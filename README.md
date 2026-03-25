# E-commerce Machine Learning Project

This project aims to analyze e-commerce orders and build machine learning models for regression, classification, and clustering.

## Project Structure

```
ecommerce-ml-project/
│
├── notebooks/
│   ├── 1_eda_and_preprocessing.ipynb  # Exploratory Data Analysis & Feature Engineering
│   ├── 2_regression_modeling.ipynb     # Price prediction and other regression tasks
│   ├── 3_classification.ipynb          # User behavior or product category classification
│   └── 4_clustering.ipynb              # Customer segmentation
│
├── artifacts/
│   ├── model.joblib                    # Trained model
│   ├── preprocessor.joblib             # Fitted preprocessor/scaler
│   └── requirements.txt                # Project dependencies
│
├── data/
│   └── ecommerce_orders.csv            # Raw dataset
│
└── README.md                           # Project documentation
```

## Getting Started

1. Install dependencies:
   ```bash
   pip install -r artifacts/requirements.txt
   ```
2. Explore the data in `notebooks/1_eda_and_preprocessing.ipynb`.
3. Train and evaluate models in subsequent notebooks.
