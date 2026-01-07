# Round Accounting & Dynamic Allocation

The protocol runs in **10‑minute rounds**.

## Tracking
During Round **N**, track total SOL spent to seize each flag inside the window:

- `S_i` = SOL spent on flag *i*  
- `S_total = Σ S_i`

## Next-round rate
In Round **N+1**, total baseline emission is:

- `12.5 $FLAGS/sec` (5 flags × 2.5 baseline)

Each flag’s actual mining rate becomes:

`rate_i = 12.5 × (S_i / S_total)  $FLAGS/sec`

## Reward ownership
Whoever controls a flag during Round N+1 mines continuously at `rate_i`.  
Because flags can be seized at any time, realized rewards depend on **holding time × round rate**.
