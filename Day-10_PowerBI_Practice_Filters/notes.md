# 📊 Day 10 – Power BI Practice, Filters, Grouping & DAX (Notes)

## 📌 Session Overview
In this session, we focus on practical learning through assignment solving and strengthen our understanding of Power BI filters, grouping techniques, and DAX.

Day 10 is a hands-on, practice-oriented session designed to help apply previously learned concepts and gain confidence in building and modifying Power BI reports.

---

## 🎯 Learning Objectives
- Practice Power BI reporting through assignments
- Understand Power BI filters in detail
- Learn grouping techniques
- Apply DAX in real scenarios
- Improve report-building confidence

---

## 🧪 Assignment-Based Learning
This session focuses on:
- Solving real-world scenarios
- Modifying existing reports
- Applying visuals, filters, and DAX together
- Improving analytical thinking

---

## 🔍 Power BI Filters

Filters help control the data displayed in visuals and reports.

### Types of Filters

### 1️⃣ Visual-Level Filters
- Apply to a single visual
- Used for focused analysis

Example:
- Show sales for one product only

---

### 2️⃣ Page-Level Filters
- Apply to all visuals on a page
- Used for page-specific insights

Example:
- Filter report page by year

---

### 3️⃣ Report-Level Filters
- Apply to the entire report
- Used for global filtering

Example:
- Show data for a specific region across all pages

---

### 4️⃣ Slicers
- User-friendly filters
- Allow dynamic interaction

Example:
- Date slicer
- Region slicer

---

## 🧩 Grouping in Power BI

Grouping helps combine similar data into meaningful categories.

### Types of Grouping

### 1️⃣ Manual Grouping
- Group categories manually
- Useful for custom classification

Example:
- Group products into High / Medium / Low sales

---

### 2️⃣ Date Grouping
- Group by:
  - Year
  - Quarter
  - Month

Example:
- Monthly or yearly sales analysis

---

### 3️⃣ Numeric Grouping (Bins)
- Group numeric values into ranges

Example:
- Age groups
- Price ranges

---

## 🧮 DAX in Practice

DAX is used to create dynamic calculations and business metrics.

### Common DAX Practice Examples

### Total Sales
Total Sales = SUM(Sales[Amount])
Copy code

### Total Orders
Total Orders = COUNT(Sales[OrderID])
Copy code

### Average Sales
Average Sales = AVERAGE(Sales[Amount])
Copy code

### Profit
Profit = SUM(Sales[Sales]) - SUM(Sales[Cost])
Copy code

---

## 🔄 Applying Filters with DAX
- Measures respond to:
  - Filters
  - Slicers
  - Visual context

Example:
- Filter sales by year using slicers
- Dynamic calculation using measures

---

## 🧠 Key Takeaways
- Practice builds confidence
- Filters control data visibility
- Grouping simplifies complex data
- DAX enables dynamic reporting
- Hands-on work improves problem-solving skills
