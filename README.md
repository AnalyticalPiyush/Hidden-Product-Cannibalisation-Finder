# Hidden Product Cannibalisation Finder
Uncovering whether new product launches drive true growth or cannibalise existing SKUs in FMCG.

## Overview
In FMCG, new product launches don’t always bring incremental growth — sometimes they cannibalise existing SKUs. This project demonstrates how data analytics can separate true innovation from internal substitution, using Cadbury’s Dairy Milk portfolio as a case study.

## Problem Statement
When New Dairy Milk Crunch 45g launched, management wanted to know:
- Did Crunch bring new sales to the category?
- Or did it simply steal share from Classic and other Dairy Milk SKUs?

## Data
- Synthetic dataset (20 weeks) built in Python to simulate SKU-level sales, pricing, promotions, and launch timing.
- SKUs: Dairy Milk Classic, Caramel, Almond, Fruit & Nut, and New Crunch.

## Tools
- Python: Pandas, NumPy, Matplotlib/Seaborn
- Power BI: Interactive dashboard (Overview, Before vs After, Cannibalisation Insights, Recommendations)

## Methodology
1. Generated synthetic SKU-level sales data with realistic seasonality, promo effects, and cannibalisation impact.
2. Performed EDA to analyse sales before and after launch.
3. Built models to estimate cannibalised vs incremental sales.
4. Designed Power BI dashboard for storytelling and decision support.

## Key Insights
- Classic was the primary victim, losing ~966 units after Crunch launched.
- Around 60% of Crunch’s sales were cannibalised from existing SKUs, mainly Classic.
- Net portfolio growth was positive but smaller than headline sales suggested.

## Deliverables
- [Python Notebook](Dairymilk.ipynb)
- [Power BI Dashboard](Cadbury_Cannibalisation.pbix)
- [Case Study Slides](slides/Case_Study_Presentation.pdf)
- [Dataset](dairymilk_cannibalisation_20w.csv)

## Business Value
This project provides FMCG managers with a framework to:
- Quantify incremental vs cannibalised sales
- Make evidence-based SKU decisions (reposition, bundle, or retire)
- Protect portfolio profitability while innovating

## Preview
<img width="1241" height="699" alt="Screenshot 2025-09-02 at 13 51 50" src="https://github.com/user-attachments/assets/01a8cdfe-e7d3-461d-b4a9-7cde068ed41c" />


---
