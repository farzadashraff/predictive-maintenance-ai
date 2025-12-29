# Predictive Maintenance of Industrial Machinery using AI

This repository contains the implementation and experimental artifacts for a hybrid AI-based predictive maintenance system designed to model both gradual equipment degradation and sudden failure behavior in industrial machinery.

The project integrates Gradient Boosting Machines (GBM), Long Short-Term Memory (LSTM) networks, and Convolutional Neural Networks (CNN) under a confidence-driven meta-controller that dynamically adapts model influence based on prediction reliability rather than static weighting.

## Project Motivation
Traditional predictive maintenance systems often rely on a single model or static ensembles, which struggle under non-stationary operating conditions. This work explores an adaptive fusion strategy that emphasizes robustness, interpretability, and deployment feasibility over purely benchmark-driven optimization.

## Repository Structure

- **paper/**  
  Contains the research paper describing the methodology, experiments, and findings.

- **figures/**  
  Architecture diagrams, workflow illustrations, and result visualizations used in the paper.

- **notebook/**  
  Jupyter notebook containing data preprocessing, model training, inference, and evaluation code.

- **results/**  
  CSV files containing experimental outputs such as MAE metrics, ablation study results, runtime predictions, and worst-case error analysis.  
  A detailed description of each file is provided in `results/README_results.md`.

## Key Features
- Hybrid modeling using GBM, LSTM, and CNN
- Confidence-based adaptive model fusion
- Monte Carlo Dropout for uncertainty estimation
- End-to-end pipeline from preprocessing to inference
- Edge deployment considerations using TensorFlow Lite

## Notes
This repository focuses on transparency and reproducibility. The results reflect practical engineering trade-offs and include both strengths and limitations observed during experimentation.