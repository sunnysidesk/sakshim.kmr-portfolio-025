# SEO & Keyword Analysis Project

This project was completed as part of a graduate practicum, where the goal was to help a digital marketing agency improve its organic search strategy. The work focused on **integrating analytics data, applying machine learning, and generating a roadmap for better keyword targeting and user engagement**.

---

## 📖 Project Overview

Traditional SEO reporting often stops at search volume and rankings. In this project, we went further by combining **behavioral analytics (GA4)** with **search performance data (GSC + third-party SEO tools)** to identify keywords that don’t just rank, but also **engage and convert**.  

The final deliverable was a modeling framework and set of recommendations that any agency could adapt to optimize their organic search presence.

---

## 🔍 Key Results

- **Organic traffic attracts new users** but typically shows **low retention**, highlighting a need for content aligned with long-term engagement.  
- **User engagement patterns were seasonal**, spiking in certain months before leveling off — a sign of volatility in organic behavior.  
- **Direct traffic users engaged the longest**, reflecting strong brand familiarity, while organic users disengaged more quickly.  
- **Modeling approach**:  
  - Lasso regression explained **~77% of SERP ranking variation**.  
  - Top predictors: **CTR, impressions, and keyword intent type**.  
  - Longer word count correlated negatively with engagement, suggesting **shorter, intent-focused pages** perform better.

---

## 📊 Insights

- **Geo-targeting gaps**: Demand across regions did not always match localized SEO coverage.  
- **Keyword quality > quantity**: Intent (navigational, transactional) predicted ranking and engagement more strongly than raw volume.  
- **Content mix imbalance**: Heavy reliance on blog content diluted engagement; commercial and transactional pages offered better conversion potential.  
- **Engagement probability matters**: High traffic ≠ high engagement. Keywords with strong engagement signals became prime targets.

---

## 🚀 Strategic Recommendations

1. **Strengthen Local SEO**  
   Prioritize regions where search demand is high but CTR or engagement is underperforming.  

2. **Target High-Opportunity Keywords**  
   Build an **Opportunity Score** combining rankability (volume + difficulty) with predicted engagement.  

3. **Refocus Content Strategy**  
   - Move away from long, generic blog posts.  
   - Develop **short, intent-driven landing pages** optimized for conversion.  

4. **Behavior-Informed SEO**  
   Integrate **engagement probability metrics** from GA4 into keyword prioritization, not just rankability scores.  

5. **Technical SEO Enhancements**  
   Optimize metadata and apply schema markup to improve CTR and visibility.

---

## 🛠️ Methods & Models

- **Data Integration Pipeline**  
  - Joined GA4 & GSC on URL  
  - Expanded dataset by exploding keyword values  
  - Merged with third-party SEO data on keyword  

- **Modeling Techniques**  
  - **Lasso Regression** → Feature selection & ranking predictors of SERP performance  
  - **Logistic Regression** → Engagement prediction (Accuracy 0.77, Recall 0.80, F1 Score 0.75)  
  - **Elastic Net & Random Forest** → Used for comparison and validation  

---

## 📌 Takeaway

By merging search and behavioral analytics, this project demonstrates how data science can transform SEO from chasing rankings into building **strategies that rank, engage, and convert**. The framework is generalizable to any content-driven business looking to optimize organic performance.
