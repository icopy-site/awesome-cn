<div class="github-widget" data-repo="stevemao/awesome-git-addons"></div>
## Awesome git addons [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

扩展/增强git CLI的附加组件的精选列表.

```
$ git bla
真棒棒的事！
```

 &gt; _“你不必知道一切.  你只需要知道必要时在哪里找到它.“（John Brunner）_

灵感来自于 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

 **注意**：某些命令可能无法开箱即用.  您可能需要运行安装后脚本来添加别名或手动添加它们.





## [git-extras](https://github.com/tj/git-extras)

### squash

```
$ git squash fixed-cursor-styling“固定光标样式”
$ git squash 95b7c52
$ git squash HEAD~3
```

### summary

```
$ git摘要

 项目：git
 回购年龄：10年
 活动：11868天
 提交：40530
 档案：2825
 作者：
 15401 June C Hamano 38.0％
  1844杰夫金4.5％
```

### line-summary

```
$ git line-summary

 项目：gulp
 线：3900
 作者：
 1040对26.7％
  828 Sindre Sorhus 21.2％
```

### effort

```
$ git努力

  文件提交活动天数

  .gitattributes ............................... 3 3
  .gitignore ................................... 265 226
  .mail文件夹................................... 47 47
```

### authors

```
$ git作者
针对<contra@maricopa.edu>
Eric Sc​​hoffstall <contra@wearefractal.com>
Sindre Sorhus <sindresorhus@gmail.com>
```

### changelog

```
$ git changelog
## 3.9.0

- 添加巴贝尔支持
- 添加转发器后备支持
- 添加对某些重命名的转发器（livingcript等）的支持
- 添加JSCS
- 更新家属（升空，解释）
- 文档调整

## 3.8.11

- 修复节点0.12 / iojs问题
- 将节点0.12和iojs添加到travis
- 更新依赖项（liftoff，v8flags）
- 文档调整
```

### commits-since

```
$ git提交 - 从昨天开始
......自昨天以来的变化
TJ Holowaychuk  - 修正了自述文件
```

### count

```
$ git计数
总计855
```

### create-branch

```
$ git create-branch开发
总计3（delta 0），重复使用0（delta 0）
要https://github.com/tj/git-extras.git
 * [新分支] HEAD  - &gt;开发
分支开发设置为从源跟踪远程分支开发.
切换到新的分支&#39;发展&#39;
```

### delete-branch

```
$ git delete-branch integration
删除了分支集成（是bfb8522）.
删除远程跟踪分支远程/集成（是bfb8522）.
致git@github.com:remote/gulp.git
 -  [删除]整合
```

### delete-submodule

```
$ git delete-submodule lib / foo
```

### delete-tag

```
$ git delete-tag v0.1.1
删除标签&#39;v0.1.1&#39;（是9fde751）
要https://github.com/tj/git-extras.git
 -  [删除] v0.1.1
```

### delete-merged-branches

```
$ git delete-merged-branches
删除的功能/主题（是c029ab3）.
删除功能/ live_preview（是a81b002）.
已删除的功能/仪表板（为923befa）.
```

### fresh-branch

```
$ git fresh-branch docs
正在删除.DS_Store
删除.editorconfig
删除.gitignore
```

### guilt

```
$ git guilt`git log --until =“3周前”--format =“％H”-n 1` HEAD
保罗·施雷伯+++++++++++++++++++++++++++++++++++++++++++++（349）
spacewander ++++++++++++++++++++++++++++++++++++++++++++++++++++++++ ++
Mark Eissler ++++++++++++++++++++++++++++++++++
```

### merge-into

```
$ git merge-into master
切换到分支&#39;主&#39;
您的分支机构与“origin / master”保持同步.
正在更新9fde751..e62edfa
Fast-forward
 234 | 0
 1个文件已更改，0个插入（+），0个删除（ - ）
 创建模式100644 234
切换到分支&#39;发展&#39;
```

### graft

```
$ git移植开发
您的分支机构与“origin / master”保持同步.
通过“递归”策略进行合并.
  package.json |  2 +  - 
 1个文件已更改，1个插入（+），1个删除（ - ）
删除分支开发（64b3563）.
```

### alias

```
$ git alias last“cat-file commit HEAD”
$ git别名
last = cat-file commit HEAD
```

### ignore

```
$ git ignore build“* .o”“* .log”
...添加&#39;构建&#39;
...添加&#39;* .o&#39;
...添加&#39;* .log&#39;
```

### info

```
$ go info

    ## 远程网址：

    origin git@github.com:sampleAuthor / git-extras.git（fetch）
    来源git@github.com:sampleAuthor / git-extras.git（推）

    ## 远程分支：

    origin / HEAD  - &gt; origin / master
    产地/ myBranch

    ## 当地分支机构：

    myBranch
    *主人

    ## 最近的提交：

    提交e3952df2c172c6f3eb533d8d0b1a6c77250769a7
    作者：样本作者<sampleAuthor@gmail.com>

    添加了git-info命令.

     输入&#39;git log&#39;以获取更多提交，或&#39;git show <commit id>  &#39;完整的提交细节.

    ## 配置（.git / config）：

    color.diff =汽车
    color.status =汽车
```

### fork

```
$ git fork LearnBoost / expect.js
```

### release

```
$ git发布0.1.0
...释放0.1.0
关于分支发展
Your branch is up-to-date with 'origin/development'.
无需提交，工作目录清理
总计0（delta 0），重用0（delta 0）
要https://github.com/tj/git-extras.git
   9fde751..e62edfa master  - &gt; master
计数对象：1，完成.
 写入对象：100％（1/1），166字节|  0字节/秒，完成.
总计1（delta 0），重用0（delta 0）
要https://github.com/tj/git-extras.git
 * [新的一天] 0.1.0  - &gt; 0.1.0
......完成
```

