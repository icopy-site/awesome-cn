<div class="github-widget" data-repo="Codepoints/awesome-codepoints"></div>
## Awesome Code Points [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是一个精选的 Unicode 字符列表，具有有趣的（和
可能不广为人知）功能或在其他方面很棒.



## Standalone Code Points

* Unicode 块的代码点 [Box
    绘图](https://codepoints.net/box_drawing)（U+2500 到 U+257F）和[块
    元素](https://codepoints.net/block_elements) (U+2580 to U+259F) 封面
    大多数等宽命令行可视化需求.

        ╭───────╮
        │Unicode│
        │rules! │
        ╰┬─────┬╯
* [U+2E2E](https://codepoints.net/U+2E2E) 反问号——“反讽
    mark” to express irony/sarcasm. A useful character&#x2E2E;
* [U+D800](https://codepoints.net/U+D800) 到
    [U+DFFF](https://codepoints.net/U+DFFF)  - 代理代码点. 他们是
    仅保留以缓解 [UTF-16
    编码] (https://en.wikipedia.org/wiki/UTF-16).
* [U+FEFF](https://codepoints.net/U+FEFF) 零宽度不间断空间 - 它的名字
    建议，它可以像 U+2060 WORD JOINER 一样使用. 而事实上
    后者被引入以继承其语义. 这是因为 U+FEFF 有
    成为一个特殊的信标，称为 [byte order
    标记] (https://en.wikipedia.org/wiki/Byte_order_mark)，它被放置在
    一些 UTF-8 文件的开头. 在符合要求的软件中（包括许多
    文本编辑器）这个字符从文件的开头被删除并且
    作为元数据处理. 在不合规的软件中（如 PHP 解释器）
    这会导致各种有趣的行为.
* [U+FFFD](https://codepoints.net/U+FFFD) 替换字符 - 当
    无法显示字符（例如，解码错误的 UTF-8 序列），
    这个代码点进入了漏洞.
* [U+1D455](https://codepoints.net/U+1D455) 不见了. 这将是一个斜体
    小“h”. 它没有编码，因为它与普朗克相同
    常量 ℎ ([U+210E](https://codepoints.net/U+210E)).
* [U+FF03](https://codepoints.net/U+FF03) 全角数字符号 - 它是 
     “日本标签”`＃`. 像 Twitter 这样的网站接受它等同于 
    regular `#` ([U+0023](https://codepoints.net/U+0023)).

## Code Points that Affect Others

* [U+202D](https://codepoints.net/U+202D) 和
    [U+202E](https://codepoints.net/U+202E) - 改变文字方向.
    相关 XKCD：

    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
* [U+FE0E](https://codepoints.net/U+FE0E) VARIATION SELECTOR-15 - 力
    黑色-_&amp;_-白色表情符号. 如果这个代码点跟在一个表情符号之后，一个明确
    请求表情符号的单色渲染（如果客户端支持）.
* [U+FE0F](https://codepoints.net/U+FE0F) VARIATION SELECTOR-16 - 力
    多彩的表情符号. 如果这个代码点跟在表情符号之后，一个明确的彩色
    请求呈现表情符号（如果客户端支持）.
*变音符号和组合标记：有[主机
    字符](https://codepoints.net/search?gc=Mn)，添加
    对之前的人物. 这些被称为组合标记. 统一码
    提供了 [handy FAQ](http://unicode.org/faq/char_combmark.html) 在
    细节，但简而言之：如果你在一个字符后添加一个，它被放置
    在前一个之上. 所以，`a + ̊ = å`. 这_可能_导致各种
    有趣的问题，因为对于某些组合有预先组合
    人物. 我们这里的小`å`也可以编码为U+00E5. 你可能
    请注意，虽然它有一个字符的长度，但 `a` 的组合
    组合环的长度为两个字符.

    当然，也可以用这些角色做一些有趣的事情，比如
    [this answer](http://stackoverflow.com/a/1732454/113195) 在 StackOverflow 上.
* 这 [Regional Indicator Symbols](https://codepoints.net/U+1F1E6..U+1F1FF)
     U+1F1E6 到 U+1F1FF 类似于 26 个拉丁字符. 他们习惯于
    创建国旗表情符号. 由于 Unicode 联盟不想继续
    董事会与国际政治，旗帜的解决方案是结合
    这 26 个字符对应一个国家/地区的相应 ISO 代码. 例子：

    国家 |  ISO 代码 | 代码点 | 表情符号（如果支持）
    --------|----------|-------------------|---------------------
    USA     | US       | U+1F1FA + U+1F1F8 | &#x1F1FA;&#x1F1F8;
    Germany | DE       | U+1F1E9 + U+1F1EA | &#x1F1E9;&#x1F1EA;
    China   | CN       | U+1F1E8 + U+1F1F3 | &#x1F1E8;&#x1F1F3;
*表情符号的肤色：有五个代码点，控制肤色
    的表情符号， [U+1F3FB to U+1F3FF](https://codepoints.net/U+1F3FB..U+1F3FF).
    它们被称为“Emoji Modifier Fitzpatrick Type”1 到 6，其中 1 最浅
     6 最暗. 如果其中一个字符跟随表情符号，则该表情符号
    is meant to be rendered in the appropriate skin color of [the Fitzpatrick
    规模] (https://en.wikipedia.org/wiki/Fitzpatrick_scale). 如果不是这样
    添加修饰剂，肤色应该不自然，e.  g.，亮黄色.
    有趣的事实：由于 Fitzpatrick 修饰符是普通代码点，表情符号
    具有这种肤色的人的长度为 2，这是 Twitter 用户最先注意到的.
    这是一个比较图表[直接来自
    specification](http://www.unicode.org/reports/tr51/tr51-2.html#Diversity):

    代码 | 名称 | 样品
    --------|-------------------------------------|---------
     U+1F3FB | 表情符号修饰符 FITZPATRICK TYPE-1-2 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2.png" alt="" height="20" width="auto"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2-bw.png" alt="" height="20" width="auto">
     U+1F3FC | 表情符号修饰符 FITZPATRICK TYPE-3 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3-bw.png" alt="" height="20" width="auto">
     U+1F3FD | 表情符号修改器 FITZPATRICK TYPE-4 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4-bw.png" alt="" height="20" width="auto">
     U+1F3FE | 表情符号修改器 FITZPATRICK TYPE-5 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5-bw.png" alt="" height="20" width="auto">
     U+1F3FF | 表情符号修饰符 FITZPATRICK TYPE-6 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6-bw.png" alt="" height="20" width="auto">

### Breaking and Gluing other characters

* [U+00A0](https://codepoints.net/U+00A0) NO-BREAK SPACE - 强制相邻
    字符粘在一起. 在 HTML 中称为 ` .
* [U+00AD](https://codepoints.net/U+00AD) 软连字符 -（在 HTML 中：``）
    像零宽度空间，但如果（且仅当）发生中断时显示连字符.
* [U+200B](https://codepoints.net/U+200B) 零宽度空间 - 与
    U+00A0：不留空格，但允许断字.
* [U+200D](https://codepoints.net/U+200D) 零宽度连接器 - 强制相邻
    要连接在一起的字符（例如，阿拉伯字符或支持
    表情符号）. 苹果用它来组成一些像不同家庭的表情符号.
* [U+2060](https://codepoints.net/U+2060) WORD JOINER - 与
     U+00A0，但完全不可见. 适合在 Twitter 上写“@font-face”.

为了更好地比较哪个代码点具有哪种效果，请参阅此
table:

 |  U+00A0 |  U+00AD |  U+200B |  U+200D |  U+2060
---------------|--------|--------|--------|--------|--------
创造空间 |  ✓ |  ✗ |  ✗ |  ✗ |  ✗
允许打破 |  ✗ |  ✓ |  ✓ |  ✗ |  ✗
可能的变化|  ✗ |  ✓ |  ✗ |  ✓ |  ✗

Smashing Magazine 精选[综合
文章](http://www.smashingmagazine.com/2015/10/space-yourself/) 上
不同类型的空格.

## Record Holders and Extremes

* [U+0000](https://codepoints.net/U+0000) &lt;control&gt; - 第一个代码点.
* [U+10FFFF](https://codepoints.net/U+10FFFF) (_non-character_) - 最后一个代码
    观点. 除了 U+10FFFE 之外的整个平面，代码点
    在 0x10000-0x10FFFD 范围内，是私人使用的字符，保证
    永远不会被未来的 Unicode 标准填充.
* [U+1F402](https://codepoints.net/U+1F402) OX - 最短的名字.
* U+1FBA8 方框图浅色对角线从上中心到中左，从中右到下中心
    和
    U+1FBA9 箱形图浅色对角线上中心到中右和中左到下中心 - 最长的名称：88
    每个字符.
* [U+FDFA](https://codepoints.net/U+FDFA) 阿拉伯连字 SALLAHOU ALAYHE
    WASALLAM - 最长的分解形式：18 个字符.
* [U+5146](https://codepoints.net/U+5146) 和
    [U+16B61](https://codepoints.net/U+16B61) - 代表的代码点
    最高的“个位数”数字. 在这两种情况下都是 1,000,000,000,000，a
    兆.
* [U+0F33](https://codepoints.net/U+0F33) 西藏数字半个零 - 代码点
    代表_lowest_“个位数”数字，同时
    只有负数，-½.
* 大多数无用代码点的奖杯是
    [U+0080](https://codepoints.net/U+0080),
    [U+0081](https://codepoints.net/U+0081) 和
    [U+0099](https://codepoints.net/U+0099) . 这些所谓的C1控制
    字符或多或少是未指定的. 他们进入了 Unicode，因为
    它们出现在后来成为 ISO 的第一个版本中
     10646，Unicode 的 ISO 标准化版本. 他们[注定要成为一部分
    升级到 ISO
    2022](http://unicode.org/mail-arch/unicode-ml/y2015-m10/0050.html)，即
    从来没有出现过.
* 在这方面紧随其后的是 CJK 统一表意文字
    [妛](https://codepoints.net/U+599B),
    [挧](https://codepoints.net/U+6327),
    [暃](https://codepoints.net/U+6683),
    [椦](https://codepoints.net/U+6926),
    [槞](https://codepoints.net/U+69DE),
    [蟐](https://codepoints.net/U+87D0),
    [袮](https://codepoints.net/U+88AE),
    [閠](https://codepoints.net/U+95A0),
    [駲](https://codepoints.net/U+99F2),
    [墸](https://codepoints.net/U+58B8),
    [壥](https://codepoints.net/U+58E5)， 和
    [彁](https://codepoints.net/U+5F41) . 这些所谓 [“ghost characters”](https://www.dampfkraft.com/ghost-characters.html)
    通过日本的 JIS 标准来到 Unicode，并在其中添加了它们，因为
    在编译 JIS 时，它们被其他标志误读或误解
    来自原始印刷文本来源.
* [U+006F](https://codepoints.net/U+006F) 拉丁文小写字母 O - 排在首位
    形状容易混淆的字符. 在所有可能的映射中
    [令人困惑的清单
    characters](http://www.unicode.org/reports/tr39/#Data_Files), the small “o”
    以多达 73 个看起来相似的字形条目开头，然后是
    [U+006C](https://codepoints.net/U+006C) 带 70 的拉丁文小写字母 L
    条目.
* [U+1F4C0](https://codepoints.net/U+1F4C0) DVD - 只有代码点名称没有任何元音 ([source](https://twitter.com/ken_lunde/status/960188623390846976))

## For Funsies

* [U+1680](https://codepoints.net/U+1680) OGHAM SPACE MARK——一个看起来像的空间
    像破折号. 伟大的让程序员接近疯狂：`1 + 2 === 3`.
* [U+037E](https://codepoints.net/U+037E) 希腊问号 - 一个看起来像
    分号. 这也是惹恼开发人员的一种有趣方式.
* [U+1DD2](https://codepoints.net/U+1DD2) 结合我们上面 - 这是最
    浪漫的代码点.
* [U+F8FF](https://codepoints.net/U+F8FF) PRIVATE USE CODEPOINT - 这个私有
    使用代码点在许多 Apple 设备上呈现为 Apple 徽标.
* [U+1F574](https://codepoints.net/U+1F574) 穿着西装的男人漂浮着 -
    一个相当奇怪的字符，只是因为它
    以 Webdings 字体出现（出于向后兼容性的原因）.
* [U+1F596](https://codepoints.net/U+1F596) 举手，部分介于两者之间
    中指和无名指 - 瓦肯式敬礼. 健康长寿·繁荣昌盛！
    &#x1F596;
* [U+1F918](https://codepoints.net/U+1F918) 号角标志 - 继续前进！
    &#x1F918;
* [U+2800](https://codepoints.net/U+2800)  BRAILLE PATTERN BLANK - 一种盲文图案，其六个或八个点中有零个被填充.根据标准：“*虽然此字符在许多字体中被成像为固定宽度的空白，但它不充当空格”本质上它呈现为空白，但由于它被指定为 *not* 空白，因此它与空白验证正则表达式不匹配. 这可用于绕过各种不允许或修剪空白的验证.


### Games

对于纯文本游戏，Unicode 配备了几个完整的集合：

* [Chess figures](https://codepoints.net/U+2654..U+265F).
* [Card suits](https://codepoints.net/U+2660..U+2667) 甚至一整套[甲板
    cards](https://codepoints.net/playing_cards) 带有小丑和背面
    卡.
* [Die faces](https://codepoints.net/U+2680..U+2685) 和一个不错的[死
    表情符号](https://codepoints.net/U+1F3B2).
* [Go pieces](https://codepoints.net/U+2686..U+2689).
* [Draughts (or checkers) pieces](https://codepoints.net/U+26C0..U+26C3).
* [Shogi pieces](https://codepoints.net/U+2616,U+2617,U+26C9,U+26CA)， A
    [Japanese variant of chess](https://en.wikipedia.org/wiki/Shogi).
* [Domino tiles](https://codepoints.net/domino_tiles)
* [Mahjong tiles](https://codepoints.net/mahjong_tiles)

## Other Lists of Code Points

* [Cross-platform terminal characters](https://github.com/ehmicky/cross-platform-terminal-characters) - 适用于大多数终端的字符列表.

## Contributing Your Code Points

See [the contribution guide](https://github.com/Codepoints/awesome-codepoints/blob/master/CONTRIBUTING.md) 了解详情.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[
contributors](https://github.com/Codepoints/awesome-codepoints/graphs/contributors)
已放弃该作品的所有版权和相关或邻接权. 看
[the license file](https://github.com/Codepoints/awesome-codepoints/blob/master/LICENSE) 了解详情.
