<h1 align="center">
  <img src="visuals/logo.jpg" alt="Logo" width="40" style="vertical-align:middle; margin-right:10px;"/>
  Amazon Sales Analysis Report
</h1>

## 🔹 Project Title  
Amazon Sales Report Analysis  

## 🔹 Brief One Line Summary  
Comprehensive analysis of Amazon sales data with data cleaning, exploratory data analysis (EDA), and visualization using Jupyter Notebook and Power BI.  

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

## 🔹 Overview  
This project focuses on analyzing Amazon sales data to identify sales trends, category performance, delivery insights, and customer behavior. The project includes dataset cleaning, EDA in Python, and a Power BI interactive dashboard for visualization.  

---

## 🔹 Business Problem  
Amazon sellers need actionable insights into their sales data to improve product performance, optimize sales channels, reduce returns, and maximize revenue.  

---

## 🔹 Dataset  
- **Raw Data:** `Amazon_Sale_Report.csv`  
- **Processed Data (after cleaning & EDA):** `Final_Sale_Report.csv`  

The dataset includes order details, category, size, status, fulfillment type, and sales channel.  

---

## 🔹 Tools and Technologies  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** → Data Cleaning & EDA  
- **Jupyter Notebook** → Analysis and visualization  
- **Power BI** → Dashboard and reporting  
- **GitHub** → Version control and project documentation  

---

## 🔹 Project Structure  

```
Amazon-Sales-Report/
│
├── 📊 Amazon_Sale_Report.csv        # Raw dataset (original sales data)
├── 📊 Final_Sale_Report.csv         # Processed dataset after cleaning & EDA
├── 📒 Sales.ipynb                   # Jupyter Notebook (data cleaning, EDA, insights)
├── 📊 Amazon Dashbaord.pbix         # Power BI dashboard file
├── 🌍 india_states.geojson          # GeoJSON file for India state-level map visualization
├── 📄 .gitignore                    # Git ignore file to keep repo clean
└── 📄 README.md                     # Project documentation
```

---

## 🔹 Data Cleaning & Preparation  
- Removed null values and duplicates  
- Standardized date formats  
- Cleaned category and size columns  
- Processed dataset saved as `Final_Sale_Report.csv`  

---

## 🔹 Exploratory Data Analysis (EDA)  
Key steps performed in `Sales.ipynb`:  
- Sales trends over time  
- Orders by status (Delivered, Cancelled, Returned, Pending)  
- Sales by category and size  
- Sales performance across channels  
- Geographic insights using India states map  

👉 Full Notebook Preview on **nbviewer**: [Click Here](https://nbviewer.org/github/Ayu0209/Amazon-Sales-Report/blob/main/Sales.ipynb)  

---

## 🔹 Research Questions & Key Findings  
- Which sales channel contributes the most revenue?  
- What are the best and worst-performing categories?  
- How do delivery statuses impact overall revenue?  
- Which states contribute the most to total sales?  

---

## 🔹 Dashboard/Model/Output  
- **Power BI Dashboard** (`Amazon Dashbaord.pbix`)  
- Includes KPIs, category insights, sales trends, and map visualization.  
- Example snapshot:  

![Dashboard Preview](dashboard_image.png)  

---

## 🔹 How to Run this Project?  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Ayu0209/Amazon-Sales-Report.git
   cd Amazon-Sales-Report
   ```
2. Open `Sales.ipynb` in Jupyter Notebook to explore EDA.  
3. Open `Amazon Dashbaord.pbix` in Power BI Desktop to view dashboard.  

---

## 🔹 Results & Conclusion  
- Electronics and Apparel categories dominate sales.  
- Amazon contributes the highest sales among channels.  
- Majority of orders are successfully delivered, with minimal returns.  
- Seasonal trends impact demand significantly.  

---

## 🔹 Future Work  
- Predictive modeling for future sales.  
- Customer segmentation for targeted strategies.  
- Automated dashboard updates using live data sources.  

---

## 🔹 Author & Contact  
👩‍💻 **Ayushi Kedia**  
📧 [ayushi.kedia@example.com](mailto:ayushi.kedia@example.com)  
🔗 [GitHub Profile](https://github.com/Ayu0209)  
