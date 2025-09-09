# Sakshi Kumar's Data Science & Analytics Portfolio

Hi, I’m Sakshi 🏖️  
I specialize in marketing science, product analytics, and experimentation — turning messy datasets into insights and frameworks that guide real business decisions.  
This portfolio highlights anonymized case studies from my work across consulting, SaaS, and digital marketing.

---

## 📊 Retention & Funnel Analytics (Consumer Loyalty Platform)
**Problem:** Identify where customers drop off in the loyalty journey and improve campaign ROI.  
**Approach:**  
- Built SQL pipelines + Python cohort analysis.  
- Designed retention heatmaps and funnel journeys (sign-up → claim → redeem).  
- Combined GA4 data with reward engagement logs.  
**Outcome:**  
Pinpointed steep 1st-month drop-offs, identified seasonal retention trends, and highlighted UX bottlenecks (only 6% claim → redemption).  
**Link:** [Anonymized Cohort Analysis Slides](retention-funnel-loyalty)

---

## 🔍 SEO + Engagement Modeling (Digital Agency Case Study)
**Problem:** Organic search attracted users but retention was low. Client wanted to identify high-intent keywords that drive engagement, not just traffic.  
**Approach:**  
- Merged GA4 + GSC + Ahrefs datasets.  
- Built logistic regression + Lasso models to rank keywords by engagement probability.  
- Visualized feature importance (CTR, impressions, intent).  
**Outcome:**  
Identified 7 high-opportunity geo-keywords, optimized localized SEO strategy, and boosted engagement conversion visibility.  
**Link:** [SEO + Engagement Project](seo-engagement-modeling)

---

## 📈 Marketing Mix Modeling (Global CPG Client)
**Problem:** Quantify media ROI and guide £3M+ cross-market spend allocation.  
**Approach:**  
- Developed econometric models (regression + UCMs) in Python.  
- Automated MMM workflows and standardized scenario simulations.  
- Embedded outputs into optimization platform with custom business rules.  
**Outcome:**  
Improved allocation accuracy, increased ROI by 13%, and improved forecast reliability by 8%.  
**Link:** [Example Notebook Snippet](mmm-forecasting)

---

## 💞 MatchMadeinML (Vector Search for Dating Profiles)
**Problem:** Build a system that recommends compatible dating profiles based on interests and personality traits.  
**Approach:**  
- Implemented **FAISS** (Facebook AI Similarity Search) for efficient nearest-neighbor lookups.  
- Engineered embeddings from user profiles (text + categorical features).  
- Designed matching pipeline with Python + FAISS to handle high-dimensional vectors.  
**Outcome:**  
Created a proof-of-concept matching engine that returns top-k compatible profiles in milliseconds, demonstrating how vector similarity search powers recommendation systems.  
**Repo:** [MatchMadeinML](https://github.com/sunnysidesk/MatchMadeinML)  

---

## 🤖 Conversational AI Chatbot (NLP Project)
**Problem:** Design a chatbot capable of detecting user intent and providing contextually relevant responses — a core challenge in healthcare and customer support applications.  

**Approach:**  
- Developed a pipeline combining **NLP classification + response generation**.  
- Fine-tuned a transformer-based language model on a labeled dataset of mental-health dialogues.  
- Implemented **multi-class classification** for user states (e.g., Normal, Stress, Anxiety, Depression).  
- Integrated **multi-turn dialogue handling** with conversation state tracking.  
- Evaluated performance with **precision, recall, F1-score**, ensuring reliable predictions.  

**Outcome:**  
Built a proof-of-concept **mental health support chatbot** that detects user intent and provides empathetic responses. Demonstrated skills in **deep learning, text classification, and conversational AI design**. The framework is adaptable to other domains (e.g., customer service or product support).  

**Link:** [Notebook](mental-health-chatbot)  

---

## 🗺️ SF Crime Aware Navigator (Streamlit + Kafka App)
**Problem:** Urban travelers often lack real-time visibility into neighborhood safety. Our team set out to design a tool that could forecast risk on walking routes and surface live incident data.  

**Approach:**  
- I built the **Streamlit app** frontend, integrating routing (OpenRouteService API), map overlays, and interactive controls.  
- Connected a pre-trained ML model for route risk prediction.  
- Integrated **Kafka event producers** to simulate live crime incidents streaming into the app sidebar.  
- Packaged everything into a lightweight UI recruiters and stakeholders could run locally.  

**Outcome:**  
Delivered a working prototype where users can:  
- Enter start & end points → receive a predicted safety score and suggested safer routes.  
- See **live-streaming incidents** update in real time.  
- Explore how data pipelines (Kafka + ML) connect to a user-facing dashboard.  

**Link:** [sf-crime-route-analyzer](https://github.com/sunnysidesk/SF-Crime-Aware-Navigator)
---

## ⚡ Skills Highlight
- **Programming & Data**: Python (pandas, scikit-learn, statsmodels, matplotlib), SQL  
- **Marketing Science**: Marketing Mix Modeling (MMM), incrementality testing, attribution, cohort & funnel analysis  
- **Experimentation & Causal Inference**: A/B tests, geo experiments, uplift modeling, causal inference methods  
- **Machine Learning & NLP**: Predictive modeling (regression, classification, time series), conversational AI (transformer fine-tuning, FAISS similarity search)  
- **Visualization & BI**: Tableau, Looker, Power BI, Streamlit dashboards  
- **Data Pipelines & Tools**: Google Analytics 4 (GA4), Google Search Console (GSC), Supabase, Kafka event streaming



📬 [LinkedIn](https://www.linkedin.com/in/sakshikmr/)   |   [GitHub](https://github.com/sunnysidesk)   |   [Email](sakshim.kmr11@gmail.com)
