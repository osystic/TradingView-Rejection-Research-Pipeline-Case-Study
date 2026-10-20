# TradingView Rejection Research Pipeline

## P — Problem & constraints
Structure noisy minute OHLCV into a defensible research pipeline for rejection/continuation analysis with clear data-quality and chronology controls.

## A — Architecture & decisions
Chunked acquisition -> validation/cleaning -> ATR/RVOL and structural features -> labels -> chronological split -> scaling/logistic-regression baseline -> feature audits.

## C — Contribution & delivery
Implemented data checks, feature construction, target preparation and out-of-sample chronological modelling workflows in Colab/Python.

## E — Evidence & outcomes
The private source validates the implemented methodology. No live-trading profitability or production execution claim is made.

## Confidentiality
Raw/licensed data, API credentials and private research artifacts remain private.
