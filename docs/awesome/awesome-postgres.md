## Awesome Postgres [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

> A curated list of awesome [PostgreSQL](https://www.postgresql.org/) 软件，图书馆，工具和资源，受到启发 [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)

[PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL)，通常只是Postgres，是一个 [object-relational database](https://en.wikipedia.org/wiki/Object-relational_database)  （ORDBMS）.  PostgreSQL是 [ACID-compliant](https://en.wikipedia.org/wiki/ACID) 和 [transactional](https://en.wikipedia.org/wiki/Transaction_processing) .  （看更多： [wikipedia:PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL), [PostgreSQL.org](https://www.postgresql.org))

  ：elephant：欢迎捐款.  添加链接 [pull requests](https://github.com/dhamaniasad/awesome-postgres/pulls) 或创建一个 [issue](https://github.com/dhamaniasad/awesome-postgres/issues)  开始讨论.  请看看 [contribution guidelines](https://github.com/dhamaniasad/awesome-postgres/blob/master/CONTRIBUTING.md).

## Contents

- [High-Availability](#high-availability)
- [Backups](#backups)
- [GUI](#gui)
- [Distributions](#distributions)
- [CLI](#cli)
- [Server](#server)
- [Monitoring](#monitoring)
- [Extensions](#extensions)
- [Optimization](#optimization)
- [Utilities](#utilities)
- [Language bindings](#language-bindings)
- [Tutorials](#tutorials)
- [Blogs](#blogs)
- [Articles](#articles)
- [Newsletters](#newsletters)
- [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
- [Docker images](#docker-images)
- [Videos](#videos)

### High-Availability
* [BDR](https://github.com/2ndQuadrant/bdr) - 双向复制 -  PostgreSQL的多主机复制系统
* [Patroni](https://github.com/zalando/patroni) - 带有ZooKeeper或etcd的PostgreSQL HA模板.
* [Stolon](https://github.com/sorintlab/stolon) - 基于Consul或etcd的PostgreSQL HA，与Kubernetes集成.
* [pglookout](https://github.com/aiven/pglookout) - 复制监视和故障转移守护程序.
* [repmgr](https://github.com/2ndQuadrant/repmgr) - 用于管理PostgreSQL服务器群集中的复制和故障转移的开源工具套件.
* [Slony-I](http://slony.info) - 具有级联和故障转移功能的“Master to multiple slaves”复制系统.
* [PAF](https://github.com/ClusterLabs/PAF) -  PostgreSQL自动故障转移：Postgres的高可用性，基于Pacemaker和Corosync.
* [SkyTools](https://github.com/pgq/skytools-legacy) - 复制工具，包括PgQ，一个排队系统和Londiste，一个比Slony管理起来更简单的复制系统.

### Backups
* [Barman](https://www.pgbarman.org/index.html) -  2ndQuadrant的PostgreSQL备份和恢复管理器.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) -  PostgreSQL的高级WAL文件管理工具.
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) - 由@PostgresPro改进的pg \ _arman的分支，支持增量备份，从副本备份，多线程备份和还原，以及无归档命令的匿名备份.
* [pgBackRest](https://pgbackrest.org/)  - 可靠的PostgreSQL备份和恢复.
* [pg\_back](https://github.com/orgrim/pg_back/) -  pg \ _back是一个简单的备份脚本
* [pghoard](https://github.com/aiven/pghoard) - 云对象存储的备份和恢复工具（AWS S3，Azure，Google Cloud，OpenStack Swift）.
* [wal-e](https://github.com/wal-e/wal-e) - Simple Continuous Archiving for PostgreSQL to S3, Azure, or Swift by Heroku.
* [wal-g](https://github.com/wal-g/wal-g)   - 在Go中重写WAL-E的继任者.  目前仅支持S3.
* [pitrery](https://dalibo.github.io/pitrery/) -  pitrery是一组用于管理PostgreSQL的即时恢复（PITR）备份的Bash脚本.

### GUI
* [Adminer](https://www.adminer.org/) - 用PHP编写的全功能数据库管理工具.
* [OmniDB](https://omnidb.org/en/) - 开源协作环境
用于数据库管理
* [DataGrip](https://www.jetbrains.com/datagrip/) - 具有高级工具集和良好的跨平台经验的IDE（商业软件）.
* [Datazenit](https://datazenit.com/) - 基于Web的PostgreSQL GUI（商业软件）.
* [DBeaver](https://dbeaver.io/) - 通用数据库管理器，对PostgreSQL提供出色的支持.
* [dbglass](http://dbglass.web-pal.com) - 使用Electron构建的PostgreSQL跨平台桌面客户端.
* [Holistics](https://www.holistics.io/) - 具有强大PostgreSQL支持的在线跨平台数据库管理工具和SQL查询报告GUI（商业软件）.
* [JackDB](https://www.jackdb.com/) - 基于Web的SQL查询界面（商业软件）.
* [Metabase](https://www.metabase.com/) -  PostgreSQL的简单仪表板，图表和查询工具.
* [Numeracy](https://numeracy.co/) - 带有PostgreSQL（商业软件）图表和仪表板的快速SQL编辑器.
* [pgAdmin](https://www.pgadmin.org/) -  PostgreSQL管理和管理GUI.
* [pgModeler](https://pgmodeler.io/) -  pgModeler是一个开源的PostgreSQL数据库建模器.
* [pgweb](https://github.com/sosedoff/pgweb) - 用Go编写的基于Web的PostgreSQL数据库浏览器.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) -  PostgreSQL的Premier Web管理工具.
* [Postbird](https://github.com/Paxa/postbird) - 用于macOS的PostgreSQL客户端.
* [Postico](https://eggerapps.at/postico/) - 用于macOS的现代PostgreSQL客户端（商业软件）.
* [PSequel](http://www.psequel.com/) - 简洁的界面，可快速执行常见的PostgreSQL任务（商业软件）.
* [SQL Tabs](http://www.sqltabs.com/) - 用JS编写的PostgreSQL跨平台桌面客户端.
* [SQLPro for Postgres](http://macpostgresclient.com/) - 用于macOS（商业软件）的简单，强大的PostgreSQL管理器.
* [temBoard](https://github.com/dalibo/temboard) - 基于Web的PostgreSQL GUI和监控.
* [TablePlus](https://tableplus.io/)   -  Native App，可让您编辑数据库和结构.  确保高端安全性（商业软件）.
* [TeamSQL](https://teamsql.io/) - 跨平台SQL客户端：简单，轻松，可扩展.
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - 跨平台数据库管理工具（免费/商业）
* [PostgresCompare](https://www.postgrescompare.com) - 跨平台数据库比较和部署工具（商业软件）.

### Distributions
* [Postgres.app](https://postgresapp.com/) - 在macOS上开始使用PostgreSQL的最简单方法.
* [PostgreSql.Binaries.Lite](https://github.com/mihasic/PostgreSql.Binaries.Lite)   -  PostgreSQL数据库的最小Windows二进制文件集.  也通过NuGet提供.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) -  Postgres CLI具有自动完成和语法突出显示功能
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - 内置的PostgreSQL CLI客户端
* [psql2csv](https://github.com/fphilipe/psql2csv) - 在psql中运行查询并将结果输出为CSV

### Server
* [Postgres-XL](https://www.postgres-xl.org/) - 基于PostgreSQL的可扩展开源数据库集群.
* [Citus](https://github.com/citusdata/citus) - 可扩展的PostgreSQL集群，用于实时工作负载.
* [PipelineDB](https://www.pipelinedb.com/) -  PostgreSQL扩展，在流上连续运行SQL查询，逐步将结果存储在表中.
* [Greenplum Database](https://github.com/greenplum-db/gpdb) - 用于大数据量的PostgreSQL的开源分支.

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity)   - 检查\ __pgactivity旨在监控Nagios中的PostgreSQL集群.  它提供了许多选项来衡量和监控有用的性能指标.
* [Check\_postgres](https://github.com/bucardo/check_postgres) -  Nagios check \ _postgres插件，用于检查PostgreSQL数据库的状态.
* [Instrumental](https://github.com/Instrumental/instrumentald) - 实时性能监控，包括 [pre-made graphs](https://instrumentalapp.com/docs/instrumentald/postgresql#suggested-graphs) 易于安装（商业软件）
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) -  Zabbix的综合PostgreSQL监控模块.
* [Pome](https://github.com/rach/pome)   -  Pome代表PostgreSQL指标.  Pome是一个PostgreSQL指标仪表板，用于跟踪数据库的运行状况.
* [pg\_view](https://github.com/zalando/pg_view) - 开源命令行工具，显示全局系统统计信息，每分区信息，内存统计信息和其他信息.
* [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - 灵活且易于上手的PostgreSQL指标监控重点关注Grafana仪表板.
* [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) - 在PostgreSQL上运行基准测试.
* [opm.io](http://opm.io)   -  Open PostgreSQL Monitoring是一个免费软件套件，旨在帮助您管理PostgreSQL服务器.  它可以收集统计信息，显示仪表板并在出现问题时发送警告.

### Extensions
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - 使用PostgreSQL进行分析的列式存储.
* [cyanaudit](https://pgxn.org/dist/cyanaudit/) -  Cyan Audit以逐列为基础提供所有DML活动的数据库内日志记录.
* [pglogical](https://github.com/2ndQuadrant/pglogical) - 提供逻辑流复制的扩展.
* [pg\_partman](https://github.com/pgpartman/pg_partman) -  PostgreSQL的分区管理扩展.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - 为PostgreSQL节点集群基本实现Paxos和基于Paxos的表复制.
* [pg\_shard](https://github.com/citusdata/pg_shard) - 扩展以扩展实时读写.
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - 扩展以将CPU密集型工作负载卸载到GPU.
* [pgxn](https://pgxn.org/) PostgreSQL扩展网络 - 许多开源PostgreSQL扩展的中心分发点
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) - 允许检查plpgsql源代码的扩展.
* [PostGIS](http://postgis.net/) -  PostgreSQL的空间和地理对象.
* [PG\_Themis](https://github.com/cossacklabs/pg_themis) -  Postgres绑定作为加密库Themis的扩展，在PgSQL方面提供各种安全服务.
* [zomboDB](https://github.com/zombodb/zombodb) - 通过使用Elasticsearch支持的索引实现高效全文搜索的扩展.
* [pgMemento](https://github.com/pgMemento/pgMemento) - 使用PL / pgSQL编写的触发器和服务器端函数为PostgreSQL数据库内的数据提供审计跟踪.
* [Timescale](https://www.timescale.com/) - 与Postgres完全兼容的开源时间序列数据库，作为扩展分发
* [pgTAP](https://pgtap.org/) -  Postgres的数据库测试框架
* [HypoPG](https://github.com/HypoPG/hypopg) -  HypoPG提供假设/虚拟索引功能.

### Optimization
* [PgHero](https://github.com/ankane/pghero) -  PostgreSQL的见解变得简单.
* [pgtune](https://github.com/gregs1104/pgtune/) -  PostgreSQL配置向导.
* [pgtune](https://github.com/le0pard/pgtune) -  PostgreSQL配置向导的在线版本.
* [pgconfig.org](https://github.com/sebastianwebber/pgconfig) -  PostgreSQL在线配置工具（也基于pgtune）.
* [PoWA](https://powa.readthedocs.io/en/latest/) -  PostgreSQL Workload Analyzer收集性能统计数据并提供实时图表和图形，以帮助监控和调整PostgreSQL服务器.
* [pg_web_stats](https://github.com/kirs/pg_web_stats) - 用于查看pg_stat_statements的Web UI.

### Utilities
* [apgdiff](https://www.apgdiff.com/) - 比较两个数据库转储文件，并使用DDL语句创建输出，这些语句可用于将旧数据库模式更新为新数据库模式.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) -  ERAlchemy从数据库生成实体关系（ER）图.
* [ldap2pg](https://github.com/dalibo/ldap2pg) - 同步YML和LDAP的角色和权限.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) -  Lanyrd的MySQL到PostgreSQL转换脚本.
* [ora2pg](http://ora2pg.darold.net) - 用于将Oracle数据库模式导出到PostgreSQL兼容模式的Perl模块.
* [pg\_activity](https://github.com/julmon/pg_activity) - 类似于PostgreSQL服务器活动监控的应用程序.
* [pg-formatter](https://github.com/gajus/pg-formatter) -  PostgreSQL SQL语法美化器（Node.js）.
* [pganalyze](https://pganalyze.com) -  PostgreSQL性能监控（商业软件）.
* [pgbadger](https://github.com/darold/pgbadger) - 快速PostgreSQL日志分析器.
* [PgBouncer](http://pgbouncer.github.io) -  PostgreSQL的轻量级连接池.
* [pgCenter](https://github.com/lesovsky/pgcenter) - 为各种统计信息，管理任务，重新加载服务，查看日志文件以及取消或终止数据库后端提供方便的界面.
* [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - 从MySQL到PostgreSQL的实时副本，可选类型覆盖迁移和迁移功能.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - 将PostgreSQL中的数据导出为不同的数据格式.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - 以简单的方式将CSV和JSON导入PostgreSQL.
* [PGInsight](http://pginsight.io/) -  CLI工具，可以轻松深入挖掘PostgreSQL数据库.
* [pgloader](https://github.com/dimitri/pgloader) - 使用COPY流协议将数据加载到PostgreSQL中，并使用单独的线程读取和写入数据.
* [pgpool-II](http://www.pgpool.net/mediawiki/index.php/Main_Page) - 提供连接池，复制，负载平衡和限制超连接的中间件.
* [pgsync](https://github.com/ankane/pgsync) - 将PostgreSQL数据同步到本地计算机的工具.
* [PGXN client](https://github.com/dvarrazzo/pgxnclient) - 与PostgreSQL扩展网络交互的命令行工具
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - 为PostgreSQL数据库提取和提供指标的工具.
* [PostgREST](https://github.com/PostgREST/postgrest) - 从任何现有的PostgreSQL数据库提供完全RESTful的API.
* [pREST](https://github.com/prest/prest) - 从任何PostgreSQL数据库（Golang）提供RESTful API
* [PostGraphile](https://github.com/graphile/postgraphile) -  PostgreSQL数据库的Instant GraphQL API或GraphQL架构
* [yoke](https://github.com/nanopack/yoke) -  PostgreSQL高可用性集群，具有自动故障转移和自动集群恢复功能.
* [pglistend](https://github.com/kabirbaidhya/pglistend) - 构建在`node-postgres`之上的轻量级PostgresSQL`LISTEN` /`NOTIFY`守护进程.
* [ZSON](https://github.com/postgrespro/zson) - 用于透明JSONB压缩的PostgreSQL扩展
* [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) - 这是PostgreSQL的高速数据加载实用程序.
* [pg_migrate](https://github.com/jwdeitch/pg_migrate) - 管理PostgreSQL代码库并简化VCS.
* [sqitch](https://github.com/sqitchers/sqitch) - 用于管理版本化模式部署的工具
* [pgmigrate](https://github.com/yandex/pgmigrate) - 由Yandex开发的用于演进模式迁移的CLI工具.
* [pgcmp](https://github.com/cbbrowne/pgcmp) - 比较数据库模式的工具，具有接受一些持久性差异的能力
* [graphql-engine](https://github.com/hasura/graphql-engine) - 通过PostgreSQL获取即时实时GraphQL API.
* [sqlcheck](https://github.com/jarulraj/sqlcheck)   - 自动检测常见的SQL反模式.  这种反模式通常会减慢查询速度.  因此，解决这些问题将有助于加快查询速度.

### Language bindings
* Common Lisp： [Postmodern](https://github.com/marijnh/Postmodern)
* Clojure： [clj-postgresql](https://github.com/remodoy/clj-postgresql)
* Elixir： [postgrex](https://github.com/elixir-ecto/postgrex)
* 走： [pgx](https://github.com/jackc/pgx)
* Java： [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* .Net / .Net核心： [Npgsql](https://github.com/npgsql/npgsql)
*节点： [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise)
* Perl： [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm)
* PHP： [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python： [psycopg2](https://pypi.org/project/psycopg2/)
* Ruby： [pg](https://bitbucket.org/ged/ruby-pg/wiki/Home)
*锈： [rust-postgresql](https://github.com/sfackler/rust-postgres)
* Lua： [luapgsql](https://github.com/arcapos/luapgsql)

### Tutorials
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - 使用wal-e在PostgreSQL中设置连续存档的教程.
* [PG Casts](https://www.pgcasts.com) -  Hashrocket每周一次的免费PostgreSQL截屏视频.
* [Postgres Guide](http://postgresguide.com/) - 指南旨在帮助初学者和有经验的用户找到PostgreSQL中可用的特定技巧和探索工具.
* [PostgreSQL Exercises](https://pgexercises.com/) - 通过练习轻松学习PostgreSQL的网站.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - 关于PostgreSQL的非常广泛的教程集合
* [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) - 样本postgres模式的集合
* [PostgreSQL Primer for Busy People](https://zaiste.net/postgresql_primer_for_busy_people/) -  PostgreSQL中使用的最常用命令的集合

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) -  PostgreSQL的博客聚合服务.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](http://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) - 关于PostgreSQL的一些帖子很酷的功能，提示和技巧.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) -  Josh Berkus博客.
* [Michael Paquier's blog](https://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) -  Hubert Lubaczewski的博客.

### Articles

* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [Why use Postgres?](http://www.craigkerstiens.com/2017/04/30/why-postgres-five-years-later/)
* [Superfast CSV imports using PostgreSQL's COPY command](https://infinum.co/the-capsized-eight/superfast-csv-imports-using-postgresqls-copy)

### Newsletters

* [Postgres Weekly](https://postgresweekly.com/) - 每周简报，其中包含与PostgreSQL相关的文章，新闻和回购.

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql)   -  PostgreSQL作为AWS，Azure，DigitalOcean，Google Cloud和UpCloud中的服务;  计划范围从每月19美元的单节点实例到大型高可用性设置，免费试用两周.
* [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) -  PostgreSQL的Amazon Relational Database Service（RDS）
* [Citus Cloud](https://www.citusdata.com/product/cloud) - 生产等级将PostgreSQL扩展为一项服务，支持实时工作负载和分割多租户应用程序.
* [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/)   - 用于PostgreSQL的Azure数据库提供完全托管的企业级社区PostgreSQL数据库即服务.  它提供内置HA，弹性扩展和Azure生态系统的本机集成.
* [Database Labs](https://www.databaselabs.io) - 在几分钟内获得一个可投入生产的云PostgreSQL服务器，每月20美元，包括备份，监控，补丁和全天候技术支持.
* [ElephantSQL](https://www.elephantsql.com/)   - 提供数据库，包括用于较小项目的共享服务器和概念证明，以及企业级多服务器设置.  免费计划最多5个数据库，每个20 MB.
* [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/)   - 完全托管的数据库服务，可以轻松地在Google Cloud Platform上设置，维护，管理和管理PostgreSQL关系数据库.  （测试版）
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql)   - 由PostgreSQL专家运营的免费到大型计划.  不需要在Heroku上运行您的应用程序.  免费计划包括10,000行，20个连接，最多两个备份，并具有PostGIS支持.

### Docker images
* [citusdata/citus](https://hub.docker.com/r/citusdata/citus/)   - 带有citus扩展功能的Citus官方图片.  基于官方Postgres容器.
* [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) -  Postgres上的PostGIS 2.3 9.基于官方Postgres容器.
* [postgres](https://hub.docker.com/_/postgres/) - 官方postgres容器（来自Docker）

### Videos
* [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) -  Citus相关视频
* [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) -  EnterpriseDB相关视频
* [PGConf US Youtube channel](https://www.youtube.com/pgconfus/) - 会议视频
