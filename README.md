# 🛒 Customer Purchase Behaviour Analysis

<div align="center">

**From raw retail transactions → clear business strategy 🧠📈**

<p>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue"/>
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20Compatible-orange"/>
  <img src="https://img.shields.io/badge/PowerBI-Dashboard-yellow"/>
  <img src="https://img.shields.io/badge/Presentation-Included-brightgreen"/>
  <img src="https://img.shields.io/badge/License-MIT-green"/>
</p>

### 📊 Analyze → Visualize → Decide → Grow  
*Understand customers so businesses can act, not assume.*

</div>

---

## 🔍 Business Problem
Retail data contains answers most businesses never extract:

- Which products generate real revenue?
- Which demographic buys the most?
- When do purchases spike?
- Are discounts helping or hurting margins?
- Why aren't loyal buyers subscribing?

This project digs into those questions and **outputs decisions, not just statistics**.

---

## ⚙️ Workflow Pipeline
1. Load 3,900 retail transactions  
2. Clean & preprocess using Python  
3. Query strategic KPIs using SQL  
4. Validate insights visually in Power BI  
5. Deliver findings through **Dashboard + Report + Presentation**

---

## 🧠 Summary of Key Insights
- **Male customers drive 68% of total revenue** (~$157,890) vs 32% by females.  
- **80% of customers are loyal**, 18% returning, only 2% new → retention is good, acquisition isn't.  
- **Only 27% are subscribed**, even though spending is almost identical between subscribers & non-subscribers (~$59 avg).  
- 2,518 repeat buyers (>5 purchases) remain **unsubscribed**, meaning subscription perks aren’t convincing enough.  
- **Top rated products:** Gloves (3.86⭐), Sandals (3.84⭐), Boots (3.82⭐).  
- **Discount-dependent items:** Hat, Sneakers, Coat, Sweater, Pants show ~45–50% discount usage → margin risk.  
- Express-shipping users spend slightly more → price-insensitive, convenience-focused segment.

_All findings sourced from project presentation._ :contentReference[oaicite:0]{index=0}

---

## 📁 Repository Overview

| File | Purpose |
|------|--------|
| `Customer Purchase Behavior Analysis.ipynb` | Data cleaning, EDA, insights extraction |
| `customer_behavior_sql_queries.sql` | Ranked insights & business KPIs |
| `customer_shopping_behavior.csv` | Retail transaction dataset |
| `Customer Behaviour Dashboard.pbix` | Interactive Power BI visuals |
| `Customer Purchase Behaviour Analysis.pdf` | Formal documented report |
| `Customer-Shopping-Behavior-Analysis.pptx` | Presentation summarizing 3,900 purchases, 18 columns, 50 locations, segmentation, ratings, discounts, shipping trends, and business recommendations |

---

## 🚀 Run This Project

```bash
git clone https://github.com/harish-3/Customer-Purchase-Behaviour-Analysis.git
cd Customer-Purchase-Behaviour-Analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook
