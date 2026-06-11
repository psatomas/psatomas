# Tomás Araújo

<h3 align="center">
Web3 Engineer  
(Solidity • TypeScript • EVM • Protocol Architecture)
</h3>

---

## Focus

Design and development of EVM-based Web3 systems, combining smart contracts with reliable off-chain infrastructure. Focused on protocol architecture, deterministic state management, event-driven systems, and clear separation between canonical on-chain state and derived application data.

---

## Areas of Work

- Smart contract development in Solidity (EVM)
- Contract testing and validation using Foundry
- Development workflows and scripting with Hardhat
- Blockchain interaction and event handling via ethers.js
- Off-chain execution and data processing using Node.js
- Event indexing and persistence strategies (PostgreSQL)
- Frontend integration with React for contract interaction
- Wallet-based authentication and transaction flow with MetaMask

---

## Projects

### Provenance Registry — On-Chain Audit Provenance Layer

- Blockchain-based audit provenance system that makes protocol evolution and audit integrity cryptographically verifiable on Ethereum.
- Implements an on-chain registry for protocol versions, audit metadata, commit hashes, auditor attribution, and timestamped records.
- Uses `keccak256` hashing to create verifiable links between off-chain audit artifacts and immutable blockchain records.
- Built a complete Web3 flow: MetaMask authentication → transaction signing → smart contract execution → blockchain state synchronization.
- Smart contract deployed on Ethereum Sepolia with React + TypeScript frontend integration using ethers.js v6.

**Stack:** Solidity • Hardhat • React • TypeScript • Vite • TailwindCSS • ethers.js • Ethereum Sepolia

### StakeVerse Protocol — Modular DeFi Governance System

- Decentralized protocol MVP combining ERC-20 token economics, NFT-based membership access, staking mechanisms, and DAO governance.
- Designed modular smart contract architecture using OpenZeppelin standards:
  - ERC-20 utility token
  - ERC-721 membership NFT
  - Staking contract with reward mechanisms
  - DAO governance layer
  - Chainlink-compatible price oracle integration
- Developed comprehensive testing infrastructure using Hardhat v3, Mocha, and Chai, achieving full contract coverage.
- Validated security using static analysis and symbolic execution tools, including Slither and Mythril.
- Deployed and tested on Ethereum Sepolia with frontend wallet integration.

**Stack:** Solidity • Hardhat v3 • OpenZeppelin • Chainlink • React • TypeScript • TailwindCSS • Slither • Mythril

---

## Stack

**Smart Contracts**  
Solidity • Foundry • Hardhat • OpenZeppelin

**Backend**  
Node.js • TypeScript • ethers.js • PostgreSQL  

**Frontend**  
React • MetaMask  

**Infrastructure**  
Docker • Linux • Git  

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/psatomas)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=psatomas@gmail.com)
