# Practice with cosmos-sdk
Cosmos blockchain is a decentralized network of independent parallel blockchains, supported by BFT consensus algorithms such as Tendermint consensus. Cosmos offers a set of tools and SDKs for developing and hosting a dApp in the Cosmos ecosystem.

## What is Cosmos?

Cosmos is an ever-growing ecosystem of connected applications and services developed for the decentralized future. It is a community-owned and operated universe of connected services. The apps and services on Cosmos connect using Inter-Blockchain Communication (IBC) protocol. It enables exchanging assets and data freely across sovereign decentralized blockchains.

The main focus of Cosmos is on customizability and interoperability. Instead of prioritizing its network, Cosmos fosters the ecosystem of networks that enables tokens and data sharing programmatically without any central party facilitating the activity.

Every new independent blockchain created on Cosmos, named Zone, is tethered to Cosmos Hub. The Cosmos hub maintains the record of the state of each Zone. It is a proof-of-stake blockchain that is powered by its native cryptocurrency, ATOM.

**The Vision**

The vision of Cosmos is to help developers to build blockchains easily and remove the barriers between blockchains by allowing them to interconnect. The end goal is to create a network of blockchains that can communicate with each other. Cosmos allows blockchains to maintain sovereignty, process transactions efficiently and connect with other blockchains in the ecosystem.

To accomplish its goal, Cosmos uses open source tools like Tedermint, Cosmos SDK and IBC. It helps to build custom, secure, interoperable and robust blockchain applications.

## What problem does Cosmos resolve?
**Scalability**

Decentralized applications built on the Ethereum blockchain are inhibited by the shared rate of 15 transactions per second. The reason behind it is that Ethereum still uses the Proof-of-Work mechanism and its dApps compete for limited resources of the single blockchain.

The problem is not limited to Ethereum but to every blockchain creating a single platform that would fit all use cases.
Cosmos’ Solution

Cosmos leverages two kinds of scalability:

**Vertical Scalability**

It provides methods for scaling blockchains. Tendermint BFT can handle thousands of transactions per second by optimizing its components and moving away from Proof-of-Work. 

**Horizontal Scalability**

Even if the applications and consensus engine are highly optimized, the transaction throughput of a single chain goes down, which it can not surpass. It is the limitation of vertical scalability. Multi-chain architectures provide the solution to this limitation. Implementing multiple parallel chains that run the same application and are operated by a common validator set can make blockchains theoretically infinitely scalable.

Cosmos offers vertical scalability at launch, which is a major improvement on current blockchains and will implement horizontal scalability solutions after completing the IBC module.

## What are the significant tools/ frameworks/ SDKs used by Cosmos?
**Agoric Swingset**

Agoric’s Cosmic SwingSet enables developers to test smart contracts build with ERTP in various blockchain setup environments. ERTP (Electronic Rights Transfer Protocol) is Agoric’s token standard for transferring tokens and other digital assets in JavaScript.

**CosmWasm**

It enables developers to write multi-chain smart contracts in Rust.

**Ethermint**

The Ethereum Virtual Machine was implemented as a Cosmos SDK module, making it possible to deploy proof-of-stake blockchains that support Ethereum smart contracts.

**Cosmos SDK**

It is a library collection of different SDKs that allow any blockchain protocol developer to easily write/run/execute the programming code with the help of the provided SDK library.

**IBC Protocol**

Inter-Blockchain Communication is another protocol that provides a way by which one blockchain protocol can communicate with another blockchain protocol. It is used to build a wide range of cross-chain applications that includes atomic swaps, token transfers, multi-chain Smart contracts and data and code sharding of different kinds.
