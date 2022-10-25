<div class="github-widget" data-repo="GustavBertram/awesome-common-lisp-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Common Lisp Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="https://raw.githubusercontent.com/GustavBertram/awesome-common-lisp-learning/master/LISP_logo_mid.png">
</div>

此列表侧重于学习 Common Lisp 的资源，尤其是我发现有用的资源.

还有其他 Awesome Common Lisp 列表专注于其他主题：
- [Libraries](https://github.com/CodyReichert/awesome-cl)
  - [Curated Libraries](https://github.com/vindarel/curated-awesome-cl) - 从上面的列表中分叉和更新.
- [Software](https://github.com/azzamsa/awesome-cl-software)

欢迎投稿. 请阅读 [contribution guidelines](https://github.com/GustavBertram/awesome-common-lisp-learning/blob/master/contributing.md) 详情.



## How To Use
1. 获取 Lisp 环境.
2. 收藏 [The Common Lisp Hyperspec](http://www.lispworks.com/documentation/common-lisp.html).
 3. 下载并阅读适当级别的 Lisp 书籍. 键入示例并使用代码. 随意切换书籍并尝试不同的书籍.
4. 试用 [Exercism](http://exercism.io/languages/common-lisp/about).
5. 如果你遇到困难，找一个在线社区，然后 [ask smart questions](http://www.catb.org/esr/faqs/smart-questions.html).
6. 了解 [Quicklisp](https://www.quicklisp.org/beta/).
7. 在某个时候，阅读你的 Lisp 实现手册.

## Lisp Environments
您可以直接运行 Lisp 实现，但编辑环境使体验更容易.
- 预打包的环境
  - [Portacle](https://shinmera.github.io/portacle/)  - 一个可移植的多平台 Common Lisp 环境. 它附带了一个带有 SLIME、SBCL（一种流行的 Common Lisp 实现）、Quicklisp 和 Git 的稍微定制的 Emacs. 无需安装，因此这是一种非常快速和简单的方式.
  - [Lispbox](https://common-lisp.net/project/lispbox/)  - 一个 IDE (Emacs + SLIME)、Common Lisp 实现 (Clozure Common Lisp) 和库管理器 (Quicklisp)，预打包为 Windows、macOS 和 Linux 的存档.  “Lisp in a Box”的后裔 [mentioned](http://www.gigamonkeys.com/book/lather-rinse-repeat-a-tour-of-the-repl.html) 在实用的通用 Lisp 中.
  - [Lispworks Personal Edition](http://www.lispworks.com/downloads/) - 用于 LispWorks Lisp 的非基于 Emacs 的 IDE，但有一些限制.
  - [Allegro Common Lisp](https://franz.com/products/allegrocl/) - 有一个免费 [Express Edition](https://franz.com/downloads/clp/survey) IDE，以及 [training videos on YouTube](https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw).
- 对于高级用户
  - [Articulate Common Lisp](http://articulate-lisp.com) - 用于组合 Lisp 环境的 HOWTO，并包含有关 [useful libraries](http://articulate-lisp.com/project/abcs.html) 以及如何 [structure projects](http://articulate-lisp.com/project/new-project.html).
  - 如果你是有经验 [Emacs](https://www.gnu.org/software/emacs/) 用户，你可以安装 [SLIME](https://common-lisp.net/project/slime/) 和一个 [supported Common Lisp implementation](https://common-lisp.net/project/slime/doc/html/Platforms.html#Platforms) . 见 [SLIME manual](https://common-lisp.net/project/slime/doc/html/) 更多细节.
  - Common Lisp Cookbook 有更多关于 [installing an implementation](https://lispcookbook.github.io/cl-cookbook/getting-started.html) 使用实施管理器，例如 [Roswell](https://github.com/roswell/roswell/wiki)，或在 Docker 上.

## Online References
- [The Common Lisp Hyperspec (CLHS)](http://www.lispworks.com/documentation/common-lisp.html)  - *The* Common Lisp 的语言参考文档. 立即加入书签.
  - [Chapter 7](http://www.lispworks.com/documentation/HyperSpec/Body/07_.htm) - 涵盖通用 Lisp 对象系统 (CLOS).
- [The ANSI Common Lisp Standard Draft](http://cberr.us/tech_writings/notes/common_lisp_standard_draft.html) - ANSI INCITS 226-1994（以前的 ANSI X3.226-1994）标准的最新草案版本.
  - 草案是免费的，标准不是.
  - 它与官方标准几乎相同，有些人更喜欢它而不是 CLHS.
- [The Common Lisp Cookbook](http://lispcookbook.github.io/cl-cookbook/)  - 有用的 Lisp 食谱列表. 还包含 CL 信息的其他在线资源列表.
- [Common Lisp the Language (2nd Edition) by Guy L. Steele](https://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html)  - 对 ANSI 标准化之前的 Common Lisp 语言的描述. 不要将其用作参考.
  - [Cliki on CLtL2](https://cliki.net/Getting+Started) - 声称它有更有用的描述 [LOOP](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node235.html#SECTION003000000000000000000) 和 [FORMAT](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node200.html) 比 CLHS 做的还要好.
  - [Stack Overflow on CLtL2](https://stackoverflow.com/questions/108537/what-are-the-main-differences-between-cltl2-and-ansi-cl) - 有些人建议使用 CLtL2 来获得洞察力和灵感，但在编程时使用 CLHS.
  - [A list of differences between CLtL2 and the ANSI Common Lisp specification.](http://linuxfinances.info/info/commonlisp.html#AEN9679)
  - [Chapter 28](https://www.cs.cmu.edu/Groups/AI/html/cltl/clm/node260.html#SECTION003200000000000000000) - 涵盖了 Common Lisp 对象系统.

## Online Books
这些可以在线免费访问的书籍，大致按从基础到高级的顺序排列：
- [Common Lisp: A Gentle Introduction to Symbolic Computation by David S. Touretzky](http://www.cs.cmu.edu/~dst/LispBook/)  - 对编程新手的一个很好的介绍. 包含真正有用的实用程序的代码，例如 [DTRACE](http://www.cs.cmu.edu/~dst/Lisp/dtrace/) 和 [SDRAW](http://www.cs.cmu.edu/~dst/Lisp/sdraw/).
- [Common Lisp: An interactive approach by Stuart C. Shapiro](https://www.cse.buffalo.edu/~shapiro/Commonlisp/) - 主要通过练习来教授的教科书.
- [Practical Common Lisp by Peter Seibel](http://www.gigamonkeys.com/book/) - 对有经验的程序员的精彩介绍，并试图从一开始就强调 CL 与其他语言的不同之处.
- [Common Lisp Koans](https://github.com/google/lisp-koans) - 不完全是一本书，而是一组帮助您学习语言的公案.
- [On Lisp by Paul Graham](http://www.paulgraham.com/onlisp.html) - 一本适合中级经验的 Lispers 的好书.
- [Let Over Lambda by Doug Hoyte](https://letoverlambda.com) - 关于 Lisp 宏的高级书籍.
  - 前六章可在​​线获取.
  - [Comments on Let Over Lambda](https://www.reddit.com/r/lisp/comments/3actsc/let_over_lambda/) - 有几个人建议你在阅读本书之前先熟悉 On Lisp，而且开始速度很慢.
  - [The chapter on closures](https://letoverlambda.com/index.cl/guest/chap2.html) - 有几个不平凡的例子，并展示了这个功能的力量.
- [Paradigms of Artificial Intelligence Programming by Peter Norvig](https://github.com/norvig/paip-lisp) - 有许多有趣的 Lisp 应用，但不再是 AI 的良好参考.

## Offline Books
这些是您必须购买或从图书馆借来的书.
- [Land of Lisp by Conrad Barski, MD](http://landoflisp.com) - 一个有趣的 Lisp 介绍，它使用漫画并让您编写游戏.
  - 可作为 [ebook](https://www.nostarch.com/lisp.htm). 
  - 一些 LOOP 宏写成 `for x for y...`，您可以将其更改为 `for x from 0 for y...` 以使它们在 SBCL 中工作.
  - 有一个 [errata page](http://landoflisp.com/errata.html).
  - 这本书的大部分内容都很有趣且相当简单，但从第 18 章开始就变得毛茸茸.感觉后面的章节介绍的不多，所以我建议在那时换一本不同的书.
  - The Web server example in Ch 13, 19 and 20 will only work on CLISP, and needs the addition of HTTP response headers to render the HTML properly.
- [ANSI Common Lisp by Paul Graham](http://www.paulgraham.com/acl.html) - 很好的参考，涵盖了 CLOS，并有几个示例程序实现.
  - 明文版本 [Chapter 1](http://lib.store.yahoo.net/lib/paulgraham/acl1.txt) 和 [Chapter 2](http://lib.store.yahoo.net/lib/paulgraham/acl2.txt) 可在线获取.
- [Common Lisp Recipes by Edmund Weitz](http://weitz.de/cl-recipes/) - 一组很棒的 Common Lisp 模式.
- [Object-Oriented Programming in Common Lisp by Sonya E. Keene](https://www.amazon.com/Object-Oriented-Programming-COMMON-LISP-Programmers/dp/0201175894) - 对 CLOS 的深入描述，并展示了如何将其与示例应用程序一起使用.
- [The Art of the Metaobject Protocol by Gregor Kiczales, Jim des Rivieres, and Daniel G. Bobrow](https://www.amazon.com/Art-Metaobject-Protocol-Gregor-Kiczales/dp/0262610744/) - 描述 CLOS 元对象协议 (MOP).
  - [Chapters 5 and 6 (available online)](http://metamodular.com/CLOS-MOP/) - Robert Strandh 对 CLOS 的元对象协议扩展的规范.
    - 由 [modern public domain CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) 让-菲利普·帕拉迪斯 (Jean-Philippe Paradis)[Hexstream](https://github.com/Hexstream)).
  - [Adam Tornhill on AMOP](http://www.adamtornhill.com/reviews/amop.htm) - 推荐阅读 Practical Common Lisp，然后是 Common Lisp 中的面向对象编程，然后是 AMOP.

## Online Community
- 这 [Cliki](http://cliki.net) - 这 Common Lisp Wiki. A great resource for all things CL. Has a great [Getting Started](http://cliki.net/Getting+Started) 页面和广泛的列表 [Lisp books](http://cliki.net/Lisp%20books).
- The #clschool, #lisp, #ccl, #sbcl and [other rooms](https://www.cliki.net/IRC) 在 [Libera.Chat](https://libera.chat/)  network 是学习 Common Lisp 的好地方.  ([Freenode should be avoided.](https://gist.github.com/joepie91/df80d8d36cd9d1bde46ba018af497409))
- [Lisp Subreddit](http://www.reddit.com/r/lisp/) - 一个活跃的社区，在侧边栏中有大量有用的链接和参考文档.
  - [Common Lisp Subreddit](https://www.reddit.com/r/Common_Lisp) - Common Lisp 的 Subreddit.
- [Exercism's Common Lisp track](http://exercism.io/languages/common-lisp/about) - 通过实践学习语言、审查代码以及与其他人讨论解决方案的绝佳方式.
- [Lisp Discord server](https://discord.gg/7tSq5EaA6Z)  - 是 Lisp 的不和谐. 有一个专用于 Common Lisp 的频道，并且很乐意回答问题.


## Library Management
这些不是库，但可以帮助您查找和安装其他库.
- [Quicklisp](https://www.quicklisp.org/beta) - Lisp 库的包管理平台.
- [Quickdocs](http://quickdocs.org) - Quicklisp 中的项目文档.
- [State of the Common Lisp Ecosystem, 2015](http://borretti.me/article/common-lisp-sotu-2015) - 关于您应该使用哪些库以及为什么使用的文章.
- [Articulate Common Lisp](http://articulate-lisp.com/project/abcs.html) - 列出一些有用的库.


## Common Lisp Implementations
本节按字母顺序列出了一些常见的 CL 实现及其手册. 除非另有说明，否则这些都是免费软件实现. 另请参阅 Cliki 的列表 [free software Common Lisp Implementations](https://www.cliki.net/Common%20Lisp%20implementation).
- [Allegro Common Lisp (ACL)](https://franz.com/products/allegrocl/) - 商业，但有免费 [Express Edition](https://franz.com/downloads/clp/survey).
  - [ACL manual](https://franz.com/support/documentation/)
  - [Training videos on YouTube](https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw)
- [CLISP](https://clisp.sourceforge.io)
  - [CLISP Manual](https://clisp.sourceforge.io/impnotes.html)
- [Clozure Common Lisp (CCL)](https://ccl.clozure.com)
  - [CCL manual](https://ccl.clozure.com/manual/)
- [Carnegie Mellon University Common Lisp (CMUCL)](https://www.cons.org/cmucl/)
  - [CMUCL manual and other useful information](https://www.cons.org/cmucl/doc/index.html)
- [Embeddable Common Lisp (ECL)](https://common-lisp.net/project/ecl/)
  - [ECL manual](https://common-lisp.net/project/ecl/static/manual/)
- [LispWorks](http://www.lispworks.com/products/index.html) - 商业，但如前所述，具有 [Personal Edition](http://www.lispworks.com/downloads/index.html) 有轻微的限制.
  - [LispWorks manual](http://www.lispworks.com/documentation/index.html)
- [Steel Bank Common Lisp (SBCL)](http://www.sbcl.org) - 我个人的最爱.
  - [SBCL manual](http://www.sbcl.org/manual/index.html)
- [Scieneer Common Lisp (SCL)](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/) - 商业 Linux 和 Unix 实现，但具有不受限制的免费评估和非商业使用版本.
  - [SCL manual](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/doc/)

## Credit
我从那里得到了很多信息 [Rainer Joswig's Stack Overflow answer on learning Common Lisp](https://stackoverflow.com/a/7224914/1005039) ，以及来自现已失效的 Stack Overflow Documents 站点. 这 [Cliki's Getting Started](https://cliki.net/Getting%20Started) 页面也非常宝贵.
