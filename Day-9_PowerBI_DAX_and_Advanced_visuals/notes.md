# 📊 Day 9 – Advanced Power BI Visuals & DAX Basics (Notes)

## 📌 Session Overview
In this session, we continue working on a Power BI project and explore advanced Power BI visuals, along with an introduction to basic DAX concepts used to create calculations and measures.

Day 9 focuses on improving reporting and analytical skills by using the right visuals and understanding how DAX supports dynamic insights in dashboards.

---

## 🎯 Learning Objectives
- Understand advanced Power BI visuals
- Learn when to use complex charts
- Introduction to DAX (Data Analysis Expressions)
- Create calculated columns and measures
- Improve analytical reporting skills

---

## 📊 Advanced Power BI Visuals

### 1️⃣ Area Chart
📌 **Purpose:** Show trends over time with magnitude.

✔ Best Used For:
- Cumulative sales
- Growth comparison
- Trend with volume impact

✔ Example:
- Sales growth by year

✔ Insight:
- Highlights both trend and total value

---

### 2️⃣ Line and Stacked Column Chart
📌 **Purpose:** Compare trends and categories together.

✔ Best Used For:
- Sales trend with category contribution
- Revenue vs profit comparison

✔ Example:
- Monthly sales (columns) with profit trend (line)

✔ Insight:
- Combines comparison and trend analysis

---

### 3️⃣ Ribbon Chart
📌 **Purpose:** Show rank changes over time.

✔ Best Used For:
- Market share changes
- Product ranking over time

✔ Example:
- Top products by sales across years

✔ Insight:
- Highlights how rankings change dynamically

---

### 4️⃣ Table Visual
📌 **Purpose:** Display detailed data.

✔ Best Used For:
- Exact values
- Transaction-level data
- Supporting visual insights

✔ Features:
- Sorting
- Filtering
- Conditional formatting

✔ Insight:
- Best for accuracy and detailed analysis

---

## 🧮 Introduction to DAX (Data Analysis Expressions)

DAX is a formula language used in Power BI to create calculations, measures, and calculated columns.

📌 Used for:
- Creating metrics
- Dynamic calculations
- Business logic implementation

---

## 🔢 DAX Basics

### Common DAX Functions
- SUM()
- COUNT()
- DISTINCTCOUNT()
- AVERAGE()
- MIN()
- MAX()

---

## 🧱 Calculated Columns
Calculated columns are computed **row by row** and stored in the table.

📌 Used For:
- Creating new fields
- Data categorization

✔ Example:
Total Sales = SUM(Sales[Amount])
Copy code

📌 Responds to slicers and filters.

---

## 🔍 Difference: Calculated Column vs Measure

| Feature | Calculated Column | Measure |
|-------|------------------|---------|
| Calculation | Row level | Aggregated |
| Storage | Stored in table | Calculated dynamically |
| Usage | Data modeling | Visuals & KPIs |

---

## 🧠 Key Takeaways
- Advanced visuals enhance storytelling
- Ribbon charts show rank movement
- Tables provide detailed insights
- DAX enables dynamic calculations
- Measures are core to interactive dashboards
 
    ├── ribbon_chart.png  
    └── table_visual.png
