<div class="github-widget" data-repo="AllThingsSmitty/css-protips"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<p align="center">
  <img src="https://rawgit.com/AllThingsSmitty/css-protips/master/media/logo.svg" width="200" alt="light bulb icon">
</p>

## CSS Protips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一系列技巧帮助您掌握CSS技能.

&gt;有关其他很棒的清单，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).



* [Contribution Guidelines](https://github.com/AllThingsSmitty/css-protips/blob/master/CONTRIBUTING.md)


## Protips



### Use a CSS Reset

 CSS重置使用干净的样式元素来帮助在不同浏览器之间实现样式一致性. 您可以使用CSS重置库，例如 [Normalize](http://necolas.github.io/normalize.css/)，_等_，或者您可以使用更简化的重置方法：

```css
*,
*::before,
* :: {之后
  框大小：border-box；
  边距：0;
  padding: 0;
}
```

现在，将去除元素的边距和内边距，“ box-sizing”可让您使用CSS box模型管理布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/kkrkLL)

**注意：**如果您遵循 [Inherit `box-sizing`](#inherit-box-sizing) 在下面的提示中，您可能会选择在CSS重置中不包含`box-sizing`属性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Inherit `box-sizing`

让`box-sizing`继承自`html`：

```css
html {
  框大小：border-box；
}

*,
*::before,
* :: {之后
  大小调整：继承；
}
```

这使得在利用其他行为的插件或其他组件中更改“ box-sizing”更加容易.

#### [Demo](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `unset` Instead of Resetting All Properties

重置元素的属性时，不必重置每个单独的属性：

```css
按钮{
  背景：无；
  边框：无；
  颜色：继承；
  font：继承;
  大纲：无；
  padding: 0;
}
```

您可以使用`all`速记来指定元素的所有属性. 将值设置为`unset`会将元素的属性更改为其初始值：

```css
按钮{
  全部：未设置；
}
```

 **注意：** IE11不支持`all`速记，目前正在考虑Edge中的支持.  IE11不支持`unset`.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:not()` to Apply/Unapply Borders on Navigation

而不是放下边界...

```css
/ *添加边框* /
.nav li {
  border-right: 1px solid #666;
}
```

...然后将其从最后一个元素中移除...

```css
/ *删除边框* /
.nav li：last-child {
  右边框：无；
}
```

...使用`：not（）`伪类仅适用于您想要的元素：

```css
.nav li：not（：last-child）{
  border-right: 1px solid #666;
}
```

在这里，CSS选择器被理解为人类会描述它的方式.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/LkymvO)

<sup>[back to table of contents](#table-of-contents)</sup>


### Check If Font Is Installed Locally

您可以在远程获取字体之前检查是否在本地安装了字体，这也是一个很好的性能提示.

```css
@ font-face {
  字体家族：“ Dank Mono”；
  src：
    /* 全名 */
    本地（“感谢Mono”），
    / *后记名称* /
    本地（“感谢Mono”），
     / *否则，请下载！  * /
    url（“ // ... a.server / fonts / DankMono.woff”）;
}

代码{
  字体家族：“ Dank Mono”，system-ui-monospace；
}
```

感谢Adam Argyle分享此建议和 [demo](https://codepen.io/argyleink/pen/VwYJpgR).

<sup>[back to table of contents](#table-of-contents)</sup>


### Add `line-height` to `body`

您不需要在每个`中添加`line-height`<p>  `，`<h*>  `，等. 分别. 相反，将其添加到`body`中：

```css
身体 {
  行高：1.5；
}
```

这样，文本元素可以轻松地从`body`继承.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/VjbdYd)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `:focus` for Form Elements

视觉键盘用户依靠焦点来确定键盘事件在页面中的位置. 将焦点放在表单元素上并与浏览器的默认实现保持一致：

```css
a:focus,
button:focus,
input:focus,
select:focus,
textarea：focus {
  盒子阴影：无；
  outline: #000 dotted 2px;
  轮廓偏移：.05em;
}
```

#### [Demo](https://codepen.io/AllThingsSmitty/pen/ePzoOP/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Vertically-Center Anything

不，这不是黑魔法，您确实可以使元素垂直居中. 您可以使用flexbox做到这一点...

```css
html,
身体 {
  高度：100％;
  边距：0;
}

身体 {
  -webkit-align-items：center;
  -ms-flex-align：居中；
  align-items：居中;
  显示：-webkit-flex;
  显示：flex;
}
```

...以及CSS Grid：

```css
身体 {
  显示：网格；
  高度：100vh；
  边距：0;
  地方项目：中心中心；
}
```


想要以其他为中心吗？ 垂直，水平...什么都可以，随时随地？  CSS技巧有 [a nice write-up](https://css-tricks.com/centering-css-complete-guide/) 在做所有这些.

**注意：**注意一些 [buggy behavior](https://github.com/philipwalton/flexbugs#3-min-height-on-a-flex-container-wont-apply-to-its-flex-items) 在IE11中使用flexbox.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/GqmGqZ)

<sup>[back to table of contents](#table-of-contents)</sup>


### Comma-Separated Lists

使列表项看起来像真实的逗号分隔列表：

```css
ul&gt; li：not（：last-child）:: after {
  内容：“，”;
}
```

使用`：not（）`伪类，不会在最后一项添加逗号.


<sup>[back to table of contents](#table-of-contents)</sup>


### Select Items Using Negative `nth-child`

在CSS中使用负数nth-child来选择项1到n.

```css
li {
  显示：无；
}

/ *选择项目1至3并显示它们* /
li：nth-​​child（-n + 3）{
  显示：块；
}
```

或者，因为您已经学到了一些 [using `:not()`](#use-not-to-applyunapply-borders-on-navigation)，尝试：

```css
/ *选择前三个项目以外的所有项目并显示它们* /
li：not（：nth-​​child（-n + 3））{
  显示：块；
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/WxjKZp)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use SVG for Icons

没有理由不对图标使用SVG：

```css
.商标 {
  背景：url（“ logo.svg”）;
}
```

SVG可以很好地适应所有分辨率类型，并且在所有浏览器中均受支持 [back to IE9](http://caniuse.com/#search=svg) . 抛弃您的.png，.jpg或.gif-jif-whatev文件.

**注意：**如果您为有视力的用户提供仅SVG图标的按钮，而SVG无法加载，则有助于维护可访问性：

```css
.no-svg .icon-only ::之后{
  内容：attr（aria-label）;
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use the "Lobotomized Owl" Selector

它的名称可能很奇怪，但是将通用选择器（*）与相邻的兄弟选择器（+）结合使用可以提供强大的CSS功能：

```css
* + * {
  上边距：1.5em;
}
```

在此示例中，文档流中所有其他元素之后的所有元素都将收到“ margin-top：1.5em”.

有关“圆角猫头鹰”选择器的更多信息，请阅读 [Heydon Pickering's post](http://alistapart.com/article/axiomatic-css-and-lobotomized-owls) 在* A List Apart *上.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/grRvWq)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `max-height` for Pure CSS Sliders

使用`max-height`实现仅CSS滑块，并隐藏溢出：

```css
.slider {
  max-height：200像素；
  溢出y：隐藏；
  宽度：300像素；
}

.slider：hover {
  最大高度：600px；
  溢出y：滚动；
}
```

该元素在悬停时扩展为“ max-height”值，并且由于溢出而显示滑块.

<sup>[back to table of contents](#table-of-contents)</sup>


### Equal-Width Table Cells

使用表格可能会很痛苦. 尝试使用“ table-layout：fixed”将单元保持相等的宽度：

```css
.calendar {
  表格布局：固定；
}
```

无痛的桌子布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALALm)

<sup>[back to table of contents](#table-of-contents)</sup>


### Get Rid of Margin Hacks With Flexbox

使用列装订线时，可以通过使用flexbox的`space-between`属性来摆脱`nth-`，`first-`和`last-child`的黑客：

```css
.list {
  显示：flex;
  证明内容：间隔；
}

.list .person {
  弹性基础：23％;
}
```

现在，列装订线始终显示为均匀间隔.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Attribute Selectors with Empty Links

当` <a>`元素没有文本值，但`href`属性具有</a>链接时，显示链接<a>：</a>

```css
a [href ^ =“ http”]：空::之前{
  内容：attr（href）;
}
```

那很方便.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/zBzXRx)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style "Default" Links

为“默认”链接添加样式：

```css
a [href]：not（[class]）{
  color: #008000;
  文字装饰：下划线；
}
```

现在，通过CMS插入的链接通常不具有“ class”属性，它们之间将具有区别，而不会普遍影响级联.

<sup>[back to table of contents](#table-of-contents)</sup>


### Consistent Vertical Rhythm

在元素内使用通用选择器（`*`）创建一致的垂直节奏：

```css
.intro&gt; * {
  底边距：1.25rem;
}
```

一致的垂直节奏可提供视觉美感，使内容更具可读性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Intrinsic Ratio Boxes

要创建具有内在比率的框，您需要做的就是对div应用顶部或底部填充：

```css
.容器 {
  高度：0；
  底部填充：20％；
  职位：相对
}

.container div {
  border: 2px dashed #ddd;
  高度：100％;
  左：0；
  位置：绝对；
  最高：0;
  宽度：100％;
}
```

使用20％的填充使框的高度等于其宽度的20％. 无论视口的宽度如何，子div都将保持其宽高比（100％/ 20％= 5：1）.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALZvE)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style Broken Images

只需一点CSS，就可以使破碎的图像更加美观.

```css
img {
  显示：块；
  字体家族：sans-serif;
  字体粗细：300；
  高度：自动；
  行高：2；
  职位：相对
  文本对齐：居中；
  宽度：100％;
}
```

现在添加伪元素规则以显示用户消息和损坏图像的URL参考：

```css
img ::之前{
  内容：“很抱歉，以下图片已损坏:(”;
  显示：块；
  底边距：10px;
}

img ::之后{
  内容：“（URL：” attr（src）“）”;
  显示：块；
  font-size：12px;
}
```

在中了解有关此样式的样式的更多信息 [Ire Aderinokun](https://github.com/ireade/)'s [original post](http://bitsofco.de/styling-broken-images/).

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `rem` for Global Sizing; Use `em` for Local Sizing

在根处设置基本字体大小（`html {font-size：100％;}`）之后，将文本元素的字体大小设置为`em`：

```css
h2 {
  字号：2em；
}

p {
  字号：1em；
}
```

然后将模块的字体大小设置为`rem`：

```css
文章{
  font-size：1.25rem;
}

除了.module {
  font-size：.9rem;
}
```

现在，每个模块都被分隔开了，更易于样式设计，更易于维护和灵活.

<sup>[back to table of contents](#table-of-contents)</sup>


### Hide Autoplay Videos That Aren't Muted

对于自定义用户样式表而言，这是一个绝妙的技巧. 避免使用户在加载页面时从视频中自动播放的视频中过载. 如果声音没有被静音，请不要显示视频：

```css
video [autoplay]：not（[muted]）{
  显示：无；
}
```

再一次，我们利用了 [`:not()`](#use-not-to-applyunapply-borders-on-navigation) 伪类.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:root` for Flexible Type

响应式布局中的字体大小应能够随每个视口调整. 您可以使用`：root`根据视口的高度和宽度来计算字体大小：

```css
：根 {
  字体大小：calc（1vw + 1vh + .5vmin）;
}
```

现在，您可以根据：root所计算出的值来利用root em单位：

```css
身体 {
  字体：1rem / 1.6 sans-serif;
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/XKgOkR)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `font-size` on Form Elements for a Better Mobile Experience

为了避免移动浏览器（iOS Safari等）在出现“<select>点击下拉菜单，在选择器规则中添加font-size：

```css
input[type="text"],
input[type="number"],
select,
textarea {
  font-size：16px;
}
```

:dancer:

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Pointer Events to Control Mouse Events

[Pointer events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events) 允许您指定鼠标如何与它所触摸的元素交互. 例如，要禁用按钮上的默认指针事件：

```css
.button-disabled {
  不透明度：.5；
  指针事件：无；
}
```

就这么简单.

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `display: none` on Line Breaks Used as Spacing

As [Harry Roberts pointed out](https://twitter.com/csswizardry/status/1170835532584235008)，这有助于防止CMS用户使用多余的换行符来分隔空格：

```css
br + br {
  显示：无；
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


## Support

Chrome，Firefox，Safari，Opera，Edge和IE11的当前版本.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

* [简体中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-CN)
* [正體中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-TW)
* [Deutsch](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/de-DE)
* [Español](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/fr-FR)
* [ગુજરાતી](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gu-IND)
* [हिन्दी](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/hi-IND)
* [Italiano](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/it-IT)
* [日本語](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ja-JP)
* [한국어](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ko-KR)
* [Polskie](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pl-PL)
* [Português do Brasil](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-BR)
* [Português do Europe](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-PT)
* [Русский](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ru-RU)
* [Tiếng Việt](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/vn-VN)

<sup>[back to table of contents](#table-of-contents)</sup>
