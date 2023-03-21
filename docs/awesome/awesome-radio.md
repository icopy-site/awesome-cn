<div class="github-widget" data-repo="kyleterry/awesome-radio"></div>
## Awesome Radio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的无线电资源列表. 灵感来自 awesome-*.

我最近拿出我的 CB 收音机并将它安装在我的卡车上. 这启发了我
为我找到的所有无线电相关资源创建一个开源存储库
有帮助和我关于这个主题的笔记.

该项目针对喜欢无线电通信各个方面的黑客.
虽然很多这项技术不被公民使用并且受到严格监管
由 FCC 提供，只是了解它是很特别的. 我一直感兴趣
了解广播的来龙去脉，以及聆听新旧故事.

## General

### Links

* [Radio (wikipedia)](http://en.wikipedia.org/wiki/Radio)
* [Radio Spectrum (wikipedia)](http://en.wikipedia.org/wiki/Radio_spectrum)
* [Skywave (skip) (wikipedia)](http://en.wikipedia.org/wiki/Skywave)
* [来自一个神秘信号
  直升机](http://www.windytan.com/2014/02/mystery-signal-from-helicopter.html)
* [Portable SDR](http://hackaday.io/project/1538-PortableSDR)
* [N0NBH's Solar-Terrestrial Data](http://www.hamqsl.com/solar2.html) - 当前
日地数据，解释它们对高频传播的影响
和传播预测.

## CB

公民频段无线电，或 CB，是一种双向无线电频谱，专供以下人员开放使用
几乎任何目的的任何人. 在美国和许多其他国家，它
不需要经营许可证.  CB 由 26.965 之间的 40 个通道组成
MHz 和 27.405 MHz，09 频道专用于紧急情况.

CB 在卡车司机和无线电爱好者中更受欢迎，但它的实用性
不止于此. 非常适合乘坐流行的卡车进行长途旅行
路线. 您可以调到 19 频道（非官方卡车司机频道）并获得
实时交通更新、备用路线和事故警告.

给定一个经过适当调谐的好天线，一个典型的预期范围
您的 CB 大约是 2 - 5 英里（3.2 - 8 公里）.

### General Use

我在 Jeep 和卡车司机论坛上找到了很多我的信息. 来自我自己
经验，我听说大约一半的 CB 传输包括一个句柄
某种. 我也听到很多脏话，所以我不会不小心出汗
放开“他妈的”或“狗屎”.

 CB 是公开的. 非常公开. 这似乎是一种“无所事事”的事情，但随着
当前这一代人几乎只使用手机，很容易忘记
使用像 CB 收音机这样“原始”的东西本质上是 [广播到
the world](http://en.wikipedia.org/wiki/Citizens_band_radio#Working_skip).

卡车司机倾向于使用频道 19.这是监控交通的好频道
conditions.

 9 频道仅用于紧急情况. 这个频道没有一般的喋喋不休. 如果你
抛锚了，或者你的车着火了，除了拨打 911，这是一个很好的方法
发送求助的频道.

在波特兰附近，我在 6、17 和 28 频道听到很多谈话.这些是
娱乐谈话的好渠道.

### SWR

[SWR](http://en.wikipedia.org/wiki/Standing_wave_ratio), 或驻波比
是将天线连接到收音机时的效率衡量标准.

最佳比例为 1:1，但最终可能会达到 1.3:1 左右. 任何事物
高于 2:1 应被视为禁忌，因为它会损坏您的收音机和
传递不良. 阅读 [如何调整
SWR](http://www.rightchannelradios.com/tuning-cb-antenna-adjusting-swr).

### Installing a mobile CB

正确安装 CB 是 A) 不损坏无线电硬件和 B) 的关键
在接收端和发射端都获得良好的范围和质量.

遵循以下文章中的建议将确保您拥有高质量
setup.

### Links

* [Right Channel Radios](http://www.rightchannelradios.com/) - 不错的网上商店
用于零件、收音机、天线和支架.
* [CB Slang](http://www.cbslang.com/) - 主要是幽默，但有点帮助.
* [CB Slang (wikipedia)](http://en.wikipedia.org/wiki/List_of_CB_slang)
* [CB Talk and etiquette](http://www.jeepforum.com/forum/f8/cb-radio-etiquette-jeep-trail-1169815/)
* [Skip](http://cbradiomagazine.com/Articles/How%20to%20Shoot%20Skip.htm)
* [Silly CB Handles](http://www.somethingawful.com/news/cb-handles/)
* [CB FAQ](http://www.advancedspecialties.net/cb-radio-faq.htm)
* [Frequency Table](http://www.radioreference.com/apps/db/?aid=7731)

## SDR (Software Defined Radio)

软件定义无线电是一种定义组件的方法，这些组件通常是
硬件，如滤波器和放大器，作为软件. 它已经存在了一个
同时，但随着运行 SDR 所需的数字电子设备的成本变得
越来越便宜，我们看到越来越多的黑客玩和建造
与特别提款权.

我想要这个部分的贡献者.

### Links

* [Gqrx](http://gqrx.dk/)
* [sdrsharp on .NET](http://sdrsharp.com)

### Hardware
* __Recommended starter hardware__ 在低端，
  [RTL-SDR](http://sdr.osmocom.org/trac/wiki/rtl-sdr) 是超便宜的usb
  加密狗，围绕它建立了一个繁荣的社区.
* 在成本范围的另一边， [pervices](http://www.pervices.com/)
  制作一些真正高吞吐量的 PCIe 设备，供您需要记录所有内容时使用
  曾经的交通. 对此的软件和社区支持不太好，
  虽然（你可以责怪@outofculture）.
* 您也可以浏览 [big
  列表](https://gnuradio.org/redmine/projects/gnuradio/wiki/Hardware) 所有
  兼容的硬件.
*天线是他们自己的选择和权衡的主体，我知道这一点
  没有什么.

### Software
根据您使用的硬件，它可能会附带一些演示软件以
玩弄. 这对于有机会看到一些海浪和
开始了解什么是可能的. 否则，[GNU
Radio](https://gnuradio.org/redmine/) 将前往您将花费时间的地方.
它主要只是一个库，但它也有一个用于组合的辅助图形用户界面
处理块，然后输出 python. 一旦你舒服了，你
也可以只使用 GNURadio 进行任何设备调整、设置和输入/输出，然后使用
用于信号处理数学的 numpy.

只是可视化和手动检查信号是学习的一个有价值的部分
如何与他们合作. [Baudline](http://www.baudline.com/) 是一个简陋的老
东西，但这是最好的. 预先警告学习用户界面不会来
容易给任何人.

## Amateur Radio (a.k.a Ham Radio)

业余无线电的爱好有着悠久而自豪的传统. 最早的收音机
业余爱好者是无线电技术的真正先驱. 业余爱好者“发明”和改进
许多早期的无线电技术，并且是第一个传输音乐、无线电
向少数拥有新奇收音机的人播放和信息
receivers.

第二次世界大战后，业余无线电的爱好蓬勃发展. 无线电俱乐部如雨后春笋般涌现
在世界各地的学校里，孩子们每天晚上回家去建造一些新
装置，或通过无线与某人聊天. 这些年轻人
成为技术专业的中流砥柱，并发展了大部分
我们今天使用的现代技术.
([WIA](http://www.wia.org.au/licenses/foundation/about/))

[What is Ham Radio?](http://www.arrl.org/what-is-ham-radio)

### Links

* American Radio Relay League - [ARRL](http://www.arrl.org/)
* 澳大利亚无线研究所 [WIA](http://www.wia.org.au/)
* 英国无线电协会 - [RSGB](http://rsgb.org/)
* 巴基斯坦业余无线电协会 - [PARS](http://www.pakhams.com/)
* [The International Amateur Radio Union](http://www.iaru.org/)
* [Japanese asteroid mission](http://www.arrl.org/news/amateur-radio-transponder-will-accompany-japanese-asteroid-mission-into-deep-space)
* [Slow-scan Television](https://en.wikipedia.org/wiki/Slow-scan_television)

我想要这个部分的贡献者.

### Amateur Radio License

* 在里面 [US](http://www.arrl.org/getting-licensed) 一共有三个许可证
  类——技师、普通和高级.
* [The Foundation Licence](http://www.wia.org.au/licenses/foundation/about/) 在
  澳大利亚.
* [基金会许可证]
  (http://rsgb.org/main/clubs-training/for-students/foundation/) 在英国.
* 在
  [Pakistan](http://www.pakhams.com/index.php?option=com_content&view=article&id=75&Itemid=92)
  首先你申请 SWL (Short Wave Listener) 会员然后你是
  有资格[申请HAM
  许可证](http://www.pta.gov.pk/index.php?option=com_content&amp;view=article&amp;id=466%3Aamateur-wireless-license&amp;catid=138%3Aguidelines&amp;Itemid=349).

## Public Health and Safety

美国的警察和消防部门通常通过集群无线电进行通信.
这使得在没有中继跟踪的情况下很难使用普通接收器进行扫描
能力. 查看更多 [trunking](#trunking) 部分.

### Trunking

虽然不是严格针对公共健康和安全，但通常是第一个
谈论集群无线电时想到的事情.

集群无线电是一种数字双向通信形式，其中多个
组织可以在不听取的情况下共享一小部分真实频率
另一个组织的对话. 用户可以选择一个逻辑频道或
组和基站将找到一个空频率进行传输.

### Links

* [Project 25](http://www.project25.org/)
* [Project 25 wikipedia](http://en.wikipedia.org/wiki/Project_25)
* [Trunked Radio wikipedia](http://en.wikipedia.org/wiki/Trunked_radio_system)
