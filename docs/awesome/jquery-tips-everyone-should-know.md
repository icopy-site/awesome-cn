## jQuery Tips Everyone Should Know [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一组简单的技巧，以帮助您的jQuery游戏.

&gt;对于其他伟大的名单，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).


## Table of Contents

* [Tips](#tips)
* [Support](#support)
* [Translations](#translations)
* [Contribution Guidelines](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/blob/master/CONTRIBUTING.md)


## Tips

1. [Use `noConflict()`](#use-noconflict)
1. [Checking If jQuery Loaded](#checking-if-jquery-loaded)
1. [Use `.on()` Binding Instead of `.click()`](#use-on-binding-instead-of-click)
1. [Back to Top Button](#back-to-top-button)
1. [Preload Images](#preload-images)
1. [Checking If Images Are Loaded](#checking-if-images-are-loaded)
1. [Fix Broken Images Automatically](#fix-broken-images-automatically)
1. [Post a Form with AJAX](#post-a-form-with-ajax)
1. [Toggle Classes on Hover](#toggle-classes-on-hover)
1. [Disabling Input Fields](#disabling-input-fields)
1. [Stop the Loading of Links](#stop-the-loading-of-links)
1. [Cache jQuery Selectors](#cache-jquery-selectors)
1. [Toggle Fade/Slide](#toggle-fadeslide)
1. [Simple Accordion](#simple-accordion)
1. [Make Two Divs the Same Height](#make-two-divs-the-same-height)
1. [Open External Links in New Tab/Window](#open-external-links-in-new-tabwindow)
1. [Find Element By Text](#find-element-by-text)
1. [Trigger on Visibility Change](#trigger-on-visibility-change)
1. [AJAX Call Error Handling](#ajax-call-error-handling)
1. [Chain Plugin Calls](#chain-plugin-calls)
1. [Sort List Items Alphabetically](#sort-list-items-alphabetically)
1. [Disable Right-Click](#disable-right-click)


### Use `noConflict()`

 jQuery使用的`$`别名也被其他JavaScript库使用.  要确保jQuery不与不同库的`$`对象冲突，请在文档的开头使用`noConflict（）`方法：

```javascript
jQuery.noConflict();
```

 现在你将使用`jQuery`变量名而不是`$`来引用jQuery对象（例如，`jQuery（&#39;div p&#39;）.hide（）`）.  如果在同一页面上有多个版本的jQuery（不推荐），可以使用`noConflict（）`为特定版本设置别名：

```javascript
let $ x = jQuery.noConflict（）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If jQuery Loaded

在使用jQuery做任何事情之前，首先需要确定它已加载：

```javascript
if（typeof jQuery ==&#39;undefined&#39;）{
  console.log（&#39;jQuery还没有加载&#39;）;
} else {
  console.log（&#39;jQuery has loaded&#39;）;
}
```

现在你离开了......

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `.on()` Binding Instead of `.click()`

使用`.on（）`比使用`.click（）`有一些优势，例如添加多个事件的能力......

```javascript
.on（&#39;点击点击悬停&#39;）
```

...绑定也适用于动态创建的元素（不需要手动绑定动态添加到DOM元素的每个元素）...

...以及设置命名空间的可能性：

```javascript
.on('click.menuOpening')
```

命名空间使您能够解除特定事件的绑定（例如，`.off（&#39;click.menuOpening&#39;）`）.

<sup>[back to table of contents](#table-of-contents)</sup>


### Back to Top Button

通过在jQuery中使用`animate`和`scrollTop`方法，您不需要插件来创建简单的滚动到顶部动画：

```javascript
// 回到顶部
$（&#39;.container&#39;）.on（&#39;click&#39;，&#39;.back-to-top&#39;，function（e）{
  e.preventDefault（）;
  $（&#39;html，body&#39;）.animate（{scrollTop：0}，800）;
});
```

```html
<!-- Create an anchor tag -->
<div class="container">
  <a href="#" class="back-to-top">Back to top</a>
</div>
```

 更改`scrollTop`值会更改滚动条着陆的位置.  所有你真正做的是在800毫秒的过程中动画文档的主体，直到它滚动到文档的顶部.

**注意：**注意一些 [buggy behavior](https://github.com/jquery/api.jquery.com/issues/417) 用`scrollTop`.

<sup>[back to table of contents](#table-of-contents)</sup>


### Preload Images

如果您的网页使用了许多最初不可见的图像（例如，在悬停时），则预加载它们是有意义的：

```javascript
$ .preloadImages = function（）{
  for（is i = 0; in &lt;arguments.length; i ++）{
     $（” <img>  &#39;）.attr（&#39;src&#39;，arguments [i]）;
  }
};

$ .preloadImages（&#39;img / hover-on.png&#39;，&#39;img / hover-off.png&#39;）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If Images Are Loaded

有时您可能需要检查图像是否已完全加载才能继续使用脚本：

```javascript
$（&#39;img&#39;）.on（&#39;load&#39;，function（）{
  console.log（&#39;image load successful&#39;）;
});
```

 您还可以通过替换`来检查是否已加载一个特定图像 <img>  带有ID或类的标签.

<sup>[back to table of contents](#table-of-contents)</sup>


### Fix Broken Images Automatically

 如果您碰巧在您的网站上发现了破损的图片链接，那么逐个替换它们可能会很痛苦.  这段简单的代码可以省去很多麻烦：

```javascript
$（&#39;img&#39;）.on（&#39;error&#39;，function（）{
  if（！$（this）.hasClass（&#39;broken-image&#39;））{
    $（this）.prop（&#39;src&#39;，&#39;img / broken.png&#39;）.addClass（&#39;broken-image&#39;）;
  }
});
```

或者，如果您希望隐藏损坏的图像，此片段将处理以下内容：

```javascript
$（&#39;img&#39;）.on（&#39;error&#39;，function（）{
  $（本）.hide（）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Post a Form with AJAX

 jQuery AJAX方法是请求文本，HTML，XML或JSON的常用方法.  如果您想通过AJAX发送表单，可以通过`val（）`方法收集用户输入：

```javascript
$ .post（&#39;sign_up.php&#39;，{
  user_name：$（&#39;input [name = user_name]&#39;）.val（），
  电子邮件：$（&#39;input [name = email]&#39;）.val（），
  密码：$（&#39;input [name = password]&#39;）.val（），
});
```

 但是所有这些`val（）`调用都很昂贵并在`上使用`.val（）` <textarea>  `elements将从浏览器报告的值中删除回车符.  收集用户输入的更好方法是使用`serialize（）`函数将它们收集为字符串：

```javascript
$.post('sign_up', $('#sign-up-form').serialize());
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Classes on Hover

 假设您希望在用户将鼠标悬停在页面上时更改页面上可点击元素的视觉效果.  您可以在用户悬停时向元素添加类;  当用户停止悬停时删除该类：

```javascript
$（&#39;.btn&#39;）.on（&#39;hover&#39;，function（）{
  $（本）.addClass（ &#39;悬停&#39;）;
，function（）{
  $（本）.removeClass（ &#39;悬停&#39;）;
});
```

 您需要添加必要的CSS.  如果你想要一个偶数_simpler_方式使用`toggleClass`方法：

```javascript
$（&#39;.btn&#39;）.on（&#39;hover&#39;，function（）{
  $（本）.toggleClass（ &#39;悬停&#39;）;
});
```

**注意：**在这种情况下，CSS可能是一个更快的解决方案，但仍然值得知道这一点.

<sup>[back to table of contents](#table-of-contents)</sup>


### Disabling Input Fields

 有时您可能希望禁用表单或其文本输入之一的提交按钮，直到用户执行了某个操作（例如，选中“我已阅读术语”复选框）.  将“disabled”属性添加到输入中，以便在需要时启用它：

```javascript
$（&#39;input [type =“submit”]&#39;）.prop（&#39;disabled&#39;，true）;
```

您需要做的就是在输入上再次运行`prop`方法，但将`disabled`的值设置为`false`：

```javascript
$（&#39;input [type =“submit”]&#39;）.prop（&#39;disabled&#39;，false）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Stop the Loading of Links

 有时您不希望链接转到某个网页，也不想重新加载页面;  你可能希望他们做其他事情，比如触发另一个脚本.  这样可以防止默认操作：

```javascript
$（&#39;a.no-link&#39;）.on（&#39;click&#39;，function（e）{
  e.preventDefault（）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Cache jQuery Selectors

 想想在任何项目中反复编写相同选择器的次数.  每个`$（&#39;.element&#39;）`选择器必须每次搜索整个DOM，无论该选择器是否先前运行过.  相反，您可以运行一次选择器并将结果存储在变量中：

```javascript
var blocks = $('#blocks').find('li');
```

现在，您可以在任何地方使用`blocks`变量，而无需每次都搜索DOM：

```javascript
$('#hideBlocks').on('click', function () {
  blocks.fadeOut（）;
});

$('#showBlocks').on('click', function () {
  blocks.fadeIn（）;
});
```

缓存jQuery选择器是一个很好的性能提升.

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Fade/Slide

 使用jQuery动画中常见滑动和褪色.  您可能希望在用户单击某个内容时显示一个元素，这使得`fadeIn`和`slideDown`方法完美无缺，但如果您希望该元素在第一次单击时出现然后在第二次单击时消失，则可以正常工作：

```javascript
// 褪色
$（&#39;.btn&#39;）.on（&#39;click&#39;，function（）{
  $（ &#39;元素 &#39;）fadeToggle（&#39; 慢&#39;）;
});

//切换
$（&#39;.btn&#39;）.on（&#39;click&#39;，function（）{
  $（ &#39;元素 &#39;）的slideToggle（&#39; 慢&#39;）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Simple Accordion

这是一种快速手风琴的简单方法：

```javascript
//关闭所有面板
$('#accordion').find('.content').hide();

//手风琴
$('#accordion').find('.accordion-header').on('click', function () {
  var next = $（this）.next（）;
  next.slideToggle（ &#39;快&#39;）;
  $（ &#39;内容 &#39;）没有（下）.slideUp（&#39; 快&#39;）.
  返回false;
});
```

通过添加此脚本，您在网页上真正需要做的就是获得此功能所必需的HTML.

<sup>[back to table of contents](#table-of-contents)</sup>


### Make Two Divs the Same Height

有时你会想要两个div具有相同的高度，无论它们有什么内容：

```javascript
$（&#39;.div&#39;）.css（&#39;min-height&#39;，$（&#39;.main-div&#39;）.height（））;
```

 这个例子设置了&#39;min-height`，这意味着它可以比主div大，但从不小.  但是，更灵活的方法是循环遍历一组元素并将“height”设置为最高元素的高度：

```javascript
var $ columns = $（&#39;.column&#39;）;
var height = 0;
$ columns.each（function（）{
  if（$（this）.height（）&gt; height）{
    height = $（this）.height（）;
  }
});
$columns.height(height);
```

如果希望_all_列具有相同的高度：

```javascript
var $ rows = $（&#39;.same-height-columns&#39;）;
$ rows.each（function（）{
  $（本）.find（ &#39;列&#39;）的高度（$（本）.height（））.
});
```

**注意：**这可以通过多种方式完成 [in CSS](http://codepen.io/AllThingsSmitty/pen/KMPqoO) 但是根据你的需求，知道如何在jQuery中执行此操作非常方便.

<sup>[back to table of contents](#table-of-contents)</sup>


### Open External Links in New Tab/Window

在新的浏览器选项卡或窗口中打开外部链接，并确保在同一选项卡或窗口中打开同一来源的链接：

```javascript
$（&#39;a [href ^ =“http”]&#39;）.attr（&#39;target&#39;，&#39;_ blank&#39;）;
$（&#39;a [href ^ =“//”]&#39;）.attr（&#39;target&#39;，&#39;_ blank&#39;）;
$（&#39;a [href ^ =“&#39;+ window.location.origin +&#39;”]&#39;）.attr（&#39;target&#39;，&#39;_ self&#39;）;
```

**注意：**`window.location.origin`在IE10中不起作用. [This fix](http://tosbourn.com/a-fix-for-window-location-origin-in-internet-explorer/) 处理这个问题.

<sup>[back to table of contents](#table-of-contents)</sup>


### Find Element By Text

 通过在jQuery中使用`contains（）`选择器，您可以在元素的内容中找到文本.  如果文本不存在，则隐藏该元素：

```javascript
var search = $('#search').val();
$（&#39;div：not（：contains（“&#39;+ search +&#39;”））&#39;）.hide（）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Trigger on Visibility Change

当用户不再关注选项卡或重新选择选项卡时触发JavaScript：

```javascript
$（document）.on（&#39;visibilitychange&#39;，function（e）{
  if（e.target.visibilityState ===&#39;visible&#39;）{
    console.log（&#39;Tab现在在视图中！&#39;）;
  } else if（e.target.visibilityState ===&#39;hidden&#39;）{
    console.log（&#39;Tab现在隐藏！&#39;）;
  }
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### AJAX Call Error Handling

 当AJAX调用返回404或500错误时，将执行错误处理程序.  如果未定义处理程序，则其他jQuery代码可能无法按预期工作.  要定义全局AJAX错误处理程序：

```javascript
$（document）.on（&#39;ajaxError&#39;，function（e，xhr，settings，error）{
  的console.log（误差）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Chain Plugin Calls

 jQuery允许插件方法调用的“链接”，以减轻重复查询DOM和创建多个jQuery对象的过程.  假设以下代码片段代表您的插件方法调用：

```javascript
$('#elem').show();
$('#elem').html('bla');
$('#elem').otherStuff();
```

使用链接可以大大改善这一点：

```javascript
$('#elem')
  .节目（）
  .html（&#39;bla&#39;）
  .其他的东西（）;
```

另一种方法是将元素缓存在变量中（前缀为`$`）：

```javascript
var $elem = $('#elem');
$elem.hide();
$elem.html('bla');
$elem.otherStuff();
```

链接和 [caching](#cache-jquery-selectors) jQuery中的方法是导致代码更短更快的最佳实践.

<sup>[back to table of contents](#table-of-contents)</sup>


### Sort List Items Alphabetically

 假设您最终在列表中包含太多项目.  也许内容是由CMS生成的，您希望按字母顺序排序：

```javascript
var ul = $('#list'),
lis = $（&#39;li&#39;，ul）.get（）;

lis.sort（function（a，b）{
   return（$（a）.text（）.toUpperCase（）&lt;$（b）.text（）.toUpperCase（））？  -1：1;
});

ul.append(lis);
```

你去！

<sup>[back to table of contents](#table-of-contents)</sup>


### Disable Right-Click

如果要禁用右键单击，则可以对整个页面执行此操作...

```javascript
$（document）.ready（function（）{
  $（document）.bind（&#39;contextmenu&#39;，function（e）{
    返回false;
  })
})
```

......你也可以为特定元素做同样的事情：

```javascript
$（document）.ready（function（）{
  $('#submit').bind('contextmenu', function (e) {
    返回false;
  })
})
```

<sup>[back to table of contents](#table-of-contents)</sup>


## Support

当前版本的Chrome，Firefox，Safari，Opera，Edge和IE11.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

* [Español](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/fr-FR)
* [Magyar](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/hu-HU)
* [Português do Europe](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/pt-PT)
* [Pусский](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ru-RU)
* [简体中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-CN)
* [繁體中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-TW)

<sup>[back to table of contents](#table-of-contents)</sup>
