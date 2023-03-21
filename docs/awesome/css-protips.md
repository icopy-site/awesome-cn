<div class="github-widget" data-repo="AllThingsSmitty/css-protips"></div>
<p align="center">
  <img src="https://raw.githubusercontent.com/AllThingsSmitty/css-protips/master/./assets/img/bulb.svg?sanitize=true" width="200" alt="light bulb icon">
</p>

## CSS Protips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

帮助您提高 CSS 技能的技巧集合.

&gt; 对于其他很棒的列表，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).



* [Contribution Guidelines](https://github.com/AllThingsSmitty/css-protips/blob/master/CONTRIBUTING.md)


## Protips



### Use a CSS Reset

 CSS 重置有助于在不同浏览器之间实现样式一致性，并为样式元素提供干净的样式. 您可以使用 CSS 重置库，例如 [Normalize](http://necolas.github.io/normalize.css/)，_et al._，或者您可以使用更简化的重置方法：

```css
*,
*::before,
*：：后 {
  框大小：边框框；
  保证金：0；
  填充：0；
}
```

现在元素将被去除边距和填充，而 `box-sizing` 让您可以使用 CSS 盒子模型管理布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/kkrkLL)

**注意：**如果您遵循 [Inherit `box-sizing`](#inherit-box-sizing) 下面提示您可以选择不在 CSS 重置中包含 `box-sizing` 属性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Inherit `box-sizing`

让 `box-sizing` 继承自 `html`：

```css
HTML {
  框大小：边框框；
}

*,
*::before,
*：：后 {
  盒子大小：继承；
}
```

这使得更改插件或利用其他行为的其他组件中的“box-sizing”变得更加容易.

#### [Demo](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `unset` Instead of Resetting All Properties

重置元素的属性时，不必重置每个单独的属性：

```css
按钮 {
  背景：无；
  边框：无；
  颜色：继承；
  字体：继承；
  大纲：无；
  填充：0；
}
```

您可以使用 `all` 速记指定元素的所有属性. 将值设置为 `unset` 会将元素的属性更改为其初始值：

```css
按钮 {
  全部：未设置；
}
```

**注意：** IE11 不支持 `all` 和 `unset` 简写.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:not()` to Apply/Unapply Borders on Navigation

而不是把边界...

```css
/* 添加边框 */
.name 在 {
  border-right: 1px solid #666;
}
```

...然后将其从最后一个元素中删除...

```css
/* 去除边框 */
.nav li:last-child {
  右边界：无；
}
```

...使用 `:not()` 伪类只应用到你想要的元素：

```css
.nav li:not(:last-child) {
  border-right: 1px solid #666;
}
```

在这里，CSS 选择器被理解为人类会描述它的方式.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/LkymvO)

<sup>[back to table of contents](#table-of-contents)</sup>


### Check If Font Is Installed Locally

您可以在远程获取字体之前检查是否在本地安装了字体，这也是一个很好的性能提示.

```css
@字体脸{
  字体系列：“Dank Mono”；
  来源：
    /* 全名 */
    本地（“Dank Mono”），
    /* 后记名称 */
    本地（“Dank-Mono”），
     /* 否则，下载它！  */
    url(&quot;//...a.server/fonts/DankMono.woff&quot;);
}

代码 {
  字体系列：“Dank Mono”，system-ui-monospace；
}
```

H/T to Adam Argyle 分享这个提示和 [demo](https://codepen.io/argyleink/pen/VwYJpgR).

<sup>[back to table of contents](#table-of-contents)</sup>


### Add `line-height` to `body`

您不需要为每个 ` 添加 `line-height`<p>  `, `<h*>  `，_等_. 分别地. 相反，将其添加到“body”：

```css
身体 {
  行高：1.5；
}
```

这样，文本元素可以很容易地从 `body` 继承.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/VjbdYd)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `:focus` for Form Elements

有视力的键盘用户依靠焦点来确定键盘事件在页面中的位置. 使表单元素的焦点比浏览器的默认实现更加突出和一致：

```css
a:focus,
button:focus,
input:focus,
select:focus,
文本区域：焦点{
  盒子阴影：无；
  outline: #000 dotted 2px;
  轮廓偏移：.05em；
}
```

#### [Demo](https://codepen.io/AllThingsSmitty/pen/ePzoOP/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Vertically-Center Anything

不，这不是黑魔法，你真的可以让元素垂直居中. 你可以用 flexbox 做到这一点......

```css
html,
身体 {
  高度：100%；
  保证金：0；
}

身体 {
  -webkit-align-items：居中；
  -ms-flex-align: 居中；
  对齐项目：居中；
  显示：-webkit-flex；
  显示：弹性；
}
```

...还有 CSS 网格：

```css
身体 {
  显示：网格；
  高度：100vh；
  保证金：0；
  放置项目：中心中心；
}
```


想居中其他东西吗？ 垂直、水平……任何时间、任何地点？  CSS 技巧有 [a nice write-up](https://css-tricks.com/centering-css-complete-guide/) 在做所有这些.

**注意：**注意一些 [buggy behavior](https://github.com/philipwalton/flexbugs#3-min-height-on-a-flex-container-wont-apply-to-its-flex-items) 在 IE11 中使用 flexbox.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/GqmGqZ)

<sup>[back to table of contents](#table-of-contents)</sup>


### Comma-Separated Lists

使列表项看起来像一个真实的逗号分隔列表：

```css
ul &gt; li:not(:last-child)::after {
  内容： ”，”;
}
```

使用 `:not()` 伪类，最后一项不会添加逗号.


<sup>[back to table of contents](#table-of-contents)</sup>


### Select Items Using Negative `nth-child`

在 CSS 中使用否定的“nth-child”来选择项目 1 到 n.

```css
那 {
  显示：无；
}

/* 选择项目 1 到 3 并显示它们 */
li:nth-child(-n+3) {
  显示：块；
}
```

或者，既然你已经了解了一些 [using `:not()`](#use-not-to-applyunapply-borders-on-navigation)， 尝试：

```css
/* 选择除前 3 个之外的所有项目并显示它们 */
li:not(:nth-child(-n+3)) {
  显示：块；
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/WxjKZp)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use SVG for Icons

没有理由不对图标使用 SVG：

```css
.标识 {
  背景：网址（“徽标.svg”）；
}
```

SVG 可以很好地适应所有分辨率类型，并且在所有浏览器中都受支持 [back to IE9](http://caniuse.com/#search=svg) . 丢弃您的 .png、.jpg 或 .gif-jif-whatev 文件.

**Note:** If you have SVG icon-only buttons for sighted users and the SVG fails to load, this will help maintain accessibility:

```css
.no-svg .icon-only::after {
  内容：属性（咏叹调标签）；
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use the "Lobotomized Owl" Selector

它可能有一个奇怪的名字，但使用通用选择器（`*`）和相邻的兄弟选择器（`+`）可以提供强大的 CSS 功能：

```css
* + * {
  顶部边距：1.5em；
}
```

在此示例中，文档流中跟在其他元素之后的所有元素都将收到 margin-top: 1.5em .

有关“lobotomized owl”选择器的更多信息，请阅读 [Heydon Pickering's post](http://alistapart.com/article/axiomatic-css-and-lobotomized-owls) 在 *A List Apart* 上.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/grRvWq)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `max-height` for Pure CSS Sliders

使用隐藏溢出的 `max-height` 实现纯 CSS 滑块：

```css
.滑块{
  最大高度：200px；
  溢出-y：隐藏；
  宽度：300px；
}

.滑块：悬停{
  最大高度：600px；
  溢出-y：滚动；
}
```

元素在悬停时扩展到“max-height”值，滑块显示为溢出的结果.

<sup>[back to table of contents](#table-of-contents)</sup>


### Equal-Width Table Cells

使用表格可能会很痛苦. 尝试使用 `table-layout: fixed` 使单元格保持等宽：

```css
.日历 {
  表格布局：固定；
}
```

无痛表布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALALm)

<sup>[back to table of contents](#table-of-contents)</sup>


### Get Rid of Margin Hacks With Flexbox

使用列间距时，您可以通过使用 flexbox 的 space-between 属性来摆脱 `nth-`、`first-` 和 `last-child` 的 hacks：

```css
.列表 {
  显示：弹性；
  证明内容：空格之间；
}

.list .person {
  弹性基础：23%；
}
```

现在列间距总是均匀分布.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Attribute Selectors with Empty Links

当 ` <a>` 元素没有文本值但 `href` 属性有链接时显示链接：</a>

```css
a[href^=&quot;http&quot;]:empty::before {
  内容：属性（href）；
}
```

这很方便.


#### [Demo](http://codepen.io/AllThingsSmitty/pen/zBzXRx)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style "Default" Links

为“默认”链接添加样式：

```css
a[href]:not([class]) {
  color: #008000;
  文本修饰：下划线；
}
```

现在，通过 CMS 插入的链接（通常不具有“class”属性）将具有区别，而不会普遍影响级联.

<sup>[back to table of contents](#table-of-contents)</sup>


### Intrinsic Ratio Boxes

要创建一个具有固有比例的框，您需要做的就是将顶部或底部填充应用于 div：

```css
.容器 {
  高度：0；
  底部填充：20%；
  位置：相对；
}

.容器分区{
  border: 2px dashed #ddd;
  高度：100%；
  左：0；
  位置：绝对；
  顶部：0；
  宽度：100%；
}
```

使用 20% 的填充使框的高度等于其宽度的 20%. 无论视口的宽度如何，子 div 都将保持其宽高比 (100% / 20% = 5:1).

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALZvE)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style Broken Images

使用一点 CSS 使损坏的图像更美观：

```css
图片 {
  显示：块；
  字体系列：无衬线；
  字体粗细：300；
  高度：自动；
  行高：2；
  位置：相对；
  文本对齐：居中；
  宽度：100%；
}
```

现在添加伪元素规则以显示损坏图像的用户消息和 URL 引用：

```css
img::之前{
  content: &quot;很抱歉，下面的图片损坏了:(&quot;;
  显示：块；
  底部边距：10px；
}

img::之后{
  内容：“（网址：“attr（src）”）”；
  显示：块；
  字体大小：12px；
}
```

在中了解有关此模式样式的更多信息 [Ire Aderinokun](https://github.com/ireade/)'s [original post](http://bitsofco.de/styling-broken-images/).

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `rem` for Global Sizing; Use `em` for Local Sizing

在根部设置基本字体大小（`html { font-size: 100%; }`）后，将文本元素的字体大小设置为 `em`：

```css
h2 {
  字体大小：2em；
}

p {
  字体大小：1em；
}
```

然后将模块的字体大小设置为“rem”：

```css
文章 {
  字体大小：1.25rem；
}

除了.module {
  字体大小：.9rem；
}
```

现在，每个模块都被分隔开来，更易于设计样式、更易于维护且更灵活.

<sup>[back to table of contents](#table-of-contents)</sup>


### Hide Autoplay Videos That Aren't Muted

这是自定义用户样式表的绝妙技巧. 避免让用户在加载页面时自动播放的视频声音过载. 如果声音未静音，则不显示视频：

```css
视频[自动播放]：不（[静音]）{
  显示：无；
}
```

再一次，我们利用了 [`:not()`](#use-not-to-applyunapply-borders-on-navigation) 伪类.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:root` for Flexible Type

响应式布局中的字体大小应该能够根据每个视口进行调整. 您可以使用“:root”根据视口高度和宽度计算字体大小：

```css
：根 {
  字体大小：计算（1vw + 1vh + .5vmin）；
}
```

现在您可以根据 :root 计算的值使用 root em 单位：

```css
身体 {
  字体：1rem/1.6 无衬线字体；
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/XKgOkR)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `font-size` on Form Elements for a Better Mobile Experience

为了避免移动浏览器（iOS Safari，_et al_）在 `<select> ` 下拉菜单被点击，添加 `font-size` 到选择器规则：

```css
input[type="text"],
input[type="number"],
select,
文本区域{
  字体大小：16px；
}
```

:dancer:

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Pointer Events to Control Mouse Events

[Pointer events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events) 允许您指定鼠标如何与其触摸的元素交互. 要禁用按钮上的默认指针事件，例如：

```css
按钮：禁用{
  不透明度：.5；
  指针事件：无；
}
```

就这么简单.

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `display: none` on Line Breaks Used as Spacing

As [Harry Roberts pointed out](https://twitter.com/csswizardry/status/1170835532584235008), 这有助于防止 CMS 用户使用额外的换行符来分隔：

```css
br + br {
  显示：无；
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:empty` to Hide Empty HTML Elements

如果您有空的 HTML 元素，即内容尚未通过 CMS 设置或动态注入（例如，`<p class="error-message"></p>  `) 并且它在您的布局上创建不需要的空间，请使用 `:empty` 伪类来隐藏布局上的元素. 

```css
：空的 {
  显示：无；
}
```

 **注意：** 请记住，带有空格的元素不被视为空元素，例如，`<p class="error-message"></p>  `.

<sup>[back to table of contents](#table-of-contents)</sup>


## Support

Chrome、Firefox、Safari、Opera、Edge 和 IE11 的当前版本.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

 **注意：**我没有多少时间来维护不断增长的翻译提示列表； 添加一个新提示需要包含十几种翻译. 因此，翻译后的 README 文件可能不包括主 README 文件中列出的所有提示.

* [简体中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-CN)
* [正體中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-TW)
* [Deutsch](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/de-DE)
* [Español](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/fr-FR)
* [λληνικά](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gr-GR)
* [ગુજરાતી](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gu-IND)
* [Italiano](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/it-IT)
* [日本語](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ja-JP)
* [한국어](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ko-KR)
* [Polskie](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pl-PL)
* [Português do Brasil](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-BR)
* [Português do Europe](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-PT)
* [Русский](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ru-RU)
* [Tiếng Việt](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/vn-VN)

<sup>[back to table of contents](#table-of-contents)</sup>
