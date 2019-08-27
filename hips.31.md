    HIP: 31
    Title: Mining and Pre-minding Design in DAG-POW System
    Author: Jeremy Chen<chenyuxin20160116@gmail.com>
    Category: Core
    Status: Draft
    Created: 2019-05-20

###Mining and Pre-minding Design in DAG-POW System

####Abstract

This is about the mining and pre-minding design of a PoW system, especially a system in which needing pre-mining design.

####Meaning of Mining

Mining essentially is a token supply schedule in PoW system, reflecting the distribution process of block rewards. More importantly, mining is essential to maintaining the network functions. Thus, in theory, mining is an infinite length of work. Even if without token-based rewards (newly minted tokens), transaction fees will reward miners to support network functions.

In the early stage of network start-up, considering security and determination of parameters, a pre-minding process is necessary before mining on mainchain network. This pre-minding period maybe called as pre-mining, in which also need to invest hardware and electricity cost.

####Importance of Mining

Blockchain, a new technology aimed at rebuilding trust and transfer of value between people, is a decentralized distributed ledger. Since it is "decentralized" and "distributed", a certain number of people (miners) who are unable or difficult to control are required to participate in the accounting. Mining is a process of gaining accounting rights.

Every transaction in blockchain system can be established after the verification of different users throughout the network. No miners, this decentralized ledger will not work. Miners are proposers and validators who maintaining the network functions and security. The participation of miners need investing hardware and electricity cost, so their contributions must be rewarded. In practice，they are rewarded in block rewards and transaction fees.

####Factors Affecting Mining period

The length of mining period result from a combination of four main factors below. Mining period here means an approximate period of time in which about 99.99% of tokens are allocated.

* Total Amount of Token Supply
 
  Let A denotes the total amount of token supply which has a constant upper limit in most cryptocurrencies. Only a few of cryptocurrencies are unlimited.

* Initial Block Reward (r) and Block Reward Schedule

  Block reward schedule reflects the way and frequency of block reward changes, also the level that rewarding miners with newly minted tokens. Maybe it's like this: halving per 210000 blocks in Bitcoin or several of its derivatives, reducing 20% per 5000000 blocks in ETC.

* Block Era (E)

  The block era E denotes a special period during which block reward will be fixed and changes at the end of each ear. Often, E is difined as a function of the block number N. A PoW system in which uses ‘Halving’ or ‘Phase decay’ in block reward schedule, the block era function may be like this (// denotes integer division)： E = (N-1) // T . Where T is the number of blocks which denotes the length of an era, it is 210000 blocks in Bitcoin, 840000 blocks in LTC, and 5000000 blocks in ETC.

* Block Rate (t)

  The block rate t is the time of one block confirmed, and a mean value during a period of time, which reflects the growth frequency of token supply. This value will remain stable as the dynamic adjustment of difficulty periodically.

Physical time of one block era will be the product of T and t. If the decay number of block reward is n when about 99.99% of tokens are allocated, the mining period P is approximate as P =T * t * n. Where n respects the block reward schedule and initial block reward r.

####Pre-mining Design

Considering security and determination of parameters, or other special requirement, such as rewarding founding team, requiting early supporters, a pre-mining design is needed. However, unlike BTG, it is not mean that getting lots of tokens at almost zero cost in an instant, only by modifying the parameters to obtain a nearly zero degree of mining difficulty. This is a real mining process that requires investment in hardware and electricity costs, and has a certain degree of difficulty in mining, and even everyone can participate in.

When considering a pre-mining design, the first thing to think about is pre-mining period P'. The determination of pre-mining period maybe result from a combination of actual demand, develop progress and parameter setting. Pre-mining period will start from test network and may be reflected intuitively in the form of taking away a certain proportion of block rewards within a certain period of time.

Often, the main process of pre-mining occurs during the test network, and sometimes may continue to the main-chain network for some time.