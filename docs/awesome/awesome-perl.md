<div class="github-widget" data-repo="hachiojipm/awesome-perl"></div>
## Awesome Perl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的 Perl 资源列表，包括框架、库和软件. 灵感来自 [awesome-go](https://github.com/avelino/awesome-go).

### Another module list

我们还推荐这些列表.

* [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho "Task::Kensho")
* [Perlres - A list of resources about Perl](https://github.com/thibaultduponchelle/perlres)
* [PerlMaven.com list of Perl Software](http://perlmaven.com/perl-based-open-source-products)
* [Slaven's CPAN in a nutshell](https://github.com/eserte/srezic-misc/blob/master/cpan_in_a_nutshell/cpan_in_a_nutshell.pod)
 * 许多任务::** 模块.  （例如 Task::Plack、Task::BeLike::<AuthorName>  ...）



## Args

*用于论证表现和验证的库.*

* [Data::Validator](https://metacpan.org/pod/Data::Validator) - 类型约束系统上基于规则的验证器.
* [Params::Util](https://metacpan.org/pod/Params::Util) - 简单、紧凑和正确的参数检查功能.
* [Params::ValidationCompiler](https://metacpan.org/pod/Params::ValidationCompiler) - 验证方法/函数参数.
* [Smart::Args](https://metacpan.org/pod/Smart::Args)

## Audio

* [Audio::CD](https://metacpan.org/pod/Audio::CD) - libcdaudio 接口 (cd + cddb)
* [Audio::Wav](https://metacpan.org/pod/Audio::Wav) - 用于读取和写入 Microsoft WAV 文件的模块.
* [Audio::SndFile](https://metacpan.org/pod/Audio::SndFile) - 用于读取和写入声音文件的 Perl 库
* [Audio::Ao](https://metacpan.org/pod/Audio::Ao) - Ao 音频库的 Perl 包装器
* [MIDI::ALSA](https://metacpan.org/pod/MIDI::ALSA) - perl ALSA 库，加上一些接口函数

### DSP
* [Audio::Analyzer](https://metacpan.org/pod/Audio::Analyzer) - 通过 FFT 和 perl 解调音频！
* [Audio::Analyzer::ToneDetect](https://metacpan.org/pod/Audio::Analyzer::ToneDetect) - 检测音频文件或流中的音调频率

## Benchmarks

*用于基准测试的库*

* [Benchmark](https://metacpan.org/pod/Benchmark)
* [Dumbbench](https://metacpan.org/pod/Dumbbench)
* [Parallel::Benchmark](https://metacpan.org/pod/Parallel::Benchmark) - 多进程中的基准

## Caches

*与缓存软件对话的库*

* [CHI](https://metacpan.org/pod/CHI) - 统一的缓存处理接口，想想缓存的DBI
* [CHI::Driver::DBI](https://metacpan.org/pod/CHI::Driver::DBI) - CHI 的 DBI 驱动程序
* [CHI::Driver::DBIC](https://metacpan.org/pod/CHI::Driver::DBIC) - DBIx::CHI 的类驱动程序
* [CHI::Driver::Memcached](https://metacpan.org/pod/CHI::Driver::Memcached) - CHI 的 Memcached 驱动程序
* [CHI::Driver::MongoDB](https://metacpan.org/pod/CHI::Driver::MongoDB) - CHI 的 MongoDB 驱动程序
* [CHI::Driver::Redis](https://metacpan.org/pod/CHI::Driver::Redis) - CHI 的 Redis 驱动程序
* [Catalyst::Plugin::Session::Store::CHI](https://metacpan.org/pod/Catalyst::Plugin::Session::Store::CHI) - 使用 CHI 模块处理会话数据的存储后端
* [CGI::Application::Plugin::CHI](https://metacpan.org/pod/CGI::Application::Plugin::CHI) - 用于 CHI 缓存接口的 CGI-App 插件
* [Mojolicious::Plugin::CHI](https://metacpan.org/pod/Mojolicious::Plugin::CHI) - Interact with CHI caches


## Class Builder

*支持编写类和元编程的库*

* [Class::Accessor::Lite](https://metacpan.org/pod/Class::Accessor::Lite) - 简单的访问器生成器.
* [Class::Accessor::Lite::Lazy](https://metacpan.org/pod/Class::Accessor::Lite::Lazy) - 生成惰性访问器.
* [Homer](https://metacpan.org/pod/Homer) - 简单的基于原型的对象系统.
* [Mo](https://metacpan.org/pod/Mo)  - 微型对象. 莫少.
* [Moo](https://metacpan.org/pod/Moo) - 支持元编程的类生成器.
* [Moose](https://metacpan.org/pod/Moose) - 唯一的，驼鹿.
* [Mouse](https://metacpan.org/pod/Mouse) - 另一个类生成器，如 Moo/Moose.
* [Object::Pad](https://metacpan.org/pod/Object::Pad)  -`类示例{有$x;  method reader { return $x } }`，实验性试验场 [Cor](https://gist.github.com/Ovid/68b33259cb81c01f9a51612c7a294ede)
* [Object::Tiny](https://metacpan.org/pod/Object::Tiny) - 一个简洁、快速、小巧的类构建器.

## CLI

*用于开发 CLI 应用程序的库*

* [App::Cmd](https://metacpan.org/pod/App::Cmd) - 以更少的痛苦编写命令行应用程序.
* [Getopt::Long](https://metacpan.org/pod/Getopt::Long) - 命令行选项的扩展处理.

## Cloud

* [AWS::CloudFront](https://metacpan.org/pod/AWS::CloudFront) - Amazon CloudFront CDN 的轻量级接口
* [AWS::S3](https://metacpan.org/pod/AWS::S3) - Amazon S3 的轻量级接口（简单存储服务）
* [Net::Amazon::EC2](https://metacpan.org/pod/Net::Amazon::EC2) - 与 Amazon Elastic Compute Cloud (EC2) 环境的接口.
* [Net::AWS::SES](https://metacpan.org/pod/Net::AWS::SES) - 实现 Amazon Simple Email Service (SES) 客户端的 Perl 扩展
* [WebService::DigitalOcean](https://metacpan.org/pod/WebService::DigitalOcean) - 访问 DigitalOcean RESTful API (v2)
* [WebService::Dropbox](https://metacpan.org/pod/WebService::Dropbox) - 与 Dropbox API 的接口

## Cryptography

* [Bitcoin::Crypto](https://metacpan.org/pod/Bitcoin::Crypto) - Perl 中的比特币密码学
* [CryptX](https://metacpan.org/pod/CryptX) - 加密工具包

## Commercial WebServices

* [Net::Xero](https://metacpan.org/pod/Net::Xero) - 与 Xero 会计的接口
* [PagerDuty::Agent](https://metacpan.org/pod/PagerDuty::Agent) - 一个 perl PagerDuty 客户端
* [WebService::Spotify](https://metacpan.org/pod/WebService::Spotify) - 一个简单的 Spotify Web API 接口
* [WebService::Xero](https://metacpan.org/pod/WebService::Xero) - 访问 Xero Accounting Package 公共和私有应用程序 API
* [WWW::Shopify](https://metacpan.org/pod/WWW::Shopify) - 表示访问特定 Shopify 商店的对象
* [WWW::Spotify](https://metacpan.org/pod/WWW::Spotify) - Spotify Web API 包装器

## Container

*用于单例模式实现的库.*

* [Object::Container](https://metacpan.org/pod/Object::Container)

## Data Format

*用于序列化、格式化和解析的库*

* [BSON](https://metacpan.org/pod/BSON) - 二进制 JSON 格式
* [CBOR::Free](https://metacpan.org/pod/CBOR::Free) - 支持 (CBOR)[https://tools.ietf.org/html/rfc7049]，IETF 的“二进制 JSON”
* [Data::Dumper::Simple](https://metacpan.org/pod/Data::Dumper::Simple) - 减少和更快的 Data::Dumper 和 eval() 等效
* [Data::MessagePack](https://metacpan.org/pod/Data::MessagePack)
* [JSON::PP](https://metacpan.org/pod/JSON::PP)
* [JSON::XS](https://metacpan.org/pod/JSON::XS)
* [Sereal](https://metacpan.org/pod/Sereal)
* [Storable](https://metacpan.org/pod/Storable)
* [Text::CSV](https://metacpan.org/pod/Text::CSV)
* [Text::CSV_XS](https://metacpan.org/pod/Text::CSV_XS)
* [Text::Markdown](https://metacpan.org/pod/Text::Markdown)
* [TOML](https://metacpan.org/pod/TOML)
* [XML::LibXML](https://metacpan.org/pod/XML::LibXML)
* [XML::Compile::Schema](https://metacpan.org/pod/XML::Compile::Schema) - 解释模式元素和类型：为 XML 消息创建处理器.
* [XML::Compile::SOAP](https://metacpan.org/pod/XML::Compile::SOAP) - 在客户端实现 SOAP 1.1 协议.
* [XML::Compile::WSDL](https://metacpan.org/pod/XML::Compile::WSDL) - 将 SOAP 与 WSDL 1.1 版通信规范文件一起使用.
* [YAML](https://metacpan.org/pod/YAML)

## Database

*处理关系数据库的库*

* [DBI](https://metacpan.org/pod/DBI)
* [DBIx::Connector](https://metacpan.org/pod/DBIx::Connector) - 快速、安全的 DBI 连接和事务管理
* [DBIx::Handler](https://metacpan.org/pod/DBIx::Handler) - 分叉安全 DBI 处理程序
* [DBIx::Inspector](https://metacpan.org/pod/DBIx::Inspector)
* [DBIx::QueryLog](https://metacpan.org/pod/DBIx::QueryLog)
* [DBIx::Sunny](https://metacpan.org/pod/DBIx::Sunny) - 有用的 DBI 包装器
* [DBIx::TransactionManager](https://metacpan.org/pod/DBIx::TransactionManager)

## Database Drivers

*使用特定数据库产品的库*

### Relational Databases

* [DBD::CSV](https://metacpan.org/pod/DBD::CSV)
* [DBD::Firebird](https://metacpan.org/pod/DBD::Firebird)
* [DBD::mysql](https://metacpan.org/pod/DBD::mysql)
* [DBD::ODBC](https://metacpan.org/pod/DBD::ODBC)  - 任何 ODBC 驱动程序. 带占位符的 MS-SQL
* [DBD::Oracle](https://metacpan.org/pod/DBD::Oracle) - DBI 模块的 Oracle 数据库驱动程序
* [DBD::Pg](https://metacpan.org/pod/DBD::Pg) - DBI 的 PostgreSQL 驱动程序.
* [DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)
* [DBD::Sybase](https://metacpan.org/pod/DBD::Sybase)  - Sybase 和 MS-SQL. 虽然没有带 MS-SQL 的占位符

### NoSQL Databases

* [Cache::Memcached::Fast](https://metacpan.org/pod/Cache::Memcached::Fast)
* [Mango](https://metacpan.org/pod/Mango) - 纯 Perl 非阻塞 I/O MongoDB 驱动程序
* [Redis](https://metacpan.org/pod/Redis)
* [Redis::Fast](https://metacpan.org/pod/Redis::Fast) - 围绕 hiredis 驱动程序的 Perl 包装器
* [Search::Elasticsearch](https://metacpan.org/pod/Search::Elasticsearch) - 官方 Elasticsearch 客户端库
* [UnQLite](https://metacpan.org/pod/UnQLite)

## Date & Time

*处理日期和时间的库*

* [DateTime](https://metacpan.org/pod/DateTime)
* [Time::Moment](https://metacpan.org/pod/Time::Moment)
* [Time::Piece](https://metacpan.org/pod/Time::Piece)

## Devices

*与物理设备对话的库*

* [Device::SerialPort](https://metacpan.org/pod/Device::SerialPort) - 用于串行线路通信的通用串行端口库
* [Device::Modem](https://metacpan.org/pod/Device::Modem) - 与通过串行端口连接的调制解调器设备通话
* [Device::Onkyo](https://metacpan.org/pod/Device::Onkyo) - 通过 LAN 或串口控制 Onkyo/Integra AV 设备
* [Chipcard::PCSC::Card](https://metacpan.org/pod/distribution/pcsc-perl/Card/Card.pod) - 使用 perl 和 PCSC 控制智能卡
* [Device::XBee::API](https://metacpan.org/pod/Device::XBee::API) - 使用纯 perl 代码控制 XBee 设备
* [Device::Firmata](https://metacpan.org/pod/Device::Firmata) - 用于控制 Arduino 等 Firmata 设备的模块

## DevOps Tools

*当您想在多台主机上跨网络部署软件/跨计算机网络工作时，这些库会有所帮助*

* [Rex](https://metacpan.org/pod/Rex) - 远程执行

## Email

*实现电子邮件创建和发送的库*

* [Email::Sender](https://metacpan.org/pod/Email::Sender)
* [Email::Reply](https://metacpan.org/pod/Email::Reply)
* [Email::Stuffer](https://metacpan.org/pod/Email::Stuffer)

## Event Loops

 *各种事件循环的库. 异步编程，如果你喜欢*

* [AE](https://metacpan.org/pod/AE) - 更简单、更快、更新的 AnyEvent API
* [AnyEvent](https://metacpan.org/pod/AnyEvent) - 事件循环编程之DBI
* [EV](https://metacpan.org/pod/EV)  - 使用 libev，非常快速且流行.  AnyEvent 的默认值（如果存在）
* [Event](https://metacpan.org/pod/Event) - 运作良好，但较旧
* [IO::Async](https://metacpan.org/pod/IO::Async) - 异步事件驱动编程
* [POE](https://metacpan.org/pod/POE) - 多个事件循环的通用接口
* [Promise::XS](https://metacpan.org/pod/Promise::XS) - Perl 中的承诺

## Exception Handling

*协助和/或提供 eval{die()} 替代方法的库*

* [autodie](https://metacpan.org/pod/autodie) - 用词法范围内成功或死亡的函数替换函数
* [Exception::Class](https://metacpan.org/pod/Exception::Class) - 允许您在 Perl 中声明真正的异常类的模块
* [Syntax::Keyword::Try](https://metacpan.org/pod/Syntax::Keyword::Try) - perl 的 try/catch/finally 语法
* [Throwable](https://metacpan.org/pod/Throwable) - 可以抛出的类的角色
* [Try::Tiny](https://metacpan.org/pod/Try::Tiny) - 最小的 try/catch 并适当保存 $@
* [TryCatch](https://metacpan.org/pod/TryCatch) - Perl 的一流 try catch 语义，没有源过滤器

## DOM Manipulation

* [HTML5::DOM](https://metacpan.org/pod/HTML5::DOM) - 带有 css 选择器的超快速 html5 DOM 库（基于 Modest/MyHTML）.

## File Manipulation

* [File::Util](https://metacpan.org/pod/File::Util) - 简单、通用、便携的文件处理.
* [Path::Tiny](https://metacpan.org/pod/Path::Tiny) - 简单的面向对象的文件操作.

## Form Frameworks

*从（Web 和 UI）表单中消除无聊和重复的库*

* [Catalyst::Controller::HTML::FormFu](https://metacpan.org/pod/Catalyst::Controller::HTML::FormFu) - 在 Catalyst 中使用 HTML::FormFu.
* [CGI::FormBuilder](https://metacpan.org/pod/CGI::FormBuilder) - 轻松生成和处理状态表单.
* [Form::Sensible](https://metacpan.org/pod/Form::Sensible) - 处理基于表单的用户界面的明智方法.
* [Form::Tiny](https://metacpan.org/pod/Form::Tiny) - 表单重用 Type::Tiny 类型约束.
* [Form::Toolkit](https://metacpan.org/pod/Form::Toolkit) - 用于构建以数据为中心的表单的工具包.
* [HTML::FormFu](https://metacpan.org/pod/HTML::FormFu) - HTML 表单创建、呈现和验证框架.
* [HTML::FormFu::ExtJS](https://metacpan.org/pod/HTML::FormFu::ExtJS) - 从 HTML::FormFu 配置文件生成 ExtJS 表单.
* [HTML::FormHandler](https://metacpan.org/pod/HTML::FormHandler) - 使用 Moose 的 HTML 表单.
* [Mojolicious::Plugin::FormFields](https://metacpan.org/pod/Mojolicious::Plugin::FormFields) - 具有验证和过滤功能的轻量级、灵活的表单生成器.
* [WWW::Form](https://metacpan.org/pod/WWW::Form) - 简单且可扩展的模块，允许开发人员灵活一致地处理 HTML 表单输入验证和显示.

## Images

*用于处理图像的库*

* [Image::Magick](https://metacpan.org/pod/Image::Magick) - ImageMagick 图像合成库的面向对象接口.
* [Imager](https://metacpan.org/pod/Imager)
* [GD](https://metacpan.org/pod/GD) - 与 Gd 图形库的接口
* [Image::Info](https://metacpan.org/pod/Image::Info) - 获取图像信息
* [Image::PNG::Libpng](https://metacpan.org/pod/release/BKB/Image-PNG-Libpng-0.52_03/lib/Image/PNG/Libpng.pm) - libpng 的 Perl 接口
* [Graphics::TIFF](https://metacpan.org/pod/Graphics::TIFF) - libtiff 的 Perl 包装器
* [Image::BMP](https://metacpan.org/pod/Image::BMP) - Perl 位图图像解析器和查看器

## List Manipulation

*用于操作列表（数组）的库*

* [Array::Unique](https://metacpan.org/pod/Array::Unique) - 仅允许唯一值的可绑定数组
* [List::AllUtils](https://metacpan.org/pod/List::AllUtils) - 将 List::Util、List::SomeUtils 和 List::UtilsBy 合并到一个小包中
* [List::Compare](https://metacpan.org/pod/List::Compare) - 比较两个或多个列表的元素
* [List::Gen](https://metacpan.org/pod/List::Gen) - 提供生成列表的函数
* [List::MoreUtils](https://metacpan.org/pod/List::MoreUtils) - 提供 List::Util 中缺少的东西
* [List::SomeUtils](https://metacpan.org/pod/List::SomeUtils) - 提供 List::Util 中缺少的东西
* [List::Util](https://metacpan.org/pod/List::Util) - 一系列通用实用程序列表子例程
* [List::UtilsBy](https://metacpan.org/pod/List::UtilsBy) - 高阶列表效用函数

## Logging

*用于生成和使用日志文件的库*

* [Log::Dispatch](https://metacpan.org/pod/Log::Dispatch)
* [Log::Log4perl](https://metacpan.org/pod/Log::Log4perl)
* [Log::Minimal](https://metacpan.org/pod/Log::Minimal)

## Module Development

*简化和改进 Perl 模块开发的库*

* [Dist::Zilla](https://metacpan.org/pod/Dist::Zilla) - <http://dzil.org/>
* [Minilla](https://metacpan.org/pod/Minilla) - CPAN 模块创作工具

## Network

*在处理计算机网络时提供帮助的库*

* [DOCSIS::ConfigFile](https://metacpan.org/pod/DOCSIS::ConfigFile) - 解码和编码 DOCSIS 配置文件
* [NetAddr::MAC](https://metacpan.org/pod/NetAddr::MAC) - 处理 MAC 地址

*在您跨计算机网络工作时提供帮助的库*

* [Net::SSH::Perl](https://metacpan.org/pod/Net::SSH::Perl) - 在 Perl 中实现的 SSH 客户端.
* [Net::SSH2](https://metacpan.org/pod/Net::SSH2) - 包装器 [libssh2](https://libssh2.org/).
* [Net::OpenSSH](https://metacpan.org/pod/Net::OpenSSH) - 使用远程运行命令 [OpenSSH](http://www.openssh.com/) 客户.
* [Net::OpenSSH::Parallel](https://metacpan.org/pod/Net::OpenSSH::Parallel) - 使用 OpenSSH 客户端并行运行远程命令.
* [Net::SSH::Any](https://metacpan.org/pod/Net::SSH::Any) - 使用可用的任何模块或二进制客户端运行远程命令.
* [Net::SFTP::Foreign](https://metacpan.org/pod/Net::SFTP::Foreign) - 用于远程文件访问的 SFTP 客户端.
* [Object::Remote](https://metacpan.org/pod/Object::Remote) - 在远程机器上运行 Perl 代码.
* [Net::CLI::Interact](https://metacpan.org/pod/Net::CLI::Interact) - 自动化交互式程序.
* [Net::Appliance::Session](https://metacpan.org/pod/Net::Appliance::Session) - 自动与设备交互.

## ORM

*实现对象关系映射或数据映射技术的库*

* [DBIx::Class](https://metacpan.org/pod/DBIx::Class)
* [Rose::DB](https://metacpan.org/pod/Rose::DB)
* [Teng](https://metacpan.org/pod/Teng)

## Package Management

*用于包和依赖管理的库*

* [App::cpanminus](https://metacpan.org/pod/App::cpanminus)
* [Carton](https://metacpan.org/pod/Carton)
* [Pinto](https://metacpan.org/pod/Pinto) - 强大的本地 CPAN 回购

## Processes and Threads

*用于管理进程和线程的库*

* [Parallel::ForkManager](https://metacpan.org/pod/Parallel::ForkManager) - 一个简单的并行处理叉管理器
* [Parallel::Prefork](https://metacpan.org/pod/Parallel::Prefork) - 一个简单的prefork服务器框架
* [Proclet](https://metacpan.org/pod/Proclet) - 简约的主管，一个 Perl 端口 [foreman](https://github.com/ddollar/foreman)

## Profiling

*用于检查程序运行时活动的库*

* [Devel::KYTProf](https://metacpan.org/pod/Devel::KYTProf) - 非常轻量级的 I/O 分析器，例如 HTTP 请求-响应和 SQL 查询.
* [Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf) - 代码分析器.

## Protocol

*协议客户端和库*

* [Furl](https://metacpan.org/pod/Furl) - 更快的 HTTP(S) 客户端
* [HTTP::Tiny](https://metacpan.org/pod/HTTP::Tiny)  - 最小和快速的客户端. 包含在标准包中.
* [LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent) - 流行的 HTTP(S) 客户端
* [Net::Curl](https://metacpan.org/pod/Net::Curl) - (libcurl)[https://curl.se/libcurl/] 整合
* [Net::DHCP](https://metacpan.org/pod/Net::DHCP) - 发送和接收 DHCP 数据包
* [Net::DNS](https://metacpan.org/pod/Net::DNS) - 解析 DNS 主机名
* [Protocol::DBus](https://metacpan.org/pod/Protocol::DBus) -（纯）Perl 中的 D-Bus

## Queueing

*消息队列，作业队列系统..*

* [Gearman](https://metacpan.org/pod/Gearman)
* [Minion](https://docs.mojolicious.org/Minion) - 纯 Perl 作业队列
* [Net::RabbitMQ](https://metacpan.org/pod/Net::RabbitMQ)
* [Net::Stomp](https://metacpan.org/pod/Net::Stomp)
* [Qudo](https://metacpan.org/pod/Qudo)
* [Resque](https://metacpan.org/pod/Resque)
* [TheSchwartz](https://metacpan.org/pod/TheSchwartz)

## Science/Numerics
*为研究、科学、数字和超计算精心挑选的模块*

* [BioPerl](https://metacpan.org/pod/BioPerl)
* [Chart::Clicker](https://metacpan.org/pod/Chart::Clicker) - 强大的、可扩展的图表
* [PDL](http://pdl.perl.org/)
* [PDL (CPAN)](https://metacpan.org/pod/PDL)
* [PDL::Graphics::Gnuplot](https://metacpan.org/pod/PDL::Graphics::Gnuplot)
* [PDL::IO::*](https://metacpan.org/search?q=PDL%3A%3AIO&size=20)
* [PDL::LinearAlgebra](https://metacpan.org/pod/PDL::LinearAlgebra)
* [PDL::Stats](https://metacpan.org/pod/PDL::Stats)
* [Physics::*](https://metacpan.org/search?q=physics%3A%3A&size=20)

## Stream Manipulation

*用于操作事件流的库*

* [RxPerl](https://metacpan.org/pod/RxPerl) - Perl 实现 [Reactive Extensions](http://reactivex.io) / rxjs

## REST Frameworks

*用于开发 REST 应用程序的库*

* [Catalyst::Action::REST](https://metacpan.org/pod/Catalyst::Action::REST) - 自动 REST 方法调度
* [Dancer2::Plugin::REST](https://metacpan.org/pod/Dancer2::Plugin::REST) - 使用 Dancer2 编写 RESTful 应用程序的插件
* [Dancer::Plugin::REST](https://metacpan.org/pod/Dancer::Plugin::REST) - 用于使用 Dancer 编写 RESTful 应用程序的插件
* [Raisin](https://metacpan.org/pod/Raisin) - 用于 Perl 的 REST API 微框架
* [Squatting](https://metacpan.org/pod/Squatting) - 受露营启发的 Perl Web 微框架

## Template Engines

*用于模板化的库和工具*

* [HTML::Template](https://metacpan.org/pod/HTML::Template) - 网页模板
* [Template::Alloy](https://metacpan.org/pod/Template::Alloy) - TT2/3、HT、HTE、Tmpl 和速度引擎
* [Template::Toolkit](https://metacpan.org/pod/Template::Toolkit) - 非常受欢迎的模板处理系统
* [Text::MicroTemplate](https://metacpan.org/pod/Text::MicroTemplate) - 用纯 Perl 和核心模块编写的快速、简单和安全的模板引擎.
* [Text::MicroTemplate::Extended](https://metacpan.org/pod/Text::MicroTemplate::Extended) - 扩展文本::微模板.
* [Text::Template](https://metacpan.org/pod/Text::Template) - 带有嵌入式 perl 的模板
* [Text::Xslate](https://metacpan.org/pod/Text::Xslate)  - 更快的 XS 模板引擎. 支持多种语法.
* [Tiffany](https://metacpan.org/pod/Tiffany)  - 模板引擎的通用接口. 它使使用多个模板引擎变得容易.
* [Template::Magic](https://metacpan.org/pod/Template::Magic) - 运行时值与模板的神奇合并.

## Testing

*用于测试代码库和生成测试数据的库.*

### Testing Frameworks

* [Test::Base](https://metacpan.org/pod/Test::Base) - 数据驱动测试框架
* [Test::Base::Less](https://metacpan.org/pod/Test::Base::Less) - 测试::基地的限制版本
* [Test::BDD::Cucumber](https://metacpan.org/pod/Test::BDD::Cucumber) - 在 Perl 中实现流行的 Cucumber 框架
* [Test::Class](https://metacpan.org/pod/Test::Class)  - 基于类的测试. 支持“设置”和“拆卸”.
* [Test::Deep](https://metacpan.org/pod/Test::Deep) - 以极大的灵活性测试深度和复杂的数据结构.
* [Test::Deep::Matcher](https://metacpan.org/pod/Test::Deep::Matcher)
* [Test::Harness](https://metacpan.org/pod/Test::Harness) - 运行带有统计信息的 Perl 标准测试脚本
* [Test::Kantan](https://metacpan.org/pod/Test::Kantan) - 简单、灵活、有趣的“测试框架”
* [Test::More](https://metacpan.org/pod/Test::More)

### Test Double

* [Test::Exception](https://metacpan.org/pod/Test::Exception)
* [Test::Fatal](https://metacpan.org/pod/Test::Fatal) - 用于验证异常的简单模块.
* [Test::Mock::Guard](https://metacpan.org/pod/Test::Mock::Guard) - 模拟包子程序.
* [Test::MockTime](https://metacpan.org/pod/Test::MockTime)
* [Test::mysqld](https://metacpan.org/pod/Test::mysqld)
* [Test::TCP](https://metacpan.org/pod/Test::TCP) - 启动临时 TCP 服务器
* [Test::Time](https://metacpan.org/pod/Test::Time) - 用于伪造系统时间的简单模块.

### Coverage

* [Devel::Cover](https://metacpan.org/pod/Devel::Cover)
* [Devel::Cover::Report::Coveralls](https://metacpan.org/pod/Devel::Cover::Report::Coveralls) 向工作服报告

## Tools

*一些有用的工具*

* [App::Ack](https://metacpan.org/pod/App::Ack) - ack 是像 grep 一样的工具，针对程序员进行了优化.
* [App::Nopaste](https://metacpan.org/pod/App::Nopaste) - 从 CLI 发布到各种 pastebin
* [Daiku](https://metacpan.org/pod/Daiku) - 为 Perl 制作.
* [Data::Printer](https://metacpan.org/pod/Data::Printer) - Perl 数据结构和对象的彩色漂亮打印.
* [Reply](https://metacpan.org/pod/Reply) - Read-eval-print-loop(REPL) 命令行工具.
* [Riji](https://metacpan.org/pod/Riji) - 使用 markdown 和 git 主要用于博客的静态站点生成器.
* [Smart::Comments](https://metacpan.org/pod/Smart::Comments) - 不仅仅是坐在那里的评论.

*用于开发命令行应用程序的库*

* [Toolbox::Simple](https://metacpan.org/pod/Toolbox::Simple) - 简化 Perl 中的一些常见任务.
* [Script::Toolbox](https://metacpan.org/pod/Script::Toolbox) - 日常业务脚本的框架.
* [Devel::Kit](https://metacpan.org/pod/Devel::Kit)- 方便开发/调试的便利工具箱.

*用于处理配置文件的库*

* [Config::Tiny](https://metacpan.org/pod/Config::Tiny) - 用尽可能少的代码读/写 .ini 样式文件


## Type checking

* [MooseX::Types](https://metacpan.org/pod/MooseX::Types) - 驼鹿类型管理工具
* [Type::Tiny](https://metacpan.org/pod/Type::Tiny) - 小而全面的类型库

## Video

* [FFmpeg](https://metacpan.org/pod/FFmpeg) - FFmpeg 接口，一个用 C 语言编写的视频转换器
* [Video::Info](https://metacpan.org/pod/Video::Info) - 检索视频属性，例如：高度宽度编解码器 fps
* [Vlc::Engine](https://metacpan.org/pod/Vlc::Engine) - 在 Perl 中使用 Vlc 媒体播放器
* [VideoLAN::LibVLC](https://metacpan.org/pod/VideoLAN::LibVLC) - libvlc.so 的 Perl 绑定
* [Video::Generator](https://metacpan.org/pod/Video::Generator) - 用于视频生成的 Perl 类

## Web Frameworks

*用于开发 Web 应用程序的库*

* [Amon2](https://metacpan.org/pod/Amon2)
* [Catalyst](https://metacpan.org/pod/Catalyst)  - 充满特色. 很受欢迎.
* [Dancer](https://metacpan.org/pod/Dancer) ([Official site](http://perldancer.org/))
* [Dancer2](https://metacpan.org/pod/Dancer2)
* [Gantry](https://metacpan.org/pod/Gantry) - 用于 mod\_perl、cgi 等的 Web 应用程序框架.
* [Kelp](https://metacpan.org/pod/Kelp) - 以 Plack 为中心的 Perl 网络框架
* [Kossy](https://metacpan.org/pod/Kossy) - 具有简单界面的Web框架.
* [Mojolicious](https://metacpan.org/pod/Mojolicious) - 一个多合一的框架.
* [Poet](https://metacpan.org/pod/Poet) - 面向 Mason 开发人员的现代 Perl Web 框架

### Middlewares

*用于创建 HTTP 中间件的库*

* [Gazelle](https://metacpan.org/pod/Gazelle) - 为性能怪胎预制的 Plack Handler
* [Plack](https://metacpan.org/pod/Plack) - 用于 Web 应用程序的 PSGI 服务器实现和实用程序.
* [Server::Starter](https://metacpan.org/pod/Server::Starter) - 具有“优雅重启”功能的进程管理器.
* [Starlet](https://metacpan.org/pod/Starlet) - 高性能 PSGI 服务器
* [Starman](https://metacpan.org/pod/Starman) - 高性能预分叉 PSGI/Plack Web 服务器
* [Twiggy](https://metacpan.org/pod/Twiggy) - 事件驱动的 PSGI 应用服务器

## Web Frameworks-Like

*介于模板和完整框架之间*

* [Embperl](https://metacpan.org/pod/Embperl) - 使用 Perl 构建动态网站（有点像 Perl 与 PHP 的结合）
* [Mason](https://metacpan.org/pod/Mason) - Powerful, high-performance templating for the web and beyond

## Web Scraping

*从网站中提取一些信息的库*

* [Web::Scraper](https://metacpan.org/pod/Web::Scraper)
* [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)
* [WWW::Mechanize::PhantomJS](https://metacpan.org/pod/WWW::Mechanize::PhantomJS) - 自动化 PhantomJS 浏览器
* [WWW::Scripter](https://metacpan.org/pod/distribution/WWW-Scripter/lib/WWW/Scripter.pod) - 对于有脚本的脚本网站
* [WWW::Selenium](https://metacpan.org/pod/WWW::Selenium) 


## Network Security

*用 Perl 开启网络安全世界的一些很棒的库*


* [Net::Pcap](https://metacpan.org/pod/Net::Pcap) - 与 pcap LBL 数据包捕获库的接口
* [Net::Ncap](https://metacpan.org/pod/Net::Ncap) - Perl 绑定到 ncap 网络数据捕获库
* [Net::Frame](https://metacpan.org/pod/Net::Frame) - 用于框架制作的 Perl 框架
* [NetPacket](https://metacpan.org/pod/NetPacket) - 在协议级别组装/拆卸网络数据包
* [Net::Write](https://metacpan.org/pod/Net::Write) - 用于打开原始数据并将其发送到网络的便携式接口
* [Net::Analysis](https://metacpan.org/pod/Net::Analysis) - 用于分析网络流量的 Perl 库
* [Net::Silk](https://metacpan.org/pod/Net::Silk) - Perl 与 SiLK 网络流库的接口
* [Net::Inspect](https://metacpan.org/pod/Net::Inspect) - 用于检查各种网络层上的数据的 Perl 库
* [Net::Tshark](https://metacpan.org/pod/Net::Tshark) - Tshark 网络捕获实用程序的 Perl 接口 
* [Net::Sharktools](https://metacpan.org/pod/Net::Sharktools) - Wireshark 在 Perl 中的数据包检测功能
* [File::PCAP](https://metacpan.org/pod/File::PCAP) - 通过 Perl 读取、写入和操作 PCAP 文件格式
* [Net::P0f](https://metacpan.org/pod/Net::P0f) - p0f 实用程序的 Perl 接口，对指纹识别操作系统很有用
* [Net::Pcap::Reassemble](https://metacpan.org/pod/Net::Pcap::Reassemble) - Net::Pcap 的 Perl IP 片段重组
* [Nagios::NRPE](https://metacpan.org/pod/Nagios::NRPE) - 纯 perl Nagios NRPE 实现
* [Monitoring::Plugin](https://metacpan.org/pod/Monitoring::Plugin) - 一系列 perl 模块，用于简化编写 Naemon、Nagios、Icinga 或 Shinken（及兼容）插件
* [Net::Connection::Sniffer](https://metacpan.org/pod/Net::Connection::Sniffer) - 用于 MiTM 连接的实用 Perl 库
* [Net::ARP](https://metacpan.org/pod/Net::ARP) - 用于制作 ARP 数据包的库
* [SNMPMonitor](https://metacpan.org/pod/SNMPMonitor) - 用于编写 SNMP 监视器的 Perl 扩展
* [Net::LibNIDS](https://metacpan.org/pod/Net::LibNIDS) - 网络入侵检测系统库的 Perl 接口
* [Parse::Snort](https://metacpan.org/pod/Parse::Snort) - Perl Snort 规则解析器
* [Net::Wireless::802_11::WPA::CLI](https://metacpan.org/pod/Net::Wireless::802_11::WPA::CLI) - Perl WPA_CLI 接口
* [IO::Socket::SSL::Intercept](https://metacpan.org/IO::Socket::SSL::Intercept) - 通过 Perl 拦截 SSL 连接的库

## Metadata Forensics

*通用元数据文件解析器，在取证调查期间很有用*

* [Image::ExifTool](https://metacpan.org/pod/distribution/Image-ExifTool/exiftool) - 通用元数据解析器和查看器框架

## Reverse Engineering

*用于反汇编操作、ELF文件和字节码的库*

* [Disassembly](https://metacpan.org/pod/distribution/B-C/script/disassemble) - 将二进制字节码反编译为可读和可重新编译的字节码汇编器
* [Python::Bytecode](https://metacpan.org/pod/Python::Bytecode) - 解析 Python 字节码
* [B::Bytecode](https://metacpan.org/pod/B::Bytecode) - 将 Perl 脚本编译成可以稍后加载的字节码格式
* [Perf::ARM](https://metacpan.org/pod/Perf::ARM) - 在 Perl 中使用 ARM 指令
* [Asm::Z80::Table](https://metacpan.org/pod/Asm::Z80::Table) - 使用 Perl 汇编/反汇编所有 Z80 CPU 汇编指令
* [X86::Disasm](https://metacpan.org/pod/X86::Disasm) - 使用 Perl 反汇编 Intel x86 指令
* [Disassemble::X86](https://metacpan.org/pod/Disassemble::X86) - 反汇编 X86 指令的另一个库
* [X86::Udis86](https://metacpan.org/pod/X86::Udis86) - C Udis 反汇编程序的接口
* [Asm::X86](https://metacpan.org/pod/Asm::X86) - x86 兼容处理器的指令和寄存器列表，验证和转换指令和内存引用
* [ELF::Writer](https://metacpan.org/pod/ELF::Writer) - 写入和读取可执行的 ELF 文件 


## Other Awesome Lists

其他令人惊叹的列表可以在以下位置找到：

* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [fleveque/awesome-awesomes](https://github.com/fleveque/awesome-awesomes)
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* [t3chnoboy/awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome)

## How to contribute?

请阅读 [https://github.com/hachiojipm/awesome-perl/blob/master/CONTRIBUTING.md](https://github.com/hachiojipm/awesome-perl/blob/master/CONTRIBUTING.md)
