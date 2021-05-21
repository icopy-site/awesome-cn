<div class="github-widget" data-repo="kdeldycke/awesome-iam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable awesome-heading-->

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-iam/">
    <img src="https://raw.githubusercontent.com/kdeldycke/awesome-iam/raw/main/assets/awesome-iam-header.jpg" alt="Awesome IAM">
  </a>
</p>

<p align="center">
  <strong>精选的资源列表，用于管理帐户，用户，角色，</strong>
权限，身份验证和授权.
  <a href="https://raw.githubusercontent.com/sindresorhus/awesome"><img src="https://awesome.re/badge-flat.svg" alt="Awesome"></a>
</p>

<p align="center">
  </i> </i><br>
  — Maria V. Snyder<sup id="intro-quote-ref"><a href="#intro-quote-def">[1]</a></sup>
</p>

<!--lint disable double-link-->

[IAM](https://en.wikipedia.org/wiki/Identity_management) 代表身份和访问管理. 但是，不仅仅是处理用户帐户：它还包含身份验证，授权和隐私，这使得此范围非常复杂. 它是用户，产品和安全性相遇的云堆栈的重要支柱. 这 [other pillar being billing & payments 💰](https://github.com/kdeldycke/awesome-billing/).

该知识库以一种全面且可行的方式展示了该领域的所有技术，协议和行话.

<!--lint enable double-link-->


<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Overview

<img align="right" width="50%" src="https://raw.githubusercontent.com/kdeldycke/awesome-iam/master/./assets/cloud-software-stack-iam.jpg"/>

在斯坦福大学的课堂上， [overview of cloud computing](http://web.stanford.edu/class/cs349d/docs/L01_overview.pdf)，平台软件架构如右图所示→

在这里，我们列出了全局：领域的定义和战略重要性，它在更大的生态系统中的位置以及一些关键功能.

- [The EnterpriseReady SaaS Feature Guides](https://www.enterpriseready.io) -使B2B用户满意的大多数功能将由IAM外围实现.

- [IAM is hard. It's really hard.](https://twitter.com/kmcquade3/status/1291801858676228098)  -“过于宽松的AWS IAM策略允许s3：GetObject获取*所有资源”，导致第一资本被罚款8000万美元. 您不能忽视IAM作为企业主的唯一原因.

- [IAM Is The Real Cloud Lock-In](https://forrestbrazeal.com/2019/02/18/cloud-irregular-iam-is-the-real-cloud-lock-in/)  -有点“点击麻烦”，但作者承认“这取决于您对他们的信任程度1.保持业务；  2.不要抬高价格；  3.不要贬低您下面的服务；  4.在业务加速方面为您提供的价值要比在灵活性方面要多得多.”

## Security

安全是IAM基金会的最核心支柱之一. 这里有一些广泛的概念.

- [Enterprise Information Security](https://infosec.mozilla.org) -Mozilla的安全性和访问准则.

- [Mitigating Cloud Vulnerabilities](https://media.defense.gov/2020/Jan/22/2002237484/-1/-1/0/CSI-MITIGATING-CLOUD-VULNERABILITIES_20200121.PDF) -“本文档将云漏洞分为四类（配置错误，访问控制差，共享租户漏洞和供应链漏洞）”.

- [Cartography](https://github.com/lyft/cartography)  -基于Neo4J的工具，用于映射服务和资源之间的依存关系和关系. 支持AWS，GCP，GSuite，Okta和GitHub.

- [Open guide to AWS Security and IAM](https://github.com/open-guides/og-aws#security-and-iam)

## Account Management

IAM的基础：用户，组，角色和权限的定义和生命周期.

- [As a user, I want…](https://mobile.twitter.com/oktopushup/status/1030457418206068736) -帐户管理的元批评家，其中业务期望的功能与虚构的项目经理编写的用户故事形式的真实用户需求相冲突.

- [Things end users care about but programmers don't](https://instadeq.com/blog/posts/things-end-users-care-about-but-programmers-dont/)  -与上述精神相同，但涵盖范围更广：开发人员忽略但用户真正关心的所有小事情. 该列表的顶部是以帐户为中心的功能，各种集成和导入/导出工具. 也就是说，所有企业客户都需要承保.

- [Separate the account, user and login/auth details](https://news.ycombinator.com/item?id=21151830) -合理的建议，以奠定面向未来的IAM API的基础.

- [Identity Beyond Usernames](https://lord.io/blog/2020/usernames/) -关于用户名作为标识符的概念，以及当Unicode字符满足唯一性要求时引入的复杂性.

- [Kratos](https://github.com/ory/kratos) -用户登录，用户注册，2FA和配置文件管理.

- [Zitadel](https://github.com/caos/zitadel) -Go中的开源解决方案，用于管理您的所有系统，用户和服务帐户及其角色，权限，登录流程和元数据.

- [Conjur](https://github.com/cyberark/conjur) -自动保护特权用户和计算机身份使用的机密.

## Cryptography

整个身份验证堆栈基于加密原语. 这是不容忽视的.

- [Cryptographic Right Answers](https://latacora.micro.blog/2018/04/03/cryptographic-right-answers.html)  -针对非密码学工程师的开发人员的最新建议集. 甚至有一个 [shorter summary](https://news.ycombinator.com/item?id=16749140) 可用的.

- [Security Recommendations for Any Device that Depends on Randomly-Generated Numbers](https://www.av8n.com/computer/htm/secure-random.htm)  -“短语“随机数生成器”应按以下方式进行解析：它是数字的随机生成器. 它不是随机数的生成器.”

- [Real World Crypto Symposium](https://rwc.iacr.org) -旨在将密码学研究人员与开发人员召集在一起，专注于互联网，云和嵌入式设备等现实环境中的使用.

- [An Overview of Cryptography](https://www.garykessler.net/library/crypto.html)  -“本文有两个主要目的. 首先是定义基本加密方法背后的一些术语和概念，并提供一种比较当今使用的无数加密方案的方法. 第二个是提供一些当今使用的加密的真实示例.”

- [Papers we love: Cryptography](https://github.com/papers-we-love/papers-we-love/blob/master/cryptography/README.md) -密码学基础论文.

- [Lifetimes of cryptographic hash functions](http://valerieaurora.org/hash.html) -“如果使用散列比较来生成可被恶意用户提供的数据地址，则应该制定计划每隔几年迁移到新的散列”.

## Zero-trust Network

零信任网络安全性以“永不信任，始终验证”的原则运行.

- [BeyondCorp: A New Approach to Enterprise Security](https://www.usenix.org/system/files/login/articles/login_dec14_02_ward.pdf) -Google的“零信任网络”计划的快速概述.

- [What is BeyondCorp? What is Identity-Aware Proxy?](https://medium.com/google-cloud/what-is-beyondcorp-what-is-identity-aware-proxy-de525d9b3f90)  -更多的公司增加了VPN，防火墙，限制和约束的额外层，从而带来了糟糕的体验和轻微的安全性提升. 有更好的方法.

- [oathkeeper](https://github.com/ory/oathkeeper)  -身份，访问代理和访问控制决策API，用于对传入的HTTP请求进行身份验证，授权和变异. 受到BeyondCorp / Zero Trust白皮书的启发.

- [transcend](https://github.com/cogolabs/transcend) -BeyondCorp启发式的访问代理服务器.

- [Pomerium](https://github.com/pomerium/pomerium) -身份识别代理，可安全访问内部应用程序.

## Authentication

用来验证自己是谁的协议和技术.

- [Scaling backend authentication at Facebook](https://www.youtube.com/watch?v=kY-Bkv3qxMc)  -简而言之：1.信任根源很小；  2. TLS还不够；  3.基于证书的令牌；  4.加密身份验证令牌（CAT）. 见 [slides](https://rwc.iacr.org/2018/Slides/Lewi.pdf) 更多细节.

### Password-based

- [The new NIST password guidance](https://pciguru.wordpress.com/2019/03/11/the-new-nist-password-guidance/) -的摘要 [NIST Special Publication 800-63B](https://pages.nist.gov/800-63-3/sp800-63b.html) 涵盖了新的密码复杂性指南.

- [Password Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html) -减慢脱机攻击的唯一方法是通过仔细选择尽可能消耗资源的哈希算法.

- [Password expiration is dead](https://techcrunch.com/2019/06/02/password-expiration-is-dead-long-live-your-passwords/) -最近的科学研究对许多长期存在的密码安全实践（例如密码过期策略）的价值提出了疑问，并指出了更好的替代方法，例如强制执行禁用密码列表和MFA.

- [Practical Recommendations for Stronger, More Usable Passwords](http://www.andrew.cmu.edu/user/nicolasc/publications/Tan-CCS20.pdf) -此研究推荐以下关联：阻止列表检查常见的泄漏密码，无字符类要求的密码策略，最低强度策略.

- [Banks, Arbitrary Password Restrictions and Why They Don't Matter](https://www.troyhunt.com/banks-arbitrary-password-restrictions-and-why-they-dont-matter/)  -“长度和字符组成的任意下限都是不好的. 它们看起来很糟，导致对安全状态的负面猜测，并且破坏了诸如密码管理器之类的工具.”

- [Dumb Password Rules](https://github.com/dumb-password-rules/dumb-password-rules) -使用愚蠢的密码规则来掩饰网站.

- [Plain Text Offenders](https://plaintextoffenders.com/about/) -以纯文本形式存储密码的网站的公开羞辱.

- [Password Manager Resources](https://github.com/apple/password-manager-resources) -密码规则的集合，根据站点更改URL和怪癖.

- [A Well-Known URL for Changing Passwords](https://github.com/WICG/change-password-url) -规范定义了用于密码更新的站点资源.

- [How to change the hashing scheme of already hashed user's passwords](https://news.ycombinator.com/item?id=20109360)  -好消息：您不必再使用旧版密码保存方案了. 这是透明升级为更强大的哈希算法的一个技巧.

### Password-less

- [An argument for passwordless](https://web.archive.org/web/20190515230752/https://biarity.gitlab.io/2018/02/23/passwordless/)  -密码不是用户身份验证的全部内容. 本文旨在告诉您原因.

- [WebAuthn guide](https://webauthn.guide) -WebAuthn的易于访问的指南，所有主要浏览器均支持该标准，该标准允许“服务器使用公共密钥密码术而非密码来注册和验证用户”.

### Security Key

- [Webauthn and security keys](https://www.imperialviolet.org/2018/03/27/webauthn.html)  -描述身份验证如何与安全密钥一起使用，详细说明协议以及它们如何与WebAuthn结合. 密钥摘要：“但是，无法使用webauthn创建U2F密钥.  （…）因此，请先完成您登录过程的Webauthn转换，然后完成注册转换.”

- [Getting started with security keys](https://paulstamatiou.com/getting-started-with-security-keys/) -实用指南，可确保在线安全并防止使用FIDO2，WebAuthn和安全密钥进行网络钓鱼.

- [Solo](https://github.com/solokeys/solo) -通过USB + NFC支持FIDO2和U2F的开放安全密钥.

- [OpenSK](https://github.com/google/OpenSK) -用Rust编写的安全密钥的开源实现，同时支持FIDO U2F和FIDO2标准.

- [YubiKey Guide](https://github.com/drduh/YubiKey-Guide)  -将YubiKey用作存储GPG加密，签名和身份验证密钥的智能卡的指南，该密钥也可用于SSH. 本文档中的许多原理都适用于其他智能卡设备.

- [YubiKey at Datadog](https://github.com/DataDog/yubikey) -设置Yubikey，U2F，GPG，git，SSH，Keybase，VMware Fusion和Docker Content Trust的指南.

### Multi-Factor

- [Breaking Password Dependencies: Challenges in the Final Mile at Microsoft](https://www.youtube.com/watch?v=B_mhJO2qHlQ)  -帐户黑客入侵的主要来源是密码喷雾（针对SMTP，IMAP，POP等旧式身份验证），其次是重播攻击. 要点：密码不安全，请使用并强制执行MFA.

- [Beyond Passwords: 2FA, U2F and Google Advanced Protection](https://www.troyhunt.com/beyond-passwords-2fa-u2f-and-google-advanced-protection/) -超越所有这些技术的极佳步行通道.

- [A Comparative Long-Term Study of Fallback Authentication](https://www.mobsec.ruhr-uni-bochum.de/media/mobsec/veroeffentlichungen/2019/02/20/usec2019-30-wip-fallback-long-term-study-finalv2.pdf)  -关键要点：“基于电子邮件和SMS的方案更有用. 另一方面，基于指定受托人和个人知识问题的机制在便利性和效率方面均达不到要求.”

- [Secrets, Lies, and Account Recovery: Lessons from the Use of Personal Knowledge Questions at Google](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43783.pdf)  -“我们的分析证实，秘密问题通常提供的安全级别远低于用户选择的密码.  （…）令人惊讶的是，我们发现这种不安全的一个重要原因是用户经常不如实回答.  （…）在可用性方面，我们证明秘密答案的记忆力令人惊讶地差”.

- [How effective is basic account hygiene at preventing hijacking](https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html) -Google安全团队的数据显示2FA阻止了100％的自动漫游器入侵.

- [Your Pa$$word doesn't matter](https://techcommunity.microsoft.com/t5/Azure-Active-Directory-Identity/Your-Pa-word-doesn-t-matter/ba-p/731984) -与Microsoft的上述结论相同：“根据我们的研究，如果您使用MFA，您的帐户被盗用的可能性会降低99.9％以上.”

- [Attacking Google Authenticator](https://unix-ninja.com/p/attacking_google_authenticator) -可能处于偏执狂的边缘，但这可能是对2FA验证尝试进行限制的原因.

- [Compromising online accounts by cracking voicemail systems](https://www.martinvigo.com/voicemailcracker/)  -或者为什么您不应该依靠自动电话来联系用户并重置密码，2FA或进行任何形式的验证. 与基于SMS的2FA不同，它目前是不安全的，并且可以通过其最薄弱的链接（语音邮件系统）来破坏.

- [Getting 2FA Right in 2019](https://blog.trailofbits.com/2019/06/20/getting-2fa-right-in-2019/) -关于2FA的UX方面.

### SMS-based

 TL; DR：不. 有关详细信息，请参见下面的文章.

- [SMS 2FA auth is deprecated by NIST](https://techcrunch.com/2016/07/25/nist-declares-the-age-of-sms-based-2-factor-authentication-over/) -NIST表示，自2016年以来，通过SMS进行的2FA既糟糕又糟糕.

- [SMS: The most popular and least secure 2FA method](https://www.allthingsauth.com/2018/02/27/sms-the-most-popular-and-least-secure-2fa-method/)

- [Is SMS 2FA Secure? No.](https://www.issms2fasecure.com) -权威的研究项目，展示了SIM交换的成功尝试.

- [Hackers Hit Twitter C.E.O. Jack Dorsey in a 'SIM Swap.' You're at Risk, Too.](https://www.nytimes.com/2019/09/05/technology/sim-swap-jack-dorsey-hack.html)

- [AT\&T rep handed control of his cellphone account to a hacker](https://www.theregister.co.uk/2017/07/10/att_falls_for_hacker_tricks/)

- [The Most Expensive Lesson Of My Life: Details of SIM port hack](https://medium.com/coinmonks/the-most-expensive-lesson-of-my-life-details-of-sim-port-hack-35de11517124)

- [SIM swap horror story](https://www.zdnet.com/article/sim-swap-horror-story-ive-lost-decades-of-data-and-google-wont-lift-a-finger/)

- [AWS is on its way to deprecate SMS-based 2FA](https://aws.amazon.com/iam/details/mfa/)  -“我们鼓励您通过U2F安全密钥，硬件设备或虚拟（基于软件的）MFA设备使用MFA. 您可以继续使用此功能，直到2019年1月31日为止.”

### Public-Key Infrastructure (PKI)

基于证书的身份验证.

- [PKI for busy people](https://rehn.me/posts/pki-for-busy-people.html) -重要内容的快速概述.

- [Everything you should know about certificates and PKI but are too afraid to ask](https://smallstep.com/blog/everything-pki.html)  -PKI允许您以密码方式定义系统. 它是通用的，与供应商无关.

- [`lemur`](https://github.com/Netflix/lemur) -充当CA与环境之间的代理，为开发人员提供一个中央门户，以颁发具有“默认”默认值的TLS证书.

- [CFSSL](https://github.com/cloudflare/cfssl)  -CloudFlare的用于PKI / TLS的瑞士军刀. 命令行工具和HTTP API服务器，用于签名，验证和捆绑TLS证书.

- [JA3](https://github.com/salesforce/ja3) -创建SSL / TLS客户端指纹的方法，该方法应该易于在任何平台上生成，并且可以轻松共享以用于威胁情报.

### JWT

[JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) 是不记名的令牌.

- [Introduction to JSON Web Tokens](https://jwt.io/introduction/) -通过本文了解JWT的最新信息.

- [Learn how to use JWT for Authentication](https://github.com/dwyl/learn-json-web-tokens) -了解如何使用JWT保护您的Web应用程序.

- [Using JSON Web Tokens as API Keys](https://auth0.com/blog/using-json-web-tokens-as-api-keys/) -与API密钥相比，JWT提供了精细的安全性，同质的身份验证体系结构，分散的发行，OAuth2遵从性，可调试性，到期控制，设备管理.

- [Managing a Secure JSON Web Token Implementation](https://cursorblog.com/managing-a-secure-json-web-token-implementation/) -JWT具有各种灵活性，因此很难很好地使用.

- [Hardcoded secrets, unverified tokens, and other common JWT mistakes](https://r2c.dev/blog/2020/hardcoded-secrets-unverified-tokens-and-other-common-jwt-mistakes/) -回顾一下所有JWT的陷阱.

- [Adding JSON Web Token API Keys to a DenyList](https://auth0.com/blog/denylist-json-web-token-api-keys/) -关于令牌失效.

- [Stop using JWT for sessions](http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/) - 和 [why your "solution" doesn't work](http://cryto.net/%7Ejoepie91/blog/2016/06/19/stop-using-jwt-for-sessions-part-2-why-your-solution-doesnt-work/)， 因为 [stateless JWT tokens cannot be invalidated or updated](https://news.ycombinator.com/item?id=18354141) . 它们将根据存储它们的位置而引起大小问题或安全性问题. 有状态的JWT令牌在功能上与会话cookie相同，但是没有经过反复测试和充分审查的实现或客户端支持.

- [JWT, JWS and JWE for Not So Dummies\!](https://medium.facilelogin.com/jwt-jws-and-jwe-for-not-so-dummies-b63310d201a3)  -签名的JWT被称为JWS（JSON Web签名）. 实际上，JWT本身并不存在-它必须是JWS或JWE（JSON Web加密）. 它就像一个抽象类-JWS和JWE是具体的实现.

- [JOSE is a Bad Standard That Everyone Should Avoid](https://paragonie.com/blog/2017/03/jwt-json-web-tokens-is-bad-standard-that-everyone-should-avoid) -这些标准要么完全被打破，要么很难导航到复杂的雷区.

- [JWT.io](https://jwt.io) -允许您解码，验证和生成JWT.

- [`loginsrv`](https://github.com/tarent/loginsrv) -独立的简约登录服务器，为多个登录后端（htpasswd，OSIAM，用户/密码，HTTP基本身份验证，OAuth2：GitHub，Google，Bitbucket，Facebook，Gitlab）提供JWT登录.

### OAuth2 & OpenID

[OAuth 2.0](https://en.wikipedia.org/wiki/OAuth#OAuth_2.0) 是一个授权框架. [OpenID Connect (OIDC)](https://en.wikipedia.org/wiki/OpenID_Connect) 是位于其之上的身份验证层.

旧的* OpenID *已死； 新的* OpenID Connect *几乎是不死的.

- [An Illustrated Guide to OAuth and OpenID Connect](https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc) -使用简化的插图说明这些标准的工作方式.

- [OAuth 2 Simplified](https://aaronparecki.com/oauth-2-simplified/) -参考文章，以简化格式描述了该协议，以帮助开发人员和服务提供商实施该协议.

- [OAuth 2.0 and OpenID Connect (in plain English)](https://www.youtube.com/watch?v=996OiexHze0) -从有关这些标准如何形成的历史背景开始，清除词汇表中的不准确之处，然后详细说明协议及其陷阱以减少威胁.

- [Everything You Need to Know About OAuth (2.0)](https://gravitational.com/blog/everything-you-need-to-know-about-oauth/) -通过一个实用的案例研究很好地概述了Teleport这个开源远程访问工具如何允许用户通过GitHub SSO登录.

- [OAuth in one picture](https://mobile.twitter.com/kamranahmedse/status/1276994010423361540) -漂亮的摘要卡.

- [How to Implement a Secure Central Authentication Service in Six Steps](https://engineering.shopify.com/blogs/engineering/implement-secure-central-authentication-service-six-steps)  -是否有多个旧系统与它们自己的登录方法和帐户合并？ 这是通过OIDC合并所有混乱情况的方法.

- [Open-Sourcing BuzzFeed's SSO Experience](https://increment.com/security/open-sourcing-buzzfeeds-single-sign-on-process/)  -中央身份验证服务（CAS）协议的OAuth2友好型改编. 您会在这里找到良好的OAuth用户流程图.

- [The Decline of OpenID](https://penguindreams.org/blog/the-decline-of-openid/) -在公共网络中，OpenID已被替换为OAuth 1，OAuth 2或其他专有SSO协议的组合.

- [Why Mastercard Doesn't Use OAuth 2.0](https://developer.mastercard.com/blog/why-mastercard-doesnt-use-oauth-20)  -“他们这样做是为了提供消息级的完整性.  OAuth 2切换到了传输级别的机密性/完整性.”  （TLS提供的）（[source](https://news.ycombinator.com/item?id=17486165)).

- [OAuth 2.0 Security Best Current Practice](https://tools.ietf.org/html/draft-ietf-oauth-security-topics-16) -“更新和扩展了OAuth 2.0安全威胁模型，以吸收自OAuth 2.0发布以来收集的实践经验，并涵盖由于应用范围更广而引起的新威胁”.

- [Hidden OAuth attack vectors](https://portswigger.net/web-security/oauth) -如何识别和利用OAuth 2.0身份验证机制中的一些关键漏洞.

- [PKCE Explained](https://www.loginradius.com/engineering/blog/pkce/) -“ PKCE用于为OAuth和OpenID Connect中的授权代码流提供一个额外的安全层.”

- [Hydra](https://gethydra.sh) -开源OIDC和OAuth2服务器.

- [Cierge](https://web.archive.org/web/20190402111431/https://pwdless.github.io/Cierge-Website/) -开源身份验证服务器（OIDC），用于处理用户注册，登录，配置文件，管理等.

- [Keycloak](https://www.keycloak.org)  -开源身份和访问管理. 支持OIDC，OAuth 2和SAML 2，LDAP和AD目录，密码策略.

- [IdentityServer](https://github.com/IdentityServer/IdentityServer4) -用于ASP.NET Core的免费，开源OpenID Connect和OAuth 2.0框架.

- [authentik](https://goauthentik.io/?#correctness) -类似于Keycloak的开源身份提供程序.

### SAML

安全声明标记语言（SAML）2.0是一种在服务之间交换授权和身份验证的方式，例如上述OAuth / OpenID协议.

典型的SAML身份提供者是机构或大公司的内部SSO，而典型的OIDC / OAuth提供者是运行数据孤岛的技术公司.

- [SAML vs. OAuth](https://www.cloudflare.com/learning/access-management/what-is-oauth/)  -“ OAuth是授权协议：它可以确保Bob到达正确的停车场. 相比之下，SAML是用于身份验证的协议，或者允许Bob越过警卫室.”

- [The Difference Between SAML 2.0 and OAuth 2.0](https://www.ubisecure.com/uncategorized/difference-between-saml-and-oauth/)  -“尽管SAML实际上是为广泛应用而设计的，但其现代用法通常会转向企业SSO方案. 另一方面，OAuth被设计用于Internet上的应用程序，特别是用于委托授权.”

- [What's the Difference Between OAuth, OpenID Connect, and SAML?](https://www.okta.com/identity-101/whats-the-difference-between-oauth-openid-connect-and-saml/)  -身份很难. 始终欢迎对不同协议进行另一种尝试，以帮助理解所有内容.

- [How SAML 2.0 Authentication Works](https://gravitational.com/blog/how-saml-authentication-works/) -有关SSO和SAML的方式和原因的概述.

- [Web Single Sign-On, the SAML 2.0 perspective](https://blog.theodo.com/2019/06/web-single-sign-on-the-saml-2-0-perspective/) -在公司SSO实施中对SAML工作流的另一种幼稚解释.

- [The Beer Drinker's Guide to SAML](https://duo.com/blog/the-beer-drinkers-guide-to-saml)  -SAML有时是不可思议的. 另一个类比可能有助于从中获得更多的了解.

- [The Difficulties of SAML Single Logout](https://wiki.shibboleth.net/confluence/display/CONCEPT/SLOIssues) -关于单一注销实施的技术和用户体验问题.

## Authorization

现在我们知道您就是您，您是否可以执行自己想做的事情？

政策规范是科学，执法是艺术.

### Policy models

从概念上讲，可以将访问控制策略设计为遵循非常不同的原型，从经典 [Access Control Lists](https://en.wikipedia.org/wiki/Access-control_list) 至 [Role Based Access Control](https://en.wikipedia.org/wiki/Role-based_access_control) . 在本节中，我们探索许多不同的模式和体系结构.

- [In Search For a Perfect Access Control System](https://goteleport.com/blog/access-controls/) -概述最流行的授权方案及其历史渊源.

- [Role Based Access Control](https://csrc.nist.gov/projects/role-based-access-control) -一个NIST项目，用于解释RBAC的概念，成本和收益，RBAC的经济影响，设计和实施问题，标准本身以及高级研究主题.

- [Semantic-based Automated Reasoning for AWS Access Policies using SMT](https://d1.awsstatic.com/Security/pdfs/Semantic_Based_Automated_Reasoning_for_AWS_Access_Policies_Using_SMT.pdf)  -Zelkova是AWS的工作方式. 该系统对IAM策略进行符号分析，并根据用户权限和访问限制来解决资源的可达性. 另请参阅上级 [introduction given at re:inforce 2019](https://youtu.be/x6wsTFnU3eY?t=2111).

- [Zanzibar: Google's Consistent, Global Authorization System](https://ai.google/research/pubs/pub48190)  -扩展到每秒数万亿的访问控制列表和数百万的授权请求，以支持数十亿人使用的服务. 在过去三年的生产使用中，它始终保持95％的延迟不到10毫秒，可用性超过99.999％. [Other bits not in the paper](https://twitter.com/LeaKissner/status/1136626971566149633).

-的说明 [authz system that is built around labeled security and RBAC concepts](https://news.ycombinator.com/item?id=20136831).

### Open-source policy frameworks

如果您希望推行自己的政策实施，请收集开源项目.

- [Keto](https://github.com/ory/keto)  -政策决策点. 它使用一组类似于AWS策略的访问控制策略，以确定主题是否被授权对资源执行特定操作.

- [Ladon](https://github.com/ory/ladon) -受AWS启发的访问控制库.

- [Athenz](https://github.com/yahoo/athenz) -支持服务身份验证和基于角色的授权（RBAC）进行供应和配置的服务和库的集合.

- [Casbin](https://github.com/casbin/casbin) -用于Golang项目的开源访问控制库.

- [Open Policy Agent](https://github.com/open-policy-agent) -允许对SQL，Kubernetes，Terraform，Kafka，Envoy，S3（通过Minio），EC2 / ECS / Lambda（Linux）进行策略的端到端测试.

- [Gubernator](https://github.com/mailgun/gubernator) -高性能限制速率的微服务和库.

### AWS policy tools

专门针对 [AWS IAM policies](http://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html) 生态系统.

- [Become an AWS IAM Policy Ninja](https://www.youtube.com/watch?v=y7-fAT3z8Lo) -“在亚马逊工作的近5年中，我每天，每周抽出一点时间浏览论坛和客户门票，以找出人们遇到麻烦的地方.”

- [Cloudsplaining](https://github.com/salesforce/cloudsplaining) -安全评估工具，可识别违反最小特权并生成风险优先报告.

- [Policy Sentry](https://github.com/salesforce/policy_sentry)  -手工编写具有安全意识的IAM策略可能非常繁琐且效率低下.  Policy Sentry帮助用户在几秒钟内创建最小特权策略.

- [Aardvark and Repokid](https://netflixtechblog.com/introducing-aardvark-and-repokid-53b081bf3a7e)  -Netflix工具，可在AWS上实施最低特权. 这个想法是，对新事物的默认策略是全部拒绝，然后它监视cloudtrail特权失败，并重新配置IAM以允许最小的特权摆脱该拒绝消息.

- [Principal Mapper](https://github.com/nccgroup/PMapper) -快速评估权限.

- [PolicyUniverse](https://github.com/Netflix-Skunkworks/policyuniverse) -解析和处理AWS策略，语句，ARN和通配符.

- [IAM Floyd](https://github.com/udondan/iam-floyd)  -具有流畅接口的AWS IAM策略声明生成器. 通过提供条件和通过IntelliSense生成ARN，帮助创建类型安全的IAM策略并编写更多限制性/安全性声明. 适用于Node.js，Python，.Net和Java.

### Macaroons

分发和委派授权的巧妙好奇心.

- [Google's Macaroons in Five Minutes or Less](https://blog.bren2010.io/2014/12/04/macaroons.html) -如果我获得了授权在一定限制下执行某些操作的蛋白杏仁饼干，则可以非交互式地构建第二个蛋白杏仁饼干，并赋予我更严格的限制.

- [Macaroons: Cookies with Contextual Caveats for Decentralized Authorization in the Cloud](https://ai.google/research/pubs/pub41892) -Google的原始论文.

- [Google paper's author compares Macaroons and JWTs](https://news.ycombinator.com/item?id=14294463) - As a consumer/verifier of macaroons, they allow you (through third-party caveats) to defer some authorization decisions to someone else. JWTs don't.

## Secret Management

允许存储和使用机密的体系结构，软件和硬件，可以在保持信任链的同时进行身份验证和授权.

- [Secret at Scale at Netflix](https://www.youtube.com/watch?v=K0EOPddWpsE)  -基于盲签名的解决方案. 见 [slides](https://rwc.iacr.org/2018/Slides/Mehta.pdf).

- [High Availability in Google's Internal KMS](https://www.youtube.com/watch?v=5T_c-lqgjso)  -不是GCP的KMS，而是位于其基础架构核心的KMS. 见 [slides](https://rwc.iacr.org/2018/Slides/Kanagala.pdf).

- [`vault`](https://www.vaultproject.io) -保护，存储和严格控制对令牌，密码，证书，加密密钥的访问.

- [`sops`](https://github.com/mozilla/sops) -加密YAML和JSON文件的值，而不是密钥.

- [`gitleaks`](https://github.com/zricethezav/gitleaks) -审核git repos的机密.

- [`truffleHog`](https://github.com/dxa4481/truffleHog) -在git存储库中搜索高熵字符串和机密，深入挖掘提交历史.

- [Keywhiz](https://square.github.io/keywhiz/) -一种用于管理和分发机密的系统，可以很好地适应面向服务的体系结构（SOA）.

- [`roca`](https://github.com/crocs-muni/roca) -Python模块，用于检查各种密钥格式的较弱的RSA模数.

### Hardware Security Module (HSM)

HSM是在硬件级别保证秘密管理安全性的物理设备.

- [HSM: What they are and why it's likely that you've (indirectly) used one today](https://rwc.iacr.org/2015/Slides/RWC-2015-Hampton.pdf) -HSM使用的真正基本概述.

- [Tidbits on AWS Cloud HSM hardware](https://news.ycombinator.com/item?id=16759383) -AWS CloudHSM Classic由SafeNet的Luna HSM支持，当前的CloudHSM依靠Cavium的Nitrox，它允许可分区的“虚拟HSM”.

- [CrypTech](https://cryptech.is) -开放式硬件HSM.

- [Keystone](https://keystone-enclave.org) -基于RISC-V架构的开放源代码项目，用于使用安全的硬件区域构建受信任的执行环境（TEE）.

- [Project Oak](https://github.com/project-oak/oak) -数据的安全传输，存储和处理的规范和参考实现.

- [Everybody be cool, this is a robbery\!](https://www.sstic.org/2019/presentation/hsm/) -HSM漏洞和可利用性的案例研究（法语，抱歉）.

## Trust & Safety

一旦拥有了重要的用户群，就将其称为社区. 然后，您将负责保护它：客户，人员，公司，业务，并促进其中发生的所有交互和交易.

A critical intermediation complex driven by a policy and constraint by local laws, the Trust & Safety department is likely embodied by a cross-functional team of 24/7 operators and systems of highly advanced moderation and administration tools. You can see it as an extension of customer support services, specialized in edge-cases like manual identity checks, moderation of harmful content, stopping harassment, handling of warrants and copyright claims, data sequestration and other credit card disputes.

- [Trust and safety 101](https://www.csoonline.com/article/3206127/trust-and-safety-101.html) -有关域及其职责的精彩介绍.

- [What the Heck is Trust and Safety?](https://www.linkedin.com/pulse/what-heck-trust-safety-kenny-shi) -几个真实的用例来说明TnS团队的作用.

<!--lint disable double-link-->

- [Awesome List of Billing and Payments: Fraud links](https://github.com/kdeldycke/awesome-billing#fraud) -我们姐妹资料库中专门用于计费和付款欺诈管理的部分.

<!--lint enable double-link-->

### User Identity

大多数企业不收集客户的身份来创建用户资料以出售给第三方，否. 但是您仍然必须：当地法律要求跟踪大型合同下的合同关系. [Know You Customer (KYC)](https://en.wikipedia.org/wiki/Know_your_customer) 横幅.

- [The Laws of Identity](https://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.pdf) -本文是否针对身份元系统，其法律仍然在较小规模上提供了深刻的见解，尤其是第一条法律：始终允许用户控制并寻求同意以赢得信任.

- [How Uber Got Lost](https://www.nytimes.com/2019/08/23/business/how-uber-got-lost.html)  -“为限制摩擦”，Uber允许车手签名，而不要求他们提供电子邮件以外的身份（容易伪造）或电话号码.  （…）车辆被盗和烧毁； 司机遭到殴打，抢劫并偶尔被谋杀. 即使暴力增加，该公司仍坚持使用低摩擦的签约系统.”

- [A Comparison of Personal Name Matching: Techniques and Practical Issues](http://users.cecs.anu.edu.au/~Peter.Christen/publications/tr-cs-06-02.pdf) -从帐户重复数据删除到欺诈监控，客户名称匹配有很多应用.

- [Statistically Likely Usernames](https://github.com/insidetrust/statistically-likely-usernames) -单词表，用于创建统计上可能的用户名，以用于用户名枚举，模拟密码攻击和其他安全测试任务.

- [Sherlock](https://github.com/sherlock-project/sherlock) -通过社交网络中的用户名搜寻社交媒体帐户.

### Fraud

作为在线服务提供商，您容易遭受欺诈，犯罪和虐待. 当涉及到金钱时，有多少人变得聪明，您会感到惊讶. 期望可以利用工作流中的任何错误或差异获取经济利益.

- [After Car2Go eased its background checks, 75 of its vehicles were stolen in one day.](https://archive.is/MuNrZ) -为什么有时需要进行背景检查.

- [Investigation into the Unusual Signups](https://openstreetmap.lu/MWGGlobalLogicReport20181226.pdf)  -在OpenStreetMap上对可疑的贡献者注册进行了非常详细的分析. 这份精美，高水平的报告展示了精心策划和定向的竞选活动，可以作为欺诈报告的模板.

- [MIDAS: Detecting Microcluster Anomalies in Edge Streams](https://github.com/bhatiasiddharth/MIDAS) -提议的方法“使用恒定的时间和内存来检测边缘流中的微团异常或突然到达的可疑相似边缘组”.

- [Gephi](https://github.com/gephi/gephi) -用于可视化和处理大型图形的开源平台.

### Moderation

任何在线社区，不仅是与游戏和社交网络相关的社区，都要求其运营商投入大量资源和精力来进行管理.

- [Still Logged In: What AR and VR Can Learn from MMOs](https://youtu.be/kgw8RLHv1j4?t=534)  -“如果您建立了一个在线社区，人们可能会伤害另一个人：您将陷入困境. 而且，如果您负担不起，请不要托管在线社区”.

- [Keep out the bad apples: How to moderate a marketplace](https://twosided.substack.com/p/keep-out-the-bad-apples-how-to-moderate)  - “拥有权利的同时也被赋予了重大的责任. 我的一些技巧可以使您的市场变得更加安全.”

- [The despair and darkness of people will get to you](https://restofworld.org/2020/facebook-international-content-moderators/)  -庞大的社交网络的管理由外包分包商组成. 这些人处于最糟糕的境地，通常会患上创伤后应激障碍.

- [The Cleaners](https://thoughtmaybe.com/the-cleaners/) -有关这些薪水不足的团队的记录片，其中包括删除帖子和删除帐户.

### Threat Intelligence

如何检测，掩盖和分类攻击性在线活动. 大多数情况下，这些都是由安全，网络和/或基础架构工程团队监视的. 对于T &amp;&amp; S和IAM员工来说，这些仍然是不错的资源，他们可能会被要求提供其他专业知识来分析和处理威胁.

- [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) -“威胁情报的简明定义：基于证据的知识，包括背景，机制，指标，影响和可操作的建议，有关现有或正在出现的威胁或资产危害的信息，可用于为有关主体对威胁的反应做出决策提供依据或危险.”

- [SpiderFoot](https://github.com/smicallef/spiderfoot)  -开源情报（OSINT）自动化工具. 它几乎与每个可用的数据源集成在一起，并使用多种方法进行数据分析，从而使数据易于浏览.

- [Standards related to Threat Intelligence](https://www.threat-intelligence.eu/standards/) -支持威胁情报分析的开放标准，工具和方法.

- [MISP taxonomies and classification](https://www.misp-project.org/taxonomies.html) -用于组织有关“威胁情报，包括网络安全指标，财务欺诈或反恐信息”的信息的标签.

- [Browser Fingerprinting: A survey](https://arxiv.org/pdf/1905.01051.pdf) -指纹可用作识别机器人和欺诈者的信号源.

- [The challenges of file formats](https://speakerdeck.com/ange/the-challenges-of-file-formats)  -一方面，您将允许用户在您的系统中上传文件. 这里有一个 [corpus of suspicious media files](https://github.com/corkami/pocs) 骗子可以利用这些漏洞绕过安全或欺骗用户.

- [SecLists](https://github.com/danielmiessler/SecLists)  -收集在一个地方收集的用于安全评估的多种类型的列表. 列表类型包括用户名，密码，URL，敏感数据模式，模糊有效载荷，Web Shell等.

- [PhishingKitTracker](https://github.com/neonprimetime/PhishingKitTracker) -诱骗者在网络钓鱼工具包中使用的电子邮件地址的CSV数据库.

- [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga)  -仅使用免费资源即可扫描电话号码的工具. 目的是首先以非常好的准确性在任何国际电话号码上收集标准信息，例如国家，地区，运营商和线路类型. 然后在搜索引擎上搜索足迹，以尝试查找VoIP提供商或识别所有者.

- [Confusable Homoglyphs](https://github.com/vhf/confusable_homoglyphs) -象形文字是常见的网络钓鱼技巧.

### Captcha

抵制垃圾邮件发送者的另一道防线.

- [Awesome Captcha](https://github.com/ZYSzys/awesome-captcha) -参考所有开放源代码验证码库，集成，替代方法和破解工具.

- [reCaptcha](https://www.google.com/recaptcha) -当您的公司无法负担起专门的团队来对抗互联网规模的僵尸程序和垃圾邮件发送者时，reCaptcha仍然是一种有效，经济且快速的解决方案.

- [You (probably) don't need ReCAPTCHA](https://kevv.net/you-probably-dont-need-recaptcha/) -首先对服务如何成为隐私的噩梦，以及如何在UI上乏味的问题大声疾呼，然后列出替代方案.

- [Anti-captcha](https://anti-captcha.com) -验证码解决服务.

## Blocklists

防止滥用的第一道机械防线是简单明了的拒绝列表. 这是欺诈斗争的低谷成果，但您会惊讶于它们仍然有效.

- [Bloom Filter](https://en.wikipedia.org/wiki/Bloom_filter)  -非常适合此用例，因为Bloom筛选器旨在快速检查元素是否不在（大）集中. 对于特定的数据类型，存在bloom过滤器的变体.

- [How Radix trees made blocking IPs 5000 times faster](https://blog.sqreen.com/demystifying-radix-trees/) -基数树可能有助于加快IP阻止列表的速度.

### Hostnames and Subdomains

对识别出的客户端，捕获和阻止大量的僵尸程序以及限制dDOS的作用很有用.

- [`hosts`](https://github.com/StevenBlack/hosts) -合并信誉良好的主机文件，并将其合并到一个统一的主机文件中，删除重复项.

- [`nextdns/metadata`](https://github.com/nextdns/metadata) -广泛收集安全，隐私和父母控制的清单.

- [The Public Suffix List](https://publicsuffix.org) -Mozilla的公共后缀注册表，Internet用户可以在该注册表中（或从历史上可以）直接注册名称.

- [Country IP Blocks](https://github.com/herrbischoff/country-ip-blocks) -直接从区域Internet注册表中获取的CIDR国家级IP数据，每小时更新一次.

- [Certificate Transparency Subdomains](https://github.com/internetwache/CT_subdomains) -从证书透明度日志收集的每小时更新的子域列表.

-子域修饰符： [\#1](https://gist.github.com/artgon/5366868), [\#2](https://github.com/sandeepshetty/subdomain-blacklist/blob/master/subdomain-blacklist.txt), [\#3](https://github.com/nccgroup/typofinder/blob/master/TypoMagic/datasources/subdomains.txt), [\#4](https://www.quora.com/How-do-sites-prevent-vanity-URLs-from-colliding-with-future-features).

- [`common-domain-prefix-suffix-list.tsv`](https://gist.github.com/erikig/826f49442929e9ecfab6d7c481870700) -前5000个最常见的域前缀/后缀列表.

- [`hosts-blocklists`](https://github.com/notracking/hosts-blocklists) -不再有广告，跟踪和其他虚拟垃圾.

- [`xkeyscorerules100.txt`](https://gist.github.com/sehrgut/324626fa370f044dbca7) -国家安全局 [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore) TOR和其他匿名保留工具的匹配规则.

- [`pyisp`](https://github.com/ActivisionGameScience/pyisp) -IP到ISP的查找库（包括ASN）.

- [AMF site blocklist](https://www.amf-france.org/Epargne-Info-Service/Proteger-son-epargne/Listes-noires) -法国官方拒绝与金钱有关的欺诈网站.

### Emails

- [Burner email providers](https://github.com/wesbos/burner-email-providers)  -临时电子邮件提供商列表. 和它 [derivative Python module](https://github.com/martenson/disposable-email-domains).

- [MailChecker](https://github.com/FGRibreau/mailchecker) - Cross-language temporary (disposable/throwaway) email detection library.

- [Temporary Email Address Domains](https://gist.github.com/adamloving/4401361)  -一次性和临时电子邮件地址的域列表. 对于过滤电子邮件列表以提高打开率很有用（将电子邮件发送到这些域可能不会打开）.

- [`gman`](https://github.com/benbalter/gman)  -“红宝石，用于检查给定电子邮件地址或网站的所有者是否正在为THE MAN工作（也就是验证政府域名）.” 在您的用户群中寻找潜在政府客户的良好资源.

- [`Swot`](https://github.com/leereilly/swot) -以与上述相同的精神，但这一次标记学术用户.

### Reserved IDs

- [General List of Reserved Words](https://gist.github.com/stuartpb/5710271) -这是在用户可以选择任何名称的系统中，您可能需要考虑保留的常规单词列表.

- [Hostnames and usernames to reserve](https://ldpreload.com/blog/names-to-reserve) -列出所有应限制在自动化系统中注册的名称.

### Profanity

- [List of Dirty, Naughty, Obscene, and Otherwise Bad Words](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words) -Shutterstock的亵渎名单.

- [`profanity-check`](https://github.com/vzhou842/profanity-check) -使用线性SVM模型，对200k个人标记的纯净亵渎文本字符串样本进行训练.

## Privacy

作为用户数据的守护者，IAM堆栈受到隐私保护的深深限制.

- [Privacy Enhancing Technologies Decision Tree](https://www.private-ai.ca/PETs_Decision_Tree.png) -根据数据类型和上下文选择合适工具的流程图.

- [Paper we love: Privacy](https://github.com/papers-we-love/papers-we-love/tree/master/privacy) -有关通过设计提供隐私的方案的科学研究的集合.

- [IRMA Authentication](https://news.ycombinator.com/item?id=20144240) -开源应用程序和协议，可使用以下属性提供基于隐私的基于属性的身份验证和签名： [Camenisch and Lysyanskaya's Idemix](https://privacybydesign.foundation/publications/).

- [Have I been Pwned?](https://haveibeenpwned.com) -数据泄露指数.

- [Automated security testing for Software Developers](https://fahrplan.events.ccc.de/camp/2019/Fahrplan/system/event_attachments/attachments/000/003/798/original/security_cccamp.pdf)  -大多数隐私违规行为是由第三方依赖项中的已知漏洞允许的. 这是如何通过CI / CD检测它们的方法.

- [Email marketing regulations around the world](https://github.com/threeheartsdigital/email-marketing-regulations) -随着世界变得越来越紧密，电子邮件营销法规环境变得越来越复杂.

- [World's Biggest Data Breaches & Hacks](https://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/) -不要成为泄漏您客户数据的下一家公司.

### Anonymization

作为用户数据的中央存储库，IAM堆栈涉众必须防止业务和客户数据的任何泄漏. 为了进行内部分析，需要匿名.

- [The False Allure of Hashing for Anonymization](https://gravitational.com/blog/hashing-for-anonymization/)  -哈希不足以实现匿名化. 但是，对于假名（GDPR所允许的）仍然足够好.

- [Four cents to deanonymize: Companies reverse hashed email addresses](https://freedom-to-tinker.com/2018/04/09/four-cents-to-deanonymize-companies-reverse-hashed-email-addresses/) -“散列的电子邮件地址可以轻松撤消并链接到个人”.

- [Why differential privacy is awesome](https://desfontain.es/privacy/differential-privacy-awesomeness.html) -解释背后的直觉 [differential privacy](https://en.wikipedia.org/wiki/Differential_privacy) ，这是一种理论框架，可在不损害机密性的情况下共享汇总数据. 请参阅以下内容的后续文章 [more details](https://desfontain.es/privacy/differential-privacy-in-more-detail.html) 和 [practical aspects](https://desfontain.es/privacy/differential-privacy-in-practice.html).

- [k-anonymity: an introduction](https://www.privitar.com/listing/k-anonymity-an-introduction) -另一种匿名性隐私模型.

- [Presidio](https://github.com/microsoft/presidio) -用于文本和图像的上下文感知，可插拔和可自定义的数据保护以及PII数据匿名服务.

- [Diffix: High-Utility Database Anonymization](https://aircloak.com/wp-content/uploads/apf17-reprint.pdf) -Diffix尝试提供匿名化，避免假名化并保持数据质量. [Written in Elixir at Aircloak](https://elixirforum.com/t/aircloak-anonymized-analitycs/10930)，它充当分析人员和未修改的实时数据库之间的SQL代理.

### GDPR

著名的欧洲隐私框架

- [GDPR Tracker](https://gdpr.eu) -欧洲参考站点.

- [GDPR Developer Guide](https://github.com/LINCnil/GDPR-Developer-Guide) -开发人员的最佳做法.

- [GDPR – A Practical guide for Developers](https://techblog.bozho.net/gdpr-practical-guide-developers/) -以上内容的一页摘要.

- [GDPR Tracker](https://gdprtracker.io) -跟踪云服务和子处理器的GDPR合规性.

- [GDPR documents](https://github.com/good-lly/gdpr-documents) -个人使用的模板，以使公司遵守“数据访问”要求.

- [Dark Patterns after the GDPR](https://arxiv.org/pdf/2001.02479.pdf) -本文表明，由于缺乏GDPR执法机构，无处不在的模式和暗含的同意.

- [GDPR Enforcement Tracker](http://enforcementtracker.com) -GDPR罚款和罚款清单.

- [Ship Your Enemies GDPR](https://shipyourenemiesgdpr.com) -对GDPR进行武器化，以帮助您向敌人发送数据请求，以尽可能多地浪费他们的时间.

## UX/UI

作为IAM堆栈的涉众，您将在后端实现构建注册隧道和用户入职所需的大多数原语. 这是客户将从您的产品中获得的第一印象，并且不能忽视：您必须与前端专家一起精心设计. 这里有一些指南可以帮助您完善这种体验.

- [The 2020 State of SaaS Product Onboarding](https://userpilot.com/saas-product-onboarding/) -涵盖了用户入职的所有重要方面.

- [User Onboarding Teardowns](https://www.useronboard.com/user-onboarding-teardowns/) -大量的已解构的首次注册用户.

- [Discover UI Design Decisions Of Leading Companies](https://goodui.org/leaks/) -从泄漏的屏幕截图和A / B测试中获取.

- [Conversion Optimization](https://www.nickkolenda.com/conversion-optimization-psychology/#cro-tactic11) -多种策略，以增加用户完成帐户创建渠道的机会.

- [Trello User Onboarding](https://growth.design/case-studies/trello-user-onboarding/) - A detailed case study, nicely presented, on how to improve user onboarding.

- [Don't get clever with login forms](http://bradfrost.com/blog/post/dont-get-clever-with-login-forms/) -创建简单，可链接，可预测的登录表单，并与密码管理器配合使用.

- [Why are the username and password on two different pages?](https://www.twilio.com/blog/why-username-and-password-on-two-different-pages)  -同时支持SSO和基于密码的登录. 现在，如果分两个步骤破坏登录渠道对于用户来说太过激怒了，请像Dropbox那样解决： [an AJAX request when you enter your username](https://news.ycombinator.com/item?id=19174355).

- [HTML attributes to improve your users' two factor authentication experience](https://www.twilio.com/blog/html-attributes-two-factor-authentication-autocomplete)  -“在这篇文章中，我们将介绍不起眼的`<input>  “元素和HTML属性将有助于加快用户的两因素身份验证体验”.

- [Remove password masking](http://passwordmasking.com) -总结了一项学术研究的结果，该研究调查了删除密码屏蔽对消费者信任的影响.

- [For anybody who thinks "I could build that in a weekend," this is how Slack decides to send a notification](https://twitter.com/ProductHunt/status/979912670970249221)  -通知很难. 真的很难.

## Commercial Solutions

- [Rippling IDM](https://www.rippling.com/idm/) -身份管理，SSO.

## Competitive Analysis

一堆资源来跟踪域中所有公司的当前状态和进度.

- [AWS Security, Identity & Compliance announcements](https://aws.amazon.com/about-aws/whats-new/security_identity_and_compliance/) -添加到IAM外围的所有新功能的来源.

- [GCP IAM release notes](https://cloud.google.com/iam/docs/release-notes) -另请注意： [Identity](https://cloud.google.com/identity/docs/release-notes), [Identity Platform](https://cloud.google.com/identity-platform/docs/release-notes), [Resource Manager](https://cloud.google.com/resource-manager/docs/release-notes), [Key Management Service/HSM](https://cloud.google.com/kms/docs/release-notes), [Access Context Manager](https://cloud.google.com/access-context-manager/docs/release-notes), [Identity-Aware Proxy](https://cloud.google.com/iap/docs/release-notes), [Data Loss Prevention](https://cloud.google.com/dlp/docs/release-notes) 和 [Security Scanner](https://cloud.google.com/security-scanner/docs/release-notes).

- [Unofficial Weekly Google Cloud Platform newsletter](https://www.gcpweekly.com) -相关关键字： [`IAM`](https://www.gcpweekly.com/gcp-resources/tag/iam/) 和 [`Security`](https://www.gcpweekly.com/gcp-resources/tag/security/).

- [DigitalOcean Platform changelog](https://www.digitalocean.com/docs/platform/release-notes/)

- [163 AWS services explained in one line each](https://adayinthelifeof.nl/2020/05/20/aws.html#discovering-aws)  -帮助使他们了解庞大的服务目录. 本着同样的精神： [AWS in simple terms](https://netrixllc.com/blog/aws-services-in-simple-terms/) & [AWS In Plain English](https://expeditedsecurity.com/aws-in-plain-english/).

- [Google Cloud Developer's Cheat Sheet](https://github.com/gregsramblings/google-cloud-4-words#the-google-cloud-developers-cheat-sheet) - Describe all GCP products in 4 words or less.

## History

- [cryptoanarchy.wiki](https://cryptoanarchy.wiki)  -Cypherpunks与安全重叠. 该Wiki汇总了有关机芯，其历史以及注释人物/事件的信息.

## Contributing

永远欢迎您的贡献\！ 请看看 [contribution guidelines](https://github.com/kdeldycke/awesome-iam/blob/master/.github/contributing.md) 第一的.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-iam/blob/main/assets/awesome-iam-header.jpg) 基于修改后 [photo](https://unsplash.com/photos/2LowviVHZ-E) 经过 [Ben Sweet](https://unsplash.com/@benjaminsweet).

<!--lint disable no-undefined-references-->

<a name="intro-quote-def">\[1\]</a>: [*Poison Study*](https://amzn.com/0778324338/?tag=kevideld-20) (Mira, 2007). [\[↑\]](#intro-quote-ref)
