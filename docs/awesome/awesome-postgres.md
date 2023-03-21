<div class="github-widget" data-repo="dhamaniasad/awesome-postgres"></div>
## Awesome Postgres [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

&gt; 精选清单 [PostgreSQL](https://www.postgresql.org/) 软件、库、工具和资源，灵感来自 [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)

[PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL)，通常只是 Postgres，是一个 [object-relational database](https://en.wikipedia.org/wiki/Object-relational_database)  （ORDBMS）.  PostgreSQL 是 [ACID-compliant](https://en.wikipedia.org/wiki/ACID) 和 [transactional](https://en.wikipedia.org/wiki/Transaction_processing) .  （查看更多： [wikipedia:PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL), [PostgreSQL.org](https://www.postgresql.org))

  :elephant: 欢迎投稿. 通过添加链接 [pull requests](https://github.com/dhamaniasad/awesome-postgres/pulls) 或创建一个 [issue](https://github.com/dhamaniasad/awesome-postgres/issues) 开始讨论. 请看一下 [contribution guidelines](https://github.com/dhamaniasad/awesome-postgres/blob/master/CONTRIBUTING.md).



### High-Availability
* [BDR](https://github.com/2ndQuadrant/bdr) - 双向复制 - PostgreSQL 的多主复制系统
* [Patroni](https://github.com/zalando/patroni) - 带有 ZooKeeper 或 etcd 的 PostgreSQL HA 模板.
* [Stolon](https://github.com/sorintlab/stolon) - 基于 Consul 或 etcd 的 PostgreSQL HA，与 Kubernetes 集成.
* [pglookout](https://github.com/aiven/pglookout) - Replication monitoring and failover daemon.
* [repmgr](https://github.com/2ndQuadrant/repmgr) - 用于管理 PostgreSQL 服务器集群中的复制和故障转移的开源工具套件.
* [Slony-I](https://slony.info/) - 具有级联和故障转移功能的“Master to multiple slaves”复制系统.
* [PAF](https://github.com/ClusterLabs/PAF) - PostgreSQL 自动故障转移：基于 Pacemaker 和 Corosync 的 Postgres 高可用性.
* [SkyTools](https://github.com/pgq/skytools-legacy) - 复制工具，包括队列系统 PgQ 和比 Slony 更易于管理的复制系统 Londiste.

### Backups
* [Barman](https://www.pgbarman.org/index.html) - 2ndQuadrant 的 PostgreSQL 备份和恢复管理器.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) - 用于 PostgreSQL 的高级 WAL 文件管理工具.
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) – pg\_arman 的一个分支，由@PostgresPro 改进，支持增量备份、从副本备份、多线程备份和恢复，以及没有存档命令的匿名备份.
* [pgBackRest](https://pgbackrest.org/)  - 可靠的 PostgreSQL 备份和恢复.
* [pg\_back](https://github.com/orgrim/pg_back/) - pg\_back 是一个简单的备份脚本
* [pghoard](https://github.com/aiven/pghoard) - 用于云对象存储（AWS S3、Azure、谷歌云、OpenStack Swift）的备份和恢复工具.
* [wal-e](https://github.com/wal-e/wal-e) （已过时）- Heroku 将 PostgreSQL 简单连续归档到 S3、Azure 或 Swift.
* [wal-g](https://github.com/wal-g/wal-g)  - 用 Go 重写的 WAL-E 的继任者. 目前支持 AWS (S3)、谷歌云 (GCS)、Azure 以及 OpenStack Swift、MinIO 和文件系统存储的云对象存储服务. 支持块级增量备份，将备份任务卸载到备用服务器，提供并行化和节流选项. 除了 Postgres 之外，WAL-G 还可以用于 MySQL 和 MongoDB 数据库.
* [pitrery](https://dalibo.github.io/pitrery/) - pitrery 是一组 Bash 脚本，用于管理 PostgreSQL 的时间点恢复 (PITR) 备份.

### GUI
* [Adminer](https://www.adminer.org/) - 用 PHP 编写的全功能数据库管理工具.
* [Beekeeper Studio](https://www.beekeeperstudio.io)  - 免费和开源的 SQL 客户端，具有现代 UI 和强大的 Postgres 支持. 跨平台.
* [Chartbrew](https://chartbrew.com)  - 从 PostgreSQL 数据创建实时仪表板、图表和客户报告. 具有可与 SQL 配合使用的查询工具.
* [Count](https://count.co/) - 基于 Web 的分析平台，带有连接到 PostgreSQL（商业软件）的笔记本界面.
* [DataGrip](https://www.jetbrains.com/datagrip/) - 具有高级工具集和良好跨平台体验的 IDE（商业软件）.
* [Datazenit](https://datazenit.com/) - 基于 Web 的 PostgreSQL GUI（商业软件）.
* [DataRow](https://www.datarow.com/) - 适用于 Amazon Redshift 的跨平台 SQL 客户端：简单、轻松、可扩展.
* [DBeaver](https://dbeaver.io/) - 对 PostgreSQL 提供出色支持的通用数据库管理器.
* [dbglass](http://dbglass.web-pal.com) - PostgreSQL 的跨平台桌面客户端，使用 Electron 构建.
* [Holistics](https://www.holistics.io/) - 在线跨平台数据库管理工具和 SQL 查询报告 GUI，具有强大的 PostgreSQL 支持（商业软件）.
* [JackDB](https://www.jackdb.com/) - 基于 Web 的 SQL 查询界面（商业软件）.
* [Metabase](https://www.metabase.com/) - 用于 PostgreSQL 的简单仪表板、图表和查询工具.
* [Numeracy](https://numeracy.co/) - 具有 PostgreSQL（商业软件）图表和仪表板的快速 SQL 编辑器.
* [OmniDB](https://omnidb.org/en/) - 开源协作环境
对于数据库管理
* [pgAdmin](https://www.pgadmin.org/) - PostgreSQL 管理和管理 GUI.
* [pgModeler](https://pgmodeler.io/) - pgModeler 是一个开源的 PostgreSQL 数据库建模器.
* [pgweb](https://github.com/sosedoff/pgweb) - 用 Go 编写的基于 Web 的 PostgreSQL 数据库浏览器.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - 用于 PostgreSQL 的首要基于 Web 的管理工具.
* [Postbird](https://github.com/Paxa/postbird) - 适用于 macOS 的 PostgreSQL 客户端.
* [PostgresCompare](https://www.postgrescompare.com) - 跨平台数据库比较和部署工具（商业软件）.
* [Postico](https://eggerapps.at/postico/) - 适用于 macOS 的现代 PostgreSQL 客户端（商业软件）.
* [PSequel](http://www.psequel.com/) - 干净简单的界面可以快速执行常见的 PostgreSQL 任务（商业软件）.
* [SQL Tabs](http://www.sqltabs.com/) - 用 JS 编写的 PostgreSQL 跨平台桌面客户端.
* [SQLPro for Postgres](http://macpostgresclient.com/) - 用于 macOS（商业软件）的简单、强大的 PostgreSQL 管理器.
* [temBoard](https://github.com/dalibo/temboard) - 基于 Web 的 PostgreSQL GUI 和监控.
* [TablePlus](https://tableplus.com/)  - 让您编辑数据库和结构的本机应用程序. 确保高端安全性（商业软件）.
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - 跨平台数据库管理工具（免费/商业）
* [DbGate](https://dbgate.org) - 最聪明的（无）SQL 数据库客户端

### Distributions
* [Postgres.app](https://postgresapp.com/) - 在 macOS 上开始使用 PostgreSQL 的最简单方法.
* [PostgreSql.Binaries.Lite](https://github.com/mihasic/PostgreSql.Binaries.Lite)  - PostgreSQL 数据库的最小 Windows 二进制文件集. 也可通过 NuGet 获得.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - 具有自动完成和语法高亮显示的 Postgres CLI
* [pgsh](https://github.com/sastraxi/pgsh) - 像 Git 一样分支你的 PostgreSQL 数据库
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - 内置的 PostgreSQL CLI 客户端
* [psql2csv](https://github.com/fphilipe/psql2csv) - 在 psql 中运行查询并将结果输出为 CSV
* [nancy](https://gitlab.com/postgres-ai/nancy) - Nancy CLI 是一种统一的方式来管理云端或本地的自动化数据库实验
* [schemaspy](https://github.com/schemaspy/schemaspy) - SchemaSpy 是一个 JAVA JDBC 兼容工具，用于将数据库生成为 HTML 文档，包括实体关系图

### Server
* [Postgres-XL](https://www.postgres-xl.org/) - 可扩展的基于 PostgreSQL 的开源数据库集群.
* [AgensGraph](https://bitnine.net/) - 基于 PostgreSQL 的强大图形数据库.
* [Greenplum Database](https://github.com/greenplum-db/gpdb) - 用于大数据量的 PostgreSQL 开源分支.

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity)  - check\_pgactivity 旨在从 Nagios 监控 PostgreSQL 集群. 它提供了许多选项来衡量和监控有用的性能指标.
* [Check\_postgres](https://github.com/bucardo/check_postgres) - Nagios check\_postgres 插件，用于检查 PostgreSQL 数据库的状态.
* [Instrumental](https://github.com/Instrumental/instrumentald) - 实时性能监控，包括 [pre-made graphs](https://instrumentalapp.com/docs/instrumentald/postgresql#suggested-graphs) 为了便于设置（商业软件）
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) - Zabbix 的综合 PostgreSQL 监控模块.
* [PMM](https://github.com/percona/pmm) - Percona 监控和管理 (PMM) 是一个免费的开源平台，用于监控和管理 PostgreSQL、MySQL 和 MongoDB.
* [Pome](https://github.com/rach/pome)  - Pome 代表 PostgreSQL 指标.  Pome 是一个 PostgreSQL 指标仪表板，用于跟踪数据库的健康状况.
* [pgmetrics](https://pgmetrics.io/) - pgmetrics 是一种开源、零依赖、单一二进制工具，可以从正在运行的 PostgreSQL 服务器收集大量信息和统计数据，并以易于阅读的文本格式显示或将其导出为 JSON 和 CSV 以用于脚本.
* [pg\_view](https://github.com/zalando/pg_view) - 显示全局系统统计信息、每个分区信息、内存统计信息和其他信息的开源命令行工具.
* [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - 灵活且易于上手的 PostgreSQL 指标监控器专注于 Grafana 仪表板.
* [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) - 在 PostgreSQL 上运行基准测试.
* [opm.io](http://opm.io)  - Open PostgreSQL Monitoring 是一款免费软件套件，旨在帮助您管理 PostgreSQL 服务器. 它可以收集统计数据、显示仪表板并在出现问题时发送警告.
* [okmeter.io](https://okmeter.io/pg)  - 基于商业 SaaS 代理的监控，带有非常详细的 PostgreSQL 插件. 它会自动收集 100 项统计数据，在各个方面显示仪表板，并在出现问题时发送警报（商业软件）.
* [dexter](https://github.com/ankane/dexter)  - Postgres 的自动索引器. 检测慢速查询并创建索引（如果配置为这样做）.

### Extensions
* [Citus](https://github.com/citusdata/citus) - 用于实时工作负载的可扩展 PostgreSQL 集群.
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - 用于使用 PostgreSQL 进行分析的列式存储.
* [cyanaudit](https://pgxn.org/dist/cyanaudit/) - Cyan Audit 逐列提供所有 DML 活动的数据库内日志记录.
* [pg_cron](https://github.com/citusdata/pg_cron) - 在 PostgreSQL 中运行定期作业.
* [pglogical](https://github.com/2ndQuadrant/pglogical) - 提供逻辑流复制的扩展.
* [pg\_partman](https://github.com/pgpartman/pg_partman) - PostgreSQL 的分区管理扩展.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - PostgreSQL 节点集群的 Paxos 和基于 Paxos 的表复制的基本实现.
* [pg\_shard](https://github.com/citusdata/pg_shard) - 扩展以扩展实时读取和写入.
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - 将 CPU 密集型工作负载卸载到 GPU 的扩展.
* [pgxn](https://pgxn.org/) PostgreSQL 扩展网络 - 许多开源 PostgreSQL 扩展的中央分发点
* [PipelineDB](https://www.confluent.io/blog/pipelinedb-team-joins-confluent/) - 一个 PostgreSQL 扩展，它在流上连续运行 SQL 查询，将结果增量存储在表中.
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) - 允许检查 plpgsql 源代码的扩展.
* [PostGIS](http://postgis.net/) - PostgreSQL 的空间和地理对象.
* [PG\_Themis](https://github.com/cossacklabs/pg_themis) - Postgres 绑定作为加密库 Themis 的扩展，在 PgSQL 端提供各种安全服务.
* [zomboDB](https://github.com/zombodb/zombodb) - 通过使用 Elasticsearch 支持的索引实现高效全文搜索的扩展.
* [pgMemento](https://github.com/pgMemento/pgMemento) - 使用以 PL/pgSQL 编写的触发器和服务器端函数，为您在 PostgreSQL 数据库中的数据提供审计跟踪.
* [TimescaleDB](https://www.timescale.com/) - 与 Postgres 完全兼容的开源时间序列数据库，作为扩展分发
* [pgTAP](https://pgtap.org/) - Postgres 的数据库测试框架
* [HypoPG](https://github.com/HypoPG/hypopg) - HypoPG 提供假设/虚拟索引功能.
* [pgRouting](https://github.com/pgRouting/pgrouting) - pgRouting 扩展了 PostGIS/PostgreSQL 地理空间数据库以提供地理空间路由和其他网络分析功能.
* [PGroonga](https://pgroonga.github.io/) - PGroonga 提供了一种新的索引访问方法，该方法使用 Groonga 允许针对所有语言的超快速全文搜索功能.
* [PGAudit](https://www.pgaudit.org/) - PostgreSQL 审计扩展（或 pgaudit）通过 PostgreSQL 提供的标准日志工具提供详细的会话和/或对象审计日志.

### Optimization
* [pg_flame](https://github.com/mgartner/pg_flame) - 用于查询计划的火焰图生成器.
* [PgHero](https://github.com/ankane/pghero) - PostgreSQL 见解变得简单.
* [pgMustard](https://www.pgmustard.com/) - 现代的用户界面
对于 `EXPLAIN`，它还提供性能提示（商业软件）.
* [pgtune](https://github.com/gregs1104/pgtune/) - PostgreSQL 配置向导.
* [pgtune](https://github.com/le0pard/pgtune) - 在线版 PostgreSQL 配置向导.
* [pgconfig.org](https://github.com/sebastianwebber/pgconfig) - PostgreSQL 在线配置工具（也基于 pgtune）.
* [PoWA](https://powa.readthedocs.io/en/latest/) - PostgreSQL 工作负载分析器收集性能统计数据并提供实时图表和图形以帮助监控和调整您的 PostgreSQL 服务器.
* [pg_web_stats](https://github.com/kirs/pg_web_stats) - 用于查看 pg_stat_statements 的 Web UI.
* [TimescaleDB Tune](https://github.com/timescale/timescaledb-tune) - 用于调整 TimescaleDB 数据库以根据主机资源（如内存和 CPU 数量）发挥最佳性能的程序.

### Utilities
* [apgdiff](https://www.apgdiff.com/) - 比较两个数据库转储文件并使用 DDL 语句创建输出，这些语句可用于将旧数据库模式更新为新模式.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy 从数据库生成实体关系 (ER) 图.
* [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) - 具有细粒度访问控制的 Postgres 上快速、即时的实时 GraphQL API，还可以触发数据库事件的 webhook.
* [ldap2pg](https://github.com/dalibo/ldap2pg) - 从 YML 和 LDAP 同步角色和权限.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd 的 MySQL 到 PostgreSQL 的转换脚本.
* [ora2pg](http://ora2pg.darold.net) - 用于将 Oracle 数据库模式导出到 PostgreSQL 兼容模式的 Perl 模块.
* [pg\_activity](https://github.com/dalibo/pg_activity) - 用于 PostgreSQL 服务器活动监控的顶级应用程序.
* [pg-formatter](https://github.com/gajus/pg-formatter) - 一个 PostgreSQL SQL 语法美化器 (Node.js).
* [pganalyze](https://pganalyze.com) - PostgreSQL 性能监控（商业软件）.
* [pgbadger](https://github.com/darold/pgbadger) - 快速 PostgreSQL 日志分析器.
* [PgBouncer](http://www.pgbouncer.org/) - PostgreSQL 的轻量级连接池.
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends.
* [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - 从 MySQL 到 PostgreSQL 的实时副本，具有可选的类型覆盖迁移和迁移功能.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - 将数据从 PostgreSQL 导出为不同的数据格式.
* [pg_docs_bot](https://github.com/mchristofides/pg_docs_bot/) - 将 PostgreSQL 文档链接重定向到当前版本的浏览器扩展.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - 以简单的方式将 CSV 和 JSON 导入 PostgreSQL.
* [PGInsight](http://pginsight.io/) - 可轻松深入挖掘 PostgreSQL 数据库的 CLI 工具.
* [pg_insights](https://github.com/lob/pg_insights) - 用于监控 Postgres 数据库健康状况的便捷 SQL.
* [pgloader](https://github.com/dimitri/pgloader) - 使用 COPY 流协议将数据加载到 PostgreSQL 中，并使用单独的线程来读取和写入数据.
* [pgMonitor](https://github.com/CrunchyData/pgmonitor) - 可以部署到裸机、虚拟机或 Kubernetes 的 Postgres 指标收集和可视化.
* [pgpool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) - 提供连接池、复制、负载平衡和限制超出连接的中间件.
* [pgsync](https://github.com/ankane/pgsync) - 将 PostgreSQL 数据同步到本地计算机的工具.
* [PGXN client](https://github.com/pgxn/pgxnclient) - 与 PostgreSQL 扩展网络交互的命令行工具
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - 为您的 PostgreSQL 数据库提取和提供指标的工具.
* [PostgREST](https://github.com/PostgREST/postgrest) - 提供来自任何现有 PostgreSQL 数据库的完全 RESTful API.
* [pREST](https://github.com/prest/prest) - 从任何 PostgreSQL 数据库 (Golang) 提供 RESTful API
* [PostGraphile](https://github.com/graphile/postgraphile) - 用于您的 PostgreSQL 数据库的即时 GraphQL API 或 GraphQL 架构
* [yoke](https://github.com/nanopack/yoke) - 具有自动故障转移和自动集群恢复功能的 PostgreSQL 高可用性集群.
* [pglistend](https://github.com/kabirbaidhya/pglistend) - 构建在 node-postgres 之上的轻量级 PostgresSQL `LISTEN`/`NOTIFY` 守护进程.
* [ZSON](https://github.com/postgrespro/zson) - 用于透明 JSONB 压缩的 PostgreSQL 扩展
* [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) - 它是 PostgreSQL 的高速数据加载实用程序.
* [pg_migrate](https://github.com/jwdeitch/pg_migrate) - 管理 PostgreSQL 代码库并简化 VCS.
* [sqitch](https://github.com/sqitchers/sqitch) - 用于管理版本化模式部署的工具
* [pgmigrate](https://github.com/yandex/pgmigrate) - 用于发展模式迁移的 CLI 工具，由 Yandex 开发.
* [pgcmp](https://github.com/cbbrowne/pgcmp) - 比较数据库模式的工具，能够接受一些持久的差异
* [pg-differ](https://github.com/multum/pg-differ) - 用于轻松初始化/更新 PostgreSQL 表结构的工具，迁移替代方案 (Node.js).
* [sqlcheck](https://github.com/jarulraj/sqlcheck)  - 自动检测常见的 SQL 反模式. 这种反模式通常会减慢查询速度. 因此，解决这些问题将有助于加速查询.
* [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - 新一代诊断工具，允许用户收集对 Postgres 数据库健康状况的深入分析.
* [ScaffoldHub.io](https://scaffoldhub.io) - 使用 Angular、Vue 或 React（商业软件）生成全栈 PostgreSQL 应用程序. 

### Language bindings
* 普通口齿不清： [Postmodern](https://github.com/marijnh/Postmodern)
* 语言： [clj-postgresql](https://github.com/remodoy/clj-postgresql)
*长生不老药： [postgrex](https://github.com/elixir-ecto/postgrex)
* 去： [pq](https://github.com/lib/pq), [pgx](https://github.com/jackc/pgx)
*哈斯克尔： [postgresql-simple](http://hackage.haskell.org/package/postgresql-simple)
*爪哇： [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* .Net/.Net核心： [Npgsql](https://github.com/npgsql/npgsql)
*节点： [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise), [pogi](https://github.com/holdfenytolvaj/pogi), [slonik](https://github.com/gajus/slonik), [postgres](https://github.com/porsager/postgres)
* 佩尔： [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python： [psycopg2](https://pypi.org/project/psycopg2/), [asyncpg](https://pypi.org/project/asyncpg/)
* 回复: [RPostgreSQL](https://github.com/tomoakin/RPostgreSQL)
*红宝石： [pg](https://github.com/ged/ruby-pg)
*锈： [rust-postgresql](https://github.com/sfackler/rust-postgres), [pgx](https://github.com/tcdi/pgx)
* 二： [luapgsql](https://github.com/arcapos/luapgsql)

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql)  - PostgreSQL 作为 AWS、Azure、DigitalOcean、Google Cloud 和 UpCloud 中的一项服务； 计划范围从每月 19 美元的单节点实例到大型高可用性设置，两周免费试用.
* [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) - 适用于 PostgreSQL 的亚马逊关系数据库服务 (RDS)
* [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/)  - Azure Database for PostgreSQL 提供完全托管、企业就绪的社区 PostgreSQL 数据库即服务. 它提供内置 HA、弹性缩放和与 Azure 生态系统的本地集成.
* [Crunchy Bridge](https://www.crunchydata.com/products/crunchy-bridge/)  - 来自 Postgres 专家的完全托管的 Postgres. 适用于所有主要云提供商：Amazon AWS、Google GCP、Microsoft Azure. 完全超级用户支持，无需锁定.
* [Database Labs](https://www.databaselabs.io) - Get a production-ready cloud PostgreSQL server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included.
* [DigitalOcean Managed Databases](https://www.digitalocean.com/products/managed-databases/)  - 完全托管的 PostgreSQL 数据库. 没有免费计划. 起价为 15 美元/月. 具有时间点恢复的每日备份. 具有自动故障转移功能的备用节点.
* [ElephantSQL](https://www.elephantsql.com/)  - 提供从用于小型项目和概念证明的共享服务器到企业级多服务器设置的数据库. 有最多 5 个数据库的免费计划，每个数据库 20 MB.
* [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/) - 完全托管的数据库服务，可让您在 Google Cloud Platform 上轻松设置、维护、管理和控制 PostgreSQL 关系数据库.
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql)  - 从免费到庞大的计划，由 PostgreSQL 专家操作. 不需要在 Heroku 上运行您的应用程序. 免费计划包括 10,000 行、20 个连接、最多两个备份，并支持 PostGIS.
* [Render Managed PostgreSQL](https://render.com/docs/databases)  - 安全、可靠且完全不干涉的托管 PostgreSQL. 所有计划均包含静态加密、自动备份和可扩展的 SSD 存储.  256MB RAM 和 1GB 存储空间的计划起价为每月 7 美元（前 90 天免费）.
* [Scaleway Managed Database](https://www.scaleway.com/en/database/)  - 完全托管的 PostgreSQL 数据库，具有 HA、扩展和自动备份，托管在欧盟. 每月 10 欧元起.

### Docker images
* [citusdata/citus](https://hub.docker.com/r/citusdata/citus/)  - 带有 citus 扩展的 Citus 官方图像. 基于官方 Postgres 容器.
* [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) - Postgres 9 上的 PostGIS 2.3.基于官方 Postgres 容器.
* [postgres](https://hub.docker.com/_/postgres/) - 官方 postgres 容器（来自 Docker）

## Resources

### Tutorials
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - 关于使用 wal-e 在 PostgreSQL 中设置连续归档的教程.
* [PG Casts](https://www.pgcasts.com) - Hashrocket 提供的每周免费 PostgreSQL 截屏视频.
* [Postgres Guide](http://postgresguide.com/) - 旨在帮助初学者和有经验的用户查找特定技巧和探索 PostgreSQL 中可用工具的指南.
* [PostgreSQL Exercises](https://pgexercises.com/) - 通过练习轻松学习 PostgreSQL 的站点.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - 非常广泛的 PostgreSQL 教程集合
* [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) - 示例 postgres 模式的集合
* [PostgreSQL Primer for Busy People](https://zaiste.net/posts/postgresql-primer-for-busy-people/) - PostgreSQL 中最常用命令的集合
* [pg-utils](https://github.com/dataegret/pg-utils) - Data Egret 的实用 DBA 工具

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) - PostgreSQL 的博客聚合服务.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](https://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) - 一组关于 PostgreSQL 很酷的特性、提示和技巧的帖子.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) - 乔希伯库斯的博客.
* [Michael Paquier's blog](https://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) - Hubert Lubaczewski 的博客.

### Articles

* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [What PostgreSQL has over other open source SQL databases: Part II](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases-part-ii/)
* [the ultimate postgres vs mysql blog post](https://di.nmfay.com/postgres-vs-mysql)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [Why use Postgres?](http://www.craigkerstiens.com/2017/04/30/why-postgres-five-years-later/)
* [Superfast CSV imports using PostgreSQL's COPY command](https://infinum.com/the-capsized-eight/superfast-csv-imports-using-postgresqls-copy)
* [Tricking Postgres into using an insane – but 200x faster – query plan](https://spacelift.io/blog/tricking-postgres-into-using-query-plan)

### Documentation
* [Wiki](https://wiki.postgresql.org/wiki/Main_Page) - 用户文档、操作方法和提示“n”技巧

### Newsletters

* [Postgres Weekly](https://postgresweekly.com/) - 包含与 PostgreSQL 相关的文章、新闻和存储库的每周时事通讯.

### Videos
* [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) - 其他相关影片
* [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) - EnterpriseDB 相关视频
* [Postgres Conference Youtube channel](https://www.youtube.com/channel/UCsJkVvxwoM7R9oRbzvUhbPQ/videos) - 会议视频
* [Scaling Postgres](https://www.scalingpostgres.com/) - Creston Jamison 的 Postgres 视频博客系列

### Community
* [Mailing lists](https://www.postgresql.org/list/)  - 用于支持、外展等的 Postgres 官方邮件列表.  Postgres 社区的主要交流渠道之一.
* [Reddit](https://www.reddit.com/r/PostgreSQL/) - 拥有超过 12000 名用户的 PostgreSQL 用户的 reddit 社区
* [Slack](https://postgres-slack.herokuapp.com/) - 拥有超过 7000 名用户的 Postgres 的 Slack 频道
* Telegram - 几个不同语言的 PostgreSQL 群组： [Russian](https://t.me/pgsql) &gt;4200人， [Brazilian Portuguese](https://t.me/postgresqlbr) &gt;2300人， [Indonesian](https://t.me/postgresql_id) ~1000人， [English](https://t.me/postgreschat) &gt;750人
* [#postgresql on Freenode](https://webchat.freenode.net/#postgresql) - Freenode 上关于 Postgres 的最受欢迎的 IRC 频道，拥有超过 1000 名用户

### Roadmaps
* [PostgreSQL Roadmap](https://roadmap.sh/postgresql-dba) - 提供 PostgreSQL 分步指南的路线图.
