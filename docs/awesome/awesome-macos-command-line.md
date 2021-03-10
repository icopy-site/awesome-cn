<div class="github-widget" data-repo="herrbischoff/awesome-macos-command-line"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<h1><img src="https://cdn.rawgit.com/herrbischoff/awesome-macos-command-line/cab824f0/assets/logo.svg" alt="Awesome macOS Command Line" width="600"></h1>

&gt;专门针对OS X的Shell命令和工具的精选列表.
>
 &gt; _“您不必一无所知. 您只需要知道在哪里找到它
 &gt;必要时.”  （约翰·布鲁纳）_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

如果您想做出贡献，强烈建议您这样做. 请阅读
[contribution guidelines](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/contributing.md).

有关终端外壳的更多信息，请参见此列表的姐妹列表.
[很棒的命令行
Apps](https://github.com/herrbischoff/awesome-command-line-apps).


## Women Empowerment in Zanzibar

顺便发送一些因果报应，并通过以下方式支持桑给巴尔妇女的赋权
帮助[资助可重复使用的女性卫生的本地生产
产品]（https://www.gofundme.com/f/women-empowerment-in-zanzibar）. 一个非常
我亲爱的朋友运行该项目. 他们已经可以购买数百个
教育书籍. 有时，只需很少的时间就能产生巨大的影响. 如果
您要感谢我或支持这项工作，请捐赠. 此外，任何当前
将来通过GitHub或其他渠道赞助我的作品将会
非政府组织的百分之一百.


## Foreword

我在这里实际上只想指出一件事：[man
页]（https://en.wikipedia.org/wiki/Man_page）.  [男人
页]（https://www.cs.mcgill.ca/~guide/help/man.html）.  [男人
页]（https://xkcd.com/1692/）. 好的，三件事. 但是这一件事似乎
非常重要，我不得不多次提及. 如果你不这样做
已经，在搜索之前，您应该养成查阅手册页的习惯
其他任何地方.  Unix风格的手册页是很好的文档来源.
甚至还有一个用于`man`命令本身的手册页：

```sh
男人男人
```

它还说明了手册页中的数字所指的是---类似于`man（1）`.





## Appearance

### Subpixel Anti-Aliasing (Font Smoothing)

自macOS 10.14（Mojave）起存在该设置.

```sh
## Enable
默认写-g CGFontRenderingFontSmoothingDisabled -bool false

## Disable (Default)
默认写-g CGFontRenderingFontSmoothingDisabled -bool true

## Per Application
默认写入com.apple.textedit CGFontRenderingFontSmoothingDisabled -bool false

## Revert for Application
defaults delete com.apple.textedit CGFontRenderingFontSmoothingDisabled
```

### Transparency

#### Transparency in Menu and Windows
```sh
## Reduce Transparency
默认写com.apple.universalaccess reduceTransparency -bool true

## Restore Default Transparency
默认写com.apple.universalaccess reduceTransparency -bool false
```


### Wallpaper

#### Set Wallpaper
```sh
## Up to OS X 10.8 (Mountain Lion)
osascript -e&#39;告诉应用程序“ Finder”将桌面图片设置为POSIX文件“ /path/to/picture.jpg”

## Since OS X 10.9 (Mavericks)
sqlite3〜/ Library / Application \ Support / Dock / desktoppicture.db“更新数据集值=&#39;/path/to/picture.jpg&#39;” &amp;&amp; killall Dock
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
适用于OS X 10.10（Yosemite）.
```sh
## Enable
默认写com.apple.appstore ShowDebugMenu -bool true

## Disable (Default)
默认写com.apple.appstore ShowDebugMenu -bool false
```


### Apple Remote Desktop

#### Kickstart Manual Pages
```sh
须藤/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -help
```

#### Activate And Deactivate the ARD Agent and Helper
```sh
## Activate And Restart the ARD Agent and Helper
sudo /系统/库/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -activate -restart -agent -console

## Deactivate and Stop the Remote Management Service
须藤/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart-停用-停止
```

#### Remote Desktop Sharing
```sh
## Allow Access for All Users and Give All Users Full Access
须藤/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -configure -allowAccessFor -allUsers -privs -all

## Disable ARD Agent and Remove Access Privileges for All Users (Default)
须藤/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -configure -access -off
```

#### Remove Apple Remote Desktop Settings
```sh
须藤rm -rf / var / db / RemoteManagement;  \
 sudo默认删除/Library/Preferences/com.apple.RemoteDesktop.plist;  \
默认为delete〜/ Library / Preferences / com.apple.RemoteDesktop.plist;  \
 sudo rm -r / Library / Application \ Support / Apple / Remote \ Desktop /;  \
 rm -r〜/ Library / Application \ Support / Remote \ Desktop /;  \
rm -r〜/ Library / Containers / com.apple.RemoteDesktop
```

### Contacts

#### Debug Mode
```sh
## Enable
默认写com.apple.addressbook ABShowDebugMenu -bool true

## Disable (Default)
默认写com.apple.addressbook ABShowDebugMenu -bool false
```

### Google

#### Uninstall Google Update
```sh
〜/ Library / Google / GoogleSoftwareUpdate / GoogleSoftwareUpdate.bundle / Contents / Resources / ksinstall --nuke
```

### iTunes

#### Keyboard Media Keys
适用于OS X 10.10（Yosemite）. 引入了系统完整性保护
在OS X 10.11（El Capitan）中，它阻止了系统启动代理
unloaded.
```sh
## Stop Responding to Key Presses
launchctl卸载-w /System/Library/LaunchAgents/com.apple.rcd.plist

## Respond to Key Presses (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

从OS X 10.11（El Capitan）开始，您可以禁用SIP或采用某种方式
黑客攻击，这将使任何用户都无法有效访问iTunes
阻止它启动自己或它的助手. 要知道，对于所有人
意图和目的将破坏您的iTunes安装，并可能发生冲突
随着操作系统的更新.
```sh
sudo chmod 0000 /应用程序/iTunes.app
```

### Mail

#### Show Attachments as Icons

```sh
默认写com.apple.mail DisableInlineAttachmentViewing -bool是
```

#### Vacuum Mail Index
下面的AppleScript代码将退出Mail，清理SQLite索引，然后
重新打开邮件. 在尚未经过优化的大型电子邮件数据库上，
这可以大大提高响应速度和速度.
```applescript
(*
通过清除信封索引来加速Mail.app
代码来自：http://web.archive.org/web/20071008123746/http://www.hawkwings.net/2007/03/03/scripts-to-automate-the-mailapp-envelope-speed-trick/
最初由“ pmbuko”修改，由Romulo修改
布雷特·特普斯特拉（Brett Terpstra）2012年更新
由MathiasTörnblom2015更新，以支持El Capitan中的V3，并且仍保持向后兼容性
由Andrei Miclaus 2017更新，以支持Sierra中的V4
*)

告诉应用程序“邮件”退出
设置os_version以执行shell脚本“ sw_vers -productVersion”
将mail_version设置为“ V2”
考虑数字字符串
    如果“ 10.10” &lt;= os_version，则将mail_version设置为“ V3”
    如果“ 10.12” &lt;= os_version，则将mail_version设置为“ V4”
    如果“ 10.13” &lt;= os_version，则将mail_version设置为“ V5”
    如果“ 10.14” &lt;= os_version，则将mail_version设置为“ V6”
    如果“ 10.15” &lt;= os_version，则将mail_version设置为“ V7”
    如果“ 11” &lt;= os_version，则将mail_version设置为“ V8”
结束考虑

设置sizeBefore做外壳程序脚本“ ls -lnah〜/ Library / Mail /”和mail_version＆“ / MailData | grep -E&#39;信封索引$&#39;| awk {&#39;print $ 5&#39;}”
做shell脚本“ / usr / bin / sqlite3〜/ Library / Mail /”和mail_version和“ / MailData / Envelope \\ Index vacuum”

设置sizeAfter做shell脚本“ ls -lnah〜/ Library / Mail /”和mail_version＆“ / MailData | grep -E&#39;信封索引$&#39;| awk {&#39;print $ 5&#39;}”

显示对话框（“之前的邮件索引：”＆sizeBefore＆return＆“之后的邮件索引：”＆sizeAfter＆return＆return＆“享受新的速度！”）

告诉应用程序“邮件”激活
```

