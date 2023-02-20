<div class="github-widget" data-repo="TheJambo/awesome-testing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
![](https://github.com/TheJambo/awesome-testing/blob/master/AwesomeTesting.jpg?raw=true)

## Awesome Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Dead link checker](https://github.com/TheJambo/awesome-testing/actions/workflows/404-links.yml/badge.svg)](https://github.com/TheJambo/awesome-testing/actions/workflows/404-links.yml)
&gt; 精选的测试软件、扩展和资源列表

## Foreword
这旨在成为软件测试社区中新人的资源策展. 它不是针对特定领域（可用性/性能）或角色（自动化/管理）量身定制的. 这个想法是，你可以将这份清单交给 CS 毕业生，这将大大提高他们的测试技能、效率和整体知识广度. 请注意，这适用于编写相关代码后的所有软件测试领域（无单元测试/静态分析！）.

最后，我相信每个阅读此列表的人都想添加一件事. 请阅读 [How to Contribute](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md) 页并添加到列表中.  :)




## Software

### Security
- [BeEF](http://beefproject.com/) - 操纵浏览器利用您发现的任何 XSS 漏洞.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy)  - 此拦截代理允许您查看所有 HTTP 流量并实时对其进行操作. 易于扫描、编目和利用安全问题.

### Make your life easier
- [Courgette](https://courgette-testing.com)  - 精美简单的 UI 测试. 使用 Gherkin、Gherkin 模板和可组合的 YAML 样式页面和组件对象的正确声明式 BDD 场景.
- [BareTail](https://www.baremetalsoft.com/baretail/) - 将 tail linux 命令引入 Windows、彩色线条和 REGEX 搜索以及加载其他功能.
- [ProxySwitcher](https://chrome.google.com/webstore/detail/proxy-switcher-manager/onnfghpihccifgojkpnnncpagjcdbjod) - 我们都必须使用代理，这使得使用 Test/Prod/localhost 代理时更容易.
- [Full Page Screenshot](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl) - 当 PrintScreen 不够大时.
- [Form Filler](https://chrome.google.com/webstore/detail/form-filler/bnjjngeaknajbdcgpfkgnonkmififhfo) - 每次填写大表格真的很烦人，用虚拟数据加快速度.
- [Bug Magnet](https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi) - 根据字段类型建议值.
- [Check All](https://chrispederick.com/work/web-developer/)  - “全选”通常不可用. 为什么不自己带？
- [Xmind](http://www.xmind.net/) - 用于记录测试的最佳（免费）思维导图工具.
- [TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code) - 开源测试用例管理系统
- [Fluxguard](https://fluxguard.com) - 屏幕截图像​​素和 DOM 变化比较和回归.
- [recheck-web](https://github.com/retest/recheck-web) - 与本地 Golden Masters 的开源更改比较工具、类似 git 的忽略语法和“牢不可破的硒”测试.
- [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) - 开源测试用例管理系统.
- [Captura](https://github.com/MathewSachin/Captura) - 开源视频录制工具.
- [QA Wolf](https://github.com/qawolf/qawolf) - 用于创建浏览器测试速度提高 10 倍的开源 Node.js 库.
- [Synth](https://github.com/getsynth/synth) - 开源测试数据生成器.
- [Requestly](https://requestly.io/)  - 作为浏览器扩展和桌面应用程序的轻量级代理，用于拦截和修改网络请求. 您可以修改标头、重定向 Url、模拟 API 响应、延迟/限制请求等.
- [Robot Framework](https://robotframework.org/)  - 通用开源自动化框架. 它可用于测试和机器人流程自动化 (RPA).
- [wopee.io](https://wopee.io/) - 自主测试平台，为自主视觉回归测试提供机器人.
- [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP)  - DeepfakeHTTP 是一种 Web 服务器，它使用 HTTP 转储作为响应源. 该工具允许您针对 REST、GraphQL 和其他 API 测试客户端.
- [Keploy](https://github.com/keploy/keploy) - API 测试平台，自动生成单元测试用例以及来自 API 调用的依赖模拟（测试数据）.
- [BugBug](https://bugbug.io)  - 用于 Web 应用程序的轻量级测试自动化工具. 易于学习，不需要编码. 它是免费的，可以进行无限制的测试. 每月支付额外费用，您还可以获得云监控和 CI/CD 集成.
- [Touca](https://github.com/trytouca/trytouca) - 开源持续回归测试，将软件的行为和性能与以前的基线版本进行比较.
- [test-each](https://github.com/ehmicky/test-each) - 使用不同的输入重复测试（数据驱动测试）.
- [Replayable](https://replayable.io) - 桌面行车记录仪，可帮助您在手动测试期间捕获意外错误.
- [RestQA](https://github.com/restqa/restqa) - 基于 ghekin 的 REST API 测试框架，使用一流的开发人员体验来管理微服务本地测试.

### Web3 and Blockchain
- [Dapp.tools](https://dapp.tools/) - 用于以太坊智能合约开发的命令行工具和智能合约库.
- [Ganache](https://trufflesuite.com/ganache/) - 个人以太坊区块链，您可以使用它来运行测试、执行命令和检查状态，同时控制链的运行方式.
- [Foundry](https://github.com/foundry-rs/foundry) - 用 Rust 编写的用于以太坊应用程序开发的快速、便携和模块化工具包.
- [Hardhat](https://hardhat.org/) - 多链以太坊开发环境.
- [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) - 这将流行的智能合约测试和部署库与 Robot Framework 结合在一起.
- [Truffle Suite](https://trufflesuite.com/) - 用于智能合约开发的综合工具套件.

### Other
- [Colour Blindness Simulator](https://altreus.github.io/colourblind/) - 立即模拟所有类型的色盲！
- [Yslow](http://yslow.org/) - 根据 Yahoo! 的性能规则分析网页速度慢的原因.

## Books
- [The Scrum Field Guide, Agile advice for your first year and beyond](https://amzn.to/2OERKEm) - 为什么您可能希望将您的公司转移到敏捷以及关于如何做到这一点的实用建议.
- [Fifty quick ideas to improve your Tests](https://amzn.to/2AzMUF7)  - 关于如何改进测试以及为什么要进行测试的很好的说明性示例. 非常适合作为赢得争论的证据！
- [Agile Testing: A Practical Guide](https://amzn.to/2n1K2aG) - 如何指导那些希望作为测试人员过渡到敏捷的人，以及作者如何在他们的敏捷团队中工作.
- [Explore It!: Reduce Risk and Increase Confidence with Exploratory Testing](https://amzn.to/2n8axLn) - 一本关于构建探索性测试和设计测试的好书.
- [The Domain Testing Workbook](https://amzn.to/2Az4l90) - 深入了解当今使用的最常见的测试技术，域测试（也称为边界分析和等价类划分），并提供大量示例以变得更好.
- [Don't Make Me Think: A Common Sense Approach to Web Usability](https://amzn.to/2naYmhf) - 一本非常有用的可用性测试书.
- [Lessons Learned in Software Testing](https://amzn.to/2LTjM01) - 关于软件测试的最好的书籍之一，分为小节课程，现在和出版时一样适用.
- [UI is Communication](https://amzn.to/2vbiALY) - 如何制作直观的用户界面（UI 和可用性测试）.
- [Thinking, Fast and Slow](https://amzn.to/2vcjasX) - 关于我们如何做出决定以及如何进行实验（实验 == 测试）.
- [Chaos Engineering: Crash test your applications](https://www.manning.com/books/chaos-engineering) - 一本关于如何设计和执行受控软件故障实验的书.
- [Testing JavaScript Applications](https://www.manning.com/books/testing-javascript-applications) - 一本关于开发人员的 JavaScript 测试工具和技术的书.
- [Chaos Engineering](https://www.manning.com/books/chaos-engineering) - 一本教您设计和执行可控实验以发现隐藏问题的书.
- [The Art of Unit Testing, Third Edition](https://www.manning.com/books/the-art-of-unit-testing-third-edition) - 一本指导您从第一个简单的单元测试逐步构建可维护、可读和可信赖的完整测试集的书.
- [Testing Web APIs](https://www.manning.com/books/testing-web-apis) - 通过实施自动化测试流程来保证 Web API 的质量和一致性.
- [Effective Software Testing](https://www.manning.com/books/effective-software-testing) - 为开发人员提供的关于如何以系统有效的方式创建高质量测试的实践指南.

## Training (Includes developer training for automation testers)
- [Learn to Code](https://github.com/karlhorky/learn-to-program) - 另一个很棒的开发人员培训列表
- [The Dojo](https://dojo.ministryoftesting.com/) - 直接来自测试社区的课程和谈话.
- [Guru99](http://www.guru99.com/) - 通过经验学习，比视频培训更有趣.
- [Coursera](https://www.coursera.org/) - 来自顶尖大学的在线课程.
- [Cybrary](https://www.cybrary.it/) - 在线免费安全培训.
- [BBST Testing Courses](https://bbst.courses/bbst-testingeducation-materials/)  - 著名的黑盒软件测试 (BBST) 课程是关于软件测试基础、错误报告和测试设计的大学水平课程. 这些材料已获得许可供任何人使用的知识共享. 包括文章、幻灯片和视频讲座.

## Blogs
- [James Bach](http://www.satisfice.com/blog/)
- [Michael Bolton](http://www.developsense.com/blog/)
- [Janet Gregory](http://janetgregory.ca/blog/)
- [Nikita Sobolev](https://sobolevn.me/)
- [Softwaretester Blog](https://www.softwaretester.blog/)
- [Automation Panda](https://automationpanda.com/)

## Newsletters
- [Software Testing Weekly](https://softwaretestingweekly.com/) - 每周五发布的最佳软件测试新闻和工具的精选综述.

## Suggested Awesome Lists

### Must Read
- [Falsehoods](https://github.com/kdeldycke/awesome-falsehood)  - 一份有趣且有教育意义的清单，说明为什么软件开发中的任何事情都不容易. 认为您可以将婚姻存储在数据库中吗？
- [Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)  - 这是著名的 Naughty Strings 列表. 如果您正在进行一些现场验证，无需再寻找灵感.
- [Unicode](https://github.com/jagracey/Awesome-Unicode) - 了解 unicode 工作原理及其可能导致的问题的重要资源.

### Useful References
- [The Original](https://github.com/sindresorhus/awesome) - 真棒列表的真棒列表.
- [Learn to Code](https://github.com/karlhorky/learn-to-program) - 学习编码，适合那些希望转向自动化的人
- [Application Security](https://github.com/paragonie/awesome-appsec) - 难以置信的广泛，但你会找到符合要求的东西.
- [Selenium](https://github.com/christian-bromann/awesome-selenium) - 如果您知道自己想要什么，比搜索谷歌更好.
- [Security](https://github.com/sbilly/awesome-security) - 这主要集中在基础设施上，但如果您正在测试一系列系统，这将非常有用.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) - 免费软件测试和验证资源列表.
- [Awesome Cucumber](https://github.com/virajkulkarni14/awesome-cucumber) - 一个（相对较新的）精选的黄瓜和小黄瓜相关资源列表.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - 围绕 Apache JMeter 精选的资源集合.
- [How They Test](https://github.com/abhivaikar/howtheytest) - 来自科技公司的精选公共资源集合，内容涉及他们如何测试软件和建立质量文化

## QA and Testing Road Map
- [How to start QA and Testing career](https://github.com/fityanos/Quality-Assurance-Road-Map) - 广泛而丰富的策略、主题和技能列表，是您开始软件测试和自动化职业生涯所需的.

## Others
- [Testers Rage Playlist](https://play.spotify.com/user/sanchezni/playlist/5yzT0HrymwEeO8ckqgkPiW) - 当红雾降临时，来自测试人员的协作播放列表.
- [Software Testing Conferences](http://testingconferences.org/) - 软件测试会议和研讨会列表.
- [Software Testing Interview Tool](https://github.com/TheJambo/ToDoInterviewTest) - 一个非常有问题的待办事项列表，以促进面对面的采访.

## Contributing
See the *Awesome Testing* [contribution guide](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md) 有关如何贡献的详细信息.

## Code of Conduct
见 [Code of Conduct](https://github.com/TheJambo/awesome-testing/blob/master/CODE-OF-CONDUCT.md) 了解详情. 基本上可以归结为：
&gt;为了营造一个开放和热情的环境，我们作为
贡献者和维护者承诺参与我们的项目，并且
我们的社区为每个人提供无骚扰的体验，无论年龄、身体如何
体型、残疾、种族、性别认同和表达、经验水平、
国籍、外貌、种族、宗教或性认同和性取向.


## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[
contributors](https://github.com/TheJambo/awesome-testing/graphs/contributors)
已放弃该作品的所有版权和相关或邻接权. 见
[license file](https://github.com/TheJambo/awesome-testing/blob/master/LICENSE) 了解详情.
