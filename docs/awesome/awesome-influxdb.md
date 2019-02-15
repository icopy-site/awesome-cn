## awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

与之相关的精彩项目，库，工具等的精选列表 [InfluxDB](https://www.influxdata.com/).
此列表侧重于支持InfluxDB 1.0及更高版本的库，工具等.

想让这份清单更好吗？
看看我们的页面 [contributing](https://github.com/mark-rushakoff/awesome-influxdb/blob/master/CONTRIBUTING.md) 然后打开一个拉请求！

## Reference material

如果您知道属于此列表的任何特别有用的博客文章，演讲，幻灯片等，请打开拉取请求！

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)
*物联网世界中的InfluxDB. [Part 1: Introduction](https://www.easyitblog.info/2017/11/10/influxdb-and-grafana-fighting-together-with-iot-data-attack/) | [Part 2: Hosting and scaling on AWS](https://www.easyitblog.info/2017/11/14/influxdb-in-iot-world-aws-part-2/) | [Part 3: Plotting graphs using Grafana](https://www.easyitblog.info/2017/11/26/influxdb-in-iot-world-making-it-production-ready-part-3/)

## Client libraries

### Official

* [C#](https://github.com/influxdata/influxdb-csharp) - 用于高效地向InfluxDB发送点的.NET库
* [Go](https://github.com/influxdata/influxdb/tree/master/client) - 成为InfluxDB的客户端，包含在主要的InfluxDB仓库中
* [Java](https://github.com/influxdata/influxdb-java) - Java client for InfluxDB
* [PHP](https://github.com/influxdata/influxdb-php) -  InfluxDB的PHP客户端
* [Python](https://github.com/influxdata/influxdb-python) -  InfluxDB的Python客户端
* [Rails](https://github.com/influxdata/influxdb-rails) -  Ruby on Rails绑定自动将指标写入InfluxDB
* [Ruby](https://github.com/influxdata/influxdb-ruby) -  InfluxDB的Ruby客户端

### Unofficial

* [capacitor](https://github.com/olauzon/capacitor) -  InfluxDB的Clojure客户端
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) - 时间序列数据库InfluxDB的通用Lisp接口
* [erflux](https://github.com/gossiperl/erflux) - 针对Erlang的InfluxDB客户端
* [fluxter](https://github.com/lexmag/fluxter) - 一个针对Elixir的InfluxDB作家
* [influent](https://github.com/gobwas/influent) -  InfluxDB Javascript驱动程序
* [influent.rs](https://github.com/gobwas/influent.rs) -  InfluxDB Rust驱动程序
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) -  InfluxDB的LabVIEW客户端
* [influxdb-cpp-rest](https://github.com/d-led/influxdb-cpp-rest) - 具有批处理异步接口的C ++ InfluxDB客户端
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) -  InfluxDB的Haskell客户端库
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) -  InfluxDB的.NET客户端
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) - 用于读取和写入数据的UDP / IP或HTTP适配器
* [influxdbr](https://github.com/dleutnant/influxdbr) -  InfluxDB的R库
* [instream](https://github.com/mneudert/instream) -  Elixir的InfluxDB驱动程序
* [node-influx](https://github.com/node-influx/node-influx) -  InfluxDB Node.js客户端
* [node-influx-udp](https://github.com/mediocre/node-influx-udp) - 使用UDP接口写入InfluxDB
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) -  Scala的异步InfluxDB客户端

## Collecting data into InfluxDB

### Projects

#### Dedicated

主要或唯一目的是将数据提供给InfluxDB的工具.

* [accelerometer2influx](https://github.com/CorpGlory/accelerometer2influx) -  Android应用程序，从您的手机加速计获取xyz轴指标，并将数据发送到InfluxDB.
* [agento](https://github.com/abrander/agento) - 客户端/服务器从Linux主机收集近实时指标
* [aggregateD](https://github.com/ccpgames/aggregateD) - 一个 [dogstatsD](https://docs.datadoghq.com/guides/dogstatsd/) InfluxDB的灵感度量和事件聚合守护进程
* [aprs2influxdb](https://github.com/FaradayRF/aprs2influxdb) - 接口火腿无线电APRS-IS服务器并将数据包数据保存到Influxdb数据库中
* [Charmander](https://github.com/att-innovate/charmander) -  Charmander是用于测量和分析资源调度算法的实验室环境
* [gopherwx](https://github.com/chrissnell/gopherwx) - 从Davis Instruments Vantage Pro2工作站获取实时天气数据并将其存储在InfluxDB中的服务
* [grade](https://github.com/influxdata/grade) - 通过将结果存储在InfluxDB中，跟踪Go基准性能
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor)   -  Influx-Capacitor使用性能计数器从Windows机器收集指标.  数据被发送到InfluxDB以供grafana查看
* [Influxdb-Powershell](https://github.com/vsavornin/Influxdb-Powershell) - 用于将Windows性能计数器发送到InfluxDB服务器的Powershell脚本
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) -  SmartApp记录 [SmartThings](https://www.smartthings.com/) 设备属性到InfluxDB数据库
* [influxdb-sqlserver](https://github.com/zensqlmonitor/influxdb-sqlserver) - 收集Microsoft SQL Server指标以报告给InfluxDB并使用Grafana可视化它们
* [k6](https://github.com/loadimpact/k6) - 使用Go和JavaScript的现代负载测试工具
* [marathon-event-metrics](https://github.com/Wikia/marathon-event-metrics) - 报告工具 [Marathon](https://mesosphere.github.io/marathon/) 关于InfluxDB的事件
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) - 轻量级 [mesos](https://mesos.apache.org/) InfluxDB的统计信息收集器
* [mqforward](https://github.com/shirou/mqforward) - [MQTT](http://mqtt.org/) to Influxdb货运代理
* [node-opcua-logger](https://github.com/coussej/node-opcua-logger) - 从OPC UA服务器收集工业数据 
* [ntp_checker](https://github.com/fss1/ntp_checker) - 比较内部NTP源并警告服务器之间的偏移是否超过可定义（分数）秒
* [proc_to_influxdb](https://github.com/d-led/proc_to_influxdb) - 通过InfluxDB观察Windows进程启动和停止的控制台应用程序
* [pysysinfo_influxdb](https://github.com/nagylzs/pysysinfo_influxdb) - 定期将系统信息发送到Influxdb（使用python3 + psutil，因此它也适用于Windows）
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) - 收集并发送系统（linux）信息到InfluxDB
* [snmpcollector](https://github.com/toni-moreno/snmpcollector) - 具有用于InfluxDB的Web管理界面的全功能通用SNMP数据收集器
* [Telegraf](https://github.com/influxdata/telegraf) - （官方）插件驱动的服务器代理，用于向InfluxDB报告指标
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) - 从特斯拉Model S到InfluxDB的数据流（[rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16))
* [traffic_stats](http://traffic-control-cdn.readthedocs.io/en/latest/overview/traffic_stats.html) - 获取并存储有关受控制的CDN的统计信息 [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go](https://github.com/Oxalide/vsphere-influxdb-go) - 收集VMware vSphere，vCenter和ESXi性能指标并将其发送到InfluxDB

#### Non-dedicated

生成包含InfluxDB的多个后端数据的工具.

* [cAdvisor](https://github.com/google/cadvisor) - 分析正在运行的容器的资源使用情况和性能特征
* [Centreon](https://github.com/centreon/centreon) - 网络，系统，应用监督和监测工具
* [cernan](https://github.com/postmates/cernan) - 遥测和记录聚合服务器
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) - 将指标发送到InfluxDB / Graphite [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) - 简单Go代理从中提取流数据 [Turbine](https://github.com/Netflix/Turbine) 通过SSE将其作为衡量标准推送到StatsD或推送到InfluxDB
* [Domoticz](https://www.domoticz.com) - 开源家庭自动化系统
* [gatling](https://github.com/gatling/gatling) - 基于异步Scala-Akka-Netty的Stress Tool
* [Glances](https://github.com/nicolargo/glances) - 浏览您的系统
* [Graphios](https://github.com/shawn-sterling/graphios) - 将nagios perf数据发送到graphite（carbon）/ statsd / librato / InfluxDB的程序
* [heapster](https://github.com/kubernetes/heapster) - 监控a的容器资源使用情况 [Kubernetes](https://kubernetes.io/) 簇
* [heka](https://github.com/mozilla-services/heka) - 通用数据收集和处理工具
* [internet_data_usage](https://github.com/precurse/internet_data_usage) - 基于Python的应用程序，用于为Telus和Koodo等不同运营商提取数据计划
* [ioBroker](http://www.iobroker.net/) -  Homeautomation / IoT Platform使用Influxdb存储 [history data](https://github.com/ioBroker/ioBroker.influxdb/blob/master/README.md)
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) - 有效地在一端通过JMX与JVM通信以及在另一端可以想到的任何日志/监视/图形包之间缺少连接器.
* [Apache JMeter](https://jmeter.apache.org/usermanual/realtime-results.html) - 流行的负载测试工具，您可以通过InfluxDBBackendListenerClient获取发送到后端的实时结果，允许您使用UDP或HTTP协议向InfluxDB后端发送指标（活动线程，响应时间......）
* [logary](https://github.com/logary/logary) - 用于单声道和.Net的高性能，多目标日志记录，度量标准和健康检查库
* [metrics.sh](https://github.com/pstadler/metrics.sh) - 使用便携式shell脚本收集和转发指标
* [OpenHAB](https://www.openhab.org/) - 适用于家庭自动化所有事物的通用集成平台
* [Riemann](https://github.com/riemann/riemann) -  Clojure中的网络事件流处理系统
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - 使用StatsD的简单JVM配置文件
* [statsite](https://github.com/statsite/statsite) -  statsd的C实现

### Libraries

用于收集数据并提供给InfluxDB的库.

* [crow-metrics](https://github.com/robey/crow-metrics) - 节点服务器的小指标收集器
* [django-influxdb-metrics](https://github.com/bitlabstudio/django-influxdb-metrics) - 可重复使用的Django应用程序，可将有关您项目的指标发送到InfluxDB
* [go-runtime-metrics](https://github.com/tevjef/go-runtime-metrics) - 收集golang运行时度量标准，输出到InfluxDB或通过Telegraf
* [lua-resty-influx](https://github.com/p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) 关于InfluxDB的客户端
* [metrics](https://github.com/beberlei/metrics)   - （PHP）抽象不同指标收集器的简单库.  “我认为这必须具有一致且简单的指标（功能）API，不会导致供应商锁定”
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) - 用于从中提取数据的库和支持脚本 [vSphere](https://www.vmware.com/products/vsphere.html) 并将其插入InfluxDB
* [telemetry](https://github.com/arussellsaw/telemetry) -  Go应用程序的度量报告

#### Hooks

其他日志库的挂钩输出到InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - 一名记者 [go-metrics library](https://github.com/rcrowley/go-metrics) 这会将指标发布到InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) -  InfluxDB Hook for [Logrus](https://github.com/Sirupsen/logrus)

### Plugins

插件允许其他独立工具将其数据发送到InfluxDB.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) -  InfluxDB输出插件 [Embulk](https://github.com/embulk/embulk)
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer](https://github.com/Feuerlabs/exometer) 关于InfluxDB的记者
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) - 缓冲输出插件 [fluentd](https://www.fluentd.org/) 和InfluxDB
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) 用于从InfluxDB查询监控统计信息的插件
* [jenkinsci/influxdb-plugin](https://github.com/jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) 插件将构建指标发送到InfluxDB
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - 一个 [Kafka](https://kafka.apache.org/) 用Python编写的InfluxDB的使用者
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) - 社区维护 [Logstash](https://www.elastic.co/products/logstash) 插件将指标输出到InfluxDB
* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) - 记者 [dropwizard](https://www.dropwizard.io/0.9.1/docs/) 向InfluxDB服务器发布测量结果的度量标准
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) 用于将数据导出到InfluxDB的模块
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensu.io/) InfluxDB插件
* [sidekiq-influxdb](https://github.com/vassilevsky/sidekiq-influxdb) - 一个 [Sidekiq](https://sidekiq.org/) 中间件将作业执行指标发送到InfluxDB
* [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) - 发布 [snap](http://www.snap-telemetry.io/) 关注InfluxDB的指标
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) -  StatsD的一个天真的InfluxDB后端

### Import tools

将一组固定数据导入InfluxDB的工具.

* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) - 进口 [nmon](http://nmon.sourceforge.net/pmwiki.php) 文件到InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://github.com/influxdata/chronograf) - 官方InfluxDB数据可视化工具
* [facette](https://github.com/facette/facette) - 时间序列数据可视化和图形软件
* [FluxDash](https://github.com/vrecan/FluxDash) - 基于终端的InfluxDB仪表板
* [grafana](https://github.com/grafana/grafana) -  Graphite，InfluxDB和OpenTSDB的华丽度量标准，仪表板和编辑器
* [InfluxGraph](https://github.com/InfluxGraph/influxgraph) - 用于Graphite-API的Graphite InfluxDB存储查找器
* [ostent](https://github.com/ostrost/ostent) - 收集并显示系统指标，并可选择中继到Graphite和/或InfluxDB
* [InfluxDB Studio](https://github.com/CymaticLabs/InfluxDBStudio) -  InfluxDB Studio是一个UI管理工具，它的灵感来自其他类似的SQL数据库管理工具（使用在MS Windows上运行的InfluxData.Net）

### Other tools

* [hubot-influxdb-alerts](https://github.com/amwelch/hubot-influxdb-alerts) - 使用在聊天室中创建和管理警报 [hubot](https://hubot.github.com/) 和流入
* [influx-alert](https://github.com/joshrendek/influx-alert) - 用于查询InfluxDB并基于YAML配置发送警报的工具
* [influxdb_google_sheets](https://github.com/HormyAJP/influxdb_google_sheets) - 用于获取和格式化InfluxDB数据的Google表格脚本
* [Morgoth](https://github.com/nathanielc/morgoth) - 度量异常检测

## Provisioning InfluxDB

工具，库等可以帮助您在不安装手动的情况下运行InfluxDB.

* [chef-influxdb](https://github.com/bdangit/chef-influxdb) -  InfluxDB的厨师食谱
* [golja-influxdb](https://github.com/dgolja/golja-influxdb) -  InfluxDB的Puppet模块
* [influxdb-formula](https://github.com/saltstack-formulas/influxdb-formula) - 安装和配置InfluxDB时间序列数据库
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) -  InfluxDB的实验性BOSH版本
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) -  Telegraf的Puppet模块
* [rossmcdonald/influxdb](https://github.com/rossmcdonald/influxdb) - 安装，配置和维护InfluxDB的安全角色
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) -  Docker镜像以运行开箱即用的InfluxDB服务器

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) -  InfluxDB的DBAL教义
* [Influxdb::Arel](https://github.com/undr/influxdb-arel)   -  Influxdb :: Arel是InfluxDB方言的SQL AST管理器.  它简化了复杂SQL查询的生成
* [influxer](https://github.com/palkan/influxer) -  InfluxDB ActiveRecord风格

## Hosting of InfluxDB / SaaS

* [InfluxCloud](https://cloud.influxdata.com/plan-picker) - 来自InfluxDB的创建者
* [Aiven](https://aiven.io/influxdb) - 提供主机（AWS，Google，DigitalOcean等），地理位置和服务器规格的选择
* [Scalingo](https://scalingo.com/databases/influxdb) - 提供服务器规格选择
* [HostedMetrics](https://hostedmetrics.com/product/influxdb/) - 通过托管InfluxDB，Grafana和StatsD的组合，面向自定义应用程序监控


## Miscellaneous

似乎不适合任何其他类别的项目.

* [influx-protector](https://github.com/ve-global/influx-protector) - 代理，以防止危险的查询进入Influxdb
* [influxdb-schema-updater](https://github.com/open-ch/influxdb-schema-updater) - 一个小型DevOps工具，用于使用一组配置文件管理InfluxDB实例的模式
* [influx-prompt](https://github.com/RPing/influx-prompt) - 具有自动完成功能的交互式命令行InfluxDB cli

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

在法律允许的范围内，作者和贡献者已经放弃了所有版权以及相关或相邻权利.
