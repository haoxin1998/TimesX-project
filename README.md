# TimesX Project Page

Static project page for:

**Rethinking Multimodal Time-Series Forecasting Evaluation**

GitHub Pages URL:

https://haoxin1998.github.io/TimesX-project/

## Dataset

The TimesX benchmark dataset is included in this repository under
[`Datasets/`](Datasets). The data cutoff has been refreshed to March 2026.

```text
Datasets/                 # TimesX benchmark data (cutoff refreshed to March 2026)
|-- SearchTrend/          # Google Search Trend data (weekly)
|-- Currency/             # USD exchange rates (daily)
`-- CommodityPrice/       # Commodity prices (daily)
```

Samples without valid event context (`metadata.event_count == 0`) are excluded.
