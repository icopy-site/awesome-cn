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

精选的 MicroPython 库、框架、软件和资源的精选列表.

[MicroPython](http://micropython.org/) 是 Python 3 编程语言的精简高效实现，其中包含 Python 标准库的一小部分，并针对在微控制器和受限环境中运行进行了优化.



## Libraries

您可以在其他地方寻找 MicroPython 库：

* [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython)  - 此过滤器仅显示 PyPi 上的 MicroPython 库. 注意：您不能 pip install micropython 库. 看 [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html?highlight=upip) 有关 upip 的更多信息.
* [GitHub Search](https://github.com/search?q=micropython) - 在 GitHub 上搜索包含 MicroPython 的存储库.
* [GitHub Topic - MicroPython](https://github.com/topics/micropython) - 浏览带有 MicroPython 标记的项目的 GitHub 主题.
* [Libraries.io](https://libraries.io/search?q=micropython) - 用于 MicroPython 的 Libraries.io 查询.
* [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc&utf8=%E2%9C%93&name=micropython&sort=latest_activity_desc) - 探索 GitLab 上的存储库.

### AI

* [MicroMLP](https://github.com/jczic/MicroMLP) - 用于 MicroPython 的微神经网络多层感知器（用于 ESP32 和 Pycom 模块）.

### Analytics

* [uMath](https://github.com/AaronKel/uMath) - 微控制器的计算机代数.
* [micropython-ulab](https://github.com/v923z/micropython-ulab) - 用于 MicroPython 的类似 numpy 的快速矢量模块.
* [micropython-fourier](https://github.com/peterhinch/micropython-fourier) - MicroPython 的内联 ARM 汇编程序中的快速傅立叶变换.
* [ulinalg](https://github.com/jalawson/ulinalg) - 小尺寸矩阵处理模块，带有一些专门用于 MicroPython (Python3) 的线性代数运算.
* [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) - MicroPython 上的快速矩阵乘法和线性求解器.
* [micropython-vec](https://gitlab.com/nickoala/micropython-vec) - MicroPython 上的矢量操作.

### Audio

* [JQ6500](https://github.com/rdagger/micropython-jq6500) - JQ6500 UART MP3 模块的驱动程序.
* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) - KT403A 驱动程序，由 DFPlayer Mini 和 Grove MP3 v2.0 使用.
* [micropython-buzzer](https://github.com/fruch/micropython-buzzer) - 在蜂鸣器上播放 nokia compose 和 mid 文件.
* [micropython-dfplayer](https://github.com/ShrimpingIt/micropython-dfplayer) - 使用 UART 的 DFPlayer Mini 驱动程序.
* [micropython-longwave](https://github.com/MattMatic/micropython-longwave) - MicroPython 板的 WAV 播放器.
* [micropython-vs1053](https://github.com/peterhinch/micropython-vs1053) - VS1053b MP3 播放器的异步驱动程序.
* [micropython-midi](https://github.com/cjbarnes18/micropython-midi) - MicroPython 的 MIDI 实现示例.
* [upy-rtttl](https://github.com/dhylands/upy-rtttl) - 用于铃声文本传输语言 (RTTTL) 的 Python 解析器.

### Communications

#### Bluetooth

* [PyBoard-HC05-Android](https://github.com/KipCrossing/PyBoard-HC05-Android) - Pyboard HC05 蓝牙适配器示例应用程序.
* [uble](https://github.com/dmazzella/uble) - 用纯 python 为 micropython 编写的轻量级蓝牙低功耗驱动程序.

#### CAN

* [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) - Spacecan 是用于嵌入式系统的 SpaceCAN 协议的 MicroPython 实现.

#### Cryptography

* [mpyaes](https://github.com/iyassou/mpyaes) - 用于 AES 加密的 MicroPython 模块.
* [micropython-aes](https://github.com/piaca/micropython-aes) - AES 算法与纯 python 实现.
* [ucrypto](https://github.com/dmazzella/ucrypto)  - 用于进行快速椭圆曲线加密的 Micropython 包，特别是数字签名.  API 设计灵感来自 fastecdsa 和基于 tomsfastmath 的实现.
* [ucryptoauthlib](https://github.com/dmazzella/ucryptoauthlib) - Microchip Crypto Authentication 安全元素的轻量级驱动程序，用纯 python 编写，用于 micropython.

#### DNS

* [ICantBelieveItsNotDNS](https://github.com/yschaeff/ICantBelieveItsNotDNS)  - “我不敢相信这不是 DNS！”  (ICBIND) 是用 MicroPython 编写的 ESP8266 的权威 DNS 服务器.
* [MicroDNSSrv](https://github.com/jczic/MicroDNSSrv) - MicroPython 的微型 DNS 服务器，可以简单地响应带有或不带有通配符的多域上的 A 查询（用于 Pycom 模块和 ESP32）.

#### Ethernet

* [Official wiznet5k](https://github.com/micropython/micropython/tree/master/drivers/wiznet5k) - WIZnet5x00 系列以太网控制器的官方驱动程序.

#### FTP

* [micropython-ftplib](https://github.com/SpotlightKid/micropython-ftplib) - MicroPython 的 FTP 客户端库.
* [FTP-Server-for-ESP8266-ESP32-and-PYBD](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) - MicroPython 平台上用于 ​​ESP8266/ESP32/PYBD 的小型 FTP 服务器.
* [MicroFTPServer](https://github.com/cpopp/MicroFTPServer) - 可以在带有 MicroPython 的 ESP8266 上运行的最小 FTP 服务器.

#### GPS

* [micropyGPS](https://github.com/inmcm/micropyGPS) - 全功能 GPS NMEA 句子解析器.
* [micropython-gnssl76l](https://github.com/tuupola/micropython-gnssl76l) - 移远通信 GNSS L76-L (GPS) 的 MicroPython I2C 驱动程序.
* [mpy-agps](https://github.com/pulkin/mpy-agps) - 辅助定位服务 (AGPS) 的 MicroPython 实现.

#### GSM

* [micropython-upyphone](https://github.com/jeffmer/micropython-upyphone) - 使用 pyboard 和 sim800l 的 GSM 手机.

#### IoT

* [microhomie](https://github.com/microhomie/microhomie) - 适用于 IoT 的 Homie MQTT 约定的 MicroPython 实现.
* [uPyEcho](https://github.com/lemariva/uPyEcho) - 模拟 Belkin WeMo 设备，在 ESP32 上使用 MicroPython 与 Amazon Echo (Alexa) 配合使用.
* [SonosRemote](https://github.com/foosel/SonosRemote) - 在 ESP8266 上运行并使用 Sonos HTTP API 的 Sonos 安装遥控器.
* [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) - 基于 MicroPython 的脚本可扩展您的家庭助理驱动的家庭自动化项目.

#### IR

* [micropython-necir](https://github.com/MattMatic/micropython-necir) - TL1838 红外接收器 LED 的 NEC 红外捕获.
* [Micropython-IR](https://github.com/designerPing/Micropython-IR) - Pyboard 红外远程嗅探和重播.
* [micropython_ir](https://github.com/peterhinch/micropython_ir) - 从红外遥控器和红外“冲击波”应用程序接收的非阻塞设备驱动程序.
* [micropython-amg88xx](https://github.com/peterhinch/micropython-amg88xx) - Grid-EYE 热红外阵列传感器 (Adafruit 3538) 的驱动程序.
* [micropython-ys-irtm](https://github.com/mcauser/micropython-ys-irtm) - YS-IRTM 5V NEC 红外 UART 收发器的 MicroPython 示例.
* [esp8266_ir](https://github.com/ruoyu0088/esp8266_ir) - 通过 websocket 控制红外信号.

#### LoRaWAN

* [uPyLoRaWAN](https://github.com/lemariva/uPyLoRaWAN) - 使用 MicroPython 的 ESP32 满足 LoRa 和 LoRaWAN.
* [DeLoReAN](https://github.com/buehl/DeLoReAN) - DeLoReAN 是一个（De）专用（Lo）RaWAN 节点（重新）记录（A）ny（N）FC 标签.

#### MDNS

* [micropython-mdns](https://github.com/cbrand/micropython-mdns) - MDNS 的纯 Python 实现，支持服务发现.

#### MQTT

* [micropython-mqtt](https://github.com/peterhinch/micropython-mqtt)  - “弹性”异步 MQTT 驱动程序. 加上一种使用 ESP8266 将 MQTT 带到非联网目标的方法.
* [MQBoard](https://github.com/tve/mqboard) - 用于在 MicroPython 板上使用 MQTT 和 asyncio 的微框架，主要在 ESP32 上.
* [pysmartnode](https://github.com/kevinkk525/pysmartnode) - MicroPython 智能家居框架.
* [umqtt_aws_iot](https://github.com/juwul/umqtt_aws_iot) - 使用 MicroPython 将 UMQTT 消息发布到 AWS IoT.
* [sonoff-mqtt by davea](https://github.com/davea/sonoff-mqtt) - 使用 MQTT 控制 Sonoff/ESP8266 的 MicroPython 脚本.
* [micropython-sonoff-switch](https://github.com/kfricke/micropython-sonoff-switch) - 使用 MicroPython 为 iTead Sonoff Switch 实现了 MQTT 可控开关.
* [micropython-thingspeak-mqtt-esp8266](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) - 使用 MQTT 和在 ESP8266/ESP32 平台上运行的 MicroPython 发布和订阅 Thingspeak.
* [uMQTT](https://github.com/andrewmk/uMQTT) - 在 WiPy 板上为 MicroPython 发布 MQTT.

#### NTP

* [esp8266_ntp_webserver](https://github.com/Roterfux/esp8266_ntp_webserver) - MicroPython + esp8266 + ntp + 网络服务器.
* [micropython-ntpd](https://github.com/dave2/micropython-ntpd) - MicroPython 中 ntpd 的实现.
* [micropython_ntpserver](https://github.com/GrantGMiller/micropython_ntpserver) - 为 MicroPython 编写的 NTP 服务器.
* [micropython-ntpclient](https://github.com/wieck/micropython-ntpclient) - 使用 uasyncio 的 MicroPython NTP 客户端.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython/tree/master/drivers/onewire) - 对于使用 OneWire 总线的设备，例如 Dallas ds18x20.

#### Onkyo EISCP

* [eiscp-micropython](https://github.com/cbrand/eiscp-micropython) - 用于 Onkyo-EISCP 协议的 Micropython 端口，其中包括 Pioneer.

#### Radio

* [micropython-radio](https://github.com/peterhinch/micropython-radio) - nRF24L01 2.4Ghz 无线电模块的协议.
* [micropython-rfsocket](https://github.com/wuub/micropython-rfsocket) - 流行的基于 433MHzn 的 RFSocket 的 MicroPython 实现.
* [Official nRF24L01](https://github.com/micropython/micropython/tree/master/drivers/nrf24l01) - nRF24L01 2.4Ghz 无线电模块的官方驱动程序.
* [micropython_remote](https://github.com/peterhinch/micropython_remote)  - 捕获和重放 433MHz 遥控代码. 控制远程开关电源适配器.
* [micropython-ys-rf34t](https://github.com/mcauser/micropython-ys-rf34t) - 使用 YS-RF34T 433MHz ASK/OOK UART 收发器的 MicroPython 示例.

#### REPL

* [webrepl](https://micropython.org/webrepl) - MicroPython WebREPL.
* [zepl](https://gitlab.com/zepl1/zepl) - 使用 ZeroMQ 的 MicroPython WebREPL 控制台应用程序.
* [jupyter_micropython_remote](https://gitlab.com/alelec/jupyter_micropython_remote) - Jupyter 内核可通过串行/网络 REPL 在 MicroPython 板上直接执行代码.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) - NXP MFRC522 RFID 读写器的驱动程序.
* [micropython-wiegand](https://github.com/pjz/micropython-wiegand) - 韦根协议阅读器.

#### RTC

* [micropython-tinyrtc-i2c](https://github.com/mcauser/micropython-tinyrtc-i2c) - DS1307 RTC 和 AT24C32N EEPROM 的驱动程序.
* [Micropython_TinyRTC](https://github.com/AnthonyKNorman/Micropython_TinyRTC) - DS1307 RTC 驱动程序.
* [micropython-mcp7940](https://github.com/mattytrentini/micropython-mcp7940) - Microchip MCP7940 RTC 的驱动程序.

#### Serial

* [mpy-miniterm](https://github.com/jeffmakes/mpy-miniterm) - 通过串行 REPL 与 MicroPython 设备进行无缝串行调试和文件同步的工具.
* [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) - modbus-tk 的 MicroPython 端口.

#### SMTP

* [uMail](https://github.com/shawwwn/uMail) - 一个轻量级、可扩展的 SMTP 客户端，用于在 MicroPython 中发送电子邮件.

#### Telnet

* [MicroTelnetServer](https://github.com/cpopp/MicroTelnetServer) - 用于 MicroPython 和 ESP8266 的简单 telnet 服务器，允许 telnet 客户端访问 REPL.

#### WiFi

* [HueBridge](https://github.com/FRC4564/HueBridge) - 飞利浦色调桥.
* [micropython-wifimanager](https://github.com/mitchins/micropython-wifimanager) - ESP8266 板上 MicroPython 的简单网络配置实用程序.

#### Web

* [MicroWebSrv](https://github.com/jczic/MicroWebSrv) - 支持 WebSockets、html/python 语言模板和路由处理程序的微型 HTTP Web 服务器，用于 MicroPython（在 Pycom 模块和 ESP32 上使用）.
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - 最后一个用于物联网 (MicroPython) 或大型服务器 (CPython) 的微型 Web 服务器，它支持 WebSockets、路由、模板引擎和真正优化的架构（内存分配、异步 I/O）.
* [tinyweb](https://github.com/belyalov/tinyweb) - 用于 MicroPython 的简单轻量级 HTTP 异步服务器.
* [upy-websocket-server](https://github.com/BetaRavener/upy-websocket-server) - MicroPython (ESP8266) websocket 服务器实现.
* [micropython-captive-portal](https://github.com/amora-labs/micropython-captive-portal) - MicroPython 的强制门户演示.
* [uPyPortal](https://github.com/lemariva/uPyPortal) - 使用 ESP32 (WeMos) 的 MicroPython 强制门户.
* [ESP8266WebServer](https://github.com/codemee/ESP8266WebServer) - 用于 MicroPython 的 ESP8266 网络服务器.
* [microCoAPy](https://github.com/insighio/microCoAPy) - 在 MicroPython 中实现 CoAP（受限应用协议）的微型客户端/服务器.
* [micropyserver](https://github.com/troublegum/micropyserver) - MicroPyServer 是一个用于 MicroPython 项目的简单 HTTP 服务器.
* [MicroRESTCli](https://github.com/jczic/MicroRESTCli) - 基于 MicroWebCli for MicroPython 的微型 JSON REST Web 客户端（用于 Pycom 模块和 ESP32）.
* [micropython-noggin](https://github.com/larsks/micropython-noggin) - 一个非常简单的 MicroPython 网络服务器.
* [uwebsockets](https://github.com/danni/uwebsockets) - ESP8266 的 MicroPython websockets 实现.
* [microdot](https://github.com/miguelgrinberg/microdot) - 用于 MicroPython 的不可思议的小型 Web 框架.
* [micropython-utelegram](https://github.com/jordiprats/micropython-utelegram) - MicroPython 的 Telegram API 包装器.

#### Zigbee

* [ZbPy](https://github.com/osresearch/ZbPy) - MicroPython IEEE802.15.4 / Zigbee 解析器.

### Display

#### E-Paper

* [micropython-epaper](https://github.com/peterhinch/micropython-epaper) - 适用于 Embedded Artists 2.7 英寸电子纸显示器的 Pyboard 驱动程序.
* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - SSD1606 有源矩阵电子纸显示器 128x180.
* [micropython-waveshare-epaper](https://github.com/mcauser/micropython-waveshare-epaper) - 各种 Waveshare 电子纸模块的驱动程序.
* [micropython-waveshare-epd](https://github.com/ayoy/micropython-waveshare-epd) - 用于运行 Pycom 风格的 MicroPython 的设备的 Waveshare 电子纸显示驱动程序.
* [ssd1675a](https://github.com/mattytrentini/ssd1675a) - 基于 SSD1675 的电子纸显示器的驱动程序.

#### GUI

* [lvgl](https://github.com/lvgl/lv_binding_micropython) - 一个面向对象的基于组件的高级 GUI 库，具有 MicroPython 绑定.
* [micropython-lcd160cr-gui](https://github.com/peterhinch/micropython-lcd160cr-gui) - 用于 Pyboard 和 LCD160CR 彩色显示器的基于简单触摸驱动事件的 GUI.
* [micropython_ra8875](https://github.com/peterhinch/micropython_ra8875) - 用于基于 RA8875 的显示器的 MicroPython 设备驱动程序和 nano-GUI.
* [micropython-nano-gui](https://github.com/peterhinch/micropython-nano-gui)  - Nano-Gui 为显示驱动程序从 framebuf 类继承的显示器提供了一组有限的 GUI 对象（小部件）. 其中包括 LCD 和 OLED 显示器.

#### LCD Character

* [Grove_RGB_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) - SeeedStudio 的 Grove RGB LCD 驱动程序.
* [lcdi2c](https://github.com/slothyrulez/lcdi2c) - 适用于 HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-charlcd](https://github.com/rdagger/micropython-charlcd) - 适用于 HD44780 兼容 LCD 的驱动程序.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) - I2C 2x16 LCD 屏幕驱动程序.
* [pyboard-LCD-character-display](https://github.com/scitoast/pyboard-LCD-character-display) - 用于 HDD44780 兼容 1602 LCD 的 PyBoard 驱动程序.
* [python_lcd](https://github.com/dhylands/python_lcd) - 适用于 HD44780 兼容点阵 LCD 的驱动程序.
* [micropython-lcd](https://github.com/wjdp/micropython-lcd) - Class for controlling the HD44780 from a MicroPython pyboard.

#### LCD Graphic

* [micropython-lcd-AQM1248A](https://github.com/forester3/micropython-lcd-AQM1248A) - 用于 AQM1248A 图形 LCD 的 ESP8266 驱动程序.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) - 诺基亚 5110 PCD8544 84x48 LCD 模块的驱动程序.
* [micropython-st7565](https://github.com/nquest/micropython-st7565) - ST7565 128x64 LCD 驱动程序.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) - 使用 ESP8266 和 SPI 在 ST7920 128x64 单色 LCD 面板上的简单图形基元库.
* [MicroPython_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) - 用于诺基亚 5110 PCD8544 的 ESP8266 驱动程序.
* [Official LCD160CR](https://github.com/micropython/micropython/tree/master/drivers/display) - 带有电阻式触摸传感器的官方 MicroPython LCD160CR 显示器驱动程序.
* [micropython-hx1230](https://github.com/mcauser/micropython-hx1230) - 用于 HX1230 96x68 LCD 模块的 MicroPython 库.

#### LCD TFT

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) - TFT 显示器驱动程序集，ILI9341、SH1106、SSD1606、ST7735.
* [micropython-ili934x](https://github.com/tuupola/micropython-ili934x) - 用于基于 ILI934X 系列的 TFT / LCD 显示器的 SPI 驱动程序.
* [MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735) - GuyCarvers 的 ST7735 TFT LCD 驱动程序的 ESP32 版本.
* [micropython-st7735](https://github.com/hosaka/micropython-st7735) - ST7735 TFT LCD 驱动器.
* [MicroPython_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735) - ST7735 128x128 TFT 驱动器.
* [SSD1963-TFT-Library-for-PyBoard-and-RP2040](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) - 用于 PyBoard 和 Raspberry Pi PICO 的 SSD1963 TFT 库.
* [ST7735](https://github.com/GuyCarver/MicroPython/blob/master/lib/ST7735.py) - ST7735 TFT LCD 驱动器.
* [micropython-ili9341](https://github.com/rdagger/micropython-ili9341) - MicroPython ILI9341 显示器和 XPT2046 触摸屏驱动程序.
* [st7789_mpy](https://github.com/devbis/st7789_mpy) - MicroPython 的快速纯 C 驱动程序，可以处理 ST7789 芯片上的显示模块.
* [st7789py_mpy](https://github.com/devbis/st7789py_mpy) - 用于 240x240 ST7789 显示器的慢速 MicroPython 驱动程序，没有来自 Ali Express 的 CS 引脚，用 MicroPython 编写.
* [micropython-ili9341](https://github.com/jeffmer/micropython-ili9341) - 用于 ILI9341 显示器的 MicroPython 驱动程序.
* [micropython-ili9341](https://github.com/tkurbad/micropython-ili9341) - 用于 ESP32 上的 MicroPython 的 ILI9341 TFT 驱动程序.

#### LED Matrix

* [micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c) - HT1632C 32x16 双色 LED 矩阵的驱动程序.
* [micropython-matrix8x8](https://github.com/JanBednarik/micropython-matrix8x8) - 带 HT16K33 背包的 AdaFruit 8x8 LED 矩阵显示器驱动程序.
* [micropython-max7219](https://github.com/mcauser/micropython-max7219) - MAX7219 8x8 LED 矩阵模块的驱动器.
* [micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield) - Wemos D1 Mini Matrix LED shield 驱动器，使用 TM1640 芯片.
* [micropython-wemos-led-matrix](https://github.com/mattytrentini/micropython-wemos-led-matrix) - Wemos D1 Mini Matrix LED shield 驱动器，使用 TM1640 芯片.
* [micropython-max7219](https://github.com/vrialland/micropython-max7219) - 用于 MAX7219 8x8 LED 矩阵的 MicroPython 驱动程序.

#### LED Segment

* [LKM1638](https://github.com/arikb/LKM1638) - 基于 TM1638 控制器的 JY-LKM1638 显示器驱动程序.
* [max7219_8digit](https://github.com/pdwerryhouse/max7219_8digit) - MAX7219 8 位 7 段 LED 模块的驱动器.
* [micropython-max7219](https://github.com/JulienBacquart/micropython-max7219) - MAX7219 8 位 7 段 LED 模块的驱动器.
* [micropython-my9221](https://github.com/mcauser/micropython-my9221) - MY9221 10 段 LED 条形图模块的驱动器.
* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) - TM1637 四路 7 段 LED 模块的驱动器.
* [micropython-tm1638](https://github.com/mcauser/micropython-tm1638) - 带有开关的 TM1638 双四路 7 段 LED 模块的驱动器.
* [micropython-tm1640](https://github.com/mcauser/micropython-tm1640) - TM1740 8x8 LED 矩阵模块的驱动程序.
* [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) - 用于由 TM1640 控制的 16 位 7 段显示器的 MicroPython 库.
* [TM74HC595](https://github.com/Sakartu/TM74HC595) - 用于移位寄存器控制的 5 针显示模块的驱动器.

#### LEDs

* [micropython-morsecode](https://github.com/mampersat/micropython-morsecode) - 用摩尔斯编码信息闪烁 LED.
* [micropython-p9813](https://github.com/mcauser/micropython-p9813) - SeeedStudio 的 Grove Chainable RGB LED 中使用的 P9813 RGB LED 驱动器.
* [micropython-ws2812-7seg](https://github.com/HubertD/micropython-ws2812-7seg) - 使用 WS2812 RGB LED 的 7 段显示器.
* [micropython-ws2812](https://github.com/JanBednarik/micropython-ws2812) - WS2812 RGB LED 驱动器.
* [Official APA102](http://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) - ESP8266 APA102/DotStar RGB LED 驱动器.
* [Official WS2811](http://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) - ESP8266 WS2811/NeoPixel RGB LED 驱动器.
* [tlc5940-micropython](https://github.com/oysols/tlc5940-micropython) - TLC5940 16 通道 LED 驱动器的驱动器.
* [ws2812-SPI](https://github.com/nickovs/ws2812-SPI) - 高效的 micropython WS2812 (NeoPixel) 驱动程序.
* [micropython-ws2801](https://github.com/HeMan/micropython-ws2801) - 用于与 WS2801 RGB LED 串连接的 MicroPython 库.
* [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) - TLC5947 24 通道 12 位 PWM LED 驱动器的驱动器.

#### OLED

* [Grove_OLED](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) - SeeedStudio 的 Grove OLED Display 1.12&quot; v1.0 使用的 SSD1327 驱动程序.
* [micropython-oled](https://github.com/mcauser/deshipu-micropython-oled) - 用于单色 OLED 显示器、PCD8544、SH1106、SSD1306、UC1701X 的驱动程序集.
* [micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327) - 用于 SSD1327 128x128 4 位灰度 OLED 显示器的驱动程序.
* [micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351) - SSD1351 OLED 显示器的驱动程序.
* [MicroPython_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306) - 用于 SSD1306 OLED 128x64 显示器的 ESP8266 驱动程序.
* [Official SSD1306](https://github.com/micropython/micropython/tree/master/drivers/display) - SSD1306 128x64 OLED 显示器驱动程序.
* [SH1106](https://github.com/robert-hh/SH1106) - SH1106 OLED 显示器的驱动程序.

### IO

#### ADC

* [ads1x15](https://github.com/robert-hh/ads1x15) - ADS1015/ADS1115 ADC、I2C 接口的驱动程序.
* [micropython-ads1015](https://github.com/mcauser/deshipu-micropython-ads1015) - ADS1015 12 位和 ADS1115 16 位 ADC，具有可编程增益的 4 通道，I2C 接口.
* [Micropython_ADS1115](https://github.com/AnthonyKNorman/Micropython_ADS1115) - ADS1115 16 位 ADC，具有可编程增益的 4 通道，I2C 接口.
* [ADS7818](https://github.com/robert-hh/ADS7818) - 连接 ADS7818 AD 转换器的 Python 类.
* [micropython-ads1219](https://github.com/miketeachman/micropython-ads1219) - 德州仪器 ADS1219 ADC 的 MicroPython 模块.
* [micropython-hx711](https://github.com/SergeyPiskunov/micropython-hx711) - 用于 HX711 24 位模数转换器的 MicroPython 驱动程序.
* [MicroPython-ADC_Cal](https://github.com/matthias-bs/MicroPython-ADC_Cal) - ESP32 ADC 驱动器使用来自 efuse 的参考电压校准值.

#### DAC

* [micropython-mcp4725](https://github.com/wayoda/micropython-mcp4725) - MCP4725 I2C DAC 的驱动程序.
* [mcp4728](https://github.com/openfablab/mcp4728) - Microchip MCP4728 I2C 12 位四通道 DAC 的帮助程序库.

#### GPIO

* [micropython-inputs](https://github.com/alanmitchell/micropython-inputs) - 为 MicroPython 板计算脉冲、数字输入去抖动和计算模拟输入的移动平均值的类.
* [ubutton](https://gitlab.com/WiLED-Project/ubutton) - 用于控制读取和消除按钮输入的 MicroPython 库，包括“短”和“长”按下回调.
* [micropython-debounce-switch](https://github.com/selfhostedhome/micropython-debounce-switch) - 用于去抖动开关的 MicroPython 类.

#### IO-Expander

* [MCP23017-ESP8266-Miniature-Driver](https://github.com/forkachild/MCP23017-ESP8266-Miniature-Driver) - MCP23017 16 位 I/O 扩展器的驱动程序.
* [micropython-mcp230xx](https://github.com/ShrimpingIt/micropython-mcp230xx) - MCP23017 和 MCP23008 GPIO 扩展器的驱动程序.
* [micropython-mcp23017](https://github.com/mcauser/micropython-mcp23017) - 用于 MCP23017 16 位 I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8574](https://github.com/mcauser/micropython-pcf8574) - 带有中断的 PCF8574 8 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8575](https://github.com/mcauser/micropython-pcf8575) - 带中断的 PCF8575 16 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) - PCF8591 8 位 I2C I/O 扩展器的 MicroPython 驱动程序.
* [micropython-74hc595](https://github.com/mcauser/micropython-74hc595) - 用于 74HC595 8 位移位寄存器的 MicroPython 驱动程序.

#### Joystick

* [micropython-nunchuck](https://github.com/kfricke/micropython-nunchuck) - Nunchuk 游戏控制器驱动程序，I2C 接口.

#### Potentiometers

* [micropython-ad840x](https://github.com/dsiggi/micropython-ad840x) - 基于 Micropython SPI 的 AD 系列数字电位器 AD8400、AD8402 和 AD8403 操作.
 
#### PWM

* [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) - 用于在异步循环中控制 PWM 输出的 MicroPython 库，具有淡入淡出和闪烁等功能.

#### Rotary Encoder

* [micropython-rotary](https://github.com/miketeachman/micropython-rotary) - 读取旋转编码器的 MicroPython 模块.
* [uencoder](https://gitlab.com/WiLED-Project/uencoder) - 用于从旋转编码器读取数据的 MicroPython 库.
* [encodermenu](https://github.com/sgall17a/encodermenu) - 使用旋转编码器和基本显示的 micropython 的简单 GUI 菜单.

#### Waveform Generator

* [Micropython-AD9833](https://github.com/KipCrossing/Micropython-AD9833) - AD9833 的 Pyboard 驱动程序，spi 接口.

### Motion

#### DC Motor

* [L298N](https://github.com/GuyCarver/MicroPython/blob/master/lib/L298N.py) - L298N 双 h 桥电机控制器的驱动程序.

#### Servo

* [micropython-pca9685](https://github.com/mcauser/deshipu-micropython-pca9685) - 16 通道 12 位 PWM/伺服驱动器.

#### Stepper

* [micropython-upybbot](https://github.com/jeffmer/micropython-upybbot) - 用于双极步进电机的 A4988 驱动器.
* [uln2003](https://github.com/IDWizard/uln2003) - 用于 5V 28BYJ-48 步进电机的驱动器.
* [micropython-multiaxis](https://gitlab.com/olivier.len02/micropython-multiaxis) - 带有 MicroPython ESP32 和 DRV8825 的多轴.
* [ticlib](https://github.com/jphalip/ticlib) - Pololu Tic 步进电机控制器的驱动程序.

### Sensors

#### Accelerometer Digital

* [ADXL345-with-Pyboard](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) - ADXL345 16g 3 轴加速度计的驱动程序.
* [adxl345_micropython](https://github.com/fanday/adxl345_micropython) - ADXL345 16g 3 轴加速度计的驱动程序.
* [micropython-lis2hh12](https://github.com/tuupola/micropython-lis2hh12) - LIS2HH12 3 轴加速度计的 I2C 驱动程序.
* [MMA7660](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) - MMA7660 1.5g 3 轴加速度计的驱动程序.

#### Air Quality

* [CCS811](https://github.com/Ledbelly2142/CCS811) - CCS811 空气质量传感器.
* [upython-aq-monitor](https://github.com/ayoy/upython-aq-monitor) - 使用 PMS5003 传感器和 WiPy 的空气质量监测器.
* [micropython-pms7003](https://github.com/pkucmus/micropython-pms7003) - PMS7003 空气质量传感器的 MicroPython 驱动程序.
* [pms5003_micropython](https://github.com/kevinkk525/pms5003_micropython) - 用于 MicroPython 的 pms5003 空气质量传感器的驱动程序.
* [micropython-pms5003-minimal](https://github.com/miketeachman/micropython-pms5003-minimal) - 用于 MicroPython 的 pms5003 空气质量传感器的驱动程序.
* [polly](https://github.com/g-sam/polly) - SDS011 污染传感器 + Wemos D1 mini pro + MicroPython.

#### Barometer

* [micropython-bme280](https://github.com/kevbu/micropython-bme280) - 博世 BME280 温度/压力/湿度传感器的驱动程序.
* [micropython-bmp180](https://github.com/micropython-IMU/micropython-bmp180) - 博世 BMP180 温度、压力和高度传感器的驱动程序.
* [mpy_bme280_esp8266](https://github.com/catdog2/mpy_bme280_esp8266) - 博世 BME280 温度/压力/湿度传感器.
* [BME280](https://github.com/robert-hh/BME280) - 用于 BME280 传感器、目标平台 Pycom 设备的 MicroPython 驱动程序.
* [micropython-bmp280](https://github.com/dafvid/micropython-bmp280) - BMP280 传感器模块.

#### Camera

* [micropython-ov2640](https://github.com/namato/micropython-ov2640) - 用于 OV2640 相机的 MicroPython 类.
* [Nikon-Trigger-for-MicroPython](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython)  - 使用红外 LED 远程触发尼康相机. 对于 PyBoard v1.1.
* [micropython-camera-driver](https://github.com/lemariva/micropython-camera-driver) - 用于 ESP32 上的 MicroPython 的 OV2640 相机驱动程序.

#### Compass

* [micropython-esp8266-hmc5883l](https://github.com/gvalkov/micropython-esp8266-hmc5883l) - ESP8266 上的 3 轴数字罗盘.
* [QMC5883](https://github.com/robert-hh/QMC5883) - QMC5883 三轴数字罗盘 IC 的 Python 类.

#### Current

* [micropythonINA219](https://github.com/kabel42/micropythonINA219) - INA219 电流传感器的驱动器.
* [pyb_ina219](https://github.com/chrisb2/pyb_ina219) - INA219 电流传感器的驱动器.

#### Distance IR

* [micropython-gp2y0e03](https://github.com/mcauser/deshipu-micropython-gp2y0e03) - 使用 Sharp GP2Y0E03 的 IR-LED 距离测量传感器.
* [micropython-vl6180](https://github.com/mcauser/deshipu-micropython-vl6180) - 飞行时间传感器、环境光传感器和红外发射器.

#### Distance Laser

* [micropython-vl53l0x](https://github.com/mcauser/deshipu-micropython-vl53l0x) - 飞行时间激光测距传感器.
* [Qwiic_TOF_Module_RFD77402](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) - Qwiic TOF 模块 (RFD77402) 飞行时间测距模块.

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) - HC-SR04 超声波距离传感器的驱动程序.

#### Energy

* [ATM90E26_Micropython](https://github.com/whatnick/ATM90E26_Micropython) - ATM90E26 电能计量设备的驱动程序.
* [MCP39F521](https://github.com/warpme/MCP39F521) - 用于读取 MCP39F521 功率监视器的 ESP8266 脚本.

#### Gaseous

* [micropython-MQ](https://github.com/kartun83/micropython-MQ) - MQ 系列气体传感器的驱动程序.
* [MQ135](https://github.com/rubfi/MQ135) - MQ135 气体传感器的驱动程序.
* [CCS811](https://github.com/Notthemarsian/CCS811) - ESP8266 板上 CCS811 的基本 MicroPython 驱动程序.
* [micropython-scd30](https://github.com/agners/micropython-scd30) - Sensirion SCD30 CO2 传感器模块的 MicroPython I2C 驱动程序.

#### Light

* [MicroPython-SI1145](https://github.com/neliogodoi/MicroPython-SI1145) - SI1145 紫外线指数、红外线、可见光和接近传感器.
* [micropython-tsl2561](https://github.com/kfricke/micropython-tsl2561) - 来自 TAOS / ams 的 TSL2561 照度传感器驱动程序.
* [mpy_bh1750fvi_esp8266](https://github.com/catdog2/mpy_bh1750fvi_esp8266) - 用于 BH1750FVI 传感器的 ESP8266 驱动程序.
* [bh1750](https://github.com/PinkInk/upylib/tree/master/bh1750) - BH1750 i2c 数字光传感器驱动程序.

#### Motion Inertial

* [micropython-bmx055](https://github.com/micropython-IMU/micropython-bmx055) - 博世 BMX055 IMU 传感器的驱动程序.
* [micropython-bno055](https://github.com/deshipu/micropython-bno055) - Bosch Sensortec BNO055 9DOF IMU 传感器，I2C 接口.
* [micropython-lsm9ds0](https://github.com/micropython-IMU/micropython-lsm9ds0) - LSM9DS0 g-force 线性加速度、高斯磁和 dps 角速率传感器.
* [micropython-mpu9250](https://github.com/tuupola/micropython-mpu9250) - 用于 MPU9250 9 轴运动跟踪设备的 I2C 驱动程序.
* [micropython-mpu9x50](https://github.com/micropython-IMU/micropython-mpu9x50) - InvenSense MPU9250 惯性测量单元的驱动程序.
* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) - 用于 MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [py-mpu6050](https://github.com/larsks/py-mpu6050) - 用于 MPU6050 加速度计/陀螺仪的 ESP8266 驱动程序.
* [micropython-mpu6886](https://github.com/tuupola/micropython-mpu6886) - 用于 MPU6886 6 轴运动跟踪设备的 MicroPython I2C 驱动程序.
* [micropython-fusion](https://gitlab.com/nnayo/micropython-fusion) - 传感器融合根据运动跟踪设备的输出计算航向、俯仰和滚转.

#### Pressure

* [ms5803-micropython](https://github.com/minyiky/ms5803-micropython) - MS5803 压力和温度传感器驱动程序的 micropython 实现.

#### Soil Moisture

* [micropython-chirp](https://github.com/robberwick/micropython-chirp) - Chirp 土壤湿度传感器的驱动程序.
* [MicroPython-MiFlora](https://github.com/matthias-bs/MicroPython-MiFlora) - 小米米植物群（又名花卉护理）BLE 植物传感器（土壤湿度/电导率/光强度/温度）.

#### Temperature Analog

* [micropython-max31855](https://github.com/mcauser/deshipu-micropython-max31855) - 热电偶放大器，SPI 接口.
* [max31856](https://github.com/alinbaltaru/max31856) - 具有线性化、SPI 接口的精密热电偶至数字转换器.

#### Temperature Digital

* [bme680-mqtt-micropython](https://github.com/robmarkcole/bme680-mqtt-micropython) - BME680 气体、压力、温度和湿度传感器的驱动程序.
* [LM75-MicroPython](https://github.com/OldhamMade/LM75-MicroPython) - LM75 数字温度传感器驱动程序，I2C 接口.
* [micropython-am2320](https://github.com/mcauser/micropython-am2320) - 奥松AM2320温湿度传感器，I2C接口.
* [micropython-dht12](https://github.com/mcauser/micropython-dht12) - 奥松DHT12温湿度传感器，I2C接口.
* [micropython-hdc1008](https://github.com/kfricke/micropython-hdc1008) - Texas Instruments HDC1008 湿度和温度传感器的驱动程序.
* [micropython-mcp9808](https://github.com/kfricke/micropython-mcp9808) - Microchip MCP9808 温度传感器的驱动程序.
* [micropython-mpl115a2](https://github.com/khoulihan/micropython-mpl115a2) - MPL115A2 气压传感器的 Pyboard 驱动程序.
* [micropython-sht30](https://github.com/rsc1975/micropython-sht30) - SHT30 温湿度传感器的驱动程序.
* [micropython-sht31](https://github.com/kfricke/micropython-sht31) - SHT31 温度和湿度传感器的驱动程序.
* [micropython-Si7005](https://github.com/Smrtokvitek/micropython-Si7005) - Si7005 相对湿度和温度传感器的驱动程序.
* [micropython-si7021](https://github.com/mcauser/deshipu-micropython-si7021) - SI7021温湿度传感器，I2C接口.
* [micropython-si7021](https://github.com/chrisbalmer/micropython-si7021) - SI7021温湿度传感器，I2C接口.
* [micropython-Si705x](https://github.com/billyrayvalentine/micropython-Si705x) - Silicon Labs Si705x 系列温度传感器，I2C 接口.
* [micropython-Si70xx](https://github.com/billyrayvalentine/micropython-Si70xx) - Silicon Labs Si70xx 系列相对湿度和温度传感器，I2C 接口.
* [micropython-tmp102](https://github.com/khoulihan/micropython-tmp102) - TMP102 数字温度传感器的驱动程序.
* [Official DHT11+DHT12](https://github.com/micropython/micropython/blob/master/drivers/dht/dht.py) - 用于 DHT11 和 DHT12 温湿度传感器的 ESP8266 驱动程序.
* [sht25-micropython](https://github.com/Miceuz/sht25-micropython) - SHT25 温湿度传感器的驱动程序.
* [micropython-tmp1075](https://github.com/mattytrentini/micropython-tmp1075) - TI TMP1075 温度传感器的驱动程序.
* [micropython-sht11](https://github.com/2black0/micropython-sht11) - Sensirion SHT11 温度和湿度传感器的驱动程序.
* [micropython-lm75a](https://github.com/mcauser/micropython-lm75a) - NXP LM75A 数字温度传感器的驱动程序.

#### Temperature IR

* [micropython-mlx90614](https://github.com/mcauser/micropython-mlx90614) - Melexis MLX90614 IR 温度传感器的驱动程序.

#### Touch Capacitive

* [micropython-mpr121](https://github.com/mcauser/micropython-mpr121) - MPR121 电容式触摸键盘和分线板的驱动程序.
* [micropython-ttp223](https://github.com/mcauser/micropython-ttp223) - 使用 TTP223 电容式触控模块的示例.

#### Touch Resistive

* [XPT2046-touch-pad-driver](https://github.com/robert-hh/XPT2046-touch-pad-driver) - 许多TFT模块中使用的XPT2046触摸板控制器的驱动程序.

### Scheduling

* [micropython-mcron](https://github.com/fizista/micropython-mcron) - MicroCRON 是一个基于时间的 MicroPython 任务调度程序.

### Storage

#### Database

* [uPyMySQL](https://github.com/dvrhax/uPyMySQL) - 纯 uPython MySQL 客户端.
* [micropython-redis](https://github.com/dwighthubbard/micropython-redis) - 设计用于 MicroPython 的 redis 客户端实现.
* [picoredis](https://github.com/SpotlightKid/picoredis) - 用于 MicroPython 的非常小的 Redis 客户端（不仅）.
* [micropg](https://github.com/nakagami/micropg) - 用于 MicroPython 的 PostgreSQL 数据库驱动程序.
* [nmongo](https://github.com/nakagami/nmongo) - 用于 CPython 和 MicroPython 的 MongoDB 客户端，具有类似 API 的 mongo shell.

#### EEPROM

* [micropython_eeprom](https://github.com/peterhinch/micropython_eeprom) - 用于非易失性存储芯片（EEPROM、FRAM、闪存）的 MicroPython 设备驱动程序.

#### FRAM

* [micropython-fram](https://github.com/rolandvs/micropython-fram) - Pyboard driver for Ferroelectric RAM module.

## Community

* [MicroPython Forum](https://forum.micropython.org/) - 超过 6400 名用户的在线社区讨论与 MicroPython 相关的所有事情.
* [MicroPython on Twitter](https://twitter.com/micropython?lang=en) - 在 Twitter 上关注 MicroPython 以获取最新消息和更新.
* [MicroPython on Facebook](https://www.facebook.com/micropython) - Like MicroPython on Facebook for competitions, news and updates.
* [Melbourne MicroPython Meetup](https://www.meetup.com/en-AU/MicroPython-Meetup) - 在澳大利亚墨尔本的 CCHS 定期聚会.
* [Slack](https://slack-micropython.herokuapp.com/) - 自动邀请到 micropython.slack.com 工作区.
* [Discord](https://discord.gg/qw7d8bv) - 获得 MicroPython Discord 服务器的邀请.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](http://shop.oreilly.com/product/0636920056515.do)  - Nicholas H. Tollervey.  ISBN 9781491972731.
* [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://www.apress.com/gp/book/9781484231227)  - 查尔斯·贝尔. 国际标准书号 9781484231227.
* [MicroPython Cookbook](https://www.packtpub.com/au/application-development/micropython-cookbook)  - Marwan Alsabbagh. 国际标准书号 9781838649951.
* [Python for Microcontrollers: Getting Started with MicroPython](https://www.amazon.com.au/Python-Microcontrollers-Getting-Started-MicroPython/dp/1259644537)  - 唐纳德诺里斯.  ISBN 9781259644535.
* [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937)  - 尤里·玛格达. 国际标准书号 9781090900937.
* [MicroPython Projects](https://www.packtpub.com/au/iot-hardware/micropython-projects)  - 雅各布·贝宁戈.  ISBN 9781789958034.
* [Get Started with MicroPython on Raspberry Pi Pico](https://store.rpipress.cc/products/get-started-with-micropython-on-raspberry-pi-pico)  - 作者 Gareth Halfacree 和 Ben Everard.  ISBN 9781912047864.
* [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book)  - 作者：君特斯潘纳.  ISBN 9783895764370.
* [MicroPython For Everyone: How To Use ESP32 And ESP8266: Micropython Mqtt](https://www.amazon.com/MicroPython-Everyone-ESP32-ESP8266-Micropython/dp/B094281XK1)  - 梅森·米莱特.  ISBN 9798748248822.

## Frameworks

* [micrOS](https://github.com/BxNxM/micrOS) - 基于 MicroPython 的物联网框架.
* [terkin-datalogger](https://github.com/hiveeyes/terkin-datalogger) - 适用于 MicroPython 和 CPython 的灵活数据记录器应用程序.

## Resources

* [MicroPython](http://micropython.org)  - 项目网站. 试驾pyboard. 使用 unicorn 在线试用 MicroPython.
* [MicroPython on GitHub](https://github.com/micropython/micropython) - 在 GitHub 上提交错误报告、关注并参与开发.
* [MicroPython Official Documentation](http://docs.micropython.org/) - 对于各种端口，包括快速参考、一般信息、示例和教程.
* [MicroPython Wiki](http://wiki.micropython.org/Home) - 社区生成的 MicroPython 和 pyboard 功能的文档和示例.
* [MicroPython Newsletter](http://micropython.org/newsletter) - 订阅 MicroPython 时事通讯，获取包括新功能和新产品在内的新闻和公告.
* [MicroPython Store](https://store.micropython.org/) - 在哪里可以买到 pyboard、外壳、皮肤、书籍、连接器和外围设备.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) - 维基百科上的 MicroPython.

## Development

### Code Generation

* [micropy-cli](https://github.com/BradenM/micropy-cli) - Micropy Cli 是一个项目管理/生成工具，用于在 VSCode 等现代 IDE 中编写 MicroPython 代码.
* [micropython-stubber](https://github.com/Josverl/micropython-stubber) - 为不同的 MicroPython 固件生成和使用存根以与 vscode 和/或 pylint 一起使用.
* [micropy-stubs](https://github.com/BradenM/micropy-stubs) - 为 Micropy-Cli 和其他任何人自动生成的存根包.

### Debugging

* [esp32-backtrace](https://github.com/tve/esp32-backtrace) - ESP32 异常堆栈回溯分析器.

### IDEs

* [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) - IntelliJ 和 PyCharm 中的 MicroPython 设备插件.
* [Micropython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) - 用于 VSCode README 的 MicroPython IDE.
* [Micropython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) - 与 MicroPython REPL 终端交互的便捷快捷方式.
* [Mu Editor](https://codewith.mu/) -  Code with Mu: a simple Python\MicroPythonb\CircuitPython editor for beginner programmers.
* [Thonny IDE](https://thonny.org/) - Thonny：适合初学者的 Python IDE.

### Shells

#### On Device

* [upy-shell](https://github.com/dhylands/upy-shell) - 一个简单的基于命令行的 MicroPython 外壳.
* [Micropython-Editor](https://github.com/robert-hh/Micropython-Editor) - 用 Python 编写的用于 PyBoard、WiPy、ESP8266、ESP32、PyCom 和 Adafruit 设备的小型板载编辑器.

#### On Host

* [rshell](https://github.com/dhylands/rshell) - 将文件复制或同步到板，从您的终端输入 REPL.
* [ampy](https://github.com/scientifichackers/ampy) - Adafruit MicroPython 工具 - 通过串行连接与 MicroPython 板交互的实用程序.
* [mpfshell](https://github.com/wendlers/mpfshell) - 一个用于 ESP8266 和 WiPy 的基于 shell 的简单文件浏览器.
* [mpsync](https://github.com/Uhlo/mpsync) - 一个小工具，可在检测到更改时将文件夹同步到 MicroPython 板.

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 名支持者承诺提供 97,803 英镑以帮助实现该项目.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 名支持者承诺提供 28,534 英镑以帮助实现该项目.

## Contributing

总是欢迎贡献和建议！ 请看一下 [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) 第一的.

如果我不确定这些库是否很棒，我将保留一些拉取请求，您可以通过添加它们来投票支持它们.
