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

精选的很棒的MicroPython库，框架，软件和资源的列表.

[MicroPython](http://micropython.org/) 是Python 3编程语言的一种精简而高效的实现，其中包括Python标准库的一小部分，并且经过优化可在微控制器和受限环境中运行.



## Libraries

您可以在其他地方找到MicroPython库：

* [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython)  -此过滤器仅显示PyPi上的MicroPython库. 注意：您不能通过pip安装micropython库. 看 [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html?highlight=upip) 有关upip的更多信息.
* [GitHub Search](https://github.com/search?q=micropython) -在GitHub上搜索包含MicroPython的存储库.
* [GitHub Topic - MicroPython](https://github.com/topics/micropython) -浏览GitHub主题以查找标记有MicroPython的项目.
* [Libraries.io](https://libraries.io/search?q=micropython) -Libraries.io查询MicroPython.
* [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc&utf8=%E2%9C%93&name=micropython&sort=latest_activity_desc) -在GitLab上浏览存储库.

### AI

* [MicroMLP](https://github.com/jczic/MicroMLP) -用于MicroPython的微神经网络多层感知器（用于ESP32和Pycom模块）.

### Analytics

* [uMath](https://github.com/AaronKel/uMath) -微控制器的计算机代数.
* [micropython-ulab](https://github.com/v923z/micropython-ulab) -适用于MicroPython的类似numpy的快速向量模块.
* [micropython-fourier](https://github.com/peterhinch/micropython-fourier) -MicroPython的嵌入式ARM汇编器中的快速傅立叶变换.
* [ulinalg](https://github.com/jalawson/ulinalg) -小型矩阵处理模块，具有一些专门用于MicroPython（Python3）的线性代数运算.
* [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) -MicroPython上的快速矩阵乘法和线性求解器.
* [micropython-vec](https://gitlab.com/nickoala/micropython-vec) -MicroPython上的向量运算.

### Audio

* [JQ6500](https://github.com/rdagger/micropython-jq6500) -JQ6500 UART MP3模块的驱动程序.
* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) -DFPlayer Mini和Grove MP3 v2.0使用的KT403A驱动程序.
* [micropython-buzzer](https://github.com/fruch/micropython-buzzer) -在蜂鸣器上播放诺基亚合成和中音文件.
* [micropython-dfplayer](https://github.com/ShrimpingIt/micropython-dfplayer) -使用UART的DFPlayer Mini驱动程序.
* [micropython-longwave](https://github.com/MattMatic/micropython-longwave) -MicroPython开发板的WAV播放器.
* [micropython-vs1053](https://github.com/peterhinch/micropython-vs1053) -VS1053b MP3播放器的异步驱动程序.
* [micropython-midi](https://github.com/cjbarnes18/micropython-midi) -MicroPython的Midi实现示例.
* [upy-rtttl](https://github.com/dhylands/upy-rtttl) -铃声文本传输语言（RTTTL）的Python分析器.

### Communications

#### Bluetooth

* [PyBoard-HC05-Android](https://github.com/KipCrossing/PyBoard-HC05-Android) -Pyboard HC05蓝牙适配器示例应用程序.

#### CAN

* [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) -Spacecan是用于嵌入式系统的SpaceCAN协议的MicroPython实现.

#### Cryptography

* [mpyaes](https://github.com/iyassou/mpyaes) -用于AES加密的MicroPython模块.
* [micropython-aes](https://github.com/piaca/micropython-aes) -带有纯python实现的AES算法.

#### DNS

* [ICantBelieveItsNotDNS](https://github.com/yschaeff/ICantBelieveItsNotDNS)  -“我不敢相信这不是DNS！”  （ICBIND）是用MicroPython编写的ESP8266的权威DNS服务器.
* [MicroDNSSrv](https://github.com/jczic/MicroDNSSrv) -用于MicroPython的微型DNS服务器，可以简单地响应带有或不带有通配符的多域上的A查询（用于Pycom模块和ESP32）.

#### Ethernet

* [Official wiznet5k](https://github.com/micropython/micropython/tree/master/drivers/wiznet5k) -WIZnet5x00系列以太网控制器的官方驱动程序.

#### FTP

* [micropython-ftplib](https://github.com/SpotlightKid/micropython-ftplib) -用于MicroPython的FTP客户端库.
* [FTP-Server-for-ESP8266-ESP32-and-PYBD](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) -适用于MicroPython平台的ESP8266 / ESP32 / PYBD的小型FTP服务器.
* [MicroFTPServer](https://github.com/cpopp/MicroFTPServer) -可以在带有MicroPython的ESP8266上运行的最小FTP服务器.

#### GPS

* [micropyGPS](https://github.com/inmcm/micropyGPS) -功能齐全的GPS NMEA句子解析器.
* [micropython-gnssl76l](https://github.com/tuupola/micropython-gnssl76l) -用于Quectel GNSS L76-L（GPS）的MicroPython I2C驱动程序.
* [mpy-agps](https://github.com/pulkin/mpy-agps) -辅助位置服务（AGPS）的MicroPython实现.

#### GSM

* [micropython-upyphone](https://github.com/jeffmer/micropython-upyphone) -使用pyboard和sim800l的gsm手机.

#### IoT

* [microhomie](https://github.com/microhomie/microhomie) -用于物联网的Homie MQTT约定的MicroPython实现.
* [uPyEcho](https://github.com/lemariva/uPyEcho) -在ESP32上使用MicroPython仿真的Belkin WeMo设备，可与Amazon Echo（Alexa）一起使用.
* [SonosRemote](https://github.com/foosel/SonosRemote) -用于在ESP8266上运行并使用Sonos HTTP API的Sonos安装的遥控器.
* [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) -基于MicroPython的脚本，可扩展您的家庭助理驱动的家庭自动化项目.

#### IR

* [micropython-necir](https://github.com/MattMatic/micropython-necir) -用于TL1838红外接收器LED的NEC红外捕获.
* [Micropython-IR](https://github.com/designerPing/Micropython-IR) -Pyboard红外遥控嗅探和重放.
* [micropython_ir](https://github.com/peterhinch/micropython_ir) -非阻塞设备驱动程序，可从IR远程接收和用于IR“ blaster”应用程序.
* [micropython-amg88xx](https://github.com/peterhinch/micropython-amg88xx) -Grid-EYE热红外阵列传感器（Adafruit 3538）的驱动程序.
* [micropython-ys-irtm](https://github.com/mcauser/micropython-ys-irtm) -用于YS-IRTM 5V NEC红外UART收发器的MicroPython示例.
* [esp8266_ir](https://github.com/ruoyu0088/esp8266_ir) -通过websocket控制IR信号.

#### LoRaWAN

* [uPyLoRaWAN](https://github.com/lemariva/uPyLoRaWAN) -使用MicroPython的ESP32符合LoRa和LoRaWAN.
* [DeLoReAN](https://github.com/buehl/DeLoReAN) -DeLoReAN是（专用）（Lo）RaWAN节点（重新）编码（A）ny（N）FC标签.

#### MDNS

* [micropython-mdns](https://github.com/cbrand/micropython-mdns) -MDNS的纯python实现，支持服务发现.

#### MQTT

* [micropython-mqtt](https://github.com/peterhinch/micropython-mqtt)  -“弹性”异步MQTT驱动程序. 加上一种使用ESP8266将MQTT带到非联网目标的方法.
* [MQBoard](https://github.com/tve/mqboard) -在MicroPython板上（主要在ESP32上）使用MQTT和asyncio的微框架.
* [pysmartnode](https://github.com/kevinkk525/pysmartnode) -MicroPython Smarthome框架.
* [umqtt_aws_iot](https://github.com/juwul/umqtt_aws_iot) -使用MicroPython将UMQTT消息发布到AWS IoT.
* [sonoff-mqtt by davea](https://github.com/davea/sonoff-mqtt) -使用MQTT来控制Sonoff / ESP8266的MicroPython脚本.
* [micropython-sonoff-switch](https://github.com/kfricke/micropython-sonoff-switch) -使用MicroPython为iTead Sonoff开关实现了MQTT可控开关.
* [micropython-thingspeak-mqtt-esp8266](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) -使用带有在ESP8266 / ESP32平台上运行的MicroPython的MQTT发布和订阅Thingspeak.
* [uMQTT](https://github.com/andrewmk/uMQTT) -MQTT在WiPy板上为MicroPython发布.

#### NTP

* [esp8266_ntp_webserver](https://github.com/Roterfux/esp8266_ntp_webserver) -MicroPython + esp8266 + ntp +网络服务器
* [micropython-ntpd](https://github.com/dave2/micropython-ntpd) -MicroPython中ntpd的实现.
* [micropython_ntpserver](https://github.com/GrantGMiller/micropython_ntpserver) -为MicroPython编写的NTP服务器.
* [micropython-ntpclient](https://github.com/wieck/micropython-ntpclient) -使用uasyncio的MicroPython的NTP客户端.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython/tree/master/drivers/onewire) -对于使用OneWire总线的设备，例如Dallas ds18x20.

#### Onkyo EISCP

* [eiscp-micropython](https://github.com/cbrand/eiscp-micropython) -先锋使用的Onkyo-EISCP协议的Micropython端口.

#### Radio

* [micropython-radio](https://github.com/peterhinch/micropython-radio) -nRF24L01 2.4Ghz无线电模块的协议.
* [micropython-rfsocket](https://github.com/wuub/micropython-rfsocket) -流行的基于433MHz的RFSocket的MicroPython实现.
* [Official nRF24L01](https://github.com/micropython/micropython/tree/master/drivers/nrf24l01) -nRF24L01 2.4Ghz无线电模块的官方驱动程序.
* [micropython_remote](https://github.com/peterhinch/micropython_remote)  -捕获并重播433MHz远程控制代码. 控制远程开关电源适配器.
* [micropython-ys-rf34t](https://github.com/mcauser/micropython-ys-rf34t) -使用YS-RF34T 433MHz ASK / OOK UART收发器的MicroPython示例.

#### REPL

* [webrepl](https://micropython.org/webrepl) -MicroPython WebREPL.
* [zepl](https://gitlab.com/zepl1/zepl) -使用ZeroMQ的MicroPython WebREPL控制台应用程序.
* [jupyter_micropython_remote](https://gitlab.com/alelec/jupyter_micropython_remote) -Jupyter内核，可通过串行/网络REPL在MicroPython板上直接执行代码.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) -NXP MFRC522 RFID读取器/写入器的驱动程序.
* [micropython-wiegand](https://github.com/pjz/micropython-wiegand) -Wiegand协议阅读器.

#### RTC

* [micropython-tinyrtc-i2c](https://github.com/mcauser/micropython-tinyrtc-i2c) -DS1307 RTC和AT24C32N EEPROM的驱动程序.
* [Micropython_TinyRTC](https://github.com/AnthonyKNorman/Micropython_TinyRTC) -DS1307 RTC的驱动程序.
* [micropython-mcp7940](https://github.com/mattytrentini/micropython-mcp7940) -Microchip MCP7940 RTC的驱动程序.

#### Serial

* [mpy-miniterm](https://github.com/jeffmakes/mpy-miniterm) -通过串行REPL与MicroPython设备进行无缝串行调试和文件同步的工具.
* [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) -modbus-tk的MicroPython端口.

#### SMTP

* [uMail](https://github.com/shawwwn/uMail) - A lightweight, scalable SMTP client for sending email in MicroPython.

#### Telnet

* [MicroTelnetServer](https://github.com/cpopp/MicroTelnetServer) -用于MicroPython和ESP8266的简单telnet服务器，允许telnet客户端访问REPL.

#### WiFi

* [HueBridge](https://github.com/FRC4564/HueBridge) -飞利浦色相桥.
* [micropython-wifimanager](https://github.com/mitchins/micropython-wifimanager) -ESP8266开发板上的MicroPython的简单网络配置实用程序.

#### Web

* [MicroWebSrv](https://github.com/jczic/MicroWebSrv) -微型HTTP Web服务器，支持用于MicroPython的WebSocket，html / python语言模板和路由处理程序（用于Pycom模块和ESP32）.
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) -最后一款用于IoT（MicroPython）或大型服务器（CPython）的微型Web服务器，支持WebSocket，路由，模板引擎，并具有真正优化的架构（内存分配，异步I / O）.
* [tinyweb](https://github.com/belyalov/tinyweb) -适用于MicroPython的简单轻便的HTTP异步服务器.
* [upy-websocket-server](https://github.com/BetaRavener/upy-websocket-server) -MicroPython（ESP8266）Websocket服务器实现.
* [micropython-captive-portal](https://github.com/amora-labs/micropython-captive-portal) -用于MicroPython的强制门户演示.
* [uPyPortal](https://github.com/lemariva/uPyPortal) -使用ESP32（WeMos）的MicroPython专属门户.
* [ESP8266WebServer](https://github.com/codemee/ESP8266WebServer) -适用于MicroPython的ESP8266 Web服务器.
* [microCoAPy](https://github.com/insighio/microCoAPy) -MicroPython中CoAP（受限应用协议）的微型客户端/服务器实现.
* [micropyserver](https://github.com/troublegum/micropyserver) -MicroPyServer是用于MicroPython项目的简单HTTP服务器.
* [MicroRESTCli](https://github.com/jczic/MicroRESTCli) -基于MicroWebCli for MicroPython的微型JSON REST Web客户端（用于Pycom模块和ESP32）.
* [micropython-noggin](https://github.com/larsks/micropython-noggin) - A very simple web server for MicroPython.
* [uwebsockets](https://github.com/danni/uwebsockets) -适用于ESP8266的MicroPython websockets实现.
* [microdot](https://github.com/miguelgrinberg/microdot) -MicroPython的小型Web框架.
* [micropython-utelegram](https://github.com/jordiprats/micropython-utelegram) -MicroPython的电报API包装器.

#### Zigbee

* [ZbPy](https://github.com/osresearch/ZbPy) -MicroPython IEEE802.15.4 / Zigbee解析器.

### Display

#### E-Paper

* [micropython-epaper](https://github.com/peterhinch/micropython-epaper) -适用于Embedded Artists 2.7英寸电子纸显示屏的Pyboard驱动程序.
* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) -SSD1606有源矩阵电子纸显示屏128x180.
* [micropython-waveshare-epaper](https://github.com/mcauser/micropython-waveshare-epaper) -各种Waveshare电子纸模块的驱动程序.
* [micropython-waveshare-epd](https://github.com/ayoy/micropython-waveshare-epd) -Waveshare电子纸显示驱动程序，用于运行带有Pycom风格的MicroPython的设备.
* [ssd1675a](https://github.com/mattytrentini/ssd1675a) -基于SSD1675的电子纸显示屏的驱动程序.

#### GUI

* [lvgl](https://github.com/lvgl/lv_binding_micropython) -具有MicroPython绑定的基于对象的基于组件的高级GUI库.
* [micropython-lcd160cr-gui](https://github.com/peterhinch/micropython-lcd160cr-gui) -用于Pyboard和LCD160CR彩色显示屏的基于事件的简单触摸驱动GUI.
* [micropython_ra8875](https://github.com/peterhinch/micropython_ra8875) -基于RA8875的显示器的MicroPython设备驱动程序和nano-GUI.
* [micropython-nano-gui](https://github.com/peterhinch/micropython-nano-gui)  -Nano-Gui为显示器的驱动程序从framebuf类子类化的显示器提供了一组有限的GUI对象（小部件）. 其中包括LCD和OLED显示器.

#### LCD Character

* [Grove_RGB_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) -SeeedStudio的Grove RGB LCD驱动程序.
* [lcdi2c](https://github.com/slothyrulez/lcdi2c) -兼容HD44780的点矩阵LCD的驱动程序.
* [micropython-charlcd](https://github.com/rdagger/micropython-charlcd) -用于HD44780兼容LCD的驱动程序.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) -I2C 2x16 LCD屏幕的驱动程序.
* [pyboard-LCD-character-display](https://github.com/scitoast/pyboard-LCD-character-display) -兼容HDD44780的1602 LCD的PyBoard驱动程序.
* [python_lcd](https://github.com/dhylands/python_lcd) -兼容HD44780的点矩阵LCD的驱动程序.
* [micropython-lcd](https://github.com/wjdp/micropython-lcd) -用于从MicroPython pyboard控制HD44780的类.

#### LCD Graphic

* [micropython-lcd-AQM1248A](https://github.com/forester3/micropython-lcd-AQM1248A) -适用于AQM1248A图形LCD的ESP8266驱动程序.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) -诺基亚5110 PCD8544 84x48 LCD模块的驱动程序.
* [micropython-st7565](https://github.com/nquest/micropython-st7565) -ST7565 128x64 LCD的驱动程序.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) -使用ESP8266和SPI的ST7920 128x64单色LCD面板上的简单图形基元的库.
* [MicroPython_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) -ESP8266驱动程序用于Nokia 5110 PCD8544.
* [Official LCD160CR](https://github.com/micropython/micropython/tree/master/drivers/display) -带有电阻式触摸传感器的官方MicroPython LCD160CR显示器的驱动程序.
* [micropython-hx1230](https://github.com/mcauser/micropython-hx1230) -用于HX1230 96x68 LCD模块的MicroPython库.

#### LCD TFT

* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) -用于TFT显示器的驱动程序集合，ILI9341，SH1106，SSD1606，ST7735.
* [micropython-ili934x](https://github.com/tuupola/micropython-ili934x) -基于ILI934X系列的TFT / LCD显示器的SPI驱动程序.
* [MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735) -GuyCarvers的ST7735 TFT LCD驱动器的ESP32版本.
* [micropython-st7735](https://github.com/hosaka/micropython-st7735) -ST7735 TFT LCD的驱动程序.
* [MicroPython_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735) -ST7735 128x128 TFT的驱动程序.
* [SSD1963-TFT-Library-for-PyBoard-and-RP2040](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) -用于PyBoard和Raspberry Pi PICO的SSD1963 TFT库.
* [ST7735](https://github.com/GuyCarver/MicroPython/blob/master/lib/ST7735.py) -ST7735 TFT LCD的驱动程序.
* [micropython-ili9341](https://github.com/rdagger/micropython-ili9341) -MicroPython ILI9341显示屏和XPT2046触摸屏驱动程序.
* [st7789_mpy](https://github.com/devbis/st7789_mpy) -适用于MicroPython的快速纯C驱动程序，可以处理ST7789芯片上的显示模块.
* [st7789py_mpy](https://github.com/devbis/st7789py_mpy) -使用MicroPython编写的240x240 ST7789显示器的慢速MicroPython驱动程序，无需使用Ali Express的CS引脚即可显示.
* [micropython-ili9341](https://github.com/jeffmer/micropython-ili9341) -用于ILI9341的MicroPython驱动程序.
* [micropython-ili9341](https://github.com/tkurbad/micropython-ili9341) -ESP32上用于MicroPython的ILI9341 TFT驱动程序.

#### LED Matrix

* [micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c) -HT1632C 32x16双色LED矩阵的驱动器.
* [micropython-matrix8x8](https://github.com/JanBednarik/micropython-matrix8x8) -带HT16K33背包的AdaFruit 8x8 LED矩阵显示器的驱动程序.
* [micropython-max7219](https://github.com/mcauser/micropython-max7219) -MAX7219 8x8 LED矩阵模块的驱动器.
* [micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield) -使用TM1640芯片的Wemos D1 Mini Matrix LED屏蔽驱动器.
* [micropython-wemos-led-matrix](https://github.com/mattytrentini/micropython-wemos-led-matrix) -使用TM1640芯片的Wemos D1 Mini Matrix LED屏蔽驱动器.
* [micropython-max7219](https://github.com/vrialland/micropython-max7219) -用于MAX7219 8x8 LED矩阵的MicroPython驱动程序.

#### LED Segment

* [LKM1638](https://github.com/arikb/LKM1638) -基于TM1638控制器的JY-LKM1638显示驱动程序.
* [max7219_8digit](https://github.com/pdwerryhouse/max7219_8digit) -MAX7219 8位7段LED模块驱动器.
* [micropython-max7219](https://github.com/JulienBacquart/micropython-max7219) -MAX7219 8位7段LED模块驱动器.
* [micropython-my9221](https://github.com/mcauser/micropython-my9221) -MY9221 10段LED条形图模块的驱动程序.
* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) -用于TM1637四路7段LED模块的驱动器.
* [micropython-tm1638](https://github.com/mcauser/micropython-tm1638) -带开关的TM1638双四极7段LED模块的驱动器.
* [micropython-tm1640](https://github.com/mcauser/micropython-tm1640) -用于TM1740 8x8 LED矩阵模块的驱动程序.
* [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) -MicroPython库，用于由TM1640控制的16位7段显示器.
* [TM74HC595](https://github.com/Sakartu/TM74HC595) -移位寄存器控制的5针显示模块的驱动器.

#### LEDs

* [micropython-morsecode](https://github.com/mampersat/micropython-morsecode) -用摩尔斯电码消息闪烁LED.
* [micropython-p9813](https://github.com/mcauser/micropython-p9813) -SeeedStudio的Grove可链接RGB LED中使用的P9813 RGB LED驱动器.
* [micropython-ws2812-7seg](https://github.com/HubertD/micropython-ws2812-7seg) -使用WS2812 RGB LED的7段显示器.
* [micropython-ws2812](https://github.com/JanBednarik/micropython-ws2812) -WS2812 RGB LED的驱动器.
* [Official APA102](http://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) -ESP8266 APA102 / DotStar RGB LED驱动器.
* [Official WS2811](http://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) -ESP8266 WS2811 / NeoPixel RGB LED驱动器.
* [tlc5940-micropython](https://github.com/oysols/tlc5940-micropython) -TLC5940 16通道LED驱动器的驱动器.
* [ws2812-SPI](https://github.com/nickovs/ws2812-SPI) -高效的micropython WS2812（NeoPixel）驱动程序.
* [micropython-ws2801](https://github.com/HeMan/micropython-ws2801) -一个MicroPython库，用于与WS2801 RGB LED串连接.
* [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) -TLC5947 24通道12位PWM LED驱动器的驱动器.

#### OLED

* [Grove_OLED](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) -SeeedStudio的Grove OLED Display 1.12“ v1.0使用的SSD1327驱动程序.
* [micropython-oled](https://github.com/mcauser/deshipu-micropython-oled) -单色OLED显示器，PCD8544，SH1106，SSD1306，UC1701X的驱动程序集合.
* [micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327) -SSD1327 128x128 4位灰度OLED显示器的驱动程序.
* [micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351) -SSD1351 OLED显示器的驱动程序.
* [MicroPython_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306) -适用于SSD1306 OLED 128x64显示器的ESP8266驱动程序.
* [Official SSD1306](https://github.com/micropython/micropython/tree/master/drivers/display) -SSD1306 128x64 OLED显示器的驱动程序.
* [SH1106](https://github.com/robert-hh/SH1106) -SH1106 OLED显示器的驱动程序.

### IO

#### ADC

* [ads1x15](https://github.com/robert-hh/ads1x15) -ADS1015 / ADS1115 ADC，I2C接口的驱动程序.
* [micropython-ads1015](https://github.com/mcauser/deshipu-micropython-ads1015) -ADS1015 12位和ADS1115 16位ADC，具有可编程增益的4通道I2C接口.
* [Micropython_ADS1115](https://github.com/AnthonyKNorman/Micropython_ADS1115) -ADS1115 16位ADC，具有可编程增益的4通道I2C接口.
* [ADS7818](https://github.com/robert-hh/ADS7818) -与ADS7818 AD转换器接口的Python类.
* [micropython-ads1219](https://github.com/miketeachman/micropython-ads1219) -适用于德州仪器（TI）ADS1219 ADC的MicroPython模块.
* [micropython-hx711](https://github.com/SergeyPiskunov/micropython-hx711) -用于HX711 24位模数转换器的MicroPython驱动程序.
* [MicroPython-ADC_Cal](https://github.com/matthias-bs/MicroPython-ADC_Cal) -ESP32 ADC驱动器使用来自漏电的参考电压校准值.

#### DAC

* [micropython-mcp4725](https://github.com/wayoda/micropython-mcp4725) -MCP4725 I2C DAC的驱动器.
* [mcp4728](https://github.com/openfablab/mcp4728) -Microchip MCP4728 I2C 12位四通道DAC的帮助程序库.

#### GPIO

* [micropython-inputs](https://github.com/alanmitchell/micropython-inputs) -用于对脉冲进行计数，对数字输入进行去抖动以及为MicroPython板计算模拟输入的移动平均值的类.
* [ubutton](https://gitlab.com/WiLED-Project/ubutton) -一个MicroPython库，用于控制按钮输入的读取和去抖，包括“短”和“长”按下回调.
* [micropython-debounce-switch](https://github.com/selfhostedhome/micropython-debounce-switch) -用于反跳开关的MicroPython类.

#### IO-Expander

* [MCP23017-ESP8266-Miniature-Driver](https://github.com/forkachild/MCP23017-ESP8266-Miniature-Driver) -MCP23017 16位I / O扩展器的驱动程序.
* [micropython-mcp230xx](https://github.com/ShrimpingIt/micropython-mcp230xx) -用于MCP23017和MCP23008 GPIO扩展器的驱动程序.
* [micropython-mcp23017](https://github.com/mcauser/micropython-mcp23017) -适用于MCP23017 16位I / O扩展器的MicroPython驱动程序.
* [micropython-pcf8574](https://github.com/mcauser/micropython-pcf8574) -用于带中断的PCF8574 8位I2C I / O扩展器的MicroPython驱动程序.
* [micropython-pcf8575](https://github.com/mcauser/micropython-pcf8575) -用于带中断的PCF8575 16位I2C I / O扩展器的MicroPython驱动程序.
* [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) -用于PCF8591 8位I2C I / O扩展器的MicroPython驱动程序.
* [micropython-74hc595](https://github.com/mcauser/micropython-74hc595) -用于74HC595 8位移位寄存器的MicroPython驱动程序.

#### Joystick

* [micropython-nunchuck](https://github.com/kfricke/micropython-nunchuck) -Nunchuk游戏控制器的驱动程序，I2C接口.

#### PWM

* [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) -MicroPython库，用于在异步循环中控制PWM输出，具有衰落和闪烁的功能.

#### Rotary Encoder

* [micropython-rotary](https://github.com/miketeachman/micropython-rotary) -MicroPython模块，用于读取旋转编码器.
* [uencoder](https://gitlab.com/WiLED-Project/uencoder) -用于从旋转编码器读取的MicroPython库.
* [encodermenu](https://github.com/sgall17a/encodermenu) -使用旋转编码器和基本显示器的Micropython的简单GUI菜单.

#### Waveform Generator

* [Micropython-AD9833](https://github.com/KipCrossing/Micropython-AD9833) -AD9833的SPI驱动程序，SPI接口.

### Motion

#### DC Motor

* [L298N](https://github.com/GuyCarver/MicroPython/blob/master/lib/L298N.py) -L298N双H桥电机控制器的驱动程序.

#### Servo

* [micropython-pca9685](https://github.com/mcauser/deshipu-micropython-pca9685) -16通道12位PWM /伺服驱动器.

#### Stepper

* [micropython-upybbot](https://github.com/jeffmer/micropython-upybbot) -用于双极步进电机的A4988驱动器.
* [uln2003](https://github.com/IDWizard/uln2003) -用于5V 28BYJ-48步进电机的驱动器.
* [micropython-multiaxis](https://gitlab.com/olivier.len02/micropython-multiaxis) -具有MicroPython ESP32和DRV8825的多轴.
* [ticlib](https://github.com/jphalip/ticlib) -Pololu Tic步进电机控制器的驱动程序.

### Sensors

#### Accelerometer Digital

* [ADXL345-with-Pyboard](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) -ADXL345 16g 3轴加速度计的驱动程序.
* [adxl345_micropython](https://github.com/fanday/adxl345_micropython) -ADXL345 16g 3轴加速度计的驱动程序.
* [micropython-lis2hh12](https://github.com/tuupola/micropython-lis2hh12) -用于LIS2HH12 3轴加速度计的I2C驱动器.
* [MMA7660](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) -MMA7660 1.5克3轴加速度计的驱动程序.

#### Air Quality

* [CCS811](https://github.com/Ledbelly2142/CCS811) -CCS811空气质量传感器.
* [upython-aq-monitor](https://github.com/ayoy/upython-aq-monitor) -使用PMS5003传感器和WiPy的空气质量监测仪.
* [micropython-pms7003](https://github.com/pkucmus/micropython-pms7003) -用于PMS7003空气质量传感器的MicroPython驱动程序.
* [pms5003_micropython](https://github.com/kevinkk525/pms5003_micropython) -适用于MicroPython的pms5003空气质量传感器的驱动程序.
* [micropython-pms5003-minimal](https://github.com/miketeachman/micropython-pms5003-minimal) -适用于MicroPython的pms5003空气质量传感器的驱动程序.
* [polly](https://github.com/g-sam/polly) -SDS011污染传感器+ Wemos D1 mini pro + MicroPython.

#### Barometer

* [micropython-bme280](https://github.com/kevbu/micropython-bme280) -博世BME280温度/压力/湿度传感器的驱动器.
* [micropython-bmp180](https://github.com/micropython-IMU/micropython-bmp180) -博世BMP180温度，压力和高度传感器的驱动程序.
* [mpy_bme280_esp8266](https://github.com/catdog2/mpy_bme280_esp8266) -博世BME280温度/压力/湿度传感器.
* [BME280](https://github.com/robert-hh/BME280) -针对BME280传感器的MicroPython驱动程序，目标平台为Pycom设备.
* [micropython-bmp280](https://github.com/dafvid/micropython-bmp280) -BMP280传感器的模块.

#### Camera

* [micropython-ov2640](https://github.com/namato/micropython-ov2640) -OV2640相机的MicroPython类.
* [Nikon-Trigger-for-MicroPython](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython)  -使用IR LED的尼康相机的远程触发器. 对于PyBoard v1.1.
* [micropython-camera-driver](https://github.com/lemariva/micropython-camera-driver) -ESP32上适用于MicroPython的OV2640相机驱动程序.

#### Compass

* [micropython-esp8266-hmc5883l](https://github.com/gvalkov/micropython-esp8266-hmc5883l) -ESP8266上的3轴数字罗盘.
* [QMC5883](https://github.com/robert-hh/QMC5883) -QMC5883三轴数字罗盘IC的Python类.

#### Current

* [micropythonINA219](https://github.com/kabel42/micropythonINA219) -INA219电流传感器的驱动器.
* [pyb_ina219](https://github.com/chrisb2/pyb_ina219) -INA219电流传感器的驱动器.

#### Distance IR

* [micropython-gp2y0e03](https://github.com/mcauser/deshipu-micropython-gp2y0e03) -使用Sharp GP2Y0E03的IR-LED测距传感器.
* [micropython-vl6180](https://github.com/mcauser/deshipu-micropython-vl6180) -飞行时间传感器，环境光传感器和红外发射器.

#### Distance Laser

* [micropython-vl53l0x](https://github.com/mcauser/deshipu-micropython-vl53l0x) -飞行时间激光测距传感器.
* [Qwiic_TOF_Module_RFD77402](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) -Qwiic TOF模块（RFD77402）飞行时间测距模块.

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) -HC-SR04超声波距离传感器的驱动程序.

#### Energy

* [ATM90E26_Micropython](https://github.com/whatnick/ATM90E26_Micropython) -ATM90E26电能计量设备的驱动程序.
* [MCP39F521](https://github.com/warpme/MCP39F521) -用于读取MCP39F521电源监视器的ESP8266脚本.

#### Gaseous

* [micropython-MQ](https://github.com/kartun83/micropython-MQ) -MQ系列气体传感器的驱动程序.
* [MQ135](https://github.com/rubfi/MQ135) -MQ135气体传感器的驱动程序.
* [CCS811](https://github.com/Notthemarsian/CCS811) -ESP8266开发板上CCS811的基本MicroPython驱动程序.
* [micropython-scd30](https://github.com/agners/micropython-scd30) -用于Sensirion SCD30 CO2传感器模块的MicroPython I2C驱动程序.

#### Light

* [MicroPython-SI1145](https://github.com/neliogodoi/MicroPython-SI1145) -SI1145紫外线指数，IR，可见光和接近传感器.
* [micropython-tsl2561](https://github.com/kfricke/micropython-tsl2561) -TAOS / ams的TSL2561照明传感器驱动程序.
* [mpy_bh1750fvi_esp8266](https://github.com/catdog2/mpy_bh1750fvi_esp8266) -适用于BH1750FVI传感器的ESP8266驱动程序.
* [bh1750](https://github.com/PinkInk/upylib/tree/master/bh1750) -BH1750 i2c数字光传感器驱动程序.

#### Motion Inertial

* [micropython-bmx055](https://github.com/micropython-IMU/micropython-bmx055) -博世BMX055 IMU传感器驱动程序.
* [micropython-bno055](https://github.com/deshipu/micropython-bno055) -博世Sensortec BNO055 9DOF IMU传感器，I2C接口.
* [micropython-lsm9ds0](https://github.com/micropython-IMU/micropython-lsm9ds0) -LSM9DS0 g力线性加速度，高斯磁和dps角速率传感器.
* [micropython-mpu9250](https://github.com/tuupola/micropython-mpu9250) -用于MPU9250 9轴运动跟踪设备的I2C驱动程序.
* [micropython-mpu9x50](https://github.com/micropython-IMU/micropython-mpu9x50) -InvenSense MPU9250惯性测量单元的驱动程序.
* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) -用于MPU6050加速度计/陀螺仪的ESP8266驱动程序.
* [py-mpu6050](https://github.com/larsks/py-mpu6050) -用于MPU6050加速度计/陀螺仪的ESP8266驱动程序.
* [micropython-mpu6886](https://github.com/tuupola/micropython-mpu6886) -用于MPU6886 6轴运动跟踪设备的MicroPython I2C驱动程序.
* [micropython-fusion](https://gitlab.com/nnayo/micropython-fusion) -传感器融合从运动跟踪设备的输出计算航向，俯仰和横滚.

#### Pressure

* [ms5803-micropython](https://github.com/minyiky/ms5803-micropython) -用于MS5803压力和温度传感器的驱动程序的micropython实现.

#### Soil Moisture

* [micropython-chirp](https://github.com/robberwick/micropython-chirp) -Chirp土壤湿度传感器的驱动程序.
* [MicroPython-MiFlora](https://github.com/matthias-bs/MicroPython-MiFlora) -小米Mi Flora（又称花卉护理）BLE植物传感器（土壤湿度/电导率/光强度/温度）.

#### Temperature Analog

* [micropython-max31855](https://github.com/mcauser/deshipu-micropython-max31855) -热电偶放大器，SPI接口.
* [max31856](https://github.com/alinbaltaru/max31856) -具有线性化，SPI接口的精密热电偶至数字转换器.

#### Temperature Digital

* [bme680-mqtt-micropython](https://github.com/robmarkcole/bme680-mqtt-micropython) -BME680气体，压力，温度和湿度传感器的驱动程序.
* [LM75-MicroPython](https://github.com/OldhamMade/LM75-MicroPython) -LM75数字温度传感器的驱动程序，I2C接口.
* [micropython-am2320](https://github.com/mcauser/micropython-am2320) -Aosong AM2320温湿度传感器，I2C接口.
* [micropython-dht12](https://github.com/mcauser/micropython-dht12) -Aosong DHT12温湿度传感器，I2C接口.
* [micropython-hdc1008](https://github.com/kfricke/micropython-hdc1008) -德州仪器（TI）HDC1008湿度和温度传感器的驱动程序.
* [micropython-mcp9808](https://github.com/kfricke/micropython-mcp9808) -Microchip MCP9808温度传感器的驱动程序.
* [micropython-mpl115a2](https://github.com/khoulihan/micropython-mpl115a2) -用于MPL115A2气压传感器的Pyboard驱动程序.
* [micropython-sht30](https://github.com/rsc1975/micropython-sht30) - Driver for SHT30 temperature and humidity sensor.
* [micropython-sht31](https://github.com/kfricke/micropython-sht31) -SHT31温湿度传感器的驱动程序.
* [micropython-Si7005](https://github.com/Smrtokvitek/micropython-Si7005) -Si7005相对湿度和温度传感器的驱动程序.
* [micropython-si7021](https://github.com/mcauser/deshipu-micropython-si7021) -SI7021温湿度传感器，I2C接口.
* [micropython-si7021](https://github.com/chrisbalmer/micropython-si7021) -SI7021温湿度传感器，I2C接口.
* [micropython-Si705x](https://github.com/billyrayvalentine/micropython-Si705x) -Silicon Labs Si705x系列温度传感器，I2C接口.
* [micropython-Si70xx](https://github.com/billyrayvalentine/micropython-Si70xx) -Silicon Labs Si70xx系列相对湿度和温度传感器，I2C接口.
* [micropython-tmp102](https://github.com/khoulihan/micropython-tmp102) -TMP102数字温度传感器的驱动程序.
* [Official DHT11+DHT12](https://github.com/micropython/micropython/blob/master/drivers/dht/dht.py) -用于DHT11和DHT12温度和湿度传感器的ESP8266驱动程序.
* [sht25-micropython](https://github.com/Miceuz/sht25-micropython) -SHT25温湿度传感器的驱动程序.
* [micropython-tmp1075](https://github.com/mattytrentini/micropython-tmp1075) -TI TMP1075温度传感器的驱动程序.
* [micropython-sht11](https://github.com/2black0/micropython-sht11) -Sensirion SHT11温湿度传感器的驱动程序.
* [micropython-lm75a](https://github.com/mcauser/micropython-lm75a) -NXP LM75A数字温度传感器的驱动程序.

#### Temperature IR

* [micropython-mlx90614](https://github.com/mcauser/micropython-mlx90614) -Melexis MLX90614红外温度传感器的驱动程序.

#### Touch Capacitive

* [micropython-mpr121](https://github.com/mcauser/micropython-mpr121) -MPR121电容式触摸键盘和分线板的驱动程序.
* [micropython-ttp223](https://github.com/mcauser/micropython-ttp223) -使用TTP223电容式触摸模块的示例.

#### Touch Resistive

* [XPT2046-touch-pad-driver](https://github.com/robert-hh/XPT2046-touch-pad-driver) -许多TFT模块中使用的XPT2046触摸板控制器的驱动程序.

### Scheduling

* [micropython-mcron](https://github.com/fizista/micropython-mcron) -MicroCRON是用于MicroPython的基于时间的任务计划程序.

### Storage

#### Database

* [uPyMySQL](https://github.com/dvrhax/uPyMySQL) -纯uPython MySQL客户端.
* [micropython-redis](https://github.com/dwighthubbard/micropython-redis) -设计用于MicroPython的redis客户端实现.
* [picoredis](https://github.com/SpotlightKid/picoredis) -一个非常小的Microis Redis客户端（不仅如此）.
* [micropg](https://github.com/nakagami/micropg) -MicroPython的PostgreSQL数据库驱动程序.
* [nmongo](https://github.com/nakagami/nmongo) -用于CPython和MicroPython的MongoDB客户端，具有像API这样的mongo shell.

#### EEPROM

* [micropython_eeprom](https://github.com/peterhinch/micropython_eeprom) -用于非易失性存储芯片（EEPROM，FRAM，闪存）的MicroPython设备驱动程序.

#### FRAM

* [micropython-fram](https://github.com/rolandvs/micropython-fram) -铁电RAM模块的Pyboard驱动程序.

## Community

* [MicroPython Forum](https://forum.micropython.org/) -超过6400个用户的在线社区，讨论与MicroPython相关的所有事情.
* [MicroPython on Twitter](https://twitter.com/micropython?lang=en) -在Twitter上关注MicroPython，以获取最新新闻和更新.
* [MicroPython on Facebook](https://www.facebook.com/micropython) -就像Facebook上的MicroPython一样，用于竞赛，新闻和更新.
* [Melbourne MicroPython Meetup](https://www.meetup.com/en-AU/MicroPython-Meetup) -在澳大利亚墨尔本举行的CCHS定期聚会.
* [Slack](https://slack-micropython.herokuapp.com/) -自动邀请您进入micropython.slack.com工作区.
* [Discord](https://discord.gg/qw7d8bv) -收到MicroPython Discord服务器的邀请.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](http://shop.oreilly.com/product/0636920056515.do)  -尼古拉斯·H·托勒维（Nicholas H. Tollervey）.  ISBN 9781491972731.
* [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://www.apress.com/gp/book/9781484231227)  -查尔斯·贝尔（Charles Bell）.  ISBN 9781484231227.
* [MicroPython Cookbook](https://www.packtpub.com/au/application-development/micropython-cookbook)  -Marwan Alsabbagh.  ISBN 9781838649951.
* [Python for Microcontrollers: Getting Started with MicroPython](https://www.amazon.com.au/Python-Microcontrollers-Getting-Started-MicroPython/dp/1259644537)  -唐纳德​​·诺里斯（Donald Norris）.  ISBN 9781259644535.
* [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937)  -尤里·玛格达（Yury Magda）.  ISBN 9781090900937.
* [MicroPython Projects](https://www.packtpub.com/au/iot-hardware/micropython-projects)  -雅各·贝宁戈（Jacob Beningo）.  ISBN 9781789958034.
* [Get Started with MicroPython on Raspberry Pi Pico](https://store.rpipress.cc/products/get-started-with-micropython-on-raspberry-pi-pico)  -由Gareth Halfacree和Ben Everard撰写.  ISBN 9781912047864.
* [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book)  -金特·斯潘纳（GünterSpanner）.  ISBN 9783895764370.
* [MicroPython For Everyone: How To Use ESP32 And ESP8266: Micropython Mqtt](https://www.amazon.com/MicroPython-Everyone-ESP32-ESP8266-Micropython/dp/B094281XK1)  -梅森·米莱特（Mason Milette）.  ISBN 9798748248822.

## Frameworks

* [micrOS](https://github.com/BxNxM/micrOS) -基于MicroPython的IoT框架.
* [terkin-datalogger](https://github.com/hiveeyes/terkin-datalogger) -适用于MicroPython和CPython的灵活的数据记录器应用程序.

## Resources

* [MicroPython](http://micropython.org)  -项目网站. 试驾pyboard. 与独角兽一起在线尝试MicroPython.
* [MicroPython on GitHub](https://github.com/micropython/micropython) -提交错误报告，关注并参与GitHub上的开发.
* [MicroPython Official Documentation](http://docs.micropython.org/) -对于各种端口，包括快速参考，一般信息，示例和教程.
* [MicroPython Wiki](http://wiki.micropython.org/Home) -社区生成的文档和MicroPython和pyboard功能的示例.
* [MicroPython Newsletter](http://micropython.org/newsletter) -订阅MicroPython新闻通讯以获取新闻和公告，包括新功能和新产品.
* [MicroPython Store](https://store.micropython.org/) -在哪里可以买到pyboard，外壳，外壳，书籍，连接器和外围设备.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) -Wikipedia上的MicroPython.

## Development

### Code Generation

* [micropy-cli](https://github.com/BradenM/micropy-cli) -Micropy Cli是一个项目管理/生成工具，用于在VSCode等现代IDE中编写MicroPython代码.
* [micropython-stubber](https://github.com/Josverl/micropython-stubber) -为不同的MicroPython固件生成并使用存根，以便与vscode和/或pylint一起使用.
* [micropy-stubs](https://github.com/BradenM/micropy-stubs) -自动为Micropy-Cli和其他任何人生成的存根软件包.

### Debugging

* [esp32-backtrace](https://github.com/tve/esp32-backtrace) -ESP32异常堆栈回溯分析器.

### IDEs

* [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) -IntelliJ和PyCharm中用于MicroPython设备的插件.
* [Micropython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) -用于VSCode自述文件的MicroPython IDE.
* [Micropython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) -与MicroPython REPL终端进行交互的便捷快捷方式.
* [Mu Editor](https://codewith.mu/) -带Mu的代码：面向初学者的简单Python \ MicroPythonb \ CircuitPython编辑器.
* [Thonny IDE](https://thonny.org/) -Thonny：适用于初学者的Python IDE.

### Shells

#### On Device

* [upy-shell](https://github.com/dhylands/upy-shell) -用于MicroPython的基于命令行的简单外壳.
* [Micropython-Editor](https://github.com/robert-hh/Micropython-Editor) -小型板载编辑器，用于用Python编写的PyBoard，WiPy，ESP8266，ESP32，PyCom和Adafruit设备.

#### On Host

* [rshell](https://github.com/dhylands/rshell) -将文件复制或同步到板，然后从终端输入REPL.
* [ampy](https://github.com/scientifichackers/ampy) -Adafruit MicroPython工具-通过串行连接与MicroPython开发板交互的实用程序.
* [mpfshell](https://github.com/wendlers/mpfshell) -一个用于ESP8266和WiPy的基于外壳的简单文件浏览器.
* [mpsync](https://github.com/Uhlo/mpsync) -一个小工具，只要它检测到更改，便会将文件夹同步到MicroPython开发板.

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) -1,931名支持者认捐了97,803英镑，以帮助实现该项目.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) -1,399位支持者认捐了28,534英镑，以帮助实现该项目.

## Contributing

始终欢迎您提供意见和建议！ 请看看 [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) 第一的.

如果不确定这些库是否很棒，我将打开一些拉取请求，您可以通过添加它们来投票支持它们.
