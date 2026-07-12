<div align="center">

 

<!-- Typing Animation -->

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=764ABA&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=Exploratory+Data+Analysis+%F0%9F%93%8A;Data+Visualization+with+Python+%F0%9F%90%8D;Turning+Raw+Data+into+Business+Insights+%F0%9F%92%A1" alt="Typing SVG Animation" />
</div>

<br/>

<!-- Badges -->
<img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge&logo=plotly&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C9A2A?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

<br/><br/>

<img src="https://img.shields.io/badge/Internship-CodeAlpha-blueviolet?style=flat-square"/>
<img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square"/>
<img src="https://img.shields.io/badge/Tasks-Task%202%20%26%20Task%203-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square"/>

</div>

<br/>

## 📌 About the Project

This repository contains **Task 2 (Exploratory Data Analysis)** and **Task 3 (Data Visualization)** completed as part of the **CodeAlpha Data Analytics Internship**. The project analyzes the popular **Superstore Sales dataset** to uncover trends in sales, profit, discounts, regions, and customer segments — turning raw retail data into clear, actionable business insights.

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="500">
</div>

---

## 🎯 Objective

> Analyze a retail sales dataset to identify trends, clean the data, perform exploratory analysis, and create meaningful visualizations for business decision-making.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐍 **Python** | Core programming language |
| 🐼 **Pandas** | Data cleaning & manipulation |
| 🔢 **NumPy** | Numerical operations |
| 📊 **Matplotlib** | Static visualizations |
| 🎨 **Seaborn** | Statistical & aesthetic plots |
| 📓 **Jupyter Notebook** | Interactive development environment |

---

## 📂 Dataset

Public **Superstore Sales dataset** containing order, product, customer, category, sales, profit, discount, and region information (9,995 records, 22 columns).

<details>
<summary>📋 Click to view dataset columns</summary>

<br/>

`Row ID` • `Order ID` • `Order Date` • `Ship Date` • `Ship Mode` • `Customer ID` • `Customer Name` • `Segment` • `Country` • `City` • `State` • `Postal Code` • `Region` • `Product ID` • `Category` • `Sub-Category` • `Product Name` • `Sales` • `Quantity` • `Discount` • `Profit`

</details>

---

## 🗂️ Repository Structure

```
📦 Superstore-Sales-Analysis
 ┣ 📂 Dataset
 ┃ ┣ 📜 Superstore.csv
 ┃ ┗ 📜 Clean_Superstore.csv
 ┣ 📓 Superstore_EDA.ipynb          # Task 2 - Exploratory Data Analysis
 ┣ 📓 Data_Visualization.ipynb      # Task 3 - Data Visualization
 ┣ 📄 CodeAlpha_Task2_Task3_Report.pdf
 ┗ 📄 README.md
```

---

## 🔍 Task 2 — Exploratory Data Analysis

<img align="right" width="220" src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385fbd1e02.gif">

Key steps performed in `Superstore_EDA.ipynb`:

- ✅ Imported dataset & checked shape, data types
- ✅ Handled missing values and duplicate records
- ✅ Converted `Order Date` and `Ship Date` to datetime format
- ✅ Generated descriptive statistics (`describe()`)
- ✅ Performed correlation analysis on numeric features
- ✅ Detected outliers in sales & profit
- ✅ Analyzed sales, profit, categories, regions & customer segments
- ✅ Exported a cleaned dataset → `Clean_Superstore.csv`

### 💡 Key Findings

| Insight | Detail |
|---|---|
| 🏆 Top Category | **Technology** generated the highest sales |
| 🌍 Regional Variance | Profit varied significantly across regions |
| 💸 Discount Impact | Higher discounts often **reduced** profit |
| 📅 Seasonality | Clear seasonal sales trends observed |
| 📦 Revenue Concentration | A small number of products drove a large share of revenue |

---

## 📊 Task 3 — Data Visualization

<img align="right" width="220" src="https://user-images.githubusercontent.com/74038190/212257460-738ff738-247f-4445-a718-cdd0ca76e2db.gif">

Visualizations created in `Data_Visualization.ipynb` using **Matplotlib** & **Seaborn**:

| Chart | Insight Revealed |
|---|---|
| 📊 Bar Chart – Sales by Category | Top-performing product categories |
| 📊 Bar Chart – Profit by Region | Most/least profitable regions |
| 📈 Line Chart – Monthly Sales Trend | Seasonal demand patterns |
| 🥧 Pie Chart – Sales Share by Category | Category-wise contribution |
| 📉 Histogram – Sales Distribution | Spread & skew of sales values |
| 📦 Box Plot – Profit Outliers | Extreme profit/loss values |
| ⚪ Scatter Plot – Sales vs Profit | Relationship between sales & profit |
| ⚪ Scatter Plot – Discount vs Profit | Effect of discounting on profit |
| 🔥 Correlation Heatmap | Relationships between numeric features |
| 🔢 Count Plot – Customer Segments | Distribution of customer segments |

---

## 💼 Business Insights

> Visualizations revealed top-performing categories, profitable regions, customer behavior, seasonal demand, and the relationship between discount and profit — enabling more informed, data-driven business decisions.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone  https://github.com/itz-roshan/CodeAlpha_Superstore_EDA.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch Jupyter Notebook
jupyter notebook

# 4. Open and run
Superstore_EDA.ipynb        # Task 2
Data_Visualization.ipynb    # Task 3
```

---

## ✅ Conclusion

This project demonstrates a complete **Data Analytics workflow** — from data cleaning and exploratory analysis to visualization and business insight generation.

## 🔮 Future Scope

- 📊 Build an interactive **Power BI / Tableau** dashboard
- 🤖 Develop **forecasting models** for future sales
- ⚙️ **Automate** reporting pipelines
- 🧠 Apply **Machine Learning** for deeper predictive insights

---

<div align="center">

## 🙌 Acknowledgement

This project was completed as part of the **CodeAlpha Data Analytics Internship Program**.

<img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20%26%20Python-red?style=for-the-badge"/>

### ⭐ If you found this project helpful, consider giving it a star!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:764ba2,100:667eea&height=120&section=footer" width="100%"/>

</div>
