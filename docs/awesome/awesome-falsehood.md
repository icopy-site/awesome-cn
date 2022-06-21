<div class="github-widget" data-repo="kdeldycke/awesome-falsehood"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## 😱 Awesome Falsehood [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

**精心挑选的程序员相信的谎言清单.**

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-falsehood/">
    <img src="https://raw.githubusercontent.com/kdeldycke/awesome-falsehood/raw/main/assets/awesome-falsehood-header.jpg" alt="Awesome Falsehood header image">
  </a>
</p>

<p align="center">
  <br>
  — Ludwig Wittgenstein<sup id="intro-quote-ref"><a href="#intro-quote-def">[1]</a></sup>
</p>

*错误*是您最初认为是正确的**想法*，但实际上，它被**证明是错误的**.

例如 *idea*：有效的电子邮件地址正好有一个 `@` 字符. 因此，您将使用此规则来实现您的电子邮件字段验证逻辑. 正确的？ 错误的！  *现实*是：电子邮件可以有多个 `@` 字符. 因此，您的实现应该允许这样做. 最初的 *idea* 是您所相信的谎言.

下面列出的 *falsehood* 文章将全面列出您应该注意的那些错误信念，以帮助您成为更好的程序员.


<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->


<!-- mdformat-toc end -->

## Meta

