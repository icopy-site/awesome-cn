<div class="github-widget" data-repo="unixorn/awesome-zsh-plugins"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![CircleCI](https://circleci.com/gh/unixorn/awesome-zsh-plugins.svg?style=shield)](https://circleci.com/gh/unixorn/awesome-zsh-plugins)
[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/gpa.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![Issue Count](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/master.svg)](https://github.com/unixorn/awesome-zsh-plugins)

ZSH框架，插件，教程和主题的集合受到那里各种出色列表列表的启发.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) 在捐款之前.*

## Frameworks

这些框架使自定义ZSH设置更加容易.

[zdharma](https://github.com/zdharma) 在以下位置收集了各种框架的一些有趣的性能时序比较 [zdharma/pm-perf-test](https://github.com/zdharma/pm-perf-test).

### [alf](https://github.com/psyrendust/alf)

 ** Alf **是针对ZSH的超快速且可配置的框架；  它以Prezto和Antigen为原型，同时在后台使用Oh-My-Zsh.  并提供标准的默认值，别名，功能，自动完成，自动更新以及可安装的提示主题和插件.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 ** ansible-role-zsh **是零知识安装的ansible角色.  它使用抗原来管理束和oh-my-zsh.  可以有条件地装入束.  默认情况下，它包括powerlevel9k主题，自动建议，语法突出显示和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) 和 [fzf-marks](https://github.com/urbainvaes/fzf-marks) .  完全可定制.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

 ** Ant-zsh **是一个微型轻巧的ZSH配置环境，可满足特殊的自定义需求.  它包括插件，主题和基本的便捷设置.

### [antibody](https://github.com/getantibody/antibody)

 **抗体**一种更快更简单的用Golang编写的抗原.  有关更多详细信息，请访问 [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

 ** antigen-hs **是抗原的替代品，在启动外壳时优化了抗原以降低系统开销.  它将自动为您克隆插件.

### [antigen](https://github.com/zsh-users/antigen)

 ** Antigen **是一小组函数，可帮助您轻松管理称为捆绑包的Shell（ZSH）插件.  这个概念与典型的vim + pathogen设置中的bundle几乎相同.  抗原是ZSH，Vundle是vim.  Antigen可以加载oh-my-zsh主题和插件，并会自动为您克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

 ** Ax-ZSH **是用于ZSH的模块化配置系统.  它提供了合理的默认值，并且可以通过插件扩展.

### [dotzsh](https://github.com/dotphiles/dotzsh)

 ** Dotzsh **致力于成为平台和版本无关的平台.  在旧版本的ZSH上运行时，某些功能可能会丢失，但是它应彻底降级，并允许您在不同操作系统的多台计算机上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

 **新鲜**是将其他人的外壳配置（别名，功能等）源到您自己的配置文件中的工具.  我们还支持ackrc和gitconfig等文件.  将其视为点文件的捆绑器.

### [oh-my-zsh](https://ohmyz.sh/)

 ** oh-my-zsh **是一个社区驱动的框架，用于管理您的ZSH配置.  包括120多个可选插件（rails，git，macOS，hub，capistrano，brew，ant，macports等），超过120个主题，为您的早晨增光添彩，以及一个自动更新工具，可轻松掌握最新信息来自社区的更新.

### [prezto](https://github.com/sorin-ionescu/prezto)

 ** Prezto **通过合理的默认值，别名，功能，自动完成和提示主题丰富了ZSH命令行界面环境.  有一些prezto专用插件 [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

** Pumice **是ZSH的轻量级插件管理器.

### [sheldon](https://github.com/rossmacarthur/sheldon)

快速，可配置的Shell插件管理器.

*可以管理
  *任何`git`仓库.
    *分支/标记/提交支持.
    *对GitHub存储库的额外支持.
    *对Gists的额外支持.
  *任意远程文件，只需指定URL.
  *本地插件，只需指定目录路径.
*高度可配置的安装方法，使用 [handlebars](http://handlebarsjs.com/) 模板化.
*超快速并行安装.
*使用配置文件 [TOML](https://github.com/toml-lang/toml) 句法.
*使用锁定文件可以更快地加载插件.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

** Toasty **是一个ZSH框架，旨在促进管理而不是命令管理.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack是一个基本的快速最小ZSH插件加载器.

### [zeesh](https://github.com/zeekay/zeesh)

 ** Zeesh **是跨平台的ZSH框架.  它类似于但不兼容， [oh-my-zsh](http://ohmyz.sh/) .  它具有模块化的插件架构，使其易于扩展.  它具有丰富的默认设置，但设计得尽可能轻巧.

### [zgem](https://github.com/qoomon/zgem)

** Zgem **是ZSH的插件管理器，支持从git，http和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 ** Zgen **是受Antigen启发的ZSH轻量级插件管理器.  目标是在启动外壳程序时将开销降至最低，因为没人喜欢等待.

 为此，`zgen`会生成一个静态的`init.zsh`文件，该文件除了提供插件并将其附加到`fpath`之外什么也不做.  这样就不必执行耗时的逻辑（插件检查，更新等），从而将启动时间减至最少.  缺点是，每当更新.zshrc时，都必须使用zgen reset手动刷新初始化脚本.  可以装 [oh-my-zsh](http://ohmyz.sh/)兼容的插件和主题，并将它们添加到插件列表时会自动为您克隆它们.

### [zilsh](https://github.com/zilsh/zilsh)

** zilsh **是一个ZSH配置系统，旨在吸引更多高级用户，并采用vim病原体的简单方法.

### [zim](https://github.com/zimfw/zimfw)

** Zim **是具有超凡脱俗的速度和模块化扩展的ZSH配置框架.

### [Zinit](https://github.com/zdharma/zinit)

** Zinit **是创新产品，目前 [fastest](https://github.com/zdharma/pm-perf-test) 插件管理器，支持：

- [Turbo mode](http://zdharma.org/zinit/wiki/INTRODUCTION/#turbo_mode_zsh_62_53)  – ** 80％**的Zsh启动速度！  例如：而不是200毫秒，而是40毫秒！，
-报告（来自插件加载-插件不再是黑匣子！），
-完成管理，
-片段（通过URL下载的常规文件，例如：脚本），并通过它们哦我的Zsh和Prezto插件支持（→低开销），
-附件（Zinit [extensions](https://github.com/zinit-zsh)),
-插件卸载（例如：动态主题切换），
-`bindkey`捕获和重新映射，
-包装
-干净的小路，
- [services](https://github.com/zservices),
-以及来自 [Zsh Plugin Standard](http://zdharma.org/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html) – Zinit是该标准的参考实现.

您可以使用 [zinit-console](https://github.com/zinit-zsh/zinit-console) 查看和更改ZSH会话的状态，以及从磁盘中删除插件和片段.

该项目非常活跃–当前&gt; 2000次提交.

### [zit](https://github.com/m45t3r/zit)

 ** zit **是ZSH的插件管理器.  它是最小的，因为它实现了成为插件管理器的最低要求：它允许用户从Git存储库（仅Git存储库，其名称为何）安装插件，源插件并更新它们.  它没有实现一些高级功能，例如清除已删除的插件，自动编译已安装的插件，oh-my-zsh / prezto /其他ZSH框架的别名，​​构建二进制文件，PATH操作等.

### [zoppo](https://github.com/zoppo/zoppo)

 ** Zoppo **是ZSH的残缺配置框架.  就像一句意大利谚语所说：“ chi va con lo zoppo，impara是zoppicare”，我们意识到自己正带着a子走路，现在自己会变得残废.

### [zpacker](https://github.com/happyslowly/zpacker)

** Zpacker **是轻量级的ZSH插件和主题管理框架.

### [zplug](https://github.com/zplug/zplug)

**：芙蓉：Zplug **是下一代ZSH插件管理器.

-可以管理一切
  -上的Zsh插件/ UNIX命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  -要点文件（[gist.github.com](https://gist.github.com/discover))
  -外部管理的插件，例如 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) 插件/主题
  -二进制文物 [GitHub Releases](https://help.github.com/articles/about-releases/)
  -本地插件
  -等等（您可以添加 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
-超快速并行安装/更新
-支持延迟加载
-分支/标记/提交支持
-更新后，加载后挂钩
-包之间的依赖关系
-不像 [antigen](https://github.com/zsh-users/antigen)，无需ZSH插件文件（`* .plugin.zsh`）
-互动界面（[fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
-减少缓存的机制 [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

** zpm **（ZSH插件管理器）是用于 [ZSH](http://www.zsh.org/)  谁结合了命令式和声明式方法.  第一次运行时，zpm将执行复杂的逻辑并生成缓存，此后将仅使用缓存，因此它使该框架变得非常快.

*最快的插件管理器（真的，第一次运行后，根本不会使用zpm）
*支持异步加载
*软件包之间的依赖关系
* zpm在Linux，macOS，FreeBSD和Android上运行.
* zpm插件与 [oh-my-zsh](http://ohmyz.sh/).

### [ZR](https://github.com/jedahan/zr)

** ZR **是用Rust编写的快速，简单的ZSH插件管理器，可通过`cargo install zr`轻松安装.

### [zshing](https://github.com/zakariaGatter/zshing)

** zshing **是类似于Vundle / Vim的ZSH插件管理器，可让您...

*在`.zshrc`中跟踪并配置您的插件
*安装ZSH插件
*更新ZSH插件
*按名称搜索所有可用的ZSH插件
*清理未使用的插件
*在单个命令中运行上述操作*
*管理已安装插件的__Source插件__

### [ztanesh](https://github.com/miohtama/ztanesh)

** Ztanesh **旨在通过ztanesh项目提供的配置来改善您的UNIX命令行体验和生产力：这些工具将使您的Shell更强大且更易于使用.

### [zulu](https://github.com/zulu-zsh/zulu)

** Zulu **是ZSH 5+的环境管理器，旨在使您无需编写任何代码即可轻松管理shell.

*轻松管理您的Shell环境，而无需编辑文件.
*创建别名，函数和环境变量，并在下次启动Shell时将其提供给您.
*使用简单的命令从$ path，$ fpath和$ cdpath中添加和删除目录.
*轻松安装软件包，插件和主题，并立即将它们提供给您.

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) -教程结合使用 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) 使开发人员的工作效率极高.
* [https://commandlinepoweruser.com](https://commandlinepoweruser.com/) -Wes Bos的视频介绍了ZSH和oh-my-zsh.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh)  -Arch Linux的ZSH简介.  不是特定于Arch或Linux.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖了ZSH具有Bash所没有的一些功能，并使用oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) -塞思·布朗（Seth Brown）的结合ZSH的教程， [tmux](https://tmux.github.io) 和vim.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) -为oh-my-zsh初学者写了一份快速安装文档，展示了如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示，提示时语法高亮，自动提示和自定义iTerm 2主题.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) -幻灯片演示.
* [ZSH Pony](https://github.com/mika/zsh-pony) -涵盖了无需框架即可自定义ZSH的内容.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) -Christian Schneider详尽列出了ZSH技巧.

### Antigen

* [https://mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) -Michael Maclean关于从oh-my-zsh转换为抗原的文章.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) -Josh Davis对Antigen的介绍.

### Oh-My-Zsh

* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html)  -2011 ZSH降临日历的一部分.  涵盖oh-my-zsh和zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) -Mike Buss关于使用Prezto的博客文章， [Tmux](https://tmux.github.io) 和疑难解答.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) -Linh M. Tran的帖子，关于从Oh-My-Zsh过渡到Prezto.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) -Jerome Dalbert关于迁移到Prezto的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) -功能强大，功能强大的闪电般快速的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)和 [Zgen](https://github.com/tarjoilija/zgen).
* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) -将ZSH与 [zgen](https://github.com/tarjoilija/zgen) .  这包括精选的插件集合，自动配置ZSH以使用 [zgen](https://github.com/tarjoilija/zgen) 加载它们并定期自动更新自身，插件和快速入门工具包本身.

### Zinit (née zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) -：crystal_ball：很棒，可自定义的Zsh入门套件：stars :: stars：
* [zinit-configs](https://github.com/zdharma/zinit-configs) -包含Zinit调用的实际配置文件（基本上是.zshrc文件的集合）.

## Plugins

* [256color](https://github.com/chrissicool/zsh-256color)  -增强了256色的终端环境.  它查看所选择的“ TERM”环境变量，并查看是否有相应的ncurses术语，并且提供256种颜色.  结果是一个多色端子（如果有）.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) -从某些“我的鱼”主题中添加了“ theme_title_use_abbreviated_pa​​th”参数的功能.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) -提供类似于`vim`的缩写扩展功能.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) -使通话更轻松 [actiona](https://github.com/Jmgr/actiona)  命令行中的脚本.  包括标签补全.
* [alehouse](https://github.com/sticklerm3/alehouse) -包含以下别名 [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) -oh-my-zsh插件，可帮助您记住一次定义的别名.
* [allergen](https://github.com/stanislas/allergen) -与Antigen一起使用的自定义ZSH插件的集合.
* [almostontop](https://github.com/Valiev/almostontop)  -每次在shell中执行新命令之前，都会清除先前的命令输出.  受到启发 [alwaysontop](https://github.com/swirepe/alwaysontop) bash的插件.
* [ansible](https://github.com/sparsick/ansible-zsh) -的插件 [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) -带有ANSI颜色和Unicode符号的终端天气.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) -Antigen / ZSH脚本可帮助git变基.
* [antigen-git-store](https://github.com/smallhadroncollider-deprecated/antigen-git-store)  -Antigen / ZSH脚本，用于存储git当前的工作目录.  用于在两台计算机之间使用git而不强制执行任意提交.
* [anyframe](https://github.com/mollifier/anyframe) -ZSH的peco / percol / fzf包装器插件.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) -添加用于管理Apache2的别名和功能.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) -在中添加了MacBook Pro触摸屏支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup)  -在当前目录（例如您的应用程序）中检测到docker-compose.yml或Vagrantfile时，添加start，stop，up和down命令.  只需运行“ up”并获取编码！
* [artisan](https://github.com/jessarcher/zsh-artisan) -ZSH的Laravel`artisan`插件，可帮助您从项目树中的任何位置运行“ artisan”，并带有制表符完成功能！
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) -AsciiDoctor的插件.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) -的整合和完成 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持Ruby，Node.js，Elixir，Erlang等.
* [assume-role](https://github.com/weizard/assume-role)  -ZSH插件，可让您轻松承担AWS IAM角色.  包括补全.
* [async](https://github.com/mafredri/zsh-async)  -在ZSH中运行异步任务而无需任何外部工具的库.  允许您运行多个异步作业，强制执行唯一的作业（同一作业的多个实例将不会运行），刷新所有当前正在运行的作业以及创建多个工作程序（每个工作程序都有自己的工作）.
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) -基于 [Sublime](https://github.com/valentinocossar/sublime) 插件，可让您在其中启动文件或文件夹 [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
* [atom](https://github.com/kingsj/atom_plugin.zsh) -的插件 [Atom](https://atom.io) macOS上的编辑器.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) -用`colorls`自动列出目录.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh)  -自动完整单词和列表选择.  最初是y.fujii的incr-0.2.zsh <y-fujii at mimosa-pudica.net>  .
* [auto-ls](https://github.com/desyncr/auto-ls) -切换到新目录时自动执行“ ls”.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) -长时间运行的任务完成后自动发送通知.
* [autodotenv](https://github.com/nocttuam/autodotenv) -当您将cd放入包含.env文件的目录时，将提示您加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) -的扩展版本 [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) -如果目录包含`.env`文件，则在将其`cd`进入文件时将自动执行该文件.
* [autojump](https://github.com/wting/autojump)  -一个学习的cd命令-可以从命令行轻松浏览目录.  安装autojump-zsh可获得最佳效果.
* [autopair](https://github.com/hlissner/zsh-autopair)  -ZSH插件，用于自动关闭，删除和跳过匹配的定界符.  仅在ZSH 5.0.2或更高版本上测试.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)像ZSH的快速/不干扰自动提示.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) -ZSH插件可在遍历目录时自动切换python virtualenvs和pipenvs.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)  -Antigen不会像oh-my-zsh那样执行自动更新.  该插件为抗原添加了自动更新，包括抗原和您配置中加载的束.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) -oh-my-zsh不会自动更新非核心插件，这会将插件自动更新添加到oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) -基于sweharris的AWS CLI MFA插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa).
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) -适用于AWS MFA的插件.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin)  -为“ aws”命令添加了辅助功能.  包括MFA和承担角色的助手.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) -使用aws-upload提高生产力.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) -插件 [aws-vault](https://github.com/99designs/aws-vault).
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) -为版本2提供完成支持 [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) 和一些实用程序来管理AWS配置文件并在提示中显示它们.
* [background](https://github.com/zpm-zsh/background) -ZSH插件，可在后台执行功能.
* [base16](https://github.com/chriskempson/base16-shell)  -添加了脚本，以允许您更改外壳的默认ANSI颜色，但最重要的是，可以更改外壳的256色空间的颜色17到21（如果终端支持）.  使用此脚本可以保留外壳的原始明亮颜色（例如，明亮的绿色仍然是绿色等），同时为诸如 [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)  -在您的外壳中打印与棒球相关的随机“有趣的事实”.  取决于要安装的“财富”和“ cowsay”.
* [basex](https://github.com/dirkk/zsh-basex) -增加了几个 [BaseX](http://basex.org/) 别名以简化用法.
* [bash-quote](https://github.com/jtprog/bash-quote) -从Bash.im获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash)  -使ZSH更兼容Bash.  它重新定义了源命令，使其行为更像`bash`.  它还启用了“ bash”补全功能.
* [battery_state](https://github.com/Jactry/zsh_battery_state) -以正确的方式显示电池状态.
* [bd](https://github.com/Tarrasch/zsh-bd) -跳回特定目录，而不用执行cd .. / .. /...
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) -重新映射法语的ZSH`vi`模式 [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) -为“ brew”添加更多命令别名
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) -添加了辅助脚本，以允许您创建位桶PR或在当前分支中打开目录.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)的工具包，用于将密钥/凭证安全地存储在git仓库中.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) -为`git`添加了一些方便的别名.
* [branch-manager](https://github.com/elstgav/branch-manager) -用于管理`git`分支的插件.
* [brew](https://github.com/wolffaxn/brew-zsh-plugin) -的独立插件 [Homebrew](https://brew.sh/) 包管理器.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) -一个插件，可让您从命令行在浏览器中打开任何提交.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) -在命令行中切换optirun的插件.
* [calc](https://github.com/arzzen/calc.plugin.zsh) -ZSH的计算器.
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) -添加 [Can I Use...](https://caniuse.com) 对ZSH的支持.
* [careful_rm](https://github.com/MikeDacre/careful_rm) -rm的包装，添加了垃圾回收/有用的警告.
* [case](https://github.com/rtuin/zsh-case) -ZSH插件，添加了两个别名“ tolower”和“ touper”来切换输出大小写.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) -ZSH插件，用于`cd`到`git`仓库根目录.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) -当进入指定目录时，显示提醒.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) -ZSH插件，用于“ cd”到当前存储库检出的根目录.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) -如果不小心将cd存入服务器，则将ssh存入服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) -一个ZSH插件，可轻松创建命名目录-所需目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc) -用于将目录更改为在您定义的常用位置之一中找到的目录的Shell函数.
* [cdr](https://github.com/willghatch/zsh-cdr) -为ZSH轻松设置cdr.
* [change-case](https://github.com/mtxr/zsh-change-case)  -用于在命令行中的大写和小写之间快速交换的插件.  ：墨镜：
* [cheatsheet](https://github.com/0b10/cheatsheet) -插件可轻松查看，创建和编辑备忘单.
* [check-deps](https://github.com/zpm-zsh/check-deps)  -ZSH插件的帮助程序，可让他们显示如何安装所有缺少的依赖项.  如果您使用的是Debian（以及Ubuntu等衍生产品），Arch及其衍生产品，Nodejs和ZSH插件，则可以使用 [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [clean-project](https://github.com/wwilsman/zsh-clean-project)  -从项目中删除文件（默认情况下自动）.  对于防止`.DS_Store`和`Thumbs.db`文件混乱目录很有用.
* [clipboard](https://github.com/zpm-zsh/clipboard)  -添加了跨平台的帮助器功能来访问系统剪贴板.  适用于macOS，X11（和Wayland）和Cygwin.
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) -根据历史记录构建命令，并在出现提示时移动，删除，添加命令段以及使用多字查询搜索历史记录.
* [code-review](https://github.com/xorkevin/code-review-zsh) -在`git merge-base target_branch base_branch`和`target_branch`上启动`git difftool`.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) -来自 [robbyrussell/oh-my-zsh/plugins/colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) .  给`man`输出着色.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) -为“ man”页面着色.
* [colorize](https://github.com/zpm-zsh/colorize) -着色各种程序的输出.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors)  -使从CLI着色文本更加容易.  `red foo`可以正常工作.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) -ZSH的增强颜色.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) -oh-my-zsh命令未找到插件的镜像，因此您不必包括所有omz.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) -记录复杂的命令并对其进行注释.
* [command-time](https://github.com/popstas/zsh-command-time) -在ZSH和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) .  与内置的“ REPORTTIME”类似，但仅在用户+系统时间&gt; =“ REPORTTIME”时输出.
* [completion-generator](https://github.com/RobSis/zsh-completion-generator)  -该插件尝试从程序的帮助文本中读取选项列表，并自动生成完成功能.  请注意，这不会自动完成，您必须显式调用生成器以创建完成脚本.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) -一个ZSH插件，可将您的shell配置通过`ssh`复制到另一台机器上.
* [crash](https://github.com/molovo/crash) -为ZSH添加了适当的错误处理，异常和try / catch.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) -用于Wordpress的Crayon插件的ZSH语法突出显示.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) -添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 目前的比特币价格细分.
* [crystal](https://github.com/veelenga/crystal-zsh) -的插件 [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) -使用99.9％纯ZSH编写的简单http服务器.
* [declare-zsh](https://github.com/zdharma/declare-zsh) -zshrc中的Zinit命令的命令行解析器.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) -收集有用和有趣的命令，以改善工作流程和生活质量.
* [deer](https://github.com/Vifon/deer) -ZSH的文件导航器受到了很多启发 [ranger](https://ranger.github.io/).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)  -安装chrome depot_tools的简单oh-my-zsh插件.  安装此插件后，所有铬depot_tools都会自动放置在您的路径中.
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) -简化将`diff-so-fancy`项目安装到您的用户帐户中.
* [diractions](https://github.com/AdrieanKhisbe/diractions) -允许您将简短的逻辑/助记符名称映射到目录以快速访问它们或在其中执行操作.
* [dircolors-solarized](https://github.com/joel-porquet/zsh-dircolors-solarized) -Solarized dircolors插件，提供深色或浅色终端背景选项.
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) -在目录堆栈中循环.
* [directory-history](https://github.com/tymm/zsh-directory-history) -ZSH的每个目录历史记录，它以目录敏感方式实现向前/向后导航以及子字符串搜索.
* [dirrc](https://github.com/gmatheu/shell-plugins) -当出现在您cd所在目录中时，执行.dirc.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) -用于在单行上显示目录堆栈信息的插件.
* [docker-aliases](https://github.com/webyneter/docker-aliases) 日常使用的Docker别名.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在提示中显示Docker容器状态.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) -Docker帮助程序脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) -ZSH的docker-machine插件.
* [docker-run](https://github.com/rawkode/zsh-docker-run) -返回“自然”运行命令，我们将处理容器.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) -Dogification插件.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) -使用`git`使您的点文件在多台机器上保持同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) -当您通过cd进入目录时，自动切换到位于名为.pyvenv的目录中的python虚拟环境（您以前使用virtualenv程序创建过）.
* [dropbox](https://github.com/zpm-zsh/dropbox) -ZSH的Dropbox插件，提供`dropbox-cli`和`dropbox-uploader`命令.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) -随机沙丘报价生成器插件.
* [dwim](https://github.com/oknowton/zsh-dwim)  -zsh-dwim尝试预测下一步将要做什么.  它提供了一个键绑定（control-u），它将用您接下来要运行的命令替换当前（或上一个）命令行.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) -列出EC2实例和`ssh`登录到实例.
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) -添加合理，复杂的命令行编辑（例如，增量历史记录_word_完成）.
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) -添加了Elixir，IEX，Mix，Kiex和Phoenix的快捷方式.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) -：scream：在命令行上完成表情符号.
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) -在方便的变量中向您的环境添加许多ascii艺术表情符号.
* [enhancd](https://github.com/b4b4r07/enhancd) -提供增强的cd命令的简单工具.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) -双击“`”时，快速插入转义的反引号.
* [evalcache](https://github.com/mroth/evalcache) -缓存二进制初始化命令的输出，以帮助缩短Shell启动时间.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) -扩展ZLE vi命令以远程访问vim和nvim编辑器的命名寄存器，以及系统选择和剪贴板.
* [exa](https://github.com/DarrinTisdale/zsh-aliases-exa) -启用多个别名扩展 [exa](https://the.exa.website)，是`ls`的现代替代品.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) -的插件 [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) -用空格扩展特定的别名.
* [explain-shell](https://github.com/gmatheu/shell-plugins) -在打开命令 [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) -通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) -细分版本中的版本 [oh-my-zsh](http://ohmyz.sh/) 因此，其他框架的用户不必导入所有oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  -帮助记住您定义和忘记的别名.  移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) -优化和改进的“ zsh-users / zsh-syntax-highlighting”-更好的响应时间，可切换的突出主题.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) -快速跳转到您喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) -ZSH的Unicode符号.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) -在提示中添加一个指示器，表明您位于带有firebase.json文件的目录中（又名“ firebase项目”）.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) -在Firebase项目目录或子目录中时，显示当前的工作项目或项目别名.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) -启用在ZSH中识别Apple键盘的小键盘按键.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) -这个插件可以在TYPO3 Flow发行版的每个子目录中使用`flow`命令.
* [forgit](https://github.com/wfxr/forgit) -利用模糊查找器的`git`实用工具 [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) -ZSH高阶功能.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) -ZSH插件，用于模糊搜索文件并立即在匹配的行上打开匹配的文件.
* [fz](https://github.com/changyuheng/fz) -无缝添加模糊搜索到 [z](https://github.com/rupa/z)的标签补全，可让您轻松地在历史目录之间跳转.
* [fzf (wyntau)](https://github.com/wyntau/fzf-zsh) -包装 [fzf](https://github.com/junegunn/fzf) 与ZSH一起使用.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) -整合 [fzf](https://github.com/junegunn/fzf) 和 [fasd](https://github.com/clvv/fasd) -用fzf的模糊搜索完成`z`的制表符！
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) -插件具有很酷的搜索键绑定功能 [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat) .  在子目录的本地树中搜索文件.
* [fzf-git](https://github.com/hschne/fzf-git) -使用添加漂亮的`git`补全 [fzf](https://github.com/junegunn/fzf).
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) -使用模糊查找器在bash和zsh中创建，导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) -为添加了一些ZLE小部件 [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) -将* z *插件和* fzf *组合在一起，使您可以在命令行的任何位置轻松浏览最近使用的目录.
* [fzy](https://github.com/aperezdc/zsh-fzy) -使用的插件 [fzy](https://github.com/jhawthorn/fzy) 用于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) -轻松选择Google Cloud Projects.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH的插件.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry)  日期时间插件.  在提示中显示日期时间（`date` Unix命令）.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 插件提醒您补水.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 插件以显示当前文件夹的npm软件包版本.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) 当存在`.rs`或`Cargo.toml`时显示当前文件夹的Rust版本的插件.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) -用于从中快速下载jQuery库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) -让您使用 [zeus](https://github.com/burke/zeus) 使用常规的rails命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) -使用gimme管理Go安装.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) -轻松地将上游遥控器添加到您的`git`分支中.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) -细分版本中的版本 [oh-my-zsh](http://ohmyz.sh/) 因此，其他框架的用户不必导入所有oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) -为常用的git命令的组合创建很多有用的别名.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) -增强`git`补全功能，以将远程控制补全中的内容（例如来自`git clone`中的内容）包括在剪贴板中.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) -额外的`git`帮助程序脚本打包为插件.
* [git-ignore](https://github.com/laggardkernel/git-ignore)  -从gitignore.io“离线”生成`.gitignore`文件.  `fzf`，完成，预览已集成.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) -增加了在GitHub当前分支中打开文件夹的功能.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) -为`git`添加了一些功能.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) -为`git` user.email添加提示提醒.
* [git-prune](https://github.com/Seinh/git-prune) -简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) -添加了git-squash-branch和git-remove-merged命令.
* [git-secret](https://github.com/sobolevn/git-secret) -一个bash工具，用于将您的私人数据存储在`git`存储库中.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) -添加了额外的git命令，以提高一些常用git的使用效率.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) -一个ZSH插件来同步`git`存储库并清理它们.
* [gitcd](https://github.com/viko16/gitcd.plugin.zsh) -克隆后将其复制到git工作目录.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) -更新了oh-my-zsh gitfast插件的分支.
* [gitgo](https://github.com/ltj/gitgo) -从命令行在浏览器中打开Github / Gitlab存储库（仅适用于macOS）.
* [github-issues](https://github.com/zdharma/zsh-github-issues) -在Github上订阅项目，并在外壳内（在提示符下）接收有关新问题的通知.
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) -用于创建`.gitignore`文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) -ZSH插件，用于使用生成GitHub短网址 [git.io](https://git.io).
* [gitster](https://github.com/zimfw/gitster) -shashankmehta的Zim叉子 [gitster.zsh-theme](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) -从 [original Gitster](https://github.com/robbyrussell/oh-my-zsh/wiki/External-themes#gitster).
* [gitsync](https://github.com/washtubs/gitsync) -ZSH插件可改善一个人在多台机器上同一存储库上开发的工作流程.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) -与Python的virtualenvwrapper类似地管理$ GOPATH.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) -用于安装，更新和加载goenv的插件.
* [going_places](https://github.com/or17191/going_places) -一个有助于使用，创建和维护外壳位置列表的插件.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) -在macOS上设置GPG代理以充当SSH代理时，尝试执行正确操作的插件.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) -ZSH插件，用于加密和解密文件或目录.
* [grep2awk](https://github.com/joepvd/grep2awk) -ZLE小部件，用于将“ grep”命令转换为“ awk”命令.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) -为`grunt`添加自动补全功能.
* [gsh](https://github.com/cjayross/gsh) -收集`git`的辅助函数
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) -的终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [guish](https://github.com/gcarrarom/oh-my-guish) -实用程序功能和别名的集合.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) -的包装器插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) -适用于ZSH的gvm（Go版本管理器）插件.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) -为`gvm`（Groovy enVironment Manager）提供自动补全功能.
* [hab](https://github.com/alexdesousa/hab) -如果在切换到新目录时发现文件.envrc，则自动加载OS环境变量.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) -打开终端时，随机输出黑客报价.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) -为hadoop功能添加了一些方便的别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) 项目.
* [hints](https://github.com/joepvd/zsh-hints) -在编辑缓冲区的正下方显示glob和参数标志以及其他不可完成的信息.
* [hipchat](https://github.com/robertzk/hipchat.zsh) -从外壳发送hipchat消息.
* [histdb](https://github.com/larkery/zsh-histdb) -将您的历史记录存储在SQLite数据库中.
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  -通过更多交互和多行选择菜单增强了历史记录搜索.  需要nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)  -允许您指定模式，这些模式将自动排除命令被插入到您的永久历史记录中.  对于防止机密信息特别有用.
* [history-here](https://github.com/leonjza/history-here) -绑定`^ G`可以快速切换当前shell历史记录文件的位置.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) -捕获PageUp键并使用“对话框”打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回到提示.
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) -突出显示了语法的ZSH多单词历史记录搜索器，绑定到Ctrl-R，具有高级功能（例如，将历史记录条目推到历史记录的顶部）.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)  -需要在`zsh-syntax-highlighting`之后加载，否则它们都会崩溃.  您还需要将键绑定到其功能，详细信息在README.md中.
* [history-sync](https://github.com/wulfgarpro/history-sync) -适用于GPG的Oh My Zsh插件已加密，Internet使用`git`同步了ZSH历史记录.
* [history](https://github.com/b4b4r07/zsh-history) -扩展历史记录，以便可以通过SQL查询.
* [homebrew](https://github.com/digitalraven/omz-homebrew) -插件 [homebrew](https://brew.sh).
* [hooks](https://github.com/willghatch/zsh-hooks) -添加缺少的挂钩-供插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) -使开发过程中切换到不同的`/ etc / hosts`文件更加容易.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) -一个简单的插件，用于向您的ZSH主题添加`hub` ci-status.
* [igit](https://github.com/ytakahashi/igit) -使用以下命令的交互式`git`命令 [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) -`ping`，但输出较短.
* [intellij](https://github.com/mgryszko/intellij) -将intellij书签提取为markdown格式.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) -类似于cd的类似于鱼的交互式制表符.
* [iosctl](https://github.com/obayer/iosctl) -快速访问正在运行的模拟器的应用程序，数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) -的插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) -增加了在iTerm2中设置选项卡颜色的功能，并可以基于cwd或正在执行的命令自动更改颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) -根据当前工作目录自动更改iTerm 2标签的颜色.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) -在MacbookPro TouchBar中显示iTerm2反馈（当前目录，git分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) -从命令行管理iTerm 2的配色方案.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) -设置iTerm 2标签的颜色和标题.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) -帮助下载各种iTerm2实用程序，并允许您省略整个iterm2-网站存储库的克隆或依赖于可能不同步的其他存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) -将iTerm的ZSH集成脚本打包到ZSH插件中，以避免污染您的$ HOME目录，而时间仅增加了2ms.
* [jabba](https://github.com/2m/zsh-jabba) -添加外壳集成代码和补全 [jabba](https://github.com/shyiko/jabba) Java版本管理器.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) -添加了“ setjdk”命令，因此您可以轻松地在不同版本的jdk之间切换.
* [javaVersions](https://github.com/miguefl/javaVersions) -使用单个命令在不同的Java版本之间进行切换.
* [jdk-switch](https://github.com/LockonS/jdk-switch) -仅限macOS的插件，可在jdk版本之间进行切换.
* [jenkins](https://github.com/tomplex/jenkins-zsh) -ZSH的jenkins插件，灵感来自出色的jira插件.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) -ZSH插件，用于延迟加载jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) -添加命令 [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) -从命令行创建JIRA票证.
* [jvm](https://github.com/mgryszko/jvm) -允许在macOS上选择JDK.
* [jq](https://github.com/reegnz/jq-zsh-plugin) 具有行编辑器功能的jq-repl.
* [k](https://github.com/supercrabtree/k) -具有`git`状态修饰符的ZSH的目录列表.
* [kill-node](https://github.com/vmattos/kill-node) -ZSH插件，用于谋杀`node`进程族.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) -oh-my-zsh的KitsuneBook插件.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) -适用于`kubectl`的ZSH插件，可添加当前上下文和名称空间.
* [kubecolor](https://github.com/droctothorpe/kubecolor) -简化和着色`kubectl get events -w`的输出
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) -用于管理`kubectl`的ZSH插件.
* [kubectx](https://github.com/unixorn/kubectx-zshplugin) -自动安装 [kubectx](https://github.com/ahmetb/kubectx) 和`kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) -添加 [kubernetes](https://kubernetes.io) 辅助函数和别名.
* [lando](https://github.com/JoshuaBedford/lando-zsh) -别名功能的集合，可在其中使用CLI [Lando](https://docs.lando.dev) 无需键入lando即可访问它们.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) -提供一个接口 [Laradock](http://laradock.io/)的工作区.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) -为Laravel 6添加别名.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) -添加Laravel 5、5.1、5.2和5.3的快捷方式.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) -在其中细分版本的副本 [oh-my-zsh](http://ohmyz.sh/) .  跟踪上次使用的工作目录，并自动跳入该目录以使用新的shell.
* [lazyload](https://github.com/qoomon/zsh-lazyload) -延迟加载命令和加快ZSH的启动时间.
* [lesaint-git](https://github.com/lesaint/lesaint-git) -替换与Oh-My-Zsh兼容的框架的git插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) -oh-my-zsh的Maven插件.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) -打开终端时输出随机的Linus Torvalds rant.
* [linuxbrew](https://github.com/zpm-zsh/linuxbrew) - ZSH plugin for [linuxbrew](http://linuxbrew.sh/).
* [listbox](https://github.com/gko/listbox) -Shell的列表框元素.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) -允许搜索 [Sublime Text](https://www.sublimetext.com) 项目并在Sublime中打开它们.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)  -在命令行上生成lorem ipsum文本.  从其获取数据 [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) -着色`ls`的输出.
* [lumberjack](https://github.com/molovo/lumberjack) -Lumberjack是Shell脚本的日志记录界面.
* [lux](https://github.com/pndurette/zsh-lux)  -ZSH插件可通过“ lux”命令切换macOS的亮暗模式以及其他项目和应用程序.  高度可定制：可以通过定义变量来配置包含的项目.  高度可扩展：可以通过定义功能来添加项目.  包含`macos_is_dark`帮助函数，以确定在主题中使用的macOS暗模式是否处于活动状态.
* [mac-packaging](https://github.com/Temikus/mac-packaging) -一组用于企业Mac打包的常用功能 [Munki](https://www.munki.org/munki/).
* [macos](https://github.com/joow/macos) -适用于macOS的ZSH插件.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) -使使用Docker和Magento 2变得容易.在容器上的Magento 2中，加速并简化了诸如清理缓存，安装升级，编译di等常用命令.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) -添加了`m2`函数来运行magento二进制文件，并添加了制表符补全.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) -用于模拟`...&#39;==`../ ..&#39;等的zle调整.
* [markedit](https://github.com/zakariaGatter/MarkEdit) -标记文件并使用自动补全功能对现有标记进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) -允许您标记目录，以便您直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) -oh-my-zsh maven插件的分支.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) -摘自oh-my-zsh，因此无需oh-my-zsh即可使用.
* [mfunc](https://github.com/hlohm/mfunc)  -允许您即时定义持久功能，而无需将其添加到配置文件中.  这些功能将永久可用，直到您将其删除.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) -一个ZSH插件，用于在普通模式和“ vi”模式之间切换命令行.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) -用于Monorepo管理的ZSH插件.
* [morpho](https://github.com/psprint/zsh-morpho) -用纯ZSH编写的终端屏幕保护程序，以及屏幕保护程序框架.
* [mouse-status](https://github.com/gryffyn/mouse-status) -根据状态码更改鼠标颜色，使用libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) -Metasploit处理程序插件，可轻松启动处理程序.
* [mylocation](https://github.com/fALKENdk/mylocation) -一个插件，可根据您的IP地址显示您的当前位置.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -为mysql表添加颜色.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) -添加了一些用于处理mysql的功能.
* [n](https://github.com/gretzky/n.zsh) -使用以下工具根据项目环境自动切换节点版本 [n](https://github.com/tj/n).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) -添加类似“ htop”的“ kill”，目录书签浏览器，多字增量历史记录搜索器等.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) -从模板生成文件.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) -将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) -插件，可让您在“ nix-shell”环境中将ZSH用作默认外壳.
* [nnvm](https://github.com/torifat/nnvm)  -根据`.nvmrc`自动切换节点版本.  需要 [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) -使用`nvm`为当前项目安装新版本和模块.
* [node-path](https://github.com/andyrichardson/zsh-node-path) -自动将当前目录的“ npm bin”添加到路径.
* [node](https://github.com/srijanshetty/node.plugin.zsh) -Srijan Shetty的ZSH的nodejs插件，具有对`nvm`补全进行缓存和对`nvm`的自动加载（如果存在）的功能.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) -自动将`nodenv`及其补全加载到外壳中.
* [nodenv (mattberther)](https://github.com/unixorn/awesome-zsh-plugins/blob/master/mattberther/zsh-nodenv)  -安装，更新和加载`nodenv`.  受zsh-rbenv启发.
* [nohup](https://github.com/micrenda/zsh-nohup) -按Ctrl-H在当前命令中添加nohup.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) -macOS用户知道尝试找出实际命令会刷新其版本的macOS上的DNS缓存的麻烦，并且此插件使烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) -受启发 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的界面来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) 目录中的文本文件.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) -在ZSH中提供快速的笔记编辑体验.
* [notify](https://github.com/marzocchi/zsh-notify) -ZSH插件（在macOS和Linux上），在终端以非零退出状态终止命令时或在终端应用程序处于后台（或命令终端）超过30秒完成时，会发布桌面通知标签无效）.
* [npm](https://github.com/igoradamenko/npm.插入.zsh)  -添加`npm`别名和命令完成.  基于Oh-My-Zsh [npm](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/npm) 插入.
* [npms](https://github.com/torifat/npms)  -由`fzf`支持的实用程序，用于交互使用npm脚本.  需要 [fzf](https://github.com/junegunn/fzf) 和 [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) -每当您进入包含.nvmrc文件的目录时，都会自动调用nvm use，该文件带有一个字符串，告诉nvm使用哪个节点.
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) -旨在尽可能减少键入nvm use的需求，尤其是当您经常在node.js版本之间切换并在项目中使用`.nvmrc`文件来管理项目所需的节点版本时，尤其如此.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy)  -用于延迟加载oh-my-zsh的** nvm **插件的插件.  它支持延迟加载nvm到多个二进制/入口点，默认值为nvm，node和npm.
* [nvm](https://github.com/lukechilds/zsh-nvm) -ZSH插件，用于安装，更新和加载`nvm`.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) -将您的终端变成矩阵.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) -在Jetbrains中打开/创建项目.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) -一个ZSH插件，用于从命令行打开拉取请求.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) -为常见的openshift原点（oc）操作添加一些快捷方式.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) -`git`别名.
* [operator](https://github.com/nivv/operator-theme) -简洁的主题，与Menlo for Powerline搭配使用效果最佳.
* [opp](https://github.com/hchbaw/opp.zsh) -Vim的ZSH文本对象.
* [opt-path](https://github.com/jreese/zsh-opt-path) -自动在您的$ PATH中添加〜/ opt子路径.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) -此插件添加了一些命令来维护我的macOS安装上的各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) -添加一些与macOS相关的常见别名和功能.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)  -长时间运行的命令的后台通知.  支持基本OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) -防止密码输入您的命令行历史记录.
* [pctl](https://github.com/ytet5uy4/pctl) -切换环境变量以进行代理.
* [peco-history](https://github.com/jimeh/zsh-peco-history) -按ctrl + R时，使用Peco搜索外壳历史记录.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) -延迟渗透测试仪的别名和功能.
* [percol](https://github.com/robturtle/percol.plugin.zsh) -使用以下内容以交互方式和增量方式搜索历史记录/恢复后台作业 [percol](https://github.com/mooz/percol).
* [pew](https://github.com/shosca/zsh-pew) -使用以下命令设置和管理Python virtualenvs [pew](https://github.com/berdario/pew)，当您移动目录时会自动切换virtualenvs.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) -添加实用程序功能 [PostgreSQL](https://www.postgresql.org/).
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) -使用自动在php版本之间切换 [php-version](https://github.com/wilmoore/php-version) 如果目录中存在rc文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) -插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) -自动加载 [phpenv](https://github.com/sptndc/phpenv) 及其完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) -插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) -易于将python应用程序安装到不同的Python virtualenv中，因此它们不会与系统上的任何其他python要求冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) -自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) 进入pipenv项目后激活.
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) -添加ibtool快捷方式以生成本地化的XIB文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) -Rails的ZSH插件.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) -适用于Visual Studio Code的插件，适用于macOS，Windows和Linux的文本编辑器.
* [plugin](https://github.com/darrenbutcher/plugin)  -从样板模板创建自定义的oh-my-zsh插件.  非常以oh-my-zsh为中心，生成的插件需要进行编辑才能与其他框架一起使用.
* [poetry](https://github.com/darvid/zsh-poetry) -自动激活和停用 [Poetry](https://poetry.eustace.io/)创建的python virtualenvs.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd)  -用当前工作目录创建一个全局变量.  插件已与 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) -显示可以在提示中嵌入的EOL符号.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) -添加一个变量，您可以使用该变量显示上一次命令运行的执行时间.
* [pr-git](https://github.com/zpm-zsh/pr-git) -创建带有`git`状态信息的全局变量，该状态信息可以在提示中显示.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) -设置以root身份运行时可以在自定义提示中使用的环境变量.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) -创建一个环境变量，可用于在自定义提示中显示后台作业信息.
* [pr-node](https://github.com/zpm-zsh/pr-node) -设置一个环境变量，该变量可用于在自定义提示中显示nodeJS信息.
* [pr-return](https://github.com/zpm-zsh/pr-return) -ZSH插件，显示上一次命令运行的退出状态.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode)  -在演示过程中扩展别名.  它还增加了终端窗口的对比度，以增强可见性.
* [pretty-time](https://github.com/sindresorhus/pretty-time-zsh) -将秒转换为人类可读的字符串：165392→1d 21h 56m 32s.
* [print-alias](https://github.com/brymck/print-alias) -每当您在命令行中使用别名时，将打印别名已扩展的命令.
* [printc](https://github.com/philFernandez/printc) -允许您通过简单的`printc`调用以RGB空间中的任何颜色进行打印.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)  -将敏感变量（api令牌，密码等）安全地保留为终端初始化文件的一部分.  使用gpg使用您的机密加密/解密文件.
* [project (gko)](https://github.com/gko/project) -在本地和github（私有或公共存储库）上创建node / python / ruby​​项目.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) -用于管理项目的插件.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) -用于管理代理外壳环境设置的别名.
* [proxy](https://github.com/SukkaW/zsh-proxy) -配置代理设置.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) -在ZSH中延迟加载`pyenv`的插件.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)  -延迟加载pyenv.  初始`eval“ $（pyenv init-）”`是在第一次调用`pyenv`时执行的.
* [pyenv](https://github.com/mattberther/zsh-pyenv)  -受zsh-rbenv启发.  安装，更新或加载“ pyenv”.
* [q (cal2195)](https://github.com/cal2195/q) -类似vim的宏为您的ZSH shell注册.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) -尾部/删除临时文件 [Q](https://github.com/y0ssar1an/q)，肮脏的调试工具.
* [quoter](https://github.com/pxgamer/quoter-zsh) -打开新的终端会话时显示随机报价.
* [quotify](https://github.com/damofthemoon/zsh-quotify) -在启动时显示来自我们配对的鼓舞人心的编码报价.
* [randeme](https://github.com/ex-surreal/randeme)  -为每个会话选择一个随机主题.  如果您不喜欢所选的主题，则可以运行`randeme_rm`以不再显示该主题.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) -改变你的颜色 [Razer Mouse](https://openrazer.github.io/)  根据最后执行的命令的状态.  需要 [OpenRazer](https://openrazer.github.io) linux驱动程序.
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) -oh-my-zsh的rbenv插件的更快分支.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) -基于原始的oh-my-zsh rbenv插件的变体.
* [rbenv (Meroje)](https://github.com/Meroje/zsh-rbenv) -受启发 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/)，使使用ruby rbenvs更加容易.
* [rbpi](https://github.com/kcousot/rbpi-plugin) -Raspberry Pi实用程序脚本.
* [rc-files](https://github.com/0b10/rc-files) -添加了用于编辑各种rc文件的快捷功能.
* [redis](https://github.com/zservices/redis)  -将运行`redis-server`将其指向`redis.conf`配置文件.  可以与 [zdharma/zredis](https://github.com/zdharma/zredis) 插件在外壳之间共享变量.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) -如果已删除并重新创建工作目录，则该插件将重新进入工作目录.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) -一个在每个提示上方显示提醒的插件.
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [ripz](https://github.com/jedahan/ripz)  -提醒您别名，以便您更多地使用它们.  取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo-zsh-plugin](https://github.com/shengyou/robo-zsh-plugin) -的ZSH插件 [Robo](https://robo.li/).
* [rockz](https://github.com/aperezdc/rockz) -基于VirtualZ的Lua + LuaRocks虚拟环境管理器.
* [ruby-switch](https://github.com/LockonS/ruby-switch) -切换红宝石版本并同时管理PATH变量.
* [rvm](https://github.com/johnhamelink/rvm-zsh) -启动RVM并添加用户$ PATH中可访问的rubygem二进制文件（如指南针）.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) -从最后一个`kubectl`命令开始经过一段可定义的秒数后，通过警告您所处的上下文，在运行`kubectl`时增加了安全性.
* [safe-paste](https://github.com/oz/safe-paste)  -安全粘贴插件.  见康拉德·欧文（Conrad Irwin） [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) -添加安全rm功能，以便“ rm”将文件放入操作系统的垃圾桶中，而不是将其永久删除.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) -使用多个AWS配置文件时，例如，您的阶段（开发，预生产，生产）的不同帐户可用于确定当前导出的配置文件以及令牌是否仍然有效.
* [saneopt](https://github.com/willghatch/zsh-saneopt) -按照vim明智的精神，Sane缺省使用ZSH选项.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) -在提示中显示当前的“ chroot”名称.
* [select](https://github.com/psprint/zsh-select) -具有近似匹配和uniq模式的多项搜索选择列表.
* [send](https://github.com/robertzk/send.zsh) -对git add，git commit以及git push的单一命令，可以更快地实现git工作流程.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) -添加了许多`git`别名和帮助程序shell函数.
* [setenv](https://github.com/kalpakrg/setenv) -更改目录时运行脚本.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) -插件可轻松启动python SimpleHTTPServer和SimpleHTTPSServer.
* [slugify](https://github.com/lashoun/slugify) -ZSH插件，可将文件名和目录转换为Web友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) -在chpwd之后运行`ls`和`git status`.
* [snippets](https://github.com/willghatch/zsh-snippets) -命令行摘要扩展.
* [solarized-man](https://github.com/zlsun/solarized-man) -oh-my-zsh的有色人页面插件的修改版本，已针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端中的主题.
* [ssh-connect](https://github.com/gko/ssh-connect) -一个简单的`ssh`经理.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) -`ssh`的插件.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) -打印启动外壳所需的时间.
* [stashy](https://github.com/MisterRios/stashy) -使用`git stash`简化的插件.
* [statify](https://github.com/vladmrnv/statify) -进行基本统计分析的插件.
* [sublime](https://github.com/valentinocossar/sublime) -与Oh My Zsh的官方Sublime插件相同，但是如果已经打开了一个文件，它将在当前Sublime窗口中打开文件.
* [sudo](https://github.com/hcgraf/zsh-sudo)  -oh-my-zsh的`sudo`插件，提取为独立插件.  在emacs模式或vi命令模式下按* ESC-ESC *可以在当前/上一个命令之前切换`sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) -使用ZSH的后缀别名直接在外壳中打开文件.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) -Symfony 2和3的ZSH插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) -ZSH语法使用dircolors实时突出显示.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  -在您的ZSH中添加语法突出显示.  确保加载此_before_ zsh-users / zsh-history-substring-search，否则它们都将中断.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) -ZSH插件，用于目录更改或编辑器启动，仅使用小部件进行关键操作，而无需键入命令.
* [sysadmin-util](https://github.com/skx/sysadmin-util) -史蒂夫·肯普（Steve Kemp）为系统管理员准备的工具脚本.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard)  -添加了对vi仿真键盘映射的ZLE（Zsh Line Editor）剪贴板操作的键盘绑定支持.  它可以在Linux，macOS和Android（通过Termux）下运行.
* [systemd](https://github.com/le0me55i/zsh-systemd) -为`systemd`添加了许多别名.
* [t32](https://github.com/chrissicool/zsh-t32)  -Lauterbach Trace32工具集的插件.  它会自动注册字体并设置所有必要的环境变量以运行t32工具集.
* [tab-title](https://github.com/trystan2k/zsh-tab-title)  -根据当前目录或运行过程设置终端选项卡标题.  分叉于 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) -添加带有前缀换行符的“ tailf”功能，而不是尾随换行符.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) -自动完成任务簿的任务编号.
* [terminal-app](https://github.com/the8/terminal-app.zsh) -用于与El Capitan Terminal.app新功能集成的插件.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) -一个插件，可以计算并显示通过终端运行了多少命令.
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) -添加terraform工作区进行提示.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) -为添加便利别名 [terraform](https://terraform.io/) 和帮助程序功能以在提示中添加您的Terraform工作区.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) -ZSH的地形便利功能和别名.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) -插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt)，用于 [Terraform](https://terraform.io/) 提供了额外的工具.
* [tfenv](https://github.com/CDA0/zsh-tfenv) -安装，更新和加载受启发的tfenv [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [thefuck](https://github.com/laggardkernel/thefuck) -负载 [thefuck](https://github.com/nvbn/thefuck) （用于纠正您先前命令的工具）具有缓存支持，可大大减少加载时间.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) -使用方便的功能 [theia-ide](https://github.com/theia-ide/theia).
* [timewarrior](https://github.com/svenXY/timewarrior) -插件 [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) -如果您刚刚运行的命令具有别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) -允许您设置终端窗口标题.
* [titles](https://github.com/jreese/zsh-titles) -自动的窗口和标签标题 [tmux](https://tmux.github.io) 和xterm兼容的终端.
* [tmux-fork](https://github.com/sharktamer/zsh-tmux) oh-my-zsh tmux插件的独立分支.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) -插件 [tmux](https://tmux.github.io) 在单个服务器进程上支持多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - 改名 [tmux](https://tmux.github.io) Windows自动.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) -使用简单的插件 [tmux](https://tmux.github.io) 与ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) -在运行的`vim`（或NeoVim）会话中，从相邻的`tmux`窗格中打开文件.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) -为模块化的`tmux`，ZSH和Vim / NVIM创建统一的终端标题.
* [tmux](https://github.com/zpm-zsh/tmux) -插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) -简单的ZSH插件可以进行R-EP-L tmux会话.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) -添加“ toggl-week”命令以显示跟踪的总工作时间 [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  -添加小部件以将前缀切换为命令.  绑定Alt + s可以在默认情况下以`sudo`前缀命令.
* [travis](https://github.com/denolfe/zsh-travis) -如果存在当前仓库，则打开Travis CI页面.
* [tsm](https://github.com/RobertAudi/tsm) -添加一个 [tmux](https://tmux.github.io) 会话管理器.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) -添加了适用于macOS的工具.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) -Ubuntu 16别名.
* [undollar](https://github.com/zpm-zsh/undollar) -从终端提示的开头剥离美元符号.
* [up.zsh](https://github.com/peterhurford/up.zsh) -将up命令添加到cd的多个级别上.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter)  -ZSH语法突出显示工具的插件，如果URL以“良好”状态响应，则URL变为绿色，否则为红色.  对于检查URL输入错误很有用.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) -扩展了原始的oh-my-zsh venv模块的功能.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) -的包装器插件 [vagrant](https://www.vagrantup.com/)  允许从box目录外部调用`vagrant`命令.  该插件还附带了一些额外的命令，这些命令可帮助管理多个框，以及自定义制表符完成功能.
* [vanilli.sh](https://github.com/yous/vanilli.sh) -Shell配置的轻量级起点.
* [velocity](https://github.com/rahulsalvi/velocity-python) -基于Powerline的ZSH和 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) -的超轻量级克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ;  它几乎希望您正在使用 [pyenv](https://github.com/pyenv/pyenv) （尽管您没有*拥有*），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html)，（creation）仅适用于python&gt; = 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) -提供ZSH功能，以简化使用`venv`的虚拟环境的管理.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) -添加类似`vim`的增量/减量操作.
* [vi-mode (Nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似于“ vi”的功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) -向ZSH添加更多类似于“ vi”的功能.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) -添加新的动作和文本对象，包括带引号/括弧的文本和命令.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) -添加引用或取消引用动作的操作.
* [viexchange](https://github.com/okapia/zsh-viexchange) -`vi`模式插件，可轻松在缓冲区中的两个位置之间交换文本，例如vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) -友好的“ vi”模式绑定，添加了基本的Emacs密钥，增量搜索，模式指示器等.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) -允许您执行`vim filename：123`打开带有光标在特定行的文件.
* [vimman](https://github.com/yonchu/vimman) -在ZSH中查看`vim`插件手册（帮助），例如`man`.
* [vimto](https://github.com/laurenkt/zsh-vimto) -改进的ZSH`vi`模式（bindkey -v）插件.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) -oh-my-zsh的经过修改的virtualenv ZSH插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt)  -来自上游的virtualenv插件的分支.  增加了对自定义oh-my-zsh主题中的virtualenv提示的支持.
* [virtualz](https://github.com/aperezdc/virtualz) -Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 受亚当·布雷内基（Adam Brenecki）启发的经理 [Virtualfish](https://github.com/adambrenecki/virtualfish) 为了 [Fish shell](http://fishshell.com/)，替换virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) -的oh-my-zsh插件 [virtuozzo](https://docs.virtuozzo.com/master/index.html) 裸机虚拟化系统.
* [visit](https://github.com/justinpchang/visit) -自定义插件，可实现更快的导航.
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/)，这是一款轻巧的功能齐全的macOS音频播放器，可以播放FLAC和Ogg Vorbis等多种格式.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) -macOS上的Visual Studio Code插件.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) -简单的插件，可以在系统之间轻松打开VS代码.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) -插件 [Visual Studio Code](https://code.visualstudio.com/).
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) -跟踪多少 [time](https://wakatime.com/)  您已经在终端上消费了.  具有每个项目的统计信息.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) -使用以下命令自动跟踪ZSH中的命令时间 [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) -使用 [grc](https://github.com/garabik/grc).
* [watson.zsh](https://github.com/bcho/Watson.zsh) -的插件 [watson](https://github.com/TailorDev/Watson) 时间管理系统.
* [wd](https://github.com/mfaerevaag/wd)  -Warp目录使您无需使用cd即可跳转到ZSH中的自定义目录.  为什么？  因为当经常访问该文件夹或路径较长时，`cd`似乎效率低下.
* [web-search](https://github.com/sinetoami/web-search) -添加命令以直接从CLI运行bing，google，yahoo和duckduckgo搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) -使用`git blame`突出显示文件中特定行的最后更改位置.
* [windows-title](https://github.com/mdarocha/zsh-windows-title/issues) -使用当前目录和最后运行的命令动态更新终端窗口标题.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) -在项目之间跳转的简单实用程序.
* [yadm](https://github.com/juanrgon/yadm-zsh) -如果本地yadm配置发生更改，则显示警告.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) -如果`pipenv`检测到一个目录的存在，则自动激活目录的pip环境.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) -爱德华·洛佩兹（Edouard Lopez）用于oh-my-zsh的Yeoman插件，与yeoman≥1.0版本兼容（包括选项和命令自动完成）.
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) -ZSH插件，提醒您使用定义的别名.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) -添加`yt`别名以从YouTube下载视频.
* [youtube-dl](https://github.com/joow/youtube-dl) -适用于的简单插件 [youtube-dl](https://youtube-dl.org/).
* [z-a-bin-gem-node](https://github.com/zinit-zsh/z-a-bin-gem-node) -Zinit扩展程序，无需更改$ PATH就可以公开二进制文件，可以安装Ruby gem和Node模块，并轻松公开其二进制文件，并在相关插件或代码段更新时更新gem和模块.
* [z-a-man](https://github.com/zinit-zsh/z-a-man) -Zinit扩展，可为所有插件和代码片段生成手册页.
* [z-a-patch-dl](https://github.com/zinit-zsh/z-a-patch-dl) -Zinit扩展程序，用于通过提供的“ dl”和“ patch”冰下载文件并应用补丁.
* [z-a-rust](https://github.com/zinit-zsh/z-a-rust) -Zinit扩展，可在插件目录内安装防锈和防锈包装.
* [z-a-submods](https://github.com/zinit-zsh/z-a-submods) -Zinit扩展允许在插件或代码片段中安装和管理其他子模块.
* [z-a-test](https://github.com/zinit-zsh/z-a-test) -Zinit扩展，在安装和更新插件或代码段后运行测试（例如，通过“ make test”进行测试）（如果找到了其中任何一个）.
* [z.lua](https://github.com/skywind3000/z.lua)  -命令行工具，可帮助您通过学习习惯来更快地导航.  的替代品 [z.sh](https://github.com/rupa/z) with windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than z.sh.
* [zaw](https://github.com/zsh-users/zaw) -ZSH any.el-like小部件.
* [zce](https://github.com/hchbaw/zce.zsh) -Vim的EasyMotion / Emacs的ZSH ace-jump-mode.
* [zconvey](https://github.com/zdharma/zconvey) -增加了向其他ZSH会话发送命令的功能，例如，您可以在所有活动的Z Shell会话上将其用于cd $ PWD.
* [zed](https://github.com/eendroroy/zed-zsh) -一个简单的包装 [z](https://github.com/rupa/z) 通过ZSH插件安装.
* [zeit](https://github.com/zeit/zeit.zsh-theme) -针对深色背景进行了优化，包括`git`状态信息.
* [zero](https://github.com/arlimus/zero.zsh)  -零既是插件又是主题.  有关安装详细信息，请参见github页面.
* [zflai](https://github.com/zdharma/zflai) -ZSH的快速日志记录框架.
* [zgdbm](https://github.com/zdharma/zgdbm) -将GDBM添加为插件.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) -在所有加载完成后，使compinit仅运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) -zimfw的自定义附加功能，打包到zimfw插件中.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) -使更多信息可用于ZSH主题.
* [zinit-console](https://github.com/zinit-zsh/zinit-console) –的半图形（诅咒）控制台 [zinit](#zinit) 插件管理器.
* [zjump](https://github.com/qoomon/zjump)  -简化ZSH目录导航；  跳至已访问过的父文件夹或子文件夹.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) -使用通知发送并按钟声提醒您，该命令需要很长时间（默认值：15秒）完成.
* [zredis](https://github.com/zdharma/zredis)  -增加了Redis数据库支持，并带有`database_key` &lt;-&gt;`shell_variable`绑定.  支持所有数据类型.
* [zsh-z](https://github.com/agkozak/zsh-z)  -快速跳转到“最近”访问过的目录.  “ z.sh”的本地ZSH端口-没有“ awk”，“ sed”，“ sort”或“ date”.
* [zshmarks](https://github.com/jocelynmallon/zshmarks) -Bashmarks的端口（由Todd Werth编写），这是一个简单的命令行书签插件，用于oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) -从您的项目范围加载本地`.zshrc`文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) -用于在Arch Linux上拍摄ZFS升级前/升级后快照的插件.
* [zsnapshot](https://github.com/psprint/zsnapshot) -添加了将当前ZSH状态转储到文件中的命令，以便以后通过获取快照文件进行还原.
* [ZUI](https://github.com/zdharma/zui/) -ZSH用户界面库–使用ZSH可以像CGI + DHTML一样快速进行TUI应用程序开发.

## Completions

这些插件在不添加额外功能或别名的情况下添加制表符补全.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) -扩展ZSH的\ _urls补全，从而允许它完成html页面的url.
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) -完成viasite-ansible / ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) -该插件可为 [Antibody](https://github.com/getantibody/antibody) 插件管理器.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) -根据YAML规范为Bash和ZSH生成补全
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) -完成autopkg.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) -添加了对awscli的完成支持，以管理AWS配置文件/区域并在提示中显示它们.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) -为aws_manager CLI添加补全.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) -为berkshelf添加制表符补全.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) -为`npm`更好地完成制表符.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) -添加BOSH自动补全功能.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) -用于自制服务的完成插件.
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) -为卡巴拉添加标签页补全.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) -为cabal添加自动补全功能.
* [carthage](https://github.com/squarefrog/zsh-carthage) -提供补全和别名以用于 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) -为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) -为Codeception测试框架添加命令完成.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) -显示git信息，无论您是否通过`ssh`登录，返回上一条命令的代码.
* [completions](https://github.com/zsh-users/zsh-completions) -ZSH额外完成的集合.
* [conda-zsh-completion](https://github.com/esc/conda-zsh-completion) -Conda的ZSH标签完成.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) -的制表符补全 [ctop](https://github.com/bcicen/ctop).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) -自动为DBIx :: Class :: Migration的脚本和Dancer设置环境变量.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) -命令完成 [docker-enter](https://github.com/jpetazzo/nsenter).
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) -为docker添加补全.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) -为docker和docker-compose添加完成内容.
* [dropbox](https://github.com/zpm-zsh/dropbox) -Zsh的Dropbox插件，提供`dropbox-cli`和`dropbox-uploader`命令.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) -ZSH的自动完成特效.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) -的ZSH插件 [duell](https://github.com/gameduell/duell).
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) -添加etcdctl选项卡补全.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) -的插件 [exercism.io](https://exercism.io/).
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) -定义了一个称为提取的函数，该函数提取您传递给它的存档文件，并支持多种存档文件类型.
* [extract (thetic)](https://github.com/thetic/extract) -oh-my-zsh提取插件的分支.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) -为所有添加自动补全选项 [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [gcloud-zsh-completion](https://github.com/littleq0903/gcloud-zsh-completion) -添加Google Cloud SDK的完成内容.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) -为上游缺少完成脚本的各种Gentoo工具提供ZSH完成支持.
* [git-annex-completion](https://github.com/Schnouki/git-annex-zsh-completion) -允许大多数git-annex命令使用Tab键完成.
* [git-flow-completion](https://github.com/bobthecow/git-flow-completion) -ZSH完成对git-flow的支持.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) -Bash和ZSH完成支持gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) -ZSH完成支持gradle.
* [grid5000-zsh-plugin](https://github.com/pmorillon/grid5000-zsh-plugin) -Grid 5000插件-添加主题，自动填充.
* [gulp-autocompletion](https://github.com/srijanshetty/gulp-autocompletion-zsh) -自动完成的大口吃.
* [gulp](https://github.com/akoenig/gulp.plugin.zsh) -在Z-Shell（ZSH）中自动完成gulp.js任务.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) -完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) -haxelib的完成.
* [ipfs](https://github.com/aramboi/zsh-ipfs) -完成 [Interplanetary File System](https://ipfs.io).
* [joe-completion](https://github.com/corvofeng/joe-completion) -为完成添加 [joe](https://github.com/karan/joe) gitignore编辑器.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) -jtool的ZSH完成.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) -增加了自动补全功能 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [kafka](https://github.com/Dabz/kafka-zsh-completions) -Apache的完成 [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) -完成 [keybase](https://keybase.io/docs/command_line).
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) -为添加标签补全 [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) -为添加标签补全 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [lets](https://github.com/lets-cli/lets-zsh-plugin) -为添加自动补全 [lets](https://github.com/lets-cli/lets) CLI任务运行程序.
* [MooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) -Perl模块MooseX :: App的完成生成器.
* [mx-honey](https://github.com/mukel/mx-honey) -提供完成 [mx](https://github.com/graalvm/mx) ;  用于开发Graal项目的命令行工具.  旨在改善通常的工作流程“构建单元测试基准...”，以简化发现并提供方便的别名.
* [newman](https://github.com/selop/newman-autocomplete) -提供自动补全功能 [Newman CLI](https://github.com/postmanlabs/newman).
* [nix-zsh-completions](https://github.com/spwhitt/nix-zsh-completions) -完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)和 [NixOps](https://nixos.org/nixops/).
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) -为nova提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) -对“ npm run”的自动补全支持.
* [packer](https://github.com/wakeful/zsh-packer) -为添加标签完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) -Pandoc完成插件.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) -为Parallels桌面添加补全.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) -方便回购，轻松获得 [pass](https://www.passwordstore.org/) ZSH的命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) -点子自动补全插件.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) -为最常见的pipenv命令启用别名.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) -完成“ pipenv”.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)  -如果目录中存在Pipfile，则在进入目录时会自动激活pipenv **.  包括pipenv补全.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) -为Pivotal的完成添加 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) -由以下内容提供支持的通用上下文感知ZSH完成引擎 [fzf](https://github.com/junegunn/fzf).
* [racket completion](https://github.com/racket/shell-completion) -完成 [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) -为rakefile目标添加快速制表符补全.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) -为Rancher CLI添加补全.
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) -提供自动完成功能 [Razor](https://github.com/puppetlabs/Razor).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) -Rustup的制表符补全.
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  -Salesforce CLI的ZSH命令完成.  需要 [jq](https://stedolan.github.io/jq/).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) -sfdx的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) -为添加自动填充 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) -管理`ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) -自动启动`ssh-agent`来设置和加载您想要的`ssh`连接凭据.
* [ssh](https://github.com/zpm-zsh/ssh) -为ssh添加主机完成.
* [startify](https://github.com/zdharma/zsh-startify) -ZSH的vim-startify插件.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) -添加完成冲浪.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) -Symfony 3和4命令的自动补全.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) -为添加完成 [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tmux pane words](https://gist.github.com/blueyed/6856354) -按键绑定可完成您的单词 [tmux](https://tmux.github.io) 面包.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) -增加了自动补全功能 [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) -Ubuntu标签的制表符完成.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) -为 [vertx](https://vertx.io/) 命令.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) -为“纱线添加”，“纱线移除”，“纱线升级”，“为什么纱线”和“纱线运行”添加自动填充.

## Themes

如果您正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果您正在使用 [zgen](https://github.com/tarjoilija/zgen)，使用`zgen load githubuser / reponame`将它们添加到您的`init.zsh`中.

* [0i0](https://github.com/0i0/0i0.zsh-theme) -针对黑暗的终端窗口进行了优化，使用nerdfont`git`状态装饰.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) -基于Sorin主题.
* [abbr](https://github.com/PhilsLab/abbr-zsh-theme)  -显示当前目录路径的缩写版本，显示Python virtualenv，Rust版本，`git`状态以及上一个命令的退出代码.  默认情况下，在深色背景上效果很好，但是可以轻松自定义颜色.
* [absolute](https://github.com/NelsonBrandao/absolute) -非常干净的主题，带有git状态，节点版本和最后一个命令的退出代码.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) -包括git状态修饰，AWS配置文件的名称，Azure服务主体的名称，kubernetes上下文，terraform工作区，命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) -macOS主题，需要Powerline兼容的字体.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) -的修改版 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh中的主题.
* [aftermath](https://github.com/schanur/aftermath) -在您的Shell中运行每个命令后，请获得漂亮的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) 包含在主题 [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) .  显示有关`git`状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  -使用三种异步方法来保持ZSH提示符响应，同时显示git状态和SSH连接，退出代码和vi模式的指示符，以及缩写的PROMPT_DIRTRIM样式的路径.  非常可定制的.  甚至在Cygwin和MSYS2上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) -日晒 [Agnoster](https://gist.github.com/agnoster/3712874)  带有`git`状态信息的变体.  需要unicode字体，最适合与 [solarized](https://github.com/altercation/solarized) 终奌站.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) -针对 [solarized](https://ethanschoonover.com/solarized/)  配色方案，`git`或其他VCS工具以及与unicode兼容的字体.  包括上次运行命令的状态，user @ hostname，`git`状态修饰，工作目录，是否以root用户身份运行，后台作业是否正在运行以及其他信息.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有右提示的变体.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 优化用于 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors)  终端配色方案.  包含git状态.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有时间戳和换行符的变体.
* [Agnoster](https://gist.github.com/agnoster/3712874)  -针对日晒的终端配色方案进行了优化，可显示git装饰，user @ host，工作目录，上一个命令的退出状态以及您是否以root特权运行.  需要兼容Powerline的字体.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874)，显示电池寿命，日期和时间，git状态，当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) -最适合深色终端主题，包括`git`装饰.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) -极简主义的ZSH主题，显示“ git”状态.
* [alien](https://github.com/eendroroy/alien)  -电力线式ZSH主题，显示git装饰和最后一个命令的退出代码.  比许多其他提示更快，因为它在后台进程中异步确定git装饰.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) -优化与 [solarized](http://ethanschoonover.com/solarized)  黑暗的终端.  这是 [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) -优雅而舒适的阅读主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874).
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) -在右侧提示中显示`git`信息.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) -显示git装饰，用户，主机，是否为root，活动的Python虚拟环境，当前的Ruby解释器，最后命令的视觉和数字状态，电源管理状态以及时间和日期.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)  -简约主题，无视觉干扰.  仅显示必要的信息：当前用户，主机名，工作目录，“ git”分支（如果存在）.  深色和白色端子看起来都很棒.
* [aplos](https://github.com/sunquan1991/aplos) -最小的ZSH提示，包括工作目录，git本地信息，git远程信息，时间和退出代码.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) -高度可定制，兼容和高性能的ZSH主题，它使用模块来启用功能.
* [arael](https://github.com/aknackd/zsh-themes) -前叉 [gallifrey](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie)  -Arch Linux启发了ZSH主题.  基于 [norm](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)  -Arity是一个简单的主题，旨在提高可读性并一目了然.  包括路径和`git`装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) -带有右侧`git`状态装饰的简约主题.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) -带有`git`装饰的ZSH最小主题.
* [asciigit](https://github.com/cemsbr/asciigit) -不想使用带有额外字形的字体的`git`用户的纯ASCII主题.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#theunraveler).
* [astral](https://github.com/alphabetum/astral) - Theme for dark backgrounds with zen mode.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) -基于 [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 主题.
* [async](https://github.com/mje-nz/zsh-themes) -显示当前目录，`git`状态，上一条命令的返回值（如果有错误代码），后台作业数，长时间运行的命令的执行时间，当前python virtualenv.
* [aterminal](https://github.com/guiferpa/aterminal) -在提示中显示Nodejs，NPM，Docker，Go，Python，Elixir和Ruby信息.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) -基于oh-my-zsh [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) 主题，变化不大.
* [avit-mod](https://github.com/zlsun/avit-mod) -oh-my-zsh的修改版 [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) 主题.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) -包括`git`状态修饰和当前目录.
* [bandit](https://github.com/Holger-Will/zsh_bandit) -另一个电力线变体.
* [bar](https://github.com/xp-bar/zsh-bar-theme) -包括用户名，主机，密码，git状态装饰和3个小时的饮水提醒.
* [bashi](https://github.com/eli-oat/bashi) -针对AhmetSülek的优化 [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) 主题和Pasquale D&#39;Silva [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) -的修改版 [gitster](https://github.com/zimfw/gitster) 的主题 [ZIM](https://github.com/zimfw/zimfw#installation).
* [bearable](https://github.com/JanmanX/bearable-zsh) -适用于深色终端背景.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) -受启发 [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
* [bender](https://github.com/specious/bender) -花哨的两行提示与git集成.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有unicode符号的变体.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme) .  包括`git`，`rvm`和`virtualenv`状态装饰.
* [bklyn](https://github.com/gporrata/bklyn-zsh) -的变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) 与应用自定义.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) -另一个git意识主题.
* [blazux](https://github.com/blazux/omz-theme) -包括git状态修饰和最后一个命令退出状态的笑脸/悲伤表情.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) -基于现有主题 [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)  -一个精致的主题，可以注入色彩而不会占用您的工作空间.  设计用于 [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案和 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) .  包括git状态装饰.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) -基于oh-my-zsh内置的主题 [gnzh](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gnzh.zsh-theme)  主题.  需要具有unicode支持的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme)  -最小，快速的ZSH主题，向您展示您的需求.  它由块组成：每个块都显示在一对\ [方括号\]内，您可以通过简单地创建一个函数来添加块.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) -最小主题，显示`git`信息.
* [bluelines](https://github.com/apbarrero/bluelines) -清晰的蓝色主题.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) -多行主题，最适合深色背景.
* [bougenville](https://github.com/bougenville/zsh-theme) -的变体 [dallas](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  -跨外壳可自定义的类似于电力线的提示，带有编写的图标.  需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) -使用“ audtool”在提示中显示当前歌曲.
* [bruh](https://github.com/haze/bruh) -包括`git`状态装饰.
* [brunty](https://github.com/Brunty/omz-brunty) -布鲁蒂主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) -受到 [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) -BTTF颜色主题.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh)  -受Powerline Vim插件的启发.  它旨在简化操作，仅在相关时才显示信息.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH主题，已修改为仅显示时间和目录.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) -简单，干净，漂亮的主题.
* [bureau](https://github.com/isqua/bureau)  -清晰且内容丰富的两行提示.  包括针对大型存储库优化的git status.
* [cactus](https://github.com/welksonramos/cactus) -带有`git`状态装饰的简约主题.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) -轻巧的糖果主题.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) -在提示中显示有效的Python版本和`git`装饰.
* [celestialorb](https://github.com/celestialorb/zsh-theme)  -@celestialorb创作的以电力线为主题的主题.  包括git状态修饰，Kubernetes集群信息（如果有），当前的AWS配置文件和区域以及活动的virtualenv.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  -基于sorin.  显示Java，Scala，Go，Node，Python和Ruby的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  -Oh-My-Zsh的小巧而美丽的主题，没有任何多余的东西.  包括git状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) -针对 [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
* [chi](https://github.com/akinjide/chi) -为macOS上的iTerm 2用户优化的ZSH主题.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) -显示时间戳，大换行符，git分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) -设计用于简单性和可扩展性.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) -带有`git`支持的最小，简洁主题.
* [clean (akz92)](https://github.com/akz92/clean) -极简主义的ZSH主题.
* [clean (BrandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) -的简约派 [pure](https://github.com/sindresorhus/pure) .  纯净不干净，清洁不净.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) -带有`git`，nix-shell和virtualenv状态装饰的简约主题.
* [cloudy](https://github.com/Huvik/Cloudy) -最小的ZSH多云主题.
* [clover](https://github.com/tzing/clover.zsh-theme) -受启发 [zeta](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) -的配置文件 [cmder](http://cmder.net/) 配置为通过ZSH和修改后的版本在地震模式下工作 [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) -与Cmder主题相匹配的ZSH主题，Cmder是Windows的流行终端模拟器.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) -ZSH和iTerm 2的Wes Bos的Cobalt 2主题.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) -带有`git`扩展名的Cobalt 2主题.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) -Codemachine主题.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) -受启发 [bashi](https://github.com/eli-oat/bashi)，在提示中包含猴子和`git`信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) -基于agnoster，但具有vi模式的右提示，在电源线外观中显示`--INSERT--`和`--NORMAL--`.
* [collon](https://github.com/lambdalisue/collon.zsh)  -轻量级主题，带有git状态装饰，cwd，时间，主机，最后命令的退出状态.  不需要特殊字体.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) -允许按主机提示着色，显示“ rvm”，“ virtualenv”和“ git”信息.
* [common](https://github.com/jackharrisonsherlock/common) -一个简单，干净且最小的提示，显示当前工作目录，主机名，AWS Vault角色，后台作业，当前SHA，最后一个命令的退出代码以及git分支和状态.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) -为深色背景优化的鲜艳主题.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) -具有git和npm支持的干净有效的ZSH主题.
* [cramin](https://github.com/FelipeCRamos/craminzsh) -基于github插件的最小接口支持 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) -基于Powerline Vim插件的带有可爱表情符号的macOS oh-my-zsh shell主题.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) -在深色背景上效果很好，具有`git`状态装饰.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - 相似 [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包含有效的Ruby版本.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 与 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 容器中的主题.
* [daily](https://github.com/ghlin/zsh-theme-daily) -包括`git`和`ssh`状态装饰.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) -带有`git`装饰的最小电力线主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) -内容丰富，精简，最重要的是X战警主题.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) -此版本受欢迎 [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 通过几乎完全重写的模块化和一些新功能，增强了主题.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) -Darksoku主题基于 [ys](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [delta-prompt](https://github.com/cusxio/delta-prompt) -最小的ZSH提示.
* [delta](https://github.com/dongri/delta-zsh-theme) -另一个带有内嵌`git`状态的最小主题.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) -以终端的右侧（因此为名称）为重点的主题.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) -带有自定义的LSCOLORS和LS_COLORS设置文件，可用于深色和浅色终端主题.
* [diy-ys](https://github.com/aprilnops/zsh-theme) -的变体 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
* [dmx](https://github.com/domix/dmx.zsh-theme) -针对黑暗的终端窗口进行了优化.
* [dp](https://github.com/davidparsson/zsh-dp-theme) -低对比度主题，如果存储库较脏且显示$ PYENV_VERSION的值，则显示当前git分支.
* [dracula](https://github.com/dracula/zsh) -Atom，Alfred，Chrome DevTools，iTerm 2，Sublime Text，Textmate，Terminal.app，Vim，Xcode和ZSH的深色主题.
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) -简约，包括`git`状态信息.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) 变体.
* [dtheme](https://github.com/OlukaDenis/DTheme)  -针对使用日晒终端配色方案和git的用户进行了优化.  使用unicode字体效果最佳.
* [duckster](https://github.com/ducky/duckster) -Gitster ZSH主题的叉子，更加新鲜.
* [ducula](https://github.com/janjoswig/Ducula)  -受吸血鬼计划的启发.  包括git状态修饰，用户名和主机名缩写，虚拟环境，当前工作目录，最后命令的返回状态和时间.
* [dustmod](https://github.com/bmihaila/dustmod) -源自 [dst](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/dst.zsh-theme) oh-my-zsh中的主题.
* [eckig](https://github.com/fouladi/eckig)  -带有utf-8图标的简约主题.  包括git状态装饰.
* [eggshausted](https://github.com/inutano/eggshausted) -厌倦了获取错误的人们的`git`意识主题.
* [elessar](https://github.com/fjpalacios/elessar-theme) -基于git的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) .  需要兼容Powerline的字体.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) -表情符号味 [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/robbyrussell/oh-my-zsh) 主题.
* [endless-dog](https://github.com/qwelyt/endless-dog) -模仿grml-zsh-config的OMZ主题.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) -在终端中占用大量空间.
* [eriner](https://github.com/zimfw/eriner) -电力线启发的Zim前叉 [agnoster](https://github.com/agnoster/agnoster-zsh-theme)  提示主题.  包括git状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) -一个带有`git`信息的简单主题.
* [eucalyptus](https://github.com/relastle/eucalyptus) -简单的一线主题，为极简主义vi模式用户带来灵感 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) -简单的ZSH颜色主题.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) -极简主义主题，带有git状态装饰，灵感来自 [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes)  -带有秋天图标的简约主题.  包括git状态装饰.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) -最小的ZSH提示，在黑暗背景下效果更好.
* [FDT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme)，预设为包括virtualenv，上一个命令状态，`nvm`，`docker machine`和`git`，`hg`和`bzr`状态修饰.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)  -干净，简单，兼容且有意义.  在Linux，Unix和Windows上以ANSI颜色进行了测试.
* [filthy](https://github.com/molovo/filthy) -令人反感的ZSH提示.
* [fishy-lite](https://github.com/sudorook/fishy-lite) -原叉 [fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy)  oh-my-zsh中的主题，并删除了许多无关紧要的内容以提高加载速度.  包括电池电量表和git状态显示，可以在提示的右侧启用.
* [fishy2](https://github.com/akinjide/fishy2) -ZSH主题的灵感来自 [original fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy).
* [fluent-git](https://github.com/RobertKozak/fluent-git) -显示上一次命令执行的时间，错误代码，主机名，用户名，git状态，kubernetes集群和名称空间，路径和ssh连接状态.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) -自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) .  包括git状态装饰.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) -包括最后一个命令的状态，git信息和当前目录.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) -前叉 [terminal-party](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) -基于 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) 哦，我的zsh主题.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) -红色版本 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh的主题.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme)  -在深色背景上效果很好.  包括git状态装饰.
* [frlo](https://github.com/fiorillo/frlo) -使用计算机的主机名提出一个（希望）唯一的三色主题以显示在提示中，因此您一眼就能知道要登录的计算机.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) -五颜六色的两行主题，支持`​​git`和`svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) -的叉子 [Cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme)  哦，我的zsh主题.  具有不同的颜色和表情符号.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) -彩色主题，在深色背景上效果更好.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) -Prezto在需要时立即提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme)  -Nicola Racco的主题.  需要`rvm`和`git`插件.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) -将oh-my-zsh gentoo主题分解为非omz用户的单独回购.
* [geometry](https://github.com/geometry-zsh/geometry) -最小的ZSH主题，可以将任何功能即时添加到左侧提示或（异步）右侧提示.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) -受启发 [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme)，包括`git`装饰，IP地址，主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) -的变体 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower)  具有更多功能，一点点注意和上下文相关的额外线条.  包括git状态修饰，历史记录编号，用户名/主机名上下文，目录状态，上次失败的命令状态以及Python virtualenv名称（如果存在）.
* [gimme](https://github.com/nralbrecht/gimmezsh)  -带有`git`集成的ZSH的简化主题.  受到启发 [gitsome](https://github.com/mtully/gitsome) 主题.
* [girazz](https://github.com/mdentremont/girazz) -对gnzh主题的修改，在右侧提示中添加了“ vi”模式.
* [git-prompt](https://github.com/olivierverdier/zsh-git-prompt)  -显示有关当前`git`信息库的信息.  特别是分支名称，与远程分支的区别，暂存或更改的文件数等.
* [gitsome](https://github.com/mtully/gitsome) -带有`git`信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)  -在`git`仓库中时，它显示`git`仓库根文件夹中的位置.  如果不在`git`仓库中，它将显示相对于家`〜`的路径.
* [gitster (zimfw)](https://github.com/unixorn/awesome-zsh-plugins/blob/master/[gitster](https://github.com/zimfw/gitster) -shashankmehta的Zim叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 提示主题
* [glimmer](https://github.com/martnu/glimmer) -包括`git`分支，时间和user @ host.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) -定制 [gnzh.zsh-theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gnzh.zsh-theme) 来自oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) -iTerm 2和ZSH的主题，包括git装饰，user @ host，路径和日期.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) -简单但内容丰富的主题，包括git装饰和最后一个命令的返回状态.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) -极简主义，包括`git`状态装饰.
* [grs](https://github.com/gersontpc/zsh-theme-grs) -包括git状态装饰，用户ID和工作目录.
* [gruvbox](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874)，使用与 [gruvbox](https://github.com/morhetz/gruvbox) `Vim`插件.
* [guri](https://github.com/victorfsf/guri) -基于以下内容的简单快速的Oh-My-Zsh主题 [Pure](https://github.com/sindresorhus/pure)的设计.
* [hackersaurus](https://github.com/bhilburn/hackersaurus)  -主题状态为git且上一条命令的退出代码运行在提示中.  相关 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) -带有`git`装饰的简约主题.
* [halil](https://github.com/5m0k3r/zsh-themes) -oh-my-zsh的货叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)  -一个简单的主题，第一个字符是花的汉字“花”.  这个主题的灵感来自一个称为DSA Hana的键帽.  这与 [hana atom](https://github.com/arturoalviar/hana-matcha-syntax)  主题.  包括git状态装饰.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) -如果超过`ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`，则显示`git`分支和状态，最后命令退出代码，最后命令执行时间.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) -基于氧化物，包括`git`状态修饰和当前用户/主机信息.
* [haribo](https://github.com/haribo/omz-haribo-theme) -简单的`git`状态+时间戳提示.
* [hcompact](https://github.com/fusion809/zsh-theme) -显示时间，操作系统（如果是Linux，则包括发行版），目录以及是否以root身份运行.
* [heart](https://github.com/gko/heart-theme) -以心脏为主题的浅色背景提示.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#bureau)，并添加了git状态装饰和npm状态.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old bash theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hexagon](https://github.com/diogoazevedos/hexagon) -基于的简约zsh主题 [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) -显示时间，日期，操作系统（如果是Linux，则包括发行版），目录以及是否以root身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) -受robbyrussell主题+ ssh连接状态提示的启发.
* [hina](https://github.com/ucpr/hina) -用`golang`编写，包括`git`状态修饰和kubernetes上下文.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) -的变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) -oh-my-zsh和iTerm 2的Honukai主题和颜色.
* [horizontal](https://github.com/nuimk/horizontal) -两行提示，带有水平分隔符.
* [hornix](https://github.com/fusion809/zsh-theme) -显示时间和日期，操作系统（如果是Linux，则包括发行版），目录以及是否以root身份运行.
* [horse-sh](https://github.com/emileswarts/horse-sh) -一个非常小的棕色/红色ZSH主题.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) -简单干净，包括最后执行的命令的返回码.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh)  -工作时需要拥抱.  包含git状态.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) -设计用于超级终端主题，包括`git`状态装饰.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) -为您提供正在处理的分支的全面概述以及存储库的状态，而不会使您的终端混乱.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) -在深色背景上效果很好.
* [ice](https://github.com/Lenart12/ice.zsh-theme) -非常轻微的修改 [bureau](https://github.com/isqua/bureau) 主题结合 [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme).
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX)  -修改了iGeek主题.  开箱即用可与macOS配合使用，包括`git`状态修饰.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) -超级快乐的Powerline风格，`git`意识的“仅prezto”主题.
* [igorsilva](https://github.com/igor9silva/zsh-theme) -显示当前目录，可自定义的定界符，当前分支，`git`状态.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) -包括git，nvm和venv装饰.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) -前叉 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster)  改进了间距并更新了图标.  包含`git`状态信息.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) -极简主义主题，在深色背景上效果更好.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) -干净的主题，显示git状态，后台作业，远程主机和其他信息.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) -的扩展 [intheloop](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/intheloop.zsh-theme) 主题以使用电力线字体.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) -itsthatguy的主题.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  -基于精致主题和ys主题，包括“ git”状态装饰.  包括可选的iterm2配色方案.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) -显示时间，当前目录和`git`分支信息，包括分支名称和红色+（如果分支未按任何更改）.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) -针对深色背景进行了优化，包括git状态和rvm状态.
* [jc](https://github.com/jclementex/jc-zsh-theme) -对于深色终端背景，请包含`git`状态信息.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) -宽松地基于ys主题.
* [jerome](https://github.com/jeromescuggs/jerome-theme) -基于 [dieter](https://github.com/jeromescuggs/jerome-theme)  主题，但具有黄色主机名.  包括git装饰.
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) -受启发 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme)，包含`git`状态.
* [jovial](https://github.com/zthxxx/jovial) -显示主机，用户，路径，开发环境，git分支，即python venv已激活.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) -极简提示.
* [just-another](https://github.com/supertassu/another-theme) -只是另一个主题，当您被丢弃到另一台计算机上时，其主机名为.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter)  -具有git，svn，npm，rvm和网络意识的电力线主题.  需要兼容Powerline的终端字体.
* [karu](https://github.com/zaari/karu) -极简单行ZSH提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) -主题，包括其他主题的一些功能.
* [kenton](https://github.com/notnek/zsh-theme) -针对深色背景进行了优化，包括`git`状态信息.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) -丰富多彩的主题，包括iTerm 2配色方案.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) -最小主题.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) -基于Fishy主题，但显示完整路径而不是缩写目录，并且仅在`ssh`会话和docker容器中显示user @ machine.
* [kiss](https://github.com/rileytwo/kiss)  -oh-my-zsh，VSCode，iTerm2，Neovim和RStudio的简单主题.  包括git状态装饰.
* [kketcham](https://github.com/prototype27/kketcham) -在git信息上具有漂亮颜色的主题.
* [klendathu](https://github.com/kegonomics/klendathu) -使用电力线iconolas.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  -最适合深色背景.  包括git状态装饰.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) -专为黑暗终端设计的两行主题，具有git装饰.
* [krak3n](https://github.com/krak3n/zsh-theme) -显示golang版本和当前的`git`分支.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) -ZSH的深色主题.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  -优化的Agnoster前叉，用于太阳能终端.  需要电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) -带有`git`和`hg`状态信息的多彩主题，能够向主机名添加主机特定的颜色.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) -最小的ZSH主题.
* [lambda (azahi)](https://github.com/azahi/zsh-lambda) -极简主义的ZSH主题.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) -受到robbyrussell的启发 [lambda](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/lambda.zsh-theme)  主题.  包括git状态装饰.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) -ZSH主题针对使用unicode兼容字体和终端应用程序的`git`用户进行了优化.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) -包含`git`信息的极简提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) -基于lambda的简单主题，具有`git`状态和virtualenv信息.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) -一个简单的ZSH主题，针对git的使用进行了优化.
* [lambda-pure](https://github.com/marszall87/lambda-pure) -基于Pure的最小ZSH主题，添加了NodeJS版本.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) -Lambda和Fishy主题的组合，包括`git`状态装饰.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) -针对暗终端进行了优化，具有适用于本地和远程系统的变体.
* [leafia](https://github.com/Ghostrick/leafia-prompt) -绿叶的prezto主题，显示git状态信息.
* [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/minimal.zsh-theme)，使用颜色和一个额外的¬字符来更好地区分命令行提示符和输出.
* [lewis](https://github.com/lewisflude/oh-my-lewis)  -黑色，白色和红色主题.  显示git状态信息.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) -极简主义主题，最好在黑暗的终端背景下使用.
* [lilith](https://github.com/aknackd/zsh-themes) -修改 [gallifrey](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gallifrey.zsh-theme) 和 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) -简单易定义的ZSH主题.
* [limpide](https://github.com/shooteram/limpide) -的修改版 [miloshadzic](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) -受Yaris Alex Gutierrez的启发 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh)，Yad Smood的y和局主题.
* [liquidprompt](https://github.com/nojhan/liquidprompt)  -功能齐全且经过精心设计的自适应提示，在您需要时会提供有用的信息.  它向您显示在需要时需要的内容.  您会注意到变化时会发生什么变化，从而节省了时间和沮丧感.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) -识别美洲驼的极简主义主题.
* [logico](https://github.com/logico-software/logico-zsh-theme)  -有`git`装饰品.  显示vi模式的远程状态和指示器.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) -基于Sindre Sorhus纯粹主题的德克萨斯主题主题.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  -lambda-mod主题的变体.  具有`git`装饰，需要电力线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)  -包括git装饰.  基于 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) 哦，我的zsh主题.
* [magicmace](https://github.com/zimfw/magicmace) -受启发 [xero's zsh prompt](http://code.xero.nu/dotfiles) 和 [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last comm和, shortened working directory, `git` status decorations.
* [magico](https://github.com/IOsonoTAN/magico) -IOsonoTAN的magico主题.
* [maivana](https://github.com/nylo-andry/zsh-themes) -包括`kubectl`上下文，`git`状态装饰.
* [materialshell](https://github.com/carloscuesta/materialshell) - 一种 [material design](https://material.io/guidelines/style/color.html)  外壳的主题，重要部分具有良好的对比度和色彩突显.  专为方便眼睛而设计.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) -的变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  看起来像Matrix电影三部曲中的某物.  包括git状态装饰.
* [matter](https://github.com/mrobillard/matter-zsh-theme) -显示git状态，AWS Vault角色，后台作业，最后命令的退出代码和主机名.
* [mattizer](https://github.com/matt-sungwook/ohmyzsh-mattizer-theme) -包括工作目录和git状态修饰.
* [mau](https://github.com/vichargrave/mau) -ZSH主题，带有猫扭纹.
* [maxulysse/myzsh](https://github.com/MaxUlysse/myzsh) -Maxime Garcia的myzsh主题.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) -包括git装饰，如果root用户，活动作业和 [jenv](https://github.com/jenv/jenv) 积分.
* [mdmini](https://github.com/MarioDena/MDmini) -包括`git`和`ssh`状态装饰.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)  -最大化提示，包括键盘模式，所有权信息和其他上下文信息，其中λ为提示字符.  需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) -包含`git`状态修饰符，如果非零则显示最后一个命令的退出代码.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  -检查“ / sys / class / power_supply”文件夹，以确定系统是否安装在便携式计算机或台式计算机上.  读取电池百分比grepping acpi命令并将其显示在提示中.  包括git装饰.
* [midin](https://github.com/xlshiz/midin) -在黑暗的终端背景下效果很好，包括`git`状态装饰.
* [milight](https://github.com/frodoslaw/milight-zsh) -带有`git`状态显示的最小ZSH提示，最适合深色终端背景.
* [min](https://github.com/andrepolischuk/min) -简约的ZSH提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) -ZSH主题，带有空间.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) -包括git，node，golang，yarn，php，docker和python状态装饰.
* [minima (eduardnikolenko)](https://github.com/eduardnikolenko/minima)  -一个最小的ZSH主题，带有git，docker，go，node，npm，python和其他指示符.  对某些标记使用Unicode字符.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) -黑暗终端的主题，在右侧提示中包含`git`装饰.
* [minimal2](https://github.com/PatTheMav/minimal2)  -最小且可扩展的ZSH主题.  分叉于 [subnixr's original](https://github.com/subnixr/minimal) 并适用于 [Zimfw](https://github.com/zimfw/zimfw).
* [minimal](https://github.com/subnixr/minimal) -最小但功能丰富的主题.
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) -灵感来自oh-my-zsh的kolo主题.
* [misa](https://github.com/misalabs/misa.zsh-theme) -Misalabs的ZSH主题.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) -针对深色背景进行了优化.
* [moderno](https://github.com/obrassard/moderno-zsh) -一个简单现代的ZSH主题，灵感来自 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH的主题.  包括git状态装饰.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [moonline](https://github.com/kagamilove0707/moonline.zsh) -最小但易于扩展的提示.
* [moux](https://github.com/gagbo/moux) -在深色背景下效果很好，在RPROMPT中包含git装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) -在您的提示下提供有关您所在存储库的有用信息.它当前可用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/)，在 [ZSH](https://en.wikipedia.org/wiki/Zsh) 以及 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) -基于电力线的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) -一个简单的最小ZSH提示主题.
* [musy](https://github.com/THaGKI9/musy-zsh-theme)  -受缪斯主题的启发.  包括git状态装饰.
* [nanofish](https://github.com/tweekmonster/nanofish) -将鱼式目录提示添加到纳米技术主题.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme)  -带有`git`装饰的最小主题.  基于 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell).
* [neon](https://github.com/sahariko/neon) -带有`git`装饰的漂亮且最小的ZSH主题.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) -带有书呆子字体的ZSH的快速主题.
* [nescalante](https://github.com/nescalante/zsh-theme) -针对黑暗终端背景进行了优化，包括git装饰.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) -包括git装饰和vi模式指示器.
* [newt](https://github.com/softmoth/zsh-prompt-newt) -胖与快的主题–由内而外的精美外观，正确完成的样式段.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) -一个非常基本的主题，仅带有macOS自行车图标.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) -色彩鲜艳，显示`git`状态装饰.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) -基于af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) -一个简单的oh-my-zsh主题.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) -极简主义的ZSH主题，带有`git`状态装饰.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) -打破了OMZ的节点主题，使其更易于与其他插件管理器一起使用.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) -基于ys主题，添加了NodeJS版本（来自NVM插件）.
* [noon](https://github.com/silky/noon.zsh-theme) -具有浅色和深色变体，显示`git`信息.
* [nord](https://github.com/TyWR/Nord-zsh) -包含git状态装饰并显示活动的conda环境.
* [nothing](https://github.com/eendroroy/nothing) -闪电般快速且非常简单，因为其中几乎没有任何东西.
* [nox](https://github.com/kbrsh/nox) -深色主题，显示当前工作目录和git状态.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)  -清洁，无干扰且关注git的开发主题.  显示相对于`git`根的路径（或在`git` repo外的〜），自上次提交以来的时间，当前SHA，分支和分支状态.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) -prezto和oh-my-zsh的简单主题.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) -简约主题，包括git状态装饰和时间.
* [odin](https://github.com/tylerreckart/odin) -Odin是具有git`风格的ZSH主题.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) -带有`git`装饰的多行主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) -强烈要求bash和ZSH提示.
* [oh-my-via](https://github.com/badouralix/oh-my-via) -ZSH的主题，它主要分叉VIA服务器上使用的历史主题.
* [ohmypc](https://github.com/joselpadronc/OhMyPC)  -适用于深色终端窗口.  包括git装饰.
* [om](https://github.com/sirshikher/zsh-om) -最小主题，可在深色背景下使用，包括`git`状态装饰.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) -包括git状态和virtualenv信息.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) -简约的深色ZSH主题.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO-让我们呼吸干净的ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) -主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) 提示，重点放在简单性上，同时仍然获得重要信息.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme)  -具有VCS支持的简单主题.  提示符显示当前工作目录，分支的一级，以及颜色编码的弯曲粗箭头.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) -允许显示主机信息，包括`git`分支修饰.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) -在提示中显示带有图标的详细git状态信息.
* [papercolor](https://github.com/erikschreier/PaperColor-themes)  -ZSH，vim和tmux的配色方案.  包括git状态装饰.
* [parrot](https://github.com/kennedy69/parrot-zsh-theme) -模仿鹦鹉安全提示，包括 [tmux](https://github.com/tmux/tmux) 配置文件.
* [pastel](https://github.com/iboyperson/pastel) -受启发的ZSH主题 [sugar-free](https://github.com/cbrock/sugar-free) .  包括git装饰.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 和纯壳主题.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) -丰富多彩的主题，包括go版本，node版本和`git`状态.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) -ZSH简洁明了的主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
* [pi](https://github.com/tobyjamesthomas/pi) -带有`git`状态装饰的简约主题.
* [plain](https://github.com/jimeh/plain.zsh-theme) -ZSH的简单主题，显示基本的git信息.
* [planet](https://github.com/borb/planet-zsh) -精简版 [steef](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) -简单，简洁的主题.
* [platypus](https://github.com/fdv/platypus) -鸭嘴兽是弗雷德里克·德·维拉米尔（Frédéricde Villamil）使用的oh-my-zsh的简单便捷主题.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) -显示工作目录，最后一个命令的返回状态以及git当前分支.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) -RDM的基本oh-my-zsh自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) -具有git状态，Ruby版本和项目路径的程序员主题.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) -适用于深色终端背景，包括git状态装饰.
* [powerless](https://github.com/martinrotter/powerless) -受电力线启发的小巧而简单的纯ZSH提示.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) -快速重新实现 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH主题.  可以用作powerlevel9k的替代产品，如果提供相同的配置选项，它将生成相同的提示，但速度更快.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) -Powerlevel9k是ZSH的主题，它使用 [Powerline Fonts](https://github.com/powerline/fonts) .  它可以与香草ZSH或ZSH框架（例如 [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) -适用于 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) -电力线的两行版本：一条用于提供信息，一条用于输入.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)  -关于电力线主题的另一种观点.  可以很好地配置，但是至少需要256种具有颜色的终端以及与电源线兼容的终端字体.
* [powerline (syui)](https://github.com/syui/powerline.zsh) -具有git意识的电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) 外壳，并且易于扩展.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一种 [Powerline](https://github.com/powerline/powerline)  用Haskell编写的克隆.  它比原始实现要快得多，并且使外壳响应速度明显加快.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) -使用Ruby创建，使用电力线字符来模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) -Bash，ZSH，Fish和tcsh的美丽而有用的提示生成器.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一种 [powerline](https://github.com/Lokaltog/vim-powerline) -类似Bash，ZSH和Fish的提示.  显示有关git / svn / hg / fossil分支的重要详细信息，并且易于自定义/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) -电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - 一种 [Powerline](https://github.com/Lokaltog/vim-powerline)类似的提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash) .  显示virtualenv，&#39;git&#39;状态信息和上次运行命令的退出代码.
* [powerzeesh](https://github.com/sevaho/Powerzeesh)  -基于电力线的ZSH主题.  它旨在简化操作，仅在相关时才显示信息，并针对速度和外观进行了优化.  受启发 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) -Sublime Text，Terminal，iTerm 2和ZSH的主题集合.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) -为黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) -oh-my-zsh的云提示的Prezto端口.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) -Lambda主题（用于prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline)  -Prezto的电力线.  显示git信息，RVM版本.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) -基于流行的同名vim插件的电力线字体，相当重的ZSH提示符，在深色背景下效果很好.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) -具有动态退出状态指示器，可以动态更改为两行以显示上下文.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) -易于定制，受到 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)  -纯粹和无知的混搭.  具有git装饰，可在深色和浅色终端背景下正常使用.
* [pure](https://github.com/sindresorhus/pure) -漂亮，最小和快速的ZSH提示.
* [purify](https://github.com/banminkyoz/purify) -简单，快速和酷的提示.
* [purity](https://github.com/petermbenjamin/purity) -受到robbyrussell主题+纯提示的启发.
* [purs](https://github.com/xcambar/purs) - 一种 [Pure](https://github.com/sindresorhus/pure)灵感提示 [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) -灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题，包括“ git”装饰.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  -针对深色背景进行了优化，包括`git`信息.  主题回购包括iTerm 2和终端颜色设置.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) -基于af-magic和posh-git.
* [radium](https://github.com/dimitardimitrov/radium) -专为深色端子设计， [Solarized](https://github.com/altercation/solarized) iTerm 2主题）（prezto）.
* [rafiki](https://github.com/akabiru/rafiki-zsh) -将表情符号添加到您的ZSH终端.
* [rainbowie](https://github.com/druskus20/rainbowie) -带有`git`信息的多彩主题.
* [ramiel](https://github.com/aknackd/zsh-themes) -的 [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和“ robbyrussell”主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) -随机表情符号.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) -简单多彩的主题，带有git状态装饰.
* [rb](https://github.com/rberenguel/rb-zsh-theme) -基于电力线的ZSH主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对git和日晒终端进行了优化.  需要兼容Powerline的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) -针对日晒终端配色方案进行了优化，包括git状态装饰.
* [redline](https://github.com/DrissTM/redline.zsh-theme)  -极简主义主题.  包括`git`状态，时间，用户.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) -使用颜色编码的状态修饰将大量信息压缩到提示中.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) -一个简单的主题，第一个字符为零（rei），数字为0.包括git状态修饰.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) -基于agnoster，针对 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [river](https://github.com/revir/river-zsh-config) -带有`git`信息的深色主题.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) -基于 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 主题与项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) -用输出装饰`robbyrussell`主题以指示** WIP **提交.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) -黑暗的主题.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) -针对深色背景进行了优化.
* [rummik](https://github.com/rummik/zsh-theme)  -@rummik的主题.  支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin)，以及提示中的git状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) -受启发 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto) .  包括git状态装饰.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) -丰富多彩的主题，包括git装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) -具有表情符号指示的git状态的主题.
* [s1ck94](https://github.com/zimfw/s1ck94)  -S1cK94的（最早不推荐使用，现已淘汰）最小提示的分叉.  显示用户是否为root，后台作业状态，vi模式，上一个命令的退出状态以及git状态修饰.
* [saltgen](https://github.com/saltgen/ohmyzsh-saltgen-theme) -robbyrussell oh-my-zsh主题的变体.
* [samshell](https://github.com/samuelb/samshell) -带有`git`，kubernetes和python virtualenv装饰的简约zsh主题.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) -包括git状态，在黑暗的终端背景下效果很好.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) -显示git状态，user @ host信息，上一个命令的退出状态以及是否以root身份运行.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) -显示在使用`：sh`命令时Vim是否在后台运行.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) -为添加标签补全 [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes)  -以海洋为灵感的表情符号装饰的最小主题.  包括git状态装饰.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) -此主题使用许多特殊的unicode字符看中，但是如果没有良好支持的字体，可能会引起一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) -受节食者主题启发，使用颜色编码提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh)  -Devops的干净提示主题.  包括git信息，kubernetes上下文，AWS配置文件，GCP项目和Azure活动云.
* [seppuku](https://github.com/Helianthella/seppuku) -干净而最小的主题灵感来自 [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme).
* [sepshell](https://github.com/sepehr/sepshell) -基于旧的迷失的taybalt主题的干净，最小的ZSH主题，带有git划分为对等/合并/重新设置基准的模式和可配置的提示符号.
* [Seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) -与omz兼容的简单主题以及相应的iTerm 2配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) -精益提示的演变，它本身就是对pure的重写.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) -具有`git`状态装饰的简单主题.
* [shellder](https://github.com/simnalamburt/shellder)  -带有git分支显示的最小主题.  需要兼容Powerline的字体.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  -一个简单的主题，第一个字符为七（shichi / nana），数字为7.主色为红色，带有黄色重音.  包括git状态装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) -来自 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) .  有`git`装饰.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) -基于 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme)  主题.  包括git和hg状态装饰.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) -包括git装饰.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) -显示当前目录和git信息的简单主题.
* [siegerts](https://github.com/siegerts/zsh-theme) -在正确的提示中包含`git`状态装饰.
* [silver](https://github.com/reujab/silver) -跨外壳可自定义的类似于电力线的提示，深受启发 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) .  更快的防锈口 [bronze](https://github.com/reujab/bronze) .  需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
* [simpalt](https://github.com/m-lima/simpalt) -基于ZSH的信息丰富的小足迹主题，基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) -电力线启发的简单主题，带有git装饰.
* [simple](https://github.com/pavdmyt/simple-oh-my-zsh-theme) -基于的简约主题 [robbyrussel](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 它将git状态信息嵌入iTerm的窗口标题栏中，而不是在提示中使用空格.
* [simplezsh](https://github.com/fr0zn/simplezsh) -带有`git`信息显示的最小主题.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  -k-kinzal的sinon主题.  包括git状态装饰.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme)  -此主题具有唯一的目录列表.  在`git`项目中时，目录显示的范围为当前存储库根目录.
* [sk9](https://github.com/skeiter9/sk9-zsh) -Skeiter9的ZSH主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) -受He-Man和Universe of Masters的Skeletor启发，为Atom，Prism和ZSH设计主题集合.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) -针对暗终端进行了优化，显示`git`状态装饰.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) -ZSH主题的灵感来自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
* [slimline](https://github.com/mengelbrecht/slimline)  -最小，快速且优雅的ZSH提示.  在正确的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme)  **收藏夹**终端的** Simplist **和** Minimalist **主题.  包括git状态装饰.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) -的变体 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) 主题 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) -出现幸福和悲伤表情的提示.
* [snakypy](https://github.com/snakypy/snakypy-prompt) -专注于 [Python](https://www.python.org/)  开发人员.  显示git和venv状态装饰.  包括安装程序脚本.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme)  -简约ZSH主题，灵感来自老式的爱好.  没有冗长的头，没有表情符号，没有烦躁的微调，也没有其他视觉噪音.  同时具有明暗模式.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) -ZSH的太阳能电力线风格主题.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) -太阳能电力线变体.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) -为robbyrussell的oh-my-zsh主题进行颜色修复 [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) -带有git，nvm，rvm / rbenv / chruby，python，ssh和其他有用状态指示器的主题.
* [spowerline](https://mbauhardt.github.io/spowerline/) -受无知者启发，以Scala语言撰写， [tmux](https://tmux.github.io) 电源线，vim电源线和vim状态插件.
* [squanchy](https://github.com/gabrielecanepa/squanchy)  -极简主义主题.  包括git，node和rbenv状态装饰.
* [staples](https://github.com/dersam/staples) -基于局，如果通过SSH连接，则显示user @ host.
* [starboy](https://github.com/prdpx7/Starboy) -一个简单的ZSH主题
* [statusline](https://github.com/el1t/statusline) -响应性ZSH主题，可在需要时提供信息性细分.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)  -ZSH steeef主题作为独立的存储库.  此仓库背后的目的是避免在使用steeef主题时依赖oh-my-zsh.  ZSH插件管理器（例如Antibody）可以使用主题，而不必使用oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) -的可自定义版本 [steeef's](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) 主题.
* [sublime](https://github.com/pjmp/sublime) -具有`git`状态装饰的崇高，干净，简约的zsh主题.
* [sugar-free](https://github.com/cbrock/sugar-free) -基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme)  -包括`git`状态装饰.  在黑暗的终端背景下效果更好.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - 相似 [sunrise](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/sunrise.zsh-theme) 但包含有效的Ruby版本.
* [superkolo](https://github.com/Minipada/superkolo) -将日期和返回状态添加到 [kolo](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) -包括git状态装饰和随附的iTerm2配色方案.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme)，包括`git`状态装饰.
* [t2er](https://github.com/t2er/t2er-zsh-theme) -带有`git`装饰的简约主题.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) -最小的ZSH主题针对深色背景进行了优化.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) -包括git状态装饰和conda / virtualenv状态.
* [termuxer](https://github.com/patrick330602/termuxer) -受agnoster和linuxer启发的主题.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) -基于的主题 [gallifrey](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) -具有`git`状态的多彩主题.
* [thetraveler](https://github.com/bassopenguin/thetraveler) -受解谜者启发，使用符号显示git状态.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) -的最低版本 [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
* [thyme](https://github.com/kawamurakazushi/thyme) -具有`git`状态装饰的简单主题.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  -包含`git`信息；  最好在深色背景上.
* [tq](https://github.com/kitian616/tq-zsh-theme) -显示git状态，时间，需要Powerline字体.
* [traffic](https://github.com/fcce/traffic-zsh-theme) -ZSH的深色主题.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) -ZSH的深色主题.
* [trinity](https://github.com/de-luca/Trinity) -基于的简单主题 [geometry](https://github.com/geometry-zsh/geometry) .  包括git装饰.
* [tsotra](https://github.com/nylo-andry/zsh-themes) -极简主义主题，包括git状态装饰，k8s上下文和rvm状态.
* [tvline](https://github.com/thvitt/tvline) -源自 [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加了电力线字体增强功能.
* [type0](https://github.com/MikereDD/type0_zsh-theme) -受启发 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh)  由yarisgutierrez.  包括git装饰.
* [typewritten](https://github.com/reobin/typewritten) -最小且内容丰富的主题，为重要内容留有余地.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) -模拟默认的Debian / Ubuntu bash提示符.
* [ultimate](https://github.com/b4b4r07/ultimate) -带有`git`指示器，vim模式指示器和缩短路径的简约主题.
* [vanan](https://github.com/avano/vanan-zsh-theme) -极简主义主题，带有用于黑暗终端的git信息.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) -修改自themes / mgutz.zsh-theme.当与 [Solarized](https://github.com/altercation/solarized) 配色方案.
* [wade](https://github.com/wadehammes/wade.zsh-theme) -流行的ZSH主题混搭 [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/fishy.zsh-theme)，并进行一些视觉上的调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) -基于0532主题.
* [webicons](https://github.com/Jmclerck/webicons.zsh-theme) -在提示中包括`git`状态，节点和纱线版本.
* [whale](https://github.com/whalesea520/whale-zsh-theme) -快速重新实现鲸鱼主题.
* [wild-cherry](https://github.com/mashaal/wild-cherry) -ZSH，iTerm 2，Sublime，Atom和Mou的童话主题.
* [work-line](https://github.com/afnizarnur/work-line) -带有精美表情符号的主题.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) -包括git状态修饰，工作目录，最后命令的退出状态和当前virtualenv.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  -一个主题，旨在在需要时向您显示所需的信息.  “ wynwyn”的灵感来自默认主题“ avit”和出色的主题. [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xm](https://github.com/Shiaoming/xm)  -黑暗终端的主题.  有`git`装饰.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) -基于Jreese主题插件的oh-my-zsh shell主题.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme)  -快速，简单，精简的主题.  最适合搭配 [tmux](https://github.com/tmux/tmux/wiki) 和 [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) -显示当前git commit的缩短的哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)  -最小主题，行分隔提示.  基于 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) -带有`git`状态装饰的简约主题.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) -修改自 [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) 主题，并针对深色背景进行了优化.
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) -干净，简单，兼容且有意义的主题，适合深色背景.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) -具有`git`状态信息的简单ZSH主题.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) -黑暗优化的ZSH主题.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) -包括conda和venv状态.
* [yz50](https://github.com/lacanlale/yz50-zsh) -色彩丰富，基于 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/crunch.zsh-theme)  主题.  包括git状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) -基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme)  塞尔达传说主题.  包括git状态装饰.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) -oh-my-zsh的定制版本 [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme) 在多方面的支持和其他变化下.
* [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh) .  包括退出状态，“ virtualenv”，“ nvm”，“ rvm”和“ git”状态装饰.
* [zero](https://github.com/arlimus/zero.zsh)  -零的主题和插件.  具有浅色和深色端子背景的变体.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) -在深色背景上效果最好，包括`git`状态装饰.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) -显示用户名，git状态信息，计算机名称和当前工作目录.
* [zinc](https://gitlab.com/robobenklein/zinc) -快速，纯净的ZSH，混合异步电力线提示，易于扩展且可高度配置.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) -oh-my-zsh的修改版 [maran](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh2000](https://github.com/inspectahstack/zsh2000) -电力线外观ZSH主题，其中包括rvm提示符，git状态和分支，当前时间，用户，主机名，密码，退出状态，是否以root和后台作业状态运行.
* [zsh313](https://github.com/amirali313/zsh313-theme) -带有`git`状态装饰的最小主题.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zshred](https://github.com/redxtech/zshred) -显示当前目录，`git`装饰，上一个命令的退出状态和时间.
* [zwsh](https://github.com/naens/zwsh) -ZSH的Zpm3 / Wordstar模式/主题.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) -类似于agnoster-zsh-theme，旨​​在通过电力线美学在上下文中公开信息.

### Fonts

此处列出的某些主题需要与Powerline兼容的字体，以下是一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) -包括一些漂亮的等距图标的字体家族.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) -一个不错的等宽字体，并添加了Font-Awesome，Octoicons和Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) -另一种与Powerline兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) -另一种与Powerline兼容的字体，专门为源代码设计.
* [Input Mono](http://input.fontbureau.com/)  -专为代码设计的字体家族.  它提供等宽字体和比例字体，并包含电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka)  -编码员的字体，由代码构建.  高度可定制的.
* [Monoid](https://larsenwork.com/monoid/) -Monoid可自定义和优化，即使在低分辨率显示器上，也能以15px行高的位图式清晰度进行编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)  -为Powerline，Font Awesome，Octicons，Devicons和Vim Devicons收集了20多种修补字体（超过2,000种变体）和FontForge字体修补器python脚本.  包括：Droid Sans，Meslo，源代码，AnonymousPro，Hack，ProFont，Inconsolata等.
* [Powerline patched font collection](https://github.com/powerline/fonts) -修补了十几种字体的集合，其中包括电力线字形.
* [Terminus](http://files.ax86.net/terminus-ttf/) -包含电力线字形的Terminus的TTF版本.

## Installation

### [Antibody](https://github.com/getantibody/antibody)

 通过将`antibody bundle githubuser / reponame`添加到您的.zshrc文件中，可以安装大多数这些插件.  下次启动“ zsh”时，抗体将自动为您处理克隆插件.  您还可以将插件添加到正在运行的ZSH中，并使用“抗体包githubuser / reponame”进行测试，然后再将其添加到.zshrc中.

### [Antigen](https://github.com/zsh-users/antigen)

 这些插件中的大多数都可以通过在.zshrc文件中添加“ antigen bundle githubuser / reponame”来安装.  Antigen会在您下次启动`zsh`时自动为您处理克隆插件.  您还可以将插件添加到正在运行的ZSH中，并使用“ antigen bundle githubuser / reponame”进行测试，然后再将其添加到.zshrc中.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.将新插件克隆到.zsh.local / modules中
2.将插件模块加载到.zshrc中
3.打开一个新的ZSH终端窗口或选项卡

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd〜/ .oh-my-zsh / custom / plugins`
2.`git clone repo`
3.将仓库添加到您的插件列表中

### [Prezto](https://github.com/sorin-ionescu/prezto)

1.将插件克隆到您的prezto模块目录中
2.将插件添加到您的.zpreztorc文件中
3.打开一个新的终端窗口或选项卡

### [Zgen](https://github.com/tarjoilija/zgen)

这些插件中的大多数都可以通过将zgen load githubuser / reponame添加到您的.zshrc文件中来进行安装，其功能与您执行其他zgen load调用时所用的功能相同.当您执行`zgen save`.

### [zplug](https://github.com/zplug/zplug)

通过将zplug“ githubuser / reponame”添加到您的.zshrc文件中，可以安装大多数这些插件.

## Writing New Plugins

我已经记录了一些有关编写新插件的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [zshdb](https://github.com/rocky/zshdb) -ZSH调试器
* [zunit](https://github.com/zunit-zsh/zunit) -强大的ZSH单元测试框架

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) -精选的出色工具，资源和工作流程提示清单，构成了很棒的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) -精湛的开源sysadmin资源精选列表
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) -CLI爱好者的精选清单.

在上找到其他有用的awesome- *列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 是必不可少的.
