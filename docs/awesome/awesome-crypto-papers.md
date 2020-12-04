<div class="github-widget" data-repo="pFarb/awesome-crypto-papers"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Crypto Papers  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选清单 [cryptography](https://en.wikipedia.org/wiki/Cryptography) 非密码学家的论文，文章，教程和howtos.

<p align="center">
  <img src="https://raw.githubusercontent.com/pFarb/awesome-crypto-papers/master/awesome-felix-big.jpg" style="width: 50%">
</p>

### Notes 

该列表的目的是为不同级别的密码知识提供教育性阅读材料. 我之所以开始，是因为我的日常工作是在 [Cossack Labs](https://www.cossacklabs.com) 包括对他们进行密码学方面的教育，并就特定主题提供建议，包括反复查找相同的材料. 希望对其他人也有用. 

它适用于在更高级别的安全系统中使用加密技术以各种方案实施数据库加密，安全共享，端到端加密的人员，并且应了解其工作方式，失败方式以及受到攻击的方式. 它不是重要/重要/历史上重要论文的列表（尽管这里有很多）. 它既不是针对学者（无论如何他们都会更好地掌握他们的需求），也不是针对想要成为密码学家的系统研究（他们在专业指导下更好地遵循结构化方法）. 

当我发现某些“必备”价值时，它将逐步扩展. 拉取请求非常受欢迎.


* [Introducing people to data security and cryptography](#introducing-people-to-data-security-and-cryptography).
  * [Simple: cryptography for non-engineers](#simple-cryptography-for-non-engineers).
  * [Brief engineer-oriented introductions](#brief-engineer-oriented-introductions).
* [Specific topics](#specific-topcs).
  * [Hashing](#hashing) -关于现代和经典哈希的重要部分.
  * [Secret key cryptography](#secret-key-cryptography) -所有事物对称加密.
  * [Cryptoanalysis](#cryptoanalysis) -攻击密码系统.
  * [Public key cryptography: General and DLP](#public-key-cryptography-general-and-dlp) -RSA，DH和其他经典技术.
  * [Public key cryptography: Elliptic-curve crypto](#public-key-cryptography-elliptic-curve-crypto) -ECC，重点关注实用密码系统.
  * [Zero Knowledge Proofs](#zero-knowledge-proofs) -知识证明和其他非公开的密码系统.
  * [Math](#math) -加密上下文中有用的数学材料.
  * [Post-quantum cryptography](#post-quantum-cryptography) -后量子时期的密码学.
* [Books](#books).
* [Lectures and educational courses](#lectures-and-educational-courses).
* [Online crypto challenges](#online-crypto-challenges).

## The list

### Introducing people to data security and cryptography

#### Simple: cryptography for non-engineers

* [Nuts and Bolts of Encryption: A Primer for Policymakers](https://www.cs.princeton.edu/~felten/encryption_primer.pdf).
* [Keys under Doormats](https://dspace.mit.edu/bitstream/handle/1721.1/97690/MIT-CSAIL-TR-2015-026.pdf) -或者为什么不应该由世界各地的加密研究全明星委员会将加密技术后门化. 

#### Brief introductions

* [An Overview of Cryptography](http://www.garykessler.net/library/crypto.html) -Gary C. Kessler.
* [Using Encryption for Authentication in Large Networks](http://inst.eecs.berkeley.edu/~cs268/sp02/cached_papers/needham.pdf) -施罗德（Needham），施罗德（Needham）：这是基于加密的身份验证开始.
* [Communication Theory of Secrecy Systems](http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf) -Claude Shannon撰写的基本密码学论文.

#### General cryptographic interest

* [Another Look at “Provable Security”](https://eprint.iacr.org/2004/152.pdf) -对Neal Koblitz等人的安全性背后形式主义和天真直觉的询问.
* [The security impact of a new cryptographic library](https://cryptojedi.org/papers/coolnacl-20120725.pdf) -关于NaCl的介绍性文件，由Daniel J. Bernstein，Tanja Lange和Peter Schwabe讨论了实现加密并将其用作安全系统中更大的构建块的重要方面.

<hr>

### Specific topics

#### Hashing

* [FIPS 198-1: HMACs](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf) -密钥哈希消息认证代码FIPS文档.
* [FIPS 202: SHA3](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf) -SHA-3标准：基于置换的哈希和可扩展输出函数.
* [Birthday problem](https://en.wikipedia.org/wiki/Birthday_problem) -背后的数学最好的简单解释 [birthday attack](https://en.wikipedia.org/wiki/Birthday_attack).
* [On the Security of HMAC and NMAC Based on HAVAL, MD4, MD5, SHA-0 and SHA-1](https://eprint.iacr.org/2006/187.pdf) -Jongsung Kim等人对不同的旧式HMAC方案进行安全性分析. 
* [On the Security of Randomized CBC-MAC Beyond the Birthday Paradox Limit ](https://eprint.iacr.org/2001/074) -随机CBC-MAC的安全性和抵抗生日悖论攻击并证明完全安全的新型结构，作者：E.Jaulmes等.

#### Secret key cryptography

* [FIPS 197](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf) -AES FIPS文档.
* [List of proposed operation modes of AES](http://csrc.nist.gov/groups/ST/toolkit/BCM/modes_development.html) -由NIST维护.
* [Recomendation for Block Cipher modes of operation: Methods and Techniques](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38a.pdf).
* [Stick figure guide to AES](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html) -如果上面的内容有点难，或者您要找一个开心的笑声.
* [Cache timing attacks on AES](http://cr.yp.to/antiforgery/cachetiming-20050414.pdf) -Daniel J. Bernstein设计对密码实施进行重大实际攻击的示例.
* [Cache Attacks and Countermeasures: the Case of AES](http://cs.tau.ac.il/~tromer/papers/cache.pdf) -Dag Arne Osvik，Adi Shamir和Eran Tromer对AES的侧信道攻击，另一种观点.
* [Salsa20 family of stream ciphers](https://cr.yp.to/snuffle/salsafamily-20071225.pdf) -Daniel J. Bernstein对Salsa20安全密码的广泛解释.
* [New Features of Latin Dances: Analysis of Salsa, ChaCha, and Rumba](https://eprint.iacr.org/2007/472.pdf) -Jean-Philippe Aumasson等人对Salsa20密码族的分析.
* [ChaCha20-Poly1305 Cipher Suites for Transport Layer Security (TLS)](https://tools.ietf.org/html/draft-ietf-tls-chacha20-poly1305-04) -Adam Langley等人的IETF密码套件家族草案.
* [AES submission document on Rijndael](https://csrc.nist.gov/csrc/media/projects/cryptographic-standards-and-guidelines/documents/aes-development/rijndael-ammended.pdf#page=1) -Joan Daemen和Vincent Rijmen提出的Rijndael原始提案.
* [Ongoing Research Areas in Symmetric Cryptography](http://www.ecrypt.eu.org/ecrypt1/documents/D.STVL.3-2.5.pdf) -ECRYPT密码学卓越网络对正在进行的秘密密码学和哈希研究进行了概述.
* [The Galois/Counter Mode of Operation (GCM)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.694.695&rep=rep1&type=pdf) -由David A. McGrew和John Viega撰写的介绍GCM的原始论文.
* [The Security and Performance of the Galois/Counter Mode (GCM) of Operation](https://eprint.iacr.org/2004/193.pdf) -David A. McGrew和John Viega设计的GCM，更具体地说是AES GCM模式的分析和安全性.
* [GCM Security Bounds Reconsidered](https://www.iacr.org/archive/fse2015/85400168/85400168.pdf) -具有较高抗冲突概率的AES GCM随机数生成的分析和算法，作者是一一（Yuichi Niwa），大桥圭介（Keisuke Ohashi），Minatsu和和彦（Kazuhiko Minematsu），岩田哲（Tetsu Iwata）.
* [Proxy-Mediated Searchable Encryption in SQL Databases Using Blind Indexes](https://eprint.iacr.org/2019/806.pdf) -概述了现有的可搜索加密方案，并分析了Eugene Pilyankevich，Dmytro Kornieiev，Artem Storozhuk的基于AES-GCM，盲索引和Bloom过滤器的方案.

#### Cryptoanalysis

* [Differential Cryptanalysis of Salsa20/8](http://www.ecrypt.eu.org/stream/papersdir/2007/010.pdf) -Yukiyasu Tsunoo等人的流密码加密分析的一个很好的例子.
* [Slide Attacks on a Class of Hash Functions](https://eprint.iacr.org/2008/263) -M. Gorski等人将滑动攻击（用于分组密码的典型密码分析技术）应用于哈希函数.
* [Self-Study Course in Block Cipher Cryptanalysis](https://www.schneier.com/academic/archives/2000/01/self-study_course_in.html) -布鲁斯·施耐尔（Bruce Schneier）试图以一种学生可以用来学习密码分析技术和打破新算法的方式来组织现有的分组密码密码分析文献.
* [Statistical Cryptanalysis of Block Ciphers](http://crypto.junod.info/phdthesis.pdf) -帕斯卡尔·朱诺（Pascal Junod）.
* [Cryptoanalysis of block ciphers and protocols](http://www.cs.technion.ac.il/users/wwwb/cgi-bin/tr-info.cgi/2006/PHD/PHD-2006-04) - By Elad Pinhas Barkan.
* [Too much crypto](https://eprint.iacr.org/2019/1492.pdf) -让-菲利普·奥马森（Jean-Philippe Aumasson）分析了对称密码原语的回合数量，并提出了减少回合数量的建议.
* [How to Break MD5 and Other Hash Functions](https://iacr.org/archive/eurocrypt2005/34940019/34940019.pdf) -王晓云和于洪波在2005年发表的一篇关于对MD5，MD4和其他哈希函数的模块化差分冲突攻击的论文.
* [New attacks on Keccak-224 and Keccak-256](https://www.iacr.org/archive/fse2012/75490447/75490447.pdf) -Itai Dinur，Orr Dunkelman，Adi Shamir在2012年发表的一篇有关将差分和代数技术相结合对SHA-3进行碰撞攻击的论文.
* [A Single-Key Attack on the Full GOST Block Cipher](https://www.iacr.org/archive/fse2011/67330297/67330297.pdf) -由Takanori Isobe对GOST分组密码进行的攻击（“中间反射遇见攻击”），它允许使用2 ^ 225的计算和2 ^ 32的已知明文恢复密钥.

#### Public key cryptography: General and DLP

* [New Directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) -Diffie和Hellman的开创性论文，介绍了公共密钥加密和密钥交换/协议协议.
* [RFC 2631: Diffie-Hellman Key Agreement](https://tools.ietf.org/html/rfc2631) -用更多工程术语解释Diffie-Hellman methon.
* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf) -介绍RSA算法的原始论文. 
* [RSA Algorithm](http://www.di-mgt.com.au/rsa_alg.html) -对RSA背后每一个方面的确切教育解释.
* [Secure Communications Over Insecure Channels ](http://www.merkle.com/1974/PuzzlesAsPublished.pdf)  -R. Merkle撰写的论文早于“密码学的新方向”，尽管它在其后发表.  Diffie-Hellman密钥交换是这种Merkle系统的实现.
* [On the Security of Public Key Protocols ](http://www.cs.huji.ac.il/~dolev/pubs/dolev-yao-ieee-01056650.pdf) -Dolev-Yao模型是形式模型，用于证明交互式密码协议的属性.
* [How to Share a Secret](https://cs.jhu.edu/~sdoshi/crypto/papers/shamirturing.pdf) -分享秘密的安全方法.
* [Twenty Years of Attacks on the RSA Cryptosystem](http://crypto.stanford.edu/~dabo/pubs/papers/RSA-survey.pdf) -Dan Boneh对攻击RSA及其内部进行了很好的询问. 
* [Remote timing attacks are practical](http://crypto.stanford.edu/~dabo/papers/ssl-timing.pdf) -D. Boneh，D.Brumley提出的攻击实际加密实现的示例.
* [The Equivalence Between the DHP and DLP for Elliptic Curves Used in Practical Applications, Revisited](https://eprint.iacr.org/2005/307.pdf) -由K. Bentahar.

#### Public key cryptography: Elliptic-curve crypto

* [Elliptic Curve cryptography: A gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/).
* [Explain me like I'm 5: How digital signatures actually work](http://blog.oleganza.com/post/162861219668/eli5-how-digital-signatures-actually-work) -EdDSA轻松而优雅地进行了解释.
* [Elliptic Curve Cryptography: finite fields and discrete logarithms](http://andrea.corbellini.name/2015/05/23/elliptic-curve-cryptography-finite-fields-and-discrete-logarithms/).
* [Detailed Elliptic Curve cryptography tutorial](https://www.johannes-bauer.com/compsci/ecc/).
* [Elliptic Curve Cryptography: ECDH and ECDSA](http://andrea.corbellini.name/2015/05/30/elliptic-curve-cryptography-ecdh-and-ecdsa/).
* [Elliptic Curve Cryptography: breaking security and a comparison with RSA](http://andrea.corbellini.name/2015/06/08/elliptic-curve-cryptography-breaking-security-and-a-comparison-with-rsa/).
* [Elliptic Curve Cryptography: the serpentine course of a paradigm shift](http://eprint.iacr.org/2008/390.pdf) -对ECC的发展及其采用的历史性研究.
* [Let's construct an elliptic curve: Introducing Crackpot2065](http://blog.bjrn.se/2015/07/lets-construct-elliptic-curve.html) -从头开始构建ECC的典范.
* [Explicit-Formulas Database](http://www.hyperelliptic.org/EFD/) -对于许多椭圆曲线表示形式.
* [Curve25519: new Diffie-Hellman speed records](https://cr.yp.to/ecdh/curve25519-20060209.pdf) -在Curve25519上的论文.
* [Software implementation of the NIST elliptic curves over prime fields](http://delta.cs.cinvestav.mx/~francisco/arith/julio.pdf) -M. Brown等人的实现椭圆曲线加密的实用示例.
* [High-speed high-security signatures](https://ed25519.cr.yp.to/ed25519-20110926.pdf) -Daniel J. Bernstein等人在ed25519曲线上有关EdDSA签名的开创性论文.

#### Zero Knowledge Proofs

* [Proofs of knowledge](http://cseweb.ucsd.edu/~mihir/papers/pok.html) -一对研究知识证明和计算能力证明概念的论文，M.Bellare和O. Goldreich.
* [How to construct zero-knowledge proof systems for NP](http://www.wisdom.weizmann.ac.il/~oded/gmw1.html) -Goldreich，Micali和Wigderson的经典论文.
* [Proofs that yield nothing but their validity and a Methodology of Cryptographic protocol design](http://www.math.ias.edu/~avi/PUBLICATIONS/MYPAPERS/GMW86/GMW86.pdf) -由Goldreich，Micali和Wigderson撰写，相对于上述说法. 
* [A Survey of Noninteractive Zero Knowledge Proof System and Its Applications](https://www.hindawi.com/journals/tswj/2014/560484/).
* [How to Prove a Theorem So No One Else Can Claim It](http://www.mathunion.org/ICM/ICM1986.2/Main/icm1986.2.1444.1451.ocr.pdf) -曼努埃尔·布鲁姆（Manuel Blum）.
* [Information Theoretic Reductions among Disclosure Problems](http://crypto.cs.mcgill.ca/~crepeau/BCR86.pdf) -Brassau等.
* [Knowledge complexity of interactive proof systems](http://groups.csail.mit.edu/cis/pubs/shafi/1989-siamjc.pdf)  -由GoldWasser，Micali和Rackoff撰写. 在零知识证明内定义“知识”的计算复杂性. 
* [A Survey of Zero-Knowledge Proofs with Applications to Cryptography](http://www.austinmohr.com/work/files/zkp.pdf) -原始ZKP协议的精彩介绍.
* [Zero Knowledge Protocols and Small Systems](http://www.tml.tkk.fi/Opinnot/Tik-110.501/1995/zeroknowledge.html) -零知识协议的良好介绍.
* [Multi-Theorem Preprocessing NIZKs from Lattices](https://link.springer.com/chapter/10.1007%2F978-3-319-96881-0_25) -Sam Kim和David J. Wu使用基于格的预处理模型构造非交互式零知识（NIZK）证明.

#### Key Management

* [Recommendation for Key Management – Part 1: General](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) -有关密钥管理目标和程序的方法学上非常相关的文件. 

#### Math

* [PRIMES is in P](https://www.cse.iitk.ac.in/users/manindra/algebra/primality_v6.pdf) -确定输入数字是质数还是复合数的无条件确定性多项式时间算法.

#### Post-quantum cryptography

* [Post-quantum cryptography - dealing with the fallout of physics success](https://eprint.iacr.org/2017/314.pdf) -对数学任务的简要观察，这些数学任务可用于构建安全的密码系统，以抵抗后量子计算机的攻击.
* [Post-quantum cryptography](https://www.researchgate.net/profile/Nicolas_Sendrier/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) -后量子密码学简介.
* [Post-quantum RSA](https://cr.yp.to/papers/pqrsa-20170419.pdf) -Daniel Bernshtein的见解如何在量子时代后保存RSA.

<hr>

### Books

这似乎有点超出范围，不是吗？ 但是这些都是只能在网上完全免费获得的书籍. 如果可以的话，可以按顺序阅读它们.

* [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/)  -Dan Boneh和Victor Shoup着. 密码学的入门课程非常均衡，其中包括一些密码分析和与密码相关的安全性.
* [Analysis and design of cryptographic hash functions, MAC algorithms and block ciphers](https://www.esat.kuleuven.be/cosic/publications/thesis-16.pdf) -Bart Van Rompay对各种密码和哈希函数进行设计和密码分析的广泛概述.
* [CrypTool book](https://www.cryptool.org/en/ctp-documentation/ctbook) -有关学习，使用和试验密码程序的主要数学信息.
* [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/)  -Alfred J. Menezes，Paul C. van Oorschot和Scott A. Vanstone. 对密码学和密码的经典介绍.
* [The joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/)  -Mike Rosulek. 很多基本内容都涵盖得很好. 没有ECC.
* [A Computational Introduction to Number Theory and Algebra](http://www.shoup.net/ntb/) -由Victor Shoup撰写的优秀入门书籍，介绍了密码学中普遍使用的数学. 

<hr>

### Lectures and educational courses

* [Understanding cryptography: A textbook for Students and Practitioners](http://www.crypto-textbook.com/) -教科书，精彩的讲座和需要解决的问题.
* [Crypto101](https://www.crypto101.io/) -Crypto 101是一门密码学入门课程，所有年龄和技能水平的程序员均可免费使用.
* [A Course in Cryptography](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf) -Abhi Shelat的Rafael Pass发表的演讲笔记.
* [Lecture Notes on Cryptography](https://cseweb.ucsd.edu/~mihir/papers/gb.pdf) -Shafi Goldwasser（麻省理工学院），M.Bellare（加利福尼亚大学）著名的密码学讲座.
* [Introduction to Cryptography by Christof Paar](https://www.youtube.com/watch?v=2aHkqB2-46k)  -Christof Paar（德国波鸿大学）的视频课程. 用英语讲.
* [Cryptography I](https://www.coursera.org/learn/crypto)  -斯坦福大学Coursera课程，教授教授. 丹·博内 [Cryptography II](https://www.coursera.org/learn/crypto2) 仍在开发中.
<hr>

### Online crypto challenges 

不完全是论文，但是加密挑战是很棒的教育材料.

* [CryptoHack](https://cryptohack.org/)

* [Cryptopals crypto challenges](https://cryptopals.com/).

* [id0-rsa crypto challenges](https://id0-rsa.pub/).

* [MTC3](https://www.mysterytwisterc3.org/en/) -密码竞赛，包含200多个不同级别的挑战，一个主持人的论坛和一个名人堂.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者放弃了该作品的所有版权以及相关或邻近的权利.
