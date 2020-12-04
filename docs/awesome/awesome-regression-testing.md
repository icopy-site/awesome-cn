<div class="github-widget" data-repo="mojoaxel/awesome-regression-testing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的出色视觉回归测试资源列表.

回归测试是一种软件测试，它可以验证先前开发和测试的软件在更改或与其他软件连接后仍以相同的方式运行. 回归测试的目的是确保对软件的更改不会引入新的错误.

## Foreword

这是关于视觉回归测试的资源的“不完整”列表. 它不是针对特定领域或角色（Developer / QA / UX-Designer）量身定制的. 请注意，这适用于*在编写相关代码后*的所有回归软件测试领域. 有关常规软件测试的出色列表，请参见例如 [awesome-testing](https://github.com/TheJambo/awesome-testing).

最后，我确定阅读此列表的每个人都想添加一件事. 请阅读 [How to Contribute](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 页面和**随时添加到列表中！**. 如果您认为这样做有帮助**请给星号★**.



## General information

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
- [visualregressiontesting.com](https://visualregressiontesting.com/) -链接的基本集合.

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) -浏览器自动化框架和生态系统.
- [SlimerJS](https://github.com/laurentj/slimerjs) -基于Firefox的可编写脚本的浏览器，例如PhantomJS.
- [trifleJS](https://github.com/sdesalas/trifleJS) -Internet Explorer的无头自动化.
- [CasperJS](https://github.com/casperjs/casperjs) -用于PhantomJS和SlimerJS的导航脚本和测试实用程序.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) -W3C WebDriver协议的Node.js绑定实现.
- [Navalia](https://github.com/joelgriffith/navalia) -基于无头Chrome和GraphQL的浏览器自动化.
- [Chromeless](https://github.com/graphcool/chromeless)  -Chrome自动化变得简单. 在AWS Lambda上本地运行或无头运行.
- [Cypress.io](https://www.cypress.io/) -在浏览器中运行的自动化框架.

## Tools and frameworks

- [basset](https://basset.io)  -用于生成和检查视觉差异的开源平台. 支持多种浏览器，以及github和slack的集成.
- [AyeSpy](https://github.com/newsuk/ayespy) -90秒内进行44张图像比较.
- [Wraith](https://github.com/BBC-News/wraith) -在docker支持下易于使用的ruby工具.
- [BackstopJS](https://github.com/garris/BackstopJS) -配置驱动的自动屏幕截图测试框架.
- [Galen](https://github.com/galenframework/galen) -基于Java框架 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Creevey](https://github.com/wKich/creevey)  -跨浏览器的魔术视觉测试. 具有UI Runner的功能丰富的工具，可测试热重载，Docker和Storybook集成.
- [CSSCritic](https://github.com/cburgmer/csscritic) -轻量级CSS回归测试.
- [Spectre](https://github.com/wearefriday/spectre) -提供图像比较功能和用于管理屏幕截图的管理界面.
- [Shoov](https://github.com/shoov/shoov) -UI回归和功能测试侧重于Drupal 7网站.
- [qd_screenshottests](https://www.drupal.org/project/qd_screenshottests) -基于CasperJS的UI回归和功能测试侧重于Drupal 8网站.
- [Look-alike](https://github.com/kdzwinel/Look-alike) -Chrome扩展程序，用于获取和比较屏幕截图.
- [Hardy](https://github.com/thingsinjars/Hardy) -硒驱动，黄瓜驱动的CSS测试.
- [TestCafe](https://github.com/DevExpress/testcafe) -针对现代Web开发堆栈的自动化浏览器测试.
- [Needle](https://github.com/python-needle/needle) -Needle是使用硒和鼻子（Python）测试视觉效果的工具.
- [gatling](https://github.com/gabrielrotbart/gatling) -集成的可视化RSpec匹配器，使真正的可视化测试变得容易（Ruby）.
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) -插件可通过您的网站的屏幕快照会话防止项目布局被破坏.
- [vrtest](https://github.com/nathanmarks/vrtest) -JavaScript库，用于通过硒跨浏览器在组件上运行视觉回归测试.
- [Happo](https://github.com/Galooshi/happo) -CI在用户界面中的视觉差异.
- [reg-cli](https://github.com/bokuweb/reg-cli) -视觉回归测试工具，可输出易于阅读的单个文件html报告.
- [Nightmare](https://github.com/segmentio/nightmare) -基于Electron的高级浏览器自动化库.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) -无头Google Chrome节点API.
- [Playwright](https://github.com/microsoft/playwright) -节点库，可通过单个API自动化Chromium，Firefox和WebKit.
- [reg-suit](https://github.com/reg-viz/reg-suit) -视觉回归测试套件，用于比较图像，存储快照，并将差异通知您的GitHub存储库.
- [Chimp](https://github.com/xolvio/chimp) -开发具有实时反馈的验收测试和端到端测试.
- [Differencify](https://github.com/NimaSoroush/differencify) -使用以下工具进行视觉回归测试的库 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ResembleJS](https://github.com/Huddle/Resemble.js) -使用Javascript和HTML5分析和比较图像.
- [Muppeteer](https://github.com/HuddleEng/Muppeteer) -使用的Chrome视觉回归测试框架 [Mocha](https://mochajs.org/) 和 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ember-visual-test](https://github.com/Cropster/ember-visual-test) -简单的视觉回归测试 [Ember](https://emberjs.com/).
- [AET](https://github.com/Cognifide/aet) -可扩展的测试工具，提供可视化回归测试，可访问性和性能验证，标记分析等.
- [Wendigo](https://github.com/angrykoala/wendigo) -基于Puppeteer的面向测试的浏览器自动化库.
- [Loki](https://github.com/oblador/loki) -在docker等中使用Chrome浏览器对Storybook进行视觉回归测试.
- [Zombie.js](http://zombie.js.org/) -使用Node.js进行快速，无头的全栈测试.
- [CodeceptJS](https://github.com/codeception/codeceptjs/) -NodeJS的现代时代验收测试框架.
- [FuncUnit](https://github.com/bitovi/funcunit) -基于jQuery的功能测试套件
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) -基于Node.js并使用Webdriver协议的自动化测试和持续集成框架.
- [Protractor](https://github.com/angular/protractor) -Angular应用的E2E测试框架.
- [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) -使用Jest和puppeteer对React组件进行视觉回归测试
- [test-crawler](https://github.com/apiel/test-crawler) -通过爬网网站并提供快照比较报告来进行视觉回归测试.
- [wdio-visual-regression](https://github.com/ennjin/wdio-visual-regression) -webdriver.io的视觉回归工具
- [Selenide](https://github.com/selenide/selenide) -由Selenium WebDriver支持的框架，用于用Java编写易于阅读和易于维护的自动化测试.
- [Karma](http://karma-runner.github.io/latest/index.html) -AngularJS团队的测试跑步者，可以满足我们的所有需求.

## Online services

- [BrowserStack](https://www.browserstack.com)  -开源免费. 支持 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [LambdaTest](https://www.lambdatest.com/) -在2000多种真实浏览器和在线操作系统上执行自动化和实时交互式浏览器的实时测试.
- [screener.io](https://screener.io) -对于React，看起来是开源的.
- [applitools](https://applitools.com) -云基础视觉测试.
- [percy.io](https://percy.io) -对Web应用程序的连续视觉审查.
- [screenster.io](http://screenster.io) -用于Web和移动UI的基于云的自动化测试平台.
- [browserling](https://www.browserling.com) -实时交互式跨浏览器测试.
- [Browser Shots](http://browsershots.org) -仅屏幕截图.
- [Ghost Inspector](https://ghostinspector.com) -看 [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com) -在1500多种真实浏览器和移动设备上进行手动和探索性测试.
- [Argos-CI](https://www.argos-ci.com) -自动化视觉回归测试.
- [Diffy](https://diffy.website)  -基于云的视觉回归工具. 使用操纵符和专有比较算法（检测布局偏移）.  AWS Lambda具有出色的可扩展性.
- [Chromatic](https://www.chromaticqa.com)  -组件库的视觉测试和UI审查. 基于云. [Video](https://youtu.be/6KDLJBcutQE)
- [VisWiz.io](https://www.viswiz.io) -灵活的视觉回归测试服务.
- [Happo](https://happo.io/) -基于云的屏幕截图测试服务，支持多种浏览器.
- [Visual Knight](https://visual-knight.io/) -基于云的可视化测试平台，具有测试工具的实时结果.
- [Axcept](https://axcept.io)  -测试整个团队. 最多并行进行100个测试. 端点模拟. 代码覆盖率. 
- [Fluxguard](https://fluxguard.com) -屏幕截图像​​素和DOM更改比较和回归.
- [Vidiff](https://vidiff.com) -跨阶段的基于云的视觉回归测试.
- [Reflect](https://reflect.run) -视觉回归测试和测试自动化工具.
- [Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker) -用于视觉回归测试的开源自托管服务

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) -比较：Wraith，PhantomCSS，Gemini，WebdriverCSS和Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -使用BackstopJS的教程.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) -使用BackstopJS的教程.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) -使用BackstopJS的教程.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) -为什么要使用BackstopJS.
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) -PhantomCSS简介.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) -无头Chrome正在改变传统的自动化测试方法.
- [Visual regression testing using Jest, Chromeless and AWS Lambda](https://novemberfive.co/blog/visual-regression-testing-jest-chromeless-lambda) -使用Chromeless和jest-image-snapshot的教程.
- [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) -介绍 [Differencify](https://github.com/NimaSoroush/differencify) 以及如何使用它.
- [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) -使用Puppeteer，Jest和VisWiz.io设置视觉测试的教程.
- [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) -使用percy和jest puppeteer在视觉上测试React组件库.
- [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) -将WebdriverIO和WebdriverCSS与Spec Reporter结合使用的教程
- [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
- [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)
- [theheadless.dev](https://theheadless.dev) -有关Playwright和Puppeteer的实用指南和可运行示例的博客.
- [Visual regression testing for Hugo with Github-CI and BackstopJS](https://jameskiefer.com/posts/visual-regression-testing-for-hugo-with-github-ci-and-backstopjs/) -如何使用BackstopJS自动化Hugo的回归测试


## Slideshows, talks and videos

- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) -截屏视频：幽灵的基本介绍，一种截图比较工具.
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) -如何设置shoov并编写您的第一个测试.
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) -乔恩·贝拉（Jon Bellah）谈论如何在wordpress开发过程中使用PhantomCSS.
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) -包含代码演示和最佳实践的截屏视频.
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) -有关如何使用Screenster创建可视化自动化测试的教程.
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) -演示Chrome扩展程序的外观，功能，工作方式以及构建原因.
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) -如何与CSS评论家一起编写您的第一个CSS测试，使其通过，中断并再次通过.
- [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) 作者：Nikhil Verma-Badoo的移动Web团队如何将PhantomCSS转换并集成到他们的工作流程中，并将其连接到CI流程.

## Deprecated

以下项目不再积极维护，但由于其用户群而仍然值得一提.

- [PhantomJS](https://github.com/ariya/phantomjs)  -可编写脚本的无头WebKit. 自2018年6月2日起不再维护.
- [PhantomCSS](https://github.com/Huddle/PhantomCSS)  -使用PhantomJS或SlimerJS进行Visual / CSS回归测试. 自2017年12月22日以来不再维护.
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) -基于决策树的UI测试的实验方法.
- [DalekJS](https://github.com/dalekjs/dalek)  -使用JavaScript自动进行跨浏览器测试. 自2017年6月4日起不再维护.
- [dpxdt](https://github.com/bslatkin/dpxdt) -使用Python进行端到端测试.
- [Visual Review](https://github.com/xebia/VisualReview) -用于测试和查看视觉回归的人性化工具.
- [Huxley](https://github.com/facebookarchive/huxley) -基于的Python框架 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) -WebdriverCSS位于 [Webdriver.io](https://github.com/webdriverio/webdriverio/) 并钩入 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) -功能丰富的框架，支持 [Selenium](https://github.com/SeleniumHQ/selenium) 和  [CasperJS](https://github.com/casperjs/casperjs) . 不建议使用双子座，请改用赫敏.
- [OcularJS](https://github.com/mmacartney10/ocularjs) -用途 [PhantomJS](https://github.com/ariya/phantomjs).

## Miscellaneous

### Contributing

见 [Contribution Guide](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 有关如何贡献的详细信息.

### Code of Conduct

见 [Code of Conduct](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CODE-OF-CONDUCT.md) 有关详细信息. 基本上可以归结为：
&gt;为了营造开放和热情的环境，我们
贡献者和维护者保证参与我们的项目，并且
我们的社区为每个人，不论年龄，身材，提供无骚扰的体验
大小，残疾，种族，性别认同和表达，经验水平，
nationality, personal appearance, race, religion, or sexual identity and orientation.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

这项工作是根据 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
许可证持有人是 [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
