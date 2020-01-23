<div class="github-widget" data-repo="webpro/awesome-dotfiles"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome dotfiles

 点文件资源的精选列表.  受到启发 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

## Articles

### Introductions

- [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789) ([L. Kappert](https://github.com/webpro))
- [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/) ([D. Vints](https://github.com/driesvints))
- [Managing your dotfiles](https://medium.com/@webprolific/managing-your-dotfiles-7d2725297304)
- [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
- [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)

### Tutorials

- [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/)
- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449); [Part 2](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
- [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
- [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
- [Managing your dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
- [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)

### Shell startup

- [Shell startup scripts](https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
- [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

- [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
- [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
- [Managing dot-files with vcsh and myrepos](https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html)
- [Manage dotfiles using vcsh and mr](https://www.kunxi.org/2014/02/manage-dotfiles-using-vcsh-and-mr/)
- [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
- [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. I think one of the best ways to go through them is by [searching GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories).

另请参阅：

- [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
- [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
-提示：在GitHub上搜索文件名，例如 [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93&type=Code&q=in%3Apath+.gitconfig).

## Example dotfiles repos

 最受欢迎，维护良好且协作的点文件存储库和框架的集合.  一些项目仅包含点文件.  其他则使您可以轻松添加自己的自定义点文件和/或包括管理点文件/插件的脚本，从而走得更远.

### Bash

 |  标题|  描述  重点|
| :------------------------------------------------------------------ | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it](https://github.com/Bash-it/bash-it)                        |  社区bash框架.  |  自动补全，主题，别名，自定义功能.  结构良好的框架.  |
| [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)      |  MacOS的明智黑客默认设置  这里有很多好处，需要社区的大力合作.  |
| [Maximum Awesome](https://github.com/square/maximum-awesome)         |  vim和tmux的配置文件|  Vim，tmux.  为Mac OS X内置.
| [dev-setup](https://github.com/donnemartin/dev-setup)                |  Mac OS X开发环境设置|  在OS X上广泛设置开发人员工具.
| [webpro's dotfiles](https://github.com/webpro/dotfiles)              |  macOS点文件|  Bash，Homebrew，Brew Cask，Git，Node.js，Hammerspoon.  |
| [Overbryd's dotfiles](https://github.com/Overbryd/dotfiles)          |  macOS 0-100引导程序|  macOS默认值，Bash，Homebrew，Casks，Git，Vim |  简单的Makefile进行简单的维护|
| [rootbeersoup's dotfiles](https://github.com/rootbeersoup/dotfiles)  |  轻松的Bash，Vim和macOS配置|  `curl \ |  sh`安装程序和Makefile为永久性或临时性配置提供了便捷的安装方式.  |

### Zsh

 |  标题|  描述  重点|
| :------------------------------------------------------------ | :--------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles)  |  vim，zsh，git和tmux配置文件集|  Zsh，vim，tmux，git，自制软件.  用途 [rcm](https://github.com/thoughtbot/rcm).                                                                                      |
| [oh-my-zsh](https://ohmyz.sh)                                  |  社区驱动的框架，用于管理zsh配置.  |  包括200多个可选插件（rails，git，OSX，集线器，capistrano，brew，ant，php，python等），超过140个主题来为您的早晨增光添彩，以及一个自动更新工具.  |
| [Prezto](https://github.com/sorin-ionescu/prezto)              |  Zsh的配置框架.  |  通过合理的默认值，别名，函数，自动完成和提示主题来丰富命令行界面环境.  |
| [YADR](http://skwp.github.io/dotfiles/)                        |  您见过的最好的vim，git，zsh插件和最干净的vimrc |  自制，zsh，git，vim等.  活动存储库.  |
| [holman does dotfiles](https://github.com/holman/dotfiles)     |  holman是否执行dotfile |  围绕主题组织得很好.  作者希望它为每个人工作.  |
| [antigen](http://antigen.sharats.me)                           |  zsh的插件管理器，受oh-my-zsh和vundle启发.  |  Antigen是一小组功能，可帮助您轻松管理Shell（zsh）插件.  Antigen对zsh而言，Vundle对vim而言.  |
| [Dries's dotfiles](https://github.com/driesvints/dotfiles)     |  适用于macOS的点文件的简化方法  Zsh，噢，我的Zsh，macOS，Homebrew，Mackup |
| [sobolevn's dotfiles](https://github.com/sobolevn/dotfiles)    |  点文件为开发人员带来幸福  Zsh，Brew，Sublime，Python，Node，Elixir |

### Fish

 |  标题|  描述  重点|
| :------------------------------------------------------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------- |
| [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)    |  社区鱼类框架.  |  包括许多插件和主题，以及安装，自动更新和脚手架工具.  |
| [Paul's dotfiles](https://github.com/paulirish/dotfiles)  |  大量的点文件和大量的自定义函数|  Fish，macOS，Homebrew，自定义Shell功能|
| [rkalis's dotfiles](https://github.com/rkalis/dotfiles)   |  维护良好的dotfile，包含Fish，存储库管理和Hammerspoon |  鱼，macOS，自制软件，存储库管理，Hammerspoon |

## Tools

- [Ansible](https://www.ansible.com) -极其简单的配置管理，应用程序部署，任务执行和多节点编排引擎.
- [bashdot](https://github.com/bashdot/bashdot) -完全用bash编写的极简主义点文件管理框架.
- [chezmoi](https://github.com/twpayne/chezmoi) -在多台计算机上安全地管理您的点文件.
- [dotbot](https://github.com/anishathalye/dotbot) -引导您的点文件的工具.
- [dotdrop](https://github.com/deadc0de6/dotdrop) -一次保存您的dotfile，将它们部署到任何地方.
- [dotfiles](https://github.com/jbernard/dotfiles) -轻松管理\ $ HOME中的点文件符号链接的工具.
- [Ellipsis](https://github.com/ellipsis/ellipsis) -dotfile的软件包管理器.
- [Fisher](https://github.com/jorgebucaran/fisher) -鱼的包装经理
- [fresh](https://freshshell.com)  -保持您的点文件新鲜.  Fresh是将其他人的外壳配置（别名，功能等）源到您自己的配置文件中的工具.
- [GNU Stow](http://www.gnu.org/software/stow/) -Symlink服务器场管理器，它采用位于文件系统上不同目录中的不同软件和/或数据包，并使它们看起来像安装在同一位置.
- [homeshick](https://github.com/andsens/homeshick) -用Bash编写的Git点文件同步器.
- [homesick](https://github.com/technicalpickles/homesick)  -您的主目录就是您的城堡.  不要将您的dotfile抛在后面（[article](https://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick)).
- [mackup](https://github.com/lra/mackup) -使您的应用程序设置保持同步（OS X / Linux）.
- [rcm](https://github.com/thoughtbot/rcm) -rc文件（dotfile）管理
- [themer](https://github.com/mjswensen/themer) -从dotfile内跨开发工具管理和生成主题.
- [vcsh](https://github.com/RichiH/vcsh) -$ HOME的版本控制系统，$ HOME中有多个Git存储库.
- [yadm](https://github.com/TheLocehiliosan/yadm) -使用共享的Git存储库和一些其他功能来管理多台计算机上文件集合的工具.

### macOS

- [Cider](https://github.com/msanders/cider) -使用Homebrew轻松启动.
- [dockutil](https://github.com/kcrawford/dockutil) -用于管理停靠项目的命令行工具
- [mas](https://github.com/mas-cli/mas) -Mac App Store命令行界面

## Miscellaneous

- [dotfiles.github.io](http://dotfiles.github.io) -您在GitHub上非官方的dotfiles指南.
- [OS X Defaults](https://github.com/kevinSuttle/macOS-Defaults) -集中精力开展令人敬畏的工作 [@mathiasbynens on .macos](https://github.com/mathiasbynens/dotfiles#sensible-macos-defaults).
- [Filesystem Hierarchy Standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard) -Linux发行版中的目录结构和目录内容.
- [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) - [Summary](https://wiki.archlinux.org/index.php/XDG_Base_Directory)
- [A lesson in shortcuts](https://www.reddit.com/r/linux/comments/at05xh/why_do_hidden_files_in_unix_begin_with_a_dot/egyj6lr/) -Rob Pike最初提出“隐藏”或“点”文件的想法（最初发布在Google+上）

## Related Lists

- [Awesome Shell](https://github.com/alebcay/awesome-shell) -精选的优秀命令行框架，工具包，指南和小玩意的列表.
- [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins) -适用于oh-my-zsh，antigen和Prezto的Zsh插件列表.
- [Awesome Dev Env](https://github.com/jondot/awesome-devenv) -精选的出色工具，资源和工作流程提示列表，可提供出色的开发环境.
- [Awesome Fish](https://github.com/jorgebucaran/awesome-fish) -精选的鱼壳包装，提示和资源列表.

## Archive/abandoned projects

- [Bashstrap](https://github.com/barryclark/bashstrap)
- [battleschool](https://github.com/spencergibb/battleschool)
- [Bork](https://github.com/mattly/bork) -用于配置管理的Bash DSL.
- [Eduardo's dotfiles](https://github.com/eduardolundgren/dotfiles)
- [Kevin's dotfiles](https://github.com/kdeldycke/dotfiles)
- [kody](https://github.com/jh3y/kody)
- [osxc](http://osxc.github.io)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Lars Kappert](https://www.webpro.nl) 放弃了此作品的所有版权以及相关或邻近的权利.
