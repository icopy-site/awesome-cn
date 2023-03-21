<div class="github-widget" data-repo="mark-rushakoff/awesome-influxdb"></div>
## awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

与以下相关的很棒的项目、库、工具等的精选列表 [InfluxDB](https://www.influxdata.com/).
此列表侧重于支持 InfluxDB 1.0 及更高版本的库、工具等.

想让这个列表更好吗？
看看我们的页面 [contributing](https://github.com/mark-rushakoff/awesome-influxdb/blob/master/CONTRIBUTING.md) 然后打开一个请求请求！

## Reference material

如果您知道属于此列表的任何特别有用的博客文章、演讲、幻灯片等，请打开请求请求！

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)
* 物联网世界中的 InfluxDB. [Part 1: Introduction](https://www.easyitblog.info/2017/11/10/influxdb-and-grafana-fighting-together-with-iot-data-attack/) | [Part 2: Hosting and scaling on AWS](https://www.easyitblog.info/2017/11/14/influxdb-in-iot-world-aws-part-2/) | [Part 3: Plotting graphs using Grafana](https://www.easyitblog.info/2017/11/26/influxdb-in-iot-world-making-it-production-ready-part-3/)

## Client libraries

### Official

* [C#](https://github.com/influxdata/influxdb-csharp) - 一个 .NET 库，用于有效地将点发送到 InfluxDB
* [Go](https://github.com/influxdata/influxdb1-client) - InfluxDB 1.x 的 Go 客户端
* [Java](https://github.com/influxdata/influxdb-java) - InfluxDB 的 Java 客户端
* [PHP](https://github.com/influxdata/influxdb-php) - InfluxDB 的 PHP 客户端
* [Python](https://github.com/influxdata/influxdb-python) - InfluxDB 的 Python 客户端
* [Rails](https://github.com/influxdata/influxdb-rails) - Ruby on Rails 绑定自动将指标写入 InfluxDB
* [Ruby](https://github.com/influxdata/influxdb-ruby) - InfluxDB 的 Ruby 客户端

### Unofficial

* [capacitor](https://github.com/olauzon/capacitor) - InfluxDB 的 Clojure 客户端
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) - 时间序列数据库 InfluxDB 的 Common Lisp 接口
* [erflux](https://github.com/gossiperl/erflux) - Erlang 的 InfluxDB 客户端
* [fluxter](https://github.com/lexmag/fluxter) - Elixir 的 InfluxDB 编写器
* [influent](https://github.com/gobwas/influent) - InfluxDB Javascript 驱动程序
* [influent.rs](https://github.com/gobwas/influent.rs) - InfluxDB Rust 驱动程序
* [InfluxDB-Client-for-Arduino](https://github.com/tobiasschuerg/InfluxDB-Client-for-Arduino) - InfluxDB 的 Arduino 客户端
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) - InfluxDB 的 LabVIEW 客户端
* [influxdb-cpp-rest](https://github.com/d-led/influxdb-cpp-rest) - A C++ InfluxDB client with a batching async interface
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) - InfluxDB 的 Haskell 客户端库
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) - InfluxDB 的 .NET 客户端
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) - 用于读取和写入数据的 UDP/IP 或 HTTP 适配器
* [influxdbr](https://github.com/dleutnant/influxdbr) - InfluxDB 的 R 库
* [instream](https://github.com/mneudert/instream) - 用于 Elixir 的 InfluxDB 驱动程序
* [node-influx](https://github.com/node-influx/node-influx) - InfluxDB Node.js 客户端
* [node-influx-udp](https://github.com/mediocre/node-influx-udp) - 使用 UDP 接口写入 InfluxDB
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) - Scala 的异步 InfluxDB 客户端

## Collecting data into InfluxDB

### Projects

#### Dedicated

主要或唯一目的是将数据输入 InfluxDB 的工具.

* [accelerometer2influx](https://github.com/CorpGlory/accelerometer2influx) - 从手机加速度计获取 xyz 轴指标并将数据发送到 InfluxDB 的 Android 应用程序.
* [agento](https://github.com/abrander/agento) - 客户端/服务器从 Linux 主机收集近乎实时的指标
* [aggregateD](https://github.com/ccpgames/aggregateD) - A [dogstatsD](https://docs.datadoghq.com/guides/dogstatsd/) InfluxDB 的启发指标和事件聚合守护进程
* [aprs2influxdb](https://github.com/FaradayRF/aprs2influxdb) - 连接业余无线电 APRS-IS 服务器并将数据包数据保存到 influxdb 数据库中
* [Charmander](https://github.com/att-innovate/charmander) - Charmander 是用于测量和分析资源调度算法的实验室环境
* [gopherwx](https://github.com/chrissnell/gopherwx) - 一项从 Davis Instruments Vantage Pro2 站提取实时天气数据并将其存储在 InfluxDB 中的服务
* [grade](https://github.com/influxdata/grade) - 通过将结果存储在 InfluxDB 中来跟踪一段时间内的 Go 基准性能
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor)  - Influx-Capacitor 使用性能计数器从 Windows 机器收集指标. 数据被发送到 influxDB 以供 grafana 查看
* [Influxdb-Powershell](https://github.com/vsavornin/Influxdb-Powershell) - 将 Windows 性能计数器发送到 InfluxDB 服务器的 Powershell 脚本
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) - SmartApp 登录 [SmartThings](https://www.smartthings.com/) InfluxDB 数据库的设备属性
* [influxdb-sqlserver](https://github.com/zensqlmonitor/influxdb-sqlserver) - 收集 Microsoft SQL Server 指标以向 InfluxDB 报告并使用 Grafana 将其可视化
* [k6](https://github.com/loadimpact/k6) - 使用 Go 和 JavaScript 的现代负载测试工具
* [marathon-event-metrics](https://github.com/Wikia/marathon-event-metrics) - 报告工具 [Marathon](https://mesosphere.github.io/marathon/) 事件到 InfluxDB
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) - 轻 [mesos](https://mesos.apache.org/) InfluxDB 的统计数据收集器
* [mqforward](https://github.com/shirou/mqforward) - [MQTT](http://mqtt.org/) 到 influxdb 转发器
* [node-opcua-logger](https://github.com/coussej/node-opcua-logger) - 从 OPC UA 服务器收集工业数据
* [ntp_checker](https://github.com/fss1/ntp_checker) - 比较内部 NTP 源并在服务器之间的偏移量超过可定义的（几分之一）秒时发出警告
* [proc_to_influxdb](https://github.com/d-led/proc_to_influxdb) - 通过 InfluxDB 观察 Windows 进程启动和停止的控制台应用程序
* [pysysinfo_influxdb](https://github.com/nagylzs/pysysinfo_influxdb) - 定期将系统信息发送到influxdb（使用python3 + psutil，因此它也适用于Windows）
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) - 收集系统 (linux) 信息并将其发送到 InfluxDB
* [snmpcollector](https://github.com/toni-moreno/snmpcollector) - 一个功能齐全的通用 SNMP 数据收集器，带有用于 InfluxDB 的 Web 管理界面
* [Telegraf](https://github.com/influxdata/telegraf) -（官方）插件驱动的服务器代理，用于将指标报告到 InfluxDB 中
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) - 将数据从 Tesla Model S 流式传输到 InfluxDB（[rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16))
* [traffic_stats](https://traffic-control-cdn.readthedocs.io/en/latest/overview/traffic_stats.html) - 获取并存储有关 CDN 控制的统计信息 [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go](https://github.com/Oxalide/vsphere-influxdb-go) - 收集 VMware vSphere、vCenter 和 ESXi 性能指标并将它们发送到 InfluxDB

#### Non-dedicated

生成输入多个后端的数据的工具，包括 InfluxDB.

* [cAdvisor](https://github.com/google/cadvisor) - 分析运行容器的资源使用情况和性能特征
* [Centreon](https://github.com/centreon/centreon) - 一个网络、系统、应用的监督和监控工具
* [cernan](https://github.com/postmates/cernan) - 遥测和日志聚合服务器
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) - 将指标发送到 InfluxDB/Graphite [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) - 简单的 Go 代理从中获取流数据 [Turbine](https://github.com/Netflix/Turbine) 通过 SSE 并将其作为仪表推入 StatsD 或推入 InfluxDB
* [Domoticz](https://www.domoticz.com) - 开源家庭自动化系统
* [gatling](https://github.com/gatling/gatling) - 基于异步 Scala-Akka-Netty 的压力工具
* [Glances](https://github.com/nicolargo/glances) - 看一眼你的系统
* [Graphios](https://github.com/shawn-sterling/graphios) - 将 nagios 性能数据发送到 graphite (carbon) / statsd / librato / influxDB 的程序
* [heapster](https://github.com/kubernetes-retired/heapster) - 监控容器资源使用情况 [Kubernetes](https://kubernetes.io/) 簇
* [heka](https://github.com/mozilla-services/heka) - 通用数据收集和处理工具
* [internet_data_usage](https://github.com/precurse/internet_data_usage) - 基于 Python 的应用程序可提取不同运营商（如 Telus 和 Koodo）的数据计划使用情况
* [ioBroker](http://www.iobroker.net/) - 家庭自动化/物联网平台使用 Influxdb 存储 [history data](https://github.com/ioBroker/ioBroker.influxdb/blob/master/README.md)
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) - 实际上，在一端通过 JMX 与 JVM 对话与在另一端您可以想到的任何日志/监控/图形包之间缺少连接器.
* [Apache JMeter](https://jmeter.apache.org/usermanual/realtime-results.html) - 流行的负载测试工具，您可以获得通过 InfluxDBBackendListenerClient 发送到后端的实时结果，它允许您使用 UDP 或 HTTP 协议将指标（活动线程、响应时间......）发送到 InfluxDB 后端
* [logary](https://github.com/logary/logary) - 用于单声道和 .Net 的高性能、多目标日志记录、指标和健康检查库
* [metrics.sh](https://github.com/pstadler/metrics.sh) - 使用可移植的 shell 脚本收集和转发指标
* [OpenHAB](https://www.openhab.org/) - 适用于家庭自动化所有事物的通用集成平台
* [Riemann](https://github.com/riemann/riemann) - Clojure 中的网络事件流处理系统
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - 使用 StatsD 的简单 JVM 分析器
* [statsite](https://github.com/statsite/statsite) - statsd的C实现
* [Sematext Agent](https://github.com/sematext/sematext-agent-integrations) - [Open source monitoring agent](https://sematext.com/blog/now-open-source-sematext-monitoring-agent/) 通过可插入集成从 Solr、Elasticsearch、Cassandra、JVM、JMX、ClickHouse、MySQL、Hadoop 等收集指标. 通过 Influx Line 协议输出到 InfluxDB 或 [Sematext Cloud](https://sematext.com/cloud/)
* [logagent](https://github.com/sematext/logagent-js)  - 是一个现代的、开源的、轻量级的日志托运人.  Logagent 包括 [influxdb input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) 和 [influxdb output plugin](https://sematext.com/docs/logagent/output-plugin-influxdb/) 和 many other [integrations](https://sematext.com/docs/logagent/plugins/)

### Libraries

收集数据并输入 InfluxDB 的图书馆.

* [crow-metrics](https://github.com/robey/crow-metrics) - 节点服务器的小型指标收集器
* [django-influxdb-metrics](https://github.com/bitlabstudio/django-influxdb-metrics) - 一个可重用的 Django 应用程序，可将有关您的项目的指标发送到 InfluxDB
* [go-runtime-metrics](https://github.com/tevjef/go-runtime-metrics) - 收集 golang 运行时指标，输出到 InfluxDB 或通过 Telegraf
* [lua-resty-influx](https://github.com/p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) InfluxDB 客户端
* [metrics](https://github.com/beberlei/metrics)  - (PHP) 抽象不同指标收集器的简单库.  “我发现这有必要拥有一个不会导致供应商锁定的一致且简单的指标（功能性）API”
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) - 用于从中提取数据的库和支持脚本 [vSphere](https://www.vmware.com/products/vsphere.html) 并将其插入 InfluxDB
* [telemetry](https://github.com/arussellsaw/telemetry) - Go 应用程序的指标报告

#### Hooks

挂钩其他日志库输出到 InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - 一名记者 [go-metrics library](https://github.com/rcrowley/go-metrics) 这会将指标发布到 InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) - InfluxDB 挂钩 [Logrus](https://github.com/Sirupsen/logrus)

### Plugins

允许其他独立工具将其数据发送到 InfluxDB 的插件.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) - InfluxDB 输出插件 [Embulk](https://github.com/embulk/embulk)
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer](https://github.com/Feuerlabs/exometer) InfluxDB 的记者
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) - 缓冲输出插件 [fluentd](https://www.fluentd.org/) 和 InfluxDB
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) 用于从 InfluxDB 查询监控统计信息的插件
* [jenkinsci/influxdb-plugin](https://github.com/jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) 将构建指标发送到 InfluxDB 的插件
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - A [Kafka](https://kafka.apache.org/) 用 Python 编写的 InfluxDB 消费者
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) - 社区维护 [Logstash](https://www.elastic.co/products/logstash) 将指标输出到 InfluxDB 的插件
* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) - 一名记者 [dropwizard](https://www.dropwizard.io/0.9.1/docs/) 向 InfluxDB 服务器宣布测量结果的指标
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) 用于将数据导出到 InfluxDB 的模块
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensu.io/) InfluxDB 插件
* [sidekiq-influxdb](https://github.com/vassilevsky/sidekiq-influxdb) - A [Sidekiq](https://sidekiq.org/) 将作业执行指标发送到 InfluxDB 的中间件
* [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) - 出版 [snap](https://github.com/intelsdi-x/snap) InfluxDB 的指标
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) - StatsD 的一个简单的 InfluxDB 后端
* [logagent influx input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) - 通过 Influx 线路协议接收数据的 Logagent 插件
* [logagent InfluxDB output plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) - 通过 Influx Line 协议发送数据的插件


### Import tools

将一组固定数据导入 InfluxDB 的工具.
* [JMeter2InfluxDB](https://github.com/soprasteria/jmeter2influxdb) - 在 csv 文件中读取 JMeter 结果，并在负载测试后将结果放入 InfluxDB
* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) - 进口 [nmon](http://nmon.sourceforge.net/pmwiki.php) 文件到 InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://github.com/influxdata/chronograf) - InfluxDB 官方数据可视化工具
* [DBeaver](https://dbeaver.com/databases/influxdb/) - DBeaver Universal Database Tool，DBeaver Enterprise 对 InfluxDB 有特殊的扩展
* [facette](https://github.com/facette/facette) - 时间序列数据可视化和绘图软件
* [FluxDash](https://github.com/vrecan/FluxDash) - 基于终端的 InfluxDB 仪表板
* [grafana](https://github.com/grafana/grafana) - Graphite、InfluxDB 和 OpenTSDB 的华丽指标可视化、仪表板和编辑器
* [InfluxDB Studio](https://github.com/CymaticLabs/InfluxDBStudio) - InfluxDB Studio 是一个UI管理工具，它的灵感来源于其他类似的SQL数据库管理工具（使用在MS Windows上运行的InfluxData.Net）
* [InfluxGraph](https://github.com/InfluxGraph/influxgraph) - 用于 Graphite-API 的 Graphite InfluxDB 存储查找器
* [ostent](https://github.com/ostrost/ostent) - 收集和显示系统指标并可选择中继到 Graphite 和/或 InfluxDB

### Other tools

* [hubot-influxdb-alerts](https://github.com/amwelch/hubot-influxdb-alerts) - 在您的聊天室使用创建和管理警报 [hubot](https://hubot.github.com/) 和 influxdb
* [influx-alert](https://github.com/joshrendek/influx-alert) - 查询 InfluxDB 并基于 YAML 配置发送警报的工具
* [influxdb_google_sheets](https://github.com/HormyAJP/influxdb_google_sheets) - 用于获取和格式化 InfluxDB 数据的 Google 表格脚本
* [Morgoth](https://github.com/nathanielc/morgoth) - 指标异常检测

## Provisioning InfluxDB

无需手动安装即可帮助您运行 InfluxDB 的工具、库等.

* [chef-influxdb](https://github.com/bdangit/chef-influxdb) - InfluxDB 的厨师食谱
* [golja-influxdb](https://github.com/dgolja/golja-influxdb) - InfluxDB 的 Puppet 模块
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) - InfluxDB 的实验性 BOSH 版本
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) - Telegraf 的木偶模块
* [rossmcdonald/influxdb](https://github.com/rossmcdonald/influxdb) - 安装、配置和维护 InfluxDB 的 Ansible 角色
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) - 用于运行开箱即用的 InfluxDB 服务器的 Docker 映像

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) - InfluxDB 的原则 DBAL
* [Influxdb::Arel](https://github.com/undr/influxdb-arel)  - Influxdb::Arel 是 InfluxDB 方言的 SQL AST 管理器. 它简化了复杂 SQL 查询的生成
* [influxer](https://github.com/palkan/influxer) - InfluxDB ActiveRecord 风格
* [Time Series Admin](https://github.com/timeseriesadmin/timeseriesadmin) - InfluxDB 数据库的管理面板和查询界面

## Hosting of InfluxDB / SaaS

* [InfluxCloud](https://cloud.influxdata.com/plan-picker) - 来自 InfluxDB 的创建者
* [Aiven](https://aiven.io/influxdb) - 提供主机（AWS、Google、DigitalOcean 等）、地理位置和服务器规格的选择
* [Scalingo](https://scalingo.com/databases/influxdb) - 提供服务器规格的选择
* [HostedMetrics](https://hostedmetrics.com/product/influxdb/) - 通过托管 InfluxDB、Grafana 和 StatsD 的组合，面向自定义应用程序监控


## Miscellaneous

似乎不属于任何其他类别的项目.

* [influx-protector](https://github.com/ve-global/influx-protector) - 防止危险查询进入 influxdb 的代理
* [influxdb-schema-updater](https://github.com/open-ch/influxdb-schema-updater) - 一个小型 DevOps 工具，用于使用一组配置文件管理 InfluxDB 实例的架构
* [influx-prompt](https://github.com/RPing/influx-prompt) - 具有自动完成功能的交互式命令行 InfluxDB cli
* [cleanflux](https://github.com/Transatel/cleanflux) - 使用自动保留策略选择和在线错误更正围绕/查询端点进行代理

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata)
* [awesome-dashboard](https://github.com/obazoud/awesome-dashboard)
* [awesome-data-engineering](https://github.com/igorbarinov/awesome-data-engineering)
* [awesome-db](https://github.com/numetriclabz/awesome-db)
* [awesome-go](https://github.com/avelino/awesome-go)
* [awesome-home-assistant](https://github.com/frenck/awesome-home-assistant)
* [awesome-microservices](https://github.com/mfornos/awesome-microservices)
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin)

### Lists of awesome lists that include awesome-influxdb

* [awesome](https://github.com/sindresorhus/awesome)
* [lists](https://github.com/jnv/lists)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者和贡献者放弃了 awesome-influxdb 的所有版权和相关或邻接权.
