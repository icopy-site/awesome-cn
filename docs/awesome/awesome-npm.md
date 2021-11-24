<div class="github-widget" data-repo="sindresorhus/awesome-npm"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>

&gt; 真棒 [npm](https://www.npmjs.com) 资源和提示

[npm](https://en.wikipedia.org/wiki/Npm_(software)) 是 JavaScript 编程语言的包管理器，捆绑在 [Node.js](https://en.wikipedia.org/wiki/Node.js) 运行.

*请阅读 [contribution guidelines](https://github.com/sindresorhus/awesome-npm/blob/master/contributing.md) 在贡献之前. *



## Articles

- [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
- [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - 编写只做一件事并把它做好的程序.
- [Writing small modules](https://web.archive.org/web/20180302125059/https://substack.net/how_I_write_modules)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/) *（必读！）*
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Offline installation of npm packages](https://addyosmani.com/blog/using-npm-offline/)
- [Task automation with npm run](https://web.archive.org/web/20180302164842/http://substack.net/task_automation_with_npm_run)
- [How to use npm as a build tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- [Install npm packages globally without sudo on macOS and Linux](https://github.com/sindresorhus/guides/blob/main/npm-global-without-sudo.md)
- [Optimizing the footprint of an npm package](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- [The Art of Node](https://github.com/maxogden/art-of-node#modules) - Node.js 和使用 npm 进行客户端开发的介绍.
- [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - 介绍带有常用包和脚本的 npm 脚本，以及样板项目.

## Tools

### Web

- [npms](https://npms.io) - 精湛的包装搜索，使用深度分析包装质量 [myriad of metrics](https://npms.io/about).
	- [npm-introspect](http://npm-introspect.z3d.tech) - 基于 npms 的实用程序，用于直观地探索包依赖项的质量.
- [npmsearch](http://npmsearch.com) - 快速包搜索，根据星级、家属、发布频率等指标进行排名.
- [node-modules](http://node-modules.com) - 基于您的 GitHub 社交图的个性化包搜索.
- [NodeICO](https://nodei.co/) - 包装徽章.
- [Libraries.io](https://libraries.io/npm) - 包发现.
- [npm-stat](http://npm-stat.com) - 包的统计图表.
- [npmgraph](http://npm.anvaka.com) - 依赖关系的可视化.
- [npm trends](http://www.npmtrends.com) - 随着时间的推移比较包下载计数.
- [npm-compare](https://npmcompare.com) - 轻松搜索和比较包.
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - 下载 npm 用户.
- [npm semver calculator](http://semver.npmjs.com) - 直观地探索 semver 范围匹配的软件包版本.
- [ghub.io](https://ghub.io) - 重定向到 npm 包的 GitHub 存储库.
- [npm addict](https://npmaddict.com) - 你每天注入的 npm 包.
- [moiva](https://moiva.io) - 发现和比较包.
- [Openbase](https://openbase.com) - 比较具有强大指标和用户评论的开源包.

### Browser extensions

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome 扩展程序可轻松浏览 GitHub 上的 npm 包.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - 用于探索 GitHub 存储库上的 npm 依赖项的 Chrome 扩展程序.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - 在 GitHub 上查看 npm 下载统计信息.
- [npm-search-update](https://chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - Chrome 扩展程序可快速搜索依赖项并监控 npm 注册表中的更改.

### CLI

- [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好地完成 npm 的 ZSH.
- [npkill](https://github.com/voidcosmos/npkill) - 轻松查找和删除旧的和沉重的 node_modules 文件夹.

## Packages

### Publishing

- [np](https://github.com/sindresorhus/np) - 更好的 `npm publish`.
- [publish-please](https://github.com/inikulin/publish-please) - 安全优雅地发布包.
- [npm-release](https://github.com/phuu/npm-release) - 让发布到 npm 变得如此简单，一只小猫可能可以做到™.
- [pkgfiles](https://github.com/timoxley/pkgfiles) - 列出将在包中发布的所有文件.
- [release-it](https://github.com/webpro/release-it)  - 自动发布 Git 存储库和/或 npm 包. 变更日志生成、GitHub/GitLab 发布等.
- [semantic-release](https://github.com/semantic-release/semantic-release) - 全自动包发布.

### Registry

- [npm-name](https://github.com/sindresorhus/npm-name-cli) - 检查包名是否在 npm 上可用.
- [package-json](https://github.com/sindresorhus/package-json) - 从 npm 注册表中获取包的 package.json.
- [latest-version](https://github.com/sindresorhus/latest-version-cli) - 获取最新版本的 npm 包.
- [npm-keyword](https://github.com/sindresorhus/npm-keyword) - 获取带有特定关键字的 npm 包列表.
- [npm-user](https://github.com/sindresorhus/npm-user) - 获取 npm 用户的用户信息.
- [npm-email](https://github.com/sindresorhus/npm-email) - Get the email of an npm user.
- [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) - 通过 npm 用户获取包.
- [dpn](https://github.com/gillstrom/dpn) - 获取用户 npm 包的依赖项.
- [npm-stats](https://github.com/hughsk/npm-stats) - 从 npm 注册表中获取数据.
- [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) - 登录到 npm.
- [nrm](https://github.com/Pana/nrm) - 注册管理器.
- [npm-register](https://github.com/dickeyxxx/npm-register) - 易于设置和维护 npm 注册表和代理.
- [verdaccio](https://github.com/verdaccio/verdaccio) - 轻量级私有 npm 代理注册表.
- [cloudsmith](https://cloudsmith.io/l/npm-registry/) - 完全托管的包管理 SaaS，支持公共和私有 npm 注册表（以及许多其他注册表）.

### Other

- [npm-home](https://github.com/sindresorhus/npm-home) - 打开包的 npm 页面.
- [gh-home](https://github.com/sindresorhus/gh-home) - 打开包的 GitHub 页面.
- [david](https://github.com/alanshaw/david) - 检查您的软件包依赖项是否已过期.
- [npm-check](https://github.com/dylang/npm-check) - 检查过时、不正确和未使用的依赖项，以及交互式更新.
- [npm-upgrade](https://github.com/th0r/npm-upgrade) - 以交互方式更新过时的 npm 依赖项.
- [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) - 一致的收缩包装工具.
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - 在 Windows 上升级 npm.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - 搭建一个 npm 包.
- [pkg-up](https://github.com/sindresorhus/pkg-up) - 找到最近的 package.json 文件.
- [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - 阅读最近的 package.json 文件.
- [normalize-package-data](https://github.com/npm/normalize-package-data) - 规范包元数据.
- [pkg-conf](https://github.com/sindresorhus/pkg-conf) - 从最近的 package.json 获取命名空间配置.
- [npm-run-path](https://github.com/sindresorhus/npm-run-path) - 按名称在终端中运行本地安装的二进制文件，就像使用全局二进制文件一样.
- [local-npm](https://github.com/nolanlawson/local-npm) - 使用 npm [offline](https://addyosmani.com/blog/using-npm-offline/).
- [npe](https://github.com/zeke/npe) - 用于检查和编辑 package.json 中的属性的 CLI.
- [engine-deps](https://github.com/samccone/engine-deps) - 轻松管理 Node.js 版本特定的依赖项.
- [enpeem-search](https://github.com/amovah/enpeem-search) - 通过抓取 npm 网络搜索来搜索包.
- [npm-issues](https://github.com/seanzarrin/npm-issues) - 一次搜索所有软件包的已知问题.
- [john](https://github.com/davej/john) - 使 npm3 的平面依赖更易于查找和排序.
- [ntl](https://github.com/ruyadorno/ntl) - 用于列出和运行 npm 任务的交互式 CLI 菜单.
- [decheck](https://github.com/egoist/decheck) - 在命令行中探索 npm 包的依赖关系.
- [shrinkpack](https://github.com/JamieMason/shrinkpack) - 锁定您的依赖项并离线安装.
- [redrun](https://github.com/coderaiser/redrun) - 从 package.json 扩展脚本以提高执行速度.
- [package-size](https://github.com/egoist/package-size) - 获取 npm 包的包大小.
- [synp](https://github.com/imsnif/synp) - 将 yarn.lock 转换为 package-lock.json，反之亦然.
- [npm-run-all](https://github.com/mysticatea/npm-run-all) - 并行或串行运行多个 npm 脚本的 CLI 工具.
- [onchange](https://github.com/Qard/onchange) - 观察文件和文件夹，并在发生变化时运行命令.
- [cli-error-notifier](https://github.com/micromata/cli-error-notifier) - 当 npm 脚本失败时发送本机桌面通知.
- [luna](https://github.com/rvpanoz/luna) - 管理 npm 依赖项的应用程序.
- [emma-cli](https://github.com/maticzav/emma-cli) - 交互式 CLI 包搜索实用程序.
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 用于改进安全性和信任策略的 Lint 锁文件，以减轻恶意包注入和不安全的锁文件资源.

## Clients

- [yarn](https://github.com/yarnpkg/yarn) - 快速、可靠和安全的依赖管理.
- [npm](https://github.com/npm/cli) - 官方客户端.
- [pnpm](https://github.com/pnpm/pnpm) - 快速、节省磁盘空间的包管理器.

## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*[Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade)*

### Command aliases

- `npm and` → `npm install`
- `npm i -D` → `npm install --save-dev`
- `asl t` →` asl test`
- `npm it` →` npm install &amp;&amp; npm test`
- `npm r` →` npm uninstall`
- `npm un` →` npm uninstall`
- `npm up` →` npm update`

### Shell aliases

加快您常见的 npm 任务.

在你的 `.zshrc`/`.bashrc` 中：

```sh
别名 ni = &#39;npm 安装&#39;
别名 nid=&#39;npm install --save-dev&#39;
别名 nig = &#39;npm install --global&#39;
别名 nt = &#39;npm 测试&#39;
别名 nit = &#39;npm install &amp;&amp; npm test&#39;
别名 nk=&#39;npm 链接&#39;
别名 nr = &#39;npm 运行&#39;
别名 ns = &#39;npm start&#39;
alias nf=&#39;npm cache clean &amp;&amp; rm -rf node_modules &amp;&amp; npm install&#39;
别名 nlg = &#39;npm 列表 --global --depth = 0&#39;
```

### Don't add to package.json when installing

默认情况下，npm 会将您安装的包添加到 package.json 中的 `dependencies` 字段（从 v5 开始）. 您可以通过指定 `--no-save` 标志来防止这种情况. 您可以使用`--save-dev`/`-D`将包添加到`devDependencies`：

```
$ npm install --save-dev ava
```

### Run scripts

你可以轻松 [run scripts](https://docs.npmjs.com/cli/run-script) 通过将它们添加到 package.json 中的 `&quot;scripts&quot;` 字段来使用 npm 并使用 `npm run 运行它们<script-name> `. 运行 `npm run` 以查看可用的脚本. 本地安装包的二进制文件在 [PATH](https://en.wikipedia.org/wiki/PATH_(variable))，因此您可以按名称运行它们.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;cat&quot;: &quot;猫名&quot;
	},
	“依赖关系”：{
		“猫名”：“^1.0.0”
	}
}
```

```
$ npm 运行猫
Max
```

所有 package.json 属性都是 [exposed](https://docs.npmjs.com/misc/scripts#packagejson-vars) 作为环境变量：

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;name&quot;: &quot;echo $npm_package_name&quot;
	}
}
```

```
$ npm 运行名称
awesome-package
```

#### Passing options to commands

您可以通过添加 `-- --flag` 来将选项传递给您在 npm 脚本中使用的命令，如下例所示.  `-` [marks the end of options parsing](https://unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-dash)，所以 `npm run` 会忽略它并将它传递给命令.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;xo&quot;: &quot;xo&quot;,
		&quot;xo:fix&quot;: &quot;npm run xo -- --fix&quot;,
	}
}
```

*添加`---fix`选项就像执行`xo --fix`*.

#### Silent option

`npm run` 有一个 `--silent` 选项，这在结合 npm 脚本时特别有用.

想象一下，您有一个用于对 JavaScript 文件进行 linting 的设置，如下所示：

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;xo&quot;: &quot;xo&quot;,
		&quot;xo:fix&quot;: &quot;npm run xo --silent -- --fix&quot;,
	}
}
```

 *使用`--silent` 选项会减少终端中的输出. 看 [this comparison](https://twitter.com/mkuehnel/status/957965749473210369).*

### Lifecycle scripts

npm 带有预定义 [lifecyle scripts](https://docs.npmjs.com/misc/scripts) 如果它们在 package.json 中定义，则在特定条件下执行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;prepublishOnly&quot;: &quot;nsp 检查&quot;
	},
	“开发依赖”：{
		&quot;nsp&quot;: &quot;^3.0.0&quot;
	}
}
```

这将在您的 npm 包通过 `npm publish` 发布到注册表之前自动执行，以检查您的依赖项中的已知漏洞.

 *注意：**prepublishOnly** 从 npm v4.0.0 开始可用. 看 [npm docs](https://docs.npmjs.com/misc/scripts#deprecation-note).*

#### `npm start` and `npm test`

`npm start` 和 `npm test` 也是生命周期脚本，但不会自动执行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;start&quot;: &quot;节点 server.js&quot;,
		“测试”：“阿瓦”
	},
	“开发依赖”：{
		&quot;ava&quot;: &quot;^ 1.0.0&quot;
	}
}
```

因此，它们可以简单地执行：

```console
$ npm 测试
$ npm 开始
```

#### `pre` and `post` scripts

这些是特殊的生命周期脚本，可用于按顺序自动运行脚本.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		&quot;pretest&quot;: &quot;eslint .&quot;,
		“测试”：“阿瓦”
	},
	“开发依赖”：{
		&quot;sling&quot;: &quot;^ 4.19.0&quot;,
		&quot;ava&quot;: &quot;^ 1.0.0&quot;
	}
}
```

```console
$ npm 测试
```

这将在运行测试之前整理您的文件. 如果 linting 失败，测试将不会运行. 或者更一般地说：如果按顺序运行的脚本之一退出时的退出代码不是 0，则不会执行以下脚本.

 *注意：`pre` 和 `post` 脚本也可用于您的自定义 npm 脚本. 所以 `npm run foo` 也将运行 `prefoo` 和 `postfoo` 如果定义.*

### Run script with `npx`

`npm` [comes bundled](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) 使用 `npx`（自 v5.2.0 起）——一种执行包二进制文件的工具. 每个命令都从本地 `node_modules/.bin` 目录或中央缓存执行，安装任何需要的包，以便 `<command>  ` 运行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“依赖关系”：{
		“猫名”：“^1.0.0”
	}
}
```

如果二进制文件已经安装，它将从`node_modules/.bin` 执行.

```
$ npx 猫名
Max
```

但是如果缺少二进制文件，它将首先安装.

```
$ npx 狗名
npx：在 3.136 秒内安装了 46 个
Bentley
```

### Run commands with different Node.js versions

使用 `npx`（与 npm v5.2.0 或更新版本捆绑）和 [`node-bin`](https://www.npmjs.com/package/node-bin) 包，您可以轻松地在不同的 Node.js 版本中尝试代码，而无需使用像这样的版本管理器 [`nvm`](http://nvm.sh), [`nave`](https://github.com/isaacs/nave)， 或者 [`n`](https://github.com/tj/n).

```
$ npx --package=node-bin@6.11.0 - node --version
v6.11.0
```

### Link local packages

有时，将包的本地版本作为依赖项会很有用. 您可以使用 `npm link` 将一个本地包链接到另一个包. 在要使用的包中运行 `npm link`. 这将创建一个全局引用. 然后进入你的原始包并运行 `npm link<package-name>  ` 链接到另一个包中.

```
$ cd 彩虹
$ npm 链接
$ cd ../独角兽
$ npm 链接彩虹
```

您现在可以使用“rainbow”作为“unicorn”包中的依赖项.

### Install a package from GitHub

npm 支持使用简写直接从 GitHub 存储库安装包：

```
$ npm install sindresorhus / chalk
```

让我们针对特定的提交，因为主分支是一个移动目标：

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

指定提交 SHA、分支、标签或什么都不指定.

您还可以使用 semver 安装 Git 依赖项：*（需要 npm v5 或更新版本）*

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### Install a specific version of a package

```
$ npm 安装粉笔@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth = 0
```

### Command help

获取命令的帮助文档：

```
$ npm 帮助<command>
```

Example:

```
$ npm 帮助安装
```

### Standalone version of a package

快速获取已浏览器化并可在浏览器中使用的独立版本的软件包.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

- <https://wzrd.in/standalone/object-assign>
- <https://wzrd.in/standalone/object-assign@4.0.0>

非常适合原型制作，但下载文件或自己使用 Browserify 进行生产.

## FAQ

- [Check in node_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)

## Community

- [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/npm)
- [Reddit](https://www.reddit.com/r/npm)
- [Twitter](https://twitter.com/npmjs)
- [Blog](https://blog.npmjs.org)

## Documentation

- [Official](https://docs.npmjs.com)
- [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting)
- [Semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning)
- [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
- [package.json](https://docs.npmjs.com/files/package.json)
- [npm run script](https://docs.npmjs.com/cli/run-script)
- [Stats API](https://github.com/npm/download-counts)

## Support

- [npm.community](https://npm.community/c/support)
- [Twitter](https://twitter.com/npm_support)
- [Contact form](https://www.npmjs.com/support)

## Related

- [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
