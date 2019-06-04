<div class="github-widget" data-repo="30-seconds/30-seconds-of-code"></div>
[![Logo](https://raw.githubusercontent.com/30-seconds/30-seconds-of-code/master//logo.png)](https://30secondsofcode.org/)

## 30 seconds of code

[![License](https://img.shields.io/badge/license-CC0--1.0-blue.svg)](https://github.com/30-seconds/30-seconds-of-code/blob/master/LICENSE) [![npm Downloads](https://img.shields.io/npm/dt/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code) [![npm Version](https://img.shields.io/npm/v/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code) [![Known Vulnerabilities](https://snyk.io/test/github/30-seconds/30-seconds-of-code/badge.svg?targetFile=package.json)](https://snyk.io/test/github/30-seconds/30-seconds-of-code?targetFile=package.json) <br/> 
[![Travis Build](https://travis-ci.com/30-seconds/30-seconds-of-code.svg?branch=master)](https://travis-ci.com/30-seconds/30-seconds-of-code) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/6ab7791fb1ea40b4a576d658fb96807f)](https://www.codacy.com/app/Chalarangelo/30-seconds-of-code?utm_source=github.com&utm_medium=referral&utm_content=30-seconds/30-seconds-of-code&utm_campaign=Badge_Grade) [![js-semistandard-style](https://img.shields.io/badge/code%20style-semistandard-brightgreen.svg)](https://github.com/Flet/semistandard) <br/>
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![ProductHunt](https://img.shields.io/badge/producthunt-vote-orange.svg)](https://www.producthunt.com/posts/30-seconds-of-code) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

&gt;精选的有用JavaScript代码段集合，您可以在30秒或更短的时间内理解这些代码段.

[![Sponsored by DigitalOcean](https://raw.githubusercontent.com/30-seconds/30-seconds-of-code/master//sponsored_by_DigitalOcean.png)](https://www.digitalocean.com)

*使用<kbd>Ctrl</kbd> + <kbd>F</kbd>或<kbd>命令</kbd> + <kbd>F</kbd>搜索片段.
*欢迎提供，请阅读 [contribution guide](https://github.com/30-seconds/30-seconds-of-code/blob/master/CONTRIBUTING.md).
*片段是用ES6编写的，使用 [Babel transpiler](https://babeljs.io/) 确保向后兼容性.
*您可以按照找到的说明将这些片段导入VSCode [here](https://github.com/30-seconds/30-seconds-of-code/tree/master/vscode_snippets).
*您可以使用CLI中的CLI应用程序从终端搜索，查看和复制这些代码段 [this repo](https://github.com/sQVe/30s).
*如果您想在社交媒体上关注30秒的代码，您可以找到我们 [Facebook](https://www.facebook.com/30secondsofcode), [Instagram](https://www.instagram.com/30secondsofcode) 和 [Twitter](https://twitter.com/30secondsofcode).

#### Related projects

* [30 Seconds of CSS](https://30-seconds.github.io/30-seconds-of-css/)
* [30 Seconds of Interviews](https://30secondsofinterviews.org/)
* [30 Seconds of React](https://github.com/30-seconds/30-seconds-of-react)
* [30 Seconds of Python](https://github.com/kriadmin/30-seconds-of-python-code) _（非官方）_
* [30 Seconds of PHP](https://github.com/appzcoder/30-seconds-of-php-code) _（非官方）_
* [30 Seconds of Kotlin](https://github.com/IvanMwiruki/30-seconds-of-kotlin) _（非官方）_
* [30 Seconds of Knowledge](https://chrome.google.com/webstore/detail/30-seconds-of-knowledge/mmgplondnjekobonklacmemikcnhklla) _（非官方）_

#### Package

⚠️**注意：**我们的一些代码片段尚未针对生产进行优化（请参阅单个代码段问题的免责声明）.

您可以找到包含所有代码段的包 [npm](https://www.npmjs.com/package/30-seconds-of-code).

```bash
## With npm
npm安装30秒的代码

## With yarn
纱线添加30秒的代码
```

[CDN link](https://unpkg.com/30-seconds-of-code/)

<details>
<summary>Details</summary>

**Browser**

```html
<script src="https://unpkg.com/30-seconds-of-code@1/dist/_30s.es5.min.js"></script>
<script>
  _30s.average（1,2,3）;
</script>
```

**Node**

```js
// CommonJS
const _30s = require（&#39;30 -sconds-of-code&#39;）;
_30s.average（1,2,3）;

// ES模块
从&#39;30 -sconds-of-code&#39;导入_30s;
_30s.average（1,2,3）;
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

创建一个接受最多`n`参数的函数，忽略任何其他参数.

使用`Array.prototype.slice（0，n）`和扩展运算符（`...`）调用提供的函数`fn`，最多为`n`参数.

```js
const ary =（fn，n）=&gt;（... args）=&gt; fn（... args.slice（0，n））;
```

<details>
<summary>Examples</summary>

```js
const firstTwoMax = ary（Math.max，2）;
 [[2,6，&#39;a&#39;]，[8,4,6]，[10]].map（x =&gt; firstTwoMax（... x））;  // [6,8,10]
```

</details>


### call

 给定一个键和一组参数，在给定上下文时调用它们.  主要用于组合物.

使用闭包来调用存储的参数的存储键.

```js
const call =（key，https：//github.com/30-seconds/30-seconds-of-code/blob/master/...args）=&gt; context =&gt; context[key](https://github.com/30-seconds/30-seconds-of-code/blob/master/...args);
```

<details>
<summary>Examples</summary>

```js
Promise.resolve（[1,2,3]）
  .then（call（&#39;map&#39;，x =&gt; 2 * x））
   .然后（的console.log）;  // [2,4,6]
const map = call.bind（null，&#39;map&#39;）;
Promise.resolve（[1,2,3]）
  .then（map（x =&gt; 2 * x））
   .然后（的console.log）;  // [2,4,6]
```

</details>


### collectInto

将接受数组的函数更改为可变参数函数.

给定一个函数，返回一个闭包，它将所有输入收集到一个接受数组的函数中.

```js
const collectInto = fn =&gt;（... args）=&gt; fn（args）;
```

<details>
<summary>Examples</summary>

```js
const Pall = collectInto（Promise.all.bind（Promise））;
让p1 = Promise.resolve（1）;
让p2 = Promise.resolve（2）;
让p3 = new Promise（resolve =&gt; setTimeout（resolve，2000,3））;
 颇尔（p1，p2，p3）.then（console.log）;  // [1,2,3]（大约2秒后）
```

</details>


### flip

Flip将函数作为参数，然后将第一个参数作为最后一个参数.

返回一个接受可变输入的闭包，并拼接最后一个参数，使其成为应用其余参数之前的第一个参数.

```js
const flip = fn =&gt;（首先，......休息）=&gt; fn（...休息，第一次）;
```

<details>
<summary>Examples</summary>

```js
让a = {name：&#39;John Smith&#39;};
让b = {};
const mergeFrom = flip（Object.assign）;
let mergePerson = mergeFrom.bind（null，a）;
 mergePerson（b）中;  // == b
b = {};
 Object.assign（b，a）;  // == b
```

</details>


### over

创建一个函数，该函数使用它接收的参数调用每个提供的函数并返回结果.

使用`Array.prototype.map（）`和`Function.prototype.apply（）`将每个函数应用于给定的参数.

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

创建一个函数，通过转换参数调用提供的函数.

使用`Array.prototype.map（）`将`transforms`与`args`结合使用扩展运算符（`...`），将转换后的参数传递给`fn`.

```js
const overArgs =（fn，transforms）=&gt;（... args）=&gt; fn（... args.map（（https://github.com/30-seconds/30-seconds-of-code/blob/ master / val，i）=&gt;变换[i](https://github.com/30-seconds/30-seconds-of-code/blob/master/val)));
```

<details>
<summary>Examples</summary>

```js
const square = n =&gt; n * n;
const double = n =&gt; n * 2;
const fn = overArgs（（x，y）=&gt; [x，y]，[square，double]）;
 fn（9,3）;  // [81,6]
```

</details>


### pipeAsyncFunctions

为异步函数执行从左到右的函数组合.

使用`Array.prototype.reduce（）`和spread运算符（```）使用`Promise.then（）`执行从左到右的函数组合.
这些函数可以返回以下组合：简单值，“Promise”，或者它们可以定义为通过`await`返回的`async`.
所有功能必须是一元的.

```js
const pipeAsyncFunctions =（... fns）=&gt; arg =&gt; fns.reduce（（p，f）=&gt; p.then（f），Promise.resolve（arg））;
```

<details>
<summary>Examples</summary>

```js
const sum = pipeAsyncFunctions（
  x =&gt; x + 1，
  x =&gt;新Promise（resolve =&gt; setTimeout（（）=&gt; resolve（x + 2），1000）），
  x =&gt; x + 3，
  async x =&gt;（等待x）+ 4
);
（async（）=&gt; {
   console.log（等待sum（5））;  // 15（一秒钟后）
})();
```

</details>


### pipeFunctions

执行从左到右的功能组合.

使用带有扩展运算符（`...`）的`Array.prototype.reduce（）`来执行从左到右的函数组合.
 第一个（最左边）函数可以接受一个或多个参数;  其余的功能必须是一元的.

```js
const pipeFunctions =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; g（f（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add5 = x =&gt; x + 5;
const multiply =（x，y）=&gt; x * y;
const multiplyAndAdd5 = pipeFunctions（multiply，add5）;
 multiplyAndAdd5（5,2）;  // 15
```

</details>


### promisify

转换异步函数以返回promise.

使用currying返回一个函数，返回一个调用原始函数的`Promise`.
使用`... rest`运算符传入所有参数.

*在Node 8+中，您可以使用 [`util.promisify`](https://nodejs.org/api/util.html#util_util_promisify_original)*

```js
const promisify = func =&gt;（... args）=&gt;
  新的承诺（（解决，拒绝）=&gt;
    func（... args，（err，result）=&gt;（错误？拒绝（错误）：解决（结果）））
  );
```

<details>
<summary>Examples</summary>

```js
const delay = promisify（（d，cb）=&gt; setTimeout（cb，d））;
 延迟（2000）.then（（）=&gt; console.log（&#39;嗨！&#39;））;  // //承诺在2秒后解决
```

</details>


### rearg

创建一个函数，该函数调用提供的函数，其参数根据指定的索引排列.

使用`Array.prototype.map（）`基于`indices`结合扩展运算符（`...`）重新排序参数，将转换后的参数传递给`fn`.

```js
const rearg =（fn，indexes）=&gt;（... args）=&gt; fn（... indexes.map（i =&gt; args [i]））;
```

<details>
<summary>Examples</summary>

```js
被重启=后方（
  function（a，b，c）{
    返回[a，b，c];
  },
  [2, 0, 1]
);
 后退（&#39;b&#39;，&#39;c&#39;，&#39;a&#39;）;  // [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
```

</details>


### spreadOver

采用可变参数函数并返回一个闭包，该闭包接受一个参数数组以映射到函数的输入.

使用闭包和扩展运算符（`...`）将参数数组映射到函数的输入.

```js
const spreadOver = fn =&gt; argsArr =&gt; fn（... argsArr）;
```

<details>
<summary>Examples</summary>

```js
const arrayMax = spreadOver(Math.max);
 arrayMax（[1,2,3]）;  // 3
```

</details>


### unary

创建一个最多接受一个参数的函数，忽略任何其他参数.

调用提供的函数`fn`，只给出第一个参数.

```js
const unary = fn =&gt; val =&gt; fn（val）;
```

<details>
<summary>Examples</summary>

```js
 [&#39;6&#39;，&#39;8&#39;，&#39;10&#39;].map（一元（parseInt））;  // [6,8,10]
```

</details>



---

## 📚 Array

### all

如果提供的谓词函数为集合中的所有元素返回“true”，则返回“true”，否则返回“false”.

使用`Array.prototype.every（）`来测试集合中的所有元素是否基于`fn`返回`true`.
省略第二个参数`fn`，使用`Boolean`作为默认值.

```js
const all =（arr，fn = Boolean）=&gt; arr.every（fn）;
```

<details>
<summary>Examples</summary>

```js
 全部（[4,2,3]，x =&gt; x&gt; 1）;  //真
 全部（[1,2,3]）;  //真
```

</details>


### allEqual

检查数组中的所有元素是否相等.

使用`Array.prototype.every（）`来检查数组的所有元素是否与第一个元素相同.
使用严格比较运算符比较数组中的元素，该运算符不考虑“NaN”自我不等式.

```js
const allEqual = arr =&gt; arr.every（val =&gt; val === arr [0]）;
```

<details>
<summary>Examples</summary>

```js
 allEqual（[1,2,3,4,5,6]）;  //假
 allEqual（[1,1,1,1]）;  //真
```

</details>


### any

如果提供的谓词函数为集合中的至少一个元素返回“true”，则返回“true”，否则返回“false”.

使用`Array.prototype.some（）`来测试集合中的任何元素是否基于`fn`返回`true`.
省略第二个参数`fn`，使用`Boolean`作为默认值.

```js
const any =（arr，fn = Boolean）=&gt; arr.some（fn）;
```

<details>
<summary>Examples</summary>

```js
 any（[0,1,2,0]，x =&gt; x&gt; = 2）;  //真
 任何（[0,0,1,0]）;  //真
```

</details>


### arrayToCSV

将2D数组转换为逗号分隔值（CSV）字符串.

使用`Array.prototype.map（）`和`Array.prototype.join（delimiter）`将各个1D数组（行）组合成字符串.
使用`Array.prototype.join（&#39;\ n&#39;）`将所有行组合成CSV字符串，用换行符分隔每一行.
省略第二个参数`delimiter`，使用`，`的默认分隔符.

```js
const arrayToCSV =（arr，delimiter =&#39;，&#39;）=&gt;
  ARR
    .map（v =&gt; v.map（x =&gt;（isNaN（x）？`“$ {x.replace（/”/ g，&#39;“”&#39;）}“`：x））.join（delimiter））
    .加入（ &#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
 arrayToCSV（[[&#39;a&#39;，&#39;b&#39;]，[&#39;c&#39;，&#39;d&#39;]]）;  //&#39;“a”，“b”\ n“c”，“d”&#39;
 arrayToCSV（[[&#39;a&#39;，&#39;b&#39;]，[&#39;c&#39;，&#39;d&#39;]]，&#39;;&#39;）;  //&#39;“a”;“b”\ n“c”;“d”&#39;
 arrayToCSV（[[&#39;a&#39;，&#39;“b”great&#39;]，[&#39;c&#39;，3.1415]]）;  //&#39;“a”，“”“b”“great”\ n“c”，3.1415&#39;
```

</details>


### bifurcate

 将值拆分为两组.  如果`filter`中的元素是真实的，则集合中的对应元素属于第一组;  否则，它属于第二组.

使用`Array.prototype.reduce（）`和`Array.prototype.push（）`基于`filter`向组添加元素.

```js
const bifurcate =（arr，filter）=&gt;
  arr.reduce（（acc，val，i）=&gt;（acc [filter [i]？0：1] .push（val），acc），[[]，[]]）;
```

<details>
<summary>Examples</summary>

```js
 bifurcate（[&#39;beep&#39;，&#39;boop&#39;，&#39;foo&#39;，&#39;bar&#39;]，[true，true，false，true]）;  // [[&#39;beep&#39;，&#39;boop&#39;，&#39;bar&#39;]，[&#39;foo&#39;]]
```

</details>


### bifurcateBy

 根据谓词函数将值拆分为两个组，谓词函数指定输入集合中的元素属于哪个组.  如果谓词函数返回truthy值，则collection元素属于第一个组;  否则，它属于第二组.

使用`Array.prototype.reduce（）`和`Array.prototype.push（）`根据`fn`为每个元素返回的值向组添加元素.

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

将数组块化为指定大小的较小数组.

使用`Array.from（）`创建一个新数组，它适合将要生成的块数.
使用`Array.prototype.slice（）`将新数组的每个元素映射到一个长度为`size`的块.
如果原始数组无法均匀分割，则最终的块将包含其余元素.

```js
const chunk =（arr，size）=&gt;
  Array.from（{length：Math.ceil（arr.length / size）}，（v，i）=&gt;
    arr.slice(i * size, i * size + size)
  );
```

<details>
<summary>Examples</summary>

```js
 块（[1,2,3,4,5]，2）;  // [[1,2]，[3,4]，[5]]
```

</details>


### compact

从数组中删除falsey值.

使用`Array.prototype.filter（）`来过滤掉虚假值（`false`，`null`，`0`，````，`undefined`和`NaN`）.

```js
const compact = arr =&gt; arr.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 紧凑的（[0,1，假，2，&#39;&#39;，3，&#39;a&#39;，&#39;e&#39;* 23，NaN，&#39;s&#39;，34]）;  // [1,2,3，&#39;a&#39;，&#39;s&#39;，34]
```

</details>


### countBy

根据给定的函数对数组的元素进行分组，并返回每个组中元素的数量.

使用`Array.prototype.map（）`将数组的值映射到函数或属性名称.
使用`Array.prototype.reduce（）`创建一个对象，其中的键是从映射的结果中生成的.

```js
const countBy = (arr, fn) =>
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val）=&gt; {
    acc [val] =（acc [val] || 0）+ 1;
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
 countBy（[6.1,4.2,6.3]，Math.floor）;  // {4：1,6：2}
 countBy（[&#39;one&#39;，&#39;two&#39;，&#39;three&#39;]，&#39;length&#39;）;  // {3：2,5：1}
```

</details>


### countOccurrences

计算数组中值的出现次数.

每次遇到数组中的特定值时，使用`Array.prototype.reduce（）`递增计数器.

```js
const countOccurrences =（arr，val）=&gt; arr.reduce（（a，v）=&gt;（v === val？a + 1：a），0）;
```

<details>
<summary>Examples</summary>

```js
 countOccurrences（[1,1,2,1,2,3]，1）;  // 3
```

</details>


### deepFlatten

深度展平阵列.

使用递归.
使用带有空数组（`[]`）的`Array.prototype.concat（）`和扩展运算符（`...`）来展平数组.
递归地展平作为数组的每个元素.

```js
const deepFlatten = arr =&gt; [] .concat（... arr.map（v =&gt;（Array.isArray（v）？deepFlatten（v）：v）））;
```

<details>
<summary>Examples</summary>

```js
 deepflat（[1，[2]，[[3]，4]，5]）;  // [1,2,3,4,5]
```

</details>


### difference

返回两个数组之间的差异.

从`b`创建一个`Set`，然后在`a`上使用`Array.prototype.filter（）`来保留不包含在`b`中的值.

```js
const差异=（a，b）=&gt; {
  const s = new Set（b）;
  return a.filter（x =&gt;！s.has（x））;
};
```

<details>
<summary>Examples</summary>

```js
 差异（[1,2,3]，[1,2,4]）;  // [3]
```

</details>


### differenceBy

将提供的函数应用于两个数组的每个数组元素后，返回两个数组之间的差异.

通过将`fn`应用于`b`中的每个元素来创建`Set`，然后使用`Array.prototype.map（）`将`fn`应用于`a`中的每个元素，然后应用`Array.prototype.filter（ ）`

```js
const differenceBy =（a，b，fn）=&gt; {
  const s = new Set（b.map（fn））;
  返回a.map（fn）.filter（=&gt;！s.has（el））;
};
```

<details>
<summary>Examples</summary>

```js
 differenceBy（[2.1,1.2]，[2.3,3.4]，Math.floor）;  // [1]
 differenceBy（[{x：2}，{x：1}]，[{x：1}]，v =&gt; vx）;  // [2]
```

</details>


### differenceWith

过滤掉比较器函数未返回“true”的数组中的所有值.

使用`Array.prototype.filter（）`和`Array.prototype.findIndex（）`来查找适当的值.

```js
const differenceWith =（arr，val，comp）=&gt; arr.filter（a =&gt; val.findIndex（b =&gt; comp（a，b））=== -1）;
```

<details>
<summary>Examples</summary>

```js
differenceWith([1, 1.2, 1.5, 3, 0], [1.9, 3, 0], (a, b) => Math.round(a) === Math.round(b)); // [1, 1.2]
```

</details>


### drop

返回一个从左侧删除了`n`个元素的新数组.

使用`Array.prototype.slice（）`从左边删除指定数量的元素.

```js
const drop =（arr，n = 1）=&gt; arr.slice（n）;
```

<details>
<summary>Examples</summary>

```js
 掉落（[1,2,3]）;  // [2,3]
 掉落（[1,2,3]，2）;  // [3]
 掉落（[1,2,3]，42）;  // []
```

</details>


### dropRight

返回一个从右侧删除了`n`个元素的新数组.

使用`Array.prototype.slice（）`从右边删除指定数量的元素.

```js
const dropRight =（arr，n = 1）=&gt; arr.slice（0，-n）;
```

<details>
<summary>Examples</summary>

```js
 dropRight（[1,2,3]）;  // [1,2]
 dropRight（[1,2,3]，2）;  // [1]
 dropRight（[1,2,3]，42）;  // []
```

</details>


### dropRightWhile

 从数组末尾删除元素，直到传递的函数返回“true”.  返回数组中的其余元素.

循环遍历数组，使用`Array.prototype.slice（）`删除数组的最后一个元素，直到函数返回的值为“true”.
返回剩余的元素.

```js
const dropRightWhile =（arr，func）=&gt; {
  let rightIndex = arr.length;
  while（rightIndex-- &amp;&amp;！func（arr [rightIndex]））;
  return arr.slice（0，rightIndex + 1）;
};
```

<details>
<summary>Examples</summary>

```js
 dropRightWhile（[1,2,3,4]，n =&gt; n &lt;3）;  // [1,2]
```

</details>


### dropWhile

 删除数组中的元素，直到传递的函数返回“true”.  返回数组中的其余元素.

循环遍历数组，使用`Array.prototype.slice（）`删除数组的第一个元素，直到函数返回的值为“true”.
返回剩余的元素.

```js
const dropWhile =（arr，func）=&gt; {
  while（arr.length&gt; 0 &amp;&amp;！func（arr [0]））arr = arr.slice（1）;
  返回
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

使用`Array.prototype.filter（）`创建一个包含给定数组的每个第n个元素的新数组.

```js
const everyNth =（arr，nth）=&gt; arr.filter（（e，i）=&gt; i％nth === nth  -  1）;
```

<details>
<summary>Examples</summary>

```js
 everyNth（[1,2,3,4,5,6]，2）;  // [2,4,6]
```

</details>


### filterFalsy

过滤掉数组中的虚假值.

使用`Array.prototype.filter（）`来获取一个只包含truthy值的数组.

```js
const filterFalsy = arr =&gt; arr.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 filterFalsy（[&#39;&#39;，true，{}，false，&#39;sample&#39;，1,0]）;  // [true，{}，&#39;sample&#39;，1]
```

</details>


### filterNonUnique

过滤掉数组中的非唯一值.

使用`Array.prototype.filter（）`表示只包含唯一值的数组.

```js
const filterNonUnique = arr =&gt; arr.filter（i =&gt; arr.indexOf（i）=== arr.lastIndexOf（i））;
```

<details>
<summary>Examples</summary>

```js
 filterNonUnique（[1,2,2,3,4,4,5]）;  // [1,3,5]
```

</details>


### filterNonUniqueBy

根据提供的比较器函数筛选出数组中的非唯一值.

使用`Array.prototype.filter（）`和`Array.prototype.every（）`作为一个只包含唯一值的数组，基于比较器函数`fn`.
比较器函数有四个参数：被比较的两个元素的值及其索引.

```js
const filterNonUniqueBy =（arr，fn）=&gt;
  arr.filter（（v，i）=&gt; arr.every（（x，j）=&gt;（i === j）=== fn（v，x，i，j）））;
```

<details>
<summary>Examples</summary>

```js
filterNonUniqueBy(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，价值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，价值：&#39;d&#39;}，
    {id：0，价值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{id：2，value：&#39;c&#39;}]
```

</details>


### findLast

返回提供的函数返回truthy值的最后一个元素.

使用`Array.prototype.filter（）`删除`fn`返回falsey值的元素，&#39;Array.prototype.pop（）`来获取最后一个.

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

返回提供的函数返回truthy值的最后一个元素的索引.

使用`Array.prototype.map（）`将每个元素映射到具有索引和值的数组.
使用`Array.prototype.filter（）`删除`fn`返回falsey值的元素，&#39;Array.prototype.pop（）`来获取最后一个.

```js
const findLastIndex =（arr，fn）=&gt;
  ARR
    .map（（val，i）=&gt; [i，val]）
    .filter（（[i，val]）=&gt; fn（val，i，arr））
    .pop（）[0];
```

<details>
<summary>Examples</summary>

```js
 findLastIndex（[1,2,3,4]，n =&gt; n％2 === 1）;  // 2（值3的索引）
```

</details>


### flatten

将数组展平到指定的深度.

使用递归，每个深度级别将“深度”递减1.
使用`Array.prototype.reduce（）`和`Array.prototype.concat（）`来合并元素或数组.
基本情况，对于`deep`等于`1`停止递归.
省略第二个参数，“深度”仅展平为“1”的深度（单个展平）.

```js
const flatten =（arr，depth = 1）=&gt;
  arr.reduce（（a，v）=&gt; a.concat（depth&gt; 1 &amp;&amp; Array.isArray（v）？flatten（v，depth  -  1）：v），[]）;
```

<details>
<summary>Examples</summary>

```js
 展平（[1，[2]，3,4]）;  // [1,2,3,4]
 压扁（[1，[2，[3，[4,5]，6]，7]，8]，2）;  // [1,2,3，[4,5]，6,7,8]
```

</details>


### forEachRight

从数组的最后一个元素开始，为每个数组元素执行一次提供的函数.

使用`Array.prototype.slice（0）`来克隆给定的数组，使用`Array.prototype.reverse（）`来反转它，使用`Array.prototype.forEach（）`迭代反转的数组.

```js
const forEachRight =（arr，callback）=&gt;
  ARR
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

使用`Array.prototype.map（）`将数组的值映射到函数或属性名称.
使用`Array.prototype.reduce（）`创建一个对象，其中的键是从映射的结果中生成的.

```js
const groupBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val，i）=&gt; {
    acc [val] =（acc [val] || []）.concat（arr [i]）;
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
 groupBy（[6.1,4.2,6.3]，Math.floor）;  // {4：[4.2]，6：[6.1,6.3]}
 groupBy（[&#39;one&#39;，&#39;two&#39;，&#39;three&#39;]，&#39;length&#39;）;  // {3：[&#39;one&#39;，&#39;two&#39;]，5：[&#39;three&#39;]}
```

</details>


### head

返回列表的头部.

使用`arr [0]`返回传递数组的第一个元素.

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

返回数组中`val`的所有索引.
如果`val`永远不会发生，则返回`[]`.

使用`Array.prototype.reduce（）`循环元素并存储匹配元素的索引.
返回索引数组.

```js
const indexOfAll =（arr，val）=&gt; arr.reduce（（acc，el，i）=&gt;（el === val？[... acc，i]：acc），[]）;
```

<details>
<summary>Examples</summary>

```js
 indexOfA11（[1,2,3,1,2,3]，1）;  // [0,3]
 indexOfA11（[1,2,3]，4）;  // []
```

</details>


### initial

返回除最后一个数组之外的数组的所有元素.

使用`arr.slice（0，-1）`返回除数组的最后一个元素之外的所有元素.

```js
const initial = arr =&gt; arr.slice（0，-1）;
```

<details>
<summary>Examples</summary>

```js
 初始（[1,2,3]）;  // [1,2]
```

</details>


### initialize2DArray

初始化给定宽度和高度以及值的2D数组.

 使用`Array.prototype.map（）`生成h行，其中每行都是一个大小为w的新数组，用value初始化.  如果未提供该值，则默认为“null”.

```js
const initialize2DArray =（w，h，val = null）=&gt;
  Array.from（{length：h}）.map（（）=&gt; Array.from（{length：w}）.fill（val））;
```

<details>
<summary>Examples</summary>

```js
 initialize2DArray（2,2,0）;  // [[0,0]，[0,0]]
```

</details>


### initializeArrayWithRange

初始化一个数组，其中包含指定范围内的数字，其中`start`和`end`包含它们的公共差异`step`.

使用`Array.from（）`创建一个所需长度的数组，`（end  -  start + 1）/ step`，以及一个map函数，用给定范围内的所需值填充它.
你可以省略`start`来使用默认值`0`.
你可以省略`step`来使用默认值`1`.

```js
const initializeArrayWithRange =（end，start = 0，step = 1）=&gt;
  Array.from（{length：Math.ceil（（end  -  start + 1）/ step）}，（v，i）=&gt; i * step + start）;
```

<details>
<summary>Examples</summary>

```js
 initializeArrayWithRange（5）;  // [0,1,2,3,4,5]
 initializeArrayWithRange（7,3）;  // [3,4,5,6,7]
 initializeArrayWithRange（9,0,2）;  // [0,2,4,6,8]
```

</details>


### initializeArrayWithRangeRight

初始化一个数组，其中包含指定范围内的数字（反向），其中`start`和`end`包含它们的公共差值`step`.

使用`Array.from（Math.ceil（（end + 1-start）/ step））`来创建一个所需长度的数组（元素的数量等于`（end-start）/ step`或`（ end + 1-start）/ step` for inclusive end），`Array.prototype.map（）`用于填充范围内的所需值.
你可以省略`start`来使用默认值`0`.
你可以省略`step`来使用默认值`1`.

```js
const initializeArrayWithRangeRight =（end，start = 0，step = 1）=&gt;
  Array.from（{length：Math.ceil（（end + 1  -  start）/ step）}）.map（
    （v，i，arr）=&gt;（arr.length  -  i  -  1）* step + start
  );
```

<details>
<summary>Examples</summary>

```js
 initializeArrayWithRangeRight（5）;  // [5,4,3,2,1,0]
 initializeArrayWithRangeRight（7,3）;  // [7,6,5,4,3]
 initializeArrayWithRangeRight（9,0,2）;  // [8,6,4,2,0]
```

</details>


### initializeArrayWithValues

使用指定的值初始化并填充数组.

使用`Array（n）`创建一个所需长度的数组，`fill（v）`用所需的值填充它.
你可以省略`val`来使用默认值`0`.

```js
const initializeArrayWithValues =（n，val = 0）=&gt; Array（n）.fill（val）;
```

<details>
<summary>Examples</summary>

```js
 initializeArrayWithValues（5,2）;  // [2,2,2,2,2]
```

</details>


### initializeNDArray

创建具有给定值的n维数组.

使用递归.
使用`Array.prototype.map（）`生成行，其中每个行都是使用`initializeNDArray`初始化的新数组.

```js
const initializeNDArray =（val，... args）=&gt;
  args.length === 0
     ？  ^ h
    ：Array.from（{length：args [0]}）.map（（）=&gt; initializeNDArray（val，... args.slice（1）））;
```

<details>
<summary>Examples</summary>

```js
 initializeNDArray（1,3）;  // [1,1,1]
 initializeNDArray（5,2,2,2）;  // [[[5,5]，[5,5]]，[[5,5]，[5,5]]]
```

</details>


### intersection

Returns a list of elements that exist in both arrays.

从`b`创建一个`Set`，然后在`a`上使用`Array.prototype.filter（）`来保存`b`中包含的值.

```js
const intersection =（a，b）=&gt; {
  const s = new Set（b）;
  return a.filter（x =&gt; s.has（x））;
};
```

<details>
<summary>Examples</summary>

```js
 交叉点（[1,2,3]，[4,3,2]）;  // [2,3]
```

</details>


### intersectionBy

在将提供的函数应用于两个数组的每个数组元素之后，返回两个数组中存在的元素列表.

通过将`fn`应用于`b`中的所有元素来创建`Set`，然后在`a`上使用`Array.prototype.filter（）`来仅保留元素，当`fn`时，它生成`b`中包含的值适用于他们.

```js
const intersectionBy =（a，b，fn）=&gt; {
  const s = new Set（b.map（fn））;
  return a.filter（x =&gt; s.has（fn（x）））;
};
```

<details>
<summary>Examples</summary>

```js
 intersectionBy（[2.1,1.2]，[2.3,3.4]，Math.floor）;  // [2.1]
```

</details>


### intersectionWith

使用提供的比较器函数返回两个数组中存在的元素列表.

使用`Array.prototype.filter（）`和`Array.prototype.findIndex（）`结合提供的比较器来确定交叉值.

```js
const intersectionWith =（a，b，comp）=&gt; a.filter（x =&gt; b.findIndex（y =&gt; comp（x，y））！== -1）;
```

<details>
<summary>Examples</summary>

```js
 intersectionWith（[1,1.2,1.5,3,0]，[1.9,3,0,3.9]，（a，b）=&gt; Math.round（a）=== Math.round（b））;  // [1.5,3,0]
```

</details>


### isSorted

如果数组按升序排序，则返回“1”;如果按降序排序，则返回“-1”;如果未排序，则返回“0”.

计算前两个元素的排序“方向”.
使用`Object.entries（）`循环遍历数组对象并成对比较它们.
如果`direction`改变则返回&#39;0`或如果到达最后一个元素则返回`direction`.

```js
isSorted常量= ARR =&gt; {
  let direction =  - （arr [0]  -  arr [1]）;
  for（let [i，val] of arr.entries（））{
     方向=！方向？   - （arr [i  -  1]  -  arr [i]）：方向;
     if（i === arr.length  -  1）返回！方向？  0：方向;
    否则if（（val  -  arr [i + 1]）* direction&gt; 0）返回0;
  }
};
```

<details>
<summary>Examples</summary>

```js
 isSorted（[0，1，2，2]）;  // 1
 isSorted（[4，3，2]）;  // -1
isSorted([4, 3, 5]); // 0
```

</details>


### join

将数组的所有元素连接成一个字符串并返回该字符串.
使用分隔符和结束分隔符.

使用`Array.prototype.reduce（）`将元素组合成一个字符串.
省略第二个参数`separator`，使用`&#39;，&#39;`的默认分隔符.
省略第三个参数`end`，默认使用与`separator`相同的值.

```js
const join =（arr，separator =&#39;，&#39;，end = separator）=&gt;
  arr.reduce（
    （acc，val，i）=&gt;
      我=== arr.length  -  2
         ？  acc + val + end
        ：i === arr.length  -  1
           ？  acc + val
          ：acc + val + separator，
    ''
  );
```

<details>
<summary>Examples</summary>

```js
 加入（[&#39;pen&#39;，&#39;pineapple&#39;，&#39;apple&#39;，&#39;pen&#39;]，&#39;，&#39;，&#39;＆&#39;）;  //“笔，菠萝，苹果和笔”
 加入（[&#39;pen&#39;，&#39;菠萝&#39;，&#39;苹果&#39;，&#39;笔&#39;]，&#39;，&#39;）;  //“笔，菠萝，苹果，笔”
 加入（[&#39;pen&#39;，&#39;菠萝&#39;，&#39;苹果&#39;，&#39;笔&#39;]）;  //“笔，菠萝，苹果，笔”
```

</details>



将对象数组转换为逗号分隔值（CSV）字符串，该字符串仅包含指定的`columns`.

使用`Array.prototype.join（delimiter）`组合`columns`中的所有名称来创建第一行.
使用`Array.prototype.map（）`和`Array.prototype.reduce（）`为每个对象创建一个行，用空字符串替换不存在的值，只用`columns`映射值.
使用`Array.prototype.join（&#39;\ n&#39;）`将所有行组合成一个字符串.
省略第三个参数`delimiter`，使用`，`的默认分隔符.

```js
const JSONtoCSV =（arr，columns，delimiter =&#39;，&#39;）=&gt;
  [
    columns.join（定界符），
    ... arr.map（obj =&gt;
      columns.reduce（
         （acc，key）=&gt;`$ {acc} $ {！acc.length？  &#39;&#39;：delimiter}“$ {！obj [key]？&#39;&#39;：obj [key]}”`，
        ''
      )
    )
  ].加入（ &#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
 JSONtoCSV（[{a：1，b：2}，{a：3，b：4，c：5}，{a：6}，{b：7}]，[&#39;a&#39;，&#39;b&#39;]） ;  //&#39;a，b \ n“1”，“2”\ n“3”，“4”\ n“6”，“”\ n“”，“7”&#39;
 JSONtoCSV（[{a：1，b：2}，{a：3，b：4，c：5}，{a：6}，{b：7}]，[&#39;a&#39;，&#39;b&#39;]， &#39;;&#39;）;  //&#39;a; b \ n“1”;“2”\ n“3”;“4”\ n“6”;“”\ n“”;“7”&#39;
```

</details>


### last

返回数组中的最后一个元素.

使用`arr.length  -  1`计算给定数组的最后一个元素的索引并返回它.

```js
const last = arr =&gt; arr [arr.length  -  1];
```

<details>
<summary>Examples</summary>

```js
 最后（[1,2,3]）;  // 3
```

</details>


### longestItem

获取具有`length`属性的任意数量的可迭代对象或对象，并返回最长的对象或对象.
如果多个对象具有相同的长度，则将返回第一个对象.
如果没有提供参数，则返回`undefined`.

使用`Array.prototype.reduce（）`，比较对象的`length`以找到最长的对象.

```js
const longestItem =（... vals）=&gt; vals.reduce（（a，x）=&gt;（x.length&gt; a.length？x：a））;
```

<details>
<summary>Examples</summary>

```js
 longestItem（&#39;this&#39;，&#39;is&#39;，&#39;a&#39;，&#39;testcase&#39;）;  // &#39;测试用例&#39;
 longestItem（... [&#39;a&#39;，&#39;ab&#39;，&#39;abc&#39;]）;  //&#39;abc&#39;
 longestItem（... [&#39;a&#39;，&#39;ab&#39;，&#39;abc&#39;]，&#39;abcd&#39;）;  // &#39;A B C D&#39;
 longestItem（[1,2,3]，[1,2]，[1,2,3,4,5]）;  // [1,2,3,4,5]
 longestItem（[1,2,3]，&#39;foobar&#39;）;  //&#39;foobar&#39;
```

</details>



使用函数将数组的值映射到对象，其中键 - 值对由原始值作为键和映射值组成.

 使用匿名内部函数作用域来声明未定义的内存空间，使用闭包来存储返回值.  使用一个新的`Array`来存储数组，其中包含函数的数据集，并使用逗号运算符返回第二步，而无需从一个上下文移动到另一个上下文（由于闭包和操作顺序）.

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
 squareIt（[1,2,3]）;  // {1：1,2：4,3：9}
```

</details>


### maxN

返回提供的数组中的`n`最大元素.
如果`n`大于或等于提供的数组长度，则返回原始数组（按降序排序）.

使用`Array.prototype.sort（）`结合扩展运算符（`...`）来创建数组的浅层克隆并按降序排序.
使用`Array.prototype.slice（）`来获取指定数量的元素.
省略第二个参数`n`，得到一个单元素数组.

```js
const maxN =（arr，n = 1）=&gt; [... arr] .sort（（a，b）=&gt; b  -  a）.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 maxN（[1,2,3]）;  // [3]
 maxN（[1,2,3]，2）;  // [3,2]
```

</details>


### minN

从提供的数组中返回`n`最小元素.
如果`n`大于或等于提供的数组长度，则返回原始数组（按升序排序）.

使用`Array.prototype.sort（）`结合扩展运算符（`...`）来创建数组的浅层克隆并按升序对其进行排序.
使用`Array.prototype.slice（）`来获取指定数量的元素.
省略第二个参数`n`，得到一个单元素数组.

```js
const minN =（arr，n = 1）=&gt; [... arr] .sort（（a，b）=&gt; a  -  b）.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 由（[1，2，3]）;  // [1]
 由（[1，2，3]，2）;  // [1,2]
```

</details>


### none

如果提供的谓词函数为集合中的所有元素返回“false”，则返回“true”，否则返回“false”.

使用`Array.prototype.some（）`来测试集合中的任何元素是否基于`fn`返回`true`.
省略第二个参数`fn`，使用`Boolean`作为默认值.

```js
const none =（arr，fn = Boolean）=&gt;！arr.some（fn）;
```

<details>
<summary>Examples</summary>

```js
 无（[0,1,3,0]，x =&gt; x == 2）;  //真
 无（[0,0,0]）;  //真
```

</details>


### nthElement

返回数组的第n个元素.

使用`Array.prototype.slice（）`来获取包含第一个元素的第n个元素的数组.
如果索引超出范围，则返回“undefined”.
省略第二个参数`n`，得到数组的第一个元素.

```js
const nthElement =（arr，n = 0）=&gt;（n === -1？arr.slice（n）：arr.slice（n，n + 1））[0];
```

<details>
<summary>Examples</summary>

```js
 nthElement（[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]，1）;  //&#39;b&#39;
 nthElement（[&#39;a&#39;，&#39;b&#39;，&#39;b&#39;]，-3）;  // &#39;一个&#39;
```

</details>


### offset

将指定数量的元素移动到数组的末尾.

使用`Array.prototype.slice（）`两次来获取指定索引之后的元素以及之前的元素.
使用扩展运算符（`...`）将两者合并为一个数组.
如果`offset`为负数，则元素将从end移动到start.

```js
const offset =（arr，offset）=&gt; [... arr.slice（offset），... arr.slice（0，offset）];
```

<details>
<summary>Examples</summary>

```js
 偏移量（[1,2,3,4,5]，2）;  // [3,4,5,1,2]
 偏移量（[1,2,3,4,5]， -  2）;  // [4,5,1,2,3]
```

</details>


### partition

将元素分组为两个数组，具体取决于所提供的函数对每个元素的真实性.

使用`Array.prototype.reduce（）`创建一个包含两个数组的数组.
使用`Array.prototype.push（）`将`fn`返回&#39;true`的元素添加到第一个数组，将`fn`返回`false`的元素添加到第二个数组.

```js
const partition =（arr，fn）=&gt;
  arr.reduce（
    （acc，val，i，arr）=&gt; {
       acc [fn（val，i，arr）？  0：1] .push（val）;
      返回acc;
    },
    [[], []]
  );
```

<details>
<summary>Examples</summary>

```js
const users = [{user：&#39;barney&#39;，age：36，active：false}，{user：&#39;fred&#39;，age：40，active：true}];
 partition（users，o =&gt; o.active）;  // [[{&#39;user&#39;：&#39;fred&#39;，&#39;age&#39;：40，&#39;active&#39;：true}]，[{&#39;user&#39;：&#39;barney&#39;，&#39;age&#39;：36，&#39;active&#39;：false}] ]
```

</details>



 ⚠️**警告**：此函数的执行时间随每个数组元素呈指数增长.  超过8到10个条目的任何内容都会导致浏览器挂起，因为它会尝试解决所有不同的组合.

生成数组元素的所有排列（包含重复项）.

使用递归.
对于给定数组中的每个元素，为其余元素创建所有部分排列.
使用`Array.prototype.map（）`将元素与每个部分排列组合，然后使用`Array.prototype.reduce（）`来组合一个数组中的所有排列.
基本情况是数组`length`等于&#39;2`或`1`.

```js
const permutations = arr =&gt; {
   if（arr.length &lt;= 2）返回arr.length === 2？  [arr，[arr [1]，arr [0]]]：arr;
  return arr.reduce（
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
 排列（[1,33,5]）;  // [[1,3,3,5]，[1,5,33]，[33,1,5]，[33,5,1]，[5,1,33]，[5,33,1] ]
```

</details>


### pull

改变原始数组以过滤掉指定的值.

使用`Array.prototype.filter（）`和`Array.prototype.includes（）`来提取不需要的值.
使用`Array.prototype.length = 0`来改变传入的数组，方法是将它的长度重置为零，并使用`Array.prototype.push（）`重新填充它，只使用拉取的值.

_(For a snippet that does not mutate the original array see [`without`](#without))_

```js
const pull = (arr, ...args) => {
   让argState = Array.isArray（args [0]）？  args [0]：args;
  let pull = arr.filter（（v，i）=&gt;！argState.includes（v））;
  arr.length = 0;
  pulling.forEach（v =&gt; arr.push（v））;
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;a&#39;，&#39;b&#39;，&#39;c&#39;];
 拉（myArray，&#39;a&#39;，&#39;c&#39;）;  // myArray = [&#39;b&#39;，&#39;b&#39;]
```

</details>



改变原始数组以过滤掉指定索引处的值.

使用`Array.prototype.filter（）`和`Array.prototype.includes（）`来提取不需要的值.
使用`Array.prototype.length = 0`来改变传入的数组，方法是将它的长度重置为零，并使用`Array.prototype.push（）`重新填充它，只使用拉取的值.
使用`Array.prototype.push（）`来跟踪拉出的值

```js
const pullAtIndex = (arr, pullArr) => {
  let removed = [];
  让拉= arr
    .map（（v，i）=&gt;（pullArr.includes（i）？removed.push（v）：v））
    .filter（（v，i）=&gt;！pullArr.includes（i））;
  arr.length = 0;
  pulling.forEach（v =&gt; arr.push（v））;
  退回;
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;d&#39;];
 let pull = pullAtIndex（myArray，[1,3]）;  // myArray = [&#39;a&#39;，&#39;c&#39;]，拉= [&#39;b&#39;，&#39;d&#39;]
```

</details>



 改变原始数组以过滤掉指定的值.  返回已删除的元素.

使用`Array.prototype.filter（）`和`Array.prototype.includes（）`来提取不需要的值.
使用`Array.prototype.length = 0`来改变传入的数组，方法是将它的长度重置为零，并使用`Array.prototype.push（）`重新填充它，只使用拉取的值.
使用`Array.prototype.push（）`来跟踪拉出的值

```js
const pullAtValue =（arr，pullArr）=&gt; {
  let removed = []，
    pushToRemove = arr.forEach（（v，i）=&gt;（pullArr.includes（v）？removed.push（v）：v）），
    mutateTo = arr.filter（（v，i）=&gt;！pullArr.includes（v））;
  arr.length = 0;
  mutateTo.forEach（v =&gt; arr.push（v））;
  退回;
};
```

<details>
<summary>Examples</summary>

```js
让myArray = [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;，&#39;d&#39;];
 let pull = pullAtValue（myArray，[&#39;b&#39;，&#39;d&#39;]）;  // myArray = [&#39;a&#39;，&#39;c&#39;]，拉= [&#39;b&#39;，&#39;d&#39;]
```

</details>



根据给定的迭代器函数，对原始数组进行变换以过滤掉指定的值.

检查函数中是否提供了最后一个参数.
使用`Array.prototype.map（）`将迭代器函数`fn`应用于所有数组元素.
使用`Array.prototype.filter（）`和`Array.prototype.includes（）`来提取不需要的值.
使用`Array.prototype.length = 0`来改变传入的数组，方法是将它的长度重置为零，并使用`Array.prototype.push（）`重新填充它，只使用拉取的值.

```js
const pullBy =（arr，... args）=&gt; {
  const length = args.length;
   让fn =长度&gt; 1？  args [length  -  1]：undefined;
   fn = typeof fn ==&#39;function&#39;？  （args.pop（），fn）：undefined;
  let argState =（Array.isArray（args [0]）？args [0]：args）.map（val =&gt; fn（val））;
  let pull = arr.filter（（v，i）=&gt;！argState.includes（fn（v）））;
  arr.length = 0;
  pulling.forEach（v =&gt; arr.push（v））;
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

根据条件过滤对象数组，同时过滤掉未指定的键.

使用`Array.prototype.filter（）`根据谓词`fn`过滤数组，以便它返回条件返回truthy值的对象.
在过滤的数组上，使用`Array.prototype.map（）`使用`Array.prototype.reduce（）`返回新对象，以过滤掉未作为`keys`参数提供的键.

```js
const reducedFilter =（data，keys，fn）=&gt;
  data.filter（fn）.map（el =&gt;
    keys.reduce（（acc，key）=&gt; {
      acc [key] = el [key];
      返回acc;
    }, {})
  );
```

<details>
<summary>Examples</summary>

```js
const date = [
  {
    id：1，
    名字：&#39;john&#39;，
    年龄：24岁
  },
  {
    id：2，
    名称：&#39;mike&#39;，
    年龄：50岁
  }
];

 reducedFilter（data，[&#39;id&#39;，&#39;name&#39;]，item =&gt; item.age&gt; 24）;  // [{id：2，name：&#39;mike&#39;}]
```

</details>


### reduceSuccessive

对累加器和数组中的每个元素（从左到右）应用函数，返回连续减少的值的数组.

使用`Array.prototype.reduce（）`将给定函数应用于给定数组，存储每个新结果.

```js
const reduceSuccessive =（arr，fn，acc）=&gt;
  arr.reduce（（res，val，i，arr）=&gt;（res.push（fn（res.slice（-1）[0]，val，i，arr）），res），[acc]）;
```

<details>
<summary>Examples</summary>

```js
 reduceSuccessive（[1,2,3,4,5,6]，（acc，val）=&gt; acc + val，0）;  // [0,1,3,6,10,15,21]
```

</details>


### reduceWhich

在应用提供的函数设置比较规则后，返回数组的最小/最大值.

将`Array.prototype.reduce（）`与`comparator`函数结合使用，可以得到数组中的相应元素.
您可以省略第二个参数`comparator`，以使用返回数组中最小元素的默认参数.

```js
const reduceWhich =（arr，comparator =（a，b）=&gt; a  -  b）=&gt;
  arr.reduce（（a，b）=&gt;（比较器（a，b）&gt; = 0？b：a））;
```

<details>
<summary>Examples</summary>

```js
 reduceWhich（[1,3,2]）;  // 1
 reduceWhich（[1,3,2]，（a，b）=&gt; b  -  a）;  // 3
reduceWhich(
  [{name：&#39;Tom&#39;，年龄：12}，{姓名：&#39;杰克&#39;，年龄：18}，{姓名：&#39;露西&#39;，年龄：9}]，
  （a，b）=&gt; a.age  -  b.age
 ）;  // {姓名：“露西”，年龄：9}
```

</details>


### reject

采用谓词和数组，如`Array.prototype.filter（）`，但只保留`x`，如果`pred（x）=== false`.

```js
const reject =（pred，array）=&gt; array.filter（（... args）=&gt;！pred（... args））;
```

<details>
<summary>Examples</summary>

```js
 拒绝（x =&gt; x％2 === 0，[1,2,3,4,5]）;  // [1,3,5]
 拒绝（word =&gt; word.length&gt; 4，[&#39;Apple&#39;，&#39;Pear&#39;，&#39;Kiwi&#39;，&#39;Banana&#39;]）;  // [&#39;梨&#39;，&#39;新西兰&#39;]
```

</details>


### remove

从数组中删除给定函数返回“false”的元素.

使用`Array.prototype.filter（）`查找返回truthy值的数组元素和使用`Array.prototype.splice（）`删除元素的`Array.prototype.reduce（）`.
使用三个参数（`value，index，array`）调用`func`.

```js
const remove =（arr，func）=&gt;
  Array.isArray（ARR）
     ？  arr.filter（func）.reduce（（acc，val）=&gt; {
      arr.splice（arr.indexOf（val），1）;
      return acc.concat（val）;
    }, [])
    : [];
```

<details>
<summary>Examples</summary>

```js
 删除（[1,2,3,4]，n =&gt; n％2 === 0）;  // [2,4]
```

</details>


### sample

从数组中返回一个随机元素.

使用`Math.random（）`生成一个随机数，乘以`length`并使用`Math.floor（）`将其四舍五入到最接近的整数.
此方法也适用于字符串.

```js
const sample = arr =&gt; arr [Math.floor（Math.random（）* arr.length）];
```

<details>
<summary>Examples</summary>

```js
 样本（[3,7,9,11]）;  // 9
```

</details>


### sampleSize

从`array`获取唯一键的`n`随机元素，直到`array`的大小.

使用the来洗牌阵列 [Fisher-Yates algorithm](https://github.com/30-seconds/30-seconds-of-code#shuffle).
使用`Array.prototype.slice（）`来获取第一个`n`元素.
省略第二个参数，`n`从数组中只获取一个随机元素.

```js
const sampleSize =（[... arr]，n = 1）=&gt; {
  设m = arr.length;
  而（m）{
    const i = Math.floor（Math.random（）* m--）;
    [arr [m]，arr [i]] = [arr [i]，arr [m]];
  }
  return arr.slice（0，n）;
};
```

<details>
<summary>Examples</summary>

```js
 sampleSize（[1,2,3]，2）;  // [3,1]
 sampleSize（[1,2,3]，4）;  // [2,3,1]
```

</details>


### shank

具有相同的功能 [`Array.prototype.splice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)，但返回一个新数组而不是改变原始数组.

在删除现有元素和/或添加新元素后，使用`Array.prototype.slice（）`和`Array.prototype.concat（）`获取包含新内容的新数组.
省略第二个参数`index`，从&#39;0&#39;开始.
省略第三个参数`delCount`，删除`0`元素.
省略第四个参数`elements`，以便不添加任何新元素.

```js
const shank =（arr，index = 0，delCount = 0，... elements）=&gt;
  ARR
    .slice（0，index）
    .concat（元素）
    .concat（arr.slice（index + delCount））;
```

<details>
<summary>Examples</summary>

```js
const names = [&#39;alpha&#39;，&#39;bravo&#39;，&#39;charlie&#39;];
 const namesAndDelta = shank（名称，1,0，&#39;delta&#39;）;  // [&#39;alpha&#39;，&#39;delta&#39;，&#39;bravo&#39;，&#39;charlie&#39;]
 const namesNoBravo = shank（名称，1,1）;  // [&#39;alpha&#39;，&#39;charlie&#39;]
 的console.log（名称）;  // [&#39;alpha&#39;，&#39;bravo&#39;，&#39;charlie&#39;]
```

</details>


### shuffle

随机化数组值的顺序，返回一个新数组.

使用 [Fisher-Yates algorithm](https://github.com/30-seconds/30-seconds-of-code#shuffle) 重新排序数组的元素.

```js
const shuffle =（[... arr]）=&gt; {
  设m = arr.length;
  而（m）{
    const i = Math.floor（Math.random（）* m--）;
    [arr [m]，arr [i]] = [arr [i]，arr [m]];
  }
  返回
};
```

<details>
<summary>Examples</summary>

```js
const foo = [1,2,3];
 洗牌（FOO）;  // [2,3,1]，foo = [1,2,3]
```

</details>


### similarity

返回两个数组中出现的元素数组.

使用`Array.prototype.filter（）`删除不属于`values`的值，使用`Array.prototype.includes（）`确定.

```js
const similarity =（arr，values）=&gt; arr.filter（v =&gt; values.includes（v））;
```

<details>
<summary>Examples</summary>

```js
 相似性（[1,2,3]，[1,2,4]）;  // [1,2]
```

</details>


### sortedIndex

返回应将值插入数组的最低索引，以便维护其排序顺序.

检查数组是否按降序排序（松散）.
使用`Array.prototype.findIndex（）`来查找应该插入元素的适当索引.

```js
const sortedIndex =（arr，n）=&gt; {
  const isDescending = arr [0]&gt; arr [arr.length  -  1];
  const index = arr.findIndex（el =&gt;（isDescending？n&gt; = el：n &lt;= el））;
   返回索引=== -1？  arr.length：index;
};
```

<details>
<summary>Examples</summary>

```js
 sortedIndex（[5,3,2,1]，4）;  // 1
 sortedIndex（[30,50]，40）;  // 1
```

</details>


### sortedIndexBy

返回应将值插入数组的最低索引，以便根据提供的迭代器函数维护其排序顺序.

检查数组是否按降序排序（松散）.
使用`Array.prototype.findIndex（）`根据迭代器函数`fn`找到应该插入元素的适当索引.

```js
const sortedIndexBy =（arr，n，fn）=&gt; {
  const isDescending = fn（arr [0]）&gt; fn（arr [arr.length  -  1]）;
  const val = fn（n）;
  const index = arr.findIndex（el =&gt;（isDescending？val&gt; = fn（el）：val &lt;= fn（el）））;
   返回索引=== -1？  arr.length：index;
};
```

<details>
<summary>Examples</summary>

```js
 sortedIndexBy（[{x：4}，{x：5}]，{x：4}，o =&gt; ox）;  // 0
```

</details>


### sortedLastIndex

返回应将值插入数组的最高索引，以便维护其排序顺序.

检查数组是否按降序排序（松散）.
使用`Array.prototype.reverse（）`和`Array.prototype.findIndex（）`来查找应该插入元素的最后一个索引.

```js
const sortedLastIndex =（arr，n）=&gt; {
  const isDescending = arr [0]&gt; arr [arr.length  -  1];
  const index = arr.reverse（）.findIndex（el =&gt;（isDescending？n &lt;= el：n&gt; = el））;
   返回索引=== -1？  0：arr.length  -  index;
};
```

<details>
<summary>Examples</summary>

```js
 sortedLastIndex（[10,20,30,30,40]，30）;  // 4
```

</details>


### sortedLastIndexBy

返回应将值插入数组的最高索引，以便根据提供的迭代器函数维护其排序顺序.

检查数组是否按降序排序（松散）.
使用`Array.prototype.map（）`将迭代器函数应用于数组的所有元素.
使用`Array.prototype.reverse（）`和`Array.prototype.findIndex（）`根据提供的迭代器函数找到应该插入元素的最后一个索引.

```js
const sortedLastIndexBy =（arr，n，fn）=&gt; {
  const isDescending = fn（arr [0]）&gt; fn（arr [arr.length  -  1]）;
  const val = fn（n）;
  const index = arr
    .MAP（FN）
    .相反（）
    .findIndex（el =&gt;（isDescending？val &lt;= el：val&gt; = el））;
   返回索引=== -1？  0：arr.length  -  index;
};
```

<details>
<summary>Examples</summary>

```js
 sortedLastIndexBy（[{x：4}，{x：5}]，{x：4}，o =&gt; ox）;  // 1
```

</details>



对数组执行稳定排序，在值相同时保留项的初始索引.
不改变原始数组，而是返回一个新数组.

使用`Array.prototype.map（）`将输入数组的每个元素与其对应的索引配对.
使用`Array.prototype.sort（）`和`compare`函数对列表进行排序，如果比较的项目相等，则保留它们的初始顺序.
使用`Array.prototype.map（）`转换回初始数组项.

```js
const stableSort =（arr，compare）=&gt;
  ARR
    .map（（item，index）=&gt;（{item，index}））
    .sort（（a，b）=&gt; compare（a.item，b.item）|| a.index  -  b.index）
    .map（（{item}）=&gt; item）;
```

<details>
<summary>Examples</summary>

```js
const arr = [0,1,2,3,4,5,6,7,8,9,10];
 const stable = stableSort（arr，（）=&gt; 0）;  // [0,1,2,3,4,5,6,7,8,9,10]
```

</details>


### symmetricDifference

返回两个数组之间的对称差异，而不过滤掉重复的值.

从每个数组创建一个`Set`，然后在每个数组上使用`Array.prototype.filter（）`只保留另一个不包含的值.

```js
const symmetricDifference =（a，b）=&gt; {
  const sA = new Set（a），
    sB = new Set(b);
  return [... a.filter（x =&gt;！sB.has（x）），... b.filter（x =&gt;！sA.has（x））];
};
```

<details>
<summary>Examples</summary>

```js
 symmetricDifference（[1,2,3]，[1,2,4]）;  // [3,4]
 symmetricDifference（[1,2,2]，[1,3,1]）;  // [2,2,3]
```

</details>


### symmetricDifferenceBy

将提供的函数应用于两个数组的每个数组元素后，返回两个数组之间的对称差异.

通过将`fn`应用于每个数组的元素来创建一个`Set`，然后在每个数组的元素上使用`Array.prototype.filter（）`来保留不包含在另一个数组中的值.

```js
const symmetricDifferenceBy = (a, b, fn) => {
  const sA = new Set（a.map（v =&gt; fn（v）））
    sB = new Set（b.map（v =&gt; fn（v）））;
  return [... a.filter（x =&gt;！sB.has（fn（x））），... b.filter（x =&gt;！sA.has（fn（x）））];
};
```

<details>
<summary>Examples</summary>

```js
 symmetricDifferenceBy（[2.1,1.2]，[2.3,3.4]，Math.floor）;  // [1.2,3.4]
```

</details>


### symmetricDifferenceWith

使用提供的函数作为比较器返回两个数组之间的对称差异.

使用`Array.prototype.filter（）`和`Array.prototype.findIndex（）`来查找适当的值.

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

返回数组中除第一个元素之外的所有元素.

如果数组的`length`大于`1`，则返回`Array.prototype.slice（1）`，否则返回整个数组.

```js
const tail = arr =&gt;（arr.length&gt; 1？arr.slice（1）：arr）;
```

<details>
<summary>Examples</summary>

```js
 尾（[1,2,3]）;  // [2,3]
 尾（[1]）;  // [1]
```

</details>


### take

返回一个从开头删除n个元素的数组.

使用`Array.prototype.slice（）`创建一个数组切片，从头开始采用`n`元素.

```js
const take =（arr，n = 1）=&gt; arr.slice（0，n）;
```

<details>
<summary>Examples</summary>

```js
 拿（[1,2,3]，5）;  // [1,2,3]
 拿（[1,2,3]，0）;  // []
```

</details>


### takeRight

返回从末尾删除n个元素的数组.

使用`Array.prototype.slice（）`创建一个数组切片，从末尾取出`n`个元素.

```js
const takeRight =（arr，n = 1）=&gt; arr.slice（arr.length  -  n，arr.length）;
```

<details>
<summary>Examples</summary>

```js
 takeRight（[1,2,3]，2）;  // [2,3]
 takeRight（[1,2,3]）;  // [3]
```

</details>


### takeRightWhile

 从数组末尾删除元素，直到传递的函数返回“true”.  返回已删除的元素.

循环遍历数组，使用`Array.prototype.reduceRight（）`并累积元素，同时函数返回falsy值.

```js
const takeRightWhile =（arr，func）=&gt;
  arr.reduceRight（（acc，el）=&gt;（func（el）？acc：[el，... acc]），[]）;
```

<details>
<summary>Examples</summary>

```js
 takeRightWhile（[1,2,3,4]，n =&gt; n &lt;3）;  // [3,4]
```

</details>


### takeWhile

 删除数组中的元素，直到传递的函数返回“true”.  返回已删除的元素.

循环遍历数组，使用`for ... of`循环遍历`Array.prototype.entries（）`，直到函数的返回值为`true`.
使用`Array.prototype.slice（）`返回删除的元素.

```js
const takeWhile =（arr，func）=&gt; {
  for（const [i，val] of arr.entries（））if（func（val））return arr.slice（0，i）;
  返回
};
```

<details>
<summary>Examples</summary>

```js
 takeWhile（[1,2,3,4]，n =&gt; n&gt; = 3）;  // [1,2]
```

</details>


### toHash

将给定的Array减少为值哈希（键控数据存储）.

给定一个Iterable或类似Array的结构，在提供的对象上调用`Array.prototype.reduce.call（）`来跳过它并返回一个Object，由参考值键入.

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
 toHash（[4,3,2,1]）;  // {0：4,1：3,2：2,3：1}
 toHash（[{a：&#39;label&#39;}]，&#39;a&#39;）;  // {label：{a：&#39;label&#39;}}
//一个更深入的例子：
让users = [{id：1，first：&#39;Jon&#39;}，{id：2，first：&#39;Joe&#39;}，{id：3，first：&#39;Moe&#39;}];
让经理= [{经理：1，员工：[2,3]}];
//我们在这里使用函数因为我们需要一个可绑定的引用，但引用哈希的闭包也可以工作.
managers.forEach(
  经理=&gt;
    （manager.employees = manager.employees.map（function（id）{
      返回此[id];
    }，toHash（users，&#39;id&#39;）））
);
 管理人员;  // [{manager：1，employees：[{id：2，first：“Joe”}，{id：3，first：“Moe”}}}]
```

</details>


### union

返回两个数组中任何一个中存在的每个元素一次.

使用`a`和`b`的所有值创建一个`Set`并转换为数组.

```js
const union =（a，b）=&gt; Array.from（new Set（[... a，... b]））;
```

<details>
<summary>Examples</summary>

```js
 联合（[1,2,3]，[4,3,2]）;  // [1,2,3,4]
```

</details>


### unionBy

在将提供的函数应用于两者的每个数组元素之后，返回两个数组中任何一个中存在的每个元素.

通过将所有`fn`应用于`a`的所有值来创建`Set`.
从`a`创建一个`Set`和&#39;b`中的所有元素，其值在应用`fn`后与先前创建的集合中的值不匹配.
返回转换为数组的最后一组.

```js
const unionBy =（a，b，fn）=&gt; {
  const s = new Set（a.map（fn））;
  return Array.from（new Set（[... a，... b.filter（x =&gt;！s.has（fn（x）））]））;
};
```

<details>
<summary>Examples</summary>

```js
 unionBy（[2.1]，[1.2,2.3]，Math.floor）;  // [2.1,1.2]
```

</details>


### unionWith

使用提供的比较器函数返回两个数组中任何一个中存在的每个元素.

Create a `Set` with all values of `a` and values in `b` for which the comparator finds no matches in `a`, using `Array.prototype.findIndex()`.

```js
const unionWith = (a, b, comp) =>
  Array.from（new Set（[... a，... b.filter（x =&gt; a.findIndex（y =&gt; comp（x，y））=== -1）]））;
```

<details>
<summary>Examples</summary>

```js
 unionWith（[1,1.2,1.5,3,0]，[1.9,3,0,3.9]，（a，b）=&gt; Math.round（a）=== Math.round（b））;  // [1,1.1,1.5,3,0,3.9]
```

</details>


### uniqueElements

返回数组的所有唯一值.

使用ES6`Set`和`... rest`运算符可以丢弃所有重复的值.

```js
const uniqueElements = arr =&gt; [... new Set（arr）];
```

<details>
<summary>Examples</summary>

```js
 uniqueElements（[1,2,2,3,4,4,5]）;  // [1,2,3,4,5]
```

</details>


### uniqueElementsBy

根据提供的比较器函数返回数组的所有唯一值.

根据比较器函数`fn`，使用`Array.prototype.reduce（）`和`Array.prototype.some（）`作为一个只包含每个值的第一个唯一出现的数组.
The comparator function takes two arguments: the values of the two elements being compared.

```js
const uniqueElementsBy =（arr，fn）=&gt;
  arr.reduce（（acc，v）=&gt; {
    if（！acc.some（x =&gt; fn（v，x）））acc.push（v）;
    返回acc;
  }, []);
```

<details>
<summary>Examples</summary>

```js
uniqueElementsBy(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，价值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，价值：&#39;d&#39;}，
    {id：0，价值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{id：0，值：&#39;a&#39;}，{id：1，值：&#39;b&#39;}，{id：2，值：&#39;c&#39;}]
```

</details>


### uniqueElementsByRight

根据提供的比较器函数返回数组的所有唯一值.

根据比较器函数`fn`，使用`Array.prototype.reduce（）`和`Array.prototype.some（）`作为一个只包含每个值的最后一个唯一出现的数组.
The comparator function takes two arguments: the values of the two elements being compared.

```js
const uniqueElementsByRight =（arr，fn）=&gt;
  arr.reduceRight（（acc，v）=&gt; {
    if（！acc.some（x =&gt; fn（v，x）））acc.push（v）;
    返回acc;
  }, []);
```

<details>
<summary>Examples</summary>

```js
uniqueElementsByRight(
  [
    {id：0，值：&#39;a&#39;}，
    {id：1，价值：&#39;b&#39;}，
    {id：2，value：&#39;c&#39;}，
    {id：1，价值：&#39;d&#39;}，
    {id：0，价值：&#39;e&#39;}
  ],
  （a，b）=&gt; a.id == b.id
 ）;  // [{id：0，value：&#39;e&#39;}，{id：1，value：&#39;d&#39;}，{id：2，value：&#39;c&#39;}]
```

</details>


### uniqueSymmetricDifference

返回两个数组之间唯一的对称差异，不包含任一数组的重复值.

在每个数组上使用`Array.prototype.filter（）`和`Array.prototype.includes（）`来删除另一个数组中包含的值，然后从结果中创建一个`Set`，删除重复的值.

```js
const uniqueSymmetricDifference =（a，b）=&gt; [
  ... new Set（[... a.filter（v =&gt;！b.includes（v）），... b.filter（v =&gt;！a.includes（v））]）
];
```

<details>
<summary>Examples</summary>

```js
 uniqueSymmetricDifference（[1,2,3]，[1,2,4]）;  // [3,4]
 uniqueSymmetricDifference（[1,2,2]，[1,3,1]）;  // [2,3]
```

</details>


### unzip

创建一个数组数组，取消组合生成的数组中的元素 [zip](#zip).

使用`Math.max.apply（）`来获取数组中最长的子数组，`Array.prototype.map（）`，使每个元素成为一个数组.
使用`Array.prototype.reduce（）`和`Array.prototype.forEach（）`将分组值映射到单个数组.

```js
const unzip = arr =&gt;
  arr.reduce（
    （acc，val）=&gt;（val.forEach（（v，i）=&gt; acc [i] .push（v）），acc），
    Array.from（{
      length：Math.max（... arr.map（x =&gt; x.length））
    }）.map（x =&gt; []）
  );
```

<details>
<summary>Examples</summary>

```js
 unzip（[[&#39;a&#39;，1，true]，[&#39;b&#39;，2，false]]）;  // [[&#39;a&#39;，&#39;b&#39;]，[1,2]，[true，false]]
 unzip（[[&#39;a&#39;，1，true]，[&#39;b&#39;，2]]）;  // [[&#39;a&#39;，&#39;b&#39;]，[1,2]，[true]]
```

</details>



创建一个元素数组，取消组合生成的数组中的元素 [zip](#zip) 并应用提供的功能.

使用`Math.max.apply（）`来获取数组中最长的子数组，`Array.prototype.map（）`，使每个元素成为一个数组.
使用`Array.prototype.reduce（）`和`Array.prototype.forEach（）`将分组值映射到单个数组.
使用`Array.prototype.map（）`和扩展运算符（`...`）将`fn`应用于每个单独的元素组.

```js
const unzipWith =（arr，fn）=&gt;
  ARR
    .降低（
      （acc，val）=&gt;（val.forEach（（v，i）=&gt; acc [i] .push（v）），acc），
      Array.from（{
        length：Math.max（... arr.map（x =&gt; x.length））
      }）.map（x =&gt; []）
    )
    .map（val =&gt; fn（... val））;
```

<details>
<summary>Examples</summary>

```js
 unzipWith（[[1,10,100]，[2,20,200]]，（... args）=&gt; args.reduce（（acc，v）=&gt; acc + v，0））;  // [3,30,300]
```

</details>


### without

过滤掉具有指定值之一的数组元素.

使用`Array.prototype.filter（）`创建一个数组，排除（使用`！Array.includes（）`）所有给定的值.

_（对于改变原始数组的片段，请参阅 [`pull`](#pull))_

```js
const without =（arr，... args）=&gt; arr.filter（v =&gt;！args.includes（v））;
```

<details>
<summary>Examples</summary>

```js
 没有（[2,1,2,3]，1,2）;  // [3]
```

</details>


### xProd

通过从数组创建每个可能的对，从提供的两个数组中创建一个新数组.

使用`Array.prototype.reduce（）`，`Array.prototype.map（）`和`Array.prototype.concat（）`从两个数组的元素中生成每个可能的对，并将它们保存在一个数组中.

```js
const xProd =（a，b）=&gt; a.reduce（（acc，x）=&gt; acc.concat（b.map（y =&gt; [x，y]）），[]）;
```

<details>
<summary>Examples</summary>

```js
 xProd（[1,2]，[&#39;a&#39;，&#39;b&#39;]）;  // [[1，&#39;a&#39;]，[1，&#39;b&#39;]，[2，&#39;a&#39;]，[2，&#39;b&#39;]]
```

</details>


### zip

创建一个元素数组，根据原始数组中的位置进行分组.

使用`Math.max.apply（）`来获取参数中最长的数组.
创建一个以该长度作为返回值的数组，并使用带有map-function的“Array.from（）”来创建一个分组元素数组.
如果参数数组的长度不同，则在未找到值的情况下使用“undefined”.

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
 zip（[&#39;a&#39;，&#39;b&#39;]，[1,2]，[true，false]）;  // [[&#39;a&#39;，1，true]，[&#39;b&#39;，2，false]]
 zip（[&#39;a&#39;]，[1,2]，[true，false]）;  // [[&#39;a&#39;，1，true]，[undefined，2，false]]
```

</details>


### zipObject

给定有效属性标识符和值数组的数组，返回将属性与值相关联的对象.

由于对象可以具有未定义的值但不具有未定义的属性指针，因此使用“Array.prototype.reduce（）”来使用属性数组来确定结果对象的结构.

```js
const zipObject =（props，values）=&gt;
  props.reduce（（obj，prop，index）=&gt;（（obj [prop] = values [index]），obj），{}）;
```

<details>
<summary>Examples</summary>

```js
 zipObject（[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]，[1,2]）;  // {a：1，b：2，c：undefined}
 zipObject（[&#39;a&#39;，&#39;b&#39;]，[1,2,3]）;  // {a：1，b：2}
```

</details>



创建一个元素数组，根据原始数组中的位置进行分组，并使用函数作为最后一个值来指定应如何组合分组值.

检查提供的最后一个参数是否为函数.
使用`Math.max（）`来获取参数中最长的数组.
创建一个以该长度作为返回值的数组，并使用带有map-function的“Array.from（）”来创建一个分组元素数组.
如果参数数组的长度不同，则在未找到值的情况下使用“undefined”.
使用每个组`（... group）`的元素调用该函数.

```js
const zipWith =（... array）=&gt; {
   const fn = typeof array [array.length  -  1] ===&#39;function&#39;？  array.pop（）：undefined;
  return Array.from（
    {length：Math.max（... array.map（a =&gt; a.length））}，
    （_，i）=&gt;（fn？fn（... array.map（a =&gt; a [i]））：array.map（a =&gt; a [i]））
  );
};
```

<details>
<summary>Examples</summary>

```js
 zipWith（[1,2]，[10,20]，[100,200]，（a，b，c）=&gt; a + b + c）;  // [111,222]
zipWith(
  [1, 2, 3],
  [10, 20],
  [100, 200],
  （a，b，c）=&gt;（a！= null？a：&#39;a&#39;）+（b！= null？b：&#39;b&#39;）+（c！= null？c：&#39;c&#39;）
 ）;  // [111,222，&#39;3bc&#39;]
```

</details>



---

## 🌐 Browser

### arrayToHtmlList

 将给定的数组元素转换为` <li>  `标记并将它们附加到给定id的列表中.

使用`Array.prototype.map（）`，`document.querySelector（）`和一个匿名内部闭包来创建一个html标签列表.

```js
const arrayToHtmlList =（arr，listID）=&gt;
  （el =&gt;（
    (el = document.querySelector('#' + listID)),
     （el.innerHTML + = arr.map（item =&gt;` <li>  $ {}项 </li>  `）.加入（ &#39;&#39;））
  ))();
```

<details>
<summary>Examples</summary>

```js
arrayToHtmlList（[&#39;item 1&#39;，&#39;item 2&#39;]，&#39;myListID&#39;）;
```

</details>


### bottomVisible

如果页面底部可见，则返回“true”，否则返回“false”.

使用`scrollY`，`scrollHeight`和`clientHeight`来确定页面底部是否可见.

```js
const bottomVisible =（）=&gt;
  document.documentElement.clientHeight + window.scrollY&gt; =
  （document.documentElement.scrollHeight || document.documentElement.clientHeight）;
```

<details>
<summary>Examples</summary>

```js
 bottomVisible（）;  //真
```

</details>



 ⚠️**注意：**使用新的异步剪贴板API可以轻松实现相同的功能，该API仍然是实验性的，但将来应该使用而不是此片段.  了解更多相关信息 [here](https://github.com/w3c/clipboard-apis/blob/master/explainer.adoc#writing-to-the-clipboard).

将字符串复制到剪贴板. 
仅在用户操作的结果下工作（即在“click”事件监听器内）.

 创建一个新的` <textarea>  `element，用提供的数据填充它并将其添加到HTML文档中.
使用`Selection.getRangeAt（）`来存储选定的范围（如果有的话）.
使用`document.execCommand（&#39;copy&#39;）`复制到剪贴板.
 删除` <textarea>  来自HTML文档的`元素.
最后，使用`Selection（）.addRange（）`来恢复原始的选定范围（如果有的话）.

```js
const copyToClipboard = str =&gt; {
  const el = document.createElement（&#39;textarea&#39;）;
  el.value = str;
  el.setAttribute（&#39;readonly&#39;，&#39;&#39;）;
  el.style.position =&#39;绝对&#39;;
  el.style.left =&#39; -  9999px&#39;;
  document.body.appendChild（EL）;
  const selected =
     document.getSelection（）.rangeCount&gt; 0？  document.getSelection（）getRangeAt（0）：false;
  el.select();
  document.execCommand（ &#39;复制&#39;）;
  document.body.removeChild（EL）;
  if（selected）{
    document.getSelection（）removeAllRanges（）;
    .document.getSelection（）的AddRange（选择的）;
  }
};
```

<details>
<summary>Examples</summary>

```js
 copyToClipboard（ &#39;Lorem存有&#39;）;  //“Lorem存有”复制到剪贴板.
```

</details>



创建具有指定选择器的指定范围，步长和持续时间的计数器.

检查`step`是否有正确的符号并相应更改.
将`setInterval（）`与`Math.abs（）`和`Math.floor（）`结合使用，计算每次新文本绘制之间的时间.
使用`document.querySelector（）.innerHTML`来更新所选元素的值.
省略第四个参数`step`，使用默认步骤`1`.
省略第五个参数`duration`，使用默认的持续时间`2000`ms.

```js
const counter =（selector，start，end，step = 1，duration = 2000）=&gt; {
  让current = start，
     _step =（结束 - 开始）*步&lt;0？  -step：step，
    timer = setInterval（（）=&gt; {
      当前+ = _step;
      document.querySelector（selector）.innerHTML = current;
      if（current&gt; = end）document.querySelector（selector）.innerHTML = end;
      if（current&gt; = end）clearInterval（timer）;
    }，Math.abs（Math.floor（duration /（end  -  start））））;
  返回时间;
};
```

<details>
<summary>Examples</summary>

```js
counter('#my-id', 1, 1000, 5, 2000); // Creates a 2-second timer for the element with id="my-id"
```

</details>


### createElement

从字符串创建元素（不将其附加到文档）. 
如果给定的字符串包含多个元素，则只返回第一个元素.

使用`document.createElement（）`创建一个新元素.
将其`innerHTML`设置为作为参数提供的字符串. 
使用`ParentNode.firstElementChild`返回字符串的元素版本.

```js
const createElement = str =&gt; {
  const el = document.createElement（&#39;div&#39;）;
  ElderHTML = str;
  return el.firstElementChild;
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
 的console.log（el.className）;  // &#39;容器&#39;
```

</details>



创建一个pub / sub（[publish–subscribe](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern)）事件集线器有`emit`，`on`和`off`方法.

使用`Object.create（null）`创建一个空的`hub`对象，该对象不从`Object.prototype`继承属性.
对于`emit`，基于`event`参数解析处理程序数组，然后通过传入数据作为参数，使用`Array.prototype.forEach（）`运行每个处理程序.
对于`on`，如果事件尚不存在，则为该事件创建一个数组，然后使用`Array.prototype.push（）`添加处理程序
到阵列.
对于`off`，使用`Array.prototype.findIndex（）`来查找事件数组中处理程序的索引，并使用`Array.prototype.splice（）`将其删除.

```js
const createEventHub =（）=&gt;（{
  hub：Object.create（null），
  发射（事件，数据）{
    （this.hub [event] || []）.forEach（handler =&gt; handler（data））;
  },
  on（event，handler）{
    if（！this.hub [event]）this.hub [event] = [];
    this.hub [事件] .push（处理程序）;
  },
  off（事件，处理程序）{
    const i =（this.hub [event] || []）.findIndex（h =&gt; h === handler）;
    if（i&gt; -1）this.hub [event] .splice（i，1）;
    if（this.hub [event] .length === 0）删除this.hub [event];
  }
});
```

<details>
<summary>Examples</summary>

```js
const handler = data =&gt; console.log（data）;
const hub = createEventHub（）;
let increment = 0;

//订阅：收听不同类型的活动
hub.on（&#39;message&#39;，handler）;
hub.on（&#39;message&#39;，（）=&gt; console.log（&#39;Message event fired&#39;））;
hub.on（&#39;increment&#39;，（）=&gt; increment ++）;

// Publish：发出事件以调用订阅它们的所有处理程序，并将数据作为参数传递给它们
 hub.emit（&#39;message&#39;，&#39;hello world&#39;）;  //记录&#39;hello world&#39;和&#39;Message event fired&#39;
 hub.emit（&#39;message&#39;，{hello：&#39;world&#39;}）;  //记录对象和&#39;Message event fired&#39;
 hub.emit（ &#39;增量&#39;）;  //`increment`变量现在为1

//取消订阅：停止特定处理程序收听&#39;message&#39;事件
hub.off（&#39;message&#39;，handler）;
```

</details>


### currentURL

返回当前URL.

使用`window.location.href`获取当前URL.

```js
const currentURL =（）=&gt; window.location.href;
```

<details>
<summary>Examples</summary>

```js
 CURRENTURL（）;  //&#39;https://google.com&#39;
```

</details>


### detectDeviceType

检测网站是在移动设备还是台式机/笔记本电脑中打开.

使用正则表达式测试`navigator.userAgent`属性，以确定设备是移动设备还是台式机/笔记本电脑.

```js
const detectDeviceType =（）=&gt;
  / Android | webOS | iPhone | iPad | iPod | BlackBerry | IEMobile | Opera Mini / i.test（navigator.userAgent）
     ？  &#39;移动&#39;
    ： &#39;桌面&#39;;
```

<details>
<summary>Examples</summary>

```js
 detectDeviceType（）;  //“手机”或“桌面”
```

</details>


### elementContains

如果`parent`元素包含`child`元素，则返回`true`，否则返回`false`.

检查`parent`与`child`不是同一个元素，使用`parent.contains（child）`来检查`parent`元素是否包含`child`元素.

```js
const elementContains =（parent，child）=&gt; parent！== child &amp;&amp; parent.contains（child）;
```

<details>
<summary>Examples</summary>

```js
 elementContains（document.querySelector（&#39;head&#39;），document.querySelector（&#39;title&#39;））;  //真
 elementContains（document.querySelector（&#39;body&#39;），document.querySelector（&#39;body&#39;））;  //假
```

</details>



如果指定的元素在视口中可见，则返回“true”，否则返回“false”.

使用`Element.getBoundingClientRect（）`和`window.inner（Width | Height）`值
确定给定元素在视口中是否可见.
省略第二个参数以确定元素是否完全可见，或指定“true”以确定是否
它是部分可见的.

```js
const elementIsVisibleInViewport =（el，partiallyVisible = false）=&gt; {
  const {top，left，bottom，right} = el.getBoundingClientRect（）;
  const {innerHeight，innerWidth} = window;
  返回partialVisible
     ？  （（top&gt; 0 &amp;&amp; top &lt;innerHeight）||（bottom&gt; 0 &amp;&amp; bottom &lt;innerHeight））&amp;&amp;
        （（left&gt; 0 &amp;&amp; left &lt;innerWidth）||（right&gt; 0 &amp;&amp; right &lt;innerWidth））
    ：top&gt; = 0 &amp;&amp; left&gt; = 0 &amp;&amp; bottom &lt;= innerHeight &amp;&amp; right &lt;= innerWidth;
};
```

<details>
<summary>Examples</summary>

```js
//例如100x100视口和位置{top：-1，left：0，bottom：9，right：10}的10x10px元素
 elementIsVisibleInViewport（EL）;  //假 - （不完全可见）
 elementIsVisibleInViewport（el，true）;  // true  - （部分可见）
```

</details>


### formToObject

Encode a set of form elements as an `object`.

使用`FormData`构造函数将HTML`form`转换为`FormData`，`Array.from（）`转换为数组.
使用`Array.prototype.reduce（）`从数组中收集对象.

```js
const formToObject = form =&gt;
  Array.from（new FormData（form））.reduce（
    （acc，[key，value]）=&gt;（{
      ... ACC，
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

从元素中获取所有图像并将它们放入数组中

 使用`Element.prototype.getElementsByTagName（）`来获取所有` <img>  `元素里面提供的元素，&#39;Array.prototype.map（）`来映射各自`的`src`属性. <img>  `element，然后创建一个`Set`来消除重复并返回数组.

```js
const getImages =（el，includeDuplicates = false）=&gt; {
  const images = [... el.getElementsByTagName（&#39;img&#39;）].map（img =&gt; img.getAttribute（&#39;src&#39;））;
   return includeDuplicates？  图像：[...新集（图像）];
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

如果定义了&#39;pageXOffset`和`pageYOffset`，则使用`scrollLeft`和`scrollTop`.
您可以省略`el`来使用默认值`window`.

```js
const getScrollPosition =（el = window）=&gt;（{
   x：el.pageXOffset！== undefined？  el.pageXOffset：el.scrollLeft，
   并且：el.pageYOffset！== undefined？  el.pageYOffset：el.scrollTop
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

使用`Window.getComputedStyle（）`获取指定元素的CSS规则的值.

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

如果元素具有指定的类，则返回“true”，否则返回“false”.

使用`element.classList.contains（）`来检查元素是否具有指定的类.

```js
const hasClass =（el，className）=&gt; el.classList.contains（className）;
```

<details>
<summary>Examples</summary>

```js
 hasClass（document.querySelector（&#39;p.special&#39;），&#39;special&#39;）;  //真
```

</details>



使用.创建值的哈希 [SHA-256](https://en.wikipedia.org/wiki/SHA-2)  算法.  返回一个promise.

使用 [SubtleCrypto](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto) 用于为给定值创建哈希的API.

```js
const hashBrowser = val =&gt;
  crypto.subtle.digest（&#39;SHA-256&#39;，new TextEncoder（&#39;utf-8&#39;）.encode（val））.then（h =&gt; {
    让hexes = []，
      view = new DataView（h）;
    for（let i = 0; i &lt;view.byteLength; i + = 4）
      hexes.push（（&#39;00000000&#39;+ view.getUint32（i）.toString（16））.slice（-8））;
    return hexes.join（&#39;&#39;）;
  });
```

<details>
<summary>Examples</summary>

```js
 hashBrowser（JSON.stringify（{a：&#39;a&#39;，b：[1,2,3,4]，foo：{c：&#39;bar&#39;}}））.then（console.log）;  //&#39;04aa106279f5977f59f9067fa9712afc4aedc6f5862a8defc34552d8c7206393&#39;
```

</details>


### hide

隐藏指定的所有元素.

使用`NodeList.prototype.forEach（）`将`display：none`应用于指定的每个元素.

```js
const hide = (...el) => [...el].forEach(e => (e.style.display = 'none'));
```

<details>
<summary>Examples</summary>

```js
 隐藏（document.querySelectorAll（ &#39;IMG&#39;））;  //隐藏所有 <img>  页面上的元素
```

</details>


### httpsRedirect

 如果页面当前处于HTTP状态，则将页面重定向到HTTPS.  此外，按下后退按钮不会将其恢复到HTTP页面，因为它已在历史记录中替换.

 使用`location.protocol`来获取当前使用的协议.  如果它不是HTTPS，请使用`location.replace（）`将现有页面替换为页面的HTTPS版本.  使用`location.href`获取完整地址，用`String.prototype.split（）`拆分它，并删除URL的协议部分.

```js
const httpsRedirect =（）=&gt; {
  if（location.protocol！==&#39;https：&#39;）location.replace（&#39;https：//&#39;+ location.href.split（&#39;//&#39;）[1]）;
};
```

<details>
<summary>Examples</summary>

```js
 httpsRedirect（）;  //如果您在http://mydomain.com上，则会被重定向到https://mydomain.com
```

</details>


### insertAfter

在指定元素结束后插入HTML字符串.

使用&#39;el.insertAdjacentHTML（）`和`&#39;afterend&#39;的位置来解析`htmlString`并在`el`结束后插入它.

```js
const insertAfter =（el，htmlString）=&gt; el.insertAdjacentHTML（&#39;afterend&#39;，htmlString）;
```

<details>
<summary>Examples</summary>

```js
 insertAfter（document.getElementById（&#39;myId&#39;），&#39; <p>  后 </p>  “）;  // <div id="myId">  ... </div><p>  后 </p>
```

</details>


### insertBefore

在指定元素的开头之前插入HTML字符串.

使用&#39;el.insertAdjacentHTML（）`和`&#39;beforebegin&#39;`的位置来解析`htmlString`并在`el`的开头之前插入它.

```js
const insertBefore =（el，htmlString）=&gt; el.insertAdjacentHTML（&#39;beforebegin&#39;，htmlString）;
```

<details>
<summary>Examples</summary>

```js
 insertBefore（document.getElementById（&#39;myId&#39;），&#39; <p>  之前 </p>  “）;  // <p>  之前 </p><div id="myId">  ... </div>
```

</details>


### isBrowserTabFocused

如果页面的浏览器选项卡是聚焦的，则返回“true”，否则返回“false”.

使用Page Visibility API引入的`Document.hidden`属性来检查页面的浏览器选项卡是可见还是隐藏.

```js
const isBrowserTabFocused =（）=&gt;！document.hidden;
```

<details>
<summary>Examples</summary>

```js
 isBrowserTabFocused（）;  //真
```

</details>


### nodeListToArray

将`NodeList`转换为数组.

在新数组中使用spread运算符将`NodeList`转换为数组.

```js
const nodeListToArray = nodeList =&gt; [... nodeList];
```

<details>
<summary>Examples</summary>

```js
 nodeListToArray（document.childNodes）;  // [ <!DOCTYPE html>  ，html]
```

</details>



返回一个新的MutationObserver，并为指定元素上的每个变异运行提供的回调.

用一个 [`MutationObserver`](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver) 观察给定元素的突变.
使用`Array.prototype.forEach（）`为每个观察到的突变运行回调.
省略第三个参数`options`，以使用默认值 [options](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver#MutationObserverInit) （所有&#39;真实&#39;）.

```js
const observeMutations =（element，callback，options）=&gt; {
  const observer = new MutationObserver（mutation =&gt; mutation.forEach（m =&gt; callback（m）））;
  observer.observe（
    元件，
    Object.assign（
      {
        childList：true，
        属性：true，
        attributeOldValue：true，
        characterData：true，
        characterDataOldValue：true，
        子树：真
      },
      选项
    )
  );
  回归观察员;
};
```

<details>
<summary>Examples</summary>

```js
 const obs = observeMutations（document，console.log）;  //记录页面上发生的所有突变
 obs.disconnect（）;  //断开观察者连接并停止在页面上记录突变
```

</details>


### off

Removes an event listener from an element.

使用`EventTarget.removeEventListener（）`从元素中删除事件侦听器. 
省略第四个参数`opts`使用`false`或根据添加事件监听器时使用的选项指定它.

```js
const off =（el，可能，fn，opts = false）=&gt; el.removeEventListener（可能，fn，opts）;
```

<details>
<summary>Examples</summary>

```js
const fn =（）=&gt; console.log（&#39;！&#39;）;
document.body.addEventListener（&#39;click&#39;，fn）;
 off（document.body，&#39;click&#39;，fn）;  //不再记录&#39;！&#39;  点击页面
```

</details>


### on

向具有使用事件委派功能的元素添加事件侦听器.

 使用`EventTarget.addEventListener（）`向元素添加事件监听器.  如果有一个`target`属性提供给options对象，请确保事件目标与指定的目标匹配，然后通过提供正确的`this`上下文来调用回调.
返回对自定义委托者函数的引用，以便可以使用 [`off`](#off).
省略`opts`以默认为非委托行为和事件冒泡.

```js
const on =（el，evt，fn，opts = {}）=&gt; {
  const delegatorFn = e =&gt; e.target.matches（opts.target）&amp;&amp; fn.call（e.target，e）;
  el.addEventListener（可能是opts.target？delegatorFn：fn，opts.options || false）;
  if（opts.target）返回delegatorFn;
};
```

<details>
<summary>Examples</summary>

```js
const fn =（）=&gt; console.log（&#39;！&#39;）;
 on（document.body，&#39;click&#39;，fn）;  //记录&#39;！&#39;  点击身体后
 on（document.body，&#39;click&#39;，fn，{target：&#39;p&#39;}）;  //记录&#39;！&#39;  点击身体的&#39;p`元素孩子
 on（document.body，&#39;click&#39;，fn，{options：true}）;  //使用捕获而不是冒泡
```

</details>



 每当用户输入类型改变时（`mouse`或`touch`）运行回调.  用于根据输入设备启用/禁用代码.  此过程是动态的，适用于混合设备（例如触摸屏笔记本电脑）.

 使用两个事件侦听器.  首先假设`mouse`输入并将`touchstart`事件监听器绑定到文档. 
在`touchstart`上，添加一个`mousemove`事件监听器，使用`performance.now（）`监听在20ms内触发的两个连续`mousemove`事件.
在任何一种情况下，使用输入类型作为参数运行回调.

```js
const onUserInputChange = callback =&gt; {
  让type =&#39;mouse&#39;，
    lastTime = 0;
  const mousemoveHandler =（）=&gt; {
    const now = performance.now（）;
    if（现在 -  lastTime &lt;20）
      （type =&#39;mouse&#39;），callback（type），document.removeEventListener（&#39;mousemove&#39;，mousemoveHandler）;
    lastTime = now;
  };
  document.addEventListener（&#39;touchstart&#39;，（）=&gt; {
    if（type ===&#39;touch&#39;）return;
    （type =&#39;touch&#39;），callback（type），document.addEventListener（&#39;mousemove&#39;，mousemoveHandler）;
  });
};
```

<details>
<summary>Examples</summary>

```js
onUserInputChange（type =&gt; {
  console.log（&#39;用户现在正在使用&#39;，type，&#39;作为输入法.&#39;）;
});
```

</details>


### prefix

返回浏览器支持的CSS属性的前缀版本（如果需要）.

在供应商前缀字符串数组上使用`Array.prototype.findIndex（）`来测试`document.body`是否在其`CSSStyleDeclaration`对象中定义了其中一个，否则返回`null`.
使用`String.prototype.charAt（）`和`String.prototype.toUpperCase（）`来大写属性，该属性将附加到供应商前缀字符串.

```js
const prefix = prop =&gt; {
  const capitalizedProp = prop.charAt（0）.toUpperCase（）+ prop.slice（1）;
  const前缀= [&#39;&#39;，&#39;webkit&#39;，&#39;moz&#39;，&#39;ms&#39;，&#39;o&#39;];
  const i = prefixes.findIndex（
     prefix =&gt; typeof document.body.style [前缀？  前缀+ capitalizedProp：prop]！==&#39;undefined&#39;
  );
   返回i！== -1？  （i === 0？prop：prefixes [i] + capitalizedProp）：null;
};
```

<details>
<summary>Examples</summary>

```js
 前缀（ &#39;外貌&#39;）;  //&#39;支持的浏览器&#39;&#39;外观&#39;，否则&#39;webkitAppearance&#39;，&#39;mozAppearance&#39;，&#39;msAppearance&#39;或&#39;oAppearance&#39;
```

</details>


### recordAnimationFrames

在每个动画帧上调用提供的回调.

使用递归. 
如果`running`是&#39;true`，则继续调用`window.requestAnimationFrame（）`，它调用提供的回调. 
使用两个方法`start`和`stop`返回一个对象，以允许手动控制录制. 
省略第二个参数`autoStart`，在调用函数时隐式调用`start`.

```js
const recordAnimationFrames =（callback，autoStart = true）=&gt; {
  让running = true，
    货架;
  const stop =（）=&gt; {
    running = false;
    cancelAnimationFrame（RAF）;
  };
  const start =（）=&gt; {
    running = true;
    跑（）;
  };
  const run =（）=&gt; {
    raf = requestAnimationFrame（（）=&gt; {
      打回来（）;
      if（running）run（）;
    });
  };
  if（autoStart）start（）;
  return { start, stop };
};
```

<details>
<summary>Examples</summary>

```js
const cb =（）=&gt; console.log（&#39;Animation frame fired&#39;）;
 const recorder = recordAnimationFrames（cb）;  //在每个动画帧上记录“动画帧触发”
 recorder.stop（）;  //停止记录
 recorder.start（）;  //再次开始
 const recorder2 = recordAnimationFrames（cb，false）;  //需要明确调用`start`来开始记录帧
```

</details>


### redirect

重定向到指定的URL.

使用`window.location.href`或`window.location.replace（）`重定向到`url`.
传递第二个参数来模拟链接点击（“true” - 默认）或HTTP重定向（“false”）.

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



使用a在单独的线程中运行函数 [Web Worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)，允许长时间运行的功能不阻止UI.

使用`Blob`对象URL创建一个新的`Worker`，其内容应该是所提供函数的字符串化版本.
立即发布回调函数的返回值.
返回一个promise，侦听`onmessage`和`onerror`事件并解析从worker返回的数据，或者抛出错误.

```js
const runAsync = fn =&gt; {
  const worker =新工人（
    URL.createObjectURL（new Blob（[`postMessage（（$ {fn}）（））;`]），{
       类型：&#39;application / javascript;  字符集= UTF-8&#39;
    })
  );
  返回新的Promise（（res，rej）=&gt; {
    worker.onmessage =（{data}）=&gt; {
      res（data），worker.terminate（）;
    };
    worker.onerror = err =&gt; {
      rej（err），worker.terminate（）;
    };
  });
};
```

<details>
<summary>Examples</summary>

```js
const longRunningFunction =（）=&gt; {
  let result = 0;
  for（let i = 0; i &lt;1000; i ++）
    for（let j = 0; j &lt;700; j ++）for（let k = 0; k &lt;300; k ++）result = result + i + j + k;

  返回结果;
};
/*
  注意：由于该函数在不同的上下文中运行，因此不支持闭包.
  提供给`runAsync`的函数被字符串化，所以一切都变成了文字.
  必须在里面定义所有变量和函数.
*/
 runAsync（longRunningFunction）.然后（的console.log）;  // 209685000000
 runAsync（（）=&gt; 10 ** 3）.then（console.log）;  // 1000
let outsideVariable = 50;
 runAsync（（）=&gt; typeof outsideVariable）.then（console.log）;  //&#39;undefined&#39;
```

</details>


### scrollToTop

平滑滚动到页面顶部.

使用`document.documentElement.scrollTop`或`document.body.scrollTop`与顶部保持距离.
 滚动距离顶部一小部分距离.  使用`window.requestAnimationFrame（）`来动画滚动.

```js
const scrollToTop =（）=&gt; {
   const c = document.documentElement.scrollTop ||  的document.body.scrollTop;
  if（c&gt; 0）{
    window.requestAnimationFrame（scrollToTop）;
    window.scrollTo（0，c  -  c / 8）;
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

Use the `FormData` constructor to convert the HTML `form` to `FormData`, `Array.from()` to convert to an array, passing a map function as the second argument.
使用`Array.prototype.map（）`和`window.encodeURIComponent（）`来编码每个字段的值.
使用带有适当参数的`Array.prototype.join（）`来生成适当的查询字符串.

```js
const serializeForm = form =&gt;
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

使用`element.style`将指定元素的CSS规则值设置为`val`.

```js
const setStyle =（the，ruleName，val）=&gt;（el.style [ruleName] = val）;
```

<details>
<summary>Examples</summary>

```js
 setStyle（document.querySelector（&#39;p&#39;），&#39;font-size&#39;，&#39;20px&#39;）;  // 首先 <p>  页面上的元素的字体大小为20px
```

</details>


### show

显示指定的所有元素.

使用扩展运算符（`...`）和`Array.prototype.forEach（）`清除指定的每个元素的`display`属性.

```js
const show =（... el）=&gt; [... el] .forEach（e =&gt;（e.style.display =&#39;&#39;））;
```

<details>
<summary>Examples</summary>

```js
 显示（... document.querySelectorAll（ &#39;IMG&#39;））;  //全部显示 <img>  页面上的元素
```

</details>


### smoothScroll

平滑地将调用它的元素滚动到浏览器窗口的可见区域.

使用`.scrollIntoView`方法滚动元素. 
将`{behavior：&#39;smooth&#39;}`传递给`.scrollIntoView`，使其顺畅滚动.

```js
const smoothScroll = element =&gt;
  document.querySelector（元件）.scrollIntoView（{
    行为：&#39;顺畅&#39;
  });
```

<details>
<summary>Examples</summary>

```js
smoothScroll('#fooBar'); // scrolls smoothly to the element with the id fooBar
 smoothScroll（ &#39;fooBar&#39; 的）;  //使用fooBar类顺利滚动到第一个元素
```

</details>


### toggleClass

切换元素的类.

使用`element.classList.toggle（）`来切换元素的指定类.

```js
const toggleClass =（el，className）=&gt; el.classList.toggle（className）;
```

<details>
<summary>Examples</summary>

```js
 toggleClass（document.querySelector（&#39;p.special&#39;），&#39;special&#39;）;  //段落将不再具有“特殊”类
```

</details>


### triggerEvent

触发给定元素上的特定事件，可选地传递自定义数据.

使用`new CustomEvent（）`从指定的`eventType`和细节创建一个事件.
使用`el.dispatchEvent（）`来触发给定元素上新创建的事件.
如果您不想将自定义数据传递给触发事件，请省略第三个参数`detail`.

```js
const triggerEvent =（el，eventType，detail）=&gt;
  el.dispatchEvent（new CustomEvent（eventType，{detail}））;
```

<details>
<summary>Examples</summary>

```js
triggerEvent（document.getElementById（&#39;myId&#39;），&#39;click&#39;）;
triggerEvent（document.getElementById（&#39;myId&#39;），&#39;click&#39;，{username：&#39;bob&#39;}）;
```

</details>


### UUIDGeneratorBrowser

在浏览器中生成UUID.

使用`crypto` API生成符合的UUID [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) 版本4.

```js
const UUIDGeneratorBrowser =（）=&gt;
  （[1e7] + -1e3 + -4e3 + -8e3 + -1e11）.replace（/ [018] / g，c =&gt;
    （c ^（crypto.getRandomValues（new Uint8Array（1））[0]＆（15 &gt;&gt;（c / 4））））.toString（16）
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

从“Date”对象获取一年中的某一天.

使用`new Date（）`和`Date.prototype.getFullYear（）`来获取一年中的第一天作为`Date`对象，从提供的`date`中减去它，然后除以每天的毫秒数得到结果.
使用`Math.floor（）`将生成的日计数适当地舍入为整数.

```js
const dayOfYear = date =&gt;
  Math.floor（（date  -  new Date（date.getFullYear（），0,0））/ 1000/60/60/24）;
```

<details>
<summary>Examples</summary>

```js
 dayOfYear（new Date（））;  // 272
```

</details>


### formatDuration

返回给定毫秒数的人类可读格式.

将`ms`除以适当的值，以获得“day”，“hour”，“minute”，“second”和“millisecond”的适当值.
使用`Object.entries（）`和`Array.prototype.filter（）`来保持非零值.
使用`Array.prototype.map（）`为每个值创建字符串，并进行适当的多元化.
使用`String.prototype.join（&#39;，&#39;）`将值组合成一个字符串.

```js
const formatDuration = ms =&gt; {
  if（ms &lt;0）ms = -ms;
  const time = {
    日：Math.floor（ms / 86400000），
    小时：Math.floor（ms / 3600000）％24，
    分钟：Math.floor（ms / 60000）％60，
    第二名：Math.floor（ms / 1000）％60，
    毫秒：Math.floor（ms）％1000
  };
  return Object.entries（time）
    .filter（choice =&gt; choice [1]！== 0）
    .map（（[key，val]）=&gt;`$ {val} $ {key} $ {val！== 1？&#39;s&#39;：&#39;&#39;}`）
    .join（&#39;，&#39;）;
};
```

<details>
<summary>Examples</summary>

```js
 formatDuration（1001）;  //&#39;1秒，1毫秒&#39;
 formatDuration（34325055574）;  //&#39;397天，6小时，44分钟，15秒，574毫秒&#39;
```

</details>


### getColonTimeFromDate

从“Date”对象返回“HH：MM：SS”形式的字符串.

使用`Date.prototype.toTimeString（）`和`String.prototype.slice（）`来获取给定`Date`对象的`HH：MM：SS`部分.

```js
const getColonTimeFromDate = date =&gt; date.toTimeString（）.slice（0,8）;
```

<details>
<summary>Examples</summary>

```js
 getColonTimeFromDate（new Date（））;  //“08:38:00”
```

</details>


### getDaysDiffBetweenDates

返回两个日期之间的差异（以天为单位）.

计算两个`Date`对象之间的差异（以天为单位）.

```js
const getDaysDiffBetweenDates =（dateInitial，dateFinal）=&gt;
  （dateFinal  -  dateInitial）/（1000 * 3600 * 24）;
```

<details>
<summary>Examples</summary>

```js
 getDaysDiffBetweenDates（新日期（&#39;2017-12-13&#39;），新日期（&#39;2017-12-22&#39;））;  // 9
```

</details>


### getMeridiemSuffixOfInteger

将整数转换为后缀字符串，根据其值添加“am”或“pm”.

使用模运算符（`％`）和条件检查将整数转换为带有meridiem后缀的字符串化12小时格式.

```js
const getMeridiemSuffixOfInteger = num =&gt;
   是否=== 0 ||  ===是否24
     ？  12 +&#39;上午&#39;
    ：num === 12
       ？  12 +&#39;pm&#39;
      ：num &lt;12
         ？  （num％12）+&#39;am&#39;
        ：（无论12％）PM“;
```

<details>
<summary>Examples</summary>

```js
 getMeridiemSuffixOfInteger（0）;  //“12am”
 getMeridiemSuffixOfInteger（11）;  // “上午11点”
 getMeridiemSuffixOfInteger（13）;  //“下午1点”
 getMeridiemSuffixOfInteger（25）;  //“下午1点”
```

</details>


### isAfterDate

检查日期是否在另一个日期之后.

使用大于运算符（`&gt;`）来检查第一个日期是否在第二个日期之后.

```js
const isAfterDate =（dateA，dateB）=&gt; dateA&gt; dateB;
```

<details>
<summary>Examples</summary>

```js
 isAfterDate（新日期（2010年，10,21），新日期（2010年，10,20））;  //真
```

</details>


### isBeforeDate

检查日期是否在另一个日期之前.

使用小于运算符（`&lt;`）来检查第一个日期是否在第二个日期之前.

```js
const isBeforeDate =（dateA，dateB）=&gt; dateA &lt;dateB;
```

<details>
<summary>Examples</summary>

```js
 isBeforeDate（新日期（2010年，10,20），新日期（2010年，10年，21日））;  //真
```

</details>


### isSameDate

检查日期是否与另一个日期相同.

使用`Date.prototype.toISOString（）`和严格的等式检查（`===`）来检查第一个日期是否与第二个日期相同.

```js
const isSameDate =（dateA，dateB）=&gt; dateA.toISOString（）=== dateB.toISOString（）;
```

<details>
<summary>Examples</summary>

```js
 isSameDate（新日期（2010年，10,20），新日期（2010年，10,20））;  //真
```

</details>


### maxDate

返回给定日期的最大值.

使用`Math.max.apply（）`查找最大日期值，`new Date（）`将其转换为`Date`对象.

```js
const maxDate =（... dates）=&gt; new Date（Math.max.apply（null，... dates））;
```

<details>
<summary>Examples</summary>

```js
const array = [
  新日期（2017年，4,13），
  新日期（2018年，2月12日），
  新日期（2016年，0,10），
  新日期（2016年，0,9）
];
 的maxDate（数组）;  // 2018-03-11T22：00：00.000Z
```

</details>


### minDate

返回给定日期的最小值.

使用`Math.min.apply（）`查找最小日期值，`new Date（）`将其转换为`Date`对象.

```js
const minDate =（... dates）=&gt; new Date（Math.min.apply（null，... dates））;
```

<details>
<summary>Examples</summary>

```js
const array = [
  新日期（2017年，4,13），
  新日期（2018年，2月12日），
  新日期（2016年，0,10），
  新日期（2016年，0,9）
];
 的minDate（数组）;  // 2016-01-08T22：00：00.000Z
```

</details>


### tomorrow

结果以明天的日期的字符串表示.

使用`new Date（）`获取当前日期，使用`Date.getDate（）`递增1，并使用`Date.setDate（）`将值设置为结果. 
使用`Date.prototype.toISOString（）`以`yyyy-mm-dd`格式返回一个字符串.

```js
const tomorrow =（）=&gt; {
  let t = new Date（）;
  t.setDate（t.getDate（）+ 1）;
  return t.toISOString（）.split（&#39;T&#39;）[0];
};
```

<details>
<summary>Examples</summary>

```js
 明天（）;  // 2018-10-19（如果当前日期是2018-10-18）
```

</details>



---

## 🎛️ Function

### attempt

尝试使用提供的参数调用函数，返回结果或捕获的错误对象.

使用`try ... catch`块返回函数的结果或适当的错误.

```js
const attempt =（fn，... args）=&gt; {
  尝试{
    return fn（... args）;
  } catch（e）{
     返回e instanceof错误？  e：新错误（e）;
  }
};
```

<details>
<summary>Examples</summary>

```js
var elements = attempt（function（selector）{
  return document.querySelectorAll（selector）;
}, '>_>');
 if（elements instanceof Error）elements = [];  // elements = []
```

</details>


### bind

创建一个函数，该函数使用给定的上下文调用`fn`，可选地将任何其他提供的参数添加到参数的开头.

返回一个`function`，它使用`Function.prototype.apply（）`将给定的`context`应用于`fn`.
使用`Array.prototype.concat（）`将任何其他提供的参数添加到参数中.

```js
const bind =（fn，context，... boundArgs）=&gt;（... args）=&gt; fn.apply（context，[... boundArgs，... args]）;
```

<details>
<summary>Examples</summary>

```js
函数问候（问候，标点符号）{
  return greeting +&#39;&#39;+ this.user + punctuation;
}
const freddy = {user：&#39;fred&#39;};
const freddyBound = bind（greet，freddy）;
 console.log（freddyBound（&#39;hi&#39;，&#39;！&#39;））;  //&#39;嗨，弗雷德！&#39;
```

</details>


### bindKey

创建一个函数，该函数在对象的给定键处调用该方法，可选地将任何其他提供的参数添加到参数的开头.

返回一个`function`，它使用`Function.prototype.apply（）`将`context [fn]`绑定到`context`.
使用扩展运算符（`...`）将任何其他提供的参数添加到参数中.

```js
const bindKey =（context，fn，... boundArgs）=&gt;（... args）=&gt;
  context [fn] .apply（context，[... boundArgs，... args]）;
```

<details>
<summary>Examples</summary>

```js
const freddy = {
  用户：&#39;fred&#39;，
  问候：功能（问候，标点符号）{
    return greeting +&#39;&#39;+ this.user + punctuation;
  }
};
const freddyBound = bindKey（freddy，&#39;greet&#39;）;
 console.log（freddyBound（&#39;hi&#39;，&#39;！&#39;））;  //&#39;嗨，弗雷德！&#39;
```

</details>


### chainAsync

链接异步函数.

循环遍历包含异步事件的函数数组，在每个异步事件完成时调用`next`.

```js
const chainAsync = fns =&gt; {
  让curr = 0;
  const last = fns [fns.length  -  1];
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
  next =&gt; {
    console.log（&#39;0秒&#39;）;
    setTimeout（next，1000）;
  },
  next =&gt; {
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

给定一个`predicate`函数和一个`prop`字符串，这个curried函数将通过调用属性并将其传递给谓词来检查`object`.

在`obj`上召唤`prop`，将它传递给提供的`predicate`函数并返回一个屏蔽的布尔值.

```js
const checkProp =（predicate，prop）=&gt; obj =&gt; !!谓词（obj [prop]）;
```

<details>
<summary>Examples</summary>

```js
















const lengthIs4 = checkProp（l =&gt; l === 4，&#39;length&#39;）;
 lengthIs4（[]）;  //假
 lengthIs4（[1,2,3,4]）;  //真
 lengthIs4（new Set（[1,2,3,4]））;  // false（设置使用大小，而不是长度）

const session = {user：{}};
const validUserSession = checkProps（u =&gt; u.active &amp;&amp;！u.disabled，&#39;user&#39;）;

 validUserSession（会话）;  //假

session.user.active = true;
 validUserSession（会话）;  //真

const noLength（l =&gt; l === undefined，&#39;length&#39;）;
 noLength（[]）;  //假
 noLength（{}）;  //真
 noLength（new Set（））;  //真
```

</details>


### compose

执行从右到左的功能组合.

使用`Array.prototype.reduce（）`来执行从右到左的函数组合.
 最后（最右边）函数可以接受一个或多个参数;  其余的功能必须是一元的.

```js
const compose =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; f（g（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add5 = x =&gt; x + 5;
const multiply =（x，y）=&gt; x * y;
const multiplyAndAdd5 =撰写（
  ADD5，
  乘
);
 multiplyAndAdd5（5,2）;  // 15
```

</details>


### composeRight

执行从左到右的功能组合.

使用`Array.prototype.reduce（）`来执行从左到右的函数组合.
 第一个（最左边）函数可以接受一个或多个参数;  其余的功能必须是一元的.

```js
const composeRight =（... fns）=&gt; fns.reduce（（f，g）=&gt;（... args）=&gt; g（f（... args）））;
```

<details>
<summary>Examples</summary>

```js
const add =（x，y）=&gt; x + y;
const square = x =&gt; x * x;
const addAndSquare = composeRight（add，square）;
 addAndSquare（1,2）;  // 9
```

</details>


### converge

接受聚合函数和分支函数列表，并返回将每个分支函数应用于参数的函数，并将分支函数的结果作为参数传递给聚合函数.

使用`Array.prototype.map（）`和`Function.prototype.apply（）`将每个函数应用于给定的参数.
使用扩展运算符（`...`）用所有其他函数的结果调用`coverger`.

```js
const converge =（converger，fns）=&gt;（... args）=&gt; converger（... fns.map（fn =&gt; fn.apply（null，args）））;
```

<details>
<summary>Examples</summary>

```js
const average = converge（（a，b）=&gt; a / b，[
  arr =&gt; arr.reduce（（a，v）=&gt; a + v，0），
  arr =&gt; arr.length
]);
 平均值（[1,2,3,4,5,6,7]）;  // 4
```

</details>


### curry

提供功能.

使用递归.
如果提供的参数（`args`）的数量足够，则调用传递的函数`fn`.
否则，返回一个curried函数`fn`，它需要其余的参数.
如果你想要一个接受可变数量的参数的函数（一个可变函数，例如`Math.min（）`），你可以选择将参数个数传递给第二个参数`arity`.

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

创建一个去抖动函数，该函数延迟调用所提供的函数，直到自上次调用它以来至少经过了“ms”毫秒.

 每次调用debounced函数时，使用`clearTimeout（）`清除当前的挂起超时，并使用`setTimeout（）`创建一个新的超时，延迟调用函数，直到至少经过`ms`毫秒.  使用`Function.prototype.apply（）`将`this`上下文应用于函数并提供必要的参数.
省略第二个参数`ms`，将超时设置为默认值0 ms.

```js
const debounce =（fn，ms = 0）=&gt; {
  let timeoutId;
  return函数（... args）{
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
    的console.log（window.innerWidth）;
    的console.log（window.innerHeight）;
  }, 250)
 ）;  //最多每250ms记录一次窗口尺寸
```

</details>


### defer

延迟调用函数，直到当前调用堆栈清除为止.

 使用超时为1ms的`setTimeout（）`将新事件添加到浏览器事件队列，并允许渲染引擎完成其工作.  使用spread（`...`）运算符为函数提供任意数量的参数.

```js
const defer =（fn，... args）=&gt; setTimeout（fn，1，... args）;
```

<details>
<summary>Examples</summary>

```js
//示例A：
 延迟（console.log，&#39;a&#39;），console.log（&#39;b&#39;）;  //记录&#39;b&#39;然后&#39;a&#39;

//例B：
document.querySelector('#someElement').innerHTML = 'Hello';
 longRunningFunction（）;  //浏览器在完成之前不会更新HTML
 推迟（longRunningFunction）;  //浏览器将更新HTML然后运行该功能
```

</details>


### delay

在`wait`毫秒后调用提供的函数.

使用`setTimeout（）`来延迟执行`fn`.
Use the spread (`...`) operator to supply the function with an arbitrary number of arguments.

```js
const delay =（fn，wait，... args）=&gt; setTimeout（fn，wait，... args）;
```

<details>
<summary>Examples</summary>

```js
delay(
  function（text）{
    的console.log（文本）;
  },
  1000,
  &#39;后来&#39;
 ）;  //一秒后“稍后”记录.
```

</details>


### functionName

记录函数的名称.

使用`console.debug（）`和传递方法的`name`属性将方法的名称记录到控制台的`debug`通道.

```js
const functionName = fn =&gt;（console.debug（fn.name），fn）;
```

<details>
<summary>Examples</summary>

```js
 使用functionName（Math.max）;  // max（登录控制台的调试通道）
```

</details>


### hz

返回每秒执行函数的次数. 
`hz`是`hertz`的单位，频率单位定义为每秒一个周期.

使用`performance.now（）`来获取迭代循环之前和之后的毫秒差异，以计算执行函数`iterations`次所经过的时间. 
通过将毫秒转换为秒并将其除以经过的时间来返回每秒的周期数. 
省略第二个参数`iterations`，使用默认的100次迭代.

```js
const hz =（fn，iterations = 100）=&gt; {
  const before = performance.now（）;
  for（let i = 0; i &lt;iterations; i ++）fn（）;
  return（1000 * iterations）/（performance.now（） -  before）;
};
```

<details>
<summary>Examples</summary>

```js
// 10,000元素数组
const numbers = Array(10000)
  .填（）
  .map（（_，i）=&gt; i）;

//具有相同目标的测试函数：总结数组中的元素
const sumReduce =（）=&gt; numbers.reduce（（acc，n）=&gt; acc + n，0）;
const sumForLoop =（）=&gt; {
  设sum = 0;
  for（let i = 0; i &lt;numbers.length; i ++）sum + = numbers [i];
  回报;
};

//`sumForLoop`快了近10倍
 Math.round（HZ（sumReduce））;  // 572
 Math.round（HZ（sumForLoop））;  // 4784
```

</details>



返回memoized（缓存）函数.

通过实例化一个新的`Map`对象来创建一个空缓存.
 返回一个函数，它通过首先检查函数的特定输入值的输出是否已经被缓存，将一个参数提供给memoized函数，如果没有则存储并返回它.  必须使用`function`关键字，以便允许memoized函数在必要时更改其`this`上下文.
允许通过将其设置为返回函数的属性来访问`cache`.

```js
const memoize = fn =&gt; {
  const cache = new Map（）;
  const cached = function（val）{
     return cache.has（val）？  cache.get（val）：cache.set（val，fn.call（this，val））&amp;&amp; cache.get（val）;
  };
  cached.cache = cache;
  返回缓存;
};
```

<details>
<summary>Examples</summary>

```js
//参见`anagrams`片段.
const anagramsCached = memoize（anagrams）;
 anagramsCached（ &#39;的javascript&#39;）;  // 需要很长的时间
 anagramsCached（ &#39;的javascript&#39;）;  //几乎立即返回，因为它现在已缓存
 的console.log（anagramsCached.cache）;  //缓存的anagrams地图
```

</details>


### negate

否定谓词函数.

获取谓词函数并使用其参数将not运算符（`！`）应用于它.

```js
const negate = func =&gt;（... args）=&gt;！func（... args）;
```

<details>
<summary>Examples</summary>

```js
 [1,2,3,4,5,6] .filter（否定（n =&gt; n％2 === 0））;  // [1,3,5]
```

</details>


### once

确保只调用一次函数.

 使用一个闭包，使用一个标志``called`，并在第一次调用该函数时将其设置为`true`，防止再次调用它.  为了允许函数更改其`this`上下文（例如在事件监听器中），必须使用`function`关键字，并且所提供的函数必须应用上下文.
允许使用rest / spread（`...`）运算符为函数提供任意数量的参数.

```js
const once = fn =&gt; {
  let called = false;
  return函数（... args）{
    if（call）return;
    叫=真;
    return fn.apply（this，args）;
  };
};
```

<details>
<summary>Examples</summary>

```js
const startApp = function（event）{
   console.log（this，event）;  // document.body，MouseEvent
};
 document.body.addEventListener（&#39;click&#39;，once（startApp））;  //只在点击时运行`startApp`
```

</details>


### partial

创建一个函数，调用`fn`并将`partials`添加到它接收的参数之前.

使用扩展运算符（```）将`partials`添加到`fn`的参数列表中.

```js
const partial =（fn，... partials）=&gt;（... args）=&gt; fn（... partials，... args）;
```

<details>
<summary>Examples</summary>

```js
const greet =（问候，姓名）=&gt;问候+&#39;&#39;+姓名+&#39;！&#39;;
const greetHello = partial（greet，&#39;Hello&#39;）;
 greetHello（ &#39;约翰&#39;）;  // &#39;你好约翰！&#39;
```

</details>


### partialRight

创建一个函数，调用`fn`并将`partials`附加到它接收的参数上.

使用扩展运算符（```）将`partials`附加到`fn`的参数列表中.

```js
const partialRight =（fn，... partials）=&gt;（... args）=&gt; fn（... args，... partials）;
```

<details>
<summary>Examples</summary>

```js
const greet =（问候，姓名）=&gt;问候+&#39;&#39;+姓名+&#39;！&#39;;
const greetJohn = partialRight（greet，&#39;John&#39;）;
 greetJohn（ &#39;你好&#39;）;  // &#39;你好约翰！&#39;
```

</details>


### runPromisesInSeries

运行一系列承诺串联.

使用`Array.prototype.reduce（）`创建一个promise链，每个promise在解析时返回下一个promise.

```js
const runPromisesInSeries = ps =&gt; ps.reduce（（p，next）=&gt; p.then（next），Promise.resolve（））;
```

<details>
<summary>Examples</summary>

```js
const delay = d =&gt; new Promise（r =&gt; setTimeout（r，d））;
 runPromisesInSeries（[（）=&gt; delay（1000），（）=&gt; delay（2000）]）;  //按顺序执行每个承诺，总共需要3秒钟才能完成
```

</details>


### sleep

延迟异步函数的执行.

延迟执行`async`函数的一部分，通过将其置于睡眠状态，返回一个`Promise`.

```js
const sleep = ms =&gt; new Promise（resolve =&gt; setTimeout（resolve，ms））;
```

<details>
<summary>Examples</summary>

```js
async function sleepyWork（）{
  console.log（“我要睡1秒钟.”）;
  等待睡眠（1000）;
  console.log（&#39;我在1秒后醒来.&#39;）;
}
```

</details>



创建一个限制函数，每个`wait`毫秒最多只调用一次提供的函数

使用`setTimeout（）`和`clearTimeout（）`来限制给定的方法`fn`.
使用`Function.prototype.apply（）`将`this`上下文应用于函数并提供必要的`参数`.
使用`Date.now（）`来跟踪上次调用限制函数的时间.
省略第二个参数`wait`，将超时设置为默认值0 ms.

```js
const throttle =（fn，wait）=&gt; {
  让inThrottle，lastFn，lastTime;
  return function（）{
    const context = this，
      args = arguments;
    if（！inThrottle）{
      fn.apply（context，args）;
      lastTime = Date.now（）;
      inThrottle = true;
    } else {
      clearTimeout（lastFn）;
      lastFn = setTimeout（function（）{
        if（Date.now（） -  lastTime&gt; = wait）{
          fn.apply（context，args）;
          lastTime = Date.now（）;
        }
      }，Math.max（wait  - （Date.now（） -  lastTime），0））;
    }
  };
};
```

<details>
<summary>Examples</summary>

```js
window.addEventListener(
  “调整大小”，
  油门（功能（evt）{
    的console.log（window.innerWidth）;
    的console.log（window.innerHeight）;
  }, 250)
 ）;  //最多每250ms记录一次窗口尺寸
```

</details>


### times

迭代回调`n`次

使用`Function.call（）`来调用`fn``n`次或直到它返回`false`.
省略最后一个参数`context`，以使用`undefined`对象（或非严格模式下的全局对象）.

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
 的console.log（输出）;  // 01234
```

</details>


### uncurry

取消深度为“n”的功能.

返回一个可变函数.
在提供的参数上使用`Array.prototype.reduce（）`来调用函数的每个后续curry级别.
如果提供的参数的`length`小于`n`则抛出错误.
否则，使用`Array.prototype.slice（0，n）`使用适当数量的参数调用`fn`.
省略第二个参数，`n`，以证明深度为“1”.

```js
const uncurry =（fn，n = 1）=&gt;（... args）=&gt; {
  const next = acc =&gt; args =&gt; args.reduce（（x，y）=&gt; x（y），acc）;
  if（n&gt; args.length）抛出新的RangeError（&#39;Arguments too few！&#39;）;
  return next(fn)(args.slice(0, n));
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

使用`while`循环和`Array.prototype.push（）`重复调用该函数，直到它返回`false`.
迭代器函数接受一个参数（`seed`）并且必须始终返回一个带有两个元素（[`value`，`nextSeed`]）或`false`的数组来终止.

```js
const unfold =（fn，seed）=&gt; {
  let result = []，
    val = [null，seed];
  while（（val = fn（val [1]）））result.push（val [0]）;
  返回结果;
};
```

<details>
<summary>Examples</summary>

```js
var f = n =&gt;（n&gt; 50？false：[ -  n，n + 10]）;
 展开（f，10）;  // [-10，-20，-30，-40，-50]
```

</details>


### when

 针对谓词函数测试值“x”.  如果是&#39;true`，则返回`fn（x）`.  否则，返回`x`. 

返回一个期望单个值`x`的函数，它返回基于`pred`的适当值.

```js
const when =（pred，whenTrue）=&gt; x =&gt;（pred（x）？whenTrue（x）：x）;
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

检查两个数字是否大致相等.

使用`Math.abs（）`将两个值的绝对差值与&#39;epsilon`进行比较.
省略第三个参数`epsilon`，使用默认值`0.001`.

```js
const approxEqual =（v1，v2，epsilon = 0.001）=&gt; Math.abs（v1  -  v2）&lt;epsilon;
```

<details>
<summary>Examples</summary>

```js
 大约等于（Math.PI / 2.0,1.5708）;  //真
```

</details>


### average

返回两个或更多数字的平均值.

使用`Array.prototype.reduce（）`将每个值添加到累加器，用值“0”初始化，除以数组的“长度”.

```js
const average =（... nums）=&gt; nums.reduce（（acc，val）=&gt; acc + val，0）/ nums.length;
```

<details>
<summary>Examples</summary>

```js
 平均值（... [1,2,3]）;  // 2
 平均（1,2,3）;  // 2
```

</details>


### averageBy

使用提供的函数将每个元素映射到值后，返回数组的平均值.

使用`Array.prototype.map（）`将每个元素映射到`fn`，`Array.prototype.reduce（）`返回的值，将每个值添加到累加器，初始化为值&#39;0`，除通过数组的`length`.

```js
const averageBy =（arr，fn）=&gt;
  arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]）.reduce（（acc，val）=&gt; acc + val，0）/
  arr.length;
```

<details>
<summary>Examples</summary>

```js
 averageBy（[{n：4}，{n：2}，{n：8}，{n：6}]或=&gt; on）;  // 5
 averageBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 5
```

</details>


### binomialCoefficient

计算两个整数“n”和“k”的二项式系数.

使用`Number.isNaN（）`来检查两个值中的任何一个是否为“NaN”.
检查`k`是否小于&#39;0`，大于或等于`n`，等于&#39;1`或&#39;n  -  1`并返回适当的结果.
检查`n  -  k`是否小于`k`并相应地切换它们的值.
从“2”到“k”循环并计算二项式系数.
使用`Math.round（）`来计算计算中的舍入误差.

```js
const binomialCoefficient =（n，k）=&gt; {
  if（Number.isNaN（n）|| Number.isNaN（k））返回NaN;
  if（k &lt;0 || k&gt; n）返回0;
  if（k === 0 || k === n）返回1;
  if（k === 1 || k === n  -  1）返回n;
  if (n - k < k) k = n - k;
  让res = n;
  for（let j = 2; j &lt;= k; j ++）res * =（n  -  j + 1）/ j;
  返回Math.round（res）;
};
```

<details>
<summary>Examples</summary>

```js
 二项式效率（8,2）;  // 28
```

</details>


### clampNumber

在边界值“a”和“b”指定的包含范围内钳位`num`.

如果`num`落在该范围内，则返回`num`.
否则，返回范围内的最近数字.

```js
const clampNumber =（num，a，b）=&gt; Math.max（Math.min（num，Math.max（a，b）），Math.min（a，b））;
```

<details>
<summary>Examples</summary>

```js
 clampNumber（2,3,5）;  // 3
 clampNumber（1，-1，-5）;  // -1
```

</details>


### degreesToRads

将角度从度数转换为弧度.

使用`Math.PI`和弧度公式将角度从度数转换为弧度.

```js
const degreesToRads = deg =&gt;（deg * Math.PI）/ 180.0;
```

<details>
<summary>Examples</summary>

```js
 degreesToRads（90.0）;  // ~1.5708
```

</details>


### digitize

将数字转换为数字数组.

将数字转换为字符串，使用扩展运算符（`...`）构建数组.
使用`Array.prototype.map（）`和`parseInt（）`将每个值转换为整数.

```js
const digitize = n =&gt; [...`$ {n}`].map（i =&gt; parseInt（i））;
```

<details>
<summary>Examples</summary>

```js
 数字化（123）;  // [1,2,3]
```

</details>


### distance

返回两点之间的距离.

使用`Math.hypot（）`计算两点之间的欧几里德距离.

```js
const distance =（x0，y0，x1，y1）=&gt; Math.hypot（x1  -  x0，y1  -  y0）;
```

<details>
<summary>Examples</summary>

```js
 距离（1,1,2,3）;  // 2.23606797749979
```

</details>



使用the计算两个或更多对手之间的新评级 [Elo rating system](https://en.wikipedia.org/wiki/Elo_rating_system) .  它需要一个数组
预评级并返回包含评级后的数组.
阵列应该从最佳表演者到最差表演者（胜利者 - &gt;失败者）订购.

使用指数`**`运算符和数学运算符来计算预期得分（获胜的机会）.
每个对手并计算每个对手的新评级.
循环评级，使用每个排列以成对方式计算每个玩家的后Elo评级. 
省略第二个参数以使用32的默认`kFactor`.

```js
const elo =（[... ratings]，kFactor = 32，selfRating）=&gt; {
  const [a，b] =评级;
  const expectedScore =（self，opponent）=&gt; 1 /（1 + 10 **（（对手 - 自我）/ 400））;
  const newRating =（rating，i）=&gt;
    （selfRating || rating）+ kFactor *（i  -  expectedScore（i？a：b，i？b：a））;
  if（ratings.length === 2）返回[newRating（a，1），newRating（b，0）];

  for（let i = 0，len = ratings.length; i &lt;len; i ++）{
    让j = i;
    while（j &lt;len  -  1）{
      J ++;
      [ratings [i]，rating [j]] = elo（[ratings [i]，rating [j]]，kFactor）;
    }
  }
  回报率;
};
```

<details>
<summary>Examples</summary>

```js
//标准1v1s
 链接（[1200,1200]）;  // [1216,1184]
 link（[1200,1200]，64）;  // [1232,1168]
// 4名球员FFA，排名相同
 elo（[1200,1200,1200,1200]）.map（Math.round）;  // [1246,1215,1185,1154]
/*
对于团队而言，每个评级都可以根据自己团队的平均评分进行调整
对方球队的平均评分，将得分加到他们的队伍中
通过提供它作为第三个参数来拥有个人评级.
*/
```

</details>


### factorial

计算数字的阶乘.

使用递归.
如果`n`小于或等于`1`，则返回`1`.
否则，返回`n`和&#39;n  -  1`的阶乘的乘积.
如果`n`是负数，则抛出异常.

```js
const factorial = n =&gt;
  n &lt;0
    ? (() => {
      抛出新的TypeError（&#39;不允许使用负数！&#39;）;
    })()
    ：n &lt;= 1
      ? 1
      ：n *阶乘（n  -  1）;
```

<details>
<summary>Examples</summary>

```js
 阶乘（6）;  // 720
```

</details>


### fibonacci

生成一个包含Fibonacci序列的数组，直到第n个项.

创建一个特定长度的空数组，初始化前两个值（“0”和“1”）.
使用`Array.prototype.reduce（）`将值添加到数组中，使用最后两个值的总和，前两个值除外.

```js
const fibonacci = n =&gt;
  Array.from（{length：n}）.reduce（
    （acc，val，i）=&gt; acc.concat（i&gt; 1？acc [i  -  1] + acc [i  -  2]：i），
    []
  );
```

<details>
<summary>Examples</summary>

```js
 斐波纳契（6）;  // [0,1,1,2,3,5]
```

</details>


### gcd

计算两个或多个数字/数组之间的最大公约数.

内部`_gcd`函数使用递归.
 基本情况是`y`等于&#39;0`.  在这种情况下，返回`x`.
否则，返回`y`的GCD和除法的剩余部分`x / y`.

```js
const gcd =（... arr）=&gt; {
  const _gcd =（x，y）=&gt;（！和？x：gcd（y，x％y））;
  return [... arr] .reduce（（a，b）=&gt; _gcd（a，b））;
};
```

<details>
<summary>Examples</summary>

```js
 gcd（8,36）;  // 4
 gcd（...... [12,8,32]）;  // 4
```

</details>


### geometricProgression

初始化一个数组，其中包含指定范围内的数字，其中`start`和`end`是包含的，两个术语之间的比率是`step`.
如果`step`等于`1`，则返回错误.

使用`Array.from（）`，`Math.log（）`和`Math.floor（）`来创建一个所需长度的数组，`Array.prototype.map（）`来填充所需的值.范围.
省略第二个参数`start`，使用默认值`1`.
省略第三个参数`step`，使用默认值`2`.

```js
const geometricProgression =（end，start = 1，step = 2）=&gt;
  Array.from（{length：Math.floor（Math.log（end / start）/ Math.log（step））+ 1}）.map（
    （v，i）=&gt; start * step ** i
  );
```

<details>
<summary>Examples</summary>

```js
 geometricProgression（256）;  // [1,2,4,8,16,32,64,128,256]
 geometricProgression（256,3）;  // [3,6,12,24,48,96,192]
 geometricProgression（256,1,4）;  // [1,4,16,64,256]
```

</details>


### hammingDistance

计算两个值之间的汉明距离.

使用XOR运算符（`^`）来查找两个数字之间的位差，使用`toString（2）`转换为二进制字符串.
使用`match（/ 1 / g）`计算并返回字符串中`1`s的数量.

```js
const hammingDistance =（num1，num2）=&gt;（（num1 ^ num2）.toString（2）.match（/ 1 / g）||&#39;&#39;）.length;
```

<details>
<summary>Examples</summary>

```js
 汉明距离（2,3）;  // 1
```

</details>


### inRange

检查给定数字是否在给定范围内.

使用算术比较来检查给定数字是否在指定范围内.
如果未指定第二个参数`end`，则认为范围是从“0”到“start”.

```js
const inRange =（n，start，end = null）=&gt; {
  if（结束&amp;&amp;开始&gt;结束）[结束，开始] = [开始，结束];
   return end == null？  n&gt; = 0 &amp;&amp; n &lt;start：n&gt; = start &amp;&amp; n &lt;end;
};
```

<details>
<summary>Examples</summary>

```js
 inRange（3,2,5）;  //真
 inRange（3,4）;  //真
 inRange（2,3,5）;  //假
 inRange（3,2）;  //假
```

</details>


### isDivisible

检查第一个数字参数是否可被第二个数字整除.

使用模运算符（`％`）来检查余数是否等于&#39;0&#39;.

```js
const isDivisible =（dividend，divisor）=&gt; dividend％divisor === 0;
```

<details>
<summary>Examples</summary>

```js
 isDivisible（6,3）;  //真
```

</details>


### isEven

如果给定的数字是偶数，则返回“true”，否则返回“false”.

使用模数（`％`）运算符检查数字是奇数还是偶数.
如果数字是偶数则返回“true”，如果数字是奇数则返回“false”.

```js
成本ISEVEN NUM =&gt; NUM 2％=== 0;
```

<details>
<summary>Examples</summary>

```js
 ISEVEN（3）;  //假
```

</details>


### isNegativeZero

检查给定值是否等于负零（`-0`）.

检查传递的值是否等于“0”，如果“1”除以值等于“-Infinity”.

```js
const isNegativeZero = val =&gt; val === 0 &amp;&amp; 1 / val === -Infinity;
```

<details>
<summary>Examples</summary>

```js
 isNegativeZero（-O）;  //真
 isNegativeZero（0）;  //假
```

</details>


### isPrime

检查提供的整数是否为素数.

检查从“2”到给定数字的平方根的数字.
如果其中任何一个除以给定的数字，则返回`false`，否则返回`true`，除非该数字小于&#39;2`.

```js
const isPrime = num =&gt; {
  const boundary = Math.floor（Math.sqrt（num））;
  for（is i = 2; i &lt;= boundary; i ++）if（num％i === 0）return false;
  返回是否&gt; = 2;
};
```

<details>
<summary>Examples</summary>

```js
 isPrime（11）;  //真
```

</details>


### lcm

返回两个或多个数字的最小公倍数.

使用最大公约数（GCD）公式和`lcm（x，y）= x * y / gcd（x，y）`来确定最小公倍数.
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
 lcm（12,7）;  // 84
 lcm（...... [1,3,4,5]）;  // 60
```

</details>



实施 [Luhn Algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm) 用于验证各种识别号码，例如信用卡号码，IMEI号码，国家提供商标识号码等.

使用`String.prototype.split（&#39;&#39;）`，`Array.prototype.reverse（）`和`Array.prototype.map（）`结合`parseInt（）`来获取数字数组.
使用`Array.prototype.splice（0,1）`获取最后一位数.
使用`Array.prototype.reduce（）`来实现Luhn算法.
如果`sum`可以被&#39;10&#39;整除，则返回&#39;true`，否则返回`false`.


```js
const luhnCheck = num =&gt; {
  让ARR =（NUM + &#39;&#39;）
    .分裂（&#39;&#39;）
    .相反（）
    .map（x =&gt; parseInt（x））;
  let lastDigit = arr.splice（0,1）[0];
  let sum = arr.reduce（（acc，val，i）=&gt;（i％2！== 0？acc + val：acc +（（val * 2）％9）|| 9），0）;
  sum + = lastDigit;
  返还总和％10 === 0;
};
```

<details>
<summary>Examples</summary>

```js
 luhnCheck（ &#39;4485275742308327&#39;）;  //真
 luhnCheck（6011329933655299）;  //假
 luhnCheck（123456789）;  //假
```

</details>


### mapNumRange

将数字从一个范围映射到另一个范围.

从`inMin`-`inMax`返回`outMin` -`outMax`之间的`num`映射.

```js
const mapNumRange =（num，inMin，inMax，outMin，outMax）=&gt;
  （（num  -  inMin）*（outMax  -  outMin））/（inMax  -  inMin）+ outMin;
```

<details>
<summary>Examples</summary>

```js
 mapNumRange（5,0,10,0,100）;  // 50
```

</details>


### maxBy

在使用提供的函数将每个元素映射到值之后，返回数组的最大值.

使用`Array.prototype.map（）`将每个元素映射到`fn`，`Math.max（）`返回的值，以获得最大值.

```js
const maxBy =（arr，fn）=&gt; Math.max（... arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]））;
```

<details>
<summary>Examples</summary>

```js
 maxBy（[{n：4}，{n：2}，{n：8}，{n：6}]或=&gt; on）;  // 8
 maxBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 8
```

</details>


### median

返回数组数组的中位数.

找到数组的中间部分，使用`Array.prototype.sort（）`对值进行排序.
如果`length`是奇数，则返回中点处的数字，否则返回两个中间数的平均值.

```js
const median = arr =&gt; {
  const mid = Math.floor（arr.length / 2），
    nums = [... arr] .sort（（a，b）=&gt; a  -  b）;
   return arr.length％2！== 0？  nums [mid] :( nums [mid  -  1] + nums [mid]）/ 2;
};
```

<details>
<summary>Examples</summary>

```js
 中位数（[5,6,50,1，-5]）;  // 5
```

</details>


### midpoint

计算两对（x，y）点之间的中点.

对数组进行构造以获得`x1`，`y1`，`x2`和`y2`，通过将两个端点的总和除以“2”来计算每个维度的中点.

```js
const midpoint =（[x1，y1]，[x2，y2]）=&gt; [（x1 + x2）/ 2，（y1 + y2）/ 2];
```

<details>
<summary>Examples</summary>

```js
 中点（[2,2]，[4,4]）;  // [3,3]
 中点（[4,4]，[6,6]）;  // [5,5]
 中点（[1,3]，[2,4]）;  // [1.5,3.5]
```


</details>


### minBy

使用提供的函数将每个元素映射到值后，返回数组的最小值.

使用`Array.prototype.map（）`将每个元素映射到`fn`，`Math.min（）`返回的值，以获得最小值.

```js
const minBy =（arr，fn）=&gt; Math.min（... arr.map（typeof fn ===&#39;function&#39;？fn：val =&gt; val [fn]））;
```

<details>
<summary>Examples</summary>

```js
 minBy（[{n：4}，{n：2}，{n：8}，{n：6}]，o =&gt; on）;  // 2
 minBy（[{n：4}，{n：2}，{n：8}，{n：6}]，&#39;n&#39;）;  // 2
```

</details>


### percentile

使用百分位公式计算给定数组中的数量是否小于或等于给定值.

使用`Array.prototype.reduce（）`来计算低于该值的数量以及有多少是相同的值并应用百分位公式.

```js
const percentile =（arr，val）=&gt;
  （100 * arr.reduce（（acc，v）=&gt; acc +（v &lt;val？1：0）+（v === val？0.5：0），0））/ arr.length;
```

<details>
<summary>Examples</summary>

```js
 百分位数（[1,2,3,4,5,6,7,8,9,10]，6）;  // 55
```

</details>


### powerset

返回给定数字数组的powerset.

使用`Array.prototype.reduce（）`结合`Array.prototype.map（）`迭代元素并组合成一个包含所有组合的数组.

```js
const powerset = arr =&gt; arr.reduce（（a，v）=&gt; a.concat（a.map（r =&gt; [v] .concat（r））），[[]]）;
```

<details>
<summary>Examples</summary>

```js
 powerset（[1,2]）;  // [[]，[1]，[2]，[2,1]]
```

</details>


### primes

使用Eratosthenes的Sieve生成达到给定数量的素数.

 生成一个从“2”到给定数字的数组.  使用`Array.prototype.filter（）`过滤掉从“2”到所提供数字的平方根的任何数字可被整除的值.

```js
CONST第一NUM =&gt; {
  let arr = Array.from（{length：num  -  1}）.map（（x，i）=&gt; i + 2），
    sqroot = Math.floor（Math.sqrt（num）），
    numsTillSqroot = Array.from（{length：sqroot  -  1}）.map（（x，i）=&gt; i + 2）;
  numsTillSqroot.forEach（x =&gt;（arr = arr.filter（y =&gt; y％x！== 0 || y === x）））;
  返回
};
```

<details>
<summary>Examples</summary>

```js
 保险费（10）;  // [2,3,5,7]
```

</details>


### radsToDegrees

将角度从弧度转换为度数.

使用`Math.PI`和弧度度数公式将角度从弧度转换为度数.

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

返回指定范围内的n个随机整数的数组.

使用`Array.from（）`创建一个特定长度的空数组，`Math.random（）`来生成一个随机数并将其映射到所需的范围，使用`Math.floor（）`使它成为一个整数.

```js
const randomIntArrayInRange =（min，max，n = 1）=&gt;
  Array.from（{length：n}，（）=&gt; Math.floor（Math.random（）*（max  -  min + 1））+ min）;
```

<details>
<summary>Examples</summary>

```js
 randomIntArrayInRange（12,35,10）;  // [34,14,27,17,30,27,20,26,21,14]
```

</details>


### randomIntegerInRange

返回指定范围内的随机整数.

使用`Math.random（）`生成一个随机数并将其映射到所需的范围，使用`Math.floor（）`使其成为整数.

```js
const randomIntegerInRange =（min，max）=&gt; Math.floor（Math.random（）*（max  -  min + 1））+ min;
```

<details>
<summary>Examples</summary>

```js
 randomIntegerInRange（0,5）;  // 2
```

</details>


### randomNumberInRange

返回指定范围内的随机数.

使用`Math.random（）`生成一个随机值，使用乘法将其映射到所需的范围.

```js
const randomNumberInRange =（min，max）=&gt; Math.random（）*（max  -  min）+ min;
```

<details>
<summary>Examples</summary>

```js
 randomNumberInRange（2,10）;  // 6.0211363285087005
```

</details>


### round

将数字舍入到指定的数字位数.

使用`Math.round（）`和模板文字将数字四舍五入到指定的位数.
省略第二个参数，`decimals`来舍入为整数.

```js
const round =（n，decimals = 0）=&gt; Number（`$ {Math.round（`$ {n} e $ {decimals}`）} e  -  $ {decimals}`）;
```

<details>
<summary>Examples</summary>

```js
 回合（1.005,2）;  // 1.01
```

</details>


### sdbm

Hashes the input string into a whole number.

使用`String.prototype.split（&#39;&#39;）`和`Array.prototype.reduce（）`来创建输入字符串的哈希，利用位移.

```js
const sdbm = str =&gt; {
  let arr = str.split（&#39;&#39;）;
  return arr.reduce（
    （hashCode，currentVal）=&gt;
      （hashCode = currentVal.charCodeAt（0）+（hashCode &lt;&lt; 6）+（hashCode &lt;&lt; 16） -  hashCode），
    0
  );
};
```

<details>
<summary>Examples</summary>

```js
sdbm('name'); // -3521204949
```

</details>


### standardDeviation

返回数字数组的标准偏差.

使用`Array.prototype.reduce（）`来计算均值，方差和值的方差之和，值的方差，然后
确定标准偏差.
您可以省略第二个参数以获取样本标准偏差或将其设置为“true”以获得总体标准偏差.

```js
const standardDeviation =（arr，usePopulation = false）=&gt; {
  const mean = arr.reduce（（acc，val）=&gt; acc + val，0）/ arr.length;
  返回Math.sqrt（
    arr.reduce（（acc，val）=&gt; acc.concat（（val  -  mean）** 2），[]）.reduce（（acc，val）=&gt; acc + val，0）/
      （arr.length  - （usePopulation？0：1））
  );
};
```

<details>
<summary>Examples</summary>

```js
 standardDeviation（[10,2,38,23,38,23,21]）;  // 13.284434142114991（样本）
 standardDeviation（[10,2,38,23,38,23,21]，true）;  // 12.29899614287479（人口）
```

</details>


### sum

返回两个或更多数字/数组的总和.

使用`Array.prototype.reduce（）`将每个值添加到累加器，使用值“0”初始化.

```js
const sum =（... arr）=&gt; [... arr] .reduce（（acc，val）=&gt; acc + val，0）;
```

<details>
<summary>Examples</summary>

```js
 总和（1,2,3,4）;  // 10
 总和（...... [1,2,3,4]）;  // 10
```

</details>


### sumBy

在使用提供的函数将每个元素映射到值之后，返回数组的总和.

使用`Array.prototype.map（）`将每个元素映射到`fn`，`Array.prototype.reduce（）`返回的值，将每个值添加到累加器，用值“0”初始化.

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

返回从“start”到“end”（包括两者）的所有数字的幂的总和.

使用`Array.prototype.fill（）`创建一个包含目标范围内所有数字的数组，`Array.prototype.map（）`和指数运算符（`**`）将它们提升为`power`和`Array.prototype.reduce（）`将它们加在一起.
省略第二个参数`power`，使用默认幂&#39;2`.
省略第三个参数`start`，使用默认的起始值`1`.

```js
const sumPower =（end，power = 2，start = 1）=&gt;
  数组（结束+ 1  - 开始）
    .fill伪（0）
    .map（（x，i）=&gt;（i + start）** power）
    .reduce（（a，b）=&gt; a + b，0）;
```

<details>
<summary>Examples</summary>

```js
 sumPower（10）;  // 385
 sumPower（10,3）;  // 3025
 sumPower（10,3,5）;  // 2925
```

</details>


### toSafeInteger

将值转换为安全整数.

使用`Math.max（）`和`Math.min（）`来找到最接近的安全值.
使用`Math.round（）`转换为整数.

```js
const toSafeInteger = num =&gt;
  Math.round（Math.max（Math.min（num，Number.MAX_SAFE_INTEGER），Number.MIN_SAFE_INTEGER））;
```

<details>
<summary>Examples</summary>

```js
 toSafeInteger（&#39;3.2&#39;）;  // 3
 toSafeInteger（无限远）;  // 9007199254740991
```

</details>


### vectorDistance

返回两个向量之间的距离.

使用`Array.prototype.reduce（）`，`Math.pow（）`和`Math.sqrt（）`来计算两个向量之间的欧几里德距离.

```js
const vectorDistance =（... coords）=&gt; {
  let pointLength = Math.trunc（coords.length / 2）;
  让sum = coords
    .slice（0，pointLength）
    .reduce（（acc，val，i）=&gt; acc + Math.pow（val  -  coords [pointLength + i]，2），0）;
  返回Math.sqrt（sum）;
};
```

<details>
<summary>Examples</summary>

```js
 vectorDistance（10,0,5,20,0,10）;  // 11.180339887498949
```

</details>



---

## 📦 Node

### atob

解码使用base-64编码编码的数据字符串.

使用base-64编码为给定字符串创建`Buffer`，并使用`Buffer.toString（&#39;binary&#39;）`返回已解码的字符串.

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

从String对象创建base-64编码的ASCII字符串，其中字符串中的每个字符都被视为二进制数据的字节.

使用二进制编码为给定字符串创建“缓冲区”，并使用“Buffer.toString（&#39;base64&#39;）`返回编码字符串.

```js
const btoa = str =&gt; Buffer.from（str，&#39;binary&#39;）.toString（&#39;base64&#39;）;
```

<details>
<summary>Examples</summary>

```js
 BTOA（ &#39;foobar的&#39;）;  //&#39;Zm9vYmFy&#39;
```

</details>


### colorize

在文本中添加特殊字符以在控制台中以彩色打印（与`console.log（）`结合使用）.

使用模板文字和特殊字符将适当的颜色代码添加到字符串输出中.
对于背景颜色，添加一个特殊字符，用于重置字符串末尾的背景颜色.

```js
const colorize =（... args）=&gt;（{
  黑色：`\ x1b [30m $ {args.join（&#39;&#39;）}`，
  红色：`\ x1b [31m $ {args.join（&#39;&#39;）}`，
  绿色：`\ x1b [32m $ {args.join（&#39;&#39;）}`，
  黄色：`\ x1b [33m $ {args.join（&#39;&#39;）}`，
  blue：`\ x1b [34m $ {args.join（&#39;&#39;）}`，
  品红色：`\ x1b [35m $ {args.join（&#39;&#39;）}`，
  青色：`\ x1b [36m $ {args.join（&#39;&#39;）}`，
  白：`\ x1b [37m $ {args.join（&#39;&#39;）}`，
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
 的console.log（上色（ &#39;富&#39;）红色.）;  //&#39;foo&#39;（红色字母）
 console.log（colorize（&#39;foo&#39;，&#39;bar&#39;）.bgBlue）;  //&#39;foo bar&#39;（蓝色背景）
 console.log（colorize（colorize（&#39;foo&#39;）.yellow，colorize（&#39;foo&#39;）.green）.bgWhite）;  //&#39;foo bar&#39;（黄色字母的第一个单词，绿色字母的第二个单词，两个的白色背景）
```

</details>


### createDirIfNotExists

创建目录（如果该目录不存在）.

使用`fs.existsSync（）`来检查目录是否存在，`fs.mkdirSync（）`来创建它.

```js
const fs = require（&#39;fs&#39;）;
const createDirIfNotExists = dir =&gt;（！fs.existsSync（dir）？fs.mkdirSync（dir）：undefined）;
```

<details>
<summary>Examples</summary>

```js
 createDirIfNotExists（ &#39;试验&#39;）;  //创建目录&#39;test&#39;，如果它不存在
```

</details>


### hasFlags

检查当前进程的参数是否包含指定的标志.

使用`Array.prototype.every（）`和`Array.prototype.includes（）`来检查`process.argv`是否包含所有指定的标志.
使用正则表达式来测试指定的标志是否以`-`或`--`作为前缀，并相应地加上前缀.

```js
const hasFlags =（... flags）=&gt;
  flags.every（flag =&gt; process.argv.includes（/ ^  -  {1,2} /.test（flag）？flag：&#39; - &#39;+ flag））;
```

<details>
<summary>Examples</summary>

```js
// node myScript.js -s --test --cool = true
 hasFlags（ &#39; -  S&#39;）;  //真
 hasFlags（&#39; -  test&#39;，&#39;cool = true&#39;，&#39; -  s&#39;）;  //真
 hasFlags（ &#39;特殊&#39;）;  //假
```

</details>


### hashNode

使用.创建值的哈希 [SHA-256](https://en.wikipedia.org/wiki/SHA-2)  算法.  返回一个promise.

使用`crypto` API为给定值创建哈希，使用`setTimeout`来阻止长操作的阻塞，使用`Promise`来为它提供熟悉的接口.

```js
const crypto = require（&#39;crypto&#39;）;
const hashNode = val =&gt;
  新的承诺（resolve =&gt;
    的setTimeout（
      () =>
        解决（
          加密
            .createHash（ &#39;SHA256&#39;）
            .update（VAL）
            .digest（ &#39;六角&#39;）
        ),
      0
    )
  );
```

<details>
<summary>Examples</summary>

```js
 hashNode（JSON.stringify（{a：&#39;a&#39;，b：[1,2,3,4]，foo：{c：&#39;bar&#39;}}））.then（console.log）;  //&#39;04aa106279f5977f59f9067fa9712afc4aedc6f5862a8defc34552d8c7206393&#39;
```

</details>


### isDuplexStream

检查给定参数是否为双工（可读写）流.

检查值是否与`null`不同，使用`typeof`检查值是否为`object`类型，`pipe`属性是否为`function`类型.
另外检查`typeof``_read`，`_ write`和`_readableState`，`_ writeableState`属性是否分别是`function`和`object`.

```js
const isDuplexStream = val =&gt;
  选择！==零&amp;&amp;
  typeof val === 'object' &&
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._read ===&#39;function&#39;&amp;&amp;
  typeof val._readableState ===&#39;object&#39;&amp;&amp;
  typeof val._write ===&#39;function&#39;&amp;&amp;
  typeof val._writableState ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
const Stream = require（&#39;stream&#39;）;
 isDuplexStream（new Stream.Duplex（））;  //真
```

</details>


### isReadableStream

检查给定参数是否为可读流.

检查值是否与`null`不同，使用`typeof`检查值是否为`object`类型，`pipe`属性是否为`function`类型.
另外检查`typeof``_read`和`_readableState`属性是否分别是`function`和`object`.

```js
const isReadableStream = val =&gt;
  选择！==零&amp;&amp;
  typeof val === 'object' &&
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._read ===&#39;function&#39;&amp;&amp;
  typeof val._readableState ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isReadableStream（fs.createReadStream（ &#39;的test.txt&#39;））;  //真
```

</details>


### isStream

检查给定的参数是否是流.

检查值是否与`null`不同，使用`typeof`检查值是否为`object`类型，`pipe`属性是否为`function`类型.

```js
const isStream = val =&gt; val！== null &amp;&amp; typeof val ===&#39;object&#39;&amp;&amp; typeof val.pipe ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isStream（fs.createReadStream（ &#39;的test.txt&#39;））;  //真
```

</details>


### isTravisCI

检查当前环境是否正常 [Travis CI](https://travis-ci.org/).

检查当前环境是否具有`TRAVIS`和`CI`环境变量（[reference](https://docs.travis-ci.com/user/environment-variables/#Default-Environment-Variables)).

```js
const isTravisCI =（）=&gt;&#39;process TR中的&#39;TRAVIS&#39;和process.env中的&#39;CI&#39;;
```

<details>
<summary>Examples</summary>

```js
 isTravisCI（）;  // true（如果代码在Travis CI上运行）
```

</details>


### isWritableStream

检查给定的参数是否是可写流.

检查值是否与`null`不同，使用`typeof`检查值是否为`object`类型，`pipe`属性是否为`function`类型.
另外检查`typeof``__write`和`_writableState`属性是否分别是`function`和`object`.

```js
const isWritableStream = val =&gt;
  选择！==零&amp;&amp;
  typeof val === 'object' &&
  typeof val.pipe ===&#39;function&#39;&amp;&amp;
  typeof val._write ===&#39;function&#39;&amp;&amp;
  typeof val._writableState ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
const fs = require（&#39;fs&#39;）;
 isWritableStream（fs.createWriteStream（ &#39;的test.txt&#39;））;  //真
```

</details>


### JSONToFile

将JSON对象写入文件.

使用`fs.writeFile（）`，模板文字和`JSON.stringify（）`将`json`对象写入`.json`文件.

```js
const fs = require（&#39;fs&#39;）;
const JSONToFile =（obj，filename）=&gt;
  fs.writeFile（`$ {filename} .json`，JSON.stringify（obj，null，2））;
```

<details>
<summary>Examples</summary>

```js
 JSONToFile（{test：&#39;传递&#39;}，&#39;testJsonFile&#39;）;  //将对象写入&#39;testJsonFile.json&#39;
```

</details>


### readFileLines

返回指定文件中的行数组.

在`fs`节点包中使用`readFileSync`函数从文件创建`Buffer`.
使用`toString（encoding）`函数将缓冲区转换为字符串.
通过逐行分割文件内容（每个`\ n`）从文件内容创建一个数组.

```js
const fs = require（&#39;fs&#39;）;
const readFileLines = filename =&gt;
  FS
    .readFileSync（文件名）
    的ToString（ &#39;UTF8&#39;）
    .split（ &#39;\ n&#39;）;
```

<details>
<summary>Examples</summary>

```js
/*
test.txt的内容：
  一号线
  2号线
  3号线
  ___________________________
*/
let arr = readFileLines（&#39;test.txt&#39;）;
 的console.log（ARR）;  // [&#39;line1&#39;，&#39;line2&#39;，&#39;line3&#39;]
```


</details>


### untildify

将波形路径转换为绝对路径.

使用带有正则表达式的`String.prototype.replace（）`和`OS.homedir（）`用主目录替换路径起点的`~`.

```js
const untildify = str =&gt; str.replace（/ ^〜（$ | \ / | \\）/，`$ {require（&#39;os&#39;）.homedir（）} $ 1`）;
```

<details>
<summary>Examples</summary>

```js
 untildify（ &#39;〜/节点&#39;）;  //&#39;/ Users / aUser / node&#39;
```

</details>


### UUIDGeneratorNode

在Node.JS中生成UUID.

使用`crypto` API生成符合的UUID [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) 版本4.

```js
const crypto = require（&#39;crypto&#39;）;
const UUIDGeneratorNode =（）=&gt;
  （[1e7] + -1e3 + -4e3 + -8e3 + -1e11）.replace（/ [018] / g，c =&gt;
    （c ^（crypto.randomBytes（1）[0]＆（15 &gt;&gt;（c / 4））））.toString（16）
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

将对象的方法绑定到对象本身，覆盖现有方法.

使用`Array.prototype.forEach（）`返回一个`function`，它使用`Function.prototype.apply（）`将给定的上下文（`obj`）应用于指定的每个函数的`fn`.

```js
const bindAll =（obj，... fns）=&gt;
  fns.forEach（
    fn =&gt;（
      （f = obj [fn]），
      （obj [fn] = function（）{
        return f.apply（obj）;
      })
    )
  );
```

<details>
<summary>Examples</summary>

```js
var view = {
  标签：&#39;docs&#39;，
  click：function（）{
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
使用`Object.assign（）`和一个空对象（`{}`）来创建原始的浅层克隆.
使用`Object.keys（）`和`Array.prototype.forEach（）`来确定需要深度克隆的键值对.

```js
const deepClone = obj =&gt; {
  let clone = Object.assign（{}，obj）;
  Object.keys（克隆）.forEach（
    key =&gt;（clone [key] = typeof obj [key] ===&#39;object&#39;？deepClone（obj [key]）：obj [key]）
  );
  return Array.isArray（obj）&amp;&amp; obj.length
     ？  （clone.length = obj.length）&amp;&amp; Array.from（clone）
    ：Array.isArray（obj）
       ？  Array.from（OBJ）
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

深度冻结一个物体.

在`instanceof`对象的传递对象的所有未冻结属性上递归调用`Object.freeze（obj）`.

```js
const deepFreeze = obj =&gt;
  Object.keys（OBJ）.forEach（
    prop =&gt;
       ！（obj [prop] instanceof Object）||  Object.isFrozen（obj [prop]）？  null：deepFreeze（obj [prop]）
   ）||  Object.freeze（OBJ）;
```

<details>
<summary>Examples</summary>

```js
&#39;使用严格&#39;;

const o = deepFreeze（[1，[2,3]]）;

 o [0] = 3;  // 不允许
 o [1] [0] = 4;  //也不允许
```

</details>


### deepGet

基于`keys`数组返回嵌套JSON对象中的目标值.

将嵌套JSON对象中所需的键与“Array”进行比较.
使用`Array.prototype.reduce（）`逐个从嵌套的JSON对象中获取值. 
如果密钥存在于object中，则返回目标值，否则返回“null”.

```js
const deepGet =（obj，keys）=&gt; keys.reduce（（xs，x）=&gt;（xs &amp;&amp; xs [x]？xs [x]：null），obj）;
```

<details>
<summary>Examples</summary>

```js
let index = 2;
const dat = {
  foo：{
    [1,2,3]，
    吧：{
      巴兹：[&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
    }
  }
};
 deepGet（data，[&#39;foo&#39;，&#39;foz&#39;，index]）;  //得到3
 deepGet（data，[&#39;foo&#39;，&#39;bar&#39;，&#39;baz&#39;，8，&#39;foz&#39;]）;  // 空值
```

</details>



深度映射对象键.

使用与提供的对象相同的值创建一个对象，并通过为每个键运行提供的函数生成密钥.

使用`Object.keys（obj）`迭代对象的键. 
使用`Array.prototype.reduce（）`使用`fn`创建具有相同值和映射键的新对象.

```js
const deepMapKeys =（obj，f）=&gt;
  Array.isArray（OBJ）
     ？  obj.map（val =&gt; deepMapKeys（val，f））
    ：typeof obj ===&#39;object&#39;
       ？  Object.keys（obj）.reduce（（acc，current）=&gt; {
        const val = obj [current];
        acc [f（current）] =
             val！== null &amp;&amp; typeof val ===&#39;object&#39;？  deepMapKeys（val，f）:( acc [f（current）] = val）;
        返回acc;
      }, {})
      ：obj;
```

<details>
<summary>Examples</summary>

```js
const obj = {
  foo：&#39;1&#39;，
  嵌套：{
    孩子：{
      withArray：[
        {
          grandChild：[&#39;你好&#39;]
        }
      ]
    }
  }
};
const upperKeysObj = deepMapKeys（obj，key =&gt; key.toUpperCase（））;
/*
{
  “foo” 的： “1”，
  “嵌套”：{
    “儿童”：{
      “WITHARRAY”：[
        {
          “GRANDCHILD”：[&#39;你好&#39;]
        }
      ]
    }
  }
}
*/
```

</details>


### defaults

为“未定义”的对象中的所有属性分配默认值.

使用`Object.assign（）`创建一个新的空对象并复制原始对象以维护键顺序，使用`Array.prototype.reverse（）`和扩展运算符`...`来组合左边的默认值到了右边，最后再次使用`obj`来覆盖最初有值的属性.

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

基于给定的键返回嵌套JSON对象中的目标值.

使用`in`运算符检查`obj`中是否存在`target`.
如果找到，则返回`obj [target]`的值，否则使用`Object.values（obj）`和`Array.prototype.reduce（）`以递归方式在每个嵌套对象上调用`dig`，直到第一个匹配键/找到价值对.

```js
const dig =（obj，target）=&gt;
  目标在obj
     ？  OBJ [靶标]
    ：Object.values（obj）.reduce（（acc，val）=&gt; {
      if（acc！== undefined）return acc;
      if（typeof val ===&#39;object&#39;）返回dig（val，target）;
    }，undefined）;
```

<details>
<summary>Examples</summary>

```js
const dat = {
  1级： {
    level2：{
      level3：&#39;一些数据&#39;
    }
  }
};
 挖（数据，&#39;level3&#39;）;  // &#39;一些数据&#39;
 你（数据，&#39;level4&#39;）;  //未定义
```

</details>



在两个值之间执行深度比较以确定它们是否相等.

检查两个值是否相同，如果它们都是具有相同时间的“Date”对象，使用`Date.getTime（）`或者它们都是具有等效值的非对象值（严格比较）.
检查是否只有一个值是“null”或“undefined”或者它们的原型是否不同.
如果没有满足上述条件，请使用`Object.keys（）`检查两个值是否具有相同数量的键，然后使用`Array.prototype.every（）`检查第一个值中的每个键是否存在在第二个中，如果它们是等效的，则通过递归方式调用此方法.

```js
const equals =（a，b）=&gt; {
  if（a === b）返回true;
  if（Date of &amp;&amp; b instanceof Date）返回a.getTime（）=== b.getTime（）;
  if（！a ||！b ||（typeof a！==&#39;object&#39;&amp;&amp; typeof b！==&#39;object&#39;））返回a === b;
  if（a === null || a === undefined || b === null || b === undefined）return false;
  if（a.prototype！== b.prototype）返回false;
  let keys = Object.keys（a）;
  if（keys.length！== Object.keys（b）.length）返回false;
  return keys.every（k =&gt; equals（a [k]，b [k]））;
};
```

<details>
<summary>Examples</summary>

```js
 等于（{a：[2，{e：3}]，b：[4]，c：&#39;foo&#39;}，{a：[2，{e：3}]，b：[4]，c：&#39; foo&#39;}）;  //真
```

</details>


### findKey

 返回满足提供的测试函数的第一个键.  否则返回`undefined`.

 使用`Object.keys（obj）`获取对象的所有属性，`Array.prototype.find（）`来测试每个键值对提供的函数.  回调接收三个参数 - 值，键和对象.

```js
const findKey =（obj，fn）=&gt; Object.keys（obj）.find（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
findKey(
  {
    巴尼：{年龄：36岁，活跃：真}，
    fred：{年龄：40岁，活跃：假}，
    鹅卵石：{年龄：1，活跃：真}
  },
  o =&gt; o [&#39;有效&#39;]
 ）;  //&#39;barney&#39;
```

</details>


### findLastKey

返回满足提供的测试函数的最后一个键.
否则返回`undefined`.

使用`Object.keys（obj）`获取对象的所有属性，`Array.prototype.reverse（）`来反转它们的顺序，使用`Array.prototype.find（）`来测试每个键提供的函数 - 价值对.
回调接收三个参数 - 值，键和对象.

```js
const findLastKey =（obj，fn）=&gt;
  Object.keys（OBJ）
    .相反（）
    .find（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
findLastKey(
  {
    巴尼：{年龄：36岁，活跃：真}，
    fred：{年龄：40岁，活跃：假}，
    鹅卵石：{年龄：1，活跃：真}
  },
  o =&gt; o [&#39;有效&#39;]
 ）;  //&#39;鹅卵石&#39;
```

</details>


### flattenObject

使用键的路径展平对象.

使用递归.
使用`Object.keys（obj）`结合`Array.prototype.reduce（）`将每个叶节点转换为展平路径节点.
如果键的值是一个对象，则该函数使用相应的`prefix`调用自身，以使用`Object.assign（）`创建路径.
否则，它会将相应的前缀键值对添加到累加器对象.
你应该总是省略第二个参数`prefix`，除非你希望每个键都有一个前缀.

```js
const flattenObject =（obj，prefix =&#39;&#39;）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
     const pre = prefix.length？  前缀+&#39;.&#39;  ：&#39;&#39;;
    if（typeof obj [k] ===&#39;object&#39;）Object.assign（acc，flattenObject（obj [k]，pre + k））;
    否则acc [pre + k] = obj [k];
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
 flattenObject（{a：{b：{c：1}}，d：1}）;  // {&#39;abc&#39;：1，d：1}
```

</details>


### forOwn

迭代对象的所有属性，为每个属性运行回调.

 使用`Object.keys（obj）`来获取对象的所有属性，`Array.prototype.forEach（）`来为每个键值对运行提供的函数.  回调接收三个参数 - 值，键和对象.

```js
const forOwn =（obj，fn）=&gt; Object.keys（obj）.forEach（key =&gt; fn（obj [key]，key，obj））;
```

<details>
<summary>Examples</summary>

```js
 forOwn（{foo：&#39;bar&#39;，a：1}，v =&gt; console.log（v））;  //&#39;酒吧&#39;，1
```

</details>


### forOwnRight

反向迭代对象的所有属性，为每个属性运行回调.

 使用`Object.keys（obj）`来获取对象的所有属性，`Array.prototype.reverse（）`来反转它们的顺序，使用`Array.prototype.forEach（）`来为每个键运行提供的函数 - 价值对.  回调接收三个参数 - 值，键和对象.

```js
const forOwnRight =（obj，fn）=&gt;
  Object.keys（OBJ）
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

从对象的自身（以及可选继承）可枚举属性返回函数属性名称数组.

使用`Object.keys（obj）`迭代对象自己的属性.
如果`inherited`是`true`，使用`Object.get.PrototypeOf（obj）`来获取对象的继承属性.
使用`Array.prototype.filter（）`只保留那些属于函数的属性.
省略第二个参数`inherited`，默认情况下不包含继承的属性.

```js
const functions =（obj，inherited = false）=&gt;
  （遗传
     ？  [... Object.keys（obj），... Object.keys（Object.getPrototypeOf（obj））]
    ：Object.keys（obj）
  ）.filter（key =&gt; typeof obj [key] ===&#39;function&#39;）;
```

<details>
<summary>Examples</summary>

```js
function Foo（）{
  this.a =（）=&gt; 1;
  this.b =（）=&gt; 2;
}
Foo.prototype.c = () => 3;
 函数（new Foo（））;  // [&#39;a&#39;，&#39;b&#39;]
 函数（new Foo（），true）;  // [&#39;a&#39;，&#39;b&#39;，&#39;c&#39;]
```

</details>


### get

从对象中检索给定选择器指示的一组属性.

对每个选择器使用`Array.prototype.map（）`，`String.prototype.replace（）`用点替换方括号，`String.prototype.split（&#39;.&#39;）`来拆分每个选择器，`Array. prototype.filter（）`删除空值和`Array.prototype.reduce（）`来获取它指示的值.

```js
const get =（from，... selectors）=&gt;
  [...选择器] .map（s =&gt;
    小号
      .replace（/ [[（[^ \ [\]] *）\] / g，&#39;.$ 1.&#39;）
      .分裂（&#39;.&#39;）
      .filter（t =&gt; t！==&#39;&#39;）
      .reduce（（prev，cur）=&gt; prev &amp;&amp; prev [cur]，from）
  );
```

<details>
<summary>Examples</summary>

```js
const obj = {selector：{to：{val：&#39;val to select&#39;}}，target：[1,2，{a：&#39;test&#39;}]};
 get（obj，&#39;selector.to.val&#39;，&#39;target [0]&#39;，&#39;target [2] .a&#39;）;  // [&#39;val to select&#39;，1，&#39;test&#39;]
```

</details>


### invertKeyValues

 反转对象的键值对，而不改变它.  每个反转键的相应反转值是负责产生反转值的键阵列.  如果提供了一个功能，它将应用于每个反转的键.

使用`Object.keys（）`和`Array.prototype.reduce（）`来反转对象的键值对并应用提供的函数（如果有的话）.
省略第二个参数`fn`，得到反转键而不对它们应用函数.

```js
const invertKeyValues =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，key）=&gt; {
     const val = fn？  fn（obj [key]）：obj [key];
     acc [val] = acc [val] ||  [];
    ACC [VAL] .push（键）;
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
 invertKeyValues（{a：1，b：2，c：1}）;  // {1：[&#39;a&#39;，&#39;c&#39;]，2：[&#39;b&#39;]}
 invertKeyValues（{a：1，b：2，c：1}，value =&gt;&#39;group&#39;+ value）;  // {group1：[&#39;a&#39;，&#39;c&#39;]，group2：[&#39;b&#39;]}
```

</details>


### lowercaseKeys

从指定对象创建一个新对象，其中所有键都是小写的.

使用`Object.keys（）`和`Array.prototype.reduce（）`从指定的对象创建一个新对象.
使用`String.toLowerCase（）`将原始对象中的每个键转换为小写.

```js
const lowercaseKeys = obj =&gt;
  Object.keys（obj）.reduce（（acc，key）=&gt; {
    acc [key.toLowerCase（）] = obj [key];
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
const myObj = {Name：&#39;Adam&#39;，sUrnAME：&#39;Smith&#39;};
 const myObjLower = lowercaseKeys（myObj）;  // {名字：&#39;亚当&#39;，姓：&#39;史密斯&#39;};
```

</details>


### mapKeys

使用为每个键运行提供的函数以及与提供的对象相同的值生成的密钥创建一个对象.

使用`Object.keys（obj）`迭代对象的键.
使用`Array.prototype.reduce（）`使用`fn`创建具有相同值和映射键的新对象.

```js
const mapKeys =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    acc [fn（obj [k]，k，obj）] = obj [k];
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
 mapKeys（{a：1，b：2}，（val，key）=&gt; key + val）;  // {a1：1，b2：2}
```

</details>


### mapValues

使用与提供的对象相同的键创建对象，并通过为每个值运行提供的函数生成值.

使用`Object.keys（obj）`迭代对象的键.
使用`Array.prototype.reduce（）`使用`fn`创建一个具有相同键和映射值的新对象.

```js
const mapValues =（obj，fn）=&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    acc [k] = fn（obj [k]，k，obj）;
    返回acc;
  }, {});
```

<details>
<summary>Examples</summary>

```js
const users = {
  fred：{user：&#39;fred&#39;，年龄：40}，
  鹅卵石：{user：&#39;pebbles&#39;，年龄：1}
};
 mapValues（users，u =&gt; u.age）;  // {fred：40，鹅卵石：1}
```

</details>


### matches

比较两个对象以确定第一个对象是否包含与第二个对应的属性值.

使用`Object.keys（source）`获取第二个对象的所有键，然后使用`Array.prototype.every（）`，`Object.hasOwnProperty（）`和严格比较来确定第一个对象中是否存在所有键并具有相同的值.

```js
const matches =（obj，source）=&gt;
  Object.keys（source）.every（key =&gt; obj.hasOwnProperty（key）&amp;&amp; obj [key] === source [key]）;
```

<details>
<summary>Examples</summary>

```js
 匹配（{age：25，hair：&#39;long&#39;，beard：true}，{hair：&#39;long&#39;，beard：true}）;  //真
 match（{hair：&#39;long&#39;，beard：true}，{age：25，hair：&#39;long&#39;，beard：true}）;  //假
```

</details>


### matchesWith

根据提供的函数，比较两个对象以确定第一个对象是否包含与第二个对应的属性值.

使用`Object.keys（source）`获取第二个对象的所有键，然后使用`Array.prototype.every（）`，`Object.hasOwnProperty（）`和提供的函数来确定第一个是否存在所有键对象并具有等效值.
如果未提供任何功能，则将使用相等运算符比较值.

```js
const matchesWith =（obj，source，fn）=&gt;
  Object.keys（源）.每（
    key =&gt;
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
  {问候：&#39;你好&#39;}，
  {问候：&#39;嗨&#39;}，
  （oV，sV）=&gt; isGreeting（oV）&amp;&amp; isgreeting（sV）
 ）;  //真
```

</details>


### merge

从两个或多个对象的组合中创建新对象.

使用`Array.prototype.reduce（）`结合`Object.keys（obj）`迭代所有对象和键.
使用`hasOwnProperty（）`和`Array.prototype.concat（）`为多个对象中存在的键附加值.

```js
const merge =（... objs）=&gt;
  [... OBJ文件].降低（
    （acc，obj）=&gt;
      Object.keys（obj）.reduce（（a，k）=&gt; {
         acc [k] = acc.hasOwnProperty（k）？  [] .concat（acc [k]）.concat（obj [k]）：obj [k];
        返回acc;
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
  并且：{z：3}，
  b：[2,3]，
  c: 'foo'
};
 合并（对象，其他）;  // {a：[{x：2}，{y：4}，{z：3}]，b：[1,2,3]，c：&#39;foo&#39;}
```

</details>


### nest

Given a flat array of objects linked to one another, it will nest them recursively.
用于嵌套注释，例如reddit.com上的注释.

使用递归.
使用`Array.prototype.filter（）`过滤`id`与`link`匹配的项，然后`Array.prototype.map（）`将每个项映射到一个具有`children`属性的新对象它根据哪些是当前项目的子项递归地嵌套项目.
省略第二个参数`id`，默认为&#39;null`，表示对象没有链接到另一个（即它是顶级对象）.
省略第三个参数`link`，使用`&#39;parent_id&#39;`作为默认属性，通过`id`将对象链接到另一个对象.

```js
const nest =（items，id = null，link =&#39;parent_id&#39;）=&gt;
  项目
    .filter（item =&gt; item [link] === id）
    .map（item =&gt;（{... item，children：nest（items，item.id）}））;
```

<details>
<summary>Examples</summary>

```js
//一个顶级评论
const comments = [
  {id：1，parent_id：null}，
  {id：2，parent_id：1}，
  {id：3，parent_id：1}，
  {id：4，parent_id：2}，
  {id：5，parent_id：4}
];
 const nestedComments = nest（comments）;  // [{id：1，parent_id：null，children：[...]}]
```


</details>


### objectFromPairs

根据给定的键值对创建对象.

使用`Array.prototype.reduce（）`来创建和组合键值对.

```js
const objectFromPairs = arr =&gt; arr.reduce（（a，[key，val]）=&gt;（（a [key] = val），a），{}）;
```

<details>
<summary>Examples</summary>

```js
 objectFromPairs（[[&#39;a&#39;，1]，[&#39;b&#39;，2]]）;  // {a：1，b：2}
```

</details>


### objectToPairs

从对象创建键值对数组的数组.

使用`Object.keys（）`和`Array.prototype.map（）`迭代对象的键并生成一个带键值对的数组.

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

使用`Object.keys（obj）`，`Array.prototype.filter（）`和`Array.prototype.includes（）`来删除提供的键.
使用`Array.prototype.reduce（）`将过滤后的密钥转换回具有相应键值对的对象.

```js
const omit =（obj，arr）=&gt;
  Object.keys（OBJ）
    .filter（k =&gt;！arr.includes（k））
    .reduce（（acc，key）=&gt;（（acc [key] = obj [key]），acc），{}）;
```

<details>
<summary>Examples</summary>

```js
 省略（{a：1，b：&#39;2&#39;，c：3}，[&#39;b&#39;]）;  // {&#39;a&#39;：1，&#39;c&#39;：3}
```

</details>


### omitBy

 创建一个由给定函数返回falsey的属性组成的对象.  使用两个参数调用该函数：（value，key）.

使用`Object.keys（obj）`和`Array.prototype.filter（）`来删除`fn`返回truthy值的键.
使用`Array.prototype.reduce（）`将过滤后的密钥转换回具有相应键值对的对象.

```js
const omitBy =（obj，fn）=&gt;
  Object.keys（OBJ）
    .filter（k =&gt;！fn（obj [k]，k））
    .reduce（（acc，key）=&gt;（（acc [key] = obj [key]），acc），{}）;
```

<details>
<summary>Examples</summary>

```js
 omitBy（{a：1，b：&#39;2&#39;，c：3}，x =&gt; typeof x ===&#39;number&#39;）;  // {b：&#39;2&#39;}
```

</details>


### orderBy

返回按属性和顺序排序的排序对象数组.

在`props`数组上使用`Array.prototype.sort（）`，`Array.prototype.reduce（）`，默认值为&#39;0`，使用数组解构根据传递的顺序交换属性位置.
如果没有传递`orders`数组，则默认按&#39;&#39;asc&#39;排序.

```js
const orderBy =（arr，props，orders）=&gt;
  [... arr] .sort（（a，b）=&gt;
    props.reduce（（acc，prop，i）=&gt; {
      if（acc === 0）{
         const [p1，p2] = orders &amp;&amp; orders [i] ===&#39;desc&#39;？  [b [prop]，[prop]]：[a [prop]，b [prop]];
         acc = p1&gt; p2？  1：p1 &lt;p2？  -1：0;
      }
      返回acc;
    }, 0)
  );
```

<details>
<summary>Examples</summary>

```js
const users = [{name：&#39;fred&#39;，年龄：48}，{name：&#39;barney&#39;，年龄：36}，{name：&#39;fred&#39;，年龄：40}];
 orderBy（users，[&#39;name&#39;，&#39;age&#39;]，[&#39;asc&#39;，&#39;desc&#39;]）;  // [{name：&#39;barney&#39;，年龄：36}，{name：&#39;fred&#39;，年龄：48}，{name：&#39;fred&#39;，年龄：40}]
 orderBy（users，[&#39;name&#39;，&#39;age&#39;]）;  // [{name：&#39;barney&#39;，年龄：36}，{name：&#39;fred&#39;，年龄：40}，{name：&#39;fred&#39;，年龄：48}]
```

</details>


### pick

Picks the key-value pairs corresponding to the given keys from an object.

如果对象中存在键，则使用`Array.prototype.reduce（）`将已过滤/拾取的键转换回具有相应键值对的对象.

```js
const pick =（obj，arr）=&gt;
  arr.reduce（（acc，curr）=&gt;（curr in obj &amp;&amp;（acc [curr] = obj [curr]），acc），{}）;
```

<details>
<summary>Examples</summary>

```js
 选择（{a：1，b：&#39;2&#39;，c：3}，[&#39;a&#39;，&#39;c&#39;]）;  // {&#39;a&#39;：1，&#39;c&#39;：3}
```

</details>


### pickBy

 创建一个由给定函数返回truthy的属性组成的对象.  使用两个参数调用该函数：（value，key）.

使用`Object.keys（obj）`和`Array.prototype.filter（）`来删除`fn`返回falsey值的键.
使用`Array.prototype.reduce（）`将过滤后的密钥转换回具有相应键值对的对象.

```js
const pickBy =（obj，fn）=&gt;
  Object.keys（OBJ）
    .filter（k =&gt; fn（obj [k]，k））
    .reduce（（acc，key）=&gt;（（acc [key] = obj [key]），acc），{}）;
```

<details>
<summary>Examples</summary>

```js
 pickBy（{a：1，b：&#39;2&#39;，c：3}，x =&gt; typeof x ===&#39;number&#39;）;  // {&#39;a&#39;：1，&#39;c&#39;：3}
```

</details>


### renameKeys

使用提供的值替换多个对象键的名称.

将`Object.keys（）`与`Array.prototype.reduce（）`和扩展运算符（`...`）结合使用，得到对象的键，并根据`keysMap`重命名它们.

```js
const renameKeys =（keysMap，obj）=&gt;
  Object.keys（OBJ）.降低（
    （acc，key）=&gt;（{
      ... ACC，
       ...... {[KeymarksMap [key] ||  关键]：obj [key]}
    }),
    {}
  );
```

<details>
<summary>Examples</summary>

```js
const obj = {name：&#39;Bobo&#39;，job：&#39;Front-End Master&#39;，shoeSize：100};
 renameKeys（{name：&#39;firstName&#39;，job：&#39;passion&#39;}，obj）;  // {firstName：&#39;Bobo&#39;，激情：&#39;前端大师&#39;，鞋子大小：100}
```

</details>


### shallowClone

创建对象的浅层克隆.

使用`Object.assign（）`和一个空对象（`{}`）来创建原始的浅层克隆.

```js
const shallowClone = obj =&gt; Object.assign（{}，obj）;
```

<details>
<summary>Examples</summary>

```js
const a = {x：true，y：1};
 const b = shallowClone（a）;  // a！== b
```

</details>


### size

获取数组，对象或字符串的大小.

获取`val`（`array`，`object`或`string`）的类型. 
对数组使用`length`属性.
如果可用，则使用“length”或“size”值或对象的键数.
使用a的&#39;size` [`Blob` object](https://developer.mozilla.org/en-US/docs/Web/API/Blob) 从`val`创建的字符串.

使用`split（&#39;&#39;）`将字符串拆分为字符数组并返回其长度.

```js
const size = val =&gt;
  Array.isArray（VAL）
     ？  val.length
    ：val &amp;&amp; typeof val ===&#39;object&#39;
       ？  val.size ||  val.length ||  Object.keys（VAL）.长度
      ：typeof val ===&#39;string&#39;
         ？  新的Blob（[val]）.尺寸
        : 0;
```

<details>
<summary>Examples</summary>

```js
 大小（[1,2,3,4,5]）;  // 5
 大小（ &#39;尺寸&#39;）;  // 4
 大小（{1：1，2：2，3：3}）;  // 3
```

</details>


### transform

对累加器和对象中的每个键应用一个函数（从左到右）.

使用`Object.keys（obj）`迭代对象中的每个键，`Array.prototype.reduce（）`来调用对给定的累加器应用指定的函数.

```js
const transform =（obj，fn，acc）=&gt; Object.keys（obj）.reduce（（a，k）=&gt; fn（a，obj [k]，k，obj），acc）;
```

<details>
<summary>Examples</summary>

```js
transform(
  {a：1，b：2，c：1}，
  （r，v，k）=&gt; {
    （r [v] ||（r [v] = []））.push（k）;
    返回r;
  },
  {}
 ）;  // {&#39;1&#39;：[&#39;a&#39;，&#39;c&#39;]，&#39;2&#39;：[&#39;b&#39;]}
```

</details>


### truthCheckCollection

检查谓词（第二个参数）是否对集合的所有元素（第一个参数）都是真实的.

使用`Array.prototype.every（）`来检查每个传递的对象是否具有指定的属性，以及它是否返回truthy值.

```js
const truthCheckCollection =（collection，pre）=&gt; collection.every（obj =&gt; obj [pre]）;
```

<details>
<summary>Examples</summary>

```js
 truthCheckCollection（[{user：&#39;Tinky-Winky&#39;，sex：&#39;male&#39;}，{user：&#39;Dipsy&#39;，sex：&#39;male&#39;}]，&#39;sex&#39;）;  //真
```

</details>



使用键的路径取消对象的展开.

使用`Object.keys（obj）`结合`Array.prototype.reduce（）`将展平路径节点转换为叶节点.
如果一个键的值包含一个点分隔符（`.`），使用`Array.prototype.split（&#39;.&#39;）`，字符串转换和`JSON.parse（）`来创建一个对象，然后`Object.assign （）`创建叶节点.
否则，将相应的键值对添加到累加器对象.

```js
const unflattenObject = obj =&gt;
  Object.keys（obj）.reduce（（acc，k）=&gt; {
    if（k.indexOf（&#39;.&#39;）！== -1）{
      const keys = k.split（&#39;.&#39;）;
      Object.assign（
        ACC，
        JSON.parse（
          '{' +
            keys.map（（v，i）=&gt;（i！== keys.length  -  1？`“$ {v}”：{`：`“$ {v}”：`））.join（&#39;&#39;） +
            obj [k] +
            &#39;}&#39;.重复（keys.length）
        )
      );
    }其他acc [k] = obj [k];
    返回acc;
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

以字节为单位返回字符串的长度.

将给定的字符串转换为 [`Blob` Object](https://developer.mozilla.org/en-US/docs/Web/API/Blob) 并找到它的“大小”.

```js
const byteSize = str =&gt; new Blob（[str]）.size;
```

<details>
<summary>Examples</summary>

```js
 byteSize（ &#39;&#39;）;  // 4
 byteSize（&#39;Hello World&#39;）;  // 11
```

</details>


### capitalize

大写字符串的第一个字母.

使用数组解构和`String.prototype.toUpperCase（）`来大写第一个字母，`... rest`来获取第一个字母后的字符数组，然后使用`Array.prototype.join（&#39;&#39;）`来使它成为一个字符串再次.
省略`lowerRest`参数以保持字符串的其余部分不变，或将其设置为`true`以转换为小写.

```js
const capitalize =（[first，... rest]，lowerRest = false）=&gt;
  first.toUpperCase（）+（lowerRest？rest.join（&#39;&#39;）.toLowerCase（）：rest.join（&#39;&#39;））;
```

<details>
<summary>Examples</summary>

```js
 利用（ &#39;fooBar&#39; 的）;  //&#39;FooBar&#39;
 大写（&#39;fooBar&#39;，true）;  //&#39;Foobar&#39;
```

</details>


### capitalizeEveryWord

将字符串中每个单词的首字母大写.

使用`String.prototype.replace（）`匹配每个单词的第一个字符和`String.prototype.toUpperCase（）`来大写它.

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

返回压缩空格的字符串.

将`String.prototype.replace（）`与正则表达式一起使用，用一个空格替换所有出现的2个或更多空格字符.

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

如果`omitFirstRow`为&#39;true`，则使用`Array.prototype.slice（）`和`Array.prototype.indexOf（&#39;\ n&#39;）`删除第一行（标题行）.
使用`String.prototype.split（&#39;\ n&#39;）`为每一行创建一个字符串，然后使用`String.prototype.split（delimiter）`来分隔每一行中的值.
省略第二个参数`delimiter`，使用`，`的默认分隔符.
省略第三个参数`omitFirstRow`，以包含CSV字符串的第一行（标题行）.

```js
const CSVToArray =（data，delimiter =&#39;，&#39;，omitFirstRow = false）=&gt;
  数据
    .slice（omitFirstRow？data.indexOf（&#39;\ n&#39;）+ 1：0）
    .split（ &#39;\ n&#39;）
    .map（v =&gt; v.split（delimiter））;
```

<details>
<summary>Examples</summary>

```js
 CSVToArray（ &#39;A，B \ NC，d&#39;）;  // [[&#39;A B C D&#39;]];
 CSVToArray（&#39;a; b \ nc; d&#39;，&#39;;&#39;）;  // [[&#39;A B C D&#39;]];
 CSVToArray（&#39;col1，col2 \ na，b \ nc，d&#39;，&#39;，&#39;，true）;  // [[&#39;A B C D&#39;]];
```

</details>



将逗号分隔值（CSV）字符串转换为2D对象数组.
字符串的第一行用作标题行.

使用`Array.prototype.slice（）`和`Array.prototype.indexOf（&#39;\ n&#39;）`和`String.prototype.split（delimiter）`将第一行（标题行）分隔为值.
使用`String.prototype.split（&#39;\ n&#39;）`为每一行创建一个字符串，然后使用`Array.prototype.map（）`和`String.prototype.split（delimiter）`来分隔每行中的值.
使用`Array.prototype.reduce（）`为每行的值创建一个对象，并从标题行解析键.
省略第二个参数`delimiter`，使用`，`的默认分隔符.

```js
const CSVToJSON =（data，delimiter =&#39;，&#39;）=&gt; {
  const titles = data.slice（0，data.indexOf（&#39;\ n&#39;））.split（delimiter）;
  返回数据
    .slice（data.indexOf（&#39;\ n&#39;）+ 1）
    .split（ &#39;\ n&#39;）
    .map（v =&gt; {
      const values = v.split（delimiter）;
      return titles.reduce（（obj，title，index）=&gt;（（obj [title] = values [index]），obj），{}）;
    });
};
```

<details>
<summary>Examples</summary>

```js
 CSVToJSON（ &#39;COL1，COL2 \ NA，B \ NC，d&#39;）;  // [{&#39;col1&#39;：&#39;a&#39;，&#39;col2&#39;：&#39;b&#39;}，{&#39;col1&#39;：&#39;c&#39;，&#39;col2&#39;：&#39;d&#39;}]​​;
 CSVToJSON（&#39;col1; col2 \ na; b \ nc; d&#39;，&#39;;&#39;）;  // [{&#39;col1&#39;：&#39;a&#39;，&#39;col2&#39;：&#39;b&#39;}，{&#39;col1&#39;：&#39;c&#39;，&#39;col2&#39;：&#39;d&#39;}]​​;
```

</details>


### decapitalize

对字符串的第一个字母进行去除资本化.

使用数组解构和`String.toLowerCase（）`去掉第一个字母，`... rest`以获得第一个字母后的字符数组，然后使用`Array.prototype.join（&#39;&#39;）`使其再次成为字符串.
省略`upperRest`参数以保持字符串的其余部分不变，或将其设置为`true`以转换为大写.

```js
const decapitalize =（[first，... rest]，upperRest = false）=&gt;
  first.toLowerCase（）+（upperRest？rest.join（&#39;&#39;）.toUpperCase（）：rest.join（&#39;&#39;））;
```

<details>
<summary>Examples</summary>

```js
 decapitalize（ &#39;fooBar&#39; 的）;  //&#39;fooBar&#39;
 decapitalize（&#39;FooBar&#39;，true）;  //&#39;fOOBAR&#39;
```

</details>


### escapeHTML

转义字符串以在HTML中使用.

使用带有regexp的`String.prototype.replace（）`，该regexp匹配需要转义的字符，使用回调函数使用字典（对象）将每个字符实例替换为其关联的转义字符.

```js
const escapeHTML = str =&gt;
  str.replace（
    / [＆&lt;&gt;“”] /克，
    tag =&gt;
      ({
        &#39;＆&#39;：&#39;＆&#39;，
        '<': '&lt;',
        &#39;&gt;&#39;：&#39;&gt;&#39;，
        "'": '&#39;',
        &#39;&#39;&#39;&#39;&#39;&#39;&#39;&#39;
       } [日] ||  标签）
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

使用`String.prototype.replace（）`来转义特殊字符.

```js
const escapeRegExp = str =&gt; str.replace（/ [.* +？^ $ {}（）| [\] \\] / g，&#39;\\ $＆&#39;）;
```

<details>
<summary>Examples</summary>

```js
 escapeRegExp（ &#39;（试验）&#39;）;  // \\（test \\）
```

</details>


### fromCamelCase

从camelcase转换字符串.

使用`String.prototype.replace（）`删除下划线，连字符和空格，并将单词转换为camelcase.
省略第二个参数以使用`_`的默认`separator`.

```js
const fromCamelCase =（str，separator =&#39;_&#39;）=&gt;
  海峡
    .replace（/（[az \ d]）（[AZ]）/ g，&#39;$ 1&#39;+分隔符+&#39;$ 2&#39;）
    .replace（/（[AZ] +）（[AZ] [az \ d] +）/ g，&#39;$ 1&#39;+分隔符+&#39;$ 2&#39;）
    .toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 fromCamelCase（&#39;someDatabaseFieldName&#39;，&#39;&#39;）;  //&#39;某个数据库字段名&#39;
 fromCamelCase（&#39;someLabelThatNeedsToBeCamelized&#39;，&#39; - &#39;）;  //&#39;某些标签 - 需要被驯化&#39;
 fromCamelCase（&#39;someJavascriptProperty&#39;，&#39;_&#39;）;  //&#39;some_javascript_property&#39;
```

</details>


### indentString

缩进提供的字符串中的每一行.

使用`String.replace`和正则表达式在每行的开头添加由`indent``count`次指定的字符.
省略第三个参数`indent`，使用`&#39;&#39;`的默认缩进字符.

```js
const indentString =（str，count，indent =&#39;&#39;）=&gt; str.replace（/ ^ / gm，indent.repeat（count））;
```

<details>
<summary>Examples</summary>

```js
 indentString（“LOREM \夹口”，2）;  // &#39;LOREM \ n很&#39;
 indentString（ &#39;LOREM \咬&#39;，2， &#39;_&#39;）;  // __Lorem \ n__Ipsum“
```

</details>


### isAbsoluteURL

如果给定的字符串是绝对URL，则返回“true”，否则返回“false”.

使用正则表达式来测试字符串是否是绝对URL.

```js
const isAbsoluteURL = str =&gt; /^ [az] [ -  z0-9 + .-] *：/.test(str）;
```

<details>
<summary>Examples</summary>

```js
 isAbsoluteURL（ &#39;https://google.com&#39;）;  //真
 isAbsoluteURL（ &#39;ftp://www.myserver.net&#39;）;  //真
 isAbsoluteURL（ &#39;/富/巴&#39;）;  //假
```

</details>


### isAnagram

检查字符串是否是另一个字符串的字谜（不区分大小写，忽略空格，标点符号和特殊字符）.

使用`String.toLowerCase（）`，`String.prototype.replace（）`和适当的正则表达式来删除不必要的字符，`String.prototype.split（&#39;&#39;）`，`Array.prototype.sort（）`和在两个字符串上使用`Array.prototype.join（&#39;&#39;）`来规范化它们，然后检查它们的规范化形式是否相等.

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
 isAnagram（&#39;iceman&#39;，&#39;cinema&#39;）;  //真
```

</details>


### isLowerCase

检查字符串是否为小写.

使用`String.toLowerCase（）`将给定字符串转换为小写，并将其与原始字符串进行比较.

```js
const isLowerCase = str =&gt; str === str.toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 isLowerCase（ &#39;ABC&#39;）;  //真
 isLowerCase（ &#39;A3 @ $&#39;）;  //真
 isLowerCase（ &#39;Ab4的&#39;）;  //假
```

</details>


### isUpperCase

检查字符串是否为大写.

使用`String.prototype.toUpperCase（）`将给定的字符串转换为大写，并将其与原始字符串进行比较.


```js
const isUpperCase = str =&gt; str === str.toUpperCase（）;
```

<details>
<summary>Examples</summary>

```js
 isUpperCase（ &#39;ABC&#39;）;  //真
 isLowerCase（ &#39;A3 @ $&#39;）;  //真
 isLowerCase（ &#39;AB4&#39;）;  //假
```

</details>


### mapString

创建一个新字符串，其结果是在调用字符串中的每个字符上调用提供的函数.

使用`String.prototype.split（&#39;&#39;）`和`Array.prototype.map（）`为`str`中的每个字符调用提供的函数`fn`.
使用`Array.prototype.join（&#39;&#39;）`将字符数组重新组合成一个字符串.
回调函数`fn`有三个参数（当前字符，当前字符的索引和字符串`mapString`被调用）.

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

用指定的掩码字符替换除最后一个字符数以外的所有字符.

使用`String.prototype.slice（）`来获取将保持未被屏蔽的字符部分，并使用`String.padStart（）`来填充字符串的开头，使用掩码字符直到原始长度.
 省略第二个参数`num`，以保持默认的“4”字符不被屏蔽.  如果`num`为负数，则未屏蔽的字符将位于字符串的开头.
省略第三个参数`mask`，为掩码使用默认字符&#39;&#39;*&#39;`.

```js
const mask =（cc，num = 4，mask =&#39;*&#39;）=&gt;`$ {cc}`.slice（-num）.padStart（`$ {cc}`.length，mask）;
```

<details>
<summary>Examples</summary>

```js
 掩模（1234567890）;  //&#39;****** 7890&#39;
 面具（1234567890,3）;  //&#39;******* 890&#39;
 面具（1234567890，-4，&#39;$&#39;）;  //&#39;$$$$ 567890&#39;
```

</details>


### pad

如果它短于指定的长度，则在指定字符的两侧填充一个字符串.

使用`String.padStart（）`和`String.padEnd（）`来填充给定字符串的两边.
省略第三个参数`char`，使用空格字符作为默认填充字符.

```js
const pad =（str，length，char =&#39;&#39;）=&gt;
  str.padStart（（str.length + length）/ 2，char）.padEnd（length，char）;
```

<details>
<summary>Examples</summary>

```js
 垫（&#39;猫&#39;，8）;  // &#39; 猫 &#39;
 pad（String（42），6，&#39;0&#39;）;  //&#39;004200&#39;
 垫（&#39;foobar&#39;，3）;  //&#39;foobar&#39;
```

</details>


### palindrome

Returns `true` if the given string is a palindrome, `false` otherwise.

将字符串转换为`String.prototype.toLowerCase（）`并使用`String.prototype.replace（）`从中删除非字母数字字符.
然后，使用扩展运算符（`...`）将字符串拆分为单个字符，`Array.prototype.reverse（）`，`String.prototype.join（&#39;&#39;）`并将其与原始字符进行比较，未反转string，将其转换为`String.prototype.toLowerCase（）`.

```js
const palindrome = str =&gt; {
  const s = str.toLowerCase（）.replace（/ [\ W _] / g，&#39;&#39;）;
  return s === [... s] .reverse（）.join（&#39;&#39;）;
};
```

<details>
<summary>Examples</summary>

```js
 回文（&#39;taco cat&#39;）;  //真
```

</details>


### pluralize

 根据输入数字返回单词或复数形式的单词.  如果第一个参数是一个`object`，它将使用一个闭包，它返回一个函数，如果提供的字典包含单词，它可以自动复制不仅仅以`s`结尾的单词.

 如果`num`是`-1`或`1`，则返回单词的单数形式.  如果`num`是任何其他数字，则返回复数形式.  省略第三个参数以使用单数词+`s`的默认值，或在必要时提供自定义复数词.  如果第一个参数是`object`，则通过返回一个函数来使用闭包，该函数可以使用提供的字典来解析单词的正确复数形式.

```js
const pluralize =（val，word，plural = word +&#39;s&#39;）=&gt; {
  const _pluralize =（num，word，plural = word +&#39;s&#39;）=&gt;
     [1，-1] .includes（Number（num））？  单词：复数;
  if（typeof val ===&#39;object&#39;）return（num，word）=&gt; _pluralize（num，word，val [word]）;
  return _pluralize（val，word，plural）;
};
```

<details>
<summary>Examples</summary>

```js
 pluralize（0，&#39;apple&#39;）;  // &#39;苹果&#39;
 复数（1，&#39;apple&#39;）;  // &#39;苹果&#39;
 pluralize（2，&#39;apple&#39;）;  // &#39;苹果&#39;
 复数（2，&#39;人&#39;，&#39;人&#39;）;  //&#39;人&#39;

const PLURALS = {
  人：&#39;人&#39;，
  半径：&#39;半径&#39;
};
const autoPluralize = pluralize（PLURALS）;
 autoPluralize（2，&#39;person&#39;）;  //&#39;人&#39;
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

反转一个字符串.

使用spread运算符（`...`）和`Array.prototype.reverse（）`来反转字符串中字符的顺序.
使用`String.prototype.join（&#39;&#39;）`组合字符以获取字符串.

```js
const reverseString = str =&gt; [... str] .reverse（）.join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 reverseString（ &#39;foobar的&#39;）;  //&#39;raboof&#39;
```

</details>


### sortCharactersInString

按字母顺序对字符串中的字符进行排序.

使用扩展运算符（`...`），`Array.prototype.sort（）`和`String.localeCompare（）`来排序`str`中的字符，使用`String.prototype.join（&#39;&#39;）重新组合`.

```js
const sortCharactersInString = str =&gt; [... str] .sort（（a，b）=&gt; a.localeCompare（b））.join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 sortCharactersInString（ &#39;白菜&#39;）;  //&#39;aabbceg&#39;
```

</details>


### splitLines

将多行字符串拆分为一行数组.

使用`String.prototype.split（）`和正则表达式来匹配换行符并创建一个数组.

```js
const splitLines = str =&gt; str.split（/ \ r？\ n /）;
```

<details>
<summary>Examples</summary>

```js
 splitLines（&#39;This \ n is a \ nmultiline \ nstring.\ n&#39;）;  // [&#39;This&#39;，&#39;是&#39;，&#39;&#39;multiline&#39;，&#39;string&#39;.  ，&#39;&#39;]
```

</details>



 ⚠️**警告**：此函数的执行时间随每个字符呈指数增长.  任何超过8到10个字符的内容都会导致浏览器挂起，因为它会尝试解决所有不同的组合.

生成字符串的所有排列（包含重复项）.

使用递归.
对于给定字符串中的每个字母，为其余字母创建所有部分排列.
使用`Array.prototype.map（）`将字母与每个部分排列组合，然后使用`Array.prototype.reduce（）`来组合一个数组中的所有排列.
字符串`length`等于“2”或“1”的基本情况.

```js
const stringPermutations = str =&gt; {
   if（str.length &lt;= 2）返回str.length === 2？  [str，str [1] + str [0]]：[str];
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
 stringPermutations（ &#39;ABC&#39;）;  // [&#39;abc&#39;，&#39;acb&#39;，&#39;bac&#39;，&#39;bca&#39;，&#39;cab&#39;，&#39;cba&#39;]
```

</details>


### stripHTMLTags

从字符串中删除HTML / XML标记.

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

将字符串转换为camelcase.

将字符串分解为单词并将它们组合起来，使用正则表达式将每个单词的第一个字母大写.

```js
const toCamelCase = str =&gt; {
  让s =
    str &amp;&amp;
    海峡
      .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | b）| [AZ]？[az] + [0-9] * | [AZ] | [0-9] + / g）
      .map（x =&gt; x.slice（0,1）.toUpperCase（）+ x.slice（1）.toLowerCase（））
      .加入（&#39;&#39;）;
  return s.slice（0,1）.toLowerCase（）+ s.slice（1）;
};
```

<details>
<summary>Examples</summary>

```js
 toCamelCase（ &#39;some_database_field_name&#39;）;  //&#39;someDatabaseFieldName&#39;
 toCamelCase（&#39;某些标签需要被驯化&#39;）;  //&#39;someLabelThatNeedsToBeCamelized&#39;
 toCamelCase（&#39;some-javascript-property&#39;）;  //&#39;someJavascriptProperty&#39;
 toCamelCase（&#39;some-mixed_string with spaces_underscores-and-hyphens&#39;）;  //&#39;someMixedStringWithSpacesUnderscoresAndHyphens&#39;
```

</details>


### toKebabCase

将字符串转换为烤肉串案例.

将字符串分解为单词并将它们组合使用regexp将`-`添加为分隔符.

```js
const toKebabCase = str =&gt;
  str &amp;&amp;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | b）| [AZ]？[az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.toLowerCase（））
    .加入（&#39;-&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toKebabCase（ &#39;驼峰&#39;）;  // &#39;骆驼香烟盒&#39;
 toKebabCase（&#39;some text&#39;）;  //&#39;some-text&#39;
 toKebabCase（&#39;some-mixed_string with spaces_underscores-and-hyphens&#39;）;  //&#39;some-mixed-string-with-spaces-underscores-and-hyphens&#39;
 toKebabCase（&#39;AllThe-small Things&#39;）;  // “所有的小事情”
 toKebabCase（ &#39;IAmListeningToFMWhileLoadingDifferentURLOnMyBrowserAndAlsoEditingSomeXMLAndHTML&#39;）;  //“i-am-listening-fm-while-loading-different-url-on-my-browser-and-also-editing-xml-and-html”
```

</details>


### toSnakeCase

将字符串转换为蛇案例.

将字符串分解为单词并将它们组合使用regexp将`_`添加为分隔符.

```js
constSnakeCase = str =&gt;
  str &amp;&amp;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | b）| [AZ]？[az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.toLowerCase（））
    .加入（&#39;_&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toSnakeCase（ &#39;驼峰&#39;）;  // &#39;骆驼香烟盒&#39;
 toSnakeCase（&#39;some text&#39;）;  //&#39;some_text&#39;
 toSnakeCase（&#39;some-mixed_string with spaces_underscores-and-hyphens&#39;）;  //&#39;some_mixed_string_with_spaces_underscores_and_hyphens&#39;
 toSnakeCase（&#39;AllThe-small Things&#39;）;  //“all_the_smal_things”
 toSnakeCase（ &#39;IAmListeningToFMWhileLoadingDifferentURLOnMyBrowserAndAlsoEditingSomeXMLAndHTML&#39;）;  //“i_am_listening_to_fm_while_loading_different_url_on_my_browser_and_also_editing_some_xml_and_html”
```

</details>


### toTitleCase

将字符串转换为标题大小写.

使用正则表达式将字符串分解为单词，并将它们组合成大写每个单词的第一个字母并在它们之间添加空格.

```js
const toTitleCase = str =&gt;
  海峡
    .match（/ [AZ] {2，}（？= [AZ] [az] + [0-9] * | b）| [AZ]？[az] + [0-9] * | [AZ] | [0-9] + / g）
    .map（x =&gt; x.charAt（0）.toUpperCase（）+ x.slice（1））
    .join（&#39;&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toTitleCase（ &#39;some_database_field_name&#39;）;  //&#39;某些数据库字段名&#39;
 toTitleCase（&#39;某些需要标题的标签&#39;）;  //&#39;一些需要标题的标签&#39;
 toTitleCase（“一些包名”）;  //&#39;某些包名&#39;
 toTitleCase（&#39;some-mixed_string with spaces_underscores-and-hyphens&#39;）;  //&#39;带有空间的混合字符串下划线和连字符&#39;
```

</details>


### truncateString

截断指定长度的字符串.

确定字符串的“长度”是否大于“num”.
将截断的字符串返回到所需的长度，并在末尾或原始字符串后附加“...”.

```js
const truncateString =（str，num）=&gt;
   str.length&gt;当然？  str.slice（0，是否&gt; 3 NUM  -  3 NUM）+ &#39;...&#39;：STR;
```

<details>
<summary>Examples</summary>

```js
 truncateString（&#39;回旋镖&#39;，7）;  //&#39;繁荣......&#39;
```

</details>


### unescapeHTML

Unescapes转义了HTML字符.

使用`String.prototype.replace（）`与正则表达式匹配需要非转义的字符，使用回调函数使用字典（对象）将每个转义的字符实例替换为其关联的非转义字符.

```js
const unescapeHTML = str =&gt;
  str.replace（
    /&amp;|&lt;|&gt;|&#39;|&quot;/g,
    tag =&gt;
      ({
        &#39;＆&#39;：&#39;＆&#39;，
        &#39;&lt;&#39;：&#39;&lt;&#39;，
        &#39;&gt;&#39;：&#39;&gt;&#39;，
        '&#39;': "'",
        &#39;&#39;&#39;&#39;&#39;&#39;&#39;&#39;
       } [日] ||  标签）
  );
```

<details>
<summary>Examples</summary>

```js
unescapeHTML('&lt;a href=&quot;#&quot;&gt;Me &amp; you&lt;/a&gt;'); // '<a href="#">Me & you</a>'
```

</details>



将所有给定的URL段连接在一起，然后规范化生成的URL.

使用`String.prototype.join（&#39;/&#39;）`组合URL段，然后使用各种regexp调用一系列`String.prototype.replace（）`来规范化生成的URL（删除双斜杠，为协议添加适当的斜杠） ，在参数前删除斜杠，将参数与&#39;&#39;＆&#39;组合，并规范化第一个参数分隔符）.

```js
const URLJoin =（... args）=&gt;
  ARGS
    .加入（&#39;/&#39;）
    .replace（/ [\ /] + / g，&#39;/&#39;）
    .replace（/^(.+):\//,&#39;$ 1：//&#39;）
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

 使用带有提供模式的`String.prototype.split（）`（默认为非alpha作为regexp）转换为字符串数组.  使用`Array.prototype.filter（）`删除任何空字符串.
省略第二个参数以使用默认的regexp.

```js
const words =（str，pattern = / [^ a-zA-Z  - ] + /）=&gt; str.split（pattern）.filter（Boolean）;
```

<details>
<summary>Examples</summary>

```js
 单词（&#39;我喜欢javaScript !!&#39;）;  // [“我”，“爱”，“javaScript”]
 单词（&#39;python，javaScript＆coffee&#39;）;  // [“python”，“javaScript”，“coffee”]
```

</details>



---

## 📃 Type

### getType

返回值的本机类型.

返回小写的构造函数名称，“”undefined“或”“null”`如果value是`undefined`或`null`.

```js
const getType = v =&gt;
   v === undefined？  &#39;undefined&#39;：v === null？  &#39;null&#39;：v.constructor.name.toLowerCase（）;
```

<details>
<summary>Examples</summary>

```js
 getType（new Set（[1,2,3]））;  //&#39;设置&#39;
```

</details>


### is

检查提供的值是否为指定类型.

使用`Array.prototype.includes（）`确保值不是`undefined`或`null`，并将值的`constructor`属性与`type`进行比较，以检查提供的值是否是指定的`type` .

```js
const is =（type，val）=&gt;！[，null] .includes（val）&amp;&amp; val.constructor === type;
```

<details>
<summary>Examples</summary>

```js
 是（Array，[1]）;  //真
 是（ArrayBuffer，new ArrayBuffer（））;  //真
 是（Map，new Map（））;  //真
 是（RegExp，/./ g）;  //真
 是（Set，new Set（））;  //真
 是（WeakMap，new WeakMap（））;  //真
 是（WeakSet，new WeakSet（））;  //真
 是（String，&#39;&#39;）;  //真
 是（String，new String（&#39;&#39;））;  //真
 是（数字，1）;  //真
 是（数字，新数字（1））;  //真
 是（Boolean，true）;  //真
 是（Boolean，new Boolean（true））;  //真
```

</details>


### isArrayLike

检查提供的参数是否类似于数组（即可迭代）.

检查提供的参数是否不是“null”，并且它的`Symbol.iterator`属性是一个函数.

```js
const isArrayLike = obj =&gt; obj！= null &amp;&amp; typeof obj [Symbol.iterator] ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
 isArrayLike（document.querySelectorAll（ &#39;的className&#39;））;  //真
 isArrayLike（ &#39;ABC&#39;）;  //真
 isArrayLike（NULL）;  //假
```

</details>


### isBoolean

检查给定的参数是否是本机布尔元素.

使用`typeof`来检查值是否被归类为布尔基元.

```js
const isBoolean = val =&gt; typeof val ===&#39;boolean&#39;;
```

<details>
<summary>Examples</summary>

```js
 isBoolean（NULL）;  //假
 isBoolean（假）;  //真
```

</details>


### isEmpty

如果a值是空对象，集合，没有可枚举属性或任何不被视为集合的类型，则返回true.

检查提供的值是否为“null”或者其“length”是否等于“0”.

```js
 const isEmpty = val =&gt; val == null ||  ！（Object.keys（val）|| val）.length;
```

<details>
<summary>Examples</summary>

```js
 是空的（[]）;  //真
 是空的（{}）;  //真
 是空的（&#39;&#39;）;  //真
 isEmpty（[1,2]）;  //假
 isEmpty（{a：1，b：2}）;  //假
 的isEmpty（ &#39;文本&#39;）;  //假
 的isEmpty（123）;  // true  - 类型不被视为集合
 的isEmpty（真）;  // true  - 类型不被视为集合
```

</details>


### isFunction

检查给定的参数是否是函数.

使用`typeof`检查值是否被归类为函数原语.

```js
const isFunction = val =&gt; typeof val ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
 isFunction（ &#39;X&#39;）;  //假
 isFunction（x =&gt; x）;  //真
```

</details>


### isNil

如果指定的值为“null”或“undefined”，则返回“true”，否则返回“false”.

使用strict equality运算符检查`val`的值是否等于`null`或`undefined`.

```js
 const isNil = val =&gt; val === undefined ||  val === null;
```

<details>
<summary>Examples</summary>

```js
 isNil（NULL）;  //真
 isNil（未定义）;  //真
```

</details>


### isNull

如果指定的值为“null”则返回“true”，否则返回“false”.

使用strict equality运算符检查`val`的值是否等于`null`.

```js
const isNull = val =&gt; val === null;
```

<details>
<summary>Examples</summary>

```js
 ISNULL（NULL）;  //真
```

</details>


### isNumber

检查给定的参数是否为数字.

使用`typeof`检查值是否被归类为数字原语. 
为了防止“NaN”，检查`val === val`（因为`NaN`的`typeof`等于`number`并且唯一的值不等于它自己）.

```js
const isNumber = val =&gt; typeof val ===&#39;number&#39;&amp;&amp; val === val;
```

<details>
<summary>Examples</summary>

```js
 ISNUMBER（1）;  //真
 ISNUMBER（ &#39;1&#39;）;  //假
 ISNUMBER（NAN）;  //假
```

</details>


### isObject

返回一个布尔值，确定传递的值是否为对象.

使用`Object`构造函数为给定值创建一个对象包装器. 
 如果值为“null”或“undefined”，则创建并返回一个空对象.  否则，返回与给定值对应的类型的对象.

```js
const isObject = obj =&gt; obj === Object（obj）;
```

<details>
<summary>Examples</summary>

```js
 isObject（[1,2,3,4]）;  //真
 则IsObject（[]）;  //真
 则IsObject（[ &#39;你好！&#39;]）;  //真
 isObject（{a：1}）;  //真
 则IsObject（{}）;  //真
 则IsObject（真）;  //假
```

</details>


### isObjectLike

检查值是否类似于对象.

检查提供的值是否为“null”且其“typeof”是否等于“object”.

```js
const isObjectLike = val =&gt; val！== null &amp;&amp; typeof val ===&#39;object&#39;;
```

<details>
<summary>Examples</summary>

```js
 isObjectLike（{}）;  //真
 isObjectLike（[1,2,3]）;  //真
 isObjectLike（x =&gt; x）;  //假
 isObjectLike（NULL）;  //假
```

</details>


### isPlainObject

检查提供的值是否是Object构造函数创建的对象.

检查提供的值是否真实，使用`typeof`检查它是否是一个对象，并使用`Object.constructor`来确保构造函数等于`Object`.

```js
const isPlainObject = val =&gt; !! val &amp;&amp; typeof val ===&#39;object&#39;&amp;&amp; val.constructor === Object;
```

<details>
<summary>Examples</summary>

```js
 isPlainObject（{a：1}）;  //真
 isPlainObject（new Map（））;  //假
```

</details>


### isPrimitive

返回一个布尔值，确定传递的值是否为原始值.

从`val`创建一个对象并将其与`val`进行比较，以确定传递的值是否是原始值（即不等于创建的对象）.

```js
const isPrimitive = val =&gt; Object（val）！== val;
```

<details>
<summary>Examples</summary>

```js
 isPrimitive（NULL）;  //真
 isPrimitive（50）;  //真
 isPrimitive（ &#39;你好！&#39;）;  //真
 isPrimitive（假）;  //真
 isPrimitive（符号（））;  //真
 isPrimitive（[]）;  //假
```

</details>


### isPromiseLike

如果对象看起来像是，则返回“true” [`Promise`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)，`false`否则.

检查对象是否不是“null”，它的`typeof`匹配`object`或`function`，如果它有`.then`属性，它也是``function`.

```js
const isPromiseLike = obj =&gt;
  obj！== null &amp;&amp;
  （typeof obj ===&#39;object&#39;|| typeof obj ===&#39;function&#39;）&amp;&amp;
  typeof obj.then ===&#39;function&#39;;
```

<details>
<summary>Examples</summary>

```js
isPromiseLike({
  那么：function（）{
    返回&#39;&#39;;
  }
 }）;  //真
 isPromiseLike（NULL）;  //假
 isPromiseLike（{}）;  //假
```

</details>


### isString

 检查给定的参数是否为字符串.  仅适用于字符串基元.

使用`typeof`检查值是否被归类为字符串原语.

```js
const isString = val =&gt; typeof val ===&#39;string&#39;;
```

<details>
<summary>Examples</summary>

```js
 isString（&#39;10&#39; ）;  //真
```

</details>


### isSymbol

检查给定的参数是否为符号.

使用`typeof`检查值是否被归类为符号原语.

```js
const isSymbol = val =&gt; typeof val ===&#39;symbol&#39;;
```

<details>
<summary>Examples</summary>

```js
 isSymbol（符号（ &#39;X&#39;））;  //真
```

</details>


### isUndefined

如果指定的值是`undefined`则返回&#39;true`，否则返回`false`.

使用strict equality运算符检查`val`的值是否等于`undefined`.

```js
const isUndefined = val =&gt; val === undefined;
```

<details>
<summary>Examples</summary>

```js
 isUndefined（未定义）;  //真
```

</details>


### isValidJSON

检查提供的字符串是否是有效的JSON.

使用`JSON.parse（）`和`try ... catch`块来检查提供的字符串是否是有效的JSON.

```js
const isValidJSON = str =&gt; {
  尝试{
    JSON.parse（STR）;
    返回true;
  } catch（e）{
    返回false;
  }
};
```

<details>
<summary>Examples</summary>

```js
 isValidJSON（ &#39;{ “名称”： “亚当”， “年龄”：20}&#39;）;  //真
 isValidJSON（ &#39;{ “名称”： “亚当”，年龄： “20”}&#39;）;  //假
 isValidJSON（NULL）;  //真
```

</details>



---

## 🔧 Utility

### castArray

如果不是一个数组，则将提供的值转换为数组.

使用`Array.prototype.isArray（）`来确定`val`是否是一个数组并按原样返回它或相应地封装在一个数组中.

```js
const castArray = val =&gt;（Array.isArray（val）？val：[val]）;
```

<details>
<summary>Examples</summary>

```js
 castArray（ &#39;富&#39;）;  // [&#39;foo&#39;]
 castArray（[1]）;  // [1]
```

</details>


### cloneRegExp

克隆正则表达式.

使用`new RegExp（）`，`RegExp.source`和`RegExp.flags`来克隆给定的正则表达式.

```js
const cloneRegExp = regExp =&gt; new RegExp（regExp.source，regExp.flags）;
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

使用`Array.prototype.find（）`返回第一个非`null` /`undefined`参数.

```js
const coalesce =（... args）=&gt; args.find（_ =&gt;！[undefined，null] .includes（_））;
```

<details>
<summary>Examples</summary>

```js
coalesce(null, undefined, '', NaN, 'Waldo'); // ""
```

</details>


### coalesceFactory

返回一个自定义的coalesce函数，它返回从提供的参数验证函数返回“true”的第一个参数.

使用`Array.prototype.find（）`返回从提供的参数验证函数返回`true`的第一个参数.

```js
const coalesceFactory = valid =&gt;（... args）=&gt; args.find（valid）;
```

<details>
<summary>Examples</summary>

```js
const customCoalesce = coalesceFactory（_ =&gt;！[null，undefined，&#39;&#39;，NaN] .includes（_））;
 customCoalesce（undefined，null，NaN，&#39;&#39;，&#39;Waldo&#39;）;  //“Waldo”
```

</details>


### extendHex

将3位颜色代码扩展为6位颜色代码.

使用`Array.prototype.map（）`，`String.prototype.split（）`和`Array.prototype.join（）`连接映射数组，将3位RGB标记的十六进制颜色代码转换为6 - 数字形式.
`Array.prototype.slice()` is used to remove `#` from string start since it's added once.

```js
const extendHex = shortHex =&gt;
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

返回包含当前URL参数的对象.

使用带有适当正则表达式的`String.match（）`来获取所有键值对，`Array.prototype.reduce（）`来映射并将它们组合成一个对象.
将`location.search`作为参数传递给当前的`url`.

```js
const getURLParameters = url =&gt;
  （url.match（/（[^？=＆] +）（=（[^＆] *））/ g）|| []）.reduce（
    （a，v）=&gt;（（和[v.slice（0，v.indexOf（&#39;=&#39;））] = v.slice（v.indexOf（&#39;=&#39;）+ 1））
    {}
  );
```

<details>
<summary>Examples</summary>

```js
 getURLParameters（ &#39;http://url.com/page?name=Adam&amp;surname=Smith&#39;）;  // {姓名：&#39;亚当&#39;，姓：&#39;史密斯&#39;}
 getURLParameters（&#39;google.com&#39;）;  // {}
```

</details>



如果提供了alpha值，则将颜色代码转换为`rgb（）`或`rgba（）`字符串.

Use bitwise right-shift operator and mask bits with `&` (and) operator to convert a hexadecimal color code (with or without prefixed with `#`) to a string with the RGB values. If it's 3-digit color code, first convert to 6-digit version. If an alpha value is provided alongside 6-digit hex, give `rgba()` string in return.

```js
const hexToRGB = hex => {
  设alpha = false，
    h = hex.slice(hex.startsWith('#') ? 1 : 0);
  if（h.length === 3）h = [... h] .map（x =&gt; x + x）.join（&#39;&#39;）;
  否则如果（h.length === 8）alpha = true;
  h = parseInt（h，16）;
  回来（
    &#39;rgb&#39;+
    （alpha？&#39;a&#39;：&#39;&#39;）+
    '(' +
    （h &gt;&gt;&gt;（阿尔法？24：16））+
    ', ' +
    （（h＆（alpha？0x00ff0000：0x00ff00））&gt;&gt;&gt;（alpha？16：8））+
    ', ' +
    （（h＆（alpha？0x0000ff00：0x0000ff））&gt;&gt;&gt;（alpha？8：0））+
    （alpha？`，$ {h＆0x000000ff}`：&#39;&#39;）+
    ')'
  );
};
```

<details>
<summary>Examples</summary>

```js
hexToRGB('#27ae60ff'); // 'rgba(39, 174, 96, 255)'
 hexToRGB（ &#39;27ae60&#39;）;  //&#39;rgb（39,174,96）&#39;
hexToRGB('#fff'); // 'rgb(255, 255, 255)'
```

</details>


### httpGet

对传递的URL发出`GET`请求.

Use [`XMLHttpRequest`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) web api对给定的`url`发出`get`请求.
通过调用给定的`callback`和`responseText`来处理`onload`事件.
通过运行提供的`err`函数处理`onerror`事件.
省略第三个参数`err`，默认情况下将错误记录到控制台的`error`流中.

```js
const httpGet =（url，callback，err = console.error）=&gt; {
  const request = new XMLHttpRequest（）;
  request.open（&#39;GET&#39;，url，true）;
  request.onload =（）=&gt; callback（request.responseText）;
  request.onerror =（）=&gt; err（request）;
  request.send（）;
};
```

<details>
<summary>Examples</summary>

```js
httpGet(
  'https://jsonplaceholder.typicode.com/posts/1',
  的console.log
); /*
日志：{
  “userId”：1，
  “id”：1，
  “标题”：“提供或拒绝盲目，欢迎找到选项”
  “身体”：“它需要\ nsuscipit遵循\ nreprehenderit不适可能是这种情况发生的事情的整个\ nnostrum轻易接受的是，他们都非常”
}
*/
```

</details>


### httpPost

对传递的URL发出`POST`请求​​.

Use [`XMLHttpRequest`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) web api对给定的`url`发出`post`请求.
使用`setRequestHeader`方法设置`HTTP`请求头的值.
通过调用给定的`callback`和`responseText`来处理`onload`事件.
通过运行提供的`err`函数处理`onerror`事件.
省略第三个参数`data`，不向提供的`url`发送数据.
省略第四个参数`err`，默认情况下将错误记录到控制台的`error`流中.

```js
const httpPost =（url，data，callback，err = console.error）=&gt; {
  const request = new XMLHttpRequest（）;
  request.open（&#39;POST&#39;，url，true）;
  request.setRequestHeader（&#39;Content-type&#39;，&#39;application / json; charset = utf-8&#39;）;
  request.onload =（）=&gt; callback（request.responseText）;
  request.onerror =（）=&gt; err（request）;
  request.send（数据）;
};
```

<details>
<summary>Examples</summary>

```js
const newPost = {
  userId：1，
  id：1337，
  标题：&#39;Foo&#39;，
  身体：酒吧吧
};
const data = JSON.stringify（newPost）;
httpPost(
  'https://jsonplaceholder.typicode.com/posts',
  数据，
  的console.log
); /*
日志：{
  “userId”：1，
  “id”：1337，
  “title”：“Foo”，
  “身体”：“酒吧吧”
}
*/
httpPost(
  'https://jsonplaceholder.typicode.com/posts',
  null，//不发送正文
  的console.log
); /*
日志：{
  “id”：101
}
*/
```

</details>


### isBrowser

Determines if the current runtime environment is a browser so that front-end modules can run on the server (Node) without throwing errors.

对`window`和`document`的`typeof`值使用`Array.prototype.includes（）`（通常只在浏览器环境中可用的全局变量，除非它们是明确定义的），如果其中一个，则返回`true`他们是&#39;未定义&#39;.
`typeof`允许检查全局变量是否存在而不抛出`ReferenceError`.
如果它们都不是“未定义”，则假定当前环境是浏览器.

```js
const isBrowser =（）=&gt;！[typeof window，typeof document] .includes（&#39;undefined&#39;）;
```

<details>
<summary>Examples</summary>

```js
 isBrowser（）;  // true（浏览器）
 isBrowser（）;  //假（节点）
```

</details>


### mostPerformant

返回执行速度最快的函数数组中函数的索引.

 使用`Array.prototype.map（）`生成一个数组，其中每个值是在`iterations`次之后执行该函数所花费的总时间.  使用之前和之后的`performance.now（）`值的差异来获得高精度的总时间（以毫秒为单位）.
使用`Math.min（）`查找最小执行时间，并返回与最高性能函数的索引相对应的最短时间的索引.
 省略第二个参数`iterations`，使用默认的10,000次迭代.  迭代次数越多，结果越可靠，但需要的时间越长.

```js
const mostPerformant =（fns，iterations = 10000）=&gt; {
  const times = fns.map（fn =&gt; {
    const before = performance.now（）;
    for（let i = 0; i &lt;iterations; i ++）fn（）;
    return performance.now（） - 之前;
  });
  return times.indexOf（Math.min（... times））;
};
```

<details>
<summary>Examples</summary>

```js
mostPerformant([
  () => {
    //在返回`false`之前循环遍历整个数组
    [1,2,3,4,5,6,7,8,9，&#39;10&#39;].every（el =&gt; typeof el ===&#39;number&#39;）;
  },
  () => {
    //只需要在返回false之前达到索引“1”
    [1，&#39;2&#39;，3,4,5,6,7,8,9,10] .every（el =&gt; typeof el ===&#39;number&#39;）;
  }
]); // 1
```

</details>


### nthArg

 创建一个在索引“n”处获取参数的函数.  如果`n`为负数，则返回结尾的第n个参数.

使用`Array.prototype.slice（）`在索引`n`获取所需的参数.

```js
const nthArg = n =&gt;（... args）=&gt; args.slice（n）[0];
```

<details>
<summary>Examples</summary>

```js
const third = nthArg（2）;
 第三（1,2,3）;  // 3
 第三（1,2）;  //未定义
const last = nthArg（-1）;
 最后（1,2,3,4,5）;  // 5
```

</details>


### parseCookie

解析HTTP Cookie标头字符串并返回所有cookie名称 - 值对的对象.

使用`String.prototype.split（&#39;;&#39;）`将键值对彼此分开.
使用`Array.prototype.map（）`和`String.prototype.split（&#39;=&#39;）`将键与每对中的值分开.
使用`Array.prototype.reduce（）`和`decodeURIComponent（）`创建一个包含所有键值对的对象.

```js
const parseCookie = str =&gt;
  海峡
    .分裂（&#39;;&#39;）
    .map（v =&gt; v.split（&#39;=&#39;））
    .reduce（（acc，v）=&gt; {
      acc [decodeURIComponent（v [0] .trim（））] = decodeURIComponent（v [1] .trim（））;
      返回acc;
    }, {});
```

<details>
<summary>Examples</summary>

```js
 parseCookie（&#39;foo = bar; equation = E％3Dmc％5E2&#39;）;  // {foo：&#39;bar&#39;，等式：&#39;E = mc ^ 2&#39;}
```

</details>



将字节数转换为人类可读的字符串.

使用基于指数访问的单元的数组字典.
使用`Number.toPrecision（）`将数字截断为一定数量的数字.
通过构建它来返回经过修饰的字符串，同时考虑所提供的选项以及它是否为负数.
省略第二个参数`precision`，使用默认精度`3`数字.
省略第三个参数`addSpace`，默认情况下在数字和单位之间添加空格.

```js
const prettyBytes =（num，precision = 3，addSpace = true）=&gt; {
  const UNITS = [&#39;B&#39;，&#39;KB&#39;，&#39;MB&#39;，&#39;GB&#39;，&#39;TB&#39;，&#39;PB&#39;，&#39;EB&#39;，&#39;ZB&#39;，&#39;YB&#39;];
  if（Math.abs（num）&lt;1）返回num +（addSpace？&#39;&#39;：&#39;&#39;）+ UNITS [0];
  const exponent = Math.min（Math.floor（Math.log10（num &lt;0？-num：num）/ 3），UNITS.length  -  1）;
  const n = Number（（（num &lt;0？-num：num）/ 1000 ** exponent）.toPrecision（precision））;
  返回（？NUM &lt;0 &#39; - &#39;： &#39;&#39;）+ N +（？addSpace &#39;&#39;： &#39;&#39;）+单元[露出];
};
```

<details>
<summary>Examples</summary>

```js
 prettyBytes（1000）;  //“1 KB”
 prettyBytes（-27145424323.5821,5）;  //“-27.145 GB”
 prettyBytes（123456789,3，false）;  //“123MB”
```

</details>


### randomHexColorCode

生成随机十六进制颜色代码.

 使用`Math.random`生成一个随机的24位（6x4bits）十六进制数.  使用位移，然后使用`toString（16）`将其转换为十六进制字符串.

```js
const randomHexColorCode =（）=&gt; {
  设n =（Math.random（）* 0xfffff * 1000000）.toString（16）;
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

将RGB组件的值转换为颜色代码.

使用按位左移运算符（`&lt;&lt;`）和`toString（16）`，然后`String.padStart（6，&#39;0&#39;）`将给定的RGB参数转换为十六进制字符串，以获得6位十六进制值.

```js
const RGBToHex =（r，g，b）=&gt;（（r &lt;&lt; 16）+（g &lt;&lt; 8）+ b）.toString（16）.padStart（6，&#39;0&#39;）;
```

<details>
<summary>Examples</summary>

```js
 RGBToHex（255,165,1）;  //&#39;ffa501&#39;
```

</details>


### serializeCookie

将cookie名称 - 值对序列化为Set-Cookie标头字符串.

使用模板文字和`encodeURIComponent（）`来创建适当的字符串.

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

测量函数执行所花费的时间.

使用`console.time（）`和`console.timeEnd（）`来衡量开始和结束时间之间的差异，以确定回调执行的时间.

```js
const timeTaken = callback =&gt; {
  console.time（ &#39;timeTaken&#39;）;
  const r = callback（）;
  console.timeEnd（&#39;timeTaken&#39;）;
  返回r;
};
```

<details>
<summary>Examples</summary>

```js
 timeTaken（（）=&gt; Math.pow（2,10））;  // 1024，（已记录）：timeTaken：0.02099609375ms
```

</details>


### toCurrency

取一个数字并返回指定的货币格式.

使用`Intl.NumberFormat`启用国家/货币敏感格式.

```js
const toCurrency =（n，curr，LanguageFormat = undefined）=&gt;
  Intl.NumberFormat（LanguageFormat，{style：&#39;currency&#39;，currency：curr}）.format（n）;
```

<details>
<summary>Examples</summary>

```js
 toCurrency（123456.789，&#39;EUR&#39;）;  //€123,456.79 |  货币：欧元|  currencyLangFormat：Local
 toCurrency（123456.789，&#39;USD&#39;，&#39;en-us&#39;）;  // $ 123,456.79 |  货币：美元|  currencyLangFormat：英语（美国）
 toCurrency（123456.789，&#39;USD&#39;，&#39;fa&#39;）;  // 123,456.79؜$ |  货币：美元|  currencyLangFormat：波斯语
 toCurrency（322342436423.2435，&#39;JPY&#39;）;  //¥322,342,436,423 |  货币：日元|  currencyLangFormat：Local
 toCurrency（322342436423.2435，&#39;JPY&#39;，&#39;fi&#39;）;  // 322 342 436 423¥|  货币：日元|  currencyLangFormat：芬兰语
```

</details>


### toDecimalMark

使用`toLocaleString（）`将浮点运算转换为 [Decimal mark](https://en.wikipedia.org/wiki/Decimal_mark)  形成.  它使用逗号分隔字符串与数字.

 ```js
const toDecimalMark = num =&gt; num.toLocaleString（&#39;en-US&#39;）;
```

<details>
<summary>Examples</summary>

```js
 toDecimalMark（12305030388.9087）;  //“12,305,030,388.909”
```

</details>


### toOrdinalSuffix

为数字添加序数后缀.

使用模运算符（`％`）查找单个和十位数的值.
找出哪些序数模式数字匹配.
如果在青少年模式中找到数字，请使用青少年序数.

```js
const toOrdinalSuffix = num =&gt; {
  const int的= parseInt函数（NUM）;
    digits = [int％10，int％100]，
    ordinals = [&#39;st&#39;，&#39;nd&#39;，&#39;rd&#39;，&#39;th&#39;]，
    oPattern = [1,2,3,4]，
    tPattern = [11,12,13,14,15,16,17,18,19];
  return oPattern.includes（digits [0]）&amp;&amp;！tPattern.includes（digits [1]）
     ？  int +序数[digits [0]  -  1]
    ：int + ordinals [3];
};
```

<details>
<summary>Examples</summary>

```js
 toOrdinalSuffix（ &#39;123&#39;）;  //“123rd”
```

</details>


### validateNumber

如果给定值是数字，则返回“true”，否则返回“false”.

将`！isNaN（）`与`parseFloat（）`结合使用来检查参数是否为数字.
使用`isFinite（）`来检查数字是否有限.
使用`Number（）`来检查强制是否成立.

```js
const validateNumber = n =&gt;！isNaN（parseFloat（n））&amp;&amp; isFinite（n）&amp;&amp; Number（n）== n;
```

<details>
<summary>Examples</summary>

```js
 validateNumber（&#39;10&#39; ）;  //真
```

</details>


### yesNo

如果字符串是`y` /`yes`则返回`true`或如果字符串是&#39;n` /`no`则返回`false`.

使用`RegExp.test（）`检查字符串是否计算为“y / yes”或“n / no”.
省略第二个参数`def`将默认答案设置为“no”.

```js
const yesNo =（val，def = false）=&gt;
   /^(y |yes)$/i.test(val）？  是：/^(n|no)$/i.test(val）？  假：def;
```

<details>
<summary>Examples</summary>

```js
 YESNO（ &#39;Y&#39;）;  //真
 YESNO（ &#39;是&#39;）;  //真
 YESNO（ &#39;否&#39;）;  //假
 yesNo（&#39;Foo&#39;，true）;  //真
```

</details>



## Collaborators

| [<img src="https://raw.githubusercontent.com/Chalarangelo.png" width="100px;"/>](https://raw.githubusercontent.com/Chalarangelo)<br/> [<sub>Angelos Chalaris</sub>](https://raw.githubusercontent.com/Chalarangelo) | [<img src="https://raw.githubusercontent.com/flxwu.png" width="100px;"/>](https://raw.githubusercontent.com/flxwu)<br/> [<sub>Felix Wu</sub>](https://raw.githubusercontent.com/Pl4gue) | [<img src="https://raw.githubusercontent.com/fejes713.png" width="100px;"/>](https://raw.githubusercontent.com/fejes713)<br/> [<sub>Stefan Feješ</sub>](https://raw.githubusercontent.com/fejes713)  | [<img src="https://raw.githubusercontent.com/kingdavidmartins.png" width="100px;"/>](https://raw.githubusercontent.com/kingdavidmartins)<br/> [<sub>King David Martins</sub>](https://raw.githubusercontent.com/iamsoorena) | [<img src="https://raw.githubusercontent.com/iamsoorena.png" width="100px;"/>](https://raw.githubusercontent.com/iamsoorena)<br/> [<sub>Soorena Soleimani</sub>](https://raw.githubusercontent.com/iamsoorena) |
| --- | --- | --- | --- | --- |
| [<img src="https://raw.githubusercontent.com/elderhsouza.png" width="100px;"/>](https://raw.githubusercontent.com/elderhsouza)<br/> [<sub>Elder Henrique Souza</sub>](https://raw.githubusercontent.com/elderhsouza) | [<img src="https://raw.githubusercontent.com/skatcat31.png" width="100px;"/>](https://raw.githubusercontent.com/skatcat31)<br/> [<sub>Robert Mennell</sub>](https://raw.githubusercontent.com/skatcat31) | [<img src="https://raw.githubusercontent.com/atomiks.png" width="100px;"/>](https://raw.githubusercontent.com/atomiks)<br/> [<sub>atomiks</sub>](https://raw.githubusercontent.com/atomiks)  |


## Credits

*标志制作 [Angelos Chalaris](https://github.com/Chalarangelo) 根据该许可证 [MIT](https://opensource.org/licenses/MIT) 执照.*
*本自述文件使用 [markdown-builder](https://github.com/30-seconds/markdown-builder).*
