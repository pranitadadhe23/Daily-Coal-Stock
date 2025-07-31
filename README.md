# Daily-Coal-Stock
# 🧱 Daily Coal Stock EDA – India Power Sector

This project performs **End-to-End Exploratory Data Analysis (EDA)** on the **Daily Coal Stock Dataset** for Indian power stations. The analysis aims to identify consumption patterns, stock levels, transport modes, and state-wise trends that could impact power generation and supply chain decisions.

---

## 📂 Dataset Description

The dataset contains daily records of coal stock levels across various Indian power stations. It includes:

- **Date-wise entries**
- **State and utility names**
- **Power station capacities**
- **Coal stock (indigenous & imported)**
- **Daily requirement**
- **Mode of transport**
- **Plant Load Factor (%)**

📄 **Source**: [India Data Portal – Daily Coal Stock Report](https://indiadataportal.com)

---

## 📊 Project Objectives

- Clean and preprocess the dataset (missing values, duplicates, data types)
- Understand the **distribution** and **correlation** of numerical features
- Analyze **state-wise** and **sector-wise** coal stock behavior
- Visualize **time trends** of stock levels across dates
- Create new **features** for better insight and modeling

---

## 📌 Steps Performed

1. **Data Cleaning**
   - Removed columns with more than 30% missing values
   - Imputed or dropped rows with fewer missing values
   - Converted date to `datetime` format
   - Dropped duplicate records

2. **Exploratory Analysis**
   - Statistical summaries
   - Distribution plots (histograms, boxplots)
   - Correlation heatmap
   - Time-series trend of coal stock
   - State-wise and utility-wise analysis

3. **Feature Engineering**
   - Created `stock_per_mw` = Total stock / Installed capacity
   - Extracted `day_of_week` from date
   - Flagged plants with `high_consumption`

---

## 📁 Folder Structure

```bash
📦coal-stock-eda  
 ┣ 📄 daily-coal-stocks.csv.xlsx     # Raw dataset  
 ┣ 📄 cleaned_coal_stock.csv         # Final cleaned dataset  
 ┣ 📄 coal_stock_eda.ipynb           # EDA notebook with full code  
 ┣ 📄 README.md                      # Project overview and instructions  
```

---

## 📷 Sample Visuals

- Heatmap showing correlation between stock, capacity, and demand
- Bar chart comparing average stock levels by state
- Time-series plot of total coal stock over the months

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for visualization
- Jupyter Notebook

---

## 🚀 Future Scope

- Build a **forecasting model** to predict future stock levels
- Deploy interactive dashboards using **Streamlit** or **Gradio**
- Analyze **supply chain bottlenecks** and transport efficiency

---

## 🤝 Contributions

Contributions, suggestions, and feedback are welcome. If you found this useful, feel free to star 🌟 the repo!

---

## 📧 Contact

Created by **[Pranita Dadhe]**  
📍 India | ✉️ pranitadadhe23@gmail.com   
🔗 [LinkedIn](https://www.linkedin.com/in/pranita-dadhe-85447b254/) | [GitHub](https://github.com/pranitadadhe23)

