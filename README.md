
# 🎬 Neuraflix - Movie Recommendation System

A data science project built using the TMDB 5000 Movie Dataset, **Neuraflix** explores various movie recommendation techniques including demographic, content-based, and collaborative filtering. The system simulates personalized movie suggestions using real metadata and evaluates different algorithms using industry-standard metrics.

---

## 📌 Project Overview

In an age of overwhelming content choices, Neuraflix aims to recommend relevant and engaging movies based on user preferences and metadata. This system demonstrates:

- 📊 **Exploratory Data Analysis** to understand trends in genres, popularity, and ratings  
- 🔍 **Content-Based Filtering** using TF-IDF and cosine similarity  
- 👥 **Collaborative Filtering** via matrix factorization  
- 🧠 **Deep Learning Techniques** using Autoencoders  
- 🤝 **K-Nearest Neighbors** for overview-based recommendations  
- 📈 **Evaluation with Precision@10, Recall@10, NDCG, RMSE, MAE, and Accuracy**


---

## 🧪 Techniques Implemented

### ✅ Demographic Filtering
- Recommends trending movies based on popularity and vote average

### ✅ Content-Based Filtering
- Uses TF-IDF on movie overviews + cosine similarity  
- Enhanced using Truncated SVD for semantic similarity

### ✅ KNN-Based Filtering
- Uses CountVectorizer + Nearest Neighbors to recommend similar movies

### ✅ Autoencoder (Deep Learning)
- Learns compressed movie representations to recommend based on latent features

### ✅ Collaborative Filtering
- Matrix Factorization using SVD on simulated user-movie rating matrix

---

## 📈 Evaluation Metrics

| Metric         | Value    |
|----------------|----------|
| Precision@10   | 0.0580   |
| Recall@10      | 0.0580   |
| NDCG@10        | 1.0000   |
| Accuracy       | 0.8000   |
| RMSE           | *Low*    |
| MAE            | *Low*    |

> **Note:** Evaluation was performed on 50 simulated users.

---

## 🧠 Key Insights

- Action, Drama, and Comedy are the most common genres
- Less popular movies can still have high vote averages
- Sparse user interaction data limits collaborative filtering performance
- Combining models improves overall recommendation quality

---

## 🚀 Future Enhancements

- Build an interactive **user interface** for personalized recommendations
- Implement **hybrid filtering** (collaborative + content-based)
- Integrate with **real-world user logs** for fine-tuning

---

## 🧑‍💻 Team Members

- Shrey Vyas (sbv2019)  
- Vidhi Ajbani (vba2015)  
- Hemraj Patel (hap8334)  
- Shabad Vaswani (sdv2034)
- Bharath Gera (bm3788)

---

