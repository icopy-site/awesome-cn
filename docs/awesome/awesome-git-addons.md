<div class="github-widget" data-repo="stevemao/awesome-git-addons"></div>
## Awesome git addons [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

扩展/增强 git CLI 的附加组件的精选列表.

```
$ git bla
很棒的事情发生了！
```

 &gt; _“你不必什么都知道. 您只需要知道在必要时在哪里可以找到它.”  （约翰布伦纳）_

灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列出事情.

 **注意**：某些命令可能无法开箱即用. 您可能需要运行安装后脚本来添加别名或手动添加它们.





## [git-extras](https://github.com/tj/git-extras)

### squash

```
$ git squash 固定光标样式“固定光标样式”
$ git 南瓜 95b7c52
$ git 南瓜头~3
```

### summary

```
$ git 总结

 项目：git
 回购年龄：10 年
 活动：11868 天
 提交：40530
 文件：2825
 作者：
 15401 朱尼奥 C 滨野 38.0%
  1844 杰夫·金 4.5%
```

### line-summary

```
$ git 行摘要

 项目：一饮而尽
 线路：3900
 作者：
 1040 反对 26.7%
  828 辛德雷·苏胡斯 21.2%
```

### effort

```
$ git 努力

  文件提交活跃天数

  .git 属性...................... 3 3
  .gitignore ..................... 265 226
  .mailmap ..................................... 47 40
```

### authors

```
$ git 作者
反对<contra@maricopa.edu>
埃里克·肖夫斯托尔<contra@wearefractal.com>
真诚的蜀黍<sindresorhus@gmail.com>
```

### changelog

```
$ git 变更日志
## 3.9.0

- 添加 babel 支持
- 添加转译器回退支持
- 添加对一些重命名的转译器（livescript 等）的支持
- 添加 JSCS
- 更新依赖项（启动、解释）
- 文档调整

## 3.8.11

- 修复节点 0.12/iojs 问题
- 将节点 0.12 和 iojs 添加到 travis
- 更新依赖项（liftoff、v8flags）
- 文档调整
```

### commits-since

```
$ git 从昨天开始提交
...自昨天以来的变化
TJ Holowaychuk - 固定自述文件
```

### count

```
$ git 计数
总计 855
```

### create-branch

```
$ git 创建分支开发
总计 3（delta 0），重复使用 0（delta 0）
到 https://github.com/tj/git-extras.git
 * [新分支] HEAD -&gt; 开发
分支开发设置为从源头跟踪远程分支开发.
切换到新分支“开发”
```

### delete-branch

```
$ git 删除分支集成
删除了分支集成（原为 bfb8522）.
删除了远程跟踪分支远程/集成（原为 bfb8522）.
到 git@github.com:remote/gulp.git
 - [删除] 集成
```

### delete-submodule

```
$ git delete-submodule lib/foo
```

### delete-tag

```
$ git 删除标签 v0.1.1
删除标签“v0.1.1”（原为 9fde751）
到 https://github.com/tj/git-extras.git
 - [删除] v0.1.1
```

### delete-merged-branches

```
$ git 删除合并分支
删除的功能/主题（原为 c029ab3）.
删除了 feature/live_preview（原为 a81b002）.
删除的功能/仪表板（原为 923befa）.
```

### fresh-branch

```
$ git 新分支文档
删除 .DS_Store
删除 .editorconfig
删除 .gitignore
```

### guilt

```
$ git guilt `git log --until=&quot;3 weeks ago&quot; --format=&quot;%H&quot; -n 1` HEAD
保罗·施赖伯 +++++++++++++++++++++++++++++++++++++++++++++++(349)
太空漫游++++++++++++++++++++++++++++++++++++++++++++++++(113)
马克艾斯勒++++++++++++++++++++++++++
```

### merge-into

```
$ git 合并到 master
切换到分支“master”
你的分支是最新的&#39;origin/master&#39;.
更新 9fde751..e62edfa
Fast-forward
 234 | 0
 1 个文件已更改，0 个插入 (+)，0 个删除 (-)
 创建模式 100644 234
切换到分支“开发”
```

### graft

```
$ git graft development
你的分支是最新的&#39;origin/master&#39;.
通过“递归”策略进行合并.
 包.json |  2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
删除了分支开发（原为 64b3563）.
```

### alias

```
$ git 别名 last “cat-file commit HEAD”
$ 其他
last = cat 文件提交 HEAD
```

### ignore

```
$ git 忽略构建“*.o”“*.log”
... 添加了“构建”
... 添加 &#39;*.o&#39;
... 添加了“*.log”
```

### info

```
$ git 信息

    ##远程网址：

    来源 git@github.com:sampleAuthor/git-extras.git（获取）
    来源 git@github.com:sampleAuthor/git-extras.git（推送）

    ##远程分支机构：

    原点/HEAD -&gt; 原点/主人
    起源/我的分支

    ##本地分支机构：

    我的分行
    * 掌握

    ##最近的提交：

    提交 e3952df2c172c6f3eb533d8d0b1a6c77250769a7
    作者：样本作者<sampleAuthor@gmail.com>

    添加了 git-info 命令.

    键入“git log”以获得更多提交，或键入“git show”<commit id>  &#39; 获取完整的提交详细信息.

    ##配置（.git/配置）：

    color.diff=自动
    color.status=自动
```

### fork

```
$ git fork LearnBoost/expect.js
```

### release

```
$ git 发布 0.1.0
... 发布 0.1.0
关于分支开发
您的分支机构是最新的“起源/发展”.
无需提交，工作目录干净
总计 0（delta 0），重复使用 0（delta 0）
到 https://github.com/tj/git-extras.git
   9fde751..e62edfa 主机 -&gt; 主机
计数对象： 1、完成.
写入对象：100% (1/1)，166 字节 |  0 字节/秒，完成.
总计 1（delta 0），重复使用 0（delta 0）
到 https://github.com/tj/git-extras.git
 * [新标签] 0.1.0 -&gt; 0.1.0
... 完全
```

