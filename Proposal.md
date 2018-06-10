
# FRD DAO Proposal Technical White Paper V0.1.2

**May 31st, 2018**

**Abstract:** The FRD DAO proposal is *the* complete Whitepaper for the future direction of FRD cryptoken. This document is a work in progress. Please check back often.

Copyright © 2018 Farad Cryptoken

Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.

**DISCLAIMER:** This `FRD DAO Proposal Technical White Paper` is for information purposes only. Farad Cryptoken does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. Farad Cryptoken does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. Farad Cryptoken and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will Farad Cryptoken or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.

# Table of Contents

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->

- [Background](#background)
- [Requirements for DAO Applications](#requirements-for-dao-applications)
- [The Proposed Idea](#the-proposed-idea)
- [Delegated Proof of Stakes] (delegated-proof-of-stakes)
- [The Stable Coin](the-stable-coin)
- [The FDAO Store](the-fdao-store)
- [Technical Realizations](technical-realizations)
- [References](references)

<!-- /MarkdownTOC -->

# Background

The idea of doing Farad DAO is to revive the current Farad cryptoken into a new fully functional Decentralized Autonomous Organization, while at the same time, proposing a compleling use case for the future use of Farad DAO (FDAO).

# Requirements for FDAO Applications

1. The FDAO has to be truly autonomous, in such that the users are truly in control of the whole FDAO ecosystem
2. Voting is the primary function to be used to achieve concensus decision moving forward
3. It needs a compelling use case in terms of uses, and solve the current integration of the Web and Crypto currency in general
4. It needs to have intrinsic demands and supply to retain its value.

# The Proposed Idea

FDAO will be an ICO by itself to garner new users to this new eco-system. The idea is to have a truly autonomous offerings whereby all the Farad holders shall be moved to the new Farad DAO once the ICO is completed.

The MVP will be the FDAO web store where users of FDAO tokens can buy nd sell the items online, fully governed by the FDAO users themselves through voting, from item listing, item buy and sell, as well as item fulfillment.

All the activities in the buy and sell shall be verified by FDAO users through our custom "Authenticator" machine whereby all actions are rewarded by the confirming the transaction is legit, valid, appropriate and sound to be added to begin with.

# Delegated Proof of Stakes

The core offering of FDAO is hinged around Delegted Proof of Stakes (DPOS) where FDAO users can purchase the authenticator machine using FDAO tokens directly, and put some FDAO tokens as stakes on the authenticator machine for further use.

## Authenticator Functions
The Authenticator machine by itself is just a DApp that runs on a Raspberry-Pi that ships with FDAO application logics and core web store application, including other functionalities that shall be added in the future, including:

1. The news application
2. The Blog application
3. .. plus many more


Authenticator machine can be seen as the "vault" where FDAO users can store their FDAO tokens there securely, and participate in the FDAO economy. That includes:
	
1. Confirming transactions that happen on FDAO network
2. Validating the action of users
3. As a mean of reward and also penalty, based on the action of the users
4. Growing the FDAO tokens based on the activity happens

## Stakes and Rewards

Authenticator machine requires a certain number of FDAO tokens to be deposited on the machine before it can be fully functional. Otherwise, the same functions of FDAO applications using a normal web explorer on their PC, or mobile through our official URL address.

Once the specific amount of FDAO tokens are added to the machine, the machine will then automaticlly perform the authentication function for each transaction that happen in the network. For doing so, the successful authentication of transaction shall be rewarded certain FDAO rewards, based on the amount of FDAO deposited as stakes.

The precentage of rewards are as follows:

1. 0 to 10,000 FDAO tokens: 1 FDAO token
2. 10,001 to 20,000 FDAO tokens: 2 FDAO tokens
3. 20,001 to 40,000 FDAO tokens: 3 FDAO tokens
4. 40,001 to 80,000 FDAO tokens: 4 FDAO tokens
5. 80,001 and above: 5 FDAO tokens

In addition to that, the amount of FDAO tokens put into the stakes are also receiving the staking reward in daily, or monthly fashion. The decision to receive the tokens daily or monthly is driven by the user option, where obviously, the decisions are based on these parameters:

1. The FDAO token deposited shall not be removed from the stakes
2. The changing from daily to monthly is subject to the supply and demands on both category, and some waiting time may be required.

# The Stable Coin

Since FDAO store is all about selling real world items, and participating in the future economy of FDAO, there needs to be a stable coin that reflect the value of the item being sold.

For this purpose, a stable coin `F` (for the lack of better name) shall be created where all items are priced in `F`. The value of `F` is fixed to 1 US Dollar per F token

`F == 1 US Dollar`

As such, the final payment in FDAO for the purchased item is then calculted based on the current value of FDAO token in the market, and then converted to F token to be sent to the seller of the item. As the value of FDAO increase, less FDAO is required to purchse the item, and vice versa.

The F Token can then be converted to `fiat` currency through the internal FDAO exchanger via bank transfer, or any other cash remittance facility that is available for that country, for example PayPal, AliPay and so on.

# The FDAO Store

The FDAO store is pretty much what `craigslist` is where it is truly autonomous and governed by the FAO users. It is a `DApp` in its own rights, and contains a few modules:

1. **Wallet module:** the private/public key that is maintained by the user, meaning user can import their private key to the internal wallet, and control it from any other supported wallet app
2. **Chat and messaging module:** users can interact with each posting, or even chat among themselves
3. **Exchanger module:** where users can exchange the F Token to `fiat`
4. **Checkout Module:** where users can checkout the products bought

The prominent product on sale is of course the **Authenticator** machine where users can buy the item using F Token as well.

The product listing module is govern by `reward and punishment` where each posting, especially new product listing, shall be accompanied with some FDAO stakes. Should the listing is deemed as offensive, or inappropriate, the stakes put by the seller are then confiscated, and be rewarded to those who participated in validating the product listing

# Technical Realizations


## Authenticator

At the moment, we are basing the technical realizations on the `Ethereum Platform` for its Smart Contract offerings. The FDAo token shall be implemented as [ERC223](https://github.com/ethereum/EIPs/issues/223) standard, and the same for the F Token as the new standard simplifies the token transfer easily as compared to the ERC20 specifications.

The Authenticator basically listens to all FDAO transactions on the contract, and then based on the logics, would verify whether the transaction is valid, or invalid. The number validators are to be determined based on the current participants and the lefover are then put into the pool for future authentications.

## User Validations

User validations are done based on the real user activities on the FDAO Web Store. All the interactions, including product listings, comments and interactions on the store are able to be rewarded by the participants of the store itself.

All these are govern by the stakes the user has, as well as the all participating user actions combined. It can either be positive, or even negative rewards based on the post being scrutinized.

## DApp

The FDAO Store DApp is to be implemented using `VueJS` framework for the interactovoty, with the RESTful backend functions to store the data in the database. This is the first version of the implementation for fast `go to market` solution. Further improvement shall be done using `swarm` as the backend storage functions.

# References

ERC223 Specifications, [https://github.com/ethereum/EIPs/issues/223](https://github.com/ethereum/EIPs/issues/223), Ethereum Foundations.




