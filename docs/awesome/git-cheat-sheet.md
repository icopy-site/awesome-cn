<div class="github-widget" data-repo="arslanbilal/git-cheat-sheet"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
Git 和 Git 流程备忘单 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============
<hr>
<p align="center">
    <img alt="Git" src="https://raw.githubusercontent.com/arslanbilal/git-cheat-sheet/master/./Img/git-logo.png" height="190" width="455">
</p>
<hr>

## Other Available Languages:

1. [Arabic Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-ar.md)
2. [Brazilian Portuguese Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-pt_BR.md)
3. [Chinese Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-zh.md)
4. [German Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-de.md)
5. [Greek Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-el.md)
6. [Hindi Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-hi.md)
7. [Korean Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-ko.md)
8. [Polish Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-pl.md)
9. [Spanish Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-es.md)
10. [Turkish Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-tr.md)
11. [Bengali Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/./other-sheets/git-cheat-sheet-bn.md)

Git 备忘单让你不用背诵所有命令.

自由贡献，更新语法错误. 您也可以自由添加您的语言文件.

<hr>

Git 备忘单
===============
### Index


<hr>

## Setup

##### Show current configuration:
```
$ git config --list
```
##### Show repository configuration:
```
$ git config --local --list
```

##### Show global configuration:
```
$ git config --global --list
```

##### Show system configuration:
```
$ git config --system --list
```

##### Set a name that is identifiable for credit when review version history:
```
$ git config --global user.name &quot;[firstname lastname]&quot;
```

##### Set an email address that will be associated with each history marker:
```
$ git config --global user.email &quot;[valid-email]&quot;
```

##### Set automatic command line coloring for Git for easy reviewing:
```
$ git config --global color.ui 自动
```

##### Set global editor for commit
```
$ git config --global core.editor vi
```

<hr>

## Configuration Files

##### Repository specific configuration file [--local]:
```
<repo>/.git/config
```

##### User-specific configuration file [--global]:
```
~/.gitconfig
```

##### System-wide configuration file [--system]:
```
/etc/gitconfig
```

<hr>

## Create

##### Clone an existing repository:

有两种方法：

通过 SSH

```
$ git clone ssh://user@domain.com/repo.git
```

通过 HTTP

```
$ git clone http://domain.com/user/repo.git
```

##### Create a new local repository in the current directory:
```
$ git热
```

##### Create a new local repository in a specific directory:
```
$ git热<directory>
```

<hr>

## Local Changes

##### Changes in working directory:
```
$ 混帐状态
```

##### Changes to tracked files:
```
$混帐差异
```

##### See changes/difference of a specific file:
```
$混帐差异<file>
```

##### Add all current changes to the next commit:
```
$ 混帐添加.
```

##### Add some changes in &lt;file&gt; to the next commit:
```
$ git添加-p<file>
```

##### Add only the mentioned files to the next commit:
```
$ 混帐添加<filename1><filename2>
```

##### Commit all local changes in tracked files:
```
$ git commit -a
```

##### Commit previously staged changes:
```
$ git提交
```

##### Commit with message:
```
$ git commit -m &#39;这里的信息&#39;
```

##### Commit skipping the staging area and adding message:
```
$ git commit -am &#39;这里的信息&#39;
```

##### Commit to some previous date:
```
 $ git commit --date=&quot;`date --date=&#39;n 天前&#39;`&quot; -am&quot;<Commit Message Here>  &quot;
```

##### Change last commit:<br>
<em><sub>不要修改已发布的提交！</sub></em>

```
$ git commit -a --amend
```

##### Amend with last commit but use the previous commit log message
<em><sub>不要修改已发布的提交！</sub></em>

```shell
$ git commit --amend --no-edit
```

##### Change committer date of last commit:
```
GIT_COMMITTER_DATE=&quot;日期&quot; git commit --amend
```

##### Change Author date of last commit:
```shell
$ git commit --amend --date=&quot;日期&quot;
```

##### Move uncommitted changes from current branch to some other branch:<br>
```
$ git藏匿
$ git checkout 分支2
$ git stash pop
```

##### Restore stashed changes back to current branch:
```shell
$ git stash 适用
```

#### Restore particular stash back to current branch:
- *{stash_number}* 可以从 `git stash list` 获得

```shell
$ git stash apply stash@{stash_number}
```

##### Remove the last set of stashed changes:
```
$ git stash drop
```

<hr>

## Search

##### A text search on all files in the directory:
```
$ git grep &quot;你好&quot;
```

##### In any version of a text search:
```
$ git grep &quot;你好&quot; v2.5
```

##### Show commits that introduced a specific keyword
```
$ git log -S &#39;关键字&#39;
```

##### Show commits that introduced a specific keyword (using a regular expression)
```
$ git log -S &#39;关键字&#39; --pickaxe-regex
```

<hr>

## Commit History

##### Show all commits, starting with newest (it'll show the hash, author information, date of commit and title of the commit):
```
$ 混帐日志
```

##### Show all the commits(it'll show just the commit hash and the commit message):
```
$ git log --oneline
```

##### Show all commits of a specific user:
```
$ git log --author=&quot;用户名&quot;
```

##### Show changes over time for a specific file:
```
$ 混帐日志 -p<file>
```

##### Display commits that are present only in remote/branch in right side
```
 $ git log --oneline<origin/master>  ..<remote/master>  - 左右
