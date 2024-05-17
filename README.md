# MLflow Machine Learning Lifecycle

This repository contains code demonstrating the use of MLflow to manage the machine learning lifecycle. MLflow is an open-source platform for managing the end-to-end machine learning lifecycle, including experiment tracking, model training, hyperparameter tuning, model deployment, and monitoring.

## Overview

The code in this repository demonstrates how to use MLflow in various stages of the machine learning lifecycle:

- **Experiment Tracking**: Logging parameters, metrics, and artifacts during model training.
- **Model Training and Tuning**: Training and tuning machine learning models using MLflow tracking and hyperparameter optimization.
- **Model Deployment**: Deploying trained models as REST APIs using MLflow model serving capabilities.
- **Performance Monitoring**: Monitoring deployed models for drifts in performance metrics over time.
- **Model Registry**: Managing model versions and lifecycle transitions using MLflow Model Registry.

## Code Information

The code in this repository is based on a project aimed at predicting loan defaults using a dataset from the finance domain. It includes:

- **Data Preprocessing**: Preprocessing the dataset to prepare it for model training.
- **Model Training**: Training machine learning model on the preprocessed data.
- **Hyperparameter Tuning**: Optimizing model hyperparameters using MLflow's hyperparameter tuning capabilities.
- **Model Deployment**: Deploying the model as a REST API using MLflow's model serving capabilities.
- **Experiment Tracking**: Logging parameters, metrics and models during model training using MLflow tracking.
- **Performance Monitoring**: Setting up mechanisms to monitor the deployed model's performance over time using MLflow.

## Prerequisites

Before running the code in this repository, ensure that you have the following dependencies installed:

- Python 3.x
- MLflow (install using `pip install mlflow`)

## Conclusion

This repository serves as a comprehensive demonstration of utilizing MLflow to streamline the machine learning lifecycle. By leveraging MLflow's robust capabilities for experiment tracking, model training, hyperparameter tuning, model deployment and performance monitoring.

