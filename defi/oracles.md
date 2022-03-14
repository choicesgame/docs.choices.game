# Oracles

DeFi is powered by smart contracts. Sometimes, the inputs required to produce an output consist of real-world data not stored on the blockchain. There is a need for protocols to bridge the gap by relaying off-chain data onto the blockchain for smart contracts to interact with the data.



Off-chain information is an integral part of DeFi and should be valid and accurate.



## Oracle Protocols

Oracles act as a bridge between off-chain data and the blockchain, or between protocols that do not have internal data feeds to reference on-chain data. These oracles seek to relay external information to the blockchain to be verified an executed upon by smart contracts and Dapps int eh DeFi ecosystem.



### Chainlink

Framework and infrastructure for building decentralized oracle networks that securely connect smart contracts on any blockchain network to external data resources and off-chain computation. Each oracle network is secured by independent and Sybil resistant node operators that fetch data from a multitude of off-chain data providers, aggregate the information into a single value, and deliver it on-chain to be executed upon by smart contracts.

One of the main functions of Chainlink is to deliver the most accurate asset prices through its price feeds, which can be integrated into blockchain protocols for specific use cases.



The most common method that Chainlink oracles use to bring external data on-chain is the Decentralized Data Model, a continuously updated on-chain smart contract representing a specific piece of data that can be queried on-demand in a single transaction.



### Band Protocol

Cross-chain oracle platform that connects smart contracts with external data and APIs. Decentralized applications that have been integrated with Band Protocol receive data through Band Protocol's smart contract data points instead of directly from off-chain oracles.

A unique aspect of Band Protocol is that they utilize BandChain a separate blockchain to handle and relay information that can handle thousands of transactions. Data can be sent to other blockchains via Cosmos' Interblockchain Communication.

Data sourced from Band Protocol are curated and verified by the community, ensuring that they are reliable enough to be referenced by Dapp users.