```

##### Who changed, what and when in &lt;file&gt;:
```
$ 混帐责备<file>
```

##### Show Reference log:
```
$ git reflog 显示
```

##### Delete Reference log:
```
$ git reflog 删除
```
<hr>

## Move / Rename

##### Rename a file:

将 Index.txt 重命名为 Index.html

```
$ git mv Index.txt Index.html
```

<hr>

## Branches & Tags

##### List all local branches:
```
$ git 分支
```

#### List local/remote branches
```
$ git 分支 -a
```

##### List all remote branches:
```
$ git 分支 -r
```

##### Switch HEAD branch:
```
$ git结帐<branch>
```

##### Checkout single file from different branch
```
 $ git结帐<branch> --<filename>
```

##### Create and switch new branch:
```
$ git结帐-b<branch>
```

##### Switch to the previous branch, without saying the name explicitly:
```
$ git结帐-
```

##### Create a new branch from an exiting branch and switch to new branch:
```
$ git结帐-b<new_branch><existing_branch>
```


#### Checkout and create a new branch from existing commit
```
 $ git结帐<commit-hash> -b<new_branch_name>
```


##### Create a new branch based on your current HEAD:
```
$ git 分支<new-branch>
```

##### Create a new tracking branch based on a remote branch:
```
$ git 分支 --track<new-branch><remote-branch>
```

##### Delete a local branch:
```
$ git 分支 -d<branch>
```

##### Rename current branch to new branch name
```shell
$ git 分支 -m<new_branch_name>
```

##### Force delete a local branch:
<em><sub>您将丢失未合并的更改！</sub></em>

```
$ git 分支 -D<branch>
```
##### Apply specific commit from another branch:
```
git 樱桃采摘<commit hash>
```

##### Mark `HEAD` with a tag:
```
$ git标签<tag-name>
```

##### Mark `HEAD` with a tag and open the editor to include a message:
```
$ git标签-a<tag-name>
```

##### Mark `HEAD` with a tag that includes a message:
```
 $ git标签<tag-name> -am &#39;在这里留言&#39;
```

##### List all tags:
```
$ git标签
```

##### List all tags with their messages (tag message or commit message if tag has no message):
```
$ git标签-n
```

<hr>

## Update & Publish

##### List all current configured remotes:
```
$ git远程-v
```

##### Show information about a remote:
```
$ git 远程显示<remote>
```

##### Add new remote repository, named &lt;remote&gt;:
```
$ git远程添加<remote><url>
```

##### Rename a remote repository, from &lt;remote&gt; to &lt;new_remote&gt;:
```
$ git远程重命名<remote><new_remote>
```

##### Remove a remote:
```
$ git远程rm<remote>
```

<em><sub>注意： git remote rm 不会从服务器中删除远程存储库.</sub></em> <em><sub>它只是从本地存储库中删除远程及其引用.</sub></em>

##### Download all changes from &lt;remote&gt;, but don't integrate into HEAD:
```
$ git 获取<remote>
```

##### Download changes and directly merge/integrate into HEAD:
```
$ git 远程拉取<remote><url>
```

##### Get all changes from HEAD to local repository:
```
$ git pull 起源大师
```

##### Get all changes from HEAD to local repository without a merge:
```
$ git pull --rebase<remote><branch>
```

##### Publish local changes on a remote:
```
$ git推送<remote><branch>
```

##### Delete a branch on the remote:
```
 $ git推送<remote> ：<branch>  （从 Git v1.5.0 开始）
```
OR
```
 $ git推送<remote> - 删除<branch> （从 Git v1.7.0 开始）
```

##### Publish your tags:
```
$ git push --tags
```
<hr>

#### Configure the merge tool globally to meld (editor)
```bash
$ git config --global merge.tool 融合
```

##### Use your configured merge tool to solve conflicts:
```
$ git 合并工具
```

## Merge & Rebase

##### Merge branch into your current HEAD:
```
$ git 合并<branch>
```

#### List merged branches
```
$ git 分支 --merged
```

##### Rebase your current HEAD onto &lt;branch&gt;:<br>
<em><sub>不要变基已发布的提交！</sub></em>

```
$ 混帐狐狸<branch>
```

##### Abort a rebase:
```
$ git rebase --abort
```

##### Continue a rebase after resolving conflicts:
```
$ git rebase -- 继续
```

##### Use your editor to manually solve conflicts and (after resolving) mark file as resolved:
```
$ 混帐添加<resolved-file>
```

```
$ git rm<resolved-file>
```

##### Squashing commits:
```
$ git rebase -i<commit-just-before-first>
```

现在替换这个，

```
挑选<commit_id>
挑选<commit_id2>
挑选<commit_id3>
```

对此，

```
挑选<commit_id>
壁球<commit_id2>
壁球<commit_id3>
```
<hr>

## Undo

##### Discard all local changes in your working directory:
```
$ git reset --hard HEAD
```

##### Get all the files out of the staging area(i.e. undo the last `git add`):
```
$ git重置头
```

##### Discard local changes in a specific file:
```
$ git checkout 头<file>
```

##### Revert a commit (by producing a new commit with contrary changes):
```
$ git 还原<commit>
```

##### Reset your HEAD pointer to a previous commit and discard all changes since then:
```
$ git reset --hard<commit>
```

##### Reset your HEAD pointer to a remote branch current state.
```
 $ git reset --hard<remote/branch> 例如，upstream/master、origin/my-feature
