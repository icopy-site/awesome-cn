## Awesome Recursion Schemes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;用于学习和使用递归方案的有用资源的管理.

递归方案是简单的可组合组合器，它通过嵌套数据结构自动化遍历和递归过程.


## Contents

- [Introductions](#introductions)
- [Articles](#articles)
- [Papers](#papers)
- [Presentations](#presentations)
- [Podcasts](#podcasts)
- [Implementations](#implementations)


## Introductions

- [Awesome Recursion Schemes](https://github.com/passy/awesome-recursion-schemes) - 用于学习和使用递归方案的有用资源的管理.
- [Practical Recursion Schemes](https://jtobin.io/practical-recursion-schemes) -
  模式仿函数，修正点，嗜好性，同态，
  paramorphisms和hylomorphisms，需要很少的先验知识.
- [An Introduction to Recursion Schemes](http://blog.sumtypeofway.com/an-introduction-to-recursion-schemes/) -
  三部分系列，您可以从头开始发现递归方案
  实现Edward Kmett图书馆的一小部分.
- [Understanding Algebras](https://www.schoolofhaskell.com/user/bartosz/understanding-algebras) -
  Bartosz Milewski解释了F-algebras并​​展示了如何在它的背景下使用它们
  catamorphisms.
- [Recursion Schemes in JavaScript and Flow](https://medium.com/@JosephJnk/recursion-schemes-in-javascript-and-flow-with-static-land-recursision-schemes-97cf10599fb7) -
  在JavaScript中引入递归方案和相关概念的系列，
  针对具有最小功能编程背景的开发人员.

## Articles

- [Recursion Schemes: A Field Guide (Redux)](http://comonad.com/reader/2009/recursion-schemes/) -
  带代码示例的各种递归方案的列表.
- [Catamorphisms](https://wiki.haskell.org/Catamorphisms) -  Haskell Wiki的定义.
- [Catamorphisms](https://www.schoolofhaskell.com/user/edwardk/recursion-schemes/catamorphisms) -
  Edward Kmett在Haskell学校的代码简短定义.
- [Rotating Squares](https://jtobin.io/rotating-squares) - 使用hylomorphism旋转Jared Tobin的四叉树.
- [Recursion Schemes, Part V: Hello, Hylomorphisms](http://blog.sumtypeofway.com/recursion-schemes-part-v/)
- [Promorphisms, Pre and Post](https://jtobin.io/promorphisms-pre-post) - 贾里德托宾的前后同态的实例.
- [Time Traveling Recursion Schemes](https://jtobin.io/time-traveling-recursion) -  Jared Tobin以身作则探索histo和futu.
- [Recursion Schemes, Part IV: Time is of the Essence](http://blog.sumtypeofway.com/recursion-schemes-part-iv-time-is-of-the-essence/) - 关于组织形态和futumorphism的实用文章.
- [Cheat Sheet](https://github.com/sellout/recursion-scheme-talk/blob/master/cheat%20sheet.pdf) - 各种递归方案及其对偶的映射.
- [Correcting the Visitor pattern](http://logji.blogspot.co.uk/2012/02/correcting-visitor-pattern.html) - 显示访问者模式实现f-代数以与catamorphism一起使用（在Java中）.

### Hylomorphisms in the Wild

Bartosz Milewski关于通过应用hylomorphism解决小的实际问题的文章.

- [Stalking a Hylomorphism in the Wild](https://bartoszmilewski.com/2017/12/29/stalking-a-hylomorphism-in-the-wild/) -  2017年代码的出现，Domino挑战
- [Open Seasons on Hylomorphisms](https://bartoszmilewski.com/2018/12/20/open-season-on-hylomorphisms/) - 代码2018的出现，字符串比较挑战

## Papers

- [Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire, 1991, Meijer et al.](http://maartenfokkinga.github.io/utwente/mmf91m.pdf) -
  原始论文大部分基于此.
- [A Duality of Sorts, 2013, Hinze et al.](http://www.cs.ox.ac.uk/ralf.hinze/publications/Sorting.pdf) -
  显示许多基本排序算法作为一对存在，并且这些对存在
  自然地出现在折叠和展开之间的二元性.
- [Sorting with Bialgebras and Distributive Laws, 2012, Hinze et al.](http://www.cs.ox.ac.uk/people/daniel.james/sorting/sorting.pdf) -
  显示如何使用paramorphisms和apomorphisms更有效
  排序算法的实现.
- [Scrap your boilerplate: a practical design pattern for generic programming, 2003, SPJ et al.](http://research.microsoft.com/en-us/um/people/simonpj/Papers/hmap/hmap.ps) -
  用于编写程序的设计模式，该程序遍历由丰富的相互递归数据类型构建的数据结构.

## Presentations

- [Slidedecks by Tim Philip Williams](http://www.timphilipwilliams.com/slides.html) -
  “示例递归方案”和“异国交易的外来工具”提供
  简明的定义以及许多递归方案的实际例子.
- [Unifying Structured Recursion Schemes](https://www.youtube.com/watch?v=9EGYSb9vov8) -
  Ralf Hinze，Nicolas Wu和Jeremy Gibbons演讲12分钟.
- [Recursion Schemes](https://www.youtube.com/watch?v=Zw9KeP3OzpU) -
  由Tim Williams在伦敦Haskell聚会上主讲.
- [F-algebras or: How I Learned to Stop Worrying and Love the Type System](https://www.youtube.com/watch?v=PK4SOaAGVfg) -
  由Anthony Burzillo在纽约Haskell用户小组主讲.
- [A Gentle Introduction to Recursion Schemes](https://www.youtube.com/watch?v=i5A2Amfcir8) -
  由Jean Remi Desjardins在Lambdaconf 2016主讲.
- [recursion-scheme-talk](https://github.com/sellout/recursion-scheme-talk) - 收集有关递归方案的幻灯片.
- [Bracer: Transforming Real-World Languages with Coproducts and Recursion Schemes](https://www.youtube.com/watch?v=5Kr7IykGMzU) -  Patrick Thomson关于使用副产品和递归方案构建程序的高级别讨论.
- [Recursion: Where Functional Programming Hits Bottom](https://www.youtube.com/watch?v=24UoRaoKLjM) - 由Greg Pfeil介绍Haskell和Scala中的递归修正点数据结构和递归方案.
- [Programming with algebras](https://www.youtube.com/watch?v=-98fR9VmLbQ) -  Bartosz Milewski在LambdaCon上发表的谈话形式的文章.
- [Peeling the Banana: Recursion Schemes from First Principles](https://www.youtube.com/watch?v=XZ9nPZbaYfE&t=3s) -  Zainab Ali在LambdaWorld上的介绍性演讲.

## Cheat Sheets

- [The Hitchhiker's Guide to Morphisms](https://ipfs.io/ipfs/QmTppu1VDAQWsdiyVSZX6qb8PErdpwzNP2oKfEhcgaBvWR/guide-to-morphisms.pdf) - 不同态射的概述，包括可打印的PDF.

## Podcasts

- [Magic Read Along](http://www.magicreadalong.com/) - 关于休闲讨论
  类别理论经常提出递归方案，包括[插曲
  33]（http://www.magicreadalong.com/episode/33）谈论Histomorphisms
  和Futumorphisms.

## Implementations

- [recursion-schemes](https://github.com/ekmett/recursion-schemes/) 对于
  Haskell  -  Edward Kmett的规范实现.
- [Matryoshka](https://github.com/slamdata/matryoshka) 对于使用Scalaz的Scala  - 
  固定点数据结构的广义折叠，展开和遍历.
- [andyscott/droste](https://github.com/andyscott/droste) 对于使用猫的Scala  - 
  固定点数据结构的广义折叠，展开和遍历.    
- [recursion\_schemes](https://github.com/vmchale/recursion_schemes/) 对于
  Idris，以Edward Kmett的Haskell图书馆为基础.
- [purescript-matryoshka](https://github.com/slamdata/purescript-matryoshka) 对于PureScript  - 
  俄罗斯套娃的在制品港口.
- [recursion](https://github.com/vmchale/recursion) 对于ATS  - 演示
  ATS中的递归方案.
- [dada](https://github.com/sellout/dada) 为Dhall  - 一个递归的库
  Dhall的计划.
- [static-land-recursion-schemes](https://github.com/JosephJNK/static-land-recursion-schemes) 用于JavaScript / Flow  - 
  数据结构的方案以风格写成 [flow-static-land](https://github.com/gcanti/flow-static-land).
- [Katalyst](https://github.com/aedans/Katalyst) 对于Kotlin来说 - 使用轻量级的高度多态性来重新设想Matryoshka.
- [Groupoid Infinity](http://groupoid.space/mltt/inductive/) [recursion schemes](https://github.com/groupoid/infinity/blob/master/priv/recursion.ctt) 对于 [cubicaltt](https://github.com/mortberg/cubicaltt) - 立方体版本的递归方案.

## License

此内容已获得许可
under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
