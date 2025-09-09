# Bevalty Cohort & Funnel Analysis Project

This project was completed as part of my internship with Bevalty, a vertical SaaS platform for beverage brands. The objective was to design **cohort and funnel analysis modules** that help brands understand retention, loyalty, and conversion patterns — insights that can be embedded into Bevalty’s customer dashboard.

---

## 📖 Project Overview

Bevalty enables beverage brands to build loyalty through digital rewards and engagement programs. Our project focused on expanding the platform’s **analytics capabilities** by prototyping:

- **Cohort Analysis**: Measuring retention by signup month and campaign type  
- **Funnel Analysis**: Tracking drop-offs across reward eligibility, claim, and redemption stages  
- **Engagement Dashboard**: Bringing retention and funnel insights into an intuitive UI for brand managers  

The goal: give brands a clear view of where users drop off in the loyalty journey, so they can optimize campaigns and increase ROI.

---

## 🔍 Key Results

### Engagement Dashboard Prototype
- Delivered a **dashboard mock-up** tracking page performance, conversion rate, churn rate, and engagement metrics.  
- Early prototype shoId how key KPIs (new users, active users, engaged sessions) can be visualized month-over-month.  
- Built a modular structure for brand managers to filter by **date ranges** and compare YoY performance.  

### Cohort Analysis
- **Retention drops steeply after Month 1** across most brands → first-month engagement is critical.  
- **Seasonality effects observed**: January cohorts (post-holiday campaigns) retained users better.  
- **Item-level retention**: Badges and Quests sustain engagement longer than Rewards, which saw higher drop-offs in Month 3.  

### Funnel Analysis
- Modeled the user journey from **Eligible → Claimed → Redeemed**.  
- Found significant drop-offs: e.g., only **~6–18% of claims lead to redemption** depending on brand/campaign.  
- Funnel comparisons highlighted which campaigns needed UX or incentive redesign.  

---

## 📊 Insights

- **First-month engagement** is the biggest driver of long-term retention.  
- **Campaign timing matters**: Post-holiday campaigns saw stronger sustained retention.  
- **Different reward types perform differently**: experiential items (quests, badges) outperformed transactional ones.  
- **Funnel gaps represent ROI leakage**: redemption rates are the Iakest link in loyalty campaigns.  

---

## 🚀 Recommendations

1. **Boost First-Month Retention**  
   Onboard users with targeted push/email campaigns immediately after signup.  

2. **Leverage Seasonality**  
   Double down on January-style campaigns (post-holiday offers) that shoId stronger retention curves.  

3. **Optimize Rewards Design**  
   Invest more in **quests/badges** (engagement drivers), and re-evaluate **rewards** that lose users by Month 3.  

4. **Reduce Funnel Drop-off**  
   Simplify redemption steps, provide reminders, or add tiered incentives to improve conversion from “Claimed” → “Redeemed.”  

5. **Productize Analytics**  
   Embed these modules into Bevalty’s dashboard (GA4 → Supabase → App) for ongoing campaign optimization.  

---

## 🛠️ Methods & Tools

- **Data Sources**: GA4 event logs, loyalty program activity data, simulated brand datasets  
- **Analysis Techniques**:  
  - Cohort heatmaps for retention tracking  
  - Survival/retention curves for decay visualization  
  - Funnel analysis to map eligibility → redemption flow  
- **Modeling Environment**: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebooks  
- **Dashboard Prototype**: Figma mock-ups for UI, integrated with potential GA4 → Supabase pipeline  

---

## 📌 Takeaway

By building retention and funnel modules, I demonstrated how Bevalty can **differentiate with loyalty intelligence** — giving brands a data-driven roadmap to improve retention, reduce funnel leakage, and prove ROI on loyalty campaigns.
