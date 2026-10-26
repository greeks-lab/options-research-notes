# Concepts: opportunity score ≠ win rate

**Audience:** developers and users of AlphaGBM Skills / website research scores  
**Related site pages:** [alphagbm.com/en](https://www.alphagbm.com/en) · [skills](https://www.alphagbm.com/en/skills)

## Short answer

An **opportunity score** is a ranked or composite indicator used to sort candidates **inside a defined screen**. It is **not** a historical or forecast **win rate**, and it is **not** a buy signal.

AlphaGBM’s public English homepage states that options candidates are ranked by opportunity score **within each strategy**, not as a whole-market scan; scores are **not win probabilities** and are not ranked across strategies; a score ≥80 marks a “high score,” **not** a buy signal.

## Why the distinction matters

| Concept | Typical meaning | Misuse |
| --- | --- | --- |
| Opportunity score | Relative ranking / composite under stated filters | “82% chance I profit” |
| Win rate | Frequency of profitable outcomes in a defined sample | Assuming the score *is* that frequency |
| Buy signal | Explicit recommendation to transact | Reading ≥80 as “buy” |

A win rate needs clear entry/exit rules, costs, sample period, and survivorship handling. A research score does not automatically publish those. Even a carefully measured win rate is not a promise of future results.

## Rules for Skill runners and agent copy

- Preserve score type labels (e.g. stock risk scores are not opportunity scores).
- Do not rewrite scores as probabilities or “win rates.”
- Do not invent backtests or P&L tables for AlphaGBM scores.
- Prefer multi-factor review: liquidity, expiry, assignment/funding risks, opposing evidence—not a single number.

## Forbidden phrases in Skill docs and demos

- “score = win rate”
- “whole-market real-time scan” (unless a specific product surface explicitly claims and timestamps it)
- return guarantees or fake testimonials
- “Delta = assignment probability” (Delta is a sensitivity, not an assignment odds meter)

## Risk note

Scores and yield illustrations are for information and research only—not investment advice. Past performance does not predict future results. Options involve leverage and can lose the full premium (buyers) or more (sellers).

## See also

- [CONCEPTS_TOOL_NOT_BROKER.md](./CONCEPTS_TOOL_NOT_BROKER.md)
- Website Options Strategies Skill framing on [alphagbm.com/en/skills](https://www.alphagbm.com/en/skills)
