# Bank-Customer-Churn-Analysis
Customer churn is a critical business metric for banks. This project explores a bank's customer dataset to uncover the demographic, financial, and behavioral patterns that distinguish customers who leave from those who stay. The goal is to provide actionable insights that can help improve customer retention strategies.

## Data Set File Path
https://www.kaggle.com/datasets/anandshaw2001/customer-churn-dataset

## 🔍 Analysis Questions
All the questions are generated through ai for my performance improvement

### 📊 Customer Churn Overview
| # | Question |
|---|----------|
| Q1 | What is the overall churn rate? |
| Q2 | How many customers stayed vs. left? |

### 🌍 Demographic Analysis
| # | Question |
|---|----------|
| Q3 | Which country has the highest churn rate? |
| Q4 | Is churn higher among males or females? |
| Q5 | Which age group has the highest churn? |

### 💰 Financial Analysis
| # | Question |
|---|----------|
| Q6 | What is the average balance of churned vs. retained customers? |
| Q7 | Do customers with higher salaries churn more? |
| Q8 | Does credit score affect churn? |

### 🧩 Customer Segmentation
| # | Question |
|---|----------|
| Q9 | Do active members churn less? |
| Q10 | Which geography has the highest average balance among churned customers? |

---
## 📈 Key Findings

| Insight | Finding |
|---------|---------|
| **Overall Churn Rate** | ~20.37% — roughly 1 in 5 customers left |
| **Churned vs. Retained** | 2,037 churned · 7,963 retained |
| **Highest Churn by Country** | 🇩🇪 Germany (32.4%) — nearly double France (16.2%) and Spain (16.7%) |
| **Churn by Gender** | Females churn more (25.1%) than males (16.5%) |
| **Highest Churn Age Group** | Middle-aged customers (45–60) — 51.1% churn rate |
| **Balance vs. Churn** | Churned customers had higher average balances (₹91,108 vs ₹72,745) |
| **Salary vs. Churn** | Minimal effect — churn rate consistent across all salary brackets (~20%) |
| **Credit Score vs. Churn** | Lower credit scores correlate with slightly higher churn |
| **Active Members** | Active members churn significantly less (14.3% vs. 26.9%) |
| **Churned Balance by Country** | Germany churned customers had the highest avg balance (~₹1,20,361) |

---

## 🛠️ Tools & Libraries

```python
import pandas as pd
import numpy as np
```

- **Python 3.12**
- **Pandas** — data manipulation, groupby, binning (cut / qcut)
- **NumPy** — numerical operations
- **Jupyter Notebook** — interactive analysis

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yuvarajat2dev/bank-churn-analysis.git
   cd bank-churn-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy jupyter
   ```

3. **Add the dataset**  
   Place `Churn_Modelling.csv` in the project root directory.

4. **Launch the notebook**
   ```bash
   jupyter notebook Churn_project.ipynb
   ```

---

## 💡 Business Recommendations

Based on the analysis:

- **Target Germany** — highest churn market; investigate service gaps or competitive pressures
- **Engage female customers** — personalized retention programs for this segment
- **Focus on middle-aged customers (45–60)** — highest churn group; consider loyalty rewards
- **Re-engage inactive members** — activity level is one of the strongest churn predictors
- **Monitor high-balance inactive customers** — they represent the highest revenue loss risk

---

## 👤 Author

YUVARAJA T 
*Data Analysis Project — Personal Portfolio*
