<div class="github-widget" data-repo="unixorn/awesome-zsh-plugins"></div>
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

ZSH框架，插件，教程和主题的集合，灵感来自各种精彩的列表集合.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) 在贡献之前.*

## Frameworks

这些框架使您可以更轻松地自定义ZSH设置.

### [alf](https://github.com/psyrendust/alf)

 ** Alf **是ZSH的超快速可配置框架;  它以Prezto和Antigen为蓝本，同时在封面下使用了Oh-My-Zsh;  并提供标准默认值，别名，功能，自动完成，自动更新和可安装的提示主题和插件.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 ** ansible-role-zsh **是一个安装零知识的安全角色.  它使用抗原来管理捆绑和oh-my-zsh.  可以有条件地加载包.  默认情况下，它包括powerlevel9k主题，autosuggestions，语法高亮和fzf-widget.  完全可定制.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

 ** Ant-zsh **是一个小巧轻便的ZSH配置环境，可满足特殊的定制需求.  它包括插件，主题和基本方便的设置.

### [antibody](https://github.com/getantibody/antibody)

 **抗体**用Golang编写的更快更简单的抗原.  更多细节在 [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

 **抗原-hs **是启动壳体时针对低开销优化的抗原的替代物.  它会自动为您修复插件.

### [antigen](https://github.com/zsh-users/antigen)

 ** Antigen **是一小组函数，可以帮助您轻松管理shell（ZSH）插件，称为bundle.  这个概念与典型的vim +病原体设置中的捆绑包几乎相同.  抗原是ZSH，Vundle是vim.  Antigen可以加载oh-my-zsh主题和插件，并会自动为你克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

 ** Ax-ZSH **是ZSH的模块化配置系统.  它提供了理智的默认值，并且可以通过插件扩展.

### [dotzsh](https://github.com/dotphiles/dotzsh)

 ** Dotzsh **力求与平台和版本无关.  在较旧版本的ZSH下运行时，某些功能可能会丢失，但它应该干净地降级并允许您在不同操作系统的多台计算机上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [oh-my-zsh](https://ohmyz.sh/)

 ** oh-my-zsh **是一个用于管理ZSH配置的社区驱动框架.  包括120多个可选插件（rails，git，macOS，hub，capistrano，brew，ant，macports等），超过120个主题，为您的早晨增添趣味，还有一个自动更新工具，可让您轻松了解最新动态来自社区的更新.

### [prezto](https://github.com/sorin-ionescu/prezto)

 ** Prezto **使用合理的默认值，别名，函数，自动完成和提示主题来丰富ZSH命令行界面环境.  有一些prezto特定的插件 [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

** Pumice **是ZSH的轻量级插件管理器.

### [sheldon](https://github.com/rossmacarthur/sheldon)

一个快速，可配置的shell插件管理器.

*可以管理
  *任何Git存储库.
    *分支/标记/提交支持.
    *对GitHub存储库的额外支持.
    *对Gists的额外支持.
  *任意远程文件，只需指定URL即可.
  *本地插件，只需指定目录路径即可.
*高度可配置的安装方法使用 [handlebars](http://handlebarsjs.com/) 模板.
*超快并行安装.
* Configuration file using [TOML](https://github.com/toml-lang/toml) 句法.
*使用锁定文件可以更快地加载插件.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

** Toasty **是一个ZSH框架，用于促进管理，而不是指令.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack是一个基本的快速最小ZSH插件加载器.

### [zeesh](https://github.com/zeekay/zeesh)

 ** Zeesh **是一个跨平台的ZSH框架.  它类似于，但不相容， [oh-my-zsh](http://ohmyz.sh/) .  它具有模块化插件架构，易于扩展.  它有一组丰富的默认值，但设计尽可能轻量级.

### [zgem](https://github.com/qoomon/zgem)

** Zgem **是ZSH的插件管理器，支持从git，http和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 ** Zgen **是一个灵感来自Antigen的ZSH的轻量级插件管理器.  目标是在启动shell时获得最小的开销，因为没有人喜欢等待.  该脚本生成一个静态的`init.zsh`文件，该文件除了获取插件并将它们附加到你的`fpath`之外什么都不做.  这样就不必执行耗时的逻辑（插件检查，更新等），从而节省了启动时间.  缺点是，每当更新`.zshrc`时，必须使用`zgen reset`手动刷新init脚本.  可以加载 [oh-my-zsh](http://ohmyz.sh/)兼容的插件和主题，并在您将它们添加到插件列表时自动克隆它们.

### [zilsh](https://github.com/zilsh/zilsh)

** zilsh **是一个ZSH配置系统，旨在吸引更多的权力用户，并遵循vim-pathogen的简单方法.

### [zim](https://github.com/zimfw/zimfw)

** Zim **是一个ZSH配置框架，具有超快的速度和模块化扩展.

### [zit](https://github.com/m45t3r/zit)

 ** zit **是ZSH的插件管理器.  它是最小的，因为它实现了作为插件管理器限定的最低限度：它允许用户从Git存储库（仅限Git存储库，它们为什么名称）安装插件，源插件并更新它们.  它没有实现奇特的功能，如清除已删除的插件，自动编译已安装的插件，别名为oh-my-zsh / prezto /其他ZSH框架，构建二进制文件，PATH操作等.

### [zoppo](https://github.com/zoppo/zoppo)

 ** Zoppo **是ZSH的残缺配置框架.  正如一句意大利语所说的那样：“chi va con lo zoppo，impara a zoppicare”，我们意识到我们正在瘫痪行走，现在我们将变得瘫痪.

### [zpacker](https://github.com/happyslowly/zpacker)

** Zpacker **是一个轻量级的ZSH插件和主题管理框架.

### [zplug](https://github.com/zplug/zplug)

**：hibiscus：Zplug **是下一代ZSH插件管理器.

- 可以管理一切
  - 打开Zsh插件/ UNIX命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  -  Gist文件（[gist.github.com](https://gist.github.com/discover))
  - 外部管理的插件，例如， [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) 插件/主题
  - 二进制文物 [GitHub Releases](https://help.github.com/articles/about-releases/)
  - 本地插件
  - 等等（你可以添加你 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- 支持延迟加载
- 分支/标记/提交支持
- 更新后，加载后挂钩
- 包之间的依赖关系
- 不像 [antigen](https://github.com/zsh-users/antigen)，不需要ZSH插件文件（`* .plugin.zsh`）
- 互动界面（[fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- 用于减少的缓存机制 [the startup time](https://github.com/zplug/zplug#vs)

### [zplugin](https://github.com/zdharma/zplugin)

** Zplugin **是一个创新的插件管理器 [semigraphical UI](https://github.com/zdharma/zplugin-crasis), [Turbo Mode](https://github.com/zdharma/zplugin#turbo-mode)，干净的道路，报告，完成管理和 [services](https://github.com/zservices)  支持.  您可以使用 [crasis](https://github.com/zdharma/zplugin-crasis) 编辑你的`〜.zshrc`中的Zplugin命令.

### [ZPM](https://github.com/zpm-zsh/zpm)

** ZPM **（ZSH插件管理器）是一个插件管理器 [ZSH](http://www.zsh.org/)  类似于vim-plug.  ZPM插件兼容 [oh-my-zsh](http://ohmyz.sh/) .  ZPM运行在Linux，macOS，FreeBSD和Android上.

### [ZR](https://github.com/jedahan/zr)

** ZR **是一个快速，简单的ZSH插件管理器，用Rust编写，可以使用`cargo install zr`轻松安装.

### [zshing](https://github.com/zakariaGatter/zshing)

** zshing **是一个类似于Vundle / Vim的ZSH插件管理器，允许你......

*在`.zshrc`中跟踪和配置你的插件
*安装Zsh插件
*更新Zsh插件
*按名称搜索所有可用的Zsh插件
*清理未使用的插件
*在* single命令中运行上述操作*
*管理已安装插件的__Source插件___

### [ztanesh](https://github.com/miohtama/ztanesh)

** Ztanesh **旨在通过ztanesh项目提供的配置来改善您的UNIX命令行体验和工作效率：这些工具将使您的shell更强大，更易于使用.

### [zulu](https://github.com/zulu-zsh/zulu)

** Zulu **是ZSH 5+的环境管理员，旨在使您无需编写任何代码即可轻松管理shell.

*无需编辑文件即可轻松管理shell环境.
*创建别名，函数和环境变量，并在下次shell启动时将它们提供给您.
*使用简单的命令在`$ path`，`$ fpath`和`$ cdpath`中添加和删除目录.
*轻松安装软件包，插件和主题，并立即为您提供.

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)，和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) 为高效的开发人员工作流程做出贡献.
* [https://commandlinepoweruser.com](https://commandlinepoweruser.com/) -  Wes Bos的视频介绍了ZSH和oh-my-zsh.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh)   -  Arch Linux的ZSH介绍.  不是Arch或Linux特定的.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖ZSH没有的一些功能，Bash没有，并使用oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) -  Seth Brown关于结合ZSH的教程， [tmux](https://tmux.github.io) 和vim.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - 为oh-my-zsh初学者写了一个快速设置文档，展示如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示，语法突出显示提示，自动提示和自定义iTerm 2主题.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) -  slidehare演示文稿.
* [ZSH Pony](https://github.com/mika/zsh-pony) - 涵盖自定义ZSH而无需框架.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) -  Christian Schneider详细列出的ZSH提示.

### Antigen

* [https://mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) -  Michael Maclean关于从oh-my-zsh转换为抗原的文章.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) -  Josh Davis对Antigen的介绍.

### Oh-My-Zsh

* [ZSH Gem 24](https://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/)   -  2011年ZSH出现日历的一部分.  涵盖了oh-my-zsh和zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) -  Mike Buss关于使用Prezto的博文， [Tmux](https://tmux.github.io) 和故障排除.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) -  Linh M. Tran关于从Oh-My-Zsh过渡到Prezto的帖子.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) -  Jerome Dalbert关于迁移到Prezto的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - 一个功能丰富，闪电般快速的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)，和 [Zgen](https://github.com/tarjoilija/zgen).
* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用ZSH的简单快速入门 [zgen](https://github.com/tarjoilija/zgen) .  这包括一个策划的插件集合，并将自动配置ZSH使用 [zgen](https://github.com/tarjoilija/zgen) 加载它们，配置 [zgen](https://github.com/tarjoilija/zgen) 定期自动更新自身，插件和快速入门工具包本身.

## Plugins

* [256color](https://github.com/chrissicool/zsh-256color)   - 使用256色增强终端环境.  它查看所选的`TERM`环境变量，并查看是否有可用256种颜色的相应ncurses&#39;terminfo.  结果是多色终端（如果有的话）.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - 从一些oh-my-fish主题中添加`theme_title_use_abbreviated_pa​​th`参数的功能.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - 提供类似于`vim`缩写扩展的功能.
* [accurev](https://github.com/dalefukami/accurev-zsh) -  ZSH插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - 让呼叫变得更容易 [actiona](https://github.com/Jmgr/actiona)  命令行中的脚本.  包括标签完成.
* [alehouse](https://github.com/sticklerm3/alehouse) - 包含短的别名 [brew](https://brew.sh) 命令，受到启发 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - 一个oh-my-zsh插件，用于帮助记住您定义过的那些别名.
* [allergen](https://github.com/stanislas/allergen) - 与Antigen一起使用的自定义ZSH插件的集合.
* [almostontop](https://github.com/Valiev/almostontop)   - 每次在shell中执行新命令之前清除以前的命令输出.  灵感来自于 [alwaysontop](https://github.com/swirepe/alwaysontop) &#39;bash`的插件.
* [ansible](https://github.com/sparsick/ansible-zsh) - 一个插件 [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - 终端天气，ANSI颜色和Unicode符号.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) -  Antigen / ZSH脚本，以帮助`git` rebasing.
* [antigen-git-store](https://github.com/smallhadroncollider-deprecated/antigen-git-store)   - 用于存储`git`当前工作目录的Antigen / ZSH脚本.  用于在两台计算机之间使用`git`而不强制任意提交.
* [anyframe](https://github.com/mollifier/anyframe) -  ZSH的peco / percol / fzf包装插件.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理Apache2的别名和函数.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 添加MacBook Pro触控条支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup)   - 当它在当前目录（例如你的应用程序）中检测到`docker-compose.yml`或`Vagrantfile`时，添加`start`，`stop`，`up`和`down`命令.  只需运行`up`并获得编码！
* [artisan](https://github.com/jessarcher/zsh-artisan) -  ZSH的Laravel`artisan`插件可帮助您从项目树中的任何位置运行`artisan`，并完成选项卡！
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) -  AsciiDoctor的插件.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 整合和完善 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持Ruby，Node.js，Elixir，Erlang等.
* [assume-role](https://github.com/weizard/assume-role)   -  ZSH插件，允许您轻松承担AWS IAM角色.  包括完成.
* [async](https://github.com/mafredri/zsh-async)   - 用于在ZSH中运行异步任务的库，无需任何外部工具.  允许您运行多个异步作业，强制执行唯一作业（同一作业的多个实例不会运行），刷新所有当前正在运行的作业并创建多个工作程序（每个都有自己的作业）.
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) 插件，允许您启动文件或文件夹 [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
* [atom](https://github.com/kingsj/atom_plugin.zsh) - 一个插件 [Atom](https://atom.io) macOS编辑.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - 使用`colorls`自动列出目录.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh)   - 自动完整单词和列表选择.  最初由y.fujii incr-0.2.zsh <y-fujii at mimosa-pudica.net>  .
* [auto-ls](https://github.com/desyncr/auto-ls) - 当cding到一个新目录时自动`ls`.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - 在长时间运行的任务完成后自动发送通知.
* [autodotenv](https://github.com/nocttuam/autodotenv) - 当你“cd”到包含`.env`文件的目录时，会提示你加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - 扩展版本 [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - 如果一个目录包含一个`.env`文件，它会在你`cd`时自动执行.
* [autojump](https://github.com/wting/autojump)   - 学习的`cd`命令 - 轻松地从命令行导航目录.  安装autojump-zsh以获得最佳效果.
* [autopair](https://github.com/hlissner/zsh-autopair)   - 一个ZSH插件，用于自动关闭，删除和跳过匹配的分隔符.  仅在ZSH 5.0.2或更高版本上测试过.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)类似于ZSH的快速/不显眼的自动建议.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) -  ZSH插件在遍历目录时自动切换python virtualenvs和pipenvs.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)   -  Antigen不会像oh-my-zsh那样进行自动更新.  此插件添加抗原的自动更新，抗原和配置中加载的束.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - 哦-my-zsh不会自动更新非核心插件，这会增加插件自动更新到oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - 基于sweharris的AWS CLI MFA插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa).
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) -  AWS MFA插件.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - 使用`aws-upload`提高工作效率.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault).
* [background](https://github.com/zpm-zsh/background) -  ZSH插件，它在后台执行功能.
* [base16](https://github.com/chriskempson/base16-shell)   - 添加脚本以允许您更改shell的默认ANSI颜色，但最重要的是，更改shell的256色空间的颜色17到21（如果您的终端支持）.  这个脚本可以使你的外壳明亮的颜色（例如亮绿色仍然是绿色等），同时为应用程序提供额外的base16颜色，如 [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)   - 在你的shell中打印随机棒球相关的“有趣的事实”.  取决于&#39;fortune`和`cowsay`正在安装.
* [basex](https://github.com/dirkk/zsh-basex) - 添加几个 [BaseX](http://basex.org/) 简化用法的别名.
* [bash-quote](https://github.com/jtprog/bash-quote) - 从Bash.im获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash)   - 使ZSH更兼容Bash.  它重新定义了source命令，使其更像`bash`.  它还可以实现`bash`完成.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - 在右键提示中显示电池状态.
* [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，不做`cd ../../ ..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - 为法语重新映射ZSH`vi`模式 [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - 为&#39;brew`添加更多命令别名
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加帮助程序脚本以允许您创建bitbucket PR或在当前分支中打开目录.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)用于将密钥/凭证安全地存储在`git`存储库中的工具包.
* [branch-manager](https://github.com/elstgav/branch-manager) - 用于管理`git`分支的插件.
* [brew](https://github.com/wolffaxn/brew-zsh-plugin) - 独立插件 [Homebrew](https://brew.sh/) 包管理器.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，允许您从命令行打开浏览器中的任何提交.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - 一个在命令行中切换optirun的插件.
* [calc](https://github.com/arzzen/calc.plugin.zsh) -  ZSH的计算器.
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm`的包装，可添加垃圾/回收和有用的警告.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - 一个ZSH插件``cd`到`git`存储库根目录.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - 当`cd`到指定目录时显示提醒.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个ZSH插件，可以`cd`到当前存储库checkout的根目录.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你意外地“cd”它时，`ssh`到服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) - 一个ZSH插件，允许轻松命名目录创建 - 您想要的任何目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc) - 用于将目录更改为常用位置的Shell函数.
* [cdr](https://github.com/willghatch/zsh-cdr) - 轻松设置ZSH的cdr.
* [change-case](https://github.com/mtxr/zsh-change-case)   - 用于在命令行中快速交换大小写的插件.  ：墨镜：
* [check-deps](https://github.com/zpm-zsh/check-deps)   -  ZSH插件的助手，允许他们展示如何安装任何缺少的依赖项.  适用于Debian（以及Ubuntu等衍生产品），Arch及其衍生产品，Nodejs和ZSH插件，如果您使用的话 [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [clean-project](https://github.com/wwilsman/zsh-clean-project)   - 从项目中删除文件（默认情况下自动）.  用于保持`.DS_Store`和`Thumbs.db`文件混乱您的目录.
* [clipboard](https://github.com/zpm-zsh/clipboard)   - 添加跨平台帮助程序功能以访问系统剪贴板.  适用于macOS，X11（和Wayland）和Cygwin.
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) - 根据历史记录以及使用多字查询提示，移动，删除，添加命令段和搜索历史记录来构建命令.
* [code-review](https://github.com/xorkevin/code-review-zsh) - 在`git merge-base target_branch base_branch`和`target_branch`上启动`git difftool`.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - 分叉 [robbyrussell/oh-my-zsh/plugins/colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) .  着色`man`输出.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 着色`man`页面.
* [colorize](https://github.com/zpm-zsh/colorize) - 着色各种程序的输出.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors)   - 使从CLI中着色文本变得更容易.  `red foo`正常运作.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - 增强ZSH的颜色.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) -  oh-my-zsh命令未找到插件的镜像，因此您不必包含所有omz.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - 记录复杂的命令并对它们进行评论.
* [command-time](https://github.com/popstas/zsh-command-time) - 显示ZSH和中的长命令的执行时间 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator)   - 此插件尝试从程序的帮助文本中读取选项列表，并自动生成完成功能.  请注意，这不会自动执行，您必须显式调用生成器来创建完成脚本.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个ZSH插件，可以通过`ssh`将shell配置复制到另一台机器上.
* [crash](https://github.com/molovo/crash) - 为ZSH添加适当的错误处理，异常和try / catch.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于Wordpress的Crayon插件的ZSH语法高亮显示.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格分段.
* [crystal](https://github.com/veelenga/crystal-zsh) - 一个插件 [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - 一个简单的http服务器，用99.9％的纯ZSH编写.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - 收集有用和有趣的命令，以改善工作流程和生活质量.
* [deer](https://github.com/Vifon/deer) -  ZSH的文件导航器受到了很大的启发 [ranger](https://ranger.github.io/).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)   - 用于安装chromium depot_tools的简单oh-my-zsh插件.  安装此插件会自动将所有chrome depot_tools放入您的路径中.
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) - 简化将“diff-so-fancy”项目安装到您的用户帐户中.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - 允许您将简短的逻辑/助记符名称映射到目录以快速访问它们，或在其中执行操作.
* [dircolors-solarized](https://github.com/joel-porquet/zsh-dircolors-solarized) -  Solarized dircolors插件，可选择黑色或浅色终端背景.
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环浏览目录堆栈.
* [directory-history](https://github.com/tymm/zsh-directory-history) -  ZSH的每个目录历史记录.
* [dirrc](https://github.com/gmatheu/shell-plugins) - 当你在`cd`目录中出现时执行`.dirc`.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在单行显示dirstack信息的插件.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker别名用于日常使用.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在提示中显示docker容器状态.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) -  docker helper脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) -  ZSH的docker-machine插件.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - 回到“自然”运行命令，我们将处理容器.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) -  Dogification插件.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用`git`在多台机器上保持dotfiles同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - 当你把&#39;cd`放到一个目录中时，自动切换到一个位于你以前用virtualenv程序创建的python虚拟环境中的一个名为`.pyvenv`的目录.
* [dropbox](https://github.com/zpm-zsh/dropbox) -  ZSH的Dropbox插件，提供`dropbox-cli`和`dropbox-uploader`命令.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
* [dwim](https://github.com/oknowton/zsh-dwim)   -  zsh-dwim试图预测下一步你想做什么.  它提供了一个键绑定（control-u），它将使用您希望接下来运行的命令替换当前（或上一个）命令行.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - 列出EC2实例和`ssh`轻松登录实例.
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) - 添加理智，复杂的命令行编辑（例如增量历史_word_完成）.
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - 为快捷键，IEX，混音，低调和凤凰城再添灵药.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - ：scream：在命令行上完成表情符号.
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 在方便的变量中为您的环境添加众多ascii art emojis.
* [enhancd](https://github.com/b4b4r07/enhancd) - 一个提供增强的`cd`命令的简单工具.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - 双击“`”时快速插入逃脱的反推.
* [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助降低shell启动时间.
* [exa](https://github.com/DarrinTisdale/zsh-aliases-exa) - 启用多个扩展别名 [exa](https://the.exa.website)，&#39;ls`的现代替代品.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - 使用空格扩展特定别名.
* [explain-shell](https://github.com/gmatheu/shell-plugins) - 打开命令 [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - 中断版本的版本 [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有的oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)   - 帮助记住您定义和忘记的别名.  来自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - 优化和改进`zsh-users / zsh-syntax-highlighting`  - 更好的响应时间，可切换的高亮主题.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) -  ZSH的Unicode符号.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示符中添加一个指示符，表明您所在的目录中包含`firebase.json`文件（又名“firebase项目”）.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - 在Firebase项目目录或子目录中显示当前工作项目或项目别名.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 允许在ZSH中识别Apple键盘的小键盘键.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [forgit](https://github.com/wfxr/forgit) - 用于`git`的实用工具，它利用模糊查找器 [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) -  ZSH高阶函数.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - 用于模糊搜索文件的ZSH插件，并立即在匹配的行上打开匹配的文件.
* [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)选项卡完成后，您可以轻松地在历史目录中跳转.
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) 和（可选） [bat](https://github.com/sharkdp/bat) .  在子目录的本地树中搜索文件.
* [fzf-git](https://github.com/hschne/fzf-git) - 使用添加好的`git`完成 [fzf](https://github.com/junegunn/fzf).
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - 使用模糊查找器在“bash”和“zsh”中创建，导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
* [fzf-mpd](https://github.com/anders-dc/fzf-mpd/) - 一个允许您控制的ZSH插件 [mpd](https://www.musicpd.org/) 运用 [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - 添加一些ZLE小部件 [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - 将* z *插件和* fzf *结合在一起，以便您可以在命令行的任何位置轻松浏览最近使用的目录.
* [fzy](https://github.com/aperezdc/zsh-fzy) - 使用的插件 [fzy](https://github.com/jhawthorn/fzy) 用于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) - 轻松选择Google Cloud项目.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH的插件.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry)  datetime插件.  在提示中显示datetime（`date` unix命令）.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 插件提醒你保湿.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 插件显示当前文件夹的npm包版本.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) 当存在`.rs`或`Cargo.toml`时，插件显示当前文件夹的Rust版本.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 从中​​快速下载jQuery库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - 让您使用 [zeus](https://github.com/burke/zeus) 使用普通的rails命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - 使用gimme管理Go安装.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游遥控器添加到您的`git`前叉.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - 中断版本的版本 [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有的oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - 为常用的`git`命令组合创建许多有用的别名.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - 增强`git`完成以包括在遥控器完成（例如来自`git clone`）剪贴板中的任何URL.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 作为插件打包的额外`git`帮助程序脚本.
* [git-ignore](https://github.com/laggardkernel/git-ignore)   - 从gitignore.io **离线**生成`.gitignore`文件.  `fzf`，完成，预览集成.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - 添加在GitHub上打开当前分支中的文件夹的功能.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - 为`git`添加一些功能.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - 为`git` user.email添加提示符.
* [git-prune](https://github.com/Seinh/git-prune) - 简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - 添加`git-squash-branch`和`git-remove-merged`命令.
* [git-secret](https://github.com/sobolevn/git-secret) - 用于将私有数据存储在`git`存储库中的bash工具.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - 添加额外的`git`命令，使一些常见的`git`用法更有效.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - 一个ZSH插件，用于同步`git`存储库并清理它们.
* [gitcd](https://github.com/viko16/gitcd.plugin.zsh) - 克隆后cd到一个`git`工作目录.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - 更新了oh-my-zsh gitfast插件的分支.
* [gitgo](https://github.com/ltj/gitgo) - 从命令行（仅限macOS）在浏览器中打开Github / Gitlab存储库.
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建`.gitignore`文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - 一个ZSH插件，用于生成GitHub短URL [git.io](https://git.io).
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 分叉 [original Gitster](https://github.com/robbyrussell/oh-my-zsh/wiki/External-themes#gitster).
* [gitsync](https://github.com/washtubs/gitsync) -  ZSH插件，用于改善在多台计算机上的同一存储库上开发的人员的工作流程.
* [goenv](https://github.com/bbenne10/goenv) - 与Python的virtualenvwrapper类似，管理`$ GOPATH`的Antigen插件.
* [going_places](https://github.com/or17191/going_places) - 一个有助于使用，创建和维护shell位置列表的插件.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - 在设置GPG代理以及在macOS上充当SSH代理时尝试做正确事情的插件.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) -  ZSH插件，用于加密和解密文件或目录.
* [grep2awk](https://github.com/joepvd/grep2awk) -  ZLE小部件将`grep`命令转换为`awk`命令.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为&#39;grunt`添加自动完成功能.
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - 包装插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) -  ZSH的gvm（Go版本管理器）插件.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为`gvm`（Groovy enVironment Manager）提供自动完成功能.
* [hab](https://github.com/alexdesousa/hab) - 如果在更改为新目录时找到，则自动加载在文件`.envrc`中定义的OS环境变量.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - 打开终端时随机输出黑客报价.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 为hadoop函数添加一些便利别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) -  ZSH插件 [hanami](http://hanamirb.org) 项目.
* [hints](https://github.com/joepvd/zsh-hints) - 在编辑缓冲区下方显示glob和参数标志以及其他不可完成的信息.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - 从shell发送hipchat消息.
* [histdb](https://github.com/larkery/zsh-histdb) - 将您的历史记录存储在SQLite数据库中.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)   - 允许您指定将自动排除命令插入永久历史记录的模式.  特别适用于防止写入秘密.
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) - 语法突出显示，ZSH的多字历史搜索器，绑定到Ctrl-R，具有高级功能（例如，历史记录进入历史记录顶部）.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)   - 需要在`zsh-syntax-highlighting`之后加载，否则它们都会中断.  您还需要将键绑定到其函数，详细信息在README.md中.
* [history-sync](https://github.com/wulfgarpro/history-sync) - 使用`git`为GPG加密，互联网同步ZSH历史的Oh My Zsh插件.
* [history](https://github.com/b4b4r07/zsh-history) - 扩展历史记录，以便SQL可以查询它.
* [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺失的钩子 - 用于插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) - 在开发过程中更容易切换到不同的`/ etc / hosts`文件.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - 一个简单的插件，用于为您的ZSH主题添加`hub` ci-status.
* [igit](https://github.com/ytakahashi/igit) - 使用交互式`git`命令 [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - `ping`，但输出更短.
* [intellij](https://github.com/mgryszko/intellij) - 将intellij书签提取为markdown格式.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - `cd`的鱼状交互式标签完成.
* [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序，数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 添加功能以在iTerm2中设置标签颜色，并可根据正在执行的cwd或命令自动更改颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - 根据当前工作目录自动更改iTerm 2选项卡颜色.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - 在MacbookPro TouchBar中显示iTerm2反馈（当前目录，git分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - 从命令行管理iTerm 2的配色方案.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - 设置iTerm 2选项卡的颜色和标题.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将iTerm的ZSH集成脚本打包到ZSH插件中，以避免污染您的$ HOME目录，可忽略不计的时间增加仅2ms.
* [jabba](https://github.com/2m/zsh-jabba) - 添加shell集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java版本管理器.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加`setjdk`命令，以便您可以在不同版本的jdk之间轻松切换.
* [javaVersions](https://github.com/miguefl/javaVersions) - 使用单个命令在不同的Java版本之间进行更改.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - 用于在jdk版本之间切换的macOS-only插件.
* [jenkins](https://github.com/tomplex/jenkins-zsh) -  ZSH的jenkins插件，受到优秀jira插件的启发.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - 一个用于延迟加载jEnv的ZSH插件.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - 添加命令 [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - 从命令行创建JIRA票证.
* [jvm](https://github.com/mgryszko/jvm) - 允许在macOS上选择JDK.
* [k](https://github.com/supercrabtree/k) - 使用`git`状态装饰的ZSH目录列表.
* [kill-node](https://github.com/vmattos/kill-node) - 用于谋杀`node`进程系列的ZSH插件.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - 用于oh-my-zsh的KitsuneBook插件.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - 从ZSH切换konsole主题.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - 用于添加当前上下文和命名空间的`kubectl`的ZSH插件.
* [kubecolor](https://github.com/droctothorpe/kubecolor) - 简化和着色`kubectl get events -w`的输出
* [kubectl-zsh-plugin](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理`kubectl`的ZSH插件.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) 辅助函数和别名.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - 提供接口 [Laradock](http://laradock.io/)的工作空间.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - 为Laravel 5,5.1,5.2和5.3添加快捷方式.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - 中断版本的版本 [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有OMZ.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - 延迟加载命令并加快ZSH的启动时间.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - 为Oh-My-Zsh兼容的框架替换`git`插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - 用于oh-my-zsh的Maven插件.
* [linuxbrew](https://github.com/zpm-zsh/linuxbrew) -  ZSH插件 [linuxbrew](http://linuxbrew.sh/).
* [listbox](https://github.com/gko/listbox) -  shell的Listbox元素.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - 允许搜索 [Sublime Text](https://www.sublimetext.com) 项目并在Sublime中打开它们.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)   - 在命令行上生成lorem ipsum文本.  从中获取数据 [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - 着色“ls”的输出.
* [lumberjack](https://github.com/molovo/lumberjack) -  Lumberjack是shell脚本的日志记录界面.
* [lux](https://github.com/pndurette/zsh-lux)   -  ZSH插件，通过`lux`命令切换macOS和其他项目和应用程序的明暗模式.  高度可定制：可以通过定义变量来配置包含的项目.  高度可扩展：可以通过定义函数来添加项目.  包括`macos_is_dark`辅助函数，用于确定macOS暗模式是否有效用于主题.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - 用于企业Mac包装的一组常用功能 [Munki](https://www.munki.org/munki/).
* [macos](https://github.com/joow/macos) -  macOS的ZSH插件.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 使用Docker和Magento轻松工作2.加快并简化常见命令，如清理缓存，设置升级，编译等，以及容器上的Magento 2等.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加`m2`函数来运行magento binary，添加制表符完成.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - 用于模拟`...&#39;==`../ ..&#39;等的zle调整
* [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用自动完成功能对现有标记进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) -  oh-my-zsh maven插件的一个分支.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - 从oh-my-zsh中提取，这样你就可以在没有oh-my-zsh的情况下使用它.
* [mfunc](https://github.com/hlohm/mfunc)   - 允许您即时定义持久性功能，而无需将其添加到配置文件中.  在删除它们之前，这些功能将永久可用.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 用于在正常模式和`vi`模式之间切换命令行的ZSH插件.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - 用于monorepo管理的ZSH插件.
* [morpho](https://github.com/psprint/zsh-morpho) - 使用纯ZSH编写的终端屏幕保护程序，以及屏幕保护程序框架.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) -  Metasploit处理程序插件，可轻松启动处理程序.
* [mylocation](https://github.com/fALKENdk/mylocation) - 根据您的IP地址显示当前位置的插件.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - 为mysql表添加颜色.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - 添加一些处理mysql的函数.
* [n](https://github.com/gretzky/n.zsh) - 使用基于项目环境自动切换节点版本 [n](https://github.com/tj/n).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) - 添加`htop`-like`shill`，目录书签浏览器，多字增量历史搜索器等.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - 允许您使用ZSH作为默认`nix-shell` shell的插件.
* [node](https://github.com/srijanshetty/node.plugin.zsh) -  Srijan Shetty用于ZSH的nodejs插件，缓存`nvm`完成并自动加载`nvm`（如果存在）.
* [nodenv](https://github.com/jsahlen/nodenv.plugin.zsh) - 自动加载`nodenv`及其完成到shell中.
* [nohup](https://github.com/micrenda/zsh-nohup) - 按“Ctrl-H”将“nohup”添加到当前命令.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) -  macOS用户知道试图弄清楚什么命令实际刷新他们的macOS版本上的DNS缓存的痛苦，而这个插件让烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的界面来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) 目录中的文本文件.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在ZSH中提供快速的笔记编辑体验.
* [notify](https://github.com/marzocchi/zsh-notify) -  ZSH（在macOS和Linux上）的插件，当命令以非零退出状态终止时或者如果终端应用程序在后台（或命令的终端）完成时间超过30秒，则发布桌面通知选项卡处于非活动状态
* [npm](https://github.com/igoradamenko/npm.插入.zsh)   - 添加`npm`别名和命令完成.  基于Oh-My-Zsh [npm](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/npm) 插入.
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - 当你进入一个包含`.nvmrc`文件的目录时，会自动调用`nvm use`，该文件带有一个字符串，告诉`nvm`使用哪个节点.
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) - 旨在减少需要尽可能多地键入`nvm use`，特别是如果您经常在node.js版本之间切换并在项目中使用`.nvmrc`文件来管理项目所需的节点版本.
* [nvm](https://github.com/lukechilds/zsh-nvm) - 用于安装，更新和加载`nvm`的ZSH插件.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - 将您的终端转入矩阵.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - 在Jetbrains中打开/创建项目.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - 一个ZSH插件，用于从命令行打开pull请求.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - 为常见的openshift origin（oc）动作添加一些快捷方式.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git`别名.
* [operator](https://github.com/nivv/operator-theme) - 干净简洁的主题，最适合Menlo for Powerline.
* [opp](https://github.com/hchbaw/opp.zsh) -  Vim的文本对象是ZSH的.
* [opt-path](https://github.com/jreese/zsh-opt-path) - 自动将`〜/ opt`子路径添加到`$ PATH`.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 这个插件添加了一些命令，用于在我的macOS安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - 添加一些常见的macOS相关别名和功能.
* [paci](https://github.com/iloginow/zsh-paci) -  archlinux包管理器的插件.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)   - 长时间运行命令的背景通知.  支持小学OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码输入命令行历史记录.
* [pctl](https://github.com/ytet5uy4/pctl) - 切换代理的环境变量.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - 按ctrl + R时，使用Peco搜索shell历史记录.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - 使用互动和增量搜索历史/恢复后台作业 [percol](https://github.com/mooz/percol).
* [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理Python virtualenvs [pew](https://github.com/berdario/pew)，在移动目录时自动切换virtualenvs.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用程序功能 [PostgreSQL](https://www.postgresql.org/).
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - 使用自动在PHP版本之间切换 [php-version](https://github.com/wilmoore/php-version) 如果目录中存在rc文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - 自动加载 [phpenv](https://github.com/sptndc/phpenv) 及其完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - 使python应用程序安装到不同的Python virtualenvs中变得容易，因此它们不会与系统上的任何其他python需求冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - 自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) 进入pipenv项目后激活.
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加ibtool快捷方式以生成本地化的XIB文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) -  Rails的ZSH插件.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
* [plugin](https://github.com/darrenbutcher/plugin)   - 从样板模板创建自定义的oh-my-zsh插件.  非常哦-my-zsh为中心，生成的插件需要编辑才能与其他框架一起使用.
* [poetry](https://github.com/darvid/zsh-poetry) - 自动激活和停用 [Poetry](https://poetry.eustace.io/)- 创建python virtualenvs.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd)   - 使用当前工作目录创建全局变量.  插件集成了 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - 显示可以嵌入提示中的EOL符号.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - 添加可用于显示上次命令运行的执行时间的变量.
* [pr-git](https://github.com/zpm-zsh/pr-git) - 使用可在提示中显示的`git`状态信息创建全局变量.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - 设置以root用户身份运行时可在自定义提示中使用的环境变量.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - 创建一个环境变量，可用于在自定义提示中显示后台作业信息.
* [pr-node](https://github.com/zpm-zsh/pr-node) - 设置一个环境变量，可用于在自定义提示中显示nodeJS信息.
* [pr-return](https://github.com/zpm-zsh/pr-return) -  ZSH的插件，显示上次命令运行的退出状态.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode)   - 在演示期间扩展别名.  它还增加了终端窗口的对比度，以提高可视性.
* [pretty-time](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串：165392→1d 21h 56m 32s.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)   - 将敏感变量（api令牌，密码等）安全地保存为终端init文件的一部分.  使用gpg加密/解密文件与你的秘密.
* [project (gko)](https://github.com/gko/project) - 在本地和github（私有或公共存储库）上创建node / python / ruby​​项目.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - 用于管理项目的插件.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - 用于管理代理shell环境设置的别名.
* [proxy](https://github.com/SukkaW/zsh-proxy) - 配置代理设置.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - 在ZSH中加载延迟加载`pyenv`的插件.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)   - 懒惰加载pyenv.  最初的`eval&#39;$（pyenv init  - ）“`在第一次调用`pyenv`时执行.
* [q (cal2195)](https://github.com/cal2195/q) - 用于ZSH shell的`vim`-like宏寄存器.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - 为/删除/删除临时文件 [Q](https://github.com/y0ssar1an/q)，脏调试工具.
* [quoter](https://github.com/pxgamer/quoter-zsh) - 打开新的终端会话时显示随机引用.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - 启动时显示来自我们对的鼓舞人心的编码引号.
* [randeme](https://github.com/ex-surreal/randeme)   - 为每个会话选择一个随机主题.  如果您不喜欢所选择的主题，您可以运行`randeme_rm`以永远不再显示该主题.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - 改变你的颜色 [Razer Mouse](https://openrazer.github.io/)  根据上次执行的命令的状态.  需要 [OpenRazer](https://openrazer.github.io) linux驱动程序.
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自oh-my-zsh的rbenv插件的快速分支.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - 基于原始oh-my-zsh rbenv插件的变体.
* [redis](https://github.com/zservices/redis)   - 运行`redis-server`将它指向`redis.conf`配置文件.  这可以用于 [zdharma/zredis](https://github.com/zdharma/zredis) 插件在shell之间共享变量.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - 如果已删除并重新创建工作目录，则重新进入工作目录的插件.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - 一个插件，在每个提示上方显示提醒.
* [revolver](https://github.com/molovo/revolver) -  ZSH脚本的进度微调器.
* [ripz](https://github.com/jedahan/ripz)   - 提醒您别名，以便更多地使用它们.  依赖于取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo-zsh-plugin](https://github.com/shengyou/robo-zsh-plugin) - 一个ZSH插件 [Robo](https://robo.li/).
* [rockz](https://github.com/aperezdc/rockz) - 基于VirtualZ的Lua + LuaRocks虚拟环境管理器.
* [ruby-switch](https://github.com/LockonS/ruby-switch) - 切换ruby版本并同时管理PATH变量.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - 启动RVM并添加可在用户的`$ PATH`中访问的rubygem二进制文件（如指南针）.
* [safe-paste](https://github.com/oz/safe-paste)   - 一个安全粘贴插件.  见康拉德欧文 [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [saneopt](https://github.com/willghatch/zsh-saneopt) -  Sane默认为ZSH选项，本着vim-sensible的精神.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - 在提示中显示当前的`chroot`名称.
* [select](https://github.com/psprint/zsh-select) - 具有近似匹配和uniq模式的多项搜索选择列表.
* [send.zsh](https://github.com/robertzk/send.zsh) - 单个命令`git add`，`git commit`和`git push`，以便更快地实现`git`工作流程.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - 添加许多`git`别名和辅助shell函数.
* [setenv](https://github.com/kalpakrg/setenv) - 更改目录时运行脚本.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - 插件轻松启动python SimpleHTTPServer和SimpleHTTPSServer.
* [slugify](https://github.com/lashoun/slugify) -  ZSH插件，将文件名和目录转换为Web友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - 在chpwd之后运行`ls`和`git status`.
* [snippets](https://github.com/willghatch/zsh-snippets) - 命令行代码段扩展.
* [solarized-man](https://github.com/zlsun/solarized-man) -  oh-my-zsh的插件彩色手册页的修改版本，针对该版本进行了优化 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端的主题.
* [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的`ssh`经理.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - `ssh`的插件.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - 打印shell启动所需的时间.
* [stashy](https://github.com/MisterRios/stashy) - 插件简化了使用`git stash`.
* [statify](https://github.com/vladmrnv/statify) - 进行基本统计分析的插件.
* [sublime](https://github.com/valentinocossar/sublime) - 与Oh My Zsh的官方Sublime插件相同，但如果有一个已经打开的话，这会打开当前Sublime窗口中的文件.
* [sudo](https://github.com/hcgraf/zsh-sudo)   - 来自oh-my-zsh的`sudo`插件，被提取为独立的.  在emacs-mode或vi-command模式下按* ESC-ESC *，在当前/上一个命令之前切换`sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用ZSH的后缀别名直接打开shell中的文件.
* [symfony](https://github.com/voronkovich/symfony.plugin.zsh) -  Symfony 2和3的ZSH插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - 使用dircolors实时突出显示ZSH语法.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)   - 为您的ZSH添加语法高亮显示.  确保加载此_before_ zsh-users / zsh-history-substring-search，否则它们都会中断.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - 用于目录更改或编辑器启动的ZSH插件，仅使用小部件进行键操作而无需键入命令.
* [sysadmin-util](https://github.com/skx/sysadmin-util) -  Steve Kemp为系统管理员提供的工具脚本集.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard)   - 为vi仿真键映射添加ZLE（Zsh行编辑器）剪贴板操作的键绑定支持.  它适用于Linux，macOS和Android（通过Termux）.
* [t32](https://github.com/chrissicool/zsh-t32)   -  Lauterbach Trace32工具集的插件.  它会自动注册字体并设置所有必要的环境变量来运行t32工具集.
* [tailf](https://github.com/rummik/zsh-tailf) - 添加带有前缀换行符的`tailf`函数，而不是尾随换行符.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - 自动完成任务簿的任务编号.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - 用于集成新El Capitan Terminal.app功能的插件.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 一个插件，用于计算和显示已通过终端运行的命令数.
* [terraform](https://github.com/pbar1/zsh-terraform) -  ZSH的Terraform便利功能和别名.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt)，一个薄的包装 [Terraform](https://terraform.io/) 这提供了额外的工具.
* [thefuck](https://github.com/laggardkernel/thefuck) - 载荷 [thefuck](https://github.com/nvbn/thefuck) （一种纠正您之前命令的工具）具有缓存支持，可显着减少加载时间.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - 使用便利功能 [theia-ide](https://github.com/theia-ide/theia).
* [timewarrior](https://github.com/svenXY/timewarrior) - 插件 [timewarrior](https://timewarrior.net/) 时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) - 如果您有刚刚运行的命令的别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - 允许您设置终端窗口标题.
* [titles](https://github.com/jreese/zsh-titles) - 自动窗口和标签标题 [tmux](https://tmux.github.io) 和xterm兼容的终端.
* [tmux-fork](https://github.com/sharktamer/zsh-tmux) oh-my-zsh tmux插件的独立分支.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 支持单个服务器进程上的多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - 改名 [tmux](https://tmux.github.io) 窗户自动.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 简单的插件使用 [tmux](https://tmux.github.io) 与ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - 从相邻的`tmux`窗格打开正在运行的`vim`（或NeoVim）会话中的文件.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - 为`tmux`，ZSH和Vim / NVIM创建统一的终端标题，模块化.
* [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 具有R-EP-L tmux会话的简单ZSH插件.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - 添加`toggl-week`命令以显示跟踪的总工作时间 [toggl.com](https://toggl.com)
* [travis](https://github.com/denolfe/zsh-travis) - 打开当前仓库的Travis CI页面（如果存在）.
* [tsm](https://github.com/RobertAudi/tsm) - 添加一个 [tmux](https://tmux.github.io) 会话管理器.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - 为macOS添加工具.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) -  Ubuntu 16别名.
* [undollar](https://github.com/zpm-zsh/undollar) - 从终端提示的开头剥去美元符号.
* [up.zsh](https://github.com/peterhurford/up.zsh) - 向&#39;cd`添加一个up命令.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter)   -  ZSH语法荧光笔的插件，如果它们以“良好”状态响应，则将URL变为绿色，否则为红色.  用于检查URL拼写错误.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - 扩展原始oh-my-zsh venv模块的功能.
* [vanilli.sh](https://github.com/yous/vanilli.sh) -  shell配置的轻量级起点.
* [velocity](https://github.com/rahulsalvi/velocity-python) -  ZSH和.的基于电力线的主题元素 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - 超轻量级的克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ;  它非常希望你能使用它 [pyenv](https://github.com/pyenv/pyenv) （虽然你没有*到*），因为它是基于 [`venv` module](https://docs.python.org/3/library/venv.html)，（创建）仅适用于python&gt; = 3.3.
* [vi-mode (Nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的`vi`类功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 为ZSH添加更多类似&#39;vi`的功能.
* [viexchange](https://github.com/okapia/zsh-viexchange) - `vi`模式插件，用于在缓冲区中的两个位置之间轻松交换文本，如vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - 友好的`vi`模式绑定，添加基本的Emacs键，增量搜索，模式指示器等.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - 允许你做`vim filename：123`来打开一个光标位于特定行的文件.
* [vimman](https://github.com/yonchu/vimman) - 在ZSH中查看`man`插件手册（帮助）.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 为oh-my-zsh修改的virtualenv ZSH插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt)   - 来自上游的virtualenv插件的一个分支.  在oh-my-zsh主题中添加了对自定义virtualenv提示的支持.
* [virtualz](https://github.com/aperezdc/virtualz) -  Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 经理受到Adam Brenecki的启发 [Virtualfish](https://github.com/adambrenecki/virtualfish) 为了 [Fish shell](http://fishshell.com/)，取代virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - 一个oh-my-zsh插件 [virtuozzo](https://docs.virtuozzo.com/master/index.html) 裸机虚拟化系统.
* [visit](https://github.com/justinpchang/visit) - 自定义插件，以加快导航速度.
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个控制的oh-my-zsh插件 [VOX](https://vox.rocks/)，一款适用于macOS的轻量级全功能音频播放器，可播放各种格式，包括FLAC和Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) -  macOS上的Visual Studio Code插件.
* [vscode](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
* [wack](https://github.com/leoxlin/wack) - 包装`ack`命令.
* [wakatime-zsh-plugin](https://github.com/sobolevn/wakatime-zsh-plugin) - 跟踪多少 [time](https://wakatime.com/)  你已经在你的终端上度过了.  有每个项目的统计数据.
* [wakatime](https://github.com/wbingli/zsh-wakatime) - 使用ZSH自动跟踪命令 [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色 [grc](https://github.com/garabik/grc).
* [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) 时间管理系统.
* [wd](https://github.com/mfaerevaag/wd)   -  Warp目录允许您跳转到ZSH中的自定义目录，而不使用`cd`.  为什么？  因为当经常访问文件夹或路径很长时，`cd`似乎效率低下.
* [web-search](https://github.com/sinetoami/web-search) - 添加命令以直接从CLI运行bing，google，yahoo和duckduckgo搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - 使用`git blame`突出显示文件中最后一次更改的位置.
* [windows-title](https://github.com/mdarocha/zsh-windows-title/issues) - 使用当前目录和最后一个命令运行动态更新终端窗口标题.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - 在项目之间跳转的简单实用程序.
* [yadm](https://github.com/juanrgon/yadm-zsh) - 如果存在本地yadm配置更改，则显示警告.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - 如果`pipenv`检测到存在一个pip环境，则自动激活目录的pip环境.
* [yeoman-zsh-plugin](https://github.com/edouard-lopez/yeoman-zsh-plugin) -  Edouard Lopez用于oh-my-zsh的Yeoman插件，兼容yeoman版本≥1.0（包括选项和命令自动完成）.
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) -  ZSH插件，提醒您使用您定义的别名.
* [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
* [z.lua](https://github.com/skywind3000/z.lua)   - 一个命令行工具，通过学习您的习惯，帮助您更快地导航.  替代 [z.sh](https://github.com/rupa/z) 与windows和posix shell支持和各种改进.
* [zaw](https://github.com/zsh-users/zaw) -  ZSH anything.el-like小部件.
* [zce](https://github.com/hchbaw/zce.zsh) -  Vim的EasyMotion / Emacs的ZSH ace-jump-mode.
* [zconvey](https://github.com/zdharma/zconvey) - 添加向其他ZSH会话发送命令的功能，例如，您可以在所有活动的Z shell会话中使用它来“cd $ PWD”.
* [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装 [z](https://github.com/rupa/z) 通过ZSH插件安装它.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - 针对深色背景进行了优化，包括`git`状态信息.
* [zero](https://github.com/arlimus/zero.zsh)   - 零既是插件又是主题.  有关安装的详细信息，请参阅github页面.
* [zgdbm](https://github.com/zdharma/zgdbm) - 将GDBM添加为插件.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 在完成所有加载后，仅使compinit运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) -  zimfw的自定义附加功能，打包成zimfw插件.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为ZSH主题提供更多信息.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zredis](https://github.com/zdharma/zredis)   - 添加Redis数据库支持，使用`database_key` &lt; - &gt;`shell_variable`绑定.  支持所有数据类型.
* [zsh-z](https://github.com/agkozak/zsh-z)   - 快速跳转到“访问频繁”的目录.  `z.sh`的原生ZSH端口 - 没有&#39;awk`，`sed`，`sort`或`date`.
* [zshmarks](https://github.com/jocelynmallon/zshmarks) -  Bashmarks的端口（由Todd Werth提供），一个简单的命令行书签插件，用于oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - 从项目范围加载本地`.zshrc`文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 在Arch Linux上获取ZFS前/后升级快照的插件.
* [zsnapshot](https://github.com/psprint/zsnapshot) - 添加命令以将当前ZSH状态转储到文件中，以便稍后通过获取快照文件进行恢复.
* [ZUI](https://github.com/zdharma/zui/) -  ZSH用户界面库 - 使用ZSH进行CGI + DHTML快速TUI应用程序开发.

## Completions

这些插件在不添加额外功能或别名的情况下添加选项卡完成.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展ZSH的\ _urls完成，允许它从html页面完成网址.
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) -  viasite-ansible / ansible-server的完成.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - 此插件提供完成 [Antibody](https://github.com/getantibody/antibody) 插件管理器.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) -  autopkg的完成.
* [aws-plugin](https://github.com/eastokes/aws-plugin-zsh) - 为`awscli`添加完成支持，以管理AWS配置文件/区域并在提示中显示它们.
* [aws_manager_plugin](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为aws_manager CLI添加完成.
* [berkshelf-zsh-plugin](https://github.com/berkshelf/berkshelf-zsh-plugin) - 为berkshelf添加标签完成.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好的标签完成`npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - 添加BOSH自动完成功能.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - 自制服务的完成插件.
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - 为cabal添加标签完成.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - 为cabal添加自动完成功能.
* [carthage](https://github.com/squarefrog/zsh-carthage) - 提供完整性和别名以供使用 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete-plugin](https://github.com/Dannyzen/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [codeception-zsh-plugin](https://github.com/shengyou/codeception-zsh-plugin) - 为Codeception测试框架添加命令完成.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示git信息，无论您是通过`ssh`登录，还是返回上一个命令的代码.
* [completions](https://github.com/zsh-users/zsh-completions) -  ZSH的额外完成集合.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 标签完成 [ctop](https://github.com/bcicen/ctop).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - 自动为DBIx :: Class :: Migration的脚本和Dancer设置环境变量.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - 命令完成 [docker-enter](https://github.com/jpetazzo/nsenter).
* [docker-zsh-completion](https://github.com/felixr/docker-zsh-completion) - 为docker添加完成.
* [dropbox](https://github.com/zpm-zsh/dropbox) -  Zsh的Dropbox插件，提供`dropbox-cli`和`dropbox-uploader`命令.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) -  ZSH的Drush自动完成功能非常棒.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - 一个ZSH插件 [duell](https://github.com/gameduell/duell).
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - 添加etcdctl选项卡完成.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](https://exercism.io/).
* [extract](https://github.com/thetic/extract) -  oh-my-zsh提取插件的分叉.
* [fly-zsh-autocomplete-plugin](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - 为所有人添加自动完成选项 [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [gcloud-zsh-completion](https://github.com/littleq0903/gcloud-zsh-completion) - 为Google Cloud SDK添加完成功能.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - 为缺少上游完成脚本的各种Gentoo工具提供ZSH完成支持.
* [git-annex-completion](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数git-annex命令的选项卡完成.
* [git-flow-completion](https://github.com/bobthecow/git-flow-completion) - 针对git-flow的ZSH完成支持.
* [gradle-completion (eriwen)](https://github.com/gradle/gradle-completion) -  Bash和ZSH完成对gradle的支持.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) -  ZSH完成对gradle的支持.
* [grid5000-zsh-plugin](https://github.com/pmorillon/grid5000-zsh-plugin) -  Grid 5000插件 - 添加主题，自动填充.
* [gulp-autocompletion](https://github.com/srijanshetty/gulp-autocompletion-zsh) - 吞咽自动完成.
* [gulp](https://github.com/akoenig/gulp.plugin.zsh) - 在Z-Shell（ZSH）中自动完成gulp.js任务.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - 完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) -  haxelib的完成.
* [ipfs](https://github.com/aramboi/zsh-ipfs) - 完成 [Interplanetary File System](https://ipfs.io).
* [joe-completion](https://github.com/corvofeng/joe-completion) - 添加完成 [joe](https://github.com/karan/joe) gitignore编辑.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) -  ZSH完成jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成功能 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [kafka](https://github.com/Dabz/kafka-zsh-completions) -  Apache的完成 [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - 完成 [keybase](https://keybase.io/docs/command_line).
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - 添加标签完成 [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - 添加标签完成 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [MooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) -  Perl模块`MooseX :: App`的完成生成器.
* [mx-honey](https://github.com/mukel/mx-honey) - 提供完成 [mx](https://github.com/graalvm/mx) ;  用于开发Graal项目的命令行工具.  它旨在改进通常的工作流程`构建unittest基准......轻松发现并提供方便的别名.
* [newman](https://github.com/selop/newman-autocomplete) - 提供自动完成功能 [Newman CLI](https://github.com/postmanlabs/newman).
* [nix-zsh-completions](https://github.com/spwhitt/nix-zsh-completions) - 完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)，和 [NixOps](https://nixos.org/nixops/).
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为新星提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持.
* [packer](https://github.com/wakeful/zsh-packer) - 添加标签完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) -  Pandoc完成插件.
* [parallels-zsh-plugin](https://github.com/benclark/parallels-zsh-plugin) - 为Parallels桌面添加完成.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) ZSH命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) -  pip的自动完成插件.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - 为最常见的pipenv命令启用别名.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - 完成`pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)   - 如果该目录中有Pipfile，则在进入目录时自动激活** pipenv **.  包括`pipenv`完成.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - 添加Pivotal的完成 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [racket completion](https://github.com/racket/shell-completion) - 完成 [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - 为rakefile目标添加快速选项卡完成.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - 为Rancher CLI添加完成.
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - 提供自动完成功能 [Razor](https://github.com/puppetlabs/Razor).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) -  Rustup的标签完成.
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) -  sfdx的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动填充功能 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - 管理`ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动`ssh-agent`以设置和加载`ssh`连接所需的凭据.
* [ssh](https://github.com/zpm-zsh/ssh) - 为`ssh`添加主机完成.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加冲浪的完成.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - 添加完成 [Test Kitchen](https://kitchen.ci/).
* [tmux pane words](https://gist.github.com/blueyed/6856354) - 用于完成您的单词的键绑定 [tmux](https://tmux.github.io) 面包.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成功能 [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) -  Ubuntu umake的Tab完成.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) 命令.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 纱线自动完成.

## Themes

如果你正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果你正在使用 [zgen](https://github.com/tarjoilija/zgen)，使用`zgen load githubuser / reponame`将它们添加到`init.zsh`中.

* [0i0](https://github.com/0i0/0i0.zsh-theme) - 优化黑暗终端窗口，使用nerdfont`git`状态装饰.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - 基于索林主题.
* [abbr](https://github.com/PhilsLab/abbr-zsh-theme)   - 显示当前目录路径的缩写版本，显示Python virtualenv，Rust版本，`git`状态和最后一个命令的退出代码.  默认情况下适用于深色背景，但颜色可以轻松定制.
* [absolute](https://github.com/NelsonBrandao/absolute) - 非常干净的主题与git状态，节点版本和最后一个命令的退出代码.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括`git`状态装饰，AWS配置文件的名称，Azure服务主体的名称，命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) -  macOS主题，需要与Powerline兼容的字体.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - 修改版 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh中的主题.
* [aftermath](https://github.com/schanur/aftermath) - 在shell中运行的每个命令后获得一个很好的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster theme](https://gist.github.com/3712874) 包括在 [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) .  显示有关`git`状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)   - 使用三个异步方法保持ZSH提示响应，同时显示SSH连接，退出代码和`vi`模式的`git`状态和指示符，以及缩写的`PROMPT_DIRTRIM`样式路径.  非常可定制.  即使在Cygwin和MSYS2上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - 曝光 [Agnoster](https://gist.github.com/agnoster/3712874)  带有`git`状态信息的变体.  需要unicode字体，最适合使用 [solarized](https://github.com/altercation/solarized) 终奌站.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 具有正确提示的变体.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 具有右提示的变体.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体优化使用 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors)  终端配色方案.  包括`git`状态.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 添加了时间戳和换行符的变体.
* [Agnoster](https://gist.github.com/agnoster/3712874)   - 针对曝光的终端配色方案进行了优化，显示了`git`装饰，user @ host，工作目录，上一个命令的退出状态以及是否以root权限运行.  需要与Powerline兼容的字体.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874)，显示电池寿命，日期和时间，`git`状态，当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) - 最好的黑色终端主题，包括`git`装饰.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - 显示“git”状态的极简主义ZSH主题.
* [alien](https://github.com/eendroroy/alien)   - 电力线式的ZSH主题，显示`git`装饰和最后一个命令的退出代码.  比许多其他提示更快，因为它在后台进程中异步确定`git`装饰.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - 修改版 [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) 优化使用 [solarized dark](https://github.com/altercation/solarized) 终端.
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 基于的优雅和舒适阅读主题 [Agnoster](https://gist.github.com/agnoster/3712874).
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - 在右侧提示中显示`git`信息.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - 显示`git`装饰，用户，主机，是否为root，活动Python虚拟环境，当前Ruby解释器，最后一个命令的可视和数字状态，电源管理状态以及时间和日期.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)   - 简约主题，没有视觉噪音.  仅显示必要的信息：当前用户，主机名，工作目录，`git`分支（如果存在）.  黑色和白色的终端看起来都很棒.
* [aplos](https://github.com/sunquan1991/aplos) - 带工作目录的最小ZSH提示，`git`本地信息，`git`远程信息，时间和退出代码.
* [archie](https://github.com/dcavalcante/archie)   -  Arch Linux启发了ZSH主题.  基于 [norm](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)   -  Arity是一个简单的主题，旨在提高可读性并概览一目了然.  包括路径和`git`装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - 极简主义主题与右侧`git`状态装饰.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有`git`装饰的最小ZSH主题.
* [asciigit](https://github.com/cemsbr/asciigit) - 不希望使用带有额外字形的字体的`git`用户的仅ASCII主题.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#theunraveler).
* [astral](https://github.com/alphabetum/astral) - 禅模式的深色背景主题.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于 [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 主题.
* [aterminal](https://github.com/guiferpa/aterminal) - 在提示符中显示Nodejs，NPM，Docker，Go，Python，Elixir和Ruby信息.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - 基于oh-my-zsh [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) 主题，变化很小.
* [avit-mod](https://github.com/zlsun/avit-mod) -  oh-my-zsh的修改版本 [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) 主题.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - 另一个电力线变体.
* [bar](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名，主机，pwd，`git`状态装饰和3x小时提醒饮用水.
* [bashi](https://github.com/eli-oat/bashi) - 针对AhmetSülek的优化 [Flat UI Terminal Theme](https://github.com/ahmetsulek/flat-terminal) 和Pasquale D&#39;Silva [Saturn Terminal Theme](https://github.com/psql/saturn-colors).
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - 修改版 [`gitster`](https://github.com/zimfw/zimfw/blob/master/modules/prompt/themes/gitster.zsh-theme) 主题为 [ZIM](https://github.com/zimfw/zimfw#installation).
* [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于黑暗的终端背景.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme)，但有啤酒图标.
* [bender](https://github.com/specious/bender) - 使用git集成的花哨的双线提示.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有unicode符号的变体.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme).
* [bklyn](https://github.com/gporrata/bklyn-zsh) - 变种 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) 应用自定义.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个git意识的主题.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)   - 精致的主题，注入色彩而不会压倒您的工作空间.  设计用于 [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) .  包括`git`状态装饰.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - 基于oh-my-zsh内置的主题 [gnzh](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gnzh.zsh-theme)  主题.  需要支持unicode的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme)   - 一个简短快速的ZSH主题，向您展示您的需求.  它由块组成：每个块显示在一对\ [方括号\]中，您只需创建一个函数即可添加块.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小主题，显示`git`信息.
* [bluelines](https://github.com/apbarrero/bluelines) - 清晰和蓝色的主题.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - 多线主题，最好的黑暗背景.
* [bronze](https://github.com/reujab/bronze)   - 一个跨shell可自定义的类似电源线的提示，带有写入的图标.  需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - 使用`audtool`在提示中显示当前歌曲.
* [brunty](https://github.com/Brunty/omz-brunty) - 布鲁恩主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - 灵感来自 [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) -  BTTF色彩主题.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh)   - 受Powerline Vim插件的启发.  它旨在简化，仅在相关时显示信息.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH主题，修改为只显示时间和目录.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - 简洁，干净，美丽的主题.
* [bureau](https://github.com/isqua/bureau)   - 一个清晰，信息丰富的双线提示.  包括针对大型存储库优化的git状态.
* [cactus](https://github.com/welksonramos/cactus) - 极简主义主题与`git`状态装饰.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - 糖果主题的轻型版本.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - 在提示符中显示活动的Python版本和`git`装饰.
* [celestialorb](https://github.com/celestialorb/zsh-theme)   -  @celestialorb以电力线为主题的主题.  包括`git`状态装饰，Kubernetes集群信息（如果有），当前AWS配置文件和区域以及活动virtualenv.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)   - 基于sorin.  显示Java，Scala，Go，Node，Python和Ruby的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)   -  Oh-My-Zsh的一个小而美丽的主题，没有任何多余的东西.  包括`git`状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - 为ZSH优化的ZSH提示 [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
* [cherry](https://github.com/feddamisch/zsh-theme-cherry) - 在正确的提示中使用`git`状态装饰的酷主题.
* [chi](https://github.com/akinjide/chi) - 针对macOS上的iTerm 2用户优化的ZSH主题.
* [ciacho](https://github.com/Ciacho/ciacho-ohmyzsh-theme) - 基于Agnoster.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳，大型换行符，git分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单和可扩展性而设计.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - 支持`git`的最小，干净的主题.
* [clean (akz92)](https://github.com/akz92/clean) - 极简主义的ZSH主题.
* [clean (BrandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - 极简主义的变种 [pure](https://github.com/sindresorhus/pure) .  纯净不干净，干净不纯净.
* [cloudy](https://github.com/Huvik/Cloudy) - 最小的阴天ZSH主题.
* [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta-zsh-theme](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - 配置文件 [cmder](http://cmder.net/) 配置为使用ZSH和修改后的地震模式工作 [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - 一个ZSH主题，与Cmder的主题相匹配，Cmder是一个流行的Windows终端模拟器.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) -  Wes Bos的Cobalt 2主题为ZSH和iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) -  Cobalt 2主题与`git`扩展.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) -  Codemachine主题.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi)，在你的提示中包含一个猴子和`git`信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - 基于agnoster，但在电源线外观中有一个显示“--INSERT  - ”和“--NORMAL  - ”的vi模式的右键提示符.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许每主机提示着色，显示`rvm`，`virtualenv`和`git`信息.
* [common](https://github.com/jackharrisonsherlock/common) - 简单，干净且最小的提示，显示当前工作目录，主机名，AWS保险库角色，后台作业，当前SHA，最后一个命令的退出代码以及`git`分支和状态.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 明亮的主题主题优化深色背景.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - 使用git和npm支持清洁有效的ZSH主题.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - 支持github插件的最小接口，基于 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于Powerline Vim插件的可爱表情符号的macOS oh-my-zsh shell主题.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 同 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) 和 [agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) 在一个容器中.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - 信息丰富，极简，以及最重要的是以X战警为主题.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - 这个版本的流行 [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 主题得到了增强，几乎完全重写，实现了模块化和一些新功能.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) -  Darksoku主题基于 [ys](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - 最小的ZSH提示.
* [delta](https://github.com/dongri/delta-zsh-theme) - 嵌入了`git`状态的另一个最小主题.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - 一个强调终端右侧（因此名称）的主题.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - 附带自定义LSCOLORS和LS_COLORS设置文件，适用于黑暗和光明的终端主题.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - 变种 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - 包括`ruby`版本和`git`状态.
* [dmx](https://github.com/domix/dmx.zsh-theme) - 针对黑暗终端窗口进行了优化.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - 低对比度主题，显示当前git分支，如果存储库是脏的，并且值为$ $ PYENV_VERSION`.
* [dracula](https://github.com/dracula/zsh) -  Atom，Alfred，Chrome DevTools，iTerm 2，Sublime Text，Textmate，Terminal.app，Vim，Xcode和ZSH的黑暗主题.
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) - 简约，包括`git`状态信息.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) 变种.
* [dustmod](https://github.com/bmihaila/dustmod) - 源自 [dst](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/dst.zsh-theme) oh-my-zsh中的主题.
* [eggshausted](https://github.com/inutano/eggshausted) - 对于厌倦了错误的人来说，这是一个“git”意识的主题.
* [elessar](https://github.com/fjpalacios/elessar-theme) - 基于的&#39;git`-aware主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) .  需要与Powerline兼容的字体.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - 表情符号风味 [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/robbyrussell/oh-my-zsh) 主题.
* [endless-dog](https://github.com/qwelyt/endless-dog) - 模仿grml-zsh-config的OMZ主题.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 占用终端的大量空间.
* [eriner](https://github.com/zimfw/eriner)   - 电力线灵感的agnoster提示主题的Zim分支.  包括`git`状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - 一个带有`git`信息的简单主题.
* [eucalyptus](https://github.com/relastle/eucalyptus) - 简单的单行主题，适合极简主义的vi模式用户 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的ZSH颜色主题.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - 最小的ZSH提示，在黑暗的背景下效果更好.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)   - 清洁，简单，兼容和有意义.  以ANSI颜色在Linux，Unix和Windows上测试.
* [filthy](https://github.com/molovo/filthy) - 一个令人厌恶的ZSH提示.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - 原始的叉子 [fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy)  在oh-my-zsh中的主题，其中大部分外来的东西被切掉以提高加载速度.  包括电池电量计和“git”状态显示，可以在提示的右侧启用.
* [fishy](https://github.com/akinjide/fishy2) -  ZSH主题灵感源自 [original fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy).
* [fluent-git](https://github.com/RobertKozak/fluent-git) - 显示上次命令执行的时间，错误代码，主机名，用户名，`git`状态，kubernetes集群和命名空间，路径和ssh连接状态.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) .  包括`git`状态装饰.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括最后一个命令的状态，`git`信息和当前目录.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉子 [terminal-party](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于的主题 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) 哦，我的-zsh的主题.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) 来自oh-my-zsh的主题.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme)   - 适用于深色背景.  包括`git`状态装饰.
* [frlo](https://github.com/fiorillo/frlo) - 使用计算机的主机名来提供（希望）独特的三色主题，以便在您的提示中显示，这样您就可以一眼就知道您登录的是哪台计算机.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 丰富的双线主题，支持`​​git`和`svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - 叉子 [Cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme)  哦，我的主题.  不同的颜色和表情符号.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - 丰富多彩的主题，在黑暗的背景下更好地工作.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) -  Prezto在您需要的时候提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme)   -  Nicola Racco的主题.  需要`rvm`和`git`插件.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将oh-my-zsh gentoo主题分解为非omz用户的单独repo.
* [geometry](https://github.com/geometry-zsh/geometry) - 基于Avit和Pure的最小ZSH主题，可显示大量的`git`信息，并且可以组合和自定义.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) 添加主机信息到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme)，包括`git`装饰，IP地址，主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - 一种变体 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower)  具有更多功能，一点眼睛糖果和上下文敏感的额外线条.  包括`git`状态装饰，历史编号，用户名/主机名上下文，目录状态，失败时最后一个命令的状态，以及Python virtualenv名称（如果存在）.
* [gime](https://github.com/nralbrecht/gimezsh)   - 使用`git`集成的ZSH的简单主题.  灵感来自于 [gitsome theme](https://github.com/mtully/gitsome).
* [girazz](https://github.com/mdentremont/girazz) - 对gnzh主题的修改，将“vi”模式添加到正确的提示中.
* [git-prompt](https://github.com/olivierverdier/zsh-git-prompt)   - 显示有关当前`git`存储库的信息.  特别是分支名称，与远程分支的区别，暂存或更改的文件数等.
* [gitsome](https://github.com/mtully/gitsome) - 使用`git`信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
* [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)   - 在`git` repo中，它显示`git`存储库根文件夹中的位置.  当不在`git`回购中时，它显示相对于home的路径，`~`.
* [glimmer](https://github.com/martnu/glimmer) - 包括`git`分支，时间和用户@主机.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) -  iTerm 2和ZSH的主题，包括`git`装饰，user @ host，路径和日期.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括`git`装饰和最后一个命令的返回状态.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874)，使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim`插件.
* [guri](https://github.com/victorfsf/guri) - 简单快速的Oh-My-Zsh主题，基于 [Pure](https://github.com/sindresorhus/pure)的设计.
* [hackersaurus](https://github.com/bhilburn/hackersaurus)   - 在提示中嵌入了一个带有`git`状态和最后一个命令的退出代码的主题.  相关 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)   - 一个简单的主题，第一个角色是花（hana），花的汉字.  这个主题的灵感来自一个名为DSA Hana的键帽.  这很好搭配 [hana atom theme](https://github.com/arturoalviar/hana-matcha-syntax) .  包括`git`状态装饰.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - 显示`git`分支和状态，最后一个命令退出代码，如果超过`ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`则显示最后一个命令执行时间.
* [haribo](https://github.com/haribo/omz-haribo-theme) - 提示中简单的`git` status + timestamp.
* [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间，操作系统（包括Linux上的发行版），目录以及是否以root身份运行.
* [heart](https://github.com/gko/heart-theme) - 以浅色背景为主题的心形提示.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old bash theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间，日期，操作系统（包括Linux上的发行版），目录以及是否以root身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - 受robbyrussell主题+ ssh连接状态提示的启发.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 一种变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) -  Honukai主题和颜色为oh-my-zsh和iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - 带水平分隔符的两行提示.
* [hornix](https://github.com/fusion809/zsh-theme) - 显示时间和日期，操作系统（包括Linux上的发行版），目录以及是否以root身份运行.
* [horse-sh](https://github.com/emileswarts/horse-sh) - 一个非常小的棕色/红色ZSH主题.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - 简单干净，包括执行的最后一个命令的返回码.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - 设计用于超级终端主题，包括`git`状态装饰.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - 使您全面了解正在处理的分支机构以及存储库的状态，而不会使终端混乱.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - 在黑暗的背景下工作良好.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX)   - 修改了iGeek主题.  适用于开箱即用的macOS，包括`git`状态装饰.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - 超级快乐的超棒电力线风格，`git`-aware ** prezto only **主题.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录，可自定义的分隔符，当前分支，`git`状态.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉子 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster)  间距改进和更新的图标.  包括`git`状态信息.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - 极简主义主题，在黑暗背景下更好.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - 清洁主题，显示`git`状态，后台作业，远程主机和其他信息.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 延伸 [intheloop](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/intheloop.zsh-theme) 主题使用powerline字体.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) -  itsthatguy的主题.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 显示时间，当前目录和`git`分支信息，包括分支名称和红色+，如果分支具有未推送的更改.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - 针对深色背景进行了优化，包括`git`状态和`rvm`状态.
* [jbrain4](https://github.com/jbrain4/jbrain4-zsh-theme) - 变种oh-my-zsh的股票bira主题.
* [jc](https://github.com/jclementex/jc-zsh-theme) - 对于黑暗终端背景，包括`git`状态信息.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - 宽松地基于ys主题.
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme)，包括`git`状态.
* [jovial](https://github.com/zthxxx/jovial) - 显示主机，用户，路径，开发环境，`git`分支，其中python venv处于活动状态.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - 极简主义提示.
* [just-another](https://github.com/supertassu/another-theme) - 只是另一个主题，当你被扔到另一台机器时带有主机名.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter)   - 电力线风格的主题与`git`，`svn`，`npm`，`rvm`和网络意识.  需要与Powerline兼容的终端字体.
* [karu](https://github.com/zaari/karu) - 极简主义单行ZSH提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - 针对深色背景进行了优化，包括`git`状态信息.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - 色彩缤纷的主题，包括iTerm 2配色方案.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - 最小的主题.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于Fishy主题，但显示完整路径而不是缩写目录，仅在`ssh`会话和docker容器中显示user @ machine.
* [kketcham](https://github.com/prototype27/kketcham) - 在`git`信息上有漂亮色彩的主题.
* [klendathu](https://github.com/kegonomics/klendathu) - 使用Powerline iconsolas.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - 为黑色终端设计的两线主题，有&#39;git`装饰.
* [krak3n](https://github.com/krak3n/zsh-theme) - 显示golang版本和当前的`git`分支.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) -  ZSH的黑暗主题.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)   -  Agnoster前叉针对日晒终端进行了优化.  需要与powerline兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - 带有`git`和`hg`状态信息的彩色主题，能够将主机特定颜色添加到主机名.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme)   - 一个简单的主题，第一个字符是九（kyuu），数字9.主要颜色是蓝色，带有洋红色的重音.  包括`git`状态装饰.
* [lagune](https://github.com/noplay/lagune) - 最小的ZSH主题.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 受到robbyrussell的启发 [lambda](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/lambda.zsh-theme)  主题.  包括`git`状态装饰.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - 为使用兼容unicode的字体和终端应用程序的`git`用户优化的ZSH主题.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含`git`信息的极简主义提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - 基于lambda的简单主题，带有`git`状态和virtualenv信息.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的ZSH主题，针对`git`使用进行了优化.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - 基于Pure的最小ZSH主题，添加了NodeJS版本.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) -  Lambda和Fishy主题的组合，包括`git`状态装饰.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - 针对黑暗终端进行了优化，具有适用于本地和远程系统的变体.
* [leafia](https://github.com/Ghostrick/leafia-prompt) -  Leafy prezto主题，显示`git`状态信息.
* [lewis](https://github.com/lewisflude/oh-my-lewis)   - 黑色，白色和红色主题.  显示`git`状态信息.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - 极简主义主题，最好在黑暗的终端背景.
* [lime](https://github.com/yous/lime) - 简单易用的ZSH主题.
* [limpide](https://github.com/shooteram/limpide) - 修改版 [miloshadzic](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) - 受Yaris Alex Gutierrez的优雅触摸，Yad Smood&#39;s ys和Bureau主题的启发.
* [liquidprompt](https://github.com/nojhan/liquidprompt)   - 功能全面且精心设计的自适应提示，可在您需要时提供有用的信息.  它会在您需要时向您显示所需内容.  您会注意到更改时会发生什么变化，从而节省时间和挫败感.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的骆驼使用的极简主题.
* [logico](https://github.com/logico-software/logico-zsh-theme)   - 有`git`装饰.  显示vi模式的远程状态和指示器.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 以Sindre Sorhus纯粹主题为基础的德克萨斯主题主题.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)   -  lambda-mod主题的变体.  有`git`装饰，需要与电源线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)   - 包括`git`装饰.  基于 [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) 哦，我的主题.
* [magico](https://github.com/IOsonoTAN/magico) -  IOsonoTAN的magico主题.
* [materialshell](https://github.com/carloscuesta/materialshell) - 一个 [material design](https://material.io/guidelines/style/color.html)  主题为你的贝壳具有良好的对比度和重要部分的颜色弹出.  设计使眼睛容易.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变种 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  在Matrix电影三部曲中看起来像是什么样的东西.  包括`git`状态装饰.
* [mattizer](https://github.com/matt-sungwook/ohmyzsh-mattizer-theme) - 包括工作目录和`git`状态装饰.
* [mau](https://github.com/vichargrave/mau) - 带有猫扭曲的ZSH主题.
* [maxulysse/myzsh](https://github.com/MaxUlysse/myzsh) -  Maxime Garcia的myzsh主题.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)   - 最大限度提示，包括键盘模式，所有权信息和其他上下文信息，以λ作为提示字符.  需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)   - 检查`/ sys / class / power_supply`文件夹以确定系统是否安装在笔记本电脑或台式机上.  读取电池百分比grepping acpi命令并在提示中显示它.  包括`git`装饰.
* [midin](https://github.com/xlshiz/midin) - 适用于黑暗的终端背景，包括`git`状态装饰.
* [milight](https://github.com/frodoslaw/milight-zsh) - 使用`git`状态显示的最小ZSH提示，最适合黑暗终端背景.
* [min](https://github.com/andrepolischuk/min) - 简约的ZSH提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) -  ZSH主题与空间的关系.
* [minima](https://github.com/eduardnikolenko/minima) - 一个最小的ZSH主题，包括`git`，`go`，`node`，`npm`，`python`和其他指标.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，在右侧提示中包含`git`装饰.
* [minimal2](https://github.com/PatTheMav/minimal2)   - 最小和可扩展的ZSH主题.  分叉 [subnixr's original](https://github.com/subnixr/minimal) 并适应 [Zimfw](https://github.com/zimfw/zimfw).
* [minimal](https://github.com/subnixr/minimal) - 最小但功能丰富的主题.
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 受到来自oh-my-zsh的kolo主题的启发.
* [misa](https://github.com/misalabs/misa.zsh-theme) -  Misalabs的ZSH主题.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - 针对深色背景进行了优化.
* [moderno](https://github.com/obrassard/moderno-zsh) - 简约而现代的ZSH主题灵感源自 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme)  来自Oh-My-ZSH的主题.  包括`git`状态装饰.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - 最小但易于扩展的提示.
* [moux](https://github.com/gagbo/moux) - 适用于深色背景，包括`RPROMPT`中的`git`装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在的存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/)，在 [ZSH](https://en.wikipedia.org/wiki/Zsh) 以及 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - 基于电力线的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - 一个简单的最小ZSH提示主题.
* [musy](https://github.com/THaGKI9/musy-zsh-theme)   - 受到缪斯主题的启发.  包括`git`状态装饰.
* [nanofish](https://github.com/tweekmonster/nanofish) - 为nanotech主题添加鱼式目录提示.
* [neon](https://github.com/sahariko/neon) - 带有`git`装饰的漂亮且极简的ZSH主题.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) -  ZSH与书呆子字体的快速主题.
* [nescalante](https://github.com/nescalante/zsh-theme) - 针对黑暗终端背景进行了优化，包括`git`装饰.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - 胖子和快速主题 - 内外都很漂亮，风格分段做得恰到好处.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - 一个非常基本的主题，只有一个macOS自行车图标.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - 丰富多彩，显示`git`状态装饰.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - 基于af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - 一个简单的oh-my-zsh主题.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - 极简主义的ZSH主题与`git`状态装饰.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) -  OMZ的节点主题，分解为更容易与其他插件管理器一起使用.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - 基于ys主题，添加了NodeJS版本（来自NVM插件）.
* [noon](https://github.com/silky/noon.zsh-theme) - 有明暗变体，显示`git`信息.
* [nord](https://github.com/TyWR/Nord-zsh) - 包括`git`状态装饰并显示活动的conda环境.
* [nothing](https://github.com/eendroroy/nothing) - 闪电快速而且非常简单，因为它几乎没有任何东西.
* [nox](https://github.com/kbrsh/nox) - 黑暗主题，显示当前工作目录和git状态.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)   - 清洁，分散注意力和“git”重点发展主题.  显示相对于`git` root（或〜在`git` repo之外的时间）的路径，自上次提交以来的时间，当前SHA，分支和分支状态.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) -  prezto和oh-my-zsh的简单主题.
* [odin](https://github.com/tylerreckart/odin) -  Odin是一个&#39;git`风格的ZSH主题.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有`git`装饰的多线主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 关于bash和ZSH的自以为是的提示.
* [oh-my-via](https://github.com/badouralix/oh-my-via) -  ZSH的主题，主要用于威盛服务器上使用的历史主题.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - 包括`git` status和virtualenv信息.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - 简约和黑暗的ZSH主题.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO  - 让我们呼吸一个干净的ZSH.
* [pad](https://github.com/eproxus/pad.zsh-theme) - 简洁而多彩的oh-my-zsh主题.
* [page](https://github.com/SLIB53/page-zsh-theme)   - 支持VCS的简单主题.  提示显示当前工作目录，分支和颜色编码弯曲胖箭头的1级.
* [palenight](https://github.com/jenssegers/palenight.zsh-theme) - 允许显示主机信息，包括`git`分支装饰.
* [papercolor](https://github.com/erikschreier/PaperColor-themes)   -  ZSH的颜色方案，`vim`和`tmux`.  包括`git`状态装饰.
* [pastel](https://github.com/iboyperson/pastel) -  ZSH主题灵感源自 [sugar-free](https://github.com/cbrock/sugar-free) .  包括`git`装饰.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) -  robbyrussell和Pure Shell主题精神的最小主题.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - 丰富多彩的主题，包括go版本，节点版本和`git`状态.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) -  ZSH灵感和分叉的干净简单的主题 [Lambda (Mod) ZSH Theme](https://github.com/halfo/lambda-mod-zsh-theme).
* [pi](https://github.com/tobyjamesthomas/pi) - 带有`git`状态装饰的极简主题.
* [plain](https://github.com/jimeh/plain.zsh-theme) -  ZSH的简单主题，显示基本的`git`信息.
* [planet](https://github.com/borb/planet-zsh) - 精简版 [steef](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [platypus](https://github.com/fdv/platypus) - 鸭嘴兽是FrédéricdeVillamil使用的oh-my-zsh简单方便的主题.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - 显示工作目录，最后一个命令的返回状态和`git`当前分支.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) -  RDM的基本oh-my-zsh自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - 程序员的主题与`git`状态，ruby版本和项目路径.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - 适用于黑暗的终端背景，包括`git`状态装饰.
* [powerless](https://github.com/martinrotter/powerless) - 受电力线启发的小而简单的纯ZSH提示.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - 快速重新实现 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH主题.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) -  Powerlevel9k是ZSH使用的主题 [Powerline Fonts](https://github.com/powerline/fonts) .  它可以与vanilla ZSH或ZSH框架一起使用，例如 [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)，和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 加载项 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - 电力线的两线版本：一个用于信息，一个用于输入.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)   - 另一个关注电力线主题.  可配置良好，但需要至少256色的终端与电源线兼容的终端字体.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个git意识的电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go)   - 一个美丽而有用的低延迟提示，用golang编写.  包括`git`和`hg`状态装饰，最后一个命令运行的退出状态，当前的Python virtualenv，无论你是否在 [nix](https://nixos.org/) 外壳，易于扩展.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一个 [Powerline](https://github.com/powerline/powerline)  克隆用Haskell编写.  它比原始实现快得多，并使shell明显响应更快.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 在Ruby中创建，使用电力线字符来模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) -  Bash，ZSH，Fish和tcsh的美丽而有用的提示生成器.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一个 [powerline](https://github.com/Lokaltog/vim-powerline) 像Bash，ZSH和Fish一样的提示.  显示有关git / svn / hg / fossil分支的重要详细信息，并且易于自定义/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - 一个 [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash) .  显示virtualenv，`git`状态信息和最后一个命令运行的退出代码.
* [powerzeesh](https://github.com/sevaho/Powerzeesh)   - 基于电力线的ZSH主题.  它旨在简化，仅在相关时显示信息，并针对速度和外观进行优化.  灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) -  Sublime Text，Terminal，iTerm 2和ZSH的主题集合.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 针对黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) -  Prezto端口的oh-my-zsh的云提示.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) -  Lambda主题（用于prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline)   -  prezto的电力线.  显示git信息，RVM版本.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 一个相当重量级的ZSH提示，基于流行的同名vim插件的powerline字体，适用于黑暗的背景.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受到影响 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)   - 纯粹和agnoster的混搭.  有`git`装饰，适用于深色和浅色的背景.
* [pure](https://github.com/sindresorhus/pure) - 漂亮，简约，快速的ZSH提示.
* [purien](https://github.com/sinetoami/purien) - 基于的漂亮提示 [pure](https://github.com/sindresorhus/pure) 提示，受到启发 [alien-minimal](https://github.com/eendroroy/alien-minimal) 和 [filthy](https://github.com/molovo/filthy).
* [purify](https://github.com/banminkyoz/purify) - 简单，快速和酷炫的提示.
* [purity](https://github.com/petermbenjamin/purity) - 受到robbyrussell主题+纯粹提示的启发.
* [purs](https://github.com/xcambar/purs) - 一个 [Pure](https://github.com/sindresorhus/pure)-inspired提示写在 [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - 丰富多彩的主题灵感来自于 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题，包括`git`装饰.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)   - 针对深色背景进行了优化，包括`git`信息.  主题回购包括iTerm 2和终端颜色设置.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于af-magic和posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - 专为黑暗终端设计（最适合 [Solarized](https://github.com/altercation/solarized) iTerm 2主题）（prezto）.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - 将表情符号添加到您的ZSH终端.
* [rainbowie](https://github.com/druskus20/rainbowie) - 丰富的主题与`git`信息.
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和&#39;robbyrussell`主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - 随机表情符号.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - 简单而多彩的主题与`git`状态装饰.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的ZSH主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和日晒终端进行了优化.  需要与Powerline兼容的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - 针对曝光的终端配色方案进行了优化，包括`git`状态装饰.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - 一个简单的主题，第一个字符是零（rei），数字0.包括`git`状态装饰.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于agnoster，优化 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - 基于Sorin的Prezto ZSH主题，使用表情符号跟踪GIT上下文.
* [river](https://github.com/revir/river-zsh-config) - 带有`git`信息的黑暗主题.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - 基于来自的想法 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - 用输出装饰`robbyrussell`主题以指示** WIP **提交.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - 一个黑暗的主题.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - 针对深色背景进行了优化.
* [rummik](https://github.com/rummik/zsh-theme)   -  @ rummik的主题.  支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin)，以及提示中的`git`状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto) .  包括`git`状态装饰.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 丰富多彩的主题，包括`git`装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) - 由emojis指示的git状态的主题.
* [saltgen](https://github.com/saltgen/ohmyzsh-saltgen-theme) -  robbyrussell oh-my-zsh主题的变体.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - 包括git状态，适用于黑暗的终端背景.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - 显示`git`状态，用户@主机信息，最后一个命令的退出状态以及是否以root身份运行.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - 使用`：sh`命令显示Vim是否在后台运行.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - 添加标签完成 [sdkman](https://sdkman.io/).
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了许多特殊的unicode字符，但如果没有支持良好的字体，它可能会导致一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食主题启发，使用颜色编码提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh)   - 为Devops清除提示主题.  包括git信息，kubernetes上下文，AWS配置文件，GCP项目和Azure活动云.
* [seppuku](https://github.com/Helianthella/seppuku) - 灵感来自干净和极简主题 [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme).
* [sepshell](https://github.com/sepehr/sepshell) - 基于旧丢失的taybalt主题的清洁和最小的ZSH主题，使用`git` bisecting / merge / rebasing模式和可配置的提示符号.
* [Seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 简单的omz兼容主题与相应的iTerm 2配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - 精益提示的演变本身就是一种纯粹的改写.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - 简单的主题与`git`状态装饰.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)   - 一个简单的主题，第一个字符是七（shichi / nana），数字7.主要颜色是红色，带有黄色重点.  包括`git`状态装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - 分叉 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) .  有`git`装饰.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - 显示当前目录和git信息的简单主题.
* [siegerts](https://github.com/siegerts/zsh-theme) - 在右侧提示中包含`git`状态装饰.
* [silver](https://github.com/reujab/silver) - 一个跨壳可定制的类似电力线的提示，受到了很大的启发 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) .  一个更快的生锈端口 [bronze](https://github.com/reujab/bronze) .  需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
* [simpalt](https://github.com/m-lima/simpalt) -  ZSH的信息丰富的小足迹主题.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - 电源线灵感的简单主题与`git`装饰.
* [simple](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - 基于的极简主题 [robbyrussel](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell) 在iTerm的窗口标题栏中嵌入`git`状态信息，而不是在提示符中使用空格.
* [simplex](https://github.com/feddamisch/zsh-theme-simplex) - 一个简单的主题与右侧`git`装饰.
* [simplezsh](https://github.com/fr0zn/simplezsh) - 使用`git`信息显示的最小主题.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)   -  k-kinzal的sinon主题.  包括`git`状态装饰.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme)   - 这个主题有一个独特的目录列表.  在`git`项目中，目录显示的范围限定为当前存储库根目录.
* [sk9](https://github.com/skeiter9/sk9-zsh) -  Skeiter9的ZSH主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) -  Atom，Prism和ZSH的主题收藏，灵感来自He-Man的Skeletor和宇宙大师.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对黑暗终端进行了优化，显示“git”状态装饰.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) -  ZSH主题灵感源自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
* [slimline](https://github.com/mgee/slimline)   - 最小，快速和优雅的ZSH提示.  在合适的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme) ** **简约**和**极简主义**主题为您的**最喜欢的**终端.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 变种 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) 主题 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 快乐和悲伤面孔的提示.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme)   - 简约的ZSH主题，灵感来自老式的爱好.  没有冗长的噱头，没有表情符号，没有颤抖的旋转器，也没有其他视觉噪音.  有明暗模式.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) -  ZSH的Solarized powerline风格主题.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) -  Solarized powerline变种.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - 使用robbyrussell的oh-my-zsh主题进行颜色修复 [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 主题与`git`，`nvm`，rvm / rbenv / chruby，python，`ssh`和其他有用的状态指标.
* [spowerline](https://mbauhardt.github.io/spowerline/) - 以scala编写，灵感来自agnoster， [tmux](https://tmux.github.io) powerline，vim powerline和vim status插件.
* [staples](https://github.com/dersam/staples) - 基于局，如果通过SSH连接，则显示user @ host.
* [starboy](https://github.com/prdpx7/Starboy) - 一个简单的ZSH主题
* [statusline](https://github.com/el1t/statusline) - 响应式ZSH主题，在您需要时提供信息片段.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)   -  ZSH steeef主题作为独立的存储库.  这个回购的目的是避免在使用steeef主题时依赖oh-my-zsh.  像抗体这样的ZSH插件管理器可以使用主题而无需使用oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - 可定制的版本 [steeef's](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) 主题.
* [sublime](https://github.com/pjmp/sublime) - 一个崇高，干净，简约的zsh主题与`git`状态装饰.
* [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme)   - 包括`git`状态装饰.  在黑暗的终端背景更好地工作.
* [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态 [kolo](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括`git`状态装饰和随附的iTerm2配色方案.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme)，包括`git`状态装饰.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - 针对深色背景优化的最小ZSH主题.
* [tahuri](https://github.com/Tahuri/environment-configuration) -  Arch Linux的ZSH主题.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - 包括`git`状态装饰和conda / virtualenv状态.
* [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自agnoster和linuxer.
* [that-human-jason](https://github.com/thatHumanJason/that-human-jason-zsh-theme) - 严重依赖于 [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme) 主题包括在内 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于gallifrey的主题.
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 具有`git`状态的彩色主题.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - 受到theunraveler的启发，使用符号显示`git`状态.
* [thyme](https://github.com/kawamurakazushi/thyme) - 简单的主题与`git`状态装饰.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)   - 包括`git`信息;  最好的黑暗背景.
* [tq](https://github.com/kitian616/tq-zsh-theme) - 显示`git`状态，时间，需要电力线字体.
* [traffic](https://github.com/fcce/traffic-zsh-theme) -  ZSH的黑暗主题.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) -  ZSH的黑暗主题.
* [trinity](https://github.com/de-luca/Trinity) - 基于的简单主题 [geometry](https://github.com/geometry-zsh/geometry) .  包括`git`装饰.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主题，包括`git`状态装饰，k8s上下文和`rvm`状态.
* [tvline](https://github.com/thvitt/tvline) - 源自 [agnoster's theme](https://gist.github.com/agnoster/3712874)，添加powerline字体增强功能.
* [ultimate](https://github.com/b4b4r07/ultimate) - 使用`git`指示器，vim模式指示器和缩短路径的极简主题.
* [vanan](https://github.com/avano/vanan-zsh-theme) - 极简主题主题与黑色终端的`git`信息.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 从themes / mgutz.zsh-theme修改.与a一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) 配色方案.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - 流行的ZSH主题的混搭 [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/fishy.zsh-theme)，有一些视觉调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
* [webicons](https://github.com/Jmclerck/webicons.zsh-theme) - 在提示符中包含`git`状态，节点和纱线版本.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - 快速重新实现鲸鱼主题.
* [wild-cherry](https://github.com/mashaal/wild-cherry) -  ZSH，iTerm 2，Sublime，Atom和Mou的童话灵感主题.
* [work-line](https://github.com/afnizarnur/work-line) - 主题与漂亮的表情符号.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)   - 一个主题，旨在向您展示您需要的信息.  `wynwyn`从默认主题`avit`和优秀的主题中获取灵感 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xm](https://github.com/Shiaoming/xm)   - 黑暗终端的主题.  有`git`装饰.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - 基于Jreese主题插件的oh-my-zsh shell主题.
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前git commit的缩短哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)   - 最小主题与行分隔提示.  基于 [Robby Russell's theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme).
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - 极简主义主题与`git`状态装饰.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - 修改自 [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) 主题并针对深色背景进行了优化.
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/)  支持使用大型集群的批量提交系统的变体.  支持Slurm，LSF / IBM Spectrum LSF和PBS.
* [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 清晰，简单，兼容和有意义的主题，适合黑暗背景.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - 带有`git`状态信息的简单ZSH主题.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - 黑暗优化的ZSH主题.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - 包括conda和venv状态.
* [yz50](https://github.com/lacanlale/yz50-zsh) - 丰富多彩，基于 [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/crunch.zsh-theme)  主题.  包括`git`状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - 定制版本的oh-my-zsh [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
* [zero](https://github.com/arlimus/zero.zsh)   -  Zero的主题和插件.  有明暗终端背景的变种.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景上效果最佳，包括`git`状态装饰.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name and the current working directory.
* [zinc](https://gitlab.com/robobenklein/zinc) - 超快速，纯粹的ZSH，混合异步电力线提示，易于扩展且极易配置.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) -  oh-my-zsh的修改版本 [maran](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh2000](https://github.com/inspectahstack/zsh2000) - 电力线寻找ZSH主题，包括`rvm`提示，`git`状态和分支，当前时间，用户，主机名，密码，退出状态，是否以root身份运行和后台作业状态.
* [zshcomrade](https://github.com/landongn/zshcomrade) - 同志的ZSH主题！
* [zwsh](https://github.com/naens/zwsh) -  ZSH的Zpm3 / Wordstar模式/主题.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - 类似于agnoster-zsh-theme，旨​​在通过电力线美学来披露信息.

### Fonts

此处列出的一些主题需要与Powerline兼容的字体，以下是一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些漂亮的等宽图标.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - 一个很好的等宽字体，用Font-Awesome，Octoicons和Powerline-Glyphs打补丁.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与Powerline兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) - 另一种专为源代码设计的Powerline兼容字体.
* [Input Mono](http://input.fontbureau.com/)   - 专为代码设计的一系列字体.  它提供等宽字体和比例字体，并包括电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka)   - 代码的字体，由代码构建.  高度可定制.
* [Monoid](https://larsenwork.com/monoid/) -  Monoid可自定义和优化，即使在低分辨率显示器上也能在15px线高处进行类似位图的清晰度编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)   - 为Powerline，Font Awesome，Octicons，Devicons和Vim Devicons收集超过20个修补字体（超过2,000种变体）和FontForge字体修补程序python脚本.  包括：Droid Sans，Meslo，源代码，AnonymousPro，Hack，ProFont，Inconsolata等等.
* [Powerline patched font collection](https://github.com/powerline/fonts) - 修补了十几个字体的集合，包括电力线gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - 终端的TTF版本，包括电力线字形.

## Installation

### [Antibody](https://github.com/getantibody/antibody)

 通过将`antigen bundle githubuser / reponame`添加到.zshrc文件中，可以安装大多数这些插件.  下次启动`zsh`时，抗体会自动为您自动克隆插件.  您还可以将插件添加到正在运行的ZSH中，并使用`antigen bundle githubuser / reponame`进行测试，然后再将其添加到`.zshrc`中.

### [Antigen](https://github.com/zsh-users/antigen)

 通过将`antigen bundle githubuser / reponame`添加到.zshrc文件中，可以安装大多数这些插件.  Antigen将在下次启动`zsh`时自动为您安装克隆插件.  您还可以将插件添加到正在运行的ZSH中，并使用`antigen bundle githubuser / reponame`进行测试，然后再将其添加到`.zshrc`中.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.将新插件克隆到`.zsh.local / modules`中
2.将插件模块加载到`.zshrc`中
3.打开一个新的ZSH终端窗口或选项卡

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd~ / .oh-my-zsh / custom / plugins`
2.`git clone repo`
3.将repo添加到插件列表中

### [Prezto](https://github.com/sorin-ionescu/prezto)

1.将插件克隆到prezto模块目录中
2.将插件添加到`.zpreztorc`文件中
3.打开新的终端窗口或选项卡

### [Zgen](https://github.com/tarjoilija/zgen)

大多数这些插件都可以通过将`zgen load githubuser / reponame`添加到您正在执行其他`zgen load`调用的同一函数中的.zshrc文件来安装.Zgen将在您执行某个时自动克隆存储库`zgen save`.

### [zplug](https://github.com/zplug/zplug)

通过将`zplug“githubuser / reponame”添加到`.zshrc`文件中，可以安装大多数这些插件.

## Writing New Plugins

我已经记录了一些编写新插件的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [zshdb](https://github.com/rocky/zshdb) -  ZSH调试器
* [zunit](https://github.com/zunit-zsh/zunit) -  ZSH强大的单元测试框架

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精湛的工具，资源和工作流技巧的精选列表，提供了一个很棒的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - 精选的开源系统管理员资源的精选列表
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) -  CLI爱好者的精选列表.

找到其他有用的awesome- *列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 是不可或缺的.
