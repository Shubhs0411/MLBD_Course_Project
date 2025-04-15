# Lung Cancer Mortality Prediction

# CS5644: Machine Learning with Big Data Course Project

# Project Overview

This project involves data analysis, feature engineering, and machine learning model training using Python. The code is organized into two Jupyter Notebooks:
- `eda+model_training_final_code.ipynb`: Covers exploratory data analysis (EDA) and model training.
- `feature_engineering.ipynb`: Focuses on creating and optimizing features for model input.

## Prerequisites

Before running the code, ensure the following:
- Python 3.8 or above is installed.
- A virtual environment is set up to manage dependencies.

## Installation

1. Clone the repository or download the files to your local machine.
2. Set up a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Required Libraries
The required libraries are listed in `requirements.txt` and include:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- imblearn
- scikit-learn
- xgboost
- prettytable
- featuretools
- jupyter

## How to Run

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the `Code` folder and open the provided notebooks:
   - `eda+model_training_final_code.ipynb`
   - `feature_engineering.ipynb`
3. Ensure the datasets are placed in the Data folder as referenced in the code.
4. Run the cells sequentially.

## Expected Outputs

### EDA (Exploratory Data Analysis)
- Basic dataset insights, including missing values, unique counts, and summary statistics.
- Visualizations such as histograms, pair plots, and correlation heatmaps.

### Feature Engineering
- Creation of new features for the dataset.
- Preprocessing steps, including scaling, PCA, and oversampling using SMOTE.

### Model Training
- Multiple machine learning models (e.g., Random Forest, Logistic Regression, XGBoost).
- Evaluation metrics such as accuracy, precision, recall, F1 score, ROC curves, and AUC.

## Directory Structure

```
project/
│
├── Data/                              # Contains the datasets used in the notebooks
│   └── lung_cancer_mortality_featured.csv
|   └── lung_cancer_mortality_data_large_v2.csv
│
├── Code/                              # Contains the code notebooks and scripts
│   ├── eda+model_training_final_code.ipynb
│   └── feature_engineering.ipynb
│
├── ML-BD Final Project Report.pdf      # Course Project Final Report 
├── requirements.txt                    # Required Python libraries
└── README.md                          # This file
```

## Contact

For any issues or queries, please contact the project members.

- Shubham Deshmukh: shubhamd23@vt.edu
- Spurthi Mohan: spurthim23@vt.edu
- Ruba Vignesh Balaji: rubavignesh@vt.edu
