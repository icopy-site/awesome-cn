<div class="github-widget" data-repo="git-tips/tips"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## git-tips
 &gt; git-tips的集合，想添加您的提示吗？  查看 [contributing.md](https://github.com/git-tips/tips/blob/master/./contributing.md)

[English](http://git.io/git-tips) | [中文](https://github.com/521xueweihan/git-tips) | [Русский](https://github.com/Imangazaliev/git-tips) | [한국어](https://github.com/mingrammer/git-tips) | [Tiếng Việt](https://github.com/hprobotic/git-tips) | [日本語](https://github.com/isotai/git-tips) | [नेपाली](https://github.com/amarduwal/git-tips)

### __Tools:__

* [git-tip](https://www.npmjs.com/package/git-tip)  -方便的CLI，可最佳利用这些技巧.  （[Here in Docker container](https://github.com/djoudi5/docker-git-tip))

PS：所有这些命令均在git版本2.7.4（Apple Git-66）上进行了测试.

<!-- @doxie.inject start toc -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
* [Edit [local/global] git config](#edit-localglobal-git-config)

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end toc -->


<!-- @doxie.inject start -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
## Everyday Git in twenty commands or so
```sh
git每天帮助
```

## Show helpful guides that come with Git
```sh
git help -g
```

```sh
git log -S&#39; <a term in the source>&#39;</a>
```

## Show changes over time for specific file
```sh
git log -p <file_name>
```

## Remove sensitive data from history, after a push
```sh
 git filter-branch --force --index-filter&#39;git rm --cached --ignore-unmatch <path-to-your-file>  &#39;--prune-empty --tag-name-filter cat---all &amp;&amp; git push origin --force --all
```

## Sync with remote, overwrite local changes
```sh
git fetch origin &amp;&amp; git reset --hard origin / master &amp;&amp; git clean -f -d
```

## List of all files till a commit
```sh
git ls-tree --name-only -r <commit-ish>
```

## Git reset first commit
```sh
git update-ref -d头
```

## Reset: preserve uncommitted local changes
```sh
git reset-保持<commit>
```

## List all the conflicted files
```sh
git diff-仅名称--diff-filter = U
```

## List of all files changed in a commit
```sh
git diff-tree --no-commit-id --name-only -r <commit-ish>
```

## Unstaged changes since last commit
```sh
git差异
```

## Changes staged for commit
```sh
git diff-缓存
```


__Alternatives:__
```sh
git diff --staged
```

## Show both staged and unstaged changes
```sh
git diff头
```

## List all branches that are already merged into master
```sh
git branch-合并的主
```

## Quickly switch to the previous branch
```sh
git checkout-
```


__Alternatives:__
```sh
git checkout @ {-1}
```

## Remove branches that have already been merged with master
```sh
 git branch-合并的主|  grep -v&#39;^ \ *&#39;|  xargs -n 1 git分支-d
```


__Alternatives:__
```sh
git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d # will not delete master if master is not checked out
```

## List all branches and their upstreams, as well as last commit on branch
```sh
git分支-vv
```

## Track upstream branch
```sh
git branch -u来源/ mybranch
```

## Delete local branch
```sh
git分支-d <local_branchname>
```

## Delete remote branch
```sh
git push origin-删除<remote_branchname>
```


__Alternatives:__
```sh
git push来源： <remote_branchname>
```


```sh
git分支-dr <remote/branch>
```

## Delete local tag
```sh
git标签-d <tag-name>
```

## Delete remote tag
```sh
git push origin：参考/标签/ <tag-name>
```

```sh
git checkout- <file_name>
```

## Revert: Undo a commit by creating a new commit
```sh
去还原<commit-ish>
```

## Reset: Discard commits, advised for private branch
```sh
git重置<commit-ish>
```

## Reword the previous commit message
```sh
git commit -v-修改
```

## See commit history for just the current branch
```sh
git cherry -v主控
```

## Amend author.
```sh
 git commit --amend --author =&#39;作者姓名 <email@address.com>  &#39;
```

## Reset author, after author has been changed in the global config.
```sh
git commit --amend --reset-author --no-edit
```

## Changing a remote's URL
```sh
git remote set-url的起源<URL>
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
git分支-a
```

## Get only remote branches
```sh
git分支-r
```

## Stage parts of a changed file, instead of the entire file
```sh
git添加-p
```

## Get git bash completion
```sh
 curl -L http://git.io/vfhol&gt;〜/ .git-completion.bash &amp;&amp; echo&#39;[-f〜/ .git-completion.bash] &amp;&amp;.  〜/ .git-completion.bash&#39;&gt;&gt;〜/ .bashrc
```

## What changed since two weeks?
```sh
git log --no-merges --raw --since =&#39;2周前&#39;
```


__Alternatives:__
```sh
git whatchanged --since =&#39;2周前&#39;
```

## See all commits made since forking from master
```sh
git log --no-merges --stat --reverse master ..
```

## Pick commits across branches using cherry-pick
```sh
 git checkout <branch-name>  &amp;&amp; git cherry-pick <commit-ish>
```

## Find out branches containing commit-hash
```sh
git branch -a-包含<commit-ish>
```


__Alternatives:__
```sh
git branch-包含<commit-ish>
```

## Git Aliases
```sh
git config-全局别名<handle><command> 
git config --global alias.st状态
```

## Saving current state of tracked files without commiting
```sh
git stash
```


__Alternatives:__
```sh
git stash保存
```

## Saving current state of unstaged changes to tracked files
```sh
git stash -k
```


__Alternatives:__
```sh
git stash --keep-index
```


```sh
git stash save --keep-index
```

## Saving current state including untracked files
```sh
去藏-u
```


__Alternatives:__
```sh
git stash save -u
```


```sh
git stash save --include-untracked
```

## Saving current state with message
```sh
git stash保存<message>
```

## Saving current state of all files (ignored, untracked, and tracked)
```sh
git stash -a
```


__Alternatives:__
```sh
git stash --all
```


```sh
git stash save --all
```

## Show list of all saved stashes
```sh
git存储列表
```

## Apply any stash without deleting from the stashed list
```sh
git stash适用<stash@{n}>
```

## Apply last stashed state and delete it from stashed list
```sh
git stash pop
```


__Alternatives:__
```sh
git stash应用stash @ {0} &amp;&amp; git stash drop存放stash @ {0}
```

## Delete all stored stashes
```sh
git隐藏
```


__Alternatives:__
```sh
git隐藏<stash@{n}>
```

## Grab a single file from a stash
```sh
 git checkout <stash@{n}>  - <file_path>
```


__Alternatives:__
```sh
git checkout stash @ {0}- <file_path>
```

## Show all tracked files
```sh
git ls文件-t
```

## Show all untracked files
```sh
git ls-files-其他
```

## Show all ignored files
```sh
git ls-files --others -i --exclude-standard
```

## Create new working tree from a repository (git 2.5)
```sh
git工作树添加-b <branch-name><path><start-point>
```

## Create new working tree from HEAD state
```sh
 git worktree添加--detach <path>  头
```

## Untrack files without deleting
```sh
git rm-缓存<file_path>
```


__Alternatives:__
```sh
git rm-缓存-r <directory_path>
```

## Before deleting untracked files/directory, do a dry run to get the list of these files/directories
```sh
git clean -n
```

## Forcefully remove untracked files
```sh
git clean -f
```

## Forcefully remove untracked directory
```sh
git clean -f -d
```

## Update all the submodules
```sh
git子模块foreach git pull
```


__Alternatives:__
```sh
git子模块更新--init --recursive
```


```sh
git子模块更新-远程
```

## Show all commits in the current branch yet to be merged to master
```sh
git cherry -v主控
```


__Alternatives:__
```sh
git cherry -v主控<branch-to-be-merged>
```

## Rename a branch
```sh
git分支-m <new-branch-name>
```


__Alternatives:__
```sh
 git branch -m [ <old-branch-name>  ] <new-branch-name>
```

## Rebases 'feature' to 'master' and merges it in to master 
```sh
git rebase master功能&amp;&amp; git checkout master &amp;&amp; git merge-
```

## Archive the `master` branch
```sh
git archive master --format = zip --output = master.zip
```

## Modify previous commit without modifying the commit message
```sh
git add --all &amp;&amp; git commit --amend --no-edit
```

## Prunes references to remote branches that have been deleted in the remote.
```sh
git fetch -p
```


__Alternatives:__
```sh
git remote prune起源
```

## Retrieve the commit hash of the initial revision.
```sh
  git rev-list --reverse HEAD |复制代码  头-1
```


__Alternatives:__
```sh
git rev-list --max-parents = 0头
```


```sh
 git log --pretty = oneline |  尾巴-1 |  切-c 1-40
```


```sh
 git log --pretty = oneline --reverse |  头-1 |  切-c 1-40
```

## Visualize the version tree.
```sh
git log --pretty = oneline --graph --decorate --all
```


__Alternatives:__
```sh
gitk-全部
```


```sh
 git log --graph --pretty =格式：&#39;％C（auto）％h |  ％s |  ％an |  ％ar％d&#39;
```

## Visualize the tree including commits that are only referenced from reflogs
```sh
git log --graph --decorate --oneline $（git rev-list --walk-reflogs --all）
```

## Deploying git tracked subfolder to gh-pages
```sh
git subtree push --prefix subfolder_name原始gh-pages
```

## Adding a project to repo using subtree
```sh
 git子树添加--prefix = <directory_name>  / <project_name>  --squash git@github.com： <username>  / <project_name>  .git master
```

## Get latest changes in your repo for a linked project using subtree
```sh
 git subtree pull --prefix = <directory_name>  / <project_name>  --squash git@github.com： <username>  / <project_name>  .git master
```

## Export a branch with history to a file.
```sh
git bundle创建<file><branch-name>
```

## Import from a bundle
```sh
 git clone repo.bundle <repo-dir>  -b <branch-name>
```

## Get the name of current branch.
```sh
git rev-parse --abbrev-ref头
```

## Ignore one file on commit (e.g. Changelog).
```sh
 git update-index-假定不变的变更日志;  git commit -a;  git update-index-无假设不变的变更日志
```

## Stash changes before rebasing
```sh
git rebase --autostash
```

## Fetch pull request by ID to a local branch
```sh
 git fetch origin pull / <id>  /头： <branch-name>
```


__Alternatives:__
```sh
 git pull origin pull / <id>  /头： <branch-name>
```

## Show the most recent tag on the current branch.
```sh
git describe --tags --abbrev = 0
```

## Show inline word diff.
```sh
git diff --word-diff
```

## Show changes using common diff tools.
```sh
 git difftool [-t <tool>  ] <commit1><commit2><path>
```

## Don’t consider changes for tracked file.
```sh
git update-index-假定不变<file_name>
```

## Undo assume-unchanged.
```sh
git update-index-无假设不变<file_name>
```

## Clean the files from `.gitignore`.
```sh
git clean -X -f
```

## Restore deleted file.
```sh
 git checkout <deleting_commit>  ^- <file_path>
```

## Restore file to a specific commit-hash
```sh
 git checkout <commit-ish>  - <file_path>
```

## Always rebase instead of merge on pull.
```sh
git config --global pull.rebase是
```


__Alternatives:__
```sh
#git < 1.7.9
git config --global branch.autosetuprebase总是
```

## List all the alias and configs.
```sh
git config --list
```

## Make git case sensitive.
```sh
git config --global core.ignorecase否
```

## Add custom editors.
```sh
git config --global core.editor&#39;$ EDITOR&#39;
```

## Auto correct typos.
```sh
git config --global help.autocorrect 1
```

## Check if the change was a part of a release.
```sh
git name-rev-仅名称<SHA-1>
```

## Dry run. (any command that supports dry-run flag should do.)
```sh
git clean -fd --dry-run
```

## Marks your commit as a fix of a previous commit.
```sh
git commit --fixup <SHA-1>
```

## Squash fixup commits normal commits.
```sh
git rebase -i-自动压扁
```

## Skip staging area during commit.
```sh
git commit-仅<file_path>
```

## Interactive staging.
```sh
git添加-i
```

## List ignored files.
```sh
git check-ignore *
```

## Status of ignored files.
```sh
git status-忽略
```

## Commits in Branch1 that are not in Branch2
```sh
git log Branch1 ^ Branch2
```

## List n last commits
```sh
git日志- <n>
```


__Alternatives:__
```sh
git log -n <n>
```

## Reuse recorded resolution, record and reuse previous conflicts resolutions.
```sh
git config --global rerere.enabled 1
```

## Open all conflicted files in an editor.
```sh
 git diff-仅名称|  uniq |  xargs $ EDITOR
```

## Count unpacked number of objects and their disk consumption.
```sh
git count-objects-可读
```

## Prune all unreachable objects from the object database.
```sh
git gc --prune = now --aggressive
```

## Instantly browse your working repository in gitweb.
```sh
 git instaweb [--local] [--httpd = <httpd>  ] [--port = <port>  ] [--browser = <browser>  ]
```

## View the GPG signatures in the commit log
```sh
git log --show-signature
```

## Remove entry in the global config.
```sh
git config --global --unset <entry-name>
```

## Checkout a new branch without any history
```sh
git checkout-孤立<branch_name>
```

## Extract file from another branch.
```sh
 git show <branch_name>  ： <file_name>
```

## List only the root and merge commits.
```sh
git log --first-parent
```

## Change previous two commits with an interactive rebase.
```sh
git rebase-交互式HEAD〜2
```

## List all branch is WIP
```sh
git checkout master &amp;&amp; git分支-不合并
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
git log-关注-p- <file_path>
```

## Clone a single branch
```sh
 git clone -b <branch-name>  --single-branch https://github.com/user/repo.git
```

## Create and switch new branch
```sh
git checkout -b <branch-name>
```


__Alternatives:__
```sh
 git分支 <branch-name>  &amp;&amp; git结帐 <branch-name>
```

## Ignore file mode changes on commits
```sh
git config core.fileMode错误
```

## Turn off git colored terminal output
```sh
git config --global color.ui false
```

## Specific color settings
```sh
git config --global <specific command e.g branch, diff><true, false or always>
```

## Show all local branches ordered by recent commits
```sh
git for-each-ref --sort = -committerdate --format =&#39;％（refname：short）&#39;refs / heads /
```

## Find lines matching the pattern (regex or string) in tracked files
```sh
git grep --heading --line-number&#39;foo bar&#39;
```

## Clone a shallow copy of a repository
```sh
git clone https://github.com/user/repo.git --depth 1
```

## Search Commit log across all branches for given text
```sh
 git log --all --grep =&#39; <given-text>  &#39;
```

## Get first commit in a branch (from master)
```sh
 git log --oneline主站 <branch-name>  |  尾-1
```


__Alternatives:__
```sh
 git log --reverse master .. <branch-name>  |  头-6
```

## Unstaging Staged file
```sh
git reset HEAD <file-name>
```

## Force push to Remote Repository
```sh
git push -f <remote-name><branch-name>
```

## Adding Remote name
```sh
git远程添加<remote-nickname><remote-url>
```

## List all currently configured remotes
```sh
git remote -v
```

## Show the author, time and last revision made to each line of a given file
```sh
吉特怪<file-name>
```

## Group commits by authors and title
```sh
git shortlog
```

## Forced push but still ensure you don't overwrite other's work
```sh
git push-强制租赁<remote-name><branch-name>
```

## Show how many lines does an author contribute
```sh
 git log --author =&#39;_ Your_Name_Here_&#39;--pretty = tformat：--numstat |  gawk&#39;{添加+ = <!-- @doxie.inject start -->  ;  潜艇+ = <!-- @doxie.inject end -->  ;  loc + = <!-- @doxie.inject start -->  -- <!-- @doxie.inject end -->  } END {printf“添加了行：％s已删除行：％s总行：％s
“，添加，订阅，位置}&#39;-
```


__Alternatives:__
```sh
 git log --author =&#39;_ Your_Name_Here_&#39;--pretty = tformat：--numstat |  awk&#39;{添加+ = <!-- @doxie.inject start -->  ;  潜艇+ = <!-- @doxie.inject end -->  ;  loc + = <!-- @doxie.inject start -->  -- <!-- @doxie.inject end -->  } END {printf“添加了行：％s，已删除的行：％s，总行：％s
", add, subs, loc }' - # on Mac OSX
```

## Revert: Reverting an entire merge
```sh
git revert -m 1 <commit-ish>
```

## Number of commits in a branch
```sh
git rev-list --count <branch-name>
```

## Alias: git undo
```sh
git config --global alias.undo '!f() { git reset --hard $(git rev-parse --abbrev-ref HEAD)@{${1-1}}; }; f'
```

## Add object notes
```sh
git notes add -m&#39;上一次提交的注释....
```

## Show all the git-notes
```sh
git log --show-notes =&#39;*&#39;
```

## Apply commit from another repository
```sh
 git --git-dir = <source-dir>  /.git format-patch -k -1 --stdout <SHA1>  |  去-3 -k
```

## Specific fetch reference
```sh
git fetch origin master：引用/远程/源/ mymaster
```

## Find common ancestor of two branches
```sh
git go-base <branch-name><other-branch-name>
```

## List unpushed git commits
```sh
git log --branches --not --remotes
```


__Alternatives:__
```sh
git log @ {u} ..
```


```sh
吉特樱桃-v
```

## Add everything, but whitespace changes
```sh
 git diff --ignore-all-space |  git apply --cached
```

## Edit [local/global] git config
```sh
git config [--global] --edit
```

## blame on certain range
```sh
 git怪-L <start>  ， <end>
```

## Show a Git logical variable.
```sh
git var -l | <variable>
```

## Preformatted patch file.
```sh
git format-patch -M上游..主题
```

## Get the repo name.
```sh
git rev-parse --show-toplevel
```

## logs between date range
```sh
git log --since =&#39;FEB 1 2017&#39;--until =&#39;FEB 14 2017&#39;
```

## Exclude author from logs
```sh
git log --perl-regexp --author =&#39;^（（?!排除作者正则表达式）.*）

```

## Generates a summary of pending changes
```sh
git request-pull v1.0 https：//git.ko.xz/project master：for-linus
```

## List references in a remote repository
```sh
git ls-远程git：//git.kernel.org/pub/scm/git/git.git
```

## Backup untracked files.
```sh
 git ls文件--others -i --exclude-standard |  xargs zip untracked.zip
```

## List all git aliases
```sh
 混帐配置-l |  grep的其他|  的sed的/ ^其他\ .// G&#39;
```


__Alternatives:__
```sh
 git config -l |  grep别名|  切-d&#39;.  -f 2
```

## Show git status short
```sh
git status --short-分支
```

## Checkout a commit prior to a day ago
```sh
git checkout master @ {昨天}
```

## Push a new local branch to remote repository and track
```sh
git push -u起源<branch_name>
```

## Change a branch base
```sh
git rebase --onto <new_base><old_base>
```

## Use SSH instead of HTTPs for remotes
```sh
git config --global url.&#39;git@github.com：&#39;.insteadOf&#39;https://github.com/&#39;
```

## Update a submodule to the latest commit
```sh
光盘<path-to-submodule>
git pull起源<branch>
光盘<root-of-your-main-project>
git添加<path-to-submodule>
git commit -m“子模块已更新”
```

## Prevent auto replacing LF with CRLF
```sh
git config --global core.autocrlf否
```

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end -->
