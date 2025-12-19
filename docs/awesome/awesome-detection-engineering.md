<div class="github-widget" data-repo="infosecB/awesome-detection-engineering"></div>
## Awesome Detection Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Detection Engineering is a tactical function of a cybersecurity defense program that involves the design, implementation, and operation of detective controls with the goal of proactively identifying malicious or unauthorized activity before it negatively impacts an individual or an organization.

All contributions are welcome, please carefully review the [contributing guidelines](https://github.com/infosecB/awesome-detection-engineering/blob/main/contributing.md) prior to submitting a pull request.



## Concepts & Frameworks 

- [MITRE ATT&CK](https://attack.mitre.org/) - The foundational framework of adversary tactics, techniques, and procedures based on real-world observations.
- [Alerting and Detection Strategies (ADS) Framework | Palantir](https://github.com/palantir/alerting-detection-strategy-framework) - A blueprint for creating and documenting effective detection content.
- [Detection Engineering Maturity Matrix | Kyle Bailey](https://detectionengineering.io) - A detailed matrix that serves as a tool to measure the overall maturity of an organization's Detection Engineering program. 
- [Detection Maturity Level (DML) Model | Ryan Stillions](http://ryanstillions.blogspot.com/2014/04/the-dml-model_21.html) - Defines and describes 8 different levels of an organization's threat detection program maturity.
- [The Pyramid of Pain | David J Bianco](http://detect-respond.blogspot.com/2013/03/the-pyramid-of-pain.html) - A model used to describe various categorizations of indicator's of compromise and their level of effectiveness in detecting threat actors. 
- [Cyber Kill Chain | Lockheed Martin](https://www.lockheedmartin.com/us/what-we-do/aerospace-defense/cyber/cyber-kill-chain.html) - Lockheed Martin's framework that outlines the 7 stages commonly observed in a cyber attack.
- [MaGMa (Management, Growth and Metrics & Assessment) Use Case Defintion Model](https://www.betaalvereniging.nl/wp-content/uploads/FI-ISAC-use-case-framework-verkorte-versie.pdf) - A business-centric approach for defining threat detection use cases.
- [Synthetic Adversarial Log Objects (SALO) | Splunk](https://github.com/splunk/salo) - Synthetic Adversarial Log Objects (SALO) is a framework for the generation of log events without the need for infrastructure or actions to initiate the event that causes a log event.
- [The Zen of Security Rules | Justin Ibarra](https://br0k3nlab.com/resources/zen-of-security-rules/) - Outlines 19 aphorisms that serve as universal principles for the creation of high quality detection content.
- [Blue-team-as-Code - the Spiral of Joy | Den Iuzvyk, Oleg Kolesnikov](https://sansorg.egnyte.com/dl/KTc16ldiqv) - Blue-Team-as-Code: Lessons From Real-world Red Team Detection Automation Using Logs.
- [Detection Development Lifecycle | Haider Dost et al.](https://medium.com/snowflake/detection-development-lifecycle-af166fffb3bc) - Snowflake’s implementation of the Detection Development Lifecycle.
- [Threat Detection Maturity Framework | Haider Dost of Snowflake](https://medium.com/snowflake/threat-detection-maturity-framework-23bbb74db2bc) - A maturity matrix to measure the success of your threat detection program.
- [Elastic's Detection Engineering Behavior Maturity Model](https://www.elastic.co/security-labs/elastic-releases-debmm) - Elastic's qualitative and quantitative approach to measuring threat detection program maturity.
- [Prioritizing Detection Engineering | Ryan McGeehan](https://medium.com/starting-up-security/prioritizing-detection-engineering-b60b46d55051) - A longtime detection engineer outlines how a detection engineering program should be built from the ground up.
- [Detection Engineering Field Manual | Zack Allen](https://www.detectionengineering.net/s/field-manual) - a series of posts exploring the various foundational components of Detection Engineering.
- [Open Threat Informed Detection Engineering aka OpenTide'](https://github.com/OpenTideHQ) - an all-in-one Detection Engineering Operations framework created and maintained by the European Commission to convert your CTI into an actionable detection coverage graph combining threat vectors with detection objectives, and manage your entire detection library from a central repository with a detection-as-code deployment system. The OpenTide format aims at measuring and expanding detection coverage, and its rule deployment engine is fully extensible and support multiple platforms in parallel (leveraging all the technology features and native query language). OpenTide works both within a single DE team as a main framework, and across SOC as a common format to facilitate data interexchange.


- [Rulehound](https://rulehound.com) - An index of publicly available and open-source threat detection rulesets.
- [MITRE Cyber Analytics Repository (CAR)](https://car.mitre.org) - MITRE's well-maintained repository of detection content.
- [CAR Coverage Comparision](https://car.mitre.org/coverage/) - A matrix of MITRE ATT&CK technique IDs and links to available Splunk Security Content, Elastic detection rules, Sigma rules, and CAR content.
- [Sigma Rules](https://github.com/Neo23x0/sigma) - Sigma's repository of turnkey detection content. Content can be converted for use with most SIEMs.
- [Sigma rule converter](https://sigconverter.io/) - An opensource tool that can convert detection content for use with most SIEMs.
- [AttackRuleMap](https://attackrulemap.com) - Mapping of open-source detection rules and atomic tests.
- [Splunk Security Content](https://github.com/splunk/security_content) - Splunk's open-source and frequently updated detection content that can be tweaked for use in other tools.
- [Elastic Detection Rules](https://github.com/elastic/detection-rules/tree/main/rules) - Elastic's detection rules written natively for the Elastic SIEM. Can easily be converted for use by other SIEMs using Uncoder.
- [Elastic Endpoint Behavioral Rules](https://github.com/elastic/protections-artifacts/tree/main/behavior/rules) - Elastic's endpoint behavioral (prevention) rules written in EQL, natively for the Elastic endpoint agent.
- [Elastic Yara Signatures](https://github.com/elastic/protections-artifacts/tree/main/yara/rules) - Elastic's YARA signatures, which run on the Elastic endpoint agent.
- [Elastic Endpoint Ransomware Artifact](https://github.com/elastic/protections-artifacts/tree/main/ransomware/artifact.lua) - Elastic's ranswomware artifact, which runs on the Elastic endpoint agent.
- [Chronicle (GCP) Detection Rules](https://github.com/chronicle/detection-rules) - Chronicle's detection rules written natively for the the Chronicle Platform.
- [Exabeam Content Library](https://github.com/ExabeamLabs/Content-Library-CIM2) - Exabeam's out of the box detection content compatible with the Exabeam Common Information Model.
- [Panther Labs Detection Rules](https://github.com/panther-labs/panther-analysis/tree/master/rules) - Panther Lab's native detection rules.
- [Anvilogic Detection Armory](https://github.com/anvilogic-forge/armory) - Anvilogic's opensource and publicly available detection content.
- [AWS GuardDuty Findings](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_finding-types-active.html) - A list of all AWS GuardDuty Findings, their descriptions, and associated data sources.
- [GCP Security Command Center Findings](https://cloud.google.com/security-command-center/docs/concepts-security-sources#threats) - A list of all GCP Security Command Center Findings, their descriptions, and associated data sources.
- [Azure Defender for Cloud Security Alerts](https://docs.microsoft.com/en-us/azure/defender-for-cloud/alerts-reference) - A list of all Azure Security for Cloud Alerts, their descriptions, and associated data sources.
- [Center for Threat Informed Defense Security Stack Mappings](https://github.com/center-for-threat-informed-defense/security-stack-mappings) - Describes cloud computing platform's (Azure, AWS) built-in detection capabilities and their mapings to the MITRE ATT&CK framework.
- [Detection Engineering with Splunk](https://github.com/west-wind/Threat-Hunting-With-Splunk) - A GitHub repo dedicated to sharing detection analytics in SPL.
- [Google Cloud Security Analytics](https://github.com/GoogleCloudPlatform/security-analytics) - This repository serves as a community-driven list of sample security analytics for auditing cloud usage and for detecting threats to your data & workloads in Google Cloud.
- [KQL Advanced Hunting Queries & Analytics Rules](https://github.com/Bert-JanP/Hunting-Queries-Detection-Rules) - A list of endpoint detections and hunting queries for Microsoft Defender for Endpoint, Defender For Identity, and Defender For Cloud Apps.
- [Sigma2KQL](https://github.com/Khadinxc/Sigma2KQL) - A repository of all SIGMA rules converted to KQL that runs on a weekly schedule to update the repository and align with the up to date version of the SIGMA rules repository.
- [TerraSigma](https://github.com/Khadinxc/TerraSigma) - A repository of all SIGMA rules converted to Microsoft Sentinel Terraform Scheduled analytic resources. The repository runs on a weekly schedule to update the repository and align with the up to date version of the SIGMA rules repository. Proper entity mapping is completed for the rules to ensure the repo is plug-and-play.
- [Detections Digest | Sergey Polzunov](https://detections-digest.rulecheck.io) - A newsletter that features updates from many popular detection content sources listed here. 

## Logging, Monitoring & Data Sources

- [Windows Logging Cheatsheets](https://www.malwarearchaeology.com/cheat-sheets) - Multiple cheatsheets outlined recommendations for Windows Event logging at various levels of granularity.
- [Linux auditd Detection Ruleset](https://github.com/Neo23x0/auditd/blob/master/audit.rules) - Linux auditd ruleset that produces telemetry required for threat detection use cases.
- [MITRE ATT&CK Data Sources Blog Post](https://medium.com/mitre-attack/defining-attack-data-sources-part-i-4c39e581454f) - MITRE describes various data sources and how they relate to the TTPs found in the MITRE ATT&CK framework.
- [MITRE ATT&CK Data Sources List](https://attack.mitre.org/datasources/) - Data source objects added to MITRE ATT&CK as part of v10.
- [Splunk Common Information Model (CIM)](https://docs.splunk.com/Documentation/CIM/5.0.0/User/Overview) - Splunk's proprietary model used as a framework for normalizing security data.
- [Elastic Common Schema](https://www.elastic.co/guide/en/ecs/current/ecs-getting-started.html) - Elastic's proprietary model used as a framework for normalizing security data.
- [Exabeam Common Information Model](https://github.com/ExabeamLabs/CIMLibrary) - Exabeam's proprietary model used as a framework for normalizing security data.
- [Open Cybersecurity Schema Framework (OCSF)](https://schema.ocsf.io/categories?extensions) - An opensource security data source and event schema.
- [Loghub](https://github.com/logpai/loghub) - Opensource and freely available security data sources for research and testing.
- [Elastalert | Yelp](https://github.com/Yelp/elastalert) - ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch.
- [Matano](https://github.com/matanolabs/matano) - Open source cloud-native security lake platform (SIEM alternative) for threat hunting, Python detections-as-code, and incident response on AWS 🦀.
- [Microsoft XDR Advanced Hunting Schema](https://learn.microsoft.com/en-us/defender-xdr/advanced-hunting-schema-tables) To help with multi-table queries, you can use the advanced hunting schema, which includes tables and columns with event information and details about devices, alerts, identities, and other entity types.

## General Resources
 
- [ATT&CK Navigator | MITRE](https://mitre-attack.github.io/attack-navigator/enterprise/) - MITRE's open-source tool that can be used to track detection coverage, visibility, and other efforts and their relationship to the ATT&CK framework.
- [Detection Engineering Weekly | Zack Allen](https://detectionengineering.net) - A newsletter dedicated to news and how-tos for Detection Engineering.
- [Detection Engineering Twitter List | Zack Allen](https://twitter.com/i/lists/1629936556298436608) - A Twitter list of Detection Engineering thought leaders.
- [DETT&CT: MAPPING YOUR BLUE TEAM TO MITRE ATT&CK™](https://www.mbsecure.nl/blog/2019/5/dettact-mapping-your-blue-team-to-mitre-attack) - Outlines a methodology measuring security data visibility and detection coverage against the MITRE ATT&CK framework.
- [Awesome Kubernetes (K8s) Threat Detection](https://github.com/jatrost/awesome-kubernetes-threat-detection) - Another Awesome List dedicated to Kubernetes (K8s) threat detection.
- [Detection and Response Pipeline](https://github.com/0x4D31/detection-and-response-pipeline) - A list of tools for each component of a detection and response pipeline which includes real-world examples.
- [Living Off the Living Off the Land](https://lolol.farm) - A collection of resources for thriving off the land.
- [Detection at Scale Podcast | Jack Naglieri](https://podcasts.apple.com/us/podcast/detection-at-scale/id1582584270) - A detection engineering-focused podcast featuring many thought leaders in the specialization.
- [Cloud Threat Landscape | Wiz](https://threats.wiz.io/all-techniques) - A cloud detection engineering-focused database, that lists threat actors known to have compromised cloud environments, the tools and techniques in their arsenal, and the technologies they prefer to target.
- [Splunk ES Correlation Searches Best Practices | OpsTune](https://github.com/inodee/threathunting-spl/blob/master/Splunk%20ES%20Correlation%20Searches%20Best%20Practices%20v1.3.pdf) - A highly detailed guide to producing high quality detection content in the Splunk Enterprise Security app.
- [How Google Does It: Making threat detection high-quality, scalable, and modern | Anton Chuvakin, Tim Nguyen](https://cloud.google.com/transform/how-google-does-it-modernizing-threat-detection) - The team at Google highlights 5 key principles for building a high quality, scalable and modern threat detection program.
- [SOCLabs](https://www.soc-labs.top/) - A lab for blue teamers and detection engineers, with real threat data and support for popular SIEM query languages, enabling hands-on learning and practice in detection rule writing and threat hunting.
