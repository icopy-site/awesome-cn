<div class="github-widget" data-repo="MystenLabs/awesome-move"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable double-link-->
## Awesome Move [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 精选的代码和内容列表 [Move](https://github.com/move-language/move) 编程语言社区.

 Move 是一种用于编写安全智能合约的编程语言，最初由 Facebook 开发，用于为 Libra 区块链提供支持.  Move 旨在成为一种与平台无关的语言，以支持跨具有截然不同的数据和执行模型的不同区块链的通用库、工具和开发人员社区.  Move 的野心是成为无所不在的“web3 的 JavaScript”——当开发者想要快速编写涉及资产的安全代码时，应该用 Move 编写.



## Overview

- [Installation](https://github.com/move-language/move/tree/main/language/tools/move-cli#installation)
- [Problem Statement](https://github.com/mystenlabs/awesome-move/blob/main/docs/problem_statement.md#problem-statement)

## Move-Powered Blockchains

- [Sui](https://github.com/MystenLabs/sui) - 具有高吞吐量、低延迟和由 Move 编程语言支持的面向资产的编程模型的下一代智能合约平台（在 [devnet](https://medium.com/mysten-labs/sui-devnet-public-release-a2be304ff36b)).
- [0L](https://github.com/OLSF/libra)  - 中立复制状态机的参考实现. 从 Libra/Diem 技术中分叉出来（在 [mainnet](https://0l.network/)).
- [Starcoin](https://github.com/starcoinorg/starcoin) - 通过分层扩展的智能合约区块链网络（在 [mainnet](https://stcscan.io/)).
- [Aptos](https://github.com/aptos-labs/aptos-core) - Aptos-core 致力于成为最安全和最具可扩展性的第一层区块链解决方案（在 [mainnet](https://explorer.aptoslabs.com/?network=mainnet)).
- [Pontem](https://github.com/pontem-network/pontem) - 基于 Substrate 的平行链，带有板载 MoveVM（在 [testnet](https://polkadot.js.org/apps/?rpc=wss://testnet.pontem.network/ws#/explorer)).
- [Celo](https://github.com/celo-org/celo-blockchain) - 带有 EVM 和 MoveVM 的区块链 ([coming soon](https://www.businesswire.com/news/home/20210921006104/en/Celo-Sets-Sights-On-Becoming-Fastest-EVM-Chain-Through-Collaboration-With-Mysten-Labs)).
- [Diem](https://github.com/diem/diem) - 来自 Meta 的基于 Move 的原始区块链（形成.Facebook 的 Libra）（已停产）.
- [ChainX](https://github.com/chainx-org/ChainX) - 比特币的layer2智能合约网络已经支持WASM和EVM，正在支持MoveVM（在 [mainnet](https://scan.chainx.org)).

## Books

- [Move Book](https://move-language.github.io/move/) - Move 核心团队维护的 Move book（[中文](https://github.com/move-language/move/tree/main/language/documentation/book/translations/move-book-zh)).
- [Move Book](https://move-book.com/) - 移动书籍维护 [@damirka](https://github.com/damirka) ([中文](https://move-book.com/cn/)).
- [Move Patterns](https://www.move-patterns.com/) - 一本关于 Move 软件设计模式的书，由 [@villesundell](https://github.com/villesundell).

## Tutorials

- [Implementing, testing, and verifying a fungible token](https://github.com/move-language/move/tree/main/language/documentation/tutorial) - 由 Move 核心团队维护.
- [Programming with objects](https://docs.sui.io/build/programming-with-objects) - 由 Sui 团队维护.
- [Move and SmartContract Development](https://starcoinorg.github.io/starcoin-cookbook/docs/move/) - 由 Starcoin 团队维护.
- [Move Language](https://imcoding.online/courses/move-language) - 交互式移动语言课程，对所有人免费，由维护 [imcoding.online](https://imcoding.online) ([中文](https://imcoding.online/courses/move-language?lng=zh)).

## Community

- [Move Language Discord](https://discord.gg/cPUmhe24Mz)
- [Move @ Sui by Mysten Labs Discord](https://discord.gg/sui)
- [Move @ 0L Discord](https://discord.gg/0lnetwork)
- [Move @ Starcoin Discord](https://discord.gg/starcoin)
- [Move @ Aptos Discord](https://discord.gg/aptoslabs)
- [MoveChina](https://move-china.com) - 最大的Move编程语言中文社区.

## Code

用 Move 编写的代码.

### Fungible Tokens

- [Fungible token examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/fungible_tokens) - 来自 Sui 的多个示例令牌实现.
- [BasicCoin](https://github.com/move-language/move/tree/main/language/documentation/examples/experimental/basic-coin) - 一个玩具实现 [ERC20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)- 像可替代的代币.
- [Diem](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/Diem.move) - 一个类似 ERC20 的令牌，具有许可的铸造/燃烧，另请参阅此 [spec](https://github.com/diem/dip/blob/main/dips/dip-20.md) . 部署在 0L 上.
- [Token](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/Token.move)  - 另一个类似 ERC20 的代币. 部署在星币上.
- [GAS](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/0L/GAS.move)  - 实例化上述 Diem 标准的代币. 部署在 0L 上.
- [STC](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/STC.move)  - 实例化上述星币标准的代币. 部署在星币上.
- [STAR](https://github.com/Elements-Studio/starswap-core/blob/master/sources/gov/STAR.move) - A governance token of Starswap dApp that powers the AMM+DEX ecosystem. Deployed on Starcoin.
- [XUSDT](https://github.com/Elements-Studio/poly-stc-contracts/blob/master/sources/asset/erc20/XUSDT.move) - 星币上USDT的映射资产.
- [XETH](https://github.com/Elements-Studio/poly-stc-contracts/blob/master/sources/asset/erc20/XETH.move) - 星币上 ETH 的映射资产.
- [WEN stablecoin](https://github.com/wenwenprotocol/wen-protocol) - 部署在星币上.
- [FAI stablecoin](https://github.com/BFlyFinance/FAI) - 部署在 Starcoin 上的超额抵押稳定币.
- [FLY stablecoin](https://github.com/BFlyFinance/FLY) - 部署在 Starcoin 上的分叉 OHM 的实现.
- [Synthetic token backed by a basket containing a reserve of other tokens](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/XDX.move) - 来自吴庭艳.
- [XBTC](https://github.com/OmniBTC/OmniBridge/blob/main/aptos/bridge/sources/xbtc.move) - Aptos 上的 BTC 镜像资产.
- [XBTC](https://github.com/OmniBTC/OmniBridge/blob/main/sui/bridge/sources/xbtc.move) - Sui 上的 BTC 镜像资产.

### Non-Fungible Tokens

- [NFT examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/nfts) - 来自 Sui 的多个 NFT 示例实现.
- [NFT](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/NFT.move)  - 类似 ERC721 的代币. 部署在星币上.
- [Merkle Airdrop](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/MerkleNFT.move)  - 用于空投大量 NFT 的实用程序. 部署在星币上.
- [NFT](https://github.com/diem/diem/blob/main/diem-move/diem-framework/experimental/sources/NFT.move)  - 混合 ERC721/ERC1155 类令牌的实现. 来自迪姆.
- [BARS](https://github.com/diem/diem/blob/main/diem-move/diem-framework/experimental/sources/BARS.move)  - 实例化该混合标准的 NFT. 来自迪姆.
- [MultiToken](https://github.com/diem/diem/blob/main/diem-move/diem-framework/experimental/sources/MultiToken.move)  - 类似 ERC1155 的代币. 来自迪姆.
- [NFTGallery](https://github.com/diem/diem/blob/main/diem-move/diem-framework/experimental/sources/NFTGallery.move)  - 用于持有多个相同类型的 NFT 的实用程序. 来自迪姆.
- [NFT Protocol](https://github.com/Origin-Byte/nft-protocol)  - NFT 协议和收集框架. 来自 OriginByte.
- [Suia](https://github.com/Mynft/suia) - Sui 上的第一个 POAP 应用程序.

### Decentralized Identity
- [aptos-cid](https://github.com/coming-chat/aptos-cid) - 在 Aptos 上的去中心化身份，Aptos 是 ComingChat 的基础账户系统.
- [MoveDID](https://github.com/NonceGeek/MoveDID)  - MoveDID 是一种 DID 协议，兼容基于 Move 的区块链网络，包括 Aptos、Sui 和 Starcoin. 维护者 [NonceGeek](https://github.com/NonceGeek).


### DeFi

- [DeFi examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/defi) - 来自 Sui 的多个 DeFi 示例实现.
- [CoinSwap](https://github.com/move-language/move/tree/main/language/documentation/examples/experimental/coin-swap) - 一个玩具实现 [Uniswap](https://uniswap.org/)-like 包含两个代币的流动资金池.
- [Starswap](https://github.com/Elements-Studio/starswap-core)  - Uniswap 风格的 DEX. 部署在星币上.
- [Offer](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/offer.move) - 任何资产对的原子互换的通用实现.
- [AptosRedPacket](https://github.com/coming-chat/aptos-red-packet) - Aptos上集私聊和加密钱包于一体的红包社交APP.
- [SuiRedPacket](https://github.com/coming-chat/sui-red-packet) - 一款集私聊和加密钱包于一身的红包社交APP.
- [AptosAMMswap](https://github.com/OmniBTC/Aptos-AMM-swap) - 由 OmniBTC 团队实施的 Aptos AMM Swap.
- [SuiAMMswap](https://github.com/OmniBTC/Sui-AMM-swap) - 由 OmniBTC 团队实施的 Sui AMM Swap.
- [AptosOmniSwap](https://github.com/OmniBTC/OmniSwap/tree/main/aptos) - 基于跨链互通协议虫洞，aptos与EVM链（如ETH/BSC/AVAX等）一键切换.
- [DolaProtocol](https://github.com/OmniBTC/DolaProtocol) - 以各公链单一币池为核心，Wormhole、Layerzero等跨链消息协议为桥梁，Sui公链为结算中心的去中心化全链流动性聚合协议.
- [ObjectMarket](https://github.com/coming-chat/object-market) - Sui 网络中独特的对象交易市场.

### SocialFi
- [Dmens](https://github.com/coming-chat/Dmens) - Decentralized Moments 是建立在 Sui 网络上的区块链 Twitter 协议.

### On-Chain Governance

- [ValidatorUniverse](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/0L/ValidatorUniverse.move)  - 验证者集管理. 部署在 0L 上.
- [Oracle](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/0L/Oracle.move)  - 用于链上社区投票. 部署在 0L 上.
- [DAO](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/Dao.move)  - 用于链上提案和投票. 部署在星币上.
- [DiemSystem](https://github.com/diem/diem/blob/main/diem-move/diem-framework/DPN/sources/DiemSystem.move)  - 验证者集管理. 来自迪姆.
- [Vote](https://github.com/diem/diem/blob/main/diem-move/diem-framework/experimental/sources/Vote.move)  - 链上投票. 来自迪姆.

### Cross-Chain Bridge

- [Poly Bridge](https://github.com/Elements-Studio/poly-stc-contracts)  - Move 和 EVM 之间的第一个跨链桥. 部署在星币上.
- [OmniBTC Bridge](https://github.com/OmniBTC/OmniBridge) - 基于超轻节点的比特币和Move语言公链（如Aptos和Sui）之间的桥梁.

### Accounts

- [Account](https://github.com/diem/diem/blob/main/diem-move/diem-framework/core/sources/Account.move)  - 由 Diem 支持的链的通用帐户. 来自迪姆.
- [DiemAccount](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/DiemAccount.move)  - 上面的叉子. 从 0L 开始.
- [Account](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/Account.move)  - 上面的叉子. 来自星币.

### Frameworks

Move **框架**是包含在链的创世状态中的一组 Move 模块. 
这些模块通常实现关键概念，如账户、货币、. 
将特定于区块链的框架逻辑与 Move 语言的通用功能分开的能力是 Move 平台无关设计的关键部分.

- [Sui Framework](https://github.com/MystenLabs/sui/tree/main/crates/sui-framework)
- [Aptos Framework](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework)
- [0L Framework](https://github.com/OLSF/libra/tree/main/language/diem-framework/modules/0L)
- [Starcoin Framework](https://github.com/starcoinorg/starcoin-framework)
- [Diem Framework](https://github.com/diem/diem/tree/main/diem-move/diem-framework/DPN)

### Libraries

- [Move standard library](https://github.com/move-language/move/tree/main/language/move-stdlib)  - 旨在（但不是必需）用于运行 Move 的每个平台的实用程序. 来自 Move 仓库.
- [Move nursery](https://github.com/move-language/move/tree/main/language/move-stdlib/nursery)  - 最终可能被提升到标准库中的实验模块. 来自 Move 仓库.
- [Decimal](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/0L/Decimal.move)  - 十进制值的高效实现. 从 0L 开始.
- [Math](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/Math.move)  - 数学效用函数. 来自星币.
- [Compare](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/compare.move)  - 多态比较（即比较同一类型的任意两个移动值）. 从托儿所.
- [Vault](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/vault.move)  - 功能库. 从托儿所.
- [ACL](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/acl.move)  - 基于列表的访问控制库. 从托儿所.
- [TaoHe](https://github.com/taoheorg/taohe) - 可嵌套 Move 资源的集合.
- [Starcoin Framework Commons](https://github.com/starcoinorg/starcoin-framework-commons)  - starcoin 框架上的 Move commons 实用程序库. 来自星币.
- [Movemate](https://github.com/pentagonxyz/movemate)  - Aptos 和 Sui 的智能合约构建块（数学实用程序、治理合约、托管等）. 由五角大楼团队维护.
- [Move cron parser](https://github.com/snowflake-so/move-cron-parser#readme)  - 库是为解析 cron 表达式而构建的. 由雪花网络团队维护.

### Miscellaneous

- [Move-on-EVM](https://github.com/move-language/move/tree/main/language/evm) - 将 Move 源代码编译为 EVM 字节码的实验项目.
- [aoc-move](https://github.com/whonore/aoc-move) - Move 中代码解决方案的出现，带有一些形式验证.

## Tools

- [Move Package Manager](https://github.com/move-language/move/tree/main/language/tools/move-cli) - 类似于 Move 的 `cargo` 或 `npm`：用于构建、运行、测试、调试和验证 Move 的单个 CLI（以及其他工具挂钩的相应 Rust API） [packages](https://move-language.github.io/move/) . 由 Move 核心团队维护.
- [Move Prover](https://github.com/move-language/move/tree/main/language/move-prover)  - 以 Move 源代码编写的用户定义规范的形式验证. 由 Move 核心团队维护.
- [Move Read/Write Set Analyzer](https://github.com/move-language/move/tree/main/language/tools/read-write-set)  - 静态分析工具，用于计算 Move 程序接触的全局内存的过度逼近. 由 Move 核心团队维护.
- [Move Playground JS Library](https://github.com/imcoding-online/js-move-playground) - 包装 [Move Playground by Pontem](https://playground.pontem.network/) 作为浏览器的 JavaScript 库. 您可以使用它来构建自己的 Move Playground.

## IDEs

- [Move VS Code plugin](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer) - 由 Move 核心团队维护 ([source code](https://github.com/move-language/move/tree/main/language/move-analyzer)).
- [Move IntelliJ plugin](https://plugins.jetbrains.com/plugin/14721-move-language) - 由 Pontem 团队维护（[source code](https://github.com/pontem-network/intellij-move)).
- [Move Playground](https://playground.pontem.network/) - 喜欢 [Remix](https://remix.ethereum.org/) 为移动.  Web IDE 的 Alpha 版本. 看 [instructions](https://gist.github.com/borispovod/64b6d23741d8c1f4b0b958a3a74aa68d) . 由 Pontem 团队维护.
- [Starcoin IDE](https://marketplace.visualstudio.com/items?itemName=starcoinorg.starcoin-ide) - 由星币团队维护（[source code](https://github.com/starcoinorg/starcoin-ide)).
- [Move Vim](https://github.com/rvmelkonian/move.vim) - 由维护 [@rvmelkonian](https://github.com/rvmelkonian/).
- [move-mode](https://github.com/amnn/move-mode) - Emacs 的主要模式由 [@amnn](https://github.com/amnn/).

## Package Managers
- [Movey](https://www.movey.net/) - 一个 crates.io 风格的移动包存储库.

## Wallets

- [StarMask](https://github.com/starcoinorg/starmask-extension)  - Starcoin 区块链的钱包. 由星币团队维护（[Chrome Webstore](https://chrome.google.com/webstore/detail/starmask/mfhbebgoclkghebffdldpobeajmbecfk?hl=en)).
- [Sui Wallet](https://github.com/MystenLabs/sui/tree/main/apps/wallet) - Sui 的 chrome (v88+) 扩展钱包 ([Chrome Webstore](https://chrome.google.com/webstore/detail/sui-wallet/opcgpfmipidbgpenhmajoajpbobppdil)).
- [Pontem Wallet](https://github.com/pontem-network/pontem-wallet) - Pontem 团队对 Aptos 网络的钱包扩展（[Chrome Webstore](https://chrome.google.com/webstore/detail/pontem-wallet/phkbamefinggmakgklpkljjmgibohnba)).
- [Fewcha Aptos Wallet](https://github.com/fewcha-wallet/fewcha.app) - 第一层区块链 Aptos 的钱包（[Chrome Webstore](https://chrome.google.com/webstore/detail/fewcha-aptos-wallet/ebfidpplhabeedpnhjnobghokpiioolj)).
- [bcs-js](https://github.com/pontem-network/lcs-js) - JavaScript 实现 [BCS](https://github.com/diem/bcs) Move 使用的序列化方案，可能对实现钱包很有用.
- [ComingChat](https://coming.chat/)  - 去中心化的社会金融/web3 门户. 支持公链钱包，如Sui、Aptos钱包.
- [Suiet Wallet](https://github.com/suiet/suiet)  - Sui 的开源钱包.  ([Chrome Webstore](https://chrome.google.com/webstore/detail/suiet/khpkpbbcccdmmclmpigdgddabeilkdpd), [Website](https://suiet.app)) 
- [Ethos Wallet](https://github.com/EthosWallet/chrome-extension) - Sui 的开源 chrome 扩展钱包 ([Chrome Webstore](https://chrome.google.com/webstore/detail/ethos-sui-wallet/mcbigmjiafegjnnogedioegffbooigli), [Website](https://ethoswallet.xyz/)).

### Wallet Adapters

- [Sui Wallet](https://github.com/MystenLabs/sui/tree/main/sdk/wallet-adapter) - 隋钱包适配器.
- [Suiet Wallet](https://github.com/suiet/wallet-adapter) - 套装钱包适配器.

### Wallet Kits

- [Suiet Wallet Kit](https://github.com/suiet/wallet-kit) - 一个包支持所有具有可定制用户界面的 Sui 钱包.
- [Ethos Connect](https://github.com/EthosWallet/ethos-connect) - 带有内置钱包适配器和电子邮件选项的 UI，用于支持 Sui 上的所有钱包和无钱包用户.

## SDKs
- [go-sui-sdk](https://github.com/coming-chat/go-sui-sdk) - Sui Golang SDK.
- [go-aptos-sdk](https://github.com/coming-chat/go-aptos-sdk) - Aptos Golang SDK.
- [OmniSwap-Sui-SDK](https://github.com/OmniBTC/OmniSwap-Sui-SDK) - Sui Network 上的 AMM Swap SDK.

## Papers

### Language Design

- [Move: A Language With Programmable Resources](https://developers.diem.com/papers/diem-move-a-language-with-programmable-resources/2019-06-18.pdf) - 这是 2018 年发布的原始 Move 白皮书.其中的许多方面现在已经过时（例如，字节码指令的语法和描述），但前两部分值得一读，以解释使用资产以及 Move 如何处理它们.
- [Robust Safety for Move](https://arxiv.org/abs/2110.05043)
- [The Move Borrow Checker](https://arxiv.org/abs/2205.05181)
- [Resources: A Safe Language Abstraction for Money](https://arxiv.org/abs/2004.05106)

### Static Analysis and Verification

- [Fast and Reliable Formal Verification of Smart Contracts with the Move Prover](https://arxiv.org/abs/2110.08362)
- [The Move Prover](https://research.facebook.com/publications/the-move-prover/)
- [Verification of Programs Written in Libra's Move Language](https://ethz.ch/content/dam/ethz/special-interest/infk/chair-program-method/pm/documents/Education/Theses/Constantin_M%C3%BCller_MS_Report.pdf)
- [Exact and Linear-Time Gas-Cost Analysis](https://research.facebook.com/publications/exact-and-linear-time-gas-cost-analysis/)

## Videos

- [The Move Programming Language](https://github.com/MystenLabs/awesome-move/blob/master/youtu.be/J1U_0exNFu0)
- [Move on Sui](https://www.youtube.com/watch?v=xMsE1X4wio4)
- [Move on Aptos](https://www.youtube.com/watch?v=gvRJdJTQd8U)
- [Move: A Safe Language for Programming with Money](https://www.youtube.com/watch?v=EG2-7bQNPv4&ab_channel=FieldsInstitute) - 谈话来自 [@sblackshear](https://github.com/sblackshear) 在 [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) 研究研讨会系列.
- [Formal Verification of Move Programs for the Libra Blockchain](http://www.fields.utoronto.ca/talks/Formal-verification-Move-programs-Libra-blockchain) - 谈话来自 [@DavidLDill](https://github.com/DavidLDill) 在 [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) 研究研讨会系列.
- [Move for the Masses](https://www.youtube.com/watch?v=b_2jZ4YEfWc) 从 [Converge '22](https://converge.circle.com/event/4ea0d06f-3900-4b6d-a9cd-aeaedda9ef2e/summary)

## Slides
- [Move deep dive](https://docs.google.com/presentation/d/1Tb2iZD0xrQSlwXIJNL1djNYc0_p0szfB2STgURgHgls/edit?usp=sharing)
- [Move overview](https://docs.google.com/presentation/d/1gU-M42Juz7ARc61unPXphJ_BX1OlQrBwR1VdaPT4M5w/edit?usp=sharing) 从 [Reasoning About Financial Systems](https://reasoningaboutfinancialsystems.org/) 车间在 [SBC '22](https://cbr.stanford.edu/sbc22/)

## Podcasts

- [Move and Sui with Sam Blackshear from Mysten Labs](https://zeroknowledge.fm/228-2/)
- [Move AMA covering Move origin story](https://twitter.com/i/spaces/1jMKgepNOleJL)

## Blog Posts
- [Comparing Move and Rust smart contract development](https://medium.com/@kklas/smart-contract-development-move-vs-rust-4d8f84754a8f)
- [Comparing Diem-style Move and Sui Move](https://sui.io/resources-move/why-we-created-sui-move)

## Security
- [Aptos-movevm Denial of Service Vulnerability](https://medium.com/numen-cyber-labs/analysis-of-the-first-critical-0-day-vulnerability-of-aptos-move-vm-8c1fd6c2b98e)

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/MystenLabs/awesome-move/blob/master/CONTRIBUTING.md) 第一的.
