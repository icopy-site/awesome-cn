<div class="github-widget" data-repo="hobbyquaker/awesome-mqtt"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome MQTT

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;与MQTT相关的内容的精选列表.

 MQTT是一种轻量级的客户端-服务器发布/订阅消息传递协议，已针对高延迟或不可靠的网络进行了优化.  该协议是物联网应用，遥测，传感器网络，智能计量，家庭自动化，消息传递和通知服务的理想选择.




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

* [An Introduction to MQTT: Why HTTP isn't the King of the Internet of Things](https://www.youtube.com/watch?v=LKz1jYngpcU) -Shinji Kim，Robert Bird-Akamai，2017年三星开发者大会.
* [Einführung in MQTT](https://www.youtube.com/watch?v=INYG4-xsa9c) -Dominik Obermaier和Jens Deters， [Building IoT](https://www.buildingiot.de/) 2016年大会（德语）.

### Broker

* [ActiveMQ](http://activemq.apache.org/) -快速的Java多协议消息传递和集成模式服务器.
* [Aedes](https://github.com/mcollina/aedes) -可以在任何流服务器上以节点方式运行的准系统MQTT代理.
* [Emitter](https://github.com/emitter-io/emitter) -基于MQTT协议并具有消息存储功能的分布式，可伸缩且容错的发布-订阅消息传递平台.
* [EMQ X](https://github.com/emqx/emqx) -适用于5G时代的IoT的可扩展且可靠的实时MQTT消息引擎.
* [esp_uMQTT_broker](https://github.com/martin-ger/esp_mqtt) - A basic MQTT Broker on the ESP8266.
* [hbmqtt](https://github.com/beerfactory/hbmqtt) -使用异步的Python MQTT代理.
* [HiveMQ](https://www.hivemq.com/)  -支持MQTT 3.1、3.1.1和5.0的Java MQTT Broker.  提供商业和开源版本.
* [hrotti](https://github.com/alsm/hrotti) -用Go编写的MQTT经纪人.
* [Moquette](https://github.com/moquette-io/moquette) -Java MQTT轻量级代理.
* [Mosca](http://www.mosca.io/) -Mosca是node.js MQTT代理，可以独立使用，也可以嵌入到另一个Node.js应用程序中.
* [Mosquitto](http://mosquitto.org/) -*“ * The” **开源MQTT代理. 
     * [Free test server](https://mqtt.eclipse.org/) 由Eclipse Foundation托管.
     * [Authorization Plugin in Go](https://github.com/iegomez/mosquitto-go-auth) 支持多种类型的登录.
     * [Let's Encrypt Mosquitto Docker Container](https://hub.docker.com/r/pythonlinks/letsencrypt-mosquitto) 使其易于加密. 
* [MyQttHub](https://myqtthub.com) -Cloud MQTT经纪人.
* [Mystique](https://github.com/TheThingsIndustries/mystique)  -用Go编写的可扩展MQTT代理，具有HTTP功能以提高可观察性.  实现MQTT v3.1.1.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) -RabbitMQ提供了MQTT适配器.
* [SurgeMQ](https://zhen.org/categories/surgemq/) -Go中的高性能MQTT服务器和客户端库.
* [VerneMQ](https://vernemq.com/) -由Erlang开发的Apache2许可的分布式MQTT代理.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) -Vert.x组件，用于处理与远程MQTT客户端的连接，通信和消息交换.

### Cloud

* [Adafruit IO](https://io.adafruit.com)  -Adafruit IO是将项目连接到Internet的最简单方法.  您可以使用您选择的编程语言（我们有很多库）轻松地将您的项目连接到Adafruit IO，并且可以通过Internet进行控制或监视.  Adafruit IO存储的数据由您管理和控制.
- [Alibaba Cloud IoT Platform](https://www.alibabacloud.com/product/iot) -在设备和IoT平台之间提供安全可靠的通信，使您可以在单个IoT平台上管理大量设备.
- [AWS IoT Core](https://aws.amazon.com/iot-core/?nc1=h_ls)  -AWS IoT Core是一项托管的云服务，可让连接的设备轻松，安全地与云应用程序和其他设备交互.  AWS IoT Core可支持数十亿个设备和数以万亿计的消息，并可将这些消息可靠且安全地处理并路由到AWS终端节点和其他设备.  借助AWS IoT Core，您的应用程序可以随时跟踪所有设备并与之通信，即使它们没有连接也是如此.
- [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/)  -在IoT应用程序及其管理的设备之间实现高度安全和可靠的通信.  Azure IoT中心提供了一个云托管的解决方案后端，可以连接几乎任何设备.  通过每设备身份验证，内置设备管理和扩展配置，将您的解决方案从云扩展到边缘.
- [CloudMQTT](https://www.cloudmqtt.com/)  -托管物联网的消息代理.  完美配置和优化的物联网消息队列，几秒钟即可完成.
- [EMQ X MQTT Cloud](https://cloud.emqx.io/) -由EMQ团队提供最佳实践的安全，可靠的MQTT云服务.
- [flespi](https://flespi.com/mqtt-broker) -具有私有名称空间，MQTT 3.1.1和MQTT 5.0支持以及华丽的限制的免费和安全的云MQTT代理.
- [Google Cloud IoT](https://cloud.google.com/solutions/iot/)  -Google Cloud IoT是一整套用于在边缘和云中连接，处理，存储和分析数据的工具.  该平台由可扩展的，完全托管的云服务组成；  用于边缘/本地计算的集成软件堆栈，具有机器学习功能，可满足您所有IoT需求.
- [IBM WATSON](https://www.ibm.com/watson) -使用Watson，您可以将AI工具和应用程序带到数据中的任何位置，无论它位于IBM Cloud，AWS，Azure，Google还是您自己的私有云平台上.

### Platforms

* [mainflux](https://www.mainflux.com/)  -设备管理，数据聚合，数据管理，数据分析，连接性以及消息路由和事件管理.  由Linux Software Foundation支持.
核心分析
* [thingsboard](https://thingsboard.io/) -物联网项目的设备管理，数据收集，处理，事件管理和可视化.


### Tools
* [hivemq-mqtt-web-client](https://github.com/hivemq/hivemq-mqtt-web-client) -基于浏览器的MQTT客户端，该客户端在Websocket上利用MQTT. [Direct Link](http://www.hivemq.com/demos/websocket-client/)
* [imqtt](https://github.com/shafreeck/imqtt) -基于IPython的交互式MQTT数据包操作外壳.
* [IoT-Testware](https://projects.eclipse.org/projects/technology.iottestware) -Eclipse IoT-Testware是用于IoT协议的一致性测试套件的集合，其中丰富了用于模糊测试和性能测试的其他工具.
* [moxy](https://github.com/jvermillard/moxy) -Golang MQTT代理，提供有用的输出跟踪，以监视MQTT通信并对其进行故障排除.
* [MQTT Board](https://github.com/flespi-software/MQTT-Board) -面向诊断的开源MQTT客户端工具.
* [mqtt-admin](https://github.com/hobbyquaker/mqtt-admin/) -基于Web的MQTT前端. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqtt-benchmark](https://github.com/chirino/mqtt-benchmark) -MQTT服务器的基准测试工具.
* [MQTT CLI](https://github.com/hivemq/mqtt-cli) -命令行界面，用于连接支持MQTT 5.0和3.1.1的各种MQTT客户端.
* [mqtt-client](https://github.com/sdeancos/mqtt-client) -简单的MQTT客户端命令行（Python）（使用paho lib）
* [mqtt-forget](https://github.com/hobbyquaker/mqtt-forget) -命令行工具，用于通过通配符删除保留的MQTT主题.
* [mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz) -MQTT协议的简单模糊器.
* [mqtt-malaria](https://github.com/etactica/mqtt-malaria) -用于MQTT环境的可伸缩性和负载测试实用程序.
* [MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn) -MQTT-PWN打算成为IoT Broker渗透测试和安全评估操作的一站式服务.
* [mqtt-shell](https://github.com/pidster-dot-org/mqtt-shell) -MQTT的简单交互式外壳.
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/)  -基于Java的MQTT前端.  支持脚本.
* [mqtt_tree](https://github.com/poggenpower/mqtt_tree)  -在可展开的树中显示所有主题，如果您有许多发布的客户端，则有助于获得概述.  （python，tkinter）
* [mqtt-utils](https://github.com/dsell/mqtt-utils) -MQTT实用程序的集合.
* [mqtt-wall](https://github.com/bastlirna/mqtt-wall) -仅订阅基于Web的客户端–如MQTT的Twitter wall.
* [mqtt-wildcard](https://github.com/hobbyquaker/mqtt-wildcard) -Node.js模块，用于将MQTT主题与通配符进行匹配.
* [MQTT.fx](https://mqttfx.jensd.de/)  -MQTT.fx是基于Java Eclipse Paho编写的MQTT客户端.  支持脚本.
* [mqttcli](https://github.com/shirou/mqttcli) -用于外壳程序脚本的MQTT Client.
* [MQTTInspector](https://github.com/ckrey/MQTTInspector) -适用于iOS（iPhone和iPad）的通用MQTT测试应用.
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) -一个Google Chrome应用程序，它连接到MQTT代理，并且可以订阅和发布MQTT主题.
* [MQTT Explorer](https://mqtt-explorer.com/) -在主题层次结构中可视化您的MQTT主题的工具，MQTT瑞士军刀.
* [Python MQTT Client Shell](https://github.com/bapowell/python-mqtt-client-shell) -基于文本控制台的交互式外壳，用于执行与MQTT客户端通信相关的各种任务.
* [SimpleMQTT](https://simplemqtt.theoi.de/) -一个Slack应用程序，使用斜杠命令将消息从Slack发送到MQTT代理.
* [Wireshark-MQTT](https://github.com/menudoproblema/Wireshark-MQTT) -Wireshark的MQTT解剖器.
* [MQTTX](https://github.com/emqx/MQTTX) - MQTTX is a cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows.

### Clients

* [aiomqtt](https://github.com/mossblaser/aiomqtt) -基于paho-mqtt的异步Python MQTT客户端.
* [CocoaMQTT](https://github.com/emqx/CocoaMQTT) -使用Swift编写的适用于iOS和OS X的MQTT.
* [emqttc](https://github.com/emqx/emqtt) -异步Erlang MQTT客户端.
* [gmqtt](https://github.com/wialon/gmqtt) -Python MQTT v5.0客户端（基于异步）.
* [hbmqtt](https://github.com/beerfactory/hbmqtt) -使用异步的Python MQTT客户端.
* [hivemq-mqtt-client](https://github.com/hivemq/hivemq-mqtt-client) -针对MQTT 5.0和3.1.1，具有不同API风格的高性能Java MQTT客户端库.
* [Hulaaki](https://github.com/suvash/hulaaki) -用于与MQTT代理进行通信的客户端的Elixir库.
* [luamqtt](https://github.com/xHasKx/luamqtt/) -Pure-lua MQTT v3.1.1和v5.0客户端.
* [Machine Head](https://github.com/clojurewerkz/machine_head) -Clojure MQTT客户端.
* [MiniMQTT](https://github.com/adafruit/Adafruit_CircuitPython_MiniMQTT) -用于CircuitPython的MQTT客户端库
* [MIMIC MQTT Simulator](https://www.gambitcomm.com/site/mqttsimulator.php) -每台服务器最多模拟100,000个MQTT客户端，用于IoT应用程序的开发/测试/部署.
* [Moscapsule](https://github.com/flightonary/Moscapsule) -使用Swift编写的iOS版MQTT客户端.
* [Mosquitto-PHP](https://github.com/mgdm/Mosquitto-PHP) -用于PHP的Mosquitto MQTT客户端库的包装.
* [mqtt_cpp](https://github.com/redboltz/mqtt_cpp) -基于Boost.Asio的C ++ 14的MQTT客户端.
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) -用于Lua语言的MQTT客户端库.
* [MQTT-C](https://github.com/LiamBindle/MQTT-C) -适用于嵌入式系统和PC的便携式MQTT C客户端.
* [MQTT-Client-Framework](https://github.com/novastone-media/MQTT-Client-Framework) -iOS，OSX，tvOS本机ObjectiveC MQTT客户端框架.
* [mqtt-client](https://github.com/centamiv/mqtt-client) -一个实现MQTT客户端的Polymer Web组件（使用Paho mqttws31.js）.
* [mqtt-elements](https://github.com/mqttjs/mqtt-elements) -MQTT的聚合物元素.
* [mqtt-rs](https://github.com/zonyitoo/mqtt-rs) -Rust的MQTT协议库.
* [mqtt-stats](https://github.com/gambitcomminc/mqtt-stats) -订户客户端以监视MQTT主题统计信息
* [mqtt-wrapper](https://www.webcomponents.org/element/hobbyquaker/mqtt-wrapper/elements/mqtt-wrapper) -包装其他元素并将其链接到MQTT主题的聚合物元素.
* [mqtt.dart](https://github.com/jnguillerme/mqtt.dart) -Dart MQTT客户端.
* [MQTT.js](https://github.com/mqttjs) -Node.js的MQTT客户端.
* [mqtt](https://github.com/jeffallen/mqtt) -Go中的MQTT客户端，服务器和负载测试器.
* [mqttex](https://github.com/alfert/mqttex) -Elixir中的MQTT实现.
* [MQTTKit](https://github.com/mobile-web-messaging/MQTTKit) -适用于iOS的MQTT Objective-C客户端.
* [Paho](http://www.eclipse.org/paho/) - Open source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient](https://github.com/knolleary/pubsubclient) -Arduino以太网屏蔽的客户端库，它支持MQTT.
* [ruby-mqtt](https://github.com/njh/ruby-mqtt) -实现MQTT协议的纯Ruby宝石.
* [rumqtt](https://github.com/AtherEnergy/rumqtt) -快速，无锁的纯Rust MQTT客户端.
* [tcl-mqtt](https://github.com/Tingenek/tcl-mqtt)  -小型库，用于连接到MQTT代理.  非常非常基本.
* [TMQTTClient](https://github.com/jamiei/Delphi-TMQTT2) -用于Delphi的MQTT客户端库.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) -Vert.x组件，提供用于连接/断开与代理，发布消息和订阅主题的方法.
* [wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/)  -用C编写的嵌入式嵌入式MQTT的客户端实现.  它通过wolfSSL库支持SSL / TLS.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) -.NET中的MQTT客户端和代理实现.

### Scripting

* [logic4mqtt](https://github.com/owagner/logic4mqtt)  -与MQTT一起使用的基于Java的逻辑和脚本引擎.  使用Java的常规脚本接口，因此可以使用多种语言（例如Javascript，Groovy等）编写脚本.
* [mqtt-scripts](https://github.com/hobbyquaker/mqtt-scripts/) -基于Node.js的脚本运行器.
* [Node-RED](https://nodered.org/) -用于连接物联网的可视化工具.


### Interfaces


#### Makers

* [arduinoTemps2mqtt](https://github.com/matbor/arduinoTemps2mqtt) -Arduino草图，获取单线温度，然后发布到MQTT代理.
* [Basecamp](https://github.com/ct-Open-Source/Basecamp)  -一个Arduino库，可简化IoT项目中ESP32的使用.  看到 [c't Magazin 2'2018 (German)](https://www.heise.de/select/ct/2018/2/1515452111258448).
* [MySensors](https://www.mysensors.org/) -基于Arduino NRF24L01的传感器网络，支持MQTT网关
* [pubsubclient](https://github.com/knolleary/pubsubclient) -Arduino以太网屏蔽的客户端库，它支持MQTT.
* [RFM69-MQTT-client](https://github.com/computourist/RFM69-MQTT-client) -基于Arduino RFM69的传感器和MQTT网关.
* [rpi2mqtt](https://github.com/hobbyquaker/rpi2mqtt) -将RaspberryPis GPIO和1-Wire温度传感器连接到MQTT.
* [xbee2mqtt](https://github.com/xoseperez/xbee2mqtt) -XBee到MQTT网关.

##### ESP

* [ESP32-BLE2MQTT](https://github.com/shmuelzon/esp32-ble2mqtt) -BLE到MQTT桥，将BLE GATT特性作为MQTT主题公开，用于双向通信.
* [ESP8266MQTTMesh](https://github.com/PhracturedBlue/ESP8266MQTTMesh) -适用于ESP8266的网状WiFi集成库中的MQTT
* [esp_mqtt](https://github.com/tuanpmt/esp_mqtt) -用于ESP8266的MQTT客户端库.
* [mqtt-ir-transceiver](https://github.com/enc-X/mqtt-ir-transceiver)  -在MQTT和IR之间基于ESP8266的双向网关.  与PlatformIO一起使用.
* [mqtt-with-micropython](https://docs.pycom.io/chapter/tutorials/all/mqtt/) -使用micropython和wipy / others连接到MQTT（内置ESP32）
* [nodemcu-gpiomqtt](https://github.com/hobbyquaker/nodemcu-gpiomqtt) -将ESP8266 GPIO连接到MQTT的Lua脚本.


##### Firmwares for ESP based Devices 

有许多基于廉价ESP8266芯片的廉价智能家庭Wi-Fi设备_（请参阅： [1](https://templates.blakadder.com/index.html), [2](https://github.com/xoseperez/espurna#supported-hardware), [3](https://www.letscontrolit.com/wiki/index.php?title=ESP_Hardware) ）_.  其中大多数可以使用自定义固件刷新.
以下是完整的固件，可将它们转换为MQTT控制的智能家庭节点：

* [ESPEasy](https://www.letscontrolit.com/wiki/index.php?title=ESPEasy)  -通过基于Web的配置将ESP变成用于<abbr title="家庭自动化">HA</abbr>解决方案的多功能传感器设备.
* [ESPHome](https://esphome.io/) -通过简洁的YAML说明构建ESP8266 / ESP32固件，并上传到Flash设备并对其进行管理.
* [Espurna](https://github.com/xoseperez/espurna)  -具有ESP8266的设备的<abbr title="家庭自动化">HA</abbr>固件，具有丰富的Web UI和开箱即用的≈120个设备
* [Sonoff-Tasmota](https://github.com/arendst/Tasmota)  -具有基于Web的配置的ESP8266设备的固件.  支持≈500个设备（不仅是Sonoffs）.
* [WiFi-IoT](https://wifi-iot.com/p/wiki/)  -ESP8266 / ESP32固件构建器.  部分用俄语.  免费功能有限.


#### Industry

* [CODESYS-MQTT](https://github.com/stefandreyer/CODESYS-MQTT) -CODESYS PLC的MQTT客户端
* [spicierModbus2mqtt](https://github.com/mbs38/spicierModbus2mqtt) -Modbus主站，通过MQTT发布寄存器值.
* [mqtt2opcua](https://github.com/nzfarmer1/mqtt2opcua) -双向MQTT到OPCUA桥.
* [OPC Router](https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/) -具有各种插件（OPC UA桥，SQL桥，REST桥，SAP桥）的MQTT网关（发布者/订阅者）

#### Telephony, PBX

* [agi-mqtt](https://github.com/zeha/agi-mqtt) -星号和MQTT之间的接口.
* [fritz2mqtt](https://github.com/akentner/fritz2mqtt) -将FRITZ！Box连接到MQTT.
* [sip2mqtt](https://github.com/MartyTremblay/sip2mqtt) -SIP监视脚本，它将带有CallerID的来电发布到MQTT.


#### Operating System

* [mqtt-os-status](https://github.com/oskarhagberg/mqtt-os-status) -与操作系统相关的数据，以固定的时间间隔发布到MQTT代理.
* [mqttlauncher](https://github.com/jpmens/mqtt-launcher) -执行由已发布的MQTT消息触发的Shell命令.
* [mqttpc](https://github.com/hobbyquaker/mqttpc)  -通过MQTT控制过程.  能够通过MQTT发送信号并发布stdout / stderr或将MQTT有效负载通过管道传递到stdin.
* [psmqtt](https://github.com/eschava/psmqtt) -通过MQTT报告实用程序的系统运行状况和状态.
* [WinThing](https://github.com/msiedlarek/winthing) -通过MQTT远程控制Windows.


#### Monitoring

* [check-mqtt](https://github.com/jpmens/check-mqtt) -Nagios / Icinga插件，用于检查与MQTT代理的连接.
* [nag2mqtt](https://github.com/DE-IBH/nag2mqtt) -Nagios事件代理到MQTT网关.
* [notify-by-mqtt](https://github.com/jpmens/notify-by-mqtt) -Nagios / Icinga通知模块，该模块将数据包装到JSON中并将其触发到MQTT代理.
* [mqtt2notifysend](https://github.com/David-Lor/MQTT2NotifySend) -订阅主题，并在Ubuntu和其他通知发送兼容的Linux发行版上显示来自MQTT消息的通知.


#### Location tracking

* [OwnTracks](https://owntracks.org/) -MQTT的位置跟踪和地理围栏.


#### Logging

* [graylog-plugin-mqtt](https://github.com/graylog-labs/graylog-plugin-mqtt) -用于Graylog的MQTT输入插件.
* [influx4mqtt](https://github.com/hobbyquaker/influx4mqtt) -订阅MQTT主题并插入InfluxDB.
* [mqtt2elasticsearch](https://github.com/hobbyquaker/mqtt2elasticsearch) -将MQTT消息发送到Elasticsearch.
* [mqtt2graphite](https://github.com/jpmens/mqtt2graphite) -订阅MQTT主题，并推送到Graphite的Carbon服务器.
* [mqttcollect](https://github.com/jpmens/mqttcollect) -为MQTT收集的“ Exec”插件.
* [mqtthandler](https://github.com/changyuheng/MQTTHandler) -用于MQTT的Python日志处理程序模块.
* [mqtt2mongodb](https://github.com/David-Lor/MQTT2MongoDB) -订阅MQTT主题并插入MongoDB.
* [mqtt-firebase](https://www.npmjs.com/package/mqtt-firebase) -一个CLI工具，用于订阅MQTT主题并将其转储到Firebase Firestore DB.


#### Smart Home Hardware Interfaces

* [aqara-mqtt](https://github.com/monster1025/aqara-mqtt) -Aqara（Xiaomi）通往MQTT桥的网关.
* [aqara2mqtt](https://github.com/hobbyquaker/aqara2mqtt) -附上 [Aqara](https://www.aqara.com/us/home.html) 智能集线器到MQTT.
* [cul2mqtt](https://github.com/hobbyquaker/cul2mqtt) -之间的接口 [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) （868MHz射频设备，例如ELV FS20，HMS，EM等）和MQTT.
* [domiqtt](https://github.com/etobi/domiqtt) -连接到Domiq Base（LCN）并与MQTT相互转换.
* [eno2mqtt](https://github.com/owagner/eno2mqtt) -Enocean USB300（TCM310）适配器和MQTT之间的接口.
* [Evohome2mqtt](https://github.com/svrooij/evohome2mqtt) - MQTT Interface for the Honeywell Evohome system.
* [helios2mqtt](https://github.com/mreschka/helios2mqtt) -用于将Helios简易控制系统（例如KWL EC 220D）同步到MQTT的守护程序.
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js)  -EQ-3的Homehome系列智能家居设备和MQTT之间的接口.  支持Homematic IP.
* [homeeToMqtt](https://github.com/odig/homeeToMqtt) -homee和MQTT之间的双向接口.
* [HS100toMQTT](https://github.com/dersimn/HS100toMQTT) -TPLink HS100 / HS110和MQTT之间的网关.
* [ipcam2mqtt](https://github.com/svrooij/ipcam2mqtt) -小型FTP服务器，用于从ipcameras接收移动图像并将其转换为MQTT警报.
* [knx-mqtt-bridge](https://github.com/pakerfeldt/knx-mqtt-bridge) -使用knx.js库建立KNX和MQTT.
* [knx2mqtt](https://github.com/owagner/knx2mqtt) -KNX家庭自动化标准和MQTT之间的接口.
* [mcsMQTT](https://shop.homeseer.com/products/mcsmqtt-software-plug-in-for-hs3) -HS3插件（HomeSeer）.
* [mqtt-dss-bridge](https://github.com/cgHome/mqtt-dss-bridge) -MQTT digitalSTROM服务器桥.
* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) -大致相反 [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt)：使用MQTT而不使用Siri或iPhone控制支持HomeKit的设备.
* [node-lox-mqtt-gateway](https://github.com/alladdin/node-lox-mqtt-gateway) -Loxone™微型服务器与MQTT代理进行通信的网关.
* [smartthings-mqtt-bridge](https://github.com/stjohnjohnson/smartthings-mqtt-bridge) -之间的桥梁 [SmartThings](https://www.smartthings.com/) 和MQTT.
* [xiaomi2mqtt](https://github.com/svrooij/node-xiaomi2mqtt) -小米智能家居网关Aquara和MQTT服务器之间的桥梁.
* [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) -允许您在没有供应商（Xiaomi / TRADFRI / Hue）桥接器/网关的情况下使用Zigbee设备.


#### Smart Home Integration Software

* [control-freak](https://github.com/catx23/control-freak)  -物联网和朋友的IDE.  内置MQTT支持.
* [Domoticz](https://www.domoticz.com/) -Domoticz Beta支持MQTT.
* [FHEM](http://fhem.de/fhem.html) 有一个 [MQTT module](http://fhem.de/commandref.html#MQTT) 自V5.6起.
* [Home Assistant](https://www.home-assistant.io/) 有一个MQTT组件.
* [Home.Pi](https://github.com/denschu/home.pi) 基于MQTT.
* [Homegear](https://homegear.eu/index.php/Main_Page) 内置了MQTT支持.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) -之间的接口 [HAP-NodeJS](https://github.com/KhaosT/HAP-NodeJS)  和MQTT.  使用Siri或HomeKit应用程序控制MQTT连接的设备.
* [ioBroker](https://github.com/ioBroker) 有一个 [MQTT adapter](https://github.com/ioBroker/ioBroker.mqtt).
* [Lelylan](http://www.lelylan.com/)  -物联网云平台.  微服务架构.  对于开发人员.
* [Node-RED](https://nodered.org/) -用于连接物联网的可视工具，具有本机MQTT支持.
* [openHAB](https://github.com/openhab) 有一个 [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) 有一个MQTT插件.


#### Lighting

* [Arilux_AL-LC0X](https://github.com/mertenats/Arilux_AL-LC0X) -这是使用MQTT的Arilux LED控制器的替代固件.
* [chromoflex2mqtt](https://github.com/owagner/chromoflex2mqtt) -通过MQTT控制Chromoflex USP3 RGB LED模块.
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) -使用MQTT作为控制通道的H801 LED调光器的备用固件.
* [hue2mqtt.js](https://github.com/hobbyquaker/hue2mqtt.js) -Philips Hue桥和MQTT之间的接口.
* [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-controller) -具有MQTT支持的DMX控制器.
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) -无头对应 [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-sequencer) -使用从MQTT DMX控制器导出的场景和序列，并通过MQTT控制它们.
* [sunricher-wifi-mqtt](https://github.com/magcode/sunricher-wifi-mqtt) -使用MQTT控制Sunricher LED设备.
* [TRADFRI2MQTT](https://github.com/hardillb/TRADFRI2MQTT) -宜家TRÅDFRILight Gateway的MQTT桥.


#### Home Entertainment

* [airtunes2mqtt](https://github.com/hobbyquaker/airtunes2mqtt) -具有Airplay / Airtunes设备的MQTT控制的多房间音频.
* [bravia2mqtt](https://github.com/forty2/bravia2mqtt) -使用MQTT控制您的Sony Bravia电视.
* [broadlink-mqtt](https://github.com/eschava/broadlink-mqtt) -MQTT客户端，用于控制BroadLink RM设备.
* [chromecast-mqtt-connector](https://github.com/nohum/chromecast-mqtt-connector) -使用MQTT控制您的Google Chromecast设备.
* [harmony-api](https://github.com/maddox/harmony-api) -简单的服务器，使您可以通过HTTP或MQTT查询/控制多个本地Harmony Home Hub.
* [htd2mqtt](https://github.com/TheOriginalAndrobot/htd2mqtt) -HTD Lync音频系统和MQTT之间的桥梁.
* [kodi2mqtt](https://github.com/owagner/kodi2mqtt) -Kodi媒体中心实例和MQTT之间的接口.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) -LG WebOS智能电视和MQTT之间的接口.
* [lirc2mqtt](https://github.com/hobbyquaker/lirc2mqtt) -通过发送和接收红外线 [LIRC](https://github.com/hobbyquaker/awesome-mqtt/blob/master/www.lirc.org).
* [mopidy-mqtt](https://github.com/magcode/mopidy-mqtt) -Mopidy的MQTT功能.
* [MQTT-DashCast-Docker](https://github.com/mukowman/MQTT-DashCast-Docker) -MQTT Docker在Chromecast上启动DashCast会话.
* [mqtt2atlonamatrix](https://github.com/forty2/mqtt2atlonamatrix) -通过MQTT控制Atlona HDMI矩阵开关.
* [mqtt2tivoremote](https://github.com/forty2/mqtt2tivoremote) -通过MQTT智能家居风格的界面使TiVo DVR遥控器可用.
* [onkyo2mqtt](https://github.com/owagner/onkyo2mqtt)  -Onkyo AVR的EISCP网络远程协议和MQTT之间的接口.  使用onkyo-eiscp库.
* [sonos2mqtt](https://github.com/svrooij/sonos2mqtt) -Sonos和MQTT之间的桥梁.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) -通过MQTT控制VLC.
* [xbmc2mqtt](https://github.com/gordonjcp/xbmc-mqtt) -XBMC的简单插件，可以在MQTT代理上侦听特定主题，并显示弹出消息.
* [yamaha-avr2mqtt](https://github.com/akentner/yamaha-avr2mqtt) -用于将Yamaha AVR连接到MQTT的简单适配器.


#### Smart Metering

* [bcontrol2mqtt](https://github.com/hobbyquaker/bcontrol2mqtt) -从TQ Energy Manager发布测量结果/ [Busch-Jäger Energy Monitor](https://www.busch-jaeger.de/files/files_ONLINE/Brosch%c3%bcre_EnergyMonitor_druck.pdf) 到MQTT.


#### Messaging

* [mqtt-irc-bot](https://github.com/dobermai/mqtt-irc-bot) -到IRC的MQTT /到MQTT桥或机器人的IRC.
* [mqttwarn](https://github.com/jpmens/mqttwarn) -订阅MQTT主题（带有通配符）并通知可插拔服务.
* [twitter-to-mqtt](https://github.com/knolleary/twitter-to-mqtt) -使用Twitter Streaming API访问推文并将其重新发布到MQTT主题的python守护程序.


#### Misc

* [AlexaMqttBridge](https://github.com/mhdawson/AlexaMqttBridge) -Amazon Alexa和MQTT之间的桥梁.
* [bt-mqtt-gateway](https://github.com/zewelor/bt-mqtt-gateway) -易于扩展的蓝牙到MQTT网关，目前支持：EQ3智能恒温器，小米Mi秤，Linak Desk，MySensors和小米Mi Flora植物传感器.
* [buderus2mqtt](https://github.com/krambox/buderus2mqtt) -Buderus KM200 Internet网关和MQTT之间的桥梁.
* [dashbutton2mqtt](https://github.com/hobbyquaker/dashbutton2mqtt) -将Amazon Dash Button的发布发布到MQTT.
* [flowerpower2mqtt](https://github.com/hobbyquaker/flowerpower2mqtt) -将测量值从鹦鹉花卉发电厂的传感器发布到MQTT.
* [gBridge](https://github.com/kservices/gBridge)  -gBridge允许您使用Google Assistant控制（几乎）任何智能家居设备，任何智能家居软件.  因此，它将语音命令从Google收到的动作转换为MQTT消息.
* [haiku2mqtt](https://github.com/forty2/haiku2mqtt) -Haiku聪明的粉丝和MQTT之间的桥梁.
* [homely](https://github.com/baol/homely) -用于连接Domoticz和其他内容的Go守护程序的集合.
* [kobold2mqtt](https://github.com/krambox/kobold2mqtt) -Vorwerk Kobold Vr200 Internet网关和MQTT之间的桥梁.
* [leaf-python-mqtt](https://github.com/glynhudson/leaf-python-mqtt) -从Nissan Leaf API中提取数据并发布到MQTT.
* [miflora-mqtt-daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) -将小米Mi Flora植物传感器数据发送到MQTT代理的Linux服务.
* [mqtt2ble](https://github.com/hardillb/mqtt2ble) -一种将MQTT主题桥接到BLE Gatt特性的方法.
* [mqttclpro](https://github.com/dc297/mqttclpro) -具有Tasker集成Android应用程序的MQTT Client.
* [mqttDB](https://github.com/hobbyquaker/mqttDB) -具有MQTT接口的JSON存储.
* [mqtt-camera-streamer](https://github.com/robmarkcole/mqtt-camera-streamer) -通过MQTT从连接的摄像机流式传输图像并使用Streamlit查看
* [node-mqtt-for-anki-overdrive](https://github.com/IBM-Cloud/node-mqtt-for-anki-overdrive) -用于Anki Overdrive的Node.js控制器和MQTT API.
* [parrot-sample](https://github.com/IBM-Cloud/parrot-sample) -使用MQTT控制派诺特AR无人机的示例代码.
* [snowboy2mqtt](https://github.com/hobbyquaker/snowboy2mqtt) -在Snowboy Hotword Detection上发布MQTT消息.
* [speedtest2mqtt](https://github.com/hobbyquaker/speedtest2mqtt) -运行speedtest-cli并通过MQTT发布结果.
* [unifi2mqtt](https://github.com/hobbyquaker/unifi2mqtt) -将连接的客户端从Ubiquiti Unifi发布到MQTT.
* [Valetudo](https://github.com/Hypfer/Valetudo) -具有MQTT和Webinterface的Xiaomi（Roborock）真空机器人固件.
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) -流行的DIY烧烤温度计的附件.
*包（Android自动化） [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin).
* [MQTT2ETCD](https://github.com/David-Lor/MQTT2ETCD) -MQTT-ETCD网关：通过MQTT在ETCD上放置PUT键，并观看关于MQTT主题的ETCD键更改


### Visualization, Dashboards

* [Crouton](https://github.com/edfungus/Crouton) -仅使用MQTT和JSON进入IOT网络的仪表板.
* [d3-MQTT-Topic-Tree](https://github.com/hardillb/d3-MQTT-Topic-Tree) -使用d3可折叠树和WebSocket上的MQTT的MQTT主题树查看器.
* [HelloIoT](https://github.com/adrianromero/helloiot) -HelloIoT是MQTT客户端和仪表板应用程序.
* [HOMR-REACT](https://github.com/klauserber/homr-react) -可配置的MQTT可视化.
* [IoT OnOff](https://www.iot-onoff.com/) -可配置的iOS / Android应用.
* [Linear MQTT Dashboard](https://github.com/ravendmaster/linear-mqtt-dashboard) -简单，可自定义的控制面板-MQTT客户端.
* [MMM-mqtt](https://github.com/javiergayala/MMM-mqtt)  -这是MagicMirror²的扩展.  它提供了订阅MQTT主题并显示它们的功能.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) -Android应用程序：使用该应用程序，您可以为启用了MQTT的IoT智能家居设备和应用程序创建仪表板.
* [MQTT-Hyperdash](https://github.com/kollokollo/MQTT-Hyperdash) -适用于linux / Raspberry Pi的通用独立MQTT仪表板.
* [mqtt-panel](https://github.com/fabaff/mqtt-panel) -MQTT的Web界面.
* [mqtt-svg-dash](https://github.com/jpmens/mqtt-svg-dash) -订阅MQTT，从消息中提取JSON，并使SVG页面上的指示灯闪烁.
* [mqtt2highcharts](https://github.com/matbor/mqtt2highcharts) -使用Highcharts绘制来自已订阅的MQTT主题的实时编号数据.
* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) -Node-RED的仪表板UI.

其他可用于创建可视化/仪表板的工具可以在下面找到 [Platforms](#platforms) 和 [Smart Home Integration Software](#smart-home-integration-software).


### Architecture, Convention

* [mqtt-smarthome](https://github.com/mqtt-smarthome/mqtt-smarthome) -以MQTT作为中央消息总线的智能家居自动化-体系结构提案.
* [The Homie Convention](https://github.com/homieiot/convention) -物联网的轻量级MQTT约定.

### Security, Encryption

* [Teserakt E4](https://teserakt.io/) -MQTT和其他M2M协议的端到端加密和密钥管理-开源和付费计划.


## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/hobbyquaker/awesome-mqtt/blob/master/contributing.md) 第一.


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
