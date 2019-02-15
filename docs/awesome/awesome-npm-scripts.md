## Awesome npm scripts [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/RyanZim/awesome-npm-scripts/master/npm-logo.png" align="right" width="150">](https://www.npmjs.com)

&gt;使用npm作为构建工具的一切都很棒.

你可能还喜欢 [awesome-npm](https://github.com/sindresorhus/awesome-npm).

 **注意：我目前忙于积极扩展此列表;  因此，我决定将其作为一个 [OPEN Open Source Project](http://openopensource.org) .  为获得重要和有价值贡献的个人提供项目承诺，以便他们认为合适.**

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Articles](#articles)
- [Videos/Talks](#videostalks)
- [Task Runners](#task-runners)
- [File Watchers](#file-watchers)
- [Dev Servers](#dev-servers)
- [Cross-platform Utilities](#cross-platform-utilities)
  - [Utility Packs](#utility-packs)
- [Other Utilities](#other-utilities)
- [Miscellaneous](#miscellaneous)
- [Cross-platform Shell Reference](#cross-platform-shell-reference)
- [`npm run` Reference](#npm-run-reference)
- [Contributing](#contributing)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Articles

- [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/) -  Keith Cirkel撰写的博客文章.
- [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) - 续集 [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/).
- [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8) -  Cory House的文章.
- [Helpers and tips for npm run scripts](http://michael-kuehnel.de/tooling/2018/03/22/helpers-and-tips-for-npm-run-scripts.html) - MichaelKühnel的博客文章涵盖了高级主题.

## Videos/Talks

- [Advanced front-end automation with npm scripts](https://www.youtube.com/watch?v=0RYETb9YVrk) - 由Kate Hudson在2015年的Nordic.js上讲话
- [How to create a build system with npm scripts](http://www.penta-code.com/how-to-create-a-build-system-with-npm-scripts/) - 关于设置前端构建系统的视频教程系列.

## Task Runners

用于并行或顺序运行多个命令或npm脚本的工具.

- [script-runner](https://github.com/paulpflug/script-runner) - 简洁的任务运行器，简洁的语法.
- [npm-run-all](https://github.com/mysticatea/npm-run-all) - 功能齐全的任务运行员.
- [redrun](https://github.com/coderaiser/redrun) - 从package.json扩展脚本以提高执行速度.

## File Watchers

用于监视源文件并在任何文件发生更改时运行构建命令的工具.

- [onchange](https://github.com/Qard/onchange)   - `onchange <glob>   -  <command>  `.
- [watch](https://github.com/mikeal/watch)   - `看 <command><directory>  `.

## Dev Servers

- [http-server](https://github.com/indexzero/http-server) - 简单的零配置命令行http服务器.
- [live-server](https://github.com/tapio/live-server) - 具有实时重新加载功能的简单开发http服务器.

## Cross-platform Utilities

实用程序可执行常见的命令行任务，而无需担心跨平台兼容性.

- [rimraf](https://github.com/isaacs/rimraf)   - 删除文件或目录;  比如`rm -rf`.
- [del-cli](https://github.com/sindresorhus/del-cli) - 更安全的文件和文件夹删除.
- [mkdirp](https://github.com/substack/node-mkdirp)   - 创建目录，根据需要创建父目录;  比如`mkdir -p`.
- [cpr](https://github.com/davglass/cpr) -  Nodejs的`cp -r`
- [cpy-cli](https://github.com/sindresorhus/cpy-cli) - 文件/目录复制/重命名.
- [copyfiles](https://github.com/calvinmetcalf/copyfiles) - 将文件列表复制到目录中.
- [sync-files](https://github.com/byteclubfr/node-sync-files) - `rsync`-like目录与watch模式同步.
- [echo-cli](https://github.com/iamakulov/echo-cli) - 具有JS转义序列支持的跨平台`echo`.
- [clear-cli](https://github.com/sindresorhus/clear-cli) - 清除终端.
- [cross-env](https://github.com/kentcdodds/cross-env) - 为脚本设置环境变量，unix-style.
- [cross-os](https://github.com/milewski/cross-os) - 运行特定于平台的npm脚本.
- [ntee](https://github.com/stefanmaric/ntee)   - 从标准输入读取并写入标准输出和文件的实用程序;  像Unix`tee`.
- [catw](https://github.com/substack/catw)   - 使用可选的监视模式将文件打印到标准输出;  有点像Unix`cat`.

### Utility Packs

- [shx](https://github.com/shelljs/shx)   - 收集在Node.js中实现的常见Unix实用程序;  示例用法：`shx rm somefile`.

## Other Utilities

- [hashmark](https://github.com/keithamus/hashmark) - 获取文件的内容并输出为名称中带有哈希的新文件.
- [gzip-size-cli](https://github.com/sindresorhus/gzip-size-cli) - 获取文件或标准输入的gzip大小.
- [opn-cli](https://github.com/sindresorhus/opn-cli) - 使用用户的首选应用程序打开网站，文件，可执行文件等.
- [headr](https://github.com/heldr/headr) - 将标题/横幅信息添加到文件中.
- [Bower files CLI](https://github.com/thompsonemerson/bower-files-cli) - 在命令行上获取主要的凉亭文件
- [cli-error-notifier](https://github.com/micromata/cli-error-notifier) - 当npm脚本失败时发送本机桌面通知.

## Miscellaneous

- [screwy](https://github.com/samueleaton/screwy) -  npm脚本GUI.
- [Forrest](https://github.com/stefanjudis/forrest) -  npm脚本桌面客户端.
- [run-npm](https://github.com/timoxley/npm-run)   - 运行本地安装的节点模块可执行文件.  用于调试npm脚本.
- [npm-quick-run](https://github.com/bahmutov/npm-quick-run) - 通过前缀快速运行npm脚本而无需键入全名.
- [edit-script](https://github.com/RyanZim/edit-script) - 从命令行编辑npm脚本，而不必担心JSON转义.
- [ntl](https://github.com/ruyadorno/ntl) - 用于列出和运行npm脚本的交互式cli菜单.

## Cross-platform Shell Reference

在Unix和Windows上运行相同的shell操作符和命令的快速参考.

  - `&amp;&amp;`按顺序运行命令.  如果命令失败，则脚本退出.
  - `|`将一个命令的stdout输入到下一个命令的stdin中.  （`do-something |别的东西`）
  - `&gt;`将命令的stdout写入文件.  （`do-something&gt; file`）
- `<` sends the contents of a file to a command's stdin. (`command < file`)
  - `cd <dir>  `将当前工作目录更改为` <dir>  `.  请注意，`cd`单独打印Windows上的当前工作目录，但将工作目录更改为\ * nix上的`~`.

## `npm run` Reference

 你可以使用`npm run-script`或`npm run`;  他们都做同样的事情，但是&#39;npm run`更短.

- 只运行`npm run`打印脚本列表.
  - 运行`npm run script`（其中`script`是你脚本的名称）将运行`prescript`，`script`和`postscript`;  以该顺序.
  - 你不能嵌套`pre`和`post`钩子（即`preprescript`不起作用）.
  - 您可以通过将`--`传递给`npm run`，然后传递参数来将参数传递给脚本.  示例：给定脚本“mocha”：“mocha”`，您可以运行`npm run mocha  -  --reporter xunit`.  这有效地运行`mocha --reporter xunit`.
  - 运行`npm test`与运行`npm run test`相同.  这同样适用于`npm start`和`npm stop`.
- 你可以运行`npm run <script> -s` to silence the default npm output (useful for calling a script within another script).

## Contributing

See [CONTRIBUTING.md](https://github.com/RyanZim/awesome-npm-scripts/blob/master/CONTRIBUTING.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
