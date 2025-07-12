# ✅ Visualization and Analysis on Restaurant Data

## 📌 Project Overview
This project focuses on visualizing and analyzing sales and item-level data from a restaurant. Using date-based filtering, aggregation, and visual tools, we derive insights into customer behavior, sales trends, and category-wise performance.

---

## 🗃️ Dataset Information
- **Source:** Local file uploaded to Google Colab (`/content/drive/MyDrive/Data.csv`)
- **Format:** CSV
- **Rows & Columns:** Varies depending on records
- **Assumed Key Features:**
  - `Invoice No.`: Unique transaction identifier
  - `Date`: Transaction date
  - `Item Name`: Name of the product sold
  - `Qty.`: Quantity sold
  - `Final Total`: Total amount of the bill
  - `Category`: Product category (e.g., Beverages, Starters)

---

## 📊 Data Preprocessing & Filtering
Performed steps include:
- Loaded dataset using `pandas`
- Aggregated mean `Final Total` per day
- Checked number of unique invoices
- Filtered data for:
  - **September 2023** (to find top-selling item)
  - **July 2023** (to identify least-selling categories)

---

## 📉 Data Analysis and Visualization

### 🔹 September Analysis
- Filtered data from **2023-09-01 to 2023-09-30**
- Identified **top-selling item** by summing `Qty.` grouped by `Item Name`

### 🔹 July Analysis
- Filtered data from **2023-07-01 to 2023-07-31**
- Found **least-selling categories** using total quantity sold

### 🔸 Visualizations
- **Bar Plot** using Seaborn for category-wise item sales in July
- **Pie Chart** using Matplotlib to show `Final Total` share per category

---

## 🔍 Insights & Observations
- The most profitable day (by average bill amount) was identified.
- Sales trends reveal specific items/categories dominate in particular months.
- Certain product categories underperform and may need promotional focus.

---

## 📌 Tools & Libraries Used
- `Python`
- `Pandas` for data manipulation
- `Matplotlib` for plotting
- `Seaborn` for advanced visualization
- `NumPy` for numerical operations

---

## 🧠 Future Scope
- Build dashboards for monthly sales summaries
- Use time series analysis for forecasting demand
- Automate reports for inventory and stock planning
- Add customer segmentation based on purchase behavior

---

## 📷 Visualizations

> Example visualization markdown for your GitHub repo:

```markdown
![Bar Plot of July Least-Selling Categories](images/july_least_selling_categories.png)
![Pie Chart of Category-wise Revenue](images/category_revenue_pie.png)
