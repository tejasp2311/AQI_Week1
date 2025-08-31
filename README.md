# Air Quality Index (AQI) Prediction - Week 1

This repository contains the initial steps of the AQI prediction project, covering data loading, exploration, and preprocessing.

## Contents
- **AQI_Prediction_Pipeline.ipynb**: Jupyter notebook with code and explanations for:
  - Importing required libraries
  - Loading the air quality dataset
  - Data exploration (head, shape, info, missing values, visualizations)
  - Data preprocessing (encoding categorical columns, feature scaling)

## Instructions
1. Upload the dataset file `city_day.csv` to the project directory.
2. Open `AQI_Prediction_Pipeline.ipynb` in Jupyter, VS Code, or Google Colab.
3. Run the notebook cells sequentially to:
   - Import libraries
   - Load and explore the dataset
   - Preprocess the data (no missing value handling needed)

## Notes
- The dataset has no missing values, so imputation is skipped.
- Categorical columns (like `City`) are label encoded.
- Numerical features are scaled using StandardScaler.

## Next Steps
- Feature engineering
- Model training and evaluation
- Model saving and feature importance analysis

---

**Project: AQI Prediction Pipeline**
