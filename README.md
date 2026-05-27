# Predictive Analysis of Solar Power Generation

> Transformer-based time-series forecasting for PV solar systems — **12.6% accuracy improvement** over baseline LSTM.

## Overview
End-to-end machine learning pipeline for predicting solar power generation from PV systems using a Transformer architecture trained on real-world sensor data. Includes real-time visualization dashboard for generation pattern analysis.

## Results
| Metric | Score |
|--------|-------|
| Accuracy improvement over LSTM | +12.6% |
| Architecture | Transformer (self-attention) |
| Data type | Real-world PV sensor time-series |

## Tech Stack
- **Framework:** TensorFlow / PyTorch
- **Model:** Transformer (multi-head self-attention)
- **Baseline:** LSTM
- **Visualization:** Matplotlib, real-time generation dashboard

## Key Features
- Transformer-based forecasting outperforming LSTM baseline by 12.6%
- Full preprocessing pipeline: normalization, sliding window sampling, missing value imputation
- Real-time visualization interface for generation pattern monitoring
- Modular, reproducible ML pipeline with documented components

## Dataset
Real-world PV system sensor data with irradiance, temperature, and power output readings.
