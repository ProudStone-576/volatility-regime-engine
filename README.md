# Volatility Regime Detection System

This project implements a walk-forward, non-leaky volatility regime detection model
designed to identify environments favorable for volatility-based options strategies.

## What it does
- Computes realized volatility from equity returns
- Labels forward volatility expansion events
- Trains a probabilistic regime classifier using walk-forward validation
- Outputs volatility expansion probabilities (not price direction)

## What it is NOT
- Not a directional trading system
- Not a high-frequency strategy
- Not an options pricer

## Intended use
- Regime filtering for options strategies (e.g. calendars, diagonals)
- Research and educational purposes

## Status
Baseline model complete.
Execution layer intentionally excluded.
