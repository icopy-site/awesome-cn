<div class="github-widget" data-repo="mark-rushakoff/awesome-influxdb"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

与以下内容相关的出色项目，库，工具等的精选列表 [InfluxDB](https://www.influxdata.com/).
此列表重点介绍支持InfluxDB 1.0版及更高版本的库，工具等.

想要使此列表更好？
看看我们的页面 [contributing](https://github.com/mark-rushakoff/awesome-influxdb/blob/master/CONTRIBUTING.md) 然后打开请求请求！

## Reference material

如果您知道此列表中包含任何特别有用的博客文章，讲座，幻灯片等，请打开请求请求！

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)
* IoT世界中的InfluxDB. [Part 1: Introduction](https://www.easyitblog.info/2017/11/10/influxdb-and-grafana-fighting-together-with-iot-data-attack/) | [Part 2: Hosting and scaling on AWS](https://www.easyitblog.info/2017/11/14/influxdb-in-iot-world-aws-part-2/) | [Part 3: Plotting graphs using Grafana](https://www.easyitblog.info/2017/11/26/influxdb-in-iot-world-making-it-production-ready-part-3/)

## Client libraries

### Official

* [C#](https://github.com/influxdata/influxdb-csharp) -一个.NET库，用于将点有效发送到InfluxDB
* [Go](https://github.com/influxdata/influxdb1-client) -Go InfluxDB 1.x客户端
* [Java](https://github.com/influxdata/influxdb-java) -InfluxDB的Java客户端
* [PHP](https://github.com/influxdata/influxdb-php) -InfluxDB的PHP客户端
* [Python](https://github.com/influxdata/influxdb-python) -InfluxDB的Python客户端
* [Rails](https://github.com/influxdata/influxdb-rails) -Ruby on Rails绑定以自动将指标写入InfluxDB
* [Ruby](https://github.com/influxdata/influxdb-ruby) -用于InfluxDB的Ruby客户端

### Unofficial

* [capacitor](https://github.com/olauzon/capacitor) -InfluxDB的Clojure客户
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) -时间序列数据库InfluxDB的通用Lisp接口
* [erflux](https://github.com/gossiperl/erflux) -用于Erlang的InfluxDB客户端
* [fluxter](https://github.com/lexmag/fluxter) -Elixir的InfluxDB编写器
* [influent](https://github.com/gobwas/influent) -InfluxDB Javascript驱动程序
* [influent.rs](https://github.com/gobwas/influent.rs) -InfluxDB Rust驱动程序
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) -用于InfluxDB的LabVIEW客户端
* [influxdb-cpp-rest](https://github.com/d-led/influxdb-cpp-rest) -具有批处理异步接口的C ++ InfluxDB客户端
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) -用于InfluxDB的Haskell客户端库
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) -用于InfluxDB的.NET客户端
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) -用于读取和写入数据的UDP / IP或HTTP适配器
* [influxdbr](https://github.com/dleutnant/influxdbr) -用于InfluxDB的R库
* [instream](https://github.com/mneudert/instream) -Elixir的InfluxDB驱动程序
* [node-influx](https://github.com/node-influx/node-influx) -InfluxDB Node.js客户端
* [node-influx-udp](https://github.com/mediocre/node-influx-udp) -使用其UDP接口写入InfluxDB
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) -Scala的异步InfluxDB客户端

## Collecting data into InfluxDB

### Projects

#### Dedicated

主要或唯一目的是将数据馈入InfluxDB的工具.

* [accelerometer2influx](https://github.com/CorpGlory/accelerometer2influx) -Android应用程序，它从手机加速度计获取xyz轴指标并将数据发送到InfluxDB.
* [agento](https://github.com/abrander/agento) -客户端/服务器从Linux主机收集接近实时的指标
* [aggregateD](https://github.com/ccpgames/aggregateD) - 一种 [dogstatsD](https://docs.datadoghq.com/guides/dogstatsd/) InfluxDB的启发指标和事件聚合守护程序
* [aprs2influxdb](https://github.com/FaradayRF/aprs2influxdb) -与无线APRS-IS服务器进行接口并将数据包数据保存到influxdb数据库中
* [Charmander](https://github.com/att-innovate/charmander) -Charmander是用于测量和分析资源调度算法的实验室环境
* [gopherwx](https://github.com/chrissnell/gopherwx) -一项服务，可从Davis Instruments Vantage Pro2站提取实时天气数据并将其存储在InfluxDB中
* [grade](https://github.com/influxdata/grade) -通过将结果存储在InfluxDB中来随时间跟踪Go基准性能
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor)  -Influx-Capacitor使用性能计数器从Windows机器收集指标.  数据发送到influxDB以供grafana查看
* [Influxdb-Powershell](https://github.com/vsavornin/Influxdb-Powershell) -Powershell脚本将Windows性能计数器发送到InfluxDB服务器
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) -SmartApp记录 [SmartThings](https://www.smartthings.com/) 设备属性到InfluxDB数据库
* [influxdb-sqlserver](https://github.com/zensqlmonitor/influxdb-sqlserver) -收集Microsoft SQL Server指标以向InfluxDB报告并使用Grafana可视化
* [k6](https://github.com/loadimpact/k6) -使用Go和JavaScript的现代负载测试工具
* [marathon-event-metrics](https://github.com/Wikia/marathon-event-metrics) -报告工具 [Marathon](https://mesosphere.github.io/marathon/) InfluxDB事件
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) 轻巧 [mesos](https://mesos.apache.org/) InfluxDB的统计信息收集器
* [mqforward](https://github.com/shirou/mqforward) - [MQTT](http://mqtt.org/) 到influxdb转发器
* [node-opcua-logger](https://github.com/coussej/node-opcua-logger) -从OPC UA服务器收集工业数据 
* [ntp_checker](https://github.com/fss1/ntp_checker) -比较内部NTP源并警告服务器之间的偏移量是否超过可定义的（分数）秒
* [proc_to_influxdb](https://github.com/d-led/proc_to_influxdb) -通过InfluxDB观察Windows进程启动和停止的控制台应用程序
* [pysysinfo_influxdb](https://github.com/nagylzs/pysysinfo_influxdb) -定期将系统信息发送到influxdb（使用python3 + psutil，因此在Windows下也可以使用）
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) -收集系统（linux）信息并将其发送到InfluxDB
* [snmpcollector](https://github.com/toni-moreno/snmpcollector) -具有用于InfluxDB的Web管理界面的功能齐全的通用SNMP数据收集器
* [Telegraf](https://github.com/influxdata/telegraf) -（官方）插件驱动的服务器代理，用于向InfluxDB报告指标
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) -将数据从Tesla Model S传输到InfluxDB（[rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16))
* [traffic_stats](https://traffic-control-cdn.readthedocs.io/en/latest/overview/traffic_stats.html) -获取并存储由CDN控制的CDN的统计信息 [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go](https://github.com/Oxalide/vsphere-influxdb-go) -收集VMware vSphere，vCenter和ESXi性能指标并将其发送到InfluxDB

#### Non-dedicated

包含生成数据的工具，这些数据可馈入多个后端（包括InfluxDB）.

* [cAdvisor](https://github.com/google/cadvisor) -分析正在运行的容器的资源使用情况和性能特征
* [Centreon](https://github.com/centreon/centreon) -网络，系统，应用监督和监视工具
* [cernan](https://github.com/postmates/cernan) -遥测和日志记录聚合服务器
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) -将指标从发送到InfluxDB / Graphite [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) -简单的Go代理从中提取流数据 [Turbine](https://github.com/Netflix/Turbine) 通过SSE并将其作为量规推入StatsD或InfluxDB
* [Domoticz](https://www.domoticz.com) -开源家庭自动化系统
* [gatling](https://github.com/gatling/gatling) -基于异步Scala-Akka-Netty的压力工具
* [Glances](https://github.com/nicolargo/glances) -一览您的系统
* [Graphios](https://github.com/shawn-sterling/graphios) -将nagios性能数据发送到石墨（碳）/ statsd / librato / influxDB的程序
* [heapster](https://github.com/kubernetes-retired/heapster) -监视容器资源的使用情况 [Kubernetes](https://kubernetes.io/) 簇
* [heka](https://github.com/mozilla-services/heka) -通用数据收集和处理工具
* [internet_data_usage](https://github.com/precurse/internet_data_usage) -基于Python的应用程序，可为Telus和Koodo等不同运营商提取数据计划的使用情况
* [ioBroker](http://www.iobroker.net/) -家庭自动化/ IoT平台使用Influxdb进行存储 [history data](https://github.com/ioBroker/ioBroker.influxdb/blob/master/README.md)
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) -实际上，缺少了通过一端通过JMX与JVM对话以及可以在另一端实现的任何日志记录/监视/图形包之间的连接器.
* [Apache JMeter](https://jmeter.apache.org/usermanual/realtime-results.html) -流行的负载测试工具，您可以通过InfluxDBBackendListenerClient将实时结果发送到后端，该客户端可以使用UDP或HTTP协议将指标（活动线程，响应时间...）发送到InfluxDB后端
* [logary](https://github.com/logary/logary) -用于mono和.net的高性能，多目标日志记录，指标和运行状况检查库
* [metrics.sh](https://github.com/pstadler/metrics.sh) -使用可移植的shell脚本收集和转发指标
* [OpenHAB](https://www.openhab.org/) -适用于家庭自动化所有事物的通用集成平台
* [Riemann](https://github.com/riemann/riemann) -Clojure中的网络事件流处理系统
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) -使用StatsD的简单JVM配置文件
* [statsite](https://github.com/statsite/statsite) -C实现statsd
* [Sematext Agent](https://github.com/sematext/sematext-agent-integrations) - [Open source monitoring agent](https://sematext.com/blog/now-open-source-sematext-monitoring-agent/)  通过可插拔集成从Solr，Elasticsearch，Cassandra，JVM，JMX，ClickHouse，MySQL，Hadoop等收集指标.  通过Influx Line Protocol输出到InfluxDB或 [Sematext Cloud](https://sematext.com/cloud/)
* [logagent](https://github.com/sematext/logagent-js)  -是一个现代的，开源的，轻量级的原木托运人.  Logagent包括 [influxdb input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) 和 [influxdb output plugin](https://sematext.com/docs/logagent/output-plugin-influxdb/) 和 many other [integrations](https://sematext.com/docs/logagent/plugins/) 

### Libraries

收集数据并将其输入InfluxDB的库.

* [crow-metrics](https://github.com/robey/crow-metrics) -节点服务器的小型指标收集器
* [django-influxdb-metrics](https://github.com/bitlabstudio/django-influxdb-metrics) -可重用的Django应用，可将有关您的项目的指标发送到InfluxDB
* [go-runtime-metrics](https://github.com/tevjef/go-runtime-metrics) -收集golang运行时指标，输出到InfluxDB或通过Telegraf
* [lua-resty-influx](https://github.com/p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) InfluxDB的客户端
* [metrics](https://github.com/beberlei/metrics)  -（PHP）抽象不同指标收集器的简单库.  “我认为有必要拥有一个一致且简单的指标（功能）API，而不会导致供应商锁定”
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) -用于从中提取数据的库和支持脚本 [vSphere](https://www.vmware.com/products/vsphere.html) 并将其插入InfluxDB
* [telemetry](https://github.com/arussellsaw/telemetry) -Go应用程序的指标报告

#### Hooks

钩子将其他日志记录库输出到InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) -一位记者 [go-metrics library](https://github.com/rcrowley/go-metrics) 它将度量标准发布到InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) -InfluxDB挂钩 [Logrus](https://github.com/Sirupsen/logrus)

### Plugins

允许其他独立工具将其数据发送到InfluxDB的插件.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) -InfluxDB输出插件 [Embulk](https://github.com/embulk/embulk)
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer](https://github.com/Feuerlabs/exometer) InfluxDB的记者
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) -的缓冲输出插件 [fluentd](https://www.fluentd.org/) 和InfluxDB
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) 用于从InfluxDB查询监视统计信息的插件
* [jenkinsci/influxdb-plugin](https://github.com/jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) 用于将构建指标发送到InfluxDB的插件
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - 一种 [Kafka](https://kafka.apache.org/) 用Python编写的InfluxDB的使用者
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) -社区维护 [Logstash](https://www.elastic.co/products/logstash) 插件将指标输出到InfluxDB
* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) -一位记者 [dropwizard](https://www.dropwizard.io/0.9.1/docs/) 向InfluxDB服务器发布度量的度量
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) 用于将数据导出到InfluxDB的模块
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensu.io/) InfluxDB插件
* [sidekiq-influxdb](https://github.com/vassilevsky/sidekiq-influxdb) - 一种 [Sidekiq](https://sidekiq.org/) 将作业执行指标发送到InfluxDB的中间件
* [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) -出版 [snap](https://github.com/intelsdi-x/snap) InfluxDB的指标
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) -用于StatsD的天真InfluxDB后端
* [logagent influx input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) -Logagent插件通过Influx线路协议接收数据  
* [logagent InfluxDB output plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) -插件通过Influx线路协议发送数据  


### Import tools

用于将一组固定的数据导入InfluxDB的工具.
* [JMeter2InfluxDB](https://github.com/soprasteria/jmeter2influxdb) -在负载测试后，将JMeter的结果读取到一个csv文件中，并将结果放入InfluxDB中
* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) -进口 [nmon](http://nmon.sourceforge.net/pmwiki.php) 文件到InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://github.com/influxdata/chronograf) -官方的InfluxDB数据可视化工具
* [DBeaver](https://dbeaver.com/databases/influxdb/) -DBeaver通用数据库工具，DBeaver Enterprise具有InfluxDB的特殊扩展
* [facette](https://github.com/facette/facette) - Time series data visualization and graphing software
* [FluxDash](https://github.com/vrecan/FluxDash) -基于终端的InfluxDB仪表板
* [grafana](https://github.com/grafana/grafana) -Graphite，InfluxDB和OpenTSDB的华丽指标度量，仪表板和编辑器
* [InfluxDB Studio](https://github.com/CymaticLabs/InfluxDBStudio) -InfluxDB Studio是一个UI管理工具，其灵感来自其他类似的SQL数据库管理工具（使用在MS Windows上运行的InfluxData.Net）
* [InfluxGraph](https://github.com/InfluxGraph/influxgraph) -用于Graphite-API的Graphite InfluxDB存储查找器
* [ostent](https://github.com/ostrost/ostent) -收集并显示系统指标，并可选地中继到Graphite和/或InfluxDB

### Other tools

* [hubot-influxdb-alerts](https://github.com/amwelch/hubot-influxdb-alerts) -使用以下内容在您的聊天室中创建和管理警报 [hubot](https://hubot.github.com/) 和influxdb
* [influx-alert](https://github.com/joshrendek/influx-alert) -用于查询InfluxDB并基于YAML配置发送警报的工具
* [influxdb_google_sheets](https://github.com/HormyAJP/influxdb_google_sheets) -Google表格脚本，用于获取和格式化InfluxDB数据
* [Morgoth](https://github.com/nathanielc/morgoth) -公制异常检测

## Provisioning InfluxDB

工具，库等可帮助您无需手动安装即可运行InfluxDB.

* [chef-influxdb](https://github.com/bdangit/chef-influxdb) -InfluxDB的厨师食谱
* [golja-influxdb](https://github.com/dgolja/golja-influxdb) -用于InfluxDB的Puppet模块
* [influxdb-formula](https://github.com/saltstack-formulas/influxdb-formula) -安装和配置InfluxDB时间序列数据库
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) -InfluxDB的实验性BOSH版本
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) -Telegraf的人偶模块
* [rossmcdonald/influxdb](https://github.com/rossmcdonald/influxdb) -用于安装，配置和维护InfluxDB的角色
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) -Docker映像以运行现成的InfluxDB服务器

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) -适用于InfluxDB的教义DBAL
* [Influxdb::Arel](https://github.com/undr/influxdb-arel)  -Influxdb :: Arel是用于InfluxDB方言的SQL AST管理器.  它简化了复杂SQL查询的生成
* [influxer](https://github.com/palkan/influxer) -InfluxDB ActiveRecord样式

## Hosting of InfluxDB / SaaS

* [InfluxCloud](https://cloud.influxdata.com/plan-picker) -来自InfluxDB的创建者
* [Aiven](https://aiven.io/influxdb) -提供主机（AWS，Google，DigitalOcean等），地理位置和服务器规格的选择
* [Scalingo](https://scalingo.com/databases/influxdb) -提供服务器规格选择
* [HostedMetrics](https://hostedmetrics.com/product/influxdb/) -通过托管InfluxDB，Grafana和StatsD的组合来实现自定义应用程序监视


## Miscellaneous

似乎不适合其他类别的项目.

* [influx-protector](https://github.com/ve-global/influx-protector) -代理以防止危险查询进入influxdb
* [influxdb-schema-updater](https://github.com/open-ch/influxdb-schema-updater) -一个小的DevOps工具，用于使用一组配置文件来管理InfluxDB实例的架构
* [influx-prompt](https://github.com/RPing/influx-prompt) -具有自动完成功能的交互式命令行InfluxDB CLI

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

在法律允许的范围内，作者和贡献者放弃了awesome-influxdb的所有版权以及相关或邻近的权利.
