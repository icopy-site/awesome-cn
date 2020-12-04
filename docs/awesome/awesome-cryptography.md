<div class="github-widget" data-repo="sobolevn/awesome-cryptography"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <img src="https://raw.githubusercontent.com/sobolevn/awesome-cryptography/master/awesome-crypto.png?raw=true" alt="Awesome Cryptography">
</p>

[![Build Status](https://travis-ci.org/sobolevn/awesome-cryptography.svg)](https://travis-ci.org/sobolevn/awesome-cryptography) [![Join the chat at https://gitter.im/sobolevn/awesome-cryptography](https://badges.gitter.im/sobolevn/awesome-cryptography.svg)](https://gitter.im/sobolevn/awesome-cryptography?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Open Source Helpers](https://www.codetriage.com/sobolevn/awesome-cryptography/badges/users.svg)](https://www.codetriage.com/sobolevn/awesome-cryptography)

[![Follow us on twitter](https://img.shields.io/twitter/follow/awe_crypto_bot.svg?style=social&maxAge=0)](https://twitter.com/awe_crypto_bot)

精选的加密资源和链接列表.


<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->


<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) -对称密钥块密码（或三重数据加密算法（TDEA或三重DEA）），它对每个数据块应用三次数据加密标准（DES）密码算法.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) -对称密钥块密码算法和美国政府标准，用于安全和分类数据加密和解密（也称为Rijndael）.
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher) ）-对称密钥分组密码，由Bruce Schneier于1993年设计. 该设计的显着特征包括依赖于密钥的S盒和高度复杂的密钥时间表.

#### Asymmetric encryption

- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem) ）-最早的实用公钥密码系统之一，被广泛用于安全数据传输. 在RSA中，这种不对称性是基于分解两个大质数乘积的实际困难，即分解问题.

#### Transform Encryption