### contrib

```
$ git contrib 视觉媒体
视觉媒体（18）：
  导出 STATUS_CODES
  用 Array.prototype.unshift.call() 替换了几个 Array.prototype.slice.call() 调用
  将帮助信息移至节点回复
```

### repl

```
$ git 回复

git&gt; ls 文件
History.md
Makefile
```

### undo

```
$ git 撤消
重置后未暂存的更改：
M包.json
自述文件.md
```

### gh-pages

```
$ git gh-页面
```

### scp

```
$ git scp 暂存头
```

### setup

```
$ git 设置
在 /GitHub/test/gulp/.git/ 中初始化空 Git 存储库
[master (root-commit) 9469797] 初始提交
 更改了 69 个文件，插入了 3900 个(+)
 创建模式 100644 .editorconfig
 创建模式 100644 .gitignore
 创建模式 100644 .jscsrc
```

### touch

```
$ git touch index.js
```

### obliterate

```
$ git 抹杀 secrets.json
重写 2357a4334051a6d1733037406ab7538255030d0b (1/981)rm &#39;secrets.json&#39;
重写 b5f62b2746c23150917d346bd0c50c467f01eb03 (2/981)rm &#39;secrets.json&#39;
重写 3cd94f3395c2701848f6ff626a0a4f883d8a8433 (3/981)rm &#39;secrets.json&#39;
```

### feature|refactor|bug|chore

```
$ git 功能依赖
$ git 功能完成依赖
已经是最新的了.
删除分支功能/依赖项（原为 f0fc4c7）.
删除了远程跟踪分支来源/功能/依赖项（原为 f0fc4c7）.
这个 git@github.com:stevemao/gulp.git
 - [删除] 功能/依赖项
```

### local-commits

```
$ git 本地提交
提交 5f00a3c1bb71876ebdca059fac96b7185dea5467
合并：7ad3ef9841af4e
添加一名作者<blaine@iceddev.com>
日期：2015 年 8 月 20 日星期四 11:35:15 -0700

    Merge pull request #1211 from JimiHFord/patch-1

    更新指南.md

提交 841af4ee7aaf55b505354d0e86d7fb876d745e26
作者：吉米·福特<JimiHFord@users.noreply.github.com>
日期：2015 年 8 月 20 日星期四 11:55:38 -0400

    更新指南.md

    固定错别字
```

### archive-file

```
$ git 归档文件
在分支“master”上建立档案
保存到“gulp.v3.9.0-36-g47cb6b0.zip”（60K）
```

### missing

```
$ git 缺少主人
< d14b8f0 only on current checked out branch
&gt; 97ef387 仅在主机上
```

### lock

```
$ git lock config/database.yml
```

### locked

```
$ git 锁定
config/database.yml
```

### unlock

```
$ git unlock config/database.yml
```

### reset-file

```
$ git reset-file README.md HEAD^
将“README.md”重置为 HEAD^
```

### pr

```
$git 公关 226
来自 https://github.com/tj/git-extras
 * [新参考] refs/pulls/226/head -&gt; pr/226
切换到分支 &#39;pr/226&#39;
```

### root

```
$ 混帐根
/GitHub/git
```

### delta

```
$ git 增量
README.md
```

### merge-repo

```
$ git merge-repo git@github.com:tj/git-extras.git master .
git fetch git@github.com:tj/git-extras.git master
警告：没有共同的提交
远程：计数对象：3507，完成.
远程：压缩对象：100% (5/5)，完成.
远程：总计 3507（增量 1），重复使用 0（增量 0），打包重复使用 3502
接收对象：100% (3507/3507), 821.12 KiB |  286.00 KiB/s，完成.
解决增量：100% (1986/1986)，完成.
来自 github.com:tj/git-extras
 * 分支主机 -&gt; FETCH_HEAD
添加目录&#39;git-merge-repo.E95m0gj&#39;
没有要保存的本地更改
```

### psykorebase

```
$ git psykorebase 大师
$ git psykorebase --继续
$ git psykorebase 主功能
```


## [gitflow (AVH Edition)](https://github.com/petervanderdoes/gitflow-avh)

### flow init

```
$ git 流初始化

应该使用哪个分支来发布生产版本？
   - 变更日志
   - 掌握
生产版本的分支名称：[master]

应该使用哪个分支来集成“下一个版本”？
   - 变更日志
“下一个版本”开发的​​分支名称：[master]
生产和集成分支应该不同.
```

### flow feature

```
$ git 流功能
$ git flow 特性启动 awesome-feature
$ git 流功能完成 awesome-feature
$ git flow feature 删除 awesome-feature

$ git flow feature publish awesome-feature
$ git flow feature pull remote awesome-feature
```

### flow release

```
$ git 流发布
$ git flow release 启动 awesome-release
$ git flow release 完成 awesome-release
$ git flow release 删除 awesome-release
```

### flow hotfix

```
$ git 流修补程序
$ git flow hotfix 启动 awesome-release
$ git flow hotfix 完成 awesome-release
$ git flow hotfix 删除 awesome-release
```

### flow support

```
$ git 流支持
```


## [git-up](https://github.com/aanand/git-up)

```
$ 起床
获取来源
4.0快进...
上游之前的变更日志
掌握快进...
回到 4.0
```


## [hub](https://github.com/github/hub)

### clone

```
$ git 克隆 schacon/ticgit
&gt; git 克隆 git://github.com/schacon/ticgit.git

$ git clone -p schacon/ticgit
&gt; git clone git@github.com:schacon/ticgit.git

$ git 克隆和 res
&gt; git 克隆 git@github.com/YOUR_USER/resque.git
```

### remote add

```
$ git 远程添加 rtomayko
&gt; git 远程添加 rtomayko git://github.com/rtomayko/CURRENT_REPO.git

$ git remote add -p rtomayko
&gt; git 远程添加 rtomayko git@github.com:rtomayko/CURRENT_REPO.git

$ git 远程添加源
&gt; git 远程添加源 git://github.com/YOUR_USER/CURRENT_REPO.git
```

