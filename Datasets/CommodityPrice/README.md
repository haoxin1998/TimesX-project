# CommodityPrice value corrections

Datasets_v5 replaces four invalid zero prices on 2024-03-22 with the midpoint of the adjacent trading-day values. Every occurrence of the same date was updated consistently across overlapping samples.

| Variable | Previous value | Corrected value |
|---|---:|---:|
| `oat_usd_bu` | 0 | 357.375 |
| `gasoline_usd_gal` | 0 | 2.73775 |
| `corn_usd_bu` | 0 | 439.25 |
| `lumber_usd_1000_board_feet` | 0 | 609.25 |
