# Forecasting industry-level corporate revenue

> Historical portfolio project from SMU DSA301 Time Series Analysis. The repository preserves the submitted work and is not actively maintained.

## Overview

This group project aggregated Russell 1000 company revenue by GICS industry and compared time-series forecasting approaches, including STL decomposition, SARIMAX, VAR, and VECM models. Out-of-sample statistics were used to compare model performance, with supporting checks for stationarity, cointegration, autocorrelation, and residual behaviour.

The project was completed by a team of six. The repository contains the group report together with the repository owner's Python data-preparation work and R analysis of the Healthcare sector and cross-industry VAR model. Consult the report for the full contributor list and project context.

## Repository contents

| Path | Purpose |
| --- | --- |
| `Final Report.pdf` | Group report, methodology, results, and contributor context. |
| `Russell1000_Data.ipynb` | Russell 1000 ticker and revenue-data preparation. |
| `Healthcare_VAR_code.rmd` | Healthcare forecasts and cross-industry VAR analysis. |

## Reproducibility status

This repository is a portfolio artifact and is **not reproducible from the tracked files alone**. The analysis references untracked inputs including:

- `Russell1000_Tickers.csv` and `Russell1000_Data.csv`;
- `data/IndustryRevenues.csv`;
- population, federal-funds-rate, GDP-growth, and VIX CSV files under `data/`.

Some corporate revenue inputs originated from Compustat and may be subject to subscription and redistribution restrictions. They are not included here. Anyone rebuilding the project should obtain authorized source data, recreate the documented schemas, and verify the meaning and vintage of every series.

## Historical environment

The Python notebook uses pandas, requests, and Beautiful Soup. The R analysis uses dplyr, ggplot2, forecast, and additional namespaced packages including `vars`, `tseries`, and `lmtest`. Versions were not pinned and current compatibility is unverified.

## Limitations

The forecasts reflect the original data vintage, industry definitions, transformations, and evaluation period. They are academic results, not current investment forecasts.

## License and reuse

No open-source license has been applied. The project is shared for viewing as portfolio work. Group-authored material and third-party data remain subject to their respective rights.