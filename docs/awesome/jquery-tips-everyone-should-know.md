<div class="github-widget" data-repo="AllThingsSmitty/jquery-tips-everyone-should-know"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## jQuery Tips Everyone Should Know [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一系列简单的技巧可以帮助您开发jQuery游戏.

&gt;有关其他很棒的清单，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).



* [Contribution Guidelines](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/blob/master/CONTRIBUTING.md)


## Tips



### Use `noConflict()`

 jQuery使用的$别名也被其他JavaScript库使用.  为了确保jQuery不会与不同库的$对象冲突，请在文档开头使用noConflict（）方法：

```javascript
jQuery.noConflict();
```

 现在，您将使用jQuery变量名而不是$来引用jQuery对象（例如jQuery（&#39;div p&#39;）.hide（））.  如果同一页面上有多个版本的jQuery（不建议使用），则可以使用`noConflict（）`来为特定版本设置别名：

```javascript
让$ x = jQuery.noConflict（）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If jQuery Loaded

在使用jQuery做任何事情之前，您首先需要确定它已经加载：

```javascript
如果（jQuery的typeof ==&#39;undefined&#39;）{
  console.log（&#39;jQuery尚未加载&#39;）;
}其他{
  console.log（&#39;jQuery已加载&#39;）;
}
```

现在你走了...

<sup>[back to table of contents](#table-of-contents)</sup>


### Check Whether an Element Exists

在使用HTML元素之前，您需要确保它是DOM的一部分.

```javascript
if ($("#selector").length) {
  //用元素做点什么
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `.on()` Binding Instead of `.click()`

与使用.click（）相比，使用.on（）具有多个优点，例如可以添加多个事件...

```javascript
.on（“单击点击悬停”）
```

...绑定也适用于动态创建的元素（无需手动绑定动态添加到DOM元素中的每个元素）...

...以及设置名称空间的可能性：

```javascript
.on('click.menuOpening')
```

命名空间使您可以解除绑定特定事件的能力（例如，.off（&#39;click.menuOpening&#39;）`）.

<sup>[back to table of contents](#table-of-contents)</sup>


### Back to Top Button

通过在jQuery中使用`animate`和`scrollTop`方法，您不需要插件即可创建简单的滚动到顶部的动画：

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

 更改`scrollTop`值会更改您希望滚动条到达的位置.  您真正要做的就是在整个800毫秒的过程中对文档正文进行动画处理，直到滚动到文档顶部.

**注意：**注意一些 [buggy behavior](https://github.com/jquery/api.jquery.com/issues/417) 与`scrollTop`.

<sup>[back to table of contents](#table-of-contents)</sup>


### Preload Images

如果您的网页使用了大量最初不可见的图像（例如，悬停时），则可以预加载它们：

```javascript
$ .preloadImages = function（）{
  for（var i = 0; i &lt;arguments.length; i ++）{
     $（&#39; <img>  &#39;）.attr（&#39;src&#39;，arguments [i]）;
  }
};

$ .preloadImages（&#39;img / hover-on.png&#39;，&#39;img / hover-off.png&#39;）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Checking If Images Are Loaded

有时您可能需要检查图像是否已完全加载才能继续执行脚本：

```javascript
$（&#39;img&#39;）.on（&#39;load&#39;，function（）{
  console.log（&#39;图像加载成功&#39;）;
});
```

 您也可以通过替换`检查特定图片是否已加载. <img>  具有ID或类的`标签.

<sup>[back to table of contents](#table-of-contents)</sup>


### Fix Broken Images Automatically

 如果您发现网站上损坏的图像链接被一个接一个地替换，可能会很痛苦.  这个简单的代码可以省去很多麻烦：

```javascript
$（&#39;img&#39;）.on（&#39;error&#39;，function（）{
  if（！$（this）.hasClass（&#39;broken-image&#39;））{
    $（this）.prop（&#39;src&#39;，&#39;img / broken.png&#39;）.addClass（&#39;broken-image&#39;）;
  }
});
```

另外，如果您希望隐藏损坏的图像，则此代码段将用于以下方面：

```javascript
$（&#39;img&#39;）.on（&#39;error&#39;，function（）{
  $（this）.hide（）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Post a Form with AJAX

 jQuery AJAX方法是请求文本，HTML，XML或JSON的常用方法.  如果您想通过AJAX发送表单，则可以通过val（）方法收集用户输入：

```javascript
$ .post（&#39;sign_up.php&#39;，{
  user_name：$（&#39;input [name = user_name]&#39;）.val（），
  电子邮件：$（&#39;input [name = email]&#39;）.val（），
  密码：$（&#39;input [name = password]&#39;）.val（），
});
```

 但是所有这些`val（）`调用都很昂贵，并且在`上使用`.val（）` <textarea>  `元素将从浏览器报告的值中去除回车符.  收集用户输入的一种更好的方法是使用`serialize（）`函数，该函数将它们收集为字符串：

