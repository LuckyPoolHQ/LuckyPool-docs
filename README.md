# LuckyPool — Docs

Design and planning docs for [LuckyPool](https://github.com/LuckyPoolHQ), a no-loss prize savings protocol on Stellar. Deposit USDC, earn yield via Blend, and one depositor wins the pooled yield each week — principal is never at risk.

## Contents

| Doc | What's in it |
|---|---|
| [`architecture.md`](architecture.md) | System design, data model, contract interaction flow |
| [`smart-contracts.md`](smart-contracts.md) | Soroban contract interface, build, deploy, events |
| [`yield-integration.md`](yield-integration.md) | How yield is generated and harvested via Blend |
| [`randomness.md`](randomness.md) | VRF design, winner selection, manipulation resistance |
| [`plan.md`](plan.md) | Phases, milestones, risks |
| [`go-to-market.md`](go-to-market.md) | Partners, launch sequence, growth flywheel |
| [`pitch.md`](pitch.md) | Investor pitch deck *(confidential)* |

## Related repos

- [LuckyPool-contracts](https://github.com/LuckyPoolHQ/LuckyPool-contracts) — Soroban smart contracts
- [LuckyPool-frontend](https://github.com/LuckyPoolHQ/LuckyPool-frontend) — Next.js app
- [LuckyPool-sdk](https://github.com/LuckyPoolHQ/LuckyPool-sdk) — DrawEngine client SDK
