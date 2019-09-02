<div class="github-widget" data-repo="pFarb/awesome-crypto-papers"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Crypto Papers  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的清单 [cryptography](https://en.wikipedia.org/wiki/Cryptography) 非密码学家的论文，文章，教程和howtos.

<p align="center">
  <img src="https://raw.githubusercontent.com/pFarb/awesome-crypto-papers/master/awesome-felix-big.jpg" style="width: 50%">
</p>

### Notes 

 该列表的目标是为不同级别的加密知识提供教育阅读材料.  我开始这是因为我的日常工作是入职工程师 [Cossack Labs](https://www.cossacklabs.com)  包括教育他们加密问题，并提供有关特定主题的阅读建议，并涉及重复查找相同的材料.  希望它对其他人也有用. 

 它针对的是那些在更高级别的安全系统中使用加密技术来实现数据库加密，安全共享，各种方案中的端到端加密，并且应该了解它是如何工作，如何失败以及如何受到攻击的人.  它不是一份重要的/重要/历史重要的论文清单（尽管其中很多都在这里）.  它不是针对学者（他们更好地掌握他们所需要的东西），也不是针对想要成为密码学家（在专业指导下更好地遵循结构化方法）的系统研究. 

 当我发现一些“必须拥有的”价值时，它会逐渐扩展.  非常欢迎拉动请求.


* [Introducing people to data security and cryptography](#introducing-people-to-data-security-and-cryptography).
  * [Simple: cryptography for non-engineers](#simple-cryptography-for-non-engineers).
  * [Brief engineer-oriented introductions](#brief-engineer-oriented-introductions).
* [Specific topics](#specific-topcs).
  * [Hashing](#hashing) - 现代和经典哈希的重要部分.
  * [Secret key cryptography](#secret-key-cryptography) - 所有东西都是对称加密.
  * [Cryptoanalysis](#cryptoanalysis) - 攻击密码系统.
  * [Public key cryptography: General and DLP](#public-key-cryptography-general-and-dlp) -  RSA，DH和其他经典技术.
  * [Public key cryptography: Elliptic-curve crypto](#public-key-cryptography-elliptic-curve-crypto) -  ECC，专注于pratcial密码系统.
  * [Zero Knowledge Proofs](#zero-knowledge-proofs) - 知识证明和其他非揭示性密码系统.
  * [Math](#math) - 加密上下文中有用的数学材料.
  * [Post-quantum cryptography](#post-quantum-cryptography) - 后量子时期的密码学.
* [Books](#books).
* [Lectures and educational courses](#lectures-and-educational-courses).
* [Online crypto challenges](#online-crypto-challenges).

## The list

### Introducing people to data security and cryptography

#### Simple: cryptography for non-engineers

* [Nuts and Bolts of Encryption: A Primer for Policymakers](https://www.cs.princeton.edu/~felten/encryption_primer.pdf).
* [Keys under Doormats](https://dspace.mit.edu/bitstream/handle/1721.1/97690/MIT-CSAIL-TR-2015-026.pdf) - 或者为什么密码学不应该被来自世界各地的全明星密码研究委员会后悔. 

#### Brief introductions

* [An Overview of Cryptography](http://www.garykessler.net/library/crypto.html) -  Gary C. Kessler.
* [Using Encryption for Authentication in Large Networks](http://inst.eecs.berkeley.edu/~cs268/sp02/cached_papers/needham.pdf) - 由Needham，Schroeder：这是基于加密的auth启动.
* [Communication Theory of Secrecy Systems](http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf) - 克劳德·香农的基本密码学论文.

#### General cryptographic interest

* [Another Look at “Provable Security”](https://eprint.iacr.org/2004/152.pdf) -  Neal Koblitz等人对安全证明背后的形式主义和天真直觉的调查.
* [The security impact of a new cryptographic library](https://cryptojedi.org/papers/coolnacl-20120725.pdf) - 关于NaCl的介绍性文件，讨论了实施密码学的重要方面，并将其用作安全系统中的一个更大的构建块，Daniel J. Bernstein，Tanja Lange，Peter Schwabe.

<hr>

### Specific topics

#### Hashing

* [FIPS 198-1: HMACs](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf) -  Keyed-Hash消息认证码FIPS文档.
* [FIPS 202: SHA3](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf) -  SHA-3标准：基于排列的散列和可扩展输出函数.
* [Birthday problem](https://en.wikipedia.org/wiki/Birthday_problem) - 背后数学最简单的解释 [birthday attack](https://en.wikipedia.org/wiki/Birthday_attack).
* [On the Security of HMAC and NMAC Based on HAVAL, MD4, MD5, SHA-0 and SHA-1](https://eprint.iacr.org/2006/187.pdf) -  Jongsung Kim等人对不同传统HMAC方案的安全性分析. 
* [On the Security of Randomized CBC-MAC Beyond the Birthday Paradox Limit ](https://eprint.iacr.org/2001/074) -  E. Jaulmes等人的随机CBC-MAC的安全性以及抵抗生日悖论攻击并且可证明达到完全安全性的新结构.

#### Secret key cryptography

* [FIPS 197](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf) -  AES FIPS文件.
* [List of proposed operation modes of AES](http://csrc.nist.gov/groups/ST/toolkit/BCM/modes_development.html) - 由NIST维护.
* [Recomendation for Block Cipher modes of operation: Methods and Techniques](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38a.pdf).
* [Stick figure guide to AES](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html) - 如果上面的东西有点难，或者你正在寻找一个好笑.
* [Cache timing attacks on AES](http://cr.yp.to/antiforgery/cachetiming-20050414.pdf) - 由Daniel J. Bernstein设计的对密码实现的实际攻击的例子.
* [Cache Attacks and Countermeasures: the Case of AES](http://cs.tau.ac.il/~tromer/papers/cache.pdf) - 另一种观点，由Dag Arne Osvik，Adi Shamir和Eran Tromer对AES进行旁道攻击.
* [Salsa20 family of stream ciphers](https://cr.yp.to/snuffle/salsafamily-20071225.pdf) -  Daniel J. Bernstein对Salsa20安全密码的广泛解释.
* [New Features of Latin Dances: Analysis of Salsa, ChaCha, and Rumba](https://eprint.iacr.org/2007/472.pdf) - 由Jean-Philippe Aumasson等人分析Salsa20密码系列.
* [ChaCha20-Poly1305 Cipher Suites for Transport Layer Security (TLS)](https://tools.ietf.org/html/draft-ietf-tls-chacha20-poly1305-04) - 亚当兰利等人的IETF密码系列草案.
* [AES submission document on Rijndael](https://csrc.nist.gov/csrc/media/projects/cryptographic-standards-and-guidelines/documents/aes-development/rijndael-ammended.pdf#page=1) -  Joan Daemen和Vincent Rijmen的原始Rijndael提议.
* [Ongoing Research Areas in Symmetric Cryptography](http://www.ecrypt.eu.org/ecrypt1/documents/D.STVL.3-2.5.pdf) -  ECRYPT密码学卓越网络正在进行的秘密密钥加密和哈希研究概述.
* [伽罗瓦/计数器操作模式（GCM）
]（http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.694.695&amp;rep=rep1&amp;type=pdf） - 由David A. McGrew和John Viega撰写的原始论文，介绍GCM.
* [安全和性能
Galois / Counter Mode（GCM）of Operation]（https://eprint.iacr.org/2004/193.pdf） -  GCM的设计，分析和安全性，更具体地说，AES GCM模式，作者David A. McGrew和约翰维耶加.

#### Cryptoanalysis

* [Differential Cryptanalysis of Salsa20/8](http://www.ecrypt.eu.org/stream/papersdir/2007/010.pdf) -  Yukiyasu Tsunoo等人的流密码加密分析的一个很好的例子.
* [Slide Attacks on a Class of Hash Functions](https://eprint.iacr.org/2008/263) - 将滑动攻击（典型的分组密码加密分析技术）应用于散列函数，M. Gorski等.
* [Self-Study Course in Block Cipher Cryptanalysis](https://www.schneier.com/academic/archives/2000/01/self-study_course_in.html) - 尝试以学生可以用来学习密码分析技术和破解新算法的方式组织现有的分组密码密码分析文献，作者：Bruce Schneier.
* [Statistical Cryptanalysis of Block Ciphers](http://crypto.junod.info/phdthesis.pdf) - 帕斯卡尔朱诺.
* [Cryptoanalysis of block ciphers and protocols](http://www.cs.technion.ac.il/users/wwwb/cgi-bin/tr-info.cgi/2006/PHD/PHD-2006-04) -  Elad Pinhas Barkan.

#### Public key cryptography: General and DLP

* [New Directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) -  Diffie和Hellman的精华论文，介绍公钥加密和密钥交换/协议协议.
* [RFC 2631: Diffie-Hellman Key Agreement](https://tools.ietf.org/html/rfc2631) - 以更多工程术语解释Diffie-Hellman方法.
* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf) - 介绍RSA算法的原始论文. 
* [RSA Algorithm](http://www.di-mgt.com.au/rsa_alg.html) - 相当教育解释RSA背后的每一点.
* [Secure Communications Over Insecure Channels ](http://www.merkle.com/1974/PuzzlesAsPublished.pdf)   -  R. Merkle的论文，早于“密码学的新方向”，尽管它是在它之后出版的.  Diffie-Hellman密钥交换是这种Merkle系统的实现.
* [On the Security of Public Key Protocols ](http://www.cs.huji.ac.il/~dolev/pubs/dolev-yao-ieee-01056650.pdf) -  Dolev-Yao模型是一种形式模型，用于证明交互式加密协议的属性.
* [How to Share a Secret](https://cs.jhu.edu/~sdoshi/crypto/papers/shamirturing.pdf) - 一种分享秘密的安全方法.
* [Twenty Years of Attacks on the RSA Cryptosystem](http://crypto.stanford.edu/~dabo/pubs/papers/RSA-survey.pdf) -  Dan Boneh对攻击RSA及其内部的深入探究. 
* [Remote timing attacks are practical](http://crypto.stanford.edu/~dabo/papers/ssl-timing.pdf) -  D. Boneh，D.Brumley攻击实用加密实现的一个例子.
* [The Equivalence Between the DHP and DLP for Elliptic Curves Used in Practical Applications, Revisited](https://eprint.iacr.org/2005/307.pdf) - 由K. Bentahar撰写.

#### Public key cryptography: Elliptic-curve crypto

* [Elliptic Curve cryptography: A gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/).
* [Explain me like I'm 5: How digital signatures actually work](http://blog.oleganza.com/post/162861219668/eli5-how-digital-signatures-actually-work) -  EdDSA轻松优雅地解释.
* [Elliptic Curve Cryptography: finite fields and discrete logarithms](http://andrea.corbellini.name/2015/05/23/elliptic-curve-cryptography-finite-fields-and-discrete-logarithms/).
* [Detailed Elliptic Curve cryptography tutorial](https://www.johannes-bauer.com/compsci/ecc/).
* [Elliptic Curve Cryptography: ECDH and ECDSA](http://andrea.corbellini.name/2015/05/30/elliptic-curve-cryptography-ecdh-and-ecdsa/).
* [Elliptic Curve Cryptography: breaking security and a comparison with RSA](http://andrea.corbellini.name/2015/06/08/elliptic-curve-cryptography-breaking-security-and-a-comparison-with-rsa/).
* [Elliptic Curve Cryptography: the serpentine course of a paradigm shift](http://eprint.iacr.org/2008/390.pdf) - 对ECC发展及其采用的历史性调查.
* [Let's construct an elliptic curve: Introducing Crackpot2065](http://blog.bjrn.se/2015/07/lets-construct-elliptic-curve.html) - 从头开始​​构建ECC的好例子.
* [Explicit-Formulas Database](http://www.hyperelliptic.org/EFD/) - 对于许多椭圆曲线表示形式.
* [Curve25519: new Diffie-Hellman speed records](https://cr.yp.to/ecdh/curve25519-20060209.pdf) -  Curve25519上的论文.
* [Software implementation of the NIST elliptic curves over prime fields](http://delta.cs.cinvestav.mx/~francisco/arith/julio.pdf) -  M. Brown等人实施椭圆曲线加密的实例.
* [High-speed high-security signatures](https://ed25519.cr.yp.to/ed25519-20110926.pdf) -  Daniel J. Bernstein等人在ed25519曲线上的EdDSA签名研究论文.

#### Zero Knowledge Proofs

* [Proofs of knowledge](http://cseweb.ucsd.edu/~mihir/papers/pok.html) - 一对调查知识证明和计算能力证明概念的论文，M. Bellare和O. Goldreich.
* [How to construct zero-knowledge proof systems for NP](http://www.wisdom.weizmann.ac.il/~oded/gmw1.html) -  Goldreich，Micali和Wigderson的经典论文.
* [Proofs that yield nothing but their validity and a Methodology of Cryptographic protocol design](http://www.math.ias.edu/~avi/PUBLICATIONS/MYPAPERS/GMW86/GMW86.pdf) -  Goldreich，Micali和Wigderson，与上述相关. 
* [A Survey of Noninteractive Zero Knowledge Proof System and Its Applications](https://www.hindawi.com/journals/tswj/2014/560484/).
* [How to Prove a Theorem So No One Else Can Claim It](http://www.mathunion.org/ICM/ICM1986.2/Main/icm1986.2.1444.1451.ocr.pdf) - 曼努埃尔布鲁姆.
* [Information Theoretic Reductions among Disclosure Problems](http://crypto.cs.mcgill.ca/~crepeau/BCR86.pdf) -  Brassau等.
* [Knowledge complexity of interactive proof systems](http://groups.csail.mit.edu/cis/pubs/shafi/1989-siamjc.pdf)   -  GoldWasser，Micali和Rackoff.  在零知识证明中定义“知识”的计算复杂性. 
* [A Survey of Zero-Knowledge Proofs with Applications to Cryptography](http://www.austinmohr.com/work/files/zkp.pdf) - 原创ZKP协议的精彩介绍.
* [Zero Knowledge Protocols and Small Systems](http://www.tml.tkk.fi/Opinnot/Tik-110.501/1995/zeroknowledge.html) - 零知识协议的简介.

#### Key Management

* [Recommendation for Key Management – Part 1: General](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) - 关于密钥管理的目标和程序的方法上非常相关的文件. 

#### Math

* [PRIMES is in P](https://www.cse.iitk.ac.in/users/manindra/algebra/primality_v6.pdf) - 无条件确定性多项式时间算法，用于确定输入数是素数还是复数.

#### Post-quantum cryptography

* [Post-quantum cryptography - dealing with the fallout of physics success](https://eprint.iacr.org/2017/314.pdf) - 简要观察可用于构建密码系统的数学任务，以防止后量子计算机的攻击.
* [Post-quantum cryptography](https://www.researchgate.net/profile/Nicolas_Sendrier/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) - 后量子密码学简介.
* [Post-quantum RSA](https://cr.yp.to/papers/pqrsa-20170419.pdf) -  Daniel Bernshtein洞察如何在后量子时期拯救RSA.

<hr>

### Books

 这似乎有点超出了范围，不是吗？  但这些只是免费在线完全免费提供的书籍.  如果愿意，请将它们作为一系列文件阅读.

* [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/)   -  Dan Boneh和Victor Shoup.  一个平衡的密码学入门课程，一点加密分析和密码学相关的安全性.
* [Analysis and design of cryptographic hash functions, MAC algorithms and block ciphers](https://www.esat.kuleuven.be/cosic/publications/thesis-16.pdf) -  Bart Van Rompay对各种密码和散列函数的设计和加密分析的广泛概述.
* [CrypTool book](https://www.cryptool.org/en/ctp-documentation/ctbook) - 主要以数学方式介绍有关学习，使用和试验加密程序的信息.
* [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/)   - 由Alfred J. Menezes，Paul C. van Oorschot和Scott A. Vanstone撰写.  密码学和密码的经典引入.
* [The joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/)   -  Mike Rosulek.  很多基本的东西都很好.  没有ECC.
* [A Computational Introduction to Number Theory and Algebra](http://www.shoup.net/ntb/) - 作者Victor Shoup，优秀的初学者预订密码学中普遍使用的数学. 

<hr>

### Lectures and educational courses

* [Understanding cryptography: A textbook for Students and Practitioners](http://www.crypto-textbook.com/) - 教科书，伟大的讲座和要解决的问题.
* [Crypto101](https://www.crypto101.io/) -  Crypto 101是一门关于密码学的入门课程，免费提供给所有年龄和技能水平的程序员.
* [A Course in Cryptography](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf) -  Rafael Pass，Abhi Shelat的讲义.
* [Lecture Notes on Cryptography](https://cseweb.ucsd.edu/~mihir/papers/gb.pdf) - 由Shafi Goldwasser（麻省理工学院），M.Bellare（加利福尼亚大学）着名的密码学讲座.
* [Introduction to Cryptography by Christof Paar](https://www.youtube.com/watch?v=2aHkqB2-46k)   -  Christof Paar（德国波鸿大学）的视频课程.  用英语讲.
* [Cryptography I](https://www.coursera.org/learn/crypto)   - 斯坦福大学Coursera课程，由教授授课.  丹·博姆. [Cryptography II](https://www.coursera.org/learn/crypto2) is still in development.
<hr>

### Online crypto challenges 

不完全是论文，但加密挑战是令人敬畏的教育材料.

* [Cryptopals crypto challenges](https://cryptopals.com/).


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃对此作品的所有版权及相关或相邻权利.