```javascript
$.post('sign_up', $('#sign-up-form').serialize());
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Classes on Hover

 假设您要在用户将鼠标悬停在页面上时更改页面上可点击元素的外观.  您可以在用户悬停时在您的元素中添加一个类；  当用户停止悬停时，将删除该类：

```javascript
$（&#39;.btn&#39;）.on（&#39;hover&#39;，function（）{
  $（this）.addClass（&#39;hover&#39;）;
}，函数（）{
  $（this）.removeClass（&#39;hover&#39;）;
});
```

 您需要添加必要的CSS.  如果您想使用_simpler_甚至的方式，请使用`toggleClass`方法：

```javascript
$（&#39;.btn&#39;）.on（&#39;hover&#39;，function（）{
  $（this）.toggleClass（&#39;hover&#39;）;
});
```

**注意：**在这种情况下，CSS可能是一个更快的解决方案，但是仍然值得一提.

<sup>[back to table of contents](#table-of-contents)</sup>


### Disabling Input Fields

 有时，您可能希望禁用表单的提交按钮或其文本输入之一，直到用户执行了某些操作（例如，选中“我已经阅读条款”复选框）.  将`disabled`属性添加到您的输入中，以便您可以在需要时启用它：

```javascript
$（&#39;input [type =“ submit”]&#39;）.prop（&#39;disabled&#39;，true）;
```

您需要做的就是再次在输入上运行`prop`方法，但是将`disabled&#39;的值设置为`false`：

```javascript
$（&#39;input [type =“ submit”]&#39;）.prop（&#39;disabled&#39;，false）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Stop the Loading of Links

 有时，您不希望链接转到某个网页，也不希望重新加载该网页；  您可能希望他们做其他事情，例如触发另一个脚本.  这样可以防止默认操作：

```javascript
$（&#39;a.no-link&#39;）.on（&#39;click&#39;，function（e）{
  e.preventDefault（）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Cache jQuery Selectors

 想想您在任何项目中一次又一次地编写同一选择器的次数.  每个`$（&#39;.element&#39;）`选择器每次都必须搜索整个DOM，无论该选择器以前是否运行过.  相反，您可以运行一次选择器并将结果存储在变量中：

```javascript
var blocks = $('#blocks').find('li');
```

现在，您可以在任何需要的地方使用`blocks`变量，而不必每次都搜索DOM：

```javascript
$('#hideBlocks').on('click', function () {
  blocks.fadeOut（）;
});

$('#showBlocks').on('click', function () {
  blocks.fadeIn（）;
});
```

缓存jQuery选择器可以提高性能.

<sup>[back to table of contents](#table-of-contents)</sup>


### Toggle Fade/Slide

 滑动和衰落在jQuery动画中很常见.  您可能希望在用户单击某些内容时显示一个元素，这使“ fadeIn”和“ slideDown”方法变得完美，但是如果您希望该元素在第一次单击时出现，然后在第二次单击时消失，则可以正常工作：

```javascript
// 褪色
$（&#39;.btn&#39;）.on（&#39;click&#39;，function（）{
  $（&#39;.element&#39;）.fadeToggle（&#39;slow&#39;）;
});

//切换
$（&#39;.btn&#39;）.on（&#39;click&#39;，function（）{
  $（&#39;.element&#39;）.slideToggle（&#39;slow&#39;）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Simple Accordion

这是快速手风琴的一种简单方法：

```javascript
//关闭所有面板
$('#accordion').find('.content').hide();

//手风琴
$('#accordion').find('.accordion-header').on('click', function () {
  var next = $（this）.next（）;
  next.slideToggle（&#39;fast&#39;）;
  $（&#39;.content&#39;）.not（next）.slideUp（&#39;fast&#39;）;
  返回false；
});
```

通过添加此脚本，您真正需要在网页上完成的工作就是实现此工作所需的HTML.

<sup>[back to table of contents](#table-of-contents)</sup>


### Make Two Divs the Same Height

有时，无论它们包含什么内容，您都希望两个div具有相同的高度：

```javascript
$（&#39;.div&#39;）.css（&#39;min-height&#39;，$（&#39;.main-div&#39;）.height（））;
```

 此示例设置了“最小高度”，这意味着它可以大于主div，但永远不能小于它.  但是，一种更灵活的方法是遍历一组元素并将“ height”设置为最高元素的高度：

```javascript
var $ columns = $（&#39;.column&#39;）;
var height = 0;
$ columns.each（function（）{
  如果（$（this）.height（）&gt; height）{
    高度= $（this）.height（）;
  }
});
$columns.height(height);
```

如果您希望_all_列具有相同的高度：

```javascript
var $ rows = $（&#39;.same-height-columns&#39;）;
$ rows.each（function（）{
  $（this）.find（&#39;.column&#39;）.height（$（this）.height（））;
});
```

**注意：**这可以通过多种方式完成 [in CSS](http://codepen.io/AllThingsSmitty/pen/KMPqoO) 但是根据您的需求，知道如何在jQuery中做到这一点很方便.

<sup>[back to table of contents](#table-of-contents)</sup>


### Open External Links in New Tab/Window

在新的浏览器标签或窗口中打开外部链接，并确保在同一标签或窗口中打开相同来源的链接：

```javascript
$（&#39;a [href ^ =“ http”]&#39;）.attr（&#39;target&#39;，&#39;_blank&#39;）;
$（&#39;a [href ^ =“ //”]&#39;）.attr（&#39;target&#39;，&#39;_blank&#39;）;
$（&#39;a [href ^ =“&#39;+ window.location.origin +&#39;”]&#39;）.attr（&#39;target&#39;，&#39;_self&#39;）;
```

**注意：**`window.location.origin`在IE10中不起作用. [This fix](http://tosbourn.com/a-fix-for-window-location-origin-in-internet-explorer/) 解决这个问题.

<sup>[back to table of contents](#table-of-contents)</sup>


### Find Element By Text

 通过在jQuery中使用“ contains（）”选择器，您可以找到元素内容中的文本.  如果文本不存在，则该元素将被隐藏：

```javascript
var search = $('#search').val();
$（&#39;div：not（：contains（“&#39;+ search +&#39;”））&#39;）.hide（）;
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Trigger on Visibility Change

