<div class="github-widget" data-repo="mehcode/awesome-atom"></div>
## Awesome Atom [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

令人愉快的 Atom 包和资源的精选列表. 更多精彩，请查看 [awesome](https://github.com/sindresorhus/awesome).


- [Themes](http://enrmarc.github.io/atom-theme-gallery/)

## Syntax

语言包通过语法高亮和/或扩展编辑器
特定语言或文件格式的片段.

 - [Angular](https://atom.io/packages/angularjs)
 - [Vue.js](https://atom.io/packages/language-vue)
 - [Dockerfile](https://atom.io/packages/language-docker)
 - [Markdown](https://atom.io/packages/language-markdown)
 - [React](https://atom.io/packages/react)
 - [Stylus](https://atom.io/packages/stylus)
 - [Pug](https://atom.io/packages/language-pug)
 - [Tcl](https://atom.io/packages/language-tcl)
 - [TypeScript](https://atom.io/packages/atom-typescript)

## Lint

如果 linting 的令人敬畏的必杀技还没有释放在你身上：
 &gt; lint 最初是一个特定程序的名称，该程序在 C 语言源代码中标记了一些可疑和不可移植的结构（可能是错误）. 该术语现在普遍适用于标记以任何计算机语言编写的软件中可疑用法的工具.

要启用 linting，您需要一般 [linter](https://atom.io/packages/linter) 它为特定语言的提供程序插件提供接口. 当前插件的完整列表可以在以下位置找到 [atomlinter.github.io](http://atomlinter.github.io/)，几个例子是：

 - C++
   - [linter-clang](https://atom.io/packages/linter-clang)
   - [linter-cppcheck](https://atom.io/packages/linter-cppcheck)
   - [linter-gcc](https://atom.io/packages/linter-gcc) - 即时检查！
   - [linter-cpplint](https://atom.io/packages/linter-cpplint) - 检查谷歌风格指南
 - [CSS](https://atom.io/packages/linter-stylelint) — stylelint
 - [JavaScript](https://atom.io/packages/linter-eslint) - eslint
 - [Python](https://atom.io/packages/linter-pylama) — 皮拉马
 - [SASS](https://atom.io/packages/linter-sass-lint) — sass-lint
 - [Stylus](https://atom.io/packages/linter-stylint) — 风格
 - [TypeScript](https://atom.io/packages/linter-tslint) - tslint

 ![atom-linter](https://camo.githubusercontent.com/70b6e697c9d793642414b4ea6d08dbb9678877b3/687474703a2f2f672e7265636f726469742e636f2f313352666d6972507a322e676966)

## Build

要启用构建，您需要常规 [build](https://atom.io/packages/build) 它为特定语言的提供程序插件提供接口，并添加了与 [lint](#lint) . 当前插件的完整列表可以在以下位置找到 [atombuild.github.io](http://atombuild.github.io/)，几个例子是：

 - [AppleScript](https://atom.io/packages/build-applescript) — 编译
 - [C/C++/Objective C](https://atom.io/packages/build-xcodebuild) — xcodebuild
 - [CoffeeScript](https://atom.io/packages/build-coffee) - 咖啡
 - [GNU Make](https://github.com/AtomBuild/atom-build-make) - 制作
 - [Sass](https://atom.io/packages/build-sass) — 萨斯
 - [TypeScript](https://atom.io/packages/build-tsc) - TSC

 ![atom-build](https://camo.githubusercontent.com/ca10be645c7a2024dddc550466e67d692fb411ed/68747470733a2f2f6e6f7365676c69642e6769746875622e696f2f746172676574732d6d616b652e676966)

## Extensions

#### [Nuclide](https://nuclide.io/)
&gt; 一个用于 Web 和本机移动开发的开放式 IDE，建立在 Atom 之上，由 [Facebook](https://github.com/facebook/nuclide).

![](https://nuclide.io/static/images/docs/promo-hack.png)

## Collaboration

#### [CodeSideStory](https://atom.io/packages/codesidestory-atom)
 &gt; Atom/Slack 集成，可直接从编辑器开始有关代码的对话. 记录屏幕并将其存档在行号旁边，以便为您的代码提供更多上下文.

![](https://storage.googleapis.com/codesidestory/static/media/atom_ss.c29b4b0b.png)

## Uncategorized

#### [Advanced Open File](https://atom.io/packages/advanced-open-file)
 &gt; 帮助 Atom 用户轻松打开文件和文件夹. 它还可以创建新的文件和文件夹（如果它们当前不存在）.

![](http://osmose.github.io/advanced-open-file/demo.gif)

#### [Atom Reverser](https://atom.io/packages/atom-reverser)
 &gt; 反转您当前的选择； 例如“假”到“真”

![Atom Reverser in action](https://i.imgur.com/YawGVsN.gif)

#### [Atom Terminal](https://atom.io/packages/atom-terminal)
&gt; 在 Atom 中使用“Ctrl-Shift-T”在当前文件目录中启动终端应用程序.

![](https://raw.githubusercontent.com/karan/atom-terminal/master/terminal.gif)

#### [Autocomplete module import](https://atom.io/packages/autocomplete-module-import)
&gt; 通过 import/require 语句搜索并安装 npm 包 [Algolia](https://www.algolia.com/)

![](https://camo.githubusercontent.com/53350e9c6d303f60101e1644605fe62f529e45f2/687474703a2f2f672e7265636f726469742e636f2f643576695542385859372e676966)

#### [Beautify](https://atom.io/packages/atom-beautify)
> [Beautify](https://github.com/beautify-web/js-beautify)
HTML（包括 [Handlebars](http://handlebarsjs.com/)),
CSS（包括 [Sass](http://sass-lang.com/) 和 [LESS](http://lesscss.org/)),
JavaScript，以及 Atom 中的更多内容.

#### [Code Peek](https://atom.io/packages/code-peek)
&gt; 从当前编辑器的上下文中快速查看和编辑单独文件中的函数.

![Code Peek Demo](https://github.com/DFreds/code-peek-atom/blob/master/code-peek.gif?raw=true)

#### [Color Picker](https://atom.io/packages/color-picker)
 &gt; 支持 HEX、HEXa、RGB、RGBa、HSL、HSLa、HSV、HSVa、VEC3、VEC4 的颜色选择器 – 并且能够在格式之间进行转换. 它还检查 Sass 和 LESS 颜色变量.

![Color Picker in action](https://github.com/thomaslindstrom/color-picker/raw/master/preview.gif)

#### [Copy Paste](https://atom.io/packages/copy-paste)
 &gt; 从剪贴板/缓冲区中输入您的代码. 只需复制代码并点击快捷方式即可观看正在键入的代码. 复制粘贴是截屏视频和在线课程的理想选择.

#### [CSS Declaration Sorter](https://atom.io/packages/css-declaration-sorter)
 &gt; 在 Atom 中对您的 CSS、Less 或 Sass 声明进行排序，永远不会厌倦. 您可以从各种现成的订单中进行选择，以保持您的 CSS 整洁.

![CSS Declaration Sorter Demo](https://github.com/Siilwyn/css-declaration-sorter-atom/raw/master/show-off.gif)

#### [Duplicate Selection](https://atom.io/packages/duplicate-line-or-selection)
&gt; 如果有则复制选区，否则复制线.

#### [Editor Config](https://atom.io/packages/editorconfig)
> [EditorConfig](http://editorconfig.org) 帮助开发人员在不同的编辑器之间保持一致的编码风格

![atom-editor-config](https://f.cloud.github.com/assets/170270/2327994/dfe40cb4-a3f6-11e3-862f-894999973373.png)

#### [Emmet](https://atom.io/packages/emmet)
 &gt; 大大提高HTML和CSS编写的插件. 快捷方式可以扩展为完整的 HTML 或 CSS 选择器集.

#### [File Icons](https://atom.io/packages/file-icons)
 &gt; 将文件特定图标添加到 atom 以改进视觉 grepping. 与树视图和模糊查找器和选项卡一起使用.

#### [Fonts](https://atom.io/packages/fonts)
&gt; 许多等宽字体.

#### [Git Time Machine](https://atom.io/packages/git-time-machine)
&gt; 它显示了随着时间的推移对当前文件的提交的可视化图，您可以在时间图上单击它或将鼠标悬停在图上并查看某个时间范围内的所有提交.

![git-time-machine](https://i.github-camo.com/62085307dccead1c2f5efdf4d7a40f9cdb777b93/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6c6974746c656265652f6769742d74696d652d6d616368696e652f6d61737465722f7265736f75726365732f74696d656d616368696e652e676966)

#### [html-to-css](https://atom.io/packages/html-to-css)
 &gt; 根据选定的 HTML 生成 CSS 样板. 支持 CSS、SCSS、Sass、LESS、BEM、JSX.

![html-to-css](https://camo.githubusercontent.com/b164c4b7b244006a7bcf7442d8c4b0812e4edcd0/687474703a2f2f64726163756c2e6b696c6c2e706c2f2537456172642f68746d6c746f6373732e676966)

#### [iMDone](https://atom.io/packages/imdone-atom)
&gt; 代码中用于 TODO、FIXME、HACK 等的任务板.

![](https://cloud.githubusercontent.com/assets/441774/9805863/757d5532-5814-11e5-8759-4196bd92c822.gif)

#### [Jumpy](https://atom.io/packages/jumpy)
&gt; 一个 Atom 包，它创建动态热键以在可见窗格中跳转文件.

![](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif)

#### [Merge Conflicts](https://atom.io/packages/merge-conflicts)
&gt; 解决 Atom 中的 git 合并冲突.

![](https://raw.github.com/smashwilson/merge-conflicts/master/docs/conflict-resolution.gif)

#### [Minimap](https://atom.io/packages/minimap)
&gt; 完整源代码的预览.

#### [Pigments](https://atom.io/packages/pigments)
&gt; 在项目和文件中显示颜色的包.

![](http://abe33.github.io/atom-pigments/pigments.gif?raw=true)

#### [Project Plus](https://atom.io/packages/project-plus)
&gt; Atom 中非常棒的项目管理.

![](https://raw.githubusercontent.com/mehcode/atom-project-plus/master/project-plus.gif)

#### [Sort Lines](https://atom.io/packages/sort-lines)
 &gt; 对您的台词进行排序. 永远不会累.

![](https://camo.githubusercontent.com/59de82a667ea690b778abaa5ba8a407f8659ebb3/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f323938382f313739363839312f38356536396666322d366139332d313165332d383961632d3331393237663630343539322e676966)

#### [Sorter](https://atom.io/packages/sorter)
 &gt; 对行、JSON、CSS、HTML、CSV 进行排序. 恢复分号. 尊重缩进. 支持自然排序.

#### [Sync Settings](https://atom.io/packages/sync-settings)
&gt; 跨 Atom 实例同步包设置、键盘映射和已安装的包.

#### [PlatformIO IDE Terminal](https://atom.io/packages/platformio-ide-terminal)
&gt; Atom 的终端包，包含主题、API 和更多 PlatformIO IDE.
&gt; 这是 terminal-plus 的维护（截至 2017-07-13）分支.  

![](https://raw.githubusercontent.com/jeremyramin/terminal-plus/master/resources/demo.gif)

#### [TernJS](https://atom.io/packages/atom-ternjs)
&gt; 带有 tern.js 和 autocomplete-plus 的 atom Javascript 代码智能.

### [Test Navigator](https://atom.io/packages/test-navigator)
&gt; 在测试和实施文件之间快速导航.

![Test Navigator Demo](https://github.com/DFreds/test-navigator-atom/blob/master/test-navigator.gif?raw=true)

#### [Themer](https://themer.mjswensen.com)
&gt; 从您喜欢的颜色生成 Atom 语法/UI 主题包（以及与您的其他工具匹配的主题）.

#### [Toggle Quotes](https://atom.io/packages/toggle-quotes)
&gt; 在单引号和双引号之间快速切换.

#### [Tree View Search Bar](https://atom.io/packages/tree-view-search-bar)
&gt; 在树视图中快速查看.
