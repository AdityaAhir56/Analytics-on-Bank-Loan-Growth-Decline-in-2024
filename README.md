# Data Analytics on Bank Loan Dataset

This repository presents a comprehensive data analytics project that explores key patterns, trends, and relationships within a synthetic bank loan dataset. The analysis covers various aspects including loan characteristics, customer demographics, and macroeconomic indicators, aiming to provide actionable insights for financial institutions and policymakers.

---

## 📌 Problem Statement

In 2025, India's bank loan growth declined to 9.6% from 19.1% in 2024, despite RBI's monetary policy measures. This slowdown, driven by cautious lending, subdued demand, and banks prioritizing profits, affects sectors like industry (4.9%) and personal loans (13.7%). This project aims to create a data analytics framework using a 100,000-record synthetic dataset to analyze loan growth decline, identify drivers like interest rates, credit profiles, and economic indicators, and provide insights for banks and policymakers to boost credit growth through targeted strategies.

---

## 📂 Repository Contents

- `Data_Analytics_on_Bank_Loan_dataset.ipynb` — Jupyter Notebook containing the full data analysis workflow:
  - Data cleaning and preprocessing (handling missing values, datatype correction)
  - Exploratory Data Analysis (EDA) including univariate, bivariate, and limited multivariate analysis
  - Statistical testing (correlation matrix, Chi-square tests)
  - Visualizations to highlight key trends and relationships

- `bank_loan_data.csv` — The synthetic dataset used for this analysis.

- `Data Analytics report on Bank Loan Data.pdf` — A comprehensive report summarizing the findings, interpretations, and strategic recommendations derived from the analysis. (You can link this PDF directly within GitHub if you upload it to the repo or host it elsewhere.)

---

## 🔍 Key Insights

- **Bank Type Profitability:** Private banks show a significantly higher average Net Interest Margin (NIM) compared to Public banks, indicating differing operational efficiencies or strategic focuses.
- **Credit Risk Assessment:** A strong inverse relationship exists between `credit_score` and `default_risk_score`, validating the importance of creditworthiness in predicting loan defaults.
- **Loan Demand & Demographics:** 'Education' and 'Working Capital' loans are highly prevalent, primarily disbursed to 'Salaried' individuals located in 'Urban' areas.
- **Macroeconomic Impact:** Central bank policies, specifically `repo_rate` and `crr`, exhibit strong correlations with `sector_loan_growth`, underscoring their direct influence on lending activity.
- **Interconnectedness:** Dependencies were found between `bank_name` and `bank_type`, `bank_name` and `employment_status`/`customer_location`, and `loan_type` and `business_size`, `employment_status` and `loan_purpose`, highlighting interconnected factors influencing loan distribution.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scipy.stats

---

## 📈 Use Cases

- **Credit Risk Management:** Enhancing models for default prediction and credit assessment.
- **Lending Strategy Optimization:** Informing product development and targeting based on loan type demand and customer demographics.
- **Financial Performance Analysis:** Benchmarking bank profitability (NIM) and identifying areas for operational improvement.
- **Monetary Policy Evaluation:** Understanding the real-world impact of central bank rates on loan growth.
- **Financial Inclusion Initiatives:** Identifying underrepresented customer segments and locations for targeted outreach.
- **Data Science Portfolio Project:** Demonstrating skills in data cleaning, EDA, and deriving business insights.

---

## 📎 Tags

`python` `data-analytics` `banking` `finance` `credit-risk` `financial-services` `eda` `loan-analysis` `fintech` `economic-analysis` `risk-management` `monetary-policy` `financial-inclusion` `data-visualization`

---

## 📬 Contact

Feel free to connect with me on Linkedin --> www.linkedin.com/in/adityaahir or reach out if you'd like to discuss the project, share feedback, or collaborate on similar work.
