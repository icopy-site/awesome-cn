<div class="github-widget" data-repo="meirwah/awesome-incident-response"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Incident Response [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;针对安全事件响应的策划工具和资源列表，旨在帮助安全分析师和 [DFIR](http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-%28DFIR%29.html) 团队.

数字取证和事件响应（DFIR）团队是负责管理安全事件响应的组织中的一组人员，包括收集事件的证据，补救其影响，以及实施控制以防止事件在未来再次发生.



## IR tools Collection

### Adversary Emulation

* [APTSimulator](https://github.com/NextronSystems/APTSimulator) -  Windows批处理脚本，它使用一组工具和输出文件使系统看起来好像已被泄露.
* [Atomic Red Team (ART)](https://github.com/redcanaryco/atomic-red-team) - 小型且高度便携的检测测试，映射到Mitre ATT和CK Framework.
* [AutoTTP](https://github.com/jymcheong/AutoTTP)   - 自动战术技术和程序.  手动重新运行复杂序列以进行回归测试，产品评估，为研究人员生成数据.
* [Blue Team Training Toolkit (BT3)](https://www.bt3.no/) - 用于防御性安全培训的软件，它将使您的网络分析培训课程，事件响应演练和红色团队合作达到一个新的水平.
* [Caldera](https://github.com/mitre/caldera)   - 自动对手仿真系统，可在Windows企业网络中执行折衷后的对抗行为.  它使用计划系统和基于对抗战术，技术和常识（ATT＆CK™）项目的预配置对手模型在运营期间生成计划.
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire)   - 模块化，菜单驱动，跨平台工具，用于构建可重复，延时，分布式安全事件.  轻松为Blue Team演习和传感器/警报映射创建自定义事件链.  红队可以制造诱饵事件，分心和诱饵，以支持和扩展他们的行动.
* [Metta](https://github.com/uber-common/metta) - 用于进行对抗性模拟的信息安全准备工具.
* [Network Flight Simulator](https://github.com/alphasoc/flightsim) - 轻量级实用程序，用于生成恶意网络流量，并帮助安全团队评估安全控制和网络可见性.
* [Red Team Automation (RTA)](https://github.com/endgameinc/RTA) -  RTA提供了一个脚本框架，旨在允许蓝队测试他们针对恶意交易的检测能力，模仿MITRE ATT和CK.
* [RedHunt-OS](https://github.com/redhuntlabs/RedHunt-OS) - 用于对手仿真和威胁搜寻的虚拟机.

### All in one Tools

* [Belkasoft Evidence Center](https://belkasoft.com/ec) - 该工具包将通过分析硬盘驱动器，驱动器映像，内存转储，iOS，Blackberry和Android备份，UFED，JTAG和芯片关闭转储，快速从多个来源提取数字证据.
* [CimSweep](https://github.com/PowerShellMafia/CimSweep) - 基于CIM / WMI的工具套件，能够在所有版本的Windows上远程执行事件响应和搜索操作.
* [CIRTkit](https://github.com/byt3smith/CIRTKit) -  CIRTKit不仅是一个工具集合，而且是一个框架，以帮助事件响应和取证调查过程的持续统一.
* [Cyber Triage](http://www.cybertriage.com)   -  Cyber​​ Triage可远程收集和分析端点数据，以帮助确定其是否受到危害.  它是无代理方法，专注于易用性和自动化，使公司能够在没有重大基础架构变更的情况下做出响应，并且没有法医专家团队.  其结果用于决定是否应该擦除系统或进一步调查.
* [Digital Forensics Framework](http://www.arxsys.fr/discover/)   - 基于专用应用程序编程接口（API）构建的开源计算机取证平台.  DFF提出了当今使用的老化数字取证解决方案的替代方案.  DFF界面专为简单使用和自动化而设计，可引导用户完成数字调查的主要步骤，因此专业人员和非专家都可以使用它快速轻松地进行数字调查并执行事件响应.
* [Doorman](https://github.com/mwielgoszewski/doorman)   -  osquery fleet manager，允许远程管理节点检索的osquery配置.  它利用了osquery的TLS配置，记录器和分布式读/写端点，使管理员能够以最小的开销和侵入性在一组设备上实现可见性.
* [Envdb](https://github.com/mephux/envdb)   -  Envdb将您的生产，开发，云等环境转变为数据库集群，您可以使用osquery作为基础进行搜索.  它使用（群集）节点代理包装osquery进程，该代理可以与中央位置进行通信.
* [Falcon Orchestrator](https://github.com/CrowdStrike/falcon-orchestrator) - 可扩展的基于Windows的应用程序，提供工作流程自动化，案例管理和安全响应功能.
* [GRR Rapid Response](https://github.com/google/grr)   - 事件响应框架侧重于远程实时取证.  它由安装在目标系统上的python代理（客户端）和可以管理代理并与代理通信的python服务器基础结构组成.
* [Kolide Fleet](https://kolide.com/fleet)   - 为安全专家量身定制的最先进的主机监控平台.  利用Facebook经过实战考验的osquery项目，Kolide可以快速回答大问题.
* [Limacharlie](https://github.com/refractionpoint/limacharlie) - 由一系列小型项目组成的端点安全平台，它们协同工作，为您提供跨平台（Windows，OSX，Linux，Android和iOS）低级环境，用于管理和将其他模块推送到内存中以扩展其功能.
* [Mozilla Investigator (MIG)](http://mig.mozilla.org/)   - 在远程终端上进行调查手术的平台.  它使调查人员能够并行获取大量系统的信息，从而加快对事件和日常操作安全性的调查.
* [MozDef](https://github.com/mozilla/MozDef) - 自动化安全事件处理流程并促进事件处理程序的实时活动.
* [nightHawk](https://github.com/biggiesmallsAG/nightHawkResponse)   - 使用ElasticSearch作为后端为异步法证数据表示构建的应用程序.  它旨在摄取Redline系列.
* [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/)   - 另一种流行的分布式开源计算机取证框架.  该框架基于Linux平台构建，使用postgreSQL数据库存储数据.
* [osquery](https://osquery.io/)   - 使用类似SQL的查询语言轻松询问有关Linux和macOS基础架构的问题;  提供的*事件响应包*可帮助您检测并响应违规行为.
* [Redline](https://www.fireeye.com/services/freeware/redline.html) - 为用户提供主机调查功能，通过内存和文件分析查找恶意活动迹象，并开发威胁评估配置文件.
* [The Sleuth Kit & Autopsy](http://www.sleuthkit.org)   - 基于Unix和Windows的工具，有助于计算机的取证分析.  它配备了各种有助于数字取证的工具.  这些工具有助于分析磁盘映像，对文件系统进行深入分析以及其他各种操作.
* [TheHive](https://thehive-project.org/) - 可扩展的3合1开源和免费解决方案，旨在使SOC，CSIRT，CERT和任何信息安全从业人员更轻松地处理需要迅速调查和采取行动的安全事件.
* [X-Ways Forensics](http://www.x-ways.net/forensics/)   - 用于磁盘克隆和映像的取证工具.  它可用于查找已删除的文件和磁盘分析.
* [Zentral](https://github.com/zentralopensource/zentral)   - 将osquery强大的端点库存功能与灵活的通知和操作框架相结合.  这使得人们可以识别OS X和Linux客户端上的更改并做出反应.

### Books

* [DFIR intro](https://medium.com/@sroberts/introduction-to-dfir-d35d5de4c180/) - 作者：Scott J. Roberts.
* [The Practice of Network Security Monitoring: Understanding Incident Detection and Response](http://www.amazon.com/gp/product/1593275099) -  Richard Bejtlich关于IR的书.

### Communities

* [augmentd](http://augmentd.co/) - 社区驱动的站点，提供可以在各种常见安全工具中实施和执行的搜索列表.
* [Sans DFIR mailing list](https://lists.sans.org/mailman/listinfo/dfir) -  SANS为DFIR提供的邮件列表.
* [Slack DFIR channel](https://dfircommunity.slack.com) -  Slack DFIR Communitiy频道 -  [Signup here](https://rishi28.typeform.com/to/sTbTI8).

### Disk Image Creation Tools

* [AccessData FTK Imager](http://accessdata.com/product-download/?/support/adownloads#FTKImager)   - 取证工具，其主要目的是从任何类型的磁盘预览可恢复的数据.  FTK Imager还可以在32位和64位系统上获取实时内存和分页文件.
* [Bitscout](https://github.com/vitaly-kamluk/bitscout)   -  Vitaly Kamluk的Bitscout帮助您构建完全可信的可定制LiveCD / LiveUSB图像，用于远程数字取证（或者您选择的任何其他任务）.  它意味着系统的所有者是透明和可监控的，具有法律声音，可定制和紧凑.
* [GetData Forensic Imager](http://www.forensicimager.com/) - 基于Windows的程序，将以下列常见取证文件格式之一获取，转换或验证取证图像.
* [Guymager](http://guymager.sourceforge.net) - 免费的取证成像器，用于在Linux上进行媒体采集.
* [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) -  Magnet Forensics的ACQUIRE允许在Windows，Linux和OS X以及移动操作系统上执行各种类型的磁盘采集.

### Evidence Collection

* [bulk_extractor](https://github.com/simsong/bulk_extractor)   - 计算机取证工具，可扫描磁盘映像，文件或文件目录，并在不解析文件系统或文件系统结构的情况下提取有用信息.  由于忽略了文件系统结构，该程序在速度和彻底性方面有所区别.
* [Cold Disk Quick Response](https://github.com/rough007/CDQR) - 简化的解析器列表，可快速分析取证图像文件（`dd`，E01，`.vmdk`等）并输出9个报告.
* [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -  Windows批处理脚本和Unix Bash脚本，用于在事件响应期间全面收集主机取证数据.
* [Live Response Collection](https://www.brimorlabs.com/tools/) - 自动化工具，可从Windows，OSX和基于* nix的操作系统收集易失性数据.
* [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - 命令行实用程序（与或不与Amazon EC2实例一起使用）以并行化远程内存获取.

### Incident Management

* [CyberCPR](https://www.cybercpr.com) - 内置和需要知识的商业事件管理工具，以便在处理敏感事件时支持GDPR合规性.
* [Cyphon](https://www.cyphon.io/)   -  Cyphon通过单一平台简化了大量相关任务，从而消除了事件管理的麻烦.  它接收，处理和分类事件，为您的分析工作流提供全方位的解决方案 - 聚合数据，捆绑和确定警报优先级，并使分析师能够调查和记录事件.
* [Demisto](https://www.demisto.com/product/) -  Demisto社区版（免费）提供完整的事件生命周期管理，事件关闭报告，团队分配和协作，以及许多增强自动化的集成（如Active Directory，PagerDuty，Jira等等）.
* [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR/)   - 网络安全事件管理平台，设计灵活，速度快.  它允许轻松创建，跟踪和报告网络安全事件，对CSIRT，CERT和SOC都很有用.
* [RTIR](https://www.bestpractical.com/rtir/)   - 事件响应请求跟踪器（RTIR）是针对计算机安全团队的首要开源事件处理系统.  我们与全球十几个CERT和CSIRT团队合作，帮助您处理不断增加的事件报告.  RTIR建立在Request Tracker的所有功能之上.
* [Sandia Cyber Omni Tracker (SCOT)](http://getscot.sandia.gov/)   - 事件响应协作和知识捕获工具侧重于灵活性和易用性.  我们的目标是为事件响应流程增加价值，而不会给用户带来负担.
* [threat_note](https://github.com/defpoint/threat_note) - 轻量级调查笔记本，允许安全研究人员注册和检索与他们的研究相关的指标.

### Linux Distributions

* [The Appliance for Digital Investigation and Analysis (ADIA)](https://forensics.cert.org/#ADIA)   - 用于数字调查和采集的基于VMware的设备，完全由公共领域软件构建.  ADIA中包含的工具包括Autopsy，Sleuth Kit，Digital Forensics Framework，log2timeline，Xplico和Wireshark.  大多数系统维护都使用Webmin.  它专为中小型数字调查和收购而设计.  该设备在Linux，Windows和Mac OS下运行.  i386（32位）和x86_64（64位）版本均可用.
* [Computer Aided Investigative Environment (CAINE)](http://www.caine-live.net/index.html) - 包含许多工具，帮助调查人员在分析过程中，包括法医证据收集.
* [CCF-VM](https://github.com/rough007/CCF-VM) -  CyLR CDQR取证虚拟机（CCF-VM）：一种解析收集数据的一体化解决方案，可通过内置常见搜索轻松搜索，同时支持单个和多个主机的搜索.
* [Digital Evidence & Forensics Toolkit (DEFT)](http://www.deftlinux.net/)   - 用于计算机取证证据收集的Linux发行版.  它与Windows的数字高级响应工具包（DART）捆绑在一起.  DEFT Zero的轻型版本也可用，它主要侧重于法医证据收集.
* [NST - Network Security Toolkit](https://sourceforge.net/projects/nst/files/latest/download?source=files) -  Linux发行版，包括对网络安全专业人员有用的大量最佳开源网络安全应用程序.
* [PALADIN](https://sumuri.com/software/paladin/)   - 修改Linux发行版，以法医声方式执行各种forenics任务.  它包含许多开源取证工具.
* [Security Onion](https://github.com/Security-Onion-Solutions/security-onion) - 针对具有高级分析工具的网络安全监控的特殊Linux发行版.
* [SANS Investigative Forensic Toolkit (SIFT) Workstation](http://digital-forensics.sans.org/community/downloads) - 使用可免费获得且经常更新的尖端开源工具，证明可以使用先进的事件响应功能和深入的数字取证技术来实现入侵.

### Linux Evidence Collection

* [FastIR Collector Linux](https://github.com/SekoiaLab/Fastir_Collector_Linux) -  FastIR for Linux在实时Linux上收集不同的人工制品，并将结果记录在csv文件中.

### Log Analysis Tools

* [Kaspersky CyberTrace](https://support.kaspersky.com/13850)   - 威胁情报融合和分析工具，将威胁数据源与SIEM解决方案集成在一起.  用户可以立即利用威胁情报在其现有安全操作的工作流程中进行安全监控和事件报告（IR）活动.
* [Lorg](https://github.com/jensvoid/lorg) - 用于高级HTTPD日志文件安全性分析和取证的工具.
* [Logdissect](https://github.com/dogoncouch/logdissect) - 用于分析日志文件和其他数据的CLI实用程序和Python API.
* [StreamAlert](https://github.com/airbnb/streamalert) - 无服务器的实时日志数据分析框架，能够使用用户定义的逻辑提取自定义数据源并触发警报.
* [SysmonSearch](https://github.com/JPCERTCC/SysmonSearch) - 通过聚合事件日志，SysmonSearch使Windows事件日志分析更有效，耗时更少.

### Memory Analysis Tools

* [Evolve](https://github.com/JamesHabben/evolve) -  Volatility Memory取证框架的Web界面.
* [inVtero.net](https://github.com/ShaneK2/inVtero.net) - 具有嵌套虚拟机管理程序支持的Windows x64高级内存分析.
* [KnTList](http://www.gmgsystemsinc.com/knttools/) - 计算机内存分析工具.
* [LiME](https://github.com/504ensicsLabs/LiME) - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD.
* [Memoryze](https://www.fireeye.com/services/freeware/memoryze.html)   - 免费内存取证软件，帮助事件响应者在现场记忆中发现邪恶.  Memoryze可以获取和/或分析存储器图像，并且在实时系统上，可以在其分析中包括页面文件.
* [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze-for-the-mac.html)   -  Memoryze for Mac是Memoryze，但随后是Mac.  但是，功能数量较少.
* [Rekall](http://www.rekall-forensic.com/) - Open source tool (and library) for the extraction of digital artifacts from volatile memory (RAM) samples.
* [Responder PRO](http://www.countertack.com/responder-pro) - Responder PRO is the industry standard physical memory and automated malware analysis solution.
* [Volatility](https://github.com/volatilityfoundation/volatility) - 高级内存取证框架.
* [VolatilityBot](https://github.com/mkorman90/VolatilityBot) - 研究人员的自动化工具可以减少二进制提取阶段的所有猜测和手动任务，或者帮助研究人员完成记忆分析调查的第一步.
* [VolDiff](https://github.com/aim4r/VolDiff) - 基于波动率的恶意软件内存占用分析.
* [WindowsSCOPE](http://www.windowsscope.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=35&category_id=3&option=com_virtuemart) - 用于分析易失性内存的内存取证和逆向工程工具，提供分析Windows内核，驱动程序，DLL以及虚拟和物理内存的功能.

### Memory Imaging Tools

* [Linux Memory Grabber](https://github.com/halpomeranz/lmg/) - 用于转储Linux内存和创建Volatility配置文件的脚本.
* [Magnet RAM Capture](https://www.magnetforensics.com/free-tool-magnet-ram-capture/)   - 免费的成像工具，旨在捕获嫌疑人计算机的物理内存.  支持最新版本的Windows.
* [OSForensics](http://www.osforensics.com/)   - 在32位和64位系统上获取实时内存的工具.  可以完成单个进程的内存空间或物理内存转储的转储.

### OSX Evidence Collection

* [Knockknock](https://github.com/synack/knockknock) - 显示设置为在OSX上自动执行的持久性项目（脚本，命令，二进制文件等）.
* [macOS Artifact Parsing Tool (mac_apt)](https://github.com/ydkhatri/mac_apt) - 基于插件的取证框架，用于快速mac分类，适用于实时机器，磁盘映像或单个工件文件.
* [OSX Auditor](https://github.com/jipegit/OSXAuditor) - 免费的Mac OS X计算机取证工具.
* [OSX Collector](https://github.com/yelp/osxcollector) -  OSX Auditor分支，用于实时响应.

### Other Lists

* [List of various Security APIs](https://github.com/deralexxx/security-apis) - 用于安全性的公共JSON API的集合列表.

### Other Tools

* [Cortex](https://thehive-project.org)   -  Cortex允许您使用Web界面逐个或以批量模式分析IP和电子邮件地址，URL，域名，文件或哈希等可观察对象.  分析师还可以使用其REST API自动执行这些操作.
* [Crits](https://crits.github.io/) - 基于Web的工具，它将分析引擎与网络威胁数据库相结合.
* [Diffy](https://github.com/Netflix-Skunkworks/diffy) - 由Netflix的SIRT开发的DFIR工具，允许调查人员在事件期间快速确定云实例（当前AWS上的Linux实例）的折衷方案，并通过显示基线差异来有效地对这些实例进行后续操作.
* [domfind](https://github.com/diogo-fernan/domfind) - 用于在不同TLD下查找相同域名的Python DNS搜寻器.
* [Fenrir](https://github.com/Neo23x0/Fenrir)   - 简单的IOC扫描仪.  它允许在普通bash中扫描任何Linux / Unix / OSX系统的IOC.  由THOR和LOKI的创作者创建.
* [Fileintel](https://github.com/keithjjones/fileintel) - 每个文件哈希拉动智能.
* [HELK](https://github.com/Cyb3rWard0g/HELK) - 威胁狩猎平台.
* [Hindsight](https://github.com/obsidianforensics/hindsight) -  Google Chrome / Chromium的互联网历史取证.
* [Hostintel](https://github.com/keithjjones/hostintel) - 每个主机提取智能.
* [imagemounter](https://github.com/ralphje/imagemounter) - 命令行实用程序和Python包，以简化（取消）安装取证磁盘映像.
* [Kansa](https://github.com/davehull/Kansa/) -  Powershell中的模块化事件响应框架.
* [PyaraScanner](https://github.com/nogoodconfig/pyarascanner) - 非常简单的多线程多规则到多文件YARA扫描Python脚本用于恶意软件动物园和IR.
* [rastrea2r](https://github.com/aboutsecurity/rastrea2r) - 允许用户在Windows，Linux和OS X上使用YARA扫描IOC的磁盘和内存.
* [RaQet](https://raqet.github.io/) - 非常规的远程采集和分类工具，允许对使用特制的取证操作系统重新启动的远程计算机（客户端）的磁盘进行分类.
* [Stalk](https://www.percona.com/doc/percona-toolkit/2.2/pt-stalk.html) - 出现问题时收集有关MySQL的取证数据.
* [Scout2](https://nccgroup.github.io/Scout2/) - 安全工具，可让Amazon Web Services管理员评估其环境的安全状况.
* [SearchGiant](https://github.com/jadacyrus/searchgiant_cli) - 用于从云服务获取取证数据的命令行实用程序.
* [Stenographer](https://github.com/google/stenographer)   - 数据包捕获解决方案，旨在快速将所有数据包假脱机到磁盘，然后提供对这些数据包的子集的简单，快速访问.  它可以存储尽可能多的历史记录，管理磁盘使用情况，以及在磁盘限制被触发时删除.  它非常适合在事件发生之前和事件期间捕获流量，而无需明确需要存储所有网络流量.
* [sqhunter](https://github.com/0x4d31/sqhunter)   - 基于osquery和Salt Open（SaltStack）的威胁猎手，可以发出临时或分布式查询，而无需osquery的tls插件.  sqhunter允许您查询打开的网络套接字并根据威胁情报源进行检查.
* [traceroute-circl](https://github.com/CIRCL/traceroute-circl)   - 扩展的traceroute，以支持CSIRT（或CERT）运营商的活动.  通常CSIRT团队必须根据收到的IP地址处理事件.  由卢森堡计算机应急响应中心创建.
* [X-Ray 2.0](https://www.raymond.cc/blog/xray/) -  Windows实用程序（维护不善或不再维护）向AV供应商提交病毒样本.


### Playbooks

* [Demisto Playbooks Collection](https://www.demisto.com/category/playbooks/) -  Playbooks系列.
* [IRM](https://github.com/certsocietegenerale/IRM) -  CERT Societe Generale的事件响应方法.
* [IR Workflow Gallery](https://www.incidentresponse.com/playbooks/)   - 不同的通用事件响应工作流程，例如恶意软件爆发，数据窃取，未经授权的访问，......每个工作流程由七个步骤组成：准备，检测，分析，包含，根除，恢复，事件后处理.  工作流程可在线获取或下载.
* [PagerDuty Incident Response Documentation](https://response.pagerduty.com/)   - 描述PagerDuty事件响应流程部分内容的文档.  它不仅提供有关准备事件的信息，还提供在期间和之后要做的事情.  来源可用 [GitHub](https://github.com/PagerDuty/incident-response-docs).

### Process Dump Tools

* [Microsoft User Mode Process Dumper](http://www.microsoft.com/en-us/download/details.aspx?id=4060) - 即时转储任何正在运行的Win32处理内存映像.

### Sandboxing/reversing tools

* [Cuckoo](https://github.com/cuckoobox) - 开源高度可配置的沙盒工具.
* [Cuckoo-modified](https://github.com/spender-sandbox/cuckoo-modified) - 由社区开发的重度修改的Cuckoo叉子.
* [Cuckoo-modified-api](https://github.com/keithjjones/cuckoo-modified-api) - 用于控制布谷鸟修改沙箱的Python库.
* [Hybrid-Analysis](https://www.hybrid-analysis.com/) -  Payload Security免费强大的在线沙箱.
* [Malwr](https://malwr.com) - 免费的在线恶意软件分析服务和社区，由Cuckoo Sandbox提供支持.
* [Mastiff](https://github.com/KoreLogicSecurity/mastiff) - 静态分析框架，自动化从多种不同文件格式中提取关键特征的过程.
* [Metadefender Cloud](https://www.metadefender.com) - 免费威胁情报平台，提供多扫描，数据清理和文件漏洞评估.
* [Viper](https://github.com/viper-framework/viper) - 基于Python的二进制分析和管理框架，适用于Cuckoo和YARA.
* [Visualize_Logs](https://github.com/keithjjones/visualize_logs) - 用于日志的开源可视化库和命令行工具（Cuckoo，Procmon，更多内容）.

### Timeline tools

* [Highlighter](https://www.fireeye.com/services/freeware/highlighter.html)   -  Fire / Mandiant提供的免费工具，它将描绘日志/文本文件，可以突出显示图形上与关键字或短语相对应的区域.  有利于时间排除感染和妥协后做了什么.
* [Morgue](https://github.com/etsy/morgue) -  Etsy的PHP Web应用程序，用于管理事后管理.
* [Plaso](https://github.com/log2timeline/plaso) - 用于工具log2timeline的基于Python的后端引擎.
* [Timesketch](https://github.com/google/timesketch) - 用于协作取证时间线分析的开源工具.


### Videos

* [Demisto IR video resources](https://www.demisto.com/category/videos/) - 事件响应和取证工具的视频资源.
* [The Future of Incident Response](https://www.youtube.com/watch?v=bDcx4UNpKNc) - 由Bruce Schneier在OWASP AppSecUSA 2015上发表.

### Windows Evidence Collection

* [AChoir](https://github.com/OMENScan/AChoir) - 框架/脚本工具，用于标准化和简化Windows脚本实时采集实用程序的过程.
* [Binaryforay](http://binaryforay.blogspot.co.il/p/software.html) -  win forensics免费工具列表（http://binaryforay.blogspot.co.il/）.
* [Crowd Response](http://www.crowdstrike.com/community-tools/)   - 轻量级Windows控制台应用程序，旨在帮助收集事件响应和安全约定的系统信息.  它具有众多模块和输出格式.
* [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector)   - 在实时Windows系统上收集不同人工制品并将结果记录在csv文件中的工具.  通过对这些人工制品的分析，可以检测到早期的妥协.
* [Fast Evidence Collector Toolkit (FECT)](https://github.com/jipegit/FECT)   -  Light事件响应工具包，用于收集可疑Windows计算机上的证据.  基本上它是由非技术精明的人与熟练工事件处理程序一起使用.
* [Fibratus](https://github.com/rabbitstack/fibratus) - 用于探索和跟踪Windows内核的工具.
* [IREC](https://binalyze.com/products/irec-free/) - All-in-one IR Evidence Collector which captures RAM Image, $MFT, EventLogs, WMI Scripts, Registry Hives, System Restore Points and much more. It is FREE, lightning fast and easy to use.
* [IOC Finder](https://www.fireeye.com/services/freeware/ioc-finder.html)   -  Mandiant的免费工具，用于收集主机系统数据并报告妥协指标（IOC）的存在.  仅支持Windows.
* [Fidelis ThreatScanner](https://www.fidelissecurity.com/resources/fidelis-threatscanner)   - 来自Fidelis Cyber​​security的免费工具，它使用OpenIOC和YARA规则来报告端点的状态.  用户提供OpenIOC和YARA规则并执行该工具.  ThreatScanner测量系统的状态，并在运行完成时生成任何匹配规则的报告.  仅限Windows.
* [LOKI](https://github.com/Neo23x0/Loki) - 使用yara规则和其他指标（IOC）扫描终点的免费红外扫描仪.
* [MEERKAT](https://github.com/TonyPhipps/Meerkat) - 基于PowerShell的Windows分类和threathunting.
* [Panorama](https://github.com/AlmCo/Panorama) - 实时Windows系统的快速事件概述.
* [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 使用PowerShell的Live disk取证平台.
* [PSRecon](https://github.com/gfoss/PSRecon/)   -  PSRecon使用PowerShell（v2或更高版本）从远程Windows主机收集数据，将数据组织到文件夹中，散列所有提取的数据，散列PowerShell和各种系统属性，并将数据发送给安全团队.  数据可以推送到共享，通过电子邮件发送或保留在本地.
* [RegRipper](https://code.google.com/p/regripper/wiki/RegRipper) - 用Perl编写的开源工具，用于从Registry中提取/解析信息（键，值，数据）并将其呈现用于分析.
* [TRIAGE-IR](https://code.google.com/p/triage-ir/) - 适用于Windows的IR收集器.
