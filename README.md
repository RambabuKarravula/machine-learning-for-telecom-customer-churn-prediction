<div align='center'>
  

  <h1>machine learning for telecom customer churn prediction</h1>

  <p>
  Explored various machine learning algorithms such as Logistic Regression, Decision,
Forest, Support Vector Machines (SVM), and GradientBoosting Machines (GBM) for churn prediction. Evaluated model performance using metrics like accuracy, precision, recall, F1-score, and area under the ROC curve (AUC). Utilized techniques like cross-validation and hyperparameter tuning to optimize model performance and generalization.

  </p>
  

<!-- Badges -->

<a href="https://github.com/RambabuKarravula/machine-learning-for-telecom-customer-churn-prediction.git"


<br />




## :signal_strength: Dataset

The trained dataset is originally from the IBM Sample Datasets. The objective is to predict behavior to retain customers by analyzing all relevant customer data and developing focused customer retention programs. The dataset can be found on [`Kaggle`](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It includes following information:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

### Details
- Number of Rows: 7043 (Customers)
- Number of Columns: 21 (Features)
- Missing Attribute Values: Yes
- Class Distribution: (churn value Yes is interpreted as "customer churn")



## :toolbox: Dependecies

`streamlit`

`pandas==1.4.4`

'Numpy==1.2.6'

`scikit-learn==1.2.1`

## :Follow the Steps to Install

Clone the repository and install the required dependencies using the following commands:

```bash
git https://github.com/RambabuKarravula machine-learning-for-telecom-customer-churn-prediction.git
```

```bash
cd machine-learning-for-telecom-customer-churn-prediction
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run streamlit.py
```

