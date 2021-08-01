<div class="github-widget" data-repo="herrbischoff/awesome-macos-command-line"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<h1><img src="https://cdn.rawgit.com/herrbischoff/awesome-macos-command-line/cab824f0/assets/logo.svg" alt="Awesome macOS Command Line" width="600"></h1>

&gt; 特定于 OS X 的 shell 命令和工具的精选列表.
>
 &gt; _“你不必什么都知道. 您只需要知道在哪里可以找到它
 &gt; 必要时.”  （约翰·布伦纳）_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

如果您想做出贡献，我们强烈建议您这样做. 请阅读
[contribution guidelines](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/contributing.md).

更多终端shell优点，还请看这份榜单的姐妹榜单
[很棒的命令行
Apps](https://github.com/herrbischoff/awesome-command-line-apps).


## Women Empowerment in Zanzibar

减少一点业力，支持桑给巴尔的妇女赋权
帮助[资助当地生产可重复使用的女性卫生用品
产品]（https://www.gofundme.com/f/women-empowerment-in-zanzibar）. 一个很
我亲爱的朋友负责这个项目. 他们已经能够购买数百个
教育书籍. 有时，产生巨大影响所需的时间很少. 如果
你想感谢我或支持这项工作，捐赠. 此外，任何电流
并且未来通过 GitHub 或其他渠道赞助我的工作将流一个
百分之一百的给非政府组织.


## Foreword

我真的只有一件事想在这里说明：[男人
页](https://en.wikipedia.org/wiki/Man_page).  [男人
页]（https://www.cs.mcgill.ca/~guide/help/man.html）.  [男人
页]（https://xkcd.com/1692/）. 好吧，三件事. 但这一件事似乎
如此重要，我不得不多次提及. 如果你不这样做
已经，您应该养成在搜索之前查阅手册页的习惯
其他任何地方.  Unix 风格的手册页是极好的文档来源.
甚至还有一个关于 `man` 命令本身的手册页：

```sh
男人男人
```

它还解释了手册页中的数字所指的内容——例如“man(1)”.





## Appearance

### Subpixel Anti-Aliasing (Font Smoothing)

自 macOS 10.14 (Mojave) 以来的设置.

```sh
## Enable
默认写 -g CGFontRenderingFontSmoothingDisabled -bool false

## Disable (Default)
默认写 -g CGFontRenderingFontSmoothingDisabled -bool true

## Per Application
默认写 com.apple.textedit CGFontRenderingFontSmoothingDisabled -bool false

## Revert for Application
默认删除 com.apple.textedit CGFontRenderingFontSmoothingDisabled
```

### Transparency

#### Transparency in Menu and Windows
```sh
## Reduce Transparency
默认写 com.apple.universalaccess reduceTransparency -bool true

## Restore Default Transparency
默认写 com.apple.universalaccess reduceTransparency -bool false
```


### Wallpaper

#### Set Wallpaper
```sh
## Up to OS X 10.8 (Mountain Lion)
osascript -e &#39;告诉应用程序“Finder”将桌面图片设置为 POSIX 文件“/path/to/picture.jpg”&#39;

## Since OS X 10.9 (Mavericks)
sqlite3 ~/Library/Application\ Support/Dock/desktoppicture.db &quot;更新数据集值 = &#39;/path/to/picture.jpg&#39;&quot; &amp;&amp; killall Dock
```


## Applications

### App Store

#### List All Apps Downloaded from App Store

```sh
## Via find
find /Applications -path '*Contents/_MASReceipt/receipt' -maxdepth 4 -print |\sed 's#.app/Contents/_MASReceipt/receipt#.app#g; s#/Applications/##'

## Via Spotlight
mdfind kMDItemAppStoreHasReceipt = 1
```

#### Show Debug Menu
适用于 OS X 10.10 (Yosemite).
```sh
## Enable
默认写入 com.apple.appstore ShowDebugMenu -bool true

## Disable (Default)
默认写入 com.apple.appstore ShowDebugMenu -bool false
```


### Apple Remote Desktop

#### Kickstart Manual Pages
```sh
须藤/系统/库/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -help
```

#### Activate And Deactivate the ARD Agent and Helper
```sh
## Activate And Restart the ARD Agent and Helper
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -activate -restart -agent -console

## Deactivate and Stop the Remote Management Service
须藤/系统/库/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -stop
```

#### Remote Desktop Sharing
```sh
## Allow Access for All Users and Give All Users Full Access
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -configure -allowAccessFor -allUsers -privs -all

## Disable ARD Agent and Remove Access Privileges for All Users (Default)
须藤/系统/库/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -configure -access -off
```

#### Remove Apple Remote Desktop Settings
```sh
须藤 rm -rf /var/db/RemoteManagement ;  \
 sudo 默认删除 /Library/Preferences/com.apple.RemoteDesktop.plist ；  \
默认删除 ~/Library/Preferences/com.apple.RemoteDesktop.plist ；  \
 sudo rm -r /Library/Application\ Support/Apple/Remote\ Desktop/ ;  \
 rm -r ~/Library/Application\ Support/Remote\ Desktop/ ;  \
rm -r ~/Library/Containers/com.apple.RemoteDesktop
```

### Contacts

#### Debug Mode
```sh
## Enable
默认写 com.apple.addressbook ABShowDebugMenu -bool true

## Disable (Default)
默认写 com.apple.addressbook ABShowDebugMenu -bool false
```

### Google

#### Uninstall Google Update
```sh
~/Library/Google/GoogleSoftwareUpdate/GoogleSoftwareUpdate.bundle/Contents/Resources/ksinstall --nuke
```

### iTunes

#### Keyboard Media Keys
适用于 OS X 10.10 (Yosemite). 引入系统完整性保护
在 OS X 10.11 (El Capitan) 中阻止系统启动代理
unloaded.
```sh
## Stop Responding to Key Presses
launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist

## Respond to Key Presses (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

从 OS X 10.11 (El Capitan) 开始，您可以禁用 SIP 或求助于某种
hack，这将使任何用户都无法访问 iTunes，有效地
阻止它启动自己或它的助手. 请注意，对于所有人
意图和目的这会破坏您的 iTunes 安装并可能发生冲突
即将推出操作系统更新.
```sh
须藤 chmod 0000 /Applications/iTunes.app
```

### Mail

#### Show Attachments as Icons

```sh
默认写入 com.apple.mail DisableInlineAttachmentViewing -bool yes
```

#### Vacuum Mail Index
下面的 AppleScript 代码将退出 Mail，清空 SQLite 索引，然后
重新打开邮件. 在一段时间没有优化的大型电子邮件数据库上，
这可以显着提高响应能力和速度.
```applescript
(*
通过清理信封索引来加速 Mail.app
代码来自：http://web.archive.org/web/20071008123746/http://www.hawkwings.net/2007/03/03/scripts-to-automate-the-mailapp-envelope-speed-trick/
最初由“pmbuko”撰写，由 Romulo 修改
由 Brett Terpstra 更新 2012
由 Mathias Törnblom 2015 更新以支持 El Capitan 中的 V3 并保持向后兼容性
由 Andrei Miclaus 2017 更新以支持 Sierra 中的 V4
*)

告诉应用程序“邮件”退出
将 os_version 设置为执行 shell 脚本“sw_vers -productVersion”
将 mail_version 设置为“V2”
考虑数字字符串
    如果 &quot;10.10&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V3&quot;
    如果 &quot;10.12&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V4&quot;
    如果 &quot;10.13&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V5&quot;
    如果 &quot;10.14&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V6&quot;
    如果 &quot;10.15&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V7&quot;
    如果 &quot;11&quot; &lt;= os_version 然后将 mail_version 设置为 &quot;V8&quot;
结束考虑

设置 sizeBefore 来做 shell 脚本 &quot;ls -lnah ~/Library/Mail/&quot; &amp; mail_version &amp; &quot;/MailData | grep -E &#39;Envelope Index$&#39; | awk {&#39;print $5&#39;}&quot;
做 shell 脚本 &quot;/usr/bin/sqlite3 ~/Library/Mail/&quot; &amp; mail_version &amp; &quot;/MailData/Envelope\\ 索引真空&quot;

设置 sizeAfter 来执行 shell 脚本 &quot;ls -lnah ~/Library/Mail/&quot; &amp; mail_version &amp; &quot;/MailData | grep -E &#39;Envelope Index$&#39; | awk {&#39;print $5&#39;}&quot;

显示对话框（“邮件索引之前：” &amp; sizeBefore &amp; return &amp; “邮件索引之后：” &amp; sizeAfter &amp; return &amp; return &amp; “享受新的速度！”）

