# Data sources and reconstruction notes

This historical portfolio does not redistribute the licensed and locally prepared inputs used by the original group project.

## Expected inputs

| Expected path | Role | Availability note |
| --- | --- | --- |
| `Russell1000_Tickers.csv` | Russell 1000 company and industry identifiers used by the Python notebook. | Recreate from an authorized and dated constituent source. |
| `Russell1000_Data.csv` | Company-level revenue data used during aggregation. | Original project data included subscription-derived corporate information and is not distributed here. |
| `data/IndustryRevenues.csv` | Quarterly revenue aggregated by industry. | Recreate from authorized company-level inputs and the original aggregation logic. |
| `data/POPTHM (1).csv` | Population series used by the R analysis. | Obtain from the provider identified in the project materials and verify its vintage. |
| `data/FEDFUNDS.csv` | Federal-funds-rate series. | Obtain from the provider identified in the project materials and verify its vintage. |
| `data/usgdpchange.csv` | GDP-growth series. | Obtain from the provider identified in the project materials and verify its vintage. |
| `data/vix.csv` | VIX series. | Obtain from the provider identified in the project materials and verify its vintage. |

## Reconstruction guidance

1. Confirm that you are authorized to access and use each source.
2. Recreate the intermediate CSV schemas expected by the notebook and R Markdown.
3. Check GICS classifications, company membership dates, units, fiscal-quarter alignment, and missing-value treatment.
4. Record the source vintage because constituent lists and macroeconomic series can be revised.
5. Compare reconstructed outputs with `Final Report.pdf`, allowing for differences caused by revised data.

The report is the authoritative record of the submitted group analysis; this file documents only the missing-input boundary of the public portfolio.
