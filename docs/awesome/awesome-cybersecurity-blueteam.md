<div class="github-widget" data-repo="fabacab/awesome-cybersecurity-blueteam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cybersecurity Blue Team [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

&gt;为网络安全蓝队提供了很棒的资源，工具和其他令人眼前一亮的东西.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security) ）是一群人，他们识别信息技术系统中的安全漏洞，验证安全措施的有效性并监视系统，以确保已实施的防御措施在将来仍然有效. 尽管不是排他性的，但此清单在很大程度上偏向于 [Free Software](https://www.gnu.org/philosophy/free-sw.html) 项目，并反对专有产品或公司服务. 有关攻击性TTP，请参阅 [awesome-pentest](https://github.com/fabacab/awesome-pentest).

衷心地欢迎您的贡献和建议♥.  （✿◕‿◕）. 请检查 [Contributing Guidelines](https://github.com/fabacab/awesome-cybersecurity-blueteam/blob/master/CONTRIBUTING.md) 更多细节. 这项工作是根据 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

许多网络安全专业人员通过向地方，州和联邦警务机构提供服务或与这样做的类似机构合作，有意或无意地助长了种族主义国家暴力. 这种邪恶通常是通过强制性的就业机制而发生的，面临着无法获得食物，住房或医疗保健的威胁. 尽管该列表可以公开获得，但维护者的意图是并希望该列表支持那些致力于对抗如此大规模的平庸邪恶的人们和组织.

![Image of a raised fist composed of the names of Black people murdered by taxpayer-funded racist police violence.](https://web.archive.org/web/20201028021653if_/https://lauerrealtygroup.com/wp-content/uploads/2020/06/BLM-FIST-scaled.jpg)

![Image of a "Blue Lives Matter" flag with the thin blue line being peeled away to reveal a Nazi swastika underneath.](https://web.archive.org/web/20201123181815if_/https://i.redd.it/86pl28p0dl631.jpg)

**[DEFUND THE POLICE.](https://defundthepolice.org/)**



## Automation

- [Ansible Lockdown](https://ansiblelockdown.io/) -精心搜集经过审查并积极维护的以信息安全为主题的Ansible角色.
- [Clevis](https://github.com/latchset/clevis) -用于自动解密的可插入框架，通常用作Tang客户端.
- [DShell](https://github.com/USArmyResearchLab/Dshell) -用Python编写的可扩展网络取证分析框架，可快速开发插件以支持剖析网络数据包捕获.
- [Dev-Sec.io](https://dev-sec.io/) -服务器强化框架，提供各种基线安全配置的Ansible，Chef和Puppet实现.
- [peepdf](https://eternal-todo.com/tools/peepdf-pdf-analysis-tool) -可编写脚本的PDF文件分析器.
- [PyREBox](https://talosintelligence.com/pyrebox) -基于QEMU的Python可编写脚本的反向工程沙箱.
- [Watchtower](https://containrrr.dev/watchtower/) -基于容器的解决方案，用于自动化Docker容器基础映像更新，提供无人值守的升级体验.

### Code libraries and bindings

- [MultiScanner](https://github.com/mitre/multiscanner) -用Python编写的文件分析框架，可通过自动对它们运行一套工具并汇总输出来帮助评估一组文件.
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) -VirusTotal.com API的PowerShell接口.
- [censys-python](https://github.com/censys/censys-python) -Censys REST API的Python包装器.
- [libcrafter](https://github.com/pellegre/libcrafter) -高级C ++网络数据包嗅探和制作库.
- [python-dshield](https://github.com/rshipp/python-dshield) -Internet风暴中心/ DShield API的Pythonic接口.
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) -用于构建与恶意软件沙箱集成的最小，一致的Python API.
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) -用于序列化和反序列化结构化威胁信息表达（STIX）JSON内容的Python API，以及用于常见任务的高级API.

### Security Orchestration, Automation, and Response (SOAR)

也可以看看 [Security Information and Event Management (SIEM)](#security-information-and-event-management-siem)和 [IR management consoles](#ir-management-consoles).

- [Shuffle](https://shuffler.io/) - Graphical generalized workflow (automation) builder for IT professionals and blue teamers.

## Cloud platform security

也可以看看 [asecure.cloud/tools](https://asecure.cloud/tools/).

- [Checkov](https://www.checkov.io/) -Terraform的静态分析（以基础结构作为代码），有助于检测CIS策略违规并防止云安全配置错误.
- [Falco](https://falco.org/) -行为活动监视器，旨在通过审核Linux内核并通过运行时数据（例如Kubernetes指标）进行充实，以检测容器化应用程序，主机和网络数据包流中的异常活动.
- [Istio](https://istio.io/) -开放平台，用于提供统一的方式来集成微服务，管理跨微服务的流量，执行策略和汇总遥测数据.
- [Kata Containers](https://katacontainers.io/) -使用感觉和性能类似容器的轻型虚拟机来保护容器运行时，但是使用硬件虚拟化技术作为第二防御层，可以提供更强的工作负载隔离.
- [Managed Kubernetes Inspection Tool (MKIT)](https://github.com/darkbitio/mkit) -查询和验证托管Kubernetes集群对象以及集群内部运行的工作负载/资源的几种与安全性相关的常见配置设置.
- [Prowler](https://github.com/toniblyx/prowler) -基于AWS-CLI命令的工具，用于Amazon Web Services帐户安全性评估和强化.
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) -开源的多云安全审核工具，可对云环境进行安全状态评估.
- [gVisor](https://github.com/google/gvisor) -用Go编写的应用程序内核，实现了Linux系统表面的很大一部分，以在应用程序和主机内核之间提供隔离边界.

## Communications security (COMSEC)

也可以看看 [Transport-layer defenses](#transport-layer-defenses).

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) -在组织或团队的所有成员之间集中和自动化OpenPGP公钥分发，吊销和更新.
- [Geneva (Genetic Evasion)](https://censorship.ai/) -新颖的实验性遗传算法，可针对国家/地区级别的检查员发展基于数据包处理的检查规避策略，以增加其他被阻止内容的可用性.

## DevSecOps

也可以看看 [awesome-devsecops](https://github.com/devsecops/awesome-devsecops).

- [Bane](https://github.com/genuinetools/bane) -用于Docker容器的自定义更好的AppArmor配置文件生成器.
- [BlackBox](https://github.com/StackExchange/blackbox) -通过使用GnuPG对其进行“静态”加密，将秘密安全地存储在Git / Mercurial / Subversion中.
- [Cilium](https://cilium.io/) -开源软件，用于透明保护使用Linux容器管理平台（如Docker和Kubernetes）部署的应用程序服务之间的网络连接.
- [Clair](https://github.com/coreos/clair) -静态分析工具，用于探测通过应用程序容器（例如Docker）映像引入的漏洞.
- [CodeQL](https://securitylab.github.com/tools/codeql) -通过对代码进行查询，就像发现数据一样，从而发现整个代码库中的漏洞.
- [DefectDojo](https://www.defectdojo.org/) -为DevOps和持续安全集成而构建的应用程序漏洞管理工具.
- [Gauntlt](http://gauntlt.org/) -在常规持续集成过程中的Pentest应用程序会构建管道.
- [Git Secrets](https://github.com/awslabs/git-secrets) - Prevents you from committing passwords and other sensitive information to a git repository.
- [SOPS](https://github.com/mozilla/sops) -支持YAML，JSON，ENV，INI和二进制格式并使用AWS KMS，GCP KMS，Azure Key Vault和PGP加密的加密文件的编辑器.
- [Snyk](https://snyk.io/) -查找并修复开源依赖项和容器映像中的漏洞和许可证违规.
- [SonarQube](https://sonarqube.org) -连续检查工具，可在自动测试期间提供详细的报告，并就新引入的安全漏洞发出警报.
- [Trivy](https://github.com/aquasecurity/trivy) -适用于容器和其他工件的简单而全面的漏洞扫描程序，适用于连续集成管道.
- [Vault](https://www.vaultproject.io/) -通过统一界面安全访问API密钥，密码或证书等机密的工具.
- [git-crypt](https://www.agwa.name/projects/git-crypt/) - Transparent file encryption in git; files which you choose to protect are encrypted when committed, and decrypted when checked out.

### Application or Binary Hardening

- [DynInst](https://dyninst.org/dyninst) -用于二进制检测，分析和修改的工具，对二进制修补很有用.
- [DynamoRIO](https://dynamorio.org/) -运行时代码操纵系统，该程序在执行时支持程序任何部分上的代码转换，并实现为进程级虚拟机.
- [Egalito](https://egalito.org/) -二进制重新编译器和工具框架，可以完全反汇编，转换和重新生成用于二进制强化和安全性研究的普通Linux二进制文件.
- [Valgrind](https://www.valgrind.org/) -用于构建动态分析工具的仪器框架.

### Compliance testing and reporting

- [Chef InSpec](https://www.chef.io/products/chef-inspec) -用于描述安全性和合规性规则的语言，这些规则成为可以针对IT基础结构运行以发现并报告不合规情况的自动化测试.
- [OpenSCAP Base](https://www.open-scap.org/tools/openscap-base/) -库和命令行工具（oscap）均用于根据SCAP基线配置文件评估系统，以报告扫描系统的安全状态. 

### Fuzzing

也可以看看 [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

* [Atheris](https://pypi.org/project/atheris/) -基于libFuzzer的覆盖率指导的Python模糊测试引擎，该引擎支持Python代码的模糊测试，也支持为CPython编写的本机扩展.
* [FuzzBench](https://google.github.io/fuzzbench/) -免费服务，可在Google规模的各种实际基准上评估模糊器.
* [OneFuzz](https://github.com/microsoft/onefuzz) -自托管的Fuzzing即服务（FaaS）平台.

### Policy enforcement

- [OpenPolicyAgent](https://www.openpolicyagent.org/) -跨云本机堆栈的统一工具集和策略框架.
- [Tang](https://github.com/latchset/tang)  -用于将数据绑定到网络状态的服务器； 仅当客户端位于某个（受保护的）网络上时才向客户端提供数据.

## Honeypots

也可以看看 [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens)  -自托管的honeytoken生成器和报告仪表板； 演示版本可在 [CanaryTokens.org](https://canarytokens.org/).
- [Kushtaka](https://kushtaka.org) -可持续的多合一蜜罐和蜜罐编排器，用于资源贫乏的蓝色团队.

### Tarpits

- [Endlessh](https://github.com/skeeto/endlessh) -缓慢地发送无尽横幅的SSH tarpit.
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) -回答ARP请求中未使用的IP空间的程序，从而形成伪造的计算机的外观，这些伪造的计算机非常缓慢地响应其他请求，从而减慢扫描程序，蠕虫等的速度.

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) -组合蜜罐，文件系统监视器和警报系统，旨在保护Linux和Windows操作系统.
- [chkrootkit](http://chkrootkit.org/) -在GNU / Linux系统上本地检查rootkit的迹象.
- [Crowd Inspect](https://www.crowdstrike.com/resources/community-tools/crowdinspect-tool/) -适用于Windows系统的免费工具，旨在提醒您存在可能通过网络进行通信的恶意软件.
- [Fail2ban](https://www.fail2ban.org/) -入侵防御软件框架，可保护计算机服务器免受暴力攻击.
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) -完全开源和免费的，功能丰富的基于主机的入侵检测系统（HIDS）.
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) -符合POSIX的Bash脚本，可扫描主机以查找各种恶意软件迹象.

### Sandboxes

- [Firejail](https://firejail.wordpress.com/) -SUID程序，可通过使用Linux名称空间和seccomp-bpf限制不受信任的应用程序的运行环境来降低安全漏洞的风险.

## Incident Response tools

也可以看看 [awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) -通过可视化和分析Windows事件日志来调查恶意Windows登录.
- [Volatility](https://www.volatilityfoundation.org/) -高级内存取证框架.
- [aws_ir](https://github.com/ThreatResponse/aws_ir) -使用零安全准备假设自动执行事件响应.

### IR management consoles

也可以看看 [Security Orchestration, Automation, and Response (SOAR)](#security-orchestration-automation-and-response-soar).

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) -建立在Viper上的可编写脚本的数字取证和事件响应（DFIR）工具包.
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) -网络安全事件管理平台，可轻松创建，跟踪和报告网络安全事件.
- [Rekall](http://www.rekall-forensic.com/) -先进的取证和事件响应框架.
- [TheHive](https://thehive-project.org/) -可扩展的免费安全事件响应平台，旨在简化SOC，CSIRT和CERT的工作，并与MISP紧密集成.
- [threat_note](https://github.com/defpoint/threat_note) -Defence Point Security构建的Web应用程序，使安全研究人员能够添加和检索与其研究相关的指标.

### Evidence collection

- [AutoMacTC](https://github.com/CrowdStrike/automactc) -模块化的自动取证分类分类框架，旨在访问macOS上的各种取证工件，进行解析，并以可行的格式展示它们以供分析.
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) -免费的macOS计算机取证工具.
- [OSXCollector](https://github.com/Yelp/osxcollector) -适用于macOS的取证证据和分析工具包.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -Windows Batch脚本和Unix Bash脚本，可在事件响应期间全面收集主机取证数据.
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) -命令行实用程序（可与或不与Amazon EC2实例一起使用）并行化远程内存获取.

## Network perimeter defenses

- [Gatekeeper](https://github.com/AltraMayor/gatekeeper) -第一个开源分布式拒绝服务（DDoS）保护系统.
- [fwknop](https://www.cipherdyne.org/fwknop/) -通过防火墙中的“单包授权”保护端口.
- [ssh-audit](https://github.com/jtesta/ssh-audit) -简单的工具，可快速提出建议以改善SSH服务器的安全状况.

### Firewall appliances or distributions

- [OPNsense](https://opnsense.org/) -基于FreeBSD的防火墙和路由平台.
- [pfSense](https://www.pfsense.org/) -防火墙和路由器FreeBSD分发.

## Operating System distributions

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) -意大利GNU / Linux实时发行版，预打包了许多数字取证和证据收集工具.
- [Security Onion](https://securityonion.net/) -免费和开源的GNU / Linux发行版，用于入侵检测，企业安全监视和日志管理.

## Phishing awareness and reporting

也可以看看 [awesome-pentest § Social Engineering Tools](https://github.com/fabacab/awesome-pentest#social-engineering-tools).

- [CertSpotter](https://github.com/SSLMate/certspotter) - Certificate Transparency log monitor from SSLMate that alerts you when a SSL/TLS certificate is issued for one of your domains.
- [Gophish](https://getgophish.com/) -强大的开源网络钓鱼框架，可以轻松测试组织对网络钓鱼的危害.
- [King Phisher](https://github.com/securestate/king-phisher) -通过模拟真实的网络钓鱼攻击来测试和增强用户意识的工具.
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) -Outlook加载项，用于帮助您的用户向安全团队报告可疑电子邮件.
- [Phishing Intelligence Engine (PIE)](https://github.com/LogRhythm-Labs/PIE) -有助于检测和响应网络钓鱼攻击的框架.
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) -允许创建和管理（伪造）网络钓鱼活动的平台，旨在训练人们识别可疑邮件. 
- [mailspoof](https://github.com/serain/mailspoof) -扫描SPF和DMARC记录以查找可能允许电子邮件欺骗的问题.
- [phishing_catcher](https://github.com/x0rz/phishing_catcher) -可配置脚本，可使用以下命令在证书透明性日志（CTL）中按域名监视可疑TLS证书的颁发 [CertStream](https://certstream.calidog.io/) 服务.

## Preparedness training and wargaming

（也称为“对手模拟”，“威胁模拟”或类似内容.）

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) -使系统看起来好像是APT攻击的受害者的工具集.
- [Atomic Red Team](https://atomicredteam.io/) -简单，可自动执行的测试库，以执行以测试安全性控制.
- [BadBlood](https://www.secframe.com/badblood/) -用数据填充测试（非生产）Windows域，使安全分析人员和工程师可以练习使用工具来了解并指定如何保​​护Active Directory.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) -模块化，菜单驱动的跨平台工具，用于为Blue Team演练和传感器/警报映射构建可重复的，延迟的，分布式的安全事件.
- [Metta](https://github.com/uber-common/metta) -自动化的信息安全准备工具进行对抗性仿真.
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) -生成恶意网络流量并帮助安全团队评估安全控制并审核其网络可见性的实用程序.
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) -基于Ubuntu的Open Virtual Appliance（`.ova`）已预先配置了多个威胁仿真工具以及防御者的工具包.

## Security configurations

（也称为“默认安全基准”和“实施的最佳做法”.）

- [Bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx) -NginX配置和脚本的Docker映像，该脚本为网站实施了许多防御技术.

## Security monitoring

### Endpoint Detection and Response (EDR)

- [Wazuh](https://wazuh.com/) -基于OSSEC HIDS分支的开源，基于多平台代理的安全监视.

### Network Security Monitoring (NSM)

也可以看看 [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [ChopShop](https://github.com/MITRECND/chopshop) -协助分析人员创建和执行基于APT的基于Pynids的解码器和检测器的框架.
- [Maltrail](https://github.com/stamparm/maltrail) -恶意网络流量检测系统.
- [Moloch](https://github.com/aol/moloch) -增强您当前的安全基础架构，以标准PCAP格式存储和索引网络流量，从而提供快速的索引访问.
- [OwlH](https://www.owlh.net/) -通过可视化Suricata，Zeek和Moloch生命周期来帮助大规模管理网络IDS.
- [Real Intelligence Threat Analysis (RITA)](https://github.com/activecm/rita) -用于网络流量分析的开源框架，可吸收Zeek日志并检测信标，DNS隧道等.
- [Respounder](https://github.com/codeexpress/respounder) -检测网络上是否存在响应者LLMNR / NBT-NS / MDNS中毒器.
- [Snort](https://snort.org/) -广泛部署的免费软件IPS，能够进行实时数据包分析，流量记录和基于规则的自定义触发器.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) -捕获欺骗的NetBIOS名称服务（NBNS）响应并提醒电子邮件或日志文件.
- [Stenographer](https://github.com/google/stenographer) -全包捕获实用程序，用于将数据包缓冲到磁盘以进行入侵检测和事件响应.
- [Suricata](https://suricata-ids.org/) -具有在线和离线分析模式以及深度数据包检查功能的免费，跨平台IDS / IPS，Lua也可以编写脚本.
- [Tsunami](https://github.com/google/tsunami-security-scanner) -具有可扩展插件系统的通用网络安全扫描程序，可高度自信地检测高严重性漏洞. 
- [VAST](https://github.com/tenzir/vast) -免费的开源网络遥测引擎，用于数据驱动的安全调查.
- [Wireshark](https://www.wireshark.org) -免费和开源的数据包分析器，可用于网络故障排除或法医网络流分析.
- [Zeek](https://zeek.org/) -专注于安全监控的强大网络分析框架，以前称为Bro.
- [netsniff-ng](http://netsniff-ng.org/) -具有众多实用程序的免费，快速的GNU / Linux网络工具包，例如连接跟踪工具（`flowtop`），流量生成器（`trafgen`）和自治系统（AS）跟踪路由实用程序（`astraceroute`）.

### Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) -由AlienVault开放威胁交换（OTX）驱动的具有资产发现，资产清单，行为监控和事件关联的单服务器开源SIEM平台.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) -开源，无代理SIEM，历史悠久，具有多种商业变体，具有安全事件收集，规范化和来自任意日志输入和大量流行的监视工具的警报功能.

### Service and performance monitoring

也可以看看 [awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) -Nagios的模块化重新设计，带有可插拔的用户界面以及一组扩展的数据连接器，收集器和报告工具.
- [Locust](https://locust.io/) -开源负载测试工具，您可以在其中使用Python代码定义用户行为，并使数以百万计的同时用户涌入您的系统.
- [Nagios](https://nagios.org) -流行的网络和服务监控解决方案和报告平台.
- [OpenNMS](https://opennms.org/) -免费且功能丰富的网络监视系统，支持多种配置，多种警报机制（电子邮件，XMPP，SMS）以及多种数据收集方法（SNMP，HTTP，JDBC等）.
- [osquery](https://github.com/facebook/osquery) -适用于macOS，Windows和Linux的操作系统检测框架，将操作系统公开为可以通过类似SQL的语法查询的高性能关系数据库.
- [Zabbix](https://www.zabbix.com/) -成熟的企业级平台，用于监视大型IT环境.

### Threat hunting

（也称为“狩猎团队”和“威胁检测”.）

也可以看看 [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) -基于CIM / WMI的工具套件，可在所有Windows版本中进行远程事件响应和搜寻操作.
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) -用于通过Windows事件日志进行寻线分组的PowerShell模块.
- [GRR Rapid Response](https://github.com/google/grr) -事件响应框架专注于远程实时取证，该远程响应取证由安装在资产上的Python代理和基于Python的服务器基础结构组成，使分析师能够快速分类攻击并进行远程分析.
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) -基于Elasticsearch，Logstash，Kafka和Kibana的多合一免费软件威胁搜寻堆栈，并具有包括Jupyter Notebook在内的各种内置集成分析功能.
- [MozDef](https://github.com/mozilla/MozDef) -自动执行安全事件处理流程，并促进事件处理程序的实时活动.
- [PSHunt](https://github.com/Infocyte/PSHunt) -PowerShell模块设计用于扫描远程端点以发现危害指标，或调查它们以获取与那些系统状态相关的更全面的信息.
- [PSRecon](https://github.com/gfoss/PSRecon) -类似PSHunt的工具，用于分析远程Windows系统，该工具还会生成其发现的独立HTML报告.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) -所有基于PowerShell的平台均可以执行实时硬盘取证分析.
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) -用于在多个端点上同时对可疑IOC进行分类的多平台工具，并与防病毒控制台集成.
- [Redline](https://www.fireeye.com/services/freeware/redline.html) -由FireEye，Inc.提供的基于端点的调查功能的免费端点审计和分析工具.

## Threat intelligence

也可以看看 [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths)  -将Active Directory权限配置（“控制关系”）可视化并绘制图形，以审核诸如“谁可以阅读CEO的电子邮件？”之类的问题. 和类似的.
- [AttackerKB](https://attackerkb.com/) -免费的公共众包漏洞评估平台，可帮助确定高风险补丁应用程序的优先级并消除漏洞疲劳.
- [DATA](https://github.com/hadojae/DATA) -凭据网络钓鱼分析和自动化工具，该工具可以直接接受可疑的网络钓鱼URL，也可以在观察到的包含此类URL的网络流量上触发.
- [Forager](https://github.com/opensourcesec/Forager) -使用Python3构建的多线程威胁情报收集功能，基于简单的文本配置和数据存储，易于使用和数据可移植性.
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) -通过被动地映射，计算和报告ICS / SCADA网络拓扑和端点，提供IP网络对工业控制系统（ICS）以及监督控制和数据采集（SCADA）的态势感知.
- [MLSec Combine](https://github.com/mlsecproject/combine) -收集多种威胁情报源并将其组合成一种可定制的，基于CSV的标准化格式.
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) -用于收集，存储，分发和共享网络安全指标的开源软件解决方案.
- [Sigma](https://github.com/Neo23x0/sigma) -SIEM系统的通用签名格式，提供一种开放签名格式，使您可以直接描述相关的日志事件.
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) -可扩展工具，可从威胁源（包括Twitter，RSS源或其他来源）提取和汇总IOC.
- [Unfetter](https://nsacyber.github.io/unfetter/) -利用Mitre的ATT＆CK框架识别安全态势中的防御性漏洞.
- [Viper](https://github.com/viper-framework/viper) -二进制分析和管理框架，可轻松组织恶意软件和利用样本.
- [YARA](https://github.com/VirusTotal/yara) -旨在（但不限于）帮助恶意软件研究人员识别和分类恶意软件样本的工具，称为文件样式和签名的“样式匹配瑞士军刀”.

### Threat signature packages and collections

- [FireEye's Red Team Tool Countermeasures](https://github.com/fireeye/red_team_tool_countermeasures) -收集Snort和YARA规则以检测使用FireEye自己的Red Team工具进行的攻击，该方法在FireEye在2020年12月披露漏洞后首次发布.
- [FireEye's Sunburst Countermeasures](https://github.com/fireeye/sunburst_countermeasures) -收集各种语言的IoC，以检测后门SolarWinds Orion NMS活动和相关漏洞.
- [YARA Rules](https://github.com/Yara-Rules/rules) -满足IT安全研究人员需要拥有一个存储库的项目，在该存储库中，将对不同的Yara签名进行编译，分类和保持最新.

## Tor Onion service defenses

也可以看看 [awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) -提供负载平衡，同时通过消除单个故障点使Onion服务更具弹性和可靠性.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) -第3版Onion Service Guard发现缓解攻击脚本（旨在最终包含在Tor核心中）.

## Transport-layer defenses

- [Certbot](https://certbot.eff.org/) -免费工具，可自动从TLS证书的发行和续签 [LetsEncrypt Root CA](https://letsencrypt.org/) 使用可配置各种Web和电子邮件服务器软件的插件.
- [MITMEngine](https://github.com/cloudflare/mitmengine) -Golang库，用于在服务器端检测TLS拦截事件.
- [OpenVPN](https://openvpn.net/) -开源的基于SSL / TLS的虚拟专用网络（VPN）.
- [Tor](https://torproject.org/) -审查制度的规避和匿名覆盖网络，提供分布式的，经过密码验证的名称服务（.onion域），以增强发布者的隐私和服务可用性.

## macOS-based defenses

也可以看看 [drduh/macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide).

- [BlockBlock](https://objective-see.com/products/blockblock.html) -监视常见的持久性位置并在添加持久性组件时发出警报，这有助于检测和阻止恶意软件的安装.
- [LuLu](https://objective-see.com/products/lulu.html) -免费的macOS防火墙.
- [Santa](https://github.com/google/santa) -在macOS的允许/拒绝列表系统中跟踪顽皮或不错的二进制文件.
- [Stronghold](https://github.com/alichtman/stronghold) -从终端轻松配置macOS安全设置.
- [macOS Fortress](https://github.com/essandess/macOS-Fortress) -自动配置内核级，操作系统级和客户端级安全功能，包括私有化代理和macOS的防病毒扫描.

## Windows-based defenses

也可以看看 [awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security) 和 [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening).

- [HardenTools](https://github.com/securitywithoutborders/hardentools) -实用程序，可禁用许多危险的Windows功能.
- [NotRuler](https://github.com/sensepost/notruler) -检测客户端规则和由VBScript启用的表单 [Ruler](https://github.com/sensepost/ruler) 尝试破坏Microsoft Exchange服务器时使用的攻击工具.
- [PlumHound](https://github.com/PlumHound/PlumHound) 通过利用其寻路引擎来识别Active Directory安全漏洞，可以在连续的安全生命周期中更有效地使用BloodHoundAD.
- [Sandboxie](https://www.sandboxie.com/) -免费和开放源代码的通用Windows应用程序沙箱工具.
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) -根据Microsoft的审核Windows主机的根证书存储 [Certificate Trust List (CTL)](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview).
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) -从主机名列表建立Windows RDP会话，并扫描可访问性工具后门，并在发现后门时发出警报.
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) -组策略对象，合规性检查和配置工具，它们提供了一种自动化且灵活的方法来安全地部署和维护Windows 10的最新版本.
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) -将新创建的WMI使用者和进程记录到Windows应用程序事件日志中.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

这项工作是根据 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
