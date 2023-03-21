<div class="github-widget" data-repo="xen0l/awesome-dtrace"></div>
## Awesome DTrace [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精彩的 DTrace 书籍、文章、视频、工具和资源的精选列表.



- - -

## Learn

学习 DTrace 的推荐读物.

### Books

- [Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) - Illumos.org DTrace 指南.
- [DTrace: Dynamic Tracing in Oracle Solaris, Mac OS X, and FreeBSD](http://www.dtracebook.com/index.php/Main_Page) - 官方 DTrace 书.
- [Dynamic Tracing with DTrace & SystemTap](http://myaut.github.io/dtrace-stap-book/) - 一本书介绍了 DTrace 和 SystemTap.

### Other

- [dtrace(1m) man page](https://illumos.org/man/1m/dtrace) - DTrace 手册页.
- [DTrace cheatsheet](http://www.brendangregg.com/DTrace/DTrace-cheatsheet.pdf) - Brendan Gregg 的 DTrace 备忘单.
- [DTrace one-liners](http://www.brendangregg.com/DTrace/dtrace_oneliners.txt)  - DTrace 一个衬里. 方便的命令.
- [DTrace one-liners (FreeBSD)](https://wiki.freebsd.org/DTrace/One-Liners) - 来自 FreeBSD 的 DTrace 一个衬里.
- [DTrace QuickStart](http://www.tablespace.net/quicksheet/dtrace-quickstart.html) - DTrace 快速入门指南.
- [Using DTrace stories](https://github.com/NanXiao/using-dtrace-stories) - 使用DTrace调试系统故事的合集.
- [Advanced DTrace Tips, Tricks and Gotchas](http://dtrace.org/resources/bmc/dtrace_tips.pdf) - 使用 DTrace 的高级技巧集合.

## Articles

有关 DTrace 和实际用例的有趣文章.

### PID Provider

- [pid provider: entry probe](http://dtrace.org/blogs/brendan/2011/02/09/dtrace-pid-provider/) - DTrace PID 提供程序.
- [pid provider: entry arguments](http://dtrace.org/blogs/brendan/2011/02/11/dtrace-pid-provider-arguments/) - DTrace PID 提供程序参数.
- [pid provider: return](http://dtrace.org/blogs/brendan/2011/02/14/dtrace-pid-provider-return/) - DTrace PID 提供程序返回.
- [pid provider: instructions](http://dtrace.org/blogs/brendan/2011/02/16/dtrace-pid-provider-instructions/) - DTrace PID 提供程序说明.
- [pid provider: overhead](http://dtrace.org/blogs/brendan/2011/02/18/dtrace-pid-provider-overhead/) - DTrace PID 提供程序开销.
- [pid provider exposed](http://dtrace.org/blogs/ahl/2005/03/01/pid-provider-exposed/) - Adam Leventhal 的 PID 供应商内部结构.
- [When magic collides](http://dtrace.org/blogs/bmc/2011/03/09/when-magic-collides/) - Bryan Cantrill 深入探讨 PID 提供程序错误.

### USDT provider

- [Understanding DTrace ustack helpers](http://dtrace.org/blogs/dap/2013/11/20/understanding-dtrace-ustack-helpers/) - DTrace ustack 助手.
- [USDT Providers Redux](http://dtrace.org/blogs/dap/2011/12/13/usdt-providers-redux/) - 在自定义应用程序中构建 USDT 提供商的参考.

### Sysevent provider

- [DTrace sysevent provider](https://blogs.oracle.com/eschrock/entry/dtrace_sysevent_provider) - DTrace 的 Solaris/illumos 系统事件提供程序.

### Ruby and DTrace

- [Using DTrace to measure mutex contention in Ruby](https://vaneyckt.io/posts/using_dtrace_to_measure_mutex_contention_in_ruby/) - Ruby 中的互斥锁争用测量.

### Visualization methods

- [Flamegraphs](http://www.brendangregg.com/flamegraphs.html) - 配置软件的可视化，允许快速准确地识别最频繁的代码路径.
- [Heat Maps](http://brendangregg.com/heatmaps.html) - 热图允许可视化数据的三个维度，类似于将颜色用作维度的天气雷达图.

## Videos

关于 DTrace 的有趣视频.

- [DTrace review](https://www.youtube.com/watch?v=TgmA48fILq8) - Bryan Cantrill 解释了如何使用 DTrace 显着改进开发和实时系统的调试.

### dtrace.conf

- [dtrace.conf 2008](https://youtu.be/RvyP61WeFdM?list=PL8516982CBF9FADCC)
    - [NFSv3 and iSCSI providers](https://www.youtube.com/watch?v=sgBCz7bXkSo&index=4&list=PL8516982CBF9FADCC)
    - [DTrace for hardware](https://www.youtube.com/watch?v=1Bc2Dz8aS6s&list=PL8516982CBF9FADCC&index=5)
    - [Zones & DTrace](https://www.youtube.com/watch?v=D8_onK0pSvA&index=8&list=PL8516982CBF9FADCC)
    - [DTracing a Solaris build](https://www.youtube.com/watch?v=e55iXXYj-74&index=10&list=PL8516982CBF9FADCC)
    - [War Stories](https://www.youtube.com/watch?v=yR39YqVXQOM&index=11&list=PL8516982CBF9FADCC)
    - [Sun Benchmarks](https://www.youtube.com/watch?v=uK0DjEXo99w&list=PL8516982CBF9FADCC&index=12)
    - [Erlang](https://www.youtube.com/watch?v=PXIGE5GFAkE&index=13&list=PL8516982CBF9FADCC)
    - [Erlang (continued)](https://www.youtube.com/watch?v=YTNiCv9Za2Y&index=14&list=PL8516982CBF9FADCC)
    - [Instrumenting Adobe AIR](https://www.youtube.com/watch?v=4astU1_X5xM&index=15&list=PL8516982CBF9FADCC)
    - [HotSpot Runtime & Java](https://www.youtube.com/watch?v=8kdJDHqiByI&list=PL8516982CBF9FADCC&index=16)
    - [PostgreSQL: Looking Under the Hood with Solaris](https://www.youtube.com/watch?v=p5NKcxDny_4&list=PL8516982CBF9FADCC&index=17)
    - [PostgreSQL Provider](https://www.youtube.com/watch?v=SJykRURWgeU&list=PL8516982CBF9FADCC&index=18)
    - [Distributed DTrace](https://www.youtube.com/watch?v=oYK1kgFwxk4&index=19&list=PL8516982CBF9FADCC)
    - [Apple Port of DTrace](https://www.youtube.com/watch?v=OKSuox4eFrk&list=PL8516982CBF9FADCC&index=21)

- [dtrace.conf 2012](https://www.youtube.com/watch?v=l_7v7Fn7uMQ&list=PL973D48F273EB0360)
    - [DTrace State of the Union](https://www.youtube.com/watch?v=l_7v7Fn7uMQ&list=PL973D48F273EB0360)
    - [User-Level CTF](https://www.youtube.com/watch?v=0QF04ivO_WE&list=PL973D48F273EB0360&index=3)
    - [Dynamic Translators](https://www.youtube.com/watch?v=CqLcj0lVnp4&index=4&list=PL973D48F273EB0360)
    - [Clang Parser for DTrace](https://www.youtube.com/watch?v=6NqV_Uj8Ba4&index=7&list=PL973D48F273EB0360)
    - [Visualizations](https://www.youtube.com/watch?v=XD5hdaWnQM4&index=8&list=PL973D48F273EB0360)
    - [Visualizations, Enabling Toolchain for Seamless USDT](https://www.youtube.com/watch?v=3Sqa8mmtnMM&index=9&list=PL973D48F273EB0360)
    - [More Visualizations](https://www.youtube.com/watch?v=-B6u6wY3Iro&index=10&list=PL973D48F273EB0360)
    - [DTrace in Node.js](https://www.youtube.com/watch?v=0ZMvSh7lUdM&list=PL973D48F273EB0360&index=11)
    - [DTrace and Erlang](https://www.youtube.com/watch?v=4Si-7nAic2c&list=PL973D48F273EB0360&index=12)
    - [DTrace on Linux](https://www.youtube.com/watch?v=NElog3MvUC8&list=PL973D48F273EB0360&index=13)
    - [ZFS Provider](https://www.youtube.com/watch?v=m_V7yrrn49Y&index=14&list=PL973D48F273EB0360)
    - [DTrace on FreeBSD](https://www.youtube.com/watch?v=s5PpSiPfSNI&index=15&list=PL973D48F273EB0360)
    - [Barriers to DTrace Adoption](https://www.youtube.com/watch?v=P95LHZ-WOWw&index=16&list=PL973D48F273EB0360)

- [dtrace.conf 2016](https://www.joyent.com/about/events/2016/dtrace-conf)
    - [Introduction](https://player.vimeo.com/video/173346406)
    - [(Useful!) DTrace intro](https://player.vimeo.com/video/173346405)
    - [CTF Everywhere!](https://player.vimeo.com/video/173346404)
    - [Distributed DTrace](https://player.vimeo.com/video/173346403)
    - [DTracign Apps](https://player.vimeo.com/video/173346402)
    - [DTrace and JSON: Together at last!](https://player.vimeo.com/video/173346401)
    - [ASSERT() as a DTrace probe (and why I need some help)](https://player.vimeo.com/video/173346400)
    - [在 FreeBSD 中实现（或不实现）fds[]](https://player.vimeo.com/video/173346399)
    - [OpenDTrace](https://player.vimeo.com/video/173346398)
    - [DTrace Performance Improvements with Always-on Instrumentation](https://player.vimeo.com/video/173300658)
    - [D language improvements](https://player.vimeo.com/video/173300657)
    - [D Syntactic Sugar](https://player.vimeo.com/video/173300656)
    - [DTrace and Go](https://player.vimeo.com/video/173300655)
    - [DTrace and Postgres](https://player.vimeo.com/video/173300654)
    - [DTrace in the Zone](https://player.vimeo.com/video/173300653)
    - [DTrace ustack() performance improvements](https://player.vimeo.com/video/173300651)
    - [DTrace Exploitation](https://player.vimeo.com/video/173300650)

## Software

支持 DTrace 的软件列表.

### Programming languages

#### Erlang

- [Erlang](http://erlang.org/doc/apps/runtime_tools/DTRACE.html) - DTrace 和 Erlang/OTP.

#### Lua

- [lua-usdt](https://github.com/chrisa/lua-usdt) - Lua 的 Libusdt 绑定.

#### Node.js

- [node-dtrace-provider](https://github.com/chrisa/node-dtrace-provider) - 用于 Node.js 应用程序的本机 DTrace 探测器.

#### Perl

- [perl-Devel-DTrace-Provider](https://github.com/chrisa/perl-Devel-DTrace-Provider) - libusdt 的 Perl 包装器.

#### PHP

- [PHP](https://secure.php.net/manual/en/features.dtrace.dtrace.php) - 使用 PHP 和 DTrace.

#### Python

- [Python](https://www.jcea.es/artic/python_dtrace.htm) - Python 2.7.x 和 3.x 的 DTrace 补丁.
- [python-usdt](https://github.com/nshalman/python-usdt) - Python 的 Libusdt 绑定.

#### Ruby

- [Ruby](http://ruby-doc.org/core-2.3.1/doc/dtrace_probes_rdoc.html) - Ruby DTrace 探测器.
- [ruby-usdt](https://github.com/kevinykchan/ruby-usdt) - 用于 ruby​​ 应用程序的本机 DTrace 探测器.

### Databases

- [MySQL](https://dev.mysql.com/doc/refman/5.7/en/dba-dtrace-mysqld-ref.html) - MySQL DTrace 探测器.
- [PostgreSQL](https://www.postgresql.org/docs/current/static/dynamic-trace.html) - PostgreSQL DTrace 探测器.

### Webservers

- [mod_usdt](https://github.com/davepacheco/mod_usdt) - “httpd”DTrace 提供程序.

### Visualization

- [FlameGraph](https://github.com/brendangregg/FlameGraph) - 堆栈跟踪可视化工具.
- [node-stackvis](https://github.com/joyent/node-stackvis) - 堆栈跟踪可视化工具.

## Tools

- [DTraceToolkit](http://www.brendangregg.com/dtracetoolkit.html) - 有用的记录 DTrace 脚本的集合.
- [dtrace-cloud-tools](https://github.com/brendangregg/dtrace-cloud-tools) - 为 SmartOS/SmartDataCenter 云（基于 illumos）编写的 DTrace 工具.
- [pgsql tools](https://github.com/joyent/pgsqlstat) - 报告顶级 PostgreSQL 统计数据.
- [portsnoop](https://github.com/davepacheco/portsnoop) - 跟踪事件端口活动.
- [storage tools](https://github.com/richardelling/tools) - 报告 NFS、CIFS 和 iSCSI 统计数据.

## Community

- [Community site](http://dtrace.org) - DTrace 社区站点.
- [Mailing list](http://dtrace.org/blogs/mailing-list/) - DTrace 社区邮件列表.
- [FreeBSD DTrace mailing list](https://lists.freebsd.org/mailman/listinfo/freebsd-dtrace) - FreeBSD DTrace 社区邮件列表.
- [China DTrace](http://chinadtrace.org/) - 中文 DTrace 站点.

## Contributing

我们非常欢迎您的贡献！ 请参见 [contribution guidelines](https://github.com/xen0l/awesome-dtrace/blob/master/CONTRIBUTING.md) 第一的.
