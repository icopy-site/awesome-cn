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

A curated list of awesome MicroPython libraries, frameworks, software and resources.

[MicroPython](http://micropython.org/) is a lean and efficient implementation of the Python 3 programming language that includes a small subset of the Python standard library and is optimised to run on microcontrollers and in constrained environments.



## Libraries

您可以在其他地方查找 MicroPython 库：

* [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython)  - 此过滤器仅显示 PyPi 上的 MicroPython 库. 注意：您不能 pip 安装 micropython 库. 看 [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html?highlight=upip) 有关 upip 的更多信息.
* [GitHub Search](https://github.com/search?q=micropython) - 在 GitHub 上搜索包含 MicroPython 的存储库.
* [GitHub Topic - MicroPython](https://github.com/topics/micropython) - Browse GitHub Topics for projects tagged with MicroPython.
* [Libraries.io](https://libraries.io/search?q=micropython) - Libraries.io query for MicroPython.
* [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc&utf8=%E2%9C%93&name=micropython&sort=latest_activity_desc) - Explore repositories on GitLab.

### AI

* [MicroMLP](https://github.com/jczic/MicroMLP) - A micro neural network multilayer perceptron for MicroPython (used on ESP32 and Pycom modules).

### Analytics

* [uMath](https://github.com/AaronKel/uMath) - 微控制器的计算机代数.
* [micropython-ulab](https://github.com/v923z/micropython-ulab) - A numpy-like fast vector module for MicroPython.
* [micropython-fourier](https://github.com/peterhinch/micropython-fourier) - MicroPython 的内联 ARM 汇编器中的快速傅立叶变换.
* [Filters](https://github.com/peterhinch/micropython-filters) FIR filters using ARM Thumb assembler. Using an online utility you can go from a graph
滤波器实现所需的频率响应.
* [ulinalg](https://github.com/jalawson/ulinalg) - Small size matrix handling module with a few linear algebra operations specifically for MicroPython (Python3).
* [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) - MicroPython 上的快速矩阵乘法和线性求解器.
* [micropython-vec](https://gitlab.com/nickoala/micropython-vec) - Vector Operations on MicroPython.
* [MicroPython_Statistics](https://github.com/rcolistete/MicroPython_Statistics) - MicroPython 的统计模块.

### Audio

* [micropython-jq6500](https://github.com/rdagger/micropython-jq6500) - JQ6500 UART MP3 模块的驱动程序.
* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) - Driver for KT403A, used by DFPlayer Mini and Grove MP3 v2.0.
* [micropython-buzzer](https://github.com/fruch/micropython-buzzer) - Play Nokia compose and mid files on buzzers.
* [micropython-dfplayer](https://github.com/ShrimpingIt/micropython-dfplayer) - 使用 UART 的 DFPlayer Mini 驱动程序.
* [micropython-longwave](https://github.com/MattMatic/micropython-longwave) - WAV player for MicroPython board.
* [micropython-vs1053](https://github.com/peterhinch/micropython-vs1053) - VS1053b MP3 播放器的异步驱动程序.
* [micropython-midi](https://github.com/cjbarnes18/micropython-midi) - MicroPython 的 midi 实现示例.
* [upy-rtttl](https://github.com/dhylands/upy-rtttl) - Python Parser for Ring Tone Text Transfer Language (RTTTL).
* [micropython-i2s-examples](https://github.com/miketeachman/micropython-i2s-examples) - Examples for I2S support on microcontrollers that run MicroPython.
* [micropython-osc](https://github.com/SpotlightKid/micropython-osc) - MicroPython 的最小 OSC 客户端和服务器库.

### Communications

#### APIs

* [micropython-utelegram](https://github.com/jordiprats/micropython-utelegram) - Telegram API wrapper for MicroPython.
* [uEagle](https://github.com/jcalbert/uEagle) - MicroPython Rainforest EAGLE 客户端.
* [micropython-youtube-api](https://github.com/UnexpectedMaker/micropython-youtube-api) - MicroPython 中的 YouTube API.
* [micropython_esp8266_tweetbot](https://github.com/ayoko/micropython_esp8266_tweetbot) - MicroPython v1.8.4 (ESP8266) 的推特机器人.
* [telegram-upy](https://github.com/gabrielebarola/telegram-upy) - Telegram API wrapper for MicroPython.
* [micropython-thingspeak](https://github.com/radeklat/micropython-thingspeak) - 用于从运行 MicroPython 的物联网设备（例如 ESP8266）向 thingspeak.com 发送数据的库.
* [micropython_pushbullet](https://github.com/gsampallo/micropython_pushbullet) - 如何在 ESP8266 上使用 PushBullet 和 MicroPython 的简单示例.
* [esp32-youtube-display](https://github.com/alvarowolfx/esp32-youtube-display) - 使用 Google API 和 MicroPython 显示 YouTube 指标.
* [micropython-spotify-web-api](https://github.com/tltx/micropython-spotify-web-api) - 一个库，用于通过 MicroPython 从 IoT 设备使用 Spotify 的 Web API.

#### Bluetooth

* [PyBoard-HC05-Android](https://github.com/KipCrossing/PyBoard-HC05-Android) - Pyboard HC05 蓝牙适配器示例应用程序.
* [uble](https://github.com/dmazzella/uble) - 用纯 Python 为 MicroPython 编写的轻量级蓝牙低功耗驱动程序.
* [MicroPythonBLEHID](https://github.com/Heerkog/MicroPythonBLEHID) - 用于 MicroPython 的基于蓝牙低功耗 (BLE) GATT 库的人机接口设备 (HID).
* [upyble](https://github.com/Carglglz/upyble) - 用于蓝牙低功耗 MicroPython 设备的命令行工具.
* [micropython-xiaomi-ble-adv-parse](https://codeberg.org/scy/micropython-xiaomi-ble-adv-parse) - Passively retrieve sensor data from some Xiaomi Bluetooth Low Energy (BLE) sensors.
* [mijia-temphum-upy](https://codeberg.org/scy/mijia-temphum-upy) - MicroPython library to read certain Xiaomi Mijia BLE temperature & humidity sensors.

#### CAN

* [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) - Spacecan 是用于嵌入式系统的 SpaceCAN 协议的 MicroPython 实现.
* [Robomaster-Micropython](https://github.com/JohnieBraaf/Robomaster-Micropython) - Robomaster S1 - MicroPython CAN BUS controller.
* [micropython-mcp2515](https://github.com/jxltom/micropython-mcp2515) - MicroPython MCP2515 驱动程序，从 Arduino MCP2515 CAN 接口库移植.

#### Compression

* [ufastlz](https://github.com/dmazzella/ufastlz) - MicroPython wrapper for FastLZ, a lightning-fast lossless compression library.

#### Cryptography

* [mpyaes](https://github.com/iyassou/mpyaes) - 用于 AES 加密的 MicroPython 模块.
* [micropython-aes](https://github.com/piaca/micropython-aes) - 具有纯 python 实现的 AES 算法.
* [ucrypto](https://github.com/dmazzella/ucrypto)  - 用于进行快速椭圆曲线加密的 MicroPython 包，特别是数字签名.  API 设计灵感来自 fastecdsa 和基于 tomsfastmath 的实现.
* [ucryptoauthlib](https://github.com/dmazzella/ucryptoauthlib) - Lightweight driver for Microchip Crypto Authentication secure elements written in pure python for MicroPython.
* [embit](https://github.com/diybitcoinhardware/embit) - MicroPython 和 Python3 的最小比特币库，专注于嵌入式系统.
* [microotp](https://github.com/gdassori/microotp) - ESP8266 MicroPython OTP 生成器.
* [micropython-rsa-signing](https://github.com/artem-smotrakov/micropython-rsa-signing) - 在 MicroPython 上进行 RSA 签名.
* [micropython-cryptomsg](https://github.com/jacklinquan/micropython-cryptomsg) - A MicroPython module to encrypt and decrypt messages with AES CBC mode.

#### DNS

* [ICantBelieveItsNotDNS](https://github.com/yschaeff/ICantBelieveItsNotDNS) - "I Can't Believe It's Not DNS!" (ICBIND) is an authoritative DNS server for the ESP8266 written in MicroPython.
* [MicroDNSSrv](https://github.com/jczic/MicroDNSSrv) - MicroPython 的微型 DNS 服务器，用于简单地响应带有或不带有通配符的多域上的 A 查询（用于 Pycom 模块和 ESP32）.
* [tinydns](https://github.com/belyalov/tinydns) - 用于 MicroPython 的非常简单的 DNS 异步服务器.
* [micropython-captiveportal](https://github.com/metachris/micropython-captiveportal) - MicroPython 的最小异步强制门户（与 uasyncio v3/MicroPython 1.13+ 以及早期版本兼容）.
* [Micropython-DNSServer-Captive-Portal](https://github.com/p-doyle/Micropython-DNSServer-Captive-Portal) - MicroPython WiFi AP Captive Portal with DNS and Web Server.

#### Ethernet

* [Official wiznet5k](https://github.com/micropython/micropython/tree/master/drivers/wiznet5k) - Official driver for the WIZnet5x00 series of Ethernet controllers.
* [micropy-ENC28J60](https://github.com/przemobe/micropy-ENC28J60) - 用于 MicroPython (RP2) 的 ENC28J60 以太网芯片驱动程序.
* [RP2040 Ethernet example](https://github.com/SteveSEK/Raspberry-Pi-Pico-MicroPython-Ethernet) - 以太网驱动程序、python 代码示例和 YouTube.

#### FTP

* [micropython-ftplib](https://github.com/SpotlightKid/micropython-ftplib) - MicroPython 的 FTP 客户端库.
* [FTP-Server-for-ESP8266-ESP32-and-PYBD](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) - Small FTP server for ESP8266/ESP32/PYBD on the MicroPython platform.
* [MicroFTPServer](https://github.com/cpopp/MicroFTPServer) - 可以在带有 MicroPython 的 ESP8266 上运行的最小 FTP 服务器.
* [micropython-uaioftp](https://github.com/cwyark/micropython-uaioftp) - MicroPython 的轻量级 FTP 库.

#### GPS

* [micropyGPS](https://github.com/inmcm/micropyGPS) - Full featured GPS NMEA sentence parser.
* [micropython-gnssl76l](https://github.com/tuupola/micropython-gnssl76l) - 适用于 Quectel GNSS L76-L (GPS) 的 MicroPython I2C 驱动程序.
* [mpy-agps](https://github.com/pulkin/mpy-agps) - 辅助定位服务 (AGPS) 的 MicroPython 实现.
* [Asynchronous GPS driver](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/GPS.md) 接收和解析 GPS 数据作为 uasyncio 任务.

#### GSM

* [micropython-upyphone](https://github.com/jeffmer/micropython-upyphone) - 使用 pyboard 和 sim800l 的 gsm 手机.
* [micropython-sim800](https://github.com/olablt/micropython-sim800) - 用于 sim800 的 MicroPython 驱动程序.
* [sim800](https://github.com/basanovase/sim800) - 用于与 MicroPython 中的 SIM800 模块接口的库.
* [MicroPython-AM7020](https://github.com/JiekangHuang/MicroPython-AM7020) - AM7020 窄带物联网 (NBIoT) 模块的 MicroPython 驱动程序.

#### IoT

* [microhomie](https://github.com/microhomie/microhomie) - 物联网的 Homie MQTT 约定的 MicroPython 实现.
* [uPyEcho](https://github.com/lemariva/uPyEcho) - Emulated Belkin WeMo device that works with Amazon Echo (Alexa) using MicroPython on an ESP32.
* [SonosRemote](https://github.com/foosel/SonosRemote) - 在 ESP8266 上运行并使用 Sonos HTTP API 的 Sonos 安装遥控器.
* [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) - 基于 MicroPython 的脚本可扩展您的家庭助理驱动的家庭自动化项目.
* [micropython-iot](https://github.com/peterhinch/micropython-iot) - 一种使用 ESP8266、ESP32 或 Pyboard D 端点设计 IOT 应用程序的方法.
* [iot-core-micropython](https://github.com/GoogleCloudPlatform/iot-core-micropython) - 使用 MicroPython 连接到 Google Cloud IoT Core.
* [SmartUPy](https://github.com/lemariva/SmartUPy) - Controlling "Tuya-type" smart power outlets using MicroPython.
* [aws-iot-GET-POST-loop](https://github.com/manningt/aws-iot-GET-POST-loop) - 使用 AWS-IOT REST API 获取/发布设备状态信息的 MicroPython 代码.
* [sensor-mqtt-homeassistant](https://github.com/DougWilkinson/sensor-mqtt-homeassistant)  - 一个基于 esp8266/32 MicroPython 的传感器平台，用于 gpio、dht、模拟、led 等. 包括来自 Web 服务器和 MQTT/Homeassistant 集成的 .py 代码远程更新.

#### IR

* [micropython-necir](https://github.com/MattMatic/micropython-necir) - 用于 TL1838 IR 接收器 LED 的 NEC 红外捕获.
* [Micropython-IR](https://github.com/designerPing/Micropython-IR) - Pyboard 红外遥控嗅探和回放.
* [micropython_ir](https://github.com/peterhinch/micropython_ir) - Nonblocking device drivers to receive from IR remotes and for IR "blaster" apps.
* [micropython-amg88xx](https://github.com/peterhinch/micropython-amg88xx) - Driver for Grid-EYE thermal infra red array sensor (Adafruit 3538).
* [micropython-ys-irtm](https://github.com/mcauser/micropython-ys-irtm) - YS-IRTM 5V NEC 红外 UART 收发器的 MicroPython 示例.
* [esp8266_ir](https://github.com/ruoyu0088/esp8266_ir) - 通过 websocket 控制 IR 信号.
* [micropython_espX_IR_Transceiver](https://github.com/gamefunc/micropython_espX_IR_Transceiver) - MicroPython esp32 IR 收发器.
* [pico-ir](https://github.com/bartoszadamczyk/pico-ir) - 用于 Raspberry Pi Pico 的 IR 库.

#### LoRaWAN

* [uPyLoRaWAN](https://github.com/lemariva/uPyLoRaWAN) - ESP32 using MicroPython meets LoRa and LoRaWAN.
* [SX127x_driver_for_MicroPython_on_ESP8266](https://github.com/Wei1234c/SX127x_driver_for_MicroPython_on_ESP8266) - SX127x (LoRa transceiver) driver for (Micro)Python on ESP8266/ESP32/Raspberry_Pi.
* [LightLora_MicroPython](https://github.com/MZachmann/LightLora_MicroPython) - 用于 MicroPython 的轻量级中断驱动的 Semtech SX127x 库.
* [u-lora](https://github.com/martynwheeler/u-lora) - 用于 MicroPython 的 Raspi-lora.
* [sx127x_esp](https://github.com/azorg/sx127x_esp) - Connect Ra-01 module base on LoRaTM sx127x chip to ESP8266/ESP32 under MicroPython.
* [nanoserver](https://github.com/gradoj/nanoserver) - MicroPython embedded LoRaWAN server.
* [micropySX126X](https://github.com/ehong-tl/micropySX126X) - 用于 MicroPython 和 CircuitPython 的 Semtech SX126X LoRa 驱动程序.

#### MDNS

* [micropython-mdns](https://github.com/cbrand/micropython-mdns) - A pure python implementation of MDNS with support for Service Discovery.

#### Modbus

* [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) - modbus-tk 的 MicroPython 端口.
* [micropython-modbus](https://github.com/techbase123/micropython-modbus) - Modbus Master library for MicroPython ESP32 devices. Based on pycom-modbus from pycom.
* [mp_modbus](https://github.com/eydam-prototyping/mp_modbus) - Modbus Lib for MicroPython.

#### MQTT

* [micropython-mqtt](https://github.com/peterhinch/micropython-mqtt)  - “弹性”异步 MQTT 驱动程序. 加上使用 ESP8266 将 MQTT 带到非网络目标的方法.
* [MQBoard](https://github.com/tve/mqboard) - A micro-framework for using MQTT with asyncio on MicroPython boards, primarily on the ESP32.
* [pysmartnode](https://github.com/kevinkk525/pysmartnode) -  MicroPython Smarthome framework.
* [umqtt_aws_iot](https://github.com/juwul/umqtt_aws_iot) - 使用 MicroPython 将 UMQTT 消息发布到 AWS IoT.
* [sonoff-mqtt by davea](https://github.com/davea/sonoff-mqtt) - MicroPython scripts to control Sonoff/ESP8266 using MQTT.
* [micropython-sonoff-switch](https://github.com/kfricke/micropython-sonoff-switch) - Implements a MQTT controllable switch for the iTead Sonoff Switch using MicroPython.
* [micropython-thingspeak-mqtt-esp8266](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) - 使用 MQTT 和在 ESP8266/ESP32 平台上运行的 MicroPython 发布和订阅 Thingspeak.
* [uMQTT](https://github.com/andrewmk/uMQTT) - 在 WiPy 板上为 MicroPython 发布 MQTT.
* [micropython-mqtt](https://github.com/chrismoorhouse/micropython-mqtt) - 异步 MQTT 库，可自动重新连接 MicroPython 设备，例如 ESP32 或 Pycom 设备。
* [micropython-adafruit-mqtt-esp8266](https://github.com/miketeachman/micropython-adafruit-mqtt-esp8266) - Using MQTT to Publish/Subscribe to adafruit io. MicroPython/CircuitPython implementation on ESP8266/ESP32.
* [MicropythonCayenneMQTTClient](https://github.com/uraich/MicropythonCayenneMQTTClient) - 将 Python Cayenne MQTT 客户端移植到 MicroPython.
* [mqtt_upython](https://github.com/matbgn/mqtt_upython) - 在 ESP8266 上使用 MicroPython 的 MQTT 客户端.

#### NFC

* [micropython-nfc](https://github.com/rolandvs/micropython-nfc) - 将 NFC 与 MicroPython 结合使用.
* [NFC_PN532_SPI](https://github.com/Carglglz/NFC_PN532_SPI) - Partial Port of Adafruit CircuitPython to MicroPython of PN532 NFC/RFID control library (SPI).

#### NTP

* [esp8266_ntp_webserver](https://github.com/Roterfux/esp8266_ntp_webserver) - MicroPython + esp8266 + ntp + 网络服务器.
* [micropython-ntpd](https://github.com/dave2/micropython-ntpd) - MicroPython 中 ntpd 的实现.
* [micropython_ntpserver](https://github.com/GrantGMiller/micropython_ntpserver) - 为 MicroPython 编写的 NTP 服务器.
* [micropython-ntpclient](https://github.com/wieck/micropython-ntpclient) - NTP client for MicroPython using uasyncio.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython/tree/master/drivers/onewire) - 对于使用 OneWire 总线的设备，例如 Dallas ds18x20.
* [Onewire_DS18X20](https://github.com/robert-hh/Onewire_DS18X20) - 使用 Pycom MicroPython 的单线协议驱动 DS18x20 传感器的类.

#### Onkyo EISCP

* [eiscp-micropython](https://github.com/cbrand/eiscp-micropython) - Pioneer 使用的 Onkyo-EISCP 协议的 MicroPython 端口.

#### OTA

* [micropython-ota-updater](https://github.com/rdehuyss/micropython-ota-updater) - MicroPython 的 OTA 更新程序.
* [Micropython-ESP32-OTA](https://github.com/AkhileshThorat/Micropython-ESP32-OTA) - MicroPython updater based on rdehuyss/micropython-ota-updater.
* [senko](https://github.com/RangerDigital/senko) - 适用于您的 MicroPython 项目的最简单的 OTA 更新解决方案.

#### Radio

* [micropython-radio](https://github.com/peterhinch/micropython-radio) - nRF24L01 2.4Ghz 无线电模块的协议.
* [micropython-rfsocket](https://github.com/wuub/micropython-rfsocket) - 流行的基于 433MHzn 的 RFSocket 的 MicroPython 实现.
* [Official nRF24L01](https://github.com/micropython/micropython/tree/master/drivers/nrf24l01) - Official driver for nRF24L01 2.4Ghz radio modules.
* [micropython_remote](https://github.com/peterhinch/micropython_remote) - Capture and replay 433MHz remote control codes. Control remote switched power adaptors.
* [micropython-ys-rf34t](https://github.com/mcauser/micropython-ys-rf34t) - 使用 YS-RF34T 433MHz ASK/OOK UART 收发器的 MicroPython 示例.
* [FM_Talkie](https://github.com/Wei1234c/FM_Talkie) - 使用 RDA5820N 的 FM 对讲机.
* [micropython-TEA5767](https://github.com/alankrantas/micropython-TEA5767) - MicroPython ESP8266/ESP32 driver for TEA5767 FM radio module.
* [micropython-ppm-decoder](https://github.com/dastultz/micropython-ppm-decoder) - 用于解码 R/C 接收器 PPM 帧信号的实用程序.
* [ESP32-433Mhz-Receiver-and-Tools](https://github.com/Aschhoff/ESP32-433Mhz-Receiver-and-Tools) - 用 MicroPython 和 Windows 工具编写的 ESP32 433Mhz 接收器.

#### REPL

* [webrepl](https://micropython.org/webrepl) - MicroPython WebREPL.
* [zepl](https://gitlab.com/zepl1/zepl) - 使用 ZeroMQ 的 MicroPython WebREPL 控制台应用程序.
* [jupyter_micropython_remote](https://gitlab.com/alelec/jupyter_micropython_remote) - Jupyter 内核通过串行/网络 REPL 直接在 MicroPython 板上执行代码.
* [FBConsole](https://github.com/boochow/FBConsole) - MicroPython 的帧缓冲控制台类.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) - Driver for NXP MFRC522 RFID reader/writer.
* [micropython-wiegand](https://github.com/pjz/micropython-wiegand) - 韦根协议阅读器.
* [urdm6300](https://github.com/membermatters/urdm6300) - 流行的 RDM6300 RFID 读卡器的 MicroPython 驱动程序.

#### RTC

* [micropython-tinyrtc-i2c](https://github.com/mcauser/micropython-tinyrtc-i2c) - DS1307 RTC 和 AT24C32N EEPROM 的驱动程序.
* [Micropython_TinyRTC](https://github.com/AnthonyKNorman/Micropython_TinyRTC) - DS1307 RTC 驱动程序.
* [micropython-mcp7940](https://github.com/mattytrentini/micropython-mcp7940) - Driver for the Microchip MCP7940 RTC.
* [micropython-ds1302-rtc](https://github.com/omarbenhamid/micropython-ds1302-rtc) - 用于 MicroPython 的 DS1302 RTC 时钟驱动程序.
* [DS3231micro](https://github.com/notUnique/DS3231micro) - DS3231 的 MicroPython 库.

#### Serial

* [mpy-miniterm](https://github.com/jeffmakes/mpy-miniterm) - 通过串行 REPL 与 MicroPython 设备进行无缝串行调试和文件同步的工具.
* [MicroPython-MorseCode](https://gitlab.com/olivierlenoir/MicroPython-MorseCode) - 使用带有 MicroPython 的微控制器的国际摩尔斯电码.
* [I2C Slave](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/I2C.md) - Uses the Pyboard's I2C slave mode to implement a full duplex asynchronous link. Principal use case is for ESP8266 which has only one UART.  

#### Serialization

* [micropython-msgpack](https://github.com/peterhinch/micropython-msgpack) - MessagePack serialisation library optimised for MicroPython.
* [micropython-uprotobuf](https://github.com/jazzycamel/micropython-uprotobuf) - A lightweight implementation of Google's Protocol Buffers (protobuf) for MicroPython.
* [minipb](https://github.com/dogtopus/minipb) - Mini Protobuf {de}serializer in pure Python.

#### SOCKS

* [micropython-socks](https://github.com/kost/micropython-socks) - MicroPython library implementing SOCKS server.

#### SMTP

* [uMail](https://github.com/shawwwn/uMail) - 一个轻量级、可扩展的 SMTP 客户端，用于在 MicroPython 中发送电子邮件.

#### TCP

* [us2n](https://github.com/tiagocoutinho/us2n) - 用于 ESP32 的 UART 和 TCP 之间的 MicroPython 桥接器.

#### Telnet

* [MicroTelnetServer](https://github.com/cpopp/MicroTelnetServer) - Simple telnet server for MicroPython and the ESP8266 allowing telnet clients access to the REPL.

#### VoIP

* [uPyVoip](https://github.com/RetepRelleum/uPyVoip) - 带有交互式语音响应的 MicroPython ESP32 的 Voip.

#### WiFi

* [HueBridge](https://github.com/FRC4564/HueBridge) - Philips Hue Bridge.
* [micropython-wifimanager](https://github.com/mitchins/micropython-wifimanager) - A simple network configuration utility for MicroPython on the ESP8266 board.
* [WiFiManager](https://github.com/tayfunulu/WiFiManager) - ESP8266 的 WiFi 管理器 - ESP12 - ESP32 - MicroPython.

#### Web

* [MicroWebSrv](https://github.com/jczic/MicroWebSrv) - A micro HTTP Web server that supports WebSockets, html/python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - The last Micro Web Server for IoTs (MicroPython) or large servers (CPython), that supports WebSockets, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
* [tinyweb](https://github.com/belyalov/tinyweb) - Simple and lightweight HTTP async server for MicroPython.
* [upy-websocket-server](https://github.com/BetaRavener/upy-websocket-server) - MicroPython (ESP8266) websocket 服务器实现.
* [micropython-captive-portal](https://github.com/amora-labs/micropython-captive-portal) - A captive portal demo for MicroPython.
* [uPyPortal](https://github.com/lemariva/uPyPortal) - A captive portal for MicroPython using ESP32 (WeMos).
* [ESP8266WebServer](https://github.com/codemee/ESP8266WebServer) - 用于 MicroPython 的 ESP8266 网络服务器.
* [microCoAPy](https://github.com/insighio/microCoAPy) - 在 MicroPython 中实现 CoAP（受限应用协议）的迷你客户端/服务器.
* [micropyserver](https://github.com/troublegum/micropyserver) - MicroPyServer is a simple HTTP server for MicroPython projects.
* [MicroRESTCli](https://github.com/jczic/MicroRESTCli) - A micro JSON REST Web client based on MicroWebCli for MicroPython (used on Pycom modules & ESP32).
* [micropython-noggin](https://github.com/larsks/micropython-noggin) - 一个非常简单的 MicroPython Web 服务器.
* [uwebsockets](https://github.com/danni/uwebsockets) - MicroPython websockets implementation for ESP8266.
* [microdot](https://github.com/miguelgrinberg/microdot) - MicroPython 的小得不可思议的 Web 框架.
* [micropython-nanoweb](https://github.com/hugokernel/micropython-nanoweb) - 完全异步 MicroPython Web 服务器，内存占用小.
* [MicroWebCli](https://github.com/jczic/MicroWebCli) - MicroPython 的微型 HTTP Web 客户端（用于 Pycom 模块和 ESP32）.
* [micropython-configserver](https://github.com/carstenblt/micropython-configserver) - MicroPython 的强制门户，包括一个哑 DNS 服务器和一个用于配置 wifi 网络的网络服务器.
* [micropython-aioweb](https://github.com/wybiral/micropython-aioweb) - MicroPython 的极简 asyncio Web 框架.

#### Zigbee

* [ZbPy](https://github.com/osresearch/ZbPy) - MicroPython IEEE802.15.4 / Zigbee 解析器.

### Display

#### E-Paper

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - SSD1606 active matrix epaper display 128x180.
* [micropython-waveshare-epaper](https://github.com/mcauser/micropython-waveshare-epaper) - 各种 Waveshare 电子纸模块的驱动程序.
* [micropython-waveshare-epd](https://github.com/ayoy/micropython-waveshare-epd) - Waveshare E-Paper Display driver for devices running Pycom-flavored MicroPython.
* [ssd1675a](https://github.com/mattytrentini/ssd1675a) - 基于 SSD1675 的电子纸显示器的驱动程序.
* [Inkplate-micropython](https://github.com/e-radionicacom/Inkplate-micropython) - MicroPython driver for Inkplate boards.
* [micropython-inkplate6](https://github.com/tve/micropython-inkplate6) - MicroPython driver for the Inkplate 6.
* [eInk-micropython](https://github.com/dhallgb/eInk-micropython) - E-Ink library for Waveshare 4.3inch device on MicroPython.
* [eink](https://github.com/chevdor/eink) - 用于 MicroPython 和 ESP32 的 E-Ink、E-Paper 显示驱动程序.
* [micropython_DEPG0213BN](https://github.com/Inqbus/micropython_DEPG0213BN) - 用于 TTGO T5 V2.3 ESP32 板上的 DEPG0213BN 电子墨水显示器的纯 MicroPython 驱动程序.

#### Fonts

* [micropython-font-to-py](https://github.com/peterhinch/micropython-font-to-py) - 一个 Python 3 实用程序，用于将字体转换为能够被冻结为字节码的 Python 源代码.
* [writer](https://github.com/peterhinch/micropython-font-to-py/blob/master/writer/WRITER.md) 一种将 Python 字体渲染到显示其驱动程序是从 `framebuf` 子类化的显示器的简单方法.
* [ssd1306big](https://github.com/nickpmulder/ssd1306big) - 128x64 像素 ssd1306 oled 显示器上的 MicroPython 字体.

#### Graphics

* [micropython-stage](https://github.com/python-ugame/micropython-stage) - Stage 游戏库的 MicroPython 端口.
* [micropython-png](https://github.com/Ratfink/micropython-png) - 用于 MicroPython 的 PyPNG 的衍生物.
* [mpy-img-decoder](https://github.com/remixer-dec/mpy-img-decoder) - PNG and JPEG decoder / parser / renderer in pure MicroPython.
* [micropython-oled-progressbars](https://github.com/follower46/micropython-oled-progressbars) - A collection of progress bars for use with esp8266 and esp32's on OLED displays.
* [microplot](https://github.com/romilly/microplot) - 简单的 MicroPython 绘图包.

#### GUI

* [lvgl](https://github.com/lvgl/lv_binding_micropython) - 基于 MicroPython 绑定的面向对象组件的高级 GUI 库.
* [micropython-lcd160cr-gui](https://github.com/peterhinch/micropython-lcd160cr-gui) - Simple touch driven event based GUI for the Pyboard and LCD160CR colour display.
* [micropython_ra8875](https://github.com/peterhinch/micropython_ra8875) - 用于基于 RA8875 的显示器的 MicroPython 设备驱动程序和 nano-GUI.
* [micropython-nano-gui](https://github.com/peterhinch/micropython-nano-gui)  - 一个小型的仅显示 GUI，具有一组有限的 GUI 对象（小部件），用于显示驱动程序是 framebuf 类的子类的显示器. 带有用于 TFT、ePaper 和 OLED 显示器的驱动程序.
* [micro-gui](https://github.com/peterhinch/micropython-micro-gui) Derived from nano-gui and supporting the same displays and hosts, this provides for user
input via pushbuttons or a navigation joystick and an optional rotary encoder.
* [TFT-GUI](https://github.com/peterhinch/micropython-tft-gui) A fast touch GUI for large displays based on SSD1963 controller with XPT2046 touch controller.  

#### LCD Character

* [Grove_RGB_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) - Driver for SeeedStudio's Grove RGB LCD.
* [lcdi2c](https://github.com/slothyrulez/lcdi2c) - HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-charlcd](https://github.com/rdagger/micropython-charlcd) - HD44780 兼容 LCD 的驱动程序.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) - I2C 2x16 LCD 屏幕的驱动程序.
* [pyboard-LCD-character-display](https://github.com/scitoast/pyboard-LCD-character-display) - 用于 HDD44780 兼容 1602 LCD 的 PyBoard 驱动程序.
* [python_lcd](https://github.com/dhylands/python_lcd) - HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-lcd](https://github.com/wjdp/micropython-lcd) - 用于从 MicroPython pyboard 控制 HD44780 的类.
* [HD44780-lcd-upy](https://gitlab.com/rafalosa/HD44780-lcd-upy) - 用于控制通用 HD44780 LCD 的 MicroPython 模块.
* [LCM1602-14_LCD_Library](https://github.com/Bhavithiran97/LCM1602-14_LCD_Library) - AIP31068L 驱动程序 [3.3 V I2C and SPI 1602 Serial Character LCDs](https://www.cytron.io/p-3v3-i2c-and-spi-1602-serial-character-lcd).

#### LCD Graphic

* [micropython-lcd-AQM1248A](https://github.com/forester3/micropython-lcd-AQM1248A) - AQM1248A 图形 LCD 的 ESP8266 驱动程序.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) - 诺基亚 5110 PCD8544 84x48 LCD 模块的驱动程序.
* [micropython-st7565](https://github.com/nquest/micropython-st7565) - Driver for ST7565 128x64 LCDs.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) - 使用 ESP8266 和 SPI 的 ST7920 128x64 单色 LCD 面板上的简单图形基元库.
* [MicroPython_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) - 诺基亚 5110 PCD8544 的 ESP8266 驱动程序.
* [Official LCD160CR](https://github.com/micropython/micropython/tree/master/drivers/display) - Driver for official MicroPython LCD160CR display with resistive touch sensor.
* [micropython-hx1230](https://github.com/mcauser/micropython-hx1230) - 用于 HX1230 96x68 LCD 模块的 MicroPython 库.
* [micropython-SHARP_Memory_Display](https://github.com/pramasoul/micropython-SHARP_Memory_Display) - MicroPython driver for SHARP memory display.

#### LCD TFT

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - Collection of drivers for TFT displays, ILI9341, SH1106, SSD1606, ST7735.
* [micropython-ili934x](https://github.com/tuupola/micropython-ili934x) - SPI driver for ILI934X series based TFT / LCD displays.
* [MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735) - ESP32 version of GuyCarvers's ST7735 TFT LCD driver.
* [micropython-st7735](https://github.com/hosaka/micropython-st7735) - Driver for ST7735 TFT LCDs.
* [MicroPython_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735) - ST7735 128x128 TFT 驱动程序.
* [SSD1963-TFT-Library-for-PyBoard-and-RP2040](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) - 用于 PyBoard 和 Raspberry Pi PICO 的 SSD1963 TFT 库.
* [ST7735](https://github.com/GuyCarver/MicroPython/blob/master/lib/ST7735.py) - Driver for ST7735 TFT LCDs.
* [micropython-ili9341](https://github.com/rdagger/micropython-ili9341) - MicroPython ILI9341 display & XPT2046 touch screen driver.
* [st7789_mpy](https://github.com/devbis/st7789_mpy) - Fast pure-C driver for MicroPython that can handle display modules on ST7789 chip.
* [st7789py_mpy](https://github.com/devbis/st7789py_mpy) - 用于 240x240 ST7789 显示器的慢速 MicroPython 驱动程序，无需来自 Ali Express 的 CS 引脚，用 MicroPython 编写.
* [micropython-ili9341](https://github.com/jeffmer/micropython-ili9341) - MicroPython Driver for ILI9341 display.
* [micropython-ili9341](https://github.com/tkurbad/micropython-ili9341) - ILI9341 TFT driver for MicroPython on ESP32.
* [st7789_mpy](https://github.com/russhughes/st7789_mpy) - Fast MicroPython driver for ST7789 display module written in C.
* [st7789py_mpy](https://github.com/russhughes/st7789py_mpy) - Driver for 320x240, 240x240 and 135x240 ST7789 displays written in MicroPython.
* [ili9342c_mpy](https://github.com/russhughes/ili9342c_mpy) - 用于 MicroPython（M5Stack 核心）的 ILI9342C 快速“C”驱动程序.
* [gc9a01py](https://github.com/russhughes/gc9a01py) - GC9A01 MicroPython 中的显示驱动程序.
* [gc9a01_mpy](https://github.com/russhughes/gc9a01_mpy) - 用 C 编写的用于 GC9A01 显示模块的快速 MicroPython 驱动程序.
* [st7735-esp8266-micropython](https://github.com/cheungbx/st7735-esp8266-micropython) - An ESP8266 MicroPython library for st7735 160x80, 128x128, 128x160 TFT LCD displays.
* [TTGO-ST7789-MicroPython](https://github.com/schumixmd/TTGO-ST7789-MicroPython) - MicroPython ST7789 display driver for TTGO T-Display ESP32 CP2104 WiFi Bluetooth Module 1.14 Inch LCD.
* [st7735_micropython](https://github.com/cheungbx/st7735_micropython) - 用于 ESP8266 的 80x160、128x128、128x160 的 ST7735 MicroPython 驱动程序.
* [ili934x-micropython](https://gitlab.com/mhepp63/ili934x-micropython) - 用于将 ILI9341 显示驱动程序与 MicroPython 一起使用的库.
* [micropython-st7735-esp8266](https://gitlab.com/mo_krauti/micropython-st7735-esp8266) - 在 esp8266 上显示 ST7735 TFT 的 MicroPython 驱动程序.

#### LED Matrix

* [micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c) - HT1632C 32x16 双色 LED 矩阵驱动器.
* [micropython-matrix8x8](https://github.com/JanBednarik/micropython-matrix8x8) - 带 HT16K33 背包的 AdaFruit 8x8 LED 矩阵显示器的驱动程序.
* [micropython-max7219](https://github.com/mcauser/micropython-max7219) - MAX7219 8x8 LED 矩阵模块的驱动器.
* [micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield) - Wemos D1 Mini Matrix LED shield 驱动，使用 TM1640 芯片.
* [micropython-wemos-led-matrix](https://github.com/mattytrentini/micropython-wemos-led-matrix) - Wemos D1 Mini Matrix LED shield 驱动，使用 TM1640 芯片.
* [micropython-max7219](https://github.com/vrialland/micropython-max7219) - MAX7219 8x8 LED 矩阵的 MicroPython 驱动程序.

#### LED Segment

* [LKM1638](https://github.com/arikb/LKM1638) - 基于 TM1638 控制器的 JY-LKM1638 显示器驱动程序.
* [max7219_8digit](https://github.com/pdwerryhouse/max7219_8digit) - MAX7219 8位7段LED模块驱动器.
* [micropython-max7219](https://github.com/JulienBacquart/micropython-max7219) - MAX7219 8位7段LED模块驱动器.
* [micropython-my9221](https://github.com/mcauser/micropython-my9221) - Driver for MY9221 10-segment LED bar graph modules.
* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) - TM1637 四路 7 段 LED 模块的驱动器.
* [micropython-tm1638](https://github.com/mcauser/micropython-tm1638) - 用于带开关的 TM1638 双四路 7 段 LED 模块的驱动器.
* [micropython-tm1640](https://github.com/mcauser/micropython-tm1640) - Driver for TM1740 8x8 LED matrix modules.
* [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) - MicroPython Library for 16 digits 7-segment displays controlled by a TM1640.
* [TM74HC595](https://github.com/Sakartu/TM74HC595) - Driver for shift register controlled 5 pin display modules.

#### LEDs

* [micropython-morsecode](https://github.com/mampersat/micropython-morsecode) - 闪烁带有莫尔斯电码信息的 LED.
* [micropython-p9813](https://github.com/mcauser/micropython-p9813) - SeeedStudio 的 Grove 可链接 RGB LED 中使用的 P9813 RGB LED 驱动程序.
* [micropython-ws2812-7seg](https://github.com/HubertD/micropython-ws2812-7seg) - 7-segment display using WS2812 RGB LEDs.
* [micropython-ws2812](https://github.com/JanBednarik/micropython-ws2812) - Driver for WS2812 RGB LEDs.
* [Official APA102](http://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) - ESP8266 APA102/DotStar RGB LED 驱动器.
* [Official WS2811](http://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) - ESP8266 WS2811/NeoPixel RGB LED driver.
* [tlc5940-micropython](https://github.com/oysols/tlc5940-micropython) - Driver for TLC5940 16 channel LED driver.
* [ws2812-SPI](https://github.com/nickovs/ws2812-SPI) - 高效的 MicroPython WS2812 (NeoPixel) 驱动程序.
* [micropython-ws2801](https://github.com/HeMan/micropython-ws2801) - 与 WS2801 RGB LED 串连接的 MicroPython 库.
* [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) - Driver for the TLC5947 24 channel 12-bit PWM LED driver.
* [Hybotics_Micropython_HT16K33](https://github.com/hybotics/Hybotics_Micropython_HT16K33) - 用于 HT16K33 的 MicroPython 驱动程序、LED 矩阵、7 段数字和 14 段字母数字显示驱动器 IC.
* [micropython-rgbled](https://github.com/Warringer/micropython-rgbled) - This wrapper module aims to reduce the work needed to work with NeoPixel (WS2812) and DotStar (APA102) RGB LED strips and matrixes.
* [micropython_fastled](https://github.com/kdschlosser/micropython_fastled) - Port of FastLED to MicroPython.
* [micropython_quickled](https://github.com/thebaron88/micropython_quickled) - MicroPython 模块，允许 python 全速将数据泵入 ws2811 LED.
* [micropython-rgb-led-driver](https://gitlab.com/Athanaze/micropython-rgb-led-driver) - 用 PWM 控制 RGB LED 的微型驱动器.

#### OLED

* [Grove_OLED](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) - Driver for SSD1327 used by SeeedStudio's Grove OLED Display 1.12" v1.0.
* [micropython-oled](https://github.com/mcauser/deshipu-micropython-oled) - Collection of drivers for monochrome OLED displays, PCD8544, SH1106, SSD1306, UC1701X.
* [micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327) - SSD1327 128x128 4 位灰度 OLED 显示器的驱动程序.
* [micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351) - Driver for SSD1351 OLED displays.
* [MicroPython_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306) - ESP8266 driver for SSD1306 OLED 128x64 displays.
* [Official SSD1306](https://github.com/micropython/micropython/tree/master/drivers/display) - SSD1306 128x64 OLED 显示器的驱动程序.
* [SH1106](https://github.com/robert-hh/SH1106) - SH1106 OLED 显示器的驱动程序.
* [micropython-ssd1309](https://github.com/rdagger/micropython-ssd1309) - MicroPython SSD1309 单色 OLED 显示驱动程序.
* [sh1107-micropython](https://github.com/nemart69/sh1107-micropython) - 基于 SH1107 的 OLED 显示器 (64 x 128) 的 MicroPython 驱动程序.

#### Printer

* [micropython-thermal-printer](https://github.com/ayoy/micropython-thermal-printer) - Adafruit 的 Python 热敏打印机的 MicroPython 端口.

### IO

#### ADC

* [ads1x15](https://github.com/robert-hh/ads1x15) - ADS1015/ADS1115 ADC 驱动程序，I2C 接口.
* [micropython-ads1015](https://github.com/mcauser/deshipu-micropython-ads1015) - ADS1015 12-Bit and ADS1115 16-bit ADC, 4 channels with programmable gain, I2C interface.
* [Micropython_ADS1115](https://github.com/AnthonyKNorman/Micropython_ADS1115) - ADS1115 16 位 ADC，4 通道可编程增益，I2C 接口.
* [ADS7818](https://github.com/robert-hh/ADS7818) - 连接 ADS7818 AD 转换器的 Python 类.
* [micropython-ads1219](https://github.com/miketeachman/micropython-ads1219) - 用于德州仪器 ADS1219 ADC 的 MicroPython 模块.
* [micropython-hx711](https://github.com/SergeyPiskunov/micropython-hx711) - 用于 HX711 24 位模数转换器的 MicroPython 驱动程序.
* [MicroPython-ADC_Cal](https://github.com/matthias-bs/MicroPython-ADC_Cal) - ESP32 ADC 驱动器使用来自 efuse 的参考电压校准值.

#### DAC

* [micropython-mcp4725](https://github.com/wayoda/micropython-mcp4725) - Driver for the MCP4725 I2C DAC.
* [mcp4728](https://github.com/openfablab/mcp4728) - Helper library for the Microchip MCP4728 I2C 12-bit Quad DAC.

#### GPIO

* [micropython-inputs](https://github.com/alanmitchell/micropython-inputs) - 用于对 MicroPython 板进行脉冲计数、数字输入去抖动和计算模拟输入移动平均值的类.
* [ubutton](https://gitlab.com/WiLED-Project/ubutton) - A MicroPython library for controlling reading and debouncing pushbutton inputs, including "short" and "long" press callbacks.
* [micropython-debounce-switch](https://github.com/selfhostedhome/micropython-debounce-switch) - 用于去抖开关的 MicroPython 类.

#### IO-Expander

* [micropython-mcp230xx](https://github.com/ShrimpingIt/micropython-mcp230xx) - Driver for MCP23017 and MCP23008 GPIO expanders.
* [micropython-mcp23017](https://github.com/mcauser/micropython-mcp23017) - 用于 MCP23017 16 位 I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8574](https://github.com/mcauser/micropython-pcf8574) - 带有中断的 PCF8574 8 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8575](https://github.com/mcauser/micropython-pcf8575) - 用于带中断的 PCF8575 16 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) - PCF8591 8 位 I2C I/O 扩展器的 MicroPython 驱动程序.

#### Joystick

* [micropython-nunchuck](https://github.com/kfricke/micropython-nunchuck) - Driver for Nunchuk game controller, I2C interface.

#### Keyboard

* [micropython-keyboard](https://github.com/mcameron/micropython-keyboard) - 在 MicroPython pyboard 上运行的 47 键键盘.
* [pico-rgbkeypad](https://github.com/martinohanlon/pico-rgbkeypad) - A Python class for controlling the Pimoroni RGB Keypad for Raspberry Pi Pico.
* [micropython-aiobutton](https://github.com/jacklinquan/micropython-aiobutton) - 用于 asyncio 按钮的 MicroPython 模块.

#### Potentiometers

* [micropython-ad840x](https://github.com/dsiggi/micropython-ad840x) - MicroPython SPI-based manipulation of the AD series digital potentiometers AD8400, AD8402 and AD8403.
* [mcp4131](https://github.com/scruss/mcp4131) - 用于控制 MicroChip 的 MCP4131 SPI 数字电位器的 MicroPython 模块.
 
#### Power Management

* [AXP202_PythonLibrary](https://github.com/lewisxhe/AXP202_PythonLibrary) - MicroPython AXP202 库.
* [micropython_hourly_sleeper_library](https://github.com/costastf/micropython_hourly_sleeper_library) - A MicroPython library that enables an esp8266 to sleep for hourly increments for a setup amount of hours.

#### PWM

* [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) - 用于在异步循环中控制 PWM 输出的 MicroPython 库，具有衰减和闪烁等功能.

#### Rotary Encoder

* [micropython-rotary](https://github.com/miketeachman/micropython-rotary) - 用于读取旋转编码器的 MicroPython 模块.
* [uencoder](https://gitlab.com/WiLED-Project/uencoder) - A MicroPython library for reading from a rotary encoder.
* [encodermenu](https://github.com/sgall17a/encodermenu) - 使用旋转编码器和基本显示器的 micropython 简单 GUI 菜单.
* [encoderLib](https://github.com/BramRausch/encoderLib) - 处理旋转编码器的 MicroPython 库.
* [rotary-encoder](https://github.com/gurgleapps/rotary-encoder) - 驱动 KY-040 旋转编码器的 MicroPython 代码.
* [micropython-encoder-knob](https://github.com/infinite-tree/micropython-encoder-knob) - 一个非常简单的轻量级编码器旋钮库，支持按钮.
* [encoders](https://github.com/peterhinch/micropython-samples/blob/master/encoders/ENCODERS.md) Short document explaining issues around encoder technology.
* [asynchronous encoder driver](https://github.com/peterhinch/micropython-async/blob/master/v3/primitives/encoder.py) 将编码器连接到 uasyncio 代码.

#### Shift Registers

* [micropython-74hc595](https://github.com/mcauser/micropython-74hc595) - MicroPython driver for 74HC595 8-bit shift registers.
* [MicroPython-SN74HCS264](https://gitlab.com/olivierlenoir/MicroPython-SN74HCS264) - 用于具有施密特触发器输入和反相输出的 SN74HCS264 8 位并行输出串行移位寄存器的 MicroPython 驱动程序.

#### Waveform Generator

* [Micropython-AD9833](https://github.com/KipCrossing/Micropython-AD9833) - AD9833 的 Pyboard 驱动程序，spi 接口.
* [Clock_Generators](https://github.com/Wei1234c/Clock_Generators) - 时钟发生器（目前为 Si5351）工具箱.
* [Signal_Generators](https://github.com/Wei1234c/Signal_Generators) - Signal generators (AD9833, AD9834, AD9850, ADF4351) tools box.
* [ad9850_signalgen](https://github.com/brenn/ad9850_signalgen) - MicroPython library for AD9850 synthesizer.

### Motion

#### DC Motor

* [L298N](https://github.com/GuyCarver/MicroPython/blob/master/lib/L298N.py) - L298N 双 H 桥电机控制器的驱动器。
* [MicroPython-L298](https://gitlab.com/olivierlenoir/MicroPython-L298) - 使用 MicroPython 驱动 L298 双 H 桥.

#### Servo

* [micropython-pca9685](https://github.com/mcauser/deshipu-micropython-pca9685) - 16 通道 12 位 PWM/伺服驱动器.

#### Stepper

* [micropython-upybbot](https://github.com/jeffmer/micropython-upybbot) - A4988 driver for bipolar stepper motors.
* [uln2003](https://github.com/IDWizard/uln2003) - 5V 28BYJ-48 步进电机驱动器.
* [micropython-multiaxis](https://gitlab.com/olivierlenoir/micropython-multiaxis) - 带有 MicroPython ESP32 和 DRV8825 的多轴.
* [ticlib](https://github.com/jphalip/ticlib) - Pololu Tic 步进电机控制器的驱动程序.
* [AccelStepper-MicroPython](https://github.com/pedromneto97/AccelStepper-MicroPython) - AccelStepper Library for MicroPython - ESP32.
* [pystepper](https://github.com/marcio-pessoa/pystepper) - MicroPython 步进电机序列控制.
* [uPySteppers](https://github.com/lemariva/uPySteppers) - 使用连接到 Wi-Fi 的 ESP32 的 DIY 旋转平台.
* [microPython_AMIS-30543](https://github.com/capella-ben/microPython_AMIS-30543) - 使用 AMIS-30543 驱动程序控制步进驱动程序的 MicroPython 库.

### Sensors

#### Accelerometer Digital

* [ADXL345-with-Pyboard](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) - Driver for ADXL345 16g 3-axis accelerometer.
* [adxl345_micropython](https://github.com/fanday/adxl345_micropython) - Driver for ADXL345 16g 3-axis accelerometer.
* [micropython-lis2hh12](https://github.com/tuupola/micropython-lis2hh12) - LIS2HH12 3 轴加速度计的 I2C 驱动程序.
* [MMA7660](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) - Driver for MMA7660 1.5g 3-axis accelerometer.
* [ADXL345_spi_micropython](https://github.com/AlekseyFedorovich/ADXL345_spi_micropython) - Library for interacting through the SPI protocol with an 'Analog Devices ADXL345' accelerometer from an MCU flashed with MicroPython.

#### Air Quality

* [CCS811](https://github.com/Ledbelly2142/CCS811) - CCS811 Air Quality Sensor.
* [upython-aq-monitor](https://github.com/ayoy/upython-aq-monitor) - 使用 PMS5003 传感器和 WiPy 的空气质量监测器.
* [micropython-pms7003](https://github.com/pkucmus/micropython-pms7003) - PMS7003 空气质量传感器的 MicroPython 驱动程序.
* [pms5003_micropython](https://github.com/kevinkk525/pms5003_micropython) - Driver for pms5003 air quality sensor for MicroPython.
* [micropython-pms5003-minimal](https://github.com/miketeachman/micropython-pms5003-minimal) - Driver for pms5003 air quality sensor for MicroPython.
* [polly](https://github.com/g-sam/polly) - SDS011 pollution sensor + Wemos D1 mini pro + MicroPython.

#### Barometer

* [micropython-bme280](https://github.com/kevbu/micropython-bme280) - Bosch BME280 温度/压力/湿度传感器的驱动程序.
* [micropython-bmp180](https://github.com/micropython-IMU/micropython-bmp180) - Bosch BMP180 温度、压力和高度传感器的驱动程序.
* [mpy_bme280_esp8266](https://github.com/catdog2/mpy_bme280_esp8266) - Bosch BME280 temperature/pressure/humidity sensor.
* [BME280](https://github.com/robert-hh/BME280) - BME280 传感器的 MicroPython 驱动程序，目标平台 Pycom 设备.
* [micropython-bmp280](https://github.com/dafvid/micropython-bmp280) - Module for the BMP280 sensor.
* [micropython_bme280_i2c](https://github.com/triplepoint/micropython_bme280_i2c) - A MicroPython module for communicating with the Bosch BME280 temperature, humidity, and pressure sensor.
* [MicroPython-BME280](https://github.com/neliogodoi/MicroPython-BME280) - 驱动温度、压力和湿度的数字传感器.
* [micropython-bmp180](https://gitlab.com/flowolf/micropython-bmp180) - A module for MicroPython which provides a class for the BMP180 pressure sensor.

#### Battery

* [Micropython-LC709203F](https://github.com/scopelemanuele/Micropython-LC709203F) - 用于 LC709293F 电量计的简单 MicroPython 库.

#### Biometric

* [micropython-fingerprint](https://github.com/chrisb2/micropython-fingerprint) - 用于读取 Grow 和 ZhianTec 指纹传感器的 MicroPython 库.
* [MAX30102-MicroPython-driver](https://github.com/n-elia/MAX30102-MicroPython-driver) - A MAX30102 driver ported to MicroPython. It should also work for MAX30105.

#### Camera

* [micropython-ov2640](https://github.com/namato/micropython-ov2640) - OV2640 相机的 MicroPython 类.
* [Nikon-Trigger-for-MicroPython](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython) - Remote trigger for a Nikon camera using an IR LED. For PyBoard v1.1.
* [micropython-camera-driver](https://github.com/lemariva/micropython-camera-driver) - 用于 ESP32 上的 MicroPython 的 OV2640 摄像头驱动程序.
* [esp32-cam-micropython](https://github.com/shariltumin/esp32-cam-micropython) - MicroPython esp32-cam.
* [uPyCam](https://github.com/lemariva/uPyCam) - Take a photo with an ESP32-CAM running MicroPython.
* [OV2640_uPy](https://github.com/FunPythonEC/OV2640_uPy) - OV2640 Camera Library for MicroPython.
* [MQTT-Cam](https://github.com/jono-allen/MQTT-Cam) - ESP-32 Cam MicroPython MQTT AWS S3 Uploader.

#### Colour

* [micropython-tcs34725](https://gitlab.com/robhamerling/micropython-tcs34725) - Driver class for TCS34725 and TCS34727 color sensors.

#### Compass

* [micropython-esp8266-hmc5883l](https://github.com/gvalkov/micropython-esp8266-hmc5883l) - ESP8266 上的 3 轴数字罗盘.
* [QMC5883](https://github.com/robert-hh/QMC5883) - QMC5883 三轴数字罗盘 IC 的 Python 类.
* [microPython_AS5600L](https://github.com/capella-ben/microPython_AS5600L) - MicroPython driver for AS5600L magnet rotary position sensor.

#### Current

* [micropythonINA219](https://github.com/kabel42/micropythonINA219) - INA219 电流传感器驱动器.
* [pyb_ina219](https://github.com/chrisb2/pyb_ina219) - INA219 电流传感器驱动器.
* [INA219](https://github.com/robert-hh/INA219) - INA219 MicroPython driver.
* [TI_INA226_micropython](https://github.com/elschopi/TI_INA226_micropython) - 用于德州仪器 INA226 功率测量 IC 的 MicroPython 驱动程序.
* [micropython-current-monitor](https://gitlab.com/n.rj.powers/micropython-current-monitor) - 使用 INA219 和 SSD1306 OLED 的电流监视器.

#### Distance IR

* [micropython-gp2y0e03](https://github.com/mcauser/deshipu-micropython-gp2y0e03) - 使用夏普 GP2Y0E03 的 IR-LED 测距传感器.
* [micropython-vl6180](https://github.com/mcauser/deshipu-micropython-vl6180) - 飞行时间传感器、环境光传感器和红外发射器.

#### Distance Laser

* [micropython-vl53l0x](https://github.com/mcauser/deshipu-micropython-vl53l0x) - 飞行时间激光测距传感器.
* [Qwiic_TOF_Module_RFD77402](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) - Qwiic TOF 模块 (RFD77402) 飞行时间测距模块.
* [VL53L0X](https://github.com/uceeatz/VL53L0X) - MicroPython Library for Lidar Sensor VL53L0X.
* [vl53l1x_pico](https://github.com/drakxtwo/vl53l1x_pico) - 用于 vl53l1x ToF 传感器的 MicroPython 驱动程序.
* [tf-luna-micropython](https://github.com/davmoz/tf-luna-micropython) - 一个用于 TF-Luna LiDAR 模块的简单 MicroPython i2c 库.
* [vl53l5cx](https://github.com/mp-extras/vl53l5cx) - MicroPython and CircuitPython Package for the [VL53L5CX](https://www.st.com/en/imaging-and-photonics-solutions/vl53l5cx.html) （4x4/8x8 ToF 传感器阵列）.

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) - Driver for HC-SR04 ultrasonic distance sensors.
* [micropython-us100](https://github.com/kfricke/micropython-us100) - MicroPython driver for the US-100 sonar distance sensor.

#### Dust

* [pyGP2Y](https://github.com/amigcamel/pyGP2Y) - MicroPython library for the Sharp GP2Y1014AU0F Dust Sensor.

#### Energy

* [ATM90E26_Micropython](https://github.com/whatnick/ATM90E26_Micropython) - ATM90E26 电能计量设备的驱动程序.
* [MCP39F521](https://github.com/warpme/MCP39F521) - ESP8266 scripts for reading MCP39F521 power monitors.
* [micropython-p1meter](https://github.com/Josverl/micropython-p1meter) - 一个 ESP32 传感器，用于读取 p1 电表并将其发布到 MQTT 和 HomeAssistant，用 MicroPython 编写.
* [esp32-solar2](https://github.com/octopusengine/esp32-solar2) - Simple solar regulator - MicroPython project.

#### Gaseous

* [micropython-MQ](https://github.com/kartun83/micropython-MQ) - MQ 系列气体传感器的驱动程序.
* [MQ135](https://github.com/rubfi/MQ135) - Driver for MQ135 gas sensor.
* [CCS811](https://github.com/Notthemarsian/CCS811) - Basic MicroPython driver for CCS811 on ESP8266 boards.
* [micropython-scd30](https://github.com/agners/micropython-scd30) - Sensirion SCD30 CO2 传感器模块的 MicroPython I2C 驱动程序.
* [micropython-sgp40](https://github.com/agners/micropython-sgp40) - MicroPython I2C driver for SGP40 VOC sensor module.
* [MICS6814-Micropython-driver](https://gitlab.com/DanNduati/MICS6814-Micropython-driver) - ESP32 Micropython driver for the Pimoroni mics6814 breakout board.

#### Light

* [MicroPython-SI1145](https://github.com/neliogodoi/MicroPython-SI1145) - SI1145 紫外线指数、红外线、可见光和接近传感器.
* [micropython-tsl2561](https://github.com/kfricke/micropython-tsl2561) - 来自 TAOS / ams 的 TSL2561 照度传感器驱动程序.
* [mpy_bh1750fvi_esp8266](https://github.com/catdog2/mpy_bh1750fvi_esp8266) - BH1750FVI 传感器的 ESP8266 驱动程序.
* [bh1750](https://github.com/PinkInk/upylib/tree/master/bh1750) - BH1750 i2c 数字光传感器驱动程序.
* [micropython-max44009](https://github.com/mcauser/micropython-max44009) - MicroPython driver for the MAX44009 ambient light sensor.
* [veml7700](https://github.com/palouf34/veml7700) - 用于 VEML7700 光传感器的 MicroPython 库.
* [MicroPython_MAX44009_driver](https://github.com/rcolistete/MicroPython_MAX44009_driver) - MAX44009 光传感器的 MicroPython 驱动程序.

#### Motion Inertial

* [micropython-bmx055](https://github.com/micropython-IMU/micropython-bmx055) - Bosch BMX055 IMU 传感器的驱动程序.
* [micropython-bno055](https://github.com/deshipu/micropython-bno055) - Bosch Sensortec BNO055 9DOF IMU sensor, I2C interface.
* [micropython-lsm9ds0](https://github.com/micropython-IMU/micropython-lsm9ds0) - LSM9DS0 g-force 线性加速度、高斯磁和 dps 角速率传感器.
* [micropython-mpu9250](https://github.com/tuupola/micropython-mpu9250) - 用于 MPU9250 9 轴运动跟踪设备的 I2C 驱动程序.
* [micropython-mpu9x50](https://github.com/micropython-IMU/micropython-mpu9x50) - InvenSense MPU9250 惯性测量单元的驱动程序.
* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) - MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [py-mpu6050](https://github.com/larsks/py-mpu6050) - MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [micropython-mpu6886](https://github.com/tuupola/micropython-mpu6886) - MicroPython I2C driver for MPU6886 6-axis motion tracking device.
* [micropython-fusion](https://github.com/micropython-IMU/micropython-fusion) - Sensor fusion calculates heading, pitch and roll from the outputs of motion tracking devices.
* [flight_controller](https://github.com/wagnerc4/flight_controller) - MicroPython 飞行控制器.
* [micropython-bno055](https://github.com/micropython-IMU/micropython-bno055)  - 用于 MicroPython 的博世 BNO055 驱动程序.  IMU 与硬件传感器融合.
* [micropython-mpu6050-mqtt-streamer](https://github.com/mozanunal/micropython-mpu6050-mqtt-streamer) - 使用 ESP8266 上的 MicroPython 将数据从 MPU6050 流式传输到 MQTT 服务器.
* [upy-motion](https://github.com/OneMadGypsy/upy-motion) - A simple MPU6050 driver written in MicroPython.
* [micropython-bno08x-rvc](https://github.com/rdagger/micropython-bno08x-rvc) - bno08x 的 MicroPython 库.
* [micropython-mpu9250](https://gitlab.com/nnayo/micropython-mpu9250) -MicroPython MPU-9250 (MPU-6500 + AK8963) I2C 驱动程序.

#### Pressure

* [ms5803-micropython](https://github.com/minyiky/ms5803-micropython) - A MicroPython implementation of the driver for an MS5803 pressure & temperature sensor.
* [MPL3115A2_MicroPython](https://github.com/PinsonJonas/MPL3115A2_MicroPython) - MPL3115A2 高度计的 MicroPython 库.

#### Proximity

* [uPy_APDS9960](https://github.com/rlangoy/uPy_APDS9960) - MicroPython proximity library for esp8266 using APDS9960.

#### Radiation

* [micropython-geiger](https://github.com/Josep/micropython-geiger) - 带有 MicroPython 卡的盖革计数器.
* [ESPGeiger](https://github.com/biemster/ESPGeiger) - 用于 ESP8266 盖革计数器的 MicroPython 库.

#### Soil Moisture

* [micropython-chirp](https://github.com/robberwick/micropython-chirp) - 啁啾土壤湿度传感器的驱动程序.
* [MicroPython-MiFlora](https://github.com/matthias-bs/MicroPython-MiFlora) - Xiaomi Mi Flora (aka. flower care) BLE plant sensors (soil moisture/conductivity/light intensity/temperature).

#### Spectral

* [AS726X_LoPy](https://github.com/jajberni/AS726X_LoPy) - 用于 AS726X 光谱传感器的 MicroPython 驱动程序.

#### Temperature Analog

* [micropython-max31855](https://github.com/mcauser/deshipu-micropython-max31855) - 热电偶放大器，SPI接口.
* [max31856](https://github.com/alinbaltaru/max31856) - Precision thermocouple to digital converter with linearization, SPI interface.
* [mcp9700](https://gitlab.com/CrispyCrafter/mcp9700) - MCP9700 的通用 MicroPython 驱动程序.

#### Temperature Digital

* [bme680-mqtt-micropython](https://github.com/robmarkcole/bme680-mqtt-micropython) - BME680 气体、压力、温度和湿度传感器的驱动程序.
* [LM75-MicroPython](https://github.com/OldhamMade/LM75-MicroPython) - LM75数字温度传感器驱动，I2C接口.
* [micropython-am2320](https://github.com/mcauser/micropython-am2320) - 傲松AM2320温湿度传感器，I2C接口.
* [micropython-dht12](https://github.com/mcauser/micropython-dht12) - 傲松DHT12温湿度传感器，I2C接口.
* [micropython-hdc1008](https://github.com/kfricke/micropython-hdc1008) - 德州仪器 HDC1008 湿度和温度传感器的驱动程序.
* [micropython-mcp9808](https://github.com/kfricke/micropython-mcp9808) - Microchip MCP9808 温度传感器的驱动程序.
* [micropython-mpl115a2](https://github.com/khoulihan/micropython-mpl115a2) - 用于 MPL115A2 气压传感器的 Pyboard 驱动程序.
* [micropython-sht30](https://github.com/rsc1975/micropython-sht30) - Driver for SHT30 temperature and humidity sensor.
* [micropython-sht31](https://github.com/kfricke/micropython-sht31) - SHT31温湿度传感器驱动.
* [micropython-Si7005](https://github.com/Smrtokvitek/micropython-Si7005) - Driver for Si7005 relative humidity and temperature sensor.
* [micropython-si7021](https://github.com/mcauser/deshipu-micropython-si7021) - SI7021 Temperature and humidity sensor, I2C interface.
* [micropython-si7021](https://github.com/chrisbalmer/micropython-si7021) - SI7021 Temperature and humidity sensor, I2C interface.
* [micropython-Si705x](https://github.com/billyrayvalentine/micropython-Si705x) - Silicon Labs Si705x 系列温度传感器，I2C 接口.
* [micropython-Si70xx](https://github.com/billyrayvalentine/micropython-Si70xx) - Silicon Labs Si70xx series of relative humidity and temperature sensors, I2C interface.
* [micropython-tmp102](https://github.com/khoulihan/micropython-tmp102) - TMP102 数字温度传感器的驱动程序.
* [Official DHT11+DHT12](https://github.com/micropython/micropython/blob/master/drivers/dht/dht.py) - DHT11 和 DHT12 温湿度传感器的 ESP8266 驱动程序.
* [sht25-micropython](https://github.com/Miceuz/sht25-micropython) - SHT25温湿度传感器驱动.
* [micropython-tmp1075](https://github.com/mattytrentini/micropython-tmp1075) - TI TMP1075 温度传感器的驱动程序.
* [micropython-sht11](https://github.com/2black0/micropython-sht11) - Driver for Sensirion SHT11 temperature and humidity sensor.
* [micropython-lm75a](https://github.com/mcauser/micropython-lm75a) - NXP LM75A 数字温度传感器的驱动程序.
* [BME680-Micropython](https://github.com/robert-hh/BME680-Micropython) - MicroPython driver for the BME680 sensor.
* [htu21d-esp8266](https://github.com/julianhille/htu21d-esp8266) - 这是一个 MicroPython 模块/类，用于测量来自 htu21d 的数据.
* [HTU21D](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/HTU21D.md) Asynchronous driver for this temperature and humidity sensor.
* [esp-sht3x-micropython](https://github.com/HAIZAKURA/esp-sht3x-micropython) - A SHT3x (SHT30/31/35) Lib for esp8266/esp32 with MicroPython.
* [sht25-micropython](https://gitlab.com/miceuz/sht25-micropython) - SHT25 温湿度传感器 API 的 MicroPython 实现.
* [micropython-sht30](https://github.com/schinckel/micropython-sht30) - SHT30 sensor driver in pure python based on I2C bus.
* [micropython_ahtx0](https://github.com/targetblank/micropython_ahtx0) - MicroPython driver for the AHT10 and AHT20 temperature and humidity sensors.

#### Temperature IR

* [micropython-mlx90614](https://github.com/mcauser/micropython-mlx90614) - Melexis MLX90614 IR 温度传感器的驱动程序.

#### Touch Capacitive

* [micropython-mpr121](https://github.com/mcauser/micropython-mpr121) - MPR121 电容式触摸键盘和分线板的驱动程序.
* [micropython-ttp223](https://github.com/mcauser/micropython-ttp223) - 使用 TTP223 电容触摸模块的示例.
* [micropython-TTP229-BSF](https://github.com/alankrantas/micropython-TTP229-BSF) - MicroPython ESP8266/ESP32 驱动程序，用于串行接口模式下的 TTP229-BSF 16 键电容式键盘.
* [uFT6336U](https://github.com/fantasticdonkey/uFT6336U) - MicroPython I2C driver for the Focus LCDs FT6336U capacitive touch panel controller IC.

#### Touch Resistive

* [XPT2046-touch-pad-driver](https://github.com/robert-hh/XPT2046-touch-pad-driver) - 用于许多 TFT 模块中的 XPT2046 触摸板控制器的驱动程序.

### Scheduling

* [micropython-mcron](https://github.com/fizista/micropython-mcron) - MicroCRON 是一个基于时间的 MicroPython 任务调度程序.
* [micropython-scron](https://github.com/fizista/micropython-scron) - SimpleCRON 是一个基于时间的任务调度程序，灵感来自著名的 Unix 系统 CRON 程序.
* [Schedule](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/SCHEDULE.md) 基于 uasyncio 的应用程序的调度程序. 在指定的时间和日期安排活动.

### Storage

#### Database

* [uPyMySQL](https://github.com/dvrhax/uPyMySQL) - Pure uPython MySQL Client.
* [micropython-redis](https://github.com/dwighthubbard/micropython-redis) - 设计用于 MicroPython 的 redis 客户端实现.
* [picoredis](https://github.com/SpotlightKid/picoredis) - MicroPython 的一个非常小的 Redis 客户端（不仅仅是）.
* [micropg](https://github.com/nakagami/micropg) - PostgreSQL database driver for MicroPython.
* [nmongo](https://github.com/nakagami/nmongo) - 用于 CPython 和 MicroPython 的 MongoDB 客户端，具有类似 API 的 mongo shell.
* [MicroPyDatabase](https://github.com/sungkhum/MicroPyDatabase) - MicroPython 的基于 json 的低内存数据库.
* [micropython-firebase-realtime-database](https://github.com/ckoever/micropython-firebase-realtime-database) - Firebase implementation for MicroPython optimized for ESP32.
* [uSQLite](https://github.com/spatialdude/usqlite) - MicroPython 的 SQLite 库模块.

#### EEPROM

* [micropython_eeprom](https://github.com/peterhinch/micropython_eeprom) - 用于存储芯片（EEPROM、FRAM、闪存、PSRAM）的跨平台 MicroPython 设备驱动程序.
* [mb_24x256_512](https://github.com/MarksBench/mb_24x256_512) - 用于 Microchip 24x256 和 24x512 I2C EEPROM 设备的非常简单的 MicroPython 模块/驱动程序.

#### Flash

* [micropython_data_to_py](https://github.com/peterhinch/micropython_data_to_py) - 一个 Python3 实用程序，用于将任意二进制文件转换为 Python 源，以便在 Flash 中冻结为字节码.

#### FRAM

* [micropython-fram](https://github.com/rolandvs/micropython-fram) - 铁电 RAM 模块的 Pyboard 驱动程序.

#### PSRAM

* [mb_PSRAM_64Mb_SPI](https://github.com/MarksBench/mb_PSRAM_64Mb_SPI) - 非常简单的 MicroPython 模块，可使用通用 64Mbit PSRAM（即 Adafruit 4677）和 Raspberry Pi Pico（RP2040）.

#### SRAM

* [mb_23LC1024](https://github.com/MarksBench/mb_23LC1024) - 非常简单的 MicroPython 模块，可使用带有 Raspberry Pi Pico (RP2040) 的 Microchip 23LC1024 SPI SRAM.
* [mb_47x16](https://github.com/MarksBench/mb_47x16) - 用于 Microchip 47x16 EERAM 设备 (47L/47C) 的非常简单的 MicroPython 模块/驱动程序.

### Threading

* [MicroWorkers](https://github.com/jczic/MicroWorkers) - 一个微工作者类，可轻松管理线程池以优化 MicroPython（用于 Pycom 模块和 ESP32）的同时作业和作业结束.

### User Interface

* [upymenu](https://github.com/jplattel/upymenu) - MicroPython Menu for LCD Displays.

## Community

* [MicroPython Forum](https://forum.micropython.org/) - 超过 6400 名用户的在线社区，讨论与 MicroPython 相关的所有内容.
* [MicroPython on Twitter](https://twitter.com/micropython?lang=en) - 在 Twitter 上关注 MicroPython 以获取最新消息和更新.
* [MicroPython on Facebook](https://www.facebook.com/micropython) - Like MicroPython on Facebook for competitions, news and updates.
* [Melbourne MicroPython Meetup](https://www.meetup.com/en-AU/MicroPython-Meetup) - 在澳大利亚墨尔本的 CCHS 定期聚会.
* [Slack](https://slack-micropython.herokuapp.com/) - Get an automated invite to the micropython.slack.com workspace.
* [Discord](https://discord.gg/qw7d8bv) - Get an invite to the MicroPython Discord server.

## Tutorials

* [uasyncio](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/TUTORIAL.md) 编写与硬件设备接口的异步代码.
* [Asynchronous drivers](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/DRIVERS.md) 开关、按钮、编码器和 ADC 异步接口的教程和代码.
* [Pyboard micropower](https://github.com/peterhinch/micropython-micropower) Pyboard 1.x 和 Pyboard D 上的低功耗应用教程和代码.
* [3D rotation with quaternions](https://github.com/peterhinch/micropython-samples/blob/master/QUATERNIONS.md) Tutorial and code for the easy way to do 3D rotation.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](http://shop.oreilly.com/product/0636920056515.do) - By Nicholas H. Tollervey. ISBN 9781491972731.
* [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://www.apress.com/gp/book/9781484231227) - By Charles Bell. ISBN 9781484231227.
* [MicroPython Cookbook](https://www.packtpub.com/au/application-development/micropython-cookbook) <i>- By Marwan Alsabbagh.</i> <b>- 马尔万·阿尔萨巴格。</b> <i>ISBN 9781838649951.</i><b>国际标准书号 9781838649951。</b>
* [Python for Microcontrollers: Getting Started with MicroPython](https://www.amazon.com.au/Python-Microcontrollers-Getting-Started-MicroPython/dp/1259644537)  - 唐纳德诺里斯. 国际标准书号 9781259644535.
* [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937)  - 尤里·玛格达. 国际标准书号 9781090900937.
* [MicroPython Projects](https://www.packtpub.com/au/iot-hardware/micropython-projects)  - 雅各布·贝宁戈. 国际标准书号 9781789958034.
* [Get Started with MicroPython on Raspberry Pi Pico](https://store.rpipress.cc/products/get-started-with-micropython-on-raspberry-pi-pico)  - Gareth Halfacree 和 Ben Everard 着. 国际标准书号 9781912047864.
* [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book)  - Günter Spanner. 国际标准书号 9783895764370.
* [MicroPython For Everyone: How To Use ESP32 And ESP8266: Micropython Mqtt](https://www.amazon.com/MicroPython-Everyone-ESP32-ESP8266-Micropython/dp/B094281XK1)  - 梅森米莱特. 国际标准书号 9798748248822.

## Frameworks

* [micrOS](https://github.com/BxNxM/micrOS) - MicroPython based IoT Framework.
* [terkin-datalogger](https://github.com/hiveeyes/terkin-datalogger) - Flexible data logger application for MicroPython and CPython.
* [perthensis](https://codeberg.org/scy/perthensis) - Perthensis: an asynchronous framework for MicroPython.

## Resources

* [MicroPython](http://micropython.org) - Project website. Test drive the pyboard. Try MicroPython online with unicorn.
* [MicroPython on GitHub](https://github.com/micropython/micropython) - Submit bug reports, follow and join in development on GitHub.
* [MicroPython Official Documentation](http://docs.micropython.org/) - 对于各种端口，包括快速参考、一般信息、示例和教程.
* [MicroPython Wiki](http://wiki.micropython.org/Home) - Community generated documentation and examples of the features of MicroPython and the pyboard.
* [MicroPython Newsletter](http://micropython.org/newsletter) - 订阅 MicroPython 时事通讯以获取包括新功能和新产品在内的新闻和公告.
* [MicroPython Store](https://store.micropython.org/) - 您可以在哪里购买 pyboard、外壳、外壳、书籍、连接器和外围设备.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) - 维基百科上的 MicroPython.
* [awesome-micropythons](https://github.com/adafruit/awesome-micropythons) - MicroPython 的许多分支和端口.

## Development

### Code Generation

* [micropy-cli](https://github.com/BradenM/micropy-cli) - Micropy Cli is a project management/generation tool for writing MicroPython code in modern IDEs such as VSCode.
* [micropython-stubber](https://github.com/Josverl/micropython-stubber) - 为不同的 MicroPython 固件生成和使用存根，以与 vscode 和/或 pylint 一起使用.
* [micropy-stubs](https://github.com/BradenM/micropy-stubs) - 为 Micropy-Cli 和其他任何人自动生成的存根包.
* [micropython-extmod-generator](https://github.com/prusnak/micropython-extmod-generator) - 用 C 编写的 MicroPython 外部模块的生成器.

### Debugging

* [esp32-backtrace](https://github.com/tve/esp32-backtrace) - ESP32 Exception Stack Backtrace Analyzer.
* [micropython-aiosentry](https://github.com/devbis/micropython-aiosentry) - Asynchronous Sentry.io micro client for MicroPython.
* [micropython-usyslog](https://github.com/kfricke/micropython-usyslog) - Simple remote syslog client for MicroPython.
* [Asynchronous monitor](https://github.com/peterhinch/micropython-monitor) 使用 Raspberry Pico 和逻辑分析仪或示波器来监控异步代码.

### IDEs

* [BIPES](https://bipes.net.br/beta2/ui/)  - 基于 Web 的 MicroPython IDE，带有文件管理器、编辑器、块代码生成、物联网仪表板和 Web 浏览器上的串行/USB/蓝牙/WebREPL 控制台！ 来源： [https://github.com/BIPES](https://github.com/BIPES).
* [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) - Plugin for MicroPython devices in IntelliJ and PyCharm.
* [Micropython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) - MicroPython IDE for VSCode README.
* [Micropython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) - Handy shortcuts for interacting with a MicroPython REPL terminal.
* [Mu Editor](https://codewith.mu/) -  Code with Mu: a simple Python\MicroPythonb\CircuitPython editor for beginner programmers.
* [Thonny IDE](https://thonny.org/) - Thonny：适合初学者的 Python IDE.
* [Pyboard File Manager](https://github.com/joewez/PyboardFileManager) - Pyboard 文件管理器：Pyboard.py 兼容设备的 Windows GUI.

### Logging

* [micropython-ulogger](https://github.com/Li-Lian1069/micropython-ulogger) - 为 MicroPython 定制的轻量级日志模块.

### Shells

#### On Device

* [upy-shell](https://github.com/dhylands/upy-shell) - A simple command line based shell for MicroPython.
* [Micropython-Editor](https://github.com/robert-hh/Micropython-Editor) - Small on-board editor for PyBoard, WiPy, ESP8266, ESP32, PyCom and Adafruit devices written in Python.

#### On Host

* [rshell](https://github.com/dhylands/rshell) - Copy or Sync files to Boards, enter REPL from your terminal.
* [ampy](https://github.com/scientifichackers/ampy) - MicroPython Tool - 通过串行连接与 MicroPython 板交互的实用程序.
* [mpfshell](https://github.com/wendlers/mpfshell) - 一个用于 ESP8266 和 WiPy 的简单的基于 shell 的文件浏览器.
* [mpsync](https://github.com/Uhlo/mpsync) - 一个小工具，可在检测到更改时将文件夹同步到 MicroPython 板.
* [mpremote](https://github.com/micropython/micropython/blob/master/tools/mpremote/README.md) 强大的官方shell支持挂载宿主机当前目录到目标机. 在不更改目标文件系统的情况下运行代码.

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 backers pledged £97,803 to help bring this project to life.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 backers pledged £28,534 to help bring this project to life.

## Contributing

贡献和建议总是受欢迎的！ 请看一下 [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could vote for them by adding 👍 to them.
