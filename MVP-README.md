# zk-Anonymous Group Treasury MVP (Fork of Semaphore MSA Modules)

This fork extends Jimmy Chu's excellent Semaphore ERC-7579 modules (original repo: https://github.com/jimmychu0807/semaphore-msa-modules) into a dead-simple app for non-technical users who need anonymous group funds (activists, small teams, journalists in restricted environments).

**Core User Story**  
As a small activist collective in a high-surveillance country, I want to create a group treasury where members contribute and spend via zk-proofs so that no one’s identity or wallet is linked on-chain.

## Quick Start (for testing the MVP)
1. `pnpm install`
2. Copy `.env.example` → `.env.local` and fill in keys (WalletConnect ID, RPCs).
3. `pnpm --filter web dev` → opens the improved frontend at localhost:3000
4. Connect wallet to Base Sepolia (or mainnet when deployed).

## What the agent is building
Follow instructions in **AGENT-PROMPT.md** exactly. Goal: Ship v0.1 with:
- Beautiful, mobile-friendly wizard UI (landing → create group → invite → deposit → propose/approve spends anonymously).
- USDC support (Permit2 or direct).
- No changes to core contracts (keep packages/contracts as-is).

## Original Project Links (do not remove)
- Live Demo (Base Sepolia): https://semaphore-msa-modules.jimmychu0807.hk/
- Demo Video: https://www.loom.com/share/0b800171a4f1491f9eedd4f555569e37
- Writeup: https://jimmychu0807.hk/semaphore-msa-modules

Thanks to Jimmy Chu, PSE, and contributors for the strong foundation.
