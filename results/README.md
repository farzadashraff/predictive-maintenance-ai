## Results

This folder contains the numerical outputs generated during experimental evaluation of the predictive maintenance framework.

### Files

- summary_metrics.csv  
  Aggregated MAE comparison across individual models (GBM, LSTM, CNN) and the adaptive meta-controller.

- ablation_mae_results.csv  
  Ablation study results comparing pairwise model combinations (GBM+LSTM, GBM+CNN, LSTM+CNN).

- runtime_preds_vectorized.csv  
  Per-unit runtime predictions including model outputs, confidence scores, fusion weights, and final meta prediction.

- meta_predictions_3model_reweighted.csv  
  Meta-controller predictions after confidence-based reweighting of GBM, LSTM, and CNN outputs.

- cnn_unit_preds.csv  
  CNN-based frequency-domain predictions generated from FFT-transformed vibration signals.

- worst_case_errors_top10.csv  
  Top 10 engine units with the highest absolute prediction error for the adaptive meta-controller.

All results are derived from the CMAPSS FD001 dataset and are provided in CSV format for reproducibility and further analysis.
