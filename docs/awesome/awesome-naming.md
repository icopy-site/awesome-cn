<div class="github-widget" data-repo="gruhn/awesome-naming"></div>
## Awesome Naming [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- lint disable no-repeat-punctuation -->
Famously...
<!-- lint enable no-repeat-punctuation -->

&gt; 计算机科学中只有两件难事：缓存失效和命名.
> 
&gt; ― 菲尔·卡尔顿

计算机科学中的概念通常没有任何有形的东西，因此命名事物很困难也就不足为奇了.
尽管如此，我们确实想出了聪明、有创意且有趣的名字.
其中一些是如此成熟，我们从未停下来钦佩.

这是一个精心策划的列表，说明何时正确命名事物.


- [Theoretical Computer Science](#theoretical-computer-science) 

---

## Data Structures and Algorithms

- [Backtracking](https://de.wikipedia.org/wiki/Backtracking) - 当您探索搜索空间并到达死胡同时，您可以沿着*轨迹*回到最后一个十字路口并尝试其他方式. 
- [Brute force](https://en.m.wikipedia.org/wiki/Brute-force_search) - 暴力实际上几乎总是一种解决方案，但不是一个非常聪明的解决方案.
- [Greedy algorithm](https://en.wikipedia.org/wiki/Greedy_algorithm) - 一种算法，通过始终选择当前最好看的选项来找到解决方案，而无需过多考虑过去和未来的决策.
- [Hill climbing](https://en.wikipedia.org/wiki/Hill_climbing)  - 从解决方案的丘陵“景观”中的某个地方开始，沿着最陡峭的上升方向，直到到达山顶. 不过，您可能会错过更高的山丘. 
- [Israeli Queue](https://rapidapi.com/blog/israeli-queues-exploring-a-bizarre-data-structure/)  - 一种优先队列以及对以色列臭名昭著的无组织队列的引用. 当这里的物品*已经有朋友在等待*时，它们可以*插队*.
- [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) - 就像一堆煎饼一样，您只能在此数据结构的顶部添加和删除项目.
- [Tree](https://en.wikipedia.org/wiki/Tree_(data_structure) ) - 分层组织的数据结构. 从_root_项开始，其他项_分支_为_nodes_和_leaves_. 树木的集合通常称为“森林”.
- [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) - 在此数据结构中，项目始终在末尾添加并在前面删除，就好像项目在排队等待一样.

## Design Patterns and Anti Patterns

- [Adapter](https://en.wikipedia.org/wiki/Adapter_pattern) - 通过将其自己的接口包装在现有类的接口周围，允许具有不兼容接口的类一起工作.
- [Facade](https://en.wikipedia.org/wiki/Facade_pattern) - 类似于建筑中的立面，立面是一个充当前端界面的对象，掩盖了更复杂的底层结构.
- [Promise](https://en.wikipedia.org/wiki/Futures_and_promises)  - 未来可用的结果的表示，除非有错误. 就像现实一样，承诺有时会被打破.
- [Shotgun surgery](https://en.wikipedia.org/wiki/Shotgun_surgery) - 一种编程反模式，在一次更改中，您可以在代码库中的任何位置疯狂地添加代码.

## Functions

- [fold](https://en.wikipedia.org/wiki/Fold_(higher-order_function)) - 就像折叠毯子一样，此函数迭代一个集合，并在每个步骤中将当前项目与已折叠的所有内容组合起来.
- [trampoline](https://clojuredocs.org/clojure.core/trampoline)  - 连续运行本身返回函数的函数. 就像一个在蹦床上_返回_并弹回来的孩子. 
- [zip](https://hackage.haskell.org/package/base-4.12.0.0/docs/Prelude.html#v:zip) - 将两个列表合并为一个对列表，就像拉链的互锁齿一样.

## IT Security

- [Backdoor](https://en.wikipedia.org/wiki/Backdoor_(computing)) - 一种绕过计算机系统中正常身份验证的方法.
- [Computer virus](https://en.wikipedia.org/wiki/Computer_virus) - 一种计算机程序，通过类似于生物病毒的行为“感染”其他计算机程序来进行自我复制.
- [Cyber hygiene](https://digitalguardian.com/blog/what-cyber-hygiene-definition-cyber-hygiene-benefits-best-practices-and-more) - 用户为维护系统健康和提高在线安全而应采取的步骤和做法.
- [Honeypot](https://en.wikipedia.org/wiki/Honeypot_(computing)) - 系统的一部分，看起来像是一个有吸引力的目标，但实际上有助于检测和转移攻击者.
- [Phoning home](https://en.wikipedia.org/wiki/Phoning_home)  - 当系统（例如被盗的计算机）秘密向当前所有者以外的第三方报告时. 这个名字参考了电影《ET》
- [Sandbox](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) - 一个安全且隔离的环境，用于测试可能包含恶意代码的未经验证的程序.
- [Trojan horse](https://en.wikipedia.org/wiki/Trojan_horse_(computing) ) - 误导用户其真实意图的恶意软件. 该术语源自古希腊欺骗性特洛伊木马的故事. 

## Libraries and Frameworks

- [clooney](https://github.com/GoogleChromeLabs/clooney)  - 一个 JavaScript 库，实现并发计算的参与者模型. 这个词指的是乔治克鲁尼，他也是一名演员.
- [Puppeteer](https://github.com/puppeteer/puppeteer)  - 浏览器自动化库. 如果浏览器是木偶，那么这就是木偶操纵者.
- [Uglify](https://github.com/mishoo/UglifyJS)  - JavaScript 缩小器. 删除所有使代码可读且美观的内容，以使其更小.
- [uppy](https://github.com/transloadit/uppy)  - 一个以狗为主题的上传器组件. 该名称是_upload_ 和_puppy_ 的混合. 它甚至还附带了一个名为_Golden Retriever_ 的崩溃恢复插件.

## Machine Learning

- [Confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix) - 分类器“混乱”的表格摘要，即它认为做出正确预测但实际上没有做出正确预测的频率.
- [Decision boundary](https://en.wikipedia.org/wiki/Decision_boundary)  - 划分可能数据点空间的边界. 在这里你决定，这一侧的所有内容都是垃圾邮件，那一侧的所有内容都不是.
- [Training](https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets) - 向机器展示一堆示例，直到它从中了解我们想要什么的过程.

## Programming Languages

- [Clojure](https://clojure.org/) - 一种函数式语言，广泛使用**闭包**，但带有 **j**，因为它运行在 Java 虚拟机上.
- [C++](https://en.wikipedia.org/wiki/C%2B%2B#External_links)  - 尽管 C 确实是一个坏名字，但 C++ 却相当聪明. 标志性的增量运算符******表示**C++**是后继者.

## User Interface Design

- [Breadcrumb](https://en.wikipedia.org/wiki/Breadcrumb_(navigation) ) - 导航帮助允许用户跟踪他们在程序、文档或网站中的位置. 该术语参考了童话故事《汉塞尔和格蕾特》.
- [Carousel](https://www.nngroup.com/articles/designing-effective-carousels/) - 一种循环播放的动画幻灯片.
- [Clipboard](https://en.wikipedia.org/wiki/Clipboard_(computing)) - 您临时放置正在使用的_文件_的位置（即复制和粘贴缓冲区）.
- [Desktop](https://en.wikipedia.org/wiki/Desktop_metaphor) - 用户办公桌的隐喻顶部，上面可以放置诸如文档和文档文件夹之类的对象.
- [Hamburger button](https://en.wikipedia.org/wiki/Hamburger_button)  - 用于切换菜单的按钮. 相关图标类似于汉堡包.
- [Optimistic UI](https://uxplanet.org/optimistic-1000-34d9eefe4c05) - 假定昂贵操作的用户界面将成功完成，从而提高感知性能.
- [Scrolling](https://en.wikipedia.org/wiki/Scrolling) - 屏幕内容通常不太像一本具有离散页面的书，而更像是一卷连续的羊皮纸，即卷轴.

## Theoretical Computer Science

- [Busy Beaver](https://en.wikipedia.org/wiki/Busy_beaver) - 图灵机产生的数字非常大，没有其他算法可以跟上它们.
- [Clique problem](https://en.wikipedia.org/wiki/Clique_problem)  - 在具有友谊关系的人的网络中找到一群共同的朋友的问题. 或者更一般地说，找到完整的子图.
- [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) - 游戏世界展示了如何从非常简单的成分中产生惊人的复杂性.
- [Oracle](https://en.wikipedia.org/wiki/Oracle_machine) - 一个黑匣子，甚至可以神奇地给出诸如停止问题之类的不可判定问题的答案. 
- [Pumping lemma](https://en.wikipedia.org/wiki/Pumping_lemma) - 事实上，在某些形式语言中，任何足够长的字符串都可以通过重复其子字符串进行“泵送”，并且结果保持在相同的形式语言中.

## Tools

- [tldr](https://tldr.sh/) - 带有实际示例的简化手册页.
- [yarn](https://yarnpkg.com/) - NodeJS 依赖管理器.

## Other

- [a11y, i18n, k8s, ...](https://en.wikipedia.org/wiki/Numeronym) - 通过保留第一个和最后一个字母来缩写长单词，并在中间写下省略的字母的数量. 
- [ACID vs. BASE](https://www.johndcook.com/blog/2009/07/06/brewer-cap-theorem-base/)  - 描述竞争数据库意识形态的首字母缩略词（又名 SQL 与 NoSQL）. 请注意，酸和碱在化学中也是相反的.
- [Bottleneck](https://en.wikipedia.org/wiki/Bottleneck#Computing) - A central part of a network/application that significantly limits throughput/performance and should ideally be eliminated.
- [Brick](https://en.m.wikipedia.org/wiki/Brick_(electronics)) - 当您的设备严重损坏时，它实际上会变成一块砖.
- [camelCase, snake_case, kebab-case](https://en.wikipedia.org/wiki/Letter_case#Use_within_programming_languages) - 不同的外壳样式，名称说明其外观.
- [Easter egg](https://en.wikipedia.org/wiki/Easter_egg_(media)) - 一个隐藏功能，特别是在与寻找复活节彩蛋有关的视频游戏中.
- [Floating point number](https://floating-point-gui.de/formats/fp/) - 通过让小数点_float_而不是固定在适当的位置，这种表示可以用有限数量的数字对不同大小的数字进行编码.
- [Framework](https://en.wikipedia.org/wiki/Software_framework) - 在软件架构中（就像在实际架构中一样），框架提供了基础结构，以指导和限制进一步的开发.
- [Garbage Collector](https://en.m.wikipedia.org/wiki/Garbage_collection_(computer_science)) - 程序的一部分，尝试查找并回收不再使用的垃圾内存块.
- [Glue Code](https://en.wikipedia.org/wiki/Glue_code) - Jenga 和乐高积木不共享相同的界面，但您始终可以将它们粘在一起.
- [Heisenbug](https://en.wikipedia.org/wiki/Heisenbug)  - 当人们试图研究它时，它似乎会消失或改变. 这是维尔纳·海森堡的双关语，他发现观察量子系统的行为不可避免地会改变它们的状态.
- [Lazy evaluation](https://en.wikipedia.org/wiki/Lazy_evaluation) - 一种评估策略，暂停评估直到绝对必要，然后不再进行.
- [Magic](https://en.wikipedia.org/wiki/Magic_(programming) ） - 一个神奇的程序/代码正在完成它的工作，但没有人知道如何做到. 就像现实一样，魔法实际上并不存在. 一旦你理解了它，它就不再是魔法了.
- [Process starvation](https://en.wikipedia.org/wiki/Starvation_(computer_science)) - 进程永远无法获得完成其工作的资源的问题.
- [Time travel debugging](https://en.wikipedia.org/wiki/Time_travel_debugging) - 通过源代码回顾过去，了解执行情况，有时甚至改变历史.
- [Tree shaking](https://en.wikipedia.org/wiki/Tree_shaking) - 摇动依赖树，直到所有死亡部分都脱落，最终得到一棵漂亮的瘦树.
- [Unfair enumeration](https://www.youtube.com/watch?v=CvLsVfq6cks&t=835s) - 输出所有偶数然后输出所有奇数的程序会生成不公平的自然数枚举，因为某些数字永远不会达到. 
- [Yoda condition](https://eslint.org/docs/latest/rules/yoda) - 当你写 `if (&quot;red&quot; === color) {` 而不是 `if (color === &quot;red&quot;) {` 时，因为它读作“如果红色等于颜色”，类似于星球大战人物尤达讲话.
