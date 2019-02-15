<p>
  <br>
  <img width="300" src="https://rawgit.com/quangv/awesome-couchdb/master/logo--couch.png" alt="awesome couchdb logo">
  <br>
</p>

## Awesome CouchDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; CouchDB的策划元资源和最佳实践列表.

**[CouchDB](http://couchdb.apache.org/)**是一个面向文档的NoSQL数据库，可以同步.

欢迎提出请求.

## Contents

- [Patterns & Best Practices](#patterns--best-practices)
  - [Map/Reduce](#mapreduce)
  - [Joins](#joins)
  - [Document Versioning](#document-versioning)
- [Blogs](#blogs)
- [Docs](#docs)
- [Books](#books)
- [Videos](#videos)
- [Libraries](#libraries)
- [Community](#community)
  - [Mailing List](#mailing-list)
  - [Companies](#companies)
    - [Hosting](#hosting)
  - [Related Projects](#related-projects)
- [Misc/Technical](#misctechnical)
  - [Attachments](#attachments)
  - [Backups](#backups)
  - [CouchApps](#couchapps)
  - [Scaling](#scaling)
- [Resource Lists](#resource-lists)
- [License](#license)

## Patterns & Best Practices

- [Best Practices](http://ehealthafrica.github.io/couchdb-best-practices/) - 最佳实践，eHealth Africa.
- [Pagination strategies with PouchDB ](https://pouchdb.com/2014/04/14/pagination-strategies-with-pouchdb.html)
- [12 pro tips for better code with PouchDB](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html)
- [Linux tuning for better CouchDB performance](https://github.com/assafmo/couchdb-linux-performance)


### Map/Reduce

- [PouchDB - Secondary Indexes](https://pouchdb.com/2014/05/01/secondary-indexes-have-landed-in-pouchdb.html)
- [Cloudant - MapReduce Primer](https://cloudant.com/blog/mapreduce-from-the-basics-to-the-actually-useful/#.WIDBfRsrKUl) - 关于reduce，group，group_level的精彩介绍.
- [Using View Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#using-view-collation) - 数据连接的索引映射（发出）.
- [Views Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/collation.html) - 有关“查看整理”的更多文档.
- [Cloudant - MapReduce and the Secondary Index (Video)](https://developer.ibm.com/clouddataservices/docs/cloudant/get-started/mapreduce-and-the-secondary-index/) - 这里有关于mapReduce，二级索引和复杂键的精彩视频.
- [Cloudant - Design Documents](https://docs.cloudant.com/design_documents.html) -  Cloudant的文档也是学习CouchDB概念的重要资源.
- [Cloudant - Design Document Management](https://docs.cloudant.com/design_document_management.html) - 如何管理生产中的设计文档更改.


### Joins

- [Joins with Views](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#joins-with-views) - 必须阅读以了解为CouchDB / PouchDB进行有效连接的方法.
- [Grouping related documents together in Cloudant](https://docs.cloudant.com/transactions.html) - 利用CouchDB高可用性的方法.


### Document Versioning

- [Document Revisions (from wiki)](https://wiki.apache.org/couchdb/Document_revisions?action=show&redirect=DocumentRevisions)
- [Simple Document Versioning](http://web.archive.org/web/20100701165612/http://blog.couch.io/post/632718824/simple-document-versioning-with-couchdb)


## Blogs

- [Official Blog](https://blog.couchdb.org/)


## Docs

- [Official Docs](http://docs.couchdb.org/)
- [FAQ (old wiki)](https://wiki.apache.org/couchdb/Frequently_asked_questions) - 似乎有更多的常见问题 [new wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Frequently+Asked+Questions).

## Books

- [The Definitive Guide](http://guide.couchdb.org/) -  CouchDB的_“狗”_书.
- [List of books on the Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Books)


## Videos

- [10 Common Misconceptions](https://www.youtube.com/watch?v=BKQ9kXKoHS810) - 更多来自此的视频 [conference](http://conf.couchdb.org/).
- [The NoSQL Tapes](http://nosqltapes.com) - 讨论了CouchDB [Volume 5 - CouchDB](http://nosqltapes.com/video/hoffman-and-kocoloski-on-cloudant-and-couchdb), [Volume 8 - MapReduce](http://nosqltapes.com/video/understanding-mapreduce-with-mike-miller).
- [Scaling Out with BigCouch](http://www.oreilly.com/pub/e/1760) - 关于使用BigCouch扩展的O&#39;Reilly视频.
- [IBM - The New Builders Webinar Series](https://event.on24.com/eventRegistration/EventLobbyServlet?target=reg20.jsp&partnerref=cdc&eventid=1240121&sessionid=1&key=9E23B44802902EAD0BB2603F0434742E&regTag=35370&sourcepage=register)

## Libraries

- [Jaki](https://github.com/pandeiro/jaki) - 一个简单的ClojureScript CouchDB客户端

## Community

- [IRC](http://webchat.freenode.net/?channels=couchdb) - `irc：// irc.freenode.net / couchdb`
- [Apache CouchDB Conf](http://conf.couchdb.org/) - 很多视频链接.
- [Bylaws](http://couchdb.apache.org/bylaws.html), [Minutes](https://whimsy.apache.org/board/minutes/CouchDB.html)


### Mailing List

&gt; -dev是couchdb聊天的开发者，-user是couchdb用户聊天的地方
&gt;并且有一些串扰
&gt; -dev是适当的，如果你正在谈论对couchdb本身的更改（“开发人员”并不意味着你必须有一个提交位或任何东西）-rnewson

- [Mailing Lists](https://mail-archives.apache.org/mod_mbox/#couchdb)
- [Mailing Lists Description](http://svn.apache.org/repos/asf/couchdb/site/htdocs/community/lists.html?p=900000)
- [Grokbase](http://grokbase.com/s/couchdb) - 邮寄名单 [Stack Overflow](http://stackoverflow.com/questions/tagged/couchdb)类似的界面.


[:star2:**The** ***Amazing*** **CouchDB Committers** *and* **Project Managers** :heart_eyes_cat:](http://people.apache.org/committers-by-project.html#couchdb) 


### Companies

- [Couchbase](https://www.couchbase.com/) -  NoSQL数据库.
- [eHealth Africa](https://github.com/eHealthAfrica) -  CouchDB的大用户，看看他们 [best practices](https://github.com/eHealthAfrica/couchdb-best-practices).


#### Hosting

- [Cloudant](https://cloudant.com/) - 分布式数据库即服务（DBaaS）.
- [Smileupps](https://www.smileupps.com/) -  CouchDB托管.
- [IrisCouch](http://www.iriscouch.com/) -  Cloud CouchDB.
- [Bitnami Launchpad for Google Cloud Platform](https://bitnami.com/stack/couchdb/cloud/google) -  Google Cloud Platform上的主机CouchDB.


### Related Projects

- [PouchDB](https://pouchdb.com/) - 口袋大小的数据库.
- [Hoodie](http://hood.ie/) -  Offline First应用程序的后端.


## Misc/Technical

- [Dynamo and CouchDB Clusters](https://web.archive.org/web/20160311144130/https://cloudant.com/blog/dynamo-and-couchdb-clusters/#.WIEp4xsrKUk) - 关于使用集群扩展CouchDB的文章.
- [Google’s paper on Sawzall](http://research.google.com/archive/sawzall.html) - 异国情调减少的例子.
- [What Every Developer Should Know About CouchDB](http://www.dimagi.com/blog/what-every-developer-should-know-about-couchdb/) - 关于经验教训的文章.
- [CouchDB Maximum Database Size](http://www.nosql.se/2011/09/couchdb-maximum-database-size/)
- [NOSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [Persistent Trees in git, Clojure and CouchDB](https://eclipsesource.com/blogs/2009/12/13/persistent-trees-in-git-clojure-and-couchdb-data-structure-convergence/)

### Attachments

- [PouchDB - Attachments are overrated](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html) -  _“更新：自从撰写这篇文章以来，PouchDB中附件的稳定性和性能已经大大提高了......”_
- [Cloudant - Attachments Performance Considerations](https://docs.cloudant.com/attachments.html#performance-considerations)
- [Are attachments duplicated for each revision?](http://grokbase.com/t/couchdb/user/14a1phbzrb/are-attachments-duplicated-for-each-revision-as-well) - 关于修订版附件的邮件列表讨论.


### Backups

- [Simple CouchDB and Cloudant Backup](https://developer.ibm.com/clouddataservices/2016/03/22/simple-couchdb-and-cloudant-backup/) - 有关备份的IBM文章.
- [Cloudant Backup Guide](https://docs.cloudant.com/backup-guide.html) - 有关备份的Cloudant文档.


### CouchApps

- [List of CouchApps](https://couchapp.readthedocs.io/en/latest/user/list-of-couchapps.html)
- [Ddoc Lab](http://ddoc.me/) - 在浏览器中创建couchapps和CouchDB设计文档.


### Scaling

- [Bitnami CouchDB](https://bitnami.com/stack/couchdb) -  Bitnami可以轻松在云中运行CouchDB.


## Resource Lists

- [Official CouchDB Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Apache+CouchDB+Wiki)
- [Official CouchDB Wiki (old)](https://wiki.apache.org/couchdb/) - 有些东西还没有在新的维基上.
- [Cloudant Official Guides](https://docs.cloudant.com/guides.html) - 适用于CouchDB.
- [List of CouchDB Clients](https://cwiki.apache.org/confluence/display/COUCHDB/CouchDB+clients)
- [List of CouchDB Useful Utilities](https://cwiki.apache.org/confluence/display/COUCHDB/Useful+utilities)
- [Old Wiki's Related Projects List](https://wiki.apache.org/couchdb/Related_Projects)

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名4.0国际许可协议授权</a> .
