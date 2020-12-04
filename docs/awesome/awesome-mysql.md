<div class="github-widget" data-repo="shlomi-noach/awesome-mysql"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-mysql

精选的精选MySQL免费和开源软件，库和资源. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

此列表接受并鼓励请求请求. 看到 [CONTRIBUTING](https://github.com/shlomi-noach/awesome-mysql/blob/master/CONTRIBUTING.md)





## Analysis

*性能，结构和数据分析工具*

- [Anemometer](https://github.com/box/Anemometer) -Box SQL慢查询监视器.
- [innodb-ruby](https://github.com/jeremycole/innodb_ruby) -使用Ruby的InnoDB文件格式的解析器.
- [innotop](https://github.com/innotop/innotop) -具有许多功能和灵活性的MySQL“顶级”克隆.
- [MySQL Explain Analyzer](https://github.com/Preetam/explain-analyzer) -基于Web的“ EXPLAIN FORMAT = JSON”输出的分析器，可为保存的样本提供注释，可伸缩性分析和永久链接.
- [mysql-statsd](https://github.com/db-art/mysql-statsd) -一个Python守护程序，用于从MySQL收集信息并将其通过StatsD发送到Graphite.
- [MySQLTuner-perl](http://mysqltuner.com) -允许您快速查看MySQL安装并进行调整以提高性能和稳定性的脚本.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) -一个用于管理和监视MySQL性能的开源平台.
- [Prometheus](https://prometheus.io/)/[mysqld_exporter](https://github.com/prometheus/mysqld_exporter) -用于实时监视和警报的时间序列数据库.
- [pstop](https://github.com/sjmudd/ps-top) -一个用于MySQL的顶级程序，用于收集，汇总和显示来自performance_schema的信息.
## Backup

*备份/还原/恢复工具*

- [Dumpling](https://github.com/pingcap/dumpling) -使用GoLang编写的用于MySQL / TiDB的逻辑并行备份/转储工具-支持csv格式输出并集成为库
- [MyDumper](https://github.com/maxbube/mydumper) -MySQL的逻辑，并行备份/转储工具
- [MySQLDumper](http://www.mysqldumper.net/) -开源的基于Web的备份工具-对于共享虚拟主机很有用
- [Percona Xtrabackup](http://www.percona.com/doc/percona-xtrabackup) -基于MySQL的开源热备份实用程序-基于服务器的服务器在备份过程中不会锁定数据库.

## Benchmarking

*压力服务器的工具*

- [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) -MySQL / Percona / MariaDB的基于Java版本的索引插入基准.
- [go-tpc](https://github.com/pingcap/go-tpc) -的高朗港口 [TPCC](http://www.tpc.org/tpcc/) 和 [TPCH](http://www.tpc.org/tpch/) MySQL的基准.
- [Sysbench](https://github.com/akopytov/sysbench) -模块化，跨平台和多线程的基准测试工具.
- [TPCC-MySQL](https://code.launchpad.net/~percona-dev/perconatools/tpcc-mysql) -受欢迎的港口 [TPCC](http://www.tpc.org/tpcc/) MySQL的基准.

## Binlog-Replication

- [DM](https://github.com/pingcap/dm) -高可用性数据迁移平台，支持将数据从MySQL / MariaDB迁移到TiDB并合并分片表
- [Kingbus](https://github.com/flike/kingbus) -基于Raft构建的分布式MySQL binlog存储系统
- [mysql-ripple](https://github.com/google/mysql-ripple) -Ripple，可以充当MySQL复制中间商的服务器

## ChatOps

*脚本集成到聊天室*

- [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops)

## Configuration

* MySQL示例配置和顾问*

- [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) -使MySQL配置表现得更像新（或更旧）的MySQL版本.

## Connectors

*适用于各种编程语言的MySQL连接器*

- [Connector/C](https://dev.mysql.com/downloads/connector/c/) -MySQL的官方C驱动程序.
- [Connector/CPP](https://dev.mysql.com/downloads/connector/cpp/) -MySQL的官方C ++驱动程序.
- [Connector/J](https://dev.mysql.com/downloads/connector/j/) -用于Java平台和开发的标准化数据库驱动程序.
- [Connector/Net](https://dev.mysql.com/downloads/connector/net/) -用于.Net平台和开发的标准化数据库驱动程序.
- [Connector/Node.js](https://dev.mysql.com/downloads/connector/nodejs/) -MySQL的官方Node.js驱动程序.
- [Connector/Python](https://dev.mysql.com/downloads/connector/python/) -用于Python平台和开发的标准化数据库驱动程序.
- [DBD::mysql](https://metacpan.org/pod/DBD::mysql) -Perl5数据库接口的MySQL驱动程序.
- [go-sql-driver](https://github.com/go-sql-driver/mysql) -Go的（golang）数据库/ sql软件包的轻量级和快速MySQL驱动程序.
- [libAttachSQL](https://github.com/libattachsql/libattachsql) -libAttachSQL是用于MySQL服务器的轻量级无阻塞C API.
- [MariaDB Java Client](https://mariadb.com/kb/en/mariadb/mariadb-connector-j/) -LGPL许可的Java应用程序MariaDB客户端库.
- [mex-mariadb](https://github.com/markuman/mex-mariadb) -MIT为GNU Octave和Matlab许可了MariaDB / MySQL客户端库.
- [mysqlclient-python](https://github.com/PyMySQL/mysqlclient-python) -（旧）适用于Python的MySQL数据库连接器.
- [node-mysql](https://github.com/felixge/node-mysql) -实现MySQL协议的纯Nodejs Javascript客户端.
- [PHP mysqlnd](https://dev.mysql.com/downloads/connector/php-mysqlnd/) -MySQL的MySQL本机驱动程序，不推荐使用基于libmysql的旧版驱动程序.
- [PyMySQL](https://github.com/PyMySQL/PyMySQL) -适用于Python的MySQL数据库连接器.
- [Ruby Mysql2 gem](https://github.com/brianmario/mysql2) -用于Ruby和Rails项目的MySQL驱动程序.

## Deployment

* MySQL部署工具*

- [MySQL Docker](https://hub.docker.com/_/mysql/) -官方Docker映像.
- [dbdeployer](https://www.dbdeployer.com) -一种工具，可在几秒钟内轻松，安全且具有完全控制权地安装一台或多台MySQL服务器.


## Development

*支持MySQL相关开发的工具*

- [Flywaydb](http://flywaydb.org/getstarted/)  -数据库迁移； 在所有实例中轻松可靠地扩展数据库架构
- [Liquibase](http://www.liquibase.org/) -数据库的源代码管理
- [Shift](https://github.com/square/shift) -帮助您在MySQL数据库上运行架构迁移的应用程序
- [Skeema](https://www.skeema.io) -用于MySQL和MariaDB的声明式纯SQL模式管理系统，支持分片和外部在线模式更改工具
- [Test database](https://github.com/datacharmer/test_db) -具有集成测试套件的示例MySQL数据库，用于测试应用程序和服务器


## GUI

* GUI前端和应用程序*

- [Adminer](https://www.adminer.org/) -在单个PHP文件中进行数据库管理.
- [HeidiSQL](http://www.heidisql.com/) - MySQL GUI frontend for Windows.
- [mycli](https://github.com/dbcli/mycli) -具有自动完成功能和语法突出显示功能的MySQL终端客户端.
- [MySQL Shell](https://dev.mysql.com/downloads/shell/) -MySQL的高级客户端和代码编辑器，通过交互式JavaScript，Python或SQL界面支持对MySQL Server和MySQL InnoDB集群（AdminAPI）的开发和管理.
- [MySQL Workbench](http://dev.mysql.com/downloads/workbench/)  -为DBA和开发人员提供用于数据库设计和建模的集成工具环境；  SQL开发数据库管理.
- [Ocelot GUI](https://github.com/ocelot-inc/ocelotgui) -MySQL或MariaDB的GUI客户端，包括调试器.
- [Percona Monitoring and Management](https://www.percona.com/doc/percona-monitoring-and-management/index.html) -一个用于管理和监视MySQL性能的开源平台.
- [phpMyAdmin](https://www.phpmyadmin.net/) -用PHP编写的免费软件工具，用于处理Web上的MySQL管理.
- [pspg](https://github.com/okbob/pspg)  -为寻呼机提供增强的表格数据可视化和导航功能. 最初为PostgreSQL实现，但也支持MySQL.
- [SequelPro](https://github.com/sequelpro/sequelpro) -Mac数据库管理应用程序，用于处理MySQL数据库.
- [SQLyog Community edition](https://github.com/webyog/sqlyog-community/wiki/Downloads)  -SQLyog社区版. 对于Windows，在Mac和Linux上的wine下运行良好
- [DBeaver](https://github.com/dbeaver/dbeaver) -跨平台的SQL和NoSQL数据库客户端.
- [OmniDB/OmniDB: Web tool for database management](https://github.com/OmniDB/OmniDB)

## HA

*高可用性解决方案*

- [Galera Cluster](http://galeracluster.com/products/) -基于同步复制的真正的Multimaster群集.
- [MHA](http://code.google.com/p/mysql-master-ha/) -掌握用于MySQL的High Availability Manager和工具.
- [orchestrator](https://github.com/github/orchestrator) -MySQL复制拓扑管理和高可用性解决方案.
- [Percona Replication Manager](https://github.com/percona/percona-pacemaker-agents/)  -用于Pacemaker的异步MySQL复制管理器代理. 使用展位支持基于文件和GTID的复制，地理分布的群集.
- [replication-manager](https://github.com/signal18/replication-manager) -用于管理MariaDB 10.x和MySQL＆Percona Server 5.7 GTID复制拓扑的高可用性解决方案.

## Proxy

* MySQL的代理*

- [MaxScale](https://github.com/mariadb-corporation/MaxScale) -开源，以数据库为中心的代理.
- [Mixer](https://github.com/siddontang/mixer) -由Go提供支持的MySQL代理，旨在为MySQL分片提供一种简单的解决方案.
- [MySQL Proxy](https://launchpad.net/mysql-proxy) -位于您的客户端和MySQL服务器之间的简单程序，可以监视，分析或转换其通信.
- [ProxySQL](https://github.com/renecannao/proxysql) -MySQL的高性能代理.
- [MySQL Router](https://dev.mysql.com/doc/mysql-router/en/) -MySQL路由器是InnoDB集群的一部分，并且是轻量级的中间件，可在应用程序和后端MySQL服务器之间提供透明的路由.

## Replication

*复制相关软件*



## Schema

*附加架构*

- [common_schema](https://github.com/shlomi-noach/common_schema) -DBA的MySQL框架，提供功能库，视图库和QueryScript解释器.
- [sys](https://github.com/mysql/mysql-sys) -一组视图，函数和过程，可帮助MySQL管理员深入了解MySQL数据库的使用.


## Security

*防止敏感数据从数据库泄漏的工具（加密，屏蔽和令牌化，蜜罐等）*

- [Acra](https://github.com/cossacklabs/acra) -SQL数据库保护套件：强大的选择性加密，SQL注入预防，入侵检测系统.

## Server

* MySQL服务器版本*

- [MariaDB](https://github.com/MariaDB/server) -社区开发的MySQL服务器分叉.
- [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) -官方的Oracle MySQL服务器和MySQL Cluster发行版.
- [Percona Server](https://launchpad.net/percona-server) -增强的嵌入式MySQL替代品.
- [TiDB](https://github.com/pingcap/tidb) -与MySQL协议兼容的分布式HTAP数据库.

## Sharding

*共享解决方案/框架*

- [jetpants](https://github.com/tumblr/jetpants) -Tumblr提供的用于管理大型分片集群的自动化套件.
- [vitess](https://github.com/vitessio/vitess) -vitess提供了有助于大规模数据库服务扩展MySQL数据库的服务器和工具.


## Toolkits

*工具包，通用脚本*

- [gh-ost](https://github.com/github/gh-ost/) -GitHub的MySQL在线模式迁移.
- [go-mysql](https://github.com/siddontang/go-mysql) -用于处理MySQL网络协议和复制的纯go库.
- [MySQL Utilities](https://dev.mysql.com/downloads/utilities/) -用Python编写的命令行实用程序的集合，用于单独或在复制层次结构中维护和管理MySQL服务器.
- [openark kit](http://code.openark.org/forge/openark-kit) -用Python编写的一组实用程序，可解决日常维护任务，这些任务可能很复杂或需要手工完成.
- [Percona Toolkit](https://www.percona.com/software/mysql-tools/percona-toolkit) -一组高级命令行工具，用于执行各种MySQL服务器和系统任务，这些任务太困难或太复杂而无法手动执行.
- [UnDROP](https://bitbucket.org/Marc-T/undrop-for-innodb) -从丢失或损坏的InnoDB表中恢复数据的工具.

## Resources

*在此阶段，“资源”将不包括网站，博客，幻灯片，演示视频等，因为担心列表大小*

## Conferences

*关于MySQL及其周围的公开，周期性会议*

- [FOSDEM](https://fosdem.org/)  -一个免费活动，软件开发人员可以见面，分享想法和合作. 每年在布鲁塞尔. 提供“ MySQL和朋友”空间.
- [MySQL Central](https://www.oracle.com/openworld/mysql/index.html) -作为Oracle开放世界的一部分的Oracle年度MySQL会议.
- [Percona Live](https://www.percona.com/live/conferences) -专注于MySQL和Openstack的会议.
- [SCALE](https://www.socallinuxexpo.org)  -社区组织了每年在南加州举行的Linux和开源会议. 本地MySQL社区以“ MySQL社区日”的名称运行.

## e-books

*有关MySQL及其周围的电子书以及相关材料*

- [Database Systems Lecture Notes](http://spots.augusta.edu/caubert/db/ln/) -有关数据库系统的讲义（可在pdf，html，odt和markdown中获得），其中包括有关SQL的一章，内容涉及基本设置，练习和问题.
- [SQL-exercise](https://github.com/XD-DENG/SQL-exercise)  -包含多个SQL练习，包括模式描述图，用于构建模式的SQL代码，SQL中的问题和解决方案. 基于Wikibook [SQL Exercises](https://en.wikibooks.org/wiki/SQL_Exercises).

## Media

*Public, ongoing video & audio casts. This excludes conference presentations in fear of list size*


## Newsletters

 *根据定义，通讯需要电子邮件地址. 以下列表是新闻通讯，只需要电子邮件地址*
