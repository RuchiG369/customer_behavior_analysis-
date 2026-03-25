# 📊 Customer Shopping Behavior Analysis

## 🔍 Overview

This project presents an end-to-end data analytics workflow using customer shopping behavior data. It covers data loading, exploratory data analysis, data cleaning, SQL-based business analysis, dashboard creation in Tableau, and final reporting. The objective is to extract meaningful insights from customer purchase patterns and present them in a clear, business-friendly format.

---

## 📁 Dataset

- **Dataset Name:** Customer Shopping Behavior Dataset
- **Format:** CSV
- **Files Included:**
  - `customer_shopping_behavior.csv`
  - `customer_shopping_behavior.sql`
  - `customer_behavior_dashboard.png`
  - `customer_behavior_report.pdf`
The dataset contains structured customer purchase information used to analyze product trends, spending behavior, subscription patterns, shipping preferences, customer segments, and revenue contribution across groups.

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **SQL**: PostgreSQL 
- **Tableau**: Dashboard design and visualization
- **Gamma**: Presentation creation
- **Jupyter Notebook**: Analysis environment

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported the dataset using Python
- Checked structure, column names, data types, and basic quality

### 2. Exploratory Data Analysis (EDA)
- Reviewed summary statistics
- Explored customer behavior and purchase trends
- Identified important patterns using visual analysis

### 3. Data Cleaning
- Handled missing values where needed
- Removed duplicates
- Standardized fields for analysis
- Prepared the data for SQL querying and dashboard use

### 4. SQL Analysis
- Wrote SQL queries in PostgreSQL to answer business questions
- Performed filtering, grouping, aggregations, and ranking
- Analyzed product ratings, discount impact, subscription behavior, customer segmentation, and revenue

  
### 5. Dashboard Creation
- Built an interactive dashboard in Tableau
- Highlighted key KPIs and business insights
- Designed the dashboard for quick stakeholder understanding

### 6. Reporting
- Summarized findings into a structured PDF report
- Included business recommendations based on the analysis

### 7. Presentation
- Created a presentation in Gamma to communicate the project clearly
- Focused on concise storytelling and visual explanation of results

---

## 📊 Dashboard

The Tableau dashboard presents the key findings from the analysis, including:

- Customer spending behavior
- Subscription insights
- Revenue distribution
- Product and category performance
- Segment-based analysis

A dashboard preview is included in the repository:

- `customer behavior Dashboard .png`

---

## 📈 Key Results

Some of the main insights from the analysis include:

- Top-rated products were identified based on average review ratings
- Express shipping showed a slightly higher average purchase amount than standard shipping
- Non-subscribers generated higher total revenue overall due to larger customer count
- Certain products showed a very high dependency on discounts
- Most customers fell into the loyal segment
- Young adults contributed the highest total revenue among age groups
- Repeat buyers were not always subscribers, highlighting opportunities for loyalty conversion

---

## 💡 Business Recommendations

- Promote stronger subscription benefits to improve subscriber growth
- Create loyalty programs to convert repeat buyers into long-term loyal customers
- Review discount strategies to balance revenue growth with profitability
- Highlight best-selling and top-rated products in marketing campaigns
- Focus campaigns on high-revenue customer groups and shipping behaviors

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/RuchiG369/customer_behavior_analysis.git
cd customer_behavior_analysis
 ```
### 2. Run SQL Queries

Use PostgreSQL to run the SQL queries provided in `customer_shopping_behavior.sql`.
