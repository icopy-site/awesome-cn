<p align="center">
  <img src="https://rawgit.com/AllThingsSmitty/css-protips/master/media/logo.svg" width="200" alt="light bulb icon">
</p>

## CSS Protips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一系列提示，帮助您掌握CSS技能.

&gt;对于其他伟大的名单，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).


## Table of Contents

* [Protips](#protips)
* [Support](#support)
* [Translations](#translations)
* [Contribution Guidelines](https://github.com/AllThingsSmitty/css-protips/blob/master/CONTRIBUTING.md)


## Protips

1. [Use a CSS Reset](#use-a-css-reset)
1. [Inherit `box-sizing`](#inherit-box-sizing)
1. [Use `unset` Instead of Resetting All Properties](#use-unset-instead-of-resetting-all-properties)
1. [Use `:not()` to Apply/Unapply Borders on Navigation](#use-not-to-applyunapply-borders-on-navigation)
1. [Add `line-height` to `body`](#add-line-height-to-body)
1. [Set `:focus` for Form Elements](#set-focus-for-form-elements)
1. [Vertically-Center Anything](#vertically-center-anything)
1. [Comma-Separated Lists](#comma-separated-lists)
1. [Select Items Using Negative `nth-child`](#select-items-using-negative-nth-child)
1. [Use SVG for Icons](#use-svg-for-icons)
1. [Use the "Lobotomized Owl" Selector](#use-the-lobotomized-owl-selector)
1. [Use `max-height` for Pure CSS Sliders](#use-max-height-for-pure-css-sliders)
1. [Equal-Width Table Cells](#equal-width-table-cells)
1. [Get Rid of Margin Hacks With Flexbox](#get-rid-of-margin-hacks-with-flexbox)
1. [Use Attribute Selectors with Empty Links](#use-attribute-selectors-with-empty-links)
1. [Style "Default" Links](#style-default-links)
1. [Consistent Vertical Rhythm](#consistent-vertical-rhythm)
1. [Intrinsic Ratio Boxes](#intrinsic-ratio-boxes)
1. [Style Broken Images](#style-broken-images)
1. [Use `rem` for Global Sizing; Use `em` for Local Sizing](#use-rem-for-global-sizing-use-em-for-local-sizing)
1. [Hide Autoplay Videos That Aren't Muted](#hide-autoplay-videos-that-arent-muted)
1. [Use `:root` for Flexible Type](#use-root-for-flexible-type)
1. [Set `font-size` on Form Elements for a Better Mobile Experience](#set-font-size-on-form-elements-for-a-better-mobile-experience)
1. [Use Pointer Events to Control Mouse Events](#use-pointer-events-to-control-mouse-events)


### Use a CSS Reset

 CSS重置有助于在不同的浏览器中实现样式一致性，并为样式元素提供干净的平板.  您可以使用CSS重置库 [Normalize](http://necolas.github.io/normalize.css/)，_et al._，或者您可以使用更简化的重置方法：

```css
*,
*::before,
* :: after {
  box-sizing：border-box;
  保证金：0;
  填充：0;
}
```

现在元素将被剥离边距和填充，“box-sizing”允许您使用CSS框模型管理布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/kkrkLL)

**注意：**如果您遵循 [Inherit `box-sizing`](#inherit-box-sizing) 您可以选择不在CSS重置中包含`box-sizing`属性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Inherit `box-sizing`

让`box-sizing`继承自`html`：

```css
html {
  box-sizing：border-box;
}

*,
*::before,
* :: after {
  box-sizing：inherit;
}
```

这样可以更容易地更改插件或其他利用其他行为的组件中的“box-sizing”.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `unset` Instead of Resetting All Properties

重置元素的属性时，不必重置每个属性：

```css
按钮{
  背景：无;
  border：none;
  颜色：继承;
  font：inherit;
  大纲：无;
  填充：0;
}
```

 您可以使用`all`简写指定所有元素的属性.  将值设置为“unset”会将元素的属性更改为其初始值：

```css
按钮{
  全部：未设置;
}
```

 **注意：** IE11不支持`all`简写，目前正在考虑Edge中的支持.  IE11不支持`unset`.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:not()` to Apply/Unapply Borders on Navigation

而不是放在边境......

```css
/ *添加边框* /
.nav li {
  border-right: 1px solid #666;
}
```

......然后把它从最后一个元素中取出......

```css
/ *删除边框* /
.nav li：last-child {
  border-right：none;
}
```

...使用`：not（）`伪类仅适用于您想要的元素：

```css
.nav li：not（：last-child）{
  border-right: 1px solid #666;
}
```

当然，您可以使用`.nav li + li`，但使用`：not（）`意图非常明确，CSS选择器按照人类描述它的方式定义边界.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/LkymvO)

<sup>[back to table of contents](#table-of-contents)</sup>


### Add `line-height` to `body`

 你不需要为每个`添加`line-height` <p>  `，` <h*>  `，_et al_.  分别.  相反，将它添加到`body`：

```css
身体 {
  线高：1.5;
}
```

这样文本元素就可以轻松地从`body`继承.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/VjbdYd)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `:focus` for Form Elements

 有视力的键盘用户依靠焦点来确定键盘事件在页面中的位置.  使表单元素的焦点脱颖而出，与浏览器的默认实现保持一致：

```css
a:focus,
button:focus,
input:focus,
select:focus,
textarea：focus {
  box-shadow：none;
  outline: #000 dotted 2px;
  outline-offset：.05em;
}
```

#### [Demo](https://codepen.io/AllThingsSmitty/pen/ePzoOP/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Vertically-Center Anything

 不，这不是黑魔法，你真的可以垂直居中.  你可以用flexbox做到这一点......

```css
html,
身体 {
  身高：100％;
  保证金：0;
}

身体 {
  -webkit-align-items：center;
  -ms-flex-align：center;
  align-items：center;
  display：-webkit-flex;
  显示：flex;
}
```

...还有CSS Grid：

```css
身体 {
  显示：网格;
  身高：100vh;
  保证金：0;
  地方物品：中心;
}
```


 想要集中其他东西？  垂直，水平......任何时间，任何地点？  CSS-Tricks有 [a nice write-up](https://css-tricks.com/centering-css-complete-guide/) 做所有这些.

**注意：**注意一些 [buggy behavior](https://github.com/philipwalton/flexbugs#3-min-height-on-a-flex-container-wont-apply-to-its-flex-items) 在IE11中使用flexbox.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/GqmGqZ)

<sup>[back to table of contents](#table-of-contents)</sup>


### Comma-Separated Lists

使列表项看起来像一个真实的逗号分隔列表：

```css
ul&gt; li：not（：last-child）:: after {
  内容：“，”;
}
```

使用`：not（）`伪类，并且不会在最后一项中添加逗号.

 **注意：**此提示可能不适用于辅助功能，特别是屏幕阅读器.  从浏览器复制/粘贴不适用于CSS生成的内容.  谨慎行事.

<sup>[back to table of contents](#table-of-contents)</sup>


### Select Items Using Negative `nth-child`

在CSS中使用否定的&#39;nth-child`来选择项目1到n.

```css
li {
  display：none;
}

/ *选择项目1到3并显示它们* /
li：nth-​​child（-n + 3）{
  display: block;
}
```

或者，因为你已经学到了一些东西 [using `:not()`](#use-not-to-applyunapply-borders-on-navigation)，尝试：

```css
/ *选择除前3个以外的所有项目并显示它们* /
li：not（：nth-​​child（-n + 3））{
  display: block;
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/WxjKZp)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use SVG for Icons

没有理由不将SVG用于图标：

```css
.商标 {
  background：url（“logo.svg”）;
}
```

SVG适用于所有分辨率类型，并且在所有浏览器中均受支持 [back to IE9](http://caniuse.com/#search=svg) .  丢弃你的.png，.jpg或.gif-jif-whatev文件.

**注意：**如果您有视觉用户的SVG图标专用按钮且SVG无法加载，这将有助于保持可访问性：

```css
.no-svg .icon-only :: after {
  内容：attr（aria-label）;
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use the "Lobotomized Owl" Selector

它可能有一个奇怪的名称，但使用通用选择器（`*`）与相邻的兄弟选择器（`+`）可以提供强大的CSS功能：

```css
* + * {
  margin-top：1.5em;
}
```

在此示例中，文档流程中跟随其他元素的所有元素都将收到`margin-top：1.5em`.

有关“lobotomized owl”选择器的更多信息，请阅读 [Heydon Pickering's post](http://alistapart.com/article/axiomatic-css-and-lobotomized-owls) 在* A List Apart *.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/grRvWq)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `max-height` for Pure CSS Sliders

使用带有溢出隐藏的`max-height`实现仅限CSS的滑块：

```css
.slider {
  最大高度：200px;
  溢出y：隐藏;
  宽度：300px;
}

.slider：悬停{
  最大高度：600px;
  overflow-y：scroll;
}
```

悬停时元素会扩展为“max-height”值，滑块会显示滑块.

<sup>[back to table of contents](#table-of-contents)</sup>


### Equal-Width Table Cells

 表可能是一种痛苦的工作.  尝试使用`table-layout：fixed`来保持单元格宽度相等：

```css
.calendar {
  table-layout：fixed;
}
```

无痛的桌面布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALALm)

<sup>[back to table of contents](#table-of-contents)</sup>


### Get Rid of Margin Hacks With Flexbox

当使用列排水沟时，你可以通过使用flexbox的`space-between`属性来摆脱`nth -`，`first -`和`last-child` hacks：

```css
.list {
  显示：flex;
  辩解内容：空间 - 间隔;
}

.list .person {
  弹性基础：23％;
}
```

现在，柱状排水沟总是呈现均匀间隔.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Attribute Selectors with Empty Links

当` <a>`元素没有文本值但`href`属性有链接时显示链接：</a>

```css
a [href ^ =“http”]：empty :: before {
  内容：attr（href）;
}
```

这很方便.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/zBzXRx)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style "Default" Links

为“默认”链接添加样式：

```css
a [href]：not（[class]）{
  color: #008000;
  文字装饰：下划线;
}
```

现在通过CMS插入的链接（通常不具有“class”属性）将具有区别，而不会对级联产生一般影响.

<sup>[back to table of contents](#table-of-contents)</sup>


### Consistent Vertical Rhythm

在元素中使用通用选择器（`*`）来创建一致的垂直节奏：

```css
.intro&gt; * {
  保证金底部：1.25rem;
}
```

一致的垂直节奏提供了视觉美感，使内容更具可读性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Intrinsic Ratio Boxes

要创建具有固有比率的框，您需要做的就是将顶部或底部填充应用于div：

```css
.容器 {
  身高：0;
  填充底部：20％;
  位置：相对;
}

.container div {
  border: 2px dashed #ddd;
  身高：100％;
  左：0;
  位置：绝对;
  顶部：0;
  宽度：100％;
}
```

 使用20％进行填充使得框的高度等于其宽度的20％.  无论视口的宽度如何，子div都将保持其纵横比（100％/ 20％= 5：1）.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALZvE)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style Broken Images

使用一点CSS使破碎的图像更美观：

```css
img {
  display: block;
  font-family：sans-serif;
  font-weight：300;
  身高：自动;
  行高：2;
  位置：相对;
  text-align：center;
  宽度：100％;
}
```

现在添加伪元素规则以显示损坏图像的用户消息和URL引用：

```css
img :: before {
  内容：“我们很抱歉，下图是坏的:(”;
  display: block;
  margin-bottom：10px;
}

img :: after {
  内容：“（url：”attr（src）“）”;
  display: block;
  font-size：12px;
}
```

了解有关此模式样式的更多信息 [Ire Aderinokun](https://github.com/ireade/)'s [original post](http://bitsofco.de/styling-broken-images/).

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `rem` for Global Sizing; Use `em` for Local Sizing

在根目录（`html {font-size：100％;}`）设置基本字体大小后，将文本元素的字体大小设置为`em`：

```css
h2 {
  font-size：2em;
}

p {
  font-size：1em;
}
```

然后将模块的font-size设置为`rem`：

```css
文章{
  font-size：1.25rem;
}

旁边.module {
  font-size：.9rem;
}
```

现在每个模块都变得分割，更容易设计，更易于维护和灵活.

<sup>[back to table of contents](#table-of-contents)</sup>


### Hide Autoplay Videos That Aren't Muted

 这对于自定义用户样式表来说是一个很好的技巧.  避免在加载页面时使用自动播放的视频中的声音使用户超载.  如果声音没有静音，请不要显示视频：

```css
video [autoplay]：not（[muted]）{
  display：none;
}
```

再一次，我们正在利用这个 [`:not()`](#use-not-to-applyunapply-borders-on-navigation) 伪类.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:root` for Flexible Type

 响应式布局中的字体大小应该能够随每个视口进行调整.  您可以使用`：root`根据视口高度和宽度计算字体大小：

```css
：根 {
  font-size：calc（1vw + 1vh + .5vmin）;
}
```

现在你可以根据`：root`计算的值来使用`root em`单元：

```css
身体 {
  做：1rem / 1.6 sans-serif;
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/XKgOkR)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `font-size` on Form Elements for a Better Mobile Experience

 为了避免移动浏览器（iOS Safari，_et al_.）在放大HTML表单元素时使用` <select>点击“下拉列表”，将“font-size”添加到选择器规则：

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

[Pointer events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events)  允许您指定鼠标如何与其触摸的元素进行交互.  要禁用按钮上的默认指针事件，例如：

```css
.button-disabled {
  不透明度：.5;
  pointer-events：none;
}
```

就这么简单.

<sup>[back to table of contents](#table-of-contents)</sup>


## Support

当前版本的Chrome，Firefox，Safari，Opera，Edge和IE11.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

* [简体中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-CN)
* [正體中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-TW)
* [Deutsche](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/de-DE)
* [Español](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/fr-FR)
* [ગુજરાતી](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gu-IND)
* [Italiano](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/it-IT)
* [日本語](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ja-JP)
* [한국어](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ko-KR)
* [Polskie](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pl-PL)
* [Português do Brasil](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-BR)
* [Português do Europe](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-PT)
* [Русский](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ru-RU)

<sup>[back to table of contents](#table-of-contents)</sup>
