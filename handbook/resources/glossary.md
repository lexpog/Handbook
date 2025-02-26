---
description: >-
  This resource is meant to ease the learning curve for anyone interested in
  web3.
---

# Web3 Glossary

![](<../../.gitbook/assets/image (15).png>)

## Open Source

> Software for which the original source code is made **freely available** and **may be redistributed and modified.**
>
> Many great projects are developed under an open source model, where developers, community members, and users come together to build and improve a product.

* [Wikipedia](https://en.wikipedia.org/wiki/Open-source_software)
* Examples of open source projects:
  * Linux (Operating system)
  * Python (High-level programming language)
  * PostgreSQL (Relational query and database language)
  * Word Press (Content management system for web)
  * Drupal (Content management system)

## Web3

![](https://lh6.googleusercontent.com/WOaT5LWvKxh9eUP6RJ5Ts3js_wgvezRhoErRTouMz\_8i9YS8yPiP88NbcvfWXPSy0Rgw0E30z3NhANRdZdFq0k2E2k27ThWaxP4tRfrsCI0cl0TZba2kqpPWtbLJdquuuCKgLU27)

> **Web3** is the vision of the serverless internet, a decentralized web. An internet where users are in control of their own data, identity, and destiny.

* [What is Web3?](https://www.youtube.com/watch?v=l44z35vabvA) (30 Minutes | Youtube) 
* [From Web 1.0 to Web3: How the Internet Grew Over The Years](https://hackernoon.com/from-web-10-to-web3-how-the-internet-grew-over-the-years-zac032g1) (Hackernoon)

## Ethereum

![](<../../.gitbook/assets/image (27) (1) (1) (1).png>)

> **Ethereum** is a decentralized platform that runs **smart contracts**: applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third party interference.

* [Wikipedia](https://en.wikipedia.org/wiki/Ethereum)
* [Ethereum for dummies](https://hackernoon.com/ethereum-for-dummies-af5aeacb13d4) (Hackernoon)

## Smart Contract

```javascript
pragma solidity ^0.4.0;

contract SimpleStorage {
    uint storedData;

    function set(uint x) public {
        storedData = x;
    }

    function get() public view returns (uint) {
        return storedData;
    }
}
```

> A **smart contract** is a self-executing agreement where the terms are directly written into a computer program that is deployed to a blockchain.

* [Blockchain and smart contracts](https://www.youtube.com/watch?v=B3cSoWoAkI4) (7 Minutes | Youtube)
* [What are smart contracts?](https://cointelegraph.com/ethereum-for-beginners/what-are-smart-contracts-guide-for-beginners) (Cointelegraph)
* [What is Solidity?](https://www.youtube.com/watch?v=3i203iTmcFc) (2 Minutes | Youtube)

## Gas

![In the Ethereum blockchain, "Gas" is an abstraction of the resources needed to "write" data.](<../../.gitbook/assets/image (31).png>)

> **Gas** is the pricing value required to **conduct a transaction** or **execute a contract** on the Ethereum blockchain platform. It can be seen as a **fee** that any user pays when **writing** information into the Ethereum network; this could be a transaction, a deployment of a smart contract, sending a proposal to an organization, just to mention a few. The price of Gas is set by the market (supply and demand), and varies over time.

* [What is Ethereum Gas?](https://www.ethos.io/what-is-ethereum-gas/) (Ethos)

## Wallet

![Different wallets can hold different crypto assets, such as Ether or ERC20 Tokens](<../../.gitbook/assets/image (13).png>)

> A **cryptocurrency wallet** is a device, physical medium, program or a service which stores **public and private keys** and can be used to track ownership, receive or spend **cryptocurrencies**.

* [Intro to Ethereum Wallets](https://docs.ethhub.io/using-ethereum/wallets/intro-to-ethereum-wallets/) (EthHub)
* [Metamask](https://metamask.io/index.html)

{% hint style="info" %}
There are many wallet providers other than Metamask. We encourage you to do your research to find the one that best suits your needs.
{% endhint %}

## ERC20 Token

![Tokens are commonly used to represent value, like currency or assets.](<../../.gitbook/assets/image (3).png>)

> Ethereum **tokens** are digital assets built on top of the **Ethereum** blockchain. They can be **created by anyone** with access to the Ethereum network. The **ERC20** is the most popular standards for creating tokens on Ethereum.

{% hint style="danger" %}
Keep in mind that not all tokens hold value, nor are backed by any type of collateral. Be cautious when accepting payments in tokens, as anyone can create their own.
{% endhint %}

* [ERC20 Tokens, Simply Explained](https://www.youtube.com/watch?v=cqZhNzZoMh8) (6 Minutes | YouTube)
* [The ERC20 standard](https://eips.ethereum.org/EIPS/eip-20) (Ethereum Improvement Proposal)

## DAO

![DAOs are organized by members who work together to achieve a common goal.](<../../.gitbook/assets/image (5).png>)

> A **Decentralized Autonomous Organization** (DAO) supports itself on multiple **smart contracts** to perform its functions. This type of organization is represented by **rules** encoded as a computer program that is **transparent**, controlled by **stakeholders**, and **not influenced** by a central authority. Anyone with an Ethereum Wallet can interact with a DAO.

* [What is a DAO?](https://hackernoon.com/what-is-a-dao-c7e84aa1bd69) (Hackernoon)
* [What is a DAO?](https://www.youtube.com/watch?v=JcPNO0o_Cng) (5 Minutes | Youtube)
* [Wikipedia](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization)
* [What We Talk About When We Talk About DAOs](https://www.youtube.com/watch?v=RkN7-UcpC4A) (1 hr | Youtube)
