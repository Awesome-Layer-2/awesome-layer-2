# Welcome to Awesome Layer 2 !
if you don't understand layer 2 solutions, check our [intro](https://github.com/Awesome-Layer-2/Awesome-Layer-2#intro) here!

Want to know more about layer 2 solutions? Want to find more about state channel,sidechain(including Plasma) and off-chain computation? Check our [all about layer 2](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/all%20about%20layer%202.md) here !

And if you want to know about all the layer 2 projects? Check [projects](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/Projects.md) here.

If you have any other ideas about the Awesome Layer 2, click here to know how to [contribute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/contributing.md) and let's work together to embrace the future of Layer 2 !

# INTRO
Different introductions of layer 2

## Introduction to Layer 2 solutions

Blockchain technology is facing a trilemma, i.e. from decentralization, security and scalability. Only two of the three features could be obtained in a single blockchain. **At the heart of the scaling problem is a tradeoff between "large user-base " and "large set of validators".**

Public blockchains need all the validators reach consensus, to ensure decentralization and security, which leads to the problem: the throughput of the whole blockchain is equal to a single validator. Fundamentally, blockchains just don’t scale.

Now there are three scalability technologies are on their way:

1. Each validator processes more transactions and improve the throughput of the blockchain, by introducing optimized blockchain protocols.（i.e DAG, Hashgraph, Avalance, etc). 
2. By using sharding technology, each shard process it's own transaction. 
3. Off chain scaling solutions, which will be the main topic of this repo.

For the first solutions, by optimizing the blockchain protocols, then only computer with better processing power can act as validator. For those home - use computers, they even can't download transaction if the throughput reach 5000 transactions per second. And storage comes to be a problem afterward.

As for Sharding, it's not mature yet. There are different issues concerning 4 level of sharding: from the computation level, network level, storage level and consensus level. These issues are also cross shard problem like [train and hotel problem](https://github.com/ethereum/wiki/wiki/Sharding-FAQs#what-is-the-train-and-hotel-problem), those problems are not solved yet.

Off chain scaling solutions are mature technologies for scaling blockchain, first introduced by Lighting Network in 2016. From our perspective, public blockchain is so far the most efficient way to reach global consensus, but it is also the slowest database as well. Thus we should let blockchain do what they should do, i.e. ensure security and decentralization. Other features like scalability, privacy and so on could be done through off chain scaling solutions, to fit the demand of different industries and applications.

Here are two main considerations behind off chain scaling solutions: 

**1. Not every thing needs to reach a global consensus.**

**2. Public blockchain should just do what they should, to guarantee public verifibility.**

Nowadays, there are several branches of off chain scaling solutions: 
1. State Channel 
2. Sidechain (Plasma) 
3. Off chain computation

We will introduce them one by one in the future.

In this repo, we use “Layer 2” to refer off chain scaling solutions. The public blockchain which guarantees the security and decentralization of the network is called "Layer 1", these names are already reach consensus inside the industry.

We boldly predict that in the future there will be variety of Layer 2 developers, they will come up with their Layer 2 solutions according to real world demand and their understanding of the technology.

This repo is designed for the future of Layer 2.
