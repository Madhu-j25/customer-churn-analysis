# 📉 Customer Churn Analysis — Telecom Industry

> **Can we predict which customers are about to leave — before they do?**  
> This project dives into telecom customer behavior to uncover the key drivers of churn and deliver actionable business recommendations.

---

## 🧩 Problem Statement

Customer churn is one of the most costly problems in the telecom industry. Acquiring a new customer costs **5x more** than retaining an existing one. This project analyzes the Telco Customer Churn dataset to identify **who is churning, why they are churning, and what the business can do about it.**

---

## 📊 Dashboard Overview

Built entirely in **Power BI**, the dashboard provides an interactive view of churn patterns across customer segments, contract types, internet services, and payment methods.

![Dashboard Preview](dashboard-preview.png)

---

## 🔑 Key Findings

| Insight | Detail |
|---|---|
| **Overall Churn Rate** | 26.54% of 7,043 customers churned |
| **Highest Risk Group** | Month-to-month contract customers — churn rate ~42% |
| **Internet Service Risk** | Fiber optic users churn significantly more than DSL users |
| **Payment Method** | Electronic check users show the highest churn rate |
| **Tenure Impact** | Customers in their first 12 months are the most likely to leave |
| **Low Risk Group** | Two-year contract customers have a churn rate below 5% |

---

## 💡 Business Recommendations

1. **Incentivize long-term contracts** — Offer discounts or free months to convert month-to-month users to annual or two-year plans. This alone could reduce churn by up to 30%.

2. **Target new customers early** — Introduce an onboarding program for customers in their first 6 months, as this is the highest churn window.

3. **Investigate fiber optic service quality** — High churn among fiber optic users suggests a potential service quality or pricing issue that needs attention.

4. **Promote auto-pay adoption** — Electronic check users churn more. Nudging users toward credit card or bank transfer auto-pay could improve retention.

---

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard design and interactive visualizations
- **DAX** — Custom measures and calculated columns
- **Power Query** — Data cleaning and transformation
- **Dataset** — [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 📁 Project Structure

```
customer-churn-analysis/
│
├── CustomerChurn.pbix        # Power BI dashboard file
├── dashboard-preview.png     # Dashboard screenshot
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Raw dataset
└── README.md                 # Project documentation
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop** (free to download)
3. Use the slicers on the right to filter by region, contract type, internet service, and more
4. Explore the insights across different customer segments

---

## 🔮 Future Improvements

- Add a **Machine Learning churn prediction model** (Logistic Regression or Random Forest) to score each customer's churn probability
- Incorporate **customer support ticket data** to see if complaint frequency predicts churn
- Build a **Revenue Impact page** — quantifying how much revenue is lost per churned customer segment

---

## 👤 Author

**Madhu** — MCA Student | Aspiring Data Analyst  
📧 [Your Email] | 💼 [Your LinkedIn] | 🐙 [GitHub Profile](https://github.com/Madhu-j25)
