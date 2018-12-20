# Welcome to Awesome Layer 2 !

## Quick Guide
To know what are layer 2 solutions? Please check the [intro](https://github.com/Awesome-Layer-2/Awesome-Layer-2#intro) here!

To know more about layer 2 solutions? Curious about state channel, sidechain(including Plasma) and off-chain computation? 
Please check the [all about layer 2](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/All%20about%20layer%202.md) here !

Then you must want to check all the layer 2 [projects](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/Projects.md) here!

Any other ideas about the Awesome Layer 2, or want to [contribute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/contributing.md) ? Welcome to join us, let's embrace the future of Layer 2 together!

# INTRO
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
1. [State Channels](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/Projects.md#state-channels)

2. [Sidechain (Plasma)](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/Projects.md#sidechains)

3. [Off chain computation(Truebit,TEE)](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/Projects.md#off---chain-computation)

We will introduce them one by one in the future.If you have anything to add here, [know how to contribute](https://github.com/Awesome-Layer-2/Awesome-Layer-2/blob/master/contributing.md)

In this repo, we use “Layer 2” to refer off chain scaling solutions. The public blockchain which guarantees the security and decentralization of the network is called "Layer 1", these names are already reach consensus inside the industry.

We boldly predict that in the future there will be variety of Layer 2 developers, they will come up with their Layer 2 solutions according to real world demand and their understanding of the technology.

This repo is designed for the future of Layer 2.
