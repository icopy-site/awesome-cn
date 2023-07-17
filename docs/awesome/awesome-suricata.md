<div class="github-widget" data-repo="satta/awesome-suricata"></div>
## Awesome Suricata [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[<img src="https://suricata.io/wp-content/uploads/2022/01/Logo-SuricataFinal-1-translucent.png" align="right" width="120">](https://suricata.io)

&gt; 与 Suricata 相关的精彩事物的精选列表.

[Suricata](https://suricata.io/features) 是一个免费的入侵检测/预防系统（IDS/IPS）和网络安全监控引擎.




## Input Tools

- [PacketStreamer](https://github.com/deepfence/PacketStreamer) - 适用于云原生环境的分布式 tcpdump.


## Output Tools

- [suricata-kafka-output](https://github.com/Center-Sun/suricata-kafka-output) - Suricata 6 的 Suricata Eve Kafka 输出插件.
- [suricata-redis-output](https://github.com/jasonish/suricata-redis-output) -Suricata 7 的 Suricata Eve Redis 输出插件.
- [Meer](https://github.com/quadrantsec/meer) - Meer 是 Suricata / Sagan 的“假脱机者”.
- [FEVER](https://github.com/DCSO/fever) - 适用于 Suricata 的 EVE-JSON 格式的快速、可扩展、多功能事件路由器.
- [Suricata-Logstash-Templates](https://github.com/pevma/Suricata-Logstash-Templates) - Kibana/Logstash 与 Suricata IDPS 一起使用的模板.
- [Lilith](https://github.com/VVelox/Lilith) - 将 EVE 文件读入 SQL 并搜索存储的数据.


## Operations, Monitoring and Troubleshooting

- [slinkwatch](https://github.com/DCSO/slinkwatch) - Suricata监控接口的自动枚举和维护.
- [suri-stats](https://github.com/regit/suri-stats) - 用于处理 suricata `stats.log` 文件的工具.
- [Mauerspecht](https://github.com/DCSO/mauerspecht) - 用于企业围墙花园网络的简单探测工具.
- [ansible-suricata](https://github.com/GitMirar/ansible-suricata) - Suricata Ansible 角色（稍微过时）.
- [MassDeploySuricata](https://github.com/pevma/MassDeploySuricata) - 使用 Ansible IT 自动化平台大规模部署和更新 Suricata IDPS.
- [docker-suricata](https://github.com/jasonish/docker-suricata) - Suricata Docker 镜像.
- [Suricata-Monitoring](https://github.com/VVelox/Suricata-Monitoring) - LibreNMS JSON / Nagios 监控 Suricata 统计数据.
- [Terraform Module for Suricata](https://github.com/onetwopunch/terraform-google-suricata) - Terraform 模块用于设置 Google Cloud 数据包镜像并将数据包发送到 Suricata.
- [InfluxDB Suricata Input Plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/suricata) - Telegraf 的输入插件，用于收集和转发 Suricata `stats` 日志（在最近的 Telegraf 版本中包含开箱即用）.
- [suricata_exporter](https://github.com/corelight/suricata_exporter) - 用 Go 编写的简单 Prometheus 导出器，导出从 Suricata 套接字抓取的统计指标.

## Programming Libraries and Toolkits

- [rust-suricatax-rule-parser](https://github.com/jasonish/rust-suricatax-rule-parser) - Rust 中的实验性 Suricata 规则解析器.
- [go-suricata](https://github.com/ks2211/go-suricata) - Suricata 的 Go 客户端（通过套接字交互）.
- [gonids](https://github.com/google/gonids) - Go 库解析 Snort 和 Suricata 等引擎的入侵检测规则.
- [surevego](https://github.com/rhaist/surevego) - Go 中的 Suricata EVE-JSON 解析器.
- [suricataparser](https://github.com/m-chrome/py-suricataparser) - 用于 Snort/Suricata 规则的纯 python 解析器.
- [py-idstools](https://github.com/jasonish/py-idstools) - Python 中的 Snort 和 Suricata 规则和事件实用程序（包括规则更新工具）.


## Dashboards and Templates

- [KTS](https://github.com/StamusNetworks/KTS) - 用于 Suricata IDPS 威胁追踪的 Kibana 4 模板.
- [KTS5](https://github.com/StamusNetworks/KTS5) - 用于 Suricata IDPS 威胁追踪的 Kibana 5 模板.
- [KTS6](https://github.com/StamusNetworks/KTS6) - 用于 Suricata IDPS 威胁追踪的 Kibana 6 模板.
- [KTS7](https://github.com/StamusNetworks/KTS7) - 用于 Suricata IDPS 威胁追踪的 Kibana 7 模板.


## Development Tools

- [Suricata Language Server](https://github.com/StamusNetworks/suricata-language-server)  - Suricata 语言服务器是 Suricata 签名语言服务器协议的实现. 配置后，它会向您的首选编辑器添加语法检查、提示和自动完成功能.
- [suricata-ls-vscode](https://github.com/StamusNetworks/suricata-ls-vscode) - 使用 Suricata 语言服务器的 Suricata IntelliSense 扩展.
- [suricata-highlight-vscode](https://github.com/dgenzer/suricata-highlight-vscode) - Suricata 规则支持 Visual Studio Code（语法突出显示等）.
- [SublimeSuricata](https://github.com/ozuriexv/SublimeSuricata) - Sublime Text 的基本 Suricata 语法荧光笔.


## Documentation and Guides

- [SEPTun](https://github.com/pevma/SEPTun) - Suricata 极限性能调整指南.
- [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - Suricata 极限性能调整指南 - Mark II.
- [suricata-4-analysts](https://github.com/StamusNetworks/suricata-4-analysts) - Suricata 安全分析师指南.


## Analysis Tools

- [Suricata Analytics](https://github.com/StamusNetworks/suricata-analytics) - 与 Suricata 数据交互时有用的各种资源.
- [Malcolm](https://github.com/cisagov/Malcolm) - 功能强大、易于部署的网络流量分析工具套件，用于完整的数据包捕获工件（PCAP 文件）、Zeek 日志和 Suricata 警报.
- [Evebox](https://github.com/jasonish/evebox) - Elastic Search 中 Suricata EVE 事件的基于 Web 的事件查看器 (GUI).


## Rule Sets

- [nids-rule-library](https://github.com/klingerko/nids-rule-library#readme) - 各种开源和商业规则集的集合.
- [Stamus Lateral Movement Detection Rules](https://www.stamus-networks.com/blog/new-open-ruleset-for-detecting-lateral-movement-with-suricata) - Suricata 规则集用于检测横向运动.
- [QuadrantSec Suricata Rules](https://github.com/quadrantsec/suricata-rules) - QuadrantSec Suricata 规则.
- [Cluster25/detection](https://github.com/Cluster25/detection) - Cluster25的检测规则.
- Networkforensic.dk (NF) 规则集： 
  - [NF IDS rules](https://networkforensic.dk/SNORT/NF-local.zip)
  - [NF SCADA IDS Rules](https://networkforensic.dk/SNORT/NF-SCADA.zip)
  - [NF Scanners IDS Rules](https://networkforensic.dk/SNORT/NF-Scanners.zip)
- [Quantum Insert detection for Suricata](https://github.com/fox-it/quantuminsert/blob/master/detection/suricata/README.md) - Suricata 规则伴随着 Fox-IT 的 QUANTUM 2015 博客/BroCon 演讲.
- [Hunting rules](https://github.com/travisbgreen/hunting-rules) - Travis Green 用于网络异常检测的 Suricata IDS 警报规则.
- [3CORESec NIDS - Lateral Movement](https://dtection.io/ruleset/3cs_lateral) - Suricata 规则集侧重于横向运动技术（付费）.
- [3CORESec NIDS - Sinkholes](https://dtection.io/ruleset/3cs_sinkholes) - Suricata 规则集专注于公共恶意软件陷阱的精选列表（免费）.



- [sidallocation.org](https://sidallocation.org/) - Sid 分配工作组，SID 范围列表.
- [Scirius](https://github.com/StamusNetworks/scirius) - 用于 Suricata 规则集管理和威胁搜寻的 Web 应用程序.
- [IOCmite](https://github.com/sebdraven/IOCmite) - 使用 MISP 实例指标创建 Suricata 数据集的工具，并在数据集指标生成警报时在 MISP 中添加目击事件.
- [luaevilbit](https://github.com/regit/luaevilbit) - luajit 中针对 Suricata 的邪恶位实现.
- [Lawmaker](https://www.3coresec.com/lawmaker) - Suricata IDS 规则管理系统.
- [surify-cli](https://github.com/dgenzer/surify-cli) - 根据您的 Suricata 模板，从 IOC（JSON、CSV 或标志）集合中生成 Suricata 规则.
- [suricata-prettifier](https://github.com/theY4Kman/suricata-prettifier) - 用于格式化和语法突出显示 Suricata 规则的命令行工具.
- [OTX-Suricata](https://github.com/AlienVault-OTX/OTX-Suricata) - 为 Suricata 创建规则和配置，以针对来自 OTX 账户的指标发出警报.


## Systems Using Suricata

- [SELKS](https://github.com/StamusNetworks/SELKS) - 基于Suricata的入侵检测系统/入侵防御系统/网络安全监控分布.
- [Amsterdam](https://github.com/StamusNetworks/Amsterdam) - 基于 Docker 的 Suricata、Elasticsearch、Logstash、Kibana、Scirius 又名 SELKS.
- [pfSense](https://www.pfsense.org) - 免费网络防火墙发行版，基于具有自定义内核的 FreeBSD 操作系统，并包含用于附加功能的第三方免费软件包.
- [OPNsense](https://opnsense.org) - 一个开源、易于使用且易于构建的基于 FreeBSD 的防火墙和路由平台.


## Training

- [Experimental Suricata Training Environment](https://github.com/jasonish/experimental-suricata-training) - 实验 Suricata 训练环境.
- [CDMCS](https://github.com/ccdcoe/CDMCS/tree/master) - 网络防御监控课程：基于规则的威胁检测.


## Simulation and Testing

- [Leonidas](https://github.com/WithSecureLabs/leonidas) - 云端自动攻击模拟，包含检测用例.
- [speeve](https://github.com/satta/speeve) - 快速、概率性 EVE-JSON 生成器，用于对 EVE 消费应用程序进行测试和基准测试.
- [Dalton](https://github.com/secureworks/dalton) - Suricata 和 Snort IDS 规则和 pcap 测试系统.


## Data Sets

- [suricata-sample-data](https://github.com/FrankHassanabad/suricata-sample-data) - 创建不同示例 Suricata 数据集的存储库.


## Misc

- [Suriwire](https://github.com/regit/suriwire) - Wireshark 插件显示 Suricata 分析信息.
- [bash_cata](https://github.com/isMTv/bash_cata) - 一个简单的脚本，实时处理生成的 Suricata eve-log，并根据警报，在指定时间内将 IP 地址添加到 MikroTik 地址列表中，以进行后续阻止.
- [suriGUI](https://github.com/control-owl/suriGUI) - Suricata + Qubes 操作系统的 GUI.
