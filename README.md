# LuckyPool Docs

Design, engineering, and go-to-market documentation for [LuckyPool](https://github.com/LuckyPoolHQ) — a no-loss prize savings protocol on Stellar.

This repo is organized by audience: **engineering** docs describe how the system is built, **product** docs describe why it exists and how it's positioned, **planning** tracks phases, milestones, and open risks.

---

## Start here

New to the project? Read in this order:

1. [`engineering/architecture.md`](engineering/architecture.md) — system overview and data flow
2. [`product/pitch.md`](product/pitch.md) — what problem this solves and why now
3. [`planning/plan.md`](planning/plan.md) — current phase, what's done, what's blocked

---

## Engineering

| Document | What's in it |
|---|---|
| [`architecture.md`](engineering/architecture.md) | System design, data model, contract interaction flow |
| [`smart-contracts.md`](engineering/smart-contracts.md) | Contract interface, build/test/deploy instructions, events |
| [`yield-integration.md`](engineering/yield-integration.md) | How yield is generated and harvested (Blend integration) |
| [`randomness.md`](engineering/randomness.md) | VRF design, winner-selection algorithm, manipulation resistance, provider status |

## Product

| Document | What's in it |
|---|---|
| [`pitch.md`](product/pitch.md) | Investor pitch — problem, solution, market |
| [`go-to-market.md`](product/go-to-market.md) | Partners, launch sequence, growth flywheel |

## Planning

| Document | What's in it |
|---|---|
| [`plan.md`](planning/plan.md) | Phases, milestones, open risks and decisions |

---

## Related repos

| Repo | What's in it |
|---|---|
| [LuckyPool-contracts](https://github.com/LuckyPoolHQ/LuckyPool-contracts) | Soroban smart contracts (Rust) |
| [LuckyPool-frontend](https://github.com/LuckyPoolHQ/LuckyPool-frontend) | Next.js landing page + dashboard |
| [LuckyPool-sdk](https://github.com/LuckyPoolHQ/LuckyPool-sdk) | DrawEngine SDK — typed Soroban RPC client |

---

## A note on accuracy

Docs in this repo are meant to reflect real, current implementation status — not aspirational claims. Where something is unresolved or unverified (e.g. the VRF provider decision in `randomness.md`), that's called out explicitly rather than glossed over. If you find a doc that's out of sync with the code, treat the code as authoritative and open an issue or PR.
