# Market Basket Analysis (Grocery)

## 📌 Business Context
Retailers increase revenue by surfacing cross-sell opportunities and optimizing store layout.

## 🎯 Objective
Discover product associations (e.g., bread → butter) to inform promotions, bundles, and shelf placement.

## 🗂️ Dataset
- Suggested source: Transactional basket data (anonymized)
- Columns: TransactionID, Product, Quantity, Timestamp

## 🔧 Tools & Techniques
- Python (Pandas)
- Association Rules (Apriori / FP-Growth)
- Tableau / Power BI for visualizing support, confidence, lift

## 📊 Key Questions
- Which pairs/sets of products co-occur most?
- What association rules are strongest (by lift)?
- What promotions or bundles should we test?

## 🖼️ Visuals
![MBA Dashboard](dashboards/mba_dashboard.png)

## 💡 Recommendations
- Bundle high-lift pairs in weekly promos
- Reposition products with strong co-occurrence nearby
- Targeted coupons based on basket patterns

## ▶️ How to Use
1) Place `transactions.csv` in `data/`
2) Run `notebooks/mba.ipynb` or `scripts/mba.py` to compute rules
3) Visualize results in your BI tool and export a screenshot to `dashboards/`