### contrib

```
$ git contrib visionmedia
visionmedia（18）：
  导出STATUS_CODES
  用Array.prototype.unshift.call（）替换了几个Array.prototype.slice.call（）调用
  将帮助消息移动到node-repl
```

### repl

```
$ git repl

git&gt; ls-files
History.md
Makefile
```

### undo

```
$ git undo
重置后未分级更改：
M package.json
M readme.md
```

### gh-pages

```
$ git gh-pages
```

### scp

```
$ git scp staging HEAD
```

### setup

```
$ git setup
/GitHub/test/gulp/.git/中初始化的空Git存储库
[master（root-commit）9469797]初始提交
 更改了69个文件，3900个插入（+）
 创建模式100644 .editorconfig
 创建模式100644 .gitignore
 创建模式100644 .jscsrc
```

### touch

```
$ git touch index.js
```

### obliterate

```
$ git obliterate secrets.json
重写2357a4334051a6d1733037406ab7538255030d0b（1/981）rm&#39;secrets.json&#39;
重写b5f62b2746c23150917d346bd0c50c467f01eb03（2/981）rm&#39;secrets.json&#39;
重写3cd94f3395c2701848f6ff626a0a4f883d8a8433（3/981）rm&#39;secrets.json&#39;
```

### feature|refactor|bug|chore

```
$ git功能依赖项
$ git功能完成依赖项
已经是最新的.
删除分支功能/依赖项（f0fc4c7）.
删除了远程跟踪分支原点/功能/依赖项（f0fc4c7）.
致git@github.com:stevemao/gulp.git
 -  [删除]功能/依赖项
```

### local-commits

```
$ git local-commits
commit 5f00a3c1bb71876ebdca059fac96b7185dea5467
合并：7ad3ef9 841af4e
作者：Blaine Bublitz <blaine@iceddev.com>
日期：2015年8月20日星期四11:35:15 -0700

    Merge pull request #1211 from JimiHFord/patch-1

    更新guidelines.md

提交841af4ee7aaf55b505354d0e86d7fb876d745e26
作者：吉米福特<JimiHFord@users.noreply.github.com>
日期：星期四8月20日11:55:38 2015 -0400

    更新guidelines.md

    固定错字
```

### archive-file

```
$ git archive-file
在分支“master”上构建存档
保存到“gulp.v3.9.0-36-g47cb6b0.zip”（60K）
```

### missing

```
$ git缺少大师
< d14b8f0 only on current checked out branch
&gt; 97ef387只对主人
```

### lock

```
$ config lock / database.yml lock
```

### locked

```
$ git已锁定
config/database.yml
```

### unlock

```
$ un config / database.yml git
```

### reset-file

```
$ git reset-file README.md HEAD ^
将&#39;README.md&#39;重置为HEAD ^
```

### pr

```
$ git pr 226
来自https://github.com/tj/git-extras
 * [new ref] refs / pulls / 226 / head  - &gt; pr / 226
切换到分支&#39;pr / 226&#39;
```

### root

```
$ git root
/GitHub/git
```

### delta

```
$ git delta
README.md
```

### merge-repo

```
$ go merge-repo git@github.com:tj / git-extras.git master.
go fetch git@github.com:tj / git-extras.git master
警告：没有常见的提交
remote：计数对象：3507，完成.
remote：压缩对象：100％（5/5），完成.
remote：总计3507（delta 1），重用0（delta 0），pack-reused 3502
 接收物体：100％（3507/3507），821.12 KiB |  286.00 KiB / s，完成.
解决增量：100％（1986/1986），完成.
来自github.com:tj/git-extras
 *分支主控 - &gt; FETCH_HEAD
添加&#39;dir-merge-repo.E95m0gj&#39;
没有保存的本地更改
```

### psykorebase

```
$ git psykorebase master
$ git psykorebase  - 继续
$ git psykorebase主要功能
```


## [gitflow (AVH Edition)](https://github.com/petervanderdoes/gitflow-avh)

### flow init

```
$ git flow init

应该使用哪个分支来生产产品？
   - 更改日志
   - 主人
生产版本的分支名称：[master]

应该使用哪个分支来整合“下一个版本”？
   - 更改日志
“下一个版本”开发的​​分支名称：[master]
生产和整合分支机构应有所不同
```

### flow feature

```
$ git流程功能
$ git flow功能启动功能强大
$ git flow功能完成了很棒的功能
$ git flow功能删除awesome-feature

$ git flow功能发布了很棒的功能
$ git flow功能拉远程awesome功能
```

### flow release

```
$ git flow release
$ git flow release start awesome-release
$ git flow release完成了awesome-release
$ git flow release删除awesome-release
```

### flow hotfix

```
$ git flow hotfix
$ git flow hotfix start awesome-release
$ git flow hotfix完成了awesome-release
$ git flow hotfix delete awesome-release
```

### flow support

```
$ git流量支持
```


## [git-up](https://github.com/aanand/git-up)

```
$ git up
获取原点
4.0快进......
在上游之前改变日志
掌握快进......
回到4.0
```


## [hub](https://github.com/github/hub)

### clone

```
$ git clone schacon / ticgit
转到克隆：//github.com/schacon/ticgit.git

$ git clone -p schacon / ticgit
&gt; go clone git@github.com:schacon/ticgit.git

$ Git的克隆福利
&gt; git clone git@github.com/YOUR_USER/resque.git
```

### remote add

