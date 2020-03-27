<div class="github-widget" data-repo="meitar/awesome-cybersecurity-blueteam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cybersecurity Blue Team [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

&gt;为网络安全蓝队提供了很棒的资源，工具和其他令人眼前一亮的东西.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security) ）是一群人，他们识别信息技术系统中的安全漏洞，验证安全措施的有效性并监视系统，以确保已实施的防御措施在将来仍然有效.  虽然不是排他性的，但此列表在很大程度上偏向于 [Free Software](https://www.gnu.org/philosophy/free-sw.html)  项目，并反对专有产品或公司服务.  有关攻击性TTP，请参阅 [awesome-pentest](https://github.com/meitar/awesome-pentest).

 衷心欢迎您的贡献和建议♥.  （✿◕‿◕）.  请检查 [Contributing Guidelines](https://github.com/meitar/awesome-cybersecurity-blueteam/blob/master/CONTRIBUTING.md)  更多细节.  这项工作是根据 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).



## Automation

- [Ansible Lockdown](https://ansiblelockdown.io/) -精心搜集经过审查并积极维护的以信息安全为主题的Ansible角色.
- [Clevis](https://github.com/latchset/clevis) -用于自动解密的可插入框架，通常用作Tang客户端.
- [Dev-Sec.io](https://dev-sec.io/) -服务器强化框架，提供各种基准安全性配置的Ansible，Chef和Puppet实现.
- [DShell](https://github.com/USArmyResearchLab/Dshell) -用Python编写的可扩展网络取证分析框架，可快速开发插件以支持剖析网络数据包捕获.
- [MultiScanner](https://github.com/mitre/multiscanner) -用Python编写的文件分析框架，可通过自动针对它们运行一套工具并汇总输出来帮助评估一组文件.
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) -VirusTotal.com API的PowerShell接口.
- [censys-python](https://github.com/censys/censys-python) -Censys REST API的Python包装器.
- [libcrafter](https://github.com/pellegre/libcrafter) -高级C ++网络数据包嗅探和制作库.
- [peepdf](https://eternal-todo.com/tools/peepdf-pdf-analysis-tool) -可编写脚本的PDF文件分析器.
- [python-dshield](https://github.com/rshipp/python-dshield) -Internet风暴中心/ DShield API的Pythonic接口.
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) -用于构建与恶意软件沙箱集成的最小，一致的Python API.
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) -用于序列化和反序列化结构化威胁信息表达（STIX）JSON内容的Python API，以及用于常见任务的高级API.

## Cloud platform security

也可以看看 [asecure.cloud/tools](https://asecure.cloud/tools/).

- [Checkov](https://www.checkov.io/) -Terraform的静态分析（以基础结构作为代码），有助于检测CIS策略违规并防止云安全配置错误.
- [Prowler](https://github.com/toniblyx/prowler) -基于AWS-CLI命令的工具，用于Amazon Web Services帐户安全性评估和强化.
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) -开源的多云安全审核工具，可对云环境进行安全状态评估.

## Communications security (COMSEC)

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) -在组织或团队的所有成员之间集中和自动化OpenPGP公钥分发，吊销和更新.

## DevSecOps

也可以看看 [awesome-devsecops](https://github.com/devsecops/awesome-devsecops).

- [BlackBox](https://github.com/StackExchange/blackbox) -通过使用GnuPG对其进行“静态”加密，将秘密安全地存储在Git / Mercurial / Subversion中.
- [Cilium](https://cilium.io/) -开源软件，用于透明保护使用Docker和Kubernetes等Linux容器管理平台部署的应用程序服务之间的网络连接.
- [Clair](https://github.com/coreos/clair) -静态分析工具，用于探测通过应用程序容器（例如Docker）映像引入的漏洞.
- [Gauntlt](http://gauntlt.org/) -在常规连续集成过程中的Pentest应用程序构建管道.
- [Git Secrets](https://github.com/awslabs/git-secrets) -防止您将密码和其他敏感信息提交到git存储库.
- [Vault](https://www.vaultproject.io/) -通过统一界面安全访问API密钥，密码或证书等机密的工具.
- [git-crypt](https://www.agwa.name/projects/git-crypt/)  -git中的透明文件加密；  您选择保护的文件在提交时会加密，而在签出时会解密.
- [Snyk](https://snyk.io/) -查找并修复开源依赖项和容器映像中的漏洞和许可证违规.
- [SonarQube](https://sonarqube.org) -连续检查工具，可在自动测试期间提供详细的报告，并就新引入的安全漏洞发出警报.

### Application or Binary Hardening

- [Egalito](https://egalito.org/) -二进制重新编译器和工具框架，可以完全反汇编，转换和重新生成用于二进制强化和安全性研究的普通Linux二进制文件.

### Fuzzing

See [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

### Policy enforcement

- [OpenPolicyAgent](https://www.openpolicyagent.org/) -跨云本机堆栈的统一工具集和策略框架.
- [Tang](https://github.com/latchset/tang)  -用于将数据绑定到网络状态的服务器；  仅当客户端位于某个（受保护的）网络上时才向客户端提供数据.

## Honeypots

也可以看看 [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens)  -自托管的honeytoken生成器和报告仪表板；  演示版本可在 [CanaryTokens.org](https://canarytokens.org/).
- [Kushtaka](https://kushtaka.org) -可持续的多合一蜜罐和蜜罐编排器，用于资源不足的蓝色团队.

### Tarpits

- [Endlessh](https://github.com/skeeto/endlessh) -缓慢地发送无尽横幅的SSH tarpit.
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) -回答ARP请求中未使用的IP空间的程序，从而形成伪造的计算机外观，这些伪造的计算机非常缓慢地响应其他请求，从而减慢扫描程序，蠕虫等的速度.

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) -组合蜜罐，文件系统监视器和警报系统，旨在保护Linux和Windows操作系统.
- [chkrootkit](http://chkrootkit.org/) -在GNU / Linux系统上本地检查rootkit的迹象.
- [Crowd Inspect](https://www.crowdstrike.com/resources/community-tools/crowdinspect-tool/) -适用于Windows系统的免费工具，旨在提醒您存在可能通过网络进行通信的恶意软件.
- [Fail2ban](https://www.fail2ban.org/) -入侵防御软件框架，可保护计算机服务器免受暴力攻击.
- [OpenSCAP Base](https://www.open-scap.org/tools/openscap-base/) -库和命令行工具（oscap）均用于根据SCAP基线配置文件评估系统，以报告扫描系统的安全状态. 
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) -完全开源和免费的，功能丰富的基于主机的入侵检测系统（HIDS）.
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) -符合POSIX的Bash脚本，可扫描主机以查找各种恶意软件迹象.

### Sandboxes

- [Firejail](https://firejail.wordpress.com/) -SUID程序，可通过使用Linux名称空间和seccomp-bpf限制不受信任的应用程序的运行环境来降低安全漏洞的风险.

## Incident Response tools

也可以看看 [awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [aws_ir](https://github.com/ThreatResponse/aws_ir) -使用零安全准备假设自动执行事件响应.

### IR management consoles

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) -建立在Viper上的可编写脚本的数字取证和事件响应（DFIR）工具包.
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) -网络安全事件管理平台，可轻松创建，跟踪和报告网络安全事件.
- [Rekall](http://www.rekall-forensic.com/) -先进的法证和事件响应框架.
- [TheHive](https://thehive-project.org/) -可扩展的免费安全事件响应平台，旨在简化SOC，CSIRT和CERT的工作，并与MISP紧密集成.
- [threat_note](https://github.com/defpoint/threat_note) -Defence Point Security构建的Web应用程序，使安全研究人员能够添加和检索与他们的研究相关的指标.

### Evidence collection

- [AutoMacTC](https://github.com/CrowdStrike/automactc) -模块化的自动取证分类收集框架，旨在访问macOS上的各种取证工件，进行解析，并以可行的格式进行分析.
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) -免费的macOS计算机取证工具.
- [OSXCollector](https://github.com/Yelp/osxcollector) -适用于macOS的取证证据和分析工具包.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -Windows Batch脚本和Unix Bash脚本，可在事件响应期间全面收集主机取证数据.
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) -命令行实用程序（可与或不与Amazon EC2实例一起使用）并行化远程内存获取.

## Network perimeter defenses

- [fwknop](https://www.cipherdyne.org/fwknop/) -通过防火墙中的“单包授权”保护端口.
- [ssh-audit](https://github.com/jtesta/ssh-audit) -简单的工具，可快速提出建议以改善SSH服务器的安全状况.

### Firewall appliances or distributions

- [OPNsense](https://opnsense.org/) -基于FreeBSD的防火墙和路由平台.
- [pfSense](https://www.pfsense.org/) -防火墙和路由器FreeBSD分发.

## Operating System distributions

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) -意大利GNU / Linux实时发行版，预打包了许多数字取证和证据收集工具.
- [Security Onion](https://securityonion.net/) -用于入侵检测，企业安全监视和日志管理的免费和开源GNU / Linux发行版.

## Phishing awareness and reporting

也可以看看 [awesome-pentest § Social Engineering Tools](https://github.com/meitar/awesome-pentest#social-engineering-tools).

- [CertSpotter](https://github.com/SSLMate/certspotter) -SSLMate的证书透明性日志监视器，当为您的一个域颁发SSL / TLS证书时提醒您.
- [Gophish](https://getgophish.com/) -强大的开源网络钓鱼框架，可轻松测试组织对网络钓鱼的危害.
- [King Phisher](https://github.com/securestate/king-phisher) - Tool for testing and promoting user awareness by simulating real world phishing attacks.
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) -Outlook加载项，用于帮助您的用户向安全团队报告可疑电子邮件.
- [Phishing Intelligence Engine (PIE)](https://github.com/LogRhythm-Labs/PIE) -有助于检测和响应网络钓鱼攻击的框架.
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) -允许创建和管理（伪造）网络钓鱼活动的平台，旨在训练人们识别可疑邮件. 
- [mailspoof](https://github.com/serain/mailspoof) -扫描SPF和DMARC记录以查找可能允许电子邮件欺骗的问题.
- [phishing_catcher](https://github.com/x0rz/phishing_catcher) -可配置脚本，可使用以下命令在证书透明日志（CTL）中按域名监视可疑TLS证书的颁发 [CertStream](https://certstream.calidog.io/) 服务.

## Preparedness training and wargaming

（也称为*对手模拟*，*威胁模拟*或类似的东西.）

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) -使系统看起来像是APT攻击的受害者的工具集.
- [Atomic Red Team](https://atomicredteam.io/) -简单，可自动执行的测试库，以执行以测试安全性控制.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) -模块化，菜单驱动的跨平台工具，用于为Blue Team演练和传感器/警报映射构建可重复的，延迟的，分布式的安全事件.
- [Metta](https://github.com/uber-common/metta) -自动化的信息安全准备工具进行对抗性模拟.
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) -生成恶意网络流量并帮助安全团队评估安全控制并审核其网络可见性的实用程序.
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) -基于Ubuntu的开放式虚拟设备（`.ova`）已预先配置了多种威胁仿真工具以及防御者的工具包.

## Security monitoring

### Endpoint Detection and Response (EDR)

- [Wazuh](https://wazuh.com/) -基于OSSEC HIDS分支的开源，基于多平台代理的安全监视.

### Network Security Monitoring (NSM)

也可以看看 [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [Bro](https://www.bro.org/) -专注于安全监控的强大网络分析框架.
- [ChopShop](https://github.com/MITRECND/chopshop) -协助分析人员创建和执行基于APT的基于Pynids的解码器和检测器的框架.
- [Maltrail](https://github.com/stamparm/maltrail) -恶意网络流量检测系统.
- [Moloch](https://github.com/aol/moloch) -增强您当前的安全基础架构，以标准PCAP格式存储和索引网络流量，从而提供快速的索引访问.
- [OwlH](https://www.owlh.net/) -通过可视化Suricata，Zeek和Moloch生命周期来帮助大规模管理网络IDS.
- [Respounder](https://github.com/codeexpress/respounder) -检测网络上是否存在响应者LLMNR / NBT-NS / MDNS中毒器.
- [Snort](https://snort.org/) -广泛部署的免费软件IPS，能够进行实时数据包分析，流量记录和基于规则的自定义触发器.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) -捕获欺骗的NetBIOS名称服务（NBNS）响应并警告电子邮件或日志文件.
- [Suricata](https://suricata-ids.org/) -具有在线和离线分析模式以及深度数据包检查功能的免费，跨平台IDS / IPS，Lua也可以编写脚本.
- [Wireshark](https://www.wireshark.org) -免费的开源数据包分析器，可用于网络故障排除或法医网络流分析.
- [netsniff-ng](http://netsniff-ng.org/) -具有众多实用程序的免费，快速的GNU / Linux网络工具包，例如连接跟踪工具（`flowtop`），流量生成器（`trafgen`）和自治系统（AS）跟踪路由实用程序（`astraceroute`）.


### Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) -由AlienVault开放威胁交换（OTX）驱动的具有资产发现，资产清单，行为监控和事件关联的单服务器开源SIEM平台.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) -开源，无代理SIEM，历史悠久，具有多种商业变体，具有安全事件收集，规范化和来自任意日志输入和大量流行的监视工具的警报功能.

### Service and performance monitoring

也可以看看 [awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) -Nagios的模块化重新设计，带有可插拔的用户界面以及一组扩展的数据连接器，收集器和报告工具.
- [Locust](https://locust.io/) -开源负载测试工具，您可以在其中使用Python代码定义用户行为，并让数以百万计的同时用户拥挤您的系统.
- [Nagios](https://nagios.org) -流行的网络和服务监控解决方案和报告平台.
- [OpenNMS](https://opennms.org/) -免费且功能丰富的网络监视系统，支持多种配置，多种警报机制（电子邮件，XMPP，SMS）以及多种数据收集方法（SNMP，HTTP，JDBC等）.
- [osquery](https://github.com/facebook/osquery) -适用于macOS，Windows和Linux的操作系统检测框架，将操作系统公开为可以使用类似SQL的语法查询的高性能关系数据库.

### Threat hunting

（也称为“狩猎团队”和“威胁检测”.）

也可以看看 [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) -基于CIM / WMI的工具套件，可在所有Windows版本中进行远程事件响应和搜寻操作.
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) -用于通过Windows事件日志进行寻线分组的PowerShell模块.
- [GRR Rapid Response](https://github.com/google/grr) -事件响应框架专注于远程实时取证，该远程响应取证由安装在资产上的Python代理和基于Python的服务器基础结构组成，使分析人员能够快速分类攻击并进行远程分析.
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) -基于Elasticsearch，Logstash，Kafka和Kibana的多合一免费软件威胁搜寻堆栈，并具有包括Jupyter Notebook在内的各种内置集成分析功能.
- [MozDef](https://github.com/mozilla/MozDef) -使安全事件处理过程自动化，并促进事件处理程序的实时活动.
- [PSHunt](https://github.com/Infocyte/PSHunt) -PowerShell模块设计用于扫描远程端点以发现危害指标，或对其进行调查以获取与那些系统状态相关的更全面的信息.
- [PSRecon](https://github.com/gfoss/PSRecon) -类似PSHunt的工具，用于分析远程Windows系统，该工具还生成其结果的独立HTML报告.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) -基于PowerShell的所有平台均可以执行实时硬盘取证分析.
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) -用于在多个端点上同时对可疑IOC进行分类的多平台工具，并与防病毒控制台集成.
- [Redline](https://www.fireeye.com/services/freeware/redline.html) -由FireEye，Inc.提供的免费端点审计和分析工具，它提供基于主机的调查功能.

## Threat intelligence

也可以看看 [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths)  -将Active Directory权限配置（“控制关系”）可视化并绘制图形，以审核诸如“谁可以阅读CEO的电子邮件？”之类的问题.  和类似的.
- [DATA](https://github.com/hadojae/DATA) -凭据网络钓鱼分析和自动化工具，可以直接接受可疑网络钓鱼URL或在观察到的包含此类URL的网络流量上触发.
- [Forager](https://github.com/opensourcesec/Forager) -使用Python3构建的多线程威胁情报收集功能，具有基于文本的简单配置和数据存储，易于使用和数据可移植性.
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) -通过被动地映射，计算和报告ICS / SCADA网络拓扑和端点，提供IP网络对工业控制系统（ICS）和监督控制与数据采集（SCADA）的态势感知.
- [MLSec Combine](https://github.com/mlsecproject/combine) -收集多种威胁情报源并将其组合成一种可定制的，基于CSV的标准化格式.
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) -用于收集，存储，分发和共享网络安全指标的开源软件解决方案.
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) -可扩展工具，可从威胁源（包括Twitter，RSS源或其他来源）提取和汇总IOC.
- [Unfetter](https://nsacyber.github.io/unfetter/) -利用Mitre的ATT＆CK框架识别安全态势中的防御性漏洞.
- [Viper](https://github.com/viper-framework/viper) -二进制分析和管理框架，可轻松组织恶意软件和利用样本.

## Tor Onion service defenses

也可以看看 [awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) -提供负载平衡，同时通过消除单个故障点使Onion服务更具弹性和可靠性.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) -版本3洋葱服务防护发现缓解脚本（打算最终包含在Tor核心中）.

## Transport-layer defenses

- [Certbot](https://certbot.eff.org/) -免费工具，可自动从TLS证书的发行和更新 [LetsEncrypt Root CA](https://letsencrypt.org/) 带有配置各种Web和电子邮件服务器软件的插件.
- [MITMEngine](https://github.com/cloudflare/mitmengine) -Golang库，用于在服务器端检测TLS拦截事件.
- [OpenVPN](https://openvpn.net/) -开源的基于SSL / TLS的虚拟专用网络（VPN）.
- [Tor](https://torproject.org/) -审查制度的规避和匿名网络覆盖，提供分布式的，经过密码验证的名称服务（.onion域），以增强发布者的隐私和服务可用性.

## macOS-based defenses

- [LuLu](https://objective-see.com/products/lulu.html) - Free macOS firewall.
- [Stronghold](https://github.com/alichtman/stronghold) -从终端轻松配置macOS安全设置.
- [macOS Fortress](https://github.com/essandess/macOS-Fortress) -自动配置内核级，操作系统级和客户端级安全功能，包括私有化代理和macOS的防病毒扫描.

## Windows-based defenses

也可以看看 [awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security) 和 [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening).

- [HardenTools](https://github.com/securitywithoutborders/hardentools) -禁用许多危险的Windows功能的实用程序.
- [NotRuler](https://github.com/sensepost/notruler) -同时检测客户端使用的规则和VBScript启用的表单 [Ruler](https://github.com/sensepost/ruler) 尝试破坏Microsoft Exchange服务器时使用的攻击工具.
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) -对照Microsoft审核Windows主机的根证书存储 [Certificate Trust List (CTL)](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview).
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) -从主机名列表建立Windows RDP会话，并扫描可访问性工具后门，并在发现后门时发出警报.
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) -组策略对象，合规性检查和配置工具，它们提供了一种自动化且灵活的方法来安全地部署和维护Windows 10的最新版本.
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) - Log newly created WMI consumers and processes to the Windows Application event log.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

这项工作是根据 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
