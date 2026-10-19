# sEMG Gesture Classification Using Machine Learning

## Overview

This project implements a machine learning pipeline for classifying muscle activity gestures using surface electromyography (sEMG) data.

The pipeline processes sEMG signals, extracts time-domain features, and uses a Multi-Layer Perceptron (MLP) classifier to predict gesture classes.

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Project Workflow

1. Load and prepare the sEMG dataset.
2. Divide signals into windows.
3. Extract time-domain features: Mean Absolute Value (MAV), Root Mean Square (RMS), Variance (VAR), Waveform Length (WL), and Zero Crossings (ZC).
4. Scale the extracted features.
5. Train a Multi-Layer Perceptron (MLP) classifier.
6. Evaluate the model and visualize the results.

## Project Files

- `semg_ml_pipeline.ipynb` – ML pipeline and notebook.
- `mlp_model.pkl` – Saved trained MLP model.
- `feature_scaler.pkl` – Saved feature scaler.
- `class_labels.npy` – Saved class labels.
- `training_metrics.csv` – Training and evaluation metrics.
- `confusion_matrix_data.csv` – Confusion matrix data.
- `prediction_timeline.csv` – Prediction timeline data.
- `images/` – Result visualizations.

## How to Run

Open `semg_ml_pipeline.ipynb` in Google Colab and run the notebook after obtaining the dataset required by the notebook.

The dataset is not included in this repository. Obtain it from the appropriate original source and follow its usage and licensing terms.

## Scope

This is a software-based machine learning project for sEMG gesture classification. Its predictions are experimental and are not intended for medical diagnosis.

## Author

Jenolin Joy
