<div class="github-widget" data-repo="GustavBertram/awesome-common-lisp-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Common Lisp Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="https://raw.githubusercontent.com/GustavBertram/awesome-common-lisp-learning/master/LISP_logo_mid.png">
</div>

该列表重点介绍了学习Common Lisp的资源，特别是我发现有用的资源.

还有其他一些令人敬畏的Common Lisp列表，它们专注于其他主题：
- [Libraries](https://github.com/CodyReichert/awesome-cl)
  - [Curated Libraries](https://github.com/vindarel/curated-awesome-cl) -从以上列表中进行了分叉和更新.
- [Software](https://github.com/azzamsa/awesome-cl-software)

欢迎捐款. 请阅读 [contribution guidelines](https://github.com/GustavBertram/awesome-common-lisp-learning/blob/master/contributing.md) 有关详细信息.



## How To Use
1.获得一个Lisp环境.
2.将 [The Common Lisp Hyperspec](http://www.lispworks.com/documentation/common-lisp.html).
 3.下载并阅读适当级别的Lisp书籍. 输入示例并使用代码. 随意切换书籍并尝试其他书籍.
4.尝试一下 [Exercism](http://exercism.io/languages/common-lisp/about).
5.如果遇到困难，请找到一个在线社区，然后 [ask smart questions](http://www.catb.org/esr/faqs/smart-questions.html).
6.了解 [Quicklisp](https://www.quicklisp.org/beta/).
7.在某些时候，请阅读Lisp实施手册.

## Lisp Environments
您可以直接运行Lisp实现，但是编辑环境使体验更轻松.
-预包装环境
  - [Portacle](https://shinmera.github.io/portacle/)  -便携式多平台Common Lisp环境. 它带有SLIME，SBCL（流行的Common Lisp实现），Quicklisp和Git，提供了稍微定制的Emacs. 无需安装，因此这是一种非常快速简便的方法.
  - [Lispbox](https://common-lisp.net/project/lispbox/)  -一个IDE（Emacs + SLIME），Common Lisp实现（Clozure Common Lisp）和库管理器（Quicklisp），它们预先打包为Windows，macOS和Linux的归档文件.  “盒中的Lisp”的后代 [mentioned](http://www.gigamonkeys.com/book/lather-rinse-repeat-a-tour-of-the-repl.html) in Practical Common Lisp.
  - [Lispworks Personal Edition](http://www.lispworks.com/downloads/) -用于LispWorks Lisp的非基于Emacs的IDE，但有一些限制.
  - [Allegro Common Lisp](https://franz.com/products/allegrocl/) -有免费 [Express Edition](https://franz.com/downloads/clp/survey) IDE，以及 [training videos on YouTube](https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw).
-对于高级用户
  - [Articulate Common Lisp](http://articulate-lisp.com) -用于整合Lisp环境的HOWTO，并提供有关以下内容的信息： [useful libraries](http://articulate-lisp.com/project/abcs.html) 以及如何 [structure projects](http://articulate-lisp.com/project/new-project.html).
  -如果您是经验丰富的人 [Emacs](https://www.gnu.org/software/emacs/) 用户，您只需安装 [SLIME](https://common-lisp.net/project/slime/) 和一个 [supported Common Lisp implementation](https://common-lisp.net/project/slime/doc/html/Platforms.html#Platforms) . 见 [SLIME manual](https://common-lisp.net/project/slime/doc/html/) 更多细节.
  -《通用Lisp食谱》包含有关以下内容的更多信息： [installing an implementation](https://lispcookbook.github.io/cl-cookbook/getting-started.html) 使用像这样的实现管理器 [Roswell](https://github.com/roswell/roswell/wiki)，或在Docker上.

## Online References
- [The Common Lisp Hyperspec (CLHS)](http://www.lispworks.com/documentation/common-lisp.html)  -* Common Lisp的*语言参考文档. 立即为其添加书签.
  - [Chapter 7](http://www.lispworks.com/documentation/HyperSpec/Body/07_.htm) -涵盖了通用Lisp对象系统（CLOS）.
- [The ANSI Common Lisp Standard Draft](http://cberr.us/tech_writings/notes/common_lisp_standard_draft.html) -ANSI INCITS 226-1994（以前为ANSI X3.226-1994）标准的最新草案版本.
  -草稿是免费的，标准不是.
  -与官方标准几乎相同，有些人更喜欢CLHS.
- [The Common Lisp Cookbook](http://lispcookbook.github.io/cl-cookbook/)  -有用的Lisp食谱列表. 还包含其他在线CL信息来源的列表.
- [Common Lisp the Language (2nd Edition) by Guy L. Steele](https://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html)  -在ANSI标准化之前对Common Lisp语言的描述. 不要将其用作参考.
  - [Cliki on CLtL2](https://cliki.net/Getting+Started) -声称它具有以下更有用的描述 [LOOP](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node235.html#SECTION003000000000000000000) 和 [FORMAT](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node200.html) 比CLHS好.
  - [Stack Overflow on CLtL2](https://stackoverflow.com/questions/108537/what-are-the-main-differences-between-cltl2-and-ansi-cl) -有些人建议使用CLtL2以获得见识和启发，但在编程时要使用CLHS.
  - [A list of differences between CLtL2 and the ANSI Common Lisp specification.](http://linuxfinances.info/info/commonlisp.html#AEN9679)
  - [Chapter 28](https://www.cs.cmu.edu/Groups/AI/html/cltl/clm/node260.html#SECTION003200000000000000000) -涵盖Common Lisp对象系统.

## Online Books
这些可在线免费访问的书籍，其排列顺序从基本到高级：
- [Common Lisp: A Gentle Introduction to Symbolic Computation by David S. Touretzky](http://www.cs.cmu.edu/~dst/LispBook/)  -对编程新手的不错的介绍. 包含一些实用工具的代码，例如 [DTRACE](http://www.cs.cmu.edu/~dst/Lisp/dtrace/) 和 [SDRAW](http://www.cs.cmu.edu/~dst/Lisp/sdraw/).
- [Common Lisp: An interactive approach by Stuart C. Shapiro](https://www.cse.buffalo.edu/~shapiro/Commonlisp/) -一本主要通过练习进行教学的教科书.
- [Practical Common Lisp by Peter Seibel](http://www.gigamonkeys.com/book/) -对经验丰富的程序员的精彩介绍，并从一开始就着重强调使CL与其他语言不同的原因.
- [Common Lisp Koans](https://github.com/google/lisp-koans) -并非完全是一本书，而是一系列的koans可以帮助您学习该语言.
- [On Lisp by Paul Graham](http://www.paulgraham.com/onlisp.html) -一本适合有经验的Lispers的好书.
- [Let Over Lambda by Doug Hoyte](https://letoverlambda.com) -有关Lisp宏的高级书籍.
  -前六章可在​​线获得.
  - [Comments on Let Over Lambda](https://www.reddit.com/r/lisp/comments/3actsc/let_over_lambda/) -有些人建议您在阅读本书之前先熟悉On Lisp，并且开始缓慢.
  - [The chapter on closures](https://letoverlambda.com/index.cl/guest/chap2.html) -有几个不平凡的示例，并演示了此功能的强大功能.
- [Paradigms of Artificial Intelligence Programming by Peter Norvig](https://github.com/norvig/paip-lisp) -具有许多Lisp有趣的应用程序，但不再是AI的良好参考.

## Offline Books
这些是您必须购买或从图书馆借来的书.
- [Land of Lisp by Conrad Barski, MD](http://landoflisp.com) -一个有趣的Lisp简介，它使用漫画并让您编写游戏.
  -可作为 [ebook](https://www.nostarch.com/lisp.htm). 
  -编写了两个LOOP宏，分别是“ for x for y ...”，您可以将其从“ 0 for y ...”更改为“ for x for y ...”，以使其在SBCL中工作.
  -有一个 [errata page](http://landoflisp.com/errata.html).
  -本书的大部分内容都很有趣并且很容易理解，但是从第18章开始却显得有些毛茸茸.以后的章节并没有太多介绍，因此我建议此时改用另一本书.
  -第13、19和20章中的Web服务器示例仅适用于CLISP，并且需要添加HTTP响应标头才能正确呈现HTML.
- [ANSI Common Lisp by Paul Graham](http://www.paulgraham.com/acl.html) -很好地作为参考，涵盖了CLOS，并提供了一些示例程序实现.
  -的纯文本版本 [Chapter 1](http://lib.store.yahoo.net/lib/paulgraham/acl1.txt) 和 [Chapter 2](http://lib.store.yahoo.net/lib/paulgraham/acl2.txt) 可以在线获得.
- [Common Lisp Recipes by Edmund Weitz](http://weitz.de/cl-recipes/) -大量的Common Lisp模式.
- [Object-Oriented Programming in Common Lisp by Sonya E. Keene](https://www.amazon.com/Object-Oriented-Programming-COMMON-LISP-Programmers/dp/0201175894) -CLOS的深入描述，并说明如何在示例应用程序中使用它.
- [The Art of the Metaobject Protocol by Gregor Kiczales, Jim des Rivieres, and Daniel G. Bobrow](https://www.amazon.com/Art-Metaobject-Protocol-Gregor-Kiczales/dp/0262610744/) -描述CLOS元对象协议（MOP）.
  - [Chapters 5 and 6 (available online)](http://metamodular.com/CLOS-MOP/) -对CLOS的元对象协议扩展的规范.
  - [Adam Tornhill on AMOP](http://www.adamtornhill.com/reviews/amop.htm) -建议先阅读实用的Lisp，然后再阅读Lisp中的面向对象编程，然后再阅读AMOP.

## Online Community
- 这 [Cliki](http://cliki.net) - 这 Common Lisp Wiki. A great resource for all things CL. Has a great [Getting Started](http://cliki.net/Getting+Started) 页面和广泛的清单 [Lisp books](http://cliki.net/Lisp%20books).
- The #clschool, #lisp, #ccl, #sbcl and [other rooms](https://www.cliki.net/IRC) 在 [Freenode IRC network](http://freenode.net) 是学习Common Lisp的好地方.
- [Lisp Subreddit](http://www.reddit.com/r/lisp/) -一个活跃的社区，并且在侧边栏中拥有大量有用的链接和参考文档.
  - [Common Lisp Subreddit](https://www.reddit.com/r/Common_Lisp) -Common Lisp的Subreddit.
- [Exercism's Common Lisp track](http://exercism.io/languages/common-lisp/about) -一种通过实践学习语言，审查代码并与其他人讨论解决方案的绝妙方法.
- [Lisp Discord server](https://discord.gg/7tSq5EaA6Z)  -是Lisp的不和. 有一个专门针对Common Lisp的频道，将很乐意回答问题.


## Library Management
这些不是库，但是可以帮助您查找和安装其他库.
- [Quicklisp](https://www.quicklisp.org/beta) -Lisp库的程序包管理平台.
- [Quickdocs](http://quickdocs.org) -Quicklisp中的项目文档.
- [State of the Common Lisp Ecosystem, 2015](http://borretti.me/article/common-lisp-sotu-2015) -有关应使用哪些库以及原因的文章.
- [Articulate Common Lisp](http://articulate-lisp.com/project/abcs.html) -列出了一些有用的库.


## Common Lisp Implementations
本节按字母顺序列出了一些常见的CL实现及其手册. 除非另有说明，否则这些都是自由软件实现. 另请参阅Cliki的清单 [free software Common Lisp Implementations](https://www.cliki.net/Common%20Lisp%20implementation).
- [Allegro Common Lisp (ACL)](https://franz.com/products/allegrocl/) -商业，但有免费 [Express Edition](https://franz.com/downloads/clp/survey).
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
- [LispWorks](http://www.lispworks.com/products/index.html) -商业广告，但如前所述，具有 [Personal Edition](http://www.lispworks.com/downloads/index.html) 有轻微的限制.
  - [LispWorks manual](http://www.lispworks.com/documentation/index.html)
- [Steel Bank Common Lisp (SBCL)](http://www.sbcl.org) -我个人的最爱.
  - [SBCL manual](http://www.sbcl.org/manual/index.html)
- [Scieneer Common Lisp (SCL)](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/) -商业Linux和Unix实现，但具有不受限制的免费评估和非商业使用版本.
  - [SCL manual](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/doc/)

## Credit
我从中获得了很多信息 [Rainer Joswig's Stack Overflow answer on learning Common Lisp](https://stackoverflow.com/a/7224914/1005039) ，以及现已停用的Stack Overflow Documents网站. 这 [Cliki's Getting Started](https://cliki.net/Getting%20Started) 页面也非常宝贵.
