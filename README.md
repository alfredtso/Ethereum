# Ethereum
An analysis on attacks and defenses in Ethereum

## Introduction
1.1 Ethereum

Ethereum is a cryptographic currency and like the more well-know BitCoin, it is built upon a blockchain, which is like a public ledger where all the transactions on the ledger are veriﬁed and publicly available. Network participants can push transactions to the blockchain network. These transaction will then be grouped and appended to the blockchain using some consensus mechanism. The Ethereum used the proof of state system right not. Transactions can be carried out by human or smart contract which will then be executed in the Ethereum Virtual Machine (EVM). EVM is quasi Turing complete as the execution could be restricted by the gas limit which essentially limits the number of execution steps. These smart contracts are usually written in a prgramming language called Solidity. Similar to object- oriented programming, Solidity is so-called ”contract-oriented” [3]. The syntax of Solidity is similar to JavaScript, with some primitives accounting for the distributed nature of Ether. Examples of these primitives are msg.sender etc.[3]

With the upgrade of the Ethereum to Ethereum 2.0, the platform promised to be more scalable and secure, again gaining the world’s attention. In recent year, several huge incidents made us question whether the platform is ready for wider adoption. To answer this we will need to study the platform, especially the smart contract more thoroughly. The real question, however, seemed to be how can we study the security of ethereum smart contract?

Smart contracts are just like computer programmes, having similar kinds of vulnerability such as integer overﬂow, reentrancy and call injection etc [12]. Afterall, most smart contracts are written in high-level programming language, Solidity being the most popular one. These codes will then be compile to low-level bytecode which would then be deployed to the blockchain, invoked by users or smart contracts and be executed by the Ethereum Virtual Machine (EVM) As such, diﬀerent kinds of technique used to analysis codes could also be used to study smart contracts.

The stake is high here because in the infamous DAO vulnerability has led to a ﬁnancial losses or more than sixty million USD and if we really want to see more real-world application of the smart contracts, we must safeguard or at least have the tool to enable us to safeguard the plarform from hacker alike.

In this report, we will be looking at several technique for detecting vulnerability: The mother of all defenses strategy, without which we will be ﬁghting in the dark.
