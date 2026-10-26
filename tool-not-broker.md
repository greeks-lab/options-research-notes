# Concepts: research tool ≠ broker (and not a signal service)

**Audience:** developers and users installing [AlphaGBM/skills](https://github.com/AlphaGBM/skills)  
**Related site pages:** [alphagbm.com/en](https://www.alphagbm.com/en) · [options](https://www.alphagbm.com/en/options) · [pricing](https://www.alphagbm.com/en/pricing) · [skills](https://www.alphagbm.com/en/skills)

## Short answer

AlphaGBM Skills bring **market research workflows** into your AI workspace (Claude Code, Cursor, and similar). They help you gather dated evidence, compare candidates, and review risk language. They are **not** a broker, **not** an order router, and **not** a signal service that tells you what to buy or sell.

Installing a Skill does **not** unlock paid data by itself. Account-backed research shares the website’s allowance and subscription rules. See [ACCESS.md](./ACCESS.md) and live [Pricing](https://www.alphagbm.com/en/pricing).

## What Skills are for

| Use | Meaning |
| --- | --- |
| Research | Fundamentals, sentiment, risk notes, options strategy screens, news impact framing |
| Evidence hygiene | Keep source dates, missing-data flags, and score definitions |
| Local review | Investment Review compares files **you** supply locally |

## What Skills are not

| Claim to avoid | Why |
| --- | --- |
| Broker / auto-trade / managed money | No order placement; Smart Money Tracking summarizes disclosed records and never copies or places trades (README) |
| “Agent free / unlimited quota from install” | Installation is free; research credits follow the account plan |
| Return guarantees | Public site: research only; past performance ≠ future results |
| DEX / on-chain trading front-end | Any separate DEX product is **out of scope** for this repository and must not be attributed to AlphaGBM Skills |

## Practical rules for agents using these Skills

1. Ask before consuming shared research allowance when a runner uses `--confirm-usage`.
2. Return successful API responses with original identity, dates, units, and missing-data flags—never silently substitute demo data.
3. Surface nonzero exits as errors.
4. Do not invent fills, net P&L, or “guaranteed” opportunity lists.

## Risk note (options)

Options involve leverage. Buyers can lose the full premium. Sellers can face losses larger than the premium received. Content is for information and research only—not investment advice.

## See also

- [CONCEPTS_SCORE_NOT_WIN_RATE.md](./CONCEPTS_SCORE_NOT_WIN_RATE.md)
- [INSTALLATION.md](./INSTALLATION.md)
- [ACCESS.md](./ACCESS.md)
