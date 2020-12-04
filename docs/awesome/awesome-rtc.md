<div class="github-widget" data-repo="rtckit/awesome-rtc"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Real Time Communications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;几乎同时交换媒体和数据的协议和方法.





## Server Software

### General Purpose

- [FreeSWITCH](http://freeswitch.org) -开源多协议，跨平台和软件交换.
- [Asterisk](http://asterisk.org) -支持多种协议和平台的PBX框架.

### SIP Servers

- [Kamailio](http://www.kamailio.org)  -运营商和提供商广泛部署的开源SIP服务器. 前身为OpenSER.
- [OpenSIPS](http://www.opensips.org) -开源SIP服务器，其根源在OpenSER（现为Kamailio）中.
- [Routr](https://routr.io) -用Node.js编写的轻量级SIP代理，位置服务器和注册器.
- [Sippy B2BUA](https://github.com/sippy/b2bua) -用Python编写的背对背用户代理服务器.
- [Flexisip](https://github.com/BelledonneCommunications/flexisip) -SIP服务器套件，包括代理，状态和群聊功能.

### Media Servers

- [Janus](https://janus.conf.meetecho.com) -轻量级的开源通用WebRTC网关.
- [RTPProxy](https://www.rtpproxy.org) -通用高性能RTP代理.
- [RTP:Engine](https://github.com/sipwise/rtpengine) -基于RTP和UDP的媒体流量代理，可用作内核模块.
- [mediasoup](https://mediasoup.org) -专门的WebRTC会议系统.
- [SEMS](https://github.com/sems-server/sems) -用于基于SIP的VoIP服务的开源媒体和应用服务器.
- [Jitsi](https://jitsi.org/projects/) -RTC开源项目的集合，重点是会议软件.

### STUN/TURN

- [coturn](https://github.com/coturn/coturn) -功能齐全的TURN / STUN服务器，支持多个平台.
- [STUNTMAN](https://github.com/jselbie/stunserver) -符合RFC的开源STUN实现.


## Operations

### Monitoring

- [sngrep](https://github.com/irontec/sngrep) -基于终端的SIP流查看器.
- [sipgrep](https://github.com/sipcapture/sipgrep) -用于嗅探，捕获和浏览SIP流量的控制台工具.
- [rtpbreak](https://github.com/Naishy/rtpsplit) -检测，重建和分析RTP会话.
- [HOMER](https://github.com/sipcapture/homer) -RTC的多协议捕获和监视框架.
- [WebRTC Troubleshooter](https://test.webrtc.org) -一站式客户端WebRTC疑难解答.
- [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice) -公开客户端NAT遍历调试数据.
- [SIP3](https://sip3.io) -VoIP和RTC流量监控和分析平台.

### Testing

- [SIPp](http://sipp.sourceforge.net) -用于SIP协议的流量生成器.
- [SIPVicious](https://github.com/EnableSecurity/sipvicious) -一套安全工具，可用于审核基于SIP的VoIP系统.
- [sipsak](https://github.com/nils-ohlmeier/sipsak) -SIP压力和诊断实用程序.

### Web/API Interfaces

- [Kazoo](https://www.2600hz.org) -使用FreeSWITCH和Kamailio的电信级VoIP API平台.
- [FusionPBX](https://www.fusionpbx.com) -建立在FreeSWITCH之上的多租户系统.
- [FreePBX](https://www.freepbx.org) -星号Web管理器.

### Billing

- [CGRateS](http://cgrates.org) -电信级开源账单/费率服务器.
- [A2Billing](http://www.asterisk2billing.org) -用于多种应用的Asterisk计费系统.
- [PyFreeBilling](https://github.com/mwolff44/pyfreebilling) -Kamailio和FreeSWITCH的批发计费平台.


## Developer Resources

### Tutorials

- [Official Website](https://webrtc.org) -入门级WebRTC资源.
- [Getting Started With WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/basics) -HTML5 Rocks的WebRTC教程.
- [WebRTC Samples](https://webrtc.github.io/samples) -收集样本说明WebRTC API的各个部分.
- [WebRTC Experiments](https://www.webrtc-experiment.com) -Muaz Khan的样品清单.
- [Interactive Codelab](https://codelabs.developers.google.com/codelabs/webrtc-web) -由Google提供的30分钟分步实时教程.

### JavaScript Libraries

- [drachtio](https://drachtio.org) -Node.js SIP服务器框架.
- [adapter.js](https://github.com/webrtcHacks/adapter) -用于填充WebRTC规范更改和不一致的JavaScript填充程序.
- [JsSIP](http://jssip.net) -轻量级开源JavaScript SIP库.
- [sipML5](https://www.doubango.org/sipml5) -具有WebRTC媒体堆栈的开源JavaScript SIP客户端.
- [simple-peer](https://github.com/feross/simple-peer) -用于Node.js和浏览器的WebRTC视频，语音和数据通道抽象.
- [Netflux](https://github.com/coast-team/netflux) -用于客户端和服务器的同构JavaScript对等传输API.
- [PeerJS](https://peerjs.com) -通过WebRTC实现的数据和媒体对等连接API.

### C/C++ Libraries

- [libre](https://github.com/creytiv/re) -便携式SIP堆栈以及用于媒体处理，STUN / TURN和模块化用户代理的配套库.
- [PJSIP](https://www.pjsip.org) -用C编写的多协议RTC库.
- [eXosip](http://savannah.nongnu.org/projects/exosip) -扩展的osip是成熟的C库，用于抽象SIP协议.
- [libdatachannel](https://github.com/paullouisageneau/libdatachannel) -独立的WebRTC DataChannels C ++实现.
- [libSRTP](https://github.com/cisco/libsrtp) -C的安全实时传输协议（SRTP）库.
- [usrsctp](https://github.com/sctplab/usrsctp) -便携式流控制传输协议（SCTP）用户区域堆栈.
- [rawrtc](https://github.com/rawrtc/rawrtc) -占地面积小的WebRTC和ORTC库.
- [OSS Core](https://github.com/joegen/oss_core) -用于实时通信的通用C ++库.
- [Open WebRTC Toolkit](https://01.org/open-webrtc-toolkit) -具有针对多个平台的绑定的WebRTC开发工具包.

### Go Libraries

- [Pion](https://pion.ly) -用Go编写的WebRTC广泛的软件堆栈.
- [gossip](https://github.com/StefanKopieczek/gossip) -使用Go编写的有状态用户代理的SIP堆栈.
- [siprocket](https://github.com/marv2097/siprocket) -快速SIP和SDP数据包解析器.
- [go-diameter](https://github.com/fiorix/go-diameter) -符合RFC的Diameter协议库.

### PHP Libraries

- [RTCKit/SIP](https://github.com/rtckit/php-sip) -符合RFC 3261的SIP解析和渲染库，用于PHP 7.4+.

### Python Libraries

- [aiortc](https://github.com/aiortc/aiortc) -使用asyncio的Python的WebRTC和ORTC实现.
- [Katari](https://github.com/hyperioxx/Katari) -SIP堆栈应用程序框架.
- [peerjs-python](https://github.com/ambianic/peerjs-python) -PeerJS对等连接库的Python端口.

### Erlang Libraries

- [NkSIP](https://github.com/NetComposer/nksip) -可扩展的SIP服务器框架.
- [ersip](https://github.com/poroh/ersip) -包含SIP应用程序构建块的库.

### Rust Libraries

- [libsip](https://docs.rs/libsip/0.2.4/libsip) -SIP实施，主要针对软件电话客户端.
- [sipcore](https://github.com/armatusmiles/sipcore) -用于创建SIP应用程序的Rust框架.
- [rtcrs/webrtc](https://github.com/rtcrs/webrtc) -WebRTC堆栈，支持SDP，RTP，RTCP和SRTP.

### Dart Libraries

- [dart-sip-ua](https://github.com/cloudwebrtc/dart-sip-ua) -JsSIP的Dart-lang端口，能够通过WebSocket进行SIP.


## Blogs

- [BlogGeekMe](https://bloggeek.me/blog) -Tsahi Levent-Levi撰写的博客，重点关注WebRTC.
- [SIP Adventures](https://andrewjprokop.wordpress.com) - Unified communications blog by Andrew Prokop.
- [WebRTCHacks](https://webrtchacks.com) -独立技术人员撰写的WebRTC博客.


## Discussion

- [FreeSWITCH Slack](https://signalwire.community) - Join #freeswitch and #freeswitch-dev for user and developer support.
- [discuss-webrtc](https://groups.google.com/forum/?fromgroups#!forum/discuss-webrtc) -面向开发人员的Google小组进行WebRTC讨论.


## Events

- [ClueCon](http://cluecon.com)  -在芝加哥举行的电信开发商年度会议.  FreeSWITCH的出生地.
- [Kamailio World](https://www.kamailioworld.com) -柏林举办了年度活动，重点是Kamailio以及VoIP，WebRTC，IMS，VoLTE等.
- [AstriCon](https://www.asterisk.org/community/astricon-user-conference) -每年在美国各地举行的星号焦点活动.
- [CommCon](https://2019.commcon.xyz) -在英国举行的年度会议主要讨论一般的电信，尤其是WebRTC.
- [OpenSIPS Summit](https://www.opensips.org/events) -OpenSIPS社区的聚会场所.
- [Kranky Geek](https://krankygeek.com) -旧金山的AI和RTC活动.
- [FOSDEM](https://fosdem.org/2020) -每年在欧洲为软件开发人员提供带有RTC组件的免费活动.


## Related Lists

- [Awesome RIPT](https://github.com/rtckit/awesome-ript) -电话的实时Internet对等.
- [Awesome RTC Hacking](https://github.com/EnableSecurity/awesome-rtc-hacking) -实时通信黑客和渗透测试资源.
- [Awesome 5G](https://github.com/calee0219/awesome-5g) -5G框架，库，软件和资源.
- [Awesome Cellular Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking) -3G / 4G / 5G蜂窝安全领域的研究资源.
- [Awesome Telco](https://github.com/ravens/awesome-telco) -电信资源和项目.


## Contribute

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/rtckit/awesome-rtc/blob/master/CONTRIBUTING.md) 第一.
