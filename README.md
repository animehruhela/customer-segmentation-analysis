# 🛒 Customer Segmentation Analysis
### Data Analyst Project | Python + SQL | By Animesh Ruhela

---

## 📌 Project Overview

This project performs **Customer Segmentation** using Python and SQL to group customers based on their purchase behavior. The goal is to help businesses identify different customer types and create targeted marketing strategies.

---

## 🎯 Objective

- Analyze customer data using **SQL queries**
- Perform **Exploratory Data Analysis (EDA)** using Python
- Apply **K-Means Clustering** to segment customers into meaningful groups
- Generate **actionable business insights** for each segment

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **Python** | Data analysis & ML |
| **SQL (SQLite)** | Data querying & storage |
| **Pandas** | Data manipulation |
| **Scikit-learn** | K-Means Clustering |
| **Matplotlib & Seaborn** | Data Visualization |
| **Jupyter Notebook** | Development environment |

---

## 📁 Project Structure

```
customer_segmentation_project/
│
├── Customer_Segmentation_Analysis.ipynb   # Main notebook
├── customer_data.csv                       # Generated dataset (500 customers)
├── customer_segmentation.db               # SQLite database
├── requirements.txt                        # Dependencies
├── README.md                               # Project documentation
│
└── Output Images/
    ├── distribution_plots.png
    ├── correlation_heatmap.png
    ├── income_vs_spending.png
    ├── elbow_silhouette.png
    ├── customer_segments.png
    └── segment_pie_chart.png
```

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| Age | Customer age |
| Annual_Income_k | Annual income in thousands |
| Spending_Score | Spending score (1-100) |
| Total_Purchases | Total number of purchases |
| Avg_Order_Value | Average order value (₹) |
| Days_Since_Last_Purchase | Recency of purchase |
| Gender | Male / Female |

---

## 🤖 Customer Segments Identified

| Segment | Description | Business Strategy |
|---------|-------------|-------------------|
| 💎 Premium Customers | High income, high spending | Loyalty programs |
| 🛍️ Regular Shoppers | Medium income, medium spending | Upsell campaigns |
| 💤 Inactive Customers | Have income but not spending | Re-engagement offers |
| 🌱 New/Budget Customers | Low income, low spending | Budget offers |

---

## 📈 Key Results

- **500 customers** analyzed and segmented
- **4 distinct customer groups** identified using K-Means
- SQL queries used for demographic and behavioral analysis
- Visualizations created for all key metrics

---

## ▶️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/customer-segmentation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:
```bash
jupyter notebook Customer_Segmentation_Analysis.ipynb
```

4. Run all cells top to bottom ✅

---

## 📧 Contact

**Animesh Ruhela**  
📧 animeshruhela@gmail.com  
📱 7017835989

---

⭐ If you found this project useful, give it a star on GitHub!
