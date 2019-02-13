## Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

&gt;纯JS编写的网络层资源列表.

## High level

&gt;至少基于CLI界面.

* [airpaste](https://github.com/mafintosh/airpaste) -  1-1使用mdns自动发现其他对等体的网络管道.
* [blecat](https://github.com/mafintosh/blecat) -  1-1蓝牙低能耗管道.
* [deejay](https://github.com/mafintosh/deejay) - 向同一网络上的每个人广播的音乐播放器.
* [dhtkv](https://github.com/maxogden/dhtkv) - 用于在bittorrent主线DHT中存储任意键/值数据的CLI.
* [gun](https://github.com/amark/gun) - 实时，分散，离线优先的图形数据库引擎.
* [hyperpipe](https://github.com/mafintosh/hyperpipe) - 分布式输入/输出管道.
* [hypervision](https://github.com/mafintosh/hypervision) -  P2P电视.
* [instant.io](https://github.com/webtorrent/instant.io) - 通过WebTorrent进行流式文件传输.
* [ipp-printer](https://github.com/watson/ipp-printer) - 在网络上创建打印机.
* [peercast](https://github.com/mafintosh/peercast) - 像peerflix一样，但对于Chromecast.
* [peerflix](https://github.com/mafintosh/peerflix) - 流媒体客户端.
* [peervisionary](https://github.com/mafintosh/peervisionary) - 通过本地网络传输p2p内容.
* [peerwiki](https://github.com/mafintosh/peerwiki) - 使用bittorrent浏览所有维基百科.
* [screencat](https://github.com/maxogden/screencat) -  WebRTC屏幕共享应用程序.
* [signalhub](https://github.com/mafintosh/signalhub) - 简单的信令服务器，可用于协调与webrtc或其他有趣的东西握手.
* [torrent-mount](https://github.com/mafintosh/torrent-mount) - 使用torrent-stream和fuse实时安装torrent（或磁力链接）作为文件系统.
* [webcat](https://github.com/mafintosh/webcat) - 使用WebRTC跨网络管道.
* [websocketd](https://github.com/joewalnes/websocketd) - 将使用stdin / stdout的任何程序转换为WebSocket服务器.
* [webtorrent](https://github.com/webtorrent/webtorrent) -  WebRTC上的BitTorrent.
* [wifi-triangulate](https://github.com/watson/wifi-triangulate) - 使用wifi接入点查找您在地球上的当前位置.

## Modules

&gt;做好一件事.

* [airplay-server](https://github.com/watson/airplay-server) - 低级AirPlay服务器.
* [castnow](https://github.com/xat/chromecast-player) - 简单的chromecast播放器.
* [discovery-swarm](https://github.com/mafintosh/discovery-swarm) - 使用的网络群 [discovery-channel](https://github.com/maxogden/discovery-channel)  找同行.  还检查一下 [webrtc-swarm](https://github.com/mafintosh/webrtc-swarm).
* [dns-packet](https://github.com/mafintosh/dns-packet)   - 用于编码/解码DNS数据包的符合抽象编码的模块.  另见 [dns-socket](https://github.com/mafintosh/dns-socket).
* [etcdjs](https://github.com/mafintosh/etcdjs) - 使用Javascript编写的低级别etcd v2客户端，具有故障转移支持.
* [geocode-wifi](https://github.com/watson/geocode-wifi) - 根据您的WiFi接入点获取您的纬度/经度.
* [hash-to-port](https://github.com/mafintosh/hash-to-port) - 将值散列到有效端口.
* [hyperdb](https://github.com/mafintosh/hyperdb) - 分布式可扩展数据库
* [ip-packet](https://github.com/mafintosh/ip-packet) - 编码/解码原始IP数据包.
* [magnet-uri](https://github.com/webtorrent/magnet-uri) - 解析磁体URI并返回键/值对象.
* [network-address](https://github.com/mafintosh/network-address) - 获取您机器的本地网络地址.
* [network-simulator](https://github.com/substack/network-simulator) - 模拟低级计算机网络.
* [rtsp-stream](https://github.com/watson/rtsp-stream) - 用于Node的与传输无关的RTSP串行多路复用器模块.
* [simple-peer](https://github.com/feross/simple-peer) - 简单的WebRTC视频/语音和数据通道.
* [simple-websocket](https://github.com/feross/simple-websocket) - 用于WebSockets的简单EventEmitter API.
* [torrent-discovery](https://github.com/webtorrent/torrent-discovery) - 发现BitTorrent和WebTorrent同行.
* [torrent-stream](https://github.com/mafintosh/torrent-stream) -  peerflix使用的低级流媒体引擎.
* [udp-packet](https://github.com/substack/udp-packet) - 编码/解码原始udp数据包.

## Protocols

&gt;在纯JavaScript中实现协议规范.

* [airswarm](https://github.com/mafintosh/airswarm) - 网络群，使用多播dns自动发现网络上的其他对等方.
* [bittorrent-dht](https://github.com/webtorrent/bittorrent-dht) -  BitTorrent DHT协议实现.
* [bittorrent-protocol](https://github.com/webtorrent/bittorrent-protocol) -  BitTorrent对等线协议实现.
* [bittorrent-tracker](https://github.com/webtorrent/bittorrent-tracker) -  BitTorrent跟踪器（客户端和服务器）实现
* [bonjour](https://github.com/watson/bonjour) -  Bonjour / Zeroconf协议实现.
* [castv2](https://github.com/thibauts/node-castv2) -  Chromecast CASTV2协议的实现.
* [dht-rpc](https://github.com/mafintosh/dht-rpc) - 通过a进行RPC调用 [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) 基于DHT.
* [dns-discovery](https://github.com/mafintosh/dns-discovery) - 使用常规dns和多播dns在分布式系统中发现对等体.
* [hypercore](https://github.com/mafintosh/hypercore) - 用于分发和复制二进制数据的静态馈送的p2p网络.
* [ipfs](https://github.com/ipfs/js-ipfs-api) -  InterPlanetary文件系统，一种新的点对点超媒体协议.
* [k-bucket](https://github.com/tristanls/k-bucket) -  Kademlia DHT K-bucket实现为二叉树.
* [k-rpc](https://github.com/mafintosh/k-rpc)   - 使用BitTorrent DHT的k-rpc协议的实现.  另见 [k-rpc-socket](https://github.com/mafintosh/k-rpc-socket).
* [mdns](https://github.com/agnat/node_mdns) -  mdns / zeroconf / bonjour服务发现.
* [multicast-dns](https://github.com/mafintosh/multicast-dns) - 低级多播-dns实现.
* [peervision](https://github.com/mafintosh/peervision) - 实时p2p流媒体协议.
* [polo](https://github.com/mafintosh/polo) - 零配置服务发现模块.
* [rtsp-server](https://github.com/watson/rtsp-server) - 用于创建RTSP服务器的低级模块.
* [utp-native](https://github.com/mafintosh/utp-native) - 微传输协议，类似于在udp之上运行的tcp的网络协议.
