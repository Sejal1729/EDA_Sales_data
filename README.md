
# 📊 Sales Data Analysis Project

This project focuses on analyzing a sales dataset using Python. The goal is to extract useful business insights through data cleaning, transformation, visualization, and statistical analysis. This type of analysis helps businesses understand customer behavior, product performance, and how to improve sales and profits.

---

## 📁 Dataset Information

- **File Name**: `salesforcourse-4fe2kehu.csv`
- **Columns Include**:
  - Date
  - Customer Age
  - Customer Gender
  - Country, State
  - Product Category, Sub Category
  - Quantity, Unit Cost, Unit Price
  - Revenue, Cost

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Statistical analysis
- **Matplotlib** – Basic plotting
- **Seaborn** – Advanced visualization

---

## 🔍 Project Steps

1. **Data Cleaning**
   - Removed unnecessary columns (`index`, `Column1`)
   - Handled missing values
   - Removed duplicates
   - Converted `Date` to proper datetime format

2. **Data Transformation**
   - Created `Profit` and `Profit Margin` columns
   - Extracted `Month` and `Age Group` for deeper insights

3. **Exploratory Data Analysis (EDA)**
   - Checked revenue, cost, and profit distributions
   - Correlation matrix to identify relationships
   - Grouped data by product, gender, state, and month

4. **Visualizations**
   - Revenue by Month (Bar Chart)
   - Customer Age Distribution (Histogram)
   - Profit by Gender (Boxplot)
   - Correlation Heatmap

---

## 📈 Key Insights

- **Best Month for Sales**: Found using total revenue by month
- **Top Age Group**: Customers aged 26–35 made the most purchases
- **High-Profit Categories**: Accessories and Clothing had highest margins
- **Customer Gender Split**: Slightly more purchases by male customers
- **Regional Sales**: Some states significantly outperformed others

---

## 💡 Business Solutions

| Problem                             | Insight                               | Suggested Solution                     |
|-------------------------------------|----------------------------------------|----------------------------------------|
| Low sales in some months            | Seasonal trends in data                | Launch promotions during peak months   |
| Underperforming product categories  | Low revenue or profit                  | Bundle or replace low-performing items |
| Undefined target audience           | Age group 26–35 has higher revenue     | Focus ads on this age group            |
| Profit margin variation             | Some products are low-margin           | Push high-margin products more         |
| Inventory planning                  | Sub-category analysis                  | Stock top-selling items first          |

---



