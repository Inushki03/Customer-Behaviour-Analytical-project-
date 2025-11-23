# **Customer Behavior Analysis – End-to-End Data Analytics Project**

## 📌 **Project Overview**
This project focuses on analyzing retail customer behavior to identify key purchasing patterns, high-value customer segments, category performance, and overall sales trends.  
An interactive Power BI dashboard was built to visualize these insights clearly for business decision-making.

This is a full end-to-end project involving:

- **Python** (data cleaning, preprocessing, feature engineering)
- **PostgreSQL / SQL** (deep querying & analysis)
- **Power BI** (data modeling, visual dashboards)
- **Presentation & report preparation**

---

## 📊 **Dashboard Features**

### **KPIs**
- **2.8K+ Customers**
- **Average Purchase Amount:** $59.87  
- **Average Review Rating:** 3.75  

### **Visual Insights**
- Revenue by Category  
- Sales Count by Category  
- Customer Distribution by Subscription Status  
- Revenue by Age Groups  
- Dynamic slicers (Gender, Category, Subscription, Shipping Type)

---

## 🧹 **Data Preprocessing (Python)**

- Imported the dataset using **Pandas**
- Performed **EDA** to understand structure and missing values
- Filled null values using **category-wise medians**
- Standardized column names to **snake_case**
- Created new features:
  - `age_group` using *qcut*
  - `frequency_of_purchases`
- Removed redundant fields (dropped `promo_code_used`)
- Exported cleaned data to CSV for SQL analysis

---

## 🛢 **SQL Analysis**

Executed SQL queries to extract key business insights:

- Total revenue by gender  
- Customers spending above the average  
- Top 5 products by review rating  
- Comparison of Standard vs Express shipping  
- Revenue differences by subscription status  
- Customer segmentation (New, Returning, Loyal)

---

## 📈 **Business Recommendations**

- Focus on the **Young Adult** age group due to higher spending
- Promote the **Subscription Program** for increased recurring revenue
- Provide **exclusive loyalty rewards** to retain top customers
- Offer **targeted discounts** for the Clothing category
- Improve marketing strategies to acquire more **new customers**

---

## 🛠 **Tools & Technologies**

- **Python** (Pandas, NumPy)
- **PostgreSQL / SQL**
- **Power BI**
- **Google Colab**
- VS Code / DBeaver *(optional)*

---

## 🎯 **Project Deliverables**

- Cleaned dataset (CSV)
- SQL queries
- Power BI report (.pbix)
- Presentation slides
- Complete project documentation
