# 📊 ApexPlanet Internship - Data Analysis Project

## 🔍 Project Overview
This project is part of the ApexPlanet Internship and focuses on **data wrangling, exploratory data analysis (EDA) and deep-dive analysis & interactive dashboarding** using Python and Power BI.
The goal is to clean raw data, extract meaningful insights, and build a professional dashboard.

---

## 📁 Dataset
- **Name:** E-Commerce Sales Dataset
- Contains information about:
  - Revenue
  - Profit
  - Category
  - Region
  - Customer segments
  - Payment methods
  - Order status
  - Acquisition channels

---

## 🔧 Task 1: Data Wrangling (Python)
- Loaded and explored the dataset
- Handled missing values
- Removed duplicate records
- Standardized column names
- Feature engineering:
  - `profit_category`
  - `sales_category`
  - `sales_per_order`
- Cleaned column names
- Exported cleaned dataset

---

## 📊 Task 2: Exploratory Data Analysis (Python + Power BI)
✅ Visualizations Created:
- Sales by Category
- Sales by Region
- Revenue vs Loss distribution
- Sales by Customer Segment
- Key Performance Indicators (Total Sales, Profit, Orders)

---

## 🔬 Task 3: Deep-Dive Analysis & Interactive Dashboarding (Python + Power BI)
✅ Core KPIs: AOV Rs.19,482 | Cancellation 10.1% | Return Rate 8.4% | Rating 3.74/5 | Delivery 5.5 days

✅ Analyses: Cohort Retention · Customer Segmentation · Acquisition Channel Analysis

✅ Built 3-page interactive Power BI dashboard with slicers (Year, Category, Age Group)

---

## 📖 Task 4: Data Storytelling & Statistical Validation (Python)
✅ Structured findings into a 5-chapter business narrative (PowerPoint)

✅ Hypothesis Tests Performed:
| Hypothesis | Test | P-Value | Result |
|---|---|---|---|
| Mobile App AOV > Website AOV | T-Test | 0.0828 | Not Significant |
| 36-45 AOV > 18-25 AOV | T-Test | 0.2317 | Not Significant |
| Cancellation rate differs by channel | Chi-Squared | 0.7467 | Not Significant |
| October AOV > Other months | T-Test | 0.0075 | ✅ Significant |

✅ **Key Finding:** October revenue spike is statistically proven (p=0.0075) — festive season effect is real.

---

## 🗂️ Data Dictionary
| Column | Description |
|---|---|
| customer_id | Unique customer ID |
| city | City |
| state | State |
| postal_code | Postal code |
| region | Region |
| category | Product category |
| sub_category | Product sub-type |
| sales | Revenue |
| quantity | Quantity sold |
| discount | Discount applied |
| profit | Profit earned |
| profit_category | Profit or Loss classification |
| sales_category | High or Low sales |
| sales_per_order | Sales per order |
| order_status | Delivered / Cancelled / Returned |
| age_group | Customer age group |
| acquisition_channel | How customer was acquired |
| customer_rating | Satisfaction score (1–5) |
| days_to_delivery | Days taken for delivery |

---

## 🛠️ Tools Used
- Python (Pandas, Matplotlib, Seaborn, SciPy)
- VS Code
- Power BI
- SQL (SQLite)

---

## 🖥️ Dashboard Preview

### Task 2 Dashboard
<img width="1152" height="720" alt="image" src="https://github.com/user-attachments/assets/b8620979-e3d0-42b6-85eb-b57ba3ae6eb0" />

### Task 3 Dashboard
<img width="1124" height="635" alt="Dashboard png" src="https://github.com/user-attachments/assets/2e974579-c6d2-4c95-ae30-380576e17165" /> 

---

## 🚀 Key Insights
- Electronics category generates highest revenue
- Some orders result in losses despite high sales
- Regional performance varies significantly
- Mobile App is the top acquisition channel
- 36–45 age group has the highest Average Order Value
- October shows consistent revenue spike every year (festive season)
- Month-1 customer retention is only ~6%

---

## 🔗 Conclusion
This project demonstrates how raw data can be transformed into meaningful insights using data cleaning, feature engineering, visualization techniques, and statistical validation.

---

## 👩‍💻 Author
Devi Sri
ApexPlanet Data Analytics Internship
