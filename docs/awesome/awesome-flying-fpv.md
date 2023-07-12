<div class="github-widget" data-repo="Matthias84/awesome-flying-fpv"></div>
## Awesome Flying FPV [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint disable awesome-toc no-repeat-punctuation match-punctuation -->

这是专用于多旋翼飞行器以及飞机或飞翼的免费软件和开放硬件的列表. 我们特别列出. 建立了一个活跃社区的项目，还有一些经典的项目，这些项目可能是遗留的，但很重要，有很多模组.

我们希望为您提供一些从哪里开始的指导，并向您展示无人机领域开源开发的全部内容.

&gt; **警告**
 &gt; 作为创造者、机械师、观察员和飞行员，您**对您的无人机及其所做的事情负责**. 您有责任避免损害并且不伤害任何人或动物.
&gt; 您还有责任遵守您所在国家/地区的当地法规，并了解前往何处以及如何飞行，以将对他人和您自己的风险降到最低.
&gt; 请尊重 [good airmanship](https://en.wikipedia.org/wiki/Airmanship).

&gt; **警告**
&gt; 在过去和最近的战争和**军事冲突**中，各方利用无人机（有时甚至是自制飞机）来发现和攻击对手.
&gt; 我对这项技术的意图是对技术和自然进行和平的研究和学习，而不是杀人！ [stopkillerrobots.org](https://www.stopkillerrobots.org)



## Airframes

无人机的机身取决于飞机的类型，并针对其用途进行了优化. 是用于赛车的高速、用于杂技自由泳的提高敏捷性、用于拍摄的重型举重机、长距离观察……. 这种要求导致了不同的机械和材料，并考虑到 DIY 方面.

您还会发现很多商用车的备件或改装件/扩展件，我们在此未列出！

&gt; **注意**
 &gt; 对于初学者来说，尤其是对于初学者来说，从头开始构建无人机是一项**相当具有挑战性的任务**. 如果你的时间有限.
 &gt; 因此，最好先尝试现有的解决方案或套件，这样您就不会过早陷入困境并拥有一本方便的手册. 稍后，如果您获得了更多经验并知道如何避免常见陷阱，您可以尝试不同的模组或从自定义构建开始.
&gt; 另请参阅： [My Raspberry Pi drone: the story so far by Matchstic](https://www.youtube.com/watch?v=ZCOlT_sz6Gs).

### Multicopters 🚁

直升机采用不同的材料制造，从铝/碳型材到 CNC 切割再到全 3D 打印外壳，并且针对不同数量的转子（双...八角）具有不同的配置：

* [NanoLongRange](https://www.thingiverse.com/thing:4769576) - 3D 打印框架，主要采用 18650 锂离子电池和一体化板，2021 年.
  * [Discovery Edition](https://www.thingiverse.com/thing:5428365) - 优化框架，带集成电池座，2022 年.
  * [NanoLongRange 2](https://www.thingiverse.com/thing:4818009) - 配备 GPS，稍轻，有 3 种型号，也适用于 21700 电池，2021 年.
* [NLR35](https://www.thingiverse.com/thing:5428923) - 更轻，与 NLR 类似，但采用 21700 电池，2022 年.
* [Ultimate 3D printable Cinewhoop](https://www.thingiverse.com/thing:4502805) - 2020.
* [TinyTina](https://blog.prusaprinters.org/how-to-build-a-3d-printed-micro-drone_29310/) - 3D 打印百日咳，2018 年.
* [Heavy Lift Quadcopter Frame](https://www.thingiverse.com/thing:4089842) - 碳数控切割，2020 年.
* [The CogniFly](https://thecognifly.github.io) - 适用于研究、群体和室内的坚固框架，配备 RPI 配套计算机，2021 年.
* [TBS Source One](https://github.com/tbs-trappy/source_one) - 碳纤维赛车车架，2021 年进行了 5 次修订.
* [TBS Source Two](https://www.team-blacksheep.com/products/prod:source_two_5in) - 碳纤维赛车车架，2019 年.
* [TBS Source Podracer](https://github.com/ps915/source_podracer) - 3D 碳纤维赛车车架，2020 年.
* [TBS Source V](https://www.team-blacksheep.com/products/prod:source_v) - 5 英寸碳纤维赛车车架，2021 年.
* [TBS Source X](https://github.com/ps915/source_x) - 碳纤维赛车车架，2019 年.
* [AESIR II](https://www.thingiverse.com/thing:4868250) - 模块化和定制 3D 碳框架，2021 年.
* [Foldable Drone Frame](https://www.thingiverse.com/thing:2004357) - 3D 打印，带万向节选项 2017.
* [OpenRC Quadcopter](https://www.thingiverse.com/thing:793425) - 3D 打印封闭式外壳，2015 年.
* [Hovership MHQ2](https://www.thingiverse.com/thing:511668) - 3D 打印可折叠，2014 年.
* [Crossfire 2](https://www.thingiverse.com/thing:234867) - 巨大的四边形 3D 打印，2014 年.
* [Spyda 500](https://www.thingiverse.com/thing:160607) - 巨大的四边形 3D 打印，2013 年.

### Fixed Wing / Planes 🛩️

传统的遥控飞机是使用轻木和箔片覆盖的机翼裂片制成的. 商业模型经常使用泡沫，您也可以通过 CNC 和激光切割泡沫来创建机翼轮廓. 完全 3D 打印的飞机也是可能的，您可以使用碳棒进行粘合和加固.  （商业）3D 打印模型社区也不断壮大，例如 [Craycle Hobby](https://craycle.com/), [Eclipson airplanes](https://www.eclipson-airplanes.com/),[3D lab print](https://3dlabprint.com/product-categ或者y/printable-airplanes/), [Plane Print](https://www.planeprint.com/) , [OWLplane](https://owlplane.com/) 或者 [rc-jetprint.de](https://rc-jetprint.de/en/) 使用轻质 PLA 来减轻重量.

* [HAWk Modular RC Wing Airplane v1](https://www.printables.com/de/model/422806-hawk-modular-rc-wing-airplane) - 3D 打印 LW-PLA 1m++ 推/拉机翼，完整 BOM + 手册文档，2023 年.
* [V-Tail Aircraft for Long Range FPV & Autonomous Missions - by AeroStuff FPV](https://www.youtube.com/watch?v=sTjXVeo_lpQ) - 使用折叠的 depron 面板作为 V 型尾推杆的身体和机翼.
* [Highly Modular Design -1 (HMD1)](https://forum.flitetest.com/index.php?threads/large-modular-uav-design.69987/) - 用于研究的 3D 打印 ABS V 型尾翼飞机，2022 年.
* [Ranger V2](https://craycle.com/product/ranger-v2-800-mm-3ch-trainer-stl-file/) - 低于 1m 的推力教练机，2022 年.
* [Berkik 3 wing](https://www.youtube.com/watch?v=ZA8fGOzJB10) - 1.3m 德普隆机翼，2021 年.
* [LukiSegler](https://www.printables.com/de/model/76098-lukisegler-electric-rc-glider) - Glider, 2021.
* [SakhWing](https://www.thingiverse.com/thing:4547317) - 类似 Drak 的固定翼，印有 PETG，2020 年.
* [GemINIce](https://www.youtube.com/watch?v=PcScS4Cj_Iw&list=PLEH_vTrFddgP8bRQFMK_z8rwmRth60Fen) - 2 架 dpron 飞机，2016 年.
* [Joywing](https://www.youtube.com/watch?app=desktop&v=X6hJCQNxVzs) - 简单的比赛翼，2019.
* [Eclipson Model V](https://www.thingiverse.com/thing:4011218) - 大部分是带轮子的 3D 打印商用飞机，2019 年.
* [Eclipson Model Y](https://www.thingiverse.com/thing:2752892) - 主要是带轮子的 3D 打印商用飞机，2018 年.
* [Northern Pike](https://www.thingiverse.com/thing:3040294) - 36 英寸固定翼 3D 打印，2018 年.
* [Moose](https://www.thingiverse.com/thing:3023606) - PLA 制成的 1m 牵引飞机，2018
* [Supernove](https://www.thingiverse.com/thing:2187747) - 喷气式推杆遥控飞机.
* [RC Flying Wing](https://www.thingiverse.com/thing:2044074) - 低于 1m 的 3D 打印推杆飞机 2017 年.
* [GASB Three](https://www.thingiverse.com/thing:3605665) - 3D 打印固定翼，2019 年.
* [GASB Two](https://www.thingiverse.com/thing:1831295) - 固定翼喷气式飞机 3D 打印，采用电动涵道风扇 (EDF) 代替经典螺旋桨，2016 年.
* [GASB One](https://www.thingiverse.com/thing:1659724) - 80cm fixed wing 3D printed, developed in 6 revisions, 2016.
* [Red swan](https://www.thingiverse.com/thing:453090) - 1950mm 带翼肋的印刷飞机，Red Duck 模型的后继者，2014 年.
* [Le Fish glider](https://lefish.fandom.com/wiki/Building_Le_Fish#Plans) - 带有大量混音的开源特技滑翔机，2005 年.

### VTOLs 🚀

垂直起降是从直升飞机转变为滑翔翼的飞行器，使其非常容易启动/着陆，但需要更复杂的机械装置，并且翼尖比固定翼更重.

* [VTOL in 5 revisions](https://www.youtube.com/watch?v=gPEeCjVrTBw) - 3D 打印和泡沫，2018 年.
  * [wing profile](https://www.printables.com/de/model/261434-vase-mode-wing) - 使用 LW-PLA 3D 打印机翼轮廓.
* [bicopter kit](https://hackaday.com/2018/08/27/the-best-new-quad-is-a-bicopter/) - 数控碳，2018.

## Batteries & Power Control 🔋

商用锂电池组在 RC 中很常见，但可以替换为基于 18650 的定制锂离子电池组. 板载电源总线直接驱动ESC和FC，提供5V输出为板载设备供电.

* 18650 锂离子电池组
  * [Using Li-Ion Battery Pack for Long Range FPV Flying](https://oscarliang.com/li-ion-battery-long-range/) - 4S 和背景信息，2023 年.
  * [build a „LongRange“ Lithium Ion Battery](https://blog.seidel-philipp.de/diy-build-a-longrange-lithium-ion-battery/) - 4S 3000mAh，2020 年.
  * [DIY FPV Goggle Battery Pack](https://nuxnik.com/diy-fpv-goggle-battery-pack/) - 适用于谷歌，带充电表和 3D 保护壳，2021 年.
  * [18650 spaceholder](https://www.printables.com/de/model/1181-18650-improved-spacerholder) - 3D 打印让包装更简单，2023 年.
* 太阳能飞机
  * [Solar Dragon - Solar Plane Might Be Able To Last Through The Night](https://hackaday.com/2022/08/06/solar-plane-might-be-able-to-last-through-the-night/) - 带有 PV 计划肋骨的飞机，2022 年.
  * [rctestflight series](https://www.youtube.com/watch?v=1OGrDvInUAY) - 8 小时 30 小时充满太阳能电池的固定翼，具有出色的测量和背景信息（[might last 24hrs](https://hackaday.com/2022/09/27/24-hours-of-le-airplanes/)), 2022.
* [diyBMS v4](https://github.com/stuartpittaway/diyBMSv4) - 锂离子电池组的电池管理 PCB 和固件.


## Motor Control ⚙️

通常使用无刷直流电机 (BLDC)，因为其功率大、精度高. 每个电机都需要电子速度控制器 (ESC).

* [BLheli_S](https://github.com/bitdump/BLHeli) - 具有细粒度控制的流行 ESC 固件.
* [BlueJay](https://github.com/mathiasvr/bluejay)  - BLheli 前叉，用于控制无刷电机的数字 ESC 固件. 更多功能，如自定义旋律. 自2020年起.
* [MESC FOC ESC](https://github.com/davidmolony/MESC_FOC_ESC) - STM32 basrd ESC 的开放硬件和固件.
* [ESC Configurator](https://github.com/stylesuxx/esc-configurator) - 用于设置 BLHeli / Bluejay ESC 的 Web 应用程序.
* [PIDtoolbox](https://github.com/bw1129/PIDtoolbox)  - 将 PID 设置调整为最大. 您的特定型号的性能.

## Flight Control 👨‍✈️

现代自动驾驶软件需要基于 STM32 的 F4/F7 芯片代板，通常不再支持 NAZE32、CC3D、ArduPilot 等传统板.大多数项目都基于 Baseflight / Cleanflight 固件和桌面配置器.

* [INAV](https://github.com/light/inav) - 专注于基于 GPS 的飞行计划/机翼和直升机的自主飞行.
* [betaflight](https://github.com/betaflight/betaflight) - 专注于机翼和直升机的赛车和敏捷性.
* [EmuFlight](https://github.com/emuflight/EmuFlight) - 专注于现代算法.
* [dRonin](https://github.com/d-ronin/dronin/) - 支持Openpilot和其他目标板.
* [Ardupilot](https://ardupilot.org)  - 完整的生态系统，包括机翼和直升机甚至陆地或水上交通工具的专业/研究用途. 很多信息、经验和可能性，但也比 INAV 更复杂.
* [dRehmflight](https://github.com/nickrehm/dRehmFlight) - 专用于 VTOL 及其在飞行过程中的转换，仅限 Teensy Boards.
* [Rotorflight](https://github.com/rotorflight/rotorflight) - 传统单旋翼直升机的固件.
* [CleanFlight](https://github.com/cleanflight/cleanflight) - 基础飞行的遗留叉子，失速.
* [BaseFlight](https://github.com/multiwii/baseflight) - Wii 陀螺仪黑客和 8 位时代的遗留和最古老的固件，失速.
* [QUICKSILVER firmware](https://github.com/BossHobby/QUICKSILVER) - ?.
* [Paparazzi UAV](https://github.com/paparazzi/paparazzi) - ?.
* [LibrePilot](https://github.com/librepilot/LibrePilot) - 自 2018 年起陷入停滞.
* [Risc V Powering a 3D Printed Drone](https://www.youtube.com/watch?v=TJCeLOiP7lU) - DIY 四轴飞行器上的 RISCV CPU 实验.

## RC Transmitters & Handcontroller 🎮

无线电控制发射器（RC TX，您这边）支持扩展托架 [JR / JR lite formfactor](https://github.com/pascallanger/DIY-Multiprotocol-TX-Module/blob/master/docs/Module_BG_4-in-1.md) 和串行接口以适应不同的无线电协议. 另请参见地面站.
大多数接收器（RX、无人机侧）支持 Crossfire (CSRF) 等标准串行协议来与 FC 通信.

* [EdgeTX](https://github.com/EdgeTX/edgetx) - OpenTX 的后继者正在积极开发中.
* [freedomTX](https://github.com/tbs-fpv/freedomtx) - OpenTX 分叉，自 2020 年起停止.

* [OpenTX](https://github.com/opentx/opentx) - 适用于流行手持发射器的固件，包括桌面管理器和声音包.
* [inav-opentx-sounds](https://github.com/JyeSmith/inav-opentx-sounds) - 模式的插件声音.
* [transmitter-sound-pack](https://inavfixedwinggroup.com/guides/transmitter-models/transmitter-sound-pack/) - INAV 声音和完整的翅膀配置.
* [VTx](https://github.com/teckel12/VTx) - 精简 betaflight Lua 脚本以仅控制您的 VTX.
* [betaflight-tx-lua-scripts](https://github.com/Matze-Jung/betaflight-tx-lua-scripts) - 扩展 BF lua 脚本.
* [opentx-lua-widgets](https://github.com/Matze-Jung/opentx-lua-widgets) - 更多用于呈现遥测数据的 UI 小部件.
* [opentx-lua-running-graphs](https://github.com/Matze-Jung/opentx-lua-running-graphs) - 更多可视化图表作为小部件.
* [OpenTX-Pong](https://github.com/SpechtD/OpenTX-Pong) - 适合您的 TX 的简单游戏.
* [Ardino Transmitter for ELRS](https://github.com/kkbin505/Arduino-Transmitter-for-ELRS) - 基于 Arduino 的简单游戏手柄，如手持发射器
* [OpenAVRc](https://github.com/Ingwie/OpenAVRc_Hw) - 基于 Arduino Mega2560 板的定制 TX.
* [ER9X](http://www.er9x.com) - 9XR 手持发射器的替代固件.

### Modules 🧩

用于建立自定义无线电链路的硬件和固件. 如今通常是双向链路，因此纯 TX/RX 侧.

* [Multi Module](https://github.com/pascallanger/DIY-Multiprotocol-TX-Module) - 支持不同的协议，如 FrSky、FlySky、Walkera、Futaba 等.
* [ExpressLRS](https://github.com/ExpressLRS/ExpressLRS)  - ELRS 可实现长距离或更好的延迟. 支持. 刷新一些现有硬件，还提供 868/915 MHz 或 2.4 / 5.8 GHz 的商业模块.
  * [ELRS Airport Firmware](https://github.com/ExpressLRS/ExpressLRS/pull/1904) - 2 路链路用于更复杂的遥测下行链路.
* [mLRS](https://github.com/olliw42/mLRS) - Mavlink 兼容 LRS.
* [openLRSng](https://github.com/openLRSng/openLRSng) - 下一代 OpenLRS，自 2018 年起陷入停滞.
* [Raven LRS](https://github.com/RavenLRS/raven) - 劳拉，2019 年.
* [OpenSky](https://fishpepper.de/projects/opensky/) - FrSky 模块的替代固件，2016.
* [DeviationTX](https://deviationtx.com/) - Walkera 的替代固件，2016.

## VTX 📺

视频发射器 (VTX) 是无人机上的模拟或数字无线电发射器，通常发送前置摄像头的视频流（第一人称视角 - FPV），但也可以传输任意信息或在无人机和地面站之间建立某种规则的双向链路，还提供控制上行链路等.另请参见地面站.

* [OpenHD](https://github.com/OpenHD/Open.HD)  - 在空中和地面使用 2.4 / 5.8 GHz WiFi 硬件和 SBC，提供视频和遥测下行链路以及可选的控制上行链路. 尝试开发更高效的专用硬件板.
* [RubyFPV](https://rubyfpv.com)  - 使用 2.4 / 5.8 GHz WiFi 硬件和 RPI 提供视频和遥测下行链路以及可选的控制上行链路. 没有提供源代码，但提供插件系统.
* [Wifibroadcast NG](https://github.com/svpcom/wifibroadcast) - 使用 2.4 / 5.8 GHz WiFi 硬件和 RPI 提供视频和遥测下行链路.
* [DroneBridge](https://github.com/DroneBridge/DroneBridge) - 使用 2.4 GHz wifi 硬件和 RPI、ESP32 和 Android 应用程序进行双向链接， [Comparison](https://dronebridge.gitbook.io/docs/comparison) 到这里的其他协议.
* [EZ Wifibroadcast](https://github.com/rodizio1/EZ-WifiBroadcast) - 最古老也是第一个基于 wifi 的 VTX 设置.
* [wtfos](https://github.com/fpv-wtf/wtfos) - 生根并修改 DJI FPV 发送器和接收器.
* [DigiView-SBC](https://github.com/fpvout/DigiView-SBC) - 接收 DJI 高清信号，alpha 2021.
* [OpenVTx](https://github.com/OpenVTx/OpenVTx) - 用于开放硬件模拟 VTX 的免费固件.
* [VTX Power Measure](https://github.com/mrRobot62/vtx_power_measure) - 对 Immersion RF-Meter V2 进行 Python 脚本编写.

## Camera & Gimbals 🎥

摄像机向板载视频发射器提供下行链路或以更高质量记录为 DVR. 另请参阅 VTX 了解允许您进行不同相机设置的自定义系统.

* [Gyroflow](https://github.com/gyroflow/gyroflow) - 使用 IMU 传感器数据来平滑高清视频录制.
* [OpenHD on thermal cameras](https://openhd.gitbook.io/open-hd/hardware/cameras) - 如何使用 RPI 读取该传感器.
* [RC Headtracker](https://github.com/dlktdr/HeadTracker)  - 当您转动谷歌时也转动相机万向节. 基于Arduino和蓝牙.
* [STORM32BGC](https://github.com/olliw42/storm32bgc) - 固件和无刷万向节控制器.
* [Open Brushless Gimbal](https://www.thingiverse.com/thing:110731) - 2013.

## GPS 🛰️

 GPS 等全球导航系统可以确定无人机的当前位置. 消费级 GPS 模块价格便宜，但有些模块可以进行调整，以获得更好的后处理或实时精度.

* [GNSS SDR](https://gnss-sdr.org) - 用于处理 SDR 硬件无线电后端接收的 GPS、百度、GLONASS 无线电信号的软件工具链.
* [rtklib](https://www.rtklib.com)  - 软件工具链，通过应用实时或后处理消除干扰来提高 GNSS 信号的精度.  SDR或一些商用GPS模块记录的信号.
* [Vicon MavLink](https://github.com/bo-rc/ViconMAVLink) - 通过商业光学系统为整个无人机群提供室内定位.

## Sensors 🌡️

无人机使用更多传感器，如指南针、气压计、空速或电流来增加位置估计，或显示系统性能

* [QLiteOSD](https://github.com/Qrome/QLiteOSD) - 基于 ESP32 的 OSD，无需 FC 即可读取传感器.
* [3D Printed Drone Build - How to Wire OpenHD and Ultrasonic Abstacle Avoidance](https://www.youtube.com/watch?v=HNR1mqUDpoE) - 用于四轴飞行器和 OpenHD 团队游戏的超声波避障.

See [Ardupilot - Optional hardware](https://ardupilot.org/copter/docs/common-optional-hardware.html) 以获得更多想法.

## Video Receivers 📶

 Google 有模块托架来支持不同的无线电协议或 HDMI 输入. 另请参阅 VTX 了解允许您进行不同相机设置的自定义系统.

* [DIY Homemade FPV Monitor](https://hackaday.io/project/160893-diy-homemade-fpv-monitor) - 具有多样性的 5,8GHz 模拟显示.
* [FENIX-rx5808-pro-diversity](https://github.com/JyeSmith/FENIX-rx5808-pro-diversity) - 开放硬件 5,8GHz 模拟模块，为谷歌提供多样性.
  * [rx5808 pro divesity](https://github.com/sheaivey/rx5808-pro-diversity)
* [rpi-rx5808-stream](https://github.com/xythobuz/rpi-rx5808-stream) - 基于 RPI 的 5.8GHz 模拟，具有多样性流媒体服务器.

## Antennas and Trackers 📡

收发器和接收器可以通过自定义天线配置进行调整，跟踪器可以支持定向天线. 他们使用多个接收器和多样性或遥测技术来指向您的无人机.
这是 VLOS 飞行之外更专业的设备，新手飞行员不需要. 还有一些方法可以使用 4G 进行视频和控制链路以实现额外扩展.

* [u360gts](https://github.com/raul-ortega/u360gts/) - 使用 F2/F3 控制器进行控制的 360° 电机跟踪器，固件 + 硬件 + 外壳，2020 年.
* [AntTracker](https://github.com/zs6buj/AntTracker) - 基于伺服，使用 F1 / ESP8266 / ESP32 控制器，2019 年.
* [open360tracker v2](https://www.thingiverse.com/thing:2568906) - 简化设计，所有部件均采用摇头灯.
* [open360tracker](https://github.com/SamuelBrucksch/open360tracker) - 360°伺服跟踪器2016.
  * [Amv-open360tracker](https://github.com/raul-ortega/amv-open360tracker) - 叉 2016.
  * [Amv-open360tracker 36bit](https://github.com/ericyao2013/amv-open360tracker-32bits) - 叉 2016.
* [Ghettostation Antenna Tracker](https://www.thingiverse.com/thing:547358) - 不同的叉子 2014 年.
* [DIY Helical Antenna For Long Range FPV](https://www.youtube.com/watch?v=aH0cW9XJ4D4) - 用于带有 3D 打印骨架的模拟谷歌的 5,8GHz 螺旋定向天线.
* [Cloverleaf Antenna - Build Instructions](https://www.youtube.com/watch?v=JGm9ESx4yzE)- 用于模拟视频传输的 5.8GHz 全向天线.

## Telemetry & Logs 📊

传感器值和控制信息通过通用串行协议共享，这些协议可以记录在 FC 的内部 SD 卡上（黑匣子），或传输到您的 TX 手机或地面站. 可用于寻找丢失的无人机，以及调试和调整 PID 和飞行行为

* [MAVlink](https://github.com/mavlink/mavlink) - 来自业余爱好者的现代可扩展协议......商用无人机.
* [Cyphal](https://opencyphal.org)  - Fka.  UAVCAN 工业专用无人机总线系统.
* [YAMSPy](https://github.com/thecognifly/YAMSPy) - 使用 Python 读取 MSP 串行协议.
* [LuaTelemetry](https://github.com/teckel12/LuaTelemetry) - OpenTX / EdgeTX 脚本，可根据遥测数据流呈现实时驾驶舱和地图.
* [betaflight-tx-lua-scripts](https://github.com/betaflight/betaflight-tx-lua-scripts) - 用于显示遥测和控制（例如 CAM、VTX 设置）的脚本.
* [otxtelemetry](https://github.com/olliw42/otxtelemetry) - OpenTX / EdgeTX 脚本添加 Mavlink 支持.
* [INAV blackbox viewer](https://github.com/iNavFlight/blackbox-log-viewer) - 将传感器/电机值渲染为视频叠加 OSD.
* [INAV blackbox tools](https://github.com/iNavFlight/blackbox-tools) - 转换为 CSV 时间序列文件或可视 OSD 叠加.
* [flightlog2x](https://github.com/stronnag/bbl2kml) - 将 INAV、OpenTX 等的黑盒日志转换为 CSV、GPX、KML，并以不同的性能风格单独渲染轨迹和轨迹 [GUI](https://github.com/stronnag/fl2xui).
* [UAVLogViewer](https://github.com/ardupilot/uavlogviewer) - Ardupilot 日志的 Web 应用程序.
* [OSD-subtitles](https://github.com/kristjanbjarni/osd-subtitles) - 将 Blackbox 日志渲染到 OSD 作为字幕，以便与视频文件同步播放.
* [Dashware](http://www.dashware.net/dashware-download/) - 黑盒日志的闭源 OSD 渲染.
* [PID-Analyzer](https://github.com/Plasmatree/PID-Analyzer) - 读取黑匣子并调整 PID 控制变量. 
* [openXsensor](https://github.com/openXsensor/openXsensor) - 转换和改变遥测协议.
* [OpenLog](https://github.com/sparkfun/OpenLog) - 和 [blackbox](https://github.com/thenickdude/blackbox/) 黑盒数据记录器的固件（现在通常是主 FC 的一部分）.

## Mission Control & Basestation 🗺️

笔记本电脑/平板电脑上的地面控制站 (GCS) 可以在长距离/长时间飞行期间更好地概述飞行参数和任务控制位置. 另请参阅 [Ardupilot.org - Choosing GCS](https://ardupilot.org/copter/docs/common-choosing-a-ground-station.html).

* [mwptools](https://github.com/stronnag/mwptools)  - 航点任务规划器，特别是. 用于 INAV，包括 INAV 雷达和 ADS-B 源.
* [APM Planner 2.0](https://ardupilot.org/planner2/) - 兼容 Mavlink，具有 MP 和 Q Groundcontrol 的经验.
* [QGroundControl](https://github.com/mavlink/qgroundcontrol) - Mavlink、桌面版和移动版.
* [MissionPlanner](https://ardupilot.org/planner/index.html)  - 航点任务规划，特别是. 对于Ardupilot.
* [MAVProxy](https://ardupilot.org/mavproxy/) - 命令行和 GUI 任务规划器以及遥测查看器和处理器.
* [BulletGCSS](https://github.com/danarrib/BulletGCSS) - 使用 GSM 和 MQTT 实现超长距离链接.
* [Dreka GCS](https://github.com/Midgrad/Dreka) - 新的 GCS（目前有限但更现代的外观和感觉）.

## Companion Computers & Integration 💻

您的 FC 专注于机动的实时控制，而其他计算机则为更复杂的数据处理添加资源，另请参阅 [Arudpilot.org - Companion Computers](https://ardupilot.org/dev/docs/companion-computers.html) 以及上述数字 VTX 系统.

* [öchìn CM4](https://github.com/ochin-space/ochin-CM4) - FC专用RPI计算模块载板
* [APsync](https://ardupilot.org/dev/docs/apsync-intro.html) - 针对不同 SBC 的 Mavlink 重点操作系统.
* [RPanion](https://www.docs.rpanion.com/software/rpanion-server) - Mavlink 聚焦 RPI 图像.
* [ROS](https://github.com/ros/ros) - 机器人操作系统，用于处理更复杂和交互式的飞行.
* [DroneKit](https://github.com/dronekit/dronekit-python) - 多平台集成生态系统，包括 Mavlink 无线电链路.

## Computer Vision 🤖

 CV 是对您在无人机实时图像或录音中看到的内容进行处理. 这是关于航空测绘或机器学习驱动的飞行计划. 也可以看看 [UAV Mapping Guidelines](https://uav-guidelines.openaerialmap.org/).

* [OpenDroneMap](https://www.opendronemap.org/) - 将照片拼接到航空图像、计算 3D 模型等.
* [OpenAerialMap](https://github.com/hotosm/OpenAerialMap/) - 分享无人机拍摄的灾难响应等.
* [DroneDB](https://github.com/DroneDB/DroneDB) - 存储和存档无人机拍摄的照片和航空图像.
* [OpenAthena](https://github.com/mkrupczak3/OpenAthena) - 使用标记自动 GCP 检测
* [OpenMMS](https://www.openmms.org/) - 携带激光扫描仪的移动测绘系统.
* [BANet](https://github.com/lironui/BANet) - 航空图像区域的机器学习分割.
* [AVCBet](https://github.com/lironui/ABCNet) - 航空图像区域的机器学习分割.
* [Faster](https://github.com/mit-acl/faster) - 机器学习让无人机学会避开障碍物.
* [Fast-Planner](https://github.com/HKUST-Aerial-Robotics/Fast-Planner) - 学习无人机以避免球场上的障碍物.
* [Autonomous Drone Dodges Obstacles Without GPS](https://hackaday.com/2021/11/03/autonomous-drone-dodges-obstacles-without-gps/) - 基于 RPI 的 CV 和路线规划以及避障.
* [Drone-net](https://github.com/chuanenlin/drone-net) - ML 使用 YOLO v4 检测照片/视频中的四轴飞行器.
* [Fire Detection UAV](https://github.com/AlirezaShamsoshoara/Fire-Detection-UAV-Aerial-Image-Classification-Segmentation-UnmannedAerialVehicle) - 机器学习学习无人机来发现火灾.
* [DroneAid](https://github.com/Call-for-Code/DroneAid) - 机器学习通过紧急标记查找灾难响应人员.
* [AirPose](https://github.com/robot-perception-group/AirPose) - 从无人机角度进行机器学习人体姿势估计.


## Complete Systems 🎁

专用无人机和工具链可帮助解决特定主题

* [SearchWing](https://www.hs-augsburg.de/searchwing/de/willkommen/)  - 一架搜索救援遥控飞机，用于对海上大片区域进行目视检查，以营救欧盟海上边境难民船上的人员. 防水降落在特区母舰旁边.
* [Dronecoria](https://dronecoria.org) - 用木头制成的八轴飞行器作为重型升降机来掉落种子.
* [Crazyflie](https://www.bitcraze.io/documentation/system/platform/) - 一款不那么 FPV 无人机，使用定制模块和不同的技术进行群体控制.
* [ESP32 Drone](https://hackaday.io/project/188578-esp32-drone) - 没有传统的 FPV，但使用 ESP32 板的低成本四核，2022 年.
* [Wifree-copter](https://open-diy-projects.com/wifree-copter/) - 简易 3D 打印直升机，使用 RPI 作为 WIFI 遥控器，通过应用程序进行，2016 年.

## Security & Safety 🪂

### Simulators 🌐

在损坏任何硬件之前，您可以学习如何避免常见陷阱并使用手持 TX 通过虚拟飞行进行训练. 其他允许测试/基准自动驾驶仪在受控环境中工作.

对消费者最友好的训练模拟器是商业版，但也适用于 Linux、macOS（[Freerider Recarged](https://fpv-freerider.itch.io/fpv-freerider-recharged), [Liftoff](https://store.steampowered.com/app/410340/Liftoff_FPV_Drone_Racing/), [DRL Sim](https://thedroneracingleague.com/drlsim/), [Velocidrone](https://www.velocidrone.com/).

* [crrcsim](https://sourceforge.net/projects/crrcsim/) - 对于遥控飞机，2018 年.
* [Picasim](http://www.rowlhouse.co.uk/PicaSim/download.html) - 对于遥控飞机，闭源，SSS 的后继者，自​​ 2019 年起停止.
* FlightGear - 通常用于大型飞机，但可以与 FC 配对 良好的描述 [from PaparazziUAV](https://wiki.paparazziuav.或者g/wiki/FlightGear) 或者 [by Arduplane](https://ardupilot.或者g/dev/docs/simulation-2.html) f或者 simulation.
* [AirSim](https://github.com/microsoft/AirSim) - 由微软进行算法测试.
* [jMAVSim](https://github.com/PX4/jMAVSim) - 对于 Mavlink.
* [JSBsim](https://github.com/JSBSim-Team/jsbsim) - 与 Python、Matlab 的绑定.
* [GAZEBOsim](https://github.com/gazebosim/gz-sim) - 多机器人.
* ROS 支持所描述的模拟 [by PX4](https://docs.px4.io/master/en/ros/ros2_comm.html).

### Checklists 📋

故障可能会产生严重的后果，并且您的无人机可能会造成巨大的损坏. 为了避免不必要的风险，每次航班都必须提供分步协议和文件，以防您可能使用保险.

#### build power check

#### maiden flight check

* [iNav Pre-maiden Checklist](https://www.mrd-rc.com/tutorials-tools-and-testing/flight-controller-therapy/inav-pre-maiden-checklist-a-helpful-reminder-and-saver-of-foam/) 由 Mr.D 固定翼

#### regular flight check

* [Ardupilot Copter Checklist](https://ardupilot.org/copter/docs/checklist.html).

### ID Systems 🛂

我们与其他飞行员共享空域. 遥控直升机和飞机很难被发现，因此建议通过转发器系统分享您的位置. 这还可以跟踪非法操作.

 * 飞机的 ADS-B 发射机可以使用软件定义的无线电进行接收，可以使用廉价的 USB DVB-T 接收器来实现. 可以通过雷达扩展进行集成，例如 [mwp-radar-view](https://github.com/stronnag/mwptools/wiki/mwp-Radar-View), [Ardupilot ADS-B receiver](https://ardupilot.org/copter/docs/common-ads-b-receiver.html) 或在 OpenHD 中. 是 Mavlink 协议的一部分并出现在大多数 GCS 上. 也可以像这样在线查看 [adsb-exchange.com](https://globe.adsbexchange.com/).
* [INAV Radar](https://github.com/OlivierC-FR/ESP32-INAV-Radar) - LORA 无线电和 ESP32 广播位置并将其显示在您的 OSD 上.
* [SoftRF](https://github.com/lyusupov/SoftRF) - 无人机版，还支持FLARM等.
* [Glidernet](https://www.glidernet.org) - 在线分享 FLARM / ADS-B 位置.
* [Opensky Network](https://opensky-network.org) - 在线分享 ADS-B 位置.
* [ArduPilot RemoteID Transmitter](https://github.com/ArduPilot/ArduRemoteID) - FCC RemoteID 与 Mavlink 和 DroneCAN 集成.
* [WiFi RID capture](https://github.com/sxjack/unix_rid_capture) - 使用嗅探器捕获远程识别信号.

### Hacking & Hijacking 🔓

无线电链路本身是不安全的，并且很容易被干扰.

* [5.8GHz video demodulation](https://www.youtube.com/watch?app=desktop&v=rl8ACNnjPFA) - 使用 hack-rf SDR.
* [GPS jamming](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms) - 使用 BladeRF SDR 和 GNUradio 来阻止卫星.
* [GPS spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf) - 通过伪造地面卫星传输来控制其他无人机.
* [RemoteID Spammer/Spoofer](https://github.com/jjshoots/RemoteIDSpoofer) - ESP8266/NodeMCU 无人机 RemoteID 欺骗器
* [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD) - 半自主机器的 CVE.

## Accesoirs 🪠

通过 3D 打印，可以轻松为您的设备和模型获得有用的插件

* [Delta 5 race timer](https://github.com/scottgchin/delta5_race_timer) - 使用5.8GHz视频信号触发圈数计数器.
  * [RotorHazard](https://github.com/RotorHazard/RotorHazard) - 具有多节点和中央 RPI 服务器的后继者
* [Capture The Flag for drones](https://github.com/SeekND/CaptureTheFlag) - 模拟近距离团战旗帜的光学系统.
* 云台保护
* 支架和支架
* 运动摄像机安装座
* 转子护罩
* ...

### Mobile Apps 📱

可在您的移动设备上使用的免费且有用的应用程序. 可能不需要开源

* [SpeedyBee](https://www.speedybee.com/speedy-bee-app/) - 是用于 betaflight、iNAV、emuflight 的飞行控制器参数设置和黑盒日志阅读器的应用程序  [Android](https://play.google.com/store/apps/details?id=com.runcam.android.runcambf), [iOS](https://apps.apple.com/us/app/speedybee-app/id1150315028).
* [BLHeli_32](https://play.google.com/store/apps/details?id=org.blheli.BLHeli_32) - 应用程序用于配置BLHeli_32 ESC.
* [FPV Video Channelsorter 5.8GHz](https://play.google.com/store/apps/details?id=florian.felix.flesch.fpvvideochannelsorter) - 对可用频率上每个导频的频道进行排序.
* [UAV Forecast](https://www.uavforecast.com) - 查看天气预报、GPS 卫星、太阳活动 (Kp)、禁飞区和飞行限制 [Android](https://play.google.com/store/apps/details?id=com.uavforecast), [iOS](https://apps.apple.com/us/app/uav-forecast/id1050023752).
* [Go FPV](https://play.google.com/store/apps/details?id=com.vertile.fpv3d) - UVC 摄像机显示和捕捉应用程序，专为我的 DIY 第一人称视角护目镜而构建.

### Workbench 🧰

* [smoke stopper](https://oscarliang.com/smoke-stopper/) - 避免在组装过程中损坏昂贵的组件.
* [4AxisFoamCutter](https://github.com/rahulsarchive/4AxisFoamCutter) - 用泡沫制作空气动力学机翼.

## Legal Information 🏛️

根据您居住的国家/地区，空域的法律和法律规则可能会有所不同.

* [Luftfahrt Bundesamt](https://www.lba.de/DE/Drohnen/Drohnen_node.html) - 法律框架.
* [Deutsche Flugsicherung GmbH](https://www.dfs.de/homepage/de/drohnenflug/) - 进行测试和批准.
* [Digitale Plattform Unbemannte Luftfahrt](https://www.dipul.de/homepage/de/) - 地图平台，有替代方案 [Droniq App](https://play.google.com/store/apps/details?id=de.droniq.droniqapp&hl=de&gl=US).
* [Bundesnetzagentur](https://www.bundesnetzagentur.de/DE/Sachgebiete/Telekommunikation/Unternehmen_Institutionen/Frequenzen/Grundlagen/Frequenzplan/frequenzplan-node.html) - 🇩🇪 Zulässige Sendefrequenzen und -Leistungen.

## Communities 🗣️

如果您与他人分享您的想法和问题，每项爱好都会变得更加有趣和进步. 除了无人机飞行员社区之外，还有大量的改装者和黑客.

* [Dronecode foundation](https://www.dronecode.org) - MavLink、QGroundcontrol 和 PX4 的主页，是 Linux 基础的一部分.
* [FPV Freedom Coalation](https://fpvfc.org/) - 保证无人机的安全和安全.
* [Deutscher Modellflieger Verband e.V.](https://www.dmfv.aero) - 活动、当地社区、保证…….
* [Deutscher Aero Club e.V.](https://www.daec.de) - .

### Forums & Social Media

* [rcroups.com](https://rcroups.com) - 大多数项目都在这里提供支持.
* [diydrones.com](https://diydrones.com) - 对大多数项目、硬件和国家/地区进行分组.
* [rotorbuilds.com](https://rotorbuilds.com) - 定制构建的秘诀.
* [openrcforums.com](https://openrcforums.com) - 从过去到现在一直致力于开放模型.
* [Stackexchange Drones](https://drones.stackexchange.com/) - 是用于无人机构建的 Stack Overflow 问答.
* [reddit \\motorcopter](https://www.reddit.com/r/Multicopter/) - 从航班、坠机、维修、定制模组等一切内容.
* [reddit \\RCPlanes](https://www.reddit.com/r/RCPlanes/) - 除遥控飞机外的一切.
* [OscarLiang.com](https://OscarLiang.com) - 包含构建、配置和知识的重要博客.
* [intofpv.com](https://intofpv.com) - 提供有关 FPV 相关信息的论坛.
* [INAV fixed wing group](https://inavfixedwinggroup.com/)  - 论坛、博客、基于固定翼尤其是构建. 与INAV兼容的自动驾驶仪.
* [fpv-community.de](https://fpv-community.de) - 也可以自己做.
* [RC-Network.de](https://RC-Network.de)  - 关于船舶和汽车的自行建造. 非常广泛 [Wiki](https://wiki.rc-network.de/wiki/Hauptseite).
* [kopterforum.de](https://kopterforum.de) - 也可以自己做.

### Video Channels

* [Painless 360](https://www.youtube.com/c/Painless360) - 英国构建、改装和配置基础知识.
* [ArxangelRC](https://www.youtube.com/c/ArxangelRC) - BG 构建和配置以及（一点）映射.
* [Joshua Bardwell](https://www.youtube.com/c/JoshuaBardwell) - 美国，关于直升机的建造和一般技巧，口号“你今天会学到一些东西”.
* [PawelSpechalski](https://www.youtube.com/c/Pawe%C5%82Spychalski) - INAV核心团队，主要是直升机，口号是“快乐飞行”.
* [Andrew Netwon](https://www.youtube.com/c/AndrewNewtonAustralia) - AU，主要是飞机评论和建造提示.
* [Mr. D - Falling with style](https://www.youtube.com/c/MrDFallingwithstyle) - 英国，达伦，INAV.
* [CurryKitten](https://www.youtube.com/c/CurryKitten/) - 评论，还有 OpenHD 和 ExpressLRS.
* [MarioFPV](https://www.youtube.com/channel/UCX2UiZjg485tDoq_Yl4Pysw) - OpenHD、RubyFPV、WFG-NG 实验.
* [TreeOrbit](https://www.youtube.com/user/montreetormee) - OpenHD、RubyFPV 实验.
* [flitetest.com](https://flitetest.com) - 电视节目，不寻常的 DIY 搭建.
* [Livyu FPV](https://www.youtube.com/c/LivyuFPV/videos) - DIY 无人机电子设备的飞行镜头和维修视频.
* [Adam G does FPV](https://www.youtube.com/c/AdamGdoesFPV) - 构建、模组和基础知识.
* [BLuefish](https://www.youtube.com/channel/UCmULLc8W-knTqiFqJgw3-FA) - 构建、INAV、远程.
