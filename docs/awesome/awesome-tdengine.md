<div class="github-widget" data-repo="taosdata/awesome-tdengine"></div>
<p align="center">
  <br>
  <a href="https://tdengine.com"><img width="240" src="https://raw.githubusercontent.com/taosdata/awesome-tdengine/master/./assets/logo.svg?sanitize=true" alt="logo of awesome-tdengine repository"></a>
  <br>
  <br>
</p>

## Awesome TDengine [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 TDengine 相关的精选清单.

时间序列数据的开源、高性能简化解决方案

 TDengine 是一种开源的云原生时间序列数据库 (TSDB)，针对物联网 (IoT)、联网汽车和工业物联网进行了优化. 它能够高效、实时地摄取、处理和监控每天由数十亿个传感器和数据收集器生成的 PB 级数据.  TDengine 内置缓存、流处理和数据订阅功能，为时序数据处理提供了一个简化的解决方案.

GitHub 仓库：https://github.com/taosdata/TDengine

官网： [tdengine.com](https://tdengine.com)



## GUI

- [TDengineGUI](https://github.com/skye0207/TDengineGUI) - 一个简单的TDengine桌面管理器（原创）.
- [TDengineGUI for 2.x & 3.x](https://github.com/arielyang/TDengineGUI) - 一个简单的TDengine桌面管理器，适用于TDengine 3.x.
- [Taos.Studio](https://github.com/maikebing/Taos.Studio) - 用于查看和编辑 TDengine 数据的 GUI 工具.
- [balloonfish](https://github.com/xielaoshi99/balloonfish) - 基于Electron + Vue3 + Vite2.0的TDengine时序数据库可视化管理工具.
- [tdengine-client](https://github.com/wurong1420/tdengine-client) - 简单的 TDengine 界面.
- [SQLAuto](https://github.com/TommyLemon/SQLAuto) - 一个智能的数据库SQL测试自动化工具，支持任意CRUD，任意模板变量，生成参数组合，生成大量数据行.

## IoT

- [Zeus IoT](https://github.com/zmops/zeus-iot) - Zeus IoT是全球首个基于Zabbix的开源物联网分布式采集平台，具备采集、分析、存储数百万物联网设备数据的能力.
- [DG-IoT](https://github.com/dgiot/dgiot-dashboard) - DG-IoT平台行业应用扩展插件.
- [dgiot_tdengine](https://github.com/dgiot/dgiot_tdengine) - TDengine 适配器插件.
- [node-red-contrib-tdengine](https://github.com/kp45-tech/node-red-contrib-tdengine) - 用于 Node-RED 的 TDengine 连接器插件.
- [IoTSharp](https://github.com/IoTSharp/IoTSharp/blob/master/IoTSharp.Data.TimeSeries/TaosStorage.cs) - IoTSharp是一个用于数据采集的开源物联网平台，它支持将时间序列数据存储到TDengine. 
- [WumeiSmart](https://github.com/kerwincui/wumei-smart) - WumeiSmart是一个智能生活物联网平台.
- [JetLinks](https://github.com/jetlinks/jetlinks-community) - JetLinks 是一个完全响应的企业级物联网平台.

## ORM
- [sqli](https://github.com/x-ream/sqli) - ORM SQL 接口、条件、CriteriaBuilder、ResultMapBuilder.
- [TDengine ORM Framework](https://github.com/hxshun/TDengineORM) - TAOS Data时序数据库TDengine的ORM框架.
- [IoTSharp.EntityFrameworkCore.Taos](https://github.com/IoTSharp/EntityFrameworkCore.Taos) - Entity, Framework, EF, Core, Data, O/RM, entity-framework-core, TDengine.
- [tdengine-orm](https://github.com/Yurunsoft/tdengine-orm) - 基于 tdengine-restful-connector 和 php-tdengine 的 TDengine ORM.<!--lint ignore awesome-list-item-->
- [crown](https://github.com/machine-w/crown) - crown 是一个用于 TDengine 的简单而小巧的 ORM.
- [APIJSON](https://github.com/Tencent/APIJSON) - 一个 JSON 传输协议和一个 ORM 库，用于在不编写任何代码的情况下提供 API 和文档.
- [ZORM](https://gitee.com/chunanyong/zorm) - ORM 通过 Go 支持 TDenging.
 
## Connector

- [PDO_TAOS](https://github.com/bearlord/pdo_taos) - PDO 的 TDengine 驱动程序.
- [yii2-tdengine](https://github.com/bearlord/yii2-tdengine) - yii2 的 TDengine，需要 pdo_taos.
- [php-tdengine](https://github.com/Yurunsoft/php-tdengine) - TDengine的PHP扩展，支持Swoole.
- [tdengine-restful-connector](https://github.com/Yurunsoft/tdengine-restful-connector) - TDengine的PHP扩展，支持Swoole.
- [imi-tdengine](https://github.com/imiphp/imi-tdengine) - 封装TDengine连接池，用于imi框架.
- [pytaos](https://github.com/horennel/pytaos) - TDengine 的 Python RESTful API.
- [Go Connector for TDengine](https://github.com/wenj91/taos-driver) - 实现Go-lang的内部数据库接口database/sql/driver.
- [node2tdengine](https://github.com/machine-w/node2tdengine)
- [NestJS TDengine Driver](https://github.com/IricBing/nestjs-tdengine) - NestJS TDengine 驱动程序（基于 RESTful）.
- [taos-rs](https://github.com/yuerrd/taos-rs) - TDengine Java RESTful 客户端.
- [TDengine Rust bindings](https://github.com/songtianyi/tdengine-rust-bindings) - 这是 TDengine 的 Rust 绑定项目.
- [TDenginex](https://github.com/lizhaochao/TDenginex) - Elixir 的 TDengine 连接器.
- [DBUtility.TDengine](https://github.com/cockroach888/GSA.MOLLE.ToolKits/tree/main/src/ToolKits.DBUtility) - C# Connector for TDengine. (.NET 6+). 
- [IoTSharp.Data.Taos](https://www.nuget.org/packages/IoTSharp.Data.Taos/)   - TDengine 的 ADO.Net 供应商.  （.Net Framework 4.6+、.Net Standard2.0+、.Net 5.0+）. 
- [taos-odbc](https://github.com/freemine/taos_odbc) - TDengine 3.0 的 ODBC 驱动程序，非常早期.

## Stack

- [NewLife.Core](https://github.com/NewLifeX/X) - NewLife.Core 数据库核心.
- [NewLife.XCode](https://github.com/NewLifeX/NewLife.XCode) - NewLife.XCode 数据库中间件.

## Plugin

<!--lint ignore awesome-list-item-->
- [rsyslog plugin for tdengine](https://github.com/mxmkeep/rsyslog-omtaos) - TDengine 的 rsyslog 插件.
- [HiveMQ TDengine Plugin](https://github.com/huskar-t/hivemq-tdengine-extension) - HiveMQ TDengine 插件.
- [hivemq-tdengine-jdsl-extension](https://github.com/huskar-t/hivemq-tdengine-jdsl-extension) - HiveMQ TDengine JDSL 插件.
- [HiveMQ-TDengine-Extension](https://github.com/john-bigz/hivemq-tdengine-extension) - HiveMQ 的 TDengine 扩展.
- [tdengine_hivemq](https://github.com/379547990/tdengine_hivemq) - HiveMQ 到 TDengine.
- [pulsar-io-tdengine](https://github.com/JueShanCoder/pulsar-io-tdengine) - TDengine 连接器连接 Pulsar 和 TDengine.

## Data

- [tsarchive](https://github.com/cenc-cea/tsarchive) - 从 Kafka 主题消费数据流，将数据包归档到 TDengine 时间序列数据库中.
- [flink-connector-tdengine](https://github.com/echisan/flink-connector-tdengine)
- [TD-Spark](https://github.com/liuyq-617/TD-Spark) - 一个java项目，从TDengine读取并写入到Spark上的TDengine.
- [Integrate TDengine to YoMo](https://github.com/yomorun/yomo-sink-tdengine-example) - 演示如何将TDengine集成到YoMo中，并将流处理后的数据存储到TDengine中.
- [YoMo x TDengine](https://github.com/fanweixiao/push-stream-logging) - 将高频日志流式传输到 TDengine.<!--lint ignore awesome-list-item-->
- [taostd](https://github.com/nzhzds/taostd) - taostd 是 TDengine 的一个简单的 sql 执行器.

## Algorithm

- [PyODDS](https://github.com/datamllab/pyodds) - 端到端异常值检测系统.
- [PYTSDA-TDengine](https://github.com/Shawshank-Smile/PYTSDA-TDengine) - 使用TDengine的端到端时间序列数据分析系统.

## Observability

- [TDengine interface for n9e transfer](https://github.com/xiangxud/transfer)
- [Business metrics monitoring based on TDengine](https://github.com/gunnerliu/horus) - 使用 TDengine 和 Spring Boot 高度定制的业务指标监控

## Container

- [TDengine cluster for kubernetes](https://github.com/wwbgo/tdengine-k8s) - 用于 kubernetes 的 TDengine 集群.
- [TDengine Containers](https://github.com/arktos-venture/docker-tdengine) - TDengine 客户端、节点、适配器和仲裁器尽可能无根和最小的容器.
- [TDengine-K8S](https://github.com/elihe2011/TDengine-K8S)

## Distribution

- [tdengine-client-macos-unofficial](https://github.com/cybartists/tdengine-client-macos-unofficial) - 用于 macOS 的非官方编译的 TDengine 客户端.
- [Unofficial TDengine Windows](https://github.com/GitHubForzhenjiazhao/Soft) - 非官方 TDengine Windows 客户端和服务器包.

## Dataset

- [seedlink2taos_py](https://github.com/schenton/seedlink2taos_py) - 从 IRIS 获取地震波形数据并写入 TDengine 数据库的 Python 程序.
- [airQuality](https://github.com/233lawliet/airQuality) - 3000+ 区空气质量指标：CO2、CO1、PM2.5、PM10 等.

## Others

- [auto_taos_cfg](https://github.com/glzhao89/auto_taos_cfg) - 自动生成 TDengine 日志/数据/cfg.
- [Sentinel Console](https://github.com/wenhao/sentinel-dashboard-tdengine) - 带有 TDengine 的哨兵仪表板.
- [Davinci](https://github.com/edp963/davinci) - Davinci 是一个 DVsaaS（数据可视化即服务）平台.
- [IoTSharp.HealthChecks.Taos](https://www.nuget.org/packages/IoTSharp.HealthChecks.Taos/)  - TDengine 的 HealthChecks 供应商.  （.Net 5.0+）. 
