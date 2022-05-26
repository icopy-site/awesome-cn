<div class="github-widget" data-repo="sobolevn/awesome-cryptography"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <img src="https://raw.githubusercontent.com/sobolevn/awesome-cryptography/master/awesome-crypto.png?raw=true" alt="Awesome Cryptography">
</p>

[![Follow us on twitter](https://img.shields.io/twitter/follow/awe_crypto_bot.svg?style=social&maxAge=0)](https://twitter.com/awe_crypto_bot)

加密资源和链接的精选列表.


<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->


<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - 对称密钥块密码（或三重数据加密算法（TDEA 或三重 DEA），它将数据加密标准 (DES) 密码算法应用于每个数据块三次.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - 对称密钥分组密码算法和美国政府安全和分类数据加密和解密标准（也称为 Rijndael）.
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher) ) - 对称密钥分组密码，由 Bruce Schneier 于 1993 年设计. 该设计的显着特点包括依赖于密钥的 S 盒和高度复杂的密钥调度.

#### Asymmetric encryption

- [DH](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)  - 一种通过公共渠道安全地交换加密密钥的方法. 与 RSA 不同，Diffie-Hellman 密钥交换不是加密，只是两方就共享秘密值达成一致的一种方式. 由于生成的密钥是完全伪随机的，DH 密钥交换可以提供前向保密（https://en.wikipedia.org/wiki/Forward_secrecy）.
- [ECC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography) - 基于有限域椭圆曲线代数结构的公钥密码系统.
- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem) ) - 最早实用的公钥密码系统之一，广泛用于安全数据传输. 在 RSA 中，这种不对称性是基于分解两个大素数的乘积的实际困难，即分解问题.

#### Transform Encryption

