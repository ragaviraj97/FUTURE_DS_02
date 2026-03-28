
# FUTURE_DS_02
#  Customer Churn & Retention Analysis

##  Project Overview
This project analyzes customer churn behavior using a telecom dataset to identify key drivers of churn and recommend strategies to improve customer retention.

The analysis focuses on:
- Understanding why customers leave
- Identifying high-risk customer segments
- Analyzing customer lifecycle and retention trends

---

##  Dataset Description

### Columns & Attributes

| Column Name | Description |
|------------|------------|
| customerID | Unique ID for each customer |
| gender | Customer gender (Male/Female) |
| SeniorCitizen | Whether the customer is a senior citizen (0/1) |
| Partner | Whether the customer has a partner (Yes/No) |
| Dependents | Whether the customer has dependents (Yes/No) |
| tenure | Number of months the customer has stayed |
| PhoneService | Whether the customer has phone service |
| MultipleLines | Multiple lines subscription |
| InternetService | Type of internet service (DSL/Fiber/No) |
| OnlineSecurity | Whether customer has security service |
| OnlineBackup | Backup service subscription |
| DeviceProtection | Device protection service |
| TechSupport | Technical support service |
| StreamingTV | Streaming TV service |
| StreamingMovies | Streaming movies service |
| Contract | Contract type (Month-to-month, One year, Two year) |
| PaperlessBilling | Whether billing is paperless |
| PaymentMethod | Payment method used |
| MonthlyCharges | Monthly billing amount |
| TotalCharges | Total amount charged |
| Churn | Whether customer churned (Yes/No) |

---

## Tools Used
- Microsoft Excel (Data Cleaning)
- Power BI (Dashboard & Visualization)
- DAX (Measures & Calculations)

---

##  Key Analysis Performed

###  Churn Analysis
- Calculated churn rate and identified churn patterns
- Analyzed churn across:
  - Contract types
  - Tenure groups
  - Payment methods

---

### Customer Lifecycle Analysis
- Created tenure-based cohorts
- Identified that early-stage customers have higher churn
- Long-term customers show strong retention

---

###  Key Influencers Analysis
Used Power BI Key Influencers visual to identify major churn drivers.

####  Factors Increasing Churn:
- Month-to-month contract
- Low tenure (new customers)
- No Tech Support
- No Online Security
- Electronic check payment method

#### Factors Reducing Churn:
- Long-term contracts (1–2 years)
- Higher tenure
- Availability of support services

---

### Customer Risk Analysis
Developed a risk scoring model based on:
- Tenure
- Contract type
- Service usage

#### High-Risk Customers:
- Low tenure (0–6 months)
- Month-to-month contracts
- No TechSupport

---

##  Key Insights

- Customers with **month-to-month contracts** have the highest churn
- **New customers (0–6 months)** are most likely to leave
- Customers without **TechSupport and OnlineSecurity** show higher churn
- Long-term customers (2+ years) demonstrate strong loyalty
- A small segment of high-risk customers contributes significantly to churn

---

## Business Recommendations

- Improve onboarding experience (first 3–6 months)
- Encourage long-term contracts through incentives
- Promote bundled services (TechSupport, Security)
- Target high-risk customers with personalized retention strategies

---

##  Dashboard Features

- KPI Cards (Churn Rate, Total Customers, Revenue)
- Churn by Contract
- Churn by Tenure
- Service-Based Analysis
- Customer Risk Segmentation
- Key Influencers Visual

---

##Conclusion

Customer churn is primarily driven by short tenure and flexible contract types. By focusing on early engagement and promoting long-term commitments, businesses can significantly improve retention and reduce revenue loss.

---

## 🚀 Author
**Ragavi R**  
Aspiring Data Analyst | Power BI | SQL | Python

Linked in:https://www.linkedin.com/in/ragavi-r-594500351/ 

Mail me:ragavikrish1997@gmail.com
