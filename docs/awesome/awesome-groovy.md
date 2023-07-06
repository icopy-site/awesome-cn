<div class="github-widget" data-repo="kdabir/awesome-groovy"></div>
很棒的格罗维 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==============

很棒的 groovy 库、框架和资源的精选列表. 受到许多其他很棒的-*存储库的启发. 这个很棒的合集也可以在 [Groovy.ZEEF.com](https://groovy.zeef.com/kunal.dabir).



## Build tools, setup and CI
* [Gradle](https://www.gradle.org/) - 强大的 JVM 构建系统
* [GMavenPlus](https://github.com/groovy/GMavenPlus) - 重写 GMaven，Groovy 的 Maven 插件
* [SDKMAN](https://sdkman.io) - 软件开发套件管理器（以前称为 GVM）
* [skeletal](https://github.com/cbmarcum/skeletal) - 一个使用打包模板的简单项目创建工具（Lazybones 的后继者）
* [Lazybones](https://github.com/pledbrook/lazybones) - 一个简单的项目创建工具，使用打包的项目模板.
* [Jenkins job-dsl-plugin](https://github.com/jenkinsci/job-dsl-plugin) - Jenkins Jobs 的 Groovy DSL
* [travis-groovy](https://github.com/kdabir/travis-groovy) - 在 travis-ci 上执行 groovy 脚本
* [Android Groovy Shell](https://play.google.com/store/apps/details?id=com.tambapps.android.grooidshell) - 直接在智能手机上编码并执行 Groovy 脚本

## IDE and Editor Support
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) - Java 平台最智能的 IDE
* [Groovy Web Console](http://groovyconsole.appspot.com) - 在线 Groovy 控制台
* [LightTable Plugin](https://github.com/rundis/LightTable-Groovy) - LightTable 支持
* [SpaceVim](https://spacevim.org/layers/lang/groovy/) - SpaceVim `lang#groovy` layer
* [Sublime Text 2/3](https://gist.github.com/kdabir/2203530) - 从 Sublime Text 运行 groovy 脚本

## Web Frameworks

* [Grails](https://github.com/grails/grails) - 一个基于Groovy语言的强大的Web应用程序框架
* [Micronaut](http://micronaut.io/) - Grails团队创建的全新微服务框架
* [Spring-Boot](https://projects.spring.io/spring-boot)  - Spring Boot 可以轻松创建独立的、生产级的基于 Spring 的应用程序，您可以“直接运行”. 使用 Groovy 作为您的编码语言.
* [Gaelyk](https://github.com/gaelyk/gaelyk) - 用于 Google App Engine Java 的轻量级 Groovy 工具包
* [Glide](https://github.com/kdabir/glide) - 在 Google App Engine 上快速创建出色的应用程序
* [Ratpack](https://github.com/ratpack/ratpack) - JVM Web 应用程序的工具包
* [gServ](https://github.com/javaConductor/gserv) - Groovy 工具包，用于创建基于 SPA 和 REST 的微服务，无需容器（Tomcat、JBoss 等）.

## Database
* [GORM](https://gorm.grails.org) - Grails ORM，但可以在没有 Grails 的情况下独立使用
* [Gmongo](https://github.com/poiati/gmongo) - mongodb Java 驱动程序的 Groovy 包装器
* [Gstorm](https://github.com/kdabir/gstorm) - 一个简单的 ORM，用于在 groovy 脚本中使用简单的数据库和 CSV 文件
* [Tayra](https://github.com/EqualExperts/Tayra) - MongoDB增量备份工具
* [Groovy-liquibase](https://github.com/tlberglund/groovy-liquibase) - Liquibase 的另一个 Groovy DSL
* [Effigy](https://github.com/cjstehno/effigy) - Groovy 注解驱动的 JDBC 行映射框架（废弃）
* [elasticsearch-groovy](https://github.com/elastic/elasticsearch-groovy) - Elasticsearch Groovy 客户端

## Rich Application

* [Griffon](http://griffon-framework.org/) - Griffon 是一个用于在 JVM 中开发桌面应用程序的应用程序框架
* [GroovyFx](http://groovyfx.org/) - GroovyFX 为 JavaFX 2.0 提供 Groovy 绑定.

## HTTP
* [Http-Builder](https://github.com/jgritman/httpbuilder) - HTTPBuilder 是从 JVM 操作基于 HTTP 的资源的最简单方法
* [HTTP Builder NG](https://github.com/http-builder-ng/http-builder-ng) - HTTP Builder NG 是一种用于发出 http 请求的现代 Groovy DSL.
* [HTTP Builder NG Gradle Plugin](https://github.com/http-builder-ng/gradle-http-plugin) - Gradle 插件在 Gradle 构建配置中提供 HTTP Builder NG 支持.
* [AsyncRestClient](https://github.com/eginez/AsyncRestClient) - 将 RESTClient 的强大功能与 RxGroovy 相结合以进行异步 http 调用
* [Groovy-wslite](https://github.com/jwagenleitner/groovy-wslite) - Groovy 的轻量级 SOAP 和 REST Web 服务客户端
* [Hyperpoet](https://github.com/tambapps/hyperpoet) - 易于使用且可定制的 Groovy HTTP 客户端

## Testing
* [Spock](https://github.com/spockframework/spock) - 企业级测试和规范框架.
* [Geb](https://github.com/geb/geb) - 非常 Groovy 浏览器自动化
* [Betamax](https://github.com/betamaxteam/betamax) - Betamax 是一个用于在测试中模拟外部 HTTP 资源（例如 Web 服务和 REST API）的工具.
* [HTTP Mock Server](https://github.com/TouK/http-mock-server) - HTTP Mock Server 允许使用常规闭包来模拟 HTTP 请求.
* [Ersatz Mock Server](https://github.com/cjstehno/ersatz) - 一个简单而富有表现力的模拟 HTTP 服务器，用于通过可配置的响应测试客户端代码.
* [Dru](https://agorapulse.github.io/dru/) - 数据重建实用程序从外部源 JSON、YML 加载数据，以便轻松测试 GORM、DynamoDB 或普通 POJO.
* [Gru](https://agorapulse.github.io/gru/) - Groovy HTTP 测试框架，用于为任何 HTTP 后端运行集成和半集成测试，并提供 Grails 和 Spring MVC 的本机单元测试支持.

## Concurrency
* [GPars](https://github.com/GPars/GPars) - JVM 的 GPars 并发和并行框架
* [RxGroovy](https://github.com/ReactiveX/RxGroovy) - Groovy 的 RxJava 绑定
* [Vertx](https://vertx.io/) - Vert.x是一个轻量级、高性能的JVM应用平台

## Code Analysis
* [CodeNarc](http://codenarc.sourceforge.net/) - Groovy 静态分析工具
* [Sonar-Groovy](https://github.com/pmayweg/sonar-groovy) - SonarQube Groovy 插件

## Transpilers
* [Grooscript](https://github.com/chiquitinxx/grooscript) - 将您的 Groovy 代码转换为 Javascript

## Static Web
* [Grain](https://github.com/sysgears/grain) - Groovy 静态网站构建框架
* [Gaiden](https://github.com/kobo/gaiden) - Gaiden 是一个可以轻松使用 Markdown 创建文档的工具.

## Language Utilities
* [Functionalgroovy](https://github.com/mperry/functionalgroovy) - Groovy 中的函数式编程
* [Groovy-stream](https://github.com/timyates/groovy-stream) - 为 Streams 提供流畅构建器的类集合（Lazy Groovy 生成器）
* [Flipside](https://github.com/johnnywey/flipside) - 简单的 Groovy 选项库
* [groovy-common-extensions](https://github.com/timyates/groovy-common-extensions) - 允许您通过扩展系统添加对 Groovy 语言常用的东西
* [groovy-extra-list-behaviour](https://github.com/dnahodil/groovy-extra-list-behaviour) - 通过扩展系统向列表添加额外的方法
* [GPerfUtils](https://github.com/gperfutils) - 基于 Groovy 的工具验证代码的性能
  * [gprof](https://github.com/gperfutils/gprof) - Groovy 的分析模块
  * [gbench](https://github.com/gperfutils/gbench) - Groovy 的基准测试模块
* [Fuzzy-CSV](https://github.com/kayr/fuzzy-csv) - 简单的轻量级数据处理库，可用于在其他服务或库使用表格数据之前对表格数据进行整形/处理.

## Data Processing
* [Nextflow](https://www.nextflow.io/) - 用于数据驱动计算管道的 Groovy DSL

## File System Utilities
* [Groovy-Vfs](https://github.com/ysb33r/groovy-vfs) - Apache VFS2 之上的 Groovy DSL
* [Directree](https://github.com/kdabir/directree) - 使用文本文件创建目录树的简单 DSL

## File Format DSL
* [document-builder](https://github.com/craigburke/document-builder) - 用于 Groovy 的 PDF 或 Word 文档的文档生成器.
* [spreadsheet-builder](http://spreadsheet.dsl.builders/) - 电子表格生成器提供了创建 MS Excel OfficeOpenXML 文档 (XSLX) 的便捷方法
* [GroovyCSV](http://xlson.com/groovycsv/) - 一个简单的groovy CSV解析库

## Scripting Tools
* [EasyDokkaPlugin](https://github.com/Vorlonsoft/EasyDokkaPlugin) - Gradle 脚本插件，用于通过 Dokka 文档引擎为 Java 和 Kotlin 生成文档
* [GradleMavenPush](https://github.com/Vorlonsoft/GradleMavenPush) - Gradle 脚本插件，用于将 Gradle Artifacts 上传到 Maven 存储库
* [picocli](https://github.com/remkop/picocli)  - CLI 的解析器库和框架.  ANSI 颜色的使用帮助. 自动完成. 嵌套子命令等等.
* [sshoogr](https://github.com/aestasit/sshoogr) - 用于通过 SSH 与远程服务器合作的 DSL 库.


## Rule Engines
* [grules](https://github.com/zhaber/grules) - 数据预处理的规则引擎
* [n-cube](https://github.com/jdereg/n-cube) - 规则引擎、决策表、决策树、模板引擎和企业电子表格，构建为超空间.

## Resources

## Official Resources
* [The official groovy home](http://www.groovy-lang.org/) - Groovy 的新家
* [Groovy's source](https://github.com/apache/groovy) - Groovy 的源代码镜像在 Github 上
* [Groovy mailing lists](http://www.groovy-lang.org/mailing-lists.html) - 注意新的邮件列表
* [Official Documentation](http://www.groovy-lang.org/documentation.html) - Groovy 文档的权威来源

## Try Groovy in Browser
* [Groovy Web Console](https://gwc-experiment.appspot.com/)
* [Groovy Playground](https://groovy-playground.appspot.com/)

## Groovy Code Examples
* [MrHaKi's Goodness](http://mrhaki.blogspot.com/) - 查找标题为“Groovy Goodness”、“Grails Goodness”、“Gradle Goodness”的条目
* [PLEAC Groovy](http://pleac.sourceforge.net/pleac_groovy/) - Groovy 是 32 种语言中的 3 种之一，已完成 100% 的 PLEAC 示例.

## Staying up to date
* [Groovy Calamari](http://groovycalamari.com/) - Weekly curated publication about the Groovy Ecosystem
* [Groovy Weekly](http://glaforge.appspot.com/category/Groovy%20Weekly) - Groovy 每周通讯
* [Grails Diary](https://grydeske.dk/news/index) - 对 Grails 开发人员特别有用
* [Groovy Podcast](https://nofluffjuststuff.com/groovypodcast) - Ken Kousen 和 Baruch Sadogursky 讨论来自 Groovy 生态系统的新闻和见解.

## Interactive Learning
* [Groovy-Koans](http://nadavc.github.io/groovykoans/) - 单元测试形式的小练习集合

## Blogs of core committer
* [Guillaume Laforge's blog](http://glaforge.appspot.com/)
* [Cédric Champeau's blog](http://melix.github.io/blog/)
* [Jochen Theodorou's blog](http://blackdragsview.blogspot.com/)
* [Grails Team blog](http://grailsblog.objectcomputing.com/)

## Conferences
* [Community Over Code](https://communityovercode.org/) - 有一首 Groovy Track
* [Greachconf](http://greachconf.com) （已停产）
* [GR8Conf Europe](https://gr8conf.eu) （已停产）
* [GR8Conf USA](http://gr8conf.us) （已停产）

## Contributing

分叉此存储库，编辑此文件并发送拉取请求.

## Using awesome.groovy script

您可以使用`awesome.groovy`脚本在github上搜索awesome项目并生成预先填充项目名称、repo url和markdown格式描述的条目. 您需要做的就是将其放在“README.md”中 markdown 列表的右侧组下.

### Examples

找出语言是 groovy 且名称包含 gpars 的存储库

    ./awesome.groovy -l groovy gpars

查找用户“kdabir”且名称包含 glide 的存储库

    ./awesome.groovy -u kdabir 滑翔

找出名称包含glide的repos

    ./awesome.groovy 滑行

如果您懒于下载存储库，一个简单的方法是：

    groovy &quot;https://git.io/awesome&quot; -l groovy glide

## Credits

对于所有很棒的-* 存储库及其聚合器，例如 [this](https://github.com/erichs/awesome-awesome) 和 [this](https://github.com/bay和in/awesome-awesomeness).
