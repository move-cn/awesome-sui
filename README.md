<!--lint disable double-link-->

# Awesome Sui [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of code and content from the [Sui](https://sui.io) community.

Sui is an innovative, decentralized Layer 1 blockchain that redefines asset ownership.

Sui (swē) is the water element in Japanese philosophy. The power of the sui element lies in its fluidity—its ability to easily adapt to and transform any environment. Similarly, the Sui platform seeks to provide a flexible network that you can leverage to shape the web3 landscape.

The Sui platform is built on Sui Move, which is derived from the core [Move](https://github.com/MystenLabs/awesome-move) programming language.

## Contents

- [Overview](#overview)
- [Books](#books)
- [Tutorials](#tutorials)
- [Community](#community)
- [Oracle](#oracle)
- [RPC](#rpc)
  - [mainnet](#mainnet-rpc)
  - [testnet](#testnet-rpc)
  - [devnet](#devnet-rpc)
- [Products](#products)
- [DeFi](#defi)
  - [lending](#lending)
  - [swap](#swap)
  - [other](#other-defi)
- [Code](#code)
  - [Fungible Tokens](#fungible-tokens)
  - [Non-Fungible Tokens](#non-fungible-tokens)
  - [Decentralized Identity](#decentralized-identity)
  - [SocialFi](#socialfi)
  - [On-Chain Governance](#on-chain-governance)
  - [Cross-Chain Bridge](#cross-chain-bridge)
  - [Accounts](#accounts)
  - [Frameworks](#frameworks)
  - [Libraries](#libraries)
- [Tools](#tools)
- [IDEs](#ides)
- [Package Managers](#package-managers)
- [Explorer](#Explorer)
- [Wallets](#wallets)
- [SDKs](#sdks)
- [Papers](#papers)
  - [Language Design](#language-design)
  - [Static Analysis and Verification](#static-analysis-and-verification)
- [Videos](#videos)
- [Slides](#slides)
- [Podcasts](#podcasts)
- [Blog Posts](#blog-posts)
- [Security](#security)

## Overview

- [Installation](https://docs.sui.io/build/install)
- [Learn](https://docs.sui.io/learn)


## Official github 
- [Mysten Labs](https://github.com/mystenlabs)
- [Sui Foundation](https://github.com/sui-foundation)
- [Sui](https://github.com/mystenlabs/sui)
- [move-language](https://github.com/move-language/move)

# Official Community
- [Website](https://sui.io)
- [Discord](https://discord.gg/sui)
- [Discord | Mysten Labs](https://discord.com/mysten)
- [Twitter](https://twitter.com/SuiNetwork) 
- [Twitter | SuiFoundation](https://twitter.com/SuiFoundation)
- [Twitter | Chinese 中文](https://twitter.com/SuiFoundation)
- [Twitter | Mysten Labs](https://twitter.com/Mysten_Labs)
- [Telegram | English](https://t.me/Sui_Blockchain_English)
- [Telegram | Chinese 中文](https://t.me/Sui_Blockchain_Chinese)
- [Telegram | Chinese 中文开发者社区](https://t.me/sui_dev_cn)

## Books

- [Sui Move by Example](https://examples.sui.io/) - A book on the Sui Move variant maintained by [@MystenLabs](https://github.com/MystenLabs).
- [Move Book](https://move-language.github.io/move/) - Move book maintained by the Move core team ([中文](https://github.com/move-language/move/tree/main/language/documentation/book/translations/move-book-zh)).
- [Move Book](https://move-book.com/) - Move book maintained by [@damirka](https://github.com/damirka) ([中文](https://move-book.com/cn/)).
- [Move Patterns](https://www.move-patterns.com/) - A book on Move software design patterns maintained by [@villesundell](https://github.com/villesundell).

## Tutorials

- [Programming with objects](https://docs.sui.io/build/programming-with-objects) - Maintained by the Sui team.
- [Implementing, testing, and verifying a fungible token](https://github.com/move-language/move/tree/main/language/documentation/tutorial) - Maintained by the Move core team.
- [Move Language](https://imcoding.online/courses/move-language) - Interactive Move language course, free for everyone, maintained by [imcoding.online](https://imcoding.online) ([中文](https://imcoding.online/courses/move-language?lng=zh)).

### Explorer
- [Sui Explorer](https://suiexplorer.com/) (official)
- [SuiVision](https://suivision.xyz/)
- [SuiScan](https://suiscan.xyz/mainnet/home)

## Wallets

- [Sui Wallet](https://github.com/MystenLabs/sui/tree/main/apps/wallet) - A chrome (v88+) extension wallet for Sui ([Chrome Webstore](https://chrome.google.com/webstore/detail/sui-wallet/opcgpfmipidbgpenhmajoajpbobppdil)).
- [Suiet Wallet](https://github.com/suiet/suiet) - A open-source wallet for Sui. ([Chrome Webstore](https://chrome.google.com/webstore/detail/suiet/khpkpbbcccdmmclmpigdgddabeilkdpd), [Website](https://suiet.app))
- [Ethos Wallet](https://github.com/EthosWallet/chrome-extension) - Open-source chrome extension wallet for Sui ([Chrome Webstore](https://chrome.google.com/webstore/detail/ethos-sui-wallet/mcbigmjiafegjnnogedioegffbooigli), [Website](https://ethoswallet.xyz/)).
- [Surf](https://github.com/EthosWallet/chrome-extension) - Open-source chrome extension wallet for Sui ([Chrome Webstore](https://chromewebstore.google.com/detail/surf-wallet/emeeapjkbcbpbpgaagfchmcgglmebnen), [Website](https://surf.tech/)).
- [Okx Wallet](https://www.okx.com/web3)  ([Chrome Webstore](https://chromewebstore.google.com/detail/%E6%AC%A7%E6%98%93web3%E9%92%B1%E5%8C%85/mcohilncbfahbmgdjkbpemcciiolgcge), [Website](https://www.okx.com/web3)).
- [ComingChat](https://coming.chat/) - A decentralized social finance/web3 portal. Supporting public chain wallets, such as Sui  wallets.

### Wallet Adapters

- [Sui Wallet](https://github.com/MystenLabs/sui/tree/main/sdk/wallet-adapter) - Sui Wallet Adapter.
- [Suiet Wallet](https://github.com/suiet/wallet-adapter) - Suiet Wallet Adapter.

### Wallet Kits

- [Suiet Wallet Kit](https://github.com/suiet/wallet-kit) - A package support all Sui wallets with customizable UI.
- [Ethos Connect](https://github.com/EthosWallet/ethos-connect) - UI with built-in wallet adapter and Email option for supporting all wallets and wallet-less users on Sui.

## Sui Faucet 
 - [official](https://docs.sui.io/build/faucet)
 - [community](https://github.com/uvd/sui-faucet)
## SDKs

### Sui SDKs

- [Rust SDK](https://docs.sui.io/devnet/build/rust-sdk) (official)
- [TS/JS SDK](https://github.com/MystenLabs/sui/tree/main/sdk/typescript) (official)
- [Sui Typescript SDK (community)](https://github.com/scallop-io/sui-kit)
- [Golang SDK 1 by block vision](https://github.com/block-vision/sui-go-sdk) (community)
- [Golang SDK 2 by coming chat](https://github.com/coming-chat/go-sui-sdk) (community)
- [Python SDK](https://github.com/FrankC01/pysui) (community)
- [Java SDK](https://github.com/GrapeBaBa/sui4j) (community)
- [Kotlin SDK](https://github.com/cosmostation/suikotlin) (community)
- [C# SDK](https://github.com/naami-finance/SuiNet) (community)
- [Sui Dart SDK](https://github.com/mofalabs/sui) (community)


## oracle
- [Pyth](https://pyth.network) offer developers permissionless access to price feeds for equities, commodities, foreign exchange pairs, and digital assets
- [SupraOracles](https://supraoracles.com/) offers decentralized oracle services for applications on Sui. Developers can now seamlessly fetch, validate, and integrate off-chain data into their smart contracts,
- [Mysten Oracles](https://mystenlabs.com/blog/simple-and-meta-oracles-on-sui) The former allows lower assurance values to be posted and read by contracts at a cheaper gas cost point than high-assurance oracles. Low assurance oracles are best used for applications with low risk and non-financial consequences such as in games.

## RPC

### mainnet RPC

- https://rpc.mainnet.sui.io
- https://fullnode.mainnet.sui.io
- https://wallet-rpc.mainnet.sui.io
- https://explorer-rpc.mainnet.sui.io
- https://sui-rpc-mainnet.testnet-pride.com
- https://sui-mainnet.nodeinfra.com
- https://mainnet-rpc.sui.chainbase.online
- https://sui-mainnet-ca-1.cosmostation.io/
- https://sui-mainnet-ca-2.cosmostation.io/
- https://sui-mainnet-eu-1.cosmostation.io/
- https://sui-mainnet-eu-2.cosmostation.io/
- https://sui-mainnet-eu-3.cosmostation.io/
- https://sui-mainnet-eu-4.cosmostation.io/
- https://sui-mainnet-us-1.cosmostation.io/
- https://sui-mainnet-us-2.cosmostation.io/
- https://mainnet.sui.rpcpool.com
- https://rpc-mainnet.suiscan.xyz
- https://sui.publicnode.com
- https://sui-mainnet-rpc.allthatnode.com/  
- https://sui-mainnet-rpc-germany.allthatnode.com/
- https://sui-mainnet-rpc-korea.allthatnode.com/
- https://sui1mainnet-rpc.chainode.tech/
- https://sui-rpc-mainnet.brightlystake.com/

### testnet RPC
- https://rpc.testnet.sui.io
- https://fullnode.testnet.sui.io
- https://wallet-rpc.testnet.sui.io
- https://explorer-rpc.testnet.sui.io
- https://sui-testnet.nodeinfra.com
- https://testnet-rpc.sui.chainbase.online

### devnet RPC
- https://rpc.devnet.sui.io
- https://fullnode.devnet.sui.io


## Products

Products support sui

### Defi

#### lending
- [omnibtc](https://omnilending.omnibtc.finance/lending) |  [Code](https://github.com/OmniBTC/DolaProtocol/tree/main/sui)
- [scallop](https://scallop.io) | [code](https://github.com/scallop-io/sui-lending-protocol)
- [naviprotocol](https://app.naviprotocol.io)

#### swap
- [deep-book](https://sui-deepbook.com/)
- [cetus](https://app.cetus.zone/) uni-v3
- [turbos](https://app.turbos.finance) uni-v3
- [Omnibtc](https://app.omnibtc.finance/swap) uvi-v2
- [AfterMath](https://aftermath.finance/trade)
- [flowx](https://flowx.finance) uvi-v2
- [kriya](https://www.app.kriya.finance/spot/swap) uni-V2  
- [suiswap](https://suiswap.app/) uni-V2
- [abex](https://abex.fi/app/trade)
- [bluemove](https://dex.bluemove.net) uni-v2
- [bayswap](https://bayswap.io) uni-v2
- [interest](https://www.interestprotocol.com/dapp/swap) uni-v2

#### other defi
- [typus](https://typus.finance/vault/)
- [bucket](https://app.bucketprotocol.io)
- [mole](https://mole.fi/)


### MEV SDKs

- [cetus-clmm-sui-sdk](https://github.com/CetusProtocol/cetus-clmm-sui-sdk)
- [sui-scallop-sdk](https://github.com/scallop-io/sui-scallop-sdk)
- [OmniSwap-Sui-SDK](https://github.com/OmniBTC/OmniSwap-Sui-SDK)
- [Kana Labs](https://docs.kanalabs.io/getting-started/welcome-to-kana-labs)

### Non Fungible Tokens

- [Clutchy](https://clutchy.io/)
- [Souffl3](https://souffl3.com/)
- [Keepsake](https://keepsake.gg/)
- [BlueMove](https://sui.bluemove.net/)
- [Hyperspace](https://sui.hyperspace.xyz/)



## Code

Code written in Move.

### Fungible Tokens

- [Fungible token examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/fungible_tokens) - Multiple example token implementations from Sui.
- [XBTC](https://github.com/OmniBTC/OmniBridge/blob/main/sui/bridge/sources/xbtc.move) - BTC mirror asset on Sui.

### Non-Fungible Tokens

- [NFT examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/nfts) - Multiple NFT example implementations from Sui.
- [NFT Protocol](https://github.com/Origin-Byte/nft-protocol) - NFT protocol and collection framework. From OriginByte.
- [Suia](https://github.com/Mynft/suia) - The first POAP application on Sui.

### Decentralized Identity

- [Polymedia Profile](https://github.com/juzybits/polymedia-profile) - A system that lets users associate a profile (name, picture, etc) to their Sui address. Maintained by [@juzybits](https://github.com/juzybits).

### DeFi

- [DeFi examples](https://github.com/MystenLabs/sui/tree/main/sui_programmability/examples/defi) - Multiple DeFi example implementations from Sui.
- [SuiRedPacket](https://github.com/coming-chat/sui-red-packet) - A red packet social app that combines private chat and encrypted wallet on Sui.
- [SuiAMMswap](https://github.com/OmniBTC/Sui-AMM-swap) - Sui AMM Swap implemented by the OmniBTC team.
- [DolaProtocol](https://github.com/OmniBTC/DolaProtocol) - A Decentralized Omnichain Liquidity Aggregation Protocol with the single coin pool of each public chain as the core, Wormhole, Layerzero and other cross-chain messaging protocols as the bridge, and Sui public chain as the settlement center.
- [ObjectMarket](https://github.com/coming-chat/object-market) - A unique object trading marketplace in the Sui network.
- [CoinSwap](https://github.com/move-language/move/tree/main/language/documentation/examples/experimental/coin-swap) - A toy implementation of a [Uniswap](https://uniswap.org/)-like liquidity pool containing two tokens.
- [Offer](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/offer.move) - Generic implementation of atomic swaps for any pair of assets.

### SocialFi

- [Dmens](https://github.com/coming-chat/Dmens) - Decentralized Moments which is a Blockchain Twitter Protocol built on the Sui network.

### On-Chain Governance

TBA

### Cross-Chain Bridge

- [OmniBTC Bridge](https://github.com/OmniBTC/OmniBridge) - A bridge between Bitcoin and Move language public chains (like Sui) based on ultra-light node.

### Accounts

- [Account](https://github.com/diem/diem/blob/main/diem-move/diem-framework/core/sources/Account.move) - A generic account for Diem-powered chains. From Diem.

### Frameworks

A Move **framework** is the set of Move modules included in the genesis state of the chain.
These modules typically implement key concepts like accounts, currencies.
The ability to separate blockchain-specific framework logic from the generic functionality of the Move language is a key part of Move's platform-agnostic design.

- [Sui Framework](https://github.com/MystenLabs/sui/tree/main/crates/sui-framework)

### Libraries

- [Move standard library](https://github.com/move-language/move/tree/main/language/move-stdlib) - Utilities intended (but not required) to be used in every platform running Move. From the Move repo.
- [Move nursery](https://github.com/move-language/move/tree/main/language/move-stdlib/nursery) - Experimental modules that may eventually be promoted into the standard library. From the Move repo.
- [Decimal](https://github.com/OLSF/libra/blob/main/language/diem-framework/modules/0L/Decimal.move) - Efficient implementation of a decimal value. From 0L.
- [Math](https://github.com/starcoinorg/starcoin-framework/blob/main/sources/Math.move) - Math utility functions. From Starcoin.
- [Compare](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/compare.move) - Polymorphic comparison (i.e., compare any two Move values of the same type). From the nursery.
- [Vault](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/vault.move) - Library for capabilities. From the nursery.
- [ACL](https://github.com/move-language/move/blob/main/language/move-stdlib/nursery/sources/acl.move) - Library for list-based access control. From the nursery.
- [TaoHe](https://github.com/taoheorg/taohe) - A collection of nestable Move resources.
- [Movemate](https://github.com/pentagonxyz/movemate) - Smart contract building blocks for  Sui (Math utilities, governance contracts, escrow, and more). Maintained by the Pentagon team.
- [Move cron parser](https://github.com/snowflake-so/move-cron-parser#readme) - Library is built for a purpose of parsing cron expression. Maintained by Snowflake Network team.

## Tools

- [Move Playground JS Library](https://github.com/imcoding-online/js-move-playground) - Wrapping [Move Playground by Pontem](https://playground.pontem.network/) as a JavaScript library for browser. You can use it to build your own Move Playground.
- [go-sui-indexer](https://github.com/coming-chat/go-sui-indexer) - An off-fullnode service to serve data from Sui Node.

## IDEs

TBA

## Package Managers

- [Movey](https://www.movey.net/) - A crates.io-style repository of Move packages.


## Papers

### Language Design

- [Move: A Language With Programmable Resources](https://developers.diem.com/papers/diem-move-a-language-with-programmable-resources/2019-06-18.pdf) - This was the original Move white paper released in 2018. Many aspects of this are now out of date (e.g., the syntax and description of the bytecode instructions), but the first two sections are worth a read for explaining the difficulties of programming with assets and how Move tackles them.
- [Robust Safety for Move](https://arxiv.org/abs/2110.05043)
- [The Move Borrow Checker](https://arxiv.org/abs/2205.05181)
- [Resources: A Safe Language Abstraction for Money](https://arxiv.org/abs/2004.05106)

### Static Analysis and Verification

- [Fast and Reliable Formal Verification of Smart Contracts with the Move Prover](https://arxiv.org/abs/2110.08362)
- [The Move Prover](https://research.facebook.com/publications/the-move-prover/)
- [Verification of Programs Written in Libra's Move Language](https://ethz.ch/content/dam/ethz/special-interest/infk/chair-program-method/pm/documents/Education/Theses/Constantin_M%C3%BCller_MS_Report.pdf)
- [Exact and Linear-Time Gas-Cost Analysis](https://research.facebook.com/publications/exact-and-linear-time-gas-cost-analysis/)

## Videos

- [The Move Programming Language](https://youtu.be/J1U_0exNFu0)
- [Move on Sui](https://www.youtube.com/watch?v=xMsE1X4wio4)
- [Move: A Safe Language for Programming with Money](https://www.youtube.com/watch?v=EG2-7bQNPv4&ab_channel=FieldsInstitute) - Talk from [@sblackshear](https://github.com/sblackshear) at the [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) research seminar series.
- [Formal Verification of Move Programs for the Libra Blockchain](http://www.fields.utoronto.ca/talks/Formal-verification-Move-programs-Libra-blockchain) - Talk from [@DavidLDill](https://github.com/DavidLDill) at the [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) research seminar series.
- [Move for the Masses](https://www.youtube.com/watch?v=b_2jZ4YEfWc) - Talk at the [Converge '22](https://converge.circle.com/event/4ea0d06f-3900-4b6d-a9cd-aeaedda9ef2e/summary).


## Podcasts

- [Move and Sui with Sam Blackshear from Mysten Labs](https://zeroknowledge.fm/228-2/)
- [Move AMA covering Move origin story](https://twitter.com/i/spaces/1jMKgepNOleJL)


## Security

- [SUI OBJECTS-SECURITY PRINCIPLES AND BEST PRACTICES](https://www.movebit.xyz/blog/post/Sui-Objects-Security-Principles-and-Best-Practices.html)

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
