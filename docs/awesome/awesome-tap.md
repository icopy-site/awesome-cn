## Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)


&gt;有用的资源 [Test Anything Protocol](https://testanything.org)<br>
&gt;测试工具中测试模块之间的简单基于文本的界面

 *该列表目前非常注重JavaScript.  那只是因为我只熟悉JS世界中的TAP内容.  欢迎任何语言的贡献.*


## Contents

- [Reporters](#reporters)
- [Producers](#producers)
- [Consumers](#consumers)
- [Tools](#tools)
- [Articles](#articles)
- [Tutorials](#tutorials)
- [Documentation](#documentation)
- [Community](#community)


## Reporters

### JavaScript

- [tap-dot](https://github.com/scottcorgan/tap-dot) - 虚线输出.
- [tap-spec](https://github.com/scottcorgan/tap-spec) - 摩卡式规格记者.
- [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) - 喵喵猫.
- [tap-min](https://github.com/gummesson/tap-min) - 最小输出.
- [tap-difflet](https://github.com/namuol/tap-difflet) - 具有差异的最小输出.
- [tap-diff](https://github.com/axross/tap-diff) - 人性化的输出与差异.
- [tap-simple](https://github.com/joeybaker/tap-simple) - 简单的输出.
- [faucet](https://github.com/substack/faucet) - 人类可读的摘要生成器.
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - 使用任何一个 [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters).
- [tap-summary](https://github.com/zoubin/tap-summary) - 汇总输出.
- [tap-pessimist](https://github.com/clux/tap-pessimist) - 仅显示测试失败.
- [tap-prettify](https://github.com/toolness/tap-prettify) - 良好的可读输出与差异.
- [tap-colorize](https://github.com/substack/tap-colorize) - 在保持机器可读性的同时着色输出.
- [tap-bail](https://github.com/juliangruber/tap-bail) - 第一次测试失败时纾困.
- [tap-notify](https://github.com/axross/tap-notify) -  macOS，Linux和Windows的通知程序.
- [tap-json](https://github.com/gummesson/tap-json) -  JSON输出.
- [tap-xunit](https://github.com/aghassemi/tap-xunit) -  xUnit输出.
- [tap-teamcity](https://github.com/smockle/tap-teamcity) -  TeamCity的输出.


## Producers

产生TAP输出的东西.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - 未来的测试运行器（`$ ava --tap`）.
- [tap](https://github.com/isaacs/node-tap) -  Node.js的TAP测试框架.
- [tape](https://github.com/substack/tape) - 针对Node.js和浏览器生成TAP的测试工具.
- [ESLint](http://eslint.org/docs/user-guide/formatters/#tap) - 可插入的JavaScript linter（`$ eslint --format = tap`）.
- [Mocha](https://mochajs.org) -  Node.js和浏览器的功能丰富的测试框架（`$ mocha reporter = tap`）.
- [qunit-tap](https://github.com/twada/qunit-tap) -  QUnit的TAP输出.
- [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) -  Jasmine的TAP输出.
- [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) -  Karma的TAP输出.
- [mos](https://github.com/zkochan/mos) -  Markdown文件生成器和测试器（`$ mos test --tap`）.

### Fish

- [Fishtape](https://github.com/fisherman/fishtape) - 鱼类的TAP生产者和测试工具.

### Bash

- [bats](https://github.com/sstephenson/bats) -  Bash自动化测试系统.

[More...](https://testanything.org/producers.html)


## Consumers

消耗TAP输出的东西.

### JavaScript

- [tap-parser](https://github.com/substack/tap-parser) -  TAP解析器.
- [tap-out](https://github.com/scottcorgan/tap-out) -  TAP解析器.
- [yamlish](https://github.com/isaacs/yamlish) -  YAML块解析器.

[More...](https://testanything.org/consumers.html)


## Tools

### JavaScript

- [tap-dev-tool](https://github.com/Jam3/tap-dev-tool) - 在浏览器控制台中整理TAP.
- [tap-merge](https://github.com/anko/tap-merge) - 合并多个TAP流.
- [smokestack](https://github.com/hughsk/smokestack) - 在浏览器中运行TAP测试并将输出写入`stdout`.
- [chutney](https://github.com/derhuerst/chutney)   - 在Sauce Labs运行TAP测试.  轻量级 [smokestack](https://github.com/hughsk/smokestack) 替代.

### Python

- [tappy](https://github.com/mblayman/tappy) - 使用TAP的工具.


## Articles

- [Understand the Test Anything Protocol](http://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)


## Tutorials

- [test-anything](https://github.com/finnp/test-anything) - 通过互动研讨会学习使用TAP进行任何测试.


## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)


## Community

- [Discuss](https://github.com/TestAnything/Specification/issues)
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/tap)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Sindre Sorhus](http://sindresorhus.com) 已放弃对此作品的所有版权及相关或相邻权利.
