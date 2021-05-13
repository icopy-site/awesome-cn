<div class="github-widget" data-repo="nix-community/awesome-nix"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="NixOS">](https://nixos.org)

&gt;精选的Nix社区最佳资源清单.

[Nix](https://github.com/nixos/nix) 是用于Linux和其他Unix系统的功能强大的程序包管理器，它使程序包管理可靠且可重现.

*请阅读 [contribution guidelines](https://github.com/nix-community/awesome-nix/blob/master/CONTRIBUTING.md) 在捐款之前.*



## Resources

### Learning

* [Nix Notes](https://github.com/noteed/nix-notes) -有关Nix的简短注释的集合，每个简短注释都构成了相同的虚拟机映像.
* [Nix Pills](https://nixos.org/nixos/nix-pills/) -最好的学习方法，并附有例子.
* [Nix Shorts](https://github.com/justinwoo/nix-shorts/) -有关Nix的简短笔记集.
* [nix.dev](https://nix.dev/) -为开发人员准备的明智指南，说明如何使用Nix生态系统完成任务.
* [Tour of Nix](https://nixcloud.io/tour) -有关Nix语言构造的在线交互式教程.

### Discovery

* [Hound](https://search.nix.gsc.io) -方便地搜索所有或选定的与Nix相关的存储库.
* [Nixpkgs Database](https://kamadorueda.github.io/nixpkgs-db/) -具有所有渠道，所有版本的Nix软件包的数据库.

### Newsletters

* [NixOS Weekly](https://weekly.nixos.org/) -**时事通讯，以随时了解社区更新.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) -进行NixOS配置并构建多种不同的映像类型，包括VirtualBox VM，Azure映像和安装ISO.
* [nixos-up](https://github.com/samuela/nixos-up) -超级容易的NixOS安装程序，可以从安装ISO使用.

## Channel History

* [Channel History](https://channels.nix.gsc.io) -获取Nix通道的历史git提交.
* [Nix Infra Status](https://status.nixos.org) -获取每个Nix通道的年龄和当前git commit.

## Deployment Tools

* [Colmena](https://github.com/zhaofengli/colmena) -一个简单，无状态的NixOS部署工具，以NixOps和morph为模型.
* [krops](https://cgit.krebsco.de/krops/about/) -轻量级的工具包，用于远程或本地部署NixOS系统.
* [KubeNix](https://github.com/xtruder/kubenix) -使用Nix的Kubernetes资源生成器.
* [KuberNix](https://github.com/saschagrunert/kubernix) -通过Nix软件包的单依赖Kubernetes集群
* [morph](https://github.com/DBCDK/morph) -用于管理现有NixOS主机的工具.
* [Nixery](https://github.com/google/nixery) -兼容Docker的容器注册表，可通过Nix临时构建映像.
* [NixOps](https://github.com/NixOS/nixops) -官方的Nix部署工具，与AWS，Hetzner等兼容.
* [nixos-shell](https://github.com/Mic92/nixos-shell) -使用Nix进行简单的无头VM配置（类似于Vagrant）.
* [pushnix](https://github.com/arnarg/pushnix) -简单的cli实用程序，可推送NixOS配置并使用ssh触发重建.
* [terraform-nixos](https://github.com/tweag/terraform-nixos) -一组旨在部署NixOS的Terraform模块.
* [terranix](https://terranix.org) -使用Nix和NixOS模块系统编写您的Terraform代码.

## Command-Line Tools

* [comma](https://github.com/Shopify/comma)  -快速运行任何二进制文件； 将“ nix run”和“ nix-index”包装在一起.
* [nixfmt](https://github.com/serokell/nixfmt) -用于Nix代码的格式化程序，旨在轻松应用统一样式.
* [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt) -用于nixpkgs的Nix代码格式化程序.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) -将您的包裹表达打成一个形状.
* [nix-diff](https://github.com/Gabriel439/nix-diff) -解释两个Nix派生为何不同的工具.
* [nix-index](https://github.com/bennofs/nix-index) -快速找到带有特定文件的Nix软件包.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) -用于更新源校验和的通用工具.
* [nix-tree](https://github.com/utdemir/nix-tree) -交互式浏览Nix派生的依赖图.

## Development

* [Arion](https://github.com/hercules-ci/arion) -在Nix / NixOS的帮助下运行docker-compose.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) -使用缓存来快速打开后续shell的`nix-shell`替代品.
* [Cachix](https://cachix.org/)  -托管的二进制缓存服务； 对于开源项目免费.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) -功能最完整且易于使用的`.gitignore`集成.
* [lorri](https://github.com/target/lorri/) -更好的“ nix-shell”开发来增强direnv.
* [niv](https://github.com/nmattia/niv/) -通过包固定轻松管理Nix项目的依赖项.
* [nix-direnv](https://github.com/nix-community/nix-direnv) -direnv环境自动装载器的快速装载器和片状配置.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) -验证Nixpkgs中的拉取请求是否正确构建的最佳工具.
* [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) -在提交时和在您的CI上运行linters / formatter.

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) -基于Nix的工具，可帮助构建Arduino草图.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) -将`shard.lock`转换为Nix表达式.

### Elm

* [elm2nix](https://github.com/hercules-ci/elm2nix) -将“ elm.json”转换为Nix表达式.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) -将Cabal文件转换为Nix构建表达式.
* [stack2nix](https://github.com/input-output-hk/stack2nix) -为Haskell项目生成nix表达式.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) -在Emacs中自动进行Haskell设置.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) -Nixpkgs的替代Haskell基础架构.

### Node.js

* [Napalm](https://github.com/nmattia/napalm) -支持使用轻量级npm注册表在Nix中构建npm软件包.
* [node2nix](https://github.com/svanderburg/node2nix) -从package.lock npm文件生成Nix表达式.
* [yarn2nix](https://github.com/nix-community/yarn2nix) -从`yarn.lock`文件生成Nix表达式.

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) -创建高度可复制的python环境的工具.
* [poetry2nix](https://github.com/nix-community/poetry2nix) -直接从构建python软件包 [Poetry's](https://python-poetry.org/) 诗歌锁无需转换步骤.
* [pypi2nix](https://github.com/nix-community/pypi2nix) -为Python软件包生成Nix表达式.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) -为您的Bundler管理的应用程序生成一个Nix表达式.

### Rust

* [fenix](https://github.com/nix-community/fenix) -夜间使用nix的Rust工具链和rust分析器.
* [naersk](https://github.com/nmattia/naersk)  -直接从Cargo.lock构建Rust包. 无需转换步骤.
* [rust-nix-templater](https://github.com/yusdacra/rust-nix-templater) -为Rust项目生成Nix构建和开发文件.

## NixOS Modules

* [musnix](https://github.com/musnix/musnix) -在NixOS中进行实时音频工作.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) -Nixpkgs扩展，专注于与Web相关的技术的易于部署.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) -完整的邮件服务器，由NixOS模块管理.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) -高性能计算软件包集.
* [Home Manager](https://github.com/nix-community/home-manager) -像NixOS一样管理您的用户配置.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) -具有更高层协议的比特币节点的Nix软件包和NixOS模块，重点是安全性.
* [nix-darwin](https://github.com/LnL7/nix-darwin) -像在NixOS上一样管理macOS配置.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) -Mozilla的最先进的Rust和Firefox叠加层.
* [nixpkgs-wayland](https://github.com/colemickens/nixpkgs-wayland) -流血的Wayland包装.
* [NUR](https://github.com/nix-community/NUR/)  -Nix用户存储库. 所有叠加层之母，允许访问用户存储库并通过属性安装软件包.

## Community

* [#nix:matrix.org (Unofficial)](https://matrix.to/#/#nix:matrix.org)
* [#nixos on FreeNode](https://webchat.freenode.net/?channels=nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) -寻求帮助和讨论与Nix相关的主题的最佳场所.
* [NixCon](https://nixcon.org/) -面向Nix和NixOS的贡献者和用户的年度社区会议.
* [Wiki (Unofficial)](https://nixos.wiki)
