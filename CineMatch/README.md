# CineMatch – Personalized Movie Recommendation System

## 📌 Overview  
This project implements a **Hybrid Movie Recommendation System** using the **MovieLens dataset**
The system combines **Collaborative Filtering** (user–item rating patterns) and **Content-Based Filtering** (movie metadata such as genres and tags) to deliver more accurate and engaging recommendations.  
By blending both approaches, the hybrid model improves recommendation accuracy, balances personalization, and enhances user engagement.  

---

## 🎯 Objectives  
- Build a **collaborative filtering model** using item-based similarity.  
- Build a **content-based model** using TF-IDF and cosine similarity on movie metadata.  
- Develop a **hybrid model** that averages collaborative and content scores.  
- Compare model performance using **Precision@k** and **NDCG@k** metrics.  
- Deliver personalized and explainable movie suggestions.

---

## 📂 Project Structure
CineMatch
│
├── data/
│ └── links.csv
│ └── movies.csv
│ └── ratings.csv
│ └── tags.csv
│
├── notebook/
│ └── movie_recommendation_system.ipynb
│
├── README.md

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy, Scikit-learn
- Surprise / LightFM (for collaborative filtering)