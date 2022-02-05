<div class="github-widget" data-repo="fabacab/awesome-cybersecurity-blueteam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cybersecurity Blue Team [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

&gt; 为网络安全蓝队提供的一系列很棒的资源、工具和其他闪亮的东西.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security)) are groups of individuals who identify security flaws in information technology systems, verify the effectiveness of security measures, and monitor the systems to ensure that implemented defensive measures remain effective in the future. While not exclusive, this list is heavily biased towards [Free Software](https://www.gnu.org/philosophy/free-sw.html) 项目和针对专有产品或公司服务. 对于攻击性 TTP，请参阅 [awesome-pentest](https://github.com/fabacab/awesome-pentest).

衷心欢迎您的贡献和建议♥.  （✿◕‿◕）. 请检查 [Contributing Guidelines](https://github.com/fabacab/awesome-cybersecurity-blueteam/blob/master/CONTRIBUTING.md) for more details. This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

许多网络安全专业人员通过向地方、州和联邦警务机构提供服务或以其他方式与这样做的类似机构合作，有意或无意地助长了种族主义国家暴力. 这种邪恶最常通过在缺乏食物、住所或医疗保健的威胁下的强制就业机制发生. 尽管这个列表是公开的，但维护者的意图和希望是这个列表支持那些致力于对抗如此大规模但平庸的邪恶的人和组织.

![Image of a raised fist composed of the names of Black people murdered by taxpayer-funded racist police violence.](https://web.archive.org/web/20201028021653if_/https://lauerrealtygroup.com/wp-content/uploads/2020/06/BLM-FIST-scaled.jpg)

![Image of a "Blue Lives Matter" flag with the thin blue line being peeled away to reveal a Nazi swastika underneath.](https://web.archive.org/web/20201123181815if_/https://i.redd.it/86pl28p0dl631.jpg)

**[DEFUND THE POLICE.](https://defundthepolice.org/)**



## Automation

- [Ansible Lockdown](https://ansiblelockdown.io/) - 精心策划的以信息安全为主题的 Ansible 角色集合，这些角色经过审查和积极维护.
- [Clevis](https://github.com/latchset/clevis) - 用于自动解密的可插入框架，通常用作 Tang 客户端.
- [DShell](https://github.com/USArmyResearchLab/Dshell) - 用 Python 编写的可扩展网络取证分析框架，支持快速开发插件以支持剖析网络数据包捕获.
- [Dev-Sec.io](https://dev-sec.io/) - 服务器加固框架，提供各种基线安全配置的 Ansible、Chef 和 Puppet 实现.
- [peepdf](https://eternal-todo.com/tools/peepdf-pdf-analysis-tool) - 可编写脚本的 PDF 文件分析器.
- [PyREBox](https://talosintelligence.com/pyrebox) - Python-scriptable reverse engineering sandbox, based on QEMU.
- [Watchtower](https://containrrr.dev/watchtower/) - Container-based solution for automating Docker container base image updates, providing an unattended upgrade experience.

### Code libraries and bindings

- [MultiScanner](https://github.com/mitre/multiscanner) - 用 Python 编写的文件分析框架，通过自动针对一组文件运行一套工具并聚合输出来帮助评估一组文件.
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) - VirusTotal.com API 的 PowerShell 接口.
- [censys-python](https://github.com/censys/censys-python) - Python wrapper to the Censys REST API.
- [libcrafter](https://github.com/pellegre/libcrafter) - 高级 C++ 网络数据包嗅探和制作库.
- [python-dshield](https://github.com/rshipp/python-dshield) - Internet Storm Center/DShield API 的 Pythonic 接口.
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) - 用于构建与恶意软件沙箱集成的最小、一致的 Python API.
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) - Python APIs for serializing and de-serializing Structured Threat Information eXpression (STIX) JSON content, plus higher-level APIs for common tasks.

### Security Orchestration, Automation, and Response (SOAR)

也可以看看 [Security Information and Event Management (SIEM)](#security-information-and-event-management-siem)， 和 [IR management consoles](#ir-management-consoles).

- [Shuffle](https://shuffler.io/) - 适用于 IT 专业人员和蓝队的图形化通用工作流（自动化）构建器.

## Cloud platform security

也可以看看 [asecure.cloud/tools](https://asecure.cloud/tools/).

- [Aaia](https://github.com/rams3sh/Aaia) - 在 Neo4j 的帮助下，帮助以图形格式可视化 AWS IAM 和组织.
- [Checkov](https://www.checkov.io/) - Terraform（基础设施即代码）的静态分析，以帮助检测 CIS 策略违规并防止云安全配置错误.
- [Falco](https://falco.org/) - Behavioral activity monitor designed to detect anomalous activity in containerized applications, hosts, and network packet flows by auditing the Linux kernel and enriched by runtime data such as Kubernetes metrics.
- [Kata Containers](https://katacontainers.io/) - 使用感觉和执行类似于容器的轻量级虚拟机保护容器运行时，但使用硬件虚拟化技术作为第二层防御提供更强的工作负载隔离.
- [Principal Mapper (PMapper)](https://github.com/nccgroup/PMapper) - 通过能够识别 AWS 账户或 AWS 组织的 AWS Identity and Access Management (IAM) 配置中的风险的脚本和库，快速评估 AWS 中的 IAM 权限.
- [Prowler](https://github.com/toniblyx/prowler) - Tool based on AWS-CLI commands for Amazon Web Services account security assessment and hardening.
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) - Open source multi-cloud security-auditing tool, which enables security posture assessment of cloud environments.
- [gVisor](https://github.com/google/gvisor) - 用 Go 编写的应用程序内核，它实现了 Linux 系统表面的大部分，以在应用程序和主机内核之间提供隔离边界.

### Distributed monitoring

也可以看看 [§ Service and performance monitoring](#service-and-performance-monitoring).

- [Cortex](https://cortexmetrics.io/) - 为 Prometheus 提供水平可扩展、高可用、多租户、长期存储.
- [Jaeger](https://www.jaegertracing.io/) - 分布式跟踪平台后端，用于监控和故障排除基于微服务的分布式系统.
- [OpenTelemetry](https://opentelemetry.io/) - 云原生软件的可观察性框架，包括一组工具、API 和 SDK，用于将应用程序性能指标导出到跟踪后端（以前由 OpenTracing 和 OpenCensus 项目维护）.
- [Prometheus](https://prometheus.io/) - Open-source systems monitoring and alerting toolkit originally built at SoundCloud.
- [Zipkin](https://zipkin.io/) - Distributed tracing system backend that helps gather timing data needed to troubleshoot latency problems in service architectures.

### Kubernetes

也可以看看 [Kubernetes-Security.info](https://kubernetes-security.info/).

- [KubeSec](https://kubesec.io/) - Kubernetes 清单的静态分析器，可以在本地运行，作为 Kuberenetes 准入控制器，或者作为它自己的云服务.
- [Kyverno](https://kyverno.io/) - Policy engine designed for Kubernetes.
- [Linkerd](https://linkerd.io/) - 超轻的 Kubernetes 特定服务网格，无需对应用程序本身进行任何修改，即可为 Kubernetes 应用程序增加可观察性、可靠性和安全性.
- [Managed Kubernetes Inspection Tool (MKIT)](https://github.com/darkbitio/mkit) - 查询和验证托管 Kubernetes 集群对象和集群内运行的工作负载/资源的几个常见的安全相关配置设置.
- [Polaris](https://polaris.docs.fairwinds.com/) - 通过针对代码提交、Kubernetes 准入请求或已在集群中运行的实时资源运行测试来验证 Kubernetes 最佳实践. 
- [certificate-expiry-monitor](https://github.com/muxinc/certificate-expiry-monitor) - 将 TLS 证书的到期时间公开为 Prometheus 指标的实用程序.
- [k-rail](https://github.com/cruise-automation/k-rail) - Kubernetes 的工作负载策略执行工具.
- [kube-forensics](https://github.com/keikoproj/kube-forensics) - 允许集群管理员转储正在运行的 pod 及其所有容器的当前状态，以便安全专业人员可以执行离线取证分析。
- [kube-hunter](https://kube-hunter.aquasec.com/) - 从外部（“攻击者的观点”）或集群内部运行一组针对 Kubernetes 集群中的安全问题的测试（“猎人”）的开源工具.
- [kubernetes-event-exporter](https://github.com/opsgenie/kubernetes-event-exporter) - Allows exporting the often missed Kubernetes events to various outputs so that they can be used for observability or alerting purposes.

### Service meshes

也可以看看 [ServiceMesh.es](https://servicemesh.es/).

- [Consul](https://consul.io/) - 跨动态、分布式基础设施连接和配置应用程序的解决方案，并通过 Consul Connect 实现安全的服务到服务通信，并具有自动 TLS 加密和基于身份的授权.
- [Istio](https://istio.io/) - Open platform for providing a uniform way to integrate microservices, manage traffic flow across microservices, enforce policies and aggregate telemetry data.

## Communications security (COMSEC)

也可以看看 [Transport-layer defenses](#transport-layer-defenses).

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) - 在组织或团队的所有成员之间集中和自动化 OpenPGP 公钥分发、撤销和更新.
- [Geneva (Genetic Evasion)](https://censorship.ai/) - 新的实验性遗传算法，改进了针对民族国家级审查员的基于数据包操作的审查规避策略，以增加其他被阻止内容的可用性.
- [GlobaLeaks](https://www.globaleaks.org/) - 免费的开源软件使任何人都可以轻松设置和维护安全的举报平台.
- [SecureDrop](https://securedrop.org/) - 媒体组织和非政府组织可以安装开源举报人提交系统，以安全地接受来自匿名来源的文件.
- [Teleport](https://goteleport.com/) - Allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments.

## DevSecOps

也可以看看 [awesome-devsecops](https://github.com/devsecops/awesome-devsecops).

- [Bane](https://github.com/genuinetools/bane) - Custom and better AppArmor profile generator for Docker containers.
- [BlackBox](https://github.com/StackExchange/blackbox) - 通过使用 GnuPG 在“静止状态”加密它们，将机密安全地存储在 Git/Mercurial/Subversion 中.
- [Cilium](https://cilium.io/) - 开源软件，用于透明地保护使用 Linux 容器管理平台（如 Docker 和 Kubernetes）部署的应用程序服务之间的网络连接.
- [Clair](https://github.com/coreos/clair) - 静态分析工具，用于探测通过应用程序容器（例如 Docker）图像引入的漏洞.
- [CodeQL](https://securitylab.github.com/tools/codeql) - Discover vulnerabilities across a codebase by performing queries against code as though it were data.
- [DefectDojo](https://www.defectdojo.org/) - 为 DevOps 和持续安全集成构建的应用程序漏洞管理工具.
- [Gauntlt](http://gauntlt.org/) - 常规持续集成构建管道期间的渗透测试应用程序。
- [Git Secrets](https://github.com/awslabs/git-secrets) - Prevents you from committing passwords and other sensitive information to a git repository.
- [SOPS](https://github.com/mozilla/sops) - 支持 YAML、JSON、ENV、INI 和二进制格式并使用 AWS KMS、GCP KMS、Azure Key Vault 和 PGP 加密的加密文件的编辑器.
- [Snyk](https://snyk.io/) - 查找并修复开源依赖项和容器映像中的漏洞和许可违规.
- [SonarQube](https://sonarqube.org) - Continuous inspection tool that provides detailed reports during automated testing and alerts on newly introduced security vulnerabilities.
- [Trivy](https://github.com/aquasecurity/trivy) - Simple and comprehensive vulnerability scanner for containers and other artifacts, suitable for use in continuous integration pipelines.
- [Vault](https://www.vaultproject.io/) - Tool for securely accessing secrets such as API keys, passwords, or certificates through a unified interface.
- [git-crypt](https://www.agwa.name/projects/git-crypt/)  - git中的透明文件加密； 您选择保护的文件在提交时被加密，在签出时被解密.
- [helm-secrets](https://github.com/jkroepke/helm-secrets) - Helm plugin that helps manage secrets with Git workflow and stores them anywhere, backed by SOPS.

### Application or Binary Hardening

- [DynInst](https://dyninst.org/dyninst) - Tools for binary instrumentation, analysis, and modification, useful for binary patching.
- [DynamoRIO](https://dynamorio.org/) - Runtime code manipulation system that supports code transformations on any part of a program, while it executes, implemented as a process-level virtual machine.
- [Egalito](https://egalito.org/) - Binary recompiler and instrumentation framework that can fully disassemble, transform, and regenerate ordinary Linux binaries designed for binary hardening and security research.
- [Valgrind](https://www.valgrind.org/) - Instrumentation framework for building dynamic analysis tools.

### Compliance testing and reporting

- [Chef InSpec](https://www.chef.io/products/chef-inspec) - 用于描述安全性和合规性规则的语言，这些规则成为可以针对 IT 基础设施运行的自动化测试，以发现和报告不合规性.
- [OpenSCAP Base](https://www.open-scap.org/tools/openscap-base/) - 用于根据 SCAP 基线配置文件评估系统以报告已扫描系统的安全状况的库和命令行工具 (`oscap`). 

### Dependency confusion

也可以看看 [§ Supply chain security](#supply-chain-security).

- [Dependency Combobulator](https://github.com/apiiro/combobulator) - Open source, modular and extensible framework to detect and prevent dependency confusion leakage and potential attacks.
- [Confusion checker](https://github.com/sonatype-nexus-community/repo-diff) - 用于检查您的存储库之间是否有包含相同名称的工件的脚本.
- [snync](https://github.com/snyk-labs/snync) - Prevent and detect if you're vulnerable to Dependency Confusion supply chain security attacks.

### Fuzzing

也可以看看 [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

* [Atheris](https://pypi.org/project/atheris/) - 基于 libFuzzer 的覆盖引导 Python 模糊测试引擎，支持 Python 代码的模糊测试，也支持为 CPython 编写的本机扩展.
* [FuzzBench](https://google.github.io/fuzzbench/) - Free service that evaluates fuzzers on a wide variety of real-world benchmarks, at Google scale.
* [OneFuzz](https://github.com/microsoft/onefuzz) - Self-hosted Fuzzing-as-a-Service (FaaS) platform.

### Policy enforcement

- [AllStar](https://github.com/ossf/allstar) - 安装在组织或存储库上的 GitHub 应用程序以设置和执行安全策略.
- [Conftest](https://conftest.dev/) - Utility to help you write tests against structured configuration data.
- [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) - 跨云原生堆栈的统一工具集和策略框架.
- [Tang](https://github.com/latchset/tang)  - 用于将数据绑定到网络存在的服务器； 仅当客户端在某个（安全）网络上时才向客户端提供数据.

### Supply chain security

也可以看看 [§ Dependency confusion](#dependency-confusion).

- [Grafeas](https://grafeas.io/) - Open artifact metadata API to audit and govern your software supply chain.
- [Helm GPG (GnuPG) Plugin](https://github.com/technosophos/helm-gpg) - Chart signing and verification with GnuPG for Helm.
- [Notary](https://github.com/theupdateframework/notary) - Aims to make the internet more secure by making it easy for people to publish and verify content.
- [in-toto](https://in-toto.io/) - 确保软件供应链完整性的框架.

## Honeypots

也可以看看 [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens) - Self-hostable honeytoken generator and reporting dashboard; demo version available at [CanaryTokens.org](https://canarytokens.org/).
- [Kushtaka](https://kushtaka.org) - Sustainable all-in-one honeypot and honeytoken orchestrator for under-resourced blue teams.
- [Manuka](https://github.com/spaceraccoon/manuka) - 开源情报 (OSINT) 蜜罐，用于监控威胁参与者的侦察尝试并为蓝队提供可操作的情报.

### Tarpits

- [Endlessh](https://github.com/skeeto/endlessh) - SSH tarpit that slowly sends an endless banner.
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - Program that answers ARP requests for unused IP space, creating the appearance of fake machines that answer further requests very slowly in order to slow down scanners, worms, etcetera.

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) - Combination honeypot, filesystem monitor, and alerting system designed to protect Linux and Windows operating systems.
- [chkrootkit](http://chkrootkit.org/) - Locally checks for signs of a rootkit on GNU/Linux systems.
- [Crowd Inspect](https://www.crowdstrike.com/resources/community-tools/crowdinspect-tool/) - 适用于 Windows 系统的免费工具，旨在提醒您存在可能通过网络进行通信的恶意软件.
- [Fail2ban](https://www.fail2ban.org/) - Intrusion prevention software framework that protects computer servers from brute-force attacks.
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) - 完全开源和免费、功能丰富、基于主机的入侵检测系统 (HIDS).
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) - 符合 POSIX 标准的 Bash 脚本，可扫描主机以查找各种恶意软件迹象.

### Sandboxes

- [Bubblewrap](https://github.com/containers/bubblewrap) - 沙盒工具供非特权 Linux 用户使用，能够限制对部分操作系统或用户数据的访问.
- [Dangerzone](https://dangerzone.rocks/) - 获取具有潜在危险的 PDF、办公文档或图像，并将它们转换为安全的 PDF.
- [Firejail](https://firejail.wordpress.com/) - SUID 程序通过使用 Linux 命名空间和 seccomp-bpf 限制不受信任的应用程序的运行环境来降低安全漏洞的风险.

## Identity and AuthN/AuthZ

- [Gluu Server](https://gluu.org/) - Central authentication and authorization for Web and mobile applications with a Free and Open Source Software cloud-native community distribution.

## Incident Response tools

也可以看看 [awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - Investigate malicious Windows logon by visualizing and analyzing Windows event log.
- [Volatility](https://www.volatilityfoundation.org/) - Advanced memory forensics framework.
- [aws_ir](https://github.com/ThreatResponse/aws_ir) - Automates your incident response with zero security preparedness assumptions.

### IR management consoles

也可以看看 [Security Orchestration, Automation, and Response (SOAR)](#security-orchestration-automation-and-response-soar).

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) - 基于 Viper 构建的脚本化数字取证和事件响应 (DFIR) 工具包.
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) - Cybersecurity incident management platform allowing for easy creation, tracking, and reporting of cybersecurity incidents.
- [Rekall](http://www.rekall-forensic.com/) - 先进的取证和事件响应框架.
- [TheHive](https://thehive-project.org/) - 可扩展的免费安全事件响应平台旨在让 SOC、CSIRT 和 CERT 的生活更轻松，并与 MISP 紧密集成.
- [threat_note](https://github.com/defpoint/threat_note) - Web application built by Defense Point Security to allow security researchers the ability to add and retrieve indicators related to their research.

### Evidence collection

- [AutoMacTC](https://github.com/CrowdStrike/automactc) - 模块化、自动化的取证分类收集框架，旨在访问 macOS 上的各种取证工件，解析它们，并以可分析的格式呈现它们.
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) - Free macOS computer forensics tool.
- [OSXCollector](https://github.com/Yelp/osxcollector) - Forensic evidence collection & analysis toolkit for macOS.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - Windows Batch 脚本和 Unix Bash 脚本，用于在事件响应期间全面收集主机取证数据.
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - Command line utility (that works with or without Amazon EC2 instances) to parallelize remote memory acquisition.

## Network perimeter defenses

- [Gatekeeper](https://github.com/AltraMayor/gatekeeper) - 第一个开源分布式拒绝服务 (DDoS) 保护系统.
- [fwknop](https://www.cipherdyne.org/fwknop/) - Protects ports via Single Packet Authorization in your firewall.
- [ssh-audit](https://github.com/jtesta/ssh-audit) - 一个简单的工具，可以为改进 SSH 服务器的安全状况提供快速建议.

### Firewall appliances or distributions

也可以看看 [Wikipedia: List of router and firewall distributions](https://en.wikipedia.org/wiki/List_of_router_and_firewall_distributions).

- [IPFire](https://www.ipfire.org/) - Hardened GNU/Linux based router and firewall distribution forked from IPCop.
- [OPNsense](https://opnsense.org/) - Hardened FreeBSD based firewall and routing platform forked from pfSense.
- [pfSense](https://www.pfsense.org/) - 从 m0n0wall 分叉的 FreeBSD 防火墙和路由器分发.

## Operating System distributions

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) - Italian GNU/Linux live distribution that pre-packages numerous digital forensics and evidence collection tools.
- [Security Onion](https://securityonion.net/) - Free and open source GNU/Linux distribution for intrusion detection, enterprise security monitoring, and log management.
- [Qubes OS](https://qubes-os.org/) - Desktop environment built atop the Xen hypervisor project that runs each end-user program in its own virtual machine intended to provide strict security controls to constrain the reach of any successful malware exploit.

## Phishing awareness and reporting

也可以看看 [awesome-pentest § Social Engineering Tools](https://github.com/fabacab/awesome-pentest#social-engineering-tools).

- [CertSpotter](https://github.com/SSLMate/certspotter) - Certificate Transparency log monitor from SSLMate that alerts you when a SSL/TLS certificate is issued for one of your domains.
- [Gophish](https://getgophish.com/) - Powerful, open-source phishing framework that makes it easy to test your organization's exposure to phishing.
- [King Phisher](https://github.com/securestate/king-phisher) - Tool for testing and promoting user awareness by simulating real world phishing attacks.
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) - Outlook 插件用于帮助您的用户向安全团队报告可疑电子邮件.
- [Phishing Intelligence Engine (PIE)](https://github.com/LogRhythm-Labs/PIE) - 有助于检测和响应网络钓鱼攻击的框架.
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) - Platform allowing to create and manage (fake) phishing campaigns intended to train people in identifying suspicious mails. 
- [mailspoof](https://github.com/serain/mailspoof) - 扫描 SPF 和 DMARC 记录以查找可能允许电子邮件欺骗的问题.
- [phishing_catcher](https://github.com/x0rz/phishing_catcher) - Configurable script to watch for issuances of suspicious TLS certificates by domain name in the Certificate Transparency Log (CTL) using the [CertStream](https://certstream.calidog.io/) 服务.

## Preparedness training and wargaming

(Also known as *adversary emulation*, *threat simulation*, or similar.)

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) - 使系统看起来像是 APT 攻击的受害者的工具集.
- [Atomic Red Team](https://atomicredteam.io/) - Library of simple, automatable tests to execute for testing security controls.
- [BadBlood](https://www.secframe.com/badblood/) - 使用数据填充测试（非生产）Windows 域，使安全分析师和工程师能够练习使用工具来了解并规定保护 Active Directory.
- [Caldera](https://caldera.mitre.org/) - Scalable, automated, and extensible adversary emulation platform developed by MITRE.
- [Drool](https://www.dns-oarc.net/tools/drool) - 从抓包文件中重放DNS流量并将其发送到指定的服务器，例如用于模拟对DNS的DDoS攻击和测量正常的DNS查询.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - 模块化、菜单驱动、跨平台工具，用于为蓝队演习和传感器/警报映射构建可重复的、延时的、分布式安全事件.
- [Infection Monkey](https://www.guardicore.com/infectionmonkey/) - Open-source breach and attack simulation (BAS) platform that helps you validate existing controls and identify how attackers might exploit your current network security gaps.
- [Metta](https://github.com/uber-common/metta) - 进行对抗性模拟的自动化信息安全准备工具.
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) - 生成恶意网络流量并帮助安全团队评估安全控制并审核其网络可见性的实用程序.
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) - 基于 Ubuntu 的开放式虚拟设备 (`.ova`) 预配置了多个威胁仿真工具以及防御者工具包.

## Security configurations

(Also known as *secure-by-default baselines* and *implemented best practices*.)

- [Bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx) - Docker image of an NginX configuration and scripts implementing many defensive techniques for Web sites.

## Security monitoring

### Endpoint Detection and Response (EDR)

- [Wazuh](https://wazuh.com/) - 基于 OSSEC HIDS 分支的开源、多平台代理安全监控.

### Network Security Monitoring (NSM)

也可以看看 [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [ChopShop](https://github.com/MITRECND/chopshop) - 帮助分析师创建和执行基于 pynids 的解码器和 APT 交易检测器的框架.
- [Maltrail](https://github.com/stamparm/maltrail) - 恶意网络流量检测系统.
- [Moloch](https://github.com/aol/moloch) - 增强您当前的安全基础设施，以标准 PCAP 格式存储和索引网络流量，提供快速、索引访问.
- [OwlH](https://www.owlh.net/) - Helps manage network IDS at scale by visualizing Suricata, Zeek, and Moloch life cycles.
- [Real Intelligence Threat Analysis (RITA)](https://github.com/activecm/rita) - Open source framework for network traffic analysis that ingests Zeek logs and detects beaconing, DNS tunneling, and more.
- [Respounder](https://github.com/codeexpress/respounder) - Detects the presence of the Responder LLMNR/NBT-NS/MDNS poisoner on a network.
- [Snort](https://snort.org/) - Widely-deployed, Free Software IPS capable of real-time packet analysis, traffic logging, and custom rule-based triggers.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) - 捕获欺骗性的 NetBIOS 名称服务 (NBNS) 响应并向电子邮件或日志文件发出警报.
- [Stenographer](https://github.com/google/stenographer) - 完整的数据包捕获实用程序，用于将数据包缓冲到磁盘以进行入侵检测和事件响应.
- [Suricata](https://suricata-ids.org/) - 免费、跨平台的 IDS/IPS，具有在线和离线分析模式和深度数据包检测功能，也可使用 Lua 编写脚本.
- [Tsunami](https://github.com/google/tsunami-security-scanner) - General purpose network security scanner with an extensible plugin system for detecting high severity vulnerabilities with high confidence. 
- [VAST](https://github.com/tenzir/vast) - Free and open-source network telemetry engine for data-driven security investigations.
- [Wireshark](https://www.wireshark.org) - 用于网络故障排除或取证网络流分析的免费和开源数据包分析器。
- [Zeek](https://zeek.org/) - Powerful network analysis framework focused on security monitoring, formerly known as Bro.
- [netsniff-ng](http://netsniff-ng.org/) -  Free and fast GNU/Linux networking toolkit with numerous utilities such as a connection tracking tool (`flowtop`), traffic generator (`trafgen`), and autonomous system (AS) trace route utility (`astraceroute`).

### Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - 由 AlienVault Open Threat Exchange (OTX) 驱动的单服务器开源 SIEM 平台，具有资产发现、资产清点、行为监控和事件关联功能.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) - Open source, agentless SIEM with a long history and several commercial variants featuring security event collection, normalization, and alerting from arbitrary log input and numerous popular monitoring tools.

### Service and performance monitoring

也可以看看 [awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) - Nagios 的模块化重新设计，具有可插拔的用户界面和一组扩展的数据连接器、收集器和报告工具.
- [Locust](https://locust.io/) - 开源负载测试工具，您可以在其中使用 Python 代码定义用户行为，并让您的系统同时拥有数百万用户.
- [Nagios](https://nagios.org) - Popular network and service monitoring solution and reporting platform.
- [OpenNMS](https://opennms.org/) - 免费且功能丰富的网络监控系统，支持多种配置、多种告警机制（email、XMPP、SMS）和多种数据采集方式（SNMP、HTTP、JDBC等）.
- [osquery](https://github.com/facebook/osquery) - Operating system instrumentation framework for macOS, Windows, and Linux, exposing the OS as a high-performance relational database that can be queried with a SQL-like syntax.
- [Zabbix](https://www.zabbix.com/) - Mature, enterprise-level platform to monitor large-scale IT environments.

### Threat hunting

（也称为 *hunt teaming* 和 *threat detection*.）

也可以看看 [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) - Suite of CIM/WMI-based tools enabling remote incident response and hunting operations across all versions of Windows.
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) - PowerShell 模块，用于通过 Windows 事件日志进行分组搜索.
- [GRR Rapid Response](https://github.com/google/grr) - Incident response framework focused on remote live forensics consisting of a Python agent installed on assets and Python-based server infrastructure enabling analysts to quickly triage attacks and perform analysis remotely.
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) - All-in-one Free Software threat hunting stack based on Elasticsearch, Logstash, Kafka, and Kibana with various built-in integrations for analytics including Jupyter Notebook.
- [MozDef](https://github.com/mozilla/MozDef) - 自动化安全事件处理过程并促进事件处理人员的实时活动.
- [PSHunt](https://github.com/Infocyte/PSHunt) - PowerShell 模块旨在扫描远程端点以获取危害指标或调查它们以获取与这些系统状态相关的更全面的信息.
- [PSRecon](https://github.com/gfoss/PSRecon) - PSHunt-like tool for analyzing remote Windows systems that also produces a self-contained HTML report of its findings.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 在一个基于 PowerShell 的平台上执行实时硬盘取证分析.
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) - 多平台工具，用于同时对多个端点上的可疑 IOC 进行分类，并与防病毒控制台集成.
- [Redline](https://www.fireeye.com/services/freeware/redline.html) - FireEye, Inc. 提供的免费端点审计和分析工具，提供基于主机的调查功能.

## Threat intelligence

也可以看看 [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [AttackerKB](https://attackerkb.com/) - 免费和公开的众包漏洞评估平台，帮助优先考虑高风险补丁应用和对抗漏洞疲劳.
- [DATA](https://github.com/hadojae/DATA) - 凭据网络钓鱼分析和自动化工具，可以直接接受可疑的网络钓鱼 URL，或在观察到的包含此类 URL 的网络流量上触发.
- [Forager](https://github.com/opensourcesec/Forager) - Multi-threaded threat intelligence gathering built with Python3 featuring simple text-based configuration and data storage for ease of use and data portability.
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) - 通过对您的 ICS/SCADA 网络拓扑和端点进行被动映射、说明和报告，提供工业控制系统 (ICS) 和监控与数据采集 (SCADA) 的 IP 网络态势感知.
- [MLSec Combine](https://github.com/mlsecproject/combine) - 收集多个威胁情报源并将其组合成一种可定制的、标准化的基于 CSV 的格式.
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) - 用于收集、存储、分发和共享网络安全指标的开源软件解决方案.
- [Open Source Vulnerabilities (OSV)](https://osv.dev/) - 开源项目的漏洞数据库和分类基础设施，旨在帮助开源维护者和开源消费者.
- [Sigma](https://github.com/Neo23x0/sigma) - SIEM 系统的通用签名格式，提供开放式签名格式，让您能够以直接的方式描述相关的日志事件.
- [Threat Bus](https://github.com/tenzir/threatbus) - Threat intelligence dissemination layer to connect security tools through a distributed publish/subscribe message broker.
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) - Extendable tool to extract and aggregate IOCs from threat feeds including Twitter, RSS feeds, or other sources.
- [Unfetter](https://nsacyber.github.io/unfetter/) - 利用 Mitre 的 ATT&amp;CK 框架识别安全态势中的防御漏洞.
- [Viper](https://github.com/viper-framework/viper) - 二进制分析和管理框架，可以轻松组织恶意软件和漏洞利用样本.
- [YARA](https://github.com/VirusTotal/yara) - Tool aimed at (but not limited to) helping malware researchers to identify and classify malware samples, described as "the pattern matching swiss army knife" for file patterns and signatures.

### Threat signature packages and collections

- [ESET's Malware IoCs](https://github.com/eset/malware-ioc) - Indicators of Compromises (IOCs) derived from ESET's various investigations.
- [FireEye's Red Team Tool Countermeasures](https://github.com/fireeye/red_team_tool_countermeasures) - Collection of Snort and YARA rules to detect attacks carried out with FireEye's own Red Team tools, first released after FireEye disclosed a breach in December 2020.
- [FireEye's Sunburst Countermeasures](https://github.com/fireeye/sunburst_countermeasures) - 收集各种语言的 IoC，用于检测后门 SolarWinds Orion NMS 活动和相关漏洞.
- [YARA Rules](https://github.com/Yara-Rules/rules) - 涵盖 IT 安全研究人员需要拥有一个单一存储库的项目，其中不同的 Yara 签名被编译、分类并尽可能保持最新.

## Tor Onion service defenses

也可以看看 [awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) - 提供负载平衡，同时通过消除单点故障使 Onion 服务更具弹性和可靠性.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - Version 3 Onion service guard discovery attack mitigation script (intended for eventual inclusion in Tor core).

## Transport-layer defenses

- [Certbot](https://certbot.eff.org/) - Free tool to automate the issuance and renewal of TLS certificates from the [LetsEncrypt Root CA](https://letsencrypt.org/) 带有配置各种 Web 和电子邮件服务器软件的插件.
- [MITMEngine](https://github.com/cloudflare/mitmengine) - Golang library for server-side detection of TLS interception events.
- [Tor](https://torproject.org/) - 审查规避和匿名覆盖网络提供分布式、加密验证的名称服务（`.onion` 域），以增强发布者的隐私和服务可用性.

### Overlay and Virtual Private Networks (VPNs)

- [IPsec VPN Server Auto Setup Scripts](https://github.com/hwdsl2/setup-ipsec-vpn) - Scripts to build your own IPsec VPN server, with IPsec/L2TP, Cisco IPsec and IKEv2.
- [Innernet](https://github.com/tonarino/innernet) - 在后台使用 WireGuard 的免费软件专用网络系统，可自托管.
- [Nebula](https://github.com/slackhq/nebula) - Completely open source and self-hosted, scalable overlay networking tool with a focus on performance, simplicity, and security, inspired by tinc.
- [OpenVPN](https://openvpn.net/) - Longstanding Free Software traditional SSL/TLS-based virtual private network.
- [Tailscale](https://tailscale.com/) - 建立在 WireGuard 之上的托管免费增值网状 VPN 服务.
- [WireGuard](https://www.wireguard.com/) - 使用最先进的加密技术的极其简单但快速且现代的 VPN.
- [tinc](https://tinc-vpn.org/) - Free Software mesh VPN implemented entirely in userspace that supports expandable network space, bridged ethernet segments, and more.

## macOS-based defenses

也可以看看 [drduh/macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide).

- [BlockBlock](https://objective-see.com/products/blockblock.html) - 监控常见的持久性位置并在添加持久性组件时发出警报，这有助于检测和防止恶意软件安装.
- [LuLu](https://objective-see.com/products/lulu.html) - Free macOS firewall.
- [Santa](https://github.com/google/santa) - 在 macOS 的允许/拒绝列表系统中跟踪顽皮或漂亮的二进制文件.
- [Stronghold](https://github.com/alichtman/stronghold) - 从终端轻松配置 macOS 安全设置.
- [macOS Fortress](https://github.com/essandess/macOS-Fortress) - 内核级、操作系统级和客户端级安全功能的自动配置，包括 macOS 的私有化代理和防病毒扫描.

## Windows-based defenses

也可以看看 [awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security) and [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening).

- [CobaltStrikeScan](https://github.com/Apr4h/CobaltStrikeScan) - Scan files or process memory for Cobalt Strike beacons and parse their configuration.
- [HardenTools](https://github.com/securitywithoutborders/hardentools) - 禁用许多有风险的 Windows 功能的实用程序.
- [NotRuler](https://github.com/sensepost/notruler) - Detect both client-side rules and VBScript enabled forms used by the [Ruler](https://github.com/sensepost/ruler) attack tool when attempting to compromise a Microsoft Exchange server.
- [Sandboxie](https://www.sandboxie.com/) - Free and open source general purpose Windows application sandboxing utility.
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - Audit a Windows host's root certificate store against Microsoft's [Certificate Trust List (CTL)](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview).
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) - 从主机名列表中建立 Windows RDP 会话并扫描可访问性工具后门，如果发现后门会发出警报.
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) - Group Policy objects, compliance checks, and configuration tools that provide an automated and flexible approach for securely deploying and maintaining the latest releases of Windows 10.
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) - Log newly created WMI consumers and processes to the Windows Application event log.

### Active Directory

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths) - Visualize and graph Active Directory permission configs ("control relations") to audit questions such as "Who can read the CEO's email?" and similar.
- [PingCastle](https://www.pingcastle.com/) - Active Directory 漏洞检测和报告工具.
- [PlumHound](https://github.com/PlumHound/PlumHound) - 通过利用寻路引擎识别 Active Directory 安全漏洞，更有效地在持续的安全生命周期中使用 BloodHoundAD.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

本作品已获得许可 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