```
$ git remote add rtomayko
> git remote add rtomayko git://github.com/rtomayko/CURRENT_REPO.git

$ git remote add -p rtomayko
&gt; git remote add rtomayko git@github.com:rtomayko/ CURRENT_REPO.git

$ git remote add origin
&gt; git remote add origin git：//github.com/YOUR_USER/CURRENT_REPO.git
```

### fetch

```
$ git fetch mislav
&gt; git remote add mislev git：//github.com/mislav/REPO.git
&gt; git fetch mislav

$ git fetch mislav，xoebus
&gt; git remote add mislav ...
&gt; git remote add xoebus ...
&gt; git fetch --multiple mislav xoebus
```

### cherry-pick

```
$ git cherry-pick https://github.com/mislav/REPO/commit/SHA
&gt; git remote add -f --no-tags match：//github.com/mislav/REPO.git
&gt; git cherry-pick SHA

$ git cherry-pick mislav @ sha
&gt; git remote add -f --no-tags mislav git：//github.com/mislav/CURRENT_REPO.git
&gt; git cherry-pick SHA

$ git cherry-pick mislav @ sha
&gt; git fetch mislav
&gt; git cherry-pick SHA
```

### am

```
$ git am https://github.com/github/hub/pull/55
[通过API下载补丁]
转到/tmp/55.patch

$ git am --ignore-whitespace https://github.com/davidbalbert/hub/commit/fdb9921
[通过API下载补丁]
&gt; git am --ignore-whitespace /tmp/fdb9921.patch
```

### apply

```
$ git apply https://gist.github.com/8da7fb575debd88c54cf
[通过API下载补丁]
&gt; git apply /tmp/gist-8da7fb575debd88c54cf.txt
```

### fork

```
$ git fork
[repo在GitHub上分叉]
&gt; git remote add -f YOUR_USER git@github.com:YOUR_USER/ CURRENT_REPO.git
```

### pull-request

```
$ git pull-request
[打开文本编辑器以编辑请求的标题和正文]
[在GitHub上打开拉取请求“YOUR_USER：feature”]
```

### checkout

```
$ git checkout https://github.com/github/hub/pull/73
&gt; git remote add -f --no-tags -t feature mislav git：//github.com/mislav/hub.git
&gt; git checkout --track -B mislav-feature mislav / feature
```

### merge

```
$ git去https://github.com/github/hub/pull/73
&gt; git fetch git：//github.com/mislav/hub.git + refs / heads / feature：refs / remotes / mislav / feature
> git merge mislav/feature --no-ff -m 'Merge pull request #73 from mislav/feature...'
```

### create

```
$ git创建
[在GitHub上创建的回购]
&gt; git remote add origin git@github.com:YOUR_USER/ CURRENT_REPO.git
```

### init

```
$ git init -g
&gt;去初始化
&gt; git remote add origin git@github.com:YOUR_USER / REPO.git
```

### push

```
$ git push origin，staging，qa bert_timeout
&gt; git push origin bert_timeout
&gt; git push staging bert_timeout
&gt; git push qa bert_timeout
```

### browse

```
$ git浏览
&gt;打开https://github.com/YOUR_USER/CURRENT_REPO
```

### compare

```
$ git比较重构
&gt;打开https://github.com/CURRENT_REPO/compare/refactor
```

### submodule

```
$ git submodule添加wycats / bundler vendor / bundler
&gt; git submodule添加git：//github.com/wycats/bundler.git vendor / bundler
```

### ci-status

```
$ git ci-status
success
```


## [git-deploy](https://github.com/mislav/git-deploy)

```
$ git remote add production“user@example.com:/ apps / mynewapp”
$ git deploy setup -r“production”
$ git deploy init
$ git push production master
```


## [git-cal](https://github.com/k4rthik/git-cal)