### Safari

#### Change Default Fonts
```sh
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily格鲁吉亚
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFontSize 16
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily Menlo
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFixedFontSize 14
```

#### Develop Menu and Web Inspector
```sh
## Enable
默认写com.apple.Safari IncludeInternalDebugMenu -bool true &amp;&amp; \
默认写com.apple.Safari IncludeDevelopMenu -bool true &amp;&amp; \
默认写com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey -bool true &amp;&amp; \
默认写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled -bool true &amp;&amp; \
默认为write -g WebKitDeveloperExtras -bool true

## Disable (Default)
默认删除com.apple.Safari IncludeInternalDebugMenu &amp;&amp; \
默认情况下，删除com.apple.Safari IncludeDevelopMenu &amp;&amp; \
默认情况下删除com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey &amp;&amp; \
默认情况下删除com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled &amp;&amp; \
默认为delete -g WebKitDeveloperExtras
```

#### Get Current Page Data
其他选项：“获取来源”，“获取文字”.
```sh
osascript -e&#39;告诉应用程序“ Safari”以获取前窗当前选项卡的URL”
```

#### Use Backspace/Delete to Go Back a Page
```sh
## Enable
默认写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool是

## Disable (Default)
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool否
```

### Sketch

#### Export Compact SVGs
```sh
默认写com.bohemiancoding.sketch3 exportCompactSVG -bool是
```

### Skim

#### Turn Off Auto Reload Dialog
删除对话框，默认为自动重新加载.
```sh
默认为write -app Skim SKAutoReloadFileUpdate -boolean true
```
### Terminal

#### Focus Follows Mouse
```sh
## Enable
默认写com.apple.Terminal FocusFollowsMo​​use -string是

## Disable (Default)
默认写com.apple.Terminal FocusFollowsMo​​use -string NO
```

### TextEdit

#### Use Plain Text Mode as Default
```sh
默认写com.apple.TextEdit RichText -int 0
```

### Visual Studio Code

#### VSCodeVim Key Repeat
```sh
## Enable
默认写入com.microsoft.VSCode ApplePressAndHoldEnabled -bool false

## Disable (Default)
默认删除com.microsoft.VSCode ApplePressAndHoldEnabled
```

#### Subpixel Anti-Aliasing
自macOS 10.14（Mojave）起存在该设置. 另请参阅系统范围的设置：
```sh
## Enable
默认写com.microsoft.VSCode CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写com.microsoft.VSCode.helper CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写com.microsoft.VSCode.helper.EH CGFontRenderingFontSmoothingDisabled -bool false &amp;&amp; \
默认写入com.microsoft.VSCode.helper.NP CGFontRenderingFontSmoothingDisabled -bool false

## Disable (Default)
默认删除com.microsoft.VSCode CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除com.microsoft.VSCode.helper CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除com.microsoft.VSCode.helper.EH CGFontRenderingFontSmoothingDisabled &amp;&amp; \
默认删除com.microsoft.VSCode.helper.NP CGFontRenderingFontSmoothingDisabled
```


## Backup

### Time Machine

#### Change Backup Interval
这会将间隔更改为30分钟. 整数值是时间
seconds.
```sh
sudo默认写入/System/Library/LaunchDaemons/com.apple.backupd-auto StartInterval -int 1800
```

#### Local Backups
Time Machine备份时Time Machine是否执行本地备份
音量不可用.
```sh
## Status
默认阅读/Library/Preferences/com.apple.TimeMachine MobileBackups

## Enable (Default)
须藤tmutil enablelocal

## Disable
须藤tmutil disablelocal
```

从macOS 10.13（High Sierra）开始，您不能禁用本地快照. 时间
现在，计算机始终创建本地APFS快照，并将该快照用作
数据源来创建常规备份，而不是使用活动磁盘
源，与HFS格式化的磁盘一样.

#### Prevent Time Machine from Prompting to Use New Hard Drives as Backup Volume
```sh
sudo默认写入/Library/Preferences/com.apple.TimeMachine DoNotOfferNewDisksForBackup -bool true
```

#### Show Time Machine Logs
这个小脚本将输出Time Machine活动的最后12小时
其次是现场活动.
```sh
#!/bin/sh

filter =&#39;processImagePath包含“ backupd”，并且子系统以“ com.apple.TimeMachine”开头

## show the last 12 hours
start =“ $（date -j -v-12H +&#39;％Y-％m-％d％H：％M：％S&#39;）”

回声“”
回声“ [历史（从$开始）]”
回声“”

日志显示--style syslog --info --start“ $ start”-谓词“ $ filter”

回声“”
回声“ [以下]”
回声“”

日志流--style syslog --info --predicate“ $ filter”
```

#### Toggle Backup While on Battery
```sh
## Status
sudo默认阅读/Library/Preferences/com.apple.TimeMachine需要ACPower

## Enable (Default)
sudo默认写入/Library/Preferences/com.apple.TimeMachine RequiresACPower -bool true

## Disable
sudo默认写入/Library/Preferences/com.apple.TimeMachine要求ACPower -bool false
```

#### Verify Backup
从OS X 10.11开始，Time Machine记录复制到其中的文件的校验和.
快照. 对于复制的文件，不会追溯计算校验和
由OS X的早期版本提供.
```sh
须藤tmutil verifychecksums / path / to / backup
```

## Developer

### Vim

#### Compile Sane Vim
通过Homebrew编译MacVim，并编写所有代码，包括覆盖
系统Vim.
```sh
brew install macvim --HEAD
```

#### Neovim
通过Homebrew安装现代的Vim替代方案.
```sh
brew install neovim
```

### Xcode

#### Install Command Line Tools without Xcode
```sh
xcode-select-安装
```

#### Remove All Unavailable Simulators
```sh
xcrun simctl删除不可用
```


## Dock

