<div class="github-widget" data-repo="bcoe/awesome-cross-platform-nodejs"></div>
<div align="center">
  <img src="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/master/logo.svg?sanitize=true" width="500"/>
  <br>
  <a href="https://awesome.re">
	  <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <p>用于编写跨平台Node.js代码的精彩开发人员工具的精选列表. </p>
</div>



## Resources

- [Core Node.js documentation](https://nodejs.org/en/docs/) - 特别是 [`os`](https://nodejs.org/api/os.html), [`path`](https://nodejs.org/api/path.html), [`fs`](https://nodejs.org/api/fs.html), [`process`](https://nodejs.org/api/process.html) 和 [`child_process`](https://nodejs.org/api/child_process.html) 模块.
- [Cross-platform Node.js guide](https://github.com/ehmicky/cross-platform-node-guide) - 如何编写跨平台的Node.js代码.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - 在Microsoft平台上使用Node.js的提示，技巧和资源.
- [Writing Cross-Platform Node.js](http://shapeshed.com/writing-cross-platform-node/) - 精彩的教程，涵盖编写跨平台代码时出现的许多常见问题：路径创建，脚本执行，换行符.

## Applications

### Development environment

- [Node.js](https://nodejs.org/en/download/) - 各种平台的Node.js安装程序.
- [nvm-windows](https://github.com/coreybutler/nvm-windows) - 在Windows计算机上管理Node.js的多个安装.
- [nvm](https://github.com/creationix/nvm) / [n](https://github.com/tj/n) -  macOS / Linux的节点版本管理器.
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - 在Windows上升级npm.
- [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) - 使用npm安装适用于Windows的C ++ Build Tools.

### Continuous integration

- [AppVeyor](http://www.appveyor.com/)   - 专注于Windows.  OSS项目提供免费等级.
- [Travis](https://travis-ci.org/)   -  Windows / macOS / Linux.  OSS项目免费.
- [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/)   -  Windows / macOS / Linux.  适用于具有10个并行作业的OSS项目.

### Virtualization

- [ievms](https://github.com/amichaelparker/ievms)   -  Microsoft提供的免费虚拟机映像的自动安装程序，用于在多个IE版本上进行测试.  这些图像可用于跨平台测试各种技术，但请确保您阅读并理解微软的许可.
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - 用于运行x86虚拟机的通用软件.
- [Docker](https://www.docker.com/) - 在通用操作系统上创建，部署和管理虚拟化应用程序容器的软件平台，具有相关工具生态系统.

### Compatibility

- [Wine](https://www.winehq.org/) - 在Linux，Mac，BSD和Solaris上运行Windows API调用.
- [Cygwin](https://www.cygwin.com/) - 在Windows上运行POSIX.
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) - 在Windows上运行Linux命令行（ELF二进制执行，系统调用，文件系统，Bash，核心实用程序，常见应用程序）.
- [MinGW](http://www.mingw.org/) -  Windows上的`gcc`.
- [msys](http://www.mingw.org/wiki/msys) / [Git Bash](https://gitforwindows.org/) -  Windows上的Bash.

### Databases

- [Redis](https://github.com/tporadowski/redis) -  Redis for Windows的本机端口.

## Libraries

### OS identification

- [is-windows](https://github.com/jonschlinkert/is-windows) - 检测当前平台是否为Windows.
- [is-wsl](https://github.com/sindresorhus/is-wsl) - 检测当前平台是否为WSL（适用于Linux的Windows子系统）.
- [getos](https://github.com/retrohacker/getos) - 检索当前的操作系统，包括Linux发行版.
- [os-name](https://github.com/sindresorhus/os-name) - 获取当前操作系统的名称.
- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - 硬件/软件系统信息.

### Shell

- [execa](https://github.com/sindresorhus/execa) - &#39;child_process.{execFile，exec}`的跨平台实现.
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - &#39;child_process.spawn（）`的跨平台实现.
- [shelljs](https://github.com/shelljs/shelljs) - 跨平台的Unix shell命令.
- [node-windows](https://github.com/coreybutler/node-windows) -  Windows支持Node.js脚本（守护进程，事件日志，UAC等）.
- [log-symbols](https://github.com/sindresorhus/log-symbols) -  Windows回退的各种日志级别的彩色符号.
- [figures](https://github.com/sindresorhus/figures) - 带有Windows回退的Unicode符号.
- [clipboardy](https://github.com/sindresorhus/clipboardy) / [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 跨平台复制/粘贴.

### Environment

- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台设置环境变量.
- [user-home](https://github.com/sindresorhus/user-home)   - 获取用户主目录的路径.  跨平台.
- [username](https://github.com/sindresorhus/username) - 获取当前用户名.
- [osenv](https://github.com/npm/osenv) - 跨平台环境变量.
- [is-elevated](https://github.com/sindresorhus/is-elevated) - 检查进程是否以提升的权限运行.
- [which](https://github.com/npm/node-which) -  Unix的`which`的跨平台实现.

### Filesystem

- [rimraf](https://github.com/isaacs/rimraf) / [del](https://github.com/sindresorhus/del)   - 删除文件和文件夹.  跨平台.
- [make-dir](https://github.com/sindresorhus/make-dir) - 跨平台`mkdir -p`.
- [readdirp](https://github.com/paulmillr/readdirp) - `fs.readdir（）`的递归版本.
- [cpy](https://github.com/sindresorhus/cpy)   - 复制文件.  跨平台.
- [chokidar](https://github.com/paulmillr/chokidar) - 改进了跨平台文件监视.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - 改进了`fs`模块，特别是在Windows上.
- [any-path](https://github.com/bcoe/any-path) - 从对象获取值时，可以互换使用Windows和POSIX路径.
- [dev-null-cli](https://github.com/sindresorhus/dev-null-cli) - 跨平台`/ dev / null`.

### Signals

- [fkill](https://github.com/sindresorhus/fkill)   - 杀死进程.  跨平台.
- [signal-exit](https://github.com/tapjs/signal-exit) - 跨平台`退出&#39;处理程序.

### Processes

- [ps-list](https://github.com/sindresorhus/ps-list) - 获取正在运行的进程
- [process-exists](https://github.com/sindresorhus/process-exists) - 检查是否存在进程.

### Streams

- [noop-stream](https://github.com/sindresorhus/noop-stream) - 跨平台`fs.createReadStream（&#39;/ dev / null&#39;）`.

### Desktop UI

- [open](https://github.com/sindresorhus/open)   - 打开网站，文件，可执行文件等内容.  跨平台.
- [node-notifier](https://github.com/mikaelbr/node-notifier) - 跨平台桌面通知.

### Windows registry

- [node-winreg](https://github.com/fresc81/node-winreg) - 访问Windows注册表.
- [rage-edit](https://github.com/MikeKovarik/rage-edit) - 访问/修改Windows注册表.
- [windows-registry-node](https://github.com/CatalystCode/windows-registry-node) - 访问/修改Windows注册表并设置文件关联.

## Known issues

- [cmd.exe unicode woes](https://github.com/nodejs/node-v0.x-archive/issues/7940) - 默认情况下，`cmd.exe`在Windows上不显示Unicode字符.
- [spawn issues](https://github.com/nodejs/node-v0.x-archive/issues/2318) - `child_process.spawn（）`行为在Windows和Linux之间不一致.
- [exec() behavior between shells](https://github.com/isaacs/spawn-wrap#contracts-and-caveats) - 根据所使用的shell，例如bash与dash，`child_process.exec（）`具有不一致的退出行为.

## See also

- [awesome-desktop-js](https://github.com/styfle/awesome-desktop-js) - 在桌面上构建JavaScript应用程序的工具列表.

## Support

如果您发现错误或想要添加更多信息，请_don&#39;t hesitate_ to
[submit an issue on GitHub](https://github.com/bcoe/awesome-cross-platform-nodejs/blob/master/../../issues).

 无论个人背景如何，都欢迎每个人.  我们强制执行
[Code of conduct](https://github.com/bcoe/awesome-cross-platform-nodejs/blob/master/CODE_OF_CONDUCT.md) 为了促进积极和
包容性环境.

## Contributing

 这个项目是用❤️制作的.  最简单的回馈方式是主演和
在线分享.

如果文档不清楚或有拼写错误，请点击页面的“编辑”
按钮（铅笔图标）并建议更正.

如果您想帮助我们修复错误或添加更多信息，请检查
our [guidelines](https://github.com/bcoe/awesome-cross-platform-nodejs/blob/master/contributing.md) .  拉请求是受欢迎的！

谢谢你们这些精彩的人：

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://twitter.com/benjamincoe"><img src="https://avatars3.githubusercontent.com/u/194609?v=4" width="100px;" alt="Benjamin E. Coe"/><br /><sub><b>Benjamin E. Coe</b></sub></a><br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Code">💻</a> <a href="#ideas-bcoe" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Documentation">📖</a></td><td align="center"><a href="https://twitter.com/ehmicky"><img src="https://avatars2.githubusercontent.com/u/8136211?v=4" width="100px;" alt="ehmicky"/><br /><sub><b>ehmicky</b></sub></a><br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Code">💻</a> <a href="#ideas-ehmicky" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Documentation">📖</a></td><td align="center"><a href="https://sindresorhus.com"><img src="https://avatars1.githubusercontent.com/u/170270?v=4" width="100px;" alt="Sindre Sorhus"/><br /><sub><b>Sindre Sorhus</b></sub></a><br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Code">💻</a> <a href="#ideas-sindresorhus" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Documentation">📖</a></td><td align="center"><a href="https://fb.com/RemoveU"><img src="https://avatars1.githubusercontent.com/u/19208123?v=4" width="100px;" alt="Hongarc"/><br /><sub><b>Hongarc</b></sub></a><br /><a href="#design-Hongarc" title="Design">🎨</a> <a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Code">💻</a></td><td align="center"><a href="https://kentcdodds.com"><img src="https://avatars0.githubusercontent.com/u/1500684?v=4" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="#ideas-kentcdodds" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://nz.linkedin.com/in/jsonc11"><img src="https://avatars0.githubusercontent.com/u/5185660?v=4" width="100px;" alt="Jason Cooke"/><br />  <sub>杰森库克</sub> <br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=Jason-Cooke" title="文档"></a></td><td align="center"><img src="https://avatars0.githubusercontent.com/u/3322693?v=4" width="100px;" alt="Aron Hafner"/><br />  <sub>亚伦哈夫纳</sub> <br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=alonalon" title="文档"></a></td></tr><tr><td align="center"><img src="https://avatars0.githubusercontent.com/u/43875468?v=4" width="100px;" alt="ShPelles"/><br />  <sub>洞穴</sub> <br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=ShPelles" title="文档"></a></td><td align="center"><img src="https://avatars1.githubusercontent.com/u/1182395?v=4" width="100px;" alt="Xiaodan Mao"/><br /><sub><b>Xiaodan Mao</b></sub></a><br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=Frederick-S" title="Documentation"></a></td><td align="center"><a href="https://raw.githubusercontent.com/jamestalmage"><img src="https://avatars0.githubusercontent.com/u/4082216?v=4" width="100px;" alt="James Talmage"/><br />  <sub>詹姆斯塔尔马</sub> <br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=jamestalmage" title="文档"></a></td><td align="center"><img src="https://avatars3.githubusercontent.com/u/3357643?v=4" width="100px;" alt="Sylvain PONTOREAU"/><br />  <sub>Sylvain PONTOREAU</sub> <br /><a href="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/commits?author=spontoreau" title="文档"></a></td><td align="center"><img src="https://avatars1.githubusercontent.com/u/229881?v=4" width="100px;" alt="Steven"/><br /><sub><b>Steven</b></sub></a><br /><a href="#ideas-styfle" title="Ideas, Planning, & Feedback">🤔</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

该项目遵循 [all-contributors](https://github.com/all-contributors/all-contributors) 规格.

## License

[![License](https://img.shields.io/github/license/bcoe/awesome-cross-platform-nodejs.svg?color=4cc61e&logo=github)](https://creativecommons.org/licenses/by-sa/4.0/)
