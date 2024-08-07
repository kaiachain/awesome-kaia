# Awesome Kaia [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Kaia (KAIA) is a public blockchain designed for the metaverse, gaming, and the creator economy that delivers performance, decentralization, scalability and interoperability.

This page introduces all links related to core and ecosystem development of Kaia.

> Your contributions are always welcome! Please read the [contributing guidelines](CONTRIBUTING.md) to get started.

> DISCLAIMER: The list is updated and maintained by the Kaia Community. Use below tools and links at your own risk.

## Contents

- [Developer Communication Channels and Forums](#developer-communication-channels-and-forums)
- [Documentation](#documentation)
- [Public Endpoints](#public-endpoints)
- [Chain Data Explorers](#chain-data-explorers)
- [Wallets](#wallets)
- [SDKs](#sdks)
- [Services running on Kaia](#services-running-on-kaia)
- [API Services](#api-services)
- [Naming Services](#naming-services)
- [Development Tools](#development-tools)
- [Starter Kits](#starter-kits)
- [Useful Packages](#useful-packages)
- [Sample Apps and Examples](#sample-apps-and-examples)
- [Useful contract addresses deployed on Kaia](#useful-contract-addresses-deployed-on-kaia)
- [NFT Marketplaces](#nft-marketplaces)
- [dApp Directory Services](#dapp-directory-services)
- [Analytics](#analytics)
- [Status Pages](#status-pages)
- [Oracles](#oracles)
- [Bridges](#bridges)
- [DEXs](#dexs)
- [Governance/Voting Tools](#governancevoting-tools)
- [Community Management Tools](#community-management-tools)
- [Deployment Tools](#deployment-tools)
- [Network Testers](#network-testers)
- [Public Disclosure](#public-disclosure)
- [Miscellaneous Links](#miscellaneous-links)
- [Useful Article Links by Community Members](#useful-article-links-by-community-members)
- [Useful Article Links by Community Members in Korean](#useful-article-links-by-community-members-in-korean)
- [Video lectures and presentations in Korean](#video-lectures-and-presentations-in-korean)
- [Presentations](#presentations)

## Developer Communication Channels and Forums
- [Discord](https://discord.gg/aY8mrCGANk)
- [Kaia Developer Forum](https://devforum.kaia.io/)
- [Kaia Developers Facebook](https://www.facebook.com/groups/klaytndevelopers)
- [Korea Blockchain Meetup](https://www.meetup.com/ko-KR/korea-blockchain-meetup/)

## Documentation
- Kaia Docs ([EN](https://docs.kaia.io/), [한](https://ko.docs.kaia.io/)) - Introduces Kaia, an enterprise-grade, service-centric platform that brings user-friendly blockchain experience to millions of users.
- [KIPs](https://github.com/kaiachain/kips) - Describe standards for the Kaia platform, including core protocol specifications, client APIs, and contract standards.
- [Tech Blog Article List](https://github.com/kaiachain/awesome-kaia/blob/main/tech-blog.md) - Contains Latest articles and updates from the Kaia Tech Blog.

## Public Endpoints
- By [Kaia Foundation](https://www.kaia.io/)
  - As is: [https://public-en.node.kaia.io](https://public-en.node.kaia.io) 
- By [BlockPI Network](https://blockpi.io/)
  - As is: [https://klaytn.blockpi.network/v1/rpc/public](https://klaytn.blockpi.network/v1/rpc/public)
  - To Be: 
- By [All That Node](https://allthatnode.com/)
  - As is: [https://klaytn-mainnet.g.allthatnode.com/full/evm](https://klaytn-mainnet.g.allthatnode.com/full/evm)
  - To Be: 
- By [Pocket network](https://docs.pokt.network/)
  - As is: [https://klaytn-rpc.gateway.pokt.network/](https://klaytn-rpc.gateway.pokt.network/)
  - To Be: 
- For more details please refer [here](https://docs.kaia.io/references/public-en/) - Contains list of public json rpc endpoints.

## Chain Data Explorers
- [Klaytnfinder](https://klaytnfinder.io/)
- [OKLink Klaytn Explorer](https://www.oklink.com/klaytn)
- [KlaytnScope](https://scope.klaytn.com/)
- [LIVE COIN WATCH](https://www.livecoinwatch.com/?platforms=KLAY)
- [Bitquery](https://explorer.bitquery.io/klaytn)

## Wallets
- Mobile Wallets
  - [Klip](https://klipwallet.com/) - [Documentation](https://docs.klipwallet.com/)
  - [D'CENT](https://dcentwallet.com/)
  - [nBlocks](https://nblocks.io/)
  - [Huobi Wallet](https://www.huobiwallet.com/en/)
  - [Token Pocket](https://www.tokenpocket.pro/)
  - [Biport](https://biport.io/)
  - [Alphawallet](https://alphawallet.com/)
  - [BitKeep](https://bitkeep.com/)
  - [Trustkeys](https://trustkeys.network/)
  - [Nest](https://nes.tech/)
  - [Math Wallet](https://mathwallet.org/ko-kr/)
  - [Favorlet](https://favorlet.io/)
  - [ABC Wallet](https://myabcwallet.io/en/)
  - [1inch](https://play.google.com/store/apps/details?id=io.oneinch.android&hl=en&gl=US)
  - [Burrito](https://www.burritowallet.com/)
  - [Midas Protocol](https://midasprotocol.io/)
  - [OKX wallet](https://www.okx.com/web3)
  - [Bit2Me](https://bit2me.com/suite/wallet-klaytn)
- Browser Extension Wallets
  - [Kaikas](https://chrome.google.com/webstore/detail/kaikas/jblndlipeogpafnldhgmapagcccfchpi) - [Documentation](https://docs.kaikas.io/)
  - [Dekey](https://chrome.google.com/webstore/detail/dekey/cekclnkpicopjiagjphfoahcinhmgbjp)
  - [COIN98](https://chrome.google.com/webstore/detail/coin98-wallet/aeachknmefphepccionboohckonoeemg)
  - [web3auth](https://web3auth.io/) - [Documentation](https://web3auth.io/docs/connect-blockchain/klaytn)
  - [ABC Wallet](https://chrome.google.com/webstore/detail/abc-wallet/mlhakagmgkmonhdonhkpjeebfphligng)
- Hardware Wallets
  - [D'CENT](https://dcentwallet.com/products/BiometricWallet)
  - [SafePal](https://www.safepal.com/en/)
- Multisig Wallet 
  - [Kaia Safe](https://safe.kaia.io/welcome)

## SDKs
- [kaiasdk](https://github.com/kaiachain/kaia-sdk) - a set of SDKs to interact with Kaia by extending existing web3 SDKs.
- [caver-js](https://github.com/kaiachain/caver-js) - JavaScript client that allows developers to interact with a Kaia node.
- [caver-java](https://github.com/kaiachain/caver-java) - Java client that allows developers to interact with a Kaia node.
- [tatum-js](https://github.com/tatumio/tatum-js) - JavaScript client to interact with a Kaia node through Tatum APIs.
- [mint.club](https://sdk.mint.club/) - SDK to create and trade bonding curve tokens / NFTs with automated liquidity.


## Services running on Kaia
- [Services running on Kaia](https://github.com/kaiachain/awesome-kaia/blob/main/Services.md) - Contains public services running on Kaia.

## API Services
- [Kaia API Service](https://www.klaytnapi.com/) - Documentation ([EN](https://docs.klaytnapi.com/v/en/), [한](https://docs.klaytnapi.com/)).
- [Public JSON-RPC Endpoints](https://docs.kaia.io/references/public-en/)
- [JSON-RPC Endpoint Services (Paid Plans)](https://docs.kaia.io/references/public-en/#rpc-service-providers)
- [Tatum](https://tatum.io/) - [Documentation](https://docs.tatum.io/reference/klaytngeneratewallet)
- [Henesis](https://henesis.io/en) - [Documentation](https://docs.henesis.io/docs)
- [Bitquery](https://bitquery.io/blog/klaytn-api)
- [BlockPI](https://blockpi.io/)
- [Octet](https://octet.im/product/) - Documentation ([EN](https://docs.octet.im/v2.0-eng/docs), [한](https://docs.octet.im/docs)).
- [BlockSDK](https://blocksdk.com/) - [Documentation](https://documenter.getpostman.com/view/20292093/Uz5FKwxw#7b85cc54-fd97-4a30-9a6b-06808938c1bc)

## Naming Services
- [KNS](https://klaytn.domains/) - [Documentation](https://docs.klaytn.domains/)

## Development Tools
- [Remix](https://remix.ethereum.org/) - No-setup tool with a GUI for developing smart contracts.
- [Hardhat](https://hardhat.org/) - Development environment, testing framework for blockchains using the EVM.
- [Foundry](https://github.com/foundry-rs/foundry)
- [thirdweb](https://thirdweb.com/) - Contains powerful dev tools and managed infrastructure services. Cypress/Baobab can be added by configuring the network in the menu.
- [Kaia Contract Wizard](https://wizard.kaia.io/) - Interactive smart contract generator.

## Starter Kits
- [Smart contracts for Kaia](https://github.com/kaiachain/kaia-contracts) - Library for secure smart contract development.
- [Kaia-dapp-mono](https://github.com/kaiachain/kaia-dapp-mono) - Boilerplate code for frontend and backend that are helpful to building blockchain applications on Klaytn.
- [kaia-0.5.6-Boilerplate](https://github.com/GaeJobBu/klaytn-0.5.6-Boilerplate) - Klaytn smart contract development environment boiler plate.
- [kaia-batch-transfer](https://github.com/GaeJobBu/klay-batch-transfer) - Klaytn batch transfer based on smart contracts.
- [kip37-snapshot](https://github.com/GaeJobBu/kip37-snapshot) - Creates a snapshot of any KIP37 token in JSON or CSV format.

## Useful Packages
- Wrapped-kaia standard - [GitHub](https://github.com/klaytn/canonical-wklay), [Npm](https://www.npmjs.com/package/canonical-wklay) Standard for wrapped KAIA for dapps.
  - Mainnet - : [0x19Aac5f612f524B754CA7e7c41cbFa2E981A4432](https://scope.klaytn.com/account/0x19Aac5f612f524B754CA7e7c41cbFa2E981A4432?tabId=txList)
  - Kairos Testnet - : [0x043c471bEe060e00A56CcD02c0Ca286808a5A436](https://baobab.scope.klaytn.com/account/0x043c471bEe060e00A56CcD02c0Ca286808a5A436?tabId=txList)

## Sample Apps and Examples
- Kaia Online Toolkit - [Website](https://toolkit.kaia.io/), [GitHub](https://github.com/kaiachain/kaia-online-toolkit) An Easy Interactive UI tool containing code snippets for Kaia SDK(caver-js) utilization.
- NFT Minting example - [FE](https://github.com/klaytn/klaytn-nft-minter-frontend), [BE](https://github.com/klaytn/klaytn-nft-minter-backend)
<!-- - [caver-js-examples](https://github.com/klaytn/caver-js-examples)
- [caver-java-examples](https://github.com/klaytn/caver-java-examples) -->
- [CN Staking contract tests](https://github.com/klaytn/cn-staking-contract-tests)
- [NFT Transfer on Cypress using Metamask](https://github.com/Yeonju-Kim/nft-transfer-klaytn)
- Soulbound token - Solidity smart contracts, deployment and test scripts for Soulbound token (SBT).
  - [Contract repository](https://github.com/bisonai/sbt-contracts)
  - [Contract npm package](https://www.npmjs.com/package/@bisonai/sbt-contracts)
  - [Typescript interface repository](https://github.com/bisonai/sbt-js)
  - [Typescript interface npm package](https://www.npmjs.com/package/@bisonai/sbt-js)

## Useful contract addresses deployed on Kaia
- [MultiCall Contract](https://github.com/makerdao/multicall) - Aggregates multiple constant function call results into one.
  - [Cypress](https://scope.klaytn.com/account/0x5f5f0d1b9ff8b3dcace308e39b13b203354906e9) 
  - [Kairos Testnet](https://baobab.scope.klaytn.com/account/0x40643B8Aeaaca0b87Ea1A1E596e64a0e14B1d244)
- [Kaia-multicall](https://github.com/inevitable-changes/klaytn-multicall)

## NFT Marketplaces
- [OpenSea](https://opensea.io/)
- [klaymint](https://www.klaymint.io/)
- [XClusive](https://xclusive.market/marketplace/collections?Chain=KLAYTN)
 
## dApp Directory Services
- [DappRadar](https://dappradar.com/rankings/protocol/klaytn)
- [State of the dApps](https://www.stateofthedapps.com/ko/rankings/platform/klaytn)

## Analytics
- [FlipSide](https://flipsidecrypto.xyz/)
- [DEX screener](https://dexscreener.com/klaytn)
- [DefiLlama](https://defillama.com/chain/Klaytn)
- [CryptoQuant](https://cryptoquant.com/asset/klay/summary)
- [NFT Stat](https://nftstat.io)


## Status Pages
- [Kaia Network Status Page](https://status.klaytn.foundation)
- [Kaia API Service Status Page](https://status.klaytnapi.com)
- Public Endpoint Status Pages
  - [DSRV](https://www.allthatnode.com/klaytn.dsrv)
 
## Oracles
- [Orakl](https://www.orakl.network/)
- [Witnet](https://feeds.witnet.io/klaytn)
- [SupraOracles](https://data.supraoracles.com/networks/klaytn)
- [KlayOracle](https://www.klayoracle.com/)

## Bridges
- [Stargate](https://stargate.finance/)
- [Synapse Protocol](https://synapseprotocol.com/landing)
- [Six Bridge](https://bridge.six.network/)
- [Wormhole](https://www.portalbridge.com)
- [cBridge](https://cbridge.celer.network/8217/1/DAI)
- [AllBridge](https://app.allbridge.io/bridge?from=KLAY&to=ETH&asset=ABR)
- [XY Finance](https://app.xy.finance/)

## DEXs
- [KaiaSwap](https://kaiaswap.org/trade/swap)
- [Capybara](https://www.capybara.exchange/)
- [Dragon Swap](https://dgswap.io/)
- [KLAYswap](https://klayswap.com/)
- [Pangea Swap](https://www.pangeaswap.com/)
- [PalaDEX](https://pala.io/dex/pool)
- [Swapscanner](https://swapscanner.io)
- [1inch](https://app.1inch.io/#/8217/simple/swap/KLAY/KDAI)
- [Open Source Dex](https://dex.baobab.klaytn.net/) 
    - [Dex Frontend](https://github.com/kaiachain/open-dex-frontend)
    - [Dex Dashboard](https://github.com/kaiachain/open-dex-dashboard)
    - [Dex Contracts](https://github.com/kaiachain/open-dex-contracts)
    - [Dex Subgraph](https://github.com/kaiachain/open-dex-subgraphs)
    
## Governance/Voting Tools 
- [XDAO](https://www.xdao.app/) - Smart DAO builder that allows you to create DAO and safely manage collective crypto assets using a clear and convenient interface.
- [Snapshot.org](https://snapshot.org/#/?type=networks&q=klaytn) - Voting tool based on the IPFS decentralized storage system.

## Community Management Tools
- [Discord Bot](https://bot.metaoneer.club/)

## Telegram Trading Bots
- [Arrow Bot](https://web.telegram.org/k/#@ArrowTradingBot)

<!-- ## Deployment Tools
- [Local Network Deployment Tool using docker-compose](https://github.com/klaytn/local-klaytn-deploy)
- [ServiceChain Deployment Tool](https://github.com/klaytn/servicechain-deploy)
- [Kaia Terraform Modules](https://github.com/klaytn/servicechain) - Terraform modules set to create various resources regarding Kaia.
- [Kaia Ansible Modules](https://github.com/klaytn/klaytn-ansible) - Ansible modules for installing and using Kaia.
- [Kaiaspray](https://github.com/klaytn/klayspray) - Deploys Kaia network in various cloud providers.
 
## Network Testers
- [Kaia Network Deployment and Integration Tester](https://github.com/klaytn/klaytn-deploy) - Contains deployment details, monitoring and load testing using Locust.
- [Kaia Node RPC tester](https://github.com/klaytn/klaytn-rpc-tester) - Checks basic operations of Kaia RPC/WebSocket APIs.
- [Kaia Load Tester](https://github.com/klaytn/klaytn-load-tester) - Load tester using boomer library and it is written in golang. -->


## Useful Article Links by Community Members
- [Building with Kaia](https://oxpampam.hashnode.dev/building-with-klaytn-what-is-klaytn-and-how-to-get-started-as-a-developer)
- [Beginner's Guide To Kaikas Wallet](https://oxpampam.hashnode.dev/the-beginners-guide-to-kaikas)
- [Create and Deploy your First Smart Contract with Kaia IDE](https://oxpampam.hashnode.dev/create-and-deploy-your-first-smart-contract-with-klaytn-ide)
- [How To Create and Deploy an ERC20 Token on Kaia](https://oxpampam.hashnode.dev/how-to-create-and-deploy-an-erc20-token-on-klaytn)
- [Building a Kaia bApp with Caver-Js](https://oxpampam.hashnode.dev/building-a-klaytn-bapp-with-caver-js)
- [How to set up an Hardhat project for Kaia](https://oxpampam.hashnode.dev/how-to-set-up-a-hardhat-project-for-klaytn)
- [Kaia Kairos Faucet: Solidity Smart Contract](https://oxpampam.hashnode.dev/klaytn-baobab-faucet-solidity-smart-contract)
- [Beginner's guide on how to add Kaia to Metamask](https://oxpampam.hashnode.dev/beginners-guide-on-how-to-add-klaytn-to-metamask)

## Useful Article Links by Community Members in Korean
- [개발없이 Kaia NFT 발행하기 - Klay-Gacha-Machine](https://medium.com/@eklee808/%EA%B0%9C%EB%B0%9C%EC%97%86%EC%9D%B4-%ED%81%B4%EB%A0%88%EC%9D%B4-%EC%A0%9C%EB%84%88%EB%9F%AC%ED%8B%B0%EB%B8%8C-nft-%EB%B0%9C%ED%96%89%ED%95%98%EA%B8%B0-1-klay-gacha-machine-eb17496e8b22)

## Video lectures and presentations in Korean
- [Video lectures and presentations in Korean](https://github.com/klaytn/awesome-klaytn/blob/main/contents_kr.md)

## Presentations
- [(2023/10/10) KlayMakers23 Workshop](https://dorahacks.io/hackathon/klaymakers23/workshop)
- [(2022/08/19) KlayMakers22 Workshop](https://dorahacks.io/hackathon/klaymakers22/workshop)
- [(2022/03/03) [Klaytn - Covalent Joint Developer Webinar] Covalent Unified API Integrated with Klaytn Ecosystem](https://www.youtube.com/watch?v=BM3QzKEVi2U)
- [(2022/02/12) [Paul Barron Network Interview] Klaytn interview | Dynamic NFTs & Layer 1 Metaverse](https://www.youtube.com/watch?v=HK64ecRSlpg)
- [(2021/08/05) [Smart Contract Summit #1] Klaytn Tech Stack for NFT](https://www.smartcontractsummit.io/)
- [(2019/10/08) [ETH Devcon5] Extending Ethereum's Account and Transaction Models in Klaytn](https://archive.devcon.org/archive/watch/5/extending-ethereums-account-and-transaction-models-in-klaytn/?tab=YouTube)
- [(2019/10/08) [KryptoOsaka] Klaytn - The Ground for All Blockchain Services](https://www.eventbrite.com/e/kryptoosaka-buidling-projects-of-east-and-west-tickets-74307566933#)
- [(2018/11/29) [BUIDL Seoul 2018] Exploiting Parallelism with Lightweight Threads in Klaytn](https://buidl.kr/)
