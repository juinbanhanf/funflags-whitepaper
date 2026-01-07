# Protocol Summary

FunFlags combines:
- **Continuous Dutch auctions** to seize flags (competitive, fee-generating)
- **10‑minute round accounting** to dynamically allocate next-round emissions (meta + variance)
- **SOL routing** into refunds, buyback & burn, staking incentives, and auto-liquidity

## Two clocks

| Clock | Value | Meaning |
| --- | ---: | --- |
| Auction decay | 6 minutes | Price linearly decays to 0 from the starting price |
| Round length | 10 minutes | Tracks SOL spent per flag; updates next-round rates |

