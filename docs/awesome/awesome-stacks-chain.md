<div class="github-widget" data-repo="friedger/awesome-stacks-chain"></div>
## Awesome Stacks[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Stacks](https://raw.githubusercontent.com/friedger/awesome-stacks-chain/master/img/awesome-stacks.png 'Awesome Stacks')](https://www.stacks.co)

[Stacks](https://www.stacks.co/what-is-stacks) is a Blockchain anchored by Bitcoin that enables apps, smart contracts, and digital assets. Stacks is a layer-1 Blockchain that connects to Bitcoin and implements smart contracts and decentralized applications through the [Clarity language](https://clarity-lang.org/). Through the [Proof of Transfer (PoX) consensus mechanism](https://docs.stacks.co/stacks-101/proof-of-transfer), the state of the Stacks Blockchain is anchored against the Bitcoin Blockchain, thus providing the security and finality of Bitcoin to Stacks. Stacks brings the programmability of other Blockchain technologies to Bitcoin, without the need to modify the core consensus mechanism of Bitcoin itself.


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!--lint ignore awesome-list-item-->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Apps

### Wallets

- [Asigna](https://asigna.io) - Multisig Wallet for Bitcoin, Ordinals, BRC20s, and Stacks.
- [Leather Wallet](https://leather.io/) - Open Source wallet for connecting to Bitcoin and Stacks web applications. Also for mobile.
- [OKX Web3 Wallet](https://web3.okx.com/download) - Multi-chain wallet that also supports Stacks.
- [Xverse Wallet](https://www.xverse.app) - Mobile wallet application and browser extension for managing Bitcoin, STX and stacking (partly open source).
- [WalletConnect](https://docs.reown.com/advanced/multichain/rpc-reference/stacks-rpc) - Documentation how to use Wallet Connect (Reown) with Stacks.

### Stacks Web Applications

- [Hiro Explorer](https://explorer.hiro.so/?chain=mainnet) - An application for reviewing transactions on the Stacks Blockchain.
- [STXER](https://stxer.xyz/) - An explorer, debugger and simulator for Stacks transactions.
- [Send Many](https://sendstx.com) - An application to send STX and other tokens to many recipients in one transaction.
- [Speed Spend](https://speed-spend.org) - A suite of working Clarity experiments on testnet ([source](https://github.com/friedger/speed-spend)).
- [Blocksurvey](https://blocksurvey.io) - AI-driven survey platform with focus on data ownership and privacy.
- [AIBTC](https://aibtc.com/) - A coordination network of AI agents working towards measurable tasks.
- [FatStx](https://fatstx.github.io/) - An annual transaction viewer for e.g. tax declaration.

### Blockchain Name System

- [BNS V2](https://www.bnsv2.com/) - Hub for all Blockchain namespaces on Stacks, with transaction history and analytics.
- [btc.us](https://btc.us) - An application for .btc names.
- [Owl.link](https://owl.link) - An application to create linking page for BNS names.

### DeFi

- [Bitflow](https://www.bitflow.finance/) - Decentralized Exchange.
- [Velar](https://www.velar.co/) - Swapping, trading, launching assets on premier Bitcoin L2s.
- [Zest Protocol](https://www.zestprotocol.com/) - Decentralized borrowing and lending on Bitcoin and Stacks.
- [FakFun](https://fak.fun) - Platform for exchange, launch, wrapping for memecoins build on Bitcoin.
- [Alex Lab](https://app.alexlab.co) - A service platform for DeFi.
- [Arkadiko Protocol](https://arkadiko.finance) - Stable coin (USDA) based on self-repaying loans.
- [Granite](https://granite.world/) - A Bitcoin liquidity protocol that provides the non-custodial, secure, and decentralized way to borrow against Bitcoin.
- [BSD](https://www.bsd.money/) - A synthetic, digital dollar backed by Bitcoin using over-collateralized lending model.
- [USDh](https://app.hermetica.fi) - A Bitcoin-baked, yield-bearing synthetic dollar using short perpetual futures position and institutional-grade custodians.
- [STXTools](https://stxtools.io/) - Charts, transactions, price alerts for DeFi on Stacks.
- [Stacks Pulse](https://www.stackspulse.com/) - Real-time on-chain Stats for Stacks DeFi.
- [Signal21](https://signal21.io/) - On-chain analysis for Bitcoin L1, L2 and Dapps.
- [Lydian](https://app.lydian.xyz) - A decentralised treasury management protocol (discontinued).
- [CityCoins](https://minecitycoins.com) - Tokens for cities (winding down).

### Games

- [Stacks Degens](https://stacksdegens.com) - A car racing game with retro graphics enabled through NFTs.
- [Project Indigo](https://www.projectindigonft.com) - An interactive story and RPG experience.

### Stacking Apps

- [Stacking on Leather](https://app.leather.io/stacking) - App to stack Stacks token directly or with a pool.
- [Fast pool](https://fastpool.org/) - Trust minimized stacking pool.
- [PlanBetter pool](https://planbetter.com/) - Stacking pool with Bitcoin rewards.
- [Xverse pool](https://pool.xverse.app/) - Stacking pool built into Xverse mobile app.
- [Stacking DAO](https://www.stackingdao.com/) - Liquid stacking on Stacks.
- [Lisa](https://app.lisalab.io) - Liquid stacking on Stacks using rebasing.
- [Stacking Tracker](https://stacking-tracker.com) - Overview of Stacking and historical data [Source code](https://github.com/StackingDAO/stacking-tracker).

## Clarity Resources

### Developer Tools

- [Clarinet](https://github.com/hirosystems/clarinet) - Clarity runtime packaged as a CLI, facilitates development and testing of Clarity smart contracts.
- [Clarigen](https://github.com/obylabs/clarigen) - A tool for writing TypeScript code that interacts with Clarity smart contracts.
- [clarity.tools](https://clarity.tools) - In-browser Clarity REPL.
- [ClarityGPT Prompt](https://claritygpt.com/) - Writing smart contracts with a chat bot.
- [Hiro Platform](https://platform.hiro.so/) - In-browser IDE.
- [secondlayer](https://github.com/ryanwaits/secondlayer) - TypeScript code generation for Clarity contracts with React hooks and testing utilities. Inspired by Clarigen.

### Example Contracts

- [Source of Clarity](https://source-of-clarity.com) - Listing of all deployed Clarity contracts on mainnet with some comments.
- [Example Contracts](https://github.com/hirosystems/clarity-examples) - A collection of sample smart contracts to serve as a starting point for writing your own.
- [Audited Example Smart Contracts](https://github.com/clarity-lang/book/tree/main/projects) - Another collection of smart contract examples, these have been audited for security.

### Libraries & Protocols

- [blaze](https://gist.github.com/r0zar/414e91d3e6769644981b4918141a1708) - A protocol for signature-based authorization.
- [uint256](https://github.com/KStasi/clarity-uint256-lib) - A library for converting values into 256-bits.
- [clarity-bitcoin](https://github.com/friedger/clarity-bitcoin) - A library to verify Bitcoin transactions.
- [STX20](https://github.com/fess-v/stx20-standard) - Protocol to create and share digital artifacts on Stacks.

### Contracts

- [CityCoin](https://github.com/citycoins/citycoin) - An implementation of PoX lite using STX transfers to mint new coins using proportional probabilities.
- [SWAPR](https://github.com/psq/swapr) - A Uniswap-like implementation on Stacks 2.0 and Clarity.
- [FLEXR](https://github.com/psq/flexr) - An interpretation of Ampleforth for Stacks.
- [ClarityDAO](https://github.com/friedger/clarity-dao) - A conversion of Moloch DAO in Clarity.
- [NFT Marketplace](https://github.com/friedger/clarity-marketplace/blob/master/contracts/market.clar) - Clarity smart contract for a marketplace of tradable assets.
- [StackStarter](https://github.com/MarvinJanssen/stackstarter/blob/master/contracts/stackstarter.clar) - Clarity smart contract for crowdfunding.
- [Lightning Swaps](https://github.com/radicleart/clarity-rstack/blob/master/contracts/lightning-swaps-v1.clar) - Fraud-proof swaps using Lightning Network.
- [Election Voting](https://github.com/elbaruni/clarity-election/blob/master/contracts/election.clar) - Basic voting for candidates using Clarity.
- [DualX](https://github.com/westridgeblockchain/dualX) - A collection of Clarity contracts that implement a DeFi ecosystem for exchanges.
- [ExecutorDAO](https://github.com/MarvinJanssen/executor-dao) - A Clarity framework for building DAO functionality into your smart contracts.
- [Digital Will](https://github.com/LoRdSoban/Cryptonomers) - Conditional fund transfers.
- [MultiSafe](https://github.com/Trust-Machines/multisafe) - A shared crypto vault for managing Stacks (STX) and Bitcoin (BTC).
- [Charisma](https://github.com/pointblankdev/dungeon-master) - Community-run memecoin DAO on the Stacks Blockchain.

### Non-Fungible Tokens

- [This is #1](https://www.thisisnumberone.com) - The first professional NFT built on Bitcoin and the Stacks Blockchain ([contract](https://explorer.hiro.so/txid/SP3QSAJQ4EA8WXEDSRRKMZZ29NH91VZ6C5X88FGZQ.thisisnumberone-v2?chain=mainnet)).
- [Smart Contract GPT](https://github.com/Markeljan/stxgpt) - Chat bot trained to create SIP-009 contracts.

### Fungible Tokens

- [Nothing](https://nothingtoken.xyz/) - A fungible token that does nothing ([contract](https://explorer.hiro.so/txid/SP32AEEF6WW5Y0NMJ1S8SBSZDAY8R5J32NBZFPKKZ.nope?chain=mainnet)).

### Stacking

- [Stacking Pools](https://github.com/friedger/clarity-stacking-pools) - Wrapper contracts of PoX for stacking pools.
- [Stacks Pools](https://github.com/degen-lab/stacks-pools) - Decentralized Stacking Pool.

## App Development

### Client Libraries

- [Stacks.js](https://github.com/stx-labs/stacks.js) - Monorepo for JavaScript libraries for interacting with the Stacks Blockchain.
- [stacks.rs](https://github.com/52/stacks.rs) - A Rust toolkit to interact with the Stacks Blockchain.
- [stacks.py](https://github.com/rohitverma007/stackspy) - Python Library to interact with the Stacks Blockchain.
- [go-stacks](https://github.com/cbadawi/go-stacks) - Golang SDK for interacting with the stacks blockchain. 
- [x402 Stacks](https://www.x402stacks.xyz) - A protocol and SDK for building payment-gated APIs on the Stacks Blockchain.
- [Stacks Connect](https://github.com/stx-labs/connect) - A library for connecting apps with Stacks accounts.
- [Sign-In With Stacks](https://github.com/pradel/sign-in-with-stacks/) - A library for creating and verifying Sign-In with Stacks messages.

### CLI

- [@stacks/cli](https://github.com/stx-labs/stacks.js/tree/main/packages/cli) - Command line interface for interacting with auth, storage, and transactions.

### Indexing and Querying APIs

- [Stacks API](https://www.hiro.so/stacks-api) - Hosted API to interact directly with the Blockchain to query information, broadcast transactions, and scale your projects on Stacks.
- [Quicknode](https://www.quicknode.com/chains/stx) - Hosted ednpoint to quickly and easily connect to Stacks using Quicknode.
- [Self-Hosted Render](https://github.com/stacksfoundation/render-stacks) - One-click deploy tool to self-host a Stacks node on Render.
- [Self-Hosted Digital Ocean](https://marketplace.digitalocean.com/apps/stacks-blockchain) - Digital Ocean droplet for running a Stacks node.
- [Self-Hosted Docker](https://github.com/stacks-network/stacks-blockchain-docker) - Tool to run a self-hosted Stacks node with Docker.
- [Stacks Monitoring](https://github.com/alexlmiller/stacks-monitoring) - Grafana Dashboard for Stacks nodes.

## Learning Resources

### Documentation

- [Official Stacks documentation](https://docs.stacks.co/) - Documentation and developer tutorials for learning
  Clarity and developing Stacks apps.
- [Hiro documentation](https://docs.hiro.so/) - Documentation focused on developers.
- [Stacks 101](https://stacks101.com) - Community curated STX knowledge.

### Videos

- [Clarity 101](https://youtu.be/lXJutQqDq3w) - Learn the basics of Clarity's design principles.
- [Developer Registry 101](https://www.crowdcast.io/e/clarity-program) - Learn how to build a Clarity smart contract from scratch.
- [How Clarity Prevents Common Smart Contract Vulnerabilities](https://www.youtube.com/watch?v=VYXhrwPsBws) - Explanation of Clarity's security princples.
- [Proof of Transfer Whitepaper Reading with Muneeb Ali](https://www.youtube.com/watch?v=NY_eUrIcWOY&t=3s) - Overview of the Proof of Transfer (PoX) whitepaper from the author.
- [Web3 for Bitcoin](https://www.crowdcast.io/e/web3-for-bitcoin/) - Overview of Stacks, the problem it solves, how it brings smart contract functionality to Bitcoin, and how to start building on it.
- [Why Build on Stacks](https://www.youtube.com/watch?v=WaTMCremGwE) - An overview of why Web3 developers might want to build on Stacks over other Blockchain protocols.

### Written Tutorials
- [Bitcoin Primer](https://docs.stacks.co/tutorials/bitcoin-primer/introduction) - An Intro to Building Full-Stack Dapps on Bitcoin.
- [Understanding Stacks Post Conditions](https://dev.to/stacks/understanding-stacks-post-conditions-e65) - A guide to understanding and working with Post Conditions in Stacks.
- [Test-Driven Stacks Development with Clarinet](https://dev.to/stacks/test-driven-stacks-development-with-clarinet-2e4i) - A tutorial showing how to utilize Clarinet for testing and TDD.
- [Build a DEX with Stacks](https://www.pointer.gg/tutorials/build-a-dex-with-stacks/56abb3a4-05c1-4608-b096-f82189e9f759) - An extensive introduction to working with Stacks by building a full-stack decentralized exchange.
- [Build a Stacks app with Remix](https://micro-stacks.dev/guides/with-remix) - How to create a server-side rendered Stacks app using the Remix JS framework and Micro-Stacks.
- [Build a Stacks app with Next.js](https://micro-stacks.dev/guides/with-nextjs) - Similar to the Remix tutorial above, this one utilizing Next.js and Micro-Stacks.
- [Creating a Voting Contract](https://www.clearness.dev/01-voting-clarity-smart-contract/01-getting-started) - A multi-part series showing how to use Clarity to create a simple voting smart contract.
- [Building an NFT with Stacks and Clarity](https://blog.developerdao.com/building-an-nft-with-stacks-and-clarity) - Utilize the SIP-009 standard to create an NFT using Clarity.
- [Order Book Contract Walkthrough](https://byzantion.hiro.so/) - Walkthrough of an order book smart contract built with Clarity.
- [NFT Tutorial](https://docs.hiro.so/tutorials/clarity-nft) - Create an NFT with Clarity.

### Books

- [Clarity of Mind](https://book.clarity-lang.org/) - Writing productive smart contracts that are predictable. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

### Courses

- [Clarity Universe](https://clarity-lang.org/universe) - A comprehensive Clarity development course, offered as both a self-paced course or as a 6-week guided cohort.

## Community

- [Discord](https://discord.gg/zrvWsQC) - Stacks ecosystem Discord.
- [Twitter](https://twitter.com/stacks) - Stacks ecosystem Twitter.
- [YouTube](https://www.youtube.com/c/Blockstack) - Stacks ecosystem YouTube.
- [Official Stacks Forum](https://forum.stacks.org/) - Stacks community forum.
- [r/stacks](https://www.reddit.com/r/stacks) - Stacks subreddit.

## Contributing

We welcome community contributions to this list. Please read the [contribution guidelines](https://github.com/friedger/awesome-stacks-chain/blob/master/contributing.md) before contributing.
