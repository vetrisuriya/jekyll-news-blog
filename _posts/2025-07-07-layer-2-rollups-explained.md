---
layout: post
title:  "Layer‑2 Rollups Explained: ZK vs Optimistic"
date:   2025-07-07 18:50:00 +0530
categories: [crypto]
tags: [ethereum, layer2, rollups, zk, optimistic]
author: Vetri Suriya
permalink: layer-2-rollups-explained
---

Scaling Ethereum has turned into a two‑horse race between **Optimistic** and **Zero‑Knowledge (ZK) rollups**. Here’s the plain‑English breakdown.

## 1. Why Rollups?
They bundle (or “roll up”) scores of L2 transactions into a single L1 call—cutting gas and boosting throughput without sacrificing Ethereum’s security.

## 2. Optimistic Rollups

| Feature          | Detail |
|------------------|--------|
| **Assumption**   | Fraud‑proof _unless_ challenged within the dispute window.|
| **Challenge Period** | 7 days (Arbitrum), 24 hrs (Base). |
| **Finality Lag** | Users wait to be sure funds won’t be disputed. |
| **Projects**     | Optimism, Arbitrum, Base, Blast |

## 3. Zero‑Knowledge Rollups

| Feature          | Detail |
|------------------|--------|
| **Assumption**   | Validity proofs generated upfront. |
| **Finality Lag** | Minutes—no challenge window needed. |
| **Cryptography** | zk‑SNARKs, zk‑STARKs (Succinct Non‑interactive ARguments of Knowledge). |
| **Projects**     | zkSync, Starknet, Linea, Polygon zkEVM |

### 4. Choosing the Right L2
* **TX Volume & Fees** – Optimistic still cheaper today, but ZK costs are falling.  
* **Withdrawal Urgency** – Need instant exits? ZK wins.  
* **Developer Tooling** – EVM‑equivalence is improving across both camps.

### 5. Looking Ahead
EIP‑4844 (“Proto‑danksharding”) will slash calldata fees, super‑charging rollup economics. Expect UX to become chain‑agnostic by 2026.

