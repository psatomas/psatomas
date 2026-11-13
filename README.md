<h1 align="center">Tomás Araújo</h1>

<h3 align="center">
Protocol Engineer · Blockchain & AI Systems
</h3>

<p align="center">
Smart Contracts • Blockchain Infrastructure • Distributed Systems • AI Engineering
</p>

<p align="center">
<a href="https://psatomas.com">More About My Work on psatomas.com</a>
</p>

---

## About

I build blockchain systems, smart contracts, and supporting infrastructure, working primarily with Solidity, TypeScript, and the EVM ecosystem.

My engineering work spans smart contract development, governance and staking mechanisms, blockchain payments, backend services, wallet integrations, and application architecture. I focus on clear system boundaries, predictable behavior, and reliable interactions between on-chain and off-chain components.

Protocol engineering is a central focus of my work, particularly state transitions, execution mechanisms, modular architectures, and security boundaries.

I also work with AI engineering technologies and concepts, including Python, LLM applications, agent orchestration, and stateful workflows, with an interest in how AI systems can interact with blockchain infrastructure.

---

## Technical Focus

### Protocol & Systems Engineering

- Protocol architecture and state-transition design
- Protocol invariants and authorization boundaries
- On-chain and off-chain system interactions
- Event-driven indexing and state synchronization
- Governance mechanisms and execution policies
- Failure handling and transaction lifecycle management

---

### Smart Contracts

- Solidity architecture for EVM protocols
- Contract composition and protocol mechanisms
- Foundry and Hardhat testing
- Fuzz testing of protocol logic
- OpenZeppelin-based implementations

---

### Blockchain Infrastructure

- Event-driven indexing and derived-state systems
- Off-chain services connected to canonical protocol state
- Transaction and execution lifecycle infrastructure
- TypeScript and Node.js backend systems

---

### AI Systems & Agent Engineering

- Agent orchestration and stateful workflows
- Context management and tool integration
- LLM application architecture
- LangGraph-based workflow design
- Workflow design and execution control

---

## Projects

<details open>
<summary><b>ExeKPro</b> — EVM Execution Infrastructure for DeFi</summary>

<br/>

ExeKPro is an evolving execution infrastructure project focused on modular, configurable, and non-custodial transaction execution in EVM-based DeFi applications.

The project combines an on-chain execution kernel with off-chain services for execution selection, monitoring, and application integration.

Its current implementation demonstrates deterministic selection among competing execution modules. The broader direction is toward customer-configurable execution infrastructure, with dedicated deployments, APIs, SDKs, and managed services.

### Engineering Components

- Solidity-based execution engine and module registry
- Modular execution strategies with deterministic scoring
- SDK and API integration for blockchain applications
- Event indexing and execution monitoring
- Separation between on-chain execution and off-chain infrastructure

### Product Direction

ExeKPro is evolving toward B2B execution infrastructure for DeFi applications, with customer-configurable execution policies, dedicated deployments, non-custodial transaction flows, and managed off-chain services through ExeKPro Cloud.

**Stack**

`Solidity` • `Foundry` • `TypeScript` • `Node.js` • `viem` • `wagmi` • `Next.js`

