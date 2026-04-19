# alpha-price-breakout

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-price-breakout/blob/main/notebooks/alpha_price_breakout.ipynb)

> Price channel breakout alpha signal

> A 20-day channel breakout: long when today's close exceeds the prior 20-day high (momentum entry), short when it falls below the prior 20-day low. Simple, robust, and captures the initial thrust of a new trend. The parameter sweep examines lookback windows from 10 to 60 days.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | L2/S2 signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity (breakout window) |
| 7 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