```

##### Reset your HEAD pointer to a previous commit and preserve all changes as unstaged changes:
```
$ git 重置<commit>
```

##### Reset your HEAD pointer to a previous commit and preserve uncommitted local changes:
```
$ git reset --keep<commit>
```

##### Remove files that were accidentally committed before they were added to .gitignore
```
$ git rm -r --cached .
$ 混帐添加.
$ git commit -m &quot;删除 xyz 文件&quot;
```
<hr>

## Git-Flow
Improved [Git-flow](https://github.com/petervanderdoes/gitflow-avh)

### Index

<hr>

### Setup
###### You need a working git installation as prerequisite. Git flow works on OSX, Linux and Windows.

##### OSX Homebrew:
```
$ brew install git-flow-avh
```

##### OSX Macports:
```
$ 端口安装 git-flow
```

##### Linux (Debian-based):
```
$ sudo apt-get 安装 git-flow
```

##### Windows (Cygwin):
###### You need wget and util-linux to install git-flow.
```bash
 $ wget -q -O - --no-check-certificate https://raw.githubusercontent.com/petervanderdoes/gitflow/develop/contrib/gitflow-installer.sh install<state>  | 重击
```
<hr>

### Getting Started
###### Git flow needs to be initialized in order to customize your project setup. Start using git-flow by initializing it inside an existing git repository:
##### Initialize:
###### You'll have to answer a few questions regarding the naming conventions for your branches. It's recommended to use the default values.
```shell
git流初始化
```
OR
###### To use default
```shell
git流初始化-d
```
<hr>

### Features
###### Develop new features for upcoming releases. Typically exist in developers repos only.
##### Start a new feature:
###### This action creates a new feature branch based on 'develop' and switches to it.
```
git flow 功能启动 MYFEATURE
```

##### Finish up a feature:
###### Finish the development of a feature. This action performs the following:
###### 1) Merged MYFEATURE into 'develop'.
###### 2) Removes the feature branch.
###### 3) Switches back to 'develop' branch
```
git flow 功能完成 MYFEATURE
```

##### Publish a feature:
###### Are you developing a feature in collaboration? Publish a feature to the remote server so it can be used by other users.
```
git flow 功能发布 MYFEATURE
```

##### Getting a published feature:
###### Get a feature published by another user.
```
git flow feature pull origin MYFEATURE
```

##### Tracking a origin feature:
###### You can track a feature on origin by using
```
git flow 功能跟踪 MYFEATURE
```
<hr>

### Make a Release
###### Support preparation of a new production release. Allow for minor bug fixes and preparing meta-data for a release

##### Start a release:
###### To start a release, use the git flow release command. It creates a release branch created from the 'develop' branch. You can optionally supply a [BASE] commit sha-1 hash to start the release from. The commit must be on the 'develop' branch.
```
git flow release start 发布 [基础]
```
###### It's wise to publish the release branch after creating it to allow release commits by other developers. Do it similar to feature publishing with the command:
```
git flow 发布发布发布
```
###### (You can track a remote release with the: ```git flow release track RELEASE``` command)

##### Finish up a release:
###### Finishing a release is one of the big steps in git branching. It performs several actions:
###### 1) Merges the release branch back into 'master'
###### 2) Tags the release with its name
###### 3) Back-merges the release into 'develop'
###### 4) Removes the release branch
```
git flow 发布完成发布
```
###### Don't forget to push your tags with ```git push --tags```

<hr>

### Hotfixes
###### Hotfixes arise from the necessity to act immediately upon an undesired state of a live production version. May be branched off from the corresponding tag on the master branch that marks the production version.

##### Git flow hotfix start:
###### Like the other git flow commands, a hotfix is started with
```
$ git flow hotfix start VERSION [BASENAME]
```
###### The version argument hereby marks the new hotfix release name. Optionally you can specify a basename to start from.

##### Finish a hotfix:
###### By finishing a hotfix it gets merged back into develop and master. Additionally the master merge is tagged with the hotfix version
```
git flow 修补程序完成版本
```
<hr>

### Commands
<p align="center">
    <img alt="Git" src="https://raw.githubusercontent.com/arslanbilal/git-cheat-sheet/master/./Img/git-flow-commands.png" height="270" width="460">
</p>
<hr>

### Git flow schema

<p align="center">
    <img alt="Git" src="https://raw.githubusercontent.com/arslanbilal/git-cheat-sheet/master/Img/git-flow-commands-without-flow.png">
</p>
<hr>
