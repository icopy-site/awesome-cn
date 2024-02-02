<div class="github-widget" data-repo="cosmos/awesome-cosmos"></div>
<!--lint disable double-link-->
## Awesome Cosmos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A community curated list of awesome projects related to the Cosmos ecosystem

The Cosmos SDK is a modular framework for building blockchain applications in Go.
Gaia, the implementation of the Cosmos Hub, is built with the Cosmos SDK.

**Contributing:**
Please read the [Contributing guide](https://github.com/cosmos/awesome-cosmos/blob/master/./CONTRIBUTING.md). Thank you to all our [contributors](https://github.com/cosmos/awesome/graphs/contributors).

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**



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
* [Interchain Developer Academy](https://ida.interchain.io/)
* [Cosmos SDK](https://docs.cosmos.network/)
* [IBC](https://ibc.cosmos.com/)
* [CometBFT](https://docs.cometbft.com/)
* [Cosmos Hub](https://hub.cosmos.network/)
* [CosmWasm](https://docs.cosmwasm.com/docs/1.0/)
* [Cosmology](https://cosmology.tech/learn)

## Client Libraries

### Go

* [Ignite CLI](https://github.com/ignite/cli) - All-in-one platform to build, launch, and maintain any crypto application on a sovereign and secured blockchain. Quickly bootstraps a new Cosmos SDK blockchain with UI and support to create new and work conveniently with existing Cosmos SDK modules.

### JavaScript

* [cosmos/cosmjs](https://github.com/cosmos/cosmjs) - The Cosmos JavaScript library.
* [telescope](https://github.com/osmosis-labs/telescope) - Typescript library generator built on top of CosmJS.
* [chainapsis/cosmosjs](https://github.com/chainapsis/cosmosjs) - Chainapsis Signing & API Library.
* [cosmos-client/cosmos-client-ts](https://github.com/cosmos-client/cosmos-client-ts) - JavaScript / TypeScript client for Cosmos SDK blockchains.
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) - A npm package for the official Cosmos Chain Registry.
* [strangelove-ventures/graz](https://github.com/strangelove-ventures/graz) - Collection of React hooks to interact with wallets, signers, signing clients, etc.
* [cosmology-tech/create-cosmos-app](https://github.com/cosmology-tech/create-cosmos-app) - A npm package to bootstrap a Cosmos Web UI.
* [cosmology-tech/cosmos-kit](https://github.com/cosmology-tech/cosmos-kit) - A wallet connector for the Cosmos.
* [nabla-studio/quirks](https://github.com/nabla-studio/quirks) - A universal wallet adapter for your Cosmos dApps, that works on both mobile and browser.
* [toschdev/bip44](https://github.com/toschdev/cosmos-bip44) - Cosmos BIP44 implementation in JavaScript for development and education learning.

### Python

* [cosmpy](https://github.com/fetchai/cosmpy) - A Python client library for interacting with blockchains based on the Cosmos SDK.
* [pyCosmicWrap](https://github.com/ChihuahuaChain/pyCosmicWrap/) - A python3 wrapper around Cosmos API/RPC.
* [mospy](https://github.com/ctrl-Felix/mospy) - A Python library to create and sign transactions for Cosmos SDK based coins.
* [cosmospy-protobuf](https://github.com/ctrl-Felix/cosmospy-protobuf) - A Python library containing all compiled protobuf files (works very good for grpc).
* [fx-py-sdk](https://github.com/functionx/fx-py-sdk) - The Cosmos Python client library.

### Rust

* [CosmWasm/cosmwasm](https://github.com/CosmWasm/cosmwasm) - WebAssembly Smart Contracts for the Cosmos SDK.
* [iqlusioninc/stdtx](https://github.com/iqlusioninc/crates) - A collection of open source Rust crates from iqlusion.
* [peggyjv/ocular](https://github.com/peggyjv/ocular) - A client library for Cosmos SDK chains focusing on pleasant UX.

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

View Inter-Blockchain Communication (IBC) transfer activity. The map traces IBC transactions between different blockchains (called zones in the Cosmos Hub) to display accurate aggregate information about the pulse of the entire Cosmos ecosystem.

* [Map of Zones](https://mapofzones.com/?period=24) - [Source](https://github.com/mapofzones)
* [Mintscan](https://hub.mintscan.io) - Interchain Explorer by Cosmostation.

### Terminal Block Explorers

Explore Cosmos SDK blockchains via a terminal.

* [gex](https://github.com/cosmos/gex) - GEX In-Terminal Explorer.
* [cshtop](https://github.com/gsk967/cshtop) - Cosmos htop , Blocks visualizer on terminal.
* [pvtop](https://github.com/blockpane/pvtop) - Consensus visualizer on terminal.
* [tmtop](https://github.com/quokkastake/tmtop) - Htop-like visualiser of consensus inspired by pvtop that allows showing upgrade info, working with consumer chains and non-Cosmos chains and way more.

## Chain Registry

A registry containing standardized metadata from most Cosmos chains.

* [cosmos/chain-registry](https://github.com/cosmos/chain-registry/)
* [Cosmos directory](https://cosmos.directory) - [Source](https://github.com/eco-stake/cosmos-directory)
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) - A npm package for the official Cosmos Chain Registry.

## Validators

Popular block explorers provide a list of active validators. The easiest entry point to view validator profiles is from a block explorer:

* [List on Mintscan](https://www.mintscan.io/cosmos/validators)
* [List on ATOMScan](https://atomscan.com/validators)
* [List on BigDipper](https://cosmos.bigdipper.live/validators)
* [List on Kujira POD](https://pod.kujira.app/cosmoshub-4)

DYOR when choosing a validator. Consider delegating your tokens to validators outside of the top 20 to increase the decentralization of the network.
This is also a good practice to avoid 0% commission validators and exchange validators.

## Cosmos SDK Modules

The best place to find an accurate list of the Cosmos SDK modules is the project repository:

* For a list of production-grade modules, see the [List of Modules](https://docs.cosmos.network/main/modules/).
* For a list of well-known third-party modules, see [Cosmod.xyz](https://cosmod.xyz)

## Monitoring

* [PANIC Monitoring and Alerting For Blockchains](https://github.com/SimplyVC/panic) - An open source monitoring and alerting solution for Cosmos SDK, Substrate, and Chainlink-based nodes.
* [Prometheus Exporter](https://github.com/node-a-team/Cosmos-IE) - An integrated Prometheus exporter for the Cosmos SDK.
* [Cosmos Chains Dashboard](https://github.com/zhangyelong/cosmos-dashboard) - A Grafana dashboard to monitor Cosmos SDK and Tendermint-based blockchain nodes.
* [Chain Pulse](https://github.com/informalsystems/chainpulse) - Relayed IBC packets monitor with Prometheus exporter.
* [missed-blocks-checker](https://github.com/QuokkaStake/missed-blocks-checker) - Monitor validators' missed blocks on multiple Cosmos chains and send its notifications to Telegram.
* [Nodes Checker](https://t.me/NodesGuru_bot) - Check your nodes status online, receive instant notification if something is wrong with your validator node.
* [Cosmon](https://github.com/iqlusioninc/cosmon) - Observability tool for Cosmos and other Tendermint applications.
* [Tenderduty](https://github.com/blockpane/tenderduty) - Comprehensive monitoring tool for Tendermint chains. Its primary function is to alert a validator if they are missing blocks, and more.
* [UpgradesWatchdog](https://github.com/ChihuahuaChain/UpgradesWatchdog) - SoftwareUpgradeProposal & GitHub Releases telegram monitoring tool.
* [cosmos-node-exporter](https://github.com/QuokkaStake/cosmos-node-exporter.git) - A Prometheus exporter to scrape data on your node sync status, Cosmovisor upgrades and GitHub version mismatches, useful for node operators and validators.
* [cosmos-wallets-exporter](https://github.com/QuokkaStake/cosmos-wallets-exporter.git) - A Prometheus exporter to scrape data on wallets balance, useful to get notified if your wallet balance is too low.
* [cosmos-validators-exporter](https://github.com/QuokkaStake/cosmos-validators-exporter.git) - A Prometheus exporter to scrape data about a validator (missed blocks, delegators count, total staked amount, rankings, etc.)
* [cosmos-proposals-checker](https://github.com/QuokkaStake/cosmos-proposals-checker.git) - A bot that sends you a notification on multiple Cosmos chains if your wallet hasn't voted on any proposal.
* [cosmos-transactions-bot](https://github.com/QuokkaStake/cosmos-transactions-bot.git) - A bot that sends you notifications on any transactions you want to be subscribed to on multiple Cosmos chains.

## Indexers

* [Cosmscan](https://github.com/cosmscan/cosmscan-go) - An indexer engine for Cosmos chains.
* [interchain-indexer](https://github.com/Reecepbcups/interchain-indexer) - A cosmos blockchain indexer in Python.
* [Cosmos Indexer](https://github.com/DefiantLabs/cosmos-indexer) - A generalized DB schema indexer with correlation and direct database indexing in Go.
* [BDJuno](https://github.com/forbole/bdjuno) - All the chains' data that are queried from the RPC and gRPC endpoints are stored inside a PostgreSQL database on top of which GraphQL APIs can then be created using Hasura.

## Frameworks

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) - A Framework for Building High Value Public Blockchains in Go.
* [Orga](https://github.com/nomic-io/orga) - ABCI framework for state machine transitions in Rust.
* [CosmosSwift](https://github.com/CosmosSwift) - Build blockchain applications in Swift on top of the Tendermint consensus.
* [ABCI-RS](https://github.com/devashishdxt/abci-rs) - Rust crate for creating ABCI applications.
* [CosmRS](https://github.com/cosmos/cosmos-rust/tree/main/cosmrs) - Framework for building Cosmos blockchain applications in Rust.

## Virtual Machines

Modules or frameworks for virtual machines that run in the Cosmos SDK

* [Agoric SDK](https://github.com/Agoric/agoric-sdk) - Agoric JavaScript Smart Contract Platform.
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) - WASM Virtual Machine & Rust Smart Contracts.
* [Ethermint](https://github.com/evmos/ethermint) - Ethereum Virtual Machine.
* [Polaris](https://github.com/berachain/polaris) - Modular Ethereum Virtual Machine.

## IBC

* [IBCprotocol.dev](https://ibcprotocol.dev/) - IBC Protocol website.
* [Interchain Standards](https://github.com/cosmos/ibc/) - Interchain Standards (ICS) for the Cosmos network & interchain ecosystem.
* [cosmos/ibc-go](https://github.com/cosmos/ibc-go) - Inter-Blockchain Communication protocol (IBC) implementation in Go.
* [cosmos/ibc-rs](https://github.com/cosmos/ibc-rs) - Rust implementation of the Inter-Blockchain Communication (IBC) protocol.
* [interchaintest](https://github.com/strangelove-ventures/interchaintest) - E2E testing framework for IBC Chains.
* [cosmos/relayer](https://github.com/cosmos/relayer) - IBC Relayer in Go.
* [informalsystems/hermes](https://github.com/informalsystems/hermes) - IBC Relayer in Rust.
* [confio/ts-relayer](https://github.com/confio/ts-relayer) - IBC Relayer in TypeScript.
* [local-interchain](https://github.com/Reecepbcups/local-interchain) - Quickly spin up a local IBC development environment on any operating system.

## Testing

* [interchaintest](https://github.com/strangelove-ventures/interchaintest) - E2E testing framework for IBC Chains.
* [atomkraft](https://github.com/informalsystems/atomkraft-cosmos) - E2E testing framework of Cosmos SDK blockchains.
* [python-iavl](https://github.com/crypto-com/python-iavl) - IAVL inspection tool implemented in Python.
* [cosmos-sdk-codeql](https://github.com/crypto-com/cosmos-sdk-codeql) - CodeQL queries for common Cosmos SDK bugs.
* [tm-load-test](https://github.com/informalsystems/tm-load-test) - CometBFT load test application.
* [cosmosloadtester](https://github.com/orijtech/cosmosloadtester) - Load tester for Cosmos SDK blockchains.
* [CometMock](https://github.com/informalsystems/CometMock) - Drop-in replacement for CometBFT in end-to-end tests.
* [quint](https://github.com/informalsystems/quint) - Executable specification language with delightful tooling.
* [apalache](https://github.com/informalsystems/apalache) - APALACHE: symbolic model checker for TLA+ and Quint.

## Templates

Templates to help you get started with building a Cosmos SDK blockchain.

* [ignite](https://github.com/cli) - Quickly bootstrap a new Cosmos SDK blockchain with UI and support to create new and work conveniently with existing Cosmos SDK modules.
* [cosmosregistry/example](https://github.com/cosmosregistry/example) - Template and example repository of a Cosmos SDK module.
* [cosmosregistry/chain-minimal](https://github.com/cosmosregistry/chain-minimal) -  Template and example of a minimal Cosmos SDK blockchain.

## Tools

### CLI

* [tmkms](https://github.com/iqlusioninc/tmkms) - Key Management System for Tendermint validators.
* [cosmosvisor](https://github.com/cosmos/cosmos-sdk/tree/main/cosmovisor#readme) - Automates Cosmos SDK application binary upgrades.
* [cosmosvanity](https://github.com/hukkinj1/cosmosvanity) - CLI tool for generating Cosmos vanity addresses.
* [findaccount](https://github.com/blockpane/findaccount) - Helps identify if an account exists on multiple Cosmos chains with the same address.
* [lens](https://github.com/strangelove-ventures/lens) - CLI tool to interact with any Cosmos chain supporting the core Cosmos-SDK modules.
* [cosmology](https://github.com/cosmology-tech/cosmology) - CLI tool for making cryptocurrency trades, joining liquidity pools, and stake rewards on Osmosis.
* [multisig](https://github.com/informalsystems/multisig) - CLI tool for managing multisig accounts on Cosmos SDK chains.
* [cosmos-genesis-tinkerer](https://github.com/hyphacoop/cosmos-genesis-tinkerer) - CLI tool for modifying Cosmos genesis files.
* [airdrop-tools](https://github.com/Reecepbcups/airdrop-tools) - CLI scripts to help distribute a variety of tokens from multiple formats.
* [cosmos.nix](https://github.com/informalsystems/cosmos.nix) - [Nix](https://nixos.org/) support for Cosmos and CosmWasm.

### GUI

* [Cosmos Hub Multisig Manager](https://cosmos-multisig-ui-kohl.vercel.app) - Create multisigs and multisig transactions on the Cosmos Hub ([source](https://github.com/cosmos/cosmos-multisig-ui)).
* [REStake](https://restake.app) - Auto-compounder app for Cosmos blockchains using Authz ([source](https://github.com/eco-stake/restake)).
* [Yieldmos](https://yieldmos.com) - Staking and LP rewards auto-compounder using Authz.
* [Cosmfaucet](https://github.com/scalalang2/cosmfaucet) - Self-hosted faucet service for Cosmos based blockchain.
* [Cosmos Notifier](https://cosmos-notifier.decrypto.online) - Governance notification tool for Telegram and Discord ([source](https://github.com/shifty11/cosmos-notifier)).
* [IBC Anywhere](https://ibc.reece.sh/) - IBC token transfers including multi-chain hops.

### Bots

* [Cosmos Discord Faucet](https://github.com/0x4139/cosmos-discord-faucet) - A configurable Discord faucet for Cosmos SDK blockchains.
* [Cosmos Discord Bot](https://github.com/okp4/discord-bot) - A general-purpose Discord bot for Cosmos SDK blockchains.
* [cosmos-proposals-checker](https://github.com/QuokkaStake/cosmos-proposals-checker.git) - A bot to notify you if your wallets didn't vote on proposal on multiple Cosmos SDK chains.
* [cosmos-transactions-bot](https://github.com/QuokkaStake/cosmos-transactions-bot.git) - Get notified about transactions matching the filters you want on multiple Cosmos SDK chains.
* [cosmos-balance-bot](https://github.com/Reecepbcups/cosmos-balance-bot) - Get notified about your wallet balance on multiple Cosmos SDK chains at a set interval.
* [validator-stats-notifications](https://github.com/Reecepbcups/validator-stats-notifs) - Discord announcements including ranking, delegations over time, and unique delegators.
* [Secret Stashh NFT Bot](https://github.com/Reecepbcups/stashh-bot) - A discord bot to get notified of sales, auctions, and purchases for a Secret Network NFT collection.
* [DAODAO Treasury Bot](https://github.com/Reecepbcups/dao-treasury-bot) - A discord bot that keeps up with a DAO's treasury fiat value.
* [Cosmos Price Bot](https://github.com/Reecepbcups/cosmos-price-bot) - A discord bot that nicknames to the USD price of any cosmos token via a DEX.

## Node Operations

### Utilities

* [Cosmos Cache](https://github.com/Reecepbcups/cosmos-endpoint-cache) - Optimize Cosmos queries by caching responses for predefined sets of time (regex).
* [cosmos-operator](https://github.com/strangelove-ventures/cosmos-operator) - Cosmos Operator is a kubernetes operator for managing cosmos nodes.

## Ecosystem

The most up-to-date list of projects built using Cosmos SDK can be found on the [Cosmos Directory](https://cosmos.directory).

## Wallets

A list of wallets supporting Cosmos chains is <https://cosmos.network/ecosystem/wallets>.

## Blogs

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**

As the ecosystem grows, so does the content. DYOR and follow the projects you find interesting.

* [What is Cosmos?](https://cosmos.network/intro/)
* [Cosmos Blog](https://blog.cosmos.network/)
* [Interchain Foundation Blog](https://interchain-io.medium.com)

### Articles

* [Cosmos Dev Series: Cosmos Blockchain Upgrade](https://zerofruit.medium.com/cosmos-dev-series-cosmos-sdk-based-blockchain-upgrade-b5e99181554c)
* [Hardening guides](https://cyber.orijtech.com/scsec/cosmos-hardening)
* [How to connect your frontend to Cosmos blockchain](https://dev.to/kikiding/how-to-connect-your-frontend-to-cosmos-blockchain-5fcn)
* [(Not So) Smart Cosmos, examples of common Cosmos app vulnerabilities](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cosmos)
* [Go coding guide](https://cyber.orijtech.com/scsec/cosmos-go-coding-guide)
* [The Cosmos Security Handbook - Part 1](https://www.faulttolerant.xyz/2024-01-16-cosmos-security-1)

## Related

* [Awesome CosmWasm](https://github.com/InterWasm/cw-awesome)
