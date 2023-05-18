<div class="github-widget" data-repo="friedger/awesome-stacks-chain"></div>
## Awesome Stacks[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Stacks](https://raw.githubusercontent.com/friedger/awesome-stacks-chain/master/img/awesome-stacks.png 'Awesome Stacks')](https://www.stacks.co)

[Stacks](https://www.stacks.co/what-is-stacks) 是由比特币锚定的区块链，支持应用程序、智能合约和数字资产.  Stacks是连接比特币的第一层区块链，通过区块链实现智能合约和去中心化应用. [Clarity language](https://clarity-lang.org/) . 通过 [Proof of Transfer (PoX) consensus mechanism](https://docs.stacks.co/understand-stacks/proof-of-transfer) ，Stacks 区块链的状态锚定在比特币区块链上，从而为 Stacks 提供了比特币的安全性和最终性.  Stacks 将其他区块链技术的可编程性带到了比特币上，而无需修改比特币本身的核心共识机制.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!--lint ignore awesome-list-item-->


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
- [Sigle](https://www.sigle.io/) - 去中心化写作平台.
- [Console](https://www.console.xyz/) - 去中心化社区应用.
- [Stacks On Chain](https://stacksonchain.com) - 链数据分析工具.

### Blockchain Name System
- [BNSx](https://www.dots.so/) - 使用一个帐户 (1:n) 管理多个 BNS 名称.
- [btc.us](https://btc.us) - .btc 名称的应用程序.
- [BNS search](https://www.bnssearch.com/) - 搜索注册 BNS 名称的应用程序.
- [BNS and Ordinals](https://www.bns.xyz/) - 将 BNS 写为序数.
- [Owl.link](https://owl.link) - 为 BNS 名称创建链接页面的应用程序.
- [Ryder Handles](https://handles.ryder.id) - 社区的 BNS 名称空间.

### DeFi
- [Alex Lab](https://app.alexlab.co) - DeFi 服务平台.
- [Lydian](https://app.lydian.xyz) - 去中心化的资金管理协议.
- [Arkadiko Protocol](https://github.com/arkadiko-dao/arkadiko) - 基于自还贷款的稳定币（USDA）.
- [Zest Protocol](https://www.zestprotocol.com/)  - 比特币的去中心化借贷. 目前仅在测试网上.

### Games
- [Stacks Degens](https://stacksdegens.com) - 一款通过 NFT 启用复古图形的赛车游戏.
- [Project Indigo](https://www.projectindigonft.com) - An interactive story and RPG experience.

### Stacking Apps
- [Lock Stacks](https://lockstacks.com) - 直接或使用池堆叠 Stacks 令牌的应用程序.
- [Friedger pool](https://pool.friedger.de/) - 免费的社区堆叠池.
- [PlanBetter pool](https://planbetter.org/) - 带有比特币奖励的堆叠池.
- [Xverse pool](https://pool.xverse.app/) - 内置于 Xverse 移动应用程序中的堆叠池.

## Clarity Resources

### Developer Tools

- [Clarinet](https://github.com/hirosystems/clarinet) - 打包为 CLI 的 Clarity 运行时，有助于 Clarity 智能合约的开发和测试.
- [Clariform](https://github.com/njordhov/clariform) - 用于 Clarity 的 Linter 和格式化程序.
- [Clarigen](https://github.com/obylabs/clarigen) - 一种用于编写与 Clarity 智能合约交互的 TypeScript 代码的工具.
- [clarity.tools](https://clarity.tools) - 浏览器内 Clarity REPL.
- [ClarityGPT Prompt](https://claritygpt.com/) - 使用聊天机器人编写智能合约.
- [Hiro Platform](https://platform.hiro.so/) - 浏览器内 IDE.
### Example Contracts
- [Source of Clarity](https://source-of-clarity.com) - 在主网上列出所有已部署的 Clarity 合约并附上一些评论.
- [Example Contracts](https://github.com/hirosystems/clarity-examples) - 示例智能合约的集合，可作为编写您自己的智能合约的起点.
- [Audited Example Smart Contracts](https://github.com/clarity-lang/book/tree/main/projects) - 另一个智能合约示例集合，这些已经过安全审计.

### Libraries

- [uint256](https://github.com/KStasi/clarity-uint256-lib) - 将值转换为 256 位的库.
- [clarity-bitcoin](https://github.com/friedger/clarity-bitcoin) - 验证比特币交易的图书馆.

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
- [ExecutorDAO](https://github.com/MarvinJanssen/executor-dao) - 用于将 DAO 功能构建到您的智能合约中的 Clarity 框架.
- [Digital Will](https://github.com/LoRdSoban/Cryptonomers) - 有条件的资金转移.
### Non-Fungible Tokens

- [Tofauti](https://www.tofauti.net) - 在 Stacks 上收集有关 NFT 的资源.
- [This is #1](https://www.thisisnumberone.com) - 第一个建立在比特币和 Stacks 区块链上的专业 NFT（[contract](https://explorer.stacks.co/txid/SP3QSAJQ4EA8WXEDSRRKMZZ29NH91VZ6C5X88FGZQ.thisisnumberone-v2?chain=mainnet)).

### Fungible Tokens

- [Nothing](https://www.nothingtoken.com/) - 什么都不做的可替代令牌（[contract](https://explorer.stacks.co/txid/0x022bed728d648ff1a68036c40f3aff8136ee22fee18380731df0ab9d76d3c4a9?chain=mainnet)).

### Stacking
- [Stacking Pools](https://github.com/friedger/clarity-stacking-pools) - 用于堆叠池的 PoX 包装合约.

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

### Indexing and Querying APIs
- [Stacks API](https://www.hiro.so/stacks-api) - 托管 API 可直接与区块链交互以查询信息、广播交易并在 Stacks 上扩展您的项目.
- [Quicknode](https://www.quicknode.com/chains/stx) - 托管 ednpoint 使用 Quicknode 快速轻松地连接到 Stacks.
- [Self-Hosted Render](https://github.com/stacksfoundation/render-stacks) - 一键式部署工具可在 Render 上自行托管 Stacks 节点.
- [Self-Hosted Digital Ocean](https://marketplace.digitalocean.com/apps/stacks-blockchain) - 用于运行 Stacks 节点的 Digital Ocean droplet.
- [Self-Hosted Docker](https://github.com/stacks-network/stacks-blockchain-docker) - 使用 Docker 运行自托管 Stacks 节点的工具.

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
- [Web3 for Bitcoin](https://www.crowdcast.io/e/web3-for-bitcoin/) - 堆栈概述，它解决的问题，它如何为比特币带来智能合约功能，以及如何开始构建它.
- [Why Build on Stacks](https://www.youtube.com/watch?v=WaTMCremGwE) - 概述为什么 web3 开发人员可能希望在 Stacks 上构建其他区块链协议.

### Written Tutorials

- [Built on Bitcoin: An Introduction to Full-Stack Web3 Development with Stacks](https://dev.to/stacks/built-on-bitcoin-an-introduction-to-full-stack-web3-development-with-stacks-me9) - 使用 Stacks 构建全栈应用程序的高级概述.
- [Understanding Stacks Post Conditions](https://dev.to/stacks/understanding-stacks-post-conditions-e65) - 理解和使用堆栈中的后置条件的指南.
- [Test-Driven Stacks Development with Clarinet](https://dev.to/stacks/test-driven-stacks-development-with-clarinet-2e4i) - 展示如何使用 Clarinet 进行测试和 TDD 的教程.
- [Build a DEX with Stacks](https://www.pointer.gg/tutorials/build-a-dex-with-stacks/56abb3a4-05c1-4608-b096-f82189e9f759) - 广泛介绍如何通过构建全栈去中心化交易所来使用 Stacks.
- [Build a Stacks app with Remix](https://micro-stacks.dev/guides/with-remix) - 如何使用 Remix JS 框架和 Micro-Stacks 创建服务器端呈现的 Stacks 应用程序.
- [Build a Stacks app with Next.js](https://micro-stacks.dev/guides/with-nextjs) - 类似于上面的 Remix 教程，这个使用 Next.js 和 Micro-Stacks.
- [Creating a Voting Contract](https://www.clearness.dev/01-voting-clarity-smart-contract/01-getting-started) - 一个由多个部分组成的系列，展示了如何使用 Clarity 创建一个简单的投票智能合约.
- [Building an NFT with Stacks and Clarity](https://blog.developerdao.com/building-an-nft-with-stacks-and-clarity) - 利用 SIP-009 标准使用 Clarity 创建 NFT.
- [Order Book Contract Walkthrough](https://byzantion.hiro.so/) - 使用 Clarity 构建的订单簿智能合约演练.
- [NFT Tutorial](https://docs.hiro.so/tutorials/clarity-nft) - 用 Clarity 创建一个 NFT.

### Books

- [Clarity of Mind](https://book.clarity-lang.org/) - 编写可预测的高效智能合约. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

### Courses

- [Clarity Universe](https://clarity-lang.org/universe) - 全面的 Clarity 开发课程，既可以作为自定进度的课程提供，也可以作为为期 6 周的指导课程提供.

## Community

- [Discord](https://discord.gg/zrvWsQC) - 堆叠生态系统 Discord.
- [Twitter](https://twitter.com/stacks) - 堆栈生态系统推特.
- [YouTube](https://www.youtube.com/c/Blockstack) - 堆栈生态系统 YouTube.
- [Official Stacks Forum](https://forum.stacks.org/) - 堆栈社区论坛.
- [r/stacks](https://www.reddit.com/r/stacks) - 堆栈 subreddit.

## Contributing

我们欢迎社区对此列表做出贡献. 请阅读 [contribution guidelines](https://github.com/friedger/awesome-stacks-chain/blob/master/contributing.md) 在贡献之前.
