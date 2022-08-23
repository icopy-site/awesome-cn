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

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) 在贡献之前.*

## Frameworks

这些框架使自定义 ZSH 设置更加容易.

您可以在以下位置找到各种框架的一些有趣的性能时序比较.

- [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
- [pm-perf-test](https://github.com/z-shell/pm-perf-test) - 用于在多个 ZSH 框架上运行性能测试的工具.
### [alf](https://github.com/psyrendust/alf)

 **Alf** 是一个超快速且可配置的 ZSH 框架； 它是仿照 [Prezto](https://github.com/sorin-ionescu/prezto) 和 [Antigen](https://github.com/zsh-users/antigen) 在利用 [Oh-My-Zsh](https://ohmyz.sh) under the covers; 和 offers st和ard defaults, aliases, functions, auto completion, automated updates 和 installable prompt themes 和 plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 **ansible-role-zsh** 是一个零知识安装的 ansible 角色. 它用 [antigen](https://github.com/zsh-users/antigen) 管理捆绑包和 [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyz.sh) . 可以有条件地加载包. 默认情况下，它包括 powerlevel9k 主题、自动建议、语法高亮和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) 和 [fzf-marks](https://github.com/urbainvaes/fzf-marks) . 完全可定制.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

 **Ant-zsh** 是一款小巧轻便的 ZSH 配置环境，可满足特殊定制需求. 它包括插件、主题和基本的方便设置.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler [antigen](https://github.com/zsh-users/antigen) 用 Golang 写的. 更多详情可在 [http://getantibody.github.io/](http://getantibody.github.io/).

### [antidote](https://getantidote.github.io/)

**Antidote** 是一个 ZSH 插件管理器，从头开始考虑性能.

它速度很快，因为它可以同时执行操作，并生成一个超快速的静态插件文件，您可以将其包含在 ZSH 配置中.

它是用 ZSH 原生编写的，经过了很好的测试，并且在哪里 [Antibody](https://github.com/getantibody/antibody) 离开了.

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** 替代 [antigen](https://github.com/zsh-users/antigen) 优化启动“zsh”会话时的低开销. 它会自动为您克隆插件.

### [antigen](https://github.com/zsh-users/antigen)

 **Antigen** 是一小组功能，可帮助您轻松管理外壳 (ZSH) 插件，称为捆绑包. 这个概念与典型的 vim+pathogen 设置中的包几乎相同.  Antigen 之于 ZSH，Vundle 之于 vim.  Antigen 可以加载 oh-my-zsh 主题和插件，并会自动为您克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

 **Ax-ZSH** 是 ZSH 的模块化配置系统. 它提供了合理的默认值，并且可以通过插件进行扩展.

**Ax-ZSH** 与 [Powerlevel10k](https://github.com/romkatv/powerlevel10k) 和其他扩展，包括兼容的插件 [oh-my-zsh](https://ohmyz.sh/).

### [dotzsh](https://github.com/dotphiles/dotzsh)

 **Dotzsh** 努力实现平台和版本独立. 在旧版本的 ZSH 下运行时，某些功能可能会丢失，但它应该会完全降级，并允许您在不同操作系统的多台机器上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

 **fresh** 是一个工具，可以将其他人的 shell 配置（别名、函数等）导入到您自己的配置文件中. 我们还支持 ackrc 和 gitconfig 等文件. 将其视为您的点文件的 Bundler.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** 是 ZSH 的简约插件管理器.

- 重新采购`.zshrc`时没有崩溃或双重插件加载
- 与其他框架不同，Miniplug 不会污染您的 `$PATH`
- 只做最低限度的管理插件

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器.

Features:

- 从 GitHub 获取和加载插件
- 加载本地插件
- 加载主题

### [oh-my-zsh](https://ohmyz.sh/)

 **oh-my-zsh** 是一个社区驱动的框架，用于管理您的 ZSH 配置. 包括 120 多个可选插件（rails、`git`、macOS、`hub`、`capistrano`、`brew`、`ant`、macports 等），超过 120 个主题为您的早晨增添趣味，以及一个自动更新工具这样可以轻松跟上社区的最新更新.

### [PMS](https://github.com/JoshuaEstes/pms)

 PMS 允许您以有助于减少设置时间并提高生产力的方式管理您的外壳. 它支持主题（更改 shell 的外观）、插件（向 shell 添加功能）和点文件管理.

 PMS 框架还允许您在不同的 shell 中使用相同的框架. 在您的个人笔记本电脑上使用 ZSH，并在远程服务器上使用 bash. 想试试“鱼”吗？ 来吧，尝试不同的贝壳.

### [prezto](https://github.com/sorin-ionescu/prezto)

 **Prezto** 通过健全的默认值、别名、函数、自动完成和提示主题丰富了 ZSH 命令行界面环境. 有一些 [prezto](https://github.com/sorin-ionescu/prezto)-特定插件在 [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** 是 ZSH 的轻量级插件管理器.

### [sheldon](https://github.com/rossmacarthur/sheldon)

一个快速、可配置的 shell 插件管理器.

- 可以管理
  - 任何 `git` 存储库.
    - 分支/标签/提交支持.
    - 对 GitHub 存储库的额外支持.
    - 对 Gists 的额外支持.
  - 任意远程文件，只需指定 URL.
  - 本地插件，只需指定目录路径.
- 使用高度可配置的安装方法 [handlebars](http://handlebarsjs.com/) 模板.
- 超快速并行安装.
- 配置文件使用 [TOML](https://github.com/toml-lang/toml) 句法.
- 使用锁定文件更快地加载插件.

### [shplug](https://github.com/dtrugman/shplug)

用于管理 shell 环境的简单解决方案. 适用于 `bash` 和 `zsh`. 使用 `git` 存储库可以轻松地在多台机器上同步您的环境.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** 是一个 ZSH 框架，旨在促进管理，而不是命令它.

### [tzpm](https://github.com/notusknot/tzpm)

最小的 ZSH 插件管理器. 仍在开发中.

### [uz](https://github.com/maxrodrigo/uz)

ZSH 微插件管理器.

### [yazt](https://github.com/bashelled/yazt)

 **Yazt** 是一个简单的 ZSH 主题管理器，它与几乎所有东西都兼容. 你可以在插件中使用提示，混合 &#39;n&#39; 匹配两个主题，稍加修改，你甚至可以在 `bash` 中使用它.

### [zapack](https://github.com/aiya000/zsh-zapack)

**zapack** 是一个基本的快速最小 ZSH 插件加载器.

### [zcomet](https://github.com/agkozak/zcomet)

 **zcomet** 是一个简约的 ZSH 插件管理器，无需缓存即可让您快速获得提示（请参阅基准）. 除了加载和更新存储在 `git` 存储库中的插件外，它还支持延迟加载插件（进一步减少启动时间）以及下载和获取代码片段.

### [zeesh](https://github.com/zeekay/zeesh)

 **Zeesh** 是一个跨平台的 ZSH 框架. 它类似于，但不兼容， [oh-my-zsh](http://ohmyz.sh/) . 它具有模块化的插件架构，使其易于扩展. 它有一组丰富的默认值，但被设计为尽可能轻量级.

### [zgem](https://github.com/qoomon/zgem)

**zgem** 是 ZSH 的插件管理器，支持从 git、http 和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** 是一个轻量级的 ZSH 插件管理器，灵感来自 [Antigen](https://github.com/zsh-users/antigen) . 目标是在启动 shell 时有最小的开销，因为没有人喜欢等待.  **目前没有积极维护**，我建议您使用 [zgenom](https://github.com/jandamm/zgenom) 取而代之的是 fork，它被积极维护和扩展.

### [zgenom](https://github.com/jandamm/zgenom)

ZSH 的轻量级插件管理器，它是一个扩展了辉煌的分支 [zgen](https://github.com/tarjoilija/zgen) 并提供更多功能和错误修复，同时完全向后兼容.

为了在新的终端会话期间保持快速加载，`zgenom` 会生成一个静态的 `init.zsh` 文件，它只会获取您的插件并将它们附加到您的 `fpath` 中.

这通过在每个 shell 会话启动期间不必执行耗时的逻辑（插件检查、更新等）来最小化启动时间. 不利的一面是，每当您更新 `.zshrc` 中的插件列表时，都必须使用 `zgenom reset` 手动刷新 init 脚本.

Zgenom 可以加载 [oh-my-zsh](http://ohmyz.sh/)-兼容和 [prezto](https://github.com/sorin-ionescu/prezto)- 兼容的插件和主题，当您将它们添加到插件列表时，它们会自动为您“git clone”插件.

### [ZI](https://github.com/z-shell/zi)

 **ZI** 是 ZSH 的瑞士军刀. 以前称为`zplugin`和`zinit`. 紫—— [Wiki Pages](https://z-shell.pages.dev/).

奖励：你可以使用 [zi-console](https://github.com/z-shell/zi-console) 查看和更改 ZSH 会话的状态（例如：列出和卸载插件）并从磁盘中删除插件和片段.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** 是一个 ZSH 配置系统，旨在吸引更多高级用户并遵循 vim-pathogen 的简单方法.

### [zim](https://github.com/zimfw/zimfw)

**Zim** 是一个 ZSH 配置框架，具有极快的速度和模块化扩展.

### [Zinit](https://github.com/zdharma-continuum/zinit)

**Zinit** 是一个创新的并且可能（由于 Turbo）最快的插件管理器，它支持：

 - Turbo 模式 – ZSH 启动速度提高 80%！ 例如：不是 200 毫秒，而是 40 毫秒
- 完成管理（有选择地禁用和启用完成）
- 片段（↔ 通过 URL 下载的常规文件，例如：脚本）并通过它们 Oh My Zsh 和 Prezto 插件支持（→ 低开销）
- 附件（↔ Zinit 扩展）
- 报告（来自插件加载 - 插件不再是黑匣子）
- 插件卸载（允许例如：动态主题切换）
- `bindkey` 捕获和重新映射
- 包
- 清理 `fpath`（数组 `$fpath` 不用于添加完成和自动加载功能，因此它保持简洁，而不是臃肿）
- 服务↔单实例后台插件
- 此外，一般来说：ZSH 插件标准中的所有机制 - Zinit 是该标准的参考实现.

该项目非常活跃——目前 &gt; 3100 次提交.

### [zit](https://github.com/thiagokokada/zit)

 **zit** 是 ZSH 的插件管理器. 它是最小的，因为它实现了作为插件管理器的最低要求：它允许用户从 `git` 存储库（和 `git` 存储库，这就是名称的原因）安装插件，获取插件并更新它们. 它没有实现花哨的功能，例如清除已删除插件、自动编译已安装插件、oh-my-zsh/prezto/其他 ZSH 框架的别名、构建二进制文件、“$PATH”操作等.

### [znap](https://github.com/marlonrichert/zsh-snap)

 **:zap:Znap** 是一个轻量级的插件管理器和用于 ZSH 的 `git` 存储库管理器，易于理解. 虽然专门为 ZSH 插件量身定制，但 **Znap** 也可用作管理 `git` 存储库的通用实用程序.

Znap 可以：

 - 使任何提示立即出现. 只需一个命令即可将启动时间从 ~200ms 减少到 ~40ms.
- 异步编译你的插件和函数.
- 缓存那些昂贵的`eval $(commands)`.
- 并行克隆或拉取多个存储库.
- 无需重新输入即可重新克隆所有存储库.
- 多回购管理
- 自动 `compinit` 和 `bashinit` - 你的 `.zshrc` 中不再需要它们，znap 会根据需要自动执行它们.

### [zoppo](https://github.com/zoppo/zoppo)

 **Zoppo** 是 ZSH 的残缺配置框架. 正如一句意大利谚语所说：“chi va con lo zoppo, impara a zoppicare”，我们意识到我们是带着跛子走路的，现在自己也会变成跛子.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** 是一个轻量级的 ZSH 插件和主题管理框架.

### [zpico](https://github.com/thornjad/zpico)

小巧的 ZSH 包管理器. 没有多余的装饰，没有臃肿，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** 是下一代 ZSH 插件管理器.

- 可以管理一切
  - ZSH 插件/UNIX 命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  - 要点文件（[gist.github.com](https://gist.github.com/discover))
  - 外部管理的插件，例如， [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) 插件/主题
  - 二进制工件 [GitHub Releases](https://help.github.com/articles/about-releases/)
  - 本地插件
  - 等等（你可以添加你 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- 支持延迟加载
- Branch/tag/commit support
- 更新后，加载后挂钩
- 包之间的依赖关系
- 不像 [antigen](https://github.com/zsh-users/antigen), 不需要 ZSH 插件文件 (`*.plugin.zsh`)
- 交互式界面（[fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- 减少缓存机制 [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) 是一个插件管理器 [ZSH](http://www.zsh.org/) 它结合了命令式和声明式方法. 在第一次运行时，zpm 会做复杂的逻辑并生成一个缓存，之后只会使用缓存，所以它使这个框架非常快.

- 最快的插件管理器（真的，第一次运行后，zpm根本不会用）
- 支持异步加载
- 包之间的依赖关系
- **zpm** 在 Linux、macOS、FreeBSD 和 Android 上运行.
- **zpm** 插件兼容 [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** 是一个快速、简单的 ZSH 插件管理器，用 Rust 编写，可以使用 `cargo install zr` 轻松安装.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** 是一个类似于 Vundle/Vim 的 ZSH 插件管理器，允许您...

- 在 `.zshrc` 中跟踪和配置您的插件
- 安装 ZSH 插件
- 更新 ZSH 插件
- 按名称搜索所有可用的 ZSH 插件
- 清理未使用的插件
- 在*单个命令中运行上述操作*
- 管理已安装插件的 __Source Plugins__

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** 旨在通过 ztanesh 项目提供的配置提高您的 UNIX 命令行体验和生产力：这些工具将使您的 shell 更强大且更易于使用.

### [ztheme](https://github.com/SkyyySi/ztheme)

**ztheme** 是一个小而快的 ZSH 主题引擎.

### [ztupide](https://github.com/mpostaire/ztupide)

一个简单快速的 ZSH 插件管理器. 它使用 `zcompile` 和异步加载来加快你的 shell 启动时间.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** 是 ZSH 5 或更高版本的环境管理器，旨在使您无需编写任何代码即可轻松管理 shell.

- 无需编辑文件即可轻松管理您的 shell 环境.
- 创建别名、函数和环境变量，并在下次 shell 启动时提供给您.
- 使用简单的命令从 `$path`、`$fpath` 和 `$cdpath` 添加和删除目录.
- 轻松安装包、插件和主题，并立即提供给您.

## Setups

本节用于完整设置插件 - 它们不是框架，但它们也不是简单的插件/主题.

### zgenom

- [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用 ZSH 的简单快速入门 [zgenom](https://github.com/jandamm/zgenom) . 这会自动配置 ZSH 以使用 [zgenom](https://github.com/jandamm/zgenom) 加载精选（但易于定制）的插件集合，并定期自动更新自身、插件和快速入门工具包本身.

### zinit

- [ZPWR](https://github.com/MenkeTechnologies/zpwr) - 一个极其强大的自定义终端环境，建立在 [Zinit](https://github.com/zdharma-continuum/zinit) 以获得最大速度. 一个完整的终端配置框架，包括 `zsh`、`tmux`、`fzf`、`vim` 和 spacemacs 配置. 这包括：

- 11.5k+ 选项卡完成
- 1.9k+ 别名
- 330 多个 git 别名
- 350 多个 zpwr 子命令
- 2.1k 功能
- 150+ zpwr 环境变量
- 170 多个 perl、python、bash、zsh 脚本
- 2.8k 行 README.md
- 46k+ 地点
- 1 行安装

## Tutorials

### Generic ZSH

- [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)， 和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) 以实现极其高效的开发人员工作流程.
- [adamnorwood-zsh](https://github.com/adamnorwood/adamnorwood-zsh/) - 一个极简但可读的 ZSH 设置，基于 [oh-my-posh](https://ohmyposh.dev/).
- [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) - 实际上不是 Arch 或 Linux 特定的.
- [GH](https://github.com/gustavohellwig/gh-zsh)  - 在基于 debian/Ubuntu 的 linux 上设置 ZSH. 安装 [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/)， 和更多.
- [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - 关于如何安装和配置 ZSH shell 的初学者友好教程.
- [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos 介绍 ZSH 和 oh-my-zsh 的视频.
- [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖了 ZSH 的一些 Bash 没有的特性，并使用了 oh-my-zsh.
- [rs-example](https://github.com/al-jshen/zshplug-rs-example) - 一个示例插件，展示了 Rust 程序如何监听和处理来自 ZSH 的命令.
- [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - 幻灯片演示.
- [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - 为 oh-my-zsh 初学者编写了一个快速设置文档，展示了如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示符、提示符处的语法高亮、自动提示和自定义 iTerm 2 主题.
- [zephyr](https://github.com/mattmc3/zephyr) - Zephyr 使用内置的 Zsh 功能来设置更好的默认选项、完成、键绑定、历史记录等等.
- [ZSH for Humans](https://github.com/romkatv/zsh4humans)  - ZSH 的交钥匙配置，旨在开箱即用. 它将一组精选的 ZSH 插件组合成一个连贯的整体，感觉就像一个成品，而不是一个 DIY 入门套件.
- [ZSH Pony](https://github.com/mika/zsh-pony) - 涵盖在没有框架的情况下自定义 ZSH.
- [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - Christian Schneider 详尽的 ZSH 技巧列表.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

- [belak/zsh-utils](https://github.com/belak/zsh-utils) - 一组最小的 ZSH 插件，旨在低摩擦和低复杂性.
- [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean 关于从 oh-my-zsh 切换到抗原的文章.
- [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis 对 Antigen 的介绍.

### Oh-My-Zsh

- [Configuration to use Hyper.js as a ZSH terminal with a Windows Subsystem Linux on windows 10, with Oh My Zsh and the Powerlevel10k theme](https://github.com/jkergal/hyperjs-wsl-zsh-powerlevel10k-config-on-windows/) - 如何让 Oh-My-ZSH 在 WSL 上运行.
- [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - Dien Bui 的 oh-my-zsh 初学者指南
- [iTerm2 + Oh-My-ZSH: Supercharge Your Mac Terminal](https://catalins.tech/improve-mac-terminal) - Catalin Pit 关于在 macOS 上开始使用 Oh-My-ZSH 的教程.
- [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - Karl Hadwen 在 macOS 上使用 Oh My Zsh 的初学者指南
- [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders Ubuntu 安装指南
- [One Key Linux Setup](https://github.com/miracleyoo/one-key-linux-setup) - `zsh`、`oh-my-zsh`、`tmux`、`python` 支持和其他软件包的简单设置（仅限 ubuntu）.
- [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html)  - 2011 年 ZSH 降临日历的一部分. 涵盖 oh-my-zsh 和 zshuery.

### Prezto

- [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss 关于使用 Prezto 的博文， [Tmux](https://tmux.github.io) ＆Tmuxinator.
- [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert 关于迁移到 Prezto 的博客文章.

### Zgen

- [rad-shell](https://github.com/brandon-fryslie/rad-shell) - 功能丰富、速度极快的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)， 和 [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

- [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh)  - :crystal_ball: 真棒，可定制的 Zsh 入门工具包 :stars::stars:. 包括电力线， [fzf](https://github.com/junegunn/fzf) 在某些终端中集成，天气和图像查看.
- [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - 真实世界的配置文件（基本上是 `.zshrc` 文件的集合）保存 [zinit](https://github.com/zdharma-continuum/zinit) 调用.

### ZSH on Windows

#### [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only.

  - `ConEmu`/`zsh` 开箱即用配置为在 `ConEmu` 重启后恢复以前打开的选项卡和 shell 工作目录
  - 开始新的 SuperConsole 会话时在干净和继承的环境之间进行选择
  - 自定义彩色方案，各种命令的彩色输出
  - 包括`MSYS2`，`zsh`和预装的必要软件，使用zsh-grml-config
  - 用途 [Antigen](https://github.com/zsh-users/antigen) 用于 ZSH 主题和配置管理
  - 启用了许多 ZSH 插件来激活完成、突出显示和历史记录，以便最舒适地使用
  - 为 `MSYS2` 环境配置了正确的 `git` 和 `git lfs` 支持的 Git-for-Windows 存储库，已经安装了 `git` 客户端.
  - `git` 的 `ssh-agent` 开箱即用，将您的密钥添加到 `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` 目录
  - 非阻塞 ZSH 提示状态更新感谢 [agkozak-zsh-prompt](https://github.com/agkozak/agkozak-zsh-prompt)
  - 为“MSYS2”定制的 Command-not-found 处理程序建议安装什么包
  - 将 `nano` 设置为主编辑器，启用 `nano` 语法高亮
  - 添加到“ConEmu/msys64/3rdparty”的自定义帮助脚本

## Plugins

- [1999](https://github.com/DTan13/zsh1999)  - 电力线式主题. 包括 `git` 状态装饰、网络和电池状态.
- [1password](https://github.com/agpenton/1password-zsh-plugin) - 添加 [1Password](https://1password.com/) 功能包括包装“op”命令的“opswd”命令. 它将服务名称作为参数并将该服务的密码复制到剪贴板.
- [256color](https://github.com/chrissicool/zsh-256color)  - 使用 256 色增强终端环境. 它查看所选的 `TERM` 环境变量，并查看是否有相应的 ncurses 的 terminfo 以及 256 种颜色可用. 结果是多色终端（如果可用）.
- [abbr (olets)](https://github.com/olets/zsh-abbr) - 管理自动扩展的缩写，当你点击空间时，内联扩展，灵感来自鱼壳.
- [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - 从一些 oh-my-fish 主题中添加 `theme_title_use_abbreviated_pa​​th` 参数的功能.
- [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - 提供类似于 `vim` 的缩写扩展的功能.
- [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH 插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
- [actiona](https://github.com/matthieusb/act) - 让打电话更容易 [actiona](https://github.com/Jmgr/actiona) 命令行中的脚本. 包括制表符补全.
- [activate-py-environment](https://github.com/se-jaeger/zsh-activate-py-environment) - 在遍历目录时自动检测并激活您的 python 环境（`poetry`、`virtualenv` 和 `conda`）.
- [alacritty](https://github.com/casonadams/alacritty-shell) - 控制 [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) 配色方案.
- [alehouse](https://github.com/sticklerm3/alehouse) - 包含短别名 [brew](https://brew.sh) 命令，灵感来自 `betterbrew`.
- [alias-finder](https://github.com/akash329d/zsh-alias-finder)  - 当您使用先前已别名的命令时显示别名. 有助于记住您过去定义的别名. 编写为纯 ZSH 脚本以提高速度
- [alias-tips](https://github.com/djui/alias-tips) - 一个 oh-my-zsh 插件，可帮助记住您曾经定义的那些别名.
- [alias](https://github.com/xylous/alias-zsh) - 用于管理别名的工具.
- [allergen](https://github.com/stanislas/allergen) - 与 Antigen 一起使用的自定义 ZSH 插件的集合.
- [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除先前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) `bash` 的插件.
- [alt-and-select](https://github.com/raisty/alt-and-select)  - 将 alt-c（复制）、alt-v（粘贴）、alt-x（剪切）键盘快捷键绑定到命令：copy-region-as-kill、yank、kill-region. 将执行命令重新映射到 Alt-Shift-X.
- [ansible](https://github.com/sparsick/ansible-zsh) - 一个插件 [Ansible](https://www.ansible.com/).
- [ansimotd](https://github.com/yuhonas/zsh-ansimotd) - 在登录 shell 启动时添加老式酷炫的 ANSI 艺术.
- [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气，带有 ANSI 颜色和 Unicode 符号.
- [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH 脚本帮助 `git` 变基.
- [anyframe](https://github.com/mollifier/anyframe) - ZSH 的 peco/percol/fzf 包装插件.
- [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理 Apache2 的别名和功能.
- [apparix](https://github.com/micans/apparix) - 带有跳转到书签、子目录选项卡完成、远程列表等的命令行目录书签.
- [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 添加 MacBook Pro 触控栏支持 [iTerm 2](https://iterm2.com).
- [appup](https://github.com/Cloudstek/zsh-plugin-appup)  - 在当前目录（例如您的应用程序）中检测到 `docker-compose.yml` 或 `Vagrantfile` 时添加 `start`、`stop`、`up` 和 `down` 命令. 只需运行 `up` 并开始编码！
- [arc](https://github.com/anton-rudeshko/zsh-arc) - 为 Yandex 版本控制系统添加别名.
- [arduino](https://github.com/raghur/zsh-arduino)  - 添加脚本以从命令行构建、上传和监控 arduino 草图. 需要 [`jq`](https://stedolan.github.io/jq/).
- [artisan](https://github.com/jessarcher/zsh-artisan) - 用于 ZSH 的 Laravel `artisan` 插件可帮助您从项目树中的任何位置运行 `artisan`，并通过选项卡完成！
- [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - AsciiDoctor 的插件.
- [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) 和 [direnv](https://github.com/asdf-community/asdf-direnv).
- [asdf-prompt](https://github.com/CurryEleison/zsh-asdf-prompt) - 提供可在提示中使用的功能，显示当前工具版本的版本信息.
- [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持 Ruby、Node.js、Elixir、Erlang 等.
- [assume-role](https://github.com/weizard/assume-role)  - ZSH 插件可让您轻松承担 AWS IAM 角色. 包括完成.
- [async](https://github.com/mafredri/zsh-async)  - 在 ZSH 中运行异步任务的库，无需任何外部工具. 允许您运行多个异步作业，强制执行唯一作业（同一作业的多个实例不会运行），刷新所有当前正在运行的作业并创建多个工作人员（每个工作人员都有自己的工作）.
- [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) 插件，可让您在其中启动文件或文件夹 [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
- [atuin](https://github.com/ellie/atuin)  - 用 SQLite 数据库替换你现有的 shell 历史，并为你的命令记录额外的上下文. 此外，它还通过 Atuin 服务器在机器之间提供可选且完全加密的历史同步.
- [aur-install](https://github.com/redxtech/zsh-aur-install) - 从 AUR 安装软件包的小插件.
- [auto-color-ls](https://github.com/gretzky/auto-color-ls) - 使用“colorls”自动列出目录.
- [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - 打印出一头牛的 ASCII 图片，在每个 ZSH 开始时说一句随机警句.
- [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh)  - 自动完成单词和列表选择. 最初是 y.fujii 的 incr-0.2.zsh<y-fujii at mimosa-pudica.net>  .
- [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - 自动运行 `ls` 或 `color-ls` 如果在 `cd` 上可用.
- [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - cd 到新目录时自动 `ls`.
- [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - 长时间运行的任务完成时自动发出通知.
- [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - 自动切换到给定目录中指定的节点版本.
- [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - 在您键入时自动列出完成，并提供直观的键绑定来选择和插入它们.
- [autodark](https://github.com/vbwx/zsh-autodark) - 如果启用暗模式（仅限 macOS），则切换到另一个终端配置文件.
- [autodotenv](https://github.com/nocttuam/autodotenv) - 当您将 `cd` 放入包含 `.env` 文件的目录时，会提示您加载变量.
- [autoenv-extended](https://github.com/zpm-zsh/autoenv) - 的扩展版本 [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
- [autoenv](https://github.com/Tarrasch/zsh-autoenv) - 如果一个目录包含一个`.env`文件，当你`cd`进入它时它会自动执行.
- [autojump](https://github.com/wting/autojump)  - 一个学习的 `cd` 命令 - 从命令行轻松导航目录. 安装 autojump-zsh 以获得最佳效果.
- [autopair](https://github.com/hlissner/zsh-autopair)  - 用于自动关闭、删除和跳过匹配分隔符的 ZSH 插件. 仅在 ZSH 5.0.2 或更高版本上测试.
- [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - 一个 `zle` 小部件（“zsh 插件”），它会自动在某些命令的参数周围加上引号.
- [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)- 类似 ZSH 的快速/不显眼的自动建议.
- [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv)  - ZSH 插件在遍历目录时自动切换 python virtualenvs 和 pipenvs. 自动检测 [pipenv](https://pypi.org/project/pipenv/) 和 [poetry](https://python-poetry.org/) 项目.
- [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - 一个叉子 [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) for the [Antibody](https://getantibody.github.io) 插件管理器，增加了配合静态加载的能力.
- [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - [Antigen](https://github.com/zsh-users/antigen) 不做自动更新，比如 [oh-my-zsh](https://ohmyz.sh/) . 这个插件为 `antigen` 添加了自动更新，`antigen` 和你的配置中加载的包.
- [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - [oh-my-zsh](https://ohmyz.sh/) 不会自动更新非核心插件，这会在 `$ZSH_CUSTOM` 目录中添加插件自动更新 `git` 存储库.
- [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - 基于 sweharris 的 AWS CLI MFA 插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa) . 支持在配置文件中指定“mfa_device”.
- [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - AWS MFA 插件.
- [aws-plugin](https://github.com/pookey/zsh-aws-plugin)  - 为 `aws` 命令添加辅助函数. 包括 mfa 和 `assume-role` 助手.
- [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - 使用 `aws-upload` 提高您的工作效率.
- [aws-vault](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault) . 包括制表符补全.
- [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - 为版本 2 提供补全支持 [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) 以及一些用于管理 AWS 配置文件并将其显示在提示中的实用程序.
- [aws](https://github.com/apachler/zsh-aws) - 从原来的分叉 [oh-my-zsh](https://ohmyz.sh/) [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws) . 包括 `awscli` 的补全和一些用于管理 AWS 配置文件并在提示中显示它们的实用程序.
- [awsume](https://github.com/Sordie/AWSume) - 可以显示当前的插件 [awsume](https://github.com/trek10inc/awsume) 轮廓.
- [azcli](https://github.com/dmakeienko/azcli) - 使用 Azure cli 工具的助手.
- [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - 从 cli 中使用 Azure keyvaults 变得不那么冗长.
- [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - 显示有关 Azure 当前订阅和租户的信息.
- [backcountry](https://github.com/jvzaniolo/zsh-backcountry) - 管理偏远地区的项目.
- [background](https://github.com/zpm-zsh/background) - 在后台执行功能的 ZSH 插件.
- [base16](https://github.com/base16-project/base16-shell)  - 添加一个脚本以允许您更改 shell 的默认 ANSI 颜色，但最重要的是，更改 shell 的 256 色空间的 17 到 21 色（如果您的终端支持）. 这个脚本可以在为应用程序提供额外的 base16 颜色的同时，尊重 shell 的原始明亮颜色（例如，亮绿色仍然是绿色等等） [Vim](https://www.vim.org).
- [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)  - 在你的外壳中打印随机棒球相关的“有趣的事实”. 取决于安装的 `fortune` 和 `cowsay`.
- [basex](https://github.com/dirkk/zsh-basex) - 增加了几个 [BaseX](http://basex.org/) 简化使用的别名.
- [bash-quote](https://github.com/jtprog/bash-quote) - 从 Bash.im 获取随机报价.
- [bash](https://github.com/chrissicool/zsh-bash)  - 使 ZSH 更兼容 Bash. 它重新定义了 source 命令，使其更像 `bash`. 它还启用了 `bash` 完成.
- [battery_state](https://github.com/Jactry/zsh_battery_state) - 在右侧提示中显示电池状态.
- [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，无需执行 `cd ../../..`.
- [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加帮助脚本以允许您创建 bitbucket PR 或在当前分支中打开目录.
- [bitwarden (game4move78)](https://github.com/Game4Move78/zsh-bitwarden) - 添加管理功能 [bitwarden](https://bitwarden.com/) 会议.
- [bitwarden (kalsowerus)](https://github.com/kalsowerus/zsh-bitwarden) - 打开一个 [fzf](https://github.com/junegunn/fzf) 包含您的小部件 [Bitwarden](https://bitwarden.com/) 保险库项目. 选择一个项目后，用户名或密码将被写入外壳或复制到剪贴板. 需要`fzf`、`jq`和`bitwarden`.
- [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)的工具包，用于将密钥/凭证安全地存储在 `git` 存储库中.
- [bofh](https://github.com/fundor333/bofh) - 添加显示随机命运的功能.
- [bol](https://github.com/ikhurramraza/bol) - 打开终端窗口时打印随机报价.
- [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - 在 macOS 上管理 `docker`.
- [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - 为 `git` 添加了一些方便的别名.
- [branch-manager](https://github.com/elstgav/branch-manager) - 用于管理 `git` 分支的插件.
- [brew (rhuang2014)](https://github.com/rhuang2014/brew) - 独立插件 [Homebrew](https://brew.sh/) 包管理器.
- [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - 独立插件 [Homebrew](https://brew.sh/) 包管理器.
- [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，可让您从命令行在浏览器中打开任何提交.
- [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - 使“brew link”不同版本的软件包变得容易.
- [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - 在命令行中切换前置“optirun”的插件.
- [bw](https://github.com/begris/bw-zsh-plugin) - 提供格式化选项和轻松访问存储在 [Bitwarden](https://bitwarden.com) 通过 Bitwarden [CLI](https://bitwarden.com/download/) . 该插件尝试在每个操作之前检索有效会话，因此事先不需要显式登录.
- [c](https://github.com/sebastiangraz/c) - 添加一些 `git` 快捷方式.
- [calc](https://github.com/arzzen/calc.plugin.zsh) - ZSH 的计算器.
- [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) 来源 [zaw](https://github.com/zsh-users/zaw)
- [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持 ZSH.
- [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm` 的包装器，添加了垃圾/回收和有用的警告.
- [case](https://github.com/rtuin/zsh-case) - 一个 ZSH 插件，添加了两个别名 `tolower` 和 `toupper` 来切换输出大小写.
- [cd-gitroot](https://github.com/mollifier/cd-gitroot) - 一个 ZSH 插件到 `cd` 到 `git` 存储库根目录.
- [cd-ls](https://github.com/zshzoo/cd-ls) - 在`cd`之后自动`ls`.
- [cd-reminder](https://github.com/bartboy011/cd-reminder) - 当 `cd`-ing 进入指定目录时显示提醒.
- [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个 ZSH 插件，用于 `cd` 到当前存储库签出的根目录.
- [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你不小心 `cd` 到服务器时，`ssh` 到服务器.
- [cdbk](https://github.com/MikeDacre/cdbk) - 一个 ZSH 插件，允许轻松创建命名目录 - 任何您想要的目录的快捷方式.
- [cdc](https://github.com/evanthegrayt/cdc)  - 更容易将目录更改为用户定义的目录列表的子目录. 包括 tab-completion、会话历史和 `pushd`、`popd` 和 `dirs` 等价物.
- [cdr](https://github.com/willghatch/zsh-cdr) - 为 ZSH 轻松设置 `cdr`.
- [change-case](https://github.com/mtxr/zsh-change-case)  - 用于在命令行中快速交换大小写的插件.  ：太阳镜：
- [cheatsheet](https://github.com/0b10/cheatsheet) - 用于轻松查看、创建和编辑备忘单的插件.
- [check-deps](https://github.com/zpm-zsh/check-deps)  - ZSH 插件的助手，允许他们展示如何安装任何缺少的依赖项. 如果您使用的是 Debian（以及 Ubuntu 等衍生产品）、Arch 及其衍生产品、Nodejs 和 ZSH 插件 [zpm](https://github.com/zpm-zsh/zpm) 框架.
- [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - 修改了 `chruby` 的克隆，以便在多个 Go 版本之间切换.
- [clean-project](https://github.com/wwilsman/zsh-clean-project)  - 从项目中删除文件（默认自动）. 有助于防止 `.DS_Store` 和 `Thumbs.db` 文件弄乱你的目录.
- [clipboard](https://github.com/zpm-zsh/clipboard)  - 添加跨平台帮助函数来访问系统剪贴板. 适用于 macOS、X11（和 Wayland）和 Cygwin.
- [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - 报告命令的状态，包括返回码和持续时间.
- [cmdtime](https://github.com/tom-auger/cmdtime) - 显示命令到终端的持续时间 [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) 插入.
- [code-review](https://github.com/xorkevin/code-review-zsh) - 在 `git merge-base target_branch base_branch` 和 `target_branch` 上启动 `git difftool`.
- [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - 计算按键并记录统计信息 [Code::Stats](https://codestats.net/).
- [codex](https://github.com/tom-doerr/zsh_codex) - 使您能够在命令行中使用 OpenAI 强大的 Codex AI.
- [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - 分叉自 [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) . 着色 `man` 输出.
- [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 为“man”页面着色.
- [colorize](https://github.com/zpm-zsh/colorize) - 为各种程序的输出着色.
- [colorls](https://github.com/Kallahan23/zsh-colorls) - 为一些 colorls 函数定义了一些有用的快捷方式.
- [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors)  - 使 CLI 中的文本更容易着色.  `red foo` 可以正常工作.
- [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - ZSH 的增强颜色.
- [command-execution-timer](https://github.com/olets/command-execution-timer) - 显示交互式 shell 命令执行所需的时间.
- [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - 一面镜子 [oh-my-zsh](https://ohmyz.sh) [command-not-found](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found) 插件，因此您不必包含所有 oh-my-zsh.
- [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - 记录复杂的命令并对其进行评论.
- [command-time](https://github.com/popstas/zsh-command-time) - 显示 ZSH 中长命令的执行时间和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 类似于 `REPORTTIME` 内置，但仅在用户 + 系统时间 &gt;= `REPORTTIME` 时输出.
- [compe](https://github.com/tamago324/compe-zsh) - 添加完成 [nvim-compe](https://github.com/hrsh7th/nvim-compe).
- [completion-generator](https://github.com/RobSis/zsh-completion-generator)  - 该插件尝试从程序的帮助文本中读取选项列表并自动生成完成功能. 请注意，这不会自动执行，您必须显式调用生成器来创建完成脚本.
- [conda](https://github.com/ThemysciraData/conda.plugin.zsh) - 添加功能以提供 `conda` 的提示段和一些基本功能的别名.
- [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) - 提供一个 `condaenv_prompt_info` 函数，它返回当前的 conda 环境名称.
- [copier](https://github.com/zshzoo/copier) - 独立的剪贴板实用程序 [oh-my-zsh](https://ohmyz.sh).
- [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - 在终端中复制和粘贴文件，就像在 GUI 中一样.
- [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个 ZSH 插件，用于通过 `ssh` 将你的 shell 配置复制到另一台机器.
- [crash](https://github.com/molovo/crash) - 为 ZSH 添加正确的错误处理、异常和 try/catch.
- [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于 Wordpress 的 Crayon 插件的 ZSH 语法突出显示.
- [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh)  - 长时间运行的任务完成时自动发出通知. 适用于 macOS 和 linux（如果安装了 `hterm-notify`）.
- [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格细分.
- [crystal](https://github.com/veelenga/crystal-zsh) - 一个插件 [Crystal](https://github.com/crystal-lang/crystal).
- [cvideo](https://github.com/aubreypwd/zsh-plugin-cvideo) - 使用 `ffmpeg` 快速压缩视频.
- [czhttpd](https://github.com/jsks/czhttpd) - 一个用 99.9% 纯 ZSH 编写的简单 http 服务器.
- [ddev](https://github.com/voronkovich/ddev.plugin.zsh) - 一个 ZSH 插件 [ddev](https://github.com/drud/ddev) 用于设置 PHP 开发环境的工具.
- [declare-zsh](https://github.com/z-shell/declare-zsh) - 一个解析器 [zinit](https://github.com/zdharma-continuum/zinit)  `.zshrc` 中的命令. 它允许您从命令行对 `.zshrc` 执行以下操作 - 启用和禁用插件添加或删除片段.
- [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - 收集有用和有趣的命令，以改善工作流程和生活质量.
- [deer](https://github.com/Vifon/deer) - ZSH 的文件导航器深受启发 [ranger](https://ranger.github.io/).
- [def](https://github.com/thevinter/def) - 允许您在您选择的任何目录中指定和运行默认命令.
- [defer](https://github.com/romkatv/zsh-defer)  - 推迟执行 `zsh` 命令，直到 `zsh` 无事可做并等待用户输入. 其预期目的是分阶段启动“zsh”. 它的工作原理类似于 Turbo 模式 [zinit](https://github.com/zdharma-continuum/zinit).
- [deno](https://github.com/Tricked-dev/deno-zsh-plugin) - 自动安装 [deno](https://deno.land/) 如果尚未安装 deno，则在启动时转到 `$HOME/.deno`.
- [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - 简单 [oh-my-zsh](https://ohmyz.sh/) 用于安装 chromium depot_tools 的插件. 安装此插件会自动将所有 chromium depot_tools 添加到您的 `$PATH` 中.
- [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - 提供 Shopify 内部开发工具的轻量级版本
- [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - 自动安装 [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) 并启用它在 ZSH 和 `git` 中的使用.
- [diractions](https://github.com/AdrieanKhisbe/diractions) - 允许您将简短的逻辑/助记名称映射到目录以快速访问它们，或在其中执行操作.
- [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors 插件，带有深色或浅色终端背景选项.
- [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - 启用 [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
- [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环浏览目录堆栈.
- [directory-history](https://github.com/tymm/zsh-directory-history) - ZSH 的每个目录历史记录，它以目录敏感的方式实现向前/向后导航以及子字符串搜索.
- [direnv](https://github.com/ptavares/zsh-direnv) - 用于安装和加载的插件 [direnv](https://github.com/direnv/direnv.git) . 灵感来自 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
- [dirrc](https://github.com/gmatheu/shell-plugins) - 当存在于你 `cd` 进入的目录中时执行 `.dirc`.
- [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在单行上显示 dirstack 信息的插件.
- [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - 通过按“ESC”两次，可以轻松地为当前或以前的命令添加“doas”前缀.
- [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - 通过按“ESC”两次，可以轻松地为当前或以前的命令添加“doas”前缀.
- [docker-aliases](https://github.com/webyneter/docker-aliases) 日常使用的“Docker”别名.
- [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在提示中显示 `docker` 容器状态.
- [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - `docker` 帮助脚本的集合.
- [docker-machine](https://github.com/asuran/zsh-docker-machine) - ZSH 的 docker-machine 插件.
- [docker-run](https://github.com/rawkode/zsh-docker-run) - 回到“自然”运行你的命令，我们将处理容器.
- [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification 插件.
- [dotbare](https://github.com/kazhala/dotbare) - 交互式点文件管理 [fzf](https://github.com/junegunn/fzf).
- [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用 `git` 使您的点文件在多台机器上保持同步.
- [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - 当您 `cd` 进入目录时，自动切换到位于名为 `.pyvenv` 的目录中的 Python 虚拟环境（您之前使用 virtualenv 程序创建的）.
- [download](https://github.com/aubreypwd/zsh-plugin-download) - 使用 `aria2c` 下载文件的助手.
- [dropbox](https://github.com/zpm-zsh/dropbox) - 一个 [dropbox](https://www.dropbox.com/) ZSH 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
- [drupal](https://github.com/yhaefliger/zsh-drupal)  - 为常见任务添加别名，并为“drush”添加标签完成. 灵感来自 [Artisan](https://github.com/jessarcher/zsh-artisan).
- [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
- [duration](https://github.com/rtakasuke/zsh-duration) - 如果超过用户可设置的运行时间，则显示命令持续时间.
- [dwim](https://github.com/oknowton/zsh-dwim)  - 尝试预测你下一步想要做什么. 它提供了一个键绑定（control-u），它将用您接下来要运行的命令替换当前（或上一个）命令行.
- [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - 一个港口 [vim-easymotion](https://github.com/easymotion/vim-easymotion) 对于 ZSH.
- [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - 列出 EC2 实例和 `ssh` 轻松登录到实例.
- [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - 添加理智、复杂的命令行编辑（例如增量历史单词完成）.
- [edward cli](https://github.com/matthieusb/zsh-edward) - 添加智能完成和别名 [edward CLI micro-service launcher](https://github.com/yext/edward).
- [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - 添加 Elixir、IEX、Mix、Kiex 和 Phoenix 的快捷方式.
- [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs)  - 使 Emacs 成为 CLI 操作的默认设置，例如编辑 git 提交消息； 设置方便的别名.
- [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - 使用 Emacs 守护进程功能，允许用户快速打开框架，无论它们是通过 `ssh` 连接在终端中打开的，还是在同一主机上打开的 X 框架.
- [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: 命令行上的表情符号补全.
- [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - 优秀的可配置 ZSH 插件 [emoji-fzf](https://github.com/noahp/emoji-fzf) . 它深受启发 [emoji-cli](https://github.com/b4b4r07/emoji-cli).
- [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 以方便的变量将大量 ASCII 艺术表情符号添加到您的环境中.
- [enhancd](https://github.com/b4b4r07/enhancd) - 一个简单的工具，通过记住用户访问的所有目录并将其用于路径名解析来提供增强的“cd”命令.
- [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - 如果在目录中找到 `.envrc` 文件，则自动加载和卸载环境变量.
- [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - 双击“`”时快速插入转义的反引号.
- [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助减少 shell 启动时间.
- [evil-registers](https://github.com/zsh-vi-more/evil-registers) - 扩展 ZLE `vi` 命令以远程访问 `vim` 和 `nvim` 编辑器的命名寄存器，以及系统选择和剪贴板.
- [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - 启用多个别名扩展 [exa](https://the.exa.website), `ls` 的现代替代品.
- [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - 添加一些别名 [exa](https://the.exa.website), `ls` 的现代替代品.
- [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - 添加别名 [exa](https://the.exa.website), `ls` 的现代替代品.
- [exa (ptavares)](https://github.com/ptavares/zsh-exa) - 安装和加载 [exa](https://github.com/ogham/exa.git).
- [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - 添加别名以使用 [exa](https://github.com/ogham/exa.git) 更轻松.
- [exa (todie)](https://github.com/todie/exa.plugin.zsh) - 集成和完成 [exa](https://the.exa.website/), `ls` 的现代替代品.
- [exa (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-exa) - 结合 [DarrinTisdale/zsh-aliases-exa](https://github.com/DarrinTisdale/zsh-aliases-exa), [hermitmaster/zsh-exa-plugin](https://github.com/hermitmaster/zsh-exa-plugin), [MohamedElashri/exa-zsh](https://github.com/MohamedElashri/exa-zsh), [ptavares/zsh-exa](https://github.com/ptavares/zsh-exa), [RitchieS/zsh-exa/](https://github.com/RitchieS/zsh-exa/), [todie/exa.plugin.zsh](https://github.com/todie/exa.plugin.zsh), [zplugin/zsh-exa](https://github.com/zplugin/zsh-exa) 和 [zsh-exa-ls-plugin](https://github.com/birdhackor/zsh-exa-ls-plugin). It also adds the default `bash` `ls` aliases 和 changes some aliases to avoid conflicts with other comm和s that [exa](https://the.exa.website) 不替换.
- [exa (zplugin)](https://github.com/zplugin/zsh-exa) - 将`ls`替换为 [ogham/exa](https://github.com/ogham/exa).
- [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - 添加别名以便您可以使用 [exa](https://the.exa.website) 作为 `ls` 和 `tree` 的替代品.
- [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](http://exercism.io/).
- [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - 用空格扩展特定别名.
- [expand](https://github.com/MenkeTechnologies/zsh-expand) - 使用空格键扩展常规别名、全局别名、不正确的拼写和短语、glob、历史扩展和 $parameters.
- [expander](https://github.com/ianthehenry/zsh-expander) - 一个“zle”小部件，允许您编写自定义扩展器并选择它们 [fzf](https://github.com/junegunn/fzf).
- [explain-shell](https://github.com/gmatheu/shell-plugins) - 打开命令 [explainshell.com](https://explainshell.com).
- [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
- [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - 使用“F1”到“F12”键制作快捷工具栏.
- [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - 破解版中的版本 [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有 [oh-my-zsh](https://ohmyz.sh).
- [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  - 帮助记住您定义和忘记的别名. 移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
- [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - 优化和改进了“zsh-users/zsh-syntax-highlighting”——更好的响应时间，可切换的高亮主题.
- [fastcache](https://github.com/QuarticCat/zsh-fastcache) - 缓存命令输出以改善 shell 启动时间.
- [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) 插件，使添加和调用重要目录的命名收藏夹变得非常容易.
- [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您最喜欢的目录.
- [fd](https://github.com/aubreypwd/zsh-plugin-fd) - 利用 [fzf](https://github.com/junegunn/fzf) 浏览目录.
- [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
- [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - 在 Firebase 项目目录或子目录中显示当前工作项目或项目别名.
- [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示中添加一个指示符，表明您位于具有 `firebase.json` 文件（又名“firebase 项目”）的目录中.
- [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 使 Apple 键盘的数字键能够在 ZSH 中被识别.
- [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - 这个插件在 TYPO3 Flow 发行版的每个子目录中都可以使用 `flow` 命令.
- [fnm](https://github.com/dominik-schwabe/zsh-fnm) - 安装并加载 [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了.
- [forgit](https://github.com/wfxr/forgit) - `git` 的实用工具，它利用了模糊查找器 [fzf](https://github.com/junegunn/fzf).
- [functional](https://github.com/Tarrasch/zsh-functional) - ZSH 高阶函数.
- [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH 插件用于模糊搜索文件并在匹配的行上立即打开匹配的文件.
- [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - 为扭曲的目录添加模糊搜索 [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) 插入.
- [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)的选项卡完成，让您轻松地在历史记录中的目录之间跳转.
- [fzf (gimbo)](https://github.com/gimbo/fzf.zsh) - 使用助手 [fzf](https://github.com/junegunn/fzf) 在 ZSH. 需要 [brew.sh](https://brew.sh).
- [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - 启用 [fzf](https://github.com/junegunn/fzf) 历史和文件搜索.
- [fzf-fasd](https://github.com/wookayin/fzf-fasd) - 整合 [fzf](https://github.com/junegunn/fzf) 和 [fasd](https://github.com/clvv/fasd) --- 使用 `fzf` 的模糊搜索完成 `z` 的制表符！
- [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) 和（可选） [bat](https://github.com/sharkdp/bat) 和 [fd](https://github.com/sharkdp/fd). Falls back to `find` 和 `cat`. Searches in the local tree of subdirectories for files.
- [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 将 `Ctrl+R` 替换为 [fzf](https://github.com/junegunn/fzf)- 驱动的历史搜索，包括日期/时间.
- [fzf-it](https://github.com/micakce/fzf-it) - 使任何命令交互式包装它 [fzf](https://github.com/junegunn/fzf) 功能.
- [fzf-marks](https://github.com/urbainvaes/fzf-marks) - 使用模糊查找器在 `bash` 和 `zsh` 中创建、导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
- [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - 更好地处理密码使用 [fzf](https://github.com/junegunn/fzf) 和 [pass](https://www.passwordstore.org/).
- [fzf-prezto](https://github.com/lildude/fzf-prezto) - 找到哪里的 Prezto 插件 [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定. 这个插件作为 Prezto `zstyle` 配置选项工作.
- [fzf-tab](https://github.com/Aloxaf/fzf-tab) - 将 ZSH 的默认补全选择菜单替换为 [fzf](https://github.com/junegunn/fzf).
- [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - 提供杀死进程并在路径中查找的功能 [fzf](https://github.com/junegunn/fzf).
- [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - 添加一些 ZLE 小部件 [fzf](https://github.com/junegunn/fzf).
- [fzf-z](https://github.com/andrewferrier/fzf-z) - 将 *z- 插件和 *[fzf](https://github.com/junegunn/fzf)- 让您可以在命令行的任何位置轻松浏览最近使用的目录.
- [fzy](https://github.com/aperezdc/zsh-fzy) - 使用的插件 [fzy](https://github.com/jhawthorn/fzy) 对于某些模糊匹配操作.
- [gcloud-project](https://github.com/avivl/gcloud-project) - 轻松选择 Google Cloud 项目.
- [gdbm](https://github.com/zdharma-continuum/zgdbm) - 添加 GDBM 作为插件.
- [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH 插件.
- [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - 添加一些别名和函数以与 Gentoo Linux 一起使用.
- [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) 日期时间插件. 在提示符中显示日期时间（`date` unix 命令）.
- [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 提醒您补水的插件.
- [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 显示当前文件夹的 npm 包版本的插件.
- [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) 当 `.rs` 或 `Cargo.toml` 存在时显示当前文件夹的 Rust 版本的插件.
- [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 用于快速下载 jQuery 库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
- [ghost-zeus](https://github.com/fontno/ghost_zeus) - 让您使用 [zeus](https://github.com/burke/zeus) 使用普通的 rails 命令.
- [gimbo-git](https://github.com/gimbo/gimbo-git.zsh) - 的一个子集 [oh-my-zsh](https://ohmyz.sh/) [git plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/git/git.plugin.zsh) 别名，加上一些新的别名，以及一些方便的功能.
- [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - 管理 [Go](https://golang.org/) 安装有 [gimme](https://github.com/travis-ci/gimme/).
- [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - 将当前命令行作为提交信息，然后一键运行`git pull`、`git add`、`git commit`和`git push`.
- [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游远程添加到您的 `git` 叉.
- [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - 破解版中的版本 [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有 [oh-my-zsh](https://ohmyz.sh).
- [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - 为常用的 `git` 命令组合创建许多有用的别名.
- [git-branches](https://github.com/Schroefdop/git-branches) - 制作一个 `git` 分支菜单，您可以切换到该菜单，而无需输入长分支名称.
- [git-clean-branch](https://github.com/gobriansteele/git-clean-branch) - 清理死的 `git` 分支.
- [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - 增强 `git` 完成以包括在远程完成中（例如来自 `git clone`）剪贴板中的任何 URL.
- [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 额外的 `git` 辅助脚本打包为插件.
- [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - 为 `git-flow` 命令添加短别名.
- [git-fuzzy](https://github.com/bigH/git-fuzzy) - 严重依赖于 `git` 的 CLI 接口 [fzf](https://github.com/junegunn/fzf).
- [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. [fzf](https://github.com/junegunn/fzf)、完成、预览一体化.
- [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - 这个函数将返回真或假，这取决于它是否发现你的 `git` 存储库是脏的.
- [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - 添加在 GitHub 上的当前分支中打开文件夹的功能.
- [git-lfs](https://github.com/nekofar/zsh-git-lfs) - 为 `git-lfs` 命令添加短别名.
- [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - 为 `git` 添加了一些功能.
- [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - 为 `git` user.email 添加提示提醒.
- [git-prune (diazod)](https://github.com/diazod/git-prune) - 允许您删除所有已合并到本地“git”存储库和/或已合并到远程源“git”存储库的分支.
- [git-prune (seinh)](https://github.com/Seinh/git-prune) - 简化在 `git` 存储库中删除合并分支的插件.
- [git-scripts](https://github.com/packruler/zsh-git-scripts) - 添加 `git-squash-branch` 和 `git-remove-merged` 命令.
- [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中.
- [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - 添加额外的 `git` 命令以使一些常见的 `git` 用法更有效.
- [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) - 包裹 [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) 使其与 [oh-my-zsh](https://ohmyz.sh) 插件系统.
- [git-sync](https://github.com/caarlos0-graveyard/zsh-git-sync) - 一个 ZSH 插件，用于同步 `git` 存储库并清理它们.
- [git-tree](https://github.com/dehlen/git-tree-zsh) - [fzf](https://github.com/junegunn/fzf) 供电的 `git worktree` 助手.
- [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree)  - 包装一些 `git worktree` 操作以简化和提高生产力. 包括 [fzf](https://github.com/junegunn/fzf) 工具.
- [git-worktrees](https://github.com/egyptianbman/zsh-git-worktrees)  - 使 `git` 工作树更实用. 包括制表符补全.
- [git](https://github.com/davidde/git) - 更换库存 [oh-my-zsh](https://ohmyz.sh/)  `git` 插件. 提供了不少有用的别名和函数. 替换默认插件的动机源于它带有一些不一致的事实，这使得一些流行的命令相当不直观，所以这个插件使别名保持一致.
- [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - 将命令添加到 `git clone` 存储库和 `cd` 到结果目录.
- [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - 克隆后自动 `cd` 到 `git` 工作目录.
- [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - 更新了分支 [oh-my-zsh](https://ohmyz.sh/) `gitfast` 插件.
- [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - 更容易在 `git` 分支之间切换.
- [gitgo (ltj)](https://github.com/ltj/gitgo) - 从命令行在浏览器中打开 Github/Gitlab 存储库（仅限 macOS）.
- [github-folders](https://github.com/buzuloiu/zsh-github-folders) - 为您组织您的 github 结帐.
- [github](https://github.com/shakir-abdo/zsh-github-plugin) - 原叉 [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) 嵌入 [oh-my-zsh](http://ohmyz.sh/).
- [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建 `.gitignore` 文件的插件.
- [gitio (denysdovhan)](https://github.com/denysdovhan/gitio-zsh) - 用于生成 GitHub 短 URL 的 ZSH 插件 [git.io](https://git.io).
- [gitio (nicolodiamante)](https://github.com/nicolodiamante/gitio) - 用途 [git.io](https://git.io/) 缩短 `git` 网址.
- [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) - 可以轻松地在提示中显示您的 `git` 状态.
- [gitsync](https://github.com/washtubs/gitsync) - ZSH 插件可改善一个人在多台机器上的同一存储库上开发的工作流程.
- [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - 用于安装、更新和加载“goenv”的插件.
- [goenv (bbenne10)](https://github.com/bbenne10/goenv) - 类似于 Python 的 virtualenvwrapper 管理 `$GOPATH`.
- [goenv (heyvito)](https://github.com/heyvito/goenv.zsh) - 自动读取当前目录中的`.goenv`文件并设置`GOPRIVATE`环境变量.
- [going_places](https://github.com/or17191/going_places) - 一个有助于使用、创建和维护 shell 位置列表的插件.
- [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - 从您的终端启动 golinks.
- [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - 在设置 GPG 代理以在 macOS 上也充当 SSH 代理时尝试做正确事情的插件.
- [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH 插件用于加密和解密文件或目录.
- [grep2awk](https://github.com/joepvd/grep2awk) - ZLE 小部件将 `grep` 命令转换为 `awk` 命令.
- [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为 `grunt` 添加自动完成功能.
- [gsh](https://github.com/cjayross/gsh) - `git` 的辅助函数集合
- [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
- [gtr](https://github.com/Zocker1999NET/zsh-gtr) - 允许使用标签名称 **release-YYYY-MM-DD-HH-MM*- 和标题 **Release YYYY-MM-DD HH:MM** 在 `git` 中快速标记发布.
- [guish](https://github.com/gcarrarom/oh-my-guish) - 实用函数和别名的集合.
- [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - 包装器插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
- [gunstage](https://github.com/LucasLarson/gunstage)  - 至少有八种方法可以在 `git` 存储库中取消暂存文件. 这是一个用于撤消 `git add` 的命令行 shell 插件.
- [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - ZSH 的“gvm”（Go 版本管理器）插件.
- [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为“gvm”（Groovy 环境管理器）提供自动完成功能.
- [hab](https://github.com/alexdesousa/hab) - 如果在更改到新目录时发现文件`.envrc` 中定义的操作系统环境变量，则自动加载它.
- [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - 当你打开一个终端时输出一个随机的黑客报价.
- [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 添加一些方便的别名 [hadoop](https://hadoop.apache.org/) 功能.
- [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH 插件 [hanami](http://hanamirb.org) 项目.
- [hangul](https://github.com/gomjellie/zsh-hangul)  - 当应该用英文输入时，自动将韩文（韩文，韩文）更正为英文. 你必须输入英文，但如果你输入韩文，它会自动更正.
- [hbt](https://github.com/lzambarda/hbt) - 基于过去命令使用的启发式 ZSH 建议系统.
- [hints](https://github.com/joepvd/zsh-hints) - 在您的编辑缓冲区下显示全局和参数标志以及其他不可完成的信息.
- [hipchat](https://github.com/robertzk/hipchat.zsh) - 从外壳发送 hipchat 消息.
- [hist](https://github.com/marlonrichert/zsh-hist) - 在 ZSH 中编辑您的历史记录，无需离开命令行.
- [histdb](https://github.com/larkery/zsh-histdb)  - 将您的历史记录存储在 SQLite 数据库中. 可以与 [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
- [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  - 通过更多交互和多行选择菜单增强历史搜索. 需要nodejs.
- [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)  - 允许您指定将自动排除命令插入永久历史记录的模式. 对于防止写入秘密特别有用.
- [history-here](https://github.com/leonjza/history-here) - 绑定 `^G` 以快速切换当前 shell 历史文件位置.
- [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - 捕获 `PageUp` 键并使用 `dialog` 打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回提示.
- [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - ZSH 的语法突出显示的多词历史搜索器，绑定到 Ctrl-R，具有高级功能（例如，将历史条目撞到历史顶部）.
- [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)  - 需要在 `zsh-syntax-highlighting` 之后加载，否则它们都会中断. 您还需要将键绑定到其功能，详细信息在 README.md 中.
- [history-sync](https://github.com/wulfgarpro/history-sync) - 一个 [oh-my-zsh](https://ohmyz.sh/) 插件 [GPG](https://www.gnupg.org/) 使用 `git` 加密的、互联网同步的 ZSH 历史记录.
- [history](https://github.com/b4b4r07/zsh-history) - 扩展历史，使其可以被 SQL 查询.
- [hitokoto](https://github.com/derry96/hitokoto) - 显示随机报价 [hitokoto.cn](https://hitokoto.cn/).
- [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - 为 [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli) . 并允许命令行交互 [Home Assistant](https://home-assistant.io/) 实例.
- [homebrew](https://github.com/digitalraven/omz-homebrew) - 插件 [homebrew](https://brew.sh) 它补充了 oh-my-zsh 内置的功能，并且可以在启用它的情况下安全运行.
- [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺少的钩子 - 用于插件和个人使用.
- [host-switch](https://github.com/LockonS/host-switch) - 在开发过程中更容易切换不同的 `/etc/hosts` 文件.
- [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - 一个简单的插件，用于将 `hub` ci-status 添加到您的 ZSH 主题.
- [hub](https://github.com/soraliu/zsh-hub) - 用于分叉模型的 ZSH 插件.
- [igit](https://github.com/ytakahashi/igit) - 使用交互式 `git` 命令 [fzf](https://github.com/junegunn/fzf).
- [ing](https://github.com/rummik/zsh-ing) - 简化的“ping”输出.
- [instant-repl](https://github.com/jandamm/instant-repl.zsh) - 为当前 ZSH 会话中的任何命令激活 REPL.
- [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - `cd` 的类似鱼的交互式选项卡完成.
- [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序、数据和日志.
- [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
- [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 在iTerm2中增加了设置标签颜色的功能，可以根据cwd或正在执行的命令自动改变颜色.
- [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - 根据当前工作目录自动更改 iTerm 2 选项卡颜色.
- [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
- [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - 从命令行管理您的 iTerm 2 的配色方案.
- [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - 设置 iTerm 2 选项卡的颜色和标题.
- [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，并让您省略整个 iterm2 网站存储库的克隆或依赖可能不同步的其他存储库.
- [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将 iTerm 2 的 ZSH 集成脚本打包到 ZSH 插件中，以避免污染您的 $HOME 目录，仅增加 2ms 的时间可以忽略不计.
- [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java 版本管理器.
- [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加 `setjdk` 命令，以便您可以在 jdk 的不同版本之间轻松切换.
- [javaVersions](https://github.com/miguefl/javaVersions) - 使用单个命令在不同的 Java 版本之间进行更改.
- [jdk-switch](https://github.com/LockonS/jdk-switch) - 一个仅用于在 jdk 版本之间切换的 macOS 插件.
- [jenkins](https://github.com/tomplex/jenkins-zsh) - ZSH 的 jenkins 插件，深受优秀 jira 插件的启发.
- [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - 用于延迟加载的 ZSH 插件 [jEnv](http://www.jenv.be/).
- [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - 添加命令 [jHipster](https://www.jhipster.tech/).
- [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - 从命令行创建 JIRA 票证.
- [jq](https://github.com/reegnz/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) 表达式. 还支持 [gojq](https://github.com/itchyny/gojq) . 需要 [fzf](https://github.com/junegunn/fzf).
- [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
- [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - 添加别名和选项卡完成 [k3d](https://k3d.io/).
- [k](https://github.com/supercrabtree/k) - 带有 `git` 状态装饰的 ZSH 目录列表.
- [kctl](https://github.com/yzdann/kctl) - 为“kubectl”添加助手别名.
- [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
- [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook 插件 [oh-my-zsh](https://ohmyz.sh).
- [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - 从 ZSH 切换 konsole 主题.
- [kube-aliases](https://github.com/Dbz/kube-aliases) - 添加函数和别名以使使用 `kubectl` 更加愉快.
- [kube-ps1](https://github.com/jonmosco/kube-ps1) - `kubectl` 的 ZSH 插件，添加当前上下文和命名空间.
- [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - 为 `kubecolor` 命令添加别名.
- [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - 简化和着色`kubectl get events -w`的输出
- [kubecolor (trejo08)](https://github.com/trejo08/kubecolor-zsh)  - 从 `kubectl` 打印彩色输出. 包括辅助函数.
- [kubectl-config-switcher](https://github.com/chmouel/kubectl-config-switcher/) - 通过 `KUBECTL` 环境变量在 `~/.kube` 中的配置文件之间切换.
- [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理 `kubectl` 的 ZSH 插件.
- [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - 安装和加载 [kubectx](https://github.com/ahmetb/kubectx).
- [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - 自动安装 [kubectx](https://github.com/ahmetb/kubectx) 和`kubens`.
- [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) 辅助函数和别名.
- [lacrimae](https://github.com/caIamity/lacrimae) - 从一组圣歌中打印一行.
- [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - 一组别名函数，用于启用 CLI [Lando](https://docs.lando.dev) 无需键入lando 即可访问它们.
- [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - 为各种添加别名 [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) 命令.
- [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - 提供接口 [Laradock](http://laradock.io/)的工作区.
- [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - 添加别名 [Laravel](https://laravel.com/) 6.
- [laravel-sail](https://github.com/ariaieboy/laravel-sail) - 添加 `sail` 命令的快捷方式.
- [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - 添加快捷方式 [Laravel](https://laravel.com/) 5, 5.1, 5.2 & 5.3.
- [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - 为常见添加一些别名 [Laravel](https://laravel.com/docs) 命令.
- [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - 全局跟踪上次使用的工作目录 [tmux](https://github.com/tmux/tmux) session 并自动跳入它以获取新的 shell.
- [last-working-directory](https://github.com/mdumitru/last-working-dir) - 破解版本的副本 [oh-my-zsh](http://ohmyz.sh/) . 跟踪上次使用的工作目录并自动跳转到新的 shell.
- [lazyload](https://github.com/qoomon/zsh-lazyload) - 延迟加载命令并加快 ZSH 的启动时间.
- [learn](https://github.com/MenkeTechnologies/zsh-learn) - MySQL/MariadB 中的学习集合，用于保存、查询和测验您学到的所有内容.
- [lesaint-git](https://github.com/lesaint/lesaint-git) - 替换 `git` 插件 [oh-my-zsh](https://ohmyz.sh)- 兼容的框架.
- [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven 插件 [oh-my-zsh](https://ohmyz.sh).
- [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - 添加脚本 [liferay](https://github.com/liferay/liferay-portal) 发展.
- [linkfile](https://github.com/JaumeRF/linkfile-zsh) - 为您喜爱的目录添加快捷方式.
- [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮.
- [listbox](https://github.com/gko/listbox) - 外壳的列表框元素.
- [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - 允许搜索 [Sublime Text](https://www.sublimetext.com) 项目并在 Sublime 中打开它们.
- [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)  - 在命令行上生成 lorem ipsum 文本. 从中获取数据 [lipsum.com](https://www.lipsum.com).
- [ls (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-ls) - 为 `ls` 添加更多别名.
- [ls (zpm-zsh)](https://github.com/zpm-zsh/ls) - 着色 `ls` 的输出.
- [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack 是一个用于 shell 脚本的日志接口.
- [lux](https://github.com/pndurette/zsh-lux)  - ZSH 插件可通过“lux”命令切换 macOS 和其他项目和应用程序的明暗模式. 高度可定制：可以通过定义变量来配置包含的项目. 高度可扩展：可以通过定义函数来添加项目. 包括一个 `macos_is_dark` 辅助函数，用于确定 macOS 暗模式是否处于活动状态以用于主题化.
- [mac-packaging](https://github.com/Temikus/mac-packaging) - 一组用于企业 Mac 打包的常用功能 [Munki](https://www.munki.org/munki/).
- [macos (joow)](https://github.com/joow/macos) - 适用于 macOS 的 ZSH 插件.
- [macos (zshzoo)](https://github.com/zshzoo/macos) - 适用于 macOS 用户的 ZSH 好东西.
- [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 使使用 Docker 和 Magento 2 变得容易.在 Magento 2 容器上加速和简化常见命令，如清理缓存、设置升级、编译 di 等等.
- [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加 `m2` 函数来运行 magento 二进制文件，添加选项卡完成.
- [magic-enter](https://github.com/zshzoo/magic-enter) - 通过将 ZSH 命令绑定到它来使您的输入键变得神奇.
- [manydots-magic](https://github.com/knu/zsh-manydots-magic) - 用于模拟 `...&#39;==`../..&#39; 等的 zle 调整.
- [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用现有标记的自动完成对其进行编辑.
- [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
- [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - 一个叉子 [oh-my-zsh](https://ohmyz.sh/) maven插件.
- [media-sync](https://github.com/redxtech/zsh-media-sync) - 一个便于在两个“rclone”位置之间复制媒体的插件.
- [mercurial](https://github.com/hcgraf/zsh-mercurial) - 摘自 [oh-my-zsh](https://ohmyz.sh) 所以你可以在没有其他 oh-my-zsh 的情况下使用它.
- [mfunc](https://github.com/hlohm/mfunc)  - 允许您动态定义持久性函数，而无需将它们添加到您的配置文件中. 这些功能永久可用，直到您将其删除.
- [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 一个 ZSH 插件，用于在普通模式和 `vi` 模式之间切换命令行.
- [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - 用于 monorepo 管理的 ZSH 插件.
- [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - 将月份名称重命名为文件名中的数字.
- [more-hooks-for-git](https://github.com/capsulescodes/more-hooks-for-git) - 为 `git add`、`git diff` 和 `git status` 添加额外的钩子.
- [mouse-status](https://github.com/gryffyn/mouse-status) - 根据状态码更改鼠标颜色，使用 libratbag.
- [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - [Metasploit](https://www.metasploit.com/) 用于轻松启动处理程序的处理程序插件.
- [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - 允许在“maven”配置之间快速切换.
- [mylocation](https://github.com/fALKENdk/mylocation) - 根据您的 IP 地址显示您当前位置的插件.
- [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - 为“mysql”表添加颜色.
- [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - 添加一些处理`mysql`的函数.
- [n](https://github.com/gretzky/n.zsh) - 使用基于项目环境的自动切换节点版本 [n](https://github.com/tj/n).
- [namelink](https://github.com/jthat/zsh-namelink) - 提供一组目录中的文件系统条目（通常是符号链接）到命名目录哈希中的对应项的自动同步映射.
- [navi](https://github.com/icatalina/zsh-navi-plugin/) - 插件 [navi](https://github.com/denisidoro/navi).
- [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - 添加`htop`-like kill、目录书签浏览器、多词增量历史搜索器等等.
- [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
- [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - 使用 Valet 启动一个新的 WordPress 网站.
- [nhl-schedule](https://github.com/Matt561/zsh-nhl-schedule) - 检索并显示 NHL 时间表.
- [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
- [nix-shell](https://github.com/chisui/zsh-nix-shell) - 允许您在 `nix-shell` 环境中使用 ZSH 作为默认 shell 的插件.
- [nnvm](https://github.com/torifat/nnvm)  - 基于 `.nvmrc` 自动切换节点版本. 需要 [n](https://github.com/tj/n).
- [node-env-installer](https://github.com/shiro-saber/node-env-installer) - 使用 `nvm` 为当前项目安装新版本和模块.
- [node-path](https://github.com/andyrichardson/zsh-node-path) - 自动将当前目录的 `npm` bin 添加到路径中.
- [node](https://github.com/srijanshetty/node.plugin.zsh) - 用于 ZSH 的 Srijan Shetty 的 nodejs 插件，具有缓存“nvm”完成和自动加载“nvm”（如果存在）.
- [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - 在您的工作目录中查找 `nodenv` 并在找到时加载它.
- [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
- [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv)  - 安装、更新和加载“nodeenv”. 灵感来自 zsh-rbenv.
- [nodo](https://github.com/nicolodiamante/nodo) - 此插件通过取消同步目录来帮助您防止 `node_modules` 目录填满您的 iCloud 存储空间，或者可以通过删除所选根目录中的所有 `node_modules` 目录来节省更多空间.
- [nohup](https://github.com/micrenda/zsh-nohup) - 按 `Ctrl-H` 将`nohup` 添加到当前命令.
- [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS 用户知道试图找出在他们的 macOS 版本上实际刷新 DNS 缓存的命令的痛苦，而这个插件让这种烦恼消失了.
- [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的接口来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) 目录中的文本文件.
- [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在 ZSH 中提供快速的笔记编辑体验.
- [notify (luismayta)](https://github.com/luismayta/zsh-notify) - 自动安装依赖项和 r2d2 声音的 ZSH 通知.
- [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - ZSH 的插件（在 macOS 和 Linux 上），如果终端应用程序在后台（或命令的终端），当命令以非零退出状态终止或完成时间超过 30 秒时发布桌面通知选项卡处于非活动状态）.
- [npm (igoradamenko)](https://github.com/igoradamenko/npm.插入.zsh)  - 添加“npm”别名和命令补全. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
- [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin)  - 添加 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
- [npm (zfben)](https://github.com/zfben/zsh-npm)  - 使用 `n` 作为带有 `noglob` 前缀等的 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
- [npms](https://github.com/torifat/npms) - 实用程序供电 [fzf](https://github.com/junegunn/fzf) 用于交互式使用 npm 脚本. 需要 [fzf](https://github.com/junegunn/fzf) 和 [jq](https://stedolan.github.io/jq/).
- [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - 每当您进入一个包含 `.nvmrc` 文件的目录时，都会自动调用 `nvm use`，该文件带有一个告诉 `nvm` 要使用哪个节点的字符串.
- [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy)  - 用于延迟加载 oh-my-zsh 的 **nvm*- 插件的插件. 它支持为多个二进制/入口点延迟加载 `nvm`，默认值为 `nvm`、`node` 和 `npm`.
- [nvm](https://github.com/lukechilds/zsh-nvm) - 用于安装、更新和加载 `nvm` 的 ZSH 插件.
- [oath](https://github.com/alexdesousa/oath)  - 管理 2FA 身份验证 6 位令牌. 这篇文章深受启发 [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
- [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - 为缺少它们的命令生成 shell 完成.
- [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - 把你的终端变成矩阵.
- [omz-git](https://github.com/aeons/omz-git) - [Oh-My-ZSH](https://ohmyz.sh/)'s [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) 插件重新打包为独立的.
- [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - 给你 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 主题而不需要 oh-my-zsh 附带的所有其他内容
- [open-create-projects](https://github.com/marcossegovia/open-create-projects) - 在 Jetbrains 中打开/创建项目.
- [open-pr](https://github.com/caarlos0/zsh-open-pr) - 从命令行打开拉取请求的 ZSH 插件.
- [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - 为常见的 openshift origin (oc) 操作添加一些快捷方式.
- [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` 别名.
- [operator](https://github.com/nivv/operator-theme) - 干净简单的主题，最适合搭配 [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
- [opp](https://github.com/hchbaw/opp.zsh) - 用于 ZSH 的 Vim 的 text-objects-ish.
- [opt-path](https://github.com/jreese/zsh-opt-path) - 自动将 `~/opt` 子路径添加到您的 `$PATH`.
- [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - 根据 macOS 的系统偏好配置代理环境变量.
- [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
- [osx](https://github.com/mwilliammyers/plugin-osx) - 添加一些常见的 macOS 相关的别名和函数.
- [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - 通过在 `.zshrc` 文件中定义 `P10K_PROMPT` 变量，添加了在 Powerlevel10k 提示主题配置文件之间轻松切换的能力.
- [paci](https://github.com/iloginow/zsh-paci) - 用于 Arch linux 包管理器的插件.
- [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - 在插件目录中轻松安装任何 Node 模块，通过由 [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) 附件.
- [packer](https://github.com/BreakingPitt/zsh-packer) - 为 Hashicorp 添加别名和自动完成 [packer](https://www.packer.io/).
- [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)  - 长时间运行命令的后台通知. 支持 Elementary OS Freya.
- [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码进入您的命令行历史记录.
- [path-ethic](https://github.com/sha1n/path-ethic)  - 帮助快速轻松地管理您的“$PATH”. 不会触及现有的 `.zshrc`、`.zprofile`，而是添加到现有环境之上.
- [pctl](https://github.com/ytet5uy4/pctl) - 切换环境变量以进行代理.
- [peco-history](https://github.com/jimeh/zsh-peco-history) - 按 `ctrl+R` 时使用 Peco 搜索 shell 历史记录.
- [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - 懒惰渗透测试仪的别名和功能.
- [per-directory-history](https://github.com/jimhester/per-directory-history) - ZSH 的每个目录历史记录，以及全局历史记录，以及使用 `^G` 在它们之间切换的能力.
- [percol](https://github.com/robturtle/percol.plugin.zsh) - 使用交互式和增量式搜索历史/恢复后台作业 [percol](https://github.com/mooz/percol).
- [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - 安装 [perlbrew](https://perlbrew.pl/) 如果尚未安装并为您的 shell 初始化它.
- [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理 Python virtualenvs [pew](https://github.com/berdario/pew)，在您移动目录时自动切换 virtualenvs.
- [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用功能以使用 [PostgreSQL](https://www.postgresql.org/).
- [ph-marks](https://github.com/lainiwa/ph-marks) - 从您的终端为pornhub 视频添加书签.
- [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - 使用 php 版本之间自动切换 [php-version](https://github.com/wilmoore/php-version) 如果目录中存在 rc 文件.
- [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
- [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - 自动加载 [phpenv](https://github.com/sptndc/phpenv) 及其完成.
- [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
- [pip-app](https://github.com/sharat87/pip-app) - 可以轻松地将 python 应用程序安装到不同的 Python virtualenvs 中，这样它们就不会与系统上的任何其他 python 要求冲突.
- [pip-env](https://github.com/iboyperson/zsh-pipenv) - 自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a `pipenv` project.
- [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)  - 如果该目录中有 Pipfile，则在进入目录时自动激活 **pipenv**. 包括 `pipenv` 完成.
- [pipenv (sudosubin)](https://github.com/sudosubin/zsh-pipenv) - 启用 `pipenv` 的 `$PATH` 并添加完成.
- [pipx](https://github.com/thuandt/zsh-pipx) - 自动完成 [pipx](https://github.com/pypa/pipx).
- [pkenv](https://github.com/ptavares/zsh-pkenv) - 安装和加载 [pkenv](https://github.com/iamhsa/pkenv.git).
- [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加 ibtool 快捷方式以生成本地化的 XIB 文件.
- [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - 用于 Rails 的 ZSH 插件.
- [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Visual Studio Code 插件，一个适用于 macOS、Windows 和 Linux 的文本编辑器.
- [plugin](https://github.com/darrenbutcher/plugin) - 创建自定义 [oh-my-zsh](https://ohmyz.sh) 样板模板中的插件. 非常以 oh-my-zsh 为中心，生成的插件需要编辑才能与其他框架一起使用.
- [pnpm (baliestri)](https://github.com/baliestri/pnpm.plugin.zsh) - 为许多常见的添加有用的别名 [pnpm](https://pnpm.io/) 命令. 包括制表符补全.
- [pnpm (ntnyq)](https://github.com/ntnyq/omz-plugin-pnpm) - 为常见添加有用的别名 [pnpm](https://pnpm.io/) 命令.
- [poetry (darvid)](https://github.com/darvid/zsh-poetry) - 自动激活和停用 [Poetry](https://poetry.eustace.io/)- 创建了 python virtualenvs.
- [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - 启用诗歌“$PATH”和自动补全.
- [posh-git-bash](https://github.com/lyze/posh-git-sh) - 在提示中添加 `git` 状态.
- [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问它以在 shell 提示中显示. 由于使用了 `/sys`，因此仅适用于 Linux.
- [pr-cwd](https://github.com/zpm-zsh/pr-cwd)  - 使用当前工作目录创建一个全局变量. 插件与集成 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
- [pr-eol](https://github.com/zpm-zsh/pr-eol) - 显示可以嵌入到提示中的 EOL 符号.
- [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - 添加一个变量，您可以使用它来显示上次命令运行的执行时间.
- [pr-git](https://github.com/zpm-zsh/pr-git) - 创建一个带有 `git` 状态信息的全局变量，可以在提示中显示.
- [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - 设置一个环境变量，您可以在以 root 身份运行时在自定义提示中使用.
- [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - 创建一个环境变量，可用于在自定义提示中显示后台作业信息.
- [pr-node](https://github.com/zpm-zsh/pr-node) - 设置一个环境变量，可用于在自定义提示中显示 nodeJS 信息.
- [pr-return](https://github.com/zpm-zsh/pr-return) - ZSH 插件，显示最后一次运行命令的退出状态.
- [presenter-mode](https://github.com/idadzie/zsh-presenter-mode)  - 在演示过程中扩展别名. 它还增加了终端窗口的对比度以增强可见性.
- [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串：165392 → 1d 21h 56m 32s.
- [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - 将原始秒数转换为人类可读的字符串.
- [prettyping](https://github.com/unixorn/prettyping) - 在标准 ping 工具周围添加一个包装器，目的是使输出更漂亮、更丰富多彩、更紧凑且更易于阅读.
- [print-alias](https://github.com/brymck/print-alias) - 每当您在命令行中使用别名时，打印带有扩展别名的命令.
- [printc](https://github.com/philFernandez/printc) - 允许您通过简单的“printc”调用以 RGB 空间中的任何颜色进行打印.
- [profile-secrets](https://github.com/gmatheu/shell-plugins)  - 将敏感变量（api 令牌、密码等）安全地保存为终端初始化文件的一部分. 使用 gpg 使用您的秘密加密/解密文件.
- [project (gko)](https://github.com/gko/project) - 在本地和 github（私有或公共存储库）上创建 node/python/ruby 项目.
- [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - 用于管理项目的插件.
- [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator)  - 生成自定义主题. 一些生成的主题需要与电力线兼容的字体.
- [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - 快速启用和禁用代理外壳环境设置.
- [proxy](https://github.com/SukkaW/zsh-proxy) - 为某些包管理器和软件配置代理设置.
- [pseudo-projectile](https://github.com/git-girl/pseudo-projectile-plugin/)  - 像emacs中的`projectile`？ 这为您的 ZSH 环境添加了类似的功能.
- [pyenv (mattberther)](https://github.com/mattberther/zsh-pyenv)  - 受 zsh-rbenv 启发. 安装、更新或加载 `pyenv`，并添加额外的功能.
- [pyenv (xlshiz)](https://github.com/xlshiz/pyenv-zsh-plugin) - 负载 [pyenv](https://github.com/pyenv/pyenv) 进入当前 shell 并通过 `pyenv_prompt_info` 函数提供提示信息. 还加载 [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) 如果可供使用的话.
- [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - 在 ZSH 中延迟加载 `pyenv` 的插件.
- [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - 懒加载 [pyenv](https://github.com/pyenv/pyenv) . 第一次调用 `pyenv` 时执行初始的 `eval &quot;$(pyenv init -)&quot;`.
- [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast)  - 使用一个命令启动 Python `venv`. 设计用于 [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
- [q (cal2195)](https://github.com/cal2195/q) - 将 `vim` 类宏寄存器添加到您的 ZSH shell.
- [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - 尾部/删除临时文件 [Q](https://github.com/y0ssar1an/q)，脏调试工具.
- [qiime2](https://github.com/misialq/zsh-qiime2) - 添加函数和别名以便使用 [Quiime 2](https://qiime2.org/) 更轻松.
- [quer-ps1](https://github.com/ya0201/qwer-ps1) - 一个高度可扩展的 ZSH 提示管理器
- [quoter](https://github.com/pxgamer/quoter-zsh) - 打开新的终端会话时显示随机报价.
- [quotify](https://github.com/dpretet/zsh-quotify) - 启动时显示我们对的鼓舞人心的编码报价.
- [qwy](https://github.com/Ryooooooga/qwy) - ZSH 模糊补全插件.
- [randeme](https://github.com/ex-surreal/randeme)  - 为每个会话选择一个随机主题. 如果您不喜欢所选主题，您可以运行 `randeme_rm` 以不再显示该主题.
- [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - 显示随机报价或事实.
- [ranger-autojump](https://github.com/fdw/ranger-autojump) - 添加 [autojump](https://github.com/wting/autojump) 支持 [ranger](https://github.com/ranger/ranger) 控制台文件管理器.
- [raspberryPi4Temperature](https://github.com/KidesLeo/RaspberryPi4TemperaturePromptPlugin/blob/main/RaspberryPi4TemperaturePromptPlugin.zsh) - 将树莓派温度放入飞船提示段
- [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - 改变你的颜色 [Razer Mouse](https://openrazer.github.io/) 基于最后执行的命令的状态. 需要 [OpenRazer](https://openrazer.github.io) linux驱动程序.
- [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - 基于 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) 插入. 该插件将安装 rbenv 并使其随时可用
- [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自 `rbenv` 插件的更快分支 [oh-my-zsh](https://ohmyz.sh/).
- [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - 基于原始版本的变体 [oh-my-zsh](https://ohmyz.sh/) `rbenv` 插件.
- [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - 灵感来自 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), 使得使用 ruby​​ `rbenv` 环境更容易.
- [rc-files](https://github.com/0b10/rc-files) - 添加用于编辑各种 rc 文件的快捷功能.
- [recall](https://github.com/mango-tree/zsh-recall) - 使使用命令历史更容易.
- [redis](https://github.com/z-shell/redis) - 会跑 [redis-server](https://redis.io/) 将其指向“redis.conf”配置文件. 这可以与 [zdharma/zredis](https://github.com/z-shell/zredis) 在 shell 之间共享变量的插件.
- [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - 如果它已被删除并重新创建，则重新进入工作目录的插件.
- [reload](https://github.com/aubreypwd/zsh-plugin-reload) - 添加快速重新加载您的`.zshrc`的功能.
- [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - 一个在每个提示上方显示提醒的插件.
- [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - 将 `...` 转换为 `../..`
- [require](https://github.com/aubreypwd/zsh-plugin-require) - 添加了“需要命令名”的功能，然后（如果 [brew](https://brew.sh) 已安装）自动 `brew install commandname` 如果尚未安装.
- [revolver](https://github.com/molovo/revolver) - ZSH 脚本的进度微调器.
- [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - 显示随机谜语.
- [ripz](https://github.com/jedahan/ripz)  - 提醒您您的别名，以便您更多地使用它们. 取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
- [robo](https://github.com/shengyou/robo-zsh-plugin) - 一个 ZSH 插件 [Robo](https://github.com/consolidation/robo/).
- [rockz](https://github.com/aperezdc/rockz) - 基于 VirtualZ 的 Lua + LuaRocks 虚拟环境管理器.
- [rust](https://github.com/cowboyd/zsh-rust) - 配置您 [rust](https://www.rust-lang.org/) 工具链，安装 [rustup](https://rustup.rs) 如果当前尚未安装.
- [rvm](https://github.com/johnhamelink/rvm-zsh) - 发起 [rvm](https://github.com/rvm/rvm) 并添加在用户的 `$PATH` 中可访问的 ruby​​gem 二进制文件（如指南针）.
- [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - 跑步时增加一些安全性 [kubectl](https://kubernetes.io/docs/reference/kubectl/) 通过在上一个“kubectl”命令后的可定义秒数后警告您所处的上下文.
- [safe-paste](https://github.com/oz/safe-paste)  - 一个安全粘贴插件. 见康拉德欧文 [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
- [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - 添加安全-`rm` 功能，以便`rm` 将文件放入操作系统的垃圾箱，而不是永久删除它们.
- [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - 当使用多个 AWS 配置文件时，例如您的阶段（开发、预生产、生产）的不同帐户，可用于确定当前导出的配置文件以及令牌是否仍然有效.
- [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - 添加支持 [saml2aws](https://github.com/Versent/saml2aws).
- [sandboxd](https://github.com/benvan/sandboxd) - 仅在需要时运行设置命令（例如 `eval &quot;$(rbenv init -)&quot;` 等），通过延迟加载加速您的 `.zshrc` 和 shell 启动.
- [saneopt](https://github.com/willghatch/zsh-saneopt) - ZSH 选项的健全默认值，本着 [vim-sensible](https://github.com/tpope/vim-sensible).
- [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - 脚本自动更新种子箱上的应用程序.
- [schroot](https://github.com/fshp/schroot.plugin.zsh) - 在提示中显示当前的 `chroot` 名称.
- [sdkman](https://github.com/ptavares/zsh-sdkman) - 安装 [sdkman](https://github.com/sdkman) 并为其添加完成和别名.
- [sealion](https://github.com/xyproto/sealion) - 允许您设置刷新提示时将出现在终端中的提醒.
- [search-directory-history](https://github.com/cmaahs/search-directory-history) - 允许对使用创建的每个目录历史记录进行复杂搜索 [per-directory-history](https://github.com/jimhester/per-directory-history) 插入.
- [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - 添加键绑定以在当前命令行上进行全局搜索和替换.
- [select](https://github.com/z-shell/zsh-select) - 具有近似匹配和 uniq 模式的多词搜索选择列表.
- [send](https://github.com/robertzk/send.zsh) - `git add`、`git commit` 和 `git push` 的单一命令可加快 `git` 工作流程.
- [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - 添加许多 `git` 别名和辅助 shell 函数.
- [session-sauce](https://github.com/ChrisPenner/session-sauce) - 一个 [fzf](https://github.com/junegunn/fzf) 用于所有项目的 tmux 会话创建和管理的界面.
- [setenv](https://github.com/kalpakrg/setenv) - 更改目录时运行脚本.
- [shelf](https://github.com/ecmma/shelf) - 可用于使用助记符为任何文件添加书签和直接访问的实用程序.
- [shellfirm](https://github.com/kaplanelad/shellfirm)  - Shellfirm 是一个方便的实用程序，可帮助避免在没有额外批准步骤的情况下运行危险命令. 当检测到有风险的模式时，您将立即收到一个小的提示挑战，以验证您的操作.
- [shift-select](https://github.com/jirutka/zsh-shift-select) - Emacs ZSH 的 shift-select 模式 - 使用 Shift 在命令行中选择文本，就像在许多文本编辑器、浏览器和其他 GUI 程序中一样.
- [show-path](https://github.com/redxtech/zsh-show-path) - 提供逐行显示`$PATH`的功能.
- [silverstein-quotes](https://github.com/silversteinsoftware/silverstein_quotes) - 在 shell 启动期间显示 Silverstein 歌曲的随机引用.
- [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - 轻松启动 python `SimpleHTTPServer` 和 `SimpleHTTPSServer` 的插件.
- [skaffold](https://github.com/todie/skaffold.plugin.zsh) - ZSH 集成和完成 [skaffold](https://skaffold.dev) 本地 Kubernetes 开发环境.
- [skim (casonadams)](https://github.com/casonadams/skim.zsh) - 试图确定在哪里 [skim](https://github.com/lotabout/skim) 安装，然后启用其模糊自动完成和键绑定.
- [skim (hackerchai)](https://github.com/hackerchai/skim-zsh) - 增加了对 [skim](https://github.com/lotabout/skim)
- [slugify](https://github.com/lashoun/slugify) - 将文件名和目录转换为网络友好格式.
- [smart-cd](https://github.com/dbkaplun/smart-cd) - 在 chpwd 之后运行 `ls` 和 `git status`.
- [smartcache](https://github.com/QuarticCat/zsh-smartcache) - 缓存命令输出以加快 shell 启动时间.
- [smartinput](https://github.com/momo-lab/zsh-smartinput) - 当您键入括号或引号时，会自动添加相应的结束括号/引号.
- [smile](https://github.com/fundor333/smile) - 添加显示随机笑脸的功能.
- [snippets](https://github.com/willghatch/zsh-snippets) - 命令行片段扩展.
- [solarized-man](https://github.com/zlsun/solarized-man) - oh-my-zsh 的插件 colour-man-pages 的修改版本，针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端中的主题.
- [spack](https://github.com/Game4Move78/zsh-spack) - 包括一些有用的别名和加载/卸载函数 [Spack](https://github.com/spack/spack) - 生成的模块. 由于它使用了 `module` 命令，它比 `spack load` 更有效.
- [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的 `ssh` 管理器.
- [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - `ssh` 的插件.
- [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - 当你 `ssh` 进入服务器时，将更新你的 `known_hosts` 文件.
- [startify](https://github.com/NorthIsMirror/zsh-startify) - 显示最近使用的 `vim` 文件、shell-util 文件、活动的 `tmux` 会话、最近运行的 `git` 命令等等.
- [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - 打印 shell 启动所需的时间.
- [stashy](https://github.com/MisterRios/stashy) - 简化使用 `git stash` 的插件.
- [statify](https://github.com/vladmrnv/statify) - 进行基本统计分析的插件.
- [sublime](https://github.com/valentinocossar/sublime) - 与官方相同 [Sublime](https://www.sublimetext.com/) 插件 [Oh My Zsh](https://ohmyz.sh/)，但是如果已经打开了当前 Sublime 窗口中的文件，这将打开文件.
- [sudo (hcgraf)](https://github.com/hcgraf/zsh-sudo) - 来自的 `sudo` 插件 [oh-my-zsh](https://ohmyz.sh/) ，提取到一个独立的. 在 emacs 模式或 vi-command 模式下按 *ESC-ESC- 在当前/上一个命令之前切换 `sudo`.
- [sudo (none9632)](https://github.com/none9632/zsh-sudo/) - 通过键入 `ESC`-`ESC` 添加 `sudo` 作为当前命令的前缀.
- [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件.
- [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - 重写股票 [oh-my-zsh](https://ohmyz.sh/) [svn](https://subversion.apache.org/) 插入.
- [switch-git](https://github.com/robin-mbg/switch-git)  - 在 `git` 存储库之间轻松切换. 只需输入`sgr<some part of you repo's name>  `，按回车，你就在那里.
- [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
- [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - 使用 dircolors 实时突出显示 ZSH 语法.
- [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  - 为您的 ZSH 添加语法高亮. 确保你加载这个_before_ [zsh-users/zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) 否则它们都会破裂.
- [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
- [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp 为系统管理员收集的工具脚本.
- [system-clipboard](https://github.com/kutsan/zsh-system-clipboard)  - 为“vi”模拟键映射添加了对 ZLE（Zsh 行编辑器）剪贴板操作的键绑定支持. 它适用于 Linux、macOS 和 Android（通过 Termux）.
- [systemd](https://github.com/le0me55i/zsh-systemd) - 为 `systemd` 添加了许多别名.
- [t32](https://github.com/chrissicool/zsh-t32)  - Lauterbach Trace32 工具集的插件. 它会自动注册字体并设置所有必要的环境变量来运行 t32 工具集.
- [tab-title](https://github.com/trystan2k/zsh-tab-title)  - 根据当前目录或正在运行的进程设置终端标签标题. 分叉自 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
- [tailf](https://github.com/rummik/zsh-tailf) - 添加带有前缀换行符而不是尾随换行符的 `tailf` 函数.
- [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - 自动完成任务簿的任务编号.
- [terminal-app](https://github.com/the8/terminal-app.zsh) - 用于与新的 macOS El Capitan Terminal.app 功能集成的插件.
- [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - 添加一个“set-term-title”功能，您可以使用它来命名终端窗口.
- [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 计算并显示通过终端运行了多少命令的插件.
- [termux](https://github.com/zpm-zsh/termux) - 增加兼容性 [Termux](https://termux.com/).
- [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - 添加 [terraform](https://www.terraform.io/) 提示的工作区.
- [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - 扩展原来 [oh-my-zsh](https://ohmyz.sh/) 具有别名和制表符补全的插件. 添加工作区（非默认时）以提示.
- [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - 添加方便别名 [terraform](https://terraform.io/)，选项卡完成和辅助功能，以在提示中添加您的 terraform 工作区.
- [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - ZSH 的 Terraform 便利函数和别名.
- [terraform (ptavares)](https://github.com/ptavares/zsh-terraform)  - 添加别名、函数和制表符补全. 还安装 [terraform-docs](https://github.com/terraform-docs/terraform-docs), [tfsec](https://github.com/aquasecurity/tfsec) 和 [tflint](https://github.com/terraform-linters/tflint).
- [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - 为 [terraform](https://terraform.io/)，以及 `terraform` 和 `terragrunt` 的补全.
- [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt), 一个薄包装 [Terraform](https://terraform.io/) 提供额外的工具.
- [tfenv](https://github.com/CDA0/zsh-tfenv) - 安装、更新和加载受启发的 `tfenv` [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
- [tfswitch](https://github.com/ptavares/zsh-tfswitch) - 安装和加载 [tfswitch](https://github.com/warrensbox/terraform-switcher).
- [tgenv](https://github.com/ptavares/zsh-tgenv) - 安装和加载 [tgenv](https://github.com/cunymatthieu/tgenv.git) . 包括手动更新 `tgenv` 的功能.
- [tgswitch](https://github.com/ptavares/zsh-tgswitch) - 安装和加载 [tgswitch](https://github.com/warrensbox/tgswitch).
- [thefuck](https://github.com/laggardkernel/thefuck) - 负载 [thefuck](https://github.com/nvbn/thefuck) （一种更正您先前命令的工具）具有缓存支持，可显着减少加载时间.
- [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - 使用的便利功能 [theia-ide](https://github.com/theia-ide/theia).
- [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - 添加一些高级绑定 [tig](https://github.com/jonas/tig) 并且还提供了一个 `tig-pick` 脚本.
- [timewarrior](https://github.com/svenXY/timewarrior) - 增加了对 [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
- [tipz](https://github.com/molovo/tipz) - 如果您有刚刚运行的命令的别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
- [title](https://github.com/zpm-zsh/title) - 允许您设置终端窗口标题.
- [titles](https://github.com/jreese/zsh-titles) - 自动窗口和标签标题 [tmux](https://tmux.github.io) 和 xterm 兼容的终端.
- [tm](https://github.com/kjhaber/tm.zsh) - 简化创建新 [tmux](https://tmux.github.io) 会话、附加到现有会话、在会话之间切换以及列出活动会话.
- [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - 自动将窗口/窗格的标题设置为当前前台命令.
- [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 支持单个服务器进程上的多个会话.
- [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - 改名 [tmux](https://tmux.github.io) 窗口自动.
- [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 使用简单的插件 [tmux](https://tmux.github.io) 与 ZSH.
- [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - 在正在运行的“vim”（或 NeoVim）会话中打开文件，从相邻 [tmux](https://tmux.github.io) 有.
- [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - 为 `tmux`、ZSH 和 Vim/NVIM 模块化创建统一的终端标题.
- [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
- [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 具有 R-EP-L 的简单 ZSH 插件 [tmux](https://tmux.github.io) 会议.
- [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - 添加一个“toggl-week”命令来显示跟踪的总工作时间 [toggl.com](https://toggl.com)
- [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  - 添加一个小部件以切换命令的前缀. 默认情况下，将 Alt+s 绑定到带有 `sudo` 的命令前缀.
- [traista](https://github.com/odgon/traista)  - 包括 `git` 状态装饰和最后一次命令运行的颜色编码退出状态. 使用深色终端主题效果更好.
- [travis](https://github.com/denolfe/zsh-travis) - 打开 [Travis CI](https://www.travis-ci.com/) 当前存储库的页面（如果存在）.
- [tre](https://github.com/redxtech/zsh-tre) - 使用 [tre](https://github.com/dduan/tre#editor-aliasing) 更轻松.
- [tsm](https://github.com/RobertAudi/tsm) - 添加一个 [tmux](https://tmux.github.io) 会话管理器.
- [tumult](https://github.com/unixorn/tumult.plugin.zsh) - 为 macOS 添加工具.
- [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - 16 个免费别名.
- [ugit](https://github.com/Bhupesh-V/ugit) - 让您撤消上一次 `git` 操作.
- [uncloudium](https://github.com/Talon1024/omz-uncloudium) - 添加帮助脚本以从 Google Chrome 网上商店下载 crx 文件.
- [undollar](https://github.com/zpm-zsh/undollar) - 从终端提示符的开头去除美元符号.
- [unique-id](https://github.com/z-shell/zsh-unique-id)  - 在其 shell 变量 `$ZUID_ID` 中提供一个唯一编号，用于标识正在运行的 Zshell 会话. 除了这个唯一的数字之外，还提供了一个唯一的代号，在 shell 变量 `$ZUID_CODENAME` 中. 一个示例用例是将日志保存在文件 `.../mylog-${ZUID_CODENAME}.log` 中，这样两个不同的 Zshell 就不会同时写入同一个文件.
- [unix-simple](https://github.com/redxtech/zsh-unix-simple) - 显示有关 unix 简单性的图形的命令.
- [unwrap](https://github.com/foxleigh81/unwrap-zsh-plugin) - 允许您在不删除内容的情况下删除目录 - 它将它们放在目录的父目录中.
- [up (cjayross)](https://github.com/cjayross/up) - 一种向上浏览目录的简单方法.
- [up (peterhurford)](https://github.com/peterhurford/up.zsh) - 添加一个向上命令到`cd`多个级别.
- [up-dir](https://github.com/sgpthomas/zsh-up-dir)  - 将 `ctrl-h` 绑定到向上导航目录. 这使得无需键入任何命令即可轻松上几个目录.
- [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - 更新自定义 [oh-my-zsh](https://ohmyz.sh/) 插件. 仅适用于 oh-my-zsh 框架.
- [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter)  - ZSH 语法高亮插件插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色. 用于检查 URL 拼写错误.
- [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - 扩展原版的功能 [oh-my-zsh](https://ohmyz.sh/) `venv` 模块.
- [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - 一个包装插件 [vagrant](https://www.vagrantup.com/) 允许从 box 目录之外调用 `vagrant` 命令. 该插件还附带了一些额外的命令，可帮助管理多个框，以及自定义选项卡完成.
- [valet](https://github.com/NasirNobin/zsh-valet/) - 从项目根目录读取 `.valetphprc` 并自动切换到该 PHP 版本.
- [vanilli.sh](https://github.com/yous/vanilli.sh) - shell 配置的轻量级起点.
- [vapor](https://github.com/notf0und/zsh-vapor) - 拉拉维尔 [vapor](https://github.com/laravel/vapor-cli) ZSH 插件可帮助您从项目树中的任何位置运行 `vapor`，并具有自动完成功能！
- [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - 帮助 vcsh 用户需要使用 `vcsh` 的 Github 存储库，以便在 `~/.zshrc` 等中自动安装.
- [velocity](https://github.com/rahulsalvi/velocity-python) - ZSH 和基于电力线的主题元素 [tmux](https://tmux.github.io).
- [venv-lite](https://github.com/gimbo/venv-lite.zsh) - 一种超轻量级的克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ; 它几乎希望您使用 [pyenv](https://github.com/pyenv/pyenv) （尽管您不必*必须），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html), （创建）仅适用于 python &gt;= 3.3.
- [venv-wrapper](https://github.com/glostis/venv-wrapper) - 提供 ZSH 功能以简化使用 `venv` 的虚拟环境管理.
- [vi-increment](https://github.com/zsh-vi-more/vi-increment) - 添加类似 `vim` 的递增/递减操作.
- [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 一个更好更友好的 ZSH `vi`(`vim`) 模式插件.
- [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似“vi”的功能.
- [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 向 ZSH 添加更多类似于 `vi` 的功能.
- [vi-motions](https://github.com/zsh-vi-more/vi-motions) - 添加新的动作和文本对象，包括带引号/括号的文本和命令.
- [vi-quote](https://github.com/zsh-vi-more/vi-quote) - 添加引用或取消引用动作的操作.
- [viexchange](https://github.com/okapia/zsh-viexchange) - 一个 `vi` 模式插件，用于在缓冲区中的两个位置之间轻松交换文本，例如 vim-exchange.
- [vim-mode](https://github.com/softmoth/zsh-vim-mode) - 友好的 `vi`-mode 绑定，添加基本的 Emacs 键、增量搜索、模式指示器等.
- [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - 允许您执行 `vim filename:123` 以将光标放在特定行上打开文件.
- [vimman](https://github.com/yonchu/vimman) - 查看 `vim` 插件手册（帮助），如 ZSH 中的 `man`.
- [vimto](https://github.com/laurenkt/zsh-vimto) - 改进了 ZSH `vi` 模式 (bindkey -v) 插件.
- [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 一个修改过的 virtualenv ZSH 插件 [oh-my-zsh](https://ohmyz.sh).
- [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - 来自上游的 virtualenv 插件的一个分支 [oh-my-zsh](https://ohmyz.sh/) . 添加对自定义 virtualenv 提示的支持 [oh-my-zsh](https://ohmyz.sh) 主题.
- [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 受 Adam Brenecki 启发的经理 [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/)，替换 virtualenvwrapper.
- [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - 一个 [oh-my-zsh](https://ohmyz.sh/) 插件 [virtuozzo](https://docs.virtuozzo.com/master/index.html) 裸机虚拟化系统.
- [visit](https://github.com/justinpchang/visit) - 用于更快导航的自定义插件.
- [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - 无缝安装和配置 [Volta](https://volta.sh) NodeJS 工具链管理器.
- [volta](https://github.com/ri7nz/zsh-volta) - 安装和加载 [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
- [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个 [oh-my-zsh](https://ohmyz.sh/) 插件来控制 [VOX](https://vox.rocks/)，一款轻量级的全功能音频播放器，适用于 macOS，可以播放包括 FLAC 和 Ogg Vorbis 在内的多种格式.
- [vsc](https://github.com/davidtong/vsc.plugin.zsh) - 插件 [Visual Studio Code](https://code.visualstudio.com/) 在 macOS 上.
- [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - 简单的插件打开 [Visual Studio Code](https://code.visualstudio.com/) 跨系统更容易一点.
- [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
- [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run `emacs` commands directly from [vterm](https://github.com/vterm/vterm) 外壳会话.
- [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - 跟踪多少 [time](https://wakatime.com/) 你已经在你的终端消费了. 具有每个项目的统计信息.
- [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - 使用 ZSH 中的命令自动时间跟踪 [wakatime](https://wakatime.com/).
- [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色与 [grc](https://github.com/garabik/grc).
- [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”，可以轻松地为当前或以前的命令添加前缀.
- [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) 时间管理系统.
- [wd](https://github.com/mfaerevaag/wd)  - Warp 目录允许您跳转到 ZSH 中的自定义目录，而无需使用 `cd`. 为什么？ 因为当文件夹被频繁访问或路径很长时，`cd` 似乎效率低下.
- [wdnote](https://github.com/Vesdii/zsh-wdnote) - 更改到新目录时打印 `.wdnote` 文件的内容（如果存在）.
- [web-search (sinetoami)](https://github.com/sinetoami/web-search) - 添加命令以直接从 CLI 运行 bing、google、yahoo 和 duckduckgo 搜索.
- [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - 添加别名以使用 Google、Wiki、Bing、YouTube 和其他流行服务进行搜索.
- [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - 使用 `git blame` 突出显示文件中最后更改特定行的位置.
- [window-title](https://github.com/olets/zsh-window-title) - 将信息图块添加到您的终端窗口.
- [windows-title](https://github.com/mdarocha/zsh-windows-title) - 使用当前目录和最后运行的命令动态更新终端窗口标题.
- [wordle](https://github.com/zechris/zwordle) - ZSH 的 Wordle，带有制表符补全.
- [workon](https://github.com/bryanculver/workon.plugin.zsh) - 用于在项目之间跳转的简单实用程序.
- [worktree](https://github.com/jspears/worktree) - 添加包装`git worktree`的函数.
- [wsl2-ssh-pageant](https://github.com/antoinemartin/wsl2-ssh-pageant-oh-my-zsh-plugin)  - 使用来自 WSL 的 Yubikey 存储的 GPG 密钥. 这将说明从 [wsl2-ssh-pageant repo](https://github.com/BlackReloaded/wsl2-ssh-pageant) 作为 ZSH 插件.
- [xdg-basedir](https://github.com/mattmc3/zsh-xdg-basedir) - 支持 [XDG](https://wiki.archlinux.org/index.php/XDG_Base_Directory) 基本目录设置.
- [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - 插件 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) 将您的`~/.zshrc`复制到远程主机并使用 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
- [yadm](https://github.com/juanrgon/yadm-zsh) - 如果有本地显示警告 [yadm](https://thelocehiliosan.github.io/yadm/) 配置更改.
- [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - 如果 `pipenv` 检测到存在一个目录，则自动激活目录的 `pip` 环境.
- [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) ——爱德华·洛佩兹 [Yeoman](http://yeoman.io/) 插件 [oh-my-zsh](https://ohmyz.sh/)，与 yeoman 版本 ≥1.0 兼容（包括选项和命令自动完成）.
- [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH 插件，提醒您使用您定义的那些别名.
- [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - 添加 `yt` 别名以从 YouTube 下载视频.
- [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
- [yup](https://github.com/redxtech/zsh-yup) - 添加帮助函数以升级 `yarn`/`npm` 项目中的所有依赖项.
- [z.lua](https://github.com/skywind3000/z.lua)  - 一个命令行工具，可帮助您通过学习习惯来更快地导航. 一个替代方案 [z.sh](https://github.com/rupa/z) 具有 Windows 和 posix shell 支持和各种改进. 比 fasd 和 autojump 快 10 倍，比 fasd 快 3 倍 [z.sh](https://github.com/rupa/z).
- [zabb](https://github.com/Mellbourn/zabb) - `zabb` 是一个命令，它试图找出可供用户使用的目录的最短记忆缩写 [z](https://github.com/ajeetdsouza/zoxide) 明确地跳转到该目录.
- [zabrze](https://github.com/Ryooooooga/zabrze) - ZSH 缩写扩展插件.
- [zaw](https://github.com/zsh-users/zaw) - ZSH any.el-like 小部件.
- [zbrowse](https://github.com/zdharma-continuum/zbrowse) - 在做shell工作时，经常会出现多次调用`echo $variable`，检查循环结果等情况.使用ZBrowse，你只需要按下`Ctrl-B`，调用ZBrowse – Zshell 变量浏览器.
- [zce](https://github.com/hchbaw/zce.zsh) - Vim 的 EasyMotion / Emacs 的 ZSH ace-jump-mode.
- [zcolors](https://github.com/marlonrichert/zcolors) - 使用你的 `$LS_COLORS` 为 Git 和你的 Zsh 提示、补全和生成一个连贯的主题 [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
- [zconvey](https://github.com/zdharma-continuum/zconvey) - 添加向其他 ZSH 会话发送命令的功能，例如，您可以在所有活动的 ZSH 会话上使用它来“cd $PWD”.
- [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装器 [z](https://github.com/rupa/z) 通过 ZSH 插件安装它.
- [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - 提供使用环境 [zellij](https://github.com/zellij-org/zellij) . 需要 [tmux](https://github.com/tmux/tmux).
- [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - 提供自动启动的环境 [zellij](https://github.com/zellij-org/zellij) 作为您终端的多路复用器.
- [zeno](https://github.com/yuki-yano/zeno.zsh) - 模糊完成和实用插件由 [Deno](https://deno.land/).
- [zenplash](https://github.com/Chivier/zenplash) - 从存储在用户目录中的模板创建文件.
- [zero](https://github.com/arlimus/zero.zsh)  - 零既是插件也是主题. 有关安装详细信息，请参阅 github 页面. 包括 `git` 和 `hg` 状态装饰器.
- [zflai](https://github.com/zdharma-continuum/zflai) - ZSH 的快速日志记录框架.
- [zfzf](https://github.com/b0o/zfzf) - 用于 ZSH 的 fzf 驱动的文件选择器，可让您快速导航目录层次结构.
- [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 让 `compinit` 在所有加载完成后只运行一次 [zgen](https://github.com/tarjoilija/zgen).
- [zhooks](https://github.com/agkozak/zhooks)  - 显示任何 ZSH 钩子数组的内容和任何已定义的钩子函数的代码. 对调试很有用.
- [zi-rbenv](https://github.com/z-shell/zi-rbenv) - 如果您正在使用快速 `rbenv` 加载 [zi](https://github.com/z-shell/zi/).
- [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - 自定义附加功能 [zimfw](https://github.com/zimfw/zimfw)，打包成一个 zimfw 插件.
- [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为 ZSH 主题提供更多信息.
- [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) 在不更改 $PATH 的情况下公开二进制文件的扩展，安装 Ruby gems 和 Node 模块并轻松公开它们的二进制文件，并在更新相关插件或片段时更新 gems 和模块.
- [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - 允许用户为多个 zinit 命令定义激活的 ice.
- [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) 为所有插件和片段生成手册页的扩展
- [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - 使用单个标签安装插件组（[zinit](https://github.com/zdharma-continuum/zinit) 只要）.
- [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) 通过提供的 `dl` 和 `patch` zinit ices 下载文件和应用补丁的扩展.
- [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - 添加自动下载网页上托管 URL 的文件的最新版本的功能.
- [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) 在插件目录中安装 rust 和 cargo 包的扩展.
- [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) 允许在插件或片段中安装和管理其他子模块的扩展.
- [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) 在安装和更新插件或代码片段之后运行测试的扩展程序（例如，通过 make test）——如果它找到其中任何一个.
- [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - 允许安装插件 [zinit](https://github.com/zdharma-continuum/zinit) 无需通过查询 Github API 指定用户名.
- [zinit-console](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) 插件管理器.
- [zinsults](https://github.com/ahmubashshir/zinsults) - 如果命令失败，则打印侮辱.
- [zjump](https://github.com/qoomon/zjump)  - 简化 ZSH 目录导航； 跳转到已经访问过的父文件夹或子文件夹.
- [zlitefetch](https://github.com/ippee/zlitefetch) - 轻量级系统信息插件.
- [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - 使用 `notify-send` 并在需要很长时间（默认值：15 秒）的命令完成时响铃以提醒您.
- [zman](https://github.com/mattmc3/zman) - 利用 [fzf](https://github.com/junegunn/fzf) 快速浏览 Zsh 手册.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - 学习您习惯的“cd”的快速替代方案.
- [zpy](https://github.com/AndydeCleyre/zpy) - 使用 ZSH 前端管理 Python 环境、依赖项和隔离的应用程序安装 [pip-tools](https://github.com/jazzband/pip-tools).
- [zredis](https://github.com/zdharma-continuum/zredis) - 添加 [Redis](https://redis.io/) 数据库支持，带有 `database_key` &lt;-&gt; `shell_variable` 绑定. 支持所有数据类型.
- [zredis-cmd](https://github.com/z-shell/zredis-cmd) - 利用由完成的变量共享 [zredis](https://github.com/zdharma-continuum/zredis) 实现远程命令执行的插件.
- [zservice-py3http](https://github.com/z-shell/zservice-py3http) - 使用标准库中的 Python 3 的 http 服务器为给定目录提供服务.
- [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - 自动化 ZSH + [oh-my-zsh](https://ohmyz.sh/) 安装到开发容器中. 适用于 Alpine、Ubuntu、Debian、CentOS 或 Amazon Linux.
- [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供一个自动羞辱用户忘记他们不在 `vim` 中的功能.
- [zsh-select](https://github.com/z-shell/zsh-select)  - 显示选择列表. 它类似于`selecta`，但使用curses库来做显示，和比较时 [fzf](https://github.com/junegunn/fzf)，主要区别是近似匹配而不是模糊匹配.
- [zsh-z (agkozak)](https://github.com/agkozak/zsh-z)  - 快速跳转到您“经常”访问的目录.  `z.sh` 的原生 ZSH 端口 - 没有 `awk`、`sed`、`sort` 或 `date`.
- [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - 安装和加载 [z](https://github.com/rupa/z.git).
- [zshange_directory_recent](https://github.com/Kjeldgaard/zshange_directory_recent)  - 切换到最近的目录. 需要 [fzf](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/junegunn/fzf).
- [zshmarks](https://github.com/jocelynmallon/zshmarks) - Bashmarks 的一个端口（由 Todd Werth 编写），一个简单的命令行书签插件，用于 [oh-my-zsh](https://ohmyz.sh).
- [zshrc](https://github.com/freak2geek/zshrc) - 从您的项目范围加载本地 `.zshrc` 文件.
- [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 用于在 Arch Linux 上拍摄 ZFS 升级前/升级后快照的插件.
- [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - 添加命令以将当前 ZSH 状态转储到文件中，以便以后通过获取快照文件进行恢复.
- [ztouch](https://github.com/mjrafferty/ztouch) - 为最近的历史命令、目录堆栈、模式之间的循环和用户可映射命令添加触摸栏控件到 macOS 上的触摸栏.
- [ztrace](https://github.com/zdharma-continuum/ztrace) - 捕获命令的输出，允许重用该输出，将其与历史内容粘合.
- [zui](https://github.com/zdharma-continuum/zui) - ZSH 用户界面库 – 使用 ZSH 进行类似 CGI+DHTML 的快速 TUI 应用程序开发.）

## Completions

这些插件添加选项卡完成而不添加额外的功能或别名.

- [1password-op](https://github.com/unixorn/1password-op.plugin.zsh) - 加载 1Password 的自动补全 [op](https://developer.1password.com/docs/cli/get-started/) 命令行工具.
- [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展 ZSH 的 \_urls 补全，允许它从 html 页面补全 url.
- [aliyun](https://github.com/thuandt/zsh-aliyun) - 添加完成 [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
- [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - 完成 [viasite-ansible/ansible-server](https://github.com/viasite-ansible/ansible-server).
- [antibody-completion](https://github.com/sinetoami/antibody-completion) - 这个插件提供完成 [Antibody](https://github.com/getantibody/antibody) 插件管理器.
- [appspec](https://github.com/perlpunk/App-AppSpec-p5) - 根据 YAML 规范为 Bash 和 ZSH 生成完成
- [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
- [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - 添加对 `awscli` 的完成支持以管理 AWS 配置文件/区域并在提示中显示它们.
- [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为 `aws_manager` CLI 添加完成.
- [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - 当没有本地 ZSH 可用时，支持命令的 `bash` 完成.
- [batect](https://github.com/batect/batect-zsh-completion/) - 添加选项卡完成 [batect](https://batect.dev/) 构建系统.
- [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - 为 berkshelf 添加选项卡完成.
- [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好的 `npm` 选项卡完成.
- [bio](https://github.com/yamaton/zsh-completions-bio/) - 完成生物信息学工具.
- [bosh (krujos)](https://github.com/krujos/bosh-zsh-autocompletion) - 添加 [BOSH](https://github.com/cloudfoundry/bosh) 自动完成.
- [bosh (thomasmitchell)](https://github.com/thomasmitchell/bosh-complete) - [BOSH(https://github.com/cloudfoundry/bosh)] 的选项卡完成.
- [brew-completions](https://github.com/z-shell/brew-completions) - 带来 [Homebrew Shell Completion](https://docs.brew.sh/Shell-Completion) 在 ZSH &amp; 的控制下 [ZI](https://github.com/z-shell/zi/).
- [brew-services](https://github.com/vasyharan/zsh-brew-services) - 完成插件 [homebrew](https://github.com/unixorn/awesome-zsh-plugins/blob/master/brew.sh) 服务.
- [buidler](https://github.com/gonzalobellino/buidler-zsh) - 为 NomicLabs Buidler 工具添加完成和有用的别名 [buidler.dev](https://buidler.dev).
- [bw](https://github.com/CupricReki/zsh-bw-completion) - 添加完成 [Bitwarden](https://bitwarden.com/).
- [cabal (ehamberg)](https://github.com/ehamberg/zsh-cabal-completion) - 为 cabal 添加制表符补全.
- [cabal (d12frosted)](https://github.com/d12frosted/cabal.plugin.zsh) - 为 cabal 添加自动完成功能.
- [carapace-bin](https://github.com/rsteube/carapace-bin) - 多壳多命令参数完成器.
- [carapace](https://github.com/rsteube/carapace)  - Bash、Elvish、Fish、Oil、Powershell、Xonsh 和 ZSH 的完成生成器. 注意 - 这不会根据需要自动生成完成，您必须显式运行它才能为命令生成完成.
- [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - 原始 oh-my-zsh 货物完成的所有功能，通过 `cargo add` 中的 `cargo search` 额外支持远程 crate.
- [carthage](https://github.com/squarefrog/zsh-carthage) - 提供补全和别名以供使用 [Carthage](https://github.com/Carthage/Carthage).
- [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
- [click-completion](https://github.com/click-contrib/click-completion) - 添加自动完成支持 [Click](http://click.pocoo.org/)，包括在选项卡完成期间显示选项和命令帮助.
- [cod](https://github.com/dim-an/cod) - `bash`/`fish`/`zsh` 的完成恶魔，当它看到你使用 `--help` 运行某些东西时，它会即时创建完成函数.
- [codeception](https://github.com/shengyou/codeception-zsh-plugin) - 为 Codeception 测试框架添加命令完成.
- [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - 选项卡完成 [comonicon](https://github.com/Roger-luo/Comonicon.jl).
- [completions (clarketm)](https://github.com/clarketm/zsh-completions) - 这包括 zsh-users[completions](https://github.com/zsh-users/zsh-completions), zchee  [completions](https://github.com/zchee/zsh-completions), 尼尔森霍尔格 [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) 以及其他各种自定义完成.
- [completions (zchee)](https://github.com/zchee/zsh-completions) - 另一个选项卡完成集合.
- [completions (zsh-users)](https://github.com/zsh-users/zsh-completions) - ZSH 的额外完成集合.
- [conda](https://github.com/esc/conda-zsh-completion) - conda 的 ZSH 选项卡完成.
- [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion)  - 添加`cpan安装字<tab> ` 和 `cpanm 安装<tab> ` 完成远程 CPAN 包名称.
- [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 选项卡完成 [ctop](https://github.com/bcicen/ctop).
- [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - 完成匕首.
- [dbic](https://github.com/lejeunerenard/dbic-migration-env) - 自动为 DBIx::Class::Migration 的脚本和 Dancer 设置环境变量.
- [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - 直接从 **Docker for Mac** 加载 `docker` ZSH 选项卡完成.
- [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - 为 `docker` 添加选项卡补全.
- [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - 为 `docker` 和 `docker-compose` 添加选项卡补全.
- [docker-enter-completion](https://github.com/primait/docker-enter-completion) - 命令完成 [docker-enter](https://github.com/jpetazzo/nsenter).
- [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - dotnet 选项卡完成.
- [dropbox](https://github.com/zpm-zsh/dropbox) - Zsh 的 Dropbox 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
- [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - ZSH 的 Drush 自动完成功能很棒.
- [duell](https://github.com/jcxavier/oh-my-zsh-duell) - 一个 ZSH 插件 [duell](https://github.com/gameduell/duell).
- [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - `efibootmgr` 的选项卡完成.
- [elm](https://github.com/kraklin/elm.plugin.zsh) - 标签完成 [elm](https://elm-lang.org/).
- [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - 添加 etcdctl 选项卡补全.
- [expressvpn](https://github.com/tk7r/zsh-expressvpn) - 为 [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) 客户.
- [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - 定义一个名为 extract 的函数，用于提取您传递给它的存档文件，并支持多种存档文件类型.
- [extract (thetic)](https://github.com/thetic/extract) - oh-my-zsh 提取插件的分支.
- [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - 为所有人添加自动完成选项 [Concourse CLI](https://concourse-ci.org/fly.html) 命令.
- [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - 导航和预览所有 Google Cloud SDK `gcloud` CLI 命令的模糊补全
- [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - 使用 GNU Readline 为 ZSH、bash 和应用程序添加选项卡完成.
- [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - 模糊完成 [fzf](https://github.com/junegunn/fzf) 和 [ZSH](https://www.zsh.org/) 可以由默认为 `**` 的触发序列触发.
- [fzshell](https://github.com/mnowotnik/fzshell) - 从用户预定义的源中获取模糊完成.
- [gardenctl](https://github.com/holgerkoser/gardenctl) - 选项卡完成 [Gardener](https://github.com/gardener/gardenctl-v2) 命令行界面，以及一些常用 gardenctl 命令的别名
- [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
- [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - 为上游缺少补全脚本的各种 Gentoo 工具提供 ZSH 补全支持.
- [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数 git-annex 命令的选项卡完成.
- [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH 完成支持 [git-flow](http://github.com/nvie/gitflow).
- [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf)  - ZSH 插件，包装了 `git` 操作以实现简单性和生产力. 它还包含完成并结合了对 [fzf](https://github.com/junegunn/fzf).
- [github-cli](https://github.com/sudosubin/zsh-github-cli) - github cli 的选项卡完成.
- [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - gitlab-ci-multi-runner 的 ZSH 完成.
- [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - 对 gradle 的 Bash 和 ZSH 完成支持.
- [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - 对 gradle 的 ZSH 完成支持.
- [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 插件 - 添加主题、自动补全.
- [gstreamer](https://github.com/CraigCarey/gstreamer-tab) - 标签完成 [GStreamer](https://gstreamer.freedesktop.org/).
- [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - 在 Z-Shell (ZSH) 中自动完成 gulp.js 任务.
- [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp 的自动补全.
- [hashlink](https://github.com/tong/zsh.plugin.hashlink) - 完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
- [haskell](https://github.com/coot/zsh-haskell) - 为 `cabal`、`ghc` 和 `ghc-pkgs` 命令添加补全.
- [haxelib](https://github.com/tong/zsh.plugin.haxelib) - 完成 haxelib.
- [helmfile](https://github.com/Downager/zsh-helmfile) - 为 `helm` 添加自动完成功能.
- [inspr](https://github.com/ptcar2009/insprzsh) - 完成 [inspr](https://github.com/inspr/inspr)
- [ipfs](https://github.com/hellounicorn/zsh-ipfs) - 完成 [Interplanetary File System](https://ipfs.io).
- [joe](https://github.com/corvofeng/joe-completion) - 添加完成 [joe](https://github.com/karan/joe) .gitignore 编辑器.
- [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - jtool 的 ZSH 完成.
- [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成 [jumpstorm](https://github.com/netresearch/jumpstorm)
- [jx](https://github.com/haysclark/zsh-jx) - 为 Jenkins-X cli 添加选项卡补全.
- [kafka](https://github.com/Dabz/kafka-zsh-completions) - 完成 Apache [kafka](https://kafka.apache.org).
- [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - 完成 [keybase](https://keybase.io/docs/command_line).
- [kitty](https://github.com/redxtech/zsh-kitty) - 完成 [kitty](https://sw.kovidgoyal.net/kitty/) 终端模拟器.
- [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - 添加选项卡完成 [Kompose](http://kompose.io/).
- [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - 添加选项卡完成 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
- [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - 快速而强大 [fzf](https://github.com/junegunn/fzf)- 为 `kubectl` 提供动力的自动完成功能.
- [kubectl-plugin](https://github.com/MartinSimango/kubectl-plugin_completion) - 生成 `kubectl` 完成脚本以扩展 `kubectl` 自动完成功能以适应插件子命令.
- [lazycomplete](https://github.com/rsteube/lazycomplete) - 延迟加载 shell 完成脚本.
- [lets](https://github.com/lets-cli/lets-zsh-plugin) - 添加自动完成 [lets](https://github.com/lets-cli/lets) cli 任务运行器.
- [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - 添加一些有用的别名 [ls-go](https://github.com/acarl005/ls-go).
- [mac](https://github.com/scriptingosx/mac-zsh-completions) - macOS 特定命令和第三方工具的完成文件.
- [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - Perl 模块 `MooseX::App` 的完成生成器.
- [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 个 zsh compsys 完成！
- [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Metasploit 的选项卡完成.
- [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx) ; 用于开发 Graal 项目的命令行工具. 它旨在改进通常的工作流程`build unittest benchmark ...`简化发现并提供方便的别名.
- [myincr](https://github.com/gaojunbin/zsh-myincr/) - 使用自动建议和增加加速粘贴.
- [newman](https://github.com/selop/newman-autocomplete) - 提供自动完成 [Newman CLI](https://github.com/postmanlabs/newman).
- [nix](https://github.com/spwhitt/nix-zsh-completions) - 完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)， 和 [NixOps](https://nixos.org/nixops/).
- [node-ace](https://github.com/romch007/node-ace-zsh-completion) - 完成“节点王牌”.
- [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为 nova 提供自动完成功能.
- [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持.
- [npm-scripts-autocomplete](https://github.com/grigorii-zander/zsh-npm-scripts-autocomplete)  - 显示来自当前目录的 `package.json` 中的脚本的自动完成建议. 适用于 `npm` 和 `yarn`.
- [nx](https://github.com/jscutlery/nx-completion) - 完成 [nx](https://nx.dev) . 需要 [`jq`](https://stedolan.github.io/jq/).
- [okta](https://github.com/sirhc/okta.plugin.zsh) - 提供命令行补全 [`aws-okta`](https://github.com/segmentio/aws-okta) 和 [okta-awscli](https://github.com/jmhale/okta-awscli) comm和s.
- [op](https://github.com/sirhc/op.plugin.zsh) - 选项卡完成 [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) 命令行工具.
- [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) - 某些特定于 macOS 的命令（如“launchctl”）的选项卡完成.
- [packer](https://github.com/wakeful/zsh-packer) - 添加选项卡完成 [packer](https://packer.io).
- [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc 补全插件.
- [parallels](https://github.com/benclark/parallels-zsh-plugin) - 为 Parallels 桌面添加补全.
- [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购，轻松获得 [pass](https://www.passwordstore.org/) ZSH 的命令完成.
- [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - pip 的自动完成插件.
- [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - 为最常见的 pipenv 命令启用别名.
- [pipenv (gangleri)](https://github.com/gangleri/pipenv) - `pipenv` 的完成.
- [pipx](https://github.com/omBratteng/zsh-plugin-pipx) - 选项卡完成 [pipx](https://github.com/pypa/pipx).
- [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - 为 Pivotal 的添加完成 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
- [pmy](https://github.com/relastle/pmy) - 通用的上下文感知 ZSH 完成引擎，由 [fzf](https://github.com/junegunn/fzf).
- [quickjump](https://github.com/fikovnik/zsh-quickjump) - 添加选项卡完成支持 [skim](https://github.com/lotabout/skim) 对于最近使用的文件和目录 [fasd](https://github.com/whjvenyl/fasd).
- [racket completion](https://github.com/racket/shell-completion) - 完成 [Racket](http://racket-lang.org).
- [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - 为 rakefile 目标添加快速选项卡完成.
- [rancher](https://github.com/go/rancher-zsh-completion) - 为 Rancher CLI 添加完成.
- [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - 添加完成 [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
- [rustup](https://github.com/pkulev/zsh-rustup-completion) - Rustup 的选项卡完成.
- [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - 添加选项卡完成 [s3cmd](https://s3tools.org/s3cmd).
- [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  - Salesforce CLI 的 ZSH 命令完成. 需要 [jq](https://stedolan.github.io/jq/).
- [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - 添加完成 [saml2aws](https://github.com/Versent/saml2aws).
- [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - sfdx 的自动完成插件.
- [speedtest](https://github.com/Yash-Singh1/zsh-plugin-speedtest) - 速度测试的选项卡完成 [cli](https://www.speedtest.net/insights/blog/introducing-speedtest-cli/).
- [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动完成 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
- [ssh](https://github.com/sunlei/zsh-ssh) - 更好的主机完成`ssh`.
- [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - 管理`ssh-agent`.
- [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动 `ssh-agent` 以设置和加载您想要的 `ssh` 连接的任何凭据.
- [ssh](https://github.com/zpm-zsh/ssh) - 为 `ssh` 添加主机补全.
- [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加完成冲浪.
- [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Symfony 3 和 4 命令的自动完成.
- [terragrunt](https://github.com/jkavan/terragrunt-oh-my-zsh-plugin) - 标签完成 [Terragrunt](https://github.com/gruntwork-io/terragrunt).
- [test-kitchen](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - 添加完成 [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
- [tinygo](https://github.com/sago35/tinygo-autocmpl) - 添加选项卡完成 [tinygo](https://tinygo.org/).
- [tmux pane words](https://gist.github.com/blueyed/6856354) - 键绑定来完成您的单词 [tmux](https://tmux.github.io) 有.
- [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成 [tugboat](https://github.com/petems/tugboat) 命令.
- [umake](https://github.com/zlsun/umake) - Ubuntu umake 的选项卡完成.
- [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) 命令.
- [vorpal](https://github.com/VorpalBlade/vorpal-zsh-completions) - 为上游似乎已死的一些项目添加完成，包括 [duperemove](https://github.com/markfasheh/duperemove), [optimus-manager](https://github.com/Askannz/optimus-manager) 和 [pacutils](https://github.com/和rewgregory/pacutils).
- [web-open](https://github.com/AndrewHaluza/zsh-web-open)  - 添加别名以打开网页. 仅适用于 Ubuntu 20.
- [yabai](https://github.com/Amar1729/yabai-zsh-completions) - 为 macOS 添加补全 [yabai](https://github.com/koekeishiya/yabai/) 平铺窗口管理器.
- [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 为 `yarn add`、`yarn remove`、`yarn upgrade`、`yarn why` 和 `yarn run` 添加自动完成功能.
- [zargparse](https://github.com/ctil/zargparse) - 向它传递一个使用 `argparse` 的脚本，它会将 ZSH 完成写入您的当前目录.

## Themes

如果你正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom)，使用 `zgenom load githubuser/reponame` 将它们添加到您的 `init.zsh` 中.

- [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - 带有用户名、主机名、完整路径、返回状态和“git”装饰的多行提示.
- [021011](https://github.com/guesswhozzz/021011.zsh-theme)  - 极简主义者. 包括 VS Code 的单个 `git` 标记.
- [0i0](https://github.com/0i0/0i0.zsh-theme) - 针对深色终端窗口进行了优化，使用 nerdfont `git` 状态装饰.
- [14degree](https://github.com/saims0n/14degree-zsh-theme/) - 包括 `git`、`virtualenv` 和 `rvm` 状态装饰.
- [a](https://github.com/chammanganti/a-zsh-theme) - 带有当前目录和 `git` 状态装饰的简单主题.
- [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - 基于索林主题.
- [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme)  - 显示当前目录路径的缩写版本，显示 Python virtualenv、Rust 版本、`git` 状态和最后一个命令的退出代码. 默认情况下适用于深色背景，但可以轻松自定义颜色.
- [absolute](https://github.com/NelsonBrandao/absolute) - 非常干净的主题，带有 `git` 状态、`node` 版本和最后一个命令的退出代码的装饰器.
- [acenoster](https://github.com/HiDe-Techno-Tips/Acenoster-ZSH-Theme)  - 具有非常详细的 `git` 和 `mercurial` 支持的多用途主题. 还包括 AWS 配置文件名称、虚拟环境名称（如果有）、后台任务数量、当前目录和上一个命令的退出代码（如果非零）的装饰器.
- [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括 `git` 状态的装饰器、AWS 配置文件的名称、Azure 服务主体的名称、kubernetes 上下文、terraform 工作区、最后一个命令退出状态和当前工作目录.
- [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS 主题，需要与电力线兼容的字体.
- [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - 修改版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) 动态路径缩短.
- [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - 修改版 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 中的主题.
- [aftermath](https://github.com/schanur/aftermath) - 在您在 shell 中运行的每个命令后获得一个漂亮的摘要行.
- [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) 主题包含在 [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) . 显示有关 `git` 状态的详细信息.
- [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  - 使用三种异步方法来保持 ZSH 提示响应，同时显示 `git` 状态和 SSH 连接、退出代码和 `vi` 模式的指示符，以及缩写的 `PROMPT_DIRTIM` 样式路径. 非常可定制. 即使在 Cygwin 和 MSYS2 上也是异步的.
- [agnoster (fcamblor)](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - 日晒 [Agnoster](https://gist.github.com/agnoster/3712874) 带有 `git` 状态信息的变体. 需要 unicode 字体，最好使用 [solarized](https://github.com/altercation/solarized) 终端.
- [agnoster (fseguin)](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
- [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - Gentoo 风格的版本 [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) 其中包括 user@hostname 和 `git` 状态装饰. 使用 unicode 字体效果更好.
- [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - 优化 [solarized](https://ethanschoonover.com/solarized/) 配色方案、`git` 或其他 VCS 工具以及兼容 unicode 的字体. 包括上次命令运行状态、user@hostname、`git` 状态、工作目录、是否以 root 身份运行、后台作业是否正在运行以及其他信息的修饰符.
- [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
- [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体优化用于 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端配色方案. 包括 `git` 状态.
- [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
- [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` 和 `mercurial` status, current time 和 time the last comm和 took decorations in the prompt.
- [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 添加了时间戳和换行符的变体.
- [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
- [agnoster](https://gist.github.com/agnoster/3712874)  - 针对 solarized 终端配色方案进行了优化，显示 `git` 装饰、用户@主机、工作目录、上一个命令的退出状态以及您是否以 root 权限运行. 需要与电力线兼容的字体.
- [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874), 显示电池寿命、日期和时间、`git` 状态、当前目录以及用户和主机信息.
- [akzsh](https://github.com/awkimball/akzsh) - 最适合深色终端主题，包括 `git` 装饰.
- [al-magic](https://github.com/Alustrat/al-magic/) - oh-my-zsh 的克隆 [af-magic](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme) 在提示右侧添加时间的主题.
- [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - 带有“git”状态装饰的极简主义主题.
- [ale](https://github.com/alepimentel/ale-zsh)  - 基于fino主题. 包括 `git`、`virtualenv` 和 `node` 状态装饰.
- [alien-minimal](https://github.com/eendroroy/alien-minimal) - 显示 `git` 状态的极简主义 ZSH 主题.
- [alien](https://github.com/eendroroy/alien)  - 电力线风格的 ZSH 主题，显示 `git` 装饰和最后一个命令的退出代码. 比许多其他提示更快，因为它在后台进程中异步确定 `git` 装饰.
- [almel](https://github.com/Ryooooooga/almel) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) , 用 Rust 编写. 包括 `git` 状态、user@host、最后一个命令退出状态和工作目录装饰
- [alpharized](https://github.com/NicoSantangelo/Alpharized) - 优化工作 [solarized](http://ethanschoonover.com/solarized) 黑暗的终端. 这是修改版 [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
- [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 优雅舒适的阅读主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874).
- [amplify](https://github.com/clintfoster/ohmyzsh-theme-amplify) - 极简主义，包括 AWS Amplify 环境和 `git` 状态装饰.- [andy](https://github.com/andymcguinness/andys-theme) - 修改 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 具有更好的 `git` 支持的主题.
- [angry fly](https://github.com/russjohnson/angry-fly-zsh) - 在右侧提示中显示 `git` 信息.
- [antoinechab](https://github.com/antoinechab/antoinechab-theme) - 包括 `git` 状态、用户名、时间和当前目录装饰.
- [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - 显示 `git` 分支和状态装饰、virtualenv、退出状态、作业计数和 vi 模式指示器.
- [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - 显示 `git` 装饰、用户、主机、是否为 root、活动的 Python 虚拟环境、当前的 Ruby 解释器、最后一个命令的视觉和数字状态、电源管理状态以及时间和日期.
- [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)  - 没有视觉噪音的简约主题. 仅显示必要的信息：当前用户、主机名、工作目录、`git` 分支（如果存在）. 深色和白色端子看起来都很棒.
- [aplos](https://github.com/sunquan1991/aplos) - 带有工作目录、`git` 本地信息、`git` 远程信息、时间和退出代码的最小 ZSH 提示.
- [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - 一个高度可定制、兼容和高性能的 ZSH 主题，它使用模块来启用功能.
- [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
- [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - 带有“git”状态装饰的极简主义主题.
- [arael](https://github.com/aknackd/zsh-themes) - 叉子 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
- [archcraft](https://github.com/mrx04programmer/ZshTheme-ArchCraft)  - 绿色主题，针对深色背景进行了优化. 包括 `git` 状态装饰.
- [archie](https://github.com/dcavalcante/archie)  - Arch Linux 启发了 ZSH 主题. 基于 [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) 主题.
- [arity](https://github.com/hybras/Arity-Zsh-Theme) - A simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
- [aronhoyer](https://github.com/aronhoyer/zsh-theme) - 带有右侧“git”状态装饰的极简主义主题.
- [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有 `git` 装饰的最小 ZSH 主题.
- [arrow](https://github.com/milon/arrow-zsh-theme) - 最小主题，包括 `git` 状态装饰.
- [asciigit](https://github.com/cemsbr/asciigit) - 为不想使用带有额外字形的字体的 `git` 用户提供的纯 ASCII 主题.
- [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
- [astral](https://github.com/xwmx/astral)  - 带有禅宗模式的深色背景主题. 适用于 zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 插入.
- [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于`ys`和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
- [async](https://github.com/mje-nz/zsh-themes) - 显示当前目录、`git` 状态、最后一个命令的返回值（如果有错误代码）、后台作业的数量、长时间运行的命令的执行时间、当前的 python virtualenv.
- [aterminal](https://github.com/guiferpa/aterminal) - 在提示符中显示 Nodejs、NPM、Docker、Go、Python、Elixir 和 Ruby 信息.
- [aub](https://github.com/FraSharp/aub) - 包括 `git` 和 `hg` 状态以及 `host` 中的 `username` 的装饰.
- [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题.
- [avit-d2k](https://github.com/fdaciuk/avit-da2k) - 基于 oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题，变化不大.
- [avit-mod](https://github.com/zlsun/avit-mod) - 修改版 oh-my-zsh&#39;s [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题.
- [banana](https://github.com/sorcererxw/banana-zsh-theme) - 包括 `git` 状态装饰和当前目录.
- [bandit](https://github.com/Holger-Will/zsh_bandit) - 另一个电力线变体.
- [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义设置 [p10k](https://github.com/romkatv/powerlevel10k).
- [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名、主机、密码、`git` 状态装饰和 3 小时饮水提醒.
- [barion](https://github.com/SEbbaDK/barion)  - 快速编译的提示，带有紧凑的 `git` 状态概览. 让人联想到电力线. 需要 [Crystal](https://crystal-lang.org/) 建造.
- [bash](https://github.com/starseekist/bash-zsh-theme) - 看起来像默认的 `bash` 提示.
- [bashi](https://github.com/eli-oat/bashi) - 针对 Ahmet Sülek 的优化 [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) 主题和 Pasquale D&#39;Silva  [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
- [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - 修改版 [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
- [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于深色终端背景.
- [bearings](https://github.com/liamg/bearings)  - 一个快速、干净、超级可定制的 shell 提示符. 包括当前目录的装饰器、`git` 状态、最后一个命令的退出代码、最后一个命令的持续时间、后台作业和用户名.
- [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - 灵感来自 [Agnoster](https://gist.github.com/agnoster/3712874)，这个多行提示包括 `git` 状态信息、后台作业计数、工作目录、用户和主机名、Python virtualenv（如果存在）、最后一个命令的彩色返回值和 root/用户 sigil.
- [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
- [bender](https://github.com/specious/bender) - 带有 git 集成的精美两行提示.
- [bernkastel](https://github.com/JamesLaverack/bernkastel) - 基于 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) . 包括 kubernetes 上下文、当前目录、最后一个命令退出状态和 `git` 状态的装饰.
- [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有 unicode 符号的变体.
- [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), 包括根状态和 `git` 状态装饰.
- [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
- [biratime](https://github.com/vemonet/biratime) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 主题，但在提示中显示日期而不是用户名.
- [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) . 包括 `git`、`rvm` 和 `virtualenv` 状态装饰.
- [bklyn](https://github.com/gporrata/bklyn-zsh) - 变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) 应用了自定义.
- [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - 包括帐户信息、root 用户、使用 ssh、目录注册、写入权限和 vcs 信息装饰.
- [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个 `git`-aware 主题.
- [blazux](https://github.com/blazux/omz-theme) - 包括 `git` 状态装饰和最后一个命令退出状态的笑脸/悲伤脸指示器.
- [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - 为 oh-my-zsh 添加了 mercurial 支持 [blink](https://github.com/max13fr/blinks.zsh-theme) 主题.
- [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
- [bliss](https://github.com/joshjon/bliss-zsh)  - 一个精致的主题，在不压倒您的工作空间的情况下注入色彩. 设计用于与 [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案和 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) . 包括 `git` 状态装饰.
- [blokkzh](https://github.com/KorvinSilver/blokkzh) - 基于 oh-my-zsh 的内置主题 [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 主题. 需要支持 unicode 的字体.
- [blox](https://github.com/yardnsm/blox-zsh-theme)  - 一个最小且快速的 ZSH 主题，向您展示您的需求. 它由块组成：每个块都显示在一对\[方括号\]内，您可以通过简单地创建一个函数来添加块.
- [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小的主题，显示 `git` 信息.
- [bluelines](https://github.com/apbarrero/bluelines) - 清晰的蓝色主题.
- [bluo](https://github.com/varunpbardwaj/bluo) - 五颜六色的提示片段让人想起 [bullet-train](https://github.com/caiogondim/bullet-train.zsh) 或者 [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status dec或者ations.
- [bogo](https://github.com/cubasepp/zsh-bogo-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) . 包括 `git` 和 ruby​​ 版本的装饰.
- [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - 多行主题，最适合深色背景.
- [born-in-the-purple](https://github.com/LeonardMH/born-in-the-purple)  - 带有紫色主题的简单主题. 灵感来自 [Pure](https://github.com/sindresorhus/pure).
- [boxy](https://github.com/evil-tim/boxy-zsh-theme)  - 适用于日晒终端颜色. 包括 `username@hostname`、当前目录、`git` 状态、最后一个命令的返回码和最后一个命令运行的时间的装饰器.
- [bref](https://github.com/mpostaire/bref-zsh-prompt)  - 一个简单的提示. 它包括异步显示“git”状态的装饰器，如果“ssh”会话是远程的，则通知，电池电量和后台作业的数量.
- [brisa](https://github.com/brisa-dev/oh-my-zsh-brisa-theme) - 基于多行主题 [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme) . 包括用户名、主机、当前目录和 `git` 状态的装饰.
- [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
- [brs](https://github.com/evenhold/brs-zsh-theme) - 使用 `audtool` 在提示中显示当前歌曲.
- [bruh](https://github.com/haze/bruh) - 包括 `git` 状态装饰.
- [brunty](https://github.com/Brunty/omz-brunty) - 包括 `git` 状态装饰.
- [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - 灵感来自 [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
- [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh)  - BTTF 颜色主题. 包括 `git` 状态装饰.
- [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
- [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 最适合搭配 [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
- [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - 基于 [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) . 生根时变色.
- [bullet-train](https://github.com/caiogondim/bullet-train.zsh)  - 灵感来自 Powerline Vim 插件. 它旨在简化，仅在相关时显示信息.
- [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH 主题，修改为只显示时间和目录.
- [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - 简单、干净、漂亮的主题.
- [bureau-env](https://github.com/angus-lherrou/bureau-env) - 修改 Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) 将 Python 虚拟环境标签添加到 `git` 块左侧的主题.
- [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme) . 包括 `git` 装饰.
- [bureau](https://github.com/isqua/bureau)  - 清晰且内容丰富的两行提示. 包括为大型存储库优化的 `git` 状态.
- [buster](https://github.com/grantbuster/buster_zsh_theme)  - 与 WSL2 配合得很好. 基于 oh-my-zsh 的 Fox 和 Jonathan 主题.
- [cactus](https://github.com/welksonramos/cactus) - 带有“git”状态装饰的极简主义主题.
- [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - 糖果主题的轻量版.
- [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - 在提示中显示活动的 Python 版本和 `git` 装饰.
- [celestialorb](https://github.com/celestialorb/zsh-theme)  - 受@celestialorb 启发的电力线主题. 包括 `git` 状态装饰、Kubernetes 集群信息（如果有）、当前 AWS 配置文件和区域以及活动的 virtualenv.
- [cf-ps1](https://github.com/mdan16/cf-ps1) - 显示当前的基础和组织和空间 [Cloud Foundry](https://www.cloudfoundry.org/) 在您的提示中.
- [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - 精益和简单的主题.
- [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  - 基于索林. 显示 Java、Scala、Go、Node、Python 和 Ruby 的当前活动版本.
- [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  - Oh-My-Zsh 的一个小巧而美丽的主题，没有任何多余的东西. 包括 `git` 状态装饰.
- [charged](https://github.com/robwierzbowski/charged-zsh-theme) - 优化的 ZSH 提示 [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
- [chello](https://github.com/Abdalla981/chello)  - 适用于深色背景. 取决于 [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) 和 [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
- [chi](https://github.com/akinjide/chi) - 针对 macOS 上的 iTerm 2 用户优化的 ZSH 主题.
- [chill](https://github.com/JKerboeuf/chill.zsh-theme) - 具有当前工作目录、最后一个命令退出状态和 `git` 状态的装饰.
- [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme)  - 包含 `git` 装饰的极简主义主题. 需要与电力线兼容的字体和 [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) 插入.
- [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括 `git` 装饰. 需要与电力线兼容的终端字体.
- [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳、大换行符、git 分支和状态.
- [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单性和可扩展性而设计.
- [classyTouchName](https://github.com/dylanroman03/classyTouchName) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) . 在深色背景下效果更好. 包括 `git` 状态装饰.
- [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - 带有 `git` 支持的最小、干净的主题.
- [clean (akz92)](https://github.com/akz92/clean) - 极简主义 ZSH 主题.
- [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - 极简主义的变体 [pure](https://github.com/sindresorhus/pure) . 清净不净，净不净.
- [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - 上游的分叉 [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) 添加了主机信息.
- [cleansh](https://github.com/diegoos/cleansh)  - 极简主义，包括 `git`、Ruby、node 和 Python 版本状态装饰. 适用于标准字体.
- [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
- [clipper](https://github.com/Robert-96/clipper)  - 带有 `git` 支持的极简主义 ZSH 主题. 它包括 pwd 的装饰，最后一个命令退出状态代码和 `git` 状态和分支.
- [cloudy](https://github.com/Huvik/Cloudy) - 最小的多云 ZSH 主题.
- [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
- [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - `cmder` 的配置文件，配置为使用 ZSH 和修改后的地震模式工作 [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
- [cmder](https://github.com/potasiyam/cmder-zsh-theme)  - 一个与 Cmder 主题相匹配的 ZSH 主题，Cmder 是一个流行的 windows 终端模拟器. 包括 `node` 和 `git` 状态装饰.
- [cn](https://github.com/shinqcn/cn-zsh/) - 包括 `username`、`directory` 和 `git` 状态装饰.
- [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos 的 ZSH 和 iTerm 2 的 Cobalt 2 主题.
- [cobalt2git](https://github.com/alexeimun/cobalt2git) - 带有 `git` 扩展的 Cobalt 2 主题.
- [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示 `git` 信息的装饰器，您是否通过 `ssh` 登录，以及最后一个命令的返回码.
- [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi), 在你的提示中包含一个猴子和 `git` 信息.
- [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - 基于 [agnoster](https://gist.github.com/3712874), 右侧提示 vi 模式，以电力线外观显示 `--INSERT--` 和 `--NORMAL--`.
- [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme)  - 为阅读舒适度而设计的蓝灰色主题. 包括 `git` 装饰.
- [collon](https://github.com/lambdalisue/collon.zsh)  - 带有“git”状态装饰、cwd、时间、主机、最后一个命令的退出状态的轻量级主题. 不需要特殊字体.
- [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许按主机提示着色，显示 `rvm`、`virtualenv` 和 `git` 信息.
- [common](https://github.com/jackharrisonsherlock/common) - 一个简单、干净和最小的提示，显示当前工作目录、主机名、AWS 保管库角色、后台作业、当前 SHA、最后一个命令的退出代码以及 `git` 分支和状态.
- [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题.
- [cordial](https://github.com/stevelacy/cordial-zsh-theme) - 干净有效的 ZSH 主题，支持 git 和 npm.
- [cr](https://github.com/cruzrovira/cr-zsh-theme) - 包括目录、时间、主机名、最后一个命令退出状态和 `git` 状态装饰.
- [cramin](https://github.com/FelipeCRamos/craminzsh) - 支持 github 插件的最小界面，基于 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
- [cryo-long](https://github.com/cryocaustik/cryo-long-zsh-theme) - 变体 [cryo](https://github.com/cryocaustik/cryo-zsh-theme/) 为主机名和当前目录添加了装饰器.
- [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - 添加日期和时间的原始 oh-my-zsh 主题的独立克隆.
- [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - 最适合轻终端背景，包括 `git` 和 `vi`-mode 状态装饰.
- [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 Powerline Vim 插件的带有可爱表情符号的 macOS oh-my-zsh shell 主题.
- [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - 在深色背景下效果很好，有 `git` 状态装饰.
- [cypher-ruby](https://github.com/ston1x/cypher-ruby) - 如同 [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包括活动的 Ruby 版本.
- [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 和 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 容器中的主题.
- [daily-emoji](https://github.com/huytran-wq/zsh-daily-emoji-theme/) - 根据星期几在每个命令的开头显示随机表情符号.
- [daily](https://github.com/ghlin/zsh-theme-daily) - 包括 `git` 和 `ssh` 状态装饰.
- [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线主题.
- [dangerroom](https://github.com/abbreviatedman/dangerroom) - 内容丰富、极简，最重要的是，以 X 战警为主题.
- [dango](https://github.com/ann-kilzer/annkilzer.zsh-theme) - 包括当前目录和 `git` 状态的装饰.
- [danielparks](https://github.com/danielparks/danielparks-zsh-theme)  - 适用于深色背景. 包括 `git` 状态、`ssh` 会话中的 user@host、最后一个命令的成功/失败、工作目录、python virtualenv、最后一个命令的执行时间以及是否以 `root` 运行的装饰器.
- [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) 灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题. 具有 `git` 和最后一个命令退出状态装饰. 需要 nerdfont 才能正确渲染.
- [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - 这个版本的流行 [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 主题已通过近乎完整的重写实现模块化和一些新功能得到增强.
- [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - 基于`ys`和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
- [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - 包括电池状态和负载平均装饰.
- [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme)  - 最小化 ZSH 主题以减少干扰. 包括一个 iTerm 颜色设置文件.
- [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - 另一个带有嵌入式 `git` 状态的最小主题.
- [delta-prompt](https://github.com/cusxio/delta-prompt) - 一个最小的 ZSH 提示.
- [destiny](https://github.com/ja1dan/Destiny)  - 一个简单、可配置的 ZSH 提示，没有依赖关系.  Destiny 已经在 Linux、macOS 和 iOS 上进行了测试.
- [devj121](https://github.com/cjeonguk/devj121-zsh-theme) - 包括带有分支字形的 `git` 装饰.
- [dexter](https://github.com/shvenkat/zsh-theme-dexter) - 强调终端右侧（因此得名）的主题.
- [dino](https://github.com/OdilonDamasceno/dino-zsh-theme)  - 包括 node、golang、flutter、lua、python 和 java 的装饰，还包括 `git` 装饰. 需要书呆子字体.
- [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - 带有自定义 `LSCOLORS` 和 `LS_COLORS` 设置文件，适用于深色和浅色终端主题.
- [diy-ys](https://github.com/aprilnops/zsh-theme) - 变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
- [djkakaroto](https://github.com/djkakaroto/theme-zsh/) - 包括 `git` 状态装饰，适用于所有字体.
- [dkniffin](https://github.com/dkniffin/zsh-theme) - 包括 `ruby` 版本和 `git` 状态.
- [dmx](https://github.com/domix/dmx.zsh-theme) - 针对深色终端窗口进行了优化.
- [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - 极简主题，包括 `git`、`terraform` 和 `aws` 状态装饰.
- [doom](https://github.com/CMOISDEAD/doom-zsh)  - 厄运启发. 看起来类似于电力线. 具有可定制的段，`git` 状态、`rust`、`node.js`、`python` 和 `ruby` 版本的装饰器.
- [dp](https://github.com/davidparsson/zsh-dp-theme) - 显示当前 git 分支的低对比度主题，如果存储库是脏的并且 `$PYENV_VERSION` 的值.
- [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - 适用于深色背景，包括 `git` 状态装饰.
- [dracula](https://github.com/dracula/zsh) - Atom、Alfred、Chrome DevTools、iTerm 2、Sublime Text、Textmate、Terminal.app、Vim、Xcode 和 ZSH 的深色主题.
- [dragon (jeop10)](https://github.com/jeop10/dragon)  - 灵感来自 kali linux. 包括 `git` 状态和工作目录装饰.
- [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - 简约，包括 `git` 状态信息.
- [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - Reminiscent of [Powerline](https://github.com/powerline/powerline) . 包括目录、`git` 状态和主机名装饰.
- [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) 变体.
- [dtheme](https://github.com/OlukaDenis/DTheme)  - 针对使用日晒终端配色方案和“git”的人进行了优化. 最适合使用 unicode 字体.
- [duckster](https://github.com/ducky/duckster) - 一个叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH 主题更新鲜.
- [ducula](https://github.com/janjoswig/Ducula)  - 受德古拉项目的启发. 包括 `git` 状态装饰、用户名和主机名缩写、虚拟环境、当前工作目录、最后一个命令的返回状态和时间.
- [dustmod](https://github.com/bmihaila/dustmod) - 源自 [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) oh-my-zsh 中的主题.
- [dyzsh](https://github.com/daotoyi/dyzsh-zsh-theme)  - 基于天文. 包括 `git` 分支和哈希、当前目录、用户、主机和时间的装饰器.
- [dzhi](https://github.com/pentago/dzhi-zsh-theme) - 针对使用的人进行了优化 [Nord](https://www.nordtheme.com/) . 包括 `git` 状态装饰.
- [eckig](https://github.com/fouladi/eckig)  - 带有 utf-8 图标的极简主义主题. 包括 `git` 状态装饰和时钟.
- [efritas](https://github.com/erikfritas/efritas) - 包括用户名、主机名、`venv`、`rvm` 和 `git` 状态装饰.
- [eggshausted](https://github.com/inutano/eggshausted) - 一个 `git`-aware 主题，适合那些厌倦了出错的人.
- [elagoht](https://github.com/Elagoht/Elagoht.zsh-theme) - 包括主机名、当前目录、虚拟环境、`git` 状态和最后一个命令的执行时间的装饰.
- [elessar](https://github.com/fjpalacios/elessar-theme) - 基于 `git` 的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) . 需要与电力线兼容的字体.
- [elm](https://github.com/gacallea/elm-zsh-theme) - 包括 `git` 状态、user@host、日期、时间和路径装饰器.
- [elsa](https://github.com/faycito/elsa) - 包括根状态、密码和 `git` 状态装饰.
- [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - 表情符号风味 [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) 主题.
- [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，将 `git` 提示符号替换为表情符号，以提高清晰度.
- [emojirussell](https://github.com/Bergiu/emojirussell) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，带有当前工作目录的状态装饰，最后一个命令退出状态，`git` 分支和状态.
- [endless-dog](https://github.com/qwelyt/endless-dog) - 模仿 grml-zsh-config 的 oh-my-zsh 兼容主题.
- [enlightenment](https://github.com/w33tmaricich/enlightenment) - 包括 `git` 状态、`vi`-mode 指示器和最后一个命令执行时间的装饰.
- [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 在终端中占用大量空间.
- [erfan](https://github.com/ekm507/erfan-zsh-theme) - 的组合 [af-magic](https://github.com/和yfleming/oh-my-zsh) 和 [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` 和 `virtualenv` status decorations.
- [eriner](https://github.com/zimfw/eriner) - 受电力线启发的 Zim 叉子 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 提示主题. 包括 `git` 状态装饰.
- [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - 一个带有 `git` 信息的简单主题.
- [eucalyptus](https://github.com/relastle/eucalyptus) - 简约的 vi 模式用户的简单单行主题，灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
- [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的 ZSH 颜色主题.
- [ez-pz](https://github.com/mangosmoothie/ez-pz) - 带有“git”状态装饰的极简主义主题，灵感来自 [bureau](https://github.com/isqua/bureau).
- [fall](https://github.com/jottenlips/seasonal-zshthemes)  - 带有秋季图标的极简主义主题. 包括 `git` 状态装饰.
- [fattyarrow](https://github.com/sohnryang/fattyarrow) - 最小的 ZSH 提示，在深色背景下效果更好.
- [fdT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme)，预设包括 virtualenv、最后命令状态、`nvm`、`docker machine` 和 `git`、`hg` 和 `bzr` 状态装饰.
- [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)  - 干净、简单、兼容且有意义. 在 ANSI 颜色下在 Linux、Unix 和 Windows 上进行了测试.
- [filthy](https://github.com/molovo/filthy) - 令人作呕的干净 ZSH 提示.
- [fish](https://github.com/Raniconduh/zshfish)  - ZSH 主题让人想起默认的 `fish` shell 主题. 包括 `git` 状态装饰.
- [fishy-lite](https://github.com/sudorook/fishy-lite) - 原叉 [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy)  oh-my-zsh 中的主题，删除了许多无关内容以提高加载速度. 包括一个电池表和 `git` 状态显示，可以在提示的右侧启用.
- [fishy2](https://github.com/akinjide/fishy2) - ZSH 主题灵感来自 [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
- [fluent-git](https://github.com/RobertKozak/fluent-git) - 显示上次命令执行的时间、错误代码、主机名、用户名、`git` 状态、kubernetes 集群和命名空间、路径和 ssh 连接状态.
- [flux](https://github.com/jmg-duarte/flux-zsh) - 带有 `git` 状态装饰的严肃简约主题.
- [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 包括 `git` 状态装饰.
- [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括最后一条命令的状态、`git` 信息和当前目录.
- [frank](https://github.com/ronmackley/frank-theme)  - Frank 言简意赅，在一行中简洁而易读地显示信息. 弗兰克坚持事实，只在重要的时候告诉你额外的事情.
- [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉子 [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) 主题.
- [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于的主题 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 哦，我的 zsh 主题.
- [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 来自 oh-my-zsh 的主题.
- [fritz](https://github.com/fritzccc/fritz-zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
- [frlo](https://github.com/fiorillo/frlo) - 使用您计算机的主机名提出（希望）独特的三色主题以显示在您的提示中，因此您一眼就知道您登录的是哪台机器.
- [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 支持 `git` 和 `svn` 的彩色两行主题.
- [furio](https://github.com/hectorpalmatellez/furio-theme) - 叉子 [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) 哦，我的 zsh 主题. 用不同的颜色和表情符号.
- [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
- [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - 原来是一个叉子 [Bureau](https://github.com/isqua/bureau) 向提示符添加新的虚拟环境信息：Kubernetes、virtualenv、rbenv 和 Java 版本. 包括 `git` 状态集成.
- [gal](https://github.com/x6r/gal) - 基于极简主义主题 [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
- [garden](https://github.com/fecat233/garden) - 在深色终端背景下效果更好，包括 `git` 状态装饰.
- [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto 在您需要的时候提示您需要的信息.
- [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme)  - Nicola Racco 的主题. 需要 `rvm` 和 `git` 插件.
- [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示生成器，灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
- [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh `gentoo` 主题拆分为非 omz 用户的单独存储库.
- [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
- [geometry](https://github.com/geometry-zsh/geometry) - 一个最小的 ZSH 主题，可以将任何功能添加到左侧提示符或（异步）右侧提示符中.
- [gerry](https://github.com/GerryLarios/gerry-prompt) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#bureau), 包括 `git` 状态、当前时间、用户名、主机名和当前目录的装饰.
- [ghoti](https://github.com/lonr/ghoti)  - 模仿 `fish-shell` 默认提示. 包括 `git` 装饰.
- [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), 包括 `git` 装饰、IP 地址、主机和路径.
- [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - 一个变种 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) 具有更多功能、一点眼花缭乱和上下文相关的额外线条. 包括 `git` 状态装饰、历史编号、用户名/主机名上下文、目录状态、最后一个命令的状态（如果失败）以及 Python 虚拟环境名称（如果存在）.
- [gimme](https://github.com/nralbrecht/gimmezsh)  - 带有 `git` 集成的 ZSH 的简单主题. 灵感来自 [gitsome](https://github.com/mtully/gitsome) 主题.
- [girazz](https://github.com/mdentremont/girazz) - 对 gnzh 主题的修改，在右侧提示中添加了“vi”模式.
- [git-prompt (awgn)](https://github.com/awgn/git-prompt) - `bash`、`zsh` 和 `fish` 的快速 `git` 提示.
- [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt)  - 显示有关当前 `git` 存储库的信息. 特别是分支名称、与远程分支的差异、暂存或更改的文件数等.
- [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - 一个快速、可定制、纯 shell、异步 `git` 感知的 ZSH 提示，深受 Olivier Verdier 的启发 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) 和fish shell的“Informative VCS”提示非常相似.
- [git-prompt-kit](https://github.com/olets/git-prompt-kit) - 一组可配置的组件，用于以最少的编码创建功能丰富、高性能的 Git 感知 zsh 提示（又名主题）.
- [git-simple](https://github.com/ZakharEl/git-simple-theme) - 简单的主题，包括详细的 `git` 状态装饰.
- [github](https://github.com/Debdut/github.zsh-theme/)  - 受 GitHub 启发的主题. 显示（截断的）当前目录、主机名和 `git` 状态的装饰器. 包括亮模式和暗模式，并检测 macOS 和 Linux 上的系统设置.
- [gitsome](https://github.com/mtully/gitsome) - 带有 `git` 信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
- [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - 显示命令和 `git` 状态装饰.
- [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)  - 在 `git` 存储库中时，它显示来自 `git` 存储库根文件夹的位置. 当不在 `git` repo 中时，它会显示相对于 home 的路径，`~`.
- [gitster (zimfw)](https://github.com/zimfw/gitster) - shashankmehta 的 Zim 叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 提示主题
- [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 从原来的分叉 [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) 主题.
- [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - 包括 `git` 状态装饰和当前目录的完整路径.
- [glimmer](https://github.com/martnu/glimmer) - 包括 `git` 分支、时间和 user@host 装饰器.
- [gndx](https://github.com/gndx/gndx-zsh-theme) - 包括 `git` 状态、主机名、目录和最后一个命令退出状态装饰.
- [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - 定制 [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 来自 oh-my-zsh.
- [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh)  - iTerm 2 和 ZSH 的主题. 不包括 `git` 状态、user@host、路径和日期装饰器.
- [gops](https://github.com/noxer/gops)  - 快速类似电力线的提示. 包括 `git` 状态、当前目录、根状态装饰.
- [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括 `git` 装饰和最后一个命令的返回状态.
- [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - 极简主义，包括 `git` 状态装饰.
- [grs](https://github.com/gersontpc/zsh-theme-grs) - 包括 `git` 状态、用户 ID 和工作目录装饰器.
- [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - 设置颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` 插件.
- [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874), 使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` 插件.
- [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - 极简主义，包括 `git` 状态装饰.
- [gugulenok](https://github.com/gugulen0k/gugulenok/)  - 有暗模式和亮模式. 包括 `git` 状态、时间和当前目录的装饰器.
- [guri](https://github.com/victorfsf/guri) - 一个简单快速的 Oh-My-Zsh 主题，基于 [Pure](https://github.com/sindresorhus/pure)的设计.
- [gusrylmubarok](https://github.com/gusrylmubarok/gusrylmubarok-zsh-theme/) - 包括 `git` 状态和最后命令退出状态的装饰器.
- [hackersaurus](https://github.com/bhilburn/hackersaurus)  - 带有“git”状态的主题和嵌入在提示中的最后一个命令运行装饰器的退出代码. 相关 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题.
- [halil](https://github.com/5m0k3r/zsh-themes) - oh-my-zsh 的分叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
- [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)  - 一个简单的主题，第一个字符是花（hana），即花的汉字. 这个主题的灵感来自一个名为 DSA Hana 的键帽集. 这与 [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) 主题. 包括 `git` 状态装饰.
- [handy](https://github.com/hanleylee/handy)  - 多彩和轻量级的主题. 显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰.
- [hanpen](https://github.com/kojole/hanpen.zsh-theme) - 如果超过 `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`，则显示 `git` 分支和状态、最后一个命令退出代码、最后一个命令执行时间.
- [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - 基于氧化物，包括 `git` 状态装饰和当前用户/主机信息.
- [haribo](https://github.com/haribo/omz-haribo-theme) - 简单的 `git` 状态 + 提示中的时间戳.
- [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
- [headline](https://github.com/Moarram/headline) - 响应式 ZSH 主题，具有 Git 状态信息和提示上方的彩色线条.
- [heart](https://github.com/gko/heart) - 浅色背景的心脏主题提示.
- [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau)，添加了 `git` 状态装饰和 `npm` 状态.
- [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
- [hematite](https://github.com/bigdave/hematite) - 极简主义促销，试图仅显示在给定时间非常有用的状态装饰.
- [hexagon](https://github.com/diogoazevedos/hexagon) - 基于极简主义 zsh 主题 [geometry](https://github.com/geometry-zsh/geometry).
- [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间、日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
- [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - 灵感来自 robbyrussell 主题 + ssh 连接状态提示.
- [hina](https://github.com/ucpr/hina) - 用 `golang` 编写，包括 `git` 状态装饰和 kubernetes 上下文.
- [hip-fellow](https://github.com/haitaim/hip-fellow) - 包括 `git` 状态装饰并使用标准字体.
- [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 一个变种 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [home](https://github.com/sheerun/home) - 漂亮而简短的单行主题，让您有宾至如归的感觉.
- [hometown](https://github.com/olets/hometown-prompt) - 一个功能丰富、高性能的 `git` 感知 ZSH 主题，包含用户、主机、时间、当前工作目录及其父级的段，以及 Git 存储库中详细的完整 Git 状态.
- [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - oh-my-zsh 和 iTerm 2 的 Honukai 主题和颜色.
- [horizontal](https://github.com/nuimk/horizontal) - 带有水平分隔符的两行提示.
- [hornix](https://github.com/fusion809/zsh-theme) - 显示时间和日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
- [horse-sh](https://github.com/emileswarts/horse-sh) - 一个非常简约的棕色/红色 ZSH 主题.
- [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - 简单干净，包括最后执行的命令的返回码.
- [hug](https://github.com/xxninjabunnyxx/hug-zsh)  - 当你工作并需要一个拥抱时. 包括 `git` 状态.
- [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - 一个简洁的主题，支持 `condaenv`、`virtualenv` 和 `git` 状态装饰，以粗体与工作目录对齐.
- [hydrogen](https://github.com/xylous/hydrogen)  - 一个简单的多行 ZSH 主题. 它显示用户名、主机名、当前目录和 `git` 状态装饰.
- [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - 设计用于超级终端主题，包括 `git` 状态装饰.
- [hyperzsh](https://github.com/tylerreckart/hyperzsh) - 让您全面了解您正在处理的分支和存储库的状态，而不会弄乱您的终端.
- [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX)  - 修改了 iGeek 主题. 开箱即用，可与 macOS 配合使用，包括 `git` 状态装饰.
- [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - 在深色背景上效果很好.
- [iay](https://github.com/aaqaishtyaq/iay)  - 一个用 Rust 编写的 `{ba,z}sh` 提示. 包括当前目录和 `git` 状态的装饰.
- [ice](https://github.com/Lenart12/ice.zsh-theme) - 非常轻微的修改 [bureau](https://github.com/isqua/bureau) 主题结合 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
- [icicle](https://github.com/JamesConlan96/Icicle) - 包括 `git` 状态装饰，以及是否以 root 身份运行.
- [igeek](https://github.com/Saleh7/igeek-zsh-theme) - 启动新的终端会话时显示系统信息.
- [iggy](https://github.com/eugenk/zsh-prompt-iggy) - 一个超级快乐的电力线风格，`git`-aware **prezto only** 主题.
- [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录、可自定义的分隔符、当前分支和 `git` 状态装饰器.
- [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - 包括 `git`、`nvm` 和 `venv` 装饰.
- [illusion](https://github.com/shabane/illusion) - 包括用户名、当前工作目录、`git` 状态和最后命令状态装饰器.
- [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉子 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) 间距改进和更新的图标. 包括 `git` 状态信息.
- [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化.
- [infernus](https://github.com/jshiell/infernus-zsh-theme) - 极简主义主题，更适合深色背景.
- [infoline](https://github.com/hevi9/infoline-zsh-theme) - 显示“git”状态、后台作业、远程主机和其他信息的清洁主题.
- [inthedeepspace](https://github.com/alionapermes/inthedeepspace/) - 基于 [intheloop](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#user-content-intheloop) 并受到启发 [vim-deep-space](https://github.com/tyrannicaltoucan/vim-deep-space).
- [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 的扩展 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 使用电力线字体的主题.
- [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy 的主题.
- [itlbv](https://github.com/itlbv/itlbv-ohmyzsh-theme)  - 极简主义者. 包括 `git` 状态和当前目录的装饰器.
- [ivabus](https://github.com/ivabus/ivabus-zsh-theme)  - 受 GitHub Codespaces 提示的启发. 包括 `git` 状态、用户名和当前目录的装饰器.
- [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy)  - 适用于深色背景. 包括 user@host、`git` 状态和时间装饰器. 基于 [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) 主题.
- [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  - 基于精致和 ys 主题，包括 `git` 状态装饰. 包括一个可选的 iterm2 颜色方案.
- [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 如果分支有未推送的更改，则显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 +.
- [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - 针对深色背景进行了优化，包括 `git` 状态和 `rvm` 状态.
- [jc](https://github.com/jclementex/jc-zsh-theme) - 对于深色终端背景，包括 `git` 状态信息.
- [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - 松散地基于 `ys` 主题.
- [jerome](https://github.com/jeromescuggs/jerome-theme) - 基于的多彩主题 [dieter](https://github.com/jeromescuggs/jerome-theme) 主题，但带有黄色主机名. 包括 `git` 装饰.
- [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - 包括 `git` 和 python virtualenv 状态装饰、用户、密码、时间和系统名称.
- [jnooree](https://github.com/jnooree/jnooree-zsh-theme) - 极简主义主题，颜色改编自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题. 包括 `git` 状态的装饰器，无论是否作为非默认用户和当前工作目录运行.
- [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - 一个简化 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 与颜色 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
- [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme)，包括“git”状态.
- [jovial](https://github.com/zthxxx/jovial) - 显示主机、用户、路径、开发环境、`git` 分支以及哪个 `python` venv 处于活动状态的装饰器.
- [jpegleg](https://github.com/jpegleg/zshrc) - 类似于暗血主题，包括时间戳和 `git` 装饰.
- [js-magic](https://github.com/JSextonn/js-magic) - 简化版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括当前工作目录和 `git` 状态装饰.
- [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - 极简主义提示.
- [just-another](https://github.com/supertassu/another-theme) - 只是另一个主题，当您 sshed 到另一台机器时使用主机名.
- [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner)  - 倒计时直到圣诞节. 包括 `git` 状态装饰.
- [jwalter](https://github.com/jeffwalter/zsh-jwalter)  - 带有 `git`、`svn`、`npm`、`rvm` 和网络意识的电力线风格主题. 需要与电力线兼容的终端字体.
- [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Powerlevel 10K 的配置文件和安装程序.
- [kali](https://github.com/h4ck3r0/kali-theme) - 包括 `git` 装饰.
- [kalsowerus](https://github.com/kalsowerus/kalsowerus.zsh-theme) - 受电力线启发的彩色多线主题，包括 `git` 状态、目录、最后命令退出状态和 `nvm` 信息的装饰.
- [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
- [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
- [kenton](https://github.com/notnek/zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
- [kevin](https://github.com/KevinParnell/Kevin-zsh) - 丰富多彩的主题，包括 iTerm 2 配色方案.
- [kgzsh](https://github.com/Kashugoyal/kgzsh) - 包括`git`状态deorations，适用于较暗的背景.
- [kido](https://github.com/KidoThunder/kido-zsh-theme)  - 基于 `ys` 和 `robbyrussell` 主题. 包括上次命令运行的退出代码、python virtualenv 和 VCS 状态的装饰器.
- [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - 最小的主题.
- [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于 Fishy 主题，但显示完整路径而不是缩写目录，并且仅在 `ssh` 会话和 docker 容器中显示 user@machine.
- [kirkdawson](https://github.com/kdawson133/KirkDawson)  - 受电力线启发. 包括 `git` 状态、最后命令退出状态、用户@主机名、工作目录以及用户是否以 root 身份运行的提示装饰.
- [kiss](https://github.com/rileytwo/kiss)  - 用于 oh-my-zsh、VSCode、iTerm2、Neovim 和 RStudio 的简单主题. 包括 `git` 状态装饰.
- [kketcham](https://github.com/prototype27/kketcham) - `git` 信息上带有漂亮颜色的主题.
- [korittg](https://github.com/dkorittki/korittg-zsh-theme)  - 简约但内容丰富. 包括 `git` 状态、当前目录和 `kubectl` 上下文和命名空间的装饰.
- [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  - 最适合深色背景. 包括 `git` 状态装饰.
- [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - 为深色终端设计的两行主题，具有 `git` 装饰.
- [krak3n](https://github.com/krak3n/zsh-theme) - 显示 golang 版本和当前的 `git` 分支.
- [kraken](https://github.com/KrakenTheme/kraken-zsh) - ZSH 的黑暗主题.
- [kube](https://github.com/tigerjz32/kube-zsh-theme) - 基于 [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal) , 包括 `kubectl` 上下文. 有时间、目录和 `git` 状态装饰.
- [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - Agnoster 前叉针对日晒终端进行了优化. 需要与电力线兼容的字体.
- [kw](https://github.com/Kwpolska/kw.zsh-theme) - 带有 `git` 和 `hg` 状态信息的彩色主题，能够将特定于主机的颜色添加到主机名.
- [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme)  - 一个简单的主题，第一个字符是九（kyuu），数字 9.原色是带有洋红色调的蓝色. 包括 `git` 状态装饰.
- [lagune](https://github.com/noplay/lagune) - 一个最小的 ZSH 主题.
- [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 灵感来自 [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) 主题. 包括 `git` 状态装饰.
- [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - 为使用 unicode 兼容字体和终端应用程序的 `git` 用户优化的 ZSH 主题.
- [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit)  - 包括快速、详细的 `git` 信息. 需要书呆子字体和 [gitstatus](https://github.com/romkatv/gitstatus) 插入.
- [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含“git”信息的极简提示.
- [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - 基于 lambda 的简单主题，带有 `git` 状态和 virtualenv 信息.
- [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的 ZSH 主题，针对 `git` 使用进行了优化.
- [lambda-p](https://github.com/paimanb和i/lambda-p) - 灵感来自 [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) 和 [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) 主题. 包括 `git` 状态装饰.
- [lambda-pure](https://github.com/marszall87/lambda-pure) - 一个最小的 ZSH 主题，基于 [pure](https://github.com/sindresorhus/pure), 添加了 NodeJS 版本装饰器.
- [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - Lambda 和 Fishy 主题的组合，包括 `git` 状态装饰.
- [lambda-zen](https://github.com/seamile/lambda-zen) - 灵感来自 [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) 带有图形 `git` 状态装饰.
- [lambder](https://github.com/avillen/zsh-theme-lambder) - 包括 `git` 状态装饰，最适合深色终端主题.
- [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme)  - 在深色背景下效果最佳. 基于伟大的`ys`主题和 [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh) . 显示根状态和 `git` 状态装饰.
- [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - 针对暗终端进行了优化，具有本地和远程系统的变体.
- [leafia](https://github.com/Ghostrick/leafia-prompt) - 显示 `git` 状态信息的多叶 prezto 主题.
- [lean](https://github.com/miekg/lean) - 灵感来自 [pure](https://github.com/sindresorhus/pure) . 包括 `git` 状态和后台作业装饰.
- [lemon](https://github.com/carlosvitr/lemon_zsh)  - 许多美丽的颜色供您欣赏. 小心和耐心地完成. 包括 `git` 状态和 ruby​​ 版本装饰.
- [leon](https://github.com/prince-an/Leon_zshTheme)  - 在浅色背景下效果很好. 包括 `git` 状态、时间、用户名@主机、工作目录和最后一个命令退出状态装饰.
- [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), 使用颜色和额外的 `¬` 字符，以更好地区分命令行提示符和输出.
- [lewis](https://github.com/lewisflude/oh-my-lewis)  - 黑色、白色和红色主题. 显示 `git` 状态信息.
- [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - 包括内核、操作系统版本、正常运行时间和 `git` 的装饰.
- [lighthaus](https://github.com/lighthaus-theme/zsh) - 一个提示，恭维 [Lighthaus](https://github.com/lighthaus-theme/lighthaus) 主题. 显示 `git` 信息、github/gitlab 徽标并在发生更改时显示更改.
- [lila](https://github.com/raphaelivan/lila-zsh-theme) - 极简主义主题，最适合深色终端背景.
- [lilith](https://github.com/aknackd/zsh-themes) - 修改 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) 和 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
- [lime](https://github.com/yous/lime) - 简单且易于定制的 ZSH 主题.
- [limpide](https://github.com/shooteram/limpide) - 修改版 [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
- [linear](https://github.com/MrYazdan/zsh-linear-theme)  - 让人想起电力线. 包括具有 `git` 状态、Pythonvirtualenv、当前目录和当前时间的段.
- [link](https://github.com/kylegl/link-zsh-theme)  - 极简主义者. 包括 `git` 状态和最后一个命令退出装饰.
- [linuxer](https://github.com/patrick330602/linuxer) - 灵感来自 Yaris Alex Gutierrez  [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood 的 `ys`, 和 [Bureau](https://github.com/isqua/bureau) 主题.
- [linuxero](https://github.com/andreshincapier/linuxero)  - 极简主义者. 包括根状态、当前目录、`git` 状态、当前 ruby​​ rvm 环境和当前 python virtualenv 的装饰.
- [liquidprompt](https://github.com/nojhan/liquidprompt)  - 一个功能齐全且精心设计的自适应提示，在您需要时提供有用的信息. 它会在您需要时向您展示您需要什么. 当它发生变化时，您会注意到发生了什么变化，从而节省时间和挫败感.
- [lish](https://github.com/bashelled/lish)  - 一个休闲的主题. 没有粗糙，只有光滑. 包括 `git`、user@host、最后一个命令退出状态、当前目录、当前时间和根状态装饰器.
- [liver](https://github.com/RenoirTan/liver.zsh-theme) - 色彩丰富，包括 `git` 状态、用户、主机、当前和当前存储库根装饰的相对路径.
- [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的美洲驼使用的极简主义主题.
- [logico](https://github.com/logico/logico-zsh-theme)  - 有 `git` 装饰. 显示 vi 模式的远程状态和指示灯.
- [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 基于 Sindre Sorhus 纯主题的德克萨斯主题.
- [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - 包括 `git` 和紧凑的 `pwd` 装饰.
- [lorond](https://github.com/lorond/zsh-lorond/) - 精简版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括 `git` 状态，适用于标准字体.
- [luceast](https://github.com/LucEast/luceast-zsh-theme)  - 为 `git` 优化. 包括用户名、主机、时间和工作目录的装饰.
- [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  - lambda-mod 主题的变体. 具有 `git` 装饰，需要与电力线兼容的终端字体.
- [luke](https://github.com/xueguangl23/luke_zsh_theme)  - 包括 `git` 装饰. 基于 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 哦，我的 zsh 主题.
- [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - 的扩展版本 [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) 主题. 包括 `git` 状态的装饰和最后一次命令运行的状态.
- [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - 极简主义主题.
- [macos](https://github.com/alejandromume/macos-zsh-theme) - 包括 `git` 状态装饰.
- [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - 包括 `git` 状态和最后命令执行时间装饰.
- [magicmace](https://github.com/zimfw/magicmace) - 灵感来自 xero 的 ZSH 提示和 [eriner's prompt](https://github.com/zimfw/eriner) . 包括活动 python `venv` 的状态代码、最后一个命令的退出状态、缩短的工作目录、`git` 状态装饰.
- [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN 的神奇主题.
- [mainnika](https://github.com/mainnika/zsh-theme-mainnika/) - 包括最后一个命令退出状态和 1、5 和 15 分钟平均负载的装饰器.
- [maivana](https://github.com/nylo-andry/zsh-themes) - 包括 `kubectl` 上下文，`git` 状态装饰.
- [majemoji](https://github.com/metalogica/majemoji)  - 在每个会话的提示中添加一个随机表情符号. 包括 `git` 状态装饰.
- [materialshell](https://github.com/carloscuesta/materialshell) - 一个 [material design](https://material.io/guidelines/style/color.html) 您的外壳主题具有良好的对比度和重要部分的颜色流行. 专为保护眼睛而设计.
- [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 风格看起来像 Matrix 电影三部曲中的东西. 包括 `git` 状态装饰.
- [matter](https://github.com/mrobillard/matter-zsh-theme) - 显示 `git` 状态、AWS 保管库角色、后台作业、最后一个命令的退出代码和主机名.
- [mau](https://github.com/vichargrave/mau)  - 带有猫扭曲的 ZSH 主题. 包括 `git` 状态装饰. 基于 [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) 和 [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) 主题.
- [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - 包括 `git` 装饰，如果是 root 用户，则更改提示颜色，活动作业和 [jenv](https://github.com/jenv/jenv) 一体化.
- [mdmini](https://github.com/MarioDena/MDmini) - 包括 `git` 和 `ssh` 状态装饰.
- [megaprompt](https://github.com/willghatch/zsh-megaprompt)  - 包含键盘模式、所有权信息和其他上下文信息的最大化提示，以 λ 作为提示字符. 需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
- [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - 包括 `git` 状态装饰，如果非零则显示最后一个命令的退出代码.
- [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  - 检查 `/sys/class/power_supply` 文件夹以确定系统是安装在笔记本电脑还是台式机上. 读取电池百分比 grepping acpi 命令并在提示符中显示. 包括 `git` 装饰.
- [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - 包括 `rvm` 和 `git` 状态装饰.
- [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX 友好的跨平台 [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/方便的时间戳和完整的 git/ruby 支持.
- [midin](https://github.com/xlshiz/midin) - 适用于深色终端背景，包括 `git` 状态装饰.
- [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - 极简主义，包括 `git` 状态装饰.
- [milight](https://github.com/frodoslaw/milight-zsh) - 带有 `git` 状态显示的最小 ZSH 提示，最适合深色终端背景.
- [min](https://github.com/andrepolischuk/min) - 一个简约的 ZSH 提示.
- [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - 考虑到空间的 ZSH 主题.
- [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt)  - 极简主义者. 包括 `vcs` 状态装饰.
- [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - 包括`git`、`node`、`golang`、`yarn`、`php`、`docker`和`python`状态装饰.
- [minima (ednikolenko)](https://github.com/ednikolenko/minima)  - 带有 `git`、`docker`、`go`、`node`、`npm`、`python` 和其他指标的最小 ZSH 主题. 对某些标记使用 unicode 字符.
- [minimal (glsorre)](https://github.com/glsorre/minimal/) - 一个最小的异步 ZSH 主题优化使用 [Fira Code](https://github.com/tonsky/FiraCode) 字体和 [Solarized Light](https://ethanschoonover.com/solarized) 终端主题.
- [minimal (subnixr)](https://github.com/subnixr/minimal) - 最小但功能丰富的主题.
- [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，包括右侧提示中的 `git` 装饰.
- [minimal2](https://github.com/PatTheMav/minimal2)  - 一个最小且可扩展的 ZSH 主题. 分叉自 [subnixr's original](https://github.com/subnixr/minimal) 并适应 [Zimfw](https://github.com/zimfw/zimfw).
- [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 灵感来自 oh-my-zsh 的 kolo 主题.
- [mira](https://github.com/mbStavola/mira) - 一个修改 [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) 带有时间信息和简化的开始提示.
- [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - 包括 `git` 状态、最后命令退出代码、`sudo` 时间戳文件是否存在以及当前活动的 Python 虚拟环境的提示装饰.
- [miramare](https://github.com/franbach/oh-my-deepin-miramare)  - 包括 `git` 状态装饰. 最适合搭配 [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
- [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs 的 ZSH 主题.
- [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - 针对深色背景进行了优化.
- [mnml](https://github.com/mnml-theme/prompt) - 带有 `git` 状态装饰的最小主题.
- [mochi2](https://github.com/mochidaz/zsh-themes)  - 极简主义主题. 包括 `git` 和 `hg` 状态装饰.
- [mochi](https://github.com/mochidaz/zsh-themes)  - 简单的主题，旨在类似于 rust 的主要功能. 包括 `git` 和 `hg` 状态装饰.
- [moderno](https://github.com/obrassard/moderno-zsh) - 一个简单而现代的 ZSH 主题，灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH 的主题. 包括 `git` 状态装饰.
- [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - 简洁的 ZSH 主题，带有 `condaenv`、`virtualenv` 和 `git` 状态装饰，整齐地右对齐显示.
- [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
- [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme)  - 让人想起电力线. 包括 `git` 状态、用户名和工作目录的装饰.
- [moonline](https://github.com/kagamilove0707/moonline.zsh) - 最小但易于扩展的提示.
- [moux](https://github.com/gagbo/moux) - 适用于深色终端背景，包括 `RPROMPT` 中的 `git` 装饰.
- [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/)， 在下面 [ZSH](https://en.wikipedia.org/wiki/Zsh) 也 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
- [multiline](https://github.com/jan-auer/zsh-multiline) - 基于电力线风格的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
- [muslim](https://github.com/nksoff/muslim) - 一个简单的最小 ZSH 提示主题.
- [musy](https://github.com/THaGKI9/musy-zsh-theme)  - 灵感来自缪斯主题. 包括 `git` 状态装饰.
- [my-hl2](https://github.com/liamm91/my-hl2)  - 包括 virtualenv、`git` 状态和目录装饰. 基于 omz  [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) 主题.
- [my](https://github.com/fabiendelpierre/my-zsh-theme/) - 变体 [kolo](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#kolo).
- [mzpt](https://github.com/linrongbin16/mzpt/) - 受启发的最小提示 [powerlevel10k](https://github.com/romkatv/powerlevel10k).
- [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia 的 myzsh 主题.
- [mzt](https://github.com/honbey/mzt) - 设置`LS_COLORS`，着色`diff`并包括`git`状态和当前工作目录装饰.
- [nanofish](https://github.com/tweekmonster/nanofish) - 为纳米技术主题添加鱼式目录提示.
- [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - 带有文本“git”状态装饰的极简主义主题.
- [nctu](https://github.com/leovincentseles/nctu.zsh-theme)  - 强调速度的轻量级主题. 包括 `git` 状态装饰.
- [neewbie](https://github.com/neewbee/neewbee.zsh-theme)  - 带有 `git` 装饰的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
- [neo](https://github.com/Saeed-MFarahani/Neo-ZSH-Theme/) - 包括 `git` 状态、当前目录、用户@主机名、时间以及是否以 root 身份运行的装饰器.
- [neon-potato](https://github.com/algosuna/neon-potato)  - 多彩和简约的主题. 包括 `git` 装饰.
- [neon](https://github.com/sahariko/neon) - 带有 `git` 装饰的漂亮且最小的 ZSH 主题.
- [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - 带有书呆子字体的 ZSH 提示主题.
- [nescalante](https://github.com/nescalante/zsh-theme) - 针对深色终端背景进行了优化，包括 `git` 装饰.
- [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - 包括 `git` 装饰和 `vi` 模式指示器.
- [newt](https://github.com/softmoth/zsh-prompt-newt)  - 胖而快的主题——内外都很漂亮，风格片段做得对. 高度可定制，包括 `git`、用户名、执行时间、目录、后台作业和编辑模式装饰.
- [newton](https://github.com/sebastienfilion/zsh.newton) - 包括 `git` 状态和外部 IP 地址装饰.
- [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - 一个非常基本的主题，只有一个 macOS 自行车图标.
- [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - 色彩丰富，显示 `git` 状态装饰.
- [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme)  - 小而简单的 oh-my-zsh 主题. 显示当前目录和后面的 2 个目录，`git` 和 `nodejs` 状态装饰.
- [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - 基于 af-magic.
- [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - 一个简单的 oh-my-zsh 主题.
- [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - 带有 `git` 状态装饰的极简主义 ZSH 主题.
- [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh 的节点主题，为了便于与其他插件管理器一起使用而进行了拆分.
- [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - 基于 ys 主题，添加了 NodeJS 版本（来自 NVM 插件）.
- [noon](https://github.com/silky/noon.zsh-theme) - 有浅色和深色的变体，显示 `git` 信息.
- [nord](https://github.com/TyWR/Nord-zsh) - 包括 `git` 状态装饰并显示活动的 conda 环境.
- [normanius](https://github.com/normanius/normanius-zsh-theme) - 源自 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
- [nothing](https://github.com/eendroroy/nothing) - 闪电般快速且非常简单，因为它几乎没有任何内容.
- [nova](https://github.com/body20002/nova)  - 包括 `git` 状态 decroations. 覆盖 `LS_COLORS` 和 `LSCOLORS` 设置.
- [nox](https://github.com/kbrsh/nox) - 深色主题，显示当前工作目录和 git 状态.
- [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)  - 一个干净、无干扰且以“git”为重点的开发主题. 显示相对于 `git` 根的路径（或 ~ 当在 `git` 存储库之外时）、自上次提交以来的时间、当前 SHA、分支和分支状态.
- [nunorc](https://github.com/nunorc/nunorc.zsh-theme)  - 极简主义主题，适用于深色背景. 包括 `git`、`mercurial` 和 `svn` satus 装饰.
- [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - prezto 和 oh-my-zsh 的简单主题.
- [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - 极简主题，包括 `git` 状态装饰和时间.
- [oblong](https://github.com/Ansimorph/oblong) - 简单的 `bash` 启发主题，基于 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last comm和 run, `git` branch 和 its clean/dirty status.
- [odie](https://github.com/masterodie/zsh-theme-odie/)  - 在深色背景上效果很好. 包括 `git` 状态、python virtualenv 和 `vi`-mode 状态装饰.
- [odin](https://github.com/tylerreckart/odin) - Odin 是一个 `git` 风格的 ZSH 主题.
- [odra](https://github.com/ErikBenavides/odra.zsh-theme)  - 色彩丰富，适用于深色背景. 包括 `git` 状态、当前目录、用户名和最后一个命令的退出状态的装饰器.
- [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有 `git` 装饰的多行主题.
- [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 对 bash 和 ZSH 的自以为是的提示.
- [oh-my-posh](https://ohmyposh.dev/)  - 不是 ZSH 特定的，但非常好，可以与 ZSH 一起使用. 允许您对所有 shell 中的提示使用相同的配置.
- [oh-my-via](https://github.com/badouralix/oh-my-via) - ZSH 的主题，主要分叉威盛服务器上使用的历史主题.
- [ohmypc](https://github.com/joselpadronc/OhMyPC)  - 适用于深色终端窗口. 包括 `git` 装饰.
- [om](https://github.com/sirshikher/zsh-om) - 最小主题，适用于深色背景，包括 `git` 状态装饰.
- [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题.
- [omuse](https://github.com/ouuan/omuse-zsh-theme) - 基于 Oh-My-ZSH  [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) . 具有 `git` 状态、时间、绝对密码、RAM 使用量、最后一个命令使用的时间和最后一个命令退出状态的装饰.
- [ortiz (andres-ortizl)](https://github.com/andres-ortizl/ortiz-zsh-theme) - 叉子 [eriner](https://github.com/zimfw/eriner) 装饰命令和 k8s 上下文之间的间隔.
- [ortiz (guezwhoz)](https://github.com/guesswhozzz/guezwhoz-zsh-theme) - 简化的分叉 [eriner](https://github.com/zimfw/eriner) 带有 `git` 状态、`kubectl` 上下文和经过时间的装饰.
- [owczarczak](https://github.com/ThemysciraData/owczarczak.zsh-theme) - 灵感来自比拉、节食者和 [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme) . 包括 `venv` 和 vcs 状态装饰.
- [owi](https://github.com/owitech/zsh-theme/) - 带有“git”状态装饰的极简主义主题.
- [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - 包括 `git` 状态和 virtualenv 信息.
- [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - 简约和黑暗的 ZSH 主题.
- [ozono](https://github.com/sfabrizio/ozono-zsh-theme) OZ0NO - 让我们呼吸干净的 ZSH.
- [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) 提示强调简单性，同时仍然可以获取重要信息.
- [pad](https://github.com/eproxus/pad.zsh-theme) - 简洁多彩的 oh-my-zsh 主题.
- [page](https://github.com/SLIB53/page-zsh-theme)  - 一个带有 VCS 支持的简单主题. 提示显示当前工作目录的 1 级、分支和一个颜色编码的弯曲粗箭头.
- [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - 允许显示主机信息，包括 `git` 分支装饰.
- [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - 在提示中使用图标显示详细的 `git` 状态信息.
- [panda](https://github.com/davymai/oh-my-zsh-panda-theme)  - 包括 `git` 和 `root` 状态装饰. 最好在深色背景上.
- [papercolor](https://github.com/erikschreier/PaperColor-themes)  - ZSH、`vim` 和 `tmux` 的配色方案. 包括 `git` 状态装饰.
- [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion)  - 包括 `git` 状态装饰，以毫秒为单位的命令运行时间. 在 macOS 上需要 coreutils.
- [pastel](https://github.com/iboyperson/pastel) - 一个受启发的 ZSH 主题 [sugar-free](https://github.com/cbrock/sugar-free) . 包括 `git` 装饰.
- [paxton](https://github.com/p1xt4n/ohmyzsh-theme-paxton)  - 灵感来自电力线. 包括 `git` 分支、时间、最后一个命令退出状态和当前目录的段. 需要与电力线兼容的字体.
- [pecodez](https://github.com/pecodez/pecodez-zsh-theme)  - 针对黑暗终端进行了优化. 具有用于 `snyk` 版本、`node` 版本、AWS 配置文件、kubernetes 上下文和 `git` 状态的装饰器.
- [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - 修改版 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 渗透测试者的主题，其中包括渗透测试日志记录的日期、时间和 IP 地址.
- [persi](https://github.com/persiliao/persi-zsh-theme)  - 包括 `git` 装饰. 适用于浅色和深色背景.
- [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - 本着精神的最小主题 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和纯壳主题.
- [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - 丰富多彩的主题，包括`golang`版本、`node`版本和`git`状态.
- [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - 一个干净简单的 ZSH 主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
- [pi](https://github.com/tobyjamesthomas/pi) - 带有 `git` 状态装饰的简约主题.
- [piboy](https://github.com/sflems/piboy-zsh-theme)  - ZSH 的简单优雅的多行主题. 包括彩色时间戳、“git”和语法高亮以及提升的根主题.
- [pifabs](https://github.com/pifabs/pifabs-zsh-theme) - 带有 `git` 状态、用户名、主机和工作目录的装饰器的最小主题.
- [plain-ui](https://github.com/purveshpatel511/plain-ui) - 极简主义，但包括 `git` 状态装饰.
- [plain](https://github.com/jimeh/plain.zsh-theme) - 一个简单的 ZSH 主题，显示基本的 `git` 信息.
- [planet](https://github.com/borb/planet-zsh) - 精简版 [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
- [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - 简单、简洁的主题.
- [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme)  - 基于对植物和苹果的热爱的极简主义主题. 包括 `git` 状态装饰.
- [platypus](https://github.com/fdv/platypus) - Platypus 是 Frédéric de Villamil 使用的 oh-my-zsh 的简单方便的主题.
- [pointer](https://github.com/gpinkard/pointer-zsh-theme) - 显示工作目录、上一条命令的返回状态和 `git` 当前分支.
- [polyglot](https://github.com/agkozak/polyglot) - `zsh`、`bash`、`ksh​​93`、`mksh`、`pdksh`、`dash`和busybox`ash`的动态提示，它使用基本的ASCII符号（和颜色，如果可能的话）来显示用户名，无论是本地还是远程 `ssh` 会话、缩写路径、`git` 分支和状态、最后一个命令的退出状态（如果非零）、使用 `virtualenv`、`venv`、`pipenv`、` 创建的任何虚拟环境诗歌`或`conda`.
- [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM 的基本 oh-my-zsh 自定义主题.
- [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - 带有 `git` 状态、ruby 版本和项目路径的程序员主题.
- [powerbash](https://github.com/erikschreier/powerbash-zsh) - 适用于深色终端背景，包括 `git` 状态装饰.
- [powerless](https://github.com/martinrotter/powerless) - 受电力线启发的小而简单的纯 ZSH 提示.
- [powerlevel10k](https://github.com/romkatv/powerlevel10k) - 快速重新实现 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH 主题. 可以用作 powerlevel9k 的直接替代品，当给定相同的配置选项时，它将生成相同的提示，只是速度更快.
- [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k 是 ZSH 的主题，它使用 [Powerline Fonts](https://github.com/powerline/fonts) . 它可以与 vanilla ZSH 或 ZSH 框架一起使用，例如 [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)， 和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
- [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - 两线版本的电力线：一根用于信息，一根用于输入.
- [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)  - 另一种电力线主题. 可以很好地配置，但至少需要一个支持 256 色的终端，并带有与电力线兼容的终端字体.
- [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个 `git` 感知电力线主题.
- [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
- [powerline-go](https://github.com/justjanne/powerline-go)  - 一个漂亮实用的低延迟提示，用 golang 编写. 包括 `git` 和 `hg` 状态装饰、上次命令运行的退出状态、当前 Python 虚拟环境、是否在 [nix](https://nixos.org/) 外壳，并且易于扩展.
- [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一个 [Powerline](https://github.com/powerline/powerline) 用 Haskell 编写的克隆. 它比原始实现要快得多，并且使 shell 的响应速度明显更快.
- [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 用 Ruby 编写，使用电力线字符来模拟具有有用信息的药丸.
- [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell)  - 漂亮而有用的 Bash、ZSH、Fish 和 tcsh 提示生成器. 包括 `git`、`svn`、`fossil` 和 `hg` 装饰、Python virtualenv 信息和最后一个命令退出状态.
- [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一个 [powerline](https://github.com/Lokaltog/vim-powerline) - 类似于 Bash、ZSH 和 Fish 的提示. 显示有关 git/svn/hg/fossil 分支的重要详细信息，并且易于自定义/扩展.
- [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
- [powerline](https://github.com/carlcarl/powerline-zsh) - 一个 [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash) . 显示 virtualenv、`git` 状态信息和最后一个命令运行的退出代码.
- [powermore](https://github.com/primejade/powermore-zsh) - 分叉自 [powerless](https://github.com/martinrotter/powerless) . 显示 `git` 状态和当前目录的简单提示.
- [powerzeesh](https://github.com/sevaho/Powerzeesh)  - 基于电力线的 ZSH 主题. 它旨在简化，仅在相关时显示信息，并针对速度和外观进行了优化. 灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
- [pre](https://github.com/leandromatos/pre-theme) - Sublime Text、Terminal、iTerm 2 和 ZSH 的主题集合.
- [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 为黑暗终端主题优化的主题.
- [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - oh-my-zsh 的云提示的 Prezto 端口.
- [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda 主题（用于 prezto）.
- [prezto_powerline](https://github.com/davidjrice/prezto_powerline)  - prezto 的电力线. 显示 git 信息，RVM 版本.
- [probe](https://github.com/probe2k/probe_zsh) - 包括 `git` 状态装饰.
- [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 一个相当重量级的 ZSH 提示，基于流行的同名 `vim` 插件的电力线字体，适用于深色背景.
- [prompt](https://github.com/nathanblair/prompt)  - 在 `sh`、`dash`、`ash`、`zsh` 和 `pwsh` 中一致的轻量级提示. 包括 `git` 状态装饰.
- [prompt_j2](https://github.com/malinoskj2/prompt_j2) - 具有动态退出状态指示器，可以动态更改为两行以显示上下文.
- [promptor](https://github.com/MickaelBlet/Promptor)  - 受电力线启发. 包括 `git` 状态、用户名、主机名、工作目录和时间的装饰器.
- [promptus](https://github.com/willeccles/promptus)  - 简单、简约且可配置的 C 语言 shell 提示程序，可用于使您的提示在任何 shell 上都相同. 包括退出代码和工作目录装饰.
- [pronto](https://github.com/jthat/zsh-pronto) - 带有“git”装饰和时间信息的简单快速的主题.
- [ps1.py](https://github.com/jwodder/ps1.py) - 具有 `git` 状态、截断目录、`chroot` 和 `virtualenv` 提示装饰.
- [pskfyi](https://github.com/pskfyi/zsh-theme) - 基于 [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda) . 以 ubuntu 为主题，但很容易调整.
- [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
- [pure-agnoster](https://github.com/yourfin/pure-agnoster) - 混搭 [pure](https://github.com/sindresorhus/pure) 和 [agnoster](https://gist.github.com/3712874). Has `git` decorations 和 works well with both dark 和 light terminal backgrounds.
- [pure](https://github.com/sindresorhus/pure)  - 一个漂亮、最小和快速的 ZSH 提示. 包括 `git` 状态装饰，如果最后一个命令失败，提示变为红色，在远程会话或容器中时的用户名和主机装饰，以及进程运行时的当前文件夹和命令.
- [purify (banminkyoz)](https://github.com/banminkyoz/purify) - 一个简单、快速和酷炫的提示.
- [purify (kyoz)](https://github.com/kyoz/purify)  - 干净而充满活力的主题，最适合深色背景. 包括 `git` 状态装饰.
- [purity](https://github.com/petermbenjamin/purity) - 灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和 [pure](https://github.com/sindresorhus/pure) 迅速的.
- [purs](https://github.com/xcambar/purs) - 快速 [pure](https://github.com/sindresorhus/pure)-灵感提示写在 [Rust](https://www.rust-lang.org/).
- [pustelto](https://github.com/Pustelto/shell_theme) - 色彩缤纷的主题灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题，包括 `git` 装饰.
- [pyhack](https://github.com/williamcanin/pyhack)  - 适用于深色终端主题. 显示 Python 版本、Python 包版本 (pyproject.toml) 和 `git` 当前分支信息.
- [qi3ber2](https://github.com/nichus/qi3ber2)  - 一个黑暗的多线主题. 包括`git`，最后一个命令装饰器的平均负载和退出代码.
- [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括 `git` 信息. 主题 repo 包括 iTerm 2 和终端颜色设置.
- [quewui](https://github.com/kauefontes/oh-my-quewui)  - 针对深色终端主题优化的简单干净的主题. 包括当前时间、用户、目录和 `git` 状态的装饰.
- [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 具有电池状态、`git/hg` 状态、时间、kubernetes 上下文和命名空间、最后一个命令的非零退出代码和日期装饰的变体. 需要电力线字体.
- [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于 af-magic 和 posh-git.
- [radium](https://github.com/dimitardimitrov/radium) - 专为黑暗终端设计，（与 [Solarized](https://github.com/altercation/solarized) iTerm 2 主题）（prezto）.
- [radius](https://github.com/erikcc02/radius-zsh-theme) - 包括 `git` 状态、用户名、主机名和目录装饰，以及 [desk](https://github.com/jamesob/desk) 支持.
- [rafiki](https://github.com/akabiru/rafiki-zsh) - 将表情符号添加到您的 ZSH 终端.
- [ramiel](https://github.com/aknackd/zsh-themes) - 叉子 [node](https://github.com/skuridin/oh-my-zsh-node-theme).
- [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
- [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - 随机表情符号.
- [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - 添加 [zoxide](https://github.com/ajeetdsouza/zoxide) 支持 [ranger](https://github.com/ranger/ranger) 控制台文件管理器.
- [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - 包括`git`、python、时间、当前主机和路径装饰.
- [raytek](https://github.com/Raytek/raytek-zsh-theme) - 带有“git”状态装饰的简单而多彩的主题.
- [raz](https://github.com/razman786/ohmyzsh-theme-raz) - 最小提示，包括 `git` 状态装饰.
- [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的 ZSH 主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和solarized终端进行了优化. 需要与电力线兼容的字体.
- [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - 针对日晒终端配色方案进行了优化，包括 `git` 状态装饰.
- [redline](https://github.com/DrissTM/redline.zsh-theme)  - 极简主义主题. 包括 `git` 状态、时间、用户.
- [refpx](https://github.com/refpx/refpx-zsh-theme) - Includes `git` status, last command status, user@hostname and directory decorations.
- [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - 使用颜色编码的状态装饰将大量信息压缩到提示中.
- [rei (arturoalviar)](https://github.com/arturoalviar/rei-zsh-theme) - 一个简单的主题，第一个字符零（rei），数字 0.包括 `git` 状态装饰.
- [rei (eilaluth)](https://github.com/Eilaluth/rei/) - 带有当前目录和 `git` 状态装饰的简约主题.
- [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) 终端主题.
- [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ，使用表情符号来跟踪 `git` 上下文. 仅适用于 [Prezto](https://github.com/sorin-ionescu/prezto).
- [repo](https://github.com/gkide/zsh-repo-theme) - 显示详细的 `git` 状态信息
- [rho](https://github.com/andrejreznik/rho-zsh-theme) - 极简主义主题.
- [ribbon](https://github.com/pyjamafish/ribbon-prompt)  - 让人想起电力线. 包括 Python `virtualenv` 装饰器.
- [risbow](https://github.com/waddupp00/risbow) - 一个 [risto](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/risto.zsh-theme) 启发了 ZSH 主题，具有类似彩虹效果的 lolcat.
- [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
- [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - 基于来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
- [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - 用输出装饰 `robbyrussell` 主题以指示 **WIP** 提交.
- [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 在提示中带有完整路径.
- [robbyrussell-plus](https://github.com/jackjyq/robbyrussell-plus-zsh-theme) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), 添加主机名装饰器.
- [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - 极简主题，包括 `git` 和 `hg` 状态装饰.
- [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - 一个黑暗的主题.
- [rounded](https://github.com/daniilty/rounded-zsh-theme) - 包括当前目录和 `git` 状态装饰.
- [roundy](https://github.com/nullxception/roundy)  - 快速、可爱和圆润的主题. 包括 `git` 装饰. 需要 nerd 字体和支持 unicode 的终端应用程序.
- [roz](https://github.com/rozNum/roz-zsh-theme)  - 极简主义者. 包括 `git` 状态装饰，最好在较暗的背景上使用.
- [rs](https://github.com/rogeliosamuel621/rs-zsh-theme)  - 包括 `git` 装饰. 需要支持 unicode 的终端.
- [rufus](https://github.com/runarsf/rufus-zsh-theme) - 针对深色背景进行了优化.
- [rummik](https://github.com/rummik/zsh-theme)  - @rummik 的主题. 支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), 和 `git` 提示中的状态信息.
- [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto) . 包括 `git` 状态装饰.
- [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 色彩丰富的主题，包括 `git` 装饰和当前目录.
- [rzh](https://github.com/patwhatev/rzh) - 带有 `git` 状态的主题由表情符号指示.
- [s1ck94](https://github.com/zimfw/s1ck94)  - S1cK94 的（第一次弃用，现已灭绝）最小提示的分支. 显示用户是否为 root、后台作业状态、vi 模式、最后一个命令的退出状态和 `git` 状态装饰.
- [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
- [samshell](https://github.com/samuelb/samshell) - 带有 `git`、kubernetes 和 python virtualenv 装饰的极简 ZSH 主题.
- [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - 包括 `git` 状态装饰，适用于深色终端背景.
- [saturn](https://github.com/gantoreno/saturn-prompt) - 为热爱空间并希望在终端上拥有一点空间的用户提供柔和简约的提示，具有酷炫的表情符号和高度可定制的提示元素（例如图标、颜色、时间格式等）.
- [schminitz-v2](https://github.com/mashdots/schminitz-v2) - 显示 `git` 状态、`user@host` 信息、最​​后一个命令的退出状态以及是否以 root 身份运行的装饰器.
- [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - 当使用 `:sh` 命令时，显示 `vim` 是否在后台运行.
- [scythe](https://github.com/kostoskistefan/scythe)  - 让人想起电力线的主题. 包括`git`，最后一个命令退出状态和目录装饰.
- [sdkman](https://github.com/matthieusb/zsh-sdkman) - 添加选项卡完成 [sdkman](https://sdkman.io/).
- [seashell](https://github.com/jottenlips/seasonal-zshthemes)  - 带有海洋灵感的表情符号装饰的最小主题. 包括 `git` 状态装饰.
- [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了许多特殊的 unicode 字符来花哨，但是如果没有很好的字体支持，它可能会导致一些问题.
- [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食者主题启发，使用颜色编码提供信息.
- [senpai](https://github.com/hiroru/senpai-zsh)  - 为 Devops 清理提示主题. 包括 `git` 状态、kubernetes 上下文、AWS 配置文件、GCP 项目和 Azure 活动云的装饰器.
- [sepshell](https://github.com/sepehr/sepshell) - 基于丢失的旧 taybalt 主题的干净和最小的 ZSH 主题，具有 `git` 平分/合并/变基模式和可配置的提示符号.
- [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和 `git` 状态装饰.
- [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 oh-my-zsh 兼容主题，带有相应的 iTerm 2 配色方案.
- [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - 精益提示的演变，它本身就是对纯的重写.
- [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括 `git` 状态、目录、主机名、用户名和时间装饰.
- [shayan](https://github.com/shayanh/shayan-zsh-theme) - 带有 `git` 状态装饰的简单主题.
- [shelby](https://github.com/athul/shelby)  - 用纯“golang”编写的快速、轻量级和最小提示. 包括最后一个命令退出状态、`git` 状态和当前工作目录的装饰.
- [shellder](https://github.com/simnalamburt/shellder)  - 带有 `git` 分支装饰器的最小主题. 需要与电力线兼容的字体.
- [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（shichi/nana），数字 7.原色是红色，带有黄色调. 包括 `git` 状态装饰.
- [shiftys](https://github.com/shifty0g/shiftys-zsh-theme/) - 调整版的kali 主题.
- [shini](https://github.com/bashelled/shini)  - 一个小小的主题，只是大声喊叫. 包括目录、用户名、主机名、时间和 `git` 装饰.
- [shinkansen](https://github.com/MRZ07/shinkansen.zsh-theme)  - 一个快速、可定制且易于扩展的主题. 在活动的 virtualenv 中包含 rhw python 版本的装饰器，如果您使用的是 `chruby`，则为当前的 ruby​​ 版本，当前的 node.js 版本，当前的 java 版本，当前的 go 版本，如果使用的是 `chperl`，则为当前的 perl 版本，当前的 elixir 版本， `git` 状态、时间、当前目录、最后一条命令的退出代码和执行时间，以及可选的自定义消息. 需要与电力线兼容的字体.
- [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - 包括 `git` 状态和 `user@hostname` 装饰.
- [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - 分叉自 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) . 有 `git` 装饰.
- [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题. 包括 `git` 和 `hg` 状态装饰.
- [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - 包括 `git` 装饰.
- [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - 简单的主题，包括当前目录的装饰和 `git` 信息.
- [shtr0m](https://github.com/kyle-pollock/shtr0m) - 包括 `git` 状态装饰.
- [shuttle](https://github.com/Pandademic/Shuttle/)  - 用“golang”编写. 具有操作系统、用户、当前目录和最后一个命令运行的退出代码的装饰器.
- [siegerts](https://github.com/siegerts/zsh-theme) - 在正确的提示中包含 `git` 状态装饰.
- [silver](https://github.com/reujab/silver) - 一个跨外壳可定制的类似电力线的提示，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 更快的生锈端口 [bronze](https://github.com/reujab/bronze) . 需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
- [simpalt](https://github.com/m-lima/simpalt) - 基于 ZSH 的信息丰富的小足迹主题 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
- [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme)  - 适用于浅色和深色终端主题. 包括 `vcs`、`username` 和 `path` 装饰.
- [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - 基于极简主义主题 [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
- [simple (rkitover)](https://github.com/rkitover/sh-prompt-simple)  - 一个简单、轻量级且外观漂亮的提示，即使在 MSYS2、Cygwin 和 WSL 等非常慢的 shell 中也能快速运行. 它显示了当前环境的短名称（发行版、操作系统等）在 `git` 签出时的 `git` 分支，以及最后一个命令退出状态（绿色复选标记表示成功，红色 X 标记表示非零退出）.
- [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - 带有 `git`、`username` 和执行状态装饰的简单而简约的主题.
- [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - 极简提示，包括 `git` 状态装饰.
- [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - 最小提示，不需要特殊字体.
- [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - 受电力线启发的简单主题，带有 `git` 装饰.
- [simple-chack](https://github.com/chack93/simple-chack.zsh-theme)  - 适用于日晒终端配色方案. 包括 `git` 状态装饰.
- [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - 极简主义主题灵感来自 [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) . 包括 `git` 装饰.
- [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme)  - 极简主义主题. 包括 `git` 状态和 `user@host` 提示装饰.
- [simplezsh](https://github.com/fr0zn/simplezsh) - 带有 `git` 信息显示的最小主题.
- [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  - k-kinzal 的 sinon 主题. 包括 `git` 状态装饰.
- [sit](https://github.com/svensen/sit.zsh-theme) - 带有 `git`、命令退出状态和路径装饰的极简主义主题.
- [sixlive](https://github.com/sixlive/sixlive-zsh-theme)  - 这个主题有一个独特的目录列表. 在 `git` 项目中，目录显示范围为当前存储库根目录.
- [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9 的 ZSH 主题.
- [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Atom、Prism 和 ZSH 的主题系列灵感来自 He-Man 和宇宙大师的 Skeletor.
- [skill (asafaeirad)](https://github.com/ASafaeirad/oh-my-zsh-skill-theme) - 包括工作目录、`git` 工作分支、工作目录状态和跟踪分支状态的装饰.
- [skill (frontendmonster)](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对黑暗终端进行了优化，显示 `git` 状态装饰.
- [skull](https://github.com/tahadostifam/skull-zsh) - 包括 `git` 状态、python 虚拟环境和 ruby​​ `rvm` 状态装饰.
- [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH 主题灵感来自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
- [slick](https://github.com/nbari/slick) - 灵感来自 [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) 和 [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt) . 安装时需要`cargo`.
- [slimline](https://github.com/mengelbrecht/slimline)  - 最小、快速和优雅的 ZSH 提示. 在正确的时间显示正确的信息.
- [sm](https://github.com/blyndusk/sm-theme)  **Simplist** 和 **Minimalist** 主题，适用于您的 **favorite** 终端. 包括 `git` 状态装饰.
- [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 的变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题在 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
- [smelly](https://github.com/Vicfs/smelly-theme/) - 极简提示，包括 Python `venv` 和 `git` 状态的装饰器.
- [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 带有快乐和悲伤面孔的提示.
- [snazzy](https://github.com/Gary-Ash/SnazzyPrompt)  - 电力线式提示. 包括当前工作目录的段、最后一个命令的错误状态、`git` 状态信息、主机名和用户名. 需要`libgit2`.
- [snowflake](https://github.com/angelina-tsuboi/snowflake-zsh-theme) - 优雅、简单、整洁的 ZSH 主题，包括与深色主题相协调的美观酷炫调色板.
- [sobole](https://github.com/sobolevn/sobole-zsh-theme)  - 受老式爱好启发的简约 ZSH 主题. 没有冗长的噱头，没有表情符号，没有烦躁的微调器，也没有其他视觉噪音. 具有明暗模式.
- [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - 日晒电力线变体.
- [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - ZSH 的太阳能电力线风格主题.
- [solarizsh](https://github.com/paddykontschak/Solarizsh) - 对 robbyrussell 的 oh-my-zsh 主题进行颜色修复 [solarized](https://github.com/altercation/solarized) terminals.
- [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 带有 `git`、`nvm`、rvm/rbenv/chruby、python、`ssh` 和其他有用的状态装饰器的主题.
- [spowerline](https://mbauhardt.github.io/spowerline/) - 用 scala 编写，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline、vim powerline 和 vim 状态插件.
- [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - 包括时间、`git` 和当前目录装饰.
- [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes)  - 极简主义主题. 包括 `git`、`node` 和 `rbenv` 状态装饰.
- [ssfprompt](https://github.com/hugoh/zsh-ssfprompt)  - 简单、纤薄、快速. 包括 `ssh`、virtualenv 和 vcs 装饰.
- [staples](https://github.com/dersam/staples) - 基于局，如果通过 SSH 连接，则显示 user@host.
- [starboy](https://github.com/prdpx7/Starboy) - 一个简单的 ZSH 主题.
- [starship](https://starship.rs/) - 最小，快速，高度可定制.
- [statusline](https://github.com/el1t/statusline) - 响应式 ZSH 主题，可在您需要时提供信息片段.
- [steef (danihodovic)](https://github.com/danihodovic/steeef)  - Oh-my-zsh steeef 主题作为独立存储库. 这个 repo 背后的目的是避免在使用 steeef 主题时依赖 oh-my-zsh.  Antibody 等 ZSH 插件管理器可以使用主题，而无需使用 oh-my-zsh.
- [steef (zimfw)](https://github.com/zimfw/steeef) - 可定制的版本 [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 主题.
- [steeple](https://github.com/erwanjugand/steeple-zsh-theme) - 带有“git”状态装饰的极简主义主题.
- [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - 最小，粉彩.
- [sublime](https://github.com/pjmp/sublime) - 带有 `git` 状态装饰的崇高、干净、简约的 ZSH 主题.
- [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) 主题.
- [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme)  - 包括 `git` 状态装饰. 在深色终端背景下效果更好.
- [sulfurium](https://github.com/Sulfurium/zsh-theme) -sulfiumOS 的官方 ZSH 主题.
- [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - 如同 [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) 但包括活动的 Ruby 版本.
- [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) 主题.
- [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括 `git` 状态装饰和随附的 iTerm2 配色方案.
- [svs](https://github.com/SvS30/svs-theme) - Clean and distraction free theme with `git` status and current path decorations.
- [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 包括 `git` 状态装饰.
- [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题.
- [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - 针对深色背景优化的最小 ZSH 主题.
- [tarcadia](https://github.com/Tarcadia/tarcadia-zsh-theme) - 基于 [jonathan](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/jonathan.zsh-theme) . 包括当前目录和 `git` 状态的装饰器.
- [temeraf](https://github.com/filiptoma/temeraf-zsh) - 带有“git”状态、时间戳和最后退出状态装饰的极简主义主题.
- [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - 包括 `git` 状态装饰和 conda/virtualenv 状态.
- [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - 极简主义主题.
- [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和linuxer.
- [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于的主题 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
- [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 带有 `git` 状态的彩色主题.
- [theta-async](https://github.com/jesec/zsh_theme_theta-async) - 异步版本 [theta](https://github.com/eendroroy/theta) . 包括 vcs 状态信息.
- [theta](https://github.com/eendroroy/theta)  - 包括 `git` 和 `hg` 状态装饰. 还有 java、python、ruby、node、go 和 elixir 版本信息.
- [theto](https://github.com/heyvito/theto-zsh-theme)  - 简单的主题. 需求 [Nerd Fonts](https://nerdfonts.com/), 包括 `vi`-mode 状态和 `git` 装饰.
- [thetraveler](https://github.com/bassopenguin/thetraveler) - 受 unraveler 启发，使用符号来显示 `git` 状态.
- [thm](https://github.com/thm-unix/thm-zshtheme) - 包括 virtualenv、当前目录和 `git` 状态的装饰器.
- [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - 的最小版本 [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
- [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme)， 和 [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
- [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - 带有 `git` 状态装饰的简单主题.
- [toledo](https://github.com/mmatongo/toledo) - 带有 `git` 状态装饰的快速简约主题.
- [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - 包括时间和 `git` 状态装饰器.
- [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  - 包括`git`信息； 最好在深色背景上.
- [tq](https://github.com/kitian616/tq-zsh-theme) - 显示 `git` 状态、时间，需要电力线字体.
- [traffic](https://github.com/fcce/traffic-zsh-theme) - ZSH 的黑暗主题.
- [trajan](https://github.com/denisinla/trajan-zsh-theme) - ZSH 的黑暗主题.
- [trinity](https://github.com/de-luca/Trinity) - 一个简单的主题基于 [geometry](https://github.com/geometry-zsh/geometry) . 包括 `git` 装饰.
- [tron](https://github.com/iDoTron/tron-zsh-theme) - 包括 `git` 状态、工作目录、时间、user@host 和最后一个命令装饰的返回状态.
- [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主义主题，包括 `git` 状态、k8s 上下文和 `rvm` 状态的装饰器.
- [turs](https://github.com/eikendev/turs) - 快速，最小 [Purs](https://github.com/xcambar/purs)-启发提示.
- [tvline](https://github.com/thvitt/tvline) - 源自 [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
- [twilight](https://github.com/Henryws/twilight-prompt) - 极简主义，但包括最后一个命令退出状态、`git` 状态和`user@hostname` 装饰.
- [type0](https://github.com/MikereDD/type0_zsh-theme) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) 通过 yarisgutierrez. 包括 `git` 装饰.
- [typewritten](https://github.com/reobin/typewritten)  - 最小和信息丰富的主题，为重要的事情留下空间. 异步 `git` 装饰更新以提高速度.
- [ubunly](https://github.com/alejandromume/ubunly-zsh-theme)  - 模仿 Kali Linux 控制台. 注意 - 这个主题还重新绑定了很多键并设置了一些主题应该不理会的 ZSH 选项.
- [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符.
- [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - 模仿默认的 Ubuntu 提示符，但带有 `git` 装饰.
- [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - 最小主题，包括 `git` 状态装饰.
- [ultimate](https://github.com/b4b4r07/ultimate) - 带有 `git` 状态、vim 模式指示器和缩短路径的装饰器的极简主义主题.
- [ultimator](https://github.com/Ultimator14/ultimator-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) - 类似的主题. 包括当前目录、`user@host`、python virtualenv、后台作业、最后命令退出状态和`git`状态信息的装饰器. 需要 [zsh-git-prompt](https://github.com/Ultimator14/zsh-git-prompt) 插件和Nerdfonts.
- [unit-1](https://github.com/nerdbude/Unit-1) - 带有 ITWTB 颜色的极简主义主题.
- [vanan](https://github.com/avano/vanan-zsh-theme) - 带有“git”信息的极简主义主题，适用于黑暗终端.
- [vehemence](https://github.com/H1N1-dev/vehemence-zsh) - 包括 `pwd`、`user@host`、`tty`、时间、最后一个命令退出代码和 `git` 状态的装饰器.
- [vercel](https://github.com/vercel/zsh-theme) - 带有“git”状态装饰的极简主义主题.
- [vertepommes](https://github.com/TheRojam/vertepommes-theme)  - 基于ys. 包括 vcs 状态、用户名和当前目录装饰.
- [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 修改自 [mgutz](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/mgutz.zsh-theme) . 与 a 一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) 配色方案.
- [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - 灵感来自 VS Code [Vitesse](https://github.com/antfu/vscode-theme-vitesse) 主题. 包括 `git` 状态装饰.
- [voidy](https://github.com/rwejdling/voidy) - Borrows elements from [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) themes 和 adds the active [aws-vault](https://github.com/99designs/aws-vault) profile 在提示的右侧.
- [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme)  - 最小的主题让人想起默认的“bash”主题. 包括 `git` 装饰.
- [wade](https://github.com/wadehammes/wade.zsh-theme) - 流行的 ZSH 主题的混搭 [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme)，有一些视觉上的调整.
- [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
- [whale](https://github.com/whalesea520/whale-zsh-theme) - 鲸鱼主题的快速重新实现.
- [whales](https://github.com/lbergelson/zsh_whales_theme) - 包括 `git` 状态、java 版本、最后命令返回状态和目录的装饰器.
- [wild-cherry](https://github.com/mashaal/wild-cherry) - ZSH、iTerm 2、Sublime、Atom 和 Mou 的童话主题主题.
- [winline](https://github.com/khuei/winline) - Greg Hurrell 的异步版本 [prompt](https://github.com/wincent/wincent/blob/master/aspects/dotfiles/files/.zshrc) . 包括 `git` 状态、最后一个命令的持续时间、当前目录、嵌套 shell、根状态的装饰器.
- [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme)  - Python 用户的简单主题. 包括 virtualenv 和 `git` 状态装饰器.
- [work-line](https://github.com/afnizarnur/work-line) - 带有漂亮表情符号的主题.
- [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - 包括`git`状态装饰、工作目录、最后一个命令的退出状态和当前`virtualenv`.
- [wormwood](https://github.com/ann-kilzer/annkilzer.zsh-theme) - 包括最后一个命令退出状态、当前目录和 `git` 状态的装饰器.
- [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  - 旨在在您需要时向您展示所需信息的主题.  `wynwyn` 从默认主题 `avit` 和优秀 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
- [xavi](https://github.com/onthedock/xavi.zsh-theme) - 修改版 [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 带有 `git` 状态和当前目录的表情符号装饰的主题.
- [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - 带有 `git` 装饰的简单主题.
- [xm](https://github.com/Shiaoming/xm)  - 黑暗终端的主题. 有 `git` 装饰.
- [xor](https://github.com/xor3n/xor-zsh-theme) - 自我描述为简约和“功能差”，包括 `git` 装饰.
- [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - 基于 Jreese 主题插件的 oh-my-zsh shell 主题.
- [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme)  - 快速、简单和流线型的主题. 最适合搭配 [tmux](https://github.com/tmux/tmux/wiki) 和 [vim-airline](https://github.com/vim-airline/vim-airline).
- [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前 `git` 提交的缩短哈希和消息.
- [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)  - 带有行分隔提示的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
- [yazpt](https://github.com/jakshin/yazpt) - 一个干净、快速、美观的 ZSH 提示主题，精心整合了 Git/Subversion/TFVC 状态信息，与 Oh My Zsh 等流行的插件管理器集成，并且易于定制和扩展.
- [yechen](https://github.com/liyechen/yechen.zsh-theme) - 带有“git”状态装饰的极简主义主题.
- [yeet](https://github.com/jeetelongname/Yeet-theme) - 带有“git”状态装饰的极简提示.
- [yellow-sea-diamonds](https://github.com/jimratliff/yellow-sea-diamonds-zsh-theme) - 包括 `git` 状态、当前目录、活动 python 虚拟环境和最后一次命令运行的退出状态的装饰.
- [yindev](https://github.com/menyinch/yindev-zsh-theme)  - `gndx` 的变体. 包括 `git` 状态和当前目录的装饰.
- [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - 修改自 [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) 主题并针对深色背景进行了优化.
- [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 干净、简单、兼容和有意义的主题，适用于深色背景.
- [ys (tinyRatP)](https://github.com/tinyRatP/ys) - 变体 [ys](https://gist.github.com/ysmood/6110461).
- [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 支持使用大型集群的批处理提交系统的变体. 支持 Slurm、LSF/IBM Spectrum LSF 和 PBS.
- [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - 带有 `git` 状态信息的简单 ZSH 主题.
- [ysr](https://github.com/raykle/ysr-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) . 包括 `git` 状态装饰.
- [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - 黑暗优化的 ZSH 主题.
- [yuyuko](https://github.com/hylwxqwq/yuyuko.zsh-theme) - 叉子 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 灵感来自 [yuyuko.vim](https://github.com/hylwxqwq/yuyuko.vim).
- [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - 包括 conda 和 venv 状态.
- [yz50](https://github.com/lacanlale/yz50-zsh) - 多彩，基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) 主题. 包括 `git` 状态装饰.
- [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
- [zcraft](https://github.com/cpea2506/zcraft) - 带有“git”状态、最后一个命令退出状态和最后一个命令所用时间的极简主义主题.
- [zeit](https://github.com/zeit/zeit.zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
- [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) 以塞尔达为灵感的主题. 包括 `git` 状态装饰.
- [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - 定制版 oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) 随着善变的支持和其他变化.
- [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh) . 包括退出状态、`virtualenv`、`nvm`、`rvm` 和 `git` 状态装饰.
- [zen](https://github.com/cybardev/zen.zsh)  - `*NIX` 系统的简约主题. 包括上次命令运行的执行时间、vcs 状态信息的装饰器，
- [zero](https://github.com/arlimus/zero.zsh)  - Zero 的主题和插件. 具有浅色和深色终端背景的变体.
- [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景下效果最佳，包括 `git` 状态装饰.
- [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - 在黑暗的草地上效果更好.
- [zest](https://github.com/hash-bang/zsh-theme-zest)  - ZSH 的功能主题. 被影响 [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) 和 [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) 主题.
- [zeta](https://github.com/skylerlee/zeta-zsh-theme) - 显示用户名、`git` 状态信息、机器名称、当前工作目录和上一个命令的成功/失败状态的装饰.
- [zinc](https://gitlab.com/robobenklein/zinc) - 一个极快、纯 ZSH、混合异步电力线提示，易于扩展且极其可配置.
- [zish](https://github.com/RubixDev/zish/) - 基于 `fish` shell 的默认外观.
- [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
- [zodiac](https://github.com/adamalsen/zsh-zodiac) - 包括与当前年份对应的动物表情符号.
- [zp](https://github.com/Karitham/zp)  - 快速提示，用 `zig` 编写. 包括 `git` 状态和当前目录装饰器.
- [zprompts](https://github.com/z-shell/zprompts) - 使用原始“zsh”主题子系统的主题（提示）.
- [zqt](https://github.com/ladychili/zqt-zsh-theme) - 修改版 oh-my-zsh&#39;s [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) 主题.
- [zsh1999](https://github.com/DTan13/zsh1999) - 包括网络连接、电池和 `git` 状态装饰.
- [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline 外观 ZSH 主题，包括 `rvm` 提示、`git` 状态和分支、当前时间、用户、主机名、密码、退出状态、是否以 root 身份运行和后台作业状态.
- [zsh313](https://github.com/amirali313/zsh313-theme) - 带有 `git` 状态装饰的最小主题.
- [zshcomrade](https://github.com/landongn/zshcomrade) - 一个ZSH主题，同志！
- [zshify](https://github.com/nrjdalal/zshify)  - 一个简约的、一个命令安装来自定义您的提示. 需要 [npx](https://docs.npmjs.com/getting-started/installing-npm-packages-locally).
- [zshpower](https://github.com/snakypy/zshpower)  - 针对 python 开发人员进行了优化. 包括 `git` 和 `pyenv` 状态装饰、用户名和主机. 尝试安装其他插件和字体，因此请在安装前阅读其说明.
- [zshred](https://github.com/redxtech/zshred) - 显示当前目录、`git` 装饰、最后一个命令的退出状态和时间.
- [zskai](https://github.com/dinizgab/zskai-theme)  - 基于 Monokai 的简单主题. 包括 user@hostname、时间、`git` 状态和当前工作目录的装饰器.
- [zwsh](https://github.com/naens/zwsh) - ZSH 的 Zpm3/Wordstar 模式/主题.
- [zys](https://github.com/ZYSzys/zys-zsh-theme) - 如同 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)，旨在根据上下文披露信息，具有电力线美学.
- [zzshell](https://github.com/thezzisu/zzshell) - 受默认启发 [Oh-My-Zsh](http://ohmyz.sh/) 主题. 显示退出代码和 `git` 状态装饰. 不需要电力线字体.

## Fonts

此处列出的一些主题需要与 Powerline 兼容的字体，以下是一些：

- [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些不错的等宽图标.
- [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - 一个漂亮的等宽字体，用 Font-Awesome、Octoicons 和 Powerline-Glyphs 修补.
- [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与电力线兼容的字体.
- [Hack](https://sourcefoundry.org/hack/) - 另一种专为源代码设计的兼容电力线的字体.
- [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono)  - 专为代码设计的字体系列. 它提供等宽字体和比例字体，并包括电力线字形.
- [Iosevka](https://github.com/be5invis/Iosevka)  - 编码器的字体，由代码构建. 高度可定制.
- [Monoid](https://larsenwork.com/monoid/) - Monoid 可定制和优化，即使在低分辨率显示器上也能以 15 像素行高的位图锐度进行编码.
- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)  - 收集超过 20 种修补字体（超过 2,000 种变体）和 FontForge 字体修补程序 python 脚本，适用于 Powerline、Font Awesome、Octicons、Devions 和 Vim Devicons. 包括：Droid Sans、Meslo、源代码、AnonymousPro、Hack、ProFont、Inconsolata 等等.
- [Powerline patched font collection](https://github.com/powerline/fonts) - 十几种字体的集合，经过修补，包括电力线字形.
- [Terminus](http://files.ax86.net/terminus-ttf/) - 包含电力线字形的 Terminus 的 TTF 版本.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

这些插件中的大多数都可以通过将 `antigen bundle githubuser/reponame` 添加到您的 .zshrc 文件中来安装.  Antigen 将在您下次启动 `zsh` 时自动为您处理克隆插件. 您还可以使用“antigen bundle githubuser/reponame”将该插件添加到正在运行的 ZSH 中进行测试，然后再将其添加到您的“.zshrc”中.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.克隆新插件到`.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3.打开一个新的ZSH终端窗口或标签

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd ~/.oh-my-zsh/custom/plugins`
2.`git clone repo`
3. 将 repo 添加到您的插件列表

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. 将插件克隆到您的 prezto 模块目录中
2. 将插件添加到您的 `.zpreztorc` 文件中
3.打开一个新的终端窗口或标签

### [Zgen](https://github.com/tarjoilija/zgen)

 Zgen 没有得到积极维护. 考虑切换到 [Zgenom](https://github.com/jandamm/zgenom) 叉子，也就是.

### [Zgenom](https://github.com/jandamm/zgenom)

这些插件中的大多数都可以通过将 `zgenom load githubuser/reponame` 添加到您的 .zshrc 文件中来安装，这与您正在执行其他 `zgenom load` 调用的功能相同.

当您执行 `zgenom save` 时，Zgenom 将自动为您克隆插件存储库.

### [zplug](https://github.com/zplug/zplug)

这些插件中的大多数都可以通过将 `zplug &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

### [zpm](https://github.com/zpm-zsh/zpm)

这些插件中的大多数可以通过将 `zpm load &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

## Writing New Plugins and Themes

我已经记录了一些关于编写新插件和主题的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins_and_Themes.md).

还有更详细 [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

- [ShellSpec](https://github.com/shellspec/shellspec) - 用于 dash、bash、ksh、ZSH 和所有 POSIX shell 的全功能 BDD 单元测试框架.
- [shtab](https://github.com/iterative/shtab) - 为 Python CLI 应用程序自动生成 shell 选项卡补全脚本，支持 `zsh`、`bash` 和 `tcsh`.
- [zsh-bench](https://github.com/romkatv/zsh-bench)  - 交互式 ZSH 的基准. 它测量交互式“zsh”的用户可见延迟：输入延迟、命令延迟等
- [zshdb](https://github.com/rocky/zshdb) - ZSH 调试器.
- [zshelldoc](https://github.com/zdharma-continuum/zshelldoc)  - 用于 shell 脚本的 Doxygen. 解析 ZSH 和 Bash 脚本，输出带有函数列表、调用树、导出变量列表等的 Asciidoc 文档.
- [zunit](https://github.com/zunit-zsh/zunit) - 一个强大的 ZSH 单元测试框架.

### Other Useful Lists

- [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精选的工具、资源和工作流程技巧列表，打造出色的开发环境
- [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - 精选的开源系统管理员资源列表
- [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - CLI 爱好者的精选列表.

在以下位置查找其他有用的 awesome-* 列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- 这 [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 是不可或缺的.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) 是一个很棒的教程，它建立在基础之上，向您展示 ZSH 的高级用法、自定义和实际示例.
