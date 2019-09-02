<div class="github-widget" data-repo="kyleterry/awesome-radio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Radio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精彩无线电资源的精选列表.  受到令人敬畏的启发 -  *.

 我最近拿出了我的CB收音机并将它安装在我的卡车上.  这启发了我
创建一个我发现的所有无线电相关资源的开源存储库
有用的和我关于这个主题的笔记.

该项目针对的是喜欢无线电通信各个方面的黑客.
虽然很多这种技术无法被公民使用，但受到严格监管
 美国联邦通信委员会（FCC），了解它的任  我一直对此感兴趣
学习广播的来龙去脉，以及听取新旧故事.

## General

### Links

* [Radio (wikipedia)](http://en.wikipedia.org/wiki/Radio)
* [Radio Spectrum (wikipedia)](http://en.wikipedia.org/wiki/Radio_spectrum)
* [Skywave (skip) (wikipedia)](http://en.wikipedia.org/wiki/Skywave)
* [来自a的神秘信号
  直升机（http://www.windytan.com/2014/02/mystery-signal-from-helicopter.html）
* [Portable SDR](http://hackaday.io/project/1538-PortableSDR)
* [N0NBH's Solar-Terrestrial Data](http://www.hamqsl.com/solar2.html) - 当前
太阳地面数据，解释它们对HF传播的影响
和传播预测.

## CB

公民频段无线电或CB是一种专用于开放使用的双向无线电频谱
 几乎任何目的的任何人.  在美国和许多其他国家，它
 不需要许可证即可运营.  CB由26.965之间的40个频道组成
MHz和27.405 MHz，频道09专门用于紧急情况.

CB在卡车司机和无线电爱好者中更受欢迎，但它的实用性
 并不止于此.  这对于热门卡车运输的长途旅行非常有用
 路线.  您可以调到第19频道（非官方卡车司机的频道）并获得
实时交通更新，备用路线和事故警告.

如果有一个好的天线可以正确调谐，这是一个典型的预期范围
你的CB大概是2到5英里（3.2到8公里）.

### General Use

 我在Jeep和卡车司机论坛上找到了很多关于我的信息.  来自我自己
经验，似乎大概有一半的CB传输我听到包括一个句柄
 某种.  我也听到很多咒骂，所以我不会不小心出汗
让“他妈的”或“狗屎”走了.

 CB是公开的.  非常公开.  这似乎是一种“没有什么”的东西，但随着
当前这一代人几乎只使用手机，很容易忘记
使用“原始”作为CB无线电的东西基本上是[广播到
the world](http://en.wikipedia.org/wiki/Citizens_band_radio#Working_skip).

卡车司机倾向于使用频道19.这是一个监控流量的好渠道
conditions.

 频道9仅用于紧急情况.  这个频道没有一般的喋喋不休.  如果你
被打破了，或者你的车着火，除了拨打911，这是一件好事
传输信道寻求帮助.

在波特兰附近，我在第6,17和28频道听到很多喋喋不休的声音
良好的娱乐对话渠道.

### SWR

[SWR](http://en.wikipedia.org/wiki/Standing_wave_ratio)或驻波比
是将天线连接到收音机时的效率测量.

 最佳比例为1：1，尽管最终可能会达到1.3：1左右.  什么
高于2：1应该被视为禁忌，因为它会损坏你的收音机和
 传播不好.  阅读[如何调整
SWR](http://www.rightchannelradios.com/tuning-cb-antenna-adjusting-swr).

### Installing a mobile CB

正确安装CB是关键A）不损坏您的无线电硬件和B）
在接收端和发送端获得良好的范围和质量.

遵循以下文章中的建议将确保您具有质量
setup.

### Links

* [Right Channel Radios](http://www.rightchannelradios.com/) - 良好的网上商店
用于零件，收音机，天线和支架.
* [CB Slang](http://www.cbslang.com/) - 大多是幽默，但有点帮助.
* [CB Slang (wikipedia)](http://en.wikipedia.org/wiki/List_of_CB_slang)
* [CB Talk and etiquette](http://www.jeepforum.com/forum/f8/cb-radio-etiquette-jeep-trail-1169815/)
* [Skip](http://cbradiomagazine.com/Articles/How%20to%20Shoot%20Skip.htm)
* [Silly CB Handles](http://www.somethingawful.com/news/cb-handles/)
* [CB FAQ](http://www.advancedspecialties.net/cb-radio-faq.htm)
* [Frequency Table](http://www.radioreference.com/apps/db/?aid=7731)

## SDR (Software Defined Radio)

软件定义无线电是一种定义典型组件的方法
 硬件，如滤波器和放大器，作为软件.  它已经存在了
但是，随着SDR运行所需的数字电子成本的增加
越来越便宜，我们看到黑客民间游戏和建设的增加
与SDR.

我想要这个部分的贡献者.

### Links

* [Gqrx](http://gqrx.dk/)
* [sdrsharp on .NET](http://sdrsharp.com)

### Hardware
* __推荐启动硬件_在低端，
  [RTL-SDR](http://sdr.osmocom.org/trac/wiki/rtl-sdr) 是一个超级便宜的USB
  加密狗，一个繁荣的社区建立在其周围.
*在成本范围的另一边， [pervices](http://www.pervices.com/)
  当您需要记录所有内容时，可以制作一些真正高吞吐量的PCIe设备
   交通有史以来.  软件和社区对此的支持不太好，
  虽然（你可以责怪@outofculture）.
*你也可以浏览[大
  清单]（https://gnuradio.org/redmine/projects/gnuradio/wiki/Hardware）
  兼容的硬件.
*天线是他们自己的选择和权衡体，我知道
  没有.

### Software
根据您使用的硬件，它可能附带一些演示软件
 玩弄.  这对于有机会看到一些波浪而言非常棒
 开始了解什么是可能的.  否则，[GNU
无线电]（https://gnuradio.org/redmine/）将用于您花费时间的地方.
它主要只是一个图书馆，但它也有一个支持组合的gui
 处理然后输出python的块.  一旦你更舒服，你
也可以使用GNURadio进行任何设备调整，设置和i / o，然后使用
numpy用于信号处理数学.

只是可视化和手动检查信号是学习的重要部分
如何与他们合作. [Baudline](http://www.baudline.com/) 是一个古怪的老人
 事情，但它是最好的.  预先警告学习UI不会来
容易对任何人.

## Amateur Radio (a.k.a Ham Radio)

 业余无线电的业余爱好有着悠久而自豪的传统.  第一台收音机
 业余爱好者是无线电技术的真正先驱.  业余爱好者&#39;发明&#39;和精致
大多数早期的无线电技术，是第一个传输音乐，广播的人
播放，并向少数拥有新收音机的人提供信息
receivers.

 第二次世界大战后，业余无线电的爱好蓬勃发展.  电台俱乐部兴起
在世界各地的学校里，孩子们每晚都回家建造一些新
 装置，或通过无线方式与某人聊天.  这些年轻人
成为技术专业的中流砥柱，并发展了很多
我们今天使用的现代技术.
([WIA](http://www.wia.org.au/licenses/foundation/about/))

[What is Ham Radio?](http://www.arrl.org/what-is-ham-radio)

### Links

*美国无线电中继联盟 -  [ARRL](http://www.arrl.org/)
*澳大利亚无线研究所 [WIA](http://www.wia.org.au/)
*英国无线电协会 -  [RSGB](http://rsgb.org/)
*巴基斯坦业余无线电协会 -  [PARS](http://www.pakhams.com/)
* [The International Amateur Radio Union](http://www.iaru.org/)
* [Japanese asteroid mission](http://www.arrl.org/news/amateur-radio-transponder-will-accompany-japanese-asteroid-mission-into-deep-space)
* [Slow-scan Television](https://en.wikipedia.org/wiki/Slow-scan_television)

我想要这个部分的贡献者.

### Amateur Radio License

* 在里面 [US](http://www.arrl.org/getting-licensed) 有三个许可证
  课程 - 技术员，一般和额外.
* [The Foundation Licence](http://www.wia.org.au/licenses/foundation/about/) 在
  Australia.
* [基础许可证]
  （http://rsgb.org/main/clubs-training/for-students/foundation/）在英国.
*在
  [Pakistan](http://www.pakhams.com/index.php?option=com_content&view=article&id=75&Itemid=92)
  首先你申请SWL（短波听众）会员资格然后你就是
  有资格[申请HAM
  许可证（http://www.pta.gov.pk/index.php?option=com_content&amp;view=article&amp;id=466%3Aamateur-wireless-license&amp;catid=138%3Aguidelines&amp;Itemid=349）.

## Public Health and Safety

美国的警察和火灾通常通过集群无线电进行通信.
这使得在没有主干跟踪的情况下使用普通接收器进行扫描很困难
 能力.  查看更多内容 [trunking](#trunking) 部分.

### Trunking

虽然并非严格针对公共健康和安全，但通常是第一个
在讨论集群无线电时想到的事情.

集群无线电是一种多重数字双向通信形式
组织可以在没有听力的情况下共享一小部分实际频率
 另一个组织的对话.  用户可以选择逻辑信道或
组和基站将找到一个空的频率进行传输.

### Links

* [Project 25](http://www.project25.org/)
* [Project 25 wikipedia](http://en.wikipedia.org/wiki/Project_25)
* [Trunked Radio wikipedia](http://en.wikipedia.org/wiki/Trunked_radio_system)