### fetch

```
$ git fetch 米斯拉夫
&gt; git remote add mislav git://github.com/mislav/REPO.git
&gt; git 获取 mislav

$ git fetch mislav,xoebus
&gt; git 远程添加 mislav ...
&gt; git 远程添加 xoebus ...
&gt; git fetch --multiple mislav xoebus
```

### cherry-pick

```
$ git cherry-pick https://github.com/mislav/REPO/commit/SHA
&gt; git remote add -f --no-tags mislav git://github.com/mislav/REPO.git
&gt; git cherry-pick SHA

$ git cherry-pick mislav@SHA
&gt; git remote add -f --no-tags mislav git://github.com/mislav/CURRENT_REPO.git
&gt; git cherry-pick SHA

$ git cherry-pick mislav@SHA
&gt; git 获取 mislav
&gt; git cherry-pick SHA
```

### am

```
$ git 是 https://github.com/github/hub/pull/55
[ 通过 API 下载补丁 ]
&gt; git am /tmp/55.补丁

$ git am --ignore-whitespace https://github.com/davidbalbert/hub/commit/fdb9921
[ 通过 API 下载补丁 ]
&gt; git am --ignore-whitespace /tmp/fdb9921.patch
```

### apply

```
$ git 申请 https://gist.github.com/8da7fb575debd88c54cf
[ 通过 API 下载补丁 ]
&gt; git 应用/tmp/gist-8da7fb575debd88c54cf.txt
```

### fork

```
$ git 叉子
[ 回购在 GitHub 上分叉 ]
&gt; git 远程添加-f YOUR_USER git@github.com:YOUR_USER/CURRENT_REPO.git
```

### pull-request

```
$ git 请求请求
[打开文本编辑器编辑请求的标题和正文]
[在 GitHub 上为“YOUR_USER:feature”打开拉取请求]
```

### checkout

```
$ git checkout https://github.com/github/hub/pull/73
&gt; git remote add -f --no-tags -t feature mislav git://github.com/mislav/hub.git
&gt; git checkout --track -B mislav-feature mislav/feature
```

### merge

```
$ git 合并 https://github.com/github/hub/pull/73
&gt; git fetch git://github.com/mislav/hub.git +refs/heads/feature:refs/remotes/mislav/feature
> git merge mislav/feature --no-ff -m 'Merge pull request #73 from mislav/feature...'
```

### create

```
$ git 创建
[在 GitHub 上创建的回购协议]
&gt; git 远程添加源 git@github.com:YOUR_USER/CURRENT_REPO.git
```

### init

```
$ git 初始化 -g
&gt; 很热
&gt; git 远程添加源 git@github.com:YOUR_USER/REPO.git
```

### push

```
$ git push origin,staging,qa bert_timeout
&gt; git 推送原点 bert_timeout
&gt; git 推送暂存 bert_timeout
&gt; git push qa bert_timeout
```

### browse

```
$ git 浏览
&gt; 打开 https://github.com/YOUR_USER/CURRENT_REPO
```

### compare

```
$ git 比较重构
&gt; 打开 https://github.com/CURRENT_REPO/compare/refactor
```

### submodule

```
$ git 子模块添加 wycats/bundler 供应商/bundler
&gt; git 子模块添加 git://github.com/wycats/bundler.git vendor/bundler
```

### ci-status

```
$ git ci状态
success
```


## [git-deploy](https://github.com/mislav/git-deploy)

```
$ git remote add production &quot;user@example.com:/apps/mynewapp&quot;
$ git deploy setup -r &quot;production&quot;
$ git 部署初始化
$ git push 生产大师
```


## [git-cal](https://github.com/k4rthik/git-cal)

