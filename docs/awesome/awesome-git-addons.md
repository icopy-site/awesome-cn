<div class="github-widget" data-repo="stevemao/awesome-git-addons"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome git addons [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

扩展/增强git CLI的附加组件的精选列表.

```
$ git bla
令人敬畏的事情发生了！
```

 &gt; _“您不必了解所有内容.  您只需要知道在必要时在哪里可以找到它.”（John Brunner）_

受到启发 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

 **注意**：某些命令可能无法立即使用.  您可能需要运行安装后脚本来添加别名或手动添加它们.





## [git-extras](https://github.com/tj/git-extras)

### squash

```
$ git squash固定光标样式“固定光标样式”
$ git壁球95b7c52
$ git南瓜头〜3
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
 15401年6月C滨野38.0％
  1844杰夫·金4.5％
```

### line-summary

```
$ git line-summary

 项目：口水
 线路：3900
 作者：
 1040对26.7％
  828 Sindre Sorhus 21.2％
```

### effort

```
$ git的努力

  文件提交活动天数

  .gitattributes ............................... 3 3
  .gitignore ................................... 265 226
  .mailmap ..................................... 47 40
```

### authors

```
$ git作者
反对<contra@maricopa.edu>
埃里克·肖夫斯托尔<contra@wearefractal.com>
信德·索胡斯（Sindre Sorhus） <sindresorhus@gmail.com>
```

### changelog

```
$ git changelog
## 3.9.0

-添加Babel支持
-添加transpiler后备支持
-添加对某些重命名的编译器（livescript等）的支持
-添加JSCS
-更新依赖关系（提升，解释）
-文档调整

## 3.8.11

-修复了节点0.12 / iojs问题
-将节点0.12和iojs添加到travis
-更新依赖关系（提升，v8flags）
-文档调整
```

### commits-since

```
$ git commits-从昨天开始
...自昨天以来发生变化
TJ Holowaychuk-固定的自述文件
```

### count

```
$ git count
总共855
```

### create-branch

```
$ git create-branch开发
总计3（增量0），重用0（增量0）
到https://github.com/tj/git-extras.git
 * [新分支] HEAD-&gt;开发
设立分支机构开发部门以跟踪从源头开始的远程分支机构发展.
切换到新的分支“开发”
```

### delete-branch

```
$ git delete-branch集成
删除了分支集成（为bfb8522）.
删除了远程跟踪分支机构的远程/集成（为bfb8522）.
到git@github.com：remote / gulp.git
 -[已删除]整合
```

### delete-submodule

```
$ git delete-submodule lib / foo
```

### delete-tag

```
$ git delete-tag v0.1.1
已删除标签“ v0.1.1”（原为9fde751）
到https://github.com/tj/git-extras.git
 -[已删除] v0.1.1
```

### delete-merged-branches

```
$ git delete-merged-branches
删除的功能/主题（为c029ab3）.
删除的功能/ live_preview（是a81b002）.
删除的功能/仪表板（以前是923befa）.
```

### fresh-branch

```
$ git fresh-branch文档
删除.DS_Store
删除.editorconfig
删除.gitignore
```

### guilt

```
$ git guilt`git log --until =“ 3星期前” --format =“％H” -n 1` HEAD
保罗·史瑞伯（Paul Schreiber）+++++++++++++++++++++++++++++++++++++++++++（349）
太空漫游者++++++++++++++++++++++++++++++++++++++++++++++（113）
马克·埃斯勒++++++++++++++++++++++++++++
```

### merge-into

```
$ git merge-into master
切换到分支“主人”
您的分支机构的最新信息是“来源/主”.
正在更新9fde751..e62edfa
Fast-forward
 234 | 0
 更改1个文件，0个插入（+），0个删除（-）
 创建模式100644 234
转到分支“发展”
```

### graft

```
$ git移植开发
您的分支机构的最新信息是“来源/主”.
通过“递归”策略进行合并.
  package.json |  2 +-
 更改1个文件，1个插入（+），1个删除（-）
删除分支开发（为64b3563）.
```

### alias

```
$ git别名最后一个“ cat-file commit HEAD”
$ git别名
最后= cat文件提交HEAD
```

### ignore

```
$ git忽略构建“ * .o”“ *.log”
...添加了“构建”
...加了&#39;* .o&#39;
...添加了&#39;* .log&#39;
```

### info

```
$ git信息

    ## 远程URL：

    原始git@github.com：sampleAuthor / git-extras.git（提取）
    原始git@github.com：sampleAuthor / git-extras.git（push）

    ## 远程分支：

    原点/头-&gt;原点/主
    来源/ myBranch

    ## 本地分行：

    myBranch
    *大师

    ## 最近提交：

    提交e3952df2c172c6f3eb533d8d0b1a6c77250769a7
    作者：样本作者<sampleAuthor@gmail.com>

    添加了git-info命令.

     输入“ git log”进行更多提交，或输入“ git show” <commit id>  有关完整的提交详细信息.

    ## 配置（.git / config）：

    color.diff =自动
    color.status =自动
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
您的分支是最新的“来源/开发”.
无需提交，工作目录干净
总计0（增量0），重用0（增量0）
到https://github.com/tj/git-extras.git
   9fde751..e62edfa主-&gt;主
计数对象：1，完成.
 写入对象：100％（1/1），166个字节|  0字节/秒，完成.
总计1（增量0），重用0（增量0）
到https://github.com/tj/git-extras.git
 * [新日期] 0.1.0-&gt; 0.1.0
...完成
```

### contrib

```
$ git contrib visionmedia
视觉媒体（18）：
  汇出STATUS_CODES
  用Array.prototype.unshift.call（）替换了几个Array.prototype.slice.call（）调用
  将帮助味精移至node-repl
```

### repl

```
$ git repl

git&gt; ls文件
History.md
Makefile
```

### undo

```
$ git撤消
重置后的未分级更改：
M package.json
自述文件
```

### gh-pages

```
$ git gh-pages
```

### scp

```
$ git scp登台HEAD
```

### setup

```
$ git设置
在/GitHub/test/gulp/.git/中初始化了空的Git存储库
[master（root-commit）9469797]初次提交
 更改了69个文件，插入了3900个（+）
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
$ git功能完成依赖
已经是最新的.
删除的分支功能/依赖关系（为f0fc4c7）.
删除了远程跟踪分支的起源/功能/依赖关系（为f0fc4c7）.
到git@github.com：stevemao / gulp.git
 -[已删除]功能/依赖项
```

### local-commits

```
$ git local-commits
提交5f00a3c1bb71876ebdca059fac96b7185dea5467
执行：7ad3ef9 841af4e
作者：Blaine Bublitz <blaine@iceddev.com>
日期：2015年8月20日星期四11:35:15

    Merge pull request #1211 from JimiHFord/patch-1

    更新指南.md

提交841af4ee7aaf55b505354d0e86d7fb876d745e26
作者：Jimi Ford <JimiHFord@users.noreply.github.com>
日期：2015年8月20日星期四11:55:38 -0400

    更新指南.md

    固定错字
```

### archive-file

```
$ git存档文件
在“主”分支上建立档案
保存到“ gulp.v3.9.0-36-g47cb6b0.zip”（60K）
```

### missing

```
$ git缺少主人
< d14b8f0 only on current checked out branch
&gt; 97ef387仅在主机上
```

### lock

```
$ git lock config / database.yml
```

### locked

```
$ git已锁定
config/database.yml
```

### unlock

```
$ git解锁配置/ database.yml
```

### reset-file

```
$ git reset-file README.md HEAD ^
将“ README.md”重置为HEAD ^
```

### pr

```
$ git pr 226
从https://github.com/tj/git-extras
 * [新裁判]裁判/拉手/ 226 /头-&gt; pr / 226
切换到分支“ pr / 226”
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
$ git merge-repo git@github.com：tj / git-extras.git大师
git fetch git@github.com：tj / git-extras.git大师
警告：没有常见的提交
远程：计数对象：3507，完成.
远程：压缩对象：100％（5/5），已完成.
远程：总计3507（增量1），已重用0（增量0），重新使用了包3502
 接收物体：100％（3507/3507），821.12 KiB |  286.00 KiB / s，已完成.
解析增量：100％（1986/1986），已完成.
来自github.com:tj/git-extras
 *分支主管-&gt; FETCH_HEAD
添加了目录&#39;git-merge-repo.E95m0gj&#39;
没有要保存的本地更改
```

### psykorebase

```
$ git psykorebase主
$ git psykorebase-继续
$ git psykorebase主功能
```


## [gitflow (AVH Edition)](https://github.com/petervanderdoes/gitflow-avh)

### flow init

```
$ git flow初始化

应该使用哪个分支来发布生产版本？
   -更新日志
   -大师
生产版本的分支名称：[master]

应该使用哪个分支来集成“下一个版本”？
   -更新日志
“下一个发行版”开发的分支名称：[master]
生产和集成部门应该有所不同.
```

### flow feature

```
$ git flow功能
$ git flow功能启动很棒的功能
$ git flow功能完成了很棒的功能
$ git flow功能删除真棒功能

$ git flow功能发布了很棒的功能
$ git flow功能拉远程真棒功能
```

### flow release

```
$ git flow发布
$ git flow release开始很棒的发布
$ git flow release完成很棒的发布
$ git flow release删除真棒发布
```

### flow hotfix

```
$ git flow修补程序
$ git flow hotfix开始发布
$ git flow hotfix完成发布
$ git flow hotfix删除令人敬畏的发布
```

### flow support

```
$ git flow支持
```


## [git-up](https://github.com/aanand/git-up)

```
$ git起来
提取来源
4.0快进...
上游的变更日志
掌握快进...
returning to 4.0
```


## [hub](https://github.com/github/hub)

### clone

```
$ git clone schacon / ticgit
&gt; git clone git：//github.com/schacon/ticgit.git

$ git clone -p schacon / ticgit
&gt; git clone git@github.com：schacon / ticgit.git

$ Git的克隆福利
&gt; git clone git@github.com/YOUR_USER/resque.git
```

### remote add

```
$ git remote add rtomayko
&gt; git remote add rtomayko git：//github.com/rtomayko/CURRENT_REPO.git

$ git remote add -p rtomayko
> git remote add rtomayko git@github.com:rtomayko/CURRENT_REPO.git

$ git remote add origin
&gt; git remote add origin git：//github.com/YOUR_USER/CURRENT_REPO.git
```

### fetch

```
$ git fetch mislav
&gt; git remote add mislav git：//github.com/mislav/REPO.git
&gt; git获取米斯拉夫

$ git fetch mislav，xoebus
&gt; git remote add mislav ...
&gt; git remote add xoebus ...
&gt; git fetch-多个mislav xoebus
```

### cherry-pick

```
$ git cherry-pick https://github.com/mislav/REPO/commit/SHA
&gt; git remote add -f --no-tags mislav git：//github.com/mislav/REPO.git
&gt; git cherry-pick SHA

SHA的$ git cherry-pick mislav @
&gt; git remote add -f --no-tags mislav git：//github.com/mislav/CURRENT_REPO.git
&gt; git cherry-pick SHA

SHA的$ git cherry-pick mislav @
&gt; git获取米斯拉夫
&gt; git cherry-pick SHA
```

### am

```
$上午去https://github.com/github/hub/pull/55
[通过API下载补丁]
&gt;转到上午/tmp/55.patch

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
[在GitHub上分叉的仓库]
&gt; git remote add -f YOUR_USER git@github.com：YOUR_USER / CURRENT_REPO.git
```

### pull-request

```
$ git pull-request
[打开文本编辑器以编辑请求的标题和正文]
[在GitHub上为“ YOUR_USER：feature”打开了请求请求]
```

### checkout

```
$ git checkout https://github.com/github/hub/pull/73
&gt; git remote add -f --no-tags -t功能mislav git：//github.com/mislav/hub.git
&gt; git checkout --track -B mislav-feature mislav / feature
```

### merge

```
$ git转到https://github.com/github/hub/pull/73
&gt; git提取git：//github.com/mislav/hub.git + refs / heads / feature：refs / remotes / mislav / feature
> git merge mislav/feature --no-ff -m 'Merge pull request #73 from mislav/feature...'
```

### create

```
$ git创建
[在GitHub上创建的仓库]
&gt; git remote add origin git@github.com：YOUR_USER / CURRENT_REPO.git
```

### init

```
$ git init -g
&gt;进入初始化
&gt; git remote add origin git@github.com：YOUR_USER / REPO.git
```

### push

```
$ git push origin，staging，qa bert_timeout
&gt; git push起源bert_timeout
&gt; git push阶段bert_timeout
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
$ git子模块添加wycats / bundler供应商/ bundler
&gt; git子模块添加git：//github.com/wycats/bundler.git供应商/ bundler
```

### ci-status

```
$ git ci状态
success
```


## [git-deploy](https://github.com/mislav/git-deploy)

```
$ git remote add production“ user@example.com：/ apps / mynewapp”
$ git deploy setup -r“生产”
$ git deploy初始化
$ git push生产大师
```


## [git-cal](https://github.com/k4rthik/git-cal)

![68747470733a2f2f7261772e6769746875622e636f6d2f6b34727468696b2f6769742d63616c2f6d61737465722f73637265656e73686f74732f696d67322e706e67](https://cloud.githubusercontent.com/assets/6316590/12465623/17d828ea-c023-11e5-8077-2e9a284defd6.png)


## [git-hooks](https://github.com/icefox/git-hooks)

```
$ git hooks-安装
$ git钩子
Git钩子已安装在此存储库中.

列出用户，项目和全局挂钩：
---
/Users/stevemao/.git_hooks:

/GitHub/git-hooks/git_hooks:
commit-msg / sign-off-by-检查提交消息中是否存在Signed-by-line.
pre-commit / bsd-检查BSD许可证.

/GitHub/git-hooks/.githooks:
```


## [git-imerge](https://github.com/mhagger/git-imerge)

### imerge start

```
$ git imerge start --name = next --goal = merge --first-parent 4.0
尝试自动合并1-1 ...成功.
尝试自动合并1-29 ...成功.
尝试自动合并1-44 ...成功.
尝试自动合并1-51 ...成功.
```

### imerge merge

```
$ git imerge merge 4.0
尝试自动合并1-1 ...成功.
尝试自动合并1-6 ...成功.
尝试自动合并1-9 ...成功.
尝试自动合并1-10 ...成功.
```

### imerge rebase

```
$ git imerge rebase 4.0
待合并分支上的以下提交是合并提交：
    8e4931ae15971a14897cf347ac50b7d7fe125ac4
    d7c772142ce663a20210db73d9ad17cc8d59e0d6
    856df83c77b33029d2ddfb8eecd08efedeadc027
```

### imerge continue

```
$ git add --all
$ git commit
[合并/下一个e442618]合并“下一个”：手动合并10-26
$ git imerge继续
已记录合并10-26的合并.
尝试自动合并10-27 ...成功.
尝试自动合并10-42 ...失败.
尝试自动合并10-34 ...失败.
尝试自动合并10-30 ...成功.
记录自动填充的块MergeState（&#39;next&#39;，tip1 =&#39;master&#39;，tip2 =&#39;4.0&#39;，Goal =&#39;merge&#39;）[18：20,34：58].
合并完成！
```

### imerge finish

```
$ git imerge完成
前一个HEAD位置是fcbe161 ... imerge&#39;next&#39;：自动合并19-57
切换到分支“ next”
[next 23362e6]将4.0合并到主服务器（使用imerge）
 日期：2015年9月2日星期三10:59:56 +1000
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
$ git imerge列表
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
尝试自动合并10-27 ...成功.
尝试自动合并10-42 ...失败.
尝试自动合并10-34 ...失败.
```

### imerge autofill

```
$ git imerge自动填充
尝试自动合并1-1 ...成功.
尝试自动合并1-29 ...成功.
尝试自动合并1-44 ...成功.
```

### imerge simplify

```
简化$ git imerge
先前的HEAD位置是4d19598 ... imerge&#39;next&#39;：自动合并20-57
切换到分支“ next”
[next 6c308aa]将4.0合并到主服务器（使用imerge）
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
$ git问题初始化
/home/dds/src/gi/.issues中的初始化的空Issues存储库
$ git issue new -s&#39;从命令行输入新问题&#39;
新增了问题e6a95c9
```

### Create a new issue (opens editor window)

```
$ git问题新
添加了问题7dfa5b7
```

### List open issues

```
$ git问题列表
7dfa5b7从编辑器输入的问题
e6a95c9从命令行输入了新问题
```

### Add an issue comment (opens editor window)

```
$ git问题评论e6a95c9
添加了评论8c0d5b3
```

### Add tag to an issue

```
$ git问题标签e6a9紧急
已添加紧急标签
```

### Add two more tags

```
$ git问题标签e6a9 gui崩溃
添加了标签gui
添加了标签崩溃
```

### Remove a tag

```
$ git问题标签-r e6a9紧急
紧急删除标签
```

### Assign issue

```
$ git问题分配e6a9 joe@example.com
分配给joe@example.com
```

### Add issue watcher

```
$ git问题观察者e6a9 jane@example.com
添加了观察者jane@example.com
```

### List issues tagged as gui

```
$ git问题列表gui
e6a95c9从命令行输入了新问题
```

### Push issues repository to a server

```
$ git问题git remote add origin git@github.com：dspinellis / gi-example.git
$ git issue git push -u原始主机
计数对象：60，完成.
压缩对象：100％（50/50），完成.
 书写对象：100％（60/60），5.35 KiB |  0字节/秒，完成.
总计60（增量8），重用0（增量0）
到git@github.com：dspinellis / gi-example.git
 * [新分支]主-&gt;主
设置了分支母版，以从源头跟踪远程分支母版.
```

### Clone issues repository from server

```
$ git问题克隆git@github.com：dspinellis / gi-example.git my-issues
Cloning into '.issues'...
远程：计数对象：60个，完成.
远程：压缩对象：100％（42/42），已完成.
远程：总计60（增量8），已重复使用60（增量8），已重复使用包装0
 接收物体：100％（60/60），5.35 KiB |  0字节/秒，完成.
解析增量：100％（8/8），已完成.
检查连通性...完成.
将git@github.com：dspinellis / gi-example.git复制到我的问题中
```

### List open issues

```
$ git问题列表
7dfa5b7从编辑器输入的问题
e6a95c9从命令行输入了新问题
```

### Create new issue

```
$ git issue new -s&#39;在另一个主机上添加的问题&#39;
添加了问题abc9adc
```

### Push changes to server

```
$ git问题推送
计数对象：7，完成.
压缩对象：100％（6/6），已完成.
 写入对象：100％（7/7），767个字节|  0字节/秒，完成.
总计7（增量0），已重用0（增量0）
到git@github.com：dspinellis / gi-example.git
   d6be890..740f9a0主-&gt;主
```

### Show issue added on the other host

```
$ git issue show 7dfa5b7
问题7dfa5b7f4591ecaa8323716f229b84ad40f5275b
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日，星期五，01：03：24 +0200
标签：开放

    从编辑器输入的问题

    这是更长的描述.
```

### Show issue and comments

```
$ git issue show -c e6a95c9
问题e6a95c91b31ded8fc229a41cc4bd7d281ce6e0f1
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日，星期五，01：03：20 +0200
标签：打开紧急GUI崩溃
观察者：jane@example.com
分配给：joe@example.com

    从命令行输入新问题

评论8c0d5b3d77bf93b937cb11038b129f927d49e34a
作者：Diomidis Spinellis <dds@aueb.gr>
日期：2016年1月29日，星期五，01：03：57 +0200

    关于此问题的第一条评论.
```

### Pull in remote changes (on the original host)

```
$ git问题拉
远程：计数对象：7，完成.
远程：压缩对象：100％（6/6），已完成.
远程：总计7（增量0），已重用7（增量0），已重用包0
打开包装箱：100％（7/7），已完成.
来自github.com:dspinellis/gi-example
   d6be890..740f9a0主站-&gt;原点/主站
正在更新d6be890..740f9a0
Fast-forward
  问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 /说明|  1 +
  问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / tags |  1 +
 更改2个文件，插入2次（+）
 创建模式100644问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / description
 创建模式100644问题/ ab / c9adc61025a3cb73b0c67470b65cefc133a8d0 / tags
```

### List open issues

```
$ git问题列表
7dfa5b7从编辑器输入的问题
abc9adc问题在另一台主机上添加
e6a95c9从命令行输入了新问题
```

### Sub-command auto-completion

```
$ git问题[Tab]
分配克隆注释git init log pull show watcher
附加关闭编辑帮助列表新的推送标签
```

### Issue Sha auto-completion

```
$ git issue show [制表符]
7dfa5b7-从编辑器输入的问题
e6a95c9-从命令行输入新问题
```


## [git-lfs](https://github.com/github/git-lfs)

```
$ git lfs track“ * .mp3”
跟踪* .mp3

$ git lfs track“ * .zip”
跟踪* .zip

$ git lfs跟踪
列出跟踪路径
    * .mp3（.gitattributes）
    * .zip（.gitattributes）

$ git lfs取消跟踪“ * .zip”
取消跟踪* .zip

$ git lfs跟踪
列出跟踪路径
    * .mp3（.gitattributes）
```


## [git-now](https://github.com/iwata/git-now)

```
现在$ git
[master 1bd9ce8] [从现在开始] 2015/08/27 10:39:10
 更改1个文件，1个插入（+），1个删除（-）
$ git日志
提交1bd9ce878a76140f7db95afd9cfd4d7befbc7243
作者：斯蒂夫·毛<maochenyan@gmail.com>
日期：2015年8月27日星期四10:39:10 +1000

    [从现在开始] 2015/08/27 10:39:10

    diff --git a / package.json b / package.json
    索引8768569..540523a 100644
    --- a / package.json
    +++ b / package.json
    @@ -1,7 +1,7 @@
     {
       “ name”：“ gulp”，
       “ description”：“流式构建系统”，
    -“版本”：“ 3.9.0”，
    +“版本”：“ 3.10.0”，
       “ homepage”：“ http://gulpjs.com”，
       “存储库”：“ gulpjs / gulp”，
        “ author”：“分形 <contact@wearefractal.com>  （http://wearefractal.com/）”，
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
$ git关系origin / 4.0
HEAD and origin / 4.0 DIVERGED，公用点是657213a52d5e9c19b85df6a42f76341a98c08ae8

从657213a52d5e9c19b85df6a42f76341a98c08ae8提交到HEAD：
检索日志657213a52d5e9c19b85df6a42f76341a98c08ae8..HEAD时出错
```

### old-branches

```
$ git old-branches -d 10
Branch 4.0的日期早于10天（139.86）！
```

### recent

```
$ git最近
      3.64天：大师
     11.63天：开发
```


## [git-test](https://github.com/spotify/git-test)

```
$ git test -v
4.0 ^ origin / 4.0 ^ origin / master将测试2次提交
迭代提交树结果
0000 57af4b0 f5ef0d8 pass（已缓存）
0001 10ed389 434370f pass
```


## [legit](https://github.com/kennethreitz/legit)

### branches

```
$ git分支
   4.0（已发布）
   开发（未发布）
   一切都不尽人意（已发布）
*硕士（已出版）
   老主人（已出版）
```

### sync

```
$ git同步
从服务器提取提交.
首先，快退一下，重播您的作品...
将4.0快进至origin / 4.0.
将提交推送到服务器.
```

### resync

```
$ git重新同步
切换到主站.
您的分支比“源/主节点”提前10次提交.
  （使用“ git push”发布您的本地提交）
从服务器提取提交.
已经是最新的.
切换到主站.
您的分支比“源/主节点”提前10次提交.
  （使用“ git push”发布您的本地提交）
嫁接来自大师.
已经是最新的.
从服务器提取提交.
已经是最新的.
将提交推送到服务器.
```

### switch

```
$ git switch master
保存本地更改.
保存的工作目录和索引状态开发中：合法性：在切换分支之前存储.
HEAD现在位于f0fc4c7合并分支“开发”中
切换到主站.
您的分支机构的最新信息是“来源/主”.
恢复本地更改.
在分支机构主管
您的分支机构的最新信息是“来源/主”.
未暂存的更改未提交：
   （使用“ git add <file>  ...”以更新将要提交的内容）
   （使用“ git checkout- <file>  ...”以放弃工作目录中的更改）

	修改：package.json

没有添加任何更改来提交（使用“ git add”和/或“ git commit -a”）
隐藏的存储@@ {0}（86f5dc9066ff9f69c01c77e2f5a55643ad19f8f2）
```

### sprout

```
$ git发芽发展
分支大师发展.
```

### harvest

```
$ git Harvest开发
嫁接来自发展.
正在更新e4f08f4..64b3563
Fast-forward
  package.json |  2 +-
 更改1个文件，1个插入（+），1个删除（-）
恢复本地更改.
在分支机构主管
您的分支比“源/主”提前1次提交.
  （使用“ git push”发布您的本地提交）
无需提交，工作目录干净
藏匿@@ {0}（7c28b7f5eaf09dd72ec6e1ea440cbd1611e36c7f）
```

### graft

```
$ git移植开发
切换到主站.
您的分支比“源/主”提前2次提交.
  （使用“ git push”发布您的本地提交）
嫁接发展成高手.
通过“递归”策略进行合并.
  功能|  0
 更改1个文件，0个插入（+），0个删除（-）
 创建模式100644功能
已删除分支开发（为6a022ba）.
```

### publish

```
$ git发布
   4.0（已发布）
   更新日志（已发布）
   一切都不尽人意（已发布）
*硕士（未出版）
找不到分支，使用当前分支母版
出版大师.
设置了分支母版，以从源头跟踪远程分支母版.
```

### unpublish

```
$ git取消发布主文件
正在发布主版.
```


## [git-when-merged](https://github.com/mhagger/git-when-merged)

```
合并时的$ git a2c9e695ecf3600f21fa731e705fd1a0503632d9
裁判/头部/主球5a2ec1b1a6633f830bd4a2b1daab578c062e6975
合并时的git $ HEAD
refs / heads / master Commit直接在此分支上.
```


## [git-playback](https://github.com/jianli/git-playback)

```
$ git回放README.md
```

![](https://camo.githubusercontent.com/9abe1d2de474dbc0d1ad4f48acf9e954ff0d0b30/68747470733a2f2f7261772e6769746875622e636f6d2f6a69616e6c692f6769742d706c61796261636b2f6d61737465722f616e696d6174696f6e2e676966)


## [git-branch-status](https://github.com/alexdavid/git-branch-status)

```
$ git branch-status
 4.0 [在母版前面57和在母版后面38] [与origin / 4.0保持最新]
 母版[当前分支] [比原版/母版领先1]
```


## [git-open](https://github.com/paulirish/git-open)

```
$ git打开
&gt;打开https://github.com/REMOTE_ORIGIN_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git向上游开放
&gt;打开https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git打开上游主机
&gt;打开https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master
```


## [git-my](https://github.com/davidosomething/git-my)

```
$ git我

+------------------------------------------------------------------------------+
 |  您的名字的远程分支git @ repo：repopath / reponame.git |
+------------------------------------------------------------------------------+

    本地副本？  在主人？  分店名称
   ....... [合并].  EC-242
   ..... [本地] .... [合并].  commonjs-lazyload
  ..... [local] ............. enqueue-gpt
  ......................... defunct-ios-app-nag
  ..... [本地] .............因子束
```


## [git-ink](https://github.com/davidosomething/git-ink)

```
$ git墨水

•enqueue-gpt ........................................... 2015-08 -31
•因子束................................................. 2015-10-14
    -将更多模块拉入node_modules
    -可行，但不会带来任何收益
•hbsfy ...................................................... .2015-10-21
✓大师................................................ 2015-10-22
•ads4…………………………………………. 2015-10-22
•remove-equalize_content_height ........................ 2015-10-21
•锻炼身体........................................... 2015-10-21
    -需要干燥驱魔功能
    -丑化后无法正确映射
    -需要撤消postCSS映射更改
•rm-convert_dates-order ................................ 2015-10-22
•sass-lint .................................... 2015年-10-14
    -模块不起作用
```


## [recursive-blame](https://github.com/scottgonzalez/recursive-blame)

```
$ git recursive-blame版本package.json

提交：247479d017f138c26be27c64a0ce27f5f21fc0af
作者：杰夫·克罗斯<middlefloor@gmail.com>
日期：2015年10月13日星期二15:58:13（7周前）
路径：package.json
匹配：1之1

    琐事（释放）：弯角版本到alpha.42

1) {
2）“ name”：“ angular”，
3）“版本”：“ 2.0.0-alpha.42”，
4）“ branchPattern”：“ 2.0.*”，
5）“ description”：“ Angular 2-现代Web应用程序的Web框架”，
6）“主页”：“ https://github.com/angular/angular”，
7）“错误”：“ https://github.com/angular/angular/issues”，

 下一个动作[r，n，p，c，d，q ,?]？  [R

提交：bb9d299b3860f6d579192828451ccd7ace70e1d8
作者：Igor Minar <igor@angularjs.org>
日期：2015年10月13日星期二12:28:03（-07星期前）
路径：package.json
匹配：1之1

    琐事（释放）：弯角版本到alpha.41

1) {
2）“ name”：“ angular”，
3）“版本”：“ 2.0.0-alpha.41”，
4）“ branchPattern”：“ 2.0.*”，
5）“ description”：“ Angular 2-现代Web应用程序的Web框架”，
6）“主页”：“ https://github.com/angular/angular”，
7）“错误”：“ https://github.com/angular/angular/issues”，
```


## [hyper-blame](https://commondatastorage.googleapis.com/chrome-infra-docs/flat/depot_tools/docs/html/git-hyper-blame.html)


```
$ git hyper-blame -i 3ddda43c ipsum.txt
c6eb3bfa（LOREM 2014年8月11日23点15分57秒0000 1）Lorem存有胡萝卜，明尼阿波利斯
134200d1（LOREM 2014年4月10日8点54分46秒+0000 2 *）ADIPISCING客户，你做那种TEMPOR
a34a1d0d（2014年4月11日11时25分04秒+0000非常3a）和活力，劳动和肥胖
 134200d1（LOREM 2014年4月10日8点54分46秒0000 4 *）功能.  多年来VENIAM，“是谁？
c6eb3bfa（LOREM 2014年8月11日23点15分57秒+0000 5）Nostrud例行学区LABORIS
0f0d17bd（ATM 2014年6月2日11时31分48秒+0000 6 *），除了从它aliquipis优势.
```


## [git-word-blame](https://framagit.org/mdamien/git-word-blame)


```
$ git word-blame README.md
导致/ tmp / word-blame-output /
 -author_stats.tsv
 -commit_stats.tsv
 -word-blame-by-commit.html
 -word-blame-by-author.html
 -文字输出
```

![git word-blame on this README](https://user-images.githubusercontent.com/1469823/57202569-0247eb00-6fa7-11e9-8549-f55d81299fab.png)



## [git-fire](https://github.com/qw3rtman/git-fire)

```
$ git fire
切换到新分支&#39;fire-master-maochenyan@gmail.com-1451379915&#39;
在分支上fire-master-maochenyan@gmail.com-1451379915
无需提交，工作目录干净
计数对象：2，完成.
 写入对象：100％（2/2），168个字节|  0字节/秒，完成.
总计2（增量0），重用0（增量0）
到git@bitbucket.org：maochenyan / fire.git
 * [新分支] fire-master-maochenyan@gmail.com-1451379915-&gt; fire-master-maochenyan@gmail.com-1451379915
分支机构fire-master-maochenyan@gmail.com-1451379915设置为从源跟踪远程分支机构fire-master-maochenyan@gmail.com-1451379915.


离开大楼！
```


## [git-town](https://github.com/Originate/git-town)

待定-PR欢迎您！


## [git-blame-someone-else](https://github.com/jayphelps/git-blame-someone-else)

```
 $ git blame-someone-else&#39;史蒂夫·毛 <maochenyan@gmail.com>  &#39;2efb4e3a061a2e8aaa58033e9c13c3e0e5fcde4b
 史蒂夫·毛（Steve Mao）现在​​是2efb4e3的作者.  你真是个混蛋
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
“ .gitsecret /”已创建.
```

### git secret tell

```
$ git secret告诉my@email.com
 完成.  my@email.com被添加为知道秘密的人.
打扫干净...
```

### git secret add

```
$ git secret add hideme.txt
添加了1个项目.
```

### git secret list

```
$ git秘密列表
hideme.txt
```

### git secret hide

```
$ git secret hide
 完成.  全部1个文件被隐藏.
```

### git secret reveal

```
$ git secret揭示

您需要一个密码短语才能解锁
 用户：“测试用户 <my@email.com>  ”
2048-bit RSA key, ID #######, created 2015-01-01 (main key ID #######)

gpg：gpg-agent在此会话中不可用
 文件“ hideme.txt”存在.  覆盖？  （y / N）y
 完成.  全部1个文件都显示出来.
```


## [git-secrets](https://github.com/awslabs/git-secrets)

&gt;防止您将密码和其他敏感信息提交到git存储库.

待定-PR欢迎您！


## [git-fixup](https://github.com/keis/git-fixup)

```
$ git diff --cached -U0
diff --git a / README.md b / README.md
索引0c700d1..7a57cef 100644
---一个/README.md
+++ b/README.md
@@ -1330 +1330 @@ $ git秘密隐藏
 -做.  全部1个文件被隐藏.
 +完成.  所有3个文件都被隐藏.
$ git fixup 6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8
24aa3d9c10cc02fe813dc83d1ac792cc2e7d705d [F]添加git-stats屏幕截图<maochenyan@gmail.com>
6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8 [L]更改了带有文本的gif <mail@sobolevn.me>
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

在*交互式*基础上编辑提交元信息.

git-fiddle（1）是git-rebase（1）的轻量级包装
用*作者*日期，作者姓名注释每个提交
 作为提交消息.  然后对其中任何一项进行更改
在git-rebase序列中使用“ exec”脚本.

Usage:
  $ SCRIPT [-[no-]-fiddle-messages] [args ...]

Options:
   -[no-] fiddle-messages不编辑提交消息.  对快速编辑很有用
                          创作或约会.  也可以使用
                         `git config fiddle.messages`.
  [args ...]这些参数逐字传递给git-rebase.
```


## [git-user](https://github.com/gesquive/git-user)

```
## add a work profile for Henry
$ git用户添加工作“ Henry Jekyll博士” henry@jekyll.com
添加了个人资料“工作”

## add a personal profile for Edward
$ git用户添加主页“ Edward Hyde” hyde@night.com
添加了个人资料“家”

## list out our saved profiles
$ git用户列表
全球概况：
  用户：亨利<hjekyll@gmail.com>

保存的个人资料：
  家：爱德华·海德<hyde@night.com>
  工作：亨利·杰基尔博士<henry@jekyll.com>

## set the current git repository user to the home profile
$ git用户设置为home
 “项目”存储库的用户也已设置为“爱德华·海德” <hyde@night.com>  &#39;

## list profiles again, notice how the current repository profile is now set
$ git用户
项目简介：
  路径：/ path / to / git / project
  用户：Edward Hyde <hyde@night.com>

保存的个人资料：
  家：爱德华·海德<hyde@night.com>
  工作：亨利·杰基尔博士<henry@jekyll.com>
```


## [gitsome](https://github.com/donnemartin/gitsome)

待定-PR欢迎您！


## [git-hound](https://github.com/ezekg/git-hound)

待定-PR欢迎您！


## [git-recall](https://github.com/Fakerr/git-recall)

![](https://camo.githubusercontent.com/eb306717b95724c33dd0de91faa535a4818cc7d0/687474703a2f2f696d6775722e636f6d2f7a7577324c71572e676966)

```
$ git回忆
## By default (without options), the command will display commits from yesterday and
## for the current user.

$ git Recall -d 5 -a“ Doge”
## Show all Doge's commits from 5 days ago.

$ git Recall -d 5 -a“全部”
## Show commits of all contributors from 5 days ago.

$ git Recall -f
## Fetch commits beforehand.
```


## [git-standup](https://github.com/kamranahmedse/git-standup)

```
$ git站立
2f50b39c-文档（提交消息）：使用commitizen生成常规提交（12小时前） <Steve Mao>
9af3600e-修复测试（12小时前） <Steve Mao>
7f17ba97-文档：标题案例（12小时前） <Steve Mao>
a6d6203c-打开搜索时不滚动（12小时前） <Steve Mao>
53fe681a-琐事（pkg）：添加回购网址（12小时前） <Steve Mao>
5e952ac0-字幕应该是通用的（13小时前） <Steve Mao>
 adbc5423-将ci / cd添加到自述文件中.  （13小时前） <Steve Mao>
a1097116-向自述文件添加版本控制（14小时前） <Steve Mao>
6b6e7465-添加测试覆盖率（15小时前） <Steve Mao>
```


## [commitizen](https://github.com/commitizen/cz-cli)

```
$去cz
cz-cli@2.9.6, cz-conventional-changelog@1.2.0


 第1行将裁剪为100个字符.  所有其他行将在100个字符后换行.

 ？  选择您要提交的更改类型：（使用箭头键）
❯壮举：一项新功能
  修复：一个错误修复
  docs：仅文档更改
  样式：不会影响代码含义的更改（空格，格式，缺少半角
-冒号等）
  重构：既不修正错误也不增加功能的代码更改
  性能：代码更改可提高性能
  测试：添加缺失的测试或更正现有的测试
```


## [git-fresh](https://github.com/imsky/git-fresh)

待定-PR欢迎您！

## [git-fs](https://github.com/freddi301/git-fs)

```
$ git fs
在./git/fs上挂载只读文件系统
```

## [git-url](https://github.com/zdharma/git-url)

### git url

```
$ cd〜/ github / git-url.git
$ git网址
编码... INPUT是下一段：

通讯协定：https
网站：github.com
回购：zdharma / git-url
修订：大师

gitu://ҝjȩMżEäḝЃȣϟṈӛŀї

$ git url -r v1.0
编码... INPUT是下一段：

通讯协定：https
网站：github.com
回购：zdharma / git-url
修订版：v1.0

gitu://ŪĪАϔEäḝЃȣϟṈӛŀї

$ git url -q -p lib/common.sh	# -q - quiet, -p - path
gitu://eḶȸṋ0oǗȟЗÛjȩMżEäḝЃȣϟṈӛŀї

$ git url //eḶȸṋ0oǗȟZÛjȩMżEäḝЃȣϟṈӛŀі
解码...输出为：

通讯协定：https
网站：github.com
回购：zdharma / git-url
修订：大师
文件：lib / common.sh

https://github.com/zdharma/git-url
```
 
### git guclone

```
$ git guclone
为版本v1.0克隆URL https://github.com/zdharma/git-url

克隆到&#39;git-url&#39;...
remote：计数对象：144，已完成.
远程：压缩对象：100％（111/111），已完成.
远程：总数144（增量71），重用102（增量32），包重用0
 接收物体：100％（144/144），116.43 KiB |  125.00 KiB / s，已完成.
解决增量：100％（71/71），已完成.

正在检出修订/参考v1.0 ...确定
HEAD位于：5d10a204，创建目录git-url
```


## [git-signatures](https://github.com/hashbang/git-signatures)

### signatures add --push

```
$ git签名添加--push v1.0.0
更新了标签“ v1.0.0”（原为4de5afd）
枚举对象：4，完成.
计数对象：100％（4/4），已完成.
增量压缩最多使用8个线程
压缩对象：100％（3/3），已完成.
 写入对象：100％（3/3），906字节|  906.00 KiB / s，已完成.
总计3（增量1），重用0（增量0）
到git@github.com：jsmith / test-signatures
   4b5300d..5b1f2cd参考/注释/签名-&gt;参考/注释/签名
 + 4de5afd ... 5b1f2cd v1.0.0-&gt; v1.0.0（强制更新）
```


### signatures verify

```
$ git签名验证v1.0.0
```


### signatures verify --min-count 2

```
$ git签名验证--min-count 2 v1.0.0
无法找到足够的经过验证的签名来满足：min_count = 2

签名验证可能仅由于您的本地gnupg而失败
keychain和trustdb不包含必需的密钥.

有关详细的签名状态，请运行：

&gt; git签名显示
```


### signatures show

```
$ git签名显示v1.0.0
  公钥ID |  现状  信任|  日期|  签名人姓名
=======================================================================================================================
 01234567890ABCDEF |  VALIDSIG |  终极  美国东部时间2018年11月10日13:16:10 |  史蒂夫·毛 <maochenyan@gmail.com>
 ```

## [git-profile](https://github.com/dm3ch/git-profile-manager)
### add a work profile
```
$ git个人资料添加工作
姓名：姓
电子邮件：name@work-domain.com
签名密钥：
个人资料工作已成功添加
```

### add a personal profile
```
$ git个人资料添加首页-n“姓氏” -e name@gmail.com
个人资料主页已成功添加
```

### list out our saved profiles
```
$ git个人资料列表
现有配置文件：
work
home
```

### set the current git repository user to the home profile
```
$ git个人资料使用工作
```
如果成功，目前将没有任何输出

## [git-revise](https://github.com/mystor/git-revise)

待定-PR欢迎您！

## [filter-repo](https://github.com/newren/git-filter-repo)

待定-PR欢迎您！


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Steve Mao](https://github.com/stevemao) 放弃了此作品的所有版权以及相关或邻近的权利.
