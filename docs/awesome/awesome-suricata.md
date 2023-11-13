<div class="github-widget" data-repo="satta/awesome-suricata"></div>
## Awesome Suricata [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[<img src="https://suricata.io/wp-content/uploads/2022/01/Logo-SuricataFinal-1-translucent.png" align="right" width="120">](https://suricata.io)

> Curated list of awesome things related to Suricata.

[Suricata](https://suricata.io/features) is a free intrusion detection/prevention system (IDS/IPS) and network security monitoring engine.




## Input Tools

- [PacketStreamer](https://github.com/deepfence/PacketStreamer) - Distributed tcpdump for cloud native environments.


## Output Tools

- [suricata-kafka-output](https://github.com/Center-Sun/suricata-kafka-output) - Suricata Eve Kafka Output Plugin for Suricata 6.
- [suricata-redis-output](https://github.com/jasonish/suricata-redis-output) - Suricata Eve Redis Output Plugin for Suricata 7.
- [Meer](https://github.com/quadrantsec/meer) - Meer is a "spooler" for Suricata / Sagan.
- [FEVER](https://github.com/DCSO/fever) - Fast, extensible, versatile event router for Suricata's EVE-JSON format.
- [Suricata-Logstash-Templates](https://github.com/pevma/Suricata-Logstash-Templates) - Templates for Kibana/Logstash to use with Suricata IDPS.
- [Lilith](https://github.com/VVelox/Lilith) - Reads EVE files into SQL as well as search stored data.


## Operations, Monitoring and Troubleshooting

- [slinkwatch](https://github.com/DCSO/slinkwatch) - Automatic enumeration and maintenance of Suricata monitoring interfaces.
- [suri-stats](https://github.com/regit/suri-stats) - A tool to work on suricata `stats.log` file.
- [Mauerspecht](https://github.com/DCSO/mauerspecht) - Simple Probing Tool for Corporate Walled Garden Networks.
- [ansible-suricata](https://github.com/GitMirar/ansible-suricata) - Suricata Ansible role (slightly outdated).
- [MassDeploySuricata](https://github.com/pevma/MassDeploySuricata) - Mass deploy and update Suricata IDPS using Ansible IT automation platform.
- [docker-suricata](https://github.com/jasonish/docker-suricata) - Suricata Docker image.
- [Suricata-Monitoring](https://github.com/VVelox/Suricata-Monitoring) - LibreNMS JSON / Nagios monitor for Suricata stats.
- [Terraform Module for Suricata](https://github.com/onetwopunch/terraform-google-suricata) - Terraform module to setup Google Cloud packet mirroring and send packets to Suricata.
- [InfluxDB Suricata Input Plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/suricata) - Input Plugin for Telegraf to collect and forward Suricata `stats` logs (included out of the box in recent Telegraf releases).
- [suricata_exporter](https://github.com/corelight/suricata_exporter) - Simple Prometheus exporter written in Go exporting stats metrics scraped from Suricata socket.

## Programming Libraries and Toolkits

- [rust-suricatax-rule-parser](https://github.com/jasonish/rust-suricatax-rule-parser) - Experimental Suricata Rule Parser in Rust.
- [go-suricata](https://github.com/ks2211/go-suricata) - Go Client for Suricata (Interacting via Socket).
- [gonids](https://github.com/google/gonids) - Go library to parse intrusion detection rules for engines like Snort and Suricata.
- [surevego](https://github.com/rhaist/surevego) - Suricata EVE-JSON parser in Go.
- [suricataparser](https://github.com/m-chrome/py-suricataparser) - Pure python parser for Snort/Suricata rules.
- [py-idstools](https://github.com/jasonish/py-idstools) - Snort and Suricata Rule and Event Utilities in Python (Including a Rule Update Tool).


## Dashboards and Templates

- [KTS](https://github.com/StamusNetworks/KTS) - Kibana 4 Templates for Suricata IDPS Threat Hunting.
- [KTS5](https://github.com/StamusNetworks/KTS5) - Kibana 5 Templates for Suricata IDPS Threat Hunting.
- [KTS6](https://github.com/StamusNetworks/KTS6) - Kibana 6 Templates for Suricata IDPS Threat Hunting.
- [KTS7](https://github.com/StamusNetworks/KTS7) - Kibana 7 Templates for Suricata IDPS Threat Hunting.


## Development Tools

- [Suricata Language Server](https://github.com/StamusNetworks/suricata-language-server) - Suricata Language Server is an implementation of the Language Server Protocol for Suricata signatures. It adds syntax check, hints and auto-completion to your preferred editor once it is configured.
- [suricata-ls-vscode](https://github.com/StamusNetworks/suricata-ls-vscode) - Suricata IntelliSense Extension using the Suricata Language Server.
- [suricata-highlight-vscode](https://github.com/dgenzer/suricata-highlight-vscode) - Suricata Rules Support for Visual Studio Code (syntax highlighting, etc).
- [SublimeSuricata](https://github.com/ozuriexv/SublimeSuricata) - Basic Suricata syntax highlighter for Sublime Text.


## Documentation and Guides

- [SEPTun](https://github.com/pevma/SEPTun) - Suricata Extreme Performance Tuning guide.
- [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - Suricata Extreme Performance Tuning guide - Mark II.
- [suricata-4-analysts](https://github.com/StamusNetworks/suricata-4-analysts) - The Security Analyst's Guide to Suricata.


## Analysis Tools

- [Suricata Analytics](https://github.com/StamusNetworks/suricata-analytics) - Various resources that are useful when interacting with Suricata data.
- [Malcolm](https://github.com/cisagov/Malcolm) - A powerful, easily deployable network traffic analysis tool suite for full packet capture artifacts (PCAP files), Zeek logs and Suricata alerts.
- [Evebox](https://github.com/jasonish/evebox) - Web Based Event Viewer (GUI) for Suricata EVE Events in Elastic Search.


## Rule Sets

- [nids-rule-library](https://github.com/klingerko/nids-rule-library#readme) - Collection of various open-source and commercial rulesets.
- [Stamus Lateral Movement Detection Rules](https://www.stamus-networks.com/blog/new-open-ruleset-for-detecting-lateral-movement-with-suricata) - Suricata ruleset to detect lateral movement.
- [QuadrantSec Suricata Rules](https://github.com/quadrantsec/suricata-rules) - QuadrantSec Suricata rules.
- [Cluster25/detection](https://github.com/Cluster25/detection) - Cluster25's detection rules.
- Networkforensic.dk (NF) rules sets: 
  - [NF IDS rules](https://networkforensic.dk/SNORT/NF-local.zip)
  - [NF SCADA IDS Rules](https://networkforensic.dk/SNORT/NF-SCADA.zip)
  - [NF Scanners IDS Rules](https://networkforensic.dk/SNORT/NF-Scanners.zip)
- [Quantum Insert detection for Suricata](https://github.com/fox-it/quantuminsert/blob/master/detection/suricata/README.md) - Suricata rules accompanying Fox-IT's QUANTUM 2015 blog/BroCon talk.
- [Hunting rules](https://github.com/travisbgreen/hunting-rules) - Suricata IDS alert rules for network anomaly detection from Travis Green.
- [3CORESec NIDS - Lateral Movement](https://dtection.io/ruleset/3cs_lateral) - Suricata ruleset focusing on lateral movement techniques (paid).
- [3CORESec NIDS - Sinkholes](https://dtection.io/ruleset/3cs_sinkholes) - Suricata ruleset focused on a curated list of public malware sinkholes (free).
- [PAW Patrules](https://pawpatrules.fr) - Another free (CC BY-NC-SA) collection of rules for the Suricata engine.



- [sidallocation.org](https://sidallocation.org/) - Sid Allocation working group, list of SID ranges.
- [Scirius](https://github.com/StamusNetworks/scirius) - Web application for Suricata ruleset management and threat hunting.
- [IOCmite](https://github.com/sebdraven/IOCmite) - Tool to create dataset for suricata with indicators of MISP instances and add sightings in MISP if an indicator of dataset generates an alert.
- [luaevilbit](https://github.com/regit/luaevilbit) - An Evil bit implementation in luajit for Suricata.
- [Lawmaker](https://www.3coresec.com/lawmaker) - Suricata IDS rule management system.
- [surify-cli](https://github.com/dgenzer/surify-cli) - Generate suricata-rules from collection of IOCs (JSON, CSV or flags) based on your suricata template.
- [suricata-prettifier](https://github.com/theY4Kman/suricata-prettifier) - Command-line tool to format and syntax highlight Suricata rules.
- [OTX-Suricata](https://github.com/AlienVault-OTX/OTX-Suricata) - Create rules and configuration for Suricata to alert on indicators from an OTX account.
- [Aristotle](https://github.com/secureworks/aristotle) - Simple Python program that allows for the filtering and modifying of Suricata and Snort rulesets based on interpreted key-value pairs present in the metadata keyword within each rule.


## Systems Using Suricata

- [SELKS](https://github.com/StamusNetworks/SELKS) - A Suricata-based intrusion detection system/intrusion prevention system/network security monitoring distribution.
- [Amsterdam](https://github.com/StamusNetworks/Amsterdam) - Docker based Suricata, Elasticsearch, Logstash, Kibana, Scirius aka SELKS.
- [pfSense](https://www.pfsense.org) - A free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality.
- [OPNsense](https://opnsense.org) - An open source, easy-to-use and easy-to-build FreeBSD based firewall and routing platform.


## Training

- [Experimental Suricata Training Environment](https://github.com/jasonish/experimental-suricata-training) - Experimental Suricata Training Environment.
- [CDMCS](https://github.com/ccdcoe/CDMCS/tree/master) - Cyber Defence Monitoring Course: Rule-based Threat Detection.


## Simulation and Testing

- [Leonidas](https://github.com/WithSecureLabs/leonidas) - Automated Attack Simulation in the Cloud, complete with detection use cases.
- [speeve](https://github.com/satta/speeve) - Fast, probabilistic EVE-JSON generator for testing and benchmarking of EVE-consuming applications.
- [Dalton](https://github.com/secureworks/dalton) - Suricata and Snort IDS rule and pcap testing system.


## Data Sets

- [suricata-sample-data](https://github.com/FrankHassanabad/suricata-sample-data) - Repository of creating different example suricata data sets.


## Misc

- [Suriwire](https://github.com/regit/suriwire) - Wireshark plugin to display Suricata analysis info.
- [bash_cata](https://github.com/isMTv/bash_cata) - A simple script that processes the generated Suricata eve-log in real time and, based on alerts, adds an ip-address to the MikroTik Address Lists for a specified time for subsequent blocking.
- [suriGUI](https://github.com/control-owl/suriGUI) - GUI for Suricata + Qubes OS.
