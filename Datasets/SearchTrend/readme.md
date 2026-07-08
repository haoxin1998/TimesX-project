SearchTrend value scale

SearchTrend variables are weekly Google Trends search-interest indices, not raw search counts. Google normalizes each query window relative to its own peak.

For 120 variables, values through 2025-06-29 are native Google Trends integers in [0, 100]. Values from 2025-07-06 are an overlap-calibrated extension through 2026-03. The extension is expressed relative to the historical scale, so values can be fractional or exceed 100. A value of 300 means approximately three times the historical reference peak.

Do not clip the extension to 100 or assume that all values are integers. Clipping would discard real changes in relative search interest.

`food_wine_festivals` is the only exception: its extension could not be validated, so it retains 20 native-segment samples ending on 2025-06-29.
