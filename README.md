# ML Experiment Lab

A reproducible machine learning experiment and benchmarking system.

## Overview

ML Experiment Lab automates the process of running multiple machine learning experiments with controlled configurations and random seeds.

The project demonstrates:

- Dataset validation
- Reusable preprocessing
- ML experiment execution
- Multi-model benchmarking
- Reproducible random seeds
- Configuration-driven experiments
- Experiment logging
- Structured experiment records
- Result persistence

## Experiment Workflow

Dataset  
↓  
Validation  
↓  
Preprocessing  
↓  
Model Training  
↓  
Evaluation  
↓  
Benchmarking  
↓  
Structured Results

## Models

The current benchmark includes:

- Logistic Regression
- Random Forest

Each model is evaluated using multiple random seeds.

## Metrics

Experiments record:

- Accuracy
- Precision
- Recall
- F1 score
- Training time
- Inference time

## Dataset

The current prototype uses the Breast Cancer Wisconsin dataset provided by scikit-learn.

## Project Status

Prototype completed in Google Colab. The next stage is to organize the implementation into reusable Python modules and add containerized execution.
## Benchmark Results

The experiment runner was evaluated using two classification models across three random seeds.

| Model | Accuracy | Precision | Recall | F1 | Avg. Training Time | Avg. Inference Time |
|---|---:|---:|---:|---:|---:|---:|
| Logistic Regression | 98.25% | 98.17% | 99.07% | 98.62% | 0.0201s | 0.0028s |
| Random Forest | 96.49% | 96.81% | 97.69% | 97.24% | 0.3017s | 0.0089s |

Results are averaged across three random seeds: 42, 123, and 456.

Logistic Regression achieved higher average accuracy and F1 score while also requiring substantially less training and inference time in this benchmark.

The raw experiment results and structured experiment records are included in the repository as CSV files.