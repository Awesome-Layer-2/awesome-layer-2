# Awesome Layer 2  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<h2 id="1"> Quick Guide</h2>

### [Introduction to Layer 2 solutions](#2) 

### [All about Layer 2:General analysis about Layer 2 solutions](#5)

### [The Layer 2 projects](#3) 

* [state channel](#11)

* [sidechain](#12)

* [off chain computation](#13)

### [contribute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/contributing.md)


<h1 id="2">INTRO</h1>

Introductions of layer 2 solutions: why we need layer 2 instead of a single blockchain.

## Introduction to Layer 2 solutions

Blockchain technology is facing a trilemma, i.e. from decentralization, security and scalability. Only two of the three features could be obtained in a single blockchain. **At the heart of the scaling problem is a tradeoff between "large user-base " and "large set of validators".**

Public blockchains need all the validators reach consensus, to ensure decentralization and security, which leads to the problem: the throughput of the whole blockchain is equal to a single validator. Fundamentally, blockchains just don’t scale.

Now there are three scalability technologies are on their way:

1. Each validator processes more transactions and improve the throughput of the blockchain, by introducing optimized blockchain protocols.（i.e DAG, Hashgraph, Avalance, etc). 

2. By using sharding technology, each shard process it's own transaction. 

3. **Layer 2 solutions, which will move most of the work off chian. These will be the main topic of this repo.**

For the first solutions, by optimizing the blockchain protocols, then only computer with better processing power can act as validator. For those home - use computers, they even can't download transaction if the throughput reach 5000 transactions per second. And storage comes to be a problem afterward.

As for Sharding, it's not mature yet. There are different issues concerning 4 level of sharding: from the computation level, network level, storage level and consensus level. These issues are also cross shard problem like [train and hotel problem](https://github.com/ethereum/wiki/wiki/Sharding-FAQs#what-is-the-train-and-hotel-problem), those problems are not solved yet.

Off chain scaling solutions are mature technologies for scaling blockchain.It was first introduced by Lighting Network in 2016. From our perspective, **public blockchain is so far the most efficient way to reach global consensus, but it is also the slowest database as well.** Thus we should let blockchain do what they should do, i.e. ensure security and decentralization. Other features like scalability, privacy and so on could be done through off chain scaling solutions, to fit the demand of different industries and applications.

Here are two main considerations behind off chain scaling solutions: 

**1. Not every thing needs to reach a global consensus.**

**2. Public blockchain should just do what they should, to guarantee public verifibility.**

Nowadays, there are several branches of off chain scaling solutions: 
1. [State Channels](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#state-channels)

2. [Sidechain (Plasma)](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#sidechains)

3. [Off chain computation(Truebit,TEE)](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#off---chain-computation)

We will introduce them one by one in the future.If you have anything to add here, [know how to contribute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/contributing.md)

In this repo, we use “Layer 2” to refer off chain scaling solutions. The public blockchain which guarantees the security and decentralization of the network is called "Layer 1", these names are already reach consensus inside the industry.

We boldly predict that in the future there will be variety of Layer 2 developers, they will come up with their Layer 2 solutions according to real world demand and their understanding of the technology.

This repo is designed for the future of Layer 2.

<h1 id="3">Project lists</h1>

All the layer 2 projects is here, click the project and you will jump to the section of this project,all you need to know about this project will be there.

## Research Institute
 * [Finality Labs](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#finality-labs)
 
 * [L4](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#l4)


<h2 id="11"> State Channels</h2>
 
* [Counterfactual](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#counterfactual)
 
* [Celer Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#celer-network)
 
* [Liquidity Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#liquidity-network)
 
* [Lighting Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#lighting-network)
 
* [Raiden Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#raiden-network)
 
* [Perun](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#perun)
 
* [Magmo](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#magmo)
 
* [FunFair](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#funfair)
 
* [Pisa](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#pisa)
 
* [Connext](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#connext)
 
* [Machionmy](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#machionmy)
 
* [Sprites](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#sprites)
 
* [SpankChain](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#spankchain)
 
* [Parsec](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#parsec)



<h2 id="12"> Sidechains</h2>
 
* [Loom Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#loom-network)
 
* [POA Network](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#poa-network)
 
* [Plasma](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#plasma)
 
* [SKALE](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#skale)
 
* [OmiseGo](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#omisego)
 
* [Livepeer](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#livepeer)

* [AlphaWallet](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#alphawallet)
 

<h2 id="13">Off - chain computation</h2>

* Truebit

* TEEX

* STARK

* [Oraclize](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#Oraclize)


* [Transmute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/README.md#Transmute)


<h1 id="4">Project contents</h1>

## Finality Labs

**Intro**: Finality Labs is a community of researchers, devs, modders, hackers, and gamers uniting to experiment with and create new applications of cryptographic systems.

### Basic Infor
* [Website](https://finalitylabs.io/)

* [Github](https://github.com/finalitylabs)

* [Medium](https://medium.com/finality-labs)：It's empty！

* [Twitter](https://twitter.com/finalitylabs)


### Product/document

* [Set-Payment paper](https://finalitylabs.io/static/media/SetPaymentChannels.8a29d449.pdf) 

* [Applied State Channels and Plasma (WIP)](https://docs.google.com/document/d/15LdH-YL3syBHdHlwCfUHou6XFvg5lXBKtrAFp5bG1Pc) :This paper will outline Finality Labs‘ protocols for complex state systems that address common blockchain applications, a state-channels and Plasma approach to payments, exchanges, and games.


### Articles

* [Finality in Blockchain Consensus
](https://medium.com/mechanism-labs/finality-in-blockchain-consensus-d1f83c120a9a)


### Videos

* [The DApp Digest | Nathan Ginnever of Finality Labs](https://www.youtube.com/watch?v=zvn30pX9_rs)

* [The DApp Digest | Nathan Ginnever | Founder of BlockEDU and Finality Labs ](https://www.youtube.com/watch?v=awmxEr2B-Z0)

* [Finality in Blockchain Consensus - by Alexis Gauba - Mechnism Labs & She256](https://www.youtube.com/watch?v=efyiPhZvqOA)

* [The Future of Layer 2 ----Prague Edition](https://www.youtube.com/watch?v=htyJrK9VuCc&t=1144s)

Click [here and back to the list](#4)

## L4
 L4 Venture is building Web3(a decentralized web that removes middlemen and incentivizes users to contribute)
 
 **Projects:**
 
* [Counterfactual](https://github.com/Awesome-Layer-2/Project#counterfactual);

* [ETHglobal](https://ethglobal.co/);

* [ETHprize](http://ethprize.io/);

* [The Stable Fund](https://stable.fund/);

* [ETHER CAPITAL](https://ethcap.co/).
 
* [Website](https://l4.ventures/)
 
* [Medium-L4 Blog](https://medium.com/l4-media)

Click [here and back to the list](#4)

## Counterfactual

**Intro:** Counterfactual is a object-oriented generalized state channel framework lead by [L4](https://l4.ventures/).

### Product/Document

* [Website](https://www.counterfactual.com/)

* [Whitepaper](https://l4.ventures/papers/statechannels.pdf)

* [Specifications](https://specs.counterfactual.com/)

* [Github](https://github.com/counterfactual)

* [Medium](https://medium.com/statechannels)

### Article

* [Counterfactual:Generalized State Channels on Ethereum](https://medium.com/statechannels/counterfactual-generalized-state-channels-on-ethereum-d38a36d25fc6) :Introduction and announcement of the project Counterfactual.

* [Generalized State Channels on Ethereum](https://medium.com/l4-media/generalized-state-channels-on-ethereum-de0357f5fb44): A state channel concept writen by Liam Horne and Jeff Coleman before the project begins.Here talks about their objects and design purpose.

* [State Channel Applications](https://medium.com/statechannels/state-channel-applications-1f170e7d542e) :A discussion about state channel applications and what Counterfactual do:  splits the state channel resolution logic from the application logic. 

* [Channelising MixEth with the Counterfactual framework](https://medium.com/pisa-research/channelising-mixeth-with-the-counterfactual-framework-b53b7f839cc) :Writen by Chris Buckland,researcher from PISA. About a jounary of writing an application(MixEth Protocol) using Counterfactual.

* [State Channels for Dummies: Part 5(Generalized State Channels / Counterfactual)](https://medium.com/blockchannel/state-channels-for-dummies-part-5-6238f83f8da3) :About mechanism of generalized state channels writen by Eric Olszewski.

* [A State Channels Adventure with Counterfactual Rick! (Part 1)](https://medium.com/spankchain/a-state-channels-adventure-with-counterfactual-rick-part-1-ce68e16252ea)

* [General State Channels](https://www.youtube.com/watch?v=Ao0tj0HcIcc):Counterfactual Instantiation Code Walkthrough

Click [here and back to the list](#4)

## Celer Network

### Basic Information

* [Website](https://www.celer.network/)

* [Medium](https://medium.com/@CelerNetwork)

* [GitHub](https://github.com/celer-network)

* [Youtube](https://www.youtube.com/channel/UC8-k15uAVa5vfpLbh1gU_hA/videos)

* [Telegram](https://t.me/celernetwork)

* [Reddit](https://www.reddit.com/r/celernetwork/)

* [Twitter](https://twitter.com/celernetwork)

* [Founder — Mo Dong Twitter](https://twitter.com/no89thkey)

### Product/Document

* [White Paper](https://www.celer.network/doc/CelerNetwork-Whitepaper.pdf)

* [cWallet](https://get.celer.app/)

### Articles
* [Celer Network：Bring Internet Scale to Every Blockchain](https://medium.com/celer-network/celer-network-bring-internet-scale-to-every-blockchain-b8f3c9a2d270)

* [Celer Network MVP: The Most Advanced State Channel Full-Stack Solution](https://medium.com/celer-network/celer-network-mvp-the-most-advanced-state-channel-full-stack-solution-21df46234e42)

* [Celer Network Off-Chain Crypto Economics](https://medium.com/celer-network/celer-network-off-chain-crypto-economics-13999b11e635)

### Videos

* [Celer Network Full Stack MVP Demo](https://www.youtube.com/watch?v=GoFnWPyEJ18)

* [Celer Network Layer-2 Crypto Economics Mechanism Design](https://www.youtube.com/watch?v=K2FxqAmrYD8)

* [SF Ethereum Developers Meetup - Celer Network with Mo Dong](https://www.youtube.com/watch?v=P_meMqDspNI)

* [Celer Network Review](https://www.youtube.com/watch?v=VsFGz4O7i5U)

* [aelf x Celer Network Community AMA](https://www.youtube.com/watch?v=5b3sNrTf210)

* [Celer Network Interview 1](https://www.youtube.com/watch?v=uU3jp_JBZ7M&t=67s)

* [Celer Network Interview 2](https://www.youtube.com/watch?v=KJwXWDmSn3c) 

* [Celer Network Interview 3](https://www.youtube.com/watch?v=fcfybxi6W30) 

Click [here and back to the list](#4)

## Liquidity Network

### Basic Information

* [Website](https://liquidity.network/)

* [GitHub](https://github.com/liquidity-network)

* [Medium](https://medium.com/@liquidity.network)

* [Youtube](https://www.youtube.com/channel/UCun8UadDUB5-lBVUli_R6GA/videos)

* [Telegram](https://t.me/liquiditynetwork)

* [Twitter](https://twitter.com/liquiditynet)

* [Reddit](https://www.reddit.com/r/liquiditynetwork/)

* [Founder—Arthur Gervai Twitter](https://twitter.com/HatforceSec)

### Product/Document

* [White Paper](https://liquidity.network/whitepaper_Liquidity_Network.pdf)

* [Apple Wallet Dowland](https://itunes.apple.com/ch/app/liquidity-network-wallet/id1395924630)

* [Android Wallet Dowland](https://play.google.com/store/apps/details?id=com.liquiditynetwork.wallet&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)

* [REVIVE Paper](https://eprint.iacr.org/2017/823.pdf)

* [NOCUST Paper](https://liquidity.network/NOCUST_Liquidity_Network_Paper.pdf):NOCUST is a specification for secure N-party payment hubs introduced by Liquidity Network

### Articles

* [Noucst 101](https://medium.com/p/2acfbc0be47b?source=user_profile---------2------------------)

* [Liquidity Network Token Model](https://medium.com/liquidity-network/liquidity-network-token-model-d22861ab9faa)

* [Liquidity Network Mobile App on Mainnet](https://medium.com/liquidity-network/liquidity-network-mobile-app-on-mainnet-f95bd87ffec9)

### Videos

* [Liquidity Network Interview 1](https://www.youtube.com/watch?v=BDX9VWBFySE) 

* [Liquidity Network Interview 2](https://www.youtube.com/watch?v=vZ3vj5HU3Ec)

* [What is Liquidity Network](https://www.youtube.com/watch?v=pYXP-X-6yxI)

* [How Liquidity Wallet Work](https://www.youtube.com/watch?v=43DFoNiE5mQ)

* [A speech on Zurich ——Non-Custodial Financial Intermediaries](https://www.youtube.com/watch?v=-s4_frwlLj0)

* [Liquidity.Network and REVIVE](https://www.youtube.com/watch?v=emZTtmiR-AY)

* [Wallet Demo](https://www.youtube.com/watch?v=jM9VWRBbqtU)

Click [here and back to the list](#4)


## Lighting Network

### Basic Information

* [Website](https://lightning.network/#intro)

* [GitHub](https://github.com/lightningnetwork)

* [Reddit](https://www.reddit.com/r/lightningnetwork/)

* [Medium](https://medium.com/@lightingnetwork) 

* [Telegram](https://t.me/LightningNetwork)

* [Founder—Joseph Poon Twitter](https://twitter.com/jcp)

* [The Bitcoin Lightning Network](https://lightning.network/lightning-network-paper.pdf) :WP of Lighting Network

### Product/Document

* [Summary](https://lightning.network/lightning-network-summary.pdf)

* [Design Overview](http://lightning.network/docs/)

* [White Paper](https://lightning.network/lightning-network-paper.pdf)

* [LIGHTNING NETWORK EXPLORER[TESTNET] ](https://explorer.acinq.co/#/)

* [SF Bitcoin Devs Presentation Slides](https://lightning.network/lightning-network.pdf)

* [SF Bitcoin Social Presentation Slides](https://lightning.network/lightning-network-presentation-sfbitcoinsocial-2015-05-26.pdf)

* [Time and Bitcoin Presentation Slides](https://lightning.network/lightning-network-presentation-time-2015-07-06.pdf)

### Articles

* [What Is Lightning Network And How It Works](https://cointelegraph.com/lightning-network-101/what-is-lightning-network-and-how-it-works)

* [Lightning Network is the Future of Bitcoin ](https://medium.com/breez-technology/the-future-of-bitcoin-3187aefe2746) 

* [Understanding Lightning Network using an Abacus ](https://medium.com/breez-technology/understanding-lightning-network-using-an-abacus-daad8dc4cf4b)

* [Mathematical Proof That the Lightning Network Cannot Be a Decentralized Bitcoin Scaling Solution ](https://medium.com/@jonaldfyookball/mathematical-proof-that-the-lightning-network-cannot-be-a-decentralized-bitcoin-scaling-solution-1b8147650800)

* [Continued Discussion on why Lightning Network Cannot Scale ](https://medium.com/@jonaldfyookball/continued-discussion-on-why-lightning-network-cannot-scale-883c17b2ef5b)

* [Introducing Fairlayer](https://medium.com/fairlayer/introducing-failsafe-network-ea47ab476fe6)

* [Why Lightning and Raiden Networks Will Not Work](https://medium.com/fairlayer/why-lightning-and-raiden-networks-will-not-work-d1880e4bc294)

* [Lightning Protocol & The Raiden Network: A Beginner’s Guide](https://blog.springrole.com/lightning-protocol-the-raiden-network-a-beginners-guide-c9d7bc702748)

* [Lightning Network enables Unicast Transactions in Bitcoin. Lightning is Bitcoin’s TCP/IP stack.](https://medium.com/@melik_87377/lightning-network-enables-unicast-transactions-in-bitcoin-lightning-is-bitcoins-tcp-ip-stack-8ec1d42c14f5)：About working principle of Lightning Network.

* [Sparky: A Lightning Network in Two Pages of Solidity](https://www.blunderingcode.com/a-lightning-network-in-two-pages-of-solidity/)

* [Lighting Network 2.0](https://blog.theabacus.io/lightning-network-2-0-b878b9bb356e)

* [The future of lightning - Elizabeth Stark - Honeybadger 2018](https://view.ly/v/9h3Kv2gS7DIu) :Text draft of a presentation by Elizabeth Stark. About Lighting Network's history and overview.


### Videos

* [Explain lighting Network](https://www.youtube.com/watch?v=rrr_zPmEiME)

* [Lightning Network Explained Simply](https://www.youtube.com/watch?v=pBh4DcM-0pg)

* [What is the Lightning Network?](https://www.youtube.com/watch?v=k14EDcB-DcE)

* [SF Bitcoin Devs Seminar: Scaling Bitcoin to Billions of Transactions Per Day（ Joseph Poon）](https://www.youtube.com/watch?v=8zVzw912wPo)

* [San Francisco Bitcoin Meetup - Lightning for the People](https://www.youtube.com/watch?v=AGHsTDrr8Ck)

* [Misconceptions about Lightning Network](https://www.youtube.com/watch?v=c4TjfaLgzj4)

* [The truth about the lightning network](https://www.youtube.com/watch?v=UYHFrf5ci_g)

Click [here and back to the list](#4)

## Raiden Network

**Intro:** The Raiden Network is an off-chain scaling solution for performing ERC20-compliant token transfers on the Ethereum blockchain. It is Ethereum's version of Bitcoin's Lightning Network, enabling near-instant, low-fee, scalable, and privacy-preserving payments.

### Basic Information

* [Website](https://raiden.network/)

* [Twitter](https://twitter.com/raiden_network)

* [Medium](https://medium.com/raiden-network)

* [GitHub](https://github.com/raiden-network)

* [Reddit](https://www.reddit.com/r/raidennetwork/)

* [Youtube](https://www.youtube.com/channel/UCoUP_hnjUddEvbxmtNCcApg)

* [Dev chat](https://gitter.im/raiden-network/raiden)

* [Twitter](https://twitter.com/raiden_network)

* [Etherscan](https://etherscan.io/token/0x255aa6df07540cb5d3d297f0d0d4d84cb52bc8e6)

* [Cofounder— Lefteris Karapetsas Twitter](https://twitter.com/LefterisJP) 

### Product/Document

* [Raiden Network Docs](http://raiden-network.readthedocs.io/en/stable/)

* [Official Raiden Network FAQ](https://raiden.network/faq.html)

* [Alpha Testing Version( Red Eyes )](https://github.com/raiden-network/raiden/milestone/13)

**Product:**

* [µRaiden](https://raiden.network/micro.html)(micro-Raiden): unidirectional micropayment channels.

* [µRaiden Github](https://github.com/raiden-network/microraiden)

* [µRaiden Docs](http://microraiden.readthedocs.io/)

* [µRaiden: Unidirectional Off-Chain Payment Framework - Loredana Cirstea](https://www.youtube.com/watch?v=E6CIgJPxgpQ) :introduction of µRaiden,how it works,and a demo of µRaiden.

### Articles

* [What is the Raiden Network?](https://raiden.network/101.html)

* [Lightning Protocol & The Raiden Network: A Beginner’s Guide](https://blog.springrole.com/lightning-protocol-the-raiden-network-a-beginners-guide-c9d7bc702748)

* [Raiden Network: Vision, Challenges and Roadmap](https://medium.com/@raiden_network/raiden-network-vision-challenges-and-roadmap-593dfa34b868)

* [Raiden Transport Explained](https://medium.com/raiden-network/raiden-transport-explained-939d7741b6f4)

* [Raiden Network Token Launch Instructions](https://medium.com/@raiden_network/raiden-token-launch-instructions-3dc5df1b2386)

* [The Raiden Network Token Auction Explained](https://medium.com/@raiden_network/the-raiden-token-auction-explained-1cc0c7946b26)

* [The Raiden Network Token Model](https://medium.com/@raiden_network/the-raiden-network-token-model-9b6ef8d0b64)

* [Raiden Network Developer Preview](https://hackernoon.com/raiden-network-developer-preview-dad83ec3fc23)

* [µRaiden: Micropayments for Ethereum](https://hackernoon.com/%C2%B5raiden-micropayments-for-ethereum-f0756cd400b3)

* [Powering Micro-Transactions through the Raiden Network](https://medium.com/@KryptoPal/powering-micro-transactions-through-the-raiden-network-971a96ff5064)

* [Why Lightning and Raiden Networks Will Not Work](https://medium.com/fairlayer/why-lightning-and-raiden-networks-will-not-work-d1880e4bc294)

* [A faster “Visa”](https://medium.com/@katerinastro/a-faster-visa-onto-the-blockchain-cfdbc7014811)

### Videos

* [Raiden Network: Getting to a production ready payment channel network by Lefteris Karapetsas](https://www.youtube.com/watch?v=v9UQlE2We50)

Click [here and back to the list](#4)

## Perun

### Basic Information

* [Website](https://www.perun.network/)

* [GitHub](https://github.com/PerunEthereum/Perun)

* [Twitter](https://twitter.com/PerunNetwork)

* [Facebook](https://www.facebook.com/perun.network/)

### Product/Document

* [Generic State Channel Networks](https://eprint.iacr.org/2018/320.pdf)

* [Perun: Virtual Payment Hubs over Cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) 

* [Perun Features](https://drive.google.com/file/d/1phBzFXt2QDEemh0JIOAI80nibe3JTRu5/view)

* [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740.pdf) 


### Articles

* [Monetha collaborates with Perun Network(News)](https://www.reddit.com/r/Monetha/comments/a5i51k/something_new_and_exciting_is_coming_monetha/))

* [Perun: virtual payment and state channel networks](https://ethresear.ch/t/perun-virtual-payment-and-state-channel-networks/1685)

### Videos

* [Perun: Virtual Payment and State Channel Networks (Devcon4)](https://www.youtube.com/watch?v=cgeELCtqE2s)

* [PERUN: Virtual Payment Hubs over Cryptographic Currencies](https://www.youtube.com/watch?v=hFD1YaYVD6c)

* [General state channel networks](https://www.youtube.com/watch?v=kBptBui1wYs)

Click [here and back to the list](#4)

## Magmo

### Basic Information

* [Website](https://magmo.com/)

* [GitHub](https://github.com/magmo/force-move-games)

* [Twitter](https://twitter.com/magmoHQ)

* [Medium](https://medium.com/magmo)

* [Cofounder—Tim Close Twitter](https://twitter.com/tomclse)

### Product/Document

* [White Paper](https://magmo.com/force-move-games.pdf)

* [First ForceMove Application-Rock Paper Scissors Game](https://demo.magmo.com/)

* [Introducing the Force-Move Games Framework for State Channels](https://medium.com/statechannels/introducing-the-force-move-games-framework-for-state-channels-b32dd953c13f)

### Articles

* [An Overview of the Force-Move Games Framework for State Channels](https://medium.com/magmo/an-overview-of-the-force-move-games-framework-for-state-channels-ff28f0962b07)

* [We launched an example state channel app](https://medium.com/magmo/we-launched-an-example-state-channel-app-17246bd98b05)

### VideoS

* [Force-Move Games - a simple framework for n-party state channel interactions](https://www.youtube.com/watch?v=CeiT4LBurh8&t=141s)

Click [here and back to the list](#4)

## FunFair

### Basic Information

* [Website](https://funfair.io/)

* [Twitter](https://twitter.com/FunFairTech)

* [Facebook](https://www.facebook.com/funfairtech/)

* [Discord](https://discordapp.com/invite/rwETqSP)

* [Reddit](https://www.reddit.com/r/FunfairTech/)

* [Telegram](https://t.me/joinchat/HtUKhUpG0FCu_X25mnU2Bg)

* [Facebook Community](https://www.facebook.com/groups/148397155706069/)

* [Discord](https://discordapp.com/invite/rwETqSP)

* [YouTube](https://www.youtube.com/channel/UCr83ZHr_jPV_ANrs8u0cGSw/videos)

### Product/Document

* [Disruptive online gaming on the blockchain that’s Fun, Fast and Fair](https://funfair.io/wp-content/uploads/FunFair-Commercial-White-Paper.pdf) 

* [FunFair Technology Roadmap and Discussion](https://funfair.io/wp-content/uploads/FunFair-Technical-White-Paper.pdf)

* [FAQ](https://funfair.io/frequently-asked-questions/)

* [GLOSSARY](https://funfair.io/glossary/)

* [Brief introduction how Funfair work](https://funfair.io/how-it-works/our-solution/)

* [Showcase—Demo](https://showcase.funfair.io/)

### Articles

* [Official gaming industry launch at ICE](https://funfair.io/ice-2018-round/)

* [Details on how to apply to participate in live beta released](https://funfair.io/how-to-apply-to-be-a-closed-beta-participant/)

* [Interview with FunFair’s CEO Jez San](https://medium.com/coinmonks/interview-with-funfairs-ceo-jez-san-bff1f6a2ad57)

* [FunFair company update — Aug 31st](https://medium.com/@aerobatic/funfair-company-update-aug-31st-72662f7576b2)

### Videos

* [Fun, fast & fair casino games powered by Ethereum](https://www.youtube.com/watch?v=Gb3RrTy40yI&feature=youtu.be)

* [FunFair @ Ethereum Community Conference: Scaling tech for mass market gaming](https://www.youtube.com/watch?v=irpu2iHDiK0)

* [FunFair - Fate Channels - the first generalised state channels to go live in a commercial product](https://www.youtube.com/watch?v=I7KFKqq9Ue0)

* [FunFair @ Enterprise Ethereum Alliance in London](https://www.youtube.com/watch?v=FOTkHRyGE6I)

* [FunFair Technologies' Fate Channels: Lessons learned Implementing State Channels (Devcon4)](https://www.youtube.com/watch?v=1ZHCpb-htMk)

Click [here and back to the list](#4)

## Pisa

### Basic Information

* [Cofounder Patrick McCorry](https://twitter.com/paddykcl?lang=zh-cn)

### Product/document

* [Pisa: Arbitration Outsourcing for State Channels](http://www0.cs.ucl.ac.uk/staff/P.McCorry/pisa.pdf) 

### Articles

* [Pisa: Arbitration Outsourcing for State Channels](https://ethresear.ch/t/pisa-arbitration-outsourcing-for-state-channels/2058)

### Videos

* [Pisa Protocol: Solving Blockchain's Arbitration Problem w/ Patrick McCorry (Founder)](https://www.youtube.com/watch?v=wPCJk5O4xwg)

* [Interview with Patrick McCorry](https://www.youtube.com/watch?v=ZdrNylN2iiY)

* [Arbitration Outsourcing for State Channels by Patrick McCorry (Devcon4)](https://www.youtube.com/watch?v=Om_zLYC8BvM):Introduction of PISA by Patrick McCorry 

Click [here and back to the list](#4)

## Connext

### Basic Information

* [Website](https://connext.network/)

* [Discord](https://discordapp.com/invite/yKkzZZm)

* [Medium](https://medium.com/connext)

* [Twitter](https://twitter.com/ConnextNetwork)

* [Cofounder Arjun Bhuptani](https://twitter.com/Arjun_Bhuptani)

### Product/Document

* [Docs](https://docs.connext.network/)

### Articles

* [Transparency Report](https://medium.com/connext/transparency-report-64c9e58e0a19)

* [Introducing Connext](https://medium.com/@arjunbhuptani/introducing-connext-ef07d4040d03)

* [What’s Next for Connext?](https://medium.com/connext/what-we-become-66605b3e22ff)

* [The Connext Vault](https://medium.com/@arjunbhuptani/the-connext-vault-4ee49df81131)

### Videos

* [Scaling Ethereum to Millions Of Users With State Channels - Connext Co-Founder Arjun Bhuptani](https://www.youtube.com/watch?v=e5Ag0dA3z9E)

* [Scaling Ethereum dApps with Ethcalate feat. Rahul Sethuram from Connext](https://www.youtube.com/watch?v=s8jRagGIoaA)

* [Episode 42: It's All About the MoneyShot, with Arjun Bhuptani](https://soundcloud.com/blockchannelshow/episode-42-its-all-about-the-moneyshot-with-arjun-bhuptani)

Click [here and back to the list](#1)

## Machionmy

### Basic Information

* [Website](https://machinomy.com/)

* [Twitter](https://twitter.com/machinomy)

* [GitHub](https://github.com/machinomy/machinomy)

* [Medium](https://medium.com/machinomy)

* [Gitter](https://gitter.im/machinomy/machinomy)

### Product/Document

* [API](https://machinomy.com/api/)

### Articles

* [We built a Generalised State Channels framework](https://medium.com/machinomy/approaching-generalised-state-channels-b0d44ec47e35)

* [Code Walkthrough for Generalised State Channels](https://medium.com/machinomy/code-walkthrough-for-generalised-state-channels-f3cdd52d8172)

* [Introduction to Vynos](https://medium.com/machinomy/explaining-vynos-91f73eeb133a)

Click [here and back to the list](#4)

## Sprites

* [Sprites and State Channels: Payment Networks that Go Faster than Lightning](https://arxiv.org/abs/1702.05812) and here is [the video with the same topic](https://www.youtube.com/watch?v=5Yyut9eFzSM) presentede by Patrick McCorry:A paper in Cornell University Library, in which they propose Sprites. Sprites can reduces the worst-case "collateral cost" that each hop along the route may incur.

Click [here and back to the list](#4)

## SpankChain

### Basic information
* [Website](https://spankchain.com/)

* [Twitter](https://twitter.com/SpankChain)

* [Medium](https://medium.com/@SpankChain)

* [GitHub](https://github.com/SpankChain)

* [Youtube](https://www.youtube.com/channel/UCRonD1SJuucnq9GJCJL_crQ)

* [Discord](https://discordapp.com/invite/S42CBSg)

* [Instagram](https://www.instagram.com/spankchain/)

* [Facebook](https://www.facebook.com/spankchain)

### Product/Document

* [Whitepaper](https://spankchain.com/static/SpankChain%20Whitepaper%20(EN).pdf)

* [Blog](https://spankchain.com/community/#blog)

### Articles
[We Got Spanked: What We Know So Far](https://medium.com/spankchain/we-got-spanked-what-we-know-so-far-d5ed3a0f38fe)

* [What are SPANK and BOOTY?](https://medium.com/spankchain/what-are-spank-and-booty-24822d5ee5c9)

### Video
* [SpankChain: Payment Channels in Production by Ameen Soleimani & Arjun Bhupati (Devcon4)](https://www.youtube.com/watch?v=Z3TCTnmd-tQ)

Click [here and back to the list](#4)

## Parsec

Click [here and back to the list](#4)

## Loom Network
**Intro**: Loom Network is building a fundamental infrastructure platform to help Ethereum scale.It allows developers to run large-scale social apps and games, and is the first Ethereum scaling solution to be live in production.

### Basic Information

* [Website](https://loomx.io/)

* [Github](https://github.com/loomnetwork)

* [Medium](https://medium.com/loom-network)

* [Youtube](https://www.youtube.com/channel/UCahF8koYeqhJ32Dn5fDr9jg)

* [Telegram](https://t.me/loomnetwork)

* [Reddit](https://www.reddit.com/r/loomnetwork/)

* [Twitter](https://twitter.com/loomnetwork)

* [FAQ](https://medium.com/loom-network/everything-you-need-to-know-about-loom-network-all-in-one-place-updated-regularly-64742bd839fe)

### Product/document

* [Loom SDK](https://loomx.io/developers/) 

* [CryptoZombies, Ethereum’s most popular DApp coding tutorial](https://cryptozombies.io/)

* [Delegatecall](https://delegatecall.com/)

* [NO whitepaper because Loom Network is too busy shipping code](https://medium.com/loom-network/loom-network-wheres-your-whitepaper-5c5c9075af72)

### Articles

* [Everything You Need to Know About Loom Network, All in One Place (Updated Regularly)](https://medium.com/loom-network/everything-you-need-to-know-about-loom-network-all-in-one-place-updated-regularly-64742bd839fe)

* [Loom SDK Projects: Axie Infinity — Collect, Breed, and Battle Fantasy Pets on the Blockchain!](https://medium.com/loom-network/loom-sdk-projects-axie-infinity-collect-breed-and-battle-fantasy-pets-on-the-blockchain-22e6fd11b410)

* [What is Loom Network (LOOM)? ](https://coinswitch.co/info/loom-network/what-is-loom-network)

### Videos

* [Loom Network AMA w/James Duffy](https://www.youtube.com/watch?v=8Evsx9cHvwA)

* [Loom Network (LOOM) - Crypto Fundamental Analysis ](https://www.youtube.com/watch?v=RstsGJREaVs)

* [WILL LOOM (LOOM) 100X?? IS IT WORTH INVESTING?](https://www.youtube.com/watch?v=rHVugUFz0Ys)

* [What is Loom Crypto? - DAppChains for Gaming?](https://www.youtube.com/watch?v=wUd2iS1BkAs)

* [Matthew Campbell on Bringing Etheruem DApps to Twitter Scale with Loom Netowrk](https://www.youtube.com/watch?v=sb2d2jJ7keI) A talk with CEO of Loom Network about what's Loom Network doing

* [LOOM Network - Using the Blockchain to Revolutionize Online Gaming](https://www.youtube.com/watch?v=XjN1rioy-GM)A video comments on Loom Network has more than 2000 views on Youtube,will help to know about Loom Network.

Click [here and back to the list](#4)

## POA Network

Click [here and back to the list](#4)

## Plasma

Click [here and back to the list](#4)

## SKALE

**Intro:** SKALE empowers Ethereum DApps to run high-speed, low-cost smart contracts in Layer 2.

### Product/Document

* [Website](https://www.skalelabs.com/)

* [Medium](https://medium.com/skale)

* [Twitter](https://twitter.com/skalelabs)

* [Telegram](https://t.me/skalefoundation)  

### Article

* [Skale Labs Overview](https://medium.com/@megadeth20/skale-labs-overview-115e75ba48d6)

### Video

* [hack.summit("blockchain") 2018 - Jack O'Holleran](https://www.youtube.com/watch?v=R4DVCEKLPWk)

* [SFBW18: Scalability: Decentralized or High Performance?](https://www.youtube.com/watch?v=VOO7oYjnA7g)

Click [here and back to the list](#4)

## OmiseGo

### Basic Information

* [Website](https://omisego.network/)

* [Twitter](https://twitter.com/omise_go)

* [Medium](https://blog.omisego.network/)

* [Reddit](http://reddit.com/r/omise_go)

* [Chat Room](https://chat.omisego.network/home)

* [Facebook](https://www.facebook.com/OmiseGO/)

* [GitHub](https://github.com/omisego)

* [Omisego/eWallet Waffle](https://waffle.io/omisego/ewallet)

### Product/document

* [Docs](https://omisego.network/token)

* [The OMG decentralized Exchange (ODEX)](https://github.com/omisego/elixir-omg/blob/develop/docs/dex_design.md)

* [eWallet](https://github.com/omisego/ewallet)

* [Tesuji Plasma](https://github.com/omisego/elixir-omg/blob/develop/docs/tesuji_blockchain_design.md)

* [First OMG Network Application: Plasma Dog](https://sadyba-plasmadog.hoard.exchange/)

### Articles

* [OmiseGO (OMG): Real Problems, Real Solutions — EVERYTHING You Need To Know](https://hackernoon.com/omisego-omg-real-problems-real-solutions-everything-you-need-to-know-8-reasons-to-buy-92551527c0a7) 

* [State of the OMG Ecosystem](https://blog.omisego.network/state-of-the-omg-ecosystem-75260c71a053)

* [The Definitive OmiseGO Beginner’s Guide](https://medium.freecodecamp.org/the-definitive-omisego-beginners-guide-f95dcdf8635c)

* [How OmiseGO will bring Plasma in everyone's daily life](https://blog.goodaudience.com/how-omisego-will-bring-plasma-in-everyones-daily-life-45c9d81a3258)

### Videos

* [Demo: eWallet admin panel](https://www.reddit.com/r/omise_go/comments/8wnhjq/demo_ewallet_admin_panel/)

* [What is OmiseGo (OMG) in a Nutshell](https://www.youtube.com/watch?v=5UmO5UsKHdk)

* [Announcing the Omise GO ewallet platform](https://www.youtube.com/watch?v=neCaG0LoKQ0)

Click [here and back to the list](#4)


## Livepeer

**intro:** The Livepeer project is building a platform for video transcoding and live video streaming for the decentralized web. It's Beta version is ready.

### Basic information

* [Website](https://livepeer.org/)

* [Medium](https://medium.com/livepeer-blog):with too many articles so if you want to find more articles you could check here.

* [WhitePaper](https://github.com/livepeer/wiki/blob/master/WHITEPAPER.md)

* [Github](https://github.com/livepeer)

### Product/document

* [Documents](https://livepeer.readthedocs.io/en/latest/)

### Articles

* [Introducing Livepeer — A Decentralized Live Video Broadcast Platform and Crypto Token Protocol](https://medium.com/@petkanics/introducing-livepeer-a-decentralized-live-video-broadcast-platform-and-crypto-token-protocol-7eb4b1de47ed)

* [Livepeer cryptoeconomics as a case study of active participation in decentralized networks](https://blog.coinfund.io/livepeer-cryptoeconomics-as-a-case-study-of-active-participation-in-decentralized-networks-19a932415e0e)

* [Livepeer + Stream = The Perfect Collab](https://blog.streamtoken.net/livepeer-stream-the-perfect-collab-e943f91222b7)

* [Token distribution in perspective: Livepeer’s merkle mine not as successful as portrayed](https://medium.com/tokenfoundry/token-distribution-in-perspective-livepeers-merkle-mine-not-as-successful-as-portrayed-1482c6564910)

* [Modeling Generalized Mining from a Fund’s Perspective: A Livepeer Case Study](https://medium.com/@visionhill_/modeling-generalized-mining-from-a-funds-perspective-a-livepeer-case-study-54dedac4fdf7)

### Video

* [Token Summit I - Show and Tell - Livepeer with Doug Petkanics](https://www.youtube.com/watch?time_continue=1&v=Vh0VxHlfxVc):Introduction of Livepeer in 7 minutes by co-founder of Livepeer.

* [Web3 Goes Live -- Livestreaming Video on the Peer-to-Peer Internet(Devcon 3)](https://www.youtube.com/watch?v=X4sK2hqz5kU):Eric(Co-foudner of Livepeer) gives a 30 minute technical presentation of how to add a live media layer to the web3 stack at Ethereum's Devcon3.(30 minutes)

* [NYC Ethereum Cryptocurrency & Consumer Media September 7th 2017](https://www.youtube.com/watch?time_continue=157&v=-40W4BRFGtE):Doug and Eric give a 10 minute presentation at the NYC Ethereum Meetup focused on Media and Cryptocurrency. The whole video is 90 minutes and contains other projects.

Click [here and back to the list](#4)

## Oraclize

### Video

* [How to design Auditable Offchain computations via Oraclize](https://www.youtube.com/watch?v=T7g8UcLlNm4)

Click [here and back to the list](#4)


## Transmute

**Intro**： configures decentralized apps to work seamlessly with both public and private clouds. Use your existing development resources to deploy superior apps in minutes.


### Basic Information：

* [website](https://www.transmute.industries/)

* [GitHub](https://github.com/transmute-industries)

* [Blog](https://medium.com/@Transmute)

* [Twitter](https://twitter.com/transmutenews)

* [Telegram](https://t.me/joinchat/ICVkOE_WTmzbGmtdl-5d8A)


### Product/Document:

* [Whitepaper](https://www.transmute.industries/whitepaper.pdf)

* [Demo](https://dashboard.transmute.network/)

### Article:

* [Inaugural Startup Class Collaborates on Enterprise Growth and Cloud Innovation at Oracle’s First U.S. Startup Hub](https://www.oracle.com/corporate/pressrelease/inaugural-austin-startup-class-101118.html)

* [Why Transmute Framwork](https://steemit.com/dapp/@sansteem/transmute-framework)

* [Announcing the Techstars Austin Class of 2018](https://www.techstars.com/content/accelerators/announcing-techstars-austin-class-2018/)

* [SXSW 2018: 10 Crypto & Blockchain Takeaways](https://hackernoon.com/sxsw-2018-10-crypto-blockchain-takeaways-d9c397b887e4)

* [Women In Bitcoin: Combatting The ‘Blockchain Bro’ Stereotype](https://bitcoinira.com/articles/women-in-bitcoin-combatting-the-blockchain-bro-stereotype)

* [Examples of People Using Crypto For Good](https://www.forbes.com/sites/devinthorpe/2018/03/18/examples-of-people-using-crypto-for-good/#23608aa34be2)

### Videos

* [Austin Ethereum Meetup: Transmute Industries Framework Demo - Blockchain Development Simplified](https://www.youtube.com/watch?v=S_pH3Qcc3QU)

* [Full Stack dApp Development with the Transmute Framework](https://www.youtube.com/watch?v=wO1dj-c89AI)

Click [here and back to the list](#4)


## AlphaWallet

**intro:** It's the Wallet Engine For The Web3 World Focusing on Usability, Scalability and Privacy

### Basic Information

* [Website](https://alphawallet.com/cn/)

* [Medium](https://medium.com/alphawallet)

* [WhitePaper]

* [Github](https://github.com/alphawallet)

* [Youtube](https://www.youtube.com/channel/UCPP12PQeQmQ4_6qXzNvZw-w/featured?view_as=subscriber)

* [Telegram](https://t.me/AlphaWalletGroup)

* [Reddit](https://www.reddit.com/r/alphawallet)

* [Twitter](https://twitter.com/Alpha_Wallet)

* [Blog](https://alphawallet.com/blog/)

* [Forum/Community](https://community.alphawallet.com/)

### Product/Document

* [ERC875 Token Factory](https://x.alphawallet.com/)

* [ERC875-Example-Implementation](https://github.com/AlphaWallet/ERC875-Example-Implementation)

* [blockchain-attestation](https://github.com/AlphaWallet/blockchain-attestation)

### Articles

* [AlphaWallet (Stormbird PTE. LTD.) Joins The Enterprise Ethereum Alliance](https://medium.com/alphawallet/alphawallet-stormbird-pte-ltd-joins-the-enterprise-ethereum-alliance-43e5ff593390): AlphaWallet joined EEA to help improving the technology and support the adoption of Ethereum in the enterprise.

* [AlphaWallet released the report of world’s first blockchain tickets experiment for 2018 World Cup](https://alphawallet.com/alphawallet-released-the-report-of-worlds-first-blockchain-tickets-experiment-for-2018-world-cup/):This is the world’s first global top sporting event ticket to use blockchain technology and one of the few blockchain based projects that is handling a real world legitimate use case.


### Videos

* [AlphaWallet CEO Victor Zhang on AsiaTech](https://www.youtube.com/watch?v=mQoamL17rsY)

* [AlphaWallet 中文品牌视频](https://www.youtube.com/watch?v=xBoudL7_R40)

* [AlphaWallet - Integration at the consumer end， Blockchain more than just cryptocurrencies](https://www.youtube.com/watch?v=5UGkxBfj5Kc)

* [Singapore Fintech Festival 2019](https://www.youtube.com/watch?v=x4ZVFp2l9vE)

Click [here and back to the list](#4)


<h1 id="5">All About Layer 2</h1>

## General contents of Layer 2

* [Making Sense of Ethereum’s Layer 2 Scaling Solutions: State Channels, Plasma, and Truebit](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4)：:Introduction of layer 2 solutions on Ethereum, after read this article writen by Josh Stark,you will really make sense of Ethereum's Layer 2 scaling solutions:State channels,Plasma, and Truebit.

* [The Importance of Layer 2](https://medium.com/mit-media-lab-digital-currency-initiative/the-importance-of-layer-2-105189f72102):The scalability problem of blockchain and come up with Layer 2 solutions.

* [Security Tokens 2.0: Some Thoughts Off-Chain vs. On-Chain Governance](https://hackernoon.com/security-token-2-0-some-thoughts-off-chain-vs-on-chain-governance-2cba087389ab)


* [Difference Between SideChains and State Channels](https://hackernoon.com/difference-between-sidechains-and-state-channels-2f5dfbd10707)

## State Channel

### Intro

* [State Channel](https://www.jeffcoleman.ca/state-channels/):About introduction of state channel by Jeff Coleman in 2015.

* [State Channel 101](https://docs.learnchannels.org/Statechannels101):Simple explaination of state channels.

* [State Channel Wiki](https://github.com/ledgerlabs/state-channels/wiki) :By Jeff Coleman,explaination of state channel and you can find more in the menu.

* [Counterfactual Terminology](https://github.com/ledgerlabs/state-channels/wiki/Counterfactual-Terminology) :Why called state channel counterfactual? Here's answer. It's the logic behind state channel.

* [Why do we need state channels?](https://docs.learnchannels.org/WhyStateChannels):An article in learnchannels. Problem of blockchain and why state channel matters.

* [An intro to state channels in depth](https://www.youtube.com/watch?v=MEL50CVOcH4&t=116s)

* [Counterfactual: Generalized State Channel](https://l4.ventures/papers/statechannels.pdf) :White paper of Counterfactual,but I highly recommanded this paper, for it explained the concept and philosophy of state channel very well. Pros and cons are also well analysed in this paper.

* [General state channel networks](https://www.youtube.com/watch?v=kBptBui1wYs)

* [State Channel Applications](https://medium.com/statechannels/state-channel-applications-1f170e7d542e)

* [10 State Channel Projects Every Blockchain Developer Should Know About](https://hackernoon.com/10-state-channel-projects-every-blockchain-developer-should-know-about-293514a516fd)

* [Counterfactual generalised state channels on Ethereum ](https://www.youtube.com/watch?v=TtaSL8WEbwY&t=153s)

* [State Channels and Blockchain Applications ](https://www.youtube.com/watch?v=mA1PD9EF3TA&t=1s)

* [State Channels by Ameen Soleimani—A paradigm shift in Ethereum Dapp development ](https://www.youtube.com/watch?v=UVRAdmycOhg&t=372s)

* [L4 | Generalized State Channels](https://www.youtube.com/watch?v=kZH_ty82jKY) 

* [State Channels Q&A](https://medium.com/@eolszewski/state-channels-q-a-fbdb6ba9c131):a brief overview of what State Channels are, the value they provide, and who is working on them in the space.

### Payment Channels

* [the state of state channels:2018 edition](https://blog.coinfund.io/the-state-of-state-channels-2018-edition-f5492134ab96): General analysis of state channel at the end of 2018, we can see channels have gone such a long way.

* [Understanding Payment Channels](https://blog.chainside.net/understanding-payment-channels-4ab018be79d4)

* [Payment Channel Contract Walkthrough](https://docs.learnchannels.org/PaymentChannelContracts)

* [Payment Channels vs. State Channels](https://docs.learnchannels.org/Paymentchannels)

* [P4: Private Periodic Payments Protocol by Liz Steininger (Devcon4)](https://www.youtube.com/watch?v=UqgBNqJ4aYM)

### Course 1：

* [State Channels For Dummies: Part 1](https://medium.com/blockchannel/counterfactual-for-dummies-part-1-8ff164f78540)：Payment Channels

* [State Channels for Dummies: Part 3](https://medium.com/blockchannel/state-channels-for-dummies-part-3-10b25f6c08b)：Multi-Hop Transactions 

* [State Channel for Dummies: Part 4](https://medium.com/blockchannel/state-channel-for-dummies-part-4-f3ba9d76c7c4)：Ledger Channels and Virtual Channels

* [State Channels for Dummies: Part 5](https://medium.com/blockchannel/state-channels-for-dummies-part-5-6238f83f8da3)：Counterfactual

### Course 2：

* [State Channels for Babies Part 1](https://medium.com/connext/state-channels-for-babies-c39a8001d9af)

* [State Channels for Babies, Part 2](https://medium.com/connext/state-channels-for-babies-part-2-76ad4538b98a)

* [State Channels for Babies, Part 3](https://medium.com/connext/state-channels-for-babies-part-3-cbda0476f0f4)

### How to create a Dapp：

* [How to create scalable dApps and smart contracts in Ethereum with State Channels step-by-step. Part 1](https://medium.com/ethereum-developers/how-to-create-scalable-dapps-and-smart-contracts-in-ethereum-with-state-channels-step-by-step-48e12481fb)

* [How to create scalable dApps and smart contracts in Ethereum with State Channels step-by-step. Part 2](https://medium.com/ethereum-developers/how-to-create-scalable-dapps-and-smart-contracts-in-ethereum-with-state-channels-step-by-step-690f71a9bf2f)

* [How to create scalable dApps and smart contracts in Ethereum with State Channels step-by-step. Final part 3](https://medium.com/ethereum-developers/how-to-create-scalable-dapps-and-smart-contracts-in-ethereum-with-state-channels-step-by-step-14318355ba79)

### Panel Talk

* [State Channel Researchers Call #1](https://www.youtube.com/watch?v=czb9Zh8P1y4):A telephone conference organized by Celer Network,in which several teams which are working on state channel communicating with each other. In this eposide, The first few calls will be about intro to every participating project and free-style Q&A.

* [State Channel Researchers Call #2](https://www.youtube.com/watch?v=Hsn17kXxVes):Counterfactual quick intro and discussion about data exchange fabric and connectivity oracle

* [State Channel Researchers Call #3](https://www.youtube.com/watch?v=TJKp7bmvA6A):Battleship and PISA intro by Patrick McCorry;Connext intro by Arjun Bhuptani;

Discussion about:
- 1.the state monitoring solutions: PISA and Celer State Guardian Network;
- 2.Discussion about Virtual Channel constructs of different projects;
- 3.Discussion about offline recipient problem;
- 4.Discussion of applicable use cases of state channel;
- 5.Discussion about operational challenges and experience of state channels.

* [State Channel Researchers Call #4](https://www.youtube.com/watch?v=XlNh7u_YHiA):Lucian Boca presenting “Threshold Signature: Improving the security of layer-2 protocols”;Discussion & QA around that

* [State Channel Researchers Call #5](https://www.youtube.com/watch?v=bPiLXOIkqBQ):Some general discussion.

* [State Channel Researchers Call #6](https://www.youtube.com/watch?v=YzomDzpLW_o)

* [State Channel Researchers Call #7](https://www.youtube.com/watch?v=5ETloioxno4)

* [State Channel Researchers Call #8](https://www.youtube.com/watch?v=8T0msU-r9ZI)

### Presentation about State channel on Devcon

* [DEVCON1: Raiden: Scaling Out With Offchain State Networks - Heiko Hees](https://www.youtube.com/watch?v=h791zjvf3uQ) :A presentation on Devcon 1(2015),and at that time the category of Raiden is called"Ethereum Sub-Protocol" rather than state channel.

* [State Channels - Ethereum is Open for Business](https://www.youtube.com/watch?v=MEL50CVOcH4): Ameen Soleimani (Now he's CEO & Co-founder of Spankchain) presents State Channels, an intro to state channels in depth.

* [Building a state channel application by Tom Close (Devcon4)](https://www.youtube.com/watch?v=_P0MTLssmA8) :A rock,paper scissors game using state channel and a demo of this game by Tome Close founder of Magmo.And he has some consideration about this experience.(A hard thing about state channel is state)

* [FunFair Technologies' Fate Channels: Lessons learned Implementing State Channels (Devcon4)](https://www.youtube.com/watch?v=1ZHCpb-htMk):Just like the title suggested.

* [General State Channels - Counterfactual Instantiation Code Walkthrough](https://www.youtube.com/watch?v=Ao0tj0HcIcc) :It'a tutorial and code overview of Counterfactual.Nathan leads a walkthrough of his counterfactual instantiation PoC code while James and Ameen follow along and ask questions.

* [The future of lightning - Elizabeth Stark - Honeybadger 2018](https://view.ly/v/9h3Kv2gS7DIu) :Text draft of a presentation by Elizabeth Stark. About Lighting Network's history and overview.

Click [here and back to the top](#1)

## Plasma

### Intro

* [Plasma Overview and Transaction Data Availability(Devcon3)](https://www.youtube.com/watch?v=yjySP0t6lYo) :Introduction of Plasma by Joseph Poon (Lighting Network)

* [The State of Plasma by David Knott & Kelvin Fitcher (Devcon4)](https://www.youtube.com/watch?v=zbgsGI7Embs):Very enthusiastic presentation of Plasma and introduction of Plasma MVP,Cash,XT and so on by David Knott & Kelvin Fitcher.

* [Practical Plasma: Gaming by Matthew Campbell (Devcon4)](https://www.youtube.com/watch?v=Epd3aMQtfZQ) :Plasma how to scale games on blockchain.

* [Smart Contracts on Plasma - Christian Reitwiessner(Devcon3)](https://www.youtube.com/watch?v=KzyqzEtEc3I) :About building smart contracts on Plasma.

* [Plasma Blockchain Scalability Framework — An Off-chain Scaling Solution for Ethereum Blockchain](https://medium.com/@neoyiukit/plasma-blockchain-scalability-framework-an-off-chain-scaling-solution-for-ethereum-blockchain-7e4ade2fdf86):Plasma's principle and different Plasma prototypes and implementations.

* [Ethereum Plasma – Ethereum’s New Scaling Strategy and Design Space](https://bitcoinbbs.org/ethereum-plasma-ethereums-new-scaling-strategy-and-design-space/):Joseph Poon, who co-authored the Lightning Network paper, further expanded on and refined the concept with Plasma on Ethereum, resulting in the conditioning of an entire new design space with its own slightly different dynamic.

### Plasma Cash

* [Plasma Cash Simple Spec](https://karl.tech/plasma-cash-simple-spec/):Overview of Plasma, how it solve some problems and some future researches to be done.

* [PoS Plasma Cash with Sharded Validation](https://ethresear.ch/t/pos-plasma-cash-with-sharded-validation/1486):Discussion about Plasma Cash with Sharded validation on Ethresearch.

* [What is Plasma? Plasma Cash?](https://medium.com/crypto-economics/what-is-plasma-plasma-cash-6fbbef784a):Introduction of Plasma Cash.

* [Plasma Cash: Towards improved Plasma constructions by Georgios Konstantopoulos (Devcon4)](https://www.youtube.com/watch?v=UKigyHGQQmQ) :Introduction of Plasma Cash by Georgios Konstantopoulos from Loom Network

### Panel Talk

* [Plasma implementers call #1](https://www.youtube.com/watch?v=_DPftmg7zR8):A telephone conference organized by Ethereum Foundation,in which several teams which are working on Plasma. In this eposide, they discussed the purpose of the group, logistics, introductions, technical details, and more!

* [Plasma implementers call #2](https://www.youtube.com/watch?v=c_Z8F6FUJxU):In this eposide,they went over a number of common Plasma questions.

* [Plasma implementers call #3](https://www.youtube.com/watch?v=JHRXrvdvLd0):In this eposide,they welcomed the Taiwan team--a group of talented engineers who came together to implement the Plasma MVP. also discussed Cosmos' challenges when exploring Plasma, a number of David's designs, and more fun stuff.

* [Plasma implementers call #4](https://www.youtube.com/watch?v=IFuxe3vL--k):In this eposide,they discussed some constructions which can be used to scale Cryptokitties! And of course update Plasma progress and have some fun technical discussions--including a new Plasma implementation from voltairelabs.

* [Plasma implementers call #5](https://www.youtube.com/watch?v=GSDc_F8xHKo):In this eposide,they discussed Plasma Cash and potential designs and research topics which are worth exploring. :)

* [Plasma implementers call #6](https://www.youtube.com/watch?v=k82L4YohW_E):In this eposide,they discussed designs for Plasma Cash with PoS and sharded validation, coin splits, exits which allow for invalid state transitions, a cryptoeconomics course, and more!

* [Plasma implementers call #7](https://www.youtube.com/watch?v=uxKcK-4PgLk):In this eposide,they discussed designs which involve sparse merkle trees, bloom filters, and some more splitting! and welcomed the Blockchain @ Berkeley crew who are working on a great Plasma Cash implementation! Yay!

* [Plasma implementers call #8](https://www.youtube.com/watch?v=2GgoYSFdTtQ):In this eposide,they discussed a whole bunch of topics, from account abstraction to Plasma XT which uses cryptoeconomic aggregate signatures (CAS) for checkpointing! Tons of fun!

* [Plasma implementers call #9](https://www.youtube.com/watch?v=sgr8bHRZUEM):In this eposide,they got to chat about simple splits in Plasma Cash, called Plasma Debit--a critical part of the Plasma Cash spec! Thanks Dan! Plus Vitalik explains instant withdrawals and Plasma with general state transitions :)

* [Plasma implementers call #10](https://www.youtube.com/watch?v=M_PtvXrrTko):In this eposide,they got to welcome Loom and Kyber to the call! Plus discussed an update to the Plasma MVP implementation which Kelvin is working on--a research version is pretty much complete! also cover Plasma Cash & debit atomic swaps, as well as Double-batched Merkle log accumulators!

* [Plasma implementers call #11](https://www.youtube.com/watch?v=w45PXH0DJa0&t=91s):In this eposide,they celebrated Loom's release of their Plasma Cash implementation, discuss state channels which are opened on and off of Plasma chains, Plasma Debit with Dan, and wrap it up with some experimental zkSNARKs talk! Amazing times!

* [Plasma implementers call #12](https://www.youtube.com/watch?v=Wbnr-9euMic):In this eposide,they discussed a wide variety of topics! We start out discussing Plasma educational materials, then move on to BLS signatures, smart contracts in Plasma, light clients, and finally we get SNARKy!

* [Plasma implementers call #13](https://www.youtube.com/watch?v=SETRL75eDgE):In this eposide,they started with discussions around nitty gritty Plasma Debit liquidity markets. Then talked about Plasma working groups to get the Plasma research done in person, plus hosting a LIVE Plasma call in devcon!chatted about Plasma XT & then Gnosis gives an awesome presentation on their batch auction Plasma construction. Fun!

* [Plasma implementers call #14](https://www.youtube.com/watch?v=lGqNTzluX10):In this eposide,they started out discussing using collateral to reduce user validation load in Plasma Cash. This gets us into triple spends & eventually we talk about the importance and difficulty of analyzing the value of in-flight transactions. Then mentioned some core cryptoeconomic principles around past provability & future accountability.

* [Plasma implementers call #15](https://www.youtube.com/watch?v=NQJfUUe2-pA):In this eposide,they dived deep into atomic swaps in both Plasma Debit and Plasma Cash. And discussed different implementation details and greifing opportunities. Next some fun discussions around watch towers!

* [Plasma implementers call #16](https://www.youtube.com/watch?v=0ApUUoWYt8U):In this eposide,they started out by discussing Plasma Cashflow which enables fungible assets on Plasma Cash! then talked about Plasma Leap, the first attempt at a general EVM Plasma!

* [Plasma implementers call #17](https://www.youtube.com/watch?v=YjTF05SeYxo):Today Vitalik reviewed his solution to the tx history proof size growth in Plasma Cash! It uses RSA accumulators & is super stylish. We are nearly there... Then they discussed Plasma Leap (even more fun!)

* [The Plasma Implementers Call](https://slideslive.com/38911962/plasma-implementers-call-live): it's a biweekly call which discusses the cutting edge of Plasma research. This is a great group of 9 people: Joseph Poon, Karl Floersch, Kelvin Fichter, Dan Robinson, David Knott, Xuanji Li, George Konstantopoulos, Alex Vlasov, & Vitalik!

Click [here and back to the top](#1)


