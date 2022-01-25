<div class="github-widget" data-repo="mojoaxel/awesome-regression-testing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome visual regression testing resources.

回归测试是一种软件测试，它验证先前开发和测试的软件在更改或与其他软件接口后仍然以相同的方式执行. 回归测试的目的是确保对软件的更改没有引入新的故障.

## Foreword

This is intended to be an *incomplete* list of resources about visual regression testing. It is not tailored to a specific area or role (Developer/QA/UX-Designer). Note that this is for all areas of regression software testing *after* the code in question is written. For a awesome list on general software testing see e.g. [awesome-testing](https://github.com/TheJambo/awesome-testing).

最后，我相信每个阅读此列表的人都有他们想要添加的一件事. 请阅读 [How to Contribute](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 页面和**随意添加到列表中！！**. 如果您认为这有帮助 **请给 Star ★**.



## General information

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) - 浏览器自动化框架和生态系统.
- [SlimerJS](https://github.com/laurentj/slimerjs) - 基于 Firefox 的可编写脚本的浏览器，例如 PhantomJS.
- [trifleJS](https://github.com/sdesalas/trifleJS) - Headless automation for Internet Explorer.
- [CasperJS](https://github.com/casperjs/casperjs) - PhantomJS 和 SlimerJS 的导航脚本和测试实用程序.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) - Node.js bindings implementation for the W3C WebDriver protocol.
- [Navalia](https://github.com/joelgriffith/navalia) - 基于无头 Chrome 和 GraphQL 的浏览器自动化.
- [Chromeless](https://github.com/graphcool/chromeless)  - Chrome 自动化变得简单. 在 AWS Lambda 上本地或无头运行.
- [Cypress.io](https://www.cypress.io/) - An automation framework that runs in-browser.

## Tools and frameworks

- [OSnap](https://github.com/eWert-Online/osnap) - The speedy and easy to use Snapshot Testing tool for your project (1200 snapshots will run in under 3 minutes).
- [basset](https://basset.io) - Open source platform for generating and reviewing visual differences. Supports multiple browsers, integrations for github and slack.
- [AyeSpy](https://github.com/newsuk/ayespy) - 在 90 秒内进行 44 次图像比较.
- [Wraith](https://github.com/BBC-News/wraith) - 易于使用的带有 docker 支持的 ruby​​ 工具.
- [BackstopJS](https://github.com/garris/BackstopJS) - 配置驱动的自动化截图测试框架.
- [Galen](https://github.com/galenframework/galen) - Java framework based on [Selenium](https://github.com/SeleniumHQ/selenium).
- [Creevey](https://github.com/wKich/creevey) - Cross-browser visual testing with magic. Feature-rich tool with UI Runner, Tests Hot Reloading, Docker and Storybook integration.
- [CSSCritic](https://github.com/cburgmer/csscritic) - 轻量级 CSS 回归测试.
- [Spectre](https://github.com/wearefriday/spectre) - Provides image comparison capabilities and an admin interface for managing screenshots.
- [Shoov](https://github.com/shoov/shoov) - UI 回归和功能测试侧重于 Drupal 7 站点.
- [qd_screenshottests](https://www.drupal.org/project/qd_screenshottests) - 基于 CasperJS 的 UI 回归和功能测试专注于 Drupal 8 站点.
- [Look-alike](https://github.com/kdzwinel/Look-alike) - 用于截取和比较屏幕截图的 Chrome 扩展程序.
- [Hardy](https://github.com/thingsinjars/Hardy) - Selenium 驱动、黄瓜驱动的 CSS 测试.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
- [Needle](https://github.com/python-needle/needle) - Needle is a tool for testing visuals with Selenium and nose (Python).
- [gatling](https://github.com/gabrielrotbart/gatling) - Integrated visual RSpec matcher which makes real visual testing easy (Ruby).
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) - 通过您网站的截图照片会话防止您的项目布局损坏的插件.
- [vrtest](https://github.com/nathanmarks/vrtest) - 用于通过 selenium 跨浏览器在组件上运行视觉回归测试的 JavaScript 库.
- [Happo](https://github.com/Galooshi/happo) - 用户界面的 CI 中的视觉差异.
- [reg-cli](https://github.com/bokuweb/reg-cli) - Visual regression test tool which output easy-to-read single file html report.
- [Nightmare](https://github.com/segmentio/nightmare) - 基于 Electron 的高级浏览器自动化库.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - 无头 Google Chrome 节点 API.
- [Playwright](https://github.com/microsoft/playwright) - Node library to automate Chromium, Firefox and WebKit with a single API.
- [reg-suit](https://github.com/reg-viz/reg-suit) - 视觉回归测试套件，用于比较图像、存储快照并将差异通知到您的 GitHub 存储库.
- [Chimp](https://github.com/xolvio/chimp) - 使用实时反馈开发验收测试和端到端测试.
- [Differencify](https://github.com/NimaSoroush/differencify) - 用于视觉回归测试的库，使用 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ResembleJS](https://github.com/Huddle/Resemble.js) - 使用 Javascript 和 HTML5 分析和比较图像.
- [Muppeteer](https://github.com/HuddleEng/Muppeteer) - 使用 Chrome 的视觉回归测试框架 [Mocha](https://mochajs.org/) and [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ember-visual-test](https://github.com/Cropster/ember-visual-test) - 简单的视觉回归测试 [Ember](https://emberjs.com/).
- [AET](https://github.com/Cognifide/aet) - Scalable testing tool providing visual regression testing, accessibility and performance validation, markup analysis and more.
- [Wendigo](https://github.com/angrykoala/wendigo) - 基于 Puppeteer 的面向测试的浏览器自动化库.
- [Loki](https://github.com/oblador/loki) - 在 docker 等人中使用 Chrome 对 Storybook 进行视觉回归测试.
- [Zombie.js](http://zombie.js.org/) - 使用 Node.js 进行快速、无头的全栈测试.
- [CodeceptJS](https://github.com/codeception/codeceptjs/) - 适用于 NodeJS 的现代时代验收测试框架.
- [FuncUnit](https://github.com/bitovi/funcunit) - A functional test suite based on jQuery
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于 Node.js 并使用 Webdriver 协议的自动化测试和持续集成框架.
- [Protractor](https://github.com/angular/protractor) - E2E test framework for Angular apps.
- [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) - Visual regression testing with Jest and puppeteer for React components
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) - Jest matcher that performs image comparisons using [pixelmatch](https://www.npmjs.com/package/pixelmatch)
- [test-crawler](https://github.com/apiel/test-crawler) - 视觉回归测试，通过抓取网站并提供快照比较报告.
- [wdio-visual-regression](https://github.com/ennjin/wdio-visual-regression) - Visual regression tool for webdriver.io
- [Selenide](https://github.com/selenide/selenide) - Framework powered by Selenium WebDriver for writing easy-to-read and easy-to-maintain automated tests in Java.
- [Karma](http://karma-runner.github.io/latest/index.html) - A test runner by the AngularJS team, that fits all our needs.

## Online services

- [BrowserStack](https://www.browserstack.com)  - 开源免费. 支持 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [LambdaTest](https://www.lambdatest.com/) - 在线对 2000 多个真实浏览器和操作系统执行自动化和实时交互式跨浏览器测试.
- [screener.io](https://screener.io) - For React, looks open source.
- [applitools](https://applitools.com) - 基于云的视觉测试.
- [percy.io](https://percy.io) - 网络应用程序的持续视觉评论.
- [screenster.io](http://screenster.io) - 基于云的 Web 和移动 UI 自动化测试平台.
- [browserling](https://www.browserling.com) - LIVE interactive cross-browser testing.
- [Browser Shots](http://browsershots.org) - 仅截图.
- [Ghost Inspector](https://ghostinspector.com) - 看 [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com) - Manual & exploratory testing on 1500+ real browsers and mobile devices.
- [Argos-CI](https://www.argos-ci.com) - 自动化视觉回归测试.
- [Diffy](https://diffy.website) - Cloud based visual regression tool. Uses puppeteer and proprietary comparison algorithm (detect layout shifts). Great scalability with AWS Lambda.
- [Chromatic](https://www.chromatic.com/)  - 组件库的可视化测试和 UI 审查. 基于云. [Video](https://youtu.be/6KDLJBcutQE)
- [VisWiz.io](https://www.viswiz.io) - Flexible visual regression testing service.
- [Happo](https://happo.io/) - 基于云的屏幕截图测试服务，支持多种浏览器.
- [Visual Knight](https://visual-knight.io/) - 基于云的可视化测试平台，具有测试工具的实时结果.
- [Axcept](https://axcept.io) - Testing for the whole team. Up to 100 tests in parallel. Endpoint Mocking. Code Coverage. 
- [Fluxguard](https://fluxguard.com) - 屏幕截图像​​素和 DOM 变化比较和回归.
- [Vidiff](https://vidiff.com) - 跨阶段的基于云的视觉回归测试.
- [Reflect](https://reflect.run) - Visual regression testing and test automation tool.
- [Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker) - 用于视觉回归测试的开源自托管服务
- [Micoo](https://github.com/Mikuu/Micoo) - 所有UI应用可视化回归解决方案的开源服务

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - 比较：Wraith、PhantomCSS、Gemini、WebdriverCSS 和 Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -  Tutorial using BackstopJS.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - 使用 BackstopJS 的教程.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - 使用 BackstopJS 的教程.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - 为什么你应该使用 BackstopJS.
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) - PhantomCSS 简介.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome 正在颠覆传统的自动化测试方法.
- [Visual regression testing using Jest, Chromeless and AWS Lambda](https://github.com/novemberfiveco/visual-regression-testing-jest-chromeless) - 使用 Chromeless 和 jest-image-snapshot 的教程.
- [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - 简介 [Differencify](https://github.com/NimaSoroush/differencify) 以及如何使用它.
- [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - Tutorial to setup visual testing with Puppeteer, Jest and VisWiz.io.
- [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - 使用 percy 和 jest puppeteer 直观地测试 React 组件库.
- [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - 在 Spec Reporter 中使用 WebdriverIO 和 WebdriverCSS 的教程
- [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
- [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)
- [theheadless.dev](https://theheadless.dev) - 包含实用指南和 Playwright 和 Puppeteer 的可运行示例的博客.
- [Visual regression testing for Hugo with Github-CI and BackstopJS](https://jameskiefer.com/posts/visual-regression-testing-for-hugo-with-github-ci-and-backstopjs/) - How to automate regression testing for Hugo with BackstopJS
- [UI Visual Regression Testing with Micoo](https://mikuu.medium.com/ui-visual-regression-testing-with-micoo-12c7a4a036b9) - Introduction about how to do visual regression testing with Micoo service 


## Slideshows, talks and videos

- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - Screencast: Basic introduction to wraith, a screenshot comparison tool.
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - 如何设置 shoov 并编写您的第一个测试.
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) - Talk by Jon Bellah on how to use PhantomCSS during wordpress development.
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - Screencast with code demo and best practices.
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - Tutorial on how to create visual automated tests with Screenster.
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - Demo what the Look-alike Chrome extension is, how it works and how and why it was build.
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - 如何用 CSS 评论家编写你的第一个 CSS 测试，让它通过，打破它，让它再次通过.
- [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) 作者 Nikhil Verma - Badoo 中的移动 Web 团队如何将 PhantomCSS 转换并集成到他们的工作流程中，并将其连接到他们的 CI 流程.

## Deprecated

The following projects are no longer maintained actively but are still worth mentioning because of their user base.

- [PhantomJS](https://github.com/ariya/phantomjs)  - 可编写脚本的无头 WebKit. 自 2018 年 6 月 2 日起不再维护.
- [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS or SlimerJS. No longer maintained since 22 Dec 2017.
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) - 基于决策树的 UI 测试实验方法.
- [DalekJS](https://github.com/dalekjs/dalek)  - 使用 JavaScript 自动进行跨浏览器测试. 自 2017 年 6 月 4 日起不再维护.
- [dpxdt](https://github.com/bslatkin/dpxdt) - 使用 Python 进行端到端测试.
- [Visual Review](https://github.com/xebia/VisualReview) - A human-friendly tool for testing and reviewing visual regressions.
- [Huxley](https://github.com/facebookarchive/huxley) - 基于 Python 框架 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - WebdriverCSS 位于 [Webdriver.io](https://github.com/webdriverio/webdriverio/) 并钩入 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) - Feature rich framework with support for [Selenium](https://github.com/SeleniumHQ/selenium) and  [CasperJS](https://github.com/casperjs/casperjs). Gemini is deprecated, use hermione instead.
- [OcularJS](https://github.com/mmacartney10/ocularjs) - 用途 [PhantomJS](https://github.com/ariya/phantomjs).

## Miscellaneous

### Contributing

See the [Contribution Guide](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 有关如何贡献的详细信息.

### Code of Conduct

See the [Code of Conduct](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CODE-OF-CONDUCT.md) 详情. 基本上它归结为：
&gt; 为了营造一个开放和热情的环境，我们作为
contributors and maintainers pledge to making participation in our project and
我们的社区为每个人提供无骚扰的体验，无论年龄、身体如何
size, disability, ethnicity, gender identity and expression, level of experience,
国籍、个人外貌、种族、宗教或性身份和性取向。

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

本作品已获得许可 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
License holders are [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
