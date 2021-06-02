<div class="github-widget" data-repo="agucova/awesome-esp"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable awesome-list-item-->
<!--lint disable awesome-toc-->
<!--lint disable no-blockquote-without-marker-->

## Awesome ESP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](https://github.com/agucova/awesome-esp/blob/master/code-of-conduct.md)
精选的 ESP8266/32 项目和代码列表.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="https://raw.githubusercontent.com/agucova/awesome-esp/master/img/esp8266.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a>
<a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>
&gt; 无论是 [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) 和 [ESP32](http://espressif.com/en/products/hardware/esp32/overview) 是低成本的 Wi-Fi 微芯片，具有完整的 TCP/IP 堆栈和微控制器功能，由上海制造商乐鑫系统生产.
> <br/>
&gt; 见 [Contributing](https://github.com/agucova/awesome-esp/blob/master/contributing.md) 有关如何为此列表做出贡献的信息.
> <br/><br/>
---
<!--lint disable no-repeat-punctuation-->
<!--lint disable remark-lint-double-link-->

## Firmware
- [Espressif AT](http://bbs.espressif.com/) - ESP8266 的默认香草固件.
- [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) - ESP8266 的基于 eLua 的固件.
- [ESPBasic](http://www.esp8266basic.com/) - 用于轻松无线编程的 BASIC 固件，为 8266 做好准备.
- [MicroPython](https://github.com/micropython/micropython/) - ESP8266 和 32 的 Python3 实现.
- [ESP32](https://github.com/luc-github/ESP3D) - ESP32 和 8266 3D 打印机的实验性固件.
- [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) - ESP8266 具有酷炫功能的快速而肮脏的固件.
- [MongooseOS](https://github.com/cesanta/mongoose-os)  - 具有 C 和 JS 的 IoT 特定固件. 适用于 ESP32/8266.
- [DeviceHive](https://devicehive.com/) - 作为 DeviceHive 物联网数据平台客户端的固件，仅适用于 8266.
- [RT-Thread](https://github.com/RT-Thread/rt-thread) - ESP32 的中文开源固件.
- [Sming Framework](https://github.com/SmingHub/Sming) - 出色的 C/C++ 物联网框架，支持 ESP8266 和 ESP32.  

## Tools
- [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) - 两个 ESP 的香草固件闪烁器.
- [Arduino Core/8266](https://github.com/esp8266/arduino) - ESP8266 的 Arduino 内核.
- [Arduino Core/32](https://github.com/espressif/arduino-esp32) - ESP32 的另一个 Arduino 核心.
- [ESPTool](https://github.com/espressif/esptool) - Espressif 的命令行工具，用于两个 ESP 中的引导加载程序通信.
- [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) - ESP8266 的开放式 SDK.
- [ESPTool-ck](https://github.com/igrr/esptool-ck) - 用于在 ESP8266 中刷新的 CLI 工具.
- [ESPTool-gui](https://github.com/Rodmg/esptool-gui) - 基于 ESPTool-ck 的闪烁 GUI 工具.
- [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) - NodeMCU 为其操作系统提供的官方刷机工具.
- [LuaNode](https://github.com/Nicholas3388/LuaNode) - 适用于 32/8266 的仅限 lua 的 SDK.
- [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) - 一个用于在 8266 中上传文件系统的 Arduino 插件.
- [PlatformIO](https://github.com/platformio/platformio-core) - 支持 ESP32 和 ESP8266 的跨平台 IDE 和调试器.

## Projects
### Smart Home and IoT
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - 为其他设备中的两个 ESP 实现多协议 MQTT 网关.
- [ESPHome](https://esphome.io/) - 一个功能齐全的系统，用于通过简单而强大的配置文件和家庭自动化系统来控制 ESP.
- [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) - Sonoff 设备（和其他 8266 设备）的替代固件，允许通过 Apple 的 Homekit 进行控制.
- [DoorsignEPD](https://github.com/jamct/DoorsignEPD) - 使用 ESP32 的带有电子纸显示屏的智能门牌.
- [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) - 使用 ESP32 的非常可爱的电子墨水天气显示.
- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) - ESP32 的全功能家庭农业自动化软件.
- [CanAirIO](https://github.com/kike-canaries/canairio_firmware#canairio-firmware) - 公民科学项目，使用移动站和固定站通过 ESP32 和智能手机测量空气质量.

### InfoSec
- [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) - 一个驱动设备，它显示 BLE 设备并从中收集数据，所有这些都在一个漂亮的屏幕界面中.
- [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) - 一套用于 WiFi 和蓝牙的综合攻击和防御工具.
- [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) - 允许为两个 ESP 生成具有网络流量的 .pcap 文件的库.
- [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) - 一个巨大的 Wifi“卫星”，可以使用 14 个 ESP32 监控所有 14 个 2.4Ghz 频道.
- [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) - 使用 ESP8266 的非常酷的 Wifi 网络伪干扰器（deauther）.
- [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32)  - 漂亮的 OLED 监视器，用于显示 WiFi 通道中的数据包活动. 每个 ESP 有两个版本.
- [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) - 支持无线的按键注入器，类似，但比 Rubber Ducky 更棒.
- [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam)  - 想迷惑人吗？ 该设备创建了数百个假 WiFi 网络.
- [DeauthDetector](https://github.com/spacehuhn/DeauthDetector)  - 如果检测到 WiFi deauth 攻击会发光的小型设备. 由与过去六个项目相同的人制作.

### Biomedical
- [HeartyPatch](https://heartypatch.protocentral.com/) - 使用 ESP32 的可穿戴 BLE 和 WiFi 连接的 ECG-HR 贴片.
- [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) - 一个惊人的开源生命体征监测器，可以监测心电图、呼吸、脉搏血氧饱和度和体温，所有这些都由 ESP32 运行.

### LoRa

- [Meshtastic](https://www.meshtastic.org/) - ESP32 LoRA 板作为安全、长电池寿命的网状 GPS 通信器.
- [ESP32-Paxcounter](https://github.com/cyberman54/ESP32-Paxcounter#esp32-paxcounter) Wifi 和蓝牙驱动、支持 LoRaWAN、电池供电的迷你 Paxcounter 建立在廉价的 ESP32 LoRa 物联网板上
- [Disaster Radio](https://disaster.radio/) - 由太阳能供电的抗灾通信网络

### Others
- [Open SmartWatch](https://open-smartwatch.github.io/) - 带有 GPS、惯性装置和超酷 3D 打印表壳的 FOSS 智能手表.
- [SoftRF](https://github.com/lyusupov/SoftRF) - 可用于无人机项目的 DIY 航空接近感知系统.
- [Retro ESP32](https://github.com/retro-esp32/RetroESP32) - 一个非常酷的 Odroid Go 启动器（带有 ESP32），它允许模拟多个复古控制台.
- [PedalinoMini](https://github.com/alf45tar/PedalinoMini) - 用 ESP32 构建的吉他手无线 MIDI 踏板控制器.
- [StickWatch](https://github.com/eggfly/StickWatch) - 基于 M5Stick 的智能手表模块，使用 ESP32.
- [DroneBridge](https://github.com/DroneBridge/ESP32) - DroneBridge 的实现，ESP32 上无人机和 UAV 的信号链路.
## Libraries
- [Wasm3](https://github.com/wasm3/wasm3) - 为嵌入式设备设计的闪电般快速的 WebAssembly 解释器，与两种 ESP 兼容.
- [Homie8266](https://github.com/marvinroger/homie-esp8266) - 8266 的 Homie 协议的框架实现.
- [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH)  - 用于在 8266/32 中创建远程仪表板的漂亮且快速的框架. 不需要互联网.
- [ESP_mqtt](https://github.com/tuanpmt/esp_mqtt) - ESP8266 的 MQTT 辅助库.
- [GUIslice](https://github.com/ImpulseAdventure/GUIslice)  - 用于多个设备和屏幕控制器的拖放 GUI 框架. 兼容8266和32.
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - 一个非常强大的 MicroPython Web 服务器，可以在 ESP32 中使用.
- [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) - 在 ESP8266 中发射和接收红外信号.
- [esphomelib](https://github.com/OttoWinter/esphomelib) - 与 8266 中的 HomeAssistant 集成的框架.
- [TTS](https://github.com/jscrane/TTS) - 一个很好的文本转语音库，适用于多个 Arduino 设备，包括 ESP.
- [Free802.11](https://github.com/Jeija/esp32free80211) - 使用 ESP32 发出任意 802.11 信号的库.
- [Koyn](https://github.com/elkrem/koyn) - ESP32 和 ESP8266 的去中心化比特币库.
- [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) - ESP32 的 TFT 兼容性.
- [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) - 对 ESP32/8266 的 UTFT 支持.
- [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) - 用于在 ESP8266/ESP32 中播放各种音频格式的库.
- [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) - 8266 和 32 的异步 TCP 库.
- [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) - RTOS 上 8266 的 Homekit 实现.
- [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) - 面向 8266 的 MQTT 和 Wi-fi 自动化库.
- [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) - ESPHelper 库的 32 端口.
- [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) - 用于 8266 的简单 Arduino Wifi 库.
- [WiFiESP](https://github.com/bportaluri/WiFiEsp) - 用于 Wifi 管理的 Arduino 库，用于 8266 板的客户端/服务器.
- [TinyGSM](https://github.com/vshymanskyy/TinyGSM) - 一个快速简单的 Arduino 库，用于与 GSM 模块交互，还可以通过 AT 命令控制 8266.
- [mJS](https://github.com/cesanta/mjs) - MongooseOS 使用的轻量级受限 JS 引擎，兼容 32 和 8266.
- [ESPUI](https://github.com/s00500/ESPUI) - 一个简单的库，用于为两个 ESP 制作交互式 Web 界面.
- [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) - 用于将 ePaper 模块与 ESP32 配合使用的全功能库.
- [TinyUPnP](https://github.com/ofekp/TinyUPnP) - A lightweight UPnP IGD library for automatic port forwarding on the 8266 and 32.
- [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) - 在 ESP32 中实现 SSH 客户端的库.
- [painlessMesh](https://github.com/gmag11/painlessMesh) - 一个库，负责使用 ESP8266 和 ESP32 硬件创建简单网状网络的细节.
- [WifiEspNow](https://github.com/yoursunny/WifiEspNow) - Arduino 库 [ESP-NOW](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html)，由定义的无连接 WiFi 通信协议 [Espressif](https://github.com/espressif).
- [go-mcu](https://github.com/matiasinsaurralde/go-mcu) - 用于与基于 NodeMCU 的板进行交互的 Golang 包.
- [CanAirIO SensorLib](https://github.com/kike-canaries/canairio_sensorlib#canairio-air-quality-sensors-library) - ESP32/8266 库，可自动配置多个 PM2.5、CO2 和环境传感器.
- [Dhyara](https://github.com/neel/dhyara) - 使用 ESP Now 制作移动自组织网络 (MANET) 的 AC/C++ 库.
