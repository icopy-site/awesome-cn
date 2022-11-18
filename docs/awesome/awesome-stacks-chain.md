<div class="github-widget" data-repo="friedger/awesome-stacks-chain"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Stacks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Stacks](https://raw.githubusercontent.com/friedger/awesome-stacks-chain/master/img/awesome-stacks.png 'Awesome Stacks')](https://www.stacks.co)

[Stacks](https://www.stacks.co/what-is-stacks) 是由比特币锚定的区块链，支持应用程序、智能合约和数字资产.  Stacks是连接比特币的第一层区块链，通过区块链实现智能合约和去中心化应用. [Clarity language](https://clarity-lang.org/) . 通过 [Proof of Transfer (PoX) consensus mechanism](https://docs.stacks.co/understand-stacks/proof-of-transfer) ，Stacks 区块链的状态锚定在比特币区块链上，从而为 Stacks 提供了比特币的安全性和最终性.  Stacks 将其他区块链技术的可编程性带到了比特币上，而无需修改比特币本身的核心共识机制.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Apps

### Wallets

- [Stacks Wallet for Desktop](https://www.hiro.so/wallet/install-desktop) - 用于管理 STX 和单独或在池中堆叠的桌面钱包应用程序.
- [Stacks Wallet for Web](https://www.hiro.so/wallet/install-web) - 用于连接 Stacks 网络应用程序的网络钱包.
- [Xverse Wallet](https://www.secretkeylabs.com/) - 用于管理 STX 和堆叠的移动钱包应用程序（非开源）.

### Stacks Web Applications

- [Stacks Explorer](https://explorer.stacks.co/?chain=mainnet) - 用于审查 Stacks 区块链上的交易的应用程序.
- [Boom.money](https://boom.money) - 专注于 NFT 和自定义令牌的网络钱包.
- [Send Many](https://sendstx.com) - 在一次交易中将 STX 发送给多个收件人的应用程序.
- [MIA Block explorer](http://miamining.com) - 一个网络应用程序，用于为所有和个人账户排除 MIA 硬币交易.
- [Speed Spend](https://speed-spend.org) - 一套在测试网上运行的 Clarity 实验（[source](https://github.com/friedger/speed-spend)).

### Blockchain Name System
- [btc.us](https://btc.us) - .btc 名称的应用程序.
- [stx.name](https://stx.name) - BNS名称注册申请（非开源）.
- [BNS search](https://www.bnssearch.com/) - 搜索注册 BNS 名称的应用程序.
- [BNS transfer](https://www.bnstransfer.com) - 转移 BNS 名称的应用程序.
- [Owl.link](https://owl.link) - 为 BNS 名称创建链接页面的应用程序.

### DeFi
- [Alex Lab](https://app.alexlab.co) - DeFi 服务平台.
- [Lydian](https://app.lydian.xyz) - 去中心化的资金管理协议.
- [Arkadiko Protocol](https://github.com/arkadiko-dao/arkadiko) - 基于自还贷款的稳定币（USDA）.

## Clarity Resources

### Developer Tools

- [Clarinet](https://github.com/hirosystems/clarinet) - 打包为 CLI 的 Clarity 运行时，有助于 Clarity 智能合约的开发和测试.
- [Clarigen](https://github.com/obylabs/clarigen) - 一种用于编写与 Clarity 智能合约交互的 TypeScript 代码的工具.
- [clarity.tools](https://clarity.tools) - 浏览器内 Clarity REPL.
- [Source of Clarity](https://source-of-clarity.com) - 在主网上列出所有已部署的 Clarity 合约并附上一些评论.

### Libraries

- [uint256](https://github.com/KStasi/clarity-uint256-lib) - 将值转换为 256 位的库.
- [clarity-bitcoin](https://github.com/jcnelson/clarity-bitcoin) - 验证比特币交易的图书馆.

### Contracts

- [CityCoin](https://github.com/citycoins/citycoin) - 使用 STX 传输的 PoX lite 实现，以使用比例概率铸造新硬币.
- [SWAPR](https://github.com/psq/swapr) - 在 Stacks 2.0 和 Clarity 上类似 Uniswap 的实现.
- [FLEXR](https://github.com/psq/flexr) - Ampleforth for Stacks 的解释.
- [ClarityDAO](https://github.com/friedger/clarity-dao) - Clarity 中 Moloch DAO 的转换.
- [NFT Marketplace](https://github.com/friedger/clarity-marketplace/blob/master/contracts/market.clar) - 可交易资产市场的清晰智能合约.
- [StackStarter](https://github.com/MarvinJanssen/stackstarter/blob/master/contracts/stackstarter.clar) - 清晰的众筹智能合约.
- [Lightning Swaps](https://github.com/radicleart/clarity-rstack/blob/master/contracts/lightning-swaps-v1.clar) - 使用闪电网络的防欺诈交换.
- [Election Voting](https://github.com/elbaruni/clarity-election/blob/master/contracts/election.clar) - 使用 Clarity 对候选人进行基本投票.
- [DualX](https://github.com/westridgeblockchain/dualX) - 为交易所实施 DeFi 生态系统的 Clarity 合约集合.

### Non-Fungible Tokens

- [Tofauti](https://www.tofauti.net) - 在 Stacks 上收集有关 NFT 的资源.
- [This is #1](https://www.thisisnumberone.com) - 第一个建立在比特币和 Stacks 区块链上的专业 NFT（[contract](https://explorer.stacks.co/txid/SP3QSAJQ4EA8WXEDSRRKMZZ29NH91VZ6C5X88FGZQ.thisisnumberone-v2?chain=mainnet)).

### Fungible Tokens

- [Nothing](https://www.nothingtoken.com/) - 什么都不做的可替代令牌（[contract](https://explorer.stacks.co/txid/0x022bed728d648ff1a68036c40f3aff8136ee22fee18380731df0ab9d76d3c4a9?chain=mainnet)).

### Stacking

- [stacking.club](https://stacking.club) - 堆叠信息和统计数据.
- [Friedger pool](https://pool.friedger.de/) - 免费的社区堆叠池.
- [PlanBetter pool](https://planbetter.org/) - 带有比特币奖励的堆叠池.

## App Development

### Frontend Libraries

- [Stacks.js](https://github.com/hirosystems/stacks.js) - 用于与 Stacks 区块链交互的 JavaScript 库的 Monorepo.
- [micro-stacks](https://github.com/fungible-systems/micro-stacks/) - 用于与 Stacks 区块链交互的 JavaScript 库的 Monorepo.

### CLI

- [@stacks/cli](https://github.com/hirosystems/stacks.js/tree/master/packages/cli) - 用于与身份验证、存储和事务交互的命令行界面.

### Storage

- [CompassDB](https://github.com/eder-ai/compass-db) - 用于管理 Gaia 存储中的高级集合的库.
- [lens-file-source](https://gitlab.com/MyLens/lens-file-source) - 通过缓存、事务和 Gaia 的 JSON 映射聚合等机制进行文件存储抽象.
- [GaiaDown](https://github.com/AcidLeroy/gaiadown-ts) - 盖亚存储后端 [LevelUp](https://github.com/Level/levelup).

## Learning Resources

### Documentation

- [Official Stacks documentation](https://docs.stacks.co/) - 用于学习的文档和开发人员教程
  清晰度和开发 Stacks 应用程序.
- [Hiro documentation](https://docs.hiro.so/) - 专注于开发人员的文档.
- [Stacks 101](https://stacks101.com) - 社区策划的 STX 知识.

### Videos

- [Clarity 101](https://youtu.be/lXJutQqDq3w) - 了解 Clarity 设计原则的基础知识.
- [Developer Registry 101](https://www.crowdcast.io/e/clarity-program) - 了解如何从头开始构建 Clarity 智能合约.
- [How Clarity Prevents Common Smart Contract Vulnerabilities](https://www.youtube.com/watch?v=VYXhrwPsBws) - Clarity 安全原则的解释.
- [Proof of Transfer Whitepaper Reading with Muneeb Ali](https://www.youtube.com/watch?v=NY_eUrIcWOY&t=3s) - 作者的传输证明 (PoX) 白皮书概述.

### Books

- [Clarity of Mind](https://book.clarity-lang.org/) - 编写可预测的高效智能合约. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) （提前预览）

## Community

- [Discord](https://discord.gg/zrvWsQC) - 堆叠生态系统 Discord.
- [Twitter](https://twitter.com/stacks) - 堆栈生态系统推特.
- [Official Stacks Forum](https://forum.stacks.org/) - 堆栈社区论坛.
- [r/stacks](https://www.reddit.com/r/stacks) - 堆栈 subreddit.

## Contributing

我们欢迎社区对此列表做出贡献. 请阅读 [contribution guidelines](https://github.com/friedger/awesome-stacks-chain/blob/master/contributing.md) 在贡献之前.
