# Medical Image Analysis with EEGNet

## Overview

This project, conducted by Riccardo Lunelli, Riccardo Parola, and Gabriele Santini, focuses on classifying patient pathologies from EEG signals using a convolutional neural network (CNN), specifically EEGNet. The primary objective is to leverage deep learning techniques to analyze EEG patterns associated with different neurological conditions.

## Data Description

The dataset, derived from fifteen epilepsy patients, includes EEG signals recorded during a verbal working memory task. The data encompass various signal parameters and are preprocessed for consistency and clarity, including frequency standardization and artifact removal.

## Methodology

- **Preprocessing:** Applied filtering and artifact removal to create a homogenized dataset.
- **Model Implementation:** Utilized EEGNet, a pretrained CNN model, with modifications to improve performance.
- **Classification Tasks:** Focused on both multiclass (specific pathologies) and binary (presence of hippocampal sclerosis) classifications.
- **Model Training:** Employed PyTorch for training, using F1 score and accuracy as primary metrics.

## Key Findings

- Transitioning to ReLU activation significantly enhanced model performance.
- The limited dataset size emphasizes the need for more extensive data for refined accuracy.
- Future work includes partitioning data for disease-focused learning and enhancing model generalizability.

## Usage

The runnable code is in the file `EEGNet_improved.ipynb`.
