# 🏦 Bank Customer Churn Analysis

Welcome to the **Bank Customer Churn Analysis** repository! 🚀  
This project demonstrates a complete analysis of bank customer churn using Python. It provides actionable business insights based on customer demographics, account activity, and financial behavior.

---

## 🎯 Objective
Understand customer churn patterns, identify key drivers of churn, and provide data-driven recommendations to improve customer retention.

---

## 📊 Dataset Description
The dataset contains 10,000 customer records with financial, demographic, and behavioral attributes.  

| Column Name        | Description                                                                                   |
|-------------------|-----------------------------------------------------------------------------------------------|
| RowNumber          | Index/serial number (can be ignored for analysis).                                            |
| CustomerId         | Unique identifier for each customer.                                                          |
| Surname            | Customer’s last name.                                                                         |
| CreditScore        | Customer’s credit score (300–850).                                                            |
| Geography          | Country/region (France, Germany, Spain).                                                      |
| Gender             | Customer’s gender (Male/Female).                                                             |
| Age                | Customer’s age in years.                                                                     |
| Tenure             | Number of years with the bank.                                                              |
| Balance            | Current account balance.                                                                     |
| NumOfProducts      | Number of bank products used.                                                               |
| HasCrCard          | Owns a credit card (1 = Yes, 0 = No).                                                       |
| IsActiveMember     | Active account holder (1 = Active, 0 = Not).                                               |
| EstimatedSalary    | Estimated annual salary.                                                                     |
| Exited             | Target variable: churned (1 = Yes, 0 = No).                                                |

---

## 🧮 Methodology
- **Data Preprocessing:** Cleaning, handling missing values, renaming columns, and categorization.
- **Exploratory Data Analysis (EDA):** Histograms, boxplots, pairplots, and heatmaps to understand distributions and relationships.
- **Statistical Analysis:** T-tests, correlation analysis, and age/churn relationship studies.
- **Insights Extraction:** Identifying high-risk and protective factors driving churn.
- **Business Recommendations:** Translating analysis into actionable strategies.

---

## 📈 Key Insights
| Feature                     | Observation                                                                                 |
|------------------------------|---------------------------------------------------------------------------------------------|
| Gender                       | Female customers churn more (25%) than male customers (16%).                                 |
| Geography                    | Germany shows highest churn (32%), followed by Spain (17%) and France (16%).                |
| Membership Activity          | Inactive members churn (27%) more than active members (14%).                                 |
| Age                          | Older customers are more likely to churn (median 45 vs 35 years).                           |
| NumOfProducts                | Single product holders churn more (28%) than multiple product holders (13%).                |
| CreditScore                  | Slightly lower among churned (~645 vs 652).                                                 |
| Balance                      | Higher among churned (~91,000 vs 73,000).                                                   |
| EstimatedSalary              | Minimal difference (~101k vs 99k).                                                          |

---

## 💡 Business Recommendations
- Target female and older customers with retention campaigns.  
- Re-engage inactive members with personalized offers.  
- Encourage adoption of multiple products to reduce churn.  
- Prioritize high-balance customers with loyalty programs.  
- Quickly resolve complaints to retain customers.  

---

## 🧰 Tech Stack
- Python 3.x  
- Jupyter Notebook  
- Libraries: pandas, numpy, matplotlib, seaborn, scipy, statsmodels  

---

## 📂 Project Structure
```plaintext
Bank-Customer-Churn-Analysis/
│
├── README.md                    # Project overview, insights, and instructions
├── requirements.txt             # Python dependencies
├── data/                        # Raw and processed datasets
│   ├──Customer Churn Records.csv                    # Original/raw datasets
│   │ 
│   └── processed/               # Cleaned and preprocessed datasets ready for analysis
│       └── cleaned_Customer Churn Records.csv
├── notebooks/                   # Stepwise analysis in Jupyter Notebooks
│   └── Bank Customer Churn Analysis.ipynb
├── visuals/                     # Generated plots and charts
```

# Clone the repository
git clone https://github.com/<Ravi-1729663>/Bank-Customer-Churn-Analysis.git

# Navigate to the project folder
cd Bank-Customer-Churn-Analysis

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook


---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **RAVI SANKAR REDDY BOVILLA **. I’m  passionate about data analyst and data engineering


