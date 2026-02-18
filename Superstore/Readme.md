# 🛒 Superstore Sales Analysis — Power BI  Project

This is continuation from previous **MySQL** project [Superstore](https://github.com/akmalbakeri/SQL/tree/main/superstore_sql) into a  **Power BI** for visualization.  
Data is exported from MySQL GUI export to csv. 
Power BI is exporting these CSV into Data Model and Dashboard Power BI is saved as [superstore.pdf](https://github.com/akmalbakeri/Visualization/blob/main/Superstore/src/superstore.pdf)

---


## 🔍 Key Findings

![Page 1](https://github.com/akmalbakeri/Visualization/blob/main/Superstore/src/page1.JPG)
### 1. Sales Trend (1.1 & 1.2)
- Sales show a consistent **year-on-year increase** from 2014 to 2017
- **December** records the highest monthly sales, likely driven by Christmas and Black Friday seasonal demand — suggesting an opportunity to optimize inventory ahead of Q4
- **January** sees the sharpest decline, typical post-holiday slowdown
- Sales remain relatively **stable between April and August**

![Page 2](https://github.com/akmalbakeri/Visualization/blob/main/Superstore/src/page2.JPG)
### 2. Sales vs Profit Gap (3.2)
- There is a **massive gap between total sales and total profit** across all categories
- This suggests the business relies heavily on **sales volume rather than product margin** — a risk if sales volume drops
- Improving profit margin should be a strategic priority

### 3. Profit Margin by Category (3.1)
- **Office Supplies** is the most profitable category with ~26–28% margin across all segments
- **Technology** sits at ~19–20% margin
- **Furniture** is the weakest at only 7–12% margin, despite generating significant sales

### 4. Scatter Plot — Profit Margin % vs Total Profit by Sub-category (3.3)

Products are segmented into four quadrants based on average profit margin % and total profit:

| Quadrant | Products | Strategy |
|---|---|---|
| ⭐ Q1: High Margin & High Profit | Copiers, Paper, Accessories | Most valuable — keep selling and investing |
| 💎 Q2: High Margin & Low Profit | Labels, Envelopes, Fasteners | High potential — focus marketing efforts here |
| ⚠️ Q3: Low Margin & High Profit | Phones, Chairs, Binders | Dependent on volume — justify keeping via sales ranking |
| 🔴 Q4: Low Margin & Low Profit | Machines, Bookcases, Supplies | Cutting these products could improve overall profit |

![Page 3](https://github.com/akmalbakeri/Visualization/blob/main/Superstore/src/page3.JPG)
### 5. Sales by Region (4)
- Sales are fairly evenly distributed across all regions — **West leads slightly at 31.58%** but no region significantly underperforms

### 6. Top Sales vs Top Profit (5.1 & 5.2)
- **Phones, Chairs, and Binders** rank in the top 5 by sales but fall in Q3 (low margin)
- Their high sales volume justifies keeping them in the product lineup
- **Copiers** ranks #1 in profit despite being lower in sales rank — confirming it as the standout product

![Page 4](https://github.com/akmalbakeri/Visualization/blob/main/Superstore/src/page4.JPG)
### 7. Most Loss-Making Products (6)
Cross-referencing the bottom 10 loss-making products with the Q4 sub-categories reveals 5 products that appear in **both** lists — making them strong candidates for discontinuation:

 Cubify CubeX 3D Printer Double Head( Machines ), Lexmark MX611dhe Monochrome Laser Printer ( Machines), Cubify CubeX 3D Printer Triple Head (Machines) ,  Cisco TelePresence System EX90 Videoconferencing (Machines), Martin Yale Chadless Opener Electric Letter Opener (Supplies)

### 8. Growth Rate 2017 (7.1 & 7.2)
- **Ibico Hi-Tech Manual Binding** (Binders) recorded the highest growth rate in 2017 at ~10.9K, consistent with Binders appearing in both top sales and Q3
- Bottom growth products show similar decline rates (~-93% to -96%) with no single standout outlier

---

## ✅ Recommendations

1. **Stock up inventory ahead of December** — identify which specific sub-categories drive the Q4 spike to optimize procurement
2. **Improve profit margins** — the business is over-reliant on volume; focus on higher margin products
3. **Invest in Q2 products** (Labels, Envelopes, Fasteners) — high margin but undermarketed; growth opportunity with relatively low risk
4. **Discontinue loss-making Machine products** — 4 of the top 10 loss-making products are Machines, which also sit in Q4 of the quadrant analysis
5. **Keep Q3 products** (Phones, Chairs, Binders) — low margin but high volume justifies their place in the lineup

---
