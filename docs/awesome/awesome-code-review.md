<div class="github-widget" data-repo="joho/awesome-code-review"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<img src="https://raw.githubusercontent.com/joho/awesome-code-review/master/Awesome Code Review.png" alt="Awesome Code Review" />

## Awesome Code Review [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 工具、文章、书籍和任何其他相关资源的精选列表 [code review](https://en.wikipedia.org/wiki/Code_review)

代码审查是对计算机源代码的系统检查（有时称为同行审查）.



## Academic Papers

- [An experiment to assess the cost-benefits of code inspections in large scale software development (Porter, Siy, Toman & Votta, 1997)](http://laser.cs.umass.edu/courses/cs521-621.Fall10/documents/PorterSiyetal.pdf) 早期的论文测试了一系列当时流行的审查技术，包括多阶段审查和通过会议进行代码审查，发现您可以在有两名审查员的离线单次通过中获得大部分好处.
- [Anywhere, anytime code inspections: using the Web to remove inspection bottlenecks in large-scale software development (Perpich, Perry, Porter, Votta & Wade, 1997)](https://dl.acm.org/citation.cfm?id=253234) 在遥远的未来有一天，审查代码的最佳方式将是在万维网上.
- [Characteristics of Useful Code Reviews: An Empirical Study at Microsoft (Bosu, Greiler, Bird, 2015)](https://www.michaelagreiler.com/wp-content/uploads/2019/02/Characteristics-Of-Useful-Comments.pdf) 本文报告了一项大规模定性和定量研究的结果，重点是了解开发人员认为哪些代码审查评论有用.  
- [Code Reviewing in the Trenches: Understanding Challenges, Best Practices, and Tool Needs (MacLeod, Greiler, Storey, Bird, Czerwonka, 2018)](https://www.michaelagreiler.com/wp-content/uploads/2019/03/Code-Reviewing-in-the-Trenches-Understanding-Challenges-Best-Practices-and-Tool-Needs.pdf) 对 900 多名 Microsoft 开发人员进行的大规模研究，以了解他们的代码审查过程、他们进行代码审查的动机以及他们遇到的陷阱和最佳实践.
- [Design and Code Inspections to Reduce Errors in Program Development (Fagan, 2002)](https://link.springer.com/chapter/10.1007/978-3-642-59412-0_35) 使用更正式的流程，特别是为每个参与者定义角色，并在审查期间大幅增加错误检测.
- [Helping Developers Help Themselves: Automatic Decomposition of Code Review Changes (Barnett et al. 2015)](http://research.microsoft.com/pubs/238937/barnett2015hdh.pdf) ([summary on the morning paper](https://blog.acolyer.org/2015/06/26/helping-developers-help-themselves-automatic-decomposition-of-code-review-changes/)) 研究自动将大差异分成较小的差异，从而获得更好的评论.
- [Modern Code Review: A Case Study at Google](https://sback.it/publications/icse2018seip.pdf) 一项研究，展示了谷歌代码审查的工作方式.
- [Work Practices and Challenges in Pull-Based Development (Gousios et al. 2015)](https://sback.it/publications/icse2016b.pdf) ([summary on the morning paper](https://blog.acolyer.org/2015/06/23/work-practices-and-challenges-in-pull-based-development/)) 实地研究如何在野外使用 GitHub 拉取请求.

## Articles

- [8 Tips for Great Code Reviews](https://kellysutton.com/2018/10/08/8-tips-for-great-code-reviews.html) 更好的代码审查过程的一些基本规则.
- [A Better Code Review](https://www.giladpeleg.com/blog/better-code-review/) 用于代码审查的一套体面的模式和反模式.
- [A Zen Manifesto for Effective Code Reviews](https://medium.freecodecamp.org/a-zen-manifesto-for-effective-code-reviews-e30b5c95204a) 提交者和审查者进行有效代码审查的实用技巧.
- [Brian Guthrie's Feature Branching Rant](https://twitter.com/bguthrie/status/937750796334174209) Twitter 帖子讨论了 GitHub 的开源优先模型在“公司内部”代码审查实践方面的优缺点.
- [Building an Inclusive Code Review Culture](https://blog.plaid.com/building-an-inclusive-code-review-culture/) 帮助确保协作和学习文化的指南
- [Code Review: Create The Culture, Learn The Best Practices](https://codingsans.com/blog/code-review) 来自技术领导者的代码审查技巧和最佳实践.
- [Code Review Etiquette](https://css-tricks.com/code-review-etiquette/) 一些有助于积极参与代码审查的技巧.
- [Code Review Guidelines for Humans](https://phauer.com/2018/code-review-guidelines/) 提供和获得代码审查的一些指南.
- [Code Reviews: Just Do It](https://blog.codinghorror.com/code-reviews-just-do-it/) 2006 年倡导对软件进行同行评审的开创性帖子.
- [Code Reviews at Google are lightweight and fast](https://www.michaelagreiler.com/code-reviews-at-google/) 有关代码审查最佳实践和流程在 Google 中如何运作的详细信息.
- [Code Review Review is the Manager's Job](https://hecate.co/blog/code-review-review-is-the-managers-job) 为什么管理层应该确保代码审查完成并做得好.
- [Comments During Code Reviews](https://medium.com/@otarutunde/comments-during-code-reviews-2cb7791e1ac7) 在代码审查期间写出好的评论.
- [Designing Awesome Code Reviews](https://medium.com/unpacking-trunk-club/designing-awesome-code-reviews-5a0d9cd867e3) 积极设计代码审查过程的原则.
- [Effective Code Reviews Without the Pain](https://www.developer.com/tech/article.php/3579756/Effective-Code-Reviews-Without-the-Pain.htm) 2006 年关于如何有效执行代码审查的另一个经典.
- [Feedback Ladders: How We Encode Code Reviews at Netlify](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/) 有助于审阅者对特定审阅反馈的可操作性进行分类的框架.
- [How Code Reviews work at Microsoft](https://www.michaelagreiler.com/code-reviews-at-microsoft-how-to-code-review-at-a-large-software-company/) 深入分析 Microsoft 的代码审查流程.
- [How I review code](https://engineering.tumblr.com/post/170040992289/how-i-review-code) 关于如何最好地审查 Tumblr 工程师的拉取请求的更多个人建议.
- [How to do a code review](https://google.github.io/eng-practices/review/reviewer/) A thorough description of how Google engineers do code reviews, from the Google's Engineering Practices documentation.
- [How to Do Code Reviews Like a Human](https://mtlynch.io/human-code-reviews-1/) 将代码审查视为不仅是一个技术过程而且也是一个社会过程的技术.
- [Modern Code Reviews](https://rethought.se/research/modern-code-reviews/) 可以说属于学术论文，但它是一个网站，按方面/上下文概述代码审查的证据. 链接到一堆论文.
- [On Code Review](https://medium.com/@schrockn/on-code-reviews-b1c7c94d868c) 关于代码审查的工具和个人元素的简短文章，来自前 Facebook 工程师.
- [Pull Requests: How to Get and Give Good Feedback](https://kickstarter.engineering/pull-requests-how-to-get-and-give-good-feedback-f573469f0c44) 为代码审查过程的双方、审查者和被审查者提供建议.
- [Ship Small Diffs](https://blog.skyliner.io/ship-small-diffs-741308bec0d1) 为什么最好审查小的变化而不是大的变化.
- [Stacked Pull Requests: Keeping GitHub Diffs Small](https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small/) 拆分大型 PR 并提高评论参与度的分步过程.
- [The Art of Humanizing Pull Requests](https://blog.usejournal.com/the-art-of-humanizing-pull-requests-prs-b520588eb345) 通过拉取请求进行代码审查的人性化表情符号丰富指南.
- [Towards Productive Technical Discussions](https://cate.blog/2018/07/03/towards-productive-technical-discussions/) 将代码审查讨论推向更有成效的领域的战术问题和行动.
- [Unlearning Toxic Behaviors in a Code Review Culture](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c) 通过 how-not-to 拉取请求的操作指南.
- [Why I changed the way I think about Code Quality](https://medium.freecodecamp.org/why-i-changed-the-way-i-think-about-code-quality-88c5d8d57e68) 为什么代码质量不仅仅是代码.

## Books

- [Best Kept Secrets of Peer Code Review](https://www.goodreads.com/book/show/1563457.Best_Kept_Secrets_of_Peer_Code_Review)  10 篇关于代码审查实践的文章的旧汇编. 由于覆盖同一领域的不同作者，有些重复.
- [Handbook of Walkthroughs, Inspections, and Technical Reviews](https://www.amazon.com/Handbook-Walkthroughs-Inspections-Technical-Reviews/dp/0932633196) 较旧的书涵盖了更正式的演练，但很好地涵盖了政治和团体动态.
- [Peer Reviews in Software: A Practical Guide](https://www.amazon.com/Peer-Reviews-Software-Practical-Guide/dp/0201734850) 作为代码审查实践的正式代码检查的实用指南.
- [Software Inspection: An Industry Best Practice](https://www.amazon.com/Software-Inspection-Industry-Best-Practice/dp/0818673400) 关于代码审查实践的论文纲要.
- [Ultimate Guide to Code Reviews](https://www.codacy.com/ebooks/guide-to-code-reviews) Codacy 赞助的基于开发人员调查的代码审查实践电子书.
- [What to Look for in a Code Review](https://leanpub.com/whattolookforinacodereview) JetBrains 赞助了一本关于如何在审查期间发现编码反模式的电子书.

## Talks and Podcasts

- [Code Reviews: Honesty, Kindness, Inspiration: Pick Three - Jacob Stoebel RubyConf 2017](http://confreaks.tv/videos/rubyconf2017-code-reviews-honesty-kindness-inspiration-pick-three) 如何在对原作者保持友善的同时进行有效的代码审查.
- [Goldilocks and the Three Code Reviews - Vaidehi Joshi RedDot Ruby Conf 2017](https://confreaks.tv/videos/reddotrubyconf2017-goldilocks-and-the-three-code-reviews) 通过关注影响因素来找到适量的代码审查.
- [Implementing a Strong Code-Review Culture - Derek Prior Railsconf 2015](https://www.youtube.com/watch?v=PJjmw9TRB7s) 如何在团队中灌输健康的代码审查文化.
- [Michaela Greiler on Code Reviews - SE Radio 2020](https://www.se-radio.net/2020/02/episode-400-michaela-greiler-on-code-reviews/) Michaela Greiler 在 Software Engineering Radio 播客中讨论了代码审查的重要性以及如何进行审查.

## Tools

- [Crucible](https://www.atlassian.com/software/crucible) Atlassian 的本地代码审查工具.
- [Gerrit](https://www.gerritcodereview.com/) 源自 Google 的开源 git 代码审查工具.
- [GitHub](https://github.com) Git 托管和“拉取请求”的先驱.
- [Gitpod](https://gitpod.io) 在浏览器中的完整 IDE 中进行代码审查拉取请求.
- [GitRise](https://www.gitrise.com/) GitHub 拉取请求的 Slack 提醒
- [LGTM](https://lgtm.com) GitHub 和 Bitbucket 拉取请求的自动化 Git 代码审查，以查找安全漏洞和代码质量问题.
- [Phabricator](https://www.phacility.com/phabricator/) 源自 Facebook 的开源 git/mercurial/svn 代码审查工具.
- [PullRequest](https://www.pullrequest.com/) 代码审查即 GitHub 拉取请求的服务.
- [Pull Reminders](https://pullreminders.com) GitHub 拉取请求的自动 Slack 提醒和指标.
- [Reviewable](https://reviewable.io/) 基于 GitHub 拉取请求构建的代码审查工具.
- [Review Board](https://www.reviewboard.org/) 与 SCM/平台无关的开源审查工具.
- [Rubberduck](https://www.rubberduck.io) 浏览器扩展向 GitHub 拉取请求添加代码感知导航.
- [Sider](https://sider.review/) GitHub 的自动代码审查服务.
- [Softagram](https://softagram.com/) 用于拉取请求、合并请求 (GitLab) 和补丁集 (Gerrit) 的自动化代码更改可视化（和依赖项分析）.
- [SonarCloud](https://sonarcloud.io) 检测 Azure DevOps、Bitbucket 和 GitHub 存储库中的代码异味、错误和漏洞.
- [Upsource](https://www.jetbrains.com/upsource/) JetBrain 的内部部署 git/mercurial/perforce/svn 代码审查工具.
- [Viezly](https://viezly.com) 具有拉取请求可视化和更改之间增强导航的代码审查服务.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/joho/awesome-code-review/blob/master/contributing.md) 第一的.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内， [John Barton](https://johnbarton.co) 已放弃所有版权和
本作品的相关或邻接权.
