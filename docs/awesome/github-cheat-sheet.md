<div class="github-widget" data-repo="tiimgreen/github-cheat-sheet"></div>
## GitHub Cheat Sheet [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
 Git和GitHub的一个很酷的隐藏和不那么隐藏的功能的集合.  这个备忘单的灵感来自于 [Zach Holman](https://github.com/holman)'s [Git and GitHub Secrets](http://confreaks.tv/videos/aloharuby2012-git-and-github-secrets) 在2012年Aloha Ruby Conference上发言（[slides](https://speakerdeck.com/holman/git-and-github-secrets)） 和他 [More Git and GitHub Secrets](https://vimeo.com/72955426) 在WDCNZ 2013上发言（[slides](https://speakerdeck.com/holman/more-git-and-github-secrets)).

*Shortlink: [`http://git.io/sheet`](http://git.io/sheet)*

*用其他语言阅读： [English](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.md), [한국어](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.ko.md), [日本語](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.ja.md), [简体中文](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md), [正體中文](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-tw.md).*



## GitHub
### Ignore Whitespace
将“？w = 1”添加到任何差异URL将仅删除空格中的任何更改，使您只能看到已更改的代码.

![Diff without whitespace](https://camo.githubusercontent.com/797184940defadec00393e6559b835358a863eeb/68747470733a2f2f6769746875622d696d616765732e73332e616d617a6f6e6177732e636f6d2f626c6f672f323031312f736563726574732f776869746573706163652e706e67)

[*Read more about GitHub secrets.*](https://github.com/blog/967-github-secrets)

### Adjust Tab Space
 将“？ts = 4”添加到差异或文件URL将显示4个宽度的制表符而不是默认值8.可以调整“ts”之后的数字以适合您的偏好.  这不适用于Gists或原始文件视图，但是a [Chrome extension](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn) 可以自动化这个.

在添加`？ts = 4`之前，这是一个Go源文件：

![Before, tab space example](http://i.imgur.com/GIT1Fr0.png)

......这是在添加`？ts = 4`之后：

![After, tab space example](http://i.imgur.com/70FL4H9.png)

### Commit History by Author
要通过作者查看repo上的所有提交，请将“？author = {user}”添加到URL.

```
https://github.com/rails/rails/commits/master?author=dhh
```

![DHH commit history](http://i.imgur.com/S7AE29b.png)

[*Read more about the differences between commits views.*](https://help.github.com/articles/differences-between-commit-views/)

### Cloning a Repository
克隆存储库时，`.git`可以不在最后.

```bash
$ git clone https://github.com/tiimgreen/github-cheat-sheet
```

[*Read more about the Git `clone` command.*](http://git-scm.com/docs/git-clone)

### Branch
#### Compare all Branches to Another Branch

如果你去回购 [Branches](https://github.com/tiimgreen/github-cheat-sheet/branches) 页面，在“提交”按钮旁边：

```
https://github.com/{user}/{repo}/branches
```

...你会看到一个未合并到主分支的所有分支的列表.

从这里，您可以访问比较页面或通过单击按钮删除分支.

![Compare branches not merged into master in rails/rails repo - https://github.com/rails/rails/branches](http://i.imgur.com/0FEe30z.png)

#### Comparing Branches
要使用GitHub比较分支，请将URL更改为如下所示：

```
https://github.com/{user}/{repo}/compare/{range}
```

其中`{range} = master ... 4-1-stable`

例如：

```
https://github.com/rails/rails/compare/master...4-1-stable
```

![Rails branch compare example](http://i.imgur.com/tIRCOsK.png)

`{range}`可以更改为：

```
https://github.com/rails/rails/compare/master@{1.day.ago}...master
https://github.com/rails/rails/compare/master@{2014-10-04}...master
```

*此处的日期格式为“YYYY-MM-DD”*

![Another compare example](http://i.imgur.com/5dtzESz.png)

分支也可以在`diff`和`patch`视图中进行比较：

```
https://github.com/rails/rails/compare/master...4-1-stable.diff
https://github.com/rails/rails/compare/master...4-1-stable.patch
```

[*Read more about comparing commits across time.*](https://help.github.com/articles/comparing-commits-across-time/)

#### Compare Branches across Forked Repositories
要使用GitHub比较分叉存储库中的分支，请将URL更改为如下所示：

```
https://github.com/{user}/{repo}/compare/{foreign-user}:{branch}...{own-branch}
```

例如：

```
https://github.com/rails/rails/compare/byroot:master...master
```

![Forked branch compare](http://i.imgur.com/Q1W6qcB.png)

### Gists
[Gists](https://gist.github.com/) 是一种简单的方法来处理少量代码而无需创建完全成熟的存储库.

![Gist](http://i.imgur.com/VkKI1LC.png?1)

将“.pibb”添加到任何Gist URL的末尾（[like this](https://gist.github.com/tiimgreen/10545817.pibb)）以获得适合嵌入任何其他网站的* HTML-only *版本.

Gists可以被视为一个存储库，因此可以像任何其他一样克隆它们：

```bash
$ git clone https://gist.github.com/tiimgreen/10545817
```

![Gists](http://i.imgur.com/BcFzabp.png)

这意味着您还可以修改并推送Gists的更新：

```bash
$ git commit
$ git push
“https://gist.github.com”的用户名：
“https：//tiimgreen@gist.github.com”的密码：
```

 但是，Gists不支持目录.  需要将所有文件添加到存储库根目录.
[*Read more about creating Gists.*](https://help.github.com/articles/creating-gists/)

### Git.io
[Git.io](http://git.io) 是GitHub的简单URL缩短器.

![Git.io](http://i.imgur.com/6JUfbcG.png?1)

您也可以使用Curl通过纯HTTP使用它：

```bash
$ curl -i http://git.io -F“url = https://github.com / ...”
HTTP/1.1 201 Created
地点：http：//git.io/abc123

$ curl -i http://git.io/abc123
找到HTTP / 1.1 302
地点：https：//github.com / ...
```

[*Read more about Git.io.*](https://github.com/blog/985-git-io-github-url-shortener)

### Keyboard Shortcuts
在存储库页面上，键盘快捷键允许您轻松导航.

 - 按`t`将调出文件浏览器.
 - 按&#39;w`将调出分支选择器.
   - 按`s`将聚焦当前存储库的搜索字段.  按退格键删除“此存储库”丸会更改该字段以搜索所有GitHub.
 - 按“l”将编辑现有问题的标签.
   - 查看文件时按&#39;y` ** **（例如，`https：// github.com / tiimgreen / github-cheat-sheet / blob / master / README.md`）会将您的URL更改为实际上，冻结了您正在查看的页面.  如果此代码更改，您仍然可以看到您在当前时间看到的内容.

要查看当前页面的所有快捷方式，请按`？`：

![Keyboard shortcuts](http://i.imgur.com/y5ZfNEm.png)

[Read more about search syntax you can use.](https://help.github.com/articles/search-syntax/)

### Line Highlighting in Repositories
Either adding, e.g., `#L52` to the end of a code file URL or simply clicking the line number will highlight that line number.

It also works with ranges, e.g., `#L53-L60`, to select ranges, hold `shift` and click two lines:

```
https://github.com/rails/rails/blob/master/activemodel/lib/active_model.rb#L53-L60
```

![Line Highlighting](http://i.imgur.com/8AhjrCz.png)

### Closing Issues via Commit Messages
如果特定提交修复了问题，任何关键字“fix / fixes / fixed”，“close / closing / closed”或“resolve / resolves / resolved”，后跟问题编号，将在提交后关闭该问题到存储库的默认分支.

```bash
$ git commit -m "Fix screwup, fixes #12"
```

这将关闭该问题并引用结束提交.

![Closing Repo](http://i.imgur.com/Uh1gZdx.png)

[*Read more about closing Issues via commit messages.*](https://help.github.com/articles/closing-issues-via-commit-messages/)

### Cross-Link Issues
If you want to link to another issue in the same repository, simply type hash `#` then the issue number, and it will be auto-linked.

To link to an issue in another repository, `{user}/{repo}#ISSUE_NUMBER`, e.g., `tiimgreen/toc#12`.

![Cross-Link Issues](https://camo.githubusercontent.com/447e39ab8d96b553cadc8d31799100190df230a8/68747470733a2f2f6769746875622d696d616765732e73332e616d617a6f6e6177732e636f6d2f626c6f672f323031312f736563726574732f7265666572656e6365732e706e67)

### Locking Conversations
现在可以通过回购的所有者或协作者锁定请求和问题.

![Lock conversation](https://cloud.githubusercontent.com/assets/2723/3221693/bf54dd44-f00d-11e3-8eb6-bb51e825bc2c.png)

这意味着不是项目协作者的用户将无法再发表评论.

![Comments locked](https://cloud.githubusercontent.com/assets/2723/3221775/d6e513b0-f00e-11e3-9721-2131cb37c906.png)

[*Read more about locking conversations.*](https://github.com/blog/1847-locking-conversations)


### CI Status on Pull Requests
如果设置正确，每次收到Pull请求时， [Travis CI](https://travis-ci.org/)  将构建Pull Request，就像每次进行新提交一样.  详细了解如何操作 [get started with Travis CI](http://docs.travis-ci.com/user/getting-started/).

[![Travis CI status](https://cloud.githubusercontent.com/assets/1687642/2700187/3a88838c-c410-11e3-9a46-e65e2a0458cd.png)](https://github.com/octokit/octokit.rb/pull/452)

[*Read more about the commit status API.*](https://github.com/blog/1227-commit-status-api)

### Filters

问题和拉取请求都允许在用户界面中进行过滤.

对于Rails repo：https：//github.com/rails/rails/issues，通过选择标签“activerecord”构建以下过滤器：

`是：issue label：activerecord`

但是，您还可以找到未标记为activerecord的所有问题：

`是：issue -label：activerecord`

此外，这也适用于拉取请求：

`是：pr -label：activerecord`

Github有标签显示打开或关闭的问题，并提取请求但你
 也可以看到合并拉取请求.  只需将以下内容放入过滤器：

`is:merged`

[*Read more about searching issues.*](https://help.github.com/articles/searching-issues/)

最后，github现在允许您按Status API的状态进行过滤.

只有成功状态的拉请求：

`status:success`

[*Read more about searching on the Status API.*](https://github.com/blog/2014-filter-pull-requests-by-status)

### Syntax Highlighting in Markdown Files
例如，要在Markdown文件中突出显示Ruby代码，请写入：

    ```红宝石
    要求&#39;tabbit&#39;
    table = Tabbit.new（&#39;姓名&#39;，&#39;电子邮件&#39;）
    table.add_row（&#39;Tim Green&#39;，&#39;tiimgreen @ gmail.com&#39;）
    puts table.to_s
    ```

这将产生：

```ruby
要求&#39;tabbit&#39;
table = Tabbit.new（&#39;姓名&#39;，&#39;电子邮件&#39;）
table.add_row（&#39;Tim Green&#39;，&#39;tiimgreen @ gmail.com&#39;）
puts table.to_s
```

GitHub使用 [Linguist](https://github.com/github/linguist)  执行语言检测和语法突出显示.  您可以通过仔细查看哪些关键字有效 [languages YAML file](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml).

[*Read more about GitHub Flavored Markdown.*](https://help.github.com/articles/github-flavored-markdown/)

### Emojis
可以使用`：name_of_emoji：`将Emojis添加到Pull请求，问题，提交消息，存储库描述等.

可以在以下位置找到GitHub上支持的Emojis的完整列表 [emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com/) 要么 [scotch-io/All-Github-Emoji-Icons](https://github.com/scotch-io/All-Github-Emoji-Icons).
一个方便的表情符号搜索引擎可以在 [emoji.muan.co](http://emoji.muan.co/).

在GitHub上使用的前5个Emojis是：

1.`：shipit：`
2.`：闪闪发光：`
3. `:-1:`
4. `:+1:`
``：拍手：`

### Images/GIFs
图像和GIF可以添加到评论，自述文件等中：

```
![Alt Text](http://www.sheawong.com/wp-content/uploads/2013/08/keephatin.gif)
```

来自repo的原始图像可以通过直接调用它们来使用：

```
![Alt Text](https://github.com/{user}/{repo}/raw/master/path/to/image.gif)
```

![Peter don't care](http://www.sheawong.com/wp-content/uploads/2013/08/keephatin.gif)

所有图像都缓存在GitHub上，因此如果您的主机出现故障，图像将保持可用状态.

#### Embedding Images in GitHub Wiki
 在Wiki页面中嵌入图像有多种方法.  有标准的Markdown语法（如上所示）.  但是还有一种语法允许指定图像的高度或宽度：

```markdown
 [[http://www.sheawong.com/wp-content/uploads/2013/08/keephatin.gif |  身高= 100像素]]
```

哪个产生：

![Just a screenshot](http://i.imgur.com/J5bMf7S.png)

### Quick Quoting
当你在评论主题上想要引用某人先前所说的内容时，请突出显示该文本并按`r`，这将以块报价格式将其复制到文本框中.

![Quick Quote](https://f.cloud.github.com/assets/296432/124483/b0fa6204-6ef0-11e2-83c3-256c37fa7abc.gif)

[*Read more about quick quoting.*](https://github.com/blog/1399-quick-quotes)

### Pasting Clipboard Image to Comments

_（仅适用于Chrome浏览器）_

在截取屏幕截图并将其添加到剪贴板（mac：`cmd-ctrl-shift-4`）之后，您只需将图像粘贴（`cmd-v / ctrl-v`）到评论部分，它就会自动显示 - 上传到github.

![Pasting Clipboard Image to Comments](https://cloud.githubusercontent.com/assets/39191/5794265/39c9b65a-9f1b-11e4-9bc7-04e41f59ea5f.png)

[*Read more about issue attachments.*](https://help.github.com/articles/issue-attachments/)

### Quick Licensing
创建存储库时，GitHub允许您添加预先制作的许可证：

![License](http://i.imgur.com/Chqj4Fg.png)

 您还可以通过Web界面创建新文件，将它们添加到现有存储库.  当输入名称“LICENSE”时，您将获得使用模板的选项：

![License](http://i.imgur.com/fTjQict.png)

也适用于`.gitignore`.

[*Read more about open source licensing.*](https://help.github.com/articles/open-source-licensing/)

### Task Lists
在“问题”和“拉取请求”中，可以使用以下语法添加复选框（请注意空格）：

```
-  []真棒
- [ ] 准备晚餐
  -  []研究食谱
  -  []购买原料
  -  []烹饪食谱
-  []睡觉
```

![Task List](http://i.imgur.com/jJBXhsY.png)

点击它们后，它们将在纯Markdown中更新：

```
-  [x]太棒了
- [ ] 准备晚餐
  -  [x]研究食谱
  -  [x]购买原料
  -  []烹饪食谱
-  []睡觉
```

[*Read more about task lists.*](https://help.github.com/articles/writing-on-github/#task-lists)

#### Task Lists in Markdown Documents
在完整的Markdown文档中**现在可以使用以下语法添加只读**清单：

```
-  []水星
-  [x]维纳斯
-  [x]地球
  -  [x]月亮
-  [x]火星
  -  [] Deimos
  -  [] Phobos
```

-  []水星
-  [x]维纳斯
-  [x]地球
  -  [x]月亮
-  [x]火星
  -  [] Deimos
  -  [] Phobos

[*Read more about task lists in markdown documents.*](https://github.com/blog/1825-task-lists-in-all-markdown-documents)

### Relative Links
Relative links are recommended in your Markdown files when linking to internal content.

```markdown
[Link to a file](https://github.com/tiimgreen/github-cheat-sheet/blob/master/docs/readme)
```

 每当URL更改时，必须更新绝对链接（例如，存储库重命名，用户名更改，项目分叉）.  使用相对链接可以使您的文档轻松独立.

[*Read more about relative links.*](https://help.github.com/articles/relative-links-in-readmes/)

### Metadata and Plugin Support for GitHub Pages
在Jekyll页面和帖子中，存储库信息在`site.github`命名空间中可用，并且可以显示，例如，使用`{{site.github.project_title}}`.

Jemoji和jekyll-mentions插件启用 [emoji](#emojis) 和 [@mentions](https://github.com/blog/821) in your Jekyll posts 和 pages to work just like you'd expect when interacting with a repository on GitHub.com.

[*Read more about repository metadata and plugin support for GitHub Pages.*](https://github.com/blog/1797-repository-metadata-and-plugin-support-for-github-pages)

### Viewing YAML Metadata in your Documents
很多博客网站都喜欢 [Jekyll](http://jekyllrb.com/) 同 [GitHub Pages](https://pages.github.com) ，取决于帖子开头的一些YAML格式的元数据.  GitHub将此元数据呈现为水平表，以便于阅读

![YAML metadata](https://camo.githubusercontent.com/47245aa16728e242f74a9a324ce0d24c0b916075/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f36343035302f313232383236372f65303439643063362d323761302d313165332d396464382d6131636432323539393334342e706e67)

[*Read more about viewing YAML metadata in your documents.*](https://github.com/blog/1647-viewing-yaml-metadata-in-your-documents)

### Rendering Tabular Data
GitHub支持以`.csv`（逗号分隔）和`.tsv`（制表符分隔）文件的形式呈现表格数据.

![Tabular data](https://camo.githubusercontent.com/1b6dd0157ffb45d9939abf14233a0cb13b3b4dfe/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f3238323735392f3937363436322f33323038336463652d303638642d313165332d393262322d3566323863313061353035392e706e67)

[*Read more about rendering tabular data.*](https://github.com/blog/1601-see-your-csvs)

### Rendering PDF

GitHub支持渲染PDF：

![PDF](https://cloud.githubusercontent.com/assets/1000669/7492902/f8493160-f42e-11e4-8cea-1cb4f02757e7.png)

[*Read more about rendering PDF.*](https://github.com/blog/1974-pdf-viewing)

### Revert a Pull Request
合并拉取请求后，您可能会发现它没有任何帮助，或者合并拉取请求是一个错误的决定.

您可以通过单击拉取请求页面中提交右侧的** Revert **按钮来恢复它，以创建一个拉回请求，并恢复对此特定拉取请求的更改.

![Revert button](https://camo.githubusercontent.com/0d3350caf2bb1cba53123ffeafc00ca702b1b164/68747470733a2f2f6769746875622d696d616765732e73332e616d617a6f6e6177732e636f6d2f68656c702f70756c6c5f72657175657374732f7265766572742d70756c6c2d726571756573742d6c696e6b2e706e67)

[*Read more about reverting pull requests*](https://github.com/blog/1857-introducing-the-revert-button)

### Diffs
#### Rendered Prose Diffs
提交和拉取请求，包括GitHub支持的渲染文档（例如，Markdown），feature * source *和* rendered * views.

![Source / Rendered view](https://github-images.s3.amazonaws.com/help/repository/rendered_prose_diff.png)

 单击“渲染”按钮以查看它们将出现在渲染文档中的更改.  当您添加，删除和编辑文本时，渲染散文视图很方便：

![Rendered Prose Diffs](https://f.cloud.github.com/assets/17715/2003056/3997edb4-862b-11e3-90be-5e9586edecd7.png)

[*Read more about rendered prose diffs.*](https://github.com/blog/1784-rendered-prose-diffs)

#### Diffable Maps
每次在GitHub上查看包含地理数据的提交或拉取请求时，GitHub都会呈现已更改内容的直观表示.

[![Diffable Maps](https://f.cloud.github.com/assets/282759/2090660/63f2e45a-8e97-11e3-9d8b-d4c8078b004e.gif)](https://github.com/benbalter/congressional-districts/commit/2233c76ca5bb059582d796f053775d8859198ec5)

[*Read more about diffable maps.*](https://github.com/blog/1772-diffable-more-customizable-maps)

#### Expanding Context in Diffs
 使用diff的装订线中的*展开*按钮，您可以通过单击显示其他上下文行.  您可以继续单击*展开*直到您显示整个文件，并且该功能可在GitHub呈现差异的任何位置使用.

![Expanding Context in Diffs](https://f.cloud.github.com/assets/22635/1610539/863c1f64-5584-11e3-82bf-151b406a272f.gif)

[*Read more about expanding context in diffs.*](https://github.com/blog/1705-expanding-context-in-diffs)

#### Diff or Patch of Pull Request
您可以通过添加`.diff`或`.patch`来获取Pull Request的差异
 扩展到URL的结尾.  例如：

```
https://github.com/tiimgreen/github-cheat-sheet/pull/15
https://github.com/tiimgreen/github-cheat-sheet/pull/15.diff
https://github.com/tiimgreen/github-cheat-sheet/pull/15.patch
```

`.diff`扩展名将以纯文本形式提供给您：

```
diff --git a / README.md b / README.md
index 88fcf69..8614873 100644
--- a / README.md
+++ b / README.md
 @@ -28,6 +28,7 @@ Git和GitHub的所有隐藏和非隐藏功能.  这个备忘单是我
@@ -381,6 +382,19 @@点击它们后，它们将在纯Markdown中更新：
 -  []睡觉

(...)
```

#### Rendering and diffing images
 GitHub可以显示几种常见的图像格式，包括PNG，JPG，GIF和PSD.  此外，有几种方法可以比较这些图像格式的版本之间的差异.

[![Diffable PSD](https://cloud.githubusercontent.com/assets/2546/3165594/55f2798a-eb56-11e3-92e7-b79ad791a697.gif)](https://github.com/blog/1845-psd-viewing-diffing)

[*Read more about rendering and diffing images.*](https://help.github.com/articles/rendering-and-diffing-images/)

### Hub
[Hub](https://github.com/github/hub) 是一个命令行Git包装器，它为您提供了额外的功能和命令，使您可以更轻松地使用GitHub.

这允许您执行以下操作：

```bash
$ hub clone tiimgreen / toc
```

[*Check out some more cool commands Hub has to offer.*](https://github.com/github/hub#commands)

### Contribution Guidelines
GitHub支持添加3个不同的文件，帮助用户为您的项目做出贡献.
这些文件可以放在存储库的根目录下，也可以放在根目录下的`.github`目录中.

#### CONTRIBUTING File
将“CONTRIBUTING”或“CONTRIBUTING.md”文件添加到存储库的根目录或`.github`目录将在贡献者创建问题或打开拉取请求时添加指向您的文件的链接.

![Contributing Guidelines](https://camo.githubusercontent.com/71995d6b0e620a9ef1ded00a04498241c69dd1bf/68747470733a2f2f6769746875622d696d616765732e73332e616d617a6f6e6177732e636f6d2f736b697463682f6973737565732d32303132303931332d3136323533392e6a7067)

[*Read more about contributing guidelines.*](https://github.com/blog/1184-contributing-guidelines)

#### ISSUE_TEMPLATE file
 您可以为项目中打开的所有新问题定义模板.  当用户创建新问题时，此文件的内容将预先填充新问题框.  将`ISSUE_TEMPLATE`或`ISSUE_TEMPLATE.md`文件添加到存储库的根目录或`.github`目录.

[*Read more about issue templates.*](https://github.com/blog/2111-issue-and-pull-request-templates)

[Issue template file generator](https://www.talater.com/open-source-templates/)

![GitHub Issue template](https://cloud.githubusercontent.com/assets/25792/13120859/733479fe-d564-11e5-8a1f-a03f95072f7a.png)

#### PULL_REQUEST_TEMPLATE file
 您可以为项目中打开的所有新拉取请求定义模板.  当用户创建拉取请求时，此文件的内容将预先填充文本区域.  将`PULL_REQUEST_TEMPLATE`或`PULL_REQUEST_TEMPLATE.md`文件添加到存储库的根目录或`.github`目录.

[*Read more about pull request templates.*](https://github.com/blog/2111-issue-and-pull-request-templates)

[Pull request template file generator](https://www.talater.com/open-source-templates/)

### Octicons
GitHubs图标（Octicons）现已开源.

![Octicons](https://og.github.com/octicons/octicons@1200x630.png)

[*Read more about GitHub's Octicons*](https://octicons.github.com)

### GitHub Student Developer Pack

 如果您是学生，您将有资格获得GitHub学生开发者包.  这为您提供免费信用，免费试用和早期访问软件，可以帮助您进行开发.

![GitHub Student Developer Pack](http://i.imgur.com/9ru3K43.png)

[*Read more about GitHub's Student Developer Pack*](https://education.github.com/pack)

### GitHub Resources
 |  标题|  链接|
| ----- | ---- |
 |  GitHub探索|  https://github.com/explore |
 |  GitHub博客|  https://github.com/blog |
 |  GitHub帮助|  https://help.github.com/ |
 |  GitHub培训|  https://training.github.com/ |
 |  GitHub开发人员|  https://developer.github.com/ |
 |  Github教育（免费微账户和其他学生用品）|  https://education.github.com/ |
 |  GitHub十大最佳实践| [Best Practices List](https://datree.io/blog/top-10-github-best-practices/) |

#### GitHub Talks
 |  标题|  链接|
| ----- | ---- |
 |  GitHub如何使用GitHub构建GitHub |  https://www.youtube.com/watch?v=qyz3jkOBbQY |
 |  与GitHub的Scott Chacon一起介绍Git  https://www.youtube.com/watch?v=ZDR433b0HJY |
 |  如何GitHub不再工作|  https://www.youtube.com/watch?v=gXD1ITW7iZI |
 |  Git和GitHub的秘密|  https://www.youtube.com/watch?v=Foz9yvMkvlA |
 |  更多Git和GitHub秘密|  https://www.youtube.com/watch?v=p50xsL-iVgU |

### SSH keys

您可以访问以下内容获取纯文本格式的公共ssh密钥列表：

```
https://github.com/{user}.keys
```

e.g. [https://github.com/tiimgreen.keys](https://github.com/tiimgreen.keys)

[*Read more about accessing public ssh keys.*](https://changelog.com/github-exposes-public-ssh-keys-for-its-users/)

### Repository Templates

 您可以在存储库中启用模板，允许任何人复制目录结构和文件，允许他们立即使用文件（例如，教程或编写样板代码）.  这可以在存储库的设置中启用.

![Convert](https://i.postimg.cc/hGCrVm9F/Template.gif)

 更改为模板存储库将提供可以共享的新URL端点，并立即允许用户将存储库用作模板.  或者，他们可以转到您的存储库并单击“用作模板”按钮.

![Template](https://i.postimg.cc/L8PKCHx0/New-Template.gif)

[*Read more about using repositories as templates*](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/)

## Git
### Remove All Deleted Files from the Working Tree
使用`/ bin / rm`删除大量文件时，可以使用以下命令将其从工作树和索引中删除，无需单独删除每个文件：

```bash
$ git rm $（git ls-files -d）
```

例如：

```bash
$ git状态
在分支大师
未提交更改的更改：
	删除：a
	删除：c

$ git rm $（git ls-files -d）
rm&#39;a&#39;
rm&#39;c&#39;

$ git状态
在分支大师
要提交的更改：
	删除：a
	删除：c
```

### Previous Branch
要转到Git中的上一个分支：

```bash
$ git checkout  - 
## Switched to branch 'master'

$ git checkout  - 
## Switched to branch 'next'

$ git checkout  - 
## Switched to branch 'master'
```

[*Read more about Git branching.*](http://git-scm.com/book/en/Git-Branching-Basic-Branching-and-Merging)

### Stripspace

Git Stripspace：

- 剥离尾随空格
- 折叠换行符
- 在文件末尾添加换行符

调用命令时必须传递一个文件，例如：
```bash
$ git stripspace &lt;README.md
```

[*Read more about the Git `stripspace` command.*](http://git-scm.com/docs/git-stripspace)

### Checking out Pull Requests

Pull Requests是GitHub存储库中的特殊分支，可以通过以下几种方式在本地检索：

检索特定的Pull请求并将其临时存储在`FETCH_HEAD`中，以便快速进行“差异”或“合并”：

```bash
$ git fetch origin refs / pull / [PR-Number] / head
```

通过refspec获取所有Pull Request分支作为本地远程分支：

```bash
$ git fetch origin&#39;+ refs / pull / * / head：refs / remotes / origin / pr / *&#39;
```

或者通过在存储库的`.git / config`中添加相应的行来设置远程自动获取Pull请求：

```
[遥远的“原产地”]
    fetch = + refs / heads / *：refs / remotes / origin / *
    url = git@github.com:tiimgreen / github-cheat-sheet.git
```

```
[遥远的“原产地”]
    fetch = + refs / heads / *：refs / remotes / origin / *
    url = git@github.com:tiimgreen / github-cheat-sheet.git
    fetch = + refs / pull / * / head：refs / remotes / origin / pr / *
```

对于基于Fork的Pull Request贡献，“checkout”表示Pull Request的远程分支并从中创建一个本地分支是很有用的：

```bash
$ git checkout pr / 42 pr-42
```

或者，如果您处理更多存储库，则可以在全局git配置中全局配置提取请求.

```bash
git config --global --add remote.origin.fetch“+ refs / pull / * / head：refs / remotes / origin / pr / *”
```

这样，您可以在所有存储库中使用以下简短命令：

```bash
git fetch origin
```

```bash
git checkout pr / 42
```

[*Read more about checking out pull requests locally.*](https://help.github.com/articles/checking-out-pull-requests-locally/)

### Empty Commits
通过添加`--allow-empty`可以推送提交而无需更改代码：

```bash
$ git commit -m“Big-ass commit” - 允许为空
```

一些用例（有意义）包括：

 - 注释新批量工作或新功能的开始.
 - 在对项目进行非代码相关更改时进行记录.
 - 与使用您的存储库的人进行通信.
 - 存储库的第一次提交：`git commit -m“初始提交”--allow-empty`.

### Styled Git Status
Running:

```bash
$ git状态
```

produces:

![git status](http://i.imgur.com/qjPyvXb.png)

添加`-sb`：

```bash
$ git status -sb
```

这是产生的：

![git status -sb](http://i.imgur.com/K0OY3nm.png)

[*Read more about the Git `status` command.*](http://git-scm.com/docs/git-status)

### Styled Git Log
Running:

```bash
$ git log --all --graph --pretty = format：&#39;％Cred％h％Creset  - ％C（auto）％d％Creset％s％Cgreen（％cr）％C（粗体蓝色）&lt;％an&gt; ％Creset&#39;--abbrev-commit --date = relative
```

produces:

![git log --all --graph --pretty=format:'%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative](http://i.imgur.com/58eOtkW.png)

归功于 [Palesz](http://stackoverflow.com/users/88355/palesz)

*可以使用找到的说明对其进行别名处理 [here](https://github.com/tiimgreen/github-cheat-sheet#aliases).*

[*Read more about the Git `log` command.*](http://git-scm.com/docs/git-log)

### Git Query
Git查询允许您搜索所有先前的提交消息，并查找与查询匹配的最新提交消息.

```bash
$ git show：/ query
```

其中`query`（区分大小写）是您要搜索的术语，然后查找最后一个并提供有关已更改行的详细信息.

```bash
$ git show：/ typo
```
![git show :/query](http://i.imgur.com/icaGiNt.png)

*按`q`退出.*


### Git Grep

Git Grep将返回与模式匹配的行列表.

Running:
```bash
$ git grep别名
```
将显示包含字符串* aliases *的所有文件.

![git grep aliases](http://i.imgur.com/DL2zpQ9.png)

*按`q`退出.*

 您还可以使用多个标志进行更高级的搜索.  例如：

 *`-e`下一个参数是模式（例如，正则表达式）
 *`--and`，`--or`和`--not`组合多种模式.

像这样使用它：
```bash
 $ git grep -e pattern  - 和-e anotherpattern
```

[*Read more about the Git `grep` command.*](http://git-scm.com/docs/git-grep)

### Merged Branches
Running:

```bash
$ git branch --merged
```

将为您提供已合并到当前分支的所有分支的列表.

Conversely:

```bash
$ git branch --no-merged
```

将为您提供尚未合并到当前分支的分支列表.

[*Read more about the Git `branch` command.*](http://git-scm.com/docs/git-branch)

### Fixup and Autosquash
如果先前的提交有错误（可以是HEAD中的一个或多个），例如`abcde`，请在修改问题后运行以下命令：
```bash
$ git commit --fixup = abcde
$ git rebase abcde ^ --autosquash -i
```
[*Read more about the Git `commit` command.*](http://git-scm.com/docs/git-commit)
[*Read more about the Git `rebase` command.*](http://git-scm.com/docs/git-rebase)

### Web Server for Browsing Local Repositories
 使用Git`instaweb`命令立即浏览`gitweb`中的工作存储库.  此命令是一个简单的脚本，用于设置`gitweb`和用于浏览本地存储库的Web服务器.

```bash
$ git instaweb
```

opens:

![Git instaweb](http://i.imgur.com/Dxekmqc.png)

[*Read more about the Git `instaweb` command.*](http://git-scm.com/docs/git-instaweb)

### Git Configurations
你的`.gitconfig`文件包含你所有的Git配置.

#### Aliases
 别名是帮助您定义自己的git调用的助手.  例如，你可以设置`git a`来运行`git add --all`.

要添加别名，请导航到`〜/ .gitconfig`并按以下格式填写：

```
[alias]
  co =结账
  cm =提交
  p =推
  # 显示有关标签，分支或遥控器的详细输出
  tags = tag -l
  branches = branch -a
  remotes = remote -v
```

...或键入命令行：

```bash
$ git config --global alias.new_alias git_function
```

例如：

```bash
$ git config --global alias.cm commit
```

对于具有多个函数的别名，请使用引号：

```bash
 $ git config --global alias.ac&#39;add -A.  &amp;&amp; commit&#39;
```

一些有用的别名包括：

 |  别名|  命令|  输入什么|
| --- | --- | --- |
 |  `git cm` |  `git commit` |  `git config --global alias.cm commit` |
 |  `git co` |  `git checkout` |  `git config --global alias.co checkout` |
 |  `git ac` |  `git add.  -A``git commit` |  `git config --global alias.ac&#39;！git add -A &amp;&amp; git commit&#39;` |
 |  `git st` |  `git status -sb` |  `git config --global alias.st&#39;status -sb&#39;` |
 |  `git tags` |  `git tag -l` |  `git config --global alias.tags&#39;tag -l&#39;` |
 |  `git branches` |  `git branch -a` |  `git config --global alias.branches&#39;branch -a&#39;` |
 |  `git cleanup` |  `git branch --merged \ |  grep -v&#39;*&#39;\ |  xargs git branch -d` |  `git config --global alias.cleanup“！git branch --merged \ | grep -v&#39;*&#39;\ | xargs git branch -d”`|
 |  `git remotes` |  `git remote -v` |  `git config --global alias.remotes&#39;remote -v&#39;` |
 |  `git lg` |  `git log --color --graph --pretty = format：&#39;％Cred％h％Creset  - ％C（黄色）％d％Creset％s％Cgreen（％cr）％C（粗体蓝色）&lt;％an&gt; ％Creset&#39; - 简称 - 提交 -  | |  `git config --global alias.lg“log --color --graph --pretty = format：&#39;％Cred％h％Creset  - ％C（黄色）％d％Creset％s％Cgreen（％cr）％C （粗体蓝色）&lt;％an&gt;％Creset&#39; - 简称 - 提交 - “`|

*一些别名取自 [@mathiasbynens](https://github.com/mathiasbynens) dotfiles：https：//github.com/mathiasbynens/dotfiles/blob/master/.gitconfig*

#### Auto-Correct
 Git为拼写错误的命令提供建议，如果启用了自动更正，则可以自动修复和执行命令.  通过指定一个整数来启用自动更正，该整数是git运行更正命令之前的十分之一秒的延迟.  零是默认值，不进行校正，负值将无延迟地运行校正的命令.

例如，如果你输入`git comit`，你会得到这个：

```bash
$ git comit -m“消息”
## git: 'comit' is not a git command. See 'git --help'.

## Did you mean this?
##   commit
```

可以像这样启用自动校正（延迟1.5秒）：

```bash
$ git config --global help.autocorrect 15
```

所以现在命令`git comit`将自动更正为`git commit`，如下所示：

```bash
$ git comit -m“消息”
## WARNING: You called a Git command named 'comit', which does not exist.
## Continuing under the assumption that you meant 'commit'
## in 1.5 seconds automatically...
```

The delay before git will rerun the command is so the user has time to abort.

#### Color
要为Git输出添加更多颜色：

```bash
$ git config --global color.ui 1
```

[*Read more about the Git `config` command.*](http://git-scm.com/docs/git-config)

### Git Resources
 |  标题|  链接|
| ----- | ---- |
 |  官方Git网站|  http://git-scm.com/ |
 |  官方Git视频教程|  http://git-scm.com/videos |
 |  Code School试试Git |  http://try.github.com/ |
 |  Git的入门参考和教程|  http://gitref.org/ |
 |  官方Git教程|  http://git-scm.com/docs/gittutorial |
 |  每天Git |  http://git-scm.com/docs/everyday |
 |  Git Immersion |  http://gitimmersion.com/ |
 |  Git God |  https://github.com/gorosgobe/git-god |
 |  Git for Computer Scientists |  http://eagain.net/articles/git-for-computer-scientists/ |
 |  Git Magic |  http://www-cs-students.stanford.edu/~blynn/gitmagic/ |
 |  GitHub培训套件|  https://training.github.com/kit/ |
| Git Visualization Playground | http://onlywei.github.io/explain-git-with-d3/#freeplay |
 |  学习Git分支|  http://pcottle.github.io/learnGitBranching/ |
 |  一组有用的.gitignore模板|  https://github.com/github/gitignore |
 |  Unixorn的git-extra-commands集合git脚本|  https://github.com/unixorn/git-extra-commands |

#### Git Books
 |  标题|  链接|
| ----- | ---- |
 |  使用Git进行语用版本控制  https://pragprog.com/titles/tsgit/pragmatic-version-control-using-git |
 |  去专业|  http://git-scm.com/book |
 |  Git Internals PluralSight |  https://github.com/pluralsight/git-internals-pdf |
 |  Git in the Trenches |  http://cbx33.github.io/gitt/ |
 |  使用Git进行版本控制|  http://www.amazon.com/Version-Control-Git-collaborative-development/dp/1449316387 |
 |  Git的实用指南|  https://pragprog.com/titles/pg_git/pragmatic-guide-to-git |
 |  Git：每个人的版本控制|  https://www.packtpub.com/application-development/git-version-control-everyone |

#### Git Videos
 |  标题|  链接|
| ----- | ---- |
 |  Linus Torvalds on Git |  https://www.youtube.com/watch?v=4XpnKHJAok8 |
 |  与Scott Chacon一起介绍Git  https://www.youtube.com/watch?v=ZDR433b0HJY |
 |  来自比特的Git |  https://www.youtube.com/watch?v=MYP56QJpDr4 |
 |  图形，哈希和压缩，哦，我的！  |  https://www.youtube.com/watch?v=ig5E8CcdM9g |
 |  GitHub培训与指南|  https://www.youtube.com/watch?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-&amp;v=FyfwLX4HAxM |

#### Git Articles
 |  标题|  链接|
| ----- | ---- |
 |  GitHub Flow |  http://scottchacon.com/2011/08/31/github-flow.html |