[Website](https://exekpro.com) · [Repository](https://github.com/psatomas/ExeKPro)

</details>
---

<details>
<summary><b>InterstellaQ</b> — Non-Custodial Payment Infrastructure on Stellar</summary>

<br/>

Non-custodial merchant payment infrastructure developed during the **BAF Código Cordillera 2026 Hackathon**.

InterstellaQ enables merchants to register Stellar accounts through on-chain proof of control, generate fixed-amount XLM invoices, and accept wallet-authorized payments through QR codes and shareable URLs.

The application verifies settlement against Stellar Horizon, automatically reconciles invoice status, and provides publicly verifiable transaction evidence without requiring custodial infrastructure or a dedicated backend.

### Architecture

- On-chain merchant registration with cryptographic proof of account control
- Fixed-amount XLM invoices with unique memo references and expiration
- QR-based payment requests and portable invoice URLs
- Non-custodial wallet integration through Stellar Wallets Kit and Freighter
- Settlement verification against transaction status, recipient, memo, exact amount, and expiration
- Automatic Horizon monitoring and merchant dashboard reconciliation
- Client-side invoice management without a dedicated backend
- Public transaction evidence through Stellar Testnet explorers

### Validation

Successfully demonstrated an end-to-end 1 XLM payment on Stellar Testnet using Freighter, including wallet authorization, on-chain settlement, Horizon verification, and automatic dashboard reconciliation.

**Stack**

`Stellar` • `TypeScript` • `React` • `Vite` • `Stellar Wallets Kit` • `Horizon` • `Freighter`

[Live Demo](https://interstellaq-app.vercel.app/) · [Repository](https://github.com/interstellaq/interstellaq) · [Video Pitch](https://youtu.be/vu6sxeFCil8)

</details>

---

<details>
<summary><b>Provenance Registry</b> — On-Chain Audit Provenance Layer</summary>

<br/>

An on-chain audit provenance registry for versioned protocol records, making document and artifact integrity cryptographically verifiable.

The system creates immutable, publicly verifiable references between off-chain artifacts and on-chain records using `keccak256` cryptographic commitments.

### Features

- On-chain protocol version registry
- Audit metadata storage
- Commit hash verification
- Timestamped blockchain records
- Cryptographic linking using `keccak256`

### Web3 Flow

`User → Wallet Authentication → Transaction Signing → Smart Contract Execution → Blockchain State Update → Frontend Synchronization`

**Stack**

`Solidity` • `Hardhat` • `React` • `TypeScript` • `Vite` • `TailwindCSS` • `ethers.js` • `Ethereum Sepolia`

[Live App (Sepolia)](https://protocol-provenance-registry.vercel.app) · [Repository](https://github.com/psatomas/ProvenanceRegistry)

</details>

---

<details>
<summary><b>StakeVerse</b> — DAO-Governed Staking and Governance Protocol</summary>

<br/>

DAO-governed staking and governance protocol with historical ERC20Votes voting power, protected reward accounting, and on-chain execution.

### Components

- DAO governance with on-chain proposal execution
- Historical, checkpointed voting power via ERC20Votes delegation
- Protected reward accounting
- Fixed-rate, time-locked staking and reward distribution
- Chainlink oracle integration for price data
- ERC-20 utility token
- ERC-721 membership NFT (secondary, non-gating credential)

### Engineering

- Modular smart contract architecture
- OpenZeppelin standards
- Automated contract testing
- Security analysis workflows
- Frontend wallet integration

**Stack**

`Solidity` • `Hardhat` • `OpenZeppelin` • `Chainlink` • `React` • `TypeScript` • `Vite` • `TailwindCSS` • `ethers.js v6`

[Live App (Sepolia)](https://stakeverse.vercel.app/) · [Repository](https://github.com/psatomas/StakeVerse)

</details>

---

## Engineering Toolkit

| Domain | Technologies & Capabilities |
|--------|-----------------------------|
| Programming Languages | Solidity, TypeScript, JavaScript, Python, Rust |
| Blockchain Ecosystems | EVM, Stellar |
| Smart Contracts | Foundry, Hardhat, OpenZeppelin |
| Blockchain Integration | viem, ethers.js, wagmi, Stellar SDK, Horizon API |
| Backend & Infrastructure | Node.js, NestJS, Event-Driven Indexing, APIs |
| Frontend | React, Next.js, Vite, Tailwind CSS |
| AI Engineering | Python, LangGraph, LLM Integration, Agent Workflows |
| Testing & Security | Jest, Vitest, Playwright, Fuzz Testing, Access Control |
| Development Tooling | Linux, Git, Docker, GitHub Actions |

---

## Education & Technical Training

**Postgraduate Specialization in Blockchain Development**  
Unyleya · 2026–Present  
360 hours · In Progress

**Web3 Engineering Residency**  
Instituto iRede · 2026–Present  
120 hours of technical training, followed by applied engineering in smart contracts, blockchain infrastructure, and collaborative Web3 development.

---

<h2 align="center">Connect with Me</h2>

<p align="center">
<a href="https://psatomas.com"><img src="assets/psat-mark-badge.png" height="28" alt="PSAT"><img src="https://img.shields.io/badge/PSATOMAS-000000?style=for-the-badge" height="28" alt="PSATOMAS"></a>
<a href="https://linkedin.com/in/psatomas"><img src="assets/linkedin-badge.svg" height="28" alt="LinkedIn"></a>
<a href="mailto:psatomas@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28"></a>
</p>
