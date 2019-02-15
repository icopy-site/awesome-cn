令人敬畏的Groovy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==============

 精选groovy库，框架和资源的精选列表.  受到许多其他令人敬畏的*存储库的启发.  这个很棒的收藏品也可用 [Groovy.ZEEF.com](https://groovy.zeef.com/kunal.dabir).


- [Awesome Groovy](#awesome-groovy)
    - [Build Tools, Setup and CI](#build-tools-setup-and-ci)
    - [Concurrency](#concurrency)
    - [Database](#database)
    - [Desktop App Frameworks](#rich-applications)
    - [HTTP](#http)
    - [IDE and Editor Support](#ide-and-editor-support)
    - [Testing](#testing)
    - [Code analysis](#code-analysis)
    - [Web Frameworks](#web-frameworks)
    - [Transpilers](#transpilers)
    - [Static Web](#static-web)
    - [Language Utilities](#language-utilities)
    - [File System Utilities](#file-system-utilities)
    - [File Format DSL](#file-format-dsl)
    - [Scripting Tools](#scripting-tools)
    - [Rule Engines](#rule-engines)
- [Resources](#resources)
- [Contributing](#contributing)
- [Credits](#credits)

## Build tools, setup and CI
* [Gradle](https://www.gradle.org/) -  JVM的强大构建系统
* [GMavenPlus](https://github.com/groovy/GMavenPlus) - 重写GMaven，一个Groovy的Maven插件
* [SDKMAN](https://sdkman.io) - 软件开发套件管理器（以前称为GVM）
* [Lazybones](https://github.com/pledbrook/lazybones) - 一个使用打包项目模板的简单项目创建工具.
* [Jenkins job-dsl-plugin](https://github.com/jenkinsci/job-dsl-plugin) -  Jenkins Jobs的Groovy DSL
* [travis-groovy](https://github.com/kdabir/travis-groovy) - 在travis-ci上执行groovy脚本

## IDE and Editor Support
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) -  Java平台最智能的IDE
* [Groovy Grails Tool Suite](https://marketplace.eclipse.org/content/groovygrails-tool-suite-ggts-eclipse) - 基于Eclipse的IDE，针对开发，调试和执行Groovy和Grails应用程序进行了优化
* [Groovy Web Console](http://groovyconsole.appspot.com) - 在线Groovy控制台
* [LightTable Plugin](https://github.com/rundis/LightTable-Groovy) -  LightTable支持
* [Sublime Text 2/3](https://gist.github.com/kdabir/2203530) - 从Sublime Text运行groovy脚本

## Web Frameworks

* [Grails](https://github.com/grails/grails) - 基于Groovy语言的强大Web应用程序框架
* [Gaelyk](https://github.com/gaelyk/gaelyk) - 适用于Google App Engine Java的轻量级Groovy工具包
* [Glide](https://github.com/kdabir/glide) - 快速在Google App Engine上创建精彩的应用程序
* [Ratpack](https://github.com/ratpack/ratpack) -  JVM Web应用程序的工具包
* [gServ](https://github.com/javaConductor/gserv) - 用于创建基于SPA和REST的微服务的Groovy工具包，无需容器（Tomcat，JBoss等）.
* [Spring-Boot](https://projects.spring.io/spring-boot) -  Spring Boot可以轻松创建独立的，生产级的基于Spring的应用程序，您可以“只运行”
* [Micronaut](http://micronaut.io/) - 由Grails团队创建的全新微服务框架

## Database
* [Gmongo](https://github.com/poiati/gmongo) -  mongodb Java驱动程序的Groovy包装器
* [Gstorm](https://github.com/kdabir/gstorm) - 简单的ORM，用于简单数据库和CSV文件，用于groovy脚本
* [Tayra](https://github.com/EqualExperts/Tayra) -  MongoDB的增量备份工具
* [Groovy-liquibase](https://github.com/tlberglund/groovy-liquibase) - 还有另一种针对Liquibase的Groovy DSL
* [Effigy](https://github.com/cjstehno/effigy) -  Groovy注释驱动的JDBC行映射框架（废弃）
* [elasticsearch-groovy](https://github.com/elastic/elasticsearch-groovy) -  Elasticsearch Groovy客户端

## Rich Application

* [Griffon](http://griffon-framework.org/) -  Griffon是一个用于在JVM中开发桌面应用程序的应用程序框架
* [GroovyFx](http://groovyfx.org/) -  GroovyFX为JavaFX 2.0提供了Groovy绑定.

## HTTP
* [Http-Builder](https://github.com/jgritman/httpbuilder) -  HTTPBuilder是从JVM操作基于HTTP的资源的最简单方法
* [HTTP Builder NG](https://github.com/http-builder-ng/http-builder-ng) -  HTTP Builder NG是一个用于发出http请求的现代Groovy DSL.
* [HTTP Builder NG Gradle Plugin](https://github.com/http-builder-ng/gradle-http-plugin) -  Gradle插件，在Gradle构建配置中提供HTTP Builder NG支持.
* [AsyncRestClient](https://github.com/eginez/AsyncRestClient) - 将RESTClient的强大功能与RxGroovy相结合，实现异步http调用
* [Groovy-wslite](https://github.com/jwagenleitner/groovy-wslite) -  Groovy的轻量级SOAP和REST Web服务客户端

## Testing
* [Spock](https://github.com/spockframework/spock) - 企业级测试和规范框架.
* [Geb](https://github.com/geb/geb) - 非常Groovy浏览器自动化
* [Betamax](https://github.com/betamaxteam/betamax) -  Betamax是一种用于在测试中模拟外部HTTP资源（如Web服务和REST API）的工具.
* [HTTP Mock Server](https://github.com/TouK/http-mock-server) -  HTTP Mock Server允许使用groovy闭包来模拟HTTP请求.
* [Ersatz Mock Server](https://github.com/cjstehno/ersatz) - 一个简单而富有表现力的模拟HTTP服务器，用于测试具有可配置响应的客户端代码
* [Dru](https://agorapulse.github.io/dru/) -  Data Reconstruction Utility从外部源JSON，YML加载数据，以便于测试GORM，DynamoDB或普通的POJO.
* [Gru](https://agorapulse.github.io/gru/) -  Groovy HTTP测试框架，用于为任何HTTP后端运行集成和半嵌入测试，并为Grails和Spring MVC提供本机单元测试支持.

## Concurrency
* [GPars](https://github.com/GPars/GPars) -  JVM的GPars并发和并行框架
* [RxGroovy](https://github.com/ReactiveX/RxGroovy) -  Groovy的RxJava绑定
* [Vertx](https://vertx.io/) -  Vert.x是JVM的轻量级高性能应用程序平台

## Code Analysis
* [CodeNarc](http://codenarc.sourceforge.net/) -  Groovy的静态分析工具
* [Sonar-Groovy](https://github.com/pmayweg/sonar-groovy) - SonarQube Groovy plugin

## Transpilers
* [Grooscript](https://github.com/chiquitinxx/grooscript) - 将您的Groovy代码转换为Javascript

## Static Web
* [Grain](https://github.com/sysgears/grain) -  Groovy的静态网站构建框架
* [Gaiden](https://github.com/kobo/gaiden) -  Gaiden是一个使用Markdown轻松创建文档的工具.

## Language Utilities
* [Functionalgroovy](https://github.com/mperry/functionalgroovy) -  Groovy中的函数编程
* [Groovy-stream](https://github.com/timyates/groovy-stream) - 为Streams提供流畅构建器的类集合（Lazy Groovy Generators）
* [Flipside](https://github.com/johnnywey/flipside) - 简单的Groovy选项库
* [groovy-common-extensions](https://github.com/timyates/groovy-common-extensions) - 允许您通过扩展系统添加对Groovy语言通常有用的内容
* [groovy-extra-list-behaviour](https://github.com/dnahodil/groovy-extra-list-behaviour) - 通过扩展系统向列表添加额外的方法
* [GPerfUtils](https://github.com/gperfutils) - 基于Groovy的工具，用于验证代码的性能
  * [gprof](https://github.com/gperfutils/gprof) -  Groovy的分析模块
  * [gbench](https://github.com/gperfutils/gbench) -  Groovy的基准测试模块
* [Fuzzy-CSV](https://github.com/kayr/fuzzy-csv) - 简单的轻量级数据处理库，可用于在表格数据被其他服务或库使用之前对其进行整形/处理.

## File System Utilities
* [Groovy-Vfs](https://github.com/ysb33r/groovy-vfs) -  Apache VFS2上的Groovy DSL
* [Directree](https://github.com/kdabir/directree) - 使用文本文件创建目录树的简单DSL

## File Format DSL
* [document-builder](https://github.com/craigburke/document-builder) - 用于PDF或Word文档的Groovy文档构建器.
* [spreadsheet-builder](http://spreadsheet.dsl.builders/) - 电子表格构建器提供了如何创建MS Excel OfficeOpenXML文档（XSLX）的便捷方法
* [GroovyCSV](http://xlson.com/groovycsv/) - 一个简单的CSV解析库，用于groovy

## Scripting Tools
* [EasyDokkaPlugin](https://github.com/Vorlonsoft/EasyDokkaPlugin) -  Gradle脚本插件，用于为Java和Kotlin生成Dokka文档引擎的文档
* [GradleMavenPush](https://github.com/Vorlonsoft/GradleMavenPush) -  Gradle脚本插件，用于将Gradle工件上载到Maven存储库
* [sshoogr](https://github.com/aestasit/sshoogr) - 用于通过SSH处理远程服务器的DSL库.


## Rule Engines
* [grules](https://github.com/zhaber/grules) - 用于数据预处理的规则引擎
* [n-cube](https://github.com/jdereg/n-cube) - 规则引擎，决策表，决策树，模板引擎和企业电子表格，构建为超空间.

## Resources

## Official Resources
* [The official groovy home](http://www.groovy-lang.org/) -  Groovy的新家
* [Groovy's source](https://github.com/apache/groovy) -  Groovy的源代码镜像在Github上
* [Groovy mailing lists](http://www.groovy-lang.org/mailing-lists.html) - 注意新的邮件列表
* [Official Documentation](http://www.groovy-lang.org/documentation.html) -  groovy文档的权威来源

## Try Groovy in Browser
* [Groovy Web Console](http://groovyconsole.appspot.com/)
* [Groovy Playground](https://groovy-playground.appspot.com/)

## Groovy Code Examples
* [MrHaKi's Goodness](http://mrhaki.blogspot.com/) - 留意题为“Groovy Goodness”，“Grails Goodness”，Gradle Goodness的条目
* [Groovy Almanac](http://groovy-almanac.org/) - 有用的代码片段
* [PLEAC Groovy](http://pleac.sourceforge.net/pleac_groovy/) -  Groovy是32种语言中的3种语言之一，完成了100％的PLEAC示例.

## Staying up to date
* [Groovy Calamari](http://groovycalamari.com/) - 关于Groovy生态系统的每周策划出版物
* [Groovy Weekly](http://glaforge.appspot.com/category/Groovy%20Weekly) -  Groovy每周时事通讯
* [Grails Diary](http://grydeske.net/news) - 特别适用于Grails开发人员
* [Groovy Podcast](https://nofluffjuststuff.com/groovypodcast) -  Ken Kousen和Baruch Sadogursky讨论了Groovy生态系统的新闻和见解.

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

 您可以使用`awesome.groovy`脚本在github上搜索真棒项目，并使用markdown格式生成预先包含项目名称，repo url和描述的条目.  您需要做的就是将它放在`README.md`的markdown列表中的右侧组下.

### Examples

找出语言是时髦的，其名称包含gpars和

    ./awesome.groovy -l groovy gpars

用户&#39;kdabir&#39;查找回购，名称包含滑行

    ./awesome.groovy -u kdabir glide

找出名字中包含滑行的回购

    ./awesome.groovy滑翔

如果你懒得下载回购，一个简单的方法是：

    groovy“https://git.io/awesome”-l groovy glide

## Credits

对所有令人敬畏的人来说，他们和他们的传播者一样 [this](https://github.com/erichs/awesome-awesome) 和 [this](https://github.com/bay和in/awesome-awesomeness).
