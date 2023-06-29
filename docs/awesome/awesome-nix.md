<div class="github-widget" data-repo="nix-community/awesome-nix"></div>
## Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="NixOS">](https://nixos.org)

&gt; Nix 社区中最佳资源的精选列表.

[Nix](https://github.com/nixos/nix) 是一款适用于 Linux 和其他 Unix 系统的强大包管理器，使包管理变得可靠且可重复.

*请阅读 [contribution guidelines](https://github.com/nix-community/awesome-nix/blob/master/CONTRIBUTING.md) 在贡献之前.*



## Resources

### Learning

* [Building a Rust service with Nix](https://fasterthanli.me/series/building-a-rust-service-with-nix) - 关于使用 Nix 创建 Rust 应用程序的深入博客系列.
* [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - 它就像 Let&#39;s Play，但软件文档晦涩难懂.
* [Nix - A One Pager](https://code.tvl.fyi/about/nix/nix-1p) - Nix 语言的一页介绍.
* [Nix from First Principles: Flake Edition](https://tonyfinn.com/blog/nix-from-first-principles-flake-edition/) - 使用 Nix 功能、Flakes 以及使用 Nix 进行开发的现代速成课程.
* [Nix Notes](https://github.com/noteed/nix-notes) - 关于 Nix 的简短注释的集合，每个注释都贡献相同的虚拟机映像.
* [Nix Pills](https://nixos.org/guides/nix-pills/) - 最好的学习方式，带有示例.
* [Nix Shorts](https://github.com/alper/nix-shorts) - 关于如何使用 Nix 的简短说明集合，针对 Nix Flakes 进行了更新.
* [nix.dev](https://nix.dev/) - 为开发人员提供的关于使用 Nix 生态系统完成工作的固执己见的指南.
* [NixOS & Flakes Book](https://github.com/ryan4yin/nixos-and-flakes-book) - 一本针对初学者的非官方且固执己见的 NixOS &amp; Flakes 书籍.
* [Tour of Nix](https://nixcloud.io/tour) - 有关 Nix 语言结构的在线交互式教程.
* [Zero to Nix](https://zero-to-nix.com/) - 由确定系统创建的以薄片为中心的 Nix 及其概念指南，可帮助初学者快速入门.

### Discovery

* [Hound](https://search.nix.gsc.io) - 轻松搜索所有或选定的 Nix 相关存储库.
* [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - 查找频道中可用的软件包的所有版本以及您可以从中下载该软件包的修订版.
* [Noogle](https://noogle.dev/) - Nix API 搜索引擎允许根据函数的类型和其他属性搜索函数.
* [Pkgs on Nix](https://pkgs.on-nix.com/) - 包含所有版本、所有渠道的 Nix 软件包的数据库.
* [Home Manager Option Search](https://mipmip.github.io/home-manager-option-search/) - 搜索所有 2000 多个家庭管理器选项并阅读如何使用它们.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) - 采用 NixOS 配置并构建多个不同的映像类型，包括 VirtualBox VM、Azure 映像和安装 ISO.
* [nixos-infect](https://github.com/elitak/nixos-infect) - 将正在运行的非 NixOS Linux 主机替换为 NixOS.
* [nixos-up](https://github.com/samuela/nixos-up) - 超级简单的 NixOS 安装程序，可以从安装 ISO 中使用.
* [nix-installer](https://github.com/DeterminateSystems/nix-installer) - 官方 Nix 安装脚本的自选替代方案.

## Channel History

* [Channel History](https://channels.nix.gsc.io) - 获取 Nix 频道的历史 git 提交.
* [Nix Infra Status](https://status.nixos.org) - 获取每个 Nix 通道的年龄和当前 git 提交.
* [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - 显示主要 Hydra 作业集有问题的依赖关系（导致最多失败构建的依赖关系）的报告.
* [Nixpkgs Bot](https://git.maralorn.de/nixos-config/tree/packages/nixpkgs-bot) - 一个 Matrix 机器人，用于跟踪 Nixpkgs 拉取请求何时到达相关分支.
* [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - 跟踪 PR 是否已进入频道的跟踪器.

## Deployment Tools

* [bento](https://github.com/rapenne-s/bento/) - KISS 部署工具，可让您的 NixOS 队列（服务器和工作站）保持最新状态.
* [Colmena](https://github.com/zhaofengli/colmena) - 一个简单、无状态的 NixOS 部署工具，以 NixOps 和 morph 为模型.
* [deploy-rs](https://github.com/serokell/deploy-rs) - 一个简单的多配置文件 Nix-flake 部署工具.
* [krops](https://cgit.krebsco.de/krops/about/) - 用于远程或本地部署 NixOS 系统的轻量级工具包.
* [KubeNix](https://github.com/xtruder/kubenix) - 使用 Nix 的 Kubernetes 资源构建器.
* [KuberNix](https://github.com/saschagrunert/kubernix) - 通过 Nix 包的单依赖 Kubernetes 集群.
* [morph](https://github.com/DBCDK/morph) - 用于管理现有 NixOS 主机的工具.
* [Nixery](https://github.com/tazjin/nixery) - 与 Docker 兼容的容器注册表，可通过 Nix 临时构建镜像.
* [Nixinate](https://github.com/MatthewCroughan/nixinate) - Nix flake 库，提供用于通过 SSH 管理现有 NixOS 主机的应用程序输出.
* [NixOps](https://github.com/NixOS/nixops) - Nix 官方部署工具，兼容 AWS、Hetzner 等.
* [pushnix](https://github.com/arnarg/pushnix) - 简单的 cli 实用程序，可推送 NixOS 配置并使用 ssh 触发重建.
* [terraform-nixos](https://github.com/tweag/terraform-nixos) - 一组旨在部署 NixOS 的 Terraform 模块.
* [terranix](https://terranix.org) - 使用 Nix 和 NixOS 模块系统编写 Terraform 代码.

## Virtualisation
* [nixos-shell](https://github.com/Mic92/nixos-shell) - 使用 Nix 进行简单的无头虚拟机配置（类似于 Vagrant）.
* [extra-container](https://github.com/erikarvstedt/extra-container) - 从命令行运行声明性 NixOS 容器.
* [microvm](https://github.com/astro/microvm.nix) - 基于 NixOS 的 MicroVM.

## Command-Line Tools

* [alejandra](https://github.com/kamadorueda/alejandra) - 固执己见的 Nix 代码格式化程序，针对速度和一致性进行了优化.
* [comma](https://github.com/nix-community/comma)  - 快速运行任何二进制文件； 将“nix run”和“nix-index”包装在一起.
* [deadnix](https://github.com/astro/deadnix) - 扫描 Nix 文件中的死代码.
* [manix](https://github.com/mlvzk/manix) - 查找 Nixpkgs、NixOS 和 Home Manager 的配置选项和功能文档.
* [nixfmt](https://github.com/serokell/nixfmt) - Nix 代码的格式化程序，旨在轻松应用统一的样式.
* [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt) - nixpkgs 的 Nix 代码格式化程序.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) - Nixpkgs 包表达式的固执己见的 linter.
* [nix-alien](https://github.com/thiagokokada/nix-alien) - 在 Nix/NixOS 上轻松运行未修补的二进制文件.
* [nix-diff](https://github.com/Gabriella439/nix-diff) - 一个解释为什么两个 Nix 推导不同的工具.
* [nix-du](https://github.com/symphorien/nix-du) - 可视化要删除哪些 gc-roots 以释放 Nix 存储中的一些空间.
* [nix-index](https://github.com/bennofs/nix-index) - 快速找到包含特定文件的 Nix 软件包.
* [nix-init](https://github.com/nix-community/nix-init) - 通过哈希预取、依赖推断、许可证检测等从 URL 生成 Nix 包.
* [nix-melt](https://github.com/nix-community/nix-melt) - 类似游侠的 flake.lock 查看器.
* [nix-output-monitor](https://git.maralorn.de/nix-output-monitor/) - 在构建推导时生成有用的图表和统计数据的工具.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) - 用于更新源校验和的通用工具.
* [nix-tree](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.
* [nurl](https://github.com/nix-community/nurl) - 从存储库 URL 生成 Nix fetcher 调用.
* [nvd](https://gitlab.com/khumba/nvd)  - 两个存储路径之间的软件包版本差异； 它对于比较重建时的 NixOS 各代特别有用.
* [statix](https://github.com/nerdypepper/statix) - 用于检查和修复 Nix 代码中的反模式的 linter/fixer.

## Development

* [Arion](https://github.com/hercules-ci/arion) - 在 Nix/NixOS 的帮助下运行“docker-compose”.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) - “nix-shell”替代品，使用缓存快速打开后续 shell.
* [Cachix](https://cachix.org/)  - 托管二进制缓存服务； 对于开源项目免费.
* [Devbox](https://github.com/jetpack-io/devbox) - 即时、可移植且可预测的开发环境.
* [devshell](https://github.com/numtide/devshell) - `mkShell` 具有额外的位和 toml 配置选项，以便能够加入非 nix 用户.
* [dream2nix](https://github.com/nix-community/dream2nix) - 一个用于自动将包从其他构建系统转换到 Nix 的框架.
* [flake.parts](https://github.com/hercules-ci/flake-parts) - Flakes 的最小 Nix 模块框架：将您的 Flakes 拆分为模块并使用社区模块完成工作.
* [flake-utils](https://github.com/numtide/flake-utils) - Pure Nix flake 实用函数可帮助编写 flake.
* [flake-utils-plus](https://github.com/gytis-ivaskevicius/flake-utils-plus) - 轻量级 Nix 库 flake，用于轻松进行 NixOS flake 配置.
* [flox](https://github.com/flox/flox) - 管理和共享开发环境、打包项目以及在任何地方发布工件.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - 功能最齐全且易于使用的“.gitignore”集成.
* [haumea](https://github.com/nix-community/haumea) - Nix 语言基于文件系统的模块系统，类似于传统编程语言，支持文件层次结构和可见性.
* [lorri](https://github.com/nix-community/lorri/) - 一个更好的“nix-shell”，用于增强 direnv 的开发.
* [namaka](https://github.com/nix-community/namaka) - 基于 haumea 的 Nix 快照测试.
* [nil](https://github.com/oxalica/nil) - NIx 语言服务器，用于在 Nix 中编写的增量分析助手.
* [niv](https://github.com/nmattia/niv/) - 通过包固定轻松管理 Nix 项目的依赖关系.
* [nix-direnv](https://github.com/nix-community/nix-direnv) - direnv 环境自动加载器的快速加载器和 flake 兼容配置.
* [nix-update](https://github.com/Mic92/nix-update) - 更新 nix 软件包的版本/源哈希.
* [nixd](https://github.com/nix-community/nixd) - Nix 语言服务器，基于 Nix 库.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) - 验证 Nixpkgs 中的拉取请求是否正确构建的最佳工具.
* [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) - 在提交时和 CI 上运行 linter/formatters.
* [rnix-lsp](https://github.com/nix-community/rnix-lsp) - Nix 的语法检查语言服务器.
* [robotnix](https://github.com/danielfullmer/robotnix) - Android (AOSP) 图像的声明性且可重现的构建系统.

## DevOps

* [Makes](https://github.com/fluidattacks/makes) - 基于 Nix 的 CI/CD 管道框架，用于从任何地方以任何语言构建、测试和发布项目. 
* [Standard](https://github.com/divnix/std) - 一个固执己见的 Nix Flakes 框架，可让大型项目中的 Nix 代码井井有条，并配有针对 DevOps 场景优化的友好 CLI/TUI.

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) - 基于 Nix 的工具可帮助构建 Arduino 草图.

### Clojure

* [clj-nix](https://github.com/jlesquembre/clj-nix) - Clojure 项目的 Nix 辅助函数.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) - 将 `shard.lock` 转换为 Nix 表达式.

### Elm

* [elm2nix](https://github.com/cachix/elm2nix) - 将 `elm.json` 转换为 Nix 表达式.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) - 将 Cabal 文件转换为 Nix 构建表达式.
* [haskell-flake](https://github.com/srid/haskell-flake) - 用于 Haskell 开发的“flake-parts”Nix 模块.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) - Nixpkgs 的替代 Haskell 基础设施.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) - Emacs 中的自动 Haskell 设置.
* [nixkell](https://github.com/pwm/nixkell) - 使用 Nix 和 direnv 的 Haskell 项目模板.

### Node.js

* [Napalm](https://github.com/nix-community/napalm) - 支持使用轻量级 npm 注册表在 Nix 中构建 npm 包.
* [node2nix](https://github.com/svanderburg/node2nix) - 从 `package.json` （或 `package-lock.json`）生成 Nix 表达式（以文件形式存储）.
* [npmlock2nix](https://github.com/nix-community/npmlock2nix) - 从 `package-lock.json` （内存中）生成 Nix 表达式，主要用于 Web 项目.

### OCaml

* [opam2nix](https://github.com/timbertson/opam2nix) - 从 opam 包生成 Nix 表达式.

### PHP

* [composer2nix](https://github.com/svanderburg/composer2nix) - 生成 Nix 表达式来构建 Composer 包.
* [composer-plugin-nixify](https://github.com/stephank/composer-plugin-nixify) - Composer 插件可帮助 Nix 打包.
* [composition-c4](https://github.com/fossar/composition-c4) - 支持从 `composer.lock` 构建 Composer 包（使用 IFD）.
* [nix-phps](https://github.com/fossar/nix-phps) - 包含旧的和未维护的 PHP 版本的 Flake（用于 CI 使用）.
* [nix-shell](https://github.com/loophp/nix-shell/) - 用于 PHP 开发的 Nix shell.

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) - 一个通过 Nix 轻松使用 PureScript 和其他工具的项目.
* [purs-nix](https://github.com/purs-nix/purs-nix)  - CLI 和库组合设计用于使用 Nix 管理 PureScript 项目. 它提供了可在您的项目中使用的 Nix API，以及用于管理开发过程的命令行界面.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) - 创建高度可重复的 python 环境的工具.
* [pip2nix](https://github.com/nix-community/pip2nix) - 与存储库无关的 Python 包生成器工具.
* [poetry2nix](https://github.com/nix-community/poetry2nix) - 直接构建Python包 [Poetry's](https://python-poetry.org/)  `诗.锁`. 无需转换步骤.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) - 为 Bundler 管理的应用程序生成 Nix 表达式.
* [ruby-nix](https://github.com/sagittaros/ruby-nix) - 使用 Nix 生成可重现的 ruby​​/bundler 应用程序环境.

### Rust

* [cargo2nix](https://github.com/cargo2nix/cargo2nix) - 粒度缓存、开发 shell、Nix 和 Rust 集成.
* [crane](https://github.com/ipetkov/crane) - 用于构建具有增量工件缓存的 Cargo 项目的 Nix 库.
* [fenix](https://github.com/nix-community/fenix) - Rust 工具链和 Rust 分析器每晚适用于 nix.
* [naersk](https://github.com/nmattia/naersk)  - 直接从“Cargo.lock”构建 Rust 包. 无需转换步骤.
* [nix-cargo-integration](https://github.com/yusdacra/nix-cargo-integration) - 一个可以轻松轻松地集成 Cargo 项目的库.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla 与 Rust 工具链和 Firefox 的叠加.
* [rust-nix-templater](https://github.com/yusdacra/rust-nix-templater) - 为 Rust 项目生成 Nix 构建和开发文件.
* [rust-overlay](https://github.com/oxalica/rust-overlay) - 二进制分布式 Rust 工具链的纯且可复制的 nix 覆盖.

### Scala

* [sbt-derivation](https://github.com/zaninime/sbt-derivation) - sbt 的 mkDerivation，类似于 buildGoModule.

## NixOS Modules

* [base16.nix](https://github.com/SenchoPens/base16.nix) - 主题节目的片状方式 [base16](https://github.com/chriskempson/base16) 包括颜色方案、胡子模板支持.
* [Home Manager](https://github.com/nix-community/home-manager) - 像 NixOS 一样管理您的用户配置.
* [musnix](https://github.com/musnix/musnix) - 在 NixOS 中进行实时音频工作.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) - Nixpkgs 扩展，重点是易于部署网络相关技术.
* [NixVim](https://github.com/pta2002/nixvim) - 使用 Nix 模块和 Nixpkg 构建的 NeoVim 发行版.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 一个完整的邮件服务器，使用 NixOS 模块进行管理.
* [Stylix](https://github.com/danth/stylix) - NixOS 的系统范围配色和排版.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) - 具有更高层协议的比特币节点模块和包，强调安全性.

## NixOS Configuration Editors

### Desktop apps

* [NixOS Configuration Editor](https://github.com/vlinkz/nixos-conf-editor)  - NixOS 配置的图形编辑器.  Rust 和 GTK 中的桌面应用程序.
* [Nix Software Center](https://github.com/vlinkz/nix-software-center)  - 安装和管理 Nix 软件包.  Rust 和 GTK 中的桌面应用程序.

### Webinterface

* [MyNixOS](https://mynixos.com/)  - Nix 薄片的图形编辑器. 创建和管理 NixOS 和 Nix home-manager 的配置和模块. 与其说是 Nix 编辑器，不如说是 Nix 生成器，因为它不允许导入 Nix 文件.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) - 高性能计算包集.
* [chaotic-nyx](https://github.com/chaotic-cx/nyx)  - 每日更新诸如“mesa_git”之类的前沿软件包以及其他尚未包含在 Nixpkgs 中的软件包. 由制作者创建 [Chaotic-AUR](https://github.com/chaotic-aur/). 
* [nix-darwin](https://github.com/LnL7/nix-darwin) - 管理 macOS 配置，就像在 NixOS 上一样.
* [nixpkgs-firefox-darwin](https://github.com/bandithedoge/nixpkgs-firefox-darwin) - 自动更新适用于 macOS 的 Firefox 二进制包.
* [nixpkgs-wayland](https://github.com/nix-community/nixpkgs-wayland) - 尖端的 Wayland 软件包.
* [NUR](https://github.com/nix-community/NUR/)  - Nix 用户存储库. 所有覆盖层之母，允许访问用户存储库并通过属性安装包.

## Community

* [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
* [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - 获得帮助和讨论 Nix 相关主题的最佳场所.
* [NixCon](https://nixcon.org/) - Nix 和 NixOS 的贡献者和用户的年度社区会议.
* [Wiki (Unofficial)](https://nixos.wiki)
