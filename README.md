# TradingView Rejection Research Pipeline — Engineering Case Study

> **OSYSTIC ENGINEERING CASE STUDY · PUBLIC SHOWCASE · SANITIZED · PORTFOLIO-SAFE**

## Problem & constraints

Build a repeatable research workflow for minute-level market data, rejection/continuation features and chronological model validation while avoiding leakage from random train/test splitting.

## Architecture & decisions

The private research flow performs chunked OHLCV acquisition, data-quality checks, ATR/RVOL engineering, structural/event features, target merging and a time-ordered modelling baseline.

The retained feature set includes relative volume, speed into level, prior tests, pullback size, wick ratio, ATR distance and premarket context.

## Contribution & delivery

OSYSTIC retained the notebook pipeline, exported research scripts and chronological model-training/evaluation logic.

## Evidence & outcomes

Private source verifies the data-validation, feature and walk-forward methodology. Public proof intentionally excludes raw/licensed data and does not claim profitable live trading, alpha or future returns.

## Confidentiality

API keys, raw datasets, client identity, private research outputs and delivery source remain excluded.


## Public vs. private repository boundary

This repository contains **sanitized public proof only**. The confidential delivery/source repository remains private. Implementation source, API credentials, raw/licensed market data, client identity, private research outputs, and protected evidence are intentionally excluded.
