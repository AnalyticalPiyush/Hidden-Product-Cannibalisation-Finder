# Hidden Product Cannibalisation Finder: Unmasking True Growth in FMCG Portfolios  

## 1. Business Problem  
In the fast-moving consumer goods (FMCG) industry, companies frequently launch new SKUs to capture market share and drive growth. However, these new products often cannibalise existing SKUs instead of bringing true incremental sales.  

For Cadbury, the launch of **New Dairy Milk Crunch 45g** raised a critical question:  
- Did Crunch expand category sales?  
- Or did it simply steal share from existing Dairy Milk variants such as Classic, Caramel, Almond, and Fruit & Nut?  

---

## 2. Objective  
The project aimed to:  
- Detect and measure cannibalisation within the Dairy Milk portfolio.  
- Quantify incremental vs cannibalised sales after the Crunch launch.  
- Provide actionable recommendations for SKU portfolio optimisation and profitable growth.  

---

## 3. Requirements  
- **Data**: SKU-level sales including date, region, price, and promotion.  
- **Tools**: Python (Pandas, NumPy, Seaborn) for data generation, cleaning, and modelling; Power BI for dashboarding and storytelling.  
- **KPIs**: Cannibalisation %, Incremental Sales, Net Growth, and SKU-level Before vs After comparisons.  

---

## 4. Process  
1. **Data Generation**: Created a synthetic dataset (20 weeks) simulating weekly sales for Dairy Milk Classic, Caramel, Almond, Fruit & Nut, and New Crunch, with realistic demand patterns, promotions, and price variations.  
2. **Exploratory Analysis**: Compared sales before and after Crunch’s launch, visualising SKU trends and regional breakdowns.  
3. **Cannibalisation Modelling**: Calculated Classic’s expected sales vs actual post-launch, quantified lost sales, and derived a Cannibalisation % KPI.  
4. **Dashboard Development**: Built a Power BI dashboard with KPI cards, time-series trends, clustered bar charts, waterfall decomposition, and a cannibalisation matrix for actionable insights.  

---

## 5. Outcome  
Deliverables produced:  
- Python notebook with data generation, cleaning, and analysis scripts.  
- Synthetic dataset (CSV) for reproducibility.  
- Power BI dashboard with multiple analysis pages (Overview, Before vs After, Cannibalisation Insights, Recommendations).  
- Case study slide deck for executive storytelling.  
- GitHub repository containing dataset, code, dashboard, and documentation.  

---

## 6. Results / Insights  
- Dairy Milk Classic was the primary victim of cannibalisation, losing approximately **966 units** after Crunch’s launch.  
- Nearly **60% of Crunch’s 4.65K sales** were cannibalised from existing SKUs rather than being truly incremental.  
- Net growth was positive but significantly smaller than suggested by Crunch’s headline sales performance.  
- Regionally, England showed stable performance, while Wales and Scotland experienced sharper declines in existing SKU sales.  
<img width="1223" height="688" alt="Screenshot 2025-09-16 at 20 34 15" src="https://github.com/user-attachments/assets/2d88ad9c-ed0a-41f3-bb32-cf9dec0eb8ee" />

---

## 7. Business Value / Recommendations  
This project provides FMCG managers with a framework to separate incremental growth from cannibalisation, enabling more informed decisions about portfolio strategy. Recommendations include:  
- Reposition Classic as a value-driven SKU to reduce overlap with Crunch.  
- Bundle Crunch with smaller SKUs to capture both premium and everyday demand.  
- Consider retiring or reformulating underperforming variants if profitability declines.  

---

## 8. Summary  
This project demonstrates how data science and analytics can uncover hidden cannibalisation, quantify true incremental growth, and guide businesses in making evidence-based portfolio decisions.  

By combining **Python modelling** and **Power BI storytelling**, it highlights the importance of measuring real business impact before celebrating new product launches.  

