<div class="github-widget" data-repo="30-seconds/30-seconds-of-code"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
[![Logo](https://raw.githubusercontent.com/30-seconds/30-seconds-of-code/master//logo.png)](https://30secondsofcode.org/)

## 30 seconds of code

[![License](https://img.shields.io/badge/license-CC0--1.0-blue.svg)](https://github.com/30-seconds/30-seconds-of-code/blob/master/LICENSE) [![npm Downloads](https://img.shields.io/npm/dt/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code) [![npm Version](https://img.shields.io/npm/v/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code) [![Known Vulnerabilities](https://snyk.io/test/github/30-seconds/30-seconds-of-code/badge.svg?targetFile=package.json)](https://snyk.io/test/github/30-seconds/30-seconds-of-code?targetFile=package.json) [![Travis Build](https://travis-ci.com/30-seconds/30-seconds-of-code.svg?branch=master)](https://travis-ci.com/30-seconds/30-seconds-of-code) <br/>
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![ProductHunt](https://img.shields.io/badge/producthunt-vote-orange.svg)](https://www.producthunt.com/posts/30-seconds-of-code) [![js-semistandard-style](https://img.shields.io/badge/code%20style-semistandard-brightgreen.svg)](https://github.com/Flet/semistandard) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

&gt;精选有用的JavaScript代码段集合，您可以在30秒或更短的时间内理解这些代码段.

*使用<kbd>Ctrl</kbd> + <kbd>F</kbd>或<kbd>Command</kbd> + <kbd>F</kbd>搜索代码段.
*欢迎捐款，请阅读 [contribution guide](https://github.com/30-seconds/30-seconds-of-code/blob/master/CONTRIBUTING.md).
* Snippets are written in ES6, use the [Babel transpiler](https://babeljs.io/) 确保向后兼容.
* You can import these snippets into VSCode, by following the instructions found [here](https://github.com/30-seconds/30-seconds-of-code/tree/master/vscode_snippets).
*您可以使用以下命令中的CLI应用程序从终端搜索，查看和复制这些片段 [this repo](https://github.com/sQVe/30s).
*如果您想在社交媒体上遵循30秒的代码，可以在以下位置找到我们 [Facebook](https://www.facebook.com/30secondsofcode), [Instagram](https://www.instagram.com/30secondsofcode) 和 [Twitter](https://twitter.com/30secondsofcode).

#### Related projects

* [30 Seconds of CSS](https://30-seconds.github.io/30-seconds-of-css/)
* [30 Seconds of Interviews](https://30secondsofinterviews.org/)
* [30 Seconds of React](https://github.com/30-seconds/30-seconds-of-react)
* [30 Seconds of Python](https://github.com/30-seconds/30-seconds-of-python-code)
* [30 Seconds of PHP](https://github.com/30-seconds/30-seconds-of-php-code)
* [30 Seconds of Knowledge](https://chrome.google.com/webstore/detail/30-seconds-of-knowledge/mmgplondnjekobonklacmemikcnhklla)
* [30 Seconds of Kotlin](https://github.com/IvanMwiruki/30-seconds-of-kotlin) _（非官方）_

#### Package

⚠️**注意：**我们的一些代码片段尚未针对生产进行优化（请参阅免责声明以了解单个代码片段的问题）.

您可以找到包含所有代码段的软件包 [npm](https://www.npmjs.com/package/30-seconds-of-code).

```bash
## With npm
npm安装30秒代码

## With yarn
纱线加长30秒的代码
```

[CDN link](https://unpkg.com/30-seconds-of-code/)

<details>
<summary>Details</summary>

**Browser**

```html
<script src="https://unpkg.com/30-seconds-of-code@1/dist/_30s.es5.min.js"></script>
<script>
  _30s.average（1、2、3）;
</script>
```

**Node**

```js
// CommonJS
const _30s = require（&#39;30秒代码&#39;）;
_30s.average（1、2、3）;

// ES模块
从“代码的30秒”中导入_30s；
_30s.average（1、2、3）;
```

</details>


### 🔌 Adapter

<details>
<summary>查看内容</summary>


</details>

### 📚 Array

<details>
<summary>查看内容</summary>


</details>

### 🌐 Browser

<details>
<summary>查看内容</summary>


</details>

### ⏱️ Date

<details>
<summary>查看内容</summary>


</details>

### 🎛️ Function

<details>
<summary>查看内容</summary>


</details>

### ➗ Math

<details>
<summary>查看内容</summary>


</details>

### 📦 Node

<details>
<summary>查看内容</summary>


</details>

### 🗃️ Object

<details>
<summary>查看内容</summary>


</details>

### 📜 String

<details>
<summary>查看内容</summary>


</details>

### 📃 Type

<details>
<summary>查看内容</summary>


</details>

### 🔧 Utility

<details>
<summary>查看内容</summary>


</details>


---

## 🔌 Adapter


### ary

创建一个最多接受n个参数的函数，而忽略任何其他参数.

使用Array.prototype.slice（0，n）和散布运算符（...）调用提供的函数fn，最多包含n个参数.

```js
const ary =（fn，n）=&gt;（... args）=&gt; fn（... args.slice（0，n））;
```

<details>
<summary>Examples</summary>

```js
const firstTwoMax = ary（Math.max，2）;
 [[2，6，&#39;a&#39;]，[6，4，8]，[10]].map（x =&gt; firstTwoMax（... x））;  // [6，6，10]
```
</details>


### call

 给定一个键和一组参数，在给定上下文时调用它们.  主要用于合成.

使用闭包调用带有存储参数的存储键.

```js
const call =（键，https://github.com/30-seconds/30-seconds-of-code/blob/master/...args）=&gt;上下文=&gt;上下文[key](https://github.com/30-seconds/30-seconds-of-code/blob/master/...args);
```

<details>
<summary>Examples</summary>

```js
Promise.resolve（[1,2,3]）
  .then（call（&#39;map&#39;，x =&gt; 2 * x））
   .then（console.log）;  // [2，4，6]
const map = call.bind（null，&#39;map&#39;）;
Promise.resolve（[1,2,3]）
  .then（map（x =&gt; 2 * x））
   .then（console.log）;  // [2，4，6]
```
</details>


### collectInto

将接受数组的函数更改为可变函数.

给定一个函数，返回一个将所有输入收集到数组接受函数的闭包.

```js
const collectInto = fn =&gt;（... args）=&gt; fn（args）;
```

<details>
<summary>Examples</summary>

```js
const Pall = collectInto（Promise.all.bind（Promise））;
令p1 = Promise.resolve（1）;
令p2 = Promise.resolve（2）;
让p3 = new Promise（resolve =&gt; setTimeout（resolve，2000，3））;
 Pall（p1，p2，p3）.then（console.log）;  // [1、2、3]（大约2秒钟后）
```
</details>


### flip

Flip将函数用作参数，然后使第一个参数成为最后一个参数.

返回一个采用可变输入的闭包，并在应用其余参数之前将最后一个参数拼接为第一个参数.

```js
const flip = fn =&gt;（first，... rest）=&gt; fn（... rest，first）;
```

<details>
<summary>Examples</summary>

```js
让a = {名称：&#39;John Smith&#39;};
令b = {};
const mergeFrom = flip（Object.assign）;
让mergePerson = mergeFrom.bind（null，a）;
 mergePerson（b）;  // == b
b = {};
 Object.assign（b，a）;  // == b
```
</details>


### over

创建一个函数，该函数使用接收到的参数调用每个提供的函数并返回结果.

使用Array.prototype.map（）和Function.prototype.apply（）将每个函数应用于给定参数.

```js
const over =（... fns）=&gt;（... args）=&gt; fns.map（fn =&gt; fn.apply（null，args））;
```

<details>
<summary>Examples</summary>

```js
const minMax = over（Math.min，Math.max）;
 minMax（1,2,3,4,5）;  // [1,5]
```
</details>


### overArgs

创建一个函数，该函数调用提供的函数并转换其参数.

使用Array.prototype.map（）来将`transforms`应用于`args`并与散布运算符（`...`）一起将转换后的参数传递给`fn`.

```js
const overArgs =（fn，变换）=&gt;（... args）=&gt; fn（... args.map（（https://github.com/30-seconds/30-seconds-of-code/blob/ master / val，i）=&gt;转换[i](https://github.com/30-seconds/30-seconds-of-code/blob/master/val)));
```

<details>
<summary>Examples</summary>

```js
const square = n =&gt; n * n;
const double = n =&gt; n * 2;
const fn = overArgs（（x，y）=&gt; [x，y]，[square，double]）;
 fn（9，3）;  // [81，6]
```
</details>


### pipeAsyncFunctions

对异步功能执行从左到右的功能组合.

使用带有传播运算符（...）的Array.prototype.reduce（）来使用Promise.then（）从左到右执行功能组合.
这些函数可以返回以下组合：简单值，Promise或可以定义为通过await返回的异步值.
所有函数必须是一元的.

```js
const pipeAsyncFunctions =（... fns）=&gt; arg =&gt; fns.reduce（（p，f）=&gt; p.then（f），Promise.resolve（arg））;
```

<details>
<summary>Examples</summary>

```js
const sum = pipeAsyncFunctions（
  x =&gt; x + 1
  x =&gt;新的Promise（resolve =&gt; setTimeout（（）=&gt; resolve（x + 2），1000）），
  x =&gt; x + 3，
  异步x =&gt;（await x）+ 4
);
（异步（）=&gt; {
   console.log（await sum（5））;  // 15（一秒钟后）
})();
```
</details>


### pipeFunctions

执行从左到右的功能合成.

使用带有传播运算符（...）的Array.prototype.reduce（）来执行从左到右的功能合成.
 第一个（最左侧）函数可以接受一个或多个参数.  其余功能必须是一元的.

```js
const pipeFunctions =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; g（f（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add5 = x =&gt; x + 5;
const乘法=（x，y）=&gt; x * y;
const multipleAndAdd5 = pipeFunctions（multiply，add5）;
 multipleAndAdd5（5，2）;  // 15
```
</details>


### promisify

转换异步函数以返回promise.

*在Node 8+中，您可以使用 [`util.promisify`](https://nodejs.org/api/util.html#util_util_promisify_original)*

使用currying返回一个函数，该函数返回一个调用原始函数的Promise.
使用`... rest`运算符来传递所有参数.

```js
const promisify = func =&gt;（... args）=&gt;
  新的Promise（（resolve，reject）=&gt;
    func（... args，（err，result）=&gt;（err？reject（err）：resolve（结果）））
  );
```

<details>
<summary>Examples</summary>

```js
const delay = promisify（（d，cb）=&gt; setTimeout（cb，d））;
 delay（2000）.then（（）=&gt; console.log（&#39;Hi！&#39;））;  // //承诺在2秒后解决
```
</details>


### rearg

创建一个函数，该函数调用提供的函数，其参数根据指定的索引排列.

使用Array.prototype.map（）结合散布运算符（...）将基于索引的参数重新排序，以将转换后的参数传递给fn.

```js
const Rearg =（fn，index）=&gt;（... args）=&gt; fn（... indexes.map（i =&gt; args [i]）））;
```

<details>
<summary>Examples</summary>

```js
var Rearged = Rearg（
  函数（a，b，c）{
    返回[a，b，c];
  },
  [2, 0, 1]
);
 重装（&#39;b&#39;，&#39;c&#39;，&#39;a&#39;）;  // [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
```
</details>


### spreadOver

接收可变参数函数并返回一个闭包，该闭包接受参数数组以映射到该函数的输入.

使用闭包和传播运算符（`...`）将参数数组映射到函数的输入.

```js
const spreadOver = fn =&gt; argsArr =&gt; fn（... argsArr）;
```

<details>
<summary>Examples</summary>

```js
const arrayMax = spreadOver（Math.max）;
 arrayMax（[1,2,3]）;  // 3
```
</details>


### unary

创建一个函数，该函数最多接受一个参数，而忽略任何其他参数.

调用提供的函数`fn`，仅给出第一个参数.

```js
const unary = fn =&gt; val =&gt; fn（val）;
```

<details>
<summary>Examples</summary>

```js
 [&#39;6&#39;，&#39;8&#39;，&#39;10&#39;].map（unary（parseInt））;  // [6，8，10]
```
</details>


---

## 📚 Array


### all

如果提供的谓词函数对集合中的所有元素都返回“ true”，则返回“ true”，否则返回“ false”.

使用Array.prototype.every（）来测试集合中的所有元素是否都基于fn返回true.
省略第二个参数`fn`，以使用`Boolean&#39;作为默认值.

```js
const all =（arr，fn = Boolean）=&gt; arr.every（fn）;
```

<details>
<summary>Examples</summary>

```js
 全部（[4，2，3]，x =&gt; x&gt; 1）;  //正确
 全部（[1,2,3]）;  //正确
```
</details>


### allEqual

检查数组中的所有元素是否相等.

使用Array.prototype.every（）检查数组的所有元素是否与第一个元素相同.
使用严格的比较运算符比较数组中的元素，该运算符不考虑NaN自不等式.

```js
const allEqual = arr =&gt; arr.every（val =&gt; val === arr [0]）;
```

<details>
<summary>Examples</summary>

```js
 allEqual（[1,2,3,4,5,6]）;  //错误
 allEqual（[1，1，1，1]）;  //正确
```
</details>


### any

如果提供的谓词函数对集合中的至少一个元素返回“ true”，则返回“ true”，否则返回“ false”.

使用Array.prototype.some（）来测试集合中是否有任何元素基于fn返回true.
省略第二个参数`fn`，以使用`Boolean&#39;作为默认值.

```js
const any =（arr，fn = Boolean）=&gt; arr.some（fn）;
```

<details>
<summary>Examples</summary>

```js
 any（[0，1，2，0]，x =&gt; x&gt; = 2）;  //正确
 任何（[0，0，1，0]）;  //正确
```
</details>


### arrayToCSV

将二维数组转换为逗号分隔值（CSV）字符串.

使用Array.prototype.map（）和Array.prototype.join（delimiter）将单个一维数组（行）组合成字符串.
使用Array.prototype.join（&#39;\ n&#39;）将所有行合并为CSV字符串，并用换行符分隔每一行.
省略第二个参数`delimiter`，以使用默认定界符`，`.

```js
const arrayToCSV =（arr，delimiter =&#39;，&#39;）=&gt;
  rr
    .map（v =&gt; v.map（x =&gt;（isNaN（x）？`“ $ {x.replace（/” / g，&#39;“”&#39;）}“`：x））.join（delimiter））
    .join（&#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
 arrayToCSV（[[&#39;a&#39;，&#39;b&#39;]，[&#39;c&#39;，&#39;d&#39;]]）;  //&#39;“ a”，“ b” \ n“ c”，“ d”&#39;
 arrayToCSV（[[&#39;a&#39;，&#39;b&#39;]，[&#39;c&#39;，&#39;d&#39;]]，&#39;;&#39;）;  //&#39;“ a”;“ b” \ n“ c”;“ d”&#39;
 arrayToCSV（[[&#39;a&#39;，&#39;“ b” great&#39;]，[&#39;c&#39;，3.1415]]）;  //&#39;“” a“，”“” b“”很棒“ \ n” c“，3.1415&#39;
```
</details>


### bifurcate

 将值分为两组.  如果`filter`中的元素是真实的，则集合中的对应元素属于第一组；  否则，它属于第二组.

使用array.prototype.reduce（）和Array.prototype.push（）将元素添加到基于filter的组中.

```js
const bifurcate =（arr，filter）=&gt;
  arr.reduce（（acc，val，i）=&gt;（acc [filter [i]？0：1] .push（val），acc），[[]，[]]）;
```

<details>
<summary>Examples</summary>

```js
 bifurcate（[&#39;beep&#39;，&#39;boop&#39;，&#39;foo&#39;，&#39;bar&#39;]，[true，true，false，true]）；  // [[&#39;beep&#39;，&#39;boop&#39;，&#39;bar&#39;]，[&#39;foo&#39;]]
```
</details>


### bifurcateBy

 根据谓词函数将值分为两组，该函数指定输入集合中元素所属的组.  如果谓词函数返回真实值，则collection元素属于第一组；  否则，它属于第二组.

根据每个元素的fn返回值，使用Array.prototype.reduce（）和Array.prototype.push（）将元素添加到组中.

```js
const bifurcateBy =（arr，fn）=&gt;
  arr.reduce（（acc，val，i）=&gt;（acc [fn（val，i）？0：1] .push（val），acc），[[]，[]]）;
```

<details>
<summary>Examples</summary>

```js
 bifurcateBy（[&#39;beep&#39;，&#39;boop&#39;，&#39;foo&#39;，&#39;bar&#39;]，x =&gt; x [0] ===&#39;b&#39;）;  // [[&#39;beep&#39;，&#39;boop&#39;，&#39;bar&#39;]，[&#39;foo&#39;]]
```
</details>


### chunk

将数组分成指定大小的较小数组.

使用Array.from（）创建一个新数组，该数组适合将要生成的块数.
使用Array.prototype.slice（）将新数组的每个元素映射到大小为size的块上.
如果原始数组无法平均分割，则最后一块将包含其余元素.

```js
const chunk =（arr，size）=&gt;
  Array.from（{length：Math.ceil（arr.length / size）}，（v，i）=&gt;
    arr.slice（i *大小，i *大小+大小）
  );
```

<details>
<summary>Examples</summary>

```js
 块（[1,2,3,4,5]，2）;  // [[1,2]，[3,4]，[5]]
```
</details>


### compact

从数组中删除伪造的值.

使用Array.prototype.filter（）过滤掉虚假的值（假，空，0，“”，“ undefined”和“ NaN”）.

```js
const compact = arr =&gt; arr.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 compact（[0，1，false，2，&#39;&#39;，3，&#39;a&#39;，&#39;e&#39;* 23，NaN，&#39;s&#39;，34]）;  // [1，2，3，&#39;a&#39;，&#39;s&#39;，34]
```
</details>


### countBy

根据给定的函数对数组的元素进行分组，并返回每个组中元素的计数.

使用Array.prototype.map（）将数组的值映射到函数或属性名称.
使用Array.prototype.reduce（）创建一个对象，从映射结果中生成键.

```js
const countBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val）=&gt; {
    acc [val] =（acc [val] || 0）+ 1;
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 countBy（[6.1，4.2，6.3]，Math.floor）;  // {4：1，6：2}
 countBy（[&#39;一个&#39;，&#39;两个&#39;，&#39;三个&#39;]，&#39;长度&#39;）;  // {3：2，5：1}
```
</details>


### countOccurrences

计算数组中某个值的出现次数.

每次遇到数组中的特定值时，都可以使用Array.prototype.reduce（）来增加计数器.

```js
const countOccurrences =（arr，val）=&gt; arr.reduce（（a，v）=&gt;（v === val？a + 1：a），0）;
```

<details>
<summary>Examples</summary>

```js
 countOccurrences（[1、1,2、1、2、3]，1）；  // 3
```
</details>


### deepFlatten

Deep展平数组.

使用递归.
将`Array.prototype.concat（）`与一个空数组（`[]`）和散布运算符（`...`）一起使用，以使数组变平.
以递归方式展平数组中的每个元素.

```js
const deepFlatten = arr =&gt; [] .concat（... arr.map（v =&gt;（Array.isArray（v）？deepFlatten（v）：v）））;;
```

<details>
<summary>Examples</summary>

```js
 deepFlatten（[1，[2]，[[3]，4]，5]）;  // [1,2,3,4,5]
```
</details>


### difference

返回两个数组之间的差.

从b中创建一个Set，然后在a中使用Array.prototype.filter（）来仅保留b中不包含的值.

```js
常数差=（a，b）=&gt; {
  const s = new Set（b）;
  返回a.filter（x =&gt;！s.has（x））;
};
```

<details>
<summary>Examples</summary>

```js
 差异（[1、2、3]，[1、2、4]）;  // [3]
```
</details>


### differenceBy

将提供的函数应用于两个数组的每个数组元素后，返回两个数组之间的差.

通过对b中的每个元素应用fn来创建Set，然后使用Array.prototype.map（）对a中的每个元素应用fn，然后对Array.prototype.filter（ ）`

```js
const DifferenceBy =（a，b，fn）=&gt; {
  const s = new Set（b.map（fn））;
  返回a.map（fn）.filter（=&gt;！s.has（el））;
};
```

<details>
<summary>Examples</summary>

```js
 DifferenceBy（[2.1，1.2]，[2.3，3.4]，Math.floor）;  // [1]
 DifferenceBy（[{x：2}，{x：1}]，[{x：1}]，v =&gt; vx）;  // [2]
```
</details>


### differenceWith

从比较器函数未返回“ true”的数组中过滤掉所有值.

使用`Array.prototype.filter（）`和`Array.prototype.findIndex（）`查找合适的值.

```js
const DifferenceWith =（arr，val，comp）=&gt; arr.filter（a =&gt; val.findIndex（b =&gt; comp（a，b））=== -1）;
```

<details>
<summary>Examples</summary>

```js
 DifferenceWith（[1，1.2，1.5，3，0]，[1.9，3，0]，（a，b）=&gt; Math.round（a）=== Math.round（b））;  // [1，1.2]
```
</details>


### drop

返回一个新数组，其中左侧删除了n个元素.

使用Array.prototype.slice（）从左侧删除指定数量的元素.

```js
const drop =（arr，n = 1）=&gt; arr.slice（n）;
```

<details>
<summary>Examples</summary>

```js
 drop（[1,2,3]）;  // [2,3]
 drop（[1、2、3]，2）;  // [3]
 drop（[1,2,3]，42）;  // []
```
</details>


### dropRight

返回一个新数组，其中右侧删除了“ n”个元素.

使用Array.prototype.slice（）从右侧删除指定数量的元素.

```js
const dropRight =（arr，n = 1）=&gt; arr.slice（0，-n）;
```

<details>
<summary>Examples</summary>

```js
 dropRight（[1,2,3]）;  // [1,2]
 dropRight（[1,2,3]，2）;  // [1]
dropRight([1, 2, 3], 42); // []
```
</details>


### dropRightWhile

 从数组末尾删除元素，直到传递的函数返回“ true”为止.  返回数组中剩余的元素.

遍历数组，使用Array.prototype.slice（）删除数组的最后一个元素，直到函数返回的值为true.
返回剩余的元素.

```js
const dropRightWhile =（arr，func）=&gt; {
  让rightIndex = arr.length;
  while（rightIndex-- &amp;&amp;！func（arr [rightIndex]））;
  返回arr.slice（0，rightIndex +1）;
};
```

<details>
<summary>Examples</summary>

```js
 dropRightWhile（[1,2,3,4]，n =&gt; n &lt;3）;  // [1，2]
```
</details>


### dropWhile

 删除数组中的元素，直到传递的函数返回“ true”为止.  返回数组中剩余的元素.

使用Array.prototype.slice（）遍历数组，删除数组的第一个元素，直到函数返回的值为true.
返回剩余的元素.

```js
const dropWhile =（arr，func）=&gt; {
  while（arr.length&gt; 0 &amp;&amp;！func（arr [0]））arr = arr.slice（1）;
  返回arr;
};
```

<details>
<summary>Examples</summary>

```js
 dropWhile（[1,2,3,4]，n =&gt; n&gt; = 3）;  // [3,4]
```
</details>


### everyNth

返回数组中的每个第n个元素.

使用Array.prototype.filter（）创建一个包含给定数组的第n个元素的新数组.

```js
const everyNth =（arr，nth）=&gt; arr.filter（（e，i）=&gt; i％nth === nth-1）;
```

<details>
<summary>Examples</summary>

```js
 everyNth（[1,2,3,4,5,6]，2）;  // [2，4，6]
```
</details>


### filterFalsy

过滤出数组中的伪造值.

使用Array.prototype.filter（）获得仅包含真实值的数组.

```js
const filterFalsy = arr =&gt; arr.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 filterFalsy（[&#39;&#39;，true，{}，false，&#39;sample&#39;，1，0]）;  // [true，{}，&#39;sample&#39;，1]
```
</details>


### filterNonUnique

筛选出数组中的非唯一值.

对仅包含唯一值的数组使用“ Array.prototype.filter（）”.

```js
const filterNonUnique = arr =&gt; arr.filter（i =&gt; arr.indexOf（i）=== arr.lastIndexOf（i））;
```

<details>
<summary>Examples</summary>

```js
 filterNonUnique（[1、2、2、3、4、4、5]）;  // [1、3、5]
```
</details>


### filterNonUniqueBy

根据提供的比较器功能，过滤出数组中的非唯一值.

根据比较器函数fn，将Array.prototype.filter（）和Array.prototype.every（）用于仅包含唯一值的数组.
比较器函数有四个参数：要比较的两个元素的值及其索引.

```js
const filterNonUniqueBy =（arr，fn）=&gt;
  arr.filter（（v，i）=&gt; arr.every（（x，j）=&gt;（i === j）=== fn（v，x，i，j））））;
```

<details>
<summary>Examples</summary>

```js
filterNonUniqueBy(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，值：&#39;d&#39;}，
    {id：0，值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{{id：2，value：&#39;c&#39;}]
```
</details>


### findLast

返回提供的函数为其返回真值的最后一个元素.

使用Array.prototype.filter（）删除fn返回虚假值的元素，Array.prototype.pop（）获取最后一个元素.

```js
const findLast =（arr，fn）=&gt; arr.filter（fn）.pop（）;
```

<details>
<summary>Examples</summary>

```js
 findLast（[1,2,3,4]，n =&gt; n％2 === 1）;  // 3
```
</details>


### findLastIndex

返回提供的函数为其返回真值的最后一个元素的索引.

Use `Array.prototype.map()` to map each element to an array with its index and value.
使用Array.prototype.filter（）删除fn返回虚假值的元素，Array.prototype.pop（）获取最后一个元素.
找不到时，“-1”是默认值.

```js
const findLastIndex =（arr，fn）=&gt;
  （arr
    .map（（val，i）=&gt; [i，val]）
    .filter（（[[i，val]）=&gt; fn（val，i，arr））
     .pop（）||  [-1]）[0]；
```

<details>
<summary>Examples</summary>

```js
 findLastIndex（[1,2,3,4]，n =&gt; n％2 === 1）;  // 2（值3的索引）
 findLastIndex（[1,2,3,4]，n =&gt; n === 5）;  // -1（找不到时的默认值）
```
</details>


### flatten

将数组展平到指定深度.

使用递归，将每个深度级别的“深度”递减1.
Use `Array.prototype.reduce()` and `Array.prototype.concat()` to merge elements or arrays.
基本情况下，对于“深度”等于“ 1”，将停止递归.
省略第二个参数“ depth”以仅展平至深度“ 1”（单展平）.

```js
const flatten =（arr，depth = 1）=&gt;
  arr.reduce（（a，v）=&gt; a.concat（depth&gt; 1 &amp;&amp; Array.isArray（v）？flatten（v，depth-1）：v），[]）;
```

<details>
<summary>Examples</summary>

```js
 flatten（[1，[2]，3，4]）;  // [1、2、3、4]
 flatten（[1，[2，[3，[4，5]，6]，7]，8]，2）;  // [1、2、3，[4、5]，6、7、8]
```
</details>


### forEachRight

从数组的最后一个元素开始，对每个数组元素执行一次提供的功能.

使用Array.prototype.slice（0）克隆给定的数组，使用Array.prototype.reverse（）反转它，并使用Array.prototype.forEach（）遍历反转的数组.

```js
const forEachRight =（arr，回调）=&gt;
  rr
    .slice（0）
    .相反（）
    .forEach（回调）;
```

<details>
<summary>Examples</summary>

```js
 forEachRight（[1,2,3,4]，val =&gt; console.log（val））;  //&#39;4&#39;，&#39;3&#39;，&#39;2&#39;，&#39;1&#39;
```
</details>


### groupBy

根据给定的函数对数组的元素进行分组.

使用Array.prototype.map（）将数组的值映射到函数或属性名称.
使用Array.prototype.reduce（）创建一个对象，从映射结果中生成键.

```js
const groupBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val，i）=&gt; {
    acc [val] =（acc [val] || []）.concat（arr [i]）;
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 groupBy（[6.1，4.2，6.3]，Math.floor）;  // {4：[4.2]，6：[6.1，6.3]}
 groupBy（[&#39;一个&#39;，&#39;两个&#39;，&#39;三个&#39;]，&#39;长度&#39;）;  // {3：[&#39;one&#39;，&#39;two&#39;]，5：[&#39;three&#39;]}
```
</details>


### head

返回列表的开头.

使用`arr [0]`返回所传递数组的第一个元素.

```js
const head = arr =&gt; arr [0];
```

<details>
<summary>Examples</summary>

```js
 头（[1,2,3]）;  // 1
```
</details>


### indexOfAll

返回数组中所有“ val”的索引.
If `val` never occurs, returns `[]`.

使用Array.prototype.reduce（）遍历元素并存储索引以匹配元素.
返回索引数组.

```js
const indexOfAll =（arr，val）=&gt; arr.reduce（（acc，el，i）=&gt;（el === val？[... acc，i]：acc），[]）;
```

<details>
<summary>Examples</summary>

```js
 indexOfAll（[1、2、3、1、2、3]，1）;  // [0,3]
 indexOfAll（[1,2,3] 4）;  // []
```
</details>


### initial

返回数组中除最后一个元素之外的所有元素.

使用`arr.slice（0，-1）`返回除数组的最后一个元素以外的所有元素.

```js
const initial = arr =&gt; arr.slice（0，-1）;
```

<details>
<summary>Examples</summary>

```js
 initial（[1,2,3]）;  // [1,2]
```
</details>


### initialize2DArray

初始化给定宽度，高度和值的2D数组.

 使用Array.prototype.map（）生成h行，其中每个行都是一个新的大小为w的数组，并使用值进行初始化.  如果未提供该值，则默认为“ null”.

```js
const initialize2DArray =（w，h，val = null）=&gt;
  Array.from（{length：h}）.map（（）=&gt; Array.from（{length：w}）.fill（val））;
```

<details>
<summary>Examples</summary>

```js
 initialize2DArray（2，2，0）;  // [[0,0]，[0,0]]
```
</details>


### initializeArrayWithRange

初始化一个数组，该数组包含指定范围内的数字，其中“ start”和“ end”包含其共同点“ step”.

使用Array.from（）创建所需长度的数组，（结束-开始+ 1）/步长，并使用map函数在给定范围内填充所需的值.
您可以省略“开始”以使用默认值“ 0”.
您可以省略`step`以使用默认值&#39;1&#39;.

```js
const initializeArrayWithRange = (end, start = 0, step = 1) =>
  Array.from（{length：Math.ceil（（end-start + 1）/ step）}，（v，i）=&gt; i * step + start）;
```

<details>
<summary>Examples</summary>

```js
initializeArrayWithRange(5); // [0,1,2,3,4,5]
 initializeArrayWithRange（7，3）;  // [3,4,5,6,7]
 initializeArrayWithRange（9，0，2）;  // [0,2,4,6,8]
```
</details>


### initializeArrayWithRangeRight

初始化一个数组，该数组包含指定范围内的数字（反向），其中“ start”和“ end”包含其共同点“ step”.

使用Array.from（Math.ceil（（end + 1-start）/ step））创建一个所需长度的数组（元素数量等于（（end-start）/ step）或`（ end + 1-start）/ step（包括结束符），使用Array.prototype.map（）填充范围内的所需值.
您可以省略“开始”以使用默认值“ 0”.
您可以省略`step`以使用默认值&#39;1&#39;.

```js
const initializeArrayWithRangeRight =（结束，开始= 0，步骤= 1）=&gt;
  Array.from（{长度：Math.ceil（（end +1-start）/ step）}）.map（
    （v，i，arr）=&gt;（arr.length-i-1）* step + start
  );
```

<details>
<summary>Examples</summary>

```js
 initializeArrayWithRangeRight（5）;  // [5,4,3,2,1,0]
 initializeArrayWithRangeRight（7，3）;  // [7,6,5,4,3]
 initializeArrayWithRangeRight（9，0，2）;  // [8,6,4,2,0]
```
</details>


### initializeArrayWithValues

使用指定的值初始化并填充数组.

使用“ Array（n）”创建所需长度的数组，使用“ fill（v）”填充所需值.
您可以省略“ val”以使用默认值“ 0”.

```js
const initializeArrayWithValues =（n，val = 0）=&gt; Array（n）.fill（val）;
```

<details>
<summary>Examples</summary>

```js
 initializeArrayWithValues（5，2）;  // [2，2，2，2，2]
```
</details>


### initializeNDArray

创建具有给定值的n维数组.

使用递归.
使用Array.prototype.map（）生成行，其中的每个行都是使用initializeNDArray初始化的新数组.

```js
const initializeNDArray =（val，... args）=&gt;
  args.length === 0
     ？  小时
    ：Array.from（{length：args [0]}）.map（（）=&gt; initializeNDArray（val，... args.slice（1）））;
```

<details>
<summary>Examples</summary>

```js
 initializeNDArray（1，3）;  // [1,1,1]
 initializeNDArray（5，2，2，2）;  // [[[5,5]，[5,5]]，[[5,5]，[5,5]]]
```
</details>


### intersection

返回两个数组中都存在的元素的列表.

从b创建一个Set，然后在a上使用Array.prototype.filter（）来仅保留b中包含的值.

```js
const交集=（a，b）=&gt; {
  const s = new Set（b）;
  返回a.filter（x =&gt; s.has（x））;
};
```

<details>
<summary>Examples</summary>

```js
 相交（[1，2，3]，[4，3，2]）;  // [2，3]
```
</details>


### intersectionBy

将提供的函数应用于两个数组的每个数组元素后，返回两个数组中存在的元素的列表.

通过对b中的所有元素应用fn创建一个Set，然后在a上使用Array.prototype.filter（）仅保留元素，当fn产生b时包含值适用于他们.

```js
const交集By =（a，b，fn）=&gt; {
  const s = new Set（b.map（fn））;
  返回a.filter（x =&gt; s.has（fn（x）））;
};
```

<details>
<summary>Examples</summary>

```js
 junctionBy（[2.1，1.2]，[2.3，3.4]，Math.floor）;  // [2.1]
```
</details>


### intersectionWith

使用提供的比较器函数返回两个数组中都存在的元素的列表.

将Array.prototype.filter（）和Array.prototype.findIndex（）与提供的比较器结合使用，以确定相交值.

```js
constsectionWith =（a，b，comp）=&gt; a.filter（x =&gt; b.findIndex（y =&gt; comp（x，y））！== -1）;
```

<details>
<summary>Examples</summary>

```js
intersectionWith([1, 1.2, 1.5, 3, 0], [1.9, 3, 0, 3.9], (a, b) => Math.round(a) === Math.round(b)); // [1.5, 3, 0]
```
</details>


### isSorted

如果数组按升序排序，则返回“ 1”，如果按降序排序，则返回“ -1”，如果未排序则返回“ 0”.

计算前两个元素的排序方向.
使用Object.entries（）遍历数组对象并成对比较它们.
如果方向更改，则返回0；如果到达最后一个元素，则返回方向.

```js
isSorted常量= ARR =&gt; {
  让方向=-（arr [0]-arr [1]）;
  为（让arr.entries（）的[i，val]为{
     方向=！方向  -（arr [i-1]-arr [i]）：方向；
     如果（i === arr.length-1）返回！direction？  0：方向；
    否则（（val-arr [i + 1]）*方向&gt; 0）返回0;
  }
};
```

<details>
<summary>Examples</summary>

```js
 isSorted（[0，1，2，2]）;  // 1
 isSorted（[4，3，2]）;  // -1
 isSorted（[4，3，5]）;  // 0
```
</details>


### join

将数组的所有元素连接到字符串中并返回此字符串.
使用分隔符和结尾分隔符.

使用Array.prototype.reduce（）将元素组合成一个字符串.
省略第二个参数“ separator”，以使用默认的分隔符“&#39;”.
省略第三个参数“ end”，默认情况下使用与“ separator”相同的值.

```js
const join =（arr，分隔符=&#39;，&#39;，end =分隔符）=&gt;
  减少（
    （acc，val，i）=&gt;
      我===长度-2
         ？  acc + val +结束
        ：i ===长度-1
           ？  acc + val
          ：acc + val +分隔符，
    ''
  );
```

<details>
<summary>Examples</summary>

```js
 join（[&#39;pen&#39;，&#39;pineapple&#39;，&#39;apple&#39;，&#39;pen&#39;]，&#39;，&#39;，&#39;＆&#39;）;  //“笔，菠萝，苹果和笔”
 join（[&#39;pen&#39;，&#39;pineapple&#39;，&#39;apple&#39;，&#39;pen&#39;]，&#39;，&#39;）;  //“笔，菠萝，苹果，笔”
 join（[&#39;pen&#39;，&#39;pineapple&#39;，&#39;apple&#39;，&#39;pen&#39;]））;  //“笔，菠萝，苹果，笔”
```
</details>



将对象数组转换为仅包含指定“ columns”的逗号分隔值（CSV）字符串.

使用Array.prototype.join（delimiter）组合列中的所有名称以创建第一行.
使用Array.prototype.map（）和Array.prototype.reduce（）为每个对象创建一行，用空字符串替换不存在的值，仅映射“列”中的值.
使用Array.prototype.join（&#39;\ n&#39;）将所有行合并为一个字符串.
省略第三个参数“定界符”，以使用默认定界符“，”.

```js
const JSONtoCSV =（arr，columns，delimiter =&#39;，&#39;）=&gt;
  [
    column.join（定界符），
    ... arr.map（obj =&gt;
      columns.reduce（
         （acc，key）=&gt;`$ {acc} $ {！acc.length？  ”：定界符}“ $ {！obj [key]？”：obj [key]}“`，
        ''
      )
    )
  ] .join（&#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
 JSONtoCSV（[{{a：1，b：2}，{a：3，b：4，c：5}，{a：6}，{b：7}]，[&#39;a&#39;，&#39;b&#39;]） ;  //&#39;a，b \ n“ 1”，“ 2” \ n“ 3”，“ 4” \ n“ 6”，“” \ n“”，“ 7”&#39;
 JSONtoCSV（[{{a：1，b：2}，{a：3，b：4，c：5}，{a：6}，{b：7}]，[&#39;a&#39;，&#39;b&#39;]， &#39;;&#39;）;  //&#39;a; b \ n“ 1”;“ 2” \ n“ 3”;“ 4” \ n“ 6”;“” \ n“”;“ 7”&#39;
```
</details>


### last

返回数组中的最后一个元素.

使用`arr.length-1`计算给定数组的最后一个元素的索引并返回它.

```js
const last = arr =&gt; arr [arr.length-1];
```

<details>
<summary>Examples</summary>

```js
 last（[1,2,3]）;  // 3
```
</details>


### longestItem

接受任意数量的可迭代对象或具有length属性的对象，并返回最长的对象.
如果多个对象的长度相同，则将返回第一个.
如果未提供任何参数，则返回`undefined`.

Use `Array.prototype.reduce()`, comparing the `length` of objects to find the longest one.

```js
const longestItem =（... vals）=&gt; vals.reduce（（a，x）=&gt;（x.length&gt; a.length？x：a））;
```

<details>
<summary>Examples</summary>

```js
 longestItem（&#39;this&#39;，&#39;is&#39;，&#39;a&#39;，&#39;testcase&#39;）;  // &#39;测试用例&#39;
 longestItem（... [&#39;a&#39;，&#39;ab&#39;，&#39;abc&#39;]））;  //&#39;abc&#39;
 longestItem（... [&#39;a&#39;，&#39;ab&#39;，&#39;abc&#39;]，&#39;abcd&#39;）;  // &#39;A B C D&#39;
 longestItem（[1、2、3]，[1、2]，[1、2、3、4、5]）;  // [1、2、3、4、5]
 longestItem（[1,2,3]，&#39;foobar&#39;）;  //&#39;foobar&#39;
```
</details>



使用函数将数组的值映射到对象，其中键-值对由字符串化的值（作为键）和映射的值组成.

 使用匿名内部函数作用域声明未定义的内存空间，并使用闭包存储返回值.  使用新的“数组”将数组及其功能映射到其数据集，并使用逗号运算符返回第二步，而无需从一个上下文移到另一个上下文（由于闭包和操作顺序）.

```js
const mapObject =（arr，fn）=&gt;
  （a =&gt;（
    （a = [arr，arr.map（fn）]），a [0] .reduce（（acc，val，ind）=&gt;（（acc [val] = a [1] [ind]），acc）， {}）
  ))();
```

<details>
<summary>Examples</summary>

```js
const squareIt = arr =&gt; mapObject（arr，a =&gt; a * a）;
 squareIt（[1,2,3]）;  // {1：1，2：4，4，3：9}
```
</details>


### maxN

从提供的数组中返回最大n个元素.
如果`n`大于或等于提供的数组长度，则返回原始数组（降序排列）.

将Array.prototype.sort（）与散布运算符（...）结合使用可创建该数组的浅表副本，并按降序对其进行排序.
使用Array.prototype.slice（）获取指定数量的元素.
省略第二个参数n，以获取一个单元素数组.

```js
const maxN =（arr，n = 1）=&gt; [... arr] .sort（（a，b）=&gt; b-a）.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 maxN（[1,2,3]）;  // [3]
 maxN（[1,2,3]，2）;  // [3,2]
```
</details>


### minN

从提供的数组中返回n个最小元素.
如果`n`大于或等于提供的数组的长度，则返回原始数组（以升序排列）.

使用`Array.prototype.sort（）`结合传播运算符（`...`）来创建数组的浅表克隆，并按升序对其进行排序.
使用Array.prototype.slice（）获取指定数量的元素.
省略第二个参数n，以获取一个单元素数组.

```js
const minN =（arr，n = 1）=&gt; [... arr] .sort（（a，b）=&gt; a-b）.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 由（[1，2，3]）;  // [1]
 由（[1，2，3]，2）;  // [1,2]
```
</details>


### none

如果提供的谓词函数对集合中的所有元素都返回“ false”，则返回“ true”，否则返回“ false”.

使用Array.prototype.some（）来测试集合中是否有任何元素基于fn返回true.
省略第二个参数`fn`，以使用`Boolean&#39;作为默认值.

```js
const none =（arr，fn = Boolean）=&gt;！arr.some（fn）;
```

<details>
<summary>Examples</summary>

```js
 none（[0，1，3，0]，x =&gt; x == 2）;  //正确
 none（[0，0，0]）;  //正确
```
</details>


### nthElement

返回数组的第n个元素.

使用Array.prototype.slice（）获得第一个包含第n个元素的数组.
如果索引超出范围，则返回`undefined`.
省略第二个参数n，以获取数组的第一个元素.

```js
const nthElement =（arr，n = 0）=&gt;（n === -1？arr.slice（n）：arr.slice（n，n + 1））[0];
```

<details>
<summary>Examples</summary>

```js
 nthElement（[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]，1）;  //&#39;b&#39;
 nthElement（[&#39;a&#39;，&#39;b&#39;，&#39;b&#39;]，-3）;  // &#39;一种&#39;
```
</details>


### offset

将指定数量的元素移动到数组的末尾.

两次使用Array.prototype.slice（）获取指定索引之后的元素和该索引之前的元素.
使用散布运算符（`...`）将两者合并为一个数组.
如果`offset`为负，则元素将从头到尾移动.

```js
const offset =（arr，offset）=&gt; [... arr.slice（offset），... arr.slice（0，offset）];
```

<details>
<summary>Examples</summary>

```js
 offset（[1,2,3,4,5]，2）;  // [3，4，5，1，2]
 offset（[1,2,3,4,5]，-2）;  // [4，5，1，2，3]
```
</details>


### partition

将元素分为两个数组，具体取决于每个元素提供的函数的真实性.

使用Array.prototype.reduce（）创建一个由两个数组组成的数组.
使用Array.prototype.push（）将第一个数组中的fn返回true的元素添加到第二个数组中false返回false的元素.

```js
const partition =（arr，fn）=&gt;
  减少（
    （acc，val，i，arr）=&gt; {
       acc [fn（val，i，arr）吗？  0：1] .push（val）;
      返回acc；
    },
    [[], []]
  );
```

<details>
<summary>Examples</summary>

```js
const users = [{{user：&#39;barney&#39;，age：36，active：false}，{user：&#39;fred&#39;，age：40，active：true}]；
 分区（用户，o =&gt; o.active）;  // [[{&#39;user&#39;：&#39;fred&#39;，&#39;age&#39;：40，&#39;active&#39;：true}]，[{&#39;user&#39;：&#39;barney&#39;，&#39;age&#39;：36，&#39;active&#39;：false}] ]
```
</details>



 ⚠警告**：此函数的执行时间随每个数组元素呈指数增加.  超过8到10个条目的任何内容都会导致您的浏览器在尝试解决所有不同的组合时挂起.

生成数组元素的所有排列（包含重复项）.

使用递归.
对于给定数组中的每个元素，为其其余元素创建所有部分置换.
使用“ Array.prototype.map（）”将元素与每个部分排列组合，然后使用“ Array.prototype.reduce（）”将所有排列组合在一个数组中.
基本情况是数组“ length”等于“ 2”或“ 1”.

```js
const permutations = arr =&gt; {
   if（arr.length &lt;= 2）返回arr.length === 2？  [arr，[arr [1]，arr [0]]]：arr;
  返回arr.reduce（
    （acc，item，i）=&gt;
      acc.concat（
        排列（[... arr.slice（0，i），... arr.slice（i + 1）]）.map（val =&gt; [item，... val]）
      ),
    []
  );
};
```

<details>
<summary>Examples</summary>

```js
 排列（[1，33，5]）;  // [[1，33，5]，[1，5，33]，[33，1，5]，[33，5，1]，[5，1，33]，[5，33，1] ]
```
</details>


### pull

突变原始数组以滤除指定的值.

使用Array.prototype.filter（）和Array.prototype.includes（）提取不需要的值.
使用“ Array.prototype.length = 0”通过将其传递的长度重置为零来更改传递的数组，并使用“ Array.prototype.push（）”仅使用提取的值重新填充它.

```js
const pull =（arr，... args）=&gt; {
   让argState = Array.isArray（args [0]）吗？  args [0]：args;
  让拉= arr.filter（（v，i）=&gt;！argState.includes（v））;
  arr.length = 0;
  pull.forEach（v =&gt; arr.push（v））;
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;a&#39;，&#39;b&#39;，&#39;c&#39;];
 pull（myArray，&#39;a&#39;，&#39;c&#39;）;  // myArray = [&#39;b&#39;，&#39;b&#39;]
```
</details>



突变原始数组以滤除指定索引处的值.

使用Array.prototype.filter（）和Array.prototype.includes（）提取不需要的值.
使用“ Array.prototype.length = 0”通过将其传递的长度重置为零来更改传递的数组，并使用“ Array.prototype.push（）”仅使用提取的值重新填充它.
使用Array.prototype.push（）来跟踪提取的值

```js
const pullAtIndex =（arr，pullArr）=&gt; {
  让我们删除= [];
  让拉= arr
    .map（（v，i）=&gt;（pullArr.includes（i）？已移除.push（v）：v））
    .filter（（v，i）=&gt;！pullArr.includes（i））;
  arr.length = 0;
  pull.forEach（v =&gt; arr.push（v））;
  返回已删除；
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;d&#39;];
 让pull = pullAtIndex（myArray，[1，3]）;  // myArray = [&#39;a&#39;，&#39;c&#39;]，pull = [&#39;b&#39;，&#39;d&#39;]
```
</details>



 突变原始数组以滤除指定的值.  返回移除的元素.

使用Array.prototype.filter（）和Array.prototype.includes（）提取不需要的值.
使用“ Array.prototype.length = 0”通过将其传递的长度重置为零来更改传递的数组，并使用“ Array.prototype.push（）”仅使用提取的值重新填充它.
使用Array.prototype.push（）来跟踪提取的值

```js
const pullAtValue =（arr，pullArr）=&gt; {
  让我们删除= []，
    pushToRemove = arr.forEach（（v，i）=&gt;（pullArr.includes（v）？remove.push（v）：v）），
    mutateTo = arr.filter（（v，i）=&gt;！pullArr.includes（v））;
  arr.length = 0;
  mutateTo.forEach（v =&gt; arr.push（v））;
  返回已删除；
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;d&#39;];
 让pull = pullAtValue（myArray，[&#39;b&#39;，&#39;d&#39;]）;  // myArray = [&#39;a&#39;，&#39;c&#39;]，pull = [&#39;b&#39;，&#39;d&#39;]
```
</details>



根据给定的迭代器函数，对原始数组进行突变以滤除指定的值.

检查函数中是否提供了最后一个参数.
使用Array.prototype.map（）将迭代器函数fn应用于所有数组元素.
使用Array.prototype.filter（）和Array.prototype.includes（）提取不需要的值.
使用“ Array.prototype.length = 0”通过将其传递的长度重置为零来更改传递的数组，并使用“ Array.prototype.push（）”仅使用提取的值重新填充它.

```js
const pullBy =（arr，... args）=&gt; {
  const length = args.length;
   令fn =长度&gt; 1吗？  args [length-1]：未定义；
   fn = typeof fn ==&#39;函数&#39;吗？  （args.pop（），fn）：未定义;
  让argState =（Array.isArray（args [0]）？args [0]：args）.map（val =&gt; fn（val））;
  让拉= arr.filter（（v，i）=&gt;！argState.includes（fn（v）））;
  arr.length = 0;
  pull.forEach（v =&gt; arr.push（v））;
};
```

<details>
<summary>Examples</summary>

```js
var myArray = [{x：1}，{x：2}，{x：3}，{x：1}];
 pullBy（myArray，[{x：1}，{x：3}]，o =&gt; ox）;  // myArray = [{x：2}]
```
</details>


### reducedFilter

根据条件过滤对象数组，同时也过滤掉未指定的键.

使用Array.prototype.filter（）基于谓词fn过滤数组，以便它返回条件返回真实值的对象.
在过滤后的数组上，使用Array.prototype.map（）返回新对象，并使用Array.prototype.reduce（）过滤掉未作为key参数提供的键.

```js
const reduceFilter =（数据，键，fn）=&gt;
  data.filter（fn）.map（el =&gt;
    keys.reduce（（acc，key）=&gt; {
      acc [key] = el [key];
      返回acc；
    }, {})
  );
```

<details>
<summary>Examples</summary>

```js
const data = [
  {
    编号：1
    名称：“ john”，
    年龄：24
  },
  {
    编号：2
    名称：“ mike”，
    年龄：50
  }
];

 reduceFilter（data，[&#39;id&#39;，&#39;name&#39;]，item =&gt; item.age&gt; 24）;  // [{id：2，name：&#39;mike&#39;}]
```
</details>


### reduceSuccessive

对一个累加器和该数组中的每个元素（从左到右）应用一个函数，返回一个依次减小值的数组.

使用Array.prototype.reduce（）将给定函数应用于给定数组，存储每个新结果.

```js
const reduceSuccessive =（arr，fn，acc）=&gt;
  arr.reduce（（res，val，i，arr）=&gt;（res.push（fn（res.slice（-1）[0]，val，i，arr）），res），[acc]）;
```

<details>
<summary>Examples</summary>

```js
 reduceSuccessive（[1,2,3,4,5,6]，（acc，val）=&gt; acc + val，0）;  // [0，1，3，6，10，15，21]
```
</details>


### reduceWhich

应用提供的函数设置比较规则后，返回数组的最小值/最大值.

将Array.prototype.reduce（）与comparator函数结合使用，以获取数组中适当的元素.
您可以省略第二个参数“比较器”，以使用默认参数来返回数组中的最小元素.

```js
const reduceWhich =（arr，比较器=（a，b）=&gt; a-b）=&gt;
  arr.reduce（（a，b）=&gt;（比较器（a，b）&gt; = 0？b：a））;
```

<details>
<summary>Examples</summary>

```js
 reduceWhich（[1，3，2]）;  // 1
 reduceWhich（[1，3，2]，（a，b）=&gt; b-a）;  // 3
reduceWhich(
  [{名称：&#39;Tom&#39;，年龄：12}，{名称：&#39;Jack&#39;，年龄：18}，{名称：&#39;Lucy&#39;，年龄：9}]，
  （a，b）=&gt; a.age-b.age
 ）;  // {name：“ Lucy”，age：9}
```
</details>


### reject

根据谓词函数过滤数组的值，仅返回谓词函数返回true的值.

将Array.prototype.filter（）与谓词函数pred结合使用，以仅返回pred（）返回true的值.

```js
const reject =（pred，array）=&gt; array.filter（（... args）=&gt;！pred（... args））;复制代码
```

<details>
<summary>Examples</summary>

```js
 拒绝（x =&gt; x％2 === 0，[1,2,3,4,5]）;  // [1、3、5]
 reject（word =&gt; word.length&gt; 4，[&#39;Apple&#39;，&#39;Pear&#39;，&#39;Kiwi&#39;，&#39;Banana&#39;]）;  // [&#39;Pear&#39;，&#39;Kiwi&#39;]
```
</details>


### remove

从给定函数为其返回false的数组中删除元素.

使用Array.prototype.filter（）查找返回真实值的数组元素，并使用Array.prototype.reduce（）使用Array.prototype.splice（）删除元素.
“ func”由三个参数（“ value”，“ index”，“ array”）调用.

```js
const remove =（arr，func）=&gt;
  Array.isArray（arr）
     ？  arr.filter（func）.reduce（（acc，val）=&gt; {
        arr.splice（arr.indexOf（val），1）;
        返回acc.concat（val）;
      }, [])
    : [];
```

<details>
<summary>Examples</summary>

```js
 remove（[1,2,3,4]，n =&gt; n％2 === 0）;  // [2，4]
```
</details>


### sample

从数组中返回一个随机元素.

使用“ Math.random（）”生成一个随机数，将其乘以“长度”，然后使用“ Math.floor（）”将其四舍五入为最接近的整数.
此方法也适用于字符串.

```js
const sample = arr =&gt; arr [Math.floor（Math.random（）* arr.length）];
```

<details>
<summary>Examples</summary>

```js
 样本（[3，7，9，11]）;  // 9
```
</details>


### sampleSize

从“数组”获取唯一键处的“ n”个随机元素，直至“数组”的大小.

使用 [Fisher-Yates algorithm](https://github.com/30-seconds/30-seconds-of-code#shuffle).
使用Array.prototype.slice（）获取第一个n元素.
省略第二个参数“ n”以从数组中随机获取一个元素.

```js
const sampleSize =（[[arr]，n = 1）=&gt; {
  令m =长度
  而（m）{
    const i = Math.floor（Math.random（）* m--）;
    [arr [m]，arr [i]] = [arr [i]，arr [m]];
  }
  返回arr.slice（0，n）;
};
```

<details>
<summary>Examples</summary>

```js
 sampleSize（[1，2，3]，2）;  // [3,1]
 sampleSize（[1、2、3]，4）;  // [2,3,1]
```
</details>


### shank

具有与以下功能相同的功能 [`Array.prototype.splice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)，但返回一个新数组而不是对原始数组进行变异.

在删除现有元素和/或添加新元素之后，使用Array.prototype.slice（）和Array.prototype.concat（）获得具有新内容的新数组.
省略第二个参数“ index”，从“ 0”开始.
省略第三个参数“ delCount”，以删除“ 0”个元素.
省略第四个参数`elements`，以便不添加任何新元素.

```js
const shank =（arr，index = 0，delCount = 0，... elements）=&gt;
  rr
    .slice（0，索引）
    .concat（元素）
    .concat（arr.slice（index + delCount））;
```

<details>
<summary>Examples</summary>

```js
const名称= [&#39;alpha&#39;，&#39;bravo&#39;，&#39;charlie&#39;];
 const namesAndDelta = shank（names，1，0，&#39;delta&#39;）;  // [&#39;&#39;alpha&#39;，&#39;delta&#39;，&#39;bravo&#39;，&#39;charlie&#39;]
 const namesNoBravo = shank（names，1，1）;  // [&#39;&#39;alpha&#39;，&#39;charlie&#39;]
 console.log（names）;  // [&#39;alpha&#39;，&#39;bravo&#39;，&#39;charlie&#39;]
```
</details>


### shuffle

随机化数组值的顺序，返回一个新数组.

使用 [Fisher-Yates algorithm](https://github.com/30-seconds/30-seconds-of-code#shuffle) 重新排列数组的元素.

```js
const shuffle =（[... arr]）=&gt; {
  令m =长度
  而（m）{
    const i = Math.floor（Math.random（）* m--）;
    [arr [m]，arr [i]] = [arr [i]，arr [m]];
  }
  返回arr;
};
```

<details>
<summary>Examples</summary>

```js
const foo = [1,2,3];
 shuffle（foo）;  // [2，3，1]，foo = [1,2,3]
```
</details>


### similarity

返回同时出现在两个数组中的元素的数组.

使用Array.prototype.filter（）删除不属于value的值，这些值是由Array.prototype.includes（）确定的.

```js
const相似=（arr，values）=&gt; arr.filter（v =&gt; values.includes（v））;
```

<details>
<summary>Examples</summary>

```js
 相似度（[1,2,3]，[1,2,4]）;  // [1，2]
```
</details>


### sortedIndex

返回应将值插入数组以保持其排序顺序的最低索引.

检查数组是否以降序排序（松散）.
使用Array.prototype.findIndex（）查找适当的索引，元素应插入该位置.

```js
const sortedIndex =（arr，n）=&gt; {
  const isDescending = arr [0]&gt; arr [arr.length-1];
  const index = arr.findIndex（el =&gt;（isDescending？n&gt; = el：n &lt;= el））;;
   返回索引=== -1吗？  arr.length：索引;
};
```

<details>
<summary>Examples</summary>

```js
 sortedIndex（[5，3，2，1]，4）;  // 1
 sortedIndex（[30，50]，40）;  // 1
```
</details>


### sortedIndexBy

根据提供的迭代器函数，返回应将值插入数组以保持其排序顺序的最低索引.

检查数组是否以降序排序（松散）.
根据迭代器函数fn，使用Array.prototype.findIndex（）查找要插入元素的适当索引.

```js
const sortedIndexBy =（arr，n，fn）=&gt; {
  const isDescending = fn（arr [0]）&gt; fn（arr [arr.length-1]）;
  const val = fn（n）;
  const index = arr.findIndex（el =&gt;（isDescending？val&gt; = fn（el）：val &lt;= fn（el））））;
   返回索引=== -1吗？  arr.length：索引;
};
```

<details>
<summary>Examples</summary>

```js
 sortedIndexBy（[{x：4}，{x：5}]，{x：4}，o =&gt; ox）;  // 0
```
</details>


### sortedLastIndex

返回将值插入数组以保持其排序顺序的最高索引.

检查数组是否以降序排序（松散）.
使用Array.prototype.reverse（）和Array.prototype.findIndex（）查找适当的最后一个索引，将元素插入该位置.

```js
const sortedLastIndex =（arr，n）=&gt; {
  const isDescending = arr [0]&gt; arr [arr.length-1];
  const index = arr.reverse（）.findIndex（el =&gt;（isDescending？n &lt;= el：n&gt; = el））;
   返回索引=== -1吗？  0：长度-索引;
};
```

<details>
<summary>Examples</summary>

```js
 sortedLastIndex（[10，20，30，30，40]，30）;  // 4
```
</details>


### sortedLastIndexBy

根据提供的迭代器函数，返回应将值插入数组以保持其排序顺序的最高索引.

检查数组是否以降序排序（松散）.
使用Array.prototype.map（）将迭代器函数应用于数组的所有元素.
根据提供的迭代器函数，使用Array.prototype.reverse（）和Array.prototype.findIndex（）查找适当的最后一个索引，该元素应插入该位置.

```js
const sortedLastIndexBy =（arr，n，fn）=&gt; {
  const isDescending = fn（arr [0]）&gt; fn（arr [arr.length-1]）;
  const val = fn（n）;
  const index = arr
    .map（fn）
    .相反（）
    .findIndex（el =&gt;（isDescending？val &lt;= el：val&gt; = el））;
   返回索引=== -1吗？  0：长度-索引;
};
```

<details>
<summary>Examples</summary>

```js
 sortedLastIndexBy（[{x：4}，{x：5}]，{x：4}，o =&gt; ox）;  // 1
```
</details>



对数组执行稳定的排序，并在它们的值相同时保留项目的初始索引.
不更改原始数组，而是返回一个新数组.

使用Array.prototype.map（）将输入数组的每个元素与其对应的索引配对.
Use `Array.prototype.sort()` and a `compare` function to sort the list, preserving their initial order if the items compared are equal.
使用Array.prototype.map（）转换回初始数组项.

```js
const stableSort =（arr，compare）=&gt;
  rr
    .map（（item，index）=&gt;（{item，index}））
    .sort（（a，b）=&gt; compare（a.item，b.item）|| a.index-b.index）
    .map（（{{item}）=&gt; item）;
```

<details>
<summary>Examples</summary>

```js
const arr = [0，1，2，3，4，5，6，7，8，9，10];
 const stable = stableSort（arr，（）=&gt; 0）;  // [0，1，2，3，4，5，6，7，8，9，10]
```
</details>


### symmetricDifference

返回两个数组之间的对称差，而不过滤掉重复的值.

从每个数组创建一个Set，然后在每个数组上使用Array.prototype.filter（）以仅保留彼此不包含的值.

```js
const symmetricDifference =（a，b）=&gt; {
  const sA = new Set（a），
    sB =新Set（b）;
  return [... a.filter（x =&gt;！sB.has（x）），... b.filter（x =&gt;！sA.has（x））];
};
```

<details>
<summary>Examples</summary>

```js
 symmetricDifference（[1,2,3]，[1,2,4]）;  // [3，4]
 symmetricDifference（[1，2，2]，[1，3，1]）;  // [2，2，3]
```
</details>


### symmetricDifferenceBy

将提供的函数应用于两个数组的每个数组元素后，返回两个数组之间的对称差.

通过对每个数组的元素应用fn来创建Set，然后对每个元素使用Array.prototype.filter（），以仅保留彼此不包含的值.

```js
const symmetricDifferenceBy =（a，b，fn）=&gt; {
  const sA = new Set（a.map（v =&gt; fn（v）））
    sB =新集（b.map（v =&gt; fn（v）））;
  return [... a.filter（x =&gt;！sB.has（fn（x））），... b.filter（x =&gt;！sA.has（fn（x）））];
};
```

<details>
<summary>Examples</summary>

```js
 symmetricDifferenceBy（[2.1，1.2]，[2.3，3.4]，Math.floor）;  // [1.2，3.4]
```
</details>


### symmetricDifferenceWith

使用提供的函数作为比较器，返回两个数组之间的对称差.

使用`Array.prototype.filter（）`和`Array.prototype.findIndex（）`查找合适的值.

```js
const symmetricDifferenceWith =（arr，val，comp）=&gt; [
  ... arr.filter（a =&gt; val.findIndex（b =&gt; comp（a，b））=== -1），
  ... val.filter（a =&gt; arr.findIndex（b =&gt; comp（a，b））=== -1）
];
```

<details>
<summary>Examples</summary>

```js
symmetricDifferenceWith(
  [1, 1.2, 1.5, 3, 0],
  [1.9, 3, 0, 3.9],
  （a，b）=&gt; Math.round（a）=== Math.round（b）
); // [1, 1.2, 3.9]
```
</details>


### tail

返回数组中除第一个元素外的所有元素.

如果数组的长度大于1，则返回Array.prototype.slice（1），否则返回整个数组.

```js
const tail = arr =&gt;（arr.length&gt; 1？arr.slice（1）：arr）;
```

<details>
<summary>Examples</summary>

```js
 tail（[1,2,3]）;  // [2,3]
 尾巴[[1]）;  // [1]
```
</details>


### take

返回一个数组，该数组从开头删除了n个元素.

使用Array.prototype.slice（）从一开始就使用n个元素创建数组的一部分.

```js
const take =（arr，n = 1）=&gt; arr.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 采取（[1,2,3]，5）;  // [1、2、3]
 take（[1,2,3]，0）;  // []
```
</details>


### takeRight

返回从末尾删除n个元素的数组.

使用Array.prototype.slice（）来创建数组的一个切片，其中数组的末尾取n个元素.

```js
const takeRight =（arr，n = 1）=&gt; arr.slice（arr.length-n，arr.length）;
```

<details>
<summary>Examples</summary>

```js
 takeRight（[1,2,3]，2）;  // [2，3]
 takeRight（[1,2,3]）;  // [3]
```
</details>


### takeRightWhile

 从数组末尾删除元素，直到传递的函数返回“ true”为止.  返回移除的元素.

使用一个Array.prototype.reduceRight（）遍历数组，并在函数返回假值时累加元素.

```js
const takeRightWhile =（arr，func）=&gt;
  arr.reduceRight（（acc，el）=&gt;（func（el）？acc：[el，... acc]），[]）;
```

<details>
<summary>Examples</summary>

```js
 takeRightWhile（[1,2,3,4]，n =&gt; n &lt;3）;  // [3，4]
```
</details>


### takeWhile

 删除数组中的元素，直到传递的函数返回“ true”为止.  返回移除的元素.

通过在Array.prototype.entries（）上使用for循环来遍历数组，直到函数返回的值为true为止.
使用Array.prototype.slice（）返回删除的元素.

```js
const takeWhile =（arr，func）=&gt; {
  如果（func（val））返回arr.slice（0，i），则为arr.entries（）的（const [i，val]）；
  返回arr;
};
```

<details>
<summary>Examples</summary>

```js
 takeWhile（[1,2,3,4]，n =&gt; n&gt; = 3）;  // [1，2]
```
</details>


### toHash

将给定的类数组简化为值哈希（键控数据存储）.

给定一个Iterable或类似Array的结构，请在提供的对象上调用Array.prototype.reduce.call（）以遍历它，并返回一个由参考值作为键的对象.

```js
const toHash =（object，key）=&gt;
  Array.prototype.reduce.call(
    宾语，
    （acc，data，index）=&gt;（（acc [！key？index：data [key]] = data），acc），
    {}
  );
```

<details>
<summary>Examples</summary>

```js
 toHash（[4，3，2，1]）;  // {0：4，1：3，2：2，3：1}
 toHash（[{a：&#39;label&#39;}]，&#39;a&#39;）;  // {标签：{a：&#39;label&#39;}}
//更深入的示例：
let users = [{{id：1，first：&#39;Jon&#39;}，{id：2，first：&#39;Joe&#39;}，{id：3，first：&#39;Moe&#39;}];
让经理= [{经理：1，雇员：[2，3]}];
//我们在这里使用function是因为我们想要一个可绑定的引用，但是引用哈希的闭包也将起作用.
managers.forEach(
  经理=&gt;
    （manager.employees = manager.employees.map（function（id）{
      返回this [id];
    }，toHash（users，&#39;id&#39;）））
);
 管理人员；  // [{经理：1，员工：[{id：2，第一个：“ Joe”}，{id：3，第一个：“ Moe”}]}]
```
</details>


### union

一次返回两个数组中任何一个存在的每个元素.

创建一个具有所有值a和b的Set并将其转换为数组.

```js
const union =（a，b）=&gt; Array.from（new Set（[... a，... b]））;
```

<details>
<summary>Examples</summary>

```js
 union（[1、2、3]，[4、3、2]）;  // [1,2,3,4]
```
</details>


### unionBy

将提供的函数应用于两个数组的每个数组元素后，一次返回两个数组中的任何一个数组中存在的每个元素.

通过将所有fn应用于a的所有值来创建Set.
从`a`和`b`中的所有元素创建一个`Set`，其值在应用`fn&#39;之后与先前创建的set中的值不匹配.
返回转换为数组的最后一组.

```js
const unionBy =（a，b，fn）=&gt; {
  const s = new Set（a.map（fn））;
  return Array.from（new Set（[... a，... b.filter（x =&gt;！s.has（fn（x））））））;;
};
```

<details>
<summary>Examples</summary>

```js
 unionBy（[2.1]，[1.2，2.3]，Math.floor）;  // [2.1，1.2]
```
</details>


### unionWith

使用提供的比较器函数一次返回两个数组中任何一个存在的每个元素.

使用Array.prototype.findIndex（）创建一个具有所有a值和b值的Set，比较器在a中找不到匹配项.

```js
const unionWith =（a，b，comp）=&gt;
  Array.from(new Set([...a, ...b.filter(x => a.findIndex(y => comp(x, y)) === -1)]));
```

<details>
<summary>Examples</summary>

```js
 unionWith（[1，1.2，1.5，3，0]，[1.9，3，0，3.9]，（a，b）=&gt; Math.round（a）=== Math.round（b））;  // [1，1.2，1.5，3，0，3.9]
```
</details>


### uniqueElements

返回数组的所有唯一值.

使用ES6`Set`和`... rest`运算符丢弃所有重复的值.

```js
const uniqueElements = arr =&gt; [... new Set（arr）];
```

<details>
<summary>Examples</summary>

```js
 uniqueElements（[1、2、2、3、4、4、5]）;  // [1、2、3、4、5]
```
</details>


### uniqueElementsBy

根据提供的比较器函数返回数组的所有唯一值.

根据比较器函数fn，将“ Array.prototype.reduce（）”和“ Array.prototype.some（）”用于仅包含每个值的第一个唯一出现的数组.
比较器函数有两个参数：比较的两个元素的值.

```js
const uniqueElementsBy =（arr，fn）=&gt;
  arr.reduce（（acc，v）=&gt; {
    如果（！acc.some（x =&gt; fn（v，x）））acc.push（v）;
    返回acc；
  }, []);
```

<details>
<summary>Examples</summary>

```js
uniqueElementsBy(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，值：&#39;d&#39;}，
    {id：0，值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{{id：0，value：&#39;a&#39;}，{id：1，value：&#39;b&#39;}，{id：2，value：&#39;c&#39;}]
```
</details>


### uniqueElementsByRight

从提供的比较器函数开始，从右开始返回数组的所有唯一值.

根据比较器函数fn，将Array.prototype.reduceRight（）和Array.prototype.some（）用于仅包含每个值的最后唯一出现的数组.
比较器函数有两个参数：比较的两个元素的值.

```js
const uniqueElementsByRight =（arr，fn）=&gt;
  arr.reduceRight（（acc，v）=&gt; {
    如果（！acc.some（x =&gt; fn（v，x）））acc.push（v）;
    返回acc；
  }, []);
```

<details>
<summary>Examples</summary>

```js
uniqueElementsByRight(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，值：&#39;d&#39;}，
    {id：0，值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{{id：0，value：&#39;e&#39;}，{id：1，value：&#39;d&#39;}，{id：2，value：&#39;c&#39;}]
```
</details>


### uniqueSymmetricDifference

返回两个数组之间的唯一对称差异，不包含两个数组中的重复值.

在每个数组上使用Array.prototype.filter（）和Array.prototype.includes（）删除另一个数组中包含的值，然后从结果中创建一个Set，删除重复的值.

```js
const uniqueSymmetricDifference =（a，b）=&gt; [
  ... new Set（[... a.filter（v =&gt;！b.includes（v）），... b.filter（v =&gt;！a.includes（v））]）
];
```

<details>
<summary>Examples</summary>

```js
 uniqueSymmetricDifference（[1,2,3]，[1,2,4]）;  // [3，4]
 uniqueSymmetricDifference（[1、2、2]，[1、3、1]）;  // [2，3]
```
</details>


### unzip

创建一个数组数组，将由以下元素产生的数组中的元素取消组合 [zip](#zip).

使用Math.max.apply（）获取数组中最长的子数组，使用Array.prototype.map（）使每个元素成为数组.
使用Array.prototype.reduce（）和Array.prototype.forEach（）将分组值映射到单个数组.

```js
const unzip = arr =&gt;
  减少（
    （acc，val）=&gt;（val.forEach（（v，i）=&gt; acc [i] .push（v）），acc），
    Array.from（{
      长度：Math.max（... arr.map（x =&gt; x.length））
    }）.map（x =&gt; []）
  );
```

<details>
<summary>Examples</summary>

```js
 解压缩（[[[&#39;a&#39;，1，true]，[&#39;b&#39;，2，false]]））;  // [[&#39;a&#39;，&#39;b&#39;]，[1，2]，[true，false]]
 解压缩（[[&#39;a&#39;，1，true]，[&#39;b&#39;，2]]）;  // [[&#39;a&#39;，&#39;b&#39;]，[1，2]，[true]]
```
</details>



创建一个元素数组，将由 [zip](#zip) 并应用提供的功能.

使用Math.max.apply（）获取数组中最长的子数组，使用Array.prototype.map（）使每个元素成为数组.
使用Array.prototype.reduce（）和Array.prototype.forEach（）将分组值映射到单个数组.
使用Array.prototype.map（）和散布运算符（...）将fn应用于每个单独的元素组.

```js
const unzipWith =（arr，fn）=&gt;
  rr
    .降低（
      （acc，val）=&gt;（val.forEach（（v，i）=&gt; acc [i] .push（v）），acc），
      Array.from（{
        长度：Math.max（... arr.map（x =&gt; x.length））
      }）.map（x =&gt; []）
    )
    .map（val =&gt; fn（... val））;
```

<details>
<summary>Examples</summary>

```js
 unzipWith（[[1，10，100]，[2，20，200]]，（... args）=&gt; args.reduce（（acc，v）=&gt; acc + v，0））;  // [3，30，300]
```
</details>


### without

筛选出具有指定值之一的数组元素.

使用Array.prototype.filter（）创建一个不包含所有给定值的数组（使用Array！includes（））.

```js
const不带=（arr，... args）=&gt; arr.filter（v =&gt;！args.includes（v））;
```

<details>
<summary>Examples</summary>

```js
 不（[2，1，2，3]，1，2）;  // [3]
```
</details>


### xProd

通过从阵列中创建每个可能的对，在提供的两个阵列中创建一个新阵列.

使用Array.prototype.reduce（），Array.prototype.map（）和Array.prototype.concat（）从两个数组的元素中生成每个可能的对，并将它们保存在一个数组中.

```js
const xProd =（a，b）=&gt; a.reduce（（acc，x）=&gt; acc.concat（b.map（y =&gt; [x，y]）），[]）;
```

<details>
<summary>Examples</summary>

```js
 xProd（[1，2]，[&#39;a&#39;，&#39;b&#39;]）;  // [[1，&#39;a&#39;]，[1，&#39;b&#39;]，[2，&#39;a&#39;]，[2，&#39;b&#39;]]
```
</details>


### zip

创建一个元素数组，根据原始数组中的位置进行分组.

使用`Math.max.apply（）`获取参数中最长的数组.
创建一个以该长度为返回值的数组，并使用带有映射功能的Array.from（）创建一个分组元素数组.
如果参数数组的长度不同，则在找不到值的地方使用“ undefined”.

```js
const zip =（... arrays）=&gt; {
  const maxLength = Math.max（... arrays.map（x =&gt; x.length））;
  return Array.from（{length：maxLength}）.map（（_，i）=&gt; {
    return Array.from（{length：arrays.length}，（_，k）=&gt; arrays [k] [i]）;
  });
};
```

<details>
<summary>Examples</summary>

```js
 zip（[&#39;a&#39;，&#39;b&#39;]，[1，2]，[true，false]）;  // [[&#39;a&#39;，1，true]，[&#39;b&#39;，2，false]]
zip(['a'], [1, 2], [true, false]); // [['a', 1, true], [undefined, 2, false]]
```
</details>


### zipObject

给定一个有效的属性标识符数组和一个值数组，返回一个将属性与值相关联的对象.

由于对象可以具有未定义的值，但不能具有未定义的属性指针，因此属性数组用于通过Array.prototype.reduce（）来确定结果对象的结构.

```js
const zipObject =（属性，值）=&gt;
  props.reduce（（obj，prop，index）=&gt;（（（obj [prop] = values [index]），obj），{}）;
```

<details>
<summary>Examples</summary>

```js
 zipObject（[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]，[1，2]）;  // {a：1，b：2，c：undefined}
 zipObject（[&#39;a&#39;，&#39;b&#39;]，[1、2、3]）;  // {a：1，b：2}
```
</details>



创建一个元素数组，根据原始数组中的位置进行分组，并使用function作为最后一个值来指定应如何组合分组的值.

检查提供的最后一个参数是否为函数.
使用`Math.max（）`获取参数中最长的数组.
创建一个以该长度为返回值的数组，并使用带有映射功能的Array.from（）创建一个分组元素数组.
如果参数数组的长度不同，则在找不到值的地方使用“ undefined”.
该函数由每个组（... group）的元素调用.

```js
const zipWith =（... array）=&gt; {
   const fn = typeof array [array.length-1] ===&#39;function&#39;吗？  array.pop（）：未定义;
  return Array.from（{length：Math.max（... array.map（a =&gt; a.length））}，（_，i）=&gt;
     fn？  fn（... array.map（a =&gt; a [i]））：array.map（a =&gt; a [i]）
  );
};
```

<details>
<summary>Examples</summary>

```js
 zipWith（[1，2]，[10，20]，[100，200]，（a，b，c）=&gt; a + b + c）;  // [111,222]
zipWith(
  [1, 2, 3],
  [10, 20],
  [100, 200],
  （a，b，c）=&gt;（a！= null？a：&#39;a&#39;）+（b！= null？b：&#39;b&#39;）+（c！= null？c：&#39;c&#39;）
 ）;  // [111，222，&#39;3bc&#39;]
```
</details>


---

## 🌐 Browser


### arrayToHtmlList

 将给定的数组元素转换为` <li>  `标签并将其附加到给定ID的列表中.

使用Array.prototype.map（），document.querySelector（）和匿名内部闭包来创建html标签列表.

```js
const arrayToHtmlList =（arr，listID）=&gt;
  （=&gt;（
    (el = document.querySelector('#' + listID)),
     （el.innerHTML + = arr.map（item =&gt;` <li>  $ {item} </li>  `）.join（&#39;&#39;））
  ))();
```

<details>
<summary>Examples</summary>

```js
arrayToHtmlList（[&#39;item 1&#39;，&#39;item 2&#39;]，&#39;myListID&#39;）;
```
</details>


### bottomVisible

如果页面底部可见，则返回“ true”，否则返回“ false”.

使用`scrollY`，`scrollHeight`和`clientHeight`确定页面底部是否可见.

```js
const bottomVisible =（）=&gt;
  document.documentElement.clientHeight + window.scrollY&gt; =
  （document.documentElement.scrollHeight || document.documentElement.clientHeight）;
```

<details>
<summary>Examples</summary>

```js
 bottomVisible（）;  //正确
```
</details>



 NO️**注意：**使用新的异步剪贴板API可以轻松实现相同的功能，该API仍处于试验阶段，应在将来代替此代码段使用.  进一步了解 [here](https://github.com/w3c/clipboard-apis/blob/master/explainer.adoc#writing-to-the-clipboard).

将字符串复制到剪贴板. 
仅由于用户操作（即在“ click”事件侦听器内部）而起作用.

 创建一个新的 <textarea>  `元素，用提供的数据填充它并将其添加到HTML文档中.
使用“ Selection.getRangeAt（）”存储所选范围（如果有）.
使用`document.execCommand（&#39;copy&#39;）`复制到剪贴板.
 移除` <textarea>  HTML文档中的`元素.
最后，使用“ Selection（）.addRange（）”恢复原始选定范围（如果有）.

```js
const copyToClipboard = str =&gt; {
  const el = document.createElement（&#39;textarea&#39;）;
  el.value = str;
  el.setAttribute（&#39;readonly&#39;，&#39;&#39;）;
  el.style.position =&#39;绝对&#39;;
  el.style.left =&#39;-9999px&#39;;
  document.body.appendChild（el）;
  const selected =
     document.getSelection（）.rangeCount&gt; 0？  document.getSelection（）.getRangeAt（0）：否；
  el.select();
  document.execCommand（&#39;copy&#39;）;
  document.body.removeChild（el）;
  如果（已选择）{
    document.getSelection（）.removeAllRanges（）;
    document.getSelection（）.addRange（selected）;
  }
};
```

<details>
<summary>Examples</summary>

```js
 copyToClipboard（ &#39;Lorem存有&#39;）;  //“Lorem存有”复制到剪贴板.
```
</details>



为指定的选择器创建一个具有指定范围，步长和持续时间的计数器.

检查`step`是否具有正确的符号并相应地进行更改.
结合使用setInterval（）和Math.abs（）和Math.floor（）来计算每次绘制新文本之间的时间.
使用document.querySelector（）.innerHTML`更新所选元素的值.
省略第四个参数“ step”以使用默认步骤“ 1”.
省略第五个参数duration以使用默认持续时间2000 ms.

```js
常量计数器=（选择器，开始，结束，步骤= 1，持续时间= 2000）=&gt; {
  让电流=开始
     _step =（结束-开始）* step &lt;0？  -step：步骤，
    计时器= setInterval（（）=&gt; {
      当前+ = _step;
      document.querySelector（selector）.innerHTML =当前；
      if（当前&gt; =结束）document.querySelector（selector）.innerHTML =结束;
      如果（当前&gt; =结束）clearInterval（timer）;
    }，Math.abs（Math.floor（duration /（end-start）））））;
  返回计时器；
};
```

<details>
<summary>Examples</summary>

```js
counter('#my-id', 1, 1000, 5, 2000); // Creates a 2-second timer for the element with id="my-id"
```
</details>


### createElement

从字符串创建元素（不将其附加到文档中）. 
如果给定的字符串包含多个元素，则仅返回第一个.

使用`document.createElement（）`创建一个新元素.
将其“ innerHTML”设置为作为参数提供的字符串. 
使用“ ParentNode.firstElementChild”返回字符串的元素版本.

```js
const createElement = str =&gt; {
  const el = document.createElement（&#39;div&#39;）;
  el.innerHTML = str;
  返回el.firstElementChild;
};
```

<details>
<summary>Examples</summary>

```js
const el = createElement（
  `<div class="container">
    <p>你好！ </p>
  </div>`
);
 console.log（el.className）;  // &#39;容器&#39;
```
</details>



创建一个发布/订阅（[publish–subscribe](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern)）事件中心，使用`emit`，`on`和`off`方法.

使用Object.create（null）创建一个空的hub对象，该对象不继承Object.prototype的属性.
对于`emit`，请基于`event`参数解析处理程序数组，然后通过将数据作为参数传入来使用`Array.prototype.forEach（）`运行每个处理程序.
对于on，为事件创建一个数组（如果尚不存在），然后使用Array.prototype.push（）添加处理程序.
到阵列.
对于“ off”，使用“ Array.prototype.findIndex（）”在事件数组中查找处理程序的索引，然后使用“ Array.prototype.splice（）”将其删除.

```js
const createEventHub =（）=&gt;（{
  集线器：Object.create（null），
  发出（事件，数据）{
    （this.hub [event] || []）.forEach（handler =&gt; handler（data））;
  },
  开（事件，处理程序）{
    如果（！this.hub [event]）this.hub [event] = [];
    this.hub [event] .push（handler）;
  },
  关闭（事件，处理程序）{
    const i =（this.hub [event] || []）.findIndex（h =&gt; h ===处理程序）;
    如果（i&gt; -1）this.hub [event] .splice（i，1）;
    如果（this.hub [event] .length === 0）删除this.hub [event];
  }
});
```

<details>
<summary>Examples</summary>

```js
const handler = data =&gt; console.log（data）;
const hub = createEventHub（）;
让增量= 0;

//订阅：监听不同类型的事件
hub.on（&#39;message&#39;，handler）;
hub.on（&#39;message&#39;，（）=&gt; console.log（&#39;Message event fired&#39;））;
hub.on（&#39;increment&#39;，（）=&gt;增量++）;

//发布：发出事件以调用所有订阅给它们的处理程序，并将数据作为参数传递给它们
 hub.emit（&#39;message&#39;，&#39;hello world&#39;）;  //记录“ hello world”和“已触发消息事件”
 hub.emit（&#39;message&#39;，{hello：&#39;world&#39;}）;  //记录对象并触发“消息事件”
 hub.emit（&#39;increment&#39;）;  //`increment`变量现在为1

//取消订阅：停止特定处理程序监听&#39;message&#39;事件
hub.off（&#39;message&#39;，handler）;
```
</details>


### currentURL

返回当前URL.

使用“ window.location.href”获取当前URL.

```js
const currentURL =（）=&gt; window.location.href;
```

<details>
<summary>Examples</summary>

```js
 currentURL（）;  //&#39;https://google.com&#39;
```
</details>


### detectDeviceType

检测网站是在移动设备中还是在台式机/笔记本电脑中打开.

使用正则表达式测试“ navigator.userAgent”属性，以确定该设备是移动设备还是台式机/笔记本电脑.

```js
const detectDeviceType =（）=&gt;
  / Android | webOS | iPhone | iPad | iPod | BlackBerry | IEMobile | Opera Mini / i.test（navigator.userAgent）
     ？  &#39;移动&#39;
    ： &#39;桌面&#39;;
```

<details>
<summary>Examples</summary>

```js
 detectDeviceType（）;  //“移动”或“台式机”
```
</details>


### elementContains

如果“ parent”元素包含“ child”元素，则返回“ true”，否则返回“ false”.

检查“ parent”和“ child”不是相同的元素，请使用“ parent.contains（child）”来检查“ parent”元素是否包含“ child”元素.

```js
const elementContains =（parent，child）=&gt; parent！== child &amp;&amp; parent.contains（child）;
```

<details>
<summary>Examples</summary>

```js
 elementContains（document.querySelector（&#39;head&#39;），document.querySelector（&#39;title&#39;））;  //正确
 elementContains（document.querySelector（&#39;body&#39;），document.querySelector（&#39;body&#39;））;  //错误
```
</details>



如果指定的元素在视口中可见，则返回“ true”，否则返回“ false”.

使用`Element.getBoundingClientRect（）`和`window.inner（Width | Height）`值
确定给定元素在视口中是否可见.
省略第二个参数以确定元素是否完全可见，或指定“ true”确定是否
它是部分可见的.

```js
const elementIsVisibleInViewport =（el，partialVisible = false）=&gt; {
  const {top，left，bottom，right} = el.getBoundingClientRect（）;
  const {innerHeight，innerWidth} =窗口；
  部分返回
     ？  （（（顶部&gt; 0 &amp;&amp;顶部&lt;innerHeight）||（底部&gt; 0 &amp;&amp;底部&lt;innerHeight））&amp;&amp;
        （（（左&gt; 0 &amp;&amp;左&lt;innerWidth）||（右&gt; 0 &amp;&amp;右&lt;innerWidth））
    ：顶部&gt; = 0 &amp;&amp;左侧&gt; = 0 &amp;&amp;底部&lt;= innerHeight &amp;&amp;右侧&lt;= innerWidth;
};
```

<details>
<summary>Examples</summary>

```js
//例如100x100视口和位置{top：-1，left：0，bottom：9，9，right：10}处的10x10px元素
 elementIsVisibleInViewport（el）;  // false-（不完全可见）
 elementIsVisibleInViewport（el，true）;  // true-（部分可见）
```
</details>


### formToObject

将一组表单元素编码为一个“对象”.

使用FormData构造函数将HTML form转换为FormData，将Array.from（）转换为数组.
使用“ Array.prototype.reduce（）”从数组中收集对象.

```js
const formToObject =形式=&gt;
  Array.from（new FormData（form））.reduce（
    （acc，[键，值]）=&gt;（{
      ... acc，
      [核心价值
    }),
    {}
  );
```

<details>
<summary>Examples</summary>

```js
formToObject(document.querySelector('#form')); // { email: 'test@email.com', name: 'Test Name' }
```
</details>


### getImages

从一个元素中获取所有图像并将它们放入一个数组中

 使用`Element.prototype.getElementsByTagName（）`获取所有` <img>  提供的元素Array.prototype.map（）中的元素，以映射其各自的`src`属性的每个 <img>  元素，然后创建一个Set来消除重复项并返回数组.

```js
const getImages =（el，includeDuplicates = false）=&gt; {
  const images = [... el.getElementsByTagName（&#39;img&#39;）].map（img =&gt; img.getAttribute（&#39;src&#39;））;
   返回includeDuplicates吗？  图片：[...新集（图片）];
};
```

<details>
<summary>Examples</summary>

```js
 getImages（document，true）;  // [&#39;image1.jpg&#39;，&#39;image2.png&#39;，&#39;image1.png&#39;，&#39;...&#39;]
 getImages（document，false）;  // [&#39;image1.jpg&#39;，&#39;image2.png&#39;，&#39;...&#39;]
```
</details>


### getScrollPosition

返回当前页面的滚动位置.

如果定义了`pageXOffset`和`pageYOffset`，否则使用`scrollLeft`和`scrollTop`.
您可以省略“ el”以使用默认值“ window”.

```js
const getScrollPosition =（el = window）=&gt;（{
   x：el.pageXOffset！==未定义？  el.pageXOffset：el.scrollLeft，
   y：el.pageYOffset！==未定义？  el.pageYOffset：el.scrollTop
});
```

<details>
<summary>Examples</summary>

```js
 getScrollPosition（）;  // {x：0，y：200}
```
</details>


### getStyle

返回指定元素的CSS规则的值.

使用“ Window.getComputedStyle（）”来获取指定元素的CSS规则的值.

```js
const getStyle =（el，ruleName）=&gt; getComputedStyle（el）[ruleName];
```

<details>
<summary>Examples</summary>

```js
 getStyle（document.querySelector（&#39;p&#39;），&#39;font-size&#39;）;  //&#39;16px&#39;
```
</details>


### hasClass

如果元素具有指定的类，则返回“ true”，否则返回“ false”.

使用`element.classList.contains（）`检查元素是否具有指定的类.

```js
const hasClass =（el，className）=&gt; el.classList.contains（className）;
```

<details>
<summary>Examples</summary>

```js
 hasClass（document.querySelector（&#39;p.special&#39;），&#39;special&#39;）;  //正确
```
</details>



使用创建一个哈希值 [SHA-256](https://en.wikipedia.org/wiki/SHA-2)  算法.  返回承诺.

使用 [SubtleCrypto](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto) 用于为给定值创建哈希的API.

```js
const hashBrowser = val =&gt;
  crypto.subtle.digest（&#39;SHA-256&#39;，新的TextEncoder（&#39;utf-8&#39;）.encode（val））.then（h =&gt; {
    让十六进制= []，
      view =新的DataView（h）;
    对于（让i = 0; i &lt;view.byteLength; i + = 4）
      hexes.push（（&#39;&#39;00000000&#39;+ view.getUint32（i）.toString（16））.slice（-8））;
    返回hexes.join（&#39;&#39;）;
  });
```

<details>
<summary>Examples</summary>

```js
 hashBrowser（JSON.stringify（{a：&#39;a&#39;，b：[1,2,3,4]，foo：{c：&#39;bar&#39;}}）））.then（console.log）;  //&#39;04aa106279f5977f59f9067fa9712afc4aedc6f5862a8defc34552d8c7206393&#39;
```
</details>


### hide

隐藏所有指定的元素.

使用NodeList.prototype.forEach（）将display：none应用于指定的每个元素.

```js
const hide =（... el）=&gt; [... el] .forEach（e =&gt;（e.style.display =&#39;none&#39;）））;
```

<details>
<summary>Examples</summary>

```js
 hide（document.querySelectorAll（&#39;img&#39;））;  //隐藏所有 <img>  页面上的元素
```
</details>


### httpsRedirect

 如果页面当前位于HTTP中，则将其重定向到HTTPS.  此外，按返回按钮不会将其带回到HTTP页面，因为它已被替换为历史记录.

 使用`location.protocol`获取当前正在使用的协议.  如果不是HTTPS，请使用“ location.replace（）”将现有页面替换为该页面的HTTPS版本.  使用location.href获取完整的地址，使用String.prototype.split（）对其进行拆分，并删除URL的协议部分.

```js
const httpsRedirect =（）=&gt; {
  如果（location.protocol！==&#39;https：&#39;）location.replace（&#39;https：//&#39;+ location.href.split（&#39;//&#39;）[1]）;
};
```

<details>
<summary>Examples</summary>

```js
 httpsRedirect（）;  //如果您位于http://mydomain.com上，则会将您重定向到https://mydomain.com
```
</details>


### insertAfter

在指定元素的末尾插入HTML字符串.

使用位置为“ afterend”的“ el.insertAdjacentHTML（）”来解析“ htmlString”并将其插入到“ el”的末尾之后.

```js
const insertAfter =（el，htmlString）=&gt; el.insertAdjacentHTML（&#39;afterend&#39;，htmlString）;
```

<details>
<summary>Examples</summary>

```js
 insertAfter（document.getElementById（&#39;myId&#39;），&#39; <p>  后 </p>  &#39;）;  // <div id="myId">  ... </div><p>  后 </p>
```
</details>


### insertBefore

在指定元素的开头之前插入HTML字符串.

使用位置为“ beforebegin”的“ el.insertAdjacentHTML（）”来解析“ htmlString”并将其插入到“ el”开始之前.

```js
const insertBefore =（el，htmlString）=&gt; el.insertAdjacentHTML（&#39;beforebegin&#39;，htmlString）;
```

<details>
<summary>Examples</summary>

```js
 insertBefore（document.getElementById（&#39;myId&#39;），&#39; <p>  之前 </p>  &#39;）;  // <p>  之前 </p><div id="myId">  ... </div>
```
</details>


### isBrowserTabFocused

如果页面的浏览器标签集中，则返回“ true”，否则返回“ false”.

使用由页面可见性API引入的“ Document.hidden”属性来检查页面的浏览器标签是否可见或隐藏.

```js
const isBrowserTabFocused =（）=&gt;！document.hidden;
```

<details>
<summary>Examples</summary>

```js
 isBrowserTabFocused（）;  //正确
```
</details>


### nodeListToArray

将NodeList转换为数组.

在新数组中使用传播运算符将NodeList转换为数组.

```js
const nodeListToArray = nodeList =&gt; [... nodeList];
```

<details>
<summary>Examples</summary>

```js
 nodeListToArray（document.childNodes）;  // [ <!DOCTYPE html>  ，html]
```
</details>



返回一个新的MutationObserver，并为指定元素上的每个突变运行提供的回调.

用一个 [`MutationObserver`](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver) 观察给定元素的突变.
使用Array.prototype.forEach（）运行每个观察到的突变的回调.
省略第三个参数“ options”以使用默认值 [options](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver#MutationObserverInit) （全部为“ true”）.

```js
const watchMutations =（元素，回调，选项）=&gt; {
  常量观察者=新的MutationObserver（突变=&gt; mutations.forEach（m =&gt;回调（m）））;
  观察者观察
    元件，
    Object.assign（
      {
        childList：是的，
        属性：true，
        attributeOldValue：true，
        characterData：true，
        characterDataOldValue：true，
        子树：true
      },
      选项
    )
  );
  返回观察员；
};
```

<details>
<summary>Examples</summary>

```js
 const obs = observeMutations（document，console.log）;  //记录页面上发生的所有变异
 obs.disconnect（）;  //断开观察者的连接并停止记录页面上的突变
```
</details>


### off

从元素中删除事件侦听器.

使用EventTarget.removeEventListener（）从元素中删除事件监听器. 
忽略第四个参数“ opts”以使用“ false”或根据添加事件侦听器时使用的选项进行指定.

```js
const off =（el，evt，fn，opts = false）=&gt; el.removeEventListener（evt，fn，opts）;
```

<details>
<summary>Examples</summary>

```js
const fn =（）=&gt; console.log（&#39;！&#39;）;
document.body.addEventListener（&#39;click&#39;，fn）;
off(document.body, 'click', fn); // no longer logs '!' upon clicking on the page
```
</details>


### on

将事件侦听器添加到具有使用事件委托功能的元素.

 使用EventTarget.addEventListener（）将事件侦听器添加到元素.  如果选项对象提供了“ target”属性，请确保事件目标与指定的目标匹配，然后通过提供正确的“ this”上下文来调用回调.
返回对自定义委托函数的引用，以便可以与 [`off`](#off).
省略“ opts”默认为非授权行为和事件冒泡.

```js
const on =（el，evt，fn，opts = {}）=&gt; {
  const delegatorFn = e =&gt; e.target.matches（opts.target）&amp;&amp; fn.call（e.target，e）;
  el.addEventListener（可能是opts.target？delegatorFn：fn，opts.options || false）；
  if（opts.target）返回委托人Fn;
};
```

<details>
<summary>Examples</summary>

```js
const fn =（）=&gt; console.log（&#39;！&#39;）;
 on（document.body，&#39;click&#39;，fn）;  //记录&#39;！&#39;  在点击身体时
 on（document.body，&#39;click&#39;，fn，{target：&#39;p&#39;}）;  //记录&#39;！&#39;  在点击身体的`p`元素子元素时
 on（document.body，&#39;click&#39;，fn，{options：true}）;  //使用捕获而不是冒泡
```
</details>



 每当用户输入类型更改（“ mouse”或“ touch”）时，运行回调.  根据输入设备来启用/禁用代码很有用.  此过程是动态的，并且适用于混合设备（例如触摸屏笔记本电脑）.

 使用两个事件侦听器.  首先假设“鼠标”输入，然后将“ touchstart”事件监听器绑定到文档. 
在`touchstart`上，添加一个`mousemove`事件侦听器，以使用`performance.now（）`侦听在20ms内触发的两个连续的`mousemove`事件.
在这两种情况下，都将输入类型作为参数运行回调.

```js
const onUserInputChange =回调=&gt; {
  让type =&#39;mouse&#39;，
    lastTime = 0;
  const mousemoveHandler =（）=&gt; {
    const now = performance.now（）;
    如果（现在-lastTime &lt;20）
      （type =&#39;mouse&#39;），callback（type），document.removeEventListener（&#39;mousemove&#39;，mousemoveHandler）;
    lastTime =现在；
  };
  document.addEventListener（&#39;touchstart&#39;，（）=&gt; {
    如果（类型===&#39;触摸&#39;）返回;
    （type =&#39;touch&#39;），callback（type），document.addEventListener（&#39;mousemove&#39;，mousemoveHandler）;
  });
};
```

<details>
<summary>Examples</summary>

```js
onUserInputChange（type =&gt; {
  console.log（“用户正在使用”，键入“作为输入方法.”）;
});
```
</details>


### prefix

返回浏览器支持的CSS属性的前缀版本（如有必要）.

在供应商前缀字符串数组上使用Array.prototype.findIndex（）来测试document.body是否在CSSStyleDeclaration对象中定义了其中之一，否则返回null.
使用`String.prototype.charAt（）`和`String.prototype.toUpperCase（）`将属性大写，该属性将追加到供应商前缀字符串中.

```js
const prefix = prop =&gt; {
  const capitalizedProp = prop.charAt（0）.toUpperCase（）+ prop.slice（1）;
  const prefixs = [&#39;&#39;，&#39;webkit&#39;，&#39;moz&#39;，&#39;ms&#39;，&#39;o&#39;];
  const i = prefixes.findIndex（
     前缀=&gt; typeof document.body.style [前缀？  前缀+ capitalizedProp：prop]！==&#39;未定义&#39;
  );
   返回i！== -1？  （i === 0？prop：前缀[i] + capitalizedProp）：null；
};
```

<details>
<summary>Examples</summary>

```js
 prefix（&#39;appearance&#39;）;  //在支持的浏览器上为“外观”，否则为“ webkitAppearance”，“ mozAppearance”，“ msAppearance”或“ oAppearance”
```
</details>


### recordAnimationFrames

在每个动画帧上调用提供的回调.

使用递归. 
假设“运行”为“真”，请继续调用“ window.requestAnimationFrame（）”，后者将调用提供的回调. 
返回带有“ start”和“ stop”两种方法的对象，以允许手动控制记录. 
省略第二个参数“ autoStart”，以在调用函数时隐式调用“ start”.

```js
const recordAnimationFrames =（回调，autoStart = true）=&gt; {
  让运行= true，
    货架;
  const stop =（）=&gt; {
    运行=假;
    cancelAnimationFrame（raf）;
  };
  const start =（）=&gt; {
    running = true;
    跑（）;
  };
  const run =（）=&gt; {
    raf = requestAnimationFrame（（）=&gt; {
      打回来（）;
      如果（正在运行）run（）;
    });
  };
  如果（autoStart）start（）;
  返回{开始，停止};
};
```

<details>
<summary>Examples</summary>

```js
const cb =（）=&gt; console.log（&#39;动画帧被触发&#39;）;
 常量记录器= recordAnimationFrames（cb）;  //在每个动画帧上记录“已触发动画帧”
 records.stop（）;  //停止记录
 records.start（）;  //重新开始
 const records2 = recordAnimationFrames（cb，false）;  //需要明确调用“ start”以开始录制帧
```
</details>


### redirect

重定向到指定的URL.

使用`window.location.href`或`window.location.replace（）`重定向到`url`.
传递第二个参数来模拟链接单击（默认为“ true”）或HTTP重定向（“ false”）.

```js
const redirect =（url，asLink = true）=&gt;
   asLink？  （window.location.href = url）：window.location.replace（url）;
```

<details>
<summary>Examples</summary>

```js
redirect('https://google.com');
```
</details>



使用以下命令在单独的线程中运行函数 [Web Worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)，允许长时间运行的功能不会阻塞UI.

使用Blob对象URL创建一个新的Worker，其内容应为所提供函数的字符串化版本.
立即发布回调该函数的返回值.
返回承诺，侦听onmessage和onerror事件，并解决从工作人员回传的数据，或者引发错误.

```js
const runAsync = fn =&gt; {
  const worker = new Worker（
    URL.createObjectURL（new Blob（[`Message（（$ {fn}）（））;`]），{
       类型：“ application / javascript;  charset = utf-8&#39;
    })
  );
  返回新的Promise（（res，rej）=&gt; {
    worker.onmessage =（{数据}）=&gt; {
      res（data），worker.terminate（）;
    };
    worker.onerror =错误=&gt; {
      rej（err），worker.terminate（）;
    };
  });
};
```

<details>
<summary>Examples</summary>

```js
const longRunningFunction =（）=&gt; {
  令result = 0;
  对于（让i = 0; i &lt;1000; i ++）
    for（let j = 0; j &lt;700; j ++）for（let k = 0; k &lt;300; k ++）结果=结果+ i + j + k;

  返回结果；
};
/*
  注意：由于该函数在不同的上下文中运行，因此不支持闭包.
  提供给`runAsync`的函数被字符串化，因此一切都变成了文字.
  所有变量和函数必须在内部定义.
*/
 runAsync（longRunningFunction）.then（console.log）;  // 209685000000
 runAsync（（）=&gt; 10 ** 3）.然后（console.log）;  // 1000
让outsideVariable = 50;
 runAsync（（）=&gt; typeof outsideVariable）.然后（console.log）;  //&#39;未定义&#39;
```
</details>


### scrollToTop

平滑滚动到页面顶部.

使用`document.documentElement.scrollTop`或`document.body.scrollTop`获取与顶部的距离.
 滚动到顶部的距离的一小部分.  使用“ window.requestAnimationFrame（）”来动画化滚动.

```js
const scrollToTop =（）=&gt; {
   const c = document.documentElement.scrollTop ||  document.body.scrollTop;
  如果（c&gt; 0）{
    window.requestAnimationFrame（scrollToTop）;
    window.scrollTo（0，c-c / 8）;
  }
};
```

<details>
<summary>Examples</summary>

```js
scrollToTop();
```
</details>


### serializeForm

将一组表单元素编码为查询字符串.

使用FormData构造函数将HTML form转换为FormData，将Array.from（）转换为数组，并使用map函数作为第二个参数.
使用Array.prototype.map（）和window.encodeURIComponent（）编码每个字段的值.
将Array.prototype.join（）与适当的参数一起使用以产生适当的查询字符串.

```js
const serializeForm =形式=&gt;
  Array.from（new FormData（form），field =&gt; field.map（encodeURIComponent）.join（&#39;=&#39;））.join（&#39;＆&#39;）;
```

<details>
<summary>Examples</summary>

```js
serializeForm(document.querySelector('#form')); // email=test%40email.com&name=Test%20Name
```
</details>


### setStyle

设置指定元素的CSS规则的值.

使用`element.style`将指定元素的CSS规则的值设置为`val`.

```js
const setStyle = (el, ruleName, val) => (el.style[ruleName] = val);
```

<details>
<summary>Examples</summary>

```js
 setStyle（document.querySelector（&#39;p&#39;），&#39;font-size&#39;，&#39;20px&#39;）;  // 首先 <p>  页面上的元素的字体大小为20px
```
</details>


### show

显示所有指定的元素.

使用传播运算符（...）和Array.prototype.forEach（）清除指定的每个元素的display属性.

```js
const show =（... el）=&gt; [... el] .forEach（e =&gt;（e.style.display =&#39;&#39;）））;
```

<details>
<summary>Examples</summary>

```js
show(...document.querySelectorAll('img')); // Shows all <img> elements on the page
```
</details>


### smoothScroll

将调用该元素的元素平滑滚动到浏览器窗口的可见区域.

使用.scrollIntoView方法滚动元素. 
将`{behavior：&#39;smooth&#39;}`传递给`.scrollIntoView`，以便其平滑滚动.

```js
const smoothScroll =元素=&gt;
  document.querySelector（element）.scrollIntoView（{
    行为：“平稳”
  });
```

<details>
<summary>Examples</summary>

```js
smoothScroll('#fooBar'); // scrolls smoothly to the element with the id fooBar
 smoothScroll（&#39;.fooBar&#39;）;  //使用fooBar类平滑滚动到第一个元素
```
</details>


### toggleClass

切换元素的类.

使用`element.classList.toggle（）`切换元素的指定类.

```js
const toggleClass =（el，className）=&gt; el.classList.toggle（className）;
```

<details>
<summary>Examples</summary>

```js
 toggleClass（document.querySelector（&#39;p.special&#39;），&#39;special&#39;）;  //该段将不再具有“特殊”类
```
</details>


### triggerEvent

在给定元素上触发特定事件，可以选择传递自定义数据.

使用`new CustomEvent（）`根据指定的`eventType`和详细信息创建一个事件.
使用`el.dispatchEvent（）`在给定元素上触发新创建的事件.
如果您不想将自定义数据传递给触发的事件，请忽略第三个参数“ detail”.

```js
const triggerEvent =（el，eventType，detail）=&gt;
  el.dispatchEvent(new CustomEvent(eventType, { detail }));
```

<details>
<summary>Examples</summary>

```js
triggerEvent（document.getElementById（&#39;myId&#39;），&#39;click&#39;）;
triggerEvent（document.getElementById（&#39;myId&#39;），&#39;click&#39;，{用户名：&#39;bob&#39;}）;
```
</details>


### UUIDGeneratorBrowser

在浏览器中生成UUID.

使用`crypto` API生成符合以下要求的UUID： [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) 版本4.

```js
const UUIDGeneratorBrowser =（）=&gt;
  （[1e7] + -1e3 + -4e3 + -8e3 + -1e11）.replace（/ [018] / g，c =&gt;
    （c ^（crypto.getRandomValues（新Uint8Array（1））[0]和（15 &gt;&gt;（c / 4））））.toString（16）
  );
```

<details>
<summary>Examples</summary>

```js
 UUIDGeneratorBrowser（）;  //&#39;7982fcfe-5721-4632-bede-6000885be57d&#39;
```
</details>


---

## ⏱️ Date


### dayOfYear

从“日期”对象获取一年中的日期.

使用`new Date（）`和`Date.prototype.getFullYear（）`获取一年中的第一天作为`Date`对象，将其从提供的`date`中减去并除以每天的毫秒数即可得到结果.
使用`Math.floor（）`将产生的天数适当地四舍五入为整数.

```js
const dayOfYear =日期=&gt;
  Math.floor（（date-new Date（date.getFullYear（），0，0））/ 1000/60/60/24）;
```

<details>
<summary>Examples</summary>

```js
 dayOfYear（new Date（））;  // 272
```
</details>


### formatDuration

返回给定毫秒数的人类可读格式.

将“ ms”除以适当的值以获得“天”，“小时”，“分钟”，“秒”和“毫秒”的适当值.
将Object.entries（）与Array.prototype.filter（）结合使用，仅保留非零值.
使用Array.prototype.map（）为每个值创建字符串，并将其适当地复数.
使用`String.prototype.join（&#39;，&#39;）`将值组合成一个字符串.

```js
const formatDuration = ms =&gt; {
  如果（ms &lt;0）ms = -ms;
  const time = {
    天：Math.floor（ms / 86400000），
    小时：Math.floor（ms / 3600000）％24，
    分钟：Math.floor（ms / 60000）％60，
    秒：Math.floor（ms / 1000）％60，
    毫秒：Math.floor（ms）％1000
  };
  返回Object.entries（时间）
    .filter（val =&gt; val [1]！== 0）
    .map（（[[key，val]）=&gt;`$ {val} $ {key} $ {val！== 1？&#39;s&#39;：&#39;&#39;}`）
    .join（&#39;，&#39;）;
};
```

<details>
<summary>Examples</summary>

```js
 formatDuration（1001）;  //&#39;1秒1毫秒&#39;
 formatDuration（34325055574）;  //&#39;397天，6小时，44分钟，15秒，574毫秒&#39;
```
</details>


### getColonTimeFromDate

从“日期”对象返回格式为“ HH：MM：SS”的字符串.

使用`Date.prototype.toTimeString（）`和`String.prototype.slice（）`获取给定`Date`对象的`HH：MM：SS`部分.

```js
const getColonTimeFromDate = date =&gt; date.toTimeString（）.slice（0，8）;
```

<details>
<summary>Examples</summary>

```js
 getColonTimeFromDate（new Date（））;  //“ 08:38:00”
```
</details>


### getDaysDiffBetweenDates

返回两个日期之间的差（以天为单位）.

计算两个“日期”对象之间的差异（以天为单位）.

```js
const getDaysDiffBetweenDates =（dateInitial，dateFinal）=&gt;
  （dateFinal-dateInitial）/（1000 * 3600 * 24）;
```

<details>
<summary>Examples</summary>

```js
 getDaysDiffBetweenDates（新日期（&#39;2017-12-13&#39;），新日期（&#39;2017-12-22&#39;））;  // 9
```
</details>


### getMeridiemSuffixOfInteger

将整数转换为带后缀的字符串，并根据其值添加“ am”或“ pm”.

使用模运算符（`％`）和条件检查将整数转换为带有后缀meridiem的字符串化12小时格式.

```js
const getMeridiemSuffixOfInteger = num =&gt;
   是否=== 0 ||  ===是否24
     ？  12 +&#39;am&#39;
    ：num === 12
       ？  12 +&#39;pm&#39;
      ：num &lt;12
         ？  （num％12）+&#39;am&#39;
        ：（无论12％）PM“;
```

<details>
<summary>Examples</summary>

```js
 getMeridiemSuffixOfInteger（0）;  //“ 12am”
 getMeridiemSuffixOfInteger（11）;  // “上午11点”
 getMeridiemSuffixOfInteger（13）;  //“ 1pm”
 getMeridiemSuffixOfInteger（25）;  //“ 1pm”
```
</details>


### isAfterDate

检查日期是否在另一个日期之后.

使用大于运算符（`&gt;`）检查第一个日期是否在第二个日期之后.

```js
const isAfterDate =（dateA，dateB）=&gt; dateA&gt; dateB;
```

<details>
<summary>Examples</summary>

```js
 isAfterDate（新日期（2010，10，21），新日期（2010，10，20））;  //正确
```
</details>


### isBeforeDate

检查某个日期是否早于另一个日期.

使用小于运算符（`&lt;`）检查第一个日期是否早于第二个日期.

```js
const isBeforeDate =（dateA，dateB）=&gt; dateA &lt;dateB;
```

<details>
<summary>Examples</summary>

```js
 isBeforeDate（新日期（2010，10，20），新日期（2010，10，21））;  //正确
```
</details>


### isSameDate

检查一个日期是否与另一个日期相同.

使用`Date.prototype.toISOString（）`和严格相等性检查（`===`）检查第一个日期是否与第二个相同.

```js
const isSameDate =（dateA，dateB）=&gt; dateA.toISOString（）=== dateB.toISOString（）;
```

<details>
<summary>Examples</summary>

```js
 isSameDate（新日期（2010，10，20），新日期（2010，10，20））;  //正确
```
</details>


### isWeekday

结果为特定日期的布尔表示形式.

首先传递特定的日期对象.
使用`Date.getDay（）`通过使用模运算符然后返回一个布尔值来检查工作日.

```js
const isWeekday =（t = new Date（））=&gt; {
  返回t.getDay（）％6！== 0;
};
```

<details>
<summary>Examples</summary>

```js
 isWeekday（）;  // true（如果当前日期是2019-07-19）
```
</details>


### isWeekend

结果为特定日期的布尔表示形式.

首先传递特定的日期对象.
使用`Date.getDay（）`根据使用模运算返回0-6的日期来检查周末，然后返回一个布尔值.

```js
const isWeekend =（t = new Date（））=&gt; {
  返回t.getDay（）％6 === 0;
};
```

<details>
<summary>Examples</summary>

```js
 isWeekend（）;  // 2018-10-19（如果当前日期为2018-10-18）
```
</details>


### maxDate

返回给定日期的最大值.

将ES6扩展语法与“ Math.max”一起使用以查找最大日期值，“ new Date（）”将其转换为“ Date”对象.

```js
const maxDate = date =&gt; new Date（Math.max（... dates））;
```

<details>
<summary>Examples</summary>

```js
const array = [
  新日期（2017，4，13），
  新日期（2018，2，12），
  新日期（2016，0，10），
  新日期（2016，0，9）
];
 maxDate（array）;  // 2018-03-11T22：00：00.000Z
```
</details>


### minDate

返回给定日期的最小值.

使用ES6扩展语法查找最小日期值，`new Date（）`将其转换为`Date`对象.

```js
const minDate = date =&gt; new Date（Math.min（... dates））;
```

<details>
<summary>Examples</summary>

```js
const array = [
  新日期（2017，4，13），
  新日期（2018，2，12），
  新日期（2016，0，10），
  新日期（2016，0，9）
];
 minDate（array）;  // 2016-01-08T22：00：00.000Z
```
</details>


### tomorrow

结果以字符串形式表示明天的日期.

使用`new Date（）`获取当前日期，使用`Date.getDate（）`递增1，并使用`Date.setDate（）`将值设置为结果. 
使用`Date.prototype.toISOString（）`返回`yyyy-mm-dd`格式的字符串.

```js
明天的const =（）=&gt; {
  令t = new Date（）;
  t.setDate（t.getDate（）+ 1）;
  返回t.toISOString（）.split（&#39;T&#39;）[0];
};
```

<details>
<summary>Examples</summary>

```js
 明天（）;  // 2018-10-19（如果当前日期为2018-10-18）
```
</details>


### yesterday

结果以字符串形式表示昨天的日期.

使用`new Date（）`获取当前日期，使用`Date.getDate（）`减一，并使用`Date.setDate（）`将值设置为结果.
使用`Date.prototype.toISOString（）`返回`yyyy-mm-dd`格式的字符串.

```js
const昨天=（）=&gt; {
  令t = new Date（）;
  t.setDate（t.getDate（）-1）;
  返回t.toISOString（）.split（&#39;T&#39;）[0];
};
```

<details>
<summary>Examples</summary>

```js
 昨天（）;  // 2018-10-17（如果当前日期为2018-10-18）
```
</details>


---

## 🎛️ Function


### attempt

尝试使用提供的参数调用函数，返回结果或捕获的错误对象.

使用`try ... catch`块返回函数结果或适当的错误.

```js
const try =（fn，... args）=&gt; {
  尝试{
    返回fn（... args）;
  }抓住（e）{
     返回e instanceof错误？  e：新的错误（e）；
  }
};
```

<details>
<summary>Examples</summary>

```js
var elements = try（function（selector）{
  返回document.querySelectorAll（selector）;
}, '>_>');
 if（elements instanceof Error）个元素= [];  //元素= []
```
</details>


### bind

创建一个在给定上下文中调用“ fn”的函数，可以选择将任何其他提供的参数添加到参数的开头.

返回一个使用Function.prototype.apply（）的function将给定的context应用于fn.
使用Array.prototype.concat（）将任何其他提供的参数放在参数之前.

```js
const bind =（fn，context，... boundArgs）=&gt;（... args）=&gt; fn.apply（context，[... boundArgs，... args]）;
```

<details>
<summary>Examples</summary>

```js
函数greet（问候，标点符号）{
  返回问候语+&#39;&#39;+ this.user +标点符号；
}
const freddy = {用户：&#39;fred&#39;};
const freddyBound =绑定（greed，freddy）;
 console.log（freddyBound（&#39;hi&#39;，&#39;！&#39;））;  //“嗨，弗雷德！”
```
</details>


### bindKey

创建一个函数，该函数在对象的给定键处调用该方法，可以选择将任何其他提供的参数添加到参数的开头.

返回一个使用Function.prototype.apply（）将functioncontext [fn]绑定到context的function.
使用扩展运算符（`...`）在参数中附加任何其他提供的参数.

```js
const bindKey =（上下文，fn，... boundArgs）=&gt;（... args）=&gt;
  context [fn] .apply（context，[... boundArgs，... args]）;
```

<details>
<summary>Examples</summary>

```js
const freddy = {
  用户：“ fred”，
  问候：功能（问候，标点符号）{
    返回问候语+&#39;&#39;+ this.user +标点符号；
  }
};
const freddyBound = bindKey（freddy，&#39;greet&#39;）;
 console.log（freddyBound（&#39;hi&#39;，&#39;！&#39;））;  //“嗨，弗雷德！”
```
</details>


### chainAsync

链接异步函数.

遍历包含异步事件的函数数组，并在每个异步事件完成后调用“ next”.

```js
const chainAsync = fns =&gt; {
  令curr = 0;
  const last = fns [fns.length-1];
  const next =（）=&gt; {
    const fn = fns [curr ++];
     fn ===最后？  fn（）：fn（下一个）;
  };
  下一个（）;
};
```

<details>
<summary>Examples</summary>

```js
chainAsync([
  下一个=&gt; {
    console.log（&#39;0秒&#39;）;
    setTimeout（next，1000）;
  },
  下一个=&gt; {
    console.log（&#39;1秒&#39;）;
    setTimeout（next，1000）;
  },
  () => {
    console.log（&#39;2秒&#39;）;
  }
]);
```
</details>


### checkProp

给定一个“谓词”函数和一个“ prop”字符串，此咖喱函数将通过调用属性并将其传递给谓词来获取一个“对象”进行检查.

召唤obj上的prop，将其传递给提供的predicate函数并返回一个带掩码的布尔值.

```js
const checkProp =（谓词，prop）=&gt; obj =&gt; !! predicate（obj [prop]）;
```

<details>
<summary>Examples</summary>

```js
const lengthIs4 = checkProp（l =&gt; l === 4，&#39;length&#39;）;
 lengthIs4（[]）;  //错误
 lengthIs4（[1,2,3,4]）;  //正确
 lengthIs4（new Set（[1,2,3,4]））;  // false（设置使用Size，而不是length）

const session = {用户：{}};
const validUserSession = checkProps（u =&gt; u.active &amp;&amp;！u.disabled，&#39;user&#39;）;

 validUserSession（session）;  //错误

session.user.active = true;
 validUserSession（session）;  //正确

const noLength（l =&gt; l === undefined，&#39;length&#39;）;
 noLength（[]）;  //错误
 noLength（{}）;  //正确
 noLength（new Set（））;  //正确
```
</details>


### compose

执行从右到左的功能合成.

使用Array.prototype.reduce（）执行从右到左的函数合成.
 最后一个（最右边）函数可以接受一个或多个参数.  其余功能必须是一元的.

```js
const compose =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; f（g（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add5 = x =&gt; x + 5;
const乘法=（x，y）=&gt; x * y;
const multipleAndAdd5 = compose（
  add5，
  乘
);
 multipleAndAdd5（5，2）;  // 15
```
</details>


### composeRight

执行从左到右的功能合成.

使用Array.prototype.reduce（）执行从左到右的功能合成.
 第一个（最左侧）函数可以接受一个或多个参数.  其余功能必须是一元的.

```js
const composeRight =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; g（f（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add =（x，y）=&gt; x + y;
const square = x =&gt; x * x;
const addAndSquare = composeRight（add，square）;
 addAndSquare（1，2）;  // 9
```
</details>


### converge

接受收敛函数和分支函数列表，然后返回将每个分支函数应用于参数的函数，并将分支函数的结果作为参数传递给收敛函数.

使用Array.prototype.map（）和Function.prototype.apply（）将每个函数应用于给定参数.
使用价差运算符（...）调用带有所有其他函数结果的`coverger`.

```js
const converge =（converger，fns）=&gt;（... args）=&gt; converger（... fns.map（fn =&gt; fn.apply（null，args））））;
```

<details>
<summary>Examples</summary>

```js
const average = converge（（（a，b）=&gt; a / b，[
  arr =&gt; arr.reduce（（a，v）=&gt; a + v，0），
  arr =&gt; arr.length
]);
 平均值（[1、2、3、4、5、6、7]）;  // 4
```
</details>


### curry

咖喱函数.

使用递归.
If the number of provided arguments (`args`) is sufficient, call the passed function `fn`.
否则，返回一个期望剩余参数的咖喱函数“ fn”.
如果要咖喱接受可变数量参数的函数（可变函数，例如`Math.min（）`），则可以选择将数量参数传递给第二个参数“ arity”.

```js
const curry =（fn，arity = fn.length，... args）=&gt;
   arity &lt;= args.length？  fn（... args）：curry.bind（null，fn，arity，... args）;
```

<details>
<summary>Examples</summary>

```js
 咖喱（Math.pow）（2）（10）;  // 1024
 咖喱（Math.min，3）（10）（50）（2）;  // 2
```
</details>


### debounce

创建一个防反跳函数，该函数将延迟调用提供的函数，直到自上次调用该函数起至少经过了ms毫秒.

 每次调用去抖动功能时，请使用clearTimeout（）清除当前的挂起超时，并使用setTimeout（）创建新的超时，该超时将延迟调用该函数，直到至少经过ms毫秒.  使用Function.prototype.apply（）将this上下文应用于函数并提供必要的参数.
省略第二个参数“ ms”，以将超时设置为默认值0 ms.

```js
const反跳=（fn，ms = 0）=&gt; {
  让timeoutId;
  返回函数（... args）{
    clearTimeout（timeoutId）;
    timeoutId = setTimeout（（）=&gt; fn.apply（this，args），ms）;
  };
};
```

<details>
<summary>Examples</summary>

```js
window.addEventListener(
  “调整大小”，
  debounce（（）=&gt; {
    console.log（window.innerWidth）;
    的console.log（window.innerHeight）;
  }, 250)
 ）;  //最多每250ms记录一次窗口尺寸
```
</details>


### defer

推迟调用函数，直到清除当前调用堆栈.

 使用`setTimeout（）`，超时时间为1ms，可将新事件添加到浏览器事件队列中，并允许渲染引擎完成其工作.  使用spread（`...`）运算符可以为函数提供任意数量的参数.

```js
const defer =（fn，... args）=&gt; setTimeout（fn，1，... args）;
```

<details>
<summary>Examples</summary>

```js
//示例A：
 defer（console.log，&#39;a&#39;），console.log（&#39;b&#39;）;  //先记录“ b”，再记录“ a”

//示例B：
document.querySelector('#someElement').innerHTML = 'Hello';
 longRunningFunction（）;  //在完成之前，浏览器不会更新HTML
 defer（longRunningFunction）;  //浏览器将更新HTML，然后运行该函数
```
</details>


### delay

在“ wait”毫秒后调用提供的功能.

使用setTimeout（）延迟执行fn.
使用spread（`...`）运算符可以为函数提供任意数量的参数.

```js
const delay =（fn，wait，... args）=&gt; setTimeout（fn，wait，... args）;复制代码
```

<details>
<summary>Examples</summary>

```js
delay(
  功能（文字）{
    console.log（text）;
  },
  1000,
  &#39;后来&#39;
 ）;  //一秒钟后记录“以后”.
```
</details>


### functionName

记录函数的名称.

使用`console.debug（）`和传递的方法的`name`属性将方法的名称记录到控制台的`debug`通道中.

```js
const functionName = fn =&gt;（console.debug（fn.name），fn）;
```

<details>
<summary>Examples</summary>

```js
 functionName（Math.max）;  //最大（登录到控制台的调试通道）
```
</details>


### hz

返回函数每秒执行一次的次数. 
“ hz”是“赫兹”的单位，频率单位是每秒一个周期.

使用performance.now（）获取迭代循环前后的毫秒数差，以计算执行迭代功能的时间. 
通过将毫秒转换为秒并除以经过的时间，返回每秒的循环数. 
省略第二个参数“迭代”，以使用默认的100次迭代.

```js
const hz =（fn，迭代= 100）=&gt; {
  const before = performance.now（）;
  for（让i = 0; i &lt;迭代; i ++）fn（）;
  return（1000 *迭代）/（performance.now（）-之前）;
};
```

<details>
<summary>Examples</summary>

```js
// 10,000个元素数组
const number = Array（10000）
  .填（）
  .map（（_，i）=&gt; i）;

//测试具有相同目标的函数：对数组中的元素求和
const sumReduce =（）=&gt;数字.reduce（（acc，n）=&gt; acc + n，0）;
const sumForLoop =（）=&gt; {
  令总和= 0;
  for（让i = 0; i &lt;numbers.length; i ++）sum + =数字[i];
  返回总和
};

//`sumForLoop`快将近10倍
 Math.round（hz（sumReduce））;  // 572
 Math.round（hz（sumForLoop））;  // 4784
```
</details>



返回已记忆（缓存）的函数.

通过实例化一个新的Map对象来创建一个空的缓存.
 通过首先检查该特定输入值的函数输出是否已被缓存，返回存储一个参数的函数，该参数将被提供给已记忆的函数；否则，将其存储并返回.  必须使用关键字function，以便在必要时允许记忆的功能对其this上下文进行更改.
通过将其设置为返回函数的属性来允许访问“缓存”.

```js
const memoize = fn =&gt; {
  const cache = new Map（）;
  const cached = function（val）{
     返回cache.has（val）吗？  cache.get（val）：cache.set（val，fn.call（this，val））&amp;&amp; cache.get（val）;
  };
  cached.cache = cache;
  返回缓存；
};
```

<details>
<summary>Examples</summary>

```js
//参见“ anagrams”代码段.
const anagramsCached = memoize（anagrams）;
 anagramsCached（&#39;javascript&#39;）;  // 需要很长的时间
 anagramsCached（&#39;javascript&#39;）;  //由于现在已缓存，因此几乎立即返回
 console.log（anagramsCached.cache）;  //缓存的字谜地图
```
</details>


### negate

否定谓词功能.

采取一个谓词函数，并将not运算符（`！`）应用于其参数.

```js
const negate = func =&gt;（... args）=&gt;！func（... args）;
```

<details>
<summary>Examples</summary>

```js
 [1、2、3、4、5、6] .filter（negate（n =&gt; n％2 === 0））;  // [1，3，5]
```
</details>


### once

确保一个函数仅被调用一次.

 利用闭包，使用一个名为“”的标志，并在第一次调用该函数时将其设置为“ true”，以防止再次调用该函数.  为了允许函数改变它的this上下文（例如在事件监听器中），必须使用function关键字，并且所提供的函数必须应用上下文.
允许使用rest / spread（`...`）运算符为函数提供任意数量的参数.

```js
const一旦= fn =&gt; {
  让称为=假;
  返回函数（... args）{
    如果（称为）返回；
    称为= true;
    返回fn.apply（this，args）;
  };
};
```

<details>
<summary>Examples</summary>

```js
const startApp = function（event）{
   console.log（this，event）;  // document.body，MouseEvent
};
 document.body.addEventListener（&#39;click&#39;，一次（startApp））;  //仅在点击后运行一次“ startApp”
```
</details>


### partial

创建一个函数，该函数使用在接收到的参数之前的`partials&#39;调用`fn`.

使用扩展运算符（`...`）将`partials`放在`fn`的参数列表之前.

```js
const partial =（fn，... partials）=&gt;（... args）=&gt; fn（... partials，... args）;
```

<details>
<summary>Examples</summary>

```js
const greet =（greeting，name）=&gt;问候+&#39;&#39;+名称+&#39;！&#39;;
const greetHello =局部（greet，&#39;Hello&#39;）;
 greetHello（&#39;John&#39;）;  // &#39;你好约翰！&#39;
```
</details>


### partialRight

创建一个函数，该函数调用fn并在接收到的参数后附加partials.

使用扩展运算符（`...）将`partials`附加到`fn`的参数列表中.

```js
const partialRight =（fn，... partials）=&gt;（... args）=&gt; fn（... args，... partials）;
```

<details>
<summary>Examples</summary>

```js
const greet =（greeting，name）=&gt;问候+&#39;&#39;+名称+&#39;！&#39;;
const greetJohn = partialRight（greet，&#39;John&#39;）;
 问候约翰（&#39;你好&#39;）;  // &#39;你好约翰！&#39;
```
</details>


### runPromisesInSeries

连续运行一系列诺言.

使用Array.prototype.reduce（）创建一个承诺链，其中每个承诺在解决后都会返回下一个承诺.

```js
const runPromisesInSeries = ps =&gt; ps.reduce（（p，next）=&gt; p.then（next），Promise.resolve（））;
```

<details>
<summary>Examples</summary>

```js
const delay = d =&gt; new Promise（r =&gt; setTimeout（r，d））;
 runPromisesInSeries（[[）=&gt; delay（1000），（）=&gt; delay（2000）]）;  //依次执行每个诺言，总共需要3秒钟才能完成
```
</details>


### sleep

延迟异步功能的执行.

通过使其进入睡眠状态并返回一个Promise来延迟执行async函数的一部分.

```js
const sleep = ms =&gt; new Promise（resolve =&gt; setTimeout（resolve，ms））;复制代码
```

<details>
<summary>Examples</summary>

```js
异步功能sleepyWork（）{
  console.log（“我要睡一秒钟.”）;
  等待睡眠（1000）;
  console.log（&#39;我在一秒钟后醒了.&#39;）;
}
```
</details>



创建一个受限制的函数，每“等待”毫秒最多只能调用一次提供的函数

使用setTimeout（）和clearTimeout（）限制给定的方法fn.
使用Function.prototype.apply（）将this上下文应用于函数并提供必要的参数.
使用`Date.now（）`来跟踪上一次调用受限制的函数的时间.
省略第二个参数“ wait”，将超时设置为默认值0 ms.

```js
const油门=（fn，等待）=&gt; {
  让inThrottle，lastFn，lastTime;
  return function（）{
    const context = this，
      args = arguments;
    如果（！inThrottle）{
      fn.apply（上下文，args）;
      lastTime = Date.now（）;
      inThrottle = true;
    }其他{
      clearTimeout（lastFn）;
      lastFn = setTimeout（function（）{
        如果（Date.now（）-lastTime&gt; =等待）{
          fn.apply（上下文，args）;
          lastTime = Date.now（）;
        }
      }，Math.max（wait-（Date.now（）-lastTime），0））;
    }
  };
};
```

<details>
<summary>Examples</summary>

```js
window.addEventListener(
  “调整大小”，
  节流阀（功能（evt）{
    console.log（window.innerWidth）;
    的console.log（window.innerHeight）;
  }, 250)
 ）;  //最多每250ms记录一次窗口尺寸
```
</details>


### times

遍历回调`n`次

使用Function.call（）来调用fn次或直到返回false为止.
省略最后一个参数“ context”，以使用“ undefined”对象（或非严格模式下的全局对象）.

```js
const times =（n，fn，context = undefined）=&gt; {
  让我= 0;
  while（fn.call（context，i）！== false &amp;&amp; ++ i &lt;n）{}
};
```

<details>
<summary>Examples</summary>

```js
var output =&#39;&#39;;
times（5，i =&gt;（输出+ = i））;
 console.log（输出）;  // 01234
```
</details>


### uncurry

取消直到n深度的函数.

返回可变参数函数.
在提供的参数上使用Array.prototype.reduce（）来调用函数的每个后续咖喱级别.
如果提供的参数的“长度”小于“ n”，则抛出错误.
否则，使用Array.prototype.slice（0，n）用适当数量的参数调用fn.
忽略第二个参数“ n”，以取消深度直至“ 1”.

```js
const uncurry =（fn，n = 1）=&gt;（... args）=&gt; {
  const next = acc =&gt; args =&gt; args.reduce（（x，y）=&gt; x（y），acc）;
  如果（n&gt; args.length）抛出新的RangeError（&#39;参数太少了！&#39;）;
  返回next（fn）（args.slice（0，n））;
};
```

<details>
<summary>Examples</summary>

```js
const add = x =&gt; y =&gt; z =&gt; x + y + z;
const uncurriedAdd = uncurry（add，3）;
 uncurriedAdd（1,2,3）;  // 6
```
</details>


### unfold

使用迭代器函数和初始种子值构建数组.

使用while循环和Array.prototype.push（）重复调用该函数，直到返回false为止.
迭代器函数接受一个参数（“ seed”），并且必须始终返回包含两个元素（[[value]，“ nextSeed”]）或“ false”的数组以终止.

```js
const unfold =（fn，seed）=&gt; {
  让结果= []，
    val = [null，seed];
  while（（val = fn（val [1]）））result.push（val [0]）;
  返回结果；
};
```

<details>
<summary>Examples</summary>

```js
var f = n =&gt;（n&gt; 50？false：[-n，n + 10]）;
 展开（f，10）;  // [-10，-20，-30，-40，-50]
```
</details>


### when

 针对谓词函数测试值“ x”.  如果为true，则返回fn（x）.  否则，返回`x`. 

返回一个期望值为x的函数，该函数基于pred返回合适的值.

```js
const when =（pred，whenTrue）=&gt; x =&gt;（pred（x）？whenTrue（x）：x）;复制代码
```

<details>
<summary>Examples</summary>

```js
const doubleEvenNumbers = when（x =&gt; x％2 === 0，x =&gt; x * 2）;
 doubleEvenNumbers（2）;  // 4
 doubleEvenNumbers（1）;  // 1
```
</details>


---

## ➗ Math


### approximatelyEqual

检查两个数字是否彼此近似相等.

使用`Math.abs（）`比较两个值的绝对差和`epsilon`.
省略第三个参数“ε”，以使用默认值“ 0.001”.

```js
const approximatelyEqual = (v1, v2, epsilon = 0.001) => Math.abs(v1 - v2) < epsilon;
```

<details>
<summary>Examples</summary>

```js
 大约等于（Math.PI / 2.0，1.5708）;  //正确
```
</details>


### average

返回两个或多个数字的平均值.

使用Array.prototype.reduce（）将每个值添加到累加器中，并以值0初始化，再除以数组的长度.

```js
const average =（... nums）=&gt; nums.reduce（（acc，val）=&gt; acc + val，0）/ nums.length;
```

<details>
<summary>Examples</summary>

```js
 平均值（... [1、2、3]）;  // 2
 平均（1,2,3）;  // 2
```
</details>


### averageBy

使用提供的函数将每个元素映射到一个值后，返回数组的平均值.

使用Array.prototype.map（）将每个元素映射到fn返回的值，Array.prototype.reduce（）将每个值添加到累加器中，并以值0初始化，除法通过数组的“长度”.

```js
const averageBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val）=&gt; acc + val，0）/
  长度
```

<details>
<summary>Examples</summary>

```js
 averageBy（[{n：4}，{n：2}，{n：8}，{n：6}]，o =&gt; on）;  // 5
 averageBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 5
```
</details>


### binomialCoefficient

计算两个整数“ n”和“ k”的二项式系数.

使用Number.isNaN（）检查两个值是否为NaN.
检查“ k”是否小于“ 0”，大于或等于“ n”，等于“ 1”或“ n-1”，并返回适当的结果.
检查“ n-k”是否小于“ k”，并相应地切换其值.
从2到k循环并计算二项式系数.
使用`Math.round（）`来解决计算中的舍入误差.

```js
const binomialCoefficient =（n，k）=&gt; {
  如果（Number.isNaN（n）|| Number.isNaN（k））返回NaN；
  如果（k &lt;0 || k&gt; n）返回0;
  如果（k === 0 || k === n）返回1；
  如果（k === 1 || k === n-1）返回n；
  如果（n-k &lt;k）k = n-k;
  令res = n;
  对于（let j = 2; j &lt;= k; j ++）res * =（n-j + 1）/ j;
  返回Math.round（res）;
};
```

<details>
<summary>Examples</summary>

```js
 二项式系数（8，2）;  // 28
```
</details>


### clampNumber

将num限制在边界值a和b指定的范围内.

如果num在此范围内，则返回num.
否则，返回范围内最接近的数字.

```js
const clampNumber =（num，a，b）=&gt; Math.max（Math.min（num，Math.max（a，b）），Math.min（a，b））;
```

<details>
<summary>Examples</summary>

```js
 clipNumber（2，3，5）;  // 3
 clipNumber（1，-1，-5）;  // -1
```
</details>


### degreesToRads

将角度从度转换为弧度.

使用Math.PI和度数到弧度公式将角度从度数转换为弧度.

```js
const degreeToRads = deg =&gt;（deg * Math.PI）/ 180.0;
```

<details>
<summary>Examples</summary>

```js
 DegreeToRads（90.0）;  //〜1.5708
```
</details>


### digitize

将数字转换为数字数组.

使用扩展运算符（`...`）将数字转换为字符串以构建数组.
使用Array.prototype.map（）和parseInt（）将每个值转换为整数.

```js
const digitize = n =&gt; [... $ {n}`] .map（i =&gt; parseInt（i））;
```

<details>
<summary>Examples</summary>

```js
 digitize（123）;  // [1、2、3]
```
</details>


### distance

返回两点之间的距离.

使用Math.hypot（）计算两点之间的欧几里得距离.

```js
const distance =（x0，y0，x1，y1）=&gt; Math.hypot（x1-x0，y1-y0）;
```

<details>
<summary>Examples</summary>

```js
 距离（1，1，2，3）;  // 2.23606797749979
```
</details>



使用来计算两个或多个对手之间的新评分 [Elo rating system](https://en.wikipedia.org/wiki/Elo_rating_system) .  它需要一个数组
的前评分，并返回包含后评分的数组.
阵列应从性能最佳到性能最差的顺序排列（优胜者-&gt;失败者）.

使用指数运算符“ **”和数学运算符来计算预期分数（获胜机会）.
并计算每个对手的新等级.
循环浏览等级，使用每个排列以成对方式计算每个玩家的Elo后等级. 
省略第二个参数以使用默认的kFactor值32.

```js
const elo =（[... ratings]，kFactor = 32，selfRating）=&gt; {
  const [a，b] =评分；
  const ExpectedScore =（自我，对手）=&gt; 1 /（1 + 10 **（（对手-自我）/ 400））;
  const newRating =（rating，i）=&gt;
    （selfRating ||评分）+ kFactor *（i-ExpectedScore（i？a：b，i？b：a））;
  如果（ratings.length === 2）返回[newRating（a，1），newRating（b，0）];

  for（让i = 0，len = ratings.length; i &lt;len; i ++）{
    令j = i;
    而（j &lt;len-1）{
      j ++;
      [ratings [i]，ratings [j]] = elo（[ratings [i]，ratings [j]]，kFactor）；
    }
  }
  返回评分；
};
```

<details>
<summary>Examples</summary>

```js
//标准1v1
 链接（[1200，1200]）;  // [1216，1184]
 链接（[1200，1200]，64）;  // [1232，1168]
// 4名球员FFA，所有级别相同
 elo（[1200，1200，1200，1200]）.map（Math.round）;  // [1246，1215，1185，1154]
/*
对于团队，每个评分都可以根据自己团队的平均评分与
对方球队的平均评分，并将得分加到对方
通过将其作为第三个参数来提供自己的个人评级.
*/
```
</details>


### factorial

计算数字的阶乘.

使用递归.
如果n小于或等于1，则返回1.
否则，返回“ n”和阶乘“ n-1”的乘积.
Throws an exception if `n` is a negative number.

```js
const factorial = n =&gt;
  n &lt;0
    ? (() => {
      抛出新的TypeError（&#39;不允许使用负数！&#39;）;
    })()
    ：n &lt;= 1
      ? 1
      ：n *阶乘（n-1）;
```

<details>
<summary>Examples</summary>

```js
 阶乘（6）;  // 720
```
</details>


### fibonacci

生成一个数组，其中包含斐波那契序列，直到第n个任期.

创建一个特定长度的空数组，初始化前两个值（“ 0”和“ 1”）.
使用“ Array.prototype.reduce（）”，使用前两个值（前两个值除外）之和将值添加到数组中.

```js
const fibonacci = n =&gt;
  Array.from（{length：n}）.reduce（
    （acc，val，i）=&gt; acc.concat（i&gt; 1？acc [i-1] + acc [i-2]：i），
    []
  );
```

<details>
<summary>Examples</summary>

```js
 fibonacci（6）;  // [0，1，1，2，3，5]
```
</details>


### gcd

计算两个或多个数字/数组之间的最大公约数.

内部的_gcd函数使用递归.
 基本情况是“ y”等于“ 0”.  在这种情况下，返回`x`.
否则，返回GCD的y和除法x / y的余数.

```js
const gcd =（... arr）=&gt; {
  const _gcd =（x，y）=&gt;（！y？x：gcd（y，x％y））;
  return [... arr] .reduce（（a，b）=&gt; _gcd（a，b））;
};
```

<details>
<summary>Examples</summary>

```js
 gcd（8，36）;  // 4
 gcd（... [12，8，32]）;  // 4
```
</details>


### geometricProgression

初始化一个数组，该数组包含指定范围内的数字，其中“ start”和“ end”包括端值，并且两项之间的比率为“ step”.
如果step等于1，则返回错误.

使用Array.from（），Math.log（）和Math.floor（）创建所需长度的数组，使用Array.prototype.map（）填充所需长度的数组.范围.
省略第二个参数“ start”以使用默认值“ 1”.
省略第三个参数“ step”以使用默认值“ 2”.

```js
const geometricProgression =（结束，开始= 1，步骤= 2）=&gt;
  Array.from（{长度：Math.floor（Math.log（end / start）/ Math.log（step））+ 1}）.map（
    （v，i）=&gt;开始*步骤** i
  );
```

<details>
<summary>Examples</summary>

```js
 geometricProgression（256）;  // [1、2、4、8、16、32、64、128、256]
 geometricProgression（256，3）;  // [3，6，12，24，48，96，192]
 geometricProgression（256，1，4）;  // [1、4、16、64、256]
```
</details>


### hammingDistance

计算两个值之间的汉明距离.

使用XOR运算符（`^`）查找两个数字之间的位差，然后使用`toString（2）`转换为二进制字符串.
使用match（/ 1 / g）计算并返回字符串中1的数目.

```js
const hammingDistance =（num1，num2）=&gt;（（（num1 ^ num2）.toString（2）.match（/ 1 / g）||&#39;&#39;）.length;
```

<details>
<summary>Examples</summary>

```js
 hammingDistance（2，3）;  // 1
```
</details>


### inRange

检查给定数字是否在给定范围内.

使用算术比较来检查给定数字是否在指定范围内.
如果未指定第二个参数“ end”，则范围被认为是从“ 0”到“ start”.

```js
const inRange =（n，start，end = null）=&gt; {
  if（结束&amp;&amp;开始&gt;结束）[结束，开始] = [开始，结束]；
   返回端== null？  n&gt; = 0 &amp;&amp; n &lt;开始：n&gt; =开始&amp;&amp; n &lt;结束；
};
```

<details>
<summary>Examples</summary>

```js
 inRange（3，2，5）;  //正确
 inRange（3，4）;  //正确
 inRange（2，3，5）;  //错误
 inRange（3，2）;  //错误
```
</details>


### isDivisible

检查第一个数字参数是否可被第二个参数整除.

使用取模运算符（％）检查余数是否等于0.

```js
const isDivisible =（股息，除数）=&gt;股息％除数=== 0;
```

<details>
<summary>Examples</summary>

```js
 isDivisible（6，3）;  //正确
```
</details>


### isEven

如果给定数字为偶数，则返回“ true”，否则为“ false”.

使用模（％）运算符检查数字是奇数还是偶数.
如果数字为偶数，则返回“ true”，如果数字为奇数，则返回“ false”.

```js
成本ISEVEN NUM =&gt; NUM 2％=== 0;
```

<details>
<summary>Examples</summary>

```js
 isEven（3）;  //错误
```
</details>


### isNegativeZero

检查给定值是否等于负零（“ -0”）.

检查传递的值是否等于“ 0”，以及“ 1”除以该值是否等于“ -Infinity”.

```js
const isNegativeZero = val =&gt; val === 0 &amp;&amp; 1 / val ===-无穷大;
```

<details>
<summary>Examples</summary>

```js
 isNegativeZero（-0）;  //正确
 isNegativeZero（0）;  //错误
```
</details>


### isOdd

如果给定数字为奇数，则返回“ true”，否则为“ false”.

使用模（％）运算符检查数字是奇数还是偶数.
如果数字为奇数，则返回“ true”，如果数字为偶数，则返回“ false”.

```js
成本ISODD NUM =&gt; NUM 2％=== 1;
```

<details>
<summary>Examples</summary>

```js
 屐（3）;  //真
```
</details>


### isPrime

检查提供的整数是否为质数.

检查从2到给定数字平方根的数字.
如果它们中的任何一个除以给定的数字，则返回“ false”，否则返回“ true”，除非该数字小于2.

```js
const isPrime = num =&gt; {
  const boundary = Math.floor（Math.sqrt（num））;
  for（var i = 2; i &lt;= boundary; i ++）如果（num％i === 0）返回false;
  返回是否&gt; = 2;
};
```

<details>
<summary>Examples</summary>

```js
 isPrime（11）;  //正确
```
</details>


### lcm

返回两个或多个数字的最小公倍数.

使用最大公因数（GCD）公式和lcm（x，y）= x * y / gcd（x，y）`的事实来确定最小公倍数.
GCD公式使用递归.

```js
LCM =常数（... ARR）=&gt; {
  const gcd =（x，y）=&gt;（！y？x：gcd（y，x％y））;
  const _lcm =（x，y）=&gt;（x * y）/ gcd（x，y）;
  return [... arr] .reduce（（a，b）=&gt; _lcm（a，b））;
};
```

<details>
<summary>Examples</summary>

```js
 厘米（12，7）;  // 84
 lcm（... [1、3、4、5]）;  // 60
```
</details>



实施 [Luhn Algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm) 用于验证各种标识号，例如信用卡号，IMEI号，国家提供商标识号等.

结合使用String.prototype.split（&#39;&#39;），Array.prototype.reverse（）和Array.prototype.map（）和parseInt（）来获得数字数组.
使用Array.prototype.splice（0,1）获得最后一位.
使用Array.prototype.reduce（）实现Luhn算法.
如果sum被10整除，则返回true，否则返回false.

```js
const luhnCheck = num =&gt; {
  让ARR =（NUM + &#39;&#39;）
    .分裂（&#39;&#39;）
    .相反（）
    .map（x =&gt; parseInt（x））;
  让lastDigit = arr.splice（0，1）[0];
  让sum = arr.reduce（（acc，val，i）=&gt;（i％2！== 0？acc + val：acc +（（val * 2）％9）|| 9），0）;
  sum + = lastDigit;
  返回总和％10 === 0;
};
```

<details>
<summary>Examples</summary>

```js
 luhnCheck（&#39;4485275742308327&#39;）;  //正确
 luhnCheck（6011329933655299）;  //错误
 luhnCheck（123456789）;  //错误
```
</details>


### mapNumRange

将数字从一个范围映射到另一范围.

从`inMin`-`inMax`返回映射在`outMin`-`outMax`之间的`num`.

```js
const mapNumRange =（num，inMin，inMax，outMin，outMax）=&gt;
  （（num-inMin）*（outMax-outMin））/（inMax-inMin）+ outMin;
```

<details>
<summary>Examples</summary>

```js
 mapNumRange（5，0，10，0，100）;  // 50
```
</details>


### maxBy

使用提供的函数将每个元素映射到一个值后，返回数组的最大值.

使用Array.prototype.map（）将每个元素映射到fn返回的值，Math.max（）获得最大值.

```js
const maxBy =（arr，fn）=&gt; Math.max（... arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]））;;
```

<details>
<summary>Examples</summary>

```js
 maxBy（[{{n：4}，{n：2}，{n：8}，{n：6}]，o =&gt; on）;  // 8
 maxBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 8
```
</details>


### median

返回数字数组的中位数.

找到数组的中间，使用Array.prototype.sort（）对值进行排序.
如果`length`为奇数，则返回中点的数字，否则返回两个中间数字的平均值.

```js
const中位数= arr =&gt; {
  const mid = Math.floor（arr.length / 2），
    nums = [... arr] .sort（（a，b）=&gt; a-b）;
   返回arr.length％2！== 0？  nums [mid]：（nums [mid-1] + nums [mid]）/ 2;
};
```

<details>
<summary>Examples</summary>

```js
 中位数（[5，6，50，1，-5]）;  // 5
```
</details>


### midpoint

计算两对（x，y）点之间的中点.

分解数组以获得x1，y1，x2和y2，通过将两个端点的总和除以2来计算每个维度的中点.

```js
const midpoint =（[[x1，y1]，[x2，y2]）=&gt; [（x1 + x2）/ 2，（y1 + y2）/ 2];
```

<details>
<summary>Examples</summary>

```js
 中点（[2，2]，[4，4]）;  // [3，3]
 中点（[4，4]，[6，6]）;  // [5，5]
 中点（[1，3]，[2，4]）;  // [1.5，3.5]
```
</details>


### minBy

使用提供的函数将每个元素映射到一个值后，返回数组的最小值.

使用Array.prototype.map（）将每个元素映射到fn返回的值，Math.min（）返回最小值.

```js
const minBy =（arr，fn）=&gt; Math.min（... arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]））;;
```

<details>
<summary>Examples</summary>

```js
 minBy（[{n：4}，{n：2}，{n：8}，{n：6}]，o =&gt; on）;  // 2
 minBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 2
```
</details>


### percentile

使用百分比公式来计算给定数组中有多少个数字小于或等于给定值.

使用Array.prototype.reduce（）来计算该值以下有多少个数字，以及相同值中有多少个数字，并应用百分位数公式.

```js
const percentile =（arr，val）=&gt;
  （100 * arr.reduce（（acc，v）=&gt; acc +（v &lt;val？1：0）+（v === val？0.5：0），0））/ arr.length;
```

<details>
<summary>Examples</summary>

```js
 percentile（[1、2、3、4、5、6、7、8、9、10]，6）;  // 55
```
</details>


### powerset

返回给定数字数组的幂集.

结合使用Array.prototype.reduce（）和Array.prototype.map（）来遍历元素并合并成包含所有组合的数组.

```js
const powerset = arr =&gt; arr.reduce（（a，v）=&gt; a.concat（a.map（r =&gt; [v] .concat（r））），[[]]）;
```

<details>
<summary>Examples</summary>

```js
 powerset（[1，2]）;  // [[]，[1]，[2]，[2、1]]
```
</details>


### primes

使用Eratosthenes筛子产生最多给定数的质数.

 从2到给定数字生成一个数组.  使用Array.prototype.filter（）过滤掉从2到所提供数字的平方根的任何数字可整除的值.

```js
const primes = num => {
  让arr = Array.from（{length：num-1}）.map（（x，i）=&gt; i + 2），
    sqroot = Math.floor（Math.sqrt（num）），
    numsTillSqroot = Array.from（{length：sqroot-1}）.map（（x，i）=&gt; i + 2）;
  numsTillSqroot.forEach（x =&gt;（arr = arr.filter（y =&gt; y％x！== 0 || y === x）））;
  返回arr;
};
```

<details>
<summary>Examples</summary>

```js
 保险费（10）;  // [2,3,5,7]
```
</details>


### radsToDegrees

将角度从弧度转换为度.

使用`Math.PI`和弧度到度的公式将弧度的角度转换为度.

```js
const radsToDegrees = rad =&gt;（rad * 180.0）/ Math.PI;
```

<details>
<summary>Examples</summary>

```js
 radsToDegrees（Math.PI / 2）;  // 90
```
</details>


### randomIntArrayInRange

返回指定范围内n个随机整数的数组.

使用Array.from（）创建一个特定长度的空数组，使用Math.random（）生成一个随机数并将其映射到所需范围，使用Math.floor（）使其成为一个整数.

```js
const randomIntArrayInRange =（最小值，最大值，n = 1）=&gt;
  Array.from（{length：n}，（）=&gt; Math.floor（Math.random（）*（max-min + 1））+ min）;
```

<details>
<summary>Examples</summary>

```js
 randomIntArrayInRange（12，35，10）;  // [34，14，27，17，30，27，20，26，21，14]
```
</details>


### randomIntegerInRange

返回指定范围内的随机整数.

使用`Math.random（）`生成一个随机数并将其映射到所需范围，使用`Math.floor（）`使其为整数.

```js
const randomIntegerInRange =（min，max）=&gt; Math.floor（Math.random（）*（max-min + 1））+ min;
```

<details>
<summary>Examples</summary>

```js
 randomIntegerInRange（0，5）;  // 2
```
</details>


### randomNumberInRange

返回指定范围内的随机数.

使用`Math.random（）`生成一个随机值，使用乘法将其映射到所需范围.

```js
const randomNumberInRange =（min，max）=&gt; Math.random（）*（max-min）+ min;
```

<details>
<summary>Examples</summary>

```js
 randomNumberInRange（2，10）;  // 6.0211363285087007005
```
</details>


### round

将数字四舍五入到指定的位数.

使用`Math.round（）`和模板文字将数字四舍五入到指定的数字位数.
省略第二个参数“ decimals”舍入为整数.

```js
const round =（n，小数= 0）=&gt; Number（`$ {Math.round（`$ {n} e $ {decimals}`）} e-$ {decimals}`）;
```

<details>
<summary>Examples</summary>

```js
 四舍五入（1.005，2）;  // 1.01
```
</details>


### sdbm

将输入字符串哈希为整数.

使用String.prototype.split（&#39;&#39;）和Array.prototype.reduce（）使用位移来创建输入字符串的哈希.

```js
const sdbm = str =&gt; {
  让arr = str.split（&#39;&#39;）;
  返回arr.reduce（
    （hashCode，currentVal）=&gt;
      （hashCode = currentVal.charCodeAt（0）+（hashCode &lt;&lt; 6）+（hashCode &lt;&lt; 16）-hashCode），
    0
  );
};
```

<details>
<summary>Examples</summary>

```js
 sdbm（&#39;name&#39;）;  // -3521204949
```
</details>


### standardDeviation

返回数字数组的标准偏差.

使用Array.prototype.reduce（）计算平均值，方差和值方差之和，值方差，然后
确定标准偏差.
您可以省略第二个参数以获取样本标准偏差，或者将其设置为“ true”以获取总体标准偏差.

```js
const standardDeviation =（arr，usePopulation = false）=&gt; {
  const mean = arr.reduce（（acc，val）=&gt; acc + val，0）/ arr.length;
  返回Math.sqrt（
    arr.reduce（（acc，val）=&gt; acc.concat（（val-mean）** 2），[]）.reduce（（acc，val）=&gt; acc + val，0）/
      （arr.length-（usePopulation？0：1））
  );
};
```

<details>
<summary>Examples</summary>

```js
 standardDeviation（[10，2，38，23，38，23，21]）;  // 13.284434142114991（示例）
 standardDeviation（[10，2，38，23，38，23，21]，true）;  // 12.29899614287479（人口）
```
</details>


### sum

返回两个或多个数字/数组的总和.

使用Array.prototype.reduce（）将每个值添加到累加器中，并以值0初始化.

```js
const sum =（... arr）=&gt; [... arr] .reduce（（acc，val）=&gt; acc + val，0）;
```

<details>
<summary>Examples</summary>

```js
 sum（1,2,3,4）;  // 10
 sum（... [1、2、3、4]）;  // 10
```
</details>


### sumBy

使用提供的函数将每个元素映射到一个值后，返回数组的总和.

使用Array.prototype.map（）将每个元素映射到fn返回的值，使用Array.prototype.reduce（）将每个值添加到累加器，并以值0初始化.

```js
const sumBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val）=&gt; acc + val，0）;
```

<details>
<summary>Examples</summary>

```js
sumBy（[{n：4}，{n：2}，{n：8}，{n：6}]，o =&gt; on）; // 20
 sumBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 20
```
</details>


### sumPower

返回从“开始”到“结束”（包括两端）的所有数字的幂的和.

使用Array.prototype.fill（）创建目标范围内所有数字的数组，使用Array.prototype.map（）和指数运算符（**）将其提高为幂，然后使用Array.prototype.reduce（）将它们添加在一起.
忽略第二个参数power，以使用默认的power 2.
忽略第三个参数“ start”以使用默认的起始值“ 1”.

```js
const sumPower =（结束，功率= 2，开始= 1）=&gt;
  数组（结束+1-开始）
    .fill（0）
    .map（（x，i）=&gt;（i +开始）**电源）
    .reduce（（a，b）=&gt; a + b，0）;
```

<details>
<summary>Examples</summary>

```js
 sumPower（10）;  // 385
 sumPower（10，3）;  // 3025
 sumPower（10，3，5）;  // 2925
```
</details>


### toSafeInteger

将值转换为安全整数.

使用`Math.max（）`和`Math.min（）`查找最接近的安全值.
使用`Math.round（）`转换为整数.

```js
const toSafeInteger = num =&gt;
  Math.round（Math.max（Math.min（num，Number.MAX.SA_INTEGER），Number.MIN_SAFE_INTEGER））;
```

<details>
<summary>Examples</summary>

```js
 toSafeInteger（&#39;3.2&#39;）;  // 3
 toSafeInteger（Infinity）;  // 9007199254740991
```
</details>


### vectorDistance

返回两个向量之间的距离.

使用Array.prototype.reduce（），Math.pow（）和Math.sqrt（）计算两个向量之间的欧几里得距离.

```js
const vectorDistance =（... coords）=&gt; {
  让pointLength = Math.trunc（coords.length / 2）;
  让总和=坐标
    .slice（0，pointLength）
    .reduce（（acc，val，i）=&gt; acc + Math.pow（val-coords [pointLength + i]，2），0）;
  返回Math.sqrt（sum）;
};
```

<details>
<summary>Examples</summary>

```js
 vectorDistance（10，0，5，20，0，10）;  // 11.180339887498949
```
</details>


---

## 📦 Node


### atob

解码已使用base-64编码编码的数据字符串.

使用base-64编码为给定的字符串创建一个“ Buffer”，并使用“ Buffer.toString（&#39;binary&#39;）”返回解码后的字符串.

```js
const atob = str =&gt; Buffer.from（str，&#39;base64&#39;）.toString（&#39;binary&#39;）;
```

<details>
<summary>Examples</summary>

```js
 细胞（ &#39;Zm9vYmFy&#39;）;  //&#39;foobar&#39;
```
</details>


### btoa

从String对象创建一个base-64编码的ASCII字符串，该字符串对象中的每个字符都被视为二进制数据的字节.

使用二进制编码为给定的字符串创建一个“ Buffer”，并使用“ Buffer.toString（&#39;base64&#39;）”返回编码后的字符串.

```js
const btoa = str =&gt; Buffer.from（str，&#39;binary&#39;）.toString（&#39;base64&#39;）;
```

<details>
<summary>Examples</summary>

```js
 btoa（&#39;foobar&#39;）;  //&#39;Zm9vYmFy&#39;
```
</details>


### colorize

在文本中添加特殊字符以在控制台中以彩色打印（与`console.log（）`组合）.

使用模板文字和特殊字符将适当的颜色代码添加到字符串输出中.
对于背景色，请在字符串的末尾添加一个特殊字符以重置背景色.

```js
const colorize =（... args）=&gt;（{
  黑色：`\ x1b [30m $ {args.join（&#39;&#39;）}`，
  红色：`\ x1b [31m $ {args.join（&#39;&#39;）}`，
  绿色：`\ x1b [32m $ {args.join（&#39;&#39;）}`，
  黄色：`\ x1b [33m $ {args.join（&#39;&#39;）}`，
  蓝色：`\ x1b [34m $ {args.join（&#39;&#39;）}`，
  洋红色：`\ x1b [35m $ {args.join（&#39;&#39;）}`，
  青色：`\ x1b [36m $ {args.join（&#39;&#39;）}`，
  白色：`\ x1b [37m $ {args.join（&#39;&#39;）}`，
  bgBlack：`\ x1b [40m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgRed：`\ x1b [41m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgGreen：`\ x1b [42m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgYellow：`\ x1b [43m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgBlue：`\ x1b [44m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgMagenta：`\ x1b [45m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgCyan：`\ x1b [46m $ {args.join（&#39;&#39;）} \ x1b [0m`，
  bgWhite：`\ x1b [47m $ {args.join（&#39;&#39;）} \ x1b [0m`
});
```

<details>
<summary>Examples</summary>

```js
 console.log（colorize（&#39;foo&#39;）.red）;  //&#39;foo&#39;（红色字母）
 console.log（colorize（&#39;foo&#39;，&#39;bar&#39;）.bgBlue）;  //&#39;foo bar&#39;（蓝色背景）
 console.log（colorize（colorize（&#39;foo&#39;）.yellow，colorize（&#39;foo&#39;）.green）.bgWhite）;  //&#39;foo bar&#39;（黄色字母的第一个单词，绿色字母的第二个单词，两者的白色背景）
```
</details>


### createDirIfNotExists

创建目录（如果不存在）.

使用“ fs.existsSync（）”检查目录是否存在，使用“ fs.mkdirSync（）”创建目录.

```js
const fs = require（&#39;fs&#39;）;
const createDirIfNotExists = dir =&gt;（！fs.existsSync（dir）？fs.mkdirSync（dir）：未定义）;
```

<details>
<summary>Examples</summary>

```js
 createDirIfNotExists（&#39;test&#39;）;  //创建目录“ test”（如果不存在）
```
</details>


### hasFlags

检查当前进程的参数是否包含指定的标志.

Use `Array.prototype.every()` and `Array.prototype.includes()` to check if `process.argv` contains all the specified flags.
使用正则表达式测试指定的标志是否以“-”或“-”为前缀，并相应地为它们添加前缀.

```js
const hasFlags =（...标志）=&gt;
  flags.every（flag =&gt; process.argv.includes（/ ^-{1,2} /.test（flag）？flag：&#39;-&#39;+ flag））;
```

<details>
<summary>Examples</summary>

```js
//节点myScript.js -s --test --cool = true
 hasFlags（&#39;-s&#39;）;  //正确
 hasFlags（&#39;-test&#39;，&#39;cool = true&#39;，&#39;-s&#39;）;  //正确
 hasFlags（&#39;special&#39;）;  //错误
```
</details>


### hashNode

使用创建一个哈希值 [SHA-256](https://en.wikipedia.org/wiki/SHA-2)  算法.  返回承诺.

使用“ crypto” API为给定值创建一个哈希值，使用“ setTimeout”防止长时间操作阻塞，并使用“ Promise”为其提供熟悉的界面.

```js
const crypto = require（&#39;crypto&#39;）;
const hashNode = val =&gt;
  new Promise(resolve =>
    setTimeout（
      () =>
        解决（
          加密货币
            .createHash（&#39;sha256&#39;）
            .update（val）
            .digest（&#39;hex&#39;）
        ),
      0
    )
  );
```

<details>
<summary>Examples</summary>

```js
 hashNode（JSON.stringify（{a：&#39;a&#39;，b：[1,2,3,4]，foo：{c：&#39;bar&#39;}}）））.then（console.log）;  //&#39;04aa106279f5977f59f9067fa9712afc4aedc6f5862a8defc34552d8c7206393&#39;
```
</details>


### isDuplexStream

检查给定的参数是否为双工（可读和可写）流.

检查该值是否与“ null”不同，使用“ typeof”检查一个值是否为“ object”类型，并且“ pipe”属性为“ function”类型.
另外检查一下typeof，_read，_write，_readState，_writableState的属性分别是function和object.

```js
const isDuplexStream = val =&gt;
  val！== null &amp;&amp;
  typeof val ===&#39;object&#39;&amp;&amp;
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._read ===&#39;函数&#39;&amp;&amp;
  typeof val._可读状态===&#39;对象&#39;&amp;&amp;
  typeof val._write ===&#39;函数&#39;&amp;&amp;
  val._writableState的typeof ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
const Stream = require（&#39;stream&#39;）;
 isDuplexStream（new Stream.Duplex（））;  //正确
```
</details>


### isReadableStream

检查给定参数是否为可读流.

检查该值是否与“ null”不同，请使用“ typeof”检查该值是否为“ object”类型，并且“ pipe”属性为“ function”类型.
此外，还要检查typeof，_read和_visibleState属性是否分别为function和object.

```js
const isReadableStream = val =&gt;
  val！== null &amp;&amp;
  typeof val ===&#39;object&#39;&amp;&amp;
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._read ===&#39;函数&#39;&amp;&amp;
  typeof val._可读状态===&#39;对象&#39;;
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isReadableStream（fs.createReadStream（&#39;test.txt&#39;））;  //正确
```
</details>


### isStream

检查给定参数是否为流.

检查该值是否与“ null”不同，请使用“ typeof”检查该值是否为“ object”类型，并且“ pipe”属性为“ function”类型.

```js
const isStream = val => val !== null && typeof val === 'object' && typeof val.pipe === 'function';
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isStream（fs.createReadStream（&#39;test.txt&#39;））;  //正确
```
</details>


### isTravisCI

检查当前环境是否 [Travis CI](https://travis-ci.org/).

检查当前环境是否具有`TRAVIS`和`CI`环境变量（[reference](https://docs.travis-ci.com/user/environment-variables/#Default-Environment-Variables)).

```js
const isTravisCI =（）=&gt; process.env中的&#39;TRAVIS&#39;&amp;&amp; process.env中的&#39;CI&#39;;
```

<details>
<summary>Examples</summary>

```js
 isTravisCI（）;  // true（如果代码在Travis CI上运行）
```
</details>


### isWritableStream

检查给定的参数是否为可写流.

检查该值是否与“ null”不同，请使用“ typeof”检查该值是否为“ object”类型，并且“ pipe”属性为“ function”类型.
此外，还要检查typeof，_write和_writableState属性分别是function函数和object对象.

```js
const isWritableStream = val =&gt;
  val！== null &amp;&amp;
  typeof val ===&#39;object&#39;&amp;&amp;
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._write ===&#39;函数&#39;&amp;&amp;
  val._writableState的typeof ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isWritableStream（fs.createWriteStream（&#39;test.txt&#39;））;  //正确
```
</details>


### JSONToFile

将JSON对象写入文件.

使用fs.writeFile（），模板文字和JSON.stringify（）将json对象写入.json文件.

```js
const fs = require（&#39;fs&#39;）;
const JSONToFile =（obj，文件名）=&gt;
  fs.writeFile（`$ {filename} .json`，JSON.stringify（obj，null，2））;
```

<details>
<summary>Examples</summary>

```js
 JSONToFile（{test：&#39;passed&#39;}，&#39;testJsonFile&#39;）;  //将对象写入“ testJsonFile.json”
```
</details>


### readFileLines

返回指定文件中的行数组.

在`fs`节点包中使用`readFileSync`函数从文件创建`Buffer&#39;.
使用toString（encoding）函数将缓冲区转换为字符串.
通过逐行拆分文件内容（每个\ n）从文件内容创建数组.

```js
const fs = require（&#39;fs&#39;）;
const readFileLines =文件名=&gt;
  fs
    .readFileSync（文件名）
    .toString（&#39;UTF8&#39;）
    .split（ &#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
/*
test.txt的内容：
  1号线
  2号线
  3号线
  ___________________________
*/
让arr = readFileLines（&#39;test.txt&#39;）;
 console.log（arr）;  // [&#39;line1&#39;，&#39;line2&#39;，&#39;line3&#39;]
```
</details>


### untildify

将波浪号路径转换为绝对路径.

使用带有正则表达式的String.prototype.replace（）和OS.homedir（）来替换主目录路径中的〜.

```js
const untildify = str =&gt; str.replace（/ ^〜（$ | \ / | \\）/，`$ {require（&#39;os&#39;）.homedir（）} $ 1`）;
```

<details>
<summary>Examples</summary>

```js
 直到dify（&#39;〜/ node&#39;）;  //&#39;/ Users / aUser / node&#39;
```
</details>


### UUIDGeneratorNode

在Node.JS中生成一个UUID.

使用`crypto` API生成符合以下要求的UUID： [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) 版本4.

```js
const crypto = require（&#39;crypto&#39;）;
const UUIDGeneratorNode =（）=&gt;
  （[1e7] + -1e3 + -4e3 + -8e3 + -1e11）.replace（/ [018] / g，c =&gt;
    （c ^（crypto.randomBytes（1）[0]和（15 &gt;&gt;（c / 4））））.toString（16）
  );
```

<details>
<summary>Examples</summary>

```js
 UUIDGeneratorNode（）;  //&#39;79c7c136-60ee-40a2-beb2-856f1feabefc&#39;
```
</details>


---

## 🗃️ Object


### bindAll

将对象的方法绑定到对象本身，从而覆盖现有方法.

使用Array.prototype.forEach（）返回一个函数，该函数使用Function.prototype.apply（）将给定的上下文（obj）应用于每个指定的函数fn.

```js
const bindAll =（obj，... fns）=&gt;
  fns.forEach（
    fn =&gt;（
      （f = obj [fn]），
      （obj [fn] = function（）{
        返回f.apply（obj）;
      })
    )
  );
```

<details>
<summary>Examples</summary>

```js
var view = {
  标签：“ docs”，
  点击：function（）{
    console.log（&#39;clicked&#39;+ this.label）;
  }
};
bindAll（view，&#39;click&#39;）;
 jQuery（element）.on（&#39;click&#39;，view.click）;  //单击时记录“单击的文档”.
```
</details>


### deepClone

创建对象的深层克隆.

使用递归.
检查传递的对象是否为null，如果是，则返回null.
使用Object.assign（）和空对象（{}）创建原始对象的浅表副本.
使用Object.keys（）和Array.prototype.forEach（）确定哪些键值对需要深度克隆.

```js
const deepClone = obj =&gt; {
  如果（obj === null）返回null;
  让clone = Object.assign（{}，obj）;
  Object.keys（clone）.forEach（
    键=&gt;（clone [键] =类型obj [键] ===&#39;对象&#39;？deepClone（obj [键]）：obj [键]）
  );
  return Array.isArray(obj) && obj.length
     ？  （clone.length = obj.length）&amp;&amp; Array.from（clone）
    ：Array.isArray（obj）
      ? Array.from(obj)
      ：克隆;
};
```

<details>
<summary>Examples</summary>

```js
const a = {foo：&#39;bar&#39;，obj：{a：1，b：2}};
 const b = deepClone（a）;  // a！== b，a.obj！== b.obj
```
</details>


### deepFreeze

深度冻结对象.

在传递的对象的所有未冻结属性（即instanceof对象）上递归调用Object.freeze（obj）.

```js
const deepFreeze = obj =&gt;
  Object.keys（obj）.forEach（prop =&gt;
     ！（obj [prop] instanceof Object）||  Object.isFrozen（obj [prop]）吗？  null：deepFreeze（obj [prop]）
   ）||  Object.freeze（obj）;
```

<details>
<summary>Examples</summary>

```js
“使用严格”；

const o = deepFreeze（[1，[2，3]]）;

 o [0] = 3;  // 不允许
 o [1] [0] = 4;  //也不允许
```
</details>


### deepGet

根据`keys`数组返回嵌套JSON对象中的目标值.

将您想要的嵌套JSON对象中的键作为“数组”进行比较.
使用Array.prototype.reduce（）来从嵌套的JSON对象中一对一地获取值. 
如果键存在于对象中，则返回目标值，否则返回“ null”.

```js
const deepGet =（obj，keys）=&gt; keys.reduce（（xs，x）=&gt;（xs &amp;&amp; xs [x]？xs [x]：null），obj）;复制代码
```

<details>
<summary>Examples</summary>

```js
令index = 2;
const data = {
  foo: {
    嘴巴：[1,2,3]，
    酒吧：{
      baz：[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
    }
  }
};
 deepGet（data，[&#39;foo&#39;，&#39;foz&#39;，index]）;  //得到3
 deepGet（数据，[&#39;foo&#39;，&#39;bar&#39;，&#39;baz&#39;，8，&#39;foz&#39;]））;  // 空值
```
</details>



深度映射对象的键.

创建一个与提供的对象具有相同值的对象，并为每个键运行通过提供的功能生成的键.
使用Object.keys（obj）遍历对象的键. 
使用Array.prototype.reduce（）使用fn创建一个具有相同值和映射键的新对象.

```js
const deepMapKeys =（obj，f）=&gt;
  Array.isArray（obj）
     什么啊  obj.map（val =&gt; deepMapKeys（val，f））
    ：typeof obj ===&#39;对象&#39;
       ？  Object.keys（obj）.reduce（（acc，current）=&gt; {
        const val = obj [current];
        acc [f（current）] =
           val！== null &amp;&amp; typeof val ===&#39;object&#39;吗？  deepMapKeys（val，f）：（acc [f（current）] = val）;
        返回acc；
      }, {})
      ：obj;
```

<details>
<summary>Examples</summary>

```js
const obj = {
  foo：“ 1”，
  嵌套：{
    孩子：{
      withArray：[
        {
          grandChild：[&#39;hello&#39;]
        }
      ]
    }
  }
};
const upperKeysObj = deepMapKeys（obj，key =&gt; key.toUpperCase（））;
/*
{
  “ FOO”：“ 1”，
  “嵌套”：{
    “儿童”：{
      “ WITHARRAY”：[
        {
          “ GRANDCHILD”：[&#39;hello&#39;]
        }
      ]
    }
  }
}
*/
```
</details>


### defaults

为对象中所有未定义的属性分配默认值.

使用Object.assign（）创建一个新的空对象，并复制原始对象以保持键顺序，使用Array.prototype.reverse（）和散布运算符...来组合左侧的默认值在右边，最后再次使用`obj`覆盖原来具有值的属性.

```js
const defaults =（obj，... defs）=&gt; Object.assign（{}，obj，... defs.reverse（），obj）;
```

<details>
<summary>Examples</summary>

```js
 默认值（{a：1}，{b：2}，{b：6}，{a：3}）;  // {a：1，b：2}
```
</details>


### dig

根据给定的键，返回嵌套JSON对象中的目标值.

使用in操作符检查obj中是否存在目标.
如果找到，则返回obj [target]的值，否则使用Object.values（obj）和Array.prototype.reduce（）在每个嵌套对象上递归调用dig，直到第一个匹配的键/找到值对.

```js
const dig =（obj，target）=&gt;
  obj中的目标
     ？  obj [目标]
    ：Object.values（obj）.reduce（（acc，val）=&gt; {
      如果（acc！==未定义）返回acc;
      如果（typeof val ===&#39;object&#39;）返回dig（val，target）;
    }，未定义）；
```

<details>
<summary>Examples</summary>

```js
const data = {
  1级： {
    级别2：{
      3级：“某些数据”
    }
  }
};
 dig（数据，&#39;level3&#39;）;  // &#39;一些数据&#39;
 您（数据，“ level4”）；  //未定义
```
</details>



在两个值之间进行深度比较以确定它们是否等效.

使用`Date.getTime（）`检查两个值是否相同，是否都是相同的&#39;Date&#39;对象，或者是否都是相等的非对象值（严格比较）.
检查是否只有一个值为“ null”或“ undefined”，或者它们的原型是否不同.
如果以上条件都不满足，则使用Object.keys（）检查两个值是否具有相同数量的键，然后使用Array.prototype.every（）检查第一个值中的每个键是否存在在第二种方法中，如果它们等效，则通过递归调用此方法.

```js
const等于=（a，b）=&gt; {
  如果（a === b）返回true;
  if（a instanceof Date &amp;&amp; b instanceof Date）返回a.getTime（）=== b.getTime（）;
  if（！a ||！b ||（typeof a！==&#39;object&#39;&amp;&amp; typeof b！==&#39;object&#39;））返回a === b;
  如果（a.prototype！== b.prototype）返回false;
  let keys = Object.keys（a）;
  如果（keys.length！== Object.keys（b）.length）返回false;
  返回keys.every（k =&gt; equals（a [k]，b [k]））;
};
```

<details>
<summary>Examples</summary>

```js
 等于（{a：[2，{e：3}]，b：[4]，c：&#39;foo&#39;}，{a：[2，{e：3}]，b：[4]，c：&#39; foo&#39;}）;  //正确
```
</details>


### findKey

 返回满足提供的测试功能的第一个键.  否则返回“未定义”.

 使用Object.keys（obj）获取对象的所有属性，使用Array.prototype.find（）测试每个键值对提供的功能.  回调接收三个参数-值，键和对象.

```js
const findKey =（obj，fn）=&gt; Object.keys（obj）.find（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
findKey(
  {
    巴尼（Barney）：{年龄：36，活跃程度：是}，
    弗雷德：{年龄：40，活跃：虚假}，
    小卵石：{年龄：1，活跃程度：是}
  },
  o =&gt; o [&#39;active&#39;]
 ）;  //&#39;barney&#39;
```
</details>


### findLastKey

返回满足提供的测试功能的最后一个键.
否则返回“未定义”.

使用Object.keys（obj）获取对象的所有属性，使用Array.prototype.reverse（）颠倒顺序，使用Array.prototype.find（）测试每个键的提供的功能，价值对.
回调接收三个参数-值，键和对象.

```js
const findLastKey =（obj，fn）=&gt;
  Object.keys（obj）
    .相反（）
    .find（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
findLastKey(
  {
    巴尼（Barney）：{年龄：36，活跃程度：是}，
    弗雷德：{年龄：40，活跃：虚假}，
    小卵石：{年龄：1，活跃程度：是}
  },
  o =&gt; o [&#39;active&#39;]
 ）;  //&#39;鹅卵石&#39;
```
</details>


### flattenObject

使用键的路径展平对象.

使用递归.
将Object.keys（obj）与Array.prototype.reduce（）结合使用，可以将每个叶节点转换为平坦的路径节点.
如果键的值是一个对象，则该函数使用适当的“前缀”调用自身，以使用“ Object.assign（）”创建路径.
否则，它将适当的前缀键值对添加到累加器对象.
除非您希望每个键都有一个前缀，否则应始终省略第二个参数“ prefix”.

```js
const flattenObject =（obj，前缀=&#39;&#39;）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
     const pre = prefix.length？  前缀+&#39;.&#39;  ：&#39;&#39;;
    如果（typeof obj [k] ===&#39;object&#39;）Object.assign（acc，flattenObject（obj [k]，pre + k））;
    else acc [pre + k] = obj [k];
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 flattenObject（{a：{b：{c：1}}，d：1}）;  // {&#39;abc&#39;：1，d：1}
```
</details>


### forOwn

遍历一个对象的所有自身属性，为每个对象运行一个回调.

 使用Object.keys（obj）获取对象的所有属性，使用Array.prototype.forEach（）为每个键值对运行提供的函数.  回调接收三个参数-值，键和对象.

```js
const forOwn =（obj，fn）=&gt; Object.keys（obj）.forEach（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
 forOwn（{foo：&#39;bar&#39;，a：1}，v =&gt; console.log（v））;  //&#39;bar&#39;，1
```
</details>


### forOwnRight

反向遍历对象的所有自身属性，为每个对象运行一个回调.

 使用Object.keys（obj）获取对象的所有属性，使用Array.prototype.reverse（）颠倒其顺序，使用Array.prototype.forEach（）为每个键运行提供的功能，价值对.  回调接收三个参数-值，键和对象.

```js
const forOwnRight =（obj，fn）=&gt;
  Object.keys（obj）
    .相反（）
    .forEach（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
 forOwnRight（{foo：&#39;bar&#39;，a：1}，v =&gt; console.log（v））;  // 1，&#39;bar&#39;
```
</details>


### functions

从对象自己的（并且可选地继承）可枚举属性中返回函数属性名称的数组.

使用Object.keys（obj）迭代对象本身的属性.
如果“继承”为“ true”，则使用“ Object.get.PrototypeOf（obj）”来获取对象的继承属性.
使用Array.prototype.filter（）仅保留那些作为函数的属性.
省略第二个参数“继承”，默认情况下不包括继承的属性.

```js
const函数=（obj，继承的= false）=&gt;
  （遗传
     ？  [... Object.keys（obj），... Object.keys（Object.getPrototypeOf（obj））]
    ：Object.keys（obj）
  ）.filter（key =&gt; typeof obj [key] ===&#39;function&#39;）;
```

<details>
<summary>Examples</summary>

```js
函数Foo（）{
  this.a =（）=&gt; 1;
  this.b =（）=&gt; 2;
}
Foo.prototype.c =（）=&gt; 3;
 函数（新的Foo（））；  // [&#39;a&#39;，&#39;b&#39;]
 函数（new Foo（），true）;  // [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
```
</details>


### get

从对象检索由给定选择器指示的一组属性.

对每个选择器使用“ Array.prototype.map（）”，“ String.prototype.replace（）”用点代替方括号，“ String.prototype.split（&#39;.”）”用于拆分每个选择器“ Array”. prototype.filter（）除去空值，而Array.prototype.reduce（）除去它指示的值.

```js
const get =（from，... selectors）=&gt;
  [... selectors] .map（s =&gt;
    s
      .replace（/ \ [（[[^ \ [\]] *）\] / g，&#39;.$ 1.&#39;）
      .分裂（&#39;.&#39;）
      .filter（t =&gt; t！==&#39;&#39;）
      .reduce（（prev，cur）=&gt; prev &amp;&amp; prev [cur]，来自）
  );
```

<details>
<summary>Examples</summary>

```js
const obj = {选择器：{到：{val：&#39;要选择的val&#39;}}，目标：[1,2，{a：&#39;test&#39;}]};
 get（obj，&#39;selector.to.val&#39;，&#39;target [0]&#39;，&#39;target [2] .a&#39;）;  // [&#39;val to select&#39;，1，&#39;test&#39;]
```
</details>


### hasKey

如果目标值存在于JSON对象中，则返回“ true”，否则返回“ false”.

检查keys是否为非空，并使用Array.prototype.every（）顺序检查其key以达到对象obj的内部深度. 
使用Object.prototype.hasOwnProperty（）检查obj是否没有当前键或不是对象，停止传播并返回false.
否则，将键的值分配给obj以在下一次迭代中使用.

如果给定的密钥列表为空，则事先返回“ false”.

```js
const hasKey =（obj，keys）=&gt; {
  返回（keys.length&gt; 0）&amp;&amp; keys.every（key =&gt; {
    if（typeof obj！==&#39;object&#39;||！obj.hasOwnProperty（key））返回false;
    obj = obj [key];
    返回true；
  });
};
```

<details>
<summary>Examples</summary>

```js
年obj = {
  a：1
  b：{c：4}，
  &#39;b.d&#39;：5
};
 hasKey（obj，[&#39;a&#39;]）;  //正确
 hasKey（obj，[&#39;b&#39;]）;  //正确
 hasKey（obj，[&#39;b&#39;，&#39;c&#39;]）;  //正确
 hasKey（obj，[&#39;b.d&#39;]）;  //正确
 hasKey（obj，[&#39;d&#39;]）;  //错误
 hasKey（obj，[&#39;c&#39;]）;  //错误
 hasKey（obj，[&#39;b&#39;，&#39;f&#39;]）;  //错误
```
</details>


### invertKeyValues

 反转对象的键/值对，而不对其进行突变.  每个反转键的相应反转值是负责生成反转值的键的数组.  如果提供了功能，则该功能将应用于每个反向键.

使用Object.keys（）和Array.prototype.reduce（）反转对象的键值对并应用提供的功能（如果有）.
省略第二个参数`fn`，以获取反向键而不对它们应用函数.

```js
const invertKeyValues =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，key）=&gt; {
     const val = fn？  fn（obj [key]）：obj [key];
     acc [val] = acc [val] ||  [];
    acc [val] .push（key）;
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 invertKeyValues（{a：1，b：2，c：1}）;  // {1：[&#39;&#39;a&#39;，&#39;c&#39;]，2：[&#39;b&#39;]}
 invertKeyValues（{a：1，b：2，c：1}，value =&gt;&#39;group&#39;+ value）;  // {group1：[&#39;a&#39;，&#39;c&#39;]，group2：[&#39;b&#39;]}
```
</details>


### lowercaseKeys

从指定的对象创建一个新的对象，其中所有键都小写.

使用Object.keys（）和Array.prototype.reduce（）从指定对象创建一个新对象.
使用String.toLowerCase（）将原始对象中的每个键转换为小写.

```js
const lowercaseKeys = obj =&gt;
  Object.keys（obj）.reduce（（acc，key）=&gt; {
    acc [key.toLowerCase（）] = obj [key];
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
const myObj = {Name：&#39;Adam&#39;，sUrnAME：&#39;Smith&#39;};
 const myObjLower = lowercaseKeys（myObj）;  // {名称：“亚当”，姓氏：“史密斯”}；
```
</details>


### mapKeys

创建一个对象，该对象具有通过为每个键运行提供的函数并与提供的对象具有相同值的键生成的键.

使用Object.keys（obj）遍历对象的键.
使用Array.prototype.reduce（）使用fn创建一个具有相同值和映射键的新对象.

```js
const mapKeys =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    acc [fn（obj [k]，k，obj）] = obj [k];
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 mapKeys（{a：1，b：2}，（val，key）=&gt;键+ val）;  // {a1：1，b2：2}
```
</details>


### mapValues

创建一个与提供的对象具有相同键的对象，并为每个值运行通过提供的函数生成的值.

使用Object.keys（obj）遍历对象的键.
使用Array.prototype.reduce（）使用fn创建具有相同键和映射值的新对象.

```js
const mapValues =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    acc [k] = fn（obj [k]，k，obj）;
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
const用户= {
  弗雷德：{用户：“弗雷德”，年龄：40}，
  卵石：{用户：“卵石”，年龄：1}
};
 mapValues（用户，u =&gt; u.age）;  // {fred：40，小卵石：1}
```
</details>


### matches

比较两个对象，以确定第一个对象是否包含与第二个对象相同的属性值.

使用Object.keys（source）获取第二个对象的所有键，然后使用Array.prototype.every（），Object.hasOwnProperty（）和严格比较来确定所有键是否都存在于第一个对象中并具有相同的值.

```js
const匹配=（obj，源）=&gt;
  Object.keys（source）.every（key =&gt; obj.hasOwnProperty（key）&amp;&amp; obj [key] === source [key]）;
```

<details>
<summary>Examples</summary>

```js
 匹配（{年龄：25，头发：“ long”，胡须：true}，{头发：“ long”，胡须：true}）；  //正确
 matchs（{hair：&#39;long&#39;，胡须：true}，{年龄：25，hair：&#39;long&#39;，胡须：true}）;  //错误
```
</details>


### matchesWith

根据提供的函数比较两个对象，以确定第一个对象是否包含与第二个对象相同的属性值.

使用Object.keys（source）获取第二个对象的所有键，然后使用Array.prototype.every（），Object.hasOwnProperty（）和提供的函数确定所有键是否都存在于第一个对象中对象并具有相等的值.
如果未提供任何功能，则将使用相等运算符比较这些值.

```js
constmatchesWith =（obj，source，fn）=&gt;
  Object.keys(source).every(key =>
    obj.hasOwnProperty（key）&amp;&amp; fn
       ？  fn（obj [key]，source [key]，key，obj，source）
      ：obj [key] == source [key]
  );
```

<details>
<summary>Examples</summary>

```js
const isGreeting = val =&gt; /^h(?:i|ello)$/.test(val）;
matchesWith(
  {问候：“ hello”}，
  {问候：“嗨”}，
  （oV，sV）=&gt; isGreeting（oV）&amp;&amp; isGreeting（sV）
 ）;  //正确
```
</details>


### merge

通过两个或更多对象的组合创建一个新对象.

将Array.prototype.reduce（）与Object.keys（obj）结合使用以遍历所有对象和键.
使用“ hasOwnProperty（）”和“ Array.prototype.concat（）”为存在于多个对象中的键附加值.

```js
const merge =（... objs）=&gt;
  [... objs] .reduce（
    （acc，obj）=&gt;
      Object.keys（obj）.reduce（（a，k）=&gt; {
         acc [k] = acc.hasOwnProperty（k）吗？  [] .concat（acc [k]）.concat（obj [k]）：obj [k];
        返回acc；
      }, {}),
    {}
  );
```

<details>
<summary>Examples</summary>

```js
const object = {
  a：[{x：2}，{y：4}]，
  b：1
};
const other = {
  和：{of：3}，
  b：[2，3]，
  c：“ foo”
};
 合并（对象，其他）；  // {a：[{x：2}，{y：4}，{z：3}]，b：[1，2，3]，c：&#39;foo&#39;}
```
</details>


### nest

给定一组相互链接的平面对象，它将以递归方式嵌套它们.
对于嵌套注释（例如reddit.com上的注释）很有用.

使用递归.
使用Array.prototype.filter（）过滤ID匹配link的项目，然后使用Array.prototype.map（）将每个对象映射到具有child属性的新对象.会根据哪些是当前项目的子项来递归嵌套这些项目.
省略第二个参数“ id”，默认为“ null”，表示该对象未链接到另一个（即它是顶级对象）.
省略第三个参数“ link”，以使用“ parent_id”作为默认属性，该默认属性通过“ id”将对象链接到另一个对象.

```js
const nest =（items，id = null，link =&#39;parent_id&#39;）=&gt;
  项目
    .filter（item =&gt; item [link] === id）
    .map（item =&gt;（{... item，children：nest（items，item.id）}））;;
```

<details>
<summary>Examples</summary>

```js
//一个顶级评论
const评论= [
  {id：1，parent_id：null}，
  {id：2，parent_id：1}，
  {id：3，parent_id：1}，
  {id：4，parent_id：2}，
  {id：5，parent_id：4}
];
 const nestedComments = nest（comments）;  // [{{id：1，parent_id：null，children：[...]}]
```
</details>


### objectFromPairs

根据给定的键值对创建一个对象.

使用Array.prototype.reduce（）创建和组合键值对.

```js
const objectFromPairs = arr =&gt; arr.reduce（（a，[key，val]）=&gt;（（（a [key] = val），a），{}）;
```

<details>
<summary>Examples</summary>

```js
 objectFromPairs（[[&#39;a&#39;，1]，[&#39;b&#39;，2]]）;  // {a：1，b：2}
```
</details>


### objectToPairs

从一个对象创建一个键-值对数组.

使用Object.keys（）和Array.prototype.map（）遍历对象的键并生成具有键值对的数组.

```js
const objectToPairs = obj =&gt; Object.keys（obj）.map（k =&gt; [k，obj [k]]）;
```

<details>
<summary>Examples</summary>

```js
 objectToPairs（{a：1，b：2}）;  // [[&#39;a&#39;，1]，[&#39;b&#39;，2]]
```
</details>


### omit

从对象中省略与给定键对应的键值对.

使用Object.keys（obj），Array.prototype.filter（）和Array.prototype.includes（）删除提供的键.
使用Array.prototype.reduce（）将过滤后的键转换回具有相应键值对的对象.

```js
const omit =（obj，arr）=&gt;
  Object.keys（obj）
    .filter（k =&gt;！arr.includes（k））
    .reduce（（acc，key）=&gt;（（（acc [key] = obj [key]），acc），{}）;;
```

<details>
<summary>Examples</summary>

```js
 omit（{a：1，b：&#39;2&#39;，c：3}，[&#39;b&#39;]）；  // {&#39;a&#39;：1，&#39;c&#39;：3}
```
</details>


### omitBy

 创建一个对象，该对象由给定函数返回falsy的属性组成.  该函数使用两个参数调用：（值，键）.

使用Object.keys（obj）和Array.prototype.filter（）删除fn返回真实值的键.
使用Array.prototype.reduce（）将过滤后的键转换回具有相应键值对的对象.

```js
const omitBy =（obj，fn）=&gt;
  Object.keys（obj）
    .filter（k =&gt;！fn（obj [k]，k））
    .reduce（（acc，key）=&gt;（（（acc [key] = obj [key]），acc），{}）;;
```

<details>
<summary>Examples</summary>

```js
 omitBy（{a：1，b：&#39;2&#39;，c：3}，x =&gt; typeof x ===&#39;number&#39;）;  // {b：&#39;2&#39;}
```
</details>


### orderBy

返回按属性和顺序排序的对象的排序数组.

在props数组上使用默认值为0的Array.prototype.sort（），Array.prototype.reduce（），并根据传递的顺序使用数组解构来交换属性位置.
如果没有传递“ orders”数组，则默认情况下按“ asc”排序.

```js
const orderBy =（arr，props，order）=&gt;
  [... arr] .sort（（a，b）=&gt;
    props.reduce（（acc，prop，i）=&gt; {
      如果（acc === 0）{
         const [p1，p2] =订单&amp;&amp;订单[i] ===&#39;desc&#39;吗？  [b [prop]，a [prop]]：[a [prop]，b [prop]]；
         acc = p1&gt; p2吗？  1：p1 &lt;p2？  -1：0;
      }
      返回acc；
    }, 0)
  );
```

<details>
<summary>Examples</summary>

```js
const users = [{{name：&#39;fred&#39;，age：48}，{name：&#39;barney&#39;，age：36}，{name：&#39;fred&#39;，age：40}]；
orderBy(users, ['name', 'age'], ['asc', 'desc']); // [{name: 'barney', age: 36}, {name: 'fred', age: 48}, {name: 'fred', age: 40}]
 orderBy（users，[&#39;name&#39;，&#39;age&#39;]）;  // [{{name：&#39;barney&#39;，age：36}，{name：&#39;fred&#39;，age：40}，{name：&#39;fred&#39;，age：48}]
```
</details>


### pick

从对象中选择与给定键对应的键值对.

如果对象中存在键，则使用Array.prototype.reduce（）将经过过滤/挑选的键转换回具有相应键值对的对象.

```js
const pick =（obj，arr）=&gt;
  arr.reduce（（acc，curr）=&gt;（obj &amp;&amp;（acc [curr] = obj [curr]），acc），{}）中的curr;
```

<details>
<summary>Examples</summary>

```js
 pick（{a：1，b：&#39;2&#39;，c：3}，[&#39;a&#39;，&#39;c&#39;]）;  // {&#39;a&#39;：1，&#39;c&#39;：3}
```
</details>


### pickBy

 创建一个由给定函数返回true的属性组成的对象.  该函数使用两个参数调用：（值，键）.

使用Object.keys（obj）和Array.prototype.filter（）删除fn返回伪造值的键.
使用Array.prototype.reduce（）将过滤后的键转换回具有相应键值对的对象.

```js
const pickBy =（obj，fn）=&gt;
  Object.keys（obj）
    .filter（k =&gt; fn（obj [k]，k））
    .reduce（（acc，key）=&gt;（（（acc [key] = obj [key]），acc），{}）;;
```

<details>
<summary>Examples</summary>

```js
 pickBy（{a：1，b：&#39;2&#39;，c：3}，x =&gt; typeof x ===&#39;number&#39;）;  // {&#39;a&#39;：1，&#39;c&#39;：3}
```
</details>


### renameKeys

用提供的值替换多个对象键的名称.

将Object.keys（）与Array.prototype.reduce（）和散布运算符（...）结合使用，以获取对象的键并根据keysMap对其重命名.

```js
const namedKeys =（keysMap，obj）=&gt;
  Object.keys（obj）.reduce（
    （acc，key）=&gt;（{
      ... acc，
       ... {[keysMap [key] ||  键]：obj [key]}
    }),
    {}
  );
```

<details>
<summary>Examples</summary>

```js
const obj = {name：&#39;Bobo&#39;，job：&#39;Front-End Master&#39;，shoeSize：100};
 namedKeys（{name：&#39;firstName&#39;，job：&#39;passion&#39;}，obj）;  // {firstName：“ Bobo”，热情：“ Front-End Master”，shoeSize：100}
```
</details>


### shallowClone

创建对象的浅表副本.

使用Object.assign（）和空对象（{}）创建原始对象的浅表副本.

```js
constallowClone = obj =&gt; Object.assign（{}，obj）;
```

<details>
<summary>Examples</summary>

```js
const a = {x：true，y：1};
 const b =浅克隆（a）;  // a！== b
```
</details>


### size

获取数组，对象或字符串的大小.

获取val类型（数组，对象或字符串）. 
对数组使用`length`属性.
如果可用，则使用“长度”或“大小”值，或者使用对象的键数.
使用a的`size` [`Blob` object](https://developer.mozilla.org/en-US/docs/Web/API/Blob) 从`val`创建的字符串.
用`split（&#39;&#39;）`将字符串分割成字符数组，并返回其长度.

```js
const size = val =&gt;
  Array.isArray（val）
     ？  长度
    ：val &amp;&amp; typeof val ===&#39;对象&#39;
     ？  val.size ||  val.length ||  Object.keys（val）.length
    ：typeof val ===&#39;字符串&#39;
     ？  新Blob（[val]）.size
    : 0;
```

<details>
<summary>Examples</summary>

```js
 大小（[1、2、3、4、5]）;  // 5
 大小（&#39;大小&#39;）;  // 4
 大小（{一：1，二：2，三：3}）;  // 3
```
</details>


### transform

对一个累加器和对象中的每个键（从左到右）应用一个函数.

使用Object.keys（obj）遍历对象中的每个键，使用Array.prototype.reduce（）调用将指定函数应用于给定的累加器.

```js
const transform =（obj，fn，acc）=&gt; Object.keys（obj）.reduce（（a，k）=&gt; fn（a，obj [k]，k，obj），acc）;
```

<details>
<summary>Examples</summary>

```js
transform(
  {a：1，b：2，c：1}，
  （r，v，k）=&gt; {
    （r [v] ||（r [v] = []）））.
    返回r;
  },
  {}
 ）;  // {&#39;1&#39;：[&#39;a&#39;，&#39;c&#39;]，&#39;2&#39;：[&#39;b&#39;]}
```
</details>


### truthCheckCollection

检查谓词（第二个参数）在集合的所有元素（第一个参数）上是否为真.

使用Array.prototype.every（）检查每个传递的对象是否具有指定的属性，以及它是否返回真实值.

```js
const trueCheckCollection =（collection，pre）=&gt; collection.every（obj =&gt; obj [pre]）;
```

<details>
<summary>Examples</summary>

```js
 trueCheckCollection（[{用户：&#39;Tinky-Winky&#39;，性别：&#39;男性&#39;}，{用户：&#39;Dipsy&#39;，性别：&#39;男性&#39;}]，“性别”）；  //正确
```
</details>



使用键的路径展开对象.

结合使用Object.keys（obj）和Array.prototype.reduce（）将扁平化的路径节点转换为叶节点.
如果键的值包含点定界符（.），请使用Array.prototype.split（..），字符串转换和JSON.parse（）创建对象，然后使用Object.assign （）`创建叶子节点.
否则，将适当的键值对添加到累加器对象.

```js
const unflattenObject = obj =&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    如果（k.indexOf（&#39;.&#39;）！== -1）{
      const键= k.split（&#39;.&#39;）;
      Object.assign（
        acc，
        JSON.parse（
          '{' +
            keys.map（（v，i）=&gt;（i！== keys.length-1？“” $ {v}“：{`：`” $ {v}“：`））.join（&#39;&#39;） +
            卷[k] +
            &#39;}&#39;.repeat（keys.length）
        )
      );
    } else acc [k] = obj [k];
    返回acc；
  }, {});
```

<details>
<summary>Examples</summary>

```js
 unflattenObject（{&#39;abc&#39;：1，d：1}）;  // {a：{b：{c：1}}，d：1}
```
</details>


---

## 📜 String


### byteSize

返回字符串的长度（以字节为单位）.

将给定的字符串转换为 [`Blob` Object](https://developer.mozilla.org/en-US/docs/Web/API/Blob) 并找到它的大小.

```js
const byteSize = str =&gt; new Blob（[str]）.size;
```

<details>
<summary>Examples</summary>

```js
 byteSize（&#39;&#39;）;  // 4
 byteSize（&#39;Hello World&#39;）;  // 11
```
</details>


### capitalize

大写字符串的第一个字母.

使用数组解构和`String.prototype.toUpperCase（）`大写第一个字母，`... rest`获取第一个字母后的字符数组，然后使用&#39;Array.prototype.join（&#39;&#39;）`使其成为字符串再次.
省略`lowerRest`参数以保持字符串的其余部分不变，或将其设置为`true`以转换为小写字母.

```js
const capitalize =（[[first，... rest]，lowerRest = false）=&gt;
  first.toUpperCase（）+（lowerRest？rest.join（&#39;&#39;）.toLowerCase（）：rest.join（&#39;&#39;））;
```

<details>
<summary>Examples</summary>

```js
 capitalize（&#39;fooBar&#39;）;  //&#39;FooBar&#39;
 capitalize（&#39;fooBar&#39;，true）;  //&#39;Foobar&#39;
```
</details>


### capitalizeEveryWord

将字符串中每个单词的首字母大写.

使用`String.prototype.replace（）`匹配每个单词的第一个字符，并使用&#39;String.prototype.toUpperCase（）`使其大写.

```js
const capitalizeEveryWord = str =&gt; str.replace（/ \ b [az] / g，char =&gt; char.toUpperCase（））;
```

<details>
<summary>Examples</summary>

```js
 capitalizeEveryWord（&#39;hello world！&#39;）;  // &#39;你好，世界！&#39;
```
</details>


### compactWhitespace

返回压缩了空格的字符串.

使用带有正则表达式的`String.prototype.replace（）`将所有出现的2个或多个空格字符替换为一个空格.

```js
const compactWhitespace = str =&gt; str.replace（/ \ s {2，} / g，&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 compactWhitespace（ &#39;Lorem存有&#39;）;  // &#39;Lorem存有&#39;
 compactWhitespace（ &#39;LOREM \ n非常&#39;）;  // &#39;Lorem存有&#39;
```
</details>


### CSVToArray

将逗号分隔值（CSV）字符串转换为2D数组.

如果`omitFirstRow`为true，则使用Array.prototype.slice（）和Array.prototype.indexOf（&#39;\ n&#39;）删除第一行（标题行）.
使用String.prototype.split（&#39;\ n&#39;）为每一行创建一个字符串，然后使用String.prototype.split（delimiter）分隔每一行中的值.
省略第二个参数`delimiter`，以使用默认定界符`，`.
省略第三个参数“ omitFirstRow”，以包含CSV字符串的第一行（标题行）.

```js
const CSVToArray =（数据，分隔符=&#39;，&#39;，omitFirstRow = false）=&gt;
  数据
    .slice（omitFirstRow？data.indexOf（&#39;\ n&#39;）+ 1：0）
    .split（ &#39;\ n&#39;）
    .map（v =&gt; v.split（定界符））;
```

<details>
<summary>Examples</summary>

```js
 CSVToArray（&#39;a，b \ nc，d&#39;）;  // [[&#39;A B C D&#39;]];
 CSVToArray（&#39;a; b \ nc; d&#39;，&#39;;&#39;）;  // [[&#39;A B C D&#39;]];
 CSVToArray（&#39;col1，col2 \ na，b \ nc，d&#39;，&#39;，&#39;，true）;  // [[&#39;A B C D&#39;]];
```
</details>



将逗号分隔值（CSV）字符串转换为2D对象数组.
字符串的第一行用作标题行.

使用Array.prototype.slice（）和Array.prototype.indexOf（&#39;\ n&#39;）和String.prototype.split（delimiter）将第一行（标题行）分隔为多个值.
使用String.prototype.split（&#39;\ n&#39;）为每一行创建一个字符串，然后使用Array.prototype.map（）和String.prototype.split（delimiter）分隔每一行中的值.
使用Array.prototype.reduce（）为每行的值创建一个对象，并从标题行中解析键.
省略第二个参数`delimiter`，以使用默认定界符`，`.

```js
const CSVToJSON =（数据，分隔符=&#39;，&#39;）=&gt; {
  const title = data.slice（0，data.indexOf（&#39;\ n&#39;））.split（delimiter）;
  返回数据
    .slice（data.indexOf（&#39;\ n&#39;）+1）
    .split（ &#39;\ n&#39;）
    .map（v =&gt; {
      const值= v.split（定界符）;
      返回titles.reduce（（（obj，title，index）=&gt;（（（obj [title] = values [index]），obj），{}）;
    });
};
```

<details>
<summary>Examples</summary>

```js
 CSVToJSON（&#39;col1，col2 \ na，b \ nc，d&#39;）;  // [{&#39;col1&#39;：&#39;a&#39;，&#39;col2&#39;：&#39;b&#39;}，{&#39;col1&#39;：&#39;c&#39;，&#39;col2&#39;：&#39;d&#39;}]​​;
 CSVToJSON（&#39;col1; col2 \ na; b \ nc; d&#39;，&#39;;&#39;）;  // [{&#39;col1&#39;：&#39;a&#39;，&#39;col2&#39;：&#39;b&#39;}，{&#39;col1&#39;：&#39;c&#39;，&#39;col2&#39;：&#39;d&#39;}]​​;
```
</details>


### decapitalize

将字符串的首字母大写.

使用数组解构和“ String.toLowerCase（）”将首字母大写，“ ... rest”获取首字母后的字符数组，然后使用“ Array.prototype.join（&#39;&#39;）`再次使其成为字符串.
省略参数upperRest以保持字符串的其余部分不变，或将其设置为true转换为大写.

```js
const decapitalize =（[[first，... rest]，upperRest = false）=&gt;
  first.toLowerCase（）+（upperRest？rest.join（&#39;&#39;）.toUpperCase（）：rest.join（&#39;&#39;））;
```

<details>
<summary>Examples</summary>

```js
 取消资本化（&#39;FooBar&#39;）;  //&#39;fooBar&#39;
 decapitalize（&#39;FooBar&#39;，true）;  //&#39;fOOBAR&#39;
```
</details>


### escapeHTML

转义用于HTML的字符串.

将String.prototype.replace（）与正则表达式匹配以匹配需要转义的字符，并使用回调函数通过字典（对象）将每个字符实例替换为其关联的转义字符.

```js
const escapeHTML = str =&gt;
  str.replace（
    / [＆&lt;&gt;&#39;“] / g，
    标签=&gt;
      ({
        &#39;＆&#39;：&#39;＆&#39;，
        '<': '&lt;',
        &#39;&gt;&#39;：&#39;&gt;&#39;，
        "'": '&#39;',
        &#39;“&#39;：&#39;”&#39;
       } [天] ||  标签）
  );
```

<details>
<summary>Examples</summary>

```js
escapeHTML('<a href="#">Me & you</a>'); // '&lt;a href=&quot;#&quot;&gt;Me &amp; you&lt;/a&gt;'
```
</details>


### escapeRegExp

转义要在正则表达式中使用的字符串.

使用String.prototype.replace（）转义特殊字符.

```js
const escapeRegExp = str =&gt; str.replace（/ [.* +？^ $ {}（）| [\] \\] / g，&#39;\\ $＆&#39;）;
```

<details>
<summary>Examples</summary>

```js
 escapeRegExp（&#39;（test）&#39;）;  // \\（测试\\）
```
</details>


### fromCamelCase

从驼峰式转换字符串.

使用String.prototype.replace（）删除下划线，连字符和空格，并将单词转换为驼峰式.
省略第二个参数以使用默认的_分隔符.

```js
const fromCamelCase =（str，分隔符=&#39;_&#39;）=&gt;
  海峡
    .replace（/（[[az \ d]）（[AZ]）/ g，&#39;$ 1&#39;+分隔符+&#39;$ 2&#39;）
    .replace（/（[[AZ] +）（[AZ] [az \ d] +）/ g，&#39;$ 1&#39;+分隔符+&#39;$ 2&#39;）
    .toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 fromCamelCase（&#39;someDatabaseFieldName&#39;，&#39;&#39;）;  //&#39;一些数据库字段名称&#39;
 fromCamelCase（&#39;someLabelThatNeedsToBeCamelized&#39;，&#39;-&#39;）;  //&#39;需要被骆驼化的某些标签&#39;
 fromCamelCase（&#39;someJavascriptProperty&#39;，&#39;_&#39;）;  //&#39;some_javascript_property&#39;
```
</details>


### indentString

缩进提供的字符串中的每一行.

使用String.replace和正则表达式在每行的开头添加由indent`count`次指定的字符.
省略第三个参数`indent`，以使用默认的缩进字符&#39;&#39;&#39;.

```js
const indentString =（str，count，indent =&#39;&#39;）=&gt; str.replace（/ ^ / gm，indent.repeat（count））;复制代码
```

<details>
<summary>Examples</summary>

```js
 indentString（“LOREM \夹口”，2）;  // &#39;LOREM \ n很&#39;
 indentString（ &#39;LOREM \咬&#39;，2， &#39;_&#39;）;  // __Lorem \ n__Ipsum“
```
</details>


### isAbsoluteURL

如果给定的字符串是绝对URL，则返回“ true”，否则返回“ false”.

使用正则表达式测试字符串是否为绝对URL.

```js
const isAbsoluteURL = str =&gt; /^[az][a-z0-9+.-]*:/.test(str）;
```

<details>
<summary>Examples</summary>

```js
 isAbsoluteURL（&#39;https://google.com&#39;）;  //正确
 isAbsoluteURL（&#39;ftp://www.myserver.net&#39;）;  //正确
 isAbsoluteURL（&#39;/ foo / bar&#39;）;  //错误
```
</details>


### isAnagram

检查一个字符串是否是另一个字符串的字谜（不区分大小写，忽略空格，标点符号和特殊字符）.

使用带有适当正则表达式的String.toLowerCase（），String.prototype.replace（）来删除不必要的字符，String.prototype.split（&#39;&#39;），Array.prototype.sort（）和在两个字符串上使用“ Array.prototype.join（&#39;&#39;）对其进行规范化，然后检查其规范化形式是否相等.

```js
const isAnagram =（str1，str2）=&gt; {
  const normalize = str =&gt;
    海峡
      .toLowerCase（）
      .replace（/ [^ a-z0-9] / gi，&#39;&#39;）
      .分裂（&#39;&#39;）
      .分类（）
      .加入（&#39;&#39;）;
  return normalize（str1）=== normalize（str2）;
};
```

<details>
<summary>Examples</summary>

```js
 isAnagram（&#39;iceman&#39;，&#39;cinema&#39;）;  //正确
```
</details>


### isLowerCase

检查字符串是否为小写.

使用String.toLowerCase（）将给定的字符串转换为小写，并将其与原始字符串进行比较.

```js
const isLowerCase = str =&gt; str === str.toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 isLowerCase（&#39;abc&#39;）;  //正确
 isLowerCase（&#39;a3 @ $&#39;）;  //正确
 isLowerCase（&#39;Ab4&#39;）;  //错误
```
</details>


### isUpperCase

检查字符串是否为大写.

使用String.prototype.toUpperCase（）将给定的字符串转换为大写，并将其与原始字符串进行比较.

```js
const isUpperCase = str =&gt; str === str.toUpperCase（）;
```

<details>
<summary>Examples</summary>

```js
 isUpperCase（&#39;ABC&#39;）;  //正确
 isUpperCase（&#39;A3 @ $&#39;）;  //正确
 isUpperCase（&#39;aB4&#39;）;  //错误
```
</details>


### mapString

创建一个新字符串，并在调用字符串中的每个字符上调用提供的函数.

使用String.prototype.split（&#39;&#39;）和Array.prototype.map（）为str中的每个字符调用提供的函数fn.
使用Array.prototype.join（&#39;&#39;）将字符数组重新组合为字符串.
回调函数fn具有三个参数（当前字符，当前字符的索引以及调用了字符串mapString）.

```js
const mapString =（str，fn）=&gt;
  海峡
    .分裂（&#39;&#39;）
    .map（（c，i）=&gt; fn（c，i，str））
    .加入（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 mapString（ &#39;Lorem存有&#39;，C =&gt; c.toUpperCase（））;  // &#39;Lorem存有&#39;
```
</details>


### mask

用指定的掩码字符替换除最后一个字符以外的所有字符.

使用`String.prototype.slice（）`抓取那些将保持未屏蔽的字符部分，并使用`String.padStart（）`用掩码字符填充字符串的开头，直到原始长度.
 省略第二个参数num以使默认的4个字符不被屏蔽.  如果num为负数，则未屏蔽的字符将在字符串的开头.
省略第三个参数“ mask”，将默认字符“ *”用作掩码.

```js
const mask =（cc，num = 4，mask =&#39;*&#39;）=&gt;`$ {cc}`.slice（-num）.padStart（`$ {cc} .length，mask）;
```

<details>
<summary>Examples</summary>

```js
 面具（1234567890）;  //&#39;****** 7890&#39;
 面具（1234567890，3）;  //&#39;******* 890&#39;
 mask（1234567890，-4，&#39;$&#39;）;  //&#39;$$$$ 567890&#39;
```
</details>


### pad

如果字符串短于指定的长度，则在字符串的两边填充字符串.

使用`String.padStart（）`和`String.padEnd（）`填充给定字符串的两侧.
省略第三个参数“ char”，以将空白字符用作默认的填充字符.

```js
const pad =（str，length，char =&#39;&#39;）=&gt;
  str.padStart（（str.length + length）/ 2，char）.padEnd（length，char）;
```

<details>
<summary>Examples</summary>

```js
 pad（&#39;cat&#39;，8）;  // &#39; 猫 &#39;
 pad（String（42），6，&#39;0&#39;）;  //&#39;004200&#39;
 pad（&#39;foobar&#39;，3）;  //&#39;foobar&#39;
```
</details>


### palindrome

如果给定的字符串是回文，则返回“ true”，否则返回“ false”.

将字符串转换为String.prototype.toLowerCase（）并使用String.prototype.replace（）从其中删除非字母数字字符.
然后，使用传播运算符（...）将字符串拆分为单个字符，即Array.prototype.reverse（），String.prototype.join（&#39;&#39;）并将其与原始的，未反转的字符进行比较字符串，将其转换为`String.prototype.toLowerCase（）`之后.

```js
const palindrome = str =&gt; {
  const s = str.toLowerCase（）.replace（/ [\ W _] / g，&#39;&#39;）;
  return s === [... s] .reverse（）.join（&#39;&#39;）;
};
```

<details>
<summary>Examples</summary>

```js
 回文（&#39;taco cat&#39;）;  //正确
```
</details>


### pluralize

 根据输入数字返回单词的单数或复数形式.  如果第一个参数是`object`，它将通过返回一个函数来使用闭包，该函数可以自动复数单词，如果提供的字典包含单词，这些单词不能简单地以`s`结尾.

 如果num是-1或1，则返回单词的单数形式.  如果num是其他任何数字，则返回复数形式.  忽略第三个参数以使用单数词+`s`的默认值，或在必要时提供自定义的复数词.  如果第一个参数是“对象”，则通过返回一个函数来利用闭包，该函数可以使用提供的字典来解析单词的正确复数形式.

```js
const pluralize =（val，单词，复数=单词+&#39;s&#39;）=&gt; {
  const _pluralize =（数字，单词，复数=单词+&#39;s&#39;）=&gt;
     [1，-1] .includes（Number（num））吗？  复数
  if（typeof val ===&#39;object&#39;）返回（num，word）=&gt; _pluralize（num，word，val [word]）;
  返回_pluralize（val，单词，复数）;
};
```

<details>
<summary>Examples</summary>

```js
 pluralize（0，&#39;apple&#39;）;  // &#39;苹果&#39;
 pluralize（1，&#39;苹果&#39;）;  // &#39;苹果&#39;
 pluralize（2，&#39;苹果&#39;）;  // &#39;苹果&#39;
 复数（2，&#39;人&#39;，&#39;人&#39;）;  //&#39;人民&#39;

const PLURALS = {
  人：“人”，
  半径：“半径”
};
const autoPluralize = pluralize（PLURALS）;
 autoPluralize（2，&#39;人&#39;）;  //&#39;人民&#39;
```
</details>


### removeNonASCII

删除不可打印的ASCII字符.

使用正则表达式删除不可打印的ASCII字符.

```js
const removeNonASCII = str =&gt; str.replace（/ [^ \ x20- \ x7E] / g，&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 removeNonASCII（ &#39;äÄçÇéÉêlorem-ipsumöÖÐþúÚ&#39;）;  //“LOREM自在”
```
</details>


### reverseString

反转字符串.

使用扩展运算符（...）和Array.prototype.reverse（）反转字符串中字符的顺序.
使用String.prototype.join（&#39;&#39;）组合字符以获得字符串.

```js
const reverseString = str =&gt; [... str] .reverse（）.join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 reverseString（&#39;foobar&#39;）;  //&#39;raboof&#39;
```
</details>


### sortCharactersInString

按字母顺序对字符串中的字符进行排序.

使用扩展运算符（...），Array.prototype.sort（）和String.localeCompare（）对str中的字符进行排序，并使用String.prototype.join（）进行重组. `.

```js
const sortCharactersInString = str =&gt; [... str] .sort（（a，b）=&gt; a.localeCompare（b））.join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 sortCharactersInString（&#39;cabbage&#39;）;  //&#39;aabbceg&#39;
```
</details>


### splitLines

将多行字符串拆分为行数组.

使用String.prototype.split（）和一个正则表达式来匹配换行符并创建一个数组.

```js
const splitLines = str =&gt; str.split（/ \ r？\ n /）;
```

<details>
<summary>Examples</summary>

```js
 splitLines（&#39;This \ nis a \ nmultiline \ nstring.\ n&#39;）;  // [&#39;This&#39;，&#39;is a&#39;，&#39;multiline&#39;，&#39;string.&#39;  ，&#39;&#39;]
```
</details>



 ⚠️**警告**：该函数的执行时间随着每个字符的增加而呈指数增长.  超过8到10个字符的任何字符都会导致您的浏览器在尝试解决所有不同的组合时挂起.

生成字符串的所有排列（包含重复项）.

使用递归.
对于给定字符串中的每个字母，为其其余字母创建所有部分排列.
使用Array.prototype.map（）将字母与每个部分排列组合，然后使用Array.prototype.reduce（）将所有排列组合在一个数组中.
基本情况是字符串“ length”等于“ 2”或“ 1”.

```js
const stringPermutations = str =&gt; {
   如果（str.length &lt;= 2）返回str.length === 2？  [str，str [1] + str [0]]：[str];
  返回str
    .分裂（&#39;&#39;）
    .降低（
      （acc，letter，i）=&gt;
        acc.concat（stringPermutations（str.slice（0，i）+ str.slice（i + 1））.map（val =&gt; letter + val）），
      []
    );
};
```

<details>
<summary>Examples</summary>

```js
 stringPermutations（&#39;abc&#39;）;  // [&#39;abc&#39;，&#39;acb&#39;，&#39;bac&#39;，&#39;bca&#39;，&#39;cab&#39;，&#39;cba&#39;]
```
</details>


### stripHTMLTags

从字符串中删除HTML / XML标签.

使用正则表达式从字符串中删除HTML / XML标记.

```js
const stripHTMLTags = str =&gt; str.replace（/ &lt;[^&gt;] *&gt; / g，&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 stripHTMLTags（&#39; <p>  <em>Lorem</em> <strong>存有</strong> </p>  “）;  // &#39;Lorem存有&#39;
```
</details>


### toCamelCase

将字符串转换为驼峰式.

将字符串分解为单词，然后使用正则表达式将它们组合为每个单词的首字母大写.

```js
const toCamelCase = str =&gt; {
  令s =
    str &amp;&amp;
    海峡
      .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | \ b）| [AZ] [az] + [0-9] * | [AZ] | [0-9] + / g）
      .map（x =&gt; x.slice（0，1）.toUpperCase（）+ x.slice（1）.toLowerCase（））
      .加入（&#39;&#39;）;
  返回s.slice（0，1）.toLowerCase（）+ s.slice（1）;
};
```

<details>
<summary>Examples</summary>

```js
 toCamelCase（&#39;some_database_field_name&#39;）;  //&#39;someDatabaseFieldName&#39;
 toCamelCase（&#39;一些需要骆驼化的标签&#39;）;  //&#39;someLabelThatNeedsToBeCamelized&#39;
 toCamelCase（&#39;some-javascript-property&#39;）;  //&#39;someJavascriptProperty&#39;
 toCamelCase（&#39;some-mixed_string带spaces_underscores和连字符&#39;）;  //&#39;someMixedStringWithSpacesUnderscoresAndHyphens&#39;
```
</details>


### toKebabCase

将字符串转换为烤肉串大小写.

将字符串分解为单词，并使用正则表达式将它们加起来以分隔符“-”组合起来.

```js
const toKebabCase = str =&gt;
  str &amp;&amp;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | \ b）| [AZ] [az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.toLowerCase（））
    .加入（&#39;-&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toKebabCase（&#39;camelCase&#39;）;  // &#39;骆驼香烟盒&#39;
 toKebabCase（&#39;some text&#39;）;  //&#39;some-text&#39;
 toKebabCase（&#39;some-mixed_string带空格和下划线和连字符&#39;）;  //&#39;一些混合字符串与空格下划线和连字符&#39;
 toKebabCase（&#39;AllThe-small Things&#39;）;  // “所有的小事情”
 toKebabCase（&#39;IAmListeningToFMWhileLoadingDifferentURLOnMyBrowserAndAlsoEditingSomeXMLAndHTML&#39;）;  //“我在浏览器同时加载不同的URL时浏览我的fm，并且还在编辑xml和HTML”
```
</details>


### toSnakeCase

将字符串转换为蛇形.

将字符串分解为单词，并使用正则表达式将它们加起来以分隔符_分隔.

```js
const toSnakeCase = str =&gt;
  str &amp;&amp;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | \ b）| [AZ] [az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.toLowerCase（））
    .加入（&#39;_&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toSnakeCase（&#39;camelCase&#39;）;  // &#39;骆驼香烟盒&#39;
 toSnakeCase（&#39;some text&#39;）;  //&#39;some_text&#39;
 toSnakeCase（&#39;some-mixed_string带空格和下划线和连字符&#39;）;  //&#39;some_mixed_string_with_spaces_underscores_and_hyphens&#39;
 toSnakeCase（&#39;所有的小东西&#39;）;  //“ all_the_smal_things”
 toSnakeCase（&#39;IAmListeningToFMWhileLoadingDifferentURLOnMyBrowserAndAlsoEditingSomeXMLAndHTML&#39;）;  //“ i_am_listening_to_fm_while_loading_different_url_on_my_browser_and_also_editing_some_xml_and_html”
```
</details>


### toTitleCase

将字符串转换为首字母大写.

使用正则表达式将字符串分成单词，然后将它们组合成大写每个单词的第一个字母，并在它们之间添加空格.

```js
const toTitleCase = str =&gt;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | \ b）| [AZ] [az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.charAt（0）.toUpperCase（）+ x.slice（1））
    .join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toTitleCase（&#39;some_database_field_name&#39;）;  //&#39;某些数据库字段名称&#39;
 toTitleCase（&#39;某些标签需要加上标题大小写&#39;）;  //&#39;需要加上标题大小写的某些标签&#39;
 toTitleCase（&#39;some-package-name&#39;）;  //&#39;Some Package Name&#39;
 toTitleCase（&#39;带有spaces_underscores和连字符的some-mixed_string&#39;）;  //&#39;一些带有下划线和连字符的混合字符串&#39;
```
</details>


### truncateString

将字符串截断为指定长度.

确定字符串的“长度”是否大于“ num”.
返回截断为所需长度的字符串，并在末尾附加“&#39;...”或原始字符串.

```js
const truncateString =（str，num）=&gt;
   str.length&gt;当然？  str.slice（0，是否&gt; 3 NUM  -  3 NUM）+ &#39;...&#39;：STR;
```

<details>
<summary>Examples</summary>

```js
 truncateString（&#39;boomerang&#39;，7）;  //&#39;Boom ...&#39;
```
</details>


### unescapeHTML

转义转义的HTML字符.

将String.prototype.replace（）与正则表达式配合使用，该正则表达式与需要取消转义的字符匹配，并使用回调函数使用字典（对象）将每个转义的字符实例与其关联的未转义的字符替换.

```js
const unescapeHTML = str =&gt;
  str.replace（
    /&amp;|&lt;|&gt;|&#39;|&quot;/g,
    标签=&gt;
      ({
        &#39;＆&#39;：&#39;＆&#39;，
        &#39;&lt;&#39;：&#39;&lt;&#39;，
        &#39;&gt;&#39;：&#39;&gt;&#39;，
        '&#39;': "'",
        &#39;“&#39;：&#39;”&#39;
       } [天] ||  标签）
  );
```

<details>
<summary>Examples</summary>

```js
unescapeHTML('&lt;a href=&quot;#&quot;&gt;Me &amp; you&lt;/a&gt;'); // '<a href="#">Me & you</a>'
```
</details>



将所有给定的URL段连接在一起，然后标准化结果URL.

使用`String.prototype.join（&#39;/&#39;）`组合URL段，然后使用各种正则表达式对一系列`String.prototype.replace（）`进行调用以标准化结果URL（删除双斜杠，为协议添加适当的斜杠） ，在参数前删除斜线，将参数与“&#39;＆&#39;`组合在一起并规范化第一个参数定界符）.

```js
const URLJoin =（... args）=&gt;
  args
    .加入（&#39;/&#39;）
    .replace（/ [\ /] + / g，&#39;/&#39;）
    .replace（/^(.+):\//，&#39;$ 1：//&#39;）
    .replace（/ ^ file：/，&#39;file：/&#39;）
    .replace(/\/(\?|&|#[^!])/g, '$1')
    .replace（/ \？/ g，&#39;＆&#39;）
    .replace（&#39;＆&#39;，&#39;？&#39;）;
```

<details>
<summary>Examples</summary>

```js
 URLJoin（&#39;http://www.google.com&#39;，&#39;a&#39;，&#39;/ b / cd&#39;，&#39;？foo = 123&#39;，&#39;？bar = foo&#39;）;  //&#39;http://www.google.com/a/b/cd?foo=123&amp;bar=foo&#39;
```
</details>


### words

将给定的字符串转换为单词数组.

 使用带有提供的模式的String.prototype.split（）（默认为非alpha的正则表达式）来转换为字符串数组.  使用Array.prototype.filter（）删除所有空字符串.
省略第二个参数以使用默认的regexp.

```js
const words =（str，pattern = / [^ a-zA-Z-] + /）=&gt; str.split（pattern）.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 words（&#39;我爱javaScript !!&#39;）;  // [“ I”，“ love”，“ javaScript”]
 单词（&#39;python，javaScript和coffee&#39;）;  // [“ python”，“ javaScript”，“ coffee”]
```
</details>


---

## 📃 Type


### getType

返回值的本机类型.

返回值的小写构造函数名称，如果值是`undefined`或`null`，则返回“ undefined”或“ null”.

```js
const getType = v =&gt;
   v ===未定义？  &#39;未定义&#39;：v === null？  &#39;null&#39;：v.constructor.name.toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 getType（new Set（[1,2,3]））;  //&#39;设置&#39;
```
</details>


### is

检查提供的值是否为指定的类型.

使用Array.prototype.includes（）确保该值不是undefined或null，然后将该值的constructor属性与type进行比较，以检查提供的值是否为指定的type. .

```js
const是=（type，val）=&gt;！[，null] .includes（val）&amp;&amp; val.constructor === type;
```

<details>
<summary>Examples</summary>

```js
 is（Array，[1]）;  //正确
 is（ArrayBuffer，new ArrayBuffer（））;  //正确
is(Map, new Map()); // true
 is（RegExp，/./g）;  //正确
 is（Set，new Set（））;  //正确
 is（WeakMap，new WeakMap（））;  //正确
 is（WeakSet，new WeakSet（））;  //正确
 is（String，&#39;&#39;）;  //正确
 is（String，new String（&#39;&#39;））;  //正确
 is（Number，1）;  //正确
 is（Number，新的Number（1））;  //正确
 is（Boolean，true）;  //正确
 is（Boolean，new Boolean（true））;  //正确
```
</details>


### isArrayLike

检查所提供的参数是否类似于数组（即可迭代）.

检查所提供的参数是否不是null，并且其Symbol.iterator属性是否为函数.

```js
const isArrayLike = obj =&gt; obj！= null &amp;&amp; typeof obj [Symbol.iterator] ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
 isArrayLike（document.querySelectorAll（&#39;.className&#39;））;  //正确
 isArrayLike（&#39;abc&#39;）;  //正确
 isArrayLike（null）;  //错误
```
</details>


### isBoolean

检查给定参数是否为本地布尔元素.

使用`typeof`来检查一个值是否被归类为布尔型原语.

```js
const isBoolean = val =&gt; typeof val ===&#39;boolean&#39;;
```

<details>
<summary>Examples</summary>

```js
 isBoolean（null）;  //错误
 isBoolean（false）;  //正确
```
</details>


### isEmpty

如果a值是一个空对象，集合，没有可枚举的属性或任何不视为集合的类型，则返回true.

检查提供的值是否为“ null”或其“ length”是否等于“ 0”.

```js
 const isEmpty = val =&gt; val == null ||  ！（Object.keys（val）|| val）.length;
```

<details>
<summary>Examples</summary>

```js
 是空的（[]）;  //正确
 是空的（{}）;  //正确
 是空的（&#39;&#39;）;  //正确
 isEmpty（[1，2]）;  //错误
 isEmpty（{a：1，b：2}）;  //错误
 isEmpty（&#39;text&#39;）;  //错误
 isEmpty（123）;  // true-类型不视为集合
 isEmpty（true）;  // true-类型不视为集合
```
</details>


### isFunction

检查给定参数是否为函数.

使用`typeof`来检查一个值是否被归类为函数原语.

```js
const isFunction = val =&gt; typeof val ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
 isFunction（&#39;x&#39;）;  //错误
 isFunction（x =&gt; x）;  //正确
```
</details>


### isNil

如果指定值为null或undefined，则返回true，否则返回false.

使用严格相等运算符检查value和val的值是否等于null或undefined.

```js
 const isNil = val =&gt; val === undefined ||  val === null;
```

<details>
<summary>Examples</summary>

```js
 isNil（null）;  //正确
 isNil（undefined）;  //正确
```
</details>


### isNull

如果指定的值为null，则返回true，否则返回false.

使用严格相等运算符检查value和val的值是否等于null.

```js
const isNull = val =&gt; val === null;
```

<details>
<summary>Examples</summary>

```js
 isNull（null）;  //正确
```
</details>


### isNumber

检查给定的参数是否为数字.

使用`typeof`来检查一个值是否被归类为数字原语. 
为了防范“ NaN”，请检查“ val === val”（因为“ NaN”的“ typeof”等于“ number”，并且是唯一不等于其自身的值）.

```js
const isNumber = val => typeof val === 'number' && val === val;
```

<details>
<summary>Examples</summary>

```js
 isNumber（1）;  //正确
 isNumber（&#39;1&#39;）;  //错误
 isNumber（NaN）;  //错误
```
</details>


### isObject

返回一个布尔值，确定传递的值是否是一个对象.

使用Object构造函数为给定值创建对象包装. 
 如果值为“ null”或“ undefined”，则创建并返回一个空对象.  另外，返回与给定值对应的类型的对象.

```js
const isObject = obj =&gt; obj === Object（obj）;
```

<details>
<summary>Examples</summary>

```js
 isObject（[1,2,3,4]）;  //正确
 isObject（[]）;  //正确
 isObject（[&#39;Hello！&#39;]）;  //正确
 isObject（{a：1}）;  //正确
 isObject（{}）;  //正确
 isObject（true）;  //错误
```
</details>


### isObjectLike

检查值是否类似于对象.

检查所提供的值是否不是&#39;null&#39;，并且其&#39;typeof&#39;是否等于&#39;object&#39;.

```js
const isObjectLike = val =&gt; val！== null &amp;&amp; typeof val ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
 isObjectLike（{}）;  //正确
 isObjectLike（[1,2,3]）;  //正确
 isObjectLike（x =&gt; x）;  //错误
 isObjectLike（null）;  //错误
```
</details>


### isPlainObject

检查提供的值是否是由Object构造函数创建的对象.

检查提供的值是否正确，使用`typeof`检查它是否是一个对象，并使用&#39;Object.constructor&#39;确保构造函数等于`Object`.

```js
const isPlainObject = val =&gt; !! val &amp;&amp; typeof val ===&#39;object&#39;&amp;&amp; val.constructor === Object;
```

<details>
<summary>Examples</summary>

```js
 isPlainObject（{a：1}）;  //正确
 isPlainObject（new Map（））;  //错误
```
</details>


### isPrimitive

返回一个布尔值，确定所传递的值是否为原始值.

从“ val”中创建一个对象，并将其与“ val”进行比较，以确定所传递的值是否为原始值（即不等于创建的对象）.

```js
const isPrimitive = val =&gt; Object（val）！== val;
```

<details>
<summary>Examples</summary>

```js
 isPrimitive（null）;  //正确
 isPrimitive（50）;  //正确
 isPrimitive（&#39;Hello！&#39;）;  //正确
 isPrimitive（false）;  //正确
 isPrimitive（Symbol（））;  //正确
 isPrimitive（[]）;  //错误
```
</details>


### isPromiseLike

如果一个对象看起来像一个对象，则返回“ true”. [`Promise`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)，否则为false.

检查对象是否不是“ null”，其“ typeof”是否匹配“ object”或“ function”，以及是否具有“ .then”属性，该属性也是“ function”.

```js
const isPromiseLike = obj =&gt;
  obj！== null &amp;&amp;
  （typeof obj ===&#39;object&#39;|| typeof obj ===&#39;function&#39;）&amp;&amp;
  typeof obj.then ===&#39;功能&#39;;
```

<details>
<summary>Examples</summary>

```js
isPromiseLike({
  然后：function（）{
    返回&#39;&#39;;
  }
 }）;  //正确
 isPromiseLike（NULL）;  //错误
 isPromiseLike（{}）;  //错误
```
</details>


### isString

 检查给定参数是否为字符串.  仅适用于字符串基元.

使用`typeof`来检查一个值是否被归类为字符串基元.

```js
const isString = val =&gt; typeof val ===&#39;字符串&#39;;
```

<details>
<summary>Examples</summary>

```js
 isString（&#39;10&#39;）;  //正确
```
</details>


### isSymbol

检查给定的参数是否为符号.

使用`typeof`来检查一个值是否被归类为符号原语.

```js
const isSymbol = val =&gt; typeof val ===&#39;符号&#39;;
```

<details>
<summary>Examples</summary>

```js
 isSymbol（Symbol（&#39;x&#39;））;  //正确
```
</details>


### isUndefined

如果指定的值是undefined，则返回true，否则返回false.

使用严格相等运算符检查value和val的值是否等于undefined.

```js
const isUndefined = val =&gt; val === undefined;
```

<details>
<summary>Examples</summary>

```js
 isUndefined（未定义）;  //正确
```
</details>


### isValidJSON

检查提供的字符串是否为有效的JSON.

使用`JSON.parse（）`和`try ... catch`块检查提供的字符串是否为有效的JSON.

```js
const isValidJSON = str =&gt; {
  尝试{
    JSON.parse（str）;
    返回true；
  }抓住（e）{
    返回false；
  }
};
```

<details>
<summary>Examples</summary>

```js
 isValidJSON（&#39;{“ name”：“ Adam”，“ age”：20}&#39;）;  //正确
 isValidJSON（&#39;{“ name”：“ Adam”，age：“ 20”}&#39;）;  //错误
 isValidJSON（null）;  //正确
```
</details>


---

## 🔧 Utility


### castArray

如果提供的值不是一个，则将其强制转换为数组.

使用Array.prototype.isArray（）确定val是一个数组，然后将其原样返回或封装在数组中.

```js
const castArray = val =&gt;（Array.isArray（val）？val：[val]）;
```

<details>
<summary>Examples</summary>

```js
 castArray（&#39;foo&#39;）;  // [&#39;foo&#39;]
 castArray（[1]）;  // [1]
```
</details>


### cloneRegExp

克隆正则表达式.

使用`new RegExp（）`，`RegExp.source`和`RegExp.flags`克隆给定的正则表达式.

```js
const cloneRegExp = regExp =&gt;新的RegExp（regExp.source，regExp.flags）;
```

<details>
<summary>Examples</summary>

```js
正则表达式=常数/ Lorem存有/ GI;
 regExp2 =常数cloneRegExp（正则表达式）;  // / Lorem存有/ GI
```
</details>


### coalesce

返回第一个非null / undefined参数.

使用Array.prototype.find（）返回第一个非null / undefined参数.

```js
const coalesce =（... args）=&gt; args.find（_ =&gt;！[undefined，null] .includes（_））;
```

<details>
<summary>Examples</summary>

```js
 coalesce（null，undefined，``，NaN，&#39;Waldo&#39;）;  //“”
```
</details>


### coalesceFactory

返回一个自定义的合并函数，该函数返回从提供的参数验证函数返回“ true”的第一个参数.

使用Array.prototype.find（）返回第一个从提供的参数验证函数返回true的参数.

```js
const coalesceFactory =有效=&gt;（... args）=&gt; args.find（有效）;
```

<details>
<summary>Examples</summary>

```js
const customCoalesce = coalesceFactory（_ =&gt;！[null，undefined，``，NaN] .includes（_））;
 customCoalesce（undefined，null，NaN，``，&#39;Waldo&#39;）;  //“ Waldo”
```
</details>


### extendHex

将3位颜色代码扩展为6位颜色代码.

使用Array.prototype.map（），String.prototype.split（）和Array.prototype.join（）连接映射的数组，以将3位RGB表示的十六进制颜色代码转换为6数字形式.
`Array.prototype.slice()` is used to remove `#` from string start since it's added once.

```js
constextendHex = shortHex =&gt;
  '#' +
  shortHex
    .slice(shortHex.startsWith('#') ? 1 : 0)
    .分裂（&#39;&#39;）
    .map（x =&gt; x + x）
    .加入（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
extendHex('#03f'); // '#0033ff'
extendHex('05a'); // '#0055aa'
```
</details>


### getURLParameters

返回一个包含当前URL参数的对象.

使用带有适当正则表达式的String.match（）获取所有键值对，Array.prototype.reduce（）映射并将它们组合为单个对象.
将location.search作为参数传递给当前的URL.

```js
const getURLParameters = url =&gt;
  （url.match（/（[[^？=＆] +）（=（[^＆] *））/ g）|| []）.reduce（
    （a，v）=&gt;（（（a [v.slice（0，v.indexOf（&#39;=&#39;））]] = v.slice（v.indexOf（&#39;=&#39;）+ 1）），
    {}
  );
```

<details>
<summary>Examples</summary>

```js
 getURLParameters（&#39;http://url.com/page?name=Adam&amp;surname=Smith&#39;）;  // {名称：“ Adam”，姓氏：“ Smith”}
 getURLParameters（&#39;google.com&#39;）;  // {}
```
</details>



如果提供了alpha值，则将颜色代码转换为rgb（）或rgba（）字符串.

Use bitwise right-shift operator and mask bits with `&` (and) operator to convert a hexadecimal color code (with or without prefixed with `#`) to a string with the RGB values. If it's 3-digit color code, first convert to 6-digit version. If an alpha value is provided alongside 6-digit hex, give `rgba()` string in return.

```js
const hexToRGB = hex =&gt; {
  令alpha = false，
    h = hex.slice(hex.startsWith('#') ? 1 : 0);
  if（h.length === 3）h = [... h] .map（x =&gt; x + x）.join（&#39;&#39;）;
  否则（h.length === 8）alpha = true;
  h = parseInt（h，16）;
  返回（
    &#39;rgb&#39;+
    （alpha？&#39;a&#39;：&#39;&#39;）+
    '(' +
    （h &gt;&gt;&gt;（alpha？24:16））+
    ', ' +
    （（h＆（alpha？0x00ff0000：0x00ff00））&gt;&gt;&gt;（alphaα16：8））+
    ', ' +
    （（h＆（alpha？0x0000ff00：0x0000ff））&gt;&gt;&gt;（alpha alpha 8：0））+
    （alpha？`，$ {h＆0x000000ff}`：&#39;&#39;）+
    ')'
  );
};
```

<details>
<summary>Examples</summary>

```js
hexToRGB('#27ae60ff'); // 'rgba(39, 174, 96, 255)'
 hexToRGB（&#39;27ae60&#39;）;  //&#39;rgb（39，174，96）&#39;
hexToRGB('#fff'); // 'rgb(255, 255, 255)'
```
</details>


### httpGet

对传递的URL进行“ GET”请求.

Use [`XMLHttpRequest`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) Web api向给定的“ url”发出“ get”请求.
通过将给定的“回调”称为“ responseText”来处理“ onload”事件.
通过运行提供的`err`函数来处理&#39;onerror&#39;事件.
省略第三个参数“ err”，默认情况下将错误记录到控制台的“ error”流中.

```js
const httpGet =（URL，回调，err = console.error）=&gt; {
  const request = new XMLHttpRequest（）;
  request.open（&#39;GET&#39;，url，true）;
  request.onload =（）=&gt; callback（request.responseText）;
  request.onerror =（）=&gt; err（请求）;
  request.send（）;
};
```

<details>
<summary>Examples</summary>

```js
httpGet(
  'https://jsonplaceholder.typicode.com/posts/1',
  console.log
); /*
日志：{
  “ userId”：1
  “ id”：1
  “标题”：“提供或拒绝盲目，欢迎找到选项”
  “身体”：“它需要\ nsuscipit遵循\ nreprehenderit不适可能是这种情况发生的事情的整个\ nnostrum轻易接受的是，他们都非常”
}
*/
```
</details>


### httpPost

向传递的URL发出POST请求.

Use [`XMLHttpRequest`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) Web api向给定的url发出post请求.
使用setRequestHeader方法设置HTTP请求标头的值.
通过将给定的“回调”称为“ responseText”来处理“ onload”事件.
通过运行提供的`err`函数来处理&#39;onerror&#39;事件.
省略第三个参数“ data”，以不将任何数据发送到提供的“ url”.
省略第四个参数“ err”，默认情况下会将错误记录到控制台的“ error”流中.

```js
const httpPost =（网址，数据，回调，err = console.error）=&gt; {
  const request = new XMLHttpRequest（）;
  request.open（&#39;POST&#39;，url，true）;
  request.setRequestHeader（&#39;Content-type&#39;，&#39;application / json; charset = utf-8&#39;）;
  request.onload =（）=&gt; callback（request.responseText）;
  request.onerror =（）=&gt; err（请求）;
  request.send（data）;
};
```

<details>
<summary>Examples</summary>

```js
const newPost = {
  userId：1
  id：1337，
  标题：“ Foo”，
  正文：“ bar bar bar”
};
const data = JSON.stringify（newPost）;
httpPost(
  'https://jsonplaceholder.typicode.com/posts',
  数据，
  console.log
); /*
日志：{
  “ userId”：1
  “ id”：1337，
  “ title”：“ Foo”，
  “ body”：“ bar bar bar”
}
*/
httpPost(
  'https://jsonplaceholder.typicode.com/posts',
  null，//不发送正文
  console.log
); /*
日志：{
  “ id”：101
}
*/
```
</details>


### isBrowser

确定当前运行时环境是否是浏览器，以便前端模块可以在服务器（节点）上运行而不会引发错误.

在window和document的typeof值上使用Array.prototype.includes（）（全局变量通常仅在浏览器环境中可用，除非明确定义它们），如果其中之一被返回，则将返回true.它们是未定义的.
使用typeof可以检查全局变量是否存在，而不会抛出ReferenceError.
如果它们都不都是未定义的，则假定当前环境为浏览器.

```js
const isBrowser =（）=&gt;！[typeof window，typeof document] .includes（&#39;undefined&#39;）;
```

<details>
<summary>Examples</summary>

```js
 isBrowser（）;  // true（浏览器）
 isBrowser（）;  // false（节点）
```
</details>


### mostPerformant

返回执行最快的函数数组中的函数索引.

 使用Array.prototype.map（）生成一个数组，其中每个值都是在迭代之后执行该函数所花费的总时间.  使用前后的performance.now（）值中的差异来获得以毫秒为单位的总时间，以达到较高的准确性.
使用`Math.min（）`查找最短执行时间，并返回最短时间的索引，该索引对应于性能最高的函数的索引.
 省略第二个参数“迭代”，以使用默认的10,000次迭代.  迭代次数越多，结果越可靠，但花费的时间也越长.

```js
const mostPerformant =（fns，迭代= 10000）=&gt; {
  const times = fns.map（fn =&gt; {
    const before = performance.now（）;
    for（让i = 0; i &lt;迭代; i ++）fn（）;
    返回performance.now（）-之前；
  });
  返回times.indexOf（Math.min（... times））;
};
```

<details>
<summary>Examples</summary>

```js
mostPerformant([
  () => {
    //循环遍历整个数组，然后返回`false`
    [1、2、3、4、5、6、7、8、9，&#39;10&#39;].every（el =&gt; typeof el ===&#39;number&#39;）;
  },
  () => {
    //在返回false之前只需要达到索引“ 1”
    [1，&#39;2&#39;，3，4，5，6，7，8，8，9，10] .every（el =&gt; typeof el ===&#39;number&#39;）;
  }
]); // 1
```
</details>


### nthArg

 创建一个将参数从索引n处获取的函数.  如果n为负，则返回末尾的第n个参数.

使用Array.prototype.slice（）在索引n处获取所需的参数.

```js
const nthArg = n =&gt;（... args）=&gt; args.slice（n）[0];
```

<details>
<summary>Examples</summary>

```js
const third = nthArg（2）;
 第三（1,2,3）;  // 3
 第三（1，2）;  //未定义
const last = nthArg（-1）;
 last（1,2,3,4,5）;  // 5
```
</details>


### objectToQueryString

返回从给定对象的键值对生成的查询字符串.

Use `Array.prototype.reduce()` on `Object.entries(queryParameters)` to create the query string.
根据`index`确定&#39;symbol&#39;为`？`或`＆`，仅当它是字符串时，将val链接到queryString.
当queryParameters为假时，返回queryString或一个空字符串.

```js
const objectToQueryString = queryParameters =&gt; {
  返回queryParameters
     ？  Object.entries（queryParameters）.reduce（（queryString，[key，val]，index）=&gt; {
         const符号=索引=== 0？  &#39;？&#39;  ：&#39;＆&#39;;
         queryString + = typeof val ===&#39;字符串&#39;  `$ {symbol} $ {key} = $ {val}`：&#39;&#39;;
        返回queryString;
      }, '')
    : '';
};
```

<details>
<summary>Examples</summary>

```js
 objectToQueryString（{page：&#39;1&#39;，size：&#39;2kg&#39;，key：undefined}）;  //&#39;？page = 1＆size = 2kg&#39;
```
</details>


### parseCookie

解析HTTP Cookie标头字符串，并返回所有cookie名称-值对的对象.

使用`String.prototype.split（&#39;;&#39;）`来分隔键值对.
使用“ Array.prototype.map（）”和“ String.prototype.split（&#39;=&#39;）`将键与每对值分开.
使用Array.prototype.reduce（）和decodeURIComponent（）创建具有所有键值对的对象.

```js
const parseCookie = str =&gt;
  海峡
    .分裂（&#39;;&#39;）
    .map（v =&gt; v.split（&#39;=&#39;））
    .reduce（（acc，v）=&gt; {
      acc [decodeURIComponent（v [0] .trim（））] = encodeURIComponent（v [1] .trim（））;
      返回acc；
    }, {});
```

<details>
<summary>Examples</summary>

```js
 parseCookie（&#39;foo = bar; equation = E％3Dmc％5E2&#39;）;  // {foo：&#39;bar&#39;，equation：&#39;E = mc ^ 2&#39;}
```
</details>



将以字节为单位的数字转换为人类可读的字符串.

根据指数使用要访问的单位的数组字典.
使用Number.toPrecision（）将数字截断为一定位数.
考虑到提供的选项以及是否为负，通过构建返回的字符串.
忽略第二个参数`precision`以使用默认精度`3` digits.
省略第三个参数“ addSpace”，默认情况下在数字和单位之间添加空格.

```js
const prettyBytes =（num，precision = 3，addSpace = true）=&gt; {
  const UNITS = [&#39;B&#39;，&#39;KB&#39;，&#39;MB&#39;，&#39;GB&#39;，&#39;TB&#39;，&#39;PB&#39;，&#39;EB&#39;，&#39;ZB&#39;，&#39;YB&#39;]；
  如果（Math.abs（num）&lt;1）返回num +（addSpace？&#39;&#39;：））+ UNITS [0];
  const exponent = Math.min（Math.floor（Math.log10（num &lt;0？-num：num）/ 3），UNITS.length-1）;
  const n = Number（（（（num &lt;0？-num：num）/ 1000 **指数）.toPrecision（precision））;
  返回（？NUM &lt;0 &#39; - &#39;： &#39;&#39;）+ N +（？addSpace &#39;&#39;： &#39;&#39;）+单元[露出];
};
```

<details>
<summary>Examples</summary>

```js
 prettyBytes（1000）;  //“ 1 KB”
 prettyBytes（-27145424323.5821，5）;  //“ -27.145 GB”
 prettyBytes（123456789，3，false）;  //“ 123MB”
```
</details>


### randomHexColorCode

生成随机的十六进制颜色代码.

 使用Math.random生成一个随机的24位（6x4bits）十六进制数.  使用位移，然后使用`toString（16）`将其转换为十六进制字符串.

```js
const randomHexColorCode =（）=&gt; {
  令n =（Math.random（）* 0xfffff * 1000000）.toString（16）;
  return '#' + n.slice(0, 6);
};
```

<details>
<summary>Examples</summary>

```js
randomHexColorCode(); // "#e34155"
```
</details>


### RGBToHex

将RGB分量的值转换为颜色代码.

使用按位左移运算符（`&lt;&lt;`）和`toString（16）`，然后`String.padStart（6，&#39;0&#39;）`，将给定的RGB参数转换为十六进制字符串，以获取6位十六进制值.

```js
const RGBToHex =（r，g，b）=&gt;（（r &lt;&lt; 16）+（g &lt;&lt; 8）+ b）.toString（16）.padStart（6，&#39;0&#39;）;
```

<details>
<summary>Examples</summary>

```js
 RGBToHex（255，165，1）;  //&#39;ffa501&#39;
```
</details>


### serializeCookie

将Cookie名称/值对序列化为Set-Cookie标头字符串.

使用模板文字和`encodeURIComponent（）`创建适当的字符串.

```js
const serializeCookie =（name，val）=&gt;`$ {encodeURIComponent（name）} = $ {encodeURIComponent（val）}`;
```

<details>
<summary>Examples</summary>

```js
 serializeCookie（&#39;foo&#39;，&#39;bar&#39;）;  //&#39;foo = bar&#39;
```
</details>


### timeTaken

测量函数执行所需的时间.

使用`console.time（）`和`console.timeEnd（）`来测量开始时间和结束时间之间的差，以确定回调执行的时间.

```js
const timeTaken =回调=&gt; {
  console.time（&#39;timeTaken&#39;）;
  const r = callback（）;
  console.timeEnd（&#39;timeTaken&#39;）;
  返回r;
};
```

<details>
<summary>Examples</summary>

```js
 timeTaken（（）=&gt; Math.pow（2，10））;  // 1024，（记录）：timeTaken：0.02099609375ms
```
</details>


### toCurrency

取一个数字并返回指定的货币格式.

使用`Intl.NumberFormat`启用对国家/货币敏感的格式.

```js
const toCurrency =（n，curr，LanguageFormat =未定义）=&gt;
  Intl.NumberFormat（LanguageFormat，{style：&#39;currency&#39;，currency：curr}）.format（n）;
```

<details>
<summary>Examples</summary>

```js
 toCurrency（123456.789，&#39;EUR&#39;）;  //€123,456.79 |  货币：欧元|  currencyLangFormat：本地
 toCurrency（123456.789，&#39;USD&#39;，&#39;en-us&#39;）;  // $ 123,456.79 |  货币：美元|  currencyLangFormat：英文（美国）
 toCurrency（123456.789，&#39;USD&#39;，&#39;fa&#39;）;  //؜$ |  货币：美元|  currencyLangFormat：波斯语
 toCurrency（322342436423.2435，&#39;JPY&#39;）;  //¥322,342,436,423 |  货币：日元|  currencyLangFormat：本地
 toCurrency（322342436423.2435，&#39;JPY&#39;，&#39;fi&#39;）;  // 322342436423¥|  货币：日元|  currencyLangFormat：芬兰语
```
</details>


### toDecimalMark

使用`toLocaleString（）`将浮点运算转换为 [Decimal mark](https://en.wikipedia.org/wiki/Decimal_mark)  形成.  它使数字与逗号分隔的字符串.

```js
const toDecimalMark = num =&gt; num.toLocaleString（&#39;en-US&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toDecimalMark（12305030388.9087）;  //“ 12,305,030,388.909”
```
</details>


### toOrdinalSuffix

在数字后添加序数后缀.

使用模运算符（`％`）查找一位和十位数的值.
查找匹配的序号数字.
如果在青少年模式中找到数字，请使用青少年序数.

```js
const toOrdinalSuffix = num =&gt; {
  const int的= parseInt函数（NUM）;
    位数= [整数％10，整数％100]，
    序数= [&#39;st&#39;，&#39;nd&#39;，&#39;rd&#39;，&#39;th&#39;]，
    oPattern = [1,2,3,4]，
    tPattern = [11、12、13、14、15、16、17、18、19]；
  返回oPattern.includes（digits [0]）&amp;&amp;！tPattern.includes（digits [1]）
     ？  int +常规[数字[0]-1]
    ：int +平凡[3];
};
```

<details>
<summary>Examples</summary>

```js
 toOrdinalSuffix（&#39;123&#39;）;  //“ 123rd”
```
</details>


### validateNumber

如果给定值是数字，则返回“ true”，否则返回“ false”.

将`！isNaN（）`与`parseFloat（）`结合使用以检查参数是否为数字.
使用`isFinite（）`检查数字是否有限.
使用Number（）检查强制是否成立.

```js
const validateNumber = n =&gt;！isNaN（parseFloat（n））&amp;&amp; isFinite（n）&amp;&amp; Number（n）== n;
```

<details>
<summary>Examples</summary>

```js
 validateNumber（&#39;10&#39;）;  //正确
```
</details>


### yesNo

如果字符串是`y` /`yes`，则返回`true`；如果字符串是`n` /`no`，则返回false.

使用RegExp.test（）检查字符串是否为y / yes或n / no.
省略第二个参数“ def”，将默认答案设置为“ no”.

```js
const yesNo =（val，def = false）=&gt;
   / ^（y |是）$ / i.test（val）吗？  true：/ ^（n | no）$ / i.test（val）吗？  false：def;
```

<details>
<summary>Examples</summary>

```js
 是的否（&#39;Y&#39;）;  //正确
 是的否（&#39;是&#39;）;  //正确
 yesNo（&#39;否&#39;）;  //错误
 yesNo（&#39;Foo&#39;，true）;  //正确
```
</details>


## Collaborators

| [<img src="https://raw.githubusercontent.com/Chalarangelo.png" width="100px;"/>](https://raw.githubusercontent.com/Chalarangelo)<br/> [<sub>Angelos Chalaris</sub>](https://raw.githubusercontent.com/Chalarangelo) | [<img src="https://raw.githubusercontent.com/flxwu.png" width="100px;"/>](https://raw.githubusercontent.com/flxwu)<br/> [<sub>Felix Wu</sub>](https://raw.githubusercontent.com/Pl4gue) | [<img src="https://raw.githubusercontent.com/fejes713.png" width="100px;"/>](https://raw.githubusercontent.com/fejes713)<br/> [<sub>Stefan Feješ</sub>](https://raw.githubusercontent.com/fejes713)  | [<img src="https://raw.githubusercontent.com/kingdavidmartins.png" width="100px;"/>](https://raw.githubusercontent.com/kingdavidmartins)<br/> [<sub>King David Martins</sub>](https://raw.githubusercontent.com/iamsoorena) | [<img src="https://raw.githubusercontent.com/iamsoorena.png" width="100px;"/>](https://raw.githubusercontent.com/iamsoorena)<br/> [<sub>Soorena Soleimani</sub>](https://raw.githubusercontent.com/iamsoorena) |
| --- | --- | --- | --- | --- |
| [<img src="https://raw.githubusercontent.com/elderhsouza.png" width="100px;"/>](https://raw.githubusercontent.com/elderhsouza)<br/> [<sub>Elder Henrique Souza</sub>](https://raw.githubusercontent.com/elderhsouza) | [<img src="https://raw.githubusercontent.com/skatcat31.png" width="100px;"/>](https://raw.githubusercontent.com/skatcat31)<br/> [<sub>Robert Mennell</sub>](https://raw.githubusercontent.com/skatcat31) | [<img src="https://raw.githubusercontent.com/atomiks.png" width="100px;"/>](https://raw.githubusercontent.com/atomiks)<br/> [<sub>atomiks</sub>](https://raw.githubusercontent.com/atomiks)  |


## Credits

*标志由 [Angelos Chalaris](https://github.com/Chalarangelo) 根据 [MIT](https://opensource.org/licenses/MIT) 执照.*
*本自述文件使用 [markdown-builder](https://github.com/30-seconds/markdown-builder).*
