<div class="github-widget" data-repo="cosmos/awesome-cosmos"></div>
<!--lint disable double-link-->
## Awesome Cosmos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 社区精选的与 Cosmos 生态系统相关的精彩项目列表

Cosmos SDK 是一个用于在 Go 中构建区块链应用程序的模块化框架.
Gaia 是 Cosmos Hub 的实现，是使用 Cosmos SDK 构建的.

**Contributing:**
请阅读 [Contributing guide](https://github.com/cosmos/awesome-cosmos/blob/master/./CONTRIBUTING.md) . 感谢我们所有人 [contributors](https://github.com/cosmos/awesome/graphs/contributors).

**免责声明：这个社区维护的存储库并不反映任何官方实体的观点.**



## Core Components

* [Cosmos Hub](https://github.com/cosmos/gaia)
<!-- -->
* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/)
* [IBC Go](https://github.com/cosmos/ibc-go)
* [CometBFT](https://github.com/cometbft/cometbft)
* [CosmWasm](https://github.com/CosmWasm/cosmwasm)
* [CosmJS](https://github.com/cosmos/cosmjs)
<!-- -->
* [Protobuf](https://buf.build/cosmos)
* [IAVL](https://github.com/cosmos/iavl)
* [ICS23](https://github.com/cosmos/ics23)

## Documentation

* [Cosmos Developer Portal](https://tutorials.cosmos.network)
* [Cosmos SDK](https://docs.cosmos.network/)
* [IBC](https://ibc.cosmos.com/)
* [CometBFT](https://docs.cometbft.com/)
* [Cosmos Hub](https://hub.cosmos.network/)
* [CosmWasm](https://docs.cosmwasm.com/docs/1.0/)
* [Cosmology](https://cosmology.tech/learn)

## Client Libraries

### Go

* [Ignite CLI](https://github.com/ignite/cli)  - 用于在主权且安全的区块链上构建、启动和维护任何加密应用程序的一体化平台. 通过 UI 快速引导新的 Cosmos SDK 区块链并支持创建新模块并方便地与现有 Cosmos SDK 模块配合使用.

### JavaScript

* [cosmos/cosmjs](https://github.com/cosmos/cosmjs) - Cosmos JavaScript 库.
* [telescope](https://github.com/osmosis-labs/telescope) - 基于 CosmJS 构建的 Typescript 库生成器.
* [chainapsis/cosmosjs](https://github.com/chainapsis/cosmosjs) - Chainapsis 签名和 API 库.
* [cosmos-client/cosmos-client-ts](https://github.com/cosmos-client/cosmos-client-ts) - Cosmos SDK 区块链的 JavaScript / TypeScript 客户端.
* [cosmos/sig](https://github.com/cosmos/sig) - Cosmos 签名库.
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) - 官方 Cosmos 链注册表的 npm 包.
* [strangelove-ventures/graz](https://github.com/strangelove-ventures/graz) - 与钱包、签名者、签名客户端等交互的 React hook 集合.
* [cosmology-tech/create-cosmos-app](https://github.com/cosmology-tech/create-cosmos-app) - 用于引导 Cosmos Web UI 的 npm 包.
* [cosmology-tech/cosmos-kit](https://github.com/cosmology-tech/cosmos-kit) - Cosmos 的钱包连接器.

### Python

* [cosmpy](https://github.com/fetchai/cosmpy) - 基于 Cosmos SDK 的用于与区块链交互的 Python 客户端库.
* [pyCosmicWrap](https://github.com/ChihuahuaChain/pyCosmicWrap/) - Cosmos API/RPC 的 python3 包装器.
* [mospy](https://github.com/ctrl-Felix/mospy) - 一个 Python 库，用于为基于 Cosmos SDK 的硬币创建和签署交易.
* [cosmospy-protobuf](https://github.com/ctrl-Felix/cosmospy-protobuf) - 包含所有已编译的 protobuf 文件的 Python 库（对于 grpc 非常有用）.

### Rust

* [CosmWasm/cosmwasm](https://github.com/CosmWasm/cosmwasm) - Cosmos SDK 的 WebAssembly 智能合约.
* [iqlusioninc/stdtx](https://github.com/iqlusioninc/crates) - 来自 iqlusion 的开源 Rust 箱的集合.
* [peggyjv/ocular](https://github.com/peggyjv/ocular) - Cosmos SDK 链的客户端库，专注于愉悦的用户体验.

## Block Explorers

* [ATOMScan](https://atomscan.com)
* [Big Dipper](https://bigdipper.live) - [Source](https://github.com/forbole/big-dipper-2.0-cosmos)
* [IOBScan](https://ibc.iobscan.io/)
* [Mintscan](https://www.mintscan.io)
    * [Mintscan for Cosmos Hub Testnet](https://cosmoshub-testnet.mintscan.io/cosmoshub-testnet)
* [NG Explorers](https://explorers.guru/)
* [Ping.pub](https://ping.pub) - [Source](https://github.com/ping-pub/explorer)
* [Stake ID](https://stake.id)

### Visual Block Explorers

查看区块链间通信 (IBC) 传输活动. 该地图跟踪不同区块链（在 Cosmos Hub 中称为区域）之间的 IBC 交易，以显示有关整个 Cosmos 生态系统脉搏的准确聚合信息.

* [Map of Zones](https://mapofzones.com/?period=24) - [Source](https://github.com/mapofzones)
* [Mintscan](https://hub.mintscan.io) - Cosmostation 的跨链浏览器.

### Terminal Block Explorers

通过终端探索 Cosmos SDK 区块链.

* [gex](https://github.com/cosmos/gex) - GEX 终端浏览器.
* [cshtop](https://github.com/gsk967/cshtop) - Cosmos htop ，在终端上阻止可视化工具.
* [pvtop](https://github.com/blockpane/pvtop) - 终端上的共识可视化工具.

## Chain Registry

包含来自大多数 Cosmos 链的标准化元数据的注册表.

* [cosmos/chain-registry](https://github.com/cosmos/chain-registry/)
* [Cosmos Directory](https://cosmos.directory) - [Source](https://github.com/eco-stake/cosmos-directory)
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) - 官方 Cosmos 链注册表的 npm 包.

## Validators

流行的区块浏览器提供了活跃验证者的列表. 查看验证器配置文件的最简单入口点是来自区块浏览器：

* [List on Mintscan](https://www.mintscan.io/cosmos/validators)
* [List on ATOMScan](https://atomscan.com/validators)
* [List on BigDipper](https://cosmos.bigdipper.live/validators)
* [List on Kujira POD](https://pod.kujira.app/cosmoshub-4)

选择验证器时的 DYOR. 考虑将您的代币委托给前 20 名之外的验证者，以提高网络的去中心化程度.
这也是避免 0% 佣金验证器和交易所验证器的好做法.

## Cosmos SDK Modules

查找 Cosmos SDK 模块的准确列表的最佳位置是项目存储库：

* 有关生产级模块的列表，请参阅 [List of Modules](https://docs.cosmos.network/main/modules/).
* 知名第三方模块列表，请参见 [Ecosystem section](https://docs.cosmos.network/main/ecosystem) Cosmos SDK 文档. 

有些模块很重要，但可能仍然缺乏官方文档，例如 [genutil](https://github.com/cosmos/cosmos-sdk/tree/main/x/genutil) 启动链所必需的模块. 请考虑向 Cosmos SDK 贡献文档，以帮助填补这些空白.

要共享您希望社区了解和使用的模块，请将其添加到此处. 您还可以创建拉取请求（PR）以将模块添加到官方项目中.

## Monitoring

* [PANIC Monitoring and Alerting For Blockchains](https://github.com/SimplyVC/panic) - 适用于 Cosmos SDK、Substrate 和 Chainlink 节点的开源监控和警报解决方案.
* [Prometheus Exporter](https://github.com/node-a-team/Cosmos-IE) - Cosmos SDK 的集成 Prometheus 导出器.
* [Cosmos Chains Dashboard](https://github.com/zhangyelong/cosmos-dashboard) - Grafana 仪表板，用于监控 Cosmos SDK 和基于 Tendermint 的区块链节点.
* [cosmos-exporter](https://github.com/solarlabsteam/cosmos-exporter) - 一个 Prometheus 抓取工具，通过 gRPC 从基于 Cosmos 的区块链的完整节点获取数据.
* [Chain Pulse](https://github.com/informalsystems/chainpulse) - 使用 Prometheus 导出器监控中继 IBC 数据包.
* [missed-blocks-checker](https://github.com/solarlabsteam/missed-blocks-checker) - 监控 Cosmos 链验证器的丢失区块，支持向 Telegram 和 Slack 发送通知.
* [Nodes Checker](https://t.me/NodesGuru_bot) - 在线检查您的节点状态，如果您的验证器节点出现问题，会收到即时通知.
* [Cosmon](https://github.com/iqlusioninc/cosmon) - 适用于 Cosmos 和其他 Tendermint 应用程序的可观察性工具.
* [Tenderduty](https://github.com/blockpane/tenderduty)  - Tendermint 链的综合监控工具. 它的主要功能是在验证者丢失区块等情况时向验证者发出警报.
* [UpgradesWatchdog](https://github.com/ChihuahuaChain/UpgradesWatchdog) - SoftwareUpgradeProposal &amp; GitHub 发布电报监控工具.
* [cosmos-node-exporter](https://github.com/QuokkaStake/cosmos-node-exporter.git) - Prometheus 导出器，用于抓取有关节点同步状态、Cosmovisor 升级和 GitHub 版本不匹配的数据，对于节点操作员和验证器非常有用.
* [cosmos-wallets-exporter](https://github.com/QuokkaStake/cosmos-wallets-exporter.git) - 一个 Prometheus 导出器，用于抓取钱包余额数据，如果您的钱包余额太低，可以收到通知.
* [cosmos-validators-exporter](https://github.com/QuokkaStake/cosmos-validators-exporter.git) - 一个 Prometheus 导出器，用于抓取有关验证者的数据（错过的区块、委托人数量、总质押金额、排名等）


## Indexers

* [Cosmscan](https://github.com/cosmscan/cosmscan-go) - Cosmos 链的索引器引擎.
* [interchain-indexer](https://github.com/Reecepbcups/interchain-indexer) - Python 中的 Cosmos 区块链索引器.

## Frameworks

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) - 用 Go 构建高价值公共区块链的框架.
* [Orga](https://github.com/nomic-io/orga) - Rust 中状态机转换的 ABCI 框架.
* [CosmosSwift](https://github.com/CosmosSwift) - 基于 Tendermint 共识在 Swift 中构建区块链应用程序.
* [ABCI-RS](https://github.com/devashishdxt/abci-rs) - 用于创建 ABCI 应用程序的 Rust 箱.
* [CosmRS](https://github.com/cosmos/cosmos-rust/tree/main/cosmrs) - 在 Rust 中构建 Cosmos 区块链应用程序的框架.

## Virtual Machines

在 Cosmos SDK 中运行的虚拟机的模块或框架

* [Agoric SDK](https://github.com/Agoric/agoric-sdk) - Agoric JavaScript 智能合约平台.
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) - WASM 虚拟机和 Rust 智能合约.
* [Ethermint](https://github.com/evmos/ethermint) - Ethereum Virtual Machine.

## IBC

* [IBCprotocol.dev](https://ibcprotocol.dev/) - IBC 协议网站.
* [Interchain Standards](https://github.com/cosmos/ibc/) - Cosmos 网络和链间生态系统的链间标准 (ICS).
* [cosmos/ibc-go](https://github.com/cosmos/ibc-go) - Go 中的区块链间通信协议（IBC）实现.
* [cosmos/ibc-rs](https://github.com/cosmos/ibc-rs) - 区块链间通信（IBC）协议的 Rust 实现.
* [interchaintest](https://github.com/strangelove-ventures/interchaintest) - IBC 链的端到端测试框架.
* [cosmos/relayer](https://github.com/cosmos/relayer) - Go 中的 IBC 中继器.
* [informalsystems/hermes](https://github.com/informalsystems/hermes) - Rust 中的 IBC 中继器.
* [confio/ts-relayer](https://github.com/confio/ts-relayer) - TypeScript 中的 IBC 中继器.
* [local-interchain](https://github.com/Reecepbcups/local-interchain) - 在任何操作系统上快速启动本地 IBC 开发环境.

## Testing

* [interchaintest](https://github.com/strangelove-ventures/interchaintest) - IBC 链的端到端测试框架.
* [atomkraft](https://github.com/informalsystems/atomkraft-cosmos) - Cosmos SDK区块链端到端测试框架.
* [python-iavl](https://github.com/crypto-com/python-iavl) - 用 Python 实现的 IAVL 检查工具.
* [cosmos-sdk-codeql](https://github.com/crypto-com/cosmos-sdk-codeql) - CodeQL 查询常见的 Cosmos SDK 错误.
* [tm-load-test](https://github.com/informalsystems/tm-load-test) - CometBFT 负载测试应用程序.
* [cosmosloadtester](https://github.com/orijtech/cosmosloadtester) - Cosmos SDK 区块链的负载测试器.

## Tools

### CLI

* [iqlusioninc/tmkms](https://github.com/iqlusioninc/tmkms) - Tendermint 验证器的密钥管理系统.
* [cosmosvisor](https://github.com/cosmos/cosmos-sdk/tree/main/cosmovisor#readme) - 自动执行 Cosmos SDK 应用程序二进制升级.
* [cosmosvanity](https://github.com/hukkinj1/cosmosvanity) - 用于生成 Cosmos 虚荣地址的 CLI 工具.
* [findaccount](https://github.com/blockpane/findaccount) - 帮助识别帐户是否存在于具有相同地址的多个 Cosmos 链上.
* [lens](https://github.com/strangelove-ventures/lens) - CLI 工具可与任何支持核心 Cosmos-SDK 模块的 Cosmos 链进行交互.
* [cosmology](https://github.com/cosmology-tech/cosmology) - 用于进行加密货币交易、加入流动性池以及在 Osmosis 上进行权益奖励的 CLI 工具.
* [multisig](https://github.com/informalsystems/multisig) - 用于管理 Cosmos SDK 链上多重签名帐户的 CLI 工具.
* [cosmos-genesis-tinkerer](https://github.com/hyphacoop/cosmos-genesis-tinkerer) - 用于修改 Cosmos 创世文件的 CLI 工具.
* [airdrop-tools](https://github.com/Reecepbcups/airdrop-tools) - CLI 脚本可帮助分发多种格式的各种令牌.

### GUI

* [Cosmos Hub Multisig Manager](https://cosmos-multisig-ui-kohl.vercel.app) - 在 Cosmos Hub 上创建多重签名和多重签名交易（[source](https://github.com/cosmos/cosmos-multisig-ui)).
* [REStake](https://restake.app) - 使用 Authz 的 Cosmos 区块链自动复合应用程序（[source](https://github.com/eco-stake/restake)).
* [Yieldmos](https://yieldmos.com) - 使用 Authz 进行质押和 LP 奖励自动复合.
* [Cosmfaucet](https://github.com/scalalang2/cosmfaucet) - 基于 Cosmos 的区块链的自托管水龙头服务.
* [Cosmos Notifier](https://cosmos-notifier.decrypto.online) - Telegram 和 Discord 的治理通知工具（[source](https://github.com/shifty11/cosmos-notifier)).
* [IBC Anywhere](https://ibc.reece.sh/) - IBC 代币传输，包括多链跳跃.

### Bots

* [Cosmos Discord Faucet](https://github.com/0x4139/cosmos-discord-faucet) - 用于 Cosmos SDK 区块链的可配置 Discord 水龙头.
* [Cosmos Discord Bot](https://github.com/okp4/discord-bot) - 用于 Cosmos SDK 区块链的通用 Discord 机器人.
* [cosmos-proposals-checker](https://github.com/QuokkaStake/cosmos-proposals-checker.git) - 如果您的钱包没有对多个 Cosmos SDK 链上的提案进行投票，机器人会通知您.
* [cosmos-transactions-bot](https://github.com/QuokkaStake/cosmos-transactions-bot.git) - 获取有关在多个 Cosmos SDK 链上与您想要的过滤器匹配的交易的通知.
* [cosmos-balance-bot](https://github.com/Reecepbcups/cosmos-balance-bot) - 按设定的时间间隔获取有关多个 Cosmos SDK 链上的钱包余额的通知.
* [validator-stats-notifications](https://github.com/Reecepbcups/validator-stats-notifs) - 不和谐公告，包括排名、一段时间内的授权以及独特的授权人.
* [Secret Stashh NFT Bot](https://github.com/Reecepbcups/stashh-bot) - 一个 Discord 机器人，用于获取 Secret Network NFT 系列的销售、拍卖和购买通知.
* [DAODAO Treasury Bot](https://github.com/Reecepbcups/dao-treasury-bot) - 一个不和谐的机器人，可以跟上 DAO 的国库法币价值.
* [Cosmos Price Bot](https://github.com/Reecepbcups/cosmos-price-bot) - 一个不和谐的机器人，通过 DEX 为任何 Cosmos 代币的美元价格起昵称.

## Node Operations

### Utilities

* [Cosmos Cache](https://github.com/Reecepbcups/cosmos-endpoint-cache) - 通过缓存预定义时间集（正则表达式）的响应来优化 Cosmos 查询.

## Ecosystem

使用 Cosmos SDK 构建的最新项目列表可以在 [Cosmos Directory](https://cosmos.directory).

## Wallets

支持 Cosmos 链的钱包列表是<https://cosmos.network/ecosystem/wallets> .

## Blogs

**免责声明：这个社区维护的存储库并不反映任何官方实体的观点.**

随着生态系统的发展，内容也在不断发展.  DYOR 并关注您感兴趣的项目.

* [What is Cosmos?](https://cosmos.network/intro/)
* [Cosmos Blog](https://blog.cosmos.network/)
* [Interchain Foundation Blog](https://interchain-io.medium.com)

### Articles

* [Cosmos Dev Series: Cosmos Blockchain Upgrade](https://zerofruit.medium.com/cosmos-dev-series-cosmos-sdk-based-blockchain-upgrade-b5e99181554c)
* [Hardening guides](https://cyber.orijtech.com/cosmos/hardening/)
* [How to connect your frontend to Cosmos blockchain](https://dev.to/kikiding/how-to-connect-your-frontend-to-cosmos-blockchain-5fcn)
* [(Not So) Smart Cosmos, examples of common Cosmos app vulnerabilities](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cosmos)

## Related

* [Awesome CosmWasm](https://github.com/InterWasm/cw-awesome)
* [Awesome Crypto.com Chain](https://github.com/crypto-org-chain/awesome)
* [Awesome Evmos](https://github.com/evmos/awesome)
* [Awesome Osmosis](https://github.com/osmosis-labs/awesome)
