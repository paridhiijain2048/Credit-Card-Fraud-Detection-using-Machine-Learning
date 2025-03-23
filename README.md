# Credit Card Fraud Detection Using Machine Learning

## Abstract  
Credit card fraud results in substantial financial losses every year. Machine learning offers a powerful approach to detecting fraudulent transactions by recognizing patterns indicative of fraud. This project aims to develop a machine learning model for identifying fraudulent credit card transactions. The model will be trained using historical transaction data and tested on a separate dataset to evaluate its performance. Various machine learning techniques will be explored to determine the most effective method for fraud detection.  

**Keywords:** Credit Card Fraud Detection, Machine Learning, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.  

---

## Overview  
The widespread adoption of credit cards in daily transactions has raised concerns about security and fraud prevention. In 2019, approximately **2.8 billion** individuals worldwide were credit card users, and a large portion of them owned only a single card. Reports indicate a **44.7% increase** in credit card fraud cases in the U.S. in 2020. Fraud can be categorized into two types:  

1. **New Account Fraud** – When an unauthorized person opens a credit card account using stolen personal information. Reports of this type of fraud increased by **48%** in 2020.  
2. **Existing Account Fraud** – When a fraudster gains access to an already existing account, typically by stealing card details. Cases of this fraud type rose by **9%** in 2020.  

The alarming rise in fraud cases highlights the need for a robust fraud detection system. This study investigates different machine learning techniques to detect fraudulent transactions efficiently and minimize financial losses.  

---

## Project Goals  
The objective of this project is to accurately detect fraudulent credit card transactions, ensuring that customers are not wrongly charged for unauthorized purchases. By implementing multiple machine learning models, we aim to compare their effectiveness in fraud detection. The models will be evaluated based on accuracy, precision, recall, and other relevant metrics. Additionally, this study will explore existing research and methodologies for fraud detection to identify the most suitable approach.  

---

## Data Source  
The dataset for this project is sourced from **Kaggle**, containing transactions made by European credit card users over two days in 2013. The dataset comprises **284,808 transactions** with **31 features**, where:  

- **28 attributes** are numerical variables derived from Principal Component Analysis (PCA) for privacy reasons.  
- **The remaining three attributes** include:  
  - **Time**: Elapsed time (in seconds) since the first transaction.  
  - **Amount**: Transaction amount.  
  - **Class**: Binary indicator (1 = Fraudulent, 0 = Legitimate).  

**Dataset Link:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

---

## Machine Learning Algorithms Used  
The following machine learning algorithms were implemented to detect fraudulent transactions:  

1. **K-Nearest Neighbors (KNN)**  
2. **Logistic Regression (LR)**  
3. **Support Vector Machine (SVM)**  
4. **Decision Tree (DT)**
5. **Neaural Network MPL** 

Accuracy with each of them is :
1. **K-Nearest Neighbors (KNN)**  -
2. **Logistic Regression (LR)**  
3. **Support Vector Machine (SVM)**  
4. **Decision Tree (DT)**
5. **Neaural Network MPL** 


Each model was trained and evaluated to determine its efficiency in classifying fraudulent transactions.  

---

## Future Enhancements  
Several improvements can be made to enhance fraud detection:  

- Testing the model on **diverse datasets** to ensure its generalizability.  
- **Optimizing data preprocessing** methods, such as adjusting the data-splitting ratio to improve accuracy.  
- **Integrating external data sources**, such as telecom location data, to verify the cardholder’s actual location during a transaction. This can help detect anomalies where transactions occur in different geographic locations within an unreasonably short period.  

---

## Conclusion  
This project explored various machine learning models to detect fraudulent credit card transactions. By comparing multiple techniques, we identified the most effective approaches. **KNN and Decision Tree models demonstrated the highest accuracy**, making them suitable candidates for fraud detection. Implementing such models in real-world financial systems can significantly improve security, reducing fraud risks and enhancing customer confidence in credit card transactions.  
