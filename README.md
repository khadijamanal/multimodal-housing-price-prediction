# multimodal-housing-price-prediction
Multimodal Housing Price Prediction using CNN-extracted image features and tabular housing data. Features are combined to train a regression model and evaluated using MAE and RMSE.
# Multimodal Housing Price Prediction

## Overview
This project implements a multimodal machine learning approach for housing price prediction by combining image features extracted using a CNN (ResNet18) with structured housing data. The combined features are used to train a regression model and predict house prices.

## Features
- CNN-based image feature extraction using ResNet18
- Integration of image and tabular data
- Housing price prediction using Random Forest Regressor
- Performance evaluation using MAE and RMSE

## Dataset
- California Housing Dataset (Tabular Data)
- Synthetic Image Dataset generated using PyTorch tensors

## Technologies Used
- Python
- PyTorch
- Torchvision
- Scikit-learn
- NumPy
- Pandas

## Workflow
1. Load California Housing Dataset
2. Generate image data
3. Extract image features using ResNet18
4. Combine image and tabular features
5. Train a Random Forest Regression model
6. Evaluate results using MAE and RMSE

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Repository
Multimodal Housing Price Prediction using CNN-extracted image features and tabular housing data.
