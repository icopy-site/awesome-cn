<div class="github-widget" data-repo="herrbischoff/awesome-macos-command-line"></div>
<h1><img src="https://cdn.rawgit.com/herrbischoff/awesome-macos-command-line/cab824f0/assets/logo.svg" alt="Awesome macOS Command Line" width="600"></h1>

&gt;特定于OS X的shell命令和工具的精选列表.
>
 &gt; _“你不必知道一切.  你只需要知道必要时在哪里找到它.“（John Brunner）_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/herrbischoff/awesome-macos-command-line.svg?branch=master)](https://travis-ci.org/herrbischoff/awesome-macos-command-line)

 如果您想贡献，我们强烈建议您这样做.  请阅读 [contribution guidelines](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/contributing.md).

有关更多终端外壳的好处，请参阅此列表的姐妹列表 [Awesome Command Line Apps](https://github.com/herrbischoff/awesome-command-line-apps).


## Caffeinating

 当你在这里找到有用的东西时，你可以给我买一杯咖啡.  我花了很多时间和精力来策划这份清单.  保持适当的咖啡因加速了事情.  它真的会成为我的一天.  善良的陌生人和所有这一切.  如果你不能或不会，没有难过的感情.  由于某种原因，它完全免费.  不过，它会很棒.

Patreon：https：//www.patreon.com/herrbischoff





## Appearance

### Transparency

#### Transparency in Menu and Windows
```bash
## Reduce Transparency
默认写入com.apple.universalaccess reduceTransparency -bool true

## Restore Default Transparency
默认写入com.apple.universalaccess reduceTransparency -bool false
```


### Wallpaper

#### Set Wallpaper
```bash
## Up to Mountain Lion
osascript -e&#39;告诉应用程序“Finder”将桌面图片设置为POSIX文件“/path/to/picture.jpg”&#39;

## Since Mavericks
sqlite3~ / Library / Application \ Support / Dock / desktoppicture.db“update data set value =&#39;/ path / to / picture.jpg&#39;”&amp;&amp; killall Dock
```


## Applications

### App Store

#### List All Apps Downloaded from App Store

```bash
## Via find
find /Applications -path '*Contents/_MASReceipt/receipt' -maxdepth 4 -print |\sed 's#.app/Contents/_MASReceipt/receipt#.app#g; s#/Applications/##'

## Via Spotlight
mdfind kMDItemAppStoreHasReceipt = 1
```

#### Show Debug Menu
适用于优胜美地.
```bash
## Enable
defaults write com.apple.appstore ShowDebugMenu -bool true

## Disable (Default)
默认写入com.apple.appstore ShowDebugMenu -bool false
```


### Apple Remote Desktop

#### Kickstart Manual Pages
```bash
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart-help
```

#### Activate And Deactivate the ARD Agent and Helper
```bash
## Activate And Restart the ARD Agent and Helper
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -activate -restart -agent -console

## Deactivate and Stop the Remote Management Service
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -stop
```

#### Enable and Disable Remote Desktop Sharing
```bash
## Allow Access for All Users and Give All Users Full Access
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -configure -allowAccessFor -allUsers -privs -all

## Disable ARD Agent and Remove Access Privileges for All Users
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -configure -access -off
```

#### Remove Apple Remote Desktop Settings
```bash
 sudo rm -rf / var / db / RemoteManagement;  \
 sudo默认删除/Library/Preferences/com.apple.RemoteDesktop.plist;  \
 默认删除〜/ Library / Preferences / com.apple.RemoteDesktop.plist;  \
 sudo rm -r / Library / Application \ Support / Apple / Remote \ Desktop /;  \
 rm -r~ / Library / Application \ Support / Remote \ Desktop /;  \
rm -r~ / Library / Containers / com.apple.RemoteDesktop
```

### Contacts

#### Debug Mode
```bash
## Enable
defaults write com.apple.addressbook ABShowDebugMenu -bool true

## Disable (Default)
默认写com.apple.addressbook ABShowDebugMenu -bool false
```

### Google

#### Uninstall Google Update
```bash
〜/ Library / Google / GoogleSoftwareUpdate / GoogleSoftwareUpdate.bundle / Contents / Resources / ksinstall --nuke
```

### iTunes

#### Keyboard Media Keys
 这适用于优胜美地.  El Capitan中引入了系统完整性保护，可防止卸载系统启动代理.
```bash
## Stop Responding to Key Presses
launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist

## Respond to Key Presses (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

 从El Capitan开始，您可以禁用SIP或使用某种黑客攻击，这将使任何用户无法访问iTunes，从而有效地阻止它自己或其帮助者启动.  请注意，出于所有意图和目的，这将废弃您的iTunes安装，并可能与未来的操作系统更新冲突.
```bash
sudo chmod 0000 /Applications/iTunes.app
```

### Mail

#### Show Attachments as Icons

```bash
defaults write com.apple.mail DisableInlineAttachmentViewing -bool yes
```

#### Vacuum Mail Index
 下面的AppleScript代码将退出Mail，清空SQLite索引，然后重新打开Mail.  在一段时间没有优化的大型电子邮件数据库中，这可以显着提高响应速度和速度.
```applescript
(*
通过吸尘信封索引来加速Mail.app
代码来自：http：//web.archive.org/web/20071008123746/http://www.hawkwings.net/2007/03/03/scripts-to-automate-the-mailapp-envelope-speed-trick/
最初由“pmbuko”改编，由Romulo修改
由Brett Terpstra 2012更新
由MathiasTörnblom2015更新，以支持El Capitan中的V3并仍然保持向后兼容性
由Andrei Miclaus 2017年更新，以支持Sierra的V4
*)

告诉应用程序“邮件”退出
设置os_version来做shell脚本“sw_vers -productVersion”
将mail_version设置为“V2”
考虑数字字符串
    如果“10.10”&lt;= os_version然后将mail_version设置为“V3”
    如果“10.12”&lt;= os_version然后将mail_version设置为“V4”
    如果“10.13”&lt;= os_version然后将mail_version设置为“V5”
    如果“10.14”&lt;= os_version然后将mail_version设置为“V6”
结束考虑

设置sizeBefore做shell脚本“ls -lnah~ / Library / Mail /”＆mail_version＆“/ MailData | grep -E&#39;信封索引$&#39;| awk {&#39;print $ 5&#39;}”
做shell脚本“/ usr / bin / sqlite3~ / Library / Mail /”＆mail_version＆“/ MailData / Envelope \\ Index vacuum”

set sizeAfter做shell脚本“ls -lnah~ / Library / Mail /”＆mail_version＆“/ MailData | grep -E&#39;Envelope Index $&#39;| awk {&#39;print $ 5&#39;}”

display dialog ("Mail index before: " & sizeBefore & return & "Mail index after: " & sizeAfter & return & return & "Enjoy the new speed!")

告诉应用程序“邮件”激活
```

### Safari

#### Change Default Fonts
```bash
默认编写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily Georgia
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFontSize 16
默认编写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily Menlo
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFixedFontSize 14
```

#### Enable Develop Menu and Web Inspector
```bash
默认写com.apple.Safari IncludeInternalDebugMenu -bool true &amp;&amp; \
默认写com.apple.Safari IncludeDevelopMenu -bool true &amp;&amp; \
默认写入com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey -bool true &amp;&amp; \
默认写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled -bool true &amp;&amp; \
defaults write -g WebKitDeveloperExtras -bool true
```

#### Get Current Page Data
其他选项：`get source`，`get text`.
```bash
osascript -e&#39;告诉应用程序“Safari”获取前窗当前选项卡的URL&#39;
```

#### Use Backspace/Delete to Go Back a Page
```bash
## Enable
默认写入com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool YES

## Disable
默认写com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool NO
```

### Sketch

#### Export Compact SVGs
```bash
默认写入com.bohemiancoding.sketch3 exportCompactSVG -bool yes
```

### Skim

#### Turn Off Auto Reload Dialog
删除对话框并默认为自动重新加载.
```bash
defaults write -app Skim SKAutoReloadFileUpdate -boolean true
```
### Terminal

#### Focus Follows Mouse
```bash
## Enable
默认写入com.apple.Terminal FocusFollowsMo​​use -string YES

## Disable
默认写入com.apple.Terminal FocusFollowsMo​​use -string NO
```

### TextEdit

#### Use Plain Text Mode as Default
```bash
默认写入com.apple.TextEdit RichText -int 0
```

### Visual Studio Code

#### Fix VSCodeVim Key Repeat
```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```

## Backup

### Time Machine

#### Change Backup Interval
 这会将间隔更改为30分钟.  整数值是以秒为单位的时间.
```bash
sudo默认写入/System/Library/LaunchDaemons/com.apple.backupd-auto StartInterval -int 1800
```

#### Local Backups
Time Machine是否在Time Machine备份卷不可用时执行本地备份.
```bash
## Status
默认值为/Library/Preferences/com.apple.TimeMachine MobileBackups

## Enable (Default)
sudo tmutil enablelocal

## Disable
sudo tmutil disablelocal
```

 自High Sierra以来，您无法禁用本地快照.  Time Machine现在始终创建本地APFS快照，并使用该快照作为数据源来创建常规备份，而不是使用活动磁盘作为源，就像HFS格式化磁盘一样.

#### Prevent Time Machine from Prompting to Use New Hard Drives as Backup Volume
```bash
sudo defaults write /Library/Preferences/com.apple.TimeMachine DoNotOfferNewDisksForBackup -bool true
```

#### Show Time Machine Logs
这个小脚本将输出Time Machine活动的最后12小时，然后是实时活动.
```bash
#!/bin/sh

filter =&#39;processImagePath包含“backupd”，子系统以“com.apple.TimeMachine”开头

## show the last 12 hours
start =“$（date -j -v-12H +&#39;％Y-％m-％d％H：％M：％S&#39;）”

回声“”
echo“[历史（来自$ start）]”
回声“”

log show --style syslog --info --start“$ start”--predicate“$ filter”

回声“”
回声“[关注]”
回声“”

log stream --style syslog --info --predicate“$ filter”
```

#### Toggle Backup While on Battery
```bash
## Status
sudo defaults read /Library/Preferences/com.apple.TimeMachine RequiresACPower

## Enable (Default)
sudo defaults write /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool true

## Disable
sudo defaults write /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool false
```

#### Verify Backup
 从OS X 10.11开始，Time Machine记录复制到快照中的文件的校验和.  对于早期版本的OS X复制的文件，不会追溯计算校验和.
```bash
sudo tmutil verifychecksums / path / to / backup
```

## Developer

### Vim

#### Compile Sane Vim
通过Homebrew编译MacVim的所有铃声和口哨声，包括覆盖系统Vim.
```bash
brew install macvim --HEAD
```

#### Neovim
通过Homebrew安装现代Vim插件替代品.
```bash
brew安装neovim
```

### Xcode

#### Install Command Line Tools without Xcode
```bash
xcode-select --install
```

#### Remove All Unavailable Simulators
```bash
xcrun simctl删除不可用
```


## Dock

#### Add a Stack with Recent Applications
```bash
 defaults write com.apple.dock persistent-others -array-add&#39;{“tile-data”= {“list-type”= 1;  };  “tile-type”=“recents-tile”;  }&#39;&amp;&amp; \
基拉尔码头
```

#### Add a Nameless Stack Folder and Small Spacer
```bash
 defaults write com.apple.dock persistent-others -array-add&#39;{“tile-data”= {};  “瓷砖式” =“小间隔瓦片”;  }&#39;&amp;&amp; \
基拉尔码头
```

#### Add a Space
```bash
defaults write com.apple.dock persistent-apps -array-add&#39;{“tile-type”=“spacer-tile”;}&#39;&amp;&amp; \
基拉尔码头
```

#### Add a Small Space
```bash
defaults write com.apple.dock persistent-apps -array-add&#39;{“tile-type”=“small-spacer-tile”;}&#39;&amp;&amp; \
基拉尔码头
```

#### Auto Rearrange Spaces Based on Most Recent Use
```bash
## Enable (Default)
默认写com.apple.dock mru-spaces -bool true &amp;&amp; \
基拉尔码头

## Disable
默认写com.apple.dock mru-spaces -bool false &amp;&amp; \
基拉尔码头
```

#### Autohide

```bash
## Enable
默认写com.apple.dock autohide -bool true &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.dock autohide -bool false &amp;&amp; \
基拉尔码头
```

#### Icon Bounce
全局设置当相应的应用程序需要您注意时，Dock图标是否应该反弹.
```bash
## Enable (Default)
默认写com.apple.dock no-bouncing -bool true &amp;&amp; \
基拉尔码头

## Disable
默认写com.apple.dock no-bouncing -bool false &amp;&amp; \
基拉尔码头
```

#### Lock the Dock Size
```bash
## Enable
默认写com.apple.Dock size-immutable -bool yes &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.Dock size-immutable -bool no &amp;&amp; \
基拉尔码头
```

#### Reset Dock
```bash
默认删除com.apple.dock &amp;&amp; \
基拉尔码头
```

#### Resize
 完全调整Dock的身体大小.  要调整大小，将“0”值更改为整数.
```bash
默认写com.apple.dock tilesize -int 0 &amp;&amp; \
基拉尔码头
```

#### Scroll Gestures
 使用触摸板或鼠标滚轮与Dock项目进行交互.  允许您使用向上滚动手势打开堆栈.  在正在运行的应用程序上使用相同的手势调用Exposé/ Mission Control.
```bash
## Enable
defaults write com.apple.dock scroll-to-open -bool true &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.dock滚动到打开-bool false &amp;&amp; \
基拉尔码头
```

#### Set Auto Show/Hide Delay
浮点数定义以毫秒为单位的显示/隐藏延迟.
```bash
默认写com.apple.dock autohide-time-modifier -float 0.4 &amp;&amp; \
默认写com.apple.dock autohide-delay -float 0 &amp;&amp; \
基拉尔码头
```

#### Show Hidden App Icons
```bash
## Enable
默认写com.apple.dock showhidden -bool true &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.dock showhidden -bool false &amp;&amp; \
基拉尔码头
```

#### Show Only Active Applications
```bash
## Enable
默认写com.apple.dock static-only -bool true &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.dock static-only -bool false &amp;&amp; \
基拉尔码头
```

#### Single App Mode
单击Dock中的应用程序图标时，将会出现相应的窗口
在前面，但所有其他应用程序窗口将被隐藏.
```bash
## Enable
默认写com.apple.dock single-app -bool true &amp;&amp; \
基拉尔码头

## Disable (Default)
默认写com.apple.dock single-app -bool false &amp;&amp; \
基拉尔码头
```


## Documents

#### Convert File to HTML
支持的格式是纯文本，富文本（rtf）和Microsoft Word（doc / docx）.
```bash
textutil -convert html file.ext
```


## Files, Disks and Volumes

#### Create an Empty File
创建一个空的10千兆字节的测试文件.
```bash
mkfile 10g / path / to / file
```

#### Disable Sudden Motion Sensor
当你使用SSD时，让这个开启是没用的.
```bash
sudo pmset -a sms 0
```

#### Eject All Mountable Volumes
唯一可行的方法是向Finder发送AppleScript命令.
```bash
osascript -e&#39;告诉应用程序“Finder”弹出（每个可弹出的磁盘都是真的）
```

#### Repair File Permissions
您不必使用“磁盘工具”GUI.
```bash
sudo diskutil repairPermissions /
```
 &gt;从OS X El Capitan开始，系统文件权限将自动受到保护.  不再需要使用“磁盘工具”验证或修复权限.  （[Source](https://support.apple.com/en-us/HT201560))

#### Set Boot Volume
```bash
## Up to Yosemite
祝福 - 装“/ path / to / mounted / volume”--setBoot

## From El Capitan
sudo systemsetup -setstartupdisk / System / Library / CoreServices
```

#### Show All Attached Disks and Partitions
```bash
讨论艺术
```

#### View File System Usage
连续的文件系统访问信息流.
```bash
sudo fs_usage
```
### APFS

 自High Sierra以来可用.  没有中央实用程序，并且使用不一致，因为大多数功能都被卷入`tmutil`.

#### Convert Volume from HFS+ to APFS
```bash
/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert /path / to / file / system
```

#### Create New APFS Filesystem
```bash
/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs / path / to / device
```

#### Create Snapshot
```bash
tmutil localsnapshot
```

#### Delete Snapshot
```bash
tmutil deletelocalsnapshots com.apple.TimeMachine.2018-01-26-044042
````

#### List Snapshots
```bash
tmutil listlocalsnapshots /
```

#### Mount Snapshot
快照是只读的.
```bash
mkdir~ / mnt
/System/Library/Filesystems/apfs.fs/Contents/Resources/mount_apfs -s com.apple.TimeMachine.2018-01-26-044042 /〜/ mnt
```

### Disk Images

```bash
hdiutil create -volname“Volume Name”-srcfolder / path / to / folder -ov diskimage.dmg
```

如果您想加密磁盘映像：
```bash
hdiutil create -encryption -stdinpass -volname“Volume Name”-srcfolder / path / to / folder -ov encrypted.dmg
```

 默认情况下，系统会提示您输入密码.  您可以通过管道密码自动执行此操作：
```bash
 echo -n YourPassword |  hdiutil create -encryption -stdinpass -volname“Volume Name”-srcfolder / path / to / folder -ov encrypted.dmg
```

#### Burn Disk Images to DVD
此命令适用于.iso，.img和.dmg图像.
```bash
hdiutil burn / path / to / image_file
```

#### Disable Disk Image Verification
```bash
默认写入com.apple.frameworks.diskimages skip-verify -bool true &amp;&amp; \
默认写入com.apple.frameworks.diskimages skip-verify-locked -bool true &amp;&amp; \
defaults write com.apple.frameworks.diskimages skip-verify-remote -bool true
```

#### Make Volume OS X Bootable
```bash
bless --folder“/ path / to / mounted / volume / System / Library / CoreServices”--bootinfo --bootefi
```

#### Mount Disk Image
```bash
hdiutil attach /path/to/diskimage.dmg
```

#### Unmount Disk Image
```bash
hdiutil detach / dev / disk2s1
```

#### Write Disk Image to Volume
像磁盘工具“恢复”功能.
```bash
须藤ASR -restore -noverify -source /path/to/diskimage.dmg -target /体积/ VolumeToRestoreTo
```


## Finder

### Desktop

#### Show External Media
外置HD，拇指驱动器等
```bash
## Enable
默认写入com.apple.finder ShowExternalHardDrivesOnDesktop -bool true &amp;&amp; \
killall Finder

## Disable (Default)
默认写入com.apple.finder ShowExternalHardDrivesOnDesktop -bool false &amp;&amp; \
killall Finder
```

#### Show Internal Media
内置HD或SSD.
```bash
## Enable
默认写com.apple.finder ShowHardDrivesOnDesktop -bool true &amp;&amp; \
killall Finder

## Disable (Default)
默认写入com.apple.finder ShowHardDrivesOnDesktop -bool false &amp;&amp; \
killall Finder
```

#### Show Removable Media
CD，DVD，iPod等
```bash
## Enable
默认写入com.apple.finder ShowRemovableMediaOnDesktop -bool true &amp;&amp; \
killall Finder

## Disable (Default)
默认写入com.apple.finder ShowRemovableMediaOnDesktop -bool false &amp;&amp; \
killall Finder
```

#### Show Network Volumes
AFP，SMB，NFS，WebDAV等
```bash
## Enable
默认写入com.apple.finder ShowMountedServersOnDesktop -bool true &amp;&amp; \
killall Finder

## Disable (Default)
默认写入com.apple.finder ShowMountedServersOnDesktop -bool false &amp;&amp; \
killall Finder
```

### Files and Folders

#### Clear All ACLs
```bash
sudo chmod -RN / path / to / folder
```

#### Hide Folder in Finder
```bash
chflags hidden / path / to / folder /
```
#### Show All File Extensions
```bash
defaults write -g AppleShowAllExtensions -bool true
```

#### Show Hidden Files
```bash
## Show All
默认写com.apple.finder AppleShowAllFiles为true

## Restore Default File Visibility
默认写com.apple.finder AppleShowAllFiles为false
```

#### Remove Protected Flag
```bash
sudo chflags -R nouchg / path / to / file /或/ folder
```

#### Show Full Path in Finder Title
```bash
defaults write com.apple.finder _FXShowPosixPathInTitle -bool true
```

#### Unhide User Library Folder
```bash
chflags nohidden~ / Library
```

#### Increase Number of Recent Places
```bash
默认写入-g NSNavRecentPlacesLimit -int 10 &amp;&amp; \
killall Finder
```

### Layout

#### Show "Quit Finder" Menu Item
使用默认快捷键<kbd>Cmd</kbd> + <kbd>Q</kbd>可以查看Finder菜单项“Quit Finder”
```bash
## Enable
默认写入com.apple.finder QuitMenuItem -bool true &amp;&amp; \
killall Finder

## Disable (Default)
默认写com.apple.finder QuitMenuItem -bool false &amp;&amp; \
killall Finder
```

#### Smooth Scrolling
如果您使用较旧的Mac会弄乱动画，这很有用.
```bash
## Disable
默认写入-g NSScrollAnimationEnabled -bool false

## Enable (Default)
defaults write -g NSScrollAnimationEnabled -bool true
```

#### Rubberband Scrolling
```bash
## Disable
默认写入-g NSScrollViewRubberbanding -bool false

## Enable (Default)
默认写入-g NSScrollViewRubberbanding -bool true
```

#### Expand Save Panel by Default
```bash
默认写入-g NSNavPanelExpandedStateForSaveMode -bool true &amp;&amp; \
defaults write -g NSNavPanelExpandedStateForSaveMode2 -bool true
```

#### Desktop Icon Visibility
```bash
## Hide Icons
默认写com.apple.finder CreateDesktop -bool false &amp;&amp; \
killall Finder

## Show Icons (Default)
默认写com.apple.finder CreateDesktop -bool true &amp;&amp; \
killall Finder
```

#### Path Bar
```bash
## Show
默认写入com.apple.finder ShowPathbar -bool true

## Hide (Default)
默认写入com.apple.finder ShowPathbar -bool false
```

#### Scrollbar Visibility
可能的值：`WhenScrolling`，`Automatic`和`Always`.
```bash
默认写入-g AppleShowScrollBars -string“Always”
```

#### Status Bar
```bash
## Show
默认写入com.apple.finder ShowStatusBar -bool true

## Hide (Default)
默认写入com.apple.finder ShowStatusBar -bool false
```

#### Save to Disk by Default
将默认保存目标设置为本地磁盘，而不是iCloud.
```bash
默认写入-g NSDocumentSaveNewDocumentsToCloud -bool false
```

#### Set Current Folder as Default Search Scope
```bash
默认写com.apple.finder FXDefaultSearchScope -string“SCcf”
```

#### Set Default Finder Location to Home Folder
```bash
默认写入com.apple.finder NewWindowTarget -string“PfLo”&amp;&amp; \
defaults write com.apple.finder NewWindowTargetPath -string“file：// $ {HOME}”
```

#### Set Sidebar Icon Size
将大小设置为“中等”.
```bash
默认写入-g NSTableViewDefaultSizeMode -int 2
```

### Metadata Files

#### Disable Creation of Metadata Files on Network Volumes
避免创建`.DS_Store`和AppleDouble文件.
```bash
defaults write com.apple.desktopservices DSDontWriteNetworkStores -bool true
```

#### Disable Creation of Metadata Files on USB Volumes
避免创建`.DS_Store`和AppleDouble文件.
```bash
defaults write com.apple.desktopservices DSDontWriteUSBStores -bool true
```

### Opening Things

#### Change Working Directory to Finder Path
如果打开多个窗口，则会选择最顶层的窗口.
```bash
cd“$（osascript -e&#39;告诉app”Finder“到POSIX路径（插入位置为别名）&#39;）”
```

#### Open URL
```bash
打开https://github.com
```

#### Open File
```bash
打开README.md
```

#### Open Applications
您可以使用`-a`打开应用程序.
```bash
打开-a“Google Chrome”https://github.com
```

#### Open Folder
```bash
open / path / to / folder /
```

#### Open Current Folder
```bash
打开.
```


## Fonts

#### Clear Font Cache for Current User
要清除所有用户的字体缓存，请在此命令前放置`sudo`.
```bash
atsutil databases -removeUser &amp;&amp; \
atsutil服务器-shutdown &amp;&amp; \
atsutil服务器-ping
```

#### Get SF Mono Fonts
 您需要下载并安装Xcode 8 beta才能使用.  之后，它们应该适用于所有应用程序.
```bash
cp -v /Applications/Xcode-beta.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources/Fonts/SFMono-*〜/ Library / Fonts
```

从Sierra开始，它们包含在Terminal.app中.
```bash
cp -v /Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-*〜/ Library / Fonts
```


## Functions

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/functions.md).


## Hardware

### Bluetooth

```bash
## Status
默认值为/Library/Preferences/com.apple.Bluetooth ControllerPowerState

## Enable (Default)
sudo默认写入/Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 1

## Disable
sudo默认写/Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 0 &amp;&amp; \
sudo killall -HUP变蓝了
```

### Harddisks

#### Force Enable Trim
 为非Apple SSD启用修剪.  自Yosemite以来，此命令可用.
```bash
forcetrim
```

### Hardware Information

#### List All Hardware Ports
```bash
networksetup -listallhardwareports
```

#### Remaining Battery Percentage
```bash
 pmset -g batt |  egrep“（[0-9] + \％）.*” -  o  -  colour = auto |  cut -f1 -d&#39;;&#39;
```

#### Remaining Battery Time
```bash
 pmset -g batt |  egrep“（[0-9] + \％）.*” -  o  -  colour = auto |  cut -f3 -d&#39;;&#39;
```

#### Show Connected Device's UDID
```bash
 system_profiler SPUSBDataType |  sed -n -e&#39;/ iPad /，/ Serial / p&#39;-e&#39;/ iPhone /，/ Serial / p&#39;
```

#### Show Current Screen Resolution
```bash
 system_profiler SPDisplaysDataType |  grep决议
```

#### Show CPU Brand String
```bash
sysctl -n machdep.cpu.brand_string
```

### Infrared Receiver

```bash
## Status
默认值为/Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled

## Enable (Default)
defaults write /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 1

## Disable
defaults write /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 0
```

### Power Management

#### Prevent System Sleep
睡眠1小时：
```bash
咖啡因-u -t 3600
```

#### Show All Power Management Settings
```bash
sudo pmset -g
```

#### Put Display to Sleep after 15 Minutes of Inactivity
```bash
sudo pmset showsleep 15
```

#### Put Computer to Sleep after 30 Minutes of Inactivity
```bash
sudo pmset sleep 30
```

#### Check System Sleep Idle Time
```bash
sudo systemsetup -getcomputersleep
```

#### Set System Sleep Idle Time to 60 Minutes
```bash
sudo systemsetup -setcomputersleep 60
```

#### Turn Off System Sleep Completely
```bash
sudo systemsetup -setcomputersleep从不
```

#### Automatic Restart on System Freeze
```bash
sudo systemsetup -setrestartfreeze on
```

#### Chime When Charging
连接MagSafe时播放iOS充电声音.
```bash
## Enable
默认写入com.apple.PowerChime ChimeOnAllHardware -bool true &amp;&amp; \ t
打开/System/Library/CoreServices/PowerChime.app

## Disable (Default)
默认写入com.apple.PowerChime ChimeOnAllHardware -bool false &amp;&amp; \ t
killall PowerChime
```


## Input Devices

### Keyboard

#### Auto-Correct
```bash
## Disable
默认写入-g NSAutomaticSpellingCorrectionEnabled -bool false

## Enable (Default)
defaults write -g NSAutomaticSpellingCorrectionEnabled -bool true

## Show Status
默认值为-g NSAutomaticSpellingCorrectionEnabled
```

#### Full Keyboard Access
在模态对话框中启用Tab.
```bash
## Text boxes and lists only (Default)
默认值写入NSGlobalDomain AppleKeyboardUIMode -int 0

## All controls
默认值写入NSGlobalDomain AppleKeyboardUIMode -in 3
```

#### Key Repeat
禁用默认的“按住”行为.
```bash
## Enable Key Repeat
默认写入-g ApplePressAndHoldEnabled -bool false

## Disable Key Repeat
默认写入-g ApplePressAndHoldEnabled -bool true
```

#### Key Repeat Rate
设定非常快的重复率，调整味道.
```bash
默认值写-g KeyRepeat -int 0.02
```

## Launchpad

#### Reset Launchpad Layout
您需要重新启动`Dock`，因为Launchpad与它绑定在一起.
```bash
## Up to Yosemite
rm~ / Library / Application \ Support / Dock / * .db &amp;&amp; \
基拉尔码头

## From El Capitan
defaults write com.apple.dock ResetLaunchPad -bool true &amp;&amp; \
基拉尔码头
```

## Media

### Audio

#### Convert Audio File to iPhone Ringtone
```bash
afconvert input.mp3 ringtone.m4r -f m4af
```

#### Create Audiobook From Text
使用“Alex”语音，一个简单的UTF-8编码文本文件，用于输入和AAC输出.
```bash
比如-v Alex -f file.txt -o“output.m4a”
```

#### Disable Sound Effects on Boot
```bash
sudo nvram SystemAudioVolume =“”
```

#### Mute Audio Output
```bash
osascript -e&#39;设置音量输出静音为真&#39;
```

#### Set Audio Volume
```bash
osascript -e&#39;设定第4卷&#39;
```

#### Play Audio File
您可以播放QuickTime本机支持的所有音频格式.
```bash
afplay -q 1 filename.mp3
```

#### Speak Text with System Default Voice
```bash
说&#39;你所有的基地都属于我们！&#39;
```

### Video

#### Auto-Play Videos in QuickTime Player
```bash
默认写入com.apple.QuickTimePlayerX MGPlayMovieOnOpen 1
```


## Networking

### Bonjour

#### Bonjour Service
```bash
## Disable
sudo defaults write /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array-add“-NoMulticastAdvertisements”

## Enable (Default)
sudo defaults write /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array“/ usr / sbin / mDNSResponder”“-launchd”
```

### DHCP

#### Renew DHCP Lease
```bash
sudo ipconfig set en0 DHCP
```

#### Show DHCP Info
```bash
ipconfig getpacket en0
```

### DNS

#### Clear DNS Cache
```bash
sudo dscacheutil -flushcache &amp;&amp; \
sudo killall -HUP mDNSResponder
```

### Hostname

#### Set Computer Name/Host Name
```bash
sudo scutil --set ComputerName“newhostname”&amp;&amp; \
sudo scutil --set HostName“newhostname”&amp;&amp; \
sudo scutil --set LocalHostName“newhostname”&amp;&amp; \
sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.smb.server NetBIOSName -string“newhostname”
```

### Network Preferences

#### Network Locations
在“网络”首选项窗格中创建的网络位置之间切换
```bash
## Status
scselect

## Switch Network Location
scselect LocationNameFromStatus
```

#### Set Static IP Address
```bash
networksetup -setmanual“Ethernet”192.168.2.100 255.255.255.0 192.168.2.1
```

### Networking Tools

#### Ping a Host to See Whether It’s Available
```bash
ping -o github.com
```

#### Troubleshoot Routing Problems
```bash
traceroute github.com
```

### SSH

#### Permanently Add Private Key Passphrase to SSH Agent
 &gt;在macOS Sierra之前，ssh会提供一个对话框，询问您的密码，并提供将其存储到钥匙串中的选项.  此UI已在不久前被弃用，已被删除.
>
 &gt;相反，在macOS Sierra中引入了一个新的UseKeychain选项，允许用户指定他们是否希望将密码短语存储在钥匙串中.  默认情况下，此选项在macOS Sierra上启用，这会导致所有密码都存储在钥匙串中.
>
 &gt;这不是预期的默认行为，因此在macOS 10.12.2中已更改.  （[Source](https://developer.apple.com/library/archive/technotes/tn2449/_index.html))
```bash
ssh-add -K / path / to / private_key
```
然后添加到`〜/ .ssh / config`：
```bash
主机server.example.com
    IdentityFile / path / to / private_key
    使用钥匙是
```

#### Remote Login
```bash
## Enable remote login
sudo launchctl load -w /System/Library/LaunchDaemons/ssh.plist

## Disable remote login
sudo launchctl unload -w /System/Library/LaunchDaemons/ssh.plist
```

### TCP/IP

#### Show Application Using a Certain Port
这将输出当前使用端口80的所有应用程序
```bash
sudo lsof -i：80
```

#### Show External IP Address
如果您的ISP不替换DNS请求（它不应该），则可以正常工作.
```bash
挖掘+短信myip.opendns.com @ resolver1.opendns.com
```
适用于所有网络的替代方案.
```bash
curl -s https://api.ipify.org&amp;&amp; echo
```

#### Show Network Interface Information
`scutil`命令的未记录标志.
```bash
scutil --nwi
```

### TFTP

#### Start Native TFTP Daemon
文件将从`/ private / tftpboot`提供.
```bash
sudo launchctl load -F /System/Library/LaunchDaemons/tftp.plist&amp;&amp; \
sudo launchctl start com.apple.tftpd
```

### Wi-Fi

#### Join a Wi-Fi Network
```bash
networksetup -setairportnetwork en0 WIFI_SSID WIFI_PASSWORD
```

#### Scan Available Access Points
创建机场命令的符号链接以便于访问：
```bash
sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport / usr / local / bin / airport
```
运行无线扫描：
```bash
机场-s
```

#### Show Current SSID
```bash
 /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -I |  awk&#39;/ SSID / {print substr（$ 0，index（$ 0，$ 2））}&#39;
```

#### Show Local IP Address
```bash
ipconfig getifaddr en0
```

#### Show Wi-Fi Connection History
```bash
 默认值为/Library/Preferences/SystemConfiguration/com.apple.airport.preferences |  grep LastConnected -A 7
```

#### Show Wi-Fi Network Passwords
使用您希望从中查询密码的访问点的SSID来交换SSID.
```bash
security find-generic-password -D“AirPort网络密码”-a“SSID”-gw
```

#### Turn on Wi-Fi Adapter
```bash
networksetup -setairportpower en0 on
```

## Package Managers

- [Fink](http://www.finkproject.org)   - 达尔文的Unix开源软件的全部世界.  有点过时了.
- [Homebrew](https://brew.sh) -  OS X缺少的包管理器.最受欢迎的选择.
- [MacPorts](https://www.macports.org)   - 编译，安装和升级命令行，X11或基于Aqua的开源软件.  非常干净，这就是我使用的.

### Homebrew

#### Full Uninstall

```bash
ruby -e“$（curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall）”
```


## Printing

#### Clear Print Queue
```bash
取消-a  - 
```

#### Expand Print Panel by Default
```bash
默认写入-g PMPrintingExpandedStateForPrint -bool true &amp;&amp; \
defaults write -g PMPrintingExpandedStateForPrint2 -bool true
```

#### Quit Printer App After Print Jobs Complete
```bash
defaults write com.apple.print.PrintingPrefs“Quit When Finished”-bool true
```


## Security

### Application Firewall

#### Firewall Service
```bash
## Show Status
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --getglobalstate

## Enable
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --setglobalstate on

## Disable (Default)
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --setglobalstate off
```

#### Add Application to Firewall
```bash
sudo / usr / libexec / ApplicationFirewall / socketfilterfw --add / path / to / file
```

### Gatekeeper

#### Add Gatekeeper Exception
```bash
spctl --add /path/to/Application.app
```

#### Remove Gatekeeper Exception
```bash
spctl --remove /path/to/Application.app
```

#### Manage Gatekeeper
```bash
## Status
spctl --status

## Enable (Default)
sudo spctl --master-enable

## Disable
sudo spctl --master-disable
```

### Passwords

#### Generate Secure Password and Copy to Clipboard
```bash
 LC_ALL = C tr -dc“[：alnum：]”&lt;/ dev / urandom |  头-c 20 |  pbcopy
```

### Physical Access

#### Launch Screen Saver

```bash
## Up to Sierra
打开/System/Library/Frameworks/ScreenSaver.framework/Versions/A/Resources/ScreenSaverEngine.app

## From High Sierra
/System/Library/CoreServices/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine
```


#### Lock Screen
```bash
/ System / Library / CoreServices / Menu \ Extras / User.menu / Contents / Resources / CGSession -suspend
```

#### Screensaver Immediate Lock
```bash
## Status
默认读取com.apple.screensaver askForPasswordDelay

## Enable (Default)
默认写入com.apple.screensaver askForPasswordDelay -int 0

## Disable (Integer = lock delay in seconds)
默认写入com.apple.screensaver askForPasswordDelay -int 10
```

#### Screensaver Password
```bash
## Status
默认读取com.apple.screensaver askForPassword

## Enable
默认写入com.apple.screensaver askForPassword -int 1

## Disable (Default)
默认写com.apple.screensaver askForPassword -int 0
```

### Wiping Data

 注意：在10.9之后，“srm”命令似乎已在MacOS上删除.  有一个注释 [Apple support page](https://support.apple.com/en-us/HT201949) 暗示为什么：
 &gt;使用SSD驱动器时，磁盘工具中不提供安全擦除和擦除可用空间.  SSD驱动器不需要这些选项，因为标准擦除使得难以从SSD恢复数据.

#### Securely Remove File
```bash
srm / path / to / file
```

#### Securely Remove Folder
```bash
srm -r / path / to / folder /
```

#### Securely Remove Path (Force)
```bash
srm -rf / path / to / complete / destruction
```


## Search

### Find

#### Recursively Delete .DS_Store Files
```bash
 找 .  -type f -name&#39;* .DS_Store&#39;-ls -delete
```

### Locate

#### Build Locate Database
```bash
sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist
```

#### Search via Locate
`-i`修饰符使搜索大小写不敏感.
```bash
找到-i * .jpg
```


## System

### AirDrop

```bash
## Enable AirDrop over Ethernet and on Unsupported Macs
defaults write com.apple.NetworkBrowser BrowseAllInterfaces -bool true

## Enable (Default)
默认删除com.apple.NetworkBrowser DisableAirDrop

## Disable
默认写入com.apple.NetworkBrowser DisableAirDrop -bool YES
```

### AppleScript

#### Execute AppleScript
```bash
osascript /path/to/script.scpt
```

### Basics

#### Compare Two Folders
```bash
diff -qr / path / to / folder1 / path / to / folder2
```

#### Copy Large File with Progress
确保安装了`pv`并用适当的写设备或文件替换`/ dev / rdisk2`.
```bash
 FILE = / path / to / file.iso pv -s $（du -h $ FILE | awk&#39;/.*/ {print $ 1}&#39;）$ FILE |  sudo dd = / dev / rdisk2 bs = 1m
```

#### Restore Sane Shell
如果您的shell会话疯狂（某些脚本或应用程序将其变成乱码）.
```bash
stty sane
```

#### Restart
```bash
sudo重启
```

#### Shutdown
```bash
sudo poweroff
```

#### Show Build Number of OS
```bash
sw_vers
```

#### Uptime
你上次重启多久了.
```bash
uptime
```

### Clipboard

#### Copy data to Clipboard
```bash
 cat whatever.txt |  pbcopy
```

#### Convert Clipboard to Plain Text
```bash
 pbpaste |  textutil -convert txt -stdin -stdout -encoding 30 |  pbcopy
```

```bash
 pbpaste |  展开|  pbcopy
```

#### Copy data from Clipboard
```bash
pbpaste&gt; whatever.txt
```

```bash
 pbpaste |  排序|  uniq |  pbcopy
```

### FileVault

#### Automatically Unlock FileVault on Restart
 如果在当前卷上启用了FileVault，则会重新启动系统，从而绕过初始解锁.  该命令可能无法在所有系统上运行.
```bash
sudo fdesetup authrestart
```

#### FileVault Service
```bash
## Status
sudo fdesetup状态

## Enable
sudo fdesetup启用

## Disable (Default)
sudo fdesetup disable
```

### Information/Reports

#### Generate Advanced System and Performance Report
```bash
sudo sysdiagnose -f~ / Desktop /
```

### Install OS

#### Create Bootable Installer
```bash
## Mojave
sudo / Applications / Install \ macOS \ Mojave.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --nointeraction --downloadassets

## High Sierra
sudo / Applications / Install \ macOS \ High \ Sierra.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ macOS \ High \ Sierra.app

## Sierra
sudo / Applications / Install \ macOS \ Sierra.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ macOS \ Sierra.app

## El Capitan
sudo / Applications / Install \ OS \ X \ El \ Capitan.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ OS \ X \ El \ Capitan.app

## Yosemite
sudo / Applications / Install \ OS \ X \ Yosemite.app/Contents/Resources/createinstallmedia --volume / Volumes / USB --applicationpath / Applications / Install \ OS \ X \ Yosemite.app
```

*要在删除驱动器之前进行确认，请从命令中删除`--nointeraction`.
 *可选的`--downloadassets`标志是Mojave中的新标志.  它会下载安装过程中可能需要的资产，例如更新.
*自从Mojave以来，不推荐使用`--applicationpath`标志，如果使用的话会抛出错误.

### Kernel Extensions

#### Display Status of Loaded Kernel Extensions
```bash
sudo kextstat -l
```

#### Load Kernel Extension
```bash
sudo kextload -b com.apple.driver.ExampleBundle
```

#### Unload Kernel Extensions
```bash
sudo kextunload -b com.apple.driver.ExampleBundle
```

### LaunchAgents

请参阅 [this file](https://github.com/herrbischoff/awesome-macos-command-line/blob/master/launchagents.md).


### LaunchServices

#### Rebuild LaunchServices Database
 为了独立于OS X版本，这依赖于`locate`来查找`lsregister`.  如果你还没有建立`locate`数据库， [do it](#build-locate-database).
```bash
sudo $（找到lsregister）-kill -seed -r
```

### Login Window

#### Set Login Window Text
```bash
sudo默认写/Library/Preferences/com.apple.loginwindow LoginwindowText“你的文字”
```

### Memory Management

#### Purge memory cache
```bash
sudo purge
```

#### Show Memory Statistics
```bash
## One time
vm_stat

## Table of data, repeat 10 times total, 1 second wait between each poll
vm_stat -c 10 1
```

### Notification Center

#### Notification Center Service
```bash
## Disable
launchctl unload -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist&amp;&amp; \
killall -9 NotificationCenter

## Enable (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist
```

### QuickLook

#### Preview via QuickLook
```bash
qlmanage -p / path / to / file
```

### Remote Apple Events
```bash
## Status
sudo systemsetup -getremoteappleevents

## Enable
sudo systemsetup -setremoteappleevents on

## Disable (Default)
sudo systemsetup -setremoteappleevents off
```

### Root User

```bash
## Enable
dsenableroot

## Disable
dsenableroot -d
```

### Safe Mode Boot

```bash
## Status
nvram boot-args

## Enable
sudo nvram boot-args =“ -  x”

## Disable
sudo nvram boot-args =“”
```

### Screenshots

#### Take Delayed Screenshot
3秒后将屏幕截图设为JPEG，并在预览中显示.
```bash
screencapture -T 3 -t jpg -P delayedpic.jpg
```

#### Save Screenshots to Given Location
Sets location to `~/Desktop`.
```bash
默认写com.apple.screencapture位置〜/桌面&amp;&amp; \
killall SystemUIServer
```

#### Save Screenshots in Given Format
 将格式设置为`png`.  其他选项是`bmp`，`gif`，`jpg`，`jpeg`，`pdf`，`tiff`.
```bash
默认写com.apple.screencapture类型-string“png”
```

#### Disable Shadow in Screenshots
```bash
默认写入com.apple.screencapture disable-shadow -bool true &amp;&amp; \
killall SystemUIServer
```

#### Set Default Screenshot Name
日期和时间保持不变.
```bash
默认写com.apple.screencapture名称“示例名称”&amp;&amp; \
killall SystemUIServer
```

### Software Installation

#### Install PKG
```bash
installer -pkg /path/to/installer.pkg -target /
```

### Software Update

#### Install All Available Software Updates
```bash
sudo softwareupdate -ia
```

#### Set Software Update Check Interval
设置为每日检查而不是每周检查.
```bash
defaults write com.apple.SoftwareUpdate ScheduleFrequency -int 1
```

#### Show Available Software Updates
```bash
sudo softwareupdate -l
```

#### Set Software Update Server
 这应仅用于测试目的或非托管客户端.  要在网络范围内使用，请正确设置DNS [Apple SUS service](http://krypted.com/mac-security/using-the-software-update-service-on-mountain-lion-server/)  并通过OpenDirectory绑定您的客户端.  或者，使用 [Reposado](https://github.com/wdas/reposado) 与正确的网络DNS设置一起使分辨率透明. [Margarita](https://github.com/jessepeterson/margarita) 也很好看.
```bash
## Use own SUS
sudo defaults write /Library/Preferences/com.apple.SoftwareUpdate CatalogURL http://su.example.com:8088/index.sucatalog

## Reset to Apple SUS
sudo默认删除/Library/Preferences/com.apple.SoftwareUpdate CatalogURL
```

### Software Version

#### Show System Software Version
```bash
sw_vers -productVersion
```

### Spotlight

#### Spotlight Indexing
```bash
## Disable
mdutil -i off -d / path / to / volume

## Enable (Default)
mdutil -i on / path / to / volume
```

#### Erase Spotlight Index and Rebuild
```bash
mdutil -E / path / to / volume
```

#### Search via Spotlight
```bash
mdfind -name&#39;searchterm&#39;
```

#### Show Spotlight Indexed Metadata
```bash
mdls / path / to / file
```

### System Integrity Protection

#### Disable System Integrity Protection
按住<kbd>Cmd</kbd> + <kbd>R</kbd>重新启动，打开终端应用程序并输入：
```bash
csrutil disable &amp;&amp; reboot
```

#### Enable System Integrity Protection
按住<kbd>Cmd</kbd> + <kbd>R</kbd>重新启动，打开终端应用程序并输入：
```bash
csrutil enable &amp;&amp; reboot
```

### Date and Time

#### List Available Timezones
```bash
sudo systemsetup -listtimezones
```

#### Set Timezone
```bash
sudo systemsetup -settimezone欧洲/柏林
```

#### Set Clock Using Network Time
```bash
## Status
sudo systemsetup getusingnetworktime

## Enable (Default)
sudo systemsetup setusingnetworktime on

## Disable
sudo systemsetup setusingnetworktime off
```



## Terminal

#### Ring Terminal Bell
敲响终端铃（如果已启用）并在其上放置徽章.
```bash
tput bel
```

### Alternative Terminals

- [Alacritty](https://github.com/jwilm/alacritty) - 跨平台，GPU加速的终端仿真器.
- [iTerm2](https://iterm2.com) - 一个更好的Terminal.app.
- [kitty](https://sw.kovidgoyal.net/kitty/) - 现代GPU加速终端仿真器.

### Shells

#### Bash
安装最新版本并设置为当前用户的默认shell：
```bash
brew安装bash &amp;&amp; \
 echo $（brew --prefix）/ bin / bash |  sudo tee -a / etc / shells &amp;&amp; \
chsh -s $（brew --prefix）/ bin / bash
```

- [Homepage](https://www.gnu.org/software/bash/) -  OS X和大多数其他基于Unix的操作系统的默认shell.
- [Bash-it](https://github.com/Bash-it/bash-it) - 社区Bash框架，就像Oh My Zsh for Bash一样.

#### fish
安装最新版本并设置为当前用户的默认shell：
```bash
brew安装鱼&amp;&amp; \
 echo $（brew --prefix）/ bin / fish |  sudo tee -a / etc / shells &amp;&amp; \
chsh -s $（brew --prefix）/ bin / fish
```

- [Homepage](http://fishshell.com) - 智能且用户友好的命令行
适用于OS X，Linux和其他系列的shell.
- [The Fishshell Framework](https://github.com/oh-my-fish/oh-my-fish) - 提供核心基础结构，允许您安装扩展或修改shell外观的软件包.
- [Installation & Configuration Tutorial](https://github.com/ellerbrock/fish-shell-setup-osx) - 如何在OS X上使用Fisherman，Powerline字体，iTerm2和Budspencer主题设置鱼壳.

#### Zsh
安装最新版本并设置为当前用户的默认shell：
```bash
brew安装zsh &amp;&amp; \
sudo sh -c 'echo $(brew --prefix)/bin/zsh >> /etc/shells' && \
chsh -s $（brew --prefix）/ bin / zsh
```

- [Homepage](http://www.zsh.org) -  Zsh是一个专为交互式使用而设计的shell，尽管它也是一种功能强大的脚本语言.
- [Oh My Zsh](http://ohmyz.sh) - 用于管理Zsh配置的开源社区驱动框架.
- [Prezto](https://github.com/sorin-ionescu/prezto)   - 快速的Zsh框架.  使用合理的默认值，别名，函数，自动完成和提示主题来丰富命令行界面环境.
- [zgen](https://github.com/tarjoilija/zgen)   - 另一个用于管理zsh配置的开源框架.  Zgen将加载兼容oh-my-zsh的插件和主题，并且具有更快速并自动克隆配置中使用的任何插件的优点.

### Terminal Fonts

- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) - 一系列四种固定宽度字体，设计时考虑了编码.
- [Codeface](https://github.com/chrissimpkins/codeface) - 开发人员的图库和等宽字体库.
- [DejaVu Sans Mono](https://dejavu-fonts.github.io/) - 基于Vera字体的字体系列.
- [Hack](http://sourcefoundry.org/hack/) -  Hack手工修饰，光学平衡，成为您的首选代码.
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) - 等宽字体，专为代码清单等设计.
- [Input](http://input.fontbureau.com) - A flexible system of fonts designed specifically for code.
- [Meslo](https://github.com/andreberg/Meslo-Font) -  Apple的Menlo字体的定制版本.
- [Operator Mono](https://www.typography.com/fonts/operator/overview/) - 一种令人惊讶的可用替代品，采用等宽字体（商业）.
- [Powerline Fonts](https://github.com/powerline/fonts) -  Powerline插件的修补字体回购.
- [Source Code Pro](https://adobe-fonts.github.io/source-code-pro/) - 用于用户界面和编码环境的等宽字体系列.


## Glossary

### Mac OS X, OS X, and macOS Version Information

 版本|  代号|  发布日期|  最新版本
-------------------------- | ------------------ | ------------------ | -------------------------------------
 Rhapsody Developer Release |  Grail1Z4 / Titan1U |  1997年8月31日|  DR2（1998年5月14日）
 Mac OS X Server 1.0 |  赫拉|  1999年3月16日|  1.2v3（2000年10月27日）
 Mac OS X开发人员预览版|  不适用|  1999年3月16日|  DP4（2000年4月5日）
 Mac OS X Public Beta |  科迪亚克|  2000年9月13日|  N / A
 Mac OS X 10.0 |  猎豹|  2001年3月24日|  10.4.4（2001年6月22日）
 Mac OS X 10.1 |  彪马|  2001年9月25日|  10.1.5（2002年6月6日）
 Mac OS X 10.2 |  捷豹|  2002年8月24日|  10.2.8（2003年10月3日）
 Mac OS X 10.3 |  豹|  2003年10月24日|  10.3.9（2005年4月15日）
 Mac OS X 10.4 |  老虎|  2005年4月29日|  10.10.11（2007年11月14日）
 Mac OS X 10.5 |  豹子|  2007年10月26日|  10.5.8（2009年8月5日）
 Mac OS X 10.6 |  雪豹|  2009年8月28日|  10.6.8 v1.1（2011年7月25日）
 Mac OS X 10.7 |  狮子|  2011年7月20日|  10.7.5（2012年9月19日）
 OS X 10.8 |  山狮|  2012年7月25日|  10.8.5（12F45）（2013年10月3日）
 OS X 10.9 |  小牛队|  2013年10月22日|  10.9.5（13F1112）（2014年9月18日）
 OS X 10.10 |  优胜美地|  2014年10月16日|  10.10.5（14F27）（2015年8月13日）
 OS X 10.11 |  El Capitan |  2015年9月30日|  10.11.6（15G31）（2016年7月18日）
 macOS 10.12 |  Sierra |  2016年9月20日|  10.12.6（16G29）（2017年7月19日）
 macOS 10.13 |  高山|  2017年9月25日|  10.13.6（17G65）（2018年7月9日）
 macOS 10.14 |  莫哈韦|  2018年9月24日|  10.14（18A391）（2018年9月24日）
 macOS 10.15 |  Catalina |  tba |  TBA


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /><br />本作品采用<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">知识共享署名 - 相同方式共享4.0国际许可协议授权</a> .
