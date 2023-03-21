<div class="github-widget" data-repo="AllThingsSmitty/jquery-tips-everyone-should-know"></div>
## jQuery Tips Everyone Should Know [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

帮助您玩 jQuery 游戏的一系列简单技巧.

&gt; 对于其他很棒的列表，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).



* [Contribution Guidelines](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/blob/master/CONTRIBUTING.md)


## Tips



### Use `noConflict()`

 jQuery 使用的 `$` 别名也被其他 JavaScript 库使用. 为确保 jQuery 不与不同库的 `$` 对象冲突，请在文档开头使用 `noConflict()` 方法：

```javascript
jQuery.noConflict();
```

现在，您将使用 `jQuery` 变量名而不是 `$`（例如，`jQuery(&#39;div p&#39;).hide()`）来引用 jQuery 对象. 如果您在同一页面上有多个版本的 jQuery（不推荐），您可以使用 `noConflict()` 为特定版本设置别名：

```javascript
让 $x = jQuery.noConflict();
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If jQuery Loaded

在你可以使用 jQuery 做任何事情之前，你首先需要确定它已经加载：

```javascript
如果（typeof jQuery == &#39;undefined&#39;）{
  console.log(&#39;jQuery 还没有加载&#39;);
} 别的 {
  console.log(&#39;jQuery 已经加载&#39;);
}
```

现在你走了...

<sup>[back to table of contents](#table-of-contents)</sup>


### Check Whether an Element Exists

在使用 HTML 元素之前，您需要确保它是 DOM 的一部分.

```javascript
if ($("#selector").length) {
  //用元素做点什么
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `.on()` Binding Instead of `.click()`

使用 `.on()` 比使用 `.click()` 有几个优势，例如添加多个事件的能力......

```javascript
.on(&#39;点击悬停&#39;)
```

...绑定也适用于动态创建的元素（无需手动绑定每个动态添加到 DOM 元素的元素）...

...以及设置命名空间的可能性：

```javascript
.on('click.menuOpening')
```

命名空间赋予您取消绑定特定事件的能力（例如，`.off(&#39;click.menuOpening&#39;)`）.

<sup>[back to table of contents](#table-of-contents)</sup>


### Back to Top Button

通过使用 jQuery 中的 `animate` 和 `scrollTop` 方法，您不需要插件来创建简单的滚动到顶部的动画：

```javascript
// 回到顶部
$(&#39;.container&#39;).on(&#39;click&#39;, &#39;.back-to-top&#39;, function (e) {
  e.preventDefault();
  $(&#39;html, body&#39;).animate({scrollTop: 0}, 800);
});
```

```html
<!-- Create an anchor tag -->
<div class="container">
  <a href="#" class="back-to-top">Back to top</a>
</div>
```

更改 `scrollTop` 值会更改您希望滚动条着陆的位置. 您真正要做的是在整个 800 毫秒的过程中为文档主体设置动画，直到它滚动到文档顶部.

**注意：**注意一些 [buggy behavior](https://github.com/jquery/api.jquery.com/issues/417) 与 `scrollTop`.

<sup>[back to table of contents](#table-of-contents)</sup>


### Preload Images

如果您的网页使用了很多最初不可见的图像（例如，在悬停时），那么预加载它们是有意义的：

```javascript
$.preloadImages = 函数 () {
  对于 (var i = 0; i &lt; arguments.length; i++) {
     $(&#39;<img>  &#39;).attr(&#39;src&#39;, 参数[i]);
  }
};

$.preloadImages(&#39;img/hover-on.png&#39;, &#39;img/hover-off.png&#39;);
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If Images Are Loaded

有时您可能需要检查图像是否已完全加载以便继续执行脚本：

```javascript
$(&#39;img&#39;).on(&#39;加载&#39;, 函数 () {
  console.log(&#39;图片加载成功&#39;);
});
```

您还可以通过替换 ` 来检查某个特定图像是否已加载<img> ` 带有 ID 或类的标签.

<sup>[back to table of contents](#table-of-contents)</sup>


### Fix Broken Images Automatically

如果您碰巧在您的网站上发现损坏的图像链接，一个一个地替换它们可能会很痛苦. 这段简单的代码可以省去很多麻烦：

```javascript
$(&#39;img&#39;).on(&#39;错误&#39;, 函数 () {
  if(!$(this).hasClass(&#39;图像损坏&#39;)) {
    $(this).prop(&#39;src&#39;, &#39;img/broken.png&#39;).addClass(&#39;broken-image&#39;);
  }
});
```

或者，如果您希望隐藏损坏的图像，此代码段将处理：

```javascript
$(&#39;img&#39;).on(&#39;错误&#39;, 函数 () {
  $(this).hide();
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Post a Form with AJAX

 jQuery AJAX 方法是请求文本、HTML、XML 或 JSON 的常用方法. 如果您想通过 AJAX 发送表单，您可以通过 `val()` 方法收集用户输入：

```javascript
$.post(&#39;sign_up.php&#39;, {
  user_name: $(&#39;input[name=user_name]&#39;).val(),
  电子邮件：$(&#39;input[name=email]&#39;).val(),
  密码：$(&#39;输入[名称=密码]&#39;).val(),
});
```

但是所有这些 `val()` 调用都很昂贵，并且在 ` 上使用 `.val()`<textarea>  ` 元素将从浏览器报告的值中去除回车符. 收集用户输入的更好方法是使用 serialize() 函数，该函数将它们收集为字符串：

```javascript
$.post('sign_up', $('#sign-up-form').serialize());
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Classes on Hover

假设您想要在用户将鼠标悬停在页面上时更改页面上可点击元素的视觉效果. 您可以在用户悬停时向您的元素添加一个类； 当用户停止悬停时删除类：

```javascript
$(&#39;.btn&#39;).on(&#39;悬停&#39;, 函数 () {
  $(this).addClass(&#39;悬停&#39;);
}， 功能 （） {
  $(this).removeClass(&#39;悬停&#39;);
});
```

您需要添加必要的 CSS. 如果你想要一种更_简单_的方法，请使用 `toggleClass` 方法：

```javascript
$(&#39;.btn&#39;).on(&#39;悬停&#39;, 函数 () {
  $(this).toggleClass(&#39;悬停&#39;);
});
```

**注意：** 在这种情况下，CSS 可能是一种更快的解决方案，但仍然值得了解这一点.

<sup>[back to table of contents](#table-of-contents)</sup>


### Disabling Input Fields

At times you may want the submit button of a form or one of its text inputs to be disabled until the user has performed a certain action (e.g., checking the "I've read the terms" checkbox). Add the `disabled` attribute to your input so you can enable it when you want:

```javascript
$(&#39;input[type=&quot;submit&quot;]&#39;).prop(&#39;disabled&#39;, true);
```

您需要做的就是在输入上再次运行 `prop` 方法，但将 `disabled` 的值设置为 `false`：

```javascript
$(&#39;input[type=&quot;submit&quot;]&#39;).prop(&#39;disabled&#39;, false);
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Stop the Loading of Links

有时您不希望链接转到某个网页，也不希望重新加载该页面； 您可能希望他们执行其他操作，例如触发另一个脚本. 这将起到阻止默认操作的作用：

```javascript
$(&#39;a.no-link&#39;).on(&#39;点击&#39;, function (e) {
  e.preventDefault();
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Cache jQuery Selectors

想一想您在任何项目中一遍又一遍地编写相同的选择器有多少次. 每个“$(&#39;.element&#39;)”选择器每次都必须搜索整个 DOM，无论该选择器之前是否运行过. 相反，您可以运行一次选择器并将结果存储在一个变量中：

```javascript
var blocks = $('#blocks').find('li');
```

现在你可以在任何地方使用 `blocks` 变量，而不必每次都搜索 DOM：

```javascript
$('#hideBlocks').on('click', function () {
  块.fadeOut();
});

$('#showBlocks').on('click', function () {
  blocks.fadeIn();
});
```

缓存 jQuery 选择器是一个很好的性能增益.

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Fade/Slide

滑动和淡入淡出在 jQuery 动画中很常见. 您可能希望在用户单击某些内容时显示一个元素，这使得 `fadeIn` 和 `slideDown` 方法非常完美，但如果您希望该元素在第一次单击时出现，然后在第二次单击时消失，这将工作正常：

```javascript
// 褪色
$(&#39;.btn&#39;).on(&#39;点击&#39;, 函数 () {
  $(&#39;.element&#39;).fadeToggle(&#39;慢&#39;);
});

// 切换
$(&#39;.btn&#39;).on(&#39;点击&#39;, 函数 () {
  $(&#39;.element&#39;).slideToggle(&#39;慢&#39;);
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Simple Accordion

这是快速手风琴的简单方法：

```javascript
// 关闭所有面板
$('#accordion').find('.content').hide();

// 手风琴
$('#accordion').find('.accordion-header').on('click', function () {
  var next = $(this).next();
  next.slideToggle(&#39;快速&#39;);
  $(&#39;.content&#39;).not(next).slideUp(&#39;fast&#39;);
  返回假；
});
```

通过添加此脚本，您真正需要在您的网页上做的就是必要的 HTML 以使其正常工作.

<sup>[back to table of contents](#table-of-contents)</sup>


### Make Two Divs the Same Height

有时您会希望两个 div 具有相同的高度，无论它们中包含什么内容：

```javascript
$(&#39;.div&#39;).css(&#39;最小高度&#39;, $(&#39;.main-div&#39;).height());
```

此示例设置了“最小高度”，这意味着它可以大于主 div 但绝不能小于. 然而，更灵活的方法是遍历一组元素并将“height”设置为最高元素的高度：

```javascript
var $columns = $(&#39;.column&#39;);
变种高度= 0;
$columns.each(函数(){
  如果 ($(this).height() &gt; height) {
    height = $(this).height();
  }
});
$columns.height(height);
```

如果您希望 _all_ 列具有相同的高度：

```javascript
var $rows = $(&#39;.same-height-columns&#39;);
$rows.each(函数(){
  $(this).find(&#39;.column&#39;).height($(this).height());
});
```

**注意：** 这可以通过多种方式完成 [in CSS](http://codepen.io/AllThingsSmitty/pen/KMPqoO) 但是根据您的需要，知道如何在 jQuery 中执行此操作很方便.

<sup>[back to table of contents](#table-of-contents)</sup>


### Open External Links in New Tab/Window

在新的浏览器选项卡或窗口中打开外部链接，并确保同一来源的链接在同一选项卡或窗口中打开：

```javascript
$(&#39;a[href^=&quot;http&quot;]&#39;).attr(&#39;target&#39;, &#39;_blank&#39;);
$(&#39;a[href^=&quot;//&quot;]&#39;).attr(&#39;target&#39;, &#39;_blank&#39;);
$(&#39;a[href^=&quot;&#39; + window.location.origin + &#39;&quot;]&#39;).attr(&#39;target&#39;, &#39;_self&#39;);
```

**注意：** `window.location.origin` 在 IE10 中不起作用. [This fix](http://tosbourn.com/a-fix-for-window-location-origin-in-internet-explorer/) 处理这个问题.

<sup>[back to table of contents](#table-of-contents)</sup>


### Find Element By Text

通过在 jQuery 中使用 `contains()` 选择器，您可以在元素的内容中找到文本. 如果文本不存在，该元素将被隐藏：

```javascript
var search = $('#search').val();
$(&#39;div:not(:contains(&quot;&#39; + search + &#39;&quot;))&#39;).hide();
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Trigger on Visibility Change

当用户不再关注选项卡或重新关注选项卡时触发 JavaScript：

```javascript
$(文档).on(&#39;visibilitychange&#39;, function (e) {
  如果（e.target.visibilityState ===&#39;可见&#39;）{
    console.log(&#39;选项卡现在可见！&#39;);
  } else if (e.target.visibilityState === &#39;hidden&#39;) {
    console.log(&#39;Tab 现在隐藏了！&#39;);
  }
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### AJAX Call Error Handling

当 AJAX 调用返回 404 或 500 错误时，将执行错误处理程序. 如果未定义处理程序，其他 jQuery 代码可能无法按预期工作. 要定义全局 AJAX 错误处理程序：

```javascript
$(document).on(&#39;ajaxError&#39;, function (e, xhr, settings, error) {
  控制台日志（错误）；
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Chain Plugin Calls

 jQuery 允许插件方法调用的“链接”，以减轻重复查询 DOM 和创建多个 jQuery 对象的过程. 假设以下代码片段代表您的插件方法调用：

```javascript
$('#elem').show();
$('#elem').html('bla');
$('#elem').otherStuff();
```

这可以通过使用链接得到极大的改善：

```javascript
$('#elem')
  .展示（）
  .html(&#39;bla&#39;)
  .其他的东西（）;
```

另一种方法是将元素缓存在变量中（以“$”为前缀）：

```javascript
var $elem = $('#elem');
$elem.hide();
$elem.html('bla');
$elem.otherStuff();
```

链接和 [caching](#cache-jquery-selectors) jQuery 中的方法是导致代码更短更快的最佳实践.

<sup>[back to table of contents](#table-of-contents)</sup>


### Sort List Items Alphabetically

假设您最终在列表中得到了太多的项目. 也许内容是由 CMS 生成的，你想按字母顺序排列它们：

```javascript
var ul = $('#list'),
lis = $(&#39;li&#39;, ul).get();

lis.sort（函数（a，b）{
  返回 ($(a).text().toUpperCase() &lt; $(b).text().toUpperCase()) ？  -1：1；
});

ul.append(lis);
```

给你！

<sup>[back to table of contents](#table-of-contents)</sup>


### Disable Right-Click

如果你想禁用右键单击，你可以为整个页面做...

```javascript
$(文档).ready(函数(){
  $(文档).bind(&#39;contextmenu&#39;, function (e) {
    返回假；
  })
})
```

...您也可以对特定元素执行相同操作：

```javascript
$(文档).ready(函数(){
  $('#submit').bind('contextmenu', function (e) {
    返回假；
  })
})
```

<sup>[back to table of contents](#table-of-contents)</sup>






## Support

Chrome、Firefox、Safari、Opera、Edge 和 IE11 的当前版本.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

* [български](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/bg-BG)
* [Español](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/fr-FR)
* [Magyar](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/hu-HU)
* [한국어](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ko-KR)
* [Português do Europe](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/pt-PT)
* [Pусский](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ru-RU)
* [简体中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-CN)
* [繁體中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-TW)

<sup>[back to table of contents](#table-of-contents)</sup>
