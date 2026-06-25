
# 🛒 Company Sales & Performance Analysis

A data analysis project built on a retail company scenario — analyzing sales, profit trends, and regional performance using Python.

---

## 📌 Business Scenario

As a **Data Analyst** at a retail company, management requested insights on:
- Sales performance across regions
- Profit trends by product category
- Top-performing orders
- Profit efficiency analysis

---

## 📦 Dataset

Synthetically generated using NumPy — 20 orders across 4 regions and 3 product categories.

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique order identifier (1–20) |
| `Region` | North, South, East, West |
| `Category` | Electronics, Clothing, Furniture |
| `Sales` | Order value (₹5,000 – ₹20,000) |
| `Profit` | Profit per order (₹500 – ₹5,000) |
| `Quantity` | Units sold (1–10) |
| `Profit_Ratio` | Derived metric — Profit / Sales |

---

## 🔍 Analysis Performed

- **Total Sales by Region** — `groupby()` to compare regional revenue
- **Total Profit by Category** — Category-wise profit breakdown
- **Top 5 Highest Sales Orders** — Sorted by Sales descending
- **Profit Ratio** — Feature engineered column (Profit / Sales)

---

## 📊 Visualizations (Plotly)

| Chart | Insight |
|-------|---------|
| Bar Chart | Sales by Region |
| Pie Chart | Profit Distribution by Category |
| Scatter Plot | Sales vs Profit (sized by Quantity) |
| Box Plot | Profit Ratio spread across Regions |

> ⚠️ Plotly charts are interactive in Jupyter Notebook — they won't render on GitHub preview. Run locally for full experience.

---

## 🛠️ Tech Stack

`Python` `NumPy` `Pandas` `Plotly Express` `Jupyter Notebook`

---

## 🚀 How to Run

```bash
pip install numpy pandas plotly
jupyter notebook Company_Project.ipynb
```

---

## 👨‍💻 Author

**Aarif Ansari** — Data Science & ML | Oxford Software Institute  
[GitHub](https://github.com/i-arif)
