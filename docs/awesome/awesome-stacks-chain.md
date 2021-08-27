<div class="github-widget" data-repo="friedger/awesome-stacks-chain"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Stacks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Stacks](https://raw.githubusercontent.com/friedger/awesome-stacks-chain/master/img/awesome-stacks.png 'Awesome Stacks')](https://www.stacks.co)

[Stacks](https://www.stacks.co/what-is-stacks) 是一个以比特币为基础的区块链，支持应用程序、智能合约和数字资产.  Stacks 是连接比特币并通过区块链实现智能合约和去中心化应用的第 1 层区块链. [Clarity language](https://clarity-lang.org/) . 通过 [Proof of Transfer (PoX) consensus mechanism](https://docs.stacks.co/understand-stacks/proof-of-transfer) ，Stacks 区块链的状态锚定在比特币区块链上，从而为 Stacks 提供了比特币的安全性和最终性.  Stacks 为比特币带来了其他区块链技术的可编程性，无需修改比特币本身的核心共识机制.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->



<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Apps

### Wallets

- [Stacks Wallet for Desktop](https://www.hiro.so/wallet/install-desktop) - 用于管理 STX 和单独或在池中堆叠的桌面钱包应用程序.
- [Stacks Wallet for Web](https://www.hiro.so/wallet/install-web) - 用于连接到 Stacks 网络应用程序的网络钱包.
- [Xverse Wallet](https://www.secretkeylabs.com/) - 用于管理 STX 和堆叠的移动钱包应用程序.

### Stacks Web Applications

- [Stacks Explorer](https://explorer.stacks.co/?chain=mainnet) - 用于审查 Stacks 区块链上的交易的应用程序.
- [Boom.money](https://boom.money) - 一个专注于 NFT 和自定义代币的网络钱包.
- [Send Many](https://sendstx.com/) - 在一次交易中向多个收件人发送 STX 的应用程序.
- [MIA Block explorer](http://miamining.com/) - 一个 web 应用程序，用于为所有和个人帐户 exolore MIA 硬币交易.
- [Speed Spend](https://speed-spend.org) - 一套在测试网上运行的 Clarity 实验（[source](https://github.com/friedger/speed-spend)).

## Clarity Resources

### Developer Tools

- [Clarinet](https://github.com/hirosystems/clarinet) - 打包为 CLI 的 Clarity 运行时，促进 Clarity 智能合约的开发和测试.
- [Clarigen](https://github.com/obylabs/clarigen) - 用于编写与 Clarity 智能合约交互的 TypeScript 代码的工具.
- [clarity.tools](https://clarity.tools) - 浏览器内的 Clarity REPL.
- [search-clarity.dev](https://search-clarity.dev) - 用于搜索已部署的 Clarity 合同的应用程序.

### Libraries

- [uint256](https://github.com/KStasi/clarity-uint256-lib) - 用于将值转换为 256 位的库.
- [clarity-bitcoin](https://github.com/jcnelson/clarity-bitcoin) - 用于验证比特币交易的库.

### Contracts

- [CityCoin](https://github.com/citycoins/citycoin) - PoX lite 的实现，使用 STX 传输使用比例概率铸造新硬币.
- [SWAPR](https://github.com/psq/swapr) - 在 Stacks 2.0 和 Clarity 上类似 Uniswap 的实现.
- [FLEXR](https://github.com/psq/flexr) - Ampleforth for Stacks 的解释.
- [ClarityDAO](https://github.com/friedger/clarity-dao) - Clarity 中 Moloch DAO 的转换.
- [NFT Marketplace](https://github.com/friedger/clarity-marketplace/blob/master/contracts/market.clar) - 可交易资产市场的清晰智能合约.
- [StackStarter](https://github.com/MarvinJanssen/stackstarter/blob/master/contracts/stackstarter.clar) - 众筹的清晰智能合约.
- [Lightning Swaps](https://github.com/radicleart/clarity-rstack/blob/master/contracts/lightning-swaps-v1.clar) - 使用闪电网络进行防欺诈交换.
- [Election Voting](https://github.com/elbaruni/clarity-election/blob/master/contracts/election.clar) - 使用 Clarity 对候选人进行基本投票.
- [DualX](https://github.com/westridgeblockchain/dualX) - 为交易所实施 DeFi 生态系统的 Clarity 合约集合.

### Non-Fungible Tokens

- [Tofauti](https://www.tofauti.net) - 围绕堆栈上的 NFT 收集资源.
- [This is #1](https://www.thisisnumberone.com) - 第一个基于比特币和 Stacks 区块链的专业 NFT（[contract](https://explorer.stacks.co/txid/SP3QSAJQ4EA8WXEDSRRKMZZ29NH91VZ6C5X88FGZQ.thisisnumberone-v2?chain=mainnet)).

### Fungible Tokens

- [Nothing](https://www.nothingtoken.com/) - 一个什么都不做的可替代代币（[contract](https://explorer.stacks.co/txid/0x022bed728d648ff1a68036c40f3aff8136ee22fee18380731df0ab9d76d3c4a9?chain=mainnet)).

### Stacking

- [stacking.club](https://stacking.club) - 堆叠信息和统计数据.
- [Friedger pool](https://pool.friedger.de/) - 不收取任何费用的社区堆叠池.
- [PlanBetter pool](https://planbetter.org/) - 带有比特币奖励的堆叠池.

## App Development

### Frontend Libraries

- [Stacks.js](https://github.com/blockstack/stacks.js) - 用于与 Stacks 区块链交互的 JavaScript 库的 Monorepo.

### CLI

- [@stacks/cli](https://github.com/blockstack/stacks.js/tree/master/packages/cli) - 用于与身份验证、存储和交易交互的命令行界面.

### Storage

- [CompassDB](https://github.com/eder-ai/compass-db) - 用于管理 Gaia 存储中高级收藏的库.
- [lens-file-source](https://gitlab.com/MyLens/lens-file-source) - 通过 Gaia 的缓存、事务和 JSON 映射聚合等机制进行文件存储抽象.
- [GaiaDown](https://github.com/AcidLeroy/gaiadown-ts) - Gaia 存储后端 [LevelUp](https://github.com/Level/levelup).

## Learning Resources

### Documentation

- [Official Stacks documentation](https://docs.stacks.co/) - 用于学习的文档和开发人员教程
  清晰和开发 Stacks 应用程序.
- [Stacks 101](https://stacks101.com) - 社区策划的 STX 知识.

### Videos

- [Clarity 101](https://youtu.be/lXJutQqDq3w) - 了解 Clarity 设计原则的基础知识.
- [Developer Registry 101](https://www.crowdcast.io/e/clarity-program) - 了解如何从头开始构建 Clarity 智能合约.
- [How Clarity Prevents Common Smart Contract Vulnerabilities](https://www.youtube.com/watch?v=VYXhrwPsBws) - Clarity 安全原则的解释.
- [Proof of Transfer Whitepaper Reading with Muneeb Ali](https://www.youtube.com/watch?v=NY_eUrIcWOY&t=3s) - 作者的转移证明 (PoX) 白皮书概述.

## Community

- [Discord](https://discord.gg/zrvWsQC) - 堆栈生态系统不和谐.
- [Twitter](https://twitter.com/stacks) - 堆栈生态系统 Twitter.
- [Official Stacks Forum](https://forum.stacks.org/) - 堆栈社区论坛.
- [r/stacks](https://www.reddit.com/r/stacks) - 堆栈 subreddit.

## Contributing

我们欢迎社区对此列表做出贡献. 请阅读 [contribution guidelines](https://github.com/friedger/awesome-stacks-chain/blob/master/contributing.md) 在贡献之前.