![68747470733a2f2f7261772e6769746875622e636f6d2f6b34727468696b2f6769742d63616c2f6d61737465722f73637265656e73686f74732f696d67322e706e67](https://cloud.githubusercontent.com/assets/6316590/12465623/17d828ea-c023-11e5-8077-2e9a284defd6.png)


## [git-hooks](https://github.com/git-hooks/git-hooks)

```
$ git hooks --install
$ git 钩子
Git 钩子安装在这个存储库中.

列出用户、项目和全局挂钩：
---
/Users/stevemao/.git_hooks:

/GitHub/git-hooks/git_hooks:
commit-msg/signed-off-by - 检查提交消息中是否存在 Signed-off-by 行.
pre-commit/bsd - 检查 BSD 许可证.

/GitHub/git-hooks/.githooks:
```


## [git-imerge](https://github.com/mhagger/git-imerge)

### imerge start

```
$ git imerge start --name=next --goal=merge --first-parent 4.0
正在尝试自动合并 1-1...成功.
正在尝试自动合并 1-29...成功.
正在尝试自动合并 1-44...成功.
正在尝试自动合并 1-51...成功.
```

### imerge merge

```
$ git imerge 合并 4.0
正在尝试自动合并 1-1...成功.
正在尝试自动合并 1-6...成功.
正在尝试自动合并 1-9...成功.
正在尝试自动合并 1-10...成功.
```

### imerge rebase

```
$ git 合并狐狸 4.0
待合并分支上的以下提交是合并提交：
    8e4931ae15971a14897cf347ac50b7d7fe125ac4
    d7c772142ce663a20210db73d9ad17cc8d59e0d6
    856df83c77b33029d2ddfb8eecd08efedeadc027
```

### imerge continue

```
$ git 添加 --all
$ git 提交
[imerge/next e442618] imerge &#39;next&#39;: 手动合并 10-26
$ git imerge 继续
已记录合并 10-26 的合并.
正在尝试自动合并 10-27...成功.
尝试自动合并 10-42...失败.
尝试自动合并 10-34...失败.
尝试自动合并 10-30...成功.
记录自动填充块 MergeState(&#39;next&#39;, tip1=&#39;master&#39;, tip2=&#39;4.0&#39;, goal=&#39;merge&#39;)[18:20,34:58].
合并完成！
```

### imerge finish

```
$ git imerge 完成
以前的 HEAD 位置是 fcbe161 ... imerge &#39;next&#39;: automatic merge 19-57
切换到“下一个”分支
[next 23362e6] 将 4.0 合并到 master 中（使用 imerge）
 日期：2015 年 9 月 2 日星期三 10:59:56 +1000
```

### imerge diagram

```
$ git imerge 图
********************
*????????.?????????|
*????????.?????????|
*????????.?????????|
*????????...-------+
*????????.*|#???????
```

### imerge list

```
$ git imerge 列表
* 下一个
```

### imerge init

```
$ git imerge init --name=next --goal=merge --first-parent 4.0
```

### imerge record

```
$ git 导入记录
已记录合并 10-26 的合并.
正在尝试自动合并 10-27...成功.
尝试自动合并 10-42...失败.
尝试自动合并 10-34...失败.
```

### imerge autofill

```
$ git imerge 自动填充
正在尝试自动合并 1-1...成功.
正在尝试自动合并 1-29...成功.
正在尝试自动合并 1-44...成功.
```

### imerge simplify

```
$ git imerge 简化
之前的 HEAD 位置是 4d19598... imerge &#39;next&#39;: automatic merge 20-57
切换到“下一个”分支
[next 6c308aa] 将 4.0 合并到 master 中（使用 imerge）
 日期：2015 年 9 月 2 日星期三 13:37:31 +1000
```

### imerge remove

```
$ git imerge 删除
```

### imerge reparent

```
$ git 合并修复
67ebc0e6517ac791de6699453b71d2c7fd81ffcd
```


## [git-issue](https://github.com/dspinellis/git-issue)

### Initialize issue repository

```
$ git 问题初始化
在 /home/dds/src/gi/.issues 中初始化空问题存储库
$ git issue new -s &#39;从命令行输入的新问题&#39;
添加问题 e6a95c9
```

### Create a new issue (opens editor window)

```
$ git 问题新
添加问题 7dfa5b7
```

### List open issues

```
$ git 问题列表
7dfa5b7 编辑输入的问题
e6a95c9 从命令行输入的新问题
```

### Add an issue comment (opens editor window)

```
$ git 问题评论 e6a95c9
添加评论 8c0d5b3
```

### Add tag to an issue

```
$ git 问题标签 e6a9 紧急
添加标签紧急
```

### Add two more tags

```
$ git 问题标签 e6a9 gui 崩溃
添加标签 gui
添加标签崩溃
```

### Remove a tag

```
$ git 问题标签 -r e6a9 紧急
删除标签紧急
```

### Assign issue

```
$ git 问题分配 e6a9 joe@example.com
分配给 joe@example.com
```

### Add issue watcher

```
$ git 问题观察者 e6a9 jane@example.com
添加了观察者 jane@example.com
```

### List issues tagged as gui

```
$ git 问题列表 gui
e6a95c9 从命令行输入的新问题
```

### Push issues repository to a server

```
$ git issue git remote add origin git@github.com:dspinellis/gi-example.git
$ git 问题 git push -u origin master
清点对象：60，完成.
压缩对象：100% (50/50)，完成.
写入对象：100% (60/60)，5.35 KiB |  0 字节/秒，完成.
总计 60（delta 8），重复使用 0（delta 0）
到 git@github.com:dspinellis/gi-example.git
 * [新分支] master -&gt; master
Branch master 设置为从源头跟踪远程分支 master.
```

### Clone issues repository from server

```
$ git 问题克隆 git@github.com:dspinellis/gi-example.git 我的问题
克隆到&#39;.issues&#39;......
远程：计数对象：60，完成.
远程：压缩对象：100% (42/42)，完成.
远程：总计 60（delta 8），重复使用 60（delta 8），打包重复使用 0
接收对象：100% (60/60), 5.35 KiB |  0 字节/秒，完成.
解决增量：100% (8/8)，完成.
检查连接...完成.
将 git@github.com:dspinellis/gi-example.git 克隆到我的问题中
```

### List open issues

```
$ git 问题列表
7dfa5b7 编辑输入的问题
e6a95c9 从命令行输入的新问题
```

### Create new issue

```
$ git issue new -s &#39;在另一台主机上添加问题&#39;
添加问题 abc9adc
```

### Push changes to server

```
$ git 问题推送
数对象：7个，完成.
压缩对象：100% (6/6)，完成.
写入对象：100% (7/7)，767 字节 |  0 字节/秒，完成.
总计 7（delta 0），重复使用 0（delta 0）
到 git@github.com:dspinellis/gi-example.git
   d6be890..740f9a0 主人 -&gt; 主人
```

### Show issue added on the other host

```
$ git 问题显示 7dfa5b7
问题 7dfa5b7f4591ecaa8323716f229b84ad40f5275b
添加一名作者<dds@aueb.gr>
日期：2016 年 1 月 29 日星期五 01:03:24 +0200
标签： 开放

    编辑器输入的问题

    这是一个更长的描述.
```

### Show issue and comments

```
$ git 问题显示 -c e6a95c9
发行 e6a95c91b31ded8fc229a41cc4bd7d281ce6e0f1
添加一名作者<dds@aueb.gr>
日期：2016 年 1 月 29 日星期五 01:03:20 +0200
标签： 打开 紧急 gui 崩溃
观察者：jane@example.com
分配给：joe@example.com

    从命令行输入的新问题

评论 8c0d5b3d77bf93b937cb11038b129f927d49e34a
添加一名作者<dds@aueb.gr>
日期：2016 年 1 月 29 日星期五 01:03:57 +0200

    关于这个问题的第一个评论.
```

### Pull in remote changes (on the original host)

```
$ git 问题拉取
远程：计数对象：7，完成.
远程：压缩对象：100% (6/6)，完成.
远程：总计 7（增量 0），重复使用 7（增量 0），打包重复使用 0
拆包对象：100% (7/7)，完成.
来自 github.com:dspinellis/gi-example
   d6be890..740f9a0 主人 -&gt; 起源/主人
更新 d6be890..740f9a0
Fast-forward
 问题/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/描述 |  1 +
 问题/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/标签 |  1 +
 更改了 2 个文件，插入了 2 个 (+)
 创建模式 100644 问题/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/描述
 创建模式 100644 问题/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/标签
```

### List open issues

```
$ git 问题列表
7dfa5b7 编辑输入的问题
abc9adc 问题添加到另一台主机上
e6a95c9 从命令行输入的新问题
```

### Sub-command auto-completion

```
$ git 问题 [制表符]
分配克隆评论 git init log pull show watcher
附加关闭编辑帮助列表新推送标签
```

### Issue Sha auto-completion

```
$ git issue show [制表符]
7dfa5b7 - 编辑输入的问题
e6a95c9 - 从命令行输入的新问题
```


## [git-lfs](https://github.com/github/git-lfs)

```
$ git lfs track &quot;*.mp3&quot;
跟踪 *.mp3

$ git lfs track &quot;*.zip&quot;
跟踪 *.zip

$ git lfs 轨道
列出跟踪路径
    *.mp3 (.git 属性)
    *.zip (.git 属性)

$ git lfs untrack &quot;*.zip&quot;
取消跟踪 *.zip

$ git lfs 轨道
列出跟踪路径
    *.mp3 (.git 属性)
```


## [git-now](https://github.com/iwata/git-now)

```
$ 现在混帐
[master 1bd9ce8] [从现在开始] 2015/08/27 10:39:10
 1 file changed, 1 insertion(+), 1 deletion(-)
$ git 日志
提交 1bd9ce878a76140f7db95afd9cfd4d7befbc7243
添加一名作者<maochenyan@gmail.com>
日期：2015 年 8 月 27 日星期四 10:39:10 +1000

    [从现在开始] 2015/08/27 10:39:10

    diff --git a/package.json b/package.json
    索引 8768569..540523a 100644
    --- 一个/package.json
    +++ b/package.json
    @@ -1,7 +1,7 @@
     {
       “名称”：“吞咽”，
       &quot;description&quot;: &quot;流式构建系统&quot;,
    - “版本”：“3.9.0”，
    +“版本”：“3.10.0”，
       &quot;主页&quot;: &quot;http://gulpjs.com&quot;,
       “存储库”：“gulpjs/gulp”，
        “作者”：“分形<contact@wearefractal.com> (http://wearefractal.com/)&quot;,
```


## [git-plus](https://github.com/tkrajina/git-plus)

### multi

```
$ 混帐多
--------------------------------------------------------------------------------
执行 git status -s
--------------------------------------------------------------------------------
chalk:
	 M包.json

gulp:
	 D索引.js
```

### relation

```
$ git 关系原点/4.0
HEAD 和 origin/4.0 DIVERGED，共同点是 657213a52d5e9c19b85df6a42f76341a98c08ae8

从 657213a52d5e9c19b85df6a42f76341a98c08ae8 提交到 HEAD：
检索日志时出错 657213a52d5e9c19b85df6a42f76341a98c08ae8..HEAD
```

### old-branches

```
$ git 旧分支 -d 10
分支 4.0 早于 10 天 (139.86)！
```

### recent

```
$ git 最近
      3.64天：掌握
     11.63 天：开发
```


## [git-test](https://github.com/spotify/git-test)

```
$ git 测试 -v
4.0 ^origin/4.0 ^origin/master 将测试 2 次提交
iter 提交树结果
0000 57af4b0 f5ef0d8 通过（缓存）
0001 10ed389 434370f 通过
```


## [legit](https://github.com/kennethreitz/legit)

### branches

```
$ git 分支
   4.0（已发布）
   发展（未发表）
   一切都不是很棒（已发布）
* 硕士（已发表）
   老主人（已出版）
```

### sync

```
$ git 同步
从服务器拉取提交.
首先，倒带头以在其上重放您的工作...
快进 4.0 到 origin/4.0.
将提交推送到服务器.
```

### switch

```
$ git 切换主机
保存本地更改.
保存的工作目录和索引状态在开发中：合法：在切换分支之前隐藏.
HEAD 现在位于 f0fc4c7 合并分支 &#39;development&#39;
转为主.
你的分支是最新的&#39;origin/master&#39;.
恢复本地更改.
在分行主
你的分支是最新的&#39;origin/master&#39;.
未暂存提交的更改：
   （使用“git 添加<file> ...”更新将提交的内容）
   （使用“git checkout——<file>  ...”以放弃工作目录中的更改）

	修改：package.json

没有添加到提交的更改（使用“git add”和/或“git commit -a”）
丢弃存储@{0} (86f5dc9066ff9f69c01c77e2f5a55643ad19f8f2)
```

### publish

```
$ git 发布
   4.0（已发布）
   变更日志（已发布）
   一切都不是很棒（已发布）
* 硕士（未发表）
未找到 Branch None，使用当前分支 master
出版大师.
Branch master 设置为从源头跟踪远程分支 master.
```

### unpublish

```
$ git 取消发布大师
取消发布大师.
```


## [git-when-merged](https://github.com/mhagger/git-when-merged)

```
$ git 合并时 a2c9e695ecf3600f21fa731e705fd1a0503632d9
参考/负责人/大师 5a2ec1b1a6633f830bd4a2b1daab578c062e6975
$ git 合并时的 HEAD
refs/heads/master Commit 直接在这个分支上.
```


## [git-playback](https://github.com/jianli/git-playback)

```
$ git 回放 README.md
```

![](https://camo.githubusercontent.com/9abe1d2de474dbc0d1ad4f48acf9e954ff0d0b30/68747470733a2f2f7261772e6769746875622e636f6d2f6a69616e6c692f6769742d706c61796261636b2f6d61737465722f616e696d6174696f6e2e676966)


## [git-branch-status](https://github.com/alexdavid/git-branch-status)

```
$ git 分支状态
 4.0 [领先 57，落后 master 38] [与 origin/4.0 保持同步]
 master [当前分支] [1 在 origin/master 之前]
```


## [git-open](https://github.com/paulirish/git-open)

```
$ git 打开
&gt; 打开 https://github.com/REMOTE_ORIGIN_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git 打开上游
&gt; 打开 https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git 打开上游主机
&gt; 打开 https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master
```


## [git-my](https://github.com/davidosomething/git-my)

```
$ git 我

+------------------------------------------------------------------------------+
 | 你名字的远程分支在 git@repo:repopath/reponame.git |
+------------------------------------------------------------------------------+

   本地副本？ 在主人？ 分店名称
   .....................[合并].  EC-242
   .....[本地]..[合并].  commonjs-lazyload
  .....[本地]................ enqueue-gpt
  ................... 失效的 ios 应用程序名称
  .....[局部]................因子束
```


## [git-ink](https://github.com/davidosomething/git-ink)

```
$ git 墨水

• 排队-gpt ................................... 2015-08 -31
• 因子束...................................... 2015-10-14
    - 拉出更多模块到node_modules
    - 工作但不提供任何收益
• hbsfy................................................ . 2015-10-21
✓ 主人................................................ 2015-10-22
• nda-ads4 ............................................... ... 2015-10-22
• remove-equalize_content_height ..................... 2015-10-21
• 驱魔...................................... 2015-10-21
    - 需要DRY up驱魔功能
    - 丑化时无法正确映射
    - 需要撤消 postCSS 映射更改
• rm-convert_dates-order ..................... 2015-10-22
• sass-lint ............................................... 2015 -10-14
    - 模块不工作
```


## [recursive-blame](https://github.com/scottgonzalez/recursive-blame)

```
$ git 递归责备版本 package.json

提交：247479d017f138c26be27c64a0ce27f5f21fc0af
作者：杰夫·克罗斯<middlefloor@gmail.com>
日期：2015 年 10 月 13 日星期二 15:58:13 -0700（7 周前）
路径：package.json
匹配: 1 of 1

    杂务（发布）：将角度版本提升到 alpha.42

1) {
2）“名称”：“角”，
3）“版本”：“2.0.0-alpha.42”，
4) &quot;branchPattern&quot;: &quot;2.0.*&quot;,
5) &quot;description&quot;: &quot;Angular 2 - 现代网络应用的网络框架&quot;,
6）“主页”：“https://github.com/angular/angular”，
7）“错误”：“https://github.com/angular/angular/issues”，

下一步行动 [r,n,p,c,d,q,?]？  r

提交：bb9d299b3860f6d579192828451ccd7ace70e1d8
添加一名作者<igor@angularjs.org>
日期：2015 年 10 月 13 日星期二 12:28:03 -0700（7 周前）
路径：package.json
匹配: 1 of 1

    杂务（发布）：将角度版本提升到 alpha.41

1) {
2）“名称”：“角”，
3）“版本”：“2.0.0-alpha.41”，
4) &quot;branchPattern&quot;: &quot;2.0.*&quot;,
5) &quot;description&quot;: &quot;Angular 2 - 现代网络应用的网络框架&quot;,
6）“主页”：“https://github.com/angular/angular”，
7）“错误”：“https://github.com/angular/angular/issues”，
```


## [hyper-blame](https://commondatastorage.googleapis.com/chrome-infra-docs/flat/depot_tools/docs/html/git-hyper-blame.html)


```
$ git hyper-blame -i 3ddda43c 本身.txt
c6eb3bfa (lorem 2014-08-11 23:15:57 +0000 1) LOREM 有被爱的痛苦
134200d1 (lorem 2014-04-10 08:54:46 +0000 2*) ADIPISCING ELIT，但时间到了
a34a1d0d（本身是 2014-04-11 11:25:04 +0000 3*）它们是一项伟大的工作和痛苦
 134200d1 (lorem 2014-04-10 08:54:46 +0000 4*) 无论如何. 因为我达到了最低限度，谁
c6eb3bfa (lorem 2014-08-11 23:15:57 +0000 5) 我们的工作 练习 ULLAMCO
0f0d17bd (pain 2014-06-02 11:31:48 +0000 6*) 除非有人来自它.
```


## [git-word-blame](https://framagit.org/mdamien/git-word-blame)


```
$ git word-blame README.md
结果 /tmp/word-blame-output/
 - author_stats.tsv
 - commit_stats.tsv
 - word-blame-by-commit.html
 - word-blame-by-author.html
 - 文本输出
```

![git word-blame on this README](https://user-images.githubusercontent.com/1469823/57202569-0247eb00-6fa7-11e9-8549-f55d81299fab.png)



## [git-fire](https://github.com/qw3rtman/git-fire)

```
$ git 火
切换到新分支&#39;fire-master-maochenyan@gmail.com-1451379915&#39;
在分支 fire-master-maochenyan@gmail.com-1451379915
无需提交，工作目录干净
计数对象：2个，完成.
Writing objects: 100% (2/2), 168 bytes | 0 bytes/s, done.
总计 2（delta 0），重复使用 0（delta 0）
到 git@bitbucket.org:maochenyan/fire.git
 * [新分支] fire-master-maochenyan@gmail.com-1451379915 -&gt; fire-master-maochenyan@gmail.com-1451379915
分支 fire-master-maochenyan@gmail.com-1451379915 设置为从源跟踪远程分支 fire-master-maochenyan@gmail.com-1451379915.


离开大楼！
```


## [git-town](https://github.com/Originate/git-town)

TBD - 公关欢迎！


## [git-blame-someone-else](https://github.com/jayphelps/git-blame-someone-else)

```
 $ git blame-someone-else &#39;Steve Mao<maochenyan@gmail.com>  &#39; 2efb4e3a061a2e8aaa58033e9c13c3e0e5fcde4b
 Steve Mao 现在是 2efb4e3 的作者. 你是一个正式的混蛋.
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
$ git 秘密初始化
&#39;.gitsecret/&#39; 创建.
```

### git secret tell

```
$ git 秘密告诉 my@email.com
完毕.  my@email.com 添加为知道秘密的人.
打扫干净...
```

### git secret add

```
$ git secret 添加 hideme.txt
添加了 1 项.
```

### git secret list

```
$ git 秘密列表
hideme.txt
```

### git secret hide

```
$ git 秘密隐藏
完毕. 所有 1 个文件都被隐藏.
```

### git secret reveal

```
$ git 秘密揭示

You need a passphrase to unlock the secret key for
用户：“测试用户<my@email.com> “
2048-bit RSA key, ID #######, created 2015-01-01 (main key ID #######)

gpg：gpg-agent 在此会话中不可用
文件“hideme.txt”存在. 覆盖？  （是/否）是
完毕. 显示所有 1 个文件.
```


## [git-secrets](https://github.com/awslabs/git-secrets)

&gt; 防止您将密码和其他敏感信息提交到 git 存储库.

TBD - 公关欢迎！


## [git-fixup](https://github.com/keis/git-fixup)

```
$ git diff --cached -U0
diff --git a/README.md b/README.md
索引 0c700d1..7a57cef 100644
--- 一个/README.md
+++ b/自述文件.md
@@ -1330 +1330 @@ $ git 秘密隐藏
 -完毕. 所有 1 个文件都被隐藏.
 +完成. 所有 3 个文件都被隐藏.
$ git 修复 6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8
24aa3d9c10cc02fe813dc83d1ac792cc2e7d705d [F] 添加 git-stats 的截图<maochenyan@gmail.com>
6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8 [L] 将 gif 更改为文字<mail@sobolevn.me>
```


## [git-recent](https://github.com/paulirish/git-recent)

```
$ git 最近
```

![git-recent screenshot](https://cloud.githubusercontent.com/assets/39191/17446638/039d4cee-5aff-11e6-9e11-4294f0020513.png)

## [git-interactive-rebase-tool](https://github.com/MitMaro/git-interactive-rebase-tool)

```
$ git rebase -i master
```

![git-interactive-rebase-tool screenshot](https://raw.githubusercontent.com/MitMaro/git-interactive-rebase-tool/master/docs/assets/images/git-interactive-rebase-demo.gif)

## [git-fiddle](https://github.com/felixSchl/git-fiddle)

```
$ git 小提琴-h
git-fiddle

在 *interactive* rebase 期间编辑提交元信息.

`git-fiddle(1)&#39; 是 `git-rebase(1)&#39; 的轻量级包装器，它
用它的 *author* 日期，作者姓名注释每个提交
作为提交信息. 然后将应用对其中任何一项的更改
在 git-rebase 序列中使用“exec”脚本.

Usage:
  $SCRIPT [--[no-]-fiddle-messages] [args...]

Options:
   --[no-]fiddle-messages 不要编辑提交信息. 用于快速编辑
                         作者或日期. 这个值也可以使用设置
                         `git config fiddle.messages`.
  [args...] 这些参数逐字传递给 git-rebase.
```


## [git-user](https://github.com/gesquive/git-user)

```
## add a work profile for Henry
$ git 用户添加工作“Henry Jekyll 博士”henry@jekyll.com
添加了配置文件“工作”

## add a personal profile for Edward
$ git 用户添加主页“Edward Hyde”hyde@night.com
添加了配置文件“主页”

## list out our saved profiles
$ git 用户列表
全球概况：
  用户：亨利<hjekyll@gmail.com>

保存的配置文件：
  家：爱德华·海德<hyde@night.com>
  作品：亨利杰基尔博士<henry@jekyll.com>

## set the current git repository user to the home profile
$ git 用户设置主页
 “项目”存储库的用户也已设置为“Edward Hyde”<hyde@night.com>  &#39;

## list profiles again, notice how the current repository profile is now set
$ git 用户
项目简介：
  路径：/path/to/git/project
  用户：爱德华·海德<hyde@night.com>

保存的配置文件：
  家：爱德华·海德<hyde@night.com>
  作品：亨利杰基尔博士<henry@jekyll.com>
```


## [gitsome](https://github.com/donnemartin/gitsome)

TBD - 公关欢迎！


## [git-hound](https://github.com/ezekg/git-hound)

TBD - 公关欢迎！


## [git-recall](https://github.com/Fakerr/git-recall)

![](https://camo.githubusercontent.com/eb306717b95724c33dd0de91faa535a4818cc7d0/687474703a2f2f696d6775722e636f6d2f7a7577324c71572e676966)

```
$ git 召回
## By default (without options), the command will display commits from yesterday and
## for the current user.

$ git recall -d 5 -a “总督”
## Show all Doge's commits from 5 days ago.

$ git recall -d 5 -a “全部”
## Show commits of all contributors from 5 days ago.

$ git 回忆 -f
## Fetch commits beforehand.
```


## [git-standup](https://github.com/kamranahmedse/git-standup)

```
$ git 站起来
2f50b39c - 文档（提交消息）：使用 commitizen 生成常规提交（12 小时前）<Steve Mao>
9af3600e - 修复测试（12 小时前）<Steve Mao>
7f17ba97 - 文档：标题案例（12 小时前）<Steve Mao>
a6d6203c - 搜索打开时不滚动（12 小时前）<Steve Mao>
53fe681a - 琐事（pkg）：添加回购网址（12 小时前）<Steve Mao>
5e952ac0 - 字幕应该是通用的（13 小时前）<Steve Mao>
 adbc5423 - 将 ci/cd 添加到自述文件.  （13 小时前）<Steve Mao>
a1097116 - 将版本控制添加到自述文件（14 小时前）<Steve Mao>
6b6e7465 - 添加测试覆盖率（15 小时前）<Steve Mao>
```


## [commitizen](https://github.com/commitizen/cz-cli)

```
$ 混帐
cz-cli@2.9.6, cz-conventional-changelog@1.2.0


第 1 行将被裁剪为 100 个字符. 所有其他行将在 100 个字符后换行.

 ？ 选择您要提交的更改类型：（使用箭头键）
❯ 壮举：一项新功能
  修复：错误修复
  docs：文档仅更改
  样式：不影响代码含义的更改（空白、格式、缺失半
-定居者等）
  重构：既不修复错误也不添加功能的代码更改
  perf：提高性能的代码更改
  测试：添加缺少的测试或更正现有测试
```


## [git-fresh](https://github.com/imsky/git-fresh)

TBD - 公关欢迎！

## [git-fs](https://github.com/freddi301/git-fs)

```
$ 混帐文件系统
在 ./git/fs 上挂载只读文件系统
```

## [git-url](https://github.com/zdharma/git-url)

### git url

```
$ cd ~/github/git-url.git
$ git 网址
编码...输入是下一段：

协议：https
站点：github.com
回购：zdharma/git-url
修订：大师

gitu://ҝjȩMżEäḝЃȣϟṈӛŀї

$ git url -r v1.0
编码...输入是下一段：

协议：https
站点：github.com
回购：zdharma/git-url
版本：v1.0

gitu://ŪĪАϔEäḝЃȣϟṈӛŀї

$ git url -q -p lib/common.sh	# -q - quiet, -p - path
gitu://eḶȸṋ0oǗȟЗÛjȩMżEäḝЃȣϟṈӛŀї

$ git url //例子
解码...输出是：

协议：https
站点：github.com
回购：zdharma/git-url
修订：大师
文件：lib/common.sh

https://github.com/zdharma/git-url
```
 
### git guclone

```
$ git guclone
克隆 URL https://github.com/zdharma/git-url 用于修订版 v1.0

克隆到&#39;git-url&#39;...
远程：计数对象：144，完成.
远程：压缩对象：100% (111/111)，完成.
远程：总计 144（增量 71），重复使用 102（增量 32），打包重复使用 0
接收对象：100% (144/144), 116.43 KiB |  125.00 KiB/s，完成.
解决增量：100% (71/71)，完成.

正在检查修订版/参考 v1.0... 确定
HEAD 位于：5d10a204，创建目录 git-url
```


## [git-signatures](https://github.com/hashbang/git-signatures)

### signatures add --push

```
$ git signatures add --push v1.0.0
更新标签“v1.0.0”（原为 4de5afd）
枚举对象：4，完成.
计数对象：100% (4/4)，完成.
使用多达 8 个线程的增量压缩
压缩对象：100% (3/3)，完成.
写入对象：100% (3/3)，906 字节 |  906.00 KiB/s，完成.
总计 3（delta 1），重复使用 0（delta 0）
到 git@github.com:jsmith/test-signatures
   4b5300d..5b1f2cd 参考/注释/签名 -&gt; 参考/注释/签名
 + 4de5afd...5b1f2cd v1.0.0 -&gt; v1.0.0（强制更新）
```


### signatures verify

```
$ git 签名验证 v1.0.0
```


### signatures verify --min-count 2

```
$ git 签名验证 --min-count 2 v1.0.0
未能找到足够的已验证签名来满足：min_count=2

签名验证可能会失败，因为您的本地 gnupg
keychain 和 trustdb 不包含所需的密钥.

对于详细的签名状态运行：

&gt; git 签名显示
```


### signatures show

```
$ git 签名显示 v1.0.0
 公钥 ID | 状态 | 信任 | 日期 | 签署人姓名
=======================================================================================================================
 01234567890ABCDEF | 有效信号 | 终极 |  2018 年 11 月 10 日星期六 13:16:10 EST | 史蒂夫·毛<maochenyan@gmail.com>
 ```

## [git-profile](https://github.com/dm3ch/git-profile-manager)
### add a work profile
```
$ git 配置文件添加工作
姓名：姓名
邮箱：name@work-domain.com
签名密钥：
配置文件工作添加成功
```

### add a personal profile
```
$ git profile add home -n &quot;Name Surname&quot; -e name@gmail.com
个人主页添加成功
```

### list out our saved profiles
```
$ git 配置文件列表
现有资料：
work
home
```

### set the current git repository user to the home profile
```
$ git 配置文件使用工作
```
目前成功后不会有输出

## [git-revise](https://github.com/mystor/git-revise)

TBD - 公关欢迎！

## [filter-repo](https://github.com/newren/git-filter-repo)

TBD - 公关欢迎！

## [git-jump](https://github.com/mykolaharmash/git-jump)

交互式 UI 和 Git 分支的模糊搜索.

![git-jump interface demo](https://raw.githubusercontent.com/mykolaharmash/git-jump/main/img/demo.gif)

## [git-project](https://github.com/mms-gianni/git-projecto)
```
git 项目打开购物清单
```
```
git项目添加购物清单牛奶
```
```
$ git 项目板

 项目：购物清单 
+-----------+------+
 | 打开| 完成 |
+-----------+------+
 | 东西 | 爱 |
+-----------+------+
 | 咖啡 |  |
+-----------+      +
 | 糖 |  |
+-----------+      +
 | 牛奶 |  |
+-----------+------+
```

```
$ git 项目状态

项目：购物清单
   0|  ⭐ 某事
   1|  ⭐咖啡
   2|  ⭐糖
   3|  ⭐牛奶
   4|  ✅爱
```

## [git-branchcut](https://github.com/dlsrb6342/git-branchcut)
### Delete branches with string pattern 
```
$ git branchcut execute -p &quot;feature/*&quot;
切换到分支“主要”
删除了分支功能/测试（原为 257725f）.
删除了分支功能/实现（原为 8120c0b）.
```

### Delete branches with day-offset
```
$ git branchcut 执行 -o 7
切换到分支“主要”
删除分支错误修复/测试（是 e2afad6）.
删除分支太旧分支（是 1d3f82d）.
```

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Steve Mao](https://github.com/stevemao) 已放弃该作品的所有版权和相关或邻接权.
