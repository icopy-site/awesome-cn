<div class="github-widget" data-repo="git-tips/tips"></div>
## git-tips
 &gt; `git-tips` 合集，想添加你的技巧吗？ 查看 [contributing.md](https://github.com/git-tips/tips/blob/master/./contributing.md)

[English](http://git.io/git-tips) | [中文](https://github.com/521xueweihan/git-tips) | [Русский](https://github.com/Imangazaliev/git-tips) | [한국어](https://github.com/mingrammer/git-tips) | [Tiếng Việt](https://github.com/hprobotic/git-tips) | [日本語](https://github.com/isotai/git-tips) | [नेपाली](https://github.com/amarduwal/git-tips) | [Polski](https://github.com/mbiesiad/tips) | [فارسی](https://github.com/javadnikbakht/git-tips)

### __Tools:__

* [git-tip](https://www.npmjs.com/package/git-tip)  - 一个方便的 CLI，可以最佳地利用这些技巧.  ([Here in Docker container](https://github.com/djoudi5/docker-git-tip))

PS：所有这些命令都在 `git version 2.7.4 (Apple Git-66)` 上进行了测试.

<!-- @doxie.inject start toc -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
* [Edit [local/global] git config](#edit-localglobal-git-config)

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end toc -->


<!-- @doxie.inject start -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
## Everyday Git in twenty commands or so
```sh
每天都有 git 帮助
```

## Show helpful guides that come with Git
```sh
git 帮助 -g
```

```sh
git 日志 -S&#39; <a term in the source>&#39;</a>
```

## Show changes over time for specific file
```sh
git 日志 -p<file_name>
```

## Remove sensitive data from history, after a push
```sh
 git filter-branch --force --index-filter &#39;git rm --cached --ignore-unmatch<path-to-your-file>  &#39; --prune-empty --tag-name-filter cat -- --all &amp;&amp; git push origin --force --all
```

## Sync with remote, overwrite local changes
```sh
git fetch origin &amp;&amp; git reset --hard origin/master &amp;&amp; git clean -f -d
```

## List of all files till a commit
```sh
git ls-tree --name-only -r<commit-ish>
```

## Git reset first commit
```sh
git update-ref -d HEAD
```

## Reset: preserve uncommitted local changes
```sh
git 重置 --keep<commit>
```

## List all the conflicted files
```sh
git diff --name-only --diff-filter=U
```

## List of all files changed in a commit
```sh
git diff-tree --no-commit-id --name-only -r<commit-ish>
```

## Unstaged changes since last commit
```sh
比较差异
```

## Changes staged for commit
```sh
git diff --cached
```


__Alternatives:__
```sh
git diff --staged
```

## Show both staged and unstaged changes
```sh
git 差异头
```

## List all branches that are already merged into master
```sh
git branch --merged master
```

## Quickly switch to the previous branch
```sh
git结帐-
```


__Alternatives:__
```sh
git checkout @{-1}
```

## Remove branches that have already been merged with master
```sh
git branch --merged master | grep -v '^\*' | xargs -n 1 git branch -d
```


__Alternatives:__
```sh
git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d # will not delete master if master is not checked out
```

## List all branches and their upstreams, as well as last commit on branch
```sh
git 分支 -vv
```

## Track upstream branch
```sh
git branch -u 原点/mybranch
```

## Delete local branch
```sh
git 分支 -d<local_branchname>
```

## Delete remote branch
```sh
git push origin --delete<remote_branchname>
```


__Alternatives:__
```sh
git 推送来源：<remote_branchname>
```


```sh
git 分支-dr<remote/branch>
```

## Create local tag
```sh
吉日<tag-name>
```

## Delete local tag
```sh
git 标签 -d<tag-name>
```

## Delete remote tag
```sh
git push 原点：refs/标签/<tag-name>
```

```sh
git结账——<file_name>
```

## Revert: Undo a commit by creating a new commit
```sh
git 恢复<commit-ish>
```

## Reset: Discard commits, advised for private branch
```sh
git 重置<commit-ish>
```

## Reword the previous commit message
```sh
git commit -v --amend
```

## See commit history for just the current branch
```sh
git cherry -v 大师
```

## Amend author.
```sh
 git commit --amend --author=&#39;作者姓名<email@address.com> &#39;
```

## Reset author, after author has been changed in the global config.
```sh
git commit --amend --reset-author --no-edit
```

## Changing a remote's URL
```sh
git 远程设置 url 来源<URL>
```

## Get list of all remote references
```sh
git远程
```


__Alternatives:__
```sh
git远程显示
```

## Get list of all local and remote branches
```sh
git 分支 -a
```

## Get only remote branches
```sh
git 分支 -r
```

## Stage parts of a changed file, instead of the entire file
```sh
git 添加 -p
```

## Get git bash completion
```sh
 curl -L http://git.io/vfhol &gt; ~/.git-completion.bash &amp;&amp; echo &#39;[ -f ~/.git-completion.bash ] &amp;&amp; .  ~/.git-completion.bash&#39; &gt;&gt; ~/.bashrc
```

## What changed since two weeks?
```sh
git log --no-merges --raw --since=&#39;2 周前&#39;
```


__Alternatives:__
```sh
git whatchanged --since=&#39;2 周前&#39;
```

## See all commits made since forking from master
```sh
git log --no-merges --stat --reverse master..
```

## Pick commits across branches using cherry-pick
```sh
结帐<branch-name> &amp;&amp; git 樱桃挑选<commit-ish>
```

## Find out branches containing commit-hash
```sh
git branch -a --contains<commit-ish>
```


__Alternatives:__
```sh
git 分支 --contains<commit-ish>
```

## Git Aliases
```sh
git config --global 别名.<handle><command> 
git config --global alias.st 状态
```

## Saving current state of tracked files without commiting
```sh
git 存储
```


__Alternatives:__
```sh
git 隐藏推送
```

## Saving current state of unstaged changes to tracked files
```sh
git 存储 -k
```


__Alternatives:__
```sh
git stash --keep-index
```


```sh
git stash push --keep-index
```

## Saving current state including untracked files
```sh
git 存储 -u
```


__Alternatives:__
```sh
git stash push -u
```


```sh
git stash push --include-untracked
```

## Saving current state with message
```sh
git stash push -m<message>
```


__Alternatives:__
```sh
git stash push——消息<message>
```

## Saving current state of all files (ignored, untracked, and tracked)
```sh
git 存储 -a
```


__Alternatives:__
```sh
git stash --all
```


```sh
git stash push --all
```

## Show list of all saved stashes
```sh
git 存储列表
```

```sh
git 存储显示 -p<stash@{n}>
```

## Apply any stash without deleting from the stashed list
```sh
git 存储应用<stash@{n}>
```

## Apply last stashed state and delete it from stashed list
```sh
git 存储弹出
```


__Alternatives:__
```sh
git stash apply stash@{0} &amp;&amp; git stash drop stash@{0}
```

## Delete all stored stashes
```sh
git 存储清除
```


__Alternatives:__
```sh
git 存储下降<stash@{n}>
```

## Grab a single file from a stash
```sh
结帐<stash@{n}> --<file_path>
```


__Alternatives:__
```sh
git checkout stash@{0} --<file_path>
```

## Show all tracked files
```sh
git ls-文件-t
```

## Show all untracked files
```sh
git ls-files --others
```

## Show all ignored files
```sh
git ls-files --others -i --exclude-standard
```

## Create new working tree from a repository (git 2.5)
```sh
git worktree 添加-b<branch-name><path><start-point>
```

## Create new working tree from HEAD state
```sh
 git worktree 添加 --detach<path> 头
```

## Untrack files without deleting
```sh
git rm --缓存<file_path>
```


__Alternatives:__
```sh
git rm --cached -r<directory_path>
```

## Before deleting untracked files/directory, do a dry run to get the list of these files/directories
```sh
混帐清洁-n
```

## Forcefully remove untracked files
```sh
混帐清理-f
```

## Forcefully remove untracked directory
```sh
git clean -f -d
```

## Update all the submodules
```sh
git 子模块 foreach git pull
```


__Alternatives:__
```sh
git 子模块更新 --init --recursive
```


```sh
git 子模块更新 --remote
```

## Show all commits in the current branch yet to be merged to master
```sh
git cherry -v 大师
```


__Alternatives:__
```sh
git cherry -v 大师<branch-to-be-merged>
```

## Rename a branch
```sh
git 分支 -m<new-branch-name>
```


__Alternatives:__
```sh
 git 分支-m [<old-branch-name>  ]<new-branch-name>
```

## Rebases 'feature' to 'master' and merges it in to master 
```sh
git rebase master feature &amp;&amp; git checkout master &amp;&amp; git merge -
```

## Archive the `master` branch
```sh
git archive master --format=zip --output=master.zip
```

## Modify previous commit without modifying the commit message
```sh
git add --all &amp;&amp; git commit --amend --no-edit
```

## Prunes references to remove branches that have been deleted in the remote.
```sh
git 获取 -p
```


__Alternatives:__
```sh
git 远程修剪源
```

## Delete local branches that has been squash and merged in the remote.
```sh
 git 分支-vv |  grep &#39;: gone]&#39; |  awk &#39;{打印<!-- @doxie.inject start --> }&#39; |  xargs git 分支-D
```

## Retrieve the commit hash of the initial revision.
```sh
  git rev-list --reverse 头 | 头-1
```


__Alternatives:__
```sh
git rev-list --max-parents=0 头
```


```sh
 git 日志 --pretty=oneline | 尾-1 | 切-c 1-40
```


```sh
 git log --pretty=oneline --reverse | 头-1 | 切-c 1-40
```

## Visualize the version tree.
```sh
git log --pretty=oneline --graph --decorate --all
```


__Alternatives:__
```sh
gitk --all
```


```sh
 git log --graph --pretty=format:&#39;%C(auto) %h |  %s |  %一个 |  %ar%d&#39;
```

## Visualize the tree including commits that are only referenced from reflogs
```sh
git log --graph --decorate --oneline $(git rev-list --walk-reflogs --all)
```

## Deploying git tracked subfolder to gh-pages
```sh
git subtree push --prefix subfolder_name origin gh-pages
```

## Adding a project to repo using subtree
```sh
 git 子树添加 --prefix=<directory_name>  /<project_name>  --squash git@github.com:<username>  /<project_name>  .git 大师
```

## Get latest changes in your repo for a linked project using subtree
```sh
 git subtree pull --prefix=<directory_name>  /<project_name>  --squash git@github.com:<username>  /<project_name>  .git 大师
```

## Export a branch with history to a file.
```sh
git 捆绑创建<file><branch-name>
```

## Import from a bundle
```sh
 git 克隆 repo.bundle<repo-dir>  -b<branch-name>
```

## Get the name of current branch.
```sh
git rev-parse --abbrev-ref HEAD
```

## Ignore one file on commit (e.g. Changelog).
```sh
 git update-index --assume-unchanged 更新日志；  git提交-a；  git update-index --no-assume-unchanged 更新日志
```

## Stash changes before rebasing
```sh
git fox --autostash
```

## Fetch pull request by ID to a local branch
```sh
 git fetch 原点拉/<id>  /头：<branch-name>
```


__Alternatives:__
```sh
 git pull 原点拉/<id>  /头：<branch-name>
```

## Show the most recent tag on the current branch.
```sh
git describe --tags --abbrev=0
```

## Show inline word diff.
```sh
git diff --word-diff
```

## Show changes using common diff tools.
```sh
 git difftool [-t<tool>  ]<commit1><commit2><path>
```

## Don’t consider changes for tracked file.
```sh
git update-index --assume-unchanged<file_name>
```

## Undo assume-unchanged.
```sh
git update-index --no-assume-unchanged<file_name>
```

## Clean the files from `.gitignore`.
```sh
git clean -X -f
```

## Restore deleted file.
```sh
结帐<deleting_commit> --<file_path>
```

## Restore file to a specific commit-hash
```sh
结帐<commit-ish> --<file_path>
```

## Always rebase instead of merge on pull.
```sh
git config --global pull.rebase true
```


__Alternatives:__
```sh
#git < 1.7.9
git config --global branch.autosetuprebase 总是
```

## List all the alias and configs.
```sh
git 配置--列表
```

## Make git case sensitive.
```sh
git config --global core.ignorecase false
```

## Add custom editors.
```sh
git config --global core.editor &#39;$EDITOR&#39;
```

## Auto correct typos.
```sh
git config --global help.autocorrect 1
```

## Check if the change was a part of a release.
```sh
git name-rev --name-only<SHA-1>
```

## Dry run. (any command that supports dry-run flag should do.)
```sh
git clean -fd --dry-run
```

## Marks your commit as a fix of a previous commit.
```sh
git commit --fixup<SHA-1>
```

## Squash fixup commits normal commits.
```sh
git fox -i --autosquash
```

## Skip staging area during commit.
```sh
git commit --only<file_path>
```

## Interactive staging.
```sh
git 添加 -i
```

## List ignored files.
```sh
git 检查忽略 *
```

## Status of ignored files.
```sh
git状态——被忽略
```

## Commits in Branch1 that are not in Branch2
```sh
git log 分支 1 ^ 分支 2
```

## List n last commits
```sh
git 日志 -<n>
```


__Alternatives:__
```sh
git 日志 -n<n>
```

## Reuse recorded resolution, record and reuse previous conflicts resolutions.
```sh
git config --global rerere.enabled 1
```

## Open all conflicted files in an editor.
```sh
 git diff --name-only | 独特 |  xargs $编辑器
```

## Count unpacked number of objects and their disk consumption.
```sh
git count-objects --human-readable
```

## Prune all unreachable objects from the object database.
```sh
git gc --prune=now --aggressive
```

## Instantly browse your working repository in gitweb.
```sh
 git instaweb [--local] [--httpd=<httpd>  ] [--端口=<port>  ] [--浏览器=<browser>  ]
```

## View the GPG signatures in the commit log
```sh
git log --show-签名
```

## Remove entry in the global config.
```sh
git 配置 --global --unset<entry-name>
```

## Checkout a new branch without any history
```sh
git checkout --orphan<branch_name>
```

## Extract file from another branch.
```sh
混帐显示<branch_name> :<file_name>
```

## List only the root and merge commits.
```sh
git log --first-parent
```

## Change previous two commits with an interactive rebase.
```sh
git rebase --interactive HEAD~2
```

## List all branch is WIP
```sh
git checkout master &amp;&amp; git branch --no-merged
```

## Find guilty with binary search
```sh
git bisect start                    # Search start 
git bisect bad                      # Set point to bad commit 
git bisect good v2.6.13-rc2         # Set point to good commit|tag 
git bisect bad                      # Say current state is bad 
git bisect good                     # Say current state is good 
git bisect reset                    # Finish search 

```

## Bypass pre-commit and commit-msg githooks
```sh
git commit --no-verify
```

## List commits and changes to a specific file (even through renaming)
```sh
git log --follow -p --<file_path>
```

## Clone a single branch
```sh
 git 克隆 -b<branch-name>  --单分支 https://github.com/user/repo.git
```

## Create and switch new branch
```sh
git结帐-b<branch-name>
```


__Alternatives:__
```sh
分支<branch-name> &amp;&amp; 结帐<branch-name>
```

```sh
git 开关 -c<branch-name>
```

## Ignore file mode changes on commits
```sh
git config core.fileMode false
```

## Turn off git colored terminal output
```sh
git config --global color.ui false
```

## Specific color settings
```sh
git 配置 --global<specific command e.g branch, diff><true, false or always>
```

## Show all local branches ordered by recent commits
```sh
git for-each-ref --sort=-committerdate --format=&#39;%(refname:short)&#39; refs/heads/
```

## Find lines matching the pattern (regex or string) in tracked files
```sh
git grep --heading --line-number &#39;foo bar&#39;
```

## Clone a shallow copy of a repository
```sh
git clone https://github.com/user/repo.git --depth 1
```

## Search Commit log across all branches for given text
```sh
 git log --all --grep=&#39;<given-text>  &#39;
```

## Get first commit in a branch (from master)
```sh
 git log --oneline master..<branch-name>  | 尾巴-1
```


__Alternatives:__
```sh
 git log --reverse master..<branch-name>  | 头-6
```

## Unstaging Staged file
```sh
git 重置 HEAD<file-name>
```

## Force push to Remote Repository
```sh
git push -f<remote-name><branch-name>
```

## Adding Remote name
```sh
git 远程添加<remote-nickname><remote-url>
```

## List all currently configured remotes
```sh
git远程-v
```

## Show the author, time and last revision made to each line of a given file
```sh
指责<file-name>
```

## Group commits by authors and title
```sh
git 简报
```

## Forced push but still ensure you don't overwrite other's work
```sh
git push --force-with-lease<remote-name><branch-name>
```

## Show how many lines does an author contribute
```sh
 git log --author=&#39;_Your_Name_Here_&#39; --pretty=tformat: --numstat | 呆呆的&#39;{ 添加 +=<!-- @doxie.inject start -->  ; 潜艇+=<!-- @doxie.inject end -->  ; 地点+=<!-- @doxie.inject start -->  -<!-- @doxie.inject end -->  } END { printf &quot;添加行：%s 删除行：%s 总行数：%s
&quot;, 添加, 潜艇, loc }&#39; -
```


__Alternatives:__
```sh
 git log --author=&#39;_Your_Name_Here_&#39; --pretty=tformat: --numstat |  awk &#39;{ 添加 +=<!-- @doxie.inject start -->  ; 潜艇+=<!-- @doxie.inject end -->  ; 地点+=<!-- @doxie.inject start -->  -<!-- @doxie.inject end -->  } END { printf &quot;添加行：%s，删除行：%s，总行数：%s
", add, subs, loc }' - # on Mac OSX
```

## Revert: Reverting an entire merge
```sh
git 恢复-m 1<commit-ish>
```

## Number of commits in a branch
```sh
git rev-list --count<branch-name>
```

## Alias: git undo
```sh
 git config --global alias.undo &#39;!f() { git reset --hard $(git rev-parse --abbrev-ref HEAD)@{${1-1}};  };  F&#39;
```

## Add object notes
```sh
git notes add -m &#39;注意上次提交....&#39;
```

## Show all the git-notes
```sh
git log --show-notes=&#39;*&#39;
```

## Apply commit from another repository
```sh
 git --git-dir=<source-dir>  /.git format-patch -k -1 --stdout<SHA1>  |  git am -3 -k
```

## Specific fetch reference
```sh
git fetch origin master：refs/remotes/origin/mymaster
```

## Find common ancestor of two branches
```sh
git 合并基础<branch-name><other-branch-name>
```

## List unpushed git commits
```sh
git log --branches --not --remotes
```


__Alternatives:__
```sh
git 日志 @{u}..
```


```sh
混帐樱桃-v
```

## Add everything, but whitespace changes
```sh
 git diff --ignore-all-space |  git apply --cached
```

## Edit [local/global] git config
```sh
git 配置 [--global] --edit
```

## blame on certain range
```sh
 git责备-L<start>  ,<end>
```

## Show a Git logical variable.
```sh
混帐变种-l |<variable>
```

## Preformatted patch file.
```sh
git format-patch -M upstream..topic
```

## Get the repo name.
```sh
git rev-parse --show-toplevel
```

## logs between date range
```sh
git log --since=&#39;2017 年 2 月 1 日&#39; --until=&#39;2017 年 2 月 14 日&#39;
```

## Exclude author from logs
```sh
git log --perl-regexp --author=&#39;^((?!excluded-author-regex).*)

```

## Generates a summary of pending changes
```sh
git request-pull v1.0 https://git.ko.xz/project master:for-linus
```

## List references in a remote repository
```sh
git ls-remote git://git.kernel.org/pub/scm/git/git.git
```

## Backup untracked files.
```sh
 git ls-files --others -i --exclude-standard |  xargs zip untracked.zip
```

## List all git aliases
```sh
 git 配置 -l |  grep 别名 |  sed &#39;s/^别名\.//g&#39;
```


__Alternatives:__
```sh
 git 配置 -l |  grep 别名 | 切-d &#39;.&#39;  -f 2
```

## Show git status short
```sh
git status --short --branch
```

## Checkout a commit prior to a day ago
```sh
git checkout master@{昨天}
```

## Push the current branch to the same name on the remote repository
```sh
git push 原点 HEAD
```

## Push a new local branch to remote repository and track
```sh
git push -u 原点<branch_name>
```

## Change a branch base
```sh
git rebase --onto<new_base><old_base>
```

## Use SSH instead of HTTPs for remotes
```sh
git config --global url.&#39;git@github.com:&#39;.insteadOf &#39;https://github.com/&#39;
```

## Update a submodule to the latest commit
```sh
光盘<path-to-submodule>
git 拉出原点<branch>
光盘<root-of-your-main-project>
添加<path-to-submodule>
git commit -m “子模块已更新”
```

## Prevent auto replacing LF with CRLF
```sh
git config --global core.autocrlf false
```

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end -->
