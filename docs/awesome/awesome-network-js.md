<div class="github-widget" data-repo="Kikobeats/awesome-network-js"></div>
## Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

&gt; 纯JS编写的网络层资源列表.

## High level

&gt; 至少基于 CLI 界面.

* [airpaste](https://github.com/mafintosh/airpaste) – 使用 mdns 自动发现其他对等点的 1-1 网络管道.
* [blecat](https://github.com/mafintosh/blecat) – 1-1 pipe over bluetooth low energy.
* [deejay](https://github.com/mafintosh/deejay) - 向同一网络上的所有人广播的音乐播放器.
* [dhtkv](https://github.com/maxogden/dhtkv) – 用于在 bittorrent 主线 DHT 中存储任意键/值数据的 CLI.
* [gun](https://github.com/amark/gun) – 一个实时的、去中心化的、离线优先的图形数据库引擎.
* [hyperpipe](https://github.com/mafintosh/hyperpipe) – 分布式输入/输出管道.
* [hypervision](https://github.com/mafintosh/hypervision) – P2P 电视.
* [instant.io](https://github.com/webtorrent/instant.io) – 通过 WebTorrent 流式传输文件.
* [ipp-printer](https://github.com/watson/ipp-printer) – 在您的网络上创建打印机.
* [peercast](https://github.com/mafintosh/peercast) – 类似于 peerflix，但适用于 Chromecast.
* [peerflix](https://github.com/mafintosh/peerflix) - 流媒体客户端.
* [peerwiki](https://github.com/mafintosh/peerwiki) – 使用 bittorrent 浏览所有维基百科.
* [screencat](https://github.com/maxogden/screencat) – WebRTC 屏幕共享应用程序.
* [signalhub](https://github.com/mafintosh/signalhub) – 简单的信令服务器，可用于协调与 webrtc 或其他有趣内容的握手.
* [torrent-mount](https://github.com/mafintosh/torrent-mount) – 使用 torrent-stream 和 fuse 实时将 torrent（或磁力链接）挂载为文件系统.
* [webcat](https://github.com/mafintosh/webcat) – 使用 WebRTC 通过网络进行管道传输.
* [websocketd](https://github.com/joewalnes/websocketd) – 将任何使用 stdin/stdout 的程序变成 WebSocket 服务器.
* [webtorrent](https://github.com/webtorrent/webtorrent) – 基于 WebRTC 的 BitTorrent.
* [wifi-triangulate](https://github.com/watson/wifi-triangulate) – 使用 wifi 接入点查找您在地球上的当前位置.

## Modules

&gt; 做好一件事.

* [airplay-server](https://github.com/watson/airplay-server) – 一个低级别的 AirPlay 服务器.
* [castnow](https://github.com/xat/chromecast-player) – 简单的 chromecast 播放器.
* [discovery-swarm](https://github.com/mafintosh/discovery-swarm) – 使用的网络群 [discovery-channel](https://github.com/maxogden/discovery-channel) 寻找同行. 还要检查 [webrtc-swarm](https://github.com/mafintosh/webrtc-swarm).
* [dns-packet](https://github.com/mafintosh/dns-packet)  – 用于编码/解码 DNS 数据包的抽象编码兼容模块. 另见 [dns-socket](https://github.com/mafintosh/dns-socket).
* [etcdjs](https://github.com/mafintosh/etcdjs) – 用 Ja​​vascript 编写的低级 etcd v2 客户端，支持故障转移.
* [geocode-wifi](https://github.com/watson/geocode-wifi) – 根据您的 wifi 接入点获取您的纬度/经度.
* [hash-to-port](https://github.com/mafintosh/hash-to-port) – 将值散列到有效端口.
* [hyperdb](https://github.com/mafintosh/hyperdb) – 分布式可扩展数据库.
* [ip-packet](https://github.com/mafintosh/ip-packet) – 编码/解码原始 ip 数据包.
* [magnet-uri](https://github.com/webtorrent/magnet-uri) – 解析一个磁铁 URI 并返回一个键/值对象.
* [mutex-server](https://github.com/samchon/mutex-server) - 关键部分控制器，如网络级别的互斥量和信号量.
* [network-address](https://github.com/mafintosh/network-address) – 获取您机器的本地网络地址.
* [network-simulator](https://github.com/substack/network-simulator) – 模拟低级计算机网络.
* [rtsp-stream](https://github.com/watson/rtsp-stream) - 用于 Node.js 的传输不可知 RTSP 串行多路复用器模块.
* [simple-peer](https://github.com/feross/simple-peer) – 简单的 WebRTC 视频/语音和数据通道.
* [simple-websocket](https://github.com/feross/simple-websocket) – 用于 WebSocket 的简单 EventEmitter API.
* [torrent-discovery](https://github.com/webtorrent/torrent-discovery) – 发现 BitTorrent 和 WebTorrent 同行.
* [torrent-stream](https://github.com/mafintosh/torrent-stream) – peerflix 使用的低级流媒体 torrent 引擎.
* [udp-packet](https://github.com/substack/udp-packet) – 编码/解码原始 udp 数据包.
* [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 通过 Node.js 和 JavaScript 的 WebSockets 实现 JSON-RPC 2.0.

## Protocols

&gt; 在纯 javascript 中实现协议规范.

* [airswarm](https://github.com/mafintosh/airswarm) – 使用多播 dns 自动发现网络上其他对等点的网络群.
* [bittorrent-dht](https://github.com/webtorrent/bittorrent-dht) – BitTorrent DHT 协议实现.
* [bittorrent-protocol](https://github.com/webtorrent/bittorrent-protocol) – BitTorrent 对等线协议实现.
* [bittorrent-tracker](https://github.com/webtorrent/bittorrent-tracker) – BitTorrent 跟踪器（客户端和服务器）实施
* [bonjour](https://github.com/watson/bonjour) – Bonjour/Zeroconf 协议实现.
* [castv2](https://github.com/thibauts/node-castv2) – Chromecast CASTV2 协议的实现.
* [dht-rpc](https://github.com/mafintosh/dht-rpc) – 进行 RPC 调用 [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) 基于 DHT.
* [dns-discovery](https://github.com/mafintosh/dns-discovery) – 使用常规 dns 和多播 dns 在分布式系统中发现对等体.
* [hypercore](https://github.com/mafintosh/hypercore) – 用于分发和复制二进制数据静态提要的 p2p 网络.
* [ipfs](https://github.com/ipfs/js-ipfs-api) – 星际文件系统，一种新的点对点超媒体协议.
* [k-bucket](https://github.com/tristanls/k-bucket) – Kademlia DHT K-bucket 实现为二叉树.
* [k-rpc](https://github.com/mafintosh/k-rpc)  – k-rpc 协议的实现使用了 BitTorrent DHT. 另见 [k-rpc-socket](https://github.com/mafintosh/k-rpc-socket).
* [mdns](https://github.com/agnat/node_mdns) – mdns/zeroconf/bonjour 服务发现.
* [multicast-dns](https://github.com/mafintosh/multicast-dns) – 低级多播-DNS 实现.
* [peervision](https://github.com/mafintosh/peervision) – 直播 p2p 流媒体协议.
* [polo](https://github.com/mafintosh/polo) – 零配置服务发现模块.
* [rtsp-server](https://github.com/watson/rtsp-server) – 用于创建 RTSP 服务器的低级模块.
* [utp-native](https://github.com/mafintosh/utp-native) – 微传输协议，一种类似于 tcp 的网络协议，运行在 udp 之上.
