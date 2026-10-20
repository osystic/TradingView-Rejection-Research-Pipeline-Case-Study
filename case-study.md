# TradingView Rejection Research Pipeline

## P — Problem & constraints

Document a completed minute-level market-research workflow with explicit data-quality checks, engineered features and chronological validation while keeping licensed/raw data and private research artifacts out of the public repository.

## A — Architecture & decisions

The private workflow uses Python/Colab for chunked OHLCV acquisition, validation/cleaning, ATR and relative-volume feature engineering, structural/event features, target preparation and time-ordered modelling.

## C — Contribution & delivery

OSYSTIC implemented the private data-quality, feature-construction, target-preparation and chronological modelling workflow together with exported research scripts and retained validation evidence.

## Engineering highlights

- Added explicit checks for missing values, dead candles, time gaps and invalid price structure.
- Engineered ATR, relative-volume and structural/event features from minute-level market data.
- Preserved chronological train/test separation to reduce look-ahead leakage.
- Retained feature-audit and baseline-modelling steps alongside the research pipeline.
- Kept raw/licensed datasets and API credentials outside the public showcase.

## Technology stack

- Python
- Google Colab
- Minute-level OHLCV processing
- ATR feature engineering
- Relative-volume feature engineering
- Chronological validation
- Feature scaling
- Baseline statistical modelling

## E — Evidence & outcomes

Private source verifies the implemented data checks, feature engineering and chronological validation methodology. Public claims are limited to documented research-engineering capability.

## Confidentiality

Raw/licensed datasets, API credentials, private notebooks/scripts, client identity and research artifacts remain private.
