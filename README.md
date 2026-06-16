# 📊 Excel Data Analysis Project  
### *Data Technician Bootcamp*

This repository showcases the Excel-based data analysis work I completed during my **Level 3 Data Technician Bootcamp**.  
The project focuses on developing core analytical skills using real retail and sales datasets, applying formulas, PivotTables, data cleaning techniques, and visualisation tools.

---

## 🚀 Project Overview
Throughout this project, I worked with multiple datasets to practise:

- Cleaning and preparing data  
- Applying formulas for calculations and categorisation  
- Using PivotTables to summarise and explore trends  
- Creating charts to visualise insights  
- Building logic-based functions such as `SWITCH`  
- Filtering, sorting, and organising large datasets  

This project demonstrates my ability to work confidently with Excel as a data analysis tool.

---

## 🧠 Key Skills Demonstrated

### 🔢 Excel Formulas & Functions
Used across retail and sales datasets:

- `SUM` – total calculations  
- `SUMIF` – conditional totals  
- `AVERAGE` – mean calculations  
- `AVERAGEIF` – conditional averages  
- `DATE` / `MONTH` / `YEAR` – extracting and manipulating date values  
- `UNIQUE` – identifying distinct values  
- `VLOOKUP` – lookup and matching across tables  
- `SWITCH` – categorising data based on logic  
- Logical expressions using `TRUE`  

These functions were used to calculate commissions, categorise sales volumes, extract time-based insights, and automate repetitive tasks.

---

### 🔍 Data Cleaning & Preparation
- Sorting data (largest → smallest, alphabetical, chronological)  
- Filtering by category, month, generation, and more  
- Removing duplicates  
- Formatting columns for consistency  
- Creating new calculated fields  

---

### 📊 PivotTables & PivotCharts
Created PivotTables to summarise:

- Sales by county and product  
- Bike sales by age group, gender, and country  
- Retail spending by generation  
- Monthly and category-based trends  

PivotCharts were used to visualise:

- Spending habits  
- Product performance  
- Customer demographics  
- Market segmentation  

<img width="1914" height="932" alt="uk market " src="https://github.com/user-attachments/assets/1981bde8-ae1f-40ae-b06b-58c7076ffb81" />

---

### 🎨 Data Visualisation
- Bar charts  
- Category colour‑coding  
- Conditional formatting  
- Highlighting high/medium/low performance  
- Visual dashboards for quick insights  

<img width="1919" height="824" alt="Bar chart showing generation purchases " src="https://github.com/user-attachments/assets/a800b705-0999-4db3-b09f-c9a136532b5f" />

---

## 🧩 Example Task Highlights

### ✔ Retail Sales Dataset
- Filtered and sorted customer age  
- Calculated total and average commission  
- Created colour‑coded commission visuals  
- Built charts showing generational spending patterns  

---

### ✔ County Sales Dataset
Built a PivotTable summarising sales by county and product.

Added a categorisation column using the `SWITCH` function:
### Here is an example of the switch function being used
<img width="564" height="567" alt="switch funtion " src="https://github.com/user-attachments/assets/72c07456-a724-45dc-88a3-252530bf4857" />

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low");
