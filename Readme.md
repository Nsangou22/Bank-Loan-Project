# 🏦 Bank Loan Prediction & Analysis

## 📌 Overview
This project combines **Machine Learning** and **Power BI** to analyze bank loan applications and predict whether a loan will be **fully repaid** or **not**.

- **1 = Fully Paid** 🟢  
- **0 = Not Fully Paid (Charged Off or Current)** 🔴  

The goal is to help financial institutions evaluate the likelihood of loan repayment.

---

## 📂 Project Structure
bank_loan_project/
│
├── data/ # sample dataset
├── ML notebooks/ # Jupyter notebook
│ └── bank_loan_ml.ipynb
├── powerbi/ 
│ └── Bank_loan.pbix
│ └── screenshots/ # images of dashboard
└── README.md # project documentation

---

## 🤖 Machine Learning
Steps followed in the notebook:
1. **Data preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Target transformation**  
   - Fully Paid = **1**  
   - Charged Off + Current = **0**  

3. **Model training**  
   - Logistic Regression, Random Forest, etc.  
   - Evaluation metrics: **Accuracy, Precision, Recall, F1-score**  

---

## 📊 Power BI Dashboard
The dashboard provides insights such as:
1. **Loan Portfolio Overview** – Summary of total applications, funded amounts, amounts received, and average interest/DTI.  
2. **Loan Status Analysis** – Distribution of Fully Paid, Charged Off, and Current loans.  
3. **Trend Analysis** – Month-over-month changes in applications, funded amounts, and amounts received.  
4. **Borrower Demographics** – Insights into loan terms, purposes, and borrower profiles.   

### Dashboard Preview:
![Dashboard Screenshot](powerbi/screenshots/dashboard.png)

---

## ⚙️ How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/bank_loan_project.git
   cd bank_loan_project ```
   
2. Install dependencies (if using Python notebook):
   '' pip install -r requirements.txt ''

3. Open the notebook in Jupyter:
    jupyter notebook/Bank_loan_prediction_LoanStatus.ipynb
	
4. Open the .pbix file in Power BI Desktop to explore the dashboard.

---

## 🛠️ Tools & Technologies

Python: Pandas, Numpy, Scikit-learn, Matplotlib etc

Jupyter Notebook

Power BI Desktop

## 👤 Author
- Nsangou Abdel Raim 
- [LinkedIn](https://linkedin.com/in/nsangou-ngoupayou-abdel-raim-aa32612b5)  
- [GitHub](https://github.com/Nsangou22)
