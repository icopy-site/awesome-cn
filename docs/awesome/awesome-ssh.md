<div class="github-widget" data-repo="moul/awesome-ssh"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome SSH [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; * SSH *的精选列表 [apps](#apps), [libraries](#libraries) 和 [resources](#resources).

<h2 align="center"><img src="https://raw.githubusercontent.com/moul/awesome-ssh/master/logo.jpg" width="400" /></h2>

受启发 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

请阅读 [contribution guidelines](https://github.com/moul/awesome-ssh/blob/master/CONTRIBUTING.md) 如果你想贡献.

**检查我 [blog](https://manfred.life/)  或者说“嗨” [Twitter](https://twitter.com/moul).**



## Apps

### `.ssh/config`

* [`assh`](https://github.com/moul/assh) [![stars](https://img.shields.io/github/stars/moul/advanced-ssh-config.svg?style=social&label=stars) ]（https://github.com/moul/advanced-ssh-config）-透明包装器（ProxyCommand），它将正则表达式，别名，网关，包括，动态主机名添加到* SSH *和`ssh-config`.  _以前：`advanced-ssh-config`_
* [storm](https://github.com/emre/storm) [![stars](https://img.shields.io/github/stars/emre/storm.svg?style=social&label=stars)]（https://github.com/emre/storm）-像老板一样管理您的* SSH *.
* [ansible-ssh-config](https://github.com/gaqzi/ansible-ssh-config) [![stars](https://img.shields.io/github/stars/gaqzi/ansible-ssh-config.svg?style=social&label=stars)]（https://github.com/gaqzi/ansible-ssh-config）-让* Ansible *管理`ssh_config`.
* [ec2ssh](https://github.com/mirakui/ec2ssh) [![stars](https://img.shields.io/github/stars/mirakui/ec2ssh.svg?style=social&label=stars)]（https://github.com/mirakui/ec2ssh）-用于* AWS EC2 *的`ssh_config`管理器.
* [ssh-config](https://github.com/dbrady/ssh-config) [![stars](https://img.shields.io/github/stars/dbrady/ssh-config.svg?style=social&label=stars)]（https://github.com/dbrady/ssh-config）-帮助管理您的`.ssh / config`文件的工具.

### Tools using the *SSH* protocol

* [scp](http://linux.die.net/man/1/scp) -通过* SSH *的安全远程文件复制实用程序.
* [rsync](https://rsync.samba.org) -支持* SSH *的快速增量传输实用程序.
* [sftp](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) -通过* SSH *的文件传输协议.
* [curl](http://curl.haxx.se) -用于传输数据的命令行工具和库（支持sftp`）.

### Servers

* [sshportal](https://github.com/moul/sshportal) [![stars](https://img.shields.io/github/stars/moul/sshportal.svg?style=social&label=stars)]（https://github.com/moul/sshportal）-简单，有趣和透明的SSH（＆Telnet）堡垒服务器
* [ssh2docker](https://github.com/moul/ssh2docker) [![stars](https://img.shields.io/github/stars/moul/ssh2docker.svg?style=social&label=stars)]（https://github.com/moul/ssh2docker）-* SSH *服务器到Docker容器.
* [ssh-proxy](https://github.com/ml-tooling/ssh-proxy) [![stars](https://img.shields.io/github/stars/ml-tooling/ssh-proxy.svg?style=social&label=stars)]（https://github.com/ml-tooling/ssh-proxy）-Dockerized SSH堡垒，用于将SSH连接代理到任意容器.
* [whosthere](https://github.com/FiloSottile/whosthere) [![stars](https://img.shields.io/github/stars/FiloSottile/whosthere.svg?style=social&label=stars) ]（https://github.com/FiloSottile/whosthere）-一个* SSH *服务器，它知道您是谁.  $ ssh whoami.filippo.io.
* [sshfront](https://github.com/gliderlabs/sshfront) [![stars](https://img.shields.io/github/stars/gliderlabs/sshfront.svg?style=social&label=stars)]（https://github.com/gliderlabs/sshfront）-可编程* SSH *前端.
* [ssh-chat](https://github.com/shazow/ssh-chat) [![stars](https://img.shields.io/github/stars/shazow/ssh-chat.svg?style=social&label=stars)]（https://github.com/shazow/ssh-chat）-通过* SSH *聊天.
* [sshcommand](https://github.com/dokku/sshcommand) [![stars](https://img.shields.io/github/stars/dokku/sshcommand.svg?style=social&label=stars)]（https://github.com/dokku/sshcommand）-将* SSH *变成专门用于您的应用程序的瘦客户端.
* [sshmuxd](https://github.com/joushou/sshmuxd) [![stars](https://img.shields.io/github/stars/joushou/sshmuxd.svg?style=social&label=stars)]（https://github.com/joushou/sshmuxd）-`sshmux`前端.
* [x84](https://github.com/jquast/x84) [![stars](https://img.shields.io/github/stars/jquast/x84.svg?style=social&label=stars) ]（https://github.com/jquast/x84）-一个用于现代* UTF-8 *和经典* cp437 *网络虚拟终端的* python *`telnet` /`ssh`服务器. 本着经典软件的精神，例如* ami / x *，* teleguard *，* renegade *，* iniquity *.
* [teleport](https://github.com/gravitational/teleport) [![stars](https://img.shields.io/github/stars/gravitational/teleport.svg?style=social&label=stars)]（https://github.com/gravitational/teleport）-适用于集群和团队的现代* SSH *服务器.
* [ShellHub](https://github.com/shellhub-io/shellhub) [![stars](https://img.shields.io/github/stars/shellhub-io/shellhub.svg?style=social&label=stars)]（https://github.com/shellhub-io/shellhub）-一个* SSH *网关，用于远程访问防火墙和NAT之后的任何Linux设备.

### Network

* [Mosh](https://mosh.mit.edu) -移动外壳.
* [sshfs](https://github.com/libfuse/sshfs) [![stars](https://img.shields.io/github/stars/libfuse/sshfs.svg?style=social&label=stars)]（https://github.com/libfuse/sshfs）-基于* SSH *文件传输协议的文件系统客户端.
* [ngrok](https://github.com/inconshreveable/ngrok) [![stars](https://img.shields.io/github/stars/inconshreveable/ngrok.svg?style=social&label=stars)]（https://github.com/inconshreveable/ngrok）-对本地主机的自省隧道.
* [localtunnel](https://github.com/progrium/localtunnel) [![stars](https://img.shields.io/github/stars/progrium/localtunnel.svg?style=social&label=stars)]（https://github.com/progrium/localtunnel）-将localhost服务器公开到Internet.
* [sshuttle](https://github.com/sshuttle/sshuttle) [![stars](https://img.shields.io/github/stars/sshuttle/sshuttle.svg?style=social&label=stars) ]（https://github.com/sshuttle/sshuttle）-透明的代理服务器，充当穷人的* VPN *. 通过`ssh`转发. 不需要管理员. 适用于* Linux *和* MacOS *. 支持* DNS隧道*.
* [sshttp](https://github.com/stealth/sshttp) [![stars](https://img.shields.io/github/stars/stealth/sshttp.svg?style=social&label=stars) ]（https://github.com/stealth/sshttp）-* SSH * / * HTTP（S）*多路复用器. 在没有更改的相同端口上运行网络服务器和`sshd`.
* [switcher](https://github.com/jamescun/switcher) [![stars](https://img.shields.io/github/stars/jamescun/switcher.svg?style=social&label=stars)]（https://github.com/jamescun/switcher）-在同一端口上运行* SSH *和* HTTP（S）*.
* [sslh](https://github.com/yrutschle/sslh) [![stars](https://img.shields.io/github/stars/yrutschle/sslh.svg?style=social&label=stars)]（https://github.com/yrutschle/sslh）-应用协议多路复用器（即：* SSH * + * HTTPS *）.
* [tund](https://github.com/aphyr/tund) [![stars](https://img.shields.io/github/stars/aphyr/tund.svg?style=social&label=stars)]（https://github.com/aphyr/tund）-* SSH *反向隧道守护程序.
* [autossh](http://www.harding.motd.ca/autossh/) -网络中断后自动重新生成* SSH *会话.
* [wssh](https://github.com/aluzzardi/wssh) [![stars](https://img.shields.io/github/stars/aluzzardi/wssh.svg?style=social&label=stars)]（https://github.com/aluzzardi/wssh）-* SSH *到WebSockets Bridge.
* [docker-volume-sshfs](https://github.com/vieux/docker-volume-sshfs) [![stars](https://img.shields.io/github/stars/vieux/docker-volume-sshfs.svg?style=social&label=stars)]（https://github.com/vieux/docker-volume-sshfs）-`sshfs` docker volume插件
* [quicssh](https://github.com/moul/quicssh) [![stars](https://img.shields.io/github/stars/moul/quicssh.svg?style=social&label=stars)]（https://github.com/moul/quicssh）-SSH的QUIC代理
* [sshpiper](https://github.com/tg123/sshpiper) [![stars](https://img.shields.io/github/stars/tg123/sshpiper.svg?style=social&label=stars)]（https://github.com/tg123/sshpiper）-缺少ssh scp的反向代理.
* [sshhub](https://sshhub.de) -Web服务：访问位于防火墙后面的SSH服务器（ssh-teamviewer）.

### Multiplexers

* [tmux](https://tmux.github.io) -终端多路复用器.
* [clusterssh](https://github.com/duncs/clusterssh) [![stars](https://img.shields.io/github/stars/duncs/clusterssh.svg?style=social&label=stars)]（https://github.com/duncs/clusterssh）-通过* SSH *进行群集管理.
* [tmux-cssh](https://github.com/dennishafemann/tmux-cssh) [![stars](https://img.shields.io/github/stars/dennishafemann/tmux-cssh.svg?style=social&label=stars)]（https://github.com/dennishafemann/tmux-cssh）-具有类似* ClusterSSH *行为的`tmux`.
* [tm](https://github.com/Ganneff/tm) [![stars](https://img.shields.io/github/stars/Ganneff/tm.svg?style=social&label=stars)]（https://github.com/Ganneff/tm）-`tmux`经理/助手.
* [i2cssh](https://github.com/wouterdebie/i2cssh) [![stars](https://img.shields.io/github/stars/wouterdebie/i2cssh.svg?style=social&label=stars)]（https://github.com/wouterdebie/i2cssh）-`csshX`，例如* iTerm2 *的* SSH *工具.
* [ClusterSSH](http://sourceforge.net/projects/clusterssh/) -通过单个图形控制台控制多个“ xterm”窗口.

### *SSH* keys / Authentication

* [authy-ssh](https://github.com/authy/authy-ssh) [![stars](https://img.shields.io/github/stars/authy/authy-ssh.svg?style=social&label=stars)]（https://github.com/authy/authy-ssh）-用于* SSH *服务器的简单*双重身份验证.
* [github-auth](https://github.com/chrishunt/github-auth) [![stars](https://img.shields.io/github/stars/chrishunt/github-auth.svg?style=social&label=stars)]（https://github.com/chrishunt/github-auth）-GitHub用户的* SSH *密钥管理.
* [cipherhub](https://github.com/substack/cipherhub) [![stars](https://img.shields.io/github/stars/substack/cipherhub.svg?style=social&label=stars)]（https://github.com/substack/cipherhub）-基于* SSH *公钥的消息加密，可轻松从GitHub导入.
* [Slack notifications](http://www.ryanbrink.com/slack-ssh-session-notifications/) ([archived version](https://web.archive.org/web/20160505202303/http://www.ryanbrink.com/slack-ssh-session-notifications/)）-设置Slack通知的指南（可以针对其他服务进行修改）.
* [totp-ssh-fluxer](https://github.com/benjojo/totp-ssh-fluxer) [![stars](https://img.shields.io/github/stars/benjojo/totp-ssh-fluxer.svg?style=social&label=stars)]（https://github.com/benjojo/totp-ssh-fluxer）-一种确保`sshd`端口每30秒更改一次的方法.
* [github-keygen](https://github.com/dolmen/github-keygen) [![stars](https://img.shields.io/github/stars/dolmen/github-keygen.svg?style=social&label=stars)]（https://github.com/dolmen/github-keygen）-轻松为您的GitHub帐户创建安全的* SSH *配置.
* [kr](https://github.com/KryptCo/kr) [![stars](https://img.shields.io/github/stars/dolmen/github-keygen.svg?style=social&label=stars)]（https://github.com/KryptCo/kr）-将访问请求路由到安装了Kryptonite的配对手机的Kr代理.
* [ServerAuth](https://serverauth.com) -在服务器之间自动同步SSH访问

### *SSH* agent

* [ssh-ident](https://github.com/ccontavalli/ssh-ident) [![stars](https://img.shields.io/github/stars/ccontavalli/ssh-ident.svg?style=social&label=stars)]（https://github.com/ccontavalli/ssh-ident）-使用`ssh`，用于不同项目的不同代理和不同密钥.
* [oh-my-zsh/plugins/ssh-agent](https://github.com/robbyrussell/oh-my-zsh) [![stars](https://img.shields.io/github/stars/robbyrussell/oh-my-zsh.svg?style=social&label=stars)]（https://github.com/robbyrussell/oh-my-zsh）-`zsh`的`ssh-agent`插件.
* [sshecret](https://github.com/thcipriani/sshecret) -自动为多个密钥创建和管理多个代理.

### Tools

* [xxh](https://github.com/xxh/xxh) [![stars](https://img.shields.io/github/stars/xxh/xxh.svg?style=social&label=stars)]（https://github.com/xxh/xxh）-随身携带ssh都可以带上您喜欢的外壳.
* [sshrc](https://github.com/danrabinowitz/sshrc) [![stars](https://img.shields.io/github/stars/danrabinowitz/sshrc.svg?style=social&label=stars)]（https://github.com/danrabinowitz/sshrc）-当您使用ssh时，请带上您的.bashrc，.vimrc等.
* [kyrat](https://github.com/fsquillace/kyrat) [![stars](https://img.shields.io/github/stars/fsquillace/kyrat.svg?style=social&label=stars)]（https://github.com/fsquillace/kyrat）-SSH包装器脚本，可在Linux和OSX上始终带给您点文件.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) [![stars](https://img.shields.io/github/stars/ssh-vault/ssh-vault.svg?style=social&label=stars)]（https://github.com/ssh-vault/ssh-vault）-使用ssh密钥加密/解密文件
* [ssh-ping](https://github.com/vaporup/ssh-tools) [![stars](https://img.shields.io/github/stars/vaporup/ssh-tools.svg?style=social&label=stars)]（https://github.com/vaporup/ssh-tools）-使用ssh_config检查主机是否可访问
* [SSHPry v2](https://github.com/nopernik/SSHPry2.0) [![stars](https://img.shields.io/github/stars/nopernik/SSHPry2.0.svg?style=social&label=stars)]（https://github.com/nopernik/SSHPry2.0）-间谍和控制SSH SSH客户端的TTY
* [redial](https://github.com/taypo/redial) [![stars](https://img.shields.io/github/stars/taypo/redial?style=social)]（https://github.com/taypo/redial）-用于Unix系统的基于终端的SSH会话管理器

### Automation

* [Ansible](https://github.com/ansible/ansible) [![stars](https://img.shields.io/github/stars/ansible/ansible.svg?style=social&label=stars)]（https://github.com/ansible/ansible）-通过* SSH *进行应用程序部署，配置管理和编排.
* [rtop](https://github.com/rapidloop/rtop) [![stars](https://img.shields.io/github/stars/rapidloop/rtop.svg?style=social&label=stars)]（https://github.com/rapidloop/rtop）-基于* SSH *的交互式远程系统监视工具.
* [DSH - Dancer's shell / distributed shell](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) -包装程序，用于从一个命令行执行多个远程Shell命令.
* [parallel-ssh](https://github.com/ParallelSSH/parallel-ssh) [![stars](https://img.shields.io/github/stars/ParallelSSH/parallel-ssh.svg?style=social&label=stars)]（https://github.com/ParallelSSH/parallel-ssh）-提供OpenSSH和相关工具的并行版本.
* [SSH Power Tool](https://code.google.com/p/sshpt/) -执行命令并将文件同时上传到许多服务器，而无需使用预共享密钥.

### Web

* [Secure Shell chrome extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo?hl=en)
* [GateOne](https://github.com/liftoff/GateOne) [![stars](https://img.shields.io/github/stars/liftoff/GateOne.svg?style=social&label=stars)]（https://github.com/liftoff/GateOne）-基于HTML5的终端仿真器和* SSH *客户端.
* [KeyBox](https://github.com/skavanagh/KeyBox) [![stars](https://img.shields.io/github/stars/skavanagh/KeyBox.svg?style=social&label=stars)]（https://github.com/skavanagh/KeyBox）-基于Web的* SSH *控制台，可集中管理对系统的管理访问.
* [Apache Guacamole](https://guacamole.incubator.apache.org/)  -Apache Guacamole是基于HTML5的无客户端远程桌面网关. 它支持标准协议，例如VNC，RDP和SSH.
* [SSHmon](https://github.com/hpello/sshmon) [![stars](https://img.shields.io/github/stars/hpello/sshmon.svg?style=social&label=stars)]（https://github.com/hpello/sshmon）-实时GUI监视SSH连接并建立端口转发.

### Testing / Honeypots

* [ssh-hammer](https://github.com/shazow/ssh-hammer) [![stars](https://img.shields.io/github/stars/shazow/ssh-hammer.svg?style=social&label=stars)]（https://github.com/shazow/ssh-hammer）-* SSH *负载测试工具.
* [kippo](https://github.com/desaster/kippo) [![stars](https://img.shields.io/github/stars/desaster/kippo.svg?style=social&label=stars)]（https://github.com/desaster/kippo）-* SSH * Honeypot.
* [cowrie](https://github.com/micheloosterhof/cowrie) [![stars](https://img.shields.io/github/stars/micheloosterhof/cowrie.svg?style=social&label=stars)]（https://github.com/micheloosterhof/cowrie）-* SSH * Honeypot（基于kippo）.
* [sshmitm](http://linux.die.net/man/8/sshmitm) -* SSH *中间猴子.
* [ssh-audit](https://github.com/arthepsy/ssh-audit) [![stars](https://img.shields.io/github/stars/arthepsy/ssh-audit.svg?style=social&label=stars)]（https://github.com/arthepsy/ssh-audit）-用于* SSH *服务器审核的工具.
* [sshesame](https://github.com/jaksi/sshesame) [![stars](https://img.shields.io/github/stars/jaksi/sshesame.svg?style=social&label=stars)]（https://github.com/jaksi/sshesame）-一个伪造的SSH服务器，它允许所有人进入并记录其活动.


### Alternatives to *SSH*

* [GoTTY](https://github.com/yudai/gotty) [![stars](https://img.shields.io/github/stars/yudai/gotty.svg?style=social&label=stars)]（https://github.com/yudai/gotty）-将您的终端共享为Web应用程序.
* [telnet](http://www.telnet.org/htm/faq.htm) -未加密的网络协议和用于连接到远程计算机并发出命令的应用程序.
* [ttyd](https://github.com/tsl0922/ttyd) [![stars](https://img.shields.io/github/stars/tsl0922/ttyd.svg?style=social&label=stars)]（https://github.com/tsl0922/ttyd）-通过网络共享您的终端.
* [rsh](https://en.wikipedia.org/wiki/Remote_Shell) -用于连接到远程计算机并发出命令的未加密的网络协议和应用程序.

## Libraries

* C / C ++
  * [libssh](https://www.libssh.org) -* SSH *库.
*高朗
  * [crypto/ssh](https://godoc.org/golang.org/x/crypto/ssh) -内置* SSH *客户端和服务器库.
  * [sftp](https://github.com/pkg/sftp) [![stars](https://img.shields.io/github/stars/pkg/sftp.svg?style=social&label=stars)]（https://github.com/pkg/sftp）-对go.crypto / ssh包的* SFTP *支持.
  * [go-sshkit](https://github.com/shazow/go-sshkit) [![stars](https://img.shields.io/github/stars/shazow/go-sshkit.svg?style=social&label=stars)]（https://github.com/shazow/go-sshkit）-用于在Go中构建* SSH *服务器和客户端的工具包.
  * [Socker](https://github.com/cosiner/socker) [![stars](https://img.shields.io/github/stars/cosiner/socker.svg?style=social&label=stars)]（https://github.com/cosiner/socker）-Go库简化了* SSH *的使用.
  * [go-sshkeys](https://github.com/moul/go-sshkeys) -SSH密钥操作库
* Java
  * [jsch](http://www.jcraft.com/jsch/) -纯* java *，* BSD *许可，* SSH2 *客户端库.
* Javascript / Node.js
  * [ssh2](https://github.com/mscdex/ssh2) [![stars](https://img.shields.io/github/stars/mscdex/ssh2.svg?style=social&label=stars)]（https://github.com/mscdex/ssh2）-* SSH2 *客户端和服务器模块，使用纯JavaScript *编写，用于* node.js *.
* Python
  * [paramiko](https://github.com/paramiko/paramiko) [![stars](https://img.shields.io/github/stars/paramiko/paramiko.svg?style=social&label=stars)]（https://github.com/paramiko/paramiko）-原生* Python * * SSHv2 *协议库.
* Ruby
  * [net-ssh](https://github.com/net-ssh/net-ssh) [![stars](https://img.shields.io/github/stars/net-ssh/net-ssh.svg?style=social&label=stars)]（https://github.com/net-ssh/net-ssh）-* SSH *（协议2）客户端的纯* Ruby *实现.

## Resources

### Tutorials

* [How to use *SSH* to Connect to a Remote Server](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-in-ubuntu)
* [Best practices](https://blog.0xbadc0de.be/archives/300)
* [Granting Temporary Access to Your Servers (Using Signed *SSH* Keys)](http://linux-audit.com/granting-temporary-access-to-servers-using-signed-ssh-keys/)
* [How to SSH login without a password](https://www.rosehosting.com/blog/ssh-login-without-password-using-ssh-keys/)
* [Gist: SSH Recipes](https://gist.github.com/mjalajel/beaa91a5f8d04ebb464c2c28da01406a) -收集用于编写很棒的ssh配置文件的食谱.

### Security

* [01/14/2016](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2016-0777) -整数溢出`CVE 2016 077 [7-8].
* [Security/Guidelines/OpenSSH - MozillaWiki](https://wiki.mozilla.org/Security/Guidelines/OpenSSH) -`sshd \ _config`为`6.7 +`，`5.3`.
* [Applied-Crypto-Hardening](https://github.com/BetterCrypto/Applied-Crypto-Hardening) [![stars](https://img.shields.io/github/stars/BetterCrypto/Applied-Crypto-Hardening.svg?style=social&label=stars)]（https://github.com/BetterCrypto/Applied-Crypto-Hardening）-用于`6.X`的`sshd \ _config`

### Documentation

* [man page](http://linux.die.net/man/1/ssh)
* [Specifications (OpenSSH)](http://www.openssh.com/specs.html)
* [Wikipedia article](https://en.wikipedia.org/wiki/Secure_Shell)

### Community

* [StackOverflow](http://stackoverflow.com/questions/tagged/ssh)
* [ServerFault](http://serverfault.com/questions/tagged/ssh)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Manfred Touron](https://github.com/moul) 放弃了此作品的所有版权以及相关或邻近的权利.
