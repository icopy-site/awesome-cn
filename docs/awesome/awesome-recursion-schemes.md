<div class="github-widget" data-repo="passy/awesome-recursion-schemes"></div>
## Awesome Recursion Schemes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 用于学习和使用递归方案的有用资源的精选.

递归方案是简单的、可组合的组合器，可自动执行遍历和递归嵌套数据结构的过程.





## Introductions

- [Awesome Recursion Schemes](https://github.com/passy/awesome-recursion-schemes) - 用于学习和使用递归方案的有用资源的精选.
- [Practical Recursion Schemes](https://jtobin.io/practical-recursion-schemes) -
  模式函子、固定点、变形、变形的介绍，
  paramorphisms 和 hylomorphisms，需要很少的先验知识.
- [An Introduction to Recursion Schemes](http://blog.sumtypeofway.com/an-introduction-to-recursion-schemes/) -
  由三部分组成的系列，您可以在其中从头开始发现递归方案并
  实现 Edward Kmett 库的一小部分.
- [Understanding Algebras](https://www.schoolofhaskell.com/user/bartosz/understanding-algebras) -
  Bartosz Milewski 解释了 F 代数并展示了如何在
  变形.
- [Recursion Schemes in JavaScript and Flow](https://medium.com/@JosephJnk/recursion-schemes-in-javascript-and-flow-with-static-land-recursision-schemes-97cf10599fb7) -
  介绍JavaScript中递归方案和相关概念的系列，
  针对具有最少函数式编程背景的开发人员.

## Articles

- [Recursion Schemes: A Field Guide (Redux)](http://comonad.com/reader/2009/recursion-schemes/) -
  带有代码示例的各种递归方案列表.
- [Catamorphisms](https://wiki.haskell.org/Catamorphisms) - Haskell Wiki 上的定义.
- [Catamorphisms](https://www.schoolofhaskell.com/user/edwardk/recursion-schemes/catamorphisms) -
  爱德华·科梅特 (Edward Kmett) 的 Haskell 学院代码简短定义.
- [Rotating Squares](https://jtobin.io/rotating-squares) - Jared Tobin 使用同态旋转四叉树.
- [Recursion Schemes, Part V: Hello, Hylomorphisms](http://blog.sumtypeofway.com/recursion-schemes-part-v/)
- [Promorphisms, Pre and Post](https://jtobin.io/promorphisms-pre-post) - Jared Tobin 的前态和后态的实际例子.
- [Time Traveling Recursion Schemes](https://jtobin.io/time-traveling-recursion) - 通过 Jared Tobin 的例子探索 histo 和 futu.
- [Recursion Schemes, Part IV: Time is of the Essence](http://blog.sumtypeofway.com/recursion-schemes-part-iv-time-is-of-the-essence/) - 关于组织态和未来态的实用文章.
- [Cheat Sheet](https://github.com/sellout/recursion-scheme-talk/blob/master/cheat%20sheet.pdf) - 各种递归方案及其对偶的映射.
- [Correcting the Visitor pattern](http://logji.blogspot.co.uk/2012/02/correcting-visitor-pattern.html) - 表明访问者模式实现了一个 f 代数以用于变形（在 Java 中）.
- [Recursion Schemes in Scala](https://free.cofree.io/2017/11/13/recursion/) - 介绍定点组合器、变形、变态、同态、同态、同态、组织态、动态态和未来态.
- [What's in a Fold: The Basic Catamorphism in recursion-schemes](https://duplode.github.io/posts/whats-in-a-fold.html) - 引入变形作为折叠的概括.

### Hylomorphisms in the Wild

Bartosz Milewski 撰写的关于通过应用质态来解决小的实际问题的文章.

- [Stalking a Hylomorphism in the Wild](https://bartoszmilewski.com/2017/12/29/stalking-a-hylomorphism-in-the-wild/) - Advent of Code 2017，多米诺骨牌挑战
- [Open Seasons on Hylomorphisms](https://bartoszmilewski.com/2018/12/20/open-season-on-hylomorphisms/) - Code 2018 的到来，字符串比较挑战

## Papers

- [Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire, 1991, Meijer et al.](http://maartenfokkinga.github.io/utwente/mmf91m.pdf) -
  本文大部分基于原始论文.
- [A Duality of Sorts, 2013, Hinze et al.](http://www.cs.ox.ac.uk/ralf.hinze/publications/Sorting.pdf) -
  表明许多基本排序算法成对存在，并且这些对
  自然地从折叠和展开之间的二元性中产生.
- [Sorting with Bialgebras and Distributive Laws, 2012, Hinze et al.](http://www.cs.ox.ac.uk/people/daniel.james/sorting/sorting.pdf) -
  展示了如何使用同态和同态来提高效率
  排序算法的实现.
- [Scrap your boilerplate: a practical design pattern for generic programming, 2003, SPJ et al.](http://research.microsoft.com/en-us/um/people/simonpj/Papers/hmap/hmap.ps) -
  用于编写遍历由丰富的相互递归数据类型构建的数据结构的程序的设计模式.

## Presentations

- [Slidedecks by Tim Philip Williams](http://www.timphilipwilliams.com/slides.html) -
  “Recursion Schemes by Example”和“Exotic Trades 的Exotic Tools”提供
  简洁的定义以及许多递归方案的实际例子.
- [Unifying Structured Recursion Schemes](https://www.youtube.com/watch?v=9EGYSb9vov8) -
  Ralf Hinze、Nicolas Wu 和 Jeremy Gibbons 的 12 分钟演讲.
- [Recursion Schemes](https://www.youtube.com/watch?v=Zw9KeP3OzpU) -
  由 Tim Williams 在伦敦 Haskell 聚会上介绍.
- [F-algebras or: How I Learned to Stop Worrying and Love the Type System](https://www.youtube.com/watch?v=PK4SOaAGVfg) -
  由纽约 Haskell 用户组的 Anthony Burzillo 介绍.
- [A Gentle Introduction to Recursion Schemes](https://www.youtube.com/watch?v=i5A2Amfcir8) -
  由 Jean Remi Desjardins 在 Lambdaconf 2016 上展示.
- [recursion-scheme-talk](https://github.com/sellout/recursion-scheme-talk) - 关于递归方案的幻灯片集.
- [Bracer: Transforming Real-World Languages with Coproducts and Recursion Schemes](https://www.youtube.com/watch?v=5Kr7IykGMzU) - 帕特里克·汤姆森 (Patrick Thomson) 关于使用联积和递归方案构建程序的高级讨论.
- [Recursion: Where Functional Programming Hits Bottom](https://www.youtube.com/watch?v=24UoRaoKLjM) - Greg Pfeil 介绍 Haskell 和 Scala 中的递归固定点数据结构和递归方案.
- [Programming with algebras](https://www.youtube.com/watch?v=-98fR9VmLbQ) - Bartosz Milewski 在 LambdaCon 上发表的谈话形式的文章.
- [Peeling the Banana: Recursion Schemes from First Principles](https://www.youtube.com/watch?v=XZ9nPZbaYfE&t=3s) - Zainab Ali 在 LambdaWorld 上的介绍性演讲.

## Cheat Sheets

- [The Hitchhiker's Guide to Morphisms](https://ipfs.io/ipfs/QmTppu1VDAQWsdiyVSZX6qb8PErdpwzNP2oKfEhcgaBvWR/guide-to-morphisms.pdf) - 不同态射的概述，包括可打印的 PDF.

## Podcasts

- [Magic Read Along](http://www.magicreadalong.com/) - 随意讨论
  经常提出递归方案的类别理论，包括[情节
  33](http://www.magicreadalong.com/episode/33) 谈论 Histomorphisms
  和未来态.
- [Scala Love](https://scala.love/) - 关于 Scala 的播客
  中的递归方案 [the second episode](https://scala.love/happy-valentin/).
- [The Haskell Cast](https://www.haskellcast.com/) - 递归方案出现
  [Episode 13 with John Wiegley](https://www.haskellcast.com/episode/013-john-wiegley-on-categories-and-compilers).

## Implementations

- [recursion-schemes](https://github.com/ekmett/recursion-schemes/) 为了
  Haskell - Edward Kmett 的规范实现.
- [Matryoshka](https://github.com/slamdata/matryoshka) 对于使用 Scalaz 的 Scala -
  定点数据结构的广义折叠、展开和遍历.
- [andyscott/droste](https://github.com/andyscott/droste) 对于使用猫的 Scala -
  定点数据结构的广义折叠、展开和遍历.
- [recursion\_schemes](https://github.com/vmchale/recursion_schemes/) 为了
  Idris，基于 Edward Kmett 的 Haskell 库.
- [purescript-matryoshka](https://github.com/slamdata/purescript-matryoshka) 对于 PureScript -
  俄罗斯套娃的半成品港口.
- [recursion](https://github.com/vmchale/recursion) 对于 ATS - 演示
  ATS 中的递归方案.
- [dada](https://github.com/sellout/dada) for Dhall - 递归库
  盲目计划.
- [static-land-recursion-schemes](https://github.com/JosephJNK/static-land-recursion-schemes) 对于 JavaScript/Flow -
  以以下风格编写的数据结构方案 [flow-static-land](https://github.com/gcanti/flow-static-land).
- [Katalyst](https://github.com/aedans/Katalyst) 对于 Kotlin - 基于 Matryoshka 使用轻量级高级多态性的重新构想.

## License

此内容已获得许可
under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
