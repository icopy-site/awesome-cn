<div class="github-widget" data-repo="naimo84/awesome-nodered"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Node-RED [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <a href="https://nodered.org/"><img src="https://nodered.org/about/resources/media/node-red-hexagon.png" width="200" align="right" alt="Node-RED"></a>

&gt; Node-RED 有用资源的精选列表.

[Node-RED](https://nodered.org/) 是一种编程工具，用于以新颖有趣的方式将硬件设备、API 和在线服务连接在一起.

它提供了一个基于浏览器的编辑器，可以使用调色板中的各种节点轻松地将流连接在一起，只需单击一下即可将其部署到其运行时.



## Installation

- [Running locally](https://nodered.org/docs/getting-started/local)
- [Running under Docker](https://github.com/node-red/node-red-docker)
- [c't-Smart-Home](https://github.com/ct-Open-Source/ct-Smart-Home) - 一个现成的家庭自动化设置，由维护 [german computer magazine c't](https://www.ct.de/smarthome).
- [Home Assistant Community Add-on](https://community.home-assistant.io/t/home-assistant-community-add-on-node-red/55023) - 在 Home Assistant 中启动一个实例并与之通信.
- [ioBroker node-red Adapter](https://github.com/ioBroker/ioBroker.node-red) - 在 ioBroker 中启动一个实例并与之通信.
- [openHAB running on openHABian](https://www.openhab.org/docs/installation/openhabian.html#optional-components) - 从命令行使用 openhab-config 安装 Node-RED，从“可选组件”中选择它.
- [RedMatic](https://github.com/rdmtc/RedMatic/wiki/Installation) - 在制造商 eQ-3 的智能家居自动化硬件 CCU3 上安装 Node-RED，在德国尤其受欢迎.

## Documentation

- [Getting Started](https://nodered.org/docs/getting-started/)
- [FAQ](https://nodered.org/docs/faq/)
- [Tutorials](https://nodered.org/docs/tutorials/)
- [User Guide](https://nodered.org/docs/user-guide/)
## Nodes

### Analysis

- [badwords](https://github.com/node-red/node-red-nodes/tree/master/analysis/swearfilter)  - 分析有效负载并尝试过滤掉任何包含脏话的消息. 这仅适用于字符串类型的有效负载. 其他一切都被阻止.
- [wordpos](https://github.com/node-red/node-red-nodes/tree/master/analysis/wordpos)  - 分析有效载荷并对每个单词的词性进行分类. 生成的消息在结果中添加了 msg.pos. 一个词可能出现在多个类别中（例如，“great”既是名词又是形容词）.

### Database

- [influxdb](https://github.com/mblackstock/node-red-contrib-influxdb) - 从 InfluxDB 时间序列数据库中保存和查询数据.
- [mssql-plus](https://github.com/bestlong/node-red-contrib-mssql-plus) - 在 Microsoft SQL Server 和 Azure 数据库 SQL2000 ~ SQL2019 中执行查询、存储过程和批量插入.
- [stackhero-influxdb-v2](https://github.com/stackhero-io/node-red-contrib-stackhero-influxdb-v2) - 从 InfluxDB v2 时间序列数据库中保存和查询数据.
- [stackhero-mysql](https://github.com/stackhero-io/node-red-contrib-stackhero-mysql) - 连接到 MySQL 或 MariaDB 数据库，使用 TLS (SSL) 并兼容“缓存 SHA2 密码”身份验证方法 (MySQL &gt;= 8).
- [leveldb](https://github.com/node-red/node-red-nodes/tree/master/storage/leveldb) - 将 LevelDB 用于简单的键值对数据库.
- [mysql](https://github.com/node-red/node-red-nodes/tree/master/storage/mysql) - 允许对 MySQL 数据库进行基本访问. 
- [sqlite](https://github.com/node-red/node-red-nodes/tree/master/storage/sqlite) - 支持读取和写入本地 sqlite 数据库.

### Development

- [typescript-starter](https://github.com/alexk111/node-red-node-typescript-starter) - 用于在 TypeScript 中创建新节点集的快速启动模板存储库.

### Function

- [datagenerater](https://github.com/node-red/node-red-nodes/tree/master/function/datagenerator) - 生成各种格式、名称、地址、电子邮件、数字、单词等的虚拟数据.
- [pidcontrol](https://github.com/node-red/node-red-nodes/tree/master/function/PID) - 数字输入的 PID 控制节点 - 提供简单的控制回路反馈能力.
- [random](https://github.com/node-red/node-red-nodes/tree/master/function/random) - 随机数生成器 - 可以为 x 到 y 生成整数 - 或在 x 和 y 之间浮动.
- [rbe](https://github.com/node-red/node-red-nodes/tree/master/function/rbe) - 为简单的输入提供异常报告和死区/带隙功能.
- [smooth](https://github.com/node-red/node-red-nodes/tree/master/function/smooth) - 提供跨越多个先前值的各种函数，包括最大值、最小值、平均值、高通和低通滤波器.

### Hardware

- [arduino](https://github.com/node-red/node-red-nodes/tree/master/hardware/Arduino) - 使用firmata 协议与董事会对话.
- [beaglebone](https://github.com/node-red/node-red-nodes/tree/master/hardware/BBB) - 节点 [Beaglebone Black](https://beagleboard.org/black).
- [blink1](https://github.com/node-red/node-red-nodes/tree/master/hardware/blink1) - [Blink1](https://blink1.thingm.com/) ThingM 的 USB LED.
- [blinkstick](https://github.com/node-red/node-red-nodes/tree/master/hardware/blinkstick) - [BlinkStick](https://www.blinkstick.com/) USB LED 设备.
- [digirgb](https://github.com/node-red/node-red-nodes/tree/master/hardware/digiRGB) - DigiSpark RGB USB LED.
- [heatmiser](https://github.com/node-red/node-red-nodes/tree/master/hardware/heatmiser) - Heatmiser 恒温器的温度和霜冻保护.
- [intel-galileo](https://github.com/node-red/node-red-nodes/tree/master/hardware/intel) - 英特尔伽利略和爱迪生的收藏.
- [ledborg](https://github.com/node-red/node-red-nodes/tree/master/hardware/LEDborg) - [LEDborg](https://www.piborg.org/ledborg) 插入模块.
- [makeymakey](https://github.com/node-red/node-red-nodes/tree/master/hardware/makey) - 从一个读 [MakeyMakey](http://www.makeymakey.com/) 输入设备.
- [pi-gpiod](https://github.com/node-red/node-red-nodes/tree/master/hardware/pigpiod) - 允许远程访问的默认 PI GPIO 节点的替代方案.
- [pi-mcp3008](https://github.com/node-red/node-red-nodes/tree/master/hardware/mcp3008) - 通过 SPI 总线读取 MCP300x 系列模数转换器芯片.
- [pi-neopixel](https://github.com/node-red/node-red-nodes/tree/master/hardware/neopixel) - 直接驱动一条 NeoPixels.
- [pi-unicorn-hat](https://github.com/node-red/node-red-nodes/tree/master/hardware/unicorn) - Controls a Pimorini Unicorn HAT 8x8 LED display.
- [pibrella](https://github.com/node-red/node-red-nodes/tree/master/hardware/Pibrella) - 控制一个 [Pibrella](https://pibrella.com/) 附加板.
- [piface](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiFace) - [PiFace](https://www.piface.org.uk/) 接口模块.
- [piliter](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiLiter) - 控制 Pimorini Pi-LITER 8 LED 附加板.
- [sensortag](https://github.com/node-red/node-red-nodes/tree/master/hardware/sensorTag) - 从 Ti 蓝牙低功耗 SensorTag 设备读取数据.
- [wemo](https://github.com/node-red/node-red-nodes/tree/master/hardware/wemo) - 驾驶 [WeMo](https://www.belkin.com/us/Products/home-automation/c/wemo-home-automation/) 插座和开关.
- [scanBLE](https://github.com/node-red/node-red-nodes/tree/master/hardware/scanBLE) - 扫描特定的低功耗蓝牙设备.

### I/O

- [discovery](https://github.com/node-red/node-red-nodes/tree/master/io/mdns) - 发现网络上的其他 Avahi/Bonjour 服务.
- [emoncms](https://github.com/node-red/node-red-nodes/tree/master/io/emoncms) - 发布到 [Emoncms](https://emoncms.org/) 服务器.
- [noble-bluetooth](https://github.com/clausbroch/node-red-contrib-noble-bluetooth) - 基于高贵与低功耗蓝牙设备的交互.
- [mindconnect](https://github.com/mindsphere/node-red-contrib-mindconnect) - 将时间序列、文件和事件上传到 MindSphere.
- [modbus](https://github.com/biancoroyal/node-red-contrib-modbus) - 多合一 Modbus TCP 和串行包.
- [mqlight](https://github.com/node-red/node-red-nodes/tree/master/io/mqlight) - 添加节点以使用 MQlight 发送和接收.
- [ping](https://github.com/node-red/node-red-nodes/tree/master/io/ping) - ping 一台机器并以毫秒为单位返回行程时间.
- [s7](https://github.com/st-one-io/node-red-contrib-s7) - 与西门子 S7 PLC 交互.
- [serialport](https://github.com/node-red/node-red-nodes/tree/master/io/serialport) - 向物理串行端口发送消息和从物理串行端口接收消息.
- [snmp](https://github.com/node-red/node-red-nodes/tree/master/io/snmp) - 单个 OID 或 OID 表的 SNMP 接收器.
- [stomp](https://github.com/node-red/node-red-nodes/tree/master/io/stomp) - 发布和订阅 [STOMP server](https://stomp.github.io/implementations.html#STOMP_Servers).
- [wol](https://github.com/node-red/node-red-nodes/tree/master/io/wol) - 将 Wake-On-LAN 魔术包发送到指定的 mac 地址.
- [xiaomi-ble](https://github.com/eschava/node-red-contrib-xiaomi-ble) - 从小米 BLE（蓝牙 4）获取所有已知数据的单个“小米 BLE”节点.

### Image processing

- [image-output](https://github.com/rikukissa/node-red-contrib-image-output)  - 简单的图像输出节点. 用于在流编辑器中预览图像（面部检测、对象识别等）.
- [image-tools](https://flows.nodered.org/node/node-red-contrib-image-tools) - 编辑图像、构建和解码 2D 和 3D 条形码.

### Parsers

- [base64](https://github.com/node-red/node-red-nodes/tree/master/parsers/base64) - 将有效负载转换为/从 base64 编码格式.
- [buffer-parser](https://flows.nodered.org/node/node-red-contrib-buffer-parser)  - 在缓冲区/数组之间转换值. 支持 Big/Little Endian、BCD、字节交换等等.
- [geohash](https://github.com/node-red/node-red-nodes/tree/master/parsers/geohash) - 将 lat、lon 有效负载转换为 geohash 格式/从 geohash 格式转换.
- [msgpack](https://github.com/node-red/node-red-nodes/tree/master/parsers/msgpack) - 将有效负载转换为 msgpack 二进制打包格式/从 msgpack 二进制打包格式转换.
- [what3words](https://github.com/node-red/node-red-nodes/tree/master/parsers/what3words) - 将 lat、lon 位置编码或解码为 what3words 文本格式.

### Smarthome

- [alexa-home](https://github.com/mabunixda/node-red-contrib-alexa-home) - 仅在本地网络中与 Alexa 连接 - 不需要额外的云内容.
- [alexa-home-skill-v3](https://github.com/coldfire84/node-red-contrib-alexa-home-skill-v3) - 通过 Alexa 和 Google Home 控制事物.
    - [alexa-home-skill-v3-web](https://github.com/coldfire84/node-red-alexa-home-skill-v3-web) - Alexa 和 Google Home 的网络服务.
    - [alexa-home-skill-v3-lambda](https://github.com/coldfire84/node-red-alexa-home-skill-v3-lambda) - node-red-alexa-home-skill-v3-web 的 Lambda 函数.
- [alexa-remote2-applestrudel](https://github.com/bbindreiter/node-red-contrib-alexa-remote2-applestrudel)  - 与 Alexa API 交互. 模拟日常行为、控制和查询您的设备.
- [avr-yamaha](https://github.com/krauskopf/node-red-contrib-avr-yamaha) - 通过 YNCA 协议集成和控制 YAMAHA™ 音频/视频接收器.
- [ccu](https://github.com/rdmtc/node-red-contrib-ccu) - 与制造商 eQ-3 的一系列智能家居自动化硬件 Homematic 连接，在德国尤其受欢迎.
- [deconz](https://github.com/deconz-community/node-red-contrib-deconz) - 通过 deCONZ 访问 Zigbee 3.0 (Z30)、Zigbee 家庭自动化 (ZHA) 和 Zigbee Light Link (ZLL) 灯.
- [fritz](https://github.com/bashgroup/node-red-contrib-fritz)  - 提供对您的 AVM Fritz!Box 的轻松访问. 读写配置，包括 VoIP 和 Dect 配置.
- [fritzapi](https://github.com/dnknth/node-red-contrib-fritzapi) - 通过 AVM Fritz!Box 控制智能家居 DECT 设备和访客 wifi.
- [harmony](https://github.com/Aietes/node-red-contrib-harmony) - 控制连接到 Logitech™ Harmony Hub 的设备.
- [home-assistant](https://github.com/AYapejian/node-red-contrib-home-assistant) - 与家庭助理联系.
- [home-assistant-websocket](https://github.com/zachowj/node-red-contrib-home-assistant-websocket) - 各种节点使用 websocket 来协助建立与 Home Assistant 的通信.
- [homebridge-automation](https://github.com/NorthernMan54/node-red-contrib-homebridge-automation) - 将 Homebridge 配件集成到流程中.
- [homee](https://github.com/stfnhmplr/node-red-contrib-homee) - 访问 homee api 并为 homee 创建虚拟设备.
- [homekit-bridged](https://github.com/NRCHKB/node-red-contrib-homekit-bridged) - 模仿 HomeKit 设备.
- [huemagic](https://github.com/Foddy/node-red-contrib-huemagic) - 控制飞利浦 Hue 桥、灯、组、场景、规则、水龙头、开关、按钮、运动传感器、温度传感器和 Lux 传感器.
- [lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - 控制 LG webOS 智能电视.
- [loxone](https://github.com/codmpm/node-red-contrib-loxone) - 连接到 Loxone 迷你服务器.
- [knx-ultimate](https://github.com/Supergiovane/node-red-contrib-knx-ultimate)  - 控制 KNX 安装. 带有可选的 ETS 组地址导入器和网关模拟. 
- [openhab3](https://github.com/jeroenhendricksen/node-red-contrib-openhab3) - openHAB 项目状态和命令的集成.
- [power-saver](https://power-saver.smoky.no/) - 自动节省可变电价的费用.
- [smartnora](https://github.com/andrei-tatar/node-red-contrib-smartnora) - 通过 Smart NORA 集成 Google 智能家居操作.
- [sonos-plus](https://github.com/hklages/node-red-contrib-sonos-plus) - 控制本地网络中的 Sonos 播放器.
- [tado-client](https://github.com/mattdavis90/node-red-contrib-tado-client) - 连接到 Tado Web API.
- [tahoma](https://github.com/nikkow/node-red-contrib-tahoma) - 控制 Somfy Tahoma 盒子（卷帘百叶窗等）. 
- [tasmota](https://github.com/DaveMDS/node-red-contrib-tasmota) - 用于楼宇自动化的 Tasmota 设备集成.
- [tuya-smart](https://github.com/hgross/node-red-contrib-tuya-smart) - 与涂鸦智能插头、灯泡等接口.
- [zigbee](https://github.com/hobbyquaker/node-red-contrib-zigbee) - 通过 CC253x 模块控制 Zigbee 设备.
- [zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) - Zigbee2mqtt 连接.
- [zwave-js](https://github.com/zwave-js/node-red-contrib-zwave-js) - 基于 Z-Wave JS 集成 Z-Wave 节点.

### Social

- [chatbot](https://github.com/guidone/node-red-contrib-chatbot) - Telegram、Facebook Messenger、Viber、Twilio 和 Slack 的全功能聊天机器人.
- [discord-advanced](https://github.com/Markoudstaal/node-red-contrib-discord-advanced) - 通过 Discord.js 与 Discord 交互.
- [dweetio](https://github.com/node-red/node-red-nodes/tree/master/social/dweetio) - 用途 [dweetio](https://dweet.io/) 发送/接收消息.
- [email](https://github.com/node-red/node-red-nodes/tree/master/social/email) - 发送和接收来自 gmail 或 smtp 或 imap 服务器等服务的简单电子邮件.
- [feedparser](https://github.com/node-red/node-red-nodes/tree/master/social/feedparser) - 从 atom 或 rss feed 读取消息.
- [irc](https://github.com/node-red/node-red-nodes/tree/master/social/irc) - 连接到 IRC 服务器以发送和接收消息.
- [notify](https://github.com/node-red/node-red-nodes/tree/master/social/notify) - 用途 [Growl](https://growl.info/) 提供桌面弹出窗口. 仅在本地 Apple 机器上有用.
- [prowl](https://github.com/node-red/node-red-nodes/tree/master/social/prowl) - 用途 [Prowl](https://www.prowlapp.com/) 推送到安装了 Prowl 应用程序的 Apple 设备.
- [pushbullet](https://github.com/node-red/node-red-nodes/tree/master/social/pushbullet) - 用途 [PushBullet](https://www.pushbullet.com/) 推送安装了该应用程序的 Android 设备.
- [pusher](https://github.com/node-red/node-red-nodes/tree/master/social/pusher) - 发布订阅 [Pusher](https://pusher.com/) 频道/事件.
- [pushover](https://github.com/node-red/node-red-nodes/tree/master/social/pushover) - 通过发送警报 [Pushover](https://pushover.net/).
- [PushStaq](https://github.com/pantchox/node-red-contrib-pushstaq) - 使用推送通知从您的 Node-Red 流向任何设备发送实时警报 [PushStaq](https://www.pushstaq.com).
- [slack](https://github.com/yayadrian/node-red-slack) - 与 Slack API 交互.
- [sms77](https://github.com/sms77io/nodered-contrib-sms77) - 用途 [sms77](https://www.sms77.io/) 短信、文字转语音电话和号码查询服务.
- [telegrambot](https://github.com/windkh/node-red-contrib-telegrambot) - 包含充当 Telegram Bot 的接收者和发送者节点.
- [twilio](https://github.com/node-red/node-red-nodes/tree/master/social/twilio) - 用途 [Twilio](https://www.twilio.com/) 发送/接收短信的服务.
- [whin](https://github.com/inUtil-info/node-red-contrib-whin) - 从节点流中发送和接收whatsapps.
- [xmpp](https://github.com/node-red/node-red-nodes/tree/master/social/xmpp) - 连接到 XMPP 服务器以发送和接收消息.
- [open-wa (whatsapp)](https://github.com/open-wa/node-red-contrib-wa-automate) - 有效连接到您的 open-wa whatsapp 自动化服务器的远程实例.

### System

- [aedes](https://github.com/martin-doyle/node-red-contrib-aedes) - 基于 Aedes 的 MQTT 代理.
- [dockerode](https://github.com/naimo84/node-red-contrib-dockerode) - 连接到 Docker 守护进程.
- [os](https://github.com/Argonne-National-Laboratory/node-red-contrib-os) - 获取系统信息.

### Time

- [blindcontroller](https://github.com/alisdairjsmyth/node-red-contrib-blindcontroller) - 根据太阳的当前位置自动控制家用卷帘.
- [bigtimer](https://github.com/scargill/node-red-contrib-bigtimer)  - 时间节点支持黄昏/日落黎明/日出和变化以及日/周/月（和特殊日子）控制. 该节点提供适用于 MQTT、语音和数据库的输出.
- [cron-plus](https://flows.nodered.org/node/node-red-contrib-cron-plus) - 具有完全动态控制和时区支持的灵活调度程序（cron、太阳能事件、简单日期）节点.
- [suncalc](https://github.com/node-red/node-red-nodes/tree/master/time/suncalc) - 使用 suncalc 模块根据指定位置在日出和日落时生成输出. 
- [simpletime](https://github.com/Paul-Reed/node-red-contrib-simpletime) - 添加具有各种格式选项的时间和日期有效负载，可以在流程中稍后检索和使用.
- [sun-position](https://github.com/rdmtc/node-red-contrib-sun-position)  - 基于定时器的流量控制，包括黄昏、黎明（和变化）等等. 另外，您可以获得太阳和月亮位置或通过太阳或月亮位置控制流量.
- [timeswitch](https://github.com/node-red/node-red-nodes/tree/master/time/timeswitch) - 让用户设置简单的重复计时器，例如简单的加热控制等.

### Utility

- [actionflows](https://github.com/Steveorevo/node-red-contrib-actionflows) - 带来易于使用的循环和 OOP（面向对象编程）功能.
- [alarm](https://github.com/Anamico/node-red-contrib-alarm) - 使用任意数量的面板、区域、传感器、触发器和自动化构建您自己的家庭报警系统.
- [bool-gate](https://flows.nodered.org/node/node-red-contrib-bool-gate) - 布尔逻辑门.
- [daemon](https://github.com/node-red/node-red-nodes/tree/master/utility/daemon) - 启动（调用）一个长时间运行的系统程序，并通过管道将 STDIN、STDOUT 和 STDERR 传送到该进程并从该进程传出. 
- [exif](https://github.com/node-red/node-red-nodes/tree/master/utility/exif) - 从传入的 jpeg 图像中提取 GPS 和其他 EXIF 信息.
- [german-holidays](https://github.com/rdmtc/node-red-contrib-german-holidays) - 如果今天/明天是假期，则获取德国假期或信息.
- [ical-events](https://github.com/naimo84/node-red-contrib-ical-events) - 通过 ical-URL、caldav-server 或 iCloud 获取事件 [kalender-events](https://github.com/naimo84/kalender-events).
- [interval-length](https://github.com/bartbutenaers/node-red-contrib-interval-length) - 测量连续消息之间的（时间）间隔长度.
- [moment](https://github.com/totallyinformation/node-red-contrib-moment) - 使用 Moment.js 库生成格式良好的日期/时间字符串. 
- [owntracks](https://github.com/hardillb/node-red-contrib-owntracks) - 将 Owntrack 消息转换为标准地理消息并处理加密位置.
- [persist](https://github.com/DeanCording/node-red-contrib-persist) - 通过 Node-RED 重新启动和部署持久化数据.
- [self-healing](https://github.com/jpdias/node-red-contrib-self-healing) - Making Node-RED more resilient by adding self-healing capabilities.
- [state-machine](https://github.com/DeanCording/node-red-contrib-state-machine) - 环绕 JavaScript 状态机以实现有限状态机.
- [string](https://github.com/steveorevo/node-red-contrib-string) - 提供原生和扩展的可链接 JavaScript 字符串解析和操作方法.
- [twc-weather](https://github.com/johnwalicki/node-red-contrib-twc-weather) - Weather Company 和 Weather Underground 个人气象站 API.
- [users](https://github.com/SenseTecnic/node-red-contrib-users) - 为基于 HTTP 的流快速构建一个非常简单的用户访问控制.
- [watson](https://github.com/watson-developer-cloud/node-red-node-watson) - 与 IBM Cloud 中的 IBM Watson 服务交互.

### UI

- [browser-utils](https://github.com/ibm-early-programs/node-red-contrib-browser-utils) - 添加浏览器功能，例如文件上传、摄像头和麦克风.
- [node-red-dashboard](https://github.com/node-red/node-red-dashboard) - 创建实时数据仪表板.
    - [https://flows.nodered.org/collection](https://flows.nodered.org/collection/590bc13ff3a5f005c7d2189bbb563976) - 仪表板额外节点.
    - [ui-svg](https://flows.nodered.org/node/node-red-contrib-ui-svg) - 在仪表板中显示交互式 SVG（矢量图形）.
    - [ui-contextmenu](https://flows.nodered.org/node/node-red-contrib-ui-contextmenu) - 在仪表板中显示弹出上下文菜单.
- [flow-manager](https://flows.nodered.org/node/node-red-contrib-flow-manager) - 将流 json 分离到多个文件.
- [iglass](https://www.npmjs.com/package/iglass-nodes) - 互动 [iGlass Automation](https://iglass.international) 块.
- [uibuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) - 为方便起见，使用任何（或不使用）前端库创建动态 Web 界面.
- [web-worldmap](https://github.com/dceejay/RedMap) - 提供用于绘制“事物”的世界地图网页.

## Community

- [HomeAssistant Forum](https://community.home-assistant.io/c/third-party/node-red/31)
- [Node-RED Forum](https://discourse.nodered.org/)
- [Node-RED Blog](https://nodered.org/blog/)
- [Node-RED User Group Japan](https://nodered.jp/)
- [Reddit](https://www.reddit.com/r/nodered/)
- [Redmatic Forum](https://homematic-forum.de/forum/viewforum.php?f=77)
- [Slack](https://nodered.org/about/community/slack)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/node-red)
- [Steves Node-RED Guide](https://stevesnoderedguide.com/)
- [Twitter](https://twitter.com/NodeRED)
- [YouTube](https://www.youtube.com/channel/UCQaB8NXBEPod7Ab8PPCLLAA)

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/naimo84/awesome-nodered/blob/master/contributing.md) 第一的.
