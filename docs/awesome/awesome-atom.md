<div class="github-widget" data-repo="mehcode/awesome-atom"></div>
## Awesome Atom [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 令人愉快的Atom包和资源的精选列表.  为了更加棒极了，请查看 [awesome](https://github.com/sindresorhus/awesome).


- [Themes](http://enrmarc.github.io/atom-theme-gallery/)

## Syntax

语言包使用语法高亮和/或扩展编辑器
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

如果还没有释放出令人敬畏的落叶的必杀技：
 &gt; lint是最初赋予特定程序的名称，该程序在C语言源代码中标记了一些可疑和不可移植的构造（可能是错误）.  该术语现在通常应用于标记以任何计算机语言编写的软件中的可疑用法的工具.

要启用linting，你需要一般 [linter](https://atom.io/packages/linter)  它为特定语言的提供者插件提供接口.  可在以下位置找到当前插件的完整列表 [atomlinter.github.io](http://atomlinter.github.io/)，一些例子是：

 -  C ++
   - [linter-clang](https://atom.io/packages/linter-clang)
   - [linter-cppcheck](https://atom.io/packages/linter-cppcheck)
   - [linter-gcc](https://atom.io/packages/linter-gcc) - 即时掉毛！
   - [linter-cpplint](https://atom.io/packages/linter-cpplint) - 检查谷歌风格指南
 - [CSS](https://atom.io/packages/linter-stylelint) -  stylelint
 - [JavaScript](https://atom.io/packages/linter-eslint) -  eslint
 - [Python](https://atom.io/packages/linter-pylama) -  pylama
 - [SASS](https://atom.io/packages/linter-sass-lint) -  sass-lint
 - [Stylus](https://atom.io/packages/linter-stylint) -  stylint
 - [TypeScript](https://atom.io/packages/linter-tslint) -  tslint

 ![atom-linter](https://camo.githubusercontent.com/70b6e697c9d793642414b4ea6d08dbb9678877b3/687474703a2f2f672e7265636f726469742e636f2f313352666d6972507a322e676966)

## Build

要启用构建，您需要通用 [build](https://atom.io/packages/build) 它为特定语言的提供者插件提供接口，并添加了集成 [lint](#lint) .  可在以下位置找到当前插件的完整列表 [atombuild.github.io](http://atombuild.github.io/)，一些例子是：

 - [AppleScript](https://atom.io/packages/build-applescript) -  oscompile
 - [C/C++/Objective C](https://atom.io/packages/build-xcodebuild) -  xcodebuild
 - [CoffeeScript](https://atom.io/packages/build-coffee) - 咖啡
 - [GNU Make](https://github.com/AtomBuild/atom-build-make) - 制作
 - [Sass](https://atom.io/packages/build-sass) - 萨斯
 - [TypeScript](https://atom.io/packages/build-tsc) -  tsc

 ![atom-build](https://camo.githubusercontent.com/ca10be645c7a2024dddc550466e67d692fb411ed/68747470733a2f2f6e6f7365676c69642e6769746875622e696f2f746172676574732d6d616b652e676966)

## Extensions

#### [Nuclide](https://nuclide.io/)
&gt;用于Web和本机移动开发的开放式IDE，构建于Atom维护之上 [Facebook](https://github.com/facebook/nuclide).

![](https://nuclide.io/static/images/docs/promo-hack.png)

## Collaboration

#### [CodeSideStory](https://atom.io/packages/codesidestory-atom)
 &gt; Atom / Slack集成，可直接从编辑器开始有关代码的对话.  记录屏幕并将其存档在行号旁边，以便为代码提供更多上下文.

![](https://storage.googleapis.com/codesidestory/static/media/atom_ss.c29b4b0b.png)

## Uncategorized

#### [Advanced Open File](https://atom.io/packages/advanced-open-file)
 &gt;帮助Atom用户轻松打开文件和文件夹.  如果它们当前不存在，它还可以创建新文件和文件夹.

![](http://osmose.github.io/advanced-open-file/demo.gif)

#### [Atom Reverser](https://atom.io/packages/atom-reverser)
 &gt;撤消当前的选择;  例如`false`到&#39;true`

![Atom Reverser in action](https://i.imgur.com/YawGVsN.gif)

#### [Atom Terminal](https://atom.io/packages/atom-terminal)
&gt;在Atom中使用“Ctrl-Shift-T”在当前文件的目录上启动终端应用程序.

![](https://raw.githubusercontent.com/karan/atom-terminal/master/terminal.gif)

#### [Autocomplete module import](https://atom.io/packages/autocomplete-module-import)
&gt;从import / require语句中搜索并安装npm软件包 [Algolia](https://www.algolia.com/)

![](https://camo.githubusercontent.com/53350e9c6d303f60101e1644605fe62f529e45f2/687474703a2f2f672e7265636f726469742e636f2f643576695542385859372e676966)

#### [Beautify](https://atom.io/packages/atom-beautify)
> [Beautify](https://github.com/beautify-web/js-beautify)
HTML（包括 [Handlebars](http://handlebarsjs.com/)),
CSS（包括 [Sass](http://sass-lang.com/) 和 [LESS](http://lesscss.org/)),
JavaScript，以及Atom中的更多内容.

#### [Code Peek](https://atom.io/packages/code-peek)
&gt;从当前编辑器的上下文中快速查看和编辑单独文件中的函数.

![Code Peek Demo](https://github.com/DFreds/code-peek-atom/blob/master/code-peek.gif?raw=true)

#### [Color Picker](https://atom.io/packages/color-picker)
 &gt;支持HEX，HEXa，RGB，RGBa，HSL，HSLa，HSV，HSVa，VEC3，VEC4的颜色选择器，并且能够在格式之间进行转换.  它还检查Sass和LESS颜色变量.

![Color Picker in action](https://github.com/thomaslindstrom/color-picker/raw/master/preview.gif)

#### [Copy Paste](https://atom.io/packages/copy-paste)
 &gt;代码中的类型来自剪贴板/缓冲区.  只需复制代码并点击快捷方式即可查看输入的代码.  复制粘贴是截屏和在线课程的理想选择.

#### [CSS Declaration Sorter](https://atom.io/packages/css-declaration-sorter)
 &gt;在Atom中对CSS，Less或Sass声明进行排序，永远不会感到疲倦.  您可以从各种现成订单中进行选择，以保持CSS整洁.

![CSS Declaration Sorter Demo](https://github.com/Siilwyn/css-declaration-sorter-atom/raw/master/show-off.gif)

#### [Duplicate Selection](https://atom.io/packages/duplicate-line-or-selection)
&gt;如果有选择，则复制选择，否则复制该行.

#### [Editor Config](https://atom.io/packages/editorconfig)
> [EditorConfig](http://editorconfig.org) 帮助开发者在不同编辑器之间保持一致的编码风格

![atom-editor-config](https://f.cloud.github.com/assets/170270/2327994/dfe40cb4-a3f6-11e3-862f-894999973373.png)

#### [Emmet](https://atom.io/packages/emmet)
 &gt;插件，大大改善了HTML和CSS写作.  快捷方式可以扩展为完整的HTML或CSS选择器集.

#### [File Icons](https://atom.io/packages/file-icons)
 &gt;向atom添加特定于文件的图标，以改善视觉效果.  使用树视图和模糊查找器和选项卡.

#### [Fonts](https://atom.io/packages/fonts)
&gt;很多等宽字体.

#### [Git Time Machine](https://atom.io/packages/git-time-machine)
&gt;它显示了当前文件的提交随时间变化的可视图，您可以在时间图上单击它或将鼠标悬停在图上并查看时间范围的所有提交.

![git-time-machine](https://i.github-camo.com/62085307dccead1c2f5efdf4d7a40f9cdb777b93/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6c6974746c656265652f6769742d74696d652d6d616368696e652f6d61737465722f7265736f75726365732f74696d656d616368696e652e676966)

#### [html-to-css](https://atom.io/packages/html-to-css)
 &gt;根据选定的HTML生成CSS样板.  支持CSS，SCSS，Sass，LESS，BEM，JSX.

![html-to-css](https://camo.githubusercontent.com/b164c4b7b244006a7bcf7442d8c4b0812e4edcd0/687474703a2f2f64726163756c2e6b696c6c2e706c2f2537456172642f68746d6c746f6373732e676966)

#### [iMDone](https://atom.io/packages/imdone-atom)
&gt;代码中的TODO，FIXME，HACK等任务板.

![](https://cloud.githubusercontent.com/assets/441774/9805863/757d5532-5814-11e5-8759-4196bd92c822.gif)

#### [Jumpy](https://atom.io/packages/jumpy)
&gt;一个Atom包，可创建动态热键以跨可见窗格跳转文件.

![](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif)

#### [Merge Conflicts](https://atom.io/packages/merge-conflicts)
&gt;解决Atom中的git合并冲突.

![](https://raw.github.com/smashwilson/merge-conflicts/master/docs/conflict-resolution.gif)

#### [Minimap](https://atom.io/packages/minimap)
&gt;完整源代码的预览.

#### [Pigments](https://atom.io/packages/pigments)
&gt;用于在项目和文件中显示颜色的包.

![](http://abe33.github.io/atom-pigments/pigments.gif?raw=true)

#### [Project Plus](https://atom.io/packages/project-plus)
&gt;简单易用的Atom项目管理.

![](https://raw.githubusercontent.com/mehcode/atom-project-plus/master/project-plus.gif)

#### [Sort Lines](https://atom.io/packages/sort-lines)
 &gt;排序你的线.  永远不会累.

![](https://camo.githubusercontent.com/59de82a667ea690b778abaa5ba8a407f8659ebb3/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f323938382f313739363839312f38356536396666322d366139332d313165332d383961632d3331393237663630343539322e676966)

#### [Sorter](https://atom.io/packages/sorter)
 &gt;排序行，JSON，CSS，HTML，CSV.  恢复分号.  尊重缩进.  支持自然排序.

#### [Sync Settings](https://atom.io/packages/sync-settings)
&gt;在Atom实例之间同步程序包设置，键盘映射和已安装的程序包.

#### [PlatformIO IDE Terminal](https://atom.io/packages/platformio-ide-terminal)
&gt; Atom的终端包，包含用于PlatformIO IDE的主题，API等.
&gt;这是一个维护（截至2017-07-13）的终端加分叉.  

![](https://raw.githubusercontent.com/jeremyramin/terminal-plus/master/resources/demo.gif)

#### [TernJS](https://atom.io/packages/atom-ternjs)
&gt;使用tern.js和autocomplete-plus的原子的Javascript代码智能.

### [Test Navigator](https://atom.io/packages/test-navigator)
&gt;在测试和实施文件之间快速导航.

![Test Navigator Demo](https://github.com/DFreds/test-navigator-atom/blob/master/test-navigator.gif?raw=true)

#### [Themer](https://themer.mjswensen.com)
&gt;从您喜欢的颜色生成Atom语法/ UI主题包（以及其他工具的匹配主题）.

#### [Toggle Quotes](https://atom.io/packages/toggle-quotes)
&gt;在单引号和双引号之间快速切换.

#### [Tree View Search Bar](https://atom.io/packages/tree-view-search-bar)
&gt;快速查看树状视图.
