<div class="github-widget" data-repo="webpro/awesome-dotfiles"></div>
## Awesome dotfiles

 精选的dotfiles资源列表.  灵感来自于 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

## Articles

### Introductions

* [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789) ([L. Kappert](https://github.com/webpro))
* [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/) ([D. Vints](https://github.com/driesvints))
* [Managing your dotfiles](https://medium.com/@webprolific/managing-your-dotfiles-7d2725297304)
* [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
* [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)

### Tutorials

* [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/)
* [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449); [Part 2](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
* [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
* [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
* [Managing your dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
* [The best way to store your dotfiles: A bare Git repository](https://developer.atlassian.com/blog/2016/02/best-way-to-store-dotfiles-git-bare-repo/)

### Shell startup

* [Shell startup scripts](https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
* [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

* [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
* [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
* [Managing dot-files with vcsh and myrepos](https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html)
* [Manage dotfiles using vcsh and mr](https://www.kunxi.org/2014/02/manage-dotfiles-using-vcsh-and-mr/)
* [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
* [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

 那里有许多伟大的dotfiles repos，每个都包含自己的灵感和宝石.  我认为通过它们的最佳方法之一是 [searching GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories).

另见：

* [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
* [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
*提示：在GitHub上搜索文件名，例如 [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93&type=Code&q=in%3Apath+.gitconfig).

## Example dotfiles repos

 最受欢迎，维护良好，协作的dotfiles存储库和框架的集合.  有些项目只包含dotfiles.  其他人更进一步，允许您轻松添加自己的自定义点文件，和/或包括管理dotfiles /插件的脚本.

### Bash

 标题|  说明|  焦点
:--|:--|:--
[Bash it](https://github.com/Bash-it/bash-it)  |  社区bash框架.  |  自动完成，主题，别名，自定义功能.  结构良好的框架.
[Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)  |  合理的黑客默认为macOS |  这里有很多善意，很棒的协作社区努力.
[Maximum Awesome](https://github.com/square/maximum-awesome)  |  为vim和tmux配置文件  Vim，tmux.  专为Mac OS X而设计.
[dev-setup](https://github.com/donnemartin/dev-setup)  |  Mac OS X开发环境设置|  在OS X上广泛设置开发人员工具.
[webpro's dotfiles](https://github.com/webpro/dotfiles)  |  macOS dotfiles |  Bash，Homebrew，Brew Cask，Git，Node.js，Hammerspoon.
[Overbryd's dotfiles](https://github.com/Overbryd/dotfiles)  |  macOS 0-100 bootstrap |  macOS默认，Bash，Homebrew，Casks，Git，Vim |  使用简单的Makefile进行简单的维护
[rootbeersoup's dotfiles](https://github.com/rootbeersoup/dotfiles)  |  轻松的Bash，Vim和macOS配置|  一个`卷曲\ |  sh`安装程序和Makefile为永久或临时配置提供便携和轻松的设置.

### Zsh

 标题|  说明|  焦点
:--|:--|:--
[thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles)  |  一组vim，zsh，git和tmux配置文件|  Zsh，vim，tmux，git，homebrew.  用途 [rcm](https://github.com/thoughtbot/rcm).
[oh-my-zsh](https://ohmyz.sh)  |  用于管理zsh配置的社区驱动框架.  |  包括200多个可选插件（rails，git，OSX，hub，capistrano，brew，ant，php，python等），超过140个主题，为您的早晨增添趣味，并提供自动更新工具.
[Prezto](https://github.com/sorin-ionescu/prezto)  |  Zsh的配置框架.  |  使用合理的默认值，别名，函数，自动完成和提示主题来丰富命令行界面环境.
[YADR](http://skwp.github.io/dotfiles/)  |  最好的vim，git，zsh插件和你见过的最干净的vimrc  Homebrew，zsh，git，vim等等.  活动存储库.
[holman does dotfiles](https://github.com/holman/dotfiles)  |  holman做dotfiles |  围绕主题组织良好.  作者希望它适合每个人.
[antigen](http://antigen.sharats.me)  |  zsh的插件管理器，受到了oh-my-zsh和vundle的启发.  |  Antigen是一小组函数，可帮助您轻松管理shell（zsh）插件.  抗原是zsh，Vundle是什么样的.
[Dries's dotfiles](https://github.com/driesvints/dotfiles)  |  macOS的dotfiles的简化方法  Zsh，哦我的Zsh，macOS，Homebrew，Mackup
[sobolevn's dotfiles](https://github.com/sobolevn/dotfiles)  |  Dotfiles为开发者带来幸福|  Zsh，Brew，Sublime，Python，Node，Elixir

### Fish

 标题|  说明|  焦点
:--|:--|:--
[oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)  |  社区鱼类框架.  |  包括许多插件和主题，包括安装，自动更新和脚手架工具.
[Paul's dotfiles](https://github.com/paulirish/dotfiles)  |  丰富的dotfiles，具有大量酷炫的自定义功能|  Fish，macOS，Homebrew，Custom Shell功能
[rkalis's dotfiles](https://github.com/rkalis/dotfiles)  |  维护良好的dotfiles，包括Fish，存储库管理和Hammerspoon |  Fish，macOS，Homebrew，Repository management，Hammerspoon


## Tools

* [Ansible](https://www.ansible.com) - 极其简单的配置管理，应用程序部署，任务执行和多节点编排引擎.
* [chezmoi](https://github.com/twpayne/chezmoi) - 在多台计算机上安全地管理您的dotfiles.
* [dotbot](https://github.com/anishathalye/dotbot) - 引导你的dotfiles的工具.
* [dotdrop](https://github.com/deadc0de6/dotdrop) - 保存一次dotfiles，将它们部署到各处.
* [dotfiles](https://github.com/jbernard/dotfiles) - 在$ HOME中轻松管理dotfile符号链接的工具.
* [Ellipsis](https://github.com/ellipsis/ellipsis) -  dotfiles的包管理器.
* [fresh](https://freshshell.com)   - 保持你的dotfiles新鲜.  Fresh是一种将shell配置（别名，函数等）从其他人配置到您自己的配置文件中的工具.
* [GNU Stow](http://www.gnu.org/software/stow/) -  Symlink场管理器，它采用位于文件系统上不同目录中的不同软件和/或数据包，并使它们看起来安装在同一个地方.
* [homeshick](https://github.com/andsens/homeshick) - 用Bash编写的Git dotfile同步器.
* [homesick](https://github.com/technicalpickles/homesick)   - 你的主目录是你的城堡.  不要留下你的dotfiles（[article](https://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick)).
* [mackup](https://github.com/lra/mackup) - 保持应用程序设置同步（OS X / Linux）.
* [rcm](https://github.com/thoughtbot/rcm) -  rc文件（dotfile）管理
* [SaltStack](https://www.saltstack.com) - 软件定义数据中心的智能编排（[article](https://medium.com/@rawkode/managing-dotfiles-with-saltstack-eb600867073e)).
* [themer](https://github.com/mjswensen/themer) - 在dotfiles中管理和生成开发工具中的主题.
* [vcsh](https://github.com/RichiH/vcsh) -  $ HOME的版本控制系统，$ HOME中的多个Git存储库.
* [yadm](https://github.com/TheLocehiliosan/yadm) - 使用共享Git存储库和一些其他功能管理跨多台计算机的文件集合的工具.

### macOS

* [Cider](https://github.com/msanders/cider) - 使用Homebrew进行无忧无虑的自举.
* [dockutil](https://github.com/kcrawford/dockutil) - 用于管理停靠项目的命令行工具
* [mas](https://github.com/mas-cli/mas) -  Mac App Store命令行界面

## Miscellaneous

* [A lesson in shortcuts](https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp) -  Rob Pike如何产生“隐藏”或“点”文件的想法.
* [dotfiles.github.io](http://dotfiles.github.io) - 你在GitHub上关于dotfiles的非官方指南.
* [OS X Defaults](https://github.com/kevinSuttle/macOS-Defaults) - 开始的伟大工作的集中地点 [@mathiasbynens on .macos](https://github.com/mathiasbynens/dotfiles#sensible-macos-defaults).
* [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) - [Summary](https://wiki.archlinux.org/index.php/XDG_Base_Directory)

## Related Lists

* [Awesome Shell](https://github.com/alebcay/awesome-shell) - 精选的命令行框架，工具包，指南和小玩意的精选列表.
* [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins) - 适用于oh-my-zsh，抗原和Prezto的Zsh插件列表.
* [Awesome Dev Env](https://github.com/jondot/awesome-devenv) - 精选工具，资源和工作流技巧的精选列表，创建了一个非常棒的开发环境.

## Archive/abandoned projects

* [Bashstrap](https://github.com/barryclark/bashstrap)
* [battleschool](https://github.com/spencergibb/battleschool)
* [Bork](https://github.com/mattly/bork) - 用于配置管理的Bash DSL.
* [Eduardo's dotfiles](https://github.com/eduardolundgren/dotfiles)
* [Kevin's dotfiles](https://github.com/kdeldycke/dotfiles)
* [kody](https://github.com/jh3y/kody)
* [osxc](http://osxc.github.io)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Lars Kappert](https://www.webpro.nl) 已放弃对此作品的所有版权及相关或相邻权利.
