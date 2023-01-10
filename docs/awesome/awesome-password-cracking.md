<div class="github-widget" data-repo="n0kovo/awesome-password-cracking"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Password Cracking	 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

在密码分析和计算机安全中，密码破解是从计算机系统中以加密形式存储或传输的数据中恢复密码的过程. 一种常见的方法（[brute-force attack](https://en.wikipedia.org/wiki/Brute-force_attack)) 是反复尝试猜测密码，并根据密码的可用加密哈希检查它们.

这是一个精选的工具、研究、论文和其他与密码破解和密码安全相关的项目的精选列表 [@n0kovo@infosec.exchange](https://infosec.exchange/@n0kovo).


Read [CONTRIBUTING.md](https://github.com/narkopolo/awesome-password-cracking/blob/main/CONTRIBUTING.md) 在贡献之前！ 简而言之：

- 列表按字母顺序排序
- 如有疑问，请使用 [awesome-lint](https://github.com/sindresorhus/awesome-lint)
- 如果您认为某个项目不应该出现在这里 [open an issue](https://github.com/narkopolo/awesome-password-cracking/issues/new)







## Books
- [Hash Crack: Password Cracking Manual (v3)](https://www.amazon.com/-/en/Joshua-Picolet/dp/1793458618) - 密码破解手册 v3 是密码恢复（破解）方法、工具和分析技术的扩展参考指南.



## Cloud
- [Cloud_crack](https://github.com/lordsaibat/Cloud_crack) - 使用 Terraform 和 AWS 破解密码.
- [Cloudcat](https://github.com/stormfleet/cloudcat) - 用于自动创建用于哈希破解的云基础设施的脚本.
- [Cloudstomp](https://github.com/Fmstrat/cloudstomp) - 通过插件以最低的价格在 EC2 上自动部署实例，用于高 CPU/GPU 应用程序.
- [Cloudtopolis](https://github.com/JoelGMSec/Cloudtopolis) - 一种有助于在 Google Cloud Shell 平台上安装和配置 Hashtopolis 的工具，快速且完全无人值守（而且免费！）.
- [NPK](https://github.com/c6fc/npk) - NPK 是一个分布式哈希破解平台，完全由 AWS 中的无服务器组件构建，包括 Cognito、DynamoDB 和 S3.
- [Penglab](https://github.com/mxrch/penglab) - 滥用 Google Colab 破解哈希.
- [Rook](https://github.com/JumpsecLabs/Rook) - 自动创建用于基于 GPU 的密码破解的 AWS p3 实例.


## Conversion
- [7z2hashcat](https://github.com/philsmd/7z2hashcat) - 从受密码保护的 .7z 档案（和 .sfx 文件）中提取信息，以便您可以使用 hashcat 破解这些“哈希”.
- [MacinHash](https://github.com/jmagers/MacinHash) - 将 macOS plist 密码文件转换为密码破解者的哈希文件.
- [NetNTLM-Hashcat](https://github.com/ins1gn1a/NetNTLM-Hashcat) - 将 John The Ripper/Cain 格式的哈希（单个或批量）转换为 HashCat 兼容的哈希格式.
- [Rubeus-to-Hashcat](https://github.com/PwnDexter/Rubeus-to-Hashcat) - 将 Rubeus kerberoasting 输出转换/格式化为 hashcat 可读格式.
- [WINHELLO2hashcat](https://github.com/Banaanhangwagen/WINHELLO2hashcat)  - 使用此工具可以从 WINDOWS HELLO PIN 中提取“哈希”. 这个哈希可以用 Hashcat 破解.
- [bitwarden2hashcat](https://github.com/0x6470/bitwarden2hashcat) - 将 Bitwarden 的数据转换为适合 hashcat 的哈希的工具.
- [hc\_to\_7z](https://github.com/philsmd/hc_to_7z) - 将 7-Zip hashcat 哈希转换回 7z 档案.
- [hcxtools](https://github.com/ZerBea/hcxtools) - 用于将 cap/pcap/pcapng（gz 压缩）WiFi 转储文件转换为 hashcat 格式的便携式解决方案.
- [itunes_backup2hashcat](https://github.com/philsmd/itunes_backup2hashcat) - 从 Manifest.plist 文件中提取所需的信息，将其转换为与 hashcat 兼容的哈希值.	
- [mongodb2hashcat](https://github.com/philsmd/mongodb2hashcat) - 从 MongoDB 数据库服务器中提取哈希为 hashcat 接受的哈希格式：-m 24100 (SCRAM-SHA-1) 或 -m 24200 (SCRAM-SHA-256).



## Hashcat
*[Hashcat](https://github.com/hashcat/hashcat) 是“世界上最快、最先进的密码恢复实用程序”. 以下是以某种方式与 Hashcat 直接相关的项目.*

- [Autocrack](https://github.com/pry0cc/autocrack) - 一组客户端和服务器工具，用于自动和轻松地自动破解哈希.
- [docker-hashcat](https://github.com/dizcza/docker-hashcat) - 适用于 Ubuntu 18.04 CUDA、OpenCL 和 POCL 的最新 hashcat docker.
- [hashcat.launcher](https://github.com/s77rt/hashcat.launcher) - Hashcat.launcher 是一个运行和控制 hashcat 的跨平台 GUI 应用程序.
- [Hashcat-Stuffs](https://github.com/xfox64x/Hashcat-Stuffs) - hashcat 列表和事物的集合.
- [hashcat-utils](https://github.com/hashcat/hashcat-utils/) - 可用于高级密码破解的小型实用程序.
- [Hashfilter](https://github.com/bharshbarger/Hashfilter) - 读取 hashcat potfile 并将不同类型解析为 sqlite 数据库.
- [known_hosts-hashcat](https://github.com/chris408/known_hosts-hashcat) - 使用 hashcat 破解 ssh known_hosts 文件的指南和工具.
- [pyhashcat](https://github.com/f0cker/pyhashcat) - 绑定到 libhashcat 的 Python C API.


### Automation
- [autocrack](https://github.com/timbo05sec/autocrack) - Hashcat 包装器帮助自动化破解过程.
- [hat](https://github.com/sp00ks-git/hat) - 一个用于常见单词列表和规则的自动化 Hashcat 工具，以加快在参与期间破解哈希的过程.
- [hate_crack](https://github.com/trustedsec/hate_crack) - 通过 TrustedSec 团队的 Hashcat 自动化破解方法的工具.
- [Naive hashcat](https://github.com/brannondorsey/naive-hashcat) - 朴素的 hashcat 是一个即插即用的脚本，它预先配置了朴素的、经过经验测试的、“足够好”的参数/攻击类型.

### Distributed cracking
- [CrackLord](https://github.com/jmmcatee/cracklord) - 用于破解密码的队列和资源系统.
- [fitcrack](https://github.com/nesfit/fitcrack) - 基于hashcat的分布式密码破解系统.
- [Hashtopolis](https://github.com/hashtopolis/server) - 用于将 hashcat 任务分发到多台计算机的多平台客户端-服务器工具.
- [HashtopoloCLI](https://github.com/jakewnuk/HashtopoCLI) - 用于 Hashtopolis API 的 CLI 工具，将一些 API 功能合并到动态 Python 包装器中.
- [Kraken](https://github.com/arcaneiceman/kraken) - 多平台分布式暴力密码破解系统.

### Rules
- [clem9669 rules](https://github.com/clem9669/hashcat-rule) - hashcat 或 john 的规则.
- [hashcat rules collection](https://github.com/narkopolo/hashcat-rules-collection) - 可能是目前最大的 hashcat 规则集.
- [Hob0Rules](https://github.com/praetorian-inc/Hob0Rules) - Password cracking rules for Hashcat based on statistics and industry patterns.
- [Kaonashi](https://github.com/kaonashi-passwords/Kaonashi) - 来自 Kaonashi 项目（RootedCON 2019）的词汇表、规则和掩码.
- [nsa-rules](https://github.com/NSAKEY/nsa-rules) - 从破解密码生成的hashcat密码破解规则和掩码.
- [nyxgeek-rules](https://github.com/nyxgeek/nyxgeek-rules) - Hashcat 和 John the Ripper 的自定义密码破解规则.
- [OneRuleToRuleThemAll](https://github.com/NotSoSecure/password_cracking_rules) - “破解所有密码的一条规则.或者至少我们希望如此.”
- [pantagrule](https://github.com/rarecoil/pantagrule) - 从现实世界中泄露的密码生成的大型 hashcat 规则集.
- [squid rules](https://github.com/jakewnuk/HIBP-578M) - 根据 HIBPv7 测试的有效性排序的 Hashcat 规则.

### Rule tools
- [duprule](https://github.com/mhasbini/duprule) - 检测和过滤重复的 hashcat 规则.


### Web interfaces
- [crackerjack](https://github.com/ctxis/crackerjack) - CrackerJack 是用 Python 开发的 Hashcat 的 Web GUI.
- [CrackQ](https://github.com/f0cker/crackq) - 一个Python Hashcat破解队列系统.
- [hashpass](https://github.com/dj-zombie/hashpass) - hashcat 的哈希破解 WebApp 和服务器.
- [Hashview](https://github.com/hashview/hashview) - 用于密码破解和分析的 Web 前端.
- [Wavecrack](https://github.com/wavestone-cdt/wavecrack) - Wavestone 的 Web 界面，用于使用 hashcat 破解密码.
- [WebHashCat](https://github.com/hegusung/WebHashcat) - WebHashcat 是一个非常简单但高效的网页界面的 hashcat 密码破解工具.



## John the Ripper
*[John the Ripper](https://github.com/openwall/john) 是“可用于许多操作系统的开源密码安全审计和密码恢复工具”. 以下是以某种方式与开膛手约翰直接相关的项目. *

- [BitCracker](https://github.com/e-ago/bitcracker) - BitCracker 是第一个用于使用 BitLocker 加密的内存单元的开源密码破解工具.
- [johnny](https://github.com/openwall/johnny) - 开膛手约翰的 GUI 前端.



## Misc
- [920mPasswordMasks](https://github.com/jakewnuk/920mPasswordMasks) - 从过滤到组中的 9.2 亿个泄露密码中提取的 Hashcat 密码掩码.
- [hashID](https://github.com/psypanda/hashID) - 识别不同类型散列的软件.
- [Name That Hash](https://github.com/HashPals/Name-That-Hash)  - 不知道它是什么类型的哈希？  Name That Hash 将命名该哈希类型！ 识别 MD5、SHA256 和 300 多种其他哈希值. 带有简洁的网络应用程序.


### People to Follow
- 水解 ([GitHub](https://github.com/Hydraze) / [Mastodon](https://infosec.exchange/@hydraze) / [Twitter](https://twitter.com/Hydraze))
- NSAKEY ([GitHub](https://github.com/NSAKEY) / [Twitter](https://twitter.com/_NSAKEY) / [Website](https://abigisp.com/))
- 空模式 ([GitHub](https://github.com/NullMode) / [Mastodon](https://infosec.exchange/@nullmode_@twtr.plus) / [Twitter](https://twitter.com/nullmode_))
- 修理工 （[GitHub](https://github.com/th3mechanic) / [Twitter](https://twitter.com/th3_m3chan1c))
- 有毒的 （[Twitter](https://twitter.com/yiannistox))
- Alotdv ([Twitter](https://twitter.com/AlongExc))
- Coolbry95 ([GitHub](https://github.com/coolbry95) / [Twitter](https://twitter.com/coolbry95))
- 达基基拉 ([GitHub](https://github.com/dakykilla) / [Twitter](https://twitter.com/dakykilla))
- Droppermit ([GitHub](https://github.com/dropdeadfu) / [Twitter](https://twitter.com/dropdeadfu))
- Epixoip ([GitHub](https://github.com/epixoip) / [Mastodon](https://infosec.exchange/@epixoip) / [Twitter](https://twitter.com/jmgosney))
- 邪恶之魔 ([GitHub](https://github.com/evilmog/) / [Mastodon](https://infosec.exchange/@evilmog) / [Twitter](https://twitter.com/Evil_Mog))
- 对比 23 ([GitHub](https://github.com/kontrast23) / [Twitter](https://twitter.com/marco_preuss))
- M3g9tr0n ([GitHub](https://github.com/m3g9tr0n) / [Twitter](https://twitter.com/m3g9tr0n))
- 矩阵 （[GitHub](https://github.com/matrix) / [Twitter](https://twitter.com/gm4tr1x))
- 荆棘 ([Twitter](https://twitter.com/mingadotcom))
- 诺科沃 ([GitHub](https://github.com/n0kovo) / [Mastodon](https://infosec.exchange/@n0kovo) / [Twitter](https://twitter.com/n0kovos))
- 哲学家 ([GitHub](https://github.com/philsmd) / [Twitter](https://twitter.com/philsmd))
- 罗伊斯威廉姆斯 ([GitHub](https://github.com/roycewilliams) / [Mastodon](https://infosec.exchange/@tychotithonus) / [Twitter](https://twitter.com/TychoTithonus))
- RuraPenthe ([GitHub](https://github.com/bitcrackcyber) / [Mastodon](https://infosec.exchange/@rurapenthe) / [Twitter](https://twitter.com/RuraPenthe0))
- S3in!c ([GitHub](https://github.com/s3inlc) / [Mastodon](https://infosec.exchange/@s3inlc) / [Twitter](https://twitter.com/s3inlc))
- Tehnlulz（[GitHub](https://github.com/tehnlulz) / [Twitter](https://twitter.com/tehnlulz))
- 亡灵 ([GitHub](https://github.com/undeath))
- Unix 忍者 ([GitHub](https://github.com/unix-ninja) / [Mastodon](https://infosec.exchange/@unix_ninja@twitterbridge.jannis.rocks) / [Twitter](https://twitter.com/unix_ninja))
- 汗 ([GitHub](https://github.com/Xanadrel) / [Mastodon](https://infosec.exchange/@Xanadrel) / [Twitter](https://twitter.com/Xanadrel))
- Paule965 ([Twitter](https://twitter.com/paule965))



## Websites

### Communities
- [hashcat Forum](https://hashcat.net/forum/) - hashcat 开发者的论坛.
- [Hashmob](https://hashmob.net/) - 一个不断壮大的密码恢复社区，旨在成为密码学爱好者的协作中心.
- [Hashkiller Forum](https://forum.hashkiller.io/) - 拥有超过 20,000 名注册用户的密码破解论坛.

### Lookup services
- [CMD5](https://www.cmd5.org/) - 提供在线MD5/sha1/mysql/sha256加解密服务.
- [CrackStation](https://crackstation.net/) - 免费的散列查找服务也提供单词列表.
- [Hashes.com](https://hashes.com/) - 具有付费功能的哈希查找服务.
- [Hashkiller](https://hashkiller.io/) - 带有论坛的散列查找服务.
- [Online Hash Crack](https://www.onlinehashcrack.com/) - 云密码恢复服务.



## Wordlist tools
*用于分析、生成和操作词表的工具.*

### Analysis
- [PACK](https://github.com/iphelix/pack) - 为帮助分析密码列表而开发的一组实用程序，以便通过掩码、规则、字符集和其他密码特征的模式检测来增强密码破解.
- [pcfg_cracker](https://github.com/lakiw/pcfg_cracker) - 该项目使用机器学习来识别用户的密码创建习惯.
- [Pipal](https://github.com/digininja/pipal) - 密码分析器.
- [PwdStat](https://github.com/jakewnuk/pwdstat) - 用于识别系统密码使用情况、创建密码掩码以及使用人类可读统计数据分析破解密码样本的工具，以帮助防御者.


### Generation/Manipulation

- [common-substr](https://github.com/sensepost/common-substr)  - 从输入文本中提取最常见子字符串的简单工具. 专为破解密码而设计.
- [Crunch](https://sourceforge.net/projects/crunch-wordlist/)  - Crunch 是一个单词列表生成器，您可以在其中指定标准字符集或您指定的字符集.  Crunch 可以生成所有可能的组合和排列.
- [CUPP](https://github.com/Mebus/cupp) - 一种工具，可让您通过用户分析数据（例如生日、昵称、地址、宠物或亲戚的名字等）生成词表.
- [duplicut](https://github.com/nil0x42/duplicut) - 从 MASSIVE wordlist 中删除重复项，而不对其进行排序（用于基于字典的密码破解）.
- [Gorilla](https://github.com/d4rckh/gorilla) - 用于生成单词列表或使用突变扩展现有单词列表的工具.
- [Elpscrk](https://github.com/D4Vinci/elpscrk) - Elpscrk 就像 cupp，但它基于排列和统计数据，同时具有内存效率.
- [Keyboard-Walk-Generators](https://github.com/Rich5/Keyboard-Walk-Generators) - 生成用于破解的 Keyboard Walk 词典.
- [kwprocessor](https://github.com/hashcat/kwprocessor) - 具有可配置的基本字符、键盘映射和路线的高级键盘行走生成器.
- [maskcat](https://github.com/jakewnuk/maskcat) - 用于 Hashcat 掩码和密码破解的实用工具.
- [maskprocessor](https://github.com/hashcat/maskprocessor/) - 具有按位置可配置字符集的高性能单词生成器.
- [maskuni](https://github.com/flbdx/maskuni) - 一个独立的快速单词生成器，本着 hashcat 的掩码生成器的精神，支持 unicode.
- [Mentalist](https://github.com/sc0tfree/mentalist)  - Mentalist 是用于自定义单词列表生成的图形工具. 它利用常见的人类范例来构建密码，并可以输出完整的单词列表以及与 Hashcat 和 John the Ripper 兼容的规则.
- [Phraser](https://github.com/Sparell/Phraser) - Phraser 是一个短语生成器，使用 n-gram 和马尔可夫链来生成用于密码短语破解的短语.
- [princeprocessor](https://github.com/hashcat/princeprocessor) - 使用 PRINCE 算法的独立密码候选生成器.
- [Rephraser](https://github.com/travco/rephraser) - 基于 Python 的 Phraser 重新构想，使用马尔可夫链进行语言正确的密码破解.
- [Rling](https://github.com/Cynosureprime/rling) - RLI Next Gen (Rling)，一种更快的多线程、功能丰富的替代品，可替代 hashcat 实用程序中的 rli.
- [statsprocessor](https://github.com/hashcat/statsprocessor/) - 基于每个位置的马尔可夫链的单词生成器.
- [TTPassGen](https://github.com/tp7309/TTPassGen) - 灵活且可编写脚本的密码字典生成器，支持暴力破解、组合、复杂规则模式等.
- [token-reverser](https://github.com/dariusztytko/token-reverser) - 用于破解安全令牌的单词列表生成器.
- [WikiRaider](https://github.com/NorthwaveSecurity/wikiraider) - WikiRaider 使您能够根据特定国家/地区的维基百科数据库生成词汇表.




## Wordlists
### Laguage specific
- [Albanian wordlist](https://github.com/its0x08/albanian-wordlist) - 名字、姓氏和一些阿尔巴尼亚文学的混合体.
- [Danish Phone Wordlist Generator](https://github.com/narkopolo/danish_phone_wordlist_generator) - 此工具可以按地区和/或用途（手机、固定电话等）生成丹麦电话号码的单词列表.对于破解密码或模糊丹麦语目标很有用.
- [Danish Wordlists](https://github.com/narkopolo/danish-wordlists) - 用于破解丹麦语密码的丹麦语词汇表集合.
- [French Wordlists](https://github.com/clem9669/wordlists) - 该项目旨在提供有关人们可以用作基本密码的所有内容的法语单词列表.

### Other
- [Packet Storm Wordlists](https://packetstormsecurity.com/Crackers/wordlists/page1/) - 多种语言的大量不同单词列表.
- [Rocktastic](https://labs.nettitude.com/tools/rocktastic/) - 包括许多在野外观察到的密码和模式排列.
- [RockYou2021](https://github.com/ohmybahgosh/RockYou2021.txt) - RockYou2021.txt 是一个由各种其他单词列表编译而成的 MASSIVE WORDLIST.
- [WeakPass](https://weakpass.com/) - Collection of large wordlists.



## Specific file formats
### PDF
- [pdfrip](https://github.com/mufeedvh/pdfrip) - 多线程 PDF 密码破解实用程序，配备常见的密码格式生成器和字典攻击.

### PEM
- [pemcracker](https://github.com/bwall/pemcracker) - 破解加密 PEM 文件的工具.

### JKS
- [JKS private key cracker](https://github.com/floyd-fuh/JKS-private-key-cracker-hashcat) - 破解JKS文件中私钥条目的密码Cracking passwords of private key entries in a JKS file.

### ZIP
- [bkcrack](https://github.com/kimci86/bkcrack) - 使用 Biham 和 Kocher 已知的明文攻击破解旧版 zip 加密.
- [frackzip](https://github.com/hyc/fcrackzip) - 破解加密 ZIP 压缩文件的小工具.



## Artificial Intelligence
- [adams](https://github.com/TheAdamProject/adams) - 通过深度学习和动态词典减少对真实世界密码强度建模的偏差.
[](https://github.com/cupslab/neural_network_cracking) - 使用神经网络破解密码的代码.
- [RNN-Passwords](https://github.com/gehaxelt/RNN-Passwords) - 使用 char-rnn 学习和猜测密码.
- [rulesfinder](https://github.com/synacktiv/rulesfinder) - 此工具为给定的字典和密码列表找到有效的密码修改规则（对于 John the Ripper 或 Hashcat）.



## Research

### Articles and Blog Posts
- [Optimizing Wordlists with Masks](https://jakewnuk.com/posts/optimizing-wordlists-w-masks/)
-  [Purple Rain Attack - Password Cracking With Random Generation](https://www.netmux.com/blog/purple-rain-attack)
- [Smashing Hashes with Token Swapping Attacks](https://jakewnuk.com/posts/token-swapping-attack/)

### Papers
- [Generating Optimized Guessing Candidates toward Better Password Cracking from Multi-Dictionaries Using Relativistic GAN (2020)](https://www.mdpi.com/2076-3417/10/20/7306/htm)
- [GENPass: A General Deep Learning Model for Password Guessing with PCFG Rules and Adversarial Generation (2018)](https://ieeexplore.ieee.org/document/8422243)
- [Password Cracking Using Probabilistic Context-Free Grammars (2009)](https://www.researchgate.net/publication/220713709_Password_Cracking_Using_Probabilistic_Context-Free_Grammars)
- [Reducing Bias in Modeling Real-world Password Strength via Deep Learning and Dynamic Dictionaries (2020)](https://arxiv.org/abs/2010.12269)
- [Fast, Lean, and Accurate: Modeling Password Guessability Using Neural Networks (2016)](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/melicher)
- [PassGAN: A Deep Learning Approach for Password Guessing (2017)](https://arxiv.org/pdf/1709.00440)

### Talks
- [DEF CON Safe Mode Password Village - Getting Started with Hashcat](https://www.youtube.com/watch?v=MBTJ8f6Fsmg)
- [DEF CON Safe Mode Password Village - Jeremi Gosney - Cracking at Extreme Scale](https://www.youtube.com/watch?v=4Ell1Tt23NI)
- [Tailored, Machine Learning-driven Password Guessing Attacks and Mitigation at DefCamp](https://www.youtube.com/watch?v=iK6ZbD6v9Gg)
- [UNHash - Methods for better password cracking](https://media.ccc.de/v/31c3_-_5966_-_en_-_saal_1_-_201412292245_-_unhash_-_methods_for_better_password_cracking_-_tonimir_kisasondi)
- [USENIX Security '21 - Reducing Bias in Modeling Real-world Password Strength via Deep Learning and Dynamic Dictionaries](https://www.youtube.com/watch?v=Jvp3UTdCeag)
- [USENIX Security &#39;16 - 快速、精益和准确：使用神经网络对密码可猜测性进行建模
](https://www.youtube.com/watch?v=GgaZ_LxsL_8)
