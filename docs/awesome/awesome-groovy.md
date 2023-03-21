<div class="github-widget" data-repo="kdabir/awesome-groovy"></div>
很棒的 Groovy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==============

很棒的 groovy 库、框架和资源的精选列表. 受到许多其他 awesome-* 存储库的启发. 这个很棒的收藏也可以在 [Groovy.ZEEF.com](https://groovy.zeef.com/kunal.dabir).



## Build tools, setup and CI
* [Gradle](https://www.gradle.org/) - 强大的 JVM 构建系统
* [GMavenPlus](https://github.com/groovy/GMavenPlus) - 重写 GMaven，Groovy 的 Maven 插件
* [SDKMAN](https://sdkman.io) - 软件开发工具包管理器（以前称为 GVM）
* [Lazybones](https://github.com/pledbrook/lazybones) - 一个简单的项目创建工具，使用打包的项目模板.
* [Jenkins job-dsl-plugin](https://github.com/jenkinsci/job-dsl-plugin) - 用于 Jenkins Jobs 的 Groovy DSL
* [travis-groovy](https://github.com/kdabir/travis-groovy) - 在 travis-ci 上执行 groovy 脚本
* [Android Groovy Shell](https://play.google.com/store/apps/details?id=com.tambapps.android.grooidshell) - 直接在您的智能手机上编写和执行 groovy 脚本

## IDE and Editor Support
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) - Java 平台最智能的 IDE
* [Groovy Web Console](http://groovyconsole.appspot.com) - 在线 Groovy 控制台
* [LightTable Plugin](https://github.com/rundis/LightTable-Groovy) - LightTable 支持
* [SpaceVim](https://spacevim.org/layers/lang/groovy/) - SpaceVim `lang#groovy` layer
* [Sublime Text 2/3](https://gist.github.com/kdabir/2203530) - 从 Sublime Text 运行 groovy 脚本

## Web Frameworks

* [Grails](https://github.com/grails/grails) - 基于 Groovy 语言的强大的 Web 应用程序框架
* [Gaelyk](https://github.com/gaelyk/gaelyk) - 适用于 Google App Engine Java 的轻量级 Groovy 工具包
* [Glide](https://github.com/kdabir/glide) - 快速在 Google App Engine 上创建很棒的应用程序
* [Ratpack](https://github.com/ratpack/ratpack) - 用于 JVM Web 应用程序的工具包
* [gServ](https://github.com/javaConductor/gserv) - 用于创建 SPA 和基于 REST 的微服务的 Groovy 工具包，无需容器（Tomcat、JBoss 等）.
* [Spring-Boot](https://projects.spring.io/spring-boot) - Spring Boot 可以轻松创建独立的、生产级的基于 Spring 的应用程序，您可以“直接运行”
* [Micronaut](http://micronaut.io/) - Grails团队打造的全新微服务框架

## Database
* [Gmongo](https://github.com/poiati/gmongo) - mongodb Java 驱动程序的 Groovy 包装器
* [Gstorm](https://github.com/kdabir/gstorm) - 一个简单的 ORM，用于在常规脚本中使用的简单数据库和 CSV 文件
* [Tayra](https://github.com/EqualExperts/Tayra) - MongoDB增量备份工具
* [Groovy-liquibase](https://github.com/tlberglund/groovy-liquibase) - 另一个用于 Liquibase 的 Groovy DSL
* [Effigy](https://github.com/cjstehno/effigy) - Groovy注解驱动的JDBC行映射框架（废弃）
* [elasticsearch-groovy](https://github.com/elastic/elasticsearch-groovy) - Elasticsearch Groovy 客户端

## Rich Application

* [Griffon](http://griffon-framework.org/) - Griffon 是一个用于在 JVM 中开发桌面应用程序的应用程序框架
* [GroovyFx](http://groovyfx.org/) - GroovyFX 为 JavaFX 2.0 提供 Groovy 绑定.

## HTTP
* [Http-Builder](https://github.com/jgritman/httpbuilder) - HTTPBuilder 是从 JVM 操作基于 HTTP 的资源的最简单方法
* [HTTP Builder NG](https://github.com/http-builder-ng/http-builder-ng) - HTTP Builder NG 是一种用于发出 http 请求的现代 Groovy DSL.
* [HTTP Builder NG Gradle Plugin](https://github.com/http-builder-ng/gradle-http-plugin) - Gradle 插件在 Gradle 构建配置中提供 HTTP Builder NG 支持.
* [AsyncRestClient](https://github.com/eginez/AsyncRestClient) - 将 RESTClient 的强大功能与 RxGroovy 结合起来进行异步 http 调用
* [Groovy-wslite](https://github.com/jwagenleitner/groovy-wslite) - Groovy 的轻量级 SOAP 和 REST 网络服务客户端
* [Hyperpoet](https://github.com/tambapps/hyperpoet) - 易于使用和可定制的 Groovy HTTP 客户端

## Testing
* [Spock](https://github.com/spockframework/spock) - 企业就绪测试和规范框架.
* [Geb](https://github.com/geb/geb) - 非常 Groovy 浏览器自动化
* [Betamax](https://github.com/betamaxteam/betamax) - Betamax 是一种用于在测试中模拟外部 HTTP 资源（例如 Web 服务和 REST API）的工具.
* [HTTP Mock Server](https://github.com/TouK/http-mock-server) - HTTP 模拟服务器允许使用 groovy 闭包模拟 HTTP 请求.
* [Ersatz Mock Server](https://github.com/cjstehno/ersatz) - 一个简单而富有表现力的模拟 HTTP 服务器，用于测试具有可配置响应的客户端代码.
* [Dru](https://agorapulse.github.io/dru/) - 数据重建实用程序从外部源 JSON、YML 加载数据，以便轻松测试 GORM、DynamoDB 或只是普通的 POJO.
* [Gru](https://agorapulse.github.io/gru/) - Groovy HTTP 测试框架，用于为任何 HTTP 后端运行集成和半集成测试，并支持 Grails 和 Spring MVC 的本机单元测试.

## Concurrency
* [GPars](https://github.com/GPars/GPars) - JVM 的 GPars 并发和并行框架
* [RxGroovy](https://github.com/ReactiveX/RxGroovy) - Groovy 的 RxJava 绑定
* [Vertx](https://vertx.io/) - Vert.x 是一个轻量级、高性能的 JVM 应用平台

## Code Analysis
* [CodeNarc](http://codenarc.sourceforge.net/) - Groovy 的静态分析工具
* [Sonar-Groovy](https://github.com/pmayweg/sonar-groovy) - SonarQube Groovy 插件

## Transpilers
* [Grooscript](https://github.com/chiquitinxx/grooscript) - 将您的 Groovy 代码转换为 Javascript

## Static Web
* [Grain](https://github.com/sysgears/grain) - Groovy 静态网站构建框架
* [Gaiden](https://github.com/kobo/gaiden) - Gaiden 是一种可以轻松使用 Markdown 创建文档的工具.

## Language Utilities
* [Functionalgroovy](https://github.com/mperry/functionalgroovy) - Groovy 中的函数式编程
* [Groovy-stream](https://github.com/timyates/groovy-stream) - 一组类，为 Streams 提供流畅的构建器（Lazy Groovy Generators）
* [Flipside](https://github.com/johnnywey/flipside) - 简单的 Groovy 选项库
* [groovy-common-extensions](https://github.com/timyates/groovy-common-extensions) - 允许您通过扩展系统向 Groovy 语言添加通常有用的东西
* [groovy-extra-list-behaviour](https://github.com/dnahodil/groovy-extra-list-behaviour) - 通过扩展系统向列表添加额外的方法
* [GPerfUtils](https://github.com/gperfutils) - 基于 Groovy 的工具验证代码的性能
  * [gprof](https://github.com/gperfutils/gprof) - Groovy 的分析模块
  * [gbench](https://github.com/gperfutils/gbench) - Groovy 的基准测试模块
* [Fuzzy-CSV](https://github.com/kayr/fuzzy-csv) - 简单的轻量级数据处理库，可用于在表格数据被其他服务或库使用之前对其进行整形/处理.

## File System Utilities
* [Groovy-Vfs](https://github.com/ysb33r/groovy-vfs) - Apache VFS2 之上的 Groovy DSL
* [Directree](https://github.com/kdabir/directree) - 使用文本文件创建目录树的简单 DSL

## File Format DSL
* [document-builder](https://github.com/craigburke/document-builder) - 用于 PDF 或 Word 文档的 Groovy 文档生成器.
* [spreadsheet-builder](http://spreadsheet.dsl.builders/) - 电子表格生成器提供了创建 MS Excel OfficeOpenXML 文档 (XSLX) 的便捷方式
* [GroovyCSV](http://xlson.com/groovycsv/) - 一个简单的 groovy CSV 解析库

## Scripting Tools
* [EasyDokkaPlugin](https://github.com/Vorlonsoft/EasyDokkaPlugin) - Gradle 脚本插件，用于通过 Dokka 文档引擎为 Java 和 Kotlin 生成文档
* [GradleMavenPush](https://github.com/Vorlonsoft/GradleMavenPush) - 用于将 Gradle 工件上传到 Maven 存储库的 Gradle 脚本插件
* [picocli](https://github.com/remkop/picocli)  - CLI 的解析器库和框架.  ANSI 颜色的使用帮助. 自动完成. 嵌套的子命令等等.
* [sshoogr](https://github.com/aestasit/sshoogr) - 通过 SSH 使用远程服务器的 DSL 库.


## Rule Engines
* [grules](https://github.com/zhaber/grules) - 用于数据预处理的规则引擎
* [n-cube](https://github.com/jdereg/n-cube) - 构建为超空间的规则引擎、决策表、决策树、模板引擎和企业电子表格.

## Resources

## Official Resources
* [The official groovy home](http://www.groovy-lang.org/) - Groovy 的新家
* [Groovy's source](https://github.com/apache/groovy) - Groovy 的源代码镜像在 Github 上
* [Groovy mailing lists](http://www.groovy-lang.org/mailing-lists.html) - 注意新的邮件列表
* [Official Documentation](http://www.groovy-lang.org/documentation.html) - groovy 文档的权威来源

## Try Groovy in Browser
* [Groovy Web Console](http://groovyconsole.appspot.com/)
* [Groovy Playground](https://groovy-playground.appspot.com/)

## Groovy Code Examples
* [MrHaKi's Goodness](http://mrhaki.blogspot.com/) - 留意标题为“Groovy Goodness”、“Grails Goodness”、“Gradle Goodness”的条目
* [PLEAC Groovy](http://pleac.sourceforge.net/pleac_groovy/) - Groovy 是 32 种语言中的 3 种语言之一，已完成 100% 的 PLEAC 示例.

## Staying up to date
* [Groovy Calamari](http://groovycalamari.com/) - 关于 Groovy 生态系统的每周精选出版物
* [Groovy Weekly](http://glaforge.appspot.com/category/Groovy%20Weekly) - Groovy 每周时事通讯
* [Grails Diary](https://grydeske.dk/news/index) - 对 Grails 开发人员特别有用
* [Groovy Podcast](https://nofluffjuststuff.com/groovypodcast) - Ken Kousen 和 Baruch Sadogursky 讨论来自 Groovy 生态系统的新闻和见解.

## Interactive Learning
* [Groovy-Koans](http://nadavc.github.io/groovykoans/) - 以单元测试的形式收集小练习

## Blogs of core committer
* [Guillaume Laforge's blog](http://glaforge.appspot.com/)
* [Cédric Champeau's blog](http://melix.github.io/blog/)
* [Jochen Theodorou's blog](http://blackdragsview.blogspot.com/)
* [Grails Team blog](http://grailsblog.objectcomputing.com/)

## Conferences
* [Greachconf](http://greachconf.com)
* [GR8Conf Europe](https://gr8conf.eu)
* [GR8Conf USA](http://gr8conf.us)

## Contributing

分叉此存储库，编辑此文件并发送拉取请求.

## Using awesome.groovy script

您可以使用 awesome.groovy 脚本在 github 上搜索 awesome 项目，并生成预先填充项目名称、repo url 和 markdown 格式描述的条目. 您需要做的就是将它放在 README.md 中降价列表中的右组下.

### Examples

找出语言是 groovy 并且其名称包含 gpars 和

    ./awesome.groovy -l groovy gpars

找出用户&#39;kdabir&#39;的repos并且名称包含glide

    ./awesome.groovy -u kdabir glide

找出名称包含 glide 的 repos

    ./awesome.groovy 滑行

如果你懒得下载 repo，一个简单的方法是：

    groovy &quot;https://git.io/awesome&quot; -l groovy glide

## Credits

对于那里所有的 awesome-* repos 和他们的聚合器 [this](https://github.com/erichs/awesome-awesome) 和 [this](https://github.com/bay和in/awesome-awesomeness).