- [Transform Encryption (aka Proxy Re-Encryption)](https://docs.ironcorelabs.com/concepts/transform-encryption) -转换加密使用三个在数学上相关的密钥：一个用于将纯文本加密给接收者，第二个用于解密密文，而第三个将加密的密文转换成一个接收者，以便可以由另一个接收者解密.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5)  -广泛使用的哈希函数可产生128位哈希值.  MD5最初被设计为用作加密哈希函数，但已发现它具有广泛的漏洞. 它仍然可以用作校验和，以验证数据的完整性，但只能防止意外损坏.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1)  -由国家安全局（NSA）设计的加密哈希函数.  SHA-1产生一个160位的哈希值，称为消息摘要.  SHA-1不再被认为能对付资金雄厚的对手.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2)  -由NSA设计的哈希函数集.  SHA-256和SHA-512是分别用32位和64位字计算的新颖哈希函数. 它们使用不同的移位量和加性常数，但是它们的结构实际上是相同的，只是轮数不同.

### Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://paragonie.com/blog/2016/05/how-generate-secure-random-numbers-in-various-programming-languages).
- [Password Insecurity](https://www.netlogix.at/news/artikel/password-insecurity-part-1/) -本文适用于对密码安全性感兴趣的每个人.
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2016/09/untangling-forget-me-knot-secure-account-recovery-made-simple).

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) -本书涵盖了密码学不同任务的许多结构.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) -现代密码学简介.
- [Crypto101](https://www.crypto101.io/) -Crypto 101是密码学入门课程.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) -学习建立可在现实世界中工作的加密协议.
- [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/index.html) -本书仅供专业密码学家参考.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) -从现代计算机科学的角度编写的入门级加密技术.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) -有关OpenSSL的书.
- [Practical Cryptography for Developers](https://cryptobook.nakov.com) -有关现代加密技术（哈希，MAC代码，对称和非对称密码，密钥交换，椭圆曲线，数字签名）的开发人员友好型书籍，其中包含许多代码示例.
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography/) -本书教您应用密码技术来理解和应用系统和应用程序各个级别的安全性.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) -剑桥大学计算机安全教授Ross Anderson写了一本非常特别的教科书.
- [Serious Cryptography](https://nostarch.com/seriouscrypto) -Jean-Philippe Aumasson撰写的《现代加密实用入门》.
- [The Code Book](https://simonsingh.net/books/the-code-book/)  -本书摘录了密码学的历史，涵盖了古代和较新的密码学方法. 最后有练习，而这些练习的解决方案将获得$ 10.000的奖励.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) -本书提供了有关计算机和Internet安全各个主题的全面指南.
- [Understanding Cryptography](http://www.crypto-textbook.com/)  -这本书经常被忽视，对初学者来说是一个福音. 在每章的末尾包含大量练习，目的是加强概念和巩固思想.

### Courses

- [A Self-Study Course In Block-Cipher Cryptanalysis](https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf) -本文试图以布鲁斯·施耐尔（Bruce Schneier）的方式组织现有的块密码密码分析文献，使学生可以学习密码分析技术和破解算法的方法.
- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387)  -从使用信用卡付款到使用电话，日常生活中都存在密码学. 了解有关制作和打破计算难题的所有知识.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) -此次演讲将涵盖广泛部署的系统中的加密漏洞，以及最小的监督如何导致灾难.
- [Cryptography](https://www.coursera.org/learn/cryptography) -马里兰大学公园大学的密码学实用课程.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography)  -本课程说明密码原语的内部工作原理以及如何正确使用它们. 学生将学习如何推理密码结构的安全性，以及如何将此知识应用于实际应用.
- [Cryptography I](https://www.coursera.org/learn/crypto)  -本课程首先详细讨论拥有共享密钥的两个方如何在强大的对手窃听和篡改流量时安全地进行通信. 我们将检查许多已部署的协议并分析现有系统中的错误.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) -本在线课程将介绍加密技术如何成为安全性的基石，以及如何通过使用加密技术（例如密码，公钥或私钥）来保护私钥或敏感信息免受未经授权的访问.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) -可汗学院的密码学课程.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) -现代密码学的实践方面，2006年冬季，华盛顿大学CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) -现代密码学简介，在实践中和在Google上使用密码学，安全性证明和安全性定义以及密码学中的特殊主题.

### Other lists

- [Awesome crypto-papers](https://github.com/pFarb/awesome-crypto-papers) –精选的密码学论文，文章，教程和howtos清单.
- [Awesome HE](https://github.com/jonaschn/awesome-he) –同构加密库，软件和资源的精选列表.

## Tools

### Standalone

- [Bcrypt](http://bcrypt.sourceforge.net/) -跨平台文件加密实用程序.
- [blackbox](https://github.com/StackExchange/blackbox) -将机密安全存储在Git / Mercurial / Subversion中.
- [certbot](https://github.com/certbot/certbot)  -以前是Let&#39;s Encrypt Client，是EFF的工具，用于从Let&#39;s Encrypt获取证书，并（可选）在服务器上自动启用HTTPS. 它也可以充当使用ACME协议的任何其他CA的客户端.
- [Coherence](https://github.com/liesware/coherence/) -用于现代Web应用程序的加密服务器.
- [cryptomator](https://github.com/cryptomator/cryptomator) -云中文件的多平台透明客户端加密.
- [gpg](https://www.gnupg.org/)  -完全免费地实施OpenPGP标准. 它允许对数据和通信进行加密和签名，并具有通用的密钥管理系统.  GnuPG是一种命令行工具，具有易于与其他应用程序集成的功能.
- [ironssh](https://github.com/IronCoreLabs/ironssh)  -使用sftp / scp端到端加密传输的文件，并选择性地与他人共享. 自动密钥管理可用于任何SSH服务器. 加密文件与gpg兼容.
- [Nipe](https://github.com/GouveaHeitor/nipe) -Nipe是一个使Tor Network成为默认网关的脚本.
- [sops](https://github.com/mozilla/sops) -sops是加密文件的编辑器，支持YAML，JSON和BINARY格式，并使用AWS KMS，GCP KMS，Azure Key Vault和PGP进行加密.
- [ves](https://ves.host/docs/ves-util) -通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络安全恢复.

### Plugins

#### Git

- [git-crypt](https://github.com/AGWA/git-crypt) -git中的透明文件加密.
- [git-secret](https://sobolevn.github.io/git-secret/) -Bash工具将您的私人数据存储在git存储库中.

### Playgrounds

- [Cryptography Playground](https://vishwas1.github.io/crypto/index.html#/crypto) -一个简单的网络工具，可播放和学习密码学的基本概念，例如哈希，对称，非对称，zkp等.

## Frameworks and Libs

### C

- [crypto-algorithms](https://github.com/B-Con/crypto-algorithms) -标准加密算法（如AES和SHA-1）的基本实现.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) -作为GnuPG的独立模块开发的密码库.
- [libsodium](https://github.com/jedisct1/libsodium) -现代且易于使用的加密库.
- [libtomcrypt](https://github.com/libtom/libtomcrypt) -非常全面，模块化和便携式的加密工具包.
- [libVES.c](https://github.com/vesvault/libVES.c) -通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络安全恢复.
- [milagro-crypto-c](https://github.com/apache/incubator-milagro-crypto-c)  -小型，独立且快速的开源密码库. 它支持RSA，ECDH，ECIES，ECDSA，AES-GCM，SHA2，SHA3和基于配对的密码术.
- [monocypher](https://monocypher.org) -受libsodium和TweetNaCl启发的小型，便携式，易于使用的加密库.
- [NaCl](https://nacl.cr.yp.to/) -用于网络通信，加密，解密，签名等的高速库.
- [OpenSSL](https://github.com/openssl/openssl) -TLS / SSL和加密库.
- [PolarSSL](https://tls.mbed.org/) -PolarSSL使开发人员在其（嵌入式）产品中轻松包含加密和SSL / TLS功能，从而以最小的代码占用空间简化了该功能.
- [RHash](https://github.com/rhash/RHash) -计算哈希和的强大工具.
- [themis](https://github.com/cossacklabs/themis) - High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption). Ported on many languages and platforms, suitable for client-server infastructures.
- [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) -C型小型便携式AES128.
- [wolfSSL](https://github.com/wolfSSL/wolfssl) -TLS / SSL的小型，快速，便携式实施，可将嵌入式设备连接到云.
- [xxHash](https://github.com/Cyan4973/xxHash) -极快的哈希算法.

### C++

- [Botan](https://botan.randombit.net/) -用C ++ 11编写的密码学库.
- [cryptopp](https://github.com/weidai11/cryptopp) -Crypto ++ Library是一个免费的C ++类密码方案库.
- [HElib](https://github.com/shaih/HElib) -实现同态加密（HE）的软件库.
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) -低级密码库.
- [s2n](https://github.com/awslabs/s2n) -TLS / SSL协议的实现.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) -通用加密库.
- [libsodium-net](https://github.com/adamcaudill/libsodium-net) -安全的密码库，.NET的libsodium端口.
- [Microsoft .NET Framework Cryptography Model](https://docs.microsoft.com/en-us/dotnet/standard/security/cryptography-model) -许多标准密码算法的.NET Framework实现.
- [PCLCrypto](https://github.com/AArnott/PCLCrypto) -通过平台实现的算法提供加密API，包括将其公开给可移植的库.
- [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) -.NET加密正确.
- [StreamCryptor](https://github.com/bitbeans/StreamCryptor) -使用libsodium和protobuf进行流加密和解密.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) -加密API.
- [clj-crypto](https://github.com/macourtney/clj-crypto/) -弹力城堡的包装.
- [pandect](https://github.com/xsc/pandect) -Clojure的快速，易于使用的消息摘要，校验和和HMAC库.
- [secrets.clj](https://github.com/lk-geimfari/secrets.clj) -Clojure库，用于生成密码强的随机数，适用于管理密码，帐户身份验证，安全令牌和相关机密等数据.



### Common Lisp

- [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) -通用密码功能的集合.
- [ironclad](http://method-combination.net/lisp/ironclad/) -常见的加密快捷方式的集合.
- [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) -Common Lisp的SSH客户端库（内置于libssh2）.

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) -Delphi的密码库.
- [LockBox](https://sourceforge.net/projects/tplockbox/) -LockBox 3是用于加密的Delphi库.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) -快速的加密例程（散列和密码），实现AES，XOR，RC4，ADLER32，MD5，SHA1，SHA256算法，并针对速度进行了优化.
- [TForge](https://bitbucket.org/sergworks/tforge) -TForge是用Delphi编写的开源加密货币库，与FPC兼容.

### Elixir

- [cipher](https://github.com/rubencaro/cipher) -Elixir加密库可加密/解密任意二进制文件.
- [cloak](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
- [comeonin](https://github.com/elixircnx/comeonin) -Elixir的密码授权（bcrypt）库.
- [elixir-rsa](https://github.com/trapped/elixir-rsa) -`：public_key` Elixir的加密包装.
- [elixir_tea](https://github.com/keichan34/elixir_tea) -在Elixir中实施TEA.
- [ex_crypto](https://github.com/ntrepid8/ex_crypto)  -Erlang`：crypto`和`：public_key`模块的Elixir包装器. 为许多加密功能提供合理的默认设置，以使其更易于使用.
- [exgpg](https://github.com/rozap/exgpg) -使用Elixir的gpg.
- [pot](https://github.com/yuce/pot) -Erlang库，用于生成与Google Authenticator兼容的一次性密码.
- [siphash-elixir](https://github.com/zackehh/siphash-elixir) -SipHash哈希家族的Elixir实现.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) -用于计算消息摘要的功能，以及用于加密和解密的功能.
- [public_key](http://erlang.org/doc/man/public_key.html) -提供处理公钥基础结构的功能.

### Go

- [crypto](https://golang.org/pkg/crypto/) -官方网站资源.
- [cryptoballot](https://github.com/cryptoballot/cryptoballot) -加密安全的在线投票.
- [dedis/crypto](https://github.com/dedis/crypto) -用于Go语言的高级密码库.
- [dkeyczar](https://github.com/dgryski/dkeyczar) -将Google的Keyczar密码库移植到Go.
- [gocrypto](https://github.com/kisom/gocrypto) -《 Goal实用密码》一书的示例源代码.
- [goThemis](https://github.com/cossacklabs/themis/wiki/Go-Howto) - Go wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).


### Haskell

- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) -协作黑客名单.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) -Haskell的官方网站.
- [cryptol](https://github.com/GaloisInc/cryptol) -密码学的语言.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) -Haskell加密原语存储库.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) - OpenSSL binding for Haskel.
- [scrypt](https://github.com/informatikr/scrypt) -Haskell绑定到Colin Percival的scrypt实现.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) -Haxe密码学图书馆.

### JavaScript

- [asmCrypto](https://github.com/vibornoff/asmcrypto.js/) -考虑性能的流行加密实用程序的JavaScript实现.
- [bcrypt-nodejs](https://github.com/shaneGirish/bcrypt-nodejs) -NodeJS的bcrypt本地实现.
- [cifre](https://github.com/openpeer/cifre) -用于现代客户端JavaScript的快速加密工具包.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) -Google的通用JavaScript库.
- [cryptico](https://github.com/wwwtyro/cryptico) -使用针对javascript的RSA和AES的易于使用的加密系统.
- [crypto-js](https://github.com/brix/crypto-js) -加密标准的JavaScript库.
- [cryptojs](https://github.com/gwjjeff/cryptojs) -为NodeJS提供标准和安全的加密算法.
- [forge](https://github.com/digitalbazaar/forge) -使用Javascript和工具编写TLS的本机实现，以编写基于加密和网络繁重的Web应用程序.
- [IronNode](https://docs.ironcorelabs.com/ironnode-sdk/overview) -转换加密库，一种代理重新加密的变体，用于加密用户或组，并轻松向NodeJS应用添加强大的数据控件.
- [IronWeb](https://docs.ironcorelabs.com/ironweb-sdk/overview) -转换加密库，一种代理重新加密的变体，用于轻松地在浏览器中安全地管理端到端加密.
- [javascript-crypto-library](https://github.com/clipperz/javascript-crypto-library) -JavaScript加密库为Web开发人员提供了广泛而有效的加密功能集.
- [js-nacl](https://github.com/tonyg/js-nacl) -纯Java高级API，用于Emscripten编译的libsodium例程.
- [jsencrypt](https://github.com/travist/jsencrypt) -执行OpenSSL RSA加密，解密和密钥生成的Javascript库.
- [JShashes](https://github.com/h2non/jshashes) - Fast and dependency-free cryptographic hashing library for node.js and browsers (supports MD5, SHA1, SHA256, SHA512, RIPEMD, HMAC).
- [jsrsasign](https://github.com/kjur/jsrsasign) -“ jsrsasign”（RSA-Sign JavaScript库）是一个免费的开源加密库，支持RSA / RSAPSS / ECDSA / DSA签名/验证.
- [jsThemis](https://github.com/cossacklabs/themis/wiki/NodeJS-Howto) - Javascript wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [libsodium.js](https://github.com/jedisct1/libsodium.js) -使用方便的包装程序将libsodium编译为纯JavaScript.
- [libVES.js](https://github.com/vesvault/libVES) -通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络安全恢复.
- - [milagro-crypto-js](https://github.com/apache/incubator-milagro-crypto-js)  -MCJS是符合标准的JavaScript密码库，除了随机种子源外，没有任何外部依赖关系. 兼容nodejs和浏览器. 它支持RSA，ECDH，ECIES，ECDSA，AES-GCM，SHA2，SHA3，基于配对的密码术和New Hope.
 -高贵-包含密码库和工具的高安全性，易于审核的集合. 每个零依赖.
  - [noble-bls12-381](https://github.com/paulmillr/noble-bls12-381) — BLS12-381配对友好曲线（阈值信号）
  - [noble-ed25519](https://github.com/paulmillr/noble-ed25519) — ed25519曲线+ ristretto255（加密，信号）
  - [noble-ripemd160](https://github.com/paulmillr/noble-ripemd160) -RIPEMD160哈希.
  - [noble-secp256k1](https://github.com/paulmillr/noble-secp256k1) — secp256k1 Koblitz曲线（加密，ECDH，信号）
- [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js) -用于NodeJS的bcrypt.
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) -JavaScript的OpenPGP实现.
- [PolyCrypt](https://github.com/polycrypt/polycrypt) -WebCrypto API的纯JS实现.
- [rusha](https://github.com/srijs/rusha) -高性能的纯JavaScript SHA1实现，适用于大型二进制数据，最高可达原始速度的一半.
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) -斯坦福Javascript加密库.
- [URSA](https://github.com/quartzjer/ursa) -节点的RSA公钥/私钥OpenSSL绑定.


### Java

- [Apache Shiro](http://shiro.apache.org/) -执行身份验证，授权，加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html)  -通用加密库.  JCA提供程序，功能广泛，从基本助手到PGP / SMIME操作.
- [Flexiprovider](http://www.flexiprovider.de/) -用于Java密码体系结构的强大工具包.
- [GDH](https://github.com/maxamel/GDH) -通用的Diffie-Hellman密钥交换Java库，用于在Vert.x框架之上构建的多个参与者.
- [Google Keyczar](https://github.com/google/keyczar) -易于使用，但具有密钥版本控制的安全加密框架.
- [Google Tink](https://github.com/google/tink) -一个小型的密码库，提供安全，简单，敏捷和快速的方式来完成一些常见的密码任务.
- [Java Themis](https://github.com/cossacklabs/themis/wiki/Java-and-Android-Howto) - Java/Android wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [jbcrypt](http://www.mindrot.org/projects/jBCrypt/) -jBCrypt是OpenBSD Blowfish密码哈希的实现
algorithm.
- [Keycloak](https://github.com/keycloak/keycloak) -用于现代应用程序和服务的开源身份和访问管理.
- [keywhiz](https://github.com/square/keywhiz) -用于分发和管理机密的系统.
- [pac4j](https://github.com/pac4j/pac4j) -安全引擎.
- [Project Kalium](http://abstractj.github.io/kalium/) -通过libsodium的强大功能将Java绑定到Networking and Cryptography（NaCl）库.
- [scrypt](https://github.com/wg/scrypt) -scrypt密钥派生功能的纯Java实现以及C实现的JNI接口，包括SSE2优化版本.
- [securitybuilder](https://github.com/tersesystems/securitybuilder) -用于JCA / JSSE对象的Fluent Builder API.



### Julia

- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) -包含OpenSSL的库，但也具有纯Julia实现供参考.
- [MbedTLS.jl](https://github.com/JuliaWeb/MbedTLS.jl) -围绕mbed TLS和加密C库的包装器.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) -朱莉娅包装荨麻加密散列/
提供MD5，SHA1，SHA2哈希和HMAC功能以及AES加密/解密的加密库.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) -执行者，100％本机朱莉娅SHA1，SHA2- {224,256,384,512}实现.

### Lua

- [lua-lockbox](https://github.com/somesocks/lua-lockbox) -用纯Lua编写的密码基元的集合.
- [LuaCrypto](https://github.com/mkottman/luacrypto) -Lua绑定到OpenSSL.

### Objective-C

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) -AES，MD5，SHA1，SHA224，SHA256，SHA384，SHA512，Base64，十六进制.
- [ObjC Themis](https://github.com/cossacklabs/themis/wiki/Objective-C-Howto) - ObjC wrapper on Themis for iOS and MacOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [ObjectivePGP](https://github.com/krzyzanowskim/ObjectivePGP)  -ObjectivePGP是针对iOS和macOS的OpenPGP协议的实现.  OpenPGP是使用最广泛的电子邮件加密标准.
- [RNCryptor](https://github.com/RNCryptor/RNCryptor) -适用于iOS和Mac的CCCryptor（AES加密）包装.


### PHP

- [halite](https://paragonie.com/project/halite) -使用`libsodium`进行加密的简单库.
- [libsodium-laravel](https://github.com/scrothers/libsodium-laravel) -使用`libsodium`的Laravel软件包抽象.
- [PHP Encryption](https://github.com/defuse/php-encryption) -在PHP中使用密钥或密码加密数据的库.
- [PHP Themis](https://github.com/cossacklabs/themis/wiki/PHP-Howto) - PHP wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [TCrypto](https://github.com/timoh6/TCrypto) -TCrypto是一个简单灵活的PHP 5.3+内存中键值存储库.

### Python

- [bcrypt](https://github.com/pyca/bcrypt) -您的软件和服务器的现代密码哈希.
- [charm](https://github.com/JHUISI/charm) -用于快速制作密码系统原型的框架.
- [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) -用于数字签名的抗量子非对称密钥生成工具.
- [cryptography](https://cryptography.io/en/latest/) -公开密码配方和原语的Python库.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) -加密算法和应用程序的纯python实现.
- [django-cryptography](https://github.com/georgemarshall/django-cryptography) -在Django中轻松加密数据.
- [hashids](https://github.com/davidaurelio/hashids-python) - 实施 [hashids](http://hashids.org) 在Python中.
- [paramiko](http://www.paramiko.org/) -SSHv2协议的Python实现，同时提供客户端和服务器功能.
- [Privy](https://github.com/ofek/privy) -一个简单，快速的库，可以正确地密码保护您的数据.
- [pycryptodome](https://github.com/Legrandin/pycryptodome) -低级密码原语的自包含Python包.
- [PyElliptic](https://github.com/yann2192/pyelliptic)  -Python OpenSSL包装器. 对于带有ECC，AES，HMAC和Blowfish的现代密码学.
- [pynacl](https://github.com/pyca/pynacl) -将Python绑定到网络和密码（NaCl）库.
- [pythemis](https://github.com/cossacklabs/themis/wiki/Python-Howto) - Python wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### R

- [rscrypt](https://github.com/rstudio/rscrypt) -一组scrypt加密功能的软件包.

### Ruby

- [bcrypt-ruby](https://github.com/codahale/bcrypt-ruby) -用于OpenBSD bcrypt（）密码哈希算法的Ruby绑定，可让您轻松存储用户密码的安全哈希.
- [RbNaCl](https://github.com/cryptosphere/rbnacl) -将Ruby绑定到网络和密码学（NaCl）库.
- [Ruby Themis](https://github.com/cossacklabs/themis/wiki/Ruby-Howto) - Ruby wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### Rust

- [dalek cryptography](https://github.com/dalek-cryptography/) -用于ECC，Bulletproofs等的快速而安全的中级API.
- [octavo](https://github.com/libOctavo/octavo) -高度模块化和可配置的哈希和加密库.
- [proteus](https://github.com/wireapp/proteus) -Rust中没有标题键的Axolotl协议实现.
- [recrypt](https://github.com/IronCoreLabs/recrypt-rs) -一个纯铁锈库，该库实现用于构建多跳代理重新加密方案（称为“转换加密”）的加密原语.
- [ring](https://github.com/briansmith/ring) -使用Rust＆BoringSSL的加密原语进行安全，快速，小型加密.
- [rust-crypto](https://github.com/DaGenix/rust-crypto) -主要是各种加密算法的纯Rust实现.
- [rust-openssl](https://github.com/sfackler/rust-openssl) -用于Rust的OpenSSL绑定.
- [rustls](https://github.com/ctz/rustls) - Rustls is a new, modern TLS library written in Rust.
- [sodiumoxide](https://github.com/dnaq/sodiumoxide) -氧化钠：Rust的快速密码库（与libsodium绑定）.
- [suruga](https://github.com/klutzy/suruga) -Rust中的TLS 1.2实施.
- [webpki](https://github.com/briansmith/webpki) -Rust中的Web PKI TLS X.509证书验证.

### Scala

- [recrypt](https://github.com/IronCoreLabs/recrypt) -转换Scala的加密库.
- [scrypto](https://github.com/input-output-hk/scrypto) -Scala的加密原语.
- [tsec](https://github.com/jmcardon/tsec) -类型安全，功能通用的安全性和加密库.

### Swift

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) -以Swift编程语言实现的与Swift相关的加密功能和帮助程序.
- [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) -苹果的包装 [CommonCrypto](https://opensource.apple.com/source/CommonCrypto/) 用Swift编写的库
- [OpenSSL](https://github.com/Zewo/OpenSSL) -适用于OS X和Linux的Swift OpenSSL.
- [SweetHMAC](https://github.com/jancassio/SweetHMAC) -微小且易于使用的Swift类使用HMAC算法对字符串进行加密.
- [Swift-Sodium](https://github.com/jedisct1/swift-sodium) -与Sodium库的Swift接口，用于iOS和OS X的常见加密操作.
- [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) -Swift中的优雅加密工具包.
- [SwiftThemis](https://github.com/cossacklabs/themis/wiki/Swift-Howto) - Swift wrapper on Themis for iOS and MacOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

## Resources

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) -关于加密的一些随机想法.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/)  -布里斯托大学密码学研究小组的官方博客. 这是一个团体博客，主要针对密码学家和密码学学生.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) -WebCrypto博客文章.
- [Root Labs rdist](https://rdist.root.org/) 内特·劳森（Nate Lawson）和他的合著者写了许多主题，包括硬件实现，加密定时攻击，DRM和Commodore 64.
- [Salty Hash](https://blog.ironcorelabs.com) -涵盖有关加密，数据控制，隐私和安全性的主题.
- [Schneier on security](https://www.schneier.com/)  -最古老，最著名的安全博客之一.  Bruce涵盖了从分组密码加密分析到机场安全的主题.

### Mailing lists

- [metzdowd.com](http://www.metzdowd.com/mailman/listinfo/cryptography) -“密码学”是一种低噪声，经过审核的邮件列表，专门用于加密技术及其政治影响.
- [Modern Crypto](https://moderncrypto.org/) -讨论现代密码实践的论坛.
- [randombit.net](https://lists.randombit.net/mailman/listinfo/cryptography) -密码学一般讨论的列表，特别是技术方面的列表.

### Web-tools

- [Boxentriq](https://www.boxentriq.com/code-breaking) -易于使用的工具，用于分析和解密最常见的密码，包括维格涅尔，博福特，凯撒凯撒，换位密码等.
- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) -是一组与密码相关的工具.
- [CrypTool](http://www.cryptool-online.org/) -经常介绍各种密码，加密方法和分析工具，并附带图解示例.
- [CyberChef](https://gchq.github.io/CyberChef/) -用于加密，编码，压缩和数据分析的网络应用.
- [factordb.com](http://factordb.com/) -Factordb.com是用于存储任意数量的已知分解的工具.
- [keybase.io](https://keybase.io/) -Keybase将您的身份映射到您的公钥，反之亦然.

### Web-sites
- [Applied Crypto Hardening](https://bettercrypto.org/) -准备使用最佳实践示例来保护Web服务器等的安全.
- [Cryptography Stackexchange](http://crypto.stackexchange.com/) -密码学Stack Exchange是软件开发人员，数学家和其他对密码学感兴趣的人的问答网站.
- [Cryptohack](https://cryptohack.org/) -与Cryptopals类似的具有许多交互式密码学挑战的平台.
- [Cryptopals Crypto Challenges](http://cryptopals.com/) -一系列应用密码学挑战，从非常基本的挑战（例如十六进制到基础64个挑战）开始，并逐渐增加难度，直至抽象代数.
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) -密码学概述.
- [IACR](https://www.iacr.org/) -国际密码学研究协会是一个非营利性的科学组织，其目的是进一步研究密码学及相关领域.
- [Learn Cryptography](https://learncryptography.com/) -致力于帮助人们了解他们日常使用的密码系统的方式和原因，而无需实现保护和保护其隐私的工作.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) -此subreddit用于围绕强密码学理论和实践的链接和讨论.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) -本规范描述了一个JavaScript API，用于在Web应用程序中执行基本的加密操作，例如哈希，签名生成和验证以及加密和解密.

## Contributing

永远欢迎您的贡献！ 请看看 [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) 第一.

## License

的“ awesome-cryptography” [@sobolevn](https://github.com/sobolevn)

在法律允许的范围内，将CC0与
`awesome-cryptography`已放弃所有版权及相关或邻近的版权
awesome-cryptography的权利.

您应该已经收到了CC0法律代码的副本以及此副本
工作. 如果没有，请参阅 [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/).
