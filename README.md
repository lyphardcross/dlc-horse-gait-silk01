# DLC Gait Analysis Project - silk01-lyphardcross

## 📌 Project Overview

This project aims to build a gait analysis model for racehorses using DeepLabCut.

## 🧠 Workflow

1. Manual annotation done on `2025_silk_01`
2. DLC training (iteration-0 ~ 5)
3. Best model: `snapshot-best-050.pt`
4. Inference with labeled videos in progress

## 📁 Structure

- `config.yaml`: DLC project config
- `training-datasets/`: Training data (HDF5, pickle)
- `labeled-data/2025_silk_01_nologo/`: Manually labeled images and annotation files
- `evaluation-results-pytorch/`: Evaluation outputs for trained models
- `videos/` and `dlc-models-pytorch/`: Excluded from Git, but stored in Google Drive

## ☁️ Google Drive Assets (excluded from Git)

The following large or essential binary files are stored in a shared Google Drive folder:

- `videos/2025_silk_01_nologo.mp4`: Source video used for annotation and inference
- `dlc-models-pytorch/`: Trained models including `snapshot-best-050.pt`
- `evaluation-results-pytorch/`: Evaluation CSVs and plots
- `labeled-data/2025_silk_01_nologo/CollectedData_lyphardcross.h5`: HDF5 annotation file for visualization
- `training-datasets/`: Automatically generated training datasets
