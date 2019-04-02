<div class="github-widget" data-repo="hobbyquaker/awesome-mqtt"></div>
## Awesome MQTT

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; MQTT相关内容的精选列表.

 MQTT是一种轻量级客户端 - 服务器发布/订阅消息传递协议，针对高延迟或不可靠的网络进行了优化.  该协议是物联网应用，遥测，传感器网络，智能计量，家庭自动化，消息传递和通知服务的理想选择.




### Community Resources

* [mqtt.org](http://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](https://github.com/hobbyquaker/awesome-mqtt/blob/master/irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/17/public-mqtt-brokers/).

#### Blogs

* [Ben Hardill](https://www.hardill.me.uk/wordpress/tag/mqtt/)
* [Dominik Obermaier](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](https://jpmens.net/)
* [Nick O'Leary](https://knolleary.net/)

#### Talks

* [An Introduction to MQTT: Why HTTP isn't the King of the Internet of Things](https://www.youtube.com/watch?v=LKz1jYngpcU) -  Shinji Kim，Robert Bird  -  Akamai，2017年三星开发者大会.
* [Einführung in MQTT](https://www.youtube.com/watch?v=INYG4-xsa9c) -  Dominik Obermaier和Jens Deters， [Building IoT](https://www.buildingiot.de/) 2016年会议（德国）.

### Broker

* [ActiveMQ](http://activemq.apache.org/) - 快速Java多协议消息传递和Integration Patterns服务器.
* [Aedes](https://github.com/mcollina/aedes) - 可以在任何流服务器上以节点方式运行的准系统MQTT代理.
* [Emitter](https://github.com/emitter-io/emitter) - 基于MQTT协议并具有消息存储功能的分布式，可扩展且容错的发布 - 订阅消息传递平台.
* [eMQTT](http://emqtt.io/) - 使用Erlang / OTP编写的可大规模扩展的MQTT Broker.
* [esp_uMQTT_broker](https://github.com/martin-ger/esp_mqtt) -  ESP8266上的基本MQTT代理.
* [flespi](https://flespi.com/mqtt-broker) - 具有私有名称空间，MQTT 5.0支持和华丽限制的免费云MQTT代理.
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - 使用asyncio的Python MQTT代理.
* [HiveMQ](https://www.hivemq.com/) - 基于Java的商业MQTT Broker.
* [hrotti](https://github.com/alsm/hrotti) - 用Go编写的MQTT代理.
* [Moquette](https://github.com/moquette-io/moquette) -  Java MQTT轻量级代理.
* [Mosca](http://www.mosca.io/) -  Mosca是一个node.js MQTT代理，可以在另一个Node.js应用程序中使用Standalone或Embedded.
* [Mosquitto](http://mosquitto.org/) - “开源MQTT经纪人”.
* [MyQttHub](https://myqtthub.com) - 云MQTT经纪人.
* [Mystique](https://github.com/TheThingsIndustries/mystique)   - 用Go编写的可扩展MQTT代理，具有可观察性的HTTP功能.  实现MQTT v3.1.1.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) -  RabbitMQ提供MQTT适配器.
* [SurgeMQ](https://zhen.org/categories/surgemq/) -  Go中的高性能MQTT服务器和客户端库.
* [VerneMQ](https://vernemq.com/) - 在Erlang中开发的Apache2许可的分布式MQTT代理.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) -  Vert.x组件，用于处理与远程MQTT客户端的连接，通信和消息交换.


### Tools

* [imqtt](https://github.com/shafreeck/imqtt) - 基于IPython的交互式MQTT数据包操作shell.
* [IoT-Testware](https://projects.eclipse.org/projects/technology.iottestware) -  Eclipse IoT-Testware是针对物联网协议的一致性测试套件的集合，其中包含用于模糊测试和性能测试的附加工具.
* [moxy](https://github.com/jvermillard/moxy) -  Golang MQTT代理，提供有用的输出跟踪，以监控和排除MQTT通信故障.
* [MQTT Board](https://github.com/flespi-software/MQTT-Board) - 面向开源诊断的MQTT客户端工具.
* [mqtt-admin](https://github.com/hobbyquaker/mqtt-admin/) - 基于Web的MQTT前端. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqtt-benchmark](https://github.com/chirino/mqtt-benchmark) -  MQTT服务器的基准测试工具.
* [mqtt-client](https://github.com/sdeancos/mqtt-client) - 一个简单的MQTT客户端命令行（Python）（使用paho lib）
* [mqtt-forget](https://github.com/hobbyquaker/mqtt-forget) - 命令行工具，用于通过通配符删除保留的MQTT主题.
* [mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz) -  MQTT协议的简单模糊器.
* [mqtt-malaria](https://github.com/etactica/mqtt-malaria) -  MQTT环境的可扩展性和负载测试实用程序.
* [MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn) -  MQTT-PWN打算成为物联网经纪人渗透测试和安全评估业务的一站式服务.
* [mqtt-shell](https://github.com/pidster-dot-org/mqtt-shell) -  MQTT的简单交互式shell.
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/)   - 基于Java的MQTT前端.  支持脚本.
* [mqtt_tree](https://github.com/poggenpower/mqtt_tree)   - 显示可扩展树中的所有主题，如果您有许多客户发布，则有助于获得概述.  （python，tkinter）
* [mqtt-utils](https://github.com/dsell/mqtt-utils) -  MQTT实用程序的集合.
* [mqtt-wall](https://github.com/bastlirna/mqtt-wall) - 仅订阅基于Web的客户端 - 如MQTT的Twitter墙.
* [mqtt-wildcard](https://github.com/hobbyquaker/mqtt-wildcard) -  Node.js模块，用于将MQTT主题与通配符进行匹配.
* [MQTT.fx](http://mqttfx.jfx4ee.org/)   -  MQTT.fx是一个基于Eclipse Paho用Java编写的MQTT客户端.  支持脚本.
* [mqttcli](https://github.com/shirou/mqttcli) - 用于shell脚本的MQTT客户端.
* [MQTTInspector](https://github.com/ckrey/MQTTInspector) - 适用于iOS（iPhone和iPad）的通用MQTT测试应用程序.
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) -  Google Chrome应用程序，可连接到MQTT代理，并可订阅和发布到MQTT主题.
* [MQTT Explorer](https://mqtt-explorer.com/) - 在主题层次结构中可视化MQTT主题的工具，MQTT瑞士军刀.
* [Python MQTT Client Shell](https://github.com/bapowell/python-mqtt-client-shell) - 基于文本控制台的交互式shell，用于执行与MQTT客户端通信相关的各种任务.
* [Wireshark-MQTT](https://github.com/menudoproblema/Wireshark-MQTT) -  Wireshark的MQTT解剖器.

### Clients

* [CocoaMQTT](https://github.com/emqtt/CocoaMQTT) - 使用Swift编写的iOS和OS X的MQTT.
* [emqttc](https://github.com/emqtt/emqttc) - 异步Erlang MQTT客户端.
* [gmqtt](https://github.com/wialon/gmqtt) -  Python MQTT v5.0客户端（基于asyncio）
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - 使用asyncio的Python MQTT客户端.
* [Hulaaki](https://github.com/suvash/hulaaki) - 用于与MQTT代理通信的客户的Elixir库.
* [luamqtt](https://github.com/xHasKx/luamqtt/) -  Pure-lua MQTT v3.1.1和v5.0客户端
* [M2Mqtt](https://m2mqtt.wordpress.com/) - 适用于所有.Net平台（.Net Framework，.Net Compact Framework和.Net Micro Framework）和WinRT平台（Windows 8.1，Windows Phone 8.1和Windows 10）的MQTT客户端.
* [Machine Head](https://github.com/clojurewerkz/machine_head) -  Clojure MQTT客户端.
* [MIMIC MQTT Simulator](https://www.gambitcomm.com/site/mqttsimulator.php) - 为每个服务器模拟多达100,000个MQTT客户端，用于开发/测试/部署IoT应用程序
* [Moscapsule](https://github.com/flightonary/Moscapsule) - 用Swift编写的MQTT Client for iOS.
* [Mosquitto-PHP](https://github.com/mgdm/Mosquitto-PHP) - 用于PHP的Mosquitto MQTT客户端库的包装器.
* [mqtt_cpp](https://github.com/redboltz/mqtt_cpp) - 基于Boost.Asio的C ++ 14 MQTT客户端.
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) -  Lua语言的MQTT客户端库.
* [MQTT-C](https://github.com/LiamBindle/MQTT-C) - 适用于嵌入式系统和PC的便携式MQTT C客户端.
* [MQTT-Client-Framework](https://github.com/novastone-media/MQTT-Client-Framework) -  iOS，OSX，tvOS原生ObjectiveC MQTT客户端框架.
* [mqtt-client](https://github.com/centamiv/mqtt-client) - 实现MQTT客户端的Polymer Web组件（使用Paho mqttws31.js）.
* [mqtt-elements](https://github.com/mqttjs/mqtt-elements) - 用于MQTT的聚合物元素.
* [mqtt-rs](https://github.com/zonyitoo/mqtt-rs) -  Rust的MQTT协议库.
* [mqtt-stats](https://github.com/gambitcomminc/mqtt-stats) - 用于监控MQTT主题统计信息的订户客户端
* [mqtt-wrapper](https://www.webcomponents.org/element/hobbyquaker/mqtt-wrapper/elements/mqtt-wrapper) - 包含其他元素并将它们链接到MQTT主题的Polymer Element.
* [mqtt.dart](https://github.com/jnguillerme/mqtt.dart) -  Dart mqtt客户端.
* [MQTT.js](https://github.com/mqttjs) -  Node.js的MQTT客户端.
* [mqtt](https://github.com/jeffallen/mqtt) -  Go中的MQTT客户端，服务器和负载测试器.
* [mqttex](https://github.com/alfert/mqttex) -  Elixir中的MQTT实现.
* [MQTTKit](https://github.com/mobile-web-messaging/MQTTKit) - 适用于iOS的MQTT Objective-C客户端.
* [Paho](http://www.eclipse.org/paho/) - Open source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient](https://github.com/knolleary/pubsubclient) -  Arduino Ethernet Shield的客户端库，为MQTT提供支持.
* [ruby-mqtt](https://github.com/njh/ruby-mqtt) - 实现MQTT协议的纯Ruby gem.
* [rumqtt](https://github.com/AtherEnergy/rumqtt) - 快速，无锁的纯锈MQTT客户端.
* [tcl-mqtt](https://github.com/Tingenek/tcl-mqtt)   - 用于连接MQTT代理的小型库.  非常，非常基本.
* [TMQTTClient](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/) - 用于Delphi的MQTT客户端库.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) -  Vert.x组件，提供连接/断开代理，发布消息和订阅主题的方法.
* [wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/)   - 用C语言编写的用于嵌入式使用的MQTT的客户端实现.  它通过wolfSSL库支持SSL / TLS.

### Scripting

* [logic4mqtt](https://github.com/owagner/logic4mqtt)   - 与MQTT一起使用的基于Java的逻辑和脚本引擎.  使用Java的通用脚本接口，因此脚本可以用多种语言编写，如Javascript，Groovy等.
* [mqtt-scripts](https://github.com/hobbyquaker/mqtt-scripts/) - 基于Node.js的脚本运行器.
* [Node-RED](https://nodered.org/) - 用于连接物联网的可视化工具.


### Interfaces

#### Makers

* [arduinoTemps2mqtt](https://github.com/matbor/arduinoTemps2mqtt) -  Arduino sketch，抓住One-wire Temperature并发布到MQTT经纪人.
* [Basecamp](https://github.com/merlinschumacher/Basecamp)   - 一个Arduino库，可以轻松在物联网项目中使用ESP32.  看到 [c't Magazin 2'2018 (German)](https://www.heise.de/select/ct/2018/02/1515452111258448).
* [esp_mqtt](https://github.com/tuanpmt/esp_mqtt) -  ESP8266的MQTT客户端库.
* [mqtt-ir-transceiver](https://github.com/enc-X/mqtt-ir-transceiver)   - 基于ESP8266的MQTT和IR之间的双向网关.  与PlatformIO一起使用.
* [mqtt-with-micropython](https://docs.pycom.io/chapter/tutorials/all/mqtt.html) - 使用micropython和wipy / others连接到MQTT（ESP32内部）
* [MySensors](https://www.mysensors.org/) - 基于Arduino NRF24L01的传感器网络，支持MQTT网关
* [nodemcu-gpiomqtt](https://github.com/hobbyquaker/nodemcu-gpiomqtt) - 用于将ESP8266 GPIO连接到MQTT的Lua脚本.
* [pubsubclient](https://github.com/knolleary/pubsubclient) -  Arduino Ethernet Shield的客户端库，为MQTT提供支持.
* [RFM69-MQTT-client](https://github.com/computourist/RFM69-MQTT-client) - 基于Arduino RFM69的传感器和MQTT网关.
* [rpi2mqtt](https://github.com/hobbyquaker/rpi2mqtt) - 将RaspberryPis GPIO和1-Wire温度传感器连接到MQTT.
* [xbee2mqtt](https://github.com/xoseperez/xbee2mqtt) -  XBee到MQTT网关.


#### Industry

* [CODESYS-MQTT](https://github.com/stefandreyer/CODESYS-MQTT) -  CODESYS PLC的MQTT客户端
* [spicierModbus2mqtt](https://github.com/mbs38/spicierModbus2mqtt) - 通过MQTT发布寄存器值的Modbus主站.
* [mqtt2opcua](https://github.com/nzfarmer1/mqtt2opcua) -  Bi定向MQTT到OPCUA桥.
* [OPC Router](https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/) - 具有各种插件的MQTT网关（发布者/订阅者）（OPC UA Bridge，SQL Bridge，REST Bridge，SAP Bridge）

#### Telephony, PBX

* [agi-mqtt](https://github.com/zeha/agi-mqtt) -  Asterisk和MQTT之间的接口.
* [fritz2mqtt](https://github.com/akentner/fritz2mqtt) - 将FRITZ！Box连接到MQTT.
* [sip2mqtt](https://github.com/MartyTremblay/sip2mqtt) -  SIP监控脚本，使用CallerID将传入呼叫发布到MQTT.


#### Operating System

* [mqtt-os-status](https://github.com/oskarhagberg/mqtt-os-status) - 与固定时间间隔发布到MQTT代理的操作系统相关数据.
* [mqttlauncher](https://github.com/jpmens/mqtt-launcher) - 执行由已发布的MQTT消息触发的shell命令.
* [mqttpc](https://github.com/hobbyquaker/mqttpc)   - 通过MQTT控制流程.  能够通过MQTT发送信号并将stdout / stderr或管道MQTT有效负载发布到stdin.
* [psmqtt](https://github.com/eschava/psmqtt) - 通过MQTT公用事业报告系统健康和状态.
* [WinThing](https://github.com/msiedlarek/winthing) - 通过MQTT远程控制Windows.


#### Monitoring

* [check-mqtt](https://github.com/jpmens/check-mqtt) - 用于检查与MQTT代理的连接的Nagios / Icinga插件.
* [nag2mqtt](https://github.com/DE-IBH/nag2mqtt) -  Nagios事件代理到MQTT网关.
* [notify-by-mqtt](https://github.com/jpmens/notify-by-mqtt) -  Nagios / Icinga通知模块，它将数据包装到JSON中并将其发送给MQTT代理.


#### Location tracking

* [OwnTracks](https://owntracks.org/) -  MQTT的位置跟踪和地理围栏.


#### Logging

* [graylog-plugin-mqtt](https://github.com/graylog-labs/graylog-plugin-mqtt) -  Graylog的MQTT输入插件.
* [influx4mqtt](https://github.com/hobbyquaker/influx4mqtt) - 订阅MQTT主题并插入InfluxDB.
* [mqtt2elasticsearch](https://github.com/hobbyquaker/mqtt2elasticsearch) - 将MQTT消息发送到Elasticsearch.
* [mqtt2graphite](https://github.com/jpmens/mqtt2graphite) - Subscribe to MQTT topics and push to Graphite's Carbon server.
* [mqttcollect](https://github.com/jpmens/mqttcollect) -  MQTT的收集“Exec”插件.
* [mqtthandler](https://github.com/changyuheng/MQTTHandler) -  MQTT的Python日志处理程序模块.


#### Smart Home Hardware Interfaces

* [aqara-mqtt](https://github.com/monster1025/aqara-mqtt) -  Aqara（小米）通往MQTT桥梁的门户.
* [aqara2mqtt](https://github.com/hobbyquaker/aqara2mqtt) - 附上 [Aqara](https://www.aqara.com/en/products.html) MQTT的智能中心.
* [cul2mqtt](https://github.com/hobbyquaker/cul2mqtt) - 之间的接口 [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) （868MHz RF设备，如ELV FS20，HMS，EM ......）和MQTT.
* [domiqtt](https://github.com/etobi/domiqtt) - 连接到Domiq Base（LCN）并从MQTT转换到MQTT.
* [eno2mqtt](https://github.com/owagner/eno2mqtt) -  Enocean USB300（TCM310）适配器和MQTT之间的接口.
* [Evohome2mqtt](https://github.com/svrooij/evohome2mqtt) - 霍尼韦尔Evohome系统的MQTT接口.
* [helios2mqtt](https://github.com/mreschka/helios2mqtt) - 用于将helios easy控制系统（如我的KWL EC 220D）同步到MQTT的守护程序.
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js)   -  EQ-3 Homematic系列智能家居设备与MQTT之间的接口.  支持Homematic IP.
* [homeeToMqtt](https://github.com/odig/homeeToMqtt) -  homee和MQTT之间的双向接口.
* [HS100toMQTT](https://github.com/dersimn/HS100toMQTT) -  TPLink HS100 / HS110和MQTT之间的网关.
* [ipcam2mqtt](https://github.com/svrooij/ipcam2mqtt) - 一个小型ftp服务器，用于从ipcameras接收运动图像并将其转换为mqtt警报.
* [knx-mqtt-bridge](https://github.com/pakerfeldt/knx-mqtt-bridge) - 使用knx.js库挖掘KNX和MQTT.
* [knx2mqtt](https://github.com/owagner/knx2mqtt) -  KNX家庭自动化标准和MQTT之间的接口.
* [mcsMQTT](https://shop.homeseer.com/products/mcsmqtt-software-plug-in-for-hs3) -  HS3插件（HomeSeer）.
* [mqtt-dss-bridge](https://github.com/cgHome/mqtt-dss-bridge) -  MQTT digitalSTROM-Server Bridge.
* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) - 大致相反 [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt)：使用MQTT控制启用HomeKit的设备，不使用Siri或iPhone.
* [node-lox-mqtt-gateway](https://github.com/alladdin/node-lox-mqtt-gateway) - 用于与MQTT代理通信的Loxone™迷你服务器的网关.
* [smartthings-mqtt-bridge](https://github.com/stjohnjohnson/smartthings-mqtt-bridge) - 桥之间 [SmartThings](https://www.smartthings.com/) 和MQTT.
* [Sonoff-Tasmota](https://github.com/arendst/Sonoff-Tasmota) - 具有本机MQTT支持的Sonoff设备的固件.
* [xiaomi2mqtt](https://github.com/svrooij/node-xiaomi2mqtt) - 小米智能家居网关Aquara和MQTT服务器之间的桥梁.
* [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) - 允许您在没有供应商（Xiaomi / TRADFRI / Hue）网桥/网关的情况下使用Zigbee设备.


#### Smart Home Integration Software

* [control-freak](https://github.com/tx4x/control-freak)   - 物联网和朋友的IDE.  内置MQTT支持.
* [Domoticz](http://www.domoticz.com/) -  Domoticz beta支持MQTT.
* [FHEM](http://fhem.de/fhem.html) 有个 [MQTT module](http://fhem.de/commandref.html#MQTT) 自V5.6起.
* [Home Assistant](https://www.home-assistant.io/) 有一个MQTT组件.
* [Home.Pi](https://github.com/denschu/home.pi) 基于MQTT.
* [Homegear](https://homegear.eu/index.php/Main_Page) 已建立MQTT支持.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - 之间的接口 [HAP-NodeJS](https://github.com/KhaosT/HAP-NodeJS)  和MQTT.  使用Siri或HomeKit Apps控制MQTT连接设备.
* [ioBroker](https://github.com/ioBroker) 有个 [MQTT adapter](https://github.com/ioBroker/ioBroker.mqtt).
* [Lelylan](http://www.lelylan.com/)   - 物联网云平台.  微服务架构.  对于开发人员.
* [Node-RED](https://nodered.org/) - 用于连接物联网的可视化工具，具有本机MQTT支持.
* [openHAB](https://github.com/openhab) 有个 [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) 有一个MQTT插件.


#### Lighting

* [Arilux_AL-LC0X](https://github.com/mertenats/Arilux_AL-LC0X) - 这是使用MQTT的Arilux LED控制器的替代固件.
* [chromoflex2mqtt](https://github.com/owagner/chromoflex2mqtt) - 通过MQTT控制Chromoflex USP3 RGB LED模块.
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) - 使用MQTT作为控制通道的H801 LED调光器的替代固件.
* [hue2mqtt.js](https://github.com/hobbyquaker/hue2mqtt.js) -  Philips Hue桥与MQTT之间的接口.
* [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-controller) - 支持MQTT的DMX控制器.
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - 无头对手 [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - 使用从MQTT DMX控制器导出的场景和序列，并通过MQTT控制它们.
* [sunricher-wifi-mqtt](https://github.com/magcode/sunricher-wifi-mqtt) - 使用MQTT控制Sunricher LED设备.
* [TRADFRI2MQTT](https://github.com/hardillb/TRADFRI2MQTT) - 适用于宜家TRÅDFRILightGateway的MQTT桥接器.


#### Home Entertainment

* [airtunes2mqtt](https://github.com/hobbyquaker/airtunes2mqtt) - 使用Airplay / Airtunes设备进行MQTT控制的多房间音频.
* [bravia2mqtt](https://github.com/forty2/bravia2mqtt) - 使用MQTT控制Sony Bravia电视.
* [broadlink-mqtt](https://github.com/eschava/broadlink-mqtt) -  MQTT客户端，用于控制BroadLink RM设备.
* [chromecast-mqtt-connector](https://github.com/nohum/chromecast-mqtt-connector) - 使用MQTT控制您的Google Chromecast设备.
* [harmony-api](https://github.com/maddox/harmony-api) - 一个简单的服务器，允许您通过HTTP或MQTT查询/控制多个本地Harmony Home Hub.
* [htd2mqtt](https://github.com/TheOriginalAndrobot/htd2mqtt) -  HTD Lync音频系统和MQTT之间的桥接.
* [kodi2mqtt](https://github.com/owagner/kodi2mqtt) -  Kodi媒体中心实例与MQTT之间的接口.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) -  LG WebOS智能电视和MQTT之间的接口.
* [lirc2mqtt](https://github.com/hobbyquaker/lirc2mqtt) - 发送和接收红外线 [LIRC](https://github.com/hobbyquaker/awesome-mqtt/blob/master/www.lirc.org).
* [mopidy-mqtt](https://github.com/magcode/mopidy-mqtt) -  Mopidy的MQTT功能.
* [MQTT-DashCast-Docker](https://github.com/mukowman/MQTT-DashCast-Docker) -  MQTT Docker在Chromecast上启动DashCast会话.
* [mqtt2atlonamatrix](https://github.com/forty2/mqtt2atlonamatrix) - 使用MQTT控制Atlona HDMI矩阵开关.
* [mqtt2tivoremote](https://github.com/forty2/mqtt2tivoremote) - 通过MQTT智能家居风格界面提供TiVo DVR遥控器.
* [onkyo2mqtt](https://github.com/owagner/onkyo2mqtt)   -  Onkyo AVR的EISCP网络远程协议与MQTT之间的接口.  使用onkyo-eiscp库.
* [sonos2mqtt](https://github.com/svrooij/sonos2mqtt) -  Sonos和MQTT之间的桥梁.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - 通过MQTT控制VLC.
* [xbmc2mqtt](https://github.com/gordonjcp/xbmc-mqtt) - 一个简单的插件，供XBMC监听MQTT代理上的特定主题，并显示弹出消息.
* [yamaha-avr2mqtt](https://github.com/akentner/yamaha-avr2mqtt) - 用于将Yamaha AVR连接到MQTT的简单适配器.


#### Smart Metering

* [bcontrol2mqtt](https://github.com/hobbyquaker/bcontrol2mqtt) - 发布测量结果 [TQ Energy Manager](https://www.tq-group.com/produkte/produktdetail/prod/energy-manager/extb/Main) 这个MQTT.


#### Messaging

* [mqtt-irc-bot](https://github.com/dobermai/mqtt-irc-bot) -  MQTT到IRC / IRC到MQTT桥或机器人.
* [mqttwarn](https://github.com/jpmens/mqttwarn) - 订阅MQTT主题（使用通配符）和notifiy可插拔服务.
* [twitter-to-mqtt](https://github.com/knolleary/twitter-to-mqtt) - 一个python守护程序，它使用Twitter Streaming API访问推文并将它们重新发布到MQTT主题.


#### Misc

* [AlexaMqttBridge](https://github.com/mhdawson/AlexaMqttBridge) - 亚马逊Alexa和Mqtt之间的桥梁.
* [bt-mqtt-gateway](https://github.com/zewelor/bt-mqtt-gateway) - 易于扩展的蓝牙到MQTT网关，目前支持：EQ3智能恒温器，小米Mi Scale，Linak Desk，MySensors和小米Mi Flora工厂传感器.
* [buderus2mqtt](https://github.com/krambox/buderus2mqtt) - 布德鲁斯KM200互联网网关和Mqtt之间的桥梁.
* [dashbutton2mqtt](https://github.com/hobbyquaker/dashbutton2mqtt) - 将Amazon Dash Button按下发布到MQTT.
* [flowerpower2mqtt](https://github.com/hobbyquaker/flowerpower2mqtt) - 将鹦鹉花电厂传感器的测量结果发布到MQTT.
* [gBridge](https://github.com/kservices/gBridge)   -  gBridge允许您使用Google智能助理控制（几乎）任何智能家居设备，任何智能家居软件.  因此，它将通过语音命令从Google收到的操作转换为MQTT消息.
* [haiku2mqtt](https://github.com/forty2/haiku2mqtt) -  Haiku智能风扇和MQTT之间的桥梁.
* [homely](https://github.com/baol/homely) - 用于连接Domoticz和其他东西的Go守护进程的集合.
* [kobold2mqtt](https://github.com/krambox/kobold2mqtt) -  Vorwerk Kobold Vr200互联网网关和Mqtt之间的桥梁.
* [leaf-python-mqtt](https://github.com/glynhudson/leaf-python-mqtt) - 从Nissan Leaf API中提取数据并发布到mqtt.
* [miflora-mqtt-daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) -  Linux服务，将Xiaomi Mi Flora工厂传感器数据发送给MQTT代理.
* [mqtt2ble](https://github.com/hardillb/mqtt2ble) - 将MQTT主题与BLE Gatt特性联系起来的方法.
* [mqttclpro](https://github.com/dc297/mqttclpro) - 具有任务集成Android应用程序的MQTT客户端.
* [mqttDB](https://github.com/hobbyquaker/mqttDB) - A JSON store with MQTT interface.
* [node-mqtt-for-anki-overdrive](https://github.com/IBM-Cloud/node-mqtt-for-anki-overdrive) - 用于Anki Overdrive的Node.js控制器和MQTT API.
* [parrot-sample](https://github.com/IBM-Cloud/parrot-sample) - 使用MQTT控制Parrot AR Drone的示例代码.
* [snowboy2mqtt](https://github.com/hobbyquaker/snowboy2mqtt) - 在Snowboy Hotword Detection上发布MQTT消息.
* [speedtest2mqtt](https://github.com/hobbyquaker/speedtest2mqtt) - 运行speedtest-cli并通过MQTT发布结果.
* [unifi2mqtt](https://github.com/hobbyquaker/unifi2mqtt) - 将连接的客户从Ubiquiti Unifi发布到MQTT.
* [Valetudo](https://github.com/Hypfer/Valetudo) - 具有MQTT和Web界面的小米（Roborock）真空机器人固件.
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) -  Addon用于流行的DIY烧烤温度计.
*手袋（Android自动化） [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin).

### Visualization, Dashboards

* [Crouton](http://crouton.mybluemix.net/crouton/gettingStarted) - 仅使用MQTT和JSON进入IOT网络的仪表板.
* [d3-MQTT-Topic-Tree](https://github.com/hardillb/d3-MQTT-Topic-Tree) - 使用d3可折叠树和基于websockets的MQTT的MQTT主题树查看器.
* [HelloIoT](https://github.com/adrianromero/helloiot) -  HelloIoT是MQTT客户端和仪表板应用程序.
* [HOMR-REACT](https://github.com/klauserber/homr-react) - 可配置的MQTT可视化.
* [IoT OnOff](https://www.iot-onoff.com/) - 可配置的iOS / Android应用程序.
* [Linear MQTT Dashboard](https://github.com/ravendmaster/linear-mqtt-dashboard) - 易于定制的控制面板 -  MQTT客户端.
* [MMM-mqtt](https://github.com/javiergayala/MMM-mqtt)   - 这是MagicMirror²的扩展.  它提供了订阅MQTT主题并显示它们的能力.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) -  Android应用程序：通过该应用程序，您可以为支持MQTT的物联网智能家居设备和应用程序创建仪表板.
* [mqtt-panel](https://github.com/fabaff/mqtt-panel) -  MQTT的Web界面.
* [mqtt-svg-dash](https://github.com/jpmens/mqtt-svg-dash) - 订阅MQTT，从消息中提取JSON并使SVG页面上的指示灯闪烁.
* [mqtt2highcharts](https://github.com/matbor/mqtt2highcharts) - 使用Highcharts从订阅的mqtt主题绘制实时编号数据.
* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) -  Node-RED的仪表板UI.
* [thingsboard](https://thingsboard.io/) - 物联网项目的设备管理，数据收集，处理和可视化.



### Architecture, Convention

* [mqtt-smarthome](https://github.com/mqtt-smarthome/mqtt-smarthome) - 使用MQTT作为中央消息总线的智能家居自动化 - 建筑方案.
* [The Homie Convention](https://github.com/homieiot/convention) - 物联网的轻量级MQTT约定.

### Security, Encryption

* [Teserakt E4](https://teserakt.io/) -  MQTT和其他M2M协议的端到端加密 - 商业解决方案.


## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/hobbyquaker/awesome-mqtt/blob/master/contributing.md) 第一.


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
