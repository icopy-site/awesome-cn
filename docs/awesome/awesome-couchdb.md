<div class="github-widget" data-repo="quangv/awesome-couchdb"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<p>
  <br>
  <img width="300" src="https://rawgit.com/quangv/awesome-couchdb/master/logo--couch.png" alt="awesome couchdb logo">
  <br>
</p>

## Awesome CouchDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

&gt; CouchDB 的精选元资源和最佳实践列表.

**[CouchDB](http://couchdb.apache.org/)** 是一个面向文档的同步 NoSQL 数据库.

欢迎请求请求.


## News & Blog Posts

- [MiniCouchDB in Rust](https://www.garrensmith.com/blogs/mini-couch-hack-week)
- [The Road to CouchDB 3.0: Prepare for 4.0](https://blog.couchdb.org/2020/02/26/the-road-to-couchdb-3-0-prepare-for-4-0/) _(02-26-2020)_

## Patterns & Best Practices

- [Best Practices](http://ehealthafrica.github.io/couchdb-best-practices/) - 最佳实践，非洲电子卫生保健.
- [Pagination strategies with PouchDB ](https://pouchdb.com/2014/04/14/pagination-strategies-with-pouchdb.html)
- [12 pro tips for better code with PouchDB](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html)
- [Linux tuning for better CouchDB performance](https://github.com/assafmo/couchdb-linux-performance)


### Map/Reduce

- [PouchDB - Secondary Indexes](https://pouchdb.com/2014/05/01/secondary-indexes-have-landed-in-pouchdb.html)
- [Cloudant - MapReduce Primer](https://cloudant.com/blog/mapreduce-from-the-basics-to-the-actually-useful/#.WIDBfRsrKUl) -关于reduce、group、group_level的精彩介绍.
- [Using View Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#using-view-collation) - 数据连接的索引映射（发射）.
- [Views Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/collation.html) - 有关“查看整理”的更多文档.
- [Cloudant - MapReduce and the Secondary Index (Video)](https://developer.ibm.com/clouddataservices/docs/cloudant/get-started/mapreduce-and-the-secondary-index/) - 这里有关于 mapReduce、二级索引和复杂键的精彩视频.
- [Cloudant - Design Documents](https://docs.cloudant.com/design_documents.html) - Cloudant 的文档也是学习 CouchDB 概念的重要资源.
- [Cloudant - Design Document Management](https://docs.cloudant.com/design_document_management.html) - 如何管理生产中的设计文档更改.


### Joins

- [Joins with Views](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#joins-with-views) - 必须阅读以了解对 CouchDB/PouchDB 进行高效连接的方法.
- [Grouping related documents together in Cloudant](https://docs.cloudant.com/transactions.html) - 一种利用 CouchDB 高可用性特性的方法.


### Document Versioning

- [Document Revisions (from wiki)](https://wiki.apache.org/couchdb/Document_revisions?action=show&redirect=DocumentRevisions)
- [Simple Document Versioning](http://web.archive.org/web/20100701165612/http://blog.couch.io/post/632718824/simple-document-versioning-with-couchdb)


## Blogs

- [Official Blog](https://blog.couchdb.org/)


## Docs

- [Official Docs](http://docs.couchdb.org/)
- [FAQ (old wiki)](https://wiki.apache.org/couchdb/Frequently_asked_questions) - 似乎有更多的常见问题解答 [new wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Frequently+Asked+Questions).

## Books

- [The Definitive Guide](http://guide.couchdb.org/) - CouchDB 的 _“狗”_ 书.
- [List of books on the Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Books)


## Videos

- [10 Common Misconceptions](https://www.youtube.com/watch?v=BKQ9kXKoHS810) - 来自此的更多视频 [conference](http://conf.couchdb.org/).
- [The NoSQL Tapes](http://nosqltapes.com) - 讨论了 CouchDB [Volume 5 - CouchDB](http://nosqltapes.com/video/hoffman-and-kocoloski-on-cloudant-and-couchdb), [Volume 8 - MapReduce](http://nosqltapes.com/video/understanding-mapreduce-with-mike-miller).
- [Scaling Out with BigCouch](http://www.oreilly.com/pub/e/1760) - O&#39;Reilly 使用 BigCouch 进​​行横向扩展的视频.
- [IBM - The New Builders Webinar Series](https://event.on24.com/eventRegistration/EventLobbyServlet?target=reg20.jsp&partnerref=cdc&eventid=1240121&sessionid=1&key=9E23B44802902EAD0BB2603F0434742E&regTag=35370&sourcepage=register)

## Libraries

- [Jaki](https://github.com/pandeiro/jaki) - 一个简单的 ClojureScript CouchDB 客户端

## Community

- [IRC](http://webchat.freenode.net/?channels=couchdb) - `irc://irc.freenode.net/couchdb`
- [Apache CouchDB Conf](http://conf.couchdb.org/) - 大量视频链接.
- [Bylaws](http://couchdb.apache.org/bylaws.html), [Minutes](https://whimsy.apache.org/board/minutes/CouchDB.html)


### Mailing List

&gt; -dev 是 couchdb 的开发者聊天的地方，-user 是 couchdb 的用户聊天的地方
&gt; 还有一些串扰
&gt; 如果您谈论的是对 couchdb 本身的更改，则 -dev 是合适的（“开发人员”并不意味着您必须提交位或任何内容）-rnewson

- [Mailing Lists](https://mail-archives.apache.org/mod_mbox/#couchdb)
- [Mailing Lists Description](http://svn.apache.org/repos/asf/couchdb/site/htdocs/community/lists.html?p=900000)
- [Grokbase](http://grokbase.com/s/couchdb) - 邮件列表 [Stack Overflow](http://stackoverflow.com/questions/tagged/couchdb)- 类似的界面.


[:star2:**The** ***Amazing*** **CouchDB Committers** *and* **Project Managers** :heart_eyes_cat:](http://people.apache.org/committers-by-project.html#couchdb) 


### Companies

- [eHealth Africa](https://github.com/eHealthAfrica) - CouchDB 的大用户，看看他们 [best practices](https://github.com/eHealthAfrica/couchdb-best-practices).


#### Hosting

- [Cloudant](https://cloudant.com/) - 分布式数据库即服务 (DBaaS).
- [Smileupps](https://www.smileupps.com/) - CouchDB 托管.
- [Bitnami Launchpad for Google Cloud Platform](https://bitnami.com/stack/couchdb/cloud/google) - 在 Google Cloud Platform 上托管 CouchDB.


### Related Projects

- [PouchDB](https://pouchdb.com/) - 袖珍型数据库.
- [FoundationDB](https://www.foundationdb.org/) - CouchDB 4.0 将使用 FoundationDB.
- [Hoodie](http://hood.ie/) - 离线优先应用程序的后端.
- [Couchbase](https://www.couchbase.com/) - NoSQL 数据库.
  - [Migrating from Apache CouchDB](https://docs.couchbase.com/server/current/install/migrate-couchdb.html) - CouchDB 和 CouchBase 的比较
- [RxDB](https://rxdb.info/)  - 用于 JavaScript 应用程序的 NoSQL 数据库.  RxDB 提供了用于与任何 CouchDB 兼容端点以及自定义 GraphQL 端点进行实时复制的模块.


## Misc/Technical

- [Dynamo and CouchDB Clusters](https://web.archive.org/web/20160311144130/https://cloudant.com/blog/dynamo-and-couchdb-clusters/#.WIEp4xsrKUk) - 关于使用集群扩展 CouchDB 的文章.
- [Google’s paper on Sawzall](http://research.google.com/archive/sawzall.html) - 异国情调的减少例子.
- [What Every Developer Should Know About CouchDB](http://www.dimagi.com/blog/what-every-developer-should-know-about-couchdb/) - 关于经验教训的文章.
- [CouchDB Maximum Database Size](http://www.nosql.se/2011/09/couchdb-maximum-database-size/)
- [NOSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [Persistent Trees in git, Clojure and CouchDB](https://eclipsesource.com/blogs/2009/12/13/persistent-trees-in-git-clojure-and-couchdb-data-structure-convergence/)
- [CouchDB - JSON and B-trees and REST, oh my!](https://pozorvlak.livejournal.com/176385.html)

### Attachments

- [PouchDB - Attachments are overrated](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html) - _&quot;更新：自从写这篇文章以来，PouchDB中附件的稳定性和性能有了很大的提升....&quot;_
- [Cloudant - Attachments Performance Considerations](https://docs.cloudant.com/attachments.html#performance-considerations)
- [Are attachments duplicated for each revision?](http://grokbase.com/t/couchdb/user/14a1phbzrb/are-attachments-duplicated-for-each-revision-as-well) - 关于跨版本附件的邮件列表讨论.


### Backups

- [Simple CouchDB and Cloudant Backup](https://developer.ibm.com/clouddataservices/2016/03/22/simple-couchdb-and-cloudant-backup/) - 关于 IBM 的关于备份的文章.
- [Cloudant Backup Guide](https://docs.cloudant.com/backup-guide.html) - 关于备份的 Cloudant 文档.


### CouchApps

- [List of CouchApps](https://couchapp.readthedocs.io/en/latest/user/list-of-couchapps.html)
- [Ddoc Lab](http://ddoc.me/) - 直接在浏览器中创建 couchapps 和 CouchDB 设计文档.


### Scaling

- [Bitnami CouchDB](https://bitnami.com/stack/couchdb) - Bitnami 使在云中运行 CouchDB 变得容易.


## Resource Lists

- [Official CouchDB Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Apache+CouchDB+Wiki)
- [Official CouchDB Wiki (old)](https://wiki.apache.org/couchdb/) - 有些东西还没有出现在新的维基上.
- [Cloudant Official Guides](https://docs.cloudant.com/guides.html) - 适用于 CouchDB.
- [List of CouchDB Clients](https://cwiki.apache.org/confluence/display/COUCHDB/CouchDB+clients)
- [List of CouchDB Useful Utilities](https://cwiki.apache.org/confluence/display/COUCHDB/Useful+utilities)
- [Old Wiki's Related Projects List](https://wiki.apache.org/couchdb/Related_Projects)

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /><br />本作品已根据<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名 4.0 国际许可协议获得许可</a>.