#### Add a Stack with Recent Applications
自macOS 10.14（Mojave）起已作废. 看 [Show Recent Apps](#show-recent-apps).
```sh
默认写com.apple.dock持久其他-array-add&#39;{“ tile-data” = {“” list-type“ = 1;  };  “ tile-type” =“最近的瓷砖”；  }&#39;&amp;&amp; \
杀人码头
```

#### Add a Nameless Stack Folder and Small Spacer
```sh
默认写com.apple.dock持久其他-array-add&#39;{“ tile-data” = {};  “ tile-type” =“小间隔片-tile”;  }&#39;&amp;&amp; \
杀人码头
```

#### Add a Space
```sh
默认写com.apple.dock持久应用程序-array-add&#39;{“ tile-type” =“ spacer-tile”;}&#39;&amp;&amp; \
杀人码头
```

#### Add a Small Space
```sh
默认写com.apple.dock持久应用程序-array-add&#39;{“ tile-type” =“ small-spacer-tile”;}&#39;&amp;&amp; \
杀人码头
```

#### Auto Rearrange Spaces Based on Most Recent Use
```sh
## Enable (Default)
defaults write com.apple.dock mru-spaces -bool true && \
杀人码头

## Disable
默认写com.apple.dock mru-spaces -bool false &amp;&amp; \
杀人码头
```

#### Automatically Hide
```sh
## Enable
默认写com.apple.dock autohide -bool true &amp;&amp; \
杀人码头

## Disable (Default)
默认写com.apple.dock autohide -bool false &amp;&amp; \
杀人码头
```

#### Icon Bounce
全局设置当相应应用程序时Dock图标是否应该弹跳
需要您的关注.
```sh
## Enable (Default)
默认写com.apple.dock不反弹-bool true &amp;&amp; \
杀人码头

## Disable
默认写com.apple.dock不反弹-bool false &amp;&amp; \
杀人码头
```

#### Lock the Dock Size
```sh
## Enable
默认写com.apple.Dock大小不可变-bool是&amp;&amp; \
杀人码头

## Disable (Default)
默认写入com.apple.Dock大小不可变-bool否&amp;&amp; \
杀人码头
```

#### Reset Dock
```sh
默认删除com.apple.dock &amp;&amp; \
杀人码头
```

#### Resize
完全调整您的Dock身体的大小. 要调整大小，请将“ 0”值更改为整数.
```sh
默认写com.apple.dock tileize -int 0 &amp;&amp; \
杀人码头
```

#### Scroll Gestures
使用触摸板或鼠标滚轮与Dock项进行交互. 允许你
使用向上滚动手势打开堆栈. 使用相同的手势
正在运行的应用程序将调用Exposé/ Mission Control.
```sh
## Enable
默认写com.apple.dock滚动到打开-bool true &amp;&amp; \
杀人码头

## Disable (Default)
默认写com.apple.dock滚动到打开-bool false &amp;&amp; \
杀人码头
```

#### Set Auto Show/Hide Delay
浮点数定义了显示/隐藏延迟（以毫秒为单位）.
```sh
默认写com.apple.dock autohide-time-modifier -float 0.4 &amp;&amp; \
默认写com.apple.dock autohide-delay -float 0 &amp;&amp; \
杀人码头
```

#### Show Hidden App Icons
```sh
## Enable
默认写com.apple.dock showhidden -bool true &amp;&amp; \
杀人码头

## Disable (Default)
默认写com.apple.dock showhidden -bool false &amp;&amp; \
杀人码头
```

#### Show Only Active Applications
```sh
## Enable
默认写com.apple.dock仅静态-bool true &amp;&amp; \
杀人码头

## Disable (Default)
默认写com.apple.dock仅静态-bool false &amp;&amp; \
杀人码头
```

#### Show Recent Apps
自macOS 10.14（Mojave）起存在该设置.
```sh
## Disable
默认写com.apple.dock show-recents -bool false &amp;&amp; \
杀人码头

## Enable (Default)
默认写com.apple.dock show-recents -bool true &amp;&amp; \
杀人码头
```

#### Single App Mode
单击Dock中的应用程序图标时，将出现相应的窗口
到最前面，但是所有其他应用程序窗口将被隐藏.
```sh
## Enable
默认写com.apple.dock单应用程序-bool true &amp;&amp; \
杀人码头

## Disable (Default)
默认写com.apple.dock单应用程序-bool false &amp;&amp; \
杀人码头
```


## Documents

#### Convert File to HTML
支持的格式为纯文本，富文本（rtf）和Microsoft Word（doc / docx）.
```sh
textutil-转换html file.ext
```


## Files, Disks and Volumes

#### Create an Empty File
创建一个空的10 GB测试文件.
```sh
mkfile 10g / path / to / file
```

#### Disable Sudden Motion Sensor
使用SSD时，将其保持打开状态是没有用的.
```sh
须藤pmset -a sms 0
```

#### Eject All Mountable Volumes
唯一可靠的方法是将AppleScript命令发送到
Finder.
```sh
osascript -e&#39;告诉应用程序“ Finder”弹出（每个可弹出的磁盘为true的磁盘）”
```

#### Repair File Permissions
您不必为此使用“磁盘工具” GUI.
```sh
sudo diskutil repairPermissions /
```
&gt;从OS X 10.11（El Capitan）开始，系统文件权限为
 &gt;自动保护. 不再需要验证或维修
&gt;具有“磁盘工具”的权限.
> ([Source](https://support.apple.com/en-us/HT201560))

#### Set Boot Volume
```sh
## Up to OS X 10.10 (Yosemite)
保佑--mount“ / path / to / mount / volume” --setBoot

## From OS X 10.11 (El Capitan)
sudo systemsetup -setstartupdisk /系统/库/ CoreServices
```

#### Show All Attached Disks and Partitions
```sh
磁盘清单
```

#### View File System Usage
文件系统访问信息的连续流.
```sh
须藤fs_usage
```
### APFS

自macOS 10.13（High Sierra）起出现. 没有中央实用程序和用法
由于大多数功能都已整合到`tmutil`中，因此不一致.

#### Convert Volume from HFS+ to APFS
```sh
/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert / path / to / file / system
```

#### Create New APFS Filesystem
```sh
/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs / path / to / device
```

#### Create Snapshot
```sh
tmutil localsnapshot
```

#### Delete Snapshot
```sh
tmutil deletelocalsnapshots com.apple.TimeMachine.2018-01-26-044042
````

#### List Snapshots
```sh
tmutil listlocals快照/
```

#### Mount Snapshot
快照是只读的.
```sh
mkdir〜/ mnt
/System/Library/Filesystems/apfs.fs/Contents/Resources/mount_apfs -s com.apple.TimeMachine.2018-01-26-044042 /〜/ mnt
```

### Disk Images

```sh
hdiutil create -volname“卷名” -srcfolder / path / to / folder -ov diskimage.dmg
```

如果您想加密磁盘映像：
```sh
hdiutil create -encryption -stdinpass -volname“卷名” -srcfolder / path / to / folder -ov crypto.dmg
```

默认情况下，系统会提示您输入密码. 您可以通过管道自动执行
输入密码：
```sh
 echo -n YourPassword |  hdiutil create -encryption -stdinpass -volname“卷名” -srcfolder / path / to / folder -ov crypto.dmg
```

#### Burn Disk Images to DVD
此命令适用于.iso，.img和.dmg图像.
```sh
hdiutil刻录/ path / to / image_file
```

#### Create Temporary High-Performance Disk
磁盘由物理RAM支持，并且速度比磁盘高出数倍.
固态硬盘. 弹出磁盘后，无法恢复磁盘的内容.
下面的示例是针对500 MiB RAM磁盘的，请根据需要进行调整.
```sh
## Up to macOS 10.14 (Mojave)
让DISKSIZE = 500 * 2048 &amp;&amp; \
diskutil擦除卷HFS +“ RAM磁盘”`hdiutil attach -nomount ram：// $ DISKSIZE`

## From macOS 10.15 (Catalina) on
让“ DISKSIZE = 500 * 2048” &amp;&amp; \
diskutil擦除卷HFS +“ RAM磁盘”`hdiutil attach -nomount ram：// $ DISKSIZE`
```

#### Disable Disk Image Verification
```sh
默认写com.apple.frameworks.diskimages skip-verify -bool true &amp;&amp; \
默认写com.apple.frameworks.diskimages skip-verify-locked -bool true &amp;&amp; \
默认写com.apple.frameworks.diskimages skip-verify-remote -bool true
```

#### Make Volume OS X Bootable
```sh
bless --folder“ /路径/到/已挂载/卷/系统/库/ CoreServices” --bootinfo --bootefi
```

#### Mount Disk Image
```sh
hdiutil附加/path/to/diskimage.dmg
```

#### Unmount Disk Image
```sh
hdiutil分离/ dev / disk2s1
```

#### Write Disk Image to Volume
就像磁盘工具的“还原”功能.
```sh
Sudo ASR-还原-noverify-源/path/to/diskimage.dmg-目标/卷/ VolumeToRestoreTo
```


## Finder

### Desktop

#### Show External Media
外部HD，拇指驱动器等
```sh
## Enable
默认值写com.apple.finder ShowExternalHardDrivesOnDesktop -bool true &amp;&amp; \
Killall搜寻器

## Disable (Default)
默认写com.apple.finder ShowExternalHardDrivesOnDesktop -bool false &amp;&amp; \
Killall搜寻器
```

#### Show Internal Media
内置HD或SSD.
```sh
## Enable
默认值写com.apple.finder ShowHardDrivesOnDesktop -bool true &amp;&amp; \
Killall搜寻器

## Disable (Default)
默认写com.apple.finder ShowHardDrivesOnDesktop -bool false &amp;&amp; \
Killall搜寻器
```

#### Show Removable Media
CD，DVD，iPod等
```sh
## Enable
默认值写com.apple.finder ShowRemovableMediaOnDesktop -bool true &amp;&amp; \
Killall搜寻器

## Disable (Default)
默认写com.apple.finder ShowRemovableMediaOnDesktop -bool false &amp;&amp; \
Killall搜寻器
```

#### Show Network Volumes
AFP，SMB，NFS，WebDAV等
```sh
## Enable
默认值写com.apple.finder ShowMountedServersOnDesktop -bool true &amp;&amp; \
Killall搜寻器

## Disable (Default)
默认写com.apple.finder ShowMountedServersOnDesktop -bool false &amp;&amp; \
Killall搜寻器
```

### Files and Folders

#### Clear All ACLs
```sh
须藤chmod -RN / path / to / folder
```

#### Increase Number of Recent Places
```sh
默认写-g NSNavRecentPlacesLimit -int 10 &amp;&amp; \
Killall搜寻器
```

#### Show All File Extensions
```sh
默认写-g AppleShowAllExtensions -bool true
```

#### Set Protected Flag
这等效于Finder的“锁定”状态.
```sh
## Disable (Default)
sudo chflags -R nouchg /路径/到/文件/或/文件夹

## Enable
sudo chflags -R uchg / path / to / file / or / folder
```

#### Show Hidden Files
```sh
## Show All
默认写入com.apple.finder AppleShowAllFiles true

## Restore Default File Visibility
默认写com.apple.finder AppleShowAllFiles false
```

#### Show Full Path in Finder Title
```sh
默认写com.apple.finder _FXShowPosixPathInTitle -bool true
```

#### Toggle Folder Visibility in Finder
默认情况下，~~ Library文件夹是隐藏的. 您可以轻松地再次显示它. 这
同样的方法适用于所有其他文件夹.
```sh
## Hidden (Default)
chflags隐藏〜/ Library

## Visible
chflags nohidden〜/库
```

### Layout

#### Show "Quit Finder" Menu Item
可以使用默认快捷方式查看Finder菜单项“ Quit Finder”
<kbd>Cmd</kbd> + <kbd>Q</kbd>
```sh
## Enable
默认写com.apple.finder QuitMenuItem -bool true &amp;&amp; \
Killall搜寻器

## Disable (Default)
默认写com.apple.finder QuitMenuItem -bool false &amp;&amp; \
Killall搜寻器
```

#### Smooth Scrolling
如果您使用的旧Mac会使动画混乱，则很有用.
```sh
## Disable
默认为write -g NSScrollAnimationEnabled -bool false

## Enable (Default)
默认为write -g NSScrollAnimationEnabled -bool true
```

#### Rubberband Scrolling
```sh
## Disable
默认为write -g NSScrollViewRubberbanding -bool false

## Enable (Default)
默认为write -g NSScrollViewRubberbanding -bool true
```

#### Expand Save Panel by Default
```sh
默认写-g NSNavPanelExpandedStateForSaveMode -bool true &amp;&amp; \
默认写-g NSNavPanelExpandedStateForSaveMode2 -bool true
```

#### Desktop Icon Visibility
```sh
## Hide Icons
默认写com.apple.finder CreateDesktop -bool false &amp;&amp; \
Killall搜寻器

## Show Icons (Default)
默认写com.apple.finder CreateDesktop -bool true &amp;&amp; \
Killall搜寻器
```

#### Path Bar
```sh
## Show
默认写com.apple.finder ShowPathbar -bool true

## Hide (Default)
默认写com.apple.finder ShowPathbar -bool false
```

#### Scrollbar Visibility
可能的值：“ WhenScrolling”，“ Automatic”和“ Always”.
```sh
默认写-g AppleShowScrollBars -string“始终”
```

#### Status Bar
```sh
## Show
默认写com.apple.finder ShowStatusBar -bool true

## Hide (Default)
默认写com.apple.finder ShowStatusBar -bool false
```

#### Save to Disk by Default
将默认保存目标设置为本地磁盘，而不是iCloud.
```sh
默认写-g NSDocumentSaveNewDocumentsToCloud -bool false
```

#### Set Current Folder as Default Search Scope
```sh
默认写com.apple.finder FXDefaultSearchScope -string“ SCcf”
```

#### Set Default Finder Location to Home Folder
```sh
默认写com.apple.finder NewWindowTarget -string“ PfLo” &amp;&amp; \
默认写com.apple.finder NewWindowTargetPath -string“ file：// $ {HOME}”
```

#### Set Sidebar Icon Size
将尺寸设置为“中”.
```sh
默认写入-g NSTableViewDefaultSizeMode -int 2
```

### Metadata Files

#### Disable Creation of Metadata Files on Network Volumes
避免创建.DS_Store和AppleDouble文件.
```sh
默认写com.apple.desktopservices DSntWriteNetworkStores -bool true
```

#### Disable Creation of Metadata Files on USB Volumes
避免创建.DS_Store和AppleDouble文件.
```sh
默认写入com.apple.desktopservices DSntWriteUSBStores -bool true
```

### Opening Things

#### Change Working Directory to Finder Path
如果打开了多个窗口，它将选择最上面的一个.
```sh
cd“ $（osascript -e&#39;告诉应用程序“ Finder”到（插入位置作为别名）的POSIX路径&#39;）”
```

#### Open URL
```sh
打开https://github.com
```

#### Open File
```sh
打开README.md
```

#### Open Applications
您可以使用`-a`打开应用程序.
```sh
打开-a“ Google Chrome” https://github.com
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
要清除所有用户的字体缓存，请将“ sudo”放在这些命令前面.
```sh
atsutil数据库-removeUser &amp;&amp; \
atsutil服务器-shutdown &amp;&amp; \
atsutil server -ping
```

#### Get SF Mono Fonts
从macOS 10.15（Catalina）开始，实用程序应用程序（包括Terminal.app）
现在可以在`/ System`文件夹中找到.
```sh
cp -v /Applications/Xcode-beta.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources/Fonts/SFMono-*〜/ Library / Fonts
```

从macOS 10.12（Sierra）开始，它们包含在Terminal.app中.
```sh
cp -v /应用程序/实用程序/Terminal.app/内容/资源/字体/ SFMono- *〜/库/字体
```

在较旧的OS版本中，您需要下载并安装Xcode 8 Beta，以便
工作. 之后，它们应在所有应用程序中可用.
```sh
cp -v /系统/应用程序/实用程序/Terminal.app/内容/资源/字体/ SFMono- *〜/库/字体
```

## Functions

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/functions.md).


## Hardware

### Bluetooth

Up to OS X 10.12 (Sierra) the Bluetooth daemon is named `blued` instead of
蓝牙您需要相应地调整`killall`命令.

```sh
## Status
默认读取/Library/Preferences/com.apple.Bluetooth ControllerPowerState

## Enable (Default)
sudo默认写入/Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 1

## Disable
sudo默认写入/Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 0 &amp;&amp; \
sudo killall -HUP蓝牙
```

### Harddisks

#### Force Trim
为非Apple SSD启用Trim. 自OS X 10.10（Yosemite）起提供此命令.
```sh
trimforce
```

### Hardware Information

#### List All Hardware Ports
```sh
networksetup -listall硬件端口
```

#### Remaining Battery Percentage
```sh
 pmset -g batt |  egrep“（[[0-9] + \％）.*” -o --colour = auto | 切-f1 -d&#39;;&#39;
```

#### Remaining Battery Time
```sh
 pmset -g batt |  egrep“（[[0-9] + \％）.*” -o --colour = auto | 切-f3 -d&#39;;&#39;
```

#### Show Connected Device's UDID
```sh
 system_profiler SPUSBDataType |  sed -n -e&#39;/ iPad /，/ Serial / p&#39;-e&#39;/ iPhone /，/ Serial / p&#39;
```

#### Show Current Screen Resolution
```sh
 system_profiler SPDisplaysDataType |  grep分辨率
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
默认写入/Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 1

## Disable
默认写入/Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 0
```

### Power Management

#### Prevent System Sleep
防止睡眠1小时：
```sh
咖啡因-u -t 3600
```

#### Show All Power Management Settings
```sh
须藤pmset -g
```

#### Put Display to Sleep after 15 Minutes of Inactivity
```sh
须藤pmset displaysleep 15
```

#### Put Computer to Sleep after 30 Minutes of Inactivity
```sh
须藤pmset睡眠30
```

#### Check System Sleep Idle Time
```sh
sudo systemsetup -getcomputersleep
```

#### Set System Sleep Idle Time to 60 Minutes
```sh
sudo systemsetup -setcomputersleep 60
```

#### Turn Off System Sleep Completely
```sh
sudo systemsetup -setcomputersleep从不
```

#### Automatic Restart on System Freeze
```sh
sudo systemsetup -setartfreeze在
```

#### Chime When Charging
连接MagSafe时播放iOS充电声音.
```sh
## Enable
默认写com.apple.PowerChime ChimeOnAllHardware -bool true &amp;&amp; \
打开/System/Library/CoreServices/PowerChime.app

## Disable (Default)
默认写com.apple.PowerChime ChimeOnAllHardware -bool false &amp;&amp; \
杀死所有力量
```


## Input Devices

### Keyboard

#### Auto-Correct
```sh
## Disable
默认为write -g NSAutomaticSpellingCorrectionEnabled -bool false

## Enable (Default)
默认为write -g NSAutomaticSpellingCorrectionEnabled -bool true

## Show Status
默认读取为-g NSAutomaticSpellingCorrectionEnabled
```

#### Full Keyboard Access
在模式对话框中启用选项卡.
```sh
## Text boxes and lists only (Default)
默认写入NSGlobalDomain AppleKeyboardUIMode -int 0

## All controls
默认写入NSGlobalDomain AppleKeyboardUIMode -int 3
```

#### Key Repeat
更改“按住”行为.
```sh
## Enable
默认写-g ApplePressAndHoldEnabled -bool false

## Disable (Default)
默认写-g ApplePressAndHoldEnabled -bool true
```

#### Key Repeat Rate
设置非常快的重复率，调整以适应口味.
```sh
默认写-g KeyRepeat -int 0.02
```

## Launchpad

#### Reset Launchpad Layout
您需要重新启动`Dock`，因为Launchpad已绑定到它.
```sh
## Up to OS X 10.10 (Yosemite)
rm〜/ Library / Application \ Support / Dock / *.db &amp;&amp; \
杀人码头

## From OS X 10.11 (El Capitan)
默认写com.apple.dock ResetLaunchPad -bool true &amp;&amp; \
杀人码头
```

## Media

### Audio

#### Convert Audio File to iPhone Ringtone
```sh
afconvert input.mp3铃声.m4r -f m4af
```

#### Create Audiobook From Text
使用“ Alex”语音（用于输入和AAC输出的普通UTF-8编码文本文件）.
```sh
说-v Alex -f file.txt -o“ output.m4a”
```

#### Disable Sound Effects on Boot
```sh
sudo nvram SystemAudioVolume =“”
```

#### Mute Audio Output
```sh
osascript -e&#39;设置音量输出静音为真&#39;
```

#### Set Audio Volume
```sh
osascript -e&#39;设置音量4&#39;
```

#### Play Audio File
您可以播放QuickTime本机支持的所有音频格式.
```sh
afplay -q 1 filename.mp3
```

#### Speak Text with System Default Voice
```sh
说“您的所有基地都属于我们！”
```

#### Startup Chime
较旧的Mac：
```sh
## Enable (Default)
sudo nvram BootAudio =％01

## Disable
sudo nvram BootAudio =％00
```

从2016年型号开始：
```sh
## Enable
sudo nvram StartupMute =％00

## Disable (Default)
sudo nvram StartupMute =％01
```

### Video

#### Auto-Play Videos in QuickTime Player
```sh
默认写入com.apple.QuickTimePlayerX MGPlayMovieOnOpen 1
```


## Networking

### Bonjour

#### Bonjour Service
```sh
## Disable
sudo默认写/System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array-add“ -NoMulticastAdvertisements”

## Enable (Default)
sudo默认写/System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array“ / usr / sbin / mDNSResponder”“ -launchd”
```

### DHCP

#### Renew DHCP Lease
```sh
sudo ipconfig设置en0 DHCP
```

#### Show DHCP Info
```sh
ipconfig getpacket zh-CN
```

### DNS

#### Clear DNS Cache
```sh
sudo dscacheutil -flushcache &amp;&amp; \
须藤killall -HUP mDNSResponder
```

### Hostname

#### Set Computer Name/Host Name
```sh
sudo scutil --set ComputerName“ newhostname” &amp;&amp; \
sudo scutil --set HostName“ newhostname” &amp;&amp; \
sudo scutil --set LocalHostName“ newhostname” &amp;&amp; \
sudo默认写/Library/Preferences/SystemConfiguration/com.apple.smb.server NetBIOSName -string“ newhostname”
```

### Network Preferences

#### Network Locations
在“网络”首选项窗格中创建的网络位置之间切换.
```sh
## Status
scselect

## Switch Network Location
scselect LocationNameFromStatus
```

#### Set Static IP Address
```sh
networksetup -setmanual“ Ethernet” 192.168.2.100 255.255.255.0 192.168.2.1
```

### Networking Tools

#### Ping a Host to See Whether It’s Available
```sh
ping -o github.com
```

#### Troubleshoot Routing Problems
```sh
traceroute github.com
```

### SSH

#### Permanently Add Private Key Passphrase to SSH Agent
&gt;在macOS 10.12（Sierra）之前，ssh将显示一个对话框，询问您
 &gt;密码，并提供将其存储到钥匙串中的选项. 这个使用者介面
&gt;不久前已过时，已被删除.
>
&gt;而是在macOS 10.12（Sierra）中引入了新的UseKeychain选项
&gt;允许用户指定是否希望使用密码短语
 &gt;存储在钥匙串中. 默认情况下，此选项已在macOS 10.12上启用
&gt;（Sierra），这导致所有密码短语都存储在钥匙串中.
>
&gt;这不是预期的默认行为，因此在macOS中已对此进行了更改
> 10.12.2.
> ([Source](https://developer.apple.com/library/archive/technotes/tn2449/_index.html))
```sh
ssh-add -K / path / to / private_key
```
然后添加到`〜/ .ssh / config`中：
```sh
主机server.example.com
    IdentityFile / path / to / private_key
    UseKeychain是
```

#### Remote Login
```sh
## Enable
sudo launchctl加载-w /System/Library/LaunchDaemons/ssh.plist

## Disable (Default)
sudo launchctl卸载-w /System/Library/LaunchDaemons/ssh.plist
```

### TCP/IP

#### Show Application Using a Certain Port
这将输出当前使用端口80的所有应用程序.
```sh
须藤lsof -i：80
```

#### Show External IP Address
如果您的ISP不替换DNS请求（不应该），则可以使用.
```sh
挖+短myip.opendns.com @ resolver1.opendns.com
```
适用于所有网络的替代方案.
```sh
curl -s https://api.ipify.org &amp;&amp;回声
```

#### Show Network Interface Information
`scutil`命令的未记录标志.
```sh
scutil --nwi
```

### TFTP

#### Start Native TFTP Daemon
文件将从`/ private / tftpboot`提供.
```sh
sudo launchctl加载-F /System/Library/LaunchDaemons/tftp.plist &amp;&amp; \
sudo launchctl启动com.apple.tftpd
```

### Wi-Fi

#### Join a Wi-Fi Network
```sh
networksetup -setairportnetwork en0 WIFI_SSID WIFI_PASSWORD
```

#### Scan Available Access Points
创建指向airport命令的符号链接，以方便访问：
```sh
sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport / usr / local / bin / airport
```
运行无线扫描：
```sh
机场-s
```

#### Show Current SSID
```sh
 /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -I |  awk&#39;/ SSID / {print substr（$ 0，index（$ 0，$ 2））}&#39;
```

#### Show Local IP Address
```sh
ipconfig getifaddr zh-CN
```

#### Show Wi-Fi Connection History
```sh
默认读取/Library/Preferences/SystemConfiguration/com.apple.airport.preferences |  grep LastConnected -A 7
```

#### Show Wi-Fi Network Passwords
用您要从中查询密码的接入点的SSID交换SSID.
```sh
安全查找通用密码-D“ AirPort网络密码” -a“ SSID” -gw
```

#### Turn on Wi-Fi Adapter
```sh
启用networksetup -setairportpower en0
```

## Package Managers

- [Fink](http://www.finkproject.org) -Unix开源的完整世界
  达尔文软件. 有点过时了.
- [Homebrew](https://brew.sh) -OS X缺少的包管理器.
  受欢迎的选择.
- [MacPorts](https://www.macports.org) -编译，安装和升级
  命令行，基于X11或Aqua的开源软件.

### Homebrew

#### Full Uninstall

```sh
ruby -e“ $（curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall）”
```


## Printing

#### Clear Print Queue
```sh
cancel -a -
```

#### Expand Print Panel by Default
```sh
默认写-g PMPrintingExpandedStateForPrint -bool true &amp;&amp; \
默认写-g PMPrintingExpandedStateForPrint2 -bool true
```

#### Quit Printer App After Print Jobs Complete
```sh
默认写com.apple.print.PrintingPrefs“完成后退出” -bool true
```


## Security

### Application Firewall

#### Firewall Service
```sh
## Show Status
须藤/ usr / libexec / ApplicationFirewall / socketfilterfw --getglobalstate

## Enable
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --setglobalstate在

## Disable (Default)
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --setglobalstate关闭
```

#### Add Application to Firewall
```sh
须藤/ usr / libexec / ApplicationFirewall / socketfilterfw --add / path / to / file
```

### Gatekeeper

#### Add Gatekeeper Exception
```sh
spctl-添加/path/to/Application.app
```

#### Remove Gatekeeper Exception
```sh
spctl-删除/path/to/Application.app
```

#### Manage Gatekeeper
对于讨厌的macOS 10.15（Catalina）系统弹出窗口特别有用
阻止非签名应用程序的执行.
```sh
## Status
spctl-状态

## Enable (Default)
sudo spctl --master-启用

## Disable
sudo spctl --master-禁用
```

### Passwords

#### Generate Secure Password and Copy to Clipboard
```sh
 LC_ALL = C tr -dc“ [：alnum：]” &lt;/ dev / urandom | 头-c 20 |  pbcopy
```

### Physical Access

#### Launch Screen Saver

```sh
## Up to macOS 10.12 (Sierra)
打开/System/Library/Frameworks/ScreenSaver.framework/Versions/A/Resources/ScreenSaverEngine.app

## From macOS 10.13 (High Sierra)
/System/Library/CoreServices/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine
```


#### Lock Screen
```sh
/ System / Library / CoreServices / Menu \ Extras / User.menu / Contents / Resources / CGSession -suspend
```

#### Screensaver Immediate Lock
```sh
## Status
默认读取com.apple.screensaver askForPasswordDelay

## Enable (Default)
默认写com.apple.screensaver askForPasswordDelay -int 0

## Disable (Integer = lock delay in seconds)
defaults write com.apple.screensaver askForPasswordDelay -int 10
```

#### Screensaver Password
```sh
## Status
默认读取com.apple.screensaver askForPassword

## Enable
默认写com.apple.screensaver askForPassword -int 1

## Disable (Default)
默认写com.apple.screensaver askForPassword -int 0
```

### Privacy Database

tccutil命令管理隐私数据库，该数据库存储决策
用户已确定应用程序是否可以访问个人数据. 您需要关闭
在运行这些命令中的任何命令之前，除Terminal以外的所有应用程序.

```sh
## Full Reset for All Applications
sudo tccutil重设所有

## Reset Adress Book Access
sudo tccutil重置地址簿

## Reset All Permission for Terminal.app
sudo tccutil reset全部com.apple.Terminal
```

### Wiping Data

注意：在Mac OS 10.9之后，似乎已删除了srm命令. 那里
是关于 [Apple support page](https://support.apple.com/en-us/HT201949)
暗示原因：
&gt;对于SSD驱动器，安全擦除和擦除可用空间在以下版本中不可用
 &gt;磁盘实用程序.  SSD驱动器不需要这些选项，因为
&gt;标准擦除使得很难从SSD恢复数据.

#### Securely Remove File
```sh
srm /路径/到/文件
```

#### Securely Remove Folder
```sh
srm -r /路径/到/文件夹/
```

#### Securely Remove Path (Force)
```sh
srm -rf /路径/到/完成/破坏
```


## Search

### Find

#### Recursively Delete .DS_Store Files
```sh
找 .  -type f -name&#39;.DS_Store&#39;-ls -delete
```

### Locate

#### Build Locate Database
```sh
sudo launchctl加载-w /System/Library/LaunchDaemons/com.apple.locate.plist
```

#### Search via Locate
-i修饰符使搜索大小写不敏感.
```sh
定位-i * .jpg
```


## System

### AirDrop

#### AirDrop over Ethernet on Unsupported Macs
```sh
## Enable
默认写com.apple.NetworkBrowser BrowseAllInterfaces -bool true &amp;&amp; \
默认情况下删除com.apple.NetworkBrowser DisableAirDrop

## Disable (Default)
默认情况下删除com.apple.NetworkBrowser BrowseAllInterfaces &amp;&amp; \
默认写com.apple.NetworkBrowser DisableAirDrop -bool是
```

### AppleScript

#### Execute AppleScript
```sh
osascript /path/to/script.scpt
```

### Basics

#### Compare Two Folders
```sh
差异-qr / path / to / folder1 / path / to / folder2
```

#### Copy Large File with Progress
确保已安装`pv`，然后将`/ dev / rdisk2`替换为
适当的写入设备或文件.
```sh
 FILE = / path / to / file.iso pv -s $（du -h $ FILE | awk&#39;/.*/ {print $ 1}&#39;）$ FILE | 须藤dd of = / dev / rdisk2 bs = 1m
```

#### Restore Sane Shell
万一您的shell会话发疯（某些脚本或应用程序将其关闭）
变成乱码）.
```sh
斯塔蒂·理智
```

#### Restart
```sh
须藤重启
```

#### Shutdown
```sh
须藤断电
```

#### Show Build Number of OS
```sh
sw_vers
```

#### Uptime
自上次重新启动以来已经过了多长时间.
```sh
uptime
```

### Clipboard

#### Copy data to Clipboard
```sh
猫what.txt |  pbcopy
```

#### Convert Clipboard to Plain Text
```sh
 pbpaste |  textutil -convert txt -stdin -stdout -encoding 30 |  pbcopy
```

```sh
 pbpaste | 扩大|  pbcopy
```

#### Copy data from Clipboard
```sh
pbpaste&gt; what.txt
```

```sh
 pbpaste | 排序|  uniq |  pbcopy
```

### FileVault

#### Automatically Unlock FileVault on Restart
如果在当前卷上启用了FileVault，它将重新启动系统，
bypassing the initial unlock. The command may not work on all systems.
```sh
须藤fdesetup authrestart
```

#### FileVault Service
```sh
## Status
sudo fdesetup状态

## Enable
sudo fdesetup启用

## Disable (Default)
sudo fdesetup禁用
```

### Information/Reports

#### Generate Advanced System and Performance Report
```sh
sudo sysdiagnose -f〜/桌面/
```

### Installation

#### Create Bootable Installer
```sh
## macOS 11 (Big Sur)
sudo / Applications / Install \ macOS \ Big \ Sur.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --nointeraction --downloadassets

## macOS 10.15 (Catalina)
sudo / Applications / Install \ macOS \ Catalina.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --nointeraction --downloadassets

## macOS 10.14 (Mojave)
sudo / Applications / Install \ macOS \ Mojave.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --nointeraction --downloadassets

## macOS 10.13 (High Sierra)
sudo / Applications / Install \ macOS \ High \ Sierra.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ macOS \ High \ Sierra.app

## macOS 10.12 (Sierra)
sudo / Applications / Install \ macOS \ Sierra.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ macOS \ Sierra.app

## OS X 10.11 (El Capitan)
sudo / Applications / Install \ OS \ X \ El \ Capitan.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ OS \ X \ El \ Capitan.app

## OS X 10.10 (Yosemite)
sudo / Applications / Install \ OS \ X \ Yosemite.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ OS \ X \ Yosemite.app
```

*为了在擦除驱动器之前进行确认，请从驱动器中删除`–nointeraction`.
  命令.
 *可选的“ –-downloadassets”标志是macOS 10.14（Mojave）中的新增功能. 它
  下载安装过程中可能需要的资产，例如更新.
*自从macOS 10.14（Mojave）和
  如果使用将抛出错误.

#### Download Older OS Versions

版本| 代号| 下载
------------- | ------------- | --------
 Mac OS X 10.0 | 猎豹不适用
 Mac OS X 10.1 | 彪马| 不适用
 Mac OS X 10.2 | 美洲虎| 在
 Mac OS X 10.3 | 豹| 不适用
 Mac OS X 10.4 | 老虎| 不适用
 Mac OS X 10.5 | 豹纹| 不适用
 Mac OS X 10.6 | 雪豹| 不适用
 Mac OS X 10.7 | 狮子| 不适用
 OS X 10.8 | 山狮| 不适用
 OS X 10.9 | 小牛| 不适用
OS X 10.10 |优胜美地| [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-41343-20191023-02465f92-3ab5-4c92-bfe2-b725447a070d/InstallMacOSX.dmg)
 OS X 10.11 | 埃尔卡皮坦| [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-41424-20191024-218af9ec-cf50-4516-9011-228c78eda3d2/InstallMacOSX.dmg)
 macOS 10.12 | 塞拉利昂| [Direct Download](http://updates-http.cdn-apple.com/2019/cert/061-39476-20191023-48f365f4-0015-4c41-9f44-39d3d2aca067/InstallOS.dmg)
 macOS 10.13 | 高塞拉利昂| [App Store](https://apps.apple.com/de/app/macos-high-sierra/id1246284741)
 macOS 10.14 | 莫哈韦沙漠| [App Store](https://apps.apple.com/de/app/macos-mojave/id1398502828)
 macOS 10.15 | 卡塔琳娜| [App Store](https://apps.apple.com/de/app/macos-catalina/id1466841314)

### Kernel Extensions

#### Display Status of Loaded Kernel Extensions
```sh
须藤kextstat -l
```

#### Load Kernel Extension
```sh
sudo kextload -b com.apple.driver.ExampleBundle
```

#### Unload Kernel Extensions
```sh
sudo kextunload -b com.apple.driver.ExampleBundle
```

### LaunchAgents

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/launchagents.md).


### LaunchServices

#### Rebuild LaunchServices Database
为了独立于OS X版本，这依赖于`locate`来查找
 lsregister. 如果您尚未建立`locate`数据库，请[
it](#build-locate-database).
```sh
须藤$（locate lsregister）-kill -seed -r
```

### Login Window

#### Set Login Window Text
```sh
sudo默认写/Library/Preferences/com.apple.loginwindow LoginwindowText“您的文本”
```

### Memory Management

#### Purge memory cache
```sh
须藤吹扫
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
launchctl卸载-w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist &amp;&amp; \
killall -9 NotificationCenter

## Enable (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist
```

### QuickLook

#### Preview via QuickLook
```sh
qlmanage -p /路径/到/文件
```

### Remote Management

也可以看看： [Apple Remote Desktop](#apple-remote-desktop).

#### Prevent Double Password Entry
通过Apple Remote Desktop或VNC远程登录Mac时，您是
有时需要在连接到
苹果电脑. 尽管您可以禁用此行为，但明确建议您不要
除非您确定没有其他人会关闭此功能，否则请关闭此功能.
不在时可以物理访问Mac.
```sh
## Disable
sudo默认写/Library/Preferences/com.apple.RemoteManagement.plist RestoreMachineState -bool否

## Enable (Default)
sudo默认写/Library/Preferences/com.apple.RemoteManagement.plist RestoreMachineState -bool是
```

#### Remote Apple Events
```sh
## Status
sudo systemsetup -getremoteappleevents

## Enable
sudo systemsetup -setremoteappleevents在

## Disable (Default)
sudo systemsetup -setremoteappleevents关闭
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
nvram引导参数

## Enable
sudo nvram boot-args =“-x”

## Disable (Default)
sudo nvram boot-args =“”
```

### Save Dialogs

大大改善了保存对话框中现在比较慢的动画.

```sh
默认写入NSGlobalDomain NSWindowResizeTime .001
```

### Screenshots

#### Take Delayed Screenshot
3秒后以JPEG格式截屏，并显示在“预览”中.
```sh
屏幕捕获-T 3 -t jpg -P delaypic.jpg
```

#### Save Screenshots to Given Location
将位置设置为“〜/桌面”.
```sh
默认写com.apple.screencapture位置〜/ Desktop &amp;&amp; \
杀死所有SystemUIServer
```

#### Save Screenshots in Given Format
将格式设置为“ png”. 其他选项包括`bmp`，`gif`，`jpg`，`jpeg`，`pdf`，
`tiff`.
```sh
默认写入com.apple.screencapture类型-string“ png”
```

#### Disable Shadow in Screenshots
```sh
默认写com.apple.screencapture disable-shadow -bool true &amp;&amp; \
杀死所有SystemUIServer
```

#### Set Default Screenshot Name
日期和时间保持不变.
```sh
默认写入com.apple.screencapture名称“示例名称” &amp;&amp; \
杀死所有SystemUIServer
```

### Software Installation

#### Install PKG
```sh
安装程序-pkg /path/to/installer.pkg -target /
```

### Sidecar

#### Use on Incompatible Macs
这可能会或可能不会起作用，具体取决于机器的寿命.
```sh
## Enable
默认写com.apple.sidecar.display AllowAllDevices -bool true &amp;&amp; \
默认写com.apple.sidecar.display hasShownPref -bool true

## Disable (Default)
默认删除com.apple.sidecar.display
```

### Software Update

#### Ignore Specific Software Update
The identifier can be found via `softwareupdate --list`. In the example below,
在macOS 10.14（Mojave）上，将忽略对macOS 10.15的所有更新提示
（Catalina），因为后者删除了32位支持.
```sh
sudo /usr/sbin/softwareupdate --ignore "macOS Catalina"
```

#### Install All Available Software Updates
```sh
sudo软件更新-ia
```

#### Set Software Update Check Interval
设置为每天检查，而不是每周检查.
```sh
默认写com.apple.SoftwareUpdate ScheduleFrequency -int 1
```

#### Show Available Software Updates
```sh
sudo softwareupdate-列表
```

#### Set Software Update Server
仅应出于测试目的或不受管理的客户端执行此操作. 使用
在整个网络范围内，可以正确设置DNS以及[Apple SUS
service](http://krypted.com/mac-security/using-the-software-update-service-on-mountain-lion-server/)
并通过OpenDirectory绑定您的客户. 或者，使用
[Reposado](https://github.com/wdas/reposado) 连同正确的网络DNS
设置以使分辨率透明.
[Margarita](https://github.com/jessepeterson/margarita) 看起来很高兴
well.
```sh
## Use own SUS
sudo默认值写入/Library/Preferences/com.apple.SoftwareUpdate CatalogURL http://su.example.com:8088/index.sucatalog

## Reset to Apple SUS
sudo默认值删除/Library/Preferences/com.apple.SoftwareUpdate CatalogURL
```

### Software Version

#### Show System Software Version
有几种方法可以获取不同级别的详细信息.
```sh
sw_vers -productVersion
```
```sh
system_profiler SPSoftwareDataType
```
```sh
默认读取登录窗口SystemVersionStampAsString
```

### Spotlight

#### Spotlight Indexing
```sh
## Disable
mdutil -i off -d / path / to / volume

## Enable (Default)
在/ path / to / volume上的mdutil -i
```

#### Erase Spotlight Index and Rebuild
```sh
mdutil -E /路径/到/卷
```

#### Search via Spotlight
```sh
mdfind -name&#39;searchterm&#39;
```

#### Show Spotlight Indexed Metadata
```sh
mdls /路径/到/文件
```

### System Integrity Protection

按住<kbd>Cmd</kbd> + <kbd>R</kbd>重启并打开终端
应用. 您将需要重新启动命令才能生效.

```sh
## Status
csrutil状态

## Enable (Default)
csrutil启用

## Disable
csrutil禁用
```

### Date and Time

#### List Available Timezones
```sh
sudo systemsetup -listtimezones
```

#### Set Timezone
```sh
sudo systemsetup -settimezone欧洲/柏林
```

#### Set Clock Using Network Time
```sh
## Status
须藤系统设置getusingnetworktime

## Enable (Default)
sudo systemsetup setusingnetworktime on

## Disable
sudo systemsetup setusingnetworktime关闭
```

#### Set Menu Bar Clock Output Format
```sh
## System Preferences > Date & Time > Time options
## Analogue
sudo默认写com.apple.menuextra.clock IsAnalog -bool true
## Digital (Default)
sudo默认写com.apple.menuextra.clock IsAnalog -bool false

## System Preferences > Date & Time > Flash the time separators
## Enable
sudo默认写com.apple.menuextra.clock FlashDateSeparators -bool true
## Disable (Default)
sudo默认写com.apple.menuextra.clock FlashDateSeparators -bool false

## Thu 18 Aug 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM HH：mm：ss”

## Thu 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE HH：mm：ss”

## 18 Aug 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM HH：mm：ss”

## 23:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ HH：mm：ss”

## Thu 18 Aug 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM h：mm：ss a”


## Thu 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE h：mm：ss a”

## 18 Aug 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM h：mm：ss a”

## 11:46:18 pm
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ h：mm：ss a”

## Thu 18 Aug 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM h：mm：ss”

## Thu 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE h：mm：ss”

## 18 Aug 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM h：mm：ss”

## 11:46:18
## System Preferences > Date & Time > Display time with seconds - Checked [:ss]
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ h：mm：ss”

## Thu 18 Aug 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM HH：mm”

## Thu 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE HH：mm”

## 18 Aug 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM HH：mm”

## 23:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Checked [HH:mm]
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ HH：mm”

## Thu 18 Aug 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM h：mm a”

## Thu 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE h：mm a”

## 18 Aug 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM h：mm a”

## 11:46 pm
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Checked [a]
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ h：mm a”

## Thu 18 Aug 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE d MMM h：mm”

## Thu 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Checked [EEE]
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ EEE h：mm”

## 18 Aug 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Checked [d MMM]
sudo默认写com.apple.menuextra.clock DateFormat -string“ d MMM h：mm”

## 11:46
## System Preferences > Date & Time > Display time with seconds - Unchecked
## System Preferences > Date & Time > Use a 24-hour clock - Unchecked
## System Preferences > Date & Time > Show AM/PM - Unchecked
## System Preferences > Date & Time > Show the day of the week - Unchecked
## System Preferences > Date & Time > Show date - Unchecked
sudo默认写com.apple.menuextra.clock DateFormat -string“ h：mm”

## Apply changes immediately
sudo killall SystemUIServer
```

([Source](https://github.com/tech-otaku/macos-defaults/blob/master/date-time.sh))


## Terminal

#### Ring Terminal Bell
敲响终端铃（如果已启用）并在其上贴上徽章.
```sh
贝尔
```

### Alternative Terminals

- [Alacritty](https://github.com/jwilm/alacritty) -跨平台
  GPU加速的终端仿真器.
- [iTerm2](https://iterm2.com) -更好的Terminal.app.
- [kitty](https://sw.kovidgoyal.net/kitty/) -先进的GPU加速终端
  仿真器.

### Shells

#### Bash
安装最新版本并设置为当前用户的默认外壳程序：
```sh
brew install bash &amp;&amp; \
 echo $（brew --prefix）/ bin / bash |  sudo tee -a / etc / shells &amp;&amp; \
chsh -s $（brew --prefix）/ bin / bash
```

- [Homepage](https://www.gnu.org/software/bash/) -OS X的默认外壳
  以及大多数其他基于Unix的操作系统.
- [Bash-it](https://github.com/Bash-it/bash-it) -社区Bash框架，
  就像《我的Bash哦我的Zsh》.

#### fish
安装最新版本并设置为当前用户的默认外壳程序：
```sh
酿造鱼&amp;&amp; \
 echo $（brew --prefix）/ bin / fish |  sudo tee -a / etc / shells &amp;&amp; \
chsh -s $（brew --prefix）/ bin /鱼
```

- [Homepage](http://fishshell.com) -智能且用户友好的命令行
  OS X，Linux和其他系列的外壳.
- [The Fishshell Framework](https://github.com/oh-my-fish/oh-my-fish) -
  提供核心基础结构，使您可以安装扩展或扩展的软件包
  修改外壳的外观.
-[安装与配置
  教程]（https://github.com/ellerbrock/fish-shell-setup-osx）-如何设置
  Fish Shell，在OS上具有Fisherman，Powerline字体，iTerm2和Budspencer主题
  X.

#### Zsh
安装最新版本并设置为当前用户的默认外壳程序：
```sh
brew install zsh &amp;&amp; \
sudo sh -c&#39;echo $（brew --prefix）/ bin / zsh &gt;&gt; / etc / shells&#39;&amp;&amp; \
chsh -s $（brew --prefix）/ bin / zsh
```

- [Homepage](http://www.zsh.org) -Zsh是专为互动使用而设计的外壳，
  尽管它还是一种功能强大的脚本语言.
- [Oh My Zsh](http://ohmyz.sh) -开源，社区驱动的框架
  管理您的Zsh配置.
- [Prezto](https://github.com/sorin-ionescu/prezto) -快速的Zsh框架.
  通过合理的默认设置，别名，
  功能，自动完成和提示主题.
- [zgen](https://github.com/tarjoilija/zgen) -另一个开源框架
  用于管理zsh配置.  Zgen将加载oh-my-zsh兼容
  插件和主题，并具有速度更快和
  自动为您克隆配置中使用的所有插件.

### Terminal Fonts

- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) - 一种
  四个固定宽度字体家族，在设计时考虑了编码.
- [Codeface](https://github.com/chrissimpkins/codeface) -画廊和
  开发人员的等宽字体存储库.
- [DejaVu Sans Mono](https://dejavu-fonts.github.io/) -基于
  维拉字体.
- [Fantasque Sans Mono](https://github.com/belluzj/fantasque-sans) -设计
  考虑到功能性，并且有些像颤抖的笔迹般的笔迹
  模糊性使其变得异常酷.
- [Hack](http://sourcefoundry.org/hack/) -哈克（Hack）经过手工修饰和修饰
  平衡成为您首选的代码.
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) -一个等宽
  字体，用于代码清单等.
- [Input](http://input.fontbureau.com) -灵活的字体系统设计
  专门用于代码.
- [Meslo](https://github.com/andreberg/Meslo-Font) -的定制版本
  苹果的Menlo字体.
- [Operator Mono](https://www.typography.com/fonts/operator/overview/) - 一种
  等宽字体（商业）上令人惊讶地有用的替代选择.
- [Powerline Fonts](https://github.com/powerline/fonts) -修补字体的回购
  用于Powerline插件.
- [Source Code Pro](https://adobe-fonts.github.io/source-code-pro/) - 一种
  用于用户界面和编码环境的等宽字体系列.


## Glossary

### Mac OS X, OS X, and macOS Version Information

版本| 代号| 发行日期| 最新版本
-------------------------- | ------------------ | ------------------ | -------------------------------------
 Rhapsody开发人员发布|  Grail1Z4 / Titan1U |  1997年8月31日|  DR2（1998年5月14日）
 Mac OS X服务器1.0 | 赫拉|  1999年3月16日|  1.2v3（2000年10月27日）
 Mac OS X开发人员预览| 不适用 1999年3月16日|  DP4（2000年4月5日）
 Mac OS X公开Beta版| 科迪亚克|  2000年9月13日| 不适用
 Mac OS X 10.0 | 猎豹 2001年3月24日|  10.0.4（2001年6月22日）
 Mac OS X 10.1 | 彪马|  2001年9月25日|  10.1.5（2002年6月6日）
 Mac OS X 10.2 | 美洲虎|  2002年8月24日|  10.2.8（2003年10月3日）
 Mac OS X 10.3 | 豹|  2003年10月24日|  10.3.9（2005年4月15日）
 Mac OS X 10.4 | 老虎|  2005年4月29日|  10.4.11（2007年11月14日）
 Mac OS X 10.5 | 豹纹|  2007年10月26日|  10.5.8（2009年8月5日）
 Mac OS X 10.6 | 雪豹|  2009年8月28日|  10.6.8 v1.1（2011年7月25日）
 Mac OS X 10.7 | 狮子|  2011年7月20日|  10.7.5（2012年9月19日）
 OS X 10.8 | 山狮|  2012年7月25日|  10.8.5（12F45）（2013年10月3日）
 OS X 10.9 | 小牛|  2013年10月22日|  10.9.5（13F1112）（2014年9月18日）
 OS X 10.10 | 优胜美地|  2014年10月16日|  10.10.5（14F27）（2015年8月13日）
 OS X 10.11 | 埃尔卡皮坦|  2015年9月30日|  10.11.6（15G31）（2016年7月18日）
 macOS 10.12 | 塞拉利昂|  2016年9月20日|  10.12.6（16G29）（2017年7月19日）
 macOS 10.13 | 高塞拉利昂|  2017年9月25日|  10.13.6（17G65）（2018年7月9日）
 macOS 10.14 | 莫哈韦沙漠|  2018年9月24日|  10.14.6（18G3020）（2020年1月28日）
 macOS 10.15 | 卡塔琳娜|  2019年10月7日|  10.15.5（19F101）（2020年6月1日）


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /><br />这项工作是根据<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享4.0国际许可许可的</a>.
