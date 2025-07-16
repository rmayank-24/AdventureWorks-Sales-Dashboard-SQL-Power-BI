# 🧮 AdventureWorks Sales Dashboard (SQL + Power BI)

This project demonstrates a complete data analysis pipeline using **SQL** for data cleaning and transformation, and **Power BI** for interactive dashboard visualization. The goal is to uncover insights from sales data for a fictional bicycle company, **AdventureWorks**.

---

## 🎯 Objective

To analyze and visualize key metrics like sales by customer, product, and time using data from the AdventureWorks Data Warehouse. The final deliverables include:

- SQL script for data cleaning and exporting
- Cleaned data tables (CSV/XLSX)
- Interactive Power BI dashboard
- Exported PDF report

---

## 🗃️ Dataset Description

The project uses the **AdventureWorksDW2019** dataset. Key data tables extracted:

| File Name                                      | Description                              |
|------------------------------------------------|------------------------------------------|
| `portfolio_1-data_table-DimCustomer.csv`       | Customer dimension table                 |
| `portfolio_1-data_table-DimDate.csv`           | Date dimension table                     |
| `portfolio_1-data_table-DimProduct.csv`        | Product dimension table                  |
| `portfolio_1-data_table-FactInternetSales.csv` | Sales fact table                         |
| `portfolio_1-data_table-SalesBudget.xlsx`      | Excel-based sales target data            |

---

## 🛠️ Tools Used

- **SQL Server Management Studio (SSMS)** – Data querying & cleaning
- **Power BI Desktop** – Dashboard creation
- **Excel** – External budget integration

---

## 📈 Dashboard Pages

The final Power BI report has **3 main dashboard views**:

| Dashboard Page        | Description                          |
|------------------------|--------------------------------------|
| **Page 1: Overview**   | Sales trends, revenue KPIs, maps     |
| **Page 2: Customers**  | Customer segmentation and patterns   |
| **Page 3: Products**   | Product performance breakdown        |

---

## 🖼️ Visual Snapshots

| Sales Overview | Sales by Customer | Sales by Product | Data Model |
|----------------|-------------------|------------------|-------------|
| ![Overview](images/adventure_works_1.png) | ![Customer](images/adventure_works_2.png) | ![Product](images/adventure_works_3.png) | ![Model](images/data_model.png) |

---

## 📁 File Structure

```
├── images/
│   ├── adventure_works_1.png
│   ├── adventure_works_2.png
│   ├── adventure_works_3.png
│   └── data_model.png
├── LICENSE
├── README.md
├── portfolio_1-project-analysis.sql
├── portfolio_1-project-visualization_powerbi.pbix
├── portfolio_1-project-visualization_pdf.pdf
├── portfolio_1-data_table-DimCustomer.csv
├── portfolio_1-data_table-DimDate.csv
├── portfolio_1-data_table-DimProduct.csv
├── portfolio_1-data_table-FactInternetSales.csv
└── portfolio_1-data_table-SalesBudget.xlsx
```

---

## 🧼 Steps Followed

1. **Data Cleaning (SQL)**  
   Queried and filtered essential columns from the DW database into 4 clean CSV files + 1 Excel file.

2. **Model Design (Power BI)**  
   Linked tables via appropriate keys in the model view.

3. **Data Transformation (Power Query)**  
   Cleaned types, renamed fields, and prepared columns for visualization.

4. **Visualization (Power BI)**  
   Created 3-page dashboard with slicers, filters, KPIs, and custom visuals.

---

## 📌 Key Deliverables

✅ Power BI `.pbix` file  
✅ SQL script for reproducibility  
✅ Cleaned dataset in CSV/XLSX  
✅ Exported report as PDF  
✅ Dashboard screenshots

---

## 🔗 Dataset Source

[AdventureWorks DW 2019 (.bak)](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2019.bak)

---

## 🧑‍💼 Role Relevance

This project highlights the core skills of a **Data Analyst / BI Analyst**:
- SQL for ETL
- Power BI for dashboarding
- Data modeling and transformation
- Business storytelling using visual insights

---
