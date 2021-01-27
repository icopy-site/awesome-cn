<div class="github-widget" data-repo="dhamaniasad/awesome-postgres"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Postgres [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

&gt;精选的超赞清单 [PostgreSQL](https://www.postgresql.org/) 受启发的软件，库，工具和资源 [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)

[PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL)，通常只是Postgres， [object-relational database](https://en.wikipedia.org/wiki/Object-relational_database)  （ORDBMS）.  PostgreSQL是 [ACID-compliant](https://en.wikipedia.org/wiki/ACID) 和 [transactional](https://en.wikipedia.org/wiki/Transaction_processing) .  （查看更多： [wikipedia:PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL), [PostgreSQL.org](https://www.postgresql.org))

  ：elephant：欢迎捐助. 通过添加链接 [pull requests](https://github.com/dhamaniasad/awesome-postgres/pulls) 或创建一个 [issue](https://github.com/dhamaniasad/awesome-postgres/issues) 开始讨论. 请看看 [contribution guidelines](https://github.com/dhamaniasad/awesome-postgres/blob/master/CONTRIBUTING.md).



### High-Availability
* [BDR](https://github.com/2ndQuadrant/bdr) -双向复制-PostgreSQL的多主复制系统
* [Patroni](https://github.com/zalando/patroni) -带有ZooKeeper或etcd的PostgreSQL HA的模板.
* [Stolon](https://github.com/sorintlab/stolon) -基于Consul或etcd的PostgreSQL HA，具有Kubernetes集成.
* [pglookout](https://github.com/aiven/pglookout) -复制监视和故障转移守护程序.
* [repmgr](https://github.com/2ndQuadrant/repmgr) -开源工具套件，用于管理PostgreSQL服务器群集中的复制和故障转移.
* [Slony-I](https://slony.info/) -具有级联和故障转移的“主从多个从”复制系统.
* [PAF](https://github.com/ClusterLabs/PAF) -PostgreSQL自动故障转移：基于Pacemaker和Corosync的Postgres的高可用性.
* [SkyTools](https://github.com/pgq/skytools-legacy) -复制工具，包括PgQ（排队系统）和Londiste（复制系统），其管理比Slony更为简单.

### Backups
* [Barman](https://www.pgbarman.org/index.html) -2ndQuadrant提供的PostgreSQL备份和恢复管理器.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) -PostgreSQL的高级WAL文件管理工具.
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) –经过@PostgresPro改进的pg \ _arman分支，支持增量备份，副本副本备份，多线程备份和还原以及无存档命令的匿名备份.
* [pgBackRest](https://pgbackrest.org/)  -可靠的PostgreSQL备份和还原.
* [pg\_back](https://github.com/orgrim/pg_back/) -pg \ _back是一个简单的备份脚本
* [pghoard](https://github.com/aiven/pghoard) -用于云对象存储（AWS S3，Azure，Google Cloud，OpenStack Swift）的备份和还原工具.
* [wal-e](https://github.com/wal-e/wal-e) -Heroku的PostgreSQL至S3，Azure或Swift的简单连续归档.
* [wal-g](https://github.com/wal-g/wal-g)  -在Go中重写了WAL-E的后继者. 当前支持AWS（S3），Google Cloud（GCS），Azure以及OpenStack Swift，MinIO和文件系统存储的云对象存储服务. 支持块级增量备份，将备份任务卸载到备用服务器，并提供并行化和限制选项. 除了Postgres，WAL-G还可用于MySQL和MongoDB数据库.
* [pitrery](https://dalibo.github.io/pitrery/) -pitrery是一组Bash脚本，用于管理PostgreSQL的时间点恢复（PITR）备份.

### GUI
* [Adminer](https://www.adminer.org/) -用PHP编写的功能齐全的数据库管理工具.
* [Beekeeper Studio](https://www.beekeeperstudio.io)  -具有现代UI和强大的Postgres支持的免费和开源SQL客户端. 跨平台.
* [DataGrip](https://www.jetbrains.com/datagrip/) -具有高级工具集和良好跨平台经验的IDE（商业软件）.
* [Datazenit](https://datazenit.com/) -基于Web的PostgreSQL GUI（商业软件）.
* [DataRow](https://www.datarow.com/) -适用于Amazon Redshift的跨平台SQL客户端：简单，轻松，可扩展.
* [DBeaver](https://dbeaver.io/) -具有对PostgreSQL的出色支持的Universal Database Manager.
* [dbglass](http://dbglass.web-pal.com) -使用Electron构建的PostgreSQL跨平台桌面客户端.
* [Holistics](https://www.holistics.io/) -具有强大的PostgreSQL支持的在线跨平台数据库管理工具和SQL查询报告GUI（商业软件）.
* [JackDB](https://www.jackdb.com/) -基于Web的SQL查询界面（商业软件）.
* [Metabase](https://www.metabase.com/) -PostgreSQL的简单仪表板，图表和查询工具.
* [Numeracy](https://numeracy.co/) -带有PostgreSQL（商业软件）图表和仪表板的快速SQL编辑器.
* [OmniDB](https://omnidb.org/en/) -开源协作环境
用于数据库管理
* [pgAdmin](https://www.pgadmin.org/) -PostgreSQL管理和管理GUI.
* [pgModeler](https://pgmodeler.io/) -pgModeler是开源的PostgreSQL数据库建模器.
* [pgweb](https://github.com/sosedoff/pgweb) -用Go编写的基于Web的PostgreSQL数据库浏览器.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) -PostgreSQL的首要基于Web的管理工具.
* [Postbird](https://github.com/Paxa/postbird) -适用于macOS的PostgreSQL客户端.
* [PostgresCompare](https://www.postgrescompare.com) -跨平台的数据库比较和部署工具（商业软件）.
* [Postico](https://eggerapps.at/postico/) -适用于macOS（商业软件）的现代PostgreSQL客户端.
* [PSequel](http://www.psequel.com/) -简洁易用的界面，可快速执行常见的PostgreSQL任务（商业软件）.
* [SQL Tabs](http://www.sqltabs.com/) -用JS编写的PostgreSQL跨平台桌面客户端.
* [SQLPro for Postgres](http://macpostgresclient.com/) -适用于macOS（商业软件）的简单，功能强大的PostgreSQL管理器.
* [temBoard](https://github.com/dalibo/temboard) -基于Web的PostgreSQL GUI和监视.
* [TablePlus](https://tableplus.com/)  -本机应用程序，可让您编辑数据库和结构. 确保高端安全性（商业软件）.
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) -跨平台数据库管理工具（免费/商业）

### Distributions
* [Postgres.app](https://postgresapp.com/) -在macOS上使用PostgreSQL的最简单方法.
* [PostgreSql.Binaries.Lite](https://github.com/mihasic/PostgreSql.Binaries.Lite)  -PostgreSQL数据库的Windows二进制文件的最小集. 也可以通过NuGet使用.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) -具有自动完成功能和语法突出显示功能的Postgres CLI
* [pgsh](https://github.com/sastraxi/pgsh) -像Git一样分支PostgreSQL数据库
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) -内置的PostgreSQL CLI客户端
* [psql2csv](https://github.com/fphilipe/psql2csv) -在psql中运行查询并将结果输出为CSV
* [nancy](https://gitlab.com/postgres-ai/nancy) -Nancy CLI是一种统一的方式，可以在云或本地环境中管理自动化数据库实验
* [schemaspy](https://github.com/schemaspy/schemaspy) -SchemaSpy是与Java JDBC兼容的工具，用于将数据库生成为HTML文档，包括实体关系图

### Server
* [Postgres-XL](https://www.postgres-xl.org/) -可伸缩的基于PostgreSQL的开源数据库集群.
* [AgensGraph](https://bitnine.net/) -基于PostgreSQL的强大图形数据库.
* [Greenplum Database](https://github.com/greenplum-db/gpdb) -PostgreSQL的开源分支，用于大数据量.

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity)  -check \ _pgactivity旨在监视Nagios的PostgreSQL集群. 它提供了许多选项来衡量和监视有用的性能指标.
* [Check\_postgres](https://github.com/bucardo/check_postgres) -Nagios check \ _postgres插件，用于检查PostgreSQL数据库的状态.
* [Instrumental](https://github.com/Instrumental/instrumentald) -实时性能监控，包括 [pre-made graphs](https://instrumentalapp.com/docs/instrumentald/postgresql#suggested-graphs) 易于设置（商业软件）
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) -用于Zabbix的综合PostgreSQL监视模块.
* [PMM](https://github.com/percona/pmm) -Percona监视和管理（PMM）是一个免费和开源的平台，用于监视和管理PostgreSQL，MySQL和MongoDB.
* [Pome](https://github.com/rach/pome) - Pome stands for PostgreSQL Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database.
* [pgmetrics](https://pgmetrics.io/) -pgmetrics是一种开放源代码，零依赖，单二进制工具，可以从正在运行的PostgreSQL服务器中收集大量信息和统计信息，并以易于阅读的文本格式显示或将其导出为JSON和CSV进行脚本编写.
* [pg\_view](https://github.com/zalando/pg_view) -开源命令行工具，可显示全局系统统计信息，每个分区的信息，内存统计信息和其他信息.
* [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) -灵活且易于上手的PostgreSQL指标监控器，专注于Grafana仪表板.
* [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) -在PostgreSQL上进行基准测试.
* [opm.io](http://opm.io)  -Open PostgreSQL Monitoring是一个免费软件套件，旨在帮助您管理PostgreSQL服务器. 它可以收集统计信息，显示仪表板并在出现问题时发送警告.
* [okmeter.io](https://okmeter.io/pg)  -基于商业SaaS代理的监视，带有非常详细的PostgreSQL插件. 它会自动收集100项统计信息，在各个方面显示仪表板，并在出现问题时发送警报（商业软件）.

### Extensions
* [Citus](https://github.com/citusdata/citus) -可扩展的PostgreSQL集群，用于实时工作负载.
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) -用于PostgreSQL分析的柱状存储.
* [cyanaudit](https://pgxn.org/dist/cyanaudit/) -Cyan Audit逐列提供所有DML活动的数据库内日志记录.
* [pg_cron](https://github.com/citusdata/pg_cron) -在PostgreSQL中运行定期作业.
* [pglogical](https://github.com/2ndQuadrant/pglogical) -提供逻辑流复制的扩展.
* [pg\_partman](https://github.com/pgpartman/pg_partman) -PostgreSQL的分区管理扩展.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) -PostgreSQL节点集群的Paxos和基于Paxos的表复制的基本实现.
* [pg\_shard](https://github.com/citusdata/pg_shard) -扩展以扩展实时读取和写入.
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) -扩展以将CPU密集型工作负载卸载到GPU.
* [pgxn](https://pgxn.org/) PostgreSQL扩展网络-许多开源PostgreSQL扩展的集中分发点
* [PipelineDB](https://www.confluent.io/blog/pipelinedb-team-joins-confluent/) -PostgreSQL扩展，可在流上连续运行SQL查询，并将结果增量存储在表中.
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) -允许检查plpgsql源代码的扩展.
* [PostGIS](http://postgis.net/) -PostgreSQL的空间和地理对象.
* [PG\_Themis](https://github.com/cossacklabs/pg_themis) -Postgres绑定作为加密库Themis的扩展，在PgSQL方面提供了各种安全服务.
* [zomboDB](https://github.com/zombodb/zombodb) -通过使用由Elasticsearch支持的索引可以进行有效的全文本搜索的扩展.
* [pgMemento](https://github.com/pgMemento/pgMemento) -使用PL / pgSQL编写的触发器和服务器端函数为PostgreSQL数据库中的数据提供审计跟踪.
* [TimescaleDB](https://www.timescale.com/) -与Postgres完全兼容的开源时间序列数据库，作为扩展分发
* [pgTAP](https://pgtap.org/) -Postgres的数据库测试框架
* [HypoPG](https://github.com/HypoPG/hypopg) -HypoPG提供了假设/虚拟索引功能.
* [pgRouting](https://github.com/pgRouting/pgrouting) -pgRouting扩展了PostGIS / PostgreSQL地理空间数据库，以提供地理空间路由和其他网络分析功能.

### Optimization
* [pg_flame](https://github.com/mgartner/pg_flame) -用于查询计划的火焰图生成器.
* [PgHero](https://github.com/ankane/pghero) -PostgreSQL见解变得容易.
* [pgMustard](https://www.pgmustard.com/) -现代化的用户界面
针对“ EXPLAIN”的说明，还提供了性能提示（商业软件）.
* [pgtune](https://github.com/gregs1104/pgtune/) -PostgreSQL配置向导.
* [pgtune](https://github.com/le0pard/pgtune) -PostgreSQL配置向导的在线版本.
* [pgconfig.org](https://github.com/sebastianwebber/pgconfig) -PostgreSQL在线配置工具（也基于pgtune）.
* [PoWA](https://powa.readthedocs.io/en/latest/) -PostgreSQL Workload Analyzer收集性能统计信息并提供实时图表，以帮助监视和调整PostgreSQL服务器.
* [pg_web_stats](https://github.com/kirs/pg_web_stats) -用于查看pg_stat_statements的Web UI.
* [TimescaleDB Tune](https://github.com/timescale/timescaledb-tune) -一种程序，用于根据主机的资源（例如内存和CPU数量）调整TimescaleDB数据库以使其发挥最佳性能.

### Utilities
* [apgdiff](https://www.apgdiff.com/) -比较两个数据库转储文件，并使用DDL语句创建输出，这些语句可用于将旧数据库模式更新为新的数据库模式.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) -ERAlchemy从数据库生成实体关系（ER）图.
* [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) -具有细粒度访问控制的Postgres上快速，即时的实时GraphQL API刷新数据库事件.
* [ldap2pg](https://github.com/dalibo/ldap2pg) -从YML和LDAP同步角色和特权.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) -Lanyrd的MySQL到PostgreSQL的转换脚本.
* [ora2pg](http://ora2pg.darold.net) -Perl模块，用于将Oracle数据库模式导出到PostgreSQL兼容模式.
* [pg\_activity](https://github.com/dalibo/pg_activity) -顶部类似PostgreSQL服务器活动监视的应用程序.
* [pg-formatter](https://github.com/gajus/pg-formatter) -PostgreSQL SQL语法美化器（Node.js）.
* [pganalyze](https://pganalyze.com) -PostgreSQL性能监控（商业软件）.
* [pgbadger](https://github.com/darold/pgbadger) -快速的PostgreSQL日志分析器.
* [PgBouncer](http://www.pgbouncer.org/) -PostgreSQL的轻量级连接池.
* [pgCenter](https://github.com/lesovsky/pgcenter) -为各种统计信息，管理任务，重新加载服务，查看日志文件以及取消或终止数据库后端提供方便的界面.
* [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) -从MySQL到PostgreSQL的实时副本，具有可选的类型，可覆盖迁移和迁移功能.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) -将数据从PostgreSQL导出为不同的数据格式.
* [pg_docs_bot](https://github.com/mchristofides/pg_docs_bot/) -用于将PostgreSQL文档链接重定向到当前版本的浏览器扩展.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) -将CSV和JSON导入PostgreSQL的简单方法.
* [PGInsight](http://pginsight.io/) -CLI工具，可轻松深入PostgreSQL数据库.
* [pg_insights](https://github.com/lob/pg_insights) -方便的SQL监视Postgres数据库运行状况.
* [pgloader](https://github.com/dimitri/pgloader) -使用COPY流协议将数据加载到PostgreSQL中，并使用单独的线程进行读写数据.
* [pgpool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) -中间件，提供连接池，复制，负载平衡和限制超连接.
* [pgsync](https://github.com/ankane/pgsync) -将PostgreSQL数据同步到本地计算机的工具.
* [PGXN client](https://github.com/pgxn/pgxnclient) -与PostgreSQL扩展网络交互的命令行工具
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) -提取并提供PostgreSQL数据库指标的工具.
* [PostgREST](https://github.com/PostgREST/postgrest) -从任何现有PostgreSQL数据库提供完全RESTful API.
* [pREST](https://github.com/prest/prest) -从任何PostgreSQL数据库（Golang）提供RESTful API
* [PostGraphile](https://github.com/graphile/postgraphile) -PostgreSQL数据库的即时GraphQL API或GraphQL模式
* [yoke](https://github.com/nanopack/yoke) -具有自动故障转移和自动群集恢复功能的PostgreSQL高可用性群集.
* [pglistend](https://github.com/kabirbaidhya/pglistend) -一个轻量级的PostgresSQL`LISTEN` /`NOTIFY`守护进程，它建立在`node-postgres`之上.
* [ZSON](https://github.com/postgrespro/zson) -用于透明JSONB压缩的PostgreSQL扩展
* [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) -这是PostgreSQL的高速数据加载实用程序.
* [pg_migrate](https://github.com/jwdeitch/pg_migrate) -管理PostgreSQL代码库并简化VCS.
* [sqitch](https://github.com/sqitchers/sqitch) -用于管理版本化架构部署的工具
* [pgmigrate](https://github.com/yandex/pgmigrate) -Yandex开发的CLI工具，用于发展模式迁移.
* [pgcmp](https://github.com/cbbrowne/pgcmp) -比较数据库架构的工具，具有接受某些持久性差异的能力
* [pg-differ](https://github.com/multum/pg-differ) -易于初始化/更新PostgreSQL表结构的工具，可替代迁移（Node.js）.
* [sqlcheck](https://github.com/jarulraj/sqlcheck)  -自动检测常见的SQL反模式. 这种反模式通常会使查询变慢. 因此，解决这些问题将有助于加快查询速度.
* [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) -新一代诊断工具，可让用户收集对Postgres数据库运行状况的深入分析.
* [ScaffoldHub.io](https://scaffoldhub.io) -使用Angular，Vue或React（商业软件）生成全栈PostgreSQL应用. 

### Language bindings
*普通Lisp： [Postmodern](https://github.com/marijnh/Postmodern)
* Clojure： [clj-postgresql](https://github.com/remodoy/clj-postgresql)
*药剂： [postgrex](https://github.com/elixir-ecto/postgrex)
* 走： [pq](https://github.com/lib/pq), [pgx](https://github.com/jackc/pgx)
* Haskell： [postgresql-simple](http://hackage.haskell.org/package/postgresql-simple)
* Java： [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* .Net / .Net核心： [Npgsql](https://github.com/npgsql/npgsql)
*节点： [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise), [pogi](https://github.com/holdfenytolvaj/pogi), [slonik](https://github.com/gajus/slonik), [postgres](https://github.com/porsager/postgres)
* Perl： [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm)
* PHP： [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python： [psycopg2](https://pypi.org/project/psycopg2/), [asyncpg](https://pypi.org/project/asyncpg/)
*红宝石： [pg](https://github.com/ged/ruby-pg)
*铁锈： [rust-postgresql](https://github.com/sfackler/rust-postgres)
*月球： [luapgsql](https://github.com/arcapos/luapgsql)

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql)  -PostgreSQL作为AWS，Azure，DigitalOcean，Google Cloud和UpCloud中的服务； 计划的范围从每月$ 19的单节点实例到大型的高可用性设置，免费试用两周.
* [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) -适用于PostgreSQL的Amazon Relational Database Service（RDS）
* [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/)  -PostgreSQL的Azure数据库提供了完全托管的企业就绪社区PostgreSQL数据库即服务. 它提供内置的HA，弹性扩展和与Azure生态系统的本机集成.
* [Citus Cloud](https://www.citusdata.com/product/cloud) -生产级扩展了PostgreSQL即服务，从而支持实时工作负载并分片多租户应用程序.
* [Compose](https://www.compose.com/databases/postgresql)  -PostgreSQL作为AWS，Google Cloud Platform和IBM Cloud中的服务； 计划价格从每月17.5美元/月用于1GB存储，到此后可扩展至12美元/ GB. 免费试用30天.
* [Database Labs](https://www.databaselabs.io) -数分钟内即可获得生产就绪的云PostgreSQL服务器，每月20美元起，包括备份，监控，补丁程序和24/7全天候技术支持.
* [DigitalOcean Managed Databases](https://www.digitalocean.com/products/managed-databases/)  -完全托管的PostgreSQL数据库. 没有免费计划. 最低$ 15 /月. 具有时间点恢复功能的每日备份. 具有自动故障转移功能的备用节点.
* [ElephantSQL](https://www.elephantsql.com/)  -提供数据库，从用于较小项目的共享服务器到概念验证，再到企业级多服务器设置. 有免费计划，最多可容纳5个DB，每个DB 20 MB.
* [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/) -完全托管的数据库服务，可轻松在Google Cloud Platform上设置，维护，管理和管理PostgreSQL关系数据库.
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql)  -由PostgreSQL专家操作的计划从免费到庞大. 不需要在Heroku上运行您的应用程序. 免费计划包括10,000行，20个连接，最多两个备份，并具有PostGIS支持.
* [Scaleway Managed Database](https://www.scaleway.com/en/database/)  -在欧洲托管的具有HA，可伸缩性和自动备份的完全托管的PostgreSQL数据库. 每月10欧元起.

### Docker images
* [citusdata/citus](https://hub.docker.com/r/citusdata/citus/)  -具有citus扩展名的Citus官方图片. 基于官方的Postgres容器.
* [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) -Postgres 9上的PostGIS 2.3.基于官方的Postgres容器.
* [postgres](https://hub.docker.com/_/postgres/) -官方postgres容器（来自Docker）

## Resources

### Tutorials
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) -有关使用wal-e在PostgreSQL中设置连续归档的教程.
* [PG Casts](https://www.pgcasts.com) -Hashrocket每周提供免费的PostgreSQL屏幕录像.
* [Postgres Guide](http://postgresguide.com/) -该指南旨在帮助初学者和有经验的用户找到特定的技巧并探索PostgreSQL中可用的工具.
* [PostgreSQL Exercises](https://pgexercises.com/) -通过练习使学习PostgreSQL变得容易的站点.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) -PostgreSQL上的教程非常丰富
* [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) -示例postgres模式的集合
* [PostgreSQL Primer for Busy People](https://zaiste.net/posts/postgresql-primer-for-busy-people/) -PostgreSQL中使用的最常用命令的集合
* [pg-utils](https://github.com/dataegret/pg-utils) - Useful DBA tools by Data Egret

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) -PostgreSQL的博客聚合服务.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](https://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) -PostgreSQL酷功能，技巧和窍门上的一组帖子.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) -Josh Berkus的博客.
* [Michael Paquier's blog](https://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) -Hubert Lubaczewski的博客.

### Articles

* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [What PostgreSQL has over other open source SQL databases: Part II](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases-part-ii/)
* [the ultimate postgres vs mysql blog post](https://di.nmfay.com/postgres-vs-mysql)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [Why use Postgres?](http://www.craigkerstiens.com/2017/04/30/why-postgres-five-years-later/)
* [Superfast CSV imports using PostgreSQL's COPY command](https://infinum.com/the-capsized-eight/superfast-csv-imports-using-postgresqls-copy)

### Documentation
* [Wiki](https://wiki.postgresql.org/wiki/Main_Page) -用户文档，操作方法和提示“ n”的技巧

### Newsletters

* [Postgres Weekly](https://postgresweekly.com/) -每周通讯，其中包含与PostgreSQL有关的文章，新闻和回购.

### Videos
* [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) -其他相关视频
* [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) -与EnterpriseDB相关的视频
* [Postgres Conference Youtube channel](https://www.youtube.com/channel/UCsJkVvxwoM7R9oRbzvUhbPQ/videos) -会议视频
* [Scaling Postgres](https://www.scalingpostgres.com/) -Cregre Jamison撰写的Postgres视频博客系列

### Community
* [Mailing lists](https://www.postgresql.org/list/)  -Postgres的官方邮件列表，以获取支持，扩展等信息.  Postgres社区中的主要沟通渠道之一.
* [Reddit](https://www.reddit.com/r/PostgreSQL/) -PostgreSQL用户超过12000的reddit社区
* [Slack](https://postgres-slack.herokuapp.com/) -拥有7000多个用户的Postgres的松弛渠道
*电报-PostgreSQL的几个组，使用不同的语言： [Russian](https://t.me/pgsql) &gt; 4200人， [Brazilian Portuguese](https://t.me/postgresqlbr) &gt; 2300人， [Indonesian](https://t.me/postgresql_id) 约1000人 [English](https://t.me/postgreschat) &gt; 750人
* [#postgresql on Freenode](https://webchat.freenode.net/#postgresql) -Freenode上有关Postgres的最受欢迎的IRC频道，拥有1000多个用户
