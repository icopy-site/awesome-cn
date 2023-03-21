<div class="github-widget" data-repo="mhinz/vim-galore"></div>
<div align='center'>
  <br /><br /><br />
  <img src='https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/logo-vim-galore.png' alt='vim-galore logo' />
  <br /><br /><br /><br />
  <div>
    <a href='https://github.com/wsdjeg/vim-galore-zh_cn'>中文</a>|
    <a href='http://postd.cc/?s=vim-galore'>日语</a>|
    <a href='https://github.com/lsrdg/vim-galore'>葡萄牙语</a>|
    <a href='http://givi.olnd.ru/vim-galore/vim-galore-ru.html'>俄语</a>|
    <a href='https://github.com/kyoz/vim-galore-vi'>越南语</a>
    <div>
      <br />
      <sub>根据<a href='https://creativecommons.org/licenses/by-sa/4.0'>CC BY-SA 4.0</a>许可<a/>.</a></sub>
    </div>
  </div>
  <br /><br />
</div>










- [:global and :vglobal](#global-and-vglobal) - 在所有匹配的行上执行命令.
- [:normal and :execute](#normal-and-execute) - 脚本梦之队.
- [:redir and execute()](#redir-and-execute) - 捕获命令输出.











### [List of colorschemes](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#colorschemes-1)

### [List of plugins](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md)

<br>

## Intro

## What is Vim?

[Vim](http://www.vim.org) 是一个文本编辑器，有着悠久的祖先
回到 [qed](https://en.wikipedia.org/wiki/QED_(text_editor) ).  [布拉姆
Molenaar](https://en.wikipedia.org/wiki/Bram_Molenaar) 在

该项目在线托管于 [vim.org](http://www.vim.org/index.php).

获取 Vim：使用您最喜欢的包管理器或访问 [下载
page](http://www.vim.org/download.php) 来自 vim.org.

讨论和用户问题最好在
[vim_use](https://groups.google.com/forum/#!forum/vim_use) 邮件列表或使用
互联网资源中心 ([Freenode](https://freenode.net)) in the `#vim` channel.

发展发生在 [GitHub](https://github.com/vim/vim), 关于的讨论
[vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮件列表.

Read [Why, oh WHY, do those #?@! nutheads use
vi?](http://www.viemu.com/a-why-vi-vim.html) 查看常见的误解
维姆解释道.

## The Vim Philosophy

 Vim 坚持模态编辑哲学. 这意味着它提供
多种模式，键的含义根据模式而变化. 你
以_正常模式_导航文件，在_插入模式_中插入文本，您选择
_visual mode_中的行，您可以在_command-line mode_中访问命令，依此类推.
乍一听这听起来很复杂，但它有一个巨大的优势：你不需要
一次按住几个键会弄断你的手指，大多数时候你
只需一个接一个地按下它们. 任务越常见，键越少
是需要的.

与模态编辑配合良好的相关概念是运算符和动作.
_Operators_ 开始某个动作，例如更改、删除或选择文本.
之后，您可以使用 _motion_ 指定要作用的文本区域.
要更改括号内的所有内容，请使用 `ci(`（阅读 _change inner
括号_）. 要删除整段文本，请使用 `dap`（阅读 _delete
围绕段落_).

如果你看到高级 Vim 用户在工作，你会注意到他们说
 _Vim 语言_以及钢琴家处理他们的乐器. 复杂
只需按几下按键即可完成操作. 他们想都没想
不再是 [muscle memory](https://en.wikipedia.org/wiki/Muscle_memory) 拿
已经结束了这减少了[认知
load](https://en.wikipedia.org/wiki/Cognitive_load) 并有助于专注于
实际任务.

## First steps

Vim 捆绑了一个交互式教程，教授最基本
你需要知道的事情. 你可以从 shell 启动它：

```
$ vimtutor
```

不要被它看起来多么无聊而推迟并完成练习. 这
您之前使用的编辑器或 IDE 很可能都是非模态的，因此通过
切换模式一开始会显得很别扭，但是你越用 Vim，就越
它成为了 [muscle memory](https://en.wikipedia.org/wiki/Muscle_memory).

Vim 被固定在 [Stevie](https://en.wikipedia.org/wiki/Stevie_(text_editor)）， A
[vi](https://en.wikipedia.org/wiki/Vi) 克隆，并支持两种操作模式：
 “兼容”和“不兼容”. 在兼容模式下使用 Vim 意味着使用 vi
所有选项的默认值，与 Vim 的默认值相反. 只要你没有创造
一个用户 vimrc 或用 `vim -N` 启动 Vim，假设是兼容模式！ 不
在兼容模式下使用 Vim. 只是不要.

下一步：

1. 创建你自己 [vimrc](#minimal-vimrc).
2. 来点 [cheatsheets](#cheatsheets) 准备好第一周.
3.通读 [basics](#basics-1) 部分了解什么是可能的.
 4.按需学习！ 你永远学不完 Vim. 如果你遇到任何
   问题，只能在网上找. 你的问题已经解决了.
   Vim 附带了很好的文档，并且必须知道如何浏览它：
   [Getting help offline](#getting-help-offline).
5.看看 [additional resources](#additional-resources).

最后一个建议：在开始添加所有内容之前，请学习如何正确使用 Vim
各种炒作 [plugins](#managing-plugins) 只实现那些功能
Vim 已经原生支持.

## Minimal vimrc

用户vimrc可以放到`~/.vimrc`或者为了更好的分离
进入 ~/.vim/vimrc . 后者可以很容易地把整个配置
在版本控制下并将其上传到 GitHub.

你在网上找到很多“最小的 vimrcs”，也许我的版本不是
它应该是最小的，但它提供了我认为的一组很好的理智设置
对开始有用.

最终你必须阅读所有提到的设置并决定
为自己.  :-)

所以这里是： [minimal-vimrc](https://github.com/mhinz/vim-galore/blob/master/static/minimal-vimrc.vim)

如果你有兴趣，这里是
[my vimrc](https://github.com/mhinz/dotfiles/blob/master/.vim/vimrc).

**提示**：大多数插件作者维护多个插件并发布他们的插件
GitHub 上的 vimrc（通常在名为“vim-config”或“dotfiles”的存储库中），所以
每当您找到喜欢的插件时，请查看其维护者的 GitHub 页面并
查看存储库.

## What kind of Vim am I running?

查看 `:version` 会给你所有你需要知道的信息
当前运行的 Vim 二进制文件是如何编译的.

第一行告诉您二进制文件的编译时间和版本，例如 7.4.
下一行中的一行指出“Included patches: 1-1051”，这是补丁
等级. 因此，您的确切 Vim 版本是 7.4.1051.

另一行表示类似“没有 GUI 的小版本”或“大版本”
与 GUI`. 显而易见的信息是你的 Vim 是否包含 GUI
支持，例如从 shell 启动 `gvim` 或从 Vim 运行 `:gui`
在终端仿真器中. 另一个重要信息是“Tiny”和
 `巨大`.  Vim 区分称为 `tiny`、`small`、`normal`、
`big` 和 `huge`，都支持不同的功能子集.

`:version` 的大部分输出都被功能列表本身消耗掉了.
`+clipboard` 表示编译了剪贴板功能，`-clipboard` 表示它
没有编译进去.

需要编译一些 Vim 特性才能使它们工作. 例如 `:prof` 到
工作，你需要一个具有大量功能集的 Vim，因为该集使
`+个人资料` 功能.

如果不是这样，并且你是从包管理器安装 Vim，请确保
安装名为“vim-x”、“vim-x11”、“vim-gtk”、“vim-gnome”或
类似的，因为这些软件包通常带有大量的功能集.

您还可以以编程方式测试版本或功能：

```vim
&quot; 如果至少运行 Vim 7.4.42 并启用 +profile，请执行某些操作.
if (v:version &gt; 704 || v:version == 704 &amp;&amp; has(&#39;patch42&#39;)) &amp;&amp; has(&#39;profile&#39;)
  “ 做东西
endif
```

Help:

```
：h：版本
:h 功能列表
:h +功能列表
:h 有补丁
```

## Cheatsheets

- http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png
- https://cdn.shopify.com/s/files/1/0165/4168/files/preview.png
- http://michael.peopleofhonoronly.com/vim/vim_cheat_sheet_for_programmers_screen.png
- http://www.rosipov.com/images/posts/vim-movement-commands-cheatsheet.png

或者从 Vim 中快速打开备忘单： [vim-cheat40](https://github.com/lifepillar/vim-cheat40).

## Basics

## Buffers, windows, tabs

 Vim 是一个文本编辑器. 每次显示文本时，文本都是
 **缓冲**. 每个文件将在其自己的缓冲区中打开. 插件显示内容
他们自己的缓冲区等

缓冲区有很多属性，例如它包含的文本是否可修改，
或者它是否与文件相关联，因此需要同步到
磁盘保存.

 **Windows** 是视口 _onto_ 缓冲区. 如果你想查看多个文件
同一文件的同一时间甚至不同位置，您使用 windows.

请不要称它们为_splits_. 您可以将窗口一分为二，但是
这不会让他们_splits_.

窗口可以垂直或水平分割，高度和宽度
现有窗口也可以更改. 因此，您可以使用任何窗口
你喜欢的布局.

 **标签页**（或只是标签）是窗口的集合. 因此，如果你想
使用多个窗口布局，使用选项卡.

简而言之，如果你不带参数启动 Vim，你将拥有一个
包含一个显示一个缓冲区的窗口的标签页.

顺便说一句，缓冲区列表是全局的，你可以从任何地方访问任何缓冲区
tab.

## Active, loaded, listed, named buffers

像这样运行 Vim `vim file1`. 该文件的内容将被加载到缓冲区中.
你现在有一个**加载的缓冲区**. 缓冲区的内容只被同步
到磁盘（写回文件）如果你在 Vim 中保存它.

由于缓冲区也显示在窗口中，因此它也是一个**活动缓冲区**. 现在
如果你通过 `:e file2` 加载另一个文件，`file1` 将成为一个**隐藏缓冲区**
和 `file2` 是活动的.

两个缓冲区也被**列出**，因此它们将在输出中列出
 `:ls`. 插件缓冲区或帮助缓冲区通常被标记为未列出，因为
它们不是您通常使用文本编辑器编辑的常规文件. 上市和
未列出的缓冲区可以通过 :ls! 显示.

**未命名缓冲区**，也经常被插件使用，是没有名字的缓冲区
关联的文件名. 例如 :enew 将创建一个未命名的暂存缓冲区. 添加
一些文本并通过 `:w /tmp/foo` 将其写入磁盘，它将成为一个命名
buffer.

## Argument list

The [global buffer list](#buffers-windows-tabs) 是 Vim 的东西. 在此之前，在
vi，以前只有参数列表，Vim也有.

在 shell 命令行上给 Vim 的每个文件名，都被记住在
参数列表. 可以有多个参数列表：默认情况下所有参数
被放入全局参数列表，但你可以使用 `:arglocal` 来创建一个
窗口本地的新参数列表.

使用 :args 列出当前参数. 根据参数在文件之间切换
列出 `:next`、`:previous`、`:first`、`:last` 和朋友. 改变它
`:argadd`、`:argdelete` 或 `:args` 以及文件列表.

如果您更喜欢使用缓冲区或参数列表来处理文件是
品味问题. 我的印象是大多数人使用缓冲区列表
exclusively.

然而，参数列表有一个巨大的用例：批处理
通过`:argdo`！ 一个简单的重构示例：

```vim
:args **/*.[ch]
 :argdo %s/foo/bar/ge | 更新
```

这会将所有 C 源文件和头文件中所有出现的“foo”替换为“bar”
从当前目录及以下.

帮助：`:h 参数列表`

## Mappings

您可以使用 `:map` 命令系列定义您自己的映射. 每个
该系列的命令定义了一组特定模式的映射. 技术上
 Vim 带有多达 12 种模式，其中 6 种可以映射. 此外，一些
命令一次作用于多种模式.

 | 递归 | 非递归 | 取消映射 | 模式 |
|-----------|---------------|-----------|----------------------------------|
 |  `：地图` |  `:noremap` |  `：取消映射` | 正常，视觉，等待操作员 |
 |  `:nmap` |  `:nnoremap` |  `:nunmap` | 正常 |
 |  `:xmap` |  `:xnoremap` |  `:xunmap` | 视觉 |
 |  `:cmap` |  `:cnoremap` |  `:cunmap` | 命令行 |
 |  `:omap` |  `:onoremap` |  `:ounmap` | 运营商待定 |
 |  `:imap` |  `:inoremap` |  `:iunmap` | 插入 |

例如，这仅定义了正常模式的映射：

```vim
 :nmap<space>  ：回声“富”<cr>
```

使用 `:nunmap 再次取消映射<space> `.

对于更多但不常见的模式（或它们的组合），请参见`:h
map-modes`.

到目前为止，一切都很好. 只有一个问题可能会让人非常困惑
初学者：`:nmap` 是_递归的_！ 也就是说，右手边取其他
映射考虑在内.

因此，您定义了一个简单地回应“Foo”的映射：

```vim
:nmap b :echo &quot;Foo&quot;<cr>
```

但是如果你想将 `b` 的默认行为（返回一个词）映射到
另一把钥匙？

```vim
:nmap ab
```

如果你点击<kbd>a</kbd> ，我们希望光标返回一个单词，但相反
 “Foo”打印在命令行中！ 因为右边的 b 是
已经映射到另一个动作，即 `:echo &quot;Foo&quot;<cr>  `.

解决这个问题的正确方法是使用_non-recursive_映射
instead:

```vim
:nnoremap ab
```

经验法则：始终使用非递归映射，除非递归实际上是
desired.

通过不给出右侧来查找您的映射. 例如 `:nmap` 显示所有
法线映射和`:nmap<leader>  ` 显示所有以
地图领导者.

如果你想禁用标准映射，将它们映射到特殊的`<nop>  `
字符，例如`:noremap<left><nop>  `.

Help:

    :h 键符号
    :h 映射
    :h 05.3

## Mapleader

mapleader 只是一个占位符，可以与自定义映射一起使用，并且
默认设置为“\”.

```vim
地图<leader>小时：帮助grep<space>
```

此映射由 `\h` 触发. 如果你想使用`<space>  h`代替：

```vim
让 mapleader = &#39; &#39;
地图<leader>小时：帮助grep<space>
```

此外，还有`<localleader>  ` 是 ` 的本地对应物<leader> `
并且应该用于缓冲区本地的映射，例如.
特定于文件类型的插件. 它也默认为“\”.

 **注意**：在映射之前设置地图领导者！ 中的所有领导者映射
 effect already, 不会因为 mapleader 改变而改变.  `:nmap
<leader>` 将显示所有正常模式的领导者映射，并解决了 mapleader
已经，所以用它来仔细检查你的映射.

有关更多信息，请参见 `:h mapleader` 和 `:h maplocalleader`.

## Registers

寄存器是保存文本的槽. 将文本复制到寄存器中称为
**从寄存器中提取**和提取文本称为**粘贴**.

Vim 提供了以下寄存器：

 | 类型 | 人物 | 被填?  | 只读？  | 包含文本来自？  |
|---------------------|------------------------|------------|-----------|---------------------|
 | 未命名 |  `&quot;` | vim | [ ] | 最后一次抽取或删除.(`d`, `c`, `s`, `x`, `y`) |
 | 编号 |  `0` 到 `9` | 维姆 |  [ ] | 寄存器“0”：最后一次猛拉. 寄存器 `1`：最后一次删除. 寄存器 `2`：倒数第二个删除. 等等. 将寄存器“​​1”-“9”视为只读 [queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type) ) 有 9 个元素.  |
 | 小删|  `-` | 维姆 |  [ ] | 最后一次删除少于一行.  |
 | 命名 |  `a` 到 `z`，`A` 到 `Z` | 用户 |  [ ] | 如果你猛拉注册`a`，你替换它的文本. 如果您猛拉以注册“A”，则会附加到寄存器“a”中的文本.  |
 | 只读 |  `:`, `.`, `%` | 维姆 |  [x] |  `:`：最后一条命令，`.`：最后插入的文本，`%`：当前文件名.  |
| Alternate buffer    | `#`                    | vim        | [ ]       | Most of the time the previously visited buffer of the current window. See `:h alternate-file` |
 | 表达 |  `=` | 用户 |  [ ] | 评估被抽出的 VimL 表达式. 例如在插入模式下这样做：`<c-r>  =5+5<cr>  ` 和“10”将被插入到缓冲区中.  |
 | 选择|  `+`, `*` | 维姆 |  [ ] |  `*` 和 `+` 是 [clipboard](#clipboard) 寄存器.  |
 | 掉落 |  `~` | 维姆 |  [x] | 从上次拖放.  |
 | 黑洞 |  `_` | 维姆 |  [ ] | 如果您不希望任何其他寄存器受到隐式影响. 例如，`&quot;_dd` 删除当前行而不影响寄存器`&quot;`、`1`、`+`、`*`.  |
 | 上次搜索模式 |  `/` | 维姆 |  [ ] | 与 `/`、`?`、`:global` 等一起使用的最后一个模式.

每个非只读的寄存器都可以由用户设置：

```vim
:let @/ = &#39;注册&#39;
```

之后<kbd>n</kbd>会跳转到下一次出现的“register”.

当寄存器被隐式填充时有很多例外，所以一定要
读取`:h 寄存器`.

使用 `y` 复制并使用 `p`/`P` 粘贴，但请注意 Vim 区分
 characterwise 和 linewise 视觉选择. 参见`:h linewise`.

**示例：按行**

`yy`（或只是`Y`）拉出当前行，将光标移动到其他地方，使用
`p` 粘贴到当前行下方 `P` 粘贴到它上面.

**示例：charwise**

用 `0yw` 拉出第一个单词，移动到其他地方，粘贴到光标后
当前行与 `p` 和光标前与 `P`.

**示例：寄存器的显式命名**

`&quot;aY` 将当前行拉入寄存器 `a`.移动到另一行.`&quot;AY`
附加当前行以注册 `a`.

我建议尝试一下所有这些寄存器并不断检查
`:reg`，所以你可以看到实际发生了什么.

**有趣的事实**：在 Emacs 中，“yanking”代表粘贴（或之前的 _reinserting
killed text_) 不复制.

## Ranges

范围很容易理解，但许多 Vimmer 不知道他们的范围
充分的潜力.

- 许多命令都有范围.
- 地址表示特定行.
- 范围可以是单个地址，也可以是一对由任一地址分隔的地址
  `,` 或 `;`.
- 范围告诉命令要作用于哪一行.
 - 默认情况下，大多数命令仅作用于当前行. 值得注意的例外是
  `:write` 和 `:global` 作用于所有行.

范围的使用非常直观，所以这里有一些例子（使用 `:d`
作为 `:delete` 的缩写形式）：

 | 命令 | 行作用于 |
|---------|----------------|
 |  `:d` | 当前行.  |
 |  `:.d` | 当前行.  |
 |  `:1d` | 第一行.  |
 |  `:$d` | 最后一行.  |
 |  `:1,$d` | 所有线路.  |
 |  `:%d` | 所有行（`1,$` 的语法糖）.  |
 |  `:.,5d` | 当前行到第 5 行.
 |  `:,5d` | 也是当前行到第 5 行.
 |  `:,+3d` | 当前行和接下来的 3 行.  |
 |  `:1,+3d` | 第一行到当前行 + 3.
 |  `:,-3d` | 当前行和最后 3 行.  （Vim 会提示你，因为这是一个反转的范围.） |
 |  `:3,&#39;xdelete` | 第 3 行到标记的行 [mark](#marks)  X.  |
 |  `:/^foo/,$delete` | 从以“foo”开头的下一行到结尾.  |
 |  `:/^foo/+1,$delete` | 从以“foo”开头的行之后的行到结尾.  |

请注意，代替 `,`，`;` 可以用作分隔符. 不同之处在于
在 `from,to` 的情况下，_to_ 是相对于当前行的，但是当
使用 `from;to`，_to_ 是相对于 _from_ 的地址的！ 假设你是
在第 5 行，`:1,+1d` 会删除第 1 到 6 行，而 `:1;+1d` 只会
删除第 1 行和第 2 行.

 `/` 地址前面可以有另一个地址. 这允许你_stack_
模式，例如：

```vim
:/foo//bar//quux/d
```

这将删除第一行之后包含“quux”的第一行
在第一行之后包含“bar”，在当前行之后包含“foo”.

有时 Vim 会自动在命令行前加上一个范围. 例如开始一个
使用 `V` 进行视觉行选择，选择一些行并键入 `:`. 命令行
将填充范围`&#39;&lt;,&#39;&gt;`，这意味着以下命令将
使用先前选择的行作为范围.  （这也是为什么你有时
查看类似`:vnoremap foo 的映射：<c-u> 命令`. 这里`<c-u>  ` 用于删除
范围，因为 Vim 在给命令指定范围时会抛出错误
不支持.）

另一个例子是在正常模式下使用 `!!`. 这将填充
带有 `:.!` 的命令行. 如果后跟外部程序，则该程序
输出将替换当前行. 所以你可以替换当前
使用 `:?^$?+1,/^$/-1!ls` 的 ls 输出段落. 想要！

Help:

```
:h 命令行范围
:h 10.3
```

## Marks

您使用标记来记住文件中的位置，即行号和列.

 | 标记 | 由...设置用法 |
|-------|----------|-------|
 |  `a` - `z` | 用户 | 本地文件，因此仅在一个文件内有效. 跳转到小写标记，表示在当前文件内跳转.  |
 |  `A` - `Z` | 用户 | 全局，因此在文件之间有效. 也称为_文件标记_. 跳转到文件标记可能会切换到另一个缓冲区.  |
 |  `0` - `9` | 信息 |  `0` 是最后写入 viminfo 文件时的位置. 实际上这意味着最后一个 Vim 进程结束的时间.  `1` 是倒数第二个 Vim 进程结束时的位置，依此类推.  |

将`&#39;`/`g&#39;` 或`` ` ``/`` g` `` 放在标记前，形成动议.

使用 `mm` 来记住带有标记“m”的当前位置. 在文件中移动
然后通过 `&#39;m`（第一个非空白）或 `` `m ``（精确列）跳回.
如果你告诉你的 viminfo，小写字母将在退出 Vim 后被记住
要这样做的文件，请参阅 `:h viminfo-&#39;`.

使用 `mM` 记住文件标记为“M”的当前位置. 切换到另一个
缓冲并通过 `&#39;M` 或 `` `M `` 切换回来.

其他动议包括：

 | 运动 | 跳转到.. |
|------------------|-----------|
 |  `&#39;[`, `` `[ `` | 先前更改或抽出的文本的第一行或字符.  |
| `']`, `` `] ``   | Last line or character of previously changed or yanked text. |
| `'<`, `` `< ``   | Beginning line or character of last visual selection. |
 |  `&#39;&gt;`, `` `&gt; `` | 最后一个视觉选择的结束行或字符.  |
 |  `&#39;&#39;`, ``` `` ``` | 最近一次跳跃前的位置.  |
 |  `&#39;&quot;`, `` `&quot; `` | 最后退出当前缓冲区时的位置.  |
 |  `&#39;^`, `` `^ `` | 上次插入停止的位置.  |
 |  `&#39;.`, `` `.  `` | 最后一次更改的位置.  |
 |  `&#39;(`, `` `( `` | 当前句子的开始.|
 |  `&#39;)`, `` `) `` | 当前句子的结尾.  |
 |  `&#39;{`, `` `{ `` | 当前段落的开头.  |
 |  `&#39;}`, `` `} `` | 当前段落结束.  |

标记也可以用于 [range](#ranges) . 你可能以前看过这个
想知道这是什么意思：在可视模式下选择一些文本并执行 `:`，
命令行将以 `:&#39;&lt;,&#39;&gt;` 开头，这意味着以下命令
会得到一个表示视觉选择的范围.

使用 `:marks` 列出所有标记. 阅读 `:h mark-motions` 中的所有内容.

## Completion

 Vim 提供多种插入模式补全. 如果有多个
比赛，弹出菜单将让您导航到您选择的比赛.

典型的完成类型是标签、来自导入模块的函数或
当前缓冲区中的库、文件名、字典或简单的单词.

Vim 为每种完成提供了一个映射，它们都以
 `<c-x>  `（记得在插入模式下使用它们）：

 | 制图 | 亲切 | 帮助 |
|---------|------|--------------|
 |  `<c-x><c-l>  ` | 整行 |  `:hi^x^l` |
 |  `<c-x><c-n>  ` | 当前文件中的关键字 |  `:hi^x^n` |
 |  `<c-x><c-k>  ` |  `&#39;dictionary&#39;` 选项中的关键字 |  `:hi^x^k` |
| `<c-x><c-t>` | keywords from `'thesaurus'` option | `:h i^x^t` |
 |  `<c-x><c-i>  ` | 当前文件和包含文件中的关键字 |  `:hi^x^i` |
 |  `<c-x><c-]>  ` | 标签 |  `:hi^x^]` |
 |  `<c-x><c-f>  ` | 文件名 |  `:hi^x^f` |
 |  `<c-x><c-d>  ` | 定义或宏 |  `:hi^x^d` |
 |  `<c-x><c-v>  ` |  Vim 命令 |  `:hi^x^v` |
 |  `<c-x><c-u>  ` | 用户定义（如“completefunc”中指定）|  `:hi^x^u` |
 |  `<c-x><c-o>  ` | 全向补全（在 `&#39;omnifunc&#39;` 中指定）|  `:hi^x^o` |
 |  `<c-x>  s` | 拼写建议 |  `:hi^Xs` |

人们可能会对用户定义的完成之间的区别感到困惑
和 omni 完成，但从技术上讲，他们做同样的事情. 他们采取
检查当前位置并返回建议列表的函数.
用户定义的完成由用户为他们自己的个人目的定义.
 （惊喜！）它可以是任何东西.  Omni 补全适用于特定文件类型
目的，如完成结构成员或类方法，通常由
文件类型插件.

Vim 还允许通过设置
 “完整”选项. 默认情况下，该选项包括很多，所以一定要
根据你的口味修剪它. 您可以使用 ` 触发此完成<c-n> `
 （下一个）和`<c-p>  `（上一个），这也恰好是用于
在弹出菜单中选择条目. 有关更多信息，请参见 `:hi^n` 和 `:h &#39;complete&#39;`
this.

请务必检查 `:h &#39;completeopt&#39;` 以配置
弹出菜单. 默认值非常合理，但我更喜欢添加“noselect”.

Help:

```
:h ins-完成
:h 弹出菜单键
:h new-omni-completion
```

## Motions, operators, text objects

 **动作**移动光标. 你们都知道`h`/`j`/`k`/`l`. 或者 `w` 和 `b`. 甚至
 `/` 是一个动议. 他们也进行计数.  `2？<cr>  ` 跳到倒数第二个
“the”的出现.

查看 `:h navigation` 和下面所有可用的动作.

**运算符**作用于文本区域，例如`d`、`~`、`gU`、`&gt;`
很少. 它们在两种情况下使用，要么在正常模式下，要么在可视模式下. 在正常情况下
模式，运算符先出现，然后是动作，例如 `&gt;j`. 在视觉模式下，
运算符只是对选择进行操作，例如“Vjd”.

像动作一样，运算符进行计数，例如 `2gUw` 使当前的其余部分
单词和下一个大写. 由于运动和运算符需要计数，
`2gU2w` 也能正常工作并执行 `gU2w` 两次.

有关所有可用的运算符，请参见 `:h operator`. 使用 `:set tildeop` 来制作 `~`
充当操作员.

**文本对象**作用于周围区域，与作用于周围区域的动作相反
一个方向. 实际上它们作用于对象，例如一个完整的词，一个整体
句子，括号之间的所有内容，等等.

文本对象不能用于在正常模式下移动光标，因为即使是
最熟练的游标不能同时跳到两个方向. 有用
但是在可视模式下，因为对象的一侧已经被选中
光标只是跳到另一边.

文本对象以“i”（想想_inner_）或“a”（想想_around_）开头
后跟一个表示对象的字符. 使用 `i` 它只作用于对象
本身，在对象上加上尾随空格. 例如 `diw` 删除了
当前单词和 `ci(` 会更改括号内的所有内容.

文本对象进行计数. 想象一下`((( )))`和光标在
大多数内括号，然后 `d2a(` 将删除 2 对内括号
以及介于两者之间的一切.

有关所有可用的文本对象，请参阅 `:h text-objects`.

## Autocmds

你可以在 Vim 中的许多事件之后触发一个动作，比如一个缓冲区被
通过所谓的 _autocmds_ 保存或启动 Vim.

 Vim 广泛依赖于自动命令. 不相信我？ 检查`:au`，但不要让
输出压倒了你. 这些都是有效的自动命令
now!

请参阅 `:h {event}` 以快速了解所有可用事件和 `:h
autocmd-events-abc` 了解更多详情.

一个典型的例子是特定于文件类型的设置：

```vim
autocmd FileType ruby​​ setlocal shiftwidth=2 softtabstop=2 comments-=:#
```

但是缓冲区怎么知道它包含 Ruby 代码呢？ 因为另一个
autocmd 检测到它并相应地再次设置文件类型
触发了 `FileType` 事件.

每个人添加到 vimrc 的第一件事就是 `filetype on`. 这
只是意味着 `filetype.vim` 在启动时被读取，它设置了 autocmds
几乎所有文件类型都在阳光下.

如果你足够勇敢，看看它：`:e $VIMRUNTIME/filetype.vim`. 搜索
对于“Ruby”，你会发现 Vim 只是使用文件扩展名 `.rb` 来
检测 Ruby 文件：

**注意**：同一事件的 Autocmd 将按照它们执行的顺序执行
创建.  `:au` 以正确的顺序显示它们.

```vim
au BufNewFile,BufRead *.rb,*.rbw setf 红宝石
```

这种情况下的 BufNewFile 和 BufRead 事件在 C 语言中被硬编码
Vim 的来源，每次你通过 `:e` 和类似的方式打开文件时都会发出
命令. 之后，`filetype.vim` 中的所有数百个文件类型都是
测试.

简而言之，Vim 大量使用事件和自动命令，但也
公开一个干净的接口以挂接到该事件驱动系统
customization.

帮助：`:h 自动命令`

## Changelist, jumplist

最后 100 个更改的位置保存在 **changelist** 中. 一些
同一行上的小改动会合并在一起，但位置会
尽管如此（如果你在中间添加了一些东西）
线）.

每次跳跃时，跳跃前的位置都会被记住
 **跳转列表**. 跳转列表最多包含 100 个条目. 每个窗口都有自己
跳转列表. 拆分窗口时，将复制跳转列表.

跳转是以下命令之一：`&#39;`, `` ` ``, `G`, `/`, `?`, `n`, `N`,
`%`, `(`, `)`, `[[`, `]]`, `{`, `}`, `:s`, `:tag`, `L`, `M`, `H ` 和命令
开始编辑一个新文件.

 | 清单 | 列出所有条目 | 转到旧位置 | 去更新的位置 |
|------------|------------------|----------------------|----------------------|
 | 跳转列表 |  `：跳跃` |  `[计数]<c-o>  ` |  `[计数]<c-i>  ` |
 | 更改列表 |  `：改变` |  `[计数]g;` |  `[计数]g,` |

当您列出所有条目时，标记`&gt;`将用于显示当前
位置. 通常这将低于位置 1，即最新位置.

如果你想让两个列表在重启 Vim 后仍然存在，你需要使用
viminfo 文件和 `:h viminfo-&#39;`.

并且可以通过 ``` `` ``` 或 `&#39;&#39;` 跳转到.

Help:

```
:h changelist
:h 跳转列表
```

## Undo tree

会记住文本状态的最新更改. 您可以使用_undo_来
还原更改和_redo_ 以重新应用以前还原的更改.

理解它的重要一点是持有最近的数据结构
变化不是
[queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) 但一个
[tree](https://en.wikipedia.org/wiki/Tree_(data_structure) ）！ 您的更改是
树中的节点，每个节点（但顶部节点除外）都有一个父节点. 每个节点保留
有关更改的文本和时间的信息. 分支是一系列节点
从任意一个节点开始，一直向上到顶层节点. 新分支创建时
您撤消更改，然后插入其他内容.

```
ifoo<esc>
obar<esc>
obaz<esc>
u
oquux<esc>
```

现在你有 3 行，撤消树看起来像这样：

```
     富（1）
       /
    酒吧(2)
   /      \
baz(3) quux(4)
```

撤消树有 4 个更改. 数字代表节点所在的时间
created.

现在有两种遍历这棵树的方法，我们称它们为_branch-wise_和
_time-wise_.

撤消 (`u`) 和重做 (`<c-r>  `) 按分支工作. 他们上下电流
分支.  `u` 会将文本状态恢复为节点“bar”之一. 另一个`你`
将进一步恢复文本状态，恢复到节点“foo”之一. 现在`<c-r>  `
回到节点“bar”的状态和另一个`<c-r>  ` 到节点的状态
 “曲”.  （无法再使用分支命令到达节点“baz”.）

与此相反，`g-` 和 `g+` 按时间工作. 因此，`g-` 不会恢复到
节点“bar”的状态，就像“u”一样，但是是按时间顺序排列的前一个状态，
节点“baz”. 另一个 `g-` 会将状态恢复为节点“bar”等状态
在. 因此，`g-` 和 `g+` 只是分别在时间上来回移动.

 | 命令/映射 | 行动 |
|-------------------|--------|
 |  `[count]u`, `:undo [count]` | 撤消 [count] 次更改.  |
 |  `[计数]<c-r>  `, `:重做` | 重做 [计数] 更改.  |
 |  `你` | 撤消对最新更改行的所有更改.  |
 |  `[count]g-`, `:earlier [count]?` | 转到旧文本状态 [count] 次. 这 ”？” 可以是“s”、“m”、“h”、“d”或“f”. 例如 `:earlier 2d` 进入 2 天前的文本状态.  `:earlier 1f` 将进入最新文件保存状态.  |
 |  `[count]g+`, `:later [count]?` | 同上，但方向不同.  |

撤消树保存在内存中，当 Vim 退出时会丢失. 请参阅 [撤消
files](#undo-files) for how to enable persistent undo.

如果你对撤消树感到困惑，
[undotree](https://github.com/mbbill/undotree) 在可视化方面做得很好
it.

Help:

```
:h 撤消.txt
:h usr_32
```

## Quickfix and location lists

 quickfix 列表是一种保存文件位置的数据结构. 本质上，
quickfix 列表中的每个条目都包含文件路径、行号和
可选列和说明.

典型的用例是汇编编译器错误或 grep 工具的结果.

Vim 有一种特殊类型的缓冲区用于显示 quickfix 列表：quickfix
缓冲.  quickfix 缓冲区中的每一行显示 quickfix 列表中的一个条目.

通常你会打开一个新窗口来显示 quickfix 列表：quickfix 窗口.
发生这种情况时，最后一个窗口将与 quickfix 窗口相关联.

在 quickfix 缓冲区中`<cr>  ` 在关联窗口中打开所选条目
和`<c-w><cr>  ` 在新窗口中.

quickfix 列表以 [Aztec C
compiler](https://en.wikipedia.org/wiki/Aztec_C).

实际上有两种列表：快速修复和位置列表. 他们举止
几乎相同，但有以下区别：

 - 只有一个 quickfix 列表. 可以有多个位置列表； 每一个
  window.
- 他们使用略有不同的导航命令.

 | 行动 | 快速修复 | 地点 |
|----------------|--------------|--------------|
 | 打开窗口 |  `：应对` |  `：步行` |
 | 关闭窗口 |  `:关闭` |  `:lclose` |
 | 下一个条目 |  `:cnext` |  `:lnext` |
 | 上一个条目 |  `:cprevious` |  `:lprevious` |
 | 第一次进入 |  `:cfirst` |  `:lfirst` |
 | 最后一个条目 |  `:clast` |  `:llast` |

请注意，不需要为这些打开 quickfix 和定位窗口
命令工作.

有关更多信息和完整的命令列表，请参阅 :h quickfix .

为了简洁起见，_quickfix_ 和 _location_ 通常缩写为 _qf_ 和
_loc_ 分别.

**Example**:

让我们使用我们的老朋友 grep 来搜索当前目录中的文件
目录递归进行某个查询，并将结果放入 quickfix
list.

```vim
:let &amp;grepprg = &#39;grep -Rn $* .&#39;
 ：伟大的！ 富
<grep output - hit enter>
:copen
```

假设任何文件包含字符串“foo”，它现在应该显示在
快速修复窗口.

## Macros

Vim 允许_recording_ 键入的字符到 [register](#registers) . 它是
即时自动执行某些任务的好方法.  （对于更复杂的任务，Vim
应该改用脚本.）

 - 通过键入 `q` 后跟寄存器开始录制，例如 `q`.  （这
  命令行将通过“记录@q”来表示这一点.）
- 再次按 `q` 停止录制.
- 通过 `[count]@q` 执行宏.
- 通过 `[count]@@` 重复上次使用的宏.

**示例 1：**

插入一行并重复 10 次：

```
qq
iabc<cr><esc>
q
10@q
```

 （没有宏也可以做同样的事情：`oabc<esc>  10.`)

**示例 2：**

要在所有行的前面添加行号，请从第一行开始并添加
 “1.”手动给它. 使用 ` 增加光标下的数字<c-a> `,
显示为`^A`.

```
qq
0yf jP0^A
q
1000@q
```

这里我们只是希望文件不超过 1000 行
使用 `1000@q`，但我们也可以使用_递归宏_，它执行直到
宏不能再应用于一行：

```
qq
0yf jP0^A@q
q
@q
```

（同样可以在没有宏的情况下完成：`:%s/^/\=line(&#39;.&#39;) . &#39;. &#39;`）

请注意，我还展示了如何在不使用宏的情况下实现相同的效果，但这
大多数只适用于这样简单的例子. 对于更复杂的自动化，宏
是炸弹！


Help:

```
:h 录音
:h &#39;懒惰重绘&#39;
```

## Colorschemes

配色方案是设置 Vim 样式的方式.  Vim 由许多组件组成，
每一个都可以为前景定制不同的颜色，
背景和其他一些属性，如粗体文本等.它们可以设置为
this:

```vim
:highlight 正常 ctermbg=1 guibg=red
```

这会将编辑器的背景涂成红色. 有关更多信息，请参见`:h :highlight`
information.

因此，配色方案主要是 `:highlight` 命令的集合.

实际上，大多数配色方案实际上是 2 种配色方案！ 上面的例子设置
通过 `ctermbg` 和 `guibg` 设置颜色. 之前的定义 (`cterm*`) 只会是
如果 Vim 在终端仿真器中启动，例如 xterm，则使用它. 后者 (`gui*`)
将在 gvim 或 MacVim 等图形环境中使用.

如果你碰巧在终端 Vim 中使用了颜色方案，而颜色不
看起来像屏幕截图中的那些，很可能是配色方案
只为 GUI 定义颜色. 相反，如果你使用图形化的 Vim (例如
gvim 或 MacVim) 并且颜色看起来不对，colorscheme 可能只定义
终端的颜色.

后一种情况可以通过在 Neovim 或 Vim 中启用真彩色来“解决”
 7.4.1830 及更新版本. 这使得终端 Vim 改用 GUI 定义，但是
还需要终端仿真器本身以及介于两者之间的所有软件（例如
 tmux）能够处理真彩色.  （[这
gist](https://gist.github.com/XVilka/8346728) 很好地概述了
topic.)

Help:

-`:h &#39;termguicolors&#39;`
- [List of colorschemes](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#colorschemes-1)

## Folding

每个文本（或源代码）都有特定的结构. 如果你有一个结构，它
意味着您有逻辑上分隔的文本区域. 折叠允许“折叠”
这样的区域成一行并显示简短的描述. 有
许多作用于这些区域的命令称为_folds_. 折叠可以嵌套.

Vim 区分几种类型的折叠方法：

 |  &#39;折叠方法&#39; | 用法 |
|--------------|-------|
 | 差异 | 在差异窗口中用于折叠未更改的文本.  |
 | 表达式 | 使用“foldexpr”基本上创建一个新的折叠方法.  |
 | 缩进 | 基于缩进的折叠.  |
 | 手册 | 通过 `zf`、`zF` 和 `:fold` 自己创建折叠.  |
 | 标记 | 基于文本中的标记折叠（通常在注释中）.  |
 | 语法 | 基于句法的折叠，例如折叠 `if` 块.  |

 **注意**：折叠可能需要大量计算！ 如果你遇到任何
性能缺陷（打字时的小延迟），看看
[FastFold](https://github.com/Konfekt/FastFold), 这会阻止 Vim
在不需要时更新折叠.

Help:

```
:h usr_28
:h 折叠
```

## Sessions

如果你保存一个 **view** (`:h :mkview`)，窗口的当前状态（和
选项和映射）被保存以备后用（`:h :loadview`）.

 **会话** 保存所有窗口的视图以及全局设置. 它基本上
制作当前 Vim 实例的快照并将其保存在会话文件中.
让我强调一下：它保存当前状态； 保存后所做的一切
会话不会成为会话文件的一部分. 要“更新”会话，只需写
再次出来.

这使得它非常适合保存您的_projects_并且易于在两者之间切换
them.

立即尝试！ 打开几个窗口和选项卡并执行 `:mksession Foo.vim`. 如果
你省略了文件名，将假定为 `Session.vim`. 该文件将被保存到
当前工作目录，检查 `:pwd`. 重启 Vim 并执行 `:source
Foo.vim` 和 voilà，缓冲区列表，窗口布局，映射，工作目录
等都应该与保存会话之前相同. 做更多的工作
并通过覆盖已经存在的会话文件来更新会话
 `：mksession！  Foo.vim`.

请注意，会话文件实际上只是 Vim 命令的集合，它们是
应该恢复 Vim 实例的某个状态，所以随意采取
看看它：`:vs Foo.vim`.

你可以通过设置 `&#39;sessionoptions&#39;` 告诉 Vim 在会话中保存什么.

出于脚本目的，Vim 保留最后一个源文件或写入会话的名称
在内部变量 `v:this_session` 中.

Help:

```
:h 会话
:h &#39;会话选项&#39;
:hv:this_session
```

## Locality

上面提到的许多概念也有_local_对应物：

 | 全球 | 本地 | 适用范围 | 帮助 |
|--------|-------|-------|------|
 |  `：设置` |  `：设置本地` | 缓冲区或窗口 |  `:h 本地选项` |
 |  `：地图` |  `：地图<buffer> ` | 缓冲区 |  `:h :map-local` |
 |  `：自动命令` |  `：自动命令*<buffer>  ` | 缓冲区 |  `:h autocmd-buflocal` |
 |  `:CD` |  `：液晶` | 窗口 |  `:h :lcd` |
 |  `<leader>  ` |  `<localleader>  ` | 缓冲区 |  `:h maplocalleader` |

[Variables also have different scopes](https://vimhelp.appspot.com/usr_41.txt.html#41.2).

## Usage

## Getting help offline

Vim 以单个文本文件的形式提供了很好的文档，带有
特殊布局.  Vim 使用一个基于标签的系统来访问某些部分
那些帮助文件.

首先，阅读：`:help :help`. 这将打开文件
`$VIMRUNTIME/doc/helphelp.txt` 在新窗口中跳转到 `:help` 标签
在该文件中.

一些简单的规则：

- 选项用单引号括起来，例如 `:h &#39;textwidth&#39;`
- VimL 函数以 `()` 结尾，例如 `:h reverse()`
- 命令以 `:` 开头，例如 `:h :echo`

你可以使用`<c-d>  `（这是<kbd>ctrl</kbd> + <kbd>d</kbd> ）列出所有标签
匹配当前输入的查询. 例如`:h 选项卡<c-d> ` 会给你一个所有的列表
从 `tab` 到 `&#39;softtabstop&#39;` 的标签到 `setting-guitablabel`.

您想列出所有 VimL 函数吗？ 简单：`:h ()<c-d>  `. 你想列出所有
与窗口有关的 VimL 函数？  `:h 赢*()<c-d>  `.

这很快成为第二天性，但尤其是在开始时，你
有时不知道您要查找的标签的任何部分. 你只能
想象一些可能涉及的关键字.  `:helpgrep` 来拯救！

```
:helpgrep 向后
```

这将在所有文档文件中查找“向后”并跳转到第一个
匹配. 比赛将在 quickfix 列表中组装. 使用 `:cn`/`:cp` 来
跳转到下一场/上一场比赛. 或者使用 `:copen` 打开 quickfix 窗口，
导航到一个条目并点击`<cr>  ` 跳转到那场比赛. 参见 `:h quickfix`
全部真相.

## Getting help offline (alternative)

此列表由最活跃的 Vim 开发人员之一@chrisbra 编制，并且
发布到 [vim_dev](https://groups.google.com/forum/#!forum/vim_dev).

它在此处重新发布并稍作更改.

---

如果您知道要查找的内容，通常会更容易搜索
使用帮助系统，因为主题遵循特定的风格指南.

此外，帮助具有属于您的特定 Vim 版本的优势，因此
过时的主题或后来添加的主题不会出现.

因此，学习帮助系统及其使用的语言是必不可少的.
这里有一些例子（不一定完整，我可能忘记了
something).

 1. 选项用单引号括起来. 所以你会使用 `:h &#39;list&#39;` 去
   列表选项的帮助主题. 如果你只知道，你正在寻找一个
   某些选项，你也可以做 `:h options.txt` 来打开帮助页面
   描述所有选项处理，然后您可以使用常规搜索
   表达式，例如 `/width`. 某些选项有自己的命名空间，例如 `:h
   cpo-a`、`:h cpo-A`、`:h cpo-b` 等等.

 2.普通模式命令就是这样. 使用 `:h gt` 进入帮助页面
   “gt”命令.

3. Regexp 项总是以“/”开头，所以 `:h /\+` 带你到帮助项
   对于 Vim 正则表达式中的 &quot;\+&quot; 量词. 如果你需要了解任何关于
   正则表达式，从 `:h pattern.txt` 开始阅读.

 4.组合键. 它们通常以表示模式的单个字母开头
   可以使用它们. 例如 `:h i_CTRL-X` 带你到
   用于插入模式的 CTRL-X 命令，可用于自动完成不同
   事物. 请注意，某些键将始终写入相同的内容，例如 Control
   将永远是 CTRL. 注意，对于普通模式命令，“n”被省略，
   例如`:h CTRL-A`. 相反，`:h c_CTRL-R` 将描述 CTRL-R 的作用
   在命令行中输入命令时，`:h v_Ctrl-A` 谈到
   在可视模式下递增数字和 `:h g_CTRL-A` 谈论 g<C-A>
   命令（因此你必须按“g”然后<Ctrl-A> ). 这里的“g”代表
   正常命令“g”在执行之前总是期待第二个键
   类似于以“z”开头的命令.

5. 寄存器总是以“quote”开头，所以使用 `:h quote` 来查找
   特殊的“：”寄存器.

 6. Vim 脚本 (VimL) 位于 `:h eval.txt`. 的某些方面
   语言可在 `:h expr-X` 中获得，其中 &#39;X&#39; 是单个字母，例如 `:h
    expr-!` 将带您进入描述 &#39;!&#39; 的主题 （非）运算符
    VimL. 同样重要的是，请参阅 `:h function-list` 以找到对
   所有功能可用.

 7. 帮助页面 `:h map.txt` 中讨论了映射. 使用 `:h mapmode-i`
   了解 `:imap` 命令. 也可以使用 `:map-topic` 来找出
   关于特定于映射的某些子主题（例如 `:h :map-local` 用于
   缓冲区本地映射或 `:h map_bar` 用于 &#39;|&#39; 在映射中处理.

8. 命令定义在 `:h command-*` 中讨论，所以使用 :h command-bar
   了解“！” 自定义命令的参数.

9. 窗口管理命令总是以 CTRL-W 开头，所以你可以找到
   `:h CTRL-W_*` 的相应帮助（例如 `:h CTRL-W_p` 用于切换到
   以前访问过的窗口）. 您还可以访问 `:h windows.txt` 并阅读
   如果您正在寻找窗口处理命令，请按照您的方式进行.

10. Ex 命令总是以“:”开头，所以 `:h :s` 覆盖了“:s”命令.

11. 输入主题后使用 CTRL-D 让 Vim 尝试完成所有可用
    主题.

12. 使用`:helpgrep` 在所有帮助页面中搜索（通常还包括帮助
    已安装插件的页面）. 参见 `:h :helpgrep` 了解如何使用它. 一旦您
    搜索了一个主题，所有匹配都在 quickfix 中可用（或
     location) 可以用 `:copen` 或 `:lopen` 打开的窗口. 给你
    也可以使用 `/` 进一步过滤匹配项.

13. `:h helphelp` 包含一些关于如何使用帮助的信息.

 14. 用户手册. 这描述了初学者的帮助主题，而不是
    友好的方式. 从 `:h usr_toc.txt` 开始查找目录（如您
    可能已经猜到了）. 略读有助于找到某些主题，例如
    你会发现条目“Digraphs”和“Entering special characters”
    第 24 章（所以使用 `:h usr_24.txt` 去那个特定的帮助页面）.

 15. 高亮组总是以 `hl-*` 开头. 例如 `:h hl-WarningMsg` 会说话
    关于“WarningMsg”高亮组.

16. 语法高亮命名为“:syn-topic”，例如`:h :syn-conceal`
    讨论 :syn 命令的隐藏参数.

17. 快速修复命令通常以“:c”开头，而位置列表命令
    usually start with ":l".

 18. `:h BufWinLeave` 谈论 BufWinLeave autocmd. 另外，`:h
    autocommands-events 谈论所有可能的事件.

19. 启动参数总是以“-”开头，所以 `:h -f` 会帮助你
    Vim 的“-f”命令开关.

20. 编译的额外功能总是以“+”开头，所以 `:h +conceal` 谈论
    隐藏支持.

 21、错误代码可以直接在帮助中查找.  `:h E297` 带你
    完全按照错误信息的描述. 然而，有时，那些
    没有描述错误代码，而是在 Vim 命令中列出
    通常会导致这个. 例如 `:h hE128` 直接带你到 `:function`
    命令.

22. 包含的语法文件的文档通常在 `:h
     ft-*-syntax`. 例如 `:h ft-c-syntax` 谈论 C 语法文件和
    它提供的选项. 有时，用于全向补全的附加部分（`:h
    ft-php-omni`) 或文件类型插件 (`:h ft-tex-plugin`) 可用.

此外，还有指向用户文档的链接（它更多地描述了某些命令
从用户的角度来看，不太详细）将在帮助顶部提及
页面（如果可用）. 所以 `:h pattern.txt` 提到了用户指南主题
`:h 03.9` 和 `:h usr_27`.

## Getting help online

如果您遇到无法解决的问题或需要一般指导，请参阅
the [vim_use](https://groups.google.com/forum/#!forum/vim_use) 邮件列表.
另一个很棒的资源正在使用
[IRC](https://de.wikipedia.org/wiki/Internet_Relay_Chat). The channel `#vim` on
[Freenode](https://freenode.net) 很大，通常到处都是乐于助人的人.

如果你想报告一个 Vim 错误，使用
[vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮件列表.

## Autocmds in practice

你现在可以触发任何事件：`:doautocmd BufRead`.

### User events

特别是对于插件来说，创建你自己的“用户”事件是很有用的：

```vim
功能！ 小胖（）
  “这里发生了很多事情.
  “最后..
  doautocmd 用户 ChibbyExit
endfunction
```

现在，您的插件用户可以在 Chibby 完成运行时执行任何操作：

```vim
autocmd 用户 ChibbyExit 调用 ChibbyCleanup()
```

顺便说一句，如果没有“捕获”:autocmd，:doautocmd 将输出一个讨厌
 “没有匹配的自动命令”消息. 这就是为什么许多插件使用`silent
 doautocmd ...` 代替. 但这有缺点，你不能简单地使用
`echo &quot;foo&quot;` 在 :autocmd 中，你必须使用 `unsilent echo &quot;foo&quot;` 来代替..

这就是为什么最好检查是否有接收 autocmd 而不是
否则会打扰发出事件：

```vim
if exists('#User#ChibbyExit')
  doautocmd 用户 ChibbyExit
endif
```

帮助：`:h 用户`

### Nested autocmds

默认情况下，自动命令不嵌套！ 如果 autocmd 执行一个命令，它在
turn 通常会触发另一个事件，它不会发生.

假设每次启动 Vim 时，您都希望自动打开 vimrc：

```vim
autocmd VimEnter * 编辑 $MYVIMRC
```

当你现在启动 Vim 时，它会打开你的 vimrc，但首先你会
请注意，虽然通常会有任何突出显示，但不会有任何突出显示.

问题是你的非嵌套 autocmd 中的 `:edit` 不会触发
“BufRead”事件，因此文件类型永远不会设置为“vim”并且
 `$VIMRUNTIME/syntax/vim.vim` 从未获取过. 参见 `:au BufRead *.vim`. 用这个
instead:

```vim
autocmd VimEnter * 嵌套编辑 $MYVIMRC
```

帮助：`:h autocmd-nested`

## Clipboard

Required [features](#what-kind-of-vim-am-i-running): `+clipboard` 和可选
`+xterm_clipboard` 如果你想在 Unix 系统上使用 `&#39;clipboard&#39;` 选项
使用不支持 GUI 的 Vim.

Help:

```
:h &#39;剪贴板&#39;
:h gui-剪贴板
:h gui-选择
```

另请参阅：[带括号的粘贴（或者为什么我必须设置“粘贴”所有
time?)](#bracketed-paste-or-why-do-i-have-to-set-paste-all-the-time)

### Clipboard usage (Windows, macOS)

Windows 自带一个
[clipboard](https://msdn.microsoft.com/en-us/library/windows/desktop/ms649012(v=vs.85).aspx)
macOS 附带了一个
[pasteboard](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/PasteboardGuide106/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008100-SW1).

两者都像大多数用户期望的那样工作. 您复制选定的文本
`ctrl+c`/`cmd+c` 并使用 `ctrl+v`/`cmd+v` 将它们粘贴到另一个应用程序中.

请注意，复制的文本实际上已传输到剪贴板，因此您可以关闭
您在粘贴到另一个应用程序之前复制的应用程序
problems.

每当发生这种情况时，剪贴板寄存器“*”就会被
选择. 在 Vim 中使用 `&quot;*y` 和 `&quot;*p` 从剪贴板中提取和粘贴
respectively.

如果您甚至不想一直指定 `*` 寄存器，请将其放入
你的 vimrc:

```vim
设置剪贴板=未命名
```

通常所有的 yank/delete/put 操作都会填充 `&quot;` 寄存器，现在是 `*`
寄存器用于相同的操作，因此简单的 y 和 p 将是
enough.

让我重复一遍：使用上面的选项意味着每次抽取/粘贴，即使
只在同一个 Vim 窗口中使用，会改变剪贴板. 自己决定
这是否有用.

如果你连输入 y 都懒得打，你可以将每个视觉选择发送到
通过使用这些设置剪贴板：

```vim
设置剪贴板=未命名，自动选择
设置guioptions+=a
```

Help:

```
:h 剪贴板未命名
:h 自动选择
:h &#39;go_a&#39;
```

### Clipboard usage (Linux, BSD, ...)

如果您的操作系统使用 [X](http://www.x.org/wiki) ，事情有点不同.  X
实现 [X 窗口系统
协议](http://www.x.org/releases/X11R7.7/doc/xproto/x11protocol.html) 其中
自 1987 年以来恰好是主要版本 11，因此 X 也常被称为 X11.

之前，在 X10 中，[剪切
buffers](http://www.x.org/releases/X11R7.7/doc/xorg-docs/icccm/icccm.html#Peer_to_Peer_Communication_by_Means_of_Cut_Buffers)
被引入那种像_剪贴板_一样工作的方式，就像在复制的文本中一样
实际上由 X 持有，所有其他应用程序都可以访问它. 这
机制在 X 中仍然存在，但它的使用现在已被弃用，大多数软件
不再使用它了.

如今，数据通过以下方式在应用程序之间传输
[selections](http://www.x.org/releases/X11R7.7/doc/xorg-docs/icccm/icccm.html#Peer_to_Peer_Communication_by_Means_of_Selections).
从定义的 3 个_选择原子_中，只有 2 个在实践中使用：PRIMARY 和
CLIPBOARD.

选择的工作大致如下：

```
方案一：<ctrl+c>
程序 A：断言 CLIPBOARD 的所有权
方案B：<ctrl+v>
程序 B：注意 CLIPBOARD 的所有权由程序 A 持有
程序B：向程序A请求数据
程序A：响应请求，发送数据给程序B
程序B：从程序A接收数据并插入窗口
```

 | 选择| 什么时候用？  | 怎么贴？  | 如何从 Vim 访问？  |
|-----------|------------|---------------|-------------------------|
 | 初级 | 选择文本 |  `middle-click`, `shift+insert` |  `*` 注册 |
 | 剪贴板 | 选择文本和 `ctrl+c` |  `ctrl+v` |  `+` 注册 |

**注意**：选择（不，甚至不包括剪贴板选择）永远不会保存在
 X服务器！ 因此，当应用程序运行时，您会丢失使用 `ctrl+c` 复制的数据
closes.

使用 `&quot;*p` 粘贴主要选择或 `&quot;+y1G` 将整个文件复制到
剪贴板选择.

如果您碰巧一直访问两个寄存器之一，请考虑使用：

```vim
设置剪贴板^=未命名“*注册
“ 或者
设置剪贴板^=unnamedplus &quot; + 注册
```

（`^=` 用于预置默认值，`:h :set^=`.）

这将使所有 yank/delete/put 操作使用 `*` 或 `+` 而不是
未命名的寄存器 `&quot;`.之后你可以简单地使用 `y` 或 `p` 来访问
您选择的 X 选择.

Help:

```vim
:h 剪贴板未命名
:h 剪贴板-未命名加号
```

## Restore cursor position when opening file

打开文件时，光标将定位在第 1 行第 1 列.
幸运的是 viminfo 文件记得 [marks](#marks) .  `&quot;` 标记包含
您离开的缓冲区中的位置.

```vim
自动命令 BufReadPost *
    \ if line(&quot;&#39;\&quot;&quot;) &gt; 1 &amp;&amp; line(&quot;&#39;\&quot;&quot;) &lt;= line(&quot;$&quot;) |
    \执行“正常！g`\””|
    \ 万一
```

读取：如果标记 `&quot;` 包含的行号大于第 1 行但不大于
比文件中的最后一行跳转到它.

    :h viminfo-&#39;
    :h`引用
    ：汞`

## Temporary files

### Backup files

在保存文件之前，Vim 会创建一个备份文件. 如果写入磁盘是
成功，备份文件将被删除.

使用 :set backup ，备份将持续存在. 这意味着，备份文件将
在最近一次保存之前，始终与原始文件具有相同的内容.
由您决定这是否有用.

你可以用 `:set nobackup nowritebackup` 完全禁用备份，但是你
shouldn't need to nowadays. `'writebackup'` is a security feature that makes
确保您不会丢失原始文件以防万一保存失败，
无论您之后是否保留备份文件.

如果你经常使用 Vim 编辑大文件，[你可能
shouldn't](#editing-huge-files-is-slow), you can exclude those from backups with
`'backupskip'`.

Vim 知道创建备份的不同方法：_copying_ 和 _renaming_.

- **复制**
    1. 创建原始文件的完整副本并用作备份.
    1. 原始文件被清空，然后填充内容
    Vim 缓冲区.
- **重命名**
    1.原文件重命名为备份文件.
    1. Vim 缓冲区的内容被写入一个名为的新文件
    原始文件.

请参阅 `:h &#39;backupcopy&#39;` 了解所有细节.

---

Demo:

```vim
 :set backup backupskip=备份目录=.  backupext=-备份
:e /tmp/富
ifoo<esc>
:w
&quot; 原始文件被创建，不需要备份文件
obar<esc>
:w
&quot; 创建备份文件，更新原始文件
```

```diff
$ diff -u /tmp/foo-备份 /tmp/foo
--- /tmp/foo-备份 2017-04-22 15:05:13.000000000 +0200
+++ /tmp/foo 2017-04-22 15:05:25.000000000 +0200
@@ -1 +1,2 @@
 富
+bar
```

---

    :h 备份
    :h 写入失败

### Swap files

编辑文件时，未保存的更改会写入交换文件.

使用 :swapname 获取当前交换文件的名称. 用 `:set 禁用它们
noswapfile`.

交换文件会更新全部 200 个字符或未键入任何内容
 4 秒. 当您停止编辑文件时，它们会被删除. 你可以改变这些
带有 `:h &#39;updatecount&#39;` 和 `:h &#39;updatetime&#39;` 的数字.

如果 Vim 被杀死（例如断电），您将丢失自上次以来的所有更改
该文件已写入磁盘，但不会删除交换文件. 现在，如果你
再次编辑文件，Vim 将提供从交换文件中恢复文件的机会
file.

当两个人试图编辑同一个文件时，第二个人会收到通知
交换文件已经存在. 它可以防止人们试图保存
一个文件的不同版本. 如果你不想要这种行为，请参阅`:h
'directory'`.

    :h 交换文件
    :h usr_11

### Undo files

The [undo tree](#undo-tree) 保存在内存中，当 Vim 退出时会丢失.
如果你想让它持续存在，`:set undofile`. 这将保存撤消文件
`~/foo.c` 在 `~/foo.c.un~` 中.

    :h &#39;撤消文件&#39;
    :h 撤消持久性

### Viminfo files

当备份、交换和撤消文件都是关于文本状态时，viminfo 文件是
用于保存退出 Vim 时会丢失的所有其他内容.
viminfo 文件保存历史（命令行、搜索、输入）、寄存器、
标记、缓冲区列表、全局变量等.

默认情况下，viminfo 被写入 `~/.viminfo`.

    :h 信息
    :h &#39;viminfo&#39;

### Example configuration for temporary files

将所有临时文件放在 ~/.vim/files 下它们自己的目录中：

```vim
&quot; 如果需要创建目录
如果 !isdirectory($HOME.&#39;/.vim/files&#39;) &amp;&amp; 存在(&#39;*mkdir&#39;)
  调用 mkdir($HOME.&#39;/.vim/files&#39;)
endif

“ 备份文件
设置备份
设置 backupdir =$HOME/.vim/files/backup/
设置 backupext =-vimbackup
设置备份跳过=
&quot; 交换文件
设置目录 =$HOME/.vim/files/swap//
设置更新计数 =100
&quot; 撤消文件
设置撤销文件
设置 undodir =$HOME/.vim/files/undo/
&quot; vim 信息文件
设置 viminfo =&#39;100,n$HOME/.vim/files/info/viminfo
```

## Editing remote files

 Vim 带有 netrw 插件，可以编辑远程文件. 其实它
通过scp将远程文件传输到本地临时文件，打开一个缓冲区
使用该文件，并在保存时将更改写回远程文件.

如果您想使用本地配置而不是
SSH 进入服务器并使用管理员希望您使用的任何内容.

```
:e scp://bram@awesome.site.com/.vimrc
```

如果你已经设置了 ~/.ssh/config ，它会自动使用：

```
主持人棒棒哒
    主机名 awesome.site.com
    端口 1234
    用户名
```

假设 ~/.ssh/config 中有上述内容，这也同样有效：

```
:e scp://awesome/.vimrc
```

类似的可以用 `~/.netrc` 来完成，见 `:h netrw-netrc`.

请务必阅读 `:h netrw-ssh-hack` 和 `:hg:netrw_ssh_cmd`.

---

另一种可能性是使用 [sshfs](https://wiki.archlinux.org/index.php/Sshfs)
它使用 [FUSE](https://en.wikipedia.org/wiki/Filesystem_in_Userspace) 到
将远程文件系统挂载到本地文件系统.

## Managing plugins

[Pathogen](https://github.com/tpope/vim-pathogen) 是第一个流行的工具
管理插件. 实际上它只是将 _runtimepath_ (`:h &#39;rtp&#39;`) 调整为
包括放在某个目录下的所有东西. 你必须克隆
您自己的插件存储库.

真正的插件管理器会公开帮助您安装和更新插件的命令
从 Vim 内部.

[List of plugin managers](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#plugin-managers)

## Block insert

这是一种在多个连续行中插入相同文本的技术
同时. 看到这个
[demo](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-block_insert.gif).

使用 ` 切换到可视块模式<c-v> `. 然后往下走几行.
点击“I”或“A”并开始输入您的文本.

一开始可能有点混乱，但始终会为当前输入文本
行，只有在完成当前插入后，才会显示相同的文本
应用于先前视觉选择的所有其他行.

所以一个简单的例子是`<c-v>  3jI文本<esc> `.

如果您有不同长度的行并且想在右侧附加相同的文本
在每一行结束后，这样做：`<c-v>  3j$A文本<esc> `.

有时您需要将光标放在当前结束后的某处
线. 默认情况下你不能这样做，但你可以设置 `virtualedit` 选项：

```vim
设置 virtualedit=all
```

之后 `$10l` 或 `90|` 即使在行尾之后也能工作.

有关更多信息，请参见`:h blockwise-examples`. 乍一看似乎很复杂，
但很快成为第二天性.

如果您想获得真正的幻想，请看一下
[multiple-cursors](https://github.com/terryma/vim-multiple-cursors).

## Running external programs and using filters

免责声明：Vim 是单线程的，因此在
前景将阻止其他一切. 当然，你可以使用 Vim 的一个
编程接口，例如 Lua，并使用其线程支持，但在此期间
尽管如此，Vim 进程还是被阻塞了.  Neovim 通过添加一个
适当的作业 API.

（显然 Bram 也在考虑为 Vim 添加作业控制.如果你
有一个非常新的版本，见 `:helpgrep startjob`.）

使用 :! 开始工作. 如果你想列出当前工作中的文件
目录，使用 `:!ls`. 像往常一样在 shell 中使用 `|` 作为管道，例如 `:!ls -1 |
排序 | 尾-n5`.

如果没有范围，`:!` 的输出将显示在可滚动的窗口中. 在
另一方面，如果给出一个范围，这些行将是
[filtered](https://en.wikipedia.org/wiki/Filter_(software) ). 这意味着他们
将被输送到
[stdin](https://en.wikipedia.org/wiki/Standard_streams#Standard_input_.28stdin.29)
过滤程序和处理后被替换为
[stdout](https://en.wikipedia.org/wiki/Standard_streams#Standard_output_.28stdout.29)
的过滤器. 例如，要将数字添加到接下来的 5 行，请使用：

    :.,+4!nl -ba -w1 -s&#39;

由于手动添加范围比较麻烦，Vim 也提供了一些
帮手方便. 与范围一样，您也可以选择行
视觉模式，然后点击`:`. 还有一个运算符 `!` 可以执行动作.
例如 `!ip!sort` 将对当前段落的行进行排序.

过滤的一个很好的用例是 [Go programming
语言](https://golang.org). 缩进非常自以为是，甚至
带有一个名为 `gofmt` 的过滤器，用于正确缩进 Go 源代码. 所以
Go 的插件通常提供称为 `:Fmt` 的辅助命令，基本上
`:%!gofmt`，所以他们缩进了文件中的所有行.

人们经常使用 `:r !prog` 将 prog 的输出放在当前行之下，
这对脚本来说很好，但是当它在运行时，我发现它更容易使用
`!!ls` 代替了当前行.

    :h 过滤器
    ：h：阅读！

## Cscope

[Cscope](http://cscope.sourceforge.net/) 做的事情比
[ctags](http://ctags.sourceforge.net/)，但仅支持 C（以及 C++ 和 Java
在一定程度上）.

标签文件只知道定义符号的位置，而 cscope 数据库
更了解您的数据：

- 这个符号在哪里定义的？
- 这个符号用在什么地方？
- 这个全局符号的定义是什么？
- 这个变量从哪里得到它的值？
- 这个函数在源文件中的什么地方？
- 什么函数调用这个函数？
- 这个函数调用了哪些函数？
- “空间不足”的消息从何而来？
- 这个源文件在目录结构中的什么位置？
- 哪些文件包含这个头文件？

### 1. Build the database

在项目的根目录中执行此操作：

```sh
$ cscope -bqR
```

这将在当前工作中创建 3 个文件：`cscope{,.in,.po}.out`
目录. 将它们视为您的数据库.

不幸的是，`cscope` 默认只分析 `*.[c|h|y|l]` 文件. 如果你想
要将 cscope 用于 Java 项目，请执行以下操作：

```sh
 $ 找到.  -name &quot;*.java&quot; &gt; cscope.files
$ cscope -bq
```

### 2. Add the database

打开与新构建的数据库的连接：

```vim
:cs 添加 cscope.out
```

验证是否已建立连接：

```vim
：CS秀
```

（是的，您可以添加多个连接.）

### 3. Query the database

```vim
:cs 查找<kind><query>
```

例如 `:cs find d foo` 将列出所有被 `foo(...)` 调用的函数.

 | 亲切 | 说明 |
|------|-------------|
 | 秒 |  **s**ymbol：查找所有对令牌的引用 |
 | 克 |  **g**lobal：查找令牌的全局定义 |
 |  c |  **c**alls：查找对该函数的所有调用 |
 | 吨 |  **t**ext：查找文本的所有实例 |
 | 电子 |  **e**grep: egrep 搜索词 |
 |  f |  **f**ile: 打开文件名 |
 | 我 |  **i**ncludes：查找包含文件名 | 的文件
 |  d |  **d**epends: 查找这个函数调用的函数 |

我建议一些方便的映射，例如：

```vim
地图<buffer><leader> cs:cscope 查找 s<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
地图<buffer><leader> cg :cscope 找到 g<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
地图<buffer><leader> cc :cscope 查找 c<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
地图<buffer><leader> ct :cscope 查找 t<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
地图<buffer><leader> ce :cscope 找到e<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
地图<buffer><leader> cf :cscope 查找 f<c-r>  =展开（&#39;<cfile>  &#39;)<cr><cr>
地图<buffer><leader> ci :cscope 找到我 ^<c-r>  =展开（&#39;<cfile>  &#39;)<cr>  $<cr>
地图<buffer><leader> cd :cscope 查找 d<c-r>  =展开（&#39;<cword>  &#39;)<cr><cr>
```

所以，当 `:tag`（或 `<c-]>  `) 从标签文件跳转到定义，`:cstag`
做同样的事情，但也会考虑连接的 cscope 数据库. 这
选项 `&#39;cscopetag&#39;` 使 `:tag` 自动像 `:cstag` 一样工作. 这是很
如果您已经有与标签相关的映射，则很方便.

帮助：`:h cscope`

## MatchIt

因为 Vim 是用 C 语言编写的，所以很多特性都采用了类 C 的语法. 默认情况下，
if your cursor is on `{` or `#endif`, you can use `%` to jump to the
corresponding `}` or `#ifdef` respectively.

Vim 捆绑了一个名为 matchit.vim 的插件，该插件未被启用
默认. 它使 `%` 也循环遍历 HTML 标签，if/else/endif 构造在
VimL 等，并引入了一些新命令.

#### Installation for Vim 8

```vim
vimrc
打包！ 匹配
```

#### Installation for Vim 7 and older

```vim
vimrc
运行时宏/matchit.vim
```

由于 matchit 的文档非常广泛，我建议也做
以下一次：

```vim
:!mkdir -p ~/.vim/文档
:!cp $VIMRUNTIME/macros/matchit.txt ~/.vim/doc
:helptags ~/.vim/文档
```

#### Small intro

该插件现在可以使用了. 有关支持的信息，请参阅`:h matchit-intro`
命令和 `:h matchit-languages` 支持的语言.

也就是说，定义您自己的匹配对很容易：

```vim
 autocmd 文件类型 python let b:match_words = &#39;\<if\>  :\<elif\>  :\<else\>  &#39;
```

之后，您可以通过使用在任何 Python 文件中循环执行这 3 个语句
`%`（向前）或 `g%`（向后）.

Help:

```
:h matchit 安装
:h 匹配
:hb:匹配词
```

## True colors

在终端仿真器中使用真彩色意味着能够使用 24 位 RGB
颜色. 这使得 16777216 (2^24) 种颜色而不是通常的 256 种.

正如所解释 [here](#colorschemes), colorschemes 实际上可以是_two_
通过为终端 (xterm) 和 GUI (gvim) 定义颜色方案.
在终端仿真器了解真彩色之前，这是有道理的.

在 `:set termguicolors` 之后，Vim 开始发出只有理解的转义序列
通过支持真彩色的终端仿真器. 当你的颜色看起来很奇怪时，
很可能你的终端模拟器不支持真彩色或者你
colorcheme 没有定义 GUI 颜色.

许多人使用终端复用器
[tmux](https://github.com/tmux/tmux/wiki) 基本上介于
终端仿真器和 Vim. 使 tmux _forward_ 真正的彩色转义
Vim 发出的序列，你必须在用户
`.tmux.conf`:

```
设置选项-g 默认终端&#39;tmux-256color&#39;
设置选项-ga terminal-overrides &#39;,xterm-256color:Tc&#39;
```

- 第一行对大多数人来说应该是相同的，表示 `$TERM`
  在 _within_ tmux 中使用.
- 第二行向
  other terminfo entries of `xterm-256color`. Obviously this assumes that the
  用户在 tmux 的_外部_使用 `TERM=xterm-256color`.

因此，这是启用真彩色的清单：

- 阅读`:h &#39;termguicolors&#39;`.
- 在你的 vimrc 中加入 `set termguicolors`.
 - 确保您的配色方案具有 GUI 的颜色定义.  （它应该包含
  带有 `guifg` 和 `guibg` 的行.）
- 确保您选择的终端仿真器支持真彩色.
 - 使用 tmux？ 配置它以添加“Tc”功能.

终端中颜色的流行参考：
https://gist.github.com/XVilka/8346728

## Tips

## Go to other end of selected text

视觉选择中的 `o` 和 `O` 使光标移动到另一端. 试试
按块选择以查看差异. 这对于快速更改很有用
所选文本的大小.

```
:h v_o
:h v_O
```

## Saner behavior of n and N

`n` 和 `N` 的方向取决于使用的是 `/` 还是 `?`
分别向前或向后搜索. 这让我很困惑.

如果您希望 `n` 始终向前搜索而 `N` 向后搜索，请使用以下命令：

```vim
地图<expr> n &#39;Nn&#39;[v:searchforward]
 xnoremap<expr>  n &#39;Nn&#39;[v:searchforward]
地图<expr> n &#39;Nn&#39;[v:searchforward]

地图<expr> N &#39;nN&#39;[v:searchforward]
 xnoremap<expr>  N &#39;nN&#39;[v:searchforward]
地图<expr> N &#39;nN&#39;[v:searchforward]
```

## Saner command-line history

如果你和我一样，你习惯于通过以下方式转到下一个和上一个项目
 `<c-n>  ` 和 `<c-p>  `分别. 默认情况下，这也适用于
命令行并从历史记录中调用较旧或较新的命令行.

到目前为止，一切都很好. 但是`<up>  ` 和 `<down>  `更聪明！ 他们回忆起
开头与当前命令行匹配的命令行. 例如`：回声<up> `
可能会变成 `:echo &quot;Vim rocks!&quot; .

当然，我不希望您伸手去拿箭头键：

```vim
核地图<expr><c-n>野生菜单模式（）？  “\<c-n>  “：”\<down>  “
核地图<expr><c-p>野生菜单模式（）？  “\<c-p>  “：”\<up>  “
```

这里我们也区分了命令行历史和wildmenu. 参见`:h
'wildmenu'`.

我每天多次依赖这种行为.

## Saner CTRL-L

默认情况下，`<c-l>  ` 清除并重绘屏幕（如 `:redraw!`）. 这
下面的映射做同样的事情，加上取消突出显示通过`/`找到的匹配项，
`?` 等，加上修复语法高亮（有时 Vim 失去高亮由于
复杂的突出显示规则），加上强制更新语法突出显示
差异模式：

```vim
地图<leader> l :nohlsearch<cr>  ：差异更新<cr> :syntax 从开始同步<cr><c-l>
```

## Disable audible and visual bells

```vim
不设置错误提示
设置novisualbell
设置 t_vb=
```

See [Vim Wiki: Disable beeping](http://vim.wikia.com/wiki/Disable_beeping).

## Quickly move current line

有时我需要一种快速的方法来将当前行移动到上方或下方：

```vim
 noremap [e :<c-u> 执行“移动-1-”.  v:count1<cr>
诺尔地图]e：<c-u> 执行“移动+”.  v:count1<cr>
```

这些映射也需要一个计数，所以 2]e 将当前行移动到下面 2 行.

## Quickly add empty lines

```vim
 noremap [<space>  :<c-u> 放！  =重复（nr2char（10），v：count1）<cr>  &#39;[
 nnoremap ]<space>  :<c-u> 放=重复（nr2char（10），v：count1）<cr>
```

现在`5[<space>  ` 在当前行上方插入 5 个空行.

## Quickly edit your macros

这是一颗真正的宝石！ 映射采用寄存器（或默认情况下的“*”）并打开
它在 cmdline 窗口中. 打`<cr>  ` 当你完成编辑设置
register.

我经常用它来纠正我在录制宏时所做的拼写错误.

```vim
地图<leader>米：<c-u><c-r><c-r>  =&#39;让@&#39;.  v:注册.  = &#39;. 字符串（getreg（v：注册））<cr><c-f><left>
```

像这样使用它`<leader>  m` 或 `&quot;q<leader> 米`.

注意使用`<c-r><c-r>  ` 以确保 `<c-r>  ` 被插入
字面上地. 参见`:h c_^R^R`.

## Quickly jump to header or source file

这种技术可能适用于许多文件类型. 它设置_文件标记_
(见 `:h marks`) 离开源文件或头文件时，可以快速跳转
使用 `&#39;C` 或 `&#39;H`（参见 `:h &#39;A`）回到上次访问的那个.

```vim
autocmd BufLeave *.{c,cpp} 标记 C
autocmd BufLeave *.h 标记 H
```

**注意**: 信息保存在 viminfo 文件中，所以确保 `:set
viminfo?` 包括 `:h viminfo-&#39;`.

## Quickly change font size in GUI

我认为这是从 tpope 的配置中获取的：

```vim
命令！ 更大 :let &amp;guifont = substitute(&amp;guifont, &#39;\d\+$&#39;, &#39;\=submatch(0)+1&#39;, &#39;&#39;)
命令！ 更小 :let &amp;guifont = substitute(&amp;guifont, &#39;\d\+$&#39;, &#39;\=submatch(0)-1&#39;, &#39;&#39;)
```

## Change cursor style dependent on mode

我喜欢在正常模式下使用块光标，在插入模式下使用 i-beam 光标，以及
替换模式下的下划线光标.

```vim
如果为空（$TMUX）
  让 &amp;t_SI = &quot;\<Esc>  ]50;CursorShape=1\x7&quot;
  让 &amp;t_EI = &quot;\<Esc>  ]50;光标形状=0\x7&quot;
  让 &amp;t_SR = &quot;\<Esc>  ]50;CursorShape=2\x7&quot;
else
  让 &amp;t_SI = &quot;\<Esc> 复用器；\<Esc>  \<Esc>  ]50;光标形状=1\x7\<Esc>  \\&quot;
  让 &amp;t_EI = &quot;\<Esc> 复用器；\<Esc>  \<Esc>  ]50;光标形状=0\x7\<Esc>  \\&quot;
  让 &amp;t_SR = &quot;\<Esc> 复用器；\<Esc>  \<Esc>  ]50;光标形状=2\x7\<Esc>  \\&quot;
endif
```

这只是告诉 Vim 打印特定的字符序列 ([escape
序列]（https://en.wikipedia.org/wiki/Escape_sequence））进入/离开时
插入模式. 底层终端，或类似的程序
[tmux](https://tmux.github.io) 位于 Vim 和终端之间的，将
处理并评价它.

但是有一个缺点：有许多终端仿真器实现
并非所有人都使用相同的序列来做相同的事情. 使用的序列
以上可能不适用于您的实施. 您的实施可能不会
甚至支持不同的光标样式. 检查文档.

上面的例子适用于 iTerm2.

## Don't lose selection when shifting sidewards

如果你选择一行或多行，你可以使用`&lt;`和`&gt;`来移动它们
侧向. 不幸的是，您之后会立即失去选择.

您可以使用 `gv` 重新选择最后一次选择（参见 `:h gv`），这样您就可以工作了
像这样围绕它：

```vim
xnoremap &lt;
xnoremap &gt; &gt;gv
```

现在您可以毫无问题地在您的视觉选择上使用`&gt;&gt;&gt;&gt;&gt;`.

**注意**：同样可以使用 `.` 来实现，它会重复最后一次更改.

## Reload a file on saving

Using [autocmds](#autocmds) 您可以在保存文件时做任何事情，例如采购
它在点文件或运行 linter 的情况下检查语法错误
你的源代码.

```vim
autocmd BufWritePost $MYVIMRC 源 $MYVIMRC
autocmd BufWritePost ~/.Xdefaults 调用系统(&#39;xrdb ~/.Xdefaults&#39;)
```

## Smarter cursorline

我喜欢光标线，但我只想在当前窗口中使用它而不是
处于插入模式时：

```vim
autocmd InsertLeave,WinEnter * set cursorline
autocmd InsertEnter,WinLeave * 设置 nocursorline
```

## Faster keyword completion

关键字补全 (`<c-n>  `/`<c-p>  `) 尝试完成中列出的任何内容
 `&#39;complete&#39;` 选项. 默认情况下，这还包括标签（可以是
烦人）并扫描所有包含的文件（这可能非常慢）. 如果可以的话
没有这些东西生活，禁用它们：

```vim
set complete-=i &quot; 禁用扫描包含的文件
set complete-=t &quot; 禁用搜索标签
```

## Cosmetic changes to colorschemes

始终使用深灰色状态行，无论选择什么颜色方案：

```vim
autocmd ColorScheme * 突出显示 StatusLine ctermbg=darkgray cterm=NONE guibg=darkgray gui=NONE
```

每次你使用 `:colorscheme ...` 时都会触发. 如果你想让它触发
仅适用于某种配色方案：

```vim
autocmd ColorScheme 沙漠高亮 StatusLine ctermbg=darkgray cterm=NONE guibg=darkgray gui=NONE
```

这仅针对 `:colorscheme desert` 触发.

## Commands

有用的命令，值得了解. 使用`：h：<command name>  ` 了解更多
关于它们，例如 `:h :global`.

## :global and :vglobal

在所有匹配的行上执行命令. 例如 `:global /regexp/ print` 将使用
`:print` 在所有包含“正则表达式”的行上.

有趣的事实：你可能都知道 grep，这是 Ken 编写的过滤程序
汤普森. 它有什么作用？ 它打印与某个规则匹配的所有行
表达！ 现在猜猜 `:global /regexp/ print` 的缩写形式？ 这是正确的！
它是 `:g/re/p`.  Ken Thompson 在编写 grep 时受到 vi 的 `:global` 的启发.

`:global` 与它的名字不同，默认情况下只作用于所有行，但它也需要
一个范围. 假设你想在从当前行到当前行的所有行上使用 `:delete`
下一个包含“foo”的空白行（由正则表达式 `^$` 匹配）：

```vim
:,/^$/g/foo/d
```

要在_不_匹配给定模式的所有行上执行命令，请使用
`:global!` 或者它的别名 `:vglobal`（想想 _inVerse_）.

## :normal and :execute

这些命令常用于 Vim 脚本中.

使用 :normal 可以从命令行进行正常模式映射. 例如
 `：正常！  4j` 将使光标向下移动 4 行（不使用任何自定义
由于“！”）映射“j”.

请注意 `:normal` 也需要一个 [range](#ranges) ，所以 `:%norm!  Iabc` 会
在每一行前添加“abc”.

使用 :execute 可以将命令与表达式混合使用. 假设你编辑一个 C
源文件并想切换到它的头文件：

```vim
 :执行 &#39;edit&#39; fnamemodify(expand(&#39;%&#39;), &#39;:r&#39;) .  &#39;.H&#39;
```

这两个命令经常一起使用. 假设你想让光标移动
向下“n”行：

```vim
: 让 n = 4
 ：执行“正常！” 名词 &#39;j&#39;
```

## :redir and execute()

许多命令打印消息，而 :redir 允许重定向该输出. 你
可以重定向到文件， [registers](#registers) 或变量.

```vim
:redir =&gt; 有
:reg
:END 运行
：回声变量
:&quot; 为了好玩，我们也把它放到当前缓冲区中.
：放=在哪里
```

在 Vim 8 中有一个更短的方法：

```vim
:put =execute(&#39;reg&#39;)
```

Help:

```
：h：运行
:h 执行()
```

## Debugging

## General tips

如果您遇到奇怪的行为，请尝试像这样重现它：

```
vim -u 无 -N
```

这将在没有 vimrc 的情况下启动 Vim（因此是默认设置）并且不兼容
模式（这使得它使用 Vim 默认值而不是 vi 默认值）.  （参见`:h
--noplugin` 用于在开始时加载的其他组合.）

如果你现在还能重现，那很可能是 Vim 本身的一个 bug！ 报告
它给 [vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮寄
列表. 大多数情况下，此时问题不会得到解决，您将拥有
进一步调查.

插件通常会引入新的/更改的/错误的行为. 例如，如果它发生在
保存，检查 `:verb au BufWritePost` 以获得潜在罪魁祸首的列表.

如果您使用的是插件管理器，请将它们注释掉，直到找到罪魁祸首.

问题还没有解决？ 如果它不是一个插件，它必须是你的其他
设置，所以也许你的选项或自动命令等.

是时候使用二分查找了. 反复将搜索空间一分为二，直到你
找到罪魁祸首. 由于二进制除法的性质，不需要很多
steps.

实际上，它是这样工作的：将 `:finish` 命令放在你的中间
 vimrc.  Vim 将跳过它之后的所有内容. 如果仍然发生，则问题出在
活跃的上半部分. 将 `:finish` 移到_that_一半的中间.
否则，问题出在不活跃的下半部分. 将 `:finish` 移动到
 _that_一半的中间. 等等.

## Verbosity

另一个观察 Vim 当前正在做什么的有用方法是增加
冗长程度. 目前 Vim 支持 9 个不同的级别. 参见`:h &#39;详细&#39;`
完整列表.

```vim
:e /tmp/富
：设置详细= 2
:w
：设置详细= 0
```

这将显示所有获取来源的文件，例如撤消文件或各种
用于保存的插件.

如果您只想增加单个命令的详细程度，还有
 `:verbose`，简单地放在任何其他命令的前面. 它需要
详细级别作为计数，默认为 1：

```vim
:动词集详细
&quot;详细=1
:10verb 设置冗长
&quot;详细=10
```

它经常与默认的详细级别 1 一起使用，以显示选项的位置
最后设置：

```vim
: 你有动词组吗？
&quot; 最后一组来自 ~/.vim/vimrc
```

自然地，冗长级别越高，输出越多. 但
不用担心，您可以简单地将输出重定向到一个文件：

```vim
 ：设置详细文件=/tmp/foo |  15verbose echo &quot;foo&quot; |  vsplit/tmp/foo
```

您还可以在开始时使用“-V”选项启用详细信息. 它
默认为详细级别 10.例如 `vim -V5`.

## Profiling startup time

 Vim 启动感觉很慢？ 是时候处理一些数字了：

```
vim --startuptime /tmp/startup.log +q &amp;&amp; vim /tmp/startup.log
```

第一列是最重要的，因为它显示了经过的绝对时间. 如果
两条线之间的时间有很大的跳跃，第二条线要么是非常
大文件或带有错误 VimL 代码的文件值得调查.

## Profiling at runtime

Required [feature](#what-kind-of-vim-am-i-running)：`+个人资料`

Vim 提供了在运行时进行分析的内置功能，这是一种很好的方式
在您的环境中查找慢速代码.

`:profile` 命令接受一堆子命令来指定要做什么
profile.

如果你想剖析_everything_，请执行以下操作：

    :profile start /tmp/profile.log
    ：配置文件*
    ：个人资料功能*
    <do something in Vim>
    ：问答

Vim 将分析信息保存在内存中，只将其写出到
退出时的日志文件.  （Neovim 已经使用 `:profile dump` 解决了这个问题）.

看看`/tmp/profile.log`. 分析期间执行的所有代码
将被显示. 每行，执行的频率以及花费的时间.

跳转到日志底部. 这里有两个不同的部分`FUNCTIONS SORTED
 ON TOTAL TIME` 和 `FUNCTIONS SORTED ON SELF TIME` 是值得的. 在一个
快速浏览一下，您可以看到哪些功能花费的时间最长.

您也可以在启动期间使用 :profile ：

     $ vim --cmd &#39;prof 启动 prof.log | 教授文件 * |  prof func *&#39; test.c
    :q
    $ tail -50 prof.log

## Debugging Vim scripts

如果你以前使用过命令行调试器，`:debug` 会很快感觉
familiar.

只需在任何其他命令前加上 `:debug` 即可进入调试模式.
也就是说，执行会在即将执行的第一行停止，那
行将被显示.

请参阅 `:h &gt;cont` 和下面的 6 个可用的调试器命令，并注意，
就像在 gdb 和类似的调试器中一样，您也可以使用它们的缩写形式：`c`、`q`、
`n`、`s`、`i` 和 `f`.

除此之外，你可以自由使用任何 Vim 命令，例如 `:echo myvar`，
它在代码中当前位置的上下文中执行.

你基本上得到一个
[REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) 经过
只需使用 `:debug 1`.

如果您必须单步执行每一行，那将是一件痛苦的事情，所以
course we can define breakpoints, too. (Breakpoints are called breakpoints,
因为当它们被击中时执行停止，因此您可以简单地跳过代码
你不感兴趣.）参见 `:h :breakadd`、`:h :breakdel` 和 `:h
:breaklist` 了解更多详情.

Let's assume you want to know what code is run every time you save a file:

```vim
:au BufWritePost
&quot; 表示 BufWritePost
"     *         call sy#start()
:breakadd func *开始
:w
" Breakpoint in "sy#start" line 1
&quot; 进入调试模式.键入“cont”继续.
" function sy#start
&quot; 第 1 行：如果 g:signify_locked
>s
" function sy#start
&quot; 第 3 行：endif
>
" function sy#start
&quot; 第 5 行：让 sy_path = resolve(expand(&#39;%:p&#39;))
>q
:breakdel *
```

如您所见，使用 `<cr>  ` 将重复之前的调试器命令 `s`
这个案例.

`:debug` 可以与 [verbose](#verbosity) 选项.

## Debugging syntax files

语法文件通常是由于错误和/或复杂而导致速度下降的原因
is compiled in, Vim provides the super useful `:syntime` command.

```vim
: 罪是
 “ 打<c-l>几次重绘导致语法规则再次应用的窗口
：同步关闭
：同步报告
```

输出包含重要指标. 例如，您可以看到哪个正则表达式也需要
很长并且应该被优化或者哪些正则表达式一直被使用但从不
甚至匹配.

参见 `:h :syntime`.

## Miscellaneous

## Additional resources

 | 资源 | 说明 |
|----------|-------------|
| [Seven habits of effective text editing](http://www.moolenaar.net/habits.html)  | 作者 Bram Moolenaar，Vim 的作者.  |
| [Seven habits of effective text editing 2.0 (PDF)](http://www.moolenaar.net/habits_2007.pdf)  | 往上看.  |
| [IBM DeveloperWorks: Scripting the Vim editor](http://www.ibm.com/developerworks/views/linux/libraryview.jsp?sort_order=asc&sort_by=Title&search_by=scripting+the+vim+editor)  | 关于 Vim 脚本的五部分系列.  |
| [Learn Vimscript the Hard Way](http://learnvimscriptthehardway.stevelosh.com)  | 从头开始开发 Vim 插件.  |
| [Practical Vim (2nd Edition)](https://pragprog.com/titles/dnvim2/practical-vim-second-edition)  | 关于 Vim 的最好的书.  |
| [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)  | 解释了常见的误解.  |
| [Your problem with Vim is that you don't grok vi](http://stackoverflow.com/a/1220118)  | 简洁、信息丰富且正确. 一颗真正的宝石.  |

#### Screencasts

- [vimcasts.org](http://vimcasts.org/episodes/archive)
- [By wincent](https://www.youtube.com/channel/UCXPHFM88IlFn68OmLwtPmZA)
- [By Derek Wyatt](http://derekwyatt.org/vim/tutorials/index.html)

## Vim distributions

Vim 发行版是 Vim 的自定义设置和插件包.

无论如何，更高级的用户知道如何配置他们的编辑器，所以发行版
主要针对初学者. 如果你考虑一下，这很
矛盾的是：通过添加更多要学习的东西来使它变得更容易？

我知道很多人不想花很多时间来定制一个
编辑器（实际上，当你最终得到时你永远不会停止定制你的 vimrc
上瘾了），但最终你只有在花时间
正确地学习它.

跟着我重复：“程序员应该了解他们的工具.”

无论如何，如果你知道自己在做什么，你可能会从中汲取一些灵感
查看一些分布：

- [cream](http://cream.sourceforge.net)
- [janus](https://github.com/carlhuda/janus.git)
- [spacevim](https://github.com/SpaceVim/SpaceVim)
- [spf13](https://github.com/spf13/spf13-vim)

## Standard plugins

许多人对 Vim 附带了一些标准的事实感到惊讶
插件. 有些默认加载（`:e $VIMRUNTIME/plugin`）有些不加载
 (`:e $VIMRUNTIME/pack/dist/opt`). 阅读 `:h pack-add` 了解如何获取
latter.

不过，大多数默认加载的插件永远不会被使用.
根据需要禁用它们. 它们仍将显示为来源
(`:scriptnames`)，但实际上只有第一行在 Vim 退出之前被读取
出去. 不会处理进一步的代码（映射、命令、逻辑）.

 | 插件 | 禁用它使用.. | 帮助 |
|------------|-------------------------------------|------|
 |  2html |  `让 g:loaded_2html_plugin = 1` |  `:h 2html` |
 | 获取脚本 |  `让 g:loaded_getscriptPlugin = 1` |  `:h pi_getscript` |
 | 压缩 |  `让 g:loaded_gzip = 1` |  `:h pi_gzip` |
 | 登录 |  `让 g:loaded_logipat = 1` |  `:h pi_logipat` |
 | 火柴 |  `让 g:loaded_matchparen = 1` |  `:h pi_paren` |
 | 网路 |  `让 g:loaded_netrwPlugin = 1` |  `:h pi_netrw` |
 | 帮助者 |  `让 g:loaded_rhelper = 1` |  `:e $VIMRUNTIME/plugin/rhelper.vim` |
 | 拼写文件 |  `让 g:loaded_spellfile_plugin = 1` |  `:h 拼写文件.vim` |
 | 焦油 |  `让 g:loaded_tarPlugin = 1` |  `:h pi_tar` |
 | 球 |  `让 g:loaded_vimballPlugin = 1` |  `:h pi_vimball` |
 | 邮编 |  `让 g:loaded_zipPlugin = 1` |  `:h pi_zip` |

## Map CapsLock to Control

CapsLock belongs to the most useless keys on your keyboard, but it's much easier
比 Control 键更触及，因为它位于您的 [home
row](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-homerow.png).
将 CapsLock 映射到 Control 是防止或至少减少的好方法
[RSI](https://de.wikipedia.org/wiki/Repetitive-Strain-Injury-Syndrom) 如果你
程序很多.

注意：当你习惯了它，你就离不开它了.

**macOS**:

 `系统偏好设置 -&gt; 键盘 -&gt; 键盘选项卡 -&gt; 修饰键`. 改变
“CapsLock”到“控制”.

**Linux**:

要更改 X 中的键，请将其放入您的 ~/.xmodmap 中：

    删除 Lock = Caps_Lock
    键盘符号 Caps_Lock = Control_L
    添加控件 = Control_L

然后通过`$ xmodmap ~/.xmodmap`获取它.

另一种方法是使用 [caps2esc](https://github.com/oblitum/caps2esc) 或者
[xcape](https://github.com/alols/xcape).

**Windows**:

请参阅 [superuser.com：将大写锁定映射到 Windows 中的控制
8.1](http://superuser.com/questions/764782/map-caps-lock-to-control-in-windows-8-1).

## Generating HTML from buffer

使用 2html [标准] 中的 :TOhtml 从任何缓冲区生成 HTML
plugin](#standard-plugins). The output can be used for printing or easy web
publishing.

该命令创建一个同名的新缓冲区，并附加了“.html”. 这
颜色与在 Vim 中看到的一样. 他们取决于
[colorscheme](#colorschemes).

该插件知道几个选项来微调输出，例如设置
编码和字体.

参见`:h :TOhtml`.

## Easter eggs

 | 命令 | 留言 |
|-----------|---------|
 |  `：你好！` |  `你需要灌木丛吗？` |
| `:h 'sm'` | `NOTE: Use of the short form is rated PG.` |
 |  `:h 42` |  `生命、宇宙和一切的意义是什么？ 不幸的是，道格拉斯·亚当斯 (Douglas Adams) 是唯一知道这个问题真正含义的人，现在已经去世了. 所以现在你可能想知道死亡的意义是什么......` |
 |  `:h UserGettingBored` |  `当用户按同一个键 42 次时. 只是在开玩笑！  :-)` |
 |  `:h 栏` |  `这不是管道.` |
 |  `:h 圣杯` |  `亚瑟，你找到了！` |
 |  `:h 地图模式` |  `:nunmap 也可以在修道院外使用.` |
 |  `：帮助！` |  `E478：不要恐慌！`（故障？当在帮助缓冲区（`buftype=help`）中使用时，它的工作方式类似于 `:h help.txt`.）
 |  `：微笑` | 自己试试看.  ;-) 在 7.4.1005 中添加.  |
 |  `：嗨！` |  `你好，Vim 用户！` |

## Why hjkl for navigation?

When [Bill Joy](https://en.wikipedia.org/wiki/Bill_Joy) 创建
[vi](https://en.wikipedia.org/wiki/Vi)，Vim 的前身，他是在一个
[ADM-3A](https://en.wikipedia.org/wiki/ADM-3A) 没有额外的光标按钮
但是用过，你可能已经猜到了，hjkl 代替了.

键盘布局： [click](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-adm-3a-layout.jpg)

这也说明了为什么在 Unix 系统上使用 ~ 来表示主目录.

## Common problems

## Editing small files is slow

有两件事会对性能产生巨大影响：

 1.复杂的**正则表达式**. 特别是 Ruby 语法文件引起
   人们过去有减速.  （另见 [Debugging syntax files](#debugging-syntax-files).)
 2. **屏幕重绘**. 某些功能会强制重绘所有线条.

 | 典型罪魁祸首 | 为什么？  | 解决方案？  |
|-----------------|------|-----------|
 |  `：设置光标线` | 导致所有线条重绘.  |  `:set nocursorline` |
 |  `:set cursorcolumn` | 导致所有线条重绘.  |  `:set nocursorcolumn` |
| `:set relativenumber`    | Causes all lines to redraw. | `:set norelativenumber` |
 |  `:set foldmethod=syntax` | 如果语法文件已经很慢，这会使情况变得更糟.  |  `:set foldmethod=manual`, `:set foldmethod=marker` 或 [FastFold](https://github.com/Konfekt/FastFold) |
 |  `:set synmaxcol=3000` | 由于内部表示，Vim 通常在长行方面存在问题. 突出显示第 3000 列之前的列.  `:set synmaxcol=200` |
 | 匹配paren.vim | 默认加载. 使用正则表达式查找伴随的括号.  | 禁用插件：`:h matchparen` |

**注意**：您只有在体验实际性能时才需要这样做
缺点. 在大多数情况下，使用上面提到的东西绝对没问题.

## Editing huge files is slow

大文件的最大问题是 Vim 一次读取整个文件. 这
由于缓冲区在内部的表示方式而完成.
([Discussion on vim_dev@](https://groups.google.com/forum/#!topic/vim_dev/oY3i8rqYGD4/discussion))

如果你只想阅读，`tail hugefile |  vim -` 是一个很好的解决方法.

如果您暂时可以不用语法、设置和插件：

```
$ vim -u 无 -N
```

这应该会使导航速度快很多，特别是因为没有昂贵
使用语法突出显示的正则表达式. 你还应该告诉 Vim
不要使用 swapfiles 和 viminfo 文件以避免长时间的写入延迟：

```
$ vim -n -u 无 -i 无 -N
```

简而言之，真正打算编写时尽量避免使用 Vim
巨大的文件.  :\

## Bracketed paste (or why do I have to set 'paste' all the time?)

括号粘贴模式允许终端仿真器区分键入的文本
并粘贴文字.

你有没有试过将代码粘贴到 Vim 中，然后一切似乎都乱七八糟
up?

仅当您通过“cmd+v”、“shift-insert”、“middle-click”等粘贴时才会发生这种情况.
因为那时你只是在终端模拟器上扔文本.  Vim 没有
知道你刚刚粘贴了文本，它认为你是一个非常快速的打字员.
因此，它试图缩进行并失败.

显然这不是问题，如果你使用 Vim 的寄存器粘贴，例如 `&quot;+p`，
因为那时 Vim 知道你实际上是在粘贴.

要解决此问题，您必须 `:set paste`，以便按原样粘贴. 参见`:h
&#39;粘贴&#39;` 和 `:h &#39;pastetoggle&#39;`.

如果你厌倦了一直切换“粘贴”，看看这个很好
为你做的插件：
[bracketed-paste](https://github.com/ConradIrwin/vim-bracketed-paste).

附加阅读来自与插件相同的作者：
[here](http://cirw.in/blog/bracketed-paste).

**Neovim**：Neovim 试图让所有这一切变得更加无缝并设置
如果终端仿真器支持，则自动使用括号粘贴模式.

## Delays when using escape key in terminal

如果您使用命令行，您可能会使用所谓的 _terminal
emulator_ 像 xterm、gnome-terminal、iTerm2 等（相对于真正
[terminal](https://en.wikipedia.org/wiki/Computer_terminal)).

像他们的祖先一样，终端仿真器使用 [escape
序列 ] ( https://en.wikipedia.org/wiki/Escape_sequence ) ( 或者 _control
sequences_) 来控制移动光标、改变文本颜色等.
它们只是以转义字符开头的 ASCII 字符字符串
（显示在 [caret notation](https://en.wikipedia.org/wiki/Caret_notation) 作为
 `^[`). 当这样的字符串到达​​时，终端仿真器查找
伴随动作 [terminfo](https://en.wikipedia.org/wiki/Terminfo)
database.

为了使问题更清楚，我将首先解释映射超时. 他们总是
当映射之间存在歧义时会发生：

```vim
:nnoremap ,a :echo &#39;foo&#39;<cr>
:nnoremap ,ab :echo &#39;bar&#39;<cr>
```

两种映射都按预期工作，但在键入 `,a` 时，会有 1 的延迟
其次，因为 Vim 会等待用户是否键入另一个 `b`.

转义序列带来同样的问题：

 -`<esc>  ` 经常用于返回正常模式或退出操作.
- 光标键使用转义序列进行编码.
- Vim 期望<kbd>Alt</kbd> （也称为_元键_）发送一个正确的 8 位
  设置高位编码，但许多终端仿真器不支持它
  （或者默认情况下不启用它）并改为发送转义序列.

您可以像这样测试上面的内容：`vim -u NONE -N` 并输入 `i<c-v><left>  `和
您会看到插入的序列以 `^[` 开头，表示转义
character.

简而言之，Vim 很难区分类型
 `<esc>  ` 字符和正确的转义序列.

默认情况下，Vim 使用 `:set timeout timeoutlen=1000`，所以它会延迟歧义
映射和键码减少 1 秒. 这是映射的合理值，但是
您可以自己定义最常见的关键代码超时
整个问题的解决方法：

```vim
为映射设置超时
设置 timeoutlen=1000 &quot; 默认值
为关键代码设置 ttimeout &quot;
设置 ttimeoutlen=10 &quot; 不明显的小值
```

在 `:h ttimeout` 下你会发现一个小表格显示了两者之间的关系
这些选项.

如果你在 Vim 和你的终端模拟器之间使用 tmux，也把它放在
你的 ~/.tmux.conf ：

```tmux
设置-sg 转义时间 0
```

## Function search undo

- 命令中的搜索模式（`/`、`:substitute`、...）更改了“上次使用
  搜索模式”.（它保存在 `/` 寄存器中；用 `:echo @/` 打印它）.
 - 可以使用 `.` 重做一个简单的文本更改.  （保存在`.`寄存器中；
  用 `:echo @.` 打印它）.

但是，如果您从一个函数中执行它们，那么这两件事都_not_是这样的！ 因此你
无法轻松突出显示函数中的单词或重做由
it.

帮助：`:h function-search-undo`

## Technical quirks

## Newline used for NUL

文件中的 NUL 字符 (`\0`) 在内存中存储为换行符 (`\n`) 并且
在缓冲区中显示为 `^@`.

有关更多信息，请参阅“man 7 ascii”和“:h NL-used-for-Nul”.

## Terminology

## Vim script? Vimscript? VimL?

`Vim script`、`Vimscript` 和 `VimL` 指的是同一个东西：
用于编写 Vim 脚本的编程语言. 虽然
[8.0.360](https://github.com/vim/vim/commit/b544f3c81f1e6a50322855681ac266ffaa8e313c)
将所有引用从 `VimL` 更改为 `Vim script`，现在可以考虑
官方术语 `VimL` 仍然在互联网上广为流传.

无论您使用哪个术语，每个人都会理解.
