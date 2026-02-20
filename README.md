# 📊 Purchase Pattern Analysis (Market Basket Analysis)

## 📌 Project Overview
This project analyzes customer purchase behavior using retail transaction data to identify frequently purchased product combinations. The goal is to uncover hidden patterns that support cross-selling, product bundling, inventory optimization, and data-driven business decision-making.

The project was executed as a **Client Project** and follows a structured analytics approach including data cleaning, exploratory data analysis (EDA), and Market Basket Analysis using the Apriori algorithm.

---

## 🎯 Business Objective
- Understand customer purchasing patterns
- Identify products frequently bought together
- Improve cross-selling and bundling strategies
- Support inventory and merchandising decisions
- Increase average order value (AOV)

---

## 🗂️ Dataset Description
- Transactional retail dataset (~5 lakh records)
- Time Period: 2010–2011
- Key Features:
  - BillNo
  - ItemName
  - Quantity
  - Price
  - CustomerID
  - Country
  - InvoiceDate

> ⚠️ Note:  
> The dataset size is approximately **39 MB**. Due to GitHub file size limitations, the full dataset is **not uploaded** to this repository.

---

## 🧹 Data Cleaning & Preprocessing
- Removed cancelled invoices (Invoice numbers starting with 'C')
- Removed transactions with negative quantities (returns)
- Dropped records with missing product names
- Filtered Top 500 most frequently purchased products
- Removed single-item transactions to reduce noise
- Created Transaction–Product Matrix
- Converted quantity data into a Binary Basket Matrix (1/0)

---

## 📊 Exploratory Data Analysis (EDA)
The following analyses were performed with visualizations:

- Monthly Revenue Trend
- Top 10 Products by Quantity
- Top 10 Products by Revenue
- Country-wise Sales Distribution
- Quantity Distribution
- Quantity vs Price Relationship

### Key EDA Insights:
- Sales are highly concentrated in the UK market
- Most customers purchase products in small quantities
- A small number of products contribute significantly to total revenue
- November shows peak sales due to seasonal demand
- Inverse relationship observed between product price and purchase quantity

---

## 🔗 Market Basket Analysis
### Algorithm Used:
- **Apriori Algorithm**

### Parameters:
- Minimum Support: 0.004
- Confidence ≥ 0.6
- Lift ≥ 1.9
- Top 500 products considered

### Results:
- 28 strong association rules identified
- High-lift product combinations indicate strong cross-selling opportunities
- Themed and complementary products show frequent co-purchase behavior

---

## 💡 Business Recommendations
- Bundle high-lift product combinations
- Optimize store layout based on association patterns
- Introduce combo discounts and promotions
- Implement cross-selling recommendations in online platforms
- Reduce dependency on a single geographic market

---

## 📈 Expected Business Impact
- Increased Average Order Value (AOV)
- Improved cross-selling performance
- Better inventory planning
- Enhanced customer shopping experience
- Data-driven merchandising strategy

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib / Seaborn
- mlxtend (Apriori Algorithm)
- Jupyter Notebook
- PowerPoint (Stakeholder Presentation)

---

## 🔗 Dataset Access
The full dataset can be accessed via:
- External storage / Google Drive (shared upon request)
- Original data source (if applicable)

---

## ✅ Conclusion
This project demonstrates how transaction-level data can be transformed into actionable business insights using Market Basket Analysis. By combining EDA and association rule mining, the analysis supports strategic decisions related to sales growth, inventory optimization, and customer experience improvement.

---

## 👤 Author
**Ankit Raj Sinha**  
Data Analyst  
Tools: Python | SQL | Excel | Power BI | Tableau