![68747470733a2f2f7261772e6769746875622e636f6d2f6b34727468696b2f6769742d63616c2f6d61737465722f73637265656e73686f74732f696d67322e706e67](https://cloud.githubusercontent.com/assets/6316590/12465623/17d828ea-c023-11e5-8077-2e9a284defd6.png)


## [git-hooks](https://github.com/icefox/git-hooks)

```
$ git hooks --install
$ git hooks
Git钩子安装在此存储库中.

列出用户，项目和全局钩子：
---
/Users/stevemao/.git_hooks:

/GitHub/git-hooks/git_hooks:
commit-msg / signed-off-by  - 检查提交消息是否存在签名越线.
pre-commit / bsd  - 检查BSD许可证.

/GitHub/git-hooks/.githooks:
```


## [git-imerge](https://github.com/mhagger/git-imerge)

### imerge start

```
$ git imerge start --name = next --goal = merge --first-parent 4.0
尝试1-1的automerge ...成功.
尝试自动充电1-29 ...成功.
尝试1-44的automerge ...成功.
尝试1-51的automerge ...成功.
```

### imerge merge

```
$ git imerge merge 4.0
尝试1-1的automerge ...成功.
尝试自动充电1-6 ...成功.
尝试自动充电1-9 ...成功.
尝试自动充电1-10 ...成功.
```

### imerge rebase

```
$ git imerge rebase 4.0
要合并的分支的以下提交是合并提交：
    8e4931ae15971a14897cf347ac50b7d7fe125ac4
    d7c772142ce663a20210db73d9ad17cc8d59e0d6
    856df83c77b33029d2ddfb8eecd08efedeadc027
```

### imerge continue

```
$ git add --all
$ git commit
[imerge / next e442618] imerge&#39;next&#39;：手动合并10-26
$ git imerge继续
已记录合并10-26的合并.
尝试10-27的automerge ...成功.
尝试自动充电10-42 ......失败.
尝试自动充电10-34 ......失败.
尝试10-30的automerge ...成功.
录制自动填充块MergeState（&#39;next&#39;，tip1 =&#39;master&#39;，tip2 =&#39;4.0&#39;，goal =&#39;merge&#39;）[18：20,34：58].
合并完成！
```

### imerge finish

```
$ git imerge完成
之前的HEAD位置是fcbe161 ... imerge&#39;next&#39;：自动合并19-57
切换到分支&#39;下一步&#39;
[next 23362e6]将4.0合并为master（使用imerge）
 日期：星期三9月2日10:59:56 2015 +1000
```

### imerge diagram

```
$ git imerge图
********************
*????????.?????????|
*????????.?????????|
*????????.?????????|
*????????...-------+
*????????.*|#???????
```

### imerge list

```
$ git imerge list
* 下一个
```

### imerge init

```
$ git imerge init --name = next --goal = merge --first-parent 4.0
```

### imerge record

```
$ git imerge记录
已记录合并10-26的合并.
尝试10-27的automerge ...成功.
尝试自动充电10-42 ......失败.
尝试自动充电10-34 ......失败.
```

### imerge autofill

```
$ git imerge autofill
尝试1-1的automerge ...成功.
尝试自动充电1-29 ...成功.
尝试1-44的automerge ...成功.
```

### imerge simplify

```
$ git imerge简化
之前的HEAD位置是4d19598 ... imerge&#39;next&#39;：自动合并20-57
切换到分支&#39;下一步&#39;
[next 6c308aa]将4.0合并为master（使用imerge）
 日期：2015年9月2日星期三13:37:31 +1000
```

### imerge remove

```
$ git imerge删除
```

### imerge reparent

```
$ git imerge reparent
67ebc0e6517ac791de6699453b71d2c7fd81ffcd
```


## [git-issue](https://github.com/dspinellis/git-issue)

### Initialize issue repository

```
$ git issue init
/home/dds/src/gi/.issues中初始化的空问题存储库
$ git issue new -s&#39;从命令行输入的新问题&#39;
添加了问题e6a95c9
```

### Create a new issue (opens editor window)

```
$ git发布新
添加了问题7dfa5b7
```

### List open issues

```
$ git issue list
7dfa5b7从编辑器输入的问题
e6a95c9从命令行输入新问题
```

### Add an issue comment (opens editor window)

```
$ git发表评论e6a95c9
添加了评论8c0d5b3
```

### Add tag to an issue

```
$ git issue标签e6a9急
添加标签紧急
```

### Add two more tags

```
$ git issue标签e6a9 gui crash
添加了标签gui
添加标签崩溃
```

### Remove a tag

```
$ git issue tag -r e6a9 urgent
删除标签紧急
```

### Assign issue

```
$ git issue assign e6a9 joe@example.com
分配给joe@example.com
```

### Add issue watcher

```
$ git issue watcher e6a9 jane@example.com
添加了观察者jane@example.com
```

### List issues tagged as gui

```
$ git issue list gui
e6a95c9从命令行输入新问题
```

### Push issues repository to a server

```
$ git issue git remote add origin git@github.com:dspinellis / gi-example.git
$ git issue git push -u origin master
计数对象：60，完成.
压缩对象：100％（50/50），完成.
 书写对象：100％（60/60），5.35 KiB |  0字节/秒，完成.
总计60（delta 8），重复使用0（delta 0）
发送到git@github.com:dspinellis / gi-example.git
 * [新分支]主人 - &gt;主人
分支主站设置为从原点跟踪远程分支主站.
```

### Clone issues repository from server

```
$ git issue clone git@github.com:dspinellis / gi-example.git my-issues
克隆成&#39;.issues&#39;......
remote：计数对象：60，完成.
remote：压缩对象：100％（42/42），完成.
remote：总计60（delta 8），重用60（delta 8），pack-reused 0
 接收对象：100％（60/60），5.35 KiB |  0字节/秒，完成.
解决增量：100％（8/8），完成.
检查连接...完成.
克隆git@github.com:dspinellis / gi-example.git进入我的问题
```

### List open issues

```
$ git issue list
7dfa5b7从编辑器输入的问题
e6a95c9从命令行输入新问题
```

### Create new issue

```
$ git issue new -s&#39;在另一台主机上添加了问题&#39;
添加了问题abc9adc
```

### Push changes to server

```
$ git问题推送
计数对象：7，完成.
压缩对象：100％（6/6），完成.
 写入对象：100％（7/7），767字节|  0字节/秒，完成.
总计7（delta 0），重用0（delta 0）
发送到git@github.com:dspinellis / gi-example.git
   d6be890..740f9a0 master  - &gt; master
```

### Show issue added on the other host

```
$ git issue show 7dfa5b7
问题7dfa5b7f4591ecaa8323716f229b84ad40f5275b
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日星期五01:03:24 +0200
标签：打开

    从编辑器输入的问题

    这是一个较长的描述.
```

### Show issue and comments

```
$ git issue show -c e6a95c9
问题e6a95c91b31ded8fc229a41cc4bd7d281ce6e0f1
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日星期五01:03:20 +0200
标签：打开紧急gui崩溃
观察者：jane@example.com
已分配给：joe@example.com

    从命令行输入新问题

评论8c0d5b3d77bf93b937cb11038b129f927d49e34a
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日星期五01:03:57 +0200

    关于这个问题的第一评论.
```

### Pull in remote changes (on the original host)

```
$ git问题拉
remote：计数对象：7，完成.
remote：压缩对象：100％（6/6），完成.
remote：总计7（delta 0），重用7（delta 0），pack-reused 0
打开包装对象：100％（7/7），完成.
来自github.com:dspinellis/gi-example
   d6be890..740f9a0 master  - &gt; origin / master
正在更新d6be890..740f9a0
Fast-forward
  issue / ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / description |  1 +
  issue / ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / tags |  1 +
 2个文件已更改，2个插入（+）
 创建模式100644问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / description
 创建模式100644问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / tags
```

### List open issues

```
$ git issue list
7dfa5b7从编辑器输入的问题
abc9adc在另一台主机上添加了问题
e6a95c9从命令行输入新问题
```

### Sub-command auto-completion

```
$ git问题[Tab]
分配克隆评论git init log pull show watcher
附上关闭编辑帮助列表新推标签
```

### Issue Sha auto-completion

```
$ git issue show [Tab]
7dfa5b7  - 从编辑器输入的问题
e6a95c9  - 从命令行输入新问题
```


## [git-lfs](https://github.com/github/git-lfs)

```
$ git lfs track“* .mp3”
跟踪* .mp3

$ git lfs track“* .zip”
跟踪* .zip

$ git lfs track
列出跟踪路径
    * .mp3（.gitattributes）
    * .zip（.gitattributes）

$ git lfs untrack“* .zip”
不跟踪* .zip

$ git lfs track
列出跟踪路径
    * .mp3（.gitattributes）
```


## [git-now](https://github.com/iwata/git-now)

```
$ git现在
[大师1bd9ce8] [从现在开始] 2015/08/27 10:39:10
 1个文件已更改，1个插入（+），1个删除（ - ）
$ git log
提交1bd9ce878a76140f7db95afd9cfd4d7befbc7243
作者：史蒂夫毛<maochenyan@gmail.com>
日期：星期四8月27日10:39:10 2015 +1000

    [从现在开始] 2015/08/27 10:39:10

    diff --git a / package.json b / package.json
    index 8768569..540523a 100644
    --- a / package.json
    +++ b / package.json
    @@ -1,7 +1,7 @@
     {
       “名字”：“gulp”，
       “description”：“流式构建系统”，
    - “版本”：“3.9.0”，
    +“版本”：“3.10.0”，
       “主页”：“http://gulpjs.com”，
       “repository”：“gulpjs / gulp”，
        “作者”：“分形 <contact@wearefractal.com>  （http://wearefractal.com/）”，
```


## [git-plus](https://github.com/tkrajina/git-plus)

### multi

```
$ git multi
--------------------------------------------------------------------------------
执行git status -s
--------------------------------------------------------------------------------
chalk:
	 M package.json

gulp:
	 D index.js
```

### relation

```
$ git relation origin / 4.0
HEAD和origin / 4.0 DIVERGED，共同点是657213a52d5e9c19b85df6a42f76341a98c08ae8

从657213a52d5e9c19b85df6a42f76341a98c08ae8转到HEAD：
检索日志时出错657213a52d5e9c19b85df6a42f76341a98c08ae8..HEAD
```

### old-branches

```
$ git old-branches -d 10
分支4.0超过10天（139.86）！
```

### recent

```
$ git最近
      3.64天：主人
     11.63天：开发
```


## [git-test](https://github.com/spotify/git-test)

```
$ go test -v
4.0 ^ origin / 4.0 ^ origin / master将测试2次提交
iter commit tree结果
0000 57af4b0 f5ef0d8通过（缓存）
0001 10ed389 434370f通过
```


## [legit](https://github.com/kennethreitz/legit)

### branches

```
$ git branches
   4.0（已发布）
   发展（未发表）
   一切都不是很棒（已发布）
*硕士（已出版）
   老主人（已出版）
```

### sync

```
$ git sync
从服务器提取提交.
首先，倒带头重播你的工作......
快进4.0到原点/ 4.0.
将提交推送到服务器.
```

### resync

```
$ git resync
切换到主人.
您的分支在10次提交之前领先于“origin / master”.
  （使用“git push”发布您的本地提交）
从服务器提取提交.
已经是最新的.
切换到主人.
您的分支在10次提交之前领先于“origin / master”.
  （使用“git push”发布您的本地提交）
从主人那里嫁接提交.
已经是最新的.
从服务器提取提交.
已经是最新的.
将提交推送到服务器.
```

### switch

```
$ git switch master
保存本地更改.
保存的工作目录和索引状态On developement：Legit：在切换分支之前进行存储.
HEAD现在在f0fc4c7合并分公司&#39;发展&#39;
切换到主人.
您的分支机构与“origin / master”保持同步.
恢复本地更改.
在分支大师
您的分支机构与“origin / master”保持同步.
未提交更改的更改：
   （使用“git add <file>  ...“更新将要提交的内容”
   （使用“git checkout  -  <file>  ...“放弃工作目录中的更改”

	修改：package.json

没有更改添加到提交（使用“git add”和/或“git commit -a”）
丢失的藏匿@ {0}（86f5dc9066ff9f69c01c77e2f5a55643ad19f8f2）
```

### sprout

```
$ git sprout开发
分支大师发展.
```

### harvest

```
$ git收获发展
从开发中嫁接提交.
正在更新e4f08f4..64b3563
Fast-forward
  package.json |  2 +  - 
 1个文件已更改，1个插入（+），1个删除（ - ）
恢复本地更改.
在分支大师
您的分支通过1次提交超过“origin / master”.
  （使用“git push”发布您的本地提交）
无需提交，工作目录清理
丢失的藏匿@ {0}（7c28b7f5eaf09dd72ec6e1ea440cbd1611e36c7f）
```

### graft

```
$ git移植开发
切换到主人.
你的分支在2次提交之前领先于&#39;origin / master&#39;.
  （使用“git push”发布您的本地提交）
嫁接发展成大师.
通过“递归”策略进行合并.
  功能|  0
 1个文件已更改，0个插入（+），0个删除（ - ）
 创建模式100644功能
删除了分支开发（是6a022ba）.
```

### publish

```
$ git发布
   4.0（已发布）
   更改日志（已发布）
   一切都不是很棒（已发布）
*硕士（未发表）
使用当前分支主服务器找不到分支
出版大师.
分支主站设置为从原点跟踪远程分支主站.
```

### unpublish

```
$ git unpublish master
取消发布主人.
```


## [git-when-merged](https://github.com/mhagger/git-when-merged)

```
$ git when-merged a2c9e695ecf3600f21fa731e705fd1a0503632d9
refs / heads / master 5a2ec1b1a6633f830bd4a2b1daab578c062e6975
$ git何时合并HEAD
refs / heads / master Commit直接在这个分支上.
```


## [git-playback](https://github.com/jianli/git-playback)

```
$ git播放README.md
```

![](https://camo.githubusercontent.com/9abe1d2de474dbc0d1ad4f48acf9e954ff0d0b30/68747470733a2f2f7261772e6769746875622e636f6d2f6a69616e6c692f6769742d706c61796261636b2f6d61737465722f616e696d6174696f6e2e676966)


## [git-branch-status](https://github.com/alexdavid/git-branch-status)

```
$ git branch-status
 4.0 [提前57和高手38] [最新原产地/ 4.0]
 主[当前分支] [原产地/主人之前1]
```


## [git-open](https://github.com/paulirish/git-open)

```
$ git open
&gt;打开https://github.com/REMOTE_ORIGIN_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git打开上游
&gt;打开https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git打开上游主人
&gt;打开https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master
```


## [git-my](https://github.com/davidosomething/git-my)

```
$ git我

+------------------------------------------------------------------------------+
 |  你的名字在git @ repo的远程分支：repopath / reponame.git |
+------------------------------------------------------------------------------+

    本地副本？  在主人？  分店名称
   ................ [合并].  EC-242
   ..... [本地] ... [合并.  CommonJS的，lazyload
  ..... [local] ............. enqueue-gpt
  ......................... defunct-ios-app-nag
  ..... [本地] ............. factor-bundles
```


## [git-ink](https://github.com/davidosomething/git-ink)

```
$ git墨水

•enqueue-gpt ........................................... 2015-08 -31
•factor-bundle ........................................ 2015-10-14
    - 将更多模块拉出到node_modules中
    - 工作但不提供任何收益
•hbsfy ................................................ 2015-10-21
✓主人................................................ 2015年10月22日
•有ads4 .................................................. 2015年10月22日
•remove-equalize_content_height ........................ 2015-10-21
•移除 - 驱除....................................... 2015-10-21
    - 需要干燥驱除功能
    -  uglified时无法正确映射
    - 需要撤消postCSS映射更改
•rm-convert_dates-order ................................ 2015-10-22
•sass-lint ............................................. 2015 -10-14
    - 模块不起作用
```


## [recursive-blame](https://github.com/scottgonzalez/recursive-blame)

```
$ git recursive-blame version package.json

提交：247479d017f138c26be27c64a0ce27f5f21fc0af
作者：杰夫克罗斯<middlefloor@gmail.com>
日期：Tue Oct 13 15:58:13 2015 -0700（7周前）
路径：package.json
匹配：1的1

    家务（发布）：将角度版本变为alpha.42

1) {
2）“名字”：“有角”，
3）“版本”：“2.0.0-alpha.42”，
4）“branchPattern”：“2.0.*”，
5）“描述”：“Angular 2  - 现代网络应用程序的Web框架”，
6）“主页”：“https://github.com/angular/angular”，
7）“bug”：“https://github.com/angular/angular/issues”，

 下一步[r，n，p，c，d，q，？]？  [R

提交：bb9d299b3860f6d579192828451ccd7ace70e1d8
作者：Igor Minar <igor@angularjs.org>
日期：Tue Oct 13 12:28:03 2015 -0700（7周前）
路径：package.json
匹配：1的1

    家务（发布）：将角度版本变为alpha.41

1) {
2）“名字”：“有角”，
3）“版本”：“2.0.0-alpha.41”，
4）“branchPattern”：“2.0.*”，
5）“描述”：“Angular 2  - 现代网络应用程序的Web框架”，
6）“主页”：“https://github.com/angular/angular”，
7）“bug”：“https://github.com/angular/angular/issues”，
```


## [hyper-blame](https://commondatastorage.googleapis.com/chrome-infra-docs/flat/depot_tools/docs/html/git-hyper-blame.html)


```
$ git hyper-blame -i 3ddda43c ipsum.txt
c6eb3bfa（LOREM 2014年8月11日23时15分57秒0000 1）Lorem存有胡萝卜，明尼阿波利斯
134200d1（LOREM 2014年4月10日八时54分46秒+0000 2 *）ADIPISCING客户，你做那种TEMPOR
a34a1d0d（2014年4月11日11时25分04秒+0000非常3a）和活力，劳动和肥胖
 134200d1（LOREM 2014年4月10日八时54分46秒0000 4 *）功能.  多年来VENIAM，“是谁？
c6eb3bfa（LOREM 2014年8月11日23时15分57秒+0000 5）Nostrud例行学区LABORIS
0f0d17bd（ATM 2014年6月2日11时31分48秒+0000 6 *）除非在它aliquipis优势.
```


## [git-word-blame](https://framagit.org/mdamien/git-word-blame)


```
$ git word-blame README.md
结果在/ tmp / word-blame-output /
 -  author_stats.tsv
 -  commit_stats.tsv
 -  word-blame-by-commit.html
 -  word-blame-by-author.html
 - 文本输出
```

![git word-blame on this README](https://user-images.githubusercontent.com/1469823/57202569-0247eb00-6fa7-11e9-8549-f55d81299fab.png)



## [git-fire](https://github.com/qw3rtman/git-fire)

```
$ git fire
切换到新的分支&#39;fire-master-maochenyan@gmail.com-1451379915&#39;
在分支fire-master-maochenyan@gmail.com-1451379915
无需提交，工作目录清理
计数对象：2，完成.
 写入对象：100％（2/2），168字节|  0字节/秒，完成.
总计2（delta 0），重复使用0（delta 0）
致git@bitbucket.org：maochenyan / fire.git
 * [新分店] fire-master-maochenyan@gmail.com-1451379915  - &gt; fire-master-maochenyan@gmail.com-1451379915
分支fire-master-maochenyan@gmail.com-1451379915设置为从原点跟踪远程分支fire-master-maochenyan@gmail.com-1451379915.


离开建筑！
```


## [git-town](https://github.com/Originate/git-town)

TBD


## [git-blame-someone-else](https://github.com/jayphelps/git-blame-someone-else)

```
 $ git blame-someone-else&#39;史蒂夫毛 <maochenyan@gmail.com>  &#39;2efb4e3a061a2e8aaa58033e9c13c3e0e5fcde4b
 Steve Mao现在是2efb4e3的作者.  你是正式混蛋.
```


## [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)

```
$ git dsf
```

![diff-highlight vs diff-so-fancy](https://user-images.githubusercontent.com/3429760/32387617-44c873da-c082-11e7-829c-6160b853adcb.png)


## [git-stats](https://github.com/IonicaBizau/git-stats)

![](http://i.imgur.com/PpM0i3v.png)


## [git-secret](https://github.com/sobolevn/git-secret)

### git secret init

```
$ git secret init
&#39;.gitsecret /&#39;创建.
```

### git secret tell

```
$ git secret告诉my@email.com
 完成.  my@email.com作为知道秘密的人添加.
打扫干净...
```

### git secret add

```
$ git secret add hideme.txt
已添加1项.
```

### git secret list

```
$ git秘密列表
hideme.txt
```

### git secret hide

```
$ git秘密隐藏
 完成.  所有1个文件都被隐藏.
```

### git secret reveal

```
$ git秘密透露

你需要一个密码来解锁密钥
 用户：“测试用户 <my@email.com>  “
2048-bit RSA key, ID #######, created 2015-01-01 (main key ID #######)

gpg：gpg-agent在此会话中不可用
 文件`hideme.txt&#39;存在.  覆盖？  （是/否）y
 完成.  显示所有1个文件.
```


## [git-secrets](https://github.com/awslabs/git-secrets)

&gt;防止您将密码和其他敏感信息提交给git存储库.

TBD


## [git-fixup](https://github.com/keis/git-fixup)

```
$ git diff --cached -U0
diff --git a / README.md b / README.md
index 0c700d1..7a57cef 100644
--- a / README.md
+++ b / README.md
@@ -1330 +1330 @@ $ git secret hide
 完成度的数.  所有1个文件都被隐藏.
 +完成.  所有3个文件都被隐藏.
$ git fixup 6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8
24aa3d9c10cc02fe813dc83d1ac792cc2e7d705d [F]添加git-stats的截图<maochenyan@gmail.com>
6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8 [L]用文本改变了gif <mail@sobolevn.me>
```


## [git-recent](https://github.com/paulirish/git-recent)

```
$ git最近
```

![git-recent screenshot](https://cloud.githubusercontent.com/assets/39191/17446638/039d4cee-5aff-11e6-9e11-4294f0020513.png)

## [git-interactive-rebase-tool](https://github.com/MitMaro/git-interactive-rebase-tool)

```
$ git rebase -i master
```

![git-interactive-rebase-tool screenshot](https://raw.githubusercontent.com/MitMaro/git-interactive-rebase-tool/master/docs/assets/images/git-interactive-rebase-demo.gif)

## [git-fiddle](https://github.com/felixSchl/git-fiddle)

```
$ git fiddle -h
git-fiddle

在* interactive * rebase期间编辑提交元信息.

`git-fiddle（1）&#39;是一个围绕`git-rebase（1）&#39;的轻量级包装器
用它的* author * date，作者名称来注释每个提交
 作为提交消息.  然后将应用对这些中的任何一个的更改
在git-rebase序列中使用&#39;exec&#39;脚本.

Usage:
  $ SCRIPT [ -  [no  - ]  -  fiddle-messages] [args ...]

Options:
    -  [no-] fiddle-messages不编辑提交消息.  对快速编辑很有用
                          作者或约会.  也可以使用此值设置此值
                         `git config fiddle.messages`.
  [args ...]这些参数逐字传递给git-rebase.
```


## [git-user](https://github.com/gesquive/git-user)

```
## add a work profile for Henry
$ git用户添加作品“Henry Jekyll博士”henry@jekyll.com
添加个人资料“工作”

## add a personal profile for Edward
$ git用户添加主页“Edward Hyde”hyde@night.com
添加个人资料&#39;home&#39;

## list out our saved profiles
$ git用户列表
全球简介：
  网友：亨利<hjekyll@gmail.com>

保存的个人资料：
  主页：爱德华海德<hyde@night.com>
  工作：Henry Jekyll博士<henry@jekyll.com>

## set the current git repository user to the home profile
$ git用户设置回家
 &#39;项目&#39;存储库的用户也设置了&#39;Edward Hyde <hyde@night.com>  “

## list profiles again, notice how the current repository profile is now set
$ git用户
项目简介：
  路径：/ path / to / git / project
  网友：Edward Hyde <hyde@night.com>

保存的个人资料：
  主页：爱德华海德<hyde@night.com>
  工作：Henry Jekyll博士<henry@jekyll.com>
```


## [gitsome](https://github.com/donnemartin/gitsome)

TBD


## [git-hound](https://github.com/ezekg/git-hound)

TBD


## [git-recall](https://github.com/Fakerr/git-recall)

![](https://camo.githubusercontent.com/eb306717b95724c33dd0de91faa535a4818cc7d0/687474703a2f2f696d6775722e636f6d2f7a7577324c71572e676966)

```
$ git召回
## By default (without options), the command will display commits from yesterday and
## for the current user.

$ git召回-d 5 -a“Doge”
## Show all Doge's commits from 5 days ago.

$ git召回-d 5 -a“全部”
## Show commits of all contributors from 5 days ago.

$ git召回-f
## Fetch commits beforehand.
```


## [git-standup](https://github.com/kamranahmedse/git-standup)

```
$ git站起来
2f50b39c  -  docs（提交消息）：使用commitizen生成常规提交（12小时前） <Steve Mao>
9af3600e  - 修复测试（12小时前） <Steve Mao>
7f17ba97  -  docs：title case（12小时前） <Steve Mao>
a6d6203c  - 搜索开启时不滚动（12小时前） <Steve Mao>
53fe681a  - 家务（pkg）：添加repo url（12小时前） <Steve Mao>
5e952ac0  - 副标题应该是通用的（13小时前） <Steve Mao>
 adbc5423  - 将ci / cd添加到自述文件中.  （13小时前） <Steve Mao>
a1097116  - 将版本添加到自述文件（14小时前） <Steve Mao>
6b6e7465  - 添加测试覆盖率（15小时前） <Steve Mao>
```


## [commitizen](https://github.com/commitizen/cz-cli)

```
$ git cz
cz-cli@2.9.6, cz-conventional-changelog@1.2.0


 第1行将被裁剪为100个字符.  所有其他行将在100个字符后换行.

 ？  选择您要提交的更改类型:(使用箭头键）
❯壮举：一项新功能
  修复：错误修复
  docs：文档只会更改
  style：不影响代码含义的更改（空格，格式，缺少半
- 等等）
  重构：代码更改既不修复错误也不添加功能
  perf：改进性能的代码更改
  测试：添加缺失测试或更正现有测试
```


## [git-fresh](https://github.com/imsky/git-fresh)

TBD

## [git-fs](https://github.com/freddi301/git-fs)

```
$ go fs
在./git/fs上挂载只读文件系统
```

## [git-url](https://github.com/zdharma/git-url)

### git url

```
$ cd~ / github / git-url.git
$ git url
编码... INPUT是下一段：

协议：https
网站：github.com
回复：zdharma / git-url
修订版：主人

gitu://ҝjȩMżEäḝЃȣϟṈӛŀї

$ go url -r v1.0
编码... INPUT是下一段：

协议：https
网站：github.com
回复：zdharma / git-url
Revision:  v1.0

gitu://ŪĪАϔEäḝЃȣϟṈӛŀї

$ git url -q -p lib/common.sh	# -q - quiet, -p - path
gitu://eḶȸṋ0oǗȟЗÛjȩMżEäḝЃȣϟṈӛŀї

$ git url //eḶȸṋ0oǗȟZûjȩMıEäḝħöbass
解码... OUTPUT是：

协议：https
网站：github.com
回复：zdharma / git-url
修订版：主人
文件：lib / common.sh

https://github.com/zdharma/git-url
```
 
### git guclone

```
$ git guclone ghosts
克隆URL https://github.com/zdharma/git-url用于修订版v1.0

克隆到&#39;git-url&#39;......
remote：计数对象：144，完成.
remote：压缩对象：100％（111/111），完成.
remote：总计144（delta 71），重用102（delta 32），pack-reused 0
 接收物体：100％（144/144），116.43 KiB |  125.00 KiB / s，完成.
解决增量：100％（71/71），完成.

检查版本/参考v1.0 ...确定
HEAD位于：5d10a204，创建了目录git-url
```


## [git-signatures](https://github.com/hashbang/git-signatures)

### signatures add --push

```
$ git签名添加--push v1.0.0
已更新标签&#39;v1.0.0&#39;（已为4de5afd）
枚举对象：4，完成.
计数对象：100％（4/4），完成.
Delta压缩使用多达8个线程
压缩对象：100％（3/3），完成.
 写入对象：100％（3/3），906字节|  906.00 KiB / s，完成了.
总计3（delta 1），重用0（delta 0）
到git@github.com:jsmith / test-signature
   4b5300d..5b1f2cd refs / notes / signatures  - &gt; refs / notes / signature
 + 4de5afd ... 5b1f2cd v1.0.0  - &gt; v1.0.0（强制更新）
```


### signatures verify

```
$ git签名验证v1.0.0
```


### signatures verify --min-count 2

```
$ git签名验证--min-count 2 v1.0.0
无法找到足够的经过验证的签名：min_count = 2

签名验证可能因为您的本地gnupg而失败
keychain和trustdb不包含所需的密钥.

对于详细的签名状态运行：

&gt; git签名显示
```


### signatures show

```
$ git签名显示v1.0.0
  公钥ID |  状态|  信任|  日期|  签名者姓名
=======================================================================================================================
 01234567890ABCDEF |  VALIDSIG |  终极|  11月10日星期六13:16:10东京2018年|  史蒂夫毛 <maochenyan@gmail.com>
 ```


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Steve Mao](https://github.com/stevemao) 已放弃对此作品的所有版权及相关或相邻权利.
