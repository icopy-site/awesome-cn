<div class="github-widget" data-repo="mojoaxel/awesome-regression-testing"></div>
## Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的视觉回归测试资源列表.

 回归测试是一种软件测试，用于验证先前开发和测试的软件在更改或与其他软件接口后仍然执行相同的操作.  回归测试的目的是确保软件的更改不会引入新的错误.

## Foreword

 这是关于视觉回归测试的*不完整*资源列表.  它不是针对特定区域或角色（Developer / QA / UX-Designer）定制的.  请注意，这是针对回归软件测试*的所有区域*之后编写的相关代码.  有关一般软件测试的精彩列表，请参阅例如 [awesome-testing](https://github.com/TheJambo/awesome-testing).

 最后，我确信阅读此列表的每个人都有一件他们想要添加的内容.  请阅读 [How to Contribute](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md)  页面和**随意添加到列表!! **.  如果你认为这是有帮助的**请给一个明星★**.



## General information

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
- [visualregressiontesting.com](https://visualregressiontesting.com/) - 基本的链接集合.

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) - 浏览器自动化框架和生态系统
- [SlimerJS](https://github.com/laurentj/slimerjs) - 基于Firefox的可编写脚本的浏览器，如PhantomJS.
- [trifleJS](https://github.com/sdesalas/trifleJS) -  Internet Explorer的无头自动化.
- [CasperJS](https://github.com/casperjs/casperjs) -  PhantomJS和SlimerJS的导航脚本和测试实用程序.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) -  W3C WebDriver协议的Node.js绑定实现.
- [Navalia](https://github.com/joelgriffith/navalia) - 基于无头Chrome和GraphQL的浏览器自动化.
- [Chromeless](https://github.com/graphcool/chromeless)   -  Chrome自动化变得简单.  在AWS Lambda上本地运行或无头运行.
- [Cypress.io](https://www.cypress.io/) - 在浏览器中运行的自动化框架.

## Tools and frameworks

- [AyeSpy](https://github.com/newsuk/ayespy) - 在90秒内进行44次图像比较.
- [Wraith](https://github.com/BBC-News/wraith) - 易于使用的红宝石工具，支持docker.
- [BackstopJS](https://github.com/garris/BackstopJS) - 配置驱动的自动截图测试框架.
- [Galen](https://github.com/galenframework/galen) - 基于Java框架 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) - 功能丰富的框架，支持 [Selenium](https://github.com/SeleniumHQ/selenium) 和  [CasperJS](https://github.com/casperjs/casperjs).
- [Huxley](https://github.com/facebookarchive/huxley) - 基于Python的Python框架 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) - 基于决策树的UI测试的实验方法.
- [CSSCritic](https://github.com/cburgmer/csscritic) - 轻量级CSS回归测试.
- [Spectre](https://github.com/wearefriday/spectre) - 提供图像比较功能和管理界面，用于管理屏幕截图.
- [Shoov](https://github.com/shoov/shoov) - 关注Drupal 7站点的UI回归和功能测试.
- [OcularJS](https://github.com/mmacartney10/ocularjs) - 用途 [PhantomJS](https://github.com/ariya/phantomjs).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) -  WebdriverCSS位于顶部 [Webdriver.io](https://github.com/webdriverio/webdriverio/) 并挂钩 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Look-alike](https://github.com/kdzwinel/Look-alike) - 用于获取和比较屏幕截图的Chrome扩展程序.
- [Hardy](https://github.com/thingsinjars/Hardy) - 硒驱动，黄瓜动力的CSS测试.
- [TestCafe](https://github.com/DevExpress/testcafe) - 针对现代Web开发堆栈的自动浏览器测试.
- [Needle](https://github.com/python-needle/needle) -  Needle是一种用Selenium和nose（Python）测试视觉效果的工具.
- [gatling](https://github.com/gabrielrotbart/gatling) - 集成的可视RSpec匹配器，使真正的视觉测试变得容易（Ruby）.
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) - 插件，以防止您的项目通过您的网站的截图照片会话破坏布局.
- [vrtest](https://github.com/nathanmarks/vrtest) - 用于通过selenium跨浏览器在组件上运行可视化回归测试的JavaScript库.
- [Happo](https://github.com/Galooshi/happo) -  CI中用于用户界面的视觉差异.
- [reg-cli](https://github.com/bokuweb/reg-cli) - 视觉回归测试工具，输出易于阅读的单文件html报告.
- [Nightmare](https://github.com/segmentio/nightmare) - 基于Electron的高级浏览器自动化库.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - 无头谷歌Chrome节点API.
- [Visual Review](https://github.com/xebia/VisualReview) - 用于测试和检查视觉回归的人性化工具.
- [reg-suit](https://github.com/reg-viz/reg-suit) - 视觉回归测试套件，用于比较图像，存储快照，并通知您与GitHub仓库的差异.
- [Chimp](https://github.com/xolvio/chimp) - 通过实时反馈开发验收测试和端到端测试.
- [Differencify](https://github.com/NimaSoroush/differencify) - 使用的视觉回归测试库 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ResembleJS](https://github.com/Huddle/Resemble.js) - 使用Javascript和HTML5分析和比较图像.
- [Muppeteer](https://github.com/HuddleEng/Muppeteer) - 使用Chrome的视觉回归测试框架 [Mocha](https://mochajs.org/) 和 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ember-visual-test](https://github.com/Cropster/ember-visual-test) - 简单的视觉回归测试 [Ember](https://emberjs.com/).
- [AET](https://github.com/Cognifide/aet) - 可扩展的测试工具，提供可视化回归测试，可访问性和性能验证，标记分析等.
- [Wendigo](https://github.com/angrykoala/wendigo) - 基于Puppeteer的面向测试的浏览器自动化库.
- [Loki](https://github.com/oblador/loki) - 在docker等人中使用Chrome进行故事书的视觉回归测试.
- [Zombie.js](http://zombie.js.org/) - 使用Node.js进行疯狂快速的无头全栈测试.
- [CodeceptJS](https://github.com/codeception/codeceptjs/) -  NodeJS的现代时代验收测试框架.
- [FuncUnit](https://github.com/bitovi/funcunit) - A functional test suite based on jQuery
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于Node.js和使用Webdriver协议的自动化测试和持续集成框架.
- [Protractor](https://github.com/angular/protractor) -  Angular应用程序的E2E测试框架.
- [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) - 使用Jest和puppeteer对React组件进行可视化回归测试
- [test-crawler](https://github.com/apiel/test-crawler) - 通过爬网和提供快照比较报告进行可视化回归测试.

## Online services

- [BrowserStack](https://www.browserstack.com)   - 免费开源.  支持 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [screener.io](https://screener.io) - 对于React，看起来是开源的.
- [applitools](https://applitools.com) - 云基视觉测试.
- [percy.io](https://percy.io) - 针对网络应用的持续视觉评论.
- [screenster.io](http://screenster.io) - 基于云的自动化测试平台，适用于Web和移动UI.
- [MogoTest](http://mogotest.com) -  SEO专家的网站浏览器测试工具.
- [browserling](https://www.browserling.com) - 实时交互式跨浏览器测试.
- [Browser Shots](http://browsershots.org) - 仅限截图.
- [Ghost Inspector](https://ghostinspector.com) - 见 [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com) - 在1500多个真实浏览器和移动设备上进行手动和探索性测试.
- [Argos-CI](https://www.argos-ci.com) - 自动化视觉回归测试.
- [BackTrac](https://backtrac.io)   - 基于云的视觉回归工具.  使用无头firefox和专有比较算法（检测布局移位）.
- [Chromatic](https://www.chromaticqa.com)   - 组件库的可视化测试和UI审查.  基于云. [Video](https://youtu.be/6KDLJBcutQE)
- [VisWiz.io](https://www.viswiz.io) - 灵活的视觉回归测试服务.
- [Happo](https://happo.io/) - 基于云的屏幕截图测试服务，支持多种浏览器.
- [Visual Knight](https://visual-knight.io/) - 基于云的可视化测试平台，具有测试工具的实时结果.
- [Axcept](https://axcept.io)   - 测试整个团队.  最多100个并行测试.  端点模拟.  代码覆盖范围. 
- [Fluxguard](https://fluxguard.com) - 屏幕截图像​​素和DOM更改比较和回归.

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - 比较：Wraith，PhantomCSS，Gemini，WebdriverCSS和Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) - 使用BackstopJS的教程.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - 使用BackstopJS的教程.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - 使用BackstopJS的教程.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - 为什么你应该使用BackstopJS.
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) -  PhantomCSS简介.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - 无头Chrome正在撼动传统的测试自动化方法.
- [Visual regression testing using Jest, Chromeless and AWS Lambda](https://novemberfive.co/blog/visual-regression-testing-jest-chromeless-lambda) - 使用Chromeless和jest-image-snapshot的教程.
- [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - 介绍 [Differencify](https://github.com/NimaSoroush/differencify) 以及如何使用它.
- [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - 使用Puppeteer，Jest和VisWiz.io设置可视化测试的教程.
- [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - 使用percy和jest puppeteer直观地测试React组件库.
- [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - 使用带有Spec Reporter的WebdriverIO和WebdriverCSS的教程

## Slideshows, talks and videos

- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - 截屏视频：幽灵的基本介绍，截图比较工具.
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - 如何设置shoov并完成第一次测试.
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) -  Jon Bellah谈论如何在wordpress开发过程中使用PhantomCSS.
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - 使用代码演示和最佳实践的截屏视频.
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - 有关如何使用Screenster创建可视化自动化测试的教程.
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - 演示看起来相似的Chrome扩展程序，它是如何工作的以及它的构建方式和原因.
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - 如何用CSS评论家编写你的第一个CSS测试，让它通过，打破它，并让它再次通过.
- [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) 作者：Nikhil Verma  -  Badoo的移动Web团队如何将PhantomCSS转换并集成到他们的工作流程中，并将其连接到他们的CI流程.

## Deprecated

以下项目不再积极维护，但仍因其用户群而值得一提.

- [PhantomJS](https://github.com/ariya/phantomjs)   -  Scriptable Headless WebKit.  自2018年6月2日起不再维持.
- [PhantomCSS](https://github.com/Huddle/PhantomCSS)   - 使用PhantomJS或SlimerJS进行Visual / CSS回归测试.  自2017年12月22日起不再维护.
- [DalekJS](https://github.com/dalekjs/dalek)   - 使用JavaScript自动进行跨浏览器测试.  自2017年6月4日起不再维护.
- [dpxdt](https://github.com/bslatkin/dpxdt) - 使用Python进行端到端测试.

## Miscellaneous

### Contributing

见 [Contribution Guide](https://github.com/mojoaxel/awesome-regression-testing/blob/master/CONTRIBUTING.md) 有关如何贡献的详细信息.

### Code of Conduct

见 [Code of Conduct](https://github.com/mojoaxel/awesome-regression-testing/blob/master/CODE-OF-CONDUCT.md)  详情.  基本上它归结为：
&gt;为了营造一个开放和热情的环境，我们就像
贡献者和维护者承诺参与我们的项目和
我们的社区为每个人提供无骚扰的体验，无论年龄，身体
大小，残疾，种族，性别认同和表达，经验水平，
国籍，个人形象，种族，宗教或性别认同和取向.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

这项工作是根据a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
许可证持有人 [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
