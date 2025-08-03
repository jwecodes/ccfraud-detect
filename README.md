# Credit Card Fraud Transaction Detection

## Overview

This project aims to build a machine learning model that detects whether a credit card transaction is **normal** or **fraudulent**. Using a real-world dataset, various data analysis and modeling techniques are applied to predict the likelihood of fraud with high accuracy.

## Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).
- **Rows**: 284,807 transactions
- **Features**: 30 principal components (`V1`–`V28`), `Time`, `Amount`
- **Target**: `Class` (`0` = Normal, `1` = Fraudulent)
- **Note**: The dataset is highly imbalanced, as only 0.17% of transactions are fraudulent.

## Approach

1. **Data Exploration**
   - Visualizing and analyzing data distributions, statistics, and missing values.
   - Understanding class imbalance.

2. **Data Preprocessing**
   - Handling missing values (if any)
   - Feature scaling and normalization
   - Splitting the data into training and testing sets

3. **Model Building**
   - Logistic Regression (as a baseline model)
   - (Can be extended with Decision Trees, Random Forest, XGBoost, etc.)
   - Addressing class imbalance using techniques like class weighting or SMOTE (optional).

4. **Evaluation**
   - Confusion Matrix
   - Classification Report (Accuracy, Precision, Recall, F1-Score)
   - ROC-AUC Curve

5. **Visualization**
   - Distribution plots
   - Correlation heatmaps
   - Model performance visuals

## Getting Started

### Prerequisites

- Python 3.7 or above
- Jupyter Notebook

## Results

- **Baseline model**: Logistic Regression
- **Key metrics**: Achieves high recall and precision on the minority (fraud) class
- Handles heavy class imbalance with proper evaluation focus

## Project Highlights

- Explains end-to-end workflow: EDA ➡️ Preprocessing ➡️ Modeling ➡️ Evaluation
- Clean, well-commented code for reproducibility
- Ready for extension with other ML models or advanced techniques

## License

This project is licensed under the MIT License.

*Happy coding! If you find this project useful, give it a star ⭐ and consider contributing!*
