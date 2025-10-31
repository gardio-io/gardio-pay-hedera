# gardio-pay

<p align="center">
  <img src="./logo.png" alt="gardio-pay" width="160" />
</p>

## Overview

**Gardio Pay** aims to revolutionize payment systems by enabling **seamless native crypto transactions** through existing **Point of Sale (PoS)** terminals, powered by **Gardio EMV Crypto Cards** and the **Hedera network**.

Originally built on **Solana**, Gardio Pay was **adapted and optimized for Hedera** during the hackathon (starting October 25) to leverage its high throughput, scalability, and predictable low fees.

---

## Demo
[![Gardio Pay Demo](./preview.png)](https://vimeo.com/1131850690)  
**Watch the full demo on Vimeo:** [Gardio Pay Demo](https://vimeo.com/1131850690)

---

## Project Description

**Gardio Pay** demonstrates a complete real-world crypto payment flow using:
- **Gardio EMV Crypto Card** (hardware or simulator) to securely sign transactions  
- **PoS Terminal** to process merchant payments  
- **Gardio Pay Portal** to manage cards, balances, and transaction history  

The current version supports **prepaid cards**, where users can charge funds to their card from the **Gardio Pay Portal** or any **external wallet supporting Hedera USDC**.  

A **Card + PoS Simulator** was developed for the hackathon to replicate physical interactions and allow testing of real Hedera transactions without hardware.

---

## System Components

1. **Portal Frontend** – User interface for managing cards, charging balances, and viewing transactions  
2. **Gardio SmartCard** – Secure EMV-based crypto card supporting contact payments (contactless in progress)  
3. **PoS Application** – Merchant-side terminal app running on Linux (Android version in development)  
4. **Backend Server** – Connects PoS and card operations with blockchain logic for authentication and settlement  
5. **Smart Contract** – Handles on-chain transaction verification and updates merchant/user balances on Hedera  
6. **Gardio Simulator** – Simulates card and PoS communication for demo purposes  

> **Note:** Card and terminal provisioning, and merchant registration are performed offline as part of the setup process.

---

## Hackathon Deliverables

During the hackathon (starting October 25), the following updates were implemented:
1. **Hedera Network Support** – Migrated from Solana; rewritten smart contract in Solidity; updated frontend and backend for Hedera SDK and MetaMask  
2. **Card + PoS Simulator** – Enables full demo testing without physical hardware  

---

## Security

- **Private keys** remain stored and used only within the Gardio Card  
- **All transactions** are verifiable and traceable on the Hedera public ledger  

---

## Workflow Summary

1. **Merchant Setup (Offline)** – Terminal and merchant provisioning  
2. **Card Provisioning (Offline)** – Secure card issuance and account linking  
3. **Payment Flow (Demo)** –  
   - User charges the **prepaid card** via the **Gardio Pay Portal**  
   - User pays via **PoS terminal**  
   - Card signs and submits the transaction to **Hedera**  
   - Merchant and user see instant confirmation  
4. **Portal Management** – Continuous balance and transaction visibility  

---

## Upcoming Features

1. **Debit Mode** – Option to link cards directly to users’ own Hedera USDC wallets for true debit functionality  
2. **Card Revocation** – Ability to instantly lock or freeze lost or compromised cards  
3. **Mobile App** – Dedicated mobile app for card management and payments  

---

## Key Advantages

- **Native crypto payments** on Hedera  
- **Instant settlements**  
- **Predictable, low fees**  
- **Hardware-level security**  
- **Familiar PoS experience** for users and merchants  

---

## Links

- Contact: **info@gardio.io**  
- Hackathon Submission: [View Gardio Pay on Hedera Africa Hackathon](https://dorahacks.io/buidl/35550) 
---

## Source Code Access

The **Gardio Pay source code** can be shared **under NDA** for evaluation or technical review.  
Please contact **info@gardio.io** to request access.  

The **Pitch Deck** and **Demo Guide** (including the Gardio Pay Portal, Simulator, and credentials) were provided via **Box links** during the hackathon submission.

---

© 2025 Gardio
