# 💳 Credit Card Fraud Transaction Detection

This project focuses on identifying fraudulent credit card transactions using machine learning classification techniques. It leverages a highly imbalanced dataset to build a predictive model that can classify whether a transaction is fraudulent or legitimate.

## 🧠 Objective

Detect fraudulent credit card transactions using transaction features such as time, amount, and anonymized principal components (V1 to V28).

## 🗂️ Dataset Description

- **Source**: The dataset is a real-world anonymized dataset of [European credit card transactions](https://www.kaggle.com/mlg-ulb/creditcardfraud).
- **Features**:
  - `Time`: Seconds elapsed between each transaction and the first transaction.
  - `Amount`: Transaction amount.
  - `V1` to `V28`: Result of PCA (to anonymize sensitive information).
  - `Class`: Target (0 = Legitimate, 1 = Fraud)

⚠️ **Note**: The dataset is highly imbalanced — only ~0.17% of transactions are fraudulent.

## 🔧 Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (EDA & visualization)
- Scikit-learn (ML modeling)

## 🚀 Approach

1. **Data Exploration**
   - Visualizing and analyzing data distributions, statistics, and missing values.
   - Understanding class imbalance.

2. **Data Preprocessing**
   - Handling missing values
   - Feature scaling and normalization (e.g., for 'Amount' and 'Time')
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

## 📊 Results

1. **Baseline model**: Logistic Regression
2. Model evaluation metrics on the test data:
   - **Accuracy**: ~99.45%
   - **Precision**: ~91.00%
   - **Recall (Sensitivity)**: ~81.50%
   - **F1-score**: ~86.00%
   - **ROC-AUC Score**: ~97.80%
3. **Key metrics**: Achieves high recall and precision on the minority (fraud) class and handles heavy class imbalance with proper evaluation focus.
4. These results indicate that the model is highly effective in detecting fraudulent transactions while maintaining a low false positive rate.

## Prerequisites

- Python 3.7 or above
- Jupyter Notebook

## License

This project is licensed under the MIT License.

*Happy coding! If you find this project useful, give it a star ⭐ and consider contributing!*

##
##
