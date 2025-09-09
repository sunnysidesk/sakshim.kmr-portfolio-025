# SEO & Keyword Analysis – KWSM Project

This project integrates Google Analytics 4 (GA4), Google Search Console (GSC), and Ahrefs data to evaluate KWSM’s organic search performance. The analysis focuses on identifying high-intent, commercially valuable keywords that not only rank but also **engage and convert**.

---

## 🔍 Key Results

- **Organic search is the top acquisition channel** but has **low user retention**. Even high-performing pages show a near 1:1 ratio of new to active users.
- **Engagement patterns show seasonality**: steady activity from March–July, spike in September, drop in October, then leveling off.
- **Direct traffic users engage the longest**, reflecting high brand intent, while organic users bounce earlier.
- **Merged dataset creation**: GA4 + GSC (on URL) + Ahrefs (on Keyword) enabled advanced modeling of keywords beyond raw traffic numbers.
- **Model performance**:  
  - Lasso Regression explained **77% of SERP ranking variation**  
  - Key drivers: **CTR, impressions, and keyword intent type**  
  - Longer word count correlated negatively with engagement

---

## 📊 Insights

- **Geo mismatches**: High-demand cities show inconsistent local SEO coverage. Click-through rates (CTR) are not aligned with search volume.
- **Keyword quality > quantity**: Intent (navigational, transactional) is more predictive of rank and engagement than raw traffic volume.
- **Blog saturation**: The word *“blog”* appeared **4,000+ times** across site content. Heavy reliance on blog pages may dilute engagement.
- **Short, intent-driven pages outperform** longer ones in driving meaningful engagement.

---

## 🚀 Strategic Recommendations

1. **Local SEO Focus**  
   Optimize for high-demand cities where search volume is strong but CTR is weak. Tailor localized content to capture those opportunities.

2. **Prioritize High-Opportunity Keywords**  
   Target the **top 7 keywords by Opportunity Score** (high intent, low difficulty, favorable predicted rank). Only 2 currently show conversion — quick wins are available.

3. **Shift Content Strategy**  
   - Reduce reliance on long-form blog posts.  
   - Build **shorter, intent-focused landing pages** designed to convert.  

4. **Behavior-Driven SEO**  
   Incorporate **Predicted Engagement Probability** (from GA4) into keyword targeting — not just rankability, but likelihood of keeping users engaged.

5. **Technical SEO Enhancements**  
   - Strengthen CTR by refining meta titles and descriptions.  
   - Leverage schema markup for service pages.  

---

## 🛠️ Methods & Models

- **Data pipeline**: GSC + GA4 + Ahrefs merged and expanded by keywords  
- **Modeling techniques**:  
  - **Lasso Regression** for feature selection  
  - **Logistic Regression** for engagement prediction (Accuracy 0.77, Recall 0.80, F1 0.75)  
  - **Elastic Net and Random Forest** explored in appendices  

---

## 📌 Takeaway

This project demonstrates how blending **behavioral analytics** with **SEO keyword modeling** moves beyond ranking for clicks — it helps identify **keywords that rank, engage, and convert**, guiding a roadmap for scalable organic growth.
