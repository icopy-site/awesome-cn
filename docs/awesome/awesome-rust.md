## Awesome Rust [<img src="https://api.travis-ci.org/rust-unofficial/awesome-rust.svg?branch=master">](https://travis-ci.org/rust-unofficial/awesome-rust)

Rust代码和资源的精选列表.

如果您想贡献，请阅读 [this](https://github.com/rust-unofficial/awesome-rust/blob/master/CONTRIBUTING.md).

## Table of contents

- [Applications](#applications)
  - [Audio](#audio)
  - [Cryptocurrencies](#cryptocurrencies)
  - [Database](#database)
  - [Emulators](#emulators)
  - [Games](#games)
  - [Graphics](#graphics)
  - [Industrial automation](#industrial-automation)
  - [Operating systems](#operating-systems)
  - [Productivity](#productivity)
  - [Security tools](#security-tools)
  - [System tools](#system-tools)
  - [Text editors](#text-editors)
  - [Text processing](#text-processing)
  - [Utilities](#utilities)
  - [Video](#video)
  - [Virtualization](#virtualization)
  - [Window managers](#window-managers)
  - [Web](#web)
  - [Web Servers](#web-servers)
- [Development tools](#development-tools)
  - [Build system](#build-system)
  - [Debugging](#debugging)
  - [Deployment](#deployment)
  - [Embedded](#embedded)
  - [FFI](#ffi)
  - [IDEs](#ides)
  - [Pattern recognition](#pattern-recognition)
  - [Profiling](#profiling)
  - [Static analysis](#static-analysis)
  - [Testing](#testing)
  - [Transpiling](#transpiling)
- [Services](#services)
- [Libraries](#libraries)
  - [Artificial Intelligence](#artificial-intelligence)
      - [Genetic algorithms](#genetic-algorithms)
      - [Machine learning](#machine-learning)
  - [Astronomy](#astronomy)
  - [Asynchronous](#asynchronous)
  - [Audio](#audio-1)
  - [Authentication](#authentication)
  - [Automotive](#automotive)
  - [Bioinformatics](#bioinformatics)
  - [Caching](#caching)
  - [Cloud](#cloud)
  - [Command-line](#command-line)
  - [Compression](#compression)
  - [Computation](#computation)
  - [Concurrency](#concurrency)
  - [Configuration](#configuration)
  - [Cryptography](#cryptography)
  - [Database](#database-1)
  - [Data processing](#data-processing)
  - [Data structures](#data-structures)
  - [Data visualization](#data-visualization)
  - [Date and time](#date-and-time)
  - [Distributed systems](#distributed-systems)
  - [Email](#email)
  - [Encoding](#encoding)
  - [Filesystem](#filesystem)
  - [Game development](#game-development)
  - [Geospatial](#geospatial)
  - [Graphics](#graphics-1)
  - [Graph processing](#graph-processing)
  - [GUI](#gui)
  - [Image processing](#image-processing)
  - [Industrial automation](#industrial-automation)
  - [Language specification](#language-specification)
  - [Logging](#logging)
  - [Macro](#macro)
  - [Markup language](#markup-language)
  - [Mobile](#mobile)
  - [Network programming](#network-programming)
  - [Parser](#parser)
  - [Platform specific](#platform-specific)
  - [Scripting](#scripting)
  - [Template engine](#template-engine)
  - [Text processing](#text-processing-1)
  - [Text search](#text-search)
  - [Virtualization](#virtualization-1)
  - [Web programming](#web-programming)
  - [Peripherals](#peripherals)
- [Resources](#resources)
- [License](#license)

## Applications

也可以看看 [Rust — Production](https://www.rust-lang.org/production)（在生产中运行Rust的组织）.

* [andschwa/rust-genetic-algorithm](https://raw.githubusercontent.com/andschwa/rust-genetic-algorithm) - 用于学术基准问题的遗传算法 [<img src="https://api.travis-ci.org/andschwa/rust-genetic-algorithm.svg?branch=master">](https://travis-ci.org/andschwa/rust-genetic-algorithm)
* [azerupi/mdBook](https://raw.githubusercontent.com/rust-lang-nursery/mdBook) - 用于从markdown文件创建书籍的命令行实用程序 [<img src="https://api.travis-ci.org/azerupi/mdBook.svg?branch=master">](https://travis-ci.org/azerupi/mdBook)
* [bluejekyll/trust-dns](https://raw.githubusercontent.com/bluejekyll/trust-dns) -  DNS服务器 [<img src="https://api.travis-ci.org/bluejekyll/trust-dns.svg?branch=master">](https://travis-ci.org/bluejekyll/trust-dns)
* [ivanceras/diwata](https://raw.githubusercontent.com/ivanceras/diwata) -  postgresql的数据库管理工具 [<img src="https://api.travis-ci.org/ivanceras/diwata.svg">](https://travis-ci.org/ivanceras/diwata)
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) -  Kubernetes超轻型服务网.
* [danielrangel/rsign](https://bitbucket.org/danielrangel/rsign) [[rsign](https://crates.io/crates/rsign)]  - 一个简单的命令行工具，用于生成/签名/验证数字签名，旨在与Minisign兼容  [![Codeship Status for danielrangel/rsign](https://app.codeship.com/projects/60b28d80-7645-0135-4402-1639b58199d0/status?branch=master)](https://app.codeship.com/projects/244452)
* [darrint/device-blocker](https://github.com/darrint/device-blocker) - 通过阻止家庭Wifi路由器上的互联网访问，限制儿童各种移动设备的屏幕时间.
* [dlecan/generic-dns-update](https://raw.githubusercontent.com/dlecan/generic-dns-update) - 使用您的IP地址更新DNS区域文件的工具 [<img src="https://api.travis-ci.org/dlecan/generic-dns-update.svg?branch=master">](https://travis-ci.org/dlecan/generic-dns-update)
* [Factotum](https://raw.githubusercontent.com/snowplow/factotum) — [A system to programmatically run data pipelines](https://snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [<img src="https://api.travis-ci.org/snowplow/factotum.svg?branch=master">](https://travis-ci.org/snowplow/factotum)
* [fcsonline/drill](https://raw.githubusercontent.com/fcsonline/drill) - 受Ansible语法启发的HTTP负载测试应用程序 [<img src="https://api.travis-ci.org/fcsonline/drill.svg?branch=master">](https://travis-ci.org/fcsonline/drill)
* [Fractalide](https://github.com/fractalide/fractalide) - 简单的Rust微服务
* [habitat](https://www.habitat.sh) - 由...创建的工具 [Chef](https://www.chef.io/) 构建，部署和管理应用程序.
* [imjacobclark/Herd](https://github.com/imjacobclark/Herd) - 实验性HTTP负载测试应用程序
* [intecture/api](https://raw.githubusercontent.com/intecture/api) -  API驱动的服务器管理和配置工具 [<img src="https://api.travis-ci.org/intecture/api.svg?branch=master">](https://travis-ci.org/intecture/api)
* [jedisct1/flowgger](https://github.com/jedisct1/flowgger) - 快速，简单和轻量级的数据收集器
* [jwilm/alacritty](https://github.com/jwilm/alacritty) - 跨平台，GPU增强型终端仿真器
* [kbknapp/docli](https://raw.githubusercontent.com/kbknapp/docli-rs) - 用于管理DigitalOcean基础架构的命令行实用程序 [<img src="https://api.travis-ci.org/kbknapp/docli-rs.svg?branch=master">](https://travis-ci.org/kbknapp/docli-rs)
* [MaidSafe](https://maidsafe.net) - 一个分散的平台.
* [nicohman/eidolon](https://raw.githubusercontent.com/nicohman/eidolon) - 适用于linux和macosx的Steam和drm-free游戏注册表和启动器 [<img src="https://api.travis-ci.org/nicohman/eidolon.svg?branch=master">](https://travis-ci.org/nicohman/eidolon)
* [notty](https://github.com/withoutboats/notty) - 一种新型终端
* [Pijul](https://pijul.org) - 基于补丁的分布式版本控制系统
* [qmx/limonite](https://raw.githubusercontent.com/qmx/limonite) - 静态博客/网站生成器 [<img src="https://api.travis-ci.org/qmx/limonite.svg?branch=master">](https://travis-ci.org/qmx/limonite)
* [Sandstorm Collections App](https://github.com/sandstorm-io/collections-app)
* [Servo](https://github.com/servo/servo) - 原型Web浏览器引擎
* [Weld](https://raw.githubusercontent.com/serayuzgur/weld) - 完整的假REST API生成器 [<img src="https://api.travis-ci.org/serayuzgur/weld.svg">](https://travis-ci.org/serayuzgur/weld)

### Audio

* [indiscipline/zrtstr](https://raw.githubusercontent.com/indiscipline/zrtstr) - 一个命令行实用程序，用于检查立体声wav文件是否为人造立体声（即具有相同的通道）并将此类文件转换为单声道. [<img src="https://api.travis-ci.org/indiscipline/zrtstr.svg?branch=master">](https://travis-ci.org/indiscipline/zrtstr)

### Cryptocurrencies

* [nearprotocol/nearcore](https://github.com/nearprotocol/nearcore) - 针对低端移动设备的分散式智能合约平台.
* [ethaddrgen](https://raw.githubusercontent.com/Limeth/ethaddrgen) -  Rust生产的自定义以太坊虚荣心地址生成器 [<img src="https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master">](https://travis-ci.org/Limeth/ethaddrgen)
* [coinbase-pro-rs](https://raw.githubusercontent.com/inv2004/coinbase-pro-rs) -  Rust中的Coinbase pro客户端，支持sync / async / websocket [<img src="https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master">](https://travis-ci.org/inv2004/coinbase-pro-rs)
* [Grin](https://github.com/mimblewimble/grin/) -  MimbleWimble协议的演变
* [Substrate](https://github.com/paritytech/substrate) - 用Rust编写的通用模块化区块链模板
* [Polkadot](https://github.com/paritytech/polkadot) - 具有池化安全性的异构多链技术
* [Parity-Ethereum](https://github.com/paritytech/parity-ethereum) - 快速，轻便，强大的以太坊客户端
* [Parity-Bridge](https://github.com/paritytech/parity-bridge) - 在任何两个基于以太坊的网络之间架起桥梁
* [Parity-Bitcoin](https://raw.githubusercontent.com/paritytech/parity-bitcoin) - 奇偶校验比特币客户端 [<img src="https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master">](https://travis-ci.com/paritytech/parity-bitcoin)
* [Parity-Zcash](https://github.com/paritytech/parity-zcash) -  Rust实现Zcash协议
* [ArgusObserver/wagu](https://raw.githubusercontent.com/ArgusObserver/wagu) [[wagu](https://crates.io/crates/wagu)]  - 为任何加密货币生成钱包 [<img src="https://api.travis-ci.com/ArgusObserver/wagu.svg?branch=master">](https://api.travis-ci.com/ArgusObserver/wagu.svg?branch=master)
* [rust-cardano](https://github.com/input-output-hk/rust-cardano) -  Cardano原语，帮助程序和相关应用程序的Rust实现
* [cardano-cli](https://github.com/input-output-hk/cardano-cli) -  Cardano命令行界面（CLI）
* [Nervos CKB](https://github.com/nervosnetwork/ckb) -  Nervos CKB是一个公共许可区块链，是Nervos网络的常识层.
* [ChainX](https://github.com/chainx-org/ChainX) -  Polkadot上完全分散的链间加密资产管理.
* [hdwallet](https://github.com/jjyr/hdwallet) -  BIP-32 HD钱包相关的密钥派生工具.

### Database

* [indradb/indradb](https://raw.githubusercontent.com/indradb/indradb) - 基于Rust的图形数据库 [<img src="https://api.travis-ci.org/indradb/indradb.svg?branch=master">](https://travis-ci.org/indradb/indradb)
* [Mentat](https://mozilla.github.io/mentat/)   -  Project Mentat是一个持久的嵌入式知识库.  它主要依赖于DataScript和Datomic.  Mentat旨在成为一个灵活的关系（非键值，而不是面向文档）存储，使您可以轻松地描述，增长和重用您的域架构.
* [PumpkinDB](https://raw.githubusercontent.com/PumpkinDB/PumpkinDB) - 事件采购数据库引擎 [<img src="https://api.travis-ci.org/PumpkinDB/PumpkinDB.svg?branch=master">](https://travis-ci.org/PumpkinDB/PumpkinDB)
* [seppo0010/rsedis](https://raw.githubusercontent.com/seppo0010/rsedis) -  Rust中的Redis重新实现 [<img src="https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master">](https://travis-ci.org/seppo0010/rsedis)
* [ParityDB](https://github.com/paritytech/paritydb) - 快速可靠的数据库，针对读取操作进行了优化
* [tikv](https://raw.githubusercontent.com/tikv/tikv) -  Rust中的分布式KV数据库 [<img src="https://circleci.com/gh/tikv/tikv.svg?style=shield&circle-token=36bab0a8e43edb0941b31c38557d2d9d0d58f708">](https://circleci.com/gh/tikv/tikv)

### Emulators

也可以看看 [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

*准将64
  * [kondrak/rust64](https://raw.githubusercontent.com/kondrak/rust64) — [<img src="https://api.travis-ci.org/kondrak/rust64.svg?branch=master">](https://travis-ci.org/kondrak/rust64)
* 掌上游戏机
  * [Gekkio/mooneye-gb](https://raw.githubusercontent.com/Gekkio/mooneye-gb) — [<img src="https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master">](https://travis-ci.org/Gekkio/mooneye-gb)
  * [mvdnes/rboy](https://raw.githubusercontent.com/mvdnes/rboy) — [<img src="https://api.travis-ci.org/mvdnes/rboy.svg?branch=master">](https://travis-ci.org/mvdnes/rboy)
  * [NivenT/RGB](https://raw.githubusercontent.com/nivent/RGB) — [<img src="https://api.travis-ci.org/NivenT/RGB.svg?branch=master">](https://travis-ci.org/NivenT/RGB)
* NES
  * [iamsix/oxidenes](https://raw.githubusercontent.com/iamsix/oxidenes) — [<img src="https://api.travis-ci.org/iamsix/oxidenes.svg?branch=master">](https://travis-ci.org/iamsix/oxidenes)
  * [koute/pinky](https://raw.githubusercontent.com/koute/pinky) — [<img src="https://api.travis-ci.org/koute/pinky.svg?branch=master">](https://travis-ci.org/koute/pinky)
  * [pcwalton/sprocketnes](https://raw.githubusercontent.com/pcwalton/sprocketnes) — [<img src="https://api.travis-ci.org/pcwalton/sprocketnes.svg?branch=master">](https://travis-ci.org/pcwalton/sprocketnes)
* Playstation
  * [simias/rustation](https://raw.githubusercontent.com/simias/rustation) — [<img src="https://api.travis-ci.org/simias/rustation.svg?branch=master">](https://travis-ci.org/simias/rustation)
* ZX Spectrum
  * [pacmancoder/rustzx](https://raw.githubusercontent.com/pacmancoder/rustzx) — [<img src="https://api.travis-ci.org/pacmancoder/rustzx.svg?branch=master">](https://travis-ci.org/pacmancoder/rustzx)
*虚拟男孩
  * [emu-rs/rustual-boy](https://raw.githubusercontent.com/emu-rs/rustual-boy) — [<img src="https://api.travis-ci.org/emu-rs/rustual-boy.svg?branch=master">](https://travis-ci.org/emu-rs/rustual-boy)
*仿真器开发工具
  * SNES
    * [ioncodes/snesutilities](https://github.com/ioncodes/snesutilities) -  ROM分析仪/提取器

### Games

也可以看看 [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [lifthrasiir/angolmois-rust](https://raw.githubusercontent.com/lifthrasiir/angolmois-rust) - 支持BMS格式的简约音乐视频游戏 [<img src="https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master">](https://travis-ci.org/lifthrasiir/angolmois-rust)
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) - 推箱子实施
* [Zone of Control](https://raw.githubusercontent.com/ozkriff/zoc) - 基于回合制的六角策略游戏 [<img src="https://api.travis-ci.org/ozkriff/zoc.svg?branch=master">](https://travis-ci.org/ozkriff/zoc)
* [rhex](https://github.com/dpc/rhex) - 六角ascii roguelike
* [citybound](https://github.com/citybound/citybound) - 你值得拥有的城市
* [ozkriff/zemeroth](https://raw.githubusercontent.com/ozkriff/zemeroth) - 一个小型的基于回转的六角形策略游戏 [<img src="https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master">](https://travis-ci.org/ozkriff/zemeroth)
* [rsaarelm/magog](https://github.com/rsaarelm/magog) -  Rust的roguelike游戏
* [cristicbz/rust-doom](https://raw.githubusercontent.com/cristicbz/rust-doom) -  Doom的渲染器，可能会成为一款可玩的游戏 [<img src="https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master">](https://travis-ci.org/cristicbz/rust-doom)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) -  Rust中的Quake map渲染器
* [aleshaleksey/TGWM](https://raw.githubusercontent.com/aleshaleksey/TGWM) - 具有回转功能的RPG（正在进行中） [<img src="https://api.travis-ci.org/aleshaleksey/TGWM.svg?branch=master">](https://travis-ci.org/aleshaleksey/TGWM)
* [garkimasera/rusted-ruins](https://raw.githubusercontent.com/garkimasera/rusted-ruins) - 可扩展的开放世界流氓喜欢像素艺术的游戏 [<img src="https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master">](https://travis-ci.org/garkimasera/rusted-ruins)

### Graphics

* [Limeth/euclider](https://raw.githubusercontent.com/Limeth/euclider) - 实时4D CPU光线跟踪器 [<img src="https://api.travis-ci.org/Limeth/euclider.svg?branch=master">](https://travis-ci.org/Limeth/euclider)
* [ivanceras/svgbob](https://raw.githubusercontent.com/ivanceras/svgbob) - 将ASCII图转换为SVG图形 [<img src="https://api.travis-ci.org/ivanceras/svgbob.svg">](https://travis-ci.org/ivanceras/svgbob)
* [RazrFalcon/svgcleaner](https://github.com/RazrFalcon/svgcleaner) - 整理SVG图形
* [Twinklebear/tray_rust](https://raw.githubusercontent.com/Twinklebear/tray_rust) - 光线追踪器 [<img src="https://api.travis-ci.org/Twinklebear/tray_rust.svg">](https://travis-ci.org/Twinklebear/tray_rust)
* 图像处理
  * [spejss/Image-Processing-CLI-in-Rust](https://github.com/spejss/Image-Processing-CLI-in-Rust) - 用于处理图像的CLI，生成直方图. [![Build Status](https://api.travis-ci.org/spejss/Image-Processing-CLI-in-Rust.svg?branch=master)](https://travis-ci.org/spejss/Image-Processing-CLI-in-Rust)

### Industrial automation

* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) - 一个 [tokio](https://tokio.rs)-based [modbus](http://modbus.org) 图书馆. [![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)
* [locka99/opcua](https://github.com/locka99/opcua) - 纯锈 [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) 图书馆.
* [BiancoRoyal/modbus-iiot-rust](https://github.com/BiancoRoyal/modbus-iiot-rust) - 纯锈 [modbus](http://modbus.org) 没有或更少依赖的库. [![Build Status](https://api.travis-ci.org/BiancoRoyal/modbus-iiot-rust.svg?branch=master)](https://travis-ci.org/BiancoRoyal/modbus-iiot-rust)

### Operating systems

也可以看看 [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison).

* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) — [<img   src="https://api.travis-ci.org/redox-os/redox.svg?branch=master">](https://travis-ci.org/redox-os/redox)
* [thepowersgang/rust_os](https://raw.githubusercontent.com/thepowersgang/rust_os) — [<img src="https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master">](https://travis-ci.org/thepowersgang/rust_os)
* [tock/tock](https://github.com/tock/tock) - 基于Cortex-M的微控制器的安全嵌入式操作系统
* [nebulet/nebulet](https://github.com/nebulet/nebulet) - 实现在Ring 0中运行的WebAssembly“usermode”的微内核.

### Productivity

* [simeg/eureka](https://github.com/simeg/eureka) [[eureka](https://crates.io/crates/eureka)]  - 一个CLI工具，无需离开终端即可输入和存储您的想法

### Security tools

* [arvancloud/libinjection-rs](https://raw.githubusercontent.com/arvancloud/libinjection-rs) -  Rust绑定 [libinjection](https://raw.githubusercontent.com/client9/libinjection) [<img src="https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master">](https://travis-ci.org/arvancloud/libinjection-rs)
* [kpcyrd/badtouch](https://raw.githubusercontent.com/kpcyrd/badtouch) - 可编写脚本的网络身份验证破解程序 [<img src="https://api.travis-ci.org/kpcyrd/badtouch.svg?branch=master">](https://travis-ci.org/kpcyrd/badtouch)
* [kpcyrd/rshijack](https://raw.githubusercontent.com/kpcyrd/rshijack) -  tcp连接劫持者，生锈重写shijack [<img src="https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master">](https://travis-ci.org/kpcyrd/rshijack)
* [kpcyrd/sniffglue](https://raw.githubusercontent.com/kpcyrd/sniffglue) - 安全的多线程数据包嗅探器 [<img src="https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master">](https://travis-ci.org/kpcyrd/sniffglue)
* [kpcyrd/sn0int](https://raw.githubusercontent.com/kpcyrd/sn0int) - 半自动OSINT框架和包管理器 [<img src="https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master">](https://travis-ci.org/kpcyrd/sn0int)

### System tools

* [Aaronepower/tokei](https://raw.githubusercontent.com/Aaronepower/tokei) - 计算代码行数 [<img src="https://img.shields.io/travis/Aaronepower/tokei.svg">](https://travis-ci.org/Aaronepower/tokei)
* [brocode/fblog](https://raw.githubusercontent.com/brocode/fblog) - 小型命令行JSON日志查看器 [<img src="https://api.travis-ci.org/brocode/fblog.svg?branch=master">](https://travis-ci.org/brocode/fblog)
* [buster/rrun](https://raw.githubusercontent.com/buster/rrun) -  Linux的命令启动器，类似于gmrun  [<img src="https://api.travis-ci.org/buster/rrun.svg?branch=master">](https://travis-ci.org/buster/rrun)
* [cristianoliveira/funzzy](https://raw.githubusercontent.com/cristianoliveira/funzzy) - 灵感来自的可配置文件系统观察者 [entr](http://entrproject.org/) [<img src="https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master">](https://travis-ci.org/cristianoliveira/funzzy)
* [ddh](https://raw.githubusercontent.com/darakian/ddh) - 快速重复的文件查找器 [<img src="https://api.travis-ci.org/darakian/ddh.svg?branch=master">](https://travis-ci.org/darakian/ddh)
* [jhspetersson/fselect](https://raw.githubusercontent.com/jhspetersson/fselect) [[fselect](https://crates.io/crates/fselect)]  - 使用类似SQL的查询查找文件 [<img src="https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master">](https://travis-ci.org/jhspetersson/fselect)
* [k0pernicus/zou](https://raw.githubusercontent.com/k0pernicus/zou) - 下载加速器 [<img src="https://api.travis-ci.org/k0pernicus/zou.svg?branch=master">](https://travis-ci.org/k0pernicus/zou)
* [lotabout/rargs](https://raw.githubusercontent.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)]  -  xargs + awk，支持模式匹配 [<img src="https://api.travis-ci.org/lotabout/rargs.svg?branch=master">](https://travis-ci.org/lotabout/rargs)
* [lotabout/skim](https://raw.githubusercontent.com/lotabout/skim) - 纯锈的模糊取景器 [<img src="https://api.travis-ci.org/lotabout/skim.svg?branch=master">](https://travis-ci.org/lotabout/skim)
* [mitnk/cicada](https://raw.githubusercontent.com/mitnk/cicada) - 类似bash的Unix shell [<img src="https://api.travis-ci.org/mitnk/cicada.svg?branch=master">](https://travis-ci.org/mitnk/cicada)
* [mmstick/concurr](https://github.com/mmstick/concurr) - 替代GNU Parallel w /客户端 - 服务器架构
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) - 用于预览和安装Google字体的GTK3应用程序
* [mmstick/parallel](https://github.com/mmstick/parallel) - 重新实现GNU Parallel
* [mmstick/systemd-manager](https://github.com/mmstick/systemd-manager) - 使用GTK-rs用Rust编写的systemd服务管理器.
* [mmstick/tv-renamer](https://raw.githubusercontent.com/mmstick/tv-renamer) - 带有可选GTK3前端的电视连续剧重命名应用程序. [<img src="https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master">](https://travis-ci.org/mmstick/tv-renamer)
* [Peltoche/lsd](https://raw.githubusercontent.com/Peltoche/lsd) - 有很多漂亮的颜色和令人敬畏的图标的ls [<img src="https://api.travis-ci.org/Peltoche/lsd.svg?branch=master">](https://travis-ci.org/Peltoche/lsd)
* [ogham/exa](https://raw.githubusercontent.com/ogham/exa) - &#39;ls&#39;的替代品 [<img src="https://api.travis-ci.org/ogham/exa.svg?branch=master">](https://travis-ci.org/ogham/exa)
* [pop-os/debrep](https://github.com/pop-os/debrepbuild) - 用于构建和管理APT仓库的APT存储库工具
* [pop-os/popsicle](https://github.com/pop-os/popsicle) -  GTK3和CLI实用程序，用于并行闪存多个USB设备
* [pop-os/pop-recovery](https://github.com/pop-os/pop-recovery) - 用于在Pop！\ _ OS安装上更新恢复分区的实用程序.
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) - 使用CLI工具的Linux电源管理守护程序（DBus接口）.
* [Ralvke/logram](https://raw.githubusercontent.com/Ralvke/logram) - 将日志文件的更新推送到Telegram [<img src="https://api.travis-ci.org/Ralvke/logram.svg?branch=master">](https://travis-ci.org/Ralvke/logram)
* [redox-os/ion](https://raw.githubusercontent.com/redox-os/ion) - 下一代系统外壳 [<img src="https://api.travis-ci.org/redox-os/ion.svg?branch=master">](https://travis-ci.org/redox-os/ion)
* [sharkdp/bat](https://raw.githubusercontent.com/sharkdp/bat) - 带翅膀的猫（1）克隆. [<img src="https://api.travis-ci.org/sharkdp/bat.svg?branch=master">](https://travis-ci.org/sharkdp/bat)
* [sharkdp/fd](https://github.com/sharkdp/fd) - 一种简单，快速且用户友好的替代品. [![Build Status](https://api.travis-ci.org/sharkdp/fd.svg?branch=master)](https://travis-ci.org/sharkdp/fd)
* [sitkevij/hex](https://raw.githubusercontent.com/sitkevij/hex) - 彩色hexdump终端实用程序. [<img src="https://api.travis-ci.org/sitkevij/hex.svg?branch=master">](https://travis-ci.org/sitkevij/hex)
* [m4b/bingrep](https://raw.githubusercontent.com/m4b/bingrep) - 通过来自各种操作系统和体系结构的二进制文件，并对它们进行着色. [<img src="https://api.travis-ci.org/m4b/bingrep.svg?branch=master">](https://travis-ci.org/m4b/bingrep)
* [uutils/coreutils](https://raw.githubusercontent.com/uutils/coreutils) -  GNU coreutils的跨平台Rust重写 [<img src="https://api.travis-ci.org/uutils/coreutils.svg?branch=master">](https://travis-ci.org/uutils/coreutils)
* [watchexec](https://raw.githubusercontent.com/watchexec/watchexec) - 执行命令以响应文件修改 [<img src="https://api.travis-ci.org/mattgreen/watchexec.svg?branch=master">](https://travis-ci.org/mattgreen/watchexec)

### Text editors

* [gchp/iota](https://raw.githubusercontent.com/gchp/iota) - 一个简单的文本编辑器 [<img src="https://api.travis-ci.org/gchp/iota.svg?branch=master">](https://travis-ci.org/gchp/iota)
* [mathall/rim](https://raw.githubusercontent.com/mathall/rim) - 用Rust编写的类似Vim的文本编辑器 [<img src="https://api.travis-ci.org/mathall/rim.svg?branch=master">](https://travis-ci.org/mathall/rim)
* [Remacs](https://raw.githubusercontent.com/Wilfred/remacs) - 一个由社区驱动的Emacs到Rust的端口. [<img src="https://api.travis-ci.org/Wilfred/remacs.svg?branch=master">](https://travis-ci.org/Wilfred/remacs)
* [xi-editor](https://github.com/xi-editor/xi-editor) - 一个现代编辑器，后端用Rust编写.
* [xray](https://raw.githubusercontent.com/atom/xray) - 实验性的下一代基于电子的文本编辑器. [<img src="https://api.travis-ci.org/atom/xray.svg?branch=master">](https://travis-ci.org/atom/xray)

### Text processing
* [BurntSushi/ripgrep](https://raw.githubusercontent.com/BurntSushi/ripgrep) - 结合了Silver Searcher的可用性和grep的原始速度 [<img src="https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master">](https://travis-ci.org/BurntSushi/ripgrep)
* [chmln/sd](https://raw.githubusercontent.com/chmln/sd) [[sd](https://crates.io/crates/sd)] -Intuitive查找和替换CLI [<img src="https://api.travis-ci.org/chmln/sd.svg?branch=master">](https://travis-ci.org/chmln/sd)
* [BurntSushi/xsv](https://raw.githubusercontent.com/BurntSushi/xsv) - 快速CSV命令行工具（切片，索引，选择，搜索，采样等） [<img src="https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master">](https://travis-ci.org/BurntSushi/xsv)
* [TankerHQ/ruplacer](https://raw.githubusercontent.com/TankerHQ/ruplacer) - 查找并替换源文件中的文本 [<img img src="https://api.travis-ci.org/TankerHQ/ruplacer.svg?branch=master">](https://travis-ci.org/TankerHQ/ruplacer)
* [lavifb/todo_r](https://raw.githubusercontent.com/lavifb/todo_r) - 使用一个命令查找所有TODO笔记！ [<img src="https://api.travis-ci.org/lavifb/todo_r.svg?branch=master">](https://travis-ci.org/lavifb/todo_r)
* [whitfin/runiq](https://github.com/whitfin/runiq) - 从未排序的输入中过滤重复行的有效方法.
* [whitfin/bytelines](https://github.com/whitfin/bytelines) - 将输入行读取为字节片以实现高效率.

### Utilities

* [brycx/checkpwn](https://github.com/brycx/checkpwn) -  A Have I Pwned（HIBP）命令行实用工具，可让您轻松检查受损帐户和密码.
* [evansmurithi/cloak](https://raw.githubusercontent.com/evansmurithi/cloak) - 命令行OTP（一次性密码）身份验证器应用程序. [<img src="https://api.travis-ci.com/evansmurithi/cloak.svg?branch=master">](https://travis-ci.com/evansmurithi/cloak) [<img src="https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true">](https://ci.appveyor.com/project/evansmurithi/cloak)
* [myfreeweb/freepass](https://raw.githubusercontent.com/myfreeweb/freepass) - 高级用户的免费密码管理器. [<img src="https://api.travis-ci.org/myfreeweb/freepass.svg?branch=master">](https://travis-ci.org/myfreeweb/freepass)
* [arthrp/quick-skeleton](https://raw.githubusercontent.com/arthrp/quick-skeleton) - 项目脚手架工具，类似于Yeoman和Slush. [<img src="https://api.travis-ci.org/arthrp/quick-skeleton.svg?branch=master">](https://travis-ci.org/arthrp/quick-skeleton)
* [yaa110/rubigo](https://raw.githubusercontent.com/yaa110/rubigo) -  Golang依赖工具和包管理器，用Rust编写 [<img src="https://api.travis-ci.org/yaa110/rubigo.svg?branch=master">](https://travis-ci.org/yaa110/rubigo)
* [whitfin/s3-concat](https://github.com/whitfin/s3-concat) - 使用灵活模式远程连接Amazon S3文件的命令行工具.
* [whitfin/s3-meta](https://github.com/whitfin/s3-meta) - 用于收集有关Amazon S3存储桶的元数据的命令行工具.
* [amar-laksh/workstation](https://github.com/amar-laksh/workstation) - 一个命令行工具，可以帮助您管理您的工作站，让您远离屏幕，当您不在OPENCV的其他地方时锁定您的屏幕！
* [aleshaleksey/AZDice](https://raw.githubusercontent.com/aleshaleksey/AZDice) - 用于桌面家庭酿酒师的骰子滚动成功分配发生器. [<img src="https://api.travis-ci.org/aleshaleksey/AZDice.svg?branch=master">](https://travis-ci.org/aleshaleksey/AZDice)

### Video

* [yuvadm/slingr](https://raw.githubusercontent.com/yuvadm/slingr) - 一个简单的CLI，用于通过本地网络将媒体文件流式传输到UPnP媒体渲染器 [<img src="https://api.travis-ci.org/yuvadm/slingr.svg?branch=master">](https://travis-ci.org/yuvadm/slingr)

### Virtualization

* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) - 用于容器工作负载的轻量级虚拟机  [Firecracker Microvm](https://firecracker-microvm.github.io/)
* [oracle/railcar](https://github.com/oracle/railcar) -  Rust中类似Docker的容器OCI运行时实现 [![wercker status](https://app.wercker.com/status/730e874772dc02c6005f4ae4e42b0ca4/s/master "wercker status")](https://app.wercker.com/applications/59696a02ee70670100155ae2 )
* [tailhook/vagga](https://raw.githubusercontent.com/tailhook/vagga) - 没有守护进程的容器化工具 [<img src="https://api.travis-ci.org/tailhook/vagga.svg?branch=master">](https://travis-ci.org/tailhook/vagga)

### Window managers

* [way-cooler/way-cooler](https://raw.githubusercontent.com/way-cooler/way-cooler) - 可定制的Wayland合成器（窗口管理器） [<img src="https://api.travis-ci.org/way-cooler/way-cooler.svg?branch=master">](https://travis-ci.org/way-cooler/way-cooler)

### Web

* [Plume-org/Plume](https://raw.githubusercontent.com/Plume-org/Plume) -  ActivityPub联合博客应用程序 [<img src="https://api.travis-ci.org/Plume-org/Plume.svg?branch=master">](https://travis-ci.org/Plume-org/Plume)
* [rustlang-cn/ruster](https://raw.githubusercontent.com/rustlang-cn/ruster) — online community in rust for rust community [<img src="https://api.travis-ci.org/rustlang-cn/ruster.svg?branch=master">](https://travis-ci.org/rustlang-cn/ruster)


### Web Servers

* [thecoshman/http](https://raw.githubusercontent.com/thecoshman/http) - 托管这些东西请 - 一个基本的http服务器，用于快速简单地托管文件夹 [<img src="https://api.travis-ci.org/thecoshman/http.svg?branch=master">](https://travis-ci.org/thecoshman/http)
- [svenstaro/miniserve](https://raw.githubusercontent.com/svenstaro/miniserve) - 一个小型，独立的跨平台CLI工具，允许您只需抓取二进制文件并通过HTTP提供一些文件 [<img src="https://api.travis-ci.org/svenstaro/miniserve.svg?branch=master">](https://travis-ci.org/svenstaro/miniserve)
- [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) - 简单的静态http服务器

## Development tools

* [Clippy](https://raw.githubusercontent.com/rust-lang/rust-clippy) [[clippy](https://crates.io/crates/clippy)]  -  Rust lints [<img src="https://api.travis-ci.org/rust-lang/rust-clippy.svg?branch=master">](https://travis-ci.org/rust-lang/rust-clippy)
* [clog-tool/clog-cli](https://raw.githubusercontent.com/clog-tool/clog-cli) - 从git元数据生成更改日志（[conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [<img src="https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master">](https://travis-ci.org/clog-tool/clog-cli)
* [dan-t/rusty-tags](https://raw.githubusercontent.com/dan-t/rusty-tags) - 为货物项目及其所有依赖项创建ctags / etags [<img src="https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master">](https://travis-ci.org/dan-t/rusty-tags)
* [frewsxcv/crate-deps](https://github.com/frewsxcv/crate-deps) - 为crates.io上托管的板条箱生成依赖图的图像
* [git-journal](https://raw.githubusercontent.com/saschagrunert/git-journal/) -  Git Commit消息和Changelog生成框架 [<img src="https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master">](https://travis-ci.org/saschagrunert/git-journal)
* [rust-lang-nursery/rustfix](https://raw.githubusercontent.com/rust-lang-nursery/rustfix)  - 自动应用rustc提出的建议 [<img src="https://api.travis-ci.org/killercup/rustfix.svg?branch=master">](https://travis-ci.org/killercup/rustfix)
* [just](https://raw.githubusercontent.com/casey/just) - 项目特定任务的便捷命令运行程序 [<img src="https://api.travis-ci.org/casey/just.svg?branch=master">](https://travis-ci.org/casey/just)
* [Module Linker](https://fiatjaf.alhur.es/module-linker/) - <a>在GitHub</a>中添加` <a>`链接到`mod`，`use`和`extern crate`语句中的引用的</a>扩展<a>.</a>
* [ptags](https://github.com/dalance/ptags) - 用于git存储库的并行通用ctags包装器 [![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
* [Racer](https://raw.githubusercontent.com/racer-rust/racer) -  Rust的代码完成 [<img src="https://api.travis-ci.org/phildawes/racer.svg?branch=master">](https://travis-ci.org/phildawes/racer)
* [rustfmt](https://raw.githubusercontent.com/rust-lang/rustfmt) -  Rust代码格式化程序 [<img src="https://api.travis-ci.org/rust-lang/rustfmt.svg?branch=master">](https://travis-ci.org/rust-lang/rustfmt)
* [Rustup](https://raw.githubusercontent.com/rust-lang/rustup.rs) -  Rust工具链安装程序 [<img src="https://api.travis-ci.org/rust-lang/rustup.rs.svg?branch=master">](https://travis-ci.org/rust-lang/rustup.rs)
* [Rust Language Server](https://github.com/rust-lang/rls) - 在后台运行的服务器，为IDE，编辑器和其他工具提供有关Rust程序的信息
* [artifact](https://github.com/vitiral/artifact) - 为开发人员设计的设计doc工具 [![Build Status](https://api.travis-ci.org/vitiral/artifact.svg?branch=master)](https://travis-ci.org/vitiral/artifact)
* [semantic-rs](https://raw.githubusercontent.com/semantic-rs/semantic-rs) - 自动包装箱出版 [<img src="https://api.travis-ci.org/semantic-rs/semantic-rs.svg?branch=master">](https://travis-ci.org/semantic-rs/semantic-rs)
* [fw](https://raw.githubusercontent.com/brocode/fw) - 工作空间生产力助推器 [<img src="https://api.travis-ci.org/brocode/fw.svg?branch=master">](https://travis-ci.org/brocode/fw)
* [tinyrick](https://github.com/mcandre/tinyrick) 一个基本的任务依赖工具，强调Rust函数优于原始shell命令.

### Build system

* [Cargo](https://crates.io/) -  Rust包管理器
  * [BurntSushi/cargo-benchcmp](https://raw.githubusercontent.com/BurntSushi/cargo-benchcmp) [[cargo-benchcmp](https://crates.io/crates/cargo-benchcmp)]  - 用于比较Rust微基准测试的实用程序 [<img src="https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master">](https://travis-ci.org/BurntSushi/cargo-benchcmp)
   * [cardoe/cargo-bitbake](https://raw.githubusercontent.com/cardoe/cargo-bitbake) [[cargo-bitbake](https://crates.io/crates/cargo-bitbake)]  - 货物延伸，可以利用meta-rust中的类生成BitBake配方 [<img src="https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master">](https://travis-ci.org/cardoe/cargo-bitbake)
  * [rsolomo/cargo-check](https://raw.githubusercontent.com/rsolomo/cargo-check) [[cargo-check](https://crates.io/crates/cargo-check)]  - 一个围绕`cargo rustc  -  -Zno-trans`的包装器，如果你只需要正确检查，它可以帮助你运行更快的编译 [<img src="https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master">](https://travis-ci.org/rsolomo/cargo-check)
  * [kbknapp/cargo-count](https://raw.githubusercontent.com/kbknapp/cargo-count) [[cargo-count](https://crates.io/crates/cargo-count)]  - 列出有关货物项目的源代码计数和详细信息，包括不安全的统计数据 [<img src="https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-count)
  * [mmstick/cargo-deb](https://raw.githubusercontent.com/mmstick/cargo-deb) - 生成二进制Debian软件包 [<img src="https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master">](https://travis-ci.org/mmstick/cargo-deb)
  * [pwoolcoc/cargo-do](https://raw.githubusercontent.com/pwoolcoc/cargo-do) [[cargo-do](https://crates.io/crates/cargo-do)]  - 连续运行多个货物命令 [<img src="https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master">](https://travis-ci.org/pwoolcoc/cargo-do)
  * [maxsnew/cargo-dot](https://raw.githubusercontent.com/maxsnew/cargo-dot) - 生成货物项目依赖关系的图表 [<img src="https://api.travis-ci.org/maxsnew/cargo-dot.svg?branch=master">](https://travis-ci.org/maxsnew/cargo-dot)
  * [cardoe/cargo-ebuild](https://raw.githubusercontent.com/cardoe/cargo-ebuild) [[cargo-ebuild](https://crates.io/crates/cargo-ebuild)]  - 货物扩展，可以使用树内eclass生成ebuild [<img src="https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master">](https://travis-ci.org/cardoe/cargo-ebuild)
  * [killercup/cargo-edit](https://raw.githubusercontent.com/killercup/cargo-edit) [[cargo-edit](https://crates.io/crates/cargo-edit)]  - 允许您通过从命令行读取/写入Cargo.toml文件来添加和列出依赖项 [<img src="https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master">](https://travis-ci.org/killercup/cargo-edit)
  * [Ralvke/cargo-find](https://raw.githubusercontent.com/Ralvke/cargo-find) [[cargo-find](https://crates.io/crates/cargo-find)<sup>不推荐使用</sup> - 从命令行查找包 [<img src="https://api.travis-ci.org/Ralvke/cargo-find.svg?branch=master">](https://travis-ci.org/Ralvke/cargo-find)
  * [kbknapp/cargo-graph](https://raw.githubusercontent.com/kbknapp/cargo-graph) [[cargo-graph](https://crates.io/crates/cargo-graph)]  - 更新了“cargo-dot”的分支，附加功能 [<img src="https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-graph)
  * [imp/cargo-info](https://gitlab.com/imp/cargo-info) [[cargo-info](https://crates.io/crates/cargo-info)]  - 从命令行查询crates.io中的crates详细信息 [<img src="https://api.travis-ci.org/imp/cargo-info.svg?branch=master">](https://travis-ci.org/imp/cargo-info)
  * [sagiegurari/cargo-make](https://raw.githubusercontent.com/sagiegurari/cargo-make) [[cargo-make](https://crates.io/crates/cargo-make)]  -  Rust任务运行器和构建工具. [<img src="https://api.travis-ci.org/sagiegurari/cargo-make.svg?branch=master">](https://travis-ci.org/sagiegurari/cargo-make)
  * [regexident/cargo-modules](https://raw.githubusercontent.com/regexident/cargo-modules) [[cargo-modules](https://crates.io/crates/cargo-modules)]  - 一个货物插件，用于显示箱子模块的树状概览. [<img src="https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master">](https://travis-ci.org/regexident/cargo-modules)
  * [imp/cargo-multi](https://gitlab.com/imp/cargo-multi) [[cargo-multi](https://crates.io/crates/cargo-multi)]  - 在多个板条箱上运行指定的货物命令 [<img src="https://api.travis-ci.org/imp/cargo-multi.svg?branch=master">](https://travis-ci.org/imp/cargo-multi)
  * [kbknapp/cargo-outdated](https://raw.githubusercontent.com/kbknapp/cargo-outdated) [[cargo-outdated](https://crates.io/crates/cargo-outdated)]  - 当较新版本的Rust依赖项可用或已过期时显示 [<img src="https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-outdated)
  * [sunng87/cargo-release](https://raw.githubusercontent.com/sunng87/cargo-release) [[cargo-release](https://crates.io/crates/cargo-release)]  - 用于发布git管理的货物项目，构建，标记，发布，文档和推送的工具 [<img src="https://api.travis-ci.org/sunng87/cargo-release.svg?branch=master">](https://travis-ci.org/sunng87/cargo-release)
  * [DanielKeep/cargo-script](https://raw.githubusercontent.com/DanielKeep/cargo-script) [[cargo-script](https://crates.io/crates/cargo-script)]  - 让人们快速轻松地运行Rust“脚本”，可以利用Cargo的包生态系统 [<img src="https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master">](https://travis-ci.org/DanielKeep/cargo-script)
  * [greyblake/cargo-testify](https://raw.githubusercontent.com/greyblake/cargo-testify) [[cargo-testify](https://crates.io/crates/cargo-testify)]  - 监视文件更改，运行测试并通过友好的操作系统通知通知结果 [<img src="https://api.travis-ci.org/greyblake/cargo-testify.svg?branch=master">](https://travis-ci.org/greyblake/cargo-testify)
  * [nabijaczleweli/cargo-update](https://raw.githubusercontent.com/nabijaczleweli/cargo-update) [[cargo-update](https://crates.io/crates/cargo-update)]  -  cargo子命令，用于检查和应用已安装可执行文件的更新 [<img src="https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master">](https://travis-ci.org/nabijaczleweli/cargo-update)
  * [passcod/cargo-watch](https://raw.githubusercontent.com/passcod/cargo-watch) [[cargo-watch](https://crates.io/crates/cargo-watch)]  - 货源在货源变更时编制项目的实用程序 [<img src="https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master">](https://travis-ci.org/passcod/cargo-watch)
  * [liuchong/cargo-x](https://raw.githubusercontent.com/liuchong/cargo-x) - 执行自定义命令的非常简单的第三方货物子命令 [<img src="https://api.travis-ci.org/liuchong/cargo-x.svg?branch=master">](https://travis-ci.org/liuchong/cargo-x)
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) - 在源代码中展开宏
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) - 用于将Rust库集成到CMake项目中
  * [SiegeLord/RustCMake](https://raw.githubusercontent.com/SiegeLord/RustCMake) - 一个示例项目，显示了使用带有Rust的CMake [<img src="https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master">](https://travis-ci.org/SiegeLord/RustCMake)
* Github行动
  * [icepuma/rust-github-actions](https://github.com/icepuma/rust-github-actions) - 生锈github行动
* Webpack
  * [Ralvke/rust-loader](https://github.com/Ralvke/rust-loader) -  Webpack Rust loader（wasm）

### Debugging

* GDB
  * [rust-gdb](https://github.com/rust-lang/rust/blob/master/src/etc/rust-gdb)
  * [gdbgui](https://raw.githubusercontent.com/cs01/gdbgui) - 基于浏览器的gdb前端，用于调试C，C ++，Rust和go. [<img src="https://api.travis-ci.org/cs01/gdbgui.svg?branch=master">](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * [lldb_batchmode.py](https://github.com/rust-lang/rust/blob/master/src/etc/lldb_batchmode.py) - 允许以类似于GDB批处理模式的方式使用LLDB.
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) -  LLDB扩展名 [Visual Studio Code](https://code.visualstudio.com/).
* rr
  * [rr](https://rr-project.org/) -  rr是一个轻量级工具，用于记录和重放应用程序的执行

### Deployment

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) - 使用musl-libc和musl-gcc编译静态Rust二进制文件的Docker镜像，以及有用的C库的静态版本
  * [kpcyrd/mini-docker-rust](https://raw.githubusercontent.com/kpcyrd/mini-docker-rust) - 非常小的防锈码头图像的示例项目 [<img src="https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master">](https://travis-ci.org/kpcyrd/mini-docker-rust)
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) - 多个版本（带有musl工具）Rust Docker图像
  * [messense/rust-musl-cross](https://raw.githubusercontent.com/messense/rust-musl-cross) - 用于使用musl-cross编译静态Rust二进制文件的Docker镜像 [<img src="https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master">](https://travis-ci.org/messense/rust-musl-cross)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) -  Rust Docker官方图片
* Google App Engine
  * [DenisKolodin/rust-app-engine](https://github.com/DenisKolodin/rust-app-engine) -  App Engine Rust样板
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) -  Heroku上Rust应用程序的buildpack

### Embedded

[Rust Embedded](https://rust-embedded.org/)

*交叉编译
  * [japaric/rust-cross](https://raw.githubusercontent.com/japaric/rust-cross) - 关于交叉编译Rust程序需要了解的所有内容 [<img src="https://api.travis-ci.org/japaric/rust-cross.svg?branch=master">](https://travis-ci.org/japaric/rust-cross)
  * [japaric/xargo](https://raw.githubusercontent.com/japaric/xargo) - 轻松地将Rust程序交叉编译为自定义裸机目标，如ARM Cortex-M [<img src="https://api.travis-ci.org/japaric/xargo.svg?branch=master">](https://travis-ci.org/japaric/xargo)
* Raspberry Pi
  * [Ogeon/rust-on-raspberry-pi](https://github.com/Ogeon/rust-on-raspberry-pi) - 有关如何为Raspberry Pi交叉编译Rust项目的说明.

### FFI

也可以看看 [Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) （使用其他语言的Rust编写的代码的示例集合）和 [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples).

* C
  * [rlhunt/cbindgen](https://raw.githubusercontent.com/eqrion/cbindgen)   - 从Rust源文件生成C头文件.  用于Gecko for WebRender [<img src="https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master">](https://travis-ci.org/eqrion/cbindgen)
  * [Sean1708/rusty-cheddar](https://raw.githubusercontent.com/Sean1708/rusty-cheddar) - 从Rust源文件生成C头文件 [<img src="https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master">](https://travis-ci.org/Sean1708/rusty-cheddar)
* C ++
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) -  Rust绑定生成器
* Erlang
  * [hansihe/Rustler](https://raw.githubusercontent.com/hansihe/Rustler) - 用于创建Erlang NIF功能的安全Rust桥 [<img src="https://api.travis-ci.org/hansihe/rustler.svg?branch=master">](https://travis-ci.org/hansihe/rustler)
*哈斯克尔
  * [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) - 弥合Haskell和Rust之间的差距
  * [mgattozzi/haskellrs](https://github.com/mgattozzi/haskellrs) - 在Haskell FFI示例中生锈
  * [mgattozzi/rushs](https://github.com/mgattozzi/rushs) -  Rust FFI示例中的Haskell
* Java
  * [bennettanderson/rjni](https://raw.githubusercontent.com/benanders/rjni) - 使用Rust的Java [<img src="https://api.travis-ci.org/bennettanderson/rjni.svg?branch=master">](https://travis-ci.org/GravityScore/RustJNI)
  * [drrb/java-rust-example](https://raw.githubusercontent.com/drrb/java-rust-example) - 使用Java中的Rust [<img src="https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master">](https://travis-ci.org/drrb/java-rust-example)
  * [kud1ing/rucaja](https://raw.githubusercontent.com/kud1ing/rucaja) [[rucaja](https://crates.io/crates/rucaja)]  - 使用Rust的Java [<img src="https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master">](https://travis-ci.org/kud1ing/rucaja)
  * [prevoty/jni-rs](https://raw.githubusercontent.com/jni-rs/jni-rs) [[jni](https://crates.io/crates/jni)]  - 使用Java中的Rust [<img src="https://api.travis-ci.org/prevoty/jni-rs.svg?branch=master">](https://travis-ci.org/prevoty/jni-rs)
  * [rawrasaur/rust-jdbc](https://raw.githubusercontent.com/rawrasaur/rust-jdbc) - 使用Rust的JDBC [<img src="https://api.travis-ci.org/rawrasaur/rust-jdbc.svg?branch=master">](https://travis-ci.org/rawrasaur/rust-jdbc)
  * [sfackler/rust-jni-sys](https://raw.githubusercontent.com/sfackler/rust-jni-sys) [[jni-sys](https://crates.io/crates/jni-sys)]  - 与jni.h对应的Rust定义 [<img src="https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master">](https://travis-ci.org/sfackler/rust-jni-sys)
* Lua
  * [jcmoyer/rust-lua53](https://raw.githubusercontent.com/jcmoyer/rust-lua53) -  Lua 5.3 Rust的绑定 [<img src="https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master">](https://travis-ci.org/jcmoyer/rust-lua53)
  * [kballard/rust-lua](https://raw.githubusercontent.com/kballard/rust-lua) - 安全Rust绑定到Lua 5.1 [<img src="https://api.travis-ci.org/kballard/rust-lua.svg">](https://travis-ci.org/kballard/rust-lua)
  * [tickbh/td_rlua](https://raw.githubusercontent.com/tickbh/td_rlua) - 适用于Rust的零成本高级lua 5.3包装 [<img src="https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master">](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua](https://raw.githubusercontent.com/tomaka/hlua) - 与Lua接口的Rust库 [<img src="https://api.travis-ci.org/tomaka/hlua.svg?branch=master">](https://travis-ci.org/tomaka/hlua)
* mruby
  * [anima-engine/mrusty](https://raw.githubusercontent.com/anima-engine/mrusty) -  Rust的mruby安全绑定 [<img src="https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master">](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [neon-bindings/neon](https://raw.githubusercontent.com/neon-bindings/neon) - 使用Node.js中的Rust [<img src="https://api.travis-ci.org/neon-bindings/neon.svg?branch=master">](https://travis-ci.org/neon-bindings/neon)
*目标-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) -  Objective-C运行时绑定和Rust的包装器
* Perl
  * [vickenty/mi-rust](https://github.com/vickenty/mi-rust) - 添加对M :: I的支持，用于构建Cargo模块
  * [vickenty/perl-xs](https://raw.githubusercontent.com/vickenty/perl-xs) - 使用Rust创建Perl XS模块 [<img src="https://api.travis-ci.org/vickenty/perl-xs.svg?branch=master">](https://travis-ci.org/vickenty/perl-xs)
* Python
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) -  python setuptools的扩展，允许您以最便携的方式在Python轮中分发动态链接库.
  * [dgrunwald/rust-cpython](https://raw.githubusercontent.com/dgrunwald/rust-cpython) -  Python绑定 [<img src="https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master">](https://travis-ci.org/dgrunwald/rust-cpython)
  * [PyO3/PyO3](https://raw.githubusercontent.com/PyO3/PyO3) -  Python解释器的Rust绑定 [<img src="https://api.travis-ci.org/PyO3/pyo3.svg?branch=master">](https://travis-ci.org/PyO3/pyo3)
* R.
  * [rustr/rustr](https://raw.githubusercontent.com/rustr/rustr) - 使用R中的Rust，并在Rust中使用R. [<img src="https://api.travis-ci.org/rustr/rustr.svg?branch=master">](https://travis-ci.org/rustr/rustr)
* Ruby
  * [d-unseductable/ruru](https://raw.githubusercontent.com/d-unseductable/ruru) - 用Rust编写的原生Ruby扩展 [<img src="https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master">](https://travis-ci.org/d-unseductable/ruru)
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) - 用Rust编写的原生Ruby扩展，反之亦然 [![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  * [tildeio/helix](https://raw.githubusercontent.com/tildeio/helix) - 在Rust中编写Ruby类 [<img src="https://api.travis-ci.org/tildeio/helix.svg?branch=master">](https://travis-ci.org/tildeio/helix)
*网络组装
  * [rustwasm/wasm-pack](https://raw.githubusercontent.com/rustwasm/wasm-pack) - ：package :: sparkles：打包wasm并将其发布到npm！ [<img src="https://api.travis-ci.org/rustwasm/wasm-pack.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-packn)
  * [rustwasm/wasm-bindgen](https://raw.githubusercontent.com/rustwasm/wasm-bindgen) - 促进wasm模块和JS之间高级交互的项目. [<img src="https://api.travis-ci.org/rustwasm/wasm-bindgen.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-bindgen)

### IDEs

也可以看看 [Are we (I)DE yet?](https://areweideyet.com/) 和 [Rust Tools](https://www.rust-lang.org/tools).

  * [Atom](https://atom.io/)
    * [zargony/atom-language-rust](https://github.com/zargony/atom-language-rust)
  * [Eclipse](https://www.eclipse.org/)
    * [RustDT](https://raw.githubusercontent.com/RustDT/RustDT) — [<img src="https://api.travis-ci.org/RustDT/RustDT.svg?branch=master">](https://travis-ci.org/RustDT/RustDT)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [rust-mode](https://github.com/rust-lang/rust-mode) -  Rust Major Mode
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) -  Rust支持 [Flycheck](https://github.com/flycheck/flycheck)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) - 自动完成（另见 [company](https://company-mode.github.io) 和 [auto-complete](https://github.com/auto-complete/auto-complete))
    * [lsp-rust](https://github.com/emacs-lsp/lsp-rust) - 添加rls支持 [lsp-mode](https://github.com/emacs-lsp/lsp-mode)
  * [gitpod.io](https://gitpod.io) - 基于Rust语言服务器的完整Rust支持的在线IDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) 自版本3.22.2起，对生锈和货物的原生支持
  * [Kakoune](http://kakoune.org/)
    * [ul/kak-lsp](https://github.com/ul/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/)  客户.  在Rust中实现并支持rls开箱即用.
  * [NetBeans](https://netbeans.org/)
    * [drrb/rust-netbeans](https://github.com/drrb/rust-netbeans)
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://raw.githubusercontent.com/intellij-rust/intellij-rust) — [<img src="https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master">](https://travis-ci.org/intellij-rust/intellij-rust)
    * [intellij-rust/intellij-toml](https://github.com/intellij-rust/intellij-toml) - 基本的Toml支持
  * [Ride](https://raw.githubusercontent.com/madeso/ride) — [<img src="https://api.travis-ci.org/madeso/ride.svg?branch=master">](https://travis-ci.org/madeso/ride)
  * [SolidOak](https://github.com/oakes/SolidOak) - 一个简单的Rust IDE，基于GTK +和 [Neovim](https://github.com/neovim/neovim)
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) - 官方Rust包
    * [sublimehq/packages](https://github.com/sublimehq/Packages/tree/master/Rust) - 原生Sublime支持（已安装）
  * [Vim](https://vim.sourceforge.io/) - 无处不在的文本编辑器
	* [rust.vim](https://github.com/rust-lang/rust.vim) - 提供文件检测，语法突出显示，格式化，合成集成等.
	* [vim-cargo](https://github.com/timonv/vim-cargo) - 命令绑定从vim快速运行货物.
	* [vim-racer](https://github.com/racer-rust/vim-racer) - 允许vim使用 [Racer](https://github.com/racer-rust/racer) 用于Rust代码完成和导航.
	* [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/)  客户.  在Rust中实现并支持rls开箱即用.
  * 视觉工作室
    * [PistonDevelopers/VisualRust](https://raw.githubusercontent.com/PistonDevelopers/VisualRust) -  Rust的Visual Studio扩展 [<img src="https://api.travis-ci.org/PistonDevelopers/VisualRust.svg?branch=master">](https://travis-ci.org/PistonDevelopers/VisualRust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) - 对Visual Studio Code的Rust支持
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) -  LLDB扩展
    * [crates](https://raw.githubusercontent.com/serayuzgur/crates) -  crates是crates.io依赖项的扩展. [<img src="https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg">](https://raw.githubusercontent.com/serayuzgur/crates) [<img src="https://api.travis-ci.org/serayuzgur/crates.svg?branch=master">](https://travis-ci.org/serayuzgur/crates)
    * [KalitaAlexey/vscode-rust](https://marketplace.visualstudio.com/items?itemName=kalitaalexey.vscode-rust) -  RustyCode的一个分支
    * [saviorisdead/RustyCode](https://marketplace.visualstudio.com/items?itemName=saviorisdead.RustyCode) （没有维护）

### Pattern recognition

* [sfikas/rusteval](https://github.com/sfikas/rusteval) - 用于评估检索算法输出的工具 [![Build Status](https://api.travis-ci.org/sfikas/rusteval.svg?branch=master)](https://travis-ci.org/sfikas/rusteval)

### Profiling

* [performancecopilot/hornet](https://raw.githubusercontent.com/performancecopilot/hornet) -  Performance Co-Pilot内存映射值检测库 [![crates.io badge](https://img.shields.io/crates/v/hornet.svg)](https://crates.io/crates/hornet) [<img src="https://api.travis-ci.org/performancecopilot/hornet.svg?branch=master">](https://travis-ci.org/performancecopilot/hornet)
* [ellisonch/rust-stopwatch](https://raw.githubusercontent.com/ellisonch/rust-stopwatch) - 秒表图书馆 [<img src="https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master">](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  * [mrhooray/torch](https://github.com/mrhooray/torch) - 基于DWARF调试信息生成FlameGraphs
  * [TyOverby/flame](https://raw.githubusercontent.com/TyOverby/flame) — [<img src="https://api.travis-ci.org/TyOverby/flame.svg?branch=master">](https://travis-ci.org/TyOverby/flame)

### Static analysis

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [nvzqz/static-assertions-rs](https://github.com/nvzqz/static-assertions-rs/) [[static_assertions](https://crates.io/crates/static_assertions)]编译时断言以确保满足不变量 [![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### Testing

[[testing](https://crates.io/keywords/testing)]

* [llogiq/mutagen](https://raw.githubusercontent.com/llogiq/mutagen) [[mutagen](https://crates.io/crates/mutagen)]  - 源级突变测试框架（仅限每晚） [<img src="https://api.travis-ci.org/llogiq/mutagen.svg?branch=master">](https://travis-ci.org/llogiq/mutagen)
* [AlKass/polish](https://github.com/AlKass/polish) - 迷你测试/测试驱动框架 [![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
* [altsysrq/proptest](https://raw.githubusercontent.com/altsysrq/proptest) [[proptest](https://crates.io/crates/proptest)]  - 财产测试框架的启发 [Hypothesis](https://hypothesis.works/) Python的框架 [<img src="https://api.travis-ci.org/altsysrq/proptest.svg?branch=master">](https://travis-ci.org/altsysrq/proptest)
* [BurntSushi/quickcheck](https://raw.githubusercontent.com/BurntSushi/quickcheck) [[quickcheck](https://crates.io/crates/quickcheck)]  -  Rust的实现 [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) [<img src="https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master">](https://travis-ci.org/BurntSushi/quickcheck)
* [Mockito](https://raw.githubusercontent.com/lipanski/mockito) [[mockito](https://crates.io/crates/mockito)]  -  HTTP模拟 [<img src="https://api.travis-ci.org/lipanski/mockito.svg?branch=master">](https://travis-ci.org/lipanski/mockito)
* [utkarshkukreti/speculate.rs](https://github.com/utkarshkukreti/speculate.rs) [[speculate](https://crates.io/crates/speculate)]  - 一个RSpec启发了Rust的最小测试框架
* [rust-fuzz/afl.rs](https://raw.githubusercontent.com/rust-fuzz/afl.rs) - 一个Rust fuzzer，使用 [AFL](http://lcamtuf.coredump.cx/afl/) [<img src="https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master">](https://travis-ci.org/rust-fuzz/afl.rs)
* [trust](https://github.com/japaric/trust) -  Travis CI和AppVeyor模板，用于在5种体系结构上测试Rust crate并为Linux，macOS和Windows发布它的二进制版本
* [xd009642/tarpaulin](https://raw.githubusercontent.com/xd009642/tarpaulin) [[tarpaulin](https://crates.io/crates/cargo-tarpaulin)]  - 为Rust设计的代码覆盖工具 [<img src="https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master">](https://travis-ci.org/xd009642/tarpaulin)

### Transpiling

* [immunant/c2rust](https://github.com/immunant/c2rust) - 在Clang / LLVM上构建的C到Rust转换器和交叉检查器. [![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
* [jameysharp/corrode](https://github.com/jameysharp/corrode) - 用Haskell编写的AC to Rust翻译器.

## Services

- [deps.rs](https://deps.rs) - 检测过时或不安全的依赖项
- [docs.rs](https://docs.rs) - 自动生成包装箱的文件

## Libraries

### Artificial Intelligence

#### Genetic algorithms

* [Martin1887/oxigen](https://github.com/Martin1887/oxigen)   - 快速，并行，可扩展和适应性强的遗传算法库.  使用此库的示例仅在几秒钟内解决N = 255的N Queens问题，并使用少于1 MB的RAM.
* [innoave/genevo](https://github.com/innoave/genevo) - 以可定制和可扩展的方式执行遗传算法（GA）模拟.
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs)   - 该库允许您使用Rust编程语言编写进化算法（EA）.  作者：Willi Kappler，执照：麻省理工学院 - 版本0.4（2017.06.26）.
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic)   -  Rust中的遗传算法库.  在维护模式下.
* [mneumann/evo-rs](https://github.com/mneumann/evo-rs)   -  Rust的进化算法库.  没有变化3年.
* [yurytsoy/revonet](https://github.com/yurytsoy/revonet) - 用于解决优化问题和神经网络训练的实际编码GA的Rust实现.

#### Machine learning

[[machine learning](https://crates.io/keywords/machine-learning)]

也可以看看 [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f).

* [AtheMathmo/rusty-machine](https://github.com/AtheMathmo/rusty-machine) -  Rust的机器学习库 [![Build Status](https://api.travis-ci.org/AtheMathmo/rusty-machine.svg?branch=master)](https://travis-ci.org/AtheMathmo/rusty-machine)
* [avinashshenoy97/RusticSOM](https://github.com/avinashshenoy97/RusticSOM) - 自组织地图（SOM）的Rust库. [![Build Status](https://api.travis-ci.org/avinashshenoy97/RusticSOM.svg?branch=master)](https://travis-ci.org/avinashshenoy97/RusticSOM)
* [autumnai/leaf](https://github.com/autumnai/leaf) - 开放机器智能框架. [![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master) ]（https://travis-ci.org/autumnai/leaf）.  被遗弃的项目.  最新的分支是 [spearow/juice](https://github.com/rust-unofficial/awesome-rust/blob/master/ https://github.com/spearow/juice).
* [tensorflow/rust](https://github.com/tensorflow/rust) -  TensorFlow的Rust语言绑定. [![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) -  Rust的机器学习箱. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://circleci.com/gh/maciejkula/rustlearn)


### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [saurvs/astro-rust](https://raw.githubusercontent.com/saurvs/astro-rust) -  Rust的天文学 [<img src="https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master">](https://travis-ci.org/saurvs/astro-rust)
* [mindriot101/rust-fitsio](https://raw.githubusercontent.com/mindriot101/rust-fitsio) [[fitsio](https://crates.io/crates/fitsio)]  - 适合包装cfitsio的接口库 [<img src="https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master">](https://travis-ci.org/mindriot101/rust-fitsio)
* [flosse/rust-sun](https://raw.githubusercontent.com/flosse/rust-sun) -  JS库suncalc的生锈端口 [<img src="https://api.travis-ci.org/flosse/rust-sun.svg?branch=master">](https://travis-ci.org/flosse/rust-sun)

### Asynchronous

* [zonyitoo/coio-rs](https://raw.githubusercontent.com/zonyitoo/coio-rs) - 带有工作窃取调度程序的协程I / O库 [<img src="https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)
* [dpc/mioco](https://raw.githubusercontent.com/dpc/mioco) - 可扩展，基于协程的异步IO处理库 [<img src="https://img.shields.io/travis/dpc/mioco/master.svg?style=flat-square" alt="Travis CI Build Status">](https://travis-ci.org/dpc/mioco)
* [TeaEntityLab/fpRust](https://raw.githubusercontent.com/TeaEntityLab/fpRust) -  Monad / MonadIO，Handler，Coroutine / doNotation，Rust的功能编程功能 [<img src="https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/TeaEntityLab/fpRust)
* [rust-lang-nursery/futures-rs](https://raw.githubusercontent.com/rust-lang-nursery/futures-rs) -  Rust的零成本期货 [<img src="https://api.travis-ci.org/rust-lang-nursery/futures-rs.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/rust-lang-nursery/futures-rs)
* [carllerche/mio](https://raw.githubusercontent.com/carllerche/mio) -  MIO是Rust的轻量级IO库，专注于在OS抽象上添加尽可能少的开销 [<img src="https://api.travis-ci.org/carllerche/mio.svg?branch=master">](https://travis-ci.org/carllerche/mio)

### Audio

[[audio](https://crates.io/keywords/audio)]

* [GuillaumeGomez/rust-fmod](https://github.com/GuillaumeGomez/rust-fmod) — [FMOD](https://www.fmod.com) 绑定 [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
* [jhasse/ears](https://raw.githubusercontent.com/jhasse/ears) - 一个简单的库，可以在OpenAL和libsndfile之上播放声音和音乐 [<img src="https://api.travis-ci.org/jhasse/ears.svg?branch=master">](https://travis-ci.org/jhasse/ears)
* [jpernst/alto](https://raw.githubusercontent.com/jpernst/alto) -  OpenAL 1.1绑定 [<img src="https://api.travis-ci.org/jpernst/alto.svg?branch=master">](https://travis-ci.org/jpernst/alto)
* [musitdev/portmidi-rs](https://raw.githubusercontent.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) 绑定 [<img src="https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master">](https://travis-ci.org/musitdev/portmidi-rs)
* [ruuda/hound](https://raw.githubusercontent.com/ruuda/hound) [[Hound](https://crates.io/crates/hound)]  -  WAV编码和解码库 [<img src="https://api.travis-ci.org/ruuda/hound.svg?branch=master">](https://travis-ci.org/ruuda/hound)
* [tomaka/rodio](https://github.com/tomaka/rodio) -  Rust音频播放库 [![Build Status](https://api.travis-ci.org/tomaka/rodio.svg?branch=master)](https://travis-ci.org/tomaka/rodio)
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/rust-portaudio](https://raw.githubusercontent.com/RustAudio/rust-portaudio) — [PortAudio](http://www.portaudio.com/) 绑定 [<img src="https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master">](https://travis-ci.org/RustAudio/rust-portaudio)

### Authentication

* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) 生锈的lib  [![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)

### Automotive

* [Altenius/j2534](https://github.com/Altenius/j2534-rs) [[j2534](https://crates.io/crates/j2534)]  -  J2534 PassThru绑定
* [jmagnuson/canparse](https://raw.githubusercontent.com/jmagnuson/canparse) [[canparse](https://crates.io/crates/canparse)]  -  CAN信号和定义解析器 [<img src="https://api.travis-ci.org/jmagnuson/canparse.svg?branch=master">](https://travis-ci.org/jmagnuson/canparse)
* [JulianSchmid/dlt_parse](https://raw.githubusercontent.com/JulianSchmid/dlt-parse-rs) -  Rust DLT（诊断日志和跟踪）数据包解析器 [<img src="https://api.travis-ci.org/JulianSchmid/dlt-parse-rs.svg?branch=master">](https://travis-ci.org/JulianSchmid/dlt-parse-rs)
* [JulianSchmid/someip_parse](https://raw.githubusercontent.com/JulianSchmid/someip-parse-rs) [[someip_parse](https://crates.io/crates/someip_parse)]  - 用于解析SOME / IP网络协议的库（无有效负载解释） [<img src="https://api.travis-ci.org/JulianSchmid/someip-parse-rs.svg?branch=master">](https://travis-ci.org/JulianSchmid/someip-parse-rs)
* [LibreTuner/tuneutils](https://github.com/LibreTuner/tuneutils) [[tuneutils](https://crates.io/crates/tuneutils)]  - 用于连接，诊断和调整汽车的实用程序
* [marcelbuesing/can-dbc](https://raw.githubusercontent.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)]  -  DBC格式的解析器 [<img src="https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev">](https://travis-ci.org/marcelbuesing/can-dbc)
* [mbr/socketcan](https://raw.githubusercontent.com/mbr/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)]  -  Linux SocketCAN库 [<img src="https://api.travis-ci.org/mbr/socketcan-rs.svg?branch=master">](https://travis-ci.org/mbr/socketcan-rs)
* [Sensirion/lin-bus](https://raw.githubusercontent.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)]  -  LIN总线驱动程序的特性和协议实现 [<img src="https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg">](https://circleci.com/gh/Sensirion/lin-bus-rs)

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) -  Rust的生物信息学库.

### Caching

* [jaysonsantos/bmemcached-rs](https://raw.githubusercontent.com/jaysonsantos/bmemcached-rs) - 用纯锈写的Memcached库 [<img src="https://api.travis-ci.org/jaysonsantos/bmemcached-rs.svg?branch=master">](https://travis-ci.org/jaysonsantos/bmemcached-rs)
* [jaemk/cached](https://github.com/jaemk/cached) - 简单的功能缓存/记忆
* [aisk/rust-memcache](https://raw.githubusercontent.com/aisk/rust-memcache) -  Memcached客户端库 [<img src="https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master">](https://travis-ci.org/aisk/rust-memcache)

### Concurrency

* [aymanmadkour/glock](https://raw.githubusercontent.com/aymanmadkour/glock) -  Rust的颗粒状锁定箱. [<img src="https://api.travis-ci.org/aymanmadkour/glock.svg?branch=master">](https://travis-ci.org/aymanmadkour/glock)
* [crossbeam-rs/crossbeam](https://raw.githubusercontent.com/crossbeam-rs/crossbeam) - 支持Rust中的并行性和低级并发性 [<img src="https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master">](https://travis-ci.org/crossbeam-rs/crossbeam)
* [pop-os/bus-writer](https://github.com/pop-os/bus-writer) - 通用单读者，多作者
* [Rayon](https://raw.githubusercontent.com/rayon-rs/rayon) -  Rust的数据并行库 [<img src="https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master">](https://travis-ci.org/rayon-rs/rayon)
* [rustcc/coroutine-rs](https://raw.githubusercontent.com/rustcc/coroutine-rs) -  Rust的Coroutine Library [<img src="https://img.shields.io/travis/rustcc/coroutine-rs.svg">](https://travis-ci.org/rustcc/coroutine-rs)
* [zonyitoo/coio-rs](https://raw.githubusercontent.com/zonyitoo/coio-rs) -  Rust的Coroutine I / O. [<img src="https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)

### Cloud

* AWS [[aws](https://crates.io/keywords/aws)]
  * [rusoto/rusoto](https://raw.githubusercontent.com/rusoto/rusoto) — [<img src="https://api.travis-ci.org/rusoto/rusoto.svg?branch=master">](https://travis-ci.org/rusoto/rusoto)
* DigitalOcean
  * [kbknapp/doapi](https://raw.githubusercontent.com/kbknapp/doapi-rs) -  DigitalOcean v2 API绑定 [<img src="https://api.travis-ci.org/kbknapp/doapi-rs.svg?branch=master">](https://travis-ci.org/kbknapp/doapi-rs)

### Command-line

*参数解析
  * [clap-rs](https://raw.githubusercontent.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)]  - 一个简单易用，功能齐全的命令行参数解析器 [<img src="https://api.travis-ci.org/clap-rs/clap-rs.svg?branch=master">](https://travis-ci.org/clap-rs/clap-rs)
  * [docopt/docopt.rs](https://raw.githubusercontent.com/docopt/docopt.rs) [[docopt](https://crates.io/crates/docopt)]  -  Rust的实现 [DocOpt](http://docopt.org) [<img src="https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master">](https://travis-ci.org/docopt/docopt.rs)
  * [TeXitoi/structopt](https://raw.githubusercontent.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)]  - 通过定义结构来解析命令行参数 [<img src="https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master">](https://travis-ci.org/TeXitoi/structopt)
  * [killercup/quicli](https://raw.githubusercontent.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)]  - 在Rust中快速构建很酷的CLI应用程序 [<img src="https://api.travis-ci.org/killercup/quicli.svg">](https://travis-ci.org/killercup/quicli)
*以人为本的设计
  * [rust-clique/human-panic](https://raw.githubusercontent.com/rust-clique/human-panic) [[human-panic](https://crates.io/crates/human-panic)]  - 人类的恐慌信息 [<img src="https://api.travis-ci.org/rust-clique/human-panic.svg">](https://travis-ci.org/rust-clique/human-panic)
*行编辑器
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)]  -  pure-Rust命令行编辑库
  * [MovingtoMars/liner](https://raw.githubusercontent.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)]  - 提供类似readline功能的库 [<img src="https://api.travis-ci.org/MovingtoMars/liner.svg">](https://travis-ci.org/MovingtoMars/liner)
  * [murarth/linefeed](https://raw.githubusercontent.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)]  - 可配置，可扩展的交互式线路阅读器 [<img src="https://api.travis-ci.org/murarth/linefeed.svg">](https://travis-ci.org/murarth/linefeed)
  * [kkawakam/rustyline](https://raw.githubusercontent.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)]  -  Rust中的readline实现 [<img src="https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master">](https://travis-ci.org/kkawakam/rustyline)
*管道
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)]  - 通过外部寻呼机管道输出 [<img src="https://gitlab.com/imp/pager-rs/badges/master/build.svg">](https://gitlab.com/imp/pager-rs/pipelines)
  * [hniksic/rust-subprocess](https://raw.githubusercontent.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)]  - 与外部管道交互的设施 [<img src="https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master">](https://travis-ci.org/hniksic/rust-subprocess)
  * [oconnor663/duct.rs](https://raw.githubusercontent.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)]  - 子进程管道和IO重定向的构建器 [<img src="https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master">](https://travis-ci.org/oconnor663/duct.rs)
  * [philippkeller/rexpect](https://raw.githubusercontent.com/philippkeller/rexpect) [[rexpect](https://crates.io/crates/rexpect)]  - 自动化交互式应用程序，如ssh，ftp，passwd等 [<img src="https://api.travis-ci.org/philippkeller/rexpect.svg?branch=master">](https://travis-ci.org/philippkeller/rexpect)
*进展
  * [mitsuhiko/indicatif](https://github.com/mitsuhiko/indicatif) [[indicatif](https://crates.io/crates/indicatif)]  - 向用户表明进度
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)]  -  Rust的控制台进度条
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)]  -  60多个优雅的终端旋转器
*提示
  * [hashmismatch/terminal_cli.rs](https://raw.githubusercontent.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)]  - 构建一个交互式命令提示符 [<img src="https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master">](https://travis-ci.org/hashmismatch/terminal_cli.rs)
*风格
  * [ogham/rust-ansi-term](https://raw.githubusercontent.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)]  - 控制ANSI终端上的颜色和格式 [<img src="https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master">](https://travis-ci.org/ogham/rust-ansi-term)
  * [LukasKalbertodt/term-painter](https://raw.githubusercontent.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)]  - 跨平台风格的终端输出 [<img src="https://img.shields.io/travis/LukasKalbertodt/term-painter/master.svg">](https://travis-ci.org/LukasKalbertodt/term-painter)
  * [vitiral/termstyle](https://github.com/vitiral/termstyle) [[termstyle](https://docs.rs/termstyle/0.1.2/termstyle/)]  - 构建（和测试）格式化和样式化的命令行应用程序
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)]  - 一个简单的ANSI终端颜色绘图库
* TUI
  * [TimonPost/crossterm](https://github.com/TimonPost/crossterm) [[crossterm](https://crates.io/crates/crossterm)]  - 跨平台终端库
  * [gyscos/Cursive](https://raw.githubusercontent.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)]  - 构建丰富的TUI应用程序 [<img src="https://api.travis-ci.org/gyscos/Cursive.svg?branch=master">](https://travis-ci.org/gyscos/Cursive)
  * [ogham/rust-term-grid](https://raw.githubusercontent.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)]  - 用于将物品放入网格的Rust库 [<img src="https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master">](https://travis-ci.org/ogham/rust-term-grid)
  * [ticki/termion](https://raw.githubusercontent.com/redox-os/termion) [[termion](https://crates.io/crates/termion)]  - 用于控制终端/ TTY的无绑定库  [<img src="https://api.travis-ci.org/ticki/termion.svg?branch=master">](https://travis-ci.org/ticki/termion)
  * [fdehau/tui-rs](https://raw.githubusercontent.com/fdehau/tui-rs) [[tui](https://crates.io/crates/tui)]  - 受到启发的TUI库 [blessed-contrib](https://raw.githubusercontent.com/yaronn/blessed-contrib) 和 [termui](https://raw.githubusercontent.com/gizak/termui) [<img src="https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master">](https://travis-ci.org/fdehau/tui-rs)
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://raw.githubusercontent.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] — [BearLibTerminal](https://bitbucket.org/cfyzium/bearlibterminal) 绑定 [<img src="https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master">](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  * ncurses
    * [jeaye/ncurses-rs](https://raw.githubusercontent.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] — [ncurses](https://www.gnu.org/software/ncurses/) 绑定 [<img src="https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master">](https://travis-ci.org/jeaye/ncurses-rs)
    * [ihalila/pancurses](https://raw.githubusercontent.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)]  -  curses库，支持linux和windows [<img src="https://api.travis-ci.org/ihalila/pancurses.svg?branch=master">](https://travis-ci.org/ihalila/pancurses)
  * Termbox
    * [gchp/rustbox](https://raw.githubusercontent.com/gchp/rustbox) [[rustbox](https://crates.io/crates/rustbox)]  - 绑定到 [Termbox](https://raw.githubusercontent.com/nsf/termbox) [<img src="https://api.travis-ci.org/gchp/rustbox.svg?branch=master">](https://travis-ci.org/gchp/rustbox)

### Compression

* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) - 实施Brotli压缩
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) -  Rust中的Brotli解压缩程序，可以选择性地避免使用stdlib
* bzip2
  * [alexcrichton/bzip2-rs](https://raw.githubusercontent.com/alexcrichton/bzip2-rs) — [libbz2](http://www.bzip.org) 绑定 [<img src="https://api.travis-ci.org/alexcrichton/bzip2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/bzip2-rs)
* gzip
  * [carols10cents/zopfli](https://github.com/carols10cents/zopfli) - 实施 [Zopfli](https://github.com/google/zopfli) 压缩算法，用于更高质量的deflate或zlib压缩
* miniz
  * [alexcrichton/flate2-rs](https://raw.githubusercontent.com/alexcrichton/flate2-rs) — [miniz](https://code.google.com/archive/p/miniz) 绑定 [<img src="https://api.travis-ci.org/alexcrichton/flate2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/flate2-rs)
*活泼
  * [JeffBelgum/rust-snappy](https://raw.githubusercontent.com/JeffBelgum/rust-snappy) — [snappy](https://raw.githubusercontent.com/google/snappy) 绑定 [<img src="https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master">](https://travis-ci.org/JeffBelgum/rust-snappy)
*焦油
  * [alexcrichton/tar-rs](https://raw.githubusercontent.com/alexcrichton/tar-rs) - 在Rust中读取/写入tar档案 [<img src="https://api.travis-ci.org/alexcrichton/tar-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/tar-rs)
* 压缩
  * [mvdnes/zip-rs](https://github.com/mvdnes/zip-rs) - 读取和写入ZIP存档 [![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### Computation

* [argmin-rs/argmin](https://raw.githubusercontent.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)]  - 纯Rust优化库 [<img src="https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master">](https://travis-ci.org/argmin-rs/argmin)
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) -  BLAS绑定
  * [stainless-steel/blas](https://raw.githubusercontent.com/blas-lapack-rs/blas) -  BLAS绑定 [<img src="https://api.travis-ci.org/blas-lapack-rs/blas.svg?branch=master">](https://travis-ci.org/blas-lapack-rs/blas)
* [Conjugate Gradient](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  * [noshu/cg-sys](https://github.com/noshu/cg-sys) -  fortran CG +子程序的Rust绑定
* [GMP](https://gmplib.org/)
  * [fizyk20/rust-gmp](https://raw.githubusercontent.com/fizyk20/rust-gmp) -  libgmp绑定 [<img src="https://api.travis-ci.org/fizyk20/rust-gmp.svg?branch=master">](https://travis-ci.org/fizyk20/rust-gmp)
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://raw.githubusercontent.com/GuillaumeGomez) -  GSL绑定 [<img src="https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master">](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://raw.githubusercontent.com/blas-lapack-rs/lapack) -  LAPACK绑定 [<img src="https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master">](https://travis-ci.org/blas-lapack-rs/lapack)
* [L-BFGS-B](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  * [noshu/lbfgsb-sys](https://github.com/noshu/lbfgsb-sys) -  Fortran L-BFGS-B子程序的锈蚀绑定
* [rustsim/nalgebra](https://raw.githubusercontent.com/rustsim/nalgebra) - 低维线性代数库 [<img src="https://api.travis-ci.org/rustsim/nalgebra.svg?branch=master">](https://travis-ci.org/rustsim/nalgebra)
* 平行
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://arrayfire.com/) 绑定
  * [autumnai/collenchyma](https://raw.githubusercontent.com/autumnai/collenchyma) - 可扩展，可插入，后端无关的框架，用于在CUDA，OpenCL和通用主机CPU上进行并行，高性能计算. [<img src="https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master">](https://travis-ci.org/autumnai/collenchyma)
  * [luqmana/rust-opencl](https://raw.githubusercontent.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) 绑定 [<img src="https://api.travis-ci.org/luqmana/rust-opencl.svg?branch=master">](https://travis-ci.org/luqmana/rust-opencl)
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) -  Rust的科学计算库 [![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  * [boxtown/statrs](https://github.com/boxtown/statrs) -  Rust中强大的统计计算库 [![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)
* Rustimization [[rustimization](https://crates.io/crates/rustimization)]
  * [noshu/rustimization](https://github.com/noshu/rustimization) - 锈蚀优化库，包括L-BFGS-B和Conjugate Gradient算法

### Configuration

* [mehcode/config-rs](https://raw.githubusercontent.com/mehcode/config-rs) [[config](https://crates.io/crates/config)]  -  Rust应用程序的分层配置系统（强大支持12因子应用程序）. [<img src="https://api.travis-ci.org/mehcode/config-rs.svg?branch=master">](https://travis-ci.org/mehcode/config-rs)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)]  - 用于轻松处理应用程序配置的库

### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [briansmith/ring](https://raw.githubusercontent.com/briansmith/ring) - 使用Rust和BoringSSL的加密原语安全，快速，小型加密. [<img src="https://api.travis-ci.org/briansmith/ring.svg?branch=master">](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki](https://raw.githubusercontent.com/briansmith/webpki) -  Rust中的Web PKI TLS X.509证书验证. [<img src="https://api.travis-ci.org/briansmith/webpki.svg?branch=master">](https://travis-ci.org/briansmith/webpki)
* [brycx/orion](https://raw.githubusercontent.com/brycx/orion)   - 该库旨在提供简单实用的加密.  “可用”意味着暴露易于使用且难以滥用的高级API. [<img src="https://api.travis-ci.org/brycx/orion.svg?branch=master">](https://travis-ci.org/brycx/orion)
* [ctz/rustls](https://github.com/ctz/rustls) -  TLS的Rust实现
* [DaGenix/rust-crypto](https://raw.githubusercontent.com/DaGenix/rust-crypto) -  Rust中的加密算法 [<img src="https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* [dnaq/sodiumoxide](https://raw.githubusercontent.com/sodiumoxide/sodiumoxide) — [libsodium](https://raw.githubusercontent.com/jedisct1/libsodium) 绑定 [<img src="https://api.travis-ci.org/dnaq/sodiumoxide.svg?branch=master">](https://travis-ci.org/dnaq/sodiumoxide)
* [doublify/libblockchain](https://raw.githubusercontent.com/doublify/libblockchain) - 区块链实施 [<img src="https://api.travis-ci.org/doublify/libblockchain.svg?branch=master">](https://travis-ci.org/doublify/libblockchain)
* [exonum/exonum](https://raw.githubusercontent.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)]  - 区块链项目的可扩展框架 [<img src="https://api.travis-ci.org/exonum/exonum.svg?branch=master">](https://travis-ci.org/exonum/exonum)
* [klutzy/suruga](https://github.com/klutzy/suruga) -  Rust的一个实现 [TLS 1.2](https://tools.ietf.org/html/rfc5246)
* [libOctavo/octavo](https://raw.githubusercontent.com/libOctavo/octavo) -  Rust中的模块化哈希和加密库 [<img src="https://api.travis-ci.org/libOctavo/octavo.svg?branch=master">](https://travis-ci.org/libOctavo/octavo)
* [RustCrypto/hashes](https://raw.githubusercontent.com/RustCrypto/hashes) - 用纯Rust编写的加密哈希函数的集合 [<img src="https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master">](https://travis-ci.org/RustCrypto/hashes)
* [rustindia/mpw-rs](https://raw.githubusercontent.com/rustindia/mpw-rs) -  Master Password密码管理器的Pure Rust实现 [<img src="https://api.travis-ci.org/rustindia/mpw-rs.svg?branch=master">](https://travis-ci.org/rustindia/mpw-rs)
* [racum/rust-djangohashers](https://raw.githubusercontent.com/racum/rust-djangohashers)   -  Django项目中使用的密码原语的Rust端口.  它不需要Django，只根据其样式散列并验证密码. [<img src="https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master">](https://travis-ci.org/Racum/rust-djangohashers)
* [RNCryptor/rncryptor-rs](https://github.com/RNCryptor/rncryptor-rs) -  RNCryptor AES文件格式的Pure Rust实现
* [conradkdotcom/rooster](https://github.com/conradkdotcom/rooster) [[rooster](https://crates.io/crates/rooster)]  - 在终端中使用的简单密码管理器
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) - 本机TLS库的绑定
* [sfackler/rust-openssl](https://raw.githubusercontent.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) 绑定 [<img src="https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master">](https://travis-ci.org/sfackler/rust-openssl)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) - 安全框架的绑定（OSX本机加密）
* [steffengy/schannel-rs](https://github.com/steffengy/schannel-rs) -  Schannel的绑定（Windows本机TLS）
* [zebradil/rustotpony](https://github.com/zebradil/rustotpony) - 一次性密码生成器的CLI管理器，即Google Authenticator（TOTP）

### Database

[[database](https://crates.io/keywords/database)]

* [sfackler/r2d2](https://raw.githubusercontent.com/sfackler/r2d2) - 通用连接池 [<img src="https://api.travis-ci.org/sfackler/r2d2.svg?branch=master">](https://travis-ci.org/sfackler/r2d2)
* NoSQL [[nosql](https://crates.io/keywords/nosql)]
  * [Cassandra](http://cassandra.apache.org) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://raw.githubusercontent.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] — native client written in Rust [<img src="https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master">](https://travis-ci.org/AlexPikalov/cdrs)
    * [Metaswitch/cassandra-rs](https://raw.githubusercontent.com/Metaswitch/cassandra-rs) - 绑定到DataStax C / C ++客户端 [<img src="https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master">](https://travis-ci.org/Metaswitch/cassandra-rs)
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://raw.githubusercontent.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)]  -  CouchDB REST API的Rust客户端 [<img src="https://api.travis-ci.org/chill-rs/chill.svg?branch=master">](https://travis-ci.org/chill-rs/chill)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://raw.githubusercontent.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)]  - 一个Rust客户端 [Elastic](https://www.elastic.co/) REST API [<img src="https://api.travis-ci.org/benashford/rs-es.svg?branch=master">](https://travis-ci.org/benashford/rs-es)
    * [elastic-rs/elastic-reqwest](https://raw.githubusercontent.com/elastic-rs/elastic-reqwest) [[elastic_reqwest](https://crates.io/crates/elastic_reqwest)]  - 基于Reqwest的Elasticsearch API的轻量级实现 [<img src="https://api.travis-ci.org/elastic-rs/elastic-reqwest.svg">](https://travis-ci.org/elastic-rs/elastic-reqwest)
  * etcd
    * [jimmycuadra/rust-etcd](https://raw.githubusercontent.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)]  -  CoreOS的etcd客户端库. [<img src="https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master">](https://travis-ci.org/jimmycuadra/rust-etcd)
  * ForestDB
    * [vhbit/sherwood](https://raw.githubusercontent.com/vhbit/sherwood) — [ForestDB](https://raw.githubusercontent.com/couchbase/forestdb) 绑定 [<img src="https://api.travis-ci.org/vhbit/sherwood.svg?branch=master">](https://travis-ci.org/vhbit/sherwood)
  * [InfluxDB](https://www.influxdata.com/)
    * [panoptix-za/influxdb-rs](https://raw.githubusercontent.com/panoptix-za/influxdb-rs) - 异步接口 [<img src="https://api.travis-ci.org/panoptix-za/influxdb-rs.svg?branch=master">](https://travis-ci.org/panoptix-za/influxdb-rs)
    * [driftluo/InfluxDBClient-rs](https://raw.githubusercontent.com/driftluo/InfluxDBClient-rs) - 同步接口 [<img src="https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master">](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  * LevelDB
    * [skade/leveldb](https://raw.githubusercontent.com/skade/leveldb) — [LevelDB](https://raw.githubusercontent.com/google/leveldb) 绑定 [<img src="https://api.travis-ci.org/skade/leveldb.svg?branch=master">](https://travis-ci.org/skade/leveldb)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://raw.githubusercontent.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](https://symas.com/lmdb/) 绑定 [<img src="https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master">](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb-labs/mongo-rust-driver-prototype](https://raw.githubusercontent.com/mongodb-labs/mongo-rust-driver-prototype) [[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.com/) 绑定 [<img src="https://api.travis-ci.org/mongodb-labs/mongo-rust-driver-prototype.svg">](https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype)
  * Neo4j [[cypher](https://crates.io/keywords/cypher), [neo4j](https://crates.io/keywords/neo4j)]
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [mitsuhiko/redis-rs](https://raw.githubusercontent.com/mitsuhiko/redis-rs) — [Redis](https://redis.io/) Rust的图书馆 [<img src="https://api.travis-ci.org/mitsuhiko/redis-rs.svg?branch=master">](https://travis-ci.org/mitsuhiko/redis-rs)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://raw.githubusercontent.com/rust-rocksdb/rust-rocksdb) -  RocksDB绑定 [<img src="https://api.travis-ci.org/rust-rocksdb/rust-rocksdb.svg?branch=master">](https://travis-ci.org/rust-rocksdb/rust-rocksdb)
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://raw.githubusercontent.com/zitsen/unqlite.rs) -  UnQLite绑定 [<img src="https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master">](https://travis-ci.org/zitsen/unqlite.rs)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://raw.githubusercontent.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)]  -  Apache ZooKeeper的客户端库. [<img src="https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master">](https://travis-ci.org/bonifaido/rust-zookeeper)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Microsoft SQL
    * [steffengy/tiberius](https://raw.githubusercontent.com/steffengy/tiberius) — [<img src="https://api.travis-ci.org/steffengy/tiberius.svg?branch=master">](https://travis-ci.org/steffengy/tiberius)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://raw.githubusercontent.com/AgilData/mysql-proxy-rs) -  MySQL代理 [<img src="https://api.travis-ci.org/AgilData/mysql-proxy-rs.svg?branch=master">](https://travis-ci.org/AgilData/mysql-proxy-rs)
    * [blackbeam/mysql_async](https://raw.githubusercontent.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)]  - 基于Tokio的asyncronous Rust Mysql驱动程序. [<img src="https://api.travis-ci.org/blackbeam/mysql_async.svg?branch=master">](https://travis-ci.org/blackbeam/mysql_async)
    * [blackbeam/rust-mysql-simple](https://raw.githubusercontent.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)]  - 本机MySql客户端 [<img src="https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://raw.githubusercontent.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)]  - 土生土长 [PostgreSQL](https://www.postgresql.org/) 客户 [<img src="https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [jgallagher/rusqlite](https://raw.githubusercontent.com/jgallagher/rusqlite) — [Sqlite3](https://www.sqlite.org/index.html) 绑定 [<img src="https://api.travis-ci.org/jgallagher/rusqlite.svg?branch=master">](https://travis-ci.org/jgallagher/rusqlite)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) -  Rust的ORM和Query构建器 [![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg)](https://travis-ci.org/diesel-rs/diesel)
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) -  Rust的ORM [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg)](https://travis-ci.org/ivanceras/rustorm)

### Data processing

* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) - 具有数组视图，多维切片和高效操作的N维数组
* [kernelmachine/utah](https://github.com/kernelmachine/utah) -  Rust中的数据帧结构和操作
* [weld-project/weld](https://github.com/weld-project/weld) - 数据分析应用程序的高性能运行时

### Data structures

* [bluss/rust-itertools](https://raw.githubusercontent.com/bluss/rust-itertools) — [<img src="https://api.travis-ci.org/bluss/rust-itertools.svg?branch=master">](https://travis-ci.org/bluss/rust-itertools)
* [contain-rs](https://github.com/contain-rs) -  Rust的std :: collections的扩展
* [danielpclark/array_tool](https://raw.githubusercontent.com/danielpclark/array_tool)   -  Rust的数组助手.  您将在数组上使用的一些最常用的方法可在Vectors上使用.  用于处理大多数用例的多态实现. [<img src="https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master">](https://travis-ci.org/danielpclark/array_tool)
* [fizyk20/generic-array](https://raw.githubusercontent.com/fizyk20/generic-array) - 允许通过typenums大小的数组的hack [<img src="https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master">](https://travis-ci.org/fizyk20/generic-array)
* [garro95/priority-queue](https://raw.githubusercontent.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)]  - 实现优先级更改的优先级队列. [<img src="https://api.travis-ci.org/garro95/priority-queue.svg?branch=master">](https://travis-ci.org/garro95/priority-queue)
* [Nemo157/roaring-rs](https://raw.githubusercontent.com/Nemo157/roaring-rs) - 在Rust中咆哮的位图 [<img src="https://api.travis-ci.org/Nemo157/roaring-rs.svg?branch=master">](https://travis-ci.org/Nemo157/roaring-rs)
* [orium/rpds](https://raw.githubusercontent.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)]  -  Rust中的持久数据结构. [<img src="https://api.travis-ci.org/orium/rpds.svg?branch=master">](https://travis-ci.org/orium/rpds)
* [pop-os/progress-streams](https://github.com/pop-os/progress-streams) - 实现`dyn io :: Read`或`dyn io :: Write`的类型的进程回调.
* [reem/rust-typemap](https://raw.githubusercontent.com/reem/rust-typemap) — [<img src="https://api.travis-ci.org/reem/rust-typemap.svg?branch=master">](https://travis-ci.org/reem/rust-typemap)
* [xfix/enum-map](https://raw.githubusercontent.com/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)]  - 使用数组存储值的枚举的优化映射实现. [<img src="https://api.travis-ci.org/xfix/enum-map.svg?branch=master">](https://travis-ci.org/xfix/enum-map)

### Data visualization

* [saresend/gust](https://raw.githubusercontent.com/saresend/Gust) — [<img src="https://api.travis-ci.org/saresend/Gust.svg?branch=master">](https://travis-ci.org/saresend/Gust)

### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://raw.githubusercontent.com/chronotope/chrono) — [<img src="https://api.travis-ci.org/chronotope/chrono.svg?branch=master">](https://travis-ci.org/chronotope/chrono)
* [yaa110/rust-persian-calendar](https://raw.githubusercontent.com/yaa110/rust-persian-calendar) — [<img src="https://api.travis-ci.org/yaa110/rust-persian-calendar.svg?branch=master">](https://travis-ci.org/yaa110/rust-persian-calendar)

### Distributed systems

*锑
  * [antimonyproject/antimony](https://raw.githubusercontent.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)]  - 流处理/分布式计算平台 [<img src="https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master">](https://travis-ci.org/antimonyproject/antimony)
* Apache Hadoop
  * [whitfin/efflux](https://github.com/whitfin/efflux) -  Rust中的Easy Hadoop Streaming和MapReduce接口.
* Apache Kafka
  * [fede1024/rust-rdkafka](https://raw.githubusercontent.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka](https://raw.githubusercontent.com/edenhill/librdkafka) 绑定 [<img src="https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master">](https://travis-ci.org/fede1024/rust-rdkafka)
  * [spicavigo/kafka-rust](https://raw.githubusercontent.com/spicavigo/kafka-rust) — [<img src="https://api.travis-ci.org/spicavigo/kafka-rust.svg?branch=master">](https://travis-ci.org/spicavigo/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://raw.githubusercontent.com/schickling/rust-beanstalkd) — [Beanstalkd](https://raw.githubusercontent.com/beanstalkd/beanstalkd) 绑定 [<img src="https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master">](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs](https://raw.githubusercontent.com/hyunsik/hdfs-rs) -  libhdfs绑定 [<img src="https://api.travis-ci.org/hyunsik/hdfs-rs.svg?branch=master">](https://travis-ci.org/hyunsik/hdfs-rs)

### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [GildedHonour/atarashii_imap](https://raw.githubusercontent.com/GildedHonour/atarashii_imap)   - 新しい（atarashii / new）Rust的IMAP客户端.  它支持普通和安全连接 [<img src="https://api.travis-ci.org/GildedHonour/atarashii_imap.svg?branch=master">](https://travis-ci.org/GildedHonour/atarashii_imap)
* [gsquire/sendgrid-rs](https://raw.githubusercontent.com/gsquire/sendgrid-rs) -  SendGrid API的非官方Rust库 [<img src="https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master">](https://travis-ci.org/gsquire/sendgrid-rs)
* [lettre/lettre](https://raw.githubusercontent.com/lettre/lettre) -  Rust的SMTP库 [<img src="https://api.travis-ci.org/lettre/lettre.svg?branch=master">](https://travis-ci.org/lettre/lettre)
* [staktrace/mailparse](https://raw.githubusercontent.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)]  - 用于解析真实世界电子邮件文件的库 [<img src="https://api.travis-ci.org/staktrace/mailparse.svg?branch=master">](https://travis-ci.org/staktrace/mailparse)

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://raw.githubusercontent.com/alex/rust-asn1) -  Rust ASN.1（DER）序列化程序 [<img src="https://api.travis-ci.org/alex/rust-asn1.svg?branch=master">](https://travis-ci.org/alex/rust-asn1)
* Bencode
  * [arjantop/rust-bencode](https://raw.githubusercontent.com/arjantop/rust-bencode) — [Bencode](https://en.wikipedia.org/wiki/Bencode) 在Rust中实现 [<img src="https://api.travis-ci.org/arjantop/rust-bencode.svg?branch=master">](https://travis-ci.org/arjantop/rust-bencode)
*二进制
  * [arcnmx/nue](https://raw.githubusercontent.com/arcnmx/nue) -  Rust的I / O和二进制数据编码 [<img src="https://api.travis-ci.org/arcnmx/nue.svg?branch=master">](https://travis-ci.org/arcnmx/nue)
  * [TyOverby/bincode](https://raw.githubusercontent.com/TyOverby/bincode) -  Rust中的二进制编码器/解码器 [<img src="https://api.travis-ci.org/TyOverby/bincode.svg?branch=master">](https://travis-ci.org/TyOverby/bincode)
  * [m4b/goblin](https://raw.githubusercontent.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)]  - 跨平台，零拷贝和字节序感知的二进制解析 [<img src="https://api.travis-ci.org/m4b/goblin.svg?branch=master">](https://travis-ci.org/m4b/goblin)
* BSON
  * [zonyitoo/bson-rs](https://raw.githubusercontent.com/zonyitoo/bson-rs) — [<img src="https://api.travis-ci.org/zonyitoo/bson-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/bson-rs)
*字节交换
  * [BurntSushi/byteorder](https://raw.githubusercontent.com/BurntSushi/byteorder) - 支持big-endian，little-endian和native byte命令 [<img src="https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master">](https://travis-ci.org/BurntSushi/byteorder)
* Cap&#39;n Proto
  * [capnproto/capnproto-rust](https://raw.githubusercontent.com/capnproto/capnproto-rust) — [<img src="https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master">](https://travis-ci.org/capnproto/capnproto-rust)
* CBOR
  * [BurntSushi/rust-cbor](https://raw.githubusercontent.com/BurntSushi/rust-cbor) - 支持JSON转换和基于类型的编码/解码 [<img src="https://api.travis-ci.org/BurntSushi/rust-cbor.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-cbor)
* 字符编码
  * [hsivonen/encoding_rs](https://raw.githubusercontent.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)]  -  Rust中面向Gecko的编码标准实现 [<img src="https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master">](https://travis-ci.org/hsivonen/encoding_rs)
  * [lifthrasiir/rust-encoding](https://raw.githubusercontent.com/lifthrasiir/rust-encoding) — [<img src="https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs](https://raw.githubusercontent.com/mrhooray/crc-rs) — [<img src="https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master">](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv](https://raw.githubusercontent.com/BurntSushi/rust-csv) - 快速灵活的CSV读写器，支持Serde [<img src="https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-csv)
* [FlatBuffers](https://google.github.io/flatbuffers/)
  * [frol/flatc-rust](https://raw.githubusercontent.com/frol/flatc-rust) - 用于Cargo构建脚本的FlatBuffers编译器（flatc）集成 [<img src="https://api.travis-ci.org/frol/flatc-rust.svg?branch=master">](https://travis-ci.org/frol/flatc-rust)
*有
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) — A HTTP Archive Format (HAR) serialization & deserialization library [![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
* HTML
  * [servo/html5ever](https://raw.githubusercontent.com/servo/html5ever) - 高性能的浏览器级HTML5解析器 [<img src="https://api.travis-ci.org/servo/html5ever.svg?branch=master">](https://travis-ci.org/servo/html5ever)
  * [veddan/rust-htmlescape](https://raw.githubusercontent.com/veddan/rust-htmlescape) - 编码/解码HTML实体 [<img src="https://api.travis-ci.org/veddan/rust-htmlescape.svg?branch=master">](https://travis-ci.org/veddan/rust-htmlescape)
* JSON
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[pikkr](https://crates.io/crates/pikkr)]  -  JSON解析器直接获取值而不在Rust中执行标记化
  * [serde-rs/json](https://raw.githubusercontent.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)]  -  JSON支持 [Serde](https://raw.githubusercontent.com/serde-rs/serde) 骨架 [<img src="https://api.travis-ci.org/serde-rs/json.svg?branch=master">](https://travis-ci.org/serde-rs/json)
  * [maciejhirsz/json-rust](https://raw.githubusercontent.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)]  -  Rust中的JSON实现 [<img src="https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master">](https://travis-ci.org/maciejhirsz/json-rust)
* Jonnet
  * [Qihoo360/rust-jsonnet](https://raw.githubusercontent.com/Qihoo360/rust-jsonnet) —  [<img src="https://api.travis-ci.org/Qihoo360/rust-jsonnet.svg?branch=master">](https://travis-ci.org/Qihoo360/rust-jsonnet)
* MsgPack
  * [3Hren/msgpack-rust](https://raw.githubusercontent.com/3Hren/msgpack-rust) - 纯Rust低/高级MessagePack实现 [<img src="https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master">](https://travis-ci.org/3Hren/msgpack-rust)
* PEM
  * [jcreekmore/pem-rs](https://raw.githubusercontent.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)]  - 基于Rust的解析和编码PEM编码数据的方法 [<img src="https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master">](https://travis-ci.org/jcreekmore/pem-rs)
*邮差收藏
  * [mandrean/postman-collection-rs](https://github.com/mandrean/postman-collection-rs) -  Postman Collection v1，v2和v2.1序列化和反序列化库 [![Build Status](https://api.travis-ci.org/mandrean/postman-collection-rs.svg?branch=master)](https://travis-ci.org/mandrean/postman-collection-rs)
* ProtocolBuffers
  * [danburkert/prost](https://raw.githubusercontent.com/danburkert/prost) — [<img src="https://api.travis-ci.org/danburkert/prost.svg?branch=master">](https://travis-ci.org/danburkert/prost)
  * [stepancheg/rust-protobuf](https://raw.githubusercontent.com/stepancheg/rust-protobuf) — [<img src="https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
* RON（生锈的对象表示法）
  * [https://raw.githubusercontent.com/ron-rs/ron](https://raw.githubusercontent.com/ron-rs/ron) — [<img src="https://api.travis-ci.org/ron-rs/ron.svg?branch=master">](https://travis-ci.org/https://raw.githubusercontent.com/ron-rs/ron)
* Tnetstring
  * [erickt/rust-tnetstring](https://raw.githubusercontent.com/erickt/rust-tnetstring) — [<img src="https://api.travis-ci.org/erickt/rust-tnetstring.svg?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
* TOML
  * [alexcrichton/toml-rs](https://raw.githubusercontent.com/alexcrichton/toml-rs) — [<img src="https://api.travis-ci.org/alexcrichton/toml-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/toml-rs)
* XML
  * [Florob/RustyXML](https://raw.githubusercontent.com/Florob/RustyXML) - 用Rust编写的XML解析器 [<img src="https://api.travis-ci.org/Florob/RustyXML.svg?branch=master">](https://travis-ci.org/Florob/RustyXML)
  * [shepmaster/sxd-document](https://raw.githubusercontent.com/shepmaster/sxd-document) -  Rust中的XML库 [<img src="https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath](https://raw.githubusercontent.com/shepmaster/sxd-xpath) -  Rust中的XPath库 [<img src="https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-xpath)
  * [netvl/xml-rs](https://raw.githubusercontent.com/netvl/xml-rs) - 流式XML库 [<img src="https://api.travis-ci.org/netvl/xml-rs.svg?branch=master">](https://travis-ci.org/netvl/xml-rs)
  * [media-io/yaserde](https://raw.githubusercontent.com/media-io/yaserde) - 另一个专门用于XML的Serializer / Deserializer [<img src="https://api.travis-ci.org/media-io/yaserde.svg?branch=master">](https://travis-ci.org/media-io/yaserde)
* YAML
  * [chyh1990/yaml-rust](https://raw.githubusercontent.com/chyh1990/yaml-rust) -  Rust缺少YAML 1.2实现. [<img src="https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master">](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://raw.githubusercontent.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)]  -  YAML支持 [Serde](https://raw.githubusercontent.com/serde-rs/serde) 骨架 [<img src="https://api.travis-ci.org/dtolnay/serde-yaml.svg?branch=master">](https://travis-ci.org/dtolnay/serde-yaml)
  * [kimhyunkang/libyaml-rust](https://raw.githubusercontent.com/kimhyunkang/libyaml-rust) — [libyaml](https://pyyaml.org/wiki/LibYAML) 绑定 [<img src="https://api.travis-ci.org/kimhyunkang/libyaml-rust.svg?branch=master">](https://travis-ci.org/kimhyunkang/libyaml-rust)
  * [vitiral/stfu8](https://raw.githubusercontent.com/vitiral/stfu8) - 以UTF-8排序文本格式 [<img src="https://api.travis-ci.org/vitiral/stfu8.svg?branch=master">](https://travis-ci.org/vitiral/stfu8)

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
*运营
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) - &gt; UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) - 对于`mount` /`umount2`系统调用的高级抽象.
  * [vitiral/path_abs](https://raw.githubusercontent.com/vitiral/path_abs) - 绝对可序列化的路径类型和相关方法. [<img src="https://api.travis-ci.org/vitiral/path_abs.svg?branch=master">](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
  * [webdesus/fs_extra](https://raw.githubusercontent.com/webdesus/fs_extra) - 扩大机会标准库std :: fs和std :: io [<img src="https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master">](https://travis-ci.org/webdesus/fs_extra)
*临时文件
  * [rust-lang-deprecated/tempdir](https://raw.githubusercontent.com/rust-lang-deprecated/tempdir) - 临时目录库 [<img src="https://api.travis-ci.org/rust-lang-nursery/tempdir.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/tempdir)
  * [Stebalien/tempfile](https://raw.githubusercontent.com/Stebalien/tempfile) - 临时文件库 [<img src="https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master">](https://travis-ci.org/Stebalien/tempfile)
  * [Stebalien/xattr](https://raw.githubusercontent.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)]  - 列出并操作unix扩展文件属性 [<img src="https://api.travis-ci.org/Stebalien/xattr.svg?branch=master">](https://travis-ci.org/Stebalien/xattr)
  * [zboxfs/zbox](https://raw.githubusercontent.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)]  - 零细节，以隐私为重点的可嵌入文件系统. [<img src="https://api.travis-ci.org/zboxfs/zbox.svg?branch=master">](https://travis-ci.org/zboxfs/zbox)

### Game development

也可以看看 [Are we game yet?](http://arewegameyet.com)
* Allegro
  * [SiegeLord/RustAllegro](https://raw.githubusercontent.com/SiegeLord/RustAllegro) — [Allegro 5](https://liballeg.org/) 绑定 [<img src="https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master">](https://travis-ci.org/SiegeLord/RustAllegro)
* Challonge
  * [vityafx/challonge-rs](https://raw.githubusercontent.com/vityafx/challonge-rs) [[challonge](https://crates.io/crates/challonge) ]  -  Challonge REST API的客户端库.  帮助组织比赛. [<img src="https://api.travis-ci.org/vityafx/challonge-rs.svg?branch=master">](https://travis-ci.org/vityafx/challonge-rs)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange) 绑定
*实体组件系统（ECS）
  * [slide-rs/specs](https://raw.githubusercontent.com/slide-rs/specs) — Specs Parallel ECS [<img src="https://api.travis-ci.org/slide-rs/specs.svg">](httpsL//raw.githubusercontent.com/travis-ci.org/slide-rs/specs)
*游戏引擎
  * [Amethyst](https://www.amethyst.rs) - 面向数据的游戏引擎 [<img src="https://api.travis-ci.org/amethyst/amethyst.svg?branch=master">](https://travis-ci.org/amethyst/amethyst)
  * [Piston](https://www.piston.rs/) — [<img src="https://api.travis-ci.org/PistonDevelopers/piston.svg?branch=master">](https://travis-ci.org/PistonDevelopers/piston)
  * [ggez](https://raw.githubusercontent.com/ggez/ggez) - 轻量级游戏框架，用于制作摩擦最小的2D游戏 [<img src="https://api.travis-ci.org/ggez/ggez.svg?branch=master">](https://travis-ci.org/ggez/ggez)
  * [Kiss3D](http://kiss3d.org/) - 用Rust编写的Keep It Simple，Stupid 3d图形引擎
  * [Unrust](https://github.com/unrust/unrust) -  unrust  - 基于纯锈（webgl 2.0 /原生）游戏引擎
  * [Vulkust](https://github.com/Hossein-Noroozpour/vulkust) -  Vulkust  - 一个用Rust编写的安全，高度多线程，基于Vulkan的游戏引擎.
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://raw.githubusercontent.com/brson/rust-sdl) -  SDL1绑定 [<img src="https://api.travis-ci.org/brson/rust-sdl.svg?branch=master">](https://travis-ci.org/brson/rust-sdl)
  * [Rust-SDL2/rust-sdl2](https://raw.githubusercontent.com/Rust-SDL2/rust-sdl2) -  SDL2绑定 [<img src="https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master">](https://travis-ci.org/Rust-SDL2/rust-sdl2)
* SFML
  * [jeremyletang/rust-sfml](https://raw.githubusercontent.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/) 绑定 [<img src="https://api.travis-ci.org/jeremyletang/rust-sfml.svg?branch=master">](https://travis-ci.org/jeremyletang/rust-sfml)
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) - 用于Rust的Libtcod绑定.
*维多利亚
  * [VictoremWinbringer/Victorem](https://raw.githubusercontent.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)]  - 简易UDP游戏服务器和UDP客户端框架，用于创建简单的2D和3D在线游戏原型 [<img src="https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master">](https://travis-ci.org/VictoremWinbringer/Victorem)
* Voxlap
  * [bbodi/rust-voxlap](https://github.com/bbodi/rust-voxlap) — [Voxlap](http://advsys.net/ken/voxlap.htm) 绑定

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://raw.githubusercontent.com/DaveKram/coord_transforms) [[coord_transforms](https://crates.io/crates/coord_transforms)]  - 坐标转换（2-d，3-d和地理空间） [<img src="https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master">](https://travis-ci.org/DaveKram/coord_transforms)
* [vlopes11/geomorph](https://raw.githubusercontent.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)]  -  UTM，LatLon和MGRS坐标之间的转换 [<img src="https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master">](https://travis-ci.org/vlopes11/geomorph)
* [Georust](https://github.com/georust) - 用Rust编写的地理空间工具和库
* [rust-reverse-geocoder](https://github.com/llambda/rrgeo) -  Rust中一个快速，离线的反向地理编码器，灵感来自https://github.com/thampiman/reverse-geocoder

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* [gfx-rs/gfx](https://raw.githubusercontent.com/gfx-rs/gfx) -  Rust的高性能无绑定图形API. [<img src="https://img.shields.io/travis/gfx-rs/gfx/master.svg">](https://travis-ci.org/gfx-rs/gfx)
*字体
  * [redox-os/rusttype](https://raw.githubusercontent.com/redox-os/rusttype) - 像FreeType这样的库的纯Rust替代品 [<img src="https://img.shields.io/travis/dredox-os/rusttype/master.svg">](https://travis-ci.org/redox-os/rusttype)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://raw.githubusercontent.com/brendanzab/gl-rs) — [<img src="https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master">](https://travis-ci.org/brendanzab/gl-rs)
  * [glium/glium](https://raw.githubusercontent.com/glium/glium) -  Rust语言的安全OpenGL包装器. [<img src="https://api.travis-ci.org/glium/glium.svg?branch=master">](https://travis-ci.org/glium/glium)
  * [Kiss3d](http://kiss3d.org) - 绘制简单的几何图形，并使用单线玩 [<img src="https://api.travis-ci.org/repositories/sebcrozet/kiss3d.json.svg?branch=master">](https://api.travis-ci.org/repositories/sebcrozet/kiss3d.json)
  * [PistonDevelopers/glfw-rs](https://raw.githubusercontent.com/PistonDevelopers/glfw-rs) — [<img src="https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master">](https://travis-ci.org/PistonDevelopers/glfw-rs)
  * [tomaka/glutin](https://raw.githubusercontent.com/tomaka/glutin) -  Rust替代品 [GLFW](https://www.glfw.org/) [<img src="https://api.travis-ci.org/tomaka/glutin.svg?branch=master">](https://travis-ci.org/tomaka/glutin)
* PDF
  * [kaj/rust-pdf](https://raw.githubusercontent.com/kaj/rust-pdf) — [<img src="https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master">](https://travis-ci.org/kaj/rust-pdf)
  * [fschutt/printpdf](https://raw.githubusercontent.com/fschutt/printpdf) -  PDF写作库 [<img src="https://api.travis-ci.org/fschutt/printpdf.svg?branch=master">](https://travis-ci.org/fschutt/printpdf)
  * [J-F-Liu/lopdf](https://raw.githubusercontent.com/J-F-Liu/lopdf) -  PDF文档操作 [<img src="https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master">](https://travis-ci.org/J-F-Liu/lopdf)
* [Vulkan](https://www.khronos.org/vulkan/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [vulkano](https://raw.githubusercontent.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] — [<img src="https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master">](https://travis-ci.org/vulkano-rs/vulkano)

### Graph processing

* [kud1ing/tinkerpop-rs](https://raw.githubusercontent.com/kud1ing/tinkerpop-rs) - 一个如何使用Rust的Apache TinkerPop的例子 [<img src="https://api.travis-ci.org/kud1ing/tinkerpop-rs.svg?branch=master">](https://travis-ci.org/kud1ing/tinkerpop-rs)

### GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) -  Rust的简单跨平台GUI自动化库.
* [maps4print/azul](https://raw.githubusercontent.com/maps4print/azul) - 一个免费的，功能性的，面向IMGUI的GUI框架，用于快速开发用Rust编写的桌面应用程序，由Mozilla WebRender渲染引擎支持. [<img src="https://api.travis-ci.org/maps4print/azul.svg?branch=master">](https://travis-ci.org/maps4print/azul)
* [PistonDevelopers/conrod](https://raw.githubusercontent.com/PistonDevelopers/conrod/) - 一个易于使用的即时模式2D GUI库，完全用Rust编写 [<img src="https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master">](https://travis-ci.org/PistonDevelopers/conrod)
* [rise-ui](https://github.com/rise-ui/rise) - 基于组件的简单跨平台GUI工具包，用于开发美观且用户友好的界面.


* 可可
  * [kylewlacy/sorbet-cocoa](https://raw.githubusercontent.com/kylewlacy/sorbet-cocoa) — [<img src="https://api.travis-ci.org/kylewlacy/sorbet-cocoa.svg?branch=master">](https://travis-ci.org/kylewlacy/sorbet-cocoa)
  * [servo/core-foundation-rs](https://raw.githubusercontent.com/servo/core-foundation-rs) — [<img src="https://api.travis-ci.org/servo/core-foundation-rs.svg?branch=master">](https://travis-ci.org/servo/core-foundation-rs)
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk](https://raw.githubusercontent.com/gtk-rs/gtk) -  GTK +绑定 [<img src="https://api.travis-ci.org/gtk-rs/gtk.svg?branch=master">](https://travis-ci.org/gtk-rs/gtk)
  * [relm](https://raw.githubusercontent.com/antoyo/relm) - 基于GTK +的异步GUI库，灵感来自Elm [<img src="https://api.travis-ci.org/antoyo/relm.svg?branch=master">](https://travis-ci.org/antoyo/relm)
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://raw.githubusercontent.com/Gekkio/imgui-rs) -  ImGui的Rust绑定 [<img src="https://api.travis-ci.org/Gekkio/imgui-rs.svg?branch=master">](https://travis-ci.org/Gekkio/imgui-rs)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [clear-coat](https://github.com/jminer/clear-coat) -  Clear Coat是IUP GUI库的Rust包装器
  * [dcampbell24/iup-rust](https://raw.githubusercontent.com/dcampbell24/iup-rust) -  IUP绑定 [<img src="https://api.travis-ci.org/dcampbell24/iup-rust.svg?branch=master">](https://travis-ci.org/dcampbell24/iup-rust)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) - 基于IUP构建的简单UI框架 [![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* [libui](https://github.com/andlabs/libui)
  * [pcwalton/libui-rs](https://raw.githubusercontent.com/pcwalton/libui-rs) -  libui绑定 [<img src="https://api.travis-ci.org/pcwalton/libui-rs.svg?branch=master">](https://travis-ci.org/pcwalton/libui-rs) .  被遗弃的项目.  最新的分支是 [LeoTindall/libui-rs](https://raw.githubusercontent.com/LeoTindall/libui-rs).
* [Nuklear](https://github.com/vurtun/nuklear)
  * [nuklear-rust](https://raw.githubusercontent.com/snuk182/nuklear-rust) -  Nuklear的Rust绑定 [<img src="https://api.travis-ci.org/snuk182/nuklear-rust.svg?branch=master">](https://travis-ci.org/snuk182/nuklear-rust)
* [Qt](http://doc.qt.io)
  * [cyndis/qmlrs](https://raw.githubusercontent.com/cyndis/qmlrs) -  QtQuick绑定 [<img src="https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master">](https://travis-ci.org/cyndis/qmlrs)
  * [kitech/qt.rs](https://raw.githubusercontent.com/kitech/qt.rs) -  Qt5绑定 [<img src="https://api.travis-ci.org/kitech/qt.rs.svg?branch=master">](https://travis-ci.org/kitech/qt.rs)
  * [Rust Qt Binding Generator](https://phabricator.kde.org/source/rust-qt-binding-generator/) - 由KDE托管的绑定生成器.
  * [rust-qt](https://github.com/rust-qt) —
  * [White-Oak/qml-rust](https://raw.githubusercontent.com/White-Oak/qml-rust) -  QML绑定. [<img src="https://api.travis-ci.org/White-Oak/qml-rust.svg?branch=master">](https://travis-ci.org/White-Oak/qml-rust)
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 绑定
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://raw.githubusercontent.com/sciter-sdk/rust-sciter) -  Sciter绑定 [<img src="https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true">](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [flutter-rs](https://github.com/gliheng/flutter-rs) - 在飞镖和铁锈中构建扑动的桌面应用程序.

### Image processing

* [abonander/img_hash](https://github.com/abonander/img_hash) - 感知图像散列和相等性和相似性的比较.
* [PistonDevelopers/imageproc](https://github.com/PistonDevelopers/imageproc) - 基于`image`库的图像处理库. [![Build Status](https://api.travis-ci.org/PistonDevelopers/imageproc.svg?branch=master)](https://travis-ci.org/PistonDevelopers/imageproc)
* [PistonDevelopers/image](https://raw.githubusercontent.com/PistonDevelopers/image) - 用于转换图像格式和从图像格式转换的基本图像处理功能和方法 [<img src="https://api.travis-ci.org/PistonDevelopers/image.svg?branch=master">](https://travis-ci.org/PistonDevelopers/image)
* [kali/opencv-rust](https://raw.githubusercontent.com/kali/opencv-rust) -  OpenCV的Rust绑定 [<img src="https://api.travis-ci.org/kali/opencv-rust.svg?branch=cv2">](https://travis-ci.org/kali/opencv-rust)
* [teovoinea/steganography](https://raw.githubusercontent.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)]  - 一个简单的隐写术库 [<img src="https://api.travis-ci.org/teovoinea/steganography.svg?branch=master">](https://travis-ci.org/teovoinea/steganography)

### Language specification

* [shnewto/bnf](https://raw.githubusercontent.com/shnewto/bnf) - 用于解析Backus-Naur形式上下文无关语法的库. [<img src="https://api.travis-ci.org/shnewto/bnf.svg?branch=master">](https://travis-ci.org/shnewto/bnf)

### Logging

[[log](https://crates.io/keywords/log)]

* [rust-lang-nursery/log](https://github.com/rust-lang-nursery/log) -  Rust的日志记录实现 [![Build Status](https://api.travis-ci.org/rust-lang-nursery/log.svg?branch=master)](https://travis-ci.org/rust-lang-nursery/log)
* [slog-rs/slog](https://github.com/slog-rs/slog) -  Rust的结构化，可组合日志记录 [![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
* [sfackler/log4rs](https://github.com/sfackler/log4rs) - 高度可配置的日志框架，以Java的Logback和log4j库为模型 [![Build Status](https://api.travis-ci.org/sfackler/log4rs.svg?branch=master)](https://travis-ci.org/sfackler/log4rs)

### Macro

*可爱
  * [mattgathu/cute](https://github.com/mattgathu/cute) -  Rust中Python-esque列表推导的宏. [![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
*哈多
  * [ludat/hado-rs](https://github.com/ludat/hado-rs) - 写一个类似haskell的表达式，没有太多的仪式

### Markup language

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — [CommonMark](https://commonmark.org/) Rust中的解析器

### Mobile

[Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)

* Android
  * [tomaka/android-rs-glue](https://raw.githubusercontent.com/tomaka/android-rs-glue) -  Rust和Android之间的粘合剂 [<img src="https://api.travis-ci.org/tomaka/android-rs-glue.svg?branch=master">](https://travis-ci.org/tomaka/android-rs-glue)
* iOS
  * [TimNN/cargo-lipo](https://raw.githubusercontent.com/TimNN/cargo-lipo) - 货物lipo子命令，可自动创建用于iOS应用程序的通用库. [<img src="https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master">](https://travis-ci.org/TimNN/cargo-lipo)
  * [vhbit/ObjCrust](https://raw.githubusercontent.com/vhbit/ObjCrust) - 使用Rust创建iOS静态库 [<img src="https://api.travis-ci.org/vhbit/ObjCrust.svg?branch=master">](https://travis-ci.org/vhbit/ObjCrust)
*卵石
  * [andars/pebble.rs](https://github.com/andars/pebble.rs) - 一个允许Rust用于开发Pebble应用程序的板条箱.

### Network programming

* HTTP
  * [pop-os/parallel-getter](https://github.com/pop-os/parallel-getter) - 下载具有并行GET请求的文件，以最大化带宽使用.
  * [pop-os/url-crawler](https://github.com/pop-os/url-crawler) - 可配置的并行网络爬虫，旨在抓取网站内容.
  * [pop-os/url-scraper](https://github.com/pop-os/url-scraper) - 从HTML页面中截取URL
* FTP
  * [mattnenterprise/rust-ftp](https://raw.githubusercontent.com/mattnenterprise/rust-ftp) - 一个 [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) Rust的客户端 [<img src="https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-ftp)
* IPNetwork
  * [achanda/ipnetwork](https://raw.githubusercontent.com/achanda/ipnetwork) - 在纯Rust中使用IP网络的库 [<img src="https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master">](https://travis-ci.org/achanda/ipnetwork)
*低水平
  * [libpnet/libpnet](https://raw.githubusercontent.com/libpnet/libpnet) - 跨平台，低级别的网络 [<img src="https://api.travis-ci.org/libpnet/libpnet.svg?branch=master">](https://travis-ci.org/libpnet/libpnet)
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) - 用于客户端和服务器的快速开发和高度可扩展的生产部署的网络应用程序框架.
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) - 自定义TCP / UDP协议定义
  * [actix/actix](https://raw.githubusercontent.com/actix/actix) -  Rust的Actor库 [<img src="https://api.travis-ci.org/actix/actix.svg?branch=master">](https://travis-ci.org/actix/actix)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://raw.githubusercontent.com/thehydroimpulse/nanomsg.rs) — [nanomsg](https://nanomsg.org/) 绑定 [<img src="https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master">](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NNTP
  * [mattnenterprise/rust-nntp](https://raw.githubusercontent.com/mattnenterprise/rust-nntp) - 一个 [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) Rust的客户端 [<img src="https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-nntp)
* POP3
  * [mattnenterprise/rust-pop3](https://raw.githubusercontent.com/mattnenterprise/rust-pop3) - 一个 [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) Rust的客户端 [<img src="https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-pop3)
* SSH
  * [alexcrichton/ssh2-rs](https://raw.githubusercontent.com/alexcrichton/ssh2-rs) — [libssh2](https://www.libssh2.org/) 绑定 [<img src="https://api.travis-ci.org/alexcrichton/ssh2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
  * [Thrussh](https://github.com/pijul-scm/thrussh/) - 在Rust中从头开始编写的SSH库，由.提供支持 [libsodium](https://download.libsodium.org/doc/)
*踩踏
  * [zslayton/stomp-rs](https://raw.githubusercontent.com/zslayton/stomp-rs) - 一个 [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) Rust中的客户端实现 [<img src="https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
* uTP
  * [meqif/rust-utp](https://raw.githubusercontent.com/meqif/rust-utp) - 一个 [uTP](http://www.bittorrent.org/beps/bep_0029.html) Rust的（微传输协议）库. [<img src="https://api.travis-ci.org/meqif/rust-utp.svg?branch=master">](https://travis-ci.org/meqif/rust-utp)
* ZeroMQ
  * [erickt/rust-zmq](https://raw.githubusercontent.com/erickt/rust-zmq) — [ZeroMQ](http://zeromq.org/) 绑定 [<img src="https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master">](https://travis-ci.org/erickt/rust-zmq)
* CoAP
  * [Covertness/coap-rs](https://raw.githubusercontent.com/Covertness/coap-rs) - 一个 [Constrained Application Protocol(CoAP)](https://tools.ietf.org/html/rfc7252) Rust的库. [<img src="https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master">](https://travis-ci.org/Covertness/coap-rs)

### Parser

  * [Geal/nom](https://raw.githubusercontent.com/Geal/nom) - 解析器组合库 [<img src="https://api.travis-ci.org/Geal/nom.svg?branch=master">](https://travis-ci.org/Geal/nom)
  * [ivanceras/inquerest](https://github.com/ivanceras/inquerest) - 用于休息过滤器查询的URL参数解析器 [![Build Status](https://api.travis-ci.org/ivanceras/inquerest.svg?branch=master)](https://travis-ci.org/ivanceras/inquerest)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) - 解析表达式语法（PEG）解析器生成器
  * [m4rw3r/chomp](https://raw.githubusercontent.com/m4rw3r/chomp) - 快速monadic风格的解析器组合器 [<img src="https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master">](https://travis-ci.org/m4rw3r/chomp)
  * [Marwes/combine](https://raw.githubusercontent.com/Marwes/combine) - 解析器组合库 [<img src="https://api.travis-ci.org/Marwes/combine.svg?branch=master">](https://travis-ci.org/Marwes/combine)
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — LR(1) parser generator for Rust [![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
  * [nrc/zero](https://raw.githubusercontent.com/nrc/zero) - 二进制数据的零分配解析 [<img src="https://api.travis-ci.org/nrc/zero.svg?branch=master">](https://travis-ci.org/nrc/zero)
  * [pest-parser/pest](https://github.com/pest-parser/pest) - 优雅的解析器 [![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
  * [ptal/oak](https://github.com/ptal/oak) - 类型化的PEG解析器生成器（编译器插件）
  * [rustless/queryst](https://github.com/rustless/queryst) - 受https://github.com/ljharb/qs启发的Rust查询字符串解析库 [![Build Status](https://api.travis-ci.org/rustless/queryst.svg?branch=master)](https://travis-ci.org/rustless/queryst)

### Packaging formats

- [pop-os/debarchive](https://github.com/pop-os/debarchive) 用于阅读和提取debian档案的图书馆

### Platform specific

* Linux
  * [frol/cgroups-fs](https://raw.githubusercontent.com/frol/cgroups-fs) - 与Linux控制组（cgroups）的Rust绑定 [<img src="https://api.travis-ci.org/frol/cgroups-fs.svg?branch=master">](https://travis-ci.org/frol/cgroups-fs)
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) -  UDisks2 DBus API
  * [pop-os/distinst](https://github.com/pop-os/distinst/) -  Linux发行安装程序库
  * [inotify-rs/inotify](https://raw.githubusercontent.com/inotify-rs/inotify) — [inotify](https://en.wikipedia.org/wiki/Inotify) 绑定 [<img src="https://api.travis-ci.org/inotify-rs/inotify.svg?branch=master">](https://travis-ci.org/inotify-rs/inotify)
  * [arvancloud/nginx-rs](https://raw.githubusercontent.com/arvancloud/nginx-rs) — [Nginx](https://www.nginx.com) 绑定 [<img src="https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master">](https://travis-ci.org/arvancloud/nginx-rs)
  * [yaa110/rust-iptables](https://raw.githubusercontent.com/yaa110/rust-iptables) — [iptables](https://www.netfilter.org/projects/iptables/index.html) 绑定 [<img src="https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master">](https://travis-ci.org/yaa110/rust-iptables)
*类Unix
  * [nix-rust/nix](https://raw.githubusercontent.com/nix-rust/nix) - 类似Unix的API绑定 [<img src="https://api.travis-ci.org/nix-rust/nix.svg?branch=master">](https://travis-ci.org/nix-rust/nix)
  * [zargony/rust-fuse](https://raw.githubusercontent.com/zargony/rust-fuse) — [FUSE](https://raw.githubusercontent.com/libfuse/libfuse) 绑定 <img src="https://api.travis-ci.org/zargony/rust-fuse.svg?branch=master">
* Windows
  * [retep998/winapi-rs](https://raw.githubusercontent.com/retep998/winapi-rs) -  Windows API绑定 [<img src="https://api.travis-ci.org/retep998/winapi-rs.svg?branch=master">](https://travis-ci.org/retep998/winapi-rs)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) - 一个FreeBSD监狱库的Rust实现
  * [dlrobertson/capsicum-rs](https://github.com/dlrobertson/capsicum-rs) -  FreeBSD辣椒框架的Rust绑定

### Scripting
[[scripting](https://crates.io/keywords/scripting)]
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) - 生锈的动态类型脚本语言
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) - 一种小型，静态类型的函数式编程语言
* [murarth/ketos](https://github.com/murarth/ketos) - 一种Lisp方言函数式编程语言，用作生锈的脚本和扩展语言
* [JohnBSmith/moss](https://github.com/JohnBSmith/moss) [[moss](https://crates.io/crates/moss)]  - 动态类型的脚本语言
* [jonathandturner/rhai](https://github.com/jonathandturner/rhai) - 一种小巧而快速的嵌入式脚本语言，类似于JS和Rust的组合

### Template engine

*把手
  * [sunng87/handlebars-rust](https://raw.githubusercontent.com/sunng87/handlebars-rust) - 具有继承，自定义助手支持的Handlebars模板引擎. [<img src="https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  * [lfairy/maud](https://raw.githubusercontent.com/lfairy/maud) - 编译时HTML模板 [<img src="https://api.travis-ci.org/lfairy/maud.svg?branch=master">](https://travis-ci.org/lfairy/maud)
  * [Stebalien/horrorshow-rs](https://raw.githubusercontent.com/Stebalien/horrorshow-rs) - 编译时HTML模板 [<img src="https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master">](https://travis-ci.org/Stebalien/horrorshow-rs)
  * [kaj/ructe](https://raw.githubusercontent.com/kaj/ructe) -  Rust的HTML模板系统 [<img src="https://api.travis-ci.org/kaj/ructe.svg?branch=master">](https://travis-ci.org/kaj/ructe)
  * [Keats/tera](https://raw.githubusercontent.com/Keats/tera) - 基于Jinja2和Django模板语言的模板引擎. [<img src="https://api.travis-ci.org/Keats/tera.svg?branch=master">](https://travis-ci.org/Keats/tera)
  * [djc/askama](https://raw.githubusercontent.com/djc/askama) - 基于Jinja的模板渲染引擎 [<img src="https://api.travis-ci.org/djc/askama.svg?branch=master">](https://travis-ci.org/djc/askama)
*小胡子
  * [rustache/rustache](https://raw.githubusercontent.com/rustache/rustache) — [<img src="https://api.travis-ci.org/rustache/rustache.svg?branch=master">](https://travis-ci.org/rustache/rustache)
* [tailhook/marafet](https://github.com/tailhook/marafet) - 将类似Jade的模板语言编译为基于cito.js的虚拟dom

### Text processing

* [BurntSushi/suffix](https://raw.githubusercontent.com/BurntSushi/suffix) - 线性时间后缀数组结构（支持Unicode） [<img src="https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master">](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://raw.githubusercontent.com/BurntSushi/tabwriter) - 弹性制表位（即文本列对齐） [<img src="https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master">](https://travis-ci.org/BurntSushi/tabwriter)
* [dguo/strsim-rs](https://raw.githubusercontent.com/dguo/strsim-rs) [[strsim-rs](https://crates.io/crates/strsim)]  - 字符串相似性度量 [<img src="https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master">](https://travis-ci.org/dguo/strsim-rs)
* [mgeisler/textwrap](https://raw.githubusercontent.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)]  - 自动换行文字（支持连字符） [<img src="https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master">](https://travis-ci.org/mgeisler/textwrap)
* [pwoolcoc/ngrams](https://raw.githubusercontent.com/pwoolcoc/ngrams) - 构造 [n-grams](https://en.wikipedia.org/wiki/N-gram) 来自任意迭代器 [<img src="https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master">](https://travis-ci.org/pwoolcoc/ngrams)
* [ps1dr3x/easy_reader](https://raw.githubusercontent.com/ps1dr3x/easy_reader) - 允许通过大型文件行进行前进，后退和随机导航而不消耗迭代器的阅读器 [<img src="https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master">](https://travis-ci.org/ps1dr3x/easy_reader)
* [rust-lang/regex](https://raw.githubusercontent.com/rust-lang/regex) - 正则表达式（RE2样式） [<img src="https://api.travis-ci.org/rust-lang/regex.svg?branch=master">](https://travis-ci.org/rust-lang/regex)
* [greyblake/whatlang-rs](https://raw.githubusercontent.com/greyblake/whatlang-rs) - 基于三元组的自然语言检测库 [<img src="https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master">](https://travis-ci.org/greyblake/whatlang-rs)
* [yaa110/rake-rs](https://raw.githubusercontent.com/yaa110/rake-rs) -  Rust的RAKE算法的多语言实现 [<img src="https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master">](https://travis-ci.org/yaa110/rake-rs)
* [Lucretiel/joinery](https://raw.githubusercontent.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)]  - 通用字符串+可迭代连接 [<img src="https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master">](https://travis-ci.org/Lucretiel/joinery)

### Text search

* [BurntSushi/fst](https://raw.githubusercontent.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] — [<img src="https://api.travis-ci.org/BurntSushi/fst.svg?branch=master">](https://travis-ci.org/BurntSushi/fst)
* [CurrySoftware/perlin](https://raw.githubusercontent.com/CurrySoftware/perlin) [[perlin](https://crates.io/crates/perlin)] — [<img src="https://api.travis-ci.org/CurrySoftware/perlin.svg?branch=master">](https://travis-ci.org/CurrySoftware/perlin)
* [tantivy-search/tantivy](https://raw.githubusercontent.com/tantivy-search/tantivy) [[tantivy](https://crates.io/crates/tantivy)] — [<img src="https://api.travis-ci.org/tantivy-search/tantivy.svg?branch=master">](https://travis-ci.org/tantivy-search/tantivy)

### Virtualization

* [beneills/quantum](https://raw.githubusercontent.com/beneills/quantum) - 高级Rust量子计算机模拟器 [<img src="https://api.travis-ci.org/beneills/quantum.svg?branch=master">](https://travis-ci.org/beneills/quantum)
* [ekse/unicorn-rs](https://github.com/ekse/unicorn-rs) - 独角兽CPU仿真器的Rust绑定
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) -  OS X上的硬件加速虚拟化

### Web programming

也可以看看 [Are we web yet?](http://www.arewewebyet.org) 和 [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

*客户端/ WASM
  * [DenisKolodin/yew](https://github.com/DenisKolodin/yew) [[yew](https://crates.io/crates/yew)]  - 用于制作客户端Web应用程序的Rust框架
  * [koute/cargo-web](https://github.com/koute/cargo-web) [[cargo-web](https://crates.io/crates/cargo-web)]  - 客户端Web的Cargo子命令 [![Build Status](https://api.travis-ci.org/koute/cargo-web.svg)](https://travis-ci.org/koute/cargo-web)
  * [koute/stdweb](https://github.com/koute/stdweb) [[stdweb](https://crates.io/crates/stdweb)]  - 客户端Web的标准库 [![Build Status](https://api.travis-ci.org/koute/stdweb.svg)](https://travis-ci.org/koute/stdweb)
* HTTP客户端
  * [alexcrichton/curl-rust](https://raw.githubusercontent.com/alexcrichton/curl-rust) — [libcurl](https://curl.haxx.se/libcurl/) 绑定 [<img src="https://api.travis-ci.org/alexcrichton/curl-rust.svg?branch=master">](https://travis-ci.org/alexcrichton/curl-rust)
  * [hyperium/hyper](https://raw.githubusercontent.com/hyperium/hyper) -  HTTP实现 [<img src="https://api.travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [seanmonstar/reqwest](https://raw.githubusercontent.com/seanmonstar/reqwest) - 适用于Rust的符合人体工程学的HTTP客户端. [<img src="https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master">](https://travis-ci.org/seanmonstar/reqwest)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) - 美丽而优雅的Yukikaze是基于超级的小型HTTP客户端库. [<img src="https://gitlab.com/Douman/yukikaze/badges/master/build.svg">](https://gitlab.com/Douman/yukikaze)
* HTTP服务器
  * [actix/actix-web](https://raw.githubusercontent.com/actix/actix-web) -  Rust的轻量级异步Web框架，支持websocket [<img src="https://api.travis-ci.org/actix/actix-web.svg?branch=master">](https://travis-ci.org/actix/actix-web)
  * [return/branca](https://raw.githubusercontent.com/return/branca) [[branca](https://crates.io/crates/branca)]  -  Branca的Pure Rust实现，用于经过身份验证和加密的API令牌. [<img src="https://api.travis-ci.org/return/branca.svg?branch=master">](https://travis-ci.org/return/branca)
  * [Gotham](https://raw.githubusercontent.com/gotham-rs/gotham) - 灵活的Web框架，不会牺牲安全性，安全性或速度. [<img src="https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master">](https://travis-ci.org/gotham-rs/gotham)
  * [hyperium/hyper](https://raw.githubusercontent.com/hyperium/hyper) -  HTTP实现 [<img src="https://api.travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [GildedHonour/frank_jwt](https://raw.githubusercontent.com/GildedHonour/frank_jwt) -  Rust中的JSON Web Token实现. [<img src="https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master">](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Iron](https://raw.githubusercontent.com/iron/iron) - 基于中间件的服务器框架 [<img src="https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master">](https://travis-ci.org/GildedHonour/frank_jwt)
  * [sunng87/handlebars-iron](https://raw.githubusercontent.com/sunng87/handlebars-iron) — [Handlebars-rust](https://raw.githubusercontent.com/sunng87/handlebars-rust) 作为Iron Web框架中间件. [<img src="https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-iron)
  * [Nickel](https://raw.githubusercontent.com/nickel-org/nickel.rs/) - 灵感来自 [Express](http://expressjs.com/) [<img src="https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master">](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful](https://raw.githubusercontent.com/Ogeon/rustful) -  Rust的RESTful Web框架  [<img src="https://api.travis-ci.org/Ogeon/rustful.svg?branch=master">](https://travis-ci.org/Ogeon/rustful)
  * [Rocket](https://raw.githubusercontent.com/SergioBenitez/Rocket) -  Rocket是Rust（夜间）的Web框架，侧重于易用性，可表达性和速度 [<img src="https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master">](https://travis-ci.org/SergioBenitez/Rocket)
  * [Rustless](https://raw.githubusercontent.com/rustless/rustless) - 受类似REST的API微框架的启发 [Grape](https://raw.githubusercontent.com/ruby-grape/grape) 和 [Hyper](https://raw.githubusercontent.com/hyperium/hyper) [<img src="https://api.travis-ci.org/rustless/rustless.svg?branch=master">](https://travis-ci.org/rustless/rustless)
  * [Saphir](https://github.com/richerarc/saphir) - 具有低级别控制的渐进式Web框架，没有痛苦.
  * [sappworks/sapper](https://raw.githubusercontent.com/sappworks/sapper) - 基于async hyper构建的轻量级Web框架，以Rust语言实现. [<img src="https://api.travis-ci.org/sappworks/sapper.svg?branch=master">](https://travis-ci.org/sappworks/sapper)
  * [tiny-http](https://raw.githubusercontent.com/tiny-http/tiny-http) - 低级HTTP服务器库 [<img src="https://api.travis-ci.org/frewsxcv/tiny-http.svg?branch=master">](https://travis-ci.org/frewsxcv/tiny-http)
  * [tomaka/rouille](https://raw.githubusercontent.com/tomaka/rouille) -  Rust中的Web框架 [<img src="https://api.travis-ci.org/tomaka/rouille.svg?branch=master">](https://travis-ci.org/tomaka/rouille)
  * [carllerche/tower-web](https://raw.githubusercontent.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)]  -  Rust的快速，无样板，Web框架 [<img src="https://api.travis-ci.org/carllerche/tower-web.svg?branch=master">](https://travis-ci.org/carllerche/tower-web)
  * [danclive/sincere](https://raw.githubusercontent.com/danclive/sincere) - 基于超线程和多线程的Rust（稳定）微网框架. [<img src="https://api.travis-ci.org/danclive/sincere.svg?branch=master">](https://travis-ci.org/danclive/sincere)
  * [oltdaniel/zap](https://raw.githubusercontent.com/oltdaniel/zap) -  Rust的快速http框架 [<img src="https://api.travis-ci.org/oltdaniel/zap.svg?branch=master">](https://travis-ci.org/oltdaniel/zap)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [cyderize/rust-websocket](https://raw.githubusercontent.com/cyderize/rust-websocket) - 处理WebSocket连接的框架（客户端和服务器） [<img src="https://api.travis-ci.org/cyderize/rust-websocket.svg?branch=master">](https://travis-ci.org/cyderize/rust-websocket)
  * [housleyjk/ws-rs](https://raw.githubusercontent.com/housleyjk/ws-rs) -  Rust的轻量级，事件驱动的WebSockets [<img src="https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable">](https://travis-ci.org/housleyjk/ws-rs)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) -  Rust的基于流的基于WebSocket的轻量级实现.
  * [actix/sockjs](https://raw.githubusercontent.com/actix/sockjs) — [SockJS](https://raw.githubusercontent.com/sockjs) Rust的服务器 [<img src="https://api.travis-ci.org/actix/sockjs.svg?branch=master">](https://travis-ci.org/actix/sockjs)
  * [vityafx/urlshortener-rs](https://raw.githubusercontent.com/vityafx/urlshortener-rs) [[urlshortener](https://crates.io/crates/urlshortener)]  -  Rust的一个非常简单的urlshortener库. [<img src="https://api.travis-ci.org/vityafx/urlshortener-rs.svg?branch=master">](https://travis-ci.org/vityafx/urlshortener-rs)
*杂项
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) - 用于构建可维护的，经过良好分解的Web应用程序的Web框架.
  * [pyros2097/rust-embed](https://github.com/pyros2097/rust-embed) - 将静态资源嵌入到生锈二进制文件中的宏
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)]  - 从HTML文档中提取有用数据的库，适用于Web抓取. [![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
*反向代理
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)]  -  HTTP反向代理. [![Build Status](https://api.travis-ci.org/sozu-proxy/sozu.svg?branch=master)](https://api.travis-ci.org/sozu-proxy/sozu)
*静态站点生成器
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)]  - 一个固定的静态站点生成器，内置所有内容. [![Build Status](https://api.travis-ci.org/getzola/zola.svg?branch=master)](https://travis-ci.org/getzola/zola)
  * [cobalt-org/cobalt.rs](https://raw.githubusercontent.com/cobalt-org/cobalt.rs) - 用Rust编写的静态站点生成器 [<img src="https://api.travis-ci.org/cobalt-org/cobalt.rs.svg?branch=master">](https://travis-ci.org/cobalt-org/cobalt.rs)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) - 来自markdown文件的静态站点生成器.
  * [leven-the-blog/leven](https://raw.githubusercontent.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)]  - 一个简单的并行化博客生成器. [<img src="https://api.travis-ci.org/leven-the-blog/leven.svg?branch=master">](https://travis-ci.org/leven-the-blog/leven)

### Peripherals

* 串行端口
  * [Susurrus/serialport-rs](https://github.com/Susurrus/serialport-rs) [[serialport](https://docs.rs/serialport/3.0.0/serialport/)]  - 提供对串行端口的访问的跨平台库

## Resources

*基准
  * [TeXitoi/benchmarksgame-rs](https://raw.githubusercontent.com/TeXitoi/benchmarksgame-rs) -  Rust的实现 [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) [<img src="https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master">](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
*甲板和演示文稿
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) - 提出者 [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) - 提出者 [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) - 提出者 [Nicholas Matsakis](https://github.com/nikomatsakis) @ C ++ Now 2018
*学习
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) - 编程社区投票推荐的资源清单.
  * [exercism.io](https://exercism.io/tracks/rust) - 编程练习，帮助您学习Rust中的新概念.
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) - 同行评审的文章/讲座/回购集合，教授惯用的Rust.
  * [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) - 通过实现几种不同类型的列表结构，深入探索Rust的内存管理规则.
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - 一组简单的示例，演示了使用Rust生态系统的板条箱完成常见编程任务的良好实践.
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - 一个视频系列 [Carol Nichols](https://github.com/carols10cents) 和 [Jake Goulding](https://github.com/shepmaster) （付费）
  * [rust-learning](https://github.com/ctjhoa/rust-learning) - 学习Rust的有用资源的集合
  * [Rustlings](https://github.com/rustlings/rustlings) - 小练习让你习惯阅读和编写Rust代码
  * [stdx](https://github.com/brson/stdx) - 首先学习这些板条箱作为标准的扩展
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
*播客
  * [New Rustacean](https://newrustacean.com) - 关于学习Rust的播客
  * [Rusty Spike](https://rusty-spike.blubrry.net) - 所有Rust的新闻
* [RustCamp 2015 Talks](http://confreaks.tv/events/rustcamp2015)
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [RustBooks](https://github.com/sger/RustBooks) -  RustBooks列表
* [Rust Subreddit](https://www.reddit.com/r/rust/) - 发布和讨论与锈相关的问题，文章和资源的subreddit（论坛）

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
