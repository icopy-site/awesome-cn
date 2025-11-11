<div class="github-widget" data-repo="sindresorhus/awesome-tap"></div>
## Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)

> Useful resources for the [Test Anything Protocol](https://testanything.org)

TAP is a simple text-based interface between testing modules in a test harness.

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*



## Reporters

### JavaScript

- [tap-dot](https://github.com/scottcorgan/tap-dot) - Dotted output.
- [tap-spec](https://github.com/scottcorgan/tap-spec) - Mocha-like spec reporter.
- [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) - Nyan cat.
- [tap-min](https://github.com/derhuerst/tap-min) - Minimal output.
- [tap-difflet](https://github.com/namuol/tap-difflet) - Minimal output with diffing.
- [tap-diff](https://github.com/axross/tap-diff) - Human-friendly output with diffing.
- [tap-simple](https://github.com/joeybaker/tap-simple) - Simple output.
- [faucet](https://github.com/substack/faucet) - Human-readable summarizer.
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - Use any of the [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters).
- [tap-summary](https://github.com/zoubin/tap-summary) - Summarized output.
- [tap-pessimist](https://github.com/clux/tap-pessimist) - Only shows failed tests.
- [tap-prettify](https://github.com/toolness/tap-prettify) - Nice readable output with diffing.
- [tap-colorize](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability.
- [tap-bail](https://github.com/juliangruber/tap-bail) - Bail out when the first test fails.
- [tap-notify](https://github.com/axross/tap-notify) - Notifier for macOS, Linux and Windows.
- [tap-json](https://github.com/gummesson/tap-json) - JSON output.
- [ava-tap-json](https://github.com/yovasx2/ava-tap-json) - JSON output with AVA compatibility.
- [tap-xunit](https://github.com/aghassemi/tap-xunit) - xUnit output.
- [tap-teamcity](https://github.com/smockle/tap-teamcity) - Output for TeamCity.

### Go

- [tapfmt](https://github.com/coreybutler/tapfmt) - Standalone cross-platform formatter.

## Producers

Things that produce TAP output.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - Futuristic test runner (`$ ava --tap`).
- [tap](https://github.com/isaacs/node-tap) - TAP test framework for Node.js.
- [tape](https://github.com/substack/tape) - TAP-producing test harness for Node.js and browsers.
- [ESLint](https://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter (`$ eslint --format=tap`).
- [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers (`$ mocha reporter=tap`).
- [qunit-tap](https://github.com/twada/qunit-tap) - TAP output for QUnit.
- [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) - TAP output for Jasmine.
- [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) - TAP output for Karma.
- [mos](https://github.com/zkochan/mos) - Markdown file generator and tester (`$ mos test --tap`).
- [zora](https://github.com/lorenzofox3/zora) - TAP-producing test runner that works with ES2015 without Babel.
- [node:test](https://nodejs.org/api/test.html) - Minimal TAP test runner included with Node.js.

### Swift

- [TAP](https://github.com/swiftdocorg/tap) - A Swift package for the Test Anything Protocol (v13).

### Fish

- [Fishtape](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish.

### Bash

- [bats](https://github.com/sstephenson/bats) - Bash Automated Testing System.
- [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for POSIX shells.

[More…](https://testanything.org/producers.html)

## Consumers

Things that consume TAP output.

### JavaScript

- [tap-parser](https://github.com/substack/tap-parser) - TAP parser.
- [tap-out](https://github.com/scottcorgan/tap-out) - TAP parser.
- [yamlish](https://github.com/isaacs/yamlish) - YAML-block parser.

[More…](https://testanything.org/consumers.html)

## Tools

### JavaScript

- [tap-dev-tool](https://github.com/Jam3/tap-dev-tool) - Prettify TAP in the browser console.
- [tap-merge](https://github.com/anko/tap-merge) - Merge multiple TAP streams.
- [smokestack](https://github.com/hughsk/smokestack) - Run TAP tests in a browser and write the output to `stdout`.
- [chutney](https://github.com/derhuerst/chutney) - Run TAP tests at Sauce Labs. Lightweight [smokestack](https://github.com/hughsk/smokestack) alternative.

### Python

- [tappy](https://github.com/mblayman/tappy) - Tools for working with TAP.

## Articles

- [Understand the Test Anything Protocol](https://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)

## Tutorials

- [test-anything](https://github.com/finnp/test-anything) - Learn to test anything with TAP through an interactive workshop.

## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)

## Community

- [Discuss](https://github.com/TestAnything/Specification/issues)
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/tap)
