<div class="github-widget" data-repo="arslanbilal/git-cheat-sheet"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
Git和Git Flow速查表 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/arslanbilal/git-cheat-sheet.svg?branch=master)](https://travis-ci.org/arslanbilal/git-cheat-sheet)
===============
<hr>
<p align="center">
    <img alt="Git" src="https://raw.githubusercontent.com/arslanbilal/git-cheat-sheet/master/./Img/git-logo.png" height="190" width="455">
</p>
<hr>

## Other Available Languages:

1. [Arabic Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-ar.md)
2. [Chinese Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-zh.md)
3. [Hindi Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-hi.md)
4. [Turkish Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-tr.md)
5. [Spanish Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-es.md)
6. [Greek Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-el.md)
7. [Brazilian Portuguese Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet/blob/master/other-sheets/git-cheat-sheet-pt_BR.md)

Git备忘单让您免于全心学习所有命令.

自由贡献，更新语法错误. 您也可以自由添加语言文件.

<hr>

Git作弊表英语
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
$ git config --global user.name“ [名姓]”
```

##### Set an email address that will be associated with each history marker:
```
$ git config --global user.email“ [有效电子邮件]”
```

##### Set automatic command line coloring for Git for easy reviewing:
```
$ git config --global color.ui自动
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

通过SSH

```
$ git clone ssh：//user@domain.com/repo.git
```

通过HTTP

```
$ git clone http://domain.com/user/repo.git
```

##### Create a new local repository in the current directory:
```
$ git init
```

##### Create a new local repository in a specific directory:
```
$ git init<directory>
```

<hr>

## Local Changes

##### Changes in working directory:
```
$ git状态
```

##### Changes to tracked files:
```
$ git diff
```

##### See changes/difference of a specific file:
```
$ git diff<file>
```

##### Add all current changes to the next commit:
```
$ git添加.
```

##### Add some changes in &lt;file&gt; to the next commit:
```
$ git add -p<file>
```

##### Add only the mentioned files to the next commit:
```
$ git添加<filename1><filename2>
```

##### Commit all local changes in tracked files:
```
$ git commit -a
```

##### Commit previously staged changes:
```
$ git commit
```

##### Commit with message:
```
$ git commit -m&#39;这里的消息&#39;
```

##### Commit skipping the staging area and adding message:
```
$ git commit -am&#39;消息在这里&#39;
```

##### Commit to some previous date:
```
 $ git commit --date =“`date --date =&#39;n day ago&#39;`” -am“<Commit Message Here>  ”
```

##### Change last commit:<br>
<em><sub>不要修改已发布的提交！</sub></em>

```
$ git commit -a-修改
```

##### Amend with last commit but use the previous commit log message
<em><sub>不要修改已发布的提交！</sub></em>

```shell
$ git commit --amend --no-edit
```

##### Change committer date of last commit:
```
GIT_COMMITTER_DATE =“ date” git commit --amend
```

##### Change Author date of last commit:
```shell
$ git commit --amend --date =“日期”
```

##### Move uncommitted changes from current branch to some other branch:<br>
```
$ git stash
$ git checkout branch2
$ git stash pop
```

##### Restore stashed changes back to current branch:
```shell
$ git stash适用
```

#### Restore particular stash back to current branch:
-* {stash_number} *可以从`git stash list`获取

```shell
$ git stash apply stash @ {stash_number}
```

##### Remove the last set of stashed changes:
```
$ git隐藏
```

<hr>

## Search

##### A text search on all files in the directory:
```
$ git grep“你好”
```

##### In any version of a text search:
```
$ git grep“ Hello” v2.5
```

##### Show commits that introduced a specific keyword
```
$ git log -S&#39;关键字&#39;
```

##### Show commits that introduced a specific keyword (using a regular expression)
```
$ git log -S&#39;关键字&#39;--pickaxe-regex
```

<hr>

## Commit History

##### Show all commits, starting with newest (it'll show the hash, author information, date of commit and title of the commit):
```
$ git日志
```

##### Show all the commits(it'll show just the commit hash and the commit message):
```
$ git log --oneline
```

##### Show all commits of a specific user:
```
$ git log --author =“用户名”
```

##### Show changes over time for a specific file:
```
$ git log -p<file>
```

##### Display commits that are present only in remote/branch in right side
```
 $ git log --oneline<origin/master>  ..<remote/master>  - 左右
```

##### Who changed, what and when in &lt;file&gt;:
```
$ git怪<file>
```

##### Show Reference log:
```
$ git reflog显示
```

##### Delete Reference log:
```
$ git reflog删除
```
<hr>

## Move / Rename

##### Rename a file:

将Index.txt重命名为Index.html

```
$ git mv Index.txt Index.html
```

<hr>

## Branches & Tags

##### List all local branches:
```
$ git分支
```

#### List local/remote branches
```
$ git branch -a
```

##### List all remote branches:
```
$ git branch -r
```

##### Switch HEAD branch:
```
$ git checkout<branch>
```

##### Checkout single file from different branch
```
 $ git checkout<branch>  -<filename>
```

##### Create and switch new branch:
```
$ git checkout -b<branch>
```


##### Create a new branch from an exiting branch and switch to new branch:
```
$ git checkout -b<new_branch><existing_branch>
```


#### Checkout and create a new branch from existing commit
```
 $ git checkout<commit-hash>  -b<new_branch_name>
```


##### Create a new branch based on your current HEAD:
```
$ git分支<new-branch>
```

##### Create a new tracking branch based on a remote branch:
```
$ git branch --track<new-branch><remote-branch>
```

##### Delete a local branch:
```
$ git branch -d<branch>
```

##### Rename current branch to new branch name
```shell
$ git branch -m<new_branch_name>
```

##### Force delete a local branch:
<em><sub>您将丢失未合并的更改！</sub></em>

```
$ git分支-D<branch>
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
 $ git标签<tag-name> -am&#39;这里的消息&#39;
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
$ git remote -v
```

##### Show information about a remote:
```
$ git remote show<remote>
```

##### Add new remote repository, named &lt;remote&gt;:
```
$ git remote add<remote><url>
```

##### Rename a remote repository, from &lt;remote&gt; to &lt;new_remote&gt;:
```
$ git远程重命名<remote><new_remote>
```

##### Remove a remote:
```
$ git远程rm<remote>
```

<em><sub>注意：git remote rm不会从服务器删除远程存储库.</sub></em> <em><sub>它只是从本地存储库中删除远程及其引用.</sub></em>

##### Download all changes from &lt;remote&gt;, but don't integrate into HEAD:
```
$ git获取<remote>
```

##### Download changes and directly merge/integrate into HEAD:
```
$ git remote pull<remote><url>
```

##### Get all changes from HEAD to local repository:
```
$ git pull origin master
```

##### Get all changes from HEAD to local repository without a merge:
```
$ git pull --rebase<remote><branch>
```

##### Publish local changes on a remote:
```
$ git push remote<remote><branch>
```

##### Delete a branch on the remote:
```
 $ git push<remote>  ：<branch>  （自Git v1.5.0起）
```
OR
```
 $ git push<remote>  - 删除<branch> （自Git v1.7.0起）
```

##### Publish your tags:
```
$ git push-标签
```
<hr>

#### Configure the merge tool globally to meld (editor)
```bash
$ git config --global merge.tool合并
```

##### Use your configured merge tool to solve conflicts:
```
$ git mergetool
```

## Merge & Rebase

##### Merge branch into your current HEAD:
```
$ git合并<branch>
```

##### Rebase your current HEAD onto &lt;branch&gt;:<br>
<em><sub>不要改变发布的提交！</sub></em>

```
$ git rebase<branch>
```

##### Abort a rebase:
```
$ git rebase --abort
```

##### Continue a rebase after resolving conflicts:
```
$ git rebase-继续
```

##### Use your editor to manually solve conflicts and (after resolving) mark file as resolved:
```
$ git添加<resolved-file>
```

```
$ git rm<resolved-file>
```

##### Squashing commits:
```
$ git rebase -i<commit-just-before-first>
```

现在更换它，

```
挑选<commit_id>
挑选<commit_id2>
挑选<commit_id3>
```

为此，

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
$ git reset HEAD
```

##### Discard local changes in a specific file:
```
$ git checkout HEAD<file>
```

##### Revert a commit (by producing a new commit with contrary changes):
```
$ git还原<commit>
```

##### Reset your HEAD pointer to a previous commit and discard all changes since then:
```
$ git reset --hard<commit>
```

##### Reset your HEAD pointer to a remote branch current state.
```
 $ git reset --hard<remote/branch> 例如，上游/母版，来源/我的功能
```

##### Reset your HEAD pointer to a previous commit and preserve all changes as unstaged changes:
```
$ git reset<commit>
```

##### Reset your HEAD pointer to a previous commit and preserve uncommitted local changes:
```
$ git reset --keep<commit>
```

##### Remove files that were accidentally committed before they were added to .gitignore
```
$ git rm -r-缓存.
$ git添加.
$ git commit -m“删除xyz文件”
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
$ brew安装git-flow-avh
```

##### OSX Macports:
```
$ port安装git-flow
```

##### Linux (Debian-based):
```
$ sudo apt-get安装git-flow
```

##### Windows (Cygwin):
###### You need wget and util-linux to install git-flow.
```bash
 $ wget -q -O---no-check-certificate https://raw.githubusercontent.com/petervanderdoes/gitflow/develop/contrib/gitflow-installer.sh安装<state> | 重击
```
<hr>

### Getting Started
###### Git flow needs to be initialized in order to customize your project setup. Start using git-flow by initializing it inside an existing git repository:
##### Initialize:
###### You'll have to answer a few questions regarding the naming conventions for your branches. It's recommended to use the default values.
```shell
git flow初始化
```
OR
###### To use default
```shell
git flow初始化-d
```
<hr>

### Features
###### Develop new features for upcoming releases. Typically exist in developers repos only.
##### Start a new feature:
###### This action creates a new feature branch based on 'develop' and switches to it.
```
git flow功能启动MYFEATURE
```

##### Finish up a feature:
###### Finish the development of a feature. This action performs the following:
###### 1) Merged MYFEATURE into 'develop'.
###### 2) Removes the feature branch.
###### 3) Switches back to 'develop' branch
```
git flow功能完成MYFEATURE
```

##### Publish a feature:
###### Are you developing a feature in collaboration? Publish a feature to the remote server so it can be used by other users.
```
git flow功能发布MYFEATURE
```

##### Getting a published feature:
###### Get a feature published by another user.
```
git flow功能拉原点MYFEATURE
```

##### Tracking a origin feature:
###### You can track a feature on origin by using
```
git flow功能跟踪MYFEATURE
```
<hr>

### Make a Release
###### Support preparation of a new production release. Allow for minor bug fixes and preparing meta-data for a release

##### Start a release:
###### To start a release, use the git flow release command. It creates a release branch created from the 'develop' branch. You can optionally supply a [BASE] commit sha-1 hash to start the release from. The commit must be on the 'develop' branch.
```
git flow发布开始发布[BASE]
```
###### It's wise to publish the release branch after creating it to allow release commits by other developers. Do it similar to feature publishing with the command:
```
git flow发布发布
```
###### (You can track a remote release with the: ```git flow release track RELEASE``` command)

##### Finish up a release:
###### Finishing a release is one of the big steps in git branching. It performs several actions:
###### 1) Merges the release branch back into 'master'
###### 2) Tags the release with its name
###### 3) Back-merges the release into 'develop'
###### 4) Removes the release branch
```
git flow发布完成发布
```
###### Don't forget to push your tags with ```git push --tags```

<hr>

### Hotfixes
###### Hotfixes arise from the necessity to act immediately upon an undesired state of a live production version. May be branched off from the corresponding tag on the master branch that marks the production version.

##### Git flow hotfix start:
###### Like the other git flow commands, a hotfix is started with
```
$ git flow hotfix启动VERSION [BASENAME]
```
###### The version argument hereby marks the new hotfix release name. Optionally you can specify a basename to start from.

##### Finish a hotfix:
###### By finishing a hotfix it gets merged back into develop and master. Additionally the master merge is tagged with the hotfix version
```
git flow修补程序完成版本
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
