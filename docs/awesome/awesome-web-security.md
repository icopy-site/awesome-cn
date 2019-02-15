## Awesome Web Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" align="right" width="70">](https://www.w3.org/TR/html5/)

&gt;策划的Web安全材料和资源列表.

 毋庸置疑，大多数网站都存在各种类型的错误，最终可能导致漏洞.  为什么这会经常发生？  可能涉及许多因素，包括配置错误，工程师的安全技能不足等.为了解决这个问题，这里列出了用于学习尖端渗透技术的Web安全材料和资源，我强烈建议您阅读本文“[So you want to be a web security researcher?](https://portswigger.net/blog/so-you-want-to-be-a-web-security-researcher)“先.

*请阅读 [contribution guidelines](https://github.com/qazbnm456/awesome-web-security/blob/master/CONTRIBUTING.md) 在贡献之前.*

---

<p align="center"><b>🌈 Want to strengthen your penetration skills?</b><br>I would recommend playing some <a href="https://github.com/apsdehal/awesome-ctf" target="_blank">awesome-ctf</a>s.</p>

---

如果您喜欢这个很棒的列表并想支持它，请查看我 [Patreon](https://www.patreon.com/boik)  页面:) <br>  另外，别忘了看看我 [repos](https://github.com/qazbnm456)  或者说我喜欢* hi * [Twitter](https://twitter.com/qazbnm456)!

## Contents

- [Forums](#forums)
- [Resources](#resources)
  - [Tips](#tips)
  - [XSS](#xss---cross-site-scripting)
  - [CSV Injection](#csv-injection)
  - [SQL Injection](#sql-injection)
  - [Command Injection](#command-injection)
  - [ORM Injection](#orm-injection)
  - [FTP Injection](#ftp-injection)
  - [XXE](#xxe---xml-external-entity)
  - [CSRF](#csrf---cross-site-request-forgery)
  - [SSRF](#ssrf---server-side-request-forgery)
  - [Web Cache Poisoning](#web-cache-poisoning)
  - [Open Redirect](#open-redirect)
  - [Upload](#upload)
  - [Rails](#rails)
  - [AngularJS](#angularjs)
  - [ReactJS](#reactjs)
  - [SSL/TLS](#ssltls)
  - [Webmail](#webmail)
  - [NFS](#nfs)
  - [AWS](#aws)
  - [Fingerprint](#fingerprint)
  - [Sub Domain Enumeration](#sub-domain-enumeration)
  - [Crypto](#crypto)
  - [Web Shell](#web-shell)
  - [OSINT](#osint)
  - [Books](#books)
- [Evasions](#evasions)
  - [CSP](#evasions-csp)
  - [WAF](#evasions-waf)
  - [JSMVC](#evasions-jsmvc)
  - [Authentication](#evasions-authentication)
- [Tricks](#tricks)
  - [CSRF](#tricks-csrf)
  - [Remote Code Execution](#tricks-rce)
  - [XSS](#tricks-xss)
  - [SQL Injection](#tricks-sql-injection)
  - [NoSQL Injection](#tricks-nosql-injection)
  - [FTP Injection](#tricks-ftp-injection)
  - [XXE](#tricks-xxe)
  - [SSRF](#tricks-ssrf)
  - [Web Cache Poisoning](#tricks-web-cache-poisoning)
  - [Header Injection](#tricks-header-injection)
  - [URL](#tricks-url)
  - [Others](#tricks-others)
- [Browser Exploitation](#browser-exploitation)
- [PoCs](#pocs)
  - [Database](#pocs-database)
- [Tools](#tools)
  - [Auditing](#tools-auditing)
  - [Command Injection](#tools-command-injection)
  - [Reconnaissance](#tools-reconnaissance)
    - [OSINT](#tools-osint)
    - [Sub Domain Enumeration](#tools-sub-domain-enumeration)
  - [Code Generating](#tools-code-generating)
  - [Fuzzing](#tools-fuzzing)
  - [Scanning](#tools-scanning)
  - [Penetration Testing](#tools-penetration-testing)
  - [Leaking](#tools-leaking)
  - [Offensive](#tools-offensive)
    - [XSS](#tools-xss)
    - [SQL Injection](#tools-sql-injection)
    - [Template Injection](#tools-template-injection)
    - [Cross Site Request Forgery](#tools-csrf)
  - [Detecting](#tools-detecting)
  - [Preventing](#tools-preventing)
  - [Proxy](#tools-proxy)
  - [Webshell](#tools-webshell)
  - [Disassembler](#tools-disassembler)
  - [Decompiler](#tools-decompiler)
  - [Others](#tools-others)
- [Social Engineering Database](#social-engineering-database)
- [Blogs](#blogs)
- [Twitter Users](#twitter-users)
- [Practices](#practices)
  - [Application](#practices-application)
  - [AWS](#practices-aws)
  - [XSS](#practices-xss)
  - [ModSecurity / OWASP ModSecurity Core Rule Set](#practices-modsecurity)
- [Community](#community)
- [Miscellaneous](#miscellaneous)

## Forums

- [Phrack Magazine](http://www.phrack.org/) - 由黑客和黑客写的电子杂志.
- [The Hacker News](https://thehackernews.com/) - 严肃的安全.
- [Security Weekly](https://securityweekly.com/) - 安全播客网络.
- [The Register](http://www.theregister.co.uk/) - 咬住提供IT的手.
- [Dark Reading](https://www.darkreading.com/Default.asp) - 连接信息安全社区.
- [HackDig](http://en.hackdig.com/) - 为黑客挖掘高质量的网络安全文章.

## Resources

<a name="tips"></a>
### Tips

- [Hacker101](https://www.hacker101.com/) - 写 [hackerone](https://www.hackerone.com/start-hacking).
- [The Daily Swig - Web security digest](https://portswigger.net/daily-swig) - 写 [PortSwigger](https://portswigger.net/).
- [Web Application Security Zone by Netsparker](https://www.netsparker.com/blog/web-security/) - 写 [Netsparker](https://www.netsparker.com/).
- [Infosec Newbie](https://www.sneakymonkey.net/2017/04/23/infosec-newbie/) - 写 [Mark Robinson](https://www.sneakymonkey.net/).
- [The Magic of Learning](https://bitvijays.github.io/) - 写 [@bitvijays](https://bitvijays.github.io/aboutme.html).
- [CTF Field Guide](https://trailofbits.github.io/ctf/) - 写 [Trail of Bits](https://www.trailofbits.com/).

<a name="xss"></a>
### XSS - Cross-Site Scripting

- [Cross-Site Scripting – Application Security – Google](https://www.google.com/intl/sw/about/appsecurity/learning/xss/) - 写 [Google](https://www.google.com/).
- [H5SC](https://github.com/cure53/H5SC) - 写 [@cure53](https://github.com/cure53).
- [AwesomeXSS](https://github.com/s0md3v/AwesomeXSS) - 写 [@s0md3v](https://github.com/s0md3v).
- [XSS.png](https://github.com/LucaBongiorni/XSS.png) - 由@jackmasa撰写.
- [C.XSS Guide](https://excess-xss.com/) - 写 [@JakobKallin](https://github.com/JakobKallin) 和 [Irene Lobo Valbuena](https://www.linkedin.com/in/irenelobovalbuena/).
- [THE BIG BAD WOLF - XSS AND MAINTAINING ACCESS](http://www.paulosyibelo.com/2018/06/the-big-bad-wolf-xss-and-maintaining.html) - 写 [Paulos Yibelo](http://www.paulosyibelo.com/).

<a name="csv-injection"></a>
### CSV Injection

- [CSV Injection -> Meterpreter on Pornhub](https://news.webamooz.com/wp-content/uploads/bot/offsecmag/147.pdf) - 写 [Andy](https://blog.zsec.uk/).
- [The Absurdly Underestimated Dangers of CSV Injection](http://georgemauer.net/2017/10/07/csv-injection.html) - 写 [George Mauer](http://georgemauer.net/).

<a name="sql-injection"></a>
### SQL Injection

- [SQL Injection Cheat Sheet](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/) - 写 [@netsparker](https://twitter.com/netsparker).
- [SQL Injection Wiki](https://sqlwiki.netspi.com/) - 写 [NETSPI](https://www.netspi.com/).
- [SQL Injection Pocket Reference](https://websec.ca/kb/sql_injection) - 写 [@LightOS](https://twitter.com/LightOS).

<a name="command-injection"></a>
### Command Injection

- [Potential command injection in resolv.rb](https://github.com/ruby/ruby/pull/1777) - 写 [@drigg3r](https://github.com/drigg3r).

<a name="orm-injection"></a>
### ORM Injection

- [HQL for pentesters](http://blog.h3xstream.com/2014/02/hql-for-pentesters.html) - 写 [@h3xstream](https://twitter.com/h3xstream/).
- [HQL : Hyperinsane Query Language (or how to access the whole SQL API within a HQL injection ?)](https://www.synacktiv.com/ressources/hql2sql_sstic_2015_en.pdf) - 写 [@_m0bius](https://twitter.com/_m0bius).
- [ORM2Pwn: Exploiting injections in Hibernate ORM](https://www.slideshare.net/0ang3el/orm2pwn-exploiting-injections-in-hibernate-orm) - 写 [Mikhail Egorov](https://0ang3el.blogspot.tw/).
- [ORM Injection](https://www.slideshare.net/simone.onofri/orm-injection) - 写 [Simone Onofri](https://onofri.org/).

<a name="ftp-injection"></a>
### FTP Injection

- [Advisory: Java/Python FTP Injections Allow for Firewall Bypass](http://blog.blindspotsecurity.com/2017/02/advisory-javapython-ftp-injections.html) - 写 [Timothy Morgan](https://plus.google.com/105917618099766831589).
- [SMTP over XXE − how to send emails using Java's XML parser](https://shiftordie.de/blog/2017/02/18/smtp-over-xxe/) - 写 [Alexander Klink](https://shiftordie.de/).

<a name="xxe"></a>
### XXE - XML eXternal Entity

- [XXE](https://phonexicum.github.io/infosec/xxe.html) - 写 [@phonexicum](https://twitter.com/phonexicum).
- [XXE OOB extracting via HTTP+FTP using single opened port](https://skavans.ru/en/2017/12/02/xxe-oob-extracting-via-httpftp-using-single-opened-port/) - 写 [skavans](https://skavans.ru/).

<a name="csrf"></a>
### CSRF - Cross-Site Request Forgery

- [Wiping Out CSRF](https://medium.com/@jrozner/wiping-out-csrf-ded97ae7e83f) - 写 [@jrozner](https://medium.com/@jrozner).

<a name="ssrf"></a>
### SSRF - Server-Side Request Forgery

- [SSRF bible. Cheatsheet](https://docs.google.com/document/d/1v1TkWZtrhzRLy0bYXBcdLUedXGb9njTNIJXa3u9akHM/edit) - 写 [Wallarm](https://wallarm.com/).

<a name="web-cache-poisoning"></a>
### Web Cache Poisoning

- [Practical Web Cache Poisoning](https://portswigger.net/blog/practical-web-cache-poisoning) - 写 [@albinowax](https://twitter.com/albinowax).

<a name="open-redirect"></a>
### Open Redirect

- [Open Redirect Vulnerability](https://s0cket7.com/open-redirect-vulnerability/) - 写 [s0cket7](https://s0cket7.com/).

<a name="upload"></a>
### Upload

- [File Upload Restrictions Bypass](https://www.exploit-db.com/docs/english/45074-file-upload-restrictions-bypass.pdf) - 写 [Haboob Team](https://www.exploit-db.com/author/?a=9381).

<a name="rails"></a>
### Rails

- [Rails Security - First part](https://hackmd.io/s/SkuTVw5O-) - 写 [@qazbnm456](https://github.com/qazbnm456).

<a name="angularjs"></a>
### AngularJS

- [XSS without HTML: Client-Side Template Injection with AngularJS](http://blog.portswigger.net/2016/01/xss-without-html-client-side-template.html) - 写 [Gareth Heyes](https://www.blogger.com/profile/10856178524811553475).
- [DOM based Angular sandbox escapes](http://blog.portswigger.net/2017/05/dom-based-angularjs-sandbox-escapes.html) - 写 [@garethheyes](https://twitter.com/garethheyes)

<a name="reactjs"></a>
### ReactJS

- [XSS via a spoofed React element](http://danlec.com/blog/xss-via-a-spoofed-react-element) - 写 [Daniel LeCheminant](http://danlec.com/).

<a name="ssl-tls"></a>
### SSL/TLS

- [SSL & TLS Penetration Testing](https://www.aptive.co.uk/blog/tls-ssl-security-testing/) - 写 [APTIVE](https://www.aptive.co.uk/).

<a name="webmail"></a>
### Webmail

- [Why mail() is dangerous in PHP](https://blog.ripstech.com/2017/why-mail-is-dangerous-in-php/) - 写 [Robin Peraglie](https://www.ripstech.com/).

<a name="nfs"></a>
### NFS

- [NFS | PENETRATION TESTING ACADEMY](https://pentestacademy.wordpress.com/2017/09/20/nfs/?t=1&cn=ZmxleGlibGVfcmVjc18y&refsrc=email&iid=b34422ce15164e99a193fea0ccc7a02f&uid=1959680352&nid=244+289476616) - 写 [PENETRATION ACADEMY](https://pentestacademy.wordpress.com/).

<a name="aws"></a>
### AWS

- [PENETRATION TESTING AWS STORAGE: KICKING THE S3 BUCKET](https://rhinosecuritylabs.com/penetration-testing/penetration-testing-aws-storage/) - 由德怀特霍恩斯坦撰写 [Rhino Security Labs](https://rhinosecuritylabs.com/).
- [AWS PENETRATION TESTING PART 1. S3 BUCKETS](https://www.virtuesecurity.com/aws-penetration-testing-part-1-s3-buckets/) - 写 [VirtueSecurity](https://www.virtuesecurity.com/).
- [AWS PENETRATION TESTING PART 2. S3, IAM, EC2](https://www.virtuesecurity.com/aws-penetration-testing-part-2-s3-iam-ec2/) - 写 [VirtueSecurity](https://www.virtuesecurity.com/).

<a name="fingerprint"></a>
### Fingerprint

<a name="sub-domain-enumeration"></a>
### Sub Domain Enumeration

- [A penetration tester’s guide to sub-domain enumeration](https://blog.appsecco.com/a-penetration-testers-guide-to-sub-domain-enumeration-7d842d5570f6) - 写 [Bharath](https://blog.appsecco.com/@yamakira_).
- [The Art of Subdomain Enumeration](https://blog.sweepatic.com/art-of-subdomain-enumeration/) - 写 [Patrik Hudak](https://blog.sweepatic.com/author/patrik/).

<a name="crypto"></a>
### Crypto

- [Applied Crypto Hardening](https://bettercrypto.org/static/applied-crypto-hardening.pdf) - 写 [The bettercrypto.org Team](https://bettercrypto.org/).

<a name="web-shell"></a>
### Web Shell

- [Hunting for Web Shells](https://www.tenable.com/blog/hunting-for-web-shells) - 写 [Jacob Baines](https://www.tenable.com/profile/jacob-baines).
- [Hacking with JSP Shells](https://blog.netspi.com/hacking-with-jsp-shells/) - 写 [@_nullbind](https://twitter.com/_nullbind).

<a name="osint"></a>
### OSINT

- [Hacking Cryptocurrency Miners with OSINT Techniques](https://medium.com/@s3yfullah/hacking-cryptocurrency-miners-with-osint-techniques-677bbb3e0157) - 写 [@s3yfullah](https://medium.com/@s3yfullah).
- [OSINT x UCCU Workshop on Open Source Intelligence](https://www.slideshare.net/miaoski/osint-x-uccu-workshop-on-open-source-intelligence) - 写 [Philippe Lin](https://www.slideshare.net/miaoski).
- [102 Deep Dive in the Dark Web OSINT Style Kirby Plessas](https://www.youtube.com/watch?v=fzd3zkAI_o4) - 提出者 [@kirbstr](https://twitter.com/kirbstr).
- [The most complete guide to finding anyone’s email](https://www.blurbiz.io/blog/the-most-complete-guide-to-finding-anyones-email) - 写 [Timur Daudpota](https://www.blurbiz.io/).

### Books

- [XSS Cheat Sheet - 2018 Edition](https://leanpub.com/xss) - 写 [@brutelogic](https://twitter.com/brutelogic).

## Evasions

<a name="evasions-csp"></a>
### CSP

- [CSP: bypassing form-action with reflected XSS](https://labs.detectify.com/2016/04/04/csp-bypassing-form-action-with-reflected-xss/) - 写 [Detectify Labs](https://labs.detectify.com/).
- [TWITTER XSS + CSP BYPASS](http://www.paulosyibelo.com/2017/05/twitter-xss-csp-bypass.html) - 写 [Paulos Yibelo](http://www.paulosyibelo.com/).
- [Neatly bypassing CSP](https://lab.wallarm.com/how-to-trick-csp-in-letting-you-run-whatever-you-want-73cb5ff428aa) - 写 [Wallarm](https://wallarm.com/).
- [Evading CSP with DOM-based dangling markup](https://portswigger.net/blog/evading-csp-with-dom-based-dangling-markup) - 写 [portswigger](https://portswigger.net/).
- [GitHub's CSP journey](https://githubengineering.com/githubs-csp-journey/) - 写 [@ptoomey3](https://github.com/ptoomey3).
- [GitHub's post-CSP journey](https://githubengineering.com/githubs-post-csp-journey/) - 写 [@ptoomey3](https://github.com/ptoomey3).

<a name="evasions-waf"></a>
### WAF

- [Web Application Firewall (WAF) Evasion Techniques](https://medium.com/secjuice/waf-evasion-techniques-718026d693d8) - 写 [@secjuice](https://twitter.com/secjuice).
- [Web Application Firewall (WAF) Evasion Techniques #2](https://medium.com/secjuice/web-application-firewall-waf-evasion-techniques-2-125995f3e7b0) - 写 [@secjuice](https://twitter.com/secjuice).
- [Airbnb – When Bypassing JSON Encoding, XSS Filter, WAF, CSP, and Auditor turns into Eight Vulnerabilities](https://buer.haus/2017/03/08/airbnb-when-bypassing-json-encoding-xss-filter-waf-csp-and-auditor-turns-into-eight-vulnerabilities/) - 写 [@Brett Buerhaus](https://twitter.com/bbuerhaus).
- [How to bypass libinjection in many WAF/NGWAF](https://medium.com/@d0znpp/how-to-bypass-libinjection-in-many-waf-ngwaf-1e2513453c0f) - 写 [@d0znpp](https://medium.com/@d0znpp).

<a name="evasions-jsmvc"></a>
### JSMVC

- [JavaScript MVC and Templating Frameworks](http://www.slideshare.net/x00mario/jsmvcomfg-to-sternly-look-at-javascript-mvc-and-templating-frameworks) - 写 [Mario Heiderich](http://www.slideshare.net/x00mario).

<a name="evasions-authentication"></a>
### Authentication

- [Trend Micro Threat Discovery Appliance - Session Generation Authentication Bypass (CVE-2016-8584)](http://blog.malerisch.net/2017/04/trend-micro-threat-discovery-appliance-session-generation-authentication-bypass-cve-2016-8584.html) - 写 [@malerisch](https://twitter.com/malerisch) 和 [@steventseeley](https://twitter.com/steventseeley).

## Tricks

<a name="tricks-csrf"></a>
### CSRF

- [Neat tricks to bypass CSRF-protection](https://zhuanlan.zhihu.com/p/32716181) - 写 [Twosecurity](https://twosecurity.io/).
- [Exploiting CSRF on JSON endpoints with Flash and redirects](https://blog.appsecco.com/exploiting-csrf-on-json-endpoints-with-flash-and-redirects-681d4ad6b31b) - 写 [@riyazwalikar](https://blog.appsecco.com/@riyazwalikar).
- [Stealing CSRF tokens with CSS injection (without iFrames)](https://github.com/dxa4481/cssInjection) - 写 [@dxa4481](https://github.com/dxa4481).

<a name="tricks-rce"></a>
### Remote Code Execution

- [Exploiting Node.js deserialization bug for Remote Code Execution](https://opsecx.com/index.php/2017/02/08/exploiting-node-js-deserialization-bug-for-remote-code-execution/) - 写 [OpSecX](https://opsecx.com/index.php/author/ajinabraham/).
- [DRUPAL 7.X SERVICES MODULE UNSERIALIZE() TO RCE](https://www.ambionics.io/blog/drupal-services-module-rce) - 写 [Ambionics Security](https://www.ambionics.io/).
- [How we exploited a remote code execution vulnerability in math.js](https://capacitorset.github.io/mathjs/) - 写 [@capacitorset](https://github.com/capacitorset).
- [GitHub Enterprise Remote Code Execution](http://exablue.de/blog/2017-03-15-github-enterprise-remote-code-execution.html) - 写 [@iblue](https://github.com/iblue).
- [Evil Teacher: Code Injection in Moodle](https://blog.ripstech.com/2018/moodle-remote-code-execution/) - 写 [RIPS Technologies](https://www.ripstech.com/).
- [How I Chained 4 vulnerabilities on GitHub Enterprise, From SSRF Execution Chain to RCE!](http://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html) - 写 [Orange](http://blog.orange.tw/).
- [$36k Google App Engine RCE](https://sites.google.com/site/testsitehacking/-36k-google-app-engine-rce) - 写 [Ezequiel Pereira](https://sites.google.com/site/testsitehacking/).
- [Poor RichFaces](https://codewhitesec.blogspot.com/2018/05/poor-richfaces.html) - 写 [CODE WHITE](https://www.code-white.com/).
- [Remote Code Execution on a Facebook server](https://blog.scrt.ch/2018/08/24/remote-code-execution-on-a-facebook-server/) - 写 [@blaklis_](https://twitter.com/blaklis_).

<a name="tricks-xss"></a>
### XSS

- [Query parameter reordering causes redirect page to render unsafe URL](https://hackerone.com/reports/293689) - 写 [kenziy](https://hackerone.com/kenziy).
- [ECMAScript 6 from an Attacker's Perspective - Breaking Frameworks, Sandboxes, and everything else](http://www.slideshare.net/x00mario/es6-en) - 写 [Mario Heiderich](http://www.slideshare.net/x00mario).
- [How I found a $5,000 Google Maps XSS (by fiddling with Protobuf)](https://medium.com/@marin_m/how-i-found-a-5-000-google-maps-xss-by-fiddling-with-protobuf-963ee0d9caff#.u50nrzhas) - 写 [@marin_m](https://medium.com/@marin_m).
- [DON'T TRUST THE DOM: BYPASSING XSS MITIGATIONS VIA SCRIPT GADGETS](https://www.blackhat.com/docs/us-17/thursday/us-17-Lekies-Dont-Trust-The-DOM-Bypassing-XSS-Mitigations-Via-Script-Gadgets.pdf) - 写 [Sebastian Lekies](https://twitter.com/slekies), [Krzysztof Kotowicz](https://twitter.com/kkotowicz)，和 [Eduardo Vela](https://twitter.com/sirdarckcat).
- [Uber XSS via Cookie](http://zhchbin.github.io/2017/08/30/Uber-XSS-via-Cookie/) - 写 [zhchbin](http://zhchbin.github.io/).
- [DOM XSS – auth.uber.com](http://stamone-bug-bounty.blogspot.tw/2017/10/dom-xss-auth14.html) - 写 [StamOne_](http://stamone-bug-bounty.blogspot.tw/).
- [Stored XSS on Facebook](https://opnsec.com/2018/03/stored-xss-on-facebook/) - 写 [Enguerran Gillier](https://opnsec.com/).
- [XSS in Google Colaboratory + CSP bypass](https://blog.bentkowski.info/2018/06/xss-in-google-colaboratory-csp-bypass.html) - 写 [Michał Bentkowski](https://blog.bentkowski.info/).
- [Another XSS in Google Colaboratory](https://blog.bentkowski.info/2018/09/another-xss-in-google-colaboratory.html) - 写 [Michał Bentkowski](https://blog.bentkowski.info/).
- [</script> is filtered ?](https://twitter.com/strukt93/status/931586377665331200) - 写 [@strukt93](https://twitter.com/strukt93).

<a name="tricks-sql-injection"></a>
### SQL Injection

- [MySQL Error Based SQL  Injection Using  EXP](https://www.exploit-db.com/docs/english/37953-mysql-error-based-sql-injection-using-exp.pdf) - 写 [@osandamalith](https://twitter.com/osandamalith).
- [SQL injection in an UPDATE query - a bug bounty story!](http://zombiehelp54.blogspot.jp/2017/02/sql-injection-in-update-query-bug.html) - 写 [Zombiehelp54](http://zombiehelp54.blogspot.jp/).
- [GitHub Enterprise SQL Injection](http://blog.orange.tw/2017/01/bug-bounty-github-enterprise-sql-injection.html) - 写 [Orange](http://blog.orange.tw/).
- [Making a Blind SQL Injection a little less blind](https://medium.com/@tomnomnom/making-a-blind-sql-injection-a-little-less-blind-428dcb614ba8) - 写 [TomNomNom](https://twitter.com/TomNomNom).

<a name="tricks-nosql-injection"></a>
### NoSQL Injection

- [GraphQL NoSQL Injection Through JSON Types](https://medium.com/@east5th/graphql-nosql-injection-through-json-types-a1a0a310c759) - 写 [@east5th](https://medium.com/@east5th).

<a name="tricks-ftp-injection"></a>
### FTP Injection

- [XML Out-Of-Band Data Retrieval](https://media.blackhat.com/eu-13/briefings/Osipov/bh-eu-13-XML-data-osipov-slides.pdf) - 写 [@a66at](https://twitter.com/a66at) 和Alexey Osipov.
- [XXE OOB exploitation at Java 1.7+](http://lab.onsec.ru/2014/06/xxe-oob-exploitation-at-java-17.html) - 写 [Ivan Novikov](http://lab.onsec.ru/).

<a name="tricks-xxe"></a>
### XXE

- [Evil XML with two encodings](https://mohemiv.com/all/evil-xml/) - 写 [Arseniy Sharoglazov](https://mohemiv.com/).
- [XXE in WeChat Pay Sdk ( WeChat leave a backdoor on merchant websites)](http://seclists.org/fulldisclosure/2018/Jul/3) - 写 [Rose Jackcode](https://github.com/qazbnm456/awesome-web-security/blob/master/1024rosecode at gamil dot com).

<a name="tricks-ssrf"></a>
### SSRF

- [AWS takeover through SSRF in JavaScript](http://10degres.net/aws-takeover-ssrf-javascript/) - 写 [Gwen](http://10degres.net/).
- [SSRF in Exchange leads to ROOT access in all instances](https://hackerone.com/reports/341876) - 写 [@0xacb](https://twitter.com/0xacb).
- [SSRF to ROOT Access](https://hackerone.com/reports/341876) - 在所有情况下，SSRF获得25,000美元的奖励，导致ROOT访问 [0xacb](https://hackerone.com/0xacb).
- [PHP SSRF Techniques](https://medium.com/secjuice/php-ssrf-techniques-9d422cb28d51) - 写 [@themiddleblue](https://medium.com/@themiddleblue).
- [SSRF in https://imgur.com/vidgif/url](https://hackerone.com/reports/115748) - 写 [aesteral](https://hackerone.com/aesteral).
- [All you need to know about SSRF and how may we write tools to do auto-detect](https://www.auxy.xyz/research/all-ssrf-knowledge/) - 写 [@realAuxy233](https://twitter.com/realAuxy233).
- [A New Era of SSRF - Exploiting URL Parser in Trending Programming Languages!](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf) - 写 [Orange](http://blog.orange.tw/).
- [SSRF Tips](http://blog.safebuff.com/2016/07/03/SSRF-Tips/) - 写 [xl7dev](http://blog.safebuff.com/).
- [Into the Borg – SSRF inside Google production network](https://opnsec.com/2018/07/into-the-borg-ssrf-inside-google-production-network/) - 写 [opnsec](https://opnsec.com/).
- [Piercing the Veil: Server Side Request Forgery to NIPRNet access](https://medium.com/bugbountywriteup/piercing-the-veil-server-side-request-forgery-to-niprnet-access-c358fd5e249a) - 写 [Alyssa Herrera](https://medium.com/@alyssa.o.herrera).

<a name="tricks-web-cache-poisoning"></a>
### Web Cache Poisoning

- [Bypassing Web Cache Poisoning Countermeasures](https://portswigger.net/blog/bypassing-web-cache-poisoning-countermeasures) - 写 [@albinowax](https://twitter.com/albinowax).
- [Cache poisoning and other dirty tricks](https://lab.wallarm.com/cache-poisoning-and-other-dirty-tricks-120468f1053f) - 写 [Wallarm](https://wallarm.com/).

<a name="tricks-header-injection"></a>
### Header Injection

- [Java/Python FTP Injections Allow for Firewall Bypass](http://blog.blindspotsecurity.com/2017/02/advisory-javapython-ftp-injections.html) - 写 [Timothy Morgan](https://plus.google.com/105917618099766831589).

<a name="tricks-url"></a>
### URL

- [Some Problems Of URLs](https://noncombatant.org/2017/11/07/problems-of-urls/) - 写 [Chris Palmer](https://noncombatant.org/about/).
- [Phishing with Unicode Domains](https://www.xudongz.com/blog/2017/idn-phishing/) - 写 [Xudong Zheng](https://www.xudongz.com/).
- [Unicode Domains are bad and you should feel bad for supporting them](https://www.vgrsec.com/post20170219.html) - 写 [VRGSEC](https://www.vgrsec.com/).
-  [[dev.twitter.com] XSS]（http://blog.blackfan.ru/2017/09/devtwittercom-xss.html） - 撰写者： [Sergey Bobrov](http://blog.blackfan.ru/).

<a name="tricks-others"></a>
### Others

- [How I hacked Google’s bug tracking system itself for $15,600 in bounties](https://medium.freecodecamp.org/messing-with-the-google-buganizer-system-for-15-600-in-bounties-58f86cc9f9a5) - 写 [@alex.birsan](https://medium.freecodecamp.org/@alex.birsan).
- [Some Tricks From My Secret Group](https://www.leavesongs.com/SHARE/some-tricks-from-my-secret-group.html) - 写 [PHITHON](https://www.leavesongs.com/).
- [Inducing DNS Leaks in Onion Web Services](https://github.com/epidemics-scepticism/writing/blob/master/onion-dns-leaks.md) - 写 [@epidemics-scepticism](https://github.com/epidemics-scepticism).
- [Stored XSS, and SSRF in Google using the Dataset Publishing Language](https://s1gnalcha0s.github.io/dspl/2018/03/07/Stored-XSS-and-SSRF-Google.html) - 写 [@signalchaos](https://twitter.com/signalchaos).

## Browser Exploitation

### Frontend (like SOP bypass, URL spoofing, and something like that)

- [JSON hijacking for the modern web](http://blog.portswigger.net/2016/11/json-hijacking-for-modern-web.html) - 写 [portswigger](https://portswigger.net/).
- [IE11 Information disclosure - local file detection](https://www.facebook.com/ExploitWareLabs/photos/a.361854183878462.84544.338832389513975/1378579648872572/?type=3&theater) - 由James Lee撰写.
- [SOP bypass / UXSS – Stealing Credentials Pretty Fast (Edge)](https://www.brokenbrowser.com/sop-bypass-uxss-stealing-credentials-pretty-fast/) - 写 [Manuel](https://twitter.com/magicmac2000).
- [Особенности Safari в client-side атаках](https://bo0om.ru/safari-client-side) - 写 [Bo0oM](https://bo0om.ru/author/admin).
- [How do we Stop Spilling the Beans Across Origins?](https://docs.google.com/document/d/1cbL-X0kV_tQ5rL8XJ3lXkV-j0pt_CfTu5ZSzYrncPDc/) - 写 [aaj at google.com](https://github.com/qazbnm456/awesome-web-security/blob/master/aaj@google.com) 和 [mkwst at google.com](https://github.com/qazbnm456/awesome-web-security/blob/master/mkwst@google.com).
- [Setting arbitrary request headers in Chromium via CRLF injection](https://blog.bentkowski.info/2018/06/setting-arbitrary-request-headers-in.html) - 写 [Michał Bentkowski](https://blog.bentkowski.info/).
- [I’m harvesting credit card numbers and passwords from your site. Here’s how.](https://hackernoon.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5) - 写 [David Gilbertson](https://hackernoon.com/@david.gilbertson).

### Backend (core of Browser implementation, and often refers to C or C++ part)

- [Attacking JavaScript Engines - A case study of JavaScriptCore and CVE-2016-4622](http://www.phrack.org/papers/attacking_javascript_engines.html) - 写 [https://github.com/qazbnm456/awesome-web-security/blob/master/phrack@saelo.net](https://github.com/qazbnm456/awesome-web-security/blob/master/phrack@saelo.net).
- [Three roads lead to Rome](http://blogs.360.cn/360safe/2016/11/29/three-roads-lead-to-rome-2/) - 写 [Luke Viruswalker](http://blogs.360.cn/360safe/author/xsecure/).
- [Exploiting a V8 OOB write.](https://halbecaf.com/2017/05/24/exploiting-a-v8-oob-write/) - 写 [@halbecaf](https://twitter.com/halbecaf).
- [FROM CRASH TO EXPLOIT: CVE-2015-6086 – OUT OF BOUND READ/ASLR BYPASS](http://payatu.com/from-crash-to-exploit/) - 写 [payatu](http://payatu.com/).
- [SSD Advisory – Chrome Turbofan Remote Code Execution](https://blogs.securiteam.com/index.php/archives/3379) - 写 [SecuriTeam Secure Disclosure (SSD)](https://blogs.securiteam.com/).
- [Look Mom, I don't use Shellcode - Browser Exploitation Case Study for Internet Explorer 11](https://labs.bluefrostsecurity.de/files/Look_Mom_I_Dont_Use_Shellcode-WP.pdf) - 写 [@moritzj](http://twitter.com/moritzj).
- [PUSHING WEBKIT'S BUTTONS WITH A MOBILE PWN2OWN EXPLOIT](https://www.zerodayinitiative.com/blog/2018/2/12/pushing-webkits-buttons-with-a-mobile-pwn2own-exploit) - 写 [@wanderingglitch](https://twitter.com/wanderingglitch).
- [A Methodical Approach to Browser Exploitation](https://blog.ret2.io/2018/06/05/pwn2own-2018-exploit-development/) - 写 [RET2 SYSTEMS, INC](https://blog.ret2.io/).
- [CVE-2017-2446 or JSC::JSGlobalObject::isHavingABadTime.](https://doar-e.github.io/blog/2018/07/14/cve-2017-2446-or-jscjsglobalobjectishavingabadtime/) - 写 [Diary of a reverse-engineer](https://doar-e.github.io/).

## PoCs

<a name="pocs-database"></a>
### Database

- [js-vuln-db](https://github.com/tunz/js-vuln-db) - 使用PoC收集JavaScript引擎CVE [@tunz](https://github.com/tunz).
- [awesome-cve-poc](https://github.com/qazbnm456/awesome-cve-poc) -  CVE PoC的策划列表 [@qazbnm456](https://github.com/qazbnm456).
- [Some-PoC-oR-ExP](https://github.com/coffeehb/Some-PoC-oR-ExP) - 各种漏洞poc、Exp的收集或编写 by [@coffeehb](https://github.com/coffeehb).
- [uxss-db](https://github.com/Metnew/uxss-db) - 使用PoC收集UXSS CVE [@Metnew](https://github.com/Metnew).
- [SPLOITUS](https://sploitus.com/) - 漏洞利用和工具搜索引擎 [@i_bo0om](https://twitter.com/i_bo0om).
- [Exploit Database](https://www.exploit-db.com/) - 漏洞利用，Shellcode和安全文件的最终归档 [Offensive Security](https://www.offensive-security.com/community-projects/the-exploit-database/).

## Tools

<a name="tools-auditing"></a>
### Auditing

- [prowler](https://github.com/Alfresco/prowler) - 用于AWS安全评估，审核和强化的工具 [@Alfresco](https://github.com/Alfresco).
- [A2SV](https://github.com/hahwul/a2sv) - 自动扫描到SSL漏洞 [@hahwul](https://github.com/hahwul).

<a name="tools-command-injection"></a>
### Command Injection

- [commix](https://github.com/commixproject/commix) - 自动化一体化操作系统命令注入和利用工具 [@commixproject](https://github.com/commixproject).

<a name="tools-reconnaissance"></a>
### Reconnaissance

<a name="tools-osint"></a>
#### OSINT - Open-Source Intelligence

- [Shodan](https://www.shodan.io/) -  Shodan是世界上第一个通过互联网连接设备的搜索引擎 [@shodanhq](https://twitter.com/shodanhq).
- [Censys](https://censys.io/) -  Censys是一个搜索引擎，允许计算机科学家提出有关组成互联网的设备和网络的问题 [University of Michigan](https://umich.edu/).
- [urlscan.io](https://urlscan.io/) - 分析网站及其请求的资源的服务 [@heipei](https://twitter.com/heipei).
- [ZoomEye](https://www.zoomeye.org/) - 网络空间搜索引擎 [@zoomeye_team](https://twitter.com/zoomeye_team).
- [FOFA](https://fofa.so/?locale=en) - 网络空间搜索引擎 [BAIMAOHUI](http://baimaohui.net/).
- [NSFOCUS](https://nti.nsfocus.com/) -  NSFOCUS GLOBAL的THREAT INTELLIGENCE门户网站.
- [Photon](https://github.com/s0md3v/Photon) - 为OSINT设计的令人难以置信的快速爬虫 [@s0md3v](https://github.com/s0md3v).
- [FOCA](https://github.com/ElevenPaths/FOCA) -  FOCA（带有收集档案的指纹识别组织）是一种主要用于在其扫描的文档中查找元数据和隐藏信息的工具. [ElevenPaths](https://www.elevenpaths.com/index.html).
- [SpiderFoot](http://www.spiderfoot.net/) - 开源足迹和情报收集工具 [@binarypool](https://twitter.com/binarypool).
- [xray](https://github.com/evilsocket/xray) -  XRay是一种用于从公共网络收集侦察，映射和OSINT的工具 [@evilsocket](https://github.com/evilsocket).
- [gitrob](https://github.com/michenriksen/Gitrob) -  GitHub组织的侦察工具 [@michenriksen](https://github.com/michenriksen).
- [GSIL](https://github.com/FeeiCN/GSIL) - Github Sensitive Information Leakage（Github敏感信息泄露）by [@FeeiCN](https://github.com/FeeiCN).
- [raven](https://github.com/0x09AL/raven) -  raven是一个Linkedin信息收集工具，可供测试人员使用，通过使用Linkedin收集有关组织员工的信息 [@0x09AL](https://github.com/0x09AL).
- [ReconDog](https://github.com/s0md3v/ReconDog) - 侦察瑞士军刀 [@s0md3v](https://github.com/s0md3v).
- [Databases - start.me](https://start.me/p/QRENnO/databases) - 您可以用于OSINT研究的各种数据库 [@technisette](https://twitter.com/technisette).
- [peoplefindThor](https://peoplefindthor.dk/) - 通过Facebook查找人员的简便方法 [postkassen](https://github.com/qazbnm456/awesome-web-security/blob/master/mailto:postkassen@oejvind.dk?subject=peoplefindthor.dk comments).
- [tinfoleak](https://github.com/vaguileradiaz/tinfoleak) - 用于Twitter智能分析的最完整的开源工具 [@vaguileradiaz](https://github.com/vaguileradiaz).
- [Raccoon](https://github.com/evyatarmeged/Raccoon) - 用于侦察和漏洞扫描的高性能攻击性安全工具 [@evyatarmeged](https://github.com/evyatarmeged).
- [Social Mapper](https://github.com/SpiderLabs/social_mapper) -  Jacob Wilkin（Greenwolf）的社交媒体枚举和关联工具 [@SpiderLabs](https://github.com/SpiderLabs).
- [espi0n/Dockerfiles](https://github.com/espi0n/Dockerfiles) - 用于各种OSINT工具的Dockerfiles [@espi0n](https://github.com/espi0n).

<a name="tools-sub-domain-enumeration"></a>
#### Sub Domain Enumeration

- [Sublist3r](https://github.com/aboul3la/Sublist3r) -  Sublist3r是一个用于渗透测试人员的多线程子域枚举工具 [@aboul3la](https://github.com/aboul3la).
- [EyeWitness](https://github.com/ChrisTruncer/EyeWitness) -  EyeWitness旨在获取网站的屏幕截图，提供一些服务器标题信息，并在可能的情况下识别默认凭据 [@ChrisTruncer](https://github.com/ChrisTruncer).
- [subDomainsBrute](https://github.com/lijiejie/subDomainsBrute) - 一个简单快速的子域粗暴工具，用于测试者 [@lijiejie](https://github.com/lijiejie).
- [AQUATONE](https://github.com/michenriksen/aquatone) - 域名天桥的工具 [@michenriksen](https://github.com/michenriksen).
- [domain_analyzer](https://github.com/eldraco/domain_analyzer) - 通过查找可能的所有信息来分析任何域的安全性 [@eldraco](https://github.com/eldraco).
- [VirusTotal domain information](https://www.virustotal.com/en/documentation/searching/#getting-domain-information) - 按域搜索域信息 [VirusTotal](https://www.virustotal.com/).
- [Certificate Transparency](https://github.com/google/certificate-transparency) -  Google的证书透明度项目修复了SSL证书系统中的几个结构性缺陷 [@google](https://github.com/google).
- [Certificate Search](https://crt.sh/) - 输入身份（域名，组织名称等），证书指纹（SHA-1或SHA-256）或crt.sh ID以搜索证书 [@crtsh](https://github.com/crtsh).
- [GSDF](https://github.com/We5ter/GSDF) - 域名搜索者名为GoogleSSLdomainFinder by [@We5ter](https://github.com/We5ter).

<a name="tools-code-generating"></a>
### Code Generating

- [VWGen](https://github.com/qazbnm456/VWGen) - 易受攻击的Web应用程序生成器 [@qazbnm456](https://github.com/qazbnm456).

<a name="tools-fuzzing"></a>
### Fuzzing

- [wfuzz](https://github.com/xmendez/wfuzz) -  Web应用程序bruteforcer by [@xmendez](https://github.com/xmendez).
- [charsetinspect](https://github.com/hack-all-the-things/charsetinspect) - 检查多字节字符集的脚本，用于查找具有特定用户定义属性的字符 [@hack-all-the-things](https://github.com/hack-all-the-things).
- [IPObfuscator](https://github.com/OsandaMalith/IPObfuscator) - 将IP转换为DWORD IP的简单工具 [@OsandaMalith](https://github.com/OsandaMalith).
- [domato](https://github.com/google/domato) -  DOM模糊器 [@google](https://github.com/google).
- [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - 用于黑盒应用程序故障注入和资源发现的攻击模式和基元的字典.
- [dirhunt](https://github.com/Nekmo/dirhunt) - 优化的Web爬虫，用于搜索和分析站点的目录结构 [@nekmo](https://github.com/Nekmo).
- [ssltest](https://www.ssllabs.com/ssltest/)   - 在线服务，对公共互联网上任何SSL Web服务器的配置进行深入分析.  由...提供 [Qualys SSL Labs](https://www.ssllabs.com).

<a name="tools-scanning"></a>
### Scanning

- [wpscan](https://github.com/wpscanteam/wpscan) -  WPScan是一个黑盒子WordPress漏洞扫描器 [@wpscanteam](https://github.com/wpscanteam).
- [JoomlaScan](https://github.com/drego85/JoomlaScan) - 免费软件，用于查找Joomla CMS中安装的组件，这些组件是由Joomscan的灰烬构建 [@drego85](https://github.com/drego85).
- [WAScan](https://github.com/m4ll0k/WAScan) - 是一个开源Web应用程序安全扫描程序，使用“黑盒”方法创建 [@m4ll0k](https://github.com/m4ll0k).

<a name="tools-penetration-testing"></a>
### Penetration Testing

- [Burp Suite](https://portswigger.net/burp/) -  Burp Suite是一个集成平台，用于执行Web应用程序的安全性测试 [portswigger](https://portswigger.net/).
- [TIDoS-Framework](https://github.com/theInfectedDrake/TIDoS-Framework) - 全面的Web应用程序审计框架，涵盖从侦察和OSINT到漏洞分析的所有内容 [@_tID](https://github.com/theInfectedDrake).
- [Astra](https://github.com/flipkart-incubator/astra) - 针对REST API的自动安全测试 [@flipkart-incubator](https://github.com/flipkart-incubator).
- [aws_pwn](https://github.com/dagrz/aws_pwn) -  AWS渗透测试垃圾的集合 [@dagrz](https://github.com/dagrz).
- [grayhatwarfare](https://buckets.grayhatwarfare.com/) - 公共水桶 [grayhatwarfare](http://www.grayhatwarfare.com/).

<a name="tools-offensive"></a>
### Offensive

<a name="tools-xss"></a>
#### XSS - Cross-Site Scripting

- [beef](https://github.com/beefproject/beef) - 浏览器开发框架项目 [beefproject](https://beefproject.com).
- [JShell](https://github.com/s0md3v/JShell) - 使用XSS获取JavaScript shell [@s0md3v](https://github.com/s0md3v).
- [XSStrike](https://github.com/s0md3v/XSStrike)   -  XSStrike是一个可以为XSS提供模糊和强力参数的程序.  它还可以通过检测和绕过WAF [@s0md3v](https://github.com/s0md3v).
- [xssor2](https://github.com/evilcos/xssor2) -  XSS&#39;OR  - 用JavaScript破解 [@evilcos](https://github.com/evilcos).

<a name="tools-sql-injection"></a>
#### SQL Injection

- [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动SQL注入和数据库接管工具.

<a name="tools-template-injection"></a>
#### Template Injection

- [tplmap](https://github.com/epinna/tplmap) - 代码和服务器端模板注入检测和利用工具 [@epinna](https://github.com/epinna).

<a name="tools-csrf"></a>
#### Cross Site Request Forgery

- [XSRFProbe](https://github.com/0xInfection/XSRFProbe) -  Prime CSRF审计与开发工具包 [@0xInfection](https://github.com/0xinfection).

<a name="tools-leaking"></a>
### Leaking

- [HTTPLeaks](https://github.com/cure53/HTTPLeaks) - 所有可能的方式，网站可以泄漏HTTP请求 [@cure53](https://github.com/cure53).
- [dvcs-ripper](https://github.com/kost/dvcs-ripper) - 翻录Web可访问（分布式）版本控制系统：SVN / GIT / HG ... by [@kost](https://github.com/kost).
- [DVCS-Pillage](https://github.com/evilpacket/DVCS-Pillage) - 通过网络访问GIT，HG和BZR存储库 [@evilpacket](https://github.com/evilpacket).
- [GitMiner](https://github.com/UnkL4b/GitMiner) - 用于Github上的内容的高级挖掘工具 [@UnkL4b](https://github.com/UnkL4b).
- [gitleaks](https://github.com/zricethezav/gitleaks) - 通过搜索完整的回购历史记录获取秘密和密钥 [@zricethezav](https://github.com/zricethezav).
- [CSS-Keylogging](https://github.com/maxchehab/CSS-Keylogging) -  Chrome扩展程序和Express服务器，利用CSS的键盘记录功能 [@maxchehab](https://github.com/maxchehab).
- [pwngitmanager](https://github.com/allyshka/pwngitmanager) - 测试者的Git经理 [@allyshka](https://github.com/allyshka).
- [snallygaster](https://github.com/hannob/snallygaster) - 用于扫描HTTP服务器上的秘密文件的工具 [@hannob](https://github.com/hannob).

<a name="tools-detecting"></a>
### Detecting

- [sqlchop](https://sqlchop.chaitin.cn/) -  SQL注入检测引擎 [chaitin](http://chaitin.com).
- [xsschop](https://xsschop.chaitin.cn/) -  XSS检测引擎 [chaitin](http://chaitin.com).
- [retire.js](https://github.com/RetireJS/retire.js) - 扫描程序检测使用已知漏洞的JavaScript库 [@RetireJS](https://github.com/RetireJS).
- [malware-jail](https://github.com/HynekPetrak/malware-jail) -  Sandbox用于半自动Javascript恶意软件分析，反混淆和有效负载提取 [@HynekPetrak](https://github.com/HynekPetrak).
- [repo-supervisor](https://github.com/auth0/repo-supervisor) - 扫描代码以查找安全性错误，搜索密码和密码.
- [bXSS](https://github.com/LewisArdern/bXSS) -  bXSS是一个简单的盲XSS应用程序改编自 [cure53.de/m](https://cure53.de/m) 通过 [@LewisArdern](https://github.com/LewisArdern).
- [OpenRASP](https://github.com/baidu/openrasp)   - 百度公司积极维护的开源RASP解决方案.通过上下文感知检测算法，该项目几乎没有误报.  在服务器负载较重的情况下，性能降低不到3％.
- [GuardRails](https://github.com/apps/guardrails) - 一个GitHub应用程序，在Pull请求中提供安全反馈.

<a name="tools-preventing"></a>
### Preventing

- [DOMPurify](https://github.com/cure53/DOMPurify) - 适用于HTML，MathML和SVG的仅限DOM，超快速，超级容忍的XSS清洁剂 [Cure53](https://cure53.de/).
- [js-xss](https://github.com/leizongmin/js-xss) - 使用白名单指定的配置清理不受信任的HTML（以防止XSS） [@leizongmin](https://github.com/leizongmin).
- [Acra](https://github.com/cossacklabs/acra) - 用于SQL数据库的客户端加密引擎，具有强选择性加密，SQL注入预防和入侵检测功能 [@cossacklabs](https://www.cossacklabs.com/).

<a name="tools-proxy"></a>
### Proxy

- [Charles](https://www.charlesproxy.com/) -  HTTP代理/ HTTP监视器/反向代理，使开发人员能够查看其计算机和Internet之间的所有HTTP和SSL / HTTPS流量.
- [mitmproxy](https://github.com/mitmproxy/mitmproxy) - 支持交互式TLS的拦截HTTP代理，用于渗透测试人员和软件开发人员 [@mitmproxy](https://github.com/mitmproxy).

<a name="tools-webshell"></a>
### Webshell

- [nano](https://github.com/s0md3v/nano) - 代码系列高尔夫球的PHP shell [@s0md3v](https://github.com/s0md3v).
- [webshell](https://github.com/tennc/webshell) - 这是一个webshel​​l开源项目 [@tennc](https://github.com/tennc).
- [Weevely](https://github.com/epinna/weevely3) - 武器化的网络外壳 [@epinna](https://github.com/epinna).
- [Webshell-Sniper](https://github.com/WangYihang/Webshell-Sniper) - 通过终端管理您的网站 [@WangYihang](https://github.com/WangYihang).
- [Reverse-Shell-Manager](https://github.com/WangYihang/Reverse-Shell-Manager) - 通过终端反向Shell管理器[@WangYihang](https://github.com/WangYihang).
- [reverse-shell](https://github.com/lukechilds/reverse-shell) - 反向壳牌即服务 [@lukechilds](https://github.com/lukechilds).

<a name="tools-disassembler"></a>
### Disassembler

- [plasma](https://github.com/plasma-disassembler/plasma) -  Plasma是x86 / ARM / MIPS的交互式反汇编程序 [@plasma-disassembler](https://github.com/plasma-disassembler).
- [radare2](https://github.com/radare/radare2) - 类似Unix的逆向工程框架和命令行工具 [@radare](https://github.com/radare).
- [Iaitō](https://github.com/hteso/iaito) - 用于radare2逆向工程框架的Qt和C ++ GUI [@hteso](https://github.com/hteso).

<a name="tools-decompiler"></a>
### Decompiler

- [CFR](http://www.benf.org/other/cfr/) - 另一个java反编译器 [@LeeAtBenf](https://twitter.com/LeeAtBenf).

<a name="tools-others"></a>
### Others

- [Dnslogger](https://wiki.skullsecurity.org/index.php?title=Dnslogger) -  DNS记录器 [@iagox86](https://github.com/iagox86).
- [CyberChef](https://github.com/gchq/CyberChef) -  Cyber​​ Swiss Army Knife  - 一款用于加密，编码，压缩和数据分析的网络应用程序 [@GCHQ](https://github.com/gchq).

## Social Engineering Database

**使用风险自负**

- [haveibeenpwned](https://haveibeenpwned.com/) - 检查您的帐户是否因数据泄露而受到损害 [Troy Hunt](https://www.troyhunt.com/).
- [databases.today](https://www.databases.today/index.php) - 面向安全研究人员和记者的最大免费下载公共网站数据库集合 [@publicdbhost](https://twitter.com/publicdbhost).
- [mysql-password](http://www.mysql-password.com/database/1) -  MySQL哈希数据库.

## Blogs

- [Orange](http://blog.orange.tw/) - 台湾有才华的网络穿透者.
- [leavesongs](https://www.leavesongs.com/) - 中国有才华的网络渗透者.
- [James Kettle](http://albinowax.skeletonscribe.net/) - 研究负责人 [PortSwigger Web Security](https://portswigger.net/).
- [Broken Browser](https://www.brokenbrowser.com/) - 浏览器漏洞的乐趣.
- [Scrutiny](https://datarift.blogspot.tw/) -  Dhiraj Mishra通过Web浏览器进行的Internet安全.
- [Blog of Osanda](https://osandamalith.com/) - 安全研究和逆向工程.
- [BRETT BUERHAUS](https://buer.haus/) - 针对应用程序安全性的漏洞披露和疏忽.
- [n0tr00t](https://www.n0tr00t.com/) - ~# n0tr00t Security Team.
- [OpnSec](https://opnsec.com/) - 开放思想安全！
- [LoRexxar](https://lorexxar.cn/) - 带着对技术的敬畏之心成长，不安于一隅...
- [Wfox](http://sec2hack.com/) - 技术宅，热衷各种方面.
- [RIPS Technologies](https://blog.ripstech.com/tags/security/) -  PHP漏洞的注释.
- [0Day Labs](http://blog.0daylabs.com/) - 令人敬畏的错误 - 赏金和挑战写作.
- [Blog of Osanda](https://osandamalith.com/) - 安全研究和逆向工程.

## Twitter Users

- [@HackwithGitHub](https://twitter.com/HackwithGithub) - 主动展示黑客和测试者的开源黑客工具
- [@filedescriptor](https://twitter.com/filedescriptor) - 主动穿透者经常推文和写有用的文章
- [@cure53berlin](https://twitter.com/cure53berlin) - [Cure53](https://cure53.de/) 是一家德国网络安全公司.
- [@XssPayloads](https://twitter.com/XssPayloads) -  JavaScript意外用法的仙境，等等.
- [@kinugawamasato](https://twitter.com/kinugawamasato) - 日本网络穿透器.
- [@h3xstream](https://twitter.com/h3xstream/) - 安全研究员，对网络安全，加密，测试，静态分析感兴趣，但最重要的是，萨米是我的英雄.
- [@garethheyes](https://twitter.com/garethheyes) - 英文网络穿透者.
- [@hasegawayosuke](https://twitter.com/hasegawayosuke) - 日本javascript安全研究员.

## Practices

<a name="practices-application"></a>
### Application

- [OWASP Juice Shop](https://github.com/bkimminich/juice-shop) - 可能是最现代和最复杂的不安全的Web应用程序 - 写 [@bkimminich](https://github.com/bkimminich) 和 [@owasp_juiceshop](https://twitter.com/owasp_juiceshop) 球队.
- [BadLibrary](https://github.com/SecureSkyTechnology/BadLibrary) - 用于培训的易受攻击的Web应用程序 - 撰写 [@SecureSkyTechnology](https://github.com/SecureSkyTechnology).
- [Hackxor](http://hackxor.net/) - 逼真的网络应用程序黑客游戏 - 撰写 [@albinowax](https://twitter.com/albinowax).
- [SELinux Game](http://selinuxgame.org/)   - 通过做学习SELinux.  解决难题，展示技巧 - 写作 [@selinuxgame](https://twitter.com/selinuxgame).

<a name="practices-aws"></a>
### AWS

- [FLAWS](http://flaws.cloud/) - 亚马逊AWS CTF挑战 - 撰写 [@0xdabbad00](https://twitter.com/0xdabbad00).
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) -  Rhino Security Labs的“易受设计”AWS基础设施设置工具 - 撰写 [@RhinoSecurityLabs](https://github.com/RhinoSecurityLabs).

<a name="practices-xss"></a>
### XSS

- [XSS Thousand Knocks](https://knock.xss.moe/index) -  XSS千敲 - 写作 [@yagihashoo](https://twitter.com/yagihashoo).
- [XSS game](https://xss-game.appspot.com/) -  Google XSS挑战赛 - 由Google撰写.
- [prompt(1) to win](http://prompt.ml/) -  2014年夏季举办的复杂16级XSS挑战赛（+4隐藏级别） - 撰写 [@cure53](https://github.com/cure53).
- [alert(1) to win](https://alf.nu/alert1) -  XSS系列挑战 - 撰写 [@steike](https://twitter.com/steike).
- [XSS Challenges](http://xss-quiz.int21h.jp/) -  XSS系列挑战 - 由yamagata21撰写.

<a name="practices-modsecurity"></a>
### ModSecurity / OWASP ModSecurity Core Rule Set

- [ModSecurity / OWASP ModSecurity Core Rule Set](https://www.netnea.com/cms/apache-tutorials/) - 一系列安装，配置和调整ModSecurity和核心规则集的教程 - 撰写者 [@ChrFolini](https://twitter.com/ChrFolini).

## Community

- [Reddit](https://www.reddit.com/r/websecurity/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/security)

## Miscellaneous

- [awesome-bug-bounty](https://github.com/djadmin/awesome-bug-bounty) - 全面的可用Bug Bounty＆Disclosure Program和策略列表 [@djadmin](https://github.com/djadmin).
- [bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference) - 由bug性质分类的bug赏金记录列表 [@ngalongc](https://github.com/ngalongc).
- [Google VRP and Unicorns](https://sites.google.com/site/bughunteruniversity/behind-the-scenes/presentations/google-vrp-and-unicorns) - 写 [Daniel Stelter-Gliese](https://www.linkedin.com/in/daniel-stelter-gliese-170a70a2/).
- [Brute Forcing Your Facebook Email and Phone Number](http://pwndizzle.blogspot.jp/2014/02/brute-forcing-your-facebook-email-and.html) - 写 [PwnDizzle](http://pwndizzle.blogspot.jp/).
- [Pentest + Exploit dev Cheatsheet wallpaper](http://i.imgur.com/Mr9pvq9.jpg) - 渗透测试和利用Dev CheatSheet.
- [The Definitive Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/) - 由JASON TROS撰写.
- [EQGRP](https://github.com/x0rz/EQGRP) - 解密的eqgrp-auction-file.tar.xz内容 [@x0rz](https://github.com/x0rz).
- [Browser Extension and Login-Leak Experiment](https://extensions.inrialpes.fr/) - 浏览器扩展和登录泄漏实验.
- [notes](https://github.com/ChALkeR/notes) - 一些公开说明 [@ChALkeR](https://github.com/ChALkeR).
- [A glimpse into GitHub's Bug Bounty workflow](https://githubengineering.com/githubs-bug-bounty-workflow/) - 写 [@gregose](https://github.com/gregose).
- [Cybersecurity Campaign Playbook](https://www.belfercenter.org/CyberPlaybook) - 写 [Belfer Center for Science and International Affairs](https://www.belfercenter.org/).
- [Infosec_Reference](https://github.com/rmusser01/Infosec_Reference) - 不吸引人的信息安全参考 [@rmusser01](https://github.com/rmusser01).
- [Internet of Things Scanner](http://iotscanner.bullguard.com/) - 检查您家中连接互联网的设备是否在Shodan by上市 [BullGuard](https://www.bullguard.com/).
- [The Bug Hunters Methodology v2.1](https://docs.google.com/presentation/d/1VpRT8dFyTaFpQa9jhehtmGaC7TqQniMSYbUdlHN6VrY/edit?usp=sharing) - 写 [@jhaddix](https://twitter.com/jhaddix).
- [$7.5k Google services mix-up](https://sites.google.com/site/testsitehacking/-7-5k-Google-services-mix-up) - 写 [Ezequiel Pereira](https://sites.google.com/site/testsitehacking/).
- [How I exploited ACME TLS-SNI-01 issuing Let's Encrypt SSL-certs for any domain using shared hosting](https://labs.detectify.com/2018/01/12/how-i-exploited-acme-tls-sni-01-issuing-lets-encrypt-ssl-certs-for-any-domain-using-shared-hosting/) - 写 [@fransrosen](https://twitter.com/fransrosen).
- [TL:DR: VPN leaks users’ IPs via WebRTC. I’ve tested seventy VPN providers and 16 of them leaks users’ IPs via WebRTC (23%)](https://voidsec.com/vpn-leak/) - 写 [voidsec](https://voidsec.com/).
- [Escape and Evasion Egressing Restricted Networks](https://www.optiv.com/blog/escape-and-evasion-egressing-restricted-networks) - 写 [Chris Patten, Tom Steele](https://github.com/qazbnm456/awesome-web-security/blob/master/info@optiv.com).
- [Be careful what you copy: Invisibly inserting usernames into text with Zero-Width Characters](https://medium.com/@umpox/be-careful-what-you-copy-invisibly-inserting-usernames-into-text-with-zero-width-characters-18b4e6f17b66) - 写 [@umpox](https://medium.com/@umpox).
- [Domato Fuzzer's Generation Engine Internals](https://www.sigpwn.io/blog/2018/4/14/domato-fuzzers-generation-engine-internals) - 写 [sigpwn](https://www.sigpwn.io/).
- [CSS Is So Overpowered It Can Deanonymize Facebook Users](https://www.evonide.com/side-channel-attacking-browsers-through-css3-features/) - 写 [Ruslan Habalov](https://www.evonide.com/).
- [Introduction to Web Application Security](https://www.slideshare.net/nragupathy/introduction-to-web-application-security-blackhoodie-us-2018) - 写 [@itsC0rg1](https://twitter.com/itsC0rg1), [@jmkeads](https://twitter.com/jmkeads) 和 [@matir](https://twitter.com/matir).
- [Finding The Real Origin IPs Hiding Behind CloudFlare or TOR](https://www.secjuice.com/finding-real-ips-of-origin-servers-behind-cloudflare-or-tor/) - 写 [Paul Dannewitz](https://www.secjuice.com/author/paul-dannewitz/).
- [Why Facebook's api starts with a for loop](https://dev.to/antogarand/why-facebooks-api-starts-with-a-for-loop-1eob?fbclid=IwAR0BQ7RmYGzQzsL33IJ2LM7lmlH0OSuIuxKLebUUBi1D51R-9UOnHrW0DQg) - 写 [@AntoGarand](https://twitter.com/AntoGarand).
- [How I could have stolen your photos from Google - my first 3 bug bounty writeups](https://blog.avatao.com/How-I-could-steal-your-photos-from-Google/) - 写 [@gergoturcsanyi](https://twitter.com/gergoturcsanyi).

## Code of Conduct

请注意，此项目已发布 [Contributor Code of Conduct](https://github.com/qazbnm456/awesome-web-security/blob/master/code-of-conduct.md) .  参与此项目即表示您同意遵守其条款.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [@qazbnm456](https://qazbnm456.github.io/) 已放弃对此作品的所有版权及相关或相邻权利.
