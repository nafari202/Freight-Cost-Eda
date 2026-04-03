# Freight Cost Exploratory Data Analysis
**Author:** Nana Afari  
**Tools:** Python (Pandas, Matplotlib, Seaborn, NumPy) · Jupyter Notebooks  
**Data:** Olist Brazilian E-Commerce Dataset (Kaggle, 110,189 orders)

---

## Project Overview
Exploratory data analysis on a real-world e-commerce logistics dataset to 
identify freight cost drivers and delivery performance patterns across 73 
product categories and 27 Brazilian states.

---

## Key Findings
- Average freight cost per order: **R$19.95** (median R$16.26)
- Overall on-time delivery rate: **92.1%** across 110,189 delivered orders
- Delivery times averaged **12 days**, with high variance suggesting 
  regional and carrier-level inefficiencies
- Weak positive correlation between product price and freight cost — 
  size and distance are likely stronger cost drivers

---

## Visualizations
| Chart | Description |
|-------|-------------|
| `viz1_freight_distribution.png` | Histogram of freight costs per order with mean marker |
| `viz2_freight_by_category.png` | Top 15 product categories by average freight cost |
| `viz3_price_vs_freight.png` | Scatter plot of order value vs. freight cost with trend line |

---

## Files
- `freight-cost-eda.ipynb` — Full analysis notebook with markdown commentary
- `viz1_freight_distribution.png`
- `viz2_freight_by_category.png`
- `viz3_price_vs_freight.png`

---

## How to Run
1. Download the [Olist dataset from Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
2. Open `freight-cost-eda.ipynb` in Jupyter or Kaggle
3. Run all cells in order
