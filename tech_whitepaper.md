# CPS Coin Technical White Paper

Copyright © 2018 Chips Limited


# Introduction
... a consensus blockchain operating system that provides databases, account permissions, scheduling, authentication, and internet-application communication to app developers. ... 

# Definitions:
## Operating System
A group of software that supports a computer's basic functions, such as scheduling tasks, executing applications, and controlling peripherals. 

## Blockchain
Blockchains are immutable digital ledger systems implemented in a distributed fashion (i.e., without a central repository) and usually without a central authority. At their most basic level,  they enable a community of users to record transactions in a ledger that is public to that community, such that no transaction can be changed once published. The most significant blockchain product so far is Bitcoin.

# Architecture

## Infrastructure
We recognizes that many different applications require the same types of functionalities, such as implementations of the cryptography and  communication tools. Keeping that in mind, we will feature the introduction of generalized role-based permissions, a web toolkit for interface development, self-describing interfaces, self-describing database schemes, and a declarative permission scheme. As a result, these functionalities will be especially powerful for simplifying user account generation and management, as well as security issues like declarative permissions and account recovery.

# Features

## DPOS (for incremental issuing)
With traditional Proof-of-Work (POW) consensus mechanisms, the security of the network and application depends on a large amount of hashing power and/or a large distribution of network tokens. For individual developers and startups, these challenges make the barrier to entry prohibitively high. 

Delegated Proof-of-Stake (DPOS) can be operated by a relatively small number of processors without the same network security concerns, although other concerns would still be present for developers. 

## Incentive: stakeholder v.s. consumer
With Ethereum, gas fees are required in exchange for every calculation, storage operation, and bandwidth utilization. Furthermore, the required fees fluctuate and can spike prohibitively high as miners preferentially select transactions with the largest fees. This was especially obvious during recent cases, in which $100 gas fees were still not enough even for trivial transactions. Furthermore, this economic model creates a scenario in which rich actors can potentially freeze the entire network by flooding it with high-fee transactions. Thirdly, this model requires developers and startups to continuously burn gas fees throughout development and deployment of their applications.

In contrast, CPS will utilize an ownership model, in which holding CPS Coin gives users a proportional share in the network bandwidth, storage, and processing power. This means that if someone owns 1% of the CPS Coin, they will always have access to 1% of the network bandwidth, regardless of the load on the rest of the network. In this way, small startups and developers can purchase a relatively small part of the network in order to receive reliable, predictable network bandwidth and computing power, and simply purchase more CPS Coins when they need to scale up their application. Furthermore, since the network will have zero transaction fees, there is no network development cost, except for the initial purchase of CPS Coin. However, these can of course always be sold in order to reclaim the initial investment if desired.
