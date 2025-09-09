# Marketing Mix Modeling (MMM) – Portfolio Case Study

This project demonstrates how MMM can be used to optimize media investment by quantifying the incremental impact of marketing channels on sales.  
The notebook simulates a dataset and walks through the full MMM workflow — inspired by real-world consulting work but using fictional data for demonstration.

---

## 📖 Project Overview
Marketing Mix Modeling (MMM) helps businesses understand:
- How much incremental sales each channel drives
- Which channels deliver the best ROI
- How to reallocate spend to maximize efficiency and growth

---

## 🔍 Key Results (based on dummy data)
- TV drives strong base sales uplift but shows diminishing returns at higher spend levels.
- Digital channels (Search, Social, Display) deliver higher ROI (~2.0–2.5) compared to TV (~1.6).
- Synergy effects modeled between **TV + Digital Video**, boosting combined effectiveness.
- Scenario analysis shows that reallocating **10% of TV budget into Social** increases predicted revenue by 3% at the same total spend.

---

## 🛠️ Methodology
1. **Data Simulation & Cleaning**
   - Generated weekly data for sales and media spend across 6 channels over 2 years.
   - Added baseline drivers (trend, seasonality, external shocks).

2. **Feature Engineering**
   - Applied *adstock* (carryover effect of media).
   - Applied *saturation* (diminishing returns curves).

3. **Modeling**
   - Ridge/Lasso regression to estimate elasticities.
   - ROI calculated as incremental sales / spend per channel.

4. **Optimization**
   - Built a scenario planner to test budget reallocation strategies.

---

## 🚀 Recommendations (Hypothetical)
- Maintain baseline TV spend for brand building, but avoid over-saturation.
- Shift incremental spend toward Social and Search for higher ROI.
- Test synergy campaigns (TV + Digital Video) to capture halo effects.
- Revisit Ecommerce Display, which underperforms in ROI compared to benchmarks.

---

## 📊 Deliverables
- **Notebook:** `mmm_case_study.ipynb` with full analysis.
- **Figures:** ROI by channel, adstock curves, budget reallocation simulations.
