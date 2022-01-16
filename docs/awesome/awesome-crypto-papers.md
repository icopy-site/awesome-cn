<div class="github-widget" data-repo="pFarb/awesome-crypto-papers"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Crypto Papers  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选列表 [cryptography](https://en.wikipedia.org/wiki/Cryptography) 面向非密码学家的论文、文章、教程和操作指南.

<p align="center">
  <img src="https://raw.githubusercontent.com/pFarb/awesome-crypto-papers/master/awesome-felix-big.jpg" style="width: 50%">
</p>

### Notes 

此列表的目标是为不同级别的密码知识提供教育阅读材料. 我开始它是因为我的日常工作是在 [Cossack Labs](https://www.cossacklabs.com) 包括对他们进行密码学方面的教育，并就特定主题提供阅读建议，这涉及反复查找相同的材料. 希望它对其他人也有用. 

它针对的是在更高级别的安全系统中使用密码学来实现数据库加密、安全共享、各种方案中的端到端加密的人们，并且应该了解它是如何工作的，它是如何失败的以及它是如何受到攻击的. 它不是著名/重要/具有历史意义的论文的列表（尽管其中很多都在这里）. 它不是针对学者（他们无论如何都能更好地掌握他们需要什么），也不是针对想要成为密码学家的系统研究（他们最好在专业指导下遵循结构化方法）. 

随着我发现一些“必备”的价值，它将逐渐扩展. 非常欢迎拉取请求.


* [Introducing people to data security and cryptography](#introducing-people-to-data-security-and-cryptography).
  * [Simple: cryptography for non-engineers](#simple-cryptography-for-non-engineers).
  * [Brief engineer-oriented introductions](#brief-engineer-oriented-introductions).
* [Specific topics](#specific-topcs).
  * [Hashing](#hashing) - 现代和经典哈希的重要部分.
  * [Secret key cryptography](#secret-key-cryptography) - 万物对称加密.
  * [Cryptanalysis](#cryptanalysis) - 攻击密码系统.
  * [Public key cryptography: General and DLP](#public-key-cryptography-general-and-dlp) - RSA、DH 等经典技术.
  * [Public key cryptography: Elliptic-curve crypto](#public-key-cryptography-elliptic-curve-crypto) - ECC，专注于实用密码系统.
  * [Zero Knowledge Proofs](#zero-knowledge-proofs) - 知识证明和其他非泄露密码系统.
  * [Math](#math) - 加密上下文中有用的数学材料.
  * [Post-quantum cryptography](#post-quantum-cryptography) - 后量子时期的密码学.
* [Books](#books).
* [Lectures and educational courses](#lectures-and-educational-courses).
* [Online crypto challenges](#online-crypto-challenges).

## The list

### Introducing people to data security and cryptography

#### Simple: cryptography for non-engineers

* [Nuts and Bolts of Encryption: A Primer for Policymakers](https://www.cs.princeton.edu/~felten/encryption_primer.pdf).
* [Keys under Doormats](https://dspace.mit.edu/bitstream/handle/1721.1/97690/MIT-CSAIL-TR-2015-026.pdf) - 或者为什么密码学不应该成为后门，来自世界各地的加密研究全明星委员会. 

#### Brief introductions

* [An Overview of Cryptography](http://www.garykessler.net/library/crypto.html) - 加里 C.凯斯勒.
* [Using Encryption for Authentication in Large Networks](http://inst.eecs.berkeley.edu/~cs268/sp02/cached_papers/needham.pdf) -由Needham，Schroeder：这是基于加密的身份验证开始.
* [Communication Theory of Secrecy Systems](http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf) - Claude Shannon 的基本密码学论文.

#### General cryptographic interest

* [Another Look at “Provable Security”](https://eprint.iacr.org/2004/152.pdf) - Neal Koblitz 等人对安全证明背后的形式主义和幼稚直觉的调查.
* [The security impact of a new cryptographic library](https://cryptojedi.org/papers/coolnacl-20120725.pdf) - 关于 NaCl 的介绍性论文，讨论了实施密码学并将其用作安全系统中更大的构建块的重要方面，作者 Daniel J. Bernstein、Tanja Lange、Peter Schwabe.

<hr>

### Specific topics

#### Hashing

* [FIPS 198-1: HMACs](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf) - Keyed-Hash Message Authentication Code FIPS 文档.
* [FIPS 202: SHA3](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf) - SHA-3 标准：基于排列的散列和可扩展输出函数.
* [Birthday problem](https://en.wikipedia.org/wiki/Birthday_problem) - 数学背后的最佳简单解释 [birthday attack](https://en.wikipedia.org/wiki/Birthday_attack).
* [On the Security of HMAC and NMAC Based on HAVAL, MD4, MD5, SHA-0 and SHA-1](https://eprint.iacr.org/2006/187.pdf) - Jongsung Kim 等人对不同传统 HMAC 方案的安全性分析. 
* [On the Security of Randomized CBC-MAC Beyond the Birthday Paradox Limit ](https://eprint.iacr.org/2001/074) - E. Jaulmes 等人的随机 CBC-MAC 的安全性和抵抗生日悖论攻击并可证明达到完全安全性的新结构.

#### Secret key cryptography

* [FIPS 197](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf) - AES FIPS 文件.
* [List of proposed operation modes of AES](http://csrc.nist.gov/groups/ST/toolkit/BCM/modes_development.html) - 由 NIST 维护.
* [Recomendation for Block Cipher modes of operation: Methods and Techniques](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38a.pdf).
* [Stick figure guide to AES](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html) - 如果上面的东西有点难，或者你正在寻找一个好笑.
* [Cache timing attacks on AES](http://cr.yp.to/antiforgery/cachetiming-20050414.pdf) - Daniel J. Bernstein 设计的密码实现的实用攻击示例.
* [Cache Attacks and Countermeasures: the Case of AES](http://cs.tau.ac.il/~tromer/papers/cache.pdf) - Dag Arne Osvik、Adi Shamir 和 Eran Tromer 对 AES 的侧信道攻击，另一种观点.
* [Salsa20 family of stream ciphers](https://cr.yp.to/snuffle/salsafamily-20071225.pdf) - Daniel J. Bernstein 对 Salsa20 安全密码的广泛解释.
* [New Features of Latin Dances: Analysis of Salsa, ChaCha, and Rumba](https://eprint.iacr.org/2007/472.pdf) - Jean-Philippe Aumasson 等人对 Salsa20 密码家族的分析.
* [ChaCha20-Poly1305 Cipher Suites for Transport Layer Security (TLS)](https://tools.ietf.org/html/draft-ietf-tls-chacha20-poly1305-04) - IETF 密码套件系列草案，由 Adam Langley 等人撰写.
* [AES submission document on Rijndael](https://csrc.nist.gov/csrc/media/projects/cryptographic-standards-and-guidelines/documents/aes-development/rijndael-ammended.pdf#page=1) - Joan Daemen 和 Vincent Rijmen 的原始 Rijndael 提案.
* [Ongoing Research Areas in Symmetric Cryptography](http://www.ecrypt.eu.org/ecrypt1/documents/D.STVL.3-2.5.pdf) - ECRYPT Network of Excellence in Cryptology 对密钥加密和散列的持续研究概述.
* [The Galois/Counter Mode of Operation (GCM)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.694.695&rep=rep1&type=pdf) - 介绍 GCM 的原始论文，由 David A. McGrew 和 John Viega 撰写.
* [The Security and Performance of the Galois/Counter Mode (GCM) of Operation](https://eprint.iacr.org/2004/193.pdf) - GCM 的设计、分析和安全性，更具体地说，是 AES GCM 模式，作者 David A. McGrew 和 John Viega.
* [GCM Security Bounds Reconsidered](https://www.iacr.org/archive/fse2015/85400168/85400168.pdf) -- 一种针对具有较高反碰撞概率的 AES GCM 的随机数生成的分析和算法，作者 Yuichi Niwa、Keisuke Ohashi、Kazuhiko Minematsu、Tetsu Iwata.
* [Proxy-Mediated Searchable Encryption in SQL Databases Using Blind Indexes](https://eprint.iacr.org/2019/806.pdf) - Eugene Pilyankevich、Dmytro Kornieiev、Artem Storozhuk 对现有可搜索加密方案的概述，以及基于 AES-GCM、盲索引和布隆过滤器的方案分析.

#### Cryptanalysis

* [Differential Cryptanalysis of Salsa20/8](http://www.ecrypt.eu.org/stream/papersdir/2007/010.pdf) - Yukiyasu Tsunoo 等人的流密码密码分析的一个很好的例子.
* [Slide Attacks on a Class of Hash Functions](https://eprint.iacr.org/2008/263) - 将滑动攻击（块密码的典型密码分析技术）应用于哈希函数，M. Gorski 等人.
* [Self-Study Course in Block Cipher Cryptanalysis](https://www.schneier.com/academic/archives/2000/01/self-study_course_in.html) - 尝试以一种学生可以用来学习密码分析技术和破解新算法的方式来组织现有的分组密码密码分析文献，作者 Bruce Schneier.
* [Statistical Cryptanalysis of Block Ciphers](http://crypto.junod.info/phdthesis.pdf) ——帕斯卡·朱诺.
* [Cryptanalysis of block ciphers and protocols](http://www.cs.technion.ac.il/users/wwwb/cgi-bin/tr-info.cgi/2006/PHD/PHD-2006-04) - By Elad Pinhas Barkan.
* [Too much crypto](https://eprint.iacr.org/2019/1492.pdf) - Jean-Philippe Aumasson 分析对称密码学原语的轮数，并建议减少轮数.
* [How to Break MD5 and Other Hash Functions](https://iacr.org/archive/eurocrypt2005/34940019/34940019.pdf) - 2005 年关于 MD5、MD4 和其他散列函数的模差分碰撞攻击的论文，作者 Xiaoyun Wang 和 Hongbo Yu.
* [New attacks on Keccak-224 and Keccak-256](https://www.iacr.org/archive/fse2012/75490447/75490447.pdf) - Itai Dinur、Orr Dunkelman、Adi Shamir 于 2012 年发表的一篇关于使用微分和代数技术组合对 SHA-3 进行碰撞攻击的论文.
* [A Single-Key Attack on the Full GOST Block Cipher](https://www.iacr.org/archive/fse2011/67330297/67330297.pdf) - 对 GOST 分组密码的攻击（“Reflection-Meet-inthe-Middle Attack”），允许通过 2^225 次计算和 2^32 个已知明文恢复密钥，作者 Takanori Isobe.
* [Intro to Linear & Differential Cryptanalysis](http://www.cs.bc.edu/~straubin/crypto2017/heys.pdf) - 一篇对初学者友好的论文，解释和演示线性和差分密码分析技术.

#### Public key cryptography: General and DLP

* [New Directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) - Diffie 和 Hellman 的开创性论文，介绍了公钥密码学和密钥交换/协议协议.
* [RFC 2631: Diffie-Hellman Key Agreement](https://tools.ietf.org/html/rfc2631) - 以更多工程术语解释 Diffie-Hellman 方法.
* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf) - 介绍 RSA 算法的原始论文. 
* [RSA Algorithm](http://www.di-mgt.com.au/rsa_alg.html) - 对 RSA 背后的每一点进行教育解释.
* [Secure Communications Over Insecure Channels ](http://www.merkle.com/1974/PuzzlesAsPublished.pdf)  - R. Merkle 的论文，早于“密码学的新方向”，尽管它是在它之后发表的.  Diffie-Hellman 密钥交换就是这样一个 Merkle 系统的实现.
* [On the Security of Public Key Protocols ](http://www.cs.huji.ac.il/~dolev/pubs/dolev-yao-ieee-01056650.pdf) - Dolev-Yao 模型是一种形式化模型，用于证明交互式密码协议的属性.
* [How to Share a Secret](https://github.com/arupmondal-cs/Crypto-Research/blob/master/Secret%20Sharing/shamirturing.pdf) - 一种共享秘密的安全方法.
* [Twenty Years of Attacks on the RSA Cryptosystem](http://crypto.stanford.edu/~dabo/pubs/papers/RSA-survey.pdf) - 对攻击 RSA 及其内部结构的深入调查，作者 Dan Boneh. 
* [Remote timing attacks are practical](http://crypto.stanford.edu/~dabo/papers/ssl-timing.pdf) - D. Boneh, D. Brumley 攻击实际加密实施的一个例子.
* [The Equivalence Between the DHP and DLP for Elliptic Curves Used in Practical Applications, Revisited](https://eprint.iacr.org/2005/307.pdf) - K. Bentahar.

#### Public key cryptography: Elliptic-curve crypto

* [Elliptic Curve cryptography: A gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/).
* [Explain me like I'm 5: How digital signatures actually work](http://blog.oleganza.com/post/162861219668/eli5-how-digital-signatures-actually-work) - EdDSA 轻松优雅地解释.
* [Elliptic Curve Cryptography: finite fields and discrete logarithms](http://andrea.corbellini.name/2015/05/23/elliptic-curve-cryptography-finite-fields-and-discrete-logarithms/).
* [Detailed Elliptic Curve cryptography tutorial](https://www.johannes-bauer.com/compsci/ecc/).
* [Elliptic Curve Cryptography: ECDH and ECDSA](http://andrea.corbellini.name/2015/05/30/elliptic-curve-cryptography-ecdh-and-ecdsa/).
* [Elliptic Curve Cryptography: breaking security and a comparison with RSA](http://andrea.corbellini.name/2015/06/08/elliptic-curve-cryptography-breaking-security-and-a-comparison-with-rsa/).
* [Elliptic Curve Cryptography: the serpentine course of a paradigm shift](http://eprint.iacr.org/2008/390.pdf) - 对 ECC 的发展及其采用的历史调查.
* [Let's construct an elliptic curve: Introducing Crackpot2065](http://blog.bjrn.se/2015/07/lets-construct-elliptic-curve.html) - 从头开始​​构建 ECC 的好例子.
* [Explicit-Formulas Database](http://www.hyperelliptic.org/EFD/) - 对于许多椭圆曲线表示形式.
* [Curve25519: new Diffie-Hellman speed records](https://cr.yp.to/ecdh/curve25519-20060209.pdf) - Curve25519 上的论文.
* [Software implementation of the NIST elliptic curves over prime fields](http://delta.cs.cinvestav.mx/~francisco/arith/julio.pdf) - M. Brown 等人实施椭圆曲线加密的实际示例.
* [High-speed high-security signatures](https://ed25519.cr.yp.to/ed25519-20110926.pdf) - Daniel J. Bernstein 等人关于 ed25519 曲线上的 EdDSA 签名的开创性论文.

#### Zero Knowledge Proofs

* [Proofs of knowledge](https://cseweb.ucsd.edu/~mihir/papers/pok.pdf) - 两篇研究知识证明和计算能力证明概念的论文，M. Bellare 和 O. Goldreich.
* [How to construct zero-knowledge proof systems for NP](http://www.wisdom.weizmann.ac.il/~oded/gmw1.html) - Goldreich、Micali 和 Wigderson 的经典论文.
* [Proofs that yield nothing but their validity and a Methodology of Cryptographic protocol design](http://www.math.ias.edu/~avi/PUBLICATIONS/MYPAPERS/GMW86/GMW86.pdf) - Goldreich、Micali 和 Wigderson，与上述有关. 
* [A Survey of Noninteractive Zero Knowledge Proof System and Its Applications](https://www.hindawi.com/journals/tswj/2014/560484/).
* [How to Prove a Theorem So No One Else Can Claim It](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.469.9048&rep=rep1&type=pdf) - 曼努埃尔·布鲁姆.
* [Information Theoretic Reductions among Disclosure Problems](http://crypto.cs.mcgill.ca/~crepeau/BCR86.pdf) - Brassau 等人.
* [Knowledge complexity of interactive proof systems](https://github.com/manjunath5496/Shafi-Goldwasser-Publications/blob/master/1989-siamjc.pdf)  - GoldWasser、Micali 和 Rackoff. 在零知识证明中定义“知识”的计算复杂度. 
* [A Survey of Zero-Knowledge Proofs with Applications to Cryptography](http://www.austinmohr.com/work/files/zkp.pdf) - 原始 ZKP 协议的精彩介绍.
* [Zero Knowledge Protocols and Small Systems](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.186.4901&rep=rep1&type=pdf) - 零知识协议的一个很好的介绍.
* [Multi-Theorem Preprocessing NIZKs from Lattices](https://link.springer.com/chapter/10.1007%2F978-3-319-96881-0_25) - Sam Kim 和 David J. Wu 使用基于格的预处理模型构建非交互式零知识 (NIZK) 证明.

#### Key Management

* [Recommendation for Key Management – Part 1: General](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) - 关于关键管理目标和程序的方法论非常相关的文件. 

#### Math

* [PRIMES is in P](https://www.cse.iitk.ac.in/users/manindra/algebra/primality_v6.pdf) - 确定输入数是素数还是合数的无条件确定性多项式时间算法.

#### Post-quantum cryptography

* [Post-quantum cryptography - dealing with the fallout of physics success](https://eprint.iacr.org/2017/314.pdf) - 简要观察可用于构建密码系统以抵御后量子计算机攻击的数学任务.
* [Post-quantum cryptography](https://www.researchgate.net/profile/Nicolas_Sendrier/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) - 后量子密码学简介.
* [Post-quantum RSA](https://cr.yp.to/papers/pqrsa-20170419.pdf) - Daniel Bernshtein 对如何在后量子时代拯救 RSA 的见解.

<hr>

### Books

这似乎有点超出范围，不是吗？ 但这些都是完全免费在线提供的书籍. 如果愿意，可以将它们作为一系列论文阅读.

* [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/)  - 丹·博内 (Dan Boneh) 和维克多·舒普 (Victor Shoup). 一个平衡的密码学入门课程，一些密码分析和密码学相关的安全性.
* [Analysis and design of cryptographic hash functions, MAC algorithms and block ciphers](https://www.esat.kuleuven.be/cosic/publications/thesis-16.pdf) - Bart Van Rompay 对各种密码和散列函数的设计和密码分析的广泛概述.
* [CrypTool book](https://www.cryptool.org/en/ctp-documentation/ctbook) - 主要以数学为导向的关于学习、使用和试验密码程序的信息.
* [Handbook of Applied Cryptography](https://cacr.uwaterloo.ca/hac/)  - Alfred J. Menezes、Paul C. van Oorschot 和 Scott A. Vanstone. 密码学和密码学的经典介绍.
* [The joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/)  - 迈克·罗苏莱克. 很多基本的东西都涵盖得很好. 没有ECC.
* [A Computational Introduction to Number Theory and Algebra](http://www.shoup.net/ntb/) - 由 Victor Shoup 撰写，关于密码学中普遍使用的数学的优秀入门书籍. 

<hr>

### Lectures and educational courses

* [Understanding cryptography: A textbook for Students and Practitioners](http://www.crypto-textbook.com/) - 教科书、精彩的讲座和需要解决的问题.
* [Crypto101](https://www.crypto101.io/) - Crypto 101 是一门密码学入门课程，所有年龄和技能水平的程序员均可免费使用.
* [A Course in Cryptography](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf) - Rafael Pass，Abhi Shelat 的讲义.
* [Lecture Notes on Cryptography](https://cseweb.ucsd.edu/~mihir/papers/gb.pdf) - Shafi Goldwasser (MIT), M. Bellare (University of California) 著名的密码学讲座集.
* [Introduction to Cryptography by Christof Paar](https://www.youtube.com/watch?v=2aHkqB2-46k)  - Christof Paar（德国波鸿大学）的视频课程. 用英语讲.
* [Cryptography I](https://www.coursera.org/learn/crypto)  - 斯坦福大学 Coursera 课程，由教授教授. 丹·博内. [Cryptography II](https://www.coursera.org/learn/crypto2) 仍在开发中.
<hr>

### Online crypto challenges 

不完全是论文，但加密挑战是很棒的教育材料.

* [CryptoHack](https://cryptohack.org/)

* [Cryptopals crypto challenges](https://cryptopals.com/).

* [id0-rsa crypto challenges](https://id0-rsa.pub/).

* [MTC3](https://www.mysterytwisterc3.org/en/) - xipher 竞赛有 200 多个不同级别的挑战、一个主持论坛和一个名人堂.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃本作品的所有版权和相关或邻接权.
