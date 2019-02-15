## Awesome Code Points [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是一个精选的Unicode字符列表，有趣（和
可能不是广为人知的特征，或者以某种其他方式令人敬畏.

## Table of Contents

1. [Standalone code points](#standalone-code-points)
2. [Code points that affect others](#code-points-that-affect-others)
    1. [Breaking and Gluing other characters](#breaking-and-gluing-other-characters)
3. [Record holders and extremes](#record-holders-and-extremes)
4. [For funsies](#for-funsies)
    1. [Games](#games)
5. [Contributing](#contributing-your-code-points)
6. [License](#license)

## Standalone Code Points

* Unicode块的代码点[Box
    绘图]（https://codepoints.net/box_drawing）（U + 2500到U + 257F）和[Block
    元素]（https://codepoints.net/block_elements）（U + 2580到U + 259F）封面
    大多数monospace命令行可视化需求.

        ╭───────╮
        │Unicode│
        │rules! │
        ╰┬─────┬╯
* [U+2E2E](https://codepoints.net/U+2E2E) 反思的问号 - “反讽
    mark” to express irony/sarcasm. A useful character&#x2E2E;
* [U+D800](https://codepoints.net/U+D800) 至
    [U+DFFF](https://codepoints.net/U+DFFF)   - 代理代码点.  他们是
    只保留缓解[UTF-16
    编码（https://en.wikipedia.org/wiki/UTF-16）.
* [U+FEFF](https://codepoints.net/U+FEFF) ZERO WIDTH NO-BREAK SPACE  - 它的名字
     建议，它可以像U + 2060 WORD JOINER一样使用.  事实上
     后者被引入以继承其语义.  这是因为U + FEFF了
    成为一个特殊的灯塔，称为[字节顺序
    标记]（https://en.wikipedia.org/wiki/Byte_order_mark），放在上面
     一些UTF-8文件的开头.  在遵守软件（包括许多
    文本编辑器）从文件的开头剥离此字符
     作为元数据处理.  在不合规的软件中（如PHP解释器）
    这导致了各种有趣的行为.
* [U+FFFD](https://codepoints.net/U+FFFD) 替换字符 - 当a
    字符无法显示（例如，解码错误的UTF-8顺序），
    此代码点进入违规行为.
* [U+1D455](https://codepoints.net/U+1D455)  不见了.  这将是一个斜体
     小“h”.  它没有编码，因为它与普朗克相同
    常数ℎ（[U+210E](https://codepoints.net/U+210E)).

## Code Points that Affect Others

* [U+202D](https://codepoints.net/U+202D) 和
    [U+202E](https://codepoints.net/U+202E) - 改变文字方向.
    相关XKCD：

    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
* [U+FE0E](https://codepoints.net/U+FE0E) VARIATION SELECTOR-15  - 力量
     黑色-_和_-白色表情符号.  如果此代码点遵循表情符号，则显式
    请求表情符号的单色渲染（如果客户端支持它）.
* [U+FE0F](https://codepoints.net/U+FE0F) VARIATION SELECTOR-16  - 强制
     多彩的表情符号.  如果这个代码点跟随一个表情符号，一个明确的多彩
    请求呈现表情符号（如果客户端支持它）.
*变音符号和组合标记：有一个[主持人
    字符]（https://codepoints.net/search?gc=Mn），即添加
     以前的人物.  这些被称为组合标记.  统一
    提供了一个 [handy FAQ](http://unicode.org/faq/char_combmark.html) 在...上
    细节，但简而言之：如果你在一个角色后添加一个，它就被放置了
     在前一个之上.  所以，`a +̊=å`.  这_may_导致各种各样
    有趣的问题，因为有些组合有预先组成
     字符.  我们这里的小`å`也可以编码为U + 00E5.  你可能会
    注意，虽然这个长度为一个字符，但是&#39;a`的组合
    并且组合环的长度为两个字符.

    当然，人们也可以用这些角色做有趣的事情
    [this answer](http://stackoverflow.com/a/1732454/113195) 在StackOverflow上.
* [Regional Indicator Symbols](https://codepoints.net/U+1F1E6..U+1F1FF)
     U + 1F1E6到U + 1F1FF类似于26个拉丁字符.  他们习惯了
     创建标志表情符号.  由于Unicode联盟不喜欢上场
    董事会与国际政治，旗帜的解决方案是结合起来
     这26个字符分别代表一个国家/地区的ISO代码.  例子：

     国家|  ISO代码|  代码点|  表情符号（如果支持）
    --------|----------|-------------------|---------------------
    USA     | US       | U+1F1FA + U+1F1F8 | &#x1F1FA;&#x1F1F8;
    Germany | DE       | U+1F1E9 + U+0F1EA | &#x1F1E9;&#x1F1EA;
    China   | CN       | U+1F1E8 + U+0F1F3 | &#x1F1E8;&#x1F1F3;
*表情符号的肤色：有五个代码点，用于控制肤色
    表情符号， [U+1F3FB to U+1F3FF](https://codepoints.net/U+1F3FB..U+1F3FF).
    它们被称为“表情符号修饰符Fitzpatrick类型”1至6，其中1表示最佳
     而最黑暗的6.  如果其中一个字符跟随表情符号，即表情符号
    意图以[Fitzpatrick的适当肤色]呈现
     规模（https://en.wikipedia.org/wiki/Fitzpatrick_scale）.  如果没有这样的话
     添加修饰语，肤色应该不自然，例如：  g.，亮黄色.
    有趣的事实：由于Fitzpatrick修饰符是正常的代码点，表情符号
    这种肤色的长度为2，Twitter用户首先注意到.
    这是一张比较图表[直接来自
    specification](http://www.unicode.org/reports/tr51/tr51-2.html#Diversity):

     代码|  名称|  样品
    --------|-------------------------------------|---------
     U + 1F3FB |  EMOJI MODIFY FITZPATRICK TYPE-1-2 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2.png" alt="" height="20" width="auto"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2-bw.png" alt="" height="20" width="auto">
    U+1F3FC | EMOJI MODIFIER FITZPATRICK TYPE-3   | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3-bw.png" alt="" height="20" width="auto">
     U + 1F3FD |  EMOJI MODIFY FITZPATRICK TYPE-4 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4-bw.png" alt="" height="20" width="auto">
     U + 1F3FE |  EMOJI MODIFY FITZPATRICK TYPE-5 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5-bw.png" alt="" height="20" width="auto">
     U + 1F3FF |  EMOJI MODIFY FITZPATRICK TYPE-6 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6-bw.png" alt="" height="20" width="auto">

### Breaking and Gluing other characters

* [U+00A0](https://codepoints.net/U+00A0) NO-BREAK SPACE  - 强迫相邻
     字符粘在一起.  在HTML中众所周知的``.
* [U+00AD](https://codepoints.net/U+00AD) SOFT HYPHEN  - （在HTML中：``）
    比如ZERO WIDTH SPACE，但是如果（并且仅当）中断发生，则显示连字符.
* [U+200B](https://codepoints.net/U+200B) ZERO WIDTH SPACE  - 与...相反
    U + 00A0：不创造空间，但允许断字.
* [U+200D](https://codepoints.net/U+200D) ZERO WIDTH JOINER  - 强迫相邻
    要连接在一起的字符（例如，阿拉伯字符或支持的字符）
     表情符号）.  Apple使用它来组成一些表情符号，如不同的家庭.
* [U+2060](https://codepoints.net/U+2060) WORD JOINER  - 与...相同
     U + 00A0，但完全看不见.  适合在Twitter上写“@ font-face”.

为了更好地比较哪个代码点具有哪种效果，请参考此处
table:

 |  U + 00A0 |  U + 00AD |  U + 200B |  U + 200D |  U + 2060
---------------|--------|--------|--------|--------|--------
 创造空间|  ✓|  ✗|  ✗|  ✗|  ✗
 允许打破|  ✗|  ✓|  ✓|  ✗|  ✗
 可能的变化|  ✗|  ✓|  ✗|  ✓|  ✗

Smashing Magazine的特色[全面
文章]（http://www.smashingmagazine.com/2015/10/space-yourself/）上
不同类型的空白.

## Record Holders and Extremes

* [U+0000](https://codepoints.net/U+0000) &lt;control&gt;  - 第一个代码点.
* [U+10FFFF](https://codepoints.net/U+10FFFF) （_non-character_） - 最后一个代码
     点.  其代码的其余部分除了U + 10FFFE之外
    在0x10000-0x10FFFD范围内，是保密的私人使用字符
    永远不会被未来的Unicode标准填充.
* [U+1F402](https://codepoints.net/U+1F402) OX  - 最短的名字.
* [U+FBF9](https://codepoints.net/U+FBF9) 阿拉伯语LIGATURE UIGHUR KIRGHIZ YEH
    与HAMZA上面的ALEF MAKSURA隔离形式 - 最长的名字：83
    字符.
* [U+FDFA](https://codepoints.net/U+FDFA) 阿拉伯语LIGATURE SALLALLAHOU ALAYHE
    WASALLAM  - 最长的分解形式：18个字符.
* [U+5146](https://codepoints.net/U+5146) 和
    [U+16B61](https://codepoints.net/U+16B61) - 代表点的代码点
     最高的“一位数”数字.  在两种情况下都是1,000,000,000,000，a
    兆.
* [U+0F33](https://codepoints.net/U+0F33) TIBETAN DIGIT HALF ZERO  - 代码点
    代表_lowest_“一位数”的数字，同时代表
    只有负一个，-½.
*大多数无用代码点的奖杯都归于此
    [U+0080](https://codepoints.net/U+0080),
    [U+0081](https://codepoints.net/U+0081) 和
    [U+0099](https://codepoints.net/U+0099) .  这些所谓的C1控制
     字符或多或少都未指定.  他们进入了Unicode，因为
    它们出现在后来成为ISO的第一个版本中
     10646，ISO的ISO标准化版本.  他们[本来应该是他们的一部分
    升级到ISO
    2022]（http://unicode.org/mail-arch/unicode-ml/y2015-m10/0050.html），
    永远不会成为.
* [U+006F](https://codepoints.net/U+006F) 拉丁文小写字母O--领先于此列表
     具有可混淆形状的字符.  在所有可能的映射中
    [混淆清单
    characters](http://www.unicode.org/reports/tr39/#Data_Files), the small “o”
    带有高达73个类似外观字形的条目，然后是
    [U+006C](https://codepoints.net/U+006C) LATIN SMALL LETTER L含70
    条目.
* [U+1F4C0](https://codepoints.net/U+1F4C0) DVD  - 没有任何元音的唯一代码点名称（[source](https://twitter.com/ken_lunde/status/960188623390846976))

## For Funsies

* [U+1680](https://codepoints.net/U+1680) OGHAM SPACE MARK  - 外观空间
     像一个破折号.  很高兴让程序员接近疯狂：`1 + 2 === 3`.
* [U+037E](https://codepoints.net/U+037E) 希腊问号 - 看起来很像
     分号.  也是一种惹恼开发者的有趣方式.
* [U+1DD2](https://codepoints.net/U+1DD2) 结合我们上面 - 这是最多
    浪漫的代码点.
* [U+F8FF](https://codepoints.net/U+F8FF) 私人使用CODEPOINT  - 这是私人
    使用代码点在许多Apple设备上呈现为Apple徽标.
* [U+1F574](https://codepoints.net/U+1F574) 男人在商务套装中徘徊 - 
    一个相当好奇的角色，只为其制作了Unicode
    出现在Webdings字体中（出于向后兼容的原因）.
* [U+1F596](https://codepoints.net/U+1F596) 提升手与部分之间的关​​系
     中环和手环 - 火神致敬.  健康长寿·繁荣昌盛！
    &#x1F596;
* [U+1F918](https://codepoints.net/U+1F918) 呐喊的标志 - 摇滚！
    &#x1F918;
* [U+2800](https://codepoints.net/U+2800)  BRAILLE PATTERN BLANK  - 填充了六个或八个点零的盲文图案.根据标准：“*虽然这个字符在许多字体中被成像为固定宽度的空白，但它不会充当空间”它被渲染为空白区域，但由于它被指定为* not * white-space，因此它不会被白色空间验证的正则表达式匹配.  这可以用于绕过不允许或修剪空白的各种验证.


### Games

对于纯文本游戏，Unicode配备了几套完整的：

* [Chess figures](https://codepoints.net/U+2654..U+265F).
* [Card suits](https://codepoints.net/U+2660..U+2667) 甚至整个[甲板上的]
    卡片]（https://codepoints.net/playing_cards）完成了小丑和回来
    卡.
* [Die faces](https://codepoints.net/U+2680..U+2685) 和一个很好的[死
    表情符号]（https://codepoints.net/U+1F3B2）.
* [Go pieces](https://codepoints.net/U+2686..U+2689).
* [Draughts (or checkers) pieces](https://codepoints.net/U+26C0..U+26C3).
* [Shogi pieces](https://codepoints.net/U+2616,U+2617,U+26C9,U+26CA)， 一个
    [Japanese variant of chess](https://en.wikipedia.org/wiki/Shogi).
* [Domino tiles](https://codepoints.net/domino_tiles)
* [Mahjong tiles](https://codepoints.net/mahjong_tiles)

## Contributing Your Code Points

See [the contribution guide](https://github.com/Codepoints/awesome-codepoints/blob/master/CONTRIBUTING.md) 详情.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[
contributors](https://github.com/Codepoints/awesome-codepoints/graphs/contributors)
 已放弃对此作品的所有版权及相关或邻接权利.  看到
[the license file](https://github.com/Codepoints/awesome-codepoints/blob/master/LICENSE) 详情.
