<div class="github-widget" data-repo="nix-community/awesome-nix"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="NixOS">](https://nixos.org)

&gt; Nix 社区中最佳资源的精选列表.

[Nix](https://github.com/nixos/nix) 是 Linux 和其他 Unix 系统的强大包管理器，使包管理可靠且可重现.

*请阅读 [contribution guidelines](https://github.com/nix-community/awesome-nix/blob/master/CONTRIBUTING.md) 在贡献之前. *



## Resources

### Learning

* [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - 这就像一个让我们玩，但对于晦涩的软件文档.
* [Nix Notes](https://github.com/noteed/nix-notes) - 一组关于 Nix 的简短注释，每个注释都贡献于同一个虚拟机映像.
* [Nix Pills](https://nixos.org/nixos/nix-pills/) - 最好的学习方式，有例子.
* [Nix Shorts](https://github.com/justinwoo/nix-shorts/) - 关于 Nix 的简短笔记集.
* [nix.dev](https://nix.dev/) - 开发人员使用 Nix 生态系统完成工作的自以为是的指南.
* [Tour of Nix](https://nixcloud.io/tour) - 关于 Nix 语言结构的在线互动教程.

### Discovery

* [Hound](https://search.nix.gsc.io) - 轻松搜索所有或选定的 Nix 相关存储库.
* [Pkgs on Nix](https://pkgs.on-nix.com/) - 包含来自所有渠道的所有版本的 Nix 软件包的数据库.

### Newsletters

* [NixOS Weekly](https://weekly.nixos.org/) - *The* 时事通讯，随时了解社区更新.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) - 采用 NixOS 配置并构建多种不同的映像类型，包括 VirtualBox VM、Azure 映像和安装 ISO.
* [nixos-up](https://github.com/samuela/nixos-up) - 超级简单的 NixOS 安装程序，可以从安装 ISO 中使用.

## Channel History

* [Channel History](https://channels.nix.gsc.io) - 获取 Nix 频道的历史 git 提交.
* [Nix Infra Status](https://status.nixos.org) - 获取每个 Nix 频道的年龄和当前 git commit.
* [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - PR 是否已进入频道的跟踪器.

## Deployment Tools

* [Colmena](https://github.com/zhaofengli/colmena) - 一个简单的、无状态的 NixOS 部署工具，以 NixOps 和 morph 为模型.
* [krops](https://cgit.krebsco.de/krops/about/) - 用于远程或本地部署 NixOS 系统的轻量级工具包.
* [KubeNix](https://github.com/xtruder/kubenix) - 使用 Nix 的 Kubernetes 资源构建器.
* [KuberNix](https://github.com/saschagrunert/kubernix) - 通过 Nix 包的单依赖 Kubernetes 集群.
* [morph](https://github.com/DBCDK/morph) - 用于管理现有 NixOS 主机的工具.
* [Nixery](https://github.com/google/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.
* [NixOps](https://github.com/NixOS/nixops) - 官方 Nix 部署工具，兼容 AWS、Hetzner 等.
* [nixos-shell](https://github.com/Mic92/nixos-shell) - 使用 Nix 的简单无头 VM 配置（类似于 Vagrant）.
* [pushnix](https://github.com/arnarg/pushnix) - 简单的 cli 实用程序，可推送 NixOS 配置并使用 ssh 触发重建.
* [terraform-nixos](https://github.com/tweag/terraform-nixos) - 一组旨在部署 NixOS 的 Terraform 模块.
* [terranix](https://terranix.org) - 使用 Nix 和 NixOS 模块系统来编写您的 Terraform 代码.

## Command-Line Tools

* [comma](https://github.com/Shopify/comma)  - 快速运行任何二进制文件； 将 `nix run` 和 `nix-index` 包装在一起.
* [nixfmt](https://github.com/serokell/nixfmt) - Nix 代码的格式化程序，旨在轻松应用统一样式.
* [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt) - 用于 nixpkgs 的 Nix 代码格式化程序.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) - 将您的包装表达打成一个形状.
* [nix-diff](https://github.com/Gabriel439/nix-diff) - 解释为什么两个 Nix 派生不同的工具.
* [nix-index](https://github.com/bennofs/nix-index) - 快速定位包含特定文件的 Nix 包.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) - 用于更新源校验和的通用工具.
* [nix-tree](https://github.com/utdemir/nix-tree) - 交互式浏览 Nix 派生的依赖关系图.

## Development

* [Arion](https://github.com/hercules-ci/arion) - 在 Nix/NixOS 的帮助下运行 `docker-compose`.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) - `nix-shell` 替代品，它使用缓存快速打开后续 shell.
* [Cachix](https://cachix.org/)  - 托管二进制缓存服务； 开源项目免费.
* [devshell](https://github.com/numtide/devshell) - 带有额外位和 toml 配置选项的 `mkShell` 能够载入非 nix 用户.
* [flake-utils](https://github.com/numtide/flake-utils) - 纯 Nix 薄片实用程序功能可帮助编写薄片.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - 功能最完整且易于使用的`.gitignore` 集成.
* [lorri](https://github.com/target/lorri/) - 一个更好的`nix-shell` 用于开发，增强了 direnv.
* [niv](https://github.com/nmattia/niv/) - 使用包固定对 Nix 项目进行简单的依赖管理.
* [nix-direnv](https://github.com/nix-community/nix-direnv) - 用于 direnv 环境自动加载器的快速加载器和 flake 兼容配置.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) - 验证 Nixpkgs 中的拉取请求是否正确构建的最佳工具.
* [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) - 在提交时和 CI 上运行 linter/格式化程序.

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) - 基于 Nix 的工具，可帮助构建 Arduino 草图.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) - 将 `shard.lock` 转换为 Nix 表达式.

### Elm

* [elm2nix](https://github.com/hercules-ci/elm2nix) - 将 `elm.json` 转换为 Nix 表达式.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) - 将 Cabal 文件转换为 Nix 构建表达式.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) - Nixpkgs 的替代 Haskell 基础设施.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) - Emacs 中的自动 Haskell 设置.
* [nixkell](https://github.com/pwm/nixkell) - 使用 Nix 和 direnv 的 Haskell 项目模板.
* [stack2nix](https://github.com/input-output-hk/stack2nix) - 为 Haskell 项目生成 nix 表达式.

### Node.js

* [Napalm](https://github.com/nmattia/napalm) - 支持使用轻量级 npm 注册表在 Nix 中构建 npm 包.
* [node2nix](https://github.com/svanderburg/node2nix) - 从`package.json`（或`package-lock.json`）生成Nix 表达式（存储为文件）.
* [npmlock2nix](https://github.com/tweag/npmlock2nix) - 从`package-lock.json`（内存中）生成 Nix 表达式，主要用于 Web 项目.
* [yarn2nix](https://github.com/nix-community/yarn2nix) - 从 `yarn.lock` 文件生成 Nix 表达式.

### PHP

* [composer2nix](https://github.com/svanderburg/composer2nix) - 生成 Nix 表达式以构建 Composer 包.
* [composition-c4](https://github.com/fossar/composition-c4) - 支持从 `composer.lock`（使用 IFD）构建 Composer 包.
* [nix-phps](https://github.com/fossar/nix-phps) - Flake 包含旧的和未维护的 PHP 版本（用于 CI 使用）.

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) - 通过 Nix 轻松使用 PureScript 和其他工具的项目.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) - 创建高度可重现的 Python 环境的工具.
* [poetry2nix](https://github.com/nix-community/poetry2nix) - 直接从构建 Python 包 [Poetry's](https://python-poetry.org/)  `poetry.lock`. 无需转换步骤.
* [pypi2nix](https://github.com/nix-community/pypi2nix) - 为 Python 包生成 Nix 表达式.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) - 为您的 Bundler 管理的应用程序生成 Nix 表达式.

### Rust

* [fenix](https://github.com/nix-community/fenix) - 每晚用于 nix 的 Rust 工具链和 Rust 分析器.
* [naersk](https://github.com/nmattia/naersk)  - 直接从 `Cargo.lock` 构建 Rust 包. 无需转换步骤.
* [nix-cargo-integration](https://github.com/yusdacra/nix-cargo-integration) - 一个允许轻松轻松地集成 Cargo 项目的库.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla 与 Rust 工具链和 Firefox 的叠加.
* [rust-nix-templater](https://github.com/yusdacra/rust-nix-templater) - 为 Rust 项目生成 Nix 构建和开发文件.
* [rust-overlay](https://github.com/oxalica/rust-overlay) - 二进制分布式 Rust 工具链的纯且可重现的 nix 覆盖.

### Scala

* [sbt-derivation](https://github.com/zaninime/sbt-derivation) - sbt 的 mkDerivation，类似于 buildGoModule.
* [sbt-nix.g8](https://github.com/gvolpe/sbt-nix.g8) - 用于具有 Nix 支持的新 Scala 项目的 gter8 模板.

## NixOS Modules

* [musnix](https://github.com/musnix/musnix) - 在 NixOS 中进行实时音频工作.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) - Nixpkgs 扩展，专注于轻松部署 Web 相关技术.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 一个完整的邮件服务器，由 NixOS 模块管理.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) - 高性能计算包集.
* [Home Manager](https://github.com/nix-community/home-manager) - 像 NixOS 一样管理您的用户配置.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) - 用于比特币节点的 Nix 包和 NixOS 模块，具有更高层的协议，强调安全性.
* [nix-darwin](https://github.com/LnL7/nix-darwin) - 就像在 NixOS 上一样管理 macOS 配置.
* [nixpkgs-wayland](https://github.com/colemickens/nixpkgs-wayland) - 流血边缘的 Wayland 包.
* [NUR](https://github.com/nix-community/NUR/)  - Nix 用户存储库. 所有覆盖的母体，允许访问用户存储库并通过属性安装包.

## Community

* [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
* [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - 获得帮助和讨论 Nix 相关主题的最佳场所.
* [NixCon](https://nixcon.org/) - Nix 和 NixOS 贡献者和用户的年度社区会议.
* [Wiki (Unofficial)](https://nixos.wiki)
