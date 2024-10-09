# Tool Wear Failure Prediction

## Description
This repository contains a machine learning model to predict tool wear failures in milling machines using the AI4I 2020 Predictive Maintenance dataset. The model aims to reduce production downtime and maintenance costs through early detection of tool wear.

## Dataset
The model utilizes the AI4I 2020 Predictive Maintenance Dataset, which is a synthetic dataset reflecting real-world predictive maintenance data. The dataset characteristics are as follows:

- **Type**: Multivariate, Time-Series
- **Instances**: 10,000
- **Features**: 6
- **Missing Values**: No
- **Associated Tasks**: Classification, Regression, Causal-Discovery

### Features
- **UID**: ID (Integer)
- **Product ID**: ID (Categorical)
- **Type**: Feature (Categorical)
- **Air temperature**: Feature (Continuous, K)
- **Process temperature**: Feature (Continuous, K)
- **Rotational speed**: Feature (Integer, rpm)
- **Torque**: Feature (Continuous, Nm)
- **Tool wear**: Feature (Integer, min)
- **Machine failure**: Target (Integer)
- **TWF**: Target (Integer)
