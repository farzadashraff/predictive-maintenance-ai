# Predictive Maintenance of Industrial Machinery (AI-Based)

This repository presents an end-to-end AI-based predictive maintenance system designed to model both gradual equipment degradation and sudden failure behaviors in industrial machinery.

The system integrates Gradient Boosting Machines (GBM), Long Short-Term Memory (LSTM) networks, and Convolutional Neural Networks (CNN) under a confidence-driven adaptive meta-controller.

---

## Project Highlights

- Hybrid AI framework combining degradation, temporal, and frequency-based modeling
- Confidence-aware meta-controller for adaptive model fusion
- Remaining Useful Life (RUL) prediction using the NASA CMAPSS dataset
- Emphasis on robustness, interpretability, and engineering trade-offs
- Edge deployment considerations using TensorFlow Lite

---

## Repository Structure

---

## Dataset

- NASA CMAPSS Turbofan Engine Degradation Dataset  
- Task: Remaining Useful Life (RUL) prediction

---

## Models Used

- **GBM** — Long-term degradation trends
- **LSTM** — Temporal sequence modeling
- **CNN** — Frequency-domain feature extraction (FFT)
- **Meta-controller** — Confidence-driven adaptive fusion

---

## Results

- MAE comparison across individual and hybrid models
- Ablation studies across model combinations
- Worst-case error analysis per engine unit
- Confidence score analysis for adaptive behavior

Detailed numerical results are available in the `results/` folder.

---

## Notes

This project emphasizes real-world engineering constraints and robustness over pure benchmark optimization.  
Configurations may require adjustment before reuse.

