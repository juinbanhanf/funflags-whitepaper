# Dutch Auction (Reverse Auction)

Each flag runs an independent continuous Dutch auction.

## Rule
When a flag is seized:
- Next starting price = **2×** the last paid price
- Price then linearly decays to **0 SOL** over **6 minutes**
- Anyone may seize at any time by paying the current price

## Why it matters
- Rewards early conviction, punishes late FOMO
- Keeps flags in constant competitive motion