- [Transform Encryption (aka Proxy Re-Encryption)](https://docs.ironcorelabs.com/concepts/transform-encryption) - 转换加密使用三个数学相关的密钥：一个用于将明文加密给收件人，第二个用于解密密文，第三个用于转换加密给一个收件人的密文，以便其他收件人可以解密.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5) - Widely used hash function producing a 128-bit hash value. MD5 was initially designed to be used as a cryptographic hash function, but it has been found to suffer from extensive vulnerabilities. It can still be used as a checksum to verify data integrity, but only against unintentional corruption.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1)  - 由 NSA 设计的加密哈希函数.  SHA-1 产生一个 160 位的散列值，称为消息摘要.  SHA-1 对于资金雄厚的对手不再被认为是安全的.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2)  - 由 NSA 设计的散列函数集.  SHA-256 和 SHA-512 是分别使用 32 位和 64 位字计算的新型哈希函数. 它们使用不同的移位量和附加常数，但它们的结构实际上是相同的，仅在轮数上有所不同.

### Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://paragonie.com/blog/2016/05/how-generate-secure-random-numbers-in-various-programming-languages).
- [Password Insecurity](https://www.netlogix.at/news/artikel/password-insecurity-part-1/) - 本文是为所有对密码安全感兴趣的人编写的.
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2016/09/untangling-forget-me-knot-secure-account-recovery-made-simple).

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - 这本书涵盖了密码学中不同任务的许多结构.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) - 现代密码学简介.
- [Applied Cryptography: Protocols, Algorithms and Source Code in C](https://www.wiley.com/en-ie/Applied+Cryptography%3A+Protocols%2C+Algorithms+and+Source+Code+in+C%2C+20th+Anniversary+Edition-p-9781119439028) - 这个密码学经典为您提供现代密码学的全面调查. 
- [Crypto101](https://www.crypto101.io/) - Crypto 101 是密码学的入门课程.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - 学习构建适用于现实世界的加密协议.
- [Handbook of Applied Cryptography](https://cacr.uwaterloo.ca/hac/) - 本书旨在为专业密码学家提供参考.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) - 从现代计算机科学的角度编写的密码学入门级处理.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - 关于 OpenSSL 的书.
- [Practical Cryptography for Developers](https://cryptobook.nakov.com) - 开发人员友好的现代密码学书籍（哈希、MAC 码、对称和非对称密码、密钥交换、椭圆曲线、数字签名），包含大量代码示例.
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography/) - 本书教您应用密码技术来理解和应用系统和应用程序各个级别的安全性.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - 剑桥大学计算机安全教授罗斯·​​安德森（Ross Anderson）写了一本非凡的教科书.
- [Serious Cryptography](https://nostarch.com/seriouscrypto) - Jean-Philippe Aumasson 的现代加密实用介绍.
- [The Code Book](https://simonsingh.net/books/the-code-book/)  - 这本书是密码学历史的摘要，涵盖了古代和较新的密码学方法. 最后有练习，解决这些问题的奖励是 10.000 美元.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) - 这本书提供了有关计算机和互联网安全的各种主题的综合指南.
- [Understanding Cryptography](http://www.crypto-textbook.com/)  - 这本书经常被忽视，是该领域初学者的福音. 每章末尾都包含大量练习，旨在强化概念和巩固思想.

### Courses

- [A Self-Study Course In Block-Cipher Cryptanalysis](https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf) - 本文试图以一种学生可以用来学习密码分析技术和破解算法的方式来组织现有的分组密码密码分析文献，作者 Bruce Schneier.
- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387)  - 密码学存在于日常生活中，从使用信用卡支付到使用电话. 了解有关在计算中制作和破解难题的所有信息.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) - 本次演讲将涵盖广泛部署的系统中的加密漏洞，以及最小的疏忽如何导致灾难.
- [Cryptography](https://www.coursera.org/learn/cryptography) - 马里兰大学帕克分校的密码学实用课程.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography)  - 本课程解释密码原语的内部工作原理以及如何正确使用它们. 学生将学习如何推理密码结构的安全性以及如何将这些知识应用于实际应用.
- [Cryptography I](https://www.coursera.org/learn/crypto)  - 本课程首先详细讨论了当强大的对手窃听和篡改流量时，拥有共享密钥的两方如何安全通信. 我们将检查许多已部署的协议并分析现有系统中的错误.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) - 这个在线课程我们将介绍密码学如何成为安全的基石，以及如何通过使用不同的加密方法（如密码、公钥或私钥）来保护私人或敏感信息免受未经授权的访问.
- [Harvard's Cryptography Lecture notes](https://intensecrypto.org/) - 介绍性但节奏快的本科/研究生密码学入门课程，用于哈佛 CS 127.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) - 可汗学院的密码学课程.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) - 现代密码学的实用方面，2006 年冬季，华盛顿大学 CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) - 现代密码学简介、在实践中和在 Google 中使用密码学、安全性证明和安全定义以及密码学专题.

### Other lists

- [Awesome crypto-papers](https://github.com/pFarb/awesome-crypto-papers) – 加密论文、文章、教程和操作指南的精选列表.
- [Awesome HE](https://github.com/jonaschn/awesome-he) – A curated list of homomorphic encryption libraries, software and resources.

## Tools

### Standalone

- [Bcrypt](http://bcrypt.sourceforge.net/) - 跨平台文件加密实用程序.
- [blackbox](https://github.com/StackExchange/blackbox) - 在 Git/Mercurial/Subversion 中安全地存储秘密.
- [certbot](https://github.com/certbot/certbot)  - 以前的 Let&#39;s Encrypt 客户端是 EFF 从 Let&#39;s Encrypt 获取证书的工具，并且（可选）在您的服务器上自动启用 HTTPS. 它还可以充当任何其他使用 ACME 协议的 CA 的客户端.
- [Coherence](https://github.com/liesware/coherence/) - 现代网络应用程序的加密服务器.
- [cryptomator](https://github.com/cryptomator/cryptomator) - 云中文件的多平台透明客户端加密.
- [Databunker](https://databunker.org/) - 为符合 GDPR 和 CCPA 而构建的基于 API 的个人数据或 PII 存储服务.
- [gpg](https://www.gnupg.org/)  - OpenPGP 标准的完整和免费实施. 它允许对您的数据和通信进行加密和签名，具有多功能的密钥管理系统.  GnuPG 是一个命令行工具，具有易于与其他应用程序集成的功能.
- [ironssh](https://github.com/IronCoreLabs/ironssh)  - 使用 sftp/scp 对传输的文件进行端到端加密，并有选择地与他人共享. 自动密钥管理适用于任何 SSH 服务器. 加密文件与 gpg 兼容.
- [Nipe](https://github.com/GouveaHeitor/nipe) - Nipe 是一个脚本，可让 Tor 网络成为您的默认网关.
- [sops](https://github.com/mozilla/sops) - sops 是加密文件的编辑器，支持 YAML、JSON 和 BINARY 格式，并使用 AWS KMS、GCP KMS、Azure Key Vault 和 PGP 进行加密.
- [ves](https://ves.host/docs/ves-util) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过病毒性朋友网络安全恢复.

### Plugins

#### Git

- [git-crypt](https://github.com/AGWA/git-crypt) - git 中的透明文件加密.
- [git-secret](https://sobolevn.github.io/git-secret/) - 用于将您的私人数据存储在 git 存储库中的 Bash 工具.

### Playgrounds

- [Cryptography Playground](https://vishwas1.github.io/crypto/index.html#/crypto) - 一个简单的网络工具，用于玩和学习密码学的基本概念，如散列、对称、非对称、zkp 等.

## Frameworks and Libs

### C

- [crypto-algorithms](https://github.com/B-Con/crypto-algorithms) - 标准加密算法的基本实现，如 AES 和 SHA-1.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - 作为 GnuPG 的独立模块开发的密码库.
- [libkcapi](https://github.com/smuellerDD/libkcapi) - Linux 内核加密 API 用户空间接口库.
- [libsodium](https://github.com/jedisct1/libsodium) - 现代且易于使用的加密库.
- [libtomcrypt](https://github.com/libtom/libtomcrypt) - 相当全面、模块化和可移植的加密工具包.
- [libVES.c](https://github.com/vesvault/libVES.c) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过病毒性朋友网络安全恢复.
- [milagro-crypto-c](https://github.com/apache/incubator-milagro-crypto-c)  - 小型、独立且快速的开源加密库. 它支持 RSA、ECDH、ECIES、ECDSA、AES-GCM、SHA2、SHA3 和基于配对的密码学.
- [monocypher](https://monocypher.org) - 受 libsodium 和 TweetNaCl 启发的小型、便携、易于使用的加密库.
- [NaCl](https://nacl.cr.yp.to/) - 用于网络通信、加密、解密、签名等的高速库.
- [nettle](https://github.com/gnutls/nettle) - 是一个密码库，旨在轻松适应或多或少的任何上下文：在面向对象语言（C++、Python、Pike 等）的加密工具包中，在 LSH 或 GNUPG 等应用程序中，甚至在内核空间中.
- [OpenSSL](https://github.com/openssl/openssl) - TLS/SSL 和加密库.
- [PolarSSL](https://tls.mbed.org/) - PolarSSL 使开发人员可以轻松地在其（嵌入式）产品中包含加密和 SSL/TLS 功能，从而以最小的编码占用空间促进此功能.
- [RHash](https://github.com/rhash/RHash) - 计算哈希和的强大工具.
- [themis](https://github.com/cossacklabs/themis) - High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption). Ported on many languages and platforms, suitable for client-server infastructures.
- [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) - C 中的小型便携式 AES128.
- [wolfSSL](https://github.com/wolfSSL/wolfssl) - 小型、快速、可移植的 TLS/SSL 实施，用于将嵌入式设备移植到云端.
- [XKCP](https://github.com/XKCP/XKCP) — 是一个存储库，它收集了 Keccak 团队定义的加密方案的不同免费和开源实现.
- [xxHash](https://github.com/Cyan4973/xxHash) - 极快的哈希算法.

### C++

- [=nil; Crypto3](https://github.com/NilFoundation/crypto3) - C++17 中的现代密码学套件（完整的应用密码学套件，从分组密码开始，到阈值密码学、zk 证明系统等结束）.
- [Botan](https://botan.randombit.net/) - 用“C++11”编写的密码库.
- [cryptopp](https://github.com/weidai11/cryptopp) - Crypto++ Library 是一个免费的 C++ 加密方案类库.
- [HElib](https://github.com/shaih/HElib) - 实现同态加密 (HE) 的软件库.
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - 低级密码库.
- [s2n](https://github.com/awslabs/s2n) - 实施 TLS/SSL 协议.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) - 通用加密库.
- [libsodium-net](https://github.com/adamcaudill/libsodium-net) - 安全加密库，.NET 的 libsodium 端口.
- [Microsoft .NET Framework Cryptography Model](https://docs.microsoft.com/en-us/dotnet/standard/security/cryptography-model) - 许多标准加密算法的 .NET Framework 实现.
- [PCLCrypto](https://github.com/AArnott/PCLCrypto) - Provides cryptographic APIs over algorithms implemented by the platform, including exposing them to portable libraries.
- [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) - .NET crypto done right.
- [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - 使用 libsodium 和 protobuf 进行流加密和解密.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) - 加密 API.
- [clj-crypto](https://github.com/macourtney/clj-crypto/) - 充气城堡的包装.
- [pandect](https://github.com/xsc/pandect) - Clojure 的快速且易于使用的消息摘要、校验和和 HMAC 库.
- [secrets.clj](https://github.com/lk-geimfari/secrets.clj) - 一个 Clojure 库，旨在生成适用于管理数据（如密码、帐户身份验证、安全令牌和相关机密）的加密强随机数.

### Common Lisp

- [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) - 常用密码学功能的集合.
- [ironclad](http://method-combination.net/lisp/ironclad/) - 常用加密快捷方式的集合.
- [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) - Common Lisp 的 SSH 客户端库（基于 libssh2 构建）.

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) - Delphi 的密码库.
- [LockBox](https://sourceforge.net/projects/tplockbox/) - LockBox 3 是一个用于密码学的 Delphi 库.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - 快速加密例程（散列和密码），实现 AES、XOR、RC4、ADLER32、MD5、SHA1、SHA256 算法，针对速度进行了优化.
- [TForge](https://bitbucket.org/sergworks/tforge) - TForge 是用 Delphi 编写的开源加密库，与 FPC 兼容.

### Elixir

- [cipher](https://github.com/rubencaro/cipher) - Elixir 加密库，用于加密/解密任意二进制文件.
- [cloak](https://github.com/danielberkompas/cloak) - Cloak 使使用 Ecto 加密变得容易.
- [comeonin](https://github.com/elixircnx/comeonin) - Elixir 的密码授权 (bcrypt) 库.
- [elixir-rsa](https://github.com/trapped/elixir-rsa) - `:public_key` Elixir 的加密包装器.
- [elixir_tea](https://github.com/keichan34/elixir_tea) - Elixir 中的 TEA 实施.
- [ex_crypto](https://github.com/ntrepid8/ex_crypto)  - Erlang `:crypto` 和 `:public_key` 模块的 Elixir 包装器. 为许多加密函数提供合理的默认值，使其更易于使用.
- [exgpg](https://github.com/rozap/exgpg) - 使用 Elixir 的 gpg.
- [pot](https://github.com/yuce/pot) - Erlang 库，用于生成与 Google Authenticator 兼容的一次性密码.
- [siphash-elixir](https://github.com/zackehh/siphash-elixir) - SipHash 哈希系列的 Elixir 实现.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) - 用于计算消息摘要的函数，以及用于加密和解密的函数.
- [public_key](http://erlang.org/doc/man/public_key.html) - 提供处理公钥基础设施的功能.

### Go

- [crypto](https://golang.org/pkg/crypto/) - 官方网站资源.
- [cryptoballot](https://github.com/cryptoballot/cryptoballot) - 加密安全的在线投票.
- [dedis/crypto](https://github.com/dedis/crypto) - Go 语言的高级加密库.
- [dkeyczar](https://github.com/dgryski/dkeyczar) - 将 Google 的 Keyczar 密码库移植到 Go.
- [gocrypto](https://github.com/kisom/gocrypto) - Practical Crypto with Go 书的示例源代码.
- [goThemis](https://github.com/cossacklabs/themis/wiki/Go-Howto) - Go wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).


### Haskell

- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) - 协作黑客列表.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) - Haskell 官方网站.
- [cryptol](https://github.com/GaloisInc/cryptol) - 密码学语言.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) - 加密原语的 Haskell 存储库.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) - Haskel 的 OpenSSL 绑定.
- [scrypt](https://github.com/informatikr/scrypt) - Haskell 绑定到 Colin Percival 的 scrypt 实现.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) - Haxe 密码库.

### JavaScript

- [asmCrypto](https://github.com/vibornoff/asmcrypto.js/) - 考虑性能的流行加密实用程序的 JavaScript 实现.
- [bcrypt-Node.js](https://github.com/shaneGirish/bcrypt-Node.js) - Node.js 的 bcrypt 的本机实现.
- [cifre](https://github.com/openpeer/cifre) - 用于现代客户端 JavaScript 的快速加密工具包.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) - Google 的通用 JavaScript 库.
- [cryptico](https://github.com/wwwtyro/cryptico) - 使用 RSA 和 AES for JavaScript 的易于使用的加密系统.
- [crypto-js](https://github.com/brix/crypto-js) - 加密标准的 JavaScript 库.
- [cryptojs](https://github.com/gwjjeff/cryptojs) - 为 Node.js 提供标准和安全的加密算法.
- [forge](https://github.com/digitalbazaar/forge) - JavaScript 中 TLS 的本机实现以及用于编写基于加密和网络密集型 Web 应用程序的工具.
- [IronNode](https://docs.ironcorelabs.com/ironnode-sdk/overview) - 转换加密库，代理重新加密的一种变体，用于对用户或组进行加密，并轻松为 Node.js 应用程序添加强大的数据控制.
- [IronWeb](https://docs.ironcorelabs.com/ironweb-sdk/overview) - 转换加密库，一种代理重新加密的变体，用于在浏览器中轻松安全地管理端到端加密.
- [javascript-crypto-library](https://github.com/clipperz/javascript-crypto-library) - JavaScript Crypto Library 为 Web 开发人员提供了一套广泛而高效的加密功能.
- [js-nacl](https://github.com/tonyg/js-nacl) - 用于 Emscripten 编译的 libsodium 例程的纯 JavaScript 高级 API.
- [jsencrypt](https://github.com/travist/jsencrypt) - 用于执行 OpenSSL RSA 加密、解密和密钥生成的 JavaScript 库.
- [JShashes](https://github.com/h2non/jshashes) - 适用于 Node.js 和浏览器的快速且无依赖的加密哈希库（支持 MD5、SHA1、SHA256、SHA512、RIPEMD、HMAC）.
- [jsrsasign](https://github.com/kjur/jsrsasign) - “jsrsasign”（RSA 签名 JavaScript 库）是一个支持 RSA/RSAPSS/ECDSA/DSA 签名/验证的开源免费密码库.
- [jsThemis](https://github.com/cossacklabs/themis/wiki/Nodejs-Howto) - JavaScript wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [libsodium.js](https://github.com/jedisct1/libsodium.js) - libsodium 编译为纯 JavaScript，带有方便的包装器.
- [libVES.js](https://github.com/vesvault/libVES) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过病毒性朋友网络安全恢复.
- [milagro-crypto-js](https://github.com/apache/incubator-milagro-crypto-js)  - MCJS 是一个符合标准的 JavaScript 加密库，除了随机种子源之外没有外部依赖项. 兼容 Node.js 和浏览器. 它支持 RSA、ECDH、ECIES、ECDSA、AES-GCM、SHA2、SHA3、基于配对的密码学和新希望.
 - 高贵 - 高安全性、易于审计的一组包含的密码库和工具. 每个零依赖.
  - [noble-bls12-381](https://github.com/paulmillr/noble-bls12-381) — BLS12-381 配对友好曲线（阈值信号）.
  - [noble-ed25519](https://github.com/paulmillr/noble-ed25519) — ed25519 曲线 + ristretto255（加密，签名）.
  - [noble-ripemd160](https://github.com/paulmillr/noble-ripemd160) — RIPEMD160 哈希.
  - [noble-secp256k1](https://github.com/paulmillr/noble-secp256k1) — secp256k1 Koblitz 曲线（加密、ECDH、sigs）.
- [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js) - 适用于 Node.js 的 bcrypt.
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) - JavaScript 的 OpenPGP 实现.
- [PolyCrypt](https://github.com/polycrypt/polycrypt) - WebCrypto API 的纯 JS 实现.
- [rusha](https://github.com/srijs/rusha) - 适用于大型二进制数据的高性能纯 JavaScript SHA1 实现，可达到本机速度的一半.
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - 斯坦福 JavaScript 加密库.
- [TweetNaCl.js](https://github.com/dchest/tweetnacl-js) - 用于现代浏览器和 Node.js 的 JavaScript 的 TweetNaCl / NaCl 端口.
- [URSA](https://github.com/quartzjer/ursa) - Node 的 RSA 公钥/私钥 OpenSSL 绑定.


### Java

- [Apache Shiro](http://shiro.apache.org/) - 执行身份验证、授权、加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html)  - 通用加密库.  JCA 提供者，从基本助手到 PGP/SMIME 操作的广泛功能.
- [Flexiprovider](http://www.flexiprovider.de/) - 用于 Java 密码体系结构的强大工具包.
- [GDH](https://github.com/maxamel/GDH) - 在 Vert.x 框架之上为多方构建的通用 Diffie-Hellman 密钥交换 Java 库.
- [Google Keyczar](https://github.com/google/keyczar) - 易于使用且安全的加密框架，带有密钥版本控制.
- [Google Tink](https://github.com/google/tink) - 一个小型加密库，提供安全、简单、敏捷和快速的方式来完成一些常见的加密任务.
- [Java Themis](https://github.com/cossacklabs/themis/wiki/Java-and-Android-Howto) - Java/Android wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [jbcrypt](http://www.mindrot.org/projects/jBCrypt/) - jBCrypt 是 OpenBSD Blowfish 密码散列的实现
algorithm.
- [Keycloak](https://github.com/keycloak/keycloak) - 现代应用程序和服务的开源身份和访问管理.
- [keywhiz](https://github.com/square/keywhiz) - 用于分发和管理机密的系统.
- [pac4j](https://github.com/pac4j/pac4j) - 安全引擎.
- [Password4j](https://github.com/Password4j/password4j) - 一个 Java 用户友好的密码库，用于使用不同的密钥派生函数 (KDF) 和密码哈希函数 (CHF) 散列和检查密码.
- [Project Kalium](http://abstractj.github.io/kalium/) - Java 绑定到网络和密码学 (NaCl) 库，具有令人敬畏的 libsodium.
- [scrypt](https://github.com/wg/scrypt) - scrypt 密钥派生函数的纯 Java 实现和 C 实现的 JNI 接口，包括 SSE2 优化版本.
- [securitybuilder](https://github.com/tersesystems/securitybuilder) - 用于 JCA/JSSE 对象的 Fluent Builder API.



### Julia

- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) - 包装 OpenSSL 的库，但也有纯 Julia 实现供参考.
- [MbedTLS.jl](https://github.com/JuliaWeb/MbedTLS.jl) - 包装 mbed TLS 和密码学 C 库.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) - 围绕荨麻加密散列的 Julia 包装器/
加密库提供 MD5、SHA1、SHA2 散列和 HMAC 功能，以及 AES 加密/解密.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) - 高性能、100% 原生 julia SHA1、SHA2-{224,256,384,512} 实现.

### Lua

- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - 用纯 Lua 编写的加密原语的集合.
- [LuaCrypto](https://github.com/mkottman/luacrypto) - Lua 绑定到 OpenSSL.

### OCaml

- [Digestif](https://github.com/mirage/digestif) - 是一个在 C 和 OCaml 中实现各种加密原语的工具箱.
- [ocaml-tls](https://github.com/mirleft/ocaml-tls) - 纯 OCaml 中的 TLS.

### Objective-C

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - AES、MD5、SHA1、SHA224、SHA256、SHA384、SHA512、Base64、十六进制.
- [ObjC Themis](https://github.com/cossacklabs/themis/wiki/Objective-C-Howto) - ObjC wrapper on Themis for iOS and macOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [ObjectivePGP](https://github.com/krzyzanowskim/ObjectivePGP)  - ObjectivePGP 是适用于 iOS 和 macOS 的 OpenPGP 协议的实现.  OpenPGP 是使用最广泛的电子邮件加密标准.
- [RNCryptor](https://github.com/RNCryptor/RNCryptor) - 适用于 iOS 和 Mac 的 CCCryptor（AES 加密）包装器.


### PHP

- [halite](https://paragonie.com/project/halite) - 使用“libsodium”进行加密的简单库.
- [libsodium-laravel](https://github.com/scrothers/libsodium-laravel) - 使用 `libsodium` 的 Laravel 包抽象.
- [PHP Encryption](https://github.com/defuse/php-encryption) - 在 PHP 中使用密钥或密码加密数据的库.
- [PHP Themis](https://github.com/cossacklabs/themis/wiki/PHP-Howto) - PHP wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [TCrypto](https://github.com/timoh6/TCrypto) - TCrypto 是一个简单灵活的 PHP 5.3+ 内存键值存储库.

### Python

- [bcrypt](https://github.com/pyca/bcrypt) - 您的软件和服务器的现代密码散列.
- [charm](https://github.com/JHUISI/charm) - 快速原型密码系统的框架.
- [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) - 用于数字签名的抗量子非对称密钥生成工具.
- [cryptography](https://cryptography.io/en/latest/) - 公开密码配方和原语的 Python 库.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) - 加密算法和应用程序的纯 python 实现.
- [django-cryptography](https://github.com/georgemarshall/django-cryptography) - 在 Django 中轻松加密数据.
- [ecdsa](https://github.com/tlsfuzzer/python-ecdsa) - 易于使用的 ECC 实施，支持 ECDSA 和 ECDH.
- [hashids](https://github.com/davidaurelio/hashids-python) - 实施 [hashids](http://hashids.org) 在 Python 中.
- [paramiko](http://www.paramiko.org/) - SSHv2 协议的 Python 实现，提供客户端和服务器功能.
- [Privy](https://github.com/ofek/privy) - 一个简单、快速的库，可正确密码保护您的数据.
- [pycryptodome](https://github.com/Legrandin/pycryptodome) - 低级加密原语的自包含 Python 包.
- [PyElliptic](https://github.com/yann2192/pyelliptic)  - Python OpenSSL 包装器. 适用于 ECC、AES、HMAC、Blowfish 的现代密码学.
- [pynacl](https://github.com/pyca/pynacl) - Python 绑定到网络和密码学 (NaCl) 库.
- [pythemis](https://github.com/cossacklabs/themis/wiki/Python-Howto) - Python wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### R

- [rscrypt](https://github.com/rstudio/rscrypt) - 用于 scrypt 加密函数集合的包.

### Ruby

- [bcrypt-ruby](https://github.com/codahale/bcrypt-ruby) - OpenBSD bcrypt() 密码散列算法的 Ruby 绑定，允许您轻松存储用户密码的安全散列.
- [RbNaCl](https://github.com/cryptosphere/rbnacl) - Ruby 绑定到网络和密码学 (NaCl) 库.
- [Ruby Themis](https://github.com/cossacklabs/themis/wiki/Ruby-Howto) - Ruby wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### Rust

- [BLAKE3](https://github.com/BLAKE3-team/BLAKE3) - 是 BLAKE3 加密哈希函数的官方 Rust 和 C 实现.
- [dalek cryptography](https://github.com/dalek-cryptography/) - 用于 ECC、Bulletproofs 等的快速而安全的中级 API.
- [mundane](https://github.com/google/mundane) - 是一个由 BoringSSL 支持的 Rust 密码库，它难以误用、符合人体工程学且性能卓越.
- [ockam](https://github.com/ockam-network/ockam) - 是一个用于端到端加密和相互身份验证的 Rust 库.
- [octavo](https://github.com/libOctavo/octavo) - 高度模块化和可配置的哈希和加密库.
- [proteus](https://github.com/wireapp/proteus) - Rust 中的 Axolotl 协议实现，没有标头键.
- [rage](https://github.com/str4d/rage) - 是一个简单、现代、安全的文件加密工具，使用年龄格式. 
- [recrypt](https://github.com/IronCoreLabs/recrypt-rs) - 一个纯 Rust 库，它实现了用于构建多跳代理重加密方案的加密原语，称为转换加密.
- [ring](https://github.com/briansmith/ring) - 使用 Rust 和 BoringSSL 的加密原语的安全、快速、小型加密.
- [rust-crypto](https://github.com/DaGenix/rust-crypto) - 主要是各种加密算法的纯 Rust 实现.
- [rust-openssl](https://github.com/sfackler/rust-openssl) - Rust 的 OpenSSL 绑定.
- [rustls](https://github.com/ctz/rustls) - Rustls 是一个用 Rust 编写的新的现代 TLS 库.
- [sodiumoxide](https://github.com/dnaq/sodiumoxide) - 氧化钠：Rust 的快速密码库（绑定到 libsodium）.
- [suruga](https://github.com/klutzy/suruga) - Rust 中的 TLS 1.2 实现.
- [webpki](https://github.com/briansmith/webpki) - Rust 中的 Web PKI TLS X.509 证书验证.

### Scala

- [recrypt](https://github.com/IronCoreLabs/recrypt) - 为 Scala 转换加密库.
- [scrypto](https://github.com/input-output-hk/scrypto) - Scala 的加密原语.
- [tsec](https://github.com/jmcardon/tsec) - 一个类型安全、功能强大、通用的安全和密码库.

### Swift

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - 以 Swift 编程语言实现的 Swift 加密相关函数和助手.
- [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - 苹果的包装器 [CommonCrypto](https://opensource.apple.com/source/CommonCrypto/) 用 Swift 编写的库.
- [OpenSSL](https://github.com/Zewo/OpenSSL) - 用于 macOS 和 Linux 的 Swift OpenSSL.
- [SweetHMAC](https://github.com/jancassio/SweetHMAC) - 小巧且易于使用的 Swift 类，使用 HMAC 算法加密字符串.
- [Swift-Sodium](https://github.com/jedisct1/swift-sodium) - Sodium 库的 Swift 接口，用于 iOS 和 macOS 的常见加密操作.
- [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - Swift 中优雅的加密工具包.
- [SwiftThemis](https://github.com/cossacklabs/themis/wiki/Swift-Howto) - Swift wrapper on Themis for iOS and macOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

## Resources

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) - 关于加密的一些随机想法.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/)  - 布里斯托大学密码学研究小组的官方博客. 这是一个小组博客，主要针对密码学家和密码学学生.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) - WebCrypto 博客文章.
- [Root Labs rdist](https://rdist.root.org/) - Nate Lawson 和他的合著者撰写了各种主题，包括硬件实现、密码计时攻击、DRM 和 Commodore 64.
- [Salty Hash](https://blog.ironcorelabs.com) - 涵盖有关加密、数据控制、隐私和安全的主题.
- [Schneier on security](https://www.schneier.com/)  - 最古老和最著名的安全博客之一.  Bruce 涵盖了从分组密码分析到机场安全的主题.

### Mailing lists

- [metzdowd.com](http://www.metzdowd.com/mailman/listinfo/cryptography) - “密码学”是一个低噪音的邮件列表，专门讨论密码技术及其政治影响.
- [Modern Crypto](https://moderncrypto.org/) - 讨论现代密码实践的论坛.
- [randombit.net](https://lists.randombit.net/mailman/listinfo/cryptography) - 密码学的一般讨论列表，特别是技术方面.

### Web-tools

- [Boxentriq](https://www.boxentriq.com/code-breaking) - 易于使用的工具，用于分析和破解最常见的密码，包括 Vigenère、Beaufort、Keyed Caesar、Transposition Ciphers 等.
- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) - 是一套密码学相关的工具.
- [CrypTool](http://www.cryptool-online.org/) - 介绍了种类繁多的密码、加密方法和分析工具，通常附有插图.
- [CyberChef](https://gchq.github.io/CyberChef/) - 用于加密、编码、压缩和数据分析的网络应用程序.
- [factordb.com](http://factordb.com/) - Factordb.com 是用于存储任意数量的已知因式分解的工具.
- [keybase.io](https://keybase.io/) - Keybase 将您的身份映射到您的公钥，反之亦然.

### Web-sites

- [Applied Crypto Hardening](https://bettercrypto.org/) - 大量准备好使用最佳实践示例来保护 Web 服务器等.
- [Cryptocurrencies Dashboard](https://dashboard.nbshare.io/apps/reddit/top-crypto-subreddits/) - Reddit 上讨论的最活跃加密货币的仪表板.
- [Cryptography Stackexchange](http://crypto.stackexchange.com/) - Cryptography Stack Exchange 是一个面向软件开发人员、数学家和其他对密码学感兴趣的人的问答网站.
- [Cryptohack](https://cryptohack.org/) - 一个具有许多交互式密码学挑战的平台，类似于 Cryptopals.
- [Cryptopals Crypto Challenges](http://cryptopals.com/) - 一系列应用密码学挑战，从非常基本的挑战开始，例如十六进制到基数 64 挑战，逐渐增加难度直到抽象代数.
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) - 密码学概述.
- [IACR](https://www.iacr.org/) - 国际密码学研究协会是一个非营利性科学组织，其目的是进一步研究密码学和相关领域.
- [Learn Cryptography](https://learncryptography.com/) - 致力于帮助人们了解他们每天使用加密系统的方式和原因，而没有意识到保护和保护他们的隐私的工作.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) - 此 subreddit 旨在围绕强密码学的理论和实践进行链接和讨论.
- [TikZ for Cryptographers](https://www.iacr.org/authors/tikz/) - 一组用 TikZ 绘制的常用密码函数框图，用于用 LaTeX 编写的研究论文和演示文稿.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) - 本规范描述了用于在 Web 应用程序中执行基本加密操作的 JavaScript API，例如散列、签名生成和验证以及加密和解密.

## Contributing

随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) 第一的.

## License

`awesome-cryptography` by [@sobolevn](https://github.com/sobolevn)

在法律可能的范围内，将 CC0 与
`awesome-cryptography` 已放弃所有版权和相关或相邻
&#39;真棒密码学&#39;的权利.

您应该已经收到 CC0 法律代码的副本以及此
工作. 如果没有，请参阅 [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/).
