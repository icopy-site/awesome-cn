<div class="github-widget" data-repo="mcauser/awesome-micropython"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<p align="center">
  <a href="https://awesome-micropython.com/" style="display:block"><img src="https://raw.githubusercontent.com/mcauser/awesome-micropython/master/docs/img/logo.svg"></a>
</p>
<p align="center">
  <a href="https://awesome.re">
    <img alt="Awesome" src="https://awesome.re/badge-flat.svg">
  </a>
</p>
<hr>

精选的 MicroPython 库、框架、软件和资源列表.

[MicroPython](https://micropython.org/) 是 Python 3 编程语言的精简高效实现，包括 Python 标准库的一小部分，并经过优化以在微控制器和受限环境中运行.



## Libraries

您可以在其他地方查找 MicroPython 库：

* [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython)  - 此过滤器仅显示 PyPi 上的 MicroPython 库. 注意：您不能“pip install”MicroPython 库. 见 [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html) 有关使用 MicroPython 管理包的更多信息.
* [GitHub Search](https://github.com/search?q=micropython) - 在 GitHub 上搜索包含 MicroPython 的存储库.
* [GitHub Topic - MicroPython](https://github.com/topics/micropython) - 浏览 GitHub 主题以查找带有 MicroPython 标记的项目.
* [Libraries.io](https://libraries.io/search?q=micropython) - MicroPython 的 Libraries.io 查询.
* [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc&utf8=%E2%9C%93&name=micropython&sort=latest_activity_desc) - 探索 GitLab 上的存储库.
* [Codeberg Explore](https://codeberg.org/explore/repos?tab=&sort=recentupdate&q=micropython) - 探索 Codeberg 上的存储库.

### AI

* [MicroMLP](https://github.com/jczic/MicroMLP) - 用于 MicroPython 的微神经网络多层感知器（用于 ESP32 和 Pycom 模块）.
* [MicroPython-NeuralNetwork](https://gitlab.com/olivierlenoir/MicroPython-NeuralNetwork) - MicroPython 的神经网络.

### Analytics

* [uMath](https://github.com/albaEDA/uMath) - 微控制器的计算机代数.
* [micropython-ulab](https://github.com/v923z/micropython-ulab) - 用于 MicroPython 的类似 NumPy 的快速矢量模块.
* [micropython-fourier](https://github.com/peterhinch/micropython-fourier) - MicroPython 的内联 ARM 汇编器中的快速傅立叶变换.
* [Filters](https://github.com/peterhinch/micropython-filters)  - 使用 ARM Thumb 汇编程序的 FIR 滤波器. 使用在线实用程序，您可以从图表
滤波器实现所需的频率响应.
* [ulinalg](https://github.com/jalawson/ulinalg) - 小型矩阵处理模块，带有一些专门用于 MicroPython (Python 3) 的线性代数运算.
* [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) - MicroPython 上的快速矩阵乘法和线性求解器.
* [micropython-vec](https://gitlab.com/nickoala/micropython-vec) - MicroPython 上的向量运算.
* [MicroPython_Statistics](https://github.com/rcolistete/MicroPython_Statistics) - MicroPython 的统计模块.
* [MicroPython-Matrix](https://gitlab.com/olivierlenoir/MicroPython-Matrix) - MicroPython 基本矩阵运算.

### Audio

* [micropython-jq6500](https://github.com/rdagger/micropython-jq6500) - JQ6500 UART MP3 模块的驱动程序.
* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) - DFPlayer Mini 和 Grove MP3 v2.0 使用的 KT403A 驱动程序.
* [micropython-buzzer](https://github.com/fruch/micropython-buzzer) - 在蜂鸣器上播放诺基亚 compose 和 mid 文件.
* [micropython-dfplayer](https://github.com/ShrimpingIt/micropython-dfplayer) - 使用 UART 的 DFPlayer Mini 驱动程序.
* [micropython-longwave](https://github.com/MattMatic/micropython-longwave) - 用于 MicroPython 开发板的 WAV 播放器.
* [micropython-vs1053](https://github.com/peterhinch/micropython-vs1053) - VS1053b MP3 播放器的异步驱动程序.
* [micropython-midi](https://github.com/cjbarnes18/micropython-midi) - MicroPython 的 MIDI 实现示例.
* [upy-rtttl](https://github.com/dhylands/upy-rtttl) - 用于铃声文本传输语言 (RTTTL) 的 Python 解析器.
* [micropython-i2s-examples](https://github.com/miketeachman/micropython-i2s-examples) - 运行 MicroPython 的微控制器上的 I2S 支持示例.
* [micropython-osc](https://github.com/SpotlightKid/micropython-osc) - 用于 MicroPython 的最小 OSC 客户端和服务器库.
* [micropython-sgtl5000](https://github.com/rdagger/micropython-sgtl5000) - 带耳机放大器的 SGTL5000 低功耗立体声编解码器库.

### Communications

#### APIs

* [micropython-utelegram](https://github.com/jordiprats/micropython-utelegram) - 用于 MicroPython 的电报 API 包装器.
* [uEagle](https://github.com/jcalbert/uEagle) - MicroPython 雨林 EAGLE 客户端.
* [micropython-youtube-api](https://github.com/UnexpectedMaker/micropython-youtube-api) - MicroPython 中的 YouTube API.
* [micropython_esp8266_tweetbot](https://github.com/ayoko/micropython_esp8266_tweetbot) - 适用于 MicroPython v1.8.4 (ESP8266) 的推文机器人.
* [telegram-upy](https://github.com/gabrielebarola/telegram-upy) - 用于 MicroPython 的电报 API 包装器.
* [micropython-thingspeak](https://github.com/radeklat/micropython-thingspeak) - 用于从运行 MicroPython 的物联网设备（例如 ESP8266）向 thingspeak.com 发送数据的库.
* [micropython_pushbullet](https://github.com/gsampallo/micropython_pushbullet) - 如何在 ESP8266 上将 PushBullet 与 MicroPython 结合使用的简单示例.
* [esp32-youtube-display](https://github.com/alvarowolfx/esp32-youtube-display) - 使用 Google API 和 MicroPython 显示 YouTube 指标.
* [micropython-spotify-web-api](https://github.com/tltx/micropython-spotify-web-api) - 用于通过 MicroPython 从 IoT 设备使用 Spotify 的 Web API 的库.

#### Authentication

* [micropython-firebase-auth](https://github.com/WoolDoughnut310/micropython-firebase-auth) - MicroPython 的 Firebase Auth 实现.

#### Bluetooth

* [PyBoard-HC05-Android](https://github.com/KipCrossing/PyBoard-HC05-Android) - Pyboard HC05 蓝牙适配器示例应用程序.
* [uble](https://github.com/dmazzella/uble) - 用纯 Python 为 MicroPython 编写的轻量级蓝牙低功耗驱动程序.
* [MicroPythonBLEHID](https://github.com/Heerkog/MicroPythonBLEHID) - 用于 MicroPython 的低功耗蓝牙 (BLE) GATT 库上的人机接口设备 (HID).
* [upyble](https://github.com/Carglglz/upyble) - 蓝牙低功耗 MicroPython 设备的命令行工具.
* [micropython-xiaomi-ble-adv-parse](https://codeberg.org/scy/micropython-xiaomi-ble-adv-parse) - 从一些小米低功耗蓝牙 (BLE) 传感器被动检索传感器数据.
* [mijia-temphum-upy](https://codeberg.org/scy/mijia-temphum-upy) - 用于读取某些小米米家 BLE 温度和湿度传感器的 MicroPython 库.

#### CAN

* [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) - Spacecan 是用于嵌入式系统的 SpaceCAN 协议的 MicroPython 实现.
* [Robomaster-Micropython](https://github.com/JohnieBraaf/Robomaster-Micropython) - Robomaster S1 - MicroPython CAN 总线控制器.
* [micropython-mcp2515](https://github.com/jxltom/micropython-mcp2515) - MicroPython MCP2515 驱动程序，从 Arduino MCP2515 CAN 接口库移植.

#### Compression

* [ufastlz](https://github.com/dmazzella/ufastlz) - FastLZ 的 MicroPython 包装器，一个闪电般快速的无损压缩库.

#### Cryptography

* [mpyaes](https://github.com/iyassou/mpyaes) - 用于 AES 加密的 MicroPython 模块.
* [micropython-aes](https://github.com/piaca/micropython-aes) - 纯 python 实现的 AES 算法.
* [ucrypto](https://github.com/dmazzella/ucrypto)  - 用于执行快速 RSA 和椭圆曲线加密的 MicroPython 包，特别是数字签名.  ECDSA API设计灵感来自fastecdsa，实现基于tomsfastmath.
* [ucryptoauthlib](https://github.com/dmazzella/ucryptoauthlib) - 用纯 Python 为 MicroPython 编写的用于 Microchip 加密身份验证安全元素的轻量级驱动程序.
* [embit](https://github.com/diybitcoinhardware/embit) - 用于 MicroPython 和 Python 3 的最小比特币库，专注于嵌入式系统.
* [microotp](https://github.com/gdassori/microotp) - ESP8266 MicroPython OTP 生成器.
* [micropython-rsa-signing](https://github.com/artem-smotrakov/micropython-rsa-signing) - 在 MicroPython 上进行 RSA 签名.
* [micropython-cryptomsg](https://github.com/jacklinquan/micropython-cryptomsg) - 一个 MicroPython 模块，用于使用 AES CBC 模式加密和解密消息.

#### DNS

* [ICantBelieveItsNotDNS](https://github.com/yschaeff/ICantBelieveItsNotDNS)  - “我不敢相信这不是 DNS！”  (ICBIND) 是用 MicroPython 编写的 ESP8266 的权威 DNS 服务器.
* [MicroDNSSrv](https://github.com/jczic/MicroDNSSrv) - 用于 MicroPython 的微型 DNS 服务器，用于简单地响应带或不带通配符的多域 A 查询（用于 Pycom 模块和 ESP32）.
* [tinydns](https://github.com/belyalov/tinydns) - 用于 MicroPython 的非常简单的 DNS 异步服务器.
* [micropython-captiveportal](https://github.com/metachris/micropython-captiveportal) - MicroPython 的最小异步强制门户（与 uasyncio v3/MicroPython 1.13+ 以及更早版本兼容）.
* [Micropython-DNSServer-Captive-Portal](https://github.com/p-doyle/Micropython-DNSServer-Captive-Portal) - 带有 DNS 和 Web 服务器的 MicroPython WiFi AP 强制门户.

#### Ethernet

* [Official WIZnet5k](https://github.com/andrewleech/wiznet_ioLibrary_Driver) - WIZnet5x00 系列以太网控制器的驱动程序.
* [micropy-ENC28J60](https://github.com/przemobe/micropy-ENC28J60) - 用于 MicroPython (RP2) 的 ENC28J60 以太网芯片驱动程序.
* [RP2040 Ethernet example](https://github.com/SteveSEK/Raspberry-Pi-Pico-MicroPython-Ethernet) - 以太网驱动程序、示例 Python 代码和 YouTube.

#### FTP

* [micropython-ftplib](https://github.com/SpotlightKid/micropython-ftplib) - MicroPython 的 FTP 客户端库.
* [FTP-Server-for-ESP8266-ESP32-and-PYBD](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) - MicroPython 平台上用于 ​​ESP8266/ESP32/Pyboard 的小型 FTP 服务器.
* [MicroFTPServer](https://github.com/cpopp/MicroFTPServer) - 可以在带有 MicroPython 的 ESP8266 上运行的最小 FTP 服务器.
* [micropython-uaioftp](https://github.com/cwyark/micropython-uaioftp) - 用于 MicroPython 的轻量级 FTP 库.

#### GPS

* [micropyGPS](https://github.com/inmcm/micropyGPS) - 全功能 GPS NMEA 句子解析器.
* [micropython-gnssl76l](https://github.com/tuupola/micropython-gnssl76l) - 用于 Quectel GNSS L76-L (GPS) 的 MicroPython I2C 驱动程序.
* [mpy-agps](https://github.com/pulkin/mpy-agps) - 辅助定位服务 (AGPS) 的 MicroPython 实现.
* [Asynchronous GPS driver](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/GPS.md) - 接收和解析 GPS 数据作为 uasyncio 任务.

#### GSM

* [micropython-upyphone](https://github.com/jeffmer/micropython-upyphone) - 使用 Pyboard 和 SIM800l 的 GSM 手机.
* [micropython-sim800](https://github.com/olablt/micropython-sim800) - SIM800 的 MicroPython 驱动程序.
* [sim800](https://github.com/basanovase/sim800) - 用于与 MicroPython 中的 SIM800 模块接口的库.
* [MicroPython-AM7020](https://github.com/JiekangHuang/MicroPython-AM7020) - 用于 AM7020 窄带物联网 (NBIoT) 模块的 MicroPython 驱动程序.

#### IoT

* [microhomie](https://github.com/microhomie/microhomie) - 用于物联网的 Homie MQTT 约定的 MicroPython 实现.
* [uPyEcho](https://github.com/lemariva/uPyEcho) - 在 ESP32 上使用 MicroPython 模拟 Belkin WeMo 设备，该设备可与 Amazon Echo (Alexa) 配合使用.
* [SonosRemote](https://github.com/foosel/SonosRemote) - 在 ESP8266 上运行并使用 Sonos HTTP API 的 Sonos 安装遥控器.
* [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) - 基于 MicroPython 的脚本，用于扩展您的 Home Assistant 驱动的家庭自动化项目.
* [micropython-iot](https://github.com/peterhinch/micropython-iot) - 一种使用 ESP8266、ESP32 或 Pyboard D 端点设计物联网应用的方法.
* [iot-core-micropython](https://github.com/GoogleCloudPlatform/iot-core-micropython) - Use MicroPython to connect to Google Cloud IoT Core.
* [SmartUPy](https://github.com/lemariva/SmartUPy) - 使用 MicroPython 控制“涂鸦式”智能电源插座.
* [aws-iot-GET-POST-loop](https://github.com/manningt/aws-iot-GET-POST-loop) - 使用 AWS IoT REST API 获取/发布设备状态信息的 MicroPython 代码.
* [sensor-mqtt-homeassistant](https://github.com/DougWilkinson/sensor-mqtt-homeassistant)  - 基于 ESP8266/ESP32 MicroPython 的传感器平台，适用于 GPIO、DHT、模拟、LED 等. 包括来自 Web 服务器和 MQTT/Home Assistant 集成的 .py 代码的远程更新.

#### IR

* [micropython-necir](https://github.com/MattMatic/micropython-necir) - 用于 TL1838 红外接收器 LED 的 NEC 红外捕获.
* [Micropython-IR](https://github.com/designerPing/Micropython-IR) - Pyboard 红外远程嗅探和回放.
* [micropython_ir](https://github.com/peterhinch/micropython_ir) - 非阻塞设备驱动程序，用于从 IR 遥控器和 IR“blaster”应用程序接收.
* [micropython-amg88xx](https://github.com/peterhinch/micropython-amg88xx) - Grid-EYE 热红外阵列传感器 (Adafruit 3538) 的驱动程序.
* [micropython-ys-irtm](https://github.com/mcauser/micropython-ys-irtm) - YS-IRTM 5V NEC 红外 UART 收发器的 MicroPython 示例.
* [esp8266_ir](https://github.com/ruoyu0088/esp8266_ir) - 通过 WebSocket 控制红外信号.
* [micropython_espX_IR_Transceiver](https://github.com/gamefunc/micropython_espX_IR_Transceiver) - MicroPython ESP32 红外收发器.
* [pico-ir](https://github.com/bartoszadamczyk/pico-ir) - Raspberry Pi Pico 的 IR 库.

#### LoRaWAN

* [uPyLoRaWAN](https://github.com/lemariva/uPyLoRaWAN) - 使用 MicroPython 的 ESP32 符合 LoRa 和 LoRaWAN.
* [SX127x_driver_for_MicroPython_on_ESP8266](https://github.com/Wei1234c/SX127x_driver_for_MicroPython_on_ESP8266) - 用于 ESP8266/ESP32/Raspberry Pi 上的 (Micro)Python 的 SX127x（LoRa 收发器）驱动程序.
* [LightLora_MicroPython](https://github.com/MZachmann/LightLora_MicroPython) - 用于 MicroPython 的轻量级中断驱动的 Semtech SX127x 库.
* [u-lora](https://github.com/martynwheeler/u-lora) - Raspi-lora for MicroPython.
* [sx127x_esp](https://github.com/azorg/sx127x_esp) - 将基于 LoRaTM sx127x 芯片的 Ra-01 模块连接到 MicroPython 下的 ESP8266/ESP32.
* [nanoserver](https://github.com/gradoj/nanoserver) - MicroPython 嵌入式 LoRaWAN 服务器.
* [micropySX126X](https://github.com/ehong-tl/micropySX126X) - 用于 MicroPython 和 CircuitPython 的 Semtech SX126X LoRa 驱动程序.

#### MDNS

* [micropython-mdns](https://github.com/cbrand/micropython-mdns) - 支持服务发现的 MDNS 的纯 Python 实现.

#### Modbus

* [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) - modbus-tk 的 MicroPython 端口.
* [micropython-modbus](https://github.com/techbase123/micropython-modbus)  - 用于 MicroPython ESP32 设备的 Modbus Master 库. 基于 Pycom 的 pycom-modbus.
* [mp_modbus](https://github.com/eydam-prototyping/mp_modbus) - MicroPython 的 Modbus 库.
* [micropython-modbus](https://github.com/brainelectronics/micropython-modbus)  - 支持客户端和主机模式的 ModBus TCP 和 RTU 库. 基于 Pycom 的 pycom-modbus.

#### MQTT

* [micropython-mqtt](https://github.com/peterhinch/micropython-mqtt)  - “弹性”异步 MQTT 驱动程序. 加上使用 ESP8266 将 MQTT 带到非联网目标的方法.
* [MQBoard](https://github.com/tve/mqboard) - 在 MicroPython 板上（主要是在 ESP32 上）将 MQTT 与 asyncio 结合使用的微框架.
* [pysmartnode](https://github.com/kevinkk525/pysmartnode) - MicroPython 智能家居框架.
* [umqtt_aws_iot](https://github.com/juwul/umqtt_aws_iot) - Publish UMQTT messages with MicroPython to AWS IoT.
* [sonoff-mqtt by davea](https://github.com/davea/sonoff-mqtt) - 使用 MQTT 控制 Sonoff/ESP8266 的 MicroPython 脚本.
* [micropython-sonoff-switch](https://github.com/kfricke/micropython-sonoff-switch) - 使用 MicroPython 为 iTead Sonoff 开关实施 MQTT 可控开关.
* [micropython-thingspeak-mqtt-esp8266](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) - 使用 MQTT 和在 ESP8266/ESP32 平台上运行的 MicroPython 发布和订阅 ThingSpeak.
* [uMQTT](https://github.com/andrewmk/uMQTT) - 在 WiPy 板上为 MicroPython 发布 MQTT.
* [micropython-mqtt](https://github.com/chrismoorhouse/micropython-mqtt) - 为 ESP32 或 Pycom 设备等 MicroPython 设备自动重新连接的异步 MQTT 库.
* [micropython-adafruit-mqtt-esp8266](https://github.com/miketeachman/micropython-adafruit-mqtt-esp8266)  - 使用 MQTT 发布/订阅 Adafruit IO.  ESP8266/ESP32 上的 MicroPython/CircuitPython 实现.
* [MicropythonCayenneMQTTClient](https://github.com/uraich/MicropythonCayenneMQTTClient) - Python Cayenne MQTT 客户端到 MicroPython 的端口.
* [mqtt_upython](https://github.com/matbgn/mqtt_upython) - 在 ESP8266 上使用 MicroPython 的 MQTT 客户端.

#### NFC

* [micropython-nfc](https://github.com/rolandvs/micropython-nfc) - 将 NFC 与 MicroPython 结合使用.
* [micropython_pn532](https://github.com/luiz-brandao/micropython_pn532) - 基于 Adafruit CircuitPython (UART) 的 PN532 NFC/RFID 分线板驱动程序.
* [NFC_PN532_SPI](https://github.com/Carglglz/NFC_PN532_SPI) - Adafruit CircuitPython 的部分端口到 PN532 NFC/RFID 控制库 (SPI) 的 MicroPython.

#### NTP

* [esp8266_ntp_webserver](https://github.com/Roterfux/esp8266_ntp_webserver) - MicroPython + ESP8266 + NTP + 网络服务器.
* [micropython-ntpd](https://github.com/dave2/micropython-ntpd) - 在 MicroPython 中实现 NTP 守护进程.
* [micropython_ntpserver](https://github.com/GrantGMiller/micropython_ntpserver) - 为 MicroPython 编写的 NTP 服务器.
* [micropython-ntpclient](https://github.com/wieck/micropython-ntpclient) - 使用 uasyncio 的 MicroPython 的 NTP 客户端.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/bus/onewire) - 对于使用 OneWire 总线的设备，例如 Dallas DS18x20.
* [Onewire_DS18X20](https://github.com/robert-hh/Onewire_DS18X20) - 使用适用于 Pycom MicroPython 的 OneWire 协议驱动 DS18x20 传感器的类.

#### Onkyo EISCP

* [eiscp-micropython](https://github.com/cbrand/eiscp-micropython) - 用于 Onkyo-EISCP 协议的 MicroPython 端口，其中包括 Pioneer.

#### OTA

* [micropython-ota-updater](https://github.com/rdehuyss/micropython-ota-updater) - MicroPython 的 OTA 更新程序.
* [Micropython-ESP32-OTA](https://github.com/AkhileshThorat/Micropython-ESP32-OTA) - 基于 rdehuyss/micropython-ota-updater 的 MicroPython 更新程序.
* [senko](https://github.com/RangerDigital/senko) - 适用于您的 MicroPython 项目的最简单的 OTA 更新解决方案.

#### Radio

* [micropython-radio](https://github.com/peterhinch/micropython-radio) - nRF24L01 2.4GHz 无线电模块的协议.
* [micropython-rfsocket](https://github.com/wuub/micropython-rfsocket) - 流行的基于 433MHz 的 RFSockets 的 MicroPython 实现.
* [Official nRF24L01](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/radio/nrf24l01) - nRF24L01 2.4GHz 无线电模块的官方驱动程序.
* [micropython_remote](https://github.com/peterhinch/micropython_remote)  - 捕获和回放 433MHz 遥控代码. 控制远程开关电源适配器.
* [micropython-ys-rf34t](https://github.com/mcauser/micropython-ys-rf34t) - 使用 YS-RF34T 433MHz ASK/OOK UART 收发器的 MicroPython 示例.
* [FM_Talkie](https://github.com/Wei1234c/FM_Talkie) - 使用 RDA5820N 的 FM 对讲机.
* [micropython-TEA5767](https://github.com/alankrantas/micropython-TEA5767) - 用于 TEA5767 FM 收音机模块的 MicroPython ESP8266/ESP32 驱动程序.
* [micropython-ppm-decoder](https://github.com/dastultz/micropython-ppm-decoder) - 用于解码 R/C 接收器 PPM 帧信号的实用程序.
* [ESP32-433Mhz-Receiver-and-Tools](https://github.com/Aschhoff/ESP32-433Mhz-Receiver-and-Tools) - 用 MicroPython 和 Windows 工具编写的 ESP32 433MHz 接收器.

#### REPL

* [webrepl](https://micropython.org/webrepl) - MicroPython WebREPL.
* [zepl](https://gitlab.com/zepl1/zepl) - 使用 ZeroMQ 的 MicroPython WebREPL 控制台应用程序.
* [jupyter_micropython_remote](https://gitlab.com/alelec/jupyter_micropython_remote) - Jupyter 内核通过串行/网络 REPL 直接在 MicroPython 板上执行代码.
* [FBConsole](https://github.com/boochow/FBConsole) - MicroPython 的帧缓冲区控制台类.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) - NXP MFRC522 RFID 读取器/写入器的驱动程序.
* [micropython-wiegand](https://github.com/pjz/micropython-wiegand) - 韦根协议阅读器.
* [urdm6300](https://github.com/membermatters/urdm6300) - 用于流行的 RDM6300 RFID 读卡器的 MicroPython 驱动程序.

#### RTC

* [micropython-tinyrtc-i2c](https://github.com/mcauser/micropython-tinyrtc-i2c) - DS1307 RTC 和 AT24C32N EEPROM 的驱动程序.
* [Micropython_TinyRTC](https://github.com/AnthonyKNorman/Micropython_TinyRTC) - DS1307 RTC 的驱动程序.
* [micropython-mcp7940](https://github.com/mattytrentini/micropython-mcp7940) - Microchip MCP7940 RTC 的驱动程序.
* [micropython-ds1302-rtc](https://github.com/omarbenhamid/micropython-ds1302-rtc) - 用于 MicroPython 的 DS1302 RTC 时钟驱动程序.
* [DS3231micro](https://github.com/notUnique/DS3231micro) - DS3231 的 MicroPython 库.

#### Serial

* [mpy-miniterm](https://github.com/jeffmakes/mpy-miniterm) - 通过串行 REPL 与 MicroPython 设备进行无缝串行调试和文件同步的工具.
* [MicroPython-MorseCode](https://gitlab.com/olivierlenoir/MicroPython-MorseCode) - 使用带有 MicroPython 的微控制器的国际摩尔斯电码.
* [I2C Slave](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/I2C.md)  - 使用 Pyboard 的 I2C 从模式实现全双工异步链接. 主要用例是针对只有一个 UART 的 ESP8266.

#### Serialization

* [micropython-msgpack](https://github.com/peterhinch/micropython-msgpack) - 针对 MicroPython 优化的 MessagePack 序列化库.
* [micropython-uprotobuf](https://github.com/jazzycamel/micropython-uprotobuf) - A lightweight implementation of Google's Protocol Buffers (protobuf) for MicroPython.
* [minipb](https://github.com/dogtopus/minipb) - 纯 Python 中的 Mini Protobuf {de} 序列化器.

#### SOCKS

* [micropython-socks](https://github.com/kost/micropython-socks) - 实现 SOCKS 服务器的 MicroPython 库.

#### SMTP

* [uMail](https://github.com/shawwwn/uMail) - 用于在 MicroPython 中发送电子邮件的轻量级、可扩展的 SMTP 客户端.

#### TCP

* [us2n](https://github.com/tiagocoutinho/us2n) - ESP32 的 UART 和 TCP 之间的 MicroPython 桥.

#### Telnet

* [MicroTelnetServer](https://github.com/cpopp/MicroTelnetServer) - 用于 MicroPython 和 ESP8266 的简单 telnet 服务器，允许 telnet 客户端访问 REPL.

#### VoIP

* [uPyVoip](https://github.com/RetepRelleum/uPyVoip) - 具有交互式语音响应的 MicroPython ESP32 的 VoIP.

#### WiFi

* [HueBridge](https://github.com/FRC4564/HueBridge) - 飞利浦 Hue 桥.
* [micropython-wifimanager](https://github.com/mitchins/micropython-wifimanager) - ESP8266 板上 MicroPython 的简单网络配置实用程序.
* [WiFiManager](https://github.com/tayfunulu/WiFiManager) - ESP8266 的 WiFi 管理器 - ESP12 - ESP32 - MicroPython.
* [Micropython-ESP-WiFi-Manager](https://github.com/brainelectronics/Micropython-ESP-WiFi-Manager) - 用于配置和连接到网络的 WiFi 管理器.

#### Web

* [MicroWebSrv](https://github.com/jczic/MicroWebSrv) - 支持 WebSockets、HTML/Python 语言模板和路由处理程序的微型 HTTP Web 服务器，适用于 MicroPython（用于 Pycom 模块和 ESP32）.
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - 最后一个用于物联网 (MicroPython) 或大型服务器 (CPython) 的微型 Web 服务器，支持 WebSocket、路由、模板引擎并具有真正优化的架构（内存分配、异步 I/O）.
* [tinyweb](https://github.com/belyalov/tinyweb) - 用于 MicroPython 的简单轻量级 HTTP 异步服务器.
* [upy-websocket-server](https://github.com/BetaRavener/upy-websocket-server) - MicroPython (ESP8266) WebSocket 服务器实现.
* [micropython-captive-portal](https://github.com/amora-labs/micropython-captive-portal) - MicroPython 的强制门户演示.
* [uPyPortal](https://github.com/lemariva/uPyPortal) - 使用 ESP32 (Wemos) 的 MicroPython 强制门户.
* [ESP8266WebServer](https://github.com/codemee/ESP8266WebServer) - 用于 MicroPython 的 ESP8266 网络服务器.
* [microCoAPy](https://github.com/insighio/microCoAPy) - CoAP（受限应用程序协议）到 MicroPython 的迷你客户端/服务器实现.
* [micropyserver](https://github.com/troublegum/micropyserver) - MicroPyServer 是用于 MicroPython 项目的简单 HTTP 服务器.
* [MicroRESTCli](https://github.com/jczic/MicroRESTCli) - 基于用于 MicroPython 的 MicroWebCli 的微型 JSON REST Web 客户端（用于 Pycom 模块和 ESP32）.
* [micropython-noggin](https://github.com/larsks/micropython-noggin) - 一个非常简单的 MicroPython 网络服务器.
* [uwebsockets](https://github.com/danni/uwebsockets) - ESP8266 的 MicroPython WebSocket 实现.
* [microdot](https://github.com/miguelgrinberg/microdot) - 超小的 MicroPython 网络框架.
* [micropython-nanoweb](https://github.com/hugokernel/micropython-nanoweb) - 内存占用少的全异步 MicroPython Web 服务器.
* [MicroWebCli](https://github.com/jczic/MicroWebCli) - 用于 MicroPython 的微型 HTTP Web 客户端（用于 Pycom 模块和 ESP32）.
* [micropython-configserver](https://github.com/carstenblt/micropython-configserver) - MicroPython 的强制门户，包括一个哑 DNS 服务器和一个用于配置 WiFi 网络的 Web 服务器.
* [micropython-aioweb](https://github.com/wybiral/micropython-aioweb) - 用于 MicroPython 的极简异步 Web 框架.
* [thimble](https://github.com/DavesCodeMusings/thimble) - 用于 MicroPython 的微型 Web 框架.

#### Zigbee

* [ZbPy](https://github.com/osresearch/ZbPy) - MicroPython IEEE802.15.4 / Zigbee 解析器.

### Display

#### E-Paper

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - SSD1606 有源矩阵电子纸显示器 128x180.
* [micropython-waveshare-epaper](https://github.com/mcauser/micropython-waveshare-epaper) - 各种 Waveshare ePaper 模块的驱动程序.
* [micropython-waveshare-epd](https://github.com/ayoy/micropython-waveshare-epd) - Waveshare 电子纸显示驱动程序，用于运行 Pycom 风格的 MicroPython 的设备.
* [ssd1675a](https://github.com/mattytrentini/ssd1675a) - 用于基于 SSD1675 的电子纸显示器的驱动程序.
* [Inkplate-micropython](https://github.com/SolderedElectronics/Inkplate-micropython) - Inkplate 板的 MicroPython 驱动程序.
* [micropython-inkplate6](https://github.com/tve/micropython-inkplate6) - Inkplate 6 的 MicroPython 驱动程序.
* [eInk-micropython](https://github.com/dhallgb/eInk-micropython) - MicroPython 上 Waveshare 4.3 英寸设备的 eInk 库.
* [eink](https://github.com/chevdor/eink) - 用于 MicroPython 和 ESP32 的 eInk、ePaper 显示驱动程序.
* [micropython_DEPG0213BN](https://github.com/Inqbus/micropython_DEPG0213BN) - 用于 TTGO T5 V2.3 ESP32 板上的 DEPG0213BN eInk 显示器的纯 MicroPython 驱动程序.

#### Fonts

* [micropython-font-to-py](https://github.com/peterhinch/micropython-font-to-py) - 一个 Python 3 实用程序，用于将字体转换为能够作为字节码冻结的 Python 源代码.
* [writer](https://github.com/peterhinch/micropython-font-to-py/blob/master/writer/WRITER.md) - 一种将 Python 字体以上渲染到显示器的简单方法，其驱动程序是 `framebuf` 的子类.
* [ssd1306big](https://github.com/nickpmulder/ssd1306big) - 128x64 像素 SSD1306 OLED 显示屏上的 MicroPython 字体.

#### Graphics

* [micropython-stage](https://github.com/python-ugame/micropython-stage) - Stage 游戏库的 MicroPython 端口.
* [micropython-png](https://github.com/Ratfink/micropython-png) - 与 MicroPython 一起使用的 PyPNG 的衍生物.
* [mpy-img-decoder](https://github.com/remixer-dec/mpy-img-decoder) - 纯 MicroPython 中的 PNG 和 JPEG 解码器/解析器/渲染器.
* [micropython-oled-progressbars](https://github.com/follower46/micropython-oled-progressbars) - 用于 OLED 显示屏上的 ESP8266 和 ESP32 的进度条集合.
* [microplot](https://github.com/romilly/microplot) - 简单的 MicroPython 绘图包.

#### GUI

* [lvgl](https://github.com/lvgl/lv_binding_micropython) - 一个面向对象、基于组件的高级 GUI 库，具有 MicroPython 绑定.
* [micropython-lcd160cr-gui](https://github.com/peterhinch/micropython-lcd160cr-gui) - 用于 Pyboard 和 LCD160CR 彩色显示器的基于简单触摸驱动事件的 GUI.
* [micropython_ra8875](https://github.com/peterhinch/micropython_ra8875) - 用于基于 RA8875 的显示器的 MicroPython 设备驱动程序和 nano-GUI.
* [micropython-nano-gui](https://github.com/peterhinch/micropython-nano-gui)  - 一个微型的仅显示 GUI，带有一组有限的 GUI 对象（小部件），用于显示器，其显示驱动程序是从 `framebuf` 类子类化的. 带有用于 TFT、电子纸和 OLED 显示器的驱动程序.
* [micro-gui](https://github.com/peterhinch/micropython-micro-gui) - 源自 nano-gui 并支持相同的显示器和主机，这为用户提供
通过按钮或导航操纵杆和可选的旋转编码器输入.
* [TFT-GUI](https://github.com/peterhinch/micropython-tft-gui) - 基于带有 XPT2046 触摸控制器的 SSD1963 控制器的大型显示器的快速触摸 GUI.
* [micropython-nextion](https://github.com/brainelectronics/micropython-nextion) - 使用 MicroPython 控制 Nextion 显示.

#### LCD Character

* [Grove_RGB_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) - SeeedStudio 的 Grove RGB LCD 驱动程序.
* [lcdi2c](https://github.com/slothyrulez/lcdi2c) - 适用于 HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-charlcd](https://github.com/rdagger/micropython-charlcd) - HD44780 兼容 LCD 的驱动程序.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) - I2C 2x16 LCD 屏幕的驱动程序.
* [pyboard-LCD-character-display](https://github.com/scitoast/pyboard-LCD-character-display) - 用于兼容 HDD44780 的 1602 LCD 的 Pyboar 驱动程序.
* [python_lcd](https://github.com/dhylands/python_lcd) - 适用于 HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-lcd](https://github.com/wjdp/micropython-lcd) - 用于从 MicroPython Pyboard 控制 HD44780 的类.
* [HD44780-lcd-upy](https://gitlab.com/rafalosa/HD44780-lcd-upy) - 用于控制通用 HD44780 LCD 的 MicroPython 模块.
* [LCM1602-14_LCD_Library](https://github.com/Bhavithiran97/LCM1602-14_LCD_Library) - AIP31068L 的驱动程序 [3.3 V I2C and SPI 1602 Serial Character LCDs](https://www.cytron.io/p-3v3-i2c-and-spi-1602-serial-character-lcd).

#### LCD Graphic

* [micropython-lcd-AQM1248A](https://github.com/forester3/micropython-lcd-AQM1248A) - 用于 AQM1248A 图形 LCD 的 ESP8266 驱动程序.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) - 诺基亚 5110 PCD8544 84x48 LCD 模块的驱动程序.
* [micropython-st7565](https://github.com/nquest/micropython-st7565) - ST7565 128x64 LCD 的驱动程序.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) - 使用 ESP8266 和 SPI 的 ST7920 128x64 单色 LCD 面板上的简单图形基元库.
* [MicroPython_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) - 诺基亚 5110 PCD8544 的 ESP8266 驱动程序.
* [Official LCD160CR](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/lcd160cr) - 带有电阻式触摸传感器的官方 MicroPython LCD160CR 显示器的驱动程序.
* [micropython-hx1230](https://github.com/mcauser/micropython-hx1230) - 用于 HX1230 96x68 LCD 模块的 MicroPython 库.
* [micropython-SHARP_Memory_Display](https://github.com/pramasoul/micropython-SHARP_Memory_Display) - 用于 SHARP 内存显示的 MicroPython 驱动程序.

#### LCD TFT

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - 用于 TFT 显示器、ILI9341、SH1106、SSD1606、ST7735 的驱动程序集合.
* [micropython-ili934x](https://github.com/tuupola/micropython-ili934x) - 用于基于 ILI934X 系列的 TFT/LCD 显示器的 SPI 驱动程序.
* [MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735) - GuyCarvers 的 ST7735 TFT LCD 驱动器的 ESP32 版本.
* [micropython-st7735](https://github.com/hosaka/micropython-st7735) - ST7735 TFT LCD 的驱动程序.
* [MicroPython_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735) - ST7735 128x128 TFT 的驱动程序.
* [SSD1963-TFT-Library-for-PyBoard-and-RP2040](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) - 用于 Pyboard 和 Raspberry Pi Pico 的 SSD1963 TFT 库.
* [ST7735](https://github.com/GuyCarver/MicroPython/blob/master/lib/ST7735.py) - ST7735 TFT LCD 的驱动程序.
* [micropython-ili9341](https://github.com/rdagger/micropython-ili9341) - MicroPython ILI9341 显示器和 XPT2046 触摸屏驱动程序.
* [st7789_mpy](https://github.com/devbis/st7789_mpy) - 用于 MicroPython 的快速纯 C 驱动程序，可以处理 ST7789 芯片上的显示模块.
* [st7789py_mpy](https://github.com/devbis/st7789py_mpy) - 用于 240x240 ST7789 显示器的慢速 MicroPython 驱动程序，没有全球速卖通的 CS 引脚，用 MicroPython 编写.
* [micropython-ili9341](https://github.com/jeffmer/micropython-ili9341) - MicroPython Driver for ILI9341 display.
* [micropython-ili9341](https://github.com/tkurbad/micropython-ili9341) - ESP32 上用于 MicroPython 的 ILI9341 TFT 驱动程序.
* [st7789_mpy](https://github.com/russhughes/st7789_mpy) - 用 C 编写的用于 ST7789 显示模块的快速 MicroPython 驱动程序.
* [st7789py_mpy](https://github.com/russhughes/st7789py_mpy) - 用 MicroPython 编写的 320x240、240x240 和 135x240 ST7789 显示器驱动程序.
* [ili9342c_mpy](https://github.com/russhughes/ili9342c_mpy) - 适用于 MicroPython（M5Stack 核心）的 ILI9342C 快速“C”驱动程序.
* [gc9a01py](https://github.com/russhughes/gc9a01py) - MicroPython 中的 GC9A01 显示驱动程序.
* [gc9a01_mpy](https://github.com/russhughes/gc9a01_mpy) - 用 C 编写的用于 GC9A01 显示模块的快速 MicroPython 驱动程序.
* [st7735-esp8266-micropython](https://github.com/cheungbx/st7735-esp8266-micropython) - 用于 ST7735 160x80、128x128、128x160 TFT LCD 显示器的 ESP8266 MicroPython 库.
* [TTGO-ST7789-MicroPython](https://github.com/schumixmd/TTGO-ST7789-MicroPython) - 用于 TTGO T-Display ESP32 CP2104 WiFi 蓝牙模块 1.14 英寸 LCD 的 MicroPython ST7789 显示驱动程序.
* [st7735_micropython](https://github.com/cheungbx/st7735_micropython) - 用于 ESP8266 的 80x160、128x128、128x160 的 ST7735 MicroPython 驱动程序.
* [ili934x-micropython](https://gitlab.com/mhepp63/ili934x-micropython) - 用于将 ILI9341 显示驱动程序与 MicroPython 结合使用的库.
* [micropython-st7735-esp8266](https://gitlab.com/mo_krauti/micropython-st7735-esp8266) - 用于 ESP8266 上 ST7735 TFT 显示器的 MicroPython 驱动程序.

#### LED Matrix

* [micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c) - 驱动 HT1632C 32x16 双色 LED 矩阵.
* [micropython-matrix8x8](https://github.com/JanBednarik/micropython-matrix8x8) - 带 HT16K33 背包的 Adafruit 8x8 LED 矩阵显示器的驱动程序.
* [micropython-max7219](https://github.com/mcauser/micropython-max7219) - MAX7219 8x8 LED 矩阵模块的驱动器.
* [micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield) - 用于 Wemos D1 迷你矩阵 LED 屏蔽的驱动程序，使用 TM1640 芯片.
* [micropython-wemos-led-matrix](https://github.com/mattytrentini/micropython-wemos-led-matrix) - 用于 Wemos D1 迷你矩阵 LED 屏蔽的驱动程序，使用 TM1640 芯片.
* [micropython-max7219](https://github.com/vrialland/micropython-max7219) - 用于 MAX7219 8x8 LED 矩阵的 MicroPython 驱动程序.

#### LED Segment

* [LKM1638](https://github.com/arikb/LKM1638) - 基于TM1638控制器的JY-LKM1638显示器驱动程序.
* [max7219_8digit](https://github.com/pdwerryhouse/max7219_8digit) - MAX7219 8 位 7 段 LED 模块的驱动器.
* [micropython-max7219](https://github.com/JulienBacquart/micropython-max7219) - MAX7219 8 位 7 段 LED 模块的驱动器.
* [micropython-my9221](https://github.com/mcauser/micropython-my9221) - MY9221 10 段 LED 条形图模块的驱动程序.
* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) - TM1637 四路 7 段 LED 模块的驱动程序.
* [micropython-tm1638](https://github.com/mcauser/micropython-tm1638) - 用于带开关的 TM1638 双四路 7 段 LED 模块的驱动器.
* [micropython-tm1640](https://github.com/mcauser/micropython-tm1640) - TM1740 8x8 LED 矩阵模块的驱动程序.
* [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) - 用于由 TM1640 控制的 16 位 7 段显示器的 MicroPython 库.
* [TM74HC595](https://github.com/Sakartu/TM74HC595) - 移位寄存器控制的 5 针显示模块的驱动程序.

#### LEDs

* [micropython-morsecode](https://github.com/mampersat/micropython-morsecode) - 闪烁带有摩尔斯编码信息的 LED.
* [micropython-p9813](https://github.com/mcauser/micropython-p9813) - SeeedStudio 的 Grove 可链接 RGB LED 中使用的 P9813 RGB LED 驱动器.
* [micropython-ws2812-7seg](https://github.com/HubertD/micropython-ws2812-7seg) - 使用 WS2812 RGB LED 的 7 段显示器.
* [micropython-ws2812](https://github.com/JanBednarik/micropython-ws2812) - WS2812 RGB LED 驱动程序.
* [Official APA102](https://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) - ESP8266 APA102/DotStar RGB LED 驱动器.
* [Official WS2811](https://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) - ESP8266 WS2811/NeoPixel RGB LED 驱动器.
* [tlc5940-micropython](https://github.com/oysols/tlc5940-micropython) - 用于 TLC5940 16 通道 LED 驱动器的驱动器.
* [ws2812-SPI](https://github.com/nickovs/ws2812-SPI) - 高效的 MicroPython WS2812 (NeoPixel) 驱动程序.
* [micropython-ws2801](https://github.com/HeMan/micropython-ws2801) - 用于连接 WS2801 RGB LED 串的 MicroPython 库.
* [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) - TLC5947 24 通道 12 位 PWM LED 驱动器的驱动器.
* [Hybotics_Micropython_HT16K33](https://github.com/hybotics/micropython-ht16k33) - HT16K33 的 MicroPython 驱动程序，一个 LED 矩阵，7 段数字和 14 段字母数字显示驱动器 IC.
* [micropython-rgbled](https://github.com/Warringer/micropython-rgbled) - 此包装器模块旨在减少使用 NeoPixel (WS2812) 和 DotStar (APA102) RGB LED 灯条和矩阵所需的工作.
* [micropython_fastled](https://github.com/kdschlosser/micropython_fastled) - FastLED 到 MicroPython 的端口.
* [micropython_quickled](https://github.com/thebaron88/micropython_quickled) - MicroPython 模块允许 Python 全速将数据泵入 WS2811 LED.
* [micropython-rgb-led-driver](https://gitlab.com/Athanaze/micropython-rgb-led-driver) - 使用 PWM 控制 RGB LED 的微型驱动程序.
* [micropython-dotstar](https://github.com/mattytrentini/micropython-dotstar) - Adafruit CircuitPython APA102/DotStar 库的 MicroPython 端口.

#### OLED

* [Grove_OLED](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) - SeeedStudio 的 Grove OLED 显示器 1.12&quot; v1.0 使用的 SSD1327 驱动程序.
* [micropython-oled](https://github.com/mcauser/deshipu-micropython-oled) - 用于单色 OLED 显示器、PCD8544、SH1106、SSD1306、UC1701X 的驱动程序集合.
* [micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327) - SSD1327 128x128 4 位灰度 OLED 显示器的驱动程序.
* [micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351) - SSD1351 OLED 显示器的驱动程序.
* [MicroPython_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306) - 用于 SSD1306 OLED 128x64 显示器的 ESP8266 驱动程序.
* [Official SSD1306](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/ssd1306) - SSD1306 128x64 OLED 显示器的驱动程序.
* [SH1106](https://github.com/robert-hh/SH1106) - SH1106 OLED 显示器的驱动程序.
* [micropython-ssd1309](https://github.com/rdagger/micropython-ssd1309) - MicroPython SSD1309 单色 OLED 显示驱动程序.
* [sh1107-micropython](https://github.com/nemart69/sh1107-micropython) - 用于基于 SH1107 的 OLED 显示器 (64x128) 的 MicroPython 驱动程序.

#### Printer

* [micropython-thermal-printer](https://github.com/ayoy/micropython-thermal-printer) - Adafruit 的 Python 热敏打印机的 MicroPython 端口.

### IO

#### ADC

* [ads1x15](https://github.com/robert-hh/ads1x15) - ADS1015/ADS1115 ADC、I2C 接口的驱动程序.
* [micropython-ads1015](https://github.com/mcauser/deshipu-micropython-ads1015) - ADS1015 12 位和 ADS1115 16 位 ADC，具有可编程增益的 4 个通道，I2C 接口.
* [Micropython_ADS1115](https://github.com/AnthonyKNorman/Micropython_ADS1115) - ADS1115 16 位 ADC，具有可编程增益的 4 个通道，I2C 接口.
* [ADS7818](https://github.com/robert-hh/ADS7818) - 连接 ADS7818 AD 转换器的 Python 类.
* [micropython-ads1219](https://github.com/miketeachman/micropython-ads1219) - 用于德州仪器 ADS1219 ADC 的 MicroPython 模块.
* [micropython-hx711](https://github.com/SergeyPiskunov/micropython-hx711) - 用于 HX711 24 位模数转换器的 MicroPython 驱动程序.
* [MicroPython-ADC_Cal](https://github.com/matthias-bs/MicroPython-ADC_Cal) - ESP32 ADC 驱动器使用来自 efuse 的参考电压校准值.
* [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) - 用于 PCF8591 ADC/DAC、I2C 接口的 MicroPython 驱动程序.

#### DAC

* [micropython-mcp4725](https://github.com/wayoda/micropython-mcp4725) - MCP4725 I2C DAC 的驱动程序.
* [mcp4728](https://github.com/openfablab/mcp4728) - Microchip MCP4728 I2C 12 位四路 DAC 的帮助程序库.

#### GPIO

* [micropython-inputs](https://github.com/alanmitchell/micropython-inputs) - 用于对 MicroPython 板进行脉冲计数、数字输入去抖和计算模拟输入移动平均值的类.
* [ubutton](https://gitlab.com/WiLED-Project/ubutton) - 一个 MicroPython 库，用于控制按钮输入的读取和去抖动，包括“短”和“长”按下回调.
* [micropython-debounce-switch](https://github.com/selfhostedhome/micropython-debounce-switch) - 用于去抖开关的 MicroPython 类.

#### IO-Expander

* [micropython-mcp230xx](https://github.com/ShrimpingIt/micropython-mcp230xx) - MCP23017 和 MCP23008 GPIO 扩展器的驱动程序.
* [micropython-mcp23017](https://github.com/mcauser/micropython-mcp23017) - 用于 MCP23017 16 位 I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8574](https://github.com/mcauser/micropython-pcf8574) - 用于带中断的 PCF8574 8 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8575](https://github.com/mcauser/micropython-pcf8575) - 用于带中断的 PCF8575 16 位 I2C I/O 扩展器的 MicroPython 驱动程序.

#### Joystick

* [micropython-nunchuck](https://github.com/kfricke/micropython-nunchuck) - Nunchuk 游戏控制器驱动程序，I2C 接口.

#### Keyboard

* [micropython-keyboard](https://github.com/mcameron/micropython-keyboard) - 在 MicroPython Pyboard 上运行的 47 键键盘.
* [pico-rgbkeypad](https://github.com/martinohanlon/pico-rgbkeypad) - 用于控制 Raspberry Pi Pico 的 Pimoroni RGB 键盘的 Python 类.
* [micropython-aiobutton](https://github.com/jacklinquan/micropython-aiobutton) - 用于异步按钮的 MicroPython 模块.

#### Potentiometers

* [micropython-ad840x](https://github.com/dsiggi/micropython-ad840x) - 基于 MicroPython SPI 的 AD 系列数字电位器 AD8400、AD8402 和 AD8403 操作.
* [mcp4131](https://github.com/scruss/mcp4131) - 用于控制 MicroChip 的 MCP4131 SPI 数字电位器的 MicroPython 模块.

#### Power Management

* [AXP202_PythonLibrary](https://github.com/lewisxhe/AXP202_PythonLibrary) - MicroPython AXP202 库.
* [micropython_hourly_sleeper_library](https://github.com/costastf/micropython_hourly_sleeper_library) - 一个 MicroPython 库，使 ESP8266 能够在设置的小时数内按小时增量休眠.

#### PWM

* [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) - 用于在异步循环中控制 PWM 输出的 MicroPython 库，具有包括淡入淡出和闪烁在内的功能.

#### Rotary Encoder

* [micropython-rotary](https://github.com/miketeachman/micropython-rotary) - 用于读取旋转编码器的 MicroPython 模块.
* [uencoder](https://gitlab.com/WiLED-Project/uencoder) - 用于从旋转编码器读取的 MicroPython 库.
* [encodermenu](https://github.com/sgall17a/encodermenu) - 使用旋转编码器和基本显示器的 MicroPython 简单 GUI 菜单.
* [encoderLib](https://github.com/BramRausch/encoderLib) - 处理旋转编码器的 MicroPython 库.
* [rotary-encoder](https://github.com/gurgleapps/rotary-encoder) - 用于驱动 KY-040 旋转编码器的 MicroPython 代码.
* [micropython-encoder-knob](https://github.com/infinite-tree/micropython-encoder-knob) - 一个非常简单的轻量级编码器旋钮库，支持按钮.
* [encoders](https://github.com/peterhinch/micropython-samples/blob/master/encoders/ENCODERS.md) - 解释有关编码器技术问题的简短文档.
* [asynchronous encoder driver](https://github.com/peterhinch/micropython-async/blob/master/v3/primitives/encoder.py) - 将编码器连接到 uasyncio 代码.

#### Shift Registers

* [micropython-74hc595](https://github.com/mcauser/micropython-74hc595) - 用于 74HC595 8 位移位寄存器的 MicroPython 驱动程序.
* [MicroPython-SN74HCS264](https://gitlab.com/olivierlenoir/MicroPython-SN74HCS264) - 用于具有施密特触发器输入和反相输出的 SN74HCS264 8 位并行输出串行移位寄存器的 MicroPython 驱动程序.

#### Waveform Generator

* [Micropython-AD9833](https://github.com/KipCrossing/Micropython-AD9833) - 用于 AD9833、SPI 接口的 Pyboard 驱动程序.
* [Clock_Generators](https://github.com/Wei1234c/Clock_Generators) - 时钟发生器（目前为 Si5351）工具箱.
* [Signal_Generators](https://github.com/Wei1234c/Signal_Generators) - 信号发生器（AD9833、AD9834、AD9850、ADF4351）工具箱.
* [ad9850_signalgen](https://github.com/brenn/ad9850_signalgen) - 用于 AD9850 合成器的 MicroPython 库.

### Motion

#### DC Motor

* [L298N](https://github.com/GuyCarver/MicroPython/blob/master/lib/L298N.py) - L298N 双 H 桥电机控制器的驱动程序.
* [MicroPython-L298](https://gitlab.com/olivierlenoir/MicroPython-L298) - 使用 MicroPython 驱动 L298 双 H 桥.

#### Servo

* [micropython-pca9685](https://github.com/mcauser/deshipu-micropython-pca9685) - 16-channel 12-bit PWM/servo driver.

#### Stepper

* [micropython-upybbot](https://github.com/jeffmer/micropython-upybbot) - 用于双极步进电机的 A4988 驱动器.
* [uln2003](https://github.com/IDWizard/uln2003) - Driver for 5V 28BYJ-48 stepper motors.
* [micropython-multiaxis](https://gitlab.com/olivierlenoir/micropython-multiaxis) - 带有 MicroPython ESP32 和 DRV8825 的多轴.
* [ticlib](https://github.com/jphalip/ticlib) - Pololu Tic 步进电机控制器的驱动程序.
* [AccelStepper-MicroPython](https://github.com/pedromneto97/AccelStepper-MicroPython) - 用于 MicroPython 的 AccelStepper 库 - ESP32.
* [pystepper](https://github.com/marcio-pessoa/pystepper) - MicroPython 步进电机顺序控制.
* [uPySteppers](https://github.com/lemariva/uPySteppers) - 使用连接到 WiFi 的 ESP32 DIY 旋转平台.
* [microPython_AMIS-30543](https://github.com/capella-ben/microPython_AMIS-30543) - 用于使用 AMIS-30543 驱动程序进行步进驱动程序控制的 MicroPython 库.

### Sensors

#### Accelerometer Digital

* [ADXL345-with-Pyboard](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) - ADXL345 16g 3 轴加速度计的驱动程序.
* [adxl345_micropython](https://github.com/fanday/adxl345_micropython) - ADXL345 16g 3 轴加速度计的驱动程序.
* [MicroPython-LIS3DH](https://github.com/tinypico/tinypico-micropython/tree/master/lis3dh%20library) - LIS3DH 3 轴加速度计的 I2C 驱动程序.
* [micropython-lis2hh12](https://github.com/tuupola/micropython-lis2hh12) - 用于 LIS2HH12 3 轴加速度计的 I2C 驱动程序.
* [MMA7660](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) - MMA7660 1.5g 3 轴加速度计的驱动程序.
* [ADXL345_spi_micropython](https://github.com/AlekseyFedorovich/ADXL345_spi_micropython) - 用于通过 SPI 协议与来自 MCU 的“Analog Devices ADXL345”加速度计进行交互的库，使用 MicroPython 进行闪存.

#### Air Quality

* [CCS811](https://github.com/Ledbelly2142/CCS811) - CCS811 空气质量传感器.
* [upython-aq-monitor](https://github.com/ayoy/upython-aq-monitor) - 使用 PMS5003 传感器和 WiPy 的空气质量监测器.
* [micropython-pms7003](https://github.com/pkucmus/micropython-pms7003) - PMS7003 空气质量传感器的 MicroPython 驱动程序.
* [pms5003_micropython](https://github.com/kevinkk525/pms5003_micropython) - 用于 MicroPython 的 PMS5003 空气质量传感器的驱动程序.
* [micropython-pms5003-minimal](https://github.com/miketeachman/micropython-pms5003-minimal) - 用于 MicroPython 的 P 空气质量传感器的驱动程序.
* [polly](https://github.com/g-sam/polly) - SDS011 污染传感器 + Wemos D1 mini pro + MicroPython.

#### Barometer

* [micropython-bme280](https://github.com/kevbu/micropython-bme280) - Bosch BME280 温度/压力/湿度传感器的驱动程序.
* [micropython-bmp180](https://github.com/micropython-IMU/micropython-bmp180) - 博世 BMP180 温度、压力和高度传感器的驱动程序.
* [mpy_bme280_esp8266](https://github.com/catdog2/mpy_bme280_esp8266) - 博世 BME280 温度/压力/湿度传感器.
* [BME280](https://github.com/robert-hh/BME280) - BME280 传感器的 MicroPython 驱动程序，目标平台 Pycom 设备.
* [micropython-bmp280](https://github.com/dafvid/micropython-bmp280) - BMP280 传感器模块.
* [micropython_bme280_i2c](https://github.com/triplepoint/micropython_bme280_i2c) - 用于与博世 BME280 温度、湿度和压力传感器通信的 MicroPython 模块.
* [MicroPython-BME280](https://github.com/neliogodoi/MicroPython-BME280) - 温度、压力和湿度数字传​​感器的驱动程序.
* [micropython-bmp180](https://gitlab.com/flowolf/micropython-bmp180) - 为 BMP180 压力传感器提供类的 MicroPython 模块.
* [BMP390](https://github.com/octaprog7/BMP390) - 用于 BMP390 压力和温度传感器的 MicroPython 模块.
* [BMP180](https://github.com/octaprog7/BMP180) - 用于 BMP180 压力和温度传感器的 MicroPython 模块.

#### Battery

* [Micropython-LC709203F](https://github.com/scopelemanuele/Micropython-LC709203F) - 用于 LC709293F 电量计的简单 MicroPython 库.

#### Biometric

* [micropython-fingerprint](https://github.com/chrisb2/micropython-fingerprint) - 用于读取 Grow 和 ZhianTec 指纹传感器的 MicroPython 库.
* [MAX30102-MicroPython-driver](https://github.com/n-elia/MAX30102-MicroPython-driver)  - 移植到 MicroPython 的 MAX30102 驱动程序. 它也适用于 MAX30105.

#### Camera

* [micropython-ov2640](https://github.com/namato/micropython-ov2640) - OV2640 相机的 MicroPython 类.
* [Nikon-Trigger-for-MicroPython](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython)  - 使用红外 LED 的尼康相机的远程触发器. 对于 Pyboard v1.1.
* [micropython-camera-driver](https://github.com/lemariva/micropython-camera-driver) - ESP32 上用于 MicroPython 的 OV2640 摄像头驱动程序.
* [esp32-cam-micropython](https://github.com/shariltumin/esp32-cam-micropython) - MicroPython ESP32-CAM.
* [uPyCam](https://github.com/lemariva/uPyCam) - 使用运行 MicroPython 的 ESP32-CAM 拍照.
* [OV2640_uPy](https://github.com/FunPythonEC/OV2640_uPy) - 用于 MicroPython 的 OV2640 相机库.
* [MQTT-Cam](https://github.com/jono-allen/MQTT-Cam) - ESP32-CAM MicroPython MQTT AWS S3 上传器.

#### Colour

* [micropython-tcs34725](https://gitlab.com/robhamerling/micropython-tcs34725) - TCS34725 和 TCS34727 颜色传感器的驱动程序类.

#### Compass

* [micropython-esp8266-hmc5883l](https://github.com/gvalkov/micropython-esp8266-hmc5883l) - ESP8266 上的 3 轴数字罗盘.
* [QMC5883](https://github.com/robert-hh/QMC5883) - QMC5883 三轴数字罗盘 IC 的 Python 类.
* [microPython_AS5600L](https://github.com/capella-ben/microPython_AS5600L) - 用于 AS5600L 磁体旋转位置传感器的 MicroPython 驱动程序.

#### Current

* [micropythonINA219](https://github.com/kabel42/micropythonINA219) - INA219 电流传感器的驱动程序.
* [pyb_ina219](https://github.com/chrisb2/pyb_ina219) - INA219 电流传感器的驱动程序.
* [INA219](https://github.com/robert-hh/INA219) - INA219 MicroPython 驱动程序.
* [TI_INA226_micropython](https://github.com/elschopi/TI_INA226_micropython) - 用于德州仪器 INA226 功率测量 IC 的 MicroPython 驱动程序.
* [micropython-current-monitor](https://gitlab.com/n.rj.powers/micropython-current-monitor) - 使用 INA219 和 SSD1306 OLED 的电流监视器.

#### Distance IR

* [micropython-gp2y0e03](https://github.com/mcauser/deshipu-micropython-gp2y0e03) - 使用夏普 GP2Y0E03 的 IR-LED 测距传感器.
* [micropython-vl6180](https://github.com/mcauser/deshipu-micropython-vl6180) - 飞行时间传感器、环境光传感器和红外发射器.

#### Distance Laser

* [micropython-vl53l0x](https://github.com/mcauser/deshipu-micropython-vl53l0x) - 飞行时间激光测距传感器.
* [Qwiic_TOF_Module_RFD77402](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) - Qwiic TOF 模块 (RFD77402) 飞行时间测距模块.
* [VL53L0X](https://github.com/uceeatz/VL53L0X) - 用于 LiDAR 传感器 VL53L0X 的 MicroPython 库.
* [vl53l1x_pico](https://github.com/drakxtwo/vl53l1x_pico) - VL53L1X ToF 传感器的 MicroPython 驱动程序.
* [tf-luna-micropython](https://github.com/davmoz/tf-luna-micropython) - 用于 TF-Luna LiDAR 模块的简单 MicroPython I2C 库.
* [vl53l5cx](https://github.com/mp-extras/vl53l5cx) - MicroPython 和 CircuitPython 包 [VL53L5CX](https://www.st.com/en/imaging-and-photonics-solutions/vl53l5cx.html) （4x4/8x8 ToF 传感器阵列）.

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) - HC-SR04 超声波距离传感器的驱动程序.
* [micropython-us100](https://github.com/kfricke/micropython-us100) - 用于 US-100 声纳距离传感器的 MicroPython 驱动程序.

#### Dust

* [pyGP2Y](https://github.com/amigcamel/pyGP2Y) - 用于夏普 GP2Y1014AU0F 灰尘传感器的 MicroPython 库.

#### Energy

* [ATM90E26_Micropython](https://github.com/whatnick/ATM90E26_Micropython) - ATM90E26电能计量设备的驱动程序.
* [MCP39F521](https://github.com/warpme/MCP39F521) - 用于读取 MCP39F521 电源监视器的 ESP8266 脚本.
* [micropython-p1meter](https://github.com/Josverl/micropython-p1meter) - 一个 ESP32 传感器，用于读取 p1 电表并将其发布到 MQTT 和 Home Assistant，用 MicroPython 编写.
* [esp32-solar2](https://github.com/octopusengine/esp32-solar2) - 简单的太阳能调节器 - MicroPython 项目.

#### Gaseous

* [micropython-MQ](https://github.com/kartun83/micropython-MQ) - MQ 系列气体传感器的驱动程序.
* [MQ135](https://github.com/rubfi/MQ135) - MQ135 气体传感器的驱动程序.
* [CCS811](https://github.com/Notthemarsian/CCS811) - ESP8266 板上 CCS811 的基本 MicroPython 驱动程序.
* [micropython-scd30](https://github.com/agners/micropython-scd30) - 用于 Sensirion SCD30 CO2 传感器模块的 MicroPython I2C 驱动程序.
* [micropython-sgp40](https://github.com/agners/micropython-sgp40) - 用于 SGP40 VOC 传感器模块的 MicroPython I2C 驱动程序.
* [MICS6814-Micropython-driver](https://gitlab.com/DanNduati/MICS6814-Micropython-driver) - 用于 Pimoroni MICS6814 分线板的 ESP32 MicroPython 驱动程序.

#### Light

* [MicroPython-SI1145](https://github.com/neliogodoi/MicroPython-SI1145) - SI1145 紫外线指数、红外线、可见光和接近传感器.
* [micropython-tsl2561](https://github.com/kfricke/micropython-tsl2561) - 来自 TAOS / ams 的 TSL2561 照明传感器的驱动程序.
* [mpy_bh1750fvi_esp8266](https://github.com/catdog2/mpy_bh1750fvi_esp8266) - 用于 BH1750FVI 传感器的 ESP8266 驱动程序.
* [bh1750](https://github.com/PinkInk/upylib/tree/master/bh1750) - BH1750 I2C 数字光传感器驱动器.
* [micropython-max44009](https://github.com/mcauser/micropython-max44009) - 用于 MAX44009 环境光传感器的 MicroPython 驱动程序.
* [veml7700](https://github.com/palouf34/veml7700) - 用于 VEML7700 光传感器的 MicroPython 库.
* [MicroPython_MAX44009_driver](https://github.com/rcolistete/MicroPython_MAX44009_driver) - MAX44009 光传感器的 MicroPython 驱动程序.

#### Motion Inertial

* [micropython-bmx055](https://github.com/micropython-IMU/micropython-bmx055) - 博世 BMX055 IMU 传感器的驱动程序.
* [micropython-bno055](https://github.com/deshipu/micropython-bno055) - Bosch Sensortec BNO055 9DOF IMU 传感器，I2C 接口.
* [micropython-lsm9ds0](https://github.com/micropython-IMU/micropython-lsm9ds0) - LSM9DS0 g-force 线性加速度、高斯磁力和 DPS 角速率传感器.
* [micropython-mpu9250](https://github.com/tuupola/micropython-mpu9250) - 用于 MPU9250 9 轴运动跟踪设备的 I2C 驱动程序.
* [micropython-mpu9x50](https://github.com/micropython-IMU/micropython-mpu9x50) - InvenSense MPU9250 惯性测量单元的驱动程序.
* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) - 用于 MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [py-mpu6050](https://github.com/larsks/py-mpu6050) - 用于 MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [micropython-mpu6886](https://github.com/tuupola/micropython-mpu6886) - 用于 MPU6886 6 轴运动跟踪设备的 MicroPython I2C 驱动程序.
* [micropython-fusion](https://github.com/micropython-IMU/micropython-fusion) - 传感器融合根据运动跟踪设备的输出计算航向、俯仰和滚动.
* [flight_controller](https://github.com/wagnerc4/flight_controller) - MicroPython 飞行控制器.
* [micropython-bno055](https://github.com/micropython-IMU/micropython-bno055)  - 用于 MicroPython 的 Bosch BNO055 驱动程序. 具有硬件传感器融合的 IMU.
* [micropython-mpu6050-mqtt-streamer](https://github.com/mozanunal/micropython-mpu6050-mqtt-streamer) - 在 ESP8266 上使用 MicroPython 将数据从 MPU6050 流式传输到 MQTT 服务器.
* [upy-motion](https://github.com/OneMadGypsy/upy-motion) - 用 MicroPython 编写的简单 MPU6050 驱动程序.
* [micropython-bno08x-rvc](https://github.com/rdagger/micropython-bno08x-rvc) - BNO08x 的 MicroPython 库.
* [micropython-mpu9250](https://gitlab.com/nnayo/micropython-mpu9250) - MicroPython MPU-9250 (MPU-6500 + AK8963) I2C 驱动程序.

#### Pressure

* [ms5803-micropython](https://github.com/minyiky/ms5803-micropython) - 用于 MS5803 压力和温度传感器的驱动程序的 MicroPython 实现.
* [MPL3115A2_MicroPython](https://github.com/PinsonJonas/MPL3115A2_MicroPython) - 用于 MPL3115A2 高度计的 MicroPython 库.

#### Proximity

* [uPy_APDS9960](https://github.com/rlangoy/uPy_APDS9960) - 使用 APDS9960 的 ESP8266 的 MicroPython 接近度库.

#### Radiation

* [micropython-geiger](https://github.com/Josep/micropython-geiger) - 带 MicroPython 卡的盖革计数器.
* [ESPGeiger](https://github.com/biemster/ESPGeiger) - 用于 ESP8266 盖革计数器的 MicroPython 库.

#### Soil Moisture

* [micropython-chirp](https://github.com/robberwick/micropython-chirp) - Chirp 土壤湿度传感器的驱动程序.
* [MicroPython-MiFlora](https://github.com/matthias-bs/MicroPython-MiFlora) - Xiaomi Mi Flora（又名花卉护理）BLE 植物传感器（土壤湿度/电导率/光照强度/温度）.

#### Spectral

* [AS726X_LoPy](https://github.com/jajberni/AS726X_LoPy) - 用于 AS726X 光谱传感器的 MicroPython 驱动程序.

#### Temperature Analog

* [micropython-max31855](https://github.com/mcauser/deshipu-micropython-max31855) - 热电偶放大器，SPI 接口.
* [max31856](https://github.com/alinbaltaru/max31856) - 具有线性化、SPI 接口的精密热电偶到数字转换器.
* [mcp9700](https://gitlab.com/CrispyCrafter/mcp9700) - 用于 MCP9700 的通用 MicroPython 驱动程序.

#### Temperature Digital

* [bme680-mqtt-micropython](https://github.com/robmarkcole/bme680-mqtt-micropython) - BME680 气体、压力、温度和湿度传感器的驱动程序.
* [LM75-MicroPython](https://github.com/OldhamMade/LM75-MicroPython) - LM75 数字温度传感器驱动程序，I2C 接口.
* [micropython-am2320](https://github.com/mcauser/micropython-am2320) - 奥松AM2320温湿度传感器，I2C接口.
* [micropython-dht12](https://github.com/mcauser/micropython-dht12) - 奥松DHT12温湿度传感器，I2C接口.
* [micropython-hdc1008](https://github.com/kfricke/micropython-hdc1008) - 德州仪器 HDC1008 湿度和温度传感器的驱动程序.
* [micropython-mcp9808](https://github.com/kfricke/micropython-mcp9808) - Microchip MCP9808 温度传感器的驱动程序.
* [micropython-mpl115a2](https://github.com/khoulihan/micropython-mpl115a2) - MPL115A2 大气压力传感器的 Pyboard 驱动程序.
* [micropython-sht30](https://github.com/rsc1975/micropython-sht30) - SHT30温湿度传感器驱动.
* [micropython-sht31](https://github.com/kfricke/micropython-sht31) - SHT31温湿度传感器的驱动程序.
* [micropython-Si7005](https://github.com/Smrtokvitek/micropython-Si7005) - Si7005 相对湿度和温度传感器的驱动程序.
* [micropython-si7021](https://github.com/mcauser/deshipu-micropython-si7021) - SI7021温湿度传感器，I2C接口.
* [micropython-si7021](https://github.com/chrisbalmer/micropython-si7021) - SI7021温湿度传感器，I2C接口.
* [micropython-Si705x](https://github.com/billyrayvalentine/micropython-Si705x) - Silicon Labs Si705x 系列温度传感器，I2C 接口.
* [micropython-Si70xx](https://github.com/billyrayvalentine/micropython-Si70xx) - Silicon Labs Si70xx 系列相对湿度和温度传感器，I2C 接口.
* [micropython-tmp102](https://github.com/khoulihan/micropython-tmp102) - TMP102 数字温度传感器的驱动程序.
* [Official DHT11+DHT12](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/sensor/dht) - DHT11和DHT12温湿度传感器的ESP8266驱动.
* [sht25-micropython](https://github.com/Miceuz/sht25-micropython) - SHT25温湿度传感器驱动.
* [micropython-tmp1075](https://github.com/mattytrentini/micropython-tmp1075) - TI TMP1075 温度传感器的驱动程序.
* [micropython-sht11](https://github.com/2black0/micropython-sht11) - Sensirion SHT11 温度和湿度传感器的驱动程序.
* [micropython-lm75a](https://github.com/mcauser/micropython-lm75a) - NXP LM75A 数字温度传感器的驱动程序.
* [BME680-Micropython](https://github.com/robert-hh/BME680-Micropython) - BME680 传感器的 MicroPython 驱动程序.
* [htu21d-esp8266](https://github.com/julianhille/htu21d-esp8266) - 这是一个 MicroPython 模块/类，用于测量来自 HTU21D 的数据.
* [HTU21D](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/HTU21D.md) - HTU21D温湿度传感器异步驱动.
* [esp-sht3x-micropython](https://github.com/HAIZAKURA/esp-sht3x-micropython) - 用于带有 MicroPython 的 ESP8266/ESP32 的 SHT3x (SHT30/31/35) 库.
* [sht25-micropython](https://gitlab.com/miceuz/sht25-micropython) - SHT25 湿度和温度传感器 API 的 MicroPython 实现.
* [micropython-sht30](https://github.com/schinckel/micropython-sht30) - 基于 I2C 总线的纯 Python 中的 SHT30 传感器驱动程序.
* [micropython_ahtx0](https://github.com/targetblank/micropython_ahtx0) - 用于 AHT10 和 AHT20 温度和湿度传感器的 MicroPython 驱动程序.
* [sht85](https://github.com/octaprog7/sht85) - MicroPython 驱动程序 [Sensiron SHT85](https://sensirion.com/products/catalog/SHT85/) 湿度和温度传感器.
* [micropython-zacwire](https://github.com/mdaeron/micropython-zacwire) - 用于 TSic 506F 温度传感器的 ZACwire 协议的 MicroPython 驱动程序.

#### Temperature IR

* [micropython-mlx90614](https://github.com/mcauser/micropython-mlx90614) - Melexis MLX90614 IR 温度传感器的驱动程序.

#### Touch Capacitive

* [micropython-mpr121](https://github.com/mcauser/micropython-mpr121) - MPR121 电容式触摸键盘和分线板的驱动程序.
* [micropython-ttp223](https://github.com/mcauser/micropython-ttp223) - 使用 TTP223 电容式触摸模块的示例.
* [micropython-TTP229-BSF](https://github.com/alankrantas/micropython-TTP229-BSF) - 用于串行接口模式下 TTP229-BSF 16 键电容式键盘的 MicroPython ESP8266/ESP32 驱动程序.
* [uFT6336U](https://github.com/fantasticdonkey/uFT6336U) - 用于 Focus LCD FT6336U 电容式触摸面板控制器 IC 的 MicroPython I2C 驱动程序.

#### Touch Resistive

* [XPT2046-touch-pad-driver](https://github.com/robert-hh/XPT2046-touch-pad-driver) - 许多 TFT 模块中使用的 XPT2046 触摸板控制器的驱动程序.

### Scheduling

* [micropython-mcron](https://github.com/fizista/micropython-mcron) - MicroCRON 是 MicroPython 的基于时间的任务调度程序.
* [micropython-scron](https://github.com/fizista/micropython-scron) - SimpleCRON 是一个基于时间的任务调度程序，其灵感来自于著名的 Unix 系统 cron 程序.
* [Schedule](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/SCHEDULE.md)  - 基于 uasyncio 的应用程序的调度程序. 在指定的时间和日期安排活动.
* [micropython-aioschedule](https://github.com/ThinkTransit/micropython-aioschedule) - 持久性 uasyncio 调度程序，支持任务运行之间的深度睡眠.

### Storage

#### Database

* [uPyMySQL](https://github.com/dvrhax/uPyMySQL) - 纯 MicroPython MySQL 客户端.
* [micropython-redis](https://github.com/dwighthubbard/micropython-redis) - 为与 MicroPython 一起使用而设计的 Redis 客户端实现.
* [picoredis](https://github.com/SpotlightKid/picoredis) - 用于 MicroPython 的非常小的 Redis 客户端（不仅）.
* [micropg](https://github.com/nakagami/micropg) - 用于 MicroPython 的 PostgreSQL 数据库驱动程序.
* [nmongo](https://github.com/nakagami/nmongo) - 用于 CPython 和 MicroPython 的 MongoDB 客户端，带有 MongoDB shell-like API.
* [MicroPyDatabase](https://github.com/sungkhum/MicroPyDatabase) - 用于 MicroPython 的基于 JSON 的低内存数据库.
* [micropython-firebase-realtime-database](https://github.com/ckoever/micropython-firebase-realtime-database) - 针对 ESP32 优化的 MicroPython 的 Firebase 实现.
* [micropython-firebase-firestore](https://github.com/WoolDoughnut310/micropython-firebase-firestore) - MicroPython 的 Firebase Firestore 实现.
* [uSQLite](https://github.com/spatialdude/usqlite) - 用于 MicroPython 的 SQLite 库模块.

#### EEPROM

* [micropython_eeprom](https://github.com/peterhinch/micropython_eeprom) - 用于存储芯片（EEPROM、FRAM、闪存、PSRAM）的跨平台 MicroPython 设备驱动程序.
* [mb_24x256_512](https://github.com/MarksBench/mb_24x256_512) - 用于 Microchip 24x256 和 24x512 I2C EEPROM 设备的非常简单的 MicroPython 模块/驱动程序.

#### Flash

* [micropython_data_to_py](https://github.com/peterhinch/micropython_data_to_py) - 一个 Python 3 实用程序，用于将任意二进制文件转换为 Python 源代码，以便在 Flash 中冻结为字节码.
* [micropython-winbond](https://github.com/brainelectronics/micropython-winbond) - 通过 SPI 与华邦 W25Q 闪存芯片交互.

#### FRAM

* [micropython-fram](https://github.com/rolandvs/micropython-fram) - 用于铁电 RAM 模块的 Pyboard 驱动程序.

#### PSRAM

* [mb_PSRAM_64Mb_SPI](https://github.com/MarksBench/mb_PSRAM_64Mb_SPI) - 非常简单的 MicroPython 模块，使用通用 64Mbit PSRAM（即 Adafruit 4677）和 Raspberry Pi Pico (RP2040).

#### SRAM

* [mb_23LC1024](https://github.com/MarksBench/mb_23LC1024) - 非常简单的 MicroPython 模块，使用带有 Raspberry Pi Pico (RP2040) 的 Microchip 23LC1024 SPI SRAM.
* [mb_47x16](https://github.com/MarksBench/mb_47x16) - 用于 Microchip 47x16 EERAM 设备 (47L/47C) 的非常简单的 MicroPython 模块/驱动程序.

### Threading

* [MicroWorkers](https://github.com/jczic/MicroWorkers) - 一个微型工人类，可轻松管理线程池以优化同步作业和作业结束，适用于 MicroPython（用于 Pycom 模块和 ESP32）.

### User Interface

* [upymenu](https://github.com/jplattel/upymenu) - 用于 LCD 显示器的 MicroPython 菜单.

## Community

* [MicroPython Discussions on GitHub](https://github.com/orgs/micropython/discussions) - 与 MicroPython 相关的所有事情的 GitHub 讨论.
* [MicroPython Forum (archive)](https://forum.micropython.org/) - 关于与 MicroPython 相关的所有事情的存档社区对话.
* [Discord](https://discord.com/invite/qw7d8bv) - 获得 MicroPython Discord 服务器的邀请.
* [MicroPython on Mastodon / Fediverse](https://fosstodon.org/@MicroPython) - 在 Fediverse 中关注 MicroPython.
* [MicroPython on Twitter](https://twitter.com/micropython) - 在 Twitter 上关注 MicroPython 以获取最新消息和更新.
* [MicroPython on Facebook](https://www.facebook.com/micropython) - 喜欢 Facebook 上的 MicroPython，了解比赛、新闻和更新.
* [Melbourne MicroPython Meetup](https://www.meetup.com/en-AU/MicroPython-Meetup) - 在澳大利亚墨尔本的 CCHS 定期聚会.

## Tutorials

* [uasyncio](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/TUTORIAL.md) - 编写与硬件设备接口的异步代码.
* [Asynchronous drivers](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/DRIVERS.md) - 开关、按钮、编码器和 ADC 异步接口的教程和代码.
* [Pyboard micropower](https://github.com/peterhinch/micropython-micropower) - Pyboard 1.x 和 Pyboard D 上低功耗应用的教程和代码.
* [3D rotation with quaternions](https://github.com/peterhinch/micropython-samples/blob/master/QUATERNIONS.md) - 进行 3D 旋转的简单方法的教程和代码.
* [Miguel Grinberg](https://blog.miguelgrinberg.com/category/MicroPython) - MicroPython 和物联网.
* [Bhavesh Kakwani](https://bhave.sh/) - MicroPython 视频 + 书面教程.
* [CoderDojo Twin Cities MicroPython](https://www.coderdojotc.org/micropython/) - 用于向儿童教授 MicroPython 的完整编码课程.
* [MicroPython Tutorials for ESP32 boards](https://www.upesy.com/blogs/tutorials/tutorials-for-esp32-with-micropython-code) - 带有代码示例的教程，用于学习使用 ESP32 板的 MicroPython 基础知识.
* [Learn MicroPython with a Pi Pico board](https://www.upesy.com/blogs/tutorials/tutorials-for-rpi-pi-pico-with-micropython-code) - 使用 Raspberry Pi Pico / RP240 开发板的 MicroPython 教程.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](https://www.oreilly.com/library/view/programming-with-micropython/9781491972724/)  - 尼古拉斯·H·托勒维 (Nicholas H. Tollervey). 国际标准书号 9781491972731.
* [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://link.springer.com/book/10.1007/978-1-4842-3123-4)  - 查尔斯·贝尔. 国际标准书号 9781484231227.
* [Beginning MicroPython with the Raspberry Pi Pico: Build Electronics and IoT Projects](https://link.springer.com/book/10.1007/978-1-4842-8135-2)  - 查尔斯·贝尔. 国际标准书号 9781484281345.
* [MicroPython Cookbook](https://www.packtpub.com/au/application-development/micropython-cookbook)  - Marwan Alsabbagh 着. 国际标准书号 9781838649951.
* [Python for Microcontrollers: Getting Started with MicroPython](https://www.mheducation.com.au/python-for-microcontrollers-getting-started-with-micropython-9781259644535-aus)  - 唐纳德诺里斯. 国际标准书号 9781259644535.
* [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937)  - 尤里玛格达. 国际标准书号 9781090900937.
* [MicroPython Projects](https://www.packtpub.com/au/iot-hardware/micropython-projects)  - 雅各布贝宁戈. 书号 9781789958034.
* [Get Started with MicroPython on Raspberry Pi Pico](https://store.rpipress.cc/products/get-started-with-micropython-on-raspberry-pi-pico)  - Gareth Halfacree 和 Ben Everard. 国际标准书号 9781912047864.
* [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book)  - 君特·斯潘纳 (Günter Spanner). 国际标准书号 9783895764370.
* [MicroPython for the Raspberry Pi Pico W: A gentle introduction to programming digital circuits with Python](https://www.amazon.com/MicroPython-Raspberry-Pico-introduction-programming/dp/B0BKSCV18D)  - 米格尔格林伯格. 国际标准书号 9798361302710.

## Frameworks

* [micrOS](https://github.com/BxNxM/micrOS) - 基于 MicroPython 的物联网框架.
* [terkin-datalogger](https://github.com/hiveeyes/terkin-datalogger) - 适用于 MicroPython 和 CPython 的灵活数据记录器应用程序.
* [perthensis](https://codeberg.org/scy/perthensis) - Perthensis：MicroPython 的异步框架.
* [meerkat](https://github.com/crdietrich/meerkat) - 用于 MicroPython 和 Raspberry Pi 的 I2C 数据采集.

## Resources

* [MicroPython](https://micropython.org)  - 项目网站. 试驾 Pyboard. 使用 Unicorn 在线试用 MicroPython.
* [MicroPython on GitHub](https://github.com/micropython/micropython) - 提交错误报告，关注并加入 GitHub 上的开发.
* [MicroPython Official Documentation](https://docs.micropython.org/) - 对于各种端口，包括快速参考、一般信息、示例和教程.
* [MicroPython Wiki](https://github.com/micropython/micropython/wiki) - 社区生成的文档以及 MicroPython 和 Pyboard 功能的示例.
* [MicroPython Newsletter](https://micropython.org/newsletter) - 订阅 MicroPython 时事通讯以获取新闻和公告，包括新功能和新产品.
* [MicroPython Store](https://store.micropython.org/) - 您可以在哪里购买 Pyboard、外壳、皮肤、书籍、连接器和外围设备.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) - 维基百科上的 MicroPython，免费的百科全书
* [awesome-micropythons](https://github.com/adafruit/awesome-micropythons) - MicroPython 的许多分支和端口.

## Development

### Code Generation

* [micropy-cli](https://github.com/BradenM/micropy-cli) - Micropy CLI 是一个项目管理/生成工具，用于在 Visual Studio Code 等现代 IDE 中编写 MicroPython 代码.
* [micropython-stubber](https://github.com/Josverl/micropython-stubber) - 为不同的 MicroPython 固件生成和使用存根，以与 Visual Studio Code 和/或 Pylint 一起使用.
* [micropy-stubs](https://github.com/BradenM/micropy-stubs) - 为 Micropy-Cli 和其他任何人自动生成的存根包.
* [micropython-extmod-generator](https://github.com/prusnak/micropython-extmod-generator) - 用 C 编写的 MicroPython 外部模块生成器.
* [micropython-package-template](https://github.com/brainelectronics/micropython-package-template) - GitHub 工作流支持 MicroPython 包模板并部署到 [Python Package Index](https://pypi.org/) 推送到主分支并测试部署到 [Test Python Package Index](https://test.pypi.org/) 在 PR 上.
* [micropython-usermod](https://micropython-usermod.readthedocs.io) - 关于用 C 编写的 MicroPython 外部模块的在线书籍.

### Debugging

* [esp32-backtrace](https://github.com/tve/esp32-backtrace) - ESP32 异常堆栈回溯分析器.
* [micropython-aiosentry](https://github.com/devbis/micropython-aiosentry) - MicroPython 的异步 Sentry.io 微型客户端.
* [micropython-usyslog](https://github.com/kfricke/micropython-usyslog) - 用于 MicroPython 的简单远程系统日志客户端.
* [Asynchronous monitor](https://github.com/peterhinch/micropython-monitor) - 使用 Raspberry Pico 和逻辑分析仪或示波器来监控异步代码.

### IDEs

* [BIPES](https://bipes.net.br/ide/)  - 基于 Web 的 MicroPython IDE，具有文件管理器、编辑器、块代码生成、IoT 仪表板和 Web 浏览器上的串行/USB/蓝牙/WebREPL 控制台. 来源： [https://github.com/BIPES](https://github.com/BIPES).
* [ESP32-MPY-Jama](https://github.com/jczic/ESP32-MPY-Jama) - 使用 MicroPython 管理 Espressif ESP32 微控制器的工具.
* [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) - IntelliJ 和 PyCharm 中的 MicroPython 设备插件.
* [MicroPython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) - 用于 Visual Studio Code 的 MicroPython IDE.
* [MicroPython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) - 与 MicroPython REPL 终端交互的便捷快捷方式.
* [Mu Editor](https://codewith.mu/) - 使用 Mu 编写代码：一个简单的 Python/MicroPython/CircuitPython 编辑器，适合初级程序员.
* [Thonny IDE](https://thonny.org/) - Thonny：适合初学者的 Python IDE.
* [Pyboard File Manager](https://github.com/joewez/PyboardFileManager) - Pyboard 文件管理器：Pyboard.py 兼容设备的 Windows GUI.

### Logging

* [micropython-ulogger](https://github.com/whales-chen/micropython-ulogger) - 为 MicroPython 定制的轻量级日志模块.

### Shells

#### On Device

* [upy-shell](https://github.com/dhylands/upy-shell) - 一个简单的基于命令行的 MicroPython shell.
* [Micropython-Editor](https://github.com/robert-hh/Micropython-Editor) - 用 Python 编写的用于 Pyboard、WiPy、ESP8266、ESP32、PyCom 和 Adafruit 设备的小型板载编辑器.

#### On Host

* [rshell](https://github.com/dhylands/rshell) - 将文件复制或同步到板，从您的终端输入 REPL.
* [ampy](https://github.com/scientifichackers/ampy) - 通过串行连接与 MicroPython 板交互的实用程序.
* [mpbridge](https://github.com/AmirHmZz/mpbridge) - 一个文件系统桥，用于同步和管理运行 MicroPython 的设备上的文件.
* [mpfshell](https://github.com/wendlers/mpfshell) - 一个简单的基于 shell 的文件浏览器，适用于 ESP8266 和 WiPy.
* [mpsync](https://github.com/thilomichael/mpsync) - 一种自动将代码同步到 MicroPython 板的工具.
* [mpremote](https://github.com/micropython/micropython/blob/master/tools/mpremote/README.md)  - 强大的官方shell，支持在目标上挂载主机的当前目录. 在不更改目标文件系统的情况下运行代码.

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 名支持者认捐了 97,803 英镑，以帮助实现该项目.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 名支持者认捐了 28,534 英镑，以帮助实现该项目.

## Contributing

随时欢迎贡献和建议！ 请看一下 [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) 第一的.

如果我不确定这些库是否很棒，我会保留一些拉取请求，您可以通过添加它们来投票给它们.
