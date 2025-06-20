# Seizure Prediction with CNN + LSTM

This project simulates real-time seizure prediction using deep learning. Leveraging Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks, it models how epileptic seizures emerge from EEG data — forecasting cognitive collapse before it occurs.

## Overview

* **Goal:** Predict preictal brain states using AI
* **Models:** CNN for spatial EEG pattern extraction, LSTM for temporal risk forecasting
* **Output:** Real-time seizure risk score

## Visualizations

All visualizations are IG-optimized and included in `/visuals`:

* EEG signals (normal vs preictal)
* CNN attention heatmap
* LSTM seizure risk score
* Full model pipeline diagram

## File Structure

```
├── visuals/                  # IG-ready figures (square, high-res)
├── cnn_lstm_pipeline.ipynb  # Main Colab notebook with model pipeline
├── data/                    # EEG data samples or links
├── README.md
```

## How It Works

1. **EEG Input:** Raw brain signals
2. **CNN:** Identifies spatial features of instability
3. **LSTM:** Learns time-based risk trajectory
4. **Output:** Seizure risk score and alert threshold

## Reference Study

Yazdani et al. (2023). *CBAM-3D CNN-LSTM with Attention for Seizure Forecasting* – Achieved 98.4% accuracy with only 0.017 false alarms/hour on CHB-MIT dataset.

## Requirements

* Python 3.8+
* PyTorch or TensorFlow
* NumPy, pandas, matplotlib, seaborn

## Try It in Colab

[Open the Notebook in Colab](#)

## Author

Made by @cognitive.engineer

Follow for more AI x brain modeling content — IG-ready projects, neurotech simulations, and real cognitive engineering.
