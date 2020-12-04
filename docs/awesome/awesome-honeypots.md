<div class="github-widget" data-repo="paralax/awesome-honeypots"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Honeypots [![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的超棒蜜罐清单，以及相关组件等等，分为Web，服务和其他类别，重点是免费和开源项目.

每个类别中没有预先确定的项目顺序，该顺序是用于贡献的. 如果您想贡献，请阅读 [guide](https://github.com/paralax/awesome-honeypots/blob/master/CONTRIBUTING.md).

发现更多精彩列表 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).



## Related Lists

- [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools) -在网络流量分析中很有用.
- [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis) -这里有些重叠以进行工件分析.

## Honeypots

-数据库蜜罐
    - [Delilah](https://github.com/SecurityTW/delilah) -用Python编写的Elasticsearch Honeypot（最初来自Novetta）.
    - [ESPot](https://github.com/mycert/ESPot) -用NodeJS编写的Elasticsearch honeypot，以捕获利用CVE-2014-3120的所有尝试.
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) -简单的Elasticsearch Honeypot.
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) -MongoDB蜜罐代理.
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - Honeypot framework built on a NoSQL-style database.
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) -用C编写的低交互MySQL蜜罐.
    - [MysqlPot](https://github.com/schmalle/MysqlPot) -MySQL蜜罐，仍处于早期阶段.
    - [pghoney](https://github.com/betheroot/pghoney) -低互动性Postgres Honeypot.
    - [sticky_elephant](https://github.com/betheroot/sticky_elephant) -中等交互性postgresql honeypot.

-网络蜜罐
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) -Symfony2表单的蜜罐类型.
    - [Glastopf](https://github.com/mushorg/glastopf) -Web应用程序蜜罐.
    - [Google Hack Honeypot](http://ghh.sourceforge.net) -旨在针对使用搜索引擎作为针对您资源的黑客工具的攻击者进行侦察.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) -适用于Laravel应用程序的简单垃圾邮件防护包.
    - [Nodepot](https://github.com/schmalle/Nodepot) -NodeJS Web应用程序蜜罐.
    - [Servletpot](https://github.com/schmalle/servletpot) -Web应用程序Honeypot.
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) -适用于PHP，Perl和Python应用程序的模块化Web应用程序防火墙/高交互Honeypot.
    - [StrutsHoneypot](https://github.com/Cymmetria/StrutsHoneypot) -Struts基于Apache 2的蜜罐以及用于Apache 2服务器的检测模块.
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) -旨在创建欺骗性网页，以欺骗攻击者并将其重定向到真实网站之外.
    - [basic-auth-pot (bap)](https://github.com/bjeborn/basic-auth-pot) -HTTP基本身份验证蜜罐.
    - [bwpot](https://github.com/graneed/bwpot) -易碎的Web应用程序honeyPot.
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) -伪造的Django管理员登录屏幕，用于通知管理员未授权的访问尝试.
    - [drupo](https://github.com/d1str0/drupot) -Drupal蜜罐.
    - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) -基于Python的Web服务器蜜罐生成器.
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) -简单有效的phpMyAdmin honeypot.
    - [shockpot](https://github.com/threatstream/shockpot) -WebApp Honeypot，用于检测Shell Shock攻击尝试.
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) -PHP脚本演示了一个智能蜜罐.
    -军鼓/制革厂-Glastopf的后继者
        - [Snare](https://github.com/mushorg/snare) -超级下一代高级反应式蜜罐.
        - [Tanner](https://github.com/mushorg/tanner) -评估SNARE事件.
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) -在垃圾邮件漫游器中插入陷阱.
    - [tomcat-manager-honeypot](https://github.com/helospark/tomcat-manager-honeypot)  -模仿Tomcat管理器端点的Honeypot. 记录请求并保存攻击者的WAR文件以供以后研究
    -WordPress蜜罐
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) -WordPress登录蜜罐，用于收集和分析失败的登录尝试.
        - [HoneyPress](https://github.com/kungfuguapo/HoneyPress) -Docker容器中基于Python的WordPress Honeypot.
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) -WordPress插件可通过更智能的蜜罐减少评论垃圾邮件.
        - [wordpot](https://github.com/gbrindisi/wordpot) -WordPress蜜罐.

-服务蜜罐
    - [ADBHoney](https://github.com/huuck/ADBHoney) -低交互性蜜罐，可模拟运行Android调试桥（ADB）服务器进程的Android设备. 
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) -英特尔AMT固件漏洞CVE-2017-5689的蜜罐.
X - [Ensnare](https://github.com/ahoernecke/ensnare) -易于部署Ruby honeypot.
    - [HoneyPy](https://github.com/foospidy/HoneyPy) -低互动蜜罐.
    - [Honeygrove](https://github.com/UHH-ISS/honeygrove) -基于Twisted的多功能模块化蜜罐.
    - [Honeyport](https://github.com/securitygeneration/Honeyport) -用Bash和Python编写的简单honeyport.
    - [Honeyprint](https://github.com/glaslos/honeyprint) -打印机蜜罐.
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) -现代的高交互蜜罐框架.
    - [MICROS honeypot](https://github.com/Cymmetria/micros_honeypot) -低交互性蜜罐，用于检测Oracle Hospitality Applications（MICROS）的Oracle Hospitality Simphony组件中的CVE-2018-2636.
    - [RDPy](https://github.com/citronneur/rdpy) -以Python实现的Microsoft远程桌面协议（RDP）蜜罐.
    - [SMB Honeypot](https://github.com/r0hi7/HoneySMB) -高交互性的SMB服务蜜罐，能够捕获类似幻想的恶意软件.
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) -低交互Python蜜罐.
    - [WebLogic honeypot](https://github.com/Cymmetria/weblogic_honeypot) -低交互性蜜罐，用于检测Oracle Fusion Middleware的Oracle WebLogic Server组件中的CVE-2017-10271.
    - [WhiteFace Honeypot](https://github.com/csirtgadgets/csirtg-honeypot) -用于WhiteFace的扭曲型蜜罐.
    - [dhp](https://github.com/ciscocsirt/dhp) -简单的Docker Honeypot服务器，模拟Docker HTTP API的小片段.
    - [honeycomb_plugins](https://github.com/Cymmetria/honeycomb_plugins) -Honeycomb的插件存储库，Cymmetria的honeypot框架.
    - [honeyntp](https://github.com/fygrave/honeyntp) -NTP记录器/蜜罐.
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) -观察相机蜜罐.
    - [honeypot-ftp](https://github.com/alexbredo/honeypot-ftp) -FTP Honeypot.
    - [honeytrap](https://github.com/honeytrap/honeytrap) -用Go编写的高级Honeypot框架，可以与其他honeypot软件连接.
    - [pyrdp](https://github.com/gosecure/pyrdp) -适用于Python 3的RDP中间人和库，能够实时监视或实时监视连接.
    - [troje](https://github.com/dutchcoders/troje/) -Honeypot，它在单独的LXC容器中运行与服务的每个连接.

-分布式蜜罐
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) -低交互蜜罐服务器.

-反蜜罐的东西
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) -检测Kippo蜜罐是否存在的令人反感的组件.

-ICS / SCADA蜜罐
    - [Conpot](https://github.com/mushorg/conpot) -ICS / SCADA蜜罐.
    - [GasPot](https://github.com/sjhilt/GasPot) -Veeder Root Gaurdian AST，在石油和天然气行业中很常见.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) -建立用于工业网络的蜜罐.
    - [gridpot](https://github.com/sk4ld/gridpot) -用于实现逼真的电网蜜网的开源工具.
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) -模仿流行的PLC提供的许多服务，并更好地帮助SCADA研究人员了解暴露的控制系统设备的潜在风险.

-其他/随机
    - [Damn Simple Honeypot (DSHP)](https://github.com/naorlivne/dshp) -具有可插拔处理程序的Honeypot框架.
    - [NOVA](https://github.com/DataSoft/Nova) -使用蜜罐作为检测器，看起来像一个完整的系统.
    - [OpenFlow Honeypot (OFPot)](https://github.com/upa/ofpot) -将未使用IP的流量重定向到基于POX的蜜罐.
    - [OpenCanary](https://github.com/thinkst/opencanary) -模块化和分散式蜜罐守护程序，该守护程序运行多个服务的canary版本，在（不）使用服务时发出警报.
    - [ciscoasa_honeypot](https://github.com/cymmetria/ciscoasa_honeypot) 用于Cisco ASA组件的低交互性蜜罐，能够检测CVE-2018-0101，DoS和远程代码执行漏洞. 
    - [miniprint](https://github.com/sa7mon/miniprint) -中型交互打​​印机蜜罐.

-僵尸网络C2工具
    - [Hale](https://github.com/pjlantz/Hale) -僵尸网络命令和控制监视器.
    - [dnsMole](https://code.google.com/archive/p/dns-mole/) -分析DNS流量并潜在地检测botnet命令并控制服务器活动以及受感染的主机.

-IPv6攻击检测工具
    - [ipv6-attack-detector](https://github.com/mzweilin/ipv6-attack-detector/) -由Honeynet Project组织支持的Google Summer of Code 2012项目.

-动态代码检测工具包
    - [Frida](https://www.frida.re) -注入JavaScript以探索Windows，Mac，Linux，iOS和Android上的本机应用程序.

-将网站转换为服务器蜜罐的工具
    - [HIHAT](http://hihat.sourceforge.net/) -将任意PHP应用程序转换为基于Web的高交互Honeypots.

-恶意软件收集器
    - [Kippo-Malware](https://bruteforcelab.com/kippo-malware) -Python脚本，它将下载所有以URL形式存储在Kippo SSH honeypot数据库中的恶意文件.

-分布式传感器部署
    - [Community Honey Network](https://communityhoneynetwork.readthedocs.io/en/stable/)  -CHN旨在使部署蜜罐和蜜罐管理工具变得轻松灵活. 默认部署方法使用Docker Compose和Docker通过一些简单命令进行部署.
    - [Modern Honey Network](https://github.com/threatstream/mhn) -多口和蜜罐传感器管理，使用虚拟机网络，小型SNORT安装，隐秘的透纳音和一个集中式服务器进行管理.

-网络分析工具
    - [Tracexploit](https://code.google.com/archive/p/tracexploit/) -重播网络数据包.

-日志匿名器
    - [LogAnon](http://code.google.com/archive/p/loganon/) -日志匿名化库，可帮助使日志和网络捕获之间的匿名日志保持一致.

-低互动蜜罐（路由器后门）
    - [Honeypot-32764](https://github.com/knalli/honeypot-for-tcp-32764) -路由器后门（TCP 32764）的蜜罐.
    - [WAPot](https://github.com/lcashdol/WAPot) -蜜罐，可用于观察定向到家用路由器的流量.

-蜜网农场流量重定向器
    - [Honeymole](https://web.archive.org/web/20100326040550/http://www.honeynet.org.pt:80/index.php/HoneyMole) -部署多个传感器，将流量重定向到集中的蜜罐集合.

-HTTPS代理
    - [mitmproxy](https://mitmproxy.org/) -允许截取，检查，修改和重放流量.

-系统仪表
    - [Sysdig](https://sysdig.com/opensource/) -开源的系统级浏览允许您从运行的GNU / Linux实例中捕获系统状态和活动，然后保存，过滤和分析结果.
    - [Fibratus](https://github.com/rabbitstack/fibratus) -Windows内核探索和跟踪工具.

-用于USB传播恶意软件的Honeypot
    - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) -蜜罐，用于通过USB存储设备传播的恶意软件.

- 数据采集
    - [Kippo2MySQL](https://bruteforcelab.com/kippo2mysql) -从Kippo基于文本的日志文件中提取一些非常基本的统计信息，并将其插入MySQL数据库中.
    - [Kippo2ElasticSearch](https://bruteforcelab.com/kippo2elasticsearch) -Python脚本，用于将数据从Kippo SSH蜜罐MySQL数据库传输到ElasticSearch实例（服务器或集群）.

-被动网络审核框架解析器
    - [Passive Network Audit Framework (pnaf)](https://github.com/jusafing/pnaf) -结合了多种被动和自动分析技术的框架，以提供对网络平台的安全评估.

-虚拟机监控和工具
    - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) -用于创建与VirtualBox一起使用的模板的脚本，以使VM检测更加困难.
    - [VMCloak](https://github.com/hatching/vmcloak) -自动生成和隐藏杜鹃沙箱的虚拟机.
    - [vmitools](http://libvmi.com/) -具有Python绑定的C库，可以轻松监视正在运行的虚拟机的低级详细信息.

-二进制调试器
    - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) -调试器后端和用于PIN的LUA包装器.
    - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) -调试器前端.

-移动分析工具
    - [Androguard](https://github.com/androguard/androguard) -对Android应用程序进行逆向工程，恶意软件和良好软件分析等.
    - [APKinspector](https://github.com/honeynet/apkinspector/) -强大的GUI工具，供分析人员分析Android应用程序.

-低互动蜜罐
    - [Honeyperl](https://sourceforge.net/projects/honeyperl/) -基于Perl的Honeypot软件，带有为多种功能而开发的插件，这些功能包括：wingates，telnet，squid，smtp等.
    - [T-Pot](https://github.com/dtag-dev-sec/tpotce) -电信提供商T-Mobile的多合一蜜罐设备

-Honeynet数据融合
    - [HFlow2](https://projects.honeynet.org/hflow) -用于蜜网/网络分析的数据合并工具.

-服务器
    - [Amun](http://amunhoney.sourceforge.net) -漏洞仿真蜜罐.
    - [Artillery](https://github.com/trustedsec/artillery/) -开源的蓝色团队工具，旨在通过多种方法保护Linux和Windows操作系统.
    - [Bait and Switch](http://baitnswitch.sourceforge.net) -将所有恶意流量重定向到蜜罐，蜜罐会部分镜像您的生产系统.
    - [Bifrozt](https://github.com/Ziemeck/bifrozt-ansible) - Automatic deploy bifrozt with ansible.
    - [Conpot](http://conpot.org/) -低交互服务器端工业控制系统蜜罐.
    - [Heralding](https://github.com/johnnykv/heralding) -证书捕获蜜罐.
    - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) -低交互Python蜜罐，旨在模仿攻击者可能瞄准的服务或端口.
    - [Honeyd](https://github.com/provos/honeyd) -看 [honeyd tools](#honeyd-tools).
    - [Honeysink](http://www.honeynet.org/node/773) -开源网络漏洞，提供一种机制，用于检测和预防给定网络上的恶意流量.
    - [Hontel](https://github.com/stamparm/hontel) -Telnet蜜罐.
    - [KFSensor](http://www.keyfocus.net/kfsensor/) -基于Windows的蜜罐入侵检测系统（IDS）.
    - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) -接管未使用的IP地址，并创建对蠕虫，黑客和其他Internet诱人的虚拟服务器.
    - [MTPot](https://github.com/Cymmetria/MTPot) -开源Telnet Honeypot，专注于Mirai恶意软件.
    - [SIREN](https://github.com/blaverick62/SIREN) -半智能HoneyPot网络-HoneyNet智能虚拟环境.
    - [TelnetHoney](https://github.com/balte/TelnetHoney) -简单的telnet蜜罐.
    - [UDPot Honeypot](https://github.com/jekil/UDPot) -简单的UDP / DNS蜜罐脚本.
    - [Yet Another Fake Honeypot (YAFH)](https://github.com/fnzv/YAFH) -用Go编写的简单蜜罐.
    - [arctic-swallow](https://github.com/ajackal/arctic-swallow) -低互动蜜罐.
    - [glutton](https://github.com/mushorg/glutton) -所有吃蜜罐.
    - [go-HoneyPot](https://github.com/Mojachieee/go-HoneyPot) -用Go编写的Honeypot服务器.
    - [go-emulators](https://github.com/kingtuna/go-emulators) -Honeypot Golang模拟器.
    - [honeymail](https://github.com/sec51/honeymail) -用Golang编写的SMTP honeypot.
    - [honeytrap](https://github.com/tillmannw/honeytrap) -编写用于捕获针对TCP和UDP服务的攻击的低交互蜜罐和网络安全工具.
    - [imap-honey](https://github.com/yvesago/imap-honey) -用Golang编写的IMAP蜜罐.
    - [mwcollectd](https://www.openhub.net/p/mwcollectd) -多功能恶意软件收集后台程序，结合了猪笼草和蜜罐的最佳功能.
    - [potd](https://github.com/lnslbrty/potd) -高度可扩展的低交互到中等交互的SSH / TCP蜜罐，是为OpenWrt / IoT设备设计的，利用了几种Linux内核功能，例如名称空间，seccomp和线程功能.
    - [portlurker](https://github.com/bartnv/portlurker) -Rust中的端口监听器，带有协议猜测功能和安全的字符串显示功能.
    - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) -简单的低交互端口监视蜜罐.
    - [telnet-iot-honeypot](https://github.com/Phype/telnet-iot-honeypot) -用于捕获僵尸网络二进制文件的Python telnet honeypot.
    - [telnetlogger](https://github.com/robertdavidgraham/telnetlogger) -旨在跟踪Mirai僵尸网络的Telnet honeypot.
    - [vnclowpot](https://github.com/magisterquis/vnclowpot) -低交互VNC蜜罐.


-IDS签名生成
    - [Honeycomb](http://www.icir.org/christian/honeycomb/) -使用蜜罐自动创建签名.

-查找AS号和前缀的服务
    - [CC2ASN](http://www.cc2asn.com/) -简单的查询服务，用于查询世界上任何国家/地区的AS号和前缀.

-数据收集/数据共享
    - [HPfriends](http://hpfriends.honeycloud.net/#/home) -Honeypot数据共享平台.
        - [hpfriends - real-time social data-sharing](https://heipei.io/sigint-hpfriends/) -关于HPFriends feed系统的介绍 
    - [HPFeeds](https://github.com/rep/hpfeeds/) -轻量级认证的发布-订阅协议.

-中央管理工具
    - [PHARM](http://www.nepenthespharm.com/) -管理，报告和分析您的分布式猪笼草实例.

-网络连接分析仪
    - [Impost](http://impost.sourceforge.net/) -网络安全审核工具，用于分析受感染和/或易受攻击的守护程序背后的取证. 

-蜜罐部署
    - [Modern Honeynet Network](http://threatstream.github.io/mhn/) -简化安全蜜罐的部署和管理.

-Wireshark的Honeypot扩展
    - [Wireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) -使用Wireshark对数据包捕获文件应用Snort IDS规则和签名.


-客户
    - [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
    - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    - [Capture-HPC-NG](https://github.com/CERT-Polska/HSN-Capture-HPC-NG)
    - [Capture-HPC](https://projects.honeynet.org/capture-hpc) -高交互性客户端蜜罐（也称为honeyclient）.
    - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    - [HoneyC](https://projects.honeynet.org/honeyc)
    - [HoneySpider Network](https://github.com/CERT-Polska/hsn2-bundle) -高度可扩展的系统，集成了多个客户端蜜罐以检测恶意网站.
    - [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/) -创建用于管理和远程共享Honeyclients资源的Web界面. 
    - [Jsunpack-n](https://github.com/urule99/jsunpack-n)
    - [MonkeySpider](http://monkeyspider.sourceforge.net)
    - [PhoneyC](https://github.com/honeynet/phoneyc) -Python honeyclient（后来被Thug取代）.
    - [Pwnypot](https://github.com/shjalayeri/pwnypot) -高交互客户端蜜罐.
    - [Rumal](https://github.com/thugs-rumal/) -暴徒的Rumāl：暴徒的服装和武器.
    - [Shelia](https://www.cs.vu.nl/~herbertb/misc/shelia/) -用于攻击检测的客户端蜜罐.
    - [Thug](https://buffer.github.io/thug/) -基于Python的低交互性honeyclient.
    - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)
    - [Trigona](https://www.honeynet.org/project/Trigona)
    - [URLQuery](https://urlquery.net/)
    - [YALIH (Yet Another Low Interaction Honeyclient)](https://github.com/Masood-M/yalih) -低交互客户端蜜罐，旨在通过签名，异常和模式匹配技术检测恶意网站.

- 蜜罐
    - [Deception Toolkit](http://www.all.net/dtk/dtk.html)
    - [IMHoneypot](https://github.com/mushorg/imhoneypot)

-PDF文件检查器
    - [peepdf](https://github.com/jesparza/peepdf) -强大的Python工具，可分析PDF文档.

-混合低/高交互蜜罐
    - [HoneyBrid](http://honeybrid.sourceforge.net)

-SSH蜜罐
    - [Blacknet](https://github.com/morian/blacknet) -多头SSH蜜罐系统.
    - [Cowrie](https://github.com/cowrie/cowrie) -Cowrie SSH Honeypot（基于kippo）.
    - [DShield docker](https://github.com/xme/dshield-docker) -在启用DShield输出的情况下运行Cowrie的Docker容器.
    - [HonSSH](https://github.com/tnich/honssh) -记录客户端和服务器之间的所有SSH通信.
    - [HUDINX](https://github.com/Cryptix720/HUDINX) -微小的交互SSH Honeypot用Python设计，可记录暴力攻击，最重要的是，攻击者执行的整个外壳交互.
    - [Kippo](https://github.com/desaster/kippo) -中级交互SSH honeypot.
    - [Kippo_JunOS](https://github.com/gregcmartin/Kippo_JunOS) -Kippo配置为后门网络屏幕.
    - [Kojoney2](https://github.com/madirish/kojoney2) -由Jose Antonio Coret基于Kojoney编写的低交互SSH蜜罐.
    - [Kojoney](http://kojoney.sourceforge.net/) -基于Python的低交互蜜罐，可模拟通过Twisted Conch实现的SSH服务器.
    - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) -分析的SSH蜜罐日志.
    - [Malbait](https://github.com/batchmcnulty/Malbait) - Simple TCP/UDP honeypot implemented in Perl.
    - [MockSSH](https://github.com/ncouture/MockSSH) -模拟SSH服务器并定义其支持的所有命令（Python，Twisted）.
    - [cowrie2neo](https://github.com/xlfe/cowrie2neo) -解析Cowrie honeypot登录到neo4j数据库.
    - [go-sshoney](https://github.com/ashmckenzie/go-sshoney) -SSH Honeypot.
    - [go0r](https://github.com/fzerorubigd/go0r) -Golang中的简单ssh honeypot.
    - [gohoney](https://github.com/PaulMaddox/gohoney) -用Go编写的SSH honeypot.
    - [hived](https://github.com/sahilm/hived) -基于Golang的蜜罐.
    - [hnypots-agent)](https://github.com/joshrendek/hnypots-agent) -Go中的SSH服务器，用于记录用户名和密码组合.
    - [honeypot.go](https://github.com/mdp/honeypot.go) -用Go编写的SSH Honeypot.
    - [honeyssh](https://github.com/ppacher/honeyssh) -带统计信息的凭证转储SSH蜜罐.
    - [hornet](https://github.com/czardoz/hornet) -支持多个虚拟主机的中等交互SSH蜜罐.
    - [ssh-auth-logger](https://github.com/JustinAzoff/ssh-auth-logger) -低/零交互SSH身份验证记录蜜罐.
    - [ssh-honeypot](https://github.com/droberson/ssh-honeypot) -伪造的sshd，用于记录IP地址，用户名和密码.
    - [ssh-honeypot](https://github.com/amv42/sshd-honeypot) -OpenSSH守护程序的修改版本，它将命令转发到Cowrie，在其中解释并返回所有命令.
    - [ssh-honeypotd](https://github.com/sjinks/ssh-honeypotd) -用C编写的低交互SSH蜜罐.
    - [sshForShits](https://github.com/traetox/sshForShits) -高交互SSH蜜罐的框架.
    - [sshesame](https://github.com/jaksi/sshesame) -伪造的SSH服务器，允许所有人登录并记录其活动.
    - [sshhipot](https://github.com/magisterquis/sshhipot) -高交互性MitM SSH蜜罐.
    - [sshlowpot](https://github.com/magisterquis/sshlowpot) -Go中又一个简洁的低交互SSH蜜罐.
    - [sshsyrup](https://github.com/mkishere/sshsyrup) -简单的SSH Honeypot，具有捕获终端活动并上传到asciinema.org的功能.
    - [twisted-honeypots](https://github.com/lanjelot/twisted-honeypots) -基于Twisted的SSH，FTP和Telnet蜜罐.

-分布式传感器项目
    - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)

-pcap分析仪
    - [Honeysnap](https://projects.honeynet.org/honeysnap/)

-网络流量重定向器
    - [Honeywall](https://projects.honeynet.org/honeywall/)

-混合含量的蜜罐分布
    - [HoneyDrive](https://bruteforcelab.com/honeydrive)

-蜜罐传感器
    - [Honeeepi](https://redmine.honeynet.org/projects/honeeepi/wiki) -基于自定义Raspbian操作系统的Raspberry Pi上的Honeypot传感器.

-文件雕刻
    - [TestDisk & PhotoRec](https://www.cgsecurity.org/)

-Win32行为分析工具
    - [Capture BAT](https://www.honeynet.org/node/315)

-现场CD
    - [DAVIX](https://www.secviz.org/node/89) -DAVIX Live CD.

-垃圾邮件陷阱
    - [Mail::SMTP::Honeypot](https://metacpan.org/pod/release/MIKER/Mail-SMTP-Honeypot-0.11/Honeypot.pm) -似乎提供标准SMTP服务器功能的Perl模块.
    - [Mailoney](https://github.com/awhitehatter/mailoney) -SMTP蜜罐，开放中继，用python编写的Cred Harvester.
    - [SendMeSpamIDS.py](https://github.com/johestephan/VerySimpleHoneypot) -简单的SMTP提取所有IDS和分析器.
    - [Shiva](https://github.com/shiva-spampot/shiva) -具有智能沙盒平台的垃圾邮件蜜罐.
        - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)
    - [SpamHAT](https://github.com/miguelraulb/spamhat) -垃圾蜜罐工具.
    - [Spamhole](http://www.spamhole.net/)
    - [honeypot](https://github.com/jadb/honeypot) -项目Honey Pot非官方的PHP SDK.
    - [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)

-商业蜜网
    - [Cymmetria Mazerunner](https://github.com/paralax/awesome-honeypots/blob/master/ttps://cymmetria.com/products/mazerunner/) -引导攻击者远离实际目标并创建攻击足迹.

-服务器（蓝牙）
    - [Bluepot](https://github.com/andrewmichaelsmith/bluepot)

-Android应用程序的动态分析
    - [Droidbox](https://code.google.com/archive/p/droidbox/)

-Dockerized低交互包装
    - [Docker honeynet](https://github.com/sreinhardt/Docker-Honeynet) -为Docker容器设置了几种Honeynet工具.
    - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) -Dockerized [Thug](https://github.com/buffer/thug) 分析恶意Web内容.
    - [Dockerpot](https://github.com/mrschyte/dockerpot) -基于Docker的蜜罐.
    - [Manuka](https://github.com/andrewmichaelsmith/manuka) -基于Docker的蜜罐（Dionaea和Kippo）.
    - [honey_ports](https://github.com/run41/honey_ports) -非常简单但有效的docker部署的蜜罐，用于检测环境中的端口扫描.
    - [mhn-core-docker](https://github.com/MattCarothers/mhn-core-docker) -在Docker中实现的Modern Honey Network的核心元素.
 
-网络分析
    - [Quechua](https://bitbucket.org/zaccone/quechua)

-SIP服务器
    - [Artemnesia VoIP](http://artemisa.sourceforge.net)

-物联网蜜罐
    - [HoneyThing](https://github.com/omererdem/honeything) -TR-069蜜罐.
    - [Kako](https://github.com/darkarnium/kako) -蜜罐，用于解决许多众所周知的已部署的嵌入式设备漏洞.

-蜂蜜令牌
    - [CanaryTokens](https://github.com/thinkst/canarytokens)  -自托管的honeytoken生成器和报告仪表板； 演示版本可在 [CanaryTokens.org](https://canarytokens.org/generate).
    - [Honeybits](https://github.com/0x4D31/honeybits) -一种简单的工具，旨在通过在生产服务器和工作站之间分布面包屑和蜜令牌，以将攻击者引向蜜罐，从而提高陷阱的效率.
    - [Honeyλ (HoneyLambda)](https://github.com/0x4D31/honeylambda) -简单，无服务器的应用程序，旨在在AWS Lambda和Amazon API Gateway之上创建和监视URL蜂蜜令牌.
    - [dcept](https://github.com/secureworks/dcept) -用于部署和检测Active Directory蜜令牌使用的工具.
    - [honeyku](https://github.com/0x4D31/honeyku) -基于Heroku的网络蜜罐，可用于创建和监视伪造的HTTP端点（即蜜罐令牌）.

## Honeyd Tools

-Honeyd插件
    - [Honeycomb](http://www.honeyd.org/tools.php)

-亲爱的观众
    - [Honeyview](http://honeyview.sourceforge.net/)

-Honeyd转MySQL连接器
    - [Honeyd2MySQL](https://bruteforcelab.com/honeyd2mysql)

-可视化Honeyd统计信息的脚本
    - [Honeyd-Viz](https://bruteforcelab.com/honeyd-viz)

-Honeyd统计
    - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)



## Network and Artifact Analysis

-沙盒
    - [Argos](http://www.few.vu.nl/argos/) -捕获零日攻击的模拟器.
    - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    - [Cuckoo](https://cuckoosandbox.org/) -领先的开源自动化恶意软件分析系统.
    - [Pylibemu](https://github.com/buffer/pylibemu) -自由Cython包装器.
    - [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) -在以下基础之上构建的PHP 5.x脚本沙箱 [funcall](https://pecl.php.net/package/funcall).
    - [dorothy2](https://github.com/m4rco-/dorothy2) -用Ruby编写的恶意软件/僵尸网络分析框架.
    - [imalse](https://github.com/hbhzwj/imalse) -集成的MALware模拟器和仿真器.
    - [libemu](https://github.com/buffer/libemu) -Shellcode仿真库，对Shellcode检测很有用.


-沙盒即服务
    - [Hybrid Analysis](https://www.hybrid-analysis.com) -由Payload Security提供支持的免费恶意软件分析服务，该服务使用独特的Hybrid Analysis技术检测和分析未知威胁.
    - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) -在Windows，Android和Mac OS X上分析恶意文件的行为，包括PE，PDF，DOC，PPT，XLS，APK，URL和MachO，以进行可疑活动.
    - [VirusTotal](https://www.virustotal.com/) -分析可疑文件和URL，以检测恶意软件的类型，并自动与安全社区共享它们.
    - [malwr.com](https://malwr.com/) -免费的恶意软件分析服务和社区.

## Data Tools

-前端
    - [DionaeaFR](https://github.com/rubenespadas/DionaeaFR) -前网到Dionaea低互动蜜罐.
    - [Django-kippo](https://github.com/jedie/django-kippo) -用于kippo SSH Honeypot的Django应用.
    - [Shockpot-Frontend](https://github.com/GovCERT-CZ/Shockpot-Frontend) -功能齐全的脚本可直观显示Shockpot蜜罐的统计信息. 
    - [Tango](https://github.com/aplura/Tango) -Splunk的Honeypot Intelligence.
    - [Wordpot-Frontend](https://github.com/GovCERT-CZ/Wordpot-Frontend) -功能齐全的脚本可可视化Wordpot蜜罐中的统计信息.
    - [honeyalarmg2](https://github.com/schmalle/honeyalarmg2) -用于显示蜜罐警报的简化UI.
    - [honeypotDisplay](https://github.com/Joss-Steward/honeypotDisplay) -Flask网站，其中显示了从SSH Honeypot收集的数据. 

-可视化
    - [Acapulco](https://github.com/hgascon/acapulco) -自动攻击社区图构建.
    - [Afterglow Cloud](https://github.com/ayrus/afterglow-cloud)
    - [Afterglow](http://afterglow.sourceforge.net/)
    - [Glastopf Analytics](https://github.com/katkad/Glastopf-Analytics) -简单的蜜罐统计.
    - [HoneyMalt](https://github.com/SneakersInc/HoneyMalt) -用于映射Honeypot系统的Maltego转换.
    - [HoneyMap](https://github.com/fw42/honeymap) -精美的SVG世界地图上的GPS事件的实时websocket流.
    - [HoneyStats](https://sourceforge.net/projects/honeystats/) -在Honeynet上记录的活动的统计视图.
    - [HpfeedsHoneyGraph](https://github.com/yuchincheng/HpfeedsHoneyGraph) -可视化应用程序，以可视化hpfeeds日志.
    - [Kippo stats](https://github.com/mfontani/kippo-stats) -Mojolicious应用，可显示您的kippo SSH蜜罐的统计信息.
    - [Kippo-Graph](https://bruteforcelab.com/kippo-graph) -功能齐全的脚本可直观显示Kippo SSH蜜罐中的统计信息.
    - [The Intelligent HoneyNet](https://github.com/jpyorre/IntelligentHoneyNet) -从蜜罐创建可操作的信息.
    - [ovizart](https://github.com/oguzy/ovizart) -网络流量的可视化分析.

## Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script](https://github.com/andrewmichaelsmith/honeypot-setup-script/)

-部署
    - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) -在EC2实例上设置Dionaea的教程.
    - [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) -基于Raspberry Pi的系统将允许我们维护一个代码库，这将使收集防火墙日志以外的丰富日志变得更加容易.
    - [honeypotpi](https://github.com/free5ty1e/honeypotpi) -将Raspberry Pi变成HoneyPot Pi的脚本.

- 调查报告
    - [Honeypot research papers](https://github.com/shbhmsingh72/Honeypot-Research-Papers) -有关蜜罐的研究论文的PDF.
    - [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) -用于自我传播蠕虫检测和性能分析的行为足迹.