- [Falsehoods Programmers Believe](https://spaceninja.com/2015/12/07/falsehoods-programmers-believe/)  - 常见谎言的简短列表. 对谎言世界的精彩概述和快速介绍.
- [Falsehoods about Programming](https://chiselapp.com/user/ttmrichter/repository/gng/doc/trunk/output/falsehoods.html) - 关于编程和程序员本身的谦逊和有趣的列表.
- [Falsehoods about Falsehoods Lists](https://kevin.deldycke.com/2016/12/falsehoods-programmers-believe-about-falsehoods-lists/) - 关于如何处理这些谎言的元评论.

## Arts

- [Falsehoods about Music](https://literateprogrammer.blogspot.fr/2016/07/falsehoods-programmers-believe-about.html) - 在编纂音乐时可能做出的错误假设.
- [Falsehoods about Art](http://artsy.github.io/blog/2018/04/18/programmer-misconceptions-about-art/) - 关于艺术的常见误解.

## Business

- [Falsehoods about Online Shopping](https://wiesmann.codiferes.net/wordpress/archives/22201) - 涵盖价格、货币和库存.
- [Falsehoods about Prices](https://gist.github.com/rgs/6509585) - 涵盖货币、金额和本地化.
- [Falsehoods about IBANs](https://github.com/globalcitizen/php-iban/blob/master/docs/FALSEHOODS.md) - International Bank Account Numbers are not international.
- [Falsehoods about Economics](http://exple.tive.org/blarg/2016/09/22/falsehoods-programmers-believe-about-economics/) - 经济学并不简单或理性.
- [Falsehoods about Cars](https://github.com/driveto/falsehoods-about-cars) - 即使像定义汽车这样常见的事情也充满了陷阱.
- [Falsehoods about Airline Seat Maps](https://duffel.com/blog/falsehoods-about-seat-maps) - 航空公司的座位图远比整齐排列的座位要复杂得多.
- [Decimal Point Error in Etsy's Accounting System](https://www.reddit.com/r/Etsy/comments/hz4877/if_you_are_an_etsy_seller_do_not_purchase_postage/) - 会计软件中类型的重要性：缺少小数点最终会导致 100 倍的超额收费.
- [Characters `<` and `>` in company names lead to XSS attacks](https://forum.aws.chdev.org/t/cross-site-scripting-xss-software-attack/3355) - 因为 [UK allows companies to be registered with special characters](https://www.legislation.gov.uk/uksi/2015/17/schedule/1/made) ，黑客利用他们注册了`\&quot;&gt;<SCRIPT SRC=MJT.XSS.HT></SCRIPT>  LTD`，还有`; 删除表“公司”；--LTD`、`BETTS &amp; TWINE LTD` 和`SAFDASD &amp; SFSAF \&#39; SFDAASF\&quot; LTD`.
- [CLDR currency definitions](https://github.com/unicode-org/cldr/blob/release-40/common/supplemental/supplementalData.xml#L87-L94) - 由于叛乱、入侵、新宪法和计划采用缓慢，货币有效日期范围重叠.
- [`tax`](https://github.com/commerceguys/tax) - PHP 5.4+ 税务管理库.

## Dates and Time

- [Falsehoods about Time](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time) - 关于日期和时间的开创性文章.
- [More Falsehoods about Time](http://infiniteundo.com/post/25509354022/more-falsehoods-programmers-believe-about-time)  - 部分.  2 上面的文章.
- [Falsehoods about Time and Time Zones](https://www.creativedeletion.com/2015/01/28/falsehoods-programmers-date-time-zones.html) - 另一个采用与时间相关的谎言，强调时区.
- [Critique of Falsehoods about Time](https://gist.github.com/thanatos/eee17100476a336a711e) - 承接上面的第一篇文章，并提供了对每个谎言的解释，以及更多的背景和外部资源.
- [Falsehoods about Unix Time](https://alexwlchan.net/2019/05/falsehoods-programmers-believe-about-unix-time/) - 注意闰秒！
- [Falsehoods about Time Zones](https://www.zainrizvi.io/blog/falsehoods-programmers-believe-about-time-zones/) - 关于 DST 转换的边缘情况有一些很好的观点.
- [Your Calendrical Fallacy Is Thinking…](http://yourcalendricalfallacyis.com) - 涵盖嵌入和文化影响的列表，由 iOS 和 macOS 开发人员社区制作.
- [Time Zone Database](https://www.iana.org/time-zones) - 代表全球许多代表性地点的当地时间历史的代码和数据.
- [The Long, Painful History of Time](http://naggum.no/lugm-time.html) - 计时中的大多数特质都可以在历史中找到解释.
- [You Advocate a Calendar Reform](https://qntm.org/calendar)  - 你的想法行不通. 这篇文章告诉你为什么.
- [So You Want to Abolish Time Zones](https://qntm.org/abolish) - 取消时区听起来可能是个好主意，但有很多复杂情况使其并非如此.
- [The Problem with Time & Timezones](https://www.youtube.com/watch?v=-5wpm-gesOY) - 如果你能提供帮助，一个关于为什么你永远不应该处理时区的视频.
- [\$26,000 Overcollection by Labor Department](http://digital.vpr.net/post/rounding-error-computer-code-leads-26000-overcollection-labor-department) - 错误的日历会计的后果.
- [RFC-3339 vs ISO-8601](https://ijmacd.github.io/rfc3339-iso8601/) - 来自两个标准的巨大格式列表、它们如何重叠以及实时示例.
- [ISO-8601, `YYYY`, `yyyy`, and why your year may be wrong](https://ericasadun.com/2018/12/25/iso-8601-yyyy-yyyy-and-why-your-year-may-be-wrong/) - 日期的字符串格式很难.
- [UTC is Enough for everyone, right?](https://zachholman.com/talk/utc-is-enough-for-everyone-right) - 关于日期和时间（特别是 UTC）有一些你可能没有想到的极端情况.
- [Storing UTC is not a silver bullet](https://codeblog.jonskeet.uk/2019/03/27/storing-utc-is-not-a-silver-bullet/) - “仅以 UTC 存储日期”并不总是正确的方法.
- [How to choose between UT1, TAI and UTC](https://news.ycombinator.com/item?id=28047376) - 取决于您在 SI 秒、地球自转同步、闰秒避免之间的优先级.
- [Why is subtracting these two times (in 1927) giving a strange result?](https://stackoverflow.com/a/6841479/57311) - 臭名昭著的 Stack Overflow 回答关于复杂的历史时区，以及如何通过较新版本的软件重新解释历史日期.
- [Critical and Significant Dates](https://web.archive.org/web/20150908004245/http://www.merlyn.demon.co.uk/critdate.htm) - 从 Y2K 到 Unix 纪元的 32 位秒溢出，根据系统需要注意的特殊日期列表.

## Education

- [Falsehoods CS Students (Still) Believe Upon Graduating](https://www.netmeister.org/blog/cs-falsehoods.html) - 一份清单（不仅）计算机科学专业的学生倾向于错误地并且有时令人惊讶地相信，即使他们（可能）应该知道得更好.
- [Postdoc myths](https://www.cs.kent.ac.uk/people/staff/srk21/blog/2019/12/02/) - `很多关于博士后研究人员的言论、写作和信仰都是不真实的.`.

## Emails

- [I Knew How to Validate an Email Address Until I Read the RFC](https://haacked.com/archive/2007/08/21/i-knew-how-to-validate-an-email-address-until-i.aspx/) - 提供复杂的示例，这些示例是根据 RFC-822 未怀疑的有效电子邮件地址.
- [So you think you can validate email addresses (FOSDEM 2018)](https://fosdem.org/2018/schedule/event/email_address_quiz/) - 展示极端情况的电子邮件地址以及为什么不应该使用正则表达式来解析它们.
- [Your E-Mail Validation Logic is Wrong](https://www.netmeister.org/blog/email.html) - 电子邮件地址中允许的各种令人惊讶的事情的摘要.

## Geography

- [Falsehoods about Geography](https://wiesmann.codiferes.net/wordpress/archives/15187) - 采用地点、名称和位置.
- [Falsehoods about Maps](http://www.atlefren.net/post/2014/09/falsehoods-programmers-believe-about-maps/) - Covers coordinates, projection and GIS.
- [Falsehoods about Maps Data](http://www.atlefren.net/post/2014/09/falsehoods-programmers-believe-about-maps/) - 地缘政治的复杂性需要在数据结构中具体化.
- [I Hate Coordinate Systems](https://ihatecoordinatesystems.com) - 地理空间从业人员关于诊断和修复坐标系常见问题的指南.
- [Top 5 most insane kanji place names in Japan](https://soranews24.com/2016/12/01/w-t-f-japan-top-5-most-insane-kanji-place-names-in-japan%e3%80%90weird-top-five%e3%80%91/) - “有一组特殊的汉字，即使是日本人也很难阅读：地名.”

## Human Identity

- [Falsehoods about Names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/) - 开始这一切的文章.
- [Falsehoods about Names – With Examples](https://shinesolutions.com/2018/01/08/falsehoods-programmers-believe-about-names-with-examples/) - 上述文章的重新审视版本，这次有详细的解释.
- [Falsehoods about Biometrics](https://shkspr.mobi/blog/2021/01/falsehoods-programmers-believe-about-biometrics/) - 指纹不是唯一的.
- [Falsehoods about Families](https://shkspr.mobi/blog/2017/03/falsehoods-programmers-believe-about-families/) - 你不能真正定义一个有严格规则的家庭.
- 关于性别的谎言： [#1](https://gist.github.com/garbados/f82604ea639e0e47bf44) & [#2](https://medium.com/gender-2-0/falsehoods-programmers-believe-about-gender-f9a3512b4c9c) - 性别是人类身份的一部分，有其自身的微妙之处.
- [Falsehoods about Me](https://skylarmacdonald.com/falsehoods/) - 姓名与性别和国际化的交叉问题.
- [Gay Marriage: The Database Engineering Perspective](https://web.archive.org/web/20170914014648/https://qntm.org/gay) - 如何将婚姻存储在数据库中，同时解决关于性别、命名和关系的大部分谎言.
- [Personal Names Around the World](https://www.w3.org/International/questions/qa-personal-names) - 世界各地人们的名字有何不同，对 Web 有何影响？
- [XKCD #327: Exploits of a Mom](https://xkcd.com/327/) - 关于虚假的实施如何导致安全漏洞的有趣看法.
- [Hello, I'm Mr. Null. My Name Makes Me Invisible to Computers](https://www.wired.com/2015/11/null/) - 现实生活中的例子，说明虚假如何对某人的生活产生负面影响.
- [My name causes an issue with any booking!](https://travel.stackexchange.com/questions/149323/my-name-causes-an-issue-with-any-booking-names-end-with-mr-and-mrs) - 旧的航空公司预订系统将“MR”后缀视为“先生”并将其删除.
- [HL7 v3 RIM](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=186) - 用于表示人名的灵活数据模型.
- [Apple iOS `NSPersonNameComponentsFormatter`](https://developer.apple.com/library/ios/documentation/Miscellaneous/Reference/NSPersonNameComponentsFormatter_Class/index.html) - 人名组成部分的本地化表示.

## Internationalization

关于字符编码、字符串格式化、unicode 和国际化.

- [Falsehoods about Language](http://garbled.benhamill.com/2017/04/18/falsehoods-programmers-believe-about-language) - 从英语翻译软件并不像看起来那么简单.
- [Falsehoods about Plain Text](https://jeremyhussell.blogspot.com/2017/11/falsehoods-programmers-believe-about.html#main) - 纯文本无法切割它，这使得 Unicode 更令人难以置信，因为它能够很好地工作.
- [Falsehoods about text](https://wiesmann.codiferes.net/wordpress/archives/30296) - 上面的谎言的一个子集，用一些例子来说明.
- [Internationalis(z)ing Code](https://www.youtube.com/watch?v=0j74jcxSunY) - 有关在国际化代码时需要记住的事项的视频.
- [Minimum to Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) - 很好地介绍了 unicode、它的历史背景和起源，然后概述了它的内部工作.
- [Awesome Unicode](https://github.com/Wisdom/Awesome-Unicode) - 令人愉快的 Unicode 花絮、包和资源的精选列表.
- [Dark corners of Unicode](https://eev.ee/blog/2015/09/12/dark-corners-of-unicode/) - Unicode 很广泛，这里是龙.
- [Let's Stop Ascribing Meaning to Code Points](https://manishearth.github.io/blog/2017/01/14/stop-ascribing-meaning-to-unicode-code-points/) - 深入了解 Unicode 并消除关于代码点的神话.
- [Breaking Our `Latin-1` Assumptions](https://manishearth.github.io/blog/2017/01/15/breaking-our-latin-1-assumptions/) - 大多数程序员在 `Latin-1` 上花费了太多时间，他们忘记了其他脚本的怪癖.
- [Ode to a shipping label](http://i.imgur.com/4J7Il0m.jpg) - 字符编码很难，当数据输入的每个损坏层添加自己的香料时更是如此.
- [i18n Testing Data](https://github.com/patch/i18n-testing) - 为单元测试和 QA 编译真实的国际和多样化名称数据.
- [Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)  - 一个巨大的字符串语料库，当用作用户输入数据时很可能会导致问题. 必须有一组实用的边缘案例来测试您的软件.

## Management

- [Falsehoods about Job Applicants](https://web.archive.org/web/20170114022820/https://medium.com/@creatrixtiara/falsehoods-programmers-believe-about-job-applicants-99280437c616) - 关于求职者及其工作经历的假设不一定正确.

## Multimedia

- [Falsehoods about Video](https://haasn.xyz/posts/2016-12-25-falsehoods-programmers-believe-about-%5Bvideo-stuff%5D.html) - 涵盖所有内容：视频解码和播放、文件、图像缩放、色彩空间和转换、显示和字幕.
- [Horrible edge cases to consider when dealing with music](https://dustri.org/b/horrible-edge-cases-to-consider-when-dealing-with-music.html) - 音乐目录数据充满了疯狂的东西.
- [MusicBrainz database schema](https://musicbrainz.org/doc/MusicBrainz_Database/Schema) - 一个开源项目和数据库，似乎解决了音乐目录管理的复杂性.
- [DDEX](https://ddex.net/standards/) - 音乐元数据的行业标准，包括存档、录音、销售和使用报告、版税和许可交易.
- [Apple Music Style Guide](https://help.apple.com/itc/musicstyleguide/en.lproj/static.html) - 格式化音乐、艺术和元数据以提高可发现性的质量保险指南.

## Networks

- [Falsehoods about Networks](http://blog.erratasec.com/2012/06/falsehoods-programmers-believe-about.html) - 涵盖 TCP、DHCP、DNS、VLAN 和 IPv4/v6.
- [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing) - 不熟悉分布式应用程序的程序员总是会做出假设.
- [There's more than one way to write an IP address](https://ma.ttias.be/theres-more-than-one-way-to-write-an-ip-address/) - 地址的某些部分是可选的，请注意十进制和八进制符号，以及 [don't forget IPv6](https://news.ycombinator.com/item?id=20390981) 任何一个.
- [URLs: It's complicated…](https://www.netmeister.org/blog/urls.html) - URL 中有很多组件，并且都有自己的逻辑.
- [`hostname-validate`](https://github.com/jakeogh/hostname-validate) - 尝试在 Python 中验证主机名.

## Phone Numbers

- [Falsehoods about Phone Numbers](https://github.com/googlei18n/libphonenumber/blob/master/FALSEHOODS.md) - 涵盖电话号码、它们的表示和含义.
- [`libphonenumber`](https://github.com/googlei18n/libphonenumber)  - Google 的通用 Java、C++ 和 JavaScript 库，用于解析、格式化和验证国际电话号码. 也可用于 [C#](https://github.com/twcclegg/libphonenumber-csharp), [Objective-C](https://github.com/iziz/libPhoneNumber-iOS), [Python](https://github.com/daviddrysdale/python-phonenumbers), [Ruby](https://github.com/sstephenson/global_phone) 和 [PHP](https://github.com/giggsey/libphonenumber-for-php).

## Postal Addresses

- [Falsehoods about Addresses](https://www.mjt.me.uk/posts/falsehoods-programmers-believe-about-addresses/) - 涵盖街道、邮政编码、建筑物、城市和国家.
- [Falsehoods about Residence](https://twitter.com/samphippen/status/813896916534784004) - 这不仅仅是地址本身，而是一个人与其住所之间的关系.
- [Letter Delivered Despite No Name, No Address](https://twitter.com/loriskumo/status/735851511331356672) - 关于邮政地址的终极谎言：你不需要一个.
- [The Bear with Its Own ZIP Code](https://kottke.org/19/08/the-bear-with-its-own-zip-code) - Smokey Bear 有自己的邮政编码（`20252`），因为他收到了很多邮件.
- [Regex and Postal Addresses](https://smartystreets.com/articles/regular-expressions-for-street-addresses) - 为什么正则表达式和街道地址不混合.
- [Parsing the Infamous Japanese Postal CSV](https://www.dampfkraft.com/posuto.html) - “我看到了很多恐怖，但我从未在其他任何地方看到过这种特殊的格式选择.”
- [`libaddressinput`](https://github.com/googlei18n/libaddressinput) - Google 用于解析、格式化和验证国际邮政地址的通用 C++ 和 Java 库.
- [`addressing`](https://github.com/commerceguys/addressing) - 由 Google 数据集提供支持的 PHP 5.4+ 寻址库.
- [`postal-address`](https://github.com/scaleway/postal-address) - 用于解析、规范化和呈现邮政地址的 Python 模块.
- [`address`](https://github.com/Boostport/address) - 使用 Google 的数据集去图书馆验证和格式化地址.

## Science

- [Falsehoods about Systems of Measurement](https://www.stevemoser.org/posts/dev/falsehoods-programmers-believe-about-systems-of-measurement.html) - 使用测量系统并在它们之间进行转换.

## Society

- [Falsehoods about Political Appointments](https://twitter.com/oliver_dw/status/737930439575404544) - 设计选举系统有它自己的技巧.
- [Falsehoods about Women In Tech](https://gist.github.com/Su-Shee/5d1a417fa9de19c15477) - 关于 STEM（科学、技术、工程、数学）行业中女性的神话.

## Software Engineering

- [Falsehoods about Versions](https://github.com/xenoterracide/falsehoods/blob/master/versions.md) - 将身份归因于软件版本可能比想象的要难.
- [Falsehoods about Build Systems](https://pozorvlak.livejournal.com/174763.html)  - 构建软件很难. 构建能够构建软件的软件更难.
- [Falsehoods about REST APIs](https://web.archive.org/web/20201112010147/http://slinkp.com/falsehoods-programmers-believe-about-apis.html) - 创建和记录 API 时要注意的陷阱.
- [Falsehoods about CSVs](https://donatstudios.com/Falsehoods-Programmers-Believe-About-CSVs) - 虽然 RFC4180 存在，但它远非确定性，并且在很大程度上被忽略了.
- [Falsehoods about Package Managers](https://kdeldycke.github.io/meta-package-manager/falsehoods.html) - 涵盖包及其经理.
- [Falsehoods about Testing](https://club.ministryoftesting.com/t/falsehoods-testers-believe/1371) - 试图建立一份关于测试的谎言清单.
- [Falsehoods about Search](https://opensourceconnections.com/blog/2019/05/29/falsehoods-programmers-believe-about-search/) - 为什么搜索（包括分析、标记化、突出显示）看似复杂.
- [What every software engineer should know about search](https://scribe.rip/p/what-every-software-engineer-should-know-about-search-27d1df99f80d) - 关于实施搜索引擎的难度的更好来源的文章.
- [Falsehoods about Bitcoin](https://github.com/theborakompanioni/spring-boot-bitcoin-starter/blob/master/docs/FALSEHOODS.md) - 关于比特币的错误观点列表.
- [Falsehoods about Pagination](https://www.hezmatt.org/~mpalmer/blog/2018/12/12/falsehoods-programmers-believe-about-pagination.html) - 为什么你的分页算法让某人（可能是你）头疼.
- [Falsehoods about garbage collection](https://paul.bone.id.au/blog/2018/10/19/gc-falsehoods/) - 关于垃圾收集的可预测性和性能的误解.
- [Myths about File Paths](https://yakking.branchable.com/posts/falsehoods-programmers-believe-about-file-paths/) - 文件系统和操作系统的多样性使文件路径比我们想象的要难一些.
- [Myths about CPU Caches](https://software.rajivprab.com/2018/04/29/myths-programmers-believe-about-cpu-caches/) - 对缓存的误解通常会导致错误的断言，尤其是在并发和竞争条件方面.
- [Myths about `/dev/urandom`](https://www.2uo.de/myths-about-urandom)  - 关于 `/dev/urandom` 和 `/dev/random` 有一些事情会一次又一次地重复. 他们仍然是错误的.
- [Hi! My name is…](https://www.youtube.com/watch?v=NIebelIpdYk) - 这个谈话可以被命名为“关于用户名（和其他标识符）的谎言”.
- [Popular misconceptions about `mtime`](https://apenwarr.ca/log/20181113) - 关于为什么文件的 `mtime` 比较可能被认为是有害的帖子的一部分.
- [Rules for Autocomplete](http://jeremymikkola.com/posts/2019_03_19_rules_for_autocomplete.html) - 不是谎言*本身*，但仍然是实现自动完成的良好实践的一个很好的列表.
- [Floating Point Math](https://0.30000000000000004.com) - “你的语言没有坏，它在做浮点数学运算.（……）这就是为什么，&#39;0.1 + 0.2 != 0.3&#39;.”
- [The Hidden Complexity of Downloading Favicons, Told in 15+ Edge Cases](https://www.simplecto.com/complexity-downloading-favicons-told-in-15-plus-edge-cases/)  - 下载您在浏览器选项卡中看到的那个小图标应该是一个简单的练习. 结果比你想象的要复杂得多. 小心你没有给牦牛剃毛.
- [Norway is not False](https://mobile.twitter.com/chrisjrn/status/1232016100038266880) - 挪威的 ISO 国家代码对于 False 也是有效的 YAML.

## Typography

- [Falsehoods about Fonts](https://github.com/RoelN/Font-Falsehoods) - 关于网络和桌面应用程序中的排版的假设.
- [Truths programmers should know about case](https://www.b-list.org/weblog/2018/nov/26/case/) - 关于大小写主题的虚假格式的完全反转（如大写和小写文本）.

## Video Games

- [The Door Problem](https://lizengland.com/blog/2014/04/the-door-problem/) - 所有你没有考虑在游戏中为你的门实施的事情.

## Contributing

随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/kdeldycke/awesome-falsehood/blob/main/.github/contributing.md) 第一的.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-falsehood/blob/main/assets/awesome-falsehood-header.jpg) 是基于修改 [photo taken in February 2010 by Iza Bella](https://commons.wikimedia.org/wiki/File:BLW_Truth_and_Falsehood.jpg), 分布在 [Creative Commons BY-SA 2.0 UK license](https://creativecommons.org/licenses/by-sa/2.0/uk/deed.en).

<!--lint disable no-undefined-references-->

<a name="intro-quote-def">\[1\]</a>: [*Notebooks, 1914-1916*, page 14e](https://archive.org/details/notebooks191419100witt/page/n35) (Harper & Brothers, New York, 1961). [\[↑\]](#intro-quote-ref)
