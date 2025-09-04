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
├── notebooks/
│ └── movie_recommendation_system.ipynb
│
├── README.md

---

## 🛠 Tech Stack  
- **Language:** Python  
- **Libraries:**  
- `pandas`, `numpy` → Data manipulation    
- `scikit-learn` →  TF-IDF, cosine similarity  
- `matplotlib`, `seaborn` → visualization  
- **Environment:** Jupyter Notebook

--- 

## 📊 Dataset 
- **Source:** [Kaggle – MovieLens dataset](https://www.kaggle.com/datasets/sriharshabsprasad/movielens-dataset-100k-ratings/data)

---

## 🏆 Results  
- **Content-Based Filtering** recommends movies with similar genres and tags.  
- **Collaborative Filtering** finds movies based on rating patterns from similar users.  
- **Hybrid Model** achieved the **best balance**, with higher **Precision@5** and **NDCG@5**, showing improved personalization and diversity in recommendations.  

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/swatighegde/datascience-kit.git
cd CineMatch

# Launch notebook
jupyter notebook movie_recommendation_system.ipynb


