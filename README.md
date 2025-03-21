# Loan_Limit_Optimization
Jupyter Notebook (loan_limit_optimization.ipynb) – Contains all code, analysis, and results.
# Loan Limit Increase Optimization

## Overview
This project aims to develop an optimized loan limit increase strategy using **machine learning** and **operations research techniques**. The approach balances **profitability and risk** by leveraging **predictive modeling, Markov chains, Monte Carlo simulations, and constraint optimization**.

## Dataset
- **Records:** 30,000 customer loan transactions
- **Features:** Initial loan amount, repayment history, eligibility, estimated default risk, and total profit contribution

## Key Objectives
1. **Predict Loan Uptake:** Develop a forecasting model to estimate the likelihood of customers accepting loan limit increases.
2. **Risk Assessment:** Use probabilistic models (Markov Chains, Monte Carlo) to evaluate default risks.
3. **Profit Maximization:** Implement optimization techniques to maximize profitability under regulatory and financial constraints.
4. **Operational Recommendations:** Provide actionable insights for integrating ML-based loan approval systems.

## Implementation Steps
### 1. **Exploratory Data Analysis (EDA)**
- Checked for missing values (none found)
- Analyzed risk distribution (**Prime vs. Near-Prime customers**)
- Evaluated default risk trends

### 2. **Machine Learning Model for Approval Decision**
- **Model Used:** Logistic Regression
- **Accuracy:** 100% (Precision, Recall, and F1-score also perfect)
- **Approval Rate:** 55.98%
  - Prime: 56.37%
  - Near-Prime: 55.84%

### 3. **Risk & Profitability Analysis**
- Average **profit contribution for approved customers:** $79.88
- **Near-Prime Default Risk:** 12.47%
- **Prime Default Risk:** 2.54%

### 4. **Optimization & Simulation**
- **Markov Chain Modeling:** Predict customer state transitions
- **Monte Carlo Simulation:** Assess future default probabilities
- **Linear Programming:** Optimize loan increase decisions for maximum profitability

## Results & Recommendations
1. **Increase Limits Dynamically:** Only approve increases for customers with improving risk profiles.
2. **Risk-Based Pricing:** Charge higher interest rates for higher-risk customers.
3. **Behavioral Nudges:** Encourage on-time payments for eligibility improvements.
4. **Automated Loan Approval System:** Deploy a real-time ML model for decision-making.

## Repository Structure
```
📂 loan-limit-optimization
│── 📁 data
│   ├── loan_limit_increases.xlsx  # Dataset
│── 📁 models
│   ├── trained_model.pkl          # Saved ML model
│── 📁 notebooks
│   ├── loan_limit_optimization.ipynb  # Jupyter Notebook
│── 📁 reports
│   ├── Loan_Limit_Report.pdf  # Final analysis report
│── README.md
```

## How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/loan-limit-optimization.git
cd loan-limit-optimization
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook notebooks/loan_limit_optimization.ipynb
```

## Future Enhancements
- Implement **Reinforcement Learning** for dynamic loan limit strategies.
- Enhance **real-time scoring models** using more advanced deep learning techniques.
- Integrate **external economic factors** into the optimization framework.

---
🔹 **Author:** Muaz  
📌 **Contact:** www.linkedin.com/in/muhammad-muaz-khan-40a73526b  
🚀 **Email:** muaz.khan180@gmail.com  

