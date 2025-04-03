> Analyze e-commerce sales data from 2019 to discover insights, identify business opportunities, and predict future sales.
# 🛍️ Sales Reporting 2019

A full data analysis project using real-world sales data from 2019 (USA-based e-commerce), with end-to-end process including:

- 📊 Data cleaning & wrangling
- 📈 Exploratory Data Analysis (EDA)
- 📉 Statistical Modeling (OLS Regression)
- 🤖 Machine Learning Regression (Random Forest)

---

## 📁 Project Structure
```
sales-reporting/
├── data/
│   └── raw/                    # 12 CSV files by month (sales2019_1.csv ... sales2019_12.csv)
│   └── processed/              # annualSales2019_finished.csv & cleaned version
├── notebooks/
│   └── sales_analysis.ipynb    # Jupyter Notebook – full analysis
├── src/                        # (Optional) Python scripts for modular reuse
├── README.md                   # Project overview
├── requirements.txt            # Python dependencies
```

---

## 🔍 Key Business Questions

- When are the best months and hours to focus marketing?
- Which cities and products generate the most revenue?
- What factors influence total sales per order?
- Can we build a model to predict order revenue?

---

## 🧪 Tools Used
- **Python**: pandas, matplotlib, seaborn, scikit-learn, statsmodels
- **Jupyter Notebook** for code documentation
- **Random Forest** for ML regression
- **OLS Regression** for statistics/insights

---

## 📈 Results Summary
## 📈 Highlights from Analysis
- 🗓️ **December** is the highest revenue month (~4.6M USD)
- 🕒 Sales peak at **11 AM and 7 PM**, aligning with lunch breaks and after work hours
- 🌆 **San Francisco** and **Los Angeles** generate the most revenue
- 📦 Top-selling products are affordable and essential (batteries, cables, headphones)
- 🔎 **Quantity Ordered** is the most impactful variable on revenue
- 🤖 ML model (Random Forest) achieves **R² = 1.000**, indicating strong predictive power


---

## 🚀 How to Run
1. Clone the repo
2. Place raw `.csv` files into `data/raw/`
3. Open `sales_analysis.ipynb`
4. Run all cells

---

## 📬 Contact
Author: *Vy Thuy Do*  
Email: *contact.vyda@gmail.com*  
GitHub: [@yourhandle](https://github.com/yourhandle)

---

> Made with 💻 & ☕ by a data analyst who loves clean visuals and real business impact.
