# Real-Time Fraud Detection for Secure Financial Transactions

This project implements a **Real-Time Fraud Detection System** designed to identify and prevent fraudulent activities in financial transactions. Leveraging machine learning and data analysis, the system processes transaction data, detects anomalies, and classifies transactions as fraudulent or legitimate with high accuracy.

---

## Features

- **Real-Time Detection:** Processes transactions instantly to flag suspicious activities.
- **Machine Learning Models:** Utilizes algorithms such as Logistic Regression, Decision Trees, and Random Forests for classification.
- **Data Preprocessing:** Cleans and prepares transaction data for analysis.
- **Feature Engineering:** Extracts and selects key features to improve model performance.
- **Performance Evaluation:** Provides metrics including accuracy, recall, and F1-score for both classes.
- **Visualization:** Includes data summaries and correlation analysis for deeper insights.

---

## Dataset Overview

- **Sample Columns:**  
  - `trans_date_trans_time`: Transaction timestamp
  - `cc_num`: Credit card number (anonymized)
  - `merchant`: Merchant name
  - `category`: Merchant category
  - `amt`: Transaction amount
  - `first`, `last`: Customer name
  - `gender`, `city`, `state`, `zip`, `lat`, `long`: Demographics and location
  - `job`, `dob`: Customer job and date of birth
  - `is_fraud`: Fraud label (1 = fraud, 0 = genuine)

---

## Installation & Setup

1. **Clone the Repository**
```
git clone https://github.com/yourusername/Real-Time-Fraud-Detection-for-Secure-Financial-Transactions.git
cd Real-Time-Fraud-Detection-for-Secure-Financial-Transactions
```

2. **Install Dependencies**
```
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. **Open the Notebook**
- Launch Jupyter Notebook and open `Final_Project.ipynb`.

2. **Run Data Preprocessing**
- Clean and preprocess the dataset as described in the notebook.

3. **Train and Evaluate Models**
- Execute cells to train Logistic Regression, Decision Tree, and Random Forest models.
- Review performance metrics (accuracy, recall, F1-score).

4. **Analyze Results**
- Use provided visualizations and tables to interpret model effectiveness and data patterns.

---

## Technologies Used

- **Languages:** Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Tools:** Jupyter Notebook
- **Algorithms:** Logistic Regression, Decision Tree, Random Forest

---

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

---

## License

This project is licensed under the MIT License.

---
