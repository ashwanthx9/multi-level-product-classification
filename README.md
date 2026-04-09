# 🛍️ Multi-Level Product Classification (Etsy)

## 📌 Overview
This project builds a machine learning pipeline to classify Etsy product listings into **top-level** and **bottom-level categories** using product metadata such as titles, descriptions, and tags.

---

## 🚀 Approach
- Text preprocessing (cleaning, missing value handling)
- Feature extraction using **TF-IDF**
- Derived features (text length, tag count)
- Models evaluated:
  - **XGBoost (best)**
  - Random Forest
  - Logistic Regression
  - Naive Bayes



## 📊 Results

**Top-Level Classification**
- XGBoost: **83% accuracy**, F1: **0.83**

**Bottom-Level Classification**
- XGBoost: **58.9% accuracy**, F1: **0.59**



## 🔍 Key Insights
- XGBoost performs best across both tasks  
- Text features (titles & tags) are highly predictive  
- Fine-grained classification is more challenging due to class imbalance  



## 🛠️ Tech Stack
Python • Scikit-learn • XGBoost • Pandas • NLP (TF-IDF)


## 👤 Author
**Ashwanth Sathish**  
MSc AI, Dublin City University
