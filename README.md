# CrypticMeta

Full-stack + Web3 engineer — Solana/Anchor, EVM/Solidity, Bitcoin/Ordinals, and AI-agent products. ~4 years shipping production dApps and infra for real money movement: escrow, payments, launchpads, and trading bots.

Building [Coderixx](https://coderixx.com) · Noida, India

---

## Selected work

### Onchain / Solana

**[BountyEscrow](https://github.com/crypticmeta/gigbounties-contracts)** — Solana/Anchor escrow program for [GigBounties](https://github.com/crypticmeta/gigbounties), a USDC bounty marketplace. Multi-token reward legs (SPL + Token-2022 + wrapped SOL), commit-reveal submissions, dispute resolution with bonded arbitration, and permissionless creator-default handling so funds can never be trapped by a disappearing funder. Deployed under a 3-of-4 Squads multisig with a scripted, hash-verified release pipeline; 30+ integration/unit/property tests before deployment.

### EVM

**OWNR Protocol** *(Base, private)* — Trust-based token launch platform. Contribution caps scale with a wallet's launch history (six trust tiers, 1–100 ETH), automatic DAO treasury per launch, automatic liquidity provisioning, price-based team vesting, full refunds on failed launches.

**[GigRamp integrator](https://github.com/crypticmeta/payment-integrators)** — Solidity USDC→INR offramp integrator for a B2B checkout protocol (P2P), contributed to its open-source integrator repo. Offramp-only: pulls gross USDC, hard-caps its fee at 200 bps, settles UPI delivery, and reconciles against the protocol's authoritative order status with full-gross refunds on cancel. 24 tests, 93% line coverage.

### Trading / prediction markets

**Polymarket trading bots** *(Rust, private)* — A whale-copy bot (per-wallet allocation limits, elite wallet tracking) and an automated market maker (configurable spreads, inventory management) for Polymarket, plus a REST API/analytics layer over both.

### Bitcoin / Ordinals

**Ordinalnovus** *(2022–2023, sunset)* — Bitcoin Ordinals marketplace and indexer I built and ran solo: inscription trading, rarity/collection tooling, and an API that handled millions of daily requests at peak. Shut down, but still ranks organically on Google years later.

### AI agents

**[Oskren](https://github.com/crypticmeta/oskren)** *(closed beta)* — Autonomous lead-gen agent. Give it a domain, it crawls and interviews the business, generates a conversion-optimized landing page with an embedded sales chat agent, then writes and launches Meta ad campaigns end-to-end with no human review gate — built and operated under Coderixx.

### Product

**[StreakTodo](https://github.com/crypticmeta/streaktodo)** — AI-assisted todo + scheduler app with streaks, built on Expo/React Native.

---

## Stack

**Chains:** Solana (Anchor, SPL/Token-2022), EVM/Base (Solidity), Bitcoin (Ordinals)
**Languages:** TypeScript, Rust, Python
**App:** Next.js, React, Node.js, Expo
**Data:** PostgreSQL, MongoDB, Redis
**Infra:** Docker, Kubernetes
**AI:** Claude API, OpenAI API — agentic pipelines, not just chat wrappers

## Currently

Building [MycoRealms](https://github.com/crypticmeta) — a futarchy-governed, radically transparent real-world agriculture DAO. Same on-chain-accountability instincts as the escrow and payment work above, applied outside crypto.

Open to short, well-scoped contracts (Solana/EVM smart contracts, escrow/payment rails, AI agent products). Reach me on [Telegram](https://t.me/crypticmetadev) or [X](https://x.com/crypticmetadev).
