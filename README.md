# 📍 Finding Underserved Markets with Yelp Data (Taiwanese Restaurants in Philadelphia)

This project identifies business opportunities in niche markets using Yelp data. We focused on Taiwanese restaurants in Philadelphia to detect gaps, uncover customer sentiment, and recommend areas for new restaurant ventures.


## 🧠 Problem Statement  
In competitive markets, entrepreneurs struggle to identify underserved opportunities. Despite strong demand, many businesses fail due to poor market fit or saturation. Our goal: Use data to highlight unmet consumer needs.


## 🎯 Business Objective  
Help restaurant owners and investors make data-driven decisions on:
- Which business categories are underserved?
- Where is demand high but supply low?
- What drives customer satisfaction or dissatisfaction?


## 📊 Dataset and Processing  
**Data Source**: Yelp Open Dataset  
**Tables Used**:  
- `business.json` (metadata, category, location)  
- `review.json` (text, rating)  
- `user.json` (demographics, review history)  
- `checkin.json` (engagement patterns)

**Steps Taken**:
- Merged and cleaned >10GB of data
- Filtered to Taiwanese restaurants in Philadelphia (10 zip codes)
- Removed duplicates and short/noise reviews
- Converted time formats and normalized text


## 🌍 Scope  
- **City**: Philadelphia  
- **Industry**: Restaurants & Cafes  
- **Category**: Taiwanese Cuisine  
- **Total Venues**: 19  
- **Target Population**: 39,000+ Taiwanese residents in Pennsylvania


## 🔍 Key Insights & Techniques  

- **EDA**: Found most reviews from 2017–2018; most-reviewed spot = *Dan Dan*  
- **Sentiment Analysis**: Used Random Forest classifier  
  - Accuracy: **90%**
  - F1-score: ~0.90  
  - Upsampling used to fix class imbalance  
- **Clustering**: K-Means to detect customer segments  
- **Feature Importance**: Total review count, average stars, and location drive customer patterns  
- **Top Words**: Word clouds revealed key themes in good vs. bad reviews


## 💡 Business Opportunities  
- **Underserved Categories**: Hot Pot & BBQ-style Taiwanese restaurants  
- **Strategic Location**: Chinatown (19107) is saturated; consider lesser-known zip codes  
- **Customer Expectations**: Focus on service quality, wait times, and flexible hours  
- **Marketing Tip**: Leverage Yelp engagement patterns to target high-activity customer groups


## 📈 Business Feasibility  
Opening a Taiwanese restaurant in Philly is feasible if you:
- Differentiate with unique offerings and branding  
- Leverage influencer marketing & loyalty programs  
- Focus on operational efficiency and online reviews  
- Consider long-term revenue models (catering, delivery, franchising)


## 🛠 Tools & Tech  
- Python (pandas, scikit-learn, matplotlib)  
- Yelp Open Dataset  
- Random Forest, K-Means  
- Jupyter Notebook for EDA and modeling


## ✅ Outcome  
Delivered a complete market analysis identifying niche restaurant opportunities in Philadelphia. Backed insights with sentiment classification, clustering, and review behavior analysis.
