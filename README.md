<h1 align="center">
  <img src="visuals/logo.jpg" alt="Logo" width="30" style="vertical-align:middle; margin-right:10px;"/>
  Amazon Sales Analysis Report
</h1>

_Comprehensive analysis of Amazon sales data with data cleaning, exploratory data analysis (EDA), and visualization using Jupyter Notebook and Power BI._  

---

## 📑 Table of Contents  
1. [Overview](#overview)  
2. [Business Problem](#business-problem)  
3. [Dataset](#dataset)  
4. [Tools and Technologies](#tools-and-technologies)  
5. [Project Structure](#project-structure)  
6. [Data Cleaning & Preparation](#data-cleaning--preparation)  
7. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
8. [Research Questions & Key Findings](#research-questions--key-findings)  
9. [Dashboard/Model/Output](#dashboardmodeloutput)  
10. [How to Run this Project?](#how-to-run-this-project)  
11. [Results & Conclusion](#results--conclusion)  
12. [Future Work](#future-work)  
13. [Author & Contact](#author--contact)  

---

## Overview  
This project focuses on analyzing Amazon sales data to identify sales trends, category performance, delivery insights, and customer behavior. The project includes dataset cleaning, EDA in Python, and a Power BI interactive dashboard for visualization.  

---

## Business Problem  
Amazon handles millions of transactions daily across multiple categories, regions, and sales channels. For sellers and decision-makers, it becomes challenging to identify:
- Which categories and products drive the most revenue?
- How regional performance varies across states.
- Which fulfilment (Amazon, Merchant, etc.) contribute more to growth.
- The impact of order status (delivered, returned, cancelled) on overall profitability.
  
Without clear insights, businesses struggle with inefficient inventory planning, missed growth opportunities, and poor customer experience.
This project analyzes Amazon sales data to uncover key trends, vendor performance, customer demand patterns, and revenue drivers, enabling data-backed strategic decisions. 

---

## Dataset  
- **Raw Data:** `Amazon_Sale_Report.csv`  
- **Processed Data (after cleaning & EDA):** `Final_Sale_Report.csv`  

The dataset includes order details, category, size, status, fulfillment type, and sales channel.  

---

## Tools and Technologies  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** → Data Cleaning & EDA  
- **Jupyter Notebook** → Analysis and visualization  
- **Power BI** → Dashboard and reporting  
- **GitHub** → Version control and project documentation  

---

## Project Structure  

```
Amazon-Sales-Report/
│
│── 📂 data/                         # Raw & processed datasets
│   │── Amazon_Sale_Report.csv       # Original dataset(s)
│   │── Final_Sale_Report.csv        # Cleaned / transformed datasets
│
│── 📂 notebook/                 # Jupyter notebooks for EDA & analysis
│   │── Sales.ipynb
│
│── 📂 dashboard/                 # Power BI dashboard
│   │── amazon_sales.pbix
│
│── 📂 visuals/                   # Exported plots, charts, and screenshots
│   │── 1_sales_analysis.jpg
│   │── 2_regional_analysis.jpg
│   │── 3_product_insights.jpg
│   │── amazonindia.png
│   │── logo.jpg
│
│── 📄 india_states.geojson        # Geo data for regional analysis
│── 📄 README.md                 # Project overview, business problem, insights,etc
│── 📄 .gitignore                 # Ignore unnecessary files

```

---

## Data Cleaning & Preparation  
- Removed null values and duplicates  
- Standardized date formats  
- Cleaned category and size columns  
- Processed dataset saved as _`Final_Sale_Report.csv`_  

---

## Exploratory Data Analysis (EDA)  
Key steps performed in `Sales.ipynb`:  
- Sales trends over time  
- Orders by status (Delivered, Cancelled, Returned, Pending)  
- Sales by category and size  
- Sales performance across channels  
- Geographic insights using India states map  

👉 Full Notebook Preview on **nbviewer**: [Click Here](https://nbviewer.org/github/Ayu0209/Amazon-Sales-Report/blob/main/notebook/Sales.ipynb)   

---

## Research Questions & Key Findings  
- Which sales channel contributes the most revenue?  
- What are the best and worst-performing categories?  
- How do delivery statuses impact overall revenue?  
- Which states contribute the most to total sales?  

---

## Dashboard/Model/Output  
- **Power BI Dashboard** (`amazon_sales.pbix`)  
- Includes KPIs, category insights, sales trends, and map visualization.  
- Example snapshot:  

![Page-1: Sales Analysis Dashboard Preview](https://github.com/Ayu0209/Amazon-Sales-Report/blob/main/visuals/1.Sales%20Anaysis.jpg)  
![Page-2: Regional Analysis Dashboard Preview](https://github.com/Ayu0209/Amazon-Sales-Report/blob/main/visuals/2.Regional%20Analysis.jpg)  
![Page-1: Product & Fulfilment Insights Dashboard Preview](https://github.com/Ayu0209/Amazon-Sales-Report/blob/main/visuals/3.Product%20%26%20Fulfilment%20Insights.jpg)  

---

## How to Run this Project?  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Ayu0209/Amazon-Sales-Report.git
   cd Amazon-Sales-Report
   ```
2. Open `Sales.ipynb` in Jupyter Notebook to explore EDA.  
3. Open `Amazon Dashbaord.pbix` in Power BI Desktop to view dashboard.  

---

## Results & Conclusion  
- Electronics and Apparel categories dominate sales.  
- Amazon contributes the highest sales among fulfilment.  
- Majority of orders are successfully delivered, with minimal returns.  
- Seasonal trends impact demand significantly.  

---

## Future Work  
- Predictive modeling for future sales.  
- Customer segmentation for targeted strategies.  
- Automated dashboard updates using live data sources.  

---

## Author & Contact  
👩‍💻 **Ayushi Kedia**    
📧 Email: ayushikediahm@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-kedia-81bb7520b/)  
