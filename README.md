# Cancer_STGNN_OOD
Spatio-Temporal Graph Neural Network for Regional Cancer Prediction and OOD Generalization

# Cancer Prediction Using Spatio-Temporal Graph Neural Networks with OOD Generalization

## Project Overview

This project investigates regional cancer incidence prediction using Spatio-Temporal Graph Neural Networks (STGNNs), with a particular focus on Out-of-Distribution (OOD) generalization.

The objective is to investigate whether a model trained on historical regional cancer statistics can maintain reliable prediction performance when evaluated on unseen or distribution-shifted geographical regions.

## Dataset

U.S. Cancer Statistics (USCS), 1999–2023 ASCII dataset.

The project uses aggregated geographical cancer statistics, not individual patient records.

## Research Components

1. Dataset preprocessing and exploratory analysis.
2. Geographical graph construction.
3. Temporal feature representation.
4. STGNN model development.
5. Geographical OOD generalization evaluation.
6. Baseline comparison and robustness analysis.

## Team Responsibilities

| Team Member | Responsibility |
|---|---|
| Aditya Prakash | OOD generalization and project integration |
| Harshita Middha | Dataset preprocessing and spatial graph |
| Kajal Mishra | STGNN architecture and baseline models |

## Repository Structure

- `docs/`: Research documentation and OOD protocol.
- `src/`: Model, preprocessing and evaluation code.
- `results/`: Experimental outputs.
- `tests/`: Code validation.

## Evaluation

Primary metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

R-squared will be used as a supplementary metric when appropriate.

## Project Status

Research implementation in progress.

## Limitations

The dataset contains aggregated regional statistics. The project does not perform individual-patient diagnosis or establish clinical validity.
