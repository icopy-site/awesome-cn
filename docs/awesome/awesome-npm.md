<div class="github-widget" data-repo="sindresorhus/awesome-npm"></div>

&gt; 太棒了 [npm](https://www.npmjs.com) 资源和提示

[npm](https://en.wikipedia.org/wiki/Npm_(software)) 是 JavaScript 编程语言的包管理器，捆绑在 [Node.js](https://en.wikipedia.org/wiki/Node.js) 运行.

*请阅读 [contribution guidelines](https://github.com/sindresorhus/awesome-npm/blob/master/contributing.md) 在贡献之前.*



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
- [The Art of Node](https://github.com/maxogden/art-of-node#modules) - 介绍 Node.js 和使用 npm 进行客户端开发.
- [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - 介绍带有通用包和脚本的 npm 脚本，以及样板项目.

## Tools

### Web

- [npms](https://npms.io) - 精湛的包裹搜索，使用深度分析包裹质量 [myriad of metrics](https://npms.io/about).
- [NodeICO](https://nodei.co/) - 包裹徽章.
- [Libraries.io](https://libraries.io/npm) - 包发现.
- [npm-stat](http://npm-stat.com) - 包的统计图表.
- [npmgraph](http://npm.anvaka.com) - 依赖关系的可视化.
- [npm trends](http://www.npmtrends.com) - 比较一段时间内的包下载次数.
- [npm-compare](https://npmcompare.com) - 轻松搜索和比较包.
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - 通过下载 npm 用户.
- [npm semver calculator](http://semver.npmjs.com) - 直观地探索一个 semver 范围匹配的包版本.
- [ghub.io](https://ghub.io) - 重定向到 npm 包的 GitHub 存储库.
- [moiva](https://moiva.io) - 发现和比较包.

### Browser extensions

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome 扩展，可轻松浏览 GitHub 上的 npm 包.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome 扩展，用于探索 GitHub 存储库上的 npm 依赖项.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - 在 GitHub 上查看 npm 下载统计信息.
- [npm-search-update](https://chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - Chrome 扩展，可快速搜索依赖项并监控 npm 注册表中的更改.

### CLI

- [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好地为 npm 完成 ZSH.
- [npkill](https://github.com/voidcosmos/npkill) - 轻松找到并删除旧的和繁重的 node_modules 文件夹.

## Packages

### Publishing

- [np](https://github.com/sindresorhus/np) - 更好的 `npm publish`.
- [publish-please](https://github.com/inikulin/publish-please) - 安全优雅地发布包.
- [npm-release](https://github.com/phuu/npm-release) - 使发布到 npm 变得如此简单，小猫可能会做到™.
- [pkgfiles](https://github.com/timoxley/pkgfiles) - 列出将在包中发布的所有文件.
- [release-it](https://github.com/webpro/release-it)  - 自动发布 Git 存储库和/或 npm 包. 变更日志生成、GitHub/GitLab 发布等.
- [semantic-release](https://github.com/semantic-release/semantic-release) - 全自动包发布.

### Registry

- [npm-name](https://github.com/sindresorhus/npm-name-cli) - 检查包名称是否在 npm 上可用.
- [package-json](https://github.com/sindresorhus/package-json) - 从 npm 注册表获取包的 package.json.
- [latest-version](https://github.com/sindresorhus/latest-version-cli) - 获取最新版本的 npm 包.
- [npm-keyword](https://github.com/sindresorhus/npm-keyword) - 获取带有特定关键字的 npm 包列表.
- [npm-user](https://github.com/sindresorhus/npm-user) - 获取 npm 用户的用户信息.
- [npm-email](https://github.com/sindresorhus/npm-email) - 获取 npm 用户的电子邮件.
- [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) - 由 npm 用户获取包.
- [dpn](https://github.com/gillstrom/dpn) - 获取用户 npm 包的依赖项.
- [npm-stats](https://github.com/hughsk/npm-stats) - 从 npm 注册表获取数据.
- [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) - 登录 npm.
- [nrm](https://github.com/Pana/nrm) - 注册管理器.
- [npm-register](https://github.com/dickeyxxx/npm-register) - 易于设置和维护 npm 注册表和代理.
- [verdaccio](https://github.com/verdaccio/verdaccio) - 轻量级私有 npm 代理注册表.
- [cloudsmith](https://cloudsmith.io/l/npm-registry/) - 一个完全托管的包管理 SaaS，支持公共和私人 npm 注册表（以及许多其他注册表）.

### Other

- [npm-home](https://github.com/sindresorhus/npm-home) - 打开包的 npm 页面.
- [gh-home](https://github.com/sindresorhus/gh-home) - 打开包的 GitHub 页面.
- [david](https://github.com/alanshaw/david) - 检查您的软件包依赖项是否已过期.
- [npm-check](https://github.com/dylang/npm-check) - 检查过时的、不正确的和未使用的依赖项，以及交互式更新.
- [npm-upgrade](https://github.com/th0r/npm-upgrade) - 以交互方式更新过时的 npm 依赖项.
- [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) - 一致的收缩包装工具.
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - 在 Windows 上升级 npm.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - 搭建一个 npm 包.
- [pkg-up](https://github.com/sindresorhus/pkg-up) - 找到最近的 package.json 文件.
- [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - 阅读最近的 package.json 文件.
- [normalize-package-data](https://github.com/npm/normalize-package-data) - 标准化包元数据.
- [pkg-conf](https://github.com/sindresorhus/pkg-conf) - 从最近的 package.json 获取命名空间配置.
- [npm-run-path](https://github.com/sindresorhus/npm-run-path) - 按名称在终端中运行本地安装的二进制文件，就像全局二进制文件一样.
- [local-npm](https://github.com/nolanlawson/local-npm) - 使用 npm [offline](https://addyosmani.com/blog/using-npm-offline/).
- [npe](https://github.com/zeke/npe) - 用于检查和编辑 package.json 中的属性的 CLI.
- [engine-deps](https://github.com/samccone/engine-deps) - 轻松管理 Node.js 版本特定的依赖项.
- [enpeem-search](https://github.com/amovah/enpeem-search) - 通过抓取 npm 网络搜索来搜索包.
- [npm-issues](https://github.com/seanzarrin/npm-issues) - 一次搜索所有包的已知问题.
- [john](https://github.com/davej/john) - 使 npm3 的平面依赖项更易于查找和排序.
- [ntl](https://github.com/ruyadorno/ntl) - 用于列出和运行 npm 任务的交互式 CLI 菜单.
- [decheck](https://github.com/egoist/decheck) - 在命令行中探索 npm 包的依赖关系.
- [shrinkpack](https://github.com/JamieMason/shrinkpack) - 锁定您的依赖项并离线安装.
- [redrun](https://github.com/coderaiser/redrun) - 扩展 package.json 中的脚本以提高执行速度.
- [package-size](https://github.com/egoist/package-size) - 获取 npm 包的包大小.
- [synp](https://github.com/imsnif/synp) - 将 yarn.lock 转换为 package-lock.json，反之亦然.
- [npm-run-all](https://github.com/mysticatea/npm-run-all) - 用于并行或串行运行多个 npm 脚本的 CLI 工具.
- [onchange](https://github.com/Qard/onchange) - 监视文件和文件夹并在发生变化时运行命令.
- [cli-error-notifier](https://github.com/micromata/cli-error-notifier) - 当 npm 脚本失败时发送本机桌面通知.
- [luna](https://github.com/rvpanoz/luna) - 用于管理 npm 依赖项的应用程序.
- [emma-cli](https://github.com/maticzav/emma-cli) - 交互式 CLI 包搜索实用程序.
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 用于改进安全性和信任策略的 Lint 锁文件，以减轻恶意包注入和不安全的锁文件资源.

## Clients

- [yarn](https://github.com/yarnpkg/yarn) - 快速、可靠和安全的依赖管理.
- [npm](https://github.com/npm/cli) - 官方客户端.
- [pnpm](https://github.com/pnpm/pnpm) - 快速、节省磁盘空间的包管理器.

## Tips

### Update to the latest npm version

```
$ npm 安装 --global npm
```

*[Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade)*

### Command aliases

-`npm i`→`npm install`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install &amp;&amp; npm test`
- `npm r` → `npm uninstall`
- `npm un` → `npm uninstall`
- `npm up` → `npm update`

### Shell aliases

加速您的常见 npm 任务.

在你的 `.zshrc`/`.bashrc` 中：

```sh
别名 ni=&#39;npm 安装&#39;
别名 nid=&#39;npm install --save-dev&#39;
别名 nig=&#39;npm install --global&#39;
别名 nt=&#39;npm 测试&#39;
别名 nit=&#39;npm install &amp;&amp; npm test&#39;
别名 nk=&#39;npm 链接&#39;
别名 nr=&#39;npm run&#39;
别名 ns=&#39;npm 开始&#39;
别名 nf=&#39;npm 缓存清理 &amp;&amp; rm -rf node_modules &amp;&amp; npm install&#39;
别名 nlg=&#39;npm list --global --depth=0&#39;
```

### Don't add to package.json when installing

默认情况下，npm 将您安装的包添加到 package.json 中的“dependencies”字段（自 v5 起）. 您可以通过指定 `--no-save` 标志来防止这种情况. 您可以使用 `--save-dev`/`-D` 将包添加到 `devDependencies`：

```
$ npm install --save-dev ava
```

### Run scripts

您可以轻松地 [run scripts](https://docs.npmjs.com/cli/run-script) 通过将它们添加到 package.json 中的“脚本”字段并使用 npm run 运行它们来使用 npm<script-name>  `. 运行“npm run”以查看可用的脚本. 本地安装包的二进制文件在 [PATH](https://en.wikipedia.org/wiki/PATH_(variable))，因此您可以按名称运行它们.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		“猫”：“猫的名字”
	},
	“依赖”：{
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
		“名称”：“回声 $npm_package_name”
	}
}
```

```
$ npm 运行名称
awesome-package
```

#### Passing options to commands

您可以通过添加 `-- --flag` 将选项传递给您在 npm 脚本中使用的命令，如下例所示.  `--` [marks the end of options parsing](https://unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-dash)，因此 `npm run` 将忽略它并将其传递给命令.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		“xo”：“xo”，
		&quot;xo:fix&quot;: &quot;npm run xo -- --fix&quot;,
	}
}
```

*添加 `-- --fix ` 选项就像执行 `xo --fix`*.

#### Silent option

`npm run` 有一个 `--silent` 选项，在组合 npm 脚本时特别有用.

想象一下，您有一个像下面这样对 JavaScript 文件进行 linting 的设置：

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		“xo”：“xo”，
		&quot;xo:fix&quot;: &quot;npm run xo --silent -- --fix&quot;,
	}
}
```

 *使用 `--silent` 选项减少终端中的输出. 看 [this comparison](https://twitter.com/mkuehnel/status/957965749473210369).*

### Lifecycle scripts

npm 自带预定义 [lifecyle scripts](https://docs.npmjs.com/misc/scripts) 如果它们在您的 package.json 中定义，它们将在特定条件下执行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		“prepublishOnly”：“nsp 检查”
	},
	“devDependencies”：{
		“nsp”：“^3.0.0”
	}
}
```

这将在您的 npm 包通过“npm publish”发布到注册表之前自动执行，以检查您的依赖项中的已知漏洞.

 *注意：**prepublishOnly** 从 npm v4.0.0 开始可用. 看 [npm docs](https://docs.npmjs.com/misc/scripts#deprecation-note).*

#### `npm start` and `npm test`

`npm start` 和 `npm test` 也是生命周期脚本，但不会自动执行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“脚本”：{
		“开始”：“节点服务器.js”，
		“测试”：“艾娃”
	},
	“devDependencies”：{
		“ava”：“^1.0.0”
	}
}
```

因此它们可以简单地执行：

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
		“预测试”：“eslint.”，
		“测试”：“艾娃”
	},
	“devDependencies”：{
		&quot;eslint&quot;: &quot;^4.19.0&quot;,
		“ava”：“^1.0.0”
	}
}
```

```console
$ npm 测试
```

这将在运行测试之前检查您的文件. 如果 linting 失败，测试将不会运行. 或者更通俗地说：如果按顺序运行的脚本之一以非 0 的退出代码退出，则不会执行以下脚本.

 *注意：`pre` 和 `post` 脚本也可以用于您的自定义 npm 脚本. 所以如果定义了 `npm run foo` 也会运行 `prefoo` 和 `postfoo`.*

### Run script with `npx`

`npm` [comes bundled](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b)  with `npx` (Since v5.2.0) — 一个执行包二进制文件的工具. 每个命令都从本地 `node_modules/.bin` 目录或中央缓存执行，安装所需的任何包以`<command>  ` 运行.

```json
{
	&quot;name&quot;: &quot;awesome-package&quot;,
	“依赖”：{
		“猫名”：“^1.0.0”
	}
}
```

如果二进制文件已经安装，它将从 `node_modules/.bin` 执行.

```
$ npx 猫名
Max
```

但是如果二进制文件丢失，它将首先安装.

```
$ npx 狗名
npx：在 3.136 秒内安装了 46 个
Bentley
```

### Run commands with different Node.js versions

使用 `npx`（与 npm v5.2.0 或更新版本捆绑在一起）和 [`node-bin`](https://www.npmjs.com/package/node-bin) 包，您可以轻松地在不同的 Node.js 版本中尝试代码，而无需使用像这样的版本管理器 [`nvm`](http://nvm.sh), [`nave`](https://github.com/isaacs/nave)， 或者 [`n`](https://github.com/tj/n).

```
$ npx --package=node-bin@6.11.0 -- 节点 --version
v6.11.0
```

### Link local packages

有时将包的本地版本作为依赖项可能很有用. 您可以使用“npm link”将一个本地包链接到另一个本地包. 在您要使用的包中运行“npm link”. 这将创建一个全局引用. 然后进入你的原始包并运行`npm link<package-name>  ` 链接到另一个包中.

```
$ CD 彩虹
$ npm 链接
$ cd ../unicorn
$ npm 链接彩虹
```

您现在可以将 rainbow 用作 unicorn 包中的依赖项.

### Install a package from GitHub

npm 支持使用简写直接从 GitHub 存储库安装包：

```
$ npm 安装 sindresorhus/粉笔
```

让我们定位一个特定的提交，因为主分支是一个移动的目标：

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

指定提交 SHA、分支、标记或什么都不指定.

您还可以使用 semver 安装 Git 依赖项：*（需要 npm v5 或更新版本）*

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### Install a specific version of a package

```
$ npm 安装 chalk@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth=0
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

快速获取独立版本的包，该版本已浏览器化并可在浏览器中使用.

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