当用户不再专注于标签或重新关注标签时触发JavaScript：

```javascript
$（document）.on（&#39;visibilitychange&#39;，function（e）{
  如果（e.target.visibilityState ===&#39;visible&#39;）{
    console.log（&#39;Tab现在可见了！&#39;）;
  }否则，如果（e.target.visibilityState ===&#39;hidden&#39;）{
    console.log（&#39;标签现在被隐藏了！&#39;）;
  }
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### AJAX Call Error Handling

 当AJAX调用返回404或500错误时，将执行错误处理程序.  如果未定义处理程序，则其他jQuery代码可能无法按预期工作.  要定义全局AJAX错误处理程序：

```javascript
$（document）.on（&#39;ajaxError&#39;，函数（例如，xhr，设置，错误）{
  console.log（错误）;
});
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Chain Plugin Calls

 jQuery允许插件方法调用的“链接”，以减轻重复查询DOM和创建多个jQuery对象的过程.  假设以下代码段表示您的插件方法调用：

```javascript
$('#elem').show();
$('#elem').html('bla');
$('#elem').otherStuff();
```

通过使用链接可以大大改善这一点：

```javascript
$('#elem')
  .显示（）
  .html（&#39;bla&#39;）
  .其他的东西（）;
```

另一种方法是将元素缓存在变量中（以$开头）：

```javascript
var $elem = $('#elem');
$elem.hide();
$elem.html('bla');
$elem.otherStuff();
```

链接和 [caching](#cache-jquery-selectors) jQuery中的方法是导致代码更短，更快的最佳实践.

<sup>[back to table of contents](#table-of-contents)</sup>


### Sort List Items Alphabetically

 假设您最终在列表中添加了太多项目.  内容可能是由CMS制作的，您想按字母顺序排序：

```javascript
var ul = $('#list'),
lis = $（&#39;li&#39;，ul）.get（）;

lis.sort（function（a，b）{
  return ($(a).text().toUpperCase() < $(b).text().toUpperCase()) ? -1 : 1;
});

ul.append(lis);
```

你去！

<sup>[back to table of contents](#table-of-contents)</sup>


### Disable Right-Click

如果要禁用右键单击，则可以在整个页面上执行此操作...

```javascript
$（document）.ready（function（）{
  $（document）.bind（&#39;contextmenu&#39;，函数（e）{
    返回false；
  })
})
```

...并且您还可以对特定元素执行相同的操作：

```javascript
$（document）.ready（function（）{
  $('#submit').bind('contextmenu', function (e) {
    返回false；
  })
})
```

<sup>[back to table of contents](#table-of-contents)</sup>






## Support

Chrome，Firefox，Safari，Opera，Edge和IE11的当前版本.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

* [български](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/bg-BG)
* [Español](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/fr-FR)
* [Magyar](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/hu-HU)
* [Português do Europe](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/pt-PT)
* [Pусский](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ru-RU)
* [简体中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-CN)
* [繁體中文](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-TW)

<sup>[back to table of contents](#table-of-contents)</sup>
