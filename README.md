
# Bank Client Eligibility Prediction

## 📌 Description
This project predicts bank loan eligibility using machine learning.  
We analyzed 3,000+ banking records to understand customer behavior and identify factors influencing loan approval. The goal is to provide actionable insights to support data-driven decisions.

## 🔹 Key Contributions
- Performed **Exploratory Data Analysis (EDA)** to examine demographics and financial behavior of clients  
- Identified **key features** influencing loan eligibility: income, savings, credit balance, and risk score  
- Executed **data cleaning, preprocessing, and feature engineering** to prepare the dataset for modeling  
- Built and compared **Logistic Regression** and **Random Forest** models  
- Evaluated model performance using **Accuracy, Precision, Recall, and ROC-AUC**  
- Generated insights to support **data-driven loan approval decisions**


## ⚙️ Technologies Used
- **Python**  
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn  

## 📈 Results
| Model                  | Accuracy | Precision | Recall | ROC-AUC |
|------------------------|----------|-----------|--------|---------|
| Logistic Regression    | 0.83     | 0.81      | 0.78   | 0.86    |
| Random Forest          | 0.88     | 0.85      | 0.84   | 0.91    |

**Key Insight:** Income and credit balance are the strongest predictors of loan eligibility. Clients with higher income and positive credit balances have a higher probability of loan approval.

## 🔗 How to Run
1. Clone this repository:  
```bash
git clone https://github.com/Leila-el-azhar/bank-client-eligibility-prediction.git
