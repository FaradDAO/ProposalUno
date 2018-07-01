
# FRD DAO Proposal White Paper V0.1.5

**June 26th, 2018**

**Abstract:** The FRD DAO proposal is *the* general Whitepaper for the future direction of FRD cryptoken. This document is a work in progress. Please check back often.

Copyright © 2018 Farad Cryptoken

Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.

**DISCLAIMER:** This `FRD DAO Proposal White Paper` is for information purposes only. Farad Cryptoken does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. Farad Cryptoken does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. Farad Cryptoken and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will Farad Cryptoken or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.

# Table of Contents

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->

- [Background](#background)
- [What is DAO](#what-is-dao)
- [Requirements for DAO Applications](#requirements-for-dao-applications)
- [The Proposed Idea](#the-proposed-idea)
- [Delegated Proof of Stakes](#delegated-proof-of-stakes)
	- [Authenticator Functions](#authenticator-functions)
	- [Stakes and Rewards](#stakes-and-rewards)
- [The Stable Coin](#the-stable-coin)
- [The FDAO Store](#the-fdao-store)
- [Technical Realizations](#technical-realizations)
	- [Authenticator](#authentictor)
	- [User Validations](#user-validations)
- [Arbitration](#arbitration)
- [References](#references)

<!-- /MarkdownTOC -->

# Document History

| Date            | Version | Author        | Remarks                               |
|:----------------|:--------|:--------------|:----------------------|
| May 31st, 2018  | 0.1.0   | Hisham Ismail |Document initialization               |
| June 11th, 2018 | 0.1.1   | Hisham Ismail | Added preliminary description of FDAO |
| June 11th, 2018 | 0.1.2   | Hisham Ismail | Added the technical realizations      |
| June 12th, 2018 | 0.1.3   | Hisham Ismail | Added detailed explanations and document history  |
| June 13th, 2018 | 0.1.4   | Hisham Ismail | Added DAO introductions and proof reading  |
| June 26th, 2018 | 0.1.5   | Hisham Ismail | Added Arbitration  |

# Background

The idea of doing Farad Distributed Autonomous Organization (DAO) is to revive the current Farad cryptoken into a new fully functional Decentralized Autonomous Organization (DAO), while at the same time, proposing a compleling use case for the future use of Farad DAO (FDAO).

This document shall not discuss the detailed implementation of the DAO as it is meant for the general public. Succint that the main idea of how the DAO is to be implemented is enough so that we can make the general public understand the intent, and put the implementation details in another set of technical papers.

# What is DAO

When Bitcoin arrives, it is conceived as the first ever DAO as it has set of rules that govern the whole Bitcoin system, minus the preliminary and limited voting rights which done by the miners of Bitcoin. Then came along Ethereum Platform with its Smart Contract as part of the core system, which makes the realizations of DAO is truly possible via a set of rules embedded in the Smart Contract.

What DAO needs to be truly operational? It needs a Smart Contract, which is essentialy a compter codes, that spells out the rules and regulations needed for the oraganization to function. And then, it also needs a group of people to interact with the codes, to make sure the rules and regulations are activated as per the design of the DAO. The DAO by itself will not function without its community.

The DAO would also have its own token so that its members can participate in the DAO economy of that particular DAO is coded with. These functions can be any monetary transactions between its members, buy and sell, as well as other intended benefits such as donations and others. All the spending of the tokens are governed by the computer codes, and executed by its members.

All members participated in the DAO economy through voting system that is baked right into the DAO. The proposal can come from any members, and once it is finalized, it shall be put into votes. If the voting results is positive, the proposed action shall be executed by the people in the community.


# Requirements for FDAO Applications

A lot has been said about DAO and yet there are many ways to implement them to make the oraganization as autonomous as possible. The requirements for this FDAO Applications are:

1. The FDAO has to be truly autonomous, in such that the users are truly in control of the whole FDAO ecosystem
2. Voting is the primary function to be used to achieve concensus decision in moving forward
3. It needs a compelling use case in terms of uses, and solve the current integration of the Web and Crypto currency in general
4. It needs to have a `reward` and `punishment` functions so that all actions come with cost.
5. It needs to have intrinsic demands and supply to retain its value.

# The Proposed Idea

Since FDAO is an eco-system by itself, and not just a migration from FRD eco-system, there is a need to open up the participation to new users in the blockchain space to include them as part of the FDAO community. As such, FDAO will be an ICO by itself to garner new users to this new eco-system. 

The idea is to have a truly autonomous offerings whereby all the Farad holders shall be moved to the new Farad DAO once the ICO is completed. By this standard, all FRD holders should receive the same amount of FDAO tokens, subject to the rules and regulations of the FDAO itself.

The MVP will be the FDAO web store where users of FDAO tokens can buy nd sell the items online, fully governed by the FDAO users themselves through voting, from item listing, item buy and sell, as well as item fulfillment. The main product offering would be the `Authenticator Machine` where all the varifications and validations of activities in the FDAO community are to be done by this device.

All the activities in the buy and sell shall also be verified by FDAO users through this `Authenticator Machine` whereby all actions are rewarded by the confirming the transaction is legit, valid, appropriate and sound to be added and presented to the community to begin with, and vice versa.

# Delegated Proof of Stakes

The core offering of FDAO is hinged around Delegated Proof of Stakes (DPOS) where FDAO users can purchase the `Authenticator Machine` using FDAO tokens directly, and put some FDAO tokens as stakes on the authenticator machine for further use as described below.

## Authenticator Functions

The Authenticator machine by itself is just a DApp that runs on a `Raspberry Pi` with our custom software and systems that baked into the machine - the FDAO application logics and core web store application, including other functionalities that shall be added in the future, including:

1. The news application
2. The Blog application
3. .. plus many more


Authenticator machine can be seen as the `vault` where FDAO users can store their FDAO tokens there securely, and participate in the FDAO economy. That includes:
	
1. Confirming transactions that happen on FDAO network
2. Validating the action of users
3. As a mean of reward and also penalty, based on the action of the users
4. Growing the FDAO tokens based on the activities and staking options.

All future applications and modules are to be added on the `Authenticator Machine` via a system update where all machines shall be notified when new modules and applications are ready to be installed, or upgraded.

## Stakes and Rewards

Authenticator machine requires a certain number of FDAO tokens to be deposited on the machine before it can be fully functional. Otherwise, the same functions of FDAO applications using a normal web explorer on their PC, or mobile through our official URL address.

Once the specific amount of FDAO tokens are added to the machine as stakes, the machine will then automaticlly perform the authentication function for each transaction that happened in the network. For doing so, the successful authentication of transaction shall be rewarded certain FDAO rewards, based on the amount of FDAO deposited as stakes.

The precentage of rewards are as follows:

| FDAO Staking Amount | Rewards       |
|:--------------------|:--------------|
| 0 to 10,000         | 1 FDAO token  |
| 10,001 to 20,000    | 2 FDAO tokens |
| 20,001 to 40,000    | 3 FDAO tokens |
| 40,001 to 80,000    | 4 FDAO tokens |
| 80,001 to 100,000   | 5 FDAO tokens |
| 100,001 and above   | 6 FDAO tokens |

In addition to that, the amount of FDAO tokens put into the stakes are also receiving the staking reward in daily, or monthly fashion. The decision to receive the tokens daily or monthly is driven by the user option, where obviously, the decisions are based on these parameters:

1. The FDAO token deposited shall not be removed from the stakes
2. The changing from daily to monthly is subject to the supply and demands on both category, and some waiting time may be required.

# The Stable Coin

Since FDAO store is all about selling real world items, and participating in the future economy of FDAO, there needs to be a stable coin that reflect the value of the item being sold.

For this purpose, a stable coin `F` (for the lack of better name) shall be created where all items are priced in `F`. The value of `F` is fixed to 1 US Dollar per F token

```
F Token Value == 1 US Dollar
```

As such, the final payment in FDAO for the purchased item is then calculated based on the current value of FDAO token in the market, and then converted to F token, and to be sent to the seller of the item. As the value of FDAO increase, less FDAO is required to purchase the item, and vice versa.

The F Token can then be converted to `fiat` currency through the internal FDAO exchanger via bank transfer, or any other cash remittance facility that is available for that country, for example PayPal, AliPay and so on.


# The FDAO Store

The FDAO store is pretty much what `craigslist` is where it is truly autonomous and governed by the FAO users. It is a `DApp` in its own rights, and contains a few modules:

1. **Wallet Module:** the private/public key that is maintained by the user, meaning user can import their private key to the internal wallet, and control it from any other supported wallet app
2. **Chat and Messaging Module:** users can interact with each posting, or even chat among themselves
3. **Exchanger Module:** where users can exchange the F Token to `fiat`
4. **Checkout Module:** where users can checkout the products bought
5. **Product Module:** where users can post new products to sell
6. **Inventory Module:** where products inventory can be tracked
7. **Shipment and Delivery Module:** where shipments can be tracked and monitored after purchase
8. **Invoice Module:** where proper invoicing can be produced for item bought
9. **Arbitration Module:** where shipped items can be returned back if it is not as per advertised.

The prominent product on sale is of course the **Authenticator Machine** where users can buy the item using F Token as well.


# Technical Realizations


## Authenticator

At the moment, we are basing the technical realizations on the `Ethereum Platform` for its Smart Contract offerings. The FDAo token shall be implemented as [ERC223](https://github.com/ethereum/EIPs/issues/223) standard, and the same for the F Token as the new standard simplifies the token transfer easily as compared to the ERC20 specifications.

The Authenticator basically listens to all FDAO transactions on the contract, and then based on the logics, would verify whether the transaction is valid, or invalid. The number validators are to be determined based on the current participants and the lefover are then put into the pool for future authentications.

## User Validations

User validations are done based on the real user activities on the FDAO Web Store. All the interactions, including product listings, comments and interactions on the store are able to be rewarded by the participants of the store itself.

The product listing module in the Web Store is governed by `reward and punishment` model where each posting, especially new product listing, shall be accompanied with some FDAO stakes. Should the listing is deemed as offensive, or inappropriate, the stakes put by the seller are then be revoked, and rewarded to those who participated in validating the product listing.

All these are govern by the stakes the user has, as well as the all participating user actions combined. It can either be positive, or even negative rewards based on the post being scrutinized.

## DApp

The FDAO Web Store is a DApp where the store shall be in communication with the Smart Contract address on Ethereum Blockchain. As it is based on a Smart Contract, the web store shall be just the client to the Smart Contract using the `web3.js` technology for Smart Contract interactions.

The Smart Contract shall be developed using `OpenZeppelin` framework, and utilizing `ZeppelinOS` solution for upgradable Smart Contract. This is particularly useful as we see the FDAO will continue to evolve in the future based on the needs of the FDAO community.

The FDAO Store DApp is to be implemented using `VueJS` framework for the interactovoty, with the RESTful backend functions to store the data in the database. This is the first version of the implementation for fast `go to market` solution. Further improvement shall be done using `swarm` as the backend storage functions.

# Arbitration

Since the running of the FDAO is truly on a decentralized mode, to protect the organization from any hijack by the potential nemesis is vital to the organization structure itself. As such, there should be an Arbitration Forum for all the members to voice their opinions and state their case for further considerations by the community. If the cse is warranted with relevant proofs, the case whould be up for votes by all the community members, and further actions should be dervied from thereon. Should there is any impasse on the decisions, the FDAO Committee Members shall step in and the decide the next logical course of actions.


# References

Raspberry Pi, [https://www.raspberrypi.org](https://www.raspberrypi.org), Raspberry Pi Foundation.

How DAO Works, [https://cointelegraph.com/ethereum-for-beginners/what-is-dao#how-daos-work](https://cointelegraph.com/ethereum-for-beginners/what-is-dao#how-daos-work), CoinTelegraph.

ERC223 Specifications, [https://github.com/ethereum/EIPs/issues/223](https://github.com/ethereum/EIPs/issues/223), Ethereum Foundation

web3.js, [https://github.com/ethereum/web3.js/](https://github.com/ethereum/web3.js/), Ethereum Foundation

OpenZeppelin, [https://zeppelin.solutions](https://zeppelin.solutions), Zeppelin Solutions

ZeppelinOS, [https://zeppelinos.org](https://zeppelinos.org), Zeppelin Solutions




