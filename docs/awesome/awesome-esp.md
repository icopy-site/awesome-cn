<div class="github-widget" data-repo="agucova/awesome-esp"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable awesome-list-item-->
<!--lint disable awesome-toc-->
<!--lint disable no-blockquote-without-marker-->

## Awesome ESP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](https://github.com/agucova/awesome-esp/blob/master/code-of-conduct.md)
精选的ESP8266 / 32专案和程式码清单.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="https://raw.githubusercontent.com/agucova/awesome-esp/master/img/esp8266.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a>
<a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>
&gt;两者 [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) 和 [ESP32](http://espressif.com/en/products/hardware/esp32/overview) 是上海的制造商乐鑫系统有限公司生产的具有完整TCP / IP堆栈和微控制器功能的低成本Wi-Fi微芯片.  
> <br/>
&gt;看 [Contributing](https://github.com/agucova/awesome-esp/blob/master/contributing.md) 有关如何为该列表做出贡献的信息.
> <br/><br/> 

<!--lint disable no-repeat-punctuation-->
<!--lint disable remark-lint-double-link-->

## Firmware
- [Espressif AT](http://bbs.espressif.com/) -ESP8266的默认香草固件.
- [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) -ESP8266基于eLua的固件.
- [ESPBasic](http://www.esp8266basic.com/) -BASIC固件，可轻松进行无线编程，适用于8266.
- [MicroPython](https://github.com/micropython/micropython/) -为ESP8266实现Python3.
- [MicroPython/32](https://github.com/micropython/micropython-esp32) -用于ESP32的MicroPython端口.
- [ESP32](https://github.com/luc-github/ESP3D) -用于ESP32和8266的3D打印机的实验性固件.
- [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) -具有ESP8266强大功能的快速脏固件.
- [MongooseOS](https://github.com/cesanta/mongoose-os)  -具有C和JS的特定于IoT的固件. 适用于ESP32 / 8266.
- [DeviceHive](https://devicehive.com/) -作为DeviceHive IoT数据平台客户端的固件，仅适用于8266.
- [RT-Thread](https://github.com/RT-Thread/rt-thread) -ESP32可用的中文开源固件.

## Tools
- [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) -两个ESP的香草固件更新程序.
- [Arduino Core/8266](https://github.com/esp8266/arduino) -ESP8266的Arduino核心.
- [Arduino Core/32](https://github.com/espressif/arduino-esp32) -ESP32的另一个Arduino核心.
- [ESPTool](https://github.com/espressif/esptool) -用于两个ESP的Bootloader通讯的Espressif命令行工具.
- [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) -ESP8266的开放SDK.
- [ESPTool-ck](https://github.com/igrr/esptool-ck) -用于在ESP8266中刷新的CLI工具.
- [ESPTool-gui](https://github.com/Rodmg/esptool-gui) -基于ESPTool-ck的Flash GUI工具.
- [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) -NodeMCU操作系统的官方刷新工具.
- [LuaNode](https://github.com/Nicholas3388/LuaNode) -适用于32/8266的仅lua的SDK.
- [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) -在8266中用于文件系统上传的Arduino插件.
- [PlatformIO](https://github.com/platformio/platformio-core) -同时支持ESP32和ESP8266的跨平台IDE和调试器.

## Projects
### Smart Home and IoT
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) -针对其他设备中的两个ESP的多协议MQTT网关的实现.
- [ESPHome](https://esphome.io/) -通过简单但功能强大的配置文件和家庭自动化系统控制ESP的功能齐全的系统.
- [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) -Sonoff设备（和其他8266设备）的备用固件，允许通过Apple的Homekit进行控制.
- [DoorsignEPD](https://github.com/jamct/DoorsignEPD) -使用ESP32的带有电子纸显示屏的智能门牌.
- [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) -使用ESP32的非常可爱的电子墨水天气显示.
- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) -用于ESP32的功能齐全的家庭农业自动化软件.

### InfoSec
- [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) -能够显示BLE设备并从中收集数据的管理设备，所有操作都在一个漂亮的屏幕界面中进行.
- [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) -用于WiFi和蓝牙的综合攻防工具套件.
- [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) -一个库，可以为两个ESP生成具有网络流量的.pcap文件.
- [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) -巨大的Wifi“卫星”，可以使用14个ESP32监视所有14个2.4Ghz通道.
- [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) -使用ESP8266的Wifi网络非常酷的伪干扰（取消身份验证）.
- [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32)  -漂亮的OLED监视器，用于WiFi通道中的数据包活动. 每个ESP有两个版本.
- [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) -具有无线功能的按键喷射器，与Rubber Ducky相似，但更加出色.
- [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam)  -想混淆别人吗？ 此设备会创建数百个伪造的WiFi网络.
- [DeauthDetector](https://github.com/spacehuhn/DeauthDetector)  -如果检测到WiFi取消身份验证攻击，就会发光的小型设备. 与最后六个项目由同一个人制作.

### Biomedical
- [HeartyPatch](https://heartypatch.protocentral.com/) -使用ESP32的可穿戴BLE和WiFi连接的ECG-HR补丁.
- [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) -一款出色的开源生命体征监测器，可以监测ESP32所运行的ECG，呼吸，脉搏血氧饱和度和体温.

### Others
- [SoftRF](https://github.com/lyusupov/SoftRF) -可以在无人机项目中使用的DIY航空近距离感知系统.
- [Retro ESP32](https://github.com/retro-esp32/RetroESP32) -适用于Odroid Go（带有ESP32）的超酷启动器，它可以模拟多个复古控制台.
- [PedalinoMini](https://github.com/alf45tar/PedalinoMini) -ESP32内置的无线MIDI踏板控制器，适用于吉他手.
- [StickWatch](https://github.com/eggfly/StickWatch) -使用ESP32的基于M5Stick的智能手表模块.
- [DroneBridge](https://github.com/DroneBridge/ESP32) -DroneBridge的实现，ESP32上用于无人机和无人机的信号链路.
## Libraries
- [Wasm3](https://github.com/wasm3/wasm3) -专为嵌入式设备设计的闪电般的WebAssembly解释器，与两个ESP兼容.
- [Homie8266](https://github.com/marvinroger/homie-esp8266) -8266的Homie协议的框架实现.
- [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH)  -用于在8266/32中创建远程仪表盘的美观，快速的框架. 无需互联网.
- [ESP_mqtt](https://github.com/tuanpmt/esp_mqtt) -用于ESP8266的MQTT帮助程序库.
- [GUIslice](https://github.com/ImpulseAdventure/GUIslice)  -用于多个设备和屏幕控制器的拖放GUI框架. 兼容8266和32.
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) -一个非常强大的MicroPython Web服务器，可以在ESP32中使用.
- [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) -在ESP8266中发射和接收IR信号.
- [esphomelib](https://github.com/OttoWinter/esphomelib) -在8266中与HomeAssistant集成的框架.
- [TTS](https://github.com/jscrane/TTS) -用于多个Arduino设备（包括ESP）的某种程度上不错的文本到语音库.
- [Free802.11](https://github.com/Jeija/esp32free80211) -通过ESP32发出任意802.11信号的库.
- [Koyn](https://github.com/elkrem/koyn) -用于ESP32和ESP8266的分散式比特币库.
- [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) -ESP32的TFT兼容性.
- [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) -对ESP32 / 8266的UTFT支持.
- [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) -用于在ESP8266 / ESP32中播放各种音频格式的库.
- [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) -8266和32的异步TCP库.
- [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) -在RTOS上实现8266的Homekit实现.
- [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) -8266的面向MQTT和Wi-fi自动化的库.
- [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) -32的ESPHelper库的端口.
- [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) -8266的简单Arduino Wifi库.
- [WiFiESP](https://github.com/bportaluri/WiFiEsp) -用于Wifi管理的Arduino库，用于8266开发板的客户端/服务器.
- [TinyGSM](https://github.com/vshymanskyy/TinyGSM) -一个快速简单的Arduino库，用于与GSM模块进行交互，该模块还可以通过AT命令控制8266.
- [mJS](https://github.com/cesanta/mjs) -MongooseOS使用的轻量级受限JS引擎，与32和8266兼容.
- [ESPUI](https://github.com/s00500/ESPUI) -一个简单的库，用于为两个ESP制作交互式Web界面.
- [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) -功能齐全的库，可将ePaper模块与ESP32一起使用.
- [TinyUPnP](https://github.com/ofekp/TinyUPnP) -轻巧的UPnP IGD库，用于在8266和32上自动进行端口转发.
- [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) -在ESP32中实现SSH客户端的库.
- [painlessMesh](https://github.com/gmag11/painlessMesh) -一个负责使用ESP8266和ESP32硬件创建简单网状网络的细节的库.
- [WifiEspNow](https://github.com/yoursunny/WifiEspNow) -的Arduino库 [ESP-NOW](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html)，由定义的无连接WiFi通信协议 [Espressif](https://github.com/espressif).
