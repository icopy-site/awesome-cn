<div class="github-widget" data-repo="paralax/awesome-honeypots"></div>
## Awesome Honeypots [![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选蜜罐的精选列表，以及相关组件等等，分为Web，服务等类别，重点关注免费和开源项目.

 每个类别中没有预先建立的项目顺序，该顺序用于贡献.  如果您想贡献，请阅读 [guide](https://github.com/paralax/awesome-honeypots/blob/master/CONTRIBUTING.md).

发现更多精彩的列表 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).



## Related Lists

- [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools) - 在网络流量分析中很有用.
- [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis) - 这里有一些重叠用于人工制品分析

## Honeypots

- 数据库蜜罐
    - [Delilah](https://github.com/SecurityTW/delilah) - 用Python编写的Elasticsearch Honeypot（最初来自Novetta）.
    - [ESPot](https://github.com/mycert/ESPot) - 用NodeJS编写的Elasticsearch蜜罐，捕获每次利用CVE-2014-3120的尝试.
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) - 简单的Elasticsearch蜜罐.
    - [HoneyMysql](https://github.com/xiaoxiaoleo/HoneyMysql) - 简单的Mysql蜜罐项目.
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) -  MongoDB蜜罐代理.
    - [MongoDB-HoneyProxyPy](https://github.com/jwxa2015/MongoDB-HoneyProxyPy) -  python3的MongoDB蜜罐代理.
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - 在NoSQL风格的数据库上构建的蜜罐框架.
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - 用C.编写的低交互MySQL蜜罐.
    - [MysqlPot](https://github.com/schmalle/MysqlPot) -  MySQL蜜罐，还处于早期阶段.
    - [pghoney](https://github.com/betheroot/pghoney) - 低交互Postgres蜜罐.
    - [sticky_elephant](https://github.com/betheroot/sticky_elephant) - 中等互动postgresql蜜罐.

- 网络蜜罐
    - [Bukkit Honeypot](https://github.com/Argomirr/Honeypot) -  Bukkit的Honeypot插件.
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) -  Symfony2表格的蜜罐类型.
    - [Glastopf](https://github.com/mushorg/glastopf) -  Web应用程序蜜罐.
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - 旨在为使用搜索引擎作为攻击资源的黑客工具的攻击者提供侦察.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) -  Laravel应用程序的简单垃圾邮件防护包.
    - [Nodepot](https://github.com/schmalle/Nodepot) -  NodeJS Web应用程序蜜罐.
    - [Servletpot](https://github.com/schmalle/servletpot) -  Web应用程序Honeypot.
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - 用于PHP，Perl和Python应用程序的模块化Web应用程序防火墙/高交互蜜罐.
    - [StrutsHoneypot](https://github.com/Cymmetria/StrutsHoneypot) -  Struts基于Apache 2的蜜罐以及Apache 2服务器的检测模块.
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - 旨在创建欺骗性网页，以欺骗和重定向攻击者远离真实网站.
    - [basic-auth-pot (bap)](https://github.com/bjeborn/basic-auth-pot) -  HTTP基本身份验证蜜罐.
    - [bwpot](https://github.com/graneed/bwpot) - 易碎的Web应用程序honeyPot.
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - 假Django管理员登录屏幕通知管理员未经授权的访问尝试.
    - [drupo](https://github.com/d1str0/drupot) -  Drupal Honeypot.
    - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) - 基于Python的Web服务器honeypot构建器.
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - 简单有效的phpMyAdmin honeypot.
    - [shockpot](https://github.com/threatstream/shockpot) - 用于检测Shell Shock漏洞尝试的WebApp Honeypot.
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) -  PHP脚本演示智能蜜罐.
    -  Snare / Tanner  -  Glastopf的继任者
        - [Snare](https://github.com/mushorg/snare) - 超级下一代高级活性蜜罐.
        - [Tanner](https://github.com/mushorg/tanner) - 评估SNARE事件.
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) - 为垃圾邮件机器人插入陷阱进入响应.
    - [tomcat-manager-honeypot](https://github.com/helospark/tomcat-manager-honeypot)   - 模仿Tomcat管理器端点的蜜罐.  记录请求并保存攻击者的WAR文件以供以后学习
    -  WordPress蜜罐
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) -  WordPress登录蜜罐，用于收集和分析失败的登录尝试.
        - [HoneyPress](https://github.com/dustyfresh/HoneyPress) -  Docker容器中基于Python的WordPress蜜罐.
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - 使用更智能的蜜罐减少垃圾评论的WordPress插件.
        - [wordpot](https://github.com/gbrindisi/wordpot) -  WordPress蜜罐.

- 服务蜜罐
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - 针对英特尔AMT固件漏洞CVE-2017-5689的蜜罐.
    - [Ensnare](https://github.com/ahoernecke/ensnare) - 易于部署Ruby honeypot.
    - [HoneyPy](https://github.com/foospidy/HoneyPy) - 低交互蜜罐.
    - [Honeygrove](https://github.com/UHH-ISS/honeygrove) - 基于Twisted的多功能模块化蜜罐.
    - [Honeyport](https://github.com/securitygeneration/Honeyport) - 用Bash和Python编写的简单honeyport.
    - [Honeyprint](https://github.com/glaslos/honeyprint) - 打印机蜜罐.
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - 现代高交互蜜罐框架.
    - [MICROS honeypot](https://github.com/Cymmetria/micros_honeypot) - 低交互蜜罐，用于检测Oracle Hospitality Applications（MICROS）的Oracle Hospitality Simphony组件中的CVE-2018-2636.
    - [RDPy](https://github.com/citronneur/rdpy) - 用Python实现的Microsoft远程桌面协议（RDP）蜜罐.
    - [SMB Honeypot](https://github.com/r0hi7/HoneySMB) - 高交互SMB服务蜜罐，能够捕获类似于类似恶意软件的恶意软件.
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - 低交互Python蜜罐.
    - [WebLogic honeypot](https://github.com/Cymmetria/weblogic_honeypot) - 低交互蜜罐，用于检测Oracle融合中间件的Oracle WebLogic Server组件中的CVE-2017-10271.
    - [WhiteFace Honeypot](https://github.com/csirtgadgets/csirtg-honeypot) - Twisted based honeypot for WhiteFace.
    - [honeycomb_plugins](https://github.com/Cymmetria/honeycomb_plugins) - Plugin repository for Honeycomb, the honeypot framework by Cymmetria.
    - [honeyntp](https://github.com/fygrave/honeyntp) -  NTP记录器/蜜罐.
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - 观察相机蜜罐.
    - [honeypot-ftp](https://github.com/alexbredo/honeypot-ftp) -  FTP蜜罐.
    - [honeytrap](https://github.com/honeytrap/honeytrap) - 用Go编写的高级Honeypot框架，可与其他蜜罐软件连接.
    - [pyrdp](https://github.com/gosecure/pyrdp) -  RDP man-in-the-middle和Python 3库，能够实时或事后观看连接.
    - [troje](https://github.com/dutchcoders/troje/) - 在单独的LXC容器内运行与服务的每个连接的蜜罐.

- 分布式蜜罐
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - 低交互蜜罐服务器.

- 反蜜罐的东西
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - 攻击组件，检测kippo蜜罐的存在.

-  ICS / SCADA蜜罐
    - [Conpot](https://github.com/mushorg/conpot) -  ICS / SCADA蜜罐.
    - [GasPot](https://github.com/sjhilt/GasPot) -  Veeder Root Gaurdian AST，在石油和天然气行业中很常见.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - 为工业网络构建蜜罐.
    - [gridpot](https://github.com/sk4ld/gridpot) - 用于逼真表现电网蜜网的开源工具.
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - 模仿来自流行PLC的许多服务，更好地帮助SCADA研究人员了解暴露控制系统设备的潜在风险.

- 其他/随机
    - [Damn Simple Honeypot (DSHP)](https://github.com/naorlivne/dshp) - 具有可插拔处理程序的蜜罐框架.
    - [NOVA](https://github.com/DataSoft/Nova) - 使用蜜罐作为探测器，看起来像一个完整的系统.
    - [OpenFlow Honeypot (OFPot)](https://github.com/upa/ofpot) - 将未使用的IP的流量重定向到基于POX构建的蜜罐.
    - [OpenCanary](https://github.com/thinkst/opencanary) - 模块化和分散式蜜罐守护程序，运行多个服务版本的服务，在服务（ab）使用时发出警报.
    - [ciscoasa_honeypot](https://github.com/cymmetria/ciscoasa_honeypot) 用于Cisco ASA组件的低交互蜜罐，能够检测CVE-2018-0101，DoS和远程代码执行漏洞. 
    - [miniprint](https://github.com/sa7mon/miniprint) - 中型交互式打印机蜜罐.

- 僵尸网络C2工具
    - [Hale](https://github.com/pjlantz/Hale) - 僵尸网络命令和控制监视器.
    - [dnsMole](https://code.google.com/archive/p/dns-mole/) - 分析DNS流量并潜在地检测僵尸网络命令和控制服务器活动以及受感染的主机.

-  IPv6攻击检测工具
    - [ipv6-attack-detector](https://github.com/mzweilin/ipv6-attack-detector/) -  Google Summer of Code 2012项目，由Honeynet项目组织提供支持.

- 动态代码检测工具包
    - [Frida](https://www.frida.re) - 注入JavaScript以探索Windows，Mac，Linux，iOS和Android上的本机应用程序.

- 将网站转换为服务器蜜罐的工具
    - [HIHAT](http://hihat.sourceforge.net/) - 将任意PHP应用程序转换为基于Web的高交互Honeypots.

- 恶意软件收集器
    - [Kippo-Malware](https://bruteforcelab.com/kippo-malware) -  Python脚本，将下载存储为Kippo SSH蜜罐数据库中的URL的所有恶意文件.

- 分布式传感器部署
    - [Modern Honey Network](https://github.com/threatstream/mhn) - 多snort和蜜罐传感器管理，使用VM网络，小型SNORT安装，隐身dionaeas和集中式服务器进行管理.

- 网络分析工具
    - [Tracexploit](https://code.google.com/archive/p/tracexploit/) - 重播网络数据包.

- 记录匿名者
    - [LogAnon](http://code.google.com/archive/p/loganon/) - 记录匿名库，帮助匿名日志在日志和网络捕获之间保持一致.

- 低交互蜜罐（路由器后门）
    - [Honeypot-32764](https://github.com/knalli/honeypot-for-tcp-32764) - 路由器后门的蜜罐（TCP 32764）.
    - [WAPot](https://github.com/lcashdol/WAPot) - 可用于观察指向家用路由器的流量的蜜罐.

- 蜜网农场交通重定向器
    - [Honeymole](https://web.archive.org/web/20100326040550/http://www.honeynet.org.pt:80/index.php/HoneyMole) - 部署多个传感器，将流量重定向到集中的蜜罐集合.

-  HTTPS代理
    - [mitmproxy](https://mitmproxy.org/) - 允许拦截，检查，修改和重放流量流.

- 系统仪表
    - [Sysdig](https://sysdig.com/opensource/) - 开源，系统级探索允许从正在运行的GNU / Linux实例捕获系统状态和活动，然后保存，过滤和分析结果.
    - [Fibratus](https://github.com/rabbitstack/fibratus) - 用于探索和跟踪Windows内核的工具.

- 用于USB传播恶意软件的蜜罐
    - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) - 通过USB存储设备传播的恶意软件的蜜罐.

- 数据采集
    - [Kippo2MySQL](https://bruteforcelab.com/kippo2mysql) - 从Kippo基于文本的日志文件中提取一些非常基本的统计信息，并将它们插入MySQL数据库中.
    - [Kippo2ElasticSearch](https://bruteforcelab.com/kippo2elasticsearch) - 用于将数据从Kippo SSH蜜罐MySQL数据库传输到ElasticSearch实例（服务器或集群）的Python脚本.

- 被动网络审计框架解析器
    - [Passive Network Audit Framework (pnaf)](https://github.com/jusafing/pnaf) - 结合多种被动和自动分析技术的框架，以提供对网络平台的安全评估.

-  VM监控和工具
    - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) - 用于创建与VirtualBox一起使用的模板的脚本，以使VM检测更加困难.
    - [VMCloak](https://github.com/hatching/vmcloak) - 为Cuckoo Sandbox自动生成虚拟机和隐藏真实内容.
    - [vmitools](http://libvmi.com/) - 带有Python绑定的C库，可以轻松监视正在运行的虚拟机的底层细节.

- 二进制调试器
    - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) - 用于PIN的调试器后端和LUA包装器.
    - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) - 调试器前端.

- 移动分析工具
    - [Androguard](https://github.com/androguard/androguard) -  Android应用程序的逆向工程，恶意软件和良好软件分析等.
    - [APKinspector](https://github.com/honeynet/apkinspector/) - 强大的GUI工具，供分析师分析Android应用程序.

- 低交互蜜罐
    - [Honeyperl](https://sourceforge.net/projects/honeyperl/) - 基于Perl的蜜罐软件，具有为许多功能开发的插件：wingates，telnet，squid，smtp等.
    - [T-Pot](https://github.com/dtag-dev-sec/tpotce) - 来自电信提供商T-Mobile的一体化蜜罐设备

-  Honeynet数据融合
    - [HFlow2](https://projects.honeynet.org/hflow) - 用于蜜网/网络分析的数据合并工具.

- 服务器
    - [Amun](http://amunhoney.sourceforge.net) - 漏洞仿真蜜罐.
    - [Artillery](https://github.com/trustedsec/artillery/) - 开源蓝色团队工具，旨在通过多种方法保护Linux和Windows操作系统.
    - [Bait and Switch](http://baitnswitch.sourceforge.net) - 将所有恶意流量重定向到蜜罐，该蜜罐部分镜像您的生产系统.
    - [Bifrozt](https://github.com/Ziemeck/bifrozt-ansible) - 使用ansible自动部署bifrozt.
    - [Conpot](http://conpot.org/) - 低交互式服务器端工业控制系统蜜罐.
    - [Heralding](https://github.com/johnnykv/heralding) - 凭据捕获蜜罐.
    - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) - 低交互Python蜜罐，旨在模仿可能被攻击者攻击的服务或端口.
    - [Honeyd](https://github.com/provos/honeyd) - 见 [honeyd tools](#honeyd-tools).
    - [Honeysink](http://www.honeynet.org/node/773) - 开源网络sinkhole，提供检测和防止给定网络上的恶意流量的机制.
    - [Hontel](https://github.com/stamparm/hontel) -  Telnet Honeypot.
    - [KFSensor](http://www.keyfocus.net/kfsensor/) - 基于Windows的蜜罐入侵检测系统（IDS）.
    - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - 接管未使用的IP地址，并创建对蠕虫，黑客和其他互联网居民具有吸引力的虚拟服务器.
    - [MTPot](https://github.com/Cymmetria/MTPot) - 开源Telnet Honeypot，专注于Mirai恶意软件.
    - [SIREN](https://github.com/blaverick62/SIREN) - 半智能HoneyPot网络 -  HoneyNet智能虚拟环境.
    - [TelnetHoney](https://github.com/balte/TelnetHoney) - 简单的telnet蜜罐.
    - [UDPot Honeypot](https://github.com/jekil/UDPot) - 简单的UDP / DNS蜜罐脚本.
    - [Yet Another Fake Honeypot (YAFH)](https://github.com/fnzv/YAFH) - 用Go编写的简单蜜罐.
    - [arctic-swallow](https://github.com/ajackal/arctic-swallow) - 低交互蜜罐.
    - [glutton](https://github.com/mushorg/glutton) - 所有吃蜜罐.
    - [go-HoneyPot](https://github.com/Mojachieee/go-HoneyPot) - 用Go编写的蜜罐服务器.
    - [go-emulators](https://github.com/kingtuna/go-emulators) - 蜜罐Golang模拟器.
    - [honeymail](https://github.com/sec51/honeymail) - 用Golang编写的SMTP蜜罐.
    - [honeytrap](https://github.com/tillmannw/honeytrap) - 低交互蜜罐和网络安全工具，用于捕获针对TCP和UDP服务的攻击.
    - [imap-honey](https://github.com/yvesago/imap-honey) - 用Golang编写的IMAP蜜罐.
    - [mwcollectd](https://www.openhub.net/p/mwcollectd) - 多功能恶意软件收集守护程序，结合了猪笼草和蜜蜂的最佳功能.
    - [potd](https://github.com/lnslbrty/potd) - 高度可扩展的低到中交互SSH / TCP蜜罐，专为OpenWrt / IoT设备而设计，利用多种Linux内核功能，如命名空间，seccomp和线程功能.
    - [portlurker](https://github.com/bartnv/portlurker) -  Rust中的端口侦听器，具有协议猜测和安全字符串显示.
    - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) - 简单的低交互端口监控蜜罐.
    - [telnet-iot-honeypot](https://github.com/Phype/telnet-iot-honeypot) - 用于捕获僵尸网络二进制文件的Python telnet蜜罐.
    - [telnetlogger](https://github.com/robertdavidgraham/telnetlogger) - 用于跟踪Mirai僵尸网络的Telnet蜜罐.
    - [vnclowpot](https://github.com/magisterquis/vnclowpot) - 低交互VNC蜜罐.


-  IDS签名生成
    - [Honeycomb](http://www.icir.org/christian/honeycomb/) - 使用蜜罐自动创建签名.

-  AS号码和前缀的查询服务
    - [CC2ASN](http://www.cc2asn.com/) - 针对属于世界上任何给定国家的AS号码和前缀的简单查找服务.

- 数据收集/数据共享
    - [HPfriends](http://hpfriends.honeycloud.net/#/home) - 蜜罐数据共享平台.
        - [hpfriends - real-time social data-sharing](https://heipei.io/sigint-hpfriends/) - 关于HPFriends饲料系统的介绍 
    - [HPFeeds](https://github.com/rep/hpfeeds/) - 轻量级认证的发布 - 订阅协议.

- 中央管理工具
    - [PHARM](http://www.nepenthespharm.com/) - 管理，报告和分析分布式Nepenthes实例.

- 网络连接分析仪
    - [Impost](http://impost.sourceforge.net/) - 网络安全审计工具，旨在分析受感染和/或易受攻击的守护进程背后的取证. 

- 蜜罐部署
    - [Modern Honeynet Network](http://threatstream.github.io/mhn/) - 简化安全蜜罐的部署和管理.

-  Wireshark的蜜罐扩展
    - [Whireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - 使用Wireshark对数据包捕获文件应用Snort IDS规则和签名.


- 客户
    - [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
    - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    - [Capture-HPC-NG](https://github.com/CERT-Polska/HSN-Capture-HPC-NG)
    - [Capture-HPC](https://projects.honeynet.org/capture-hpc) - 高交互客户端蜜罐（也称为honeyclient）.
    - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    - [HoneyC](https://projects.honeynet.org/honeyc)
    - [HoneySpider Network](https://github.com/CERT-Polska/hsn2-bundle) - 高度可扩展的系统，集成多个客户端蜜罐，以检测恶意网站.
    - [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/) - 创建Web界面以管理和远程共享Honeyclients资源. 
    - [Jsunpack-n](https://github.com/urule99/jsunpack-n)
    - [MonkeySpider](http://monkeyspider.sourceforge.net)
    - [PhoneyC](https://github.com/honeynet/phoneyc) -  Python honeyclient（后来被Thug取代）.
    - [Pwnypot](https://github.com/shjalayeri/pwnypot) - 高互动客户蜜罐.
    - [Rumal](https://github.com/thugs-rumal/) - 暴徒的Rumāl：暴徒的衣服和武器.
    - [Shelia](https://www.cs.vu.nl/~herbertb/misc/shelia/) - 用于攻击检测的客户端蜜罐.
    - [Thug](https://buffer.github.io/thug/) - 基于Python的低交互式honeyclient.
    - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)
    - [Trigona](https://www.honeynet.org/project/Trigona)
    - [URLQuery](https://urlquery.net/)
    - [YALIH (Yet Another Low Interaction Honeyclient)](https://github.com/Masood-M/yalih) - 低交互客户端蜜罐，旨在通过签名，异常和模式匹配技术检测恶意网站.

- 蜜罐
    - [Deception Toolkit](http://www.all.net/dtk/dtk.html)
    - [IMHoneypot](https://github.com/mushorg/imhoneypot)

-  PDF文件检查员
    - [peepdf](https://github.com/jesparza/peepdf) - 功能强大的Python工具，用于分析PDF文档.

- 混合低/高交互蜜罐
    - [HoneyBrid](http://honeybrid.sourceforge.net)

-  SSH蜜罐
    - [Blacknet](https://github.com/morian/blacknet) - 多头SSH蜜罐系统.
    - [Cowrie](https://github.com/cowrie/cowrie) -  Cowrie SSH Honeypot（基于kippo）.
    - [DShield docker](https://github.com/xme/dshield-docker) - 启用了DShield输出的Docker容器运行cowrie.
    - [HonSSH](https://github.com/tnich/honssh) - 记录客户端和服务器之间的所有SSH通信.
    - [HUDINX](https://github.com/Cryptix720/HUDINX) - 微型交互SSH蜜罐，用Python编写，用于记录暴力攻击，最重要的是，攻击者执行的整个shell交互.
    - [Kippo](https://github.com/desaster/kippo) - 中等交互SSH蜜罐.
    - [Kippo_JunOS](https://github.com/gregcmartin/Kippo_JunOS) -  Kippo配置为后门屏幕.
    - [Kojoney2](https://github.com/madirish/kojoney2) - 使用Python编写的低交互式SSH蜜罐，基于Kojoney的Jose Antonio Coret.
    - [Kojoney](http://kojoney.sourceforge.net/) - 基于Python的低交互蜜罐，模拟使用Twisted Conch实现的SSH服务器.
    - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - 分析SSH蜜罐日志.
    - [Malbait](https://github.com/batchmcnulty/Malbait) - 在Perl中实现的简单TCP / UDP蜜罐.
    - [MockSSH](https://github.com/ncouture/MockSSH) - 模拟SSH服务器并定义它​​支持的所有命令（Python，Twisted）.
    - [cowrie2neo](https://github.com/xlfe/cowrie2neo) - 解析cowrie honeypot登录到neo4j数据库.
    - [go-sshoney](https://github.com/ashmckenzie/go-sshoney) -  SSH Honeypot.
    - [go0r](https://github.com/fzerorubigd/go0r) -  Golang中的简单ssh蜜罐.
    - [gohoney](https://github.com/PaulMaddox/gohoney) - 用Go编写的SSH蜜罐.
    - [hived](https://github.com/sahilm/hived) - 基于Golang  - 蜜罐.
    - [hnypots-agent)](https://github.com/joshrendek/hnypots-agent) -  Go中的SSH服务器记录用户名和密码组合.
    - [honeypot.go](https://github.com/mdp/honeypot.go) - 用Go编写的SSH Honeypot.
    - [honeyssh](https://github.com/ppacher/honeyssh) - 凭据统计信息转储SSH蜜罐的凭据.
    - [hornet](https://github.com/czardoz/hornet) - 中等交互支持多个虚拟主机的SSH蜜罐.
    - [ssh-auth-logger](https://github.com/JustinAzoff/ssh-auth-logger) - 低/零交互SSH身份验证日志记录蜜罐.
    - [ssh-honeypot](https://github.com/droberson/ssh-honeypot) - 伪造sshd，记录IP地址，用户名和密码.
    - [ssh-honeypot](https://github.com/amv42/sshd-honeypot) -  OpenSSH守护程序的修改版本，它将命令转发给Cowrie，其中所有命令都被解释并返回.
    - [ssh-honeypotd](https://github.com/sjinks/ssh-honeypotd) - 用C编写的低交互式SSH蜜罐.
    - [sshForShits](https://github.com/traetox/sshForShits) - 高度交互SSH蜜罐的框架.
    - [sshesame](https://github.com/jaksi/sshesame) - 假SSH服务器，允许每个人进入并记录他们的活动.
    - [sshhipot](https://github.com/magisterquis/sshhipot) - 高交互性MitM SSH蜜罐.
    - [sshlowpot](https://github.com/magisterquis/sshlowpot) -  Go中又一个简洁的低交互式SSH蜜罐.
    - [sshsyrup](https://github.com/mkishere/sshsyrup) - 简单的SSH Honeypot，具有捕获终端活动和上传到asciinema.org的功能.
    - [twisted-honeypots](https://github.com/lanjelot/twisted-honeypots) - 基于Twisted的SSH，FTP和Telnet蜜罐.

- 分布式传感器项目
    - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)

- 一台pcap分析仪
    - [Honeysnap](https://projects.honeynet.org/honeysnap/)

- 网络流量重定向器
    - [Honeywall](https://projects.honeynet.org/honeywall/)

- 具有混合内容的蜜罐分布
    - [HoneyDrive](https://bruteforcelab.com/honeydrive)

- 蜜罐传感器
    - [Honeeepi](https://redmine.honeynet.org/projects/honeeepi/wiki) - 基于定制Raspbian OS的Raspberry Pi上的蜜罐传感器.

- 文件雕刻
    - [TestDisk & PhotoRec](https://www.cgsecurity.org/)

-  win32的行为分析工具
    - [Capture BAT](https://www.honeynet.org/node/315)

-  Live CD
    - [DAVIX](https://www.secviz.org/node/89) -  DAVIX Live CD.

-  Spamtrap
    - [Mail::SMTP::Honeypot](https://metacpan.org/pod/release/MIKER/Mail-SMTP-Honeypot-0.11/Honeypot.pm) -  Perl模块似乎提供标准SMTP服务器的功能.
    - [Mailoney](https://github.com/awhitehatter/mailoney) -  SMTP蜜罐，Open Relay，用Python编写的Cred Harvester.
    - [SendMeSpamIDS.py](https://github.com/johestephan/VerySimpleHoneypot) - 简单的SMTP获取所有IDS和分析器.
    - [Shiva](https://github.com/shiva-spampot/shiva) - 使用智能沙盒平台的垃圾邮件蜜罐.
        - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)
    - [SpamHAT](https://github.com/miguelraulb/spamhat) - 垃圾邮件蜜罐工具.
    - [Spamhole](http://www.spamhole.net/)
    - [honeypot](https://github.com/jadb/honeypot) -  Project Honey Pot非官方PHP SDK.
    - [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)

- 商业蜜网
    - [Cymmetria Mazerunner](https://github.com/paralax/awesome-honeypots/blob/master/ttps://cymmetria.com/products/mazerunner/) - 使攻击者远离真实目标并创建攻击的足迹.

- 服务器（蓝牙）
    - [Bluepot](https://github.com/andrewmichaelsmith/bluepot)

-  Android应用程序的动态分析
    - [Droidbox](https://code.google.com/archive/p/droidbox/)

-  Dockerized Low Interaction包装
    - [Docker honeynet](https://github.com/sreinhardt/Docker-Honeynet) - 为Docker容器设置了几个Honeynet工具.
    - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) -  Dockerized [Thug](https://github.com/buffer/thug) 分析恶意Web内容.
    - [Dockerpot](https://github.com/mrschyte/dockerpot) - 基于Docker的蜜罐.
    - [Manuka](https://github.com/andrewmichaelsmith/manuka) - 基于Docker的蜜罐（Dionaea和Kippo）.
    - [mhn-core-docker](https://github.com/MattCarothers/mhn-core-docker) - 在Docker中实现的现代蜂蜜网络的核心元素.

- 网络分析
    - [Quechua](https://bitbucket.org/zaccone/quechua)

-  SIP服务器
    - [Artemnesia VoIP](http://artemisa.sourceforge.net)

- 物联网蜜罐
    - [HoneyThing](https://github.com/omererdem/honeything) -  TR-069蜜罐.
    - [Kako](https://github.com/darkarnium/kako) - 许多众所周知和部署的嵌入式设备漏洞的蜜罐.

-  Honeytokens
    - [CanaryTokens](https://github.com/thinkst/canarytokens)   - 自助式蜜语发电机和报告仪表板;  演示版可在 [CanaryTokens.org](https://canarytokens.org/generate).
    - [Honeybits](https://github.com/0x4D31/honeybits) - 简单的工具，旨在通过在生产服务器和工作站上传播面包屑和蜜蜂来增强陷阱的有效性，以吸引攻击者前往您的蜜罐.
    - [Honeyλ (HoneyLambda)](https://github.com/0x4D31/honeylambda) - 简单的无服务器应用程序，用于在AWS Lambda和Amazon API Gateway之上创建和监控URL honeytokens.
    - [dcept](https://github.com/secureworks/dcept) - 用于部署和检测Active Directory蜜蜂使用的工具.
    - [honeyku](https://github.com/0x4D31/honeyku) - 基于Heroku的web蜜罐，可用于创建和监控虚假的HTTP端点（即honeytokens）.

## Honeyd Tools

-  Honeyd插件
    - [Honeycomb](http://www.honeyd.org/tools.php)

-  Honeyd观众
    - [Honeyview](http://honeyview.sourceforge.net/)

-  Honeyd到MySQL连接器
    - [Honeyd2MySQL](https://bruteforcelab.com/honeyd2mysql)

- 一个可以从honeyd可视化统计信息的脚本
    - [Honeyd-Viz](https://bruteforcelab.com/honeyd-viz)

-  Honeyd统计数据
    - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)



## Network and Artifact Analysis

- 沙盒
    - [Argos](http://www.few.vu.nl/argos/) - 用于捕获零日攻击的模拟器.
    - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    - [Cuckoo](https://cuckoosandbox.org/) - 领先的开源自动恶意软件分析系统.
    - [Pylibemu](https://github.com/buffer/pylibemu) - 自由用Cython包装.
    - [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) - PHP 5.x script sandbox built on top of [funcall](https://pecl.php.net/package/funcall).
    - [dorothy2](https://github.com/m4rco-/dorothy2) - 用Ruby编写的恶意软件/僵尸网络分析框架.
    - [imalse](https://github.com/hbhzwj/imalse) - 集成的MALware模拟器和仿真器.
    - [libemu](https://github.com/buffer/libemu) -  Shellcode仿真库，对shellcode检测很有用.


- 沙盒即服务
    - [Hybrid Analysis](https://www.hybrid-analysis.com) - 由Payload Security提供支持的免费恶意软件分析服务，可使用独特的混合分析技术检测和分析未知威胁.
    - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - 分析Windows，Android和Mac OS X上的恶意文件（包括PE，PDF，DOC，PPT，XLS，APK，URL和MachO）的可疑活动行为.
    - [VirusTotal](https://www.virustotal.com/) - 分析可疑文件和URL以检测恶意软件类型，并自动与安全社区共享.
    - [malwr.com](https://malwr.com/) - 免费的恶意软件分析服务和社区.

## Data Tools

- 前端
    - [DionaeaFR](https://github.com/rubenespadas/DionaeaFR) - 前网到Dionaea低交互蜜罐.
    - [Django-kippo](https://github.com/jedie/django-kippo) - 用于kippo SSH Honeypot的Django应用程序.
    - [Shockpot-Frontend](https://github.com/GovCERT-CZ/Shockpot-Frontend) - 全功能脚本，可以显示来自Shockpot蜜罐的统计数据. 
    - [Tango](https://github.com/aplura/Tango) - 与Splunk的蜜罐情报.
    - [Wordpot-Frontend](https://github.com/GovCERT-CZ/Wordpot-Frontend) - 全功能脚本，可以显示Wordpot蜜罐中的统计信息.
    - [honeyalarmg2](https://github.com/schmalle/honeyalarmg2) - 用于显示蜜罐警报的简化UI.
    - [honeypotDisplay](https://github.com/Joss-Steward/honeypotDisplay) -  Flask网站，显示从SSH Honeypot收集的数据. 

- 可视化
    - [Acapulco](https://github.com/hgascon/acapulco) - 自动攻击社区图构建.
    - [Afterglow Cloud](https://github.com/ayrus/afterglow-cloud)
    - [Afterglow](http://afterglow.sourceforge.net/)
    - [Glastopf Analytics](https://github.com/katkad/Glastopf-Analytics) - 简单的蜜罐统计.
    - [HoneyMalt](https://github.com/SneakersInc/HoneyMalt) -  Maltego转型用于映射蜜罐系统.
    - [HoneyMap](https://github.com/fw42/honeymap) - 花式SVG世界地图上的GPS事件的实时websocket流.
    - [HoneyStats](https://sourceforge.net/projects/honeystats/) - 蜜网上记录的活动的统计视图.
    - [HpfeedsHoneyGraph](https://github.com/yuchincheng/HpfeedsHoneyGraph) - 可视化应用程序可视化hpfeeds日志.
    - [Kippo stats](https://github.com/mfontani/kippo-stats) -  Mojolicious应用程序显示您的kippo SSH蜜罐的统计信息.
    - [Kippo-Graph](https://bruteforcelab.com/kippo-graph) - 全功能脚本，可以显示Kippo SSH蜜罐中的统计信息.
    - [The Intelligent HoneyNet](https://github.com/jpyorre/IntelligentHoneyNet) - 从蜜罐中创建可操作的信息.
    - [ovizart](https://github.com/oguzy/ovizart) - 网络流量的可视化分析.

## Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script](https://github.com/andrewmichaelsmith/honeypot-setup-script/)

- 部署
    - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - 关于在EC2实例上设置Dionaea的教程.
    - [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) - 基于Raspberry Pi的系统将允许我们维护一个代码库，以便更容易收集防火墙日志之外的丰富日志.
    - [honeypotpi](https://github.com/free5ty1e/honeypotpi) - 将Raspberry Pi转变为HoneyPot Pi的脚本.

- 调查报告
    - [Honeypot research papers](https://github.com/shbhmsingh72/Honeypot-Research-Papers) - 关于蜜罐的研究论文的PDF.
    - [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - 用于自我传播的蠕虫检测和分析的行为足迹.
