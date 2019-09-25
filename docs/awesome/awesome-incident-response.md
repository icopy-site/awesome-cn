<div class="github-widget" data-repo="meirwah/awesome-incident-response"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Incident Response [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的安全事件响应工具和资源列表，旨在帮助安全分析人员和 [DFIR](http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-%28DFIR%29.html) 团队.

数字取证和事件响应（DFIR）团队是组织中的一组人员，负责管理对安全事件的响应，包括收集事件的证据，补救其影响以及实施控制措施以防止将来再次发生该事件.



## IR tools Collection

### Adversary Emulation

* [APTSimulator](https://github.com/NextronSystems/APTSimulator) -Windows Batch脚本，该脚本使用一组工具和输出文件来使系统看起来好像已受到威胁.
* [Atomic Red Team (ART)](https://github.com/redcanaryco/atomic-red-team) -映射到Mitre ATT＆CK框架的小型且高度便携的检测测试.
* [AutoTTP](https://github.com/jymcheong/AutoTTP)  -自动化战术技术与程序.  手动重新运行复杂序列以进行回归测试，产品评估，并为研究人员生成数据.
* [Blue Team Training Toolkit (BT3)](https://www.bt3.no/) -用于防御性安全培训的软件，它将使您的网络分析培训课程，事件响应演练和红色团队参与度提高到一个新的水平.
* [Caldera](https://github.com/mitre/caldera)  -自动化的对手仿真系统，可在Windows Enterprise网络内执行攻击后的对手行为.  它在运行过程中使用规划系统和基于对抗策略，技术和常识（ATT＆CK™）项目的预先配置的对抗模型来生成计划.
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire)  -模块化，菜单驱动的跨平台工具，用于构建可重复的，延迟的，分布式的安全事件.  轻松为Blue Team演习和传感器/警报映射创建自定义事件链.  红队可以制造诱饵事件，分散注意力和吸引人，以支持和扩大其行动.
* [Metta](https://github.com/uber-common/metta) -进行对抗模拟的信息安全准备工具.
* [Network Flight Simulator](https://github.com/alphasoc/flightsim) -轻量级实用程序，用于生成恶意网络流量，并帮助安全团队评估安全控制和网络可见性.
* [Red Team Automation (RTA)](https://github.com/endgameinc/RTA) -RTA提供了一个脚本框架，旨在使蓝队可以根据MITER ATT＆CK进行建模，以针对恶意贸易工具测试其检测功能.
* [RedHunt-OS](https://github.com/redhuntlabs/RedHunt-OS) -用于对手仿真和威胁搜寻的虚拟机.

### All in one Tools

* [Belkasoft Evidence Center](https://belkasoft.com/ec) -该工具包将通过分析硬盘驱动器，驱动器映像，内存转储，iOS，Blackberry和Android备份，UFED，JTAG和碎片转储来快速从多个来源提取数字证据.
* [CimSweep](https://github.com/PowerShellMafia/CimSweep) -基于CIM / WMI的工具套件，使您能够跨所有版本的Windows远程执行事件响应和搜寻操作.
* [CIRTkit](https://github.com/byt3smith/CIRTKit) -CIRTKit不仅是工具的集合，而且还是有助于持续统一事件响应和取证调查过程的框架.
* [Cyber Triage](http://www.cybertriage.com)  -Cyber​​ Triage可以远程收集和分析端点数据，以帮助确定是否受到威胁.  它采用无代理方式，并专注于易用性和自动化，因此公司无需大型基础架构变更和法医专家团队即可做出响应.  其结果用于确定系统是否应删除或进一步调查.
* [Digital Forensics Framework](http://www.arxsys.fr/discover/)  -建立在专用应用程序编程接口（API）之上的开源计算机取证平台.  DFF提出了一种替代当今使用的老化数字取证解决方案的方案.  DFF界面专为简单易用和自动化而设计，可指导用户完成数字调查的主要步骤，因此专业人士和非专家均可使用它快速，轻松地进行数字调查并执行事件响应.
* [Doorman](https://github.com/mwielgoszewski/doorman)  -osquery队列管理器，允许远程管理节点检索的osquery配置.  它利用osquery的TLS配置，记录器和分布式读写端点的优势，以最小的开销和侵入性为管理员提供跨一组设备的可见性.
* [Envdb](https://github.com/mephux/envdb)  -Envdb将您的生产，开发，云等环境转换为数据库集群，您可以使用osquery作为基础进行搜索.  它使用（集群）节点代理包装osquery进程，该代理可以通信回中央位置.
* [Falcon Orchestrator](https://github.com/CrowdStrike/falcon-orchestrator) -基于Windows的可扩展应用程序，提供工作流自动化，案例管理和安全响应功能.
* [GRR Rapid Response](https://github.com/google/grr)  -针对远程现场取证的事件响应框架.  它由安装在目标系统上的python代理（客户端）以及可以管理代理并与之通信的python服务器基础结构组成.
* [Kolide Fleet](https://kolide.com/fleet)  -为安全专家量身定制的最先进的主机监控平台.  利用Facebook经过考验的osquery项目，Kolide可以为重大问题提供快速答案.
* [Limacharlie](https://github.com/refractionpoint/limacharlie) -由一系列小项目组成的端点安全平台，这些小项目都协同工作，为您提供跨平台（Windows，OSX，Linux，Android和iOS）低级环境，用于管理其他模块并将其推入内存以扩展其功能.
* [Mozilla Investigator (MIG)](http://mig.mozilla.org/)  -在远程端点上执行调查性手术的平台.  它使调查人员可以并行地从大量系统中获取信息，从而加快事件调查和日常操作安全性.
* [MozDef](https://github.com/mozilla/MozDef) -自动执行安全事件处理流程，并促进事件处理程序的实时活动.
* [nightHawk](https://github.com/biggiesmallsAG/nightHawkResponse)  -使用ElasticSearch作为后端为异步取证数据表示而构建的应用程序.  它旨在吸收Redline集合.
* [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/)  -另一个流行的分布式开源计算机取证框架.  该框架建立在Linux平台上，并使用postgreSQL数据库存储数据.
* [osquery](https://osquery.io/) - Easily ask questions about your Linux and macOS infrastructure using a SQL-like query language; the provided *incident-response pack* helps you detect and respond to breaches.
* [Redline](https://www.fireeye.com/services/freeware/redline.html) -为主机提供调查功能，以便用户通过内存和文件分析以及制定威胁评估配置文件来查找恶意活动的迹象.
* [The Sleuth Kit & Autopsy](http://www.sleuthkit.org)  -基于Unix和Windows的工具，可帮助对计算机进行取证分析.  它带有各种有助于数字取证的工具.  这些工具有助于分析磁盘映像，执行文件系统的深入分析以及其他各种操作.
* [TheHive](https://thehive-project.org/) -可扩展的三合一开源和免费解决方案，旨在使SOC，CSIRT，CERT和任何需要快速调查并采取行动的安全事件的信息安全从业人员，更加轻松.
* [X-Ways Forensics](http://www.x-ways.net/forensics/)  -用于磁盘克隆和映像的取证工具.  它可用于查找已删除的文件和磁盘分析.
* [Zentral](https://github.com/zentralopensource/zentral)  -将osquery强大的端点清单功能与灵活的通知和操作框架相结合.  这使人们能够识别OS X和Linux客户端上的更改并对更改做出反应.

### Books

* [DFIR intro](https://medium.com/@sroberts/introduction-to-dfir-d35d5de4c180/) -Scott J. Roberts着.
* [The Practice of Network Security Monitoring: Understanding Incident Detection and Response](http://www.amazon.com/gp/product/1593275099) -理查德·贝特里奇（Richard Bejtlich）关于IR的书.

### Communities

* [augmentd](http://augmentd.co/) -社区驱动的站点，提供可在各种常见安全工具中实施和执行的搜索列表.
* [Sans DFIR mailing list](https://lists.sans.org/mailman/listinfo/dfir) -SANS的DFIR邮件列表.
* [Slack DFIR channel](https://dfircommunity.slack.com) -松弛的DFIR社区频道- [Signup here](https://rishi28.typeform.com/to/sTbTI8).

### Disk Image Creation Tools

* [AccessData FTK Imager](http://accessdata.com/product-download/?/support/adownloads#FTKImager)  -取证工具，其主要目的是预览任何类型的磁盘中的可恢复数据.  FTK Imager还可以在32位和64位系统上获取实时内存和页面文件.
* [Bitscout](https://github.com/vitaly-kamluk/bitscout)  -Vitaly Kamluk的Bitscout可帮助您构建完全可信的可定制LiveCD / LiveUSB映像，以用于远程数字取证（或您选择的任何其他任务）.  它的意思是透明的，可由系统所有者监视，取证声音，可自定义和紧凑.
* [GetData Forensic Imager](http://www.forensicimager.com/) -基于Windows的程序，将以以下常见的取证文件格式之一获取，转换或验证取证图像.
* [Guymager](http://guymager.sourceforge.net) -免费的取证成像器，用于在Linux上进行媒体获取.
* [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) -Magnet Forensics的ACQUIRE允许在Windows，Linux和OS X以及移动操作系统上执行各种类型的磁盘获取.

### Evidence Collection

* [bulk_extractor](https://github.com/simsong/bulk_extractor)  -计算机取证工具，可扫描磁盘映像，文件或文件目录并提取有用的信息，而无需解析文件系统或文件系统结构.  由于忽略了文件系统结构，因此该程序在速度和完整性方面与众不同.
* [Cold Disk Quick Response](https://github.com/rough007/CDQR) -简化的解析器列表，可快速分析法医图像文件（“ dd”，E01，“.vmdk”等）并输出九份报告.
* [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -Windows Batch脚本和Unix Bash脚本，可在事件响应期间全面收集主机取证数据.
* [Live Response Collection](https://www.brimorlabs.com/tools/) -自动化工具，可从Windows，OSX和基于* nix的操作系统收集易失性数据.
* [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) -命令行实用程序（可与或不与Amazon EC2实例一起使用）并行化远程内存获取.

### Incident Management

* [CyberCPR](https://www.cybercpr.com) -内置了“需要知道”功能的社区和商业事件管理工具，可在处理敏感事件时支持GDPR合规性.
* [Cyphon](https://www.cyphon.io/)  -Cyphon通过一个平台简化了许多相关任务，从而消除了事件管理的麻烦.  它接收，处理和分类事件，为您的分析工作流提供全方位的解决方案-汇总数据，捆绑警报并对其进行优先级排序，并赋予分析人员调查和记录事件的能力.
* [Demisto](https://www.demisto.com/product/) -Demisto社区版（免费）提供完整的事件生命周期管理，事件关闭报告，团队分配和协作以及许多集成，以增强自动化（例如Active Directory，PagerDuty，Jira等）.
* [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR/)  -网络安全事件管理平台的设计考虑了敏捷性和速度.  它可以轻松创建，跟踪和报告网络安全事件，对于CSIRT，CERT和SOC都非常有用.
* [RTIR](https://www.bestpractical.com/rtir/)  -事件响应请求跟踪器（RTIR）是针对计算机安全团队的首要开源事件处理系统.  我们与世界各地的十几个CERT和CSIRT团队合作，帮助您处理事件报告的数量不断增加.  RTIR建立在Request Tracker的所有功能之上.
* [Sandia Cyber Omni Tracker (SCOT)](http://getscot.sandia.gov/)  -事件响应协作和知识捕获工具专注于灵活性和易用性.  我们的目标是在不给用户造成负担的情况下为事件响应流程增加价值.
* [threat_note](https://github.com/defpoint/threat_note) -轻巧的调查笔记本，可让安全研究人员注册和检索与其研究相关的指标.

### Linux Distributions

* [The Appliance for Digital Investigation and Analysis (ADIA)](https://forensics.cert.org/#ADIA)  -用于数字调查和获取的基于VMware的设备，完全基于公共领域的软件构建.  ADIA中包含的工具包括尸检，侦探工具包，数字取证框架，log2timeline，Xplico和Wireshark.  大多数系统维护使用Webmin.  它设计用于中小型数字调查和获取.  该设备可在Linux，Windows和Mac OS上运行.  i386（32位）和x86_64（64位）版本均可用.
* [Computer Aided Investigative Environment (CAINE)](http://www.caine-live.net/index.html) -包含许多工具，可帮助调查人员进行分析，包括法医证据收集.
* [CCF-VM](https://github.com/rough007/CCF-VM) -CyLR CDQR取证虚拟机（CCF-VM）：一种用于解析收集的数据的多合一解决方案，使其可以通过内置的常用搜索轻松地进行搜索，并且可以同时搜索单个和多个主机.
* [Digital Evidence & Forensics Toolkit (DEFT)](http://www.deftlinux.net/)  -用于计算机取证证据的Linux发行版.  它与Windows的Digital Advanced Response工具包（DART）捆绑在一起.  还提供了DEFT的轻型版本，称为DEFT Zero，其主要侧重于法医上合理的证据收集.
* [NST - Network Security Toolkit](https://sourceforge.net/projects/nst/files/latest/download?source=files) -Linux发行版，其中包含大量对网络安全专业人员有用的同类最佳的开源网络安全应用程序.
* [PALADIN](https://sumuri.com/software/paladin/)  -修改后的Linux发行版，以法医合理的方式执行各种法医任务.  它包含许多开放源代码取证工具.
* [Security Onion](https://github.com/Security-Onion-Solutions/security-onion) -专门用于网络安全监视的Linux发行版，具有高级分析工具.
* [SANS Investigative Forensic Toolkit (SIFT) Workstation](http://digital-forensics.sans.org/community/downloads) - Demonstrates that advanced incident response capabilities and deep dive digital forensic techniques to intrusions can be accomplished using cutting-edge open-source tools that are freely available and frequently updated.

### Linux Evidence Collection

* [FastIR Collector Linux](https://github.com/SekoiaLab/Fastir_Collector_Linux) -适用于Linux的FastIR在实时Linux上收集不同的工件，并将结果记录在csv文件中.

### Log Analysis Tools

* [Kaspersky CyberTrace](https://support.kaspersky.com/13850)  -威胁情报融合和分析工具，可将威胁数据源与SIEM解决方案集成在一起.  用户可以在其现有安全操作的工作流程中立即将威胁情报用于安全监控和事件报告（IR）活动.
* [Lorg](https://github.com/jensvoid/lorg) -用于高级HTTPD日志文件安全性分析和取证的工具.
* [Logdissect](https://github.com/dogoncouch/logdissect) -CLI工具和Python API，用于分析日志文件和其他数据.
* [StreamAlert](https://github.com/airbnb/streamalert) -无服务器实时日志数据分析框架，能够提取自定义数据源并使用用户定义的逻辑触发警报.
* [SysmonSearch](https://github.com/JPCERTCC/SysmonSearch) -SysmonSearch通过聚集事件日志，使Windows事件日志分析更有效且耗时更少.

### Memory Analysis Tools

* [Evolve](https://github.com/JamesHabben/evolve) -易失性存储器取证框架的Web界面.
* [inVtero.net](https://github.com/ShaneK2/inVtero.net) -带有嵌套虚拟机管理程序支持的Windows x64高级内存分析.
* [KnTList](http://www.gmgsystemsinc.com/knttools/) -计算机内存分析工具.
* [LiME](https://github.com/504ensicsLabs/LiME) 可加载内核模块（LKM），允许从Linux和基于Linux的设备（以前称为DMD）中获取易失性内存.
* [Memoryze](https://www.fireeye.com/services/freeware/memoryze.html)  -免费的内存取证软件，可帮助事件响应者在实时内存中发现恶意.  Memoryze可以获取和/或分析内存映像，并且在实时系统上可以将分页文件包括在其分析中.
* [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze-for-the-mac.html)  -Mac版Memoryze是Memoryze，但Mac版则是.  但是，功能数量较少.
* [Rekall](http://www.rekall-forensic.com/) -开源工具（和库），用于从易失性存储器（RAM）样本中提取数字伪像.
* [Responder PRO](http://www.countertack.com/responder-pro) -Responder PRO是行业标准的物理内存和自动化恶意软件分析解决方案.
* [Volatility](https://github.com/volatilityfoundation/volatility) -高级内存取证框架.
* [VolatilityBot](https://github.com/mkorman90/VolatilityBot) -用于研究人员的自动化工具可将所有猜测工作和手动任务从二进制提取阶段中消除，或帮助研究人员进行内存分析研究的第一步.
* [VolDiff](https://github.com/aim4r/VolDiff) -基于波动率的恶意软件内存足迹分析.
* [WindowsSCOPE](http://www.windowsscope.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=35&category_id=3&option=com_virtuemart) -用于分析易失性内存的内存取证和反向工程工具，可以分析Windows内核，驱动程序，DLL，虚拟和物理内存.

### Memory Imaging Tools

* [Linux Memory Grabber](https://github.com/halpomeranz/lmg/) -用于转储Linux内存和创建Volatility配置文件的脚本.
* [Magnet RAM Capture](https://www.magnetforensics.com/free-tool-magnet-ram-capture/)  -免费的成像工具，旨在捕获犯罪嫌疑人计算机的物理内存.  支持Windows的最新版本.
* [OSForensics](http://www.osforensics.com/)  -在32位和64位系统上获取实时内存的工具.  可以完成单个进程的内存空间转储或物理内存转储.

### OSX Evidence Collection

* [Knockknock](https://github.com/synack/knockknock) -显示设置为在OSX上自动执行的持久项（脚本，命令，二进制文件等）.
* [macOS Artifact Parsing Tool (mac_apt)](https://github.com/ydkhatri/mac_apt) -基于插件的取证框架，可在实时计算机，磁盘映像或单个工件文件上进行快速Mac分流.
* [OSX Auditor](https://github.com/jipegit/OSXAuditor) -免费的Mac OS X计算机取证工具.
* [OSX Collector](https://github.com/yelp/osxcollector) -OSX Auditor分支以实时响应.

### Other Lists

* [List of various Security APIs](https://github.com/deralexxx/security-apis) -用于安全性的公共JSON API的集体列表.

### Other Tools

* [Cortex](https://thehive-project.org)  -Cortex允许您使用Web界面逐一或以批量模式分析IP和电子邮件地址，URL，域名，文件或哈希等可观察对象.  分析师还可以使用其REST API自动执行这些操作.
* [Crits](https://crits.github.io/) -基于Web的工具，将分析引擎与网络威胁数据库结合在一起.
* [Diffy](https://github.com/Netflix-Skunkworks/diffy) -由Netflix的SIRT开发的DFIR工具，使研究人员可以在事件发生期间跨云实例（当前在AWS上的Linux实例）快速确定妥协范围，并通过显示与基准的差异有效地将这些实例分类以采取后续行动.
* [domfind](https://github.com/diogo-fernan/domfind) -Python DNS搜寻器，用于在不同TLD下查找相同的域名.
* [Fenrir](https://github.com/Neo23x0/Fenrir)  -简单的IOC扫描仪.  它允许在纯bash中扫描任何Linux / Unix / OSX系统中的IOC.  由THOR和LOKI的创建者创建.
* [Fileintel](https://github.com/keithjjones/fileintel) -提取每个文件哈希的智能.
* [HELK](https://github.com/Cyb3rWard0g/HELK) -威胁搜寻平台.
* [Hindsight](https://github.com/obsidianforensics/hindsight) -Google Chrome / Chromium的互联网历史取证.
* [Hostintel](https://github.com/keithjjones/hostintel) -每个主机获取智能.
* [imagemounter](https://github.com/ralphje/imagemounter) -命令行实用程序和Python软件包可简化（取消）法医磁盘映像的安装.
* [Kansa](https://github.com/davehull/Kansa/) - Modular incident response framework in Powershell.
* [PyaraScanner](https://github.com/nogoodconfig/pyarascanner) -非常简单的多线程多规则多文件YARA扫描Python脚本的恶意软件动物园和IR.
* [rastrea2r](https://github.com/aboutsecurity/rastrea2r) -允许在Windows，Linux和OS X上使用YARA扫描磁盘和内存以查找IOC.
* [RaQet](https://raqet.github.io/) -非常规的远程获取和分类工具，可对通过专门构建的取证操作系统重新启动的远程计算机（客户端）的磁盘进行分类.
* [Stalk](https://www.percona.com/doc/percona-toolkit/2.2/pt-stalk.html) -发生问题时收集有关MySQL的取证数据.
* [Scout2](https://nccgroup.github.io/Scout2/) -安全工具，可让Amazon Web Services管理员评估其环境的安全状况.
* [SearchGiant](https://github.com/jadacyrus/searchgiant_cli) -命令行实用程序，用于从云服务获取取证数据.
* [Stenographer](https://github.com/google/stenographer)  -数据包捕获解决方案，旨在将所有数据包快速后台处理到磁盘，然后提供对这些数据包子集的简单，快速访问.  它存储尽可能多的历史记录，管理磁盘使用情况，并在达到磁盘限制时删除.  非常适合在事件发生之前和发生期间捕获流量，而无需明确需要存储所有网络流量.
* [sqhunter](https://github.com/0x4d31/sqhunter)  -基于osquery和Salt Open（SaltStack）的威胁猎人，无需osquery的tls插件即可发出即席或分布式查询.  sqhunter允许您查询打开的网络套接字，并根据威胁情报源对其进行检查.
* [traceroute-circl](https://github.com/CIRCL/traceroute-circl)  -扩展的跟踪路由以支持CSIRT（或CERT）运营商的活动.  通常，CSIRT团队必须根据收到的IP地址来处理事件.  由卢森堡计算机紧急响应中心创建.
* [X-Ray 2.0](https://www.raymond.cc/blog/xray/) -Windows实用程序（维护不良或不再维护），用于将病毒样本提交给AV供应商.


### Playbooks

* [Demisto Playbooks Collection](https://www.demisto.com/category/playbooks/) -剧本收藏.
* [IRM](https://github.com/certsocietegenerale/IRM) -CERT法国兴业银行的事件响应方法.
* [IR Workflow Gallery](https://www.incidentresponse.com/playbooks/)  -不同的通用事件响应工作流程，例如针对恶意软件爆发，数据盗窃，未经授权的访问....每个工作流程包含七个步骤：准备，检测，分析，遏制，根除，恢复，事后处理.  这些工作流程可以在线获得或下载.
* [PagerDuty Incident Response Documentation](https://response.pagerduty.com/)  -描述PagerDuty事件响应过程部分内容的文档.  它不仅提供有关事件准备的信息，而且还提供事件发生期间和之后的处理方法.  资料来源为 [GitHub](https://github.com/PagerDuty/incident-response-docs).

### Process Dump Tools

* [Microsoft User Mode Process Dumper](http://www.microsoft.com/en-us/download/details.aspx?id=4060) -动态转储所有正在运行的Win32进程的内存映像.

### Sandboxing/reversing tools

* [AMAaaS](https://amaaas.com/index.php/AMAaaS/dashboard) -在本地Android环境中执行的Android恶意软件分析即服务.
* [Any Run](https://app.any.run/) -交互式在线恶意软件分析服务，可在任何环境下对大多数类型的威胁进行动态和静态研究.
* [Cuckoo](https://github.com/cuckoobox) -开源高度可配置的沙箱工具.
* [Cuckoo-modified](https://github.com/spender-sandbox/cuckoo-modified) -社区开发的经过大量修改的布谷鸟叉子.
* [Cuckoo-modified-api](https://github.com/keithjjones/cuckoo-modified-api) -用于控制布谷鸟修改的沙箱的Python库.
* [Hybrid-Analysis](https://www.hybrid-analysis.com/) -CrowdStrike提供的免费强大的在线沙箱.
* [Intezer](https://analyze.intezer.com/#/) -Intezer Analyze深入研究Windows二进制文件，以检测与已知威胁的微代码相似性，从而提供准确而又易于理解的结果.
* [Joe Sandbox (Community)](https://www.joesandbox.com/)  -Joe Sandbox在Windows，Android，Mac OS，Linux和iOS上检测并分析潜在的恶意文件和URL，以进行可疑活动；  提供全面详细的分析报告.
* [Mastiff](https://github.com/KoreLogicSecurity/mastiff) -静态分析框架，可自动从多种不同的文件格式中提取关键特征.
* [Metadefender Cloud](https://www.metadefender.com) -免费的威胁情报平台，提供文件的多重扫描，数据清理和漏洞评估.
* [Reverse.IT](https://www.reverse.it/) -CrowdStrike提供的混合分析工具的替代域.
* [Valkyrie Comodo](https://valkyrie.comodo.com) -Valkyrie使用运行时行为和文件中的数百个功能来执行分析.
* [Viper](https://github.com/viper-framework/viper) -基于Python的二进制分析和管理框架，可与Cuckoo和YARA很好地配合使用.
* [Visualize_Logs](https://github.com/keithjjones/visualize_logs) -用于日志的开源可视化库和命令行工具（Cuckoo，Procmon，以后还会有更多）.

### Timeline tools

* [Highlighter](https://www.fireeye.com/services/freeware/highlighter.html)  -Fire / Mandiant提供的免费工具，它将描述日志/文本文件，该文件可以突出显示图形上与关键字或短语相对应的区域.  非常适合用于安排感染以及妥协后所做的工作.
* [Morgue](https://github.com/etsy/morgue) -Etsy的PHP Web应用程序，用于管理验尸.
* [Plaso](https://github.com/log2timeline/plaso) -工具log2timeline的基于Python的后端引擎.
* [Timesketch](https://github.com/google/timesketch) -用于协作取证时间表分析的开源工具.


### Videos

* [Demisto IR video resources](https://www.demisto.com/category/videos/) -事件响应和取证工具的视频资源.
* [The Future of Incident Response](https://www.youtube.com/watch?v=bDcx4UNpKNc) -由Bruce Schneier在OWASP AppSecUSA 2015上发表.

### Windows Evidence Collection

* [AChoir](https://github.com/OMENScan/AChoir) -框架/脚本工具，用于标准化和简化用于Windows的实时采集实用程序的脚本编写过程.
* [Binaryforay](http://binaryforay.blogspot.co.il/p/software.html) -用于取证的免费工具列表（http://binaryforay.blogspot.co.il/）.
* [Crowd Response](http://www.crowdstrike.com/community-tools/)  -轻量级Windows控制台应用程序，旨在帮助收集系统信息以进行事件响应和安全参与.  它具有许多模块和输出格式.
* [DFIR ORC](https://dfir-orc.github.io/)  -DFIR ORC是专用工具的集合，这些工具专用于可靠地解析和收集关键工件，例如MFT，注册表配置单元或事件日志.  DFIR ORC收集数据，但不对其进行分析：它不打算对机器进行分类.  它提供了运行Microsoft Windows的计算机的取证相关快照.  该代码可以在找到 [GitHub](https://github.com/DFIR-ORC/dfir-orc).
* [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector)  -可以在实时Windows系统上收集不同工件的工具，并将结果记录在csv文件中.  通过对这些伪像的分析，可以发现早期的妥协.
* [Fast Evidence Collector Toolkit (FECT)](https://github.com/jipegit/FECT)  -轻微事件响应工具包，用于在可疑Windows计算机上收集证据.  基本上，它打算由与熟练操作者“事件处理程序”一起工作的非技术敏锐人士使用.
* [Fibratus](https://github.com/rabbitstack/fibratus) -Windows内核探索和跟踪工具.
* [IREC](https://binalyze.com/products/irec-free/)  -多合一的IR证据收集器，可捕获RAM映像，$ MFT，EventLogs，WMI脚本，注册表配置单元，系统还原点等等.  它是免费的，闪电般快速且易于使用.
* [IOC Finder](https://www.fireeye.com/services/freeware/ioc-finder.html)  -Mandiant提供的免费工具，用于收集主机系统数据并报告危害指标（IOC）的存在.  仅支持Windows.
* [Fidelis ThreatScanner](https://www.fidelissecurity.com/resources/fidelis-threatscanner)  -Fidelis网络安全提供的免费工具，该工具使用OpenIOC和YARA规则报告端点状态.  用户提供OpenIOC和YARA规则并执行该工具.  ThreatScanner可以测量系统状态，运行完成后，将生成任何匹配规则的报告.  仅Windows.
* [LOKI](https://github.com/Neo23x0/Loki) -免费的IR扫描仪，可使用yara规则和其他指示器（IOC）扫描端点.
* [MEERKAT](https://github.com/TonyPhipps/Meerkat) -Windows的基于PowerShell的分类和威胁搜寻.
* [Panorama](https://github.com/AlmCo/Panorama) -实时Windows系统上的快速事件概述.
* [PowerForensics](https://github.com/Invoke-IR/PowerForensics) -使用PowerShell的实时磁盘取证平台.
* [PSRecon](https://github.com/gfoss/PSRecon/)  -PSRecon使用PowerShell（v2或更高版本）从远程Windows主机收集数据，将数据组织到文件夹中，对所有提取的数据进行哈希处理，对PowerShell和各种系统属性进行哈希处理，然后将数据发送给安全团队.  数据可以推送到共享，通过电子邮件发送或本地保留.
* [RegRipper](https://code.google.com/p/regripper/wiki/RegRipper) -用Perl编写的开源工具，用于从注册表中提取/解析信息（键，值，数据）并将其呈现出来进行分析.
* [TRIAGE-IR](https://code.google.com/p/triage-ir/) -用于Windows的IR收集器.
