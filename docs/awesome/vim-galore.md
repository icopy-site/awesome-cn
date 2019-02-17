<div class="github-widget" data-repo="mhinz/vim-galore"></div>
<div align='center'>
  <br /><br /><br />
  <img src='https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/logo-vim-galore.png' alt='vim-galore logo' />
  <br /><br /><br /><br />
  <div>
    <a href='https://github.com/wsdjeg/vim-galore-zh_cn'>中文</a> |
    <a href='http://postd.cc/?s=vim-galore'>日语</a> |
    <a href='https://github.com/lsrdg/vim-galore'>葡萄牙语</a> |
    <a href='http://givi.olnd.ru/vim-galore/vim-galore-ru.html'>俄语</a>
    <div>
      <br />
      <sub>根据<a href='https://creativecommons.org/licenses/by-sa/4.0'>CC BY-SA 4.0获得</a>许可<a/>.</a></sub>
    </div>
  </div>
  <br /><br />
</div>










- [:global and :vglobal](#global-and-vglobal) - 在所有匹配的行上执行命令.
- [:normal and :execute](#normal-and-execute) - 脚本梦想团队.
- [:redir and execute()](#redir-and-execute) - 捕获命令输出.











### [List of colorschemes](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#colorschemes-1)

### [List of plugins](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md)

<br>

## Intro

## What is Vim?

[Vim](http://www.vim.org) 是一个文本编辑器，有很长的祖先
回到 [qed](https://en.wikipedia.org/wiki/QED_(text_editor) ）.  [布拉姆
Moolenaar]（https://en.wikipedia.org/wiki/Bram_Moolenaar）于1991年发布.

该项目在线托管 [vim.org](http://www.vim.org/index.php).

获取Vim：使用您最喜欢的包管理器或访问[下载
页面]（http://www.vim.org/download.php）来自vim.org.

讨论和用户问题最好在
[vim_use](https://groups.google.com/forum/#!forum/vim_use) 邮件列表或使用
IRC（[Freenode](https://freenode.net)) in the `#vim` channel.

发展正在发生 [GitHub](https://github.com/vim/vim)，讨论
[vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮件列表.

Read [Why, oh WHY, do those #?@! nutheads use
vi？]（http://www.viemu.com/a-why-vi-vim.html）看到常见的误解
Vim解释道.

## The Vim Philosophy

 Vim坚持模态编辑理念.  这意味着它提供
multiple modes and the meaning of keys changes according to the mode. You
在_normal mode_中导航文件，在_insert mode_中插入文本，然后选择
在_visual mode_中的行，您可以在_command-line mode_中访问命令，依此类推.
这听起来可能很复杂，但有一个巨大的优势：你没有
通过一次握住几把钥匙来打破你的手指，大多数时候你
 只需一个接一个地按下它们.  任务越常见，密钥越少
是必要的.

与模态编辑一起使用的相关概念是运算符和运动.
_Operators_开始某项操作，例如更改，删除或选择文本.
然后，使用_motion_指定要对其执行操作的文本区域.
要更改括号之间的所有内容，请使用`ci（`（read _change inner
 括弧_）.  要删除整段文本，请使用`dap`（读_delete
在段落_）.

如果您看到高级Vim用户正在工作，您会发现他们说的是
 _Vim_的语言以及钢琴家处理他们的乐器.  复杂
 仅使用几次按键即可完成操作.  他们甚至都没想过
再也像 [muscle memory](https://en.wikipedia.org/wiki/Muscle_memory) 拿
 已经结束了.  这减少了[认知
加载]（https://en.wikipedia.org/wiki/Cognitive_load）并有助于专注于
实际任务.

## First steps

Vim捆绑了一个教授最基本的互动教程
 你需要知道的事情.  你可以从shell启动它：

```
$ vimtutor
```

 不要被它看起来多么无聊并且通过练习来解决.  该
你之前使用的编辑器或IDE很可能都是非模态的，所以工作
切换模式起初看起来很尴尬，但你使用Vim越多，越多
它成为了 [muscle memory](https://en.wikipedia.org/wiki/Muscle_memory).

Vim被拴上了 [Stevie](https://en.wikipedia.org/wiki/Stevie_(text_editor)）， 一个
[vi](https://en.wikipedia.org/wiki/Vi) 克隆，并支持两种操作模式：
 “兼容”和“不兼容”.  在兼容模式下使用Vim意味着使用vi
 所有选项的默认值，与Vim默认值相反.  只要你没有创造
 一个用户vimrc尚未启动或使用`vim -N`启动Vim，假设兼容模式！  别
 在兼容模式下使用Vim.  只是不要.

下一步：

1.创建自己 [vimrc](#minimal-vimrc).
有一些 [cheatsheets](#cheatsheets) 准备好第一周.
阅读 [basics](#basics-1) 要了解什么是可能的部分.
 4.随时学习！  你永远不会完成学习Vim.  如果遇到任何问题
    问题，只需在互联网上查找.  你的问题已经解决了.
   Vim附带了很好的文档，知道如何导航它是必须的：
   [Getting help offline](#getting-help-offline).
看看吧 [additional resources](#additional-resources).

最后一点建议：在开始添加所有内容之前，请先了解如何正确使用Vim
各种炒作 [plugins](#managing-plugins) 只实现功能
Vim已经原生支持了.

## Minimal vimrc

用户vimrc可以放入`〜/ .vimrc`或为了更好的分离
 进入`〜/ .vim / vimrc`.  后者使整个配置变得容易
在版本控制下并将其上传到，让我们说GitHub.

你在网上找到了很多“最小的vimrcs”，也许我的版本不是那样
应该是最小的，但它提供了我认为的一套良好的理智设置
对于开始有用.

最后你必须阅读所有提到的设置并决定
 为自己.  :-)

所以这里是： [minimal-vimrc](https://github.com/mhinz/vim-galore/blob/master/static/minimal-vimrc.vim)

如果您有兴趣，请点击这里
[my vimrc](https://github.com/mhinz/dotfiles/blob/master/.vim/vimrc).

**提示**：大多数插件作者都会保留几个插件并发布他们的插件
GitHub上的vimrc（通常在名为“vim-config”或“dotfiles”的存储库中），所以
每当你找到你喜欢的插件时，请查看其维护者的GitHub页面
浏览存储库.

## What kind of Vim am I running?

查看`：version`将为您提供您需要了解的所有信息
如何编译当前运行的Vim二进制文件.

第一行告诉您何时编译二进制文件和版本，例如7.4.
接下来的一行说明了“包含的补丁：1-1051”，这是补丁
 水平.  因此，您确切的Vim版本是7.4.1051.

另一行说的是“没有GUI的小版本”或“巨大的版本”
 用GUI`.  显而易见的信息是你的Vim是否包含GUI
支持，例如从shell启动`gvim`或从Vim运行`：gui`
 在终端模拟器中.  其他重要信息是“Tiny”和
 `Huge`.  Vim区分称为“tiny”，“small”，“normal”的特征集，
`big`和`huge`，都可以启用不同的功能子集.

大多数`：version`输出由功能列表本身使用.
`+ clipboard`表示编译的剪贴板功能，`-clipboard`表示它
没有编译.

 需要编译一些Vim功能才能使它们正常工作.  例如``prof` to
工作，你需要一个具有巨大功能集的Vim，因为该集启用了
`+ profile`功能.

如果不是这样，并且您从包管理器安装了Vim，请确保
安装名为`vim-x`，`vim-x11`，`vim-gtk`，`vim-gnome`或
类似的，因为这些包通常带有巨大的功能集.

您还可以通过编程方式测试版本或功能：

```vim
“如果启用+配置文件至少运行Vim 7.4.42，请执行某些操作.
if（v：version&gt; 704 || v：version == 704 &amp;&amp; has（&#39;patch42&#39;））&amp;&amp; has（&#39;profile&#39;）
  “ 做东西
endif
```

Help:

```
：h：版本
：h功能列表
：h +功能列表
：h有补丁
```

## Cheatsheets

- http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png
- https://cdn.shopify.com/s/files/1/0165/4168/files/preview.png
- http://www.nathael.org/Data/vi-vim-cheat-sheet.svg
- http://michael.peopleofhonoronly.com/vim/vim_cheat_sheet_for_programmers_screen.png
- http://www.rosipov.com/images/posts/vim-movement-commands-cheatsheet.png

或者从Vim内快速打开一张备忘单： [vim-cheat40](https://github.com/lifepillar/vim-cheat40).

## Basics

## Buffers, windows, tabs

 Vim是一个文本编辑器.  每次显示文本时，文本都是文本的一部分
 **缓冲**.  每个文件都将在自己的缓冲区中打开.  插件显示内容
他们自己的缓冲等

缓冲区有许多属性，例如它包含的文本是否可修改，
或者它是否与文件相关联，因此需要同步
磁盘保存.

 ** Windows **是视口_onto_ buffers.  如果要查看多个文件
在同一个文件的同一时间甚至不同的位置，您使用的是Windows.

 请不要叫他们_splits_.  您可以将窗口拆分为两个，但是
这不会使他们_splits_.

Windows可以垂直或水平分割，高度和宽度分开
 现有的窗户也可以改变.  因此，您可以使用任何窗口
您喜欢的布局.

 **标签页**（或只是标签页）是一组窗口.  因此，如果你想
使用多个窗口布局，使用选项卡.

简而言之，如果你在没有参数的情况下启动Vim，你就会拥有一个
标签页，其中包含一个显示一个缓冲区的窗口.

顺便说一句，缓冲区列表是全局的，您可以从任何缓冲区访问任何缓冲区
tab.

## Active, loaded, listed, named buffers

 像这样的`vim file1`运行Vim.  文件的内容将加载到缓冲区中.
 你现在有一个**加载的缓冲区**.  缓冲区的内容仅是同步
如果将其保存在Vim中，则转到磁盘（写回文件）.

 由于缓冲区也显示在窗口中，因此它也是**活动缓冲区**.  现在
如果你通过`：e file2`加载另一个文件，`file1`将成为**隐藏缓冲区**
和`file2`是活动的.

两个缓冲区也**列出**，因此它们将列在输出中
 `：ls`.  插件缓冲区或帮助缓冲区通常标记为未列出，因为
 它们不是您通常使用文本编辑器编辑的常规文件.  列出和
未列出的缓冲区可以通过`：ls！`显示.

**未命名的缓冲区**（也经常被插件使用）是没有缓冲区的缓冲区
 相关文件名.  例如`：enew`将创建一个未命名的临时缓冲区.  加
一些文本并通过`：w / tmp / foo`将其写入磁盘，它将成为一个命名
buffer.

## Argument list

The [global buffer list](#buffers-windows-tabs)  是Vim的事.  在那之前，在
vi，这里只有参数列表，也可以在Vim中找到.

在shell命令行中给Vim赋予的每个文件名都记在
 参数列表.  可以有多个参数列表：默认情况下所有参数
被放入全局参数列表，但你可以使用`：arglocal`来创建一个
窗口本地的新参数列表.

 用`：args`列出当前参数.  从参数切换文件
 列表与`：next`，`：previous`，`：first`，`：last`和朋友.  改变它
`：argadd`，`：argdelete`或`：args`，带有文件列表.

如果您更喜欢使用缓冲区或参数列表来处理文件
 品味问题.  我的印象是大多数人都使用缓冲区列表
exclusively.

然而，参数列表有一个巨大的用例：批处理
 通过`：argdo`！  一个简单的重构示例：

```vim
：args ** / *.[ch]
 ：argdo％s / foo / bar / ge |  更新
```

这将在所有C源文件和头文件中替换“bar”中出现的所有“foo”
从当前目录及以下.

帮助：`：h argument-list`

## Mappings

 您可以使用`：map`系列命令定义自己的映射.  每
 该系列的命令定义了某组模式的映射.  技术上
 Vim带有惊人的12种模式，其中6种可以映射.  另外，一些
命令一次作用于多个模式.

 |  递归|  非递归|  取消映射|  模式|
|-----------|---------------|-----------|----------------------------------|
 |  `：map` |  `：noremap` |  `：unmap` |  正常，视觉，操作员待定|
 |  `：nmap` |  `：nnoremap` |  `：nunmap` |  正常|
 |  `：xmap` |  `：xnoremap` |  `：xunmap` |  视觉|
 |  `：cmap` |  `：cnoremap` |  `：cunmap` |  命令行|
 |  `：omap` |  `：onoremap` |  `：ounmap` |  operator-pending |
 | |  `：map` |  `：inoremap` |  `：iunmap` |  插入|

例如，这仅定义了正常模式的映射：

```vim
 ：NMAP <space>  ：echo“foo” <cr>
```

 使用`：nunmap再次取消映射 <space>  `.

对于更多但非常罕见的模式（或它们的组合），请参阅`：h
map-modes`.

 到现在为止还挺好.  只有一个问题可能会令人困惑
 初学者：`：nmap`是_recursive_！  也就是说，右手拿其他
考虑到映射.

所以你定义了一个简单地回应“Foo”的映射：

```vim
：nmap b：echo“Foo” <cr>
```

但是如果你想将`b`的默认行为（将一个单词返回）映射到
另一个关键？

```vim
：nmap ab
```

如果你点击<kbd>a</kbd> ，我们希望光标返回一个单词，而是
 “Foo”在命令行中打印！  因为右边的&#39;b`是
 映射到另一个动作，即`：echo“Foo” <cr>  `.

解决此问题的正确方法是使用_non-recursive_ mapping
instead:

```vim
：nnoremap ab
```

经验法则：除非实际进行递归，否则始终使用非递归映射
desired.

 通过不给右侧来查找您的映射.  例如`：nmap`显示全部
 普通映射和`：nmap <leader>  `显示所有以＃开头的正常映射
枫树.

 如果要禁用标准映射，请将它们映射到特殊的` <nop>  `
 字符，例如`：noremap <left><nop>  `.

Help:

    ：h键符号
    ：h映射
    ：h 05.3

## Mapleader

mapleader只是一个占位符，可以与自定义映射一起使用
默认设置为`\`.

```vim
 nnoremap <leader>  h：helpgrep <space>
```

 该映射由`\ h`触发.  如果你想使用` <space>  h`而不是：

```vim
让mapleader =&#39;&#39;
 nnoremap <leader>  h：helpgrep <space>
```

 而且，有` <localleader>  `那是`的当地对应物 <leader>  `
并且应该用于缓冲区本地的映射，例如.
 特定于文件类型的插件.  它也默认为`\`.

 **注意**：在映射之前设置fotaders！  所有领导者映射都在
 效果已经不会因为修理者改变而改变.  `：NMAP
<leader> `将显示所有正常模式的领导者映射，并解决了mapleader
已经，所以用它来仔细检查你的映射.

有关更多信息，请参阅`：h mapleader`和`：h maplocalleader`.

## Registers

 寄存器是保存文本的插槽.  调用将文本复制到寄存器中
** yanking **并从寄存器中提取文本称为**粘贴**.

Vim提供以下寄存器：

 |  输入|  人物|  填充？  |  只读？  |  包含来自的文字？  |
|---------------------|------------------------|------------|-----------|---------------------|
 |  未命名的|  ```| vim | [] |最后猛拉或删除.（`d`，`c`，`s`，`x`，`y`）|
 |  编号|  `0`到&#39;9` |  vim |  [] |  注册`0`：最后猛拉.  注册`1`：最后删除.  注册`2`：第二次删除.  等等.  将寄存器“​​1” - “9”视为只读 [queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type) ）有9个元素.  |
 |  小删除|  `-` |  vim |  [] |  上次删除少于一行.  |
 |  命名为|  `a`到`z`，`A`到`Z` |  用户|  [] |  如果你想要注册`a`，你可以替换它的文本.  如果你想要注册“A”，你可以在寄存器“a”中附加文本.  |
 |  只读|  `：`，`.`，`％`|  vim |  [x] |  `：`：上一个命令，`.`：最后插入的文本，`％`：当前文件名.  |
| Alternate buffer    | `#`                    | vim        | [ ]       | Most of the time the previously visited buffer of the current window. See `:h alternate-file` |
 |  表达|  `=`|  用户|  [] |  评估被猛拉的VimL表达式.  例如，在插入模式下执行此操作：` <c-r>  = 5 + 5 <cr>  `和“10”将被插入缓冲区.  |
 |  选择|  `+`，`*`|  vim |  [] |  `*`和`+`是 [clipboard](#clipboard)  寄存器.  |
 |  掉落|  `~` |  vim |  [x] |  从上次拖车开始.  |
 |  黑洞|  `_` |  vim |  [] |  如果您不希望任何其他寄存器受到隐式影响.  例如``_dd`删除当前行而不影响寄存器```，`1`，`+`，`*`.  |
 |  最后搜索模式|  `/`|  vim |  [] |  最后一个模式用于`/`，`？`，`：global`等

每个不是只读的寄存器可以由用户设置：

```vim
：让@ / =&#39;注册&#39;
```

之后<kbd>n</kbd>会跳到下一次出现的“寄存器”.

当寄存器被隐式填充时有很多例外，所以一定要确定
读`：h registers`.

用`y`猛拉并用&#39;p` /`P`粘贴，但请记住Vim区分
 字符和线性视觉选择.  见`：h linewise`.

**Example: linewise**

`yy`（或只是&#39;Y`）猛拉当前行，将光标移动到其他地方，使用
`p`粘贴在当前行&#39;P`下面以粘贴它.

**示例：charwise **

用“0yw”将第一个单词拉出来，移动到其他地方，在光标打开后粘贴
带有`p`的当前行和带有&#39;P`的光标前面的行.

**示例：显式命名寄存器**

`“aY”将当前行拉入寄存器`a`.移到另一行.“”AY`
将当前行追加到寄存器`a`.

我建议稍微调试所有这些寄存器并不断检查
`：reg`，所以你可以看到实际发生了什么.

**有趣的事实**：在Emacs中，“yanking”代表粘贴（或之前的_reinserting）
杀死text_）不复制.

## Ranges

范围很容易理解，但许多Vimmers不知道他们
充分发挥潜力

- 许多命令采用范围.
- 地址表示某一行.
- 范围是单个地址或由两者分隔的一对地址
  `，`或`;`.
- 范围告诉命令要对哪些行进行操作.
  - 默认情况下，大多数命令仅在当前行上起作用.  值得注意的例外是
  `：write`和`：global`，它们作用于所有行.

范围的使用非常直观，所以这里有一些例子（使用`：d`
作为`：delete`的缩写形式：

 |  命令|  行作用于|
|---------|----------------|
 |  `：d` |  当前行.  |
 |  `：.d` |  当前行.  |
 |  `：1d` |  第一行.  |
 |  `：$ d` |  最后一行.  |
 |  `：1，$ d` |  所有线路.  |
 |  `：％d` |  所有行（&#39;1，$`的语法糖）.  |
 |  `：.，5d` |  当前第5行到第5行
 |  `：，5d` |  也是第5行的当前行
 |  `：，+ 3d` |  当前行和接下来的3行.  |
 |  `：1，+ 3d` |  第一行到当前行+ 3. |
 |  `：， -  3d` |  当前行和最后3行.  （Vim会提示你，因为这是一个相反的范围.）|
 |  `：3，&#39;xdelete` |  第3行到标记的行 [mark](#marks)  X.  |
 |  `：/ ^ foo /，$ delete` |  从以“foo”开头到下一行的下一行.  |
 |  `：/ ^ foo / + 1，$ delete` |  从以“foo”开头的行之后的行到结尾.  |

 注意，而不是`，`，`;`可以用作分隔符.  不同之处在于
在`from，to`的情况下，_to_是相对于当前行的，但是当
 使用`from; to`，_to_是相对于_from_的地址！  假设你是
在第5行，`：1，+ 1d`将删除1到6行，而`：1; + 1d`只会删除
删除第1行和第2行.

 `/`地址前面可以有另一个地址.  这允许你_stack_
模式，例如：

```vim
:/foo//bar//quux/d
```

这将删除第一行后面包含“quux”的第一行
在当前行之后包含“foo”的第一行之后包含“bar”.

 有时候Vim会自动在命令行中添加一个范围.  例如，开始一个
 用`V`选择视线，选择一些线并输入`：`.  命令行
将使用“&lt;，”&gt;“范围填充，这意味着将执行以下命令
 使用先前选择的行作为范围.  （这也是你有时候的原因
 看看像`：vnoremap foo这样的映射： <c-u>  command`.  在这里 <c-u>  `用于删除
范围，因为当给命令的范围时，Vim会抛出错误
不支持它.）

 另一个例子是在正常模式下使用`!!`.  这将填补
 命令行与`：.！`.  如果后面跟着一个外部程序，那个程序就是
 输出将替换当前行.  所以你可以替换当前
 使用`：？^ $？+ 1，/ ^ $ /  -  1！ls`输出ls的段落.  花式！

Help:

```
：h cmdline-ranges
：h 10.3
```

## Marks

您可以使用标记记住文件中的位置，即行号和列.

 |  标记|  设置为.. |  用法|
|-------|----------|-------|
 |  `a`  - `z` |  用户|  本地到文件，因此仅在一个文件中有效.  跳到小写标记，表示在当前文件中跳转.  |
 |  `A`  - `Z` |  用户|  全局，因此在文件之间有效.  也称为_file marks_.  跳转到文件标记可能会切换到另一个缓冲区.  |
 |  `0`  - `9` |  viminfo |  `0`是最后写入viminfo文件时的位置.  实际上，这意味着最后一个Vim进程结束.  `1`是第二个最后一个Vim进程结束时的位置，依此类推.  |

Put `'`/`g'` or `` ` ``/`` g` `` in front of a mark to form a motion.

 使用“mm”记住标记为“m”的当前位置.  移动文件
然后通过`&#39;m`（第一个非空白）或```m``（精确列）跳回来.
如果你告诉你的viminfo，退出Vim后会记住小写标记
文件，请参阅`：h viminfo-&#39;`.

 使用`mM`记住文件标记为“M”的当前位置.  切换到另一个
缓冲并通过&#39;&#39;M`或```M``切换回来.

其他动议包括：

 |  动作|  跳转到.. |
|------------------|-----------|
 |  `&#39;[`，```[``|  先前更改或抽出文本的第一行或字符.  |
 |  `&#39;]`，```````  以前更改或抽出文本的最后一行或字符.  |
| `'<`, `` `< ``   | Beginning line or character of last visual selection. |
 |  `&#39;&gt;`，```````  最后一次视觉选择的结束行或字符.  |
 |  `&#39;&#39;``````````  最新跳跃前的位置.  |
 |  `&#39;“`，```````  上次退出当前缓冲区时的位置.  |
 |  `&#39;^`，```^``|  上次插入停止的位置.  |
 |  `&#39;.`，```.  ``|  最后一次更改的位置.  |
 |  `&#39;（``````````|当前句子的开头
 |  `&#39;）`，```````  当前句子结束.  |
 |  `&#39;{`，```{``|  当前段落的开头.  |
 |  `&#39;}`，```}``|  当前段落结束.  |

标记也可用于 [range](#ranges) .  你可能之前看过这个
想知道这意味着什么：在视觉模式中选择一些文本并做`：`，
命令行将以`：&#39;&lt;，&#39;&gt;`开头，这意味着以下命令
会得到一个表示视觉选择的范围.

 使用`：marks`列出所有标记.  阅读`：h mark-motions`中的所有内容.

## Completion

 Vim提供多种插入模式完成.  如果有多个
匹配，弹出菜单将让您导航到您选择的匹配.

典型的完成类型是标签，来自导入模块的功能或
库，文件名，字典或只是当前缓冲区中的单词.

Vim为每种完成提供了一个映射，它们都是从它开始
 ` <c-x>  `（记得在插入模式下使用它们）：

 |  映射|  种类|  帮助|
|---------|------|--------------|
 |  ` <c-x><c-l>  `|  整线|  `：hi ^ x ^ l` |
 |  ` <c-x><c-n>  `|  来自当前文件的关键字|  `：hi ^ x ^ n` |
 |  ` <c-x><c-k>  `|  来自`&#39;dictionary&#39;`选项的关键字  `：hi ^ x ^ k` |
 |  ` <c-x><c-t>  `|  来自&#39;&#39;thesaurus&#39;选项的关键字|  `：hi ^ x ^ t` |
 |  ` <c-x><c-i>  `|  来自当前和包含文件的关键字|  `：嗨^ x ^ i` |
 |  ` <c-x><c-]>  `|  标签|  `：hi ^ x ^]`|
 |  ` <c-x><c-f>  `|  文件名|  `：hi ^ x ^ f` |
 |  ` <c-x><c-d>  `|  定义或宏|  `：hi ^ x ^ d` |
 |  ` <c-x><c-v>  `|  Vim命令|  `：hi ^ x ^ v` |
 |  ` <c-x><c-u>  `|  用户定义（在`&#39;completefunc&#39;中指定）|  `：嗨^ x ^ u` |
 |  ` <c-x><c-o>  `|  omn​​i completion（在&#39;&#39;omnifunc&#39;中指定）|  `：hi ^ x ^ o` |
 |  ` <c-x>  s` |  拼写建议|  `：hi ^ Xs` |

人们可能会对用户定义完成之间的差异感到困惑
 和omni完成，但从技术上讲，他们做同样的事情.  他们拿了一个
检查当前位置并返回建议列表的功能.
用户定义的完成由用户为其个人目的定义.
 （惊喜！）它可能是任何东西.  Omni完成意味着特定于文件类型
目的，如完成struct成员或类方法，并且通常由
文件类型插件.

Vim还允许通过设置来一次完成多种
 &#39;&#39;完整&#39;选项.  默认情况下，该选项包含了很多，所以一定要确保
 根据您的口味修剪它.  您可以使用`来触发此完成 <c-n>  `
 （下）和` <c-p>  `（上一个），它也恰好是用于的键
 在弹出菜单中选择条目.  有关详细信息，请参阅`：hi ^ n`和`：h&#39;complete&#39;
this.

一定要检查`：h&#39;completeopt&#39;`来配置行为
 弹出菜单.  默认是非常理智，但我更喜欢添加“noselect”.

Help:

```
：h ins-completion
：h popupmenu-keys
：h new-omni-completion
```

## Motions, operators, text objects

 **动作**移动光标.  你们都知道`h` /`j` /`k` /`l`.  或者`w`和`b`.  甚至
 `/`是动议.  他们也算一算.  `2？的 <cr>  `跳到最后一秒
发生“的”.

有关所有可用动作，请参阅“：h navigation”和以下所有内容.

**操作符**作用于文本区域，例如`d`，`~`，`gU`，`&gt;`来命名一个
 少数.  它们在两种情况下使用，无论是正常模式还是视觉模式.  正常
 在模式中，运算符首先跟随运动，例如`&gt; j`.  在视觉模式中，
操作员只需对选择进行操作，例如`Vjd`.

像运动一样，操作员需要计算，例如`2gUw`来计算当前的其余部分
 单词和下一个大写.  由于运动和操作员需要计数，
`2gU2w`同样适用并执行两次`gU2w`.

 对于所有可用的运算符，请参见`：h operator`.  使用`：set tildeop`来制作`~`
充当运营商.

**文本对象**作用于周围区域，与行动中的动作相反
 一个方向.  实际上他们在物体上工作，例如整个单词，整体
句子，括号之间的所有内容，等等.

文本对象不能用于在正常模式下移动光标，因为即使是
 最熟练的游标不能同时跳入两个方向.  有用
但是在可视模式下，因为已经选择了对象的一侧
并且光标只是跳转到另一侧.

文本对象以“i”（想想_inner_）或“a”（想想_around_）开头
 后跟一个表示该对象的字符.  使用`i`它只会作用于对象
 本身，在对象上加上“a”加上尾随空格.  例如`diw`删除了
当前单词和`ci（`改变括号之间的所有内容.

 文本对象需要计算.  想象一下`（（（）））`和光标在或之间
大多数内括号，然后`d2a（`将删除2对内括号
介于两者之间.

请参阅所有可用文本对象的`：h text-objects`.

## Autocmds

 很多时候，Vim会发布事件.  你通过使用钩住这些事件
autocmds.

 如果没有autocmds你就不会使用Vim.  他们一直都在使用，甚至
 如果你没注意到它.  不相信我？  检查`：au`，但不要输出
 压倒你.  这些都是现在生效的所有autocmds！

请参阅`：h {event}`以快速了解所有可用事件和`：h
autocmd-events-abc`了解更多详情.

一个典型的例子是设置特定于文件类型的设置：

```vim
autocmd FileType ruby​​ setlocal shiftwidth = 2 softtabstop = 2 comments- =：#
```

 但是缓冲区如何知道它包含Ruby代码？  因为另一个
autocmd检测到它并再次相应地设置文件类型
触发了`FileType`事件.

 每个人都为他们的vimrc添加的第一件事就是`filetype on`.  这个
只是意味着在启动时读取`filetype.vim`，它为autocmds设置
在阳光下几乎所有的文件类型.

 如果你足够勇敢，请看一下：`：e $ VIMRUNTIME / filetype.vim`.  搜索
对于“Ruby”，你会发现Vim只使用文件扩展名`.rb`来实现
检测Ruby文件：

**注意**：同一事件的Autocmds按照它们的顺序执行
 创建.  `：au`以正确的顺序显示它们.

```vim
au BufNewFile，BufRead * .rb，*.rbw setf ruby
```

在这种情况下，`BufNewFile`和`BufRead`事件在C中是硬编码
Vim的来源，每当你通过`：e`和类似的方式打开一个文件时就会发出
 命令.  之后来自`filetype.vim`的所有​​数百种文件类型都是
测试.

简而言之，Vim大量使用事件和autocmds
暴露一个干净的接口，以挂钩到该事件驱动的系统
customization.

帮助：`：h autocommand`

## Changelist, jumplist

 最后100次更改的位置保存在**更改列表**中.  一些
同一行的小变化将合并在一起，但位置将是
不过最后一次改变（如果你在中间添加了一些东西
这条线）.

每次跳跃时，位置_before_跳跃都会被记住
 ** **跳转列表.  跳转列表最多包含100个条目.  每个窗口都有自己的窗口
 跳转列表.  拆分窗口时，会复制跳转列表.

跳转是以下命令之一：```，`````，`G`，`/`，`？`，`n`，`N`，
`％`，`（`，`）`，`[[`，`]]`，`{`，`}`，`：s`，`：tag`，`L`，`M`，`H `和命令
开始编辑新文件.

| List       | List all entries | Go to older position | Go to newer position |
|------------|------------------|----------------------|----------------------|
 |  跳转列表|  `：跳跃`|  `[COUNT] <c-o>  `|  `[COUNT] <c-i>  `|
 |  变更清单|  `：更改`|  `[count] g;`|  `[count] g，`|

列出所有条目时，将使用标记“&gt;”来显示当前条目
 位置.  通常情况下，这将是位置1，即最新位置.

如果您希望在重新启动Vim后两个列表都保持不变，则需要使用
viminfo文件和`：h viminfo-&#39;`.

并且可以通过```````或`&#39;&#39;`跳转到.

Help:

```
：h变更清单
：h跳转列表
```

## Undo tree

 记住文本状态的最新变化.  你可以使用_undo_来
还原更改并_redo_重新应用以前还原的更改.

理解它的重要一点是数据结构最近持有
变化不是一个
[queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)）但是a
[tree](https://en.wikipedia.org/wiki/Tree_(data_structure) ）！  你的改变是
 树中的节点和每个节点（但顶部节点）都有一个父节点.  每个节点都有
 有关更改的文本和时间的信息.  分支是一系列节点
 从任何节点开始，然后转到顶级节点.  新分支在何时创建
撤消更改，然后插入其他内容.

```
ifoo<esc>
obar<esc>
obaz<esc>
u
oquux<esc>
```

现在你有3行，撤销树看起来像这样：

```
     FOO（1）
       /
    杆（2）
   /      \
baz（3）quux（4）
```

 撤消树有4个更改.  数字代表节点的_time_
created.

现在有两种方法来遍历这棵树，让我们称之为_branch-wise_和
_time-wise_.

 撤消（`u`）和重做（` <c-r>  `）分支工作.  它们在当前上下波动
 科.  `u`将文本状态恢复为节点“bar”之一.  另一个`你`
 将文本状态进一步恢复到节点“foo”之一.  现在` <c-r>  `
 回到节点“bar”和另一个`的状态 <c-r>  `到节点的状态
 “QUUX”.  （再也无法使用分支命令到达节点“baz”.）

 与此相反，`g -`和`g +`按时工作.  因此，`g-`将不会恢复为
节点“bar”的状态，就像“你”那样，但是按时间顺序排在前面的状态，
 节点“baz”.  另一个`g -`会将状态恢复为节点“bar”之一
 上.  因此，`g -`和`g +`分别只是及时地来回传递.

 |  命令/映射|  行动|
|-------------------|--------|
 |  `[count] u`，`：undo [count]`|  撤消[计数]更改.  |
 |  `[COUNT] <c-r>  `，`：redo` |  重做[count]更改.  |
 |  `U` |  撤消对最新更改行的所有更改.  |
 |  `[count] g-`，`：更早[count]？`|  转到较旧的文本状态[count]次.  “？”  可以是“s”，“m”，“h”，“d”或“f”.  例如`：较早的2d`从2天前进入文本状态.  `：之前的1f`将进入最新文件保存的状态.  |
 |  `[count] g +`，`：以后[count]？`|  与上述相同，但其他方向.  |

 撤消树保留在内存中，当Vim退出时将丢失.  请参阅[撤消
files](#undo-files) for how to enable persistent undo.

如果您对撤消树感到困惑，
[undotree](https://github.com/mbbill/undotree) 在可视化方面做得很好
it.

Help:

```
：h undo.txt
：h usr_32
```

## Quickfix and location lists

 quickfix列表是保存文件位置的数据结构.  实质上，
quickfix列表中的每个条目都包含文件路径，行号和
可选列和说明.

典型的用例是汇编编译器错误或grep工具的结果.

Vim有一种特殊类型的缓冲区用于显示quickfix列表：quickfix
 缓冲.  quickfix缓冲区中的每一行显示quickfix列表中的一个条目.

通常，您打开一个新窗口以显示quickfix列表：quickfix窗口.
发生这种情况时，最后一个窗口将与quickfix窗口关联.

 在quickfix缓冲区` <cr>  `在相关窗口中打开所选条目
 和` <c-w><cr>  `在新窗口中.

quickfix列表以[Aztec C.的“快速修复”功能命名
compiler](https://en.wikipedia.org/wiki/Aztec_C).

 实际上有两种列表：quickfix和位置列表.  他们表现得很好
几乎相同，但有以下差异：

  - 只有一个quickfix列表.  可以有多个位置列表;  一个
  窗口.
- 他们使用稍微不同的命令进行导航.

 |  行动|  Quickfix |  位置|
|----------------|--------------|--------------|
 |  打开窗口|  `：Copen` |  `：walk` |
 |  关闭窗口|  `：cclose` |  `：lclose` |
 |  下一个条目|  `：cnext` |  `：lnext` |
 |  上一个条目|  `：cprevious` |  `：lprevious` |
 |  第一次进入|  `：cfirst` |  `：lfirst` |
 |  最后一个条目|  `：clast` |  `：镇流器|

请注意，不需要为这些打开quickfix和位置窗口
命令工作.

有关更多信息，请参阅`：h quickfix`以及完整的命令列表.

为简明起见，_quickfix_和_location_通常缩写为_qf_和
_loc_分别.

**Example**:

让我们用我们好老朋友`grep`来搜索当前的文件
目录递归地为某个查询，并将结果放在quickfix中
list.

```vim
：let＆grepprg =&#39;grep -Rn $ *.&#39;
 ：握！  FOO
<grep output - hit enter>
:copen
```

假设任何文件包含字符串“foo”，它现在应该显示在
quickfix窗口.

## Macros

Vim允许_recording_类型的字符成为 [register](#registers) .  它是
 实时自动执行某些任务的好方法.  （对于更复杂的任务，Vim
应该使用脚本.）

  - 通过键入`q`然后输入寄存器开始录制，例如`q`.  （该
  命令行将通过“录制@q”表示这一点.）
- 再次按“q”停止录音.
- 通过`[count] @ q`执行宏.
- 通过`[count] @@`重复上次使用的宏.

**例1：**

插入一行并重复10次：

```
qq
iabc<cr><esc>
q
10@q
```

 （没有宏也可以这样做：`oabc <esc>  10.`）

**例2：**

要在所有行前面添加行号，请从第一行开始添加
 “1.”手动.  使用`增加光标下的数字 <c-a>  `
显示为“^ A”.

```
qq
0yf jP0 ^ A.
q
1000@q
```

这里我们只希望文件中包含的行不超过1000行
使用`1000 @ q`，但我们也可以使用_recursive macro_，直到执行
宏不能再应用于一行：

```
qq
0yf jP0 ^ A @ q
q
@q
```

（没有宏也可以这样做：`：％s / ^ / \ = line（&#39;.&#39;）.&#39;.&#39;``）

请注意，我还展示了如何在不使用宏的情况下实现相同的功能，但这一点
 主要适用于这些简单的例子.  对于更复杂的自动化，宏
是炸弹！


Help:

```
：录音
：h&#39;lazyredraw&#39;
```

## Colorschemes

 Colorschemes是为你的Vim设计风格的方式.  Vim由许多组件组成
每个都可以为前景定制不同的颜色，
背景和一些其他属性，如粗体文本等.它们可以设置为
this:

```vim
：突出显示正常ctermbg = 1 guibg =红色
```

 这会将编辑器的背景描绘成红色.  请参阅`：h：highlight`了解更多信息
information.

因此，colorschemes主要是`：highlight`命令的集合.

 实际上，大多数colorschemes真的是2色调！  上面的例子设置
 通过`ctermbg`和`guibg`的颜色.  前一个定义（`cterm *`）只会是
 如果Vim是在终端仿真器中启动的，例如xterm.  后者（`gui *`）
将用于gvim或MacVim等图形环境.

如果您碰巧在终端Vim中使用colorscheme而颜色没有
看起来像截图中的那些，很可能是colorscheme
 仅定义GUI的颜色.  相反，如果你使用图形Vim（例如
gvim或MacVim）和颜色看起来，colorscheme可能只定义
终端的颜色.

后一种情况可以通过在Neovim或Vim中启用真彩色来“解决”
 7.4.1830和更新.  这使得终端Vim使用GUI定义，但是
还需要终端仿真器本身和其间的所有软件（例如
 tmux）能够处理真实的颜色.  （[这个
gist]（https://gist.github.com/XVilka/8346728）给出了一个很好的概述
topic.)

Help:

- `：h&#39;termguicolors&#39;`
- [List of colorschemes](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#colorschemes-1)

## Folding

 每个文本（或源代码）都有一定的结构.  如果你有一个结构，它
 表示您具有逻辑上分隔的文本区域.  折叠允许“折叠”
 将这样的区域划分为单行并显示简短描述.  有
 许多命令作用于这些区域，称为_folds_.  折叠可以嵌套.

Vim区分了几种折叠方法：

 |  &#39;foldmethod&#39;|  用法|
|--------------|-------|
 |  diff |  在差异窗口中使用折叠未更改的文本.  |
 |  expr |  使用`&#39;foldexpr&#39;`基本上创建一个新的折叠方法.  |
 |  缩进|  基于缩进折叠.  |
 |  手册|  通过`zf`，`zF`和`：fold`自己创建折叠.  |
 |  标记|  基于文本中的标记折叠（通常在注释中）.  |
 |  语法|  基于语法折叠，例如折叠“if”块.  |

 **注意**：折叠可能是计算密集型的！  如果您遇到任何问题
性能缺点（打字时间小延迟），请看一下
[FastFold](https://github.com/Konfekt/FastFold)，这阻止了Vim
在不需要时更新折叠.

Help:

```
：h usr_28
：h折叠
```

## Sessions

如果你保存**视图**（`：h：mkview`），窗口的当前状态（和
保存选项和映射以供以后使用（`：h：loadview`）.

 **会话**保存所有窗口的视图加上全局设置.  基本上
制作当前Vim实例的快照并将其保存在会话文件中.
 让我强调一下：它保存了现状;  保存后完成的一切
 session不会成为会话文件的一部分.  要“更新”会话，只需写入
它再次出来.

这使它非常适合保存_projects_并且易于切换
them.

 马上试试吧！  打开几个窗口和标签，然后执行`：mksession Foo.vim`.  如果
 省略文件名，将假设`Session.vim`.  该文件将保存到
 当前的工作目录，检查`：pwd`.  重新启动Vim并执行`：source
Foo.vim`和voilà，缓冲区列表，窗口布局，映射，工作目录
 等等都应该与保存会话之前相同.  做更多的工作
and update the session by overwriting the already existing session file with
 `：mksession！  Foo.vim`.

请注意，会话文件实际上只是Vim命令的集合
应该恢复一个Vim实例的某个状态，所以随意拿一个
看看它：`：vs Foo.vim`.

您可以通过设置`&#39;sessionoptions&#39;来告诉Vim在会话中保存哪些内容.

出于脚本目的，Vim保留最后一个源或写会话的名称
在内部变量`v：this_session`中.

Help:

```
：h会话
：h&#39;sessionoptions&#39;
：HV：this_session
```

## Locality

Many of the concepts mentioned above also have _local_ counterparts:

 |  全球|  本地|  范围|  帮助|
|--------|-------|-------|------|
 |  `：set` |  `：setlocal` |  缓冲区或窗口|  `：h local-options` |
 |  `：map` |  `：地图 <buffer>  `|  缓冲区|  `：h：map-local` |
 |  `：autocmd` |  `：autocmd * <buffer>  `|  缓冲区|  `：h autocmd-buflocal` |
 |  `：cd` |  `：lcd` |  窗口|  `：h：lcd` |
 |  ` <leader>  `|  ` <localleader>  `|  缓冲区|  `：h maplocalleader` |

[Variables also have different scopes](https://vimhelp.appspot.com/usr_41.txt.html#41.2).

## Usage

## Getting help offline

Vim带有一个带有单个文本文件形式的优秀文档
 特殊布局.  Vim使用基于标签的系统来访问某些部分
那些帮助文件.

 首先，请阅读：`：help：help`.  这将打开文件
`$ VIMRUNTIME / doc / helphelp.txt`在新窗口中跳转到`：help`标签
在该文件中.

一些简单的规则：

- 选项用单引号括起来，例如`：h&#39;textwidth&#39;`
-  VimL函数以`（）`结尾，例如`：h reverse（）`
- 命令以`：`开头，例如`：h：echo`

 你可以用` <c-d>  `（这是<kbd>ctrl</kbd> + <kbd>d</kbd> ）列出所有标签
 匹配当前输入的查询.  例如`：h tab <c-d>  `会给你一份清单
标签从&#39;tab` over`&#39;softtabstop&#39;`到`setting-guitablabel`.

 您想列出所有VimL功能吗？  简单：`：h（） <c-d>  `.  你想列出所有
 与Windows有关的VimL功能？  `：h win *（） <c-d>  `.

这很快成为第二天性，但尤其是在开始时，你
 有时候不知道你要找的标签的任何部分.  你只能
 想象一些可能涉及的关键词.  `：helpgrep`来救援！

```
：helpgrep倒退
```

这将在所有文档文件中查找“向后”并跳转到第一个文档
 比赛.  匹配将在quickfix列表中汇编.  使用`：cn` /`：cp`来
 跳到下一个/上一个比赛.  或者使用`：copen`打开quickfix窗口，
 导航到一个条目并点击` <cr>  `跳到那场比赛.  参见`：h quickfix`
全部真相.

## Getting help offline (alternative)

这个列表是由最活跃的Vim开发人员之一@chrisbra编写
张贴到 [vim_dev](https://groups.google.com/forum/#!forum/vim_dev).

它在这里重新发布了一些细微的变化.

---

如果您知道自己在寻找什么，通常可以更轻松地进行搜索
使用帮助系统，因为主题遵循某种风格指南.

此外，帮助具有属于您的特定Vim版本的优势，因此
过时添加的主题或主题不会出现.

因此，学习帮助系统及其使用的语言至关重要.
这里有一些例子（不一定完整，我可能已经忘记了
something).

 1.选项用单引号括起来.  所以你会使用`：h&#39;list&#39;`去
    列表选项的帮助主题.  如果你只知道，你正在寻找一个
   某些选项，你也可以做`：h options.txt`来打开帮助页面
   描述所有选项处理，然后您可以使用常规搜索
    表达式例如`/ width`.  某些选项有自己的命名空间，例如`：h
   cpo-a`，`：h cpo-A`，`：h cpo-b`，依此类推.

 2.正常模式命令就是这样.  使用`：h gt`转到帮助页面
   “gt”命令.

3. Regexp项始终以“/”开头，因此`：h / \ +`将您带到帮助项目
    对于Vim正则表达式中的“\ +”量词.  如果你需要了解任何事情
   正则表达式，从`：h pattern.txt`开始阅读.

 4.组合键.  它们通常以单个字母开头，表示模式
    可以使用它们.  例如`：h i_CTRL-X`带你去的家庭
   用于插入模式的CTRL-X命令可用于自动完成不同的操作
    的东西.  请注意，某些键始终写为相同，例如Control
    将永远是CTRL.  注意，对于普通模式命令，保留“n”，
    例如`：h CTRL-A`.  相反，`：h c_CTRL-R`将描述CTRL-R的作用
   在命令行中输入命令和`：h v_Ctrl-A`谈论
   在视觉模式中递增数字和`：h g_CTRL-A`谈论g <C-A>
    命令（因此你必须按“g”然后 <Ctrl-A>  ）.  这里的“g”代表
   正常命令“g”，在执行之前总是期望第二个键
   类似于以“z”开头的命令.

5.注册总是以“引用”开头，所以使用`：h quote`来查找
   特别“：”注册.

 6. Vim脚本（VimL）可以在`：h eval.txt`找到.  某些方面
   语言可在`：h expr-X`获得，其中&#39;X&#39;是单个字母，例如`：h
    expr-！`将带您进入描述&#39;！&#39;的主题  （不）运营商
    VimL.  同样重要的是，请参阅`：h function-list`以查找简短描述
   所有功能.

 7.在帮助页面`：h map.txt`中讨论了映射.  使用`：h mapmode-i`
    找出`：imap`命令.  也可以使用`：map-topic`来查找
   关于某些特定于映射的子主题（例如`：h：map-local` for
    缓冲局部映射或`：h map_bar`如何&#39;|&#39;  在映射中处理.

8.命令定义在`：h command- *`中讨论，所以使用：h command-bar
    找出&#39;！&#39;  自定义命令的参数.

9.窗口管理命令总是以CTRL-W开头，所以你找到了
   在`：h CTRL-W_ *`的相应帮助（例如`：h CTRL-W_p`用于切换到
    以前访问过的窗口）.  您也可以访问`：h windows.txt`并阅读
   如果你正在寻找窗口处理命令，你的方式通过.

10. Ex commands always start with ":", so `:h :s` covers the ":s" command.

11. Use CTRL-D after typing a topic and let Vim try to complete to all available
    话题.

12.使用`：helpgrep`搜索所有帮助页面（通常还包括帮助
     安装插件的页面）.  有关如何使用它，请参阅`：h：helpgrep`.  一旦您
    已经搜索了一个主题，所有匹配都可以在quickfix中找到（或者
     location）窗口可以用`：copen`或`：lopen`打开.  在那里
    也可以使用`/`来进一步过滤匹配.

13.`：h helphelp`包含有关如何使用帮助的一些信息.

 14.用户手册.  这描述了初学者的帮助主题
     友好的方式.  从`：h usr_toc.txt`开始查找内容表（就像你一样）
     可能已经猜到了）.  略过那些帮助找到某些主题，.eg
    你会在中找到一个条目“Digraphs”和“输入特殊字符”
    第24章（所以使用`：h usr_24.txt`转到特定的帮助页面）.

 15.突出显示组始终以`hl- *`开头.  例如`：h hl-WarningMsg`会谈
    关于“WarningMsg”突出显示组.

16.语法高亮将命名为“：syn-topic”，例如`：h：syn-conceal`
    讨论：syn命令的隐藏参数.

17. Quickfix命令通常以“：c”开头，而位置列表命令
    通常以“：l”开头.

 18.`：h BufWinLeave`谈论BufWinLeave autocmd.  还有，`：h
    autocommands-events`讨论所有可能的事件.

19.启动参数总是以“ - ”开头，所以`：h -f`会带你去帮忙
    Vim的“-f”命令开关.

20.编译的额外功能总是以“+”开头，所以`：h + conceal`谈论
    隐瞒支持.

 21.可以直接在帮助中查找错误代码.  `：h E297`带你
     完全符合错误消息的描述.  然而，有时那些
    错误代码没有描述，而是列在Vim命令中
     通常会导致这一点  例如`：h hE128`直接带你到`：function`
    命令.

22.包含语法文件的文档通常位于`：h
     FT  -  *  -  syntax`.  例如`：h ft-c-syntax`谈论C语法文件和
     它提供的选项.  有时，全方位完成的附加部分（`：h
    ft-php-omni`）或filetype插件（`：h ft-tex-plugin`）可用.

此外，还有用户文档的链接（更多地描述了某些命令）
从帮助的角度来看，从用户的角度来看并且不那么详细
 页面如果可用.  所以`：h pattern.txt`提到用户指南主题
`：h 03.9`和`：h usr_27`.

## Getting help online

如果您遇到问题，无法解决或需要一般性指导，请参阅
the [vim_use](https://groups.google.com/forum/#!forum/vim_use) 邮件列表.
另一个很好的资源是使用
[IRC](https://de.wikipedia.org/wiki/Internet_Relay_Chat). The channel `#vim` on
[Freenode](https://freenode.net) 是巨大的，通常充满乐于助人的人.

如果您想报告Vim错误，请使用
[vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮件列表.

## Autocmds in practice

你现在可以触发任何事件：`：doautocmd BufRead`.

### User events

特别是对于插件，创建自己的“用户”事件很有用：

```vim
 功能！  Chibby（）
  “这里发生了很多事情.
  “最后......
  doautocmd用户ChibbyExit
endfunction
```

现在，当Chibby完成运行时，插件的用户可以执行任何操作：

```vim
autocmd用户ChibbyExit调用ChibbyCleanup（）
```

顺便说一句，如果没有“捕获”：autocmd，：doautocmd将输出一个讨厌
 “没有匹配的自动命令”消息.  这就是为什么很多插件都使用`silent
 doautocmd ......`相反.  但这有缺点，你不能简单地使用
`echo：foo“`在：autocmd中，你必须使用`unsilent echo”foo“`而不是..

这就是为什么最好检查是否有接收autocmd而不是
否则会发生事件：

```vim
if exists('#User#ChibbyExit')
  doautocmd用户ChibbyExit
endif
```

帮助：`：h用户`

### Nested autocmds

 默认情况下，autocmds不会嵌套！  如果autocmd执行一个命令，该命令在
转弯通常会触发另一个事件，它不会发生.

假设您每次启动Vim时都想自动打开vimrc：

```vim
autocmd VimEnter *编辑$ MYVIMRC
```

当你现在启动Vim时，它将打开你的vimrc，但你要做的第一件事
通知是没有任何突出显示，虽然通常会有.

问题是你的非嵌套autocmd中的`：edit`不会触发
“BufRead”事件，因此文件类型永远不会被设置为“vim”和
 `$ VIMRUNTIME / syntax / vim.vim`从未采购过.  见`：au BufRead * .vim`.  用这个
instead:

```vim
autocmd VimEnter *嵌套编辑$ MYVIMRC
```

帮助：`：h autocmd-nested`

## Clipboard

Required [features](#what-kind-of-vim-am-i-running)：`+剪贴画`和可选
`+ xterm_clipboard`如果你想在Unix系统上使用&#39;&#39;clipboard&#39;`选项
使用没有GUI支持的Vim.

Help:

```
：h&#39;剪贴板&#39;
：h gui-clipboard
：h gui-selections
```

另见：[括号粘贴（或者为什么我必须设置&#39;粘贴&#39;全部
time?)](#bracketed-paste-or-why-do-i-have-to-set-paste-all-the-time)

### Clipboard usage (Windows, macOS)

Windows附带一个
[clipboard](https://msdn.microsoft.com/en-us/library/windows/desktop/ms649012(v=vs.85).aspx)
和macOS一起来了
[pasteboard](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/PasteboardGuide106/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008100-SW1).

 两者都像大多数用户一样希望它们起作用.  您使用复制选定的文本
`ctrl + c` /`cmd + c`并用`ctrl + v` /`cmd + v`将它们粘贴到另一个应用程序中.

请注意，复制的文本实际上已传输到剪贴板，因此您可以关闭
您在粘贴到另一个应用程序之前复制的应用程序
problems.

每当发生这种情况时，剪贴板寄存器`*`就会被填充
 选择.  从Vim使用``* y`和``* p`从剪贴板中拉出并粘贴
respectively.

如果您甚至不想一直指定`*`寄存器，请将其放入
你的vimrc：

```vim
set clipboard = unnamed
```

通常所有的yank / delete / put操作都填充```寄存器，现在是`*`
register用于相同的操作，因此只需`y`和`p`
enough.

让我再说一遍：使用上面的选项意味着每次猛拉/粘贴，即使是
 只在同一个Vim窗口中使用，会改变剪贴板.  自行决定
如果这是有用的.

如果你甚至懒得键入“y”，你可以将每个视觉选择发送到
剪贴板使用这些设置：

```vim
set clipboard = unnamed，autoselect
设置guioptions + = a
```

Help:

```
：h clipboard-unnamed
：h自动选择
：h&#39;go_a&#39;
```

### Clipboard usage (Linux, BSD, ...)

如果您的操作系统使用 [X](http://www.x.org/wiki) ，事情有点不同.  X
实现[X Window系统
议定书]（http://www.x.org/releases/X11R7.7/doc/xproto/x11protocol.html）
恰好是自1987年以来的主要版本11，因此X也经常被称为X11.

之前，在X10中，[切
buffers](http://www.x.org/releases/X11R7.7/doc/xorg-docs/icccm/icccm.html#Peer_to_Peer_Communication_by_Means_of_Cut_Buffers)
介绍了那种像复制文本一样的_clipboard_工作
 实际上由X持有，所有其他应用程序都可以访问它.  这个
机制仍然存在于X中，但现在大多数软件都不推荐使用它
不再使用它了.

现在，数据通过以下方式在应用程序之间传输
[selections](http://www.x.org/releases/X11R7.7/doc/xorg-docs/icccm/icccm.html#Peer_to_Peer_Communication_by_Means_of_Selections).
从定义的3个_selection atoms_中，实际上只使用了2个：PRIMARY和
CLIPBOARD.

选择工作大致如下：

```
计划A： <ctrl+c>
程序A：断言CLIPBOARD的所有权
方案B： <ctrl+v>
计划B：注意CLIPBOARD的所有权由计划A持有
程序B：从程序A请求数据
程序A：响应请求并将数据发送到程序B.
程序B：从程序A接收数据并将其插入窗口
```

 |  选择|  什么时候用？  |  怎么贴？  |  如何从Vim访问？  |
|-----------|------------|---------------|-------------------------|
 |  主要|  选择文字|  `mid-click`，`shift + insert` |  `*`注册|
 |  剪贴板|  选择文本和`ctrl + c` |  `ctrl + v` |  `+`注册|

**注意**：从不保留选择（不，甚至不包括CLIPBOARD）
 X服务器！  因此，在应用程序中丢失了用`ctrl + c`复制的数据
closes.

使用`“* p`粘贴PRIMARY选择或`”+ y1G`将整个文件拉到
CLIPBOARD选择.

如果您碰巧一直访问两个寄存器中的一个，请考虑使用：

```vim
设置剪贴板^ =未命名“*注册
“ 要么
设置剪贴板^ = unnamedplus“+注册
```

（`^ =`用于前置默认值，`：h：set ^ =`.）

这将使所有yank / delete / put操作使用`*`或`+`而不是
未命名的寄存器```.之后你可以简单地使用`y`或`p`来访问
你选择的X选择.

Help:

```vim
：h clipboard-unnamed
：h clipboard-unnamedplus
```

## Restore cursor position when opening file

打开文件时，光标将位于第1行第1列.
幸运的是，viminfo文件记得 [marks](#marks) .  ```标记包含
你离开的缓冲区中的位置.

```vim
autocmd BufReadPost *
    \ if line（“&#39;\”“）&gt; 1 &amp;&amp; line（”&#39;\“”）&lt;= line（“$”）|
    \执行“normal！g` \”“|
    \ ENDIF
```

读：如果标记“”包含的行号大于第1行但不大于行1
比文件中的最后一行跳转到它.

    ：h viminfo-&#39;
    ：h`引用
    ：hg`

## Temporary files

### Backup files

 在保存文件之前，Vim会创建一个备份文件.  如果写入磁盘是
成功后，备份文件将被删除.

 使用`：set backup`，备份将保持不变.  这意味着，备份文件将
始终具有与原始文件相同的内容_before_最近的保存.
由您来决定这是否有用.

您可以使用`：set nobackup nowritebackup`完全禁用备份，但是您
 现在不应该这样.  `&#39;writebackup&#39;`是一个安全功能
确保你没有丢失原始文件，以防它保存失败，
无论你是否保留备份文件.

如果你经常使用Vim编辑大文件，[和你可能
shouldn't](#editing-huge-files-is-slow), you can exclude those from backups with
`'backupskip'`.

Vim知道创建备份的不同方法：_copying_和_renaming_.

-  **复制**
    1.创建原始文件的完整副本并将其用作备份.
    1.原始文件被清空，然后填充了内容
    Vim buffer.
-  **重命名**
    1.原始文件重命名为备份文件.
    1. Vim缓冲区的内容被写入名为的新文件
    原始文件.

有关所有细节的详细信息，请参阅`：h&#39;backupcopy&#39;.

---

Demo:

```vim
 ：set backup backupskip = backupdir =.  backupext = -backup
：e / tmp / foo
ifoo<esc>
:w
“原始文件被创建，不需要备份文件
obar<esc>
:w
“创建备份文件，更新原始文件
```

```diff
$ diff -u / tmp / foo-backup / tmp / foo
--- / tmp / foo-backup 2017-04-22 15：05：13.000000000 +0200
+++ / tmp / foo 2017-04-22 15：05：25.000000000 +0200
@@ -1 +1,2 @@
 FOO
+bar
```

---

    ：h备份
    ：h写入失败

### Swap files

编辑文件时，未保存的更改将写入交换文件.

 使用`：swapname`获取当前交换文件的名称.  用`：set禁用它们
noswapfile`.

交换文件会更新所有200个字符或未输入任何内容
 4秒  当您停止编辑文件时，它们会被删除.  你可以改变这些
带有`：h&#39;updatecount&#39;`和`：h&#39;updatetime&#39;`的数字.

如果Vim被杀死（例如断电），您将失去自上次以来的所有更改
 该文件已写入磁盘，但不会删除交换文件.  现在，如果你
再次编辑文件，Vim将提供从交换中恢复文件的机会
file.

当两个人尝试编辑同一个文件时，第二个人会收到通知
 交换文件已经存在.  它可以防止人们试图保存
 不同版本的文件.  如果您不想要这种行为，请参阅`：h
'directory'`.

    ：h swap-file
    ：h usr_11

### Undo files

The [undo tree](#undo-tree) 保留在内存中，当Vim退出时将丢失.
 如果你想要它坚持，`：set undofile`.  这将保存撤消文件
`〜/ foo.c`在`〜/ foo.c.un~`中.

    ：h&#39;undofile&#39;
    ：h undo-persistence

### Viminfo files

当备份，交换和撤消文件都是关于文本状态时，viminfo文件是
用于保存退出Vim时可能会丢失的所有其他内容.
viminfo文件保存历史记录（命令行，搜索，输入），寄存器，
标记，缓冲列表，全局变量等

默认情况下，viminfo被写入`〜/ .viminfo`.

    ：h viminfo
    ：h&#39;viminfo&#39;

### Example configuration for temporary files

将所有临时文件放在`〜/ .vim / files`下的自己的目录中：

```vim
“如果需要，创建目录
if！isdirectory（$ HOME.&#39;/.vim / files&#39;）&amp;&amp; exists（&#39;* mkdir&#39;）
  叫mkdir（$ HOME.&#39;/.vim / files&#39;）
endif

“ 备份文件
设置备份
set backupdir = $ HOME / .vim / files / backup /
设置backupext = -vimbackup
设置backupskip =
“交换文件
set directory = $ HOME / .vim / files / swap //
设置updatecount = 100
“撤消文件
设置undofile
set undodir = $ HOME / .vim / files / undo /
“viminfo文件
set viminfo =&#39;100，n $ HOME / .vim / files / info / viminfo
```

## Editing remote files

 Vim附带了netrw插件，可以编辑远程文件.  实际上
通过scp将远程文件传输到本地临时文件，打开缓冲区
使用该文件，并在保存时将更改写回远程文件.

如果您想使用与之相对的本地配置，这非常有用
ssh&#39;ing到服务器并使用管理员希望你使用的任何东西.

```
：e scp：//bram@awesome.site.com/.vimrc
```

如果您已经设置了`〜/ .ssh / config`，则会自动使用它：

```
主持人真棒
    主机名awesome.site.com
    1234号港口
    用户bram
```

假设上面的内容在`〜/ .ssh / config`中，这也适用：

```
：e scp：//awesome/.vimrc
```

类似的可以使用`〜/ .netrc`来完成，参见`：h netrw-netrc`.

请务必阅读`：h netrw-ssh-hack`和`：hg：netrw_ssh_cmd`.

---

另一种可能性是使用 [sshfs](https://wiki.archlinux.org/index.php/Sshfs)
哪个使用 [FUSE](https://en.wikipedia.org/wiki/Filesystem_in_Userspace) 至
将远程文件系统挂载到本地文件系统中.

## Managing plugins

[Pathogen](https://github.com/tpope/vim-pathogen) 是第一个流行的工具
 管理插件.  实际上它只是将_runtimepath_（`：h&#39;rtp&#39;`）调整为
 包括放在某个目录下的所有内容.  你必须克隆
那些插件的存储库你自己.

Real插件管理器公开可帮助您安装和更新插件的命令
来自Vim.

[List of plugin managers](https://github.com/mhinz/vim-galore/blob/master/PLUGINS.md#plugin-managers)

## Block insert

这是一种在相同的文本中插入相同文本的技术
 同时.  看到这个
[demo](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-block_insert.gif).

 用`切换到可视块模式 <c-v>  `.  然后下去几行.
点击“我”或“A”开始输入你的文字.

起初可能有点混乱，但总是为当前输入文本
行和只有在完成当前插入后，相同的文本才会出现
应用于先前视觉选择的所有其他行.

 所以一个简单的例子就是` <c-v>  3jItext <esc>  `.

如果您有不同长度的行并且想要向右追加相同的文本
after the end of each line, do this: `<c-v>3j$Atext<esc>`.

有时您需要在当前结束后将光标放在某处
 线.  默认情况下你不能这样做，但你可以设置`virtualedit`选项：

```vim
设置virtualedit =全部
```

之后`$ 10l`或&#39;90 |`甚至在线路结束后也能正常工作.

 有关详细信息，请参阅`：h blockwise-examples`.  起初看起来可能很复杂，
但很快成为第二天性.

如果你想获得真正的幻想，请看看
[multiple-cursors](https://github.com/terryma/vim-multiple-cursors).

## Running external programs and using filters

免责声明：Vim是单线程的，因此运行外部程序
 前景将阻止其他一切.  当然，你可以使用Vim之一
编程接口，例如Lua，并使用它的线程支持，但在此期间
 然而，Vim进程被阻止的时间.  Neovim通过添加一个来修复
适当的工作API.

（显然Bram正在考虑为Vim增加工作控制权.如果你
有一个非常新的版本，请参阅`：helpgrep startjob`.）

 使用`：！`开始工作.  如果要列出当前工作中的文件
 目录，使用`：！ls`.  像往常一样在shell中使用`|`，例如`：！ls -1 |
 排序|  尾巴-n5`.

 如果没有范围，`：！`的输出将显示在可滚动窗口中.  在
另一方面，如果给出范围，这些线将是
[filtered](https://en.wikipedia.org/wiki/Filter_(software) ）.  这意味着他们
将用管道输送到
[stdin](https://en.wikipedia.org/wiki/Standard_streams#Standard_input_.28stdin.29)
过滤程序和处理后的替换
[stdout](https://en.wikipedia.org/wiki/Standard_streams#Standard_output_.28stdout.29)
 过滤器.  例如，为了将数字预先添加到接下来的5行，请使用：

    ：.，+ 4！nl -ba -w1 -s&#39;&#39;

由于手动添加范围非常繁琐，Vim也提供了一些
 帮助者方便.  与范围一样，您也可以选择行
 视觉模式，然后点击`：`.  还有一个运算符`！`来进行运动.
例如`！ip！sort`将对当前段落的行进行排序.

过滤的一个很好的用例是[Go编程
 语言（https://golang.org）.  缩进是相当自以为是，它甚至
 附带一个名为`gofmt`的过滤器，用于正确缩进Go源代码.  所以
Go的插件经常提供称为`：Fmt`的辅助命令
`：％！gofmt`，所以它们缩进文件中的所有行.

人们经常使用`：r！prog`将prog的输出放在当前行之下，
这对于脚本来说很好，但是当它在运行时，它发现它更容易使用
`!! ls`代替，它取代了当前的行.

    ：h过滤器
    ：h：读！

## Cscope

[Cscope](http://cscope.sourceforge.net/) 做的事情比
[ctags](http://ctags.sourceforge.net/)，但只支持C（和C ++和Java）
在某种程度上）.

标签文件只知道符号的定义位置，而cscope数据库
了解您的数据：

- 这个符号在哪里定义？
- 这个符号在哪里使用？
- 这个全球符号的定义是什么？
- 这个变量在哪里得到它的价值？
- 源文件中的这个功能在哪里？
- 什么函数调用此函数？
- 此功能调用哪些功能？
- “空间不足”的信息来自哪里？
- 目录结构中的源文件在哪里？
- 哪些文件包含此头文件？

### 1. Build the database

在项目的根目录中执行此操作：

```sh
$ cscope -bqR
```

这将创建3个文件：当前工作中的`cscope {，.in，.po} .out`
 目录.  将它们视为您的数据库.

 不幸的是`cscope`默认只分析`*.[c | h | y | l]`文件.  如果你想
要将cscope用于Java项目，请执行以下操作：

```sh
 $ find.  -name“* .java”&gt; cscope.files
$ cscope -bq
```

### 2. Add the database

打开与新构建的数据库的连接：

```vim
：cs添加cscope.out
```

验证是否已建立连接：

```vim
：cs显示
```

（是的，您可以添加多个连接.）

### 3. Query the database

```vim
：cs找到<kind><query>
```

例如`：cs find d foo`将列出由`foo（...）`调用的所有函数.

 |  种类|  说明|
|------|-------------|
 |  s |  ** s ** ymbol：找到对令牌的所有引用
 |  g |  ** g ** lobal：查找令牌的全局定义
 |  c |  ** c ** alls：查找函数的所有调用|
 |  t |  ** t ** ext：查找文本的所有实例
 |  e |  ** e ** grep：egrep搜索单词|
 |  f |  ** f ** ile：打开文件名|
 |  我|  ** i **包括：查找包含文件名|的文件
 |  d |  ** d ** epends：查找此函数调用的函数

我建议一些便利映射，例如：

```vim
 nnoremap <buffer><leader>  cs：cscope find s <c-r>  =扩大（” <cword>  “） <cr><cr>
 nnoremap <buffer><leader>  cg：cscope找到g <c-r>  =扩大（” <cword>  “） <cr><cr>
 nnoremap <buffer><leader>  cc：cscope找到c <c-r>  =扩大（” <cword>  “） <cr><cr>
 nnoremap <buffer><leader>  ct：cscope find t <c-r>  =扩大（” <cword>  “） <cr><cr>
 nnoremap <buffer><leader>  ce：cscope find e <c-r>  =扩大（” <cword>  “） <cr><cr>
 nnoremap <buffer><leader>  cf：cscope find f <c-r>  =扩大（” <cfile>  “） <cr><cr>
 nnoremap <buffer><leader>  ci：cscope找到i ^ <c-r>  =扩大（” <cfile>  “） <cr>  $ <cr>
 nnoremap <buffer><leader>  cd：cscope找到d <c-r>  =扩大（” <cword>  “） <cr><cr>
```

 所以，当`：tag`（或` <c-]>  `）跳转到标签文件`：cstag`的定义
 做同样的事情，但也考虑到连接的cscope数据库.  该
 选项`&#39;cscopetag&#39;`使`：tag`自动像`：cstag`.  这是非常
如果您已经有与标记相关的映射，那么很方便.

帮助：`：h cscope`

## MatchIt

 由于Vim是用C语言编写的，因此许多功能都采用类C语法.  默认情况下，
if your cursor is on `{` or `#endif`, you can use `%` to jump to the
corresponding `}` or `#ifdef` respectively.

Vim捆绑了一个名为matchit.vim的插件，该插件未启用
 默认.  如果/ else / endif构造，它使&#39;％`也循环遍历HTML标记
VimL等并介绍了一些新命令.

#### Installation for Vim 8

```vim
“vimrc
 packadd！  matchit
```

#### Installation for Vim 7 and older

```vim
“vimrc
运行时宏/ matchit.vim
```

由于matchit的文档相当广泛，我建议也做
以下一次：

```vim
：！mkdir -p~ / .vim / doc
：！cp $ VIMRUNTIME / macros / matchit.txt~ / .vim / doc
：helptags~ / .vim / doc
```

#### Small intro

 该插件现在可以使用了.  请参阅`：h matchit-intro`以获得支持
命令和`：h matchit-languages`用于支持的语言.

也就是说，定义自己的匹配对很容易：

```vim
 autocmd FileType python let b：match_words =&#39;\ <if\>  ：\ <elif\>  ：\ <else\>  “
```

之后，您可以使用任何Python文件循环遍历这3个语句
`％`（前进）或`g％`（后退）.

Help:

```
：h matchit-install
：h matchit
：HB：match_words来
```

## True colors

在终端仿真器中使用真彩色意味着能够使用24位RGB
 颜色.  这使得16777216（2 ^ 24）种颜色代替通常的256种颜色.

如上所述 [here](#colorschemes)，colorschemes实际上可以_two-
通过定义终端（xterm）和GUI（gvim）的colorschemes.
在终端模拟器了解真实颜色之前，这是有道理的.

在`：set termguicolors`之后，Vim开始发出只能理解的转义序列
 通过支持真彩色的终端模拟器.  当你的颜色看起来很怪异时，
机会是您的终端模拟器不支持真实颜色或您
colorcheme没有定义GUI颜色.

很多人使用终端多路复用器
[tmux](https://github.com/tmux/tmux/wiki) 它基本上位于之间
 终端模拟器和Vim.  使tmux _forward_真正的颜色逃脱
Vim发出的序列，你必须将以下内容放在用户
`.tmux.conf`:

```
set-option -g default-terminal&#39;tMux-256color&#39;
set-option -ga terminal-overrides&#39;，xterm-256color：Tc&#39;
```

- 对于大多数人来说，第一行应该是相同的，并表示`$ TERM`
  使用_within_ tmux.
- 第二行将tmux特定的`Tc`（真彩色）功能添加到
   `xterm-256color`的其他terminfo条目.  显然这是假设
  用户正在使用tmux的`TERM = xterm-256color` _outside_.

所以，这是启用真彩色的清单：

- 阅读`：h&#39;termguicolors&#39;`.
- 在你的vimrc中放置`set termguicolors`.
  - 确保您的colorscheme具有GUI的颜色定义.  （它应该包含
  带有&#39;guifg`和`guibg`的行.）
- 确保您选择的终端仿真器支持真彩色.
  - 使用tmux？  配置它以添加`Tc`功能.

终端中颜色的流行参考：
https://gist.github.com/XVilka/8346728

## Tips

## Go to other end of selected text

 视觉选择中的`o`和`O`使光标移动到另一端.  试试吧
 逐块选择以查看差异.  这对于快速更改非常有用
所选文本的大小.

```
：h v_o
：h v_O
```

## Saner behavior of n and N

`n`和`N`的方向取决于是使用`/`还是`？`
 分别向前或向后搜索.  这让我很困惑.

如果你想要`n`总是向前搜索和&#39;N`向后搜索，请使用：

```vim
 nnoremap <expr>  n&#39;Nn&#39;[v：searchforward]
 xnoremap <expr>  n&#39;Nn&#39;[v：searchforward]
 onoremap <expr>  n&#39;Nn&#39;[v：searchforward]

 nnoremap <expr>  N&#39;nN&#39;[v：searchforward]
 xnoremap <expr>  N&#39;nN&#39;[v：searchforward]
 onoremap <expr>  N&#39;nN&#39;[v：searchforward]
```

## Saner command-line history

如果你像我一样，你习惯于通过下一个和之前的项目
 ` <c-n>  `和` <c-p>  `分别.  默认情况下，这也适用于
命令行并从历史记录中调用旧的或更新的命令行.

 到现在为止还挺好.  但是` <up>  `和` <down>  `甚至更聪明！  他们回忆起了
 命令行，其开头与当前命令行匹配.  例如`：echo <up>  `
可能会变成`：echo“Vim rock！”`

当然，我不希望你到达箭头键，只需映射它：

```vim
cnoremap <c-n><down>
cnoremap <c-p><up>
```

我每天都会依赖这种行为几次.

## Saner CTRL-L

 默认情况下，` <c-l>  `清除并重绘屏幕（如`：重绘！`）.  该
以下映射做同样的事情，加上去除通过`/`找到的匹配，
`？`等，加上修复语法高亮（有时Vim失去突出显示到期
复杂的突出显示规则），加上强制更新语法突出显示
差异模式：

```vim
 nnoremap <leader>  l：nohlsearch <cr>  ：diffupdate <cr>  ：语法同步fromstart <cr><c-l>
```

## Disable audible and visual bells

```vim
设置noerrorbells
设置novisualbell
设置t_vb =
```

See [Vim Wiki: Disable beeping](http://vim.wikia.com/wiki/Disable_beeping).

## Quickly move current line

有时候我需要一种快速的方法来移动上面或下面的当前行：

```vim
 nnoremap [e： <c-u>  执行&#39;move -1-&#39;.  in：count1 <cr>
 nnoremap] e： <c-u>  执行&#39;move +&#39;.  in：count1 <cr>
```

这些映射也需要计数，因此`2] e`将当前行移动到下面2行.

## Quickly add empty lines

```vim
 nnoremap [ <space>  ： <c-u>  放！  = repeat（nr2char（10），v：count1） <cr>  “[
 nnoremap] <space>  ： <c-u>  put = repeat（nr2char（10），v：count1） <cr>
```

 现在`5 [ <space>  `在当前行上方插入5个空行.

## Quickly edit your macros

 这是一个真正的宝石！  映射采用寄存器（或默认为“*”）并打开
 它在cmdline窗口中.  点击` <cr>  `当你完成编辑设置时
register.

我经常使用它来纠正我在录制宏时所犯的错别字.

```vim
nnoremap <leader>m  :<c-u><c-r><c-r>='let @'. v:register .' = '. string(getreg(v:register))<cr><c-f><left>
```

 像这样使用它 <leader>  m`或``q <leader>  M`.

 注意使用` <c-r><c-r>  `以确保` <c-r>  `插入
 从字面上.  见`：h c_ ^ R ^ R`.

## Quickly jump to header or source file

 这种技术可能适用于许多文件类型.  它设置_file标记_
（请参阅`：h marks`）离开源文件或头文件时，您可以快速跳转
使用`&#39;C`或&#39;&#39;H`返回上次访问的那个（参见`：h&#39;A`）.

```vim
autocmd BufLeave *.{c，cpp}标记C.
autocmd BufLeave * .h标记H.
```

**注意**：信息保存在viminfo文件中，因此请确保`：set
viminfo？`包括`：h viminfo-&#39;`.

## Quickly change font size in GUI

我认为这是从tpope的配置中获取的：

```vim
 命令！  更大：让＆guifont =替换（＆guifont，&#39;\ d \ + $&#39;，&#39;\ = submatch（0）+1&#39;，&#39;&#39;）
 命令！  更小：让＆guifont =替换（＆guifont，&#39;\ d \ + $&#39;，&#39;\ = submatch（0）-1&#39;，&#39;&#39;）
```

## Change cursor style dependent on mode

我喜欢在正常模式下使用块光标，在插入模式下使用i-beam光标，以及
在替换模式下为游标加下划线.

```vim
如果为空（$ TMUX）
   let＆t_SI =“\ <Esc>  ] 50; CursorShape = 1 \×7&quot;
   let＆t_EI =“\ <Esc>  ] 50; CursorShape = 0 \×7&quot;
   let＆t_SR =“\ <Esc>  ] 50; CursorShape = 2 \×7&quot;
else
   let＆t_SI =“\ <Esc>  Ptmux; \ <Esc>  \ <Esc>  ] 50; CursorShape = 1 \ X7 \ <Esc>  \\”
   let＆t_EI =“\ <Esc>  Ptmux; \ <Esc>  \ <Esc>  ] 50; CursorShape = 0 \ X7 \ <Esc>  \\”
   let＆t_SR =“\ <Esc>  Ptmux; \ <Esc>  \ <Esc>  ] 50; CursorShape = 2 \ X7 \ <Esc>  \\”
endif
```

这只是告诉Vim打印一定数量的字符（[转义
序列]（https://en.wikipedia.org/wiki/Escape_sequence））进/出时
 插入模式.  底层终端，或类似的程序
[tmux](https://tmux.github.io) 将坐在Vim和终端之间
处理并评估它.

但是有一个缺点：有许多终端仿真器实现
 并不是所有人都使用相同的序列来做同样的事情.  使用的序列
 以上可能不适用于您的实现.  您的实施可能不会
 甚至支持不同的光标样式.  查看文档.

以上示例适用于iTerm2.

## Don't lose selection when shifting sidewards

如果选择一行或多行，可以使用`&lt;`和`&gt;`来移动它们
 侧向.  不幸的是，你之后会立即失去选择.

您可以使用`gv`重新选择最后一个选项（参见`：h gv`），这样您就可以工作了
就像这样：

```vim
xnoremap &lt;
xnoremap &gt;&gt; gv
```

现在你可以在视觉选择上使用`&gt;&gt;&gt;&gt;&gt;`而不会有任何问题.

**注意**：使用`.`可以实现相同的效果，重复上一次更改.

## Reload a file on saving

Using [autocmds](#autocmds) 你可以做任何事情来保存文件，例如采购
它在dotfile或运行linter的情况下检查语法错误
你的源代码.

```vim
autocmd BufWritePost $ MYVIMRC来源$ MYVIMRC
autocmd BufWritePost~ / .Xdefaults调用系统（&#39;xrdb~ / .Xdefaults&#39;）
```

## Smarter cursorline

我喜欢光标，但我只想在当前窗口中使用它而不是
处于插入模式时：

```vim
autocmd InsertLeave，WinEnter *设置cursorline
autocmd InsertEnter，WinLeave * set nocursorline
```

## Faster keyword completion

 关键字完成（` <c-n>  `/` <c-p>  `）尝试完成列出的内容
 &#39;&#39;完整&#39;选项.  默认情况下，这还包括标签（可以是
 烦人）并扫描所有包含的文件（可能非常慢）.  如果你可以的话
没有这些东西，禁用它们：

```vim
set complete- = i“禁用扫描包含的文件
set complete- = t“禁用搜索标签
```

## Cosmetic changes to colorschemes

无论选择何种颜色方案，始终使用深灰色状态线：

```vim
autocmd ColorScheme * highlight StatusLine ctermbg = darkgray cterm = NONE guibg = darkgray gui = NONE
```

 每次使用`：colorscheme ...`时都会触发.  如果你想要它触发
仅适用于某种颜色方案：

```vim
autocmd ColorScheme沙漠高亮StatusLine ctermbg = darkgray cterm = NONE guibg = darkgray gui = NONE
```

这只触发`：colorscheme desert`.

## Commands

 有用的命令很好知道.  使用`：h： <command name>  `了解更多
关于他们，例如`：h：global`.

## :global and :vglobal

 在所有匹配的行上执行命令.  例如`：global / regexp / print`将使用
`：print`包含“regexp”的所有行.

有趣的事实：你可能都知道好的旧grep，Ken编写的过滤程序
 汤普森.  它有什么作用？  它打印所有与特定规则匹配的行
 表达！  现在猜猜`：global / regexp / print`的缩写形式？  那就对了！
 这是`：g / re / p`.  当他写下grep时，Ken Thompson的灵感来自vi的`：global`.

尽管它的名字，`：global`默认只作用于所有行，但它也需要
 范围.  假设你想在当前行到的所有行上使用`：delete`
包含“foo”的下一个空白行（由正则表达式`^ $`匹配）：

```vim
:,/^$/g/foo/d
```

要在与给定模式匹配的所有行上执行命令，请使用
`：global！`或其别名`：vglobal`（想想_inVerse_）.

## :normal and :execute

这些命令通常用在Vim脚本中.

 使用`：normal`，您可以从命令行执行普通模式映射.  例如
 `：正常！  4j`将使光标向下移动4行（不使用任何自定义
由于“！”而映射为“j”.

注意`：normal`也需要一个 [range](#ranges) ，所以`：％规范！  Iabc`会
将“abc”添加到每一行.

 使用`：execute`，您可以将命令与表达式混合使用.  假设您编辑C
源文件，并希望切换到其头文件：

```vim
 ：执行&#39;edit&#39;fnamemodify（expand（&#39;％&#39;），&#39;：r&#39;）.  &#39;.H&#39;
```

 这两个命令通常一起使用.  假设你想让光标移动
向下“n”行：

```vim
：设n = 4
 ：执行&#39;正常！&#39;  n.  &#39;J&#39;
```

## :redir and execute()

 许多命令打印消息，`：redir`允许重定向该输出.  您
可以重定向到文件， [registers](#registers) 或变量.

```vim
：redir =&gt; var
:reg
：redir END
：echo var
：“为了好玩，我们也把它放到当前的缓冲区.
：put = var
```

在Vim 8中有一个更短的方式：

```vim
：put = execute（&#39;reg&#39;）
```

Help:

```
：h：redir
：h execute（）
```

## Debugging

## General tips

如果您遇到奇怪的行为，请尝试像这样重现：

```
vim -u NONE -N
```

这将启动Vim而不使用vimrc（因此默认设置）并且不兼容
 模式（使其使用Vim默认值而不是vi默认值）.  （见`：h
--noplugin`用于开始时加载的其他组合.）

 如果你现在仍然可以重现它，它很可能是Vim本身的一个错误！  报告
它到了 [vim_dev](https://groups.google.com/forum/#!forum/vim_dev) 邮件
 名单.  大多数情况下，此时此问题将无法解决，您将拥有
进一步调查.

 插件通常会引入新的/更改/错误的行为.  例如，如果它发生
保存，检查`：verb au BufWritePost`以获取可能的罪魁祸首列表.

如果您正在使用插件管理器，请将其注释掉，直至找到罪魁祸首.

 问题仍未解决？  如果它不是插件，那一定是你的另一个
设置，也许你的选项或autocmds等.

 是时候使用二进制搜索了.  反复将搜索空间分成两部分直到你
 找到罪魁祸首.  由于二元分裂的性质，它不会需要很多
steps.

在实践中，它的工作原理如下：将`：finish`命令放在你的中间
 的vimrc.  Vim会跳过它之后的所有内容.  如果它仍然发生，问题出在
 活跃的上半部分.  将`：finish`移到_that_ half的中间.
 否则，问题在于非活动的下半部分.  将`：finish`移动到
 一半的中间.  等等.

## Verbosity

观察Vim目前正在做的另一个有用的方法是增加
 冗长程度.  目前Vim支持9个不同级别.  见`：h&#39;verbose&#39;`
完整列表.

```vim
：e / tmp / foo
：set verbose = 2
:w
：set verbose = 0
```

这将显示所有获取的文件，例如撤消文件或各种文件
插件，用于保存.

如果您只想增加单个命令的详细程度，那么也是如此
 `：verbose`，它只是放在任何其他命令之前.  需要
详细级别为count，默认为1：

```vim
：动词设置详细
“详细= 1
：10verb设置详细
“详细= 10
```

它经常与其默认详细级别1一起使用以显示选项的位置
最后设定：

```vim
：动词设置ai？
“最后设置来自〜/ .vim / vimrc
```

 当然，详细程度越高，输出就越大.  但
不用担心，你可以简单地将输出重定向到一个文件：

```vim
 ：set verbosefile = / tmp / foo |  15verbose echo“foo”|  vsplit / tmp / foo
```

 您还可以使用`-V`选项在开始时启用详细程度.  它
默认为详细级别10.例如`vim -V5`.

## Profiling startup time

 Vim启动感觉慢？  时间紧缩一些数字：

```
vim --startuptime /tmp/startup.log + q &amp;&amp; vim /tmp/startup.log
```

 第一列是最重要的，因为它显示了经过的绝对时间.  如果
两条线之间的时间有很大的跳跃，第二条线是非常
大文件或有错误的VimL代码的文件，值得研究.

## Profiling at runtime

Required [feature](#what-kind-of-vim-am-i-running)：`+ profile`

Vim提供了在运行时进行性能分析的内置功能，是一种很好的方法
在您的环境中找到慢代码.

`：profile`命令需要一堆子命令来指定内容
profile.

如果您想要分析_everything_，请执行以下操作：

```
：profile start /tmp/profile.log
：个人档案*
：profile func *
<do something in Vim>
<quit Vim>
```

Vim keeps the profiling information in memory and only writes it out to the
 退出时的日志文件.  （Neovim使用`：profile dump`修复了此问题）.

 看看`/ tmp / profile.log`.  分析期间执行的所有代码
 将会显示.  每一行，它执行的频率和花费的时间.

大部分时间都是用户不熟悉的插件代码，但是如果
 你正在调查某个问题，跳到日志的底部.  这是
两个不同的部分`功能在总时间内排序`和&#39;功能已分类
 自我时间`值得金.  如果确定的话，你可以快速浏览一下
功能太长了.

## Debugging Vim scripts

如果之前曾使用过命令行调试器，那么`：debug`很快就会感觉到
familiar.

只需将`：debug`添加到任何其他命令，您将进入调试模式.
也就是说，执行将在即将执行的第一行停止
将显示一行.

有关6个可用的调试器命令，请参阅`：h&gt; cont`及以下内容，请注意，
比如在gdb和类似的调试器中，你也可以使用它们的简短形式：`c`，`q`，
`n`，`s`，`i`和`f`.

除此之外，您可以自由使用任何Vim命令，例如`：echo myvar`，
它在代码中的当前位置的上下文中执行.

你基本上得到了一个
[REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) 通过
只需使用`：debug 1`.

如果你必须单步执行每一行，那将是一种痛苦
 当然我们也可以定义断点.  （断点称为断点，
因为当它们被击中时执行停止，因此你可以简单地跳过代码
你不感兴趣.）见`：h：breakadd`，`：h：breakdel`和`：h
：breaklist`了解更多详情.

假设您想知道每次保存文件时运行的代码：

```vim
：在BufWritePost
“表示BufWritePost
"     *         call sy#start()
：breakadd func * start
:w
" Breakpoint in "sy#start" line 1
“进入调试模式.输入”cont“继续.
" function sy#start
“第1行：如果g：signify_locked
>s
" function sy#start
“第3行：endif
>
" function sy#start
“第5行：让sy_path =解析（展开（&#39;％：p&#39;））
>q
：breakdel *
```

 如你所见，使用` <cr>  `将重复上一个调试器命令`s` in
这个案例.

`：debug`可以和.一起使用 [verbose](#verbosity) 选项.

## Debugging syntax files

语法文件通常是由于错误和/或复杂而导致速度降低的原因
在编译中，Vim提供了超级有用的`：syntime`命令.

```vim
：罪是
 “打了 <c-l>  几次重绘窗口，导致语法规则再次应用
：syntime off
：syntime报告
```

 输出包含重要指标.  例如，你可以看到哪个正则表达式
应该进行优化，或者始终使用哪些正则表达式，但从不使用
甚至比赛.

见`：h：syntime`.

## Miscellaneous

## Additional resources

 |  资源|  说明|
|----------|-------------|
| [Seven habits of effective text editing](http://www.moolenaar.net/habits.html)  |  作者：Bim Moolenaar，Vim的作者.  |
| [Seven habits of effective text editing 2.0 (PDF)](http://www.moolenaar.net/habits_2007.pdf)  |  往上看.  |
| [IBM DeveloperWorks: Scripting the Vim editor](http://www.ibm.com/developerworks/views/linux/libraryview.jsp?sort_order=asc&sort_by=Title&search_by=scripting+the+vim+editor)  |  关于Vim脚本的五部分系列.  |
| [Learn Vimscript the Hard Way](http://learnvimscriptthehardway.stevelosh.com)  |  从头开发Vim插件.  |
| [Practical Vim (2nd Edition)](http://www.amazon.com/Practical-Vim-Edit-Speed-Thought/dp/1680501275/)  |  提供关于Vim的最佳书籍.  |
| [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)  |  常见的误解解释了.  |
| [Your problem with Vim is that you don't grok vi](http://stackoverflow.com/a/1220118)  |  简洁，翔实，正确.  真正的宝石.  |

#### Screencasts

- [vimcasts.org](http://vimcasts.org/episodes/archive)
- [By wincent](https://www.youtube.com/channel/UCXPHFM88IlFn68OmLwtPmZA)
- [By Derek Wyatt](http://derekwyatt.org/vim/tutorials/index.html)

## Vim distributions

Vim发行版是Vim的自定义设置和插件的捆绑包.

更高级的用户知道如何配置他们的编辑器，所以分发
 主要针对初学者.  如果你考虑一下，那就完全了
矛盾的是：通过添加更多要学习的东西来简化它？

我知道很多人不想花几个小时来定制一个
编辑器（实际上，当你最终获得时，你永远不会停止自定义你的vimrc
迷上了，但最终你只有在花时间去Vim时才能提高效率
正确学习.

在我之后重复：“程序员应该知道他们的工具.”

无论如何，如果你知道自己在做什么，你可能会从中汲取灵感
看几个发行版：

- [cream](http://cream.sourceforge.net)
- [janus](https://github.com/carlhuda/janus.git)
- [spacevim](https://github.com/SpaceVim/SpaceVim)
- [spf13](https://github.com/spf13/spf13-vim)

## Standard plugins

许多人对Vim带有一些标准这一事实感到惊讶
 插件.  有些是默认加载的（`：e $ VIMRUNTIME / plugin`）而有些则没有
 （`：e $ VIMRUNTIME / pack / dist / opt`）.  阅读`：h pack-add`如何获取
latter.

但是，默认情况下加载的大多数插件永远不会被使用.
 根据需要禁用它们.  它们仍将显示为来源
（`：scriptnames`），但只有在Vim保释之前实际读取了第一行
 出.  不会处理其他代码（映射，命令，逻辑）.

 |  插件|  使用.. |禁用它  帮助|
|------------|-------------------------------------|------|
 |  2html |  `let g：loaded_2html_plugin = 1` |  `：h 2html` |
 |  getscript |  `let g：loaded_getscriptPlugin = 1` |  `：h pi_getscript` |
 |  gzip |  `let g：loaded_gzip = 1` |  `：h pi_gzip` |
 |  logipat |  `let g：loaded_logipat = 1` |  `：h pi_logipat` |
 |  匹配对|  `let g：loaded_match pairs = 1` |  `：h pi_paren` |
 |  netrw |  `let g：loaded_netrwPlugin = 1` |  `：h pi_netrw` |
 |  rrhelper |  `let g：loaded_rrhelper = 1` |  `：e $ VIMRUNTIME / plugin / rrhelper.vim` |
 |  拼写文件|  `let g：loaded_spellfile_plugin = 1` |  `：h spellfile.vim` |
 |  焦油|  `let g：loaded_tarPlugin = 1` |  `：h pi_tar` |
 |  vimball |  `let g：loaded_vimballPlugin = 1` |  `：h pi_vimball` |
 |  zip |  `let g：loaded_zipPlugin = 1` |  `：h pi_zip` |

## Map CapsLock to Control

CapsLock属于键盘上最无用的键，但它更容易
达到比控制键，因为它位于你的[家
row](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-homerow.png).
将CapsLock映射到Control是一种防止或至少减少的好方法
[RSI](https://de.wikipedia.org/wiki/Repetitive-Strain-Injury-Syndrom) 如果你
节目很多.

注意：当你习惯它时，你就不能没有它了.

**macOS**:

 `系统偏好设置 - &gt;键盘 - &gt;键盘选项卡 - &gt;修改键.  更改
“CapsLock”到“控制”.

**Linux**:

要更改X中的键，请将其放在`〜/ .xmodmap`中：

    删除Lock = Caps_Lock
    keysym Caps_Lock = Control_L
    添加Control = Control_L

然后通过`$ xmodmap~ / .xmodmap`来源它.

另一种选择是使用 [caps2esc](https://github.com/oblitum/caps2esc) 要么
[xcape](https://github.com/alols/xcape).

**Windows**:

请参阅[superuser.com：在Windows中将Caps-Lock映射到控件
8.1](http://superuser.com/questions/764782/map-caps-lock-to-control-in-windows-8-1).

## Generating HTML from buffer

使用来自2html [标准的`：TOhtml`从任何缓冲区生成HTML
plugin](#standard-plugins). The output can be used for printing or easy web
publishing.

 该命令创建一个附加了“.html”的同名新缓冲区.  该
 颜色与Vim中看到的颜色相同.  他们依赖于
[colorscheme](#colorschemes).

该插件知道几个微调输出的选项，例如用于设置
编码和字体.

见`：h：TOhtml`.

## Easter eggs

 |  命令|  消息|
|-----------|---------|
 |  `：倪！`|  “你要求灌木丛吗？”|
 |  `：h&#39;sm&#39;` |  `注意：短形式的使用被评为PG.|
 |  `：h 42` |  “生命，宇宙和一切的意义是什么？  道格拉斯亚当斯，唯一一个知道这个问题真正意义的人现在已经死了，不幸的是.  所以现在你可能想知道死亡的含义是什么......`|
 |  `：h UserGettingBored` |  `当用户按下相同的键42次时.  开玩笑！  :-)`|
| `:h bar` | `Ceci n'est pas une pipe.` |
 |  `：h holy-grail` |  “你找到了，亚瑟！”|
 |  `：h map-modes` |  `：nunmap也可以在修道院外使用.|
 |  `：帮助！`|  `E478：不要惊慌！`（故障？当在帮助缓冲区（`buftype = help`）中使用时，这就像`：h help.txt`一样.）|
 |  `：smile` |  自己尝试一下.  ;-)在7.4.1005中添加.  |

## Why hjkl for navigation?

When [Bill Joy](https://en.wikipedia.org/wiki/Bill_Joy) 创建
[vi](https://en.wikipedia.org/wiki/Vi)作为Vim的前身，他是在一个人的基础上做到
[ADM-3A](https://en.wikipedia.org/wiki/ADM-3A) 没有额外的光标按钮
但是用过，你可能已经猜到了，而不是hjkl.

键盘布局： [click](https://raw.githubusercontent.com/mhinz/vim-galore/master/static/images/content-adm-3a-layout.jpg)

这也说明了为什么`~`用于表示Unix系统上的主目录.

## Common problems

## Editing small files is slow

有两件事可以对性能产生巨大影响：

 1.复杂的**正则表达式**.  特别是Ruby语法文件造成
    人们过去有所减缓.  （另见 [Debugging syntax files](#debugging-syntax-files).)
 2. **屏幕重绘**.  某些功能强制所有行重绘.

| Typical culprit | Why? | Solution? |
|-----------------|------|-----------|
 |  `：设置cursorlines` |  导致所有行重绘.  |  `：设置nocursorline` |
 |  `：set cursorcolumn` |  导致所有行重绘.  |  `：设置nocursorcolumn` |
 |  `：设置relativenumber` |  导致所有行重绘.  |  `：设置norelativenumber` |
 |  `：设置foldmethod = syntax` |  如果语法文件已经很慢，这会使情况变得更糟.  |  `：set foldmethod = manual`，`：set foldmethod = marker`或 [FastFold](https://github.com/Konfekt/FastFold) |
 |  `：设置synmaxcol = 3000` |  由于内部表示，Vim一般存在长线问题.  列到列3000之前的列.|  `：设置synmaxcol = 200` |
 |  matchparen.vim |  默认加载.  使用正则表达式查找附带的括号.  |  禁用插件：`：h matchparen` |

**注意**：如果您遇到实际性能，则只需执行此操作
 缺点.  在大多数情况下，使用上面提到的东西绝对没问题.

## Editing huge files is slow

 大文件最大的问题是，Vim一次读取整个文件.  这个
由于内部如何表示缓冲区而完成.
([Discussion on vim_dev@](https://groups.google.com/forum/#!topic/vim_dev/oY3i8rqYGD4/discussion))

 如果你只想阅读，`tail hugefile |  vim -`是一个很好的解决方法.

如果你现在可以没有语法，设置和插件：

```
$ vim -u NONE -N
```

这应该使导航速度快得多，特别是因为没有昂贵
 使用用于语法突出显示的正则表达式.  你也应该告诉Vim
不要使用swapfiles和viminfo文件来避免写入时的长时间延迟：

```
$ vim -n -u NONE -i NONE -N
```

简而言之，在打算真正写时，尽量避免使用Vim
 巨大的文件.  ：\

## Bracketed paste (or why do I have to set 'paste' all the time?)

括号粘贴模式允许终端仿真器区分键入的文本
和粘贴的文字.

你有没有试过将代码粘贴到Vim中，然后一切都显得混乱
up?

只有通过`cmd + v`，`shift-insert`，`middle-click`等粘贴时才会发生这种情况.
 因为那时你只是在终端模拟器上抛出文本.  Vim没有
知道你刚刚粘贴了文本，它认为你是一个非常快速的打字员.
因此，它试图缩进行并失败.

显然这不是问题，如果你使用Vim的寄存器粘贴，例如`“+ p`，
因为那时Vim知道你实际上正在粘贴.

 要解决这个问题，你必须`：设置粘贴`，以便按原样粘贴.  见`：h
&#39;paste&#39;`和`：h&#39;pastetoggle&#39;`.

如果你厌倦了一直打开“粘贴”，请看看这个好
为你做的插件：
[bracketed-paste](https://github.com/ConradIrwin/vim-bracketed-paste).

与插件相同的其他读物：
[here](http://cirw.in/blog/bracketed-paste).

** Neovim **：Neovim试图让所有这些更加无缝和集合
如果终端仿真器支持，则自动括起粘贴模式.

## Delays when using escape key in terminal

如果你住在命令行中，你可能会使用所谓的_terminal
emulator_喜欢xterm，gnome-terminal，iTerm2等（与真实的相反）
[terminal](https://en.wikipedia.org/wiki/Computer_terminal)).

像他们的祖先一样，终端模拟器使用[逃避
序列]（https://en.wikipedia.org/wiki/Escape_sequence）（或_control
sequences_）控制移动光标，改变文本颜色等内容.
它们只是以转义字符开头的ASCII字符串
（显示在 [caret notation](https://en.wikipedia.org/wiki/Caret_notation) 如
 `^ [`）.  当这样的字符串到达​​时，终端仿真器会查找
随之而来的行动 [terminfo](https://en.wikipedia.org/wiki/Terminfo)
database.

 为了使问题更清楚，我将首先解释映射超时.  他们总是
当映射之间存在歧义时发生：

```vim
：nnoremap，a：echo&#39;foo&#39; <cr>
：nnoremap，ab：echo&#39;bar&#39; <cr>
```

两个映射都按预期工作，但是当键入`，a`时，将会有1的延迟
第二，因为Vim等待用户是否键入另一个`b`.

转义序列带来同样的问题：

  - ` <esc>  `用于返回正常模式或退出操作.
- 使用转义序列对光标键进行编码.
-  Vim期望<kbd>Alt</kbd> （也称为_Meta key_）发送一个合适的8位
  高位设置编码，但许多终端仿真器不支持它
  （或者默认情况下不启用它）并发送转义序列.

 您可以像这样测试上面的内容：`vim -u NONE -N`并输入`i <c-v><left>  `和
你会看到插入的序列以`^ [`开头，表示转义
character.

简而言之，Vim难以区分打字
 ` <esc>  `字符和适当的转义序列.

默认情况下，Vim使用`：set timeout timeoutlen = 1000`，因此它会延迟模糊
 映射_和_密钥代码1秒.  这是映射的合理值，但是
你可以自己定义密钥代码超时，这是最常见
整个问题的解决方法：

```vim
设置超时“用于映射
设置timeoutlen = 1000“默认值
设置ttimeout“用于密钥代码
设置ttimeoutlen = 10“不明显的小值
```

在`：h ttimeout`下，你会找到一张显示两者之间关系的小表
这些选择.

如果您在Vim和终端仿真器之间使用tmux，也请将其放入
你的`〜/ .tmux.conf`：

```tmux
set -sg escape-time 0
```

## Function search undo

- 命令中的搜索模式（`/`，`：substitute`，...）改变了“最后使用的”
  搜索模式“.（它保存在`/`寄存器中;用`：echo @ /`打印）.
  - 可以使用`.`重做简单的文本更改.  （它保存在`.`寄存器中;
  用`：echo @ .`打印它.

 如果你从一个函数中执行它们，那么这两件事都不是这样的！  因此你
无法轻松突出显示函数中的单词或重做所做的文本更改
it.

帮助：`：h function-search-undo`

## Technical quirks

## Newline used for NUL

文件中的NUL字符（`\ 0`）在内存中存储为换行符（`\ n`）
在缓冲区中显示为“^ @”.

有关更多信息，请参阅`man 7 ascii`和`：h NL-used-for-Nul`.

## Terminology

## Vim script? Vimscript? VimL?

`Vim script`, `Vimscript`, and `VimL` all refer to the same thing: The
 用于编写Vim脚本的编程语言.  即使
[8.0.360](https://github.com/vim/vim/commit/b544f3c81f1e6a50322855681ac266ffaa8e313c)
将所有对“VimL”的引用改为“Vim脚本”，现在可以考虑了
官方称，“VimL”仍然遍布互联网.

无论你使用哪个术语，每个人都会理解它.
