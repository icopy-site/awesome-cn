<div class="github-widget" data-repo="sobolevn/awesome-cryptography"></div>
## Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <img src="https://raw.githubusercontent.com/sobolevn/awesome-cryptography/master/awesome-crypto.png?raw=true" alt="Awesome Cryptography">
</p>

[![Build Status](https://travis-ci.org/sobolevn/awesome-cryptography.svg)](https://travis-ci.org/sobolevn/awesome-cryptography) [![Join the chat at https://gitter.im/sobolevn/awesome-cryptography](https://badges.gitter.im/sobolevn/awesome-cryptography.svg)](https://gitter.im/sobolevn/awesome-cryptography?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Open Source Helpers](https://www.codetriage.com/sobolevn/awesome-cryptography/badges/users.svg)](https://www.codetriage.com/sobolevn/awesome-cryptography)

[![Follow us on twitter](https://img.shields.io/twitter/follow/awe_crypto_bot.svg?style=social&maxAge=0)](https://twitter.com/awe_crypto_bot)

密码学资源和链接的精选列表.


<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->


<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - 对称密钥分组密码（或三重数据加密算法（TDEA或三重DEA），它将数据加密标准（DES）密码算法应用于每个数据块三次.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - 对称密钥分组密码算法和用于安全和分类数据加密和解密的美国政府标准（也称为Rijndael）.
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher) ） - 对称密钥分组密码，由Bruce Schneier于1993年设计.  该设计的显着特征包括依赖于键的S盒和高度复杂的密钥安排.

#### Asymmetric encryption

- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem) ） - 第一个实用的公钥密码系统之一，广泛用于安全数据传输.  在RSA中，这种不对称性是基于将两个大素数的乘积分解的实际困难，即因子分解问题.

#### Transform Encryption

- [Transform Encryption (aka Proxy Re-Encryption)](https://docs.ironcorelabs.com/concepts/transform-encryption) - 转换加密使用三个数学相关的密钥：一个用于将明文加密到接收者，另一个用于解密密文，第三个用于将加密的密文转换为一个接收者，因此可以由不同的接收者解密.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5)   - 广泛使用的散列函数，产生128位散列值.  MD5最初被设计用作加密哈希函数，但它已被发现存在广泛的漏洞.  它仍可用作校验和来验证数据完整性，但仅用于防止意外损坏.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1)   - 由NSA设计的加密哈希函数.  SHA-1生成160位散列值，称为消息摘要.  对于资金充足的对手，SHA-1不再被认为是安全的.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2)   - 由NSA设计的哈希函数集.  SHA-256和SHA-512是分别用32位和64位字计算的新型散列函数.  它们使用不同的偏移量和附加常数，但它们的结构实际上是相同的，仅在轮数方面不​​同.

### Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://paragonie.com/blog/2016/05/how-generate-secure-random-numbers-in-various-programming-languages).
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2016/09/untangling-forget-me-knot-secure-account-recovery-made-simple).

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - 本书涵盖了密码学中不同任务的许多结构.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) - 现代密码学概论.
- [Crypto101](https://www.crypto101.io/) -  Crypto 101是一门关于密码学的入门课程.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - 学习构建在现实世界中工作的加密协议.
- [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/index.html) - 本书旨在作为专业密码学家的参考.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) - 从现代计算机科学的角度编写的密码学入门级处理.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - 关于OpenSSL的书.
- [Practical Cryptography for Developers](https://cryptobook.nakov.com) - 开发人员友好的现代密码学书籍（哈希，MAC代码，对称和非对称密码，密钥交换，椭圆曲线，数字签名），包含大量代码示例.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - 剑桥大学计算机安全教授罗斯安德森写了一本非凡的教科书.
- [Serious Cryptography](https://nostarch.com/seriouscrypto) -  Jean-Philippe Aumasson对现代加密的实用介绍.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) - 本书提供了有关计算机和互联网安全的各种主题的综合指南.
- [Understanding Cryptography](http://www.crypto-textbook.com/)   - 经常被忽视的是，这本书对初学者来说是一个福音.  它包含了每章末尾的大量练习，旨在强化概念和巩固思想.

### Courses

- [A Self-Study Course In Block-Cipher Cryptanalysis](https://www.schneier.com/academic/paperfiles/paper-self-study.pdf) - 本文试图以一种学生可以用来学习密码分析技术和破解算法的方法来组织现有的分组密码密码分析文献，Bruce Schneier.
- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387)   - 密码学在日常生活中存在，从使用信用卡付款到使用电话.  了解有关在计算中制作和打破谜题的所有信息.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) - 本演讲将讨论广泛部署的系统中的加密漏洞以及最小的监督如何导致灾难.
- [Cryptography](https://www.coursera.org/learn/cryptography) - 马里兰大学帕克分校密码学实践导向课程.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography)   - 本课程介绍了加密原语的内部工作原理以及如何正确使用它们.  学生将学习如何推断加密结构的安全性以及如何将这些知识应用于实际应用.
- [Cryptography I](https://www.coursera.org/learn/crypto)   - 本课程首先详细讨论了当强大的对手窃听和篡改流量时，拥有共享密钥的双方如何能够安全地进行通信.  我们将检查许多已部署的协议并分析现有系统中的错误.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) - 这个在线课程我们将介绍加密技术如何成为安全的基石，以及如何通过使用不同的加密方法（如密码，公钥或私钥），保护私人或敏感信息免受未经授权的访问.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) - 可汗学院的密码学课程.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) - 现代密码学的实践方面，2006年冬季华盛顿大学CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) - 现代密码学简介，在实践和谷歌中使用密码学，安全和安全定义的证明以及密码学中的一个特殊主题.

### Other lists

- [Awesome crypto-papers](https://github.com/pFarb/awesome-crypto-papers) - 密码学论文，文章，教程和howtos的精选列表.
- [Awesome HE](https://github.com/jonaschn/awesome-he) - 同态加密库，软件和资源的精选列表.

## Tools

### Standalone

- [Bcrypt](http://bcrypt.sourceforge.net/) - 跨平台文件加密实用程序.
- [blackbox](https://github.com/StackExchange/blackbox) - 在Git / Mercurial / Subversion中安全地存储秘密.
- [certbot](https://github.com/certbot/certbot)   - 以前的Let&#39;s Encrypt Client是EFF的工具，用于从Let&#39;s Encrypt获取证书，以及（可选）在您的服务器上自动启用HTTPS.  它还可以充当使用ACME协议的任何其他CA的客户端.
- [Coherence](https://github.com/liesware/coherence/) - 用于现代网络应用程序的加密服务器.
- [cryptomator](https://github.com/cryptomator/cryptomator) - 云中文件的多平台透明客户端加密.
- [gpg](https://www.gnupg.org/)   - 完全免费实施OpenPGP标准.  它允许加密和签署您的数据和通信，具有通用的密钥管理系统.  GnuPG是一个命令行工具，具有与其他应用程序轻松集成的功能.
- [ironssh](https://github.com/IronCoreLabs/ironssh)   - 端到端使用sftp / scp加密传输的文件，并有选择地与他人共享.  自动密钥管理适用于任何SSH服务器.  加密文件与gpg兼容.
- [Nipe](https://github.com/GouveaHeitor/nipe) -  Nipe是一个使Tor Network成为默认网关的脚本.
- [sops](https://github.com/mozilla/sops) -  sops是加密文件的编辑器，支持YAML，JSON和BINARY格式，并使用AWS KMS，GCP KMS，Azure Key Vault和PGP进行加密.
- [ves](https://ves.host/docs/ves-util) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络进行安全恢复.

### Plugins

#### Git

- [git-crypt](https://github.com/AGWA/git-crypt) -  git中的透明文件加密.
- [git-secret](https://sobolevn.github.io/git-secret/) - 用于将私有数据存储在git存储库中的Bash工具.

## Frameworks and Libs

### C

- [crypto-algorithms](https://github.com/B-Con/crypto-algorithms) - 标准加密算法的基本实现，如AES和SHA-1.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - 作为GnuPG的独立模块开发的加密库.
- [libsodium](https://github.com/jedisct1/libsodium) - 现代且易于使用的加密库.
- [libtomcrypt](https://github.com/libtom/libtomcrypt) - 相当全面的模块化和便携式加密工具包.
- [libVES.c](https://github.com/vesvault/libVES.c) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络进行安全恢复.
- [monocypher](http://loup-vaillant.fr/projects/monocypher/) - 小巧，便携，易于使用的加密库，受libsodium和TweetNaCl的启发.
- [NaCl](https://nacl.cr.yp.to/) - 用于网络通信，加密，解密，签名等的高速库.
- [OpenSSL](https://github.com/openssl/openssl) -  TLS / SSL和加密库.
- [PolarSSL](https://tls.mbed.org/) -  PolarSSL使开发人员能够轻松地在其（嵌入式）产品中包含加密和SSL / TLS功能，以最小的编码占用空间来实现此功能.
- [RHash](https://github.com/rhash/RHash) - 用于计算哈希值的实用工具.
- [themis](https://github.com/cossacklabs/themis) - High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption). Ported on many languages and platforms, suitable for client-server infastructures.
- [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) -  C中的小型便携式AES128
- [wolfSSL](https://github.com/wolfSSL/wolfssl) - 用于嵌入式设备到云的小型，快速，可移植的TLS / SSL实现.
- [xxHash](https://github.com/Cyan4973/xxHash) - 极快的哈希算法.

### C++

- [Botan](https://botan.randombit.net/) - 用“C ++ 11”编写的密码学库.
- [cryptopp](https://github.com/weidai11/cryptopp) -  Crypto ++ Library是一个加密方案的免费C ++类库.
- [HElib](https://github.com/shaih/HElib) - 实现同态加密（HE）的软件库.
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - 低级加密库.
- [s2n](https://github.com/awslabs/s2n) - 实施TLS / SSL协议.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) - 通用加密库.
- [libsodium-net](https://github.com/adamcaudill/libsodium-net) - 安全加密库，libsodium for .NET端口.
- [Microsoft .NET Framework Cryptography Model](https://docs.microsoft.com/en-us/dotnet/standard/security/cryptography-model) - 许多标准加密算法的.NET Framework实现.
- [PCLCrypto](https://github.com/AArnott/PCLCrypto) - 提供由平台实现的算法的加密API，包括将它们暴露给可移植库.
- [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) -  .NET加密正确完成.
- [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - 使用libsodium和protobuf进行流加密和解密.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) - 加密Api.
- [clj-crypto](https://github.com/macourtney/clj-crypto/) -  Bouncy Castle的包​​装.
- [pandect](https://github.com/xsc/pandect) - 用于Clojure的快速且易于使用的消息摘要，校验和和HMAC库.

### Common Lisp

- [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) - 常见加密函数的集合.
- [ironclad](http://method-combination.net/lisp/ironclad/) - 收集常见的加密快捷方式.
- [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) -  Common Lisp的SSH客户端库（基于libssh2构建）.

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) -  Delphi的加密库.
- [LockBox](https://sourceforge.net/projects/tplockbox/) -  LockBox 3是用于加密的Delphi库.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - 快速加密例程（散列和密码），实现AES，XOR，RC4，ADLER32，MD5，SHA1，SHA256算法，针对速度进行了优化.
- [TForge](https://bitbucket.org/sergworks/tforge) -  TForge是用Delphi编写的开源加密库，与FPC兼容.

### Elixir

- [cipher](https://github.com/rubencaro/cipher) -  Elixir加密库，用于加密/解密任意二进制文件.
- [cloak](https://github.com/danielberkompas/cloak) -  Cloak使用Ecto轻松加密.
- [comeonin](https://github.com/elixircnx/comeonin) -  Elixir的密码授权（bcrypt）库.
- [elixir-rsa](https://github.com/trapped/elixir-rsa) -  Elixir的`：public_key`加密包装器.
- [elixir_tea](https://github.com/keichan34/elixir_tea) - 在Elixir中实施TEA.
- [ex_crypto](https://github.com/ntrepid8/ex_crypto)   -  Erlang的Elixir包装器`：crypto`和`：public_key`模块.  为许多加密函数提供合理的默认值，使其更易于使用.
- [exgpg](https://github.com/rozap/exgpg) - 使用Elixir的gpg.
- [pot](https://github.com/yuce/pot) - 用于生成与Google身份验证器兼容的一次性密码的Erlang库.
- [siphash-elixir](https://github.com/zackehh/siphash-elixir) -  Elixir实现SipHash哈希族.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) - 用于计算消息摘要的函数，以及用于加密和解密的函数.
- [public_key](http://erlang.org/doc/man/public_key.html) - 提供处理公钥基础结构的功能.

### Go

- [crypto](https://golang.org/pkg/crypto/) - 官方网站资源.
- [cryptoballot](https://github.com/cryptoballot/cryptoballot) - 密码安全的在线投票.
- [dedis/crypto](https://github.com/dedis/crypto) -  Go语言的高级加密库.
- [dkeyczar](https://github.com/dgryski/dkeyczar) -  Google的Keyczar密码库到Go的端口.
- [gocrypto](https://github.com/kisom/gocrypto) -  Practical Crypto with Go书的示例源代码.
- [goThemis](https://github.com/cossacklabs/themis/wiki/Go-Howto) - Go wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).


### Haskell

- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) -  Collaborative Hackage列表.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) -  Haskell官方网站.
- [cryptol](https://github.com/GaloisInc/cryptol) - 密码学的语言.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) - 加密原语的Haskell存储库.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) -  Haskel的OpenSSL绑定.
- [scrypt](https://github.com/informatikr/scrypt) -  Haskell绑定到Colin Percival的scrypt实现.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) -  Haxe密码学图书馆.

### JavaScript

- [asmCrypto](https://github.com/vibornoff/asmcrypto.js/) - 考虑到性能的流行加密实用程序的JavaScript实现.
- [bcrypt-nodejs](https://github.com/shaneGirish/bcrypt-nodejs) - Native implementation of bcrypt for NodeJS.
- [cifre](https://github.com/openpeer/cifre) - 用于现代客户端JavaScript的快速加密工具包.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) -  Google常用的JavaScript库.
- [cryptico](https://github.com/wwwtyro/cryptico) - 易于使用的加密系统，利用RSA和AES进行javascript.
- [crypto-js](https://github.com/brix/crypto-js) - 加密标准的JavaScript库.
- [cryptojs](https://github.com/gwjjeff/cryptojs) - 为NodeJS提供标准和安全的加密算法.
- [forge](https://github.com/digitalbazaar/forge) - 在Javascript和工具中本地实现TLS，以编写基于加密和网络的Web应用程序.
- [IronNode](https://docs.ironcorelabs.com/ironnode-sdk/overview) - 转换加密库，一种代理重新加密的变体，用于加密用户或组，并轻松地向NodeJS应用添加强大的数据控件.
- [IronWeb](https://docs.ironcorelabs.com/ironweb-sdk/overview) - 转换加密库，一种代理重新加密的变体，用于在浏览器中安全地轻松管理端到端加密.
- [javascript-crypto-library](https://github.com/clipperz/javascript-crypto-library) -  JavaScript Crypto Library为Web开发人员提供了广泛而有效的加密函数集.
- [js-nacl](https://github.com/tonyg/js-nacl) - 用于Emscripten编译的libsodium例程的纯Javascript高级API.
- [jsencrypt](https://github.com/travist/jsencrypt) - 用于执行OpenSSL RSA加密，解密和密钥生成的Javascript库.
- [JShashes](https://github.com/h2non/jshashes) - 用于node.js和浏览器的快速且无依赖关系的加密散列库（支持MD5，SHA1，SHA256，SHA512，RIPEMD，HMAC）.
- [jsrsasign](https://github.com/kjur/jsrsasign) - &#39;jsrsasign&#39;（RSA-Sign JavaScript Library）是一个支持RSA / RSAPSS / ECDSA / DSA签名/验证的无源加密库.
- [jsThemis](https://github.com/cossacklabs/themis/wiki/NodeJS-Howto) - Javascript wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [libsodium.js](https://github.com/jedisct1/libsodium.js) -  libsodium编译为纯JavaScript，方便包装.
- [libVES.js](https://github.com/vesvault/libVES) - 通过云存储库进行端到端加密共享，在密钥丢失的情况下通过朋友的病毒网络进行安全恢复.
- [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js) - 用于NodeJS的bcrypt.
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) -  JavaScript的OpenPGP实现.
- [PolyCrypt](https://github.com/polycrypt/polycrypt) -  WebCrypto API的纯JS实现.
- [rusha](https://github.com/srijs/rusha) - 适用于大型二进制数据的高性能纯javascript SHA1实现，可达到本机速度的一半.
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - 斯坦福Javascript加密库.
- [URSA](https://github.com/quartzjer/ursa) - 用于Node的RSA公钥/私钥OpenSSL绑定.


### Java

- [Apache Shiro](http://shiro.apache.org/) - 执行身份验证，授权，加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html)   - 通用加密库.  JCA提供商，从基本帮助者到PGP / SMIME操作的广泛功能.
- [Flexiprovider](http://www.flexiprovider.de/) - 用于Java加密体系结构的强大工具包.
- [GDH](https://github.com/maxamel/GDH) - 广泛的Diffie-Hellman密钥交换Java库，用于在Vert.x框架之上构建的多方.
- [Google Keyczar](https://github.com/google/keyczar) - 易于使用且安全的加密框架，具有密钥版本控制.
- [Google Tink](https://github.com/google/tink) - 一个小型加密库，提供安全，简单，灵活，快速的方法来完成一些常见的加密任务.
- [Java Themis](https://github.com/cossacklabs/themis/wiki/Java-and-Android-Howto) - Java/Android wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [jbcrypt](http://www.mindrot.org/projects/jBCrypt/) -  jBCrypt是OpenBSD Blowfish密码散列的实现
algorithm.
- [Keycloak](https://github.com/keycloak/keycloak) - 针对现代应用和服务的开源身份和访问管理.
- [keywhiz](https://github.com/square/keywhiz) - 用于分发和管理秘密的系统.
- [pac4j](https://github.com/pac4j/pac4j) - 安全引擎.
- [Project Kalium](http://abstractj.github.io/kalium/) -  Java与网络和密码学（NaCl）库的绑定与libsodium的精彩.
- [scrypt](https://github.com/wg/scrypt) -  scrypt密钥派生函数的纯Java实现和C实现的JNI接口，包括SSE2优化版本.
- [securitybuilder](https://github.com/tersesystems/securitybuilder) - 用于JCA / JSSE对象的Fluent Builder API.



### Julia

- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) - 包含OpenSSL的库，但也有纯Julia实现供参考.
- [MbedTLS.jl](https://github.com/JuliaWeb/MbedTLS.jl) -  mbed TLS和加密C库周围的包装.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) - 朱莉娅包装荨麻加密哈希/
加密库提供MD5，SHA1，SHA2散列和HMAC功能，以及AES加密/解密.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) -  Performant，100％native-julia SHA1，SHA2- {224,256,384,512}实现.

### Lua

- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - 用纯Lua编写的加密原语的集合.
- [LuaCrypto](https://github.com/mkottman/luacrypto) -  Lua绑定到OpenSSL.

### Objective-C

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) -  AES，MD5，SHA1，SHA224，SHA256，SHA384，SHA512，Base64，Hex.
- [ObjC Themis](https://github.com/cossacklabs/themis/wiki/Objective-C-Howto) - ObjC wrapper on Themis for iOS and MacOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [ObjectivePGP](https://github.com/krzyzanowskim/ObjectivePGP)   -  ObjectivePGP是iOS和macOS的OpenPGP协议的实现.  OpenPGP是使用最广泛的电子邮件加密标准.
- [RNCryptor](https://github.com/RNCryptor/RNCryptor) - 适用于iOS和Mac的CCCryptor（AES加密）包装器.


### PHP

- [halite](https://paragonie.com/project/halite) - 使用`libsodium`进行加密的简单库.
- [libsodium-laravel](https://github.com/scrothers/libsodium-laravel) - 使用`libsodium`的Laravel包抽象.
- [PHP Encryption](https://github.com/defuse/php-encryption) - 用于使用PHP中的密钥或密码加密数据的库.
- [PHP Themis](https://github.com/cossacklabs/themis/wiki/PHP-Howto) - PHP wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [TCrypto](https://github.com/timoh6/TCrypto) -  TCrypto是一个简单而灵活的PHP 5.3+内存中键值存储库.

### Python

- [bcrypt](https://github.com/pyca/bcrypt) - 为您的软件和服务器提供现代密码哈希.
- [charm](https://github.com/JHUISI/charm) - 快速原型化密码系统的框架.
- [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) - 用于数字签名的量子抗性非对称密钥生成工具.
- [cryptography](https://cryptography.io/en/latest/) -  Python库，它公开了加密配方和基元.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) - 加密算法和应用程序的纯python实现.
- [hashids](https://github.com/davidaurelio/hashids-python) - 实施 [hashids](http://hashids.org) 在Python中.
- [paramiko](http://www.paramiko.org/) -  SSHv2协议的Python实现，提供客户端和服务器功能.
- [Privy](https://github.com/ofek/privy) - 一个简单，快速的lib，可以正确地密码保护您的数据.
- [pycryptodome](https://github.com/Legrandin/pycryptodome) - 低级加密原语的自包含Python包.
- [PyElliptic](https://github.com/yann2192/pyelliptic)   -  Python OpenSSL包装器.  适用于ECC，AES，HMAC，Blowfish的现代加密技术.
- [pynacl](https://github.com/pyca/pynacl) -  Python绑定到网络和加密（NaCl）库.
- [pythemis](https://github.com/cossacklabs/themis/wiki/Python-Howto) - Python wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### R

- [rscrypt](https://github.com/rstudio/rscrypt) - 用于scrypt加密函数集合的包.

### Ruby

- [bcrypt-ruby](https://github.com/codahale/bcrypt-ruby) - 用于OpenBSD bcrypt（）密码散列算法的Ruby绑定，允许您轻松存储用户密码的安全散列.
- [RbNaCl](https://github.com/cryptosphere/rbnacl) -  Ruby绑定到网络和密码（NaCl）库.
- [Ruby Themis](https://github.com/cossacklabs/themis/wiki/Ruby-Howto) - Ruby wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### Rust

- [dalek cryptography](https://github.com/dalek-cryptography/) - 用于ECC，防弹等的快速而安全的中级API.
- [octavo](https://github.com/libOctavo/octavo) - 高度模块化和可配置的哈希和加密库.
- [proteus](https://github.com/wireapp/proteus) -  Rust中没有标题键的Axolotl协议实现.
- [recrypt](https://github.com/IronCoreLabs/recrypt-rs) - 一个pure-Rust库，它实现用于构建多跳代理重新加密方案的加密原语，称为转换加密.
- [ring](https://github.com/briansmith/ring) - 使用Rust＆BoringSSL的加密原语安全，快速，小型加密.
- [rust-crypto](https://github.com/DaGenix/rust-crypto) - 大多数纯Rust实现各种加密算法.
- [rust-openssl](https://github.com/sfackler/rust-openssl) -  Rust的OpenSSL绑定.
- [rustls](https://github.com/ctz/rustls) -  Rustls是一个用Rust编写的全新现代TLS库.
- [sodiumoxide](https://github.com/dnaq/sodiumoxide) - 氧化钠：Rust的快速加密库（绑定到libsodium）.
- [suruga](https://github.com/klutzy/suruga) -  Rust中的TLS 1.2实现.
- [webpki](https://github.com/briansmith/webpki) -  Rust中的Web PKI TLS X.509证书验证.

### Scala

- [recrypt](https://github.com/IronCoreLabs/recrypt) - 转换Scala的加密库.
- [scrypto](https://github.com/input-output-hk/scrypto) -  Scala的加密原语.
- [tsec](https://github.com/jmcardon/tsec) - 类型安全，功能强大的通用安全和加密库.

### Swift

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - 使用Swift编程语言实现的Swift的加密相关函数和帮助程序.
- [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) -  Apple的包装 [CommonCrypto](https://opensource.apple.com/source/CommonCrypto/) library written in Swift.
- [OpenSSL](https://github.com/Zewo/OpenSSL) - 适用于OS X和Linux的Swift OpenSSL.
- [SweetHMAC](https://github.com/jancassio/SweetHMAC) - 使用HMAC算法轻松且易于使用Swift类加密字符串.
- [Swift-Sodium](https://github.com/jedisct1/swift-sodium) - 用于iOS和OS X的常见加密操作的Sodium库的Swift接口.
- [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) -  Swift中优雅的加密工具包.
- [SwiftThemis](https://github.com/cossacklabs/themis/wiki/Swift-Howto) - Swift wrapper on Themis for iOS and MacOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

## Resources

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) - 关于加密的一些随机想法.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/)   - 布里斯托尔大学密码学研究组的官方博客.  这是一个小组博客，主要针对密码学家和加密学生.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) -  WebCrypto博客帖子.
- [Root Labs rdist](https://rdist.root.org/) -  Nate Lawson和他的合作者撰写了各种主题，包括硬件实现，加密定时攻击，DRM和Commodore 64.
- [Salty Hash](https://blog.ironcorelabs.com) - 涵盖有关加密，数据控制，隐私和安全性的主题.
- [Schneier on security](https://www.schneier.com/)   - 最古老，最着名的安全博客之一.  布鲁斯涵盖了从分组密码密码分析到机场安全的主题.

### Mailing lists

- [metzdowd.com](http://www.metzdowd.com/mailman/listinfo/cryptography) - “密码学”是一个低噪声的主持邮件列表，专门用于加密技术及其政治影响.
- [Modern Crypto](https://moderncrypto.org/) - 讨论现代加密实践的论坛.
- [randombit.net](https://lists.randombit.net/mailman/listinfo/cryptography) - 密码学一般性讨论清单，特别是技术方面.

### Web-tools

- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) - 是一组与密码学相关的工具.
- [CrypTool](http://www.cryptool-online.org/) - 引入了各种各样的密码，加密方法和分析工具，通常与插图示例一起使用.
- [CyberChef](https://gchq.github.io/CyberChef/) - 用于加密，编码，压缩和数据分析的Web应用程序.
- [keybase.io](https://keybase.io/) -  Keybase将您的身份映射到您的公钥，反之亦然.

### Web-sites

- [Cryptography Stackexchange](http://crypto.stackexchange.com/) - 加密堆栈交换是软件开发人员，数学家和其他对密码学感兴趣的人的问答网站.
- [Cryptopals Crypto Challenges](http://cryptopals.com/) - 一系列应用的加密挑战，从非常基本的挑战开始，例如十六进制到基数64挑战，并逐渐增加抽象代数的难度.
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) - 密码学概述.
- [IACR](https://www.iacr.org/) - 国际密码学研究协会是一个非营利性科学组织，其目的是进一步研究密码学和相关领域.
- [Learn Cryptography](https://learncryptography.com/) - 致力于帮助人们了解他们日常使用的加密系统的方式和原因，而无需实现保护和保护隐私的工作.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) - 此subreddit旨在用于围绕强加密理论和实践的链接和讨论.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) - 此规范描述了用于在Web应用程序中执行基本加密操作的JavaScript API，例如散列，签名生成和验证以及加密和解密.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) 第一.

## License

`awesome-cryptography` [@sobolevn](https://github.com/sobolevn)

在法律允许的范围内，与CC0相关联的人
`awesome-cryptography`已放弃所有版权及相关或邻近
“awesome-cryptography”的权利.

您应该已经收到了CC0 legalcode的副本
 工作.  如果没有，请参阅 [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/).
