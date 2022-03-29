<div class="github-widget" data-repo="rtckit/awesome-rtc"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Real Time Communications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 几乎同时交换媒体和数据的协议和方法.





## Server Software

### General Purpose

- [FreeSWITCH](http://freeswitch.org) - 开源多协议、跨平台和软件切换.
- [Asterisk](http://asterisk.org) - 支持多种协议和平台的 PBX 框架.

### SIP Servers

- [Kamailio](http://www.kamailio.org)  - 运营商和提供商广泛部署的开源 SIP 服务器. 以前称为 OpenSER.
- [OpenSIPS](http://www.opensips.org) - 开源 SIP 服务器，追溯其根源于 OpenSER（现为 Kamailio）.
- [Routr](https://routr.io) - 用 Node.js 编写的轻量级 SIP 代理、位置服务器和注册器.
- [Sippy B2BUA](https://github.com/sippy/b2bua) - 用 Python 编写的背靠背用户代理服务器.
- [Flexisip](https://github.com/BelledonneCommunications/flexisip) - SIP 服务器套件，包括代理、在线状态和群聊功能.

### Media Servers

- [Janus](https://janus.conf.meetecho.com) - 轻量级开源、通用、WebRTC 网关.
- [RTPProxy](https://www.rtpproxy.org) - 通用高性能 RTP 代理.
- [RTP:Engine](https://github.com/sipwise/rtpengine) - 基于 RTP 和 UDP 的媒体流量代理，可用作内核模块.
- [mediasoup](https://mediasoup.org) - 专门的 WebRTC 会议系统.
- [SEMS](https://github.com/sems-server/sems) - 用于基于 SIP 的 VoIP 服务的开源媒体和应用服务器.
- [Jitsi](https://jitsi.org/projects) - RTC 开源项目的集合，专注于会议软件.

### STUN/TURN

- [coturn](https://github.com/coturn/coturn) - 支持多种平台的全功能 TURN/STUN 服务器.
- [STUNTMAN](https://github.com/jselbie/stunserver) - 符合 RFC 的开源 STUN 实现.


## Operations

### Monitoring

- [sngrep](https://github.com/irontec/sngrep) - 基于终端的 SIP 流查看器.
- [sipgrep](https://github.com/sipcapture/sipgrep) - 用于嗅探、捕获和探索 SIP 流量的控制台工具.
- [rtpbreak](https://github.com/Naishy/rtpsplit) - 检测、重建和分析 RTP 会话.
- [HOMER](https://github.com/sipcapture/homer) - RTC 的多协议捕获和监控框架.
- [WebRTC Troubleshooter](https://github.com/webrtc/testrtc) - 自托管的一站式客户端 WebRTC 疑难解答.
- [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice) - 公开客户端 NAT 遍历调试数据.
- [SIP3](https://sip3.io) - VoIP &amp; RTC 流量监控和分析平台.

### Testing

- [SIPp](http://sipp.sourceforge.net) - SIP 协议的流量生成器.
- [SIPVicious](https://github.com/EnableSecurity/sipvicious) - 可用于审计基于 SIP 的 VoIP 系统的安全工具套件.
- [sipsak](https://github.com/nils-ohlmeier/sipsak) - SIP 压力和诊断实用程序.
- [sipexer](https://github.com/miconda/sipexer) - 现代灵活的 SIP 命令行工具.

### Deployment

- [slimswitch](https://github.com/rtckit/slimswitch) - 用于创建精益安全的 FreeSWITCH Docker 映像的工具.

### Web/API Interfaces

- [Eqivo](https://eqivo.org) - 开源可编程语音/电话 API 平台.
- [Kazoo](https://www.2600hz.org) - 使用 FreeSWITCH 和 Kamailio 的运营商级 VoIP API 平台.
- [FusionPBX](https://www.fusionpbx.com) - 建立在 FreeSWITCH 之上的多租户系统.
- [FreePBX](https://www.freepbx.org) - Asterisk 的网络管理器.
- [Fonoster](https://github.com/fonoster/fonoster) - 使用 Node.js 构建的电信堆栈.
- [Wazo](https://wazo-platform.org) - VoIP API 平台建立在 Asterisk、Kamailio 和 RTPEngine 之上.
- [jambonz](https://www.jambonz.org) - 为通信服务提供商构建的开源 CPaaS.
- [IVOZ Provider](https://github.com/irontec/ivozprovider) - VoIP 电话提供商的多租户解决方案.

### Billing

- [CGRateS](http://cgrates.org) - 运营商级开源计费/评级服务器.
- [A2Billing](http://www.asterisk2billing.org) - 用于多个应用程序的 Asterisk 计费系统.
- [PyFreeBilling](https://github.com/mwolff44/pyfreebilling) - Kamailio 和 FreeSWITCH 的批发计费平台.


## Developer Resources

### Tutorials

- [Official Website](https://webrtc.org) - 入门级 WebRTC 资源.
- [Getting Started With WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/basics) - HTML5 Rocks 的 WebRTC 教程.
- [WebRTC Samples](https://webrtc.github.io/samples) - 展示 WebRTC API 各个部分的示例集合.
- [WebRTC Experiments](https://www.webrtc-experiment.com) - Muaz Khan 提供的完整样本清单.
- [Interactive Codelab](https://codelabs.developers.google.com/codelabs/webrtc-web) - Google 提供的 30 分钟分步实时教程.

### JavaScript Libraries

- [drachtio](https://drachtio.org) - Node.js SIP 服务器框架.
- [adapter.js](https://github.com/webrtcHacks/adapter) - 用于抽象 WebRTC 规范更改和不一致的 JavaScript 垫片.
- [JsSIP](http://jssip.net) - 轻量级开源 JavaScript SIP 库.
- [sipML5](https://www.doubango.org/sipml5) - 带有 WebRTC 媒体堆栈的开源 JavaScript SIP 客户端.
- [simple-peer](https://github.com/feross/simple-peer) - Node.js 和浏览器的 WebRTC 视频、语音和数据通道抽象.
- [Netflux](https://github.com/coast-team/netflux) - 用于客户端和服务器的同构 JavaScript 点对点传输 API.
- [PeerJS](https://peerjs.com) - 通过 WebRTC 实现的数据和媒体对等连接 API.

### C/C++ Libraries

- [libre](https://github.com/creytiv/re) - 便携式 SIP 堆栈以及用于媒体处理、STUN/TURN 和模块化用户代理的配套库.
- [PJSIP](https://www.pjsip.org) - 用 C 编写的多协议 RTC 库.
- [eXosip](http://savannah.nongnu.org/projects/exosip) - eXtended osip 是一个成熟的 C 库，用于抽象 SIP 协议.
- [libdatachannel](https://github.com/paullouisageneau/libdatachannel) - 独立的 WebRTC DataChannels C++ 实现.
- [libSRTP](https://github.com/cisco/libsrtp) - C 的安全实时传输协议 (SRTP) 库.
- [usrsctp](https://github.com/sctplab/usrsctp) - 便携式流控制传输协议 (SCTP) 用户级堆栈.
- [rawrtc](https://github.com/rawrtc/rawrtc) - WebRTC 和 ORTC 库，占用空间小.
- [OSS Core](https://github.com/joegen/oss_core) - 用于实时通信的通用 C++ 库.
- [Open WebRTC Toolkit](https://01.org/open-webrtc-toolkit) - 具有多个平台绑定的 WebRTC 开发工具包.
- [Sofia-SIP](https://github.com/freeswitch/sofia-sip) - FreeSWITCH 使用的开源 SIP 库.

### Go Libraries

- [Pion](https://pion.ly) - 用 Go 编写的用于 WebRTC 的广泛软件堆栈.
- [gossip](https://github.com/StefanKopieczek/gossip) - 用 Go 编写的有状态用户代理的 SIP 堆栈.
- [siprocket](https://github.com/marv2097/siprocket) - 快速 SIP 和 SDP 数据包解析器.
- [go-diameter](https://github.com/fiorix/go-diameter) - 符合 RFC 的 Diameter 协议库.

### PHP Libraries

- [RTCKit/SIP](https://github.com/rtckit/php-sip) - 适用于 PHP 7.4+ 的符合 RFC 3261 的 SIP 解析和呈现库.

### Python Libraries

- [aiortc](https://github.com/aiortc/aiortc) - 使用 asyncio 的 Python 的 WebRTC 和 ORTC 实现.
- [Katari](https://github.com/hyperioxx/Katari) - SIP 堆栈应用程序框架.
- [peerjs-python](https://github.com/ambianic/peerjs-python) - PeerJS 点对点连接库的 Python 端口.

### Erlang Libraries

- [NkSIP](https://github.com/NetComposer/nksip) - 可扩展的 SIP 服务器框架.
- [ersip](https://github.com/poroh/ersip) - 包含 SIP 应用程序构建块的库.

### Rust Libraries

- [libsip](https://docs.rs/libsip/0.2.4/libsip) - SIP 实施，侧重于软电话客户端.
- [sipcore](https://github.com/armatusmiles/sipcore) - 用于创建 SIP 应用程序的 Rust 框架.
- [rtcrs/webrtc](https://github.com/rtcrs/webrtc) - WebRTC 堆栈，支持 SDP、RTP、RTCP 和 SRTP.

### Dart Libraries

- [dart-sip-ua](https://github.com/cloudwebrtc/dart-sip-ua) - JsSIP 的 Dart-lang 端口，能够通过 WebSocket 进行 SIP.


## Blogs

- [BlogGeekMe](https://bloggeek.me/blog) - Tsahi Levent-Levi 的博客，重点关注 WebRTC.
- [SIP Adventures](https://andrewjprokop.wordpress.com) - Andrew Prokop 的统一通信博客.
- [WebRTCHacks](https://webrtchacks.com) - 独立技术人员的 WebRTC 博客.


## Discussion

- [FreeSWITCH Slack](https://signalwire.community) - Join #freeswitch and #freeswitch-dev for user and developer support.
- [discuss-webrtc](https://groups.google.com/forum/?fromgroups#!forum/discuss-webrtc) - 面向开发人员的 Google Group 用于 WebRTC 讨论.


## Events

- [ClueCon](http://cluecon.com)  - 在芝加哥举行的电信开发商年度会议.  FreeSWITCH 的诞生地.
- [Kamailio World](https://www.kamailioworld.com) - 柏林举办了专注于 Kamailio 以及 VoIP、WebRTC、IMS、VoLTE 等的年度活动.
- [AstriCon](https://www.asterisk.org/community/astricon-user-conference) - 每年在美国举行的星号焦点活动.
- [CommCon](https://commcon.xyz) - 在英国举行的年度会议主要关注电信，特别是 WebRTC.
- [OpenSIPS Summit](https://www.opensips.org/events) - Meeting place for the OpenSIPS community.
- [Kranky Geek](https://krankygeek.com) - 旧金山的 AI 和 RTC 活动.
- [FOSDEM](https://fosdem.org) - 每年在欧洲举办的带有 RTC 组件的软件开发人员免费活动.
- [JanusCon](https://www.januscon.it) - JanusCon 是 Janus 和 RTC 实施者的现场活动.
- [TADHack](https://tadhack.com) - 专注于可编程通信的全球黑客马拉松.


## Related Lists

- [Awesome RIPT](https://github.com/rtckit/awesome-ript) - 实时互联网对等电话.
- [Awesome RTC Hacking](https://github.com/EnableSecurity/awesome-rtc-hacking) - 实时通信黑客和渗透测试资源.
- [Awesome 5G](https://github.com/calee0219/awesome-5g) - 5G 框架、库、软件和资源.
- [Awesome Cellular Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking) - 3G/4G/5G 蜂窝安全领域的研究资源.
- [Awesome Telco](https://github.com/ravens/awesome-telco) - 电信资源和项目.
- [SIP Resources](https://github.com/miconda/sip-resources) - 由 Kamailio 的首席开发人员策划的有用 SIP 资源.


## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/rtckit/awesome-rtc/blob/master/CONTRIBUTING.md) 第一的.
