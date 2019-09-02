<div class="github-widget" data-repo="shlomi-noach/awesome-mysql"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-mysql

精选的MySQL免费和开源软件，库和资源的精选列表. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 此列表接受并鼓励拉取请求.  看到 [CONTRIBUTING](https://github.com/shlomi-noach/awesome-mysql/blob/master/CONTRIBUTING.md)





## Analysis

*性能，结构和数据分析工具*

- [Anemometer](https://github.com/box/Anemometer) -  Box SQL慢查询监视器.
- [innodb-ruby](https://github.com/jeremycole/innodb_ruby) -  Ruby中InnoDB文件格式的解析器.
- [innotop](https://github.com/innotop/innotop) -  MySQL的“顶级”克隆，具有许多功能和灵活性.
- [MySQL Explain Analyzer](https://github.com/Preetam/explain-analyzer) - 基于Web的“EXPLAIN FORMAT = JSON”输出分析器，为保存的样本提供注释，可伸缩性分析和永久链接.
- [mysql-statsd](https://github.com/db-art/mysql-statsd) - 一个Python守护进程，用于从MySQL收集信息并通过StatsD将其发送到Graphite.
- [MySQLTuner-perl](http://mysqltuner.com) - 一个脚本，允许您快速查看MySQL安装并进行调整以提高性能和稳定性.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) - 用于管理和监控MySQL性能的开源平台.
- [Prometheus](https://prometheus.io/)/[mysqld_exporter](https://github.com/prometheus/mysqld_exporter) - 用于实时监控和警报的时间序列数据库.
- [pstop](https://github.com/sjmudd/ps-top) - 一个类似于MySQL的顶级程序，从performance_schema收集，聚合和显示信息.
## Backup

*备份/恢复/恢复工具*

- [MyDumper](https://github.com/maxbube/mydumper) -  MySQL的逻辑，并行备份/转储工具
- [MySQLDumper](http://www.mysqldumper.net/) - 基于开源Web的备份工具 - 对共享虚拟主机很有用
- [Percona Xtrabackup](http://www.percona.com/doc/percona-xtrabackup) - 基于MySQL的服务器的开源热备份实用程序，在备份期间不会锁定您的数据库.

## Benchmarking

*强调服务器的工具*

- [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) - 基于Java的MySQL / Percona / MariaDB索引插入基准版本.
- [Sysbench](https://github.com/akopytov/sysbench) - 模块化，跨平台和多线程的基准测试工具.
- [TPCC-MySQL](https://code.launchpad.net/~percona-dev/perconatools/tpcc-mysql) - 流行的港口 [TPCC](http://www.tpc.org/tpcc/) MySQL的基准.

## Binlog-Replication

- [Kingbus](https://github.com/flike/kingbus) - 基于Raft构建的分布式MySQL binlog存储系统
- [mysql-ripple](https://github.com/google/mysql-ripple) -  Ripple，一个可以作为MySQL复制中间人的服务器

## ChatOps

*脚本集成到聊天室*

- [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops)

## Configuration

* MySQL示例配置和顾问*

- [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) - 使MySQL配置更像MySQL的新版本（或更旧版本）.

## Connectors

*用于各种编程语言的MySQL连接器*

- [Connector/C](https://dev.mysql.com/downloads/connector/c/) -  MySQL的官方C驱动程序.
- [Connector/CPP](https://dev.mysql.com/downloads/connector/cpp/) -  MySQL的官方C ++驱动程序.
- [Connector/J](https://dev.mysql.com/downloads/connector/j/) - 用于Java平台和开发的标准化数据库驱动程序.
- [Connector/Net](https://dev.mysql.com/downloads/connector/net/) -  .Net平台和开发的标准化数据库驱动程序.
- [Connector/Node.js](https://dev.mysql.com/downloads/connector/nodejs/) -  MySQL的官方Node.js驱动程序.
- [Connector/Python](https://dev.mysql.com/downloads/connector/python/) - 用于Python平台和开发的标准化数据库驱动程序.
- [DBD::mysql](https://metacpan.org/pod/DBD::mysql) -  Perl5数据库接口的MySQL驱动程序.
- [go-sql-driver](https://github.com/go-sql-driver/mysql) -  Go（golang）数据库/ sql包的轻量级快速MySQL驱动程序.
- [libAttachSQL](https://github.com/libattachsql/libattachsql) -  libAttachSQL是一个用于MySQL服务器的轻量级，非阻塞的C API.
- [MariaDB Java Client](https://mariadb.com/kb/en/mariadb/mariadb-connector-j/) -  LGPL许可的用于Java应用程序的MariaDB客户端库.
- [mex-mariadb](https://github.com/markuman/mex-mariadb) - 麻省理工学院为GNU Octave和Matlab授权MariaDB / MySQL客户端库.
- [mysqlclient-python](https://github.com/PyMySQL/mysqlclient-python) - （旧）用于Python的MySQL数据库连接器.
- [node-mysql](https://github.com/felixge/node-mysql) - 实现MySQL协议的纯Nodejs Javascript客户端.
- [PHP mysqlnd](https://dev.mysql.com/downloads/connector/php-mysqlnd/) -  MySQL的MySQL本机驱动程序，不推荐使用旧的基于libmysql的驱动程序.
- [PyMySQL](https://github.com/PyMySQL/PyMySQL) - 用于Python的MySQL数据库连接器.
- [Ruby Mysql2 gem](https://github.com/brianmario/mysql2) - 用于Ruby和Rails项目的MySQL驱动程序.

## Deployment

* MySQL部署工具*

- [MySQL Docker](https://hub.docker.com/_/mysql/) -  Docker官方图片.
- [dbdeployer](https://www.dbdeployer.com) - 一种可在几秒钟内轻松，安全地完全控制安装一个或多个MySQL服务器的工具.


## Development

*支持MySQL相关开发的工具*

- [Flywaydb](http://flywaydb.org/getstarted/)   - 数据库迁移;  在所有实例中轻松可靠地发展数据库架构
- [Liquibase](http://www.liquibase.org/) - 数据库的源代码管理
- [Propagator](https://github.com/outbrain/propagator) - 在多种东西拓扑上集中架构和数据部署
- [Shift](https://github.com/square/shift) - 可帮助您在MySQL数据库上运行架构迁移的应用程序
- [Test database](https://github.com/datacharmer/test_db) - 带有集成测试套件的MySQL数据库示例，用于测试应用程序和服务器


## GUI

* GUI前端和应用*

- [Adminer](https://www.adminer.org/) - 单个PHP文件中的数据库管理.
- [HeidiSQL](http://www.heidisql.com/) - 适用于Windows的MySQL GUI前端.
- [mycli](https://github.com/dbcli/mycli) - 具有AutoCompletion和语法突出显示的MySQL终端客户端.
- [MySQL Shell](https://dev.mysql.com/downloads/shell/) -  MySQL的高级客户端和代码编辑器，支持MySQL服务器和MySQL InnoDB集群（AdminAPI）的开发和管理，具有交互式JavaScript，Python或SQL接口.
- [MySQL Workbench](http://dev.mysql.com/downloads/workbench/)   - 为DBA和开发人员提供数据库设计和建模的集成工具环境;  SQL开发;  数据库管理.
- [Ocelot GUI](https://github.com/ocelot-inc/ocelotgui) - 用于MySQL或MariaDB的GUI客户端，包括调试器.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) - 用于管理和监控MySQL性能的开源平台.
- [phpMyAdmin](https://www.phpmyadmin.net/) - 一个用PHP编写的免费软件工具，旨在通过Web管理MySQL.
- [pspg](https://github.com/okbob/pspg)   - 为表格数据提供增强的可视化和导航的寻呼机.  最初是为PostgreSQL实现的，但也支持MySQL.
- [SequelPro](https://github.com/sequelpro/sequelpro) - 用于处理MySQL数据库的Mac数据库管理应用程序.
- [SQLyog Community edition](https://github.com/webyog/sqlyog-community/wiki/Downloads)   -  SQLyog社区版.  对于Windows，在Mac和Linux下使用葡萄酒可以正常工作
- [DBeaver](https://github.com/dbeaver/dbeaver) - 跨平台的SQL和NoSQL数据库客户端.
- [OmniDB/OmniDB: Web tool for database management](https://github.com/OmniDB/OmniDB)

## HA

*高可用性解决方案*

- [Galera Cluster](http://galeracluster.com/products/) - 基于同步复制的真正多主机群集.
- [MHA](http://code.google.com/p/mysql-master-ha/) - 掌握MySQL的高可用性管理器和工具.
- [orchestrator](https://github.com/github/orchestrator) -  MySQL复制拓扑管理和高可用性解决方案.
- [Percona Replication Manager](https://github.com/percona/percona-pacemaker-agents/)   -  Pacemaker的异步MySQL复制管理器代理.  支持基于文件和GTID的复制，使用booth的地理分布式集群.
- [replication-manager](https://github.com/signal18/replication-manager) - 管理MariaDB 10.x和MySQL＆Percona Server 5.7 GTID复制拓扑的高可用性解决方案.

## Proxy

*代理MySQL *

- [MaxScale](https://github.com/mariadb-corporation/MaxScale) - 开源，以数据库为中心的代理.
- [Mixer](https://github.com/siddontang/mixer) - 由Go提供支持的MySQL代理，旨在为MySQL分片提供简单的解决方案.
- [MySQL Proxy](https://launchpad.net/mysql-proxy) - 位于客户端和MySQL服务器之间的简单程序，可以监视，分析或转换其通信.
- [ProxySQL](https://github.com/renecannao/proxysql) -  MySQL的高性能代理.
- [MySQL Router](https://dev.mysql.com/doc/mysql-router/en/) -  MySQL路由器是InnoDB集群的一部分，是一个轻量级中间件，提供应用程序和后端MySQL服务器之间的透明路由.

## Replication

*复制相关软件*



## Schema

*附加模式*

- [common_schema](https://github.com/shlomi-noach/common_schema) -  DBA的MySQL框架，提供函数库，视图库和QueryScript解释器.
- [sys](https://github.com/mysql/mysql-sys) - 一组视图，函数和过程，帮助MySQL管理员深入了解MySQL数据库的使用情况.


## Security

*防止数据库中敏感数据泄露的工具（加密，屏蔽和标记化，蜜罐等）*

- [Acra](https://github.com/cossacklabs/acra) -  SQL数据库保护套件：强选择性加密，SQL注入防护，入侵检测系统.

## Server

* MySQL服务器风味*

- [MariaDB](https://github.com/MariaDB/server) - 社区开发了MySQL服务器分支.
- [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) - 官方Oracle的MySQL服务器和MySQL Cluster分发.
- [Percona Server](https://launchpad.net/percona-server) - 增强的，免费的MySQL替代品.
- [TiDB](https://github.com/pingcap/tidb) - 与MySQL协议兼容的分布式HTAP数据库.

## Sharding

*分片解决方案/框架*

- [jetpants](https://github.com/tumblr/jetpants) -  Tumblr管理大范围分片集群的自动化套件.
- [vitess](https://github.com/vitessio/vitess) -  vitess提供服务器和工具，有助于扩展大型Web服务的MySQL数据库.


## Toolkits

*工具包，通用脚本*

- [gh-ost](https://github.com/github/gh-ost/) -  GitHub的MySQL在线模式迁移.
- [go-mysql](https://github.com/siddontang/go-mysql) - 一个纯go库来处理MySQL网络协议和复制.
- [MySQL Utilities](https://dev.mysql.com/downloads/utilities/) - 一组用Python编写的命令行实用程序，用于单独或在复制层次结构中维护和管理MySQL服务器.
- [openark kit](http://code.openark.org/forge/openark-kit) - 一组解决日常维护任务的实用程序，用Python编写可能很复杂或耗时.
- [Percona Toolkit](https://www.percona.com/software/mysql-tools/percona-toolkit) - 一组高级命令行工具，用于执行各种MySQL服务器和系统任务，这些任务太难或难以手动执行.
- [UnDROP](https://bitbucket.org/Marc-T/undrop-for-innodb) - 从丢弃或损坏的InnoDB表中恢复数据的工具.

## Resources

*在此阶段，“资源”将不包括网站，博客，幻灯片，演示视频等，因为担心列表大小*

## Conferences

*Public, recurring conferences on and around MySQL*

- [FOSDEM](https://fosdem.org/)   - 软件开发人员免费参加会议，分享想法和协作的活动.  每年，在布鲁塞尔.  提供“MySQL和朋友”房间.
- [MySQL Central](https://www.oracle.com/openworld/mysql/index.html) -  Oracle年度MySQL会议，作为Oracle Open World的一部分.
- [Percona Live](https://www.percona.com/live/conferences) -  MySQL和Openstack专注会议.
- [SCALE](https://www.socallinuxexpo.org)   - 每年在南加州举办的社区组织的Linux和开源会议.  本地MySQL社区以MySQL社区日的名义运行一条轨道.

## e-books

*电子书以及MySQL *周围的相关资料*

- [SQL-exercise](https://github.com/XD-DENG/SQL-exercise)   - 包含几个SQL练习，包括模式描述图，构建模式的SQL代码，SQL中的问题和解决方案.  基于wikibook [SQL Exercises](https://en.wikibooks.org/wiki/SQL_Exercises).

## Media

 *公开，持续的视频和音频演员.  由于担心列表大小，这不包括会议演示*


## Newsletters

 *根据定义，简报需要一个电子邮件地址.  以下列表是只需要电子邮件地址的简报*
