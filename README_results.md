# Results Overview

This folder contains quantitative outputs generated during the evaluation of the predictive maintenance framework.

## Files Description

- summary_metrics.csv  
  Overall MAE comparison for individual models (GBM, LSTM, CNN) and the adaptive meta-controller.

- mae_results.csv  
  Mean Absolute Error values computed against true Remaining Useful Life (RUL) targets.

- ablation_mae_results.csv  
  MAE results for pairwise model combinations used for ablation analysis.

- meta_predictions_3model_reweighted.csv  
  Final meta-controller predictions obtained after confidence-based model fusion.

- runtime_preds_vectorized.csv  
  Inference-time predictions including per-model outputs, confidence scores, and adaptive weights.

- cnn_unit_predictions.csv  
  CNN-only predictions used to evaluate frequency-domain fault detection performance.

- confidence_scores.csv  
  Confidence estimates produced by each model during inference.

- worst_case_errors_top10.csv  
  Units with the highest absolute prediction error, used for failure case analysis.

All results are generated from the CMAPSS turbofan engine dataset.