# 📘 Sales Performance & Order Insights Dashboard

## 🎯 Objective
This project aims to analyze sales trends, customer behavior, order performance, and operational efficiency using a 6,000-row synthetic sales dataset.
The dashboard provides:

- Overall sales & profit metrics
- Customer & product insights
- Order status analysis (Completed, Pending, Cancelled)
- Lost revenue & cancellation impact
- Data assessment & documentation

## 📊 Dataset
- **Source:** Custom-generated sales dataset  
- **Total Rows:** 6,000  
- **Columns:** 11  
- **Key Fields:**  
  - order_id  
  - date  
  - product  
  - category  
  - price  
  - quantity  
  - total_sales  
  - customer_name  
  - customer_location  
  - payment_method  
  - status  

## 📁 Folder Structure
```
Project/
│
├── BRD/                     # Business Requirement Document  
├── FRD/                     # Functional Requirement Document  
├── Data/                    # Raw & cleaned datasets  
│   ├── raw_data.csv  
│   └── cleaned_data.csv  
│
├── PowerBI/                 # PBIX files, DAX references  
│   ├── SalesDashboard.pbix  
│   └── Measures.txt  
│
├── Visuals/                 # Dashboard screenshots, mockups  
│   ├── Page1_Overview.png  
│   ├── Page2_Insights.png  
│   └── Page3_Status.png  
│
├── Reports/                 # PDF exports & analysis reports  
│   └── Dashboard_Report.pdf  
│
├── Scripts/                 # Python/SQL scripts for cleaning  
│   └── data_cleaning.ipynb  
│
└── README.md                # Documentation
```

## 🔄 Steps to Reproduce

### 1. Assess & clean dataset
- Analyze column quality  
- Handle duplicates  
- Standardize product, customer, location names  
- Validate total_sales = price × quantity  

### 2. Design dashboard mockups
- Page 1: Sales Overview  
- Page 2: Product & Customer Insights  
- Page 3: Order Performance & Status  

### 3. Build Power BI dashboard & data model
- Create Fact & Dimension tables  
- Build relationships  
- Create DAX measures (Sales, Profit, Lost Revenue, Status KPIs)  
- Apply theme & formatting  

### 4. Export reports & prepare Analysis Report
- Export PDF  
- Document insights & recommendations  
- Save PBIX file  
