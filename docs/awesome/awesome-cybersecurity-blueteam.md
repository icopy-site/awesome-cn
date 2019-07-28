<div class="github-widget" data-repo="meitar/awesome-cybersecurity-blueteam"></div>
## Awesome Cybersecurity Blue Team [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

&gt;为网络安全蓝队提供了一系列精彩的资源，工具和其他闪亮的东西.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security) ）是识别信息技术系统中的安全缺陷，验证安全措施的有效性以及监控系统以确保实施的防御措施在未来仍然有效的个人群体.  虽然不是排他性的，但这个列表却严重偏向于 [Free Software](https://www.gnu.org/philosophy/free-sw.html)  项目和反对专有产品或公司服务.  对于攻击性TTP，请参阅 [awesome-pentest](https://github.com/meitar/awesome-pentest).

 您的贡献和建议是衷心的♥欢迎.  （✿◕‿◕）.  请检查 [Contributing Guidelines](https://github.com/meitar/awesome-cybersecurity-blueteam/blob/master/CONTRIBUTING.md)  更多细节.  这项工作是根据a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).



## Automation

- [Autosnort](https://github.com/da667/Autosnort) - 一系列bash shell脚本，旨在在各种Linux发行版上安装功能齐全，完全更新的独立snort传感器和您选择的IDS事件审查控制台.
- [DShell](https://github.com/USArmyResearchLab/Dshell) - 用Python编写的可扩展网络取证分析框架，可以快速开发插件，以支持解析网络数据包捕获.
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) -  VirusTotal.com API的PowerShell接口.
- [censys-python](https://github.com/censys/censys-python) -  Censys REST API的Python包装器.
- [python-dshield](https://github.com/rshipp/python-dshield) -  Internet Storm Center / DShield API的Pythonic接口.
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) - 用于构建与恶意软件沙箱的集成的最小，一致的Python API.
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) - 用于序列化和反序列化结构化威胁信息eXpression（STIX）JSON内容的Python API，以及用于常见任务的更高级API.
- [libcrafter](https://github.com/pellegre/libcrafter) - 高级C ++网络数据包嗅探和制作库.

## Communications security (COMSEC)

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) - 在组织或团队的所有成员之间集中和自动化OpenPGP公钥分发，撤销和更新.

## DevSecOps

也可以看看 [awesome-devsecops](https://github.com/devsecops/awesome-devsecops).

- [BlackBox](https://github.com/StackExchange/blackbox) - 通过使用GnuPG“静止”加密它们，安全地将秘密存储在Git / Mercurial / Subversion中.
- [Cilium](https://cilium.io/) - 开源软件，用于透明地保护使用Docker和Kubernetes等Linux容器管理平台部署的应用程序服务之间的网络连接.
- [Clair](https://github.com/coreos/clair) - 静态分析工具，用于探测通过应用程序容器（例如Docker）映像引入的漏洞.
- [Gauntlt](http://gauntlt.org/) - 在常规持续集成期间使用Pentest应用程序构建管道.
- [Git Secrets](https://github.com/awslabs/git-secrets) - 防止您将密码和其他敏感信息提交给git存储库.
- [Prowler](https://github.com/toniblyx/prowler) - Tool based on AWS-CLI commands for Amazon Web Services account security assessment and hardening.
- [Vault](https://www.vaultproject.io/) - 通过统一界面安全访问API密钥，密码或证书等秘密的工具.
- [git-crypt](https://www.agwa.name/projects/git-crypt/)   -  git中的透明文件加密;  您选择保护的文件在提交时会加密，在签出时会被解密.
- [SonarQube](https://sonarqube.org) - 连续检查工具，可在自动化测试期间提供详细报告，并对新引入的安全漏洞发出警报.

### Fuzzing

See [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

## Honeypots

也可以看看 [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens)   - 自助式蜜语发电机和报告仪表板;  演示版可在 [CanaryTokens.org](https://canarytokens.org/).

### Tarpits

- [Endlessh](https://github.com/skeeto/endlessh) -  SSH tarpit，慢慢发送无尽的横幅.
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - 响应未使用IP空间的ARP请求的程序，创建假机器的外观，可以非常缓慢地响应进一步的请求，以减慢扫描程序，蠕虫等速度.

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) - 组合蜜罐，文件系统监视器和警报系统，旨在保护Linux和Windows操作系统.
- [chkrootkit](http://chkrootkit.org/) - 在GNU / Linux系统上本地检查rootkit的标志.
- [Fail2ban](https://www.fail2ban.org/) - 入侵防御软件框架，保护计算机服务器免受暴力攻击.
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) - 完全开源和免费，功能丰富的基于主机的入侵检测系统（HIDS）.
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) - 符合POSIX标准的Bash脚本，用于扫描主机是否存在各种恶意软件迹象.

### Sandboxes

- [Firejail](https://firejail.wordpress.com/) -  SUID程序通过使用Linux命名空间和seccomp-bpf限制不受信任的应用程序的运行环境来降低安全漏洞的风险.

## Incident Response tools

也可以看看 [awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [aws_ir](https://github.com/ThreatResponse/aws_ir) - 通过零安全准备假设自动化您的事件响应.

### IR management consoles

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) - 基于Viper构建的可编写脚本的数字取证和事件响应（DFIR）工具包.
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) - 网络安全事件管理平台，可轻松创建，跟踪和报告网络安全事件.
- [Rekall](http://www.rekall-forensic.com/) - 先进的取证和事件响应框架.
- [TheHive](https://thehive-project.org/) - 可扩展，免费的安全事件响应平台，旨在使SOC，CSIRT和CERT的生活更轻松，与MISP紧密集成.
- [threat_note](https://github.com/defpoint/threat_note) - 由Defense Point Security构建的Web应用程序，使安全研究人员能够添加和检索与其研究相关的指标.

### Evidence collection

- [AutoMacTC](https://github.com/CrowdStrike/automactc) - 模块化，自动化的取证分类收集框架，旨在访问macOS上的各种取证工件，解析它们，并以可用于分析的格式呈现它们.
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) - 免费macOS计算机取证工具.
- [OSXCollector](https://github.com/Yelp/osxcollector) - 针对macOS的法证证据收集和分析工具包.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -  Windows批处理脚本和Unix Bash脚本，用于在事件响应期间全面收集主机取证数据.
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - 命令行实用程序（与或不与Amazon EC2实例一起使用）以并行化远程内存获取.

### Threat hunting

（也称为* hunt teaming *和*威胁检测*.）

也可以看看 [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) - 基于CIM / WMI的工具套件，支持所有Windows版本的远程事件响应和搜索操作.
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) -  PowerShell模块，用于通过Windows事件日志进行搜索组合.
- [GRR Rapid Response](https://github.com/google/grr) - 事件响应框架侧重于远程实时取证，包括安装在资产上的Python代理和基于Python的服务器基础架构，使分析人员能够快速分类攻击并远程执行分析.
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) - 基于Elasticsearch，Logstash，Kafka和Kibana的一体化自由软件威胁搜索堆栈，包括各种内置的分析集成，包括Jupyter Notebook.
- [Mozilla InvestiGator (MIG)](https://mig.mozilla.org/) - 在远程终端上进行调查手术的平台.
- [PSHunt](https://github.com/Infocyte/PSHunt) -  PowerShell模块，旨在扫描远程端点以获取危害指示，或者对其进行调查，以获取与这些系统状态相关的更全面的信息.
- [PSRecon](https://github.com/gfoss/PSRecon) - 类似PSHunt的工具，用于分析远程Windows系统，该工具还可生成其结果的自包含HTML报告.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 基于PowerShell的平台，可执行实时硬盘取证分析.
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) - 多平台工具，可同时在许多端点上对可疑IOC进行分类，并与防病毒控制台集成.
- [Redline](https://www.fireeye.com/services/freeware/redline.html) -  FireEye公司提供的免费端点审计和分析工具，提供基于主机的调查功能.
- [Scout2](https://github.com/nccgroup/Scout2) - 安全工具，可让Amazon Web Services管理员评估其环境的安全状况.

## Network Security Monitoring (NSM)

也可以看看 [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [Bro](https://www.bro.org/) - 强大的网络分析框架，侧重于安全监控.
- [ChopShop](https://github.com/MITRECND/chopshop) - 帮助分析师创建和执行基于pynids的解码器和APT行业探测器的框架.
- [Maltrail](https://github.com/stamparm/maltrail) - 恶意网络流量检测系统.
- [Respounder](https://github.com/codeexpress/respounder) - 检测网络上响应者LLMNR / NBT-NS / MDNS中毒的存在.
- [Security Monkey](https://github.com/Netflix/security_monkey) - 监控您的AWS和GCP帐户，以了解有关不安全配置的策略更改和警报.
- [Snort](https://snort.org/) - 广泛部署的自由软件IPS，能够进行实时数据包分析，流量记录和基于规则的自定义触发器.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) - 捕获欺骗性NetBIOS名称服务（NBNS）响应并警告电子邮件或日志文件.
- [Suricata](https://suricata-ids.org/) - 免费，跨平台，IDS / IPS，具有在线和离线分析模式以及深度数据包检测功能，这些功能也可与Lua一起编写脚本.
- [Wireshark](https://www.wireshark.org) - 免费和开源数据包分析器，可用于网络故障排除或取证网络流分析.
- [netsniff-ng](http://netsniff-ng.org/) - 免费且快速的GNU / Linux网络工具包，具有许多实用程序，如连接跟踪工具（`flowtop`），流量生成器（`trafgen`）和自治系统（AS）跟踪路由实用程序（`astraceroute`）.

## Network perimeter defenses

- [fwknop](https://www.cipherdyne.org/fwknop/) - 通过防火墙中的单数据包授权保护端口.
- [ssh-audit](https://github.com/arthepsy/ssh-audit.git) - 简单的工具，可以快速建议改善SSH服务器的安全状态.

### Firewall appliances or distributions

- [OPNsense](https://opnsense.org/) - 基于FreeBSD的防火墙和路由平台.
- [pfSense](https://www.pfsense.org/) - 防火墙和路由器FreeBSD分发.

## Operating System distributions

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) - 意大利GNU / Linux实时发布，预先打包许多数字取证和证据收集工具.
- [Security Onion](https://securityonion.net/) - 用于入侵检测，企业安全监控和日志管理的免费和开源GNU / Linux发行版.

## Phishing awareness and reporting

也可以看看 [awesome-pentest § Social Engineering Tools](https://github.com/meitar/awesome-pentest#social-engineering-tools).

- [Gophish](https://getgophish.com/) - 强大的开源网络钓鱼框架，可以轻松测试您的组织的网络钓鱼风险.
- [King Phisher](https://github.com/securestate/king-phisher) - 通过模拟真实世界的网络钓鱼攻击来测试和提升用户意识的工具.
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) -  Outlook加载项用于帮助您的用户向安全团队报告可疑电子邮件.
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) - 允许创建和管理（虚假）网络钓鱼活动的平台，旨在培训人们识别可疑邮件. 

## Preparedness training and wargaming

（也称为*对手仿真*，*威胁模拟*或类似.）

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) - 使系统看起来好像是APT攻击受害者的工具集.
- [Atomic Red Team](https://atomicredteam.io/) - 用于测试安全控制的简单自动化测试库.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - 模块化，菜单驱动，跨平台工具，用于为Blue Team演习和传感器/警报映射构建可重复，延时，分布式安全事件.
- [Metta](https://github.com/uber-common/metta) - 自动化信息安全准备工具，用于进行对抗性模拟.
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) - 用于生成恶意网络流量并帮助安全团队评估安全控制并审核其网络可见性的实用程序.
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) - 基于Ubuntu的开放虚拟设备（`.ova`）预先配置了几个威胁仿真工具以及一个防御工具包.

## Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - 由AlienVault Open Threat Exchange（OTX）驱动的单服务器开源SIEM平台，具有资产发现，资产清点，行为监控和事件关联功能.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) - 具有悠久历史的开源无代理SIEM和多种商业变体，包括安全事件收集，规范化以及来自任意日志输入和众多流行监控工具的警报.

## Service and performance monitoring

也可以看看 [awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) - 模块化重新设计Nagios，具有可插拔的用户界面和一组扩展的数据连接器，收集器和报告工具.
- [Nagios](https://nagios.org) - 流行的网络和服务监控解决方案和报告平台.
- [OpenNMS](https://opennms.org/) - 免费且功能丰富的网络监控系统，支持多种配置，各种警报机制（电子邮件，XMPP，SMS）和众多数据收集方法（SNMP，HTTP，JDBC等）.
- [osquery](https://github.com/facebook/osquery) - 用于macOS，Windows和Linux的操作系统检测框架，将操作系统公开为高性能关系数据库，可以使用类似SQL的语法进行查询.

## Threat intelligence

也可以看看 [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths)   - 可视化和绘制Active Directory权限配置（“控制关系”）以审核诸如“谁可以阅读CEO的电子邮件？”之类的问题.  和类似的.
- [DATA](https://github.com/hadojae/DATA) - 凭证网络钓鱼分析和自动化工具，可以直接接收可疑的网络钓鱼URL或触发包含此类URL的观察到的网络流量.
- [Forager](https://github.com/opensourcesec/Forager) - 使用Python3构建的多线程威胁情报收集功能，具有简单的基于文本的配置和数据存储，易于使用和数据可移植性.
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) - 通过被动映射，计算和报告您的ICS / SCADA网络拓扑和端点，提供工业控制系统（ICS）和监控和数据采集（SCADA）的IP网络态势感知.
- [MLSec Combine](https://github.com/mlsecproject/combine) - Gather and combine multiple threat intelligence feed sources into one customizable, standardized CSV-based format.
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) - 用于收集，存储，分发和共享网络安全指标的开源软件解决方案.
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) - 可扩展的工具，用于从威胁源（包括Twitter，RSS源或其他来源）中提取和聚合IOC.
- [Unfetter](https://nsacyber.github.io/unfetter/) - 利用Mitre的ATT和CK框架，确定安全状况的防御性差距.
- [Viper](https://github.com/viper-framework/viper) - 二进制分析和管理框架，可轻松组织恶意软件并利用样本.

## Tor Onion service defenses

也可以看看 [awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) - 提供负载平衡，同时通过消除单点故障，使Onion服务更具弹性和可靠性.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - 版本3洋葱服务保护发现攻击缓解脚本（最终包含在Tor核心中）.

## Transport-layer defenses

- [Certbot](https://certbot.eff.org/) - 免费工具，自动发布和更新TLS证书 [LetsEncrypt Root CA](https://letsencrypt.org/) 使用配置各种Web和电子邮件服务器软件的插件.
- [MITMEngine](https://github.com/cloudflare/mitmengine) - 用于服务器端检测TLS拦截事件的Golang库.
- [OpenVPN](https://openvpn.net/) - 开源，基于SSL / TLS的虚拟专用网络（VPN）.
- [Tor](https://torproject.org/) - 审查规避和匿名覆盖网络，提供分布式，加密验证的名称服务（`.onion`域名），以增强发布者的隐私和服务可用性.

## macOS-based defenses

* [macOS Fortress](https://github.com/essandess/macOS-Fortress) - 自动配置内核级，操作系统级和客户端级安全功能，包括为macOS进行私有化代理和防病毒扫描.
* [Stronghold](https://github.com/alichtman/stronghold) - 从终端轻松配置macOS安全设置.

## Windows-based defenses

也可以看看 [awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security) 和 [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening).

- [HardenTools](https://github.com/securitywithoutborders/hardentools) - 禁用许多有风险的Windows功能的实用程序.
- [NotRuler](https://github.com/sensepost/notruler) - 检测客户端规则和使用的VBScript启用表单 [Ruler](https://github.com/sensepost/ruler) 尝试破坏Microsoft Exchange服务器时的攻击工具.
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - 针对Microsoft的审核Windows主机的根证书存储区 [Certificate Trust List (CTL)](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview).
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) - 从主机名列表中建立Windows RDP会话，并扫描可访问性工具后门，并在发现后门时发出警报.
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) - 组策略对象，合规性检查和配置工具，为安全部署和维护最新版本的Windows 10提供自动且灵活的方法.
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) - 将新创建的WMI使用者和进程记录到Windows应用程序事件日志中.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

这项工作是根据a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
