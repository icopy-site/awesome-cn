<div class="github-widget" data-repo="Codepoints/awesome-codepoints"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Code Points [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是Unicode中精选字符的列表，这些字符很有意思（并且
可能还不为人所知）功能，或者在其他方面很棒.



## Standalone Code Points

* Unicode块的代码点[Box
    绘图]（https://codepoints.net/box_drawing）（U + 2500至U + 257F）和[块
    元素]（https://codepoints.net/block_elements）（U + 2580至U + 259F）封面
    您大多数等宽命令行可视化需求.

        ╭───────╮
        │Unicode│
        │rules! │
        ╰┬─────┬╯
* [U+2E2E](https://codepoints.net/U+2E2E) 反向问号-“讽刺”
    mark” to express irony/sarcasm. A useful character&#x2E2E;
* [U+D800](https://codepoints.net/U+D800) 至
    [U+DFFF](https://codepoints.net/U+DFFF)  -替代代码点. 他们是
    只为缓解[UTF-16
    编码]（https://en.wikipedia.org/wiki/UTF-16）.
* [U+FEFF](https://codepoints.net/U+FEFF) 零宽度无间断空间-它的名字
    建议，它可以像U + 2060 WORD JOINER一样使用. 实际上
    引入后者来继承其语义. 这是因为U + FEFF具有
    成为称为[字节顺序的特殊信标
    标记]（https://en.wikipedia.org/wiki/Byte_order_mark），放在
    一些UTF-8文件的开头. 在合规软件（包括许多
    文本编辑器），将从文件开头删除此字符，然后
    作为元数据处理. 在非兼容软件（例如PHP解释器）中
    这导致各种有趣的行为.
* [U+FFFD](https://codepoints.net/U+FFFD) 更换字符-当
    字符无法显示（例如，解码错误的UTF-8序列），
    此代码点进入了违反行为.
* [U+1D455](https://codepoints.net/U+1D455) 不见了. 这将是斜体
    小“ h”. 它未编码，因为它与Planck相同
    常数ℎ（[U+210E](https://codepoints.net/U+210E)).
* [U+FF03](https://codepoints.net/U+FF03) 完整数字符号-这是 
     “日语标签”`＃`. 像Twitter这样的网站将其等同于 
    regular `#` ([U+0023](https://codepoints.net/U+0023)).

## Code Points that Affect Others

* [U+202D](https://codepoints.net/U+202D) 和
    [U+202E](https://codepoints.net/U+202E) -更改文字方向.
    相关的XKCD：

    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
* [U+FE0E](https://codepoints.net/U+FE0E) VARIATION SELECTOR-15-强制
    黑色_＆_-白色表情符号. 如果此代码点跟随表情符号，则显式
    请求表情符号的单色渲染（如果客户端支持）.
* [U+FE0F](https://codepoints.net/U+FE0F) VARIATION SELECTOR-16-强制
    多彩的表情符号. 如果此代码点跟随表情符号，则显式的彩色
    请求渲染表情符号（如果客户端支持）.
*变音符号和组合标记：[
    字符]（https://codepoints.net/search?gc=Mn），
    到以前的字符. 那些被称为组合标记. 统一码
    提供一个 [handy FAQ](http://unicode.org/faq/char_combmark.html) 在
    细节，但简而言之：如果在字符后添加一个，则将其放置
    在前一个之上. 因此，“ a +¿=å”. 这_可能_导致各种
    有趣的问题，因为对于某些组合，它们是预先组成
    字符. 我们这里的小“å”也可以编码为U + 00E5. 你可能会
    注意，尽管它的长度为一个字符，但是`a`的组合
    组合环的长度为两个字符.

    Of course, one can also do fun things with those characters like
    [this answer](http://stackoverflow.com/a/1732454/113195) 在StackOverflow上.
* [Regional Indicator Symbols](https://codepoints.net/U+1F1E6..U+1F1FF)
     U + 1F1E6至U + 1F1FF与26个拉丁字符相似. 他们习惯了
    创建标志表情符号. 由于Unicode联盟不想继续前进
    在国际政治中，旗帜的解决方案是结合
    这26个字符对应一个国家/地区的相应ISO代码. 例子：

    国家（地区）|  ISO代码| 代码点| 表情符号（如果支持）
    --------|----------|-------------------|---------------------
    USA     | US       | U+1F1FA + U+1F1F8 | &#x1F1FA;&#x1F1F8;
    Germany | DE       | U+1F1E9 + U+1F1EA | &#x1F1E9;&#x1F1EA;
    China   | CN       | U+1F1E8 + U+1F1F3 | &#x1F1E8;&#x1F1F3;
*表情符号的肤色：共有五个代码点，用于控制肤色
    表情符号 [U+1F3FB to U+1F3FF](https://codepoints.net/U+1F3FB..U+1F3FF).
    它们被称为“表情符号Fitzpatrick类型” 1到6，其中1代表最浅
    和6个最暗的. 如果这些字符之一跟随表情符号，则该表情符号
    旨在以[菲茨帕特里克（Fitzpatrick）
    比例]（https://en.wikipedia.org/wiki/Fitzpatrick_scale）. 如果没有
    添加修饰剂后，肤色应该不自然，例如 g.亮黄色.
    有趣的事实：由于Fitzpatrick修饰符是正常的代码点，因此表情符号
    具有此类肤色的长度为2，这是Twitter用户首先注意到的长度.
    这是一个比较表[直接来自
    specification](http://www.unicode.org/reports/tr51/tr51-2.html#Diversity):

    代码姓名| 样品
    --------|-------------------------------------|---------
     U + 1F3FB | 表情符号修改器FITZPATRICK TYPE-1-2 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2.png" alt="" height="20" width="auto"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2-bw.png" alt="" height="20" width="auto">
     U + 1F3FC | 表情符号修饰器FITZPATRICK TYPE-3 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3-bw.png" alt="" height="20" width="auto">
     U + 1F3FD | 表情符号修饰器FITZPATRICK TYPE-4 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4-bw.png" alt="" height="20" width="auto">
     U + 1F3FE | 表情符号修饰器FITZPATRICK TYPE-5 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5-bw.png" alt="" height="20" width="auto">
     U + 1F3FF | 表情符号修饰器FITZPATRICK TYPE-6 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6-bw.png" alt="" height="20" width="auto">

### Breaking and Gluing other characters

* [U+00A0](https://codepoints.net/U+00A0) 无间断空间-强制相邻
    字符粘在一起. 在HTML中众所周知为``.
* [U+00AD](https://codepoints.net/U+00AD) 软连字符-（在HTML中：``）
    类似于零宽度的空格，但在（且仅当）出现中断时显示连字符.
* [U+200B](https://codepoints.net/U+200B) 零宽度空间-的倒数
    U + 00A0：不创建空格，但允许断字.
* [U+200D](https://codepoints.net/U+200D) 零宽度JOINER-强制相邻
    要结合在一起的字符（例如阿拉伯字符或受支持的字符）
    表情符号）. 苹果使用它来组成一些像不同家族的表情符号.
* [U+2060](https://codepoints.net/U+2060) WORD JOINER-与
     U + 00A0，但完全不可见. 非常适合在Twitter上编写`@ font-face`.

为了更好地比较哪个代码点具有哪个效果，请参阅此
table:

 |  U + 00A0 |  U + 00AD |  U + 200B |  U + 200D |  U + 2060
---------------|--------|--------|--------|--------|--------
创造空间|  ✓|  ✗|  ✗|  ✗|  ✗
允许破坏|  ✗|  ✓|  ✓|  ✗|  ✗
可能的变化|  ✗|  ✓|  ✗|  ✓|  ✗

粉碎杂志精选[综合
文章]（http://www.smashingmagazine.com/2015/10/space-yourself/）上
不同类型的空格.

## Record Holders and Extremes

* [U+0000](https://codepoints.net/U+0000) &lt;control&gt;-第一个代码点.
* [U+10FFFF](https://codepoints.net/U+10FFFF) （_non-character_）-最后一个代码
    点. 除U + 10FFFE之外，飞机的整个其余部分，代码指向
    在0x10000-0x10FFFD范围内，是专用字符，请确保
    永远不会被将来的Unicode标准所填充.
* [U+1F402](https://codepoints.net/U+1F402) OX-最短名称.
* U + 1FBA8方框图浅对角线的上中心到左中间，中间右到下中心
    和
    U + 1FBA9方框图轻右上角中心向右中间，左中角向下中心-最长名称：88
    每个字符.
* [U+FDFA](https://codepoints.net/U+FDFA) 阿拉伯文绑带SALLALLAHOU ALAYHE
    WASALLAM-最长的分解形式：18个字符.
* [U+5146](https://codepoints.net/U+5146) 和
    [U+16B61](https://codepoints.net/U+16B61) -代表
    最高的“个位数”数字. 在两种情况下都是1,000,000,000,000，
    兆.
* [U+0F33](https://codepoints.net/U+0F33) 西藏数字半零-代码点
    代表_lowest_“个位数”数字，同时
    只有负数-1/2.
*大多数无用代码点的奖杯
    [U+0080](https://codepoints.net/U+0080),
    [U+0081](https://codepoints.net/U+0081) 和
    [U+0099](https://codepoints.net/U+0099) . 这些所谓的C1控制
    字符或多或少未指定. 他们加入了Unicode，因为
    它们出现在后来应成为ISO的第一个版本中
     10646，ISO标准化版本的Unicode. 他们[本来是一部分
    升级到ISO
    2022]（http://unicode.org/mail-arch/unicode-ml/y2015-m10/0050.html），
    从来没有成为.
*在这方面排名第二的是中日韩统一表意文字
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
    [壥](https://codepoints.net/U+58E5)和
    [彁](https://codepoints.net/U+5F41) . 这些所谓 [“ghost characters”](https://www.dampfkraft.com/ghost-characters.html)
    通过添加了日语JIS标准的Unicode来到Unicode，因为
    在编制JIS时被误读或从其他符号中误解了它们
    来自原始的印刷文本来源.
* [U+006F](https://codepoints.net/U+006F) 拉丁文小写字母O-领先
    形状混乱的字符集. 在所有可能的映射中
    [易混淆的清单
    characters](http://www.unicode.org/reports/tr39/#Data_Files), the small “o”
    带有多达73个看起来相似的字形的条目，其次是
    [U+006C](https://codepoints.net/U+006C) 带70的拉丁文小写字母L
    条目.
* [U+1F4C0](https://codepoints.net/U+1F4C0) DVD-仅代码点名称，没有任何元音（[source](https://twitter.com/ken_lunde/status/960188623390846976))

## For Funsies

* [U+1680](https://codepoints.net/U+1680) OGHAM SPACE MARK-看上去很美的空间
    像破折号. 使程序员接近疯狂非常好：`1 + 2 === 3`.
* [U+037E](https://codepoints.net/U+037E) 希腊问号-类似于
    分号. 这也是使开发人员恼火的一种有趣方式.
* [U+1DD2](https://codepoints.net/U+1DD2) 结合以上-这是最
    浪漫的代码点.
* [U+F8FF](https://codepoints.net/U+F8FF) 私人使用密码点-此私人
    使用代码点在许多Apple设备上都被渲染为Apple徽标.
* [U+1F574](https://codepoints.net/U+1F574) 从事商务休闲的人-
    一个相当奇怪的字符，仅因其字符而变成了Unicode
    Webdings字体中的外观（出于向后兼容的原因）.
* [U+1F596](https://codepoints.net/U+1F596) 零件之间的举手
    中指和指环-火神致敬. 健康长寿·繁荣昌盛！
    &#x1F596;
* [U+1F918](https://codepoints.net/U+1F918) 刺的迹象-继续前进！
    &#x1F918;
* [U+2800](https://codepoints.net/U+2800)  BRAILLE PATTERN BLANK-盲文图案，其中填充了六个或八个点中的零.根据标准：“ *在许多字体中，此字符被成像为固定宽度的空白时，它不充当空格”它被呈现为空白，但是由于它被指定为* not *空格，因此它与验证空白的正则表达式不匹配. 这可以用来绕过各种不允许或修剪空白的验证.


### Games

对于纯文本游戏，Unicode配备了几套完整的设备：

* [Chess figures](https://codepoints.net/U+2654..U+265F).
* [Card suits](https://codepoints.net/U+2660..U+2667) 甚至整个[
    卡]（https://codepoints.net/playing_cards）带有小丑和后盖
    卡.
* [Die faces](https://codepoints.net/U+2680..U+2685) 和一个不错的[死
    表情符号]（https://codepoints.net/U+1F3B2）.
* [Go pieces](https://codepoints.net/U+2686..U+2689).
* [Draughts (or checkers) pieces](https://codepoints.net/U+26C0..U+26C3).
* [Shogi pieces](https://codepoints.net/U+2616,U+2617,U+26C9,U+26CA)， 一种
    [Japanese variant of chess](https://en.wikipedia.org/wiki/Shogi).
* [Domino tiles](https://codepoints.net/domino_tiles)
* [Mahjong tiles](https://codepoints.net/mahjong_tiles)

## Contributing Your Code Points

See [the contribution guide](https://github.com/Codepoints/awesome-codepoints/blob/master/CONTRIBUTING.md) 有关详细信息.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[
contributors](https://github.com/Codepoints/awesome-codepoints/graphs/contributors)
放弃了此作品的所有版权以及相关或邻近的权利. 看到
[the license file](https://github.com/Codepoints/awesome-codepoints/blob/master/LICENSE) 有关详细信息.
