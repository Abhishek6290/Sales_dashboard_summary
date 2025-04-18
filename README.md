# Sales_dashboard_summary
---
# 📊 Sales Dashboard – Data Analyst Internship Task 8

## 📁 Dataset Used
We used the dataset: `cleaned_train_data.csv`  
It includes information such as:
- Order Date
- Region
- Category
- Sales
- Profit

---

## 🧠 Objective
To build a simple interactive dashboard in **Power BI** to visualize sales performance over time, by region, and by product category.

---

## 🛠 Tools Used
- 🔹 Power BI Desktop (for dashboard creation)
- 🔹 Microsoft Excel / Power BI Editor (for basic data cleanup)
- 🔹 GitHub (for version control and submission)

---

## 📊 Dashboard Features
---
### 1. **Line Chart – Sales Over Time**
- X-Axis: Month-Year (converted from Order Date)
- Y-Axis: Total Sales
- Shows seasonal trends and sales peaks
---
### 2. **Bar Chart – Sales by Region**
- X-Axis: Region
- Y-Axis: Total Sales
- Highlights top-performing geographic regions
---
### 3. **Donut Chart – Sales by Category**
- Slices: Product Categories
- Values: Total Sales
- Compares category-level contribution to revenue
---
### 4. **Slicer – Region**
- Interactive filter to explore data for each region
- Affects all visuals on the report


---
## 🧹 Data Preparation Steps

1. Imported `cleaned_train_data.csv` into Power BI
2. Converted **Order Date** to **Date** type
3. Created a new column for Month-Year:
   ```DAX
   MonthYear = FORMAT([Order Date], "MMM-YYYY")
    ```
---
  ## 📌 Key Insights
   
-📈 Sales peaked in Dec-2023, indicating a strong Q4 performance.
-🌍 West region had the highest sales across all months.
-🖥️ Technology category outperformed Furniture and Office Supplies.
-📉 South region showed decent sales but relatively lower profits.
---
## 🖼️ Files Included

| File Name | 	Description |
|----------|----------|
| cleaned_train_data.csv| 	Dataset used for dashboard | 
| SalesDashboard.pbix | Power BI project file | 
| Dashboard_Export.pdf| Exported view of the final dashboard | 
| README.md | 	Documentation of the task | 

---
## Author
👤 **Abhishek Verma**  

## Contact
📧 Email: [abhisehekverma6290@gmail.com]

## LinkedIn
🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/abhishek-verma-52603a313/)

