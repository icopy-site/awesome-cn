## Awesome PowerShell [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/PowerShell/PowerShell/raw/master/assets/Powershell_256.png" align="right" width="80">](https://msdn.microsoft.com/en-us/powershell/)

令人愉快的策划清单 [PowerShell](https://en.wikipedia.org/wiki/PowerShell) 包和资源.

PowerShell是一种跨平台（Windows，Linux和macOS）自动化和配置工具，针对结构化数据（例如JSON，CSV，XML等），REST API和对象模型进行了优化.
它包括命令行shell和相关的脚本语言.

## Contents

* [API Wrapper](#api-wrapper)
* [Blogs](#blogs)
* [Books](#books)
* [Build Tools](#build-tools)
* [Code and Package Repositories](#code-and-package-repositories)
* [Commandline Productivity](#commandline-productivity)
* [Communities](#communities)
* [Documentation Helper](#documentation-helper)
* [Frameworks](#frameworks)
* [Editors and IDEs](#editors-and-ides)
* [Module Development Templates](#module-development-templates)
* [Package Managers](#package-managers)
* [Parallel Processing](#parallel-processing)
* [Podcasts](#podcasts)
* [Security](#security)
* [Testing](#testing)
* [Themes](#themes)
* [Videos](#videos)
* [Webserver](#webserver)
* [SharePoint](#sharepoint)
* [SQL Server](#sql-server)
* [Misc](#misc)

## API Wrapper

- [HipChatAdmin](https://github.com/cofonseca/HipChatAdmin) - 通过HipChat API与Atlassian HipChat简单集成的模块.
- [PSGitHub](https://github.com/pcgeek86/PSGitHub) - 此PowerShell模块包含通过其REST API管理GitHub的命令. 
- [Posh-Github](https://github.com/Iristyle/Posh-GitHub) - 公开GitHub API的Powershell cmdlet.
- [Posh-Gist](https://github.com/dfinke/Posh-Gist) - 用于与GitHub Gist交互的PowerShell cmdlet.
- [PSGist](https://github.com/dotps1/PSGist) - 与GitHub Gists配合使用的PowerShell模块.
- [PSAppVeyor](https://github.com/dotps1/PSAppVeyor) - 与AppVeyor REST Api交互的PowerShell模块.
- [PSSlack](https://github.com/RamblingCookieMonster/PSSlack) -  PowerShell模块，用于简单的Slack集成.
- [ConfluencePS](https://atlassianps.org/module/ConfluencePS/) - 一个模块，用于在powershell中使用Atlassian的Confluence进行交互（通过使用API​​）.
- [JiraPS](https://atlassianps.org/module/JiraPS/) - 用于与PowerShell中的Atlassian的Jira交互的模块（通过使用API​​）.

## Blogs

- [Windows PowerShell Blog](https://blogs.msdn.microsoft.com/powershell/) - 官方PowerShell团队博客.
- [Hey, Scripting Guy! Blog](http://blogs.technet.com/b/heyscriptingguy/) - 热门微软博客.
- [Learn Powershell | Achieve More](http://learn-powershell.net/) - 为Scripting Guy主持的Boe Prox个人博客.
- [PowerShellMagazine](http://www.powershellmagazine.com/) - 很棒的杂志.
- [Doug Finke](https://dfinke.github.io/#blog) - 作者 [PowerShell for Developers](http://shop.oreilly.com/product/0636920024491.do).
- [Mike F. Robbins](http://mikefrobbins.com/)   - 微软MVP.  SAPIEN Tech MVP.  Windows PowerShell TFM第4版的合着者.

## Books

- [Exploring PowerShell Automation](https://www.manning.com/books/exploring-powershell-automation) - 免费的电子书采样器，概述了如何管理您的环境. 
- [PowerShell in Depth](https://www.manning.com/books/powershell-in-depth)   - 管理员的首选参考.  解释和演示了每种主要的shell技术，技术和策略，提供了管理员在shell中几乎所有内容的全面参考.
- [Windows PowerShell in Action, Third Edition](https://www.manning.com/books/windows-powershell-in-action-third-edition) - 综合参考指南的最新版本.
- [Learn Windows PowerShell in a Month of Lunches, Third Edition](https://www.manning.com/books/learn-windows-powershell-in-a-month-of-lunches-third-edition)   - 专为繁忙的IT专业人士设计的创新教程.  每天只留出一小时 - 午餐时间会很完美 - 一个月，你将比你想象的更快地自动执行Windows任务.
- [Learn PowerShell Scripting in a Month of Lunches](https://www.manning.com/books/learn-powershell-scripting-in-a-month-of-lunches) - 开发，测试和部署脚本的过程指南，以及工具制作的艺术.

## Build Tools

* [psake](https://github.com/psake/psake) - 构建自动化工具，灵感来自rake（又名Ruby in Ruby）和bake（又名boo中的make）.
* [Invoke-Build](https://github.com/nightroman/Invoke-Build) - 构建和测试受psake启发的自动化工具.
* [PSDeploy](https://github.com/RamblingCookieMonster/PSDeploy) - 为简化多种类型的部署而构建的模块.
* [BuildHelpers](https://github.com/RamblingCookieMonster/BuildHelpers) -  CI / CD场景的各种辅助功能.
* [YDeliver](https://github.com/manojlds/YDeliver) - 针对.NET项目的构建和部署框架.

## Code and Package Repositories

- [GitHub](https://github.com/search?l=powershell&q=stars%3A%3E1&s=stars&type=Repositories)   - 寻找开源PowerShell项目？  它可能就在这里.
- [PowerShell Gallery](https://www.powershellgallery.com/) -  PowerShellGet使用的官方PowerShell包存储库.
- [TechNet Gallery](https://gallery.technet.microsoft.com/) - 从代码段到模块的各种PowerShell代码.

## Commandline Productivity

- [posh-git](https://github.com/dahlbyk/posh-git) - 一组PowerShell脚本，提供Git / PowerShell集成.
- [PSReadLine](https://github.com/lzybkr/PSReadLine)   -  Bash启发PowerShell的readline实现.  保持会话之间的历史记录，添加反向历史记录搜索并使整个命令行体验更好.
- [TabExpansionPlusPlus](https://github.com/lzybkr/TabExpansionPlusPlus) -  PowerShell模块，可以更轻松地自定义选项卡，并添加自定义参数完成程序库.
- [Jump-Location](https://github.com/tkellogg/Jump-Location) -  Powershell`cd`读取你的想法. [Autojump](https://github.com/wting/autojump) PowerShell的实现.
- [Zlocation](https://github.com/vors/ZLocation) - [z.sh](https://github.com/rupa/z)  PowerShell的实现.  与Jump-Location相似.
- [thefuck](https://github.com/nvbn/thefuck) - 华丽的应用程序，纠正您以前的控制台命令（通过键入`fuck`）.
- [pslinq](https://github.com/manojlds/pslinq) -  Powershell的LINQ（LINQ2Objects）.
- [posh-with](https://github.com/JanJoris/posh-with) - 使用单个工具为连续工作流命令前缀.
- [poco](https://gist.github.com/yumura/8df37c22ae1b7942dec7) - [peco](https://github.com/peco/peco)  实现.  交互式过滤工具.
- [PSDirTag](https://github.com/wtjones/PSDirTag)   -  DirTags是相对路径，在Powershell提示符中显示为变量，在您导航时更新.  导航文件夹结构时保存击键.
- [PSUtil](https://github.com/PowershellFrameworkCollective/PSUtil)   - 旨在使用户的控制台生活更方便.  它包括快捷方式，别名，键绑定和便利功能，旨在提高效率和减少打字.

## Communities

- [PowerShell.com](http://powershell.com/) - 论坛，博客文章等.
- [PowerShell.org](http://powershell.org/) - 论坛，峰会，社区博客帖子等.
- [/r/PowerShell](http://www.reddit.com/r/powershell) -  Reddit PowerShell社区.
- [Slack PowerShell team](http://slack.poshcode.org/) - Large chat room dedicated to PowerShell. Bridged with `#PowerShell` on irc.freenode.net.
- [Twitter #PowerShell](https://twitter.com/search?q=%23PowerShell&src=hash)   - 充满活力的PowerShell社区;  跟上新闻和博客内容的好方法.

## Documentation Helper

- [platyPS](https://github.com/PowerShell/platyPS) - 在Markdown中编写PowerShell外部帮助.
- [Invoke-CreateModuleHelpFile](https://github.com/gravejester/Invoke-CreateModuleHelpFile) -  PowerShell函数，用于为模块及其所有命令创建HTML帮助文件.
- [PScribo](https://github.com/iainbrighton/PScribo) -  PowerShell文档框架可以创建基于PowerShell的DSL（特定于域的语言）的HTML，Word，文本文件.

## Editors and IDEs

- [PowerShell Studio](https://www.sapien.com/software/powershell_studio) - 功能强大的PowerShell IDE，具有模块，帮助和用户界面开发工具，高DPI支持和定期更新.
- [PowerShell for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell) - 提供智能感知，代码导航，脚本分析，脚本调试等功能 [Visual Studio Code](https://code.visualstudio.com) 编辑.
- [PoshTools for Visual Studio](https://github.com/adamdriscoll/PoshTools) - 为Visual Studio提供PowerShell的IntelliSense，脚本调试和Pester测试支持.
- [PowerShell ISE](https://msdn.microsoft.com/en-us/powershell/scripting/core-powershell/ise/using-the-windows-powershell-ise) -  Microsoft Windows附带的官方PowerShell开发环境.
- [ISE Steroids](http://www.powertheshell.com/isesteroids/) -  PowerShell ISE的附加组件，它提供了丰富的附加功能，可以完成ISE开发体验.
- [PowerShell Plus](https://www.idera.com/productssolutions/freetools/powershellplus) - 一体化IDE.
- [SublimeText package](https://github.com/SublimeText/PowerShell) -  Sublime Text的PowerShell语言支持.
- [Atom package](https://github.com/jugglingnutcase/language-powershell) -  Atom的PowerShell语言支持.

## Module Development Templates
- [Plaster](https://github.com/PowerShell/Plaster) - Plaster is a template-based file and project generator written in PowerShell.
- [PSModuleDevelopment](https://github.com/PowershellFrameworkCollective/PSModuleDevelopment) - 使用此模块的低入口门槛和随意的便利性，在2分钟内开始使用模块模板.

## Frameworks

- [Carbon](http://get-carbon.org/) - 用于自动配置Windows计算机的DevOps.
- [PowerShell PowerUp](https://github.com/janikvonrotz/PowerShell-PowerUp) - 强大的服务器管理框架.
- [PSCX](https://github.com/Pscx/Pscx) -  PowerShell社区扩展 - 有用的其他cmdlet集.
- [PSFramework](https://github.com/PowershellFrameworkCollective/psframework) - 轻松地将配置，日志记录等添加到您自己的PowerShell模块中.

## Package Managers

- [PowershellGet](https://github.com/powershell/powershellget)   -  PowerShellGet是PowerShell的软件包管理器.  套餐可用 [PowerShellGallery](https://www.PowerShellGallery.com).
- [PsGet](http://psget.net/) - 用于从中央目录，本地文件或Web安装模块的命令集.
- [Chocolatey](https://chocolatey.org/)   -  Windows的包管理器.  在Windows上管理软件的理智方式.
- [GitLab](https://github.com/akamac/GitLabProvider) - 使用GitLab服务器作为包提供程序.

## Parallel Processing

- [PoshRSJob](https://github.com/proxb/PoshRSJob) - 提供PSjobs的替代方案，在后台运行命令具有更高的性能和更少的开销.
- [Invoke-Parallel](https://github.com/RamblingCookieMonster/Invoke-Parallel) - 此函数将接受脚本或脚本块，并且并行地针对指定的对象运行它.

## Podcasts

- [PowerScripting](https://powershell.org/podcast/) - 由Jon Walz和Hal Rottenberg主持的每周表演.
- [The PowerShell News Podcast](https://powershellnews.podbean.com/) - 这个播客是PowerShell的最新消息.

## Security

- [File System Security](https://gallery.technet.microsoft.com/scriptcenter/1abd77a5-9c0b-4a2b-acef-90dbb2b84e85) - 允许更轻松地管理文件和文件夹的权限.
- [PowerShellArsenal](https://github.com/mattifestation/PowerShellArsenal) - 用于辅助逆向工程师的模块.
- [PowerTools](https://github.com/Veil-Framework/PowerTools) - 收集以进攻性行动为重点的项目.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 用于Windows的流行的活盘取证平台.
- [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - 后开发框架.
- [PowerShellEmpire](https://github.com/PowerShellEmpire/Empire) - 后期开发代理商.
- [PSReflect](https://github.com/mattifestation/PSReflect)   - 在PowerShell中轻松定义内存中的枚举，结构和Win32函数.  对攻击很有用 [example](https://github.com/FuzzySecurity/PowerShell-Suite/tree/master/Bypass-UAC).
- [BloodHound](https://github.com/BloodHoundAD/BloodHound) - 轻松识别高度复杂的攻击路径，否则无法快速识别. 

## Testing

- [Pester](https://github.com/pester/Pester) -  Powershell BDD风格测试框架.
- [Format-Pester](https://github.com/equelin/format-pester) - 用于记录Pester结果的Powershell模块 - 将Pester结果导出为HTML，Word，文本文件 [PScribo](https://github.com/iainbrighton/PScribo) .

## Themes

- [Oh-My-Posh](https://github.com/JanJoris/oh-my-posh) - 可以通过一个命令启用的美丽主题吨（包括许多令人敬畏的电力线主题）.
- [Powerline](https://github.com/Jaykul/PowerLine) -  PowerShell类，提供更丰富的输出和提示.

## Videos

- [PowerShell Unplugged with Jeffrey Snover and Don Jones Ignite 2017](https://www.youtube.com/watch?v=D15vh-ryJGk)  PowerShell的发明者谈论“最新和最酷的PowerShell功能，以帮助您自动化和管理混合云”.  专注于PowerShell社区
- [Getting Started With PowerShell 3.0 Jump Start](https://mva.microsoft.com/en-US/training-courses/getting-started-with-powershell-30-jump-start-8276) -  Jump starts系列适用于以前没有PowerShell经验的IT专业人员，并希望快速学习.
- [Advanced Tools & Scripting with PowerShell 3.0](https://channel9.msdn.com/Series/advpowershell3) -  IT专业人员，参加此高级PowerShell课程，了解如何将实时管理和自动化脚本转换为有用的可重用工具和cmdlet.
- [What's New in PowerShell v5](https://mva.microsoft.com/en-US/training-courses/whats-new-in-powershell-v5-16434) - 通过PowerShell 5.0版中一些令人兴奋的新功能的描述.
- [PowerShell Open Source Project](https://channel9.msdn.com/series/PowerShell-Open-Source-Project) - 视频集合充分展示了PowerShell开源项目如何在Linux上运行.
- [PowerShell on Linux and Open Source](https://channel9.msdn.com/Blogs/hybrid-it-management/PowerShell-on-Linux-and-Open-Source) -  PowerShell开源项目简介及其在linux上的运行方式.
- [PowerShell](https://channel9.msdn.com/Shows/MsftPowerShell)   - 此节目将包括讨论PowerShell自动化平台，所需状态配置（DSC），基础设施代码和相关概念的视频！  这些视频由Windows PowerShell的Microsoft MVP Trevor Sullivan创建.

## Webserver

- [Flancy](https://github.com/toenuff/flancy) - 适用于Windows PowerShell的Web微框架.
- [NancyPS](https://github.com/Jaykul/NancyPS) -  Nancy，在PowerShell中自托管，带有脚本方法处理程序.
- [PoSH Server](http://www.poshserver.net/) - 安全，灵活，轻量级的Web服务器，以满足您的要求.
- [Polaris](https://github.com/PowerShell/Polaris) -  PowerShell的跨平台，极简主义Web框架
- [WebCommander](https://github.com/vmware/webcommander) - 在友好的Web GUI或Web服务中运行脚本和查看结果.

## SharePoint

- [AutoSPInstaller](https://autospinstaller.com/) - 自动SharePoint 2010-2019安装脚本.
- [Client-side SharePoint](https://sharepointpowershell.codeplex.com/) -  SharePoint 2010,2013和Online的API.
- [SPReplicator](https://github.com/potatoqualitee/SPReplicator) -  SPReplicator有助于将CSV列表数据复制到CSV，SQL Server，SharePoint本身等等.

## SQL Server

- [dbachecks](https://dbachecks.io) -  SQL Server环境验证（众包SQL Server DBA检查表）
- [dbatools](https://dbatools.io) - 通过实例迁移等方式帮助SQL Server专业人员提高工作效率.

## Misc

- [DbgShell](https://github.com/Microsoft/DbgShell) -  Windows调试器引擎的PowerShell前端.
- [poke](https://github.com/oising/poke) -  PowerShell的疯狂酷反射模块.
  探索和调用私人API，就像没有人在看.
  适用于安全研究，测试和快速黑客攻击.
- [psInlineProgress](https://github.com/gravejester/psInlineProgress) - 在PowerShell中编写内联进度条. 