告诉应用程序“邮件”激活
```

### Safari

#### Change Default Fonts
```sh
默认写 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily Georgia
默认写 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFontSize 16
默认写 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily Menlo
默认写 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFixedFontSize 14
```

#### Develop Menu and Web Inspector
```sh
## Enable
默认写 com.apple.Safari IncludeInternalDebugMenu -bool true &amp;&amp; \
默认写 com.apple.Safari IncludeDevelopMenu -bool true &amp;&amp; \
默认写 com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey -bool true &amp;&amp; \
默认写 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled -bool true &amp;&amp; \
默认写 -g WebKitDeveloperExtras -bool true

## Disable (Default)
默认删除 com.apple.Safari IncludeInternalDebugMenu &amp;&amp; \
默认删除 com.apple.Safari IncludeDevelopMenu &amp;&amp; \
默认删除 com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey &amp;&amp; \
默认删除 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled &amp;&amp; \
默认删除 -g WebKitDeveloperExtras
```

#### Get Current Page Data
其他选项：`get source`、`get text`.
```sh
osascript -e &#39;告诉应用程序“Safari”获取前窗口当前选项卡的 URL&#39;
```

#### Use Backspace/Delete to Go Back a Page
```sh
## Enable
默认写入 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool YES

## Disable (Default)
默认写入 com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool NO
```

### Sketch

#### Export Compact SVGs
```sh
默认写 com.bohemiancoding.sketch3 exportCompactSVG -bool yes
```

### Skim

#### Turn Off Auto Reload Dialog
删除对话框并默认为自动重新加载.
```sh
默认值 write -app Skim SKAutoReloadFileUpdate -boolean true
```
### Terminal

#### Focus Follows Mouse
```sh
## Enable
默认写入 com.apple.Terminal FocusFollowsMo​​use -string YES

## Disable (Default)
默认写入 com.apple.Terminal FocusFollowsMo​​use -string NO
```

### TextEdit

#### Use Plain Text Mode as Default
```sh
默认写 com.apple.TextEdit RichText -int 0
```

### Visual Studio Code

#### VSCodeVim Key Repeat
```sh
## Enable
默认写入 com.microsoft.VSCode ApplePressAndHoldEnabled -bool false

## Disable (Default)
默认删除 com.microsoft.VSCode ApplePressAndHoldEnabled
```

#### Subpixel Anti-Aliasing
自 macOS 10.14 (Mojave) 以来的设置. 另请参阅系统范围的设置：
```sh
## Enable
默认写 com.microsoft.VSCode CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写 com.microsoft.VSCode.helper CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写 com.microsoft.VSCode.helper.EH CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写 com.microsoft.VSCode.helper.NP CGFontRenderingFontSmoothingDisabled -bool false

## Disable (Default)
默认删除 com.microsoft.VSCode CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除 com.microsoft.VSCode.helper CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除 com.microsoft.VSCode.helper.EH CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除 com.microsoft.VSCode.helper.NP CGFontRenderingFontSmoothingDisabled
```


## Backup

### Time Machine

#### Change Backup Interval
这会将间隔更改为 30 分钟. 整数值是时间
seconds.
```sh
sudo 默认写入 /System/Library/LaunchDaemons/com.apple.backupd-auto StartInterval -int 1800
```

#### Local Backups
Whether Time Machine performs local backups while the Time Machine backup
音量不可用.
```sh
## Status
默认读取/Library/Preferences/com.apple.TimeMachine MobileBackups

## Enable (Default)
须藤 tmutil 启用本地

## Disable
须藤 tmutil 禁用本地
```

从 macOS 10.13 (High Sierra) 开始，您无法禁用本地快照. 时间
机器现在总是创建一个本地 APFS 快照并使用该快照作为
数据源创建定期备份，而不是使用实时磁盘作为
源，就像 HFS 格式的磁盘一样.

#### Prevent Time Machine from Prompting to Use New Hard Drives as Backup Volume
```sh
sudo 默认写入 /Library/Preferences/com.apple.TimeMachine DoNotOfferNewDisksForBackup -bool true
```

#### Show Time Machine Logs
这个小脚本将输出过去 12 小时的 Time Machine 活动
其次是现场活动.
```sh
#!/bin/sh

filter=&#39;processImagePath 包含“backupd”，子系统以“com.apple.TimeMachine”开始&#39;

