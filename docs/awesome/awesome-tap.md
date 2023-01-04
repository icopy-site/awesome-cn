<div class="github-widget" data-repo="sindresorhus/awesome-tap"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)

&gt; 有用的资源 [Test Anything Protocol](https://testanything.org)

TAP 是测试工具中测试模块之间基于文本的简单界面.

 *该列表现在非常专注于 JavaScript. 那只是因为我只熟悉 JS 世界中的 TAP 东西. 欢迎任何语言的贡献.*



## Reporters

### JavaScript

- [tap-dot](https://github.com/scottcorgan/tap-dot) - 点输出.
- [tap-spec](https://github.com/scottcorgan/tap-spec) - 类似摩卡的规范记者.
- [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) - 那只猫.
- [tap-min](https://github.com/derhuerst/tap-min) - 最小输出.
- [tap-difflet](https://github.com/namuol/tap-difflet) - 带差异的最小输出.
- [tap-diff](https://github.com/axross/tap-diff) - 带有差异的人性化输出.
- [tap-simple](https://github.com/joeybaker/tap-simple) - 简单的输出.
- [faucet](https://github.com/substack/faucet) - 人类可读的总结器.
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - 使用任何 [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters).
- [tap-summary](https://github.com/zoubin/tap-summary) - 汇总输出.
- [tap-pessimist](https://github.com/clux/tap-pessimist) - 只显示失败的测试.
- [tap-prettify](https://github.com/toolness/tap-prettify) - 带有差异的漂亮可读输出.
- [tap-colorize](https://github.com/substack/tap-colorize) - 在保持机器可读性的同时对输出进行着色.
- [tap-bail](https://github.com/juliangruber/tap-bail) - 当第一次测试失败时退出.
- [tap-notify](https://github.com/axross/tap-notify) - 适用于 macOS、Linux 和 Windows 的通知程序.
- [tap-json](https://github.com/gummesson/tap-json) - JSON 输出.
- [ava-tap-json](https://github.com/yovasx2/ava-tap-json) - 具有 AVA 兼容性的 JSON 输出.
- [tap-xunit](https://github.com/aghassemi/tap-xunit) - xUnit 输出.
- [tap-teamcity](https://github.com/smockle/tap-teamcity) - TeamCity 的输出.

## Producers

产生 TAP 输出的事物.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - 未来的测试运行器（`$ ava --tap`）.
- [tap](https://github.com/isaacs/node-tap) - 用于 Node.js 的 TAP 测试框架.
- [tape](https://github.com/substack/tape) - 用于 Node.js 和浏览器的 TAP 生成测试工具.
- [ESLint](https://eslint.org/docs/user-guide/formatters/#tap) - 可插入的 JavaScript linter (`$ eslint --format=tap`).
- [Mocha](https://mochajs.org) - 用于 Node.js 和浏览器的功能丰富的测试框架 (`$ mocha reporter=tap`).
- [qunit-tap](https://github.com/twada/qunit-tap) - QUnit 的 TAP 输出.
- [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) - Jasmine 的 TAP 输出.
- [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) - Karma 的 TAP 输出.
- [mos](https://github.com/zkochan/mos) - Markdown 文件生成器和测试器（`$ mos test --tap`）.
- [zora](https://github.com/lorenzofox3/zora) - 生成 TAP 的测试运行器，可在没有 Babel 的情况下使用 ES2015.
- [node:test](https://nodejs.org/api/test.html) - Node.js 中包含的最小 TAP 测试运行器.

### Swift

- [TAP](https://github.com/swiftdocorg/tap) - 用于测试任何协议 (v13) 的 Swift 包.

### Fish

- [Fishtape](https://github.com/fisherman/fishtape) - TAP 生产者和鱼类测试工具.

### Bash

- [bats](https://github.com/sstephenson/bats) - Bash 自动化测试系统.
- [ShellSpec](https://github.com/shellspec/shellspec) - 用于 POSIX shell 的全功能 BDD 单元测试框架.

[More…](https://testanything.org/producers.html)

## Consumers

消耗 TAP 输出的事物.

### JavaScript

- [tap-parser](https://github.com/substack/tap-parser) - TAP 解析器.
- [tap-out](https://github.com/scottcorgan/tap-out) - TAP 解析器.
- [yamlish](https://github.com/isaacs/yamlish) - YAML 块解析器.

[More…](https://testanything.org/consumers.html)

## Tools

### JavaScript

- [tap-dev-tool](https://github.com/Jam3/tap-dev-tool) - 在浏览器控制台中美化 TAP.
- [tap-merge](https://github.com/anko/tap-merge) - 合并多个 TAP 流.
- [smokestack](https://github.com/hughsk/smokestack) - 在浏览器中运行 TAP 测试并将输出写入“stdout”.
- [chutney](https://github.com/derhuerst/chutney)  - 在 Sauce Labs 运行 TAP 测试. 轻 [smokestack](https://github.com/hughsk/smokestack) 选择.

### Python

- [tappy](https://github.com/mblayman/tappy) - 使用 TAP 的工具.

## Articles

- [Understand the Test Anything Protocol](https://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)

## Tutorials

- [test-anything](https://github.com/finnp/test-anything) - 通过互动研讨会学习使用 TAP 测试任何东西.

## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)

## Community

- [Discuss](https://github.com/TestAnything/Specification/issues)
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/tap)
