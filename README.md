# ML Final Project: Australia Precipitation Predictions

**Group Members:** Peter Pan, Sherry Tao, Eva Wu

## Project Overview
This project applies multiple machine learning models to predict precipitation patterns in Australia using historical climate data. We compare classical machine learning and deep learning approaches.

## Models Implemented
- **Random Forest** (`Final_RF.ipynb`)
- **LSTM** for temporal sequence modeling (`Final_LSTM.ipynb`)
- **CNN** for spatial/structured feature learning (`Final_CNN.ipynb`)

## Data
- Source: [https://catalog.leap.columbia.edu/feedstock/australian-gridded-climate-data-agcd]
- Preprocessing includes normalization, train-test splitting, and feature engineering.

## Evaluation
Models are evaluated using appropriate regression metrics (e.g. RMSE, MAE) and visual comparison of predicted vs observed precipitation.

## Repository Structure
- `Final_RF.ipynb`: Random Forest implementation
- `Final_LSTM.ipynb`: LSTM time-series model
- `Final_CNN.ipynb`: CNN-based model
- `README.md`: Project overview

## How to Run
Open notebooks sequentially and run all cells. Required libraries include NumPy, Pandas, Scikit-learn, TensorFlow/PyTorch.
