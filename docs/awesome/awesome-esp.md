<div class="github-widget" data-repo="agucova/awesome-esp"></div>
## Awesome ESP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](https://github.com/agucova/awesome-esp/blob/master/code-of-conduct.md)
精选的 ESP8266/32 项目和代码列表.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="https://raw.githubusercontent.com/agucova/awesome-esp/master/img/esp8266.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a>
<a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>
&gt; 两者 [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) 和 [ESP32](http://espressif.com/en/products/hardware/esp32/overview) 是低成本 Wi-Fi 微芯片，具有完整的 TCP/IP 堆栈和微控制器功能，由总部位于上海的制造商 Espressif Systems 生产.
> <br/>
&gt; 看 [Contributing](https://github.com/agucova/awesome-esp/blob/master/contributing.md) 有关如何为该列表做出贡献的信息.
> <br/><br/>
---


## Firmware
- [Espressif AT](http://bbs.espressif.com/) - ESP8266 的默认香草固件.
- [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) - 用于 ESP8266 的基于 eLua 的固件.
- [ESPBasic](http://www.esp8266basic.com/) - 用于轻松无线编程的 BASIC 固件，适用于 8266.
- [MicroPython](https://github.com/micropython/micropython/) - 用于 ESP8266 和 32 的 Python3 实现.
- [ESP3D](https://github.com/luc-github/ESP3D) - 用于 3D 打印机的实验性固件，包括 ESP32 和 8266.
- [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) - 一个快速而肮脏的固件，具有 ESP8266 的酷炫功能.
- [MongooseOS](https://github.com/cesanta/mongoose-os)  - 物联网特定固件，同时具有 C 和 JS. 适用于 ESP32/8266.
- [DeviceHive](https://devicehive.com/) - 作为 DeviceHive 物联网数据平台客户端制作的固件，仅适用于 8266.
- [RT-Thread](https://github.com/RT-Thread/rt-thread) - 可用于 ESP32 的中文开源固件.
- [Sming Framework](https://github.com/SmingHub/Sming) - 出色的 C/C++ 物联网框架，支持 ESP8266 和 ESP32.

## Tools
- [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) - 两个 ESP 的香草固件闪光器.
- [Arduino Core/8266](https://github.com/esp8266/arduino) - ESP8266 的 Arduino 内核.
- [Arduino Core/32](https://github.com/espressif/arduino-esp32) - ESP32 的另一个 Arduino 内核.
- [ESPTool](https://github.com/espressif/esptool) - Espressif 的命令行工具，用于两个 ESP 中的引导加载程序通信.
- [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) - ESP8266 的开放式 SDK.
- [ESPTool-ck](https://github.com/igrr/esptool-ck) - 用于在 ESP8266 中闪烁的 CLI 工具.
- [ESPTool-gui](https://github.com/Rodmg/esptool-gui) - 基于 ESPTool-ck 的刷机 GUI 工具.
- [LuaNode](https://github.com/Nicholas3388/LuaNode) - 用于 32/8266 的 lua-only SDK.
- [Tuya-Convert](https://github.com/ct-Open-Source/tuya-convert) - Wi-Fi刷机ESP8266，已预装涂鸦固件.
- [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) - NodeMCU OS 官方刷机工具.
- [Tasmotizer](https://github.com/tasmota/tasmotizer)  - 用于 Tasmota 固件的图形刷写工具. 可以管理 Wi-Fi 和 MQTT 设置、模块和模板.
- [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) - 用于 8266 中文件系统上传的 Arduino 插件.
- [PlatformIO](https://github.com/platformio/platformio-core) - 支持 ESP32 和 ESP8266 的跨平台 IDE 和调试器.

## Projects
### Smart Home and IoT
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - 为 ESP 和其他设备实施多协议 MQTT 网关.
- [ESPHome](https://esphome.io/) - 一个功能齐全的系统，用于通过简单而强大的配置文件和家庭自动化系统来控制 ESP.
- [Tasmota](https://tasmota.github.io/docs/)  - Sonoff 和其他 ESP8266/ESP32 设备的替代固件. 包括大量传感器驱动程序并与 [Home Assistant](https://www.home-assistant.io/) 本机或通过 MQTT.
- [ESPEasy](https://github.com/letscontrolit/ESPEasy) - 轻松将 ESP 模块变成用于家庭自动化系统的多功能传感器设备.
- [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) - Sonoff 设备（和其他 8266 设备）的替代固件，允许通过 Apple 的 Homekit 进行控制.
- [DoorsignEPD](https://github.com/jamct/DoorsignEPD) - 使用 ESP32 的带有电子纸显示屏的智能门牌.
- [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) - 使用 ESP32 的非常可爱的电子墨水天气显示器.
- [HomePoint](https://github.com/sieren/Homepoint) - 从 ESP32 供电的屏幕控制 MQTT/HomeKit 智能家居设备.
- [openHASP](https://www.openhasp.com/) - 从通过 MQTT 连接的可自定义触摸屏 UI 控制您的家庭自动化设备.
- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) - 适用于 ESP32 的全功能家庭农业自动化软件.
- [CanAirIO](https://github.com/kike-canaries/canairio_firmware#canairio-firmware) - 利用移动站和固定站通过 ESP32 和智能手机测量空气质量的公民科学项目.

### InfoSec
- [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) - 显示 BLE 设备并从中收集数据的 wardriving 设备，所有这些都在一个漂亮的屏幕界面中.
- [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) - 一套集成的 WiFi 和蓝牙攻防工具.
- [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) - 允许为两个 ESP 生成具有网络流量的 .pcap 文件的库.
- [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) - 一个巨大的 Wifi“卫星”，可以使用 14 个 ESP32 监控所有 14 个 2.4Ghz 频道.
- [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) - 一个非常酷的使用 ESP8266 的 Wifi 网络伪干扰器（deauther）.
- [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32)  - 一个漂亮的 OLED 监视器，用于 WiFi 通道中的数据包活动. 每个 ESP 有两个版本.
- [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) - 支持无线的击键注入器，类似，但比 Rubber Ducky 更棒.
- [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam)  - 想迷惑人吗？ 该设备创建了数百个虚假 WiFi 网络.
- [DeauthDetector](https://github.com/spacehuhn/DeauthDetector)  - 如果检测到 WiFi deauth 攻击，就会发光的小型设备. 由与最后六个项目相同的人制作.

### Biomedical
- [HeartyPatch](https://heartypatch.protocentral.com/) - 使用 ESP32 的可穿戴 BLE 和 WiFi 连接 ECG-HR 贴片.
- [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) - 一个惊人的开源生命体征监测器，可以监测心电图、呼吸、脉搏血氧饱和度和体温，所有这些都由 ESP32 运行.

### LoRa

- [Meshtastic](https://www.meshtastic.org/) - ESP32 LoRA 板作为安全、电池寿命长的网状 GPS 通信器.
- [ESP32-Paxcounter](https://github.com/cyberman54/ESP32-Paxcounter#esp32-paxcounter) - Wifi 和蓝牙驱动、LoRaWAN 启用、电池供电的迷你 Paxcounter，建立在廉价的 ESP32 LoRa 物联网板上.
- [Disaster Radio](https://disaster.radio/) - 由太阳能供电的抗灾通信网络.

### Music and Audio

- [Alles](https://github.com/bwhitman/alles) - 多扬声器分布式音乐合成器，使用 WiFi 上的 UDP 多播，仿照 alles machine/AMY.
- [ESP32-Radio](https://github.com/Edzelf/ESP32-Radio) - 基于 ESP32、VS1053 和 TFT 屏幕的网络广播.
- [ESPuino](https://github.com/biologist79/ESPuino) - 由 ESP32 驱动的 RFID 控制音乐播放器.
- [Knobby](https://github.com/quadule/knobby) - 鼓励您探索不熟悉的音乐的手持式 Spotify 遥控器.
- [PedalinoMini](https://github.com/alf45tar/PedalinoMini) - 用于吉他手的无线 MIDI 踏板控制器，使用 ESP32 构建.
- [Squeezelite-esp32](https://github.com/sle118/squeezelite-esp32) - 具有多房间同步、AirPlay、蓝牙、硬件按钮、显示器等功能的流式音频接收器.
- [ThingPulse esp8266-spotify-remote](https://github.com/ThingPulse/esp8266-spotify-remote) - 通过带彩色触摸屏的 ESP8266 控制您的 Spotify 播放器.

### Smartwatches

- [mutantW_V1](https://mutantcybernetics.com/mutantW_V1.html) - 基于 ESP32 的开源智能手表，具有 1.7 英寸显示屏、WiFi、蓝牙、NeoPixel 和振动功能.
- [Open SmartWatch](https://open-smartwatch.github.io/) - 带有 GPS、惯性单元和非常酷的 3D 打印表壳的 FOSS 智能手表.
- [StickWatch](https://github.com/eggfly/StickWatch) - 基于 M5Stick 的智能手表模块，使用 ESP32.
- [Watchy](https://watchy.sqfmi.com) - 一个开源电子纸手表，有很多定制选项.

### Others
- [SoftRF](https://github.com/lyusupov/SoftRF) - 可用于无人机项目的 DIY 航空接近感知系统.
- [Retro ESP32](https://github.com/retro-esp32/RetroESP32) - 一个非常酷的 Odroid Go 启动器（带有 ESP32），它允许模拟多个复古控制台.
- [DroneBridge](https://github.com/DroneBridge/ESP32) - An implementation of DroneBridge, a signal link for drones and UAV's on the ESP32.
- [E-TKT](https://github.com/andreisperid/E-TKT) - ESP32 供电的 DIY 标签制作器，融合了老式和现代技术.
- [FreeTouchDeck](https://github.com/DustinWatts/FreeTouchDeck) - 开源触摸 macropad 和带有内置网络配置器的流控制面板.
- [SmartSpin2k](https://github.com/doudar/SmartSpin2k) - 通过 Zwift 等健身应用程序中的自动阻力旋钮控制，将您的动感单车变成智能教练.
- [WirelessPrinting](https://github.com/probonopd/WirelessPrinting) - 从 Cura、PrusaSlicer 或 Slic3r 无线打印到连接到 ESP 模块的 3D 打印机.
- [WLED](https://kno.wled.ge/) - 通过 WiFi 使用 ESP8266 或 ESP32 控制多种类型的 RGB(W) LED 灯条.

## Libraries
- [Wasm3](https://github.com/wasm3/wasm3) - 专为嵌入式设备设计的闪电般快速的 WebAssembly 解释器，与两种 ESP 兼容.
- [Homie8266](https://github.com/marvinroger/homie-esp8266) - 8266 的 Homie 协议的框架实现.
- [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH)  - 用于在 8266/32 中创建远程仪表板的漂亮而快速的框架. 无需互联网.
- [ESP_mqtt](https://github.com/tuanpmt/esp_mqtt) - ESP8266 的 MQTT 帮助程序库.
- [GUIslice](https://github.com/ImpulseAdventure/GUIslice)  - 用于多个设备和屏幕控制器的拖放式 GUI 框架. 兼容8266和32.
- [LVGL](https://lvgl.io) - 一个开源图形库，提供创建嵌入式 GUI 所需的一切，具有易于使用的图形元素、漂亮的视觉效果和低内存占用.
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - 一个非常强大的 MicroPython 网络服务器，可以在 ESP32 中使用.
- [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) - 在 ESP8266 中发射和接收红外信号.
- [esphomelib](https://github.com/OttoWinter/esphomelib) - 与 8266 中的 HomeAssistant 集成的框架.
- [TTS](https://github.com/jscrane/TTS) - 一个适用于多个 Arduino 设备的文本到语音库，包括两个 ESP.
- [Free802.11](https://github.com/Jeija/esp32free80211) - 使用 ESP32 发出任意 802.11 信号的库.
- [Koyn](https://github.com/elkrem/koyn) - 用于 ESP32 和 ESP8266 的去中心化比特币库.
- [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) - ESP32 的 TFT 兼容性.
- [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) - 对 ESP32/8266 的 UTFT 支持.
- [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) - 用于在 ESP8266/ESP32 中播放各种音频格式的库.
- [ESP32-audioI2S](https://github.com/schreibfaul1/ESP32-audioI2S) - 播放 SD 卡中的 mp3、m4a 和 wav 文件或通过 I2S 接口流式传输.
- [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) - 8266 和 32 的异步 TCP 库.
- [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) - RTOS 上 8266 的 Homekit 实现.
- [HomeSpan](https://github.com/HomeSpan/HomeSpan) - 一个强大且极其易于使用的 Arduino 库，用于创建您自己的基于 ESP32 的 HomeKit 设备.
- [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) - 8266 的 MQTT 和 Wi-fi 面向自动化的库.
- [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) - 32 的 ESPHelper 库的端口.
- [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) - 用于 8266 的简单 Arduino Wifi 库.
- [WiFiESP](https://github.com/bportaluri/WiFiEsp) - 用于 Wifi 管理的 Arduino 库，8266 板的客户端/服务器.
- [TinyGSM](https://github.com/vshymanskyy/TinyGSM) - 一个快速简单的 Arduino 库，用于与 GSM 模块交互，也可以通过 AT 命令控制 8266.
- [mJS](https://github.com/cesanta/mjs) - MongooseOS 使用的轻量级受限 JS 引擎，兼容 32 和 8266.
- [ESPUI](https://github.com/s00500/ESPUI) - 一个简单的库，用于为两个 ESP 制作交互式 Web 界面.
- [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) - 用于将电子纸模块与 ESP32 结合使用的全功能库.
- [TinyUPnP](https://github.com/ofekp/TinyUPnP) - 轻量级 UPnP IGD 库，用于 8266 和 32 上的自动端口转发.
- [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) - 在 ESP32 中实现 SSH 客户端的库.
- [painlessMesh](https://github.com/gmag11/painlessMesh) - 一个处理使用 ESP8266 和 ESP32 硬件创建简单网状网络细节的库.
- [WifiEspNow](https://github.com/yoursunny/WifiEspNow) - Arduino 图书馆 [ESP-NOW](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html), 一种无连接的 WiFi 通信协议，由 [Espressif](https://github.com/espressif).
- [go-mcu](https://github.com/matiasinsaurralde/go-mcu) - 用于与基于 NodeMCU 的板进行交互的 Golang 包.
- [CanAirIO SensorLib](https://github.com/kike-canaries/canairio_sensorlib#canairio-air-quality-sensors-library) - ESP32/8266 库，可自动配置多个 PM2.5、CO2 和环境传感器.
- [Dhyara](https://github.com/neel/dhyara) - 用于使用 ESP Now 制作移动自组织网络 (MANET) 的 AC/C++ 库.
- [LedFx](https://github.com/LedFx/LedFx)  - 使用音频输入创建实时灯光秀的库.  LedFx 可以控制多个设备，并且可以与廉价的 ESP8266 节点配合使用.
