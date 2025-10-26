
#  Retail Insights Dashboard – TCS Data Science Project

##  Project Summary
Welcome to the **Retail Insights Notebook**, where raw transaction data transforms into actionable business intelligence. This project explores **customer behavior, sales trends, and revenue patterns** using Python, Pandas, Matplotlib, Seaborn, and Plotly.  

The goal is to uncover hidden insights that can **drive marketing, inventory, and payment strategies** for retailers.  

---

##  Dataset
The dataset represents **realistic retail transactions**, with the following key fields:

| Column | Description |
|--------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender (Male, Female, Other) |
| Age | Age of the customer |
| City | Customer city |
| ProductCategory | Purchased product category |
| Quantity | Number of units purchased |
| Price | Price per unit |
| PurchaseDate | Date of transaction |
| PaymentMode | Mode of payment (Cash, Card, Wallet, UPI) |
| TotalAmount | Total amount of purchase |

---

##  Workflow & Features

1. **Data Cleaning & Validation**
   - Handled negative, zero, and missing values.  
   - Ensured `TotalAmount` consistency: `Quantity × Price`.  

2. **Feature Engineering**
   - Extracted `Month` and `DayOfWeek` from `PurchaseDate`.  
   - Created **AgeGroup** categories: Teen, Young Adult, Adult, Senior, Elder.  
   - Derived insights-ready fields for visual analysis.  

3. **Encoding & Normalization**
   - Transformed categorical variables (`Gender`, `City`, `PaymentMode`, etc.) for modeling.  
   - Normalized numeric features (`Age`, `Price`, `TotalAmount`) for uniformity.  

4. **Visual Analytics**
   - **Total Sales by Category:** Quickly see the top-performing products.  
   - **Monthly Sales Trend:** Track revenue patterns across months.  
   - **Payment Mode Distribution:** Understand customer preferences.  
   - **Age-Group Spending:** Identify which customer segments spend more.  
   - **City Revenue Map & Heatmaps:** Geographical and cross-category insights.  

5. **Interactive Dashboards (Optional)**
   - Built with Plotly for real-time exploration of sales KPIs.  
   - Can be exported to **Power BI / Tableau** for executive dashboards.  

---

##  Key Insights
- Young Adults and Adults form the majority of high-value customers.  
- Certain cities dominate revenue contribution.  
- Credit/Digital payments are overtaking cash in transaction frequency.  
- Seasonal trends are visible in monthly sales spikes.  

---

