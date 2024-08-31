# Online Payment Fraud Detection 🛡️💳

## Overview 📝

The **Online Payment Fraud Detection** project uses machine learning to identify fraudulent transactions in online payment systems. By analyzing various transaction features, this model classifies transactions as either fraudulent or legitimate. 🕵️‍♂️🔍💡

## Project Components 🛠️

1. **Data Preparation**: The dataset is read and preprocessed to handle missing values, transform categorical features, and address outliers. 📊🧹

2. **Feature Engineering**: Categorical features are converted into numerical values, and feature skewness is adjusted by removing outliers. 🔧📉

3. **Exploratory Data Analysis (EDA)**: Various visualizations and statistical analyses are performed to understand the distribution of features and relationships between variables. 📈📉🔍

4. **Model Training**: A Decision Tree Classifier is trained on the preprocessed dataset. The model's performance is evaluated on test data. 🏋️‍♂️📚

5. **Prediction**: The trained model predicts the fraud status of new transactions based on given features. 🤖📊

## Dataset 📂

The dataset used, named `MachineLearningProject.csv`, includes:

- `Unnamed: 0`: Index column
- `step`: Time step (1 hour) ⏳
- `type`: Type of online transaction (e.g., PAYMENT, TRANSFER) 💸
- `amount`: Transaction amount 💵
- `nameOrig`: Originating customer 🏦
- `oldbalanceOrg`: Balance before transaction 💰
- `newbalanceOrig`: Balance after transaction 📈
- `nameDest`: Recipient customer 🏤
- `oldbalanceDest`: Initial balance of recipient 🏦
- `newbalanceDest`: New balance of recipient 📉
- `isFraud`: Indicates if the transaction is fraudulent (1) or not (0) 🚨
- `isFlaggedFraud`: Indicates if the transaction was flagged as fraud (1) or not (0) 🚩

## Getting Started 🚀

### Prerequisites 📦

Install the required packages using the provided `requirements.txt` file. 🔧

### Running the Analysis 🏃‍♂️

1. **Load the dataset** and preprocess it. 🔍
2. **Train the model** using the prepared data. 🎯
3. **Evaluate the model** to check its performance. ✅📊
4. **Make predictions** on new transaction data. 💡📈

## Example Output 🖼️

- **Model Accuracy**: 100% 🏆
- **Predictions**:
  - For certain features, the model predicts `'Fraud'`. 🚨
  - For other features, it predicts `'No Fraud'`. ✔️

## Acknowledgements 🙏

- Libraries used: `pandas`, `numpy`, `plotly`, `seaborn`, `matplotlib`, `scikit-learn` 🌟
