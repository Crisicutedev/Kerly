# 📊 Sales Exploratory Data Analysis - Mother's Day Campaign

This project contains an Exploratory Data Analysis (EDA) performed using Python. The goal is to understand sales behavior during a specific period and propose actionable strategies to improve performance during the month of May, with a special focus on the opportunity around Mother's Day.

---

## 🔍 Objective

- Analyze sales data to detect patterns, key product categories, and potential performance drops.
- Create insightful visualizations to support decision-making.
- Suggest marketing strategies based on findings.

---

## 📁 Dataset Structure

The dataset used contains the following 5 main columns:

| Column    | Description                          |
|-----------|--------------------------------------|
| FECHA     | Date of the sale                     |
| CATEGORIA | Product category or classification   |
| CODIGO    | Product code                         |
| TOTAL     | Total amount of the sale             |
| VENDEDOR  | Salesperson responsible              |

---

## 🧪 Analysis Process

### 1. **Data Import and Cleaning**
- Loaded the dataset and converted date strings to datetime format.
- Detected null values; two rows were missing salesperson names.

### 2. **General Exploration**
- Checked the number of records by category and salesperson.
- Explored the distribution of sales values (`TOTAL`).

### 3. **Generated Visualizations**
- **Stripplots** to visualize sales distribution by `CATEGORIA` and `VENDEDOR`.
- **Time-based scatterplot** to view sales trends over time (`FECHA`).
- **Correlation heatmap** (only one main numeric variable available).
- **Barplot** showing average sales by category to highlight top performers.

### 4. **Monthly Analysis**
- Extracted month from `FECHA` to compare historical performance in May and identify opportunities.

---

## 🎯 Suggested Strategies to Boost May Sales

- Create **Mother’s Day promotional bundles**.
- Organize products into a dedicated Mother's Day section.
- Launch quick social media campaigns with gift suggestions.
- Offer limited-time discounts or flash coupons.
- Guarantee delivery before May 10th.
- Contact previous customers with personalized offers.

---

## 🛠️ Tools Used

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
- Analysis with Power BI

---

## 📌 Next Steps

- Perform customer segmentation (if customer data is available).
- Forecast future sales using statistical or machine learning models.
- Automate detection of early sales drops for proactive action.

---

## 🤝 Contributions

This analysis was developed as part of an internal exploration. Suggestions and improvements are welcome. Feel free to open pull requests or issues.
