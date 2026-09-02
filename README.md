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
