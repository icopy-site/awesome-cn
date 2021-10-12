<div class="github-widget" data-repo="shlomi-noach/awesome-mysql"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-mysql

精选的 MySQL 免费和开源软件、库和资源列表. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

此列表接受并鼓励拉取请求. 看 [CONTRIBUTING](https://github.com/shlomi-noach/awesome-mysql/blob/master/CONTRIBUTING.md)





## Analysis

*性能、结构和数据分析工具*

- [Anemometer](https://github.com/box/Anemometer) - Box SQL 慢查询监视器.
- [innodb-ruby](https://github.com/jeremycole/innodb_ruby) - InnoDB 文件格式的解析器，使用 Ruby.
- [innotop](https://github.com/innotop/innotop) - MySQL 的“顶级”克隆，具有许多功能和灵活性.
- [MySQL Explain Analyzer](https://github.com/Preetam/explain-analyzer) - 基于 Web 的“EXPLAIN FORMAT=JSON”输出分析器，为保存的样本提供注释、可扩展性分析和永久链接.
- [mysql-statsd](https://github.com/db-art/mysql-statsd) - 一个 Python 守护进程，用于从 MySQL 收集信息并通过 StatsD 将其发送到 Graphite.
- [MySQLTuner-perl](http://mysqltuner.com) - 允许您快速查看 MySQL 安装并进行调整以提高性能和稳定性的脚本.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) - 用于管理和监控 MySQL 性能的开源平台.
- [Prometheus](https://prometheus.io/)/[mysqld_exporter](https://github.com/prometheus/mysqld_exporter) - 用于实时监控和警报的时间序列数据库.
- [pstop](https://github.com/sjmudd/ps-top) - 一个顶级的 MySQL 程序，从 performance_schema 收集、聚合和显示信息.
## Backup

*备份/恢复/恢复工具*

- [Dumpling](https://github.com/pingcap/dumpling) - 用 GoLang 编写的用于 MySQL/TiDB 的逻辑并行备份/转储工具 - 支持 csv 格式输出并集成为库
- [MyDumper](https://github.com/maxbube/mydumper) - 用于 MySQL 的逻辑并行备份/转储工具
- [MySQLDumper](http://www.mysqldumper.net/) - 基于 Web 的开源备份工具 - 对共享虚拟主机很有用
- [Percona Xtrabackup](http://www.percona.com/doc/percona-xtrabackup) - 基于 MySQL 的开源热备份实用程序，在备份期间不会锁定您的数据库.

## Benchmarking

*给服务器施加压力的工具*

- [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) - 基于 Java 的 MySQL/Percona/MariaDB 索引插入基准测试版本.
- [go-tpc](https://github.com/pingcap/go-tpc) - 一个 golang 端口 [TPCC](http://www.tpc.org/tpcc/) 和 [TPCH](http://www.tpc.org/tpch/) MySQL 的基准测试.
- [Sysbench](https://github.com/akopytov/sysbench) - 一个模块化、跨平台和多线程的基准测试工具.
- [TPCC-MySQL](https://code.launchpad.net/~percona-dev/perconatools/tpcc-mysql) - 流行的港口 [TPCC](http://www.tpc.org/tpcc/) MySQL 的基准测试.

## Binlog-Replication

- [DM](https://github.com/pingcap/dm) - 高可用数据迁移平台，支持将数据从 MySQL/MariaDB 迁移到 TiDB 并合并分表
- [Kingbus](https://github.com/flike/kingbus) - 一个基于 Raft 构建的分布式 MySQL binlog 存储系统
- [mysql-ripple](https://github.com/google/mysql-ripple) - Ripple，一个可以作为 MySQL 复制中间人的服务器

## ChatOps

*脚本集成到聊天室*

- [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops)

## Configuration

*MySQL 示例配置和顾问*

- [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) - 使 MySQL 配置表现得更像较新（或较旧）版本的 MySQL.

## Connectors

*用于各种编程语言的 MySQL 连接器*

- [Connector/C](https://dev.mysql.com/downloads/connector/c/) - MySQL 的官方 C 驱动程序.
- [Connector/CPP](https://dev.mysql.com/downloads/connector/cpp/) - MySQL 的官方 C++ 驱动程序.
- [Connector/J](https://dev.mysql.com/downloads/connector/j/) - 用于 Java 平台和开发的标准化数据库驱动程序.
- [Connector/Net](https://dev.mysql.com/downloads/connector/net/) - 用于 .Net 平台和开发的标准化数据库驱动程序.
- [Connector/Node.js](https://dev.mysql.com/downloads/connector/nodejs/) - MySQL 的官方 Node.js 驱动程序.
- [Connector/Python](https://dev.mysql.com/downloads/connector/python/) - 用于 Python 平台和开发的标准化数据库驱动程序.
- [DBD::mysql](https://metacpan.org/pod/DBD::mysql) - Perl5 数据库接口的 MySQL 驱动程序.
- [go-sql-driver](https://github.com/go-sql-driver/mysql) - 一个轻量级且快速的 MySQL 驱动程序，用于 Go 的 (golang) 数据库/sql 包.
- [libAttachSQL](https://github.com/libattachsql/libattachsql) - libAttachSQL 是用于 MySQL 服务器的轻量级、非阻塞 C API.
- [MariaDB Java Client](https://mariadb.com/kb/en/mariadb/mariadb-connector-j/) - LGPL 许可的用于 Java 应用程序的 MariaDB 客户端库.
- [mex-mariadb](https://github.com/markuman/mex-mariadb) - MIT 许可的 MariaDB/MySQL 客户端库，用于 GNU Octave 和 Matlab.
- [mysqlclient-python](https://github.com/PyMySQL/mysqlclient-python) -（旧）用于 Python 的 MySQL 数据库连接器.
- [node-mysql](https://github.com/felixge/node-mysql) - 实现 MySQL 协议的纯 Nodejs Javascript 客户端.
- [PHP mysqlnd](https://dev.mysql.com/downloads/connector/php-mysqlnd/) - MySQL 的 MySQL 本机驱动程序，弃用旧的基于 libmysql 的驱动程序.
- [PyMySQL](https://github.com/PyMySQL/PyMySQL) - 用于 Python 的 MySQL 数据库连接器.
- [Ruby Mysql2 gem](https://github.com/brianmario/mysql2) - 用于 Ruby 和 Rails 项目的 MySQL 驱动程序.

## Deployment

*MySQL 部署工具*

- [MySQL Docker](https://hub.docker.com/_/mysql/) - 官方 Docker 镜像.
- [dbdeployer](https://www.dbdeployer.com) - 一种可在几秒钟内轻松、安全且完全控制地安装一个或多个 MySQL 服务器的工具.


## Development

*支持MySQL相关开发的工具*

- [Flywaydb](http://flywaydb.org/getstarted/)  - 数据库迁移； 在所有实例中轻松可靠地发展您的数据库架构
- [Liquibase](http://www.liquibase.org/) - 数据库的源代码控制
- [Shift](https://github.com/square/shift) - 帮助您在 MySQL 数据库上运行架构迁移的应用程序
- [Skeema](https://www.skeema.io) - 用于 MySQL 和 MariaDB 的声明式纯 SQL 模式管理系统，支持分片和外部在线模式更改工具
- [Test database](https://github.com/datacharmer/test_db) - 带有集成测试套件的示例 MySQL 数据库，用于测试应用程序和服务器


## GUI

*GUI 前端和应用程序*

- [Adminer](https://www.adminer.org/) - 单个 PHP 文件中的数据库管理.
- [HeidiSQL](http://www.heidisql.com/) - MySQL GUI frontend for Windows.
- [mycli](https://github.com/dbcli/mycli) - 具有自动完成和语法突出显示功能的 MySQL 终端客户端.
- [MySQL Shell](https://dev.mysql.com/downloads/shell/) - MySQL 的高级客户端和代码编辑器，通过交互式 JavaScript、Python 或 SQL 界面支持 MySQL 服务器和 MySQL InnoDB 集群 (AdminAPI) 的开发和管理.
- [MySQL Workbench](http://dev.mysql.com/downloads/workbench/)  - 为 DBA 和开发人员提供用于数据库设计和建模的集成工具环境；  SQL开发； 数据库管理.
- [Ocelot GUI](https://github.com/ocelot-inc/ocelotgui) - MySQL 或 MariaDB 的 GUI 客户端，包括调试器.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) - 用于管理和监控 MySQL 性能的开源平台.
- [phpMyAdmin](https://www.phpmyadmin.net/) - 一种用 PHP 编写的免费软件工具，旨在通过 Web 处理 MySQL 的管理.
- [pspg](https://github.com/okbob/pspg)  - 为表格数据提供具有增强的可视化和导航功能的寻呼机. 最初为 PostgreSQL 实现，但也支持 MySQL.
- [Sequel Ace](https://github.com/Sequel-Ace/Sequel-Ace) - 用于处理 MySQL 数据库的 Mac 数据库管理应用程序.
- [SQLyog Community edition](https://github.com/webyog/sqlyog-community/wiki/Downloads)  - SQLyog 社区版. 对于 Windows，在 Mac 和 Linux 中的 wine 下工作正常
- [DBeaver](https://github.com/dbeaver/dbeaver) - 跨平台的 SQL 和 NoSQL 数据库客户端.
- [OmniDB/OmniDB: Web tool for database management](https://github.com/OmniDB/OmniDB)

## HA

*高可用性解决方案*

- [Galera Cluster](http://galeracluster.com/products/) - 基于同步复制的真正多主集群.
- [MHA](http://code.google.com/p/mysql-master-ha/) - 掌握 MySQL 的高可用性管理器和工具.
- [orchestrator](https://github.com/github/orchestrator) - MySQL 复制拓扑管理和高可用性解决方案.
- [Percona Replication Manager](https://github.com/percona/percona-pacemaker-agents/)  - 用于 Pacemaker 的异步 MySQL 复制管理器代理. 支持基于文件和 GTID 的复制，使用booth 的地理分布式集群.
- [replication-manager](https://github.com/signal18/replication-manager) - 管理 MariaDB 10.x 和 MySQL &amp; Percona Server 5.7 GTID 复制拓扑的高可用性解决方案.

## Proxy

*MySQL 的代理*

- [MaxScale](https://github.com/mariadb-corporation/MaxScale) - 开源的、以数据库为中心的代理.
- [Mixer](https://github.com/siddontang/mixer) - 由 Go 提供支持的 MySQL 代理，旨在为 MySQL 分片提供简单的解决方案.
- [MySQL Proxy](https://launchpad.net/mysql-proxy) - 一个简单的程序，位于您的客户端和 MySQL 服务器之间，可以监视、分析或转换它们的通信.
- [ProxySQL](https://github.com/renecannao/proxysql) - MySQL 的高性能代理.
- [MySQL Router](https://dev.mysql.com/doc/mysql-router/en/) - MySQL Router 是 InnoDB 集群的一部分，是一个轻量级中间件，可在您的应用程序和后端 MySQL 服务器之间提供透明路由.

## Replication

*复制相关软件*



## Schema

*附加模式*

- [common_schema](https://github.com/shlomi-noach/common_schema) - DBA 的 MySQL 框架，提供函数库、视图库和 QueryScript 解释器.
- [sys](https://github.com/mysql/mysql-sys) - 一组视图、功能和过程，可帮助 MySQL 管理员深入了解 MySQL 数据库的使用情况.


## Security

*防止从数据库泄露敏感数据的工具（加密、屏蔽和标记化、蜜罐等）*

- [Acra](https://github.com/cossacklabs/acra) - SQL 数据库保护套件：强选择性加密、SQL 注入预防、入侵检测系统.

## Server

*MySQL 服务器口味*

- [MariaDB](https://github.com/MariaDB/server) - 社区开发的 MySQL 服务器分支.
- [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) - 官方 Oracle 的 MySQL 服务器和 MySQL 集群分布.
- [Percona Server](https://launchpad.net/percona-server) - 增强的、嵌入式 MySQL 替代品.
- [TiDB](https://github.com/pingcap/tidb) - 一个兼容 MySQL 协议的分布式 HTAP 数据库.

## Sharding

*分片解决方案/框架*

- [jetpants](https://github.com/tumblr/jetpants) - 一个用于管理大范围分片集群的自动化套件，由 Tumblr 提供.
- [vitess](https://github.com/vitessio/vitess) -vitess 提供有助于扩展 MySQL 数据库以用于大规模 Web 服务的服务器和工具.


## Toolkits

*工具包，通用脚本*

- [gh-ost](https://github.com/github/gh-ost/) - GitHub 的 MySQL 在线架构迁移.
- [go-mysql](https://github.com/siddontang/go-mysql) - 一个处理 MySQL 网络协议和复制的纯 go 库.
- [MySQL Utilities](https://dev.mysql.com/downloads/utilities/) - 一组用 Python 编写的命令行实用程序，用于单独或在复制层次结构中维护和管理 MySQL 服务器.
- [openark kit](http://code.openark.org/forge/openark-kit) - 一组用于解决日常维护任务的实用程序，用 Python 编写，手动完成这些任务可能很复杂或耗时.
- [Percona Toolkit](https://www.percona.com/software/mysql-tools/percona-toolkit) - 一组高级命令行工具，用于执行各种难以手动执行或过于复杂的 MySQL 服务器和系统任务.
- [UnDROP](https://bitbucket.org/Marc-T/undrop-for-innodb) - 从删除或损坏的 InnoDB 表中恢复数据的工具.

## Resources

*现阶段“资源”将不包括网站、博客、幻灯片、演示视频等，因为担心列表大小*

## Conferences

*关于 MySQL 及其周围的公共、定期会议*

- [FOSDEM](https://fosdem.org/)  - 软件开发人员见面、分享想法和协作的免费活动. 每年，在布鲁塞尔. 提供“MySQL &amp; Friends”房间.
- [MySQL Central](https://www.oracle.com/openworld/mysql/index.html) - 作为 Oracle Open World 的一部分，Oracle 的年度 MySQL 会议.
- [Percona Live](https://www.percona.com/live/conferences) - MySQL 和 Openstack 重点会议.
- [SCALE](https://www.socallinuxexpo.org)  - 社区组织的 Linux 和开源会议每年在南加州举行. 本地 MySQL 社区以 MySQL Community Day 的名义运行一个轨道.

## e-books

*有关 MySQL 的电子书以及相关材料*

- [Database Systems Lecture Notes](http://spots.augusta.edu/caubert/db/ln/) - 关于数据库系统的讲义（以 pdf、html、odt 和 markdown 格式提供），包括关于 SQL 的一章，其中涵盖了基本设置、练习和问题.
- [SQL-exercise](https://github.com/XD-DENG/SQL-exercise)  - 包含多个 SQL 练习，包括模式描述图、用于构建模式的 SQL 代码、SQL 中的问题和解决方案. 基于维基书 [SQL Exercises](https://en.wikibooks.org/wiki/SQL_Exercises).

## Media

*Public, ongoing video & audio casts. This excludes conference presentations in fear of list size*


## Newsletters

 *根据定义，时事通讯需要电子邮件地址. 以下列表是只需要电子邮件地址的时事通讯*
