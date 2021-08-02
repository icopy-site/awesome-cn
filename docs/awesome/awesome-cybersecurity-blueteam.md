<div class="github-widget" data-repo="fabacab/awesome-cybersecurity-blueteam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cybersecurity Blue Team [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

&gt; 为网络安全蓝队收集了一系列很棒的资源、工具和其他闪亮的东西.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security) ) 是识别信息技术系统中的安全缺陷、验证安全措施的有效性并监控系统以确保实施的防御措施在未来仍然有效的一组个人. 虽然不是排他性的，但这份清单严重偏向于 [Free Software](https://www.gnu.org/philosophy/free-sw.html) 项目和反对专有产品或公司服务. 对于攻击性 TTP，请参阅 [awesome-pentest](https://github.com/fabacab/awesome-pentest).

衷心欢迎您的贡献和建议.  （✿◕‿◕）. 请检查 [Contributing Guidelines](https://github.com/fabacab/awesome-cybersecurity-blueteam/blob/master/CONTRIBUTING.md) 更多细节. 这项工作已获得许可 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

许多网络安全专业人员通过向地方、州和联邦警务机构提供服务或以其他方式与这样做的类似机构合作，有意或无意地助长了种族主义国家暴力. 这种邪恶最常通过就业的强制机制在缺乏食物、住所或医疗保健的威胁下发生. 尽管此列表是公开的，但维护者的意图是并希望此列表支持致力于对抗如此庞大但平庸的邪恶的人和组织.

![Image of a raised fist composed of the names of Black people murdered by taxpayer-funded racist police violence.](https://web.archive.org/web/20201028021653if_/https://lauerrealtygroup.com/wp-content/uploads/2020/06/BLM-FIST-scaled.jpg)

![Image of a "Blue Lives Matter" flag with the thin blue line being peeled away to reveal a Nazi swastika underneath.](https://web.archive.org/web/20201123181815if_/https://i.redd.it/86pl28p0dl631.jpg)

**[DEFUND THE POLICE.](https://defundthepolice.org/)**



## Automation

- [Ansible Lockdown](https://ansiblelockdown.io/) - Curated collection of information security themed Ansible roles that are both vetted and actively maintained.
- [Clevis](https://github.com/latchset/clevis) - 用于自动解密的可插拔框架，经常用作 Tang 客户端.
- [DShell](https://github.com/USArmyResearchLab/Dshell) - Extensible network forensic analysis framework written in Python that enables rapid development of plugins to support the dissection of network packet captures.
- [Dev-Sec.io](https://dev-sec.io/) - 服务器强化框架，提供各种基线安全配置的 Ansible、Chef 和 Puppet 实现.
- [peepdf](https://eternal-todo.com/tools/peepdf-pdf-analysis-tool) - 可编写脚本的 PDF 文件分析器.
- [PyREBox](https://talosintelligence.com/pyrebox) - 基于 QEMU 的 Python 脚本化逆向工程沙箱.
- [Watchtower](https://containrrr.dev/watchtower/) - 基于容器的解决方案，用于自动更新 Docker 容器基础镜像，提供无人值守的升级体验.

### Code libraries and bindings

- [MultiScanner](https://github.com/mitre/multiscanner) - 用 Python 编写的文件分析框架，通过自动针对一组文件运行一套工具并聚合输出来帮助评估一组文件.
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) - VirusTotal.com API 的 PowerShell 接口.
- [censys-python](https://github.com/censys/censys-python) - Censys REST API 的 Python 包装器.
- [libcrafter](https://github.com/pellegre/libcrafter) - 高级 C++ 网络数据包嗅探和制作库.
- [python-dshield](https://github.com/rshipp/python-dshield) - Internet Storm Center/DShield API 的 Pythonic 接口.
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) - 最小、一致的 Python API，用于构建与恶意软件沙箱的集成.
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) - 用于序列化和反序列化结构化威胁信息表达 (STIX) JSON 内容的 Python API，以及用于常见任务的更高级别的 API.

### Security Orchestration, Automation, and Response (SOAR)

也可以看看 [Security Information and Event Management (SIEM)](#security-information-and-event-management-siem)， 和 [IR management consoles](#ir-management-consoles).

- [Shuffle](https://shuffler.io/) - 适用于 IT 专业人员和蓝队的图形化通用工作流（自动化）构建器.

## Cloud platform security

也可以看看 [asecure.cloud/tools](https://asecure.cloud/tools/).

- [Checkov](https://www.checkov.io/) - Terraform（基础设施即代码）的静态分析，以帮助检测 CIS 策略违规并防止云安全配置错误.
- [Falco](https://falco.org/) - 行为活动监视器，旨在通过审核 Linux 内核并通过 Kubernetes 指标等运行时数据进行丰富，从而检测容器化应用程序、主机和网络数据包流中的异常活动.
- [Kata Containers](https://katacontainers.io/) - 使用轻量级虚拟机保护容器运行时，这些虚拟机的感觉和性能类似于容器，但使用硬件虚拟化技术作为第二层防御提供更强的工作负载隔离.
- [Prowler](https://github.com/toniblyx/prowler) - 基于 AWS-CLI 命令的工具，用于 Amazon Web Services 帐户安全评估和强化.
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) - 开源多云安全审计工具，可对云环境进行安全态势评估.
- [gVisor](https://github.com/google/gvisor) - 应用程序内核，用 Go 编写，实现了 Linux 系统表面的很大一部分，以在应用程序和主机内核之间提供隔离边界.

### Distributed monitoring

也可以看看 [§ Service and performance monitoring](#service-and-performance-monitoring).

- [Cortex](https://cortexmetrics.io/) - 为 Prometheus 提供水平可扩展、高可用、多租户、长期存储.
- [Jaeger](https://www.jaegertracing.io/) - 分布式跟踪平台后端，用于监控和排除基于微服务的分布式系统.
- [OpenTelemetry](https://opentelemetry.io/) - 云原生软件的可观察性框架，包括一组工具、API 和 SDK，用于将应用程序性能指标导出到跟踪后端（以前由 OpenTracing 和 OpenCensus 项目维护）.
- [Prometheus](https://prometheus.io/) - 最初在 SoundCloud 构建的开源系统监控和警报工具包.
- [Zipkin](https://zipkin.io/) - 分布式跟踪系统后端，有助于收集对服务架构中的延迟问题进行故障排除所需的计时数据.

### Kubernetes

也可以看看 [Kubernetes-Security.info](https://kubernetes-security.info/).

- [KubeSec](https://kubesec.io/) - Kubernetes 清单的静态分析器，可以在本地运行，作为 Kuberenetes 准入控制器，或作为它自己的云服务.
- [Kyverno](https://kyverno.io/) - 为 Kubernetes 设计的策略引擎.
- [Linkerd](https://linkerd.io/) - 特定于 Kubernetes 的超轻型服务网格，可为 Kubernetes 应用程序增加可观察性、可靠性和安全性，而无需对应用程序本身进行任何修改.
- [Managed Kubernetes Inspection Tool (MKIT)](https://github.com/darkbitio/mkit) - 查询和验证托管 Kubernetes 集群对象和集群内运行的工作负载/资源的几个常见的与安全相关的配置设置.
- [Polaris](https://polaris.docs.fairwinds.com/) - 通过针对代码提交、Kubernetes 准入请求或已在集群中运行的实时资源运行测试来验证 Kubernetes 最佳实践. 
- [certificate-expiry-monitor](https://github.com/muxinc/certificate-expiry-monitor) - 将 TLS 证书的到期时间公开为 Prometheus 指标的实用程序.
- [k-rail](https://github.com/cruise-automation/k-rail) - Kubernetes 的工作负载策略实施工具.
- [kube-forensics](https://github.com/keikoproj/kube-forensics) - 允许集群管理员转储正在运行的 pod 及其所有容器的当前状态，以便安全专业人员可以执行离线取证分析.
- [kube-hunter](https://kube-hunter.aquasec.com/) - 开源工具，可以从集群外部（“攻击者的观点”）或集群内部针对 Kubernetes 集群中的安全问题运行一组测试（“猎人”）.
- [kubernetes-event-exporter](https://github.com/opsgenie/kubernetes-event-exporter) - 允许将经常错过的 Kubernetes 事件导出到各种输出，以便它们可用于可观察性或警报目的.

### Service meshes

也可以看看 [ServiceMesh.es](https://servicemesh.es/).

- [Consul](https://consul.io/) - 跨动态分布式基础架构连接和配置应用程序的解决方案，并通过 Consul Connect，通过自动 TLS 加密和基于身份的授权实现安全的服务到服务通信.
- [Istio](https://istio.io/) - 开放平台，用于提供集成微服务、管理跨微服务的流量、执行策略和聚合遥测数据的统一方法.

## Communications security (COMSEC)

也可以看看 [Transport-layer defenses](#transport-layer-defenses).

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) - 在组织或团队的所有成员之间集中和自动化 OpenPGP 公钥分发、撤销和更新.
- [Geneva (Genetic Evasion)](https://censorship.ai/) - 新颖的实验性遗传算法，可针对民族国家级审查者发展基于数据包操纵的审查规避策略，以增加其他被阻止内容的可用性.
- [GlobaLeaks](https://www.globaleaks.org/) - 免费的开源软件使任何人都可以轻松设置和维护安全的举报平台.
- [SecureDrop](https://securedrop.org/) - 媒体组织和非政府组织可以安装开源举报人提交系统，以安全地接受来自匿名来源的文件.
- [Teleport](https://goteleport.com/) - 允许工程师和安全专家在所有环境中统一对 SSH 服务器、Kubernetes 集群、Web 应用程序和数据库的访问.

## DevSecOps

也可以看看 [awesome-devsecops](https://github.com/devsecops/awesome-devsecops).

- [Bane](https://github.com/genuinetools/bane) - Custom and better AppArmor profile generator for Docker containers.
- [BlackBox](https://github.com/StackExchange/blackbox) - 通过使用 GnuPG 加密“静态”秘密，将秘密安全地存储在 Git/Mercurial/Subversion 中.
- [Cilium](https://cilium.io/) - 开源软件，用于透明地保护使用 Linux 容器管理平台（如 Docker 和 Kubernetes）部署的应用程序服务之间的网络连接.
- [Clair](https://github.com/coreos/clair) - 用于探测通过应用程序容器（例如 Docker）镜像引入的漏洞的静态分析工具.
- [CodeQL](https://securitylab.github.com/tools/codeql) - 通过像数据一样对代码执行查询来发现代码库中的漏洞.
- [DefectDojo](https://www.defectdojo.org/) - 为 DevOps 和持续安全集成构建的应用程序漏洞管理工具.
- [Gauntlt](http://gauntlt.org/) - 在常规持续集成构建管道期间对应用程序进行渗透测试.
- [Git Secrets](https://github.com/awslabs/git-secrets) - 防止您将密码和其他敏感信息提交到 git 存储库.
- [SOPS](https://github.com/mozilla/sops) - 支持 YAML、JSON、ENV、INI 和二进制格式并使用 AWS KMS、GCP KMS、Azure Key Vault 和 PGP 加密的加密文件编辑器.
- [Snyk](https://snyk.io/) - 查找并修复开源依赖项和容器映像中的漏洞和许可证违规.
- [SonarQube](https://sonarqube.org) - 持续检查工具，可在自动测试期间提供详细报告，并对新引入的安全漏洞发出警报.
- [Trivy](https://github.com/aquasecurity/trivy) - 简单而全面的容器和其他工件的漏洞扫描器，适用于持续集成管道.
- [Vault](https://www.vaultproject.io/) - 用于通过统一界面安全访问机密信息（例如 API 密钥、密码或证书）的工具.
- [git-crypt](https://www.agwa.name/projects/git-crypt/)  - git中的透明文件加密； 您选择保护的文件在提交时加密，签出时解密.
- [helm-secrets](https://github.com/jkroepke/helm-secrets) - Helm 插件，帮助管理 Git 工作流程中的机密并将它们存储在任何地方，由 SOPS 支持.

### Application or Binary Hardening

- [DynInst](https://dyninst.org/dyninst) - 用于二进制检测、分析和修改的工具，对二进制修补很有用.
- [DynamoRIO](https://dynamorio.org/) - 运行时代码操作系统，支持程序任何部分的代码转换，同时它执行，作为进程级虚拟机实现.
- [Egalito](https://egalito.org/) - 二进制重新编译器和检测框架，可以完全反汇编、转换和重新生成专为二进制加固和安全研究设计的普通 Linux 二进制文件.
- [Valgrind](https://www.valgrind.org/) - 用于构建动态分析工具的检测框架.

### Compliance testing and reporting

- [Chef InSpec](https://www.chef.io/products/chef-inspec) - 用于描述安全性和合规性规则的语言，这些规则成为可以针对 IT 基础架构运行的自动化测试，以发现和报告不合规性.
- [OpenSCAP Base](https://www.open-scap.org/tools/openscap-base/) - 用于根据 SCAP 基线配置文件评估系统的库和命令行工具 (`oscap`)，以报告扫描系统的安全状况. 

### Fuzzing

也可以看看 [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

* [Atheris](https://pypi.org/project/atheris/) - 基于 libFuzzer 的覆盖引导 Python 模糊测试引擎，支持 Python 代码模糊测试以及为 CPython 编写的本机扩展.
* [FuzzBench](https://google.github.io/fuzzbench/) - 免费服务，可在 Google 规模的各种真实世界基准测试中评估模糊器.
* [OneFuzz](https://github.com/microsoft/onefuzz) - 自托管的模糊测试即服务 (FaaS) 平台.

### Policy enforcement

- [Conftest](https://conftest.dev/) - 帮助您针对结构化配置数据编写测试的实用程序.
- [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) - 统一的工具集和跨云原生堆栈的策略框架.
- [Tang](https://github.com/latchset/tang)  - 将数据绑定到网络存在的服务器； 仅当客户端位于特定（安全）网络上时才向客户端提供数据.

### Supply chain security

- [Grafeas](https://grafeas.io/) - 开放工件元数据 API 以审核和管理您的软件供应链.
- [Helm GPG (GnuPG) Plugin](https://github.com/technosophos/helm-gpg) - 使用 GnuPG for Helm 进行图表签名和验证.
- [Notary](https://github.com/theupdateframework/notary) - 旨在通过让人们轻松发布和验证内容来使互联网更加安全.

## Honeypots

也可以看看 [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens)  - 自托管的蜜币生成器和报告仪表板； 演示版可在 [CanaryTokens.org](https://canarytokens.org/).
- [Kushtaka](https://kushtaka.org) - 为资源不足的蓝队提供可持续的多合一蜜罐和蜜币协调器.

### Tarpits

- [Endlessh](https://github.com/skeeto/endlessh) - SSH tarpit 缓慢发送无尽的横幅.
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - 响应未使用 IP 空间的 ARP 请求的程序，创建假冒机器的外观，响应进一步请求的速度非常缓慢，以减慢扫描仪、蠕虫等的速度.

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) - 组合蜜罐、文件系统监视器和警报系统，旨在保护 Linux 和 Windows 操作系统.
- [chkrootkit](http://chkrootkit.org/) - 在 GNU/Linux 系统上本地检查 rootkit 的迹象.
- [Crowd Inspect](https://www.crowdstrike.com/resources/community-tools/crowdinspect-tool/) - 用于 Windows 系统的免费工具，旨在提醒您可能通过网络进行通信的恶意软件的存在.
- [Fail2ban](https://www.fail2ban.org/) - 保护计算机服务器免受暴力攻击的入侵防御软件框架.
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) - 完全开源且免费、功能丰富、基于主机的入侵检测系统 (HIDS).
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) - 符合 POSIX 标准的 Bash 脚本，可扫描主机以查找各种恶意软件迹象.

### Sandboxes

- [Bubblewrap](https://github.com/containers/bubblewrap) - 供非特权 Linux 用户使用的沙盒工具，能够限制对部分操作系统或用户数据的访问.
- [Dangerzone](https://dangerzone.rocks/) - 将具有潜在危险的 PDF、办公文档或图像转换为安全的 PDF.
- [Firejail](https://firejail.wordpress.com/) - SUID 程序，通过使用 Linux 命名空间和 seccomp-bpf 限制不受信任的应用程序的运行环境来降低安全漏洞的风险.

## Incident Response tools

也可以看看 [awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - 通过可视化和分析 Windows 事件日志来调查恶意 Windows 登录.
- [Volatility](https://www.volatilityfoundation.org/) - 高级内存取证框架.
- [aws_ir](https://github.com/ThreatResponse/aws_ir) - 以零安全准备假设自动化您的事件响应.

### IR management consoles

也可以看看 [Security Orchestration, Automation, and Response (SOAR)](#security-orchestration-automation-and-response-soar).

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) - 基于 Viper 构建的可编写脚本的数字取证和事件响应 (DFIR) 工具包.
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) - Cybersecurity incident management platform allowing for easy creation, tracking, and reporting of cybersecurity incidents.
- [Rekall](http://www.rekall-forensic.com/) - 高级取证和事件响应框架.
- [TheHive](https://thehive-project.org/) - 可扩展、免费的安全事件响应平台，旨在让 SOC、CSIRT 和 CERT 的生活更轻松，并与 MISP 紧密集成.
- [threat_note](https://github.com/defpoint/threat_note) - 由 Defense Point Security 构建的 Web 应用程序，允许安全研究人员添加和检索与其研究相关的指标.

### Evidence collection

- [AutoMacTC](https://github.com/CrowdStrike/automactc) - 模块化、自动化的取证分类收集框架，旨在访问 macOS 上的各种取证工件、解析它们并以可用于分析的格式呈现它们.
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) - 免费的 macOS 计算机取证工具.
- [OSXCollector](https://github.com/Yelp/osxcollector) - 适用于 macOS 的取证证据收集和分析工具包.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - Windows Batch 脚本和 Unix Bash 脚本，用于在事件响应期间全面收集主机取证数据.
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - 用于并行化远程内存获取的命令行实用程序（适用于或不适用 Amazon EC2 实例）.

## Network perimeter defenses

- [Gatekeeper](https://github.com/AltraMayor/gatekeeper) - 第一个开源分布式拒绝服务 (DDoS) 保护系统.
- [fwknop](https://www.cipherdyne.org/fwknop/) - 通过防火墙中的单包授权保护端口.
- [ssh-audit](https://github.com/jtesta/ssh-audit) - 一个简单的工具，可以为改进 SSH 服务器的安全状况提供快速建议.

### Firewall appliances or distributions

也可以看看 [Wikipedia: List of router and firewall distributions](https://en.wikipedia.org/wiki/List_of_router_and_firewall_distributions).

- [IPFire](https://www.ipfire.org/) - 从 IPCop 派生的基于 GNU/Linux 的强化路由器和防火墙分发.
- [OPNsense](https://opnsense.org/) - 从 pfSense 分叉的基于 FreeBSD 的强化防火墙和路由平台.
- [pfSense](https://www.pfsense.org/) - FreeBSD 防火墙和路由器发行版从 m0n0wall 派生出来.

## Operating System distributions

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) - 意大利 GNU/Linux 实时发行版，预先打包了大量数字取证和证据收集工具.
- [Security Onion](https://securityonion.net/) - 用于入侵检测、企业安全监控和日志管理的免费开源 GNU/Linux 发行版.
- [Qubes OS](https://qubes-os.org/) - 桌面环境构建在 Xen 管理程序项目之上，该项目在其自己的虚拟机中运行每个最终用户程序，旨在提供严格的安全控制，以限制任何成功的恶意软件利用的范围.

## Phishing awareness and reporting

也可以看看 [awesome-pentest § Social Engineering Tools](https://github.com/fabacab/awesome-pentest#social-engineering-tools).

- [CertSpotter](https://github.com/SSLMate/certspotter) - 来自 SSLMate 的证书透明度日志监视器，当为您的域之一颁发 SSL/TLS 证书时会向您发出警报.
- [Gophish](https://getgophish.com/) - 功能强大的开源网络钓鱼框架，可以轻松测试您的组织对网络钓鱼的暴露程度.
- [King Phisher](https://github.com/securestate/king-phisher) - 通过模拟真实世界的网络钓鱼攻击来测试和提高用户意识的工具.
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) - Outlook 插件用于帮助您的用户向安全团队报告可疑电子邮件.
- [Phishing Intelligence Engine (PIE)](https://github.com/LogRhythm-Labs/PIE) - 有助于检测和响应网络钓鱼攻击的框架.
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) - 允许创建和管理（假）网络钓鱼活动的平台，旨在培训人们识别可疑邮件. 
- [mailspoof](https://github.com/serain/mailspoof) - 扫描 SPF 和 DMARC 记录以查找可能允许电子邮件欺骗的问题.
- [phishing_catcher](https://github.com/x0rz/phishing_catcher) - 可配置的脚本以使用证书透明度日志 (CTL) 中的域名监视可疑 TLS 证书的发布 [CertStream](https://certstream.calidog.io/) 服务.

## Preparedness training and wargaming

（也称为*对手模拟*、*威胁模拟*或类似.）

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) - 使系统看起来好像是 APT 攻击的受害者的工具集.
- [Atomic Red Team](https://atomicredteam.io/) - 用于测试安全控制的简单、可自动化的测试库.
- [BadBlood](https://www.secframe.com/badblood/) - 使用数据填充测试（非生产）Windows 域，使安全分析师和工程师能够练习使用工具来了解和规定保护 Active Directory 的方法.
- [Drool](https://www.dns-oarc.net/tools/drool) - 从抓包文件中重放DNS流量并将其发送到指定的服务器，例如用于模拟对DNS的DDoS攻击和测量正常的DNS查询.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - 模块化、菜单驱动、跨平台工具，用于为蓝队演习和传感器/警报映射构建可重复、延时、分布式安全事件.
- [Metta](https://github.com/uber-common/metta) - 用于进行对抗性模拟的自动化信息安全准备工具.
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) - 用于生成恶意网络流量并帮助安全团队评估安全控制并审核其网络可见性的实用程序.
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) - 基于 Ubuntu 的开放虚拟设备 (`.ova`) 预先配置了多个威胁仿真工具以及防御者的工具包.

## Security configurations

（也称为*默认安全基线*和*已实施的最佳实践*.）

- [Bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx) - NginX 配置的 Docker 映像和为网站实施许多防御技术的脚本.

## Security monitoring

### Endpoint Detection and Response (EDR)

- [Wazuh](https://wazuh.com/) - 基于 OSSEC HIDS 分支的开源、基于多平台代理的安全监控.

### Network Security Monitoring (NSM)

也可以看看 [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [ChopShop](https://github.com/MITRECND/chopshop) - 帮助分析师创建和执行基于 pynids 的 APT 技术解码器和检测器的框架.
- [Maltrail](https://github.com/stamparm/maltrail) - 恶意网络流量检测系统.
- [Moloch](https://github.com/aol/moloch) - 增强您当前的安全基础设施，以标准 PCAP 格式存储和索引网络流量，提供快速的索引访问.
- [OwlH](https://www.owlh.net/) - 通过可视化 Suricata、Zeek 和 Moloch 生命周期，帮助大规模管理网络 IDS.
- [Real Intelligence Threat Analysis (RITA)](https://github.com/activecm/rita) - 用于网络流量分析的开源框架，可摄取 Zeek 日志并检测信标、DNS 隧道等.
- [Respounder](https://github.com/codeexpress/respounder) - 检测网络上是否存在响应者 LLMNR/NBT-NS/MDNS 投毒者.
- [Snort](https://snort.org/) - 广泛部署的免费软件 IPS，能够进行实时数据包分析、流量记录和基于规则的自定义触发器.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) - 捕获欺骗的 NetBIOS 名称服务 (NBNS) 响应并警告电子邮件或日志文件.
- [Stenographer](https://github.com/google/stenographer) - 完整的数据包捕获实用程序，用于将数据包缓冲到磁盘以进行入侵检测和事件响应.
- [Suricata](https://suricata-ids.org/) - 免费、跨平台、IDS/IPS，具有在线和离线分析模式以及深度数据包检测功能，也可使用 Lua 编写脚本.
- [Tsunami](https://github.com/google/tsunami-security-scanner) - 具有可扩展插件系统的通用网络安全扫描器，用于高可信度检测高严重性漏洞. 
- [VAST](https://github.com/tenzir/vast) - 用于数据驱动安全调查的免费开源网络遥测引擎.
- [Wireshark](https://www.wireshark.org) - 免费和开源的数据包分析器，可用于网络故障排除或取证网络流分析.
- [Zeek](https://zeek.org/) - 专注于安全监控的强大网络分析框架，原名Bro.
- [netsniff-ng](http://netsniff-ng.org/) - 免费且快速的 GNU/Linux 网络工具包，具有许多实用程序，例如连接跟踪工具 (`flowtop`)、流量生成器 (`trafgen`) 和自治系统 (AS) 跟踪路由实用程序 (`astraceroute`).

### Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - 由 AlienVault Open Threat Exchange (OTX) 驱动的单服务器开源 SIEM 平台，具有资产发现、资产盘点、行为监控和事件关联功能.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) - 具有悠久历史的开源、无代理 SIEM 和几个商业变体，具有安全事件收集、规范化和来自任意日志输入和众多流行监控工具的警报.

### Service and performance monitoring

也可以看看 [awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) - Nagios 的模块化重新设计，具有可插拔的用户界面和一组扩展的数据连接器、收集器和报告工具.
- [Locust](https://locust.io/) - 开源负载测试工具，您可以在其中使用 Python 代码定义用户行为，并让您的系统同时拥有数百万个用户.
- [Nagios](https://nagios.org) - 流行的网络和服务监控解决方案和报告平台.
- [OpenNMS](https://opennms.org/) - 免费且功能丰富的网络监控系统，支持多种配置、多种告警机制（email、XMPP、SMS）和多种数据采集方式（SNMP、HTTP、JDBC等）.
- [osquery](https://github.com/facebook/osquery) - 适用于 macOS、Windows 和 Linux 的操作系统检测框架，将操作系统公开为高性能关系数据库，可以使用类似 SQL 的语法进行查询.
- [Zabbix](https://www.zabbix.com/) - 成熟的企业级平台，用于监控大规模 IT 环境.

### Threat hunting

（也称为*狩猎组队*和*威胁检测*.）

也可以看看 [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) - 基于 CIM/WMI 的工具套件，支持跨所有 Windows 版本的远程事件响应和搜寻操作.
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) - PowerShell 模块，用于通过 Windows 事件日志进行狩猎组队.
- [GRR Rapid Response](https://github.com/google/grr) - 事件响应框架专注于远程实时取证，由安装在资产上的 Python 代理和基于 Python 的服务器基础设施组成，使分析师能够快速对攻击进行分类并远程执行分析.
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) - 基于 Elasticsearch、Logstash、Kafka 和 Kibana 的多合一免费软件威胁狩猎堆栈，具有各种内置分析集成，包括 Jupyter Notebook.
- [MozDef](https://github.com/mozilla/MozDef) - 自动化安全事件处理过程并促进事件处理者的实时活动.
- [PSHunt](https://github.com/Infocyte/PSHunt) - PowerShell 模块旨在扫描远程端点以查找入侵指标或调查它们以获取与这些系统状态相关的更全面信息.
- [PSRecon](https://github.com/gfoss/PSRecon) - 类似于 PSHunt 的工具，用于分析远程 Windows 系统，该工具还可以生成关于其发现的独立 HTML 报告.
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 一个基于 PowerShell 的平台，用于执行实时硬盘取证分析.
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) - 用于同时对多个端点上的可疑 IOC 进行分类并与防病毒控制台集成的多平台工具.
- [Redline](https://www.fireeye.com/services/freeware/redline.html) - 免费软件端点审计和分析工具，提供基于主机的调查功能，由 FireEye, Inc. 提供.

## Threat intelligence

也可以看看 [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths)  - 可视化并绘制 Active Directory 权限配置（“控制关系”）以审核诸如“谁可以阅读 CEO 的电子邮件？”等问题. 和类似的.
- [AttackerKB](https://attackerkb.com/) - 免费和公共的众包漏洞评估平台，帮助优先考虑高风险补丁应用程序和对抗漏洞疲劳.
- [DATA](https://github.com/hadojae/DATA) - 凭证网络钓鱼分析和自动化工具，可以直接接受可疑的网络钓鱼 URL 或触发观察到的包含此类 URL 的网络流量.
- [Forager](https://github.com/opensourcesec/Forager) - 使用 Python3 构建的多线程威胁情报收集，具有简单的基于文本的配置和数据存储，易于使用和数据可移植.
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) - 通过被动映射、说明和报告您的 ICS/SCADA 网络拓扑和端点，提供工业控制系统 (ICS) 和监督控制和数据采集 (SCADA) 的 IP 网络态势感知.
- [MLSec Combine](https://github.com/mlsecproject/combine) - 将多个威胁情报源收集并组合成一种可自定义的、基于 CSV 的标准化格式.
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) - 用于收集、存储、分发和共享网络安全指标的开源软件解决方案.
- [Open Source Vulnerabilities (OSV)](https://osv.dev/) - 开源项目的漏洞数据库和分类基础设施，旨在帮助开源维护者和开源消费者.
- [Sigma](https://github.com/Neo23x0/sigma) - SIEM 系统的通用签名格式，提供开放的签名格式，允许您以直接的方式描述相关的日志事件.
- [Threat Bus](https://github.com/tenzir/threatbus) - 威胁情报传播层通过分布式发布/订阅消息代理连接安全工具.
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) - 从威胁源（包括 Twitter、RSS 源或其他来源）中提取和聚合 IOC 的可扩展工具.
- [Unfetter](https://nsacyber.github.io/unfetter/) - 通过利用 Mitre 的 ATT&amp;CK 框架识别安全态势中的防御漏洞.
- [Viper](https://github.com/viper-framework/viper) - 二进制分析和管理框架，可以轻松组织恶意软件和漏洞利用样本.
- [YARA](https://github.com/VirusTotal/yara) - 旨在（但不限于）帮助恶意软件研究人员识别和分类恶意软件样本的工具，被描述为文件模式和签名的“模式匹配瑞士军刀”.

### Threat signature packages and collections

- [ESET's Malware IoCs](https://github.com/eset/malware-ioc) - 从 ESET 的各种调查中得出的妥协指标 (IOC).
- [FireEye's Red Team Tool Countermeasures](https://github.com/fireeye/red_team_tool_countermeasures) - 用于检测使用 FireEye 自己的 Red Team 工具进行的攻击的 Snort 和 YARA 规则集合，在 FireEye 于 2020 年 12 月披露违规行为后首次发布.
- [FireEye's Sunburst Countermeasures](https://github.com/fireeye/sunburst_countermeasures) - 各种语言的 IoC 集合，用于检测后门 SolarWinds Orion NMS 活动和相关漏洞.
- [YARA Rules](https://github.com/Yara-Rules/rules) - 项目涵盖了 IT 安全研究人员拥有一个单一存储库的需求，其中不同的 Yara 签名被编译、分类并尽可能保持最新.

## Tor Onion service defenses

也可以看看 [awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) - 提供负载平衡，同时通过消除单点故障使 Onion 服务更具弹性和可靠性.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - 第 3 版洋葱服务防护发现攻击缓解脚本（旨在最终包含在 Tor 核心中）.

## Transport-layer defenses

- [Certbot](https://certbot.eff.org/) - 自动发布和更新 TLS 证书的免费工具 [LetsEncrypt Root CA](https://letsencrypt.org/) 带有配置各种 Web 和电子邮件服务器软件的插件.
- [MITMEngine](https://github.com/cloudflare/mitmengine) - 用于服务器端检测 TLS 拦截事件的 Golang 库.
- [OpenVPN](https://openvpn.net/) - 开源、基于 SSL/TLS 的虚拟专用网络 (VPN).
- [Tor](https://torproject.org/) - 审查规避和匿名覆盖网络提供分布式、加密验证的名称服务（`.onion` 域），以增强发布者的隐私和服务可用性.

## macOS-based defenses

也可以看看 [drduh/macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide).

- [BlockBlock](https://objective-see.com/products/blockblock.html) - 监控常见的持久性位置并在添加持久性组件时发出警报，这有助于检测和防止恶意软件安装.
- [LuLu](https://objective-see.com/products/lulu.html) - 免费的 macOS 防火墙.
- [Santa](https://github.com/google/santa) - 在 macOS 的允许/拒绝列表系统中跟踪顽皮或漂亮的二进制文件.
- [Stronghold](https://github.com/alichtman/stronghold) - 从终端轻松配置 macOS 安全设置.
- [macOS Fortress](https://github.com/essandess/macOS-Fortress) - 内核级、操作系统级和客户端级安全功能的自动配置，包括 macOS 的私有化代理和防病毒扫描.

## Windows-based defenses

也可以看看 [awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security) 和 [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening).

- [HardenTools](https://github.com/securitywithoutborders/hardentools) - 禁用许多有风险的 Windows 功能的实用程序.
- [NotRuler](https://github.com/sensepost/notruler) - 检测客户端使用的客户端规则和启用 VBScript 的表单 [Ruler](https://github.com/sensepost/ruler) 尝试破坏 Microsoft Exchange 服务器时的攻击工具.
- [PlumHound](https://github.com/PlumHound/PlumHound) - 通过利用其寻路引擎识别 Active Directory 安全漏洞，在持续的安全生命周期中更有效地使用 BloodHoundAD.
- [Sandboxie](https://www.sandboxie.com/) - 免费和开源的通用 Windows 应用程序沙箱实用程序.
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - 对照 Microsoft 审核 Windows 主机的根证书存储 [Certificate Trust List (CTL)](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview).
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) - 从主机名列表建立 Windows RDP 会话并扫描辅助工具后门，如果发现后门，则发出警报.
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) - 组策略对象、合规性检查和配置工具，为安全部署和维护最新版本的 Windows 10 提供自动化和灵活的方法.
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) - 将新创建的 WMI 使用者和进程记录到 Windows 应用程序事件日志中.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

这项工作已获得许可 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
