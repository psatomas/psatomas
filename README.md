<h1 align="center">Tomás Araújo</h1>

<h3 align="center">
Protocol Engineer · EVM & AI Systems
</h3>

<p align="center">
Protocol Architecture • Distributed Systems • On-Chain Systems • Autonomous Economic Systems
</p>

<p align="center">
<a href="https://psatomas.com">Learn About My Work on psatomas.com</a>
</p>

---

## About

I build EVM protocols and supporting infrastructure across execution, state, governance, indexing, SDKs, and application-facing services.

I design around protocol guarantees: which state must be canonical, which data can be derived, how execution is constrained and verified, and where trust boundaries exist between on-chain and off-chain components.

I treat protocol engineering as systems engineering, emphasizing deterministic behavior, explicit state transitions, modular boundaries, observability, and security at the architectural level.

I am extending this systems-oriented approach into AI engineering, focusing on agent orchestration, context management, tool integration, stateful workflows, and reliable execution boundaries.

---

## Technical Focus

### Protocol Engineering

- Protocol architecture and state-transition systems
- Deterministic execution and execution mechanisms
- Canonical state, derived state, and trust boundaries
- Financial and governance mechanisms
- Modular and composable protocol architecture

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
- MCP-based tool interfaces
- Workflow design and execution control

---

## Projects

<details open>
<summary><b>ExeKPro</b> — Execution-Selection Protocol for Web3 Intents</summary>

<br/>

Execution-selection protocol for Web3 intents with modular strategies and deterministic scoring.

Competing execution modules are simulated and scored through a deterministic `ScorePolicy`, with the highest-scoring module executing on-chain through the protocol's `ExecutionEngine` kernel.

### Architecture

- Intent layer for standardized, owner-registered intent types
- On-chain `ExecutionEngine` kernel for scoring and executing candidate modules
- Modular execution modules competing for selection
- Deterministic scoring via `ScorePolicy`
- Observability and indexing layer for execution performance
- SDK layer for developer integration
- Separation between canonical protocol state and supporting execution/application services

**Stack**

`Solidity` • `Foundry` • `TypeScript` • `Node.js` • `viem` • `wagmi` • `Next.js` • `Cloudflare Workers`

[Protocol Console](https://exekpro.com) · [Repository](https://github.com/psatomas/ExeKPro)

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

| Domain | Technologies |
|---------|--------------|
| Smart Contracts | Solidity, Foundry, Hardhat, OpenZeppelin |
| Blockchain Infrastructure | TypeScript, Node.js, viem, Event-Driven Systems |
| Frontend | React, Next.js, Vite, ethers.js |
| AI Systems | Agent Orchestration, MCP, LLM Workflows, Context Management, Claude Code, Codex CLI |
| Tooling | Linux, Git, Docker, CI/CD |

---

<h2 align="center">Connect with Me</h2>

<p align="center">
<a href="https://psatomas.com"><img src="assets/psat-mark-badge.png" height="28" alt="PSAT"><img src="https://img.shields.io/badge/PSATOMAS-000000?style=for-the-badge" height="28" alt="PSATOMAS"></a>
<a href="https://linkedin.com/in/psatomas"><img src="assets/linkedin-badge.svg" height="28" alt="LinkedIn"></a>
<a href="mailto:psatomas@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28"></a>
</p>