## show the last 12 hours
start=&quot;$(date -j -v-12H +&#39;%Y-%m-%d %H:%M:%S&#39;)&quot;

回声“”
echo &quot;[历史 (从 $start)]&quot;
回声“”

日志显示 --style syslog --info --start &quot;$start&quot; --predicate &quot;$filter&quot;

回声“”
回声“[以下]”
回声“”

日志流 --style syslog --info --predicate &quot;$filter&quot;
```

#### Toggle Backup While on Battery
```sh
## Status
sudo 默认读取 /Library/Preferences/com.apple.TimeMachine RequiresACPower

## Enable (Default)
sudo 默认写入 /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool true

## Disable
sudo 默认写入 /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool false
```

#### Verify Backup
从 OS X 10.11 开始，Time Machine 记录复制到的文件的校验和
快照. 不会为复制的文件追溯计算校验和
通过早期版本的 OS X.
```sh
须藤 tmutil verifychecksums /path/to/backup
```

## Developer

### Vim

#### Compile Sane Vim
通过 Homebrew 编译 MacVim 并带有所有花里胡哨的功能，包括覆盖
系统 Vim.
```sh
brew install macvim --HEAD
```

#### Neovim
通过 Homebrew 安装现代 Vim 替代品.
```sh
酿造安装neovim
```

### Xcode

#### Install Command Line Tools without Xcode
```sh
xcode-select --install
```

#### Remove All Unavailable Simulators
```sh
xcrun simctl 删除不可用
```


## Dock

#### Add a Stack with Recent Applications
自 macOS 10.14 (Mojave) 起已过时. 看 [Show Recent Apps](#show-recent-apps).
```sh
默认写入 com.apple.dock persistent-others -array-add &#39;{ &quot;tile-data&quot; = {​​ &quot;list-type&quot; = 1;  };  “瓷砖类型”=“最近瓷砖”；  }&#39; &amp;&amp; \
基尔码头
```

#### Add a Nameless Stack Folder and Small Spacer
```sh
默认写入 com.apple.dock persistent-others -array-add &#39;{“tile-data” = {};  &quot;瓷砖类型&quot;=&quot;小间隔瓷砖&quot;;  }&#39; &amp;&amp; \
基尔码头
```

#### Add a Space
```sh
默认写 com.apple.dock persistent-apps -array-add &#39;{&quot;tile-type&quot;=&quot;spacer-tile&quot;;}&#39; &amp;&amp; \
基尔码头
```

#### Add a Small Space
```sh
默认写 com.apple.dock persistent-apps -array-add &#39;{&quot;tile-type&quot;=&quot;small-spacer-tile&quot;;}&#39; &amp;&amp; \
基尔码头
```

#### Auto Rearrange Spaces Based on Most Recent Use
```sh
## Enable (Default)
默认写 com.apple.dock mru-spaces -bool true &amp;&amp; \
基尔码头

## Disable
默认写 com.apple.dock mru-spaces -bool false &amp;&amp; \
基尔码头
```

#### Automatically Hide
```sh
## Enable
默认写 com.apple.dock autohide -bool true &amp;&amp; \
基尔码头

## Disable (Default)
默认写 com.apple.dock autohide -bool false &amp;&amp; \
基尔码头
```

#### Icon Bounce
全局设置 Dock 图标在相应应用程序时是否应该弹跳
需要你的注意.
```sh
## Enable (Default)
默认写 com.apple.dock no-bouncing -bool true &amp;&amp; \
基尔码头

## Disable
默认写 com.apple.dock no-bouncing -bool false &amp;&amp; \
基尔码头
```

#### Lock the Dock Size
```sh
## Enable
默认写 com.apple.Dock size-immutable -bool yes &amp;&amp; \
基尔码头

## Disable (Default)
默认写 com.apple.Dock size-immutable -bool no &amp;&amp; \
基尔码头
```

#### Reset Dock
```sh
默认删除 com.apple.dock &amp;&amp; \
基尔码头
```

#### Resize
完全调整 Dock 的主体大小. 要调整大小，请将“0”值更改为整数.
```sh
默认写 com.apple.dock tilesize -int 0 &amp;&amp; \
基尔码头
```

#### Scroll Gestures
使用触摸板或鼠标滚轮与 Dock 项目进行交互. 让你
to use an upward scrolling gesture to open stacks. Using the same gesture on
正在运行的应用程序调用 Exposé/Mission Control.
```sh
## Enable
默认写 com.apple.dock scroll-to-open -bool true &amp;&amp; \
基尔码头

## Disable (Default)
defaults write com.apple.dock scroll-to-open -bool false && \
基尔码头
```

#### Set Auto Show/Hide Delay
浮点数以毫秒为单位定义显示/隐藏延迟.
```sh
默认写 com.apple.dock autohide-time-modifier -float 0.4 &amp;&amp; \
默认写 com.apple.dock autohide-delay -float 0 &amp;&amp; \
基尔码头
```

#### Show Hidden App Icons
```sh
## Enable
默认写 com.apple.dock showhidden -bool true &amp;&amp; \
基尔码头

## Disable (Default)
默认写 com.apple.dock showhidden -bool false &amp;&amp; \
基尔码头
```

#### Show Only Active Applications
```sh
## Enable
默认写 com.apple.dock static-only -bool true &amp;&amp; \
基尔码头

## Disable (Default)
默认写 com.apple.dock static-only -bool false &amp;&amp; \
基尔码头
```

#### Show Recent Apps
自 macOS 10.14 (Mojave) 以来的设置.
```sh
## Disable
默认写 com.apple.dock show-recents -bool false &amp;&amp; \
基尔码头

## Enable (Default)
默认写 com.apple.dock show-recents -bool true &amp;&amp; \
基尔码头
```

#### Single App Mode
单击 Dock 中的应用程序图标时，将出现相应的窗口
到前面，但所有其他应用程序窗口将被隐藏.
```sh
## Enable
默认写 com.apple.dock single-app -bool true &amp;&amp; \
基尔码头

## Disable (Default)
默认写 com.apple.dock single-app -bool false &amp;&amp; \
基尔码头
```


## Documents

#### Convert File to HTML
支持的格式是纯文本、富文本 (rtf) 和 Microsoft Word (doc/docx).
```sh
textutil -convert html file.ext
```


## Files, Disks and Volumes

#### Create an Empty File
创建一个空的 10 GB 测试文件.
```sh
mkfile 10g /path/to/file
```

#### Disable Sudden Motion Sensor
当您使用 SSD 时，将其打开是没有用的.
```sh
须藤 pmset -a 短信 0
```

#### Eject All Mountable Volumes
唯一可靠的方法是发送 AppleScript 命令到
Finder.
```sh
osascript -e &#39;告诉应用程序“Finder”弹出（每个可弹出的磁盘为真）&#39;
```

#### Repair File Permissions
您不必为此使用磁盘工具 GUI.
```sh
sudo diskutil repairPermissions /
```
&gt; 从 OS X 10.11 (El Capitan) 开始，系统文件权限为
 &gt; 自动保护. 不再需要验证或修复
&gt; 磁盘工具的权限.
> ([Source](https://support.apple.com/en-us/HT201560))

#### Set Boot Volume
```sh
## Up to OS X 10.10 (Yosemite)
bless --mount &quot;/path/to/mounted/volume&quot; --setBoot

## From OS X 10.11 (El Capitan)
须藤 systemsetup -setstartupdisk /System/Library/CoreServices
```

#### Show All Attached Disks and Partitions
```sh
磁盘列表
```

#### View File System Usage
文件系统访问信息的连续流.
```sh
须藤 fs_usage
```
### APFS

自 macOS 10.13 (High Sierra) 起出现. 没有中央实用程序和用途
是不一致的，因为大多数功能都包含在 `tmutil` 中.

#### Convert Volume from HFS+ to APFS
```sh
/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert /path/to/file/system
```

#### Create New APFS Filesystem
```sh
/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs /path/to/device
```

#### Create Snapshot
```sh
tmutil 本地快照
```

#### Delete Snapshot
```sh
tmutil deletelocalsnapshots com.apple.TimeMachine.2018-01-26-044042
````

#### List Snapshots
```sh
tmutil 列表本地快照 /
```

#### Mount Snapshot
快照是只读的.
```sh
mkdir ~/mnt
/System/Library/Filesystems/apfs.fs/Contents/Resources/mount_apfs -s com.apple.TimeMachine.2018-01-26-044042 / ~/mnt
```

### Disk Images

```sh
hdiutil create -volname &quot;卷名&quot; -srcfolder /path/to/folder -ov diskimage.dmg
```

如果您想加密磁盘映像：
```sh
hdiutil create -encryption -stdinpass -volname &quot;卷名&quot; -srcfolder /path/to/folder -ov encrypted.dmg
```

默认情况下，系统会提示您输入密码. 你可以通过管道自动化
在密码中：
```sh
 echo -n 你的密码 |  hdiutil create -encryption -stdinpass -volname &quot;卷名&quot; -srcfolder /path/to/folder -ov encrypted.dmg
```

#### Burn Disk Images to DVD
此命令适用于 .iso、.img 和 .dmg 图像.
```sh
hdiutil 刻录 /path/to/image_file
```

#### Create Temporary High-Performance Disk
磁盘由物理 RAM 支持，并且比普通磁盘快几倍
固态硬盘. 磁盘弹出后无法恢复其内容.
以下示例适用于 500 MiB RAM 磁盘，请根据需要进行调整.
```sh
## Up to macOS 10.14 (Mojave)
让 DISKSIZE=500*2048 &amp;&amp; \
diskutil erasevolume HFS+“RAM 磁盘”`hdiutil attach -nomount ram://$DISKSIZE`

## From macOS 10.15 (Catalina) on
让 &quot;DISKSIZE = 500*2048&quot; &amp;&amp; \
diskutil erasevolume HFS+“RAM 磁盘”`hdiutil attach -nomount ram://$DISKSIZE`
```

#### Disable Disk Image Verification
```sh
默认写 com.apple.frameworks.diskimages skip-verify -bool true &amp;&amp; \
默认写入 com.apple.frameworks.diskimages skip-verify-locked -bool true &amp;&amp; \
默认写入 com.apple.frameworks.diskimages skip-verify-remote -bool true
```

#### Make Volume OS X Bootable
```sh
bless --folder &quot;/path/to/mounted/volume/System/Library/CoreServices&quot; --bootinfo --bootefi
```

#### Mount Disk Image
```sh
hdiutil attach /path/to/diskimage.dmg
```

#### Unmount Disk Image
```sh
hdiutil 分离 /dev/disk2s1
```

#### Write Disk Image to Volume
就像磁盘工具“恢复”功能一样.
```sh
Sudo ASR -restore -noverify -source /path/to/diskimage.dmg -target / volume / VolumeToRestoreTo
```


## Finder

### Desktop

#### Show External Media
外置硬盘、拇指驱动器等.
```sh
## Enable
默认写入 com.apple.finder ShowExternalHardDrivesOnDesktop -bool true &amp;&amp; \
杀戮查找器

## Disable (Default)
默认写入 com.apple.finder ShowExternalHardDrivesOnDesktop -bool false &amp;&amp; \
杀戮查找器
```

#### Show Internal Media
内置 HD 或 SSD.
```sh
## Enable
默认写入 com.apple.finder ShowHardDrivesOnDesktop -bool true &amp;&amp; \
杀戮查找器

## Disable (Default)
默认写入 com.apple.finder ShowHardDrivesOnDesktop -bool false &amp;&amp; \
杀戮查找器
```

#### Show Removable Media
CD、DVD、iPod 等.
```sh
## Enable
默认写 com.apple.finder ShowRemovableMediaOnDesktop -bool true &amp;&amp; \
杀戮查找器

## Disable (Default)
默认写 com.apple.finder ShowRemovableMediaOnDesktop -bool false &amp;&amp; \
杀戮查找器
```

#### Show Network Volumes
AFP、SMB、NFS、WebDAV 等
```sh
## Enable
默认写入 com.apple.finder ShowMountedServersOnDesktop -bool true &amp;&amp; \
杀戮查找器

## Disable (Default)
默认写 com.apple.finder ShowMountedServersOnDesktop -bool false &amp;&amp; \
杀戮查找器
```

### Files and Folders

#### Clear All ACLs
```sh
须藤 chmod -RN /path/to/folder
```

#### Increase Number of Recent Places
```sh
默认写 -g NSNavRecentPlacesLimit -int 10 &amp;&amp; \
杀戮查找器
```

#### Show All File Extensions
```sh
默认写 -g AppleShowAllExtensions -bool true
```

#### Set Protected Flag
这相当于 Finder 的“锁定”状态.
```sh
## Disable (Default)
sudo chflags -R nouchg /path/to/file/or/folder

## Enable
sudo chflags -R uchg /path/to/file/or/folder
```

#### Show Hidden Files
```sh
## Show All
默认写 com.apple.finder AppleShowAllFiles true

## Restore Default File Visibility
默认写入 com.apple.finder AppleShowAllFiles false
```

#### Show Full Path in Finder Title
```sh
默认写 com.apple.finder _FXShowPosixPathInTitle -bool true
```

#### Toggle Folder Visibility in Finder
默认情况下，`~/Library` 文件夹是隐藏的. 您可以轻松地再次显示它. 这
相同的方法适用于所有其他文件夹.
```sh
## Hidden (Default)
chflags 隐藏 ~/库

## Visible
chflags nohidden ~/Library
```

### Layout

#### Show "Quit Finder" Menu Item
可以使用默认快捷方式查看 Finder 菜单项“退出 Finder”
<kbd>Cmd</kbd> + <kbd>Q</kbd>
```sh
## Enable
默认写 com.apple.finder QuitMenuItem -bool true &amp;&amp; \
杀戮查找器

## Disable (Default)
默认写 com.apple.finder QuitMenuItem -bool false &amp;&amp; \
杀戮查找器
```

#### Smooth Scrolling
如果您使用的是弄乱动画的较旧 Mac，则很有用.
```sh
## Disable
默认写入 -g NSScrollAnimationEnabled -bool false

## Enable (Default)
默认写入 -g NSScrollAnimationEnabled -bool true
```

#### Rubberband Scrolling
```sh
## Disable
默认写入 -g NSScrollViewRubberbanding -bool false

## Enable (Default)
默认写 -g NSScrollViewRubberbanding -bool true
```

#### Expand Save Panel by Default
```sh
默认写 -g NSNavPanelExpandedStateForSaveMode -bool true &amp;&amp; \
默认写入 -g NSNavPanelExpandedStateForSaveMode2 -bool true
```

#### Desktop Icon Visibility
```sh
## Hide Icons
默认写 com.apple.finder CreateDesktop -bool false &amp;&amp; \
杀戮查找器

## Show Icons (Default)
默认写 com.apple.finder CreateDesktop -bool true &amp;&amp; \
杀戮查找器
```

#### Path Bar
```sh
## Show
默认写 com.apple.finder ShowPathbar -bool true

## Hide (Default)
默认写 com.apple.finder ShowPathbar -bool false
```

#### Scrollbar Visibility
可能的值：“WhenScrolling”、“Automatic”和“Always”.
```sh
默认写入 -g AppleShowScrollBars -string &quot;Always&quot;
```

#### Status Bar
```sh
## Show
默认写 com.apple.finder ShowStatusBar -bool true

## Hide (Default)
默认写 com.apple.finder ShowStatusBar -bool false
```

#### Save to Disk by Default
将默认保存目标设置为本地磁盘，而不是 iCloud.
```sh
默认写入 -g NSDocumentSaveNewDocumentsToCloud -bool false
```

#### Set Current Folder as Default Search Scope
```sh
默认写入 com.apple.finder FXDefaultSearchScope -string &quot;SCcf&quot;
```

#### Set Default Finder Location to Home Folder
```sh
默认写 com.apple.finder NewWindowTarget -string &quot;PfLo&quot; &amp;&amp; \
默认写入 com.apple.finder NewWindowTargetPath -string &quot;file://${HOME}&quot;
```

#### Set Sidebar Icon Size
将大小设置为“中等”.
```sh
默认写入 -g NSTableViewDefaultSizeMode -int 2
```

### Metadata Files

#### Disable Creation of Metadata Files on Network Volumes
避免创建 `.DS_Store` 和 AppleDouble 文件.
```sh
默认写入 com.apple.desktopservices DSDontWriteNetworkStores -bool true
```

#### Disable Creation of Metadata Files on USB Volumes
避免创建 `.DS_Store` 和 AppleDouble 文件.
```sh
默认写入 com.apple.desktopservices DSDontWriteUSBStores -bool true
```

### Opening Things

#### Change Working Directory to Finder Path
如果打开了多个窗口，它会选择最上面的一个.
```sh
cd &quot;$(osascript -e &#39;tell app &quot;Finder&quot; to POSIX path of (insertion location as alias)&#39;)&quot;
```

#### Open URL
```sh
打开 https://github.com
```

#### Open File
```sh
打开 README.md
```

#### Open Applications
您可以使用 `-a` 打开应用程序.
```sh
open -a “谷歌浏览器” https://github.com
```

#### Open Folder
```sh
打开/路径/到/文件夹/
```

#### Open Current Folder
```sh
打开 .
```


## Fonts

#### Clear Font Cache for Current User
要清除所有用户的字体缓存，请将 `sudo` 放在这些命令前面.
```sh
atsutil 数据库 -removeUser &amp;&amp; \
atsutil 服务器 -shutdown &amp;&amp; \
atsutil server -ping
```

#### Get SF Mono Fonts
从 macOS 10.15 (Catalina) 开始，Utilities 应用程序（包括 Terminal.app）
现在可以在`/System` 文件夹中找到.
```sh
cp -v /Applications/Xcode-beta.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources/Fonts/SFMono-* ~/Library/Fonts
```

从 macOS 10.12 (Sierra) 开始，它们包含在 Terminal.app 中.
```sh
cp -v /Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-* ~/Library/Fonts
```

在较旧的操作系统版本中，您需要为此下载并安装 Xcode 8 beta
工作. 之后它们应该在所有应用程序中可用.
```sh
cp -v /System/Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-* ~/Library/Fonts
```

## Functions

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/functions.md).


## Hardware

### Bluetooth

Up to OS X 10.12 (Sierra) the Bluetooth daemon is named `blued` instead of
 `蓝牙`. 您需要相应地调整 `killall` 命令.

```sh
## Status
默认读取/Library/Preferences/com.apple.Bluetooth ControllerPowerState

## Enable (Default)
sudo 默认写入 /Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 1

## Disable
sudo 默认写入 /Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 0 &amp;&amp; \
须藤 killall -HUP 蓝牙
```

### Harddisks

#### Force Trim
为非 Apple SSD 启用修剪. 此命令自 OS X 10.10 (Yosemite) 起就存在.
```sh
trimforce
```

### Hardware Information

#### List All Hardware Ports
```sh
networksetup -listallhardwareports
```

#### Remaining Battery Percentage
```sh
 pmset -g batt |  egrep &quot;([0-9]+\%).*&quot; -o --colour=auto |  cut -f1 -d&#39;;&#39;
```

#### Remaining Battery Time
```sh
 pmset -g batt |  egrep &quot;([0-9]+\%).*&quot; -o --colour=auto | 剪切 -f3 -d&#39;;&#39;
```

#### Show Connected Device's UDID
```sh
 system_profiler SPUSBDataType |  sed -n -e &#39;/iPad/,/Serial/p&#39; -e &#39;/iPhone/,/Serial/p&#39;
```

#### Show Current Screen Resolution
```sh
 system_profiler SPDisplaysDataType | 解析度
```

#### Show CPU Brand String
```sh
sysctl -n machdep.cpu.brand_string
```

### Infrared Receiver

```sh
## Status
默认读取/Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled

## Enable (Default)
默认写入 /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 1

## Disable
默认写入 /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 0
```

### Power Management

#### Prevent System Sleep
防止睡眠1小时：
```sh
咖啡因 -u -t 3600
```

#### Show All Power Management Settings
```sh
须藤 pmset -g
```

#### Put Display to Sleep after 15 Minutes of Inactivity
```sh
须藤 pmset 显示睡眠 15
```

#### Put Computer to Sleep after 30 Minutes of Inactivity
```sh
须藤 pmset 睡眠 30
```

#### Check System Sleep Idle Time
```sh
须藤系统设置-getcomputersleep
```

#### Set System Sleep Idle Time to 60 Minutes
```sh
须藤系统设置-setcomputersleep 60
```

#### Turn Off System Sleep Completely
```sh
sudo systemsetup -setcomputersleep 从不
```

#### Automatic Restart on System Freeze
```sh
sudo systemsetup -setrestartfreeze on
```

#### Chime When Charging
连接 MagSafe 时播放 iOS 充电声音.
```sh
## Up to macOS 10.12 (Sierra)

## Enable
默认写入 com.apple.PowerChime ChimeOnAllHardware -bool true &amp;&amp; \
打开 /System/Library/CoreServices/PowerChime.app

## Disable (Default)
默认写入 com.apple.PowerChime ChimeOnAllHardware -bool false &amp;&amp; \
killall PowerChime
```
```sh
## From macOS 10.13 (High Sierra) on

## Enable (Default)
默认写入 com.apple.PowerChime ChimeOnNoHardware -bool false &amp;&amp; \
打开 /System/Library/CoreServices/PowerChime.app

## Disable
默认写入 com.apple.PowerChime ChimeOnNoHardware -bool true &amp;&amp; \
killall PowerChime
```


## Input Devices

### Keyboard

#### Auto-Correct
```sh
## Disable
默认写入 -g NSAutomaticSpellingCorrectionEnabled -bool false

## Enable (Default)
默认写入 -g NSAutomaticSpellingCorrectionEnabled -bool true

## Show Status
默认读取 -g NSAutomaticSpellingCorrectionEnabled
```

#### Full Keyboard Access
在模态对话框中启用 Tab.
```sh
## Text boxes and lists only (Default)
默认写 NSGlobalDomain AppleKeyboardUIMode -int 0

## All controls
默认写 NSGlobalDomain AppleKeyboardUIMode -int 3
```

#### Key Repeat
更改“按住”行为.
```sh
## Enable
默认写入 -g ApplePressAndHoldEnabled -bool false

## Disable (Default)
默认写入 -g ApplePressAndHoldEnabled -bool true
```

#### Key Repeat Rate
设置非常快的重复率，根据口味进行调整.
```sh
默认写入 -g KeyRepeat -int 0.02
```

## Launchpad

#### Reset Launchpad Layout
您需要重新启动“Dock”，因为 Launchpad 已绑定到它.
```sh
## Up to OS X 10.10 (Yosemite)
rm ~/Library/Application\ Support/Dock/*.db &amp;&amp; \
基尔码头

## From OS X 10.11 (El Capitan)
默认写入 com.apple.dock ResetLaunchPad -bool true &amp;&amp; \
基尔码头
```

## Media

### Audio

#### Convert Audio File to iPhone Ringtone
```sh
afconvert input.mp3 ringtone.m4r -f m4af
```

#### Create Audiobook From Text
使用“Alex”语音，一种用于输入和 AAC 输出的纯 UTF-8 编码文本文件.
```sh
说 -v Alex -f file.txt -o &quot;output.m4a&quot;
```

#### Disable Sound Effects on Boot
```sh
须藤 nvram SystemAudioVolume=&quot;&quot;
```

#### Mute Audio Output
```sh
osascript -e &#39;设置音量输出静音&#39;
```

#### Set Audio Volume
```sh
osascript -e &#39;设置第 4 卷&#39;
```

#### Play Audio File
您可以播放 QuickTime 本身支持的所有音频格式.
```sh
afplay -q 1 文件名.mp3
```

#### Speak Text with System Default Voice
```sh
说&#39;你所有的基地都属于我们！
```

#### Startup Chime
较旧的 Mac：
```sh
## Enable (Default)
须藤 nvram BootAudio =%01

## Disable
须藤 nvram BootAudio =%00
```

从 2016 款开始：
```sh
## Enable
须藤 nvram 启动静音=%00

## Disable (Default)
须藤 nvram 启动静音=%01
```

### Video

#### Auto-Play Videos in QuickTime Player
```sh
默认写入 com.apple.QuickTimePlayerX MGPlayMovieOnOpen 1
```


## Networking

### Bonjour

#### Bonjour Service
```sh
## Disable
sudo 默认写入 /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array-add &quot;-NoMulticastAdvertisements&quot;

## Enable (Default)
sudo 默认写入 /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array &quot;/usr/sbin/mDNSResponder&quot; &quot;-launchd&quot;
```

### DHCP

#### Renew DHCP Lease
```sh
须藤 ipconfig 设置 en0 DHCP
```

#### Show DHCP Info
```sh
ipconfig getpacket en0
```

### DNS

#### Clear DNS Cache
```sh
须藤 dscacheutil -flushcache &amp;&amp; \
须藤 killall -HUP mDNSResponder
```

### Hostname

#### Set Computer Name/Host Name
```sh
sudo scutil --set ComputerName &quot;newhostname&quot; &amp;&amp; \
sudo scutil --set HostName &quot;newhostname&quot; &amp;&amp; \
sudo scutil --set LocalHostName &quot;newhostname&quot; &amp;&amp; \
sudo 默认写入 /Library/Preferences/SystemConfiguration/com.apple.smb.server NetBIOSName -string &quot;newhostname&quot;
```

### Network Preferences

#### Network Locations
在“网络”首选项面板中创建的网络位置之间切换.
```sh
## Status
scselect

## Switch Network Location
scselect LocationNameFromStatus
```

#### Set Static IP Address
```sh
网络设置-setmanual“以太网”192.168.2.100 255.255.255.0 192.168.2.1
```

### Networking Tools

#### Ping a Host to See Whether It’s Available
```sh
ping -o github.com
```

#### Troubleshoot Routing Problems
```sh
跟踪路由 github.com
```

### SSH

#### Permanently Add Private Key Passphrase to SSH Agent
&gt; 在 macOS 10.12 (Sierra) 之前，ssh 会显示一个对话框，询问您
 &gt; 密码，并提供将其存储到钥匙串中的选项. 这个用户界面
&gt; 前段时间被弃用并已被删除.
>
&gt; 相反，macOS 10.12 (Sierra) 中引入了一个新的 UseKeychain 选项
&gt; 允许用户指定他们是否希望密码
 &gt; 存储在钥匙串中. 此选项在 macOS 10.12 上默认启用
&gt; (Sierra)，这导致所有密码都存储在钥匙串中.
>
&gt; 这不是预期的默认行为，因此在 macOS 中已更改
> 10.12.2.
> ([Source](https://developer.apple.com/library/archive/technotes/tn2449/_index.html))
```sh
ssh-add -K /path/to/private_key
```
然后添加到`~/.ssh/config`：
```sh
主机 server.example.com
    IdentityFile /path/to/private_key
    使用钥匙串 是
```

#### Remote Login
```sh
## Enable
sudo launchctl load -w /System/Library/LaunchDaemons/ssh.plist

## Disable (Default)
sudo launchctl unload -w /System/Library/LaunchDaemons/ssh.plist
```

### TCP/IP

#### Show Application Using a Certain Port
这将输出当前使用端口 80 的所有应用程序.
```sh
须藤 lsof -i :80
```

#### Show External IP Address
如果您的 ISP 不替换 DNS 请求（它不应该替换），则可以使用.
```sh
dig +short myip.opendns.com @resolver1.opendns.com
```
适用于所有网络的替代方案.
```sh
curl -s https://api.ipify.org &amp;&amp; echo
```

#### Show Network Interface Information
`scutil` 命令的未记录标志.
```sh
scutil --nwi
```

### TFTP

#### Start Native TFTP Daemon
文件将从`/private/tftpboot` 提供.
```sh
sudo launchctl load -F /System/Library/LaunchDaemons/tftp.plist &amp;&amp; \
sudo launchctl start com.apple.tftpd
```

### Wi-Fi

#### Join a Wi-Fi Network
```sh
networksetup -setairportnetwork en0 WIFI_SSID WIFI_PASSWORD
```

#### Scan Available Access Points
创建一个指向机场命令的符号链接以便于访问：
```sh
sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/local/bin/airport
```
运行无线扫描：
```sh
机场 -s
```

#### Show Current SSID
```sh
 /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -I |  awk &#39;/ SSID/ {print substr($0, index($0, $2))}&#39;
```

#### Show Local IP Address
```sh
ipconfig getifaddr en0
```

#### Show Wi-Fi Connection History
```sh
默认读取/Library/Preferences/SystemConfiguration/com.apple.airport.preferences |  grep LastConnected -A 7
```

#### Show Wi-Fi Network Passwords
将 SSID 与您要查询密码的接入点的 SSID 交换.
```sh
security find-generic-password -D &quot;AirPort 网络密码&quot; -a &quot;SSID&quot; -gw
```

#### Turn on Wi-Fi Adapter
```sh
networksetup -setairportpower en0 on
```

## Package Managers

- [Fink](http://www.finkproject.org) - Unix 开源的完整世界
  达尔文的软件. 有点过时了.
- [Homebrew](https://brew.sh) - OS X 缺少的包管理器.最
  热门选择.
- [MacPorts](https://www.macports.org) - 编译、安装和升级
  基于命令行、X11 或 Aqua 的开源软件.

### Homebrew

#### Full Uninstall

```sh
ruby -e &quot;$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)&quot;
```


## Printing

#### Clear Print Queue
```sh
取消 -a -
```

#### Expand Print Panel by Default
```sh
默认写 -g PMPrintingExpandedStateForPrint -bool true &amp;&amp; \
默认写 -g PMPrintingExpandedStateForPrint2 -bool true
```

#### Quit Printer App After Print Jobs Complete
```sh
默认写入 com.apple.print.PrintingPrefs“完成后退出”-bool true
```


## Security

### Application Firewall

#### Firewall Service
```sh
## Show Status
须藤/usr/libexec/ApplicationFirewall/socketfilterfw --getglobalstate

## Enable
须藤/usr/libexec/ApplicationFirewall/socketfilterfw --setglobalstate on

## Disable (Default)
须藤/usr/libexec/ApplicationFirewall/socketfilterfw --setglobalstate off
```

#### Add Application to Firewall
```sh
须藤/usr/libexec/ApplicationFirewall/socketfilterfw --add /path/to/file
```

### Gatekeeper

#### Add Gatekeeper Exception
```sh
spctl --add /path/to/Application.app
```

#### Remove Gatekeeper Exception
```sh
spctl --remove /path/to/Application.app
```

#### Manage Gatekeeper
对恼人的 macOS 10.15 (Catalina) 系统弹出窗口特别有用
阻止执行未签名的应用程序.
```sh
## Status
spctl --status

## Enable (Default)
须藤 spctl --master-enable

## Disable
须藤 spctl --master-disable
```

### Passwords

#### Generate Secure Password and Copy to Clipboard
```sh
 LC_ALL=C tr -dc &quot;[:alnum:]&quot; &lt; /dev/urandom | 头-c 20 | 复制
```

### Physical Access

#### Launch Screen Saver

```sh
## Up to macOS 10.12 (Sierra)
打开 /System/Library/Frameworks/ScreenSaver.framework/Versions/A/Resources/ScreenSaverEngine.app

## From macOS 10.13 (High Sierra)
/System/Library/CoreServices/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine
```


#### Lock Screen
```sh
/System/Library/CoreServices/Menu\ Extras/User.menu/Contents/Resources/CGSession -suspend
```

#### Screensaver Immediate Lock
```sh
## Status
默认读取 com.apple.screensaver askForPasswordDelay

## Enable (Default)
默认写 com.apple.screensaver askForPasswordDelay -int 0

## Disable (Integer = lock delay in seconds)
默认写 com.apple.screensaver askForPasswordDelay -int 10
```

#### Screensaver Password
```sh
## Status
默认读取 com.apple.screensaver askForPassword

## Enable
默认写 com.apple.screensaver askForPassword -int 1

## Disable (Default)
默认写 com.apple.screensaver askForPassword -int 0
```

### Privacy Database

`tccutil` 命令管理隐私数据库，该数据库存储决策
用户就应用程序是否可以访问个人数据做出了决定. 你需要关闭
在运行任何这些命令之前，除终端之外的所有应用程序.

```sh
## Full Reset for All Applications
须藤 tccutil 重置所有

## Reset Adress Book Access
sudo tccutil 重置地址簿

## Reset All Permission for Terminal.app
sudo tccutil reset All com.apple.Terminal
```

### Wiping Data

注意：MacOS 10.9 之后的`srm` 命令似乎已被删除. 那里
是一个注释 [Apple support page](https://support.apple.com/en-us/HT201949)
暗示为什么：
&gt; 对于 SSD 驱动器，安全擦除和擦除可用空间不可用
 &gt; 磁盘工具.  SSD 驱动器不需要这些选项，因为
&gt; 标准擦除使从 SSD 恢复数据变得困难.

#### Securely Remove File
```sh
srm /路径/到/文件
```

#### Securely Remove Folder
```sh
srm -r /path/to/folder/
```

#### Securely Remove Path (Force)
```sh
srm -rf /path/to/complete/destruction
```


## Search

### Find

#### Recursively Delete .DS_Store Files
```sh
寻找 .  -type f -name &#39;.DS_Store&#39; -ls -delete
```

### Locate

#### Build Locate Database
```sh
sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist
```

#### Search via Locate
`-i` 修饰符使搜索不区分大小写.
```sh
定位 -i *.jpg
```


## System

### AirDrop

#### AirDrop over Ethernet on Unsupported Macs
```sh
## Enable
默认写 com.apple.NetworkBrowser BrowseAllInterfaces -bool true &amp;&amp; \
默认删除 com.apple.NetworkBrowser DisableAirDrop

## Disable (Default)
默认删除 com.apple.NetworkBrowser BrowseAllInterfaces &amp;&amp; \
默认写入 com.apple.NetworkBrowser DisableAirDrop -bool 是
```

### AppleScript

#### Execute AppleScript
```sh
osascript /path/to/script.scpt
```

### Basics

#### Compare Two Folders
```sh
diff -qr /path/to/folder1 /path/to/folder2
```

#### Copy Large File with Progress
确保你已经安装了 `pv` 并将 `/dev/rdisk2` 替换为
适当的写入设备或文件.
```sh
 FILE=/path/to/file.iso pv -s $(du -h $FILE | awk &#39;/.*/ {print $1}&#39;) $FILE |  sudo dd of=/dev/rdisk2 bs=1m
```

#### Restore Sane Shell
In case your shell session went insane (some script or application turned it
变成乱码）.
```sh
头脑清醒
```

#### Restart
```sh
须藤重启
```

#### Shutdown
```sh
须藤关机
```

#### Show Build Number of OS
```sh
sw_vers
```

#### Uptime
距离上次重启多久了.
```sh
uptime
```

### Clipboard

#### Copy data to Clipboard
```sh
猫什么的.txt | 复制
```

#### Convert Clipboard to Plain Text
```sh
 pbpaste |  textutil -convert txt -stdin -stdout -encoding 30 | 复制
```

```sh
 pbpaste | 展开 | 复制
```

#### Copy data from Clipboard
```sh
pbpaste &gt; 随便.txt
```

```sh
 pbpaste | 排序 | 唯一| 复制
```

### FileVault

#### Automatically Unlock FileVault on Restart
如果在当前卷上启用了 FileVault，它会重新启动系统，
bypassing the initial unlock. The command may not work on all systems.
```sh
须藤 fdesetup authrestart
```

#### FileVault Service
```sh
## Status
须藤 fdesetup 状态

## Enable
须藤 fdesetup 启用

## Disable (Default)
须藤 fdesetup 禁用
```

### Information/Reports

#### Generate Advanced System and Performance Report
```sh
须藤 sysdiagnose -f ~/桌面/
```

### Installation

#### Create Bootable Installer
```sh
## macOS 11 (Big Sur)
sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --nointeraction --downloadassets

## macOS 10.15 (Catalina)
sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --nointeraction --downloadassets

## macOS 10.14 (Mojave)
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --nointeraction --downloadassets

## macOS 10.13 (High Sierra)
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ macOS\ High\ Sierra.app

## macOS 10.12 (Sierra)
sudo /Applications/Install\ macOS\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ macOS\ Sierra.app

## OS X 10.11 (El Capitan)
sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app

## OS X 10.10 (Yosemite)
sudo /Applications/Install\ OS\ X\ Yosemite.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ OS\ X\ Yosemite.app
```

* 为了在擦除驱动器之前进行确认，请从
  命令.
 * 可选的 `--downloadassets` 标志是 macOS 10.14 (Mojave) 中的新增功能. 它
  下载安装期间可能需要的资产，例如更新.
* 自 macOS 10.14 (Mojave) 和
  如果使用会抛出错误.

#### Download Older OS Versions

版本 | 代号 | 下载
------------- | ------------- | --------
 Mac OS X 10.0 | 猎豹 | 不适用
 Mac OS X 10.1 | 彪马 | 无/一个
 Mac OS X 10.2 | 捷豹 | 在
 Mac OS X 10.3 | 黑豹 | 不适用
 Mac OS X 10.4 | 老虎 | 不适用
 Mac OS X 10.5 | 豹| 不适用
 Mac OS X 10.6 | 雪豹 | 不适用
 Mac OS X 10.7 | 狮子 | [Direct Download](https://updates.cdn-apple.com/2021/macos/041-7683-20210614-E610947E-C7CE-46EB-8860-D26D71F0D3EA/InstallMacOSX.dmg)
 OS X 10.8 | 山狮 | [Direct Download](https://updates.cdn-apple.com/2021/macos/031-0627-20210614-90D11F33-1A65-42DD-BBEA-E1D9F43A6B3F/InstallMacOSX.dmg)
 OS X 10.9 | 小牛 | 无/一个
OS X 10.10 | 优胜美地 | [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-41343-20191023-02465f92-3ab5-4c92-bfe2-b725447a070d/InstallMacOSX.dmg)
 OS X 10.11 | 埃尔卡皮坦 | [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-41424-20191024-218af9ec-cf50-4516-9011-228c78eda3d2/InstallMacOSX.dmg)
 macOS 10.12 | 塞拉 | [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-39476-20191023-48f365f4-0015-4c41-9f44-39d3d2aca067/InstallOS.dmg)
 macOS 10.13 | 高山脉 | [App Store](https://apps.apple.com/de/app/macos-high-sierra/id1246284741)
 macOS 10.14 | 莫哈韦 | [App Store](https://apps.apple.com/de/app/macos-mojave/id1398502828)
 macOS 10.15 | 卡特琳娜 | [App Store](https://apps.apple.com/de/app/macos-catalina/id1466841314)
 macOS 11 | 大苏尔 | [App Store](https://apps.apple.com/de/app/macos-big-sur/id1526878132)

### Kernel Extensions

#### Display Status of Loaded Kernel Extensions
```sh
须藤 kextstat -l
```

#### Load Kernel Extension
```sh
须藤 kextload -b com.apple.driver.ExampleBundle
```

#### Unload Kernel Extensions
```sh
须藤 kextunload -b com.apple.driver.ExampleBundle
```

### LaunchAgents

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/launchagents.md).


### LaunchServices

#### Rebuild LaunchServices Database
为了独立于 OS X 版本，这依赖于 `locate` 来查找
 `lsregister`. 如果你还没有建立你的 `locate` 数据库，[做
it](#build-locate-database).
```sh
须藤 $(locate lsregister) -kill -seed -r
```

### Login Window

#### Set Login Window Text
```sh
sudo 默认写 /Library/Preferences/com.apple.loginwindow LoginwindowText “你的文字”
```

### Memory Management

#### Purge memory cache
```sh
须藤清除
```

#### Show Memory Statistics
```sh
## One time
vm_stat

## Table of data, repeat 10 times total, 1 second wait between each poll
vm_stat -c 10 1
```

### Notification Center

#### Notification Center Service
```sh
## Disable
launchctl unload -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist &amp;&amp; \
killall -9 通知中心

## Enable (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist
```

### QuickLook

#### Preview via QuickLook
```sh
qlmanage -p /path/to/file
```

### Remote Management

也可以看看： [Apple Remote Desktop](#apple-remote-desktop).

#### Prevent Double Password Entry
通过 Apple Remote Desktop 或 VNC 远程登录 Mac 时，您是
有时需要在连接后再次输入密码
苹果. 虽然您可以禁用此行为，但明确建议不要
关闭此功能，除非您确定没有其他人
能够在您离开时物理访问您的 Mac.
```sh
## Disable
sudo 默认写入 /Library/Preferences/com.apple.RemoteManagement.plist RestoreMachineState -bool no

## Enable (Default)
sudo 默认写入 /Library/Preferences/com.apple.RemoteManagement.plist RestoreMachineState -bool yes
```

#### Remote Apple Events
```sh
## Status
须藤系统设置-getremoteappleevents

## Enable
sudo systemsetup -setremoteappleevents on

## Disable (Default)
sudo systemsetup -setremoteappleevents 关闭
```

### Root User

```sh
## Enable
dsenableroot

## Disable (Default)
dsenableroot -d
```

### Safe Mode Boot

```sh
## Status
nvram 引导参数

## Enable
须藤 nvram 引导参数 =“-x”

## Disable (Default)
须藤 nvram 引导参数 =“”
```

### Save Dialogs

显着改善了保存对话框中现在相当慢的动画.

```sh
默认写 NSGlobalDomain NSWindowResizeTime .001
```

### Screenshots

#### Take Delayed Screenshot
3 秒后截取 JPEG 格式的屏幕截图并显示在预览中.
```sh
screencapture -T 3 -t jpg -P delaypic.jpg
```

#### Save Screenshots to Given Location
将位置设置为`~/Desktop`.
```sh
默认写入 com.apple.screencapture 位置 ~/Desktop &amp;&amp; \
killall SystemUIServer
```

#### Save Screenshots in Given Format
将格式设置为`png`. 其他选项是`bmp`、`gif`、`jpg`、`jpeg`、`pdf`、
`tiff`.
```sh
默认写入 com.apple.screencapture type -string &quot;png&quot;
```

#### Disable Shadow in Screenshots
```sh
默认写 com.apple.screencapture disable-shadow -bool true &amp;&amp; \
killall SystemUIServer
```

#### Set Default Screenshot Name
日期和时间保持不变.
```sh
默认写 com.apple.screencapture name &quot;Example name&quot; &amp;&amp; \
killall SystemUIServer
```

### Software Installation

#### Install PKG
```sh
安装程序 -pkg /path/to/installer.pkg -target /
```

### Sidecar

#### Use on Incompatible Macs
这可能有效，也可能无效，具体取决于机器的使用年限.
```sh
## Enable
默认写 com.apple.sidecar.display AllowAllDevices -bool true &amp;&amp; \
默认写 com.apple.sidecar.display hasShownPref -bool true

## Disable (Default)
默认删除 com.apple.sidecar.display
```

### Software Update

#### Ignore Specific Software Update
标识符可以通过`softwareupdate --list`找到. 在下面的例子中，
在 macOS 10.14 (Mojave) 上，将忽略所有更新到 macOS 10.15 的提示
(Catalina)，因为后者删除了 32 位支持.
```sh
sudo /usr/sbin/softwareupdate --ignore "macOS Catalina"
```

#### Install All Available Software Updates
```sh
须藤软件更新 -ia
```

#### Set Software Update Check Interval
设置为每天检查而不是每周检查.
```sh
默认写入 com.apple.SoftwareUpdate ScheduleFrequency -int 1
```

#### Show Available Software Updates
```sh
须藤软件更新 --list
```

#### Set Software Update Server
这应该仅用于测试目的或非托管客户端. 使用
网络范围内，或者正确设置 DNS 以及 [Apple SUS
service](http://krypted.com/mac-security/using-the-software-update-service-on-mountain-lion-server/)
并通过 OpenDirectory 绑定您的客户端. 或者，使用
[Reposado](https://github.com/wdas/reposado) 连同正确的网络DNS
设置使分辨率透明.
[Margarita](https://github.com/jessepeterson/margarita) 看起来不错
well.
```sh
## Use own SUS
sudo 默认写入 /Library/Preferences/com.apple.SoftwareUpdate CatalogURL http://su.example.com:8088/index.sucatalog

## Reset to Apple SUS
sudo 默认删除 /Library/Preferences/com.apple.SoftwareUpdate CatalogURL
```

### Software Version

#### Show System Software Version
有多种方法可以获得不同级别的细节.
```sh
sw_vers -productVersion
```
```sh
system_profiler SPSoftwareDataType
```
```sh
默认读取 loginwindow SystemVersionStampAsString
```

### Spotlight

#### Spotlight Indexing
```sh
## Disable
mdutil -i off -d /path/to/volume

## Enable (Default)
mdutil -i 在 /path/to/volume
```

#### Erase Spotlight Index and Rebuild
```sh
mdutil -E /path/to/volume
```

#### Search via Spotlight
```sh
mdfind -name &#39;searchterm&#39;
```

#### Show Spotlight Indexed Metadata
```sh
mdls /path/to/file
```

### System Integrity Protection

按住<kbd>Cmd</kbd> + <kbd>R</kbd>重新启动并打开终端
应用. 您将需要“重新启动”以使命令生效.

```sh
## Status
csrutil 状态

## Enable (Default)
csrutil 启用

## Disable
csrutil 禁用
```

### Date and Time

#### List Available Timezones
```sh
须藤系统设置-listtimezones
```

#### Set Timezone
```sh
sudo systemsetup -settimezone 欧洲/柏林
```

#### Set Clock Using Network Time
```sh
## Status
须藤系统设置获取使用网络时间

## Enable (Default)
sudo systemsetup setusingnetworktime on

## Disable
须藤系统设置设置使用网络时间关闭
```

#### Set Menu Bar Clock Output Format
```sh
## System Preferences > Date & Time > Time options
## Analogue
sudo 默认写 com.apple.menuextra.clock IsAnalog -bool true
## Digital (Default)
sudo 默认写 com.apple.menuextra.clock IsAnalog -bool false

## System Preferences > Date & Time > Flash the time separators
## Enable
sudo 默认写入 com.apple.menuextra.clock FlashDateSeparators -bool true
## Disable (Default)
sudo 默认写入 com.apple.menuextra.clock FlashDateSeparators -bool false

## Thu 18 Aug 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM HH:mm:ss&quot;

## Thu 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE HH:mm:ss&quot;

## 18 Aug 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;d MMM HH:mm:ss&quot;

## 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;HH:mm:ss&quot;

## Thu 18 Aug 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM h:mm:ss a&quot;


## Thu 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;EEE h:mm:ss a&quot;

## 18 Aug 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;d MMM h:mm:ss a&quot;

## 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;h:mm:ss a&quot;

## Thu 18 Aug 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM h:mm:ss&quot;

## Thu 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;EEE h:mm:ss&quot;

## 18 Aug 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;d MMM h:mm:ss&quot;

## 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;h:mm:ss&quot;

## Thu 18 Aug 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM HH:mm&quot;

## Thu 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE HH:mm&quot;

## 18 Aug 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;d MMM HH:mm&quot;

## 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;HH:mm&quot;

## Thu 18 Aug 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM h:mm a&quot;

## Thu 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;EEE h:mm a&quot;

## 18 Aug 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;d MMM h:mm a&quot;

## 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写 com.apple.menuextra.clock DateFormat -string &quot;h:mm a&quot;

## Thu 18 Aug 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE d MMM h:mm&quot;

## Thu 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;EEE h:mm&quot;

## 18 Aug 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;d MMM h:mm&quot;

## 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo 默认写入 com.apple.menuextra.clock DateFormat -string &quot;h:mm&quot;

## Apply changes immediately
须藤killall SystemUIServer
```

([Source](https://github.com/tech-otaku/macos-defaults/blob/master/date-time.sh))


## Terminal

#### Ring Terminal Bell
敲响终端铃（如果已启用）并在其上放置徽章.
```sh
输入贝尔
```

### Alternative Terminals

- [Alacritty](https://github.com/jwilm/alacritty) - 跨平台，
  GPU 加速的终端模拟器.
- [iTerm2](https://iterm2.com) - 更好的 Terminal.app.
- [kitty](https://sw.kovidgoyal.net/kitty/) - 现代的 GPU 加速终端
  模拟器.

### Shells

#### Bash
安装最新版本并设置为当前用户的默认 shell：
```sh
brew install bash &amp;&amp; \
 echo $(brew --prefix)/bin/bash | 须藤 tee -a /etc/shells &amp;&amp; \
chsh -s $(brew --prefix)/bin/bash
```

- [Homepage](https://www.gnu.org/software/bash/) - OS X 的默认外壳
  和大多数其他基于 Unix 的操作系统.
- [Bash-it](https://github.com/Bash-it/bash-it) - 社区 Bash 框架，
  就像 Oh My Zsh for Bash.

#### fish
安装最新版本并设置为当前用户的默认 shell：
```sh
酿造安装鱼&amp;&amp; \
 echo $(brew --prefix)/bin/fish | 须藤 tee -a /etc/shells &amp;&amp; \
chsh -s $(brew --prefix)/bin/fish
```

- [Homepage](http://fishshell.com) - 智能且用户友好的命令行
  用于 OS X、Linux 和其他家族的 shell.
- [The Fishshell Framework](https://github.com/oh-my-fish/oh-my-fish) -
  提供核心基础设施以允许您​​安装扩展或
  修改外壳的外观.
- [安装和配置
  教程](https://github.com/ellerbrock/fish-shell-setup-osx) - 如何设置
  OS 上带有 Fisherman、Powerline 字体、iTerm2 和 Budspencer 主题的 Fish Shell
  X.

#### Zsh
安装最新版本并设置为当前用户的默认 shell：
```sh
brew install zsh &amp;&amp; \
须藤 sh -c &#39;echo $(brew --prefix)/bin/zsh &gt;&gt; /etc/shells&#39; &amp;&amp; \
chsh -s $(brew --prefix)/bin/zsh
```

- [Homepage](http://www.zsh.org) - Zsh 是一个专为交互使用而设计的 shell，
  虽然它也是一种强大的脚本语言.
- [Oh My Zsh](http://ohmyz.sh) - 一个开源的、社区驱动的框架
  管理您的 Zsh 配置.
- [Prezto](https://github.com/sorin-ionescu/prezto) - 一个快速的 Zsh 框架.
  使用合理的默认值、别名、
  功能、自动完成和提示主题.
- [zgen](https://github.com/tarjoilija/zgen) - 另一个开源框架
  用于管理您的 zsh 配置.  Zgen 将加载 oh-my-zsh 兼容
  插件和主题，并具有更快和
  为您自动克隆配置中使用的任何插件.

### Terminal Fonts

- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) - 一种
  四种固定宽度字体系列，设计时考虑到了编码.
- [Codeface](https://github.com/chrissimpkins/codeface) - 画廊和
  供开发人员使用的等宽字体存储库.
- [DejaVu Sans Mono](https://dejavu-fonts.github.io/) - 基于的字体系列
  维拉字体.
- [Fantasque Sans Mono](https://github.com/belluzj/fantasque-sans) - 设计
  考虑到功能性，并带有一些摇摆不定的笔迹
  模糊，使它毫不起眼地很酷.
- [Hack](http://sourcefoundry.org/hack/) - 哈克是手工修饰和光学
  平衡成为您的首选代码面孔.
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) - 等宽
  字体，专为代码清单等设计.
- [Input](http://input.fontbureau.com) - 设计灵活的字体系统
  专门用于代码.
- [Meslo](https://github.com/andreberg/Meslo-Font) - 定制版
  Apple 的 Menlo 字体.
- [Operator Mono](https://www.typography.com/fonts/operator/overview/) - 一种
  令人惊讶的可用替代等宽字体（商业）.
- [Powerline Fonts](https://github.com/powerline/fonts) - 修补字体的回购
  对于电力线插件.
- [Source Code Pro](https://adobe-fonts.github.io/source-code-pro/) - 一种
  用于用户界面和编码环境的等宽字体系列.


## Glossary

### Mac OS X, OS X, and macOS Version Information

版本 | 代号 | 发布日期 | 最新版本
-------------------------- | ------------------ | ------------------ | -------------------------------------
 Rhapsody 开发者发布 |  Grail1Z4 / Titan1U |  1997 年 8 月 31 日 |  DR2（1998 年 5 月 14 日）
 Mac OS X 服务器 1.0 | 赫拉 |  1999 年 3 月 16 日 |  1.2v3（2000 年 10 月 27 日）
 Mac OS X 开发者预览版 | 不适用 |  1999 年 3 月 16 日 |  DP4（2000 年 4 月 5 日）
 Mac OS X 公测 | 科迪亚克 |  2000 年 9 月 13 日 | 不适用
 Mac OS X 10.0 | 猎豹 |  2001 年 3 月 24 日 |  10.0.4（2001 年 6 月 22 日）
 Mac OS X 10.1 | 彪马 |  2001 年 9 月 25 日 |  10.1.5（2002 年 6 月 6 日）
 Mac OS X 10.2 | 捷豹 |  2002 年 8 月 24 日 |  10.2.8（2003 年 10 月 3 日）
 Mac OS X 10.3 | 黑豹 |  2003 年 10 月 24 日 |  10.3.9（2005 年 4 月 15 日）
 Mac OS X 10.4 | 老虎 |  2005 年 4 月 29 日 |  10.4.11（2007 年 11 月 14 日）
 Mac OS X 10.5 | 豹|  2007 年 10 月 26 日 |  10.5.8（2009 年 8 月 5 日）
 Mac OS X 10.6 | 雪豹 |  2009 年 8 月 28 日 |  10.6.8 v1.1（2011 年 7 月 25 日）
 Mac OS X 10.7 | 狮子 |  2011 年 7 月 20 日 |  10.7.5（2012 年 9 月 19 日）
 OS X 10.8 | 山狮 |  2012 年 7 月 25 日 |  10.8.5 (12F2560)（2015 年 8 月 13 日）
 OS X 10.9 | 小牛 |  2013 年 10 月 22 日 |  10.9.5 (13F1911)（2016 年 7 月 18 日）
 OS X 10.10 | 优胜美地 |  2014 年 10 月 16 日 |  10.10.5 (14F2511)（2017 年 7 月 19 日）
 OS X 10.11 | 埃尔卡皮坦 |  2015 年 9 月 30 日 |  10.11.6 (15G22010)（2018 年 7 月 9 日）
 macOS 10.12 | 塞拉 |  2016 年 9 月 20 日 |  10.12.6 (16G2136)（2019 年 9 月 26 日）
 macOS 10.13 | 高山脉 |  2017 年 9 月 25 日 |  10.13.6 (17G14042)（2020 年 11 月 12 日）
 macOS 10.14 | 莫哈韦 |  2018 年 9 月 24 日 |  10.14.6 (18G9216)（2021 年 5 月 24 日）
 macOS 10.15 | 卡特琳娜 |  2019 年 10 月 7 日 |  10.15.7 (19H1217)（2021 年 5 月 24 日）
 macOS 11 | 大苏尔 |  2020 年 11 月 12 日 |  11.5.1 (20G80)（2021 年 7 月 26 日）


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /><br />本作品采用<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议进行许可</a>.
