# 🛍️ Retail Promotion Analysis

A complete Retail Promotion Analytics project that evaluates the effectiveness of promotional campaigns using Python. This project includes exploratory data analysis (EDA), business insights, and visualizations to answer client business questions.

---

## 📌 Project Overview

Promotional campaigns are widely used to increase sales and revenue in the retail industry. This project analyzes promotional campaign data to measure their impact on product sales, revenue, and customer purchasing behavior.

The analysis addresses seven client business requests using data visualization and business metrics such as **Incremental Revenue (IR%)** and **Incremental Sold Units (ISU%)**.

---

## 📂 Repository Structure

```text
RetailPromotionAnalysis/
│
├── datasets/
│   ├── dim_campaigns.csv
│   ├── dim_products.csv
│   ├── dim_stores.csv
│   └── fact_events.csv
│
├── resources/
│   ├── dim_campaigns.jpg
│   ├── dim_products.jpg
│   ├── dim_stores.jpg
│   ├── fact_events.jpg
│   ├── Q1_Stores_by_City.png
│   ├── Q2_Sankranti_Category_Contribution.png
│   ├── Q3_Correlation_Heatmap.png
│   ├── Q4_Grocery_&_Staples.png
│   ├── Q4_Home_Care.png
│   ├── Q4_Combo1.png
│   ├── Q4_Home_Appliances.png
│   ├── Q4_Personal_Care.png
│   ├── Q5_ISU_by_City.png
│   ├── Q6_Hyderabad_IR_vs_ISU.png
│   └── Q7_Bengaluru_Revenue_Comparison.png
│
├── Solutions.pdf
├── README.md

```

---

# 🎯 Business Objectives

The project aims to answer the following business questions:

1. Analyze the distribution of stores across cities.
2. Measure category-wise contribution during the Sankranti campaign.
3. Examine the relationship between product price and quantity sold after promotion.
4. Study the distribution of quantity sold before promotions across product categories.
5. Compare Incremental Sold Units Percentage (ISU%) across cities.
6. Analyze Incremental Revenue (IR%) vs Incremental Sold Units (ISU%) for different promotion types in Hyderabad.
7. Compare revenue before and after promotions across product categories in Bengaluru.

---

# 📊 Project Visualizations

| Question | Visualization |
|----------|---------------|
| Q1 | Bar Chart – Number of Stores by City |
| Q2 | Pie Chart – Category-wise Contribution |
| Q3 | Correlation Heatmap |
| Q4 | Histograms by Product Category |
| Q5 | Line Chart – ISU% Across Cities |
| Q6 | Scatter Plot – IR% vs ISU% |
| Q7 | Clustered Bar Chart – Revenue Comparison |

All generated charts are available in the **resources/** directory.

---

# 📈 Key Business Insights

## 🏪 Store Distribution

- Bengaluru has the highest number of retail stores.
- Chennai and Hyderabad follow closely, indicating strong market presence.

---

## 🛒 Sankranti Campaign

- Grocery & Staples contributed over **70%** of total quantity sold after promotion.
- Home Appliances ranked second in contribution.

---

## 💰 Price vs Sales

- A weak positive correlation (~0.27) exists between post-promotion base price and quantity sold.
- Product pricing alone does not significantly influence sales volume.

---

## 📦 Product Categories

- Grocery & Staples consistently exhibit the highest demand.
- Personal Care products contribute the lowest sales volume.

---

## 📈 ISU% Analysis

- Madurai achieved the highest Incremental Sold Units Percentage.
- Visakhapatnam recorded the smallest improvement after promotions.

---

## 🎯 Promotion Effectiveness

- **BOGOF** generated the highest increase in units sold.
- **500 Cashback** produced the highest increase in revenue.

---

## 💵 Revenue Analysis

- Combo1 products experienced the highest revenue growth after promotions.
- Personal Care showed a decline in revenue, indicating scope for improving promotional strategies.

---

# 📁 Dataset Description

| Dataset | Description |
|----------|-------------|
| dim_campaigns.csv | Campaign information |
| dim_products.csv | Product details |
| dim_stores.csv | Store information |
| fact_events.csv | Promotional sales transactions |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/vijaysamco/RetailPromotionAnalysis.git
```

## Navigate to the Project

```bash
cd RetailPromotionAnalysis
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib
```

Run the Python notebooks or scripts to reproduce the analysis.

---

# 📄 Project Report

A comprehensive report containing:

- Business Questions
- Methodology
- Visualizations
- Business Insights
- Conclusions

is available in:

📘 **Solutions.pdf**

---

# 📸 Resources

All visualizations generated during the analysis are stored in the **resources/** folder.

---

# 🎯 Conclusion

This project demonstrates how data analytics can evaluate the success of retail promotional campaigns using business metrics such as **Incremental Revenue (IR%)** and **Incremental Sold Units (ISU%)**. The findings provide actionable insights into customer purchasing behavior, campaign effectiveness, and regional performance, enabling informed business decisions.

---

## 🤝 Connect

If you found this project useful, feel free to ⭐ star the repository and share your feedback.

Happy Learning! 🚀
