<div class="github-widget" data-repo="webpro/awesome-dotfiles"></div>
## Awesome dotfiles

精选的点文件资源列表. 灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列出事情.
请注意，某些文章或工具可能看起来过时或过时，但这通常意味着它们是久经考验且成熟
 （就像点文件本身）. 欢迎提出新文章、项目或工具！

## Articles

### Introductions

- [Getting started with dotfiles](https://www.webpro.nl/articles/getting-started-with-dotfiles)
  ([L. Kappert](https://github.com/webpro))
- [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/)
  ([D. Vints](https://github.com/driesvints))
- [Managing your dotfiles](https://www.webpro.nl/articles/managing-your-dotfiles)
- [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
- [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)
- [I do Dotfiles!](https://jogendra.dev/i-do-dotfiles)

### Tutorials

- [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/)
- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449);
  [Part 2](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
- [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
- [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
- [Managing your dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
- [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)
- [Dotfiles Management](https://mitxela.com/projects/dotfiles_management)

### Shell startup

- [Shell startup scripts](https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
- [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

- [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
- [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
- [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
- [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

那里有许多很棒的点文件存储库，每个都包含自己的灵感和精华. 一种方法可以通过
他们是为了 [search GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories).

另见：

- [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
- [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
- 提示：在 GitHub 上搜索文件名，例如
  [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93&type=Code&q=in%3Apath+.gitconfig).

## Example dotfiles repos

最受欢迎、维护良好且协作的点文件存储库和框架的集合. 一些项目
只包含点文件. 其他人更进一步，允许您轻松添加自己的自定义点文件，其中一些包括
管理点文件和插件的脚本.

### Bash

 | 标题 | 说明 | 聚焦 |
| :------------------------------------------------------------------ | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it](https://github.com/Bash-it/bash-it)                        | 社区 bash 框架.  | 自动完成、主题、别名、自定义功能. 结构良好的框架.  |
| [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)      |  macOS 的明智黑客默认设置 | 这里有很多优点，很棒的协作社区努力.  |
| [Maximum Awesome](https://github.com/square/maximum-awesome)         |  vim 和 tmux 的配​​置文件 | 维姆，TMUX. 为 Mac OS X 构建.
| [webpro's dotfiles](https://github.com/webpro/dotfiles)              |  macOS 点文件 |  Bash、Homebrew、Brew Cask、Git、Node.js、Hammerspoon.  |
| [rootbeersoup's dotfiles](https://github.com/darrylabbate/dotfiles)  | 轻松的 Bash、Vim 和 macOS 配置 |  `卷曲\|  sh` 安装程序和 Makefile 为永久或临时配置提供可移植且轻松的设置.  |
| [Luke's voidrice](https://github.com/LukeSmithxyz/voidrice)          |  Arch linux 点文件引导程序 | 无臃肿，通常很糟糕的软件. 用于在 markdown 或 latex 中编辑文档的 Vim 配置 |

### Zsh

 | 标题 | 说明 | 聚焦 |
| :------------------------------------------------------------ | :-------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles)  |  vim、zsh、git 和 tmux 配置文件集 |  Zsh、vim、tmux、git、自制软件. 用途 [rcm](https://github.com/thoughtbot/rcm).                                                                                      |
| [oh-my-zsh](https://ohmyz.sh)                                  | 用于管理 zsh 配置的社区驱动框架.  | 包括 200 多个可选插件（rails、git、OSX、hub、capistrano、brew、ant、php、python 等）、超过 140 个主题来为您的早晨增添趣味，以及一个自动更新工具.  |
| [Prezto](https://github.com/sorin-ionescu/prezto)              |  Zsh 的配置框架.  | 使用合理的默认值、别名、函数、自动完成和提示主题丰富命令行界面环境.  |
| [Dries's dotfiles](https://github.com/driesvints/dotfiles)     |  macOS 点文件的简化方法 |  Zsh, Oh My Zsh, macOS, Homebrew, Mackup |
| [sobolevn's dotfiles](https://github.com/sobolevn/dotfiles)    | 为开发者带来快乐的点文件 |  Zsh、Brew、Sublime、Python、Node、Elixir |

### Fish

 | 标题 | 说明 | 聚焦 |
| :------------------------------------------------------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------- |
| [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)    | 社区鱼框架.  | 包括许多插件和主题，带有安装、自动更新和脚手架工具.  |
| [Paul's dotfiles](https://github.com/paulirish/dotfiles)  | 具有大量很酷的自定义函数的丰富点文件 |  Fish、macOS、Homebrew、自定义 Shell 函数 |
| [rkalis's dotfiles](https://github.com/rkalis/dotfiles)   | 维护良好的点文件，具有 Fish、存储库管理和 Hammerspoon |  Fish、macOS、Homebrew、存储库管理、Hammerspoon |

### Ansible

 | 标题 | 说明 | 聚焦 |
| :------------------------------------------------------ | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots](https://github.com/Addvilz/dots)                 | 新的和升级的点文件，现在有了 Ansible！  | 使用 Ansible 实现完全自动化的桌面设置、配置和维护 |
| [sloria's dotfiles](https://github.com/sloria/dotfiles)  |  sloria 的点文件作为 Ansible 角色 | 使用单个命令设置完整的本地开发环境 |

## Tools

- [Ansible](https://www.ansible.com) - 极其简单的配置管理、应用程序部署，
  任务执行和多节点编排引擎.
- [bashdot](https://github.com/bashdot/bashdot) - 完全用 bash 编写的极简点文件管理框架.
- [chezmoi](https://github.com/twpayne/chezmoi) - 跨多台机器安全地管理您的点文件.
- [comtrya](https://github.com/comtrya/comtrya) - Configuration management for localhost, written in Rust, for Linux,
  BSD、macOS 和 Windows
- [dotbare](https://github.com/kazhala/dotbare) - 使用 fzf 交互式管理点文件.
- [dotbot](https://github.com/anishathalye/dotbot) - 引导您的点文件的工具.
- [dotdrop](https://github.com/deadc0de6/dotdrop) - 保存您的点文件一次，将它们部署到任何地方.
- [Fisher](https://github.com/jorgebucaran/fisher) - Fish 的包管理器
- [fresh](https://freshshell.com)  - 保持你的点文件新鲜.  Fresh 是一个获取 shell 配置（别名，
  功能等）从别人到你自己的配置文件.
- [GNU Stow](http://www.gnu.org/software/stow/) - Symlink 农场管理器，它采用不同的软件包和/或
  数据位于文件系统上的不同目录中，并使它们看起来像是安装在同一个地方.
- [homeshick](https://github.com/andsens/homeshick) - 用 Bash 编写的 Git 点文件同步器.
- [mackup](https://github.com/lra/mackup) - 使您的应用程序设置保持同步 (OS X/Linux).
- [Pearl](https://github.com/pearl-core/pearl) - 允许控制、同步、共享点文件的包管理器
  在 shell 或编辑器启动期间自动激活的包. 已经有多种套餐可供选择
  在里面 [Official Pearl Hub](https://github.com/pearl-hub) （适用于 Linux 和 OSX）.
- [rcm](https://github.com/thoughtbot/rcm) -rc文件（dotfile）管理.
- [themer](https://github.com/themerdev/themer) - 从内部跨开发工具管理和生成主题
  你的点文件.
- [toml-bombadil](https://github.com/oknozor/toml-bombadil) - 模板化和管理您的点文件.
- [yadm](https://github.com/TheLocehiliosan/yadm) - 用于管理跨多台计算机的文件集合的工具，
  使用共享的 Git 存储库和一些附加功能.

### macOS

- [dockutil](https://github.com/kcrawford/dockutil) - 用于管理停靠项目的命令行工具
- [mas](https://github.com/mas-cli/mas) - Mac App Store 命令行界面
- [zero](https://github.com/zero-sh/zero.sh) - 适用于 macOS 的极其简单的个人引导工具.

## Miscellaneous

- [dotfiles.github.io](https://dotfiles.github.io/) - GitHub 上的点文件非官方指南.
- [Filesystem Hierarchy Standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard) - 目录结构和
  Linux 发行版中的目录内容.
- [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) -
  [Summary](https://wiki.archlinux.org/title/XDG_Base_Directory)
- [A lesson in shortcuts](https://www.reddit.com/r/linux/comments/at05xh/comment/egyj6lr/) - “隐藏”或“隐藏”的想法
  “点”文件由 Rob Pike 诞生（最初发布在 Google+ 上）

## Related Lists

- [Awesome Dev Env](https://github.com/jondot/awesome-devenv) - 很棒的工具、资源和工作流程的精选列表
  制作出色开发环境的技巧.
- [Awesome Fish](https://github.com/jorgebucaran/awsm.fish) - 精选的包、提示和资源列表
  鱼壳.
- [Awesome Shell](https://github.com/alebcay/awesome-shell) - 很棒的命令行框架、工具包的精选列表，
  指南和小发明.
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 令人惊叹的开源精选列表
  系统管理员资源.
- [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins) - 适合使用的 Zsh 插件列表
  oh-my-zsh，抗原和 Prezto.
- [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - 精选的终端框架、插件和
  CLI 爱好者的资源.

## Archive/abandoned projects

- [antigen](http://antigen.sharats.me)
- [Bashstrap](https://github.com/barryclark/bashstrap)
- [battleschool](https://github.com/spencergibb/battleschool)
- [Bork](https://github.com/mattly/bork)
- [Cider](https://github.com/msanders/cider)
- [dev-setup](https://github.com/donnemartin/dev-setup)
- [dotfiles](https://github.com/jbernard/dotfiles)
- [dotstow](https://github.com/clayrisser/dotstow)
- [Eduardo's dotfiles](https://github.com/eduardolundgren/dotfiles)
- [ellipsis](https://github.com/ellipsis/ellipsis)
- [emplace](https://github.com/tversteeg/emplace)
- [holman does dotfiles](https://github.com/holman/dotfiles)
- [homesick](https://github.com/technicalpickles/homesick)
- [Kevin's dotfiles](https://github.com/kdeldycke/dotfiles)
- [kody](https://github.com/jh3y/kody)
- [OS X Defaults](https://github.com/kevinSuttle/macOS-Defaults)
- [osxc](http://osxc.github.io)
- [vcsh](https://github.com/RichiH/vcsh)
  ([article](https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html),
  [article](https://www.kunxi.org/2014/02/manage-dotfiles-using-vcsh-and-mr/))
- [YADR](http://skwp.github.io/dotfiles/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Lars Kappert](https://www.webpro.nl) 已放弃所有版权及相关或
本作品的邻接权.
