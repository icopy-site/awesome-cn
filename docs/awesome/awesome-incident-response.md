<div class="github-widget" data-repo="meirwah/awesome-incident-response"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Incident Response [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 安全事件响应工具和资源的精选列表，旨在帮助安全分析师和 [DFIR](http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-%28DFIR%29.html) 团队.

数字取证和事件响应 (DFIR) 团队是组织中负责管理对安全事件的响应的一组人员，包括收集事件的证据、补救其影响以及实施控制以防止事件在未来再次发生.



## IR Tools Collection

### Adversary Emulation

* [APTSimulator](https://github.com/NextronSystems/APTSimulator) - Windows Batch 脚本，它使用一组工具和输出文件使系统看起来好像被入侵了.
* [Atomic Red Team (ART)](https://github.com/redcanaryco/atomic-red-team) - 映射到 MITRE ATT&amp;CK 框架的小型且高度便携的检测测试.
* [AutoTTP](https://github.com/jymcheong/AutoTTP)  - 自动化战术技术和程序. 手动重新运行复杂序列以进行回归测试、产品评估，为研究人员生成数据.
* [Blue Team Training Toolkit (BT3)](https://www.bt3.no/) - 防御性安全培训软件，它将您的网络分析培训课程、事件响应演习和红队参与提升到一个新的水平.
* [Caldera](https://github.com/mitre/caldera)  - 在 Windows Enterprise 网络中执行妥协后对抗行为的自动化对手仿真系统. 它在操作期间使用计划系统和基于对抗战术、技术和常识 (ATT&amp;CK™) 项目的预配置对手模型生成计划.
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire)  - 模块化的、菜单驱动的、跨平台的工具，用于构建可重复的、延时的、分布式的安全事件. 为蓝队演习和传感器/警报映射轻松创建自定义事件链. 红队可以制造诱饵事件、干扰和诱饵来支持和扩展他们的行动.
* [Metta](https://github.com/uber-common/metta) - 进行对抗模拟的信息安全准备工具.
* [Network Flight Simulator](https://github.com/alphasoc/flightsim) - 用于生成恶意网络流量并帮助安全团队评估安全控制和网络可见性的轻量级实用程序.
* [Red Team Automation (RTA)](https://github.com/endgameinc/RTA) - RTA 提供了一个脚本框架，旨在允许蓝队测试其针对恶意交易的检测能力，以 MITRE ATT&amp;CK 为模型.
* [RedHunt-OS](https://github.com/redhuntlabs/RedHunt-OS) - 用于对手仿真和威胁搜寻的虚拟机.

### All-In-One Tools

* [Belkasoft Evidence Center](https://belkasoft.com/ec) - 该工具包将通过分析硬盘驱动器、驱动器映像、内存转储、iOS、Blackberry 和 Android 备份、UFED、JTAG 和芯片转储转储，从多个来源快速提取数字证据.
* [CimSweep](https://github.com/PowerShellMafia/CimSweep) - 基于 CIM/WMI 的工具套件，能够跨所有 Windows 版本远程执行事件响应和搜寻操作.
* [CIRTkit](https://github.com/byt3smith/CIRTKit) - CIRTKit 不仅是一组工具，而且还是一个有助于持续统一事件响应和取证调查流程的框架.
* [Cyber Triage](http://www.cybertriage.com)  - Cyber​​ Triage 远程收集和分析端点数据，以帮助确定它是否受到损害. 它采用无代理方法，专注于易用性和自动化，使公司无需重大基础设施更改和取证专家团队即可做出响应. 其结果用于决定是否应该删除或进一步调查系统.
* [Doorman](https://github.com/mwielgoszewski/doorman)  - osquery 车队管理器，允许远程管理节点检索的 osquery 配置. 它利用 osquery 的 TLS 配置、记录器和分布式读/写端点，以最小的开销和侵入性为管理员提供对一组设备的可见性.
* [Falcon Orchestrator](https://github.com/CrowdStrike/falcon-orchestrator) - 可扩展的基于 Windows 的应用程序，提供工作流自动化、案例管理和安全响应功能.
* [Flare](https://github.com/fireeye/flare-vm) - A fully customizable, Windows-based security distribution for malware analysis, incident response, penetration testing.
* [Fleetdm](https://github.com/fleetdm/fleet)  - 为安全专家量身定制的最先进的主机监控平台. 利用 Facebook 久经考验的 osquery 项目，Fleetdm 为重大问题提供持续更新、功能和快速答案.
* [GRR Rapid Response](https://github.com/google/grr)  - 专注于远程实时取证的事件响应框架. 它由安装在目标系统上的 python 代理（客户端）和可以管理代理并与之对话的 python 服务器基础结构组成. 除了包含的 Python API 客户端， [PowerGRR](https://github.com/swisscom/PowerGRR) 在 PowerShell 中提供 API 客户端库，可在 Windows、Linux 和 macOS 上运行，用于 GRR 自动化和脚本编写.
* [IRIS](https://github.com/dfir-iris/iris-web) - IRIS 是事件响应分析师的网络协作平台，允许在技术层面共享调查.
* [Kuiper](https://github.com/DFIRKuiper/Kuiper) - 数字取证调查平台
* [Limacharlie](https://www.limacharlie.io/) - 端点安全平台由一系列共同工作的小项目组成，为您提供一个跨平台（Windows、OSX、Linux、Android 和 iOS）的低级环境，用于管理附加模块并将其推送到内存中以扩展其功能.
* [Matano](https://github.com/matanolabs/matano)：AWS 上的开源无服务器安全湖平台，可让您将 PB 级安全数据摄取、存储和分析到 Apache Iceberg 数据湖中，并将实时 Python 检测作为代码运行.
* [MozDef](https://github.com/mozilla/MozDef) - 自动化安全事件处理过程并促进事件处理人员的实时活动.
* [MutableSecurity](https://github.com/MutableSecurity/mutablesecurity) - 用于自动设置、配置和使用网络安全解决方案的 CLI 程序.
* [nightHawk](https://github.com/biggiesmallsAG/nightHawkResponse)  - 为使用 ElasticSearch 作为后端的异步取证数据呈现而构建的应用程序. 它旨在摄取 Redline 集合.
* [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/)  - 另一个流行的分布式开源计算机取证框架. 该框架建立在 Linux 平台上，使用 postgreSQL 数据库存储数据.
* [osquery](https://osquery.io/)  - 使用类似 SQL 的查询语言轻松询问有关 Linux 和 macOS 基础架构的问题； 提供的*事件响应包*可帮助您检测和响应违规行为.
* [Redline](https://www.fireeye.com/services/freeware/redline.html) - 为用户提供主机调查功能，以通过内存和文件分析以及威胁评估配置文件的开发来发现恶意活动的迹象.
* [The Sleuth Kit & Autopsy](http://www.sleuthkit.org)  - 基于 Unix 和 Windows 的工具，有助于对计算机进行取证分析. 它带有各种有助于数字取证的工具. 这些工具有助于分析磁盘映像、对文件系统进行深入分析以及其他各种事情.
* [TheHive](https://thehive-project.org/) - 可扩展的 3 合 1 开源和免费解决方案，旨在让 SOC、CSIRT、CERT 和任何处理需要迅速调查和采取行动的安全事件的信息安全从业人员的生活更轻松.
* [Velociraptor](https://github.com/Velocidex/velociraptor) - 端点可见性和收集工具
* [X-Ways Forensics](http://www.x-ways.net/forensics/)  - 用于磁盘克隆和映像的取证工具. 它可用于查找已删除的文件和磁盘分析.
* [Zentral](https://github.com/zentralopensource/zentral)  - 将 osquery 强大的端点清单功能与灵活的通知和操作框架相结合. 这使人们能够识别 OS X 和 Linux 客户端上的更改并做出反应.

### Books

* [Applied Incident Response](https://www.amazon.com/Applied-Incident-Response-Steve-Anson/dp/1119560268/) - Steve Anson 关于事件响应的书.
* [Art of Memory Forensics](https://www.amazon.com/Art-Memory-Forensics-Detecting-Malware/dp/1118825098/) - 检测 Windows、Linux 和 Mac 内存中的恶意软件和威胁.
* [Crafting the InfoSec Playbook: Security Monitoring and Incident Response Master Plan](https://www.amazon.com/Crafting-InfoSec-Playbook-Security-Monitoring/dp/1491949406) - Jeff Bollinger、Brandon Enright 和 Matthew Valites.
* [Digital Forensics and Incident Response: Incident response techniques and procedures to respond to modern cyber threats](https://www.amazon.com/Digital-Forensics-Incident-Response-techniques/dp/183864900X) ——杰拉德·约翰森着.
* [Introduction to DFIR](https://medium.com/@sroberts/introduction-to-dfir-d35d5de4c180/) - 斯科特 J. 罗伯茨.
* [Incident Response & Computer Forensics, Third Edition](https://www.amazon.com/Incident-Response-Computer-Forensics-Third/dp/0071798684/) - 事件响应的权威指南.
* [Incident Response Techniques for Ransomware Attacks](https://www.amazon.com/Incident-Response-Techniques-Ransomware-Attacks/dp/180324044X)  - 为勒索软件攻击制定事件响应策略的绝佳指南. 通过奥列格斯库尔金.
* [Incident Response with Threat Intelligence](https://www.amazon.com/Incident-response-Threat-Intelligence-intelligence-based/dp/1801072957) - Great reference to build an incident response plan based also on Threat Intelligence. By Roberto Martinez.
* [Intelligence-Driven Incident Response](https://www.amazon.com/Intelligence-Driven-Incident-Response-Outwitting-Adversary-ebook-dp-B074ZRN5T7/dp/B074ZRN5T7) - 斯科特 J. 罗伯茨，丽贝卡布朗.
* [Operator Handbook: Red Team + OSINT + Blue Team Reference](https://www.amazon.com/Operator-Handbook-Team-OSINT-Reference/dp/B085RR67H5/) - 事件响应者的重要参考.
* [Practical Memory Forensics](https://www.amazon.com/Practical-Memory-Forensics-Jumpstart-effective/dp/1801070334)  - 练习记忆取证的权威指南. 作者：Svetlana Ostrovskaya 和 Oleg Skulkin.
* [The Practice of Network Security Monitoring: Understanding Incident Detection and Response](http://www.amazon.com/gp/product/1593275099) - Richard Bejtlich 关于 IR 的书.

### Communities

* [Digital Forensics Discord Server](https://discordapp.com/invite/JUqe9Ek)  - 来自执法部门、私营部门和法医供应商的 8,000 多名在职专业人员组成的社区. 此外，还有很多学生和爱好者！ 指导 [here](https://aboutdfir.com/a-beginners-guide-to-the-digital-forensics-discord-server/). 
* [SANS DFIR mailing list](https://lists.sans.org/mailman/listinfo/dfir) - SANS 为 DFIR 提供的邮件列表.
* [Slack DFIR channel](https://dfircommunity.slack.com) - Slack DFIR 社区频道 - [Signup here](https://start.paloaltonetworks.com/join-our-slack-community).

### Disk Image Creation Tools

* [AccessData FTK Imager](http://accessdata.com/product-download/?/support/adownloads#FTKImager)  - 取证工具，其主要目的是从任何类型的磁盘预览可恢复的数据.  FTK Imager 还可以在 32 位和 64 位系统上获取实时内存和分页文件.
* [Bitscout](https://github.com/vitaly-kamluk/bitscout)  - Vitaly Kamluk 的 Bitscout 可帮助您构建完全受信任的可定制 LiveCD/LiveUSB 映像，以用于远程数字取证（或您选择的任何其他任务）. 它应该是透明的和系统所有者可监控的、合法的、可定制的和紧凑的.
* [GetData Forensic Imager](http://www.forensicimager.com/) - 基于 Windows 的程序，它将获取、转换或验证以下常见取证文件格式之一的取证图像.
* [Guymager](http://guymager.sourceforge.net) - 在 Linux 上用于媒体采集的免费取证成像器.
* [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) - Magnet Forensics 的 ACQUIRE 允许在 Windows、Linux 和 OS X 以及移动操作系统上执行各种类型的磁盘采集.

### Evidence Collection

* [artifactcollector](https://github.com/forensicanalysis/artifactcollector) - artifactcollector 项目提供了一个在系统上收集取证文物的软件.
* [bulk_extractor](https://github.com/simsong/bulk_extractor)  - 计算机取证工具，可扫描磁盘映像、文件或文件目录并提取有用信息，而无需解析文件系统或文件系统结构. 由于忽略了文件系统结构，该程序在速度和彻底性方面与众不同.
* [Cold Disk Quick Response](https://github.com/rough007/CDQR) - 简化的解析器列表，可快速分析取证图像文件（`dd`、E01、`.vmdk` 等）并输出九份报告.
* [CyLR](https://github.com/orlikoski/CyLR) - CyLR 工具快速、安全地从具有 NTFS 文件系统的主机收集取证工件，并将对主机的影响降至最低.
* [Forensic Artifacts](https://github.com/ForensicArtifacts/artifacts) - 数字取证神器存储库
* [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - Windows Batch 脚本和 Unix Bash 脚本，用于在事件响应期间全面收集主机取证数据.
* [Live Response Collection](https://www.brimorlabs.com/tools/) - 从基于 Windows、OSX 和 \*nix 的操作系统收集易失性数据的自动化工具.
* [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - 命令行实用程序（可使用或不使用 Amazon EC2 实例）以并行化远程内存获取.
* [UAC](https://github.com/tclahr/uac) - UAC（类 Unix 工件收集器）是事件响应的实时响应收集脚本，它利用本地二进制文件和工具自动收集 AIX、Android、ESXi、FreeBSD、Linux、macOS、NetBSD、NetScaler、OpenBSD 和 Solaris系统工件.

### Incident Management

* [Catalyst](https://github.com/SecurityBrewery/catalyst) - 一个免费的 SOAR 系统，有助于自动化警报处理和事件响应流程.
* [CyberCPR](https://www.cybercpr.com) - 内置 Need-to-Know 的社区和商业事件管理工具，在处理敏感事件时支持 GDPR 合规性.
* [Cyphon](https://medevel.com/cyphon/)  - Cyphon 通过单一平台简化大量相关任务，消除了事件管理的难题. 它接收、处理和分类事件，为您的分析工作流提供一个包罗万象的解决方案——聚合数据、捆绑和优先级警报，以及授权分析师调查和记录事件.
* [CORTEX XSOAR](https://www.paloaltonetworks.com/cortex/xsoar) - Paloalto 安全编排、自动化和响应平台，具有完整的事件生命周期管理和许多集成以增强自动化.
* [DFTimewolf](https://github.com/log2timeline/dftimewolf) - 用于协调取证收集、处理和数据导出的框架.
* [DFIRTrack](https://github.com/dfirtrack/dfirtrack) - 事件响应跟踪应用程序通过具有大量受影响系统和工件的案例和任务处理一个或多个事件.
* [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR/)  - 网络安全事件管理平台的设计考虑了敏捷性和速度. 它允许轻松创建、跟踪和报告网络安全事件，并且对 CSIRT、CERT 和 SOC 等都非常有用.
* [RTIR](https://www.bestpractical.com/rtir/)  - Request Tracker for Incident Response (RTIR) 是针对计算机安全团队的首要开源事件处理系统. 我们与全球十多个 CERT 和 CSIRT 团队合作，帮助您处理不断增加的事件报告量.  RTIR 建立在 Request Tracker 的所有功能之上.
* [Sandia Cyber Omni Tracker (SCOT)](https://github.com/sandialabs/scot)  - 专注于灵活性和易用性的事件响应协作和知识捕获工具. 我们的目标是在不增加用户负担的情况下为事件响应流程增加价值.
* [Shuffle](https://github.com/frikky/Shuffle) - 一个专注于可访问性的通用安全自动化平台.
* [threat_note](https://github.com/defpoint/threat_note) - 轻量级调查笔记本，让安全研究人员能够注册和检索与其研究相关的指标.
* [Zenduty](https://www.zenduty.com) - Zenduty 是一个新颖的事件管理平台，提供端到端的事件警报、待命管理和响应编排，使团队能够更好地控制和自动化事件管理生命周期.

### Knowledge Bases

* [Digital Forensics Artifact Knowledge Base](https://github.com/ForensicArtifacts/artifacts-kb) - 数字取证神器知识库
* [Windows Events Attack Samples](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) - Windows 事件攻击示例
* [Windows Registry Knowledge Base](https://github.com/libyal/winreg-kb) - Windows 注册表知识库

### Linux Distributions

* [The Appliance for Digital Investigation and Analysis (ADIA)](https://forensics.cert.org/#ADIA)  - 基于 VMware 的设备用于数字调查和采集，完全由公共领域软件构建.  ADIA 中包含的工具包括 Autopsy、Sleuth Kit、数字取证框架、log2timeline、Xplico 和 Wireshark. 大多数系统维护使用Webmin. 它专为中小型数字调查和收购而设计. 该设备在 Linux、Windows 和 Mac OS 下运行.  i386（32 位）和 x86_64（64 位）版本均可用.
* [Computer Aided Investigative Environment (CAINE)](http://www.caine-live.net/index.html) - 包含在分析过程中帮助调查人员的众多工具，包括法医证据收集.
* [CCF-VM](https://github.com/rough007/CCF-VM) - CyLR CDQR 取证虚拟机 (CCF-VM)：用于解析收集的数据的一体化解决方案，通过内置的常用搜索使其易于搜索，可同时搜索单个和多个主机.
* [Digital Evidence & Forensics Toolkit (DEFT)](http://www.deftlinux.net/)  - 用于计算机取证收集的 Linux 发行版. 它与 Windows 的数字高级响应工具包 (DART) 捆绑在一起. 还提供名为 DEFT Zero 的轻量版 DEFT，它主要专注于法医健全的证据收集.
* [NST - Network Security Toolkit](https://sourceforge.net/projects/nst/files/latest/download?source=files) - Linux 发行版，其中包括对网络安全专业人员有用的大量同类最佳开源网络安全应用程序.
* [PALADIN](https://sumuri.com/software/paladin/)  - 修改了 Linux 发行版，以合理的方式执行各种取证任务. 它附带了许多开源取证工具.
* [Security Onion](https://github.com/Security-Onion-Solutions/security-onion) - 针对具有高级分析工具的网络安全监控的特殊 Linux 发行版.
* [SANS Investigative Forensic Toolkit (SIFT) Workstation](http://digital-forensics.sans.org/community/downloads) - 证明先进的事件响应能力和针对入侵的深入数字取证技术可以使用免费且经常更新的尖端开源工具来完成.

### Linux Evidence Collection

* [FastIR Collector Linux](https://github.com/SekoiaLab/Fastir_Collector_Linux) - FastIR for Linux 收集实时 Linux 上的不同工件并将结果记录在 CSV 文件中.

### Log Analysis Tools

* [AppCompatProcessor](https://github.com/mbevilacqua/appcompatprocessor) - AppCompatProcessor 旨在从企业范围的 AppCompat / AmCache 数据中提取超出经典堆叠和 grepping 技术的附加价值.
* [APT Hunter](https://github.com/ahmedkhlief/APT-Hunter) - APT-Hunter 是 Windows 事件日志的威胁搜寻工具.
* [Chainsaw](https://github.com/countercept/chainsaw) - Chainsaw 提供强大的“第一响应”功能，可快速识别 Windows 事件日志中的威胁.
* [Event Log Explorer](https://eventlogxp.com/) - 为快速分析日志文件和其他数据而开发的工具.
* [Event Log Observer](https://lizard-labs.com/event_log_observer.aspx) - 使用此 GUI 工具查看、分析和监控 Microsoft Windows 事件日志中记录的事件.
* [Hayabusa](https://github.com/Yamato-Security/hayabusa) - Hayabusa 是一个 Windows 事件日志快速取证时间线生成器和威胁搜寻工具，由日本 Yamato 安全组创建.
* [Kaspersky CyberTrace](https://support.kaspersky.com/13850)  - 威胁情报融合和分析工具，将威胁数据馈送与 SIEM 解决方案集成. 用户可以立即利用威胁情报在其现有安全操作的工作流程中进行安全监控和事件报告 (IR) 活动.
* [Log Parser Lizard](https://lizard-labs.com/log_parser_lizard.aspx)  - 针对结构化日志数据执行 SQL 查询：服务器日志、Windows 事件、文件系统、Active Directory、log4net 日志、逗号/制表符分隔的文本、XML 或 JSON 文件. 还为 Microsoft LogParser 2.2 提供了一个具有强大 UI 元素的 GUI：语法编辑器、数据网格、图表、数据透视表、仪表板、查询管理器等.
* [Lorg](https://github.com/jensvoid/lorg) - 用于高级 HTTPD 日志文件安全分析和取证的工具.
* [Logdissect](https://github.com/dogoncouch/logdissect) - 用于分析日志文件和其他数据的 CLI 实用程序和 Python API.
* [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - 通过可视化和分析 Windows 事件日志来调查恶意 Windows 登录的工具.
* [Sigma](https://github.com/SigmaHQ/sigma) - 已包含大量规则集的 SIEM 系统的通用签名格式.
* [StreamAlert](https://github.com/airbnb/streamalert) - 无服务器、实时日志数据分析框架，能够摄取自定义数据源并使用用户定义的逻辑触发警报.
* [SysmonSearch](https://github.com/JPCERTCC/SysmonSearch) - SysmonSearch 通过聚合事件日志使 Windows 事件日志分析更有效且耗时更少.
* [WELA](https://github.com/Yamato-Security/WELA) - Windows 事件日志分析器旨在成为 Windows 事件日志的瑞士军刀.
* [Zircolite](https://github.com/wagga40/Zircolite) - 一个独立且快速的基于 SIGMA 的 EVTX 或 JSON 检测工具.

### Memory Analysis Tools

* [AVML](https://github.com/microsoft/avml) - 适用于 Linux 的便携式易失性存储器采集工具.
* [Evolve](https://github.com/JamesHabben/evolve) - 波动性内存取证框架的 Web 界面.
* [inVtero.net](https://github.com/ShaneK2/inVtero.net) - 具有嵌套管理程序支持的 Windows x64 高级内存分析.
* [LiME](https://github.com/504ensicsLabs/LiME) - 可加载内核模块 (LKM)，它允许从 Linux 和基于 Linux 的设备（以前称为 DMD）获取易失性内存.
* [MalConfScan](https://github.com/JPCERTCC/MalConfScan)  - MalConfScan 是一个 Volatility 插件，用于提取已知恶意软件的配置数据.  Volatility 是一个用于事件响应和恶意软件分析的开源内存取证框架. 该工具在内存映像中搜索恶意软件并转储配置数据. 此外，该工具还具有列出恶意代码引用的字符串的功能.
* [Memoryze](https://www.fireeye.com/services/freeware/memoryze.html)  - 免费的内存取证软件，可帮助事件响应者在实时内存中发现邪恶.  Memoryze 可以获取和/或分析内存图像，并且在实时系统上，可以在其分析中包含页面文件.
* [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze.html)  - 适用于 Mac 的 Memoryze 是 Memoryze，但适用于 Mac. 但是，功能数量较少.
* [Orochi](https://github.com/LDO-CERT/orochi) - Orochi 是一个用于协作取证内存转储分析的开源框架.
* [Rekall](http://www.rekall-forensic.com/) - 用于从易失性存储器 (RAM) 样本中提取数字伪影的开源工具（和库）.
* [Responder PRO](http://www.countertack.com/responder-pro) - Responder PRO 是行业标准的物理内存和自动化恶意软件分析解决方案.
* [Volatility](https://github.com/volatilityfoundation/volatility) - 高级内存取证框架.
* [Volatility 3](https://github.com/volatilityfoundation/volatility3) - 易失性内存提取框架（Volatility 的继承者）
* [VolatilityBot](https://github.com/mkorman90/VolatilityBot) - 研究人员的自动化工具将所有猜测和手动任务从二进制提取阶段中剔除，或帮助研究人员进行内存分析调查的第一步.
* [VolDiff](https://github.com/aim4r/VolDiff) - 基于波动性的恶意软件内存占用分析.
* [WindowsSCOPE](http://www.windowsscope.com/windowsscope-cyber-forensics/) - 用于分析易失性内存的内存取证和逆向工程工具，提供分析 Windows 内核、驱动程序、DLL 以及虚拟和物理内存的能力.

### Memory Imaging Tools

* [Linux Memory Grabber](https://github.com/halpomeranz/lmg/) - 用于转储 Linux 内存和创建波动率配置文件的脚本.
* [Magnet RAM Capture](https://www.magnetforensics.com/free-tool-magnet-ram-capture/)  - 旨在捕获嫌疑人计算机物理内存的免费成像工具. 支持最新版本的 Windows.
* [OSForensics](http://www.osforensics.com/)  - 在 32 位和 64 位系统上获取实时内存的工具. 可以转储单个进程的内存空间或物理内存转储.

### OSX Evidence Collection

* [Knockknock](https://objective-see.com/products/knockknock.html) - 显示设置为在 OSX 上自动执行的持久项目（脚本、命令、二进制文件等）.
* [macOS Artifact Parsing Tool (mac_apt)](https://github.com/ydkhatri/mac_apt) - 基于插件的取证框架，用于在实时机器、磁盘映像或单个工件文件上工作的快速 mac 分类.
* [OSX Auditor](https://github.com/jipegit/OSXAuditor) - 免费的 Mac OS X 计算机取证工具.
* [OSX Collector](https://github.com/yelp/osxcollector) - 用于实时响应的 OSX Auditor 分支.
* [The ESF Playground](https://themittenmac.com/the-esf-playground/) - 实时查看 Apple Endpoint Security Framework (ESF) 中事件的工具.

### Other Lists

* [Awesome Event IDs](https://github.com/stuhli/awesome-event-ids) - 收集对数字取证和事件响应有用的事件 ID 资源.
* [Awesome Forensics](https://github.com/cugu/awesome-forensics) - 精选的法医分析工具和资源列表.
* [Didier Stevens Suite](https://github.com/DidierStevens/DidierStevensSuite) - 工具集合
* [Eric Zimmerman Tools](https://ericzimmerman.github.io/) - 由 SANS 研究所讲师 Eric Zimmerman 创建的法医工具更新列表.
* [List of various Security APIs](https://github.com/deralexxx/security-apis) - 用于安全的公共 JSON API 的集合列表.

### Other Tools

* [Cortex](https://thehive-project.org)  - Cortex 允许您使用 Web 界面一一分析或以批量模式分析可观察数据，例如 IP 和电子邮件地址、URL、域名、文件或哈希值. 分析师还可以使用其 REST API 自动执行这些操作.
* [Crits](https://crits.github.io/) - 基于网络的工具，将分析引擎与网络威胁数据库相结合.
* [Diffy](https://github.com/Netflix-Skunkworks/diffy) - 由 Netflix 的 SIRT 开发的 DFIR 工具，允许调查人员在事件期间快速确定跨云实例（目前是 AWS 上的 Linux 实例）的妥协范围，并通过显示与基线的差异来有效地对这些实例进行分类以采取后续行动.
* [domfind](https://github.com/diogo-fernan/domfind) - 用于在不同 TLD 下查找相同域名的 Python DNS 爬虫.
* [Fileintel](https://github.com/keithjjones/fileintel) - 提取每个文件哈希的智能.
* [HELK](https://github.com/Cyb3rWard0g/HELK) - 威胁狩猎平台.
* [Hindsight](https://github.com/obsidianforensics/hindsight) - Google Chrome/Chromium 的互联网历史取证.
* [Hostintel](https://github.com/keithjjones/hostintel) - 提取每个主机的情报.
* [imagemounter](https://github.com/ralphje/imagemounter) - 命令行实用程序和 Python 包，以简化取证磁盘映像的（卸载）安装.
* [Kansa](https://github.com/davehull/Kansa/) - PowerShell 中的模块化事件响应框架.
* [MFT Browser](https://github.com/kacos2000/MFT_Browser) - MFT 目录树重建和记录信息.
* [Munin](https://github.com/Neo23x0/munin) - VirusTotal 和其他服务的在线哈希检查器.
* [PowerSponse](https://github.com/swisscom/PowerSponse) - PowerSponse 是一个 PowerShell 模块，专注于在安全事件响应期间进行有针对性的遏制和补救.
* [PyaraScanner](https://github.com/nogoodconfig/pyarascanner) - 非常简单的多线程多规则多文件 YARA 扫描恶意软件动物园和 IR 的 Python 脚本.
* [rastrea2r](https://github.com/rastrea2r/rastrea2r) - 允许在 Windows、Linux 和 OS X 上使用 YARA 扫描磁盘和内存以查找 IOC.
* [RaQet](https://raqet.github.io/) - 非常规的远程采集和分类工具，允许对使用专门构建的取证操作系统重新启动的远程计算机（客户端）的磁盘进行分类.
* [Raccine](https://github.com/Neo23x0/Raccine) - 一个简单的勒索软件保护
* [Stalk](https://www.percona.com/doc/percona-toolkit/2.2/pt-stalk.html) - 出现问题时收集有关 MySQL 的取证数据.
* [Scout2](https://nccgroup.github.io/Scout2/) - 可让 Amazon Web Services 管理员评估其环境的安全状况的安全工具.
* [Stenographer](https://github.com/google/stenographer)  - 数据包捕获解决方案，旨在快速将所有数据包假脱机到磁盘，然后提供对这些数据包子集的简单、快速访问. 它存储尽可能多的历史记录，管理磁盘使用情况，并在达到磁盘限制时删除. 它非常适合在事件之前和期间捕获流量，而无需明确需要存储所有网络流量.
* [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config) - 具有默认高质量事件跟踪的 Sysmon 配置文件模板
* [sysmon-modular](https://github.com/olafhartong/sysmon-modular) - A repository of sysmon configuration modules
* [traceroute-circl](https://github.com/CIRCL/traceroute-circl)  - 扩展跟踪路由以支持 CSIRT（或 CERT）操作员的活动. 通常 CSIRT 团队必须根据收到的 IP 地址来处理事件. 由卢森堡计算机应急响应中心创建.
* [X-Ray 2.0](https://www.raymond.cc/blog/xray/) - 用于向 AV 供应商提交病毒样本的 Windows 实用程序（维护不善或不再维护）.

### Playbooks

* [AWS Incident Response Runbook Samples](https://github.com/aws-samples/aws-incident-response-runbooks/tree/0d9a1c0f7ad68fb2c1b2d86be8914f2069492e21)  - AWS IR Runbook 示例旨在为每个使用它们的实体进行定制. 这三个样本是：“DoS 或 DDoS 攻击”、“凭证泄露”和“对 Amazon S3 存储桶的意外访问”.
* [Counteractive Playbooks](https://github.com/counteractive/incident-response-plan-template/tree/master/playbooks) - 反作用的剧本收藏.
* [GuardSIght Playbook Battle Cards](https://github.com/guardsight/gsvsoc_cirt-playbook-battle-cards) - 一系列网络事件响应手册战斗卡
* [IRM](https://github.com/certsocietegenerale/IRM) - CERT 法国兴业银行的事件响应方法.
* [IR Workflow Gallery](https://www.incidentresponse.org/playbooks/)  - 不同的通用事件响应工作流程，例如恶意软件爆发、数据盗窃、未经授权的访问……每个工作流程都包含七个步骤：准备、检测、分析、遏制、根除、恢复、事件后处理. 工作流程可在线获取或下载.
* [PagerDuty Incident Response Documentation](https://response.pagerduty.com/)  - 描述 PagerDuty 事件响应流程部分的文件. 它不仅提供了有关准备事件的信息，还提供了在事件发生期间和之后应该做什么的信息. 来源可在 [GitHub](https://github.com/PagerDuty/incident-response-docs).
* [Phantom Community Playbooks](https://github.com/phantomcyber/playbooks) - 用于 Splunk 的 Phantom 社区手册，但也可针对其他用途进行定制.
* [ThreatHunter-Playbook](https://github.com/OTRF/ThreatHunter-Playbook) - 帮助开发狩猎活动的技术和假设的剧本.

### Process Dump Tools

* [Microsoft ProcDump](https://docs.microsoft.com/en-us/sysinternals/downloads/procdump) - 动态转储任何正在运行的 Win32 进程内存映像.

### Sandboxing/Reversing Tools

* [AMAaaS](https://amaaas.com/index.php/AMAaaS/dashboard) - Android 恶意软件分析即服务，在原生 Android 环境中执行.
* [Any Run](https://app.any.run/) - 交互式在线恶意软件分析服务，用于使用任何环境对大多数类型的威胁进行动态和静态研究.
* [CAPEv2](https://github.com/kevoreilly/CAPEv2) - 恶意软件配置和有效负载提取.
* [Cuckoo](https://github.com/cuckoosandbox/cuckoo) - 开源高度可配置的沙盒工具.
* [Cuckoo-modified](https://github.com/spender-sandbox/cuckoo-modified) - 由社区开发的经过大量修改的 Cuckoo 分叉.
* [Cuckoo-modified-api](https://github.com/keithjjones/cuckoo-modified-api) - 控制杜鹃修改沙箱的 Python 库.
* [Cutter](https://github.com/radareorg/cutter) - 由Radare2提供支持的逆向工程平台.
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - 软件逆向工程框架.
* [Hybrid-Analysis](https://www.hybrid-analysis.com/) - CrowdStrike 提供的免费强大的在线沙盒.
* [Intezer](https://analyze.intezer.com/#/) - Intezer Analyze 深入 Windows 二进制文件以检测与已知威胁的微代码相似性，以提供准确且易于理解的结果.
* [Joe Sandbox (Community)](https://www.joesandbox.com/)  - Joe Sandbox 检测和分析 Windows、Android、Mac OS、Linux 和 iOS 上的潜在恶意文件和 URL 以查找可疑活动； 提供全面详细的分析报告.
* [Mastiff](https://github.com/KoreLogicSecurity/mastiff) - 静态分析框架，可自动从多种不同文件格式中提取关键特征.
* [Metadefender Cloud](https://www.metadefender.com) - 免费威胁情报平台，提供文件的多重扫描、数据清理和漏洞评估.
* [Radare2](https://github.com/radareorg/radare2) - 逆向工程框架和命令行工具集.
* [Reverse.IT](https://www.reverse.it/) - CrowdStrike 提供的混合分析工具的替代域.
* [Rizin](https://github.com/rizinorg/rizin) - 类 UNIX 逆向工程框架和命令行工具集
* [StringSifter](https://github.com/fireeye/stringsifter) - 一种机器学习工具，可根据字符串与恶意软件分析的相关性对字符串进行排名.
* [Threat.Zone](https://app.threat.zone) - 基于云的威胁分析平台，包括沙箱、CDR 和研究人员的交互式分析. 
* [Valkyrie Comodo](https://valkyrie.comodo.com) - Valkyrie 使用运行时行为和文件中的数百个特征来执行分析.
* [Viper](https://github.com/viper-framework/viper) - 基于 Python 的二进制分析和管理框架，适用于 Cuckoo 和 YARA.
* [Visualize_Logs](https://github.com/keithjjones/visualize_logs) - 用于日志的开源可视化库和命令行工具（Cuckoo、Procmon 等）.
* [Yomi](https://yomi.yoroi.company) - 由 Yoroi 管理和托管的免费 MultiSandbox.

### Scanner Tools

* [Fenrir](https://github.com/Neo23x0/Fenrir)  - 简单的 IOC 扫描仪. 它允许在普通 bash 中扫描任何 Linux/Unix/OSX 系统的 IOC. 由 THOR 和 LOKI 的创造者创建.
* [LOKI](https://github.com/Neo23x0/Loki) - 免费的 IR 扫描仪，用于使用 yara 规则和其他指标 (IOC) 扫描端点.
* [Spyre](https://github.com/spyre-project/spyre) - 用 Go 编写的简单的基于 YARA 的 IOC 扫描仪

### Timeline Tools

* [Aurora Incident Response](https://github.com/cyb3rfox/Aurora-Incident-Response) - Platform developed to build easily a detailed timeline of an incident.
* [Highlighter](https://www.fireeye.com/services/freeware/highlighter.html)  - Fire/Mandiant 提供的免费工具，它将描述日志/文本文件，可以突出显示图形上与关键字或短语相对应的区域. 有利于确定感染的时间以及妥协后所做的事情.
* [Morgue](https://github.com/etsy/morgue) - Etsy 的 PHP Web 应用程序，用于管理事后分析.
* [Plaso](https://github.com/log2timeline/plaso) - 用于工具 log2timeline 的基于 Python 的后端引擎.
* [Timesketch](https://github.com/google/timesketch) - 用于协作取证时间线分析的开源工具.

### Videos

* [The Future of Incident Response](https://www.youtube.com/watch?v=bDcx4UNpKNc) - Bruce Schneier 在 OWASP AppSecUSA 2015 上发表.

### Windows Evidence Collection

* [AChoir](https://github.com/OMENScan/AChoir) - 框架/脚本工具，用于标准化和简化 Windows 实时采集实用程序的脚本编写过程.
* [Crowd Response](http://www.crowdstrike.com/community-tools/)  - 轻量级 Windows 控制台应用程序，旨在帮助收集系统信息以进行事件响应和安全参与. 它具有众多模块和输出格式.
* [DFIR ORC](https://dfir-orc.github.io/)  - DFIR ORC 是一组专门用于可靠解析和收集关键工件（如 MFT、注册表配置单元或事件日志）的专用工具.  DFIR ORC 收集数据，但不对其进行分析：它并不意味着对机器进行分类. 它提供了运行 Microsoft Windows 的机器的取证相关快照. 代码可以在 [GitHub](https://github.com/DFIR-ORC/dfir-orc).
* [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector)  - 在实时 Windows 系统上收集不同工件并将结果记录在 csv 文件中的工具. 通过对这些工件的分析，可以检测到早期的危害.
* [Fibratus](https://github.com/rabbitstack/fibratus) - 用于探索和跟踪 Windows 内核的工具.
* [Hoarder](https://github.com/muteb/Hoarder) - 为取证或事件响应调查收集最有价值的文物.
* [IREC](https://binalyze.com/products/irec-free/)  - 多合一的 IR 证据收集器，可捕获 RAM 映像、$MFT、事件日志、WMI 脚本、注册表配置单元、系统还原点等等. 它是免费的，闪电般快速且易于使用.
* [Invoke-LiveResponse](https://github.com/mgreen27/Invoke-LiveResponse) - Invoke-LiveResponse 是一个针对目标收集的实时响应工具.
* [IOC Finder](https://www.fireeye.com/services/freeware/ioc-finder.html)  - Mandiant 提供的免费工具，用于收集主机系统数据并报告入侵指标 (IOC) 的存在. 仅支持 Windows. 不再维护. 仅完全支持 Windows 7 / Windows Server 2008 R2.
* [IRTriage](https://github.com/AJMartel/IRTriage) - 事件响应分类 - 用于取证分析的 Windows 证据收集.
* [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)  - Eric Zimmerman 的 Kroll Artifact Parser and Extractor (KAPE). 一种分类工具，可以找到最流行的数字工件，然后快速解析它们. 当时间至关重要时，伟大而彻底.  
* [LOKI](https://github.com/Neo23x0/Loki) - 免费的 IR 扫描仪，用于使用 yara 规则和其他指标 (IOC) 扫描端点.
* [MEERKAT](https://github.com/TonyPhipps/Meerkat) - 适用于 Windows 的基于 PowerShell 的分类和威胁搜寻.
* [Panorama](https://github.com/AlmCo/Panorama) - 实时 Windows 系统上的快速事件概览.
* [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - Live disk forensics platform, using PowerShell.
* [PSRecon](https://github.com/gfoss/PSRecon/)  - PSRecon 使用 PowerShell（v2 或更高版本）从远程 Windows 主机收集数据，将数据组织到文件夹中，对所有提取的数据进行哈希处理，对 PowerShell 和各种系统属性进行哈希处理，并将数据发送给安全团队. 数据可以推送到共享、通过电子邮件发送或在本地保留.
* [RegRipper](https://github.com/keydet89/RegRipper3.0) - 用 Perl 编写的开源工具，用于从注册表中提取/解析信息（键、值、数据）并将其呈现以供分析.
